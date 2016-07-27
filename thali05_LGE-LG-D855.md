#### Test 77622416b768259_thali05_LGE-LG-D855 Logs


```
--------- beginning of main
07-27 15:04:14.024  6508  6508 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
--------- beginning of system
07-27 15:04:14.476  1033  1907 I ActivityManager: Killing 5805:com.google.android.gm/u0a64 (adj 15): empty #17
07-27 15:04:14.546  1033  1052 W libprocessgroup: failed to open /acct/uid_10064/pid_5805/cgroup.procs: No such file or directory
07-27 15:04:14.824  1818  4746 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
07-27 15:04:14.866  1818  4746 D Icing   : Loaded CLD2 Version V2.0 - 20140131
07-27 15:04:14.919  1818  4746 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
07-27 15:04:14.941   334   432 I ThermalEngine: Thermal-Server: Thermal received msg from  override
07-27 15:04:14.944  3216  6537 I Thermal-Lib: Thermal-Lib-Client: Client request sent
07-27 15:04:15.253  6508  6508 D LgDataFeature: LgDataFeature() Constructor: none
07-27 15:04:15.253  6508  6508 D LgDataFeature: LgDataFeature() Constructor Done, null
07-27 15:04:15.473  6113  6113 I LockScreenSettings: New app installed broadcast received ..
07-27 15:04:15.480  6113  6113 I LockScreenSettings: Number of installed packages  1
07-27 15:04:15.492  6508  6508 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
07-27 15:04:15.555  1033  1973 V SIM_STK : Menu title from STK is T-Mobile
07-27 15:04:15.604  1033  1052 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6554 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
07-27 15:04:15.690  6554  6554 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
07-27 15:04:15.690  6554  6554 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
07-27 15:04:15.764  1033  1973 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6572 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
07-27 15:04:15.766  1033  1973 I ActivityManager: Killing 5852:com.google.android.talk/u0a72 (adj 15): empty #17
07-27 15:04:15.866  1033  1870 W libprocessgroup: failed to open /acct/uid_10072/pid_5852/cgroup.procs: No such file or directory
07-27 15:04:15.975  6572  6572 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
07-27 15:04:16.002  6572  6572 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,07-27 15:04:16.005  6386  6386 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
07-27 15:04:16.064  6386  6386 D PostponalbeReceiver: OasPackageInstalledReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
07-27 15:04:16.065  1033  1051 I ActivityManager: Killing 5640:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
07-27 15:04:16.085  5619  5619 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
07-27 15:04:16.085  5619  5619 W System.err: android.os.DeadObjectException
07-27 15:04:16.085  5619  5619 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
07-27 15:04:16.086  5619  5619 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
07-27 15:04:16.086  5619  5619 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
07-27 15:04:16.086  5619  5619 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
07-27 15:04:16.086  5619  5619 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
07-27 15:04:16.086  5619  5619 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
07-27 15:04:16.086  5619  5619 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-27 15:04:16.086  5619  5619 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-27 15:04:16.086  5619  5619 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-27 15:04:16.086  5619  5619 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-27 15:04:16.086  5619  5619 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 15:04:16.086  5619  5619 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 15:04:16.086  5619  5619 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-27 15:04:16.086  5619  5619 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-27 15:04:16.086  5619  5619 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
07-27 15:04:16.087  5619  5619 W System.err: android.os.DeadObjectException
07-27 15:04:16.087  5619  5619 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
07-27 15:04:16.087  5619  5619 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
07-27 15:04:16.087  5619  5619 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
07-27 15:04:16.087  5619  5619 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
07-27 15:04:16.087  5619  5619 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
07-27 15:04:16.087  5619  5619 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
07-27 15:04:16.087  5619  5619 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-27 15:04:16.087  5619  5619 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-27 15:04:16.087  5619  5619 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-27 15:04:16.087  5619  5619 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-27 15:04:16.087  5619  5619 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 15:04:16.087  5619  5619 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 15:04:16.087  5619  5619 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-27 15:04:16.087  5619  5619 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-27 15:04:16.088  5619  5619 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
07-27 15:04:16.088  5619  5619 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
07-27 15:04:16.186  1033  1888 W libprocessgroup: failed to open /acct/uid_1000/pid_5640/cgroup.procs: No such file or directory
07-27 15:04:16.187  1033  1888 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
07-27 15:04:16.211  5619  5619 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
07-27 15:04:16.211  5619  5619 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
07-27 15:04:16.272  1033  2007 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6595 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
07-27 15:04:16.283  5619  5619 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
07-27 15:04:16.353  6595  6595 D UEI.SmartControl: Quickset Services start...
07-27 15:04:16.360  6595  6595 I UEI.SmartControl: Manufacture = LGE
07-27 15:04:16.360  6595  6595 D UEI.SmartControl: Id = LGNevo
07-27 15:04:16.361  6595  6595 D UEI.SmartControl: File observer start...
07-27 15:04:16.362  6595  6595 E UEI.SmartControl: IR Port is disabled: false
07-27 15:04:16.362  6595  6595 D UEI.SmartControl: Starting file observer...
07-27 15:04:16.363  6595  6595 D UEI.SmartControl: Extracting JNI libs...
07-27 15:04:16.363  6595  6595 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
07-27 15:04:16.443  6593  6593 D AndroidRuntime: 
07-27 15:04:16.443  6593  6593 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-27 15:04:16.447  6593  6593 D AndroidRuntime: CheckJNI is OFF
07-27 15:04:16.453  6595  6595 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
07-27 15:04:16.453  6595  6595 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
07-27 15:04:16.454  6595  6595 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
07-27 15:04:16.488  6595  6595 I UEI.SmartControl: --- Selecting new region: 6
07-27 15:04:16.490  6595  6595 I UEI.SmartControl: Model = LG-D855
07-27 15:04:16.491  6595  6595 D UEI.SmartControl: QS Service created
07-27 15:04:16.507  6595  6595 I UEI.SmartControl: Service initServices...
07-27 15:04:16.511  6595  6595 D UEI.SmartControl: QS start get config
07-27 15:04:16.554  6595  6595 D UEI.SmartControl: Loading JNI Libs...
07-27 15:04:16.610  6593  6593 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-27 15:04:16.616  1033  2007 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-27 15:04:16.626  1944  1960 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
07-27 15:04:16.629  1033  2007 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
07-27 15:04:16.631  1033  2007 D ActivityManager: setTaskToReturnTo : TaskRecord{151f7168 #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
07-27 15:04:16.632  1033  2007 D ActivityManager: setTaskToReturnTo : TaskRecord{151f7168 #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
07-27 15:04:16.635  1033  2007 D WindowStateEx: AppWindowTokenEx init.. 
07-27 15:04:16.637   341   370 E GBMv2   : DFP En is all cleared set to be enabled
07-27 15:04:16.684  1033  2007 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6632 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-27 15:04:16.686  6593  6593 D AndroidRuntime: Shutting down VM
07-27 15:04:16.753  1944  1959 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
07-27 15:04:16.753  1944  1959 D SplitWindowPolicy: topRunningActivity=ActivityInfo{360e19e4 co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
07-27 15:04:16.754  1944  2635 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
07-27 15:04:16.755  1944  2635 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3a3cae4d co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
07-27 15:04:16.833  6632  6632 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
07-27 15:04:16.876  6595  6595 I UEI.SmartControl: Supports setup maps: true
07-27 15:04:16.882  6595  6595 D UEI.SmartControl: QS start statue = true Error code = 0
07-27 15:04:16.882  6595  6595 I UEI.SmartControl: QS version = v2.7.10.1_RC1
07-27 15:04:16.882  6595  6595 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
07-27 15:04:16.882  6595  6595 I UEI.SmartControl: ### init IR Blaster...
07-27 15:04:16.888  6595  6595 D serial_port: Configuring serial port
,07-27 15:04:16.894  6632  6632 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
07-27 15:04:16.896  6595  6595 E UEI.SmartControl: UEIBLaster setting for 616
07-27 15:04:16.896  6595  6595 I UEI.SmartControl: Setting serial record hearder size = 2
07-27 15:04:16.898  6595  6595 I UEI.SmartControl: configuring settings for MAXQ616
07-27 15:04:16.898  6595  6595 I UEI.SmartControl: Get version...
,07-27 15:04:16.900  6632  6632 I LibraryLoader: Loading: webviewchromium
07-27 15:04:16.903  6632  6632 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9585-9588)
07-27 15:04:16.903  6632  6632 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-27 15:04:16.916  6595  6649 D UEI.SmartControl: serial port data available: 21
,07-27 15:04:16.918  6632  6632 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {9826d32}
07-27 15:04:16.919  6632  6632 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-27 15:04:16.920  6632  6632 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
07-27 15:04:16.927  6632  6632 I BrowserStartupController: Initializing chromium process, renderers=0
07-27 15:04:16.927  6632  6632 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-27 15:04:16.938  6632  6632 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
07-27 15:04:16.939  6632  6632 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=33 off=46780 len=2953
07-27 15:04:16.939  6632  6632 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:23 off:229536 len:643667
,07-27 15:04:16.942   315  2148 V AudioPolicyService: registerClient() client 0xb1021ee0, uid 10118
07-27 15:04:16.945  6595  6595 D UEI.SmartControl: MAXQ616 A2-X4 software.
07-27 15:04:16.945  6595  6595 I UEI.SmartControl: IR Blaster version: 256702256704300002
07-27 15:04:16.945  6595  6595 I UEI.SmartControl: QS saving settings...
07-27 15:04:16.946  6595  6595 D UEI.SmartControl: IR Blaster version: 25672567
07-27 15:04:16.951  6632  6632 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-27 15:04:16.951  6632  6632 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-27 15:04:16.951  6632  6632 I Adreno-EGL: Build Date: 12/12/14 금
07-27 15:04:16.951  6632  6632 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-27 15:04:16.951  6632  6632 I Adreno-EGL: Remote Branch: 
07-27 15:04:16.951  6632  6632 I Adreno-EGL: Local Patches: 
07-27 15:04:16.951  6632  6632 I Adreno-EGL: Reconstruct Branch: 
,07-27 15:04:16.953  1033  1098 D BluetoothManagerService: Message: 20
07-27 15:04:16.953  1033  1098 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2a9ec2b2:true
07-27 15:04:16.966  6595  6649 D UEI.SmartControl: serial port data available: 4
,07-27 15:04:16.994  6595  6666 I UEI.SmartControl: Device manager: loading config....
07-27 15:04:16.994  6595  6666 D UEI.SmartControl: ----------- loading internal config...
07-27 15:04:16.994  6595  6595 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
07-27 15:04:16.995  6595  6595 E UEI.SmartControl: Services init done
07-27 15:04:16.995  6595  6595 D UEI.SmartControl: QS Service init finished
,07-27 15:04:16.997  6595  6595 D UEI.SmartControl: QS Service version name: 2.1.91
07-27 15:04:16.997  6595  6595 D UEI.SmartControl: QS Service version code: 201091
07-27 15:04:16.997  6595  6595 D UEI.SmartControl: Service requested: Control
07-27 15:04:16.999  6595  6666 E UEI.SmartControl: Loading SETTINGS...
07-27 15:04:17.002  6595  6666 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
07-27 15:04:17.003  6595  6595 D UEI.SmartControl: Request IControl service: devices are loaded...
07-27 15:04:17.004  1033  1927 I ActivityManager: Killing 5619:com.lge.qremote/u0a112 (adj 15): empty #17
07-27 15:04:17.013  6595  6665 I UEI.SmartControl: Notify AllClients services are ready: 0
07-27 15:04:17.013  6595  6665 D UEI.SmartControl: -----service ready thread exits
,07-27 15:04:17.035  1033  1576 W libprocessgroup: failed to open /acct/uid_10112/pid_5619/cgroup.procs: No such file or directory
,07-27 15:04:17.036  6595  6595 D UEI.SmartControl: Internal service binding...
07-27 15:04:17.060  6632  6663 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,07-27 15:04:17.063  6632  6632 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
07-27 15:04:17.082  6632  6632 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-27 15:04:17.087  6632  6632 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-27 15:04:17.090  6632  6632 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
07-27 15:04:17.092  6632  6632 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
07-27 15:04:17.092  6632  6632 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
07-27 15:04:17.108  6632  6632 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,07-27 15:04:17.117  6632  6632 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-27 15:04:17.117  6632  6632 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-27 15:04:17.154  6632  6678 D OpenGLRenderer: Render dirty regions requested: true
,07-27 15:04:17.155  6632  6678 I OpenGLRenderer: Initialized EGL, version 1.4
07-27 15:04:17.176  6632  6678 D OpenGLRenderer: Enabling debug mode 0
,07-27 15:04:17.188  6632  6632 D Atlas   : Validating map...
07-27 15:04:17.192  1033  2007 D SplitWindow: check instance of lgWin Window{7707c6b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,07-27 15:04:17.233  6632  6676 D LgDataFeature: LgDataFeature() Constructor: none
,07-27 15:04:17.233  6632  6676 D LgDataFeature: LgDataFeature() Constructor Done, null
07-27 15:04:17.348  1033  1099 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +598ms (total +704ms)
07-27 15:04:17.349  1033  1099 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{31612981 u0 com.test.thalitest/.MainActivity t40} time:120034
,07-27 15:04:17.356  6632  6632 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1b877da9 time:120042
07-27 15:04:17.465  6632  6632 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-27 15:04:17.497  6632  6632 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
07-27 15:04:17.497  6632  6632 I chromium: 
,07-27 15:04:17.535  6632  6676 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
07-27 15:04:17.535  6632  6676 I chromium: 
,07-27 15:04:17.645  6632  6692 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435186176
,07-27 15:04:17.659  6632  6692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-27 15:04:17.659  6632  6692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-27 15:04:17.659  6632  6692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-27 15:04:17.659  6632  6692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-27 15:04:17.659  6632  6692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-27 15:04:17.660  6632  6692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26d6821d added. We now have 1 listener(s)
07-27 15:04:17.665  1033  1943 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 15:04:17.668  6632  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
07-27 15:04:17.669  6632  6692 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-27 15:04:17.670  6632  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 15:04:17.671  6632  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-27 15:04:17.678  6632  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-27 15:04:17.678  6632  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-27 15:04:17.678  6632  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-27 15:04:17.678  6632  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
07-27 15:04:17.678  6632  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-27 15:04:17.678  6632  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-27 15:04:17.678  6632  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
07-27 15:04:17.678  6632  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
07-27 15:04:17.678  6632  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
07-27 15:04:17.678  6632  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-27 15:04:17.678  6632  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-27 15:04:17.678  6632  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-27 15:04:17.678  6632  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-27 15:04:17.678  6632  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-27 15:04:17.678  6632  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c647260 added. We now have 1 listener(s)
07-27 15:04:17.678  6632  6692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 15:04:17.683  1033  1544 D WifiService: New client listening to asynchronous messages
07-27 15:04:17.686  6632  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-27 15:04:17.687  6632  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-27 15:04:17.687  6632  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-27 15:04:17.687  6632  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-27 15:04:17.691  6632  6692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 15:04:17.692  1033  1870 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 15:04:17.693  6632  6692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
07-27 15:04:17.704  6632  6692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
07-27 15:04:17.705  6632  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 15:04:17.705  6632  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:17.705  6632  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:17.705  6632  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 15:04:17.705  6632  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 15:04:17.705  6632  6692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 15:04:17.705  6632  6692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 15:04:17.705  6632  6692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-27 15:04:17.705  6632  6692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-27 15:04:17.705  6632  6692 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 15:04:17.708  6632  6692 I io.jxcore.node.LifeCycleMonitor: start: OK
07-27 15:04:17.709  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:17.712  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:17.740  6632  6632 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-27 15:04:18.278   341   372 E GBMv2   : DFP En is all cleared set to be enabled
07-27 15:04:18.278   341   372 E GBMv2   : Set value is all cleared set the max
07-27 15:04:18.278   341   372 I GBMv2   : DFP Enabled. Ignore VFP set
,07-27 15:04:18.421  6632  6695 W jxcore-log: Initializing JXcore engine
07-27 15:04:18.421  6632  6695 W jxcore-log: JXcore engine is ready
,07-27 15:04:18.502  6695  6695 W Thread-767: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10304]" dev="sockfs" ino=10304 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,07-27 15:04:18.502  6695  6695 W Thread-767: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
07-27 15:04:18.502  6695  6695 W Thread-767: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[7644]" dev="sockfs" ino=7644 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
07-27 15:04:18.502  6695  6695 W Thread-767: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
07-27 15:04:18.502  6695  6695 W Thread-767: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[31930]" dev="sockfs" ino=31930 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
07-27 15:04:18.535  6632  6695 W jxcore-log: Starting JXcore engine
,07-27 15:04:18.663  6632  6695 W jxcore-log: Platform android
07-27 15:04:18.663  6632  6695 W jxcore-log: 
07-27 15:04:18.663  6632  6695 W jxcore-log: Process ARCH arm
07-27 15:04:18.663  6632  6695 W jxcore-log: 
,07-27 15:04:18.857  6632  6695 I jxcore-log: JXcore Cordova bridge is ready!
07-27 15:04:18.857  6632  6695 I jxcore-log: 
07-27 15:04:18.857  6632  6695 W jxcore-log: JXcore engine is started
,07-27 15:04:18.862  6632  6692 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
07-27 15:04:18.864  6632  6632 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
07-27 15:04:19.383  6508  6508 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,07-27 15:04:19.392  1033  1927 I ActivityManager: Killing 6229:com.android.calendar/u0a13 (adj 15): empty #17
07-27 15:04:19.467  1033  2034 W libprocessgroup: failed to open /acct/uid_10013/pid_6229/cgroup.procs: No such file or directory
,07-27 15:04:20.359  6508  6538 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-27 15:04:21.995  6595  6667 D UEI.SmartControl: Internal timer expired: 1
07-27 15:04:21.995  6595  6667 D UEI.SmartControl: unbind internal service
,07-27 15:04:22.005  6595  6595 D UEI.SmartControl: Service.onUnbind: IControl
07-27 15:04:22.005  6595  6595 D UEI.SmartControl: Service.onDestroy
07-27 15:04:22.005  6595  6595 D UEI.SmartControl: Lock is in USE false
07-27 15:04:22.005  6595  6595 D UEI.SmartControl: unbind internal service
07-27 15:04:22.006  6595  6595 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@37662a7e
07-27 15:04:22.006  6595  6595 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
07-27 15:04:22.006  6595  6595 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
07-27 15:04:22.006  6595  6595 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
07-27 15:04:22.006  6595  6595 W System.err: 	at com.uei.control.Service.c(Unknown Source)
07-27 15:04:22.006  6595  6595 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
07-27 15:04:22.006  6595  6595 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
07-27 15:04:22.006  6595  6595 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
07-27 15:04:22.006  6595  6595 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
07-27 15:04:22.006  6595  6595 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 15:04:22.006  6595  6595 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-27 15:04:22.006  6595  6595 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-27 15:04:22.006  6595  6595 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 15:04:22.006  6595  6595 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 15:04:22.007  6595  6595 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-27 15:04:22.007  6595  6595 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-27 15:04:22.007  6595  6595 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@37662a7e
07-27 15:04:22.010  6595  6595 D serial_port: close(fd = 25)
,07-27 15:04:22.016  6595  6595 I UEI.SmartControl: Serial port is closed.
07-27 15:04:22.016  6595  6595 I UEI.SmartControl: Serial port is closed.
07-27 15:04:22.017  6595  6595 D UEI.SmartControl: Blaster closed
07-27 15:04:22.017  6595  6595 D UEI.SmartControl: Shut down QS...
07-27 15:04:22.017  6595  6595 D UEI.SmartControl: Stopping QS lib
07-27 15:04:22.017  6595  6595 D UEI.SmartControl: QS lib stop result = true
07-27 15:04:22.017  6595  6595 D UEI.SmartControl: Stopped QS lib
07-27 15:04:22.018  6595  6595 D UEI.SmartControl: Stopped file observer...
07-27 15:04:22.018  6595  6595 D UEI.SmartControl: QS shutdown complete
,07-27 15:04:28.251  1033  1093 I ActivityManager: Waited long enough for: ServiceRecord{24569ebb u0 com.google.android.gms/.wearable.service.WearableService}
,07-27 15:04:29.096  6632  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-27 15:04:29.096  6632  6695 I jxcore-log: 
,07-27 15:04:29.099  6632  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-27 15:04:29.099  6632  6695 I jxcore-log: 
07-27 15:04:29.104  6632  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 15:04:29.104  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:29.104  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:29.104  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 15:04:29.104  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 15:04:29.104  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 15:04:29.104  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 15:04:29.104  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 15:04:29.107  6632  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 15:04:29.110  6632  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-27 15:04:29.110  6632  6695 I jxcore-log: 
,07-27 15:04:29.111  6632  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-27 15:04:29.111  6632  6695 I jxcore-log: 
07-27 15:04:29.442  6632  6695 D ExecuteNativeTests: Running unit tests
,07-27 15:04:29.525  6632  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 15:04:29.525  6632  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@256f8d3e added. We now have 2 listener(s)
07-27 15:04:29.525  1033  1870 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 15:04:29.528  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-27 15:04:29.528  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 15:04:29.528  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 15:04:29.528  6632  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 15:04:29.528  6632  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@297c379f added. We now have 2 listener(s)
07-27 15:04:29.528  6632  6695 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 15:04:29.528  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-27 15:04:29.530  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 15:04:29.535  6632  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 15:04:29.535  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:29.535  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:29.535  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 15:04:29.535  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 15:04:29.535  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 15:04:29.535  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 15:04:29.535  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 15:04:29.536  6632  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 15:04:29.537  6632  6695 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 15:04:29.538  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:29.539  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 15:04:29.541  6632  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-27 15:04:29.543  6632  6695 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-27 15:04:29.543  6632  6695 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-27 15:04:29.544  6632  6695 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
07-27 15:04:29.545  6632  6695 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-27 15:04:29.545  6632  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-27 15:04:29.545  6632  6695 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-27 15:04:29.546  6632  6695 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-27 15:04:29.546  6632  6695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 15:04:29.547  6632  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 15:04:29.547  6632  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 15:04:29.547  6632  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:29.547  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.547  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 15:04:29.547  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 15:04:29.547  6632  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@256f8d3e removed from the list
07-27 15:04:29.547  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:29.547  6632  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@297c379f removed from the list
07-27 15:04:29.547  6632  6695 D io.jxcore.node.ConnectivityMonitor: stop
07-27 15:04:29.547  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.548  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.548  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.548  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:29.548  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:29.548  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:29.548  6632  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@297c379f not in the list
07-27 15:04:29.550  6632  6695 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
07-27 15:04:29.550  6632  6695 I io.jxcore.node.Co,nnectionHelper: stop: Stopping all activities and killing all connections
07-27 15:04:29.550  6632  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 15:04:29.550  6632  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 15:04:29.550  6632  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:29.550  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.550  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.550  6632  6695 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@256f8d3e not in the list,
,07-27 15:04:29.550  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:29.550  6632  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@297c379f not in the list
07-27 15:04:29.550  6632  6695 D io.jxcore.node.ConnectivityMonitor: stop
07-27 15:04:29.550  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-27 15:04:29.550  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.551  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-27 15:04:29.551  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.551  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:29.551  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:29.551  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:29.551  6632  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@297c379f not in the list
07-27 15:04:29.555  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-27 15:04:29.555  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010],
07-27 15:04:29.555  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-27 15:04:29.555  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-27 15:04:29.555  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-27 15:04:29.555  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-27 15:04:29.555  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510],
07-27 15:04:29.555  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-27 15:04:29.555  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-27 15:04:29.555  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,07-27 15:04:29.555  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-27 15:04:29.555  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-27 15:04:29.556  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-27 15:04:29.556  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,07-27 15:04:29.556  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-27 15:04:29.556  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-27 15:04:29.556  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-27 15:04:29.556  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-27 15:04:29.556  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,07-27 15:04:29.556  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-27 15:04:29.556  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-27 15:04:29.556  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-27 15:04:29.556  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-27 15:04:29.556  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,07-27 15:04:29.556  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-27 15:04:29.556  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-27 15:04:29.556  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-27 15:04:29.556  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-27 15:04:29.556  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,07-27 15:04:29.556  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-27 15:04:29.556  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-27 15:04:29.556  6632  6695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 15:04:29.556  6632  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 15:04:29.556  6632  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-27 15:04:29.557  6632  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:29.557  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.557  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.557  6632  6695 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@256f8d3e not in the list,
07-27 15:04:29.557  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:29.557  6632  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@297c379f not in the list
07-27 15:04:29.557  6632  6695 D io.jxcore.node.ConnectivityMonitor: stop
07-27 15:04:29.557  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.557  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.557  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-27 15:04:29.557  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.557  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:29.557  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:29.557  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:29.557  6632  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@297c379f not in the list
07-27 15:04:29.558  6632  6695 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-27 15:04:29.559  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 15:04:29.561  6632  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 15:04:29.561  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:29.561  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:29.561  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 15:04:29.561  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 15:04:29.561  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 15:04:29.561  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 15:04:29.561  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 15:04:29.562  6632  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 15:04:29.562  6632  6695 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 15:04:29.563  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:29.564  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:29.564  6632  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 15:04:29.564  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-27 15:04:29.564  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 15:04:29.564  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-27 15:04:29.567  6632  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-27 15:04:29.567  1033  1943 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 15:04:29.571  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-27 15:04:29.575  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-27 15:04:29.577  6632  6695 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
07-27 15:04:29.577  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-27 15:04:29.578  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 15:04:29.580  6632  6695 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-27 15:04:29.581  6632  6695 I io.jxcore.node.ConnectionHelper: start: OK
07-27 15:04:29.583  6632  6695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 15:04:29.583  6632  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 15:04:29.583  6632  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 15:04:29.583  6632  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:29.583  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.583  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 15:04:29.583  6632  6695 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@256f8d3e not in the list
07-27 15:04:29.583  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:29.583  6632  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@297c379f not in the list
07-27 15:04:29.583  6632  6695 D io.jxcore.node.ConnectivityMonitor: stop
07-27 15:04:29.583  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.583  6632  6695 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-27 15:04:29.585  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 15:04:29.587  6632  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 15:04:29.587  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:29.587  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:29.587  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 15:04:29.587  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 15:04:29.587  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 15:04:29.587  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 15:04:29.587  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 15:04:29.588  6632  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 15:04:29.588  6632  6695 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 15:04:29.589  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:29.591  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:29.591  6632  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 15:04:29.591  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-27 15:04:29.591  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 15:04:29.591  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-27 15:04:29.593  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-27 15:04:29.594  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 15:04:29.595  6632  6695 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-27 15:04:29.595  6632  6695 I io.jxcore.node.ConnectionHelper: start: OK
07-27 15:04:29.596  6632  6695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 15:04:29.596  6632  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 15:04:29.596  6632  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 15:04:29.596  6632  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:29.596  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.596  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 15:04:29.596  6632  6695 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@256f8d3e not in the list
07-27 15:04:29.596  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:29.596  6632  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@297c379f not in the list
07-27 15:04:29.596  6632  6695 D io.jxcore.node.ConnectivityMonitor: stop
07-27 15:04:29.596  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.597  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.597  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.597  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:29.597  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:29.598  6632  6695 D BluetoothLeScanner: could not find callback wrapper
07-27 15:04:29.598  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 15:04:29.598  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:29.598  6632  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@297c379f not in the list
07-27 15:04:29.599  6632  6695 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-27 15:04:29.599  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 15:04:29.602  6632  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 15:04:29.602  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:29.602  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:29.602  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 15:04:29.602  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 15:04:29.602  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 15:04:29.602  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 15:04:29.602  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 15:04:29.603  6632  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 15:04:29.603  6632  6695 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 15:04:29.604  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:29.604  6632  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 15:04:29.604  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-27 15:04:29.604  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 15:04:29.604  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-27 15:04:29.605  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:29.607  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-27 15:04:29.607  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 15:04:29.608  6632  6695 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-27 15:04:29.608  6632  6695 I io.jxcore.node.ConnectionHelper: start: OK
07-27 15:04:29.608  6632  6695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 15:04:29.608  6632  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 15:04:29.608  6632  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 15:04:29.609  6632  6695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 15:04:29.609  6632  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 15:04:29.609  6632  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 15:04:29.609  6632  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:29.609  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.609  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 15:04:29.609  6632  6695 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@256f8d3e not in the list
07-27 15:04:29.609  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:29.609  6632  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@297c379f not in the list
07-27 15:04:29.609  6632  6695 D io.jxcore.node.ConnectivityMonitor: stop
07-27 15:04:29.609  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.610  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.610  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.610  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:29.610  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:29.611  6632  6695 D BluetoothLeScanner: could not find callback wrapper
07-27 15:04:29.611  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 15:04:29.611  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:29.611  6632  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@297c379f not in the list
07-27 15:04:29.612  6632  6695 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
07-27 15:04:29.612  6632  6695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 15:04:29.612  6632  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 15:04:29.612  6632  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 15:04:29.612  6632  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:29.612  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.612  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.612  6632  6695 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@256f8d3e not in the list
07-27 15:04:29.612  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:29.612  6632  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@297c379f not in the list
07-27 15:04:29.612  6632  6695 D io.jxcore.node.ConnectivityMonitor: stop
07-27 15:04:29.612  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.612  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.612  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.612  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.613  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:29.613  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:29.614  6632  6695 D BluetoothLeScanner: could not find callback wrapper
07-27 15:04:29.614  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 15:04:29.614  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:29.614  6632  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@297c379f not in the list
07-27 15:04:29.615  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-27 15:04:29.615  6632  6695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 15:04:29.615  6632  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 15:04:29.615  6632  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 15:04:29.615  6632  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:29.615  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.615  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.615  6632  6695 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@256f8d3e not in the list
07-27 15:04:29.615  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:29.615  6632  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@297c379f not in the list
07-27 15:04:29.615  6632  6695 D io.jxcore.node.ConnectivityMonitor: stop
07-27 15:04:29.615  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.615  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.615  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.615  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.615  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:29.615  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:29.616  6632  6695 D BluetoothLeScanner: could not find callback wrapper
07-27 15:04:29.616  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 15:04:29.616  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:29.616  6632  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@297c379f not in the list
07-27 15:04:29.616  6632  6695 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
07-27 15:04:29.616  6632  6695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 15:04:29.616  6632  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 15:04:29.616  6632  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 15:04:29.617  6632  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:29.617  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.617  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.617  6632  6695 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@256f8d3e not in the list
07-27 15:04:29.617  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:29.617  6632  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@297c379f not in the list
07-27 15:04:29.617  6632  6695 D io.jxcore.node.ConnectivityMonitor: stop
07-27 15:04:29.617  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.617  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.617  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.617  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.618  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:29.618  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:29.618  6632  6695 D BluetoothLeScanner: could not find callback wrapper
07-27 15:04:29.618  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 15:04:29.618  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:29.618  6632  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@297c379f not in the list
07-27 15:04:29.619  6632  6695 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
07-27 15:04:29.619  6632  6695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 15:04:29.619  6632  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 15:04:29.619  6632  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 15:04:29.619  6632  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:29.619  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.619  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.619  6632  6695 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@256f8d3e not in the list
07-27 15:04:29.619  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:29.619  6632  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@297c379f not in the list
07-27 15:04:29.619  6632  6695 D io.jxcore.node.ConnectivityMonitor: stop
07-27 15:04:29.619  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.619  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.619  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.619  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.620  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:29.620  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:29.620  6632  6695 D BluetoothLeScanner: could not find callback wrapper
07-27 15:04:29.620  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 15:04:29.620  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:29.620  6632  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@297c379f not in the list
07-27 15:04:29.621  6632  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-27 15:04:29.622  6632  6695 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-27 15:04:29.622  6632  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-27 15:04:29.622  6632  6695 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-27 15:04:29.622  6632  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-27 15:04:29.622  6632  6695 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-27 15:04:29.622  6632  6695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 15:04:29.622  6632  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 15:04:29.622  6632  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 15:04:29.623  6632  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:29.623  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.623  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.623  6632  6695 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@256f8d3e not in the list
07-27 15:04:29.623  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:29.623  6632  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@297c379f not in the list
07-27 15:04:29.623  6632  6695 D io.jxcore.node.ConnectivityMonitor: stop
07-27 15:04:29.623  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.623  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.623  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.623  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.624  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:29.624  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:29.624  6632  6695 D BluetoothLeScanner: could not find callback wrapper
07-27 15:04:29.624  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 15:04:29.624  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:29.624  6632  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@297c379f not in the list
07-27 15:04:29.625  6632  6695 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-27 15:04:29.625  6632  6695 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
07-27 15:04:29.625  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-27 15:04:29.627  6632  6695 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-27 15:04:29.627  6632  6695 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
07-27 15:04:29.627  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-27 15:04:29.627  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-27 15:04:29.627  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-27 15:04:29.627  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-27 15:04:29.627  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-27 15:04:29.627  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-27 15:04:29.627  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-27 15:04:29.627  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-27 15:04:29.627  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-27 15:04:29.627  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-27 15:04:29.627  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-27 15:04:29.627  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-27 15:04:29.627  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-27 15:04:29.627  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-27 15:04:29.627  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-27 15:04:29.627  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-27 15:04:29.627  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-27 15:04:29.627  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-27 15:04:29.627  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-27 15:04:29.627  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-27 15:04:29.627  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-27 15:04:29.627  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-27 15:04:29.627  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-27 15:04:29.627  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-27 15:04:29.627  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-27 15:04:29.627  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-27 15:04:29.627  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-27 15:04:29.627  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-27 15:04:29.627  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-27 15:04:29.627  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-27 15:04:29.627  6632  6695 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
07-27 15:04:29.628  6632  6695 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-27 15:04:29.628  6632  6695 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
07-27 15:04:29.628  6632  6695 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-27 15:04:29.628  6632  6695 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-27 15:04:29.628  6632  6695 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
07-27 15:04:29.628  6632  6695 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-27 15:04:29.628  6632  6695 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-27 15:04:29.628  6632  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
07-27 15:04:29.630  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
07-27 15:04:29.631  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
07-27 15:04:29.631  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
07-27 15:04:29.631  6632  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
07-27 15:04:29.631  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
07-27 15:04:29.631  6632  6695 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
07-27 15:04:29.631  6632  6695 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-27 15:04:29.632  6632  6695 E io.jxcore.node.ConnectionHelper: connect: Callback is null
07-27 15:04:29.632  6632  6695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 15:04:29.632  6632  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 15:04:29.632  6632  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 15:04:29.633  6632  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:29.633  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.633  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.633  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
07-27 15:04:29.635  6632  6695 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@256f8d3e not in the list
07-27 15:04:29.635  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:29.635  6632  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@297c379f not in the list
07-27 15:04:29.635  6632  6695 D io.jxcore.node.ConnectivityMonitor: stop
07-27 15:04:29.635  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.635  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.635  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.635  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.645  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:29.645  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-27 15:04:29.646  6632  6695 D BluetoothLeScanner: could not find callback wrapper
07-27 15:04:29.646  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 15:04:29.646  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:29.646  6632  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@297c379f not in the list
07-27 15:04:29.648  6632  6709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 831)
07-27 15:04:29.650  6632  6695 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
07-27 15:04:29.650  6632  6695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 15:04:29.650  6632  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 15:04:29.650  6632  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 15:04:29.650  6632  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:29.650  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.650  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.650  6632  6695 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@256f8d3e not in the list
07-27 15:04:29.650  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:29.650  6632  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@297c379f not in the list
07-27 15:04:29.650  6632  6695 D io.jxcore.node.ConnectivityMonitor: stop
07-27 15:04:29.650  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.650  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.650  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.650  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.651  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:29.651  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:29.651  6632  6695 D BluetoothLeScanner: could not find callback wrapper
07-27 15:04:29.651  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 15:04:29.651  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:29.652  6632  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@297c379f not in the list
07-27 15:04:29.652  6632  6695 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
07-27 15:04:29.653  6632  6695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 15:04:29.653  6632  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 15:04:29.653  6632  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 15:04:29.653  6632  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:29.653  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.653  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.653  6632  6695 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@256f8d3e not in the list
07-27 15:04:29.653  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:29.653  6632  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@297c379f not in the list
07-27 15:04:29.653  6632  6695 D io.jxcore.node.ConnectivityMonitor: stop
07-27 15:04:29.653  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.653  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.653  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.653  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.654  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:29.654  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:29.654  6632  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 831
07-27 15:04:29.655  6632  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 831)
07-27 15:04:29.655  6632  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 831)
07-27 15:04:29.655  6632  6695 D BluetoothLeScanner: could not find callback wrapper
07-27 15:04:29.655  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 15:04:29.655  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:29.655  6632  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@297c379f not in the list
07-27 15:04:29.656  6632  6695 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
07-27 15:04:29.656  6632  6695 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
07-27 15:04:29.656  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-27 15:04:29.656  6632  6695 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
07-27 15:04:29.656  6632  6695 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-27 15:04:29.656  6632  6695 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
07-27 15:04:29.656  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-27 15:04:29.656  6632  6695 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
07-27 15:04:29.656  6632  6695 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-27 15:04:29.656  6632  6695 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
07-27 15:04:29.656  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-27 15:04:29.656  6632  6695 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
07-27 15:04:29.657  6632  6695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 15:04:29.657  6632  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 15:04:29.657  6632  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 15:04:29.657  6632  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:29.657  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.657  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.657  6632  6695 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@256f8d3e not in the list
07-27 15:04:29.657  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:29.657  6632  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@297c379f not in the list
07-27 15:04:29.657  6632  6695 D io.jxcore.node.ConnectivityMonitor: stop
07-27 15:04:29.657  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.657  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.657  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.657  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.658  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:29.658  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:29.658  6632  6695 D BluetoothLeScanner: could not find callback wrapper
07-27 15:04:29.658  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 15:04:29.658  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:29.658  6632  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@297c379f not in the list
07-27 15:04:29.659  6632  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:29.659  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.659  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.659  6632  6695 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@256f8d3e not in the list
07-27 15:04:29.659  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:29.659  6632  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@297c379f not in the list
07-27 15:04:29.659  6632  6695 D io.jxcore.node.ConnectivityMonitor: stop
07-27 15:04:29.659  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.659  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.659  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:29.659  6632  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@297c379f not in the list
07-27 15:04:29.659  6632  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:29.659  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.659  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.659  6632  6695 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@256f8d3e not in the list
07-27 15:04:29.659  6632  6695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 15:04:29.659  6632  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 15:04:29.659  6632  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 15:04:29.659  6632  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:29.659  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.659  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.659  6632  6695 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@256f8d3e not in the list
07-27 15:04:29.659  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:29.659  6632  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@297c379f not in the list
07-27 15:04:29.659  6632  6695 D io.jxcore.node.ConnectivityMonitor: stop
07-27 15:04:29.659  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.659  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.659  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.659  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.660  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:29.660  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:29.660  6632  6695 D BluetoothLeScanner: could not find callback wrapper
07-27 15:04:29.660  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 15:04:29.660  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:29.660  6632  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@297c379f not in the list
07-27 15:04:29.661  6632  6695 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-27 15:04:29.661  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 15:04:29.662  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
07-27 15:04:29.662  6632  6695 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-27 15:04:29.662  6632  6695 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-27 15:04:29.663  6632  6632 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-27 15:04:29.663  6632  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-27 15:04:29.663  6632  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-27 15:04:29.664  6632  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:29.664  6632  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-27 15:04:29.664  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-27 15:04:29.664  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-27 15:04:29.664  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.664  6632  6695 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-27 15:04:29.664  6632  6695 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@256f8d3e not in the list
07-27 15:04:29.664  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:29.664  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-27 15:04:29.665  6632  6695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-27 15:04:29.665  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-27 15:04:29.665  6632  6632 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-27 15:04:29.665  6632  6716 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-27 15:04:29.666  6632  6716 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-27 15:04:29.666  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-27 15:04:29.666  6632  6695 D BluetoothLeScanner: could not find callback wrapper
07-27 15:04:29.666  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 15:04:29.667  6632  6695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-27 15:04:29.667  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.667  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.675  6632  6695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-27 15:04:29.675  6632  6632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-27 15:04:29.675  6632  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@297c379f not in the list
07-27 15:04:29.675  6632  6695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 15:04:29.675  6632  6632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-27 15:04:29.675  6632  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 15:04:29.675  6632  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 15:04:29.675  6632  6632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-27 15:04:29.675  6632  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:29.675  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.675  6632  6632 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-27 15:04:29.675  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.675  6632  6695 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@256f8d3e not in the list
07-27 15:04:29.675  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:29.675  6632  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@297c379f not in the list
07-27 15:04:29.675  6632  6695 D io.jxcore.node.ConnectivityMonitor: stop
07-27 15:04:29.675  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.675  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.675  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-27 15:04:29.676  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.676  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:29.676  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:29.676  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:29.676  6632  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@297c379f not in the list
07-27 15:04:29.677  6632  6695 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,07-27 15:04:29.677  6632  6695 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-27 15:04:29.677  6632  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-27 15:04:29.678  6632  6695 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-27 15:04:29.679  6632  6695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 15:04:29.679  6632  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 15:04:29.679  6632  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 15:04:29.679  6632  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:29.679  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.679  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.679  6632  6695 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@256f8d3e not in the list
07-27 15:04:29.679  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:29.679  6632  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@297c379f not in the list,
07-27 15:04:29.679  6632  6695 D io.jxcore.node.ConnectivityMonitor: stop
07-27 15:04:29.679  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.679  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.679  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.679  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.680  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-27 15:04:29.680  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:29.680  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:29.680  6632  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@297c379f not in the list
07-27 15:04:29.680  1033  1973 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 15:04:29.681  1033  1888 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 15:04:29.682  1033  1630 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-27 15:04:29.682  6632  6695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 15:04:29.682  6632  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 15:04:29.682  6632  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 15:04:29.682  6632  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:29.682  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.682  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
07-27 15:04:29.682  6632  6695 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@256f8d3e not in the list
07-27 15:04:29.682  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:29.682  6632  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@297c379f not in the list
07-27 15:04:29.682  6632  6695 D io.jxcore.node.ConnectivityMonitor: stop
07-27 15:04:29.682  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-27 15:04:29.682  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.682  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.682  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.683  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:29.683  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:29.683  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-27 15:04:29.683  6632  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@297c379f not in the list
07-27 15:04:29.684  6632  6695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 15:04:29.684  6632  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 15:04:29.684  6632  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 15:04:29.684  6632  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-27 15:04:29.684  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.684  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.684  6632  6695 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@256f8d3e not in the list
07-27 15:04:29.684  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:29.684  6632  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@297c379f not in the list
07-27 15:04:29.684  6632  6695 D io.jxcore.node.ConnectivityMonitor: stop
,07-27 15:04:29.684  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.684  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.684  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:29.684  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:29.685  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-27 15:04:29.685  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:29.685  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:29.685  6632  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@297c379f not in the list
,07-27 15:04:29.686  6632  6695 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
07-27 15:04:29.686  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-27 15:04:29.686  6632  6695 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
07-27 15:04:29.686  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-27 15:04:29.687  6632  6695 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
07-27 15:04:29.687  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left,
07-27 15:04:29.689  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-27 15:04:29.689  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
07-27 15:04:29.690  6632  6695 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
07-27 15:04:29.690  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-27 15:04:29.691  6632  6695 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
07-27 15:04:29.691  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-27 15:04:29.691  6632  6695 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
07-27 15:04:29.691  6632  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
07-27 15:04:29.691  6632  6695 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
07-27 15:04:29.691  6632  6695 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
07-27 15:04:29.692  6632  6695 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
07-27 15:04:29.692  6632  6695 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
07-27 15:04:29.692  6632  6695 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
07-27 15:04:29.692  6632  6695 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
07-27 15:04:29.693  6632  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-27 15:04:29.693  6632  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3431d184 added. We now have 2 listener(s)
07-27 15:04:29.693  6632  6695 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 15:04:29.694  6632  6695 D BluetoothAdapter: enable(): BT is already enabled..!
07-27 15:04:29.695  1033  1870 D WifiServiceImplEx: setWifiEnabled: true pid=6632, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-27 15:04:29.695  1033  1870 D WifiService: setWifiEnabled: true pid=6632, uid=10118
07-27 15:04:29.695  1033  1870 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-27 15:04:29.696  6632  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 15:04:29.696  6632  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@37249d6d added. We now have 3 listener(s)
07-27 15:04:29.696  6632  6695 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 15:04:29.699  6632  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 15:04:29.699  6632  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@11dc6da2 added. We now have 4 listener(s)
07-27 15:04:29.699  6632  6695 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 15:04:29.701  6632  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-27 15:04:29.702  6632  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@318e3a33 added. We now have 5 listener(s)
07-27 15:04:29.702  6632  6695 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 15:04:29.703  1033  1576 D WifiServiceImplEx: setWifiEnabled: false pid=6632, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-27 15:04:29.703  1033  1576 D WifiService: setWifiEnabled: false pid=6632, uid=10118
,07-27 15:04:29.703  1033  1576 E WifiService: Invoking mWifiStateMachine.setWifiEnabled,
,07-27 15:04:29.720  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-27 15:04:29.720  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-27 15:04:29.720  1033  1033 D Ulp_jni : JNI:system_update. Event-4
07-27 15:04:29.721  1033  1927 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 15:04:29.721  1033  1537 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
07-27 15:04:29.721  1033  1927 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1a9cbf41 mBinding = false
07-27 15:04:29.721  1033  1537 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
07-27 15:04:29.722  1033  1537 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
07-27 15:04:29.722  1033  1537 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
07-27 15:04:29.723  1033  1537 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
07-27 15:04:29.723  1033  1537 E WifiStateMachine: WifiStateMachine: Leaving Connected state
07-27 15:04:29.723  1033  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-27 15:04:29.724  1033  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-27 15:04:29.724  1033  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-27 15:04:29.724  1033  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-27 15:04:29.732  1033  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-27 15:04:29.732  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-27 15:04:29.732  1033  1536 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:29.732  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:29.732  2653  2653 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,07-27 15:04:29.734  1033  1098 D BluetoothManagerService: Message: 2
07-27 15:04:29.735  1033  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-27 15:04:29.735  1033  1537 D WifiNative-wlan0: doBoolean: SET ps 1
07-27 15:04:29.735  1033  1098 D BluetoothManagerService: Sending off request.
07-27 15:04:29.735  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-27 15:04:29.736  1033  1537 D WifiNative-wlan0: SET ps 1: returned true
07-27 15:04:29.736  3886  3902 D LGBluetoothServiceAdapter: [BTUI] Precleanup
07-27 15:04:29.736  1033  2798 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:29.736   309   884 D CommandListener: Clearing all IP addresses on wlan0
07-27 15:04:29.739  3886  3964 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
07-27 15:04:29.739  3886  3964 D BluetoothAdapterProperties: Setting state to 13
07-27 15:04:29.739  3886  3964 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-27 15:04:29.740  3886  3964 D BluetoothAdapterProperties: onBluetoothDisable()
07-27 15:04:29.740  3886  3964 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
07-27 15:04:29.744  3886  3974 D BluetoothAdapterProperties: Scan Mode:20
,07-27 15:04:29.744  3886  3964 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
07-27 15:04:29.745  3886  3964 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
07-27 15:04:29.746  3886  4196 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
07-27 15:04:29.746  3886  4196 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-27 15:04:29.746  3886  4196 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
07-27 15:04:29.746  3886  4196 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
07-27 15:04:29.746  3886  4196 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
07-27 15:04:29.746  3886  4196 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
07-27 15:04:29.746  3886  4196 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
07-27 15:04:29.746  3886  4196 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
07-27 15:04:29.747  3886  4197 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-27 15:04:29.748  3886  4221 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-27 15:04:29.748  3886  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
07-27 15:04:29.748  3886  4219 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-27 15:04:29.748  3886  4073 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
07-27 15:04:29.749  3886  4217 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-27 15:04:29.751  3886  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-27 15:04:29.751  3886  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-27 15:04:29.751  3886  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-27 15:04:29.751  3886  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-27 15:04:29.751  3886  4073 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-27 15:04:29.751  3886  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-27 15:04:29.751  3886  4073 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-27 15:04:29.751  3886  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-27 15:04:29.751  3886  4073 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-27 15:04:29.751  3886  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
07-27 15:04:29.751  3886  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
07-27 15:04:29.751  3886  4073 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
07-27 15:04:29.753  6632  6632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 15:04:29.754  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 15:04:29.754  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:29.754  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:29.754  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 15:04:29.754  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth ,enabled: false
07-27 15:04:29.754  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 15:04:29.754  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 15:04:29.754  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 15:04:29.755  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-27 15:04:29.755  1033  1033 D Ulp_jni : JNI:system_update. Event-4
07-27 15:04:29.756  6632  6632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 15:04:29.756  6632  6632 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-27 15:04:29.760  1033  1098 D BluetoothManagerService: Message: 60
07-27 15:04:29.760  1033  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
07-27 15:04:29.760  1033  1098 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
07-27 15:04:29.772  6632  6709 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
,07-27 15:04:29.773  6632  6709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 831)
07-27 15:04:29.777  1033  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
07-27 15:04:29.777  1033  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
07-27 15:04:29.786  1033  2007 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
07-27 15:04:29.786  1033  2795 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:29.786  1033  2795 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:29.786  1033  2795 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
07-27 15:04:29.786  1033  2795 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:29.786  1033  2795 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
,07-27 15:04:29.801  1033  1093 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6729 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
07-27 15:04:29.802  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-27 15:04:29.804  1033  1033 D WifiHS20: hidePasspointNotification off =false
07-27 15:04:29.805  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:29.805  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 15:04:29.805  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:29.805  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:29.805  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-27 15:04:29.806  1944  1944 V WfdStateTracker: handleWifiStateChangedEvent: 0
07-27 15:04:29.806  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 15:04:29.806  6632  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 15:04:29.806  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:29.806  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:29.806  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 15:04:29.806  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 15:04:29.806  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 15:04:29.806  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 15:04:29.806  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 15:04:29.807  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 15:04:29.807  6632  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-27 15:04:29.807  6632  6695 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 15:04:29.808  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 15:04:29.809  1033  1377 V AlarmManager: RTC_WAKEUP set : Alarm{187039c3 type 0 when 1469624668653 com.android.vending} when 1469624668653
07-27 15:04:29.810  1033  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 15:04:29.810  1033  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 15:04:29.811  1033  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 15:04:29.811  1033  1537 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
07-27 15:04:29.811  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:29.811  1033  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 15:04:29.811  1033  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 15:04:29.811  1033  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 15:04:29.814  1033  1536 D LGWifiP2pService: InactiveState{ when=-5ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:29.814  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:29.814  1033  1536 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wif,i.p2p.LGWifiP2pServiceImpl$P2pStateMachine@d27ad20
07-27 15:04:29.815  1033  1536 D LGWifiP2pService: P2pDisablingState
,07-27 15:04:29.815  1033  1536 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:29.815  1033  1536 D LGWifiP2pService: p2p socket connection lost
07-27 15:04:29.815  1033  1536 D LGWifiP2pService: P2pDisabledState
07-27 15:04:29.815  1033  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 15:04:29.815  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:29.815  1033  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 15:04:29.816  1033  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 15:04:29.816  1033  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
07-27 15:04:29.816  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-27 15:04:29.817  2653  2653 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-27 15:04:29.818  1944  1944 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-27 15:04:29.818  3886  3886 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-27 15:04:29.818  3886  3886 D BluetoothMapService: STATE_TURNING_OFF
07-27 15:04:29.818  3886  3886 V BluetoothMapService: Handler(): got msg=4
07-27 15:04:29.818  3886  3886 D BluetoothMapService: MAP Service closeService in
07-27 15:04:29.818  3886  3886 D BluetoothMapMasInstance: MAP Service shutdown
07-27 15:04:29.818  1033  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-27 15:04:29.818  1033  1537 D WifiNative-wlan0: doBoolean: SET ps 1
07-27 15:04:29.819  1033  1537 D WifiNative-wlan0: SET ps 1: returned true
07-27 15:04:29.819  3886  3886 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-27 15:04:29.819  3886  3886 V BluetoothMapService: MAP Service closeService out
07-27 15:04:29.819  3886  3886 V BtOppService: Receiver DISABLED_ACTION 
07-27 15:04:29.820  3886  3886 I BtOppRfcommListener: stopping Accept Thread
07-27 15:04:29.820  3886  3886 V BtOppRfcommListener: close mBtServerSocket
07-27 15:04:29.820  3886  3886 V BtOppRfcommListener: waiting for thread to terminate
07-27 15:04:29.820  1033  1536 D LGWifiP2pService: P2pDisabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:29.820  1033  1536 D LGWifiP2pService: DefaultState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:29.820  3886  4217 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-27 15:04:29.821  3886  3886 V BtOppRfcommListener: done waiting for thread to terminate
07-27 15:04:29.823  6632  6632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 15:04:29.823  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 15:04:29.823  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:29.823  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:29.823  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 15:04:29.823  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 15:04:29.823  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 15:04:29.823  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 15:04:29.823  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 15:04:29.824  6632  6632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disab,led - will return stored value
07-27 15:04:29.824  6632  6632 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-27 15:04:29.825  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:29.826   309   884 D CommandListener: Clearing all IP addresses on wlan0
,07-27 15:04:29.830  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-27 15:04:29.831   309  6748 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
07-27 15:04:29.832  1033  2795 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
07-27 15:04:29.834  1033  1545 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
07-27 15:04:29.834  1033  1545 D DSQN    : disableDataServiceNotify
07-27 15:04:29.835  1033  1545 D DSQN    : stop dsqn bin
07-27 15:04:29.835  1033  1096 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-27 15:04:29.848  1033  1093 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6749 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,07-27 15:04:29.849  3886  3886 V BtOppService: onDestroy
07-27 15:04:29.851  1033  1537 D WifiNative-p2p0: doBoolean: TERMINATE
07-27 15:04:29.851  1033  1537 D WifiNative-p2p0: TERMINATE: returned true
07-27 15:04:29.851  1033  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-27 15:04:29.851  1033  1537 E WifiStateMachine: useWiFiOffloading() : false
07-27 15:04:29.851  1033  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-27 15:04:29.852  1033  1545 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
07-27 15:04:29.852  1033  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 15:04:29.852  1033  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 15:04:29.852  1033  1545 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 15:04:29.852  1033  1545 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
07-27 15:04:29.853  1033  1545 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
07-27 15:04:29.853  1033  1545 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
07-27 15:04:29.853  1033  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-27 15:04:29.853  1604  2066 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
07-27 15:04:29.853  1033  2795 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:29.853  1033  2795 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:29.853  1033  2795 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
07-27 15:04:29.857  1033  1033 D WifiHS20: hidePasspointNotification off =false
07-27 15:04:29.857  1033  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-27 15:04:29.857  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:29.857  1033  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-27 15:04:29.857  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:29.857  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-27 15:04:29.857  1033  1033 D WifiScanningService: SCAN_AVAILABLE : 1
07-27 15:04:29.857  1033  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-27 15:04:29.857  1033  1033 D RttService: SCAN_AVAILABLE : 1
07-27 15:04:29.857  1033  1557 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:29.85,7  1033  1545 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 15:04:29.858  1033  1033 D WifiHS20: hidePasspointNotification off =false
07-27 15:04:29.858  1033  1545 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 15:04:29.858  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:29.858  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:29.858  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-27 15:04:29.858  1033  1558 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,07-27 15:04:29.858  3886  3886 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
07-27 15:04:29.858  1033  1535 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
07-27 15:04:29.859  1033  1545 D NetworkManagementService: Removing idletimer
07-27 15:04:29.859  1853  1853 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 15:04:29.859  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-27 15:04:29.860  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
07-27 15:04:29.860  1944  1944 D WfdsService: WifiP2pState is changed : false
07-27 15:04:29.861  1033  1033 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
07-27 15:04:29.862  1944  2341 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
07-27 15:04:29.862  1944  2341 D WfdsService: Set the WFDS Monitor: false
07-27 15:04:29.862  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-27 15:04:29.862  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-27 15:04:29.862  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-27 15:04:29.862  1033  1545 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:29.863  1033  1545 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
07-27 15:04:29.864  1033  1535 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
07-27 15:04:29.865  1944  2341 D WfdsMonitor: WFDS Monitor is stopped
07-27 15:04:29.865  1944  2341 D WfdsService: STATE : WfdsDisabledState - enter
07-27 15:04:29.865  1944  2343 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
07-27 15:04:29.865  1944  2719 D CtrlSupplicant: Received on exit socket, terminate
07-27 15:04:29.865  1944  2719 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
07-27 15:04:29.865  1944  2719 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
07-27 15:04:29.865  1944  2719 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
07-27 15:04:29.866  1033  1033 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
07-27 15:04:29.866  1944  2341 W WfdsService: DefaultState - msg [9445378] is not handled
07-27 15:04:29.866  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-27 15:04:29.866  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-27 15:04:29.866  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-27 15:04:29.868  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:29.868  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 15:04:29.869  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 15:04:29.871  1033  1537 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 15:04:29.871  1033  1537 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRIC,TED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,07-27 15:04:29.872  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
07-27 15:04:29.873  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
07-27 15:04:29.875  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 15:04:29.875  1033  1033 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
07-27 15:04:29.875  6632  6632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 15:04:29.875  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 15:04:29.875  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:29.875  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:29.875  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 15:04:29.875  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 15:04:29.875  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 15:04:29.875  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 15:04:29.875  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 15:04:29.876  6632  6632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 15:04:29.876  6632  6632 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-27 15:04:29.877  6632  6632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 15:04:29.877  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 15:04:29.877  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:29.877  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:29.877  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 15:04:29.877  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 15:04:29.877  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 15:04:29.877  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 15:04:29.877  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 15:04:29.877  6632  6632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 15:04:29.877  6632  6632 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-27 15:04:29.907  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-27 15:04:29.907  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,07-27 15:04:29.914  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 15:04:29.918  6749  6749 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-27 15:04:29.918  6749  6749 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
07-27 15:04:29.918  6749  6749 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-27 15:04:29.918  6749  6749 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
07-27 15:04:29.919  6749  6749 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-27 15:04:29.919  6749  6749 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,07-27 15:04:29.927  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-27 15:04:29.928  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 15:04:29.928  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 15:04:29.940  6729  6729 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
07-27 15:04:29.940  6729  6729 W LG Account v2.2: No ProfileInfo entries
07-27 15:04:29.941  6729  6729 I LG Account v2.2: isEnabled: false
07-27 15:04:29.941  6729  6729 I Feature : [Lifetracker]ver: 4.21.112(40211120)
07-27 15:04:29.941  6729  6729 I Feature : [Lifetracker]Country: EU
07-27 15:04:29.941  1033  2015 I art     : Explicit concurrent mark sweep GC freed 37496(1915KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.776ms total 102.495ms
07-27 15:04:29.941  6729  6729 I Feature : [Lifetracker]Operator: OPEN
07-27 15:04:29.941  6729  6729 I Feature : [Lifetracker]Ranking support: false
07-27 15:04:29.941  6729  6729 I Feature : [Lifetracker]Comfort support: false
07-27 15:04:29.941  6729  6729 I Feature : [Lifetracker]Accessory: true
07-27 15:04:29.941  6729  6729 I Feature : [Lifetracker]Health device: true
07-27 15:04:29.941  6729  6729 I Feature : [Lifetracker]Extra Pedometer: false
07-27 15:04:29.941  6729  6729 I Feature : [Lifetracker]Blood glucose device: false
07-27 15:04:29.941  6729  6729 I Feature : [Lifetracker]Device Number: 3
07-27 15:04:29.945  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-27 15:04:29.945  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 15:04:29.946  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 15:04:29.946  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 15:04:29.953  1033  2798 D DhcpStateMachine: StoppedState
07-27 15:04:29.953  1033  2798 D DhcpStateMachine: StoppedState{ when=-134ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:29.953  1033  1537 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
07-27 15:04:29.954  1033  1537 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,07-27 15:04:29.964  6386  6386 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 15:04:29.965  2653  2653 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
07-27 15:04:29.965  2653  2653 I wpa_supplicant: monitor socket send errors count : 1
07-27 15:04:29.965  2653  2653 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1944-2\x00 that cannot receive messages
,07-27 15:04:29.966  1033  2703 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
07-27 15:04:29.966  1033  2703 D WifiMonitor: Dropping event because (p2p0) is stopped
07-27 15:04:29.988  1033  1052 V SIM_STK : Menu title from STK is T-Mobile
,07-27 15:04:29.996  1033  1630 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6769 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
07-27 15:04:30.004  2653  2653 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,07-27 15:04:30.004  2653  2653 W wpa_supplicant: USIM:  scard_deinit function
07-27 15:04:30.005  1033  2703 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
07-27 15:04:30.005  1033  2703 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-27 15:04:30.005  1033  2703 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-27 15:04:30.005  1033  2703 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
07-27 15:04:30.005  1033  2703 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-27 15:04:30.005  1033  2703 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-27 15:04:30.006  1033  1537 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=132677
07-27 15:04:30.006  1033  1098 D Tethering: InitialState.processMessage what=4
07-27 15:04:30.006  1033  1537 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=132678
07-27 15:04:30.006  1033  1537 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=132678  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
07-27 15:04:30.007  1033  1098 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
07-27 15:04:30.007  1033  1537 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=132678  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
07-27 15:04:30.007  1033  1537 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
07-27 15:04:30.007  1033  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-27 15:04:30.017  6749  6749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,07-27 15:04:30.020  3886  3886 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-27 15:04:30.020  3886  3886 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-27 15:04:30.020  3886  3886 V BluetoothPbapReceiver: ***********state = 13
07-27 15:04:30.023  1033  1098 D BluetoothManagerService: Message: 20
07-27 15:04:30.023  1033  1098 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@cff32be:true
07-27 15:04:30.023  3886  3886 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
07-27 15:04:30.023  3886  3886 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-27 15:04:30.024  3886  3886 V BluetoothPbapService: state: 13
07-27 15:04:30.024  3886  3886 V BluetoothPbapService: Pbap Service closeService in
07-27 15:04:30.025  3886  3886 V BluetoothPbapService: successfully stopped pbap service
07-27 15:04:30.025  3886  3886 V BluetoothPbapService: Pbap Service closeService out
07-27 15:04:30.025  2188  2188 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-27 15:04:30.025  3886  3886 V BluetoothPbapService: Pbap Service onDestroy
07-27 15:04:30.025  3886  3886 V BluetoothPbapService: Pbap Service closeService in
07-27 15:04:30.025  3886  3886 V BluetoothPbapService: Pbap Service closeService out
07-27 15:04:30.025  3886  3886 D LGBluetoothPbapAdapter: [BTUI] cleanup
07-27 15:04:30.031  1033  1098 D BluetoothManagerService: Message: 30
,07-27 15:04:30.035  1033  1098 D BluetoothManagerService: Message: 30
07-27 15:04:30.036  6749  6749 D LocalBluetoothProfileManager: Adding local MAP profile
07-27 15:04:30.037  6749  6749 D BluetoothMap: Create BluetoothMap proxy object
07-27 15:04:30.037  1033  1098 D BluetoothManagerService: Message: 30
07-27 15:04:30.040  1033  1098 D BluetoothManagerService: Message: 30
07-27 15:04:30.041  6749  6749 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
07-27 15:04:30.041  6749  6749 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
07-27 15:04:30.049  6749  6749 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,07-27 15:04:30.051  6749  6749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
07-27 15:04:30.056  6749  6749 D DockEventReceiver: finishStartingService: stopping service
,07-27 15:04:30.060  6769  6769 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-27 15:04:30.061  6749  6749 D BluetoothInputDevice: Proxy object connected
07-27 15:04:30.062  6769  6769 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-27 15:04:30.062  6749  6749 D HidProfile: Bluetooth service connected
07-27 15:04:30.062  6769  6769 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-27 15:04:30.063  6749  6749 D BluetoothPan: BluetoothPAN Proxy object connected
07-27 15:04:30.063  6749  6749 D PanProfile: Bluetooth service connected
07-27 15:04:30.064  1033  1630 I ActivityManager: Killing 6194:com.android.providers.calendar/u0a14 (adj 15): empty #17
07-27 15:04:30.064  6749  6749 D BluetoothMap: Proxy object connected
07-27 15:04:30.065  6749  6749 D MapProfile: Bluetooth service connected
07-27 15:04:30.065  6749  6749 D BluetoothMap: getConnectedDevices()
07-27 15:04:30.065  6749  6749 D BluetoothMap: Bluetooth is Not enabled
07-27 15:04:30.065  6749  6749 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
07-27 15:04:30.066  6749  6749 D LGBluetoothAuthorization: [BTUI] cancel All Notification
07-27 15:04:30.086  2653  2653 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
07-27 15:04:30.086  1033  2703 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
07-27 15:04:30.086  1033  2703 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
07-27 15:04:30.086  1033  2703 D WifiMonitor: Disconnecting from the supplicant, no more events
07-27 15:04:30.086  1033  1537 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
,07-27 15:04:30.096  1033  1870 W libprocessgroup: failed to open /acct/uid_10014/pid_6194/cgroup.procs: No such file or directory
07-27 15:04:30.103  6749  6749 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 15:04:30.117  6075  6075 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,07-27 15:04:30.120  1033  2015 I ActivityManager: Killing 2128:com.lge.music/u0a34 (adj 15): empty #17
07-27 15:04:30.128  6749  6749 D LgDataFeature: LgDataFeature() Constructor: none
07-27 15:04:30.128  6749  6749 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-27 15:04:30.133   315   315 V AudioFlinger: 2128 died, releasing its sessions
07-27 15:04:30.133   315   315 V AudioFlinger:  pid 1853 @ 0
07-27 15:04:30.133   315   315 V AudioFlinger:  pid 3422 @ 1
07-27 15:04:30.133   315   315 V AudioFlinger:  pid 3422 @ 2
07-27 15:04:30.136  6749  6749 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 15:04:30.137  6749  6749 D BluetoothPermissionRequest: onReceive
07-27 15:04:30.138  6749  6749 D LGBluetoothAuthorization: [BTUI] cancel All Notification
07-27 15:04:30.156  1033  1052 W libprocessgroup: failed to open /acct/uid_10034/pid_2128/cgroup.procs: No such file or directory
,07-27 15:04:30.164  6749  6749 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-27 15:04:30.168  1033  2015 I ActivityManager: Killing 6422:com.google.android.partnersetup/u0a8 (adj 15): empty #17
07-27 15:04:30.187  1033  1927 W libprocessgroup: failed to open /acct/uid_10008/pid_6422/cgroup.procs: No such file or directory
,07-27 15:04:30.187  3886  3886 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,07-27 15:04:30.188  3886  3886 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
07-27 15:04:30.188  3886  3886 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
07-27 15:04:30.192  1944  1944 D WfdsService: Supplicant Connection state is changed : false
07-27 15:04:30.192  1944  2341 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
07-27 15:04:30.192  1944  2341 D WfdsService: Set the WFDS Monitor: false
07-27 15:04:30.192  1944  2341 D WfdsMonitor: WFDS Monitor is stopped
07-27 15:04:30.192  1033  1537 D WifiOffDelayIfNotUsed: stopMonitoring
07-27 15:04:30.192  1033  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-27 15:04:30.192  1033  1537 E WifiStateMachine: useWiFiOffloading() : false
07-27 15:04:30.192  1033  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-27 15:04:30.194  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
07-27 15:04:30.197  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:30.197  2501  2501 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:30.197  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 15:04:30.199  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:30.201  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
07-27 15:04:30.202  1033  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
07-27 15:04:30.202  1033  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
,07-27 15:04:30.207  3886  3886 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-27 15:04:30.207  3886  3886 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
07-27 15:04:30.209  3886  3886 V BluetoothFtpService: Ftp Service onStartCommand
07-27 15:04:30.209  3886  3886 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-27 15:04:30.209  3886  3886 V BluetoothFtpService: Ftp Service closeService
07-27 15:04:30.210  3886  3886 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
,07-27 15:04:30.260  1033  2007 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6799 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
07-27 15:04:30.263  3886  3886 V BluetoothFtpService: successfully stopped ftp service
,07-27 15:04:30.263  3886  3886 V BluetoothFtpService: Ftp Service onDestroy
07-27 15:04:30.263  3886  3886 V BluetoothFtpService: Ftp Service closeService
07-27 15:04:30.266  3886  3886 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-27 15:04:30.266  3886  3886 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-27 15:04:30.266  3886  3886 V BluetoothSapReceiver: SapReceiver onReceive 
07-27 15:04:30.266  3886  3886 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-27 15:04:30.266  3886  3886 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
07-27 15:04:30.266  3886  3886 V BluetoothSapReceiver: Calling SAP service start service with action = null
07-27 15:04:30.267  3886  3886 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-27 15:04:30.267  3886  3886 V BluetoothSapService: state: 13
07-27 15:04:30.267  3886  3886 V BluetoothSapService: Stopping SAP server process
07-27 15:04:30.268  3886  3886 V BluetoothSapService: Sap Service closeSapService in
07-27 15:04:30.268  3886  3886 V BluetoothSapService: Close listen Socket : 
07-27 15:04:30.268  3886  3886 V BluetoothSapService: Close rfcomm Socket : 
07-27 15:04:30.268  3886  3886 V BluetoothSapService: Close sapd  Socket : 
07-27 15:04:30.317  1033  2007 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6816 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
07-27 15:04:30.319  3886  3886 V BluetoothSapService: Sap Service closeSapService out
07-27 15:04:30.319  3886  3886 V BluetoothSapService: Sap Service onDestroy
07-27 15:04:30.319  3886  3886 V BluetoothSapService: Sap Service closeSapService in
07-27 15:04:30.319  3886  3886 V BluetoothSapService: Close listen Socket : 
07-27 15:04:30.319  3886  3886 V BluetoothSapService: Close rfcomm Socket : 
07-27 15:04:30.319  3886  3886 V BluetoothSapService: Close sapd  Socket : 
07-27 15:04:30.320  3886  3886 V BluetoothSapService: Sap Service closeSapService out
,07-27 15:04:30.334   346   346 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 261us total 17.303ms
,07-27 15:04:30.348  6799  6799 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-27 15:04:30.348   346   346 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 235us total 12.039ms
,07-27 15:04:30.359   346   346 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 221us total 11.008ms
,07-27 15:04:30.373  6799  6799 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
07-27 15:04:30.388  6816  6816 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,07-27 15:04:30.402  1033  1907 I ActivityManager: Killing 6005:com.lge.appbox.client/u0a11 (adj 15): empty #17
,07-27 15:04:30.412  6799  6799 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
07-27 15:04:30.413  6799  6799 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
07-27 15:04:30.413  6799  6799 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
,07-27 15:04:30.414  6799  6799 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
07-27 15:04:30.415  6799  6799 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
07-27 15:04:30.418  6799  6799 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
07-27 15:04:30.427  6799  6799 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
07-27 15:04:30.437  1033  1052 W libprocessgroup: failed to open /acct/uid_10011/pid_6005/cgroup.procs: No such file or directory
,07-27 15:04:30.445  6799  6799 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 15:04:30.450  6799  6799 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-27 15:04:30.478  6799  6799 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,07-27 15:04:30.482  6386  6386 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 15:04:30.484  6799  6799 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
07-27 15:04:30.487  6769  6769 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-27 15:04:30.487  6769  6769 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-27 15:04:30.487  6769  6769 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-27 15:04:30.489  6799  6799 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,07-27 15:04:30.495  6749  6749 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 15:04:30.506  6749  6749 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-27 15:04:30.514  6799  6799 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 15:04:30.514  6799  6799 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-27 15:04:30.516  6799  6799 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,07-27 15:04:30.521  6386  6386 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 15:04:30.524  6769  6769 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-27 15:04:30.525  6769  6769 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-27 15:04:30.525  6769  6769 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-27 15:04:30.529  6749  6749 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 15:04:30.542  6749  6749 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 15:04:30.552  6799  6799 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 15:04:30.552  6799  6799 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 15:04:30.554  6799  6799 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,07-27 15:04:30.607  1033  1889 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6836 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,07-27 15:04:30.722  6769  6769 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-27 15:04:30.727  6749  6749 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,07-27 15:04:30.741  6749  6749 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 15:04:30.753  3886  3974 D bt_hci_bdroid: cleanup
07-27 15:04:30.753  3886  4073 W bt-btif : ag scb idx 1 not allocated
07-27 15:04:30.753  3886  4073 E bt-btif : BTA AG is already disabled, ignoring ...
07-27 15:04:30.753  3886  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-27 15:04:30.754  3886  4073 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-27 15:04:30.754  3886  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-27 15:04:30.754  3886  4073 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-27 15:04:30.754  3886  4078 I bt_lpm  : LPM is already off!!!
07-27 15:04:30.754  3886  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-27 15:04:30.754  3886  4073 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-27 15:04:30.754  3886  4181 I bt_userial_mct: exiting userial_read_thread
07-27 15:04:30.754  3886  4181 D bt_userial_mct: Leaving userial_evt_read_thread()
07-27 15:04:30.754  3886  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-27 15:04:30.754  3886  4073 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-27 15:04:30.754  3886  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-27 15:04:30.754  3886  4073 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-27 15:04:30.754  3886  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-27 15:04:30.754  3886  4073 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-27 15:04:30.754  3886  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-27 15:04:30.754  3886  4073 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-27 15:04:30.754  3886  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-27 15:04:30.754  3886  4073 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-27 15:04:30.754  3886  4073 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-27 15:04:30.754  3886  4073 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-27 15:04:30.754  3886  3974 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
07-27 15:04:30.755  3886  4073 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
07-27 15:04:30.755  3886  4078 I bt_vendor: hw_epilog_process
07-27 15:04:30.755  3886  3974 D bt_hci_bdroid: cleanup Finalizing cleanup
07-27 15:04:30.755  3886  3974 D bt_userial_mct: userial_close
07-27 15:04:30.755  3886  3974 E bt_userial_mct: pthread_join() FAILED result:3
07-27 15:04:30.755  3886  3974 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,07-27 15:04:30.768  6836  6858 W FormManager: Network not available. Please check & try again.
,07-27 15:04:30.774  6836  6860 V FormManager: Network unavailable.
07-27 15:04:30.776  6749  6749 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-27 15:04:30.776  6836  6860 V FormManager: Network unavailable.
07-27 15:04:30.776  6749  6749 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-27 15:04:30.776  6749  6749 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-27 15:04:30.777  6749  6749 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-27 15:04:30.778  6749  6749 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-27 15:04:30.788  6749  6749 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,07-27 15:04:30.791  6749  6749 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
07-27 15:04:30.791  6749  6749 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-27 15:04:30.791  6749  6749 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-27 15:04:30.792  6749  6749 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-27 15:04:30.792  6749  6749 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-27 15:04:30.794  1033  1052 I ActivityManager: Killing 6027:com.android.contacts/u0a19 (adj 15): empty #17
07-27 15:04:30.825  3886  3974 D bt_hci_bdroid: set_power 0
07-27 15:04:30.825  3886  3974 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
07-27 15:04:30.825  3886  3974 I bt_vendor: bluetooth satus is on
07-27 15:04:30.825  3886  3974 I bt_vendor: bt-vendor : resetting BT status
07-27 15:04:30.825  3886  3974 I bt_vendor: Starting hciattach daemon
,07-27 15:04:30.825  3886  3974 I bt_vendor: try to set false,
07-27 15:04:30.827  3886  3974 I bt_vendor: Starting hciattach daemon
,07-27 15:04:30.828  3886  3974 I bt_vendor: try to set false
07-27 15:04:30.829  3886  3974 I bt_vendor: cleanup
07-27 15:04:30.831  3886  4073 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
07-27 15:04:30.832  3886  3974 I GKI_LINUX: GKI_exit_task 0 done
07-27 15:04:30.832  3886  3974 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
07-27 15:04:30.836  3886  3964 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
07-27 15:04:30.844  4320  4320 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
07-27 15:04:30.845  4320  4320 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-27 15:04:30.846  1033  1888 W libprocessgroup: failed to open /acct/uid_10019/pid_6027/cgroup.procs: No such file or directory
,07-27 15:04:30.855  4320  4320 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-27 15:04:30.858  3886  3886 D HeadsetService: Received stop request...Stopping profile...
07-27 15:04:30.864  3886  3886 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
07-27 15:04:30.864  3886  3886 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,07-27 15:04:30.865  3886  3886 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3079ea83
07-27 15:04:30.865  3886  3995 D HeadsetStateMachine: Exit Disconnected: -1
07-27 15:04:30.866  4320  4320 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-27 15:04:30.867  1033  1033 D BluetoothHeadset: Proxy object disconnected
07-27 15:04:30.867  1853  1853 D BluetoothHeadset: Proxy object disconnected
07-27 15:04:30.867  1033  1033 D AudioService: onServiceDisconnected: Bluetooth profile: 1
07-27 15:04:30.867  1853  1853 D BluetoothHeadset: Proxy object disconnected
07-27 15:04:30.867  1853  1853 D BluetoothHeadset: Proxy object disconnected
07-27 15:04:30.868  3886  3886 D A2dpService: Received stop request...Stopping profile...
07-27 15:04:30.868  3886  4058 D A2dpStateMachine: Exit Disconnected: -1
07-27 15:04:30.869  3886  3886 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
07-27 15:04:30.875  4320  6863 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-27 15:04:30.878  3886  3886 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
07-27 15:04:30.878  3886  3886 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
07-27 15:04:30.878  3886  3886 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3079ea83
07-27 15:04:30.878  3886  3964 D BluetoothAdapterState: Stopping profile services that were post enabled
,07-27 15:04:30.879  1033  1033 D BluetoothA2dp: Proxy object disconnected
07-27 15:04:30.880  1033  1033 D AudioService: onServiceDisconnected: Bluetooth profile: 2
07-27 15:04:30.881  4320  6864 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
07-27 15:04:30.881  4320  6864 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-27 15:04:30.882  3886  3886 D HeadsetStateMachine: Unbinding service...
07-27 15:04:30.883  3886  3886 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-27 15:04:30.883  3886  3886 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-27 15:04:30.883  3886  3886 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-27 15:04:30.883  3886  3886 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-27 15:04:30.883  3886  3886 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-27 15:04:30.884  3886  3886 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-27 15:04:30.884  3886  3886 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
07-27 15:04:30.885  3886  3886 D HidService: Received stop request...Stopping profile...
07-27 15:04:30.885  3886  3886 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3079ea83
07-27 15:04:30.890  3886  3886 D HealthService: Received stop request...Stopping profile...
07-27 15:04:30.890  3886  3886 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3079ea83
,07-27 15:04:30.894  6749  6749 D BluetoothInputDevice: Proxy object disconnected
07-27 15:04:30.894  6749  6749 D HidProfile: Bluetooth service disconnected
07-27 15:04:30.894  3886  3886 D PanService: Received stop request...Stopping profile...
07-27 15:04:30.897  3886  3886 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3079ea83
07-27 15:04:30.897  6769  6769 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
07-27 15:04:30.898  3886  3886 D BtGatt.DebugUtils: handleDebugAction() action=null
07-27 15:04:30.898  6769  6769 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-27 15:04:30.898  6769  6769 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-27 15:04:30.898  6749  6749 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-27 15:04:30.898  6749  6749 D PanProfile: Bluetooth service disconnected
07-27 15:04:30.898  3886  3886 D BtGatt.GattService: Received stop request...Stopping profile...
07-27 15:04:30.898  3886  3886 D BtGatt.GattService: stop()
07-27 15:04:30.898  3886  3886 D BtGatt.AdvertiseManager: advertise clients cleared
07-27 15:04:30.899  3886  3886 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3079ea83
07-27 15:04:30.905  3886  3886 D BluetoothMapService: Received stop request...Stopping profile...
07-27 15:04:30.905  3886  3886 D BluetoothMapService: stop()
,07-27 15:04:30.907  3886  3886 D BluetoothMapEmailAppObserver: deinitObservers()
07-27 15:04:30.907  3886  3886 D BluetoothMapEmailAppObserver: removeReceiver()
07-27 15:04:30.908  3886  3886 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3079ea83
07-27 15:04:30.910  3886  3886 I BluetoothA2dpServiceJni: cleanupNative
07-27 15:04:30.910  3886  4061 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
07-27 15:04:30.910  3886  3886 I GKI_LINUX: GKI_exit_task 2 done
07-27 15:04:30.910  3886  3886 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
07-27 15:04:30.911  3886  3886 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-27 15:04:30.911  3886  3886 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-27 15:04:30.911  3886  3886 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-27 15:04:30.911  3886  3886 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-27 15:04:30.911  3886  3886 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-27 15:04:30.912  3886  3886 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-27 15:04:30.912  3886  3886 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-27 15:04:30.912  6749  6749 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-27 15:04:30.913  3886  3886 V BluetoothMapService: Handler(): got msg=4
07-27 15:04:30.913  3886  3886 D BluetoothMapService: MAP Service closeService in
07-27 15:04:30.913  3886  3886 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-27 15:04:30.913  3886  3886 V BluetoothMapService: MAP Service closeService out
07-27 15:04:30.913  3886  3886 D BluetoothMapService: cleanup()
07-27 15:04:30.914  3886  3886 D BluetoothMapService: MAP Service closeService in
07-27 15:04:30.914  3886  3886 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-27 15:04:30.914  3886  3886 V BluetoothMapService: MAP Service closeService out
07-27 15:04:30.914  3886  3964 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
07-27 15:04:30.914  3886  3964 D BluetoothAdapterProperties: Setting state to 10
07-27 15:04:30.914  3886  3964 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
07-27 15:04:30.915  6836  6867 V FormManager: Network unavailable.
07-27 15:04:30.915  1033  1098 D BluetoothManagerService: Message: 60
07-27 15:04:30.915  1033  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
07-27 15:04:30.915  1033  1098 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
07-27 15:04:30.915  1033  1098 D BluetoothHeadset: onBluetoothStateChange: up=false
07-27 15:04:30.915  6836  6866 W FormManager: Network not available. Please check & try again.
07-27 15:04:30.915  3886  3964 I BluetoothAdapterState: Entering OffState
07-27 15:04:30.916  6749  6765 D BluetoothPbap: onBluetoothStateChange: up=false
07-27 15:04:30.917  1853  1869 D BluetoothHeadset: onBluetoothStateChange: up=false
07-27 15:04:30.917  1853  2461 D BluetoothHeadset: onBluetoothStateChange: up=false
07-27 15:04:30.919  1853  1868 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-27 15:04:30.919  6836  6867 V FormManager: Network unavailable.
07-27 15:04:30.920  6749  6764 D BluetoothMap: onBluetoothStateChange: up=false
07-27 15:04:30.921  6749  6765 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-27 15:04:30.922  1033  1098 D BluetoothA2dp: onBluetoothStateChange: up=false
07-27 15:04:30.923  6749  6764 D BluetoothPan: onBluetoothStateChange on: false
07-27 15:04:30.925  1033  1098 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
,07-27 15:04:30.926  1033  1098 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,07-27 15:04:30.931  6749  6749 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 15:04:30.931  1033  1098 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
07-27 15:04:30.931  1033  1098 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
07-27 15:04:30.931  1033  1098 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@1a9cbf41 mBinding = false
07-27 15:04:30.932  1033  1098 D BluetoothManagerService: Sending unbind request.
07-27 15:04:30.937  1033  1098 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
07-27 15:04:30.945  3886  3974 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,07-27 15:04:30.946  3886  3886 I GKI_LINUX: GKI_exit_task 1 done
07-27 15:04:30.946  3886  3886 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
07-27 15:04:30.946  3886  3886 I BluetoothServiceJni: cleanupNative: return from cleanup
07-27 15:04:30.946  3886  3886 I art     : --- WEIRD: removing null entry 246
07-27 15:04:30.946  3886  3886 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
07-27 15:04:30.946  3886  3886 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
07-27 15:04:30.949  6749  6749 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-27 15:04:30.949  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-27 15:04:30.950  6749  6749 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
07-27 15:04:30.950  6749  6749 D LGBluetoothEventManager: [BTUI] clear device connection state
07-27 15:04:30.950  1944  1944 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-27 15:04:30.950  1944  2150 D LGBluetoothAPIService: Message: 2
07-27 15:04:30.951  1944  2150 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@257fdd02 mBinding = false
07-27 15:04:30.952  1944  2150 D LGBluetoothAPIService: Sending unbind request.
07-27 15:04:30.956  1604  1604 D BluetoothAdapter: 179525898: getState() :  mService = null. Returning STATE_OFF
07-27 15:04:30.956  1604  1604 D BluetoothAdapter: 179525898: getState() :  mService = null. Returning STATE_OFF
,07-27 15:04:30.960  3886  3886 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
07-27 15:04:30.965  3886  3886 I art     : System.exit called, status: 0
07-27 15:04:30.966  3886  3886 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
07-27 15:04:30.967  6749  6749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,07-27 15:04:30.976  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:30.977  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:30.986  6749  6749 D DockEventReceiver: finishStartingService: stopping service
,07-27 15:04:30.986  6799  6799 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,07-27 15:04:30.989  6799  6799 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
07-27 15:04:30.989  6799  6799 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
07-27 15:04:30.993   315  2147 V AudioFlinger: 3886 died, releasing its sessions
07-27 15:04:30.993   315  2147 V AudioFlinger:  pid 1853 @ 0
07-27 15:04:30.993   315  2147 V AudioFlinger:  pid 3422 @ 1
07-27 15:04:30.993   315  2147 V AudioFlinger:  pid 3422 @ 2
07-27 15:04:30.993  6749  6749 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,07-27 15:04:31.026  6799  6799 D LgDataFeature: LgDataFeature() Constructor: none
07-27 15:04:31.026  6799  6799 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-27 15:04:31.034  6799  6799 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
07-27 15:04:31.036  6799  6799 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
07-27 15:04:31.036  6799  6799 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
07-27 15:04:31.036  6799  6799 V SoundPool: doLoad: loading sample sampleID=1
07-27 15:04:31.037  6799  6799 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
07-27 15:04:31.039  6799  6878 V SoundPool: Start decode
07-27 15:04:31.039  6799  6878 V MediaPlayer[Native]: decode(31, 10857164, 17813)
07-27 15:04:31.040   315   315 V MediaPlayerService: decode(23, 10857164, 17813)
07-27 15:04:31.040   315   315 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
07-27 15:04:31.040   315   315 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
07-27 15:04:31.040   315   315 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
07-27 15:04:31.040   315   315 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
07-27 15:04:31.040   315   315 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
07-27 15:04:31.040   315   315 V MediaPlayerService: player type = 3
07-27 15:04:31.040   315   315 V AwesomePlayer: AwesomePlayer create()
,07-27 15:04:31.041   315   315 V AwesomePlayer: reset_l() 
,07-27 15:04:31.041   315   315 V AwesomePlayer: cancelPlayerEvents
07-27 15:04:31.041   315   315 V AwesomePlayer: setAudioSink() 
07-27 15:04:31.041   315   315 V AwesomePlayer: reset_l() 
07-27 15:04:31.041   315   315 V AudioCache: notify(0xb16a6b40, 8, 0, 0)
,07-27 15:04:31.041   315   315 V AudioCache: ignored
07-27 15:04:31.041   315   315 V AwesomePlayer: cancelPlayerEvents
07-27 15:04:31.041   315   315 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk,
07-27 15:04:31.041   315   315 V AwesomePlayer: setDataSource_l dataSource
07-27 15:04:31.041   315   315 V LGParserOSAL: SniffLGParser start
,07-27 15:04:31.041   315   315 V LGParserOSAL: MainType:5, SubType=0
07-27 15:04:31.041   315   315 V LGParserOSAL: #### check Mime : application/ogg
07-27 15:04:31.041   315   315 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
,07-27 15:04:31.041   315   315 E MediaExtractor: Use LGExtractor :application/ogg 
07-27 15:04:31.055  1033  1980 I ActivityManager: Process com.android.bluetooth (pid 3886) has died
,07-27 15:04:31.056  1033  1980 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,07-27 15:04:31.068  6595  6595 D UEI.SmartControl: QS Service created,
,07-27 15:04:31.074  6799  6799 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
07-27 15:04:31.074  2188  2188 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-27 15:04:31.085  6799  6799 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
07-27 15:04:31.086  6799  6799 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
07-27 15:04:31.088  6595  6595 I UEI.SmartControl: Service initServices...
07-27 15:04:31.088  6595  6595 D UEI.SmartControl: QS start get config
07-27 15:04:31.091   315   315 V LGParserOSAL: supported mime: application/ogg
07-27 15:04:31.092   315   315 V AwesomePlayer: setDataSource_l() extractor countTracks=1
07-27 15:04:31.092   315   315 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
07-27 15:04:31.092   315   315 V AwesomePlayer: mBitrate = -1 bits/sec
07-27 15:04:31.092   315   315 V AwesomePlayer: AudioTrack Setting
07-27 15:04:31.092   315   315 V AwesomePlayer: AudioTrack Setting channelCount = 2
07-27 15:04:31.092   315   315 V AwesomePlayer: setAudioSource() 
07-27 15:04:31.092   315   315 V MediaPlayerService: prepare
07-27 15:04:31.092   315   315 V AwesomePlayer: prepareAsync_l() 
07-27 15:04:31.092   315   315 V MediaPlayerService: wait for prepare
07-27 15:04:31.092   315  6879 V AwesomePlayer: onPrepareAsyncEvent() 
07-27 15:04:31.092   315  6879 V AwesomePlayer: initAudioDecoder() 
07-27 15:04:31.092   315  6879 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
07-27 15:04:31.092   315  6879 V AudioSystem: isOffloadSupported()
07-27 15:04:31.092   315  6879 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
07-27 15:04:31.092   315  6879 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
07-27 15:04:31.092   315  6879 I AudioFlinger: isAudioPlaybackHookOn() false
07-27 15:04:31.092   315  6879 V AwesomePlayer: getUseOffload() = 0 
07-27 15:04:31.092   315  6879 V OMXCodec: OMXCodec::Create
07-27 15:04:31.092   315  6879 V OMXCodec: findMatchingCodecs()
07-27 15:04:31.092   315  6879 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
07-27 15:04:31.092   315  6879 V OMXCodec: matchingCodecs.size()=1
,07-27 15:04:31.092   315  6879 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
07-27 15:04:31.095   315  6879 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,07-27 15:04:31.095   315  6879 V LGCodecAdapter: LG Codec Adapter start
07-27 15:04:31.095   315  6879 V OMXCodec: OMXCodec Createtor
07-27 15:04:31.095   315  6879 V OMXCodec: setComponentRole
07-27 15:04:31.095   315  6879 V OMXCodec: configureCodec protected=0
07-27 15:04:31.095   315  6879 V LGCodecAdapter: called getLGCodecSpecificData
07-27 15:04:31.095   315  6879 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
07-27 15:04:31.095   315  6879 V LGCodecOSAL: Called LGconfigureCodecMETA
07-27 15:04:31.095   315  6879 V LGCodecOSAL: Called LGconfigureCodecMSG
07-27 15:04:31.095   315  6879 V LGCodecOSAL: Not support LGCodec
,07-27 15:04:31.095   315  6879 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
07-27 15:04:31.095   315  6879 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
07-27 15:04:31.095   315  6879 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
07-27 15:04:31.095   315  6879 I AwesomePlayer: Could not offload audio decode, try pcm offload
07-27 15:04:31.095   315  6879 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
07-27 15:04:31.095   315  6879 V AudioSystem: isOffloadSupported()
07-27 15:04:31.095   315  6879 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
07-27 15:04:31.095   315  6879 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
07-27 15:04:31.095   315  6879 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
07-27 15:04:31.095   315  6879 V OMXCodec: init()
07-27 15:04:31.095   315  6879 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
07-27 15:04:31.095   315  6879 V OMXCodec: allocateBuffers
07-27 15:04:31.095   315  6879 V OMXCodec: allocateBuffersOnPort portIndex=0
07-27 15:04:31.095   315  6879 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
07-27 15:04:31.096   315  6879 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7650 on input port
07-27 15:04:31.096   315  6879 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f77e0 on input port
07-27 15:04:31.096   315  6879 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f78d0 on input port
07-27 15:04:31.096   315  6879 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on input port
07-27 15:04:31.096   315  6879 V OMXCodec: allocateBuffersOnPort portIndex=1
07-27 15:04:31.096   315  6879 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
07-27 15:04:31.096   315  6879 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on output port
07-27 15:04:31.096   315  6879 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
07-27 15:04:31.096   315  6879 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
07-27 15:04:31.096   315  6879 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
07-27 15:04:31.096   315  6879 V OMXCodec: init() mAsyncCompletion wait!!! 
07-27 15:04:31.096   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
07-27 15:04:31.096   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
07-27 15:04:31.097   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
07-27 15:04:31.097   315  6879 V OMXCodec: init() mAsyncCompletion wait!!! 
07-27 15:04:31.097   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
07-27 15:04:31.097   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
07-27 15:04:31.097   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
07-27 15:04:31.097   315  6879 V OMXCodec: init() mAsyncCompletion wait free! 
07-27 15:04:31.097   315  6879 V AwesomePlayer: finishAsyncPrepare_l() 
07-27 15:04:31.097   315  6879 V AudioCache: notify(0xb16a6b40, 5, 0, 0)
07-27 15:04:31.097   315  6879 V AudioCache: ignored
07-27 15:04:31.097   315  6879 V AudioCache: notify(0xb16a6b40, 1, 0, 0)
07-27 15:04:31.097   315  6879 V AudioCache: prepared
07-27 15:04:31.097   315   315 V AudioCache: wait - success
07-27 15:04:31.097   315   315 V MediaPlayerService: start
07-27 15:04:31.097   315   315 V AwesomePlayer: play_l() 
07-27 15:04:31.097   315   315 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchase,file:0
07-27 15:04:31.097   315   315 V AwesomePlayer: createAudioPlayer_l
07-27 15:04:31.097   315   315 V AwesomePlayer: seekAudioIfNecessary_l() 
07-27 15:04:31.097   315   315 V AwesomePlayer: startAudioPlayer_l() 
07-27 15:04:31.097   315   315 D AudioPlayer: start of Playback, useOffload 0
07-27 15:04:31.097   315   315 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
07-27 15:04:31.097   315   315 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
07-27 15:04:31.100   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
07-27 15:04:31.100   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
07-27 15:04:31.100   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
07-27 15:04:31.100   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
07-27 15:04:31.100   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
07-27 15:04:31.100   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
07-27 15:04:31.100   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884528
07-27 15:04:31.100   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-27 15:04:31.100   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884688
07-27 15:04:31.100   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-27 15:04:31.100   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884768
07-27 15:04:31.101   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-27 15:04:31.101   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884848
07-27 15:04:31.101   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-27 15:04:31.101   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
07-27 15:04:31.101   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
07-27 15:04:31.101   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
07-27 15:04:31.101   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
07-27 15:04:31.101   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
07-27 15:04:31.101   315  6881 V OMXCodec: allocateBuffersOnPort portIndex=1
07-27 15:04:31.101   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
07-27 15:04:31.101   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
07-27 15:04:31.101   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
07-27 15:04:31.101   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on output port
07-27 15:04:31.101   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb00 on output port
07-27 15:04:31.101   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
07-27 15:04:31.101   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
,07-27 15:04:31.103   315   315 V AudioCache: open(48000, 2, 0x0, 1, 4)
07-27 15:04:31.103   315   315 V AudioCache: notify(0xb16a6b40, 6, 0, 0)
07-27 15:04:31.103   315   315 V AudioCache: ignored
07-27 15:04:31.103   315   315 V MediaPlayerService: wait for playback complete
07-27 15:04:31.104   315  6882 V AudioCache: write(0xb16e2000, 4096)
07-27 15:04:31.104   315  6882 V AudioCache: memcpy(0xaf004000, 0xb16e2000, 4096)
07-27 15:04:31.105   315  6882 V AudioCache: write(0xb16e2000, 4096)
07-27 15:04:31.105   315  6882 V AudioCache: memcpy(0xaf005000, 0xb16e2000, 4096)
07-27 15:04:31.107  6749  6749 D BluetoothPermissionRequest: onReceive
07-27 15:04:31.107   315  6882 V AudioCache: write(0xb16e2000, 4096)
,07-27 15:04:31.107   315  6882 V AudioCache: memcpy(0xaf006000, 0xb16e2000, 4096)
07-27 15:04:31.107   315  6882 V AudioCache: write(0xb16e2000, 4096)
07-27 15:04:31.107   315  6882 V AudioCache: memcpy(0xaf007000, 0xb16e2000, 4096)
07-27 15:04:31.107   315  6882 V AudioCache: write(0xb16e2000, 4096)
07-27 15:04:31.107   315  6882 V AudioCache: memcpy(0xaf008000, 0xb16e2000, 4096)
07-27 15:04:31.108   315  6882 V AudioCache: write(0xb16e2000, 4096)
07-27 15:04:31.108   315  6882 V AudioCache: memcpy(0xaf009000, 0xb16e2000, 4096)
07-27 15:04:31.110  6749  6749 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,07-27 15:04:31.110  6799  6799 V LGMDMManager: Create singleton instance
07-27 15:04:31.110  6749  6749 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
07-27 15:04:31.113  6749  6749 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,07-27 15:04:31.114   315  6882 V AudioCache: write(0xb16e2000, 4096)
07-27 15:04:31.114   315  6882 V AudioCache: memcpy(0xaf00a000, 0xb16e2000, 4096)
07-27 15:04:31.114   315  6882 V AudioCache: write(0xb16e2000, 4096)
07-27 15:04:31.114   315  6882 V AudioCache: memcpy(0xaf00b000, 0xb16e2000, 4096)
07-27 15:04:31.114   315  6882 V AudioCache: write(0xb16e2000, 4096)
07-27 15:04:31.115   315  6882 V AudioCache: memcpy(0xaf00c000, 0xb16e2000, 4096)
07-27 15:04:31.134   315  6882 V AudioCache: write(0xb16e2000, 4096)
,07-27 15:04:31.134   315  6882 V AudioCache: memcpy(0xaf00d000, 0xb16e2000, 4096)
07-27 15:04:31.135   315  6882 V AudioCache: write(0xb16e2000, 4096)
07-27 15:04:31.135   315  6882 V AudioCache: memcpy(0xaf00e000, 0xb16e2000, 4096)
07-27 15:04:31.136   315  6882 V AudioCache: write(0xb16e2000, 4096)
07-27 15:04:31.136   315  6882 V AudioCache: memcpy(0xaf00f000, 0xb16e2000, 4096)
07-27 15:04:31.136   315  6882 V AudioCache: write(0xb16e2000, 4096)
07-27 15:04:31.136   315  6882 V AudioCache: memcpy(0xaf010000, 0xb16e2000, 4096)
07-27 15:04:31.137   315  6882 V AudioCache: write(0xb16e2000, 4096)
07-27 15:04:31.137   315  6882 V AudioCache: memcpy(0xaf011000, 0xb16e2000, 4096)
07-27 15:04:31.137   315  6882 V AudioCache: write(0xb16e2000, 4096)
07-27 15:04:31.138   315  6882 V AudioCache: memcpy(0xaf012000, 0xb16e2000, 4096)
07-27 15:04:31.138   315  6882 V AudioCache: write(0xb16e2000, 4096)
,07-27 15:04:31.138   315  6882 V AudioCache: memcpy(0xaf013000, 0xb16e2000, 4096)
07-27 15:04:31.139   315  6882 V AudioCache: write(0xb16e2000, 4096)
07-27 15:04:31.139   315  6882 V AudioCache: memcpy(0xaf014000, 0xb16e2000, 4096)
07-27 15:04:31.140   315  6882 V AudioCache: write(0xb16e2000, 4096)
07-27 15:04:31.140   315  6882 V AudioCache: memcpy(0xaf015000, 0xb16e2000, 4096)
07-27 15:04:31.140   315  6882 V AudioCache: write(0xb16e2000, 4096)
07-27 15:04:31.140   315  6882 V AudioCache: memcpy(0xaf016000, 0xb16e2000, 4096)
07-27 15:04:31.141   315  6882 V AudioCache: write(0xb16e2000, 4096)
07-27 15:04:31.141   315  6882 V AudioCache: memcpy(0xaf017000, 0xb16e2000, 4096)
07-27 15:04:31.142   315  6882 V AudioCache: write(0xb16e2000, 4096)
07-27 15:04:31.142   315  6882 V AudioCache: memcpy(0xaf018000, 0xb16e2000, 4096)
07-27 15:04:31.142   315  6882 V AudioCache: write(0xb16e2000, 4096)
07-27 15:04:31.142   315  6882 V AudioCache: memcpy(0xaf019000, 0xb16e2000, 4096)
07-27 15:04:31.143   315  6882 V AudioCache: write(0xb16e2000, 4096)
07-27 15:04:31.143   315  6882 V AudioCache: memcpy(0xaf01a000, 0xb16e2000, 4096)
07-27 15:04:31.144   315  6882 V AudioCache: write(0xb16e2000, 4096)
07-27 15:04:31.144   315  6882 V AudioCache: memcpy(0xaf01b000, 0xb16e2000, 4096)
07-27 15:04:31.145   315  6882 V AudioCache: write(0xb16e2000, 4096)
07-27 15:04:31.145   315  6882 V AudioCache: memcpy(0xaf01c000, 0xb16e2000, 4096)
07-27 15:04:31.148   315  6882 V AudioCache: write(0xb16e2000, 4096)
07-27 15:04:31.148   315  6882 V AudioCache: memcpy(0xaf01d000, 0xb16e2000, 4096)
07-27 15:04:31.148   315  6882 V AudioCache: write(0xb16e2000, 4096)
07-27 15:04:31.149   315  6882 V AudioCache: memcpy(0xaf01e000, 0xb16e2000, 4096)
07-27 15:04:31.149   315  6882 V AudioCache: write(0xb16e2000, 4096)
07-27 15:04:31.149   315  6882 V AudioCache: memcpy(0xaf01f000, 0xb16e2000, 4096)
07-27 15:04:31.150   315  6882 V AudioCache: write(0xb16e2000, 4096)
07-27 15:04:31.150   315  6882 V AudioCache: memcpy(0xaf020000, 0xb16e2000, 4096)
07-27 15:04:31.151  1033  1973 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6883 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
07-27 15:04:31.151   315  6882 V AudioCache: write(0xb16e2000, 4096)
07-27 15:04:31.151   315  6882 V AudioCache: memcpy(0xaf021000, 0xb16e2000, 4096)
07-27 15:04:31.152   315  6882 V AudioCache: write(0xb16e2000, 4096)
07-27 15:04:31.152   315  6882 V AudioCache: memcpy(0xaf022000, 0xb16e2000, 4096)
07-27 15:04:31.153   315  6882 V AudioCache: write(0xb16e2000, 4096)
07-27 15:04:31.153   315  6882 V AudioCache: memcpy(0xaf023000, 0xb16e2000, 4096)
07-27 15:04:31.153   315  6882 V AudioCache: write(0xb16e2000, 4096)
07-27 15:04:31.153   315  6882 V AudioCache: memcpy(0xaf024000, 0xb16e2000, 4096)
07-27 15:04:31.153   315  6882 V AudioCache: write(0xb16e2000, 4096)
07-27 15:04:31.153   315  6882 V AudioCache: memcpy(0xaf025000, 0xb16e2000, 4096)
07-27 15:04:31.155   315  6882 V AudioCache: write(0xb16e2000, 4096)
07-27 15:04:31.155   315  6882 V AudioCache: memcpy(0xaf026000, 0xb16e2000, 4096)
07-27 15:04:31.156   315  6882 V AudioCache: write(0xb16e2000, 4096)
07-27 15:04:31.156   315  6882 V AudioCache: memcpy(0xaf027000, 0xb16e2000, 4096)
07-27 15:04:31.156   315  6882 V AudioCache: write(0xb16e2000, 4096)
07-27 15:04:31.156   315  6882 V AudioCache: memcpy(0xaf028000, 0xb16e2000, 4096)
07-27 15:04:31.157   315  6882 V AudioCache: write(0xb16e2000, 4096)
07-27 15:04:31.157   315  6882 V AudioCache: memcpy(0xaf029000, 0xb16e2000, 4096)
,07-27 15:04:31.157   315  6882 V AudioCache: write(0xb16e2000, 4096)
07-27 15:04:31.158   315  6882 V AudioCache: memcpy(0xaf02a000, 0xb16e2000, 4096)
07-27 15:04:31.158   315  6882 V AudioCache: write(0xb16e2000, 4096)
07-27 15:04:31.158   315  6882 V AudioCache: memcpy(0xaf02b000, 0xb16e2000, 4096)
07-27 15:04:31.158   315  6882 V AudioCache: write(0xb16e2000, 4096)
07-27 15:04:31.158   315  6882 V AudioCache: memcpy(0xaf02c000, 0xb16e2000, 4096)
07-27 15:04:31.159   315  6882 V AudioCache: write(0xb16e2000, 4096)
07-27 15:04:31.159   315  6882 V AudioCache: memcpy(0xaf02d000, 0xb16e2000, 4096)
07-27 15:04:31.159   315  6882 V AudioCache: write(0xb16e2000, 4096)
07-27 15:04:31.159   315  6882 V AudioCache: memcpy(0xaf02e000, 0xb16e2000, 4096)
07-27 15:04:31.160   315  6882 V AudioCache: write(0xb16e2000, 4096)
07-27 15:04:31.160   315  6882 V AudioCache: memcpy(0xaf02f000, 0xb16e2000, 4096)
07-27 15:04:31.160   315  6882 V AudioCache: write(0xb16e2000, 4096)
07-27 15:04:31.160   315  6882 V AudioCache: memcpy(0xaf030000, 0xb16e2000, 4096)
07-27 15:04:31.161   315  6882 V AudioCache: write(0xb16e2000, 4096)
07-27 15:04:31.161   315  6882 V AudioCache: memcpy(0xaf031000, 0xb16e2000, 4096)
07-27 15:04:31.161   315  6882 V AudioCache: write(0xb16e2000, 4096)
07-27 15:04:31.161   315  6882 V AudioCache: memcpy(0xaf032000, 0xb16e2000, 4096)
07-27 15:04:31.162   315  6882 V AudioCache: write(0xb16e2000, 4096)
07-27 15:04:31.162   315  6882 V AudioCache: memcpy(0xaf033000, 0xb16e2000, 4096)
07-27 15:04:31.162   315  6882 V AudioCache: write(0xb16e2000, 4096)
07-27 15:04:31.162   315  6882 V AudioCache: memcpy(0xaf034000, 0xb16e2000, 4096)
07-27 15:04:31.162   315  6882 V AudioCache: write(0xb16e2000, 4096)
07-27 15:04:31.162   315  6882 V AudioCache: memcpy(0xaf035000, 0xb16e2000, 4096)
07-27 15:04:31.162   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
07-27 15:04:31.163   315  6882 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
07-27 15:04:31.163   315  6882 V AwesomePlayer: postAudioEOS() 
07-27 15:04:31.163   315  6882 V AudioCache: write(0xb16e2000, 280)
07-27 15:04:31.163   315  6882 V AudioCache: memcpy(0xaf036000, 0xb16e2000, 280)
07-27 15:04:31.165   315  6879 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
07-27 15:04:31.165   315  6879 V AwesomePlayer: onStreamDone
07-27 15:04:31.165   315  6879 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
07-27 15:04:31.165   315  6879 V AudioCache: notify(0xb16a6b40, 2, 0, 0)
07-27 15:04:31.165   315  6879 V AudioCache: playback complete
07-27 15:04:31.165   315  6879 V AwesomePlayer: pause_l() 
07-27 15:04:31.165   315  6879 V AudioCache: notify(0xb16a6b40, 7, 0, 0)
07-27 15:04:31.165   315   315 V AudioCache: wait - success
07-27 15:04:31.165   315  6879 V AudioCache: ignored
07-27 15:04:31.165   315  6879 V AwesomePlayer: cancelPlayerEvents
07-27 15:04:31.165   315   315 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
07-27 15:04:31.165   315  6879 D AudioPlayer: Pause Playback at 1068125
07-27 15:04:31.166   315   315 V AwesomePlayer: reset_l() 
07-27 15:04:31.166   315   315 V AudioCache: notify(0xb16a6b40, 8, 0, 0)
07-27 15:04:31.166   315   315 V AudioCache: ignored
07-27 15:04:31.166   315   315 V AwesomePlayer: cancelPlayerEvents
07-27 15:04:31.166   315   315 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
07-27 15:04:31.166   315   315 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
07-27 15:04:31.166   315   315 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
07-27 15:04:31.166   315   315 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
07-27 15:04:31.166   315   315 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
07-27 15:04:31.166   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
07-27 15:04:31.166   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
07-27 15:04:31.166   315  68,81 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
07-27 15:04:31.166   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 0
07-27 15:04:31.166   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
07-27 15:04:31.166   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f78d0 on port 0
07-27 15:04:31.166   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
07-27 15:04:31.166   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f77e0 on port 0
07-27 15:04:31.166   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
07-27 15:04:31.166   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7650 on port 0
07-27 15:04:31.166   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
07-27 15:04:31.166   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
07-27 15:04:31.166   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fb00 on port 1
07-27 15:04:31.166   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
07-27 15:04:31.166   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 1
07-27 15:04:31.166   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
07-27 15:04:31.166   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 1
07-27 15:04:31.166   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
07-27 15:04:31.166   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 1
07-27 15:04:31.166   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-27 15:04:31.166   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
07-27 15:04:31.166   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
07-27 15:04:31.166   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
07-27 15:04:31.166   315  6881 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
07-27 15:04:31.166   315   315 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
07-27 15:04:31.166   315   315 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
07-27 15:04:31.167   315   315 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
07-27 15:04:31.167   315   315 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
07-27 15:04:31.167   315   315 D AudioPlayer: AudioPlayer releasing audio source
07-27 15:04:31.167   315   315 D AudioPlayer: AudioPlayer done releasing audio source
07-27 15:04:31.167   315   315 V AwesomePlayer: reset_l() 
07-27 15:04:31.167   315   315 V AwesomePlayer: cancelPlayerEvents
07-27 15:04:31.167   315   315 V AwesomePlayer: ~AwesomePlayer call
07-27 15:04:31.168   315   315 V AwesomePlayer: reset_l() 
07-27 15:04:31.168   315   315 V AwesomePlayer: cancelPlayerEvents
07-27 15:04:31.168  6799  6878 V SoundPool: close(31)
07-27 15:04:31.168  6799  6878 V SoundPool: pointer = 0x9fe8e000, size = 205080, sampleRate = 48000, numChannels = 2
,07-27 15:04:31.191  6799  6799 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
07-27 15:04:31.192  6799  6799 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
07-27 15:04:31.194  6799  6799 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:5524
07-27 15:04:31.200  6883  6883 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
07-27 15:04:31.200  6883  6883 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-27 15:04:31.201  6883  6883 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
07-27 15:04:31.201  6883  6883 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,07-27 15:04:31.214  6883  6883 D BluetoothAdapterApp: Loading JNI Library
,07-27 15:04:31.235  6883  6883 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2dec0fe8 Instance Count = 1
,07-27 15:04:31.239  6883  6883 D BluetoothAdapterApp: onCreate
07-27 15:04:31.253  6883  6883 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,07-27 15:04:31.253  6883  6883 D ProfileConfigQcom: Adding HeadsetService
07-27 15:04:31.253  6883  6883 D ProfileConfigQcom: [BTUI] A2dpService is supported
07-27 15:04:31.253  6883  6883 D ProfileConfigQcom: Adding A2dpService
07-27 15:04:31.253  6883  6883 D ProfileConfigQcom: [BTUI] HidService is supported
07-27 15:04:31.253  6883  6883 D ProfileConfigQcom: Adding HidService
07-27 15:04:31.254  6883  6883 D ProfileConfigQcom: [BTUI] HealthService is supported
07-27 15:04:31.254  6883  6883 D ProfileConfigQcom: Adding HealthService
07-27 15:04:31.254  6883  6883 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
07-27 15:04:31.255  6883  6883 D ProfileConfigQcom: [BTUI] PanService is supported
07-27 15:04:31.255  6883  6883 D ProfileConfigQcom: Adding PanService
07-27 15:04:31.255  6883  6883 D ProfileConfigQcom: [BTUI] GattService is supported
07-27 15:04:31.255  6883  6883 D ProfileConfigQcom: Adding GattService
07-27 15:04:31.255  6883  6883 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
07-27 15:04:31.255  6883  6883 D ProfileConfigQcom: Adding BluetoothMapService
07-27 15:04:31.255  6883  6883 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
07-27 15:04:31.256  6883  6883 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
07-27 15:04:31.260  6749  6749 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
07-27 15:04:31.262  6883  6883 V LGMDMManagerInternal: Create singleton instance
07-27 15:04:31.306  6883  6883 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-27 15:04:31.308  6883  6883 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-27 15:04:31.308  6883  6883 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-27 15:04:31.308  6883  6883 V BluetoothSapReceiver: SapReceiver onReceive 
07-27 15:04:31.309  6883  6883 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-27 15:04:31.309  6883  6883 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,07-27 15:04:31.317  6816  6816 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
07-27 15:04:31.399  6595  6595 I UEI.SmartControl: Supports setup maps: true
,07-27 15:04:31.402  6595  6595 D UEI.SmartControl: QS start statue = true Error code = 0
07-27 15:04:31.402  6595  6595 I UEI.SmartControl: QS version = v2.7.10.1_RC1
07-27 15:04:31.402  6595  6595 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
,07-27 15:04:31.402  6595  6595 I UEI.SmartControl: ### init IR Blaster...
07-27 15:04:31.405  6595  6595 D serial_port: Configuring serial port
07-27 15:04:31.406  6595  6595 E UEI.SmartControl: UEIBLaster setting for 616
07-27 15:04:31.406  6595  6595 I UEI.SmartControl: Setting serial record hearder size = 2
07-27 15:04:31.406  6595  6595 I UEI.SmartControl: configuring settings for MAXQ616
07-27 15:04:31.406  6595  6595 I UEI.SmartControl: Get version...
07-27 15:04:31.424  6595  6903 D UEI.SmartControl: serial port data available: 21
,07-27 15:04:31.450  6595  6595 D UEI.SmartControl: MAXQ616 A2-X4 software.
,07-27 15:04:31.450  6595  6595 I UEI.SmartControl: IR Blaster version: 256702256704300002
07-27 15:04:31.450  6595  6595 I UEI.SmartControl: QS saving settings...
07-27 15:04:31.452  6595  6595 D UEI.SmartControl: IR Blaster version: 25672567
07-27 15:04:31.469  6595  6903 D UEI.SmartControl: serial port data available: 4
,07-27 15:04:31.501  6595  6909 I UEI.SmartControl: Device manager: loading config....
,07-27 15:04:31.502  6595  6909 D UEI.SmartControl: ----------- loading internal config...
07-27 15:04:31.503  6595  6595 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
07-27 15:04:31.506  6595  6595 E UEI.SmartControl: Services init done
07-27 15:04:31.506  6595  6595 D UEI.SmartControl: QS Service init finished
07-27 15:04:31.508  6595  6595 D UEI.SmartControl: QS Service version name: 2.1.91
07-27 15:04:31.508  6595  6595 D UEI.SmartControl: QS Service version code: 201091
07-27 15:04:31.509  6595  6595 D UEI.SmartControl: Service requested: Control
07-27 15:04:31.516  6595  6909 E UEI.SmartControl: Loading SETTINGS...
,07-27 15:04:31.525  6595  6595 D UEI.SmartControl: Request IControl service: devices are loaded...
,07-27 15:04:31.528  6595  6595 D UEI.SmartControl: Internal service binding...
07-27 15:04:31.531  6595  6909 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
07-27 15:04:31.532  6799  6799 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
07-27 15:04:31.535  6595  6611 I UEI.SmartControl: ------ IControl API: 11
07-27 15:04:31.535  6595  6611 D UEI.SmartControl: File observer start...
07-27 15:04:31.535  6595  6611 E UEI.SmartControl: IR Port is disabled: false
07-27 15:04:31.535  6595  6611 D UEI.SmartControl: Starting file observer...
07-27 15:04:31.537  6595  6611 I UEI.SmartControl: Registering callback...
,07-27 15:04:31.538  6595  6908 I UEI.SmartControl: Notify AllClients services are ready: 0
07-27 15:04:31.538  6595  6908 D UEI.SmartControl: -----service ready thread exits
07-27 15:04:31.539  6595  6610 I UEI.SmartControl: ------ IControl API: 19
07-27 15:04:31.540  6595  6610 I UEI.SmartControl: Registering Services Ready callback...
07-27 15:04:31.540  6595  6610 I UEI.SmartControl: Notify client services are ready...
07-27 15:04:31.541  6799  6814 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
07-27 15:04:31.542  6799  6876 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
07-27 15:04:31.542  6799  6876 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
07-27 15:04:31.543  6799  6799 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
07-27 15:04:31.543  6799  6799 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
07-27 15:04:31.543  6595  6611 I UEI.SmartControl: ------ IControl API: 8
07-27 15:04:31.545  6799  6799 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
07-27 15:04:31.545  6799  6799 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
07-27 15:04:31.546  6799  6799 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
07-27 15:04:31.546  6799  6799 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
07-27 15:04:31.547  6799  6799 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
07-27 15:04:31.547  6799  6799 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
07-27 15:04:31.548  6799  6799 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,07-27 15:04:31.553  6799  6799 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
07-27 15:04:31.555  6799  6799 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
07-27 15:04:31.556  6799  6799 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
07-27 15:04:31.556  6799  6799 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
07-27 15:04:31.557  6799  6799 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
07-27 15:04:31.558  6799  6799 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
07-27 15:04:31.559  6799  6799 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
07-27 15:04:31.560  6799  6799 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1469624671559]
07-27 15:04:31.562  6799  6799 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,07-27 15:04:31.567  1033  1889 I ActivityManager: Killing 6051:com.android.gallery3d/u0a27 (adj 15): empty #17
07-27 15:04:31.588  6799  6914 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,07-27 15:04:31.646  1033  1889 I ActivityManager: Killing 6470:com.lge.email/u0a23 (adj 15): empty #18
,07-27 15:04:31.704  1033  1051 W libprocessgroup: failed to open /acct/uid_10027/pid_6051/cgroup.procs: No such file or directory
,07-27 15:04:31.721  1033  1052 W libprocessgroup: failed to open /acct/uid_10023/pid_6470/cgroup.procs: No such file or directory
07-27 15:04:31.726  6799  6799 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,07-27 15:04:31.730  6799  6799 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
07-27 15:04:31.731  6799  6799 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
07-27 15:04:31.732  6799  6799 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
07-27 15:04:31.733  6799  6799 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
07-27 15:04:31.734  6799  6799 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
07-27 15:04:31.735  6799  6799 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
07-27 15:04:31.758  6799  6799 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,07-27 15:04:32.812  1033  2034 D WifiServiceImplEx: setWifiEnabled: true pid=6632, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-27 15:04:32.813  1033  2034 D WifiService: setWifiEnabled: true pid=6632, uid=10118
07-27 15:04:32.814  1033  2034 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-27 15:04:32.839  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-27 15:04:32.840  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-27 15:04:32.840  1033  1033 D Ulp_jni : JNI:system_update. Event-4
,07-27 15:04:32.844  1033  1537 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
07-27 15:04:32.844  1033  1537 I LGFTMITEM: [GET_FTM][id=6], offset=12288
07-27 15:04:32.847  1033  1537 E WifiUtil: wfc_util_ffile_check_copy(): pid[1033] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
07-27 15:04:32.847  1033  1537 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
07-27 15:04:32.847  1033  1537 E WifiUtil: wfc_util_ffile_check_copy(): pid[1033] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
07-27 15:04:32.847  1033  1537 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
07-27 15:04:32.847  1033  1537 I WifiUtil: Intf0MacAddress=C49A027FFB5D
07-27 15:04:32.847  1033  1537 E WifiHW  : unknown target_country: EU , set to default
07-27 15:04:32.847  1033  1537 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
07-27 15:04:32.847  1033  1537 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
07-27 15:04:32.847  1033  1537 I WifiUtil: gEnableBmps=1
07-27 15:04:32.861  1033  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-27 15:04:32.869  1033  1098 D Tethering: MasterInitialState.processMessage what=3
07-27 15:04:32.878  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 15:04:32.883  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:32.883  1033  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-27 15:04:32.889  1033  1092 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-27 15:04:32.889  1033  1098 D Tethering: MasterInitialState.processMessage what=3
07-27 15:04:32.899  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 15:04:32.904  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:32.906  6386  6386 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
07-27 15:04:32.909  6386  6412 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
07-27 15:04:32.921  5751  5751 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,07-27 15:04:32.929  5751  5751 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
07-27 15:04:32.947  2188  2188 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,07-27 15:04:32.971  1033  1092 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-27 15:04:32.972  1033  1092 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:32.973  1033  1092 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:33.030  1033  1630 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6943 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,07-27 15:04:33.109  6943  6943 I AppUp4:AppBoxCP: onCreate
,07-27 15:04:33.110  6943  6943 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,07-27 15:04:33.121  6943  6943 I AppUp4:DB:  setFingerPrint start
,07-27 15:04:33.121  6943  6943 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,07-27 15:04:33.130  6943  6943 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
07-27 15:04:33.131  6943  6943 I AppUp4:DB:  SDK version = 21
,07-27 15:04:33.131  6943  6943 I AppUp4:DB:  beforefinger == newfinger no write in DB
07-27 15:04:33.133  6943  6943 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,07-27 15:04:33.134  6943  6943 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
07-27 15:04:33.134  6943  6943 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
07-27 15:04:33.137  6943  6943 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
,07-27 15:04:33.137  6943  6943 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,07-27 15:04:33.143  6943  6943 I AppUp4:CustModeStarterReceiver: onReceive
07-27 15:04:33.189  6943  6943 D LgDataFeature: LgDataFeature() Constructor: none
07-27 15:04:33.189  6943  6943 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-27 15:04:33.201  6943  6943 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@9826d32
07-27 15:04:33.201  6943  6943 D AppUp4:CustFacade: isCustomizationCompleted : false
07-27 15:04:33.201  6943  6943 D AppUp4:CustFacade: isPhone : true
07-27 15:04:33.202  6943  6943 D AppUp4:CustModeStarterReceiver: begin check event
07-27 15:04:33.202  6943  6943 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
07-27 15:04:33.203  6943  6943 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
07-27 15:04:33.203  6943  6961 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
07-27 15:04:33.204  6943  6961 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
07-27 15:04:33.204  6943  6961 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
07-27 15:04:33.209  1033  1051 I ActivityManager: Killing 6309:com.android.defcontainer/u0a4 (adj 15): empty #17
,07-27 15:04:33.267  1033  2007 W libprocessgroup: failed to open /acct/uid_10004/pid_6309/cgroup.procs: No such file or directory
07-27 15:04:33.269  4320  4320 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
07-27 15:04:33.270  4320  4320 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,07-27 15:04:33.276  4320  4320 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-27 15:04:33.281  4320  4320 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-27 15:04:33.297  4320  6964 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,07-27 15:04:33.301  4320  6965 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
07-27 15:04:33.301  4320  6965 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-27 15:04:33.342  1033  1927 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6966 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,07-27 15:04:33.415  6966  6966 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-27 15:04:33.416  6966  6966 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,07-27 15:04:33.418  6966  6966 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-27 15:04:33.419  6966  6966 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
07-27 15:04:33.515  6966  6966 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,07-27 15:04:33.535  6966  6966 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,07-27 15:04:33.585  6966  6966 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-27 15:04:33.623  6966  6966 D LgDataFeature: LgDataFeature() Constructor: none
,07-27 15:04:33.623  6966  6966 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-27 15:04:33.747  1033  1098 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
07-27 15:04:33.747  6966  6966 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,07-27 15:04:33.752  1033  1098 D Tethering: InitialState.processMessage what=4
07-27 15:04:33.757  1033  1098 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
07-27 15:04:33.758   309   884 D SoftapController: Softap fwReload - Ok
07-27 15:04:33.765  1033  1537 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (913ms)
,07-27 15:04:33.767   309   884 D CommandListener: Setting iface cfg
07-27 15:04:33.767   309   884 D CommandListener: Trying to bring down wlan0
07-27 15:04:33.771   309   884 D CommandListener: Clearing all IP addresses on wlan0
,07-27 15:04:33.791  1033  1537 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
07-27 15:04:33.796  1033  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-27 15:04:33.796  1033  1537 E WifiStateMachine: useWiFiOffloading() : false
07-27 15:04:33.796  1033  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-27 15:04:33.797  1033  1537 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
07-27 15:04:33.797  1033  1537 D WifiMonitor: connecting to supplicant
07-27 15:04:33.799  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 15:04:33.800  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,07-27 15:04:33.792  7001  7001 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 15:04:33.792  7001  7001 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 15:04:33.804  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
07-27 15:04:33.808  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:33.809  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:33.828  3422  3422 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
07-27 15:04:33.828  3422  3422 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
07-27 15:04:33.828  3422  3422 I LgeMiscReceiver: networkInfo.isConnected() = false
,07-27 15:04:33.844  7001  7001 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-27 15:04:33.876  6966  6966 I HubEmail: JNI_OnLoad()
07-27 15:04:33.876  6966  6966 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-27 15:04:33.876  6966  6966 I HubEmail: registerNatives()
07-27 15:04:33.876  6966  6966 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-27 15:04:33.876  6966  6966 I HubEmail: registerNativeMethods()
07-27 15:04:33.876  6966  6966 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-27 15:04:33.876  6966  6966 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
07-27 15:04:33.878  1033  2007 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7017 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,07-27 15:04:33.891  6836  7004 W FormManager: Network not available. Please check & try again.
07-27 15:04:33.894  7001  7001 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-27 15:04:33.894  7001  7001 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
07-27 15:04:33.899  6836  7005 V FormManager: Network unavailable.
07-27 15:04:33.900  6966  7027 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:33.902  6836  7005 V FormManager: Network unavailable.
07-27 15:04:33.909  1033  1889 I ActivityManager: Killing 6113:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,07-27 15:04:33.978  7001  7001 I wpa_supplicant: rfkill: Cannot open RFKILL control device
07-27 15:04:33.989  1033  2007 W libprocessgroup: failed to open /acct/uid_10080/pid_6113/cgroup.procs: No such file or directory
,07-27 15:04:33.998  1604  1604 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-27 15:04:33.999  1604  1604 I [SystemUI]LGPowerUI: On Skip Timer : true
07-27 15:04:34.001  1033  1544 D WifiController: battery changed pluggedType: 2
07-27 15:04:34.002  1604  1604 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 296
07-27 15:04:34.002  1604  1604 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
,07-27 15:04:34.003  1944  2124 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-27 15:04:34.004  1944  2124 D LEDHandler: Battery Level Remaining: 100%
07-27 15:04:34.004  1944  2124 D LEDHandler: Battery Temp: 296, mChargingStatus=5, mChargingStop=false
07-27 15:04:34.006  1604  1604 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-27 15:04:34.013  6572  6572 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-27 15:04:34.018  7001  7001 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,07-27 15:04:34.023  7001  7001 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
07-27 15:04:34.026  1033  1537 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
07-27 15:04:34.026  1033  1537 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
07-27 15:04:34.027  1033  1537 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
07-27 15:04:34.027  1033  7036 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
07-27 15:04:34.027  1033  7036 D WifiMonitor: Dropping event because (p2p0) is stopped
07-27 15:04:34.027  1033  1537 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
07-27 15:04:34.028  1033  1537 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
07-27 15:04:34.028  1033  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-27 15:04:34.028  1033  1537 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
07-27 15:04:34.029  1033  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-27 15:04:34.029  1033  1537 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
07-27 15:04:34.029  1033  1537 D WifiNative-wlan0: doString: [DRIVER MACADDR]
07-27 15:04:34.030  1033  1537 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
,07-27 15:04:34.030  1033  1537 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
07-27 15:04:34.030  1033  1537 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
07-27 15:04:34.031  1033  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-27 15:04:34.031  1033  1537 E WifiStateMachine: useWiFiOffloading() : false
07-27 15:04:34.031  1033  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-27 15:04:34.031  1033  1537 D WifiNative-wlan0: doBoolean: SET update_config 1
07-27 15:04:34.032  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:34.032  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:34.032  1033  1537 D WifiNative-wlan0: SET update_config 1: returned true
07-27 15:04:34.032  1033  1537 D WifiConfigStore: Loading config and enabling all networks 
07-27 15:04:34.032  1033  1537 D WifiNative-wlan0: doString: [LIST_NETWORKS]
07-27 15:04:34.032  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:34.033  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:34.033  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-27 15:04:34.033  1033  1537 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
07-27 15:04:34.034  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 15:04:34.035  1944  1944 D WfdService: Waiting for WifiP2p enabling
07-27 15:04:34.035  1033  7036 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
07-27 15:04:34.036  7001  7001 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
07-27 15:04:34.036  1033  7036 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
07-27 15:04:34.036  1033  7036 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
07-27 15:04:34.036  1033  7036 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
07-27 15:04:34.036  1033  7036 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
07-27 15:04:34.036  1033  7036 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
07-27 15:04:34.037  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
07-27 15:04:34.038  1033  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
07-27 15:04:34.038  6632  6632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 15:04:34.038  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 15:04:34.038  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:34.038  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:34.038  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 15:04:34.038  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 15:04:34.038  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 15:04:34.038  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 15:04:34.038  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 15:04:34.038  6632  6632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Bluetoo,thManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 15:04:34.039  6632  6632 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-27 15:04:34.039  6632  6632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 15:04:34.039  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 15:04:34.039  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:34.039  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:34.039  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 15:04:34.039  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 15:04:34.039  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 15:04:34.039  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 15:04:34.039  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 15:04:34.039  6632  6632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 15:04:34.039  6632  6632 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-27 15:04:34.041  1033  1537 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,07-27 15:04:34.053  1033  1537 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
07-27 15:04:34.053  1033  1537 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
07-27 15:04:34.054  1033  1537 D WifiStateMachine: enableVerboseLogging : level 2
07-27 15:04:34.054  1033  1537 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
07-27 15:04:34.055  1033  1537 D WifiNative-wlan0: SET device_name g3_global_com: returned true
07-27 15:04:34.055  1033  1537 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
07-27 15:04:34.055  1033  1537 D WifiNative-wlan0: SET manufacturer LGE: returned true
,07-27 15:04:34.055  1033  1537 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
07-27 15:04:34.056  1033  1537 D WifiNative-wlan0: SET model_name LG-D855: returned true
07-27 15:04:34.056  1033  1537 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
07-27 15:04:34.056  1033  1537 D WifiNative-wlan0: SET model_number LG-D855: returned true
07-27 15:04:34.056  1033  1537 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
07-27 15:04:34.056  1033  1537 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
07-27 15:04:34.056  1033  1537 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
07-27 15:04:34.057  1033  1537 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
07-27 15:04:34.057  1033  1537 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
07-27 15:04:34.057  1033  1537 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
07-27 15:04:34.058  1033  1537 D WifiStateMachine: Setting OUI to DA-A1-19
07-27 15:04:34.058  1033  1537 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
07-27 15:04:34.058  1033  1537 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
07-27 15:04:34.058  1944  1944 D WfdsService: Supplicant Connection state is changed : true
07-27 15:04:34.058  1033  1537 D WifiNative-HAL: Setting external_sim to 1
07-27 15:04:34.058  1033  1537 D WifiNative-wlan0: doBoolean: SET external_sim 1
,07-27 15:04:34.058  1944  2341 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
07-27 15:04:34.058  1944  2341 D WfdsService: Set the WFDS Monitor: true
07-27 15:04:34.058  1944  2341 D WfdsMonitor: WfdsMonitorThread create
07-27 15:04:34.059  1944  2341 D WfdsMonitor: WFDS Monitor is created and started
07-27 15:04:34.059  1944  2341 D WfdsService: WiFi: Supplicant connection re-established
07-27 15:04:34.059  1033  1537 D WifiNative-wlan0: SET external_sim 1: returned true
07-27 15:04:34.059  1033  1537 I WifiNative-HAL: startHal
07-27 15:04:34.059  1033  1537 D wifi    : setting scan oui 0xaf66e0c0
07-27 15:04:34.060  1033  1537 D WifiStateMachine: Setting OUI to DA-A1-19
07-27 15:04:34.060  1033  1537 I WifiNative-HAL: startHal
07-27 15:04:34.060  1033  1537 D wifi    : setting scan oui 0xaf66e0c0
07-27 15:04:34.060  1033  1537 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
07-27 15:04:34.060  1944  7037 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
07-27 15:04:34.061  1944  7037 E CtrlSupplicant: Succeed to open control connection
07-27 15:04:34.061  1033  1537 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
07-27 15:04:34.061  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
07-27 15:04:34.061  1944  7037 E CtrlSupplicant: Succeed to open monitor connection
07-27 15:04:34.061  7001  7001 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
07-27 15:04:34.061  1944  7037 D WfdsMonitor: Supplicant connection established
07-27 15:04:34.061  1944  2341 D WfdsService: Connected to the supplicant for wfds
07-27 15:04:34.062  1033  1537 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
07-27 15:04:34.062  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
07-27 15:04:34.062  7001  7001 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
07-27 15:04:34.062  1033  1537 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
07-27 15:04:34.062  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
07-27 15:04:34.063  7001  7001 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
07-27 15:04:34.063  1033  1537 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
07-27 15:04:34.063  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
07-27 15:04:34.063  7001  7001 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
07-27 15:04:34.064  1033  1537 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
07-27 15:04:34.064  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
07-27 15:04:34.064  7001  7001 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
07-27 15:04:34.064  1033  1537 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
07-27 15:04:34.064  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
07-27 15:04:34.064  7001  7001 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
07-27 15:04:34.065  1033  1537 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
07-27 15:04:34.065  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
,07-27 15:04:34.065  7001  7001 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
07-27 15:04:34.065  1033  1537 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
07-27 15:04:34.066  1033  1537 E WifiNative: : [136,737,411 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
07-27 15:04:34.066  1033  1537 D WifiNative-wlan0: doBoolean: RECONNECT
07-27 15:04:34.067  1033  1537 D WifiNative-wlan0: RECONNECT: returned true
07-27 15:04:34.067  1033  1537 D WifiNative-wlan0: doString: [STATUS]
07-27 15:04:34.068  1033  7036 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
07-27 15:04:34.068  1033  7036 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,07-27 15:04:34.068  1033  1537 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
07-27 15:04:34.068  1033  1537 D WifiNative-wlan0: doBoolean: SET ps 1
07-27 15:04:34.068  1033  1537 D WifiNative-wlan0: SET ps 1: returned true
07-27 15:04:34.068  1033  1536 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:34.070   309   884 D CommandListener: Setting iface cfg
07-27 15:04:34.070   309   884 D CommandListener: Trying to bring up p2p0
,07-27 15:04:34.070  1033  1536 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-27 15:04:34.070  1033  1536 D LGWifiP2pService: P2pEnablingState
07-27 15:04:34.070  1033  1536 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:34.070  1033  1536 D LGWifiP2pService: P2p socket connection successful
07-27 15:04:34.070  1033  1536 D LGWifiP2pService: P2pEnabledState
07-27 15:04:34.071  1033  1536 D LGWifiP2pService: sending p2p connection changed broadcast
07-27 15:04:34.071  7017  7017 D LgDataFeature: LgDataFeature() Constructor: none
07-27 15:04:34.071  7017  7017 D LgDataFeature: LgDataFeature() Constructor Done, null
07-27 15:04:34.071  1033  1536 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
07-27 15:04:34.072  1033  1033 D WifiScanningService: SCAN_AVAILABLE : 3
07-27 15:04:34.072  1033  1033 D RttService: SCAN_AVAILABLE : 3
07-27 15:04:34.072  1033  1557 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:34.072  1033  1557 I WifiNative-HAL: startHal
07-27 15:04:34.072  1033  1558 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:34.073  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
07-27 15:04:34.073  7017  7017 D PhoneMonitor: Register our PhoneStateListener
07-27 15:04:34.074  1033  1536 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
07-27 15:04:34.074  1033  1536 D WifiNative-p2p0: doBoolean: SET device_name G3
07-27 15:04:34.074  1944  1944 D WfdsService: WifiP2pState is changed : true
07-27 15:04:34.074  1033  1536 D WifiNative-p2p0: SET device_name G3: returned true
07-27 15:04:34.074  1944  2341 D WfdsService: Receive the WFDS_ENABLE Method
07-27 15:04:34.074  1944  2341 D WfdsService: Set the WFDS Monitor: true
07-27 15:04:34.074  1033  1536 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
07-27 15:04:34.074  1033  1536 D LGWifiP2pService: before postfix = G3
07-27 15:04:34.074  1033  1557 D wifi    : getting scan capabilities on interface[1] = 0xaf66e0c0
07-27 15:04:34.074  1033  1536 D WifiServerServiceExt: postfix byte check : 2
07-27 15:04:34.074  1033  1557 D wifi    : failed to get capabilities : -3
07-27 15:04:34.074  1944  2341 D WfdsService: Connected to the supplicant for wfds
07-27 15:04:34.074  1033  1557 E WifiScanningService: could not get scan capabilities
07-27 15:04:34.074  1033  1536 D LGWifiP2pService: after postfix = G3
07-27 15:04:34.075  1033  1536 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
07-27 15:04:34.075  1944  2341 D WfdsJNI : doCommand: WFDS_SET TRUE
07-27 15:04:34.075  7001  7001 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
07-27 15:04:34.075  1033  1537 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
07-27 15:04:34.075  1033  1536 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
07-27 15:04:34.075  1033  1536 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
07-27 15:04:34.076  1033  1537 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
07-27 15:04:34.076  1944  2341 D WfdsService: selectPreferredScanChannel [36]
07-27 15:04:34.076  1944  2341 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
07-27 15:04:34.076  1033  1537 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
07-27 15:04:34.076  1944  1944 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
07-27 15:04:34.076  1033  1537 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
07-27 15:04:34.077  1944  1944 D WfdsService: isConnected: false
07-27 15:04:34.077  1033  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=136749  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-27 15:04:34.078  1033  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=136750  SSID:  B,SSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-27 15:04:34.079  1033  1537 E WifiStateMachine:  DisconnectedState what:132106 1 0
07-27 15:04:34.079  1033  1536 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
07-27 15:04:34.079  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:34.079  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 15:04:34.079  1033  1536 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
07-27 15:04:34.079  1033  1537 E WifiStateMachine:  ConnectModeState what:132106 1 0
07-27 15:04:34.079  1033  1537 E WifiStateMachine:  DriverStartedState what:132106 1 0
07-27 15:04:34.080  1033  1537 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
07-27 15:04:34.080  7001  7001 E wpa_supplicant: nWIFIDualbandAPConnection: 1
07-27 15:04:34.080  1033  1536 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
07-27 15:04:34.080  1033  1536 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
07-27 15:04:34.080  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 15:04:34.080  1033  1537 E WifiStateMachine:  DisconnectedState what:132096 -100 0
07-27 15:04:34.080  1033  1536 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
07-27 15:04:34.080  1033  1536 D WifiNative-HAL: p2pGetDeviceAddress
07-27 15:04:34.081  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:34.081  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:34.081  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
07-27 15:04:34.081  1033  1536 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
07-27 15:04:34.081  1033  1536 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
07-27 15:04:34.081  1033  1537 E WifiStateMachine:  ConnectModeState what:132096 -100 0
07-27 15:04:34.081  1033  1536 D WifiNative-p2p0: doBoolean: P2P_FLUSH
07-27 15:04:34.082  1033  1537 E WifiStateMachine:  DriverStartedState what:132096 -100 0
07-27 15:04:34.082  1033  1537 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
07-27 15:04:34.082  7001  7001 E wpa_supplicant: disconnect_rssi_lvl: -100
07-27 15:04:34.082  1033  1537 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
07-27 15:04:34.083  1033  1537 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
07-27 15:04:34.083  1944  1944 I WfdStateTracker: handleP2pThisDeviceChanged
07-27 15:04:34.083  1944  1944 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
07-27 15:04:34.083  1944  1944 D WfdsService: Update P2p Interface State: 3
07-27 15:04:34.083  1033  1536 D WifiNative-p2p0: P2P_FLUSH: returned true
07-27 15:04:34.083  1033  1536 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
,07-27 15:04:34.084  1033  1536 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
07-27 15:04:34.084  1033  1536 D WifiNative-p2p0: doString: [LIST_NETWORKS]
,07-27 15:04:34.085  1033  1536 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
07-27 15:04:34.085  1033  1536 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
07-27 15:04:34.085  1033  1537 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
07-27 15:04:34.085  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
07-27 15:04:34.088  7017  7017 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
07-27 15:04:34.090  7017  7017 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
07-27 15:04:34.095  1033  1536 D WifiNative-p2p0: SAVE_CONFIG: returned true
07-27 15:04:34.095  1033  1536 D LGWifiP2pService: sending p2p persistent groups changed broadcast
,07-27 15:04:34.096  7001  7001 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
07-27 15:04:34.097  7001  7001 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 15:04:34.097  7001  7001 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
07-27 15:04:34.097  7001  7001 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 15:04:34.098  7001  7001 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 15:04:34.099  1944  7037 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,07-27 15:04:34.099  1944  7037 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-27 15:04:34.099  1033  1537 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
07-27 15:04:34.099  1033  7036 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-27 15:04:34.099  1033  7036 E WifiMonitor: WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 15:04:34.099  1033  7036 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 15:04:34.099  1033  7036 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 15:04:34.099  1033  7036 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-27 15:04:34.099  1033  7036 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 15:04:34.099  1033  7036 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 15:04:34.099  1033  1537 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
07-27 15:04:34.099  1033  7036 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 15:04:34.099  1033  7036 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-27 15:04:34.100  1033  7036 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 15:04:34.100  1033  7036 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 15:04:34.100  1033  7036 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 15:04:34.100  1033  1537 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
07-27 15:04:34.100  1033  1537 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
07-27 15:04:34.100  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
07-27 15:04:34.100  7001  7001 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
,07-27 15:04:34.100  7001  7001 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-27 15:04:34.101  1033  1537 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
07-27 15:04:34.101  1033  1537 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
07-27 15:04:34.101  1033  7036 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
07-27 15:04:34.101  1033  7036 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-27 15:04:34.101  1033  7036 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-27 15:04:34.101  1033  7036 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-27 15:04:34.102  1033  1537 D WifiNative-wlan0: BSS_FLUSH 0: returned true
07-27 15:04:34.102  1033  1537 D WifiNative-wlan0: doBoolean: SCAN
,07-27 15:04:34.102  1033  1537 D WifiNative-wlan0: SCAN: returned false
07-27 15:04:34.102  1033  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=136774  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-27 15:04:34.104  7017  7017 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
07-27 15:04:34.105  7017  7017 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
07-27 15:04:34.105  7017  7017 D TelephonyAutoProfiling: [parse] Load xml
07-27 15:04:34.107  7017  7017 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
07-27 15:04:34.107  7017  7017 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
07-27 15:04:34.107  7017  7017 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
07-27 15:04:34.107  7017  7017 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
07-27 15:04:34.107  7017  7017 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
07-27 15:04:34.107  7017  7017 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
07-27 15:04:34.107  7017  7017 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
07-27 15:04:34.107  7017  7017 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
07-27 15:04:34.107  7017  7017 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
07-27 15:04:34.107  7017  7017 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
07-27 15:04:34.107  7017  7017 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
07-27 15:04:34.107  7017  7017 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
07-27 15:04:34.107  7017  7017 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
07-27 15:04:34.107  7017  7017 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
07-27 15:04:34.107  7017  7017 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
,07-27 15:04:34.107  7017  7017 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
07-27 15:04:34.107  7017  7017 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,07-27 15:04:34.111  7017  7017 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,07-27 15:04:34.129  1033  1051 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7040 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-27 15:04:34.131  1033  1051 I ActivityManager: Killing 6508:com.google.android.apps.docs/u0a61 (adj 15): empty #17
07-27 15:04:34.176  1033  1536 D LGWifiP2pService: InactiveState
07-27 15:04:34.176  1033  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=136847  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-27 15:04:34.176  1033  1536 D LGWifiP2pService: InactiveState{ when=-92ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:34.176  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=-93ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:34.176  1033  1536 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
07-27 15:04:34.177  1033  1537 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-27 15:04:34.177  1033  1537 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-27 15:04:34.178  1033  1537 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-27 15:04:34.178  7001  7001 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
07-27 15:04:34.178  1033  1537 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-27 15:04:34.178  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:34.178  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,07-27 15:04:34.179  1033  1537 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,07-27 15:04:34.179  7001  7001 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 15:04:34.180  7001  7001 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
07-27 15:04:34.180  7001  7001 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 15:04:34.180  7001  7001 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 15:04:34.181  1944  7037 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-27 15:04:34.181  1944  7037 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-27 15:04:34.181  1944  7037 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-27 15:04:34.181  1033  7036 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-27 15:04:34.181  1033  7036 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 15:04:34.181  1033  7036 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 15:04:34.181  1033  7036 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 15:04:34.181  1033  7036 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-27 15:04:34.181  1033  7036 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 15:04:34.181  1033  7036 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 15:04:34.181  1033  7036 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 15:04:34.181  1033  7036 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-27 15:04:34.181  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:34.182  1033  7036 E WifiMonitor: WifiMonitor:p2p0 cnt=31 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 15:04:34.182  1033  7036 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 15:04:34.182  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:34.182  1033  7036 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 15:04:34.182  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
07-27 15:04:34.182  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 15:04:34.183  1033  1888 W libprocessgroup: failed to open /acct/uid_10061/pid_6508/cgroup.procs: No such file or directory
07-27 15:04:34.184  1033  1536 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
07-27 15:04:34.185  1033  1536 D LGWifiP2pService: InactiveState{ when=-85ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:34.185  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=-85ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:34.185  1033  1536 D LGWifiP2pService: InactiveState{ when=-9ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:34.185  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:34.185  1033  1536 D LGWifiP2pService: DefaultState{ when=-9ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:34.185  1033  1536 D LGWifiP2pService: InactiveState{ when=-9ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:34.185  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHa,ndler }
07-27 15:04:34.185  1033  1536 D LGWifiP2pService: DefaultState{ when=-10ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:34.185  1033  1536 D LGWifiP2pService: InactiveState{ when=-10ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:34.185  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:34.185  1033  1536 D LGWifiP2pService: DefaultState{ when=-10ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:34.186  1033  1536 D LGWifiP2pService: InactiveState{ when=-10ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:34.186  1944  2341 W WfdsService: DefaultState - msg [9441285] is not handled
07-27 15:04:34.186  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:34.186  1033  1536 D LGWifiP2pService: DefaultState{ when=-10ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:34.186  1033  1033 E WifiServerServiceExt: No p2p device connected
07-27 15:04:34.191  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 15:04:34.191  1033  1033 D WifiServerServiceExt: setSupplicantStateSCANNING
,07-27 15:04:34.381  1033  2034 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7058 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
07-27 15:04:34.383  1033  2034 I ActivityManager: Killing 6138:com.google.android.apps.plus/u0a97 (adj 15): empty #17
07-27 15:04:34.456  1033  1927 W libprocessgroup: failed to open /acct/uid_10097/pid_6138/cgroup.procs: No such file or directory
,07-27 15:04:34.579  1033  1870 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7075 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-27 15:04:34.580  1033  1870 I ActivityManager: Killing 6554:com.lge.eula/1000 (adj 15): empty #17
,07-27 15:04:34.618  1033  7036 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
,07-27 15:04:34.618  1033  7036 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
07-27 15:04:34.618  7001  7001 E wpa_supplicant: USIM:  scard_init function
07-27 15:04:34.618  1033  7036 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
07-27 15:04:34.618  1033  7036 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: WPS-AP-AVAILABLE 
07-27 15:04:34.618  1033  7036 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
07-27 15:04:34.619  7001  7001 I wpa_supplicant: Trying to associate with SSID 'NG700'
,07-27 15:04:34.619  1033  1537 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
07-27 15:04:34.620  1033  1537 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
07-27 15:04:34.620  1033  1537 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
07-27 15:04:34.621  1033  7036 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
07-27 15:04:34.621  1033  7036 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
07-27 15:04:34.621  1033  1537 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
07-27 15:04:34.621  1033  1537 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
07-27 15:04:34.635  1033  1927 W libprocessgroup: failed to open /acct/uid_1000/pid_6554/cgroup.procs: No such file or directory
,07-27 15:04:34.644  1033  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=137315  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
07-27 15:04:34.647  1033  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=137318  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
07-27 15:04:34.648  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:34.648  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 15:04:34.649  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:34.649  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:34.649  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
07-27 15:04:34.649  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 15:04:34.651  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 15:04:34.651  1033  1033 D WifiServerServiceExt: setSupplicantStateASSOCIATING
,07-27 15:04:34.685  7075  7075 I art     : Almond Protected OAT
,07-27 15:04:34.730  7001  7001 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
07-27 15:04:34.731  1033  7036 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
07-27 15:04:34.731  1033  7036 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
07-27 15:04:34.732  1033  7036 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
07-27 15:04:34.732  1033  7036 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: Associated with f4:f2:6d:22:99:3e
07-27 15:04:34.732  1033  7036 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-27 15:04:34.732  1033  7036 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,07-27 15:04:34.732  1033  1098 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
07-27 15:04:34.736  1033  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=137407  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
07-27 15:04:34.740  1033  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=137411  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
07-27 15:04:34.742  1033  1537 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=137413
07-27 15:04:34.743  1033  1537 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=137414
07-27 15:04:34.746  1033  1537 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=137418
07-27 15:04:34.747  1033  1537 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=137418
07-27 15:04:34.747  1033  1537 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=137418
07-27 15:04:34.748  1033  7036 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-27 15:04:34.748  1033  7036 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-27 15:04:34.749  7001  7001 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-27 15:04:34.749  1033  7036 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
07-27 15:04:34.749  7001  7001 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-27 15:04:34.749  1033  7036 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-27 15:04:34.749  1033  7036 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-27 15:04:34.749  1033  7036 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
07-27 15:04:34.749  1033  7036 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-27 15:04:34.749  1033  7036 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-27 15:04:34.749  1033  7036 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-27 15:04:34.749  1033  7036 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-27 15:04:34.750  1033  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=137422  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
07-27 15:04:34.752  7075  7075 D WeatherApplication: removeAccount
07-27 15:04:34.753  1033  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=137424  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
07-27 15:04:34.753  1033  1537 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
07-27 15:04:34.753  7075  7075 D WeatherApplication: Account.length = 0
07-27 15:04:34.754  7075  7075 E WeatherApplication: OPERATOR:OPEN
07-27 15:04:34.754  1033  1537 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
07-27 15:04:34.755  1033  1537 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
07-27 15:04:34.756  1033  1537 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
07-27 15:04:34.756  1033  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-27 15:04:34.757  1033  1537 E WifiStateMachine:  DisconnectedState SUPPLIC,ANT_STATE_CHANGE_EVENT 38 0 rt=137428  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
07-27 15:04:34.758  1033  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=137429  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
07-27 15:04:34.759  1033  1537 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=137430
07-27 15:04:34.759  7075  7075 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:4:34
07-27 15:04:34.759  1033  1537 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=137430
07-27 15:04:34.760  1033  1537 D WifiNative-wlan0: doString: [STATUS]
07-27 15:04:34.760  1033  7036 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-27 15:04:34.760  1033  7036 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-27 15:04:34.761  1033  1537 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
07-27 15:04:34.762  7075  7075 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
07-27 15:04:34.762  7075  7075 D Weather.Utils: 2 : All the weather widget is gone.
07-27 15:04:34.762  1033  1537 I WifiServiceExtension: setVHTCapabilityType  : false
,07-27 15:04:34.764  7075  7075 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-27 15:04:34.767  7075  7075 D WeatherAncestor: connectivity changed - connection : true
07-27 15:04:34.768  7075  7075 D WeatherService: 2 : isServiceAlived():false forecastCache:null
07-27 15:04:34.770  1033  1537 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
07-27 15:04:34.770  1033  1537 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
07-27 15:04:34.776  7075  7075 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
07-27 15:04:34.776  7075  7075 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
07-27 15:04:34.776  7075  7075 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,07-27 15:04:34.792  1033  1537 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,07-27 15:04:34.792  1033  1545 D ConnectivityService: Got NetworkAgent Messenger
07-27 15:04:34.792  1033  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-27 15:04:34.792  1033  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-27 15:04:34.792  1033  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
07-27 15:04:34.793  1033  1545 D ConnectivityService: NetworkAgent connected
07-27 15:04:34.795  1033  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-27 15:04:34.795  1033  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,07-27 15:04:34.797  7075  7075 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-27 15:04:34.798  7075  7075 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:4:34
07-27 15:04:34.799  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:34.799  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 15:04:34.800  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 15:04:34.801  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:34.801  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:34.801  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
07-27 15:04:34.805  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:34.805  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:34.805  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
07-27 15:04:34.805  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 15:04:34.805  1033  1033 D WifiServerServiceExt: setSupplicantStateASSOCIATED
07-27 15:04:34.806  1033  1093 W ProcessCpuTracker: Skipping unknown process pid 7011
07-27 15:04:34.806  1033  1093 W ProcessCpuTracker: Skipping unknown process pid 7012
07-27 15:04:34.807  1033  1093 W ProcessCpuTracker: Skipping unknown process pid 7014
07-27 15:04:34.807  1033  1093 W ProcessCpuTracker: Skipping unknown process pid 7015
07-27 15:04:34.810  1033  1093 W ProcessCpuTracker: Skipping unknown process pid 7092
,07-27 15:04:34.816  1033  1536 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:34.816  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:34.816  1033  1536 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:34.816  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:34.816  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:34.816  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
07-27 15:04:34.820  1033  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-27 15:04:34.820  1033  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-27 15:04:34.820  1033  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-27 15:04:34.821  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:34.821  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 15:04:34.822  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 15:04:34.822  1033  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-27 15:04:34.822  1033  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,07-27 15:04:34.825  1033  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-27 15:04:34.826  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:34.826  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 15:04:34.827   309   884 D CommandListener: Setting iface cfg
07-27 15:04:34.827  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 15:04:34.828  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:34.828  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:34.829  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
07-27 15:04:34.829  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:34.829  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 15:04:34.830  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 15:04:34.880  1033  1576 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7103 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-27 15:04:34.881  1033  1576 I ActivityManager: Killing 6572:com.lge.bnr/1000 (adj 15): empty #17
,07-27 15:04:34.946  1033  1889 W libprocessgroup: failed to open /acct/uid_1000/pid_6572/cgroup.procs: No such file or directory
,07-27 15:04:34.956  1033  1537 E WifiStateMachine: Start Dhcp Watchdog 2
,07-27 15:04:34.956  1033  7102 D DhcpStateMachine: StoppedState
07-27 15:04:34.956  1033  1537 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=137628  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-27 15:04:34.957  1033  7102 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:34.957  1033  7102 D DhcpStateMachine: WaitBeforeStartState
07-27 15:04:34.957  1033  1537 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=137628  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-27 15:04:34.958  1033  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=137629  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-27 15:04:34.959  1033  1537 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=137630  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-27 15:04:34.959  1033  1537 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=137631  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-27 15:04:34.960  1033  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=137631  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-27 15:04:34.961  1033  1537 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:91964] from screen [on:0 period:745859729] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-27 15:04:34.962  1033  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:745859730] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-27 15:04:34.962  1033  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 15:04:34.963  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 15:04:34.964  1033  1033 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
,07-27 15:04:34.969  1033  1545 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
07-27 15:04:34.969  1033  1537 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 15:04:34.969  1033  1537 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 15:04:34.970  1033  1537 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 15:04:34.970  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 15:04:34.970  1033  1537 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 15:04:34.970  1033  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 15:04:34.971  1033  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 15:04:34.971  1033  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
07-27 15:04:34.972  1033  1537 E WifiStateMachine:  ObtainingIpState CMD_STOP_SUPPLICANT_FAILED 1 0
,07-27 15:04:34.972  1033  1537 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
07-27 15:04:34.973  1033  1537 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
07-27 15:04:34.973  1033  1537 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
07-27 15:04:34.974  1033  1537 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
07-27 15:04:34.974  1033  1537 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
07-27 15:04:34.975  1033  1537 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=102,0,0
07-27 15:04:34.975  1033  1537 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=102,0,0
07-27 15:04:34.975  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
07-27 15:04:34.976  7001  7001 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
07-27 15:04:34.976  1033  1537 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
07-27 15:04:34.976  1033  1537 D WifiNative-wlan0: doBoolean: SET ps 0
07-27 15:04:34.977  1033  1537 D WifiNative-wlan0: SET ps 0: returned true
07-27 15:04:34.977  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
07-27 15:04:34.977  7001  7001 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
07-27 15:04:34.977  1033  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
07-27 15:04:34.977  1033  1537 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
07-27 15:04:34.977  1033  1537 V DhcpStateMachine: Current State is mWaitBeforeStartState.
07-27 15:04:34.977  1033  1536 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2e2534b7 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:34.977  1033  1537 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
07-27 15:04:34.978  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2e2534b7 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:34.978  1033  7102 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:34.978  1033  7102 D DhcpStateMachine: DHCP Start wake lock is acquired.
07-27 15:04:34.978   309   884 D CommandListener: Setting iface cfg
07-27 15:04:34.979   309   884 D CommandListener: Trying to bring up wlan0
07-27 15:04:34.980  1033  1537 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
07-27 15:04:34.981  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 15:04:34.981  1033  1033 D WifiServerServiceExt: setSupplicantStateCOMPLETED
07-27 15:04:34.982  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 15:04:34.982  1033  1033 D WifiServerServiceExt: setSupplicantStateCOMPLETED
07-27 15:04:34.983  1033  1537 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 15:04:34.984  1033  1537 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 15:04:34.984  1033  1537 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 15:04:34.985  1033  1537 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 15:04:34.985  1033  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 15:04:34.986  1033  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 15:04:34.986  1033  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
07-27 15:04:34.986  1033  1537 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
07-27 15:04:34.987  1033  1537 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
07-,27 15:04:34.987  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-27 15:04:34.987  1033  1536 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:34.987  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:34.987  7001  7001 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-27 15:04:34.987  1033  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-27 15:04:34.987  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
07-27 15:04:34.988  7001  7001 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
07-27 15:04:34.989  1033  1537 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
07-27 15:04:34.989  1033  1537 D WifiNative-wlan0: doBoolean: SET ps 1
,07-27 15:04:35.005  1033  1537 D WifiNative-wlan0: SET ps 1: returned true
07-27 15:04:35.005  1033  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
07-27 15:04:35.006  1033  1537 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
07-27 15:04:35.006  1033  1537 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
07-27 15:04:35.006  1033  1537 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
07-27 15:04:35.006  1033  1545 D ConnectivityService: ignoring duplicate network state non-change
,07-27 15:04:35.012  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:35.012  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 15:04:35.013  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:35.013  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:35.013  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
07-27 15:04:35.014  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 15:04:35.015  1033  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
07-27 15:04:35.015  1033  1545 D ConnectivityService: Adding iface wlan0 to network 101
07-27 15:04:35.019  1033  1537 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-27 15:04:35.023  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:35.023  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:35.023  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
07-27 15:04:35.024  1033  1033 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
07-27 15:04:35.029  1944  1944 V WfdStateTracker: handleWifiStateChangedEvent: 1
07-27 15:04:35.035  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:35.035  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:35.035  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:35.035  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 15:04:35.035  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
07-27 15:04:35.037  1033  1033 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,07-27 15:04:35.040  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 15:04:35.042  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:35.042  1604  1604 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
07-27 15:04:35.043  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:35.043  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 15:04:35.043  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:35.043  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
07-27 15:04:35.045  1033  1545 E ConnectivityService: Unexpected mtu value: 0, wlan0
07-27 15:04:35.045  1033  1545 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
07-27 15:04:35.047  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:35.047  1033  1545 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
07-27 15:04:35.047  1604  1604 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
07-27 15:04:35.047  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-27 15:04:35.048   309   884 E Netd    : netlink response contains error (File exists)
07-27 15:04:35.048  1033  1545 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
07-27 15:04:35.049  1033  1545 D ConnectivityService: addLocalRoutetoDefaultNetwork
07-27 15:04:35.049  1033  1545 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
07-27 15:04:35.049  1033  1545 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
07-27 15:04:35.050  1033  1545 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
07-27 15:04:35.050  1033  1545 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
07-27 15:04:35.050  1033  1545 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
07-27 15:04:35.050  1033  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
07-27 15:04:35.050  1033  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 15:04:35.050  1033  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 15:04:35.050  1033  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
07-27 15:04:35.050  1033  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 15:04:35.051  1033  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
07-27 15:04:35.051  1033  1545 D ConnectivityService: currentScore = 0, newScore = 20
07-27 15:04:35.051  1033  1545 D ConnectivityService:    accepting network in place of null
07-27 15:04:35.051  1033  1545 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 15:04:35.052  1033  1545 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
07-27 15:04:35.052  1033  7096 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:35.052  1033  7096 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
07-27 15:04:35.052  1033  1545 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
07-27 15:04:35.052  1033  7096 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:35.052  1033  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-27 15:04:35.052  1033  7096 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
07-27 15:04:35.054   309  7124 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
,07-27 15:04:35.055  1853  1853 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 15:04:35.055  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-27 15:04:35.056  1033  1537 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 15:04:35.056  1033  1537 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,07-27 15:04:35.059  1033  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-27 15:04:35.060  1033  1545 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
07-27 15:04:35.060  1033  1545 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
07-27 15:04:35.061  1033  1545 D ConnectivityService: validation of new default Network = false
07-27 15:04:35.061  1033  1545 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
07-27 15:04:35.061  1033  1545 D DSQN    : enableDataServiceNotify 
07-27 15:04:35.061  1033  1545 D DSQN    : start dsqn bin
07-27 15:04:35.062  1033  1033 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
07-27 15:04:35.062  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-27 15:04:35.062  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-27 15:04:35.062  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-27 15:04:35.065  1033  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
07-27 15:04:35.065  1033  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 15:04:35.065  1033  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 15:04:35.062  7125  7125 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 15:04:35.062  7125  7125 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 15:04:35.068  1033  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 15:04:35.069  1604  2066 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-27 15:04:35.070  1033  1535 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,07-27 15:04:35.082  7125  7125 E DSQN    : DSQN ssw
,07-27 15:04:35.090  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-27 15:04:35.091  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 15:04:35.092  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 15:04:35.103  1818  7129 I CheckinService: active receiver: enabled
,07-27 15:04:35.107   309  7124 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
07-27 15:04:35.111  1818  7129 I CheckinService: Preparing to send checkin request
07-27 15:04:35.112  1818  7129 I EventLogService: Accumulating logs since 1469624595063
07-27 15:04:35.127   278   379 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-27 15:04:35.127   278   379 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
07-27 15:04:35.128   278   379 W Vold    : Returning OperationFailed - no handler for errno 0
07-27 15:04:35.128  7103  7132 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,07-27 15:04:35.129   278   379 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-27 15:04:35.129   278   379 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
07-27 15:04:35.129   278   379 W Vold    : Returning OperationFailed - no handler for errno 0
07-27 15:04:35.130  7103  7132 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
07-27 15:04:35.133   278   379 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-27 15:04:35.133   278   379 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
07-27 15:04:35.133   278   379 W Vold    : Returning OperationFailed - no handler for errno 0
07-27 15:04:35.134  7103  7134 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
07-27 15:04:35.135   278   379 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-27 15:04:35.135   278   379 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
07-27 15:04:35.135   278   379 W Vold    : Returning OperationFailed - no handler for errno 0
07-27 15:04:35.135  7103  7134 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
07-27 15:04:35.138  1818  7129 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,07-27 15:04:35.144   309  7124 D libc-netbsd: res_queryN name = clients3.google.com succeed
,07-27 15:04:35.178   309   883 D LGDataListener: argv[0]=dsqncommand
07-27 15:04:35.178   309   883 D LGDataListener: argv[1]=wlan0
,07-27 15:04:35.178   309   883 D LGDataListener: argv[2]=1
07-27 15:04:35.178   309   883 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
07-27 15:04:35.179  1033  1096 D DSQN    : DSQM DsqnNotification wlan0  1
07-27 15:04:35.179  1033  1096 D DSQN    : start to monitor internet connection
07-27 15:04:35.181  1033  7102 D DhcpStateMachine: DHCPV4 request on wlan0
07-27 15:04:35.182  1033  7102 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
07-27 15:04:35.182  1033  7102 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
07-27 15:04:35.172  7140  7140 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 15:04:35.172  7140  7140 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 15:04:35.191  7140  7140 I dhcpcd  : version 5.5.6 starting
07-27 15:04:35.193  7140  7140 E dhcpcd  : get_duid: m
07-27 15:04:35.193  7140  7140 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
07-27 15:04:35.193  7140  7140 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,07-27 15:04:35.213  1033  7096 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 27 Jul 2016 13:04:35 GMT], X-Android-Received-Millis=[1469624675212], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1469624675178]}
07-27 15:04:35.213  1033  7096 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
07-27 15:04:35.213  1033  7096 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
07-27 15:04:35.213  1033  1545 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
07-27 15:04:35.213  1033  1630 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7143 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
07-27 15:04:35.213  1033  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
07-27 15:04:35.213  1033  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 15:04:35.213  1033  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 15:04:35.213  1033  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
07-27 15:04:35.213  1033  1545 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
07-27 15:04:35.213  1033  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
07-27 15:04:35.213  1033  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 15:04:35.213  1033  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 15:04:35.214  1033  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 15:04:35.214  1033  1545 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 15:04:35.214  1033  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
07-27 15:04:35.214  1033  1537 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 15:04:35.214  1033  1537 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 15:04:35.215  1604  2066 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-27 15:04:35.215  1853  1853 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 15:04:35.215  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,07-27 15:04:35.233  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-27 15:04:35.234  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 15:04:35.235  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 15:04:35.246  7140  7140 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,07-27 15:04:35.246  7140  7140 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
07-27 15:04:35.246  7140  7140 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
07-27 15:04:35.246  7140  7140 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
07-27 15:04:35.247  7140  7140 D dhcpcd  : wlan0: sending REQUEST (xid 0x56496c29), next in 3.34 seconds
07-27 15:04:35.263  7140  7140 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,07-27 15:04:35.271  7143  7143 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-27 15:04:35.271  7143  7143 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
07-27 15:04:35.274  7140  7140 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
07-27 15:04:35.274  7140  7140 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
07-27 15:04:35.274  7140  7140 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
07-27 15:04:35.274  7140  7140 D dhcpcd  : wlan0: adding default route via 192.168.1.1
,07-27 15:04:35.275  7140  7140 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
07-27 15:04:35.275  7140  7140 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
07-27 15:04:35.275  7140  7140 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
07-27 15:04:35.275  7140  7140 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
07-27 15:04:35.292  7143  7143 I MultiDex: VM with version 2.1.0 has multidex support
07-27 15:04:35.292  7143  7143 I MultiDex: install
07-27 15:04:35.292  7143  7143 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-27 15:04:35.301  7143  7143 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
07-27 15:04:35.338  7103  7103 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,07-27 15:04:35.343  7103  7103 I LibraryLoader: Loading: webviewchromium
07-27 15:04:35.345  7103  7103 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 8028-8031)
07-27 15:04:35.346  7103  7103 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-27 15:04:35.349  7103  7103 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {31b14b65}
07-27 15:04:35.350  7103  7103 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-27 15:04:35.350  7103  7103 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
07-27 15:04:35.357  7103  7103 I BrowserStartupController: Initializing chromium process, renderers=0
,07-27 15:04:35.357  7103  7103 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-27 15:04:35.358  7143  7160 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
07-27 15:04:35.366  7103  7103 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
07-27 15:04:35.366  7103  7103 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
07-27 15:04:35.366  7103  7103 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
07-27 15:04:35.377   309  7199 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,07-27 15:04:35.379   309  7199 D libc-netbsd: res_queryN name = www.googleapis.com, class = 1, type = 1
,07-27 15:04:35.384   315  1384 V AudioPolicyService: registerClient() client 0xb1021cc0, uid 10093
07-27 15:04:35.386  7103  7195 W AudioManagerAndroid: Requires BLUETOOTH permission
07-27 15:04:35.393  7103  7103 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-27 15:04:35.393  7103  7103 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-27 15:04:35.393  7103  7103 I Adreno-EGL: Build Date: 12/12/14 금
07-27 15:04:35.393  7103  7103 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-27 15:04:35.393  7103  7103 I Adreno-EGL: Remote Branch: 
07-27 15:04:35.393  7103  7103 I Adreno-EGL: Local Patches: 
07-27 15:04:35.393  7103  7103 I Adreno-EGL: Reconstruct Branch: 
,07-27 15:04:35.411   309  7199 D libc-netbsd: res_queryN name = www.googleapis.com succeed
,07-27 15:04:35.443  7103  7103 I NSApplication: Starting up...
,07-27 15:04:35.533  1033  1889 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7220 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,07-27 15:04:35.537  1033  1889 I ActivityManager: Killing 6075:com.android.vending/u0a44 (adj 15): empty #17
07-27 15:04:35.563   346   346 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 473us total 30.073ms
,07-27 15:04:35.583   346   346 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 416us total 19.210ms
,07-27 15:04:35.585  1033  7102 D DhcpStateMachine: DHCPV4 succeeded on wlan0
07-27 15:04:35.586  1033  7102 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
07-27 15:04:35.586  1033  7102 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
07-27 15:04:35.586  1033  7102 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
07-27 15:04:35.586  1033  7102 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
07-27 15:04:35.586  1033  7102 V DhcpStateMachine: Current State is mWaitBeforeStartState.
07-27 15:04:35.586  1033  7102 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
07-27 15:04:35.586  1033  7102 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
07-27 15:04:35.587  1033  7102 D DhcpStateMachine: RunningState
07-27 15:04:35.602   346   346 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 363us total 17.840ms
,07-27 15:04:35.629  1033  1973 W libprocessgroup: failed to open /acct/uid_10044/pid_6075/cgroup.procs: No such file or directory
,07-27 15:04:35.655  7220  7220 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-27 15:04:35.846  1033  1889 D WifiServiceImplEx: setWifiEnabled: false pid=6632, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,07-27 15:04:35.846  1033  1889 D WifiService: setWifiEnabled: false pid=6632, uid=10118
07-27 15:04:35.846  1033  1889 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-27 15:04:35.863  1033  1537 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
07-27 15:04:35.863  1033  1537 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
07-27 15:04:35.863  1033  1537 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
07-27 15:04:35.863  1033  1537 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
07-27 15:04:35.863  1033  1537 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
07-27 15:04:35.863  1033  1537 E WifiStateMachine: WifiStateMachine: Leaving Connected state
07-27 15:04:35.864  1033  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-27 15:04:35.864  1033  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-27 15:04:35.864  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-27 15:04:35.865  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-27 15:04:35.865  1033  1033 D Ulp_jni : JNI:system_update. Event-4
,07-27 15:04:35.873  1033  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-27 15:04:35.873  1033  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-27 15:04:35.887  1033  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-27 15:04:35.887  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-27 15:04:35.887  1033  1536 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:35.887  7001  7001 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-27 15:04:35.887  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:35.888  1033  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-27 15:04:35.888  1033  1537 D WifiNative-wlan0: doBoolean: SET ps 1
07-27 15:04:35.888  1033  1537 D WifiNative-wlan0: SET ps 1: returned true
07-27 15:04:35.888   309   884 D CommandListener: Clearing all IP addresses on wlan0
,07-27 15:04:35.889  1033  7102 D DhcpStateMachine: RunningState{ when=-2ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:35.913  1033  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 15:04:35.913  1033  1536 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:35.913  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:35.913  1033  1536 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@d27ad20
,07-27 15:04:35.913  1033  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 15:04:35.914  1033  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
07-27 15:04:35.914  1033  1545 D ConnectivityService: ignoring duplicate network state non-change
07-27 15:04:35.914  1033  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
07-27 15:04:35.914  1033  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 15:04:35.914  1033  1537 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,07-27 15:04:35.922  1944  1944 V WfdStateTracker: handleWifiStateChangedEvent: 0
07-27 15:04:35.923  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:35.923  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 15:04:35.924  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 15:04:35.925  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:35.925  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 15:04:35.926  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 15:04:35.927  1033  1033 D WifiHS20: hidePasspointNotification off =false
,07-27 15:04:35.928  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:35.928  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:35.928  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-27 15:04:35.929  1033  1033 D WifiHS20: hidePasspointNotification off =false
07-27 15:04:35.929  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:35.929  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:35.929  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-27 15:04:35.929  1033  1033 D WifiScanningService: SCAN_AVAILABLE : 1
07-27 15:04:35.929  1033  1033 D RttService: SCAN_AVAILABLE : 1
07-27 15:04:35.929  1033  1557 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:35.930  1033  1558 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:35.930  1033  1536 D LGWifiP2pService: P2pDisablingState
07-27 15:04:35.930  1033  1536 D LGWifiP2pService: P2pDisablingState{ when=-16ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:35.930  1033  1536 D LGWifiP2pService: p2p socket connection lost
07-27 15:04:35.930  1033  1536 D LGWifiP2pService: P2pDisabledState
07-27 15:04:35.932  1033  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
07-27 15:04:35.932  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-27 15:04:35.932  7001  7001 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-27 15:04:35.932  1033  1536 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:35.932  1033  1536 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:35.932  1033  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-27 15:04:35.932  1033  1537 D WifiNative-wlan0: doBoolean: SET ps 1
07-27 15:04:35.933  1033  1537 D WifiNative-wlan0: SET ps 1: returned true
07-27 15:04:35.934  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
07-27 15:04:35.934  1944  1944 D WfdsService: WifiP2pState is changed : false
07-27 15:04:35.934  1944  2341 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
07-27 15:04:35.934  1944  2341 D WfdsService: Set the WFDS Monitor: false
07-27 15:04:35.935  1944  2341 D WfdsMonitor: WFDS Monitor is stopped
07-27 15:04:35.935  1944  2341 D WfdsService: STATE : WfdsDisabledState - enter
07-27 15:04:35.935  1944  7037 D CtrlSupplicant: Received on exit socket, terminate
07-27 15:04:35.935  1944  7037 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
07-27 15:04:35.935  1944  7037 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
07-27 15:04:35.935  1944  7037 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
07-27 15:04:35.936  1944  2343 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
07-27 15:04:35.936  1944  2341 W WfdsService: DefaultState - msg [9445378] is not handled
07-27 15:04:35.939  1033  1052 I art     : Explicit concurrent mark sweep GC freed 87588(4MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 3.945ms total 164.997ms
,07-27 15:04:35.975  1033  1545 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
07-27 15:04:35.975  1033  1545 D DSQN    : disableDataServiceNotify
07-27 15:04:35.975  1033  1545 D DSQN    : stop dsqn bin
07-27 15:04:35.975   309   884 D CommandListener: Clearing all IP addresses on wlan0
,07-27 15:04:35.977  1033  1537 D WifiNative-p2p0: doBoolean: TERMINATE
07-27 15:04:35.978  1033  1537 D WifiNative-p2p0: TERMINATE: returned true
07-27 15:04:35.978  1033  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-27 15:04:35.978  1033  1537 E WifiStateMachine: useWiFiOffloading() : false
07-27 15:04:35.978  1033  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-27 15:04:35.979  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-27 15:04:35.979  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 15:04:35.979  1033  1033 D WifiHS20: hidePasspointNotification off =false
07-27 15:04:35.980  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:35.980  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:35.980  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-27 15:04:35.980  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
07-27 15:04:35.982  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
07-27 15:04:35.982  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 15:04:35.982  1033  1033 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
07-27 15:04:35.983  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 15:04:35.985  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 15:04:35.986  6632  6632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 15:04:35.986  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 15:04:35.986  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:35.986  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:35.986  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 15:04:35.986  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 15:04:35.986  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 15:04:35.986  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 15:04:35.986  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 15:04:35.986  6632  6632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 15:04:35.986  6632  6632 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-27 15:04:35.988  6632  6632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 15:04:35.988  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 15:04:35.988  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:35.988  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:35.988  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 15:04:35.988  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 15:04:35.988  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 15:04:35.988  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 15:04:35.988  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 15:04:35.988  6632  6632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 15:04:35.988  6632  6632 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-27 15:04:35.993  1033  1545 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
07-27 15:04:35.993  1033  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 15:04:35.993  1033  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 15:04:35.993  1033  1545 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 15:04:35.994  1033  1545 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
07-27 15:04:35.994  1033  1545 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
07-27 15:04:35.994  1033  1545 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
07-27 15:04:35.994  1033  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-27 15:04:35.995  1033  7096 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:35.995  1033  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-27 15:04:35.995  1033  7096 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:35.995  1033  7096 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
07-27 15:04:35.995  1033  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-27 15:04:35.996  1604  2066 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
07-27 15:04:35.996  1033  1535 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
07-27 15:04:35.996  1033  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-27 15:04:35.996  1033  1545 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 15:04:35.996  1033  1545 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 15:04:35.996  1033  1545 D NetworkManagementService: Removing idletimer
07-27 15:04:35.996  1033  1545 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:35.996  1033  1537 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 15:04:35.997  1033  1537 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 15:04:35.997  1853  1853 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 15:04:35.997  1853  1853 D Telephon,yNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-27 15:04:35.998  1033  1033 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
07-27 15:04:35.998  1033  1033 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
07-27 15:04:35.998  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-27 15:04:35.998  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-27 15:04:35.998  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-27 15:04:35.998  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-27 15:04:35.998  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-27 15:04:35.998  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-27 15:04:35.999  1033  1535 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
,07-27 15:04:36.020  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-27 15:04:36.021  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 15:04:36.022  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-27 15:04:36.036  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-27 15:04:36.037  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 15:04:36.037  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 15:04:36.064  1033  1377 V AlarmManager: ELAPSED_WAKEUP set : Alarm{29ad18a2 type 2 when 138735 com.google.android.gms} when 138735
,07-27 15:04:36.065  1033  1545 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,07-27 15:04:36.082  7001  7001 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
07-27 15:04:36.082  7001  7001 I wpa_supplicant: monitor socket send errors count : 1
07-27 15:04:36.082  7001  7001 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1944-4\x00 that cannot receive messages
07-27 15:04:36.083  1033  7036 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
07-27 15:04:36.083  1033  7036 D WifiMonitor: Dropping event because (p2p0) is stopped
,07-27 15:04:36.104  7001  7001 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,07-27 15:04:36.104  7001  7001 W wpa_supplicant: USIM:  scard_deinit function
,07-27 15:04:36.105  1033  1098 D Tethering: InitialState.processMessage what=4
07-27 15:04:36.106  1033  1098 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
07-27 15:04:36.106  1033  7036 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
07-27 15:04:36.106  1033  7036 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-27 15:04:36.106  1033  7036 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-27 15:04:36.106  1033  7036 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
07-27 15:04:36.106  1033  7036 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-27 15:04:36.108  1033  1537 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=138780
07-27 15:04:36.109  1033  7102 D DhcpStateMachine: StoppedState
07-27 15:04:36.109  1033  7102 D DhcpStateMachine: StoppedState{ when=-176ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:36.109  1033  1537 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=138780
07-27 15:04:36.109  1033  1537 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
07-27 15:04:36.110  1033  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-27 15:04:36.110  1033  7036 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-27 15:04:36.110  1033  1537 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
07-27 15:04:36.110  1033  1537 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
07-27 15:04:36.111  1033  1537 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=138782  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
07-27 15:04:36.111  1033  1537 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=138783  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
07-27 15:04:36.178  7001  7001 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
07-27 15:04:36.178  1033  7036 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
07-27 15:04:36.178  1033  7036 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-TERMINATING 
07-27 15:04:36.178  1033  7036 D WifiMonitor: Disconnecting from the supplicant, no more events
07-27 15:04:36.180  1033  1537 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 45 0
07-27 15:04:36.183  1944  1944 D WfdsService: Supplicant Connection state is changed : false
07-27 15:04:36.183  1944  2341 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
07-27 15:04:36.183  1944  2341 D WfdsService: Set the WFDS Monitor: false
07-27 15:04:36.183  1944  2341 D WfdsMonitor: WFDS Monitor is stopped
07-27 15:04:36.183  1033  1537 D WifiOffDelayIfNotUsed: stopMonitoring
07-27 15:04:36.184  1033  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-27 15:04:36.184  1033  1537 E WifiStateMachine: useWiFiOffloading() : false
07-27 15:04:36.184  1033  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,07-27 15:04:36.189  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 15:04:36.191  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
07-27 15:04:36.191  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
07-27 15:04:36.191  1033  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
07-27 15:04:36.191  1033  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
07-27 15:04:36.192  2501  2501 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:36.192  6632  6632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 15:04:36.192  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 15:04:36.192  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:36.192  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:36.192  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 15:04:36.192  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 15:04:36.192  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 15:04:36.192  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 15:04:36.192  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 15:04:36.193  6632  6632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 15:04:36.193  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 15:04:36.193  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:36.193  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:36.193  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 15:04:36.193  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 15:04:36.193  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 15:04:36.193  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 15:04:36.193  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 15:04:36.195  6386  6386 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,07-27 15:04:36.199  6386  6412 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
07-27 15:04:36.214  2188  2188 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,07-27 15:04:36.220  6943  6943 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
07-27 15:04:36.220  6943  6943 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
07-27 15:04:36.220  6943  6943 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-27 15:04:36.220  6943  6943 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
07-27 15:04:36.221  6943  6943 I AppUp4:CustModeStarterReceiver: onReceive
07-27 15:04:36.222  7143  7160 D LgDataFeature: LgDataFeature() Constructor: none
07-27 15:04:36.223  7143  7160 D LgDataFeature: LgDataFeature() Constructor Done, null
07-27 15:04:36.225  6943  6943 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@9826d32
07-27 15:04:36.225  6943  6943 D AppUp4:CustFacade: isCustomizationCompleted : false
07-27 15:04:36.225  6943  6943 D AppUp4:CustFacade: isPhone : true
07-27 15:04:36.225  6943  6943 D AppUp4:CustModeStarterReceiver: begin check event
07-27 15:04:36.225  6943  6943 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,07-27 15:04:36.227  4320  4320 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
07-27 15:04:36.227  4320  4320 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-27 15:04:36.231  4320  4320 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-27 15:04:36.233  4320  4320 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-27 15:04:36.238  6966  6966 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,07-27 15:04:36.243  4320  7262 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-27 15:04:36.248  4320  7263 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
07-27 15:04:36.249  4320  7263 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-27 15:04:36.251  6966  7267 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-27 15:04:36.253  3422  3422 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
07-27 15:04:36.253  3422  3422 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
07-27 15:04:36.253  3422  3422 I LgeMiscReceiver: networkInfo.isConnected() = false
,07-27 15:04:36.255  7017  7017 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
07-27 15:04:36.255  7017  7017 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
07-27 15:04:36.262  6836  7266 W FormManager: Network not available. Please check & try again.
,07-27 15:04:36.266  7075  7075 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:4:36
07-27 15:04:36.275  7075  7075 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
07-27 15:04:36.275  7075  7075 D Weather.Utils: 2 : All the weather widget is gone.
07-27 15:04:36.276  7075  7075 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,07-27 15:04:36.276  6836  7270 V FormManager: Network unavailable.
07-27 15:04:36.276  7075  7075 D WeatherAncestor: connectivity changed - connection : true
07-27 15:04:36.276  7075  7075 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2daef400
07-27 15:04:36.276  7075  7075 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
07-27 15:04:36.276  7075  7075 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
,07-27 15:04:36.276  7075  7075 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
07-27 15:04:36.276  7075  7075 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-27 15:04:36.276  7075  7075 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:4:36
07-27 15:04:36.280  6836  7270 V FormManager: Network unavailable.
07-27 15:04:36.302  6749  6749 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-27 15:04:36.302  6749  6749 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-27 15:04:36.302  6749  6749 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-27 15:04:36.302  6749  6749 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-27 15:04:36.303  6749  6749 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-27 15:04:36.303  7272  7272 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=36 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
07-27 15:04:36.303  6749  6749 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-27 15:04:36.303  6749  6749 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
07-27 15:04:36.303  6749  6749 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-27 15:04:36.303  6749  6749 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-27 15:04:36.303  6749  6749 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-27 15:04:36.304  6749  6749 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,07-27 15:04:36.311  6769  6769 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-27 15:04:36.316  6749  6749 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,07-27 15:04:36.321  6749  6749 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 15:04:36.334  6836  7275 W FormManager: Network not available. Please check & try again.
,07-27 15:04:36.338  6769  6769 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-27 15:04:36.342  6749  6749 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-27 15:04:36.342  6836  7276 V FormManager: Network unavailable.
07-27 15:04:36.344  6836  7276 V FormManager: Network unavailable.
,07-27 15:04:36.348  7272  7272 I dex2oat : dex2oat took 44.868ms (threads: 4)
07-27 15:04:36.352  6749  6749 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 15:04:36.355  6836  7280 W FormManager: Network not available. Please check & try again.
07-27 15:04:36.359  7143  7160 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-27 15:04:36.359  7143  7160 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-27 15:04:36.359  7143  7160 I Adreno-EGL: Build Date: 12/12/14 금
07-27 15:04:36.359  7143  7160 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-27 15:04:36.359  7143  7160 I Adreno-EGL: Remote Branch: 
07-27 15:04:36.359  7143  7160 I Adreno-EGL: Local Patches: 
07-27 15:04:36.359  7143  7160 I Adreno-EGL: Reconstruct Branch: 
07-27 15:04:36.365  4320  4320 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
07-27 15:04:36.365  4320  4320 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,07-27 15:04:36.365  6836  7281 V FormManager: Network unavailable.
07-27 15:04:36.367  4320  4320 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-27 15:04:36.367  6836  7281 V FormManager: Network unavailable.
07-27 15:04:36.368  4320  4320 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,07-27 15:04:36.379  4320  7282 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,07-27 15:04:36.381  4320  7283 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
07-27 15:04:36.381  4320  7283 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-27 15:04:36.416  1033  2034 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7285 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,07-27 15:04:36.451  7143  7160 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-27 15:04:36.451  7143  7160 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-27 15:04:36.451  7143  7160 I Adreno-EGL: Build Date: 12/12/14 금
07-27 15:04:36.451  7143  7160 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-27 15:04:36.451  7143  7160 I Adreno-EGL: Remote Branch: 
07-27 15:04:36.451  7143  7160 I Adreno-EGL: Local Patches: 
07-27 15:04:36.451  7143  7160 I Adreno-EGL: Reconstruct Branch: 
,07-27 15:04:36.501  6595  6910 D UEI.SmartControl: Internal timer expired: 2
07-27 15:04:36.501  6595  6910 D UEI.SmartControl: unbind internal service
,07-27 15:04:36.515  7285  7285 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-27 15:04:36.515  7285  7285 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
07-27 15:04:36.519  7143  7160 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-27 15:04:36.519  7143  7160 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-27 15:04:36.519  7143  7160 I Adreno-EGL: Build Date: 12/12/14 금
07-27 15:04:36.519  7143  7160 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-27 15:04:36.519  7143  7160 I Adreno-EGL: Remote Branch: 
07-27 15:04:36.519  7143  7160 I Adreno-EGL: Local Patches: 
07-27 15:04:36.519  7143  7160 I Adreno-EGL: Reconstruct Branch: 
07-27 15:04:36.526  7285  7285 V [BNRBootReceiver]: Boot Receiver Return
07-27 15:04:36.527  7285  7285 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-27 15:04:36.530  6386  6386 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-27 15:04:36.540  6749  6749 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 15:04:36.545  6749  6749 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-27 15:04:36.556  6799  6799 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 15:04:36.556  6799  6799 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 15:04:36.557  6799  6799 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-27 15:04:36.564  6386  6386 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-27 15:04:36.579  6749  6749 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 15:04:36.592  6749  6749 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 15:04:36.595  6595  6904 D serial_port: close(fd = 24)
,07-27 15:04:36.600  6595  6904 I UEI.SmartControl: Serial port is closed.
,07-27 15:04:36.603  6799  6799 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 15:04:36.604  6799  6799 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 15:04:36.605  6799  6799 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-27 15:04:36.613  6749  6749 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,07-27 15:04:36.617  6749  6749 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
07-27 15:04:36.621  6386  6386 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 15:04:36.633  6749  6749 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 15:04:36.640  6749  6749 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 15:04:36.647  6799  6799 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 15:04:36.648  6799  6799 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 15:04:36.649  6799  6799 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,07-27 15:04:36.653  6386  6386 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 15:04:36.662  6749  6749 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 15:04:36.671  6749  6749 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 15:04:36.681  6799  6799 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-27 15:04:36.682  6799  6799 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-27 15:04:36.682  6799  6799 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-27 15:04:36.689  6386  6386 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 15:04:36.701  6749  6749 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 15:04:36.707  6749  6749 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 15:04:36.717  6799  6799 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-27 15:04:36.718  6799  6799 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 15:04:36.718  6799  6799 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-27 15:04:36.725  6386  6386 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 15:04:36.737  6749  6749 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 15:04:36.743  6749  6749 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 15:04:36.751  6799  6799 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-27 15:04:36.751  6799  6799 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 15:04:36.751  6799  6799 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-27 15:04:36.753  6386  6386 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-27 15:04:36.770  6749  6749 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 15:04:36.777  6749  6749 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 15:04:36.788  6799  6799 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-27 15:04:36.789  6799  6799 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 15:04:36.789  6799  6799 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-27 15:04:36.799  6386  6386 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 15:04:36.816  6749  6749 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 15:04:36.823  6749  6749 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 15:04:36.837  6799  6799 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 15:04:36.837  6799  6799 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-27 15:04:36.845  6799  6799 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-27 15:04:36.850   309  7304 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
07-27 15:04:36.851  1033  1096 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-27 15:04:36.851  1818  7129 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
07-27 15:04:36.853  6386  6386 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-27 15:04:36.867  6749  6749 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-27 15:04:36.868  1818  7129 I CheckinService: active receiver: disabled
,07-27 15:04:36.876  6749  6749 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-27 15:04:36.883  6799  6799 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 15:04:36.883  6799  6799 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 15:04:36.884  6799  6799 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,07-27 15:04:36.887  6386  6386 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 15:04:36.890  6769  6769 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
07-27 15:04:36.897  1033  1544 D WifiService: New client listening to asynchronous messages
,07-27 15:04:36.900  6769  6769 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-27 15:04:36.903  6749  6749 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-27 15:04:36.908  6749  6749 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-27 15:04:36.917  6799  6799 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 15:04:36.918  6799  6799 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 15:04:36.920  6799  6799 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,07-27 15:04:36.923  6799  6799 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,07-27 15:04:36.924  6799  6799 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,07-27 15:04:36.929  6386  6386 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 15:04:36.936  6769  6769 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
07-27 15:04:36.938  6769  6769 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-27 15:04:36.944  6749  6749 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-27 15:04:36.952  6749  6749 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-27 15:04:36.960  6799  6799 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 15:04:36.961  6799  6799 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 15:04:36.962  6799  6799 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
07-27 15:04:36.964  6799  6799 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
07-27 15:04:36.965  6799  6799 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
07-27 15:04:36.973  1033  2015 I ActivityManager: Killing 6729:com.lge.lifetracker/u0a37 (adj 15): empty #17
,07-27 15:04:37.062  1033  1889 W libprocessgroup: failed to open /acct/uid_10037/pid_6729/cgroup.procs: No such file or directory
,07-27 15:04:37.068  2188  2188 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
07-27 15:04:37.083  2188  2188 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
07-27 15:04:37.085  2188  2188 D c       : Getting all permits...
,07-27 15:04:37.085  2188  2188 D a       : Opening database...
,07-27 15:04:37.096  2188  2188 D a       : Opening database auth.proximity.permit_store...
,07-27 15:04:37.098  2188  2188 D a       : Closing database...
07-27 15:04:37.123  6386  6386 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-27 15:04:37.134  6769  6769 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-27 15:04:37.134  6769  6769 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-27 15:04:37.135  6769  6769 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-27 15:04:37.144  6749  6749 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 15:04:37.157  6749  6749 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-27 15:04:37.172  6799  6799 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 15:04:37.173  6799  6799 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-27 15:04:37.178  6799  6799 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-27 15:04:37.185  6386  6386 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 15:04:37.190  6769  6769 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-27 15:04:37.190  6769  6769 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,07-27 15:04:37.190  6769  6769 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-27 15:04:37.199  6749  6749 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 15:04:37.214  6749  6749 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 15:04:37.231  6799  6799 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 15:04:37.232  6799  6799 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 15:04:37.234  6799  6799 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,07-27 15:04:37.241  6386  6386 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 15:04:37.246  6769  6769 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-27 15:04:37.246  6769  6769 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-27 15:04:37.247  6769  6769 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-27 15:04:37.256  6749  6749 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 15:04:37.263  6749  6749 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 15:04:37.271  6799  6799 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-27 15:04:37.272  6799  6799 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 15:04:37.275  6799  6799 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-27 15:04:37.293  6769  6769 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-27 15:04:37.299  6749  6749 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-27 15:04:37.308  6836  7309 W FormManager: Network not available. Please check & try again.
07-27 15:04:37.309  6749  6749 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-27 15:04:37.322  6836  7310 V FormManager: Network unavailable.
07-27 15:04:37.334  6836  7310 V FormManager: Network unavailable.
,07-27 15:04:37.347  4320  4320 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,07-27 15:04:37.348   309  7315 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
07-27 15:04:37.349  1033  1096 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-27 15:04:37.349  4320  4320 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-27 15:04:37.351  4320  4320 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-27 15:04:37.356  4320  4320 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-27 15:04:37.367  4320  7316 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,07-27 15:04:37.372  6769  6769 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
07-27 15:04:37.372  6769  6769 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-27 15:04:37.372  6769  6769 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-27 15:04:37.376  4320  7317 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
07-27 15:04:37.376  4320  7317 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-27 15:04:37.378  6749  6749 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-27 15:04:37.382  6836  7319 W FormManager: Network not available. Please check & try again.
,07-27 15:04:37.389  6836  7320 V FormManager: Network unavailable.
07-27 15:04:37.391  6749  6749 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 15:04:37.396  6836  7320 V FormManager: Network unavailable.
,07-27 15:04:37.407  2188  2188 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
07-27 15:04:37.971  1033  1537 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:745862739] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-27 15:04:37.974  1033  1537 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:745862742] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-27 15:04:38.062  1033  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-27 15:04:38.083  1033  1098 D Tethering: MasterInitialState.processMessage what=3
,07-27 15:04:38.090  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:38.092  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:38.097  1033  1092 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,07-27 15:04:38.103  6386  6386 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
07-27 15:04:38.106  5751  5751 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
07-27 15:04:38.108  6386  6412 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,07-27 15:04:38.135  2188  2188 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,07-27 15:04:38.175  6943  6943 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
07-27 15:04:38.175  6943  6943 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
07-27 15:04:38.175  6943  6943 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-27 15:04:38.175  6943  6943 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,07-27 15:04:38.181  6943  6943 I AppUp4:CustModeStarterReceiver: onReceive
07-27 15:04:38.184  6943  6943 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@9826d32
07-27 15:04:38.184  6943  6943 D AppUp4:CustFacade: isCustomizationCompleted : false
07-27 15:04:38.184  6943  6943 D AppUp4:CustFacade: isPhone : true
07-27 15:04:38.190  1033  1092 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:38.195  6943  6943 I art     : WaitForGcToComplete blocked for 10.167ms for cause DisableMovingGc
07-27 15:04:38.195  6943  6943 D AppUp4:CustModeStarterReceiver: begin check event
07-27 15:04:38.195  6943  6943 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
07-27 15:04:38.200  4320  4320 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
07-27 15:04:38.200  4320  4320 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-27 15:04:38.202  4320  4320 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-27 15:04:38.207  4320  4320 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,07-27 15:04:38.223  6966  6966 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,07-27 15:04:38.228  4320  7339 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-27 15:04:38.239  4320  7340 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
07-27 15:04:38.240  4320  7340 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,07-27 15:04:38.248  6836  7344 W FormManager: Network not available. Please check & try again.
07-27 15:04:38.254  6966  7341 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-27 15:04:38.259  3422  3422 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,07-27 15:04:38.259  3422  3422 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
07-27 15:04:38.259  3422  3422 I LgeMiscReceiver: networkInfo.isConnected() = true
07-27 15:04:38.259  3422  3422 D PhoneState: setPdpRejectCasuse : false
07-27 15:04:38.262  7017  7017 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
07-27 15:04:38.262  7017  7017 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
07-27 15:04:38.266  6836  7345 V FormManager: Network unavailable.
,07-27 15:04:38.273  7075  7075 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:4:38
07-27 15:04:38.276  6836  7345 V FormManager: Network unavailable.
,07-27 15:04:38.276  7075  7075 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,07-27 15:04:38.276  7075  7075 D Weather.Utils: 2 : All the weather widget is gone.
07-27 15:04:38.276  7075  7075 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-27 15:04:38.276  7075  7075 D WeatherAncestor: connectivity changed - connection : true
,07-27 15:04:38.276  7075  7075 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2daef400
07-27 15:04:38.277  7075  7075 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
07-27 15:04:38.277  7075  7075 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
07-27 15:04:38.277  7075  7075 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
07-27 15:04:38.277  7075  7075 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-27 15:04:38.278  7075  7075 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:4:38
07-27 15:04:38.868  1033  1870 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 15:04:38.869  1033  1870 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,07-27 15:04:38.908  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-27 15:04:38.908  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-27 15:04:38.908  1033  1033 D Ulp_jni : JNI:system_update. Event-4
07-27 15:04:38.909  1033  1098 D BluetoothManagerService: Message: 1
07-27 15:04:38.909  1033  1098 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
07-27 15:04:38.936  1033  1098 D BluetoothManagerService: Message: 20
07-27 15:04:38.936  1033  1098 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3d131d13:true
,07-27 15:04:38.942  6883  6883 D BluetoothAdapterState: make
07-27 15:04:38.947  6883  6883 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
07-27 15:04:38.947  6883  6883 I bluedroid-qcom: init
07-27 15:04:38.949  6883  7359 I BluetoothAdapterState: Entering OffState
07-27 15:04:38.949  6883  6883 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
07-27 15:04:38.949  6883  6883 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-27 15:04:38.949  6883  6883 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-27 15:04:38.949  6883  6883 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-27 15:04:38.949  6883  6883 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
07-27 15:04:38.952  6883  6883 I bluedroid-qcom: get_profile_interface socket
07-27 15:04:38.952  6883  6883 I bluedroid-qcom: get_profile_interface map_client
,07-27 15:04:38.957  6883  7363 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
07-27 15:04:38.961  6883  7363 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
07-27 15:04:38.952  7362  7362 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 15:04:38.952  7362  7362 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 15:04:38.971  7362  7362 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
07-27 15:04:38.971  7362  7362 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
07-27 15:04:38.971  7362  7362 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,07-27 15:04:38.978  1033  1033 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
07-27 15:04:38.978  1033  1033 D BluetoothManagerService: Bluetooth Adapter name changed to G3
07-27 15:04:38.978  1033  1033 D BluetoothManagerService: Stored Bluetooth name: G3
07-27 15:04:38.979  1033  1098 D BluetoothManagerService: Message: 40
07-27 15:04:38.979  1033  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
07-27 15:04:38.979  6883  6898 I bluedroid-qcom: config_hci_snoop_log
07-27 15:04:38.981  1033  1098 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
07-27 15:04:38.981  1033  1098 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
07-27 15:04:38.982  7362  7362 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
07-27 15:04:38.996  6883  7359 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,07-27 15:04:38.999  1033  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-27 15:04:39.001  7362  7362 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
07-27 15:04:39.001  7362  7362 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
07-27 15:04:39.006  1033  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-27 15:04:39.012  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 15:04:39.024  1033  1098 D Tethering: MasterInitialState.processMessage what=3
07-27 15:04:39.027  6386  6386 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,07-27 15:04:39.035  1033  1098 D Tethering: MasterInitialState.processMessage what=3
07-27 15:04:39.037  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:39.038  6883  7363 D BluetoothAdapterProperties: Name is: G3
07-27 15:04:39.039  6883  7359 D BluetoothAdapterProperties: Setting state to 11
07-27 15:04:39.039  6883  7359 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
07-27 15:04:39.040  1033  1098 D BluetoothManagerService: Message: 60
07-27 15:04:39.040  1033  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
07-27 15:04:39.040  1033  1098 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
07-27 15:04:39.041  6883  7359 I LGBluetoothServiceJni: classInitNative: succeeds
07-27 15:04:39.048  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:39.051  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:39.054  6883  7359 D BluetoothBondStateMachine: make
07-27 15:04:39.055  1944  1944 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-27 15:04:39.056  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-27 15:04:39.059  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:39.060  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 15:04:39.064  6749  6749 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
07-27 15:04:39.066  1033  1092 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-27 15:04:39.070  6883  6883 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-27 15:04:39.071  6883  6883 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-27 15:04:39.071  6883  6883 V BluetoothPbapReceiver: ***********state = 11
07-27 15:04:39.073  2188  2188 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-27 15:04:39.078  6883  7380 I BluetoothBondStateMachine: StableState(): Entering Off State
07-27 15:04:39.078  6883  7359 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2daef400
07-27 15:04:39.078  6883  7359 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
07-27 15:04:39.078  6883  7359 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2daef400
07-27 15:04:39.079  6883  7359 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
07-27 15:04:39.079  6883  7359 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
07-27 15:04:39.080  1033  1092 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-27 15:04:39.082  6883  7359 E BluetoothAdapterService: File transfer profiles supported!!
07-27 15:04:39.085  6386  6412 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
07-27 15:04:39.121  1033  1870 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7382 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,07-27 15:04:39.127  6883  7359 E BluetoothAdapterService: File transfer profiles supported!!
07-27 15:04:39.128  6883  6883 D HeadsetService: Received start request. Starting profile...
07-27 15:04:39.129  6883  6883 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
07-27 15:04:39.129  6883  6883 D LGBluetoothHfpAdapter: Version 1.6
07-27 15:04:39.131  6883  6883 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-27 15:04:39.132  6883  6883 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-27 15:04:39.132  5751  5751 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
07-27 15:04:39.132  6883  6883 D HeadsetStateMachine: make
07-27 15:04:39.145  6883  7359 E BluetoothAdapterService: File transfer profiles supported!!
07-27 15:04:39.145  1033  1092 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:39.145  1033  1092 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:39.152  6883  7359 E BluetoothAdapterService: File transfer profiles supported!!
07-27 15:04:39.153  5751  5751 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
07-27 15:04:39.156  6883  7359 E BluetoothAdapterService: File transfer profiles supported!!
07-27 15:04:39.162  6883  7359 E BluetoothAdapterService: File transfer profiles supported!!
,07-27 15:04:39.163  6883  6883 D LgDataFeature: LgDataFeature() Constructor: none
07-27 15:04:39.163  6883  6883 D LgDataFeature: LgDataFeature() Constructor Done, null
07-27 15:04:39.166  6883  7359 E BluetoothAdapterService: File transfer profiles supported!!
07-27 15:04:39.169  6883  6883 D HeadsetStateMachine: max_hf_connections = 1
07-27 15:04:39.169  6883  6883 I bluedroid-qcom: get_profile_interface handsfree
07-27 15:04:39.171  6883  6883 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
07-27 15:04:39.171   315  2148 V AudioPolicyService: registerClient() client 0xb1021c80, uid 1002
07-27 15:04:39.171   315   315 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
07-27 15:04:39.171   315   315 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-27 15:04:39.171   315   315 V AudioPolicyManagerEx: getOutput() returns output 2
07-27 15:04:39.172  6883  6883 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
07-27 15:04:39.172   315  1384 V AudioFlinger: registerClient() client 0xb1433088, pid 6883
07-27 15:04:39.172   315  1378 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-27 15:04:39.172   315  1378 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-27 15:04:39.173  1033  2015 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
,07-27 15:04:39.173  1033  2015 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-27 15:04:39.173  1853  1868 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-27 15:04:39.173  1853  1868 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-27 15:04:39.173  3422  3439 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-27 15:04:39.173  3422  3439 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-27 15:04:39.173   315  1379 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-27 15:04:39.173   315  1379 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-27 15:04:39.173  1604  3134 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-27 15:04:39.173  1604  3134 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-27 15:04:39.173  1604  2099 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-27 15:04:39.173  1604  2099 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-27 15:04:39.173  3422  3438 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-27 15:04:39.173  1853  2461 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-27 15:04:39.173  3422  3438 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-27 15:04:39.173  1853  2461 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-27 15:04:39.173  1033  1943 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-27 15:04:39.173  6883  6883 V ToneGenerator: Create Track: 0xb4927680
07-27 15:04:39.173  1033  1943 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-27 15:04:39.173  6883  6883 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
07-27 15:04:39.173  6883  6883 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
07-27 15:04:39.174   315  2147 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
07-27 15:04:39.174   315  2147 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
07-27 15:04:39.174   315  2147 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-27 15:04:39.174  6883  6899 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-27 15:04:39.174   315  2147 V AudioPolicyManagerEx: getOutput() returns output 2
07-27 15:04:39.174  6883  6899 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
07-27 15:04:39.174  6883  6899 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-27 15:04:39.174  6883  6899 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
07-27 15:04:39.174   315  2148 I AudioFlinger: isAudioPlaybackHookOn() false
07-27 15:04:39.174   315   315 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
07-27 15:04:39.174   315   315 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
07-27 15:04:39.174   315   315 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-27 15:04:39.174   315   315 V AudioPolicyManagerEx: getOutput() returns output 2
07-27 15:04:39.175  6883  6883 V AudioSystem: getLatency() output 2, latency 50
07-27 15:04:39.175  6883  6883 V AudioSystem: getFrameCount() output 2, frameCount 960
07-27 15:04:39.175  6883  6883 V AudioTrack: createTrack_l() output 2 afLatency 50
07-27 15:04:39.176   315  1384 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
07-27 15:04:39.176   315  1384 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
07-27 15:04:39.176   315  1384 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
07-27 15:04:39.176   315  1384 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
07-27 15:04:39.176   315  13,84 V AudioFlinger: createTrack() lSessionId: 22
07-27 15:04:39.178  2188  2188 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
07-27 15:04:39.178  6883  6883 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
07-27 15:04:39.179   315  1384 V AudioFlinger: acquiring 22 from 6883, for 6883
07-27 15:04:39.179   315  1384 V AudioFlinger:  added new entry for 22
07-27 15:04:39.179  6883  6883 V ToneGenerator: ToneGenerator INIT OK, time: 141865
07-27 15:04:39.179  6883  6883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2daef400
07-27 15:04:39.180  6883  7398 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
07-27 15:04:39.180  6883  7398 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-27 15:04:39.180  6883  7398 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-27 15:04:39.181  6883  7398 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
07-27 15:04:39.181   315  1383 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6883
07-27 15:04:39.181  6883  6883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2daef400
07-27 15:04:39.183  6883  6883 D A2dpService: Received start request. Starting profile...
07-27 15:04:39.183  6883  6883 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-27 15:04:39.184  6883  6883 V Avrcp   : make
07-27 15:04:39.184  6883  6883 D Avrcp   : [BTUI] Use Native AVRCP : init jni
07-27 15:04:39.184  6883  6883 I bluedroid-qcom: get_profile_interface avrcp
07-27 15:04:39.185   315  1383 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
07-27 15:04:39.185   315  1383 V voice   : voice_set_parameters: enter: bt_samplerate=8000
07-27 15:04:39.185   315  1383 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
07-27 15:04:39.185   315  1383 V compress_voip: voice_extn_compress_voip_set_parameters: exit
07-27 15:04:39.185   315  1383 V voice   : voice_set_parameters: exit with code(0)
07-27 15:04:39.185   315  1383 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
07-27 15:04:39.185   315  1383 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
07-27 15:04:39.185  6883  7359 V LGMDMManager: Create singleton instance
07-27 15:04:39.185   315  1383 V msm8974_platform: platform_set_parameters: exit with code(0)
07-27 15:04:39.185   315  1383 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
07-27 15:04:39.185   315  1383 V audio_hw_primary: adev_set_parameters: exit with code(0)
07-27 15:04:39.185   315  1383 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
07-27 15:04:39.186  6943  6943 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
07-27 15:04:39.186  6943  6943 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
07-27 15:04:39.186  6943  6943 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-27 15:04:39.186  6943  6943 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
07-27 15:04:39.188  6883  7398 V ToneGenerator: ToneGenerator destructor
07-27 15:04:39.188  6883  7398 V ToneGenerator: stopTone
07-27 15:04:39.188  6883  7398 V ToneGenerator: Delete Track: 0xb4927680
07-27 15:04:39.188  6883  7398 V AudioTrack: ~AudioTrack, releasing session id from 6883 on behalf of 6883
07-27 15:04:39.188   315  2148 V AudioPolicyService: AudioCommandThread() adding release output 2
07-27 15:04:39.188   315  2148 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
07-27 15:04:39.188   315  2148 V AudioFlinger: PlaybackThread::Track destructor
07-27 15:04:39.188   315  2148 V AudioFlinger: removeClient_l() pid 688,3, calling pid 315
07-27 15:04:39.188   315  1229 V AudioPolicyService: AudioCommandThread() waking up
07-27 15:04:39.188   315  1229 V AudioPolicyService: AudioCommandThread() processing release output 2
07-27 15:04:39.188   315  1229 V AudioPolicyManager: releaseOutput() 2
07-27 15:04:39.188   315  2148 V AudioFlinger: releasing 22 from 6883 for 6883
07-27 15:04:39.188   315  1229 V AudioPolicyService: AudioCommandThread() going to sleep
07-27 15:04:39.189   315  2148 V AudioFlinger:  decremented refcount to 0
07-27 15:04:39.189  6883  7359 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
07-27 15:04:39.189   315  2148 V AudioFlinger: purging stale effects
07-27 15:04:39.190  6943  6943 I AppUp4:CustModeStarterReceiver: onReceive
07-27 15:04:39.199  6883  6883 V AudioManager: registerRemoteController: size of Media player list: 0
07-27 15:04:39.202  6883  6883 E AudioManager: No RCC entry present to update
07-27 15:04:39.202  6883  6883 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
07-27 15:04:39.205  6883  6883 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
07-27 15:04:39.205  6883  6883 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
07-27 15:04:39.205  6883  6883 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
07-27 15:04:39.207  6943  6943 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@9826d32
07-27 15:04:39.207  6943  6943 D AppUp4:CustFacade: isCustomizationCompleted : false
07-27 15:04:39.207  6943  6943 D AppUp4:CustFacade: isPhone : true
,07-27 15:04:39.208  6943  6943 D AppUp4:CustModeStarterReceiver: begin check event
07-27 15:04:39.208  6943  6943 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
07-27 15:04:39.211  6883  6883 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
07-27 15:04:39.214  4320  4320 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
07-27 15:04:39.214  4320  4320 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-27 15:04:39.215  4320  4320 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-27 15:04:39.245  7382  7382 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,07-27 15:04:39.245  7382  7382 W LG Account v2.2: No ProfileInfo entries
07-27 15:04:39.245  7382  7382 I LG Account v2.2: isEnabled: false
,07-27 15:04:39.246  7382  7382 I Feature : [Lifetracker]ver: 4.21.112(40211120)
07-27 15:04:39.246  7382  7382 I Feature : [Lifetracker]Country: EU
07-27 15:04:39.246  7382  7382 I Feature : [Lifetracker]Operator: OPEN
07-27 15:04:39.246  7382  7382 I Feature : [Lifetracker]Ranking support: false
07-27 15:04:39.246  7382  7382 I Feature : [Lifetracker]Comfort support: false
07-27 15:04:39.246  7382  7382 I Feature : [Lifetracker]Accessory: true
07-27 15:04:39.246  7382  7382 I Feature : [Lifetracker]Health device: true
07-27 15:04:39.246  7382  7382 I Feature : [Lifetracker]Extra Pedometer: false
07-27 15:04:39.246  7382  7382 I Feature : [Lifetracker]Blood glucose device: false
07-27 15:04:39.246  7382  7382 I Feature : [Lifetracker]Device Number: 3
07-27 15:04:39.250  4320  4320 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-27 15:04:39.261  6749  6749 D BluetoothPermissionRequest: onReceive
,07-27 15:04:39.265  6749  6749 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-27 15:04:39.265  6966  6966 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
07-27 15:04:39.267  4320  7406 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-27 15:04:39.272  4320  7407 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
07-27 15:04:39.273  4320  7407 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-27 15:04:39.291  6966  7408 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-27 15:04:39.293  1033  1051 V SIM_STK : Menu title from STK is T-Mobile
07-27 15:04:39.293  1033  1051 V SIM_STK : Menu title from STK is T-Mobile
07-27 15:04:39.296  3422  3422 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
07-27 15:04:39.297  3422  3422 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
07-27 15:04:39.297  3422  3422 I LgeMiscReceiver: networkInfo.isConnected() = false
07-27 15:04:39.301  7017  7017 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
07-27 15:04:39.301  7017  7017 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
07-27 15:04:39.313  7075  7075 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:4:39
,07-27 15:04:39.315  7075  7075 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
07-27 15:04:39.316  7075  7075 D Weather.Utils: 2 : All the weather widget is gone.
07-27 15:04:39.316  7075  7075 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-27 15:04:39.316  6836  7411 W FormManager: Network not available. Please check & try again.
07-27 15:04:39.316  7075  7075 D WeatherAncestor: connectivity changed - connection : true
07-27 15:04:39.316  7075  7075 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2daef400
07-27 15:04:39.317  6836  7412 V FormManager: Network unavailable.
07-27 15:04:39.318  7075  7075 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
07-27 15:04:39.318  7075  7075 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
07-27 15:04:39.318  7075  7075 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
07-27 15:04:39.318  7075  7075 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-27 15:04:39.318  7075  7075 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:4:39
07-27 15:04:39.326  6836  7412 V FormManager: Network unavailable.
,07-27 15:04:39.340  6386  6386 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,07-27 15:04:39.342  6386  6412 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
07-27 15:04:39.349  1033  1980 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
07-27 15:04:39.354  6883  6883 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,07-27 15:04:39.357  6883  6883 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
07-27 15:04:39.358  2188  2188 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
07-27 15:04:39.358  6883  6883 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
07-27 15:04:39.358  6883  6883 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
07-27 15:04:39.358  6883  6883 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
07-27 15:04:39.358  6883  6883 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-27 15:04:39.358  6883  6883 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
07-27 15:04:39.358  6883  6883 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
07-27 15:04:39.358  6883  6883 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
07-27 15:04:39.358  6883  6883 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-27 15:04:39.358  6883  6883 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
07-27 15:04:39.358  6883  6883 I BluetoothA2dpServiceJni: classInitNative
07-27 15:04:39.359  6883  6883 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-27 15:04:39.359  6883  6883 D A2dpStateMachine: make
07-27 15:04:39.360  6883  6883 I bluedroid-qcom: get_profile_interface a2dp
07-27 15:04:39.360  6883  7414 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
07-27 15:04:39.362  6883  6883 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
07-27 15:04:39.362  6883  6883 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
07-27 15:04:39.363  6883  6883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2daef400
07-27 15:04:39.363  6883  7413 D A2dpStateMachine: Enter Disconnected: -2
07-27 15:04:39.364  6883  6883 I BluetoothHidServiceJni: classInitNative: succeeds
07-27 15:04:39.365  6943  6943 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
07-27 15:04:39.365  6943  6943 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
07-27 15:04:39.365  6943  6943 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-27 15:04:39.365  6943  6943 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
07-27 15:04:39.365  6883  6883 D HidService: Received start request. Starting profile...
07-27 15:04:39.365  6883  6883 I bluedroid-qcom: get_profile_interface hidhost
07-27 15:04:39.366  6883  6883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2daef400
07-27 15:04:39.366  6943  6943 I AppUp4:CustModeStarterReceiver: onReceive
07-27 15:04:39.366  6883  6883 I BluetoothHealthServiceJni: classInitNative: succeeds
,07-27 15:04:39.370  6883  6883 D HealthService: Received start request. Starting profile...
07-27 15:04:39.371  6943  6943 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@9826d32
07-27 15:04:39.371  6943  6943 D AppUp4:CustFacade: isCustomizationCompleted : false
07-27 15:04:39.371  6943  6943 D AppUp4:CustFacade: isPhone : true
07-27 15:04:39.371  6943  6943 D AppUp4:CustModeStarterReceiver: begin check event
07-27 15:04:39.371  6883  6883 I bluedroid-qcom: get_profile_interface health
07-27 15:04:39.371  6943  6943 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
07-27 15:04:39.371  6883  6883 I LGBluetoothHealthServiceJni: classInitNative: succeeds
07-27 15:04:39.371  6883  6883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2daef400
07-27 15:04:39.372  6883  6883 I BluetoothPanServiceJni: classInitNative(L105): succeeds
07-27 15:04:39.373  6883  6883 D PanService: Received start request. Starting profile...
07-27 15:04:39.373  6883  6883 D BluetoothPanServiceJni: initializeNative(L110): pan
07-27 15:04:39.373  6883  6883 I bluedroid-qcom: get_profile_interface pan
07-27 15:04:39.374  4320  4320 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
07-27 15:04:39.374  4320  4320 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-27 15:04:39.376  4320  4320 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-27 15:04:39.378  4320  4320 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-27 15:04:39.378  6883  6883 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
07-27 15:04:39.378  6883  6883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2daef400
07-27 15:04:39.379  6883  6883 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,07-27 15:04:39.382  6966  6966 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
07-27 15:04:39.383  6883  6883 D BtGatt.DebugUtils: handleDebugAction() action=null
07-27 15:04:39.383  6883  6883 D BtGatt.GattService: Received start request. Starting profile...
07-27 15:04:39.383  6883  6883 D BtGatt.GattService: start()
07-27 15:04:39.383  6883  6883 I bluedroid-qcom: get_profile_interface gatt
07-27 15:04:39.383  6883  6883 D BtGatt.AdvertiseManager: advertise manager created
07-27 15:04:39.388  6883  6883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2daef400
07-27 15:04:39.388  6883  6883 D HeadsetStateMachine: Proxy object connected
07-27 15:04:39.389  6883  6883 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
07-27 15:04:39.389  4320  7423 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
07-27 15:04:39.389  6883  6883 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
07-27 15:04:39.389  4320  7423 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-27 15:04:39.389  4320  7420 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-27 15:04:39.391  6883  6883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2daef400
07-27 15:04:39.391  6883  6883 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
,07-27 15:04:39.392  6883  6883 V BluetoothMapService: BluetoothMapBinder()
07-27 15:04:39.393  6883  6883 D BluetoothMapService: Received start request. Starting profile...
07-27 15:04:39.393  6883  6883 D BluetoothMapService: start()
07-27 15:04:39.396  6883  6883 D BluetoothMapEmailSettingsLoader: Found 0 applications
07-27 15:04:39.396  6883  6883 D BluetoothMapEmailAppObserver: createReceiver()
,07-27 15:04:39.396  6836  7425 W FormManager: Network not available. Please check & try again.
07-27 15:04:39.396  6883  6883 D BluetoothMapEmailAppObserver: initObservers()
07-27 15:04:39.396  6883  6883 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
07-27 15:04:39.401  6883  6883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2daef400
07-27 15:04:39.402  6883  7398 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-27 15:04:39.402  6966  7421 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:39.402  6883  7398 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-27 15:04:39.403  6883  7398 D HeadsetStateMachine: Disconnected process message: 11, size: 0
,07-27 15:04:39.406  6883  6883 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-27 15:04:39.406  3422  3422 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
07-27 15:04:39.406  3422  3422 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
07-27 15:04:39.406  3422  3422 I LgeMiscReceiver: networkInfo.isConnected() = false
07-27 15:04:39.409  6883  6883 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-27 15:04:39.411  7017  7017 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
07-27 15:04:39.411  7017  7017 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
07-27 15:04:39.413  6883  6883 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-27 15:04:39.415  6883  6883 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-27 15:04:39.415  6883  6883 V PanService: [BTUI] SIM Extra State :ABSENT
,07-27 15:04:39.419  6883  6883 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-27 15:04:39.420  6836  7426 V FormManager: Network unavailable.
07-27 15:04:39.420  6883  6883 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
07-27 15:04:39.421  6883  6883 V BluetoothMapService: Handler(): got msg=1
07-27 15:04:39.421  6883  7359 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
07-27 15:04:39.421  6883  7359 I bluedroid-qcom: enable
07-27 15:04:39.422  6883  7428 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
07-27 15:04:39.422  6883  7428 I bt-btu  : btu_task pending for preload complete event
07-27 15:04:39.422  6883  7359 I bt_hci_bdroid: init
,07-27 15:04:39.422  7075  7075 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:4:39
07-27 15:04:39.423  6883  7359 I bt_vendor: bt-vendor : init
07-27 15:04:39.423  6883  7359 I bt_vendor: bt-vendor : get_bt_soc_type
07-27 15:04:39.423  6883  7359 E bt_vendor: get_bt_soc_type: Failed to get soc type
07-27 15:04:39.423  6883  7359 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
07-27 15:04:39.423  6883  7359 D bt_userial_mct: userial_init
07-27 15:04:39.423  6883  6883 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-27 15:04:39.423  6883  7359 D bt_hci_bdroid: set_power 1
07-27 15:04:39.423  6883  7359 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
07-27 15:04:39.423  6883  7359 I bt_vendor: Starting hciattach daemon
07-27 15:04:39.423  6883  7359 I bt_vendor: try to set true
07-27 15:04:39.424  7075  7075 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
07-27 15:04:39.424  7075  7075 D Weather.Utils: 2 : All the weather widget is gone.
07-27 15:04:39.424  6883  6883 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-27 15:04:39.424  6883  6883 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-27 15:04:39.425  6883  6883 V BluetoothSapReceiver: SapReceiver onReceive 
07-27 15:04:39.425  6883  6883 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-27 15:04:39.425  6883  6883 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
07-27 15:04:39.422  7431  7431 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 15:04:39.422  7431  7431 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 15:04:39.433  7075  7075 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-27 15:04:39.433  7075  7075 D WeatherAncestor: connectivity changed - connection : true
07-27 15:04:39.433  7075  7075 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2daef400
,07-27 15:04:39.436  7075  7075 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
07-27 15:04:39.436  7075  7075 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
07-27 15:04:39.436  7075  7075 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
07-27 15:04:39.436  7075  7075 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-27 15:04:39.436  7075  7075 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:4:39
07-27 15:04:39.440  7432  7432 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
07-27 15:04:39.440  6836  7426 V FormManager: Network unavailable.
07-27 15:04:39.488  7438  7438 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,07-27 15:04:39.498  7439  7439 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
07-27 15:04:39.519  7441  7441 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,07-27 15:04:39.543  7442  7442 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,07-27 15:04:39.558  7443  7443 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,07-27 15:04:39.572  7444  7444 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,07-27 15:04:39.612  7446  7446 I libmdmdetect: ESOC framework not supported
07-27 15:04:39.614  7446  7446 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,07-27 15:04:39.625  7446  7446 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
07-27 15:04:39.625  7446  7446 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
07-27 15:04:39.625  7446  7446 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
07-27 15:04:39.625  7446  7446 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
07-27 15:04:39.625  7446  7446 D bthci_qcomm_common: [BTUI]     LE: Class 2
07-27 15:04:39.626  7446  7446 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
07-27 15:04:39.626  7446  7446 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
07-27 15:04:39.669  7446  7447 E QC-QMI  : qmi_client [7446] 14: failed to locate client data
,07-27 15:04:39.670   453   453 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
07-27 15:04:39.670   453   453 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
07-27 15:04:39.738  7448  7448 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,07-27 15:04:39.755  7452  7452 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,07-27 15:04:39.777  6883  7359 I bt_vendor: bluetooth satus is on
07-27 15:04:39.777  6883  7359 D bt_hci_bdroid: preload
,07-27 15:04:39.777  6883  7430 D bt_userial_mct: userial_open(port:0)
,07-27 15:04:39.777  6883  7430 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
07-27 15:04:39.781  6883  7430 I bt_vendor: Done intiailizing UART
07-27 15:04:39.785  6883  7430 I bt_vendor: Done intiailizing UART
07-27 15:04:39.785  6883  7430 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
07-27 15:04:39.785  6883  7430 I bt_vendor: Bluetooth Firmware and transport layer are initialized
07-27 15:04:39.786  6883  7428 I bt-btu  : btu_task received preload complete event
07-27 15:04:39.786  6883  7454 D bt_userial_mct: Entering userial_read_thread()
07-27 15:04:39.786  6883  7428 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
07-27 15:04:39.787  6883  7428 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
07-27 15:04:39.789  6883  7428 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,07-27 15:04:39.805  6883  7428 I         : BTE_InitTraceLevels -- TRC_HCI
,07-27 15:04:39.805  6883  7428 I         : BTE_InitTraceLevels -- TRC_L2CAP
,07-27 15:04:39.805  6883  7428 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-27 15:04:39.805  6883  7428 I         : BTE_InitTraceLevels -- TRC_AVDT
07-27 15:04:39.805  6883  7428 I         : BTE_InitTraceLevels -- TRC_AVRC
07-27 15:04:39.805  6883  7428 I         : BTE_InitTraceLevels -- TRC_A2D
,07-27 15:04:39.805  6883  7428 I         : BTE_InitTraceLevels -- TRC_BNEP
07-27 15:04:39.805  6883  7428 I         : BTE_InitTraceLevels -- TRC_BTM
07-27 15:04:39.805  6883  7428 I         : BTE_InitTraceLevels -- TRC_HID_HOST
07-27 15:04:39.805  6883  7428 I         : BTE_InitTraceLevels -- TRC_GAP
07-27 15:04:39.805  6883  7428 I         : BTE_InitTraceLevels -- TRC_PAN
07-27 15:04:39.805  6883  7428 I         : BTE_InitTraceLevels -- TRC_SDP
07-27 15:04:39.806  6883  7428 I         : BTE_InitTraceLevels -- TRC_GATT
07-27 15:04:39.806  6883  7428 I         : BTE_InitTraceLevels -- TRC_SMP
07-27 15:04:39.806  6883  7428 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-27 15:04:39.806  6883  7428 I         : BTE_InitTraceLevels -- TRC_BTIF
07-27 15:04:39.852  6883  7428 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
07-27 15:04:39.852  6883  7428 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa019a061 
07-27 15:04:39.852  6883  7428 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa019a061 
,07-27 15:04:39.874  6883  7363 E bt-btif : Calling BTA_HhEnable
07-27 15:04:39.874  6883  7363 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
07-27 15:04:39.875  6883  7428 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
07-27 15:04:39.875  6883  7363 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
07-27 15:04:39.875  6883  7428 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
07-27 15:04:39.875  6883  7428 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
07-27 15:04:39.875  6883  7428 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
07-27 15:04:39.875  6883  7428 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
07-27 15:04:39.877  1033  1033 D BluetoothManagerService: Bluetooth Adapter name changed to G3
07-27 15:04:39.878  1033  1033 D BluetoothManagerService: Stored Bluetooth name: G3
07-27 15:04:39.878  6883  7363 D BluetoothAdapterProperties: Name is: G3
,07-27 15:04:39.880  6883  7363 D BluetoothAdapterProperties: Scan Mode:20
07-27 15:04:39.880  6883  7363 D BluetoothAdapterProperties: Discoverable Timeout:120
07-27 15:04:39.881  6883  7363 D bt_hci_bdroid: postload
07-27 15:04:39.881  6883  7430 D bt_hci_bdroid: Used up Tx Cmd credits
07-27 15:04:39.883  6883  7430 D bt_hci_bdroid: Used up Tx Cmd credits
07-27 15:04:39.883  6883  7430 D bt_hci_bdroid: Used up Tx Cmd credits
07-27 15:04:39.883  6883  7430 D bt_hci_bdroid: Used up Tx Cmd credits
07-27 15:04:39.884  6883  7428 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
07-27 15:04:39.885  6883  7430 D bt_hci_bdroid: Used up Tx Cmd credits
07-27 15:04:39.885  6883  7363 D bte_conf: Device ID record 1 : primary
07-27 15:04:39.885  6883  7363 D bte_conf:   vendorId            = 00c4
07-27 15:04:39.885  6883  7363 D bte_conf:   vendorIdSource      = 0001
07-27 15:04:39.885  6883  7363 D bte_conf:   product             = 13a1
07-27 15:04:39.886  6883  7363 D bte_conf:   version             = 1000
07-27 15:04:39.886  6883  7363 D bte_conf:   clientExecutableURL = 
07-27 15:04:39.886  6883  7363 D bte_conf:   serviceDescription  = 
07-27 15:04:39.886  6883  7363 D bte_conf:   documentationURL    = 
07-27 15:04:39.886  6883  7363 D bte_conf: bte_load_did_conf no section named DID2.
07-27 15:04:39.889  6883  7454 E bt_mct  : hci lib postload completed
07-27 15:04:39.893  6883  7359 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
07-27 15:04:39.894  6883  7359 D BluetoothAdapterProperties: ScanMode =  20
07-27 15:04:39.894  6883  7359 D BluetoothAdapterProperties: State =  11
,07-27 15:04:39.892  7459  7459 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 15:04:39.900  6883  7359 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
07-27 15:04:39.892  7459  7459 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 15:04:39.901  6883  7359 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
,07-27 15:04:39.901  6883  7359 D BluetoothAdapterProperties: Setting state to 12
07-27 15:04:39.901  6883  7359 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-27 15:04:39.902  6883  7428 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-27 15:04:39.902  6883  7428 W bt-smp  : Plain text(LSB ~ MSB) = 12 13 73 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-27 15:04:39.905  6883  7428 W bt-smp  : Encrypted text(LSB ~ MSB) = 29 79 3a 7f 06 86 de 01 91 6b 3f 2a b1 b8 6e 0c 
07-27 15:04:39.905  6883  7428 W bt-btm  : Stopping oneshot timer
07-27 15:04:39.906  6883  7363 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-27 15:04:39.906  6883  7363 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,07-27 15:04:39.923  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 15:04:39.923  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:39.923  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:39.923  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 15:04:39.923  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 15:04:39.923  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 15:04:39.923  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 15:04:39.923  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 15:04:39.925  1033  1098 D BluetoothManagerService: Message: 60
07-27 15:04:39.925  1033  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
07-27 15:04:39.925  1033  1098 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
07-27 15:04:39.925  1033  1098 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 15:04:39.927  6883  7428 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-27 15:04:39.927  6883  7428 W bt-smp  : Plain text(LSB ~ MSB) = db f9 7e 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-27 15:04:39.927  6883  7428 W bt-smp  : Encrypted text(LSB ~ MSB) = 26 cf d9 3e f5 cb a9 22 cb e6 7d c9 12 8c c7 bd 
07-27 15:04:39.927  6883  7428 W bt-btm  : Stopping oneshot timer
07-27 15:04:39.929  6883  7359 I BluetoothAdapterState: Entering On State
07-27 15:04:39.930  6632  6632 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-27 15:04:39.932  6883  7363 D BluetoothAdapterProperties: Discoverable Timeout:120
07-27 15:04:39.932  6883  7363 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
07-27 15:04:39.938  1033  1033 D BluetoothHeadset: Proxy object connected
,07-27 15:04:39.941  6883  7428 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-27 15:04:39.941  6883  7428 W bt-smp  : Plain text(LSB ~ MSB) = b2 4c 5c 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-27 15:04:39.941  6883  7428 W bt-smp  : Encrypted text(LSB ~ MSB) = 64 41 08 8f 83 92 ac 21 59 71 dc 2c 3b 7d db ba 
07-27 15:04:39.941  6883  7428 W bt-btm  : Stopping oneshot timer
07-27 15:04:39.942  6883  7359 D LGBluetoothServiceAdapter: [BTUI] OnState
07-27 15:04:39.942  6883  7359 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
07-27 15:04:39.942  6883  7359 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
07-27 15:04:39.943  6883  7359 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
07-27 15:04:39.947  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 15:04:39.947  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:39.947  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:39.947  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 15:04:39.947  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 15:04:39.947  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 15:04:39.947  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 15:04:39.947  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 15:04:39.950  6749  6765 D BluetoothPbap: onBluetoothStateChange: up=true
,07-27 15:04:39.954  6883  7428 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-27 15:04:39.954  6883  7428 W bt-smp  : Plain text(LSB ~ MSB) = e3 02 6b 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-27 15:04:39.954  6883  7428 W bt-smp  : Encrypted text(LSB ~ MSB) = 86 a0 a6 f8 a7 b5 68 53 b3 49 f6 b2 9d fd 9d b0 
07-27 15:04:39.954  6883  7428 W bt-btm  : Stopping oneshot timer
07-27 15:04:39.963  1853  1869 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 15:04:39.965  6632  6632 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-27 15:04:39.966  1853  1853 D BluetoothHeadset: Proxy object connected
,07-27 15:04:39.967  1853  2461 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 15:04:39.969  1853  1853 D BluetoothHeadset: Proxy object connected
07-27 15:04:39.970  1853  1869 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 15:04:39.972  1853  1853 D BluetoothHeadset: Proxy object connected
07-27 15:04:39.972  6883  7428 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-27 15:04:39.973  6883  7428 W bt-smp  : Plain text(LSB ~ MSB) = 7a 8c 5b 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-27 15:04:39.973  6883  7428 W bt-smp  : Encrypted text(LSB ~ MSB) = 97 d8 0e af 52 0b 67 66 99 1c cf f8 e7 5c f6 29 
07-27 15:04:39.973  6883  7428 W bt-btm  : Stopping oneshot timer
07-27 15:04:39.974  6749  6764 D BluetoothMap: onBluetoothStateChange: up=true
07-27 15:04:39.979  7475  7475 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
07-27 15:04:39.980  6883  7359 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
07-27 15:04:39.981  6749  6764 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-27 15:04:39.984  6749  6749 D BluetoothMap: Proxy object connected
07-27 15:04:39.984  6749  6749 D MapProfile: Bluetooth service connected
07-27 15:04:39.984  6749  6749 D BluetoothMap: getConnectedDevices()
07-27 15:04:39.995  1033  1098 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-27 15:04:39.996  6749  6765 D BluetoothPan: onBluetoothStateChange on: true
07-27 15:04:39.996  6749  6765 D BluetoothPan: onBluetoothStateChange call bindService
07-27 15:04:39.998  1033  1033 D BluetoothA2dp: Proxy object connected
07-27 15:04:40.005  6883  6899 V BluetoothMapService: getConnectedDevices()
07-27 15:04:40.006  1033  1098 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
07-27 15:04:40.006  1033  1098 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
07-27 15:04:40.007  6749  6749 D BluetoothInputDevice: Proxy object connected
07-27 15:04:40.007  6749  6749 D HidProfile: Bluetooth service connected
07-27 15:04:40.008  1033  1033 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
07-27 15:04:40.009  1033  1098 D BluetoothManagerService: Message: 40
07-27 15:04:40.009  1033  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
07-27 15:04:40.010  6749  6749 D BluetoothPan: BluetoothPAN Proxy object connected
07-27 15:04:40.010  6749  6749 D PanProfile: Bluetooth service connected
,07-27 15:04:40.028  1944  1944 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-27 15:04:40.029  1944  2150 D LGBluetoothAPIService: Message: 1
,07-27 15:04:40.029  1944  2150 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
07-27 15:04:40.031  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-27 15:04:40.034  6632  6632 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
07-27 15:04:40.036  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:40.039  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:40.039  1944  2150 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
07-27 15:04:40.041  6883  6883 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,07-27 15:04:40.041  6883  6883 D BluetoothMapService: STATE_ON
07-27 15:04:40.043  6883  6883 D LGBluetoothAPIServer: [BTUI] onCreate()
07-27 15:04:40.043  6883  6883 D LGBluetoothAPIServer: [BTUI] onBind()
07-27 15:04:40.045  1944  1944 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
07-27 15:04:40.045  1944  2150 D LGBluetoothAPIService: Message: 100
07-27 15:04:40.045  1944  2150 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
07-27 15:04:40.045  6749  6749 D LocalBluetoothProfileManager: Adding local A2DP profile
07-27 15:04:40.047  1033  1098 D BluetoothManagerService: Message: 30
07-27 15:04:40.049  6749  6749 D LocalBluetoothProfileManager: Adding local HEADSET profile
07-27 15:04:40.052  1033  1098 D BluetoothManagerService: Message: 30
07-27 15:04:40.055  6749  6749 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
,07-27 15:04:40.057  6749  6749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-27 15:04:40.060  6749  6749 D BluetoothA2dp: Proxy object connected
07-27 15:04:40.061  6883  6883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2daef400
07-27 15:04:40.061  6749  6749 D A2dpProfile: Bluetooth service connected
07-27 15:04:40.061  6883  6883 V BluetoothPbapService: Pbap Service onCreate
07-27 15:04:40.061  6883  6883 V BluetoothPbapService: Starting PBAP service
07-27 15:04:40.062  6749  6749 D BluetoothHeadset: Proxy object connected
07-27 15:04:40.062  6883  6883 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
07-27 15:04:40.062  6883  6883 V BluetoothPbapService: Pbap Service onBind
07-27 15:04:40.063  6749  6749 D HeadsetProfile: Bluetooth service connected
07-27 15:04:40.063  6883  6883 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-27 15:04:40.063  6883  6883 V BluetoothPbapService: state: 12
07-27 15:04:40.064  6883  6883 V BluetoothMapService: Handler(): got msg=1
07-27 15:04:40.064  6883  6883 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
07-27 15:04:40.065  6883  6883 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-27 15:04:40.065  6883  6883 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-27 15:04:40.065  6883  6883 V BluetoothPbapReceiver: ***********state = 12
07-27 15:04:40.066  6883  7481 D BluetoothMapMasInstance: MAS initSocket()
07-27 15:04:40.066  6883  7481 D BluetoothMapMasInstance:   masId = 00
07-27 15:04:40.066  6883  7481 D BluetoothMapMasInstance:   msgTypes = 0e
07-27 15:04:40.066  6883  7481 D BluetoothMapMasInstance:   masName = SMS/MMS
07-27 15:04:40.066  6883  7481 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
07-27 15:04:40.067  6883  6883 V BluetoothPbapService: Handler(): got msg=1
07-27 15:04:40.067  6883  6883 V BluetoothPbapService: Pbap Service startRfcommSocketListener
07-27 15:04:40.068  1033  1927 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 15:04:40.069  6883  7483 V BluetoothPbapService: Pbap Service initSocket
07-27 15:04:40.069  2188  2188 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-27 15:04:40.069  1033  1889 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-27 15:04:40.070  2188  2188 D c       : Getting all permits...
,07-27 15:04:40.070  2188  2188 D a       : Opening database...
07-27 15:04:40.071  6883  7481 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 15:04:40.073  6883  7483 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 15:04:40.073  6883  7481 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
07-27 15:04:40.074  6883  7481 V BluetoothMapMasInstance: Succeed to create listening socket 
07-27 15:04:40.074  6883  7481 D BluetoothMapMasInstance: Accepting socket connection...
07-27 15:04:40.074  6883  7363 D BluetoothAdapterProperties: Scan Mode:21
07-27 15:04:40.074  6883  7363 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
07-27 15:04:40.074  6749  6749 D DockEventReceiver: finishStartingService: stopping service
07-27 15:04:40.075  6749  6749 D BluetoothPbap: Proxy object connected
07-27 15:04:40.076  6749  6749 D PbapServerProfile: Bluetooth service connected
07-27 15:04:40.077  2188  2188 D a       : Opening database auth.proximity.permit_store...
07-27 15:04:40.077  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:40.079  6883  7483 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
07-27 15:04:40.079  6883  7483 V BluetoothPbapService: Succeed to create listening socket 
07-27 15:04:40.079  6883  7483 V BluetoothPbapService: Accepting socket connection...
07-27 15:04:40.080  2188  2188 D a       : Closing database...
,07-27 15:04:40.081  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:40.096  6749  6749 D BluetoothPermissionRequest: onReceive
,07-27 15:04:40.098  6749  6749 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
07-27 15:04:40.100  6749  6749 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-27 15:04:40.103  6883  6883 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
07-27 15:04:40.105  6883  6883 I LGBluetoothOppAdapter: [BTUI] startOppService()
07-27 15:04:40.111  6883  6883 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,07-27 15:04:40.129  6883  6883 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-27 15:04:40.129  6883  6883 V BtOppService: onCreate
,07-27 15:04:40.133  6883  6883 V BluetoothOppNotification: send message
07-27 15:04:40.137  6883  6883 V BtOppService: Starting RfcommListener
07-27 15:04:40.146  6883  6883 D BluetoothOppPreference: Dumping Names:  
07-27 15:04:40.146  6883  6883 D BluetoothOppPreference: {}
07-27 15:04:40.146  6883  6883 D BluetoothOppPreference: Dumping Channels:  
,07-27 15:04:40.146  6883  6883 D BluetoothOppPreference: {}
07-27 15:04:40.147  6883  6883 V BtOppService: onStartCommand
07-27 15:04:40.147  7103  7135 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
07-27 15:04:40.152  6883  6883 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-27 15:04:40.153  6883  6883 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
07-27 15:04:40.155  6883  7491 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
07-27 15:04:40.156  6883  6883 V BluetoothOppNotification: new notify threadi!
07-27 15:04:40.157  6883  6883 V BluetoothOppNotification: send delay message
07-27 15:04:40.157  6883  6883 V BtOppService: start RfcommListener
07-27 15:04:40.166  6883  6883 V BtOppService: RfcommListener started
07-27 15:04:40.166  6883  7493 V BtOppRfcommListener: Starting RFCOMM listener....
07-27 15:04:40.166  1033  1576 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 15:04:40.167  6883  7486 V BtOppService: Deleted complete outbound shares, number =  0
07-27 15:04:40.167  6883  7493 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 15:04:40.169  6883  7493 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
,07-27 15:04:40.171  6883  7493 V BtOppRfcommListener: Started RFCOMM listener....
07-27 15:04:40.171  6883  7486 V BtOppService: Deleted complete inbound failed shares, number = 0
07-27 15:04:40.171  6883  7493 I BtOppRfcommListener: Accept thread started.
07-27 15:04:40.171  6883  7493 V BtOppRfcommListener: Accepting connection...
07-27 15:04:40.172  6883  7491 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-27 15:04:40.172  6883  7486 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
07-27 15:04:40.172  6883  7492 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
07-27 15:04:40.174  6883  7491 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2b8c6045 on behalf of 
07-27 15:04:40.175  6883  7486 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@a78339a on behalf of 
07-27 15:04:40.177  6883  7491 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
07-27 15:04:40.179  6883  7492 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@180314cb on behalf of 
07-27 15:04:40.180  6883  7492 V BluetoothOppNotification: mUpdateCompleteNotification = true
07-27 15:04:40.183  6883  7492 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,07-27 15:04:40.186  6883  7492 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@9a7e4a8 on behalf of 
07-27 15:04:40.188  6883  6883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2daef400
07-27 15:04:40.188  6883  6883 V BluetoothFtpService: Ftp Service onCreate
07-27 15:04:40.188  6883  6883 I BluetoothFtpService: Ftp Service onCreate
07-27 15:04:40.188  6883  6883 V BluetoothFtpService: Ftp Service onStartCommand
07-27 15:04:40.188  6883  6883 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-27 15:04:40.189  6883  7492 V BluetoothOppNotification: outbound: succ-0  fail-0
07-27 15:04:40.189  6883  6883 V BluetoothFtpService: Starting Listening on sockets
07-27 15:04:40.189  6883  6883 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-27 15:04:40.189  6883  6883 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-27 15:04:40.189  6883  6883 V BluetoothSapReceiver: SapReceiver onReceive 
07-27 15:04:40.189  6883  6883 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-27 15:04:40.189  6883  6883 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
07-27 15:04:40.189  6883  6883 V BluetoothSapReceiver: Calling SAP service start service with action = null
07-27 15:04:40.191  6883  7492 V BluetoothOppNotification: outbound notification was removed.
07-27 15:04:40.191  6883  7492 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
07-27 15:04:40.192  6883  6883 V BtOppService: ContentObserver received notification
07-27 15:04:40.192  6883  6883 V BtOppService: ContentObserver received notification
07-27 15:04:40.192  6883  6883 V BluetoothFtpService: Handler(): got msg=1
07-27 15:04:40.193  6883  6883 V BluetoothFtpService: Ftp Service startRfcommSocketListener
07-27 15:04:40.193  6883  6883 V BluetoothFtpService: Ftp Service initSocket
07-27 15:04:40.194  6883  7494 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
07-27 15:04:40.195  6883  7494 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,07-27 15:04:40.198  6883  7492 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@b95ef66 on behalf of 
07-27 15:04:40.198  6883  7494 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2cac32a7 on behalf of 
07-27 15:04:40.199  1033  1889 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 15:04:40.199  6883  7492 V BluetoothOppNotification: inbound: succ-0  fail-0
07-27 15:04:40.200  6883  7494 V BluetoothOppNotification: update too frequent, put in queue
07-27 15:04:40.200  6883  6883 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 15:04:40.201  6883  6883 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=78
07-27 15:04:40.202  6883  6883 V BluetoothFtpService: Succeed to create listening socket on channel 20
07-27 15:04:40.203  6883  7492 V BluetoothOppNotification: inbound notification was removed.
07-27 15:04:40.203  6883  7492 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
07-27 15:04:40.204  6883  7495 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
07-27 15:04:40.204  6883  7494 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
07-27 15:04:40.204  6883  7492 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@10eaa354 on behalf of 
07-27 15:04:40.229  6883  6883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2daef400
07-27 15:04:40.229  6883  6883 V BluetoothSapService: Sap Service onCreate
,07-27 15:04:40.231  6883  6883 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-27 15:04:40.231  6883  6883 V BluetoothSapService: state: 12
07-27 15:04:40.232  6883  6883 V BluetoothSapService: Starting SAP server process
07-27 15:04:40.234  6883  6883 V BluetoothSapService: SAP Service startRfcommListenerThread
07-27 15:04:40.236  6883  7497 V BluetoothSapService: Sap Service initRfcommSocket
07-27 15:04:40.232  7496  7496 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 15:04:40.236  1033  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 15:04:40.232  7496  7496 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 15:04:40.237  6883  7497 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 15:04:40.238  6883  7497 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
07-27 15:04:40.238  6883  7497 V BluetoothSapService: Succeed to create listening socket 
07-27 15:04:40.238  6883  7497 V BluetoothSapService: Accepting socket connection...
07-27 15:04:40.260  7496  7496 V BT_SAP  : Event pipe created
07-27 15:04:40.260  7496  7496 V BT_SAP  : create_server_socket qcom.sap.server
07-27 15:04:40.260  7496  7496 V BT_SAP  : created socket fd 6
,07-27 15:04:40.935  1033  1536 D LGWifiP2pService: P2pDisabledState{ when=-6ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,07-27 15:04:40.942  1033  1536 D LGWifiP2pService: DefaultState{ when=-12ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:40.982  1033  1537 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
07-27 15:04:40.984  1033  1537 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,07-27 15:04:41.159  6883  6883 V BluetoothOppNotification: new notify threadi!
07-27 15:04:41.160  6883  6883 V BluetoothOppNotification: send delay message
,07-27 15:04:41.170  6883  7507 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
07-27 15:04:41.173  6883  7507 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@8f8a0c0 on behalf of 
07-27 15:04:41.190  6883  7507 V BluetoothOppNotification: mUpdateCompleteNotification = true
,07-27 15:04:41.199  1033  1052 I ActivityManager: Killing 7285:com.lge.bnr/1000 (adj 15): empty #17
07-27 15:04:41.209  6883  7507 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,07-27 15:04:41.221  6883  7507 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@275721f9 on behalf of 
07-27 15:04:41.221  6883  7507 V BluetoothOppNotification: outbound: succ-0  fail-0
,07-27 15:04:41.226  6883  7507 V BluetoothOppNotification: outbound notification was removed.
07-27 15:04:41.226  6883  7507 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
07-27 15:04:41.227  6883  7507 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@c09853e on behalf of 
07-27 15:04:41.228  6883  7507 V BluetoothOppNotification: inbound: succ-0  fail-0
07-27 15:04:41.229  6883  7507 V BluetoothOppNotification: inbound notification was removed.
07-27 15:04:41.230  6883  7507 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
07-27 15:04:41.231  6883  7507 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@129acf9f on behalf of 
07-27 15:04:41.236  1033  1889 W libprocessgroup: failed to open /acct/uid_1000/pid_7285/cgroup.procs: No such file or directory
,07-27 15:04:41.852  1033  2015 I ActivityManager: Killing 6595:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,07-27 15:04:41.877  6799  6799 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
07-27 15:04:41.877  6799  6799 W System.err: android.os.DeadObjectException
07-27 15:04:41.877  6799  6799 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
07-27 15:04:41.877  6799  6799 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
07-27 15:04:41.878  6799  6799 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
07-27 15:04:41.878  6799  6799 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
07-27 15:04:41.878  6799  6799 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
07-27 15:04:41.878  6799  6799 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
07-27 15:04:41.878  6799  6799 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-27 15:04:41.878  6799  6799 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-27 15:04:41.878  6799  6799 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-27 15:04:41.878  6799  6799 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-27 15:04:41.878  6799  6799 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 15:04:41.878  6799  6799 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 15:04:41.878  6799  6799 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-27 15:04:41.878  6799  6799 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-27 15:04:41.878  6799  6799 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
07-27 15:04:41.878  6799  6799 W System.err: android.os.DeadObjectException
07-27 15:04:41.879  6799  6799 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
07-27 15:04:41.879  6799  6799 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
07-27 15:04:41.879  6799  6799 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
07-27 15:04:41.879  6799  6799 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
07-27 15:04:41.879  6799  6799 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
07-27 15:04:41.879  6799  6799 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
07-27 15:04:41.879  6799  6799 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-27 15:04:41.879  6799  6799 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-27 15:04:41.879  6799  6799 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-27 15:04:41.879  6799  6799 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-27 15:04:41.879  6799  6799 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 15:04:41.879  6799  6799 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 15:04:41.879  6799  6799 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-27 15:04:41.879  6799  6799 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-27 15:04:41.879  6799  6799 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
07-27 15:04:41.880  6799  6799 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,07-27 15:04:41.913  1033  1630 W libprocessgroup: failed to open /acct/uid_1000/pid_6595/cgroup.procs: No such file or directory
,07-27 15:04:41.914  1033  1630 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,07-27 15:04:41.936  1033  1889 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 15:04:41.936  1033  1889 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@130d6d0f mBinding = false
,07-27 15:04:41.943  6799  6799 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
07-27 15:04:41.944  6799  6799 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
07-27 15:04:42.000  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-27 15:04:42.000  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-27 15:04:42.000  1033  1033 D Ulp_jni : JNI:system_update. Event-4
,07-27 15:04:42.004  1033  1052 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7508 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
07-27 15:04:42.004  1033  1098 D BluetoothManagerService: Message: 2
07-27 15:04:42.005  1033  1098 D BluetoothManagerService: Sending off request.
07-27 15:04:42.006  6883  7463 D LGBluetoothServiceAdapter: [BTUI] Precleanup
07-27 15:04:42.006  6883  7359 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
07-27 15:04:42.006  6883  7359 D BluetoothAdapterProperties: Setting state to 13
07-27 15:04:42.006  6883  7359 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-27 15:04:42.007  6883  7359 D BluetoothAdapterProperties: onBluetoothDisable()
07-27 15:04:42.007  6883  7359 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
07-27 15:04:42.009  6883  7363 D BluetoothAdapterProperties: Scan Mode:20
07-27 15:04:42.010  6883  7359 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
07-27 15:04:42.011  6883  7359 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
07-27 15:04:42.012  6883  7481 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
07-27 15:04:42.012  6883  7481 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-27 15:04:42.012  6883  7481 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
07-27 15:04:42.012  6883  7481 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
07-27 15:04:42.012  6883  7481 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
07-27 15:04:42.012  6883  7481 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
07-27 15:04:42.012  6883  7481 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
07-27 15:04:42.012  6883  7481 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
07-27 15:04:42.014  6883  7483 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,07-27 15:04:42.016  6883  7493 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-27 15:04:42.017  6883  7497 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-27 15:04:42.018  6883  7428 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
07-27 15:04:42.018  6883  7428 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
07-27 15:04:42.019  6883  7495 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-27 15:04:42.023  6883  7428 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-27 15:04:42.023  6883  7428 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-27 15:04:42.023  6883  7428 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-27 15:04:42.023  6883  7428 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-27 15:04:42.023  6883  7428 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-27 15:04:42.023  6883  7428 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-27 15:04:42.023  6883  7428 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-27 15:04:42.023  6883  7428 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-27 15:04:42.023  6883  7428 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-27 15:04:42.026  6883  7428 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
07-27 15:04:42.026  6883  7428 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
07-27 15:04:42.026  6883  7428 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,07-27 15:04:42.035  6632  6632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 15:04:42.035  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 15:04:42.035  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:42.035  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:42.035  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 15:04:42.035  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 15:04:42.035  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 15:04:42.035  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 15:04:42.035  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 15:04:42.036  6632  6632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 15:04:42.036  6632  6632 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-27 15:04:42.041  6632  6632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 15:04:42.041  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 15:04:42.041  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:42.041  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:42.041  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 15:04:42.041  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 15:04:42.041  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 15:04:42.041  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 15:04:42.041  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 15:04:42.045  6632  6632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 15:04:42.045  6632  6632 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-27 15:04:42.046  1033  1098 D BluetoothManagerService: Message: 60
07-27 15:04:42.046  1033  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
07-27 15:04:42.046  1033  1098 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
07-27 15:04:42.049  1944  1944 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-27 15:04:42.050  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-27 15:04:42.054  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 15:04:42.058  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:42.060  6883  6883 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-27 15:04:42.060  6883  6883 D BluetoothMapService: STATE_TURNING_OFF
07-27 15:04:42.060  6883  6883 V BluetoothMapService: Handler(): got msg=4
07-27 15:04:42.060  6883  6883 D BluetoothMapService: MAP Service closeService in
07-27 15:04:42.061  6883  6883 D BluetoothMapMasInstance: MAP Service shutdown
07-27 15:04:42.061  6883  6883 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-27 15:04:42.061  6883  6883 V BluetoothMapService: MAP Service closeService out
07-27 15:04:42.062  6883  6883 V BtOppService: Receiver DISABLED_ACTION 
07-27 15:04:42.062  6883  6883 I BtOppRfcommListener: stopping Accept Thread
07-27 15:04:42.062  6883  6883 V BtOppRfcommListener: close mBtServerSocket
07-27 15:04:42.063  6883  7493 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-27 15:04:42.063  6883  6883 V BtOppRfcommListener: waiting for thread to terminate
07-27 15:04:42.063  6883  6883 V BtOppRfcommListener: done waiting for thread to terminate
07-27 15:04:42.066  6749  6749 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
,07-27 15:04:42.077  6749  6749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-27 15:04:42.078  6883  6883 V BtOppService: onDestroy
,07-27 15:04:42.082  6883  6883 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
07-27 15:04:42.087  6883  6883 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-27 15:04:42.087  6883  6883 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-27 15:04:42.087  6883  6883 V BluetoothPbapReceiver: ***********state = 13
07-27 15:04:42.088  6883  6883 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
07-27 15:04:42.089  6883  6883 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-27 15:04:42.090  6883  6883 V BluetoothPbapService: state: 13
07-27 15:04:42.090  6883  6883 V BluetoothPbapService: Pbap Service closeService in
07-27 15:04:42.094  2188  2188 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-27 15:04:42.100  6883  6883 V BluetoothPbapService: successfully stopped pbap service
07-27 15:04:42.100  6883  6883 V BluetoothPbapService: Pbap Service closeService out
07-27 15:04:42.103  6883  6883 V BluetoothPbapService: Pbap Service onDestroy
07-27 15:04:42.103  6883  6883 V BluetoothPbapService: Pbap Service closeService in
07-27 15:04:42.103  6883  6883 V BluetoothPbapService: Pbap Service closeService out
07-27 15:04:42.103  6883  6883 D LGBluetoothPbapAdapter: [BTUI] cleanup
,07-27 15:04:42.115  6799  6799 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
07-27 15:04:42.131  6749  6749 D DockEventReceiver: finishStartingService: stopping service
07-27 15:04:42.131  6749  6749 D BluetoothPbap: Proxy object disconnected
07-27 15:04:42.131  6749  6749 D PbapServerProfile: Bluetooth service disconnected
,07-27 15:04:42.136  6749  6749 D LGBluetoothAuthorization: [BTUI] cancel All Notification
07-27 15:04:42.141  6749  6749 D BluetoothPermissionRequest: onReceive
07-27 15:04:42.141  6749  6749 D LGBluetoothAuthorization: [BTUI] cancel All Notification
07-27 15:04:42.148  6749  6749 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,07-27 15:04:42.152  6883  6883 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
07-27 15:04:42.152  6883  6883 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
07-27 15:04:42.152  6883  6883 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
07-27 15:04:42.156  6883  6883 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-27 15:04:42.156  6883  6883 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
07-27 15:04:42.157  6883  6883 V BluetoothFtpService: Ftp Service onStartCommand
07-27 15:04:42.157  6883  6883 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-27 15:04:42.157  6883  6883 V BluetoothFtpService: Ftp Service closeService
07-27 15:04:42.157  6883  6883 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
07-27 15:04:42.158  6883  6883 V BluetoothFtpService: successfully stopped ftp service
07-27 15:04:42.159  6883  6883 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-27 15:04:42.159  6883  6883 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-27 15:04:42.159  6883  6883 V BluetoothSapReceiver: SapReceiver onReceive 
07-27 15:04:42.159  6883  6883 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-27 15:04:42.159  6883  6883 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
07-27 15:04:42.159  6883  6883 V BluetoothSapReceiver: Calling SAP service start service with action = null
07-27 15:04:42.161  6883  6883 V BluetoothFtpService: Ftp Service onDestroy
07-27 15:04:42.161  6883  6883 V BluetoothFtpService: Ftp Service closeService
,07-27 15:04:42.164  6883  6883 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-27 15:04:42.164  6883  6883 V BluetoothSapService: state: 13
07-27 15:04:42.164  6883  6883 V BluetoothSapService: Stopping SAP server process
07-27 15:04:42.167  6883  6883 V BluetoothSapService: Sap Service closeSapService in
07-27 15:04:42.167  6883  6883 V BluetoothSapService: Close listen Socket : 
07-27 15:04:42.168  6883  6883 V BluetoothSapService: Close rfcomm Socket : 
07-27 15:04:42.168  6883  6883 V BluetoothSapService: Close sapd  Socket : 
07-27 15:04:42.169  6883  6883 V BluetoothSapService: Sap Service closeSapService out
07-27 15:04:42.169  6883  6883 V BluetoothSapService: Sap Service onDestroy
07-27 15:04:42.169  6883  6883 V BluetoothSapService: Sap Service closeSapService in
07-27 15:04:42.169  6883  6883 V BluetoothSapService: Close listen Socket : 
07-27 15:04:42.169  6883  6883 V BluetoothSapService: Close rfcomm Socket : 
,07-27 15:04:42.169  6883  6883 V BluetoothSapService: Close sapd  Socket : 
07-27 15:04:42.172  6883  6883 V BluetoothSapService: Sap Service closeSapService out
07-27 15:04:42.208  7508  7508 D UEI.SmartControl: Quickset Services start...
,07-27 15:04:42.211  7508  7508 I UEI.SmartControl: Manufacture = LGE
07-27 15:04:42.211  7508  7508 D UEI.SmartControl: Id = LGNevo
07-27 15:04:42.212  7508  7508 D UEI.SmartControl: File observer start...
07-27 15:04:42.213  7508  7508 E UEI.SmartControl: IR Port is disabled: false
07-27 15:04:42.213  7508  7508 D UEI.SmartControl: Starting file observer...
07-27 15:04:42.213  7508  7508 D UEI.SmartControl: Extracting JNI libs...
07-27 15:04:42.213  7508  7508 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
07-27 15:04:42.284  7508  7508 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
07-27 15:04:42.284  7508  7508 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
07-27 15:04:42.285  7508  7508 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,07-27 15:04:42.309  7508  7508 I UEI.SmartControl: --- Selecting new region: 6
07-27 15:04:42.312  7508  7508 I UEI.SmartControl: Model = LG-D855
,07-27 15:04:42.315  7508  7508 D UEI.SmartControl: QS Service created
07-27 15:04:42.325  7508  7508 I UEI.SmartControl: Service initServices...
,07-27 15:04:42.329  7508  7508 D UEI.SmartControl: QS start get config
07-27 15:04:42.361  7508  7508 D UEI.SmartControl: Loading JNI Libs...
,07-27 15:04:42.596  7508  7508 I UEI.SmartControl: Supports setup maps: true
,07-27 15:04:42.599  7508  7508 D UEI.SmartControl: QS start statue = true Error code = 0
07-27 15:04:42.599  7508  7508 I UEI.SmartControl: QS version = v2.7.10.1_RC1
07-27 15:04:42.600  7508  7508 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
07-27 15:04:42.600  7508  7508 I UEI.SmartControl: ### init IR Blaster...
07-27 15:04:42.609  7508  7508 D serial_port: Configuring serial port
07-27 15:04:42.613  7508  7508 E UEI.SmartControl: UEIBLaster setting for 616
07-27 15:04:42.613  7508  7508 I UEI.SmartControl: Setting serial record hearder size = 2
07-27 15:04:42.614  7508  7508 I UEI.SmartControl: configuring settings for MAXQ616
07-27 15:04:42.614  7508  7508 I UEI.SmartControl: Get version...
,07-27 15:04:42.631  7508  7552 D UEI.SmartControl: serial port data available: 21
,07-27 15:04:42.662  7508  7508 D UEI.SmartControl: MAXQ616 A2-X4 software.
,07-27 15:04:42.662  7508  7508 I UEI.SmartControl: IR Blaster version: 256702256704300002
,07-27 15:04:42.662  7508  7508 I UEI.SmartControl: QS saving settings...
,07-27 15:04:42.669  7508  7508 D UEI.SmartControl: IR Blaster version: 25672567
07-27 15:04:42.686  7508  7552 D UEI.SmartControl: serial port data available: 4
,07-27 15:04:42.738  7508  7508 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,07-27 15:04:42.742  7508  7558 I UEI.SmartControl: Device manager: loading config....
07-27 15:04:42.743  7508  7558 D UEI.SmartControl: ----------- loading internal config...
07-27 15:04:42.845  7508  7558 E UEI.SmartControl: Loading SETTINGS...
,07-27 15:04:42.914  1033  1907 I art     : Explicit concurrent mark sweep GC freed 94159(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 2.718ms total 158.005ms
,07-27 15:04:42.919  7508  7508 E UEI.SmartControl: Services init done
07-27 15:04:42.920  7508  7508 D UEI.SmartControl: QS Service init finished
07-27 15:04:42.920  7508  7508 D UEI.SmartControl: QS Service version name: 2.1.91
07-27 15:04:42.921  7508  7508 D UEI.SmartControl: QS Service version code: 201091
07-27 15:04:42.921  7508  7508 D UEI.SmartControl: Service requested: Control
07-27 15:04:42.924  6883  7363 D bt_hci_bdroid: cleanup
07-27 15:04:42.924  1033  1576 I ActivityManager: Killing 6799:com.lge.qremote/u0a112 (adj 15): empty #17
07-27 15:04:42.924  6883  7430 I bt_lpm  : LPM is already off!!!
07-27 15:04:42.924  6883  7454 I bt_userial_mct: exiting userial_read_thread
07-27 15:04:42.924  6883  7454 D bt_userial_mct: Leaving userial_evt_read_thread()
07-27 15:04:42.924  6883  7428 W bt-btif : ag scb idx 1 not allocated
07-27 15:04:42.924  6883  7428 E bt-btif : BTA AG is already disabled, ignoring ...
07-27 15:04:42.924  6883  7428 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-27 15:04:42.924  6883  7428 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-27 15:04:42.924  6883  7428 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-27 15:04:42.924  6883  7428 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-27 15:04:42.924  6883  7428 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-27 15:04:42.924  6883  7428 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-27 15:04:42.924  6883  7428 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-27 15:04:42.924  6883  7428 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-27 15:04:42.924  6883  7428 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-27 15:04:42.924  6883  7428 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-27 15:04:42.924  6883  7428 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-27 15:04:42.924  6883  7428 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-27 15:04:42.925  6883  7428 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-27 15:04:42.925  6883  7428 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-27 15:04:42.925  6883  7428 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-27 15:04:42.925  6883  7428 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-27 15:04:42.925  6883  7428 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-27 15:04:42.925  6883  7428 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-27 15:04:42.925  6883  7428 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
07-27 15:04:42.925  6883  7363 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
07-27 15:04:42.925  6883  7430 I bt_vendor: hw_epilog_process
07-27 15:04:42.926  6883  7363 D bt_hci_bdroid: cleanup Finalizing cleanup
07-27 15:04:42.926  6883  7363 D bt_userial_mct: userial_close
,07-27 15:04:42.926  6883  7363 E bt_userial_mct: pthread_join() FAILED result:3
07-27 15:04:42.926  6883  7363 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,07-27 15:04:42.938  7508  7558 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,07-27 15:04:42.947  7508  7557 I UEI.SmartControl: Notify AllClients services are ready: 0
,07-27 15:04:42.947  7508  7557 D UEI.SmartControl: -----service ready thread exits
07-27 15:04:43.027  1033  1630 W libprocessgroup: failed to open /acct/uid_10112/pid_6799/cgroup.procs: No such file or directory
,07-27 15:04:43.038  7508  7508 D UEI.SmartControl: Internal service binding...
,07-27 15:04:43.039  6883  7363 D bt_hci_bdroid: set_power 0
07-27 15:04:43.039  6883  7363 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
07-27 15:04:43.039  6883  7363 I bt_vendor: bluetooth satus is on
07-27 15:04:43.039  6883  7363 I bt_vendor: bt-vendor : resetting BT status
07-27 15:04:43.039  6883  7363 I bt_vendor: Starting hciattach daemon
07-27 15:04:43.039  6883  7363 I bt_vendor: try to set false
07-27 15:04:43.042  6883  7363 I bt_vendor: Starting hciattach daemon
07-27 15:04:43.042  6883  7363 I bt_vendor: try to set false
07-27 15:04:43.043  6883  7363 I bt_vendor: cleanup
07-27 15:04:43.046  6883  7428 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
07-27 15:04:43.046  6883  7363 I GKI_LINUX: GKI_exit_task 0 done
07-27 15:04:43.047  6883  7363 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,07-27 15:04:43.050  6883  7359 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,07-27 15:04:43.055  6883  6883 D HeadsetService: Received stop request...Stopping profile...
07-27 15:04:43.057  6883  6883 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
07-27 15:04:43.057  6883  6883 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-27 15:04:43.057  6883  6883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2daef400
07-27 15:04:43.058  6883  7398 D HeadsetStateMachine: Exit Disconnected: -1
07-27 15:04:43.060  1033  1033 D BluetoothHeadset: Proxy object disconnected
07-27 15:04:43.060  1033  1033 D AudioService: onServiceDisconnected: Bluetooth profile: 1
07-27 15:04:43.060  1853  1853 D BluetoothHeadset: Proxy object disconnected
07-27 15:04:43.060  1853  1853 D BluetoothHeadset: Proxy object disconnected
,07-27 15:04:43.064  1853  1853 D BluetoothHeadset: Proxy object disconnected
07-27 15:04:43.065  6883  6883 D A2dpService: Received stop request...Stopping profile...
07-27 15:04:43.066  6749  6749 D BluetoothHeadset: Proxy object disconnected
07-27 15:04:43.066  6749  6749 D HeadsetProfile: Bluetooth service disconnected
07-27 15:04:43.066  6883  7413 D A2dpStateMachine: Exit Disconnected: -1
07-27 15:04:43.066  6883  7359 D BluetoothAdapterState: Stopping profile services that were post enabled
07-27 15:04:43.067  6883  6883 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
07-27 15:04:43.069  6883  6883 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
07-27 15:04:43.069  6883  6883 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
07-27 15:04:43.069  6883  6883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2daef400
07-27 15:04:43.069  1033  1033 D BluetoothA2dp: Proxy object disconnected
07-27 15:04:43.070  1033  1033 D AudioService: onServiceDisconnected: Bluetooth profile: 2
07-27 15:04:43.071  6749  6749 D BluetoothA2dp: Proxy object disconnected
07-27 15:04:43.071  6749  6749 D A2dpProfile: Bluetooth service disconnected
07-27 15:04:43.071  6883  6883 D HidService: Received stop request...Stopping profile...
07-27 15:04:43.072  6883  6883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2daef400
07-27 15:04:43.073  6749  6749 D BluetoothInputDevice: Proxy object disconnected
07-27 15:04:43.073  6749  6749 D HidProfile: Bluetooth service disconnected
07-27 15:04:43.074  6883  6883 D HealthService: Received stop request...Stopping profile...
,07-27 15:04:43.074  6883  6883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2daef400
07-27 15:04:43.078  6883  6883 D HeadsetStateMachine: Unbinding service...
07-27 15:04:43.078  6883  6883 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-27 15:04:43.078  6883  6883 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-27 15:04:43.078  6883  6883 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-27 15:04:43.078  6883  6883 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-27 15:04:43.078  6883  6883 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-27 15:04:43.078  6883  6883 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-27 15:04:43.078  6883  6883 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
07-27 15:04:43.079  6883  6883 D PanService: Received stop request...Stopping profile...
07-27 15:04:43.080  6883  6883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2daef400
07-27 15:04:43.081  6883  6883 D BtGatt.DebugUtils: handleDebugAction() action=null
07-27 15:04:43.082  6883  6883 D BtGatt.GattService: Received stop request...Stopping profile...
07-27 15:04:43.082  6749  6749 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-27 15:04:43.082  6749  6749 D PanProfile: Bluetooth service disconnected
07-27 15:04:43.082  6883  6883 D BtGatt.GattService: stop()
07-27 15:04:43.082  6883  6883 D BtGatt.AdvertiseManager: advertise clients cleared
07-27 15:04:43.083  6883  6883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2daef400
07-27 15:04:43.084  6883  6883 D BluetoothMapService: Received stop request...Stopping profile...
07-27 15:04:43.084  6883  6883 D BluetoothMapService: stop()
07-27 15:04:43.085  6883  6883 D BluetoothMapEmailAppObserver: deinitObservers()
07-27 15:04:43.085  6883  6883 D BluetoothMapEmailAppObserver: removeReceiver()
07-27 15:04:43.085  6883  6883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2daef400
,07-27 15:04:43.089  6883  6883 I BluetoothA2dpServiceJni: cleanupNative
07-27 15:04:43.089  6883  7414 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
07-27 15:04:43.089  6749  6749 D BluetoothMap: Proxy object disconnected
07-27 15:04:43.089  6749  6749 D MapProfile: Bluetooth service disconnected
07-27 15:04:43.090  6883  6883 I GKI_LINUX: GKI_exit_task 2 done
07-27 15:04:43.090  6883  6883 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
07-27 15:04:43.090  6883  6883 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-27 15:04:43.090  6883  6883 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-27 15:04:43.091  6883  6883 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-27 15:04:43.091  6883  6883 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-27 15:04:43.091  6883  6883 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-27 15:04:43.091  6883  6883 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-27 15:04:43.091  6883  6883 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-27 15:04:43.092  6883  6883 V BluetoothMapService: Handler(): got msg=4
07-27 15:04:43.092  6883  6883 D BluetoothMapService: MAP Service closeService in
07-27 15:04:43.092  6883  6883 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-27 15:04:43.092  6883  6883 V BluetoothMapService: MAP Service closeService out
07-27 15:04:43.093  6883  7359 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
07-27 15:04:43.093  6883  6883 D BluetoothMapService: cleanup()
07-27 15:04:43.093  6883  7359 D BluetoothAdapterProperties: Setting state to 10
07-27 15:04:43.093  6883  6883 D BluetoothMapService: MAP Service closeService in
07-27 15:04:43.093  6883  6883 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-27 15:04:43.093  6883  7359 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
07-27 15:04:43.093  6883  6883 V BluetoothMapService: MAP Service closeService out
07-27 15:04:43.093  1033  1098 D BluetoothManagerService: Message: 60
07-27 15:04:43.093  1033  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
07-27 15:04:43.093  1033  1098 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
07-27 15:04:43.093  1033  1098 D BluetoothHeadset: onBluetoothStateChange: up=false
07-27 15:04:43.094  6883  7359 I BluetoothAdapterState: Entering OffState
07-27 15:04:43.094  6749  6764 D BluetoothPbap: onBluetoothStateChange: up=false
07-27 15:04:43.095  1853  1868 D BluetoothHeadset: onBluetoothStateChange: up=false
07-27 15:04:43.096  1853  1869 D BluetoothHeadset: onBluetoothStateChange: up=false
07-27 15:04:43.097  6749  7479 D BluetoothA2dp: onBluetoothStateChange: up=false
07-27 15:04:43.097  6749  7480 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-27 15:04:43.101  1853  2461 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-27 15:04:43.102  6749  6765 D BluetoothMap: onBluetoothStateChange: up=false
07-27 15:04:43.103  6749  6764 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-27 15:04:43.103  1033  1098 D BluetoothA2dp: onBluetoothStateChange: up=false
07-27 15:04:43.103  6749  7479 D BluetoothPan: onBluetoothStateChange on: false
07-27 15:04:43.105  1033  1098 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
07-27 15:04:43.105  1033  1098 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
07-27 15:04:43.107  1033  1098 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
07-27 15:04:43.107  1033  1098 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
07-27 15:04:43.107  1033  1098 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@130d6d0f mBinding = false
07-27 15:04:43.107  1033  1098 D BluetoothManagerService: Sending unbind request.
07-27 15:04:43.108  1033  1098 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,07-27 15:04:43.113  6749  6749 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
07-27 15:04:43.113  6749  6749 D LGBluetoothEventManager: [BTUI] clear device connection state
07-27 15:04:43.115  1944  1944 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-27 15:04:43.117  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-27 15:04:43.117  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:43.118  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:43.122  1944  2150 D LGBluetoothAPIService: Message: 2
07-27 15:04:43.122  1944  2150 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@1e53e613 mBinding = false
07-27 15:04:43.122  1944  2150 D LGBluetoothAPIService: Sending unbind request.
07-27 15:04:43.125  6883  7363 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
07-27 15:04:43.121  1604  1604 D BluetoothAdapter: 179525898: getState() :  mService = null. Returning STATE_OFF
07-27 15:04:43.125  1604  1604 D BluetoothAdapter: 179525898: getState() :  mService = null. Returning STATE_OFF
,07-27 15:04:43.126  6883  6883 I GKI_LINUX: GKI_exit_task 1 done
07-27 15:04:43.126  6883  6883 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
07-27 15:04:43.127  6883  6883 I BluetoothServiceJni: cleanupNative: return from cleanup
07-27 15:04:43.128  6883  6883 I art     : --- WEIRD: removing null entry 248
07-27 15:04:43.128  6883  6883 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
07-27 15:04:43.128  6883  6883 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
07-27 15:04:43.129  6883  6883 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
07-27 15:04:43.130  6749  6749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-27 15:04:43.132  6883  6883 I art     : System.exit called, status: 0
07-27 15:04:43.133  6883  6883 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
07-27 15:04:43.140  6749  6749 D DockEventReceiver: finishStartingService: stopping service
,07-27 15:04:43.155   315  2148 V AudioFlinger: 6883 died, releasing its sessions
07-27 15:04:43.155   315  2148 V AudioFlinger:  pid 1853 @ 0
07-27 15:04:43.155   315  2148 V AudioFlinger:  pid 3422 @ 1
,07-27 15:04:43.155   315  2148 V AudioFlinger:  pid 3422 @ 2
07-27 15:04:43.156  6749  6749 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,07-27 15:04:43.174  1033  1870 I ActivityManager: Process com.android.bluetooth (pid 6883) has died
07-27 15:04:43.174  1033  1870 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
,07-27 15:04:43.180  2188  2188 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-27 15:04:43.197  6749  6749 D BluetoothPermissionRequest: onReceive
,07-27 15:04:43.202  6749  6749 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
07-27 15:04:43.202  6749  6749 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
07-27 15:04:43.207  6749  6749 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-27 15:04:43.281  1033  2015 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7581 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,07-27 15:04:43.356  7581  7581 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
07-27 15:04:43.357  7581  7581 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-27 15:04:43.357  7581  7581 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
07-27 15:04:43.358  7581  7581 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,07-27 15:04:43.379  7581  7581 D BluetoothAdapterApp: Loading JNI Library
,07-27 15:04:43.417  7581  7581 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2dec0fe8 Instance Count = 1
,07-27 15:04:43.431  7581  7581 D BluetoothAdapterApp: onCreate
07-27 15:04:43.468  7581  7581 D ProfileConfigQcom: [BTUI] HeadsetService is supported
07-27 15:04:43.468  7581  7581 D ProfileConfigQcom: Adding HeadsetService
,07-27 15:04:43.468  7581  7581 D ProfileConfigQcom: [BTUI] A2dpService is supported
07-27 15:04:43.468  7581  7581 D ProfileConfigQcom: Adding A2dpService
07-27 15:04:43.469  7581  7581 D ProfileConfigQcom: [BTUI] HidService is supported
07-27 15:04:43.469  7581  7581 D ProfileConfigQcom: Adding HidService
07-27 15:04:43.469  7581  7581 D ProfileConfigQcom: [BTUI] HealthService is supported
07-27 15:04:43.469  7581  7581 D ProfileConfigQcom: Adding HealthService
07-27 15:04:43.470  7581  7581 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
07-27 15:04:43.471  7581  7581 D ProfileConfigQcom: [BTUI] PanService is supported
07-27 15:04:43.471  7581  7581 D ProfileConfigQcom: Adding PanService
07-27 15:04:43.471  7581  7581 D ProfileConfigQcom: [BTUI] GattService is supported
07-27 15:04:43.471  7581  7581 D ProfileConfigQcom: Adding GattService
07-27 15:04:43.472  7581  7581 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
07-27 15:04:43.472  7581  7581 D ProfileConfigQcom: Adding BluetoothMapService
07-27 15:04:43.472  7581  7581 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
07-27 15:04:43.474  7581  7581 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
07-27 15:04:43.480  6749  6749 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
07-27 15:04:43.482  7581  7581 V LGMDMManagerInternal: Create singleton instance
07-27 15:04:43.573  7581  7581 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,07-27 15:04:43.585  7581  7581 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-27 15:04:43.587  7581  7581 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-27 15:04:43.587  7581  7581 V BluetoothSapReceiver: SapReceiver onReceive 
07-27 15:04:43.591  7581  7581 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-27 15:04:43.592  7581  7581 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
07-27 15:04:43.602  6816  6816 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,07-27 15:04:43.606  1033  1576 I ActivityManager: Killing 6769:com.lge.sync/1000 (adj 15): empty #17
07-27 15:04:43.621  1033  1544 D WifiService: Client connection lost with reason: 4
,07-27 15:04:43.636  1033  1052 W libprocessgroup: failed to open /acct/uid_1000/pid_6769/cgroup.procs: No such file or directory
,07-27 15:04:45.065  6632  6695 D io.jxcore.node.ConnectivityMonitor: stop
,07-27 15:04:45.065  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 15:04:45.173  1604  1604 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,07-27 15:04:45.204  1033  1391 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-27 15:04:45.273  1033  1093 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7608 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,07-27 15:04:45.280  1604  1604 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
07-27 15:04:45.280  1604  1604 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
07-27 15:04:45.293  1033  1033 D administrator: Handling package changes for user 0
,07-27 15:04:45.310  2035  2035 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,07-27 15:04:45.363  7608  7608 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,07-27 15:04:45.366  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-27 15:04:45.428  7608  7608 D LgDataFeature: LgDataFeature() Constructor: none
07-27 15:04:45.428  7608  7608 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-27 15:04:45.444  1033  1033 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
07-27 15:04:45.444  1033  1033 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,07-27 15:04:45.481  1033  1092 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-27 15:04:45.488  1033  1092 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
07-27 15:04:45.495  2035  2035 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
07-27 15:04:45.497  2501  2501 V GmsNetworkLocationProvi: DISABLE
,07-27 15:04:45.510  7608  7654 I Babel   : MmsConfig: mnc/mcc: 0/0
07-27 15:04:45.510  7608  7654 I Babel   : MmsConfig.loadMmsSettings
07-27 15:04:45.512  7608  7654 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
07-27 15:04:45.512  7608  7654 I Babel   : MmsConfig.loadFromDatabase
07-27 15:04:45.517  1033  1092 D LocationProviderProxy: applying state to connected service
07-27 15:04:45.518  2501  2501 E GCoreFlp: Bound FusedProviderService with LocationManager
,07-27 15:04:45.530  7608  7654 E Babel   : canonicalizeMccMnc: invalid mccmnc 
07-27 15:04:45.531  7608  7654 I Babel   : MmsConfig.loadFromResources
07-27 15:04:45.536  7608  7654 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
07-27 15:04:45.536  7608  7654 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,07-27 15:04:45.552  7608  7608 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:45.557  7608  7650 W AudioCapabilities: Unsupported mime audio/evrc
07-27 15:04:45.558  7608  7650 W AudioCapabilities: Unsupported mime audio/qcelp
,07-27 15:04:45.559  7608  7650 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-27 15:04:45.566  7608  7650 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
07-27 15:04:45.567  7608  7650 W AudioCapabilities: Unsupported mime audio/qcelp
07-27 15:04:45.568  7608  7650 W AudioCapabilities: Unsupported mime audio/evrc
07-27 15:04:45.576  7608  7650 W VideoCapabilities: Unsupported mime video/x-ms-wmv
07-27 15:04:45.578  7608  7650 W VideoCapabilities: Unsupported mime video/divx
,07-27 15:04:45.580  1818  7655 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
07-27 15:04:45.580  7608  7650 W VideoCapabilities: Unsupported mime video/divx311
07-27 15:04:45.580  1818  7655 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
07-27 15:04:45.582  6943  6943 I AppUp4:CustModeStarterReceiver: onReceive
07-27 15:04:45.584  7608  7650 W VideoCapabilities: Unsupported mime video/divx4
07-27 15:04:45.586  6943  6943 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@9826d32
07-27 15:04:45.586  6943  6943 D AppUp4:CustFacade: isCustomizationCompleted : false
07-27 15:04:45.586  6943  6943 D AppUp4:CustFacade: isPhone : true
07-27 15:04:45.586  6943  6943 D AppUp4:CustModeStarterReceiver: begin check event
07-27 15:04:45.586  6943  6943 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
07-27 15:04:45.592  1818  4746 I Icing   : updateResources: need to parse e{com.google.android.gms}
,07-27 15:04:45.595  7608  7650 W VideoCapabilities: Unsupported mime video/mp4v-esdp
07-27 15:04:45.616  1033  1980 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7658 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,07-27 15:04:45.619  7608  7650 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
07-27 15:04:45.622  7608  7650 W AudioCapabilities: Unsupported mime audio/eac3
07-27 15:04:45.622  7608  7650 W AudioCapabilities: Unsupported mime audio/ac3
07-27 15:04:45.623  7608  7650 W AudioCapabilities: Unsupported mime audio/g726
07-27 15:04:45.624  7608  7650 W AudioCapabilities: Unsupported mime audio/wma-voice
07-27 15:04:45.625  7608  7650 W AudioCapabilities: Unsupported mime audio/x-ms-wma
07-27 15:04:45.626  7608  7650 W AudioCapabilities: Unsupported mime audio/adpcm
07-27 15:04:45.629  7608  7650 W VideoCapabilities: Unsupported mime video/theora
,07-27 15:04:45.631  7608  7650 W VideoCapabilities: Unsupported mime video/mjpg
,07-27 15:04:45.658  1033  1052 I ActivityManager: Killing 6966:com.lge.email/u0a23 (adj 15): empty #17
07-27 15:04:45.661  7658  7658 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-27 15:04:45.662  7658  7658 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-27 15:04:45.662  7658  7658 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,07-27 15:04:45.663  7658  7658 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
07-27 15:04:45.664  7658  7658 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-27 15:04:45.727  1033  1888 W libprocessgroup: failed to open /acct/uid_10023/pid_6966/cgroup.procs: No such file or directory
,07-27 15:04:45.786  7658  7658 I SystemConfig: BUILD Country: EU
07-27 15:04:45.786  7658  7658 I SystemConfig: BUILD Operator: OPEN
,07-27 15:04:45.840  1033  1870 I ActivityManager: Killing 6836:com.lge.formmanager/u0a26 (adj 15): empty #17
,07-27 15:04:45.969  1033  1576 W libprocessgroup: failed to open /acct/uid_10026/pid_6836/cgroup.procs: No such file or directory
,07-27 15:04:45.980  7658  7677 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
07-27 15:04:45.981  7658  7677 I SystemConfig: existFile = false
07-27 15:04:45.981  7658  7677 I SystemConfig: canReadFile = false
07-27 15:04:45.984  7658  7677 I SystemConfig: systemFeature RCS result false
07-27 15:04:45.984  7658  7677 D SystemConfig: refreshRcsSupport() :false
07-27 15:04:46.026  1033  1870 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7682 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,07-27 15:04:46.096  7682  7682 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-27 15:04:46.096  7682  7682 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-27 15:04:46.096  7682  7682 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,07-27 15:04:46.097  7682  7682 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,07-27 15:04:46.218  7682  7682 I AppConfig: Total System Memory = 2995761152
,07-27 15:04:46.229  7682  7682 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
07-27 15:04:46.317  1033  1051 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7704 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-27 15:04:46.318  1033  1051 I ActivityManager: Killing 6386:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,07-27 15:04:46.385  1033  1973 W libprocessgroup: failed to open /acct/uid_1000/pid_6386/cgroup.procs: No such file or directory
,07-27 15:04:46.576  7704  7704 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,07-27 15:04:46.651  7704  7704 D LgDataFeature: LgDataFeature() Constructor: none
07-27 15:04:46.651  7704  7704 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-27 15:04:46.704  7704  7704 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,07-27 15:04:46.724  7704  7704 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-27 15:04:46.725  7704  7704 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
07-27 15:04:46.741  7704  7704 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
07-27 15:04:46.742  7704  7704 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,07-27 15:04:46.769  1033  1973 I ActivityManager: Killing 7017:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,07-27 15:04:46.887  1033  1889 W libprocessgroup: failed to open /acct/uid_10046/pid_7017/cgroup.procs: No such file or directory
,07-27 15:04:46.898  4604  7741 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
07-27 15:04:46.930  1033  1630 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7742 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,07-27 15:04:46.943  2861  2958 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,07-27 15:04:46.974  2861  2958 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@271aecb6 on behalf of 7704
,07-27 15:04:46.987  7704  7704 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,07-27 15:04:46.998  7704  7704 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,07-27 15:04:47.035  7742  7742 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,07-27 15:04:47.057  7742  7742 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
07-27 15:04:47.057  7742  7742 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
07-27 15:04:47.057  7742  7742 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
07-27 15:04:47.057  7742  7742 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
07-27 15:04:47.058  7742  7742 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
07-27 15:04:47.058  7742  7742 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,07-27 15:04:47.076  1033  2015 I ActivityManager: Killing 7040:com.android.chrome/u0a57 (adj 15): empty #17
,07-27 15:04:47.107  1033  1907 W libprocessgroup: failed to open /acct/uid_10057/pid_7040/cgroup.procs: No such file or directory
,07-27 15:04:47.277  1033  1943 V SIM_STK : Menu title from STK is T-Mobile
,07-27 15:04:47.304  4604  7741 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 406 ms] updated apps [took 405 ms] 
,07-27 15:04:47.735  7508  7559 D UEI.SmartControl: Internal timer expired: 1
,07-27 15:04:47.735  7508  7559 D UEI.SmartControl: unbind internal service
,07-27 15:04:47.753  7508  7508 D UEI.SmartControl: Service.onUnbind: IControl
,07-27 15:04:47.758  7508  7508 D UEI.SmartControl: Service.onDestroy
07-27 15:04:47.758  7508  7508 D UEI.SmartControl: Lock is in USE false
07-27 15:04:47.758  7508  7508 D UEI.SmartControl: unbind internal service
07-27 15:04:47.758  7508  7508 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@37662a7e
07-27 15:04:47.759  7508  7508 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
07-27 15:04:47.759  7508  7508 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
07-27 15:04:47.759  7508  7508 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
07-27 15:04:47.759  7508  7508 W System.err: 	at com.uei.control.Service.c(Unknown Source)
07-27 15:04:47.759  7508  7508 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
07-27 15:04:47.759  7508  7508 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
07-27 15:04:47.759  7508  7508 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
07-27 15:04:47.759  7508  7508 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
07-27 15:04:47.759  7508  7508 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 15:04:47.759  7508  7508 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-27 15:04:47.759  7508  7508 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-27 15:04:47.759  7508  7508 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 15:04:47.759  7508  7508 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 15:04:47.759  7508  7508 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-27 15:04:47.759  7508  7508 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-27 15:04:47.760  7508  7508 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@37662a7e
07-27 15:04:47.762  7508  7508 D serial_port: close(fd = 25)
07-27 15:04:47.766  7508  7508 I UEI.SmartControl: Serial port is closed.
07-27 15:04:47.766  7508  7508 I UEI.SmartControl: Serial port is closed.
07-27 15:04:47.766  7508  7508 D UEI.SmartControl: Blaster closed
07-27 15:04:47.766  7508  7508 D UEI.SmartControl: Shut down QS...
07-27 15:04:47.766  7508  7508 D UEI.SmartControl: Stopping QS lib
07-27 15:04:47.767  7508  7508 D UEI.SmartControl: QS lib stop result = true
07-27 15:04:47.767  7508  7508 D UEI.SmartControl: Stopped QS lib
07-27 15:04:47.767  7508  7508 D UEI.SmartControl: Stopped file observer...
07-27 15:04:47.767  7508  7508 D UEI.SmartControl: QS shutdown complete
,07-27 15:04:48.081  6632  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-27 15:04:48.081  6632  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@307aa369 added. We now have 6 listener(s)
07-27 15:04:48.081  6632  6695 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-27 15:04:48.096  6632  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 15:04:48.096  6632  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e37c1ee added. We now have 7 listener(s)
07-27 15:04:48.096  6632  6695 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 15:04:48.098  6632  6695 I System.out: IsBluetoothEnabled
07-27 15:04:48.099  1033  1870 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 15:04:48.099  1033  1870 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
,07-27 15:04:48.101  1033  1098 D BluetoothManagerService: Message: 2
07-27 15:04:48.105  6632  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:48.105  1033  1576 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 15:04:48.106  1033  1576 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,07-27 15:04:48.123  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-27 15:04:48.124  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-27 15:04:48.124  1033  1033 D Ulp_jni : JNI:system_update. Event-4
07-27 15:04:48.125  1033  1098 D BluetoothManagerService: Message: 1
07-27 15:04:48.125  1033  1098 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
07-27 15:04:48.152  1033  1098 D BluetoothManagerService: Message: 20
07-27 15:04:48.152  1033  1098 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3b9cc687:true
,07-27 15:04:48.156  7581  7581 D BluetoothAdapterState: make
07-27 15:04:48.161  7581  7581 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
07-27 15:04:48.161  7581  7581 I bluedroid-qcom: init
07-27 15:04:48.163  7581  7787 I BluetoothAdapterState: Entering OffState
07-27 15:04:48.163  7581  7581 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
07-27 15:04:48.163  7581  7581 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-27 15:04:48.163  7581  7581 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-27 15:04:48.163  7581  7581 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-27 15:04:48.163  7581  7581 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
07-27 15:04:48.165  7581  7581 I bluedroid-qcom: get_profile_interface socket
07-27 15:04:48.165  7581  7581 I bluedroid-qcom: get_profile_interface map_client
,07-27 15:04:48.170  7581  7791 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
07-27 15:04:48.162  7790  7790 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 15:04:48.172  7790  7790 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 15:04:48.180  7581  7791 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,07-27 15:04:48.188  7790  7790 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
07-27 15:04:48.188  7790  7790 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
07-27 15:04:48.188  7790  7790 I LGFTMITEM: [GET_FTM][id=8], offset=16384
07-27 15:04:48.189  1033  1033 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
07-27 15:04:48.190  1033  1098 D BluetoothManagerService: Message: 40
07-27 15:04:48.190  1033  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
07-27 15:04:48.191  1033  1033 D BluetoothManagerService: Bluetooth Adapter name changed to G3
07-27 15:04:48.191  1033  1033 D BluetoothManagerService: Stored Bluetooth name: G3
07-27 15:04:48.192  7581  7597 I bluedroid-qcom: config_hci_snoop_log
,07-27 15:04:48.194  7790  7790 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
07-27 15:04:48.196  1033  1098 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
07-27 15:04:48.196  1033  1098 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
07-27 15:04:48.200  7581  7791 D BluetoothAdapterProperties: Name is: G3
07-27 15:04:48.203  7790  7790 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
07-27 15:04:48.203  7790  7790 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
07-27 15:04:48.207  7581  7787 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
07-27 15:04:48.207  7581  7787 D BluetoothAdapterProperties: Setting state to 11
07-27 15:04:48.207  7581  7787 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,07-27 15:04:48.211  7581  7787 I LGBluetoothServiceJni: classInitNative: succeeds
07-27 15:04:48.215  1033  1098 D BluetoothManagerService: Message: 60
07-27 15:04:48.215  1033  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
07-27 15:04:48.215  1033  1098 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
07-27 15:04:48.219  1944  1944 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,07-27 15:04:48.222  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-27 15:04:48.233  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 15:04:48.248  6749  6749 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,07-27 15:04:48.257  7581  7787 D BluetoothBondStateMachine: make
07-27 15:04:48.260  7581  7787 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2daef400
07-27 15:04:48.260  7581  7787 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
07-27 15:04:48.260  7581  7787 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2daef400
,07-27 15:04:48.263  7581  7581 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-27 15:04:48.263  7581  7581 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-27 15:04:48.264  7581  7581 V BluetoothPbapReceiver: ***********state = 11
07-27 15:04:48.260  7581  7787 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
07-27 15:04:48.267  7581  7787 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
07-27 15:04:48.268  7581  7805 I BluetoothBondStateMachine: StableState(): Entering Off State
07-27 15:04:48.268  2188  2188 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-27 15:04:48.274  7581  7787 E BluetoothAdapterService: File transfer profiles supported!!
,07-27 15:04:48.282  6749  6749 D BluetoothPermissionRequest: onReceive
07-27 15:04:48.282  7581  7581 D HeadsetService: Received start request. Starting profile...
07-27 15:04:48.283  7581  7581 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
07-27 15:04:48.283  7581  7581 D LGBluetoothHfpAdapter: Version 1.6
07-27 15:04:48.285  7581  7787 E BluetoothAdapterService: File transfer profiles supported!!
07-27 15:04:48.286  7581  7581 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-27 15:04:48.287  7581  7581 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-27 15:04:48.287  6749  6749 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-27 15:04:48.288  7581  7581 D HeadsetStateMachine: make
,07-27 15:04:48.294  7581  7787 E BluetoothAdapterService: File transfer profiles supported!!
,07-27 15:04:48.300  7581  7787 E BluetoothAdapterService: File transfer profiles supported!!
,07-27 15:04:48.305  7581  7787 E BluetoothAdapterService: File transfer profiles supported!!
07-27 15:04:48.310  7581  7787 E BluetoothAdapterService: File transfer profiles supported!!
07-27 15:04:48.315  7581  7787 E BluetoothAdapterService: File transfer profiles supported!!
,07-27 15:04:48.320  7581  7581 D LgDataFeature: LgDataFeature() Constructor: none
07-27 15:04:48.320  7581  7581 D LgDataFeature: LgDataFeature() Constructor Done, null
07-27 15:04:48.325  7581  7581 D HeadsetStateMachine: max_hf_connections = 1
07-27 15:04:48.325  7581  7581 I bluedroid-qcom: get_profile_interface handsfree
07-27 15:04:48.327  7581  7787 V LGMDMManager: Create singleton instance
07-27 15:04:48.327  7581  7581 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
07-27 15:04:48.328   315  1383 V AudioPolicyService: registerClient() client 0xb1021e60, uid 1002
07-27 15:04:48.328   315  1384 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
07-27 15:04:48.328   315  1384 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-27 15:04:48.328   315  1384 V AudioPolicyManagerEx: getOutput() returns output 2
07-27 15:04:48.328  7581  7581 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
07-27 15:04:48.328   315   315 V AudioFlinger: registerClient() client 0xb101fcb8, pid 7581
07-27 15:04:48.328  7581  7787 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
07-27 15:04:48.329   315  1378 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-27 15:04:48.329   315  1378 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-27 15:04:48.329  1033  2034 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-27 15:04:48.329  1033  2034 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-27 15:04:48.329  3422  3439 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-27 15:04:48.329  3422  3439 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-27 15:04:48.329  1604  3134 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-27 15:04:48.329  1604  3134 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-27 15:04:48.329  7581  7596 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-27 15:04:48.329  1853  1869 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-27 15:04:48.329   315  1379 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-27 15:04:48.329  1853  1869 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-27 15:04:48.329   315  1379 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-27 15:04:48.329  1604  2099 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-27 15:04:48.329  1604  2099 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-27 15:04:48.330  1853  2461 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-27 15:04:48.330  1853  2461 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-27 15:04:48.330  1033  1943 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-27 15:04:48.330  1033  1943 V AudioSystem: ioConfigChanged() opening already existing output! 4
,07-27 15:04:48.330  3422  3438 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-27 15:04:48.330  3422  3438 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-27 15:04:48.331  7581  7596 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
07-27 15:04:48.331  7581  7596 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-27 15:04:48.331  7581  7596 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
07-27 15:04:48.331  7581  7581 V ToneGenerator: Create Track: 0xb4928a80
07-27 15:04:48.331  7581  7581 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
07-27 15:04:48.331  7581  7581 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
07-27 15:04:48.331   315  2148 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
07-27 15:04:48.331   315  2148 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
07-27 15:04:48.331   315  2148 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-27 15:04:48.331   315  2148 V AudioPolicyManagerEx: getOutput() returns output 2
07-27 15:04:48.332   315  1383 I AudioFlinger: isAudioPlaybackHookOn() false
07-27 15:04:48.332   315  1384 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
07-27 15:04:48.332   315  1384 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
07-27 15:04:48.332   315  1384 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-27 15:04:48.332   315  1384 V AudioPolicyManagerEx: getOutput() returns output 2
07-27 15:04:48.332  7581  7581 V AudioSystem: getLatency() output 2, latency 50
07-27 15:04:48.332  7581  7581 V AudioSystem: getFrameCount() output 2, frameCount 960
07-27 15:04:48.332  7581  7581 V AudioTrack: createTrack_l() output 2 afLatency 50
07-27 15:04:48.333   315   315 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
07-27 15:04:48.333   315   315 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
07-27 15:04:48.333   315   315 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
,07-27 15:04:48.333   315   315 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
07-27 15:04:48.333   315   315 V AudioFlinger: createTrack() lSessionId: 23
07-27 15:04:48.334  7581  7581 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
07-27 15:04:48.335   315   315 V AudioFlinger: acquiring 23 from 7581, for 7581
07-27 15:04:48.335   315   315 V AudioFlinger:  added new entry for 23
07-27 15:04:48.335  7581  7581 V ToneGenerator: ToneGenerator INIT OK, time: 151020
07-27 15:04:48.335  7581  7581 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2daef400
07-27 15:04:48.336  7581  7810 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
07-27 15:04:48.336  7581  7810 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-27 15:04:48.336  7581  7810 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-27 15:04:48.337  7581  7581 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2daef400
07-27 15:04:48.337  7581  7810 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
07-27 15:04:48.337   315  1383 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7581
07-27 15:04:48.338  7581  7581 D A2dpService: Received start request. Starting profile...
07-27 15:04:48.339  7581  7581 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-27 15:04:48.340   315  1383 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
07-27 15:04:48.340   315  1383 V voice   : voice_set_parameters: enter: bt_samplerate=8000
07-27 15:04:48.340   315  1383 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
07-27 15:04:48.340  7581  7581 V Avrcp   : make
07-27 15:04:48.340   315  1383 V compress_voip: voice_extn_compress_voip_set_parameters: exit
07-27 15:04:48.340   315  1383 V voice   : voice_set_parameters: exit with code(0)
07-27 15:04:48.340   315  1383 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
07-27 15:04:48.340   315  1383 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
07-27 15:04:48.341   315  1383 V msm8974_platform: platform_set_parameters: exit with code(0)
07-27 15:04:48.341   315  1383 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
07-27 15:04:48.341  7581  7581 D Avrcp   : [BTUI] Use Native AVRCP : init jni
07-27 15:04:48.341   315  1383 V audio_hw_primary: adev_set_parameters: exit with code(0)
07-27 15:04:48.341  7581  7581 I bluedroid-qcom: get_profile_interface avrcp
07-27 15:04:48.341   315  1383 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
,07-27 15:04:48.344  7581  7810 V ToneGenerator: ToneGenerator destructor
07-27 15:04:48.344  7581  7810 V ToneGenerator: stopTone
07-27 15:04:48.344  7581  7810 V ToneGenerator: Delete Track: 0xb4928a80
07-27 15:04:48.346  7581  7810 V AudioTrack: ~AudioTrack, releasing session id from 7581 on behalf of 7581
07-27 15:04:48.346   315  2147 V AudioFlinger: releasing 23 from 7581 for 7581
07-27 15:04:48.346   315  2147 V AudioFlinger:  decremented refcount to 0
07-27 15:04:48.346   315  2147 V AudioFlinger: purging stale effects
07-27 15:04:48.346   315  2147 V AudioPolicyService: AudioCommandThread() adding release output 2
07-27 15:04:48.346   315  2147 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
07-27 15:04:48.346   315  2147 V AudioFlinger: PlaybackThread::Track destructor
07-27 15:04:48.346   315  1229 V AudioPolicyService: AudioCommandThread() waking up
07-27 15:04:48.346   315  2147 V AudioFlinger: removeClient_l() pid 7581, calling pid 315
07-27 15:04:48.346   315  1229 V AudioPolicyService: AudioCommandThread() processing release output 2
,07-27 15:04:48.346   315  1229 V AudioPolicyManager: releaseOutput() 2
07-27 15:04:48.346   315  1229 V AudioPolicyService: AudioCommandThread() going to sleep
07-27 15:04:48.351  7581  7581 V AudioManager: registerRemoteController: size of Media player list: 0
07-27 15:04:48.352  7581  7581 E AudioManager: No RCC entry present to update
07-27 15:04:48.352  7581  7581 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
07-27 15:04:48.355  7581  7581 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
07-27 15:04:48.356  7581  7581 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
07-27 15:04:48.356  7581  7581 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
,07-27 15:04:48.362  7581  7581 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
07-27 15:04:48.495  1033  1907 V SIM_STK : Menu title from STK is T-Mobile
07-27 15:04:48.495  1033  1907 V SIM_STK : Menu title from STK is T-Mobile
,07-27 15:04:48.630  1033  1051 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,07-27 15:04:48.642  7581  7581 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,07-27 15:04:48.653  7581  7581 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,07-27 15:04:48.655  7581  7581 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
,07-27 15:04:48.655  7581  7581 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
,07-27 15:04:48.656  7581  7581 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
07-27 15:04:48.656  7581  7581 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-27 15:04:48.656  7581  7581 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
07-27 15:04:48.657  7581  7581 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
07-27 15:04:48.657  7581  7581 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
07-27 15:04:48.657  7581  7581 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-27 15:04:48.657  7581  7581 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
07-27 15:04:48.659  7581  7581 I BluetoothA2dpServiceJni: classInitNative
07-27 15:04:48.659  7581  7581 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-27 15:04:48.660  7581  7581 D A2dpStateMachine: make
07-27 15:04:48.665  7581  7581 I bluedroid-qcom: get_profile_interface a2dp
07-27 15:04:48.666  7581  7821 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
07-27 15:04:48.669  7581  7581 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
07-27 15:04:48.669  7581  7581 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
07-27 15:04:48.670  7581  7581 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2daef400
07-27 15:04:48.672  7581  7581 I BluetoothHidServiceJni: classInitNative: succeeds
,07-27 15:04:48.677  7581  7820 D A2dpStateMachine: Enter Disconnected: -2
,07-27 15:04:48.677  7581  7581 D HidService: Received start request. Starting profile...
07-27 15:04:48.678  7581  7581 I bluedroid-qcom: get_profile_interface hidhost
07-27 15:04:48.678  7581  7581 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2daef400
07-27 15:04:48.679  7581  7581 I BluetoothHealthServiceJni: classInitNative: succeeds
07-27 15:04:48.681  7581  7581 D HealthService: Received start request. Starting profile...
07-27 15:04:48.685  7581  7581 I bluedroid-qcom: get_profile_interface health
07-27 15:04:48.685  7581  7581 I LGBluetoothHealthServiceJni: classInitNative: succeeds
07-27 15:04:48.685  7581  7581 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2daef400
07-27 15:04:48.687  7581  7581 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,07-27 15:04:48.690  7581  7581 D PanService: Received start request. Starting profile...
,07-27 15:04:48.690  7581  7581 D BluetoothPanServiceJni: initializeNative(L110): pan
07-27 15:04:48.690  7581  7581 I bluedroid-qcom: get_profile_interface pan
07-27 15:04:48.698  7581  7581 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
07-27 15:04:48.699  7581  7581 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2daef400
,07-27 15:04:48.700  7581  7581 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
07-27 15:04:48.708  7581  7581 D BtGatt.DebugUtils: handleDebugAction() action=null
07-27 15:04:48.709  7581  7581 D BtGatt.GattService: Received start request. Starting profile...
07-27 15:04:48.709  7581  7581 D BtGatt.GattService: start()
07-27 15:04:48.709  7581  7581 I bluedroid-qcom: get_profile_interface gatt
07-27 15:04:48.710  7581  7581 D BtGatt.AdvertiseManager: advertise manager created
07-27 15:04:48.718  7581  7581 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2daef400
,07-27 15:04:48.721  7581  7581 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2daef400
07-27 15:04:48.722  7581  7581 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
07-27 15:04:48.724  7581  7581 V BluetoothMapService: BluetoothMapBinder()
07-27 15:04:48.725  7581  7581 D BluetoothMapService: Received start request. Starting profile...
07-27 15:04:48.725  7581  7581 D BluetoothMapService: start()
07-27 15:04:48.729  7581  7581 D BluetoothMapEmailSettingsLoader: Found 0 applications
07-27 15:04:48.729  7581  7581 D BluetoothMapEmailAppObserver: createReceiver()
07-27 15:04:48.730  7581  7581 D BluetoothMapEmailAppObserver: initObservers()
,07-27 15:04:48.732  7581  7581 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
07-27 15:04:48.744  7581  7581 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2daef400
,07-27 15:04:48.745  7581  7581 D HeadsetStateMachine: Proxy object connected
,07-27 15:04:48.747  7581  7581 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
07-27 15:04:48.747  7581  7581 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
07-27 15:04:48.754  7581  7581 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-27 15:04:48.755  7581  7810 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-27 15:04:48.756  7581  7810 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-27 15:04:48.756  7581  7810 D HeadsetStateMachine: Disconnected process message: 11, size: 0
,07-27 15:04:48.761  7581  7581 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-27 15:04:48.768  7581  7581 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-27 15:04:48.772  7581  7581 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,07-27 15:04:48.778  7581  7581 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-27 15:04:48.779  7581  7581 V PanService: [BTUI] SIM Extra State :ABSENT
07-27 15:04:48.784  7581  7581 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-27 15:04:48.789  7581  7581 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
,07-27 15:04:48.789  7581  7581 V BluetoothMapService: Handler(): got msg=1
07-27 15:04:48.790  7581  7787 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
07-27 15:04:48.791  7581  7787 I bluedroid-qcom: enable
07-27 15:04:48.791  7581  7581 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-27 15:04:48.792  7581  7581 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-27 15:04:48.792  7581  7787 I bt_hci_bdroid: init
07-27 15:04:48.792  7581  7581 V BluetoothSapReceiver: SapReceiver onReceive 
,07-27 15:04:48.792  7581  7581 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-27 15:04:48.792  7581  7581 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
07-27 15:04:48.796  7581  7828 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
07-27 15:04:48.796  7581  7828 I bt-btu  : btu_task pending for preload complete event
07-27 15:04:48.800  7581  7787 I bt_vendor: bt-vendor : init
07-27 15:04:48.800  7581  7787 I bt_vendor: bt-vendor : get_bt_soc_type
07-27 15:04:48.800  7581  7787 E bt_vendor: get_bt_soc_type: Failed to get soc type
07-27 15:04:48.800  7581  7787 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
,07-27 15:04:48.800  7581  7787 D bt_userial_mct: userial_init
07-27 15:04:48.802  7581  7787 D bt_hci_bdroid: set_power 1
07-27 15:04:48.802  7581  7787 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
07-27 15:04:48.802  7581  7787 I bt_vendor: Starting hciattach daemon
07-27 15:04:48.802  7581  7787 I bt_vendor: try to set true
07-27 15:04:48.802  7831  7831 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 15:04:48.802  7831  7831 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 15:04:48.834  7832  7832 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,07-27 15:04:48.910  7838  7838 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,07-27 15:04:48.923  7839  7839 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
07-27 15:04:48.948  7841  7841 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,07-27 15:04:48.960  7842  7842 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,07-27 15:04:48.971  7843  7843 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,07-27 15:04:48.981  7844  7844 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,07-27 15:04:48.999  7846  7846 I libmdmdetect: ESOC framework not supported
07-27 15:04:48.999  7846  7846 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,07-27 15:04:49.007  7846  7846 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
07-27 15:04:49.007  7846  7846 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
07-27 15:04:49.007  7846  7846 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
07-27 15:04:49.007  7846  7846 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
07-27 15:04:49.007  7846  7846 D bthci_qcomm_common: [BTUI]     LE: Class 2
07-27 15:04:49.007  7846  7846 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
07-27 15:04:49.007  7846  7846 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
07-27 15:04:49.042  7846  7847 E QC-QMI  : qmi_client [7846] 15: failed to locate client data
07-27 15:04:49.043   453   453 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
07-27 15:04:49.043   453   453 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,07-27 15:04:49.088  7848  7848 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,07-27 15:04:49.102  7849  7849 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
07-27 15:04:49.162  7581  7787 I bt_vendor: bluetooth satus is on
07-27 15:04:49.162  7581  7787 D bt_hci_bdroid: preload
07-27 15:04:49.163  7581  7830 D bt_userial_mct: userial_open(port:0)
07-27 15:04:49.163  7581  7830 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,07-27 15:04:49.168  7581  7830 I bt_vendor: Done intiailizing UART
07-27 15:04:49.172  7581  7830 I bt_vendor: Done intiailizing UART
07-27 15:04:49.172  7581  7830 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
07-27 15:04:49.173  7581  7830 I bt_vendor: Bluetooth Firmware and transport layer are initialized
07-27 15:04:49.174  7581  7828 I bt-btu  : btu_task received preload complete event
07-27 15:04:49.174  7581  7851 D bt_userial_mct: Entering userial_read_thread()
07-27 15:04:49.175  7581  7828 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
07-27 15:04:49.175  7581  7828 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
07-27 15:04:49.181  7581  7828 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
07-27 15:04:49.192  7581  7828 I         : BTE_InitTraceLevels -- TRC_HCI
07-27 15:04:49.192  7581  7828 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-27 15:04:49.192  7581  7828 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-27 15:04:49.192  7581  7828 I         : BTE_InitTraceLevels -- TRC_AVDT
07-27 15:04:49.192  7581  7828 I         : BTE_InitTraceLevels -- TRC_AVRC
07-27 15:04:49.192  7581  7828 I         : BTE_InitTraceLevels -- TRC_A2D
,07-27 15:04:49.193  7581  7828 I         : BTE_InitTraceLevels -- TRC_BNEP
,07-27 15:04:49.193  7581  7828 I         : BTE_InitTraceLevels -- TRC_BTM
07-27 15:04:49.193  7581  7828 I         : BTE_InitTraceLevels -- TRC_HID_HOST
07-27 15:04:49.193  7581  7828 I         : BTE_InitTraceLevels -- TRC_GAP
,07-27 15:04:49.193  7581  7828 I         : BTE_InitTraceLevels -- TRC_PAN
07-27 15:04:49.193  7581  7828 I         : BTE_InitTraceLevels -- TRC_SDP
07-27 15:04:49.193  7581  7828 I         : BTE_InitTraceLevels -- TRC_GATT
07-27 15:04:49.193  7581  7828 I         : BTE_InitTraceLevels -- TRC_SMP
07-27 15:04:49.193  7581  7828 I         : BTE_InitTraceLevels -- TRC_BTAPP
,07-27 15:04:49.193  7581  7828 I         : BTE_InitTraceLevels -- TRC_BTIF,
,07-27 15:04:49.304  7581  7828 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,07-27 15:04:49.304  7581  7828 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa019a061 
,07-27 15:04:49.305  7581  7828 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa019a061 ,
,07-27 15:04:49.337  7581  7791 E bt-btif : Calling BTA_HhEnable
07-27 15:04:49.337  7581  7791 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
07-27 15:04:49.337  7581  7791 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,07-27 15:04:49.340  7581  7828 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
07-27 15:04:49.340  7581  7828 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
07-27 15:04:49.340  7581  7828 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
07-27 15:04:49.341  7581  7828 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
07-27 15:04:49.341  7581  7828 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
07-27 15:04:49.342  1033  1033 D BluetoothManagerService: Bluetooth Adapter name changed to G3
07-27 15:04:49.342  1033  1033 D BluetoothManagerService: Stored Bluetooth name: G3
07-27 15:04:49.343  7581  7791 D BluetoothAdapterProperties: Name is: G3
07-27 15:04:49.344  7581  7791 D BluetoothAdapterProperties: Scan Mode:20
07-27 15:04:49.344  7581  7791 D BluetoothAdapterProperties: Discoverable Timeout:120
07-27 15:04:49.344  7581  7791 D bt_hci_bdroid: postload
07-27 15:04:49.344  7581  7830 D bt_hci_bdroid: Used up Tx Cmd credits
07-27 15:04:49.345  7581  7830 D bt_hci_bdroid: Used up Tx Cmd credits
07-27 15:04:49.345  7581  7830 D bt_hci_bdroid: Used up Tx Cmd credits
07-27 15:04:49.346  7581  7828 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
07-27 15:04:49.347  7581  7830 D bt_hci_bdroid: Used up Tx Cmd credits
07-27 15:04:49.347  7581  7791 D bte_conf: Device ID record 1 : primary
07-27 15:04:49.347  7581  7791 D bte_conf:   vendorId            = 00c4
07-27 15:04:49.347  7581  7791 D bte_conf:   vendorIdSource      = 0001
07-27 15:04:49.347  7581  7791 D bte_conf:   product             = 13a1
07-27 15:04:49.347  7581  7791 D bte_conf:   version             = 1000
07-27 15:04:49.347  7581  7791 D bte_conf:   clientExecutableURL = 
07-27 15:04:49.347  7581  7791 D bte_conf:   serviceDescription  = 
07-27 15:04:49.347  7581  7791 D bte_conf:   documentationURL    = 
07-27 15:04:49.347  7581  7791 D bte_conf: bte_load_did_conf no section named DID2.
07-27 15:04:49.348  7581  7851 E bt_mct  : hci lib postload completed
07-27 15:04:49.351  7581  7787 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
07-27 15:04:49.351  7581  7787 D BluetoothAdapterProperties: ScanMode =  20
07-27 15:04:49.351  7581  7787 D BluetoothAdapterProperties: State =  11
07-27 15:04:49.351  7581  7787 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
07-27 15:04:49.352  7581  7787 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
07-27 15:04:49.352  7581  7787 D BluetoothAdapterProperties: Setting state to 12
07-27 15:04:49.352  7581  7787 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,07-27 15:04:49.352  7856  7856 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 15:04:49.360  1033  1098 D BluetoothManagerService: Message: 60
07-27 15:04:49.360  1033  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
07-27 15:04:49.360  1033  1098 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
07-27 15:04:49.360  1033  1098 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 15:04:49.352  7856  7856 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 15:04:49.365  7581  7828 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-27 15:04:49.365  7581  7828 W bt-smp  : Plain text(LSB ~ MSB) = 10 e7 7b 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-27 15:04:49.365  7581  7828 W bt-smp  : Encrypted text(LSB ~ MSB) = 80 2d f6 4f b2 19 11 8d 8e 4c 6c 8d d3 e8 5e c1 
,07-27 15:04:49.368  7581  7828 W bt-btm  : Stopping oneshot timer
07-27 15:04:49.369  7581  7791 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-27 15:04:49.372  7581  7791 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
07-27 15:04:49.392  7581  7828 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-27 15:04:49.392  7581  7828 W bt-smp  : Plain text(LSB ~ MSB) = ac c8 64 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-27 15:04:49.392  7581  7828 W bt-smp  : Encrypted text(LSB ~ MSB) = b4 ee e7 20 e8 03 4d f0 9a 13 97 ef 43 9e f3 08 
,07-27 15:04:49.395  7581  7828 W bt-btm  : Stopping oneshot timer
07-27 15:04:49.405  7581  7787 I BluetoothAdapterState: Entering On State
,07-27 15:04:49.422  7581  7828 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-27 15:04:49.423  7581  7828 W bt-smp  : Plain text(LSB ~ MSB) = e6 96 58 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-27 15:04:49.423  7581  7828 W bt-smp  : Encrypted text(LSB ~ MSB) = 5d 19 ff 49 43 64 04 49 28 64 87 a6 6a d9 cf 98 
,07-27 15:04:49.425  7581  7828 W bt-btm  : Stopping oneshot timer
07-27 15:04:49.426  7581  7791 D BluetoothAdapterProperties: Discoverable Timeout:120
07-27 15:04:49.426  7581  7791 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
07-27 15:04:49.432  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 15:04:49.432  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:49.432  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:49.432  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 15:04:49.432  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 15:04:49.432  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 15:04:49.432  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 15:04:49.432  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 15:04:49.437  7581  7828 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-27 15:04:49.437  7581  7828 W bt-smp  : Plain text(LSB ~ MSB) = 94 4d 7e 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-27 15:04:49.437  7581  7828 W bt-smp  : Encrypted text(LSB ~ MSB) = 49 6d 5e 2e ca 21 0b af 60 f1 5f 63 fd ef d7 e7 
,07-27 15:04:49.440  7581  7828 W bt-btm  : Stopping oneshot timer
07-27 15:04:49.449  6632  6632 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-27 15:04:49.458  7581  7828 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-27 15:04:49.458  7581  7828 W bt-smp  : Plain text(LSB ~ MSB) = eb 55 4b 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-27 15:04:49.458  7581  7828 W bt-smp  : Encrypted text(LSB ~ MSB) = 8b 9e 61 b1 96 6f 54 e3 62 00 9a df a0 8d 87 b3 
07-27 15:04:49.458  7581  7828 W bt-btm  : Stopping oneshot timer
07-27 15:04:49.466  1033  1033 D BluetoothHeadset: Proxy object connected
,07-27 15:04:49.474  6749  6764 D BluetoothPbap: onBluetoothStateChange: up=true
07-27 15:04:49.475  7581  7787 D LGBluetoothServiceAdapter: [BTUI] OnState
07-27 15:04:49.475  7581  7787 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
07-27 15:04:49.476  7581  7787 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
07-27 15:04:49.478  7581  7787 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
07-27 15:04:49.479  7581  7787 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
07-27 15:04:49.482  1853  1869 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-27 15:04:49.486  1853  1853 D BluetoothHeadset: Proxy object connected
07-27 15:04:49.486  1853  1868 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 15:04:49.489  1853  1853 D BluetoothHeadset: Proxy object connected
07-27 15:04:49.489  6749  7479 D BluetoothA2dp: onBluetoothStateChange: up=true
07-27 15:04:49.491  6749  7480 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 15:04:49.491  7875  7875 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
07-27 15:04:49.492  6749  6749 D BluetoothA2dp: Proxy object connected
07-27 15:04:49.492  6749  6749 D A2dpProfile: Bluetooth service connected
07-27 15:04:49.494  1853  1869 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 15:04:49.494  6749  6749 D BluetoothHeadset: Proxy object connected
07-27 15:04:49.494  6749  6749 D HeadsetProfile: Bluetooth service connected
07-27 15:04:49.496  1853  1853 D BluetoothHeadset: Proxy object connected
,07-27 15:04:49.497  6749  7479 D BluetoothMap: onBluetoothStateChange: up=true
07-27 15:04:49.499  6749  6765 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-27 15:04:49.499  6749  6749 D BluetoothMap: Proxy object connected
07-27 15:04:49.499  6749  6749 D MapProfile: Bluetooth service connected
07-27 15:04:49.499  6749  6749 D BluetoothMap: getConnectedDevices()
07-27 15:04:49.500  7581  7597 V BluetoothMapService: getConnectedDevices()
07-27 15:04:49.501  6749  6749 D BluetoothInputDevice: Proxy object connected
07-27 15:04:49.501  1033  1098 D BluetoothA2dp: onBluetoothStateChange: up=true
07-27 15:04:49.501  6749  6749 D HidProfile: Bluetooth service connected
07-27 15:04:49.502  1033  1033 D BluetoothA2dp: Proxy object connected
07-27 15:04:49.502  6749  7480 D BluetoothPan: onBluetoothStateChange on: true
07-27 15:04:49.502  6749  7480 D BluetoothPan: onBluetoothStateChange call bindService
07-27 15:04:49.505  6749  6749 D BluetoothPan: BluetoothPAN Proxy object connected
07-27 15:04:49.505  6749  6749 D PanProfile: Bluetooth service connected
07-27 15:04:49.506  1033  1098 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
07-27 15:04:49.506  1033  1098 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
07-27 15:04:49.507  1033  1033 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
07-27 15:04:49.508  1944  1944 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,07-27 15:04:49.508  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-27 15:04:49.508  1944  2150 D LGBluetoothAPIService: Message: 1
07-27 15:04:49.508  1944  2150 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
07-27 15:04:49.512  1033  1098 D BluetoothManagerService: Message: 40
07-27 15:04:49.512  1033  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
07-27 15:04:49.515  7581  7581 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-27 15:04:49.515  7581  7581 D BluetoothMapService: STATE_ON
07-27 15:04:49.516  1944  2150 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
07-27 15:04:49.516  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:49.520  6749  6749 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
07-27 15:04:49.521  6749  6749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,07-27 15:04:49.528  6749  6749 D DockEventReceiver: finishStartingService: stopping service
07-27 15:04:49.528  7581  7581 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2daef400
07-27 15:04:49.528  7581  7581 V BluetoothPbapService: Pbap Service onCreate
07-27 15:04:49.528  7581  7581 V BluetoothPbapService: Starting PBAP service
07-27 15:04:49.529  7581  7581 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
07-27 15:04:49.530  7581  7581 V BluetoothPbapService: Pbap Service onBind
07-27 15:04:49.531  7581  7581 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-27 15:04:49.531  7581  7581 V BluetoothPbapService: state: 12
07-27 15:04:49.531  7581  7581 V BluetoothMapService: Handler(): got msg=1
07-27 15:04:49.531  6749  6749 D BluetoothPbap: Proxy object connected
07-27 15:04:49.531  6749  6749 D PbapServerProfile: Bluetooth service connected
07-27 15:04:49.532  7581  7581 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
07-27 15:04:49.533  7581  7881 D BluetoothMapMasInstance: MAS initSocket()
07-27 15:04:49.533  7581  7581 D LGBluetoothAPIServer: [BTUI] onCreate()
07-27 15:04:49.533  7581  7581 D LGBluetoothAPIServer: [BTUI] onBind()
07-27 15:04:49.533  7581  7881 D BluetoothMapMasInstance:   masId = 00
07-27 15:04:49.533  7581  7881 D BluetoothMapMasInstance:   msgTypes = 0e
07-27 15:04:49.533  7581  7881 D BluetoothMapMasInstance:   masName = SMS/MMS
07-27 15:04:49.533  7581  7881 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
07-27 15:04:49.534  7581  7581 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-27 15:04:49.534  7581  7581 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,07-27 15:04:49.534  7581  7581 V BluetoothPbapReceiver: ***********state = 12
07-27 15:04:49.536  1033  1630 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 15:04:49.536  1944  1944 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
07-27 15:04:49.536  1944  2150 D LGBluetoothAPIService: Message: 100
07-27 15:04:49.536  1944  2150 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
07-27 15:04:49.537  7581  7581 V BluetoothPbapService: Handler(): got msg=1
07-27 15:04:49.537  7581  7881 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 15:04:49.537  7581  7581 V BluetoothPbapService: Pbap Service startRfcommSocketListener
07-27 15:04:49.538  7581  7881 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
07-27 15:04:49.538  2188  2188 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-27 15:04:49.538  7581  7881 V BluetoothMapMasInstance: Succeed to create listening socket 
07-27 15:04:49.539  7581  7881 D BluetoothMapMasInstance: Accepting socket connection...
07-27 15:04:49.539  7581  7791 D BluetoothAdapterProperties: Scan Mode:21
07-27 15:04:49.539  7581  7791 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
07-27 15:04:49.539  7581  7882 V BluetoothPbapService: Pbap Service initSocket
07-27 15:04:49.540  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:49.541  2188  2188 D c       : Getting all permits...
07-27 15:04:49.541  2188  2188 D a       : Opening database...
07-27 15:04:49.543  1033  1576 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 15:04:49.543  2188  2188 D a       : Opening database auth.proximity.permit_store...
07-27 15:04:49.544  7581  7882 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 15:04:49.544  2188  2188 D a       : Closing database...
07-27 15:04:49.547  7581  7882 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
07-27 15:04:49.547  7581  7882 V BluetoothPbapService: Succeed to create listening socket 
07-27 15:04:49.548  7581  7882 V BluetoothPbapService: Accepting socket connection...
,07-27 15:04:49.554  6749  6749 D BluetoothPermissionRequest: onReceive
07-27 15:04:49.556  6749  6749 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
07-27 15:04:49.557  6749  6749 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-27 15:04:49.560  7581  7581 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,07-27 15:04:49.561  7581  7581 I LGBluetoothOppAdapter: [BTUI] startOppService()
07-27 15:04:49.565  7581  7581 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
07-27 15:04:49.577  7581  7581 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-27 15:04:49.577  7581  7581 V BtOppService: onCreate
07-27 15:04:49.580  7581  7581 V BluetoothOppNotification: send message
07-27 15:04:49.583  7581  7581 V BtOppService: Starting RfcommListener
,07-27 15:04:49.586  7581  7581 D BluetoothOppPreference: Dumping Names:  
07-27 15:04:49.586  7581  7581 D BluetoothOppPreference: {}
07-27 15:04:49.586  7581  7581 D BluetoothOppPreference: Dumping Channels:  
07-27 15:04:49.586  7581  7581 D BluetoothOppPreference: {}
07-27 15:04:49.586  7581  7581 V BtOppService: onStartCommand
07-27 15:04:49.587  7581  7890 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
07-27 15:04:49.589  7581  7581 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-27 15:04:49.589  7581  7581 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
07-27 15:04:49.592  7581  7581 V BluetoothOppNotification: new notify threadi!
07-27 15:04:49.592  7581  7581 V BluetoothOppNotification: send delay message
07-27 15:04:49.592  7581  7581 V BtOppService: start RfcommListener
07-27 15:04:49.594  7581  7581 V BtOppService: RfcommListener started
,07-27 15:04:49.597  7581  7891 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
07-27 15:04:49.597  7581  7892 V BtOppRfcommListener: Starting RFCOMM listener....
07-27 15:04:49.597  7581  7890 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-27 15:04:49.598  1033  2015 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 15:04:49.599  7581  7886 V BtOppService: Deleted complete outbound shares, number =  0
07-27 15:04:49.599  7581  7890 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2b8c6045 on behalf of 
07-27 15:04:49.599  7581  7892 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 15:04:49.600  7581  7892 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
07-27 15:04:49.600  7581  7891 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@a78339a on behalf of 
07-27 15:04:49.600  7581  7892 V BtOppRfcommListener: Started RFCOMM listener....
07-27 15:04:49.600  7581  7892 I BtOppRfcommListener: Accept thread started.
07-27 15:04:49.600  7581  7892 V BtOppRfcommListener: Accepting connection...
07-27 15:04:49.601  7581  7886 V BtOppService: Deleted complete inbound failed shares, number = 0
07-27 15:04:49.601  7581  7886 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
07-27 15:04:49.602  7581  7891 V BluetoothOppNotification: mUpdateCompleteNotification = true
07-27 15:04:49.603  7581  7886 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@180314cb on behalf of 
07-27 15:04:49.603  7581  7890 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
07-27 15:04:49.604  7581  7890 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-27 15:04:49.604  7581  7581 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2daef400
07-27 15:04:49.605  7581  7581 V BluetoothFtpService: Ftp Service onCreate
07-27 15:04:49.605  7581  7581 I BluetoothFtpService: Ftp Service onCreate
07-27 15:04:49.605  7581  7581 V BluetoothFtpService: Ftp Service onStartCommand
07-27 15:04:49.605  7581  7581 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-27 15:04:49.605  7581  7581 V BluetoothFtpService: Starting Listening on sockets
07-27 15:04:49.605  7581  7581 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-27 15:04:49.605  7581  7581 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-27 15:04:49.605  7581  7581 V BluetoothSapReceiver: SapReceiver onReceive 
07-27 15:04:49.605  7581  7581 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-27 15:04:49.605  7581  7581 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
07-27 15:04:49.605  7581  7581 V BluetoothSapReceiver: Calling SAP service start service with action = null
,07-27 15:04:49.611  7581  7581 V BtOppService: ContentObserver received notification
07-27 15:04:49.611  7581  7581 V BtOppService: ContentObserver received notification
07-27 15:04:49.611  7581  7581 V BluetoothFtpService: Handler(): got msg=1
07-27 15:04:49.611  7581  7581 V BluetoothFtpService: Ftp Service startRfcommSocketListener
07-27 15:04:49.611  7581  7581 V BluetoothFtpService: Ftp Service initSocket
07-27 15:04:49.613  7581  7891 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
07-27 15:04:49.616  1033  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 15:04:49.616  7581  7581 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 15:04:49.617  7581  7581 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
,07-27 15:04:49.617  7581  7581 V BluetoothFtpService: Succeed to create listening socket on channel 20
07-27 15:04:49.618  7581  7893 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
07-27 15:04:49.626  7581  7581 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2daef400
07-27 15:04:49.626  7581  7581 V BluetoothSapService: Sap Service onCreate
07-27 15:04:49.628  7581  7581 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-27 15:04:49.628  7581  7581 V BluetoothSapService: state: 12
07-27 15:04:49.628  7581  7581 V BluetoothSapService: Starting SAP server process
07-27 15:04:49.629  7581  7581 V BluetoothSapService: SAP Service startRfcommListenerThread
07-27 15:04:49.622  7894  7894 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 15:04:49.622  7894  7894 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,07-27 15:04:49.630  7581  7895 V BluetoothSapService: Sap Service initRfcommSocket
07-27 15:04:49.631  1033  1888 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 15:04:49.631  7581  7895 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 15:04:49.632  7581  7895 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
07-27 15:04:49.632  7581  7895 V BluetoothSapService: Succeed to create listening socket 
07-27 15:04:49.632  7581  7895 V BluetoothSapService: Accepting socket connection...
07-27 15:04:49.640  7894  7894 V BT_SAP  : Event pipe created
07-27 15:04:49.640  7894  7894 V BT_SAP  : create_server_socket qcom.sap.server
07-27 15:04:49.640  7894  7894 V BT_SAP  : created socket fd 6
07-27 15:04:49.740  1033  2034 I art     : Explicit concurrent mark sweep GC freed 26104(1281KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.887ms total 134.413ms
,07-27 15:04:49.740  7581  7891 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@10eaa354 on behalf of 
07-27 15:04:49.742  7581  7890 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@18a352fd on behalf of 
07-27 15:04:49.744  7581  7890 V BluetoothOppNotification: update too frequent, put in queue
07-27 15:04:49.746  7581  7891 V BluetoothOppNotification: outbound: succ-0  fail-0
07-27 15:04:49.747  7581  7890 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
07-27 15:04:49.747  7581  7890 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-27 15:04:49.749  7581  7891 V BluetoothOppNotification: outbound notification was removed.
07-27 15:04:49.749  7581  7891 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
07-27 15:04:49.751  7581  7890 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2d819bf2 on behalf of 
07-27 15:04:49.752  7581  7891 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2cdf5243 on behalf of 
07-27 15:04:49.752  7581  7890 V BluetoothOppNotification: update too frequent, put in queue
07-27 15:04:49.753  7581  7891 V BluetoothOppNotification: inbound: succ-0  fail-0
07-27 15:04:49.753  7581  7890 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,07-27 15:04:49.756  7581  7891 V BluetoothOppNotification: inbound notification was removed.
,07-27 15:04:49.756  7581  7891 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
07-27 15:04:49.757  7581  7891 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@8f8a0c0 on behalf of 
07-27 15:04:50.163  6632  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 15:04:50.163  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:50.163  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:50.163  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 15:04:50.163  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 15:04:50.163  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 15:04:50.163  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 15:04:50.163  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 15:04:50.178  6632  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-27 15:04:50.186  6632  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 15:04:50.187  6632  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@36e8468f added. We now have 8 listener(s)
07-27 15:04:50.187  6632  6695 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-27 15:04:50.192  1033  1943 D WifiServiceImplEx: setWifiEnabled: false pid=6632, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-27 15:04:50.196  1033  1943 D WifiService: setWifiEnabled: false pid=6632, uid=10118
07-27 15:04:50.196  1033  1943 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-27 15:04:50.201  6632  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 15:04:50.204  1033  1630 D WifiServiceImplEx: setWifiEnabled: true pid=6632, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-27 15:04:50.205  1033  1630 D WifiService: setWifiEnabled: true pid=6632, uid=10118
07-27 15:04:50.205  1033  1630 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-27 15:04:50.224  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
,07-27 15:04:50.225  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,07-27 15:04:50.225  1033  1033 D Ulp_jni : JNI:system_update. Event-4
07-27 15:04:50.226  1033  1537 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
07-27 15:04:50.226  1033  1537 I LGFTMITEM: [GET_FTM][id=6], offset=12288
07-27 15:04:50.229  1033  1537 E WifiUtil: wfc_util_ffile_check_copy(): pid[1033] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
07-27 15:04:50.229  1033  1537 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
07-27 15:04:50.229  1033  1537 E WifiUtil: wfc_util_ffile_check_copy(): pid[1033] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
07-27 15:04:50.229  1033  1537 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
07-27 15:04:50.229  1033  1537 I WifiUtil: Intf0MacAddress=C49A027FFB5D
07-27 15:04:50.229  1033  1537 E WifiHW  : unknown target_country: EU , set to default
07-27 15:04:50.229  1033  1537 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
07-27 15:04:50.229  1033  1537 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
07-27 15:04:50.229  1033  1537 I WifiUtil: gEnableBmps=1
,07-27 15:04:50.597  7581  7581 V BluetoothOppNotification: new notify threadi!
,07-27 15:04:50.597  7581  7581 V BluetoothOppNotification: send delay message
,07-27 15:04:50.614  7581  7908 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,07-27 15:04:50.619  7581  7908 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@275721f9 on behalf of 
,07-27 15:04:50.625  7581  7908 V BluetoothOppNotification: mUpdateCompleteNotification = true
07-27 15:04:50.626  7581  7908 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
07-27 15:04:50.627  7581  7908 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@c09853e on behalf of 
07-27 15:04:50.628  7581  7908 V BluetoothOppNotification: outbound: succ-0  fail-0
07-27 15:04:50.631  7581  7908 V BluetoothOppNotification: outbound notification was removed.
07-27 15:04:50.631  7581  7908 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
07-27 15:04:50.632  7581  7908 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@129acf9f on behalf of 
07-27 15:04:50.632  7581  7908 V BluetoothOppNotification: inbound: succ-0  fail-0
,07-27 15:04:50.636  7581  7908 V BluetoothOppNotification: inbound notification was removed.
07-27 15:04:50.636  7581  7908 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
07-27 15:04:50.637  7581  7908 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@b2708ec on behalf of 
07-27 15:04:50.928   309   884 D SoftapController: Softap fwReload - Ok
,07-27 15:04:50.933  1033  1537 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (700ms)
07-27 15:04:50.936   309   884 D CommandListener: Setting iface cfg
07-27 15:04:50.936   309   884 D CommandListener: Trying to bring down wlan0
07-27 15:04:50.943  1033  1098 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
07-27 15:04:50.944  1033  1098 D Tethering: InitialState.processMessage what=4
,07-27 15:04:50.957   309   884 D CommandListener: Clearing all IP addresses on wlan0
07-27 15:04:50.965  1033  1098 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
07-27 15:04:50.978  1033  1537 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
07-27 15:04:50.996  1033  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-27 15:04:50.996  1033  1537 E WifiStateMachine: useWiFiOffloading() : false
07-27 15:04:50.996  1033  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-27 15:04:50.992  7916  7916 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 15:04:50.992  7916  7916 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 15:04:51.005  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 15:04:51.006  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
07-27 15:04:51.025  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 15:04:51.040  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
07-27 15:04:51.042  1033  1537 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
07-27 15:04:51.042  1033  1537 D WifiMonitor: connecting to supplicant
,07-27 15:04:51.073  7916  7916 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-27 15:04:51.074  6749  6749 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-27 15:04:51.074  6749  6749 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-27 15:04:51.075  6749  6749 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-27 15:04:51.075  6749  6749 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-27 15:04:51.085  6749  6749 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-27 15:04:51.095  6749  6749 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-27 15:04:51.095  6749  6749 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
07-27 15:04:51.095  6749  6749 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-27 15:04:51.095  6749  6749 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-27 15:04:51.095  6749  6749 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-27 15:04:51.095  6749  6749 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-27 15:04:51.097  6749  6749 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-27 15:04:51.097  6749  6749 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-27 15:04:51.098  6749  6749 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-27 15:04:51.098  6749  6749 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-27 15:04:51.098  6749  6749 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-27 15:04:51.099  6749  6749 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-27 15:04:51.099  6749  6749 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
07-27 15:04:51.099  6749  6749 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-27 15:04:51.099  6749  6749 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-27 15:04:51.099  6749  6749 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-27 15:04:51.099  6749  6749 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,07-27 15:04:51.119  7916  7916 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-27 15:04:51.119  7916  7916 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
07-27 15:04:51.149  1033  2007 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7934 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,07-27 15:04:51.193  7916  7916 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-27 15:04:51.229  7916  7916 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,07-27 15:04:51.236  7916  7916 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
07-27 15:04:51.238  1033  1537 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
07-27 15:04:51.239  1033  1537 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
07-27 15:04:51.240  1033  1537 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
07-27 15:04:51.240  1033  1537 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
07-27 15:04:51.241  1033  1537 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
07-27 15:04:51.241  1033  7952 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
07-27 15:04:51.241  1033  7952 D WifiMonitor: Dropping event because (p2p0) is stopped
07-27 15:04:51.242  1033  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-27 15:04:51.242  1033  1537 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
07-27 15:04:51.243  1033  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-27 15:04:51.243  1033  1537 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
,07-27 15:04:51.243  1033  1537 D WifiNative-wlan0: doString: [DRIVER MACADDR]
07-27 15:04:51.245  1033  1537 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
07-27 15:04:51.245  1033  1537 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
07-27 15:04:51.245  1033  1537 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
07-27 15:04:51.246  1033  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-27 15:04:51.246  1033  1537 E WifiStateMachine: useWiFiOffloading() : false
07-27 15:04:51.246  1033  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-27 15:04:51.246  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:51.246  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:51.246  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:51.246  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:51.247  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-27 15:04:51.247  1033  1537 D WifiNative-wlan0: doBoolean: SET update_config 1
07-27 15:04:51.248  1033  1537 D WifiNative-wlan0: SET update_config 1: returned true
07-27 15:04:51.248  1033  1537 D WifiConfigStore: Loading config and enabling all networks 
,07-27 15:04:51.248  1033  1537 D WifiNative-wlan0: doString: [LIST_NETWORKS]
,07-27 15:04:51.249  1033  1537 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
,07-27 15:04:51.252  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
07-27 15:04:51.253  1944  1944 D WfdService: Waiting for WifiP2p enabling
,07-27 15:04:51.254  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 15:04:51.254  1033  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
07-27 15:04:51.256  7916  7916 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
07-27 15:04:51.257  1033  7952 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
,07-27 15:04:51.257  1033  7952 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
07-27 15:04:51.257  1033  7952 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
07-27 15:04:51.257  1033  7952 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
07-27 15:04:51.258  1033  7952 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
07-27 15:04:51.258  1033  7952 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,07-27 15:04:51.258  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 15:04:51.258  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:51.258  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:51.258  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 15:04:51.258  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 15:04:51.258  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 15:04:51.258  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 15:04:51.258  6632  6632 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 15:04:51.260  6632  6632 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-27 15:04:51.274  1033  1537 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
07-27 15:04:51.287  1033  1537 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
07-27 15:04:51.287  1033  1537 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,07-27 15:04:51.315  1033  1943 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7957 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,07-27 15:04:51.319  1033  1537 D WifiStateMachine: enableVerboseLogging : level 2
07-27 15:04:51.319  1033  1537 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
07-27 15:04:51.320  1033  1537 D WifiNative-wlan0: SET device_name g3_global_com: returned true
07-27 15:04:51.320  1033  1537 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
,07-27 15:04:51.321  1033  1537 D WifiNative-wlan0: SET manufacturer LGE: returned true
07-27 15:04:51.321  1033  1537 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
07-27 15:04:51.321  7934  7955 W FormManager: Network not available. Please check & try again.
07-27 15:04:51.321  1033  1537 D WifiNative-wlan0: SET model_name LG-D855: returned true
07-27 15:04:51.321  1033  1537 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
,07-27 15:04:51.322  1033  1537 D WifiNative-wlan0: SET model_number LG-D855: returned true
07-27 15:04:51.322  1033  1537 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
07-27 15:04:51.322  1033  1537 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
07-27 15:04:51.322  1033  1537 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
07-27 15:04:51.323  1033  1537 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
07-27 15:04:51.323  1033  1537 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
07-27 15:04:51.324  1033  1537 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
07-27 15:04:51.326  1944  1944 D WfdsService: Supplicant Connection state is changed : true
07-27 15:04:51.326  7608  7608 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:51.326  1033  1537 D WifiStateMachine: Setting OUI to DA-A1-19
07-27 15:04:51.326  1033  1537 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
07-27 15:04:51.327  1033  1537 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
07-27 15:04:51.327  1944  2341 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
07-27 15:04:51.327  1033  1537 D WifiNative-HAL: Setting external_sim to 1
07-27 15:04:51.327  1033  1537 D WifiNative-wlan0: doBoolean: SET external_sim 1
07-27 15:04:51.327  1944  2341 D WfdsService: Set the WFDS Monitor: true
07-27 15:04:51.327  1944  2341 D WfdsMonitor: WfdsMonitorThread create
07-27 15:04:51.327  1033  1537 D WifiNative-wlan0: SET external_sim 1: returned true
07-27 15:04:51.327  1033  1537 I WifiNative-HAL: startHal
07-27 15:04:51.327  1033  1537 D wifi    : setting scan oui 0xaf66e0c0
07-27 15:04:51.327  1944  2341 D WfdsMonitor: WFDS Monitor is created and started
07-27 15:04:51.327  1944  2341 D WfdsService: WiFi: Supplicant connection re-established
07-27 15:04:51.328  1033  1537 D WifiStateMachine: Setting OUI to DA-A1-19
07-27 15:04:51.328  1033  1537 I WifiNative-HAL: startHal
07-27 15:04:51.328  1033  1537 D wifi    : setting scan oui 0xaf66e0c0
07-27 15:04:51.328  1033  1537 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
07-27 15:04:51.328  1033  1537 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
07-27 15:04:51.328  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
07-27 15:04:51.328  7916  7916 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
07-27 15:04:51.329  1944  7967 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
07-27 15:04:51.330  1944  7967 E CtrlSupplicant: Succeed to open control connection
07-27 15:04:51.330  1944  7967 E CtrlSupplicant: Succeed to open monitor connection
07-27 15:04:51.331  1033  1537 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
07-27 15:04:51.331  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
,07-27 15:04:51.331  7916  7916 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
07-27 15:04:51.331  1033  1537 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
07-27 15:04:51.331  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
07-27 15:04:51.331  7916  7916 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
07-27 15:04:51.332  1033  1537 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
07-27 15:04:51.332  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
07-27 15:04:51.332  7916  7916 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
07-27 15:04:51.332  1033  1537 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
07-27 15:04:51.332  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
07-27 15:04:51.332  7916  7916 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
07-27 15:04:51.332  1033  1537 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
07-27 15:04:51.332  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
07-27 15:04:51.333  7916  7916 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
07-27 15:04:51.333  1944  7967 D WfdsMonitor: Supplicant connection established
07-27 15:04:51.333  1944  2341 D WfdsService: Connected to the supplicant for wfds
07-27 15:04:51.333  1033  1537 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
07-27 15:04:51.333  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
07-27 15:04:51.333  7916  7916 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
07-27 15:04:51.334  1033  1537 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
07-27 15:04:51.335  1033  1537 E WifiNative: : [154,005,620 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
07-27 15:04:51.335  1033  1537 D WifiNative-wlan0: doBoolean: RECONNECT
07-27 15:04:51.335  1033  1537 D WifiNative-wlan0: RECONNECT: returned true
07-27 15:04:51.335  1033  1537 D WifiNative-wlan0: doString: [STATUS]
07-27 15:04:51.336  1033  7952 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
07-27 15:04:51.336  1033  7952 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
07-27 15:04:51.336   346   346 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 437us total 21.450ms
07-27 15:04:51.337  1033  1537 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
07-27 15:04:51.337  1033  1537 D WifiNative-wlan0: doBoolean: SET ps 1
07-27 15:04:51.340  1033  1537 D WifiNative-wlan0: SET ps 1: returned true
07-27 15:04:51.340  1033  1536 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:51.341  1033  1033 D WifiScanningService: SCAN_AVAILABLE : 3
07-27 15:04:51.342  1033  1033 D RttService: SCAN_AVAILABLE : 3
07-27 15:04:51.342  1033  1557 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:51.342  1033  1557 I WifiNative-HAL: startHal
07-27 15:04:51.342  1033  1557 D wifi    : getting scan capabilities on interface[1] = 0xaf66e0c0
07-27 15:04:51.342  1033  1557 D wifi    : failed to get capabilities : -3
07-27 15:04:51.342  1033  1557 E WifiScanningService: could not get scan capabilities
07-27 15:04:51.342  1033  1558 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:51.343   309   884 D CommandListener: Setting iface cfg
07-27 15:04:51.343   309   884 D CommandListener: Trying to bring up p2p0
07-27 15:04:51.343  1033  1536 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-27 15:04:51.343  1033  1536 D LGWifiP2pSe,rvice: P2pEnablingState
07-27 15:04:51.343  1033  1536 D LGWifiP2pService: P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:51.343  1033  1536 D LGWifiP2pService: P2p socket connection successful
07-27 15:04:51.343  1033  1536 D LGWifiP2pService: P2pEnabledState
07-27 15:04:51.344  1033  1536 D LGWifiP2pService: sending p2p connection changed broadcast
07-27 15:04:51.346  1033  1537 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
07-27 15:04:51.346  1033  1537 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
07-27 15:04:51.347  1033  1537 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
07-27 15:04:51.348  1033  1537 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
07-27 15:04:51.349  1033  1537 E WifiStateMachine:  DisconnectedState what:132106 1 0
07-27 15:04:51.349  1033  1537 E WifiStateMachine:  ConnectModeState what:132106 1 0
07-27 15:04:51.349  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
07-27 15:04:51.350  1944  1944 D WfdsService: WifiP2pState is changed : true
07-27 15:04:51.350  1944  2341 D WfdsService: Receive the WFDS_ENABLE Method
07-27 15:04:51.350  1033  1537 E WifiStateMachine:  DriverStartedState what:132106 1 0
07-27 15:04:51.350  1033  1537 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
07-27 15:04:51.350  1944  2341 D WfdsService: Set the WFDS Monitor: true
07-27 15:04:51.350  7916  7916 E wpa_supplicant: nWIFIDualbandAPConnection: 1
07-27 15:04:51.350  1033  1536 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
07-27 15:04:51.352  1944  2341 D WfdsService: Connected to the supplicant for wfds
07-27 15:04:51.352  1944  2341 D WfdsJNI : doCommand: WFDS_SET TRUE
07-27 15:04:51.352  7916  7916 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
07-27 15:04:51.352  1944  2341 D WfdsService: selectPreferredScanChannel [36]
07-27 15:04:51.352  1944  2341 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
07-27 15:04:51.353  1033  1536 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
07-27 15:04:51.354   346   346 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 371us total 16.849ms
07-27 15:04:51.354  1033  1536 D WifiNative-p2p0: doBoolean: SET device_name G3
07-27 15:04:51.355  1033  1536 D WifiNative-p2p0: SET device_name G3: returned true
07-27 15:04:51.355  1033  1536 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
07-27 15:04:51.355  1033  1536 D LGWifiP2pService: before postfix = G3
07-27 15:04:51.355  1033  1536 D WifiServerServiceExt: postfix byte check : 2
07-27 15:04:51.355  1033  1536 D LGWifiP2pService: after postfix = G3
07-27 15:04:51.355  1033  1536 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
07-27 15:04:51.355  1033  1537 E WifiStateMachine:  DisconnectedState what:132096 -100 0
07-27 15:04:51.356  1033  1537 E WifiStateMachine:  ConnectModeState what:132096 -100 0
07-27 15:04:51.356  1944  1944 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
07-27 15:04:51.356  1033  1537 E WifiStateMachine:  DriverStartedState what:132096 -100 0
07-27 15:04:51.356  1033  1537 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
07-27 15:04:51.356  7916  7916 E wpa_supplicant: disconnect_rssi_lvl: -100
07-27 15:04:51.357  1944  1944 D WfdsService: isConnected: false
07-27 15:04:51.357  1033  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=154028  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-27 15:04:51.357  1033  1536 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
07-27 15:04:51.357  1033  1536 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
07-27 15:04:51.357  1033  1536 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
07-27 15:04:51.357  1033  1536 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
07-27 15:04:51.358  1033  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=154029  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-27 15:04:51.359  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:51.359  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:51.359  1033  1537 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
07-27 15:04:51.359  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
07-27 15:04:51.359  1033  1537 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
07-27 15:04:51.360  1033  1537 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
07-27 15:04:51.360  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
07-27 15:04:51.360  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:51.360  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 15:04:51.361  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 15:04:51.362  1033  1536 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
07-27 15:04:51.362  1033  1536 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
07-27 15:04:51.363  1033  1536 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
07-27 15:04:51.363  1033  1536 D WifiNative-HAL: p2pGetDeviceAddress
07-27 15:04:51.364  7916  7916 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
07-27 15:04:51.364  7916  7916 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 15:04:51.365  7916  7916 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
07-27 15:04:51.365  7916  7916 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 15:04:51.365  1033  1537 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
07-27 15:04:51.365  7916  7916 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 15:04:51.366  1033  1537 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
07-27 15:04:51.366  1944  7967 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-27 15:04:51.366  1944  7967 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-27 15:04:51.366  1033  7952 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-27 15:04:51.366  1033  1536 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
07-27 15:04:51.366  1033  7952 E WifiMonitor: WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 15:04:51.366  1033  7952 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 15:04:51.366  1033  7952 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 15:04:51.367  1033  7952 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-27 15:04:51.367  1033  1537 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
07-27 15:04:51.367  1033  7952 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 15:04:51.367  1033  7952 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 15:04:51.367  1033  7952 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 15:04:51.367  1033  7952 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-27 15:04:51.367  1033  7952 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 15:04:51.367  1033  7952 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 15:04:51.367  1033  7952 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 15:04:51.367  1033  1537 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
07-27 15:04:51.367  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
07-27 15:04:51.367  7916  7916 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
07-27 15:04:51.367  7916  7916 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-27 15:04:51.368  1033  7952 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
07-27 15:04:51.368  1033  7952 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-27 15:04:51.368  1033  1536 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
07-27 15:04:51.368  1033  1536 D WifiNative-p2p0: doBoolean: P2P_FLUSH
07-27 15:04:51.368  1033  7952 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-27 15:04:51.368  1033  7952 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-27 15:04:51.368  1033  1537 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
07-27 15:04:51.368  1033  1537 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
07-27 15:04:51.369  1033  1537 D WifiNative-wlan0: BSS_FLUSH 0: returned true
07-27 15:04:51.369  1033  1537 D WifiNative-wlan0: doBoolean: SCAN
07-27 15:04:51.369   346   346 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 281us total 13.246ms
07-27 15:04:51.369  1033  1537 D WifiNative-wlan0: SCAN: returned false
07-27 15:04:51.370  1944  1944 I WfdStateTracker: handleP2pThisDeviceChanged
07-27 15:04:51.370  1944  1944 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
07-27 15:04:51.370  1033  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=154041  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-27 15:04:51.370  1944  1944 D WfdsService: Update P2p Interface State: 3
07-27 15:04:51.370  1033  1536 D WifiNative-p2p0: P2P_FLUSH: returned true
07-27 15:04:51.370  1033  1536 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
07-27 15:04:51.371  1033  1536 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
07-27 15:04:51.371  1033  1536 D WifiNative-p2p0: doString: [LIST_NETWORKS]
07-27 15:04:51.371  1033  1536 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
07-27 15:04:51.371  1033  1536 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
07-27 15:04:51.372  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:51.372  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:51.372  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
,07-27 15:04:51.373  1033  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=154044  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-27 15:04:51.373  1033  1537 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-27 15:04:51.374  1033  1537 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-27 15:04:51.374  1033  1537 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-27 15:04:51.375  1033  1537 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-27 15:04:51.375  1033  1537 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-27 15:04:51.376  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 15:04:51.376  1033  1033 D WifiServerServiceExt: setSupplicantStateSCANNING
07-27 15:04:51.376  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 15:04:51.376  1033  1033 D WifiServerServiceExt: setSupplicantStateSCANNING
07-27 15:04:51.377  7934  7956 V FormManager: Network unavailable.
07-27 15:04:51.380  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:51.380  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 15:04:51.380  1033  1536 D WifiNative-p2p0: SAVE_CONFIG: returned true
07-27 15:04:51.380  1033  1536 D LGWifiP2pService: sending p2p persistent groups changed broadcast
07-27 15:04:51.383  1033  1536 D LGWifiP2pService: InactiveState
07-27 15:04:51.383  1033  1536 D LGWifiP2pService: InactiveState{ when=-18ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:51.383  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=-18ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:51.383  1033  1536 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
07-27 15:04:51.384  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 15:04:51.384  7916  7916 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
07-27 15:04:51.384  7916  7916 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 15:04:51.385  1033  7952 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-27 15:04:51.385  1033  7952 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 15:04:51.385  1033  7952 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 15:04:51.385  1033  7952 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 15:04:51.385  1944  7967 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-27 15:04:51.385  7916  7916 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
07-27 15:04:51.385  7916  7916 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 15:04:51.385  1033  1536 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
07-27 15:04:51.385  1033  1536 D LGWifiP2pService: InactiveState{ when=-15ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:51.385  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=-15ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:51.385  1033  1536 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:51.385  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:51.385  1033  1536 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:51.386  1033  1536 D LGWifiP2pService: InactiveState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:51.386  7916  7916 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 15:04:51.386  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:51.386  7934  7956 V FormManager: Network unavailable.
07-27 15:04:51.386  1033  1536 D LGWifiP2pService: DefaultState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:51.386  1033  1536 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:51.386  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:51.386  1033  1536 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:51.386  1944  2341 W WfdsService: DefaultState - msg [9441285] is not handled
07-27 15:04:51.386  1033  1536 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:51.386  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:51.386  1033  1536 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:51.387  1033  1033 E WifiServerServiceExt: No p2p device connected
07-27 15:04:51.387  1944  7967 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-27 15:04:51.387  1944  7967 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-27 15:04:51.387  1033  7952 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-27 15:04:51.387  1033  7952 E WifiMonitor: WifiMonitor:p2p0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 15:04:51.387  1033  7952 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 15:04:51.387  1033  7952 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 15:04:51.387  1033  7952 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-27 15:04:51.387  1033  7952 E WifiMonitor: WifiMonitor:p2p0 cnt=54 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 15:04:51.387  1033  7952 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 15:04:51.387  1033  7952 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 15:04:51.413  7957  7957 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-27 15:04:51.414  6749  6749 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,07-27 15:04:51.418  6749  6749 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 15:04:51.419  1033  1630 I ActivityManager: Killing 7058:com.lge.drmservice/u0a62 (adj 15): empty #17
07-27 15:04:51.436  1033  2007 W libprocessgroup: failed to open /acct/uid_10062/pid_7058/cgroup.procs: No such file or directory
,07-27 15:04:51.449  7957  7957 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-27 15:04:51.452  6749  6749 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-27 15:04:51.456  6749  6749 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 15:04:51.461  7934  7980 V FormManager: Network unavailable.
07-27 15:04:51.461  7934  7979 W FormManager: Network not available. Please check & try again.
,07-27 15:04:51.463  7934  7980 V FormManager: Network unavailable.
07-27 15:04:51.467  4320  4320 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
07-27 15:04:51.467  4320  4320 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-27 15:04:51.469  4320  4320 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-27 15:04:51.470  4320  4320 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-27 15:04:51.473  4320  7981 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,07-27 15:04:51.475  4320  7982 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
07-27 15:04:51.475  4320  7982 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-27 15:04:51.531  1033  1973 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7983 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,07-27 15:04:51.641  7983  7983 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
07-27 15:04:51.642  7983  7983 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,07-27 15:04:51.649  7983  7983 V [BNRBootReceiver]: Boot Receiver Return
07-27 15:04:51.650  7983  7983 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,07-27 15:04:51.718  1033  1943 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8004 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
07-27 15:04:51.718  1033  1943 I ActivityManager: Killing 7075:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,07-27 15:04:51.775  1033  1889 W libprocessgroup: failed to open /acct/uid_10085/pid_7075/cgroup.procs: No such file or directory
,07-27 15:04:51.800  8004  8004 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,07-27 15:04:51.825  8004  8004 D PluginManager: init()
,07-27 15:04:51.869  7916  7916 E wpa_supplicant: USIM:  scard_init function
07-27 15:04:51.870  7916  7916 I wpa_supplicant: Trying to associate with SSID 'NG700'
,07-27 15:04:51.872  1033  7952 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
07-27 15:04:51.872  1033  7952 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
07-27 15:04:51.872  1033  7952 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
07-27 15:04:51.872  1033  7952 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: WPS-AP-AVAILABLE 
07-27 15:04:51.872  1033  7952 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
07-27 15:04:51.872  1033  7952 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
07-27 15:04:51.872  1033  7952 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
07-27 15:04:51.873  1033  1537 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
07-27 15:04:51.874  1033  1537 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
07-27 15:04:51.876  1033  1537 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
07-27 15:04:51.876  1033  1537 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
07-27 15:04:51.876  1033  1537 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
07-27 15:04:51.887  1033  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=154558  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
07-27 15:04:51.888  1033  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=154559  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,07-27 15:04:51.890  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:51.890  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:51.890  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
07-27 15:04:51.894  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 15:04:51.894  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 15:04:51.896  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 15:04:51.896  1033  1033 D WifiServerServiceExt: setSupplicantStateASSOCIATING
07-27 15:04:51.897  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-27 15:04:51.990  7916  7916 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,07-27 15:04:52.000  1033  7952 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
07-27 15:04:52.000  1033  7952 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
07-27 15:04:52.001  1033  7952 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
,07-27 15:04:52.001  1033  7952 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: Associated with f4:f2:6d:22:99:3e
07-27 15:04:52.001  1033  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=154672  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
07-27 15:04:52.001  1033  7952 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-27 15:04:52.001  1033  7952 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-27 15:04:52.002  1033  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=154673  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
07-27 15:04:52.002  1033  1098 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
07-27 15:04:52.002  1033  1537 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=154674
07-27 15:04:52.003  1033  1537 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=154674
07-27 15:04:52.003  1033  1537 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=154674
07-27 15:04:52.003  1033  1537 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=154675
07-27 15:04:52.004  1033  1537 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=154675
07-27 15:04:52.005  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 15:04:52.005  1033  1033 D WifiServerServiceExt: setSupplicantStateASSOCIATED
07-27 15:04:52.005  1033  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=154677  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
07-27 15:04:52.008  7916  7916 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-27 15:04:52.008  7916  7916 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-27 15:04:52.008  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:52.008  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:52.008  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
07-27 15:04:52.013  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:52.014  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 15:04:52.017  1033  7952 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-27 15:04:52.017  1033  7952 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-27 15:04:52.018  1033  7952 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
,07-27 15:04:52.018  1033  7952 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-27 15:04:52.018  1033  7952 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-27 15:04:52.018  1033  7952 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
07-27 15:04:52.018  1033  7952 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-27 15:04:52.018  1033  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=154689  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
07-27 15:04:52.018  1033  7952 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-27 15:04:52.018  1033  1537 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
07-27 15:04:52.019  1033  7952 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-27 15:04:52.019  1033  7952 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-27 15:04:52.019  1033  1537 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
07-27 15:04:52.019  1033  1537 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
07-27 15:04:52.019  1033  1537 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
07-27 15:04:52.019  1033  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-27 15:04:52.020  1033  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=154691  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
07-27 15:04:52.020  1033  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=154692  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
,07-27 15:04:52.023  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 15:04:52.023  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:52.023  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:52.023  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
07-27 15:04:52.024  1033  1537 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=154695
07-27 15:04:52.025  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 15:04:52.025  1033  1033 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
07-27 15:04:52.025  1033  1537 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=154696
07-27 15:04:52.025  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:52.025  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 15:04:52.025  1033  1537 D WifiNative-wlan0: doString: [STATUS]
07-27 15:04:52.026  1033  7952 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-27 15:04:52.026  1033  1537 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
07-27 15:04:52.026  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 15:04:52.026  1033  7952 E WifiMonitor: WifiMonitor:wlan0 cnt=65 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-27 15:04:52.027  1033  1537 I WifiServiceExtension: setVHTCapabilityType  : false
07-27 15:04:52.033  1033  1537 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
07-27 15:04:52.033  1033  1537 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,07-27 15:04:52.039  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:52.039  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:52.039  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
07-27 15:04:52.041  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:52.041  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:52.041  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
07-27 15:04:52.043  1033  1537 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
07-27 15:04:52.043  1033  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-27 15:04:52.043  1033  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-27 15:04:52.043  1033  1545 D ConnectivityService: Got NetworkAgent Messenger
,07-27 15:04:52.043  1033  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
07-27 15:04:52.043  1033  1545 D ConnectivityService: NetworkAgent connected
07-27 15:04:52.043  1033  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-27 15:04:52.043  1033  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-27 15:04:52.047  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:52.047  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 15:04:52.047  1033  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-27 15:04:52.047  1033  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-27 15:04:52.047  1033  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-27 15:04:52.048  1033  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-27 15:04:52.048  1033  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-27 15:04:52.048  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 15:04:52.051  1033  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
,07-27 15:04:52.052   309   884 D CommandListener: Setting iface cfg
07-27 15:04:52.053  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:52.053  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 15:04:52.054  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 15:04:52.055  1033  1537 E WifiStateMachine: Start Dhcp Watchdog 3
07-27 15:04:52.056  1033  1537 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=154727  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-27 15:04:52.056  1033  1537 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=154728  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-27 15:04:52.057  1033  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=154728  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-27 15:04:52.058  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 15:04:52.058  1033  1033 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
07-27 15:04:52.058  1033  1537 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=154729  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-27 15:04:52.059  1033  1537 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=154730  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-27 15:04:52.059  1033  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=154730  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-27 15:04:52.060  1033  1537 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14075] from screen [on:0 period:745876828] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-27 15:04:52.061  1033  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:745876829] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-27 15:04:52.061  1033  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 15:04:52.061  1033  8022 D DhcpStateMachine: StoppedState
07-27 15:04:52.062  1033  8022 D DhcpStateMachine: StoppedState{ when=-6ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:52.062  1033  8022 D DhcpStateMachine: WaitBeforeStartState
07-27 15:04:52.065  1033  1545 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,07-27 15:04:52.065  1033  1537 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 15:04:52.066  1033  1537 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 15:04:52.066  1033  1537 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 15:04:52.066  1033  1537 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 15:04:52.066  1033  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 15:04:52.067  1033  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 15:04:52.067  1033  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
07-27 15:04:52.068  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 15:04:52.068  1033  1033 D WifiServerServiceExt: setSupplicantStateCOMPLETED
07-27 15:04:52.068  1033  1537 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=137,0,0
07-27 15:04:52.068  1033  1537 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=137,0,0
07-27 15:04:52.068  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
07-27 15:04:52.069  7916  7916 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
07-27 15:04:52.069  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 15:04:52.069  1033  1033 D WifiServerServiceExt: setSupplicantStateCOMPLETED
07-27 15:04:52.069  1033  1537 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
07-27 15:04:52.069  1033  1537 D WifiNative-wlan0: doBoolean: SET ps 0
07-27 15:04:52.069  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-27 15:04:52.070  1033  1537 D WifiNative-wlan0: SET ps 0: returned true
,07-27 15:04:52.070  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
07-27 15:04:52.070  7916  7916 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
07-27 15:04:52.070  1033  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
07-27 15:04:52.070  1033  1537 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
07-27 15:04:52.070  1033  1537 V DhcpStateMachine: Current State is mWaitBeforeStartState.
07-27 15:04:52.070  1033  1536 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@21298a2b target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:52.070  1033  1537 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
07-27 15:04:52.070  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@21298a2b target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:52.070  1033  8022 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:52.070  1033  8022 D DhcpStateMachine: DHCP Start wake lock is acquired.
07-27 15:04:52.071   309   884 D CommandListener: Setting iface cfg
07-27 15:04:52.071   309   884 D CommandListener: Trying to bring up wlan0
07-27 15:04:52.072  1033  1537 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
07-27 15:04:52.073  1033  1537 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 15:04:52.073  1033  1537 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 15:04:52.073  1033  1537 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 15:04:52.073  1033  1537 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 15:04:52.074  1033  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 15:04:52.074  1033  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 15:04:52.075  1033  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
07-27 15:04:52.075  1033  1537 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
07-27 15:04:52.075  1033  1537 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
07-27 15:04:52.075  1033  1536 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:52.075  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:52.075  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-27 15:04:52.076  7916  7916 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-27 15:04:52.076  1033  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-27 15:04:52.076  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
07-27 15:04:52.076  7916  7916 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
07-27 15:04:52.076  1033  1537 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
07-27 15:04:52.076  1033  1537 D WifiNative-wlan0: doBoolean: SET ps 1
,07-27 15:04:52.096  1033  1537 D WifiNative-wlan0: SET ps 1: returned true
07-27 15:04:52.096  1033  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
07-27 15:04:52.097  1033  1537 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
07-27 15:04:52.097  1033  1537 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
07-27 15:04:52.097  1033  1537 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
07-27 15:04:52.097  1033  1545 D ConnectivityService: ignoring duplicate network state non-change
,07-27 15:04:52.099  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:52.099  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 15:04:52.100  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 15:04:52.101  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:52.101  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:52.101  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
07-27 15:04:52.104  1033  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
07-27 15:04:52.104  1033  1545 D ConnectivityService: Adding iface wlan0 to network 102
07-27 15:04:52.106  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:52.106  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:52.106  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
07-27 15:04:52.108  1033  1537 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
07-27 15:04:52.109  1033  1033 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,07-27 15:04:52.113  1944  1944 V WfdStateTracker: handleWifiStateChangedEvent: 1
07-27 15:04:52.113  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:52.113  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:52.113  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
07-27 15:04:52.121  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:52.121  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 15:04:52.122  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 15:04:52.124  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:52.124  1604  1604 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
07-27 15:04:52.125  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-27 15:04:52.125  1033  1033 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
07-27 15:04:52.127  1033  1545 E ConnectivityService: Unexpected mtu value: 0, wlan0
07-27 15:04:52.127  1033  1545 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
07-27 15:04:52.128  1033  1545 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
07-27 15:04:52.129   309   884 E Netd    : netlink response contains error (File exists)
07-27 15:04:52.129  1033  1545 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
07-27 15:04:52.129  1033  1545 D ConnectivityService: addLocalRoutetoDefaultNetwork
07-27 15:04:52.129  1033  1545 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
07-27 15:04:52.129  1033  1545 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
07-27 15:04:52.132  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:52.132  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 15:04:52.132  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
07-27 15:04:52.133  1033  1545 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
07-27 15:04:52.133  1033  1545 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
07-27 15:04:52.133  1033  1545 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
07-27 15:04:52.133  1033  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
07-27 15:04:52.133  1033  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 15:04:52.133  1033  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 15:04:52.133  1033  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
07-27 15:04:52.133  1033  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 15:04:52.133  1033  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
07-27 15:04:52.133  1033  1545 D ConnectivityService: currentScore = 0, newScore = 20
07-27 15:04:52.133  1033  1545 D ConnectivityService:    accepting network in place of null
07-27 15:04:52.133  1033  1545 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 15:04:52.133  1033  8021 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:52.133  1033  8021 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
07-27 15:04:52.134  1033  8021 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-27 15:04:52.134  1033  8021 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
07-27 15:04:52.134  1853  1853 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 15:04:52.134  1033  1537 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 15:04:52.134  1033  1537 D W,IFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 15:04:52.135  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-27 15:04:52.135  1033  1545 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
07-27 15:04:52.135  1033  1545 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
07-27 15:04:52.135  1033  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-27 15:04:52.135  1033  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-27 15:04:52.135  1033  1545 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
07-27 15:04:52.136  1033  1545 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
07-27 15:04:52.136  1033  1545 D ConnectivityService: validation of new default Network = false
07-27 15:04:52.136  1033  1545 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
07-27 15:04:52.136  1033  1545 D DSQN    : enableDataServiceNotify 
07-27 15:04:52.136  1033  1545 D DSQN    : start dsqn bin
,07-27 15:04:52.139   309  8026 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
07-27 15:04:52.145  1033  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
07-27 15:04:52.145  1033  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 15:04:52.145  1033  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 15:04:52.145  1033  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 15:04:52.146  1033  1033 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
07-27 15:04:52.147  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-27 15:04:52.147  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-27 15:04:52.147  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-27 15:04:52.142  8027  8027 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,07-27 15:04:52.142  8027  8027 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 15:04:52.142  8027  8027 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 15:04:52.155  1604  2066 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-27 15:04:52.157  1033  1535 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
07-27 15:04:52.159  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 15:04:52.160  1604  1604 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
07-27 15:04:52.160  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 15:04:52.168  8027  8027 E DSQN    : DSQN ssw
,07-27 15:04:52.184   309  8026 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,07-27 15:04:52.184  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,07-27 15:04:52.184  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 15:04:52.185  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 15:04:52.217   309  8026 D libc-netbsd: res_queryN name = clients3.google.com succeed
,07-27 15:04:52.246  6632  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 15:04:52.246  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:52.246  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:52.246  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 15:04:52.246  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 15:04:52.246  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 15:04:52.246  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 15:04:52.246  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-27 15:04:52.247  6632  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 15:04:52.252  6632  6695 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
07-27 15:04:52.252   309   883 D LGDataListener: argv[0]=dsqncommand
07-27 15:04:52.252   309   883 D LGDataListener: argv[1]=wlan0
07-27 15:04:52.252   309   883 D LGDataListener: argv[2]=1
07-27 15:04:52.252   309   883 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
07-27 15:04:52.252  6632  6695 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
07-27 15:04:52.253  1033  1096 D DSQN    : DSQM DsqnNotification wlan0  1
07-27 15:04:52.253  1033  1096 D DSQN    : start to monitor internet connection
07-27 15:04:52.254  6632  6695 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@11e978c4 Bundle[{}]
07-27 15:04:52.255  6632  6695 I io.jxcore.node.LifeCycleMonitor: start: OK
07-27 15:04:52.255  6632  6695 I io.jxcore.node.LifeCycleMonitor: stop: OK
07-27 15:04:52.256  6632  6695 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
07-27 15:04:52.256  6632  6695 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-27 15:04:52.257  6632  6695 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
07-27 15:04:52.257  6632  6695 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
07-27 15:04:52.262  6632  6695 I System.out: Running OutgoingSocketThread
07-27 15:04:52.263  6632  8039 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 861)
07-27 15:04:52.264  6632  8039 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 37543
07-27 15:04:52.264  6632  8039 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,07-27 15:04:52.273  1033  8022 D DhcpStateMachine: DHCPV4 request on wlan0
07-27 15:04:52.274  1033  8022 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
07-27 15:04:52.275  1033  8022 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
07-27 15:04:52.272  8040  8040 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 15:04:52.272  8040  8040 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,07-27 15:04:52.284  1033  8021 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 27 Jul 2016 13:04:52 GMT], X-Android-Received-Millis=[1469624692284], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1469624692250]}
07-27 15:04:52.284  1033  8021 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
07-27 15:04:52.284  1033  8021 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
07-27 15:04:52.285  1033  1545 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
07-27 15:04:52.285  1033  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
07-27 15:04:52.285  1033  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 15:04:52.285  1033  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 15:04:52.285  1033  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
07-27 15:04:52.286  1033  1545 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
07-27 15:04:52.286  1033  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
07-27 15:04:52.286  1033  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 15:04:52.286  1033  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 15:04:52.286  8040  8040 I dhcpcd  : version 5.5.6 starting
07-27 15:04:52.287  1033  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 15:04:52.288  1604  2066 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-27 15:04:52.288  8040  8040 E dhcpcd  : get_duid: m
07-27 15:04:52.288  8040  8040 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
07-27 15:04:52.288  8040  8040 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
07-27 15:04:52.290  1033  1545 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 15:04:52.291  1853  1853 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 15:04:52.292  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-27 15:04:52.293  1033  1537 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 15:04:52.293  1033  1537 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 15:04:52.293  1033  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,07-27 15:04:52.314  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-27 15:04:52.315  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 15:04:52.316  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 15:04:52.351  8040  8040 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
07-27 15:04:52.352  8040  8040 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
07-27 15:04:52.352  8040  8040 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
07-27 15:04:52.352  8040  8040 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
,07-27 15:04:52.352  8040  8040 D dhcpcd  : wlan0: sending REQUEST (xid 0x53d246fd), next in 4.59 seconds
,07-27 15:04:52.405  8004  8004 W ExternalStrings: load override strings
07-27 15:04:52.405  8004  8004 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
07-27 15:04:52.405  8004  8004 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
07-27 15:04:52.405  8004  8004 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
07-27 15:04:52.405  8004  8004 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
07-27 15:04:52.405  8004  8004 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
07-27 15:04:52.405  8004  8004 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
07-27 15:04:52.405  8004  8004 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
07-27 15:04:52.405  8004  8004 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
07-27 15:04:52.405  8004  8004 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
07-27 15:04:52.405  8004  8004 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
07-27 15:04:52.405  8004  8004 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
07-27 15:04:52.405  8004  8004 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 15:04:52.405  8004  8004 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
07-27 15:04:52.405  8004  8004 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-27 15:04:52.405  8004  8004 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 15:04:52.405  8004  8004 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 15:04:52.405  8004  8004 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-27 15:04:52.405  8004  8004 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,07-27 15:04:52.407  8004  8004 D StatusProvider: onCreate
,07-27 15:04:52.415  8040  8040 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
07-27 15:04:52.447  8004  8004 V Signer  : override build config not found
07-27 15:04:52.447  8004  8004 D Signer  : value of property debug is false
,07-27 15:04:52.464  8040  8040 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
,07-27 15:04:52.464  8040  8040 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
,07-27 15:04:52.465  8040  8040 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
,07-27 15:04:52.465  8040  8040 D dhcpcd  : wlan0: adding default route via 192.168.1.1
07-27 15:04:52.466  8040  8040 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
07-27 15:04:52.466  8040  8040 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
07-27 15:04:52.467  8040  8040 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
07-27 15:04:52.467  8040  8040 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
07-27 15:04:52.509  8004  8004 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
07-27 15:04:52.510  8004  8004 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
07-27 15:04:52.510  8004  8004 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
07-27 15:04:52.511  8004  8004 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
07-27 15:04:52.511  8004  8004 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
07-27 15:04:52.511  8004  8004 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
07-27 15:04:52.511  8004  8004 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
07-27 15:04:52.512  8004  8004 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
07-27 15:04:52.512  8004  8004 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
07-27 15:04:52.512  8004  8004 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
07-27 15:04:52.513  8004  8004 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
07-27 15:04:52.513  8004  8004 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
07-27 15:04:52.513  8004  8004 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
,07-27 15:04:52.528  8004  8004 V LGMDMManager: Create singleton instance
07-27 15:04:52.586  8004  8004 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,07-27 15:04:52.624  8004  8004 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-27 15:04:52.632  6749  6749 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-27 15:04:52.635  6749  6749 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 15:04:52.635  8004  8062 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-27 15:04:52.678  1033  2007 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8069 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,07-27 15:04:52.681  1033  2007 I ActivityManager: Killing 7103:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
07-27 15:04:52.793  8004  8061 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,07-27 15:04:52.879  1033  8022 D DhcpStateMachine: DHCPV4 succeeded on wlan0
07-27 15:04:52.882  1033  8022 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
07-27 15:04:52.883  1033  8022 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
07-27 15:04:52.883  1033  8022 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
07-27 15:04:52.883  1033  8022 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
07-27 15:04:52.883  1033  8022 V DhcpStateMachine: Current State is mWaitBeforeStartState.
07-27 15:04:52.883  1033  8022 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
07-27 15:04:52.883  1033  8022 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
07-27 15:04:52.884  1033  8022 D DhcpStateMachine: RunningState
,07-27 15:04:52.925  1033  1576 W libprocessgroup: failed to open /acct/uid_10093/pid_7103/cgroup.procs: No such file or directory
,07-27 15:04:52.970  8069  8069 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,07-27 15:04:52.995  8069  8069 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,07-27 15:04:53.028  8069  8069 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
07-27 15:04:53.029  8069  8069 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
07-27 15:04:53.029  8069  8069 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
07-27 15:04:53.029  8069  8069 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
07-27 15:04:53.030  8069  8069 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
07-27 15:04:53.031  8069  8069 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,07-27 15:04:53.036  8069  8069 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
07-27 15:04:53.043  8069  8069 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 15:04:53.047  8069  8069 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-27 15:04:53.054  8004  8061 D LgDataFeature: LgDataFeature() Constructor: none
07-27 15:04:53.055  8004  8061 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-27 15:04:53.071  8069  8069 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,07-27 15:04:53.075  8069  8069 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
07-27 15:04:53.076  8004  8004 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 15:04:53.077  8004  8062 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-27 15:04:53.080  8069  8069 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
07-27 15:04:53.083  6749  6749 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 15:04:53.089  6749  6749 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-27 15:04:53.095  8069  8069 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 15:04:53.095  8069  8069 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 15:04:53.097  8069  8069 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,07-27 15:04:53.100  6749  6749 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
07-27 15:04:53.103  6749  6749 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
07-27 15:04:53.106  8004  8004 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 15:04:53.106  8004  8062 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-27 15:04:53.115  6749  6749 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 15:04:53.120  6749  6749 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 15:04:53.126  8069  8069 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 15:04:53.126  8069  8069 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 15:04:53.127  8069  8069 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,07-27 15:04:53.129  6749  6749 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-27 15:04:53.129  6749  6749 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-27 15:04:53.129  6749  6749 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-27 15:04:53.129  6749  6749 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-27 15:04:53.130  6749  6749 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-27 15:04:53.135  6749  6749 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-27 15:04:53.135  6749  6749 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
07-27 15:04:53.135  6749  6749 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-27 15:04:53.135  6749  6749 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-27 15:04:53.135  6749  6749 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-27 15:04:53.135  6749  6749 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
07-27 15:04:53.135  6749  6749 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-27 15:04:53.138  8004  8004 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 15:04:53.139  8004  8062 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,07-27 15:04:53.150  6749  6749 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 15:04:53.165  6749  6749 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-27 15:04:53.176  8069  8069 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 15:04:53.176  8069  8069 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 15:04:53.176  8069  8069 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-27 15:04:53.180  8004  8004 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 15:04:53.180  8004  8062 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,07-27 15:04:53.189  6749  6749 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 15:04:53.200  6749  6749 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-27 15:04:53.205  8004  8061 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
07-27 15:04:53.206  8069  8069 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 15:04:53.206  8069  8069 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-27 15:04:53.207  8069  8069 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-27 15:04:53.210  8004  8004 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 15:04:53.211  8004  8062 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-27 15:04:53.217  6749  6749 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 15:04:53.225  6749  6749 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 15:04:53.231  8069  8069 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 15:04:53.231  8069  8069 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 15:04:53.232  8069  8069 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-27 15:04:53.234  8004  8004 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 15:04:53.235  8004  8062 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,07-27 15:04:53.238  8004  8061 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
07-27 15:04:53.245  6749  6749 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 15:04:53.248  8004  8061 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported,
07-27 15:04:53.249  8004  8061 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
07-27 15:04:53.249  8004  8061 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
07-27 15:04:53.250  8004  8061 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
07-27 15:04:53.250  8004  8061 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
07-27 15:04:53.254  6749  6749 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 15:04:53.255  8004  8061 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
07-27 15:04:53.257  8004  8061 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
07-27 15:04:53.260  8069  8069 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 15:04:53.261  8069  8069 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 15:04:53.261  8069  8069 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,07-27 15:04:53.263  6632  6695 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 862)
07-27 15:04:53.263  6632  6695 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 862)
07-27 15:04:53.263  6632  6695 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 862)
07-27 15:04:53.263  6632  6695 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 862)
07-27 15:04:53.268  6632  6695 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 867)
07-27 15:04:53.268  6632  6695 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Nothing to close (thread ID: 867)
07-27 15:04:53.268  6632  6695 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 867)
07-27 15:04:53.269  6632  6695 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Closing... (thread ID: 868)
07-27 15:04:53.271  6632  6695 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 870)
07-27 15:04:53.272  8004  8004 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 15:04:53.272  8004  8062 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-27 15:04:53.274  6632  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 15:04:53.274  6632  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ffcd1c added. We now have 2 listener(s)
,07-27 15:04:53.279  1033  2015 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 15:04:53.282  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-27 15:04:53.282  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 15:04:53.282  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 15:04:53.282  6632  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 15:04:53.282  6632  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18110d25 added. We now have 9 listener(s)
07-27 15:04:53.282  6632  6695 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 15:04:53.283  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-27 15:04:53.285  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 15:04:53.288  6632  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 15:04:53.288  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:53.288  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:53.288  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 15:04:53.288  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 15:04:53.288  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 15:04:53.288  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 15:04:53.288  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-27 15:04:53.292  6749  6749 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-27 15:04:53.294  6632  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 15:04:53.294  6632  6695 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 15:04:53.294  6632  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 15:04:53.295  6632  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@102cbcab added. We now have 3 listener(s)
07-27 15:04:53.295  1033  1927 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 15:04:53.297  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:53.299  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 15:04:53.300  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-27 15:04:53.300  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 15:04:53.300  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 15:04:53.300  6632  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 15:04:53.300  6632  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bca9f08 added. We now have 10 listener(s)
07-27 15:04:53.301  6632  6695 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 15:04:53.301  6632  6695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 15:04:53.301  6632  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 15:04:53.301  6632  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 15:04:53.301  6632  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:53.302  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:53.302  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 15:04:53.302  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 15:04:53.302  6632  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ffcd1c removed from the list
07-27 15:04:53.302  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:53.302  6632  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18110d25 removed from the list
07-27 15:04:53.302  6632  6695 D io.jxcore.node.ConnectivityMonitor: stop
07-27 15:04:53.302  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:53.303  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:53.303  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:53.303  6749  6749 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 15:04:53.305  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:53.305  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:53.305  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:53.305  6632  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18110d25 not in the list
07-27 15:04:53.305  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:53.305  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Bluetoo,thManager: release: 1 listener(s) left
07-27 15:04:53.306  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:53.306  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:53.306  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:53.306  6632  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bca9f08 removed from the list
07-27 15:04:53.306  6632  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:53.306  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:53.306  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:53.306  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 15:04:53.306  6632  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@102cbcab removed from the list
07-27 15:04:53.307  6632  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 15:04:53.307  6632  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19ea56a1 added. We now have 2 listener(s)
07-27 15:04:53.307  1033  2007 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 15:04:53.310  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-27 15:04:53.310  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 15:04:53.310  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 15:04:53.310  6632  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 15:04:53.310  6632  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10b220c6 added. We now have 9 listener(s)
07-27 15:04:53.310  6632  6695 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 15:04:53.314  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-27 15:04:53.316  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-27 15:04:53.318  8069  8069 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 15:04:53.321  8069  8069 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 15:04:53.322  6632  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 15:04:53.322  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:53.322  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:53.322  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 15:04:53.322  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 15:04:53.322  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 15:04:53.322  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 15:04:53.322  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 15:04:53.324  6632  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 15:04:53.324  6632  6695 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 15:04:53.325  6632  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 15:04:53.325  6632  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1deea3b4 added. We now have 3 listener(s)
07-27 15:04:53.325  1033  1927 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 15:04:53.328  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-27 15:04:53.328  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 15:04:53.328  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 15:04:53.328  6632  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 15:04:53.328  6632  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5b4bbdd added. We now have 10 listener(s)
07-27 15:04:53.328  6632  6695 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 15:04:53.328  6632  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 15:04:53.328  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-27 15:04:53.328  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 15:04:53.328  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-27 15:04:53.331  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:53.332  6632  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-27 15:04:53.332  1033  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 15:04:53.334  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:53.338  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-27 15:04:53.338  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-27 15:04:53.340  8069  8069 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-27 15:04:53.340  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-27 15:04:53.340  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 15:04:53.343  6632  6695 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-27 15:04:53.343  6632  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 15:04:53.343  6632  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 15:04:53.346  6632  6695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 15:04:53.346  6632  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 15:04:53.346  6632  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 15:04:53.346  6632  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:53.346  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:53.346  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 15:04:53.346  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 15:04:53.346  6632  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19ea56a1 removed from the list
07-27 15:04:53.346  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:53.347  6632  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10b220c6 removed from the list
07-27 15:04:53.347  6632  6695 D io.jxcore.node.ConnectivityMonitor: stop
07-27 15:04:53.347  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:53.347  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:53.347  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:53.348  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:53.348  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:53.348  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:53.348  6632  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10b220c6 not in the list
07-27 15:04:53.348  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:53.348  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:53.349  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:53.350  8004  8004 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 15:04:53.351  8004  8062 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrap,per.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,07-27 15:04:53.352  6632  6695 D BluetoothLeScanner: could not find callback wrapper
07-27 15:04:53.352  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 15:04:53.352  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:53.353  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:53.353  6632  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5b4bbdd removed from the list
07-27 15:04:53.353  6632  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:53.353  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:53.353  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:53.353  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 15:04:53.353  6632  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1deea3b4 removed from the list
07-27 15:04:53.354  6632  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 15:04:53.354  6632  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24ac4720 added. We now have 2 listener(s)
07-27 15:04:53.354  1033  1973 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 15:04:53.359  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-27 15:04:53.359  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 15:04:53.359  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 15:04:53.360  6632  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 15:04:53.360  6632  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dc638d9 added. We now have 9 listener(s)
07-27 15:04:53.360  6632  6695 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 15:04:53.361  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-27 15:04:53.361  6749  6749 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-27 15:04:53.364  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-27 15:04:53.369  6632  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 15:04:53.369  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:53.369  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:53.369  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 15:04:53.369  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 15:04:53.369  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 15:04:53.369  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 15:04:53.369  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-27 15:04:53.371  6749  6749 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 15:04:53.371  6632  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 15:04:53.371  6632  6695 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 15:04:53.372  6632  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 15:04:53.372  6632  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13adf17f added. We now have 3 listener(s)
07-27 15:04:53.375  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:53.378  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:53.380  1033  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-27 15:04:53.387  8069  8069 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 15:04:53.387  8069  8069 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 15:04:53.387  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-27 15:04:53.387  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 15:04:53.387  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 15:04:53.388  6632  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 15:04:53.388  6632  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27deb54c added. We now have 10 listener(s)
07-27 15:04:53.388  8069  8069 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-27 15:04:53.388  6632  6695 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 15:04:53.388  6632  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 15:04:53.390  6632  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 15:04:53.390  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-27 15:04:53.390  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 15:04:53.390  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-27 15:04:53.392  8004  8004 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 15:04:53.393  8004  8062 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,07-27 15:04:53.398  6632  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-27 15:04:53.398  1033  1927 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 15:04:53.403  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-27 15:04:53.405  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-27 15:04:53.405  7957  7957 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
07-27 15:04:53.406  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-27 15:04:53.407  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 15:04:53.408  6632  6695 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-27 15:04:53.408  7957  7957 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
07-27 15:04:53.409  6632  6695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 15:04:53.409  6632  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 15:04:53.409  6632  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 15:04:53.409  6632  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:53.409  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:53.409  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 15:04:53.409  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 15:04:53.409  6632  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24ac4720 removed from the list
07-27 15:04:53.409  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:53.409  6632  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dc638d9 removed from the list
07-27 15:04:53.409  6632  6695 D io.jxcore.node.ConnectivityMonitor: stop
07-27 15:04:53.409  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:53.412  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:53.412  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 15:04:53.413  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-27 15:04:53.413  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:53.413  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:53.413  6632  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dc638d9 not in the list
07-27 15:04:53.413  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:53.413  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:53.414  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:53.415  6749  6749 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-27 15:04:53.415  6632  6695 D BluetoothLeScanner: could not find callback wrapper
07-27 15:04:53.415  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 15:04:53.415  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:53.415  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:53.415  6632  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27deb54c removed from the list
07-27 15:04:53.415  6632  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:53.415  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:53.415  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:53.415  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 15:04:53.415  6632  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13adf17f removed from the list
07-27 15:04:53.416  6632  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 15:04:53.416  6632  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2aba269b added. We now have 2 listener(s)
07-27 15:04:53.416  1033  2007 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 15:04:53.419  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-27 15:04:53.419  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 15:04:53.419  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 15:04:53.419  6632  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 15:04:53.419  6632  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fe7da38 added. We now have 9 listener(s)
07-27 15:04:53.419  6632  6695 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 15:04:53.419  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-27 15:04:53.421  6749  6749 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 15:04:53.421  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 15:04:53.429  6632  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 15:04:53.429  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:53.429  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:53.429  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 15:04:53.429  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 15:04:53.429  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 15:04:53.429  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 15:04:53.429  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-27 15:04:53.430  8069  8069 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-27 15:04:53.430  8069  8069 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 15:04:53.430  6632  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 15:04:53.431  6632  6695 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 15:04:53.431  6632  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 15:04:53.431  6632  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2aaa4776 added. We now have 3 listener(s)
07-27 15:04:53.431  1033  1980 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 15:04:53.432  8069  8069 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
07-27 15:04:53.433  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:53.433  8069  8069 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
07-27 15:04:53.434  8069  8069 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
07-27 15:04:53.435  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-27 15:04:53.435  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 15:04:53.435  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 15:04:53.435  6632  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 15:04:53.435  6632  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78a9177 added. We now have 10 listener(s)
07-27 15:04:53.435  6632  6695 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 15:04:53.435  6632  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 15:04:53.435  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-27 15:04:53.435  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 15:04:53.435  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-27 15:04:53.436  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:53.439  8004  8004 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 15:04:53.439  6632  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-27 15:04:53.439  1033  2015 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 15:04:53.442  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-27 15:04:53.443  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-27 15:04:53.444  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-27 15:04:53.445  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 15:04:53.446  6632  6695 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-27 15:04:53.448  6632  6695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 15:04:53.448  6632  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 15:04:53.448  6632  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 15:04:53.448  6632  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:53.448  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:53.448  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 15:04:53.448  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 15:04:53.448  6632  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2aba269b removed from the list
07-27 15:04:53.448  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:53.448  6632  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fe7da38 removed from the list
07-27 15:04:53.448  6632  6695 D io.jxcore.node.ConnectivityMonitor: stop
07-27 15:04:53.448  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:53.449  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:53.449  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:53.449  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:53.449  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:53.449  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:53.450  6632  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fe7da38 not in the list
07-27 15:04:53.450  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:53.450  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:53.450  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:53.451  6632  6695 D BluetoothLeScanner: could not find callback wrapper
07-27 15:04:53.451  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 15:04:53.451  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:53.451  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:53.451  6632  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78a9177 removed from the list
,07-27 15:04:53.451  6632  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:53.451  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:53.451  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:53.451  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 15:04:53.451  6632  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2aaa4776 removed from the list
07-27 15:04:53.452  6632  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 15:04:53.452  6632  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5eb6502 added. We now have 2 listener(s)
07-27 15:04:53.452  1033  1889 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 15:04:53.455  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-27 15:04:53.455  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 15:04:53.455  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 15:04:53.455  6632  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 15:04:53.455  6632  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f8cce13 added. We now have 9 listener(s)
07-27 15:04:53.455  6632  6695 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 15:04:53.456  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-27 15:04:53.458  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-27 15:04:53.461  6632  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 15:04:53.461  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 15:04:53.461  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 15:04:53.461  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 15:04:53.461  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 15:04:53.461  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 15:04:53.461  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 15:04:53.461  6632  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 15:04:53.463  6632  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 15:04:53.464  6632  6695 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 15:04:53.464  6632  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 15:04:53.464  6632  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@69a0a49 added. We now have 3 listener(s)
07-27 15:04:53.464  1033  1888 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 15:04:53.465  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:53.467  6632  6632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 15:04:53.468  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-27 15:04:53.468  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 15:04:53.468  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 15:04:53.468  6632  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 15:04:53.469  6632  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c2ecf4e added. We now have 10 listener(s)
07-27 15:04:53.469  6632  6695 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 15:04:53.469  6632  6695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 15:04:53.469  6632  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 15:04:53.469  6632  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 15:04:53.470  6632  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:53.470  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:53.470  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 15:04:53.470  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 15:04:53.470  6632  6695 V org.,thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5eb6502 removed from the list
,07-27 15:04:53.470  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:53.470  6632  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f8cce13 removed from the list
07-27 15:04:53.470  6632  6695 D io.jxcore.node.ConnectivityMonitor: stop
07-27 15:04:53.470  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:53.472  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:53.472  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:53.473  7957  7957 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
07-27 15:04:53.473  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:53.473  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:53.473  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:53.473  6632  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f8cce13 not in the list
07-27 15:04:53.473  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:53.473  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:53.474  7957  7957 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
07-27 15:04:53.475  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 15:04:53.475  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 15:04:53.475  6632  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 15:04:53.475  6632  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c2ecf4e removed from the list
07-27 15:04:53.475  6632  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 15:04:53.475  6632  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 15:04:53.475  6632  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 15:04:53.475  6632  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 15:04:53.475  6632  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@69a0a49 removed from the list
07-27 15:04:53.476  6632  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-27 15:04:53.477  6632  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
07-27 15:04:53.477  6632  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-27 15:04:53.477  6632  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
07-27 15:04:53.477  6749  6749, V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-27 15:04:53.477  6632  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
07-27 15:04:53.477  6632  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,07-27 15:04:53.483  6749  6749 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 15:04:53.487  6632  8124 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 876, name: My test thread name)
07-27 15:04:53.487  6632  8124 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 876, thread name: My test thread name)
07-27 15:04:53.488  6632  8124 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 876, name: My test thread name)
07-27 15:04:53.489  8069  8069 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 15:04:53.490  8069  8069 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 15:04:53.490  6632  8125 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 878, name: My test thread name)
07-27 15:04:53.491  6632  8125 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 878, thread name: My test thread name)
07-27 15:04:53.491  8069  8069 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
07-27 15:04:53.491  6632  8125 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 878, name: My test thread name)
07-27 15:04:53.491  8069  8069 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
07-27 15:04:53.491  8069  8069 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
07-27 15:04:53.495  8004  8004 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 15:04:53.495  6632  6695 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
07-27 15:04:53.495  6632  6695 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
07-27 15:04:53.495  6632  6695 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
07-27 15:04:53.495  6632  6695 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
,07-27 15:04:53.495  6632  6695 D com.test.thalitest.ThaliTestRunner: Total duration: 23973 ms
,07-27 15:04:53.497  6632  6695 I jxcore-log: Total number of executed tests:  80
07-27 15:04:53.497  6632  6695 I jxcore-log: 
07-27 15:04:53.497  6632  6695 I jxcore-log: Number of passed tests:  80
07-27 15:04:53.497  6632  6695 I jxcore-log: 
07-27 15:04:53.497  6632  6695 I jxcore-log: Number of failed tests:  0
07-27 15:04:53.497  6632  6695 I jxcore-log: 
07-27 15:04:53.497  6632  6695 I jxcore-log: Number of ignored tests:  0
07-27 15:04:53.497  6632  6695 I jxcore-log: 
07-27 15:04:53.498  6632  6695 I jxcore-log: Total duration:  23973
07-27 15:04:53.498  6632  6695 I jxcore-log: 
07-27 15:04:53.498  6632  6695 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
07-27 15:04:53.498  6632  6695 I jxcore-log: 
07-27 15:04:53.501  8069  8069 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
07-27 15:04:53.501  6632  6695 I jxcore-log: Unit Test app is loaded
07-27 15:04:53.501  6632  6695 I jxcore-log: 
07-27 15:04:53.502  8069  8069 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
07-27 15:04:53.502  8069  8069 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
07-27 15:04:53.507  6632  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 15:04:53.507  6632  6695 I jxcore-log: 
07-27 15:04:53.512  6632  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 15:04:53.512  6632  6695 I jxcore-log: 
07-27 15:04:53.513  6632  6632 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
07-27 15:04:53.514  6632  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 15:04:53.514  6632  6695 I jxcore-log: 
,07-27 15:04:53.515  6632  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 15:04:53.515  6632  6695 I jxcore-log: 
07-27 15:04:53.516  6632  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 15:04:53.516  6632  6695 I jxcore-log: 
07-27 15:04:53.518  6632  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
07-27 15:04:53.518  6632  6695 I jxcore-log: 
07-27 15:04:53.521  6632  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-27 15:04:53.521  6632  6695 I jxcore-log: 
07-27 15:04:53.523  6632  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 15:04:53.523  6632  6695 I jxcore-log: 
07-27 15:04:53.524  6632  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-27 15:04:53.524  6632  6695 I jxcore-log: 
07-27 15:04:53.525  6632  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-27 15:04:53.525  6632  6695 I jxcore-log: 
,07-27 15:04:53.526  6632  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-27 15:04:53.526  6632  6695 I jxcore-log: 
07-27 15:04:53.526  6632  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-27 15:04:53.526  6632  6695 I jxcore-log: 
07-27 15:04:53.528  6632  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-27 15:04:53.528  6632  6695 I jxcore-log: 
07-27 15:04:53.529  6632  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-27 15:04:53.529  6632  6695 I jxcore-log: 
07-27 15:04:53.530  6632  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-27 15:04:53.530  6632  6695 I jxcore-log: 
07-27 15:04:53.530  6632  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-27 15:04:53.530  6632  6695 I jxcore-log: 
07-27 15:04:53.531  6632  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-27 15:04:53.531  6632  6695 I jxcore-log: 
07-27 15:04:53.532  6632  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-27 15:04:53.532  6632  6695 I jxcore-log: 
07-27 15:04:53.533  6632  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-27 15:04:53.533  6632  6695 I jxcore-log: 
07-27 15:04:53.533  6632  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-27 15:04:53.533  6632  6695 I jxcore-log: 
07-27 15:04:53.534  6632  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-27 15:04:53.534  6632  6695 I jxcore-log: 
07-27 15:04:53.535  6632  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-27 15:04:53.535  6632  6695 I jxcore-log: 
07-27 15:04:53.536  6632  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-27 15:04:53.536  6632  6695 I jxcore-log: 
07-27 15:04:53.536  6632  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 15:04:53.536  6632  6695 I jxcore-log: 
,07-27 15:04:53.537  6632  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 15:04:53.537  6632  6695 I jxcore-log: 
07-27 15:04:53.538  6632  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 15:04:53.538  6632  6695 I jxcore-log: 
07-27 15:04:53.539  6632  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 15:04:53.539  6632  6695 I jxcore-log: 
07-27 15:04:53.540  6632  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 15:04:53.540  6632  6695 I jxcore-log: 
07-27 15:04:53.541  6632  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
,07-27 15:04:53.541  6632  6695 I jxcore-log: 
07-27 15:04:53.543  8069  8069 D LgDataFeature: LgDataFeature() Constructor: none
07-27 15:04:53.544  8069  8069 D LgDataFeature: LgDataFeature() Constructor Done, null
07-27 15:04:53.544  6632  6695 I jxcore-log: My device name is: LGE-LG-D855
07-27 15:04:53.544  6632  6695 I jxcore-log: 
07-27 15:04:53.545  6632  6695 I jxcore-log: WARN testUtils: myNameCallback not set!
07-27 15:04:53.545  6632  6695 I jxcore-log: 
07-27 15:04:53.550  8069  8069 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,07-27 15:04:53.555  8069  8069 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
07-27 15:04:53.555  8069  8069 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
07-27 15:04:53.555  8069  8069 V SoundPool: doLoad: loading sample sampleID=1
07-27 15:04:53.555  8069  8128 V SoundPool: Start decode
07-27 15:04:53.555  8069  8128 V MediaPlayer[Native]: decode(31, 10857164, 17813)
07-27 15:04:53.556  8069  8069 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
07-27 15:04:53.557   315   315 V MediaPlayerService: decode(23, 10857164, 17813)
07-27 15:04:53.557   315   315 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
07-27 15:04:53.557   315   315 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
07-27 15:04:53.558   315   315 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
07-27 15:04:53.558   315   315 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
07-27 15:04:53.558   315   315 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
07-27 15:04:53.558   315   315 V MediaPlayerService: player type = 3
07-27 15:04:53.558   315   315 V AwesomePlayer: AwesomePlayer create()
07-27 15:04:53.559  7508  7508 D UEI.SmartControl: QS Service created
07-27 15:04:53.559   315   315 V AwesomePlayer: reset_l() 
07-27 15:04:53.559   315   315 V AwesomePlayer: cancelPlayerEvents
07-27 15:04:53.559   315   315 V AwesomePlayer: setAudioSink() 
07-27 15:04:53.559   315   315 V AwesomePlayer: reset_l() 
07-27 15:04:53.559   315   315 V AudioCache: notify(0xb5474600, 8, 0, 0)
07-27 15:04:53.559   315   315 V AudioCache: ignored
07-27 15:04:53.559   315   315 V AwesomePlayer: cancelPlayerEvents
07-27 15:04:53.560   315   315 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
07-27 15:04:53.560   315   315 V AwesomePlayer: setDataSource_l dataSource
07-27 15:04:53.560   315   315 V LGParserOSAL: SniffLGParser start
07-27 15:04:53.560   315   315 V LGParserOSAL: MainType:5, SubType=0
07-27 15:04:53.560   315   315 V LGParserOSAL: #### check Mime : application/ogg
07-27 15:04:53.560   315   315 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
07-27 15:04:53.560   315   315 E MediaExtractor: Use LGExtractor :application/ogg 
07-27 15:04:53.562  8069  8069 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
07-27 15:04:53.565  8069  8069 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,07-27 15:04:53.565  8069  8069 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
07-27 15:04:53.570  7508  7508 I UEI.SmartControl: Service initServices...
07-27 15:04:53.570  7508  7508 D UEI.SmartControl: QS start get config
07-27 15:04:53.591  8069  8069 V LGMDMManager: Create singleton instance
07-27 15:04:53.641   315   315 V LGParserOSAL: supported mime: application/ogg
07-27 15:04:53.641   315   315 V AwesomePlayer: setDataSource_l() extractor countTracks=1
07-27 15:04:53.641   315   315 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
07-27 15:04:53.641   315   315 V AwesomePlayer: mBitrate = -1 bits/sec
07-27 15:04:53.641   315   315 V AwesomePlayer: AudioTrack Setting
07-27 15:04:53.641   315   315 V AwesomePlayer: AudioTrack Setting channelCount = 2
07-27 15:04:53.641   315   315 V AwesomePlayer: setAudioSource() 
07-27 15:04:53.641   315   315 V MediaPlayerService: prepare
07-27 15:04:53.641   315   315 V AwesomePlayer: prepareAsync_l() 
07-27 15:04:53.641   315   315 V MediaPlayerService: wait for prepare
07-27 15:04:53.642   315  8131 V AwesomePlayer: onPrepareAsyncEvent() 
07-27 15:04:53.643   315  8131 V AwesomePlayer: initAudioDecoder() 
07-27 15:04:53.643   315  8131 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
07-27 15:04:53.643   315  8131 V AudioSystem: isOffloadSupported()
07-27 15:04:53.643   315  8131 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
07-27 15:04:53.643   315  8131 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
07-27 15:04:53.643   315  8131 I AudioFlinger: isAudioPlaybackHookOn() false
07-27 15:04:53.643   315  8131 V AwesomePlayer: getUseOffload() = 0 
07-27 15:04:53.643   315  8131 V OMXCodec: OMXCodec::Create
07-27 15:04:53.643   315  8131 V OMXCodec: findMatchingCodecs()
07-27 15:04:53.643   315  8131 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
07-27 15:04:53.643   315  8131 V OMXCodec: matchingCodecs.size()=1
07-27 15:04:53.643   315  8131 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
07-27 15:04:53.645   315  8131 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
07-27 15:04:53.645   315  8131 V LGCodecAdapter: LG Codec Adapter start
07-27 15:04:53.645   315  8131 V OMXCodec: OMXCodec Createtor
07-27 15:04:53.645   315  8131 V OMXCodec: setComponentRole
07-27 15:04:53.645   315  8131 V OMXCodec: configureCodec protected=0
07-27 15:04:53.645   315  8131 V LGCodecAdapter: called getLGCodecSpecificData
07-27 15:04:53.645   315  8131 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
07-27 15:04:53.645   315  8131 V LGCodecOSAL: Called LGconfigureCodecMETA
07-27 15:04:53.645   315  8131 V LGCodecOSAL: Called LGconfigureCodecMSG
07-27 15:04:53.645   315  8131 V LGCodecOSAL: Not support LGCodec
07-27 15:04:53.645   315  8131 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
07-27 15:04:53.645   315  8131 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
07-27 15:04:53.645   315  8131 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
07-27 15:04:53.645   315  8131 I AwesomePlayer: Could not offload audio decode, try pcm offload
07-27 15:04:53.645   315  8131 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
07-27 15:04:53.645   315  8131 V AudioSystem: isOffloadSupported()
07-27 15:04:53.645   315  8131 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068,125 us, has_video=0
07-27 15:04:53.645   315  8131 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
07-27 15:04:53.645   315  8131 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
07-27 15:04:53.645   315  8131 V OMXCodec: init()
07-27 15:04:53.645   315  8131 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
07-27 15:04:53.645   315  8131 V OMXCodec: allocateBuffers
07-27 15:04:53.645   315  8131 V OMXCodec: allocateBuffersOnPort portIndex=0
07-27 15:04:53.645   315  8131 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,07-27 15:04:53.646   315  8131 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7650 on input port
07-27 15:04:53.646   315  8131 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f77e0 on input port
07-27 15:04:53.646   315  8131 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f78d0 on input port
07-27 15:04:53.646   315  8131 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on input port
07-27 15:04:53.646   315  8131 V OMXCodec: allocateBuffersOnPort portIndex=1
07-27 15:04:53.646   315  8131 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
07-27 15:04:53.646   315  8131 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on output port
07-27 15:04:53.646   315  8131 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
07-27 15:04:53.646   315  8131 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
07-27 15:04:53.646   315  8131 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
07-27 15:04:53.646   315  8131 V OMXCodec: init() mAsyncCompletion wait!!! 
07-27 15:04:53.657   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
07-27 15:04:53.657   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
07-27 15:04:53.657   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
07-27 15:04:53.657   315  8131 V OMXCodec: init() mAsyncCompletion wait!!! 
07-27 15:04:53.657   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
07-27 15:04:53.657   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
07-27 15:04:53.657   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
07-27 15:04:53.657   315  8131 V OMXCodec: init() mAsyncCompletion wait free! 
07-27 15:04:53.657   315  8131 V AwesomePlayer: finishAsyncPrepare_l() 
07-27 15:04:53.657   315  8131 V AudioCache: notify(0xb5474600, 5, 0, 0)
07-27 15:04:53.657   315  8131 V AudioCache: ignored
07-27 15:04:53.657   315  8131 V AudioCache: notify(0xb5474600, 1, 0, 0)
07-27 15:04:53.657   315  8131 V AudioCache: prepared
07-27 15:04:53.657   315   315 V AudioCache: wait - success
07-27 15:04:53.657   315   315 V MediaPlayerService: start
07-27 15:04:53.657   315   315 V AwesomePlayer: play_l() 
07-27 15:04:53.657   315   315 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
07-27 15:04:53.657   315   315 V AwesomePlayer: createAudioPlayer_l
07-27 15:04:53.657   315   315 V AwesomePlayer: seekAudioIfNecessary_l() 
07-27 15:04:53.657   315   315 V AwesomePlayer: startAudioPlayer_l() 
07-27 15:04:53.657   315   315 D AudioPlayer: start of Playback, useOffload 0
07-27 15:04:53.657   315   315 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
07-27 15:04:53.657   315   315 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
07-27 15:04:53.659   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
07-27 15:04:53.659   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
07-27 15:04:53.659   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
07-27 15:04:53.659   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
07-27 15:04:53.659   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
07-27 15:04:53.659   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
07-27 15:04:53.659   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884528
07-27 15:04:53.659   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-27 15:04:53.659   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884688
07-27 15:04:53.659   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bu,fIndex=0
07-27 15:04:53.659   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884768
07-27 15:04:53.659   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-27 15:04:53.659   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885008
07-27 15:04:53.659   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-27 15:04:53.659   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
07-27 15:04:53.659   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
07-27 15:04:53.659   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
07-27 15:04:53.659   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
07-27 15:04:53.659   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
07-27 15:04:53.659   315  8133 V OMXCodec: allocateBuffersOnPort portIndex=1
07-27 15:04:53.659   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
07-27 15:04:53.659   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
07-27 15:04:53.659   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
07-27 15:04:53.659   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on output port
07-27 15:04:53.659   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bc470 on output port
07-27 15:04:53.659   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
07-27 15:04:53.659   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
07-27 15:04:53.660   315   315 V AudioCache: open(48000, 2, 0x0, 1, 4)
07-27 15:04:53.660   315   315 V AudioCache: notify(0xb5474600, 6, 0, 0)
07-27 15:04:53.660   315   315 V AudioCache: ignored
07-27 15:04:53.661   315   315 V MediaPlayerService: wait for playback complete
07-27 15:04:53.661   315  8134 V AudioCache: write(0xb16f6000, 4096)
07-27 15:04:53.661   315  8134 V AudioCache: memcpy(0xabf08000, 0xb16f6000, 4096)
07-27 15:04:53.662   315  8134 V AudioCache: write(0xb16f6000, 4096)
07-27 15:04:53.662   315  8134 V AudioCache: memcpy(0xabf09000, 0xb16f6000, 4096)
07-27 15:04:53.662   315  8134 V AudioCache: write(0xb16f6000, 4096)
07-27 15:04:53.662   315  8134 V AudioCache: memcpy(0xabf0a000, 0xb16f6000, 4096)
07-27 15:04:53.663   315  8134 V AudioCache: write(0xb16f6000, 4096)
07-27 15:04:53.663   315  8134 V AudioCache: memcpy(0xabf0b000, 0xb16f6000, 4096)
,07-27 15:04:53.664   315  8134 V AudioCache: write(0xb16f6000, 4096)
07-27 15:04:53.664   315  8134 V AudioCache: memcpy(0xabf0c000, 0xb16f6000, 4096)
07-27 15:04:53.664   315  8134 V AudioCache: write(0xb16f6000, 4096)
07-27 15:04:53.664   315  8134 V AudioCache: memcpy(0xabf0d000, 0xb16f6000, 4096)
07-27 15:04:53.665   315  8134 V AudioCache: write(0xb16f6000, 4096)
07-27 15:04:53.665   315  8134 V AudioCache: memcpy(0xabf0e000, 0xb16f6000, 4096)
07-27 15:04:53.665   315  8134 V AudioCache: write(0xb16f6000, 4096)
07-27 15:04:53.665   315  8134 V AudioCache: memcpy(0xabf0f000, 0xb16f6000, 4096)
07-27 15:04:53.665   315  8134 V AudioCache: write(0xb16f6000, 4096)
07-27 15:04:53.665   315  8134 V AudioCache: memcpy(0xabf10000, 0xb16f6000, 4096)
07-27 15:04:53.665   315  8134 V AudioCache: write(0xb16f6000, 4096)
07-27 15:04:53.665   315  8134 V AudioCache: memcpy(0xabf11000, 0xb16f6000, 4096)
07-27 15:04:53.666   315  8134 V AudioCache: write(0xb16f6000, 4096)
07-27 15:04:53.666   315  8134 V AudioCache: memcpy(0xabf12000, 0xb16f6000, 4096)
07-27 15:04:53.666   315  8134 V AudioCache: write(0xb16f6000, 4096)
07-27 15:04:53.666   315  8134 V AudioCache: memcpy(0xabf13000, 0xb16f6000, 4096)
07-27 15:04:53.666   315  8134 V AudioCache: write(0xb16f6000, 4096)
07-27 15:04:53.666   315  8134 V AudioCache: memcpy(0xabf14000, 0xb16f6000, 4096)
07-27 15:04:53.667   315  8134 V AudioCache: write(0xb16f6000, 4096)
07-27 15:04:53.667   315  8134 V AudioCache: memcpy(0xabf15000, 0xb16f6000, 4096)
07-27 15:04:53.667   315  8134 V AudioCache: write(0xb16f6000, 4096)
07-27 15:04:53.667   315  8134 V AudioCache: memcpy(0xabf16000, 0xb16f6000, 4096)
07-27 15:04:53.667   315  8134 V AudioCache: write(0xb16f6000, 4096)
07-27 15:04:53.667   315  8134 V AudioCache: memcpy(0xabf17000, 0xb16f6000, 4096)
07-27 15:04:53.668   315  8134 V AudioCache: write(0xb16f6000, 4096)
07-27 15:04:53.668   315  8134 V AudioCache: memcpy(0xabf18000, 0xb16f6000, 4096)
07-27 15:04:53.668   315  8134 V AudioCache: write(0xb16f6000, 4096)
07-27 15:04:53.668   315  8134 V AudioCache: memcpy(0xabf19000, 0xb16f6000, 4096)
07-27 15:04:53.668   315  8134 V AudioCache: write(0xb16f6000, 4096)
07-27 15:04:53.669   315  8134 V AudioCache: memcpy(0xabf1a000, 0xb16f6000, 4096)
07-27 15:04:53.669   315  8134 V AudioCache: write(0xb16f6000, 4096)
07-27 15:04:53.669   315  8134 V AudioCache: memcpy(0xabf1b000, 0xb16f6000, 4096)
07-27 15:04:53.669   315  8134 V AudioCache: write(0xb16f6000, 4096)
07-27 15:04:53.669   315  8134 V AudioCache: memcpy(0xabf1c000, 0xb16f6000, 4096)
07-27 15:04:53.670   315  8134 V AudioCache: write(0xb16f6000, 4096)
07-27 15:04:53.670   315  8134 V AudioCache: memcpy(0xabf1d000, 0xb16f6000, 4096)
07-27 15:04:53.670   315  8134 V AudioCache: write(0xb16f6000, 4096)
07-27 15:04:53.670   315  8134 V AudioCache: memcpy(0xabf1e000, 0xb16f6000, 4096)
07-27 15:04:53.671   315  8134 V AudioCache: write(0xb16f6000, 4096)
07-27 15:04:53.671   315  8134 V AudioCache: memcpy(0xabf1f000, 0xb16f6000, 4096)
07-27 15:04:53.671   315  8134 V AudioCache: write(0xb16f6000, 4096)
07-27 15:04:53.671   315  8134 V AudioCache: memcpy(0xabf20000, 0xb16f6000, 4096)
07-27 15:04:53.671   315  8134 V AudioCache: write(0xb16f6000, 4096)
07-27 15:04:53.671   315  8134 V AudioCache: memcpy(0xabf21000, 0xb16f6000, 4096)
07-27 15:04:53.672   315  8134 V AudioCache: write(0xb16f6000, 4096)
07-27 15:04:53.672   315  8134 V AudioCache: memcpy(0xabf22000, 0xb16f6000, 4096)
07-27 15:04:53.675   315  8134 V AudioCache: write(0xb16f6000, 4096)
07-27 15:04:53.675   315  8134 V AudioCache: memcpy(0xabf23000, 0xb16f6000, 4096)
07-27 15:04:53.676   315  8134 V AudioCache: write(0xb16f6000, 4096)
07-27 15:04:53.676   315  8134 V AudioCache: memcpy(0xabf24000, 0xb16f6000, 4096)
07-27 15:04:53.676   315  8134 V AudioCache: write(0xb16f6000, 4096)
07-27 15:04:53.676   315  8134 V AudioCache: memcpy(0xabf25000, 0xb16f6000, 4096)
07-27 15:04:53.677   315  8134 V AudioCache: write(0xb16f6000, 4096)
07-27 15:04:53.677   315  8134 V AudioCache: mem,cpy(0xabf26000, 0xb16f6000, 4096)
07-27 15:04:53.677   315  8134 V AudioCache: write(0xb16f6000, 4096)
07-27 15:04:53.677   315  8134 V AudioCache: memcpy(0xabf27000, 0xb16f6000, 4096)
07-27 15:04:53.677   315  8134 V AudioCache: write(0xb16f6000, 4096)
07-27 15:04:53.677   315  8134 V AudioCache: memcpy(0xabf28000, 0xb16f6000, 4096)
07-27 15:04:53.678   315  8134 V AudioCache: write(0xb16f6000, 4096)
07-27 15:04:53.678   315  8134 V AudioCache: memcpy(0xabf29000, 0xb16f6000, 4096)
07-27 15:04:53.678   315  8134 V AudioCache: write(0xb16f6000, 4096)
07-27 15:04:53.678   315  8134 V AudioCache: memcpy(0xabf2a000, 0xb16f6000, 4096)
07-27 15:04:53.678   315  8134 V AudioCache: write(0xb16f6000, 4096)
,07-27 15:04:53.678   315  8134 V AudioCache: memcpy(0xabf2b000, 0xb16f6000, 4096)
07-27 15:04:53.679   315  8134 V AudioCache: write(0xb16f6000, 4096)
,07-27 15:04:53.679   315  8134 V AudioCache: memcpy(0xabf2c000, 0xb16f6000, 4096)
07-27 15:04:53.679   315  8134 V AudioCache: write(0xb16f6000, 4096)
07-27 15:04:53.679   315  8134 V AudioCache: memcpy(0xabf2d000, 0xb16f6000, 4096)
07-27 15:04:53.679   315  8134 V AudioCache: write(0xb16f6000, 4096)
07-27 15:04:53.679   315  8134 V AudioCache: memcpy(0xabf2e000, 0xb16f6000, 4096)
07-27 15:04:53.680   315  8134 V AudioCache: write(0xb16f6000, 4096)
07-27 15:04:53.680   315  8134 V AudioCache: memcpy(0xabf2f000, 0xb16f6000, 4096)
07-27 15:04:53.680   315  8134 V AudioCache: write(0xb16f6000, 4096)
07-27 15:04:53.680   315  8134 V AudioCache: memcpy(0xabf30000, 0xb16f6000, 4096)
07-27 15:04:53.681   315  8134 V AudioCache: write(0xb16f6000, 4096)
07-27 15:04:53.681   315  8134 V AudioCache: memcpy(0xabf31000, 0xb16f6000, 4096)
07-27 15:04:53.681   315  8134 V AudioCache: write(0xb16f6000, 4096)
07-27 15:04:53.681   315  8134 V AudioCache: memcpy(0xabf32000, 0xb16f6000, 4096)
07-27 15:04:53.681   315  8134 V AudioCache: write(0xb16f6000, 4096)
07-27 15:04:53.681   315  8134 V AudioCache: memcpy(0xabf33000, 0xb16f6000, 4096)
07-27 15:04:53.682   315  8134 V AudioCache: write(0xb16f6000, 4096)
07-27 15:04:53.682   315  8134 V AudioCache: memcpy(0xabf34000, 0xb16f6000, 4096)
07-27 15:04:53.682   315  8134 V AudioCache: write(0xb16f6000, 4096)
07-27 15:04:53.682   315  8134 V AudioCache: memcpy(0xabf35000, 0xb16f6000, 4096)
07-27 15:04:53.682   315  8134 V AudioCache: write(0xb16f6000, 4096)
07-27 15:04:53.682   315  8134 V AudioCache: memcpy(0xabf36000, 0xb16f6000, 4096)
07-27 15:04:53.683   315  8134 V AudioCache: write(0xb16f6000, 4096)
07-27 15:04:53.683   315  8134 V AudioCache: memcpy(0xabf37000, 0xb16f6000, 4096)
07-27 15:04:53.683   315  8134 V AudioCache: write(0xb16f6000, 4096)
07-27 15:04:53.683   315  8134 V AudioCache: memcpy(0xabf38000, 0xb16f6000, 4096)
07-27 15:04:53.683   315  8134 V AudioCache: write(0xb16f6000, 4096)
07-27 15:04:53.683   315  8134 V AudioCache: memcpy(0xabf39000, 0xb16f6000, 4096)
07-27 15:04:53.684   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
07-27 15:04:53.684   315  8134 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
07-27 15:04:53.684   315  8134 V AwesomePlayer: postAudioEOS() 
07-27 15:04:53.684   315  8134 V AudioCache: write(0xb16f6000, 280)
07-27 15:04:53.684   315  8134 V AudioCache: memcpy(0xabf3a000, 0xb16f6000, 280)
07-27 15:04:53.685   315  8131 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
07-27 15:04:53.685   315  8131 V AwesomePlayer: onStreamDone
07-27 15:04:53.685   315  8131 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
07-27 15:04:53.685   315  8131 V AudioCache: notify(0xb5474600, 2, 0, 0)
07-27 15:04:53.685   315  8131 V AudioCache: playback complete
07-27 15:04:53.685   315  8131 V AwesomePlayer: pause_l() 
07-27 15:04:53.685   315  8131 V AudioCache: notify(0xb5474600, 7, 0, 0)
07-27 15:04:53.685   315  8131 V AudioCache: ignored
07-27 15:04:53.685   315  8131 V AwesomePlayer: cancelPlayerEvents
07-27 15:04:53.685   315   315 V AudioCache: wait - success
07-27 15:04:53.685   315   315 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
07-27 15:04:53.686   315  8131 D AudioPlayer: Pause Playback at 1068125
07-27 15:04:53.691   315   315 V AwesomePlayer: reset_l() 
07-27 15:04:53.691   315   315 V AudioCache: notify(0xb5474600, 8, 0, 0)
07-27 15:04:53.691   315   315 V AudioCache: ignored
07-27 15:04:53.691   315   315 V AwesomePlayer: cancelPlayerEvents
07-27 15:04:53.691   315   315 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
07-27 15:04:53.691   315   315 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
07-27 15:04:53.691   315   315 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
07-27 15:04:53.691   315   315 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
07-27 15:04:53.691   315   315 V OMXCodec: [OMX.google.vorbis.d,ecoder] mAsyncCompletion wait lock!!
07-27 15:04:53.691   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
07-27 15:04:53.691   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
07-27 15:04:53.691   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
07-27 15:04:53.691   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 0
07-27 15:04:53.691   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
07-27 15:04:53.691   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f78d0 on port 0
07-27 15:04:53.691   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
07-27 15:04:53.691   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f77e0 on port 0
07-27 15:04:53.691   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
07-27 15:04:53.691   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7650 on port 0
07-27 15:04:53.691   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
07-27 15:04:53.691   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
07-27 15:04:53.691   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57bc470 on port 1
07-27 15:04:53.691   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
07-27 15:04:53.691   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 1
07-27 15:04:53.691   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
07-27 15:04:53.691   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 1
07-27 15:04:53.691   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
07-27 15:04:53.691   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 1
07-27 15:04:53.692   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-27 15:04:53.692   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
07-27 15:04:53.692   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
07-27 15:04:53.692   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
07-27 15:04:53.692   315  8133 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
07-27 15:04:53.692   315   315 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
07-27 15:04:53.692   315   315 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
07-27 15:04:53.692   315   315 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
07-27 15:04:53.692   315   315 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
07-27 15:04:53.693   315   315 D AudioPlayer: AudioPlayer releasing audio source
07-27 15:04:53.693   315   315 D AudioPlayer: AudioPlayer done releasing audio source
07-27 15:04:53.693   315   315 V AwesomePlayer: reset_l() 
07-27 15:04:53.693   315   315 V AwesomePlayer: cancelPlayerEvents
07-27 15:04:53.693   315   315 V AwesomePlayer: ~AwesomePlayer call
07-27 15:04:53.693   315   315 V AwesomePlayer: reset_l() 
07-27 15:04:53.693   315   315 V AwesomePlayer: cancelPlayerEvents
07-27 15:04:53.693  8069  8128 V SoundPool: close(31)
07-27 15:04:53.693  8069  8128 V SoundPool: pointer = 0x9fe84000, size = 205080, sampleRate = 48000, numChannels = 2
07-27 15:04:53.699  8069  8069 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
07-27 15:04:53.699  8069  8069 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
07-27 15:04:53.701  8069  8069 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:8022
07-27 15:04:53.703  8004  8004 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed br,oadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 15:04:53.706  8004  8004 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-27 15:04:53.708  8004  8004 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 15:04:53.710  8004  8004 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 15:04:53.713  8004  8004 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 15:04:53.715  8004  8004 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 15:04:53.717  8004  8004 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 15:04:53.720  8004  8004 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 15:04:53.723  8004  8004 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 15:04:53.751  8129  8129 D AndroidRuntime: 
07-27 15:04:53.751  8129  8129 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-27 15:04:53.753  8129  8129 D AndroidRuntime: CheckJNI is OFF
,07-27 15:04:53.874  8129  8129 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,07-27 15:04:53.905  1033  1093 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
07-27 15:04:53.905  1033  1093 I ActivityManager: Killing 6632:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
07-27 15:04:53.907  7508  7508 I UEI.SmartControl: Supports setup maps: true
07-27 15:04:53.909  7508  7508 D UEI.SmartControl: QS start statue = true Error code = 0
07-27 15:04:53.909  7508  7508 I UEI.SmartControl: QS version = v2.7.10.1_RC1
07-27 15:04:53.909  7508  7508 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
07-27 15:04:53.909  7508  7508 I UEI.SmartControl: ### init IR Blaster...
,07-27 15:04:53.916  7508  7508 D serial_port: Configuring serial port
07-27 15:04:53.916  7508  7508 E UEI.SmartControl: UEIBLaster setting for 616
07-27 15:04:53.916  7508  7508 I UEI.SmartControl: Setting serial record hearder size = 2
07-27 15:04:53.916  7508  7508 I UEI.SmartControl: configuring settings for MAXQ616
07-27 15:04:53.916  7508  7508 I UEI.SmartControl: Get version...
07-27 15:04:53.935  7508  8147 D UEI.SmartControl: serial port data available: 21
,07-27 15:04:53.949  1033  1870 I WindowState: WIN DEATH: Window{7707c6b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,07-27 15:04:53.950  1033  1544 D WifiService: Client connection lost with reason: 4
07-27 15:04:53.957  1033  1870 D InputDispatcher: Window went away: Window{7707c6b u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-27 15:04:53.961  7508  7508 D UEI.SmartControl: MAXQ616 A2-X4 software.
07-27 15:04:53.961  7508  7508 I UEI.SmartControl: IR Blaster version: 256702256704300002
07-27 15:04:53.961  7508  7508 I UEI.SmartControl: QS saving settings...
07-27 15:04:53.962  7508  7508 D UEI.SmartControl: IR Blaster version: 25672567
07-27 15:04:53.969  1033  1537 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-27 15:04:53.969  1033  1537 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-27 15:04:53.970  1033  1537 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-27 15:04:53.970  1033  1537 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-27 15:04:53.971  1033  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-27 15:04:53.971  1033  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-27 15:04:53.972  1033  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
07-27 15:04:53.972  1033  1545 D ConnectivityService: identical MTU - not setting
07-27 15:04:53.972  1033  1545 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
07-27 15:04:53.972  1033  1545 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
07-27 15:04:53.972  1033  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 15:04:53.972  1033  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 15:04:53.973  1033  1545 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-27 15:04:53.974  1604  2066 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
07-27 15:04:53.982  7508  8147 D UEI.SmartControl: serial port data available: 4
07-27 15:04:54.009  7508  8150 I UEI.SmartControl: Device manager: loading config....
,07-27 15:04:54.010  7508  7508 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
07-27 15:04:54.011  7508  8150 D UEI.SmartControl: ----------- loading internal config...
07-27 15:04:54.014  7508  8150 E UEI.SmartControl: Loading SETTINGS...
07-27 15:04:54.017  1033  1093 I ActivityManager:   Force finishing activity ActivityRecord{31612981 u0 com.test.thalitest/.MainActivity t40}
07-27 15:04:54.019  7508  8150 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,07-27 15:04:54.028  7508  8149 I UEI.SmartControl: Notify AllClients services are ready: 0
07-27 15:04:54.028  7508  8149 D UEI.SmartControl: -----service ready thread exits
07-27 15:04:54.038   341   370 E GBMv2   : DFP En is all cleared set to be enabled
07-27 15:04:54.039  1033  1630 W ActivityManager: Spurious death for ProcessRecord{12a47f5 6632:com.test.thalitest/u0a118}, curProc for 6632: null
07-27 15:04:54.040  1033  1104 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
,07-27 15:04:54.041  1033  1104 I ActivityManager:   Force finishing activity ActivityRecord{31612981 u0 com.test.thalitest/.MainActivity t40 f}
07-27 15:04:54.041  1033  1104 W ActivityManager: Duplicate finish request for ActivityRecord{31612981 u0 com.test.thalitest/.MainActivity t40 f}
07-27 15:04:54.059  7508  7508 E UEI.SmartControl: Services init done
,07-27 15:04:54.059  7508  7508 D UEI.SmartControl: QS Service init finished
07-27 15:04:54.061  1944  1959 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
07-27 15:04:54.061  1944  1959 D SplitWindowPolicy: topRunningActivity=ActivityInfo{c92c74e co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
07-27 15:04:54.061  2035  2035 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
07-27 15:04:54.062  7508  7508 D UEI.SmartControl: QS Service version name: 2.1.91
07-27 15:04:54.063  1944  1960 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
07-27 15:04:54.063  7508  7508 D UEI.SmartControl: QS Service version code: 201091
07-27 15:04:54.063  1944  1960 D SplitWindowPolicy: topRunningActivity=ActivityInfo{78cd06f co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
07-27 15:04:54.063  7508  7508 D UEI.SmartControl: Service requested: Control
07-27 15:04:54.065  2035  2035 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
,07-27 15:04:54.080  1604  1604 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
07-27 15:04:54.088  1033  1391 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-27 15:04:54.100  2501  2618 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-27 15:04:54.102  1997  1997 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
07-27 15:04:54.103  3838  3838 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,07-27 15:04:54.108  4491  4491 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-27 15:04:54.109  4491  4491 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
07-27 15:04:54.109  4491  4491 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
07-27 15:04:54.109  4491  4491 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
07-27 15:04:54.109  4491  4491 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-27 15:04:54.109  4491  4491 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-27 15:04:54.109  4491  4491 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-27 15:04:54.109  4491  4491 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-27 15:04:54.109  4491  4491 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 15:04:54.109  4491  4491 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 15:04:54.109  4491  4491 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-27 15:04:54.109  4491  4491 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-27 15:04:54.111  7581  7581 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
07-27 15:04:54.111  7581  7581 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,07-27 15:04:54.130  4604  4604 I art     : Explicit concurrent mark sweep GC freed 8186(467KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 532us total 75.482ms
07-27 15:04:54.145  1033  1927 V SIM_STK : Menu title from STK is T-Mobile
,07-27 15:04:54.155  1033  1092 W InputMethodInfo: Duplicated subtype definition found: , voice
07-27 15:04:54.184  1033  1033 D administrator: Handling package changes for user 0
,07-27 15:04:54.190  2035  2035 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
07-27 15:04:54.191  2035  2149 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
07-27 15:04:54.195  8069  8069 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
07-27 15:04:54.195  7508  7508 D UEI.SmartControl: Internal service binding...
07-27 15:04:54.196  7508  7543 I UEI.SmartControl: ------ IControl API: 11
07-27 15:04:54.196  7508  7543 D UEI.SmartControl: File observer start...
07-27 15:04:54.196  7508  7543 E UEI.SmartControl: IR Port is disabled: false
07-27 15:04:54.196  7508  7543 D UEI.SmartControl: Starting file observer...
07-27 15:04:54.196  8004  8004 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
07-27 15:04:54.197  7508  7543 I UEI.SmartControl: Registering callback...
07-27 15:04:54.200  7508  7544 I UEI.SmartControl: ------ IControl API: 19
07-27 15:04:54.201  7508  7544 I UEI.SmartControl: Registering Services Ready callback...
07-27 15:04:54.201  7508  7544 I UEI.SmartControl: Notify client services are ready...
07-27 15:04:54.201  8069  8085 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
07-27 15:04:54.202  8069  8126 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
07-27 15:04:54.202  8069  8126 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
,07-27 15:04:54.212  2035  2035 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
07-27 15:04:54.212  1908  1908 D ActionManagerService: notifyUserLog: 1000003
07-27 15:04:54.213  3838  4479 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
07-27 15:04:54.214  2035  2035 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,07-27 15:04:54.219  1818  1818 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
07-27 15:04:54.226  1871  1871 D SplitUIManager: split_name #11 / not available #0
07-27 15:04:54.227  1871  1871 D SplitUIService: removed split : 
,07-27 15:04:54.230  2035  2035 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
07-27 15:04:54.231  1604  1604 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
07-27 15:04:54.231  2035  2035 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
07-27 15:04:54.223  8069  8069 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
07-27 15:04:54.233  8069  8069 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
07-27 15:04:54.234  1604  1660 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
07-27 15:04:54.234  1604  1660 D KeyguardModel: createShortcutInfo...
07-27 15:04:54.234  7508  7543 I UEI.SmartControl: ------ IControl API: 8
07-27 15:04:54.238  8069  8069 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
07-27 15:04:54.238  8069  8069 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
07-27 15:04:54.238  8069  8069 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
07-27 15:04:54.238  8069  8069 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
07-27 15:04:54.239  1604  1660 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
07-27 15:04:54.239  1604  1660 D KeyguardModel: createShortcutInfo...
07-27 15:04:54.240  8069  8069 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
07-27 15:04:54.240  8069  8069 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
,07-27 15:04:54.244  2035  2035 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
07-27 15:04:54.244  1908  1908 D ActionManagerService: notifyUserLog: 1000004
07-27 15:04:54.246  3838  3853 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
07-27 15:04:54.247  3838  4479 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
07-27 15:04:54.247  1033  2034 V SIM_STK : Menu title from STK is T-Mobile
07-27 15:04:54.247  1033  2034 V SIM_STK : Menu title from STK is T-Mobile
07-27 15:04:54.249  1604  1660 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
07-27 15:04:54.250  1604  1660 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-27 15:04:54.250  1604  1660 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
07-27 15:04:54.251  2188  2188 I ConfigService: onCreate
,07-27 15:04:54.252  2188  2188 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
07-27 15:04:54.256  2035  2035 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
07-27 15:04:54.256  2035  2035 I GBoardWebViewUtils: , create_time: 1430832262123
07-27 15:04:54.256  2035  2035 I GBoardWebViewUtils: , expire_time: 0
07-27 15:04:54.256  2035  2035 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
07-27 15:04:54.256  2035  2035 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
07-27 15:04:54.256  2035  2035 I GBoardWebViewUtils: , display: false
07-27 15:04:54.256  2035  2035 I GBoardWebViewUtils: , animation: false }
07-27 15:04:54.256  2035  2035 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
07-27 15:04:54.256  2035  2035 I GBoardWebViewUtils: , create_time: 1430832262287
07-27 15:04:54.256  2035  2035 I GBoardWebViewUtils: , expire_time: 0
07-27 15:04:54.256  2035  2035 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
07-27 15:04:54.256  2035  2035 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
07-27 15:04:54.256  2035  2035 I GBoardWebViewUtils: , display: false
07-27 15:04:54.256  2035  2035 I GBoardWebViewUtils: , animation: false }
07-27 15:04:54.256  2035  2035 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1469186101390
07-27 15:04:54.256  2035  2035 I GBoardWebViewUtils: , create_time: 1469186101943
07-27 15:04:54.256  2035  2035 I GBoardWebViewUtils: , expire_time: 0
07-27 15:04:54.256  2035  2035 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1469186101390&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
07-27 15:04:54.256  2035  2035 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
07-27 15:04:54.256  2035  2035 I GBoardWebViewUtils: , display: false
07-27 15:04:54.256  2035  2035 I GBoardWebViewUtils: , animation: false }
07-27 15:04:54.252  1604  1660 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
07-27 15:04:54.259  1604  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 15:04:54.259  1604  1660 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
07-27 15:04:54.260  1818  1818 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
07-27 15:04:54.265  1604  1660 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
07-27 15:04:54.265  1604  1604 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
07-27 15:04:54.265  1604  1604 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
07-27 15:04:54.265  1604  1660 D KeyguardModel: createShortcutInfo...
,07-27 15:04:54.266  1871  1871 D SplitUIManager: split_name #11 / not available #0
07-27 15:04:54.266  1871  1871 I SplitUIService: split app #11
07-27 15:04:54.270  1604  1660 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
07-27 15:04:54.270  1604  1660 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-27 15:04:54.276  2188  2188 I ConfigService: onBind returning update interface
07-27 15:04:54.277  2188  2188 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
07-27 15:04:54.277  2188  2188 I ConfigService: onBind returning config service
07-27 15:04:54.280  2188  2188 I ConfigService: onDestroy
07-27 15:04:54.281  2035  8154 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,07-27 15:04:54.285  1818  8155 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
07-27 15:04:54.286  1604  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 15:04:54.287  1604  1660 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
07-27 15:04:54.289  8069  8069 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
07-27 15:04:54.291  8069  8069 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
07-27 15:04:54.293  1604  1660 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
07-27 15:04:54.293  1604  1660 D KeyguardModel: createShortcutInfo...
07-27 15:04:54.300  1604  1660 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-27 15:04:54.301  1604  1660 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-27 15:04:54.301  1604  1660 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
07-27 15:04:54.301  1604  1660 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
07-27 15:04:54.304  1033  1052 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
07-27 15:04:54.304  1604  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 15:04:54.304  1604  1660 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
07-27 15:04:54.304  7581  7581 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
07-27 15:04:54.304  7581  7581 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
07-27 15:04:54.304  7581  7581 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
07-27 15:04:54.304  7581  7581 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
07-27 15:04:54.304  7581  7581 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
07-27 15:04:54.304  7581  7581 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-27 15:04:54.304  7581  7581 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
07-27 15:04:54.304  7581  7581 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
07-27 15:04:54.304  7581  7581 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
07-27 15:04:54.304  7581  7581 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-27 15:04:54.304  7581  7581 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
07-27 15:04:54.305  2035  2035 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-27 15:04:54.305  2035  2035 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
07-27 15:04:54.306  1604  1660 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
07-27 15:04:54.306  1604  1660 D KeyguardModel: createShortcutInfo...
07-27 15:04:54.308  1033  1889 V SIM_STK : Menu title from STK is T-Mobile
07-27 15:04:54.311  1604  1604 D KeyguardModel: handleShortcutListChanged...
07-27 15:04:54.311  1604  1604 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,07-27 15:04:54.320  1604  1660 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
07-27 15:04:54.320  1604  1660 D KeyguardModel: createShortcutInfo...
07-27 15:04:54.327  1604  1660 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
07-27 15:04:54.327  1604  1660 D KeyguardModel: createShortcutInfo...
07-27 15:04:54.335  1604  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 15:04:54.335  1604  1660 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,07-27 15:04:54.336  1604  1660 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
07-27 15:04:54.336  1604  1660 D KeyguardModel: createShortcutInfo...
07-27 15:04:54.337  1604  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 15:04:54.337  1604  1660 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
07-27 15:04:54.338  1604  1660 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
07-27 15:04:54.338  1604  1660 D KeyguardModel: createShortcutInfo...
07-27 15:04:54.339  1604  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 15:04:54.339  1604  1660 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
07-27 15:04:54.340  1604  1660 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
07-27 15:04:54.340  1604  1660 D KeyguardModel: createShortcutInfo...
07-27 15:04:54.350  1033  1033 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
07-27 15:04:54.350  1033  1033 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-27 15:04:54.351  1033  1033 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-27 15:04:54.353  1818  4746 I Icing   : doRemovePackageData com.test.thalitest
07-27 15:04:54.353  1033  1579 D TaskPersister: removeObsoleteFile: deleting file=40_task.xml
07-27 15:04:54.354  1818  8163 I PeopleContactsSync: CP2 sync disabled
,07-27 15:04:54.372  5936  8161 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,07-27 15:04:54.373  6943  6943 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
07-27 15:04:54.374  2035  2035 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
07-27 15:04:54.380  1604  1604 D KeyguardModel: handleShortcutListChanged...
07-27 15:04:54.380  1604  1604 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
07-27 15:04:54.393  1033  1576 I ActivityManager: Killing 7143:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
,07-27 15:04:54.426   334   432 I ThermalEngine: Thermal-Server: Thermal received msg from  override
07-27 15:04:54.428  3216  8166 I Thermal-Lib: Thermal-Lib-Client: Client request sent
,07-27 15:04:54.454  2035  2035 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,07-27 15:04:54.458  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-27 15:04:54.459  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
07-27 15:04:54.460  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
07-27 15:04:54.461  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
07-27 15:04:54.462  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
07-27 15:04:54.471  1033  1104 I art     : Explicit concurrent mark sweep GC freed 86234(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 2.387ms total 407.130ms
,07-27 15:04:54.476  1033  1888 W libprocessgroup: failed to open /acct/uid_10005/pid_7143/cgroup.procs: No such file or directory
07-27 15:04:54.478  2035  2035 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
07-27 15:04:54.478  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-27 15:04:54.479  2035  2292 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
07-27 15:04:54.480  2035  2292 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,07-27 15:04:54.486  1033  1099 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{4944698 u0 com.lge.launcher2/.Launcher t39} time:157172
07-27 15:04:54.488  1818  8162 W GmsApplication: Using Auth Proxy for data requests.
07-27 15:04:54.491  2344  8168 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
07-27 15:04:54.494  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,07-27 15:04:54.495  2035  2035 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
07-27 15:04:54.495  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-27 15:04:54.506  2035  2035 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,07-27 15:04:54.519  1033  1980 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8170 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
07-27 15:04:54.521  2656  2656 D [Concierge]Service: onStartCommand(). Type : 8
07-27 15:04:54.521  2656  2656 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
,07-27 15:04:54.523  2656  2656 D [Concierge]Service: Update widget ID : 11
07-27 15:04:54.526  2035  2035 D [Concierge]WidgetView: change position of spinner
07-27 15:04:54.527  2035  2035 I [Concierge]WidgetView: initWebView(). Time : 1469624694527
07-27 15:04:54.527  2656  2656 D [Concierge]Service: onStartCommand(). Type : 0
07-27 15:04:54.528  1818  8162 W GmsApplication: Using Auth Proxy for data requests.
07-27 15:04:54.546  2035  2035 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 226655489
07-27 15:04:54.546  2035  2035 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
07-27 15:04:54.546  2035  2035 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
07-27 15:04:54.549  2035  2035 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@28a6e55a
07-27 15:04:54.549  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
07-27 15:04:54.551  2035  2035 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
07-27 15:04:54.551  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,07-27 15:04:54.556  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
07-27 15:04:54.556  2035  2035 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
07-27 15:04:54.556  2035  2035 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
07-27 15:04:54.557  2035  2035 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1469624566098, New one : 1469624694527
07-27 15:04:54.557  2035  2035 D [Concierge]WidgetView: Unregister all receivers
07-27 15:04:54.557  2035  2035 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
07-27 15:04:54.557  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-27 15:04:54.559  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
07-27 15:04:54.561  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
07-27 15:04:54.562  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
,07-27 15:04:54.563  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
07-27 15:04:54.565  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
07-27 15:04:54.570  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-27 15:04:54.570  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-27 15:04:54.586  8170  8170 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-27 15:04:54.586  8170  8170 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,07-27 15:04:54.587  8129  8129 D AndroidRuntime: Shutting down VM
07-27 15:04:54.587  8170  8170 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-27 15:04:54.588  8170  8170 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
07-27 15:04:54.605  2035  2035 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,07-27 15:04:54.608  2188  2340 I art     : Explicit concurrent mark sweep GC freed 5474(330KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 3.159ms total 43.547ms
07-27 15:04:54.616  2035  2035 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
07-27 15:04:54.617  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
,07-27 15:04:54.618  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-27 15:04:54.639  2035  2035 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3bd4e5a2 time:157324
,07-27 15:04:54.646  1033  1092 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-27 15:04:54.650  1033  1092 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
07-27 15:04:54.655  8170  8170 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
07-27 15:04:54.657  2035  2035 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
07-27 15:04:54.664  8170  8170 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,07-27 15:04:54.683  8170  8170 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-27 15:04:54.701  8170  8170 D LgDataFeature: LgDataFeature() Constructor: none
,07-27 15:04:54.701  8170  8170 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-27 15:04:54.746  2035  2035 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,07-27 15:04:54.747  8170  8170 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,07-27 15:04:54.754  1033  2034 I ActivityManager: Killing 7608:com.google.android.talk/u0a72 (adj 15): empty #17
07-27 15:04:54.783  2035  2947 I GBoardtInterface: onReloaded()
,07-27 15:04:54.785  2035  2035 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
07-27 15:04:54.828  1997  1997 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
07-27 15:04:54.828  1997  1997 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
,07-27 15:04:54.828  1033  1052 W libprocessgroup: failed to open /acct/uid_10072/pid_7608/cgroup.procs: No such file or directory
07-27 15:04:54.830  3838  3853 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
07-27 15:04:54.862  1033  1104 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8193 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,07-27 15:04:54.862  1997  1997 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
07-27 15:04:54.864  3838  4478 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
07-27 15:04:54.871  1908  1908 D ActionManagerService: notifyUserLog: 1000001
07-27 15:04:54.872  3838  4479 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
07-27 15:04:54.872  3838  4479 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
07-27 15:04:54.876  1908  1908 D ActionManagerService: notifyUserLog: 1000001
,07-27 15:04:54.878  3838  4479 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
07-27 15:04:54.878  3838  4479 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
07-27 15:04:54.878  3838  4479 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
07-27 15:04:54.878  3838  4479 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
07-27 15:04:54.878  3838  3853 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
07-27 15:04:54.880  2035  2035 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
07-27 15:04:54.880  2035  2035 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
07-27 15:04:54.883  2035  2035 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
07-27 15:04:54.883  2035  2035 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
07-27 15:04:54.884  2035  2035 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1469186101390&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
07-27 15:04:54.884  2035  2035 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1469186101390&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
07-27 15:04:54.886  8004  8004 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
07-27 15:04:54.905  7382  7382 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
,07-27 15:04:54.908  6749  6749 D PackageIntentReceiver: Not supported Hotkey customization function 
,07-27 15:04:54.912  6749  6749 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
07-27 15:04:54.912  6749  6749 D HideNavigationAppsReceiver: replacing : false
07-27 15:04:54.914  6749  6749 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
07-27 15:04:54.917  6749  6749 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
07-27 15:04:54.917  6749  6749 D ButtonCombinationReceiver: replacing : false
,07-27 15:04:54.924  1033  1576 I ActivityManager: Killing 7220:com.google.android.apps.plus/u0a97 (adj 15): empty #17
07-27 15:04:54.995  1033  1888 W libprocessgroup: failed to open /acct/uid_10097/pid_7220/cgroup.procs: No such file or directory

```
