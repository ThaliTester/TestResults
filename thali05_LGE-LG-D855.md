#### Test 800380637c16410_thali05_LGE-LG-D855 Logs


```
--------- beginning of main
08-04 10:45:58.472  6557  6557 D DocsApplication: Installing DEX configuration.
08-04 10:45:58.491  6557  6557 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
08-04 10:45:58.494  6557  6557 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{39c4100 com.google.android.apps.docs}
08-04 10:45:58.512  6557  6557 D TAG     : onCreate()
08-04 10:45:58.524  4589  6556 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 365 ms] updated apps [took 365 ms] 
08-04 10:45:58.531  6557  6557 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
08-04 10:45:59.525  1805  4646 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
08-04 10:45:59.549   334   429 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-04 10:45:59.552  3206  6604 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-04 10:45:59.580  1805  4646 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-04 10:45:59.601  6557  6557 D LgDataFeature: LgDataFeature() Constructor: none
08-04 10:45:59.601  6557  6557 D LgDataFeature: LgDataFeature() Constructor Done, null
08-04 10:45:59.630  1805  4646 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
08-04 10:45:59.707  6190  6190 I LockScreenSettings: New app installed broadcast received ..
08-04 10:45:59.713  6190  6190 I LockScreenSettings: Number of installed packages  1
08-04 10:45:59.718  6557  6557 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
08-04 10:45:59.758  1039  1983 V SIM_STK : Menu title from STK is T-Mobile
--------- beginning of system
08-04 10:45:59.803  1039  2003 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6616 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-04 10:45:59.879  6616  6616 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-04 10:45:59.879  6616  6616 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
08-04 10:45:59.922  1039  1983 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6633 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-04 10:45:59.924  1039  1983 I ActivityManager: Killing 5807:com.google.android.talk/u0a72 (adj 15): empty #17
08-04 10:45:59.983  1039  2020 W libprocessgroup: failed to open /acct/uid_10072/pid_5807/cgroup.procs: No such file or directory
08-04 10:46:00.000  1039  1364 D PowerManagerServiceEx: acquireWakeLockInternal: lock=431689952, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
08-04 10:46:00.033  2581  2581 D [Concierge]Service: onStartCommand(). Type : 9
08-04 10:46:00.043  1590  1590 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-04 10:46:00.043  1590  1590 I KeyguardUpdateMonitor: called onTimeUpdated()
08-04 10:46:00.044  1590  1590 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-04 10:46:00.044  1590  1590 I [SystemUI]Clock: called onTimeUpdated()
08-04 10:46:00.050  1590  1590 I LgeClockWidgetControlView: called onTimeUpdated()
08-04 10:46:00.050  1590  1590 I [SystemUI]DateView: called onTimeUpdated()
08-04 10:46:00.051  1590  1590 I [SystemUI]DateView: called onTimeUpdated()
08-04 10:46:00.054  1590  1590 D KeyguardUpdateMonitor: handleTimeUpdate
08-04 10:46:00.063  6633  6633 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
08-04 10:46:00.090  6633  6633 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-04 10:46:00.095  6409  6409 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-04 10:46:00.139  1039  1054 I ActivityManager: Killing 5620:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-04 10:46:00.156  5598  5598 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-04 10:46:00.157  5598  5598 W System.err: android.os.DeadObjectException
08-04 10:46:00.157  5598  5598 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-04 10:46:00.157  5598  5598 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-04 10:46:00.157  5598  5598 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-04 10:46:00.157  5598  5598 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-04 10:46:00.157  5598  5598 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-04 10:46:00.157  5598  5598 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-04 10:46:00.157  5598  5598 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-04 10:46:00.157  5598  5598 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-04 10:46:00.157  5598  5598 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-04 10:46:00.157  5598  5598 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-04 10:46:00.158  5598  5598 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 10:46:00.158  5598  5598 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-04 10:46:00.158  5598  5598 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-04 10:46:00.158  5598  5598 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-04 10:46:00.158  5598  5598 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-04 10:46:00.159  5598  5598 W System.err: android.os.DeadObjectException
08-04 10:46:00.159  5598  5598 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-04 10:46:00.159  5598  5598 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-04 10:46:00.159  5598  5598 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-04 10:46:00.159  5598  5598 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-04 10:46:00.160  5598  5598 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-04 10:46:00.160  5598  5598 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-04 10:46:00.160  5598  5598 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-04 10:46:00.160  5598  5598 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-04 10:46:00.160  5598  5598 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-04 10:46:00.160  5598  5598 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-04 10:46:00.160  5598  5598 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 10:46:00.160  5598  5598 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-04 10:46:00.160  5598  5598 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-04 10:46:00.160  5598  5598 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-04 10:46:00.160  5598  5598 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-04 10:46:00.161  5598  5598 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-04 10:46:00.166  4456  6658 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
08-04 10:46:00.290  1039  1875 W libprocessgroup: failed to open /acct/uid_1000/pid_5620/cgroup.procs: No such file or directory
08-04 10:46:00.291  1039  1875 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-04 10:46:00.305  1039  1039 D PowerManagerServiceEx: releaseWakeLockInternal: lock=431689952 [*alarm*], flags=0x0
08-04 10:46:00.313  5598  5598 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-04 10:46:00.314  5598  5598 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-04 10:46:00.389  1039  1563 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6667 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-04 10:46:00.389  5598  5598 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-04 10:46:00.398  6663  6663 D AndroidRuntime: 
08-04 10:46:00.398  6663  6663 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-04 10:46:00.401  6663  6663 D AndroidRuntime: CheckJNI is OFF
08-04 10:46:00.469  6667  6667 D UEI.SmartControl: Quickset Services start...
08-04 10:46:00.471  6667  6667 I UEI.SmartControl: Manufacture = LGE
08-04 10:46:00.471  6667  6667 D UEI.SmartControl: Id = LGNevo
08-04 10:46:00.472  6667  6667 D UEI.SmartControl: File observer start...
08-04 10:46:00.473  6667  6667 E UEI.SmartControl: IR Port is disabled: false
08-04 10:46:00.473  6667  6667 D UEI.SmartControl: Starting file observer...
08-04 10:46:00.473  6667  6667 D UEI.SmartControl: Extracting JNI libs...
08-04 10:46:00.473  6667  6667 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-04 10:46:00.527  6663  6663 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-04 10:46:00.532  1039  1054 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-04 10:46:00.542  1930  1945 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-04 10:46:00.544  1039  1054 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-04 10:46:00.545  1039  1054 D ActivityManager: setTaskToReturnTo : TaskRecord{42d575b #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-04 10:46:00.545  1039  1054 D ActivityManager: setTaskToReturnTo : TaskRecord{42d575b #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-04 10:46:00.546  1039  1054 D WindowStateEx: AppWindowTokenEx init.. 
08-04 10:46:00.547   343   365 E GBMv2   : DFP En is all cleared set to be enabled
08-04 10:46:00.550  6667  6667 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-04 10:46:00.550  6667  6667 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-04 10:46:00.551  6667  6667 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
08-04 10:46:00.576  6667  6667 I UEI.SmartControl: --- Selecting new region: 6
08-04 10:46:00.577  6667  6667 I UEI.SmartControl: Model = LG-D855
08-04 10:46:00.578  6667  6667 D UEI.SmartControl: QS Service created
08-04 10:46:00.586  1039  1054 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6705 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-04 10:46:00.587  6663  6663 D AndroidRuntime: Shutting down VM
08-04 10:46:00.596  6667  6667 I UEI.SmartControl: Service initServices...
08-04 10:46:00.599  6667  6667 D UEI.SmartControl: QS start get config
08-04 10:46:00.631  6667  6667 D UEI.SmartControl: Loading JNI Libs...
08-04 10:46:00.650  1930  1945 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-04 10:46:00.650  1930  1945 D SplitWindowPolicy: topRunningActivity=ActivityInfo{c5e9e7c co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
08-04 10:46:00.651  1930  1945 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-04 10:46:00.652  1930  1945 D SplitWindowPolicy: topRunningActivity=ActivityInfo{287b7305 co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
08-04 10:46:00.708  6705  6705 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-04 10:46:00.782  6705  6705 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-04 10:46:00.789  6705  6705 I LibraryLoader: Loading: webviewchromium
08-04 10:46:00.791  6705  6705 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 8209-8213)
08-04 10:46:00.792  6705  6705 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-04 10:46:00.807  6705  6705 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3b31558a}
08-04 10:46:00.808  6705  6705 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-04 10:46:00.808  6705  6705 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-04 10:46:00.816  6705  6705 I BrowserStartupController: Initializing chromium process, renderers=0
08-04 10:46:00.817  6705  6705 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-04 10:46:00.831  6705  6705 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-04 10:46:00.838  6705  6705 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-04 10:46:00.839  6705  6705 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-04 10:46:00.842   322  1374 V AudioPolicyService: registerClient() client 0xb14e7160, uid 10118
08-04 10:46:00.845  1039  1121 D BluetoothManagerService: Message: 20
08-04 10:46:00.846  1039  1121 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e1d010d:true
,08-04 10:46:00.853  6705  6705 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-04 10:46:00.853  6705  6705 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-04 10:46:00.853  6705  6705 I Adreno-EGL: Build Date: 12/12/14 금
08-04 10:46:00.853  6705  6705 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-04 10:46:00.853  6705  6705 I Adreno-EGL: Remote Branch: 
08-04 10:46:00.853  6705  6705 I Adreno-EGL: Local Patches: 
08-04 10:46:00.853  6705  6705 I Adreno-EGL: Reconstruct Branch: 
08-04 10:46:00.873  6667  6667 I UEI.SmartControl: Supports setup maps: true
08-04 10:46:00.876  6667  6667 D UEI.SmartControl: QS start statue = true Error code = 0
,08-04 10:46:00.876  6667  6667 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-04 10:46:00.876  6667  6667 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-04 10:46:00.876  6667  6667 I UEI.SmartControl: ### init IR Blaster...
,08-04 10:46:00.880  6667  6667 D serial_port: Configuring serial port
,08-04 10:46:00.883  6667  6667 E UEI.SmartControl: UEIBLaster setting for 616
08-04 10:46:00.883  6667  6667 I UEI.SmartControl: Setting serial record hearder size = 2
08-04 10:46:00.884  6667  6667 I UEI.SmartControl: configuring settings for MAXQ616
08-04 10:46:00.884  6667  6667 I UEI.SmartControl: Get version...
08-04 10:46:00.901  6667  6736 D UEI.SmartControl: serial port data available: 21
,08-04 10:46:00.928  6667  6667 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-04 10:46:00.928  6667  6667 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-04 10:46:00.928  6667  6667 I UEI.SmartControl: QS saving settings...
,08-04 10:46:00.931  6667  6667 D UEI.SmartControl: IR Blaster version: 25672567
08-04 10:46:00.945  6705  6734 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-04 10:46:00.947  6705  6705 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,08-04 10:46:00.947  6667  6736 D UEI.SmartControl: serial port data available: 4
08-04 10:46:00.966  6705  6705 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-04 10:46:00.972  6705  6705 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-04 10:46:00.976  6705  6705 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
,08-04 10:46:00.979  6705  6705 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-04 10:46:00.979  6705  6705 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-04 10:46:00.980  6667  6745 I UEI.SmartControl: Device manager: loading config....
,08-04 10:46:00.981  6667  6745 D UEI.SmartControl: ----------- loading internal config...
,08-04 10:46:00.985  6667  6667 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-04 10:46:00.987  6667  6667 E UEI.SmartControl: Services init done
08-04 10:46:00.987  6667  6667 D UEI.SmartControl: QS Service init finished
08-04 10:46:00.989  6667  6667 D UEI.SmartControl: QS Service version name: 2.1.91
08-04 10:46:00.989  6667  6667 D UEI.SmartControl: QS Service version code: 201091
08-04 10:46:00.996  6705  6705 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-04 10:46:00.997  6667  6667 D UEI.SmartControl: Service requested: Control
08-04 10:46:01.001  6667  6745 E UEI.SmartControl: Loading SETTINGS...
,08-04 10:46:01.004  6667  6667 D UEI.SmartControl: Request IControl service: devices are loaded...
08-04 10:46:01.005  6705  6705 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-04 10:46:01.005  1039  1874 I ActivityManager: Killing 5598:com.lge.qremote/u0a112 (adj 15): empty #17
08-04 10:46:01.005  6705  6705 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-04 10:46:01.015  6667  6745 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-04 10:46:01.038  6667  6744 I UEI.SmartControl: Notify AllClients services are ready: 0
08-04 10:46:01.038  6667  6744 D UEI.SmartControl: -----service ready thread exits
,08-04 10:46:01.076  6667  6667 D UEI.SmartControl: Internal service binding...
08-04 10:46:01.077  1039  1563 W libprocessgroup: failed to open /acct/uid_10112/pid_5598/cgroup.procs: No such file or directory
,08-04 10:46:01.091  6705  6756 D OpenGLRenderer: Render dirty regions requested: true
,08-04 10:46:01.091  6705  6756 I OpenGLRenderer: Initialized EGL, version 1.4
08-04 10:46:01.095  6705  6750 D LgDataFeature: LgDataFeature() Constructor: none
08-04 10:46:01.096  6705  6750 D LgDataFeature: LgDataFeature() Constructor Done, null
08-04 10:46:01.107  6705  6756 D OpenGLRenderer: Enabling debug mode 0
,08-04 10:46:01.114  6705  6705 D Atlas   : Validating map...
08-04 10:46:01.121  1039  2020 D SplitWindow: check instance of lgWin Window{21d9a1ca u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-04 10:46:01.293  1039  1122 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +644ms (total +745ms)
,08-04 10:46:01.294  1039  1122 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{34e1bf8 u0 com.test.thalitest/.MainActivity t40} time:118715
08-04 10:46:01.297  6705  6705 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@4cc61e1 time:118718
08-04 10:46:01.399  6705  6705 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-04 10:46:01.399  6705  6705 I chromium: 
,08-04 10:46:01.446  6705  6705 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-04 10:46:01.609  6705  6766 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435163136
,08-04 10:46:01.621  6705  6766 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-04 10:46:01.621  6705  6766 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-04 10:46:01.621  6705  6766 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-04 10:46:01.621  6705  6766 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-04 10:46:01.621  6705  6766 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-04 10:46:01.621  6705  6766 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ef8b0d5 added. We now have 1 listener(s)
08-04 10:46:01.626  1039  1563 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-04 10:46:01.632  6705  6766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-04 10:46:01.637  6705  6766 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-04 10:46:01.639  6705  6766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 10:46:01.640  6705  6766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-04 10:46:01.652  6705  6766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-04 10:46:01.652  6705  6766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-04 10:46:01.652  6705  6766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-04 10:46:01.652  6705  6766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-04 10:46:01.652  6705  6766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-04 10:46:01.652  6705  6766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-04 10:46:01.652  6705  6766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-04 10:46:01.652  6705  6766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-04 10:46:01.652  6705  6766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-04 10:46:01.652  6705  6766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-04 10:46:01.652  6705  6766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-04 10:46:01.652  6705  6766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-04 10:46:01.652  6705  6766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-04 10:46:01.652  6705  6766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-04 10:46:01.652  6705  6766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b69a78 added. We now have 1 listener(s)
08-04 10:46:01.652  6705  6766 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 10:46:01.664  1039  1531 D WifiService: New client listening to asynchronous messages
,08-04 10:46:01.669  6705  6766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-04 10:46:01.669  6705  6766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-04 10:46:01.670  6705  6766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-04 10:46:01.670  6705  6766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-04 10:46:01.670  6705  6766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-04 10:46:01.673  6705  6766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 10:46:01.674  1039  1893 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 10:46:01.675  6705  6766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-04 10:46:01.684  6705  6766 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-04 10:46:01.685  6705  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 10:46:01.685  6705  6766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:01.685  6705  6766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:01.685  6705  6766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:46:01.685  6705  6766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 10:46:01.685  6705  6766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 10:46:01.685  6705  6766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 10:46:01.685  6705  6766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 10:46:01.685  6705  6766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-04 10:46:01.685  6705  6766 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-04 10:46:01.687  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:46:01.689  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:46:01.690  6705  6766 I io.jxcore.node.LifeCycleMonitor: start: OK
08-04 10:46:01.725  6705  6750 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-04 10:46:01.725  6705  6750 I chromium: 
,08-04 10:46:01.790  6705  6705 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-04 10:46:02.348  6705  6769 W jxcore-log: Initializing JXcore engine
08-04 10:46:02.348  6705  6769 W jxcore-log: JXcore engine is ready
,08-04 10:46:02.419   343   367 E GBMv2   : DFP En is all cleared set to be enabled
,08-04 10:46:02.419   343   367 E GBMv2   : Set value is all cleared set the max
08-04 10:46:02.419   343   367 I GBMv2   : DFP Enabled. Ignore VFP set
,08-04 10:46:02.437  6769  6769 W Thread-777: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[8322]" dev="sockfs" ino=8322 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-04 10:46:02.437  6769  6769 W Thread-777: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-04 10:46:02.437  6769  6769 W Thread-777: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10541]" dev="sockfs" ino=10541 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-04 10:46:02.437  6769  6769 W Thread-777: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-04 10:46:02.437  6769  6769 W Thread-777: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[33879]" dev="sockfs" ino=33879 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-04 10:46:02.468  6705  6769 W jxcore-log: Starting JXcore engine
,08-04 10:46:02.612  6705  6769 W jxcore-log: Platform android
08-04 10:46:02.612  6705  6769 W jxcore-log: 
08-04 10:46:02.612  6705  6769 W jxcore-log: Process ARCH arm
08-04 10:46:02.612  6705  6769 W jxcore-log: 
,08-04 10:46:02.898  6705  6769 I jxcore-log: JXcore Cordova bridge is ready!
08-04 10:46:02.898  6705  6769 I jxcore-log: 
,08-04 10:46:02.901  6705  6769 W jxcore-log: JXcore engine is started
,08-04 10:46:02.915  6705  6766 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-04 10:46:02.919  6705  6705 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-04 10:46:03.669  6557  6557 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
08-04 10:46:03.671  1039  1893 I ActivityManager: Killing 6258:com.android.calendar/u0a13 (adj 15): empty #17
,08-04 10:46:03.730  1039  2020 W libprocessgroup: failed to open /acct/uid_10013/pid_6258/cgroup.procs: No such file or directory
,08-04 10:46:04.671  6557  6605 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-04 10:46:05.987  6667  6746 D UEI.SmartControl: Internal timer expired: 1
,08-04 10:46:05.988  6667  6746 D UEI.SmartControl: unbind internal service
,08-04 10:46:05.997  6667  6667 D UEI.SmartControl: Service.onUnbind: IControl
08-04 10:46:05.997  6667  6667 D UEI.SmartControl: Service.onDestroy
08-04 10:46:05.997  6667  6667 D UEI.SmartControl: Lock is in USE false
08-04 10:46:05.997  6667  6667 D UEI.SmartControl: unbind internal service
08-04 10:46:05.997  6667  6667 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@b574056
08-04 10:46:05.998  6667  6667 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-04 10:46:05.998  6667  6667 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-04 10:46:05.998  6667  6667 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-04 10:46:05.998  6667  6667 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-04 10:46:05.998  6667  6667 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-04 10:46:05.998  6667  6667 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-04 10:46:05.998  6667  6667 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-04 10:46:05.998  6667  6667 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-04 10:46:05.998  6667  6667 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 10:46:05.998  6667  6667 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-04 10:46:05.998  6667  6667 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-04 10:46:05.998  6667  6667 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 10:46:05.998  6667  6667 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-04 10:46:05.998  6667  6667 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-04 10:46:05.998  6667  6667 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-04 10:46:05.998  6667  6667 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@b574056
08-04 10:46:06.000  6667  6667 D serial_port: close(fd = 25)
08-04 10:46:06.004  6667  6667 I UEI.SmartControl: Serial port is closed.
08-04 10:46:06.004  6667  6667 I UEI.SmartControl: Serial port is closed.
08-04 10:46:06.004  6667  6667 D UEI.SmartControl: Blaster closed
08-04 10:46:06.004  6667  6667 D UEI.SmartControl: Shut down QS...
08-04 10:46:06.004  6667  6667 D UEI.SmartControl: Stopping QS lib
08-04 10:46:06.004  6667  6667 D UEI.SmartControl: QS lib stop result = true
08-04 10:46:06.004  6667  6667 D UEI.SmartControl: Stopped QS lib
08-04 10:46:06.004  6667  6667 D UEI.SmartControl: Stopped file observer...
08-04 10:46:06.004  6667  6667 D UEI.SmartControl: QS shutdown complete
,08-04 10:46:12.453  1039  1113 I ActivityManager: Waited long enough for: ServiceRecord{15f8596f u0 com.google.android.gms/.wearable.service.WearableService}
,08-04 10:46:13.156  6705  6769 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-04 10:46:13.156  6705  6769 I jxcore-log: 
08-04 10:46:13.159  6705  6769 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-04 10:46:13.159  6705  6769 I jxcore-log: 
,08-04 10:46:13.162  6705  6769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 10:46:13.162  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:13.162  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:13.162  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:46:13.162  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 10:46:13.162  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 10:46:13.162  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 10:46:13.162  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 10:46:13.165  6705  6769 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 10:46:13.167  6705  6769 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-04 10:46:13.167  6705  6769 I jxcore-log: 
08-04 10:46:13.168  6705  6769 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-04 10:46:13.168  6705  6769 I jxcore-log: 
08-04 10:46:13.491  6705  6769 D ExecuteNativeTests: Running unit tests
,08-04 10:46:13.571  6705  6769 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 10:46:13.571  6705  6769 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10a1183a added. We now have 2 listener(s)
08-04 10:46:13.571  1039  1633 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-04 10:46:13.573  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-04 10:46:13.573  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-04 10:46:13.573  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 10:46:13.573  6705  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 10:46:13.573  6705  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20d52ceb added. We now have 2 listener(s)
08-04 10:46:13.573  6705  6769 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 10:46:13.573  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-04 10:46:13.579  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 10:46:13.581  6705  6769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 10:46:13.581  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:13.581  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:13.581  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:46:13.581  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 10:46:13.581  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 10:46:13.581  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 10:46:13.581  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 10:46:13.582  6705  6769 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 10:46:13.582  6705  6769 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 10:46:13.585  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:46:13.586  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:46:13.588  6705  6769 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-04 10:46:13.590  6705  6769 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-04 10:46:13.590  6705  6769 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-04 10:46:13.592  6705  6769 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-04 10:46:13.593  6705  6769 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-04 10:46:13.593  6705  6769 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-04 10:46:13.593  6705  6769 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-04 10:46:13.593  6705  6769 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-04 10:46:13.594  6705  6769 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:46:13.595  6705  6769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:46:13.595  6705  6769 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:46:13.595  6705  6769 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:13.595  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.595  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 10:46:13.595  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 10:46:13.595  6705  6769 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10a1183a removed from the list
08-04 10:46:13.595  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:13.595  6705  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20d52ceb removed from the list
08-04 10:46:13.595  6705  6769 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:46:13.595  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.596  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.596  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.597  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:13.597  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:13.597  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:13.597  6705  6769 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20d52ceb not in the list
08-04 10:46:13.600  6705  6769 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-04 10:46:13.600  6705  6769 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:46:13.600  6705  6769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STA,RTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:46:13.600  6705  6769 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:46:13.601  6705  6769 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:13.601  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.601  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.601  6705  6769 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10a1183a not in the list
08-04 10:46:13.601  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:13.601  6705  6769 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20d52ceb not in the list
08-04 10:46:13.601  6705  6769 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:46:13.601  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 10:46:13.601  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.601  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.601  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 10:46:13.602  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:13.602  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:13.602  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:13.602  6705  6769 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20d52ceb not in the list
08-04 10:46:13.607  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-04 10:46:13.607  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-04 10:46:13.607  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-04 10:46:13.607  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-04 10:46:13.607  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-04 10:46:13.607  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-04 10:46:13.607  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-04 10:46:13.607  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-04 10:46:13.607  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-04 10:46:13.607  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-04 10:46:13.607  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-04 10:46:13.607  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-04 10:46:13.607  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-04 10:46:13.607  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-04 10:46:13.607  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-04 10:46:13.607  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-04 10:46:13.607  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-04 10:46:13.607  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-04 10:46:13.607  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-04 10:46:13.607  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-04 10:46:13.607  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-04 10:46:13.607  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-04 10:46:13.607  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-04 10:46:13.607  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoing,Connections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-04 10:46:13.607  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-04 10:46:13.607  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-04 10:46:13.607  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-04 10:46:13.607  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-04 10:46:13.607  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-04 10:46:13.607  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-04 10:46:13.607  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-04 10:46:13.607  6705  6769 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:46:13.607  6705  6769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:46:13.607  6705  6769 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:46:13.608  6705  6769 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:13.608  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.608  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.608  6705  6769 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10a1183a not in the list
08-04 10:46:13.608  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:13.608  6705  6769 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20d52ceb not in the list
08-04 10:46:13.608  6705  6769 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:46:13.609  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.609  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-04 10:46:13.609  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.609  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.609  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:13.609  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:13.609  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:13.609  6705  6769 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20d52ceb not in the list
08-04 10:46:13.610  6705  6769 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-04 10:46:13.611  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 10:46:13.613  6705  6769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 10:46:13.613  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:13.613  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:13.613  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:46:13.613  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 10:46:13.613  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 10:46:13.613  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 10:46:13.613  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-04 10:46:13.615  6705  6769 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 10:46:13.616  6705  6769 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 10:46:13.617  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:46:13.617  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:46:13.618  6705  6769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-04 10:46:13.618  6705  6769 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 10:46:13.618  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-04 10:46:13.618  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 10:46:13.618  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-04 10:46:13.620  6705  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-04 10:46:13.621  1039  2003 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 10:46:13.624  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-04 10:46:13.627  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-04 10:46:13.629  6705  6769 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-04 10:46:13.630  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-04 10:46:13.630  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 10:46:13.631  6705  6769 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-04 10:46:13.632  6705  6769 I io.jxcore.node.ConnectionHelper: start: OK
08-04 10:46:13.634  6705  6769 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:46:13.634  6705  6769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:46:13.634  6705  6769 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:46:13.634  6705  6769 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:13.634  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.634  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 10:46:13.634  6705  6769 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10a1183a not in the list
08-04 10:46:13.634  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:13.634  6705  6769 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20d52ceb not in the list
08-04 10:46:13.634  6705  6769 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:46:13.634  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.635  6705  6769 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-04 10:46:13.635  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 10:46:13.637  6705  6769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 10:46:13.637  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:13.637  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:13.637  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:46:13.637  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 10:46:13.637  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 10:46:13.637  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 10:46:13.637  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 10:46:13.638  6705  6769 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 10:46:13.638  6705  6769 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 10:46:13.638  6705  6769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 10:46:13.638  6705  6769 V io.jxcore.node.StartStopO,perationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 10:46:13.638  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-04 10:46:13.638  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 10:46:13.638  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-04 10:46:13.641  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:46:13.646  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:46:13.646  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-04 10:46:13.647  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 10:46:13.647  6705  6769 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-04 10:46:13.647  6705  6769 I io.jxcore.node.ConnectionHelper: start: OK
08-04 10:46:13.649  6705  6769 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:46:13.649  6705  6769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:46:13.649  6705  6769 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:46:13.649  6705  6769 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:13.649  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.649  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 10:46:13.649  6705  6769 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10a1183a not in the list
08-04 10:46:13.649  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:13.649  6705  6769 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20d52ceb not in the list
08-04 10:46:13.649  6705  6769 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:46:13.649  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.649  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.649  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.650  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:13.650  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:13.651  6705  6769 D BluetoothLeScanner: could not find callback wrapper
08-04 10:46:13.651  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 10:46:13.651  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:13.651  6705  6769 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20d52ceb not in the list
08-04 10:46:13.652  6705  6769 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-04 10:46:13.653  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 10:46:13.655  6705  6769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 10:46:13.655  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:13.655  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:13.655  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:46:13.655  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 10:46:13.655  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 10:46:13.655  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 10:46:13.655  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 10:46:13.656  6705  6769 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 10:46:13.656  6705  6769 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 10:46:13.656  6705  6769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 10:46:13.656  6705  6769 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 10:46:13.656  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-04 10:46:13.656  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 10:46:13.656  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-04 10:46:13.658  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:46:13.659  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:46:13.661  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-04 10:46:13.661  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 10:46:13.662  6705  6769 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-04 10:46:13.662  6705  6769 I io.jxcore.node.ConnectionHelper: start: OK
08-04 10:46:13.662  6705  6769 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:46:13.662  6705  6769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:46:13.662  6705  6769 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:46:13.663  6705  6769 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:46:13.663  6705  6769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:46:13.663  6705  6769 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:46:13.663  6705  6769 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:13.663  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probab,ly already removed
08-04 10:46:13.663  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 10:46:13.663  6705  6769 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10a1183a not in the list
08-04 10:46:13.663  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:13.663  6705  6769 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20d52ceb not in the list
08-04 10:46:13.663  6705  6769 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:46:13.664  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.665  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.665  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.668  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:13.668  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:13.669  6705  6769 D BluetoothLeScanner: could not find callback wrapper
08-04 10:46:13.669  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 10:46:13.669  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:13.669  6705  6769 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20d52ceb not in the list
08-04 10:46:13.670  6705  6769 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-04 10:46:13.671  6705  6769 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:46:13.671  6705  6769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:46:13.671  6705  6769 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:46:13.671  6705  6769 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:13.671  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.671  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.671  6705  6769 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10a1183a not in the list
08-04 10:46:13.671  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:13.671  6705  6769 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20d52ceb not in the list
08-04 10:46:13.671  6705  6769 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:46:13.671  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.671  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.671  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.671  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.672  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:13.672  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:13.673  6705  6769 D BluetoothLeScanner: could not find callback wrapper
08-04 10:46:13.673  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 10:46:13.673  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:13.673  6705  6769 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20d52ceb not in the list
08-04 10:46:13.674  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-04 10:46:13.674  6705  6769 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:46:13.674  6705  6769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:46:13.675  6705  6769 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:46:13.675  6705  6769 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:13.675  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.675  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.675  6705  6769 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10a1183a not in the list
08-04 10:46:13.675  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:13.675  6705  6769 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20d52ceb not in the list
08-04 10:46:13.675  6705  6769 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:46:13.675  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.675  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.675  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.675  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.675  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:13.675  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:13.676  6705  6769 D BluetoothLeScanner: could not find callback wrapper
08-04 10:46:13.676  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 10:46:13.676  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:13.676  6705  6769 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20d52ceb not in the list
08-04 10:46:13.676  6705  6769 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-04 10:46:13.676  6705  6769 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:46:13.676  6705  6769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:46:13.676  6705  6769 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:46:13.677  6705  6769 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:13.677  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.677  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.677  6705  6769 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10a1183a not in the list
08-04 10:46:13.677  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:13.677  6705  6769 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20d52ceb not in the list
08-04 10:46:13.677  6705  6769 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:46:13.677  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.677  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.677  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.677  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.677  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:13.677  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:13.678  6705  6769 D BluetoothLeScanner: could not find callback wrapper
08-04 10:46:13.678  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 10:46:13.678  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:13.678  6705  6769 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20d52ceb not in the list
08-04 10:46:13.679  6705  6769 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-04 10:46:13.679  6705  6769 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:46:13.679  6705  6769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:46:13.679  6705  6769 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:46:13.679  6705  6769 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:13.679  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.679  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.679  6705  6769 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10a1183a not in the list
08-04 10:46:13.679  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:13.679  6705  6769 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20d52ceb not in the list
08-04 10:46:13.679  6705  6769 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:46:13.679  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.679  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.679  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.679  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.680  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:13.680  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:13.680  6705  6769 D BluetoothLeScanner: could not find callback wrapper
08-04 10:46:13.680  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 10:46:13.680  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:13.680  6705  6769 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20d52ceb not in the list
08-04 10:46:13.681  6705  6769 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-04 10:46:13.681  6705  6769 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-04 10:46:13.681  6705  6769 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-04 10:46:13.681  6705  6769 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-04 10:46:13.681  6705  6769 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-04 10:46:13.681  6705  6769 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-04 10:46:13.681  6705  6769 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:46:13.681  6705  6769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:46:13.681  6705  6769 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:46:13.681  6705  6769 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:13.681  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.681  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.682  6705  6769 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10a1183a not in the list
08-04 10:46:13.682  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:13.682  6705  6769 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20d52ceb not in the list
08-04 10:46:13.682  6705  6769 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:46:13.682  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.682  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.682  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.682  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.682  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:13.682  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:13.683  6705  6769 D BluetoothLeScanner: could not find callback wrapper
08-04 10:46:13.683  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 10:46:13.683  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:13.683  6705  6769 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20d52ceb not in the list
08-04 10:46:13.683  6705  6769 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-04 10:46:13.683  6705  6769 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-04 10:46:13.683  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-04 10:46:13.685  6705  6769 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-04 10:46:13.685  6705  6769 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-04 10:46:13.685  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-04 10:46:13.685  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-04 10:46:13.685  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-04 10:46:13.685  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-04 10:46:13.685  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-04 10:46:13.685  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-04 10:46:13.685  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-04 10:46:13.685  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-04 10:46:13.685  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-04 10:46:13.685  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-04 10:46:13.685  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-04 10:46:13.685  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-04 10:46:13.685  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-04 10:46:13.685  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-04 10:46:13.685  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-04 10:46:13.685  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-04 10:46:13.685  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-04 10:46:13.685  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-04 10:46:13.685  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-04 10:46:13.685  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-04 10:46:13.685  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-04 10:46:13.686  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-04 10:46:13.686  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-04 10:46:13.686  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-04 10:46:13.686  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-04 10:46:13.686  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-04 10:46:13.686  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-04 10:46:13.686  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-04 10:46:13.686  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-04 10:46:13.686  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-04 10:46:13.686  6705  6769 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-04 10:46:13.686  6705  6769 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-04 10:46:13.686  6705  6769 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-04 10:46:13.686  6705  6769 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-04 10:46:13.686  6705  6769 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-04 10:46:13.686  6705  6769 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-04 10:46:13.686  6705  6769 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-04 10:46:13.686  6705  6769 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-04 10:46:13.686  6705  6769 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-04 10:46:13.690  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-04 10:46:13.691  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-04 10:46:13.691  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-04 10:46:13.691  6705  6769 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-04 10:46:13.691  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-04 10:46:13.691  6705  6769 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-04 10:46:13.691  6705  6769 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-04 10:46:13.691  6705  6769 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-04 10:46:13.692  6705  6769 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:46:13.692  6705  6769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:46:13.692  6705  6769 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:46:13.692  6705  6769 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-04 10:46:13.692  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.692  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.692  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-04 10:46:13.693  6705  6769 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10a1183a not in the list
08-04 10:46:13.693  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:13.693  6705  6769 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20d52ceb not in the list
08-04 10:46:13.693  6705  6769 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:46:13.693  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.693  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.693  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.693  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.694  6705  6777 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 841)
08-04 10:46:13.699  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:13.699  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:13.699  6705  6769 D BluetoothLeScanner: could not find callback wrapper
08-04 10:46:13.699  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 10:46:13.699  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:13.699  6705  6769 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20d52ceb not in the list
08-04 10:46:13.700  6705  6769 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-04 10:46:13.700  6705  6769 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:46:13.700  6705  6769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:46:13.700  6705  6769 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:46:13.702  6705  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 841
08-04 10:46:13.702  6705  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 841)
08-04 10:46:13.702  6705  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 841)
08-04 10:46:13.702  6705  6769 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:13.702  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.702  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.704  6705  6769 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10a1183a not in the list
08-04 10:46:13.704  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:13.704  6705  6769 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20d52ceb not in the list
08-04 10:46:13.704  6705  6769 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:46:13.704  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.704  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.704  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.704  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.705  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:13.705  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:13.705  6705  6769 D BluetoothLeScanner: could not find callback wrapper
08-04 10:46:13.705  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 10:46:13.705  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:13.705  6705  6769 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20d52ceb not in the list
08-04 10:46:13.706  6705  6769 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-04 10:46:13.707  6705  6769 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:46:13.708  6705  6769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:46:13.708  6705  6769 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:46:13.708  6705  6769 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:13.708  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.708  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.708  6705  6769 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10a1183a not in the list
08-04 10:46:13.708  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:13.708  6705  6769 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20d52ceb not in the list
08-04 10:46:13.708  6705  6769 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:46:13.708  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.708  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.708  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.708  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.709  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:13.709  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:13.709  6705  6769 D BluetoothLeScanner: could not find callback wrapper
08-04 10:46:13.709  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 10:46:13.710  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:13.710  6705  6769 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20d52ceb not in the list
08-04 10:46:13.712  6705  6769 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-04 10:46:13.712  6705  6769 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-04 10:46:13.712  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-04 10:46:13.712  6705  6769 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-04 10:46:13.712  6705  6769 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-04 10:46:13.712  6705  6769 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-04 10:46:13.712  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-04 10:46:13.712  6705  6769 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-04 10:46:13.712  6705  6769 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-04 10:46:13.712  6705  6769 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-04 10:46:13.712  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-04 10:46:13.712  6705  6769 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-04 10:46:13.712  6705  6769 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:46:13.712  6705  6769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:46:13.712  6705  6769 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:46:13.718  6705  6769 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:13.718  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.718  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.718  6705  6769 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10a1183a not in the list
08-04 10:46:13.718  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:13.718  6705  6769 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20d52ceb not in the list
08-04 10:46:13.718  6705  6769 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:46:13.718  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.718  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.718  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.719  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.719  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:13.719  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:13.721  6705  6769 D BluetoothLeScanner: could not find callback wrapper
08-04 10:46:13.721  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 10:46:13.721  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:13.721  6705  6769 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20d52ceb not in the list
08-04 10:46:13.722  6705  6769 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:13.722  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.722  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.722  6705  6769 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10a1183a not in the list
08-04 10:46:13.722  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:13.722  6705  6769 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20d52ceb not in the list
08-04 10:46:13.722  6705  6769 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:46:13.722  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.722  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.722  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:13.722  6705  6769 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20d52ceb not in the list
08-04 10:46:13.722  6705  6769 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:13.722  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.722  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.722  6705  6769 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10a1183a not in the list
08-04 10:46:13.722  6705  6769 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:46:13.722  6705  6769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:46:13.722  6705  6769 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:46:13.723  6705  6769 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:13.723  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.723  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.723  6705  6769 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10a1183a not in the list
08-04 10:46:13.723  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:13.723  6705  6769 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20d52ceb not in the list
08-04 10:46:13.723  6705  6769 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:46:13.723  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.723  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.723  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.723  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.724  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:13.724  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:13.725  6705  6769 D BluetoothLeScanner: could not find callback wrapper
08-04 10:46:13.725  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 10:46:13.725  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:13.725  6705  6769 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20d52ceb not in the list
08-04 10:46:13.726  6705  6769 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-04 10:46:13.726  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 10:46:13.727  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-04 10:46:13.727  6705  6769 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-04 10:46:13.727  6705  6769 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-04 10:46:13.728  6705  6705 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-04 10:46:13.728  6705  6769 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-04 10:46:13.728  6705  6769 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-04 10:46:13.729  6705  6769 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:13.729  6705  6769 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-04 10:46:13.729  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-04 10:46:13.729  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-04 10:46:13.729  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.729  6705  6769 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-04 10:46:13.729  6705  6705 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-04 10:46:13.730  6705  6769 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10a1183a not in the list
08-04 10:46:13.730  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:13.730  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-04 10:46:13.730  6705  6769 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-04 10:46:13.730  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-04 10:46:13.730  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-04 10:46:13.731  6705  6769 D BluetoothLeScanner: could not find callback wrapper
08-04 10:46:13.731  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 10:46:13.731  6705  6769 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-04 10:46:13.731  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.731  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.731  6705  6779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-04 10:46:13.731  6705  6779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-04 10:46:13.732  6705  6769 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 10:46:13.733  6705  6705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 10:46:13.733  6705  6705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 10:46:13.733  6705  6705 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-04 10:46:13.733  6705  6705 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 10:46:13.733  6705  6769 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20d52ceb not in the list
08-04 10:46:13.733  6705  6769 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:46:13.733  6705  6769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:46:13.733  6705  6769 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:46:13.733  6705  6769 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:13.733  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.733  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.733  6705  6769 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10a1183a not in the list
08-04 10:46:13.733  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:13.733  6705  6769 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20d52ceb not in the list
08-04 10:46:13.733  6705  6769 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:46:13.733  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.733  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.733  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.734  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.734  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:13.734  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:13.734  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:13.734  6705  6769 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20d52ceb not in the list
08-04 10:46:13.735  6705  6769 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-04 10:46:13.735  6705  6769 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-04 10:46:13.735  6705  6769 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setI,nsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-04 10:46:13.735  6705  6769 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-04 10:46:13.735  6705  6769 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:46:13.735  6705  6769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:46:13.735  6705  6769 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:46:13.737  6705  6769 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:13.737  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.737  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.737  6705  6769 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10a1183a not in the list
08-04 10:46:13.737  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:13.737  6705  6769 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20d52ceb not in the list
08-04 10:46:13.737  6705  6769 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:46:13.737  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 10:46:13.737  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.737  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.737  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.738  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:13.738  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:13.738  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:13.738  6705  6769 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20d52ceb not in the list
08-04 10:46:13.739  1039  2020 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 10:46:13.739  1039  2003 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 10:46:13.740  1039  1054 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 10:46:13.740  6705  6769 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:46:13.740  6705  6769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:46:13.740  6705  6769 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:46:13.740  6705  6769 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:13.740  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.740  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 10:46:13.740  6705  6769 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10a1183a not in the list
08-04 10:46:13.740  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:13.740  6705  6769 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20d52ceb not in the list
08-04 10:46:13.740  6705  6769 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:46:13.740  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.740  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.740  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.740  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.741  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:13.741  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-04 10:46:13.741  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:13.741  6705  6769 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20d52ceb not in the list
08-04 10:46:13.742  6705  6769 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:46:13.742  6705  6769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:46:13.742  6705  6769 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-04 10:46:13.742  6705  6769 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:13.742  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:13.742  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.742  6705  6769 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10a1183a not in the list
08-04 10:46:13.742  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:13.742  6705  6769 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20d52ceb not in the list
08-04 10:46:13.742  6705  6769 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:46:13.742  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-04 10:46:13.742  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.742  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-04 10:46:13.742  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:13.743  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:13.743  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:13.743  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:13.743  6705  6769 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20d52ceb not in the list
08-04 10:46:13.744  6705  6769 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-04 10:46:13.744  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-04 10:46:13.744  6705  6769 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,08-04 10:46:13.744  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-04 10:46:13.744  6705  6769 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-04 10:46:13.744  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-04 10:46:13.745  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-04 10:46:13.745  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-04 10:46:13.746  6705  6769 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-04 10:46:13.746  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-04 10:46:13.746  6705  6769 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-04 10:46:13.746  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-04 10:46:13.746  6705  6769 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-04 10:46:13.746  6705  6769 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-04 10:46:13.747  6705  6769 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-04 10:46:13.747  6705  6769 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-04 10:46:13.747  6705  6769 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,08-04 10:46:13.747  6705  6769 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-04 10:46:13.747  6705  6769 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-04 10:46:13.747  6705  6769 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-04 10:46:13.748  6705  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 10:46:13.748  6705  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3a4dba60 added. We now have 2 listener(s)
08-04 10:46:13.748  6705  6769 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 10:46:13.751  6705  6769 D BluetoothAdapter: enable(): BT is already enabled..!
08-04 10:46:13.752  1039  1973 D WifiServiceImplEx: setWifiEnabled: true pid=6705, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-04 10:46:13.752  1039  1973 D WifiService: setWifiEnabled: true pid=6705, uid=10118
08-04 10:46:13.752  1039  1973 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-04 10:46:13.753  6705  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 10:46:13.753  6705  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@821cb19 added. We now have 3 listener(s)
08-04 10:46:13.753  6705  6769 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 10:46:13.755  6705  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 10:46:13.755  6705  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@309b47de added. We now have 4 listener(s)
08-04 10:46:13.755  6705  6769 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 10:46:13.757  6705  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 10:46:13.757  6705  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@35b76dbf added. We now have 5 listener(s)
08-04 10:46:13.757  6705  6769 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 10:46:13.758  1039  1983 D WifiServiceImplEx: setWifiEnabled: false pid=6705, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-04 10:46:13.758  1039  1983 D WifiService: setWifiEnabled: false pid=6705, uid=10118
08-04 10:46:13.758  1039  1983 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-04 10:46:13.766  1039  1039 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-04 10:46:13.766  1039  1039 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-04 10:46:13.766  1039  1039 D Ulp_jni : JNI:system_update. Event-4
,08-04 10:46:13.768  1039  1526 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-04 10:46:13.768  1039  1526 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-04 10:46:13.768  1039  1526 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-04 10:46:13.768  1039  1526 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-04 10:46:13.769  1039  1526 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-04 10:46:13.769  1039  1526 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-04 10:46:13.769  1039  1526 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-04 10:46:13.769  1039  1526 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-04 10:46:13.769  1039  1526 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-04 10:46:13.769  1039  1526 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-04 10:46:13.770  1039  1893 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 10:46:13.771  1039  1893 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@35fc80b8 mBinding = false
08-04 10:46:13.775  1039  1526 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-04 10:46:13.775  1039  1526 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-04 10:46:13.775  2740  2740 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-04 10:46:13.775  1039  1525 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:13.775  1039  1525 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:13.776  1039  1526 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-04 10:46:13.776  1039  1526 D WifiNative-wlan0: doBoolean: SET ps 1
08-04 10:46:13.776  1039  1526 D WifiNative-wlan0: SET ps 1: returned true
08-04 10:46:13.776  1039  2851 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:13.776   315   897 D CommandListener: Clearing all IP addresses on wlan0
08-04 10:46:13.782  1039  1121 D BluetoothManagerService: Message: 2
08-04 10:46:13.786  1039  1121 D BluetoothManagerService: Sending off request.
08-04 10:46:13.787  3868  3978 D LGBluetoothServiceAdapter: [BTUI] Precleanup
,08-04 10:46:13.790  3868  3942 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-04 10:46:13.790  3868  3942 D BluetoothAdapterProperties: Setting state to 13
08-04 10:46:13.790  3868  3942 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-04 10:46:13.792  3868  3942 D BluetoothAdapterProperties: onBluetoothDisable()
08-04 10:46:13.792  3868  3942 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-04 10:46:13.793  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 10:46:13.794  1039  1039 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-04 10:46:13.795  1039  1039 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-04 10:46:13.795  1039  1039 D Ulp_jni : JNI:system_update. Event-4
08-04 10:46:13.801  1039  1121 D BluetoothManagerService: Message: 60
08-04 10:46:13.801  1039  1121 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-04 10:46:13.801  1039  1121 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,08-04 10:46:13.802  3868  3946 D BluetoothAdapterProperties: Scan Mode:20
08-04 10:46:13.802  3868  3942 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-04 10:46:13.804  3868  4172 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-04 10:46:13.804  3868  4172 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-04 10:46:13.804  3868  4172 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-04 10:46:13.804  3868  4172 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-04 10:46:13.804  3868  4172 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-04 10:46:13.804  3868  4172 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-04 10:46:13.804  3868  4172 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-04 10:46:13.804  3868  4172 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-04 10:46:13.804  3868  4178 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-04 10:46:13.805  3868  4200 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-04 10:46:13.805  3868  4205 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-04 10:46:13.805  3868  4016 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-04 10:46:13.805  3868  4016 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-04 10:46:13.804  3868  3942 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-04 10:46:13.805  3868  4198 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-04 10:46:13.811  3868  4016 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-04 10:46:13.811  3868  4016 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-04 10:46:13.811  3868  4016 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-04 10:46:13.811  3868  4016 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-04 10:46:13.811  3868  4016 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 10:46:13.811  3868  4016 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-04 10:46:13.811  3868  4016 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-04 10:46:13.811  3868  4016 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-04 10:46:13.811  3868  4016 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-04 10:46:13.811  3868  4016 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-04 10:46:13.811  3868  4016 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-04 10:46:13.811  3868  4016 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-04 10:46:13.815  1039  1532 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-04 10:46:13.816  1039  1532 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,08-04 10:46:13.821  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:46:13.821  6705  6769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 10:46:13.821  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:13.821  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:13.821  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:46:13.821  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 10:46:13.821  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:46:13.821  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 10:46:13.821  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 10:46:13.822  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:46:13.822  6705  6769 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 10:46:13.822  6705  6769 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 10:46:13.824  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:46:13.824  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:46:13.824  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:13.824  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:13.824  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:46:13.824  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 10:46:13.824  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:46:13.824  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:46:13.824  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 10:46:13.825  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:46:13.828  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:46:13.828  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:46:13.828  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:13.828  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:13.828  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:46:13.828  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 10:46:13.828  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:46:13.828  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:46:13.828  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 10:46:13.828  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multipl,e advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:46:13.828  6705  6705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 10:46:13.830  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:46:13.844  1039  1113 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6796 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-04 10:46:13.848  1930  1930 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:13.849  1590  1590 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-04 10:46:13.851  3868  3868 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:13.851  3868  3868 D BluetoothMapService: STATE_TURNING_OFF
08-04 10:46:13.851  3868  3868 V BluetoothMapService: Handler(): got msg=4
08-04 10:46:13.851  3868  3868 D BluetoothMapService: MAP Service closeService in
08-04 10:46:13.851  3868  3868 D BluetoothMapMasInstance: MAP Service shutdown
08-04 10:46:13.851  3868  3868 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-04 10:46:13.852  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:46:13.852  3868  3868 V BluetoothMapService: MAP Service closeService out
08-04 10:46:13.852  3868  3868 V BtOppService: Receiver DISABLED_ACTION 
08-04 10:46:13.852  3868  3868 I BtOppRfcommListener: stopping Accept Thread
08-04 10:46:13.853  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:46:13.854  3868  3868 V BtOppRfcommListener: close mBtServerSocket
08-04 10:46:13.854  3868  3868 V BtOppRfcommListener: waiting for thread to terminate
08-04 10:46:13.854  3868  4198 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-04 10:46:13.855  3868  3868 V BtOppRfcommListener: done waiting for thread to terminate
08-04 10:46:13.863  1039  1532 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-04 10:46:13.863  1039  1532 D DSQN    : disableDataServiceNotify
08-04 10:46:13.863  1039  1532 D DSQN    : stop dsqn bin
08-04 10:46:13.874  1039  1532 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-04 10:46:13.874  1039  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 10:46:13.874  1039  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-04 10:46:13.874  1039  1532 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-04 10:46:13.874  1039  1532 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-04 10:46:13.875  1039  1532 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-04 10:46:13.875  1039  1532 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-04 10:46:13.875  1039  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-04 10:46:13.875  1039  2848 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:13.875  1039  2848 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:13.875  1039  2848 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-04 10:46:13.875  1590  2055 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,08-04 10:46:13.881  6705  6777 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-04 10:46:13.882  6705  6777 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 841)
08-04 10:46:13.889  1039  1113 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6815 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-04 10:46:13.889  1039  1039 D WifiHS20: hidePasspointNotification off =false
08-04 10:46:13.890  1930  1930 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-04 10:46:13.891  1039  1039 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 10:46:13.891  1039  1039 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 10:46:13.891  1039  1039 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-04 10:46:13.893  3868  3868 V BtOppService: onDestroy
08-04 10:46:13.893  1039  1532 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-04 10:46:13.893  1039  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-04 10:46:13.893  1039  1532 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-04 10:46:13.893  1039  1532 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 10:46:13.893  1039  1532 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 10:46:13.893  1039  1532 D NetworkManagementService: Removing idletimer
08-04 10:46:13.893  1039  1532 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 10:46:13.894  3868  3868 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-04 10:46:13.895  1840  1840 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 10:46:13.895  1840  1840 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-04 10:46:13.898  1039  1526 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 10:46:13.898  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:13.898  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-04 10:46:13.898  1039  1526 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 10:46:13.898  1039  1526 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 10:46:13.898  1039  1525 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:13.898  1039  1525 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:13.899  1039  1525 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@160b6d38
08-04 10:46:13.899  1039  1526 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 10:46:13.899  1039  1526 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 10:46:13.899  1039  1525 D LGWifiP2pService: P2pDisablingState
08-04 10:46:13.899  1039  1526 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 10:46:13.899  1039  1525 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:13.899  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-04 10:46:13.899  1039  1525 D LGWifiP2pService: p2p socket connection lost
08-04 10:46:13.899  1039  1525 D LGWifiP2pService: P2pDisabledState
08-04 10:46:13.899  1039  1526 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-04 10:46:13.899  1039  1524 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-04 10:46:13.900  1039  1526 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 10:46:13.900  1039  1039 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-04 10:46:13.900  1039  1524 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-04 10:46:13.901  1039  1526 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 10:46:13.901  1039  1526 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 10:46:13.901  1039  1526 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 10:46:13.901  1039  1526 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-04 10:46:13.901  1039  1526 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-04 10:46:13.902  1039  1525 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:13.902  1039  1525 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:13.902  1039  1526 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-04 10:46:13.902  2740  2740 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-04 10:46:13.902  1930  1930 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-04 10:46:13.902  1930  1930 D WfdsService: WifiP2pState is changed : false
08-04 10:46:13.902  1930  2236 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-04 10:46:13.902  1930  2236 D WfdsService: Set the WFDS Monitor: false
08-04 10:46:13.902  1039  1526 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-04 10:46:13.902  1039  1526 D WifiNative-wlan0: doBoolean: SET ps 1
08-04 10:46:13.903  1039  1526 D WifiNative-wlan0: SET ps 1: returned true
08-04 10:46:13.903  1930  2236 D WfdsMonitor: WFDS Monitor is stopped
08-04 10:46:13.903   315   897 D CommandListener: Clearing all IP addresses on wlan0
08-04 10:46:13.903  1930  2782 D CtrlSupplicant: Received on exit socket, terminate
08-04 10:46:13.903  1930  2782 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-04 10:46:13.903  1930  2782 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-04 10:46:13.903  1930  2782 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-04 10:46:13.904  1930  2236 D WfdsService: STATE : WfdsDisabledState - enter
08-04 10:46:13.904  1930  2236 W WfdsService: DefaultState - msg [9445378] is not handled
,08-04 10:46:13.904  1930  2241 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-04 10:46:13.905  1039  1526 D WifiNative-p2p0: doBoolean: TERMINATE
08-04 10:46:13.906  1039  1526 D WifiNative-p2p0: TERMINATE: returned true
08-04 10:46:13.906  1039  1526 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-04 10:46:13.906  1039  1526 E WifiStateMachine: useWiFiOffloading() : false
08-04 10:46:13.906  1039  1526 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-04 10:46:13.908  1930  1930 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-04 10:46:13.911  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:46:13.911  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:46:13.911  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:13.911  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:13.911  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 10:46:13.911  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 10:46:13.911  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:46:13.911  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:46:13.911  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 10:46:13.912  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:46:13.912  6705  6705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 10:46:13.917  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:46:13.917  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:46:13.917  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:13.917  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:13.917  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 10:46:13.917  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 10:46:13.917  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:46:13.917  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:46:13.917  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 10:46:13.917  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-04 10:46:13.917  6705  6705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-04 10:46:13.938  1590  1590 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-04 10:46:13.939  6815  6815 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-04 10:46:13.939  6815  6815 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-04 10:46:13.939  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 10:46:13.940  6815  6815 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-04 10:46:13.940  6815  6815 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-04 10:46:13.940  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 10:46:13.941  6815  6815 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-04 10:46:13.941  6815  6815 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-04 10:46:13.946  1039  1766 I art     : Explicit concurrent mark sweep GC freed 29917(1524KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.638ms total 137.660ms
08-04 10:46:13.946  1039  1532 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-04 10:46:13.947  1039  1039 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-04 10:46:13.947  1039  1039 D WifiHS20: hidePasspointNotification off =false
08-04 10:46:13.947  1039  1039 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 10:46:13.947  1039  1039 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 10:46:13.947  1039  1039 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-04 10:46:13.947  1039  1039 D WifiScanningService: SCAN_AVAILABLE : 1
08-04 10:46:13.947  1039  1544 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:13.948  1039  1039 D RttService: SCAN_AVAILABLE : 1
08-04 10:46:13.948  1039  1039 D WifiHS20: hidePasspointNotification off =false
08-04 10:46:13.948  1039  1039 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 10:46:13.948  1039  1039 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 10:46:13.948  1039  1039 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-04 10:46:13.948  1039  1545 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:13.949  1039  1039 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-04 10:46:13.949  1039  1039 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-04 10:46:13.949  1039  1039 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-04 10:46:13.949  1039  1039 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-04 10:46:13.949  1039  1039 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-04 10:46:13.949  1039  1039 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-04 10:46:13.949  1039  1039 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-04 10:46:13.949  1039  1039 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DI,SCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-04 10:46:13.950  1039  1039 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-04 10:46:13.973  1590  1590 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-04 10:46:13.974  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 10:46:13.974  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 10:46:13.974  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:13.974  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-04 10:46:13.976  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-04 10:46:13.991  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-04 10:46:13.991  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-04 10:46:13.992  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 10:46:13.993  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 10:46:13.993  6796  6796 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-04 10:46:13.993  6796  6796 W LG Account v2.2: No ProfileInfo entries
08-04 10:46:13.994  6796  6796 I LG Account v2.2: isEnabled: false
08-04 10:46:13.994  6796  6796 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-04 10:46:13.994  6796  6796 I Feature : [Lifetracker]Country: EU
08-04 10:46:13.994  6796  6796 I Feature : [Lifetracker]Operator: OPEN
08-04 10:46:13.994  6796  6796 I Feature : [Lifetracker]Ranking support: false
08-04 10:46:13.994  6796  6796 I Feature : [Lifetracker]Comfort support: false
08-04 10:46:13.994  6796  6796 I Feature : [Lifetracker]Accessory: true
08-04 10:46:13.994  6796  6796 I Feature : [Lifetracker]Health device: true
08-04 10:46:13.994  6796  6796 I Feature : [Lifetracker]Extra Pedometer: false
08-04 10:46:13.994  6796  6796 I Feature : [Lifetracker]Blood glucose device: false
08-04 10:46:13.994  6796  6796 I Feature : [Lifetracker]Device Number: 3
08-04 10:46:13.995  1039  2851 D DhcpStateMachine: StoppedState
08-04 10:46:13.995  1039  2851 D DhcpStateMachine: StoppedState{ when=-92ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:13.995  1039  1526 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-04 10:46:13.996  1039  1526 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-04 10:46:14.002  6409  6409 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-04 10:46:14.014  2740  2740 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-04 10:46:14.014  2740  2740 I wpa_supplicant: monitor socket send errors count : 1
08-04 10:46:14.014  2740  2740 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1930-2\x00 that cannot receive messages
08-04 10:46:14.015  1039  2771 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-04 10:46:14.015  1039  2771 D WifiMonitor: Dropping event because (p2p0) is stopped
,08-04 10:46:14.033  1039  1973 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6834 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-04 10:46:14.034  1039  1973 I ActivityManager: Killing 6230:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-04 10:46:14.037  6815  6815 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-04 10:46:14.046   347   347 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 215us total 13.251ms
,08-04 10:46:14.049  2740  2740 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-04 10:46:14.050  1039  1121 D Tethering: InitialState.processMessage what=4
08-04 10:46:14.050  2740  2740 W wpa_supplicant: USIM:  scard_deinit function
08-04 10:46:14.051  1039  2771 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-04 10:46:14.051  1039  2771 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-04 10:46:14.051  1039  2771 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-04 10:46:14.051  1039  2771 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-04 10:46:14.051  1039  2771 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-04 10:46:14.051  1039  2771 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-04 10:46:14.052  1039  1526 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=131461
08-04 10:46:14.052  1039  1526 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=131461
08-04 10:46:14.053  1039  1526 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=131462  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-04 10:46:14.053  1039  1526 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=131462  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-04 10:46:14.058   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 200us total 11.392ms
,08-04 10:46:14.067   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 186us total 9.044ms
,08-04 10:46:14.083  1039  2003 W libprocessgroup: failed to open /acct/uid_10014/pid_6230/cgroup.procs: No such file or directory
08-04 10:46:14.084  1039  1121 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-04 10:46:14.086  3868  3868 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-04 10:46:14.086  3868  3868 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:14.086  3868  3868 V BluetoothPbapReceiver: ***********state = 13
08-04 10:46:14.087  1039  1526 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-04 10:46:14.088  3868  3868 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-04 10:46:14.088  1039  1526 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-04 10:46:14.090  3868  3868 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:14.090  3868  3868 V BluetoothPbapService: state: 13
08-04 10:46:14.090  3868  3868 V BluetoothPbapService: Pbap Service closeService in
08-04 10:46:14.090  1039  1121 D BluetoothManagerService: Message: 20
08-04 10:46:14.090  1039  1121 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1a96d782:true
08-04 10:46:14.091  3868  3868 V BluetoothPbapService: successfully stopped pbap service
08-04 10:46:14.092  3868  3868 V BluetoothPbapService: Pbap Service closeService out
08-04 10:46:14.092  2170  2170 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-04 10:46:14.092  3868  3868 V BluetoothPbapService: Pbap Service onDestroy
08-04 10:46:14.092  3868  3868 V BluetoothPbapService: Pbap Service closeService in
08-04 10:46:14.092  3868  3868 V BluetoothPbapService: Pbap Service closeService out
08-04 10:46:14.092  3868  3868 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-04 10:46:14.098  1039  1121 D BluetoothManagerService: Message: 30
08-04 10:46:14.105  1039  1121 D BluetoothManagerService: Message: 30
,08-04 10:46:14.107  6815  6815 D LocalBluetoothProfileManager: Adding local MAP profile
08-04 10:46:14.108  6815  6815 D BluetoothMap: Create BluetoothMap proxy object
08-04 10:46:14.109  1039  1121 D BluetoothManagerService: Message: 30
,08-04 10:46:14.111  1039  1121 D BluetoothManagerService: Message: 30
08-04 10:46:14.112  6815  6815 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-04 10:46:14.113  6815  6815 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-04 10:46:14.120  2740  2740 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-04 10:46:14.120  1039  2771 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-04 10:46:14.120  1039  2771 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-04 10:46:14.120  1039  2771 D WifiMonitor: Disconnecting from the supplicant, no more events
08-04 10:46:14.121  1039  1526 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-04 10:46:14.125  6834  6834 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-04 10:46:14.129  6834  6834 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-04 10:46:14.130  6834  6834 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-04 10:46:14.131  6815  6815 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
08-04 10:46:14.132  1039  1983 I ActivityManager: Killing 2149:com.lge.music/u0a34 (adj 15): empty #17
08-04 10:46:14.137  6815  6815 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-04 10:46:14.151   322  1372 V AudioFlinger: 2149 died, releasing its sessions
08-04 10:46:14.151   322  1372 V AudioFlinger:  pid 1840 @ 0
08-04 10:46:14.151   322  1372 V AudioFlinger:  pid 3467 @ 1
08-04 10:46:14.151   322  1372 V AudioFlinger:  pid 3467 @ 2
,08-04 10:46:14.178  1039  1563 W libprocessgroup: failed to open /acct/uid_10034/pid_2149/cgroup.procs: No such file or directory
,08-04 10:46:14.194  6815  6815 D DockEventReceiver: finishStartingService: stopping service
,08-04 10:46:14.219  6815  6815 D BluetoothInputDevice: Proxy object connected
08-04 10:46:14.220  6815  6815 D HidProfile: Bluetooth service connected
,08-04 10:46:14.221  6815  6815 D BluetoothPan: BluetoothPAN Proxy object connected
08-04 10:46:14.222  6815  6815 D PanProfile: Bluetooth service connected
08-04 10:46:14.224  6815  6815 D BluetoothMap: Proxy object connected
08-04 10:46:14.224  6815  6815 D MapProfile: Bluetooth service connected
08-04 10:46:14.224  6815  6815 D BluetoothMap: getConnectedDevices()
08-04 10:46:14.225  6815  6815 D BluetoothMap: Bluetooth is Not enabled
08-04 10:46:14.226  1039  1526 D WifiOffDelayIfNotUsed: stopMonitoring
08-04 10:46:14.226  1039  1526 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-04 10:46:14.226  1039  1526 E WifiStateMachine: useWiFiOffloading() : false
08-04 10:46:14.226  1039  1526 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-04 10:46:14.229  1930  1930 D WfdsService: Supplicant Connection state is changed : false
08-04 10:46:14.230  1930  2236 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-04 10:46:14.230  1930  2236 D WfdsService: Set the WFDS Monitor: false
08-04 10:46:14.230  1930  2236 D WfdsMonitor: WFDS Monitor is stopped
08-04 10:46:14.230  1930  1930 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-04 10:46:14.232  1039  1039 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-04 10:46:14.233  1039  1530 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
,08-04 10:46:14.233  1039  1530 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-04 10:46:14.233  6705  6705 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-04 10:46:14.234  2453  2453 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 10:46:14.236  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:46:14.236  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:46:14.236  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:14.236  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:14.236  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 10:46:14.236  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 10:46:14.236  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:46:14.236  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:46:14.236  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 10:46:14.237  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 10:46:14.242  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:46:14.242  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:46:14.242  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:14.242  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:14.242  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 10:46:14.242  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 10:46:14.242  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:46:14.242  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:46:14.242  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 10:46:14.245  6815  6815 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-04 10:46:14.287  6815  6815 D LgDataFeature: LgDataFeature() Constructor: none
08-04 10:46:14.287  6815  6815 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-04 10:46:14.298  6815  6815 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 10:46:14.300  6815  6815 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-04 10:46:14.303  6815  6815 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-04 10:46:14.309  6815  6815 D BluetoothPermissionRequest: onReceive
08-04 10:46:14.316  6815  6815 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-04 10:46:14.325  6815  6815 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-04 10:46:14.326  1039  2020 I ActivityManager: Killing 6475:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-04 10:46:14.372  1039  1055 W libprocessgroup: failed to open /acct/uid_10008/pid_6475/cgroup.procs: No such file or directory
,08-04 10:46:14.372  3868  3868 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-04 10:46:14.373  3868  3868 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-04 10:46:14.375  3868  3868 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-04 10:46:14.485  1039  2020 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6869 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-04 10:46:14.485  3868  3868 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:14.485  3868  3868 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-04 10:46:14.491  3868  3868 V BluetoothFtpService: Ftp Service onStartCommand
08-04 10:46:14.491  3868  3868 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:14.492  3868  3868 V BluetoothFtpService: Ftp Service closeService
08-04 10:46:14.492  3868  3868 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-04 10:46:14.494  3868  3868 V BluetoothFtpService: successfully stopped ftp service
08-04 10:46:14.495  3868  3868 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-04 10:46:14.495  3868  3868 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-04 10:46:14.495  3868  3868 V BluetoothSapReceiver: SapReceiver onReceive 
08-04 10:46:14.495  3868  3868 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:14.495  3868  3868 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-04 10:46:14.495  3868  3868 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-04 10:46:14.497  3868  3868 V BluetoothFtpService: Ftp Service onDestroy
08-04 10:46:14.497  3868  3868 V BluetoothFtpService: Ftp Service closeService
08-04 10:46:14.545  1039  1055 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6886 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-04 10:46:14.546  3868  3868 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:14.546  3868  3868 V BluetoothSapService: state: 13
,08-04 10:46:14.546  3868  3868 V BluetoothSapService: Stopping SAP server process
08-04 10:46:14.547  3868  3868 V BluetoothSapService: Sap Service closeSapService in
08-04 10:46:14.547  3868  3868 V BluetoothSapService: Close listen Socket : 
08-04 10:46:14.547  3868  3868 V BluetoothSapService: Close rfcomm Socket : 
08-04 10:46:14.548  3868  3868 V BluetoothSapService: Close sapd  Socket : 
08-04 10:46:14.550  3868  3868 V BluetoothSapService: Sap Service closeSapService out
08-04 10:46:14.550  3868  3868 V BluetoothSapService: Sap Service onDestroy
08-04 10:46:14.550  3868  3868 V BluetoothSapService: Sap Service closeSapService in
08-04 10:46:14.550  3868  3868 V BluetoothSapService: Close listen Socket : 
08-04 10:46:14.550  3868  3868 V BluetoothSapService: Close rfcomm Socket : 
08-04 10:46:14.550  3868  3868 V BluetoothSapService: Close sapd  Socket : 
08-04 10:46:14.551  3868  3868 V BluetoothSapService: Sap Service closeSapService out
08-04 10:46:14.591  6869  6869 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-04 10:46:14.623  6869  6869 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-04 10:46:14.634  6886  6886 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-04 10:46:14.649  1039  1928 I ActivityManager: Killing 6084:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-04 10:46:14.656  6869  6869 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-04 10:46:14.656  6869  6869 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-04 10:46:14.657  6869  6869 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-04 10:46:14.657  6869  6869 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-04 10:46:14.657  6869  6869 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-04 10:46:14.658  6869  6869 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-04 10:46:14.663  6869  6869 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
,08-04 10:46:14.681  1039  1563 W libprocessgroup: failed to open /acct/uid_10011/pid_6084/cgroup.procs: No such file or directory
,08-04 10:46:14.685  6869  6869 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-04 10:46:14.688  6869  6869 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-04 10:46:14.706  6869  6869 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-04 10:46:14.710  6869  6869 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-04 10:46:14.712  6409  6409 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-04 10:46:14.715  6869  6869 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-04 10:46:14.720  6834  6834 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-04 10:46:14.720  6834  6834 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-04 10:46:14.720  6834  6834 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-04 10:46:14.728  6815  6815 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-04 10:46:14.735  6815  6815 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 10:46:14.745  6869  6869 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-04 10:46:14.745  6869  6869 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-04 10:46:14.747  6869  6869 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-04 10:46:14.751  6409  6409 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-04 10:46:14.754  6834  6834 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-04 10:46:14.754  6834  6834 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-04 10:46:14.754  6834  6834 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-04 10:46:14.757  6815  6815 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-04 10:46:14.764  6815  6815 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 10:46:14.772  6869  6869 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-04 10:46:14.773  6869  6869 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-04 10:46:14.775  6869  6869 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-04 10:46:14.815  3868  3946 D bt_hci_bdroid: cleanup
08-04 10:46:14.815  3868  4021 I bt_lpm  : LPM is already off!!!
,08-04 10:46:14.816  3868  4139 I bt_userial_mct: exiting userial_read_thread
08-04 10:46:14.816  3868  4139 D bt_userial_mct: Leaving userial_evt_read_thread()
08-04 10:46:14.816  3868  4016 W bt-btif : ag scb idx 1 not allocated
08-04 10:46:14.816  3868  4016 E bt-btif : BTA AG is already disabled, ignoring ...
08-04 10:46:14.816  3868  4016 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-04 10:46:14.816  3868  4016 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 10:46:14.816  3868  4016 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-04 10:46:14.816  3868  4016 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-04 10:46:14.816  3868  4016 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-04 10:46:14.816  3868  4016 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-04 10:46:14.816  3868  4016 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-04 10:46:14.816  3868  4016 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 10:46:14.816  3868  4016 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-04 10:46:14.816  3868  4016 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-04 10:46:14.816  3868  4016 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-04 10:46:14.816  3868  4016 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-04 10:46:14.816  3868  4016 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-04 10:46:14.817  3868  4016 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 10:46:14.817  3868  4016 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-04 10:46:14.817  3868  4016 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-04 10:46:14.817  3868  4016 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-04 10:46:14.817  3868  4016 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-04 10:46:14.817  3868  4016 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-04 10:46:14.818  3868  3946 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-04 10:46:14.818  3868  4021 I bt_vendor: hw_epilog_process
08-04 10:46:14.819  3868  3946 D bt_hci_bdroid: cleanup Finalizing cleanup
08-04 10:46:14.819  3868  3946 D bt_userial_mct: userial_close
08-04 10:46:14.819  3868  3946 E bt_userial_mct: pthread_join() FAILED result:3
08-04 10:46:14.819  3868  3946 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-04 10:46:14.846  1039  1973 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6919 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-04 10:46:14.917  3868  3946 D bt_hci_bdroid: set_power 0
08-04 10:46:14.917  3868  3946 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-04 10:46:14.917  3868  3946 I bt_vendor: bluetooth satus is on
08-04 10:46:14.917  3868  3946 I bt_vendor: bt-vendor : resetting BT status
08-04 10:46:14.917  3868  3946 I bt_vendor: Starting hciattach daemon
08-04 10:46:14.917  3868  3946 I bt_vendor: try to set false
08-04 10:46:14.918  3868  3946 I bt_vendor: Starting hciattach daemon
08-04 10:46:14.918  3868  3946 I bt_vendor: try to set false
08-04 10:46:14.919  3868  3946 I bt_vendor: cleanup
08-04 10:46:14.919  3868  4016 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-04 10:46:14.947  1039  1364 V AlarmManager: RTC_WAKEUP set : Alarm{3fdb4356 type 0 when 1470300373123 com.android.vending} when 1470300373123
,08-04 10:46:14.952  3868  3946 I GKI_LINUX: GKI_exit_task 0 done
08-04 10:46:14.952  3868  3946 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-04 10:46:14.953  3868  3942 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-04 10:46:14.955  3868  3868 D HeadsetService: Received stop request...Stopping profile...
08-04 10:46:14.956  3868  3868 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-04 10:46:14.956  3868  3868 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-04 10:46:14.956  3868  3868 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ecda7fb
08-04 10:46:14.956  3868  3971 D HeadsetStateMachine: Exit Disconnected: -1
08-04 10:46:14.958  1840  1840 D BluetoothHeadset: Proxy object disconnected
08-04 10:46:14.958  1840  1840 D BluetoothHeadset: Proxy object disconnected
08-04 10:46:14.958  1039  1039 D BluetoothHeadset: Proxy object disconnected
08-04 10:46:14.958  1039  1039 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-04 10:46:14.959  1840  1840 D BluetoothHeadset: Proxy object disconnected
08-04 10:46:14.959  3868  3868 D A2dpService: Received stop request...Stopping profile...
08-04 10:46:14.959  3868  4001 D A2dpStateMachine: Exit Disconnected: -1
,08-04 10:46:14.962  3868  3942 D BluetoothAdapterState: Stopping profile services that were post enabled
08-04 10:46:14.962  3868  3868 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-04 10:46:14.964  3868  3868 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-04 10:46:14.964  3868  3868 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-04 10:46:14.964  3868  3868 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ecda7fb
08-04 10:46:14.965  1039  1039 D BluetoothA2dp: Proxy object disconnected
08-04 10:46:14.965  1039  1039 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-04 10:46:14.966  3868  3868 D HidService: Received stop request...Stopping profile...
08-04 10:46:14.966  3868  3868 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ecda7fb
08-04 10:46:14.967  3868  3868 D HeadsetStateMachine: Unbinding service...
08-04 10:46:14.967  6815  6815 D BluetoothInputDevice: Proxy object disconnected
08-04 10:46:14.967  6815  6815 D HidProfile: Bluetooth service disconnected
08-04 10:46:14.968  3868  3868 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-04 10:46:14.968  3868  3868 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-04 10:46:14.968  3868  3868 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-04 10:46:14.968  3868  3868 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-04 10:46:14.968  3868  3868 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-04 10:46:14.968  3868  3868 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-04 10:46:14.968  3868  3868 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-04 10:46:14.969  3868  3868 D HealthService: Received stop request...Stopping profile...
08-04 10:46:14.969  3868  3868 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ecda7fb
08-04 10:46:14.971  3868  3868 D PanService: Received stop request...Stopping profile...
08-04 10:46:14.971  3868  3868 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ecda7fb
,08-04 10:46:14.972  3868  3868 D BtGatt.DebugUtils: handleDebugAction() action=null
08-04 10:46:14.972  6815  6815 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-04 10:46:14.972  6815  6815 D PanProfile: Bluetooth service disconnected
08-04 10:46:14.973  3868  3868 D BtGatt.GattService: Received stop request...Stopping profile...
08-04 10:46:14.973  3868  3868 D BtGatt.GattService: stop()
08-04 10:46:14.974  3868  3868 D BtGatt.AdvertiseManager: advertise clients cleared
08-04 10:46:14.976  3868  3868 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ecda7fb
08-04 10:46:14.977  3868  3868 D BluetoothMapService: Received stop request...Stopping profile...
08-04 10:46:14.977  3868  3868 D BluetoothMapService: stop()
08-04 10:46:14.980  6834  6834 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-04 10:46:14.980  3868  3868 D BluetoothMapEmailAppObserver: deinitObservers()
08-04 10:46:14.981  3868  3868 D BluetoothMapEmailAppObserver: removeReceiver()
08-04 10:46:14.984  3868  3868 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ecda7fb
08-04 10:46:14.984  6815  6815 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-04 10:46:14.986  3868  3868 I BluetoothA2dpServiceJni: cleanupNative
08-04 10:46:14.986  3868  4003 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-04 10:46:14.986  3868  3868 I GKI_LINUX: GKI_exit_task 2 done
08-04 10:46:14.986  3868  3868 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-04 10:46:14.986  3868  3868 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-04 10:46:14.986  3868  3868 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-04 10:46:14.987  3868  3868 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-04 10:46:14.987  3868  3868 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-04 10:46:14.987  3868  3868 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-04 10:46:14.987  3868  3868 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-04 10:46:14.987  3868  3868 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-04 10:46:14.989  3868  3868 V BluetoothMapService: Handler(): got msg=4
08-04 10:46:14.989  3868  3868 D BluetoothMapService: MAP Service closeService in
08-04 10:46:14.989  3868  3868 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-04 10:46:14.989  3868  3868 V BluetoothMapService: MAP Service closeService out
08-04 10:46:14.989  3868  3868 D BluetoothMapService: cleanup()
08-04 10:46:14.989  3868  3868 D BluetoothMapService: MAP Service closeService in
08-04 10:46:14.989  3868  3868 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-04 10:46:14.989  3868  3868 V BluetoothMapService: MAP Service closeService out
08-04 10:46:14.990  3868  3942 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-04 10:46:14.990  3868  3942 D BluetoothAdapterProperties: Setting state to 10
08-04 10:46:14.990  3868  3942 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-04 10:46:14.990  1039  1121 D BluetoothManagerService: Message: 60
08-04 10:46:14.990  1039  1121 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-04 10:46:14.991  1039  1121 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-04 10:46:14.991  3868  3942 I BluetoothAdapterState: Entering OffState
08-04 10:46:14.991  1840  3975 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 10:46:14.992  6815  6830 D BluetoothPan: onBluetoothStateChange on: false
08-04 10:46:14.992  6815  6831 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-04 10:46:14.993  1039  1121 D BluetoothA2dp: onBluetoothStateChange: up=false
08-04 10:46:14.993  1840  1856 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 10:46:14.994  6815  6830 D BluetoothMap: onBluetoothStateChange: up=false
08-04 10:46:14.994  1039  1121 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 10:46:14.994  6815  6831 D BluetoothPbap: onBluetoothStateChange: up=false
08-04 10:46:14.995  1840  1855 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 10:46:14.996  1039  1121 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-04 10:46:14.996  1039  1121 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-04 10:46:14.999  1039  1121 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-04 10:46:14.999  1039  1121 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-04 10:46:14.999  1039  1121 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@35fc80b8 mBinding = false
08-04 10:46:14.999  6815  6815 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 10:46:15.005  1039  1121 D BluetoothManagerService: Sending unbind request.
08-04 10:46:15.007  1039  1121 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-04 10:46:15.013  3868  3946 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-04 10:46:15.014  3868  3868 I GKI_LINUX: GKI_exit_task 1 done
08-04 10:46:15.014  3868  3868 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-04 10:46:15.014  3868  3868 I BluetoothServiceJni: cleanupNative: return from cleanup
08-04 10:46:15.014  3868  3868 I art     : --- WEIRD: removing null entry 246
08-04 10:46:15.014  3868  3868 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-04 10:46:15.014  3868  3868 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-04 10:46:15.016  3868  3868 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-04 10:46:15.018  3868  3868 I art     : System.exit called, status: 0
08-04 10:46:15.019  3868  3868 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-04 10:46:15.034  1590  1590 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-04 10:46:15.034  1930  1930 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:15.035  1930  2116 D LGBluetoothAPIService: Message: 2
08-04 10:46:15.035  1930  2116 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@1479af5a mBinding = false
08-04 10:46:15.035  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:46:15.035  1930  2116 D LGBluetoothAPIService: Sending unbind request.
08-04 10:46:15.036  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:46:15.039  1590  1590 D BluetoothAdapter: 764314722: getState() :  mService = null. Returning STATE_OFF
08-04 10:46:15.039  1590  1590 D BluetoothAdapter: 764314722: getState() :  mService = null. Returning STATE_OFF
08-04 10:46:15.043  6815  6815 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-04 10:46:15.043  6815  6815 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-04 10:46:15.043  6815  6815 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-04 10:46:15.043  6815  6815 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-04 10:46:15.044  6815  6815 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-04 10:46:15.049   322  1373 V AudioFlinger: 3868 died, releasing its sessions
08-04 10:46:15.049   322  1373 V AudioFlinger:  pid 1840 @ 0
08-04 10:46:15.049   322  1373 V AudioFlinger:  pid 3467 @ 1
08-04 10:46:15.050   322  1373 V AudioFlinger:  pid 3467 @ 2
08-04 10:46:15.052  6919  6941 W FormManager: Network not available. Please check & try again.
08-04 10:46:15.055  6815  6815 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-04 10:46:15.055  1039  1633 V SIM_STK : Menu title from STK is T-Mobile
08-04 10:46:15.055  6815  6815 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-04 10:46:15.055  6815  6815 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-04 10:46:15.055  6815  6815 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-04 10:46:15.055  6815  6815 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-04 10:46:15.056  6815  6815 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-04 10:46:15.056  6815  6815 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-04 10:46:15.057  6815  6815 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-04 10:46:15.057  6815  6815 D LGBluetoothEventManager: [BTUI] clear device connection state
08-04 10:46:15.059  6815  6815 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-04 10:46:15.078  1039  1983 I ActivityManager: Process com.android.bluetooth (pid 3868) has died
08-04 10:46:15.079  1039  1983 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-04 10:46:15.084  6815  6815 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-04 10:46:15.142  1039  1563 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=6952 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-04 10:46:15.144  6815  6815 D DockEventReceiver: finishStartingService: stopping service
08-04 10:46:15.148  4298  4298 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-04 10:46:15.149  4298  4298 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-04 10:46:15.151  4298  4298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-04 10:46:15.157  4298  4298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-04 10:46:15.160  6919  6947 V FormManager: Network unavailable.
08-04 10:46:15.165  6919  6947 V FormManager: Network unavailable.
08-04 10:46:15.168  4298  6967 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-04 10:46:15.174  6834  6834 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-04 10:46:15.174  6834  6834 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-04 10:46:15.174  6834  6834 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-04 10:46:15.178  6815  6815 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-04 10:46:15.180  4298  6970 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-04 10:46:15.180  4298  6970 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-04 10:46:15.184  6815  6815 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 10:46:15.193  6919  6972 W FormManager: Network not available. Please check & try again.
,08-04 10:46:15.203  6919  6973 V FormManager: Network unavailable.
,08-04 10:46:15.207  6919  6973 V FormManager: Network unavailable.
,08-04 10:46:15.211  6869  6869 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-04 10:46:15.212  6869  6869 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-04 10:46:15.213  6869  6869 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-04 10:46:15.219  6952  6952 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-04 10:46:15.220  6952  6952 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-04 10:46:15.220  6952  6952 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,08-04 10:46:15.221  6952  6952 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-04 10:46:15.238  6952  6952 D BluetoothAdapterApp: Loading JNI Library
,08-04 10:46:15.248  6869  6869 D LgDataFeature: LgDataFeature() Constructor: none
08-04 10:46:15.249  6869  6869 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-04 10:46:15.255  6869  6869 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-04 10:46:15.257  6869  6869 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-04 10:46:15.257  6869  6869 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-04 10:46:15.257  6869  6869 V SoundPool: doLoad: loading sample sampleID=1
08-04 10:46:15.257  6869  6976 V SoundPool: Start decode
08-04 10:46:15.257  6869  6976 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-04 10:46:15.258   322  1373 V MediaPlayerService: decode(23, 10857164, 17813)
08-04 10:46:15.258   322  1373 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-04 10:46:15.258   322  1373 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-04 10:46:15.258   322  1373 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-04 10:46:15.258   322  1373 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-04 10:46:15.258   322  1373 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-04 10:46:15.258   322  1373 V MediaPlayerService: player type = 3
08-04 10:46:15.258   322  1373 V AwesomePlayer: AwesomePlayer create()
08-04 10:46:15.258   322  1373 V AwesomePlayer: reset_l() 
08-04 10:46:15.258   322  1373 V AwesomePlayer: cancelPlayerEvents
08-04 10:46:15.258   322  1373 V AwesomePlayer: setAudioSink() 
08-04 10:46:15.258   322  1373 V AwesomePlayer: reset_l() 
08-04 10:46:15.258   322  1373 V AudioCache: notify(0xb14327c0, 8, 0, 0)
08-04 10:46:15.258   322  1373 V AudioCache: ignored
08-04 10:46:15.258   322  1373 V AwesomePlayer: cancelPlayerEvents
08-04 10:46:15.258   322  1373 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-04 10:46:15.258   322  1373 V AwesomePlayer: setDataSource_l dataSource
08-04 10:46:15.258   322  1373 V LGParserOSAL: SniffLGParser start
08-04 10:46:15.258  6869  6869 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-04 10:46:15.259   322  1373 V LGParserOSAL: MainType:5, SubType=0
08-04 10:46:15.259   322  1373 V LGParserOSAL: #### check Mime : application/ogg
08-04 10:46:15.259   322  1373 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-04 10:46:15.259   322  1373 E MediaExtractor: Use LGExtractor :application/ogg 
08-04 10:46:15.261  6869  6869 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-04 10:46:15.262  6667  6667 D UEI.SmartControl: QS Service created
08-04 10:46:15.262  6869  6869 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-04 10:46:15.263  6869  6869 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-04 10:46:15.272  6952  6952 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@39c4100 Instance Count = 1
08-04 10:46:15.274  6667  6667 I UEI.SmartControl: Service initServices...
08-04 10:46:15.274  6667  6667 D UEI.SmartControl: QS start get config
08-04 10:46:15.278  6952  6952 D BluetoothAdapterApp: onCreate
08-04 10:46:15.285  6869  6869 V LGMDMManager: Create singleton instance
,08-04 10:46:15.293   322  1373 V LGParserOSAL: supported mime: application/ogg
08-04 10:46:15.293   322  1373 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-04 10:46:15.293   322  1373 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-04 10:46:15.293   322  1373 V AwesomePlayer: mBitrate = -1 bits/sec
08-04 10:46:15.293   322  1373 V AwesomePlayer: AudioTrack Setting
08-04 10:46:15.293   322  1373 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-04 10:46:15.293   322  1373 V AwesomePlayer: setAudioSource() 
08-04 10:46:15.293   322  1373 V MediaPlayerService: prepare
08-04 10:46:15.293   322  1373 V AwesomePlayer: prepareAsync_l() 
08-04 10:46:15.293   322  1373 V MediaPlayerService: wait for prepare
08-04 10:46:15.293   322  6978 V AwesomePlayer: onPrepareAsyncEvent() 
08-04 10:46:15.293   322  6978 V AwesomePlayer: initAudioDecoder() 
08-04 10:46:15.293   322  6978 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-04 10:46:15.293   322  6978 V AudioSystem: isOffloadSupported()
08-04 10:46:15.293   322  6978 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-04 10:46:15.293   322  6978 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-04 10:46:15.293   322  6978 I AudioFlinger: isAudioPlaybackHookOn() false
08-04 10:46:15.293   322  6978 V AwesomePlayer: getUseOffload() = 0 
08-04 10:46:15.293   322  6978 V OMXCodec: OMXCodec::Create
08-04 10:46:15.293   322  6978 V OMXCodec: findMatchingCodecs()
08-04 10:46:15.293   322  6978 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-04 10:46:15.293   322  6978 V OMXCodec: matchingCodecs.size()=1
08-04 10:46:15.293   322  6978 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-04 10:46:15.295   322  6978 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-04 10:46:15.295   322  6978 V LGCodecAdapter: LG Codec Adapter start
08-04 10:46:15.295   322  6978 V OMXCodec: OMXCodec Createtor
08-04 10:46:15.295   322  6978 V OMXCodec: setComponentRole
08-04 10:46:15.295  6952  6952 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-04 10:46:15.295   322  6978 V OMXCodec: configureCodec protected=0
08-04 10:46:15.295   322  6978 V LGCodecAdapter: called getLGCodecSpecificData
08-04 10:46:15.295   322  6978 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-04 10:46:15.295   322  6978 V LGCodecOSAL: Called LGconfigureCodecMETA
08-04 10:46:15.295   322  6978 V LGCodecOSAL: Called LGconfigureCodecMSG
08-04 10:46:15.295  6952  6952 D ProfileConfigQcom: Adding HeadsetService
08-04 10:46:15.295   322  6978 V LGCodecOSAL: Not support LGCodec
08-04 10:46:15.295   322  6978 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-04 10:46:15.295   322  6978 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-04 10:46:15.295   322  6978 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-04 10:46:15.295  6952  6952 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-04 10:46:15.295   322  6978 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-04 10:46:15.295   322  6978 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-04 10:46:15.295   322  6978 V AudioSystem: isOffloadSupported()
08-04 10:46:15.295   322  6978 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-04 10:46:15.295  6952  6952 D ProfileConfigQcom: Adding A2dpService
08-0,4 10:46:15.295   322  6978 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-04 10:46:15.295   322  6978 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-04 10:46:15.295   322  6978 V OMXCodec: init()
08-04 10:46:15.295   322  6978 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-04 10:46:15.295   322  6978 V OMXCodec: allocateBuffers
08-04 10:46:15.295   322  6978 V OMXCodec: allocateBuffersOnPort portIndex=0
08-04 10:46:15.295  6952  6952 D ProfileConfigQcom: [BTUI] HidService is supported
08-04 10:46:15.295   322  6978 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-04 10:46:15.295  6952  6952 D ProfileConfigQcom: Adding HidService
08-04 10:46:15.295   322  6978 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434380 on input port
08-04 10:46:15.295   322  6978 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14343d0 on input port
08-04 10:46:15.295  6952  6952 D ProfileConfigQcom: [BTUI] HealthService is supported
08-04 10:46:15.295   322  6978 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434420 on input port
08-04 10:46:15.295   322  6978 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14344c0 on input port
08-04 10:46:15.295   322  6978 V OMXCodec: allocateBuffersOnPort portIndex=1
08-04 10:46:15.295   322  6978 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-04 10:46:15.295  6952  6952 D ProfileConfigQcom: Adding HealthService
08-04 10:46:15.296   322  6978 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434510 on output port
08-04 10:46:15.296   322  6978 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14345b0 on output port
08-04 10:46:15.296   322  6978 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434600 on output port
08-04 10:46:15.296  6952  6952 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-04 10:46:15.296   322  6978 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14346a0 on output port
08-04 10:46:15.296   322  6978 V OMXCodec: init() mAsyncCompletion wait!!! 
08-04 10:46:15.296   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-04 10:46:15.296   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-04 10:46:15.296   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-04 10:46:15.296   322  6978 V OMXCodec: init() mAsyncCompletion wait!!! 
08-04 10:46:15.296   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-04 10:46:15.296   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-04 10:46:15.296   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-04 10:46:15.296   322  6978 V OMXCodec: init() mAsyncCompletion wait free! 
08-04 10:46:15.296   322  6978 V AwesomePlayer: finishAsyncPrepare_l() 
08-04 10:46:15.296   322  6978 V AudioCache: notify(0xb14327c0, 5, 0, 0)
08-04 10:46:15.296   322  6978 V AudioCache: ignored
08-04 10:46:15.296   322  6978 V AudioCache: notify(0xb14327c0, 1, 0, 0)
08-04 10:46:15.296   322  6978 V AudioCache: prepared
08-04 10:46:15.296   322  1373 V AudioCache: wait - success
08-04 10:46:15.296   322  1373 V MediaPlayerService: start
08-04 10:46:15.296  6952  6952 D ProfileConfigQcom: [BTUI] PanService is supported
08-04 10:46:15.296   322  1373 V AwesomePlayer: play_l() 
08-04 10:46:15.296   322  1373 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-04 10:46:15.296   322  1373 V AwesomePlayer: createAudioPlayer_l
08-04 10:46:15.296   322  1373 V AwesomePlayer: seekAudioIfNecessary_l() 
08-04 10:46:15.296   322  1373 V AwesomePlayer: startAudioPlayer_l() 
08-04 10:46:15.296   322  1373 D AudioPlayer: start of Playback, useOffload 0
08-04 10:46:15.296   322  1373 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-04 10:46:15.296  6952  6952 D ProfileConfigQcom: Adding PanService
08-04 10:46:15.296   322  1373 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-04 10:46:15.296  6952  6952 D ProfileConfigQcom: [BTUI] GattService is supported
08-04 10:46:15.296  6952  6952 D ProfileConfigQcom: Adding GattService
08-04 10:46:15.297  6952  6952 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-04 10:46:15.297  6952  6952 D ProfileConfigQcom: Adding BluetoothMapService
08-04 10:46:15.297  6952  6952 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-04 10:46:15.297  6952  6952 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-04 10:46:15.298   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-04 10:46:15.298   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-04 10:46:15.298   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-04 10:46:15.298  6952  6952 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:15.298   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-04 10:46:15.298   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-04 10:46:15.298  6952  6952 V BluetoothPbapReceiver: ***********state = 10
08-04 10:46:15.298   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-04 10:46:15.299   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973975824
08-04 10:46:15.299   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-04 10:46:15.299   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973975984
08-04 10:46:15.299   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-04 10:46:15.299   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976064
08-04 10:46:15.299   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-04 10:46:15.299   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976224
08-04 10:46:15.299   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-04 10:46:15.299   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-04 10:46:15.299   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-04 10:46:15.299   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-04 10:46:15.299   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-04 10:46:15.299   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-04 10:46:15.299  6952  6952 V LGMDMManagerInternal: Create singleton instance
08-04 10:46:15.299   322  6980 V OMXCodec: allocateBuffersOnPort portIndex=1
08-04 10:46:15.299   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-04 10:46:15.300   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434600 on output port
08-04 10:46:15.300   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14345b0 on output port
08-04 10:46:15.300   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434510 on output port
08-04 10:46:15.300   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1233060 on output port
08-04 10:46:15.300   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-04 10:46:15.300   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-04 10:46:15.301   322  1373 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-04 10:46:15.301   322  1373 V AudioCache: notify(0xb14327c0, 6, 0, 0)
08-04 10:46:15.301   322  1373 V AudioCache: ignored
08-04 10:46:15.301   322  1373 V MediaPlayerService: wait for playback complete
08-04 10:46:15.301   322  6981 V AudioCache: write(0xb11b7000, 4096)
08-04 10:46:15.301   322  6981 V AudioCache: memcpy(0xac602000, 0xb11b7000, 4096)
08-04 10:46:15.303   322  6981 V AudioCache: write(0xb11b7000, 4096)
08-04 10:46:15.303   322  6981 V AudioCache: memcpy(0xac603000, 0xb11b7000, 4096)
08-04 10:46:15.304   322  6981 V AudioCache: write(0xb11b7000, 4096)
08-04 10:46:15.304   322  6981 V AudioCache: memcpy(0xac604000, 0xb11b7000, 4096)
08-04 10:46:15.304   322  6981 V AudioCache: write(0xb11b7000, 4096)
08-04 10:46:15.304   322  6981 V AudioCache: memcpy(0xac605000, 0xb11b7000, 4096)
08-04 10:46:15.305   322  6981 V AudioCache: write(0xb11b7000, 4096)
08-04 10:46:15.305   322  6981 V AudioCache: memcpy(0xac606000, 0xb11b7000, 4096)
08-04 10:46:15.305   322  6981 V AudioCache: write(0xb11b7000, 4096)
08-04 10:46:15.305   322  6981 V AudioCache: memcpy(0xac607000, 0xb11b7000, 4096)
08-04 10:46:15.306   322  6981 V AudioCache: write(0xb11b7000, 4096)
08-04 10:46:15.306   322  6981 V AudioCache: memcpy(0xac608000, 0xb11b7000, 4096)
08-04 10:46:15.306   322  6981 V AudioCache: write(0xb11b7000, 4096)
08-04 10:46:15.306   322  6981 V AudioCache: memcpy(0xac609000, 0xb11b7000, 4096)
08-04 10:46:15.307   322  6981 V AudioCache: write(0xb11b7000, 4096)
08-04 10:46:15.307   322  6981 V AudioCache: memcpy(0xac60a000, 0xb11b7000, 4096)
08-04 10:46:15.307   322  6981 V AudioCache: write(0xb11b7000, 4096)
08-04 10:46:15.307   322  6981 V AudioCache: memcpy(0xac60b000, 0xb11b7000, 4096)
08-04 10:46:15.308   322  6981 V AudioCache: write(0xb11b7000, 4096)
08-04 10:46:15.308   322  6981 V AudioCache: memcpy(0xac60c000, 0xb11b7000, 4096)
08-04 10:46:15.308   322  6981 V AudioCache: write(0xb11b7000, 4096)
08-04 10:46:15.308   322  6981 V AudioCache: memcpy(0xac60d000, 0xb11b7000, 4096)
08-04 10:46:15.309   322  6981 V AudioCache: write(0xb11b7000, 4096)
08-04 10:46:15.309   322  6981 V AudioCache: memcpy(0xac60e000, 0xb11b7000, 4096)
08-04 10:46:15.309   322  6981 V AudioCache: write(0xb11b7000, 4096)
08-04 10:46:15.309   322  6981 V AudioCache: memcpy(0xac60f000, 0xb11b7000, 4096)
08-04 10:46:15.309   322  6981 V AudioCache: write(0xb11b7000, 4096)
08-04 10:46:15.309   322  6981 V AudioCache: memcpy(0xac610000, 0xb11b7000, 4096)
08-04 10:46:15.310   322  6981 V AudioCache: write(0xb11b7000, 4096)
08-04 10:46:15.310   322  6981 V AudioCache: memcpy(0xac611000, 0xb11b7000, 4096)
08-04 10:46:15.310   322  6981 V AudioCache: write(0xb11b7000, 4096)
08-04 10:46:15.310   322  6981 V AudioCache: memcpy(0xac612000, 0xb11b7000, 4096)
08-04 10:46:15.311   322  6981 V AudioCache: write(0xb11b7000, 4096)
08-04 10:46:15.311   322  6981 V AudioCache: memcpy(0xac613000, 0xb11b7000, 4096)
08-04 10:46:15.311   322  6981 V AudioCache: write(0xb11b7000, 4096)
08-04 10:46:15.311   322  6981 V AudioCache: memcpy(0xac614000, 0xb11b7000, 4096)
08-04 10:46:15.311   322  6981 V AudioCache: write(0xb11b7000, 4096)
08-04 10:46:15.311   322  6981 V AudioCache: memcpy(0xac615000, 0xb11b7000, 4096)
08-04 10:46:15.312   322  6981 V AudioCache: write(0xb11b7000, 4096)
08-04 10:46:15.312   322  6981 V AudioCache: memcpy(0xac616000, 0xb11b7000, 4096)
08-04 10:46:15.312   322  6981 V AudioCache: write(0xb11b7000, 4096)
08-04 10:46:15.312   322  6981 V AudioCache: memcpy(0xac617000, 0xb11b7000, 4096)
08-04 10:46:15.312   322  6981 V AudioCache: write(0xb11b7000, 4096)
08-04 10:46:15.312   322  6981 V AudioCache: memcpy(0xac618000, 0xb11b7000, 4096)
08-04 10:46:15.313   322  6981 V AudioCache: write(0xb11b7000, 4096)
08-04 10:46:15.313   322  6981 V AudioCache: memcpy(0xac619000, 0xb11b7000, 4096)
08-04 10:46:15.313   322  6981 V AudioCache: write(0xb11b7000, 4096)
08-04 10:46:15.313   322  6981 V AudioCache: memcpy(0xac61a000, 0xb11b7000, 4096)
08-04 10:46:15.314   322  6981 V AudioCache: write(0xb11b7000, 4096)
08-04 10:46:15.314   322  6981 V AudioCache: memcpy(0xac61b000, 0xb11b7000, 4096)
08-04 10:46:15.314   322  6981 V AudioCache: write(0xb11b7000, 4096)
08-04 10:46:15.314   322  6981 V AudioCache: memcpy(0xac61c000, 0xb11b7000, 4096)
08-04 10:46:15.314   322  6981 V AudioCache: write(0xb11b7000, 4096)
08-04 10:46:15.314   322  6981 V AudioCache: memcpy(0xac61d000, 0xb11b7000, 4096)
08-04 10:46:15.314   322  6981 V AudioCache: write(0xb11b7000, 4096)
08-04 10:46:15.314   322  6981 V AudioCache: memcpy(0xac61e000, 0xb11b7000, 4096)
08-04 10:46:15.315   322  6981 V AudioCache: write(0xb11b7000, 4096)
08-04 10:46:15.315   322  6981 V AudioCache: memcpy(0xac61f000, 0xb11b7000, 4096)
08-04 10:46:15.316   322  6981 V AudioCache: write(0xb11b7000, 4096)
08-04 10:46:15.316   322  6981 V AudioCache: memcpy(0xac620000, 0xb11b7000, 4096)
08-04 10:46:15.316   322  6981 V AudioCache: write(0xb11b7000, 4096)
08-04 10:46:15.316   322  6981 V AudioCache: memcpy(0xac621000, 0xb11b7000, 4096)
08-04 10:46:15.316   322  6981 V AudioCache: write(0xb11b7000, 4096)
08-04 10:46:15.316   322  6981 V AudioCache: memcpy(0xac622000, 0xb11b7000, 4096)
08-04 10:46:15.317   322  6981 V AudioCache: write(0xb11b7000, 4096)
08-04 10:46:15.317   322  6981 V AudioCache: memcpy(0xac623000, 0xb11b7000, 4096)
08-04 10:46:15.317   322  6981 V AudioCache: write(0xb11b7000, 4096)
08-04 10:46:15.317   322  6981 V AudioCache: memcpy(0xac624000, 0xb11b7000, 4096)
08-04 10:46:15.317   322  6981 V AudioCache: write(0xb11b7000, 4096)
08-04 10:46:15.317   322  6981 V AudioCache: memcpy(0xac625000, 0xb11b7000, 4096)
08-04 10:46:15.317   322  6981 V AudioCache: write(0xb11b7000, 4096)
08-04 10:46:15.317   322  6981 V AudioCache: memcpy(0xac626000, 0xb11b7000, 4096)
08-04 10:46:15.318   322  6981 V AudioCache: write(0xb11b7000, 4096)
08-04 10:46:15.318   322  6981 V AudioCache: memcpy(0xac627000, 0xb11b7000, 4096)
08-04 10:46:15.319   322  6981 V AudioCache: write(0xb11b7000, 4096)
08-04 10:46:15.319   322  6981 V AudioCache: memcpy(0xac628000, 0xb11b7000, 4096)
08-04 10:46:15.319   322  6981 V AudioCache: write(0xb11b7000, 4096)
08-04 10:46:15.319   322  6981 V AudioCache: memcpy(0xac629000, 0xb11b7000, 4096)
08-04 10:46:15.319   322  6981 V AudioCache: write(0xb11b7000, 4096)
08-04 10:46:15.319   322  6981 V AudioCache: memcpy(0xac62a000, 0xb11b7000, 4096)
08-04 10:46:15.320   322  6981 V AudioCache: write(0xb11b7000, 4096)
08-04 10:46:15.320   322  6981 V AudioCache: memcpy(0xac62b000, 0xb11b7000, 4096)
08-04 10:46:15.320   322  6981 V AudioCache: write(0xb11b7000, 4096)
08-04 10:46:15.320   322  6981 V AudioCache: memcpy(0xac62c000, 0xb11b7000, 4096)
08-04 10:46:15.321   322  6981 V AudioCache: write(0xb11b7000, 4096)
08-04 10:46:15.321   322  6981 V AudioCache: memcpy(0xac62d000, 0xb11b7000, 4096)
08-04 10:46:15.321   322  6981 V AudioCache: write(0xb11b7000, 4096)
08-04 10:46:15.321   322  6981 V AudioCache: memcpy(0xac62e000, 0xb11b7000, 4096)
08-04 10:46:15.322   322  6981 V AudioCache: write(0xb11b7000, 4096)
08-04 10:46:15.322   322  6981 V AudioCache: memcpy(0xac62f000, 0xb11b7000, 4096)
08-04 10:46:15.322   322  6981 V AudioCache: write(0xb11b7000, 4096)
08-04 10:46:15.322   322  6981 V AudioCache: memcpy(0xac630000, 0xb11b7000, 4096)
08-04 10:46:15.322   322  6981 V AudioCache: write(0xb11b7000, 4096)
08-04 10:46:15.322   322  6981 V AudioCache: memcpy(0xac631000, 0xb11b7000, 4096)
08-04 10:46:15.323   322  6981 V AudioCache: write(0xb11b7000, 4096)
08-04 10:46:15.323   322  6981 V AudioCache: memcpy(0xac632000, 0xb11b7000, 4096)
08-04 10:46:15.323   322  6981 V AudioCache: write(0xb11b7000, 4096)
08-04 10:46:15.323   322  6981 V AudioCache: memcpy(0xac633000, 0xb11b7000, 4096)
08-04 10:46:15.323   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-04 10:46:15.323   322  6981 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-04 10:46:15.323   322  6981 V AwesomePlayer: postAudioEOS() 
08-04 10:46:15.323   322  6981 V AudioCache: write(0xb11b7000, 280)
08-04 10:46:15.323   322  6981 V AudioCache: memcpy(0xac634000, 0xb11b7000, 280)
08-04 10:46:15.326   322  6978 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-04 10:46:15.326   322  6978 V AwesomePlayer: onStreamDone
08-04 10:46:15.326   322  6978 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-04 10:46:15.326   322  6978 V AudioCache: notify(0xb14327c0, 2, 0, 0)
08-04 10:46:15.326   322  6978 V AudioCache: playback complete
08-04 10:46:15.326   322  6978 V AwesomePlayer: pause_l() 
08-04 10:46:15.326   322  6978 V AudioCache: notify(0xb14327c0, 7, 0, 0)
08-04 10:46:15.326   322  6978 V AudioCache: ignored
08-04 10:46:15.326   322  6978 V AwesomePlayer: cancelPlayerEvents
08-04 10:46:15.326   322  1373 V AudioCache: wait - success
08-04 10:46:15.326   322  1373 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-04 10:46:15.326   322  6978 D AudioPlayer: Pause Playback at 1068125
08-04 10:46:15.328   322  1373 V AwesomePlayer: reset_l() 
08-04 10:46:15.328   322  1373 V AudioCache: notify(0xb14327c0, 8, 0, 0)
08-04 10:46:15.328   322  1373 V AudioCache: ignored
08-04 10:46:15.328   322  1373 V AwesomePlayer: cancelPlayerEvents
08-04 10:46:15.328   322  1373 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-04 10:46:15.328   322  1373 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-04 10:46:15.328   322  1373 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-04 10:46:15.328   322  1373 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-04 10:46:15.328   322  1373 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-04 10:46:15.329   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-04 10:46:15.329   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-04 10:46:15.329   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-04 10:46:15.329   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14344c0 on port 0
08-04 10:46:15.329   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-04 10:46:15.329   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434420 on port 0
08-04 10:46:15.329   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-04 10:46:15.329   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14343d0 on port 0
08-04 10:46:15.329   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-04 10:46:15.329   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434380 on port 0
08-04 10:46:15.329   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-04 10:46:15.329   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-04 10:46:15.329   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1233060 on port 1
08-04 10:46:15.329   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-04 10:46:15.329   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434510 on port 1
08-04 10:46:15.329   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-04 10:46:15.329   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14345b0 on port 1
08-04 10:46:15.329   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-04 10:46:15.329   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434600 on port 1
08-04 10:46:15.329   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-04 10:46:15.329   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-04 10:46:15.330   322  1373 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-04 10:46:15.330   322  1373 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-04 10:46:15.330   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-04 10:46:15.330   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-04 10:46:15.330   322  6980 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-04 10:46:15.330   322  1373 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-04 10:46:15.330   322  1373 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-04 10:46:15.330   322  1373 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-04 10:46:15.331   322  1373 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-04 10:46:15.331   322  1373 D AudioPlayer: AudioPlayer releasing audio source
08-04 10:46:15.331   322  1373 D AudioPlayer: AudioPlayer done releasing audio source
08-04 10:46:15.331   322  1373 V AwesomePlayer: reset_l() 
08-04 10:46:15.331   322  1373 V AwesomePlayer: cancelPlayerEvents
08-04 10:46:15.331   322  1373 V AwesomePlayer: ~AwesomePlayer call
08-04 10:46:15.332   322  1373 V AwesomePlayer: reset_l() 
08-04 10:46:15.332   322  1373 V AwesomePlayer: cancelPlayerEvents
,08-04 10:46:15.338  6869  6976 V SoundPool: close(31)
08-04 10:46:15.338  6869  6976 V SoundPool: pointer = 0x9fe87000, size = 205080, sampleRate = 48000, numChannels = 2
08-04 10:46:15.347  6869  6869 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-04 10:46:15.348  6869  6869 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-04 10:46:15.350  6869  6869 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:6526
08-04 10:46:15.359  6152  6152 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-04 10:46:15.365  2170  2170 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-04 10:46:15.366  6815  6815 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-04 10:46:15.366  1039  1947 I ActivityManager: Killing 6105:com.android.contacts/u0a19 (adj 15): empty #17
08-04 10:46:15.461  1039  1973 W libprocessgroup: failed to open /acct/uid_10019/pid_6105/cgroup.procs: No such file or directory
,08-04 10:46:15.490  6815  6815 D BluetoothPermissionRequest: onReceive
,08-04 10:46:15.494  6815  6815 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-04 10:46:15.495  6815  6815 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-04 10:46:15.498  6815  6815 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-04 10:46:15.502  6952  6952 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-04 10:46:15.506  6952  6952 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:15.509  6952  6952 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-04 10:46:15.510  6952  6952 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-04 10:46:15.510  6952  6952 V BluetoothSapReceiver: SapReceiver onReceive 
08-04 10:46:15.511  6952  6952 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:15.511  6952  6952 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-04 10:46:15.521  6886  6886 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-04 10:46:15.545  6667  6667 I UEI.SmartControl: Supports setup maps: true
08-04 10:46:15.548  6667  6667 D UEI.SmartControl: QS start statue = true Error code = 0
08-04 10:46:15.548  6667  6667 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-04 10:46:15.548  6667  6667 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-04 10:46:15.548  6667  6667 I UEI.SmartControl: ### init IR Blaster...
,08-04 10:46:15.551  6667  6667 D serial_port: Configuring serial port
,08-04 10:46:15.551  6667  6667 E UEI.SmartControl: UEIBLaster setting for 616
08-04 10:46:15.551  6667  6667 I UEI.SmartControl: Setting serial record hearder size = 2
08-04 10:46:15.551  6667  6667 I UEI.SmartControl: configuring settings for MAXQ616
08-04 10:46:15.551  6667  6667 I UEI.SmartControl: Get version...
08-04 10:46:15.566  6667  6985 D UEI.SmartControl: serial port data available: 21
,08-04 10:46:15.592  6667  6667 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-04 10:46:15.592  6667  6667 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-04 10:46:15.592  6667  6667 I UEI.SmartControl: QS saving settings...
08-04 10:46:15.594  6667  6667 D UEI.SmartControl: IR Blaster version: 25672567
,08-04 10:46:15.610  6667  6985 D UEI.SmartControl: serial port data available: 4
,08-04 10:46:15.643  6667  6991 I UEI.SmartControl: Device manager: loading config....
08-04 10:46:15.645  6667  6991 D UEI.SmartControl: ----------- loading internal config...
,08-04 10:46:15.646  6667  6667 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-04 10:46:15.649  6667  6667 E UEI.SmartControl: Services init done
08-04 10:46:15.649  6667  6667 D UEI.SmartControl: QS Service init finished
08-04 10:46:15.650  6667  6667 D UEI.SmartControl: QS Service version name: 2.1.91
08-04 10:46:15.650  6667  6667 D UEI.SmartControl: QS Service version code: 201091
08-04 10:46:15.650  6667  6667 D UEI.SmartControl: Service requested: Control
08-04 10:46:15.656  6667  6991 E UEI.SmartControl: Loading SETTINGS...
08-04 10:46:15.661  6667  6667 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-04 10:46:15.663  6869  6869 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-04 10:46:15.663  6667  6991 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-04 10:46:15.664  6667  6687 I UEI.SmartControl: ------ IControl API: 11
08-04 10:46:15.664  6667  6667 D UEI.SmartControl: Internal service binding...
08-04 10:46:15.664  6667  6687 D UEI.SmartControl: File observer start...
08-04 10:46:15.665  6667  6687 E UEI.SmartControl: IR Port is disabled: false
08-04 10:46:15.665  6667  6687 D UEI.SmartControl: Starting file observer...
08-04 10:46:15.666  6667  6687 I UEI.SmartControl: Registering callback...
08-04 10:46:15.667  6667  6686 I UEI.SmartControl: ------ IControl API: 19
08-04 10:46:15.668  6667  6686 I UEI.SmartControl: Registering Services Ready callback...
08-04 10:46:15.669  6667  6686 I UEI.SmartControl: Notify client services are ready...
08-04 10:46:15.669  6869  6885 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-04 10:46:15.670  6869  6974 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-04 10:46:15.670  6869  6974 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-04 10:46:15.671  6869  6869 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-04 10:46:15.671  6869  6869 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-04 10:46:15.671  6667  6747 I UEI.SmartControl: ------ IControl API: 8
08-04 10:46:15.673  6869  6869 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-04 10:46:15.673  6869  6869 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-04 10:46:15.674  6869  6869 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-04 10:46:15.674  6869  6869 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-04 10:46:15.675  6869  6869 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-04 10:46:15.675  6869  6869 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
,08-04 10:46:15.676  6869  6869 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-04 10:46:15.680  6667  6990 I UEI.SmartControl: Notify AllClients services are ready: 0
08-04 10:46:15.680  6667  6990 D UEI.SmartControl: -----service ready thread exits
08-04 10:46:15.680  6869  6885 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-04 10:46:15.681  6869  6974 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-04 10:46:15.681  6869  6974 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-04 10:46:15.684  6869  6869 D QRemote : [RemoteControlManager.java:327:handleMessage()] oooooo 140510:retrieveDevices already complete. Do nothing
08-04 10:46:15.685  6869  6869 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-04 10:46:15.686  6869  6869 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-04 10:46:15.686  6869  6869 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-04 10:46:15.687  6869  6869 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-04 10:46:15.689  6869  6869 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-04 10:46:15.691  6869  6869 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-04 10:46:15.692  6869  6869 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-04 10:46:15.695  6869  6869 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1470300375694]
08-04 10:46:15.698  6869  6869 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-04 10:46:15.701  1039  1928 I ActivityManager: Killing 6129:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-04 10:46:15.718  6869  6993 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-04 10:46:15.789  1039  1928 I ActivityManager: Killing 6519:com.lge.email/u0a23 (adj 15): empty #18
,08-04 10:46:15.856  1039  1875 W libprocessgroup: failed to open /acct/uid_10023/pid_6519/cgroup.procs: No such file or directory
,08-04 10:46:15.858  6869  6869 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-04 10:46:15.860  6869  6869 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-04 10:46:15.861  1039  2003 W libprocessgroup: failed to open /acct/uid_10027/pid_6129/cgroup.procs: No such file or directory
08-04 10:46:15.862  6869  6869 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-04 10:46:15.863  6869  6869 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-04 10:46:15.864  6869  6869 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-04 10:46:15.865  6869  6869 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-04 10:46:15.866  6869  6869 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-04 10:46:15.877  6869  6869 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-04 10:46:16.341  1039  1364 V AlarmManager: ELAPSED_WAKEUP set : Alarm{39bbe365 type 2 when 133739 com.google.android.gms} when 133739
,08-04 10:46:16.354   315  7001 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-04 10:46:16.362  1039  1119 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-04 10:46:16.835  1039  1983 D WifiServiceImplEx: setWifiEnabled: true pid=6705, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-04 10:46:16.836  1039  1983 D WifiService: setWifiEnabled: true pid=6705, uid=10118
08-04 10:46:16.836  1039  1983 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-04 10:46:16.864  1039  1039 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-04 10:46:16.865  1039  1039 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-04 10:46:16.865  1039  1039 D Ulp_jni : JNI:system_update. Event-4
,08-04 10:46:16.868  1039  1526 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-04 10:46:16.868  1039  1526 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-04 10:46:16.871  1039  1526 E WifiUtil: wfc_util_ffile_check_copy(): pid[1039] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-04 10:46:16.871  1039  1526 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-04 10:46:16.871  1039  1526 E WifiUtil: wfc_util_ffile_check_copy(): pid[1039] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-04 10:46:16.871  1039  1526 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-04 10:46:16.871  1039  1526 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-04 10:46:16.871  1039  1526 E WifiHW  : unknown target_country: EU , set to default
08-04 10:46:16.871  1039  1526 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-04 10:46:16.871  1039  1526 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-04 10:46:16.871  1039  1526 I WifiUtil: gEnableBmps=1
08-04 10:46:16.895  1039  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-04 10:46:16.903  1039  1121 D Tethering: MasterInitialState.processMessage what=3
08-04 10:46:16.911  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:46:16.914  1039  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-04 10:46:16.916  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:46:16.922  1039  1111 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-04 10:46:16.925  1039  1121 D Tethering: MasterInitialState.processMessage what=3
08-04 10:46:16.935  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:46:16.937  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:46:16.940  6409  6409 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-04 10:46:16.943  6409  6448 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-04 10:46:16.954  5720  5720 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-04 10:46:16.962  5720  5720 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-04 10:46:16.987  2170  2170 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-04 10:46:17.023  1039  1111 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-04 10:46:17.069  1039  1893 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7017 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
08-04 10:46:17.074  1039  1111 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:17.074  1039  1111 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:17.124  7017  7017 I AppUp4:AppBoxCP: onCreate
08-04 10:46:17.125  7017  7017 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-04 10:46:17.136  7017  7017 I AppUp4:DB:  setFingerPrint start
08-04 10:46:17.136  7017  7017 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-04 10:46:17.144  7017  7017 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-04 10:46:17.145  7017  7017 I AppUp4:DB:  SDK version = 21
08-04 10:46:17.145  7017  7017 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-04 10:46:17.146  7017  7017 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,08-04 10:46:17.148  7017  7017 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-04 10:46:17.148  7017  7017 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-04 10:46:17.150  7017  7017 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-04 10:46:17.150  7017  7017 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-04 10:46:17.155  7017  7017 I AppUp4:CustModeStarterReceiver: onReceive
08-04 10:46:17.200  7017  7017 D LgDataFeature: LgDataFeature() Constructor: none
08-04 10:46:17.201  7017  7017 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-04 10:46:17.213  7017  7017 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3b31558a
08-04 10:46:17.214  7017  7017 D AppUp4:CustFacade: isCustomizationCompleted : false
08-04 10:46:17.214  7017  7017 D AppUp4:CustFacade: isPhone : true
08-04 10:46:17.215  7017  7017 D AppUp4:CustModeStarterReceiver: begin check event
08-04 10:46:17.216  7017  7017 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-04 10:46:17.217  7017  7017 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-04 10:46:17.218  7017  7034 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-04 10:46:17.218  7017  7034 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-04 10:46:17.218  7017  7034 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-04 10:46:17.220  1039  1875 I ActivityManager: Killing 6350:com.android.defcontainer/u0a4 (adj 15): empty #17
,08-04 10:46:17.264  4298  4298 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-04 10:46:17.265  4298  4298 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-04 10:46:17.266  1039  1766 W libprocessgroup: failed to open /acct/uid_10004/pid_6350/cgroup.procs: No such file or directory
,08-04 10:46:17.272  4298  4298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-04 10:46:17.279  4298  4298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-04 10:46:17.307  4298  7038 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-04 10:46:17.307  4298  7042 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-04 10:46:17.307  4298  7042 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-04 10:46:17.375  1039  1983 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7043 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-04 10:46:17.483  7043  7043 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-04 10:46:17.483  7043  7043 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-04 10:46:17.485  7043  7043 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-04 10:46:17.485  7043  7043 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-04 10:46:17.572  7043  7043 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-04 10:46:17.586  7043  7043 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-04 10:46:17.659  7043  7043 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-04 10:46:17.691  1039  1121 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-04 10:46:17.697   315   897 D SoftapController: Softap fwReload - Ok
08-04 10:46:17.702  1039  1526 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (826ms)
08-04 10:46:17.703   315   897 D CommandListener: Setting iface cfg
08-04 10:46:17.703   315   897 D CommandListener: Trying to bring down wlan0
08-04 10:46:17.704   315   897 D CommandListener: Clearing all IP addresses on wlan0
,08-04 10:46:17.708  1039  1121 D Tethering: InitialState.processMessage what=4
08-04 10:46:17.709  1039  1121 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-04 10:46:17.710  1039  1526 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-04 10:46:17.714  1039  1526 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-04 10:46:17.714  1039  1526 E WifiStateMachine: useWiFiOffloading() : false
08-04 10:46:17.714  1039  1526 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-04 10:46:17.715  1039  1526 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-04 10:46:17.715  1039  1526 D WifiMonitor: connecting to supplicant
08-04 10:46:17.716  1039  1526 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
08-04 10:46:17.707  7071  7071 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 10:46:17.707  7071  7071 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-04 10:46:17.729  1930  1930 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-04 10:46:17.730  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-04 10:46:17.749  1039  1039 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,08-04 10:46:17.751  7071  7071 I wpa_supplicant: Successfully initialized wpa_supplicant
08-04 10:46:17.765  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:46:17.767  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:46:17.781  7071  7071 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-04 10:46:17.782  7071  7071 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-04 10:46:17.783  7043  7043 D LgDataFeature: LgDataFeature() Constructor: none
08-04 10:46:17.783  7043  7043 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-04 10:46:17.862  7071  7071 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-04 10:46:17.898  7043  7043 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-04 10:46:17.908  7071  7071 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-04 10:46:17.926  3467  3467 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-04 10:46:17.926  3467  3467 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-04 10:46:17.927  3467  3467 I LgeMiscReceiver: networkInfo.isConnected() = false
08-04 10:46:17.929  7071  7071 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-04 10:46:17.930  7071  7071 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,08-04 10:46:17.933  7043  7043 I HubEmail: JNI_OnLoad()
08-04 10:46:17.933  7043  7043 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-04 10:46:17.933  7043  7043 I HubEmail: registerNatives()
08-04 10:46:17.933  7043  7043 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-04 10:46:17.933  7043  7043 I HubEmail: registerNativeMethods()
08-04 10:46:17.933  7043  7043 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-04 10:46:17.934  7043  7043 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-04 10:46:17.979  1039  1054 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7090 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-04 10:46:17.984  6919  7087 W FormManager: Network not available. Please check & try again.
08-04 10:46:17.986  7043  7089 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 10:46:17.989  6919  7088 V FormManager: Network unavailable.
08-04 10:46:17.990  6919  7088 V FormManager: Network unavailable.
08-04 10:46:17.997  1039  1875 I ActivityManager: Killing 6190:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-04 10:46:18.039  1039  1563 W libprocessgroup: failed to open /acct/uid_10080/pid_6190/cgroup.procs: No such file or directory
,08-04 10:46:18.107  7090  7090 D LgDataFeature: LgDataFeature() Constructor: none
,08-04 10:46:18.107  7090  7090 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-04 10:46:18.110  7090  7090 D PhoneMonitor: Register our PhoneStateListener
08-04 10:46:18.130  7090  7090 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-04 10:46:18.133  7090  7090 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-04 10:46:18.165  7090  7090 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-04 10:46:18.166  7090  7090 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
,08-04 10:46:18.169  7090  7090 D TelephonyAutoProfiling: [parse] Load xml
08-04 10:46:18.175  7090  7090 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-04 10:46:18.175  7090  7090 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-04 10:46:18.175  7090  7090 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-04 10:46:18.175  7090  7090 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-04 10:46:18.175  7090  7090 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-04 10:46:18.175  7090  7090 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-04 10:46:18.175  7090  7090 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-04 10:46:18.176  7090  7090 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-04 10:46:18.176  7090  7090 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-04 10:46:18.176  7090  7090 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-04 10:46:18.176  7090  7090 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-04 10:46:18.176  7090  7090 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-04 10:46:18.176  7090  7090 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-04 10:46:18.176  7090  7090 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-04 10:46:18.176  7090  7090 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-04 10:46:18.177  7090  7090 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-04 10:46:18.177  7090  7090 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-04 10:46:18.190  7090  7090 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,08-04 10:46:18.207  1039  1054 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7110 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-04 10:46:18.208  1039  1054 I ActivityManager: Killing 6557:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-04 10:46:18.260  1039  1929 W libprocessgroup: failed to open /acct/uid_10061/pid_6557/cgroup.procs: No such file or directory
,08-04 10:46:18.516  1039  1766 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7132 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-04 10:46:18.521  1039  1766 I ActivityManager: Killing 5994:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-04 10:46:18.550  7071  7071 E wpa_supplicant: USIM:  scard_init function
08-04 10:46:18.551  7071  7071 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-04 10:46:18.589  1039  1983 W libprocessgroup: failed to open /acct/uid_10097/pid_5994/cgroup.procs: No such file or directory
,08-04 10:46:18.664  7071  7071 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-04 10:46:18.682  7071  7071 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-04 10:46:18.682  7071  7071 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-04 10:46:18.713  1039  1766 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7152 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-04 10:46:18.718  1039  1526 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-04 10:46:18.719  1039  1526 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-04 10:46:18.719  1039  1526 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-04 10:46:18.720  1039  1526 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-04 10:46:18.720  1039  1526 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-04 10:46:18.721  1039  1526 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-04 10:46:18.721  1039  1526 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-04 10:46:18.721  1039  1526 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-04 10:46:18.722  1039  1526 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-04 10:46:18.722  1039  1526 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-04 10:46:18.724  1039  1766 I ActivityManager: Killing 6616:com.lge.eula/1000 (adj 15): empty #17
,08-04 10:46:18.727  1039  1526 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-04 10:46:18.729  1039  1526 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-04 10:46:18.729  1039  1526 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-04 10:46:18.759  1039  1121 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-04 10:46:18.762  1039  1526 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-04 10:46:18.762  1039  1526 E WifiStateMachine: useWiFiOffloading() : false
08-04 10:46:18.762  1039  1526 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-04 10:46:18.763  1039  1526 D WifiNative-wlan0: doBoolean: SET update_config 1
08-04 10:46:18.764  1930  1930 D WfdService: Waiting for WifiP2p enabling
08-04 10:46:18.766  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 10:46:18.767  1039  1055 W libprocessgroup: failed to open /acct/uid_1000/pid_6616/cgroup.procs: No such file or directory
08-04 10:46:18.768  1039  1526 D WifiNative-wlan0: SET update_config 1: returned true
08-04 10:46:18.768  1039  1526 D WifiConfigStore: Loading config and enabling all networks 
08-04 10:46:18.768  1039  1526 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-04 10:46:18.768  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:46:18.768  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:46:18.768  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:18.768  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:18.768  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:46:18.768  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 10:46:18.768  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:46:18.768  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:46:18.768  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 10:46:18.768  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:46:18.768  6705  6705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 10:46:18.769  1039  1039 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 10:46:18.769  1039  1039 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 10:46:18.769  1039  1039 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 10:46:18.769  1039  1526 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	[CURRENT]
08-04 10:46:18.769  1039  1039 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 10:46:18.770  1039  1039 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-04 10:46:18.771  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:46:18.771  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:46:18.771  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:18.771  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:18.771  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
,08-04 10:46:18.771  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 10:46:18.771  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:46:18.771  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:46:18.771  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 10:46:18.771  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:46:18.771  6705  6705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 10:46:18.774  1039  1039 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-04 10:46:18.774  1039  1530 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
,08-04 10:46:18.786  1039  1526 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-04 10:46:18.796  1039  1526 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-04 10:46:18.797  1039  1526 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-04 10:46:18.797  1039  1526 D WifiStateMachine: enableVerboseLogging : level 2
08-04 10:46:18.797  1039  1526 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
,08-04 10:46:18.800  1039  1526 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-04 10:46:18.800  1039  1526 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-04 10:46:18.801  1039  1526 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-04 10:46:18.801  1039  1526 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-04 10:46:18.801  1039  1526 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-04 10:46:18.801  1039  1526 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-04 10:46:18.802  1039  1526 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-04 10:46:18.802  1039  1526 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-04 10:46:18.802  1039  1526 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-04 10:46:18.802  1039  1526 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-04 10:46:18.803  1039  1526 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-04 10:46:18.803  1039  1526 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-04 10:46:18.803  1039  1526 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-04 10:46:18.804  1039  1526 D WifiStateMachine: Setting OUI to DA-A1-19
08-04 10:46:18.804  1039  1526 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-04 10:46:18.804  1039  1526 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-04 10:46:18.804  1039  1526 D WifiNative-HAL: Setting external_sim to 1
08-04 10:46:18.804  1039  1526 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-04 10:46:18.805  1039  1526 D WifiNative-wlan0: SET external_sim 1: returned true
08-04 10:46:18.805  1039  1526 I WifiNative-HAL: startHal
08-04 10:46:18.805  1039  1526 D wifi    : setting scan oui 0xaf6723c0
08-04 10:46:18.805  1039  1526 D WifiStateMachine: Setting OUI to DA-A1-19
08-04 10:46:18.805  1039  1526 I WifiNative-HAL: startHal
08-04 10:46:18.805  1039  1526 D wifi    : setting scan oui 0xaf6723c0
08-04 10:46:18.806  1039  1526 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-04 10:46:18.806  1039  1526 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-04 10:46:18.806  1039  1526 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-04 10:46:18.807  7071  7071 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-04 10:46:18.807  1039  1526 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-04 10:46:18.807  1039  1526 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-04 10:46:18.807  7071  7071 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-04 10:46:18.808  1039  1526 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-04 10:46:18.808  1039  1526 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-04 10:46:18.808  7071  7071 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-04 10:46:18.808  1039  1526 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-04 10:46:18.809  1039  1526 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-04 10:46:18.809  7071  7071 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-04 10:46:18.809  1039  1526 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-04 10:46:18.809  1039  1526 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-04 10:46:18.809  7071  7071 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-04 10:46:18.810  1039  1526 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-04 10:46:18.810  1039  1526 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-04 10:46:18.810  7071  7071 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-04 10:46:18.810  1039  1526 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-04 10:46:18.810  1039  1526 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-04 10:46:18.810  7071  7071 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-04 10:4,6:18.810  1039  1526 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-04 10:46:18.811  1039  1526 E WifiNative: : [136,220,184 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-04 10:46:18.811  1039  1526 D WifiNative-wlan0: doBoolean: RECONNECT
08-04 10:46:18.812  1039  1526 D WifiNative-wlan0: RECONNECT: returned true
08-04 10:46:18.812  1039  1526 D WifiNative-wlan0: doString: [STATUS]
08-04 10:46:18.812  1039  7158 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-04 10:46:18.813  1039  7158 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-04 10:46:18.813  1039  1526 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-04 10:46:18.813  1039  1526 D WifiNative-wlan0: doBoolean: SET ps 1
08-04 10:46:18.813  1039  1526 D WifiNative-wlan0: SET ps 1: returned true
08-04 10:46:18.814  1039  1525 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:18.816  1039  1526 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-04 10:46:18.816  1039  1526 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-04 10:46:18.816  1039  1526 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-04 10:46:18.817  1039  1526 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-04 10:46:18.817  1039  1526 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-04 10:46:18.818  1039  1526 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-04 10:46:18.819   315   897 D CommandListener: Setting iface cfg
08-04 10:46:18.819   315   897 D CommandListener: Trying to bring up p2p0
08-04 10:46:18.819  1039  1525 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-04 10:46:18.820  1039  1525 D LGWifiP2pService: P2pEnablingState
08-04 10:46:18.820  1039  1525 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:18.820  1039  1525 D LGWifiP2pService: P2p socket connection successful
,08-04 10:46:18.820  1039  1525 D LGWifiP2pService: P2pEnabledState
,08-04 10:46:18.820  1039  1525 D LGWifiP2pService: sending p2p connection changed broadcast
,08-04 10:46:18.820  1039  1525 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-04 10:46:18.821  1039  1526 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-04 10:46:18.821  1039  1525 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-04 10:46:18.821  1039  1525 D WifiNative-p2p0: doBoolean: SET device_name G3
08-04 10:46:18.821  1039  1526 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-04 10:46:18.821  1039  1525 D WifiNative-p2p0: SET device_name G3: returned true
08-04 10:46:18.821  1039  1525 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-04 10:46:18.821  1039  1525 D LGWifiP2pService: before postfix = G3
08-04 10:46:18.821  1039  1525 D WifiServerServiceExt: postfix byte check : 2
08-04 10:46:18.821  1039  1525 D LGWifiP2pService: after postfix = G3
,08-04 10:46:18.822  1039  1525 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-04 10:46:18.822  1039  1526 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-04 10:46:18.822  1039  1525 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-04 10:46:18.822  1039  1525 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-04 10:46:18.822  1039  1525 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-04 10:46:18.822  1039  1526 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-04 10:46:18.822  1039  1525 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-04 10:46:18.823  1039  1526 E WifiStateMachine:  ConnectModeState what:132106 1 0
,08-04 10:46:18.823  1039  1525 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-04 10:46:18.823  1039  1525 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-04 10:46:18.823  1039  1525 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-04 10:46:18.823  1039  1525 D WifiNative-HAL: p2pGetDeviceAddress
08-04 10:46:18.824  1039  1525 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-04 10:46:18.824  1039  1526 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-04 10:46:18.824  1039  1526 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-04 10:46:18.824  1039  1525 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
,08-04 10:46:18.824  1039  1525 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-04 10:46:18.824  7071  7071 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-04 10:46:18.824  1039  1525 D WifiNative-p2p0: P2P_FLUSH: returned true
08-04 10:46:18.824  1039  1525 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-04 10:46:18.824  1039  1525 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-04 10:46:18.825  1039  1525 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-04 10:46:18.825  1039  1526 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-04 10:46:18.825  1039  1525 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
,08-04 10:46:18.825  1039  1525 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-04 10:46:18.826  1039  1526 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-04 10:46:18.826  1039  1526 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-04 10:46:18.826  1039  1526 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
,08-04 10:46:18.836  7152  7152 I art     : Almond Protected OAT
08-04 10:46:18.841  1930  1930 D WfdsService: Supplicant Connection state is changed : true
08-04 10:46:18.842  1930  2236 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
,08-04 10:46:18.842  1930  2236 D WfdsService: Set the WFDS Monitor: true
08-04 10:46:18.842  1930  2236 D WfdsMonitor: WfdsMonitorThread create
08-04 10:46:18.842  1930  2236 D WfdsMonitor: WFDS Monitor is created and started
08-04 10:46:18.842  1930  2236 D WfdsService: WiFi: Supplicant connection re-established
08-04 10:46:18.843  1039  1039 D WifiScanningService: SCAN_AVAILABLE : 3
08-04 10:46:18.843  1039  1039 D RttService: SCAN_AVAILABLE : 3
08-04 10:46:18.843  1039  1545 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:18.843  1039  1544 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:18.843  1039  1544 I WifiNative-HAL: startHal
08-04 10:46:18.844  1930  1930 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-04 10:46:18.845  1930  1930 D WfdsService: WifiP2pState is changed : true
08-04 10:46:18.845  1930  2236 D WfdsService: Receive the WFDS_ENABLE Method
08-04 10:46:18.845  1930  2236 D WfdsService: Set the WFDS Monitor: true
08-04 10:46:18.845  1930  2236 D WfdsService: Connected to the supplicant for wfds
08-04 10:46:18.845  1930  2236 D WfdsJNI : doCommand: WFDS_SET TRUE
08-04 10:46:18.845  1930  2236 E CtrlSupplicant: Not connected to wap_supplicant - "WFDS_SET TRUE" command dropped.
08-04 10:46:18.845  1930  2236 D WfdsJNI : wfds_send_command: [WFDS_SET TRUE] failed
08-04 10:46:18.845  1930  2236 D WfdsService: selectPreferredScanChannel [36]
08-04 10:46:18.845  1930  2236 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-04 10:46:18.846  1930  7180 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-04 10:46:18.846  1930  7180 E CtrlSupplicant: Succeed to open control connection
08-04 10:46:18.847  1930  7180 E CtrlSupplicant: Succeed to open monitor connection
08-04 10:46:18.848  1930  1930 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-04 10:46:18.849  1930  1930 D WfdsService: isConnected: false
08-04 10:46:18.849  1930  1930 I WfdStateTracker: handleP2pThisDeviceChanged
08-04 10:46:18.849  1930  1930 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-04 10:46:18.849  1930  1930 D WfdsService: Update P2p Interface State: 3
08-04 10:46:18.851  7071  7071 E wpa_supplicant: disconnect_rssi_lvl: -100
08-04 10:46:18.852  1039  1525 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-04 10:46:18.852  1039  1525 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-04 10:46:18.852  1039  1525 D LGWifiP2pService: InactiveState
08-04 10:46:18.852  1039  1525 D LGWifiP2pService: InactiveState{ when=-27ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:18.852  1039  1525 D LGWifiP2pService: P2pEnabledState{ when=-27ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:18.852  1039  1525 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-04 10:46:18.853  7071  7071 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-04 10:46:18.853  1930  7180 D WfdsMonitor: Supplicant connection established
08-04 10:46:18.853  1930  2236 D WfdsService: Received the Event that WfdsMonitor is connected to supplicant
08-04 10:46:18.853  7071  7071 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-04 10:46:18.853  1039  1526 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
,08-04 10:46:18.854  1039  1526 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-04 10:46:18.854  7071  7071 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-04 10:46:18.854  7071  7071 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 10:46:18.854  1039  1526 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-04 10:46:18.854  1039  1526 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-04 10:46:18.855  7071  7071 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-04 10:46:18.857  1039  7158 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-04 10:46:18.857  1039  7158 E WifiMonitor: WifiMonitor:p2p0 cnt=23 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-04 10:46:18.857  1039  7158 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-04 10:46:18.857  1039  7158 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-04 10:46:18.857  1039  7158 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-04 10:46:18.857  1039  7158 E WifiMonitor: WifiMonitor:p2p0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-04 10:46:18.857  1039  7158 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 10:46:18.857  1039  7158 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 10:46:18.857  1039  7158 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-04 10:46:18.858  1039  7158 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 10:46:18.858  1039  7158 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 10:46:18.858  1039  7158 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 10:46:18.859  1930  7180 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-04 10:46:18.859  1930  7180 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-04 10:46:18.859  1930  7180 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-04 10:46:18.859  1039  1525 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-04 10:46:18.860  1039  1525 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:18.860  1039  1525 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:18.860  1039  1525 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:18.860  1039  1525 D LGWifiP2pService: InactiveState{ when=0 what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:18.860  1039  1525 D LGWifiP2pService: P2pEnabledState{ when=0 what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:18.860  1039  1525 D LGWifiP2pService: DefaultState{ when=0 what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:18.860  1039  1544 D wifi    : getting scan capabilities on interface[1] = 0xaf6723c0
08-04 10:46:18.860  1039  1544 D wifi    : failed to get capabilities : -3
08-04 10:46:18.860  1039  1544 E WifiScanningService: could not get scan capabilities
08-04 10:46:18.860  1039  1039 E WifiServerServiceExt: No p2p device connected
08-04 10:46:18.860  1039  1525 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:18.860  1039  1525 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:18.860  1039  1525 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:18.860  1039  1525 D LGWifiP2pService: InactiveState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:18.860  1039  1525 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:18.860  1039  1525 D LGWifiP2pService: DefaultState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:18.861  7071  7071 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-04 10:46:18.862  7071  7071 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-04 10:46:18.862  7071  7071 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-04 10:46:18.862  7071  7071 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 10:46:18.863  1930  2236 W WfdsService: DefaultState - msg [9441285] is not handled
08-04 10:46:18.863  1039  7158 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-04 10:46:18.863  1039  7158 E WifiMonitor: WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-04 10:46:18.863  7071  7071 I wpa_supplicant: p2p0,: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 10:46:18.863  1039  7158 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-04 10:46:18.863  1039  7158 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-04 10:46:18.863  1039  7158 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-04 10:46:18.863  1039  7158 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 10:46:18.863  1039  7158 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 10:46:18.863  1039  7158 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 10:46:18.863  1930  7180 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-04 10:46:18.863  1039  7158 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-04 10:46:18.864  1930  7180 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-04 10:46:18.864  1039  7158 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 10:46:18.864  1039  7158 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 10:46:18.864  1039  7158 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 10:46:18.864  1039  1526 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-04 10:46:18.864  1039  1526 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-04 10:46:18.864  1039  1525 D LGWifiP2pService: InactiveState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:18.865  1039  1525 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:18.865  1039  1526 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-04 10:46:18.865  1039  1526 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-04 10:46:18.865  1039  1526 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-04 10:46:18.865  7071  7071 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-04 10:46:18.865  7071  7071 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-04 10:46:18.866  1039  7158 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-04 10:46:18.866  1039  7158 E WifiMonitor: WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-04 10:46:18.866  1039  7158 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-04 10:46:18.866  1039  7158 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-04 10:46:18.866  1039  1526 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-04 10:46:18.866  1039  1526 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-04 10:46:18.867  1039  1526 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-04 10:46:18.867  1039  1526 D WifiNative-wlan0: doBoolean: SCAN
08-04 10:46:18.867  7071  7071 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-04 10:46:18.868  1039  1526 D WifiNative-wlan0: SCAN: returned true
08-04 10:46:18.868  1039  7158 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-04 10:46:18.868  1039  7158 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-04 10:46:18.868  1039  7158 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-04 10:46:18.868  1039  7158 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-04 10:46:18.868  1039  1526 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=136277  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-04 10:46:18.871  1039  1039 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-04 10:46:18.871  1039  1039 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 10:46:18.871  1039  1039 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-04 10:46:18.871  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:18.871  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-04 10:46:18.872  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 10:46:18.873  1039  1526 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=136282  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-04 10:46:18.873  1039  1526 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-04 10:46:18.874  1039  1526 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-04 10:46:18.874  1039  1526 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-04 10:46:18.874  1039  1526 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-04 10:46:18.875  1039  1526 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-04 10:46:18.876  1039  1039 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-04 10:46:18.876  1039  1039 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-04 10:46:18.892  7152  7152 D WeatherApplication: removeAccount
08-04 10:46:18.893  7152  7152 D WeatherApplication: Account.length = 0
08-04 10:46:18.893  7152  7152 E WeatherApplication: OPERATOR:OPEN
,08-04 10:46:18.897  7152  7152 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:46:18
,08-04 10:46:18.899  7152  7152 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-04 10:46:18.899  7152  7152 D Weather.Utils: 2 : All the weather widget is gone.
08-04 10:46:18.899  1039  1525 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:18.899  1039  1525 D LGWifiP2pService: P2pEnabledState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:18.899  1039  1525 D LGWifiP2pService: DefaultState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:18.900  7152  7152 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-04 10:46:18.902  7152  7152 D WeatherAncestor: connectivity changed - connection : true
08-04 10:46:18.902  7152  7152 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,08-04 10:46:18.906  1039  1526 E WifiStateMachine:  DisconnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-04 10:46:18.907  1039  1526 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-04 10:46:18.907  1039  1526 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-04 10:46:18.907  1039  1526 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-04 10:46:18.908  1039  1526 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-04 10:46:18.909  7152  7152 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-04 10:46:18.909  7152  7152 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-04 10:46:18.910  7152  7152 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-04 10:46:18.925  7152  7152 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-04 10:46:18.925  7152  7152 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:46:18
,08-04 10:46:18.999  1039  1633 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7184 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-04 10:46:19.003  1039  1633 I ActivityManager: Killing 6633:com.lge.bnr/1000 (adj 15): empty #17
,08-04 10:46:19.019   347   347 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 439us total 20.491ms
08-04 10:46:19.037   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 366us total 16.988ms
,08-04 10:46:19.052   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 296us total 14.612ms
,08-04 10:46:19.059  1039  1947 W libprocessgroup: failed to open /acct/uid_1000/pid_6633/cgroup.procs: No such file or directory
,08-04 10:46:19.168   278   371 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-04 10:46:19.168   278   371 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-04 10:46:19.168   278   371 W Vold    : Returning OperationFailed - no handler for errno 0
08-04 10:46:19.169  7184  7205 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-04 10:46:19.174   278   371 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-04 10:46:19.174   278   371 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-04 10:46:19.174   278   371 W Vold    : Returning OperationFailed - no handler for errno 0
08-04 10:46:19.175  7184  7205 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-04 10:46:19.181   278   371 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-04 10:46:19.181   278   371 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-04 10:46:19.181   278   371 W Vold    : Returning OperationFailed - no handler for errno 0
,08-04 10:46:19.184  7184  7209 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-04 10:46:19.190   278   371 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-04 10:46:19.190   278   371 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-04 10:46:19.190   278   371 W Vold    : Returning OperationFailed - no handler for errno 0
08-04 10:46:19.190  7184  7209 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-04 10:46:19.439  7184  7184 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-04 10:46:19.451  7184  7184 I LibraryLoader: Loading: webviewchromium
08-04 10:46:19.455  7184  7184 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 6872-6877)
08-04 10:46:19.456  7184  7184 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-04 10:46:19.473  7184  7184 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {30f395c7}
,08-04 10:46:19.478  7184  7184 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-04 10:46:19.480  7184  7184 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-04 10:46:19.510  7184  7184 I BrowserStartupController: Initializing chromium process, renderers=0
08-04 10:46:19.511  7184  7184 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-04 10:46:19.529  7184  7184 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-04 10:46:19.530  7184  7184 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-04 10:46:19.530  7184  7184 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,08-04 10:46:19.544   322  1374 V AudioPolicyService: registerClient() client 0xb14e7480, uid 10093
,08-04 10:46:19.547  7184  7235 W AudioManagerAndroid: Requires BLUETOOTH permission
08-04 10:46:19.569  7184  7184 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-04 10:46:19.569  7184  7184 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-04 10:46:19.569  7184  7184 I Adreno-EGL: Build Date: 12/12/14 금
08-04 10:46:19.569  7184  7184 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-04 10:46:19.569  7184  7184 I Adreno-EGL: Remote Branch: 
08-04 10:46:19.569  7184  7184 I Adreno-EGL: Local Patches: 
08-04 10:46:19.569  7184  7184 I Adreno-EGL: Reconstruct Branch: 
,08-04 10:46:19.681  7184  7184 I NSApplication: Starting up...
,08-04 10:46:19.723  1039  1875 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7248 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-04 10:46:19.726  1039  1875 I ActivityManager: Killing 6152:com.android.vending/u0a44 (adj 15): empty #17
08-04 10:46:19.814  1039  1973 W libprocessgroup: failed to open /acct/uid_10044/pid_6152/cgroup.procs: No such file or directory
,08-04 10:46:19.863  7248  7248 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-04 10:46:19.871  1039  1983 D WifiServiceImplEx: setWifiEnabled: false pid=6705, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-04 10:46:19.871  1039  1983 D WifiService: setWifiEnabled: false pid=6705, uid=10118
08-04 10:46:19.871  1039  1983 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-04 10:46:19.886  1039  1039 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-04 10:46:19.887  1039  1039 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-04 10:46:19.887  1039  1039 D Ulp_jni : JNI:system_update. Event-4
08-04 10:46:19.888  1039  1526 E WifiStateMachine:  DisconnectedState CMD_STOP_SUPPLICANT 0 0
08-04 10:46:19.889  1039  1526 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-04 10:46:19.890  1039  1526 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-04 10:46:19.890  1039  1526 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-04 10:46:19.899  1039  1039 D WifiScanningService: SCAN_AVAILABLE : 1
08-04 10:46:19.899  1039  1525 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:19.899  1039  1525 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:19.899  1039  1525 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@160b6d38
08-04 10:46:19.899  1039  1544 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-04 10:46:19.899  1039  1039 D RttService: SCAN_AVAILABLE : 1
08-04 10:46:19.899  1039  1525 D LGWifiP2pService: P2pDisablingState
08-04 10:46:19.900  1039  1525 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:19.900  1039  1525 D LGWifiP2pService: p2p socket connection lost
08-04 10:46:19.900  1039  1525 D LGWifiP2pService: P2pDisabledState
08-04 10:46:19.900  1930  1930 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-04 10:46:19.901  1930  1930 D WfdsService: WifiP2pState is changed : false
08-04 10:46:19.901  1930  2236 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
,08-04 10:46:19.901  1930  2236 D WfdsService: Set the WFDS Monitor: false
08-04 10:46:19.901  1039  1526 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-04 10:46:19.902   315   897 D CommandListener: Clearing all IP addresses on wlan0
08-04 10:46:19.903  1039  1545 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-04 10:46:19.903  1930  2236 D WfdsMonitor: WFDS Monitor is stopped
08-04 10:46:19.903  1930  2236 D WfdsService: STATE : WfdsDisabledState - enter
08-04 10:46:19.904  1930  7180 D CtrlSupplicant: Received on exit socket, terminate
08-04 10:46:19.904  1930  7180 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-04 10:46:19.904  1930  7180 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-04 10:46:19.904  1930  7180 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-04 10:46:19.904  1930  2241 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-04 10:46:19.904  1930  2236 W WfdsService: DefaultState - msg [9445378] is not handled
08-04 10:46:19.905  1039  1039 D WifiHS20: hidePasspointNotification off =false
08-04 10:46:19.906  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-04 10:46:19.906  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-04 10:46:19.907  1039  1039 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 10:46:19.907  1039  1039 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 10:46:19.907  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 10:46:19.907  1039  1039 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-04 10:46:19.909  1039  1039 D WifiHS20: hidePasspointNotification off =false
08-04 10:46:19.911  1039  1526 D WifiNative-p2p0: doBoolean: TERMINATE
08-04 10:46:19.912  1039  1039 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 10:46:19.912  1039  1039 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 10:46:19.912  1039  1039 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-04 10:46:19.913  1039  1526 D WifiNative-p2p0: TERMINATE: returned true
08-04 10:46:19.913  1039  1526 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-04 10:46:19.913  1039  1526 E WifiStateMachine: useWiFiOffloading() : false
08-04 10:46:19.913  1039  1526 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-04 10:46:19.916  1930  1930 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-04 10:46:19.918  1039  1039 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-04 10:46:19.918  1039  1039 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-04 10:46:19.918  1039  1039 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-04 10:46:19.919  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:46:19.919  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:46:19.919  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:19.919  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:19.919  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 10:46:19.919  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 10:46:19.919  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:46:19.919  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting ,to active network: false
08-04 10:46:19.919  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 10:46:19.919  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:46:19.919  6705  6705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-04 10:46:19.920  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:46:19.920  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:46:19.920  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:19.920  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:19.920  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 10:46:19.920  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 10:46:19.920  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:46:19.920  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:46:19.920  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 10:46:19.920  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:46:19.920  6705  6705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 10:46:19.928  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-04 10:46:19.928  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-04 10:46:19.929  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 10:46:19.931  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-04 10:46:20.000  7071  7071 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-04 10:46:20.000  7071  7071 I wpa_supplicant: monitor socket send errors count : 1
08-04 10:46:20.000  7071  7071 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1930-4\x00 that cannot receive messages
08-04 10:46:20.001  1039  7158 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-04 10:46:20.001  1039  7158 D WifiMonitor: Dropping event because (p2p0) is stopped
,08-04 10:46:20.144  7071  7071 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-04 10:46:20.147  1039  7158 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-04 10:46:20.147  1039  7158 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-04 10:46:20.147  1039  7158 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-04 10:46:20.147  1039  7158 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-04 10:46:20.151  1039  1526 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=137560
08-04 10:46:20.152  1039  1526 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=137561
08-04 10:46:20.152  7071  7071 W wpa_supplicant: USIM:  scard_deinit function
08-04 10:46:20.152  1039  7158 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-04 10:46:20.153  1039  7158 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-04 10:46:20.153  1039  1121 D Tethering: InitialState.processMessage what=4
08-04 10:46:20.155  1039  1526 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=137564  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-04 10:46:20.156  1039  1121 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-04 10:46:20.158  1039  1526 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=137566  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-04 10:46:20.158  1039  1526 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-04 10:46:20.159  1039  1526 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-04 10:46:20.177  6409  6409 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-04 10:46:20.184  6409  6448 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-04 10:46:20.194  2170  2170 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-04 10:46:20.215  7017  7017 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-04 10:46:20.215  7017  7017 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-04 10:46:20.215  7017  7017 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-04 10:46:20.215  7017  7017 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-04 10:46:20.219  7017  7017 I AppUp4:CustModeStarterReceiver: onReceive
,08-04 10:46:20.224  7017  7017 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3b31558a
08-04 10:46:20.224  7017  7017 D AppUp4:CustFacade: isCustomizationCompleted : false
08-04 10:46:20.224  7017  7017 D AppUp4:CustFacade: isPhone : true
08-04 10:46:20.224  7017  7017 D AppUp4:CustModeStarterReceiver: begin check event
08-04 10:46:20.224  7017  7017 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-04 10:46:20.227  4298  4298 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-04 10:46:20.227  4298  4298 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-04 10:46:20.229  4298  4298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-04 10:46:20.231  4298  4298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-04 10:46:20.240  7071  7071 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-04 10:46:20.247  1039  7158 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-04 10:46:20.247  1039  7158 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-TERMINATING 
08-04 10:46:20.247  1039  7158 D WifiMonitor: Disconnecting from the supplicant, no more events
08-04 10:46:20.247  1039  1526 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 33 0
08-04 10:46:20.373  1039  1875 I art     : Explicit concurrent mark sweep GC freed 71442(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 2.027ms total 139.963ms
08-04 10:46:20.377  1930  1930 D WfdsService: Supplicant Connection state is changed : false
08-04 10:46:20.378  1930  2236 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-04 10:46:20.378  1930  2236 D WfdsService: Set the WFDS Monitor: false
08-04 10:46:20.378  1930  2236 D WfdsMonitor: WFDS Monitor is stopped
,08-04 10:46:20.384  1039  1526 D WifiOffDelayIfNotUsed: stopMonitoring
08-04 10:46:20.385  1039  1526 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-04 10:46:20.385  1039  1526 E WifiStateMachine: useWiFiOffloading() : false
08-04 10:46:20.385  1039  1526 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-04 10:46:20.386  4298  7295 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-04 10:46:20.387  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 10:46:20.388  1930  1930 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-04 10:46:20.390  4298  7297 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,08-04 10:46:20.390  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:46:20.391  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:46:20.392  1039  1039 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-04 10:46:20.392  2453  2453 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 10:46:20.392  1039  1530 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-04 10:46:20.392  1039  1530 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-04 10:46:20.393  4298  7297 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-04 10:46:20.396  7043  7043 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-04 10:46:20.417  3467  3467 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-04 10:46:20.417  3467  3467 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-04 10:46:20.417  3467  3467 I LgeMiscReceiver: networkInfo.isConnected() = false
08-04 10:46:20.424  7090  7090 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-04 10:46:20.425  7090  7090 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-04 10:46:20.425  7043  7298 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 10:46:20.435  7152  7152 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:46:20
,08-04 10:46:20.437  7152  7152 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-04 10:46:20.437  7152  7152 D Weather.Utils: 2 : All the weather widget is gone.
08-04 10:46:20.437  7152  7152 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-04 10:46:20.436  6919  7301 W FormManager: Network not available. Please check & try again.
08-04 10:46:20.438  7152  7152 D WeatherAncestor: connectivity changed - connection : true
08-04 10:46:20.438  7152  7152 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3de13018
08-04 10:46:20.439  7152  7152 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-04 10:46:20.439  7152  7152 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-04 10:46:20.439  7152  7152 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-04 10:46:20.439  7152  7152 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-04 10:46:20.439  6919  7302 V FormManager: Network unavailable.
08-04 10:46:20.439  7152  7152 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:46:20
08-04 10:46:20.447  6919  7302 V FormManager: Network unavailable.
,08-04 10:46:20.462  6815  6815 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-04 10:46:20.462  6815  6815 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-04 10:46:20.462  6815  6815 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-04 10:46:20.462  6815  6815 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-04 10:46:20.462  6815  6815 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-04 10:46:20.463  6815  6815 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-04 10:46:20.463  6815  6815 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-04 10:46:20.463  6815  6815 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-04 10:46:20.463  6815  6815 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-04 10:46:20.463  6815  6815 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-04 10:46:20.463  6815  6815 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-04 10:46:20.470  6834  6834 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-04 10:46:20.472  6815  6815 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-04 10:46:20.476  6919  7304 W FormManager: Network not available. Please check & try again.
08-04 10:46:20.478  6815  6815 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 10:46:20.482  6919  7305 V FormManager: Network unavailable.
08-04 10:46:20.484  6919  7305 V FormManager: Network unavailable.
08-04 10:46:20.495  6834  6834 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-04 10:46:20.500  6815  6815 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-04 10:46:20.504  6919  7308 V FormManager: Network unavailable.
08-04 10:46:20.505  6919  7307 W FormManager: Network not available. Please check & try again.
08-04 10:46:20.507  6919  7308 V FormManager: Network unavailable.
,08-04 10:46:20.509  6815  6815 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-04 10:46:20.522  4298  4298 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-04 10:46:20.523  4298  4298 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-04 10:46:20.524  4298  4298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-04 10:46:20.526  4298  4298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-04 10:46:20.531  4298  7309 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-04 10:46:20.533  4298  7310 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-04 10:46:20.533  4298  7310 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-04 10:46:20.561  1039  1874 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7311 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-04 10:46:20.644  6667  6992 D UEI.SmartControl: Internal timer expired: 2
,08-04 10:46:20.644  6667  6992 D UEI.SmartControl: unbind internal service
,08-04 10:46:20.705  7311  7311 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-04 10:46:20.705  7311  7311 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-04 10:46:20.710  6667  6986 D serial_port: close(fd = 24)
,08-04 10:46:20.713  6667  6986 I UEI.SmartControl: Serial port is closed.
08-04 10:46:20.714  7311  7311 V [BNRBootReceiver]: Boot Receiver Return
08-04 10:46:20.715  7311  7311 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-04 10:46:20.722  6409  6409 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-04 10:46:20.733  6815  6815 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-04 10:46:20.738  6815  6815 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 10:46:20.748  6869  6869 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-04 10:46:20.748  6869  6869 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-04 10:46:20.749  6869  6869 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-04 10:46:20.756  6409  6409 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-04 10:46:20.760  6834  6834 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-04 10:46:20.760  6834  6834 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-04 10:46:20.760  6834  6834 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-04 10:46:20.764  6815  6815 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-04 10:46:20.771  6815  6815 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 10:46:20.779  6869  6869 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-04 10:46:20.781  6869  6869 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-04 10:46:20.783  6869  6869 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-04 10:46:20.787  6409  6409 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-04 10:46:20.791  6834  6834 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-04 10:46:20.791  6834  6834 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-04 10:46:20.791  6834  6834 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-04 10:46:20.796  6815  6815 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-04 10:46:20.802  6815  6815 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 10:46:20.808  6869  6869 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-04 10:46:20.808  6869  6869 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-04 10:46:20.812  6869  6869 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-04 10:46:20.821  6834  6834 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-04 10:46:20.827  6815  6815 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-04 10:46:20.834  6919  7336 W FormManager: Network not available. Please check & try again.
08-04 10:46:20.840  6919  7337 V FormManager: Network unavailable.
08-04 10:46:20.840  6815  6815 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 10:46:20.848  6919  7337 V FormManager: Network unavailable.
,08-04 10:46:20.859  1039  1874 I ActivityManager: Killing 6796:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-04 10:46:20.890  4298  4298 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-04 10:46:20.891  4298  4298 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-04 10:46:20.891  1039  1766 W libprocessgroup: failed to open /acct/uid_10037/pid_6796/cgroup.procs: No such file or directory
,08-04 10:46:20.895  4298  4298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-04 10:46:20.898  4298  4298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-04 10:46:20.906  4298  7338 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-04 10:46:20.907  6834  6834 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-04 10:46:20.907  6834  6834 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-04 10:46:20.907  6834  6834 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-04 10:46:20.912  6815  6815 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-04 10:46:20.920  6815  6815 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 10:46:20.923  4298  7339 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-04 10:46:20.923  4298  7339 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-04 10:46:20.935  6919  7342 V FormManager: Network unavailable.
,08-04 10:46:20.937  6919  7341 W FormManager: Network not available. Please check & try again.
,08-04 10:46:20.941  6919  7342 V FormManager: Network unavailable.
,08-04 10:46:22.890  1039  1973 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-04 10:46:22.891  1039  1973 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-04 10:46:22.916  1039  1039 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-04 10:46:22.916  1039  1039 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-04 10:46:22.917  1039  1039 D Ulp_jni : JNI:system_update. Event-4
,08-04 10:46:22.921  1039  1121 D BluetoothManagerService: Message: 1
08-04 10:46:22.921  1039  1121 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-04 10:46:22.954  1039  1121 D BluetoothManagerService: Message: 20
08-04 10:46:22.954  1039  1121 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3407fa49:true
,08-04 10:46:22.958  6952  6952 D BluetoothAdapterState: make
08-04 10:46:22.963  6952  6952 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-04 10:46:22.963  6952  6952 I bluedroid-qcom: init
08-04 10:46:22.964  6952  7347 I BluetoothAdapterState: Entering OffState
08-04 10:46:22.964  6952  6952 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-04 10:46:22.965  6952  6952 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-04 10:46:22.965  6952  6952 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-04 10:46:22.965  6952  6952 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-04 10:46:22.965  6952  6952 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-04 10:46:22.967  6952  6952 I bluedroid-qcom: get_profile_interface socket
08-04 10:46:22.967  6952  6952 I bluedroid-qcom: get_profile_interface map_client
,08-04 10:46:22.972  6952  7351 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-04 10:46:22.974  6952  7351 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-04 10:46:22.967  7350  7350 W bdaddr_loader: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 10:46:22.967  7350  7350 W bdaddr_loader: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 10:46:22.986  7350  7350 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-04 10:46:22.986  7350  7350 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-04 10:46:22.986  7350  7350 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-04 10:46:22.990  1039  1039 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-04 10:46:22.990  1039  1039 D BluetoothManagerService: Stored Bluetooth name: G3
08-04 10:46:22.992  1039  1039 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-04 10:46:22.992  1039  1121 D BluetoothManagerService: Message: 40
08-04 10:46:22.992  1039  1121 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-04 10:46:22.993  6952  6971 I bluedroid-qcom: config_hci_snoop_log
08-04 10:46:22.994  1039  1121 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-04 10:46:22.995  1039  1121 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-04 10:46:22.996  7350  7350 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-04 10:46:23.002  7350  7350 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-04 10:46:23.002  7350  7350 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-04 10:46:23.008  6952  7347 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-04 10:46:23.008  6952  7351 D BluetoothAdapterProperties: Name is: G3
08-04 10:46:23.009  6952  7347 D BluetoothAdapterProperties: Setting state to 11
08-04 10:46:23.009  6952  7347 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-04 10:46:23.009  1039  1121 D BluetoothManagerService: Message: 60
08-04 10:46:23.009  1039  1121 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-04 10:46:23.010  1039  1121 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-04 10:46:23.011  6952  7347 I LGBluetoothServiceJni: classInitNative: succeeds
08-04 10:46:23.017  1930  1930 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-04 10:46:23.020  1590  1590 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-04 10:46:23.024  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:46:23.025  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:46:23.026  6815  6815 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-04 10:46:23.034  6952  6952 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-04 10:46:23.034  6952  6952 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:23.034  6952  6952 V BluetoothPbapReceiver: ***********state = 11
,08-04 10:46:23.040  2170  2170 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-04 10:46:23.065  6952  7347 D BluetoothBondStateMachine: make
,08-04 10:46:23.072  6952  7364 I BluetoothBondStateMachine: StableState(): Entering Off State
08-04 10:46:23.072  6952  7347 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3de13018
08-04 10:46:23.072  6952  7347 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-04 10:46:23.072  6952  7347 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3de13018
08-04 10:46:23.072  6952  7347 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-04 10:46:23.073  6952  7347 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-04 10:46:23.076  6952  7347 E BluetoothAdapterService: File transfer profiles supported!!
08-04 10:46:23.104  1039  1563 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7369 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-04 10:46:23.109  6952  7347 E BluetoothAdapterService: File transfer profiles supported!!
08-04 10:46:23.111  6952  6952 D HeadsetService: Received start request. Starting profile...
08-04 10:46:23.111  6952  6952 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-04 10:46:23.111  6952  6952 D LGBluetoothHfpAdapter: Version 1.6
08-04 10:46:23.113  6952  6952 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-04 10:46:23.114  6952  7347 E BluetoothAdapterService: File transfer profiles supported!!
08-04 10:46:23.114  6952  6952 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-04 10:46:23.114  6952  6952 D HeadsetStateMachine: make
08-04 10:46:23.118  6952  7347 E BluetoothAdapterService: File transfer profiles supported!!
,08-04 10:46:23.124  6952  7347 E BluetoothAdapterService: File transfer profiles supported!!
08-04 10:46:23.129  6952  7347 E BluetoothAdapterService: File transfer profiles supported!!
08-04 10:46:23.133  6952  7347 E BluetoothAdapterService: File transfer profiles supported!!
08-04 10:46:23.138  6952  6952 D LgDataFeature: LgDataFeature() Constructor: none
08-04 10:46:23.138  6952  6952 D LgDataFeature: LgDataFeature() Constructor Done, null
08-04 10:46:23.141  6952  6952 D HeadsetStateMachine: max_hf_connections = 1
08-04 10:46:23.141  6952  6952 I bluedroid-qcom: get_profile_interface handsfree
08-04 10:46:23.143  6952  6952 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-04 10:46:23.143   322  1373 V AudioPolicyService: registerClient() client 0xb14b5360, uid 1002
08-04 10:46:23.143   322  1374 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-04 10:46:23.143   322  1374 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-04 10:46:23.143   322  1374 V AudioPolicyManagerEx: getOutput() returns output 2
08-04 10:46:23.143  6952  6952 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-04 10:46:23.144   322  1372 V AudioFlinger: registerClient() client 0xb1185b08, pid 6952
08-04 10:46:23.144   322  1367 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-04 10:46:23.144   322  1367 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-04 10:46:23.144  1039  1929 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-04 10:46:23.144  1039  1929 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-04 10:46:23.144  1590  1610 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-04 10:46:23.145  1590  1610 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-04 10:46:23.145  1840  1855 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-04 10:46:23.145  1840  1855 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-04 10:46:23.145  3467  3482 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-04 10:46:23.145  3467  3482 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-04 10:46:23.145  6952  6969 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-04 10:46:23.145   322  1368 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-04 10:46:23.145   322  1368 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-04 10:46:23.145  1039  1875 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-04 10:46:23.145  1039  1875 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-04 10:46:23.145  1590  1614 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-04 10:46:23.145  1590  1614 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-04 10:46:23.145  1840  3970 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-04 10:46:23.145  1840  3970 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-04 10:46:23.145  3467  3483 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-04 10:46:23.145  3467  3483 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-04 10:46:23.146  6952  6969 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-04 10:46:23.146  6952  6969 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-04 10:46:23.146  6952  6969 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-04 10:46:23.146  6952  6952 V ToneGenerator: Create Track: 0xb4928a80
08-04 10:46:23.146  6952  6952 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-04 10:46:23.146  6952  6952 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-04 10:46:23.146   322  1373 V AudioPolicyManager: getOu,tputForAttr() usage=3, content=4, tag= flags=00000000
08-04 10:46:23.146   322  1373 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-04 10:46:23.146   322  1373 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-04 10:46:23.146   322  1373 V AudioPolicyManagerEx: getOutput() returns output 2
08-04 10:46:23.146  6952  7347 V LGMDMManager: Create singleton instance
08-04 10:46:23.146   322  1374 I AudioFlinger: isAudioPlaybackHookOn() false
08-04 10:46:23.146   322  1372 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-04 10:46:23.146   322  1372 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-04 10:46:23.146   322  1372 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-04 10:46:23.146   322  1372 V AudioPolicyManagerEx: getOutput() returns output 2
08-04 10:46:23.147  6952  6952 V AudioSystem: getLatency() output 2, latency 50
08-04 10:46:23.147  6952  6952 V AudioSystem: getFrameCount() output 2, frameCount 960
08-04 10:46:23.147  6952  6952 V AudioTrack: createTrack_l() output 2 afLatency 50
08-04 10:46:23.147   322   322 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-04 10:46:23.147   322   322 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-04 10:46:23.147   322   322 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-04 10:46:23.147   322   322 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-04 10:46:23.147   322   322 V AudioFlinger: createTrack() lSessionId: 22
08-04 10:46:23.147  6952  6952 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-04 10:46:23.148   322  1373 V AudioFlinger: acquiring 22 from 6952, for 6952
08-04 10:46:23.148   322  1373 V AudioFlinger:  added new entry for 22
08-04 10:46:23.148  6952  6952 V ToneGenerator: ToneGenerator INIT OK, time: 140569
08-04 10:46:23.148  6952  6952 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3de13018
08-04 10:46:23.149  6952  7385 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-04 10:46:23.149  6952  7385 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-04 10:46:23.149  6952  7385 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-04 10:46:23.149  6952  7385 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-04 10:46:23.149   322  1374 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6952
08-04 10:46:23.150   322  1374 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-04 10:46:23.150   322  1374 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-04 10:46:23.150   322  1374 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-04 10:46:23.150  6952  6952 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3de13018
08-04 10:46:23.150   322  1374 V compress_voip: voice_extn_compress_voip_set_parameters: exit
,08-04 10:46:23.150   322  1374 V voice   : voice_set_parameters: exit with code(0)
08-04 10:46:23.150   322  1374 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-04 10:46:23.150   322  1374 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-04 10:46:23.150   322  1374 V msm8974_platform: platform_set_parameters: exit with code(0)
08-04 10:46:23.150   322  1374 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-04 10:46:23.150   322  1374 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-04 10:46:23.150   322  1374 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-04 10:46:23.151  6952  7385 V ToneGenerator: ToneGenerator destructor
08-04 10:46:23.151  6952  7385 V ToneGenerator: stopTone
,08-04 10:46:23.151  6952  7385 V ToneGenerator: Delete Track: 0xb4928a80
08-04 10:46:23.152  6952  6952 D A2dpService: Received start request. Starting profile...
08-04 10:46:23.152  6952  6952 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-04 10:46:23.153  6952  6952 V Avrcp   : make
08-04 10:46:23.153  6952  6952 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-04 10:46:23.153  6952  6952 I bluedroid-qcom: get_profile_interface avrcp
,08-04 10:46:23.155  6952  7347 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false,
08-04 10:46:23.155  6952  7385 V AudioTrack: ~AudioTrack, releasing session id from 6952 on behalf of 6952
08-04 10:46:23.155   322   322 V AudioFlinger: releasing 22 from 6952 for 6952
08-04 10:46:23.155   322   322 V AudioFlinger:  decremented refcount to 0
08-04 10:46:23.155   322   322 V AudioFlinger: purging stale effects
08-04 10:46:23.155   322   322 V AudioPolicyService: AudioCommandThread() adding release output 2
08-04 10:46:23.155   322   322 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-04 10:46:23.155   322  1277 V AudioPolicyService: AudioCommandThread() waking up
08-04 10:46:23.155   322  1277 V AudioPolicyService: AudioCommandThread() processing release output 2
08-04 10:46:23.155   322  1277 V AudioPolicyManager: releaseOutput() 2,
08-04 10:46:23.155   322  1277 V AudioPolicyService: AudioCommandThread() going to sleep
08-04 10:46:23.155   322   322 V AudioFlinger: PlaybackThread::Track destructor
08-04 10:46:23.155   322   322 V AudioFlinger: removeClient_l() pid 6952, calling pid 322
08-04 10:46:23.162  6952  6952 V AudioManager: registerRemoteController: size of Media player list: 0
08-04 10:46:23.164  6952  6952 E AudioManager: No RCC entry present to update
08-04 10:46:23.164  6952  6952 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-04 10:46:23.167  6952  6952 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-04 10:46:23.167  6952  6952 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-04 10:46:23.167  6952  6952 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-04 10:46:23.170  6952  6952 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-04 10:46:23.249  7369  7369 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,08-04 10:46:23.249  7369  7369 W LG Account v2.2: No ProfileInfo entries
08-04 10:46:23.250  7369  7369 I LG Account v2.2: isEnabled: false
08-04 10:46:23.250  7369  7369 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-04 10:46:23.250  7369  7369 I Feature : [Lifetracker]Country: EU
08-04 10:46:23.250  7369  7369 I Feature : [Lifetracker]Operator: OPEN
08-04 10:46:23.250  7369  7369 I Feature : [Lifetracker]Ranking support: false
08-04 10:46:23.250  7369  7369 I Feature : [Lifetracker]Comfort support: false
08-04 10:46:23.250  7369  7369 I Feature : [Lifetracker]Accessory: true
08-04 10:46:23.250  7369  7369 I Feature : [Lifetracker]Health device: true
08-04 10:46:23.250  7369  7369 I Feature : [Lifetracker]Extra Pedometer: false
08-04 10:46:23.250  7369  7369 I Feature : [Lifetracker]Blood glucose device: false
08-04 10:46:23.250  7369  7369 I Feature : [Lifetracker]Device Number: 3
08-04 10:46:23.256  1039  1973 V SIM_STK : Menu title from STK is T-Mobile
08-04 10:46:23.256  1039  1973 V SIM_STK : Menu title from STK is T-Mobile
08-04 10:46:23.262  6815  6815 D BluetoothPermissionRequest: onReceive
,08-04 10:46:23.273  6815  6815 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-04 10:46:23.349  1039  1947 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-04 10:46:23.356  6952  6952 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-04 10:46:23.361  6952  6952 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,08-04 10:46:23.361  6952  6952 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-04 10:46:23.361  6952  6952 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-04 10:46:23.361  6952  6952 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-04 10:46:23.361  6952  6952 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-04 10:46:23.361  6952  6952 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-04 10:46:23.361  6952  6952 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-04 10:46:23.361  6952  6952 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-04 10:46:23.361  6952  6952 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-04 10:46:23.362  6952  6952 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-04 10:46:23.362  6952  6952 I BluetoothA2dpServiceJni: classInitNative
08-04 10:46:23.362  6952  6952 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-04 10:46:23.362  6952  6952 D A2dpStateMachine: make
08-04 10:46:23.365  6952  6952 I bluedroid-qcom: get_profile_interface a2dp
08-04 10:46:23.365  6952  7395 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-04 10:46:23.368  6952  6952 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-04 10:46:23.368  6952  6952 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
,08-04 10:46:23.369  6952  6952 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3de13018
,08-04 10:46:23.369  6952  7394 D A2dpStateMachine: Enter Disconnected: -2
08-04 10:46:23.370  6952  6952 I BluetoothHidServiceJni: classInitNative: succeeds
08-04 10:46:23.371  6952  6952 D HidService: Received start request. Starting profile...
08-04 10:46:23.371  6952  6952 I bluedroid-qcom: get_profile_interface hidhost
08-04 10:46:23.371  6952  6952 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3de13018
08-04 10:46:23.372  6952  6952 I BluetoothHealthServiceJni: classInitNative: succeeds
08-04 10:46:23.373  6952  6952 D HealthService: Received start request. Starting profile...
08-04 10:46:23.376  6952  6952 I bluedroid-qcom: get_profile_interface health
08-04 10:46:23.377  6952  6952 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-04 10:46:23.377  6952  6952 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3de13018
08-04 10:46:23.378  6952  6952 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-04 10:46:23.379  6952  6952 D PanService: Received start request. Starting profile...
08-04 10:46:23.379  6952  6952 D BluetoothPanServiceJni: initializeNative(L110): pan
08-04 10:46:23.379  6952  6952 I bluedroid-qcom: get_profile_interface pan
,08-04 10:46:23.387  6952  6952 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-04 10:46:23.387  6952  6952 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3de13018
08-04 10:46:23.388  6952  6952 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-04 10:46:23.392  6952  6952 D BtGatt.DebugUtils: handleDebugAction() action=null
08-04 10:46:23.393  6952  6952 D BtGatt.GattService: Received start request. Starting profile...
08-04 10:46:23.393  6952  6952 D BtGatt.GattService: start()
08-04 10:46:23.393  6952  6952 I bluedroid-qcom: get_profile_interface gatt
08-04 10:46:23.393  6952  6952 D BtGatt.AdvertiseManager: advertise manager created
,08-04 10:46:23.405  6952  6952 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3de13018
08-04 10:46:23.406  6952  6952 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3de13018
08-04 10:46:23.406  6952  6952 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-04 10:46:23.407  6952  6952 V BluetoothMapService: BluetoothMapBinder()
,08-04 10:46:23.409  6952  6952 D BluetoothMapService: Received start request. Starting profile...
08-04 10:46:23.409  6952  6952 D BluetoothMapService: start()
08-04 10:46:23.411  6952  6952 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-04 10:46:23.411  6952  6952 D BluetoothMapEmailAppObserver: createReceiver()
08-04 10:46:23.412  6952  6952 D BluetoothMapEmailAppObserver: initObservers()
08-04 10:46:23.412  6952  6952 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-04 10:46:23.418  6952  6952 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3de13018
08-04 10:46:23.418  6952  6952 D HeadsetStateMachine: Proxy object connected
,08-04 10:46:23.419  6952  6952 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-04 10:46:23.419  6952  6952 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-04 10:46:23.420  6952  7385 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-04 10:46:23.422  6952  7385 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-04 10:46:23.422  6952  6952 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-04 10:46:23.422  6952  7385 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-04 10:46:23.424  6952  6952 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-04 10:46:23.428  6952  6952 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-04 10:46:23.430  6952  6952 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-04 10:46:23.432  6952  6952 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-04 10:46:23.432  6952  6952 V PanService: [BTUI] SIM Extra State :ABSENT
08-04 10:46:23.438  6952  6952 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-04 10:46:23.438  6952  6952 V BluetoothMapService: Handler(): got msg=1
08-04 10:46:23.439  6952  7347 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-04 10:46:23.440  6952  7347 I bluedroid-qcom: enable
08-04 10:46:23.440  6952  6952 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:23.440  6952  7405 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-04 10:46:23.440  6952  7405 I bt-btu  : btu_task pending for preload complete event
,08-04 10:46:23.441  6952  7347 I bt_hci_bdroid: init
,08-04 10:46:23.441  6952  6952 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-04 10:46:23.442  6952  6952 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-04 10:46:23.442  6952  6952 V BluetoothSapReceiver: SapReceiver onReceive 
08-04 10:46:23.442  6952  6952 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:23.442  6952  6952 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-04 10:46:23.446  6952  7347 I bt_vendor: bt-vendor : init
08-04 10:46:23.446  6952  7347 I bt_vendor: bt-vendor : get_bt_soc_type
08-04 10:46:23.446  6952  7347 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-04 10:46:23.446  6952  7347 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-04 10:46:23.446  6952  7347 D bt_userial_mct: userial_init
08-04 10:46:23.446  6952  7347 D bt_hci_bdroid: set_power 1
08-04 10:46:23.446  6952  7347 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-04 10:46:23.446  6952  7347 I bt_vendor: Starting hciattach daemon
08-04 10:46:23.446  6952  7347 I bt_vendor: try to set true
08-04 10:46:23.447  7408  7408 W sh      : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-04 10:46:23.447  7408  7408 W sh      : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 10:46:23.478  7409  7409 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-04 10:46:23.579  7415  7415 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-04 10:46:23.594  7416  7416 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-04 10:46:23.637  7418  7418 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-04 10:46:23.649  7419  7419 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-04 10:46:23.660  7420  7420 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-04 10:46:23.672  7421  7421 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-04 10:46:23.702  7423  7423 I libmdmdetect: ESOC framework not supported
08-04 10:46:23.704  7423  7423 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-04 10:46:23.717  7423  7423 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-04 10:46:23.717  7423  7423 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
,08-04 10:46:23.717  7423  7423 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
,08-04 10:46:23.717  7423  7423 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
,08-04 10:46:23.717  7423  7423 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-04 10:46:23.717  7423  7423 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-04 10:46:23.717  7423  7423 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-04 10:46:23.761  7423  7424 E QC-QMI  : qmi_client [7423] 14: failed to locate client data
08-04 10:46:23.762   461   461 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,08-04 10:46:23.762   461   461 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-04 10:46:23.824  7431  7431 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-04 10:46:23.841  7432  7432 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-04 10:46:23.857  6952  7347 I bt_vendor: bluetooth satus is on
08-04 10:46:23.857  6952  7347 D bt_hci_bdroid: preload
,08-04 10:46:23.860  6952  7407 D bt_userial_mct: userial_open(port:0)
08-04 10:46:23.860  6952  7407 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-04 10:46:23.864  6952  7407 I bt_vendor: Done intiailizing UART
08-04 10:46:23.865  6952  7407 I bt_vendor: Done intiailizing UART
08-04 10:46:23.865  6952  7407 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-04 10:46:23.865  6952  7407 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-04 10:46:23.866  6952  7405 I bt-btu  : btu_task received preload complete event
08-04 10:46:23.866  6952  7405 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-04 10:46:23.866  6952  7405 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-04 10:46:23.868  6952  7405 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-04 10:46:23.877  6952  7434 D bt_userial_mct: Entering userial_read_thread()
,08-04 10:46:23.882  6952  7405 I         : BTE_InitTraceLevels -- TRC_HCI
,08-04 10:46:23.882  6952  7405 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-04 10:46:23.882  6952  7405 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-04 10:46:23.882  6952  7405 I         : BTE_InitTraceLevels -- TRC_AVDT
08-04 10:46:23.882  6952  7405 I         : BTE_InitTraceLevels -- TRC_AVRC
08-04 10:46:23.882  6952  7405 I         : BTE_InitTraceLevels -- TRC_A2D
08-04 10:46:23.882  6952  7405 I         : BTE_InitTraceLevels -- TRC_BNEP
08-04 10:46:23.882  6952  7405 I         : BTE_InitTraceLevels -- TRC_BTM
08-04 10:46:23.882  6952  7405 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-04 10:46:23.882  6952  7405 I         : BTE_InitTraceLevels -- TRC_GAP
08-04 10:46:23.882  6952  7405 I         : BTE_InitTraceLevels -- TRC_PAN
08-04 10:46:23.882  6952  7405 I         : BTE_InitTraceLevels -- TRC_SDP
08-04 10:46:23.882  6952  7405 I         : BTE_InitTraceLevels -- TRC_GATT
08-04 10:46:23.882  6952  7405 I         : BTE_InitTraceLevels -- TRC_SMP
08-04 10:46:23.882  6952  7405 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-04 10:46:23.882  6952  7405 I         : BTE_InitTraceLevels -- TRC_BTIF
08-04 10:46:23.937  6952  7405 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-04 10:46:23.937  6952  7405 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa019d061 
08-04 10:46:23.937  6952  7405 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa019d061 
,08-04 10:46:23.956  1039  1532 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-04 10:46:23.980  6952  7351 E bt-btif : Calling BTA_HhEnable
,08-04 10:46:23.980  6952  7351 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-04 10:46:23.981  6952  7351 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-04 10:46:23.987  6952  7405 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
,08-04 10:46:23.987  6952  7405 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-04 10:46:23.987  6952  7405 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-04 10:46:23.987  6952  7405 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-04 10:46:23.987  6952  7405 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-04 10:46:23.991  1039  1039 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-04 10:46:23.991  1039  1039 D BluetoothManagerService: Stored Bluetooth name: G3
08-04 10:46:23.992  6952  7351 D BluetoothAdapterProperties: Name is: G3
08-04 10:46:23.995  6952  7351 D BluetoothAdapterProperties: Scan Mode:20
08-04 10:46:23.996  6952  7351 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-04 10:46:24.001  6952  7351 D bt_hci_bdroid: postload
08-04 10:46:24.001  6952  7407 D bt_hci_bdroid: Used up Tx Cmd credits
08-04 10:46:24.002  6952  7407 D bt_hci_bdroid: Used up Tx Cmd credits
08-04 10:46:24.002  6952  7405 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-04 10:46:24.003  6952  7351 D bte_conf: Device ID record 1 : primary
08-04 10:46:24.003  6952  7351 D bte_conf:   vendorId            = 00c4
08-04 10:46:24.003  6952  7351 D bte_conf:   vendorIdSource      = 0001
08-04 10:46:24.003  6952  7351 D bte_conf:   product             = 13a1
08-04 10:46:24.003  6952  7351 D bte_conf:   version             = 1000
08-04 10:46:24.003  6952  7351 D bte_conf:   clientExecutableURL = 
08-04 10:46:24.003  6952  7351 D bte_conf:   serviceDescription  = 
08-04 10:46:24.003  6952  7351 D bte_conf:   documentationURL    = 
08-04 10:46:24.003  6952  7351 D bte_conf: bte_load_did_conf no section named DID2.
08-04 10:46:24.006  6952  7407 D bt_hci_bdroid: Used up Tx Cmd credits
08-04 10:46:23.997  7436  7436 W sh      : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 10:46:24.009  6952  7351 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-04 10:46:24.009  6952  7347 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-04 10:46:24.010  6952  7347 D BluetoothAdapterProperties: ScanMode =  20
08-04 10:46:24.010  6952  7347 D BluetoothAdapterProperties: State =  11
08-04 10:46:24.010  6952  7347 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-04 10:46:24.010  6952  7347 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-04 10:46:24.010  6952  7347 D BluetoothAdapterProperties: Setting state to 12
08-04 10:46:24.010  6952  7347 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-04 10:46:24.007  7436  7436 W sh      : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-04 10:46:24.017  1039  1121 D BluetoothManagerService: Message: 60
08-04 10:46:24.017  1039  1121 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-04 10:46:24.017  1039  1121 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-04 10:46:24.018  6952  7405 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-04 10:46:24.021  6952  7405 W bt-smp  : Plain text(LSB ~ MSB) = ff 79 78 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-04 10:46:24.021  6952  7405 W bt-smp  : Encrypted text(LSB ~ MSB) = f8 37 85 3b 53 ac 97 26 26 e7 29 53 50 e6 e8 2c 
08-04 10:46:24.021  6952  7407 D bt_hci_bdroid: Used up Tx Cmd credits
08-04 10:46:24.022  6952  7405 W bt-btm  : Stopping oneshot timer
08-04 10:46:24.022  6952  7434 E bt_mct  : hci lib postload completed
08-04 10:46:24.022  6952  7351 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-04 10:46:24.043  6952  7405 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-04 10:46:24.044  6952  7405 W bt-smp  : Plain text(LSB ~ MSB) = 3b ba 6e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-04 10:46:24.044  6952  7405 W bt-smp  : Encrypted text(LSB ~ MSB) = f0 96 b3 7c 7a 19 c4 9a a9 44 fa ce 82 4b f3 9d 
,08-04 10:46:24.047  6952  7405 W bt-btm  : Stopping oneshot timer
08-04 10:46:24.060  6952  7351 D BluetoothAdapterProperties: Discoverable Timeout:120
08-04 10:46:24.060  6952  7351 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-04 10:46:24.064  6952  7347 I BluetoothAdapterState: Entering On State
08-04 10:46:24.065  1840  3537 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 10:46:24.068  6952  7405 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-04 10:46:24.068  6952  7405 W bt-smp  : Plain text(LSB ~ MSB) = eb ab 40 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-04 10:46:24.068  6952  7405 W bt-smp  : Encrypted text(LSB ~ MSB) = d0 6c 6f 2a 47 84 18 7e 26 a6 6a bc 26 9e 12 a6 
08-04 10:46:24.069  6952  7405 W bt-btm  : Stopping oneshot timer
08-04 10:46:24.074  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:46:24.074  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:24.074  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:24.074  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 10:46:24.074  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 10:46:24.074  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:46:24.074  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:46:24.074  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 10:46:24.082  6952  7405 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-04 10:46:24.082  6952  7405 W bt-smp  : Plain text(LSB ~ MSB) = d4 9e 4a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-04 10:46:24.082  6952  7405 W bt-smp  : Encrypted text(LSB ~ MSB) = b1 0c 9b 17 c5 6e 07 ae 0a d5 e4 c8 68 1c 18 e9 
08-04 10:46:24.083  6952  7405 W bt-btm  : Stopping oneshot timer
08-04 10:46:24.097  6705  6705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-04 10:46:24.104  6952  7405 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-04 10:46:24.104  6952  7405 W bt-smp  : Plain text(LSB ~ MSB) = 70 a7 7b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-04 10:46:24.105  6952  7405 W bt-smp  : Encrypted text(LSB ~ MSB) = 53 45 21 36 ac 9a 55 9f 24 b2 e1 1d 19 02 55 10 
08-04 10:46:24.105  6952  7405 W bt-btm  : Stopping oneshot timer
08-04 10:46:24.117  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:46:24.117  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:24.117  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:24.117  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 10:46:24.117  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 10:46:24.117  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:46:24.117  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:46:24.117  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 10:46:24.127  7441  7441 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-04 10:46:24.130  6705  6705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-04 10:46:24.138  6952  7347 D LGBluetoothServiceAdapter: [BTUI] OnState
,08-04 10:46:24.138  6952  7347 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-04 10:46:24.141  6952  7347 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-04 10:46:24.149  6952  7347 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-04 10:46:24.149  6952  7347 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-04 10:46:24.152  1840  1840 D BluetoothHeadset: Proxy object connected
08-04 10:46:24.153  6815  6830 D BluetoothPan: onBluetoothStateChange on: true
08-04 10:46:24.153  6815  6830 D BluetoothPan: onBluetoothStateChange call bindService
08-04 10:46:24.159  6815  6831 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-04 10:46:24.163  6815  6815 D BluetoothPan: BluetoothPAN Proxy object connected
08-04 10:46:24.163  6815  6815 D PanProfile: Bluetooth service connected
08-04 10:46:24.164  1039  1121 D BluetoothA2dp: onBluetoothStateChange: up=true
08-04 10:46:24.168  1840  1856 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 10:46:24.168  1039  1039 D BluetoothA2dp: Proxy object connected
08-04 10:46:24.168  6815  6815 D BluetoothInputDevice: Proxy object connected
08-04 10:46:24.168  6815  6815 D HidProfile: Bluetooth service connected
08-04 10:46:24.170  1840  1840 D BluetoothHeadset: Proxy object connected
08-04 10:46:24.171  6815  7457 D BluetoothMap: onBluetoothStateChange: up=true
08-04 10:46:24.174  6815  6815 D BluetoothMap: Proxy object connected
,08-04 10:46:24.174  6815  6815 D MapProfile: Bluetooth service connected
08-04 10:46:24.174  1039  1121 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 10:46:24.174  6815  6815 D BluetoothMap: getConnectedDevices()
08-04 10:46:24.174  1039  1039 D BluetoothHeadset: Proxy object connected
08-04 10:46:24.175  6952  6971 V BluetoothMapService: getConnectedDevices()
08-04 10:46:24.175  6815  6830 D BluetoothPbap: onBluetoothStateChange: up=true
,08-04 10:46:24.178  1840  3970 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 10:46:24.180  1840  1840 D BluetoothHeadset: Proxy object connected
08-04 10:46:24.181  1039  1121 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-04 10:46:24.181  1039  1121 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-04 10:46:24.182  1039  1039 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-04 10:46:24.182  1930  1930 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:24.185  1930  2116 D LGBluetoothAPIService: Message: 1
08-04 10:46:24.185  1930  2116 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-04 10:46:24.186  1590  1590 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-04 10:46:24.186  1039  1121 D BluetoothManagerService: Message: 40
08-04 10:46:24.186  1039  1121 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,08-04 10:46:24.195  6952  6952 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:24.195  6952  6952 D BluetoothMapService: STATE_ON
08-04 10:46:24.195  1930  2116 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-04 10:46:24.197  6705  6705 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-04 10:46:24.197  6815  6815 D LocalBluetoothProfileManager: Adding local A2DP profile
08-04 10:46:24.199  1039  1121 D BluetoothManagerService: Message: 30
08-04 10:46:24.202  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:46:24.205  6815  6815 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-04 10:46:24.206  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:46:24.207  1039  1121 D BluetoothManagerService: Message: 30
08-04 10:46:24.212  6952  6952 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3de13018
08-04 10:46:24.212  6952  6952 V BluetoothPbapService: Pbap Service onCreate
08-04 10:46:24.212  6952  6952 V BluetoothPbapService: Starting PBAP service
08-04 10:46:24.214  6815  6815 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-04 10:46:24.214  6952  6952 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-04 10:46:24.214  6952  6952 V BluetoothPbapService: Pbap Service onBind
,08-04 10:46:24.215  6952  6952 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:24.215  6952  6952 V BluetoothPbapService: state: 12
08-04 10:46:24.216  6815  6815 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-04 10:46:24.217  6952  6952 D LGBluetoothAPIServer: [BTUI] onCreate()
08-04 10:46:24.218  6952  6952 D LGBluetoothAPIServer: [BTUI] onBind()
08-04 10:46:24.219  6952  6952 V BluetoothMapService: Handler(): got msg=1
08-04 10:46:24.219  1930  1930 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-04 10:46:24.219  1930  2116 D LGBluetoothAPIService: Message: 100
08-04 10:46:24.219  1930  2116 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-04 10:46:24.219  6815  6815 D BluetoothA2dp: Proxy object connected
08-04 10:46:24.220  6815  6815 D A2dpProfile: Bluetooth service connected
08-04 10:46:24.221  6952  6952 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-04 10:46:24.221  6952  6952 V BluetoothPbapService: Handler(): got msg=1
08-04 10:46:24.221  6952  6952 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-04 10:46:24.222  6815  6815 D BluetoothHeadset: Proxy object connected
08-04 10:46:24.222  6952  6952 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-04 10:46:24.222  6952  6952 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:24.222  6952  6952 V BluetoothPbapReceiver: ***********state = 12
08-04 10:46:24.222  6815  6815 D HeadsetProfile: Bluetooth service connected
08-04 10:46:24.223  6952  7463 V BluetoothPbapService: Pbap Service initSocket
08-04 10:46:24.226  1039  1055 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 10:46:24.226  2170  2170 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-04 10:46:24.227  2170  2170 D c       : Getting all permits...
08-04 10:46:24.227  2170  2170 D a       : Opening database...
,08-04 10:46:24.232  6952  7463 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-04 10:46:24.232  6952  7463 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-04 10:46:24.233  2170  2170 D a       : Opening database auth.proximity.permit_store...
08-04 10:46:24.234  2170  2170 D a       : Closing database...
08-04 10:46:24.234  6952  7351 D BluetoothAdapterProperties: Scan Mode:21
08-04 10:46:24.234  6952  7351 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-04 10:46:24.234  6952  7463 V BluetoothPbapService: Succeed to create listening socket 
,08-04 10:46:24.234  6952  7463 V BluetoothPbapService: Accepting socket connection...
08-04 10:46:24.234  6952  7462 D BluetoothMapMasInstance: MAS initSocket()
08-04 10:46:24.235  6952  7462 D BluetoothMapMasInstance:   masId = 00
08-04 10:46:24.235  6952  7462 D BluetoothMapMasInstance:   msgTypes = 0e
08-04 10:46:24.235  6952  7462 D BluetoothMapMasInstance:   masName = SMS/MMS
08-04 10:46:24.235  6952  7462 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-04 10:46:24.237  1039  1973 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 10:46:24.237  6815  6815 D BluetoothPbap: Proxy object connected
08-04 10:46:24.237  6815  6815 D PbapServerProfile: Bluetooth service connected
08-04 10:46:24.239  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:46:24.239  6952  7462 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-04 10:46:24.240  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:46:24.241  6952  7462 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-04 10:46:24.241  6952  7462 V BluetoothMapMasInstance: Succeed to create listening socket 
08-04 10:46:24.241  6952  7462 D BluetoothMapMasInstance: Accepting socket connection...
,08-04 10:46:24.243  7184  7207 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-04 10:46:24.244  6815  6815 D DockEventReceiver: finishStartingService: stopping service
08-04 10:46:24.247  6815  6815 D BluetoothPermissionRequest: onReceive
08-04 10:46:24.249  6815  6815 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-04 10:46:24.251  6815  6815 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-04 10:46:24.253  6952  6952 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,08-04 10:46:24.254  6952  6952 I LGBluetoothOppAdapter: [BTUI] startOppService()
,08-04 10:46:24.259  6952  6952 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-04 10:46:24.273  6952  6952 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-04 10:46:24.273  6952  6952 V BtOppService: onCreate
,08-04 10:46:24.276  6952  6952 V BluetoothOppNotification: send message
,08-04 10:46:24.278  6952  6952 V BtOppService: Starting RfcommListener
08-04 10:46:24.285  6952  7469 V BtOppService: Deleted complete outbound shares, number =  0
08-04 10:46:24.286  6952  7469 V BtOppService: Deleted complete inbound failed shares, number = 0
08-04 10:46:24.286  6952  7469 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
,08-04 10:46:24.287  6952  6952 D BluetoothOppPreference: Dumping Names:  
08-04 10:46:24.287  6952  6952 D BluetoothOppPreference: {}
08-04 10:46:24.287  6952  6952 D BluetoothOppPreference: Dumping Channels:  
08-04 10:46:24.287  6952  6952 D BluetoothOppPreference: {}
08-04 10:46:24.287  6952  7469 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@5f22054 on behalf of 
08-04 10:46:24.288  6952  6952 V BtOppService: onStartCommand
08-04 10:46:24.293  1590  1590 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-04 10:46:24.293  1590  1590 I [SystemUI]LGPowerUI: On Skip Timer : true
08-04 10:46:24.294  6952  6952 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:24.294  6952  6952 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-04 10:46:24.296  6952  7472 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-04 10:46:24.296  6952  7472 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-04 10:46:24.299  6952  6952 V BluetoothOppNotification: new notify threadi!
,08-04 10:46:24.300  6952  6952 V BluetoothOppNotification: send delay message
08-04 10:46:24.301  6952  7473 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-04 10:46:24.302  6952  7472 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@8c5e0f2 on behalf of 
08-04 10:46:24.303  6952  7473 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@33f6b343 on behalf of 
08-04 10:46:24.303  6952  6952 V BtOppService: start RfcommListener
08-04 10:46:24.307  1039  1531 D WifiController: battery changed pluggedType: 2
08-04 10:46:24.308  1590  1590 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
08-04 10:46:24.308  1590  1590 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-04 10:46:24.309  1930  2083 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-04 10:46:24.309  1930  2083 D LEDHandler: Battery Level Remaining: 100%
08-04 10:46:24.309  1930  2083 D LEDHandler: Battery Temp: 291, mChargingStatus=5, mChargingStop=false
08-04 10:46:24.310  7311  7311 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-04 10:46:24.310  6952  6952 V BtOppService: RfcommListener started
,08-04 10:46:24.311  1590  1590 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-04 10:46:24.311  6952  6952 V BtOppService: ContentObserver received notification
08-04 10:46:24.311  6952  6952 V BtOppService: ContentObserver received notification
08-04 10:46:24.312  6952  7474 V BtOppRfcommListener: Starting RFCOMM listener....
08-04 10:46:24.313  1039  1874 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 10:46:24.313  6952  7474 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-04 10:46:24.314  6952  7473 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-04 10:46:24.315  6952  7474 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=75
08-04 10:46:24.315  6952  7474 V BtOppRfcommListener: Started RFCOMM listener....
08-04 10:46:24.315  6952  7474 I BtOppRfcommListener: Accept thread started.
08-04 10:46:24.315  6952  7474 V BtOppRfcommListener: Accepting connection...
08-04 10:46:24.316  6952  7472 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-04 10:46:24.316  6952  7472 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-04 10:46:24.317  6952  7473 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-04 10:46:24.317  6952  7472 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@337aedc0 on behalf of 
08-04 10:46:24.318  6952  7472 V BluetoothOppNotification: update too frequent, put in queue
08-04 10:46:24.319  6952  7473 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@247eaf9 on behalf of 
08-04 10:46:24.319  6952  7473 V BluetoothOppNotification: outbound: succ-0  fail-0
08-04 10:46:24.320  6952  7472 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-04 10:46:24.321  6952  7473 V BluetoothOppNotification: outbound notification was removed.
08-04 10:46:24.321  6952  7473 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-04 10:46:24.322  6952  7473 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@17cd1a3e on behalf of 
08-04 10:46:24.322  6952  7473 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-04 10:46:24.324  6952  7473 V BluetoothOppNotification: inbound notification was removed.
,08-04 10:46:24.324  6952  7473 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-04 10:46:24.327  6952  7473 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2a47409f on behalf of 
08-04 10:46:24.330  6952  6952 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3de13018
08-04 10:46:24.330  6952  6952 V BluetoothFtpService: Ftp Service onCreate
08-04 10:46:24.330  6952  6952 I BluetoothFtpService: Ftp Service onCreate
08-04 10:46:24.330  6952  6952 V BluetoothFtpService: Ftp Service onStartCommand
08-04 10:46:24.330  6952  6952 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:24.330  6952  6952 V BluetoothFtpService: Starting Listening on sockets
08-04 10:46:24.331  6952  6952 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-04 10:46:24.331  6952  6952 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-04 10:46:24.331  6952  6952 V BluetoothSapReceiver: SapReceiver onReceive 
08-04 10:46:24.331  6952  6952 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:24.331  6952  6952 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-04 10:46:24.331  6952  6952 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-04 10:46:24.333  6952  6952 V BluetoothFtpService: Handler(): got msg=1
08-04 10:46:24.333  6952  7385 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-04 10:46:24.333  6952  6952 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-04 10:46:24.333  6952  6952 V BluetoothFtpService: Ftp Service initSocket
,08-04 10:46:24.340  1039  1054 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 10:46:24.341  6952  6952 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-04 10:46:24.342  6952  6952 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-04 10:46:24.343  6952  7475 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-04 10:46:24.357  6952  6952 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3de13018
08-04 10:46:24.357  6952  6952 V BluetoothSapService: Sap Service onCreate
,08-04 10:46:24.359  6952  6952 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-04 10:46:24.359  6952  6952 V BluetoothSapService: state: 12
08-04 10:46:24.360  6952  6952 V BluetoothSapService: Starting SAP server process
08-04 10:46:24.362  6952  6952 V BluetoothSapService: SAP Service startRfcommListenerThread
08-04 10:46:24.357  7476  7476 W sapd    : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 10:46:24.357  7476  7476 W sapd    : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 10:46:24.363  6952  7477 V BluetoothSapService: Sap Service initRfcommSocket
08-04 10:46:24.363  1039  1983 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 10:46:24.364  6952  7477 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-04 10:46:24.365  6952  7477 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-04 10:46:24.365  6952  7477 V BluetoothSapService: Succeed to create listening socket 
08-04 10:46:24.365  6952  7477 V BluetoothSapService: Accepting socket connection...
08-04 10:46:24.382  7476  7476 V BT_SAP  : Event pipe created
08-04 10:46:24.382  7476  7476 V BT_SAP  : create_server_socket qcom.sap.server
08-04 10:46:24.382  7476  7476 V BT_SAP  : created socket fd 6
,08-04 10:46:24.903  1039  1525 D LGWifiP2pService: P2pDisabledState{ when=-4ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:24.904  1039  1525 D LGWifiP2pService: DefaultState{ when=-4ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-04 10:46:24.916  1039  1526 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-04 10:46:24.917  1039  1526 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-04 10:46:25.217  1039  1874 I ActivityManager: Killing 7017:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-04 10:46:25.250  1039  1875 W libprocessgroup: failed to open /acct/uid_10011/pid_7017/cgroup.procs: No such file or directory
,08-04 10:46:25.301  6952  6952 V BluetoothOppNotification: new notify threadi!
,08-04 10:46:25.302  6952  6952 V BluetoothOppNotification: send delay message
,08-04 10:46:25.311  6952  7487 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-04 10:46:25.313  6952  7487 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3d0b4d8 on behalf of 
08-04 10:46:25.314  6952  7487 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-04 10:46:25.317  6952  7487 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-04 10:46:25.323  6952  7487 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2e070031 on behalf of 
,08-04 10:46:25.324  6952  7487 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-04 10:46:25.326  6952  7487 V BluetoothOppNotification: outbound notification was removed.
,08-04 10:46:25.326  6952  7487 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-04 10:46:25.327  6952  7487 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@11f03316 on behalf of 
,08-04 10:46:25.328  6952  7487 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-04 10:46:25.330  6952  7487 V BluetoothOppNotification: inbound notification was removed.
08-04 10:46:25.330  6952  7487 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-04 10:46:25.331  6952  7487 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2bdaa497 on behalf of 
08-04 10:46:25.943  1039  2003 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 10:46:25.943  1039  2003 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3c831035 mBinding = false
,08-04 10:46:25.973  1039  1039 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-04 10:46:25.974  1039  1039 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-04 10:46:25.975  1039  1039 D Ulp_jni : JNI:system_update. Event-4
08-04 10:46:25.975  1039  1121 D BluetoothManagerService: Message: 2
08-04 10:46:25.976  1039  1121 D BluetoothManagerService: Sending off request.
08-04 10:46:25.977  6952  7458 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-04 10:46:25.978  6952  7347 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-04 10:46:25.978  6952  7347 D BluetoothAdapterProperties: Setting state to 13
08-04 10:46:25.978  6952  7347 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-04 10:46:25.979  6952  7347 D BluetoothAdapterProperties: onBluetoothDisable()
08-04 10:46:25.979  6952  7347 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-04 10:46:25.981  6952  7351 D BluetoothAdapterProperties: Scan Mode:20
08-04 10:46:25.982  6952  7347 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-04 10:46:25.985  6952  7347 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-04 10:46:25.990  6952  7463 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-04 10:46:25.991  6952  7405 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-04 10:46:25.992  6952  7474 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-04 10:46:25.992  6952  7405 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-04 10:46:25.994  6952  7475 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-04 10:46:25.994  6952  7462 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-04 10:46:25.994  6952  7462 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-04 10:46:25.994  6952  7462 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-04 10:46:25.994  6952  7462 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-04 10:46:25.994  6952  7462 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-04 10:46:25.994  6952  7462 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-04 10:46:25.994  6952  7462 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-04 10:46:25.994  6952  7462 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-04 10:46:25.999  6952  7405 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-04 10:46:25.999  6952  7405 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-04 10:46:25.999  6952  7405 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-04 10:46:25.999  6952  7405 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-04 10:46:25.999  6952  7405 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 10:46:25.999  6952  7405 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-04 10:46:25.999  6952  7405 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-04 10:46:25.999  6952  7405 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-04 10:46:25.999  6952  7405 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-04 10:46:25.999  6952  7405 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
,08-04 10:46:25.999  6952  7405 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-04 10:46:26.006  6952  7405 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-04 10:46:26.011  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:46:26.011  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:46:26.011  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:26.011  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:26.011  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 10:46:26.011  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 10:46:26.011  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:46:26.011  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:46:26.011  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 10:46:26.014  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:46:26.014  6705  6705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 10:46:26.016  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:46:26.016  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:46:26.016  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:26.016  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:26.016  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 10:46:26.016  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 10:46:26.016  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:46:26.016  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:46:26.016  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 10:46:26.017  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:46:26.017  6705  6705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 10:46:26.020  1039  1121 D BluetoothManagerService: Message: 60
08-04 10:46:26.020  1039  1121 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-04 10:46:26.022  1039  1121 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,08-04 10:46:26.026  1930  1930 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:26.027  1590  1590 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-04 10:46:26.033  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:46:26.035  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:46:26.039  6952  6952 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:26.039  6952  6952 D BluetoothMapService: STATE_TURNING_OFF
08-04 10:46:26.039  6952  6952 V BluetoothMapService: Handler(): got msg=4
08-04 10:46:26.039  6952  6952 D BluetoothMapService: MAP Service closeService in
08-04 10:46:26.039  6952  6952 D BluetoothMapMasInstance: MAP Service shutdown
08-04 10:46:26.040  6952  6952 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-04 10:46:26.040  6952  6952 V BluetoothMapService: MAP Service closeService out
08-04 10:46:26.041  6952  6952 V BtOppService: Receiver DISABLED_ACTION 
08-04 10:46:26.041  6952  6952 I BtOppRfcommListener: stopping Accept Thread
08-04 10:46:26.041  6952  6952 V BtOppRfcommListener: close mBtServerSocket
08-04 10:46:26.041  6952  7474 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-04 10:46:26.042  6952  6952 V BtOppRfcommListener: waiting for thread to terminate
08-04 10:46:26.042  6952  6952 V BtOppRfcommListener: done waiting for thread to terminate
08-04 10:46:26.045  6815  6815 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-04 10:46:26.053  6952  7477 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-04 10:46:26.061  6815  6815 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-04 10:46:26.063  6952  6952 V BtOppService: onDestroy
08-04 10:46:26.065  6952  6952 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
,08-04 10:46:26.071  6952  6952 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-04 10:46:26.072  6952  6952 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:26.072  6952  6952 V BluetoothPbapReceiver: ***********state = 13
08-04 10:46:26.075  6952  6952 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-04 10:46:26.077  6952  6952 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:26.077  6952  6952 V BluetoothPbapService: state: 13
08-04 10:46:26.078  6952  6952 V BluetoothPbapService: Pbap Service closeService in
,08-04 10:46:26.082  2170  2170 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-04 10:46:26.083  6952  6952 V BluetoothPbapService: successfully stopped pbap service
08-04 10:46:26.083  6952  6952 V BluetoothPbapService: Pbap Service closeService out
08-04 10:46:26.084  6952  6952 V BluetoothPbapService: Pbap Service onDestroy
08-04 10:46:26.084  6952  6952 V BluetoothPbapService: Pbap Service closeService in
08-04 10:46:26.084  6952  6952 V BluetoothPbapService: Pbap Service closeService out
08-04 10:46:26.085  6952  6952 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-04 10:46:26.113  6815  6815 D DockEventReceiver: finishStartingService: stopping service
,08-04 10:46:26.117  6815  6815 D BluetoothPbap: Proxy object disconnected
08-04 10:46:26.117  6815  6815 D PbapServerProfile: Bluetooth service disconnected
08-04 10:46:26.122  6815  6815 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-04 10:46:26.129  6815  6815 D BluetoothPermissionRequest: onReceive
08-04 10:46:26.129  6815  6815 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-04 10:46:26.136  6815  6815 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-04 10:46:26.140  6952  6952 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-04 10:46:26.140  6952  6952 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-04 10:46:26.140  6952  6952 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-04 10:46:26.146  6952  6952 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:26.146  6952  6952 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-04 10:46:26.147  6952  6952 V BluetoothFtpService: Ftp Service onStartCommand
08-04 10:46:26.147  6952  6952 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:26.147  6952  6952 V BluetoothFtpService: Ftp Service closeService
08-04 10:46:26.147  6952  6952 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-04 10:46:26.150  6952  6952 V BluetoothFtpService: successfully stopped ftp service
08-04 10:46:26.151  6952  6952 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-04 10:46:26.151  6952  6952 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-04 10:46:26.151  6952  6952 V BluetoothSapReceiver: SapReceiver onReceive 
08-04 10:46:26.151  6952  6952 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:26.151  6952  6952 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-04 10:46:26.151  6952  6952 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-04 10:46:26.152  6952  6952 V BluetoothFtpService: Ftp Service onDestroy
,08-04 10:46:26.152  6952  6952 V BluetoothFtpService: Ftp Service closeService
,08-04 10:46:26.158  6952  6952 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:26.158  6952  6952 V BluetoothSapService: state: 13
,08-04 10:46:26.158  6952  6952 V BluetoothSapService: Stopping SAP server process
08-04 10:46:26.160  6952  6952 V BluetoothSapService: Sap Service closeSapService in
08-04 10:46:26.160  6952  6952 V BluetoothSapService: Close listen Socket : 
08-04 10:46:26.160  6952  6952 V BluetoothSapService: Close rfcomm Socket : 
,08-04 10:46:26.160  6952  6952 V BluetoothSapService: Close sapd  Socket : 
08-04 10:46:26.161  6952  6952 V BluetoothSapService: Sap Service closeSapService out
08-04 10:46:26.161  6952  6952 V BluetoothSapService: Sap Service onDestroy
08-04 10:46:26.161  6952  6952 V BluetoothSapService: Sap Service closeSapService in
,08-04 10:46:26.161  6952  6952 V BluetoothSapService: Close listen Socket : 
08-04 10:46:26.161  6952  6952 V BluetoothSapService: Close rfcomm Socket : 
08-04 10:46:26.161  6952  6952 V BluetoothSapService: Close sapd  Socket : 
08-04 10:46:26.162  6952  6952 V BluetoothSapService: Sap Service closeSapService out
08-04 10:46:26.902  6952  7351 D bt_hci_bdroid: cleanup
,08-04 10:46:26.913  6952  7407 I bt_lpm  : LPM is already off!!!
08-04 10:46:26.914  6952  7434 I bt_userial_mct: exiting userial_read_thread
08-04 10:46:26.914  6952  7434 D bt_userial_mct: Leaving userial_evt_read_thread()
08-04 10:46:26.914  6952  7405 W bt-btif : ag scb idx 1 not allocated
08-04 10:46:26.914  6952  7405 E bt-btif : BTA AG is already disabled, ignoring ...
08-04 10:46:26.914  6952  7405 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-04 10:46:26.914  6952  7405 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 10:46:26.914  6952  7405 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-04 10:46:26.914  6952  7405 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-04 10:46:26.914  6952  7405 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-04 10:46:26.914  6952  7405 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-04 10:46:26.915  6952  7405 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-04 10:46:26.915  6952  7405 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 10:46:26.915  6952  7405 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-04 10:46:26.915  6952  7405 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-04 10:46:26.915  6952  7405 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-04 10:46:26.915  6952  7405 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-04 10:46:26.915  6952  7405 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-04 10:46:26.915  6952  7405 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 10:46:26.915  6952  7405 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-04 10:46:26.915  6952  7405 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-04 10:46:26.915  6952  7405 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-04 10:46:26.915  6952  7405 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-04 10:46:26.915  6952  7405 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-04 10:46:26.915  6952  7351 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-04 10:46:26.916  6952  7407 I bt_vendor: hw_epilog_process
08-04 10:46:26.916  6952  7351 D bt_hci_bdroid: cleanup Finalizing cleanup
08-04 10:46:26.916  6952  7351 D bt_userial_mct: userial_close
08-04 10:46:26.916  6952  7351 E bt_userial_mct: pthread_join() FAILED result:3
08-04 10:46:26.916  6952  7351 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-04 10:46:26.919  6952  7351 D bt_hci_bdroid: set_power 0
08-04 10:46:26.920  6952  7351 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-04 10:46:26.920  6952  7351 I bt_vendor: bluetooth satus is on
08-04 10:46:26.921  6952  7351 I bt_vendor: bt-vendor : resetting BT status
08-04 10:46:26.921  6952  7351 I bt_vendor: Starting hciattach daemon
08-04 10:46:26.921  6952  7351 I bt_vendor: try to set false
08-04 10:46:26.923  6952  7351 I bt_vendor: Starting hciattach daemon
08-04 10:46:26.923  6952  7351 I bt_vendor: try to set false
,08-04 10:46:26.928  6952  7351 I bt_vendor: cleanup
08-04 10:46:26.929  6952  7405 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-04 10:46:26.929  6952  7351 I GKI_LINUX: GKI_exit_task 0 done
08-04 10:46:26.929  6952  7351 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-04 10:46:26.930  6952  7347 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-04 10:46:26.935  6952  6952 D HeadsetService: Received stop request...Stopping profile...
,08-04 10:46:26.939  6952  6952 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-04 10:46:26.939  6952  6952 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-04 10:46:26.939  6952  6952 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3de13018
08-04 10:46:26.940  6952  7385 D HeadsetStateMachine: Exit Disconnected: -1
08-04 10:46:26.944  1840  1840 D BluetoothHeadset: Proxy object disconnected
08-04 10:46:26.944  1840  1840 D BluetoothHeadset: Proxy object disconnected
08-04 10:46:26.945  1840  1840 D BluetoothHeadset: Proxy object disconnected
08-04 10:46:26.945  1039  1039 D BluetoothHeadset: Proxy object disconnected
08-04 10:46:26.945  1039  1039 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-04 10:46:26.947  6952  6952 D A2dpService: Received stop request...Stopping profile...
,08-04 10:46:26.951  6952  7394 D A2dpStateMachine: Exit Disconnected: -1
08-04 10:46:26.953  6952  7347 D BluetoothAdapterState: Stopping profile services that were post enabled
08-04 10:46:26.953  6952  6952 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-04 10:46:26.955  6952  6952 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-04 10:46:26.955  6952  6952 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-04 10:46:26.955  6952  6952 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3de13018
08-04 10:46:26.956  1039  1039 D BluetoothA2dp: Proxy object disconnected
08-04 10:46:26.956  1039  1039 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-04 10:46:26.957  6952  6952 D HidService: Received stop request...Stopping profile...
08-04 10:46:26.957  6952  6952 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3de13018
08-04 10:46:26.961  6952  6952 D HealthService: Received stop request...Stopping profile...
,08-04 10:46:26.964  6952  6952 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3de13018
08-04 10:46:26.966  6952  6952 D HeadsetStateMachine: Unbinding service...
08-04 10:46:26.967  6952  6952 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-04 10:46:26.967  6952  6952 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-04 10:46:26.967  6952  6952 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-04 10:46:26.967  6952  6952 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-04 10:46:26.967  6952  6952 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-04 10:46:26.967  6952  6952 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-04 10:46:26.967  6952  6952 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-04 10:46:26.969  6952  6952 D PanService: Received stop request...Stopping profile...
08-04 10:46:26.970  6952  6952 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3de13018
08-04 10:46:26.971  6952  6952 D BtGatt.DebugUtils: handleDebugAction() action=null
08-04 10:46:26.972  6952  6952 D BtGatt.GattService: Received stop request...Stopping profile...
08-04 10:46:26.972  6952  6952 D BtGatt.GattService: stop()
08-04 10:46:26.972  6952  6952 D BtGatt.AdvertiseManager: advertise clients cleared
08-04 10:46:26.973  6952  6952 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3de13018
,08-04 10:46:26.978  6952  6952 D BluetoothMapService: Received stop request...Stopping profile...
08-04 10:46:26.978  6952  6952 D BluetoothMapService: stop()
08-04 10:46:26.979  6952  6952 D BluetoothMapEmailAppObserver: deinitObservers()
08-04 10:46:26.979  6952  6952 D BluetoothMapEmailAppObserver: removeReceiver()
08-04 10:46:26.980  6952  6952 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3de13018
08-04 10:46:26.981  6952  6952 I BluetoothA2dpServiceJni: cleanupNative
08-04 10:46:26.981  6952  7395 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-04 10:46:26.981  6952  6952 I GKI_LINUX: GKI_exit_task 2 done
08-04 10:46:26.981  6952  6952 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-04 10:46:26.982  6952  6952 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-04 10:46:26.982  6952  6952 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-04 10:46:26.982  6952  6952 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-04 10:46:26.982  6952  6952 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-04 10:46:26.982  6952  6952 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-04 10:46:26.983  6952  6952 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-04 10:46:26.983  6952  6952 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-04 10:46:26.986  6952  6952 V BluetoothMapService: Handler(): got msg=4
08-04 10:46:26.986  6952  6952 D BluetoothMapService: MAP Service closeService in
08-04 10:46:26.986  6952  6952 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-04 10:46:26.986  6952  6952 V BluetoothMapService: MAP Service closeService out
,08-04 10:46:26.990  6952  7347 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-04 10:46:26.990  6952  7347 D BluetoothAdapterProperties: Setting state to 10
08-04 10:46:26.990  6952  7347 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-04 10:46:26.991  6952  6952 D BluetoothMapService: cleanup()
08-04 10:46:26.991  6952  6952 D BluetoothMapService: MAP Service closeService in
08-04 10:46:26.991  6952  6952 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-04 10:46:26.991  6952  6952 V BluetoothMapService: MAP Service closeService out
08-04 10:46:26.992  1039  1121 D BluetoothManagerService: Message: 60
08-04 10:46:26.992  1039  1121 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-04 10:46:26.992  1039  1121 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-04 10:46:26.993  6952  7347 I BluetoothAdapterState: Entering OffState
08-04 10:46:26.993  1840  1855 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 10:46:26.994  6815  6830 D BluetoothPan: onBluetoothStateChange on: false
08-04 10:46:26.994  6815  6830 D BluetoothA2dp: onBluetoothStateChange: up=false
08-04 10:46:26.995  6815  6830 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-04 10:46:26.995  1039  1121 D BluetoothA2dp: onBluetoothStateChange: up=false
08-04 10:46:26.996  1840  3970 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 10:46:26.996  6815  6830 D BluetoothMap: onBluetoothStateChange: up=false
08-04 10:46:26.997  1039  1121 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 10:46:26.997  6815  6830 D BluetoothPbap: onBluetoothStateChange: up=false
08-04 10:46:26.999  1840  3537 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-04 10:46:27.004  6815  6830 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 10:46:27.005  1039  1121 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-04 10:46:27.006  1039  1121 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-04 10:46:27.008  1039  1121 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-04 10:46:27.008  1039  1121 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-04 10:46:27.008  1039  1121 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@3c831035 mBinding = false
08-04 10:46:27.009  1039  1121 D BluetoothManagerService: Sending unbind request.
08-04 10:46:27.014  6952  7351 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-04 10:46:27.016  6952  6952 I GKI_LINUX: GKI_exit_task 1 done
08-04 10:46:27.016  6952  6952 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-04 10:46:27.017  6952  6952 I BluetoothServiceJni: cleanupNative: return from cleanup
08-04 10:46:27.017  6952  6952 I art     : --- WEIRD: removing null entry 248
08-04 10:46:27.017  6952  6952 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-04 10:46:27.017  6952  6952 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-04 10:46:27.018  6952  6952 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-04 10:46:27.019  1039  1121 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-04 10:46:27.021  6952  6952 I art     : System.exit called, status: 0
08-04 10:46:27.021  6952  6952 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-04 10:46:27.040   322   322 V AudioFlinger: 6952 died, releasing its sessions
08-04 10:46:27.040   322   322 V AudioFlinger:  pid 1840 @ 0
08-04 10:46:27.040   322   322 V AudioFlinger:  pid 3467 @ 1
08-04 10:46:27.040   322   322 V AudioFlinger:  pid 3467 @ 2
,08-04 10:46:27.044  1930  1930 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-04 10:46:27.044  1930  2116 D LGBluetoothAPIService: Message: 101
08-04 10:46:27.044  1930  2116 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-04 10:46:27.044  1930  2116 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-04 10:46:27.044  1930  2116 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-04 10:46:27.047  6815  6815 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-04 10:46:27.050  1039  1054 I ActivityManager: Process com.android.bluetooth (pid 6952) has died
08-04 10:46:27.051  1039  1054 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
08-04 10:46:27.051  1039  1054 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 10999ms
,08-04 10:46:27.062  1930  1930 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:27.063  1930  2116 D LGBluetoothAPIService: Message: 2
08-04 10:46:27.063  1930  2116 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-04 10:46:27.063  1590  1590 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-04 10:46:27.070  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:46:27.071  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:46:27.071  1590  1590 D BluetoothAdapter: 764314722: getState() :  mService = null. Returning STATE_OFF
08-04 10:46:27.071  1590  1590 D BluetoothAdapter: 764314722: getState() :  mService = null. Returning STATE_OFF
08-04 10:46:27.073  6815  6815 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-04 10:46:27.073  6815  6815 D LGBluetoothEventManager: [BTUI] clear device connection state
08-04 10:46:27.075  6815  6815 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-04 10:46:27.128  1039  1875 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7535 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-04 10:46:27.132  6815  6815 D DockEventReceiver: finishStartingService: stopping service
,08-04 10:46:27.208  7535  7535 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-04 10:46:27.209  7535  7535 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-04 10:46:27.209  7535  7535 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-04 10:46:27.210  7535  7535 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-04 10:46:27.227  7535  7535 D BluetoothAdapterApp: Loading JNI Library
,08-04 10:46:27.257  7535  7535 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@39c4100 Instance Count = 1
,08-04 10:46:27.261  7535  7535 D BluetoothAdapterApp: onCreate
,08-04 10:46:27.280  7535  7535 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-04 10:46:27.280  7535  7535 D ProfileConfigQcom: Adding HeadsetService
08-04 10:46:27.280  7535  7535 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-04 10:46:27.280  7535  7535 D ProfileConfigQcom: Adding A2dpService
08-04 10:46:27.280  7535  7535 D ProfileConfigQcom: [BTUI] HidService is supported
08-04 10:46:27.280  7535  7535 D ProfileConfigQcom: Adding HidService
08-04 10:46:27.281  7535  7535 D ProfileConfigQcom: [BTUI] HealthService is supported
08-04 10:46:27.281  7535  7535 D ProfileConfigQcom: Adding HealthService
08-04 10:46:27.281  7535  7535 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-04 10:46:27.282  7535  7535 D ProfileConfigQcom: [BTUI] PanService is supported
08-04 10:46:27.282  7535  7535 D ProfileConfigQcom: Adding PanService
08-04 10:46:27.282  7535  7535 D ProfileConfigQcom: [BTUI] GattService is supported
08-04 10:46:27.282  7535  7535 D ProfileConfigQcom: Adding GattService
08-04 10:46:27.282  7535  7535 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-04 10:46:27.283  7535  7535 D ProfileConfigQcom: Adding BluetoothMapService
08-04 10:46:27.283  7535  7535 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-04 10:46:27.284  7535  7535 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-04 10:46:27.284  7535  7535 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:27.285  7535  7535 V BluetoothPbapReceiver: ***********state = 10
08-04 10:46:27.286  7535  7535 V LGMDMManagerInternal: Create singleton instance
,08-04 10:46:27.331  2170  2170 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-04 10:46:27.332  7535  7535 D LGBluetoothAPIServer: [BTUI] onCreate()
08-04 10:46:27.332  7535  7535 D LGBluetoothAPIServer: [BTUI] onBind()
08-04 10:46:27.342  1930  1930 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-04 10:46:27.343  1930  2116 D LGBluetoothAPIService: Message: 100
,08-04 10:46:27.343  1930  2116 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-04 10:46:27.345  6815  6815 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-04 10:46:27.357  6815  6815 D BluetoothPermissionRequest: onReceive
08-04 10:46:27.360  6815  6815 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-04 10:46:27.360  6815  6815 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-04 10:46:27.363  6815  6815 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-04 10:46:27.366  7535  7535 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-04 10:46:27.371  7535  7535 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:27.373  7535  7535 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-04 10:46:27.374  7535  7535 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-04 10:46:27.374  7535  7535 V BluetoothSapReceiver: SapReceiver onReceive 
08-04 10:46:27.375  7535  7535 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:27.375  7535  7535 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,08-04 10:46:27.378  6886  6886 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-04 10:46:29.059  6705  6769 D io.jxcore.node.ConnectivityMonitor: stop
,08-04 10:46:29.060  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 10:46:32.076  6705  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-04 10:46:32.077  6705  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@24faffd5 added. We now have 6 listener(s)
,08-04 10:46:32.077  6705  6769 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 10:46:32.110  6705  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-04 10:46:32.110  6705  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2c9003ea added. We now have 7 listener(s)
08-04 10:46:32.110  6705  6769 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 10:46:32.115  6705  6769 I System.out: IsBluetoothEnabled
08-04 10:46:32.116  1039  1973 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 10:46:32.116  1039  1973 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-04 10:46:32.117  1039  1121 D BluetoothManagerService: Message: 2
08-04 10:46:32.129  6705  6769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:46:32.132  1039  1055 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 10:46:32.132  1039  1055 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-04 10:46:32.149  1039  1039 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-04 10:46:32.149  1039  1039 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-04 10:46:32.150  1039  1039 D Ulp_jni : JNI:system_update. Event-4
08-04 10:46:32.150  1039  1121 D BluetoothManagerService: Message: 1
08-04 10:46:32.150  1039  1121 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-04 10:46:32.187  1039  1121 D BluetoothManagerService: Message: 20
08-04 10:46:32.187  1039  1121 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1d76e304:true
,08-04 10:46:32.190  7535  7535 D BluetoothAdapterState: make
08-04 10:46:32.195  7535  7535 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-04 10:46:32.195  7535  7535 I bluedroid-qcom: init
08-04 10:46:32.196  7535  7567 I BluetoothAdapterState: Entering OffState
08-04 10:46:32.196  7535  7535 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-04 10:46:32.197  7535  7535 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-04 10:46:32.197  7535  7535 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-04 10:46:32.197  7535  7535 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-04 10:46:32.197  7535  7535 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-04 10:46:32.198  7535  7535 I bluedroid-qcom: get_profile_interface socket
08-04 10:46:32.198  7535  7535 I bluedroid-qcom: get_profile_interface map_client
,08-04 10:46:32.202  7535  7571 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-04 10:46:32.197  7570  7570 W bdaddr_loader: type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 10:46:32.197  7570  7570 W bdaddr_loader: type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 10:46:32.209  1039  1039 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-04 10:46:32.210  1039  1121 D BluetoothManagerService: Message: 40
08-04 10:46:32.210  1039  1121 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-04 10:46:32.211  7535  7552 I bluedroid-qcom: config_hci_snoop_log
08-04 10:46:32.217  7570  7570 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-04 10:46:32.217  7570  7570 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-04 10:46:32.217  7570  7570 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-04 10:46:32.222  1039  1121 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
,08-04 10:46:32.222  1039  1121 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,08-04 10:46:32.225  7535  7571 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-04 10:46:32.226  7570  7570 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-04 10:46:32.228  1039  1039 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-04 10:46:32.231  1039  1039 D BluetoothManagerService: Stored Bluetooth name: G3
08-04 10:46:32.236  7570  7570 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-04 10:46:32.236  7570  7570 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-04 10:46:32.239  7535  7571 D BluetoothAdapterProperties: Name is: G3
08-04 10:46:32.250  7535  7567 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,08-04 10:46:32.250  7535  7567 D BluetoothAdapterProperties: Setting state to 11
08-04 10:46:32.250  7535  7567 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-04 10:46:32.251  1039  1121 D BluetoothManagerService: Message: 60
08-04 10:46:32.251  1039  1121 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-04 10:46:32.251  1039  1121 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-04 10:46:32.253  7535  7567 I LGBluetoothServiceJni: classInitNative: succeeds
08-04 10:46:32.257  1930  1930 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:32.258  1590  1590 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-04 10:46:32.260  6815  6815 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-04 10:46:32.264  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:46:32.266  7535  7567 D BluetoothBondStateMachine: make
08-04 10:46:32.270  7535  7588 I BluetoothBondStateMachine: StableState(): Entering Off State
08-04 10:46:32.270  7535  7535 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-04 10:46:32.270  7535  7535 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:32.271  7535  7535 V BluetoothPbapReceiver: ***********state = 11
08-04 10:46:32.274  2170  2170 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-04 10:46:32.286  7535  7567 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18fa71
08-04 10:46:32.286  7535  7567 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-04 10:46:32.286  7535  7567 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18fa71
08-04 10:46:32.286  7535  7567 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-04 10:46:32.287  7535  7567 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
,08-04 10:46:32.291  6815  6815 D BluetoothPermissionRequest: onReceive
08-04 10:46:32.294  6815  6815 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-04 10:46:32.296  7535  7567 E BluetoothAdapterService: File transfer profiles supported!!
08-04 10:46:32.306  7535  7567 E BluetoothAdapterService: File transfer profiles supported!!
,08-04 10:46:32.308  7535  7535 D HeadsetService: Received start request. Starting profile...
08-04 10:46:32.309  7535  7535 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-04 10:46:32.309  7535  7535 D LGBluetoothHfpAdapter: Version 1.6
08-04 10:46:32.312  7535  7535 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-04 10:46:32.313  7535  7535 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-04 10:46:32.313  7535  7567 E BluetoothAdapterService: File transfer profiles supported!!
08-04 10:46:32.313  7535  7535 D HeadsetStateMachine: make
08-04 10:46:32.319  7535  7567 E BluetoothAdapterService: File transfer profiles supported!!
,08-04 10:46:32.324  7535  7567 E BluetoothAdapterService: File transfer profiles supported!!
08-04 10:46:32.329  7535  7567 E BluetoothAdapterService: File transfer profiles supported!!
08-04 10:46:32.333  7535  7567 E BluetoothAdapterService: File transfer profiles supported!!
,08-04 10:46:32.345  7535  7567 V LGMDMManager: Create singleton instance
,08-04 10:46:32.346  7535  7567 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-04 10:46:32.346  7535  7535 D LgDataFeature: LgDataFeature() Constructor: none
08-04 10:46:32.347  7535  7535 D LgDataFeature: LgDataFeature() Constructor Done, null
08-04 10:46:32.350  7535  7535 D HeadsetStateMachine: max_hf_connections = 1
08-04 10:46:32.351  7535  7535 I bluedroid-qcom: get_profile_interface handsfree
08-04 10:46:32.352  7535  7535 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-04 10:46:32.353   322   322 V AudioPolicyService: registerClient() client 0xb14b54e0, uid 1002
08-04 10:46:32.353   322  1373 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-04 10:46:32.353   322  1373 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-04 10:46:32.353   322  1373 V AudioPolicyManagerEx: getOutput() returns output 2
08-04 10:46:32.353  7535  7535 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-04 10:46:32.353   322  1372 V AudioFlinger: registerClient() client 0xb1433598, pid 7535
08-04 10:46:32.354   322  1368 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-04 10:46:32.354   322  1368 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-04 10:46:32.354  7535  7535 V ToneGenerator: Create Track: 0xb4928080
08-04 10:46:32.354  7535  7535 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-04 10:46:32.354  7535  7535 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-04 10:46:32.354  1590  1610 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-04 10:46:32.354  1590  1610 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-04 10:46:32.354  7535  7552 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-04 10:46:32.354  7535  7552 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-04 10:46:32.354   322  1367 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-04 10:46:32.354   322  1367 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-04 10:46:32.354  1590  1614 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-04 10:46:32.355  1590  1614 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-04 10:46:32.355  1039  1983 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-04 10:46:32.355  1039  1983 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-04 10:46:32.355  1039  1983 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-04 10:46:32.355  1039  1983 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-04 10:46:32.355  1840  3970 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-04 10:46:32.355  1840  3970 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-04 10:46:32.355  7535  7550 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-04 10:46:32.355  1840  3970 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-04 10:46:32.355  7535  7550 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-04 10:46:32.355  1840  3970 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-04 10:46:32.355  3467  3482 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-04 10:46:32.355  3467  3482 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-04 10:46:32.355  3467  3482 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-04 10:46:32.355  3467  3482 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-04 10:46:32.355   322  1374 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-04 10:46:32.355   322  1374 V AudioPolicyManager: getOutputForAttr() device 2, samplingRat,e 0, format 0, channelMask 3, flags 0
08-04 10:46:32.355   322  1374 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
,08-04 10:46:32.355   322  1374 V AudioPolicyManagerEx: getOutput() returns output 2
08-04 10:46:32.356   322  1373 I AudioFlinger: isAudioPlaybackHookOn() false
08-04 10:46:32.356   322   322 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-04 10:46:32.356   322   322 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-04 10:46:32.356   322   322 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-04 10:46:32.356   322   322 V AudioPolicyManagerEx: getOutput() returns output 2
08-04 10:46:32.356  7535  7535 V AudioSystem: getLatency() output 2, latency 50
08-04 10:46:32.356  7535  7535 V AudioSystem: getFrameCount() output 2, frameCount 960
08-04 10:46:32.356  7535  7535 V AudioTrack: createTrack_l() output 2 afLatency 50
08-04 10:46:32.356   322  1372 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-04 10:46:32.356   322  1372 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-04 10:46:32.356   322  1372 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-04 10:46:32.356   322  1372 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-04 10:46:32.356   322  1372 V AudioFlinger: createTrack() lSessionId: 23
08-04 10:46:32.357  7535  7535 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-04 10:46:32.357   322  1374 V AudioFlinger: acquiring 23 from 7535, for 7535
08-04 10:46:32.357   322  1374 V AudioFlinger:  added new entry for 23
08-04 10:46:32.357  7535  7535 V ToneGenerator: ToneGenerator INIT OK, time: 149779
08-04 10:46:32.357  7535  7535 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18fa71
08-04 10:46:32.359  7535  7535 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18fa71
08-04 10:46:32.359  7535  7590 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-04 10:46:32.359  7535  7590 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-04 10:46:32.359  7535  7590 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-04 10:46:32.360  7535  7590 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-04 10:46:32.360   322  1373 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7535
08-04 10:46:32.360   322  1373 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-04 10:46:32.360  7535  7535 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:32.361   322  1373 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-04 10:46:32.361   322  1373 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-04 10:46:32.361   322  1373 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-04 10:46:32.361   322  1373 V voice   : voice_set_parameters: exit with code(0)
08-04 10:46:32.361   322  1373 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-04 10:46:32.361   322  1373 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-04 10:46:32.361  7535  7535 D A2dpService: Received start request. Starting profile...
08-04 10:46:32.362   322  1373 V msm8974_platform: platform_set_parameters: exit with code(0)
08-04 10:46:32.362   322  1373 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-04 10:46:32.362   322  1373 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-04 10:46:32.362   322  1373 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-04 10:46:32.362  7535  7590 V ToneGenerator: ToneGenerator destructor
08-04 10:46:32.362  7535  7590 V ToneGenerator: stopTone
08-04 10:46:32.362  7535  7590 V ToneGenerator: Delete Track: 0xb4928080
08-04 10:46:32.362  7535,  7535 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-04 10:46:32.362  7535  7590 V AudioTrack: ~AudioTrack, releasing session id from 7535 on behalf of 7535
08-04 10:46:32.362   322   322 V AudioFlinger: releasing 23 from 7535 for 7535
08-04 10:46:32.362   322   322 V AudioFlinger:  decremented refcount to 0
08-04 10:46:32.362   322   322 V AudioFlinger: purging stale effects
08-04 10:46:32.362   322   322 V AudioPolicyService: AudioCommandThread() adding release output 2
08-04 10:46:32.362   322   322 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-04 10:46:32.362   322   322 V AudioFlinger: PlaybackThread::Track destructor
08-04 10:46:32.362   322  1277 V AudioPolicyService: AudioCommandThread() waking up
08-04 10:46:32.362   322  1277 V AudioPolicyService: AudioCommandThread() processing release output 2
08-04 10:46:32.362   322   322 V AudioFlinger: removeClient_l() pid 7535, calling pid 322
08-04 10:46:32.362   322  1277 V AudioPolicyManager: releaseOutput() 2
08-04 10:46:32.362   322  1277 V AudioPolicyService: AudioCommandThread() going to sleep
08-04 10:46:32.363  7535  7535 V Avrcp   : make
08-04 10:46:32.363  7535  7535 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-04 10:46:32.363  7535  7535 I bluedroid-qcom: get_profile_interface avrcp
08-04 10:46:32.365  1039  2020 W Process : Unable to open /proc/7591/status
08-04 10:46:32.370  7535  7535 V AudioManager: registerRemoteController: size of Media player list: 0
,08-04 10:46:32.373  7535  7535 E AudioManager: No RCC entry present to update
,08-04 10:46:32.373  7535  7535 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-04 10:46:32.376  7535  7535 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
,08-04 10:46:32.378  7535  7535 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-04 10:46:32.378  7535  7535 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-04 10:46:32.381  7535  7535 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-04 10:46:32.528  1039  1055 V SIM_STK : Menu title from STK is T-Mobile
08-04 10:46:32.529  1039  1055 V SIM_STK : Menu title from STK is T-Mobile
,08-04 10:46:32.609  1039  1054 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-04 10:46:32.615  7535  7535 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-04 10:46:32.619  7535  7535 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-04 10:46:32.619  7535  7535 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-04 10:46:32.619  7535  7535 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-04 10:46:32.619  7535  7535 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-04 10:46:32.619  7535  7535 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-04 10:46:32.619  7535  7535 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-04 10:46:32.619  7535  7535 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-04 10:46:32.620  7535  7535 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-04 10:46:32.620  7535  7535 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-04 10:46:32.620  7535  7535 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-04 10:46:32.620  7535  7535 I BluetoothA2dpServiceJni: classInitNative
08-04 10:46:32.620  7535  7535 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-04 10:46:32.620  7535  7535 D A2dpStateMachine: make
,08-04 10:46:32.626  7535  7535 I bluedroid-qcom: get_profile_interface a2dp
08-04 10:46:32.626  7535  7599 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-04 10:46:32.629  7535  7535 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-04 10:46:32.629  7535  7535 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-04 10:46:32.630  7535  7535 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18fa71
08-04 10:46:32.630  7535  7598 D A2dpStateMachine: Enter Disconnected: -2
08-04 10:46:32.630  7535  7535 I BluetoothHidServiceJni: classInitNative: succeeds
08-04 10:46:32.632  7535  7535 D HidService: Received start request. Starting profile...
08-04 10:46:32.632  7535  7535 I bluedroid-qcom: get_profile_interface hidhost
08-04 10:46:32.632  7535  7535 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18fa71
08-04 10:46:32.632  7535  7535 I BluetoothHealthServiceJni: classInitNative: succeeds
08-04 10:46:32.634  7535  7535 D HealthService: Received start request. Starting profile...
,08-04 10:46:32.638  7535  7535 I bluedroid-qcom: get_profile_interface health
08-04 10:46:32.639  7535  7535 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-04 10:46:32.639  7535  7535 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18fa71
08-04 10:46:32.642  7535  7535 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-04 10:46:32.643  7535  7535 D PanService: Received start request. Starting profile...
08-04 10:46:32.644  7535  7535 D BluetoothPanServiceJni: initializeNative(L110): pan
08-04 10:46:32.644  7535  7535 I bluedroid-qcom: get_profile_interface pan
08-04 10:46:32.648  7535  7535 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-04 10:46:32.648  7535  7535 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18fa71
,08-04 10:46:32.650  7535  7535 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-04 10:46:32.653  7535  7535 D BtGatt.DebugUtils: handleDebugAction() action=null
08-04 10:46:32.653  7535  7535 D BtGatt.GattService: Received start request. Starting profile...
08-04 10:46:32.653  7535  7535 D BtGatt.GattService: start()
08-04 10:46:32.653  7535  7535 I bluedroid-qcom: get_profile_interface gatt
08-04 10:46:32.654  7535  7535 D BtGatt.AdvertiseManager: advertise manager created
08-04 10:46:32.664  7535  7535 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18fa71
,08-04 10:46:32.668  7535  7535 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18fa71
08-04 10:46:32.668  7535  7535 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-04 10:46:32.669  7535  7535 V BluetoothMapService: BluetoothMapBinder()
08-04 10:46:32.669  7535  7535 D BluetoothMapService: Received start request. Starting profile...
08-04 10:46:32.669  7535  7535 D BluetoothMapService: start()
08-04 10:46:32.671  7535  7535 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-04 10:46:32.671  7535  7535 D BluetoothMapEmailAppObserver: createReceiver()
08-04 10:46:32.672  7535  7535 D BluetoothMapEmailAppObserver: initObservers()
08-04 10:46:32.672  7535  7535 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-04 10:46:32.677  7535  7535 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18fa71
08-04 10:46:32.677  7535  7535 D HeadsetStateMachine: Proxy object connected
,08-04 10:46:32.677  7535  7535 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-04 10:46:32.677  7535  7535 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-04 10:46:32.681  7535  7535 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-04 10:46:32.681  7535  7535 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-04 10:46:32.681  7535  7535 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-04 10:46:32.681  7535  7590 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-04 10:46:32.681  7535  7535 V BluetoothSapReceiver: SapReceiver onReceive 
08-04 10:46:32.681  7535  7535 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:32.681  7535  7535 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-04 10:46:32.682  7535  7590 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-04 10:46:32.682  7535  7590 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-04 10:46:32.684  7535  7535 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-04 10:46:32.686  7535  7535 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-04 10:46:32.688  7535  7535 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-04 10:46:32.692  7535  7535 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-04 10:46:32.692  7535  7535 V PanService: [BTUI] SIM Extra State :ABSENT
08-04 10:46:32.695  7535  7535 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-04 10:46:32.695  7535  7535 V BluetoothMapService: Handler(): got msg=1
08-04 10:46:32.696  7535  7567 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-04 10:46:32.696  7535  7567 I bluedroid-qcom: enable
08-04 10:46:32.696  7535  7567 I bt_hci_bdroid: init
08-04 10:46:32.697  7535  7567 I bt_vendor: bt-vendor : init
08-04 10:46:32.697  7535  7567 I bt_vendor: bt-vendor : get_bt_soc_type
08-04 10:46:32.697  7535  7567 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-04 10:46:32.697  7535  7567 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-04 10:46:32.697  7535  7567 D bt_userial_mct: userial_init
08-04 10:46:32.697  7535  7609 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-04 10:46:32.697  7535  7609 I bt-btu  : btu_task pending for preload complete event
08-04 10:46:32.697  7535  7567 D bt_hci_bdroid: set_power 1
08-04 10:46:32.697  7535  7567 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-04 10:46:32.697  7535  7567 I bt_vendor: Starting hciattach daemon
08-04 10:46:32.697  7535  7567 I bt_vendor: try to set true
08-04 10:46:32.697  7612  7612 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 10:46:32.697  7612  7612 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-04 10:46:32.710  7613  7613 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-04 10:46:32.748  7619  7619 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-04 10:46:32.754  7620  7620 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-04 10:46:32.768  7622  7622 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-04 10:46:32.775  7623  7623 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-04 10:46:32.782  7624  7624 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-04 10:46:32.791  7625  7625 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-04 10:46:32.806  7627  7627 I libmdmdetect: ESOC framework not supported
08-04 10:46:32.808  7627  7627 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-04 10:46:32.818  7627  7627 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-04 10:46:32.818  7627  7627 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-04 10:46:32.819  7627  7627 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-04 10:46:32.819  7627  7627 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-04 10:46:32.819  7627  7627 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-04 10:46:32.819  7627  7627 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-04 10:46:32.819  7627  7627 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,08-04 10:46:32.867  7627  7628 E QC-QMI  : qmi_client [7627] 15: failed to locate client data
,08-04 10:46:32.869   461   461 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-04 10:46:32.870   461   461 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-04 10:46:32.917  7629  7629 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-04 10:46:32.932  7630  7630 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-04 10:46:32.949  7535  7567 I bt_vendor: bluetooth satus is on
08-04 10:46:32.949  7535  7567 D bt_hci_bdroid: preload
08-04 10:46:32.949  7535  7611 D bt_userial_mct: userial_open(port:0)
08-04 10:46:32.949  7535  7611 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-04 10:46:32.953  7535  7611 I bt_vendor: Done intiailizing UART
,08-04 10:46:32.954  7535  7611 I bt_vendor: Done intiailizing UART
08-04 10:46:32.954  7535  7611 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-04 10:46:32.954  7535  7611 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-04 10:46:32.954  7535  7609 I bt-btu  : btu_task received preload complete event
08-04 10:46:32.955  7535  7609 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-04 10:46:32.956  7535  7632 D bt_userial_mct: Entering userial_read_thread()
08-04 10:46:32.956  7535  7609 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
,08-04 10:46:32.961  7535  7609 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-04 10:46:32.966  7535  7609 I         : BTE_InitTraceLevels -- TRC_HCI
08-04 10:46:32.966  7535  7609 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-04 10:46:32.966  7535  7609 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-04 10:46:32.966  7535  7609 I         : BTE_InitTraceLevels -- TRC_AVDT
08-04 10:46:32.966  7535  7609 I         : BTE_InitTraceLevels -- TRC_AVRC
08-04 10:46:32.966  7535  7609 I         : BTE_InitTraceLevels -- TRC_A2D
08-04 10:46:32.966  7535  7609 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-04 10:46:32.966  7535  7609 I         : BTE_InitTraceLevels -- TRC_BTM
08-04 10:46:32.967  7535  7609 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-04 10:46:32.967  7535  7609 I         : BTE_InitTraceLevels -- TRC_GAP
08-04 10:46:32.967  7535  7609 I         : BTE_InitTraceLevels -- TRC_PAN
08-04 10:46:32.967  7535  7609 I         : BTE_InitTraceLevels -- TRC_SDP
,08-04 10:46:32.967  7535  7609 I         : BTE_InitTraceLevels -- TRC_GATT
08-04 10:46:32.967  7535  7609 I         : BTE_InitTraceLevels -- TRC_SMP
08-04 10:46:32.967  7535  7609 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-04 10:46:32.967  7535  7609 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-04 10:46:33.083  7535  7609 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-04 10:46:33.083  7535  7609 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa019d061 
,08-04 10:46:33.083  7535  7609 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa019d061 
,08-04 10:46:33.133  7535  7571 E bt-btif : Calling BTA_HhEnable
,08-04 10:46:33.134  7535  7571 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-04 10:46:33.134  7535  7571 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-04 10:46:33.141  7535  7609 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
,08-04 10:46:33.141  7535  7609 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-04 10:46:33.141  7535  7609 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-04 10:46:33.142  7535  7609 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-04 10:46:33.142  7535  7609 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-04 10:46:33.145  7535  7571 D BluetoothAdapterProperties: Name is: G3
08-04 10:46:33.147  7535  7571 D BluetoothAdapterProperties: Scan Mode:20
08-04 10:46:33.148  7535  7571 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-04 10:46:33.148  7535  7571 D bt_hci_bdroid: postload
08-04 10:46:33.149  7535  7611 D bt_hci_bdroid: Used up Tx Cmd credits
,08-04 10:46:33.159  7535  7611 D bt_hci_bdroid: Used up Tx Cmd credits
08-04 10:46:33.159  7535  7609 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-04 10:46:33.160  7535  7571 D bte_conf: Device ID record 1 : primary
08-04 10:46:33.160  7535  7571 D bte_conf:   vendorId            = 00c4
08-04 10:46:33.160  7535  7571 D bte_conf:   vendorIdSource      = 0001
08-04 10:46:33.160  7535  7571 D bte_conf:   product             = 13a1
08-04 10:46:33.160  7535  7571 D bte_conf:   version             = 1000
08-04 10:46:33.160  7535  7571 D bte_conf:   clientExecutableURL = 
08-04 10:46:33.160  7535  7571 D bte_conf:   serviceDescription  = 
08-04 10:46:33.160  7535  7571 D bte_conf:   documentationURL    = 
08-04 10:46:33.160  7535  7571 D bte_conf: bte_load_did_conf no section named DID2.
08-04 10:46:33.163  7535  7611 D bt_hci_bdroid: Used up Tx Cmd credits
08-04 10:46:33.164  7535  7567 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-04 10:46:33.164  7535  7567 D BluetoothAdapterProperties: ScanMode =  20
08-04 10:46:33.164  7535  7567 D BluetoothAdapterProperties: State =  11
08-04 10:46:33.165  7535  7567 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-04 10:46:33.165  7535  7567 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-04 10:46:33.165  7535  7567 D BluetoothAdapterProperties: Setting state to 12
08-04 10:46:33.165  7535  7567 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-04 10:46:33.167  7535  7571 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-04 10:46:33.170  7535  7571 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-04 10:46:33.167  7637  7637 W sh      : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 10:46:33.167  7637  7637 W sh      : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 10:46:33.175  1039  1121 D BluetoothManagerService: Message: 60
08-04 10:46:33.176  1039  1121 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-04 10:46:33.176  1039  1121 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-04 10:46:33.177  7535  7609 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-04 10:46:33.177  7535  7609 W bt-smp  : Plain text(LSB ~ MSB) = ec 3e 5d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-04 10:46:33.177  7535  7609 W bt-smp  : Encrypted text(LSB ~ MSB) = e0 1d 1a 64 66 1d db 56 bd e8 26 4b b5 e3 54 1a 
08-04 10:46:33.177  7535  7611 D bt_hci_bdroid: Used up Tx Cmd credits
08-04 10:46:33.177  7535  7609 W bt-btm  : Stopping oneshot timer
08-04 10:46:33.180  7535  7632 E bt_mct  : hci lib postload completed
,08-04 10:46:33.144  1039  1039 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-04 10:46:33.195  1039  1039 D BluetoothManagerService: Stored Bluetooth name: G3
,08-04 10:46:33.206  1840  3975 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 10:46:33.206  7535  7567 I BluetoothAdapterState: Entering On State
08-04 10:46:33.210  7535  7609 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-04 10:46:33.210  7535  7609 W bt-smp  : Plain text(LSB ~ MSB) = 9f be 57 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-04 10:46:33.210  7535  7609 W bt-smp  : Encrypted text(LSB ~ MSB) = e4 d5 2e 73 9a db d7 11 43 06 c7 9a d1 b3 48 1d 
,08-04 10:46:33.213  7535  7609 W bt-btm  : Stopping oneshot timer
08-04 10:46:33.224  7535  7571 D BluetoothAdapterProperties: Discoverable Timeout:120
08-04 10:46:33.224  7535  7571 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-04 10:46:33.227  7535  7609 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-04 10:46:33.227  7535  7609 W bt-smp  : Plain text(LSB ~ MSB) = 29 72 7e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-04 10:46:33.227  7535  7609 W bt-smp  : Encrypted text(LSB ~ MSB) = 59 fa 0d c4 ee 17 a0 1d 9e 6d c1 c7 da 67 ae 3c 
08-04 10:46:33.227  7535  7609 W bt-btm  : Stopping oneshot timer
08-04 10:46:33.234  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:46:33.234  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:33.234  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:33.234  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 10:46:33.234  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 10:46:33.234  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:46:33.234  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:46:33.234  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 10:46:33.244  7535  7609 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-04 10:46:33.244  7535  7609 W bt-smp  : Plain text(LSB ~ MSB) = 38 22 42 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-04 10:46:33.244  7535  7609 W bt-smp  : Encrypted text(LSB ~ MSB) = ea 04 30 c5 fb 60 d2 89 f0 f1 2d ca b1 79 e2 5f 
,08-04 10:46:33.247  7535  7609 W bt-btm  : Stopping oneshot timer
08-04 10:46:33.257  7535  7567 D LGBluetoothServiceAdapter: [BTUI] OnState
08-04 10:46:33.257  7535  7567 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-04 10:46:33.258  7535  7567 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-04 10:46:33.263  7535  7567 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-04 10:46:33.263  7535  7567 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-04 10:46:33.269  6705  6705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 10:46:33.270  7535  7609 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-04 10:46:33.271  7535  7609 W bt-smp  : Plain text(LSB ~ MSB) = d9 85 61 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-04 10:46:33.271  7535  7609 W bt-smp  : Encrypted text(LSB ~ MSB) = 8e da a6 c8 0b 8e 42 5f 08 d9 d0 57 00 b2 ac 12 
,08-04 10:46:33.273  7535  7609 W bt-btm  : Stopping oneshot timer
,08-04 10:46:33.274  6705  6769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:46:33.274  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:33.274  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:33.274  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 10:46:33.274  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 10:46:33.274  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:46:33.274  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:46:33.274  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 10:46:33.283  6815  6830 D BluetoothPan: onBluetoothStateChange on: true
08-04 10:46:33.283  6815  6830 D BluetoothPan: onBluetoothStateChange call bindService
08-04 10:46:33.295  6705  6769 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-04 10:46:33.300  6815  7457 D BluetoothA2dp: onBluetoothStateChange: up=true
08-04 10:46:33.301  6705  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 10:46:33.301  6705  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b7f26db added. We now have 8 listener(s)
08-04 10:46:33.301  6705  6769 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 10:46:33.304  1840  1840 D BluetoothHeadset: Proxy object connected
08-04 10:46:33.315  6815  6831 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-04 10:46:33.318  7659  7659 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-04 10:46:33.319  1039  2020 D WifiServiceImplEx: setWifiEnabled: false pid=6705, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-04 10:46:33.319  1039  2020 D WifiService: setWifiEnabled: false pid=6705, uid=10118
08-04 10:46:33.319  1039  2020 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-04 10:46:33.320  6815  6815 D BluetoothPan: BluetoothPAN Proxy object connected
08-04 10:46:33.320  6815  6815 D PanProfile: Bluetooth service connected
08-04 10:46:33.320  1039  1121 D BluetoothA2dp: onBluetoothStateChange: up=true
08-04 10:46:33.321  1039  1039 D BluetoothA2dp: Proxy object connected
08-04 10:46:33.322  6815  6815 D BluetoothA2dp: Proxy object connected
08-04 10:46:33.322  6815  6815 D A2dpProfile: Bluetooth service connected
08-04 10:46:33.323  1840  2442 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 10:46:33.324  6815  6815 D BluetoothInputDevice: Proxy object connected
08-04 10:46:33.324  6815  6815 D HidProfile: Bluetooth service connected
08-04 10:46:33.324  6705  6769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:46:33.325  1840  1840 D BluetoothHeadset: Proxy object connected
08-04 10:46:33.325  1039  1054 D WifiServiceImplEx: setWifiEnabled: true pid=6705, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-04 10:46:33.326  1039  1054 D WifiService: setWifiEnabled: true pid=6705, uid=10118
08-04 10:46:33.326  1039  1054 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-04 10:46:33.328  6815  6831 D BluetoothMap: onBluetoothStateChange: up=true
08-04 10:46:33.330  1039  1121 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 10:46:33.331  1039  1039 D BluetoothHeadset: Proxy object connected
,08-04 10:46:33.332  6815  6815 D BluetoothMap: Proxy object connected
08-04 10:46:33.332  6815  6815 D MapProfile: Bluetooth service connected
08-04 10:46:33.332  6815  6815 D BluetoothMap: getConnectedDevices()
08-04 10:46:33.333  6815  7457 D BluetoothPbap: onBluetoothStateChange: up=true
08-04 10:46:33.334  7535  7655 V BluetoothMapService: getConnectedDevices()
08-04 10:46:33.335  1840  3970 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 10:46:33.337  1039  1039 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-04 10:46:33.337  1840  1840 D BluetoothHeadset: Proxy object connected
08-04 10:46:33.337  1039  1039 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-04 10:46:33.337  1039  1039 D Ulp_jni : JNI:system_update. Event-4
08-04 10:46:33.337  6815  6831 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 10:46:33.338  1039  1526 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-04 10:46:33.338  1039  1526 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-04 10:46:33.338  1039  1526 E WifiUtil: wfc_util_ffile_check_copy(): pid[1039] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-04 10:46:33.338  1039  1526 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-04 10:46:33.338  1039  1526 E WifiUtil: wfc_util_ffile_check_copy(): pid[1039] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-04 10:46:33.338  1039  1526 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-04 10:46:33.339  1039  1526 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-04 10:46:33.339  1039  1526 E WifiHW  : unknown target_country: EU , set to default
08-04 10:46:33.339  1039  1526 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-04 10:46:33.339  1039  1526 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-04 10:46:33.339  1039  1526 I WifiUtil: gEnableBmps=1
08-04 10:46:33.340  6815  6815 D BluetoothHeadset: Proxy object connected
08-04 10:46:33.340  6815  6815 D HeadsetProfile: Bluetooth service connected
08-04 10:46:33.341  1039  1121 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-04 10:46:33.341  1039  1121 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-04 10:46:33.343  1039  1039 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,08-04 10:46:33.348  1930  1930 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:33.348  1590  1590 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-04 10:46:33.348  1930  2116 D LGBluetoothAPIService: Message: 1
08-04 10:46:33.349  1930  2116 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-04 10:46:33.349  1930  2116 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-04 10:46:33.349  1930  2116 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-04 10:46:33.352  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:46:33.353  7535  7535 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:33.354  7535  7535 D BluetoothMapService: STATE_ON
08-04 10:46:33.354  6815  6815 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-04 10:46:33.355  1039  1121 D BluetoothManagerService: Message: 40
08-04 10:46:33.355  1039  1121 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-04 10:46:33.355  6815  6815 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-04 10:46:33.361  6815  6815 D DockEventReceiver: finishStartingService: stopping service
,08-04 10:46:33.369  7535  7535 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18fa71
08-04 10:46:33.369  7535  7535 V BluetoothPbapService: Pbap Service onCreate
08-04 10:46:33.369  7535  7535 V BluetoothPbapService: Starting PBAP service
,08-04 10:46:33.370  7535  7535 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-04 10:46:33.371  7535  7535 V BluetoothPbapService: Pbap Service onBind
08-04 10:46:33.371  7535  7535 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:33.372  7535  7535 V BluetoothPbapService: state: 12
08-04 10:46:33.372  6815  6815 D BluetoothPbap: Proxy object connected
08-04 10:46:33.372  6815  6815 D PbapServerProfile: Bluetooth service connected
08-04 10:46:33.372  7535  7535 V BluetoothMapService: Handler(): got msg=1
08-04 10:46:33.372  7535  7535 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-04 10:46:33.373  7535  7535 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-04 10:46:33.373  7535  7535 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:33.373  7535  7535 V BluetoothPbapReceiver: ***********state = 12
08-04 10:46:33.373  7535  7666 D BluetoothMapMasInstance: MAS initSocket()
08-04 10:46:33.374  7535  7666 D BluetoothMapMasInstance:   masId = 00
08-04 10:46:33.374  7535  7666 D BluetoothMapMasInstance:   msgTypes = 0e
08-04 10:46:33.374  7535  7666 D BluetoothMapMasInstance:   masName = SMS/MMS
08-04 10:46:33.374  7535  7666 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-04 10:46:33.374  7535  7535 V BluetoothPbapService: Handler(): got msg=1
08-04 10:46:33.375  7535  7535 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-04 10:46:33.375  1039  1947 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 10:46:33.376  7535  7667 V BluetoothPbapService: Pbap Service initSocket
08-04 10:46:33.376  2170  2170 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-04 10:46:33.376  1039  1055 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 10:46:33.376  2170  2170 D c       : Getting all permits...
08-04 10:46:33.376  2170  2170 D a       : Opening database...
08-04 10:46:33.377  7535  7666 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-04 10:46:33.378  7535  7666 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-04 10:46:33.379  7535  7666 V BluetoothMapMasInstance: Succeed to create listening socket 
08-04 10:46:33.379  7535  7666 D BluetoothMapMasInstance: Accepting socket connection...
08-04 10:46:33.379  7535  7571 D BluetoothAdapterProperties: Scan Mode:21
08-04 10:46:33.379  7535  7571 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-04 10:46:33.380  7535  7667 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-04 10:46:33.380  2170  2170 D a       : Opening database auth.proximity.permit_store...
08-04 10:46:33.381  2170  2170 D a       : Closing database...
08-04 10:46:33.383  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:46:33.384  7535  7667 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-04 10:46:33.384  7535  7667 V BluetoothPbapService: Succeed to create listening socket 
08-04 10:46:33.385  7535  7667 V BluetoothPbapService: Accepting socket connection...
08-04 10:46:33.391  6815  6815 D BluetoothPermissionRequest: onReceive
08-04 10:46:33.392  6815  6815 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-04 10:46:33.393  6815  6815 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-04 10:46:33.396  7535  7535 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,08-04 10:46:33.397  7535  7535 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-04 10:46:33.403  7535  7535 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-04 10:46:33.420  7535  7535 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-04 10:46:33.421  7535  7535 V BtOppService: onCreate
,08-04 10:46:33.424  7535  7535 V BluetoothOppNotification: send message
08-04 10:46:33.435  7535  7671 V BtOppService: Deleted complete outbound shares, number =  0
,08-04 10:46:33.437  7535  7671 V BtOppService: Deleted complete inbound failed shares, number = 0
,08-04 10:46:33.437  7535  7671 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-04 10:46:33.539  1039  1973 I art     : Explicit concurrent mark sweep GC freed 45058(2MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.719ms total 114.060ms
,08-04 10:46:33.540  7535  7535 V BtOppService: Starting RfcommListener
08-04 10:46:33.542  7535  7671 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@5f22054 on behalf of 
08-04 10:46:33.547  7535  7535 D BluetoothOppPreference: Dumping Names:  
08-04 10:46:33.547  7535  7535 D BluetoothOppPreference: {}
08-04 10:46:33.547  7535  7535 D BluetoothOppPreference: Dumping Channels:  
08-04 10:46:33.547  7535  7535 D BluetoothOppPreference: {}
08-04 10:46:33.549  7535  7535 V BtOppService: onStartCommand
08-04 10:46:33.551  7535  7674 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-04 10:46:33.551  7535  7674 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,08-04 10:46:33.553  7535  7535 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:33.553  7535  7535 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-04 10:46:33.556  7535  7535 V BluetoothOppNotification: new notify threadi!
08-04 10:46:33.556  7535  7535 V BluetoothOppNotification: send delay message
08-04 10:46:33.556  7535  7535 V BtOppService: ContentObserver received notification
08-04 10:46:33.556  7535  7535 V BtOppService: ContentObserver received notification
08-04 10:46:33.557  7535  7535 V BtOppService: start RfcommListener
08-04 10:46:33.557  7535  7674 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@8c5e0f2 on behalf of 
08-04 10:46:33.558  7535  7674 V BluetoothOppNotification: update too frequent, put in queue
08-04 10:46:33.559  7535  7674 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-04 10:46:33.559  7535  7674 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-04 10:46:33.559  7535  7535 V BtOppService: RfcommListener started
08-04 10:46:33.561  7535  7676 V BtOppRfcommListener: Starting RFCOMM listener....
08-04 10:46:33.562  1039  1563 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 10:46:33.563  7535  7674 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@33f6b343 on behalf of 
08-04 10:46:33.564  7535  7676 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-04 10:46:33.565  7535  7676 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-04 10:46:33.565  7535  7675 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-04 10:46:33.566  7535  7676 V BtOppRfcommListener: Started RFCOMM listener....
08-04 10:46:33.566  7535  7676 I BtOppRfcommListener: Accept thread started.
08-04 10:46:33.566  7535  7676 V BtOppRfcommListener: Accepting connection...
08-04 10:46:33.566  7535  7674 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-04 10:46:33.567  7535  7675 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@337aedc0 on behalf of 
08-04 10:46:33.568  7535  7535 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18fa71
08-04 10:46:33.568  7535  7535 V BluetoothFtpService: Ftp Service onCreate
08-04 10:46:33.568  7535  7535 I BluetoothFtpService: Ftp Service onCreate
08-04 10:46:33.568  7535  7675 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-04 10:46:33.568  7535  7535 V BluetoothFtpService: Ftp Service onStartCommand
08-04 10:46:33.568  7535  7535 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:33.568  7535  7535 V BluetoothFtpService: Starting Listening on sockets
08-04 10:46:33.568  7535  7535 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-04 10:46:33.568  7535  7535 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-04 10:46:33.568  7535  7535 V BluetoothSapReceiver: SapReceiver onReceive 
08-04 10:46:33.568  7535  7535 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:33.568  7535  7535 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-04 10:46:33.568  7535  7535 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-04 10:46:33.571  7535  7535 V BluetoothFtpService: Handler(): got msg=1
08-04 10:46:33.570  7535  7675 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-04 10:46:33.571  7535  7535 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-04 10:46:33.571  7535  7535 V BluetoothFtpService: Ftp Service initSocket
08-04 10:46:33.572  7535  7675 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@17cd1a3e on behalf of 
08-04 10:46:33.573  1039  1054 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 10:46:33.573  7535  7675 V BluetoothOppNotification: outbound: succ-0  fail-0
08-04 10:46:33.573  7535  7535 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-04 10:46:33.574  7535  7535 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
08-04 10:46:33.574  7535  7675 V BluetoothOppNotification: outbound notification was removed.
08-04 10:46:33.574  7535  7675 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-04 10:46:33.575  7535  7535 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-04 10:46:33.575  7535  7675 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2a47409f on behalf of 
08-04 10:46:33.576  7535  7675 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-04 10:46:33.576  7535  7677 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-04 10:46:33.577  7535  7675 V BluetoothOppNotification: inbound notification was removed.
08-04 10:46:33.577  7535  7675 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-04 10:46:33.578  7535  7675 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@100125ec on behalf of 
08-04 10:46:33.598  7535  7535 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18fa71
08-04 10:46:33.598  7535  7535 V BluetoothSapService: Sap Service onCreate
,08-04 10:46:33.600  7535  7535 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-04 10:46:33.600  7535  7535 V BluetoothSapService: state: 12
08-04 10:46:33.600  7535  7535 V BluetoothSapService: Starting SAP server process
08-04 10:46:33.597  7678  7678 W sapd    : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-04 10:46:33.597  7678  7678 W sapd    : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 10:46:33.602  7535  7535 V BluetoothSapService: SAP Service startRfcommListenerThread
08-04 10:46:33.604  7535  7679 V BluetoothSapService: Sap Service initRfcommSocket
08-04 10:46:33.604  1039  2020 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 10:46:33.605  7535  7679 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-04 10:46:33.606  7535  7679 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-04 10:46:33.606  7535  7679 V BluetoothSapService: Succeed to create listening socket 
08-04 10:46:33.606  7535  7679 V BluetoothSapService: Accepting socket connection...
08-04 10:46:33.608  7678  7678 V BT_SAP  : Event pipe created
08-04 10:46:33.608  7678  7678 V BT_SAP  : create_server_socket qcom.sap.server
,08-04 10:46:33.608  7678  7678 V BT_SAP  : created socket fd 6
08-04 10:46:34.080   315   897 D SoftapController: Softap fwReload - Ok
,08-04 10:46:34.090  1039  1121 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-04 10:46:34.090  1039  1121 D Tethering: InitialState.processMessage what=4
08-04 10:46:34.090  1039  1121 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-04 10:46:34.105  1039  1526 E NetdConnector: NDC Command {67 softap fwreload wlan0 STA} took too long (732ms)
,08-04 10:46:34.129   315   897 D CommandListener: Setting iface cfg
08-04 10:46:34.130   315   897 D CommandListener: Trying to bring down wlan0
08-04 10:46:34.130   315   897 D CommandListener: Clearing all IP addresses on wlan0
08-04 10:46:34.139  1039  1526 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-04 10:46:34.137  7696  7696 W wpa_supplicant: type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 10:46:34.146  1039  1526 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-04 10:46:34.146  1039  1526 E WifiStateMachine: useWiFiOffloading() : false
08-04 10:46:34.146  1039  1526 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-04 10:46:34.150  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 10:46:34.147  7696  7696 W wpa_supplicant: type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 10:46:34.159  1930  1930 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,08-04 10:46:34.181  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:46:34.185  1039  1039 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-04 10:46:34.185  1039  1526 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-04 10:46:34.185  1039  1526 D WifiMonitor: connecting to supplicant
08-04 10:46:34.194  6815  6815 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-04 10:46:34.194  6815  6815 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-04 10:46:34.195  6815  6815 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-04 10:46:34.195  6815  6815 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-04 10:46:34.201  6815  6815 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-04 10:46:34.203  6815  6815 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-04 10:46:34.203  6815  6815 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-04 10:46:34.203  6815  6815 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-04 10:46:34.203  6815  6815 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-04 10:46:34.203  6815  6815 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-04 10:46:34.204  6815  6815 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-04 10:46:34.205  7696  7696 I wpa_supplicant: Successfully initialized wpa_supplicant
08-04 10:46:34.207  6815  6815 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-04 10:46:34.208  6815  6815 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-04 10:46:34.208  6815  6815 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-04 10:46:34.208  6815  6815 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-04 10:46:34.209  6815  6815 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-04 10:46:34.212  6815  6815 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-04 10:46:34.212  6815  6815 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-04 10:46:34.212  6815  6815 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-04 10:46:34.213  6815  6815 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-04 10:46:34.213  6815  6815 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-04 10:46:34.213  6815  6815 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-04 10:46:34.222  6834  6834 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-04 10:46:34.229  6815  6815 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-04 10:46:34.239  7696  7696 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-04 10:46:34.239  7696  7696 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-04 10:46:34.240  6815  6815 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 10:46:34.242  6919  7713 W FormManager: Network not available. Please check & try again.
08-04 10:46:34.246  6919  7714 V FormManager: Network unavailable.
,08-04 10:46:34.254  6919  7714 V FormManager: Network unavailable.
,08-04 10:46:34.365  7696  7696 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-04 10:46:34.384  7696  7696 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-04 10:46:34.392  7696  7696 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,08-04 10:46:34.398  1039  7717 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-04 10:46:34.398  1039  7717 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-04 10:46:34.398  1039  7717 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-04 10:46:34.398  1039  7717 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-04 10:46:34.399  1039  1526 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-04 10:46:34.400  1039  1526 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-04 10:46:34.402  1039  1526 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-04 10:46:34.404  1039  1526 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-04 10:46:34.405  1039  1526 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-04 10:46:34.406  1039  1526 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-04 10:46:34.407  1039  1526 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-04 10:46:34.407  1039  1526 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-04 10:46:34.409  1039  1526 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-04 10:46:34.410  1039  1526 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-04 10:46:34.410  1039  1526 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-04 10:46:34.411  1039  1526 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-04 10:46:34.411  1039  1526 E WifiStateMachine: useWiFiOffloading() : false
08-04 10:46:34.411  1039  1526 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-04 10:46:34.411  1039  1039 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 10:46:34.412  1039  1039 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 10:46:34.412  1039  1039 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 10:46:34.412  1039  1039 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 10:46:34.413  1039  1039 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-04 10:46:34.414  1039  1526 D WifiNative-wlan0: doBoolean: SET update_config 1
08-04 10:46:34.416  1930  1930 D WfdService: Waiting for WifiP2p enabling
08-04 10:46:34.416  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 10:46:34.417  1039  1526 D WifiNative-wlan0: SET update_config 1: returned true
08-04 10:46:34.417  1039  1526 D WifiConfigStore: Loading config and enabling all networks 
08-04 10:46:34.417  1039  1526 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-04 10:46:34.419  1039  1526 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
,08-04 10:46:34.426  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:46:34.426  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:34.426  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:34.426  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:46:34.426  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 10:46:34.426  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:46:34.426  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:46:34.426  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 10:46:34.429  1039  1039 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
,08-04 10:46:34.430  1039  1530 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-04 10:46:34.434  6705  6705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 10:46:34.435  1039  1526 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-04 10:46:34.446  1039  1526 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-04 10:46:34.447  1039  1526 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-04 10:46:34.447  6834  6834 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-04 10:46:34.447  1039  1526 D WifiStateMachine: enableVerboseLogging : level 2
08-04 10:46:34.447  1039  1526 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-04 10:46:34.448  1039  1526 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-04 10:46:34.448  1039  1526 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-04 10:46:34.449  1039  1526 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-04 10:46:34.449  1039  1526 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-04 10:46:34.449  1039  1526 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-04 10:46:34.449  1039  1526 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-04 10:46:34.450  1039  1526 D WifiNative-wlan0: SET model_number LG-D855: returned true
,08-04 10:46:34.450  1039  1526 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-04 10:46:34.450  1039  1526 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-04 10:46:34.450  1039  1526 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-04 10:46:34.451  1039  1526 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-04 10:46:34.451  1039  1526 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
,08-04 10:46:34.451  1039  1526 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-04 10:46:34.452  6815  6815 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-04 10:46:34.453  1039  1526 D WifiStateMachine: Setting OUI to DA-A1-19
08-04 10:46:34.453  1039  1526 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-04 10:46:34.454  1930  1930 D WfdsService: Supplicant Connection state is changed : true
08-04 10:46:34.454  1930  2236 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-04 10:46:34.454  1930  2236 D WfdsService: Set the WFDS Monitor: true
08-04 10:46:34.454  1930  2236 D WfdsMonitor: WfdsMonitorThread create
08-04 10:46:34.454  1930  2236 D WfdsMonitor: WFDS Monitor is created and started
08-04 10:46:34.454  1930  2236 D WfdsService: WiFi: Supplicant connection re-established
08-04 10:46:34.455  1039  1526 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-04 10:46:34.455  1039  1526 D WifiNative-HAL: Setting external_sim to 1
08-04 10:46:34.455  1039  1526 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-04 10:46:34.456  1039  1526 D WifiNative-wlan0: SET external_sim 1: returned true
08-04 10:46:34.456  1039  1526 I WifiNative-HAL: startHal
08-04 10:46:34.456  1039  1526 D wifi    : setting scan oui 0xaf6723c0
08-04 10:46:34.456  1039  1526 D WifiStateMachine: Setting OUI to DA-A1-19
08-04 10:46:34.456  1039  1526 I WifiNative-HAL: startHal
08-04 10:46:34.456  1039  1526 D wifi    : setting scan oui 0xaf6723c0
08-04 10:46:34.457  1039  1526 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-04 10:46:34.457  1039  1526 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-04 10:46:34.458  1039  1526 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-04 10:46:34.458  7696  7696 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-04 10:46:34.458  1930  7720 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-04 10:46:34.459  1039  1526 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-04 10:46:34.459  1039  1526 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-04 10:46:34.459  7696  7696 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-04 10:46:34.459  1930  7720 E CtrlSupplicant: Succeed to open control connection
08-04 10:46:34.460  1039  1526 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-04 10:46:34.460  1039  1526 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-04 10:46:34.460  7696  7696 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-04 10:46:34.460  1039  1526 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-04 10:46:34.460  1930  7720 E CtrlSupplicant: Succeed to open monitor connection
08-04 10:46:34.460  1039  1526 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-04 10:46:34.461  7696  7696 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-04 10:46:34.461  1039  1526 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-04 10:46:34.461  1039  1526 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-04 10:46:34.461  7696  7696 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-04 10:46:34.462  1039  1526 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
,08-04 10:46:34.462  1039  1526 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-04 10:46:34.462  7696  7696 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-04 10:46:34.463  1039  1526 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-04 10:46:34.463  1039  1526 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-04 10:46:34.463  7696  7696 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-04 10:46:34.463  1930  7720 D WfdsMonitor: Supplicant connection established
08-04 10:46:34.464  1930  2236 D WfdsService: Connected to the supplicant for wfds
08-04 10:46:34.464  1039  1526 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-04 10:46:34.465  1039  1526 E WifiNative: : [151,873,866 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-04 10:46:34.465  1039  1526 D WifiNative-wlan0: doBoolean: RECONNECT
08-04 10:46:34.465  6815  6815 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 10:46:34.466  1039  1526 D WifiNative-wlan0: RECONNECT: returned true
08-04 10:46:34.466  1039  1526 D WifiNative-wlan0: doString: [STATUS]
08-04 10:46:34.467  1039  7717 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-04 10:46:34.467  1039  7717 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-04 10:46:34.467  1039  1526 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-04 10:46:34.467  1039  1526 D WifiNative-wlan0: doBoolean: SET ps 1
08-04 10:46:34.467  1039  1526 D WifiNative-wlan0: SET ps 1: returned true
08-04 10:46:34.468  1039  1525 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:34.470   315   897 D CommandListener: Setting iface cfg
08-04 10:46:34.470   315   897 D CommandListener: Trying to bring up p2p0
08-04 10:46:34.470  1039  1525 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-04 10:46:34.470  1039  1525 D LGWifiP2pService: P2pEnablingState
08-04 10:46:34.470  1039  1525 D LGWifiP2pService: P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:34.470  1039  1525 D LGWifiP2pService: P2p socket connection successful
08-04 10:46:34.470  1039  1525 D LGWifiP2pService: P2pEnabledState
08-04 10:46:34.476  1039  1526 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-04 10:46:34.476  6919  7721 W FormManager: Network not available. Please check & try again.
08-04 10:46:34.476  1039  1526 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-04 10:46:34.476  1039  1526 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-04 10:46:34.477  1039  1526 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-04 10:46:34.477  1039  1526 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-04 10:46:34.478  1039  1526 E WifiStateMachine:  ConnectModeState what:132106 1 0
,08-04 10:46:34.474  1039  1525 D LGWifiP2pService: sending p2p connection changed broadcast
08-04 10:46:34.478  1039  1526 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-04 10:46:34.478  1039  1526 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-04 10:46:34.479  7696  7696 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-04 10:46:34.479  1039  1526 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-04 10:46:34.480  1039  1526 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-04 10:46:34.480  1039  1526 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-04 10:46:34.481  1039  1526 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-04 10:46:34.481  7696  7696 E wpa_supplicant: disconnect_rssi_lvl: -100
08-04 10:46:34.481  1930  1930 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-04 10:46:34.481  1930  1930 D WfdsService: WifiP2pState is changed : true
08-04 10:46:34.481  1039  1526 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-04 10:46:34.481  1039  1039 D WifiScanningService: SCAN_AVAILABLE : 3
08-04 10:46:34.481  1039  1039 D RttService: SCAN_AVAILABLE : 3
08-04 10:46:34.482  1039  1544 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:34.482  1039  1544 I WifiNative-HAL: startHal
08-04 10:46:34.482  1039  1544 D wifi    : getting scan capabilities on interface[1] = 0xaf6723c0
08-04 10:46:34.482  1039  1544 D wifi    : failed to get capabilities : -3
08-04 10:46:34.482  1039  1544 E WifiScanningService: could not get scan capabilities
,08-04 10:46:34.482  1039  1545 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:34.483  1930  2236 D WfdsService: Receive the WFDS_ENABLE Method
08-04 10:46:34.483  1930  2236 D WfdsService: Set the WFDS Monitor: true
08-04 10:46:34.483  1930  2236 D WfdsService: Connected to the supplicant for wfds
08-04 10:46:34.483  1930  2236 D WfdsJNI : doCommand: WFDS_SET TRUE
08-04 10:46:34.483  7696  7696 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-04 10:46:34.484  1039  1525 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-04 10:46:34.484  1039  1526 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-04 10:46:34.484  1039  1525 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-04 10:46:34.484  1930  2236 D WfdsService: selectPreferredScanChannel [36]
08-04 10:46:34.484  1930  2236 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-04 10:46:34.484  1039  1525 D WifiNative-p2p0: doBoolean: SET device_name G3
08-04 10:46:34.484  1039  1526 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-04 10:46:34.484  1039  1526 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-04 10:46:34.485  1039  1525 D WifiNative-p2p0: SET device_name G3: returned true
08-04 10:46:34.485  1039  1525 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-04 10:46:34.485  1039  1525 D LGWifiP2pService: before postfix = G3
08-04 10:46:34.485  1039  1525 D WifiServerServiceExt: postfix byte check : 2
08-04 10:46:34.485  1039  1525 D LGWifiP2pService: after postfix = G3
08-04 10:46:34.485  1039  1525 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-04 10:46:34.485  1039  1525 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-04 10:46:34.485  6919  7722 V FormManager: Network unavailable.
08-04 10:46:34.485  1039  1525 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-04 10:46:34.486  7696  7696 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-04 10:46:34.486  7696  7696 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-04 10:46:34.486  1039  7717 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-04 10:46:34.486  1039  7717 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-04 10:46:34.487  1039  7717 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-04 10:46:34.487  1039  7717 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-04 10:46:34.487  7696  7696 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-04 10:46:34.487  7696  7696 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 10:46:34.487  1930  7720 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-04 10:46:34.488  1039  7717 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-04 10:46:34.488  1930  1930 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-04 10:46:34.488  1039  7717 E WifiMonitor: WifiMonitor:p2p0 cnt=36 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 10:46:34.488  1039  7717 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 10:46:34.488  1039  7717 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 10:46:34.488  7696  7696 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 10:46:34.488  1039  1526 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-04 10:46:34.488  1039  7717 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-04 10:46:34.488  1039  7717 E WifiMonitor: WifiMonitor:p2p0 cnt=37 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 10:46:34.489  1930  7720 D WfdsMonitor: E,vent [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-04 10:46:34.489  1930  1930 D WfdsService: isConnected: false
08-04 10:46:34.489  1039  7717 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 10:46:34.489  1039  7717 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 10:46:34.489  1039  1526 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-04 10:46:34.490  1039  1526 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-04 10:46:34.491  1039  1526 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-04 10:46:34.491  1039  1526 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-04 10:46:34.491  7696  7696 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-04 10:46:34.491  7696  7696 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-04 10:46:34.491  1039  7717 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-04 10:46:34.491  1039  7717 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-04 10:46:34.491  1039  7717 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-04 10:46:34.491  1039  7717 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,08-04 10:46:34.492  1039  1526 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-04 10:46:34.492  1039  1526 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-04 10:46:34.492  1039  1526 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-04 10:46:34.492  1039  1526 D WifiNative-wlan0: doBoolean: SCAN
08-04 10:46:34.493  1039  1526 D WifiNative-wlan0: SCAN: returned false
08-04 10:46:34.493  1039  1526 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=151902  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,08-04 10:46:34.494  1039  1525 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-04 10:46:34.494  1039  1525 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-04 10:46:34.494  1039  1525 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-04 10:46:34.494  1039  1525 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-04 10:46:34.495  1039  1525 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-04 10:46:34.495  1039  1525 D WifiNative-HAL: p2pGetDeviceAddress
08-04 10:46:34.495  1039  1525 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
,08-04 10:46:34.496  1039  1526 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=151905  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-04 10:46:34.497  1039  1526 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-04 10:46:34.497  1039  1526 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-04 10:46:34.497  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:34.497  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-04 10:46:34.498  1039  1526 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-04 10:46:34.498  1039  1526 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-04 10:46:34.499  1039  1525 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-04 10:46:34.499  1039  1525 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-04 10:46:34.499  1039  1039 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 10:46:34.499  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 10:46:34.499  1039  1039 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 10:46:34.499  1039  1039 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-04 10:46:34.500  1039  1525 D WifiNative-p2p0: P2P_FLUSH: returned true
08-04 10:46:34.500  1039  1525 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-04 10:46:34.500  6919  7722 V FormManager: Network unavailable.
08-04 10:46:34.500  1039  1525 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-04 10:46:34.501  1039  1525 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-04 10:46:34.501  1039  1525 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-04 10:46:34.501  1039  1525 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-04 10:46:34.502  1930  1930 I WfdStateTracker: handleP2pThisDeviceChanged
08-04 10:46:34.502  1930  1930 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-04 10:46:34.502  1930  1930 D WfdsService: Update P2p Interface State: 3
08-04 10:46:34.502  1039  1526 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-04 10:46:34.503  1039  1039 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-04 10:46:34.503  1039  1039 D WifiServerServiceExt: setSupplicantStateSCANNING
08-04 10:46:34.507  4298  4298 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-04 10:46:34.507  4298  4298 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-04 10:46:34.509  4298  4298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-04 10:46:34.514  4298  4298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-04 10:46:34.520  7311  7311 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-04 10:46:34.520  7311  7311 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-04 10:46:34.520  7311  7311 V [BNRBootReceiver]: Boot Receiver Return
08-04 10:46:34.523  1039  1525 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-04 10:46:34.523  1039  1525 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-04 10:46:34.523  6409  6409 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-04 10:46:34.523  1039  1525 D LGWifiP2pService: InactiveState
08-04 10:46:34.523  1039  1525 D LGWifiP2pService: InactiveState{ when=-36ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:34.523  1039  1525 D LGWifiP2pService: P2pEnabledState{ when=-36ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:34.523  1039  1525 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
,08-04 10:46:34.525  7696  7696 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-04 10:46:34.525  4298  7723 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-04 10:46:34.526  7696  7696 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-04 10:46:34.526  1930  7720 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-04 10:46:34.526  1039  7717 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-04 10:46:34.526  1039  7717 E WifiMonitor: WifiMonitor:p2p0 cnt=39 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-04 10:46:34.526  1039  7717 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-04 10:46:34.526  1039  7717 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-04 10:46:34.527  7696  7696 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-04 10:46:34.527  7696  7696 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 10:46:34.527  1930  7720 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-04 10:46:34.527  1039  7717 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-04 10:46:34.527  1039  7717 E WifiMonitor: WifiMonitor:p2p0 cnt=40 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 10:46:34.527  1039  7717 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 10:46:34.527  1039  7717 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 10:46:34.527  7696  7696 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 10:46:34.527  4298  7724 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-04 10:46:34.527  1930  7720 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-04 10:46:34.527  1039  7717 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-04 10:46:34.527  1039  7717 E WifiMonitor: WifiMonitor:p2p0 cnt=41 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 10:46:34.528  1039  7717 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 10:46:34.528  1039  7717 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 10:46:34.528  4298  7724 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-04 10:46:34.528  1039  1525 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-04 10:46:34.529  1039  1525 D LGWifiP2pService: InactiveState{ when=-28ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:34.529  1039  1525 D LGWifiP2pService: P2pEnabledState{ when=-28ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:34.529  1039  1525 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:34.529  1039  1525 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:34.529  1039  1525 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:34.529  1039  1525 D LGWifiP2pService: InactiveState{ when=0 what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:34.529  1039  1525 D LGWifiP2pService: P2pEnabledState{ when=0 what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:34.529  1039  1525 D LGWifiP2pService: DefaultState{ when=0 what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:34.529  1039  1525 D LGWifiP2pService: InactiveS,tate{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:34.529  1039  1525 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:34.529  1039  1525 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:34.529  1039  1525 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:34.529  1039  1525 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:34.530  1039  1525 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:34.530  1039  1039 E WifiServerServiceExt: No p2p device connected
08-04 10:46:34.530  1930  2236 W WfdsService: DefaultState - msg [9441285] is not handled
08-04 10:46:34.531  6815  6815 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-04 10:46:34.536  6815  6815 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-04 10:46:34.542  6869  6869 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-04 10:46:34.542  6869  6869 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-04 10:46:34.543  6869  6869 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-04 10:46:34.557  7535  7535 V BluetoothOppNotification: new notify threadi!
08-04 10:46:34.557  7535  7535 V BluetoothOppNotification: send delay message
08-04 10:46:34.558  7535  7725 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-04 10:46:34.559  7535  7725 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3d0b4d8 on behalf of 
08-04 10:46:34.560  7535  7725 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-04 10:46:34.561  7535  7725 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-04 10:46:34.561  7535  7725 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2e070031 on behalf of 
08-04 10:46:34.562  7535  7725 V BluetoothOppNotification: outbound: succ-0  fail-0
08-04 10:46:34.563  7535  7725 V BluetoothOppNotification: outbound notification was removed.
08-04 10:46:34.563  7535  7725 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-04 10:46:34.563  7535  7725 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@11f03316 on behalf of 
08-04 10:46:34.564  7535  7725 V BluetoothOppNotification: inbound: succ-0  fail-0
08-04 10:46:34.565  7535  7725 V BluetoothOppNotification: inbound notification was removed.
08-04 10:46:34.565  7535  7725 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-04 10:46:34.565  7535  7725 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2bdaa497 on behalf of 
08-04 10:46:35.043  7696  7696 E wpa_supplicant: USIM:  scard_init function
08-04 10:46:35.045  7696  7696 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-04 10:46:35.062  1039  7717 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-04 10:46:35.062  1039  7717 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-04 10:46:35.062  1039  7717 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-04 10:46:35.062  1039  7717 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: WPS-AP-AVAILABLE 
08-04 10:46:35.063  1039  1526 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-04 10:46:35.064  1039  1526 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-04 10:46:35.064  1039  1526 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-04 10:46:35.064  1039  1526 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-04 10:46:35.064  1039  1526 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-04 10:46:35.067  1039  7717 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-04 10:46:35.067  1039  7717 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-04 10:46:35.067  1039  7717 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-04 10:46:35.087  1039  1526 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=152496  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-04 10:46:35.097  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:35.097  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-04 10:46:35.100  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 10:46:35.102  1039  1039 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 10:46:35.102  1039  1039 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 10:46:35.102  1039  1039 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
,08-04 10:46:35.113  1039  1039 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 10:46:35.113  1039  1039 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 10:46:35.113  1039  1039 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-04 10:46:35.114  1039  1526 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=152523  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-04 10:46:35.115  1039  1039 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-04 10:46:35.115  1039  1039 D WifiServerServiceExt: setSupplicantStateASSOCIATING
,08-04 10:46:35.122  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:35.122  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-04 10:46:35.125  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 10:46:35.128  6815  6815 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-04 10:46:35.146  6815  6815 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-04 10:46:35.151  6409  6409 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-04 10:46:35.160  6815  6815 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-04 10:46:35.170  6815  6815 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 10:46:35.177  6869  6869 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-04 10:46:35.177  6869  6869 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-04 10:46:35.183  7696  7696 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-04 10:46:35.193  7696  7696 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-04 10:46:35.193  7696  7696 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-04 10:46:35.188  1039  7717 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-04 10:46:35.201  1039  7717 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-04 10:46:35.206  1039  1526 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=152615  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-04 10:46:35.207  1039  7717 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-04 10:46:35.207  1039  7717 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-04 10:46:35.207  1039  7717 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-04 10:46:35.207  1039  7717 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-04 10:46:35.208  1039  1526 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=152617  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-04 10:46:35.208  1039  7717 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-04 10:46:35.208  1039  7717 E WifiMonitor: WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-04 10:46:35.208  1039  7717 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-04 10:46:35.209  1039  7717 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-04 10:46:35.209  1039  7717 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-04 10:46:35.209  1039  7717 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-04 10:46:35.209  1039  7717 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-04 10:46:35.209  1039  7717 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-04 10:46:35.209  1039  7717 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-04 10:46:35.209  1039  7717 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-04 10:46:35.211  1039  1526 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 46 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=152620
08-04 10:46:35.212  1039  1526 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 46 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=152621
,08-04 10:46:35.213  1039  1526 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 46 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=152623
08-04 10:46:35.215  1039  1526 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 46 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=152624
08-04 10:46:35.216  1039  1526 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 46 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=152625
08-04 10:46:35.217  1039  1526 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=152626  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-04 10:46:35.220  6869  6869 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-04 10:46:35.222  1039  1039 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 10:46:35.222  1039  1039 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 10:46:35.222  1039  1039 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-04 10:46:35.223  1039  1526 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=152632  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-04 10:46:35.225  1039  1039 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 10:46:35.225  1039  1039 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 10:46:35.225  1039  1039 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-04 10:46:35.226  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:35.226  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-04 10:46:35.232  1039  1121 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-04 10:46:35.234  6409  6409 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-04 10:46:35.234  1039  1526 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=152643  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-04 10:46:35.234  1039  1526 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=152643  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-04 10:46:35.235  1039  1526 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=152644
08-04 10:46:35.236  1039  1039 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-04 10:46:35.236  1039  1039 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-04 10:46:35.236  1039  1526 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=152645
08-04 10:46:35.237  1039  1526 D WifiNative-wlan0: doString: [STATUS]
08-04 10:46:35.237  1039  7717 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-04 10:46:35.237  1039  7717 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-04 10:46:35.238  1039  1526 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-04 10:46:35.242  1039  1526 I WifiServiceExtension: setVHTCapabilityType  : false
,08-04 10:46:35.247  6815  6815 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-04 10:46:35.247  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 10:46:35.249  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:35.249  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-04 10:46:35.251  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 10:46:35.253  6815  6815 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 10:46:35.256  1039  1526 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-04 10:46:35.256  1039  1526 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-04 10:46:35.261  6869  6869 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-04 10:46:35.270  1039  1526 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-04 10:46:35.270  1039  1039 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-04 10:46:35.270  1039  1039 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 10:46:35.270  1039  1526 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-04 10:46:35.270  1039  1039 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-04 10:46:35.270  1039  1526 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-04 10:46:35.270  1039  1039 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 10:46:35.270  1039  1039 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 10:46:35.270  1039  1039 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-04 10:46:35.270  1039  1526 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-04 10:46:35.270  1039  1526 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-04 10:46:35.271  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:35.271  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-04 10:46:35.272  1039  1532 D ConnectivityService: Got NetworkAgent Messenger
08-04 10:46:35.272  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 10:46:35.272  1039  1532 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-04 10:46:35.272  1039  1532 D ConnectivityService: NetworkAgent connected
08-04 10:46:35.272  6869  6869 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-04 10:46:35.273  6869  6869 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-04 10:46:35.273  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:35.273  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-04 10:46:35.276  1039  1526 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-04 10:46:35.276  1039  1526 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-04 10:46:35.276  1039  1526 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-04 10:46:35.277  6409  6409 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-04 10:46:35.277  1039  1526 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-04 10:46:35.277  1039  1526 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-04 10:46:35.277  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 10:46:35.282  6815  6815 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-04 10:46:35.284  1039  1526 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-04 10:46:35.285   315   897 D CommandListener: Setting iface cfg
08-04 10:46:35.287  1039  1526 E WifiStateMachine: Start Dhcp Watchdog 2
08-04 10:46:35.287  1039  7753 D DhcpStateMachine: StoppedState
08-04 10:46:35.287  1039  7753 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:35.287  1039  7753 D DhcpStateMachine: WaitBeforeStartState
08-04 10:46:35.287  1039  1526 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=152696  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-04 10:46:35.288  1039  1526 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=152697  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-04 10:46:35.288  1039  1526 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=152697  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-04 10:46:35.289  6815  6815 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 10:46:35.291  1039  1039 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-04 10:46:35.291  1039  1039 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-04 10:46:35.291  1039  1526 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-04 10:46:35.291  1039  1526 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-04 10:46:35.291  1039  1526 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-04 10:46:35.292  1039  1526 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-04 10:46:35.292  1039  1526 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-04 10:46:35.292  1039  1526 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-04 10:46:35.293  1039  1526 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=152702  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-04 10:46:35.293  1039  1526 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=152702  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-04 10:46:35.293  1039  1526 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=152702  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-04 10:46:35.294  1039  1526 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:107514] from screen [on:0 period:1421580062] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-04 10:46:35.295  1039  1526 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1421580063] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-04 10:46:35.295  1039  1526 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-04 10:46:35.296  6869  6869 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-04 10:46:35.296  6869  6869 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-04 10:46:35.296  6869  6869 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-04 10:46:35.301  6409  6409 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-04 10:46:35.304  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 10:46:35.305  1039  1532 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-04 10:46:35.306  1039  1526 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 10:46:35.306  1039  1526 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 10:46:35.306  1039  1526 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,08-04 10:46:35.307  1039  1526 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 10:46:35.307  1039  1526 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 10:46:35.307  1039  1526 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 10:46:35.308  1039  1532 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-04 10:46:35.308  1039  1526 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=159,0,0
08-04 10:46:35.308  1039  1526 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=159,0,0
08-04 10:46:35.308  1039  1526 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-04 10:46:35.309  7696  7696 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-04 10:46:35.309  1039  1526 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-04 10:46:35.309  1039  1526 D WifiNative-wlan0: doBoolean: SET ps 0
08-04 10:46:35.309  1039  1526 D WifiNative-wlan0: SET ps 0: returned true
08-04 10:46:35.309  1039  1526 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-04 10:46:35.309  7696  7696 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
,08-04 10:46:35.310  1039  1526 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
,08-04 10:46:35.310  1039  1526 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-04 10:46:35.310  1039  1526 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-04 10:46:35.310  1039  1525 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3fffa83e target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:35.310  1039  1525 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3fffa83e target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:35.310  1039  1526 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-04 10:46:35.310  1039  7753 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:35.310  1039  7753 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-04 10:46:35.311  6815  6815 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-04 10:46:35.311   315   897 D CommandListener: Setting iface cfg
08-04 10:46:35.312   315   897 D CommandListener: Trying to bring up wlan0
08-04 10:46:35.312  1039  1526 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-04 10:46:35.313  1039  1039 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-04 10:46:35.313  1039  1039 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-04 10:46:35.313  1039  1039 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-04 10:46:35.313  1039  1039 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-04 10:46:35.314  1039  1526 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
08-04 10:46:35.314  1039  1526 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
08-04 10:46:35.314  1039  1526 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-04 10:46:35.314  1039  1525 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:35.314  1039  1525 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:35.314  7696  7696 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-04 10:46:35.314  1039  1526 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-04 10:46:35.314  1039  1526 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-04 10:46:35.314  7696  7696 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-04 10:46:35.315  1039  1526 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-04 10:46:35.315  1039  1526 D WifiNative-wlan0: doBoolean: SET ps 1
08-04 10:46:35.316  6815  6815 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 10:46:35.321  6869  6869 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-04 10:46:35.321  6869  6869 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-04 10:46:35.321  6869  6869 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-04 10:46:35.325  6815  6815 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-04 10:46:35.325  6815  6815 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-04 10:46:35.325  6815  6815 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-04 10:46:35.325  6815  6815 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-04 10:46:35.325  6815  6815 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-04 10:46:35.325  6815  6815 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-04 10:46:35.326  6815  6815 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-04 10:46:35.326  6815  6815 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-04 10:46:35.326  6815  6815 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-04 10:46:35.326  6815  6815 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-04 10:46:35.326  6815  6815 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-04 10:46:35.326  6815  6815 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-04 10:46:35.329  6409  6409 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-04 10:46:35.336  1039  1526 D WifiNative-wlan0: SET ps 1: returned true
08-04 10:46:35.336  1039  1532 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-04 10:46:35.336  1039  1526 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-04 10:46:35.337  1039  1526 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-04 10:46:35.337  1039  1526 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-04 10:46:35.337  1039  1526 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-04 10:46:35.338  1039  1526 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-04 10:46:35.338  1039  1526 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-04 10:46:35.338  1039  1532 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-04 10:46:35.339  6815  6815 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-04 10:46:35.339  1039  1526 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-04 10:46:35.340  1039  1526 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-04 10:46:35.340  1039  1526 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-04 10:46:35.340  1039  1532 D ConnectivityService: ignoring duplicate network state non-change
08-04 10:46:35.343  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:35.343  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-04 10:46:35.344  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 10:46:35.345  1039  1039 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 10:46:35.345  1039  1039 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 10:46:35.345  1039  1039 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-04 10:46:35.346  1039  1532 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-04 10:46:35.348  1039  1532 D ConnectivityService: Adding iface wlan0 to network 101
,08-04 10:46:35.351  1039  1039 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 10:46:35.351  1039  1039 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 10:46:35.351  1039  1039 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-04 10:46:35.354  1039  1526 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-04 10:46:35.354  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:35.354  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-04 10:46:35.354  6705  6769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:46:35.354  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:35.354  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:35.354  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:46:35.354  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 10:46:35.354  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:46:35.354  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:46:35.354  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 10:46:35.356  1039  1039 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-04 10:46:35.357  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 10:46:35.357  6705  6769 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 10:46:35.359  1039  1039 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 10:46:35.360  1039  1039 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 10:46:35.360  1930  1930 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-04 10:46:35.360  1039  1039 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,08-04 10:46:35.361  1039  1039 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-04 10:46:35.365  6705  6769 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-04 10:46:35.366  6705  6769 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-04 10:46:35.368  6705  6769 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@f93795c Bundle[{}]
08-04 10:46:35.369  6705  6769 I io.jxcore.node.LifeCycleMonitor: start: OK
08-04 10:46:35.369  6705  6769 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-04 10:46:35.370  6705  6769 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-04 10:46:35.370  6705  6769 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-04 10:46:35.371  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:35.371  1590  1590 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-04 10:46:35.371  1039  1039 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 10:46:35.371  1039  1039 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 10:46:35.371  6705  6769 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-04 10:46:35.371  1039  1039 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-04 10:46:35.371  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 10:46:35.372  6705  6769 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-04 10:46:35.375  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:35.376  1590  1590 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-04 10:46:35.376  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 10:46:35.377  6705  6769 I System.out: Running OutgoingSocketThread
08-04 10:46:35.379  6705  7756 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 871)
08-04 10:46:35.380  6705  7756 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 37679
08-04 10:46:35.380  6705  7756 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-04 10:46:35.381  1039  1532 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-04 10:46:35.381  1039  1532 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-04 10:46:35.382  6815  6815 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 10:46:35.382  1039  1532 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-04 10:46:35.383   315   897 E Netd    : netlink response contains error (File exists)
08-04 10:46:35.383  1039  1532 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-04 10:46:35.384  1039  1532 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-04 10:46:35.384  1039  1532 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-04 10:46:35.384  1039  1532 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-04 10:46:35.389  1039  1532 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-04 10:46:35.389  1039  1532 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-04 10:46:35.389  1039  1532 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-04 10:46:35.389  1039  1532 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-04 10:46:35.389  1039  1532 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-04 10:46:35.389  1039  1532 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-04 10:46:35.389  1039  1532 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-04 10:46:35.389  1039  1532 D ConnectivityService:   checking if request is sati,sfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 10:46:35.389  1039  1532 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-04 10:46:35.389  1039  1532 D ConnectivityService: currentScore = 0, newScore = 20
08-04 10:46:35.389  1039  1532 D ConnectivityService:    accepting network in place of null
08-04 10:46:35.389  1039  1532 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 10:46:35.390  1039  7752 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:35.390  1039  1526 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 10:46:35.390  1039  7752 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-04 10:46:35.390  1039  1526 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-04 10:46:35.390  1039  7752 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:35.390  1039  7752 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
,08-04 10:46:35.392  1840  1840 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 10:46:35.392  1840  1840 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-04 10:46:35.393  1039  1532 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-04 10:46:35.393  1039  1532 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-04 10:46:35.393  1039  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-04 10:46:35.394   315  7759 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-04 10:46:35.400  1039  1532 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-04 10:46:35.401  6869  6869 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-04 10:46:35.401  6869  6869 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-04 10:46:35.401  1039  1039 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-04 10:46:35.401  6869  6869 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-04 10:46:35.401  1039  1039 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-04 10:46:35.401  1039  1039 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-04 10:46:35.401  1039  1039 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-04 10:46:35.407  1039  1532 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-04 10:46:35.407  1039  1532 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-04 10:46:35.408  6409  6409 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-04 10:46:35.411  1039  1532 D ConnectivityService: validation of new default Network = false
08-04 10:46:35.411  1039  1532 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-04 10:46:35.411  1039  1532 D DSQN    : enableDataServiceNotify 
08-04 10:46:35.411  1039  1532 D DSQN    : start dsqn bin
08-04 10:46:35.418  6815  6815 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-04 10:46:35.418  1039  1532 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-04 10:46:35.418  1039  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 10:46:35.418  1039  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-04 10:46:35.419  1039  1532 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-04 10:46:35.417  7760  7760 W dsqn    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 10:46:35.417  7760  7760 W dsqn    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-04 10:46:35.421  1590  2055 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-04 10:46:35.425  1039  1524 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-04 10:46:35.425  6815  6815 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 10:46:35.433  6869  6869 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-04 10:46:35.434  6869  6869 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-04 10:46:35.434  7760  7760 E DSQN    : DSQN ssw
08-04 10:46:35.434  6869  6869 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-04 10:46:35.441   315  7759 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-04 10:46:35.446  6409  6409 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-04 10:46:35.453  1805  7764 I CheckinService: active receiver: enabled
,08-04 10:46:35.462  1805  7764 I CheckinService: Preparing to send checkin request
,08-04 10:46:35.463  1805  7764 I EventLogService: Accumulating logs since 1470300302059
08-04 10:46:35.464  6815  6815 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-04 10:46:35.470  6815  6815 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 10:46:35.473   315  7759 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-04 10:46:35.477  6869  6869 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-04 10:46:35.479  6869  6869 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-04 10:46:35.480  1805  7764 W EventLogAggregator: Unknown tag: snet_gcore
08-04 10:46:35.480  1805  7764 W EventLogAggregator: Unknown tag: snet_launch_service
08-04 10:46:35.482  6869  6869 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-04 10:46:35.484  1590  1590 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-04 10:46:35.485  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 10:46:35.486  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 10:46:35.486  6409  6409 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-04 10:46:35.493  6815  6815 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-04 10:46:35.501  6815  6815 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 10:46:35.507  6869  6869 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-04 10:46:35.508  6869  6869 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-04 10:46:35.509  6869  6869 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-04 10:46:35.512  1039  7753 D DhcpStateMachine: DHCPV4 request on wlan0
08-04 10:46:35.512  1039  7753 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-04 10:46:35.512  1039  7753 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-04 10:46:35.513  6409  6409 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-04 10:46:35.507  7766  7766 W dhcpcd  : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 10:46:35.507  7766  7766 W dhcpcd  : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 10:46:35.518  6834  6834 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-04 10:46:35.519   315   896 D LGDataListener: argv[0]=dsqncommand
08-04 10:46:35.519   315   896 D LGDataListener: argv[1]=wlan0
08-04 10:46:35.519   315   896 D LGDataListener: argv[2]=1
08-04 10:46:35.519   315   896 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-04 10:46:35.520  1039  1119 D DSQN    : DSQM DsqnNotification wlan0  1
08-04 10:46:35.520  1039  1119 D DSQN    : start to monitor internet connection
08-04 10:46:35.524  6834  6834 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-04 10:46:35.524  7766  7766 I dhcpcd  : version 5.5.6 starting
08-04 10:46:35.526  7766  7766 E dhcpcd  : get_duid: m
08-04 10:46:35.526  7766  7766 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-04 10:46:35.527  7766  7766 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-04 10:46:35.527  6815  6815 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-04 10:46:35.534  6815  6815 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 10:46:35.544  6869  6869 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-04 10:46:35.544  6869  6869 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-04 10:46:35.545  6869  6869 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-04 10:46:35.546  6869  6869 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-04 10:46:35.547  6869  6869 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-04 10:46:35.547  1805  7764 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-04 10:46:35.552  6409  6409 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-04 10:46:35.557  6834  6834 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-04 10:46:35.557  6834  6834 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-04 10:46:35.560  6815  6815 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-04 10:46:35.562  1039  7752 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 04 Aug 2016 08:46:35 GMT], X-Android-Received-Millis=[1470300395561], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470300395518]}
08-04 10:46:35.562  1039  7752 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-04 10:46:35.562  1039  7752 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-04 10:46:35.562  1039  1532 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-04 10:46:35.562  1039  1532 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-04 10:46:35.562  1039  1532 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-04 10:46:35.562  1039  1532 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-04 10:46:35.562  1039  1532 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-04 10:46:35.562  1039  1532 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-04 10:46:35.562  1039  1532 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-04 10:46:35.563  1039  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 10:46:35.563  1039  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-04 10:46:35.563  1039  1532 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-04 10:46:35.563  1039  1532 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 10:46:35.564  1039  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-04 10:46:35.564  1039  1526 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 10:46:35.564  1039  1526 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-04 10:46:35.564  1590  2055 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-04 10:46:35.564  1840  1840 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 10:46:35.565  1840  1840 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-04 10:46:35.572  6815  6815 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 10:46:35.580  6869  6869 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-04 10:46:35.582  6869  6869 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-04 10:46:35.582  6869  6869 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-04 10:46:35.583  6869  6869 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-04 10:46:35.583  6869  6869 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-04 10:46:35.590  7766  7766 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-04 10:46:35.591  7766  7766 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-04 10:46:35.591  7766  7766 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-04 10:46:35.591  7766  7766 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-04 10:46:35.591  7766  7766 D dhcpcd  : wlan0: sending REQUEST (xid 0x300f9751), next in 3.96 seconds
,08-04 10:46:35.597  1590  1590 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-04 10:46:35.598  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 10:46:35.599  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 10:46:35.618  7766  7766 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,08-04 10:46:35.638  7766  7766 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
,08-04 10:46:35.638  7766  7766 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-04 10:46:35.639  7766  7766 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-04 10:46:35.639  7766  7766 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-04 10:46:35.639  7766  7766 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-04 10:46:35.639  7766  7766 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-04 10:46:35.639  7766  7766 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-04 10:46:35.639  7766  7766 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-04 10:46:35.708  1039  1054 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7781 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-04 10:46:35.781  7781  7781 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-04 10:46:35.782  7781  7781 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-04 10:46:35.815  7781  7781 I MultiDex: VM with version 2.1.0 has multidex support
,08-04 10:46:35.815  7781  7781 I MultiDex: install
08-04 10:46:35.815  7781  7781 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-04 10:46:35.828  7781  7781 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-04 10:46:35.834  2170  2170 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-04 10:46:35.847  2170  2170 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-04 10:46:35.849  2170  2170 D c       : Getting all permits...
08-04 10:46:35.849  2170  2170 D a       : Opening database...
08-04 10:46:35.853  2170  2170 D a       : Opening database auth.proximity.permit_store...
08-04 10:46:35.854  2170  2170 D a       : Closing database...
08-04 10:46:35.916  1039  7753 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-04 10:46:35.919  1039  7753 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-04 10:46:35.920  1039  7753 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-04 10:46:35.920  1039  7753 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-04 10:46:35.920  1039  7753 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-04 10:46:35.920  1039  7753 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-04 10:46:35.920  1039  7753 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-04 10:46:35.920  1039  7753 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-04 10:46:35.921  1039  7753 D DhcpStateMachine: RunningState
08-04 10:46:36.339  7821  7821 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-04 10:46:36.379  6705  6769 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 872)
08-04 10:46:36.379  6705  6769 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 872)
08-04 10:46:36.381  6705  6769 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 877)
08-04 10:46:36.382  6705  6769 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-04 10:46:36.382  6705  6769 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 878)
08-04 10:46:36.384  6705  6769 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 10:46:36.384  6705  6769 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5c7578 added. We now have 2 listener(s)
,08-04 10:46:36.387  1039  1893 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 10:46:36.397  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-04 10:46:36.397  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 10:46:36.397  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 10:46:36.397  6705  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 10:46:36.397  6705  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14f8c451 added. We now have 9 listener(s)
08-04 10:46:36.397  6705  6769 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 10:46:36.398  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-04 10:46:36.401  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 10:46:36.405  6705  6769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 10:46:36.405  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:36.405  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:36.405  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:46:36.405  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 10:46:36.405  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 10:46:36.405  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 10:46:36.405  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 10:46:36.406  6705  6769 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 10:46:36.406  6705  6769 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 10:46:36.407  6705  6769 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 10:46:36.407  6705  6769 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@313f55b7 added. We now have 3 listener(s)
08-04 10:46:36.408  1039  1874 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 10:46:36.408  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:46:36.410  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:46:36.414  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-04 10:46:36.414  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 10:46:36.414  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 10:46:36.414  6705  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 10:46:36.414  6705  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69f7124 added. We now have 10 listener(s)
08-04 10:46:36.414  6705  6769 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 10:46:36.414  6705  6769 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:46:36.414  6705  6769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:46:36.414  6705  6769 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:46:36.414  6705  6769 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:36.414  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:36.414  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 10:46:36.414  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 10:46:36.414  6705  6769 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5c7578 removed from the list
08-04 10:46:36.414  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:36.415  6705  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14f8c451 removed from the list
08-04 10:46:36.415  6705  6769 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:46:36.415  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:36.415  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:36.415  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 10:46:36.416  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:36.416  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:36.416  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:36.416  6705  6769 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14f8c451 not in the list
08-04 10:46:36.416  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:36.416  7821  7821 I dex2oat : dex2oat took 76.866ms (threads: 4)
08-04 10:46:36.416  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:36.417  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:36.417  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:36.417  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:36.417  6705  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69f7124 removed from the list
08-04 10:46:36.417  6705  6769 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:36.417  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:36.417  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:36.417  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 10:46:36.417  6705  6769 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@313f55b7 removed from the list
08-04 10:46:36.418  6705  6769 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 10:46:36.418  6705  6769 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c34548d added. We now have 2 listener(s)
08-04 10:46:36.418  1039  1766 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 10:46:36.423  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-04 10:46:36.423  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 10:46:36.423  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 10:46:36.423  6705  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 10:46:36.423  6705  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16192642 added. We now have 9 listener(s)
08-04 10:46:36.423  6705  6769 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 10:46:36.424  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-04 10:46:36.427  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 10:46:36.430  7781  7799 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 ,QUALCOMM build:  ()
08-04 10:46:36.430  7781  7799 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-04 10:46:36.430  7781  7799 I Adreno-EGL: Build Date: 12/12/14 금
08-04 10:46:36.430  7781  7799 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-04 10:46:36.430  7781  7799 I Adreno-EGL: Remote Branch: 
08-04 10:46:36.430  7781  7799 I Adreno-EGL: Local Patches: 
08-04 10:46:36.430  7781  7799 I Adreno-EGL: Reconstruct Branch: 
08-04 10:46:36.439  6705  6769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 10:46:36.439  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:36.439  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:36.439  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:46:36.439  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 10:46:36.439  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 10:46:36.439  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 10:46:36.439  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-04 10:46:36.441  6705  6769 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 10:46:36.441  6705  6769 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 10:46:36.442  6705  6769 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 10:46:36.442  6705  6769 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ef47b90 added. We now have 3 listener(s)
08-04 10:46:36.442  1039  1766 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 10:46:36.443  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:46:36.446  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-04 10:46:36.446  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 10:46:36.446  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 10:46:36.446  6705  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 10:46:36.446  6705  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d1eac89 added. We now have 10 listener(s)
08-04 10:46:36.446  6705  6769 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 10:46:36.446  6705  6769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 10:46:36.446  6705  6769 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 10:46:36.446  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-04 10:46:36.446  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 10:46:36.446  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-04 10:46:36.449  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:46:36.450  6705  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-04 10:46:36.450  1039  1928 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-04 10:46:36.457  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-04 10:46:36.457  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-04 10:46:36.458  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-04 10:46:36.459  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 10:46:36.461  6705  6769 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-04 10:46:36.461  6705  6769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:46:36.461  6705  6769 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-04 10:46:36.464  6705  6769 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:46:36.464  6705  6769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:46:36.464  6705  6769 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:46:36.465  6705  6769 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:36.465  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:36.465  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 10:46:36.465  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 10:46:36.465  6705  6769 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c34548d removed from the list
08-04 10:46:36.465  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:36.465  6705  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16192642 removed from the list
08-04 10:46:36.465  6705  6769 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:46:36.465  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:36.465  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:36.465  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:36.466  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:36.466  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:36.466  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:36.466  6705  6769 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16192642 not in the list
08-04 10:46:36.466  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:36.466  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:36.467  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:36.467  6705  6769 D BluetoothLeScanner: could not find callback wrapper
08-04 10:46:36.467  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 10:46:36.467  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:36.467  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:36.467  6705  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d1eac89 removed from the list
08-04 10:46:36.468  6705  6769 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:36.468  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:36.468  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 1,0:46:36.468  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 10:46:36.468  6705  6769 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ef47b90 removed from the list
08-04 10:46:36.468  6705  6769 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 10:46:36.468  6705  6769 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@134dc0bc added. We now have 2 listener(s)
08-04 10:46:36.468  1039  1766 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 10:46:36.470  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-04 10:46:36.470  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 10:46:36.470  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 10:46:36.470  6705  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 10:46:36.470  6705  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@363c8845 added. We now have 9 listener(s)
08-04 10:46:36.470  6705  6769 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 10:46:36.471  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-04 10:46:36.473  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 10:46:36.478  6705  6769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 10:46:36.478  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:36.478  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:36.478  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:46:36.478  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 10:46:36.478  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 10:46:36.478  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 10:46:36.478  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 10:46:36.479  6705  6769 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 10:46:36.479  6705  6769 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 10:46:36.480  6705  6769 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 10:46:36.480  6705  6769 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2537ccb added. We now have 3 listener(s)
08-04 10:46:36.481  1039  1874 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 10:46:36.481  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:46:36.483  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:46:36.484  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-04 10:46:36.484  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 10:46:36.484  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 10:46:36.485  6705  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 10:46:36.485  6705  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d942ca8 added. We now have 10 listener(s)
,08-04 10:46:36.485  6705  6769 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 10:46:36.485  6705  6769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 10:46:36.486  6705  6769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 10:46:36.486  6705  6769 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 10:46:36.486  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-04 10:46:36.486  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 10:46:36.486  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-04 10:46:36.488  6705  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-04 10:46:36.488  1039  1766 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 10:46:36.491  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-04 10:46:36.492  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-04 10:46:36.493  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-04 10:46:36.493  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 10:46:36.494  6705  6769 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-04 10:46:36.494  6705  6769 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:46:36.494  6705  6769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:46:36.494  6705  6769 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:46:36.494  6705  6769 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:36.494  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:36.494  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 10:46:36.494  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 10:46:36.494  6705  6769 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@134dc0bc removed from the list
08-04 10:46:36.494  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:36.495  6705  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@363c8845 removed from the list
08-04 10:46:36.495  6705  6769 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:46:36.495  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:36.495  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Bluetoo,thManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:36.495  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:36.495  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:36.495  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:36.496  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:36.496  6705  6769 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@363c8845 not in the list
08-04 10:46:36.496  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:36.496  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 10:46:36.497  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:36.498  6705  6769 D BluetoothLeScanner: could not find callback wrapper
08-04 10:46:36.498  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 10:46:36.498  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:36.498  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:36.498  6705  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d942ca8 removed from the list
08-04 10:46:36.498  6705  6769 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:36.498  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:36.498  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:36.498  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 10:46:36.498  6705  6769 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2537ccb removed from the list
08-04 10:46:36.500  6705  6769 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 10:46:36.501  6705  6769 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f9b1aa7 added. We now have 2 listener(s)
08-04 10:46:36.501  1039  1928 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 10:46:36.503  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-04 10:46:36.503  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 10:46:36.503  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 10:46:36.503  6705  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 10:46:36.503  6705  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b536b54 added. We now have 9 listener(s)
08-04 10:46:36.503  6705  6769 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 10:46:36.503  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-04 10:46:36.505  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 10:46:36.507  6705  6769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 10:46:36.507  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:36.507  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:36.507  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:46:36.507  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 10:46:36.507  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 10:46:36.507  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active netwo,rk: true
08-04 10:46:36.507  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-04 10:46:36.509  6705  6769 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 10:46:36.509  6705  6769 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 10:46:36.509  6705  6769 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 10:46:36.509  6705  6769 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1acba3f2 added. We now have 3 listener(s)
08-04 10:46:36.509  1039  1875 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 10:46:36.511  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:46:36.512  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:46:36.512  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-04 10:46:36.512  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 10:46:36.512  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 10:46:36.513  6705  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 10:46:36.513  6705  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33d4ba43 added. We now have 10 listener(s)
08-04 10:46:36.513  6705  6769 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 10:46:36.513  6705  6769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 10:46:36.513  6705  6769 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 10:46:36.513  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-04 10:46:36.513  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 10:46:36.513  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-04 10:46:36.516  6705  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-04 10:46:36.517  1039  2003 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 10:46:36.521  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-04 10:46:36.523  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-04 10:46:36.524  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-04 10:46:36.525  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 10:46:36.526  6705  6769 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-04 10:46:36.527  6705  6769 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:46:36.527  6705  6769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:46:36.527  6705  6769 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:46:36.527  6705  6769 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:36.527  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:36.527  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 10:46:36.527  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 10:46:36.527  6705  6769 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f9b1aa7 removed from the list
08-04 10:46:36.528  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:36.528  6705  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b536b54 removed from the list
08-04 10:46:36.528  6705  6769 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:46:36.528  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:36.528  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:36.528  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:36.529  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:36.529  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:36.529  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:36.529  6705  6769 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b536b54 not in the list
08-04 10:46:36.529  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:36.529  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:36.530  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:36.531  6705  6769 D BluetoothLeScanner: could not find callback wrapper
08-04 10:46:36.531  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 10:46:36.531  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:36.531  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:36.531  6705,  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33d4ba43 removed from the list
08-04 10:46:36.531  6705  6769 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:36.531  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:36.531  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:36.531  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 10:46:36.531  6705  6769 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1acba3f2 removed from the list
08-04 10:46:36.532  6705  6769 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 10:46:36.532  6705  6769 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37ec0d3e added. We now have 2 listener(s)
08-04 10:46:36.533  1039  1563 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-04 10:46:36.539  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-04 10:46:36.539  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 10:46:36.539  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 10:46:36.539  6705  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 10:46:36.539  6705  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@377eb79f added. We now have 9 listener(s)
08-04 10:46:36.539  6705  6769 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 10:46:36.540  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-04 10:46:36.543  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 10:46:36.545  6705  6769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 10:46:36.545  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:36.545  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:36.545  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:46:36.545  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 10:46:36.545  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 10:46:36.545  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 10:46:36.545  6705  6769 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-04 10:46:36.547  6705  6769 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 10:46:36.547  6705  6769 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 10:46:36.548  6705  6769 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 10:46:36.548  6705  6769 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e90cb5 added. We now have 3 listener(s)
08-04 10:46:36.548  1039  1766 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 10:46:36.550  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:46:36.551  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-04 10:46:36.551  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 10:46:36.552  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 10:46:36.552  6705  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 10:46:36.552  6705  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b17bf4a added. We now have 10 listener(s)
08-04 10:46:36.552  6705  6769 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 10:46:36.552  6705  6769 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:46:36.552  6705  6769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:46:36.552  6705  6769 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:46:36.552  6705  6769 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:36.553  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:36.553  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 10:46:36.553  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 10:46:36.553  6705  6769 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37ec0d3e removed from the list
08-04 10:46:36.553  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:36.553  6705  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@377eb79f removed from the list
08-04 10:46:36.553  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:46:36.553  6705  6769 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:46:36.553  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:36.554  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:36.554  6705  6769 D org.tha,liproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:36.554  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:36.554  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:36.554  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:36.555  6705  6769 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@377eb79f not in the list
08-04 10:46:36.555  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:36.555  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:36.555  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:36.555  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:36.555  6705  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:36.556  6705  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b17bf4a removed from the list
08-04 10:46:36.556  6705  6769 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:36.556  6705  6769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:36.556  6705  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:36.556  6705  6769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 10:46:36.556  6705  6769 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e90cb5 removed from the list
08-04 10:46:36.556  7781  7799 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-04 10:46:36.556  7781  7799 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-04 10:46:36.556  7781  7799 I Adreno-EGL: Build Date: 12/12/14 금
08-04 10:46:36.556  7781  7799 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-04 10:46:36.556  7781  7799 I Adreno-EGL: Remote Branch: 
08-04 10:46:36.556  7781  7799 I Adreno-EGL: Local Patches: 
08-04 10:46:36.556  7781  7799 I Adreno-EGL: Reconstruct Branch: 
08-04 10:46:36.557  6705  6769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-04 10:46:36.557  6705  6769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-04 10:46:36.557  6705  6769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-04 10:46:36.557  6705  6769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 10:46:36.558  6705  6769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-04 10:46:36.558  6705  6769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-04 10:46:36.570  1039  1526 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-04 10:46:36.570  1039  1526 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-04 10:46:36.570  1039  1526 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-04 10:46:36.570  1039  1526 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-04 10:46:36.571  1039  1526 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-04 10:46:36.571  1039  1526 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-04 10:46:36.571  1039  1532 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
08-04 10:46:36.571  1039  1532 D ConnectivityService: identical MTU - not setting
08-04 10:46:36.572  1039  1532 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-04 10:46:36.572  1039  1532 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-04 10:46:36.572  1039  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 10:46:36.572  1039  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-04 10:46:36.574  1039  1532 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-04 10:46:36.575  1590  2055 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-04 10:46:36.575  6705  7839 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 885, name: My test thread name)
08-04 10:46:36.576  6705  7839 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 885, thread name: My test thread name)
,08-04 10:46:36.576  6705  7839 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 885, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-04 10:46:36.579  6705  7840 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 887, name: My test thread name)
08-04 10:46:36.579  6705  7840 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 887, thread name: My test thread name)
08-04 10:46:36.580  6705  7840 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 887, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-04 10:46:36.582  6705  6769 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-04 10:46:36.582  6705  6769 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-04 10:46:36.582  6705  6769 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-04 10:46:36.582  6705  6769 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-04 10:46:36.582  6705  6769 D com.test.thalitest.ThaliTestRunner: Total duration: 23014 ms
08-04 10:46:36.584  6705  6769 I jxcore-log: Total number of executed tests:  80
08-04 10:46:36.584  6705  6769 I jxcore-log: 
08-04 10:46:36.584  6705  6769 I jxcore-log: Number of passed tests:  80
08-04 10:46:36.584  6705  6769 I jxcore-log: 
08-04 10:46:36.584  6705  6769 I jxcore-log: Number of failed tests:  0
08-04 10:46:36.584  6705  6769 I jxcore-log: 
08-04 10:46:36.584  6705  6769 I jxcore-log: Number of ignored tests:  0
08-04 10:46:36.584  6705  6769 I jxcore-log: 
08-04 10:46:36.584  6705  6769 I jxcore-log: Total duration:  23014
08-04 10:46:36.584  6705  6769 I jxcore-log: 
08-04 10:46:36.585  6705  6769 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-04 10:46:36.585  6705  6769 I jxcore-log: 
,08-04 10:46:36.591  6705  6769 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 10:46:36.591  6705  6769 I jxcore-log: 
08-04 10:46:36.594  6705  6769 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 10:46:36.594  6705  6769 I jxcore-log: ,
08-04 10:46:36.595  6705  6769 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 10:46:36.595  6705  6769 I jxcore-log: 
08-04 10:46:36.596  6705  6769 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 10:46:36.596  6705  6769 I jxcore-log: 
08-04 10:46:36.597  6705  6769 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 10:46:36.597  6705  6769 I jxcore-log: 
08-04 10:46:36.599  6705  6769 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-04 10:46:36.599  6705  6769 I jxcore-log: 
08-04 10:46:36.602  6705  6769 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-04 10:46:36.602  6705  6769 I jxcore-log: 
08-04 10:46:36.604  6705  6769 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 10:46:36.604  6705  6769 I jxcore-log: 
,08-04 10:46:36.604  6705  6769 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 10:46:36.604  6705  6769 I jxcore-log: 
08-04 10:46:36.606  6705  6769 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-04 10:46:36.606  6705  6769 I jxcore-log: 
08-04 10:46:36.607  6705  6769 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-04 10:46:36.607  6705  6769 I jxcore-log: 
08-04 10:46:36.608  6705  6769 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-04 10:46:36.608  6705  6769 I jxcore-log: 
08-04 10:46:36.611  6705  6769 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 10:46:36.611  6705  6769 I jxcore-log: 
08-04 10:46:36.611  6705  6705 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-04 10:46:36.612  6705  6769 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 10:46:36.612  6705  6769 I jxcore-log: 
,08-04 10:46:36.612  6705  6769 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-04 10:46:36.612  6705  6769 I jxcore-log: 
,08-04 10:46:36.613  6705  6769 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-04 10:46:36.613  6705  6769 I jxcore-log: 
08-04 10:46:36.614  6705  6769 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 10:46:36.614  6705  6769 I jxcore-log: 
08-04 10:46:36.615  6705  6769 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 10:46:36.615  6705  6769 I jxcore-log: 
08-04 10:46:36.616  6705  6769 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-04 10:46:36.616  6705  6769 I jxcore-log: 
08-04 10:46:36.616  6705  6769 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-04 10:46:36.616  6705  6769 I jxcore-log: 
08-04 10:46:36.617  6705  6769 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 10:46:36.617  6705  6769 I jxcore-log: 
08-04 10:46:36.618  6705  6769 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 10:46:36.618  6705  6769 I jxcore-log: 
08-04 10:46:36.619  6705  6769 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 10:46:36.619  6705  6769 I jxcore-log: 
,08-04 10:46:36.620  6705  6769 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 10:46:36.620  6705  6769 I jxcore-log: 
08-04 10:46:36.621  6705  6769 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 10:46:36.621  6705  6769 I jxcore-log: 
08-04 10:46:36.621  6705  6769 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 10:46:36.621  6705  6769 I jxcore-log: 
08-04 10:46:36.622  6705  6769 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 10:46:36.622  6705  6769 I jxcore-log: 
,08-04 10:46:36.663  7781  7799 D LgDataFeature: LgDataFeature() Constructor: none
,08-04 10:46:36.663  7781  7799 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-04 10:46:36.718  7781  7799 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-04 10:46:36.718  7781  7799 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-04 10:46:36.718  7781  7799 I Adreno-EGL: Build Date: 12/12/14 금
08-04 10:46:36.718  7781  7799 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-04 10:46:36.718  7781  7799 I Adreno-EGL: Remote Branch: 
08-04 10:46:36.718  7781  7799 I Adreno-EGL: Local Patches: 
08-04 10:46:36.718  7781  7799 I Adreno-EGL: Reconstruct Branch: 
,08-04 10:46:36.873  7842  7842 D AndroidRuntime: 
08-04 10:46:36.873  7842  7842 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-04 10:46:36.876  7842  7842 D AndroidRuntime: CheckJNI is OFF
,08-04 10:46:36.980   315  7858 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-04 10:46:36.980   315  7858 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,08-04 10:46:37.023   315  7858 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-04 10:46:37.039  7842  7842 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-04 10:46:37.053  1039  1113 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-04 10:46:37.053  1039  1113 I ActivityManager: Killing 6705:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-04 10:46:37.119  1039  1563 I WindowState: WIN DEATH: Window{21d9a1ca u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-04 10:46:37.119  1039  1531 D WifiService: Client connection lost with reason: 4
08-04 10:46:37.127  1039  1563 D InputDispatcher: Window went away: Window{21d9a1ca u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-04 10:46:37.183  1039  1113 I ActivityManager:   Force finishing activity ActivityRecord{34e1bf8 u0 com.test.thalitest/.MainActivity t40}
,08-04 10:46:37.214   343   365 E GBMv2   : DFP En is all cleared set to be enabled
08-04 10:46:37.215  1039  2020 W ActivityManager: Spurious death for ProcessRecord{37eef07f 6705:com.test.thalitest/u0a118}, curProc for 6705: null
,08-04 10:46:37.216  1039  1127 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-04 10:46:37.222  1039  1127 I ActivityManager:   Force finishing activity ActivityRecord{34e1bf8 u0 com.test.thalitest/.MainActivity t40 f}
08-04 10:46:37.222  1039  1127 W ActivityManager: Duplicate finish request for ActivityRecord{34e1bf8 u0 com.test.thalitest/.MainActivity t40 f}
08-04 10:46:37.233  1805  7764 I CheckinTask: Sending checkin request (7881 bytes)
,08-04 10:46:37.248  1930  2913 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-04 10:46:37.249  2021  2021 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-04 10:46:37.249  1930  2913 D SplitWindowPolicy: topRunningActivity=ActivityInfo{4d9458b co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
08-04 10:46:37.250  1930  1946 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-04 10:46:37.250  1930  1946 D SplitWindowPolicy: topRunningActivity=ActivityInfo{18352668 co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
,08-04 10:46:37.252  2021  2021 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume,
08-04 10:46:37.256  1590  1590 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-04 10:46:37.262  1039  1385 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-04 10:46:37.265  3805  3805 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-04 10:46:37.270  2453  2601 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-04 10:46:37.270  7535  7535 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-04 10:46:37.270  7535  7535 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-04 10:46:37.270  1984  1984 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
,08-04 10:46:37.280  4456  4456 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-04 10:46:37.280  4456  4456 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-04 10:46:37.280  4456  4456 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-04 10:46:37.281  4456  4456 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-04 10:46:37.281  4456  4456 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-04 10:46:37.281  4456  4456 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-04 10:46:37.281  4456  4456 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-04 10:46:37.281  4456  4456 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-04 10:46:37.281  4456  4456 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 10:46:37.281  4456  4456 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-04 10:46:37.281  4456  4456 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-04 10:46:37.281  4456  4456 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-04 10:46:37.303  4589  4589 I art     : Explicit concurrent mark sweep GC freed 919(49KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 779us total 62.290ms
,08-04 10:46:37.310  1039  1111 W InputMethodInfo: Duplicated subtype definition found: , voice
08-04 10:46:37.340  1039  1039 D administrator: Handling package changes for user 0
,08-04 10:46:37.342  6409  6409 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-04 10:46:37.342  2021  2021 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-04 10:46:37.343  2021  2108 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-04 10:46:37.381  1039  1929 I ActivityManager: Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7866 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-04 10:46:37.383  2021  2021 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-04 10:46:37.384  1894  1894 D ActionManagerService: notifyUserLog: 1000003
08-04 10:46:37.384  3805  4455 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-04 10:46:37.387  1805  1805 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-04 10:46:37.389  2021  2021 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-04 10:46:37.391  2021  2021 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-04 10:46:37.391  1590  1590 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-04 10:46:37.393  2021  2021 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
,08-04 10:46:37.417  1039  1947 V SIM_STK : Menu title from STK is T-Mobile
,08-04 10:46:37.419  1039  1875 V SIM_STK : Menu title from STK is T-Mobile
,08-04 10:46:37.419  1039  1875 V SIM_STK : Menu title from STK is T-Mobile
08-04 10:46:37.420  2021  2021 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-04 10:46:37.421  1894  1894 D ActionManagerService: notifyUserLog: 1000004
08-04 10:46:37.421  2170  2170 I ConfigService: onCreate
08-04 10:46:37.421  2170  2170 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-04 10:46:37.421  3805  4455 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-04 10:46:37.425  2170  2170 I ConfigService: onBind returning update interface
08-04 10:46:37.442  3805  3820 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,08-04 10:46:37.447  1590  1590 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-04 10:46:37.447  1590  1590 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-04 10:46:37.451  2021  2021 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-04 10:46:37.451  2021  2021 I GBoardWebViewUtils: , create_time: 1430832262123
08-04 10:46:37.451  2021  2021 I GBoardWebViewUtils: , expire_time: 0
08-04 10:46:37.451  2021  2021 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-04 10:46:37.451  2021  2021 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-04 10:46:37.451  2021  2021 I GBoardWebViewUtils: , display: false
08-04 10:46:37.451  2021  2021 I GBoardWebViewUtils: , animation: false }
08-04 10:46:37.451  2021  2021 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-04 10:46:37.451  2021  2021 I GBoardWebViewUtils: , create_time: 1430832262287
08-04 10:46:37.451  2021  2021 I GBoardWebViewUtils: , expire_time: 0
08-04 10:46:37.451  2021  2021 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-04 10:46:37.451  2021  2021 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-04 10:46:37.451  2021  2021 I GBoardWebViewUtils: , display: false
08-04 10:46:37.451  2021  2021 I GBoardWebViewUtils: , animation: false }
08-04 10:46:37.451  2021  2021 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1469801564706
08-04 10:46:37.451  2021  2021 I GBoardWebViewUtils: , create_time: 1469801565454
08-04 10:46:37.451  2021  2021 I GBoardWebViewUtils: , expire_time: 0
08-04 10:46:37.451  2021  2021 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide.html?id=guide_1111111111116_1469801564706&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-04 10:46:37.451  2021  2021 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-04 10:46:37.451  2021  2021 I GBoardWebViewUtils: , display: false
08-04 10:46:37.451  2021  2021 I GBoardWebViewUtils: , animation: false }
08-04 10:46:37.454  2021  7885 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,08-04 10:46:37.468  1805  1805 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,08-04 10:46:37.470  2170  2170 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-04 10:46:37.470  2170  2170 I ConfigService: onBind returning config service
08-04 10:46:37.476  1039  1874 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-04 10:46:37.477  7535  7535 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-04 10:46:37.477  7535  7535 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-04 10:46:37.477  7535  7535 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-04 10:46:37.477  7535  7535 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-04 10:46:37.477  7535  7535 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-04 10:46:37.477  7535  7535 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-04 10:46:37.477  7535  7535 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-04 10:46:37.477  7535  7535 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-04 10:46:37.477  7535  7535 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-04 10:46:37.477  7535  7535 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-04 10:46:37.477  7535  7535 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
,08-04 10:46:37.483  1857  1857 D SplitUIManager: split_name #11 / not available #0
08-04 10:46:37.484  1857  1857 D SplitUIService: removed split : 
08-04 10:46:37.488  1805  1805 I ConfigFetchService: service connected
08-04 10:46:37.489  1805  1805 I ConfigClient: service connected
08-04 10:46:37.489  7866  7866 I LockScreenSettings: Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
08-04 10:46:37.490  2021  2021 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-04 10:46:37.490  2021  2021 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-04 10:46:37.492  2170  2170 I ConfigService: onDestroy
,08-04 10:46:37.519  1805  7888 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-04 10:46:37.524  1039  1039 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-04 10:46:37.524  1039  1039 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-04 10:46:37.525  1039  1039 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-04 10:46:37.533  1039  1565 D TaskPersister: removeObsoleteFile: deleting file=40_task.xml
08-04 10:46:37.537  1857  1857 D SplitUIManager: split_name #11 / not available #0
08-04 10:46:37.537  1857  1857 I SplitUIService: split app #11
08-04 10:46:37.556  1039  1983 V SIM_STK : Menu title from STK is T-Mobile
,08-04 10:46:37.566  1039  1947 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7891 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
08-04 10:46:37.569  2021  2021 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-04 10:46:37.569  1590  1643 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-04 10:46:37.569  1590  1643 D KeyguardModel: createShortcutInfo...
,08-04 10:46:37.571  1590  1643 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-04 10:46:37.571  1590  1643 D KeyguardModel: createShortcutInfo...
08-04 10:46:37.576  1590  1643 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-04 10:46:37.577  1590  1643 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-04 10:46:37.577  1590  1643 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-04 10:46:37.578  1590  1643 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-04 10:46:37.578  1590  1643 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-04 10:46:37.578  1590  1643 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-04 10:46:37.579  1590  1643 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-04 10:46:37.579  1590  1643 D KeyguardModel: createShortcutInfo...
,08-04 10:46:37.586  1590  1643 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-04 10:46:37.586  1590  1643 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-04 10:46:37.588  1590  1643 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-04 10:46:37.589  1590  1643 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-04 10:46:37.591  1590  1643 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-04 10:46:37.591  1590  1643 D KeyguardModel: createShortcutInfo...
08-04 10:46:37.596  1590  1643 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-04 10:46:37.596  1590  1643 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-04 10:46:37.596  1590  1643 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-04 10:46:37.596  1590  1643 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-04 10:46:37.597  1590  1643 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-04 10:46:37.597  1590  1643 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-04 10:46:37.597  5897  7911 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-04 10:46:37.599  1590  1643 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-04 10:46:37.599  1590  1643 D KeyguardModel: createShortcutInfo...
08-04 10:46:37.601  1805  7912 I PeopleContactsSync: CP2 sync disabled
08-04 10:46:37.615  1805  4646 I Icing   : doRemovePackageData com.test.thalitest
,08-04 10:46:37.620  1590  1590 D KeyguardModel: handleShortcutListChanged...
08-04 10:46:37.620  1590  1590 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-04 10:46:37.625  1590  1643 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-04 10:46:37.625  1590  1643 D KeyguardModel: createShortcutInfo...
08-04 10:46:37.627   334   429 I ThermalEngine: Thermal-Server: Thermal received msg from  override
,08-04 10:46:37.628  3206  7914 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-04 10:46:37.635  1805  7910 W GmsApplication: Using Auth Proxy for data requests.
08-04 10:46:37.639  1590  1643 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-04 10:46:37.639  1590  1643 D KeyguardModel: createShortcutInfo...
08-04 10:46:37.640  1590  1643 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-04 10:46:37.640  1590  1643 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-04 10:46:37.643  1805  7910 W GmsApplication: Using Auth Proxy for data requests.
08-04 10:46:37.646  1590  1643 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-04 10:46:37.646  1590  1643 D KeyguardModel: createShortcutInfo...
,08-04 10:46:37.647  1590  1643 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-04 10:46:37.647  1590  1643 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-04 10:46:37.648  1590  1643 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-04 10:46:37.648  1590  1643 D KeyguardModel: createShortcutInfo...
08-04 10:46:37.650  1590  1643 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-04 10:46:37.650  1590  1643 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-04 10:46:37.659  7891  7891 I AppUp4:AppBoxCP: onCreate
08-04 10:46:37.660  7891  7891 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-04 10:46:37.660  1590  1643 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-04 10:46:37.660  1590  1643 D KeyguardModel: createShortcutInfo...
,08-04 10:46:37.664  1039  1766 I ActivityManager: Killing 7043:com.lge.email/u0a23 (adj 15): empty #17
08-04 10:46:37.667  7891  7891 I AppUp4:DB:  setFingerPrint start
08-04 10:46:37.667  7891  7891 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-04 10:46:37.682  7891  7891 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,08-04 10:46:37.682  7891  7891 I AppUp4:DB:  SDK version = 21
08-04 10:46:37.682  7891  7891 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-04 10:46:37.677  1039  1127 I art     : Explicit concurrent mark sweep GC freed 81645(4MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 43MB/65MB, paused 1.648ms total 257.462ms
08-04 10:46:37.693  2021  2021 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-04 10:46:37.697  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-04 10:46:37.698  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-04 10:46:37.699  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-04 10:46:37.700  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-04 10:46:37.701  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,08-04 10:46:37.719  2021  2021 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-04 10:46:37.719  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-04 10:46:37.719  2021  2148 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-04 10:46:37.719  2021  2148 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,08-04 10:46:37.732  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,08-04 10:46:37.733  2021  2021 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-04 10:46:37.733  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-04 10:46:37.741  2021  2021 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,08-04 10:46:37.743  1039  1111 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-04 10:46:37.746  1039  1111 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-04 10:46:37.758  1590  1590 D KeyguardModel: handleShortcutListChanged...
,08-04 10:46:37.758  1590  1590 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-04 10:46:37.759  7842  7842 D AndroidRuntime: Shutting down VM
08-04 10:46:37.759  1039  1928 W libprocessgroup: failed to open /acct/uid_10023/pid_7043/cgroup.procs: No such file or directory
,08-04 10:46:37.761  7891  7891 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-04 10:46:37.764  1039  1122 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{11cdddb0 u0 com.lge.launcher2/.Launcher t39} time:155185
08-04 10:46:37.790  1805  7890 I art     : Explicit concurrent mark sweep GC freed 18444(1275KB) AllocSpace objects, 12(192KB) LOS objects, 51% free, 30MB/62MB, paused 1.072ms total 24.343ms
08-04 10:46:37.790  1805  1817 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/history_query.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-04 10:46:37.790  1805  1817 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/help_responses.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-04 10:46:37.791  1805  1817 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/metrics.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,08-04 10:46:37.792  7891  7891 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-04 10:46:37.797  1039  1127 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7918 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-04 10:46:37.798  2581  2581 D [Concierge]Service: onStartCommand(). Type : 8
08-04 10:46:37.798  2581  2581 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-04 10:46:37.799  2581  2581 D [Concierge]Service: Update widget ID : 11
08-04 10:46:37.801  2021  2021 D [Concierge]WidgetView: change position of spinner
08-04 10:46:37.806  1805  7764 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,08-04 10:46:37.828  1039  1766 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7935 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-04 10:46:37.828  1039  1766 I ActivityManager: Killing 7090:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-04 10:46:37.861  1039  2003 W libprocessgroup: failed to open /acct/uid_10046/pid_7090/cgroup.procs: No such file or directory
08-04 10:46:37.866  2021  2021 I [Concierge]WidgetView: initWebView(). Time : 1470300397866
08-04 10:46:37.866  2581  2581 D [Concierge]Service: onStartCommand(). Type : 0
08-04 10:46:37.868  1805  7764 I CheckinService: active receiver: disabled
,08-04 10:46:37.876  2021  2021 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 782422957
08-04 10:46:37.876  2021  2021 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-04 10:46:37.876  2021  2021 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-04 10:46:37.879  2021  2021 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@aa58d80
08-04 10:46:37.879  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-04 10:46:37.880  2021  2021 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-04 10:46:37.880  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-04 10:46:37.884  7935  7935 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-04 10:46:37.884  7935  7935 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-04 10:46:37.885  7935  7935 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-04 10:46:37.885  7935  7935 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-04 10:46:37.885  7935  7935 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-04 10:46:37.886  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-04 10:46:37.886  2021  2021 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-04 10:46:37.888  2021  2021 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-04 10:46:37.888  2021  2021 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-04 10:46:37.889  2021  2021 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1470300269442, New one : 1470300397866
08-04 10:46:37.889  2021  2021 D [Concierge]WidgetView: Unregister all receivers
08-04 10:46:37.889  2021  2021 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-04 10:46:37.889  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-04 10:46:37.891  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-04 10:46:37.892  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-04 10:46:37.893  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-04 10:46:37.894  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-04 10:46:37.895  1039  1875 I ActivityManager: Killing 7110:com.android.chrome/u0a57 (adj 15): empty #17
08-04 10:46:37.895  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-04 10:46:37.897  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-04 10:46:37.897  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-04 10:46:37.937  2021  2021 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-04 10:46:37.944  2021  2021 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-04 10:46:37.944  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-04 10:46:37.945  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-04 10:46:37.949  1039  1055 W libprocessgroup: failed to open /acct/uid_10057/pid_7110/cgroup.procs: No such file or directory
,08-04 10:46:37.965  2021  2021 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3f9cabfa time:155386
,08-04 10:46:37.974  2170  2292 I art     : Explicit concurrent mark sweep GC freed 4941(295KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 611us total 17.308ms
08-04 10:46:37.979  7935  7935 I SystemConfig: BUILD Country: EU
08-04 10:46:37.979  7935  7935 I SystemConfig: BUILD Operator: OPEN
,08-04 10:46:38.016  1039  1766 I ActivityManager: Killing 7132:com.lge.drmservice/u0a62 (adj 15): empty #17
,08-04 10:46:38.073  2021  2021 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-04 10:46:38.107  2021  2959 I GBoardtInterface: onReloaded()
,08-04 10:46:38.108  2021  2021 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
,08-04 10:46:38.110  1039  1929 W libprocessgroup: failed to open /acct/uid_10062/pid_7132/cgroup.procs: No such file or directory
08-04 10:46:38.112  3805  3820 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-04 10:46:38.115  7935  7954 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-04 10:46:38.114  2354  2495 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-04 10:46:38.115  7935  7954 I SystemConfig: existFile = false
08-04 10:46:38.115  7935  7954 I SystemConfig: canReadFile = false
08-04 10:46:38.115  7935  7954 I SystemConfig: systemFeature RCS result false
08-04 10:46:38.115  7935  7954 D SystemConfig: refreshRcsSupport() :false
08-04 10:46:38.116  2354  2495 D ContactsProvider2ForLG: performBackgroundTask SQLiteDiskIOException during query
08-04 10:46:38.116  2354  2495 D ContactsProvider2ForLG: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-04 10:46:38.116  2354  2495 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-04 10:46:38.116  2354  2495 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
08-04 10:46:38.116  2354  2495 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-04 10:46:38.116  2354  2495 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-04 10:46:38.116  2354  2495 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-04 10:46:38.116  2354  2495 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-04 10:46:38.116  2354  2495 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:394)
08-04 10:46:38.116  2354  2495 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:363)
08-04 10:46:38.116  2354  2495 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:974)
08-04 10:46:38.116  2354  2495 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2ForLG.performBackgroundTask(ContactsProvider2ForLG.java:375)
08-04 10:46:38.116  2354  2495 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:748)
08-04 10:46:38.116  2354  2495 D ContactsProvider2ForLG: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 10:46:38.116  2354  2495 D ContactsProvider2ForLG: 	at android.os.Looper.loop(Looper.java:135)
08-04 10:46:38.116  2354  2495 D ContactsProvider2ForLG: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-04 10:46:38.116  2354  7958 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-04 10:46:38.121  2354  7958 E SQLiteLog: (3850) statement aborts at 37: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error

```
