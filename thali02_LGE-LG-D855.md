#### Test 8076137433f931a_thali02_LGE-LG-D855 Logs


```
--------- beginning of system
08-11 17:47:07.745  1036  1624 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6618 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-11 17:47:07.768  1036  1413 D PowerManagerServiceEx: acquireWakeLockInternal: lock=965614699, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
08-11 17:47:07.779  1036  1100 W ProcessCpuTracker: Skipping unknown process pid 6616
--------- beginning of main
08-11 17:47:07.808  2598  2598 D [Concierge]Service: onStartCommand(). Type : 9
08-11 17:47:07.904  1821  4803 I art     : Explicit concurrent mark sweep GC freed 23692(1549KB) AllocSpace objects, 16(256KB) LOS objects, 51% free, 29MB/61MB, paused 1.100ms total 75.151ms
08-11 17:47:07.916  4634  6615 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 256 ms] updated apps [took 256 ms] 
08-11 17:47:08.000  6618  6618 D DocsApplication: Installing DEX configuration.
08-11 17:47:08.017  6618  6618 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
08-11 17:47:08.020  6618  6618 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{3cd2f233 com.google.android.apps.docs}
08-11 17:47:08.035  6618  6618 D TAG     : onCreate()
08-11 17:47:08.051  6618  6618 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,08-11 17:47:08.858  6645  6645 D AndroidRuntime: 
08-11 17:47:08.858  6645  6645 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-11 17:47:08.861  6645  6645 D AndroidRuntime: CheckJNI is OFF
08-11 17:47:08.920  1821  4803 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
08-11 17:47:08.962  6645  6645 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-11 17:47:08.973  1036  1940 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-11 17:47:08.983  1821  4803 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-11 17:47:08.996  1944  2771 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-11 17:47:08.999  1036  1940 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-11 17:47:09.000  1036  1940 D ActivityManager: setTaskToReturnTo : TaskRecord{1d0af699 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-11 17:47:09.000  1036  1940 D ActivityManager: setTaskToReturnTo : TaskRecord{1d0af699 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-11 17:47:09.001  1036  1940 D WindowStateEx: AppWindowTokenEx init.. 
08-11 17:47:09.002   342   358 E GBMv2   : DFP En is all cleared set to be enabled
08-11 17:47:09.038  1036  1940 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6670 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-11 17:47:09.043  6645  6645 D AndroidRuntime: Shutting down VM
08-11 17:47:09.088  1821  4803 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
08-11 17:47:09.104  1944  2771 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-11 17:47:09.104  1944  2771 D SplitWindowPolicy: topRunningActivity=ActivityInfo{39bbf71f co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-11 17:47:09.105  1944  1961 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-11 17:47:09.106  1944  1961 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1b4dda6c co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-11 17:47:09.162  6670  6670 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-11 17:47:09.192  6618  6618 D LgDataFeature: LgDataFeature() Constructor: none
08-11 17:47:09.192  6618  6618 D LgDataFeature: LgDataFeature() Constructor Done, null
08-11 17:47:09.220  6670  6670 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-11 17:47:09.227  6670  6670 I LibraryLoader: Loading: webviewchromium
08-11 17:47:09.229  6670  6670 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 8152-8155)
08-11 17:47:09.229  6670  6670 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-11 17:47:09.243  6670  6670 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8700525}
,08-11 17:47:09.244  6670  6670 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-11 17:47:09.247  6670  6670 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-11 17:47:09.278  6670  6670 I BrowserStartupController: Initializing chromium process, renderers=0
08-11 17:47:09.281  6670  6670 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-11 17:47:09.294  6198  6198 I LockScreenSettings: New app installed broadcast received ..
,08-11 17:47:09.295   322  1384 V AudioPolicyService: registerClient() client 0xb558a2c0, uid 10118
08-11 17:47:09.297  6670  6670 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-11 17:47:09.298  6670  6670 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-11 17:47:09.298  6670  6670 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-11 17:47:09.299  6618  6618 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
08-11 17:47:09.300  1036  1119 D BluetoothManagerService: Message: 20
08-11 17:47:09.300  1036  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2009d37:true
,08-11 17:47:09.301  6198  6198 I LockScreenSettings: Number of installed packages  1
08-11 17:47:09.310  6670  6670 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-11 17:47:09.310  6670  6670 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-11 17:47:09.310  6670  6670 I Adreno-EGL: Build Date: 12/12/14 금
08-11 17:47:09.310  6670  6670 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-11 17:47:09.310  6670  6670 I Adreno-EGL: Remote Branch: 
08-11 17:47:09.310  6670  6670 I Adreno-EGL: Local Patches: 
08-11 17:47:09.310  6670  6670 I Adreno-EGL: Reconstruct Branch: 
,08-11 17:47:09.354  1036  2016 V SIM_STK : Menu title from STK is T-Mobile
,08-11 17:47:09.398  1036  2053 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6716 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-11 17:47:09.429  6670  6708 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-11 17:47:09.432  6670  6670 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-11 17:47:09.450  6670  6670 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-11 17:47:09.454  6670  6670 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-11 17:47:09.457  6670  6670 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-11 17:47:09.460  6670  6670 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-11 17:47:09.460  6670  6670 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-11 17:47:09.472  6716  6716 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-11 17:47:09.472  6716  6716 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,08-11 17:47:09.473  6670  6670 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-11 17:47:09.515  1036  1788 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6737 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-11 17:47:09.516  1036  1788 I ActivityManager: Killing 5872:com.google.android.talk/u0a72 (adj 15): empty #17
08-11 17:47:09.561  1036  1940 W libprocessgroup: failed to open /acct/uid_10072/pid_5872/cgroup.procs: No such file or directory
,08-11 17:47:09.566  6670  6670 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-11 17:47:09.567  6670  6670 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-11 17:47:09.598  1036  1100 W ActivityManager: Activity pause timeout for ActivityRecord{823cd5e u0 com.test.thalitest/.MainActivity t6}
,08-11 17:47:09.618  6670  6761 D OpenGLRenderer: Render dirty regions requested: true
08-11 17:47:09.618  6670  6761 I OpenGLRenderer: Initialized EGL, version 1.4
08-11 17:47:09.622  6737  6737 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
08-11 17:47:09.642  6495  6495 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
,08-11 17:47:09.646  6670  6761 D OpenGLRenderer: Enabling debug mode 0
08-11 17:47:09.647  6737  6737 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-11 17:47:09.654  6670  6670 D Atlas   : Validating map...
,08-11 17:47:09.658  1036  1051 D SplitWindow: check instance of lgWin Window{7f13035 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-11 17:47:09.664  1036  2016 I ActivityManager: Killing 5684:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-11 17:47:09.678  5649  5649 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-11 17:47:09.678  5649  5649 W System.err: android.os.DeadObjectException
08-11 17:47:09.679  5649  5649 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
,08-11 17:47:09.679  5649  5649 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-11 17:47:09.679  5649  5649 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-11 17:47:09.679  5649  5649 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-11 17:47:09.679  5649  5649 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-11 17:47:09.679  5649  5649 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-11 17:47:09.679  5649  5649 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-11 17:47:09.679  5649  5649 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-11 17:47:09.679  5649  5649 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-11 17:47:09.679  5649  5649 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-11 17:47:09.679  5649  5649 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 17:47:09.679  5649  5649 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-11 17:47:09.679  5649  5649 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-11 17:47:09.679  5649  5649 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-11 17:47:09.679  5649  5649 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-11 17:47:09.680  5649  5649 W System.err: android.os.DeadObjectException
08-11 17:47:09.680  5649  5649 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-11 17:47:09.680  5649  5649 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-11 17:47:09.680  5649  5649 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-11 17:47:09.680  5649  5649 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-11 17:47:09.680  5649  5649 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-11 17:47:09.680  5649  5649 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-11 17:47:09.680  5649  5649 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-11 17:47:09.680  5649  5649 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-11 17:47:09.680  5649  5649 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-11 17:47:09.680  5649  5649 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-11 17:47:09.680  5649  5649 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 17:47:09.680  5649  5649 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-11 17:47:09.680  5649  5649 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-11 17:47:09.680  5649  5649 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-11 17:47:09.680  5649  5649 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-11 17:47:09.681  5649  5649 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-11 17:47:09.690  6670  6759 D LgDataFeature: LgDataFeature() Constructor: none
08-11 17:47:09.690  6670  6759 D LgDataFeature: LgDataFeature() Constructor Done, null
08-11 17:47:09.698  4532  6767 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,08-11 17:47:09.826   276   276 E lowmemorykiller: Error opening /proc/5684/oom_score_adj; errno=2
,08-11 17:47:09.831  1036  1981 W ActivityManager: Exception when unbinding service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service
08-11 17:47:09.831  1036  1981 W ActivityManager: android.os.DeadObjectException
08-11 17:47:09.831  1036  1981 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
08-11 17:47:09.831  1036  1981 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:496)
08-11 17:47:09.831  1036  1981 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleUnbindService(ApplicationThreadNative.java:917)
08-11 17:47:09.831  1036  1981 W ActivityManager: 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1776)
08-11 17:47:09.831  1036  1981 W ActivityManager: 	at com.android.server.am.ActiveServices.unbindServiceLocked(ActiveServices.java:901)
08-11 17:47:09.831  1036  1981 W ActivityManager: 	at com.android.server.am.ActivityManagerService.unbindService(ActivityManagerService.java:15417)
08-11 17:47:09.831  1036  1981 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:963)
08-11 17:47:09.831  1036  1981 W ActivityManager: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2560)
08-11 17:47:09.831  1036  1981 W ActivityManager: 	at com.android.server.am.ActivityManagerServiceEx.onTransact(ActivityManagerServiceEx.java:421)
08-11 17:47:09.831  1036  1981 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:446)
08-11 17:47:09.835  1036  1788 W libprocessgroup: failed to open /acct/uid_1000/pid_5684/cgroup.procs: No such file or directory
08-11 17:47:09.836  5649  5649 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-11 17:47:09.837  5649  5649 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-11 17:47:09.844  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=965614699 [*alarm*], flags=0x0
08-11 17:47:09.891  1036  1052 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6774 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-11 17:47:09.898  5649  5649 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-11 17:47:09.923  1036  1120 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +825ms (total +921ms)
08-11 17:47:09.924  1036  1120 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{823cd5e u0 com.test.thalitest/.MainActivity t6} time:108850
,08-11 17:47:09.927  6670  6670 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@11333238 time:108853
08-11 17:47:09.996  6774  6774 D UEI.SmartControl: Quickset Services start...
08-11 17:47:09.998  6774  6774 I UEI.SmartControl: Manufacture = LGE
08-11 17:47:09.998  6774  6774 D UEI.SmartControl: Id = LGNevo
08-11 17:47:09.999  6774  6774 D UEI.SmartControl: File observer start...
08-11 17:47:10.000  6774  6774 E UEI.SmartControl: IR Port is disabled: false
08-11 17:47:10.000  6774  6774 D UEI.SmartControl: Starting file observer...
08-11 17:47:10.000  6774  6774 D UEI.SmartControl: Extracting JNI libs...
08-11 17:47:10.001  6774  6774 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,08-11 17:47:10.033  6670  6670 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-11 17:47:10.033  6670  6670 I chromium: 
,08-11 17:47:10.054  6670  6670 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-11 17:47:10.083  6774  6774 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,08-11 17:47:10.083  6774  6774 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
,08-11 17:47:10.083  6774  6774 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-11 17:47:10.110  6774  6774 I UEI.SmartControl: --- Selecting new region: 6
08-11 17:47:10.112  6774  6774 I UEI.SmartControl: Model = LG-D855
,08-11 17:47:10.113  6774  6774 D UEI.SmartControl: QS Service created
,08-11 17:47:10.124  6774  6774 I UEI.SmartControl: Service initServices...
08-11 17:47:10.127  6774  6774 D UEI.SmartControl: QS start get config
08-11 17:47:10.164  6774  6774 D UEI.SmartControl: Loading JNI Libs...
,08-11 17:47:10.240  6670  6803 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435165696
,08-11 17:47:10.257  6670  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-11 17:47:10.257  6670  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-11 17:47:10.257  6670  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-11 17:47:10.257  6670  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-11 17:47:10.257  6670  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-11 17:47:10.257  6670  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f0be17c added. We now have 1 listener(s)
,08-11 17:47:10.264  1036  1940 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-11 17:47:10.266  6670  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-11 17:47:10.268  6670  6803 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-11 17:47:10.269  6670  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-11 17:47:10.269  6670  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-11 17:47:10.278  6670  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-11 17:47:10.278  6670  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-11 17:47:10.278  6670  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-11 17:47:10.278  6670  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-11 17:47:10.278  6670  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-11 17:47:10.278  6670  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-11 17:47:10.278  6670  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-11 17:47:10.278  6670  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-11 17:47:10.278  6670  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-11 17:47:10.278  6670  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-11 17:47:10.278  6670  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-11 17:47:10.278  6670  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-11 17:47:10.278  6670  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-11 17:47:10.278  6670  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-11 17:47:10.278  6670  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d8da48b added. We now have 1 listener(s)
08-11 17:47:10.279  6670  6803 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 17:47:10.287  1036  1544 D WifiService: New client listening to asynchronous messages
,08-11 17:47:10.289  6670  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-11 17:47:10.289  6670  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-11 17:47:10.290  6670  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-11 17:47:10.290  6670  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-11 17:47:10.290  6670  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-11 17:47:10.292  6670  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 17:47:10.293  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 17:47:10.294  6670  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-11 17:47:10.301  6670  6803 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-11 17:47:10.302  6670  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 17:47:10.302  6670  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:47:10.302  6670  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 17:47:10.302  6670  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:47:10.302  6670  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 17:47:10.302  6670  6803 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 17:47:10.302  6670  6803 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 17:47:10.302  6670  6803 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 17:47:10.302  6670  6803 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-11 17:47:10.302  6670  6803 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-11 17:47:10.303  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:47:10.304  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:47:10.305  6670  6803 I io.jxcore.node.LifeCycleMonitor: start: OK
08-11 17:47:10.329  6670  6759 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-11 17:47:10.329  6670  6759 I chromium: 
,08-11 17:47:10.362  6670  6670 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-11 17:47:10.434  6774  6774 I UEI.SmartControl: Supports setup maps: true
,08-11 17:47:10.437  6774  6774 D UEI.SmartControl: QS start statue = true Error code = 0
08-11 17:47:10.437  6774  6774 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-11 17:47:10.437  6774  6774 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-11 17:47:10.437  6774  6774 I UEI.SmartControl: ### init IR Blaster...
08-11 17:47:10.442  6774  6774 D serial_port: Configuring serial port
08-11 17:47:10.445  6774  6774 E UEI.SmartControl: UEIBLaster setting for 616
08-11 17:47:10.445  6774  6774 I UEI.SmartControl: Setting serial record hearder size = 2
08-11 17:47:10.445  6774  6774 I UEI.SmartControl: configuring settings for MAXQ616
08-11 17:47:10.445  6774  6774 I UEI.SmartControl: Get version...
,08-11 17:47:10.462  6774  6810 D UEI.SmartControl: serial port data available: 21
,08-11 17:47:10.490  6774  6774 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-11 17:47:10.490  6774  6774 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-11 17:47:10.490  6774  6774 I UEI.SmartControl: QS saving settings...
,08-11 17:47:10.491  6774  6774 D UEI.SmartControl: IR Blaster version: 25672567
08-11 17:47:10.512  6774  6810 D UEI.SmartControl: serial port data available: 4
,08-11 17:47:10.556  6774  6813 I UEI.SmartControl: Device manager: loading config....
,08-11 17:47:10.560  6774  6813 D UEI.SmartControl: ----------- loading internal config...
08-11 17:47:10.561  6774  6774 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-11 17:47:10.564  6774  6774 E UEI.SmartControl: Services init done
08-11 17:47:10.564  6774  6774 D UEI.SmartControl: QS Service init finished
08-11 17:47:10.568  6774  6774 D UEI.SmartControl: QS Service version name: 2.1.91
08-11 17:47:10.569  6774  6774 D UEI.SmartControl: QS Service version code: 201091
08-11 17:47:10.569  6774  6774 D UEI.SmartControl: Service requested: Control
08-11 17:47:10.576  6774  6813 E UEI.SmartControl: Loading SETTINGS...
,08-11 17:47:10.581  6774  6813 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-11 17:47:10.583  6774  6774 D UEI.SmartControl: Request IControl service: devices are loaded...
08-11 17:47:10.586  5649  5649 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-11 17:47:10.586  1036  1788 I ActivityManager: Killing 5649:com.lge.qremote/u0a112 (adj 15): empty #17
08-11 17:47:10.586  6774  6791 I UEI.SmartControl: ------ IControl API: 11
08-11 17:47:10.587  6774  6791 I UEI.SmartControl: Registering callback...
08-11 17:47:10.592  6774  6812 I UEI.SmartControl: Notify AllClients services are ready: 0
08-11 17:47:10.592  6774  6812 D UEI.SmartControl: -----service ready thread exits
,08-11 17:47:10.645  1036  1975 W libprocessgroup: failed to open /acct/uid_10112/pid_5649/cgroup.procs: No such file or directory
,08-11 17:47:10.646  6774  6774 D UEI.SmartControl: Internal service binding...
08-11 17:47:10.883   342   360 E GBMv2   : DFP En is all cleared set to be enabled
08-11 17:47:10.884   342   360 E GBMv2   : Set value is all cleared set the max
,08-11 17:47:10.884   342   360 I GBMv2   : DFP Enabled. Ignore VFP set
08-11 17:47:11.166  6670  6809 W jxcore-log: Initializing JXcore engine
08-11 17:47:11.166  6670  6809 W jxcore-log: JXcore engine is ready
,08-11 17:47:11.214  6809  6809 W Thread-762: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[7533]" dev="sockfs" ino=7533 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-11 17:47:11.214  6809  6809 W Thread-762: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-11 17:47:11.214  6809  6809 W Thread-762: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[8517]" dev="sockfs" ino=8517 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-11 17:47:11.214  6809  6809 W Thread-762: type=1400 audit(0.0:169): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
,08-11 17:47:11.214  6809  6809 W Thread-762: type=1400 audit(0.0:170): avc: denied { ioctl } for path="socket:[31593]" dev="sockfs" ino=31593 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-11 17:47:11.234  6670  6809 W jxcore-log: Starting JXcore engine
08-11 17:47:11.304   332   436 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-11 17:47:11.305  3178  6822 I Thermal-Lib: Thermal-Lib-Client: Client request sent
,08-11 17:47:11.308  6670  6809 W jxcore-log: Platform android
08-11 17:47:11.308  6670  6809 W jxcore-log: 
,08-11 17:47:11.308  6670  6809 W jxcore-log: Process ARCH arm
08-11 17:47:11.308  6670  6809 W jxcore-log: 
08-11 17:47:11.517  6670  6809 I jxcore-log: JXcore Cordova bridge is ready!
08-11 17:47:11.517  6670  6809 I jxcore-log: 
08-11 17:47:11.517  6670  6809 W jxcore-log: JXcore engine is started
,08-11 17:47:11.533  6670  6803 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-11 17:47:11.543  6670  6670 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-11 17:47:13.262  6618  6618 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-11 17:47:13.269  1036  1788 I ActivityManager: Killing 6312:com.android.calendar/u0a13 (adj 15): empty #17
08-11 17:47:13.346  1036  1577 W libprocessgroup: failed to open /acct/uid_10013/pid_6312/cgroup.procs: No such file or directory
,08-11 17:47:14.233  6618  6689 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-11 17:47:15.558  6774  6814 D UEI.SmartControl: Internal timer expired: 1
08-11 17:47:15.559  6774  6814 D UEI.SmartControl: unbind internal service
,08-11 17:47:15.561  6774  6774 D UEI.SmartControl: Service.onUnbind: IControl
08-11 17:47:15.565  6774  6774 D UEI.SmartControl: Service.onDestroy
08-11 17:47:15.565  6774  6774 D UEI.SmartControl: Lock is in USE false
08-11 17:47:15.565  6774  6774 D UEI.SmartControl: unbind internal service
08-11 17:47:15.566  6774  6774 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@3d40cea1
08-11 17:47:15.567  6774  6774 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-11 17:47:15.568  6774  6774 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-11 17:47:15.568  6774  6774 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-11 17:47:15.568  6774  6774 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-11 17:47:15.568  6774  6774 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-11 17:47:15.568  6774  6774 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-11 17:47:15.568  6774  6774 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-11 17:47:15.568  6774  6774 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-11 17:47:15.568  6774  6774 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 17:47:15.568  6774  6774 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-11 17:47:15.569  6774  6774 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-11 17:47:15.569  6774  6774 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 17:47:15.569  6774  6774 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-11 17:47:15.569  6774  6774 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-11 17:47:15.569  6774  6774 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-11 17:47:15.569  6774  6774 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@3d40cea1
08-11 17:47:15.574  6774  6774 D serial_port: close(fd = 25)
,08-11 17:47:15.579  6774  6774 I UEI.SmartControl: Serial port is closed.
08-11 17:47:15.579  6774  6774 I UEI.SmartControl: Serial port is closed.
08-11 17:47:15.579  6774  6774 D UEI.SmartControl: Blaster closed
08-11 17:47:15.580  6774  6774 D UEI.SmartControl: Shut down QS...
08-11 17:47:15.580  6774  6774 D UEI.SmartControl: Stopping QS lib
08-11 17:47:15.580  6774  6774 D UEI.SmartControl: QS lib stop result = true
08-11 17:47:15.580  6774  6774 D UEI.SmartControl: Stopped QS lib
08-11 17:47:15.580  6774  6774 D UEI.SmartControl: Stopped file observer...
08-11 17:47:15.580  6774  6774 D UEI.SmartControl: QS shutdown complete
08-11 17:47:16.854  1821  6528 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-11 17:47:16.859   318  6847 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-11 17:47:16.859   318  6847 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-11 17:47:16.860   318  6847 D libc-netbsd: res_queryN name = android.clients.google.com succeed
08-11 17:47:17.055  1821  1821 I ConfigFetchService: fetch service done; releasing wakelock
,08-11 17:47:17.061  1821  1821 I ConfigFetchService: stopping self
08-11 17:47:17.070  2184  2184 I ConfigService: onDestroy
,08-11 17:47:17.535  2158  2158 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19986
,08-11 17:47:22.014  1036  1100 I ActivityManager: Waited long enough for: ServiceRecord{1b82e2b2 u0 com.google.android.gms/.wearable.service.WearableService}
,08-11 17:47:24.387  1036  1413 V AlarmManager: RTC_WAKEUP set : Alarm{3d80b0d2 type 0 when 1470930442533 com.android.vending} when 1470930442533
,08-11 17:47:24.464  1036  1905 V SIM_STK : Menu title from STK is T-Mobile
,08-11 17:47:24.561  6150  6150 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-11 17:47:27.864  6670  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-11 17:47:27.864  6670  6809 I jxcore-log: 
,08-11 17:47:27.868  6670  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-11 17:47:27.868  6670  6809 I jxcore-log: 
08-11 17:47:27.871  6670  6809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 17:47:27.871  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:47:27.871  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 17:47:27.871  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:47:27.871  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 17:47:27.871  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 17:47:27.871  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 17:47:27.871  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 17:47:27.874  6670  6809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 17:47:27.876  6670  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-11 17:47:27.876  6670  6809 I jxcore-log: 
08-11 17:47:27.877  6670  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-11 17:47:27.877  6670  6809 I jxcore-log: 
,08-11 17:47:28.217  6670  6809 I jxcore-log: Running unit tests
08-11 17:47:28.217  6670  6809 I jxcore-log: 
,08-11 17:47:28.218  6670  6809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-11 17:47:28.218  6670  6809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@302d255 added. We now have 2 listener(s)
08-11 17:47:28.219  1036  1577 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 17:47:28.220  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-11 17:47:28.220  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-11 17:47:28.220  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-11 17:47:28.220  6670  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 17:47:28.220  6670  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2707a46a added. We now have 2 listener(s)
08-11 17:47:28.221  6670  6809 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-11 17:47:28.221  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-11 17:47:28.223  6670  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-11 17:47:28.225  6670  6809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 17:47:28.225  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:47:28.225  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 17:47:28.225  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:47:28.225  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 17:47:28.225  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 17:47:28.225  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 17:47:28.225  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 17:47:28.226  6670  6809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 17:47:28.226  6670  6809 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 17:47:28.227  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:47:28.228  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:47:28.228  6670  6809 D ExecuteNativeTests: Running unit tests
08-11 17:47:29.276  1603  1603 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
,08-11 17:47:29.283  1603  1603 I [SystemUI]LGPowerUI: On Skip Timer : true
08-11 17:47:33.394  6670  6809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-11 17:47:33.394  6670  6809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17902128 added. We now have 3 listener(s)
08-11 17:47:33.395  1036  1914 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-11 17:47:33.409  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-11 17:47:33.409  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-11 17:47:33.410  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-11 17:47:33.410  6670  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 17:47:33.410  6670  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f687e41 added. We now have 3 listener(s)
08-11 17:47:33.410  6670  6809 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-11 17:47:33.416  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-11 17:47:33.421  6670  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 17:47:33.424  6670  6809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 17:47:33.424  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:47:33.424  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 17:47:33.424  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:47:33.424  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 17:47:33.424  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 17:47:33.424  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 17:47:33.424  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 17:47:33.428  6670  6809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 17:47:33.428  6670  6809 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 17:47:33.430  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:47:33.432  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:47:33.436  6670  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-11 17:47:33.440  6670  6809 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-11 17:47:33.441  6670  6809 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-11 17:47:33.441  6670  6809 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-11 17:47:33.446  6670  6809 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-11 17:47:33.447  6670  6809 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-11 17:47:33.448  6670  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-11 17:47:33.450  6670  6809 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-11 17:47:33.450  6670  6809 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-11 17:47:33.450  6670  6809 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-11 17:47:33.454  6670  6809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 17:47:33.455  6670  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 17:47:33.455  6670  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 17:47:33.456  6670  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:47:33.457  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:33.457  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 17:47:33.457  6670  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-11 17:47:33.457  6670  6809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17902128 removed from the list
08-11 17:47:33.457  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:47:33.457  6670  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f687e41 removed from the list
08-11 17:47:33.457  6670  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:47:33.457  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:33.458  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:33.458  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:33.459  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:47:33.460  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 17:47:33.460  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:47:33.460  6670  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f687e41 not in the list
08-11 17:47:33.462  6670  6809 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-11 17:47:33.462  6670  6809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 17:47:33.462  6670  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 17:47:33.463  6670  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 17:47:33.463  6670  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:47:33.463  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:33.463  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:33.463  6670  6809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17902128 not in the list
08-11 17:47:33.463  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:47:33.463  6670  6809 E org.thaliproject.p2p.btconnectorl,ib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f687e41 not in the list
08-11 17:47:33.463  6670  6809 D io.jxcore.node.ConnectivityMonitor: stop
,08-11 17:47:33.463  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:33.467  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:33.467  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:33.467  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:33.470  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:47:33.470  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 17:47:33.470  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:47:33.470  6670  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f687e41 not in the list
08-11 17:47:33.477  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-11 17:47:33.477  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-11 17:47:33.477  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-11 17:47:33.477  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-11 17:47:33.477  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-11 17:47:33.478  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-11 17:47:33.478  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-11 17:47:33.478  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-11 17:47:33.478  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-11 17:47:33.478  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-11 17:47:33.478  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-11 17:47:33.478  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-11 17:47:33.478  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-11 17:47:33.478  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-11 17:47:33.478  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-11 17:47:33.478  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-11 17:47:33.478  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-11 17:47:33.478  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-11 17:47:33.478  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-11 17:47:33.478  6670  6809 D io.jxcore.node.ConnectionMode,l: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-11 17:47:33.478  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-11 17:47:33.478  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-11 17:47:33.478  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-11 17:47:33.478  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-11 17:47:33.478  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-11 17:47:33.478  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-11 17:47:33.478  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-11 17:47:33.479  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-11 17:47:33.479  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-11 17:47:33.479  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-11 17:47:33.479  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-11 17:47:33.479  6670  6809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 17:47:33.479  6670  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 17:47:33.479  6670  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 17:47:33.485  6670  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:47:33.485  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:33.485  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:33.486  6670  6809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17902128 not in the list
08-11 17:47:33.486  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:47:33.487  6670  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f687e41 not in the list
08-11 17:47:33.487  6670  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:47:33.487  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:33.487  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:33.487  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:33.487  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:33.488  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:47:33.488  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 17:47:33.488  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:47:33.488  6670  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f687e41 not in the list
08-11 17:47:33.489  6670  6809 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-11 17:47:33.492  6670  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-11 17:47:33.497  6670  6809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 17:47:33.497  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:47:33.497  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 17:47:33.497  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:47:33.497  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 17:47:33.497  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 17:47:33.497  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 17:47:33.497  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 17:47:33.499  6670  6809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 17:47:33.499  6670  6809 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 17:47:33.501  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:47:33.503  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 17:47:33.505  6670  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-11 17:47:33.505  6670  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-11 17:47:33.505  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-11 17:47:33.506  6670  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 17:47:33.506  6670  6809 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-11 17:47:33.510  6670  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-11 17:47:33.511  1036  2053 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 17:47:33.518  6670  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-11 17:47:33.526  6670  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-11 17:47:33.529  6670  6809 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-11 17:47:33.531  6670  6809 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-11 17:47:33.532  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 17:47:33.534  6670  6809 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-11 17:47:33.536  6670  6809 I io.jxcore.node.ConnectionHelper: start: OK
,08-11 17:47:37.531  2158  2158 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,08-11 17:47:37.540  2158  2158 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,08-11 17:47:38.547  6670  6809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 17:47:38.548  6670  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 17:47:38.548  6670  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 17:47:38.555  6670  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:47:38.555  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:38.555  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 17:47:38.556  6670  6809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17902128 not in the list
08-11 17:47:38.556  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:47:38.556  6670  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f687e41 not in the list
08-11 17:47:38.556  6670  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:47:38.557  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 17:47:43.558  6670  6809 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-11 17:47:43.570  6670  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 17:47:43.577  6670  6809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 17:47:43.577  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:47:43.577  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 17:47:43.577  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:47:43.577  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 17:47:43.577  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 17:47:43.577  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 17:47:43.577  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 17:47:43.582  6670  6809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 17:47:43.582  6670  6809 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 17:47:43.584  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:47:43.586  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:47:43.586  6670  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-11 17:47:43.586  6670  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-11 17:47:43.586  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-11 17:47:43.586  6670  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 17:47:43.586  6670  6809 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-11 17:47:43.764  1036  1788 I art     : Explicit concurrent mark sweep GC freed 21096(1113KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 2.804ms total 144.494ms
,08-11 17:47:43.777  6670  6809 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-11 17:47:43.778  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 17:47:43.780  6670  6809 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-11 17:47:43.780  6670  6809 I io.jxcore.node.ConnectionHelper: start: OK
08-11 17:47:43.781  6670  6809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 17:47:43.781  6670  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 17:47:43.781  6670  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 17:47:43.782  6670  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:47:43.782  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:43.782  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 17:47:43.782  6670  6809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17902128 not in the list
08-11 17:47:43.782  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:47:43.782  6670  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f687e41 not in the list
08-11 17:47:43.782  6670  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:47:43.782  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:43.782  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:43.782  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:43.783  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:47:43.783  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 17:47:43.784  6670  6809 D BluetoothLeScanner: could not find callback wrapper
08-11 17:47:43.784  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 17:47:43.784  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:47:43.785  6670  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f687e41 not in the list
08-11 17:47:43.785  6670  6809 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-11 17:47:43.794  6670  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-11 17:47:43.801  6670  6809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 17:47:43.801  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:47:43.801  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 17:47:43.801  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:47:43.801  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 17:47:43.801  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 17:47:43.801  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 17:47:43.801  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 17:47:43.802  6670  6809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 17:47:43.802  6670  6809 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 17:47:43.804  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:47:43.805  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 17:47:43.807  6670  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-11 17:47:43.807  6670  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-11 17:47:43.807  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-11 17:47:43.807  6670  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 17:47:43.807  6670  6809 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-11 17:47:43.811  6670  6809 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-11 17:47:43.811  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 17:47:43.812  6670  6809 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-11 17:47:43.812  6670  6809 I io.jxcore.node.ConnectionHelper: start: OK,
08-11 17:47:48.814  6670  6809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 17:47:48.814  6670  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 17:47:48.815  6670  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 17:47:53.829  6670  6809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-11 17:47:53.831  6670  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-11 17:47:53.831  6670  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 17:47:53.841  6670  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:47:53.841  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:53.841  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 17:47:53.841  6670  6809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17902128 not in the list
08-11 17:47:53.841  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:47:53.842  6670  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f687e41 not in the list
08-11 17:47:53.842  6670  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:47:53.842  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:53.845  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:53.845  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:53.846  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:47:53.846  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 17:47:53.847  6670  6809 D BluetoothLeScanner: could not find callback wrapper
08-11 17:47:53.847  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 17:47:53.847  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:47:53.847  6670  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f687e41 not in the list
08-11 17:47:53.849  6670  6809 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-11 17:47:53.850  6670  6809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 17:47:53.850  6670  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 17:47:53.851  6670  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 17:47:53.853  6670  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:47:53.853  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:53.853  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:53.853  6670  6809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17902128 not in the list
08-11 17:47:53.853  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:47:53.853  6670  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f687e41 not in the list
08-11 17:47:53.853  6670  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:47:53.853  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:53.854  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:53.854  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:53.854  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:53.855  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:47:53.855  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 17:47:53.856  6670  6809 D BluetoothLeScanner: could not find callback wrapper
08-11 17:47:53.856  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 17:47:53.856  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:47:53.856  6670  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f687e41 not in the list
08-11 17:47:53.858  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-11 17:47:53.858  6670  6809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 17:47:53.858  6670  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 17:47:53.858  6670  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 17:47:53.859  6670  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:47:53.859  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:53.859  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:53.859  6670  6809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17902128 not in the list
08-11 17:47:53.859  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:47:53.859  6670  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f687e41 not in the list
08-11 17:47:53.859  6670  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:47:53.859  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.B,luetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:53.859  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:53.859  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:53.859  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:53.860  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:47:53.860  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 17:47:53.863  6670  6809 D BluetoothLeScanner: could not find callback wrapper
08-11 17:47:53.863  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 17:47:53.863  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:47:53.863  6670  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f687e41 not in the list
08-11 17:47:53.864  6670  6809 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-11 17:47:53.864  6670  6809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 17:47:53.864  6670  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 17:47:53.864  6670  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 17:47:53.869  6670  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:47:53.869  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:53.869  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:53.869  6670  6809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17902128 not in the list
08-11 17:47:53.869  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:47:53.870  6670  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f687e41 not in the list
08-11 17:47:53.870  6670  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:47:53.870  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:53.870  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:53.870  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:53.870  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:53.871  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:47:53.871  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 17:47:53.872  6670  6809 D BluetoothLeScanner: could not find callback wrapper
08-11 17:47:53.872  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 17:47:53.872  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:47:53.872  6670  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f687e41 not in the list
08-11 17:47:53.873  6670  6809 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-11 17:47:53.873  6670  6809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 17:47:53.874  6670  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 17:47:53.874  6670  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 17:47:53.875  6670  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:47:53.875  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:53.875  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:53.875  6670  6809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17902128 not in the list
08-11 17:47:53.875  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:47:53.876  6670  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f687e41 not in the list
08-11 17:47:53.876  6670  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:47:53.876  6670  6,809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:53.876  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:53.876  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:53.876  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:53.877  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:47:53.877  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-11 17:47:53.881  6670  6809 D BluetoothLeScanner: could not find callback wrapper
08-11 17:47:53.881  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 17:47:53.881  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:47:53.881  6670  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f687e41 not in the list
08-11 17:47:53.883  6670  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-11 17:47:53.886  6670  6809 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-11 17:47:53.886  6670  6809 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-11 17:47:53.886  6670  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-11 17:47:53.888  6670  6809 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-11 17:47:53.888  6670  6809 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-11 17:47:53.889  6670  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-11 17:47:53.892  6670  6809 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-11 17:47:53.892  6670  6809 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-11 17:47:53.892  6670  6809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 17:47:53.892  6670  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 17:47:53.892  6670  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 17:47:53.893  6670  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:47:53.893  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:53.893  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:53.893  6670  6809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17902128 not in the list
08-11 17:47:53.893  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:47:53.893  6670  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f687e41 not in the list
08-11 17:47:53.893  6670  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:47:53.894  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:53.894  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:53.894  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:53.894  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:53.896  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:47:53.896  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 17:47:53.897  6670  6809 D BluetoothLeScanner: could not find callback wrapper
08-11 17:47:53.897  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 17:47:53.897  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:47:53.897  6670  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f687e41 not in the list
08-11 17:47:53.901  6670  6809 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-11 17:47:53.901  6670  6809 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-11 17:47:53.901  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-11 17:47:53.910  6670  6809 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-11 17:47:53.911  6670  6809 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-11 17:47:53.911  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-11 17:47:53.911  6670  6809 D io.jxcore.node.Connecti,onModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-11 17:47:53.911  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-11 17:47:53.911  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-11 17:47:53.911  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-11 17:47:53.911  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-11 17:47:53.911  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-11 17:47:53.911  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-11 17:47:53.911  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-11 17:47:53.911  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-11 17:47:53.911  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-11 17:47:53.911  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110],
08-11 17:47:53.911  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-11 17:47:53.911  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-11 17:47:53.911  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-11 17:47:53.911  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-11 17:47:53.912  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-11 17:47:53.912  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-11 17:47:53.912  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-11 17:47:53.912  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-11 17:47:53.912  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-11 17:47:53.912  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-11 17:47:53.912  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-11 17:47:53.912  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,08-11 17:47:53.912  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-11 17:47:53.912  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-11 17:47:53.912  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-11 17:47:53.912  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-11 17:47:53.912  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,08-11 17:47:53.912  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-11 17:47:53.912  6670  6809 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-11 17:47:53.912  6670  6809 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-11 17:47:53.912  6670  6809 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-11 17:47:53.913  6670  6809 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-11 17:47:53.913  6670  6809 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-11 17:47:53.913  6670  6809 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-11 17:47:53.913  6670  6809 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-11 17:47:53.913  6670  6809 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-11 17:47:53.913  6670  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-11 17:47:53.925  6670  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-11 17:47:53.927  6670  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-11 17:47:53.927  6670  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-11 17:47:53.928  6670  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-11 17:47:53.928  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-11 17:47:53.928  6670  6809 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-11 17:47:53.928  6670  6809 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-11 17:47:53.928  6670  6809 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-11 17:47:53.929  6670  6809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 17:47:53.929  6670  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 17:47:53.929  6670  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 17:47:53.933  6670  6877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 826)
,08-11 17:47:53.936  6670  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:47:53.936  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:53.936  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:53.936  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-11 17:47:53.937  6670  6809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17902128 not in the list
08-11 17:47:53.937  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:47:53.937  6670  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f687e41 not in the list
08-11 17:47:53.937  6670  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:47:53.937  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:53.937  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:53.937  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:53.937  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:53.938  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:47:53.938  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 17:47:53.939  6670  6809 D BluetoothLeScanner: could not find callback wrapper
08-11 17:47:53.939  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 17:47:53.939  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:47:53.939  6670  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f687e41 not in the list
08-11 17:47:53.940  6670  6809 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-11 17:47:53.940  6670  6809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 17:47:53.941  6670  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 17:47:53.941  6670  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 17:47:53.941  6670  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:47:53.941  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:53.941  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:53.941  6670  6809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17902128 not in the list
08-11 17:47:53.941  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:47:53.941  6670  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f687e41, not in the list
08-11 17:47:53.941  6670  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:47:53.941  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:53.941  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:53.942  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:53.942  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:53.955  6670  6878 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 826
08-11 17:47:53.955  6670  6878 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 826)
08-11 17:47:53.955  6670  6878 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 826)
08-11 17:47:53.961  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:47:53.961  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 17:47:53.962  6670  6809 D BluetoothLeScanner: could not find callback wrapper
08-11 17:47:53.962  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 17:47:53.962  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:47:53.962  6670  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f687e41 not in the list
08-11 17:47:53.963  6670  6809 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-11 17:47:53.965  6670  6809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 17:47:53.965  6670  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 17:47:53.965  6670  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 17:47:53.966  6670  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:47:53.966  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:53.966  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:53.966  6670  6809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17902128 not in the list
08-11 17:47:53.966  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:47:53.966  6670  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f687e41 not in the list
08-11 17:47:53.966  6670  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:47:53.966  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:53.966  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:53.966  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:53.966  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:53.967  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:47:53.967  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-11 17:47:53.970  6670  6809 D BluetoothLeScanner: could not find callback wrapper
,08-11 17:47:53.970  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 17:47:53.970  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:47:53.970  6670  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f687e41 not in the list
08-11 17:47:53.971  6670  6809 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-11 17:47:53.971  6670  6809 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-11 17:47:53.971  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-11 17:47:53.972  6670  6809 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-11 17:47:53.972  6670  6809 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-11 17:47:53.972  6670  6809 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-11 17:47:53.972  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-11 17:47:53.972  6670  6809 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-11 17:47:53.972  6670  6809 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-11 17:47:53.972  6670  6809 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-11 17:47:53.972  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-11 17:47:53.972  6670  6809 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-11 17:47:53.972  6670  6809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 17:47:53.972  6670  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 17:47:53.972  6670  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 17:47:53.974  6670  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:47:53.974  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:53.974  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:53.975  6670  6809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17902128 not in the list
08-11 17:47:53.975  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:47:53.975  6670  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f687e41 not in the list
08-11 17:47:53.975  6670  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:47:53.975  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:53.975  6670 , 6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:53.975  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:53.975  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:53.976  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:47:53.976  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 17:47:53.977  6670  6809 D BluetoothLeScanner: could not find callback wrapper
08-11 17:47:53.977  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 17:47:53.977  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:47:53.977  6670  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f687e41 not in the list
08-11 17:47:53.977  6670  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:47:53.977  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:53.977  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:53.977  6670  6809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17902128 not in the list
08-11 17:47:53.977  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:47:53.977  6670  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f687e41 not in the list
08-11 17:47:53.978  6670  6809 D io.jxcore.node.ConnectivityMonitor: stop
,08-11 17:47:53.978  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:53.978  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:54.052  6670  6877 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
,08-11 17:47:54.056  6670  6877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 826)
08-11 17:47:58.979  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:47:58.979  6670  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f687e41 not in the list
08-11 17:47:58.979  6670  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:47:58.979  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:58.980  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:58.980  6670  6809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17902128 not in the list
08-11 17:47:58.980  6670  6809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-11 17:47:58.988  6670  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 17:47:58.989  6670  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 17:47:58.990  6670  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:47:58.990  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:58.990  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:58.990  6670  6809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17902128 not in the list
08-11 17:47:58.990  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:47:58.991  6670  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f687e41 not in the list
08-11 17:47:58.991  6670  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:47:58.991  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:58.991  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:58.991  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:58.991  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:58.996  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:47:58.996  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-11 17:47:58.998  6670  6809 D BluetoothLeScanner: could not find callback wrapper
08-11 17:47:58.998  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 17:47:58.998  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:47:58.999  6670  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f687e41 not in the list
08-11 17:47:59.003  6670  6809 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-11 17:47:59.003  6670  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 17:47:59.004  6670  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-11 17:47:59.005  6670  6809 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-11 17:47:59.005  6670  6809 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-11 17:47:59.006  6670  6670 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-11 17:47:59.006  6670  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-11 17:47:59.006  6670  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-11 17:47:59.007  6670  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:47:59.008  6670  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-11 17:47:59.008  6670  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-11 17:47:59.008  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-11 17:47:59.008  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:59.008  6670  6809 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-11 17:47:59.010  6670  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-11 17:47:59.010  6670  6895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-11 17:47:59.015  6670  6670 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-11 17:47:59.015  6670  6809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17902128 not in the list
08-11 17:47:59.015  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:47:59.015  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-11 17:47:59.015  6670  6809 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-11 17:47:59.015  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-11 17:47:59.017  6670  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-11 17:47:59.019  6670  6809 D BluetoothLeScanner: could not find callback wrapper
08-11 17:47:59.019  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 17:47:59.019  6670  6809 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-11 17:47:59.019  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:59.019  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:59.020  6670  6809 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-11 17:47:59.021  6670  6670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-11 17:47:59.021  6670  6670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-11 17:47:59.021  6670  6670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-11 17:47:59.021  6670  6670 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-11 17:47:59.022  6670  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f687e41 not in the list
08-11 17:47:59.022  6670  6809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 17:47:59.022  6670  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 17:47:59.022  6670  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 17:47:59.022  6670  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:47:59.022  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:59.022  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:59.022  6670  6809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17902128 not in the list
08-11 17:47:59.022  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:47:59.022  6670  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f687e41 not in the list
08-11 17:47:59.022  6670  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:47:59.023  6670 , 6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:59.023  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:59.023  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:59.023  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 17:47:59.028  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:47:59.028  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 17:47:59.028  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:47:59.028  6670  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f687e41 not in the list
08-11 17:47:59.032  6670  6809 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-11 17:47:59.032  6670  6809 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-11 17:47:59.032  6670  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-11 17:47:59.034  6670  6809 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-11 17:47:59.034  6670  6809 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-11 17:47:59.035  6670  6809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-11 17:47:59.035  6670  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 17:47:59.035  6670  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 17:47:59.038  6670  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:47:59.038  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:59.039  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:59.039  6670  6809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17902128 not in the list
08-11 17:47:59.039  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:47:59.039  6670  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f687e41 not in the list
08-11 17:47:59.039  6670  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:47:59.039  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:59.039  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:59.039  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:59.039  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:59.040  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:47:59.040  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 17:47:59.040  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:47:59.040  6670  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f687e41 not in the list
08-11 17:47:59.044  1036  1788 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 17:47:59.047  1036  1981 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-11 17:47:59.051  1036  2035 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 17:47:59.051  6670  6809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 17:47:59.052  6670  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 17:47:59.052  6670  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 17:47:59.053  6670  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:47:59.053  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:59.053  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:59.053  6670  6809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17902128 not in the list
08-11 17:47:59.053  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:47:59.053  6670  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f687e41 not in the list
08-11 17:47:59.053  6670  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:47:59.053  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:59.053  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:59.053  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:59.053  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:59.054  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:47:59.054  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 17:47:59.054  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:47:59.054  6670  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f687e41 not in the list
08-11 17:47:59.056  6670  6809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 17:47:59.056  6670  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 17:47:59.056  6670  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 17:47:59.056  6670  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:47:59.056  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:59.057  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:59.057  6670  6809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17902128 not in the list
08-11 17:47:59.057  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:47:59.057  6670  6809 E org.,thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f687e41 not in the list
08-11 17:47:59.057  6670  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:47:59.057  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:59.057  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:59.057  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:47:59.057  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:47:59.059  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:47:59.059  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 17:47:59.060  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:47:59.060  6670  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f687e41 not in the list
,08-11 17:47:59.523  6670  6670 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-11 17:48:00.058  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-11 17:48:00.058  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
08-11 17:48:00.058  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-11 17:48:00.059  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,08-11 17:48:00.070  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
08-11 17:48:00.070  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-11 17:48:00.072  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-11 17:48:00.076  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,08-11 17:48:04.065  6670  6809 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,08-11 17:48:04.065  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-11 17:48:04.066  6670  6809 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,08-11 17:48:04.066  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-11 17:48:04.066  6670  6809 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-11 17:48:04.067  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-11 17:48:04.085  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-11 17:48:04.085  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-11 17:48:04.087  6670  6809 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,08-11 17:48:04.087  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-11 17:48:04.087  6670  6809 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-11 17:48:04.087  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-11 17:48:04.087  6670  6809 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-11 17:48:04.087  6670  6809 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,08-11 17:48:04.088  6670  6809 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed,
08-11 17:48:04.088  6670  6809 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-11 17:48:04.089  6670  6809 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-11 17:48:04.089  6670  6809 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-11 17:48:04.089  6670  6809 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,08-11 17:48:04.090  6670  6809 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-11 17:48:09.092  6670  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 17:48:09.092  6670  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2188e5be added. We now have 3 listener(s)
08-11 17:48:09.092  6670  6809 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-11 17:48:09.108  6670  6809 D BluetoothAdapter: enable(): BT is already enabled..!
08-11 17:48:09.111  1036  1905 D WifiServiceImplEx: setWifiEnabled: true pid=6670, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-11 17:48:09.112  1036  1905 D WifiService: setWifiEnabled: true pid=6670, uid=10118
08-11 17:48:09.112  1036  1905 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-11 17:48:09.114  6670  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 17:48:09.114  6670  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2c3de61f added. We now have 4 listener(s)
08-11 17:48:09.114  6670  6809 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 17:48:09.119  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:48:09.119  6670  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2c3de61f removed from the list
08-11 17:48:09.119  6670  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:48:09.119  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:48:09.119  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:48:09.120  6670  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 17:48:09.120  6670  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d729d6c added. We now have 4 listener(s)
08-11 17:48:09.120  6670  6809 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-11 17:48:09.124  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:48:09.124  6670  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d729d6c removed from the list
08-11 17:48:09.124  6670  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:48:09.124  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:48:09.124  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:48:09.125  6670  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 17:48:09.125  6670  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@134c1f35 added. We now have 4 listener(s)
08-11 17:48:09.125  6670  6809 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 17:48:09.129  1036  1905 D WifiServiceImplEx: setWifiEnabled: false pid=6670, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-11 17:48:09.129  1036  1905 D WifiService: setWifiEnabled: false pid=6670, uid=10118
08-11 17:48:09.130  1036  1905 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-11 17:48:09.150  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-11 17:48:09.153  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-11 17:48:09.154  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-11 17:48:09.155  1036  1539 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-11 17:48:09.156  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-11 17:48:09.156  1036  1539 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-11 17:48:09.157  1036  1539 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-11 17:48:09.157  1036  1539 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-11 17:48:09.157  1036  1539 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-11 17:48:09.158  1036  1539 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-11 17:48:09.158  1036  1539 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-11 17:48:09.159  1036  1788 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 17:48:09.159  1036  1788 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3a9a9c0b mBinding = false
08-11 17:48:09.162  1036  1539 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-11 17:48:09.162  1036  1539 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-11 17:48:09.171  1036  1539 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-11 17:48:09.171  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-11 17:48:09.172  2748  2748 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-11 17:48:09.173  1036  1538 D LGWifiP2pService: InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:09.173  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:09.174  1036  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-11 17:48:09.174  1036  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-11 17:48:09.176  1036  1539 D WifiNative-wlan0: SET ps 1: returned true
08-11 17:48:09.176   318   894 D CommandListener: Clearing all IP addresses on wlan0
,08-11 17:48:09.186  1036  2852 D DhcpStateMachine: RunningState{ when=-10ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:09.203  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-11 17:48:09.206  1036  1119 D BluetoothManagerService: Message: 2
08-11 17:48:09.207  1036  1119 D BluetoothManagerService: Sending off request.
08-11 17:48:09.207  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-11 17:48:09.208  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-11 17:48:09.222  6670  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-11 17:48:09.245  1036  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-11 17:48:09.245  1036  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,08-11 17:48:09.251  1036  1036 D WifiHS20: hidePasspointNotification off =false
,08-11 17:48:09.289  6670  6809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 17:48:09.289  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:48:09.289  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 17:48:09.289  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:48:09.289  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 17:48:09.289  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 17:48:09.289  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 17:48:09.289  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 17:48:09.295  3949  3969 D LGBluetoothServiceAdapter: [BTUI] Precleanup
,08-11 17:48:09.297  1944  1944 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-11 17:48:09.298  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-11 17:48:09.298  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-11 17:48:09.301  1036  1624 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-11 17:48:09.301  1036  2851 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:09.301  1036  2851 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:09.301  1036  2851 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-11 17:48:09.302  1036  2851 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:09.302  1036  2851 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
08-11 17:48:09.307  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 17:48:09.307  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 17:48:09.307  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-11 17:48:09.308  3949  4027 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-11 17:48:09.308  3949  4027 D BluetoothAdapterProperties: Setting state to 13
08-11 17:48:09.308  3949  4027 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-11 17:48:09.309  3949  4027 D BluetoothAdapterProperties: onBluetoothDisable()
08-11 17:48:09.309  3949  4027 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-11 17:48:09.317  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:48:09.317  6670  6809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-11 17:48:09.317  6670  6809 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-11 17:48:09.320  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-11 17:48:09.323  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 17:48:09.323  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 17:48:09.323  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-11 17:48:09.323  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
08-11 17:48:09.323  1036  1036 D RttService: SCAN_AVAILABLE : 1
08-11 17:48:09.323  1036  1558 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:09.324  1036  1557 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:09.324  1036  1538 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:09.324  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:09.324  1036  1538 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@18baba4b
08-11 17:48:09.325  1036  1538 D LGWifiP2pService: P2pDisablingState
08-11 17:48:09.325  1036  1538 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:09.325  1036  1538 D LGWifiP2pService: p2p socket connection lost
08-11 17:48:09.325  1036  1538 D LGWifiP2pService: P2pDisabledState
08-11 17:48:09.327  1036  1545 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-11 17:48:09.327  1036  1545 D DSQN    : disableDataServiceNotify
08-11 17:48:09.327  1036  1545 D DSQN    : stop dsqn bin
08-11 17:48:09.327   318  6921 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-11 17:48:09.327  1036  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-11 17:48:09.328  1036  2851 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-11 17:48:09.328  6495  6495 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-11 17:48:09.329  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-11 17:48:09.329  1944  1944 D WfdsService: WifiP2pState is changed : false
08-11 17:48:09.329  1944  2276 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
,08-11 17:48:09.329  1944  2276 D WfdsService: Set the WFDS Monitor: false
08-11 17:48:09.330  1944  2276 D WfdsMonitor: WFDS Monitor is stopped
08-11 17:48:09.330  1944  2276 D WfdsService: STATE : WfdsDisabledState - enter
08-11 17:48:09.330  1944  2784 D CtrlSupplicant: Received on exit socket, terminate
08-11 17:48:09.330  1944  2784 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-11 17:48:09.330  1944  2784 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-11 17:48:09.330  1944  2784 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-11 17:48:09.330  1944  2277 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-11 17:48:09.331  1944  2276 W WfdsService: DefaultState - msg [9445378] is not handled
08-11 17:48:09.334  1036  1119 D BluetoothManagerService: Message: 60
08-11 17:48:09.334  1036  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-11 17:48:09.334  1036  1119 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-11 17:48:09.335  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 17:48:09.335  1036  1545 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-11 17:48:09.335  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-11 17:48:09.335  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-11 17:48:09.335  1036  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-11 17:48:09.336  1036  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-11 17:48:09.336  1036  1545 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-11 17:48:09.336  1036  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-11 17:48:09.336  1036  2851 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:09.336  1036  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-11 17:48:09.336  1036  2851 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:09.336  1036  2851 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-11 17:48:09.337  1036  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-11 17:48:09.337  6670  6670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:48:09.337  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:48:09.337  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:48:09.337  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 17:48:09.337  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:48:09.337  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 17:48:09.337  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 17:48:09.337  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 17:48:09.337  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 17:48:09.337  1036  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-11 17:48:09.337  1036  1545 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasIntern,etCapability=true
08-11 17:48:09.337  1036  1539 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-11 17:48:09.338  1036  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-11 17:48:09.338  6670  6670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:48:09.338  1036  1545 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-11 17:48:09.338  1036  1538 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:09.338  6670  6670 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-11 17:48:09.338  1036  1538 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:09.338  1036  1545 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-11 17:48:09.338  1036  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-11 17:48:09.338  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-11 17:48:09.338  2748  2748 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-11 17:48:09.339  1603  2081 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-11 17:48:09.339  1036  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
,08-11 17:48:09.339  1036  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-11 17:48:09.339  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-11 17:48:09.339  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-11 17:48:09.340  1036  1539 D WifiNative-wlan0: SET ps 1: returned true
08-11 17:48:09.340   318   894 D CommandListener: Clearing all IP addresses on wlan0
08-11 17:48:09.340  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-11 17:48:09.378  1036  1947 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6922 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-11 17:48:09.381  3949  4031 D BluetoothAdapterProperties: Scan Mode:20
,08-11 17:48:09.381  3949  4027 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-11 17:48:09.382  1036  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-11 17:48:09.382  3949  4027 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-11 17:48:09.382  1036  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-11 17:48:09.382  1036  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-11 17:48:09.382  1036  1545 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-11 17:48:09.383  3949  4258 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-11 17:48:09.383  1036  1545 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-11 17:48:09.384  3949  4257 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-11 17:48:09.384  3949  4257 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-11 17:48:09.384  3949  4257 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-11 17:48:09.384  3949  4257 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-11 17:48:09.384  3949  4257 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-11 17:48:09.384  3949  4257 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-11 17:48:09.384  3949  4257 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-11 17:48:09.384  3949  4257 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-11 17:48:09.384  3949  4148 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-11 17:48:09.384  3949  4148 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-11 17:48:09.385  3949  4301 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-11 17:48:09.385  3949  4292 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-11 17:48:09.386  3949  4293 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-11 17:48:09.389  3949  4148 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-11 17:48:09.389  3949  4148 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-11 17:48:09.389  3949  4148 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-11 17:48:09.389  3949  4148 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-11 17:48:09.389  3949  4148 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-11 17:48:09.389  3949  4148 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-11 17:48:09.389  3949  4148 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-11 17:48:09.389  3949  4148 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-11 17:48:09.389  3949  4148 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-11 17:48:09.389  3949  4148 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-11 17:48:09.389  3949  4148 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-11 17:48:09.389  3949  4148 E bt-btif : bta_gattc_deregister Deregister F,ailedm unknown client cif
08-11 17:48:09.390  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:48:09.390  1036  1539 D WifiNative-p2p0: doBoolean: TERMINATE
08-11 17:48:09.392  1856  1856 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-11 17:48:09.392  1856  1856 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-11 17:48:09.393  1036  1539 D WifiNative-p2p0: TERMINATE: returned true
08-11 17:48:09.394  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-11 17:48:09.394  3949  3949 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-11 17:48:09.394  3949  3949 D BluetoothMapService: STATE_TURNING_OFF
08-11 17:48:09.394  3949  3949 V BluetoothMapService: Handler(): got msg=4
08-11 17:48:09.394  3949  3949 D BluetoothMapService: MAP Service closeService in
08-11 17:48:09.394  3949  3949 D BluetoothMapMasInstance: MAP Service shutdown
08-11 17:48:09.395  3949  3949 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-11 17:48:09.395  3949  3949 V BluetoothMapService: MAP Service closeService out
08-11 17:48:09.395  1944  1944 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-11 17:48:09.396  1036  1545 D NetworkManagementService: Removing idletimer
08-11 17:48:09.396  1036  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-11 17:48:09.396  1036  1539 E WifiStateMachine: useWiFiOffloading() : false
08-11 17:48:09.396  1036  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-11 17:48:09.398  3949  3949 V BtOppService: Receiver DISABLED_ACTION 
08-11 17:48:09.398  3949  3949 I BtOppRfcommListener: stopping Accept Thread
08-11 17:48:09.398  3949  3949 V BtOppRfcommListener: close mBtServerSocket
08-11 17:48:09.398  3949  3949 V BtOppRfcommListener: waiting for thread to terminate
08-11 17:48:09.399  3949  4292 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-11 17:48:09.399  1036  1545 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 17:48:09.400  3949  3949 V BtOppRfcommListener: done waiting for thread to terminate
08-11 17:48:09.402  1036  1545 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-11 17:48:09.436  1036  1100 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6940 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-11 17:48:09.438  1036  1537 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-11 17:48:09.438  1036  1537 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-11 17:48:09.438  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-11 17:48:09.438  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
,08-11 17:48:09.439  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-11 17:48:09.439  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 17:48:09.439  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 17:48:09.439  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-11 17:48:09.439  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-11 17:48:09.439  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-11 17:48:09.439  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-11 17:48:09.439  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-11 17:48:09.439  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-11 17:48:09.439  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-11 17:48:09.442  3949  3949 V BtOppService: onDestroy
08-11 17:48:09.444  1036  1539 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-11 17:48:09.444  1036  1539 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-11 17:48:09.457  6670  6670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:48:09.457  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:48:09.457  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:48:09.457  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 17:48:09.457  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 17:48:09.457  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 17:48:09.457  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 17:48:09.457  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 17:48:09.457  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 17:48:09.458  6670  6670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:48:09.458  6670  6670 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 17:48:09.459  3949  3949 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-11 17:48:09.459  6670  6670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:48:09.459  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:48:09.459  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:48:09.459  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 17:48:09.459  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 17:48:09.459  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 17:48:09.459  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 17:48:09.459  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 17:48:09.459  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 17:48:09.460  6670  6670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:48:09.460  6670  6670 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 17:48:09.460  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-11 17:48:09.461  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-11 17:48:09.462  6670  6670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:48:09.462  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:48:09.462  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:48:09.462  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 17:48:09.462  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 17:48:09.462  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetoot,h enabled: false
08-11 17:48:09.462  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 17:48:09.462  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 17:48:09.462  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 17:48:09.462  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-11 17:48:09.462  6670  6670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:48:09.462  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-11 17:48:09.462  6670  6670 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 17:48:09.464  6670  6670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:48:09.464  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:48:09.464  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:48:09.464  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 17:48:09.464  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 17:48:09.464  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 17:48:09.464  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 17:48:09.464  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 17:48:09.464  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 17:48:09.466  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:48:09.467  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 17:48:09.467  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:48:09.469  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:48:09.470  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:48:09.473  1036  2852 D DhcpStateMachine: StoppedState
08-11 17:48:09.474  1036  2852 D DhcpStateMachine: StoppedState{ when=-133ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:09.475  1036  1539 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-11 17:48:09.475  1036  1539 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-11 17:48:09.485  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-11 17:48:09.485  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 17:48:09.486  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 17:48:09.490  6940  6940 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-11 17:48:09.490  6940  6940 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-11 17:48:09.490  6940  6940 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-11 17:48:09.490  6940  6940 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-11 17:48:09.491  6940  6940 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-11 17:48:09.492  6940  6940 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-11 17:48:09.496  2748  2748 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-11 17:48:09.496  2748  2748 I wpa_supplicant: monitor socket send errors count : 1
08-11 17:48:09.496  2748  2748 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1944-2\x00 that cannot receive messages
08-11 17:48:09.498  1036  2779 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-11 17:48:09.498  1036  2779 D WifiMonitor: Dropping event because (p2p0) is stopped
08-11 17:48:09.501  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-11 17:48:09.502  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 17:48:09.502  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 17:48:09.502  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-11 17:48:09.503  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-11 17:48:09.503  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 17:48:09.520  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-11 17:48:09.529  6922  6922 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-11 17:48:09.531  6922  6922 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-11 17:48:09.532  6922  6922 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-11 17:48:09.534  1036  1947 I ActivityManager: Killing 6283:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-11 17:48:09.535  2748  2748 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-11 17:48:09.535  1036  2779 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-11 17:48:09.535  1036  2779 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-11 17:48:09.535  1036  2779 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-11 17:48:09.535  1036  2779 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
,08-11 17:48:09.536  2748  2748 W wpa_supplicant: USIM:  scard_deinit function
08-11 17:48:09.536  1036  1539 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=168448
08-11 17:48:09.537  1036  1119 D Tethering: InitialState.processMessage what=4
08-11 17:48:09.538  1036  2779 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-11 17:48:09.538  1036  2779 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-11 17:48:09.539  1036  1539 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=168451
08-11 17:48:09.539  1036  1539 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=168451  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-11 17:48:09.539  1036  1539 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=168452  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-11 17:48:09.566  1036  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-11 17:48:09.566  1036  1914 W libprocessgroup: failed to open /acct/uid_10014/pid_6283/cgroup.procs: No such file or directory
,08-11 17:48:09.568  1036  1539 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
,08-11 17:48:09.569  1036  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-11 17:48:09.574  2748  2748 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-11 17:48:09.574  1036  2779 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-11 17:48:09.574  1036  2779 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-11 17:48:09.575  1036  2779 D WifiMonitor: Disconnecting from the supplicant, no more events
08-11 17:48:09.575  1036  1539 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-11 17:48:09.641  6940  6940 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-11 17:48:09.651  3949  3949 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-11 17:48:09.651  3949  3949 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-11 17:48:09.651  3949  3949 V BluetoothPbapReceiver: ***********state = 13
08-11 17:48:09.653  3949  3949 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-11 17:48:09.654  3949  3949 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-11 17:48:09.654  3949  3949 V BluetoothPbapService: state: 13
08-11 17:48:09.654  3949  3949 V BluetoothPbapService: Pbap Service closeService in
08-11 17:48:09.657  2184  2184 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-11 17:48:09.659  3949  3949 V BluetoothPbapService: successfully stopped pbap service
08-11 17:48:09.659  3949  3949 V BluetoothPbapService: Pbap Service closeService out
08-11 17:48:09.659  3949  3949 V BluetoothPbapService: Pbap Service onDestroy
08-11 17:48:09.659  3949  3949 V BluetoothPbapService: Pbap Service closeService in
08-11 17:48:09.659  3949  3949 V BluetoothPbapService: Pbap Service closeService out
08-11 17:48:09.659  3949  3949 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-11 17:48:09.662  6940  6940 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-11 17:48:09.706  6940  6940 D LgDataFeature: LgDataFeature() Constructor: none
08-11 17:48:09.706  6940  6940 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-11 17:48:09.717  6940  6940 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-11 17:48:09.724  1036  1052 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6962 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-11 17:48:09.725  1036  1119 D BluetoothManagerService: Message: 20
08-11 17:48:09.725  1036  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3b910032:true
08-11 17:48:09.728  1036  1539 D WifiOffDelayIfNotUsed: stopMonitoring
08-11 17:48:09.728  1036  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-11 17:48:09.728  1036  1539 E WifiStateMachine: useWiFiOffloading() : false
08-11 17:48:09.728  1036  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-11 17:48:09.734  1944  1944 D WfdsService: Supplicant Connection state is changed : false
08-11 17:48:09.734  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-11 17:48:09.734  1944  2276 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-11 17:48:09.734  1944  2276 D WfdsService: Set the WFDS Monitor: false
08-11 17:48:09.734  1944  2276 D WfdsMonitor: WFDS Monitor is stopped
08-11 17:48:09.735  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 17:48:09.737  2477  2477 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-11 17:48:09.741   346   346 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 417us total 22.178ms
08-11 17:48:09.742  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-11 17:48:09.743  1036  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-11 17:48:09.743  1036  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-11 17:48:09.745  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:48:09.747  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:48:09.749  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 17:48:09.759   346   346 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 362us total 17.715ms
,08-11 17:48:09.774   346   346 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 290us total 14.319ms
,08-11 17:48:09.777  1036  1119 D BluetoothManagerService: Message: 30
08-11 17:48:09.781  1036  1119 D BluetoothManagerService: Message: 30
08-11 17:48:09.783  6940  6940 D LocalBluetoothProfileManager: Adding local MAP profile
08-11 17:48:09.784  6940  6940 D BluetoothMap: Create BluetoothMap proxy object
08-11 17:48:09.785  1036  1119 D BluetoothManagerService: Message: 30
08-11 17:48:09.788  1036  1119 D BluetoothManagerService: Message: 30
,08-11 17:48:09.792  6940  6940 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-11 17:48:09.793  6940  6940 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-11 17:48:09.805  6940  6940 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-11 17:48:09.806  6962  6962 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-11 17:48:09.806  6962  6962 W LG Account v2.2: No ProfileInfo entries
08-11 17:48:09.806  6962  6962 I LG Account v2.2: isEnabled: false
08-11 17:48:09.806  6962  6962 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-11 17:48:09.806  6962  6962 I Feature : [Lifetracker]Country: EU
08-11 17:48:09.806  6962  6962 I Feature : [Lifetracker]Operator: OPEN
08-11 17:48:09.806  6962  6962 I Feature : [Lifetracker]Ranking support: false
08-11 17:48:09.806  6962  6962 I Feature : [Lifetracker]Comfort support: false
08-11 17:48:09.806  6962  6962 I Feature : [Lifetracker]Accessory: true
08-11 17:48:09.807  6962  6962 I Feature : [Lifetracker]Health device: true
08-11 17:48:09.807  6962  6962 I Feature : [Lifetracker]Extra Pedometer: false
08-11 17:48:09.807  6962  6962 I Feature : [Lifetracker]Blood glucose device: false
08-11 17:48:09.807  6962  6962 I Feature : [Lifetracker]Device Number: 3
08-11 17:48:09.807  6940  6940 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-11 17:48:09.810  1036  2016 I ActivityManager: Killing 6428:com.android.defcontainer/u0a4 (adj 15): empty #17
08-11 17:48:09.836  6940  6940 D DockEventReceiver: finishStartingService: stopping service
08-11 17:48:09.836  1036  1577 W libprocessgroup: failed to open /acct/uid_10004/pid_6428/cgroup.procs: No such file or directory
,08-11 17:48:09.848  6940  6940 D BluetoothInputDevice: Proxy object connected
,08-11 17:48:09.849  6940  6940 D HidProfile: Bluetooth service connected
08-11 17:48:09.850  6940  6940 D BluetoothPan: BluetoothPAN Proxy object connected
08-11 17:48:09.851  6940  6940 D PanProfile: Bluetooth service connected
08-11 17:48:09.852  6940  6940 D BluetoothMap: Proxy object connected
08-11 17:48:09.852  6940  6940 D MapProfile: Bluetooth service connected
08-11 17:48:09.853  6940  6940 D BluetoothMap: getConnectedDevices()
08-11 17:48:09.853  6940  6940 D BluetoothMap: Bluetooth is Not enabled
08-11 17:48:09.854  6940  6940 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-11 17:48:09.856  6940  6940 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-11 17:48:09.860  6940  6940 D BluetoothPermissionRequest: onReceive
,08-11 17:48:09.863  6940  6940 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-11 17:48:09.872  1036  1051 I ActivityManager: Killing 6532:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,08-11 17:48:09.877  6940  6940 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-11 17:48:09.906  3949  3949 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-11 17:48:09.906  3949  3949 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-11 17:48:09.907  3949  3949 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-11 17:48:09.907  1036  1975 W libprocessgroup: failed to open /acct/uid_10008/pid_6532/cgroup.procs: No such file or directory
08-11 17:48:09.978  1036  1051 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6989 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-11 17:48:09.983  3949  3949 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-11 17:48:09.983  3949  3949 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-11 17:48:09.985  3949  3949 V BluetoothFtpService: Ftp Service onStartCommand
08-11 17:48:09.985  3949  3949 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-11 17:48:09.985  3949  3949 V BluetoothFtpService: Ftp Service closeService
08-11 17:48:09.986  3949  3949 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-11 17:48:09.987  3949  3949 V BluetoothFtpService: successfully stopped ftp service
08-11 17:48:09.988  3949  3949 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-11 17:48:09.988  3949  3949 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-11 17:48:09.988  3949  3949 V BluetoothSapReceiver: SapReceiver onReceive 
08-11 17:48:09.988  3949  3949 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-11 17:48:09.988  3949  3949 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-11 17:48:09.988  3949  3949 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-11 17:48:09.990  3949  3949 V BluetoothFtpService: Ftp Service onDestroy
08-11 17:48:09.990  3949  3949 V BluetoothFtpService: Ftp Service closeService
08-11 17:48:10.043  1036  1052 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7006 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-11 17:48:10.050  3949  3949 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-11 17:48:10.050  3949  3949 V BluetoothSapService: state: 13
08-11 17:48:10.050  3949  3949 V BluetoothSapService: Stopping SAP server process
08-11 17:48:10.051  3949  3949 V BluetoothSapService: Sap Service closeSapService in
08-11 17:48:10.051  3949  3949 V BluetoothSapService: Close listen Socket : 
08-11 17:48:10.051  3949  3949 V BluetoothSapService: Close rfcomm Socket : 
08-11 17:48:10.051  3949  3949 V BluetoothSapService: Close sapd  Socket : 
08-11 17:48:10.052  3949  3949 V BluetoothSapService: Sap Service closeSapService out
08-11 17:48:10.053  3949  3949 V BluetoothSapService: Sap Service onDestroy
08-11 17:48:10.053  3949  3949 V BluetoothSapService: Sap Service closeSapService in
08-11 17:48:10.053  3949  3949 V BluetoothSapService: Close listen Socket : 
08-11 17:48:10.053  3949  3949 V BluetoothSapService: Close rfcomm Socket : 
08-11 17:48:10.053  3949  3949 V BluetoothSapService: Close sapd  Socket : 
08-11 17:48:10.053  3949  3949 V BluetoothSapService: Sap Service closeSapService out
08-11 17:48:10.085  6989  6989 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-11 17:48:10.128  6989  6989 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-11 17:48:10.131  7006  7006 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-11 17:48:10.150  1036  1051 I ActivityManager: Killing 6067:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-11 17:48:10.165  6989  6989 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-11 17:48:10.165  6989  6989 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-11 17:48:10.166  6989  6989 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-11 17:48:10.166  6989  6989 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-11 17:48:10.166  6989  6989 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-11 17:48:10.168  6989  6989 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-11 17:48:10.173  6989  6989 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-11 17:48:10.209  1036  2035 W libprocessgroup: failed to open /acct/uid_10011/pid_6067/cgroup.procs: No such file or directory
,08-11 17:48:10.220  6989  6989 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-11 17:48:10.224  6989  6989 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-11 17:48:10.246  6989  6989 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-11 17:48:10.251  6495  6495 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-11 17:48:10.254  6922  6922 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-11 17:48:10.255  6922  6922 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-11 17:48:10.255  6922  6922 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-11 17:48:10.255  6989  6989 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-11 17:48:10.262  6989  6989 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-11 17:48:10.262  6940  6940 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-11 17:48:10.273  6940  6940 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-11 17:48:10.290  6989  6989 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-11 17:48:10.291  6989  6989 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-11 17:48:10.295  6989  6989 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-11 17:48:10.310  6495  6495 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-11 17:48:10.326  6922  6922 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-11 17:48:10.326  6922  6922 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-11 17:48:10.326  6922  6922 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-11 17:48:10.336  6940  6940 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-11 17:48:10.352  6940  6940 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-11 17:48:10.364  6989  6989 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-11 17:48:10.366  6989  6989 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-11 17:48:10.369  6989  6989 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-11 17:48:10.396  3949  4031 D bt_hci_bdroid: cleanup
08-11 17:48:10.396  3949  4150 I bt_lpm  : LPM is already off!!!
,08-11 17:48:10.396  3949  4241 I bt_userial_mct: exiting userial_read_thread
08-11 17:48:10.396  3949  4241 D bt_userial_mct: Leaving userial_evt_read_thread()
08-11 17:48:10.397  3949  4148 W bt-btif : ag scb idx 1 not allocated
08-11 17:48:10.397  3949  4148 E bt-btif : BTA AG is already disabled, ignoring ...
08-11 17:48:10.397  3949  4148 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-11 17:48:10.397  3949  4148 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-11 17:48:10.397  3949  4148 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-11 17:48:10.397  3949  4148 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-11 17:48:10.398  3949  4148 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-11 17:48:10.398  3949  4148 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-11 17:48:10.398  3949  4148 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-11 17:48:10.398  3949  4148 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-11 17:48:10.398  3949  4148 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-11 17:48:10.398  3949  4148 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-11 17:48:10.398  3949  4148 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-11 17:48:10.398  3949  4148 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-11 17:48:10.398  3949  4148 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-11 17:48:10.398  3949  4148 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-11 17:48:10.398  3949  4148 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-11 17:48:10.398  3949  4148 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-11 17:48:10.398  3949  4148 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-11 17:48:10.398  3949  4148 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-11 17:48:10.398  3949  4148 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-11 17:48:10.399  3949  4031 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-11 17:48:10.399  3949  4150 I bt_vendor: hw_epilog_process
08-11 17:48:10.400  3949  4031 D bt_hci_bdroid: cleanup Finalizing cleanup
08-11 17:48:10.400  3949  4031 D bt_userial_mct: userial_close
08-11 17:48:10.400  3949  4031 E bt_userial_mct: pthread_join() FAILED result:3
08-11 17:48:10.400  3949  4031 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-11 17:48:10.451  1036  1975 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7030 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-11 17:48:10.514  3949  4031 D bt_hci_bdroid: set_power 0
08-11 17:48:10.514  3949  4031 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-11 17:48:10.514  3949  4031 I bt_vendor: bluetooth satus is on
08-11 17:48:10.515  3949  4031 I bt_vendor: bt-vendor : resetting BT status
08-11 17:48:10.515  3949  4031 I bt_vendor: Starting hciattach daemon
08-11 17:48:10.515  3949  4031 I bt_vendor: try to set false
08-11 17:48:10.516  3949  4031 I bt_vendor: Starting hciattach daemon
08-11 17:48:10.516  3949  4031 I bt_vendor: try to set false
08-11 17:48:10.518  3949  4031 I bt_vendor: cleanup
08-11 17:48:10.519  3949  4148 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-11 17:48:10.520  3949  4031 I GKI_LINUX: GKI_exit_task 0 done
08-11 17:48:10.520  3949  4031 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-11 17:48:10.522  3949  4027 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-11 17:48:10.524  3949  3949 D HeadsetService: Received stop request...Stopping profile...
,08-11 17:48:10.528  3949  3949 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-11 17:48:10.528  3949  3949 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-11 17:48:10.528  3949  3949 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18e1a6fa
08-11 17:48:10.528  3949  4052 D HeadsetStateMachine: Exit Disconnected: -1
08-11 17:48:10.528  1036  1036 D BluetoothHeadset: Proxy object disconnected
08-11 17:48:10.529  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-11 17:48:10.530  1856  1856 D BluetoothHeadset: Proxy object disconnected
08-11 17:48:10.530  1856  1856 D BluetoothHeadset: Proxy object disconnected
08-11 17:48:10.530  1856  1856 D BluetoothHeadset: Proxy object disconnected
08-11 17:48:10.531  3949  3949 D A2dpService: Received stop request...Stopping profile...
08-11 17:48:10.532  3949  4102 D A2dpStateMachine: Exit Disconnected: -1
08-11 17:48:10.532  3949  3949 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-11 17:48:10.535  3949  3949 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-11 17:48:10.535  3949  4027 D BluetoothAdapterState: Stopping profile services that were post enabled
08-11 17:48:10.535  3949  3949 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-11 17:48:10.535  3949  3949 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18e1a6fa
08-11 17:48:10.537  3949  3949 D HeadsetStateMachine: Unbinding service...
,08-11 17:48:10.537  3949  3949 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-11 17:48:10.538  3949  3949 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-11 17:48:10.538  3949  3949 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-11 17:48:10.538  3949  3949 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-11 17:48:10.538  3949  3949 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-11 17:48:10.538  3949  3949 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-11 17:48:10.538  3949  3949 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-11 17:48:10.539  1036  1036 D BluetoothA2dp: Proxy object disconnected
08-11 17:48:10.539  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-11 17:48:10.539  3949  3949 D HidService: Received stop request...Stopping profile...
08-11 17:48:10.539  3949  3949 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18e1a6fa
08-11 17:48:10.540  6940  6940 D BluetoothInputDevice: Proxy object disconnected
08-11 17:48:10.540  3949  3949 D HealthService: Received stop request...Stopping profile...
,08-11 17:48:10.540  6940  6940 D HidProfile: Bluetooth service disconnected
08-11 17:48:10.541  3949  3949 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18e1a6fa
08-11 17:48:10.542  3949  3949 D PanService: Received stop request...Stopping profile...
08-11 17:48:10.543  3949  3949 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18e1a6fa
08-11 17:48:10.544  3949  3949 D BtGatt.DebugUtils: handleDebugAction() action=null
08-11 17:48:10.545  3949  3949 D BtGatt.GattService: Received stop request...Stopping profile...
08-11 17:48:10.545  3949  3949 D BtGatt.GattService: stop()
08-11 17:48:10.545  3949  3949 D BtGatt.AdvertiseManager: advertise clients cleared
08-11 17:48:10.546  3949  3949 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18e1a6fa
08-11 17:48:10.547  6940  6940 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-11 17:48:10.547  6940  6940 D PanProfile: Bluetooth service disconnected
08-11 17:48:10.547  3949  3949 D BluetoothMapService: Received stop request...Stopping profile...
08-11 17:48:10.547  3949  3949 D BluetoothMapService: stop()
08-11 17:48:10.547  3949  3949 D BluetoothMapEmailAppObserver: deinitObservers()
08-11 17:48:10.548  3949  3949 D BluetoothMapEmailAppObserver: removeReceiver()
08-11 17:48:10.548  3949  3949 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18e1a6fa
,08-11 17:48:10.551  6940  6940 D BluetoothMap: Proxy object disconnected
08-11 17:48:10.551  6940  6940 D MapProfile: Bluetooth service disconnected
08-11 17:48:10.551  3949  3949 I BluetoothA2dpServiceJni: cleanupNative
08-11 17:48:10.552  3949  4103 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-11 17:48:10.552  3949  3949 I GKI_LINUX: GKI_exit_task 2 done
08-11 17:48:10.552  3949  3949 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-11 17:48:10.552  3949  3949 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-11 17:48:10.552  3949  3949 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-11 17:48:10.553  3949  3949 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-11 17:48:10.553  3949  3949 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-11 17:48:10.553  3949  3949 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-11 17:48:10.553  3949  3949 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-11 17:48:10.553  3949  3949 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-11 17:48:10.554  3949  3949 V BluetoothMapService: Handler(): got msg=4
08-11 17:48:10.554  3949  3949 D BluetoothMapService: MAP Service closeService in
08-11 17:48:10.554  3949  3949 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-11 17:48:10.554  3949  3949 V BluetoothMapService: MAP Service closeService out
08-11 17:48:10.555  3949  3949 D BluetoothMapService: cleanup()
08-11 17:48:10.555  3949  3949 D BluetoothMapService: MAP Service closeService in
08-11 17:48:10.555  3949  3949 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-11 17:48:10.555  3949  3949 V BluetoothMapService: MAP Service closeService out
08-11 17:48:10.555  3949  4027 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-11 17:48:10.555  3949  4027 D BluetoothAdapterProperties: Setting state to 10
08-11 17:48:10.555  3949  4027 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-11 17:48:10.555  1036  1119 D BluetoothManagerService: Message: 60
08-11 17:48:10.555  1036  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-11 17:48:10.555  1036  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-11 17:48:10.555  3949  4027 I BluetoothAdapterState: Entering OffState
08-11 17:48:10.555  1856  4051 D BluetoothHeadset: onBluetoothStateChange: up=false
08-11 17:48:10.556  6940  6955 D BluetoothMap: onBluetoothStateChange: up=false
08-11 17:48:10.557  1856  2683 D BluetoothHeadset: onBluetoothStateChange: up=false
08-11 17:48:10.557  6940  6956 D BluetoothPbap: onBluetoothStateChange: up=false
08-11 17:48:10.558  1036  1119 D BluetoothA2dp: onBluetoothStateChange: up=false
08-11 17:48:10.558  6940  6955 D BluetoothPan: onBluetoothStateChange on: false
08-11 17:48:10.559  6940  6956 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-11 17:48:10.559  1036  1119 D BluetoothHeadset: onBluetoothStateChange: up=false
08-11 17:48:10.559  1856  1871 D BluetoothHeadset: onBluetoothStateChange: up=false
08-11 17:48:10.560  1036  1119 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-11 17:48:10.560  1036  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,08-11 17:48:10.566  1036  1119 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-11 17:48:10.566  1036  1119 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-11 17:48:10.567  1036  1119 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@3a9a9c0b mBinding = false
08-11 17:48:10.567  1036  1119 D BluetoothManagerService: Sending unbind request.
08-11 17:48:10.569  1036  1119 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-11 17:48:10.570  1944  1944 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-11 17:48:10.571  1944  2082 D LGBluetoothAPIService: Message: 2
08-11 17:48:10.571  1944  2082 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@343b1835 mBinding = false
08-11 17:48:10.571  1944  2082 D LGBluetoothAPIService: Sending unbind request.
,08-11 17:48:10.574  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-11 17:48:10.576  3949  4031 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-11 17:48:10.576  3949  3949 I GKI_LINUX: GKI_exit_task 1 done
08-11 17:48:10.576  3949  3949 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-11 17:48:10.577  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:48:10.577  3949  3949 I BluetoothServiceJni: cleanupNative: return from cleanup
08-11 17:48:10.578  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:48:10.578  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:48:10.579  6940  6940 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-11 17:48:10.580  6940  6940 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-11 17:48:10.580  6940  6940 D LGBluetoothEventManager: [BTUI] clear device connection state
08-11 17:48:10.580  3949  3949 I art     : --- WEIRD: removing null entry 246
08-11 17:48:10.580  3949  3949 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-11 17:48:10.580  3949  3949 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-11 17:48:10.581  1603  1603 D BluetoothAdapter: 511128530: getState() :  mService = null. Returning STATE_OFF
08-11 17:48:10.581  1603  1603 D BluetoothAdapter: 511128530: getState() :  mService = null. Returning STATE_OFF
08-11 17:48:10.584  3949  3949 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
,08-11 17:48:10.585  6940  6940 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-11 17:48:10.587  3949  3949 I art     : System.exit called, status: 0
08-11 17:48:10.588  3949  3949 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-11 17:48:10.592  6922  6922 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-11 17:48:10.597  6940  6940 D DockEventReceiver: finishStartingService: stopping service
,08-11 17:48:10.600  6940  6940 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-11 17:48:10.609   322  1783 V AudioFlinger: 3949 died, releasing its sessions
08-11 17:48:10.609   322  1783 V AudioFlinger:  pid 1856 @ 0
,08-11 17:48:10.609   322  1783 V AudioFlinger:  pid 3521 @ 1
08-11 17:48:10.609   322  1783 V AudioFlinger:  pid 3521 @ 2
08-11 17:48:10.610  6940  6940 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-11 17:48:10.611  6940  6940 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-11 17:48:10.694  1036  1981 I ActivityManager: Process com.android.bluetooth (pid 3949) has died
08-11 17:48:10.695  1036  1981 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-11 17:48:10.713  2184  2184 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-11 17:48:10.728  7030  7051 W FormManager: Network not available. Please check & try again.
,08-11 17:48:10.755  6940  6940 D BluetoothPermissionRequest: onReceive
,08-11 17:48:10.756  7030  7057 V FormManager: Network unavailable.
08-11 17:48:10.762  6940  6940 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-11 17:48:10.763  6940  6940 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-11 17:48:10.765  7030  7057 V FormManager: Network unavailable.
08-11 17:48:10.770  6940  6940 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-11 17:48:10.831  1036  1624 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7060 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-11 17:48:10.837  1036  1789 I ActivityManager: Killing 6090:com.android.contacts/u0a19 (adj 15): empty #17
,08-11 17:48:10.942  1036  1947 W libprocessgroup: failed to open /acct/uid_10019/pid_6090/cgroup.procs: No such file or directory
,08-11 17:48:10.969  6940  6940 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-11 17:48:10.969  6940  6940 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-11 17:48:10.969  6940  6940 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-11 17:48:10.970  6940  6940 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-11 17:48:10.970  6940  6940 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-11 17:48:10.981  7060  7060 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-11 17:48:10.982  7060  7060 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-11 17:48:10.982  7060  7060 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-11 17:48:10.983  7060  7060 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-11 17:48:10.995  6940  6940 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-11 17:48:10.995  6940  6940 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-11 17:48:10.995  6940  6940 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
,08-11 17:48:10.995  6940  6940 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-11 17:48:10.995  6940  6940 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-11 17:48:10.996  6940  6940 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-11 17:48:11.004  4365  4365 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-11 17:48:11.004  7060  7060 D BluetoothAdapterApp: Loading JNI Library
08-11 17:48:11.004  4365  4365 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-11 17:48:11.006  4365  4365 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-11 17:48:11.009  4365  4365 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-11 17:48:11.019  4365  7084 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-11 17:48:11.031  6922  6922 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED,
08-11 17:48:11.031  6922  6922 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-11 17:48:11.031  6922  6922 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-11 17:48:11.035  6940  6940 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-11 17:48:11.040  4365  7085 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-11 17:48:11.040  4365  7085 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-11 17:48:11.048  6940  6940 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-11 17:48:11.049  7060  7060 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@3cd2f233 Instance Count = 1
08-11 17:48:11.054  7060  7060 D BluetoothAdapterApp: onCreate
08-11 17:48:11.066  6989  6989 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-11 17:48:11.067  6989  6989 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-11 17:48:11.067  6989  6989 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-11 17:48:11.080  7030  7092 W FormManager: Network not available. Please check & try again.
08-11 17:48:11.081  7060  7060 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-11 17:48:11.081  7060  7060 D ProfileConfigQcom: Adding HeadsetService
08-11 17:48:11.082  7060  7060 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-11 17:48:11.082  7060  7060 D ProfileConfigQcom: Adding A2dpService
08-11 17:48:11.082  7060  7060 D ProfileConfigQcom: [BTUI] HidService is supported
08-11 17:48:11.082  7060  7060 D ProfileConfigQcom: Adding HidService
08-11 17:48:11.082  7060  7060 D ProfileConfigQcom: [BTUI] HealthService is supported
08-11 17:48:11.083  7060  7060 D ProfileConfigQcom: Adding HealthService
08-11 17:48:11.083  7060  7060 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-11 17:48:11.084  7060  7060 D ProfileConfigQcom: [BTUI] PanService is supported
08-11 17:48:11.084  7060  7060 D ProfileConfigQcom: Adding PanService
08-11 17:48:11.085  7060  7060 D ProfileConfigQcom: [BTUI] GattService is supported
08-11 17:48:11.085  7060  7060 D ProfileConfigQcom: Adding GattService
08-11 17:48:11.085  7060  7060 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-11 17:48:11.085  7060  7060 D ProfileConfigQcom: Adding BluetoothMapService
08-11 17:48:11.086  7060  7060 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-11 17:48:11.087  7060  7060 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-11 17:48:11.095  7030  7093 V FormManager: Network unavailable.
,08-11 17:48:11.099  7030  7093 V FormManager: Network unavailable.
08-11 17:48:11.101  6940  6940 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-11 17:48:11.102  7060  7060 V LGMDMManagerInternal: Create singleton instance
08-11 17:48:11.127  6989  6989 D LgDataFeature: LgDataFeature() Constructor: none
08-11 17:48:11.128  6989  6989 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-11 17:48:11.135  6989  6989 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-11 17:48:11.136  6989  6989 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-11 17:48:11.136  6989  6989 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-11 17:48:11.136  6989  6989 V SoundPool: doLoad: loading sample sampleID=1
08-11 17:48:11.137  6989  6989 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-11 17:48:11.138  6989  7103 V SoundPool: Start decode
08-11 17:48:11.138  6989  7103 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-11 17:48:11.138   322  2157 V MediaPlayerService: decode(23, 10857164, 17813)
08-11 17:48:11.138   322  2157 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-11 17:48:11.138   322  2157 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-11 17:48:11.138   322  2157 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-11 17:48:11.138   322  2157 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-11 17:48:11.138   322  2157 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-11 17:48:11.138   322  2157 V MediaPlayerService: player type = 3
08-11 17:48:11.139   322  2157 V AwesomePlayer: AwesomePlayer create()
08-11 17:48:11.139   322  2157 V AwesomePlayer: reset_l() 
08-11 17:48:11.139   322  2157 V AwesomePlayer: cancelPlayerEvents
08-11 17:48:11.139   322  2157 V AwesomePlayer: setAudioSink() 
08-11 17:48:11.139   322  2157 V AwesomePlayer: reset_l() 
08-11 17:48:11.139   322  2157 V AudioCache: notify(0xb1432300, 8, 0, 0)
08-11 17:48:11.139   322  2157 V AudioCache: ignored
08-11 17:48:11.139   322  2157 V AwesomePlayer: cancelPlayerEvents
08-11 17:48:11.139   322  2157 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-11 17:48:11.139   322  2157 V AwesomePlayer: setDataSource_l dataSource
08-11 17:48:11.139   322  2157 V LGParserOSAL: SniffLGParser start
08-11 17:48:11.139   322  2157 V LGParserOSAL: MainType:5, SubType=0
08-11 17:48:11.140   322  2157 V LGParserOSAL: #### check Mime : application/ogg
08-11 17:48:11.140   322  2157 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-11 17:48:11.140   322  2157 E MediaExtractor: Use LGExtractor :application/ogg 
08-11 17:48:11.143  6774  6774 D UEI.SmartControl: QS Service created
08-11 17:48:11.144  6989  6989 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-11 17:48:11.145  6989  6989 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-11 17:48:11.146  6989  6989 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-11 17:48:11.159  6989  6989 V LGMDMManager: Create singleton instance
08-11 17:48:11.174  6774  6774 I UEI.SmartControl: Service initServices...
08-11 17:48:11.174  6774  6774 D UEI.SmartControl: QS start get config
08-11 17:48:11.182   322  2157 V LGParserOSAL: supported mime: application/ogg
08-11 17:48:11.182   322  2157 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-11 17:48:11.182   322  2157 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-11 17:48:11.182   322  2157 V AwesomePlayer: mBitrate = -1 bits/sec
08-11 17:48:11.182   322  2157 V AwesomePlayer: AudioTrack Setting
08-11 17:48:11.182   322  2157 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-11 17:48:11.182   322  2157 V AwesomePlayer: setAudioSource() 
08-11 17:48:11.182   322  2157 V MediaPlayerService: prepare
08-11 17:48:11.182   322  2157 V AwesomePlayer: prepareAsync_l() 
08-11 17:48:11.183   322  2157 V MediaPlayerService: wait for prepare
08-11 17:48:11.183   322  7104 V AwesomePlayer: onPrepareAsyncEvent() 
08-11 17:48:11.183   322  7104 V AwesomePlayer: initAudioDecoder() 
08-11 17:48:11.183   322  7104 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-11 17:48:11.183   322  7104 V AudioSystem: isOffloadSupported()
08-11 17:48:11.183   322  7104 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-11 17:48:11.183   322  7104 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-11 17:48:11.183   322  7104 I AudioFlinger: isAudioPlaybackHookOn() false
08-11 17:48:11.183   322  7104 V AwesomePlayer: getUseOffload() = 0 
08-11 17:48:11.183   322  7104 V OMXCodec: OMXCodec::Create
08-11 17:48:11.183   322  7104 V OMXCodec: findMatchingCodecs()
08-11 17:48:11.183   322  7104 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-11 17:48:11.183   322  7104 V OMXCodec: matchingCodecs.size()=1
08-11 17:48:11.183   322  7104 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-11 17:48:11.185   322  7104 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-11 17:48:11.185   322  7104 V LGCodecAdapter: LG Codec Adapter start
08-11 17:48:11.185   322  7104 V OMXCodec: OMXCodec Createtor
08-11 17:48:11.185   322  7104 V OMXCodec: setComponentRole
08-11 17:48:11.185   322  7104 V OMXCodec: configureCodec protected=0
08-11 17:48:11.185   322  7104 V LGCodecAdapter: called getLGCodecSpecificData
,08-11 17:48:11.185   322  7104 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-11 17:48:11.185   322  7104 V LGCodecOSAL: Called LGconfigureCodecMETA
08-11 17:48:11.185   322  7104 V LGCodecOSAL: Called LGconfigureCodecMSG
,08-11 17:48:11.185   322  7104 V LGCodecOSAL: Not support LGCodec
08-11 17:48:11.185   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-11 17:48:11.185   322  7104 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-11 17:48:11.185   322  7104 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-11 17:48:11.185   322  7104 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-11 17:48:11.185   322  7104 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-11 17:48:11.185   322  7104 V AudioSystem: isOffloadSupported()
08-11 17:48:11.185   322  7104 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-11 17:48:11.185   322  7104 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-11 17:48:11.185   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-11 17:48:11.185   322  7104 V OMXCodec: init()
08-11 17:48:11.185   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-11 17:48:11.185   322  7104 V OMXCodec: allocateBuffers
08-11 17:48:11.185   322  7104 V OMXCodec: allocateBuffersOnPort portIndex=0
08-11 17:48:11.185   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-11 17:48:11.186   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7650 on input port
08-11 17:48:11.186   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on input port
08-11 17:48:11.186   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
08-11 17:48:11.186   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
08-11 17:48:11.186   322  7104 V OMXCodec: allocateBuffersOnPort portIndex=1
08-11 17:48:11.186   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-11 17:48:11.186   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
08-11 17:48:11.186   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
08-11 17:48:11.186   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
08-11 17:48:11.186   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-11 17:48:11.186   322  7104 V OMXCodec: init() mAsyncCompletion wait!!! 
08-11 17:48:11.186   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-11 17:48:11.186   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-11 17:48:11.186   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-11 17:48:11.186   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-11 17:48:11.186   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-11 17:48:11.186   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-11 17:48:11.187   322  7104 V OMXCodec: init() mAsyncCompletion wait free! 
08-11 17:48:11.187   322  7104 V AwesomePlayer: finishAsyncPrepare_l() 
08-11 17:48:11.187   322  7104 V AudioCache: notify(0xb1432300, 5, 0, 0)
08-11 17:48:11.187   322  7104 V AudioCache: ignored
08-11 17:48:11.187   322  7104 V AudioCache: notify(0xb1432300, 1, 0, 0)
08-11 17:48:11.187   322  7104 V AudioCache: prepared
08-11 17:48:11.187   322  2157 V AudioCache: wait - success
08-11 17:48:11.187   322  2157 V MediaPlayerService: start
08-11 17:48:11.187   322  2157 V AwesomePlayer: play_l() 
08-11 17:48:11.187   322  2157 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08,-11 17:48:11.187   322  2157 V AwesomePlayer: createAudioPlayer_l
08-11 17:48:11.187   322  2157 V AwesomePlayer: seekAudioIfNecessary_l() 
08-11 17:48:11.187   322  2157 V AwesomePlayer: startAudioPlayer_l() 
08-11 17:48:11.187   322  2157 D AudioPlayer: start of Playback, useOffload 0
08-11 17:48:11.187   322  2157 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-11 17:48:11.187   322  2157 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-11 17:48:11.193   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-11 17:48:11.193   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-11 17:48:11.193   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-11 17:48:11.193   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-11 17:48:11.193   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-11 17:48:11.193   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-11 17:48:11.197   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884688
08-11 17:48:11.197   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-11 17:48:11.198   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884848
,08-11 17:48:11.198   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-11 17:48:11.198   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884928
08-11 17:48:11.198   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-11 17:48:11.198   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885008
08-11 17:48:11.198   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-11 17:48:11.198   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-11 17:48:11.198   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-11 17:48:11.198   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-11 17:48:11.198   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-11 17:48:11.198   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-11 17:48:11.199   322  7106 V OMXCodec: allocateBuffersOnPort portIndex=1
08-11 17:48:11.199   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-11 17:48:11.199   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
08-11 17:48:11.199   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
08-11 17:48:11.199   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
08-11 17:48:11.199   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f9c0 on output port
08-11 17:48:11.199   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
,08-11 17:48:11.199   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-11 17:48:11.200   322  2157 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-11 17:48:11.201  7060  7060 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-11 17:48:11.201   322  2157 V AudioCache: notify(0xb1432300, 6, 0, 0)
08-11 17:48:11.201   322  2157 V AudioCache: ignored
08-11 17:48:11.201   322  2157 V MediaPlayerService: wait for playback complete
08-11 17:48:11.202   322  7108 V AudioCache: write(0xb16e5000, 4096)
08-11 17:48:11.202   322  7108 V AudioCache: memcpy(0xac300000, 0xb16e5000, 4096)
08-11 17:48:11.205   322  7108 V AudioCache: write(0xb16e5000, 4096)
08-11 17:48:11.205   322  7108 V AudioCache: memcpy(0xac301000, 0xb16e5000, 4096)
08-11 17:48:11.206   322  7108 V AudioCache: write(0xb16e5000, 4096)
08-11 17:48:11.206   322  7108 V AudioCache: memcpy(0xac302000, 0xb16e5000, 4096)
08-11 17:48:11.206   322  7108 V AudioCache: write(0xb16e5000, 4096)
08-11 17:48:11.206   322  7108 V AudioCache: memcpy(0xac303000, 0xb16e5000, 4096)
08-11 17:48:11.206  7060  7060 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-11 17:48:11.207  7060  7060 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-11 17:48:11.207   322  7108 V AudioCache: write(0xb16e5000, 4096)
08-11 17:48:11.207   322  7108 V AudioCache: memcpy(0xac304000, 0xb16e5000, 4096)
08-11 17:48:11.207  7060  7060 V BluetoothSapReceiver: SapReceiver onReceive 
08-11 17:48:11.208   322  7108 V AudioCache: write(0xb16e5000, 4096)
08-11 17:48:11.208   322  7108 V AudioCache: memcpy(0xac305000, 0xb16e5000, 4096)
08-11 17:48:11.208  7060  7060 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-11 17:48:11.208  7060  7060 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-11 17:48:11.208   322  7108 V AudioCache: write(0xb16e5000, 4096)
08-11 17:48:11.208   322  7108 V AudioCache: memcpy(0xac306000, 0xb16e5000, 4096)
08-11 17:48:11.209   322  7108 V AudioCache: write(0xb16e5000, 4096)
08-11 17:48:11.209   322  7108 V AudioCache: memcpy(0xac307000, 0xb16e5000, 4096)
08-11 17:48:11.210   322  7108 V AudioCache: write(0xb16e5000, 4096)
08-11 17:48:11.210   322  7108 V AudioCache: memcpy(0xac308000, 0xb16e5000, 4096)
08-11 17:48:11.211   322  7108 V AudioCache: write(0xb16e5000, 4096)
08-11 17:48:11.211   322  7108 V AudioCache: memcpy(0xac309000, 0xb16e5000, 4096)
08-11 17:48:11.211   322  7108 V AudioCache: write(0xb16e5000, 4096)
08-11 17:48:11.211   322  7108 V AudioCache: memcpy(0xac30a000, 0xb16e5000, 4096)
08-11 17:48:11.212   322  7108 V AudioCache: write(0xb16e5000, 4096)
08-11 17:48:11.212   322  7108 V AudioCache: memcpy(0xac30b000, 0xb16e5000, 4096)
08-11 17:48:11.212   322  7108 V AudioCache: write(0xb16e5000, 4096)
,08-11 17:48:11.212   322  7108 V AudioCache: memcpy(0xac30c000, 0xb16e5000, 4096)
08-11 17:48:11.213   322  7108 V AudioCache: write(0xb16e5000, 4096)
08-11 17:48:11.213   322  7108 V AudioCache: memcpy(0xac30d000, 0xb16e5000, 4096)
08-11 17:48:11.214   322  7108 V AudioCache: write(0xb16e5000, 4096)
08-11 17:48:11.214   322  7108 V AudioCache: memcpy(0xac30e000, 0xb16e5000, 4096)
08-11 17:48:11.214   322  7108 V AudioCache: write(0xb16e5000, 4096)
08-11 17:48:11.214   322  7108 V AudioCache: memcpy(0xac30f000, 0xb16e5000, 4096)
08-11 17:48:11.215   322  7108 V AudioCache: write(0xb16e5000, 4096)
08-11 17:48:11.215   322  7108 V AudioCache: memcpy(0xac310000, 0xb16e5000, 4096)
08-11 17:48:11.215  7006  7006 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-11 17:48:11.216   322  7108 V AudioCache: write(0xb16e5000, 4096)
08-11 17:48:11.216   322  7108 V AudioCache: memcpy(0xac311000, 0xb16e5000, 4096)
08-11 17:48:11.216   322  7108 V AudioCache: write(0xb16e5000, 4096)
08-11 17:48:11.216   322  7108 V AudioCache: memcpy(0xac312000, 0xb16e5000, 4096)
08-11 17:48:11.217   322  7108 V AudioCache: write(0xb16e5000, 4096)
08-11 17:48:11.217   322  7108 V AudioCache: memcpy(0xac313000, 0xb16e5000, 4096)
08-11 17:48:11.218   322  7108 V AudioCache: write(0xb16e5000, 4096)
08-11 17:48:11.218   322  7108 V AudioCache: memcpy(0xac314000, 0xb16e5000, 4096)
08-11 17:48:11.218   322  7108 V AudioCache: write(0xb16e5000, 4096)
08-11 17:48:11.219   322  7108 V AudioCache: memcpy(0xac315000, 0xb16e5000, 4096)
08-11 17:48:11.219   322  7108 V AudioCache: write(0xb16e5000, 4096)
08-11 17:48:11.219   322  7108 V AudioCache: memcpy(0xac316000, 0xb16e5000, 4096)
08-11 17:48:11.220   322  7108 V AudioCache: write(0xb16e5000, 4096)
08-11 17:48:11.220   322  7108 V AudioCache: memcpy(0xac317000, 0xb16e5000, 4096)
,08-11 17:48:11.221   322  7108 V AudioCache: write(0xb16e5000, 4096)
08-11 17:48:11.221   322  7108 V AudioCache: memcpy(0xac318000, 0xb16e5000, 4096)
08-11 17:48:11.221   322  7108 V AudioCache: write(0xb16e5000, 4096)
08-11 17:48:11.221   322  7108 V AudioCache: memcpy(0xac319000, 0xb16e5000, 4096)
08-11 17:48:11.222   322  7108 V AudioCache: write(0xb16e5000, 4096)
08-11 17:48:11.222   322  7108 V AudioCache: memcpy(0xac31a000, 0xb16e5000, 4096)
08-11 17:48:11.223   322  7108 V AudioCache: write(0xb16e5000, 4096)
08-11 17:48:11.223   322  7108 V AudioCache: memcpy(0xac31b000, 0xb16e5000, 4096)
08-11 17:48:11.223   322  7108 V AudioCache: write(0xb16e5000, 4096)
08-11 17:48:11.223   322  7108 V AudioCache: memcpy(0xac31c000, 0xb16e5000, 4096)
08-11 17:48:11.223   322  7108 V AudioCache: write(0xb16e5000, 4096)
08-11 17:48:11.223   322  7108 V AudioCache: memcpy(0xac31d000, 0xb16e5000, 4096)
08-11 17:48:11.223   322  7108 V AudioCache: write(0xb16e5000, 4096)
08-11 17:48:11.223   322  7108 V AudioCache: memcpy(0xac31e000, 0xb16e5000, 4096)
08-11 17:48:11.223   322  7108 V AudioCache: write(0xb16e5000, 4096)
08-11 17:48:11.224   322  7108 V AudioCache: memcpy(0xac31f000, 0xb16e5000, 4096)
08-11 17:48:11.225   322  7108 V AudioCache: write(0xb16e5000, 4096)
08-11 17:48:11.225   322  7108 V AudioCache: memcpy(0xac320000, 0xb16e5000, 4096)
08-11 17:48:11.225   322  7108 V AudioCache: write(0xb16e5000, 4096)
08-11 17:48:11.226   322  7108 V AudioCache: memcpy(0xac321000, 0xb16e5000, 4096)
08-11 17:48:11.226   322  7108 V AudioCache: write(0xb16e5000, 4096)
08-11 17:48:11.226   322  7108 V AudioCache: memcpy(0xac322000, 0xb16e5000, 4096)
08-11 17:48:11.226   322  7108 V AudioCache: write(0xb16e5000, 4096)
08-11 17:48:11.226   322  7108 V AudioCache: memcpy(0xac323000, 0xb16e5000, 4096)
08-11 17:48:11.227   322  7108 V AudioCache: write(0xb16e5000, 4096)
08-11 17:48:11.227   322  7108 V AudioCache: memcpy(0xac324000, 0xb16e5000, 4096)
08-11 17:48:11.228   322  7108 V AudioCache: write(0xb16e5000, 4096)
08-11 17:48:11.228   322  7108 V AudioCache: memcpy(0xac325000, 0xb16e5000, 4096)
08-11 17:48:11.228   322  7108 V AudioCache: write(0xb16e5000, 4096)
08-11 17:48:11.228   322  7108 V AudioCache: memcpy(0xac326000, 0xb16e5000, 4096)
08-11 17:48:11.228   322  7108 V AudioCache: write(0xb16e5000, 4096)
08-11 17:48:11.228   322  7108 V AudioCache: memcpy(0xac327000, 0xb16e5000, 4096)
08-11 17:48:11.229   322  7108 V AudioCache: write(0xb16e5000, 4096)
,08-11 17:48:11.229   322  7108 V AudioCache: memcpy(0xac328000, 0xb16e5000, 4096)
08-11 17:48:11.229   322  7108 V AudioCache: write(0xb16e5000, 4096)
08-11 17:48:11.229   322  7108 V AudioCache: memcpy(0xac329000, 0xb16e5000, 4096)
08-11 17:48:11.229   322  7108 V AudioCache: write(0xb16e5000, 4096)
08-11 17:48:11.229   322  7108 V AudioCache: memcpy(0xac32a000, 0xb16e5000, 4096)
08-11 17:48:11.230   322  7108 V AudioCache: write(0xb16e5000, 4096)
08-11 17:48:11.230   322  7108 V AudioCache: memcpy(0xac32b000, 0xb16e5000, 4096)
08-11 17:48:11.230   322  7108 V AudioCache: write(0xb16e5000, 4096)
08-11 17:48:11.230   322  7108 V AudioCache: memcpy(0xac32c000, 0xb16e5000, 4096)
08-11 17:48:11.231   322  7108 V AudioCache: write(0xb16e5000, 4096)
08-11 17:48:11.231   322  7108 V AudioCache: memcpy(0xac32d000, 0xb16e5000, 4096)
08-11 17:48:11.231   322  7108 V AudioCache: write(0xb16e5000, 4096)
08-11 17:48:11.231   322  7108 V AudioCache: memcpy(0xac32e000, 0xb16e5000, 4096)
08-11 17:48:11.232   322  7108 V AudioCache: write(0xb16e5000, 4096)
08-11 17:48:11.232   322  7108 V AudioCache: memcpy(0xac32f000, 0xb16e5000, 4096)
08-11 17:48:11.232   322  7108 V AudioCache: write(0xb16e5000, 4096)
,08-11 17:48:11.232   322  7108 V AudioCache: memcpy(0xac330000, 0xb16e5000, 4096)
,08-11 17:48:11.233   322  7108 V AudioCache: write(0xb16e5000, 4096)
08-11 17:48:11.233   322  7108 V AudioCache: memcpy(0xac331000, 0xb16e5000, 4096)
,08-11 17:48:11.233   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-11 17:48:11.233   322  7108 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-11 17:48:11.233   322  7108 V AwesomePlayer: postAudioEOS() 
08-11 17:48:11.233   322  7108 V AudioCache: write(0xb16e5000, 280)
08-11 17:48:11.233   322  7108 V AudioCache: memcpy(0xac332000, 0xb16e5000, 280)
08-11 17:48:11.235  6989  6989 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-11 17:48:11.235   322  7104 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-11 17:48:11.235   322  7104 V AwesomePlayer: onStreamDone
08-11 17:48:11.235   322  7104 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-11 17:48:11.235   322  7104 V AudioCache: notify(0xb1432300, 2, 0, 0)
08-11 17:48:11.235   322  7104 V AudioCache: playback complete
08-11 17:48:11.235   322  7104 V AwesomePlayer: pause_l() 
08-11 17:48:11.235   322  7104 V AudioCache: notify(0xb1432300, 7, 0, 0)
08-11 17:48:11.235   322  7104 V AudioCache: ignored
08-11 17:48:11.235   322  7104 V AwesomePlayer: cancelPlayerEvents
08-11 17:48:11.235   322  2157 V AudioCache: wait - success
08-11 17:48:11.235   322  2157 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-11 17:48:11.235   322  7104 D AudioPlayer: Pause Playback at 1068125
08-11 17:48:11.235   322  2157 V AwesomePlayer: reset_l() 
08-11 17:48:11.235   322  2157 V AudioCache: notify(0xb1432300, 8, 0, 0)
08-11 17:48:11.235   322  2157 V AudioCache: ignored
08-11 17:48:11.235   322  2157 V AwesomePlayer: cancelPlayerEvents
08-11 17:48:11.235   322  2157 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-11 17:48:11.235   322  2157 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-11 17:48:11.235  6989  6989 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-11 17:48:11.235   322  2157 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-11 17:48:11.235   322  2157 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-11 17:48:11.235   322  2157 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-11 17:48:11.236   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-11 17:48:11.236   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-11 17:48:11.236   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-11 17:48:11.236   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
08-11 17:48:11.236   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-11 17:48:11.236   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
08-11 17:48:11.236   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-11 17:48:11.236   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 0
08-11 17:48:11.236   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-11 17:48:11.236   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7650 on port 0
08-11 17:48:11.236   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-11 17:48:11.236   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-11 17:48:11.236   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f9c0 on port 1
08-11 17:48:11.236   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-11 17:48:11.236   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 1
08-11 17:48:11.236   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-11 17:48:11.236   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 ,on port 1
08-11 17:48:11.236   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-11 17:48:11.236   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 1
08-11 17:48:11.236   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-11 17:48:11.236   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-11 17:48:11.236   322  2157 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-11 17:48:11.236   322  2157 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-11 17:48:11.237   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-11 17:48:11.237   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-11 17:48:11.237   322  7106 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-11 17:48:11.237   322  2157 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-11 17:48:11.237  6989  6989 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:2875
08-11 17:48:11.237   322  2157 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-11 17:48:11.237   322  2157 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-11 17:48:11.237   322  2157 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-11 17:48:11.237   322  2157 D AudioPlayer: AudioPlayer releasing audio source
08-11 17:48:11.237   322  2157 D AudioPlayer: AudioPlayer done releasing audio source
08-11 17:48:11.238   322  2157 V AwesomePlayer: reset_l() 
08-11 17:48:11.238   322  2157 V AwesomePlayer: cancelPlayerEvents
08-11 17:48:11.238   322  2157 V AwesomePlayer: ~AwesomePlayer call
08-11 17:48:11.238   322  2157 V AwesomePlayer: reset_l() 
08-11 17:48:11.238   322  2157 V AwesomePlayer: cancelPlayerEvents
08-11 17:48:11.238  6989  7103 V SoundPool: close(31)
08-11 17:48:11.238  6989  7103 V SoundPool: pointer = 0x9ffdb000, size = 205080, sampleRate = 48000, numChannels = 2
08-11 17:48:11.446  6774  6774 I UEI.SmartControl: Supports setup maps: true
08-11 17:48:11.449  6774  6774 D UEI.SmartControl: QS start statue = true Error code = 0
08-11 17:48:11.449  6774  6774 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-11 17:48:11.449  6774  6774 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
,08-11 17:48:11.449  6774  6774 I UEI.SmartControl: ### init IR Blaster...
08-11 17:48:11.453  6774  6774 D serial_port: Configuring serial port
08-11 17:48:11.454  6774  6774 E UEI.SmartControl: UEIBLaster setting for 616
08-11 17:48:11.454  6774  6774 I UEI.SmartControl: Setting serial record hearder size = 2
,08-11 17:48:11.454  6774  6774 I UEI.SmartControl: configuring settings for MAXQ616
08-11 17:48:11.454  6774  6774 I UEI.SmartControl: Get version...
,08-11 17:48:11.472  6774  7110 D UEI.SmartControl: serial port data available: 21
,08-11 17:48:11.499  6774  6774 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-11 17:48:11.500  6774  6774 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-11 17:48:11.500  6774  6774 I UEI.SmartControl: QS saving settings...
08-11 17:48:11.502  6774  6774 D UEI.SmartControl: IR Blaster version: 25672567
,08-11 17:48:11.520  6774  7110 D UEI.SmartControl: serial port data available: 4
,08-11 17:48:11.557  6774  6774 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-11 17:48:11.562  6774  7116 I UEI.SmartControl: Device manager: loading config....
,08-11 17:48:11.566  6774  6774 E UEI.SmartControl: Services init done
08-11 17:48:11.566  6774  6774 D UEI.SmartControl: QS Service init finished
08-11 17:48:11.563  6774  7116 D UEI.SmartControl: ----------- loading internal config...
08-11 17:48:11.568  6774  6774 D UEI.SmartControl: QS Service version name: 2.1.91
,08-11 17:48:11.568  6774  6774 D UEI.SmartControl: QS Service version code: 201091
08-11 17:48:11.569  6774  6774 D UEI.SmartControl: Service requested: Control
08-11 17:48:11.572  6774  7116 E UEI.SmartControl: Loading SETTINGS...
,08-11 17:48:11.576  6774  6774 D UEI.SmartControl: Request IControl service: devices are loaded...
08-11 17:48:11.579  6989  6989 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-11 17:48:11.580  6774  7116 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-11 17:48:11.581  6774  6789 I UEI.SmartControl: ------ IControl API: 11
08-11 17:48:11.581  6774  6789 D UEI.SmartControl: File observer start...
08-11 17:48:11.581  6774  6774 D UEI.SmartControl: Internal service binding...
08-11 17:48:11.582  6774  6789 E UEI.SmartControl: IR Port is disabled: false
08-11 17:48:11.582  6774  6789 D UEI.SmartControl: Starting file observer...
08-11 17:48:11.582  6774  6789 I UEI.SmartControl: Registering callback...
08-11 17:48:11.589  6774  6791 I UEI.SmartControl: ------ IControl API: 19
08-11 17:48:11.590  6774  6791 I UEI.SmartControl: Registering Services Ready callback...
08-11 17:48:11.590  6774  6791 I UEI.SmartControl: Notify client services are ready...
,08-11 17:48:11.591  6989  7004 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-11 17:48:11.591  6774  7115 I UEI.SmartControl: Notify AllClients services are ready: 0
08-11 17:48:11.592  6989  7101 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-11 17:48:11.592  6989  7101 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-11 17:48:11.592  6989  7005 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-11 17:48:11.593  6774  7115 D UEI.SmartControl: -----service ready thread exits
08-11 17:48:11.594  6989  7101 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-11 17:48:11.594  6989  7101 D QRemote : [RemoteControlManager.java:391:handleMessage()] oooooo 140510:Retrieve msg remove
08-11 17:48:11.594  6989  7101 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-11 17:48:11.595  6989  6989 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-11 17:48:11.595  6989  6989 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-11 17:48:11.595  6774  6789 I UEI.SmartControl: ------ IControl API: 8
08-11 17:48:11.597  6989  6989 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-11 17:48:11.597  6989  6989 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-11 17:48:11.598  6989  6989 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-11 17:48:11.598  6989  6989 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-11 17:48:11.599  6989  6989 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-11 17:48:11.599  6989  6989 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-11 17:48:11.601  6989  6989 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,08-11 17:48:11.604  6989  6989 D QRemote : [RemoteControlManager.java:327:handleMessage()] oooooo 140510:retrieveDevices already complete. Do nothing
08-11 17:48:11.605  6989  6989 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-11 17:48:11.605  6989  6989 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-11 17:48:11.606  6989  6989 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-11 17:48:11.606  6989  6989 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-11 17:48:11.607  6989  6989 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-11 17:48:11.608  6989  6989 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-11 17:48:11.609  6989  6989 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-11 17:48:11.610  6989  6989 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1470930491610]
08-11 17:48:11.611  6989  6989 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-11 17:48:11.613  1036  1975 I ActivityManager: Killing 6116:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-11 17:48:11.635  6989  7121 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-11 17:48:11.644  1036  1975 I ActivityManager: Killing 6587:com.lge.email/u0a23 (adj 15): empty #18
,08-11 17:48:11.747  1036  2016 W libprocessgroup: failed to open /acct/uid_10027/pid_6116/cgroup.procs: No such file or directory
,08-11 17:48:11.755  1036  1788 W libprocessgroup: failed to open /acct/uid_10023/pid_6587/cgroup.procs: No such file or directory
08-11 17:48:11.807  6989  6989 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-11 17:48:11.808  6989  6989 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-11 17:48:11.808  6989  6989 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-11 17:48:11.808  6989  6989 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-11 17:48:11.809  6989  6989 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-11 17:48:11.809  6989  6989 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-11 17:48:11.810  6989  6989 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-11 17:48:11.820  6989  6989 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-11 17:48:12.385  1036  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-11 17:48:12.399  1036  1119 D Tethering: MasterInitialState.processMessage what=3
08-11 17:48:12.416  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 17:48:12.421  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:48:12.423  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:48:12.423  1036  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-11 17:48:12.428  1036  1119 D Tethering: MasterInitialState.processMessage what=3
08-11 17:48:12.429  1036  1099 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-11 17:48:12.439  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:48:12.441  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 17:48:12.444  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:48:12.446  6495  6495 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-11 17:48:12.449  6495  6521 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-11 17:48:12.461  5336  5336 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-11 17:48:12.469  5336  5336 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-11 17:48:12.484  2184  2184 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-11 17:48:12.517  1036  1099 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-11 17:48:12.541  1036  1981 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7141 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-11 17:48:12.558  1036  1099 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-11 17:48:12.558  1036  1099 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-11 17:48:12.674  7141  7141 I AppUp4:AppBoxCP: onCreate
,08-11 17:48:12.675  7141  7141 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-11 17:48:12.687  7141  7141 I AppUp4:DB:  setFingerPrint start
08-11 17:48:12.687  7141  7141 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-11 17:48:12.696  7141  7141 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-11 17:48:12.696  7141  7141 I AppUp4:DB:  SDK version = 21
08-11 17:48:12.696  7141  7141 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-11 17:48:12.699  7141  7141 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-11 17:48:12.701  7141  7141 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-11 17:48:12.701  7141  7141 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-11 17:48:12.704  7141  7141 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-11 17:48:12.704  7141  7141 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-11 17:48:12.712  7141  7141 I AppUp4:CustModeStarterReceiver: onReceive
,08-11 17:48:12.763  7141  7141 D LgDataFeature: LgDataFeature() Constructor: none
,08-11 17:48:12.763  7141  7141 D LgDataFeature: LgDataFeature() Constructor Done, null
08-11 17:48:12.774  7141  7141 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@8700525
08-11 17:48:12.774  7141  7141 D AppUp4:CustFacade: isCustomizationCompleted : false
,08-11 17:48:12.774  7141  7141 D AppUp4:CustFacade: isPhone : true
08-11 17:48:12.775  7141  7141 D AppUp4:CustModeStarterReceiver: begin check event
08-11 17:48:12.775  7141  7141 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-11 17:48:12.776  7141  7141 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-11 17:48:12.777  7141  7173 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
,08-11 17:48:12.777  7141  7173 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-11 17:48:12.777  7141  7173 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-11 17:48:12.780  1036  1905 I ActivityManager: Killing 2158:com.lge.music/u0a34 (adj 15): empty #17
08-11 17:48:12.817   322  1383 V AudioFlinger: 2158 died, releasing its sessions
,08-11 17:48:12.817   322  1383 V AudioFlinger:  pid 1856 @ 0
,08-11 17:48:12.817   322  1383 V AudioFlinger:  pid 3521 @ 1
,08-11 17:48:12.817   322  1383 V AudioFlinger:  pid 3521 @ 2
,08-11 17:48:12.916  4365  4365 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-11 17:48:12.917  1036  2016 W libprocessgroup: failed to open /acct/uid_10034/pid_2158/cgroup.procs: No such file or directory
,08-11 17:48:12.926  4365  4365 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-11 17:48:12.928  4365  4365 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-11 17:48:12.931  4365  4365 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-11 17:48:12.940  4365  7182 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-11 17:48:12.940  4365  7183 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,08-11 17:48:12.940  4365  7183 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-11 17:48:12.983  1036  1940 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7184 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-11 17:48:13.014  1036  1413 D PowerManagerServiceEx: acquireWakeLockInternal: lock=965614699, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
08-11 17:48:13.015  1036  1413 V AlarmManager: ELAPSED_WAKEUP set : Alarm{92c6b51 type 2 when 171926 com.google.android.gms} when 171926
,08-11 17:48:13.049  2598  2598 D [Concierge]Service: onStartCommand(). Type : 9
,08-11 17:48:13.078  7184  7184 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-11 17:48:13.079  7184  7184 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-11 17:48:13.081  7184  7184 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-11 17:48:13.081  7184  7184 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-11 17:48:13.162  7184  7184 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-11 17:48:13.190  7184  7184 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-11 17:48:13.230  7184  7184 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-11 17:48:13.292  7184  7184 D LgDataFeature: LgDataFeature() Constructor: none
,08-11 17:48:13.292  7184  7184 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-11 17:48:13.427  7184  7184 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-11 17:48:13.491  7184  7184 I HubEmail: JNI_OnLoad()
,08-11 17:48:13.491  7184  7184 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-11 17:48:13.491  7184  7184 I HubEmail: registerNatives()
08-11 17:48:13.491  7184  7184 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-11 17:48:13.491  7184  7184 I HubEmail: registerNativeMethods()
08-11 17:48:13.491  7184  7184 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-11 17:48:13.491  7184  7184 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-11 17:48:13.499  3521  3521 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-11 17:48:13.500  3521  3521 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-11 17:48:13.501  3521  3521 I LgeMiscReceiver: networkInfo.isConnected() = false
08-11 17:48:13.506  7184  7207 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-11 17:48:13.540  1036  1577 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7210 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-11 17:48:13.551  7030  7208 W FormManager: Network not available. Please check & try again.
08-11 17:48:13.556  7030  7209 V FormManager: Network unavailable.
,08-11 17:48:13.571  7030  7209 V FormManager: Network unavailable.
,08-11 17:48:13.581  1036  1789 I ActivityManager: Killing 6618:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-11 17:48:13.632  1036  2053 W libprocessgroup: failed to open /acct/uid_10061/pid_6618/cgroup.procs: No such file or directory
,08-11 17:48:13.712  7210  7210 D LgDataFeature: LgDataFeature() Constructor: none
08-11 17:48:13.712  7210  7210 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-11 17:48:13.716  7210  7210 D PhoneMonitor: Register our PhoneStateListener
08-11 17:48:13.739  7210  7210 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-11 17:48:13.742  7210  7210 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-11 17:48:13.768  7210  7210 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-11 17:48:13.769  7210  7210 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-11 17:48:13.770  7210  7210 D TelephonyAutoProfiling: [parse] Load xml
,08-11 17:48:13.778  7210  7210 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-11 17:48:13.778  7210  7210 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-11 17:48:13.778  7210  7210 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-11 17:48:13.778  7210  7210 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-11 17:48:13.778  7210  7210 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
,08-11 17:48:13.778  7210  7210 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-11 17:48:13.778  7210  7210 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-11 17:48:13.779  7210  7210 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-11 17:48:13.779  7210  7210 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-11 17:48:13.779  7210  7210 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-11 17:48:13.779  7210  7210 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-11 17:48:13.779  7210  7210 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-11 17:48:13.779  7210  7210 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-11 17:48:13.779  7210  7210 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-11 17:48:13.779  7210  7210 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-11 17:48:13.779  7210  7210 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-11 17:48:13.780  7210  7210 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-11 17:48:13.795  7210  7210 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-11 17:48:13.812  1036  1975 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7240 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-11 17:48:13.814  1036  1975 I ActivityManager: Killing 6198:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-11 17:48:13.875  1036  1940 W libprocessgroup: failed to open /acct/uid_10080/pid_6198/cgroup.procs: No such file or directory
,08-11 17:48:14.073  1036  1975 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7262 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
08-11 17:48:14.074  1036  1975 I ActivityManager: Killing 6223:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-11 17:48:14.125  1036  2016 W libprocessgroup: failed to open /acct/uid_10097/pid_6223/cgroup.procs: No such file or directory
,08-11 17:48:14.240  1036  1940 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7279 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-11 17:48:14.245  1036  1940 I ActivityManager: Killing 6716:com.lge.eula/1000 (adj 15): empty #17
08-11 17:48:14.326  1036  1538 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:14.326  1036  1538 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-11 17:48:14.335  1036  2016 W libprocessgroup: failed to open /acct/uid_1000/pid_6716/cgroup.procs: No such file or directory
08-11 17:48:14.349  1036  1947 D WifiServiceImplEx: setWifiEnabled: true pid=6670, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-11 17:48:14.350  1036  1947 D WifiService: setWifiEnabled: true pid=6670, uid=10118
08-11 17:48:14.350  1036  1947 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-11 17:48:14.371  1036  1539 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
,08-11 17:48:14.371  1036  1539 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-11 17:48:14.373  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-11 17:48:14.374  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-11 17:48:14.375  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-11 17:48:14.377  1036  1539 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-11 17:48:14.377  1036  1539 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-11 17:48:14.377  1036  1539 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-11 17:48:14.377  1036  1539 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-11 17:48:14.377  1036  1539 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-11 17:48:14.377  1036  1539 E WifiHW  : unknown target_country: EU , set to default
08-11 17:48:14.377  1036  1539 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-11 17:48:14.377  1036  1539 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-11 17:48:14.377  1036  1539 I WifiUtil: gEnableBmps=1
08-11 17:48:14.392  7279  7279 I art     : Almond Protected OAT
,08-11 17:48:14.455  7279  7279 D WeatherApplication: removeAccount
08-11 17:48:14.457  7279  7279 D WeatherApplication: Account.length = 0
08-11 17:48:14.457  7279  7279 E WeatherApplication: OPERATOR:OPEN
,08-11 17:48:14.470  7279  7279 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:48:14
,08-11 17:48:14.475  7279  7279 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-11 17:48:14.476  7279  7279 D Weather.Utils: 2 : All the weather widget is gone.
08-11 17:48:14.486  7279  7279 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-11 17:48:14.490  7279  7279 D WeatherAncestor: connectivity changed - connection : true
08-11 17:48:14.495  7279  7279 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,08-11 17:48:14.510  7279  7279 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,08-11 17:48:14.510  7279  7279 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-11 17:48:14.510  7279  7279 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-11 17:48:14.534  7279  7279 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-11 17:48:14.534  7279  7279 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:48:14
,08-11 17:48:14.588  1036  2035 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7298 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-11 17:48:14.591  1036  2035 I ActivityManager: Killing 6737:com.lge.bnr/1000 (adj 15): empty #17
08-11 17:48:14.614   346   346 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 458us total 21.147ms
,08-11 17:48:14.637   346   346 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 412us total 22.579ms
,08-11 17:48:14.658   346   346 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 408us total 19.231ms
,08-11 17:48:14.665  1036  1624 W libprocessgroup: failed to open /acct/uid_1000/pid_6737/cgroup.procs: No such file or directory
08-11 17:48:14.794   278   382 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-11 17:48:14.794   278   382 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-11 17:48:14.794   278   382 W Vold    : Returning OperationFailed - no handler for errno 0
,08-11 17:48:14.798  7298  7316 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-11 17:48:14.801   278   382 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-11 17:48:14.801   278   382 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-11 17:48:14.801   278   382 W Vold    : Returning OperationFailed - no handler for errno 0
08-11 17:48:14.801  7298  7316 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-11 17:48:14.818   278   382 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-11 17:48:14.818   278   382 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,08-11 17:48:14.818   278   382 W Vold    : Returning OperationFailed - no handler for errno 0
08-11 17:48:14.819  7298  7319 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-11 17:48:14.824   278   382 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-11 17:48:14.824   278   382 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-11 17:48:14.824   278   382 W Vold    : Returning OperationFailed - no handler for errno 0
08-11 17:48:14.824  7298  7319 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-11 17:48:15.066  1036  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-11 17:48:15.070  1036  1119 D Tethering: InitialState.processMessage what=4
08-11 17:48:15.072  1036  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-11 17:48:15.077   318   894 D SoftapController: Softap fwReload - Ok
08-11 17:48:15.083  1036  1539 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (698ms)
08-11 17:48:15.085   318   894 D CommandListener: Setting iface cfg
08-11 17:48:15.086   318   894 D CommandListener: Trying to bring down wlan0
08-11 17:48:15.086   318   894 D CommandListener: Clearing all IP addresses on wlan0
,08-11 17:48:15.088  1036  1539 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-11 17:48:15.090  1036  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-11 17:48:15.090  1036  1539 E WifiStateMachine: useWiFiOffloading() : false
08-11 17:48:15.090  1036  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-11 17:48:15.091  1036  1539 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-11 17:48:15.091  1036  1539 D WifiMonitor: connecting to supplicant
08-11 17:48:15.092  1036  1539 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": Permission denied
08-11 17:48:15.093  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 17:48:15.074  7342  7342 W wpa_supplicant: type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-11 17:48:15.094  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-11 17:48:15.074  7342  7342 W wpa_supplicant: type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-11 17:48:15.097  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:48:15.097  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-11 17:48:15.097  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:48:15.098  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 17:48:15.107  7298  7298 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-11 17:48:15.130  7298  7298 I LibraryLoader: Loading: webviewchromium
,08-11 17:48:15.133  7342  7342 I wpa_supplicant: Successfully initialized wpa_supplicant
08-11 17:48:15.136  7298  7298 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 4055-4061)
08-11 17:48:15.136  7298  7298 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-11 17:48:15.145  7298  7298 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {25815f76}
08-11 17:48:15.147  7298  7298 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-11 17:48:15.148  7298  7298 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-11 17:48:15.160  7298  7298 I BrowserStartupController: Initializing chromium process, renderers=0
,08-11 17:48:15.161  7298  7298 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-11 17:48:15.163  7342  7342 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-11 17:48:15.163  7342  7342 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-11 17:48:15.173  7298  7298 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-11 17:48:15.174  7298  7298 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-11 17:48:15.175  7298  7298 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-11 17:48:15.175   322   322 V AudioPolicyService: registerClient() client 0xb1427180, uid 10093
08-11 17:48:15.176  7298  7354 W AudioManagerAndroid: Requires BLUETOOTH permission
08-11 17:48:15.186  7298  7298 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-11 17:48:15.186  7298  7298 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-11 17:48:15.186  7298  7298 I Adreno-EGL: Build Date: 12/12/14 금
08-11 17:48:15.186  7298  7298 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-11 17:48:15.186  7298  7298 I Adreno-EGL: Remote Branch: 
08-11 17:48:15.186  7298  7298 I Adreno-EGL: Local Patches: 
08-11 17:48:15.186  7298  7298 I Adreno-EGL: Reconstruct Branch: 
08-11 17:48:15.233  7342  7342 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-11 17:48:15.248  7298  7298 I NSApplication: Starting up...
,08-11 17:48:15.303  7342  7342 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-11 17:48:15.309  1036  2035 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7367 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-11 17:48:15.310  1036  2035 I ActivityManager: Killing 6150:com.android.vending/u0a44 (adj 15): empty #17
08-11 17:48:15.317  7342  7342 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-11 17:48:15.317  7342  7342 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-11 17:48:15.376  1036  2016 W libprocessgroup: failed to open /acct/uid_10044/pid_6150/cgroup.procs: No such file or directory
,08-11 17:48:15.408  7367  7367 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-11 17:48:15.827  1036  2053 I art     : Explicit concurrent mark sweep GC freed 59557(2MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 3.107ms total 179.412ms
,08-11 17:48:15.887  6495  6495 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-11 17:48:15.889  6495  6521 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-11 17:48:15.908  2184  2184 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-11 17:48:15.921  7141  7141 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-11 17:48:15.921  7141  7141 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-11 17:48:15.921  7141  7141 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-11 17:48:15.921  7141  7141 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-11 17:48:15.925  7141  7141 I AppUp4:CustModeStarterReceiver: onReceive
08-11 17:48:15.929  7141  7141 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@8700525
08-11 17:48:15.929  7141  7141 D AppUp4:CustFacade: isCustomizationCompleted : false
08-11 17:48:15.929  7141  7141 D AppUp4:CustFacade: isPhone : true
08-11 17:48:15.929  7141  7141 D AppUp4:CustModeStarterReceiver: begin check event
08-11 17:48:15.929  7141  7141 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-11 17:48:15.934  4365  4365 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-11 17:48:15.936  4365  4365 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-11 17:48:15.938  4365  4365 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-11 17:48:15.941  4365  4365 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-11 17:48:15.949  4365  7400 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-11 17:48:15.957  4365  7407 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-11 17:48:15.957  4365  7407 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-11 17:48:15.960  7184  7184 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-11 17:48:15.976  7342  7342 E wpa_supplicant: USIM:  scard_init function
08-11 17:48:15.976  7342  7342 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-11 17:48:15.992  3521  3521 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-11 17:48:15.992  3521  3521 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-11 17:48:15.992  3521  3521 I LgeMiscReceiver: networkInfo.isConnected() = false
08-11 17:48:16.001  7210  7210 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-11 17:48:16.001  7210  7210 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-11 17:48:16.003  7184  7415 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 17:48:16.012  7279  7279 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:48:16
,08-11 17:48:16.014  7030  7418 W FormManager: Network not available. Please check & try again.
,08-11 17:48:16.014  7279  7279 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-11 17:48:16.014  7279  7279 D Weather.Utils: 2 : All the weather widget is gone.
08-11 17:48:16.015  7030  7419 V FormManager: Network unavailable.
08-11 17:48:16.016  7279  7279 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-11 17:48:16.016  7279  7279 D WeatherAncestor: connectivity changed - connection : true
08-11 17:48:16.016  7279  7279 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@385074ab
08-11 17:48:16.019  7030  7419 V FormManager: Network unavailable.
08-11 17:48:16.019  7279  7279 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-11 17:48:16.019  7279  7279 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-11 17:48:16.019  7279  7279 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-11 17:48:16.019  7279  7279 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-11 17:48:16.019  7279  7279 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:48:16
08-11 17:48:16.049  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=965614699 [*alarm*], flags=0x0
,08-11 17:48:16.050   318  7421 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-11 17:48:16.051  1036  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-11 17:48:16.057  6940  6940 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-11 17:48:16.057  6940  6940 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-11 17:48:16.057  6940  6940 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-11 17:48:16.057  6940  6940 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-11 17:48:16.057  6940  6940 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-11 17:48:16.059  6940  6940 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-11 17:48:16.059  6940  6940 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-11 17:48:16.059  6940  6940 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-11 17:48:16.059  6940  6940 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-11 17:48:16.059  6940  6940 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-11 17:48:16.060  6940  6940 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-11 17:48:16.073  6922  6922 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-11 17:48:16.076  6940  6940 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-11 17:48:16.084  7342  7342 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-11 17:48:16.087  1036  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-11 17:48:16.088  6940  6940 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-11 17:48:16.093  7342  7342 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-11 17:48:16.093  7342  7342 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-11 17:48:16.096  1036  1539 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-11 17:48:16.097  1036  1539 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-11 17:48:16.097  1036  1539 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-11 17:48:16.098  1036  1539 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-11 17:48:16.099  1036  1539 E WifiStateMachine:  SupplicantStartingState CMD_STOP_SUPPLICANT_FAILED 1 0
08-11 17:48:16.099  1036  1539 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-11 17:48:16.100  1036  1539 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-11 17:48:16.100  1036  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-11 17:48:16.101  1036  1539 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-11 17:48:16.101  1036  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-11 17:48:16.104  1036  1539 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-11 17:48:16.105  1036  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-11 17:48:16.105  1036  1539 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-11 17:48:16.105  1036  1539 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-11 17:48:16.106  1036  1539 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-11 17:48:16.106  1036  1539 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-11 17:48:16.106  1036  1539 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-11 17:48:16.106  7030  7423 W FormManager: Network not available. Please check & try again.
08-11 17:48:16.107  1036  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-11 17:48:16.107  1036  1539 E WifiStateMachine: useWiFiOffloading() : false
08-11 17:48:16.107  1036  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-11 17:48:16.108  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 17:48:16.109  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 17:48:16.109  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 17:48:16.109  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 17:48:16.109  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-11 17:48:16.109  1036  1539 D WifiNative-wlan0: doBoolean: SET update_config 1
08-11 17:48:16.110  1944  1944 D WfdService: Waiting for WifiP2p enabling
08-11 17:48:16.112  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-11 17:48:16.112  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 17:48:16.112  1036  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-11 17:48:16.110  1036  1539 D WifiNative-wlan0: SET update_config 1: returned true
08-11 17:48:16.114  1036  1539 D WifiConfigStore: Loading config and enabling all networks 
08-11 17:48:16.114  1036  1539 D WifiNative-wlan0: doString: [LIST_NETWORKS]
,08-11 17:48:16.115  1036  1539 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	[CURRENT]
,08-11 17:48:16.119  6670  6670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:48:16.119  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:48:16.119  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:48:16.119  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 17:48:16.119  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:48:16.119  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 17:48:16.119  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 17:48:16.119  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 17:48:16.119  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 17:48:16.119  6670  6670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:48:16.119  6670  6670 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-11 17:48:16.120  6670  6670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:48:16.120  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:48:16.120  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:48:16.120  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 17:48:16.120  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:48:16.120  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 17:48:16.120  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 17:48:16.120  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 17:48:16.120  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 17:48:16.120  6670  6670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:48:16.120  6670  6670 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-11 17:48:16.113  7030  7424 V FormManager: Network unavailable.
08-11 17:48:16.120  6940  6940 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-11 17:48:16.120  6940  6940 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-11 17:48:16.121  6940  6940 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-11 17:48:16.121  6940  6940 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-11 17:48:16.121  6670  6670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:48:16.121  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:48:16.121  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:48:16.121  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported,: NOT_SUPPORTED
08-11 17:48:16.121  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:48:16.121  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 17:48:16.121  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 17:48:16.121  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 17:48:16.121  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 17:48:16.121  6670  6670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:48:16.121  6670  6670 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-11 17:48:16.122  7030  7424 V FormManager: Network unavailable.
08-11 17:48:16.123  1036  1539 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-11 17:48:16.124  6940  6940 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-11 17:48:16.127  6940  6940 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-11 17:48:16.127  6940  6940 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-11 17:48:16.127  6940  6940 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-11 17:48:16.128  6940  6940 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-11 17:48:16.128  6940  6940 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-11 17:48:16.128  6940  6940 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-11 17:48:16.128  6940  6940 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-11 17:48:16.137  1036  1539 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-11 17:48:16.137  1036  1539 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-11 17:48:16.140  6922  6922 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-11 17:48:16.143  6940  6940 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-11 17:48:16.144  1036  1539 D WifiStateMachine: enableVerboseLogging : level 2
,08-11 17:48:16.144  1036  1539 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-11 17:48:16.146  1036  1539 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-11 17:48:16.146  1036  1539 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-11 17:48:16.146  7030  7428 W FormManager: Network not available. Please check & try again.
08-11 17:48:16.149  6940  6940 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-11 17:48:16.150  1036  1539 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-11 17:48:16.150  1036  1539 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-11 17:48:16.150  1036  1539 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-11 17:48:16.151  1036  1539 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-11 17:48:16.151  1036  1539 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-11 17:48:16.151  1036  1539 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-11 17:48:16.152  1036  1539 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-11 17:48:16.152  1036  1539 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-11 17:48:16.152  1036  1539 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-11 17:48:16.152  1036  1539 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-11 17:48:16.153  1036  1539 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-11 17:48:16.155  1036  1539 D WifiStateMachine: Setting OUI to DA-A1-19
08-11 17:48:16.155  1036  1539 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-11 17:48:16.155  1036  1539 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-11 17:48:16.155  1036  1539 D WifiNative-HAL: Setting external_sim to 1
08-11 17:48:16.155  1036  1539 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-11 17:48:16.155  1036  1539 D WifiNative-wlan0: SET external_sim 1: returned true
08-11 17:48:16.156  1036  1539 I WifiNative-HAL: startHal
08-11 17:48:16.156  1036  1539 D wifi    : setting scan oui 0xaf6a0a40
08-11 17:48:16.156  1036  1539 D WifiStateMachine: Setting OUI to DA-A1-19
08-11 17:48:16.156  1036  1539 I WifiNative-HAL: startHal
08-11 17:48:16.156  1036  1539 D wifi    : setting scan oui 0xaf6a0a40
08-11 17:48:16.156  1036  1539 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
,08-11 17:48:16.157  1036  1539 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-11 17:48:16.157  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-11 17:48:16.157  7342  7342 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-11 17:48:16.157  1036  1539 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-11 17:48:16.157  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-11 17:48:16.158  7342  7342 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-11 17:48:16.158  1036  1539 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-11 17:48:16.158  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-11 17:48:16.158  7342  7342 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-11 17:48:16.158  1036  1539 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-11 17:48:16.158  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-11 17:48:16.158  7342  7342 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-11 17:48:16.159  1036  1539 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-11 17:48:16.159  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-11 17:48:16.159  7342  7342 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-11 17:48:16.159  1036  1539 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-11 17:48:16.159  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-11 17:48:16.159  7342  7342 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-11 17:48:16.160  1036  1539 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-11 17:48:16.160  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-11 17:48:16.160  7342  7342 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-11 17:48:16.160  1036  1539 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-11 17:48:16.161  1036  1539 E WifiNative: : [175,072,943 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-11 17:48:16.161  1036  1539 D WifiNative-wlan0: doBoolean: RECONNECT
08-11 17:48:16.161  1944  1944 D WfdsService: Supplicant Connection state is changed : true
08-11 17:48:16.161  1944  2276 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-11 17:48:16.162  1944  2276 D WfdsService: Set the WFDS Monitor: true
08-11 17:48:16.162  1944  2276 D WfdsMonitor: WfdsMonitorThread create
08-11 17:48:16.162  1036  1539 D WifiNative-wlan0: RECONNECT: returned true
08-11 17:48:16.162  1036  1539 D WifiNative-wlan0: doString: [STATUS]
08-11 17:48:16.162  1944  2276 D WfdsMonitor: WFDS Monitor is created and started
08-11 17:48:16.162  1944  2276 D WfdsService: WiFi: Supplicant connection re-established
08-11 17:48:16.162  1036  7426 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-11 17:48:16.162  1036  7426 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-11 17:48:16.163  1944  7430 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-11 17:48:16.164  1944  7430 E CtrlSupplicant: Succeed to open control connection
08-11 17:48:16.165  1944  7430 E CtrlSupplicant: Succeed to open monitor connection
08-11 17:48:16.165  1036  1539 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-11 17:48:16.165  1036  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-11 17:48:16.166  1944  7430 D WfdsMonitor: Supplicant connection established
08-11 17:48:16.166  1944  2276 D WfdsService: Connected to the supplicant for wfds
08-11 17:48:16.166  1036  1539 D WifiNative-wlan0: SET ps 1: returned true
08-11 17:48:16.166  1036  1538 D LGWifiP2pSer,vice: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,08-11 17:48:16.168   318   894 D CommandListener: Setting iface cfg
08-11 17:48:16.168   318   894 D CommandListener: Trying to bring up p2p0
08-11 17:48:16.168  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
08-11 17:48:16.169  1036  1538 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-11 17:48:16.169  1036  1538 D LGWifiP2pService: P2pEnablingState
08-11 17:48:16.169  1036  1036 D RttService: SCAN_AVAILABLE : 3
08-11 17:48:16.169  1036  1538 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:16.169  1036  1538 D LGWifiP2pService: P2p socket connection successful
08-11 17:48:16.169  1036  1538 D LGWifiP2pService: P2pEnabledState
08-11 17:48:16.169  1036  1558 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:16.169  1036  1538 D LGWifiP2pService: sending p2p connection changed broadcast
08-11 17:48:16.169  1036  1557 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:16.169  1036  1557 I WifiNative-HAL: startHal
08-11 17:48:16.169  1036  1557 D wifi    : getting scan capabilities on interface[1] = 0xaf6a0a40
,08-11 17:48:16.169  1036  1557 D wifi    : failed to get capabilities : -3
08-11 17:48:16.169  1036  1557 E WifiScanningService: could not get scan capabilities
08-11 17:48:16.170  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-11 17:48:16.170  1944  1944 D WfdsService: WifiP2pState is changed : true
08-11 17:48:16.170  1944  2276 D WfdsService: Receive the WFDS_ENABLE Method
08-11 17:48:16.170  1944  2276 D WfdsService: Set the WFDS Monitor: true
08-11 17:48:16.170  1944  2276 D WfdsService: Connected to the supplicant for wfds
08-11 17:48:16.170  1944  2276 D WfdsJNI : doCommand: WFDS_SET TRUE
08-11 17:48:16.170  7342  7342 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-11 17:48:16.171  1944  2276 D WfdsService: selectPreferredScanChannel [36]
08-11 17:48:16.171  1944  2276 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-11 17:48:16.172  1036  1538 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-11 17:48:16.172  1036  1539 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-11 17:48:16.172  1036  1538 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
,08-11 17:48:16.172  1036  1538 D WifiNative-p2p0: doBoolean: SET device_name G3
08-11 17:48:16.173  1036  1539 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-11 17:48:16.173  1944  1944 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-11 17:48:16.173  1036  1538 D WifiNative-p2p0: SET device_name G3: returned true
08-11 17:48:16.173  1036  1538 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-11 17:48:16.173  1036  1538 D LGWifiP2pService: before postfix = G3
08-11 17:48:16.173  4365  4365 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-11 17:48:16.173  1036  1538 D WifiServerServiceExt: postfix byte check : 2
08-11 17:48:16.173  1036  1538 D LGWifiP2pService: after postfix = G3
08-11 17:48:16.173  1036  1538 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-11 17:48:16.173  1036  1539 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-11 17:48:16.173  1944  1944 D WfdsService: isConnected: false
08-11 17:48:16.173  4365  4365 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-11 17:48:16.173  1036  1539 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-11 17:48:16.174  1036  1538 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-11 17:48:16.174  7030  7429 V FormManager: Network unavailable.
08-11 17:48:16.174  1036  1538 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-11 17:48:16.174  1036  1539 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-11 17:48:16.174  1036  1538 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-11 17:48:16.174  1036  1538 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-11 17:48:16.174  1036  1539 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-11 17:48:16.175  1036  1539 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-11 17:48:16.175  1036  1538 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-11 17:48:16.175  1036  1539 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-11 17:48:16.175  1036  1538 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-11 17:48:16.175  7342  7342 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-11 17:48:16.175  1036  1538 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-11 17:48:16.175  1036  1538 D WifiNative-HAL: p2pGetDeviceAddress
08-11 17:48:16.175  4365  4365 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-11 17:48:16.175  1036  1538 D WifiNative-HAL: p2pGetDeviceAddress returning 
08-11 17:48:16.176  1036  1538 D LGWifiP2pService: DeviceAddress: 
08-11 17:48:16.176  1036  1538 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-11 17:48:16.176  1036  1539 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-11 17:48:16.176  1036  1539 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-11 17:48:16.176  1944  1944 I WfdStateTracker: handleP2pThisDeviceChanged
08-11 17:48:16.177  1944  1944 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-11 17:48:16.177  1944  1944 D WfdsService: Update P2p Interface State: 3
08-11 17:48:16.177  1036  1539 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-11 17:48:16.177  1036  1539 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-11 17:48:16.177  1036  1538 D WifiNative-p2p0: P2P_FLUSH: returned true
08-11 17:48:16.177  7342  7342 E wpa_supplicant: disconnect_rssi_lvl: -100
08-11 17:48:16.177  1036  1538 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
,08-11 17:48:16.177  1036  1538 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-11 17:48:16.178  1036  1538 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-11 17:48:16.178  1036  1539 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-11 17:48:16.179  1036  1539 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-11 17:48:16.179  1036  1539 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-11 17:48:16.179  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
,08-11 17:48:16.179  4365  4365 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-11 17:48:16.180  1036  1538 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-11 17:48:16.180  1036  1538 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
,08-11 17:48:16.184  7030  7429 V FormManager: Network unavailable.
08-11 17:48:16.186  4365  7431 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-11 17:48:16.188  4365  7432 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-11 17:48:16.188  4365  7432 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-11 17:48:16.191  1036  1538 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-11 17:48:16.191  1036  1538 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-11 17:48:16.191  7342  7342 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-11 17:48:16.192  7342  7342 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-11 17:48:16.193  1036  7426 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-11 17:48:16.193  1036  7426 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-11 17:48:16.193  1036  7426 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-11 17:48:16.193  1036  7426 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-11 17:48:16.193  7342  7342 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
,08-11 17:48:16.193  7342  7342 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 17:48:16.193  1036  1539 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-11 17:48:16.194  7342  7342 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 17:48:16.194  1036  1539 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
,08-11 17:48:16.194  1036  1539 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-11 17:48:16.195  1036  1539 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-11 17:48:16.195  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-11 17:48:16.195  1944  7430 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-11 17:48:16.195  7342  7342 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-11 17:48:16.195  1944  7430 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-11 17:48:16.195  7342  7342 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-11 17:48:16.195  1036  7426 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-11 17:48:16.195  1036  7426 E WifiMonitor: WifiMonitor:p2p0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 17:48:16.195  1036  7426 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 17:48:16.195  1036  7426 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 17:48:16.195  1036  7426 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-11 17:48:16.195  1036  7426 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 17:48:16.195  1036  7426 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 17:48:16.195  1036  7426 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 17:48:16.195  1036  7426 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-11 17:48:16.195  1036  7426 E WifiMonitor: WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-11 17:48:16.196  1036  7426 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-11 17:48:16.196  1036  7426 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-11 17:48:16.196  1036  1539 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-11 17:48:16.196  1036  1539 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-11 17:48:16.196  1036  1539 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-11 17:48:16.196  1036  1539 D WifiNative-wlan0: doBoolean: SCAN
08-11 17:48:16.197  7342  7342 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-11 17:48:16.197  1036  1539 D WifiNative-wlan0: SCAN: returned true
08-11 17:48:16.197  1036  7426 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-11 17:48:16.198  1036  7426 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-11 17:48:16.198  1036  7426 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-11 17:48:16.198  1036  7426 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-11 17:48:16.198  1036  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=175110  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-11 17:48:16.226  1036  1905 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7433 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-11 17:48:16.228  1036  1538 D LGWifiP2pService: InactiveState
08-11 17:48:16.228  1036  1538 D LGWifiP2pService: InactiveState{ when=-50ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:16.228  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=-50ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:16.228  1036  1538 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
,08-11 17:48:16.229  1036  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=175141  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-11 17:48:16.230  1036  1539 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-11 17:48:16.230  1036  1539 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-11 17:48:16.231  1036  1539 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-11 17:48:16.232  7342  7342 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-11 17:48:16.232  1036  1539 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-11 17:48:16.232  1036  1539 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-11 17:48:16.233  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 17:48:16.233  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 17:48:16.233  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-11 17:48:16.233  7342  7342 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-11 17:48:16.234  1036  7426 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-11 17:48:16.234  1036  7426 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-11 17:48:16.234  1036  7426 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-11 17:48:16.234  1036  7426 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-11 17:48:16.234  1944  7430 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-11 17:48:16.234  7342  7342 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-11 17:48:16.235  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-11 17:48:16.235  7342  7342 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 17:48:16.235  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-11 17:48:16.235  1036  7426 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-11 17:48:16.235  1036  7426 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 17:48:16.235  1036  7426 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 17:48:16.235  1036  7426 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 17:48:16.235  7342  7342 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 17:48:16.236  1944  7430 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-11 17:48:16.236  1944  7430 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-11 17:48:16.236  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 17:48:16.236  1036  1538 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-11 17:48:16.236  1036  1538 D LGWifiP2pService: InactiveState{ when=-43ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:16.236  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=-43ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:16.237  1036  7426 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD],
08-11 17:48:16.237  1036  1538 D LGWifiP2pService: InactiveState{ when=-9ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:16.237  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:16.237  1036  1538 D LGWifiP2pService: DefaultState{ when=-9ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:16.237  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-11 17:48:16.237  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-11 17:48:16.237  1036  1538 D LGWifiP2pService: InactiveState{ when=-9ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:16.237  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:16.237  1036  1538 D LGWifiP2pService: DefaultState{ when=-9ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:16.237  1036  1538 D LGWifiP2pService: InactiveState{ when=-9ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:16.237  1036  7426 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 17:48:16.237  1036  7426 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 17:48:16.238  1036  7426 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 17:48:16.238  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:16.238  1036  1538 D LGWifiP2pService: DefaultState{ when=-10ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:16.238  1036  1538 D LGWifiP2pService: InactiveState{ when=-10ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:16.238  1944  2276 W WfdsService: DefaultState - msg [9441285] is not handled
08-11 17:48:16.238  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:16.238  1036  1538 D LGWifiP2pService: DefaultState{ when=-10ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:16.238  1036  1036 E WifiServerServiceExt: No p2p device connected
,08-11 17:48:16.330  7433  7433 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-11 17:48:16.330  7433  7433 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-11 17:48:16.344  7433  7433 V [BNRBootReceiver]: Boot Receiver Return
,08-11 17:48:16.345  7433  7433 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-11 17:48:16.351  6495  6495 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-11 17:48:16.363  6940  6940 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-11 17:48:16.377  6940  6940 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-11 17:48:16.403  6989  6989 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-11 17:48:16.404  6989  6989 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-11 17:48:16.405  6989  6989 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-11 17:48:16.410  1036  1947 I ActivityManager: Killing 6962:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-11 17:48:16.470  1036  2008 W libprocessgroup: failed to open /acct/uid_10037/pid_6962/cgroup.procs: No such file or directory
,08-11 17:48:16.557  6774  7120 D UEI.SmartControl: Internal timer expired: 2
,08-11 17:48:16.557  6774  7120 D UEI.SmartControl: unbind internal service
,08-11 17:48:16.613  6774  7114 D serial_port: close(fd = 24)
,08-11 17:48:16.620  6774  7114 I UEI.SmartControl: Serial port is closed.
08-11 17:48:19.372  1036  1052 D WifiServiceImplEx: setWifiEnabled: false pid=6670, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-11 17:48:19.373  1036  1052 D WifiService: setWifiEnabled: false pid=6670, uid=10118
08-11 17:48:19.373  1036  1052 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-11 17:48:19.391  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-11 17:48:19.391  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-11 17:48:19.391  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,08-11 17:48:19.394  1036  1539 E WifiStateMachine:  DisconnectedState CMD_STOP_SUPPLICANT 0 0
08-11 17:48:19.395  1036  1539 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-11 17:48:19.395  1036  1539 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-11 17:48:19.395  1036  1539 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-11 17:48:19.404  1036  1545 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-11 17:48:19.407  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
08-11 17:48:19.407  1036  1036 D RttService: SCAN_AVAILABLE : 1
08-11 17:48:19.407  1036  1557 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:19.407  1036  1558 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:19.408  1036  1538 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:19.408  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:19.408  1036  1538 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@18baba4b
08-11 17:48:19.408  1036  1538 D LGWifiP2pService: P2pDisablingState
08-11 17:48:19.408  1036  1538 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:19.408  1036  1538 D LGWifiP2pService: p2p socket connection lost
08-11 17:48:19.408  1036  1538 D LGWifiP2pService: P2pDisabledState
08-11 17:48:19.410  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-11 17:48:19.411  1944  1944 D WfdsService: WifiP2pState is changed : false
08-11 17:48:19.411  1944  2276 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-11 17:48:19.411  1944  2276 D WfdsService: Set the WFDS Monitor: false
08-11 17:48:19.412  1944  2276 D WfdsMonitor: WFDS Monitor is stopped
08-11 17:48:19.412  1944  2276 D WfdsService: STATE : WfdsDisabledState - enter
08-11 17:48:19.412  1944  7430 D CtrlSupplicant: Received on exit socket, terminate
08-11 17:48:19.412  1944  7430 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-11 17:48:19.413  1944  7430 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-11 17:48:19.413  1944  7430 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-11 17:48:19.413  1944  2277 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-11 17:48:19.419  1944  2276 W WfdsService: DefaultState - msg [9445378] is not handled
,08-11 17:48:19.423  1036  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-11 17:48:19.425   318   894 D CommandListener: Clearing all IP addresses on wlan0
08-11 17:48:19.430  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-11 17:48:19.430  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-11 17:48:19.437  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 17:48:19.438  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-11 17:48:19.438  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 17:48:19.439  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 17:48:19.439  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-11 17:48:19.444  1036  1036 D WifiHS20: hidePasspointNotification off =false
,08-11 17:48:19.452  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 17:48:19.452  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 17:48:19.452  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-11 17:48:19.453  1036  1539 D WifiNative-p2p0: doBoolean: TERMINATE
08-11 17:48:19.453  1036  1539 D WifiNative-p2p0: TERMINATE: returned true
08-11 17:48:19.453  1036  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-11 17:48:19.453  1036  1539 E WifiStateMachine: useWiFiOffloading() : false
08-11 17:48:19.453  1036  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-11 17:48:19.455  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-11 17:48:19.459  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-11 17:48:19.459  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-11 17:48:19.466  6670  6670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:48:19.466  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:48:19.466  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:48:19.466  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 17:48:19.466  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 17:48:19.466  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 17:48:19.466  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 17:48:19.466  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 17:48:19.466  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 17:48:19.466  6670  6670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:48:19.466  6670  6670 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 17:48:19.468  6670  6670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:48:19.468  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:48:19.468  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:48:19.468  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 17:48:19.468  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 17:48:19.468  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 17:48:19.468  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 17:48:19.468  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 17:48:19.468  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 17:48:19.468  6670  6670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:48:19.468  6670  6670 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 17:48:19.469  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-11 17:48:19.470  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-11 17:48:19.470  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-11 17:48:19.471  6670  6670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:48:19.471  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:48:19.471  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:48:19.471  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 17:48:19.471  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 17:48:19.471  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
,08-11 17:48:19.471  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 17:48:19.471  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 17:48:19.471  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 17:48:19.471  6670  6670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:48:19.471  6670  6670 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 17:48:19.473  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-11 17:48:19.479  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 17:48:19.481  6495  6495 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-11 17:48:19.489  6922  6922 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-11 17:48:19.489  6922  6922 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-11 17:48:19.489  6922  6922 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-11 17:48:19.499  6940  6940 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-11 17:48:19.507  7342  7342 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-11 17:48:19.507  7342  7342 I wpa_supplicant: monitor socket send errors count : 1
08-11 17:48:19.507  7342  7342 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1944-4\x00 that cannot receive messages
08-11 17:48:19.509  1036  7426 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-11 17:48:19.509  1036  7426 D WifiMonitor: Dropping event because (p2p0) is stopped
,08-11 17:48:19.519  6940  6940 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-11 17:48:19.529  7342  7342 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-11 17:48:19.530  7342  7342 W wpa_supplicant: USIM:  scard_deinit function
,08-11 17:48:19.535  1036  7426 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-11 17:48:19.535  1036  7426 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-11 17:48:19.536  1036  7426 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-11 17:48:19.536  1036  7426 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-11 17:48:19.538  1036  1119 D Tethering: InitialState.processMessage what=4
08-11 17:48:19.538  1036  1539 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=178450
08-11 17:48:19.539  1036  1539 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=178451
08-11 17:48:19.540  1036  7426 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-11 17:48:19.540  1036  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-11 17:48:19.540  1036  7426 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-11 17:48:19.542  1036  1539 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-11 17:48:19.544  1036  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-11 17:48:19.548  1036  1539 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=178460  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-11 17:48:19.549  1036  1539 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=178461  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-11 17:48:19.551  6989  6989 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-11 17:48:19.552  6989  6989 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-11 17:48:19.554  6989  6989 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-11 17:48:19.557  6495  6495 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-11 17:48:19.560  6922  6922 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-11 17:48:19.560  6922  6922 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-11 17:48:19.560  6922  6922 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-11 17:48:19.563  6940  6940 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-11 17:48:19.567  6940  6940 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-11 17:48:19.572  6989  6989 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-11 17:48:19.573  6989  6989 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-11 17:48:19.574  6989  6989 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-11 17:48:19.581  6922  6922 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-11 17:48:19.583  6940  6940 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-11 17:48:19.589  7030  7479 W FormManager: Network not available. Please check & try again.
08-11 17:48:19.590  6940  6940 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-11 17:48:19.596  7030  7480 V FormManager: Network unavailable.
08-11 17:48:19.601  7030  7480 V FormManager: Network unavailable.
,08-11 17:48:19.603  6940  6940 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-11 17:48:19.603  6940  6940 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-11 17:48:19.603  6940  6940 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-11 17:48:19.603  6940  6940 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-11 17:48:19.605  6940  6940 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-11 17:48:19.607  6940  6940 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-11 17:48:19.607  6940  6940 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-11 17:48:19.607  6940  6940 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-11 17:48:19.607  6940  6940 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-11 17:48:19.607  6940  6940 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-11 17:48:19.607  6940  6940 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-11 17:48:19.616  7342  7342 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-11 17:48:19.616  1036  7426 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-11 17:48:19.616  1036  7426 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-TERMINATING 
08-11 17:48:19.616  1036  7426 D WifiMonitor: Disconnecting from the supplicant, no more events
,08-11 17:48:19.617  1036  1539 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 33 0
,08-11 17:48:19.720  1944  1944 D WfdsService: Supplicant Connection state is changed : false
08-11 17:48:19.721  1944  2276 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-11 17:48:19.721  1944  2276 D WfdsService: Set the WFDS Monitor: false
08-11 17:48:19.721  1944  2276 D WfdsMonitor: WFDS Monitor is stopped
08-11 17:48:19.722  1036  1539 D WifiOffDelayIfNotUsed: stopMonitoring
08-11 17:48:19.722  1036  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-11 17:48:19.722  1036  1539 E WifiStateMachine: useWiFiOffloading() : false
08-11 17:48:19.722  1036  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-11 17:48:19.724  4365  4365 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-11 17:48:19.725  4365  4365 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-11 17:48:19.726  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 17:48:19.729  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-11 17:48:19.729  2477  2477 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 17:48:19.730  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:48:19.730  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-11 17:48:19.731  1036  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-11 17:48:19.731  1036  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-11 17:48:19.731  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:48:19.732  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:48:19.734  4365  4365 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-11 17:48:19.740  4365  4365 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-11 17:48:19.755  6922  6922 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
,08-11 17:48:19.755  6922  6922 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-11 17:48:19.755  6922  6922 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-11 17:48:19.755  4365  7482 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-11 17:48:19.761  6940  6940 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-11 17:48:19.764  4365  7484 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-11 17:48:19.764  4365  7484 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-11 17:48:19.767  7030  7485 W FormManager: Network not available. Please check & try again.
,08-11 17:48:19.772  7030  7486 V FormManager: Network unavailable.
08-11 17:48:19.775  7030  7486 V FormManager: Network unavailable.
08-11 17:48:19.775  6940  6940 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-11 17:48:19.809  7298  7318 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-11 17:48:20.908  1036  1051 I ActivityManager: Killing 7006:com.lge.settings.easy/1000 (adj 15): empty #17
,08-11 17:48:20.939  1036  1577 W libprocessgroup: failed to open /acct/uid_1000/pid_7006/cgroup.procs: No such file or directory
,08-11 17:48:24.396  1036  1940 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-11 17:48:24.397  1036  1940 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-11 17:48:24.415  1036  1538 D LGWifiP2pService: P2pDisabledState{ when=-7ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:24.416  1036  1538 D LGWifiP2pService: DefaultState{ when=-8ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-11 17:48:24.436  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-11 17:48:24.436  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-11 17:48:24.436  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-11 17:48:24.437  1036  1119 D BluetoothManagerService: Message: 1
08-11 17:48:24.437  1036  1119 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-11 17:48:24.454  1036  1539 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
08-11 17:48:24.455  1036  1539 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-11 17:48:24.483  1036  1119 D BluetoothManagerService: Message: 20
08-11 17:48:24.484  1036  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@320d7cac:true
,08-11 17:48:24.487  7060  7060 D BluetoothAdapterState: make
08-11 17:48:24.492  7060  7060 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-11 17:48:24.492  7060  7060 I bluedroid-qcom: init
08-11 17:48:24.493  7060  7499 I BluetoothAdapterState: Entering OffState
08-11 17:48:24.495  7060  7060 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-11 17:48:24.495  7060  7060 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-11 17:48:24.495  7060  7060 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-11 17:48:24.495  7060  7060 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-11 17:48:24.495  7060  7060 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
,08-11 17:48:24.499  7060  7060 I bluedroid-qcom: get_profile_interface socket
08-11 17:48:24.499  7060  7060 I bluedroid-qcom: get_profile_interface map_client
08-11 17:48:24.484  7502  7502 W bdaddr_loader: type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-11 17:48:24.504  7060  7503 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-11 17:48:24.507  7060  7503 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-11 17:48:24.494  7502  7502 W bdaddr_loader: type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-11 17:48:24.516  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-11 17:48:24.516  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-11 17:48:24.521  7502  7502 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-11 17:48:24.521  7502  7502 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-11 17:48:24.521  7502  7502 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-11 17:48:24.524  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-11 17:48:24.524  1036  1119 D BluetoothManagerService: Message: 40
08-11 17:48:24.524  1036  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-11 17:48:24.525  7060  7076 I bluedroid-qcom: config_hci_snoop_log
08-11 17:48:24.526  1036  1119 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-11 17:48:24.527  1036  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-11 17:48:24.527  7502  7502 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-11 17:48:24.534  7502  7502 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-11 17:48:24.534  7502  7502 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-11 17:48:24.540  7060  7499 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-11 17:48:24.540  7060  7503 D BluetoothAdapterProperties: Name is: G3
08-11 17:48:24.540  7060  7499 D BluetoothAdapterProperties: Setting state to 11
08-11 17:48:24.541  7060  7499 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-11 17:48:24.541  1036  1119 D BluetoothManagerService: Message: 60
08-11 17:48:24.541  1036  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-11 17:48:24.541  1036  1119 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-11 17:48:24.543  7060  7499 I LGBluetoothServiceJni: classInitNative: succeeds
08-11 17:48:24.547  1944  1944 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-11 17:48:24.550  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-11 17:48:24.558  6940  6940 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-11 17:48:24.559  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 17:48:24.564  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:48:24.566  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:48:24.570  7060  7060 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-11 17:48:24.571  7060  7060 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-11 17:48:24.571  7060  7060 V BluetoothPbapReceiver: ***********state = 11
08-11 17:48:24.573  7060  7499 D BluetoothBondStateMachine: make
08-11 17:48:24.576  2184  2184 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-11 17:48:24.576  7060  7499 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@385074ab
08-11 17:48:24.577  7060  7499 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-11 17:48:24.577  7060  7499 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@385074ab
08-11 17:48:24.577  7060  7499 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-11 17:48:24.577  7060  7499 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
,08-11 17:48:24.581  7060  7519 I BluetoothBondStateMachine: StableState(): Entering Off State
08-11 17:48:24.584  7060  7499 E BluetoothAdapterService: File transfer profiles supported!!
08-11 17:48:24.614  1036  1789 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7523 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-11 17:48:24.619  7060  7060 D HeadsetService: Received start request. Starting profile...
08-11 17:48:24.619  7060  7499 E BluetoothAdapterService: File transfer profiles supported!!
08-11 17:48:24.619  7060  7060 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-11 17:48:24.619  7060  7060 D LGBluetoothHfpAdapter: Version 1.6
08-11 17:48:24.622  7060  7060 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-11 17:48:24.623  7060  7060 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-11 17:48:24.623  7060  7060 D HeadsetStateMachine: make
08-11 17:48:24.624  7060  7499 E BluetoothAdapterService: File transfer profiles supported!!
08-11 17:48:24.629  7060  7499 E BluetoothAdapterService: File transfer profiles supported!!
08-11 17:48:24.636  7060  7499 E BluetoothAdapterService: File transfer profiles supported!!
08-11 17:48:24.641  7060  7499 E BluetoothAdapterService: File transfer profiles supported!!
,08-11 17:48:24.647  7060  7499 E BluetoothAdapterService: File transfer profiles supported!!
08-11 17:48:24.653  7060  7060 D LgDataFeature: LgDataFeature() Constructor: none
08-11 17:48:24.653  7060  7060 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-11 17:48:24.658  7060  7060 D HeadsetStateMachine: max_hf_connections = 1
08-11 17:48:24.658  7060  7060 I bluedroid-qcom: get_profile_interface handsfree
08-11 17:48:24.660  7060  7060 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-11 17:48:24.660   322  2157 V AudioPolicyService: registerClient() client 0xb1021bc0, uid 1002
08-11 17:48:24.661   322  1383 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-11 17:48:24.661   322  1383 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-11 17:48:24.661   322  1383 V AudioPolicyManagerEx: getOutput() returns output 2
08-11 17:48:24.661  7060  7060 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-11 17:48:24.664   322   322 V AudioFlinger: registerClient() client 0xb5581610, pid 7060
08-11 17:48:24.664   322  1378 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-11 17:48:24.664   322  1378 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-11 17:48:24.664  7060  7060 V ToneGenerator: Create Track: 0xb4928a80
08-11 17:48:24.664  7060  7060 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-11 17:48:24.664  7060  7060 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-11 17:48:24.664   322  2157 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-11 17:48:24.664   322  2157 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-11 17:48:24.664   322  2157 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-11 17:48:24.664   322  2157 V AudioPolicyManagerEx: getOutput() returns output 2
08-11 17:48:24.665  7060  7060 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-11 17:48:24.665  1603  2272 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-11 17:48:24.665  1603  2272 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-11 17:48:24.665  1036  1052 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-11 17:48:24.665  7060  7517 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-11 17:48:24.665  1036  1052 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-11 17:48:24.665  7060  7517 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-11 17:48:24.665  1856  1871 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-11 17:48:24.665  1856  1871 V AudioSystem: ioConfigChanged() opening already existing output! 2
,08-11 17:48:24.665  3521  3541 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-11 17:48:24.665  3521  3541 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-11 17:48:24.665   322  1379 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-11 17:48:24.665   322  1379 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-11 17:48:24.665  1603  1623 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-11 17:48:24.665  1603  1623 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-11 17:48:24.665   322  1384 I AudioFlinger: isAudioPlaybackHookOn() false
08-11 17:48:24.665  1856  1872 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-11 17:48:24.665  1856  1872 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-11 17:48:24.665   322  1783 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-11 17:48:24.665  1036  1789 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-11 17:48:24.665   322  1783 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-11 17:48:24.665  3521  3540 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-11 17:48:24.665   322  1783 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-11 17:48:24.665  1036  1789 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-11 17:48:24.665  3521  3540 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-11 17:48:24.666   322  1783 V AudioPolicyManagerEx: getOutput() returns output 2
08-11 17:48:24.666  7060  7060 V AudioSystem: getLatency() output 2, latency 50
08-11 17:48:24.666  7060  7517 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-11 17:48:24.666  7060  7060 V AudioSystem: getFrameCount() output 2, frameCount 960
08-11 17:48:24.666  7060  7517 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-11 17:48:24.666  7060  7060 V AudioTrack: createTrack_l() output 2 afLatency 50
08-11 17:48:24.666   322  2157 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-11 17:48:24.666   322  2157 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-11 17:48:24.666   322  2157 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-11 17:48:24.666   322  2157 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-11 17:48:24.666   322  2157 V AudioFlinger: createTrack() lSessionId: 22
08-11 17:48:24.668  7060  7060 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-11 17:48:24.668   322  2157 V AudioFlinger: acquiring 22 from 7060, for 7060
08-11 17:48:24.668   322  2157 V AudioFlinger:  added new entry for 22
08-11 17:48:24.668  7060  7060 V ToneGenerator: ToneGenerator INIT OK, time: 183595
08-11 17:48:24.669  7060  7060 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@385074ab
,08-11 17:48:24.670  7060  7060 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@385074ab
,08-11 17:48:24.672  7060  7060 D A2dpService: Received start request. Starting profile...
08-11 17:48:24.673  7060  7060 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-11 17:48:24.674  7060  7060 V Avrcp   : make
08-11 17:48:24.674  7060  7533 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-11 17:48:24.674  7060  7533 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-11 17:48:24.674  7060  7533 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-11 17:48:24.674  7060  7060 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-11 17:48:24.674  7060  7060 I bluedroid-qcom: get_profile_interface avrcp
08-11 17:48:24.674  7060  7533 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-11 17:48:24.674   322  1383 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7060
08-11 17:48:24.675  7060  7499 V LGMDMManager: Create singleton instance
08-11 17:48:24.676   322  1383 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-11 17:48:24.676   322  1383 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-11 17:48:24.676   322  1383 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-11 17:48:24.676   322  1383 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-11 17:48:24.676   322  1383 V voice   : voice_set_parameters: exit with code(0)
08-11 17:48:24.676   322  1383 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-11 17:48:24.676   322  1383 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-11 17:48:24.676   322  1383 V msm8974_platform: platform_set_parameters: exit with code(0)
08-11 17:48:24.676   322  1383 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-11 17:48:24.676   322  1383 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-11 17:48:24.676   322  1383 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-11 17:48:24.676  7060  7533 V ToneGenerator: ToneGenerator destructor
08-11 17:48:24.676  7060  7533 V ToneGenerator: stopTone
08-11 17:48:24.676  7060  7533 V ToneGenerator: Delete Track: 0xb4928a80
08-11 17:48:24.677  7060  7499 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-11 17:48:24.677  7060  7533 V AudioTrack: ~AudioTrack, releasing session id from 7060 on behalf of 7060
08-11 17:48:24.677   322  1384 V AudioPolicyService: AudioCommandThread() adding release output 2
08-11 17:48:24.677   322  1384 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-11 17:48:24.677   322  1275 V AudioPolicyService: AudioCommandThread() waking up
08-11 17:48:24.677   322  1275 V AudioPolicyService: AudioCommandThread() processing release output 2
08-11 17:48:24.677   322  1275 V AudioPolicyManager: releaseOutput() 2
08-11 17:48:24.677   322  1275 V AudioPolicyService: AudioCommandThread() going to sleep
08-11 17:48:24.677   322  1384 V AudioFlinger: PlaybackThread::Track destructor
08-11 17:48:24.677   322  1384 V AudioFlinger: removeClient_l() pid 7060, calling pid 322
08-11 17:48:24.677   322  1783 V AudioFlinger: releasing 22 from 7060 for 7060
08-11 17:48:24.677   322  1783 V AudioFlinger:  decremented refcount to 0
08-11 17:48:24.677   322  1783 V AudioFlinger: purging stale effects
08-11 17:48:24.683  7060  7060 V AudioManager: registerRemoteController: size of Media player list: 0
,08-11 17:48:24.685  7060  7060 E AudioManager: No RCC entry present to update
08-11 17:48:24.685  7060  7060 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-11 17:48:24.689  7060  7060 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-11 17:48:24.690  7060  7060 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-11 17:48:24.690  7060  7060 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-11 17:48:24.693  7060  7060 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-11 17:48:24.824  7523  7523 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,08-11 17:48:24.825  7523  7523 W LG Account v2.2: No ProfileInfo entries
08-11 17:48:24.826  7523  7523 I LG Account v2.2: isEnabled: false
08-11 17:48:24.826  7523  7523 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-11 17:48:24.826  7523  7523 I Feature : [Lifetracker]Country: EU
08-11 17:48:24.826  7523  7523 I Feature : [Lifetracker]Operator: OPEN
08-11 17:48:24.827  7523  7523 I Feature : [Lifetracker]Ranking support: false
08-11 17:48:24.827  7523  7523 I Feature : [Lifetracker]Comfort support: false
08-11 17:48:24.827  7523  7523 I Feature : [Lifetracker]Accessory: true
08-11 17:48:24.827  7523  7523 I Feature : [Lifetracker]Health device: true
08-11 17:48:24.827  7523  7523 I Feature : [Lifetracker]Extra Pedometer: false
08-11 17:48:24.827  7523  7523 I Feature : [Lifetracker]Blood glucose device: false
,08-11 17:48:24.828  7523  7523 I Feature : [Lifetracker]Device Number: 3
08-11 17:48:24.834  1036  1052 V SIM_STK : Menu title from STK is T-Mobile
08-11 17:48:24.834  1036  1052 V SIM_STK : Menu title from STK is T-Mobile
08-11 17:48:24.843  6940  6940 D BluetoothPermissionRequest: onReceive
,08-11 17:48:24.848  6940  6940 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-11 17:48:24.955  1036  2053 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-11 17:48:24.967  7060  7060 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-11 17:48:24.972  7060  7060 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,08-11 17:48:24.974  7060  7060 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
,08-11 17:48:24.974  7060  7060 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-11 17:48:24.975  7060  7060 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-11 17:48:24.975  7060  7060 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-11 17:48:24.975  7060  7060 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-11 17:48:24.975  7060  7060 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-11 17:48:24.975  7060  7060 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
,08-11 17:48:24.975  7060  7060 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-11 17:48:24.976  7060  7060 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
,08-11 17:48:24.977  7060  7060 I BluetoothA2dpServiceJni: classInitNative
08-11 17:48:24.977  7060  7060 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-11 17:48:24.977  7060  7060 D A2dpStateMachine: make
08-11 17:48:24.979  7060  7060 I bluedroid-qcom: get_profile_interface a2dp
08-11 17:48:24.979  7060  7551 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-11 17:48:24.982  7060  7060 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-11 17:48:24.982  7060  7060 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-11 17:48:24.983  7060  7060 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@385074ab
08-11 17:48:24.984  7060  7060 I BluetoothHidServiceJni: classInitNative: succeeds
08-11 17:48:24.984  7060  7550 D A2dpStateMachine: Enter Disconnected: -2
,08-11 17:48:24.988  7060  7060 D HidService: Received start request. Starting profile...
08-11 17:48:24.989  7060  7060 I bluedroid-qcom: get_profile_interface hidhost
08-11 17:48:24.989  7060  7060 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@385074ab
08-11 17:48:24.989  7060  7060 I BluetoothHealthServiceJni: classInitNative: succeeds
08-11 17:48:24.991  7060  7060 D HealthService: Received start request. Starting profile...
08-11 17:48:24.995  7060  7060 I bluedroid-qcom: get_profile_interface health
08-11 17:48:24.995  7060  7060 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-11 17:48:24.995  7060  7060 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@385074ab
08-11 17:48:24.996  7060  7060 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-11 17:48:24.997  7060  7060 D PanService: Received start request. Starting profile...
08-11 17:48:24.997  7060  7060 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-11 17:48:24.997  7060  7060 I bluedroid-qcom: get_profile_interface pan
08-11 17:48:25.007  7060  7060 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-11 17:48:25.007  7060  7060 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@385074ab
08-11 17:48:25.010  7060  7060 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-11 17:48:25.026  7060  7060 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-11 17:48:25.027  7060  7060 D BtGatt.GattService: Received start request. Starting profile...
08-11 17:48:25.027  7060  7060 D BtGatt.GattService: start()
,08-11 17:48:25.027  7060  7060 I bluedroid-qcom: get_profile_interface gatt
08-11 17:48:25.029  7060  7060 D BtGatt.AdvertiseManager: advertise manager created
08-11 17:48:25.039  7060  7060 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@385074ab
08-11 17:48:25.041  7060  7060 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@385074ab
08-11 17:48:25.041  7060  7060 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-11 17:48:25.043  7060  7060 V BluetoothMapService: BluetoothMapBinder()
08-11 17:48:25.044  7060  7060 D BluetoothMapService: Received start request. Starting profile...
08-11 17:48:25.044  7060  7060 D BluetoothMapService: start()
,08-11 17:48:25.048  7060  7060 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-11 17:48:25.048  7060  7060 D BluetoothMapEmailAppObserver: createReceiver()
,08-11 17:48:25.050  7060  7060 D BluetoothMapEmailAppObserver: initObservers()
08-11 17:48:25.050  7060  7060 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-11 17:48:25.060  7060  7060 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@385074ab
08-11 17:48:25.060  7060  7060 D HeadsetStateMachine: Proxy object connected
08-11 17:48:25.061  7060  7060 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-11 17:48:25.061  7060  7060 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-11 17:48:25.069  7060  7060 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-11 17:48:25.070  7060  7533 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-11 17:48:25.071  7060  7533 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-11 17:48:25.072  7060  7533 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-11 17:48:25.073  7060  7060 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-11 17:48:25.078  7060  7060 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-11 17:48:25.081  7060  7060 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-11 17:48:25.085  7060  7060 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-11 17:48:25.085  7060  7060 V PanService: [BTUI] SIM Extra State :ABSENT
08-11 17:48:25.089  7060  7060 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-11 17:48:25.089  7060  7060 V BluetoothMapService: Handler(): got msg=1
08-11 17:48:25.091  7060  7499 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-11 17:48:25.091  7060  7499 I bluedroid-qcom: enable
08-11 17:48:25.091  7060  7558 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-11 17:48:25.093  7060  7499 I bt_hci_bdroid: init
08-11 17:48:25.094  7060  7060 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-11 17:48:25.095  7060  7558 I bt-btu  : btu_task pending for preload complete event
08-11 17:48:25.097  7060  7060 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-11 17:48:25.097  7060  7060 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-11 17:48:25.097  7060  7060 V BluetoothSapReceiver: SapReceiver onReceive 
08-11 17:48:25.097  7060  7060 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-11 17:48:25.097  7060  7060 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-11 17:48:25.097  7060  7499 I bt_vendor: bt-vendor : init
08-11 17:48:25.097  7060  7499 I bt_vendor: bt-vendor : get_bt_soc_type
08-11 17:48:25.097  7060  7499 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-11 17:48:25.097  7060  7499 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-11 17:48:25.097  7060  7499 D bt_userial_mct: userial_init
08-11 17:48:25.098  7060  7499 D bt_hci_bdroid: set_power 1
08-11 17:48:25.098  7060  7499 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-11 17:48:25.098  7060  7499 I bt_vendor: Starting hciattach daemon
08-11 17:48:25.098  7060  7499 I bt_vendor: try to set true
08-11 17:48:25.084  7561  7561 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-11 17:48:25.084  7561  7561 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-11 17:48:25.127  7562  7562 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-11 17:48:25.178  1036  1914 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7567 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-11 17:48:25.197  7574  7574 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-11 17:48:25.208  7580  7580 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-11 17:48:25.242  7588  7588 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-11 17:48:25.251  7567  7567 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-11 17:48:25.254  7589  7589 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-11 17:48:25.268  1036  1947 I ActivityManager: Killing 7141:com.lge.appbox.client/u0a11 (adj 15): empty #17
08-11 17:48:25.270  7590  7590 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-11 17:48:25.282  7591  7591 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-11 17:48:25.305  7593  7593 I libmdmdetect: ESOC framework not supported
08-11 17:48:25.306  7593  7593 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-11 17:48:25.320  7593  7593 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-11 17:48:25.320  7593  7593 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-11 17:48:25.320  7593  7593 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-11 17:48:25.321  7593  7593 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
,08-11 17:48:25.321  7593  7593 D bthci_qcomm_common: [BTUI]     LE: Class 2
,08-11 17:48:25.321  7593  7593 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-11 17:48:25.321  7593  7593 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-11 17:48:25.321  1036  1975 W libprocessgroup: failed to open /acct/uid_10011/pid_7141/cgroup.procs: No such file or directory
08-11 17:48:25.366  7593  7594 E QC-QMI  : qmi_client [7593] 14: failed to locate client data
08-11 17:48:25.367   466   466 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-11 17:48:25.367   466   466 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-11 17:48:25.400  7595  7595 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-11 17:48:25.423  7596  7596 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-11 17:48:25.453  7060  7499 I bt_vendor: bluetooth satus is on
08-11 17:48:25.453  7060  7499 D bt_hci_bdroid: preload
08-11 17:48:25.454  7060  7560 D bt_userial_mct: userial_open(port:0)
08-11 17:48:25.454  7060  7560 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-11 17:48:25.458  7060  7560 I bt_vendor: Done intiailizing UART
08-11 17:48:25.459  7060  7560 I bt_vendor: Done intiailizing UART
08-11 17:48:25.459  7060  7560 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
,08-11 17:48:25.459  7060  7560 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-11 17:48:25.459  7060  7558 I bt-btu  : btu_task received preload complete event
08-11 17:48:25.460  7060  7598 D bt_userial_mct: Entering userial_read_thread()
08-11 17:48:25.460  7060  7558 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-11 17:48:25.460  7060  7558 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-11 17:48:25.466  7060  7558 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-11 17:48:25.471  7060  7558 I         : BTE_InitTraceLevels -- TRC_HCI
08-11 17:48:25.472  7060  7558 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-11 17:48:25.472  7060  7558 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-11 17:48:25.472  7060  7558 I         : BTE_InitTraceLevels -- TRC_AVDT
08-11 17:48:25.472  7060  7558 I         : BTE_InitTraceLevels -- TRC_AVRC
08-11 17:48:25.472  7060  7558 I         : BTE_InitTraceLevels -- TRC_A2D
08-11 17:48:25.472  7060  7558 I         : BTE_InitTraceLevels -- TRC_BNEP
08-11 17:48:25.472  7060  7558 I         : BTE_InitTraceLevels -- TRC_BTM
08-11 17:48:25.472  7060  7558 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-11 17:48:25.472  7060  7558 I         : BTE_InitTraceLevels -- TRC_GAP
,08-11 17:48:25.472  7060  7558 I         : BTE_InitTraceLevels -- TRC_PAN
08-11 17:48:25.472  7060  7558 I         : BTE_InitTraceLevels -- TRC_SDP
08-11 17:48:25.472  7060  7558 I         : BTE_InitTraceLevels -- TRC_GATT
08-11 17:48:25.472  7060  7558 I         : BTE_InitTraceLevels -- TRC_SMP
08-11 17:48:25.472  7060  7558 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-11 17:48:25.472  7060  7558 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-11 17:48:25.559  7060  7558 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-11 17:48:25.559  7060  7558 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01e9061 
,08-11 17:48:25.559  7060  7558 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01e9061 
,08-11 17:48:25.600  7060  7503 E bt-btif : Calling BTA_HhEnable
08-11 17:48:25.600  7060  7503 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-11 17:48:25.601  7060  7503 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-11 17:48:25.605  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-11 17:48:25.605  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-11 17:48:25.606  7060  7558 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-11 17:48:25.606  7060  7558 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-11 17:48:25.606  7060  7558 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-11 17:48:25.606  7060  7558 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-11 17:48:25.606  7060  7558 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-11 17:48:25.607  7060  7503 D BluetoothAdapterProperties: Name is: G3
08-11 17:48:25.608  7060  7503 D BluetoothAdapterProperties: Scan Mode:20
08-11 17:48:25.608  7060  7503 D BluetoothAdapterProperties: Discoverable Timeout:120
08-11 17:48:25.608  7060  7503 D bt_hci_bdroid: postload
08-11 17:48:25.609  7060  7560 D bt_hci_bdroid: Used up Tx Cmd credits
08-11 17:48:25.610  7060  7503 D bte_conf: Device ID record 1 : primary
08-11 17:48:25.610  7060  7503 D bte_conf:   vendorId            = 00c4
08-11 17:48:25.610  7060  7503 D bte_conf:   vendorIdSource      = 0001
08-11 17:48:25.610  7060  7503 D bte_conf:   product             = 13a1
08-11 17:48:25.610  7060  7503 D bte_conf:   version             = 1000
08-11 17:48:25.610  7060  7503 D bte_conf:   clientExecutableURL = 
08-11 17:48:25.610  7060  7503 D bte_conf:   serviceDescription  = 
08-11 17:48:25.610  7060  7503 D bte_conf:   documentationURL    = 
08-11 17:48:25.610  7060  7503 D bte_conf: bte_load_did_conf no section named DID2.
08-11 17:48:25.611  7060  7558 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-11 17:48:25.614  7060  7499 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-11 17:48:25.614  7060  7499 D BluetoothAdapterProperties: ScanMode =  20
08-11 17:48:25.614  7060  7499 D BluetoothAdapterProperties: State =  11
08-11 17:48:25.615  7060  7499 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-11 17:48:25.615  7060  7499 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-11 17:48:25.615  7060  7499 D BluetoothAdapterProperties: Setting state to 12
08-11 17:48:25.615  7060  7499 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-11 17:48:25.620  7060  7503 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-11 17:48:25.621  7060  7503 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-11 17:48:25.614  7606  7606 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-11 17:48:25.614  7606  7606 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-11 17:48:25.634  1036  1119 D BluetoothManagerService: Message: 60
08-11 17:48:25.634  1036  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-11 17:48:25.634  1036  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
,08-11 17:48:25.638  7060  7560 D bt_hci_bdroid: Used up Tx Cmd credits
08-11 17:48:25.642  7060  7560 D bt_hci_bdroid: Used up Tx Cmd credits
08-11 17:48:25.645  7060  7560 D bt_hci_bdroid: Used up Tx Cmd credits
08-11 17:48:25.646  7060  7598 E bt_mct  : hci lib postload completed
08-11 17:48:25.650  1856  4059 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-11 17:48:25.653  7060  7499 I BluetoothAdapterState: Entering On State
08-11 17:48:25.657  7060  7558 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-11 17:48:25.657  7060  7558 W bt-smp  : Plain text(LSB ~ MSB) = d2 23 71 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-11 17:48:25.657  7060  7558 W bt-smp  : Encrypted text(LSB ~ MSB) = 5b 81 96 f4 47 7a 08 07 b4 55 20 fc 91 9e b5 45 
08-11 17:48:25.657  7060  7558 W bt-btm  : Stopping oneshot timer
08-11 17:48:25.662  7060  7503 D BluetoothAdapterProperties: Discoverable Timeout:120
08-11 17:48:25.662  7060  7503 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-11 17:48:25.670  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:48:25.670  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:48:25.670  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 17:48:25.670  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 17:48:25.670  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 17:48:25.670  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 17:48:25.670  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 17:48:25.670  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 17:48:25.676  6670  6670 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-11 17:48:25.690  7060  7558 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-11 17:48:25.690  7060  7558 W bt-smp  : Plain text(LSB ~ MSB) = 3e fc 5a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-11 17:48:25.690  7060  7558 W bt-smp  : Encrypted text(LSB ~ MSB) = 0a f0 1d 82 cc 0c c1 0a 91 01 8b bf 24 09 0b d4 
,08-11 17:48:25.693  7060  7558 W bt-btm  : Stopping oneshot timer
08-11 17:48:25.694  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:48:25.694  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:48:25.694  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 17:48:25.694  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 17:48:25.694  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 17:48:25.694  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 17:48:25.694  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 17:48:25.694  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 17:48:25.701  6670  6670 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 17:48:25.706  7060  7558 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-11 17:48:25.706  7060  7558 W bt-smp  : Plain text(LSB ~ MSB) = e5 d4 4a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-11 17:48:25.706  7060  7558 W bt-smp  : Encrypted text(LSB ~ MSB) = 50 92 bc 21 b5 11 f8 77 3e 25 c5 7d d5 cd ac 17 
,08-11 17:48:25.708  7060  7558 W bt-btm  : Stopping oneshot timer
08-11 17:48:25.713  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:48:25.713  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:48:25.713  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 17:48:25.713  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 17:48:25.713  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 17:48:25.713  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 17:48:25.713  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 17:48:25.713  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 17:48:25.721  7060  7558 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-11 17:48:25.721  7060  7558 W bt-smp  : Plain text(LSB ~ MSB) = c4 8e 55 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-11 17:48:25.721  7060  7558 W bt-smp  : Encrypted text(LSB ~ MSB) = 43 06 b2 a6 a4 49 0b a6 db c0 8a 58 e2 14 74 e5 
,08-11 17:48:25.723  7060  7558 W bt-btm  : Stopping oneshot timer
08-11 17:48:25.725  6670  6670 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 17:48:25.730  7060  7499 D LGBluetoothServiceAdapter: [BTUI] OnState
08-11 17:48:25.730  7060  7499 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-11 17:48:25.730  7060  7499 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-11 17:48:25.732  7060  7499 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-11 17:48:25.733  7060  7499 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-11 17:48:25.749  1856  1856 D BluetoothHeadset: Proxy object connected
,08-11 17:48:25.754  7060  7558 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-11 17:48:25.754  7060  7558 W bt-smp  : Plain text(LSB ~ MSB) = 93 56 7b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-11 17:48:25.754  7060  7558 W bt-smp  : Encrypted text(LSB ~ MSB) = 87 6e b9 c8 e6 3f 0a 26 de b3 6c ae 8c 56 d5 6f 
,08-11 17:48:25.754  7060  7558 W bt-btm  : Stopping oneshot timer
08-11 17:48:25.755  6940  6956 D BluetoothMap: onBluetoothStateChange: up=true
08-11 17:48:25.760  7611  7611 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-11 17:48:25.778  1856  2683 D BluetoothHeadset: onBluetoothStateChange: up=true
08-11 17:48:25.778  6940  6940 D BluetoothMap: Proxy object connected
08-11 17:48:25.778  6940  6940 D MapProfile: Bluetooth service connected
08-11 17:48:25.779  6940  6940 D BluetoothMap: getConnectedDevices()
08-11 17:48:25.782  7060  7076 V BluetoothMapService: getConnectedDevices()
,08-11 17:48:25.784  1856  1856 D BluetoothHeadset: Proxy object connected
,08-11 17:48:25.785  6940  6955 D BluetoothPbap: onBluetoothStateChange: up=true
08-11 17:48:25.787  1036  1119 D BluetoothA2dp: onBluetoothStateChange: up=true
08-11 17:48:25.789  1036  1036 D BluetoothA2dp: Proxy object connected
08-11 17:48:25.789  6940  6956 D BluetoothPan: onBluetoothStateChange on: true
08-11 17:48:25.789  6940  6956 D BluetoothPan: onBluetoothStateChange call bindService
08-11 17:48:25.794  6940  6955 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-11 17:48:25.794  6940  6940 D BluetoothPan: BluetoothPAN Proxy object connected
08-11 17:48:25.794  6940  6940 D PanProfile: Bluetooth service connected
,08-11 17:48:25.800  1036  1119 D BluetoothHeadset: onBluetoothStateChange: up=true
08-11 17:48:25.801  1036  1036 D BluetoothHeadset: Proxy object connected
08-11 17:48:25.801  1856  1872 D BluetoothHeadset: onBluetoothStateChange: up=true
08-11 17:48:25.802  6940  6940 D BluetoothInputDevice: Proxy object connected
08-11 17:48:25.802  6940  6940 D HidProfile: Bluetooth service connected
08-11 17:48:25.805  1856  1856 D BluetoothHeadset: Proxy object connected
08-11 17:48:25.806  1036  1119 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-11 17:48:25.806  1036  1119 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
,08-11 17:48:25.814  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-11 17:48:25.815  1036  1119 D BluetoothManagerService: Message: 40
08-11 17:48:25.815  1036  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-11 17:48:25.815  1944  1944 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-11 17:48:25.815  1944  2082 D LGBluetoothAPIService: Message: 1
08-11 17:48:25.816  1944  2082 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-11 17:48:25.816  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-11 17:48:25.818  1944  2082 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
,08-11 17:48:25.822  7060  7060 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-11 17:48:25.822  7060  7060 D BluetoothMapService: STATE_ON
08-11 17:48:25.823  7060  7060 D LGBluetoothAPIServer: [BTUI] onCreate()
08-11 17:48:25.824  7060  7060 D LGBluetoothAPIServer: [BTUI] onBind()
08-11 17:48:25.824  7060  7060 V BluetoothMapService: Handler(): got msg=1
08-11 17:48:25.825  6940  6940 D LocalBluetoothProfileManager: Adding local A2DP profile
08-11 17:48:25.827  1944  1944 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-11 17:48:25.827  1944  2082 D LGBluetoothAPIService: Message: 100
08-11 17:48:25.827  7060  7060 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-11 17:48:25.827  1944  2082 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-11 17:48:25.827  1036  1119 D BluetoothManagerService: Message: 30
08-11 17:48:25.828  7060  7629 D BluetoothMapMasInstance: MAS initSocket()
08-11 17:48:25.828  6670  6670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-11 17:48:25.829  7060  7629 D BluetoothMapMasInstance:   masId = 00
08-11 17:48:25.829  7060  7629 D BluetoothMapMasInstance:   msgTypes = 0e
08-11 17:48:25.829  7060  7629 D BluetoothMapMasInstance:   masName = SMS/MMS
08-11 17:48:25.829  7060  7629 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-11 17:48:25.830  1036  1981 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 17:48:25.831  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 17:48:25.835  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 17:48:25.836  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:48:25.836  6940  6940 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-11 17:48:25.838  1036  1119 D BluetoothManagerService: Message: 30
08-11 17:48:25.843  7060  7060 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@385074ab
08-11 17:48:25.843  7060  7629 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-11 17:48:25.843  7060  7060 V BluetoothPbapService: Pbap Service onCreate
08-11 17:48:25.843  7060  7060 V BluetoothPbapService: Starting PBAP service
,08-11 17:48:25.844  7060  7060 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-11 17:48:25.844  7060  7060 V BluetoothPbapService: Pbap Service onBind
08-11 17:48:25.846  7060  7060 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-11 17:48:25.846  7060  7629 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-11 17:48:25.847  7060  7629 V BluetoothMapMasInstance: Succeed to create listening socket 
08-11 17:48:25.847  7060  7629 D BluetoothMapMasInstance: Accepting socket connection...
08-11 17:48:25.847  7060  7503 D BluetoothAdapterProperties: Scan Mode:21
08-11 17:48:25.847  7060  7060 V BluetoothPbapService: state: 12
08-11 17:48:25.847  7060  7503 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-11 17:48:25.847  7060  7060 V BluetoothPbapService: Handler(): got msg=1
08-11 17:48:25.847  7060  7060 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-11 17:48:25.848  6940  6940 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-11 17:48:25.849  7060  7632 V BluetoothPbapService: Pbap Service initSocket
08-11 17:48:25.850  6940  6940 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-11 17:48:25.850  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 17:48:25.851  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:48:25.851  7060  7632 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-11 17:48:25.852  7060  7632 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-11 17:48:25.852  7060  7632 V BluetoothPbapService: Succeed to create listening socket 
08-11 17:48:25.852  7060  7632 V BluetoothPbapService: Accepting socket connection...
08-11 17:48:25.852  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:48:25.853  6940  6940 D BluetoothA2dp: Proxy object connected
08-11 17:48:25.853  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:48:25.853  6940  6940 D A2dpProfile: Bluetooth service connected
08-11 17:48:25.854  7060  7060 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-11 17:48:25.854  7060  7060 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-11 17:48:25.854  7060  7060 V BluetoothPbapReceiver: ***********state = 12
,08-11 17:48:25.860  2184  2184 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-11 17:48:25.861  2184  2184 D c       : Getting all permits...
08-11 17:48:25.861  2184  2184 D a       : Opening database...
08-11 17:48:25.861  6940  6940 D BluetoothHeadset: Proxy object connected
08-11 17:48:25.862  6940  6940 D HeadsetProfile: Bluetooth service connected
08-11 17:48:25.863  6940  6940 D BluetoothPbap: Proxy object connected
08-11 17:48:25.863  6940  6940 D PbapServerProfile: Bluetooth service connected
08-11 17:48:25.864  2184  2184 D a       : Opening database auth.proximity.permit_store...
08-11 17:48:25.865  2184  2184 D a       : Closing database...
08-11 17:48:25.868  6940  6940 D DockEventReceiver: finishStartingService: stopping service
,08-11 17:48:25.874  6940  6940 D BluetoothPermissionRequest: onReceive
08-11 17:48:25.876  6940  6940 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-11 17:48:25.878  6940  6940 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-11 17:48:25.880  7060  7060 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,08-11 17:48:25.882  7060  7060 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-11 17:48:25.888  7060  7060 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-11 17:48:25.907  7060  7060 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-11 17:48:25.908  7060  7060 V BtOppService: onCreate
08-11 17:48:25.912  7060  7060 V BluetoothOppNotification: send message
08-11 17:48:25.916  7060  7060 V BtOppService: Starting RfcommListener
08-11 17:48:25.921  7060  7060 D BluetoothOppPreference: Dumping Names:  
08-11 17:48:25.921  7060  7060 D BluetoothOppPreference: {}
,08-11 17:48:25.921  7060  7060 D BluetoothOppPreference: Dumping Channels:  
08-11 17:48:25.921  7060  7060 D BluetoothOppPreference: {}
08-11 17:48:25.922  7060  7060 V BtOppService: onStartCommand
08-11 17:48:25.925  7060  7640 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-11 17:48:25.926  7060  7060 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-11 17:48:25.926  7060  7060 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-11 17:48:25.930  7060  7637 V BtOppService: Deleted complete outbound shares, number =  0
08-11 17:48:25.930  7060  7060 V BluetoothOppNotification: new notify threadi!
08-11 17:48:25.930  7060  7060 V BluetoothOppNotification: send delay message
08-11 17:48:25.931  7060  7060 V BtOppService: start RfcommListener
08-11 17:48:25.932  7060  7641 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-11 17:48:25.934  7060  7640 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-11 17:48:25.934  7060  7637 V BtOppService: Deleted complete inbound failed shares, number = 0
,08-11 17:48:25.936  7060  7060 V BtOppService: RfcommListener started
08-11 17:48:25.938  7060  7641 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@204b7a44 on behalf of 
08-11 17:48:25.939  7060  7642 V BtOppRfcommListener: Starting RFCOMM listener....
08-11 17:48:25.940  1036  1624 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 17:48:25.941  7060  7642 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-11 17:48:25.942  7060  7642 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-11 17:48:25.943  7060  7640 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@13fbf72d on behalf of 
08-11 17:48:25.944  7060  7637 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-11 17:48:25.944  7060  7641 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-11 17:48:25.944  7060  7642 V BtOppRfcommListener: Started RFCOMM listener....
08-11 17:48:25.945  7060  7642 I BtOppRfcommListener: Accept thread started.
08-11 17:48:25.945  7060  7642 V BtOppRfcommListener: Accepting connection...
08-11 17:48:25.947  7060  7641 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-11 17:48:25.947  7060  7637 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@21662462 on behalf of 
08-11 17:48:25.947  7060  7640 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,08-11 17:48:25.951  7060  7641 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1d5f89f3 on behalf of 
08-11 17:48:25.953  7060  7641 V BluetoothOppNotification: outbound: succ-0  fail-0
08-11 17:48:25.954  7060  7641 V BluetoothOppNotification: outbound notification was removed.
08-11 17:48:25.954  7060  7641 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-11 17:48:25.956  7060  7641 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2a7f6b0 on behalf of 
08-11 17:48:25.957  7060  7641 V BluetoothOppNotification: inbound: succ-0  fail-0
08-11 17:48:25.957  7060  7060 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@385074ab
08-11 17:48:25.957  7060  7060 V BluetoothFtpService: Ftp Service onCreate
08-11 17:48:25.957  7060  7060 I BluetoothFtpService: Ftp Service onCreate
,08-11 17:48:25.958  7060  7060 V BluetoothFtpService: Ftp Service onStartCommand
08-11 17:48:25.958  7060  7060 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-11 17:48:25.958  7060  7060 V BluetoothFtpService: Starting Listening on sockets
08-11 17:48:25.958  7060  7060 V BtOppService: ContentObserver received notification
08-11 17:48:25.959  7060  7060 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-11 17:48:25.959  7060  7060 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-11 17:48:25.959  7060  7060 V BluetoothSapReceiver: SapReceiver onReceive 
08-11 17:48:25.959  7060  7060 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-11 17:48:25.959  7060  7060 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-11 17:48:25.959  7060  7060 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-11 17:48:25.960  7060  7643 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,08-11 17:48:25.961  7060  7643 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-11 17:48:25.961  7060  7641 V BluetoothOppNotification: inbound notification was removed.
08-11 17:48:25.962  7060  7641 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-11 17:48:25.964  7060  7060 V BtOppService: ContentObserver received notification
08-11 17:48:25.964  7060  7060 V BluetoothFtpService: Handler(): got msg=1
08-11 17:48:25.965  7060  7060 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-11 17:48:25.965  7060  7060 V BluetoothFtpService: Ftp Service initSocket
08-11 17:48:25.965  7060  7643 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@308624ae on behalf of 
08-11 17:48:25.966  7060  7641 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@14ded24f on behalf of 
08-11 17:48:25.966  7060  7643 V BluetoothOppNotification: update too frequent, put in queue
08-11 17:48:25.968  7060  7643 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-11 17:48:25.969  7060  7643 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-11 17:48:25.970  1036  2035 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 17:48:25.970  7060  7643 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3f0dcddc on behalf of 
08-11 17:48:25.971  7060  7643 V BluetoothOppNotification: update too frequent, put in queue
08-11 17:48:25.972  7060  7060 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-11 17:48:25.974  7060  7643 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,08-11 17:48:25.975  7060  7060 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
08-11 17:48:25.975  7060  7060 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-11 17:48:25.977  7060  7644 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-11 17:48:25.997  7060  7060 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@385074ab
,08-11 17:48:25.997  7060  7060 V BluetoothSapService: Sap Service onCreate
08-11 17:48:25.999  7060  7060 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-11 17:48:25.999  7060  7060 V BluetoothSapService: state: 12
08-11 17:48:26.000  7060  7060 V BluetoothSapService: Starting SAP server process
08-11 17:48:26.002  7060  7060 V BluetoothSapService: SAP Service startRfcommListenerThread
08-11 17:48:25.984  7645  7645 W sapd    : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-11 17:48:25.984  7645  7645 W sapd    : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-11 17:48:26.004  7060  7646 V BluetoothSapService: Sap Service initRfcommSocket
08-11 17:48:26.005  1036  1905 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 17:48:26.007  7060  7646 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-11 17:48:26.009  7060  7646 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-11 17:48:26.009  7060  7646 V BluetoothSapService: Succeed to create listening socket 
08-11 17:48:26.009  7060  7646 V BluetoothSapService: Accepting socket connection...
,08-11 17:48:26.028  7645  7645 V BT_SAP  : Event pipe created
,08-11 17:48:26.029  7645  7645 V BT_SAP  : create_server_socket qcom.sap.server
08-11 17:48:26.029  7645  7645 V BT_SAP  : created socket fd 6
,08-11 17:48:26.932  7060  7060 V BluetoothOppNotification: new notify threadi!
,08-11 17:48:26.933  7060  7060 V BluetoothOppNotification: send delay message
,08-11 17:48:26.946  7060  7656 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-11 17:48:26.949  7060  7656 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3a97ebc8 on behalf of 
08-11 17:48:26.955  7060  7656 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-11 17:48:26.958  7060  7656 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-11 17:48:26.959  7060  7656 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@21368461 on behalf of 
08-11 17:48:26.960  7060  7656 V BluetoothOppNotification: outbound: succ-0  fail-0
08-11 17:48:26.961  7060  7656 V BluetoothOppNotification: outbound notification was removed.
08-11 17:48:26.962  7060  7656 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-11 17:48:26.963  7060  7656 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@4921b86 on behalf of 
08-11 17:48:26.963  7060  7656 V BluetoothOppNotification: inbound: succ-0  fail-0
08-11 17:48:26.966  7060  7656 V BluetoothOppNotification: inbound notification was removed.
08-11 17:48:26.966  7060  7656 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-11 17:48:26.970  7060  7656 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@63cbc47 on behalf of 
,08-11 17:48:29.446  1603  1603 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
,08-11 17:48:29.446  1603  1603 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-11 17:48:29.460  1036  1905 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 17:48:29.460  1036  1905 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@251c677a mBinding = false
08-11 17:48:29.475  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-11 17:48:29.475  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-11 17:48:29.475  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,08-11 17:48:29.484  1603  1603 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
08-11 17:48:29.484  1603  1603 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-11 17:48:29.486  1944  2075 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-11 17:48:29.486  1944  2075 D LEDHandler: Battery Level Remaining: 100%
08-11 17:48:29.486  1944  2075 D LEDHandler: Battery Temp: 282, mChargingStatus=5, mChargingStop=false
08-11 17:48:29.490  1603  1603 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,08-11 17:48:29.496  1036  1544 D WifiController: battery changed pluggedType: 2
08-11 17:48:29.496  1036  1119 D BluetoothManagerService: Message: 2
08-11 17:48:29.497  1036  1119 D BluetoothManagerService: Sending off request.
08-11 17:48:29.498  7060  7517 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-11 17:48:29.499  7060  7499 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-11 17:48:29.499  7060  7499 D BluetoothAdapterProperties: Setting state to 13
08-11 17:48:29.499  7060  7499 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-11 17:48:29.500  1036  1119 D BluetoothManagerService: Message: 60
08-11 17:48:29.500  1036  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-11 17:48:29.500  1036  1119 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-11 17:48:29.500  7060  7499 D BluetoothAdapterProperties: onBluetoothDisable()
08-11 17:48:29.501  7060  7499 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-11 17:48:29.502  7060  7533 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-11 17:48:29.504  7060  7503 D BluetoothAdapterProperties: Scan Mode:20
,08-11 17:48:29.508  7060  7499 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-11 17:48:29.509  7060  7499 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-11 17:48:29.511  7060  7632 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-11 17:48:29.511  7060  7558 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-11 17:48:29.512  7060  7642 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-11 17:48:29.513  7060  7558 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-11 17:48:29.514  7060  7629 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-11 17:48:29.514  7060  7629 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-11 17:48:29.514  7060  7629 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-11 17:48:29.514  7060  7629 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-11 17:48:29.514  7060  7629 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-11 17:48:29.514  7060  7629 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-11 17:48:29.514  7060  7629 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-11 17:48:29.514  7060  7629 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-11 17:48:29.518  7060  7558 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-11 17:48:29.518  7060  7558 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-11 17:48:29.518  7060  7558 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-11 17:48:29.518  7060  7558 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-11 17:48:29.518  7060  7558 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-11 17:48:29.522  7060  7558 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-11 17:48:29.522  7060  7558 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-11 17:48:29.522  7060  7558 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-11 17:48:29.522  7060  7558 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-11 17:48:29.522  7060  7558 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-11 17:48:29.522  7060  7558 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-11 17:48:29.523  7060  7558 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-11 17:48:29.525  7060  7644 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-11 17:48:29.528  1944  1944 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-11 17:48:29.530  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-11 17:48:29.538  6670  6670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:48:29.538  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:48:29.538  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:48:29.538  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 17:48:29.538  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 17:48:29.538  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 17:48:29.538  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 17:48:29.538  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 17:48:29.538  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 17:48:29.540  6670  6670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:48:29.540  6670  6670 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 17:48:29.543  6670  6670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:48:29.543  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:48:29.543  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:48:29.543  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 17:48:29.543  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 17:48:29.543  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 17:48:29.543  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 17:48:29.543  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 17:48:29.543  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-11 17:48:29.547  6670  6670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:48:29.547  6670  6670 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 17:48:29.549  6670  6670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:48:29.549  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:48:29.549  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:48:29.549  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 17:48:29.549  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 17:48:29.549  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 17:48:29.549  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 17:48:29.549  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 17:48:29.549  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 17:48:29.550  6670  6670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:48:29.550  6670  6670 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 17:48:29.550  7060  7646 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-11 17:48:29.555  7060  7060 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-11 17:48:29.555  7060  7060 D BluetoothMapService: STATE_TURNING_OFF
08-11 17:48:29.556  7060  7060 V BluetoothMapService: Handler(): got msg=4
08-11 17:48:29.556  7060  7060 D BluetoothMapService: MAP Service closeService in
08-11 17:48:29.556  7060  7060 D BluetoothMapMasInstance: MAP Service shutdown
08-11 17:48:29.556  7060  7060 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-11 17:48:29.556  7060  7060 V BluetoothMapService: MAP Service closeService out
,08-11 17:48:29.560  7060  7060 V BtOppService: Receiver DISABLED_ACTION 
08-11 17:48:29.560  7060  7060 I BtOppRfcommListener: stopping Accept Thread
08-11 17:48:29.560  7060  7060 V BtOppRfcommListener: close mBtServerSocket
08-11 17:48:29.560  7060  7060 V BtOppRfcommListener: waiting for thread to terminate
08-11 17:48:29.561  7060  7642 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-11 17:48:29.561  7060  7060 V BtOppRfcommListener: done waiting for thread to terminate
08-11 17:48:29.564  6940  6940 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-11 17:48:29.569  6940  6940 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-11 17:48:29.596  7060  7060 V BtOppService: onDestroy
,08-11 17:48:29.604  7060  7060 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-11 17:48:29.606  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:48:29.607  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 17:48:29.609  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:48:29.612  7433  7433 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-11 17:48:29.619  7060  7060 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-11 17:48:29.619  7060  7060 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-11 17:48:29.619  7060  7060 V BluetoothPbapReceiver: ***********state = 13
08-11 17:48:29.620  7060  7060 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-11 17:48:29.622  7060  7060 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-11 17:48:29.622  7060  7060 V BluetoothPbapService: state: 13
08-11 17:48:29.622  7060  7060 V BluetoothPbapService: Pbap Service closeService in
08-11 17:48:29.624  2184  2184 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-11 17:48:29.624  7060  7060 V BluetoothPbapService: successfully stopped pbap service
08-11 17:48:29.624  7060  7060 V BluetoothPbapService: Pbap Service closeService out
08-11 17:48:29.624  7060  7060 V BluetoothPbapService: Pbap Service onDestroy
08-11 17:48:29.625  7060  7060 V BluetoothPbapService: Pbap Service closeService in
08-11 17:48:29.625  7060  7060 V BluetoothPbapService: Pbap Service closeService out
08-11 17:48:29.625  7060  7060 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-11 17:48:29.627  6940  6940 D DockEventReceiver: finishStartingService: stopping service
08-11 17:48:29.628  6940  6940 D BluetoothPbap: Proxy object disconnected
08-11 17:48:29.628  6940  6940 D PbapServerProfile: Bluetooth service disconnected
,08-11 17:48:29.635  6940  6940 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-11 17:48:29.641  6940  6940 D BluetoothPermissionRequest: onReceive
,08-11 17:48:29.641  6940  6940 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-11 17:48:29.642  1036  1413 V AlarmManager: ELAPSED_WAKEUP set : Alarm{11f5eb88 type 2 when 187570 com.google.android.gms} when 187570
08-11 17:48:29.647   318  7677 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-11 17:48:29.648  1036  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-11 17:48:29.649  6989  6989 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-11 17:48:29.650  6989  6989 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:2875
08-11 17:48:29.651  6940  6940 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-11 17:48:29.657  7060  7060 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-11 17:48:29.657  7060  7060 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-11 17:48:29.658  7060  7060 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-11 17:48:29.662  7060  7060 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-11 17:48:29.662  7060  7060 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-11 17:48:29.663  7060  7060 V BluetoothFtpService: Ftp Service onStartCommand
08-11 17:48:29.663  7060  7060 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-11 17:48:29.663  7060  7060 V BluetoothFtpService: Ftp Service closeService
08-11 17:48:29.663  7060  7060 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
,08-11 17:48:29.666  7060  7060 V BluetoothFtpService: successfully stopped ftp service
08-11 17:48:29.666  7060  7060 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-11 17:48:29.667  7060  7060 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-11 17:48:29.667  7060  7060 V BluetoothSapReceiver: SapReceiver onReceive 
08-11 17:48:29.667  7060  7060 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-11 17:48:29.667  7060  7060 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-11 17:48:29.667  7060  7060 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-11 17:48:29.668  7060  7060 V BluetoothFtpService: Ftp Service onDestroy
08-11 17:48:29.668  7060  7060 V BluetoothFtpService: Ftp Service closeService
08-11 17:48:29.671  7060  7060 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-11 17:48:29.671  7060  7060 V BluetoothSapService: state: 13
08-11 17:48:29.671  7060  7060 V BluetoothSapService: Stopping SAP server process
08-11 17:48:29.674  7060  7060 V BluetoothSapService: Sap Service closeSapService in
08-11 17:48:29.674  7060  7060 V BluetoothSapService: Close listen Socket : 
08-11 17:48:29.674  7060  7060 V BluetoothSapService: Close rfcomm Socket : 
08-11 17:48:29.674  7060  7060 V BluetoothSapService: Close sapd  Socket : 
,08-11 17:48:29.675  7060  7060 V BluetoothSapService: Sap Service closeSapService out
,08-11 17:48:29.675  7060  7060 V BluetoothSapService: Sap Service onDestroy
08-11 17:48:29.675  7060  7060 V BluetoothSapService: Sap Service closeSapService in
08-11 17:48:29.675  7060  7060 V BluetoothSapService: Close listen Socket : 
08-11 17:48:29.676  7060  7060 V BluetoothSapService: Close rfcomm Socket : 
08-11 17:48:29.676  7060  7060 V BluetoothSapService: Close sapd  Socket : 
08-11 17:48:29.676  7060  7060 V BluetoothSapService: Sap Service closeSapService out
08-11 17:48:29.701  1036  1100 W ProcessCpuTracker: Skipping unknown process pid 7645
,08-11 17:48:30.478  7060  7503 D bt_hci_bdroid: cleanup
,08-11 17:48:30.485  7060  7560 I bt_lpm  : LPM is already off!!!
08-11 17:48:30.486  7060  7598 I bt_userial_mct: exiting userial_read_thread
08-11 17:48:30.486  7060  7598 D bt_userial_mct: Leaving userial_evt_read_thread()
08-11 17:48:30.486  7060  7558 W bt-btif : ag scb idx 1 not allocated
,08-11 17:48:30.486  7060  7558 E bt-btif : BTA AG is already disabled, ignoring ...
08-11 17:48:30.486  7060  7558 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-11 17:48:30.486  7060  7558 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-11 17:48:30.486  7060  7558 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-11 17:48:30.486  7060  7558 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-11 17:48:30.487  7060  7558 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-11 17:48:30.487  7060  7558 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-11 17:48:30.487  7060  7558 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-11 17:48:30.487  7060  7558 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-11 17:48:30.487  7060  7558 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-11 17:48:30.487  7060  7558 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-11 17:48:30.487  7060  7558 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-11 17:48:30.487  7060  7558 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-11 17:48:30.487  7060  7558 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-11 17:48:30.487  7060  7558 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-11 17:48:30.487  7060  7558 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-11 17:48:30.487  7060  7558 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-11 17:48:30.487  7060  7558 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-11 17:48:30.487  7060  7558 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-11 17:48:30.487  7060  7558 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-11 17:48:30.488  7060  7503 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-11 17:48:30.488  7060  7560 I bt_vendor: hw_epilog_process
08-11 17:48:30.488  7060  7503 D bt_hci_bdroid: cleanup Finalizing cleanup
08-11 17:48:30.488  7060  7503 D bt_userial_mct: userial_close
08-11 17:48:30.488  7060  7503 E bt_userial_mct: pthread_join() FAILED result:3
08-11 17:48:30.488  7060  7503 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-11 17:48:30.495  7060  7503 D bt_hci_bdroid: set_power 0
08-11 17:48:30.495  7060  7503 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-11 17:48:30.495  7060  7503 I bt_vendor: bluetooth satus is on
08-11 17:48:30.495  7060  7503 I bt_vendor: bt-vendor : resetting BT status
08-11 17:48:30.495  7060  7503 I bt_vendor: Starting hciattach daemon
08-11 17:48:30.495  7060  7503 I bt_vendor: try to set false
08-11 17:48:30.498  7060  7503 I bt_vendor: Starting hciattach daemon
08-11 17:48:30.498  7060  7503 I bt_vendor: try to set false
,08-11 17:48:30.504  7060  7503 I bt_vendor: cleanup
08-11 17:48:30.505  7060  7558 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-11 17:48:30.506  7060  7503 I GKI_LINUX: GKI_exit_task 0 done
08-11 17:48:30.506  7060  7503 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-11 17:48:30.508  7060  7499 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-11 17:48:30.516  7060  7060 D HeadsetService: Received stop request...Stopping profile...
,08-11 17:48:30.518  7060  7060 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-11 17:48:30.518  7060  7060 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-11 17:48:30.519  7060  7060 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@385074ab
08-11 17:48:30.519  7060  7533 D HeadsetStateMachine: Exit Disconnected: -1
08-11 17:48:30.523  1856  1856 D BluetoothHeadset: Proxy object disconnected
08-11 17:48:30.525  1036  1036 D BluetoothHeadset: Proxy object disconnected
08-11 17:48:30.526  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-11 17:48:30.527  7060  7499 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-11 17:48:30.529  7060  7060 D A2dpService: Received stop request...Stopping profile...
08-11 17:48:30.529  7060  7550 D A2dpStateMachine: Exit Disconnected: -1
08-11 17:48:30.531  1856  1856 D BluetoothHeadset: Proxy object disconnected
08-11 17:48:30.532  1856  1856 D BluetoothHeadset: Proxy object disconnected
08-11 17:48:30.532  7060  7060 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-11 17:48:30.534  7060  7060 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-11 17:48:30.534  7060  7060 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-11 17:48:30.534  7060  7060 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@385074ab
08-11 17:48:30.536  7060  7060 D HidService: Received stop request...Stopping profile...
08-11 17:48:30.536  7060  7060 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@385074ab
08-11 17:48:30.537  1036  1036 D BluetoothA2dp: Proxy object disconnected
08-11 17:48:30.537  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-11 17:48:30.540  7060  7060 D HealthService: Received stop request...Stopping profile...
08-11 17:48:30.540  7060  7060 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@385074ab
,08-11 17:48:30.545  7060  7060 D PanService: Received stop request...Stopping profile...
08-11 17:48:30.545  7060  7060 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@385074ab
08-11 17:48:30.546  7060  7060 D BtGatt.DebugUtils: handleDebugAction() action=null
08-11 17:48:30.547  7060  7060 D BtGatt.GattService: Received stop request...Stopping profile...
08-11 17:48:30.547  7060  7060 D BtGatt.GattService: stop()
08-11 17:48:30.547  7060  7060 D BtGatt.AdvertiseManager: advertise clients cleared
08-11 17:48:30.548  7060  7060 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@385074ab
08-11 17:48:30.550  7060  7060 D HeadsetStateMachine: Unbinding service...
08-11 17:48:30.551  7060  7060 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-11 17:48:30.552  7060  7060 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-11 17:48:30.552  7060  7060 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-11 17:48:30.552  7060  7060 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-11 17:48:30.552  7060  7060 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-11 17:48:30.552  7060  7060 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-11 17:48:30.552  7060  7060 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
,08-11 17:48:30.555  7060  7060 D BluetoothMapService: Received stop request...Stopping profile...
08-11 17:48:30.555  7060  7060 D BluetoothMapService: stop()
08-11 17:48:30.556  7060  7060 D BluetoothMapEmailAppObserver: deinitObservers()
08-11 17:48:30.556  7060  7060 D BluetoothMapEmailAppObserver: removeReceiver()
08-11 17:48:30.557  7060  7060 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@385074ab
08-11 17:48:30.558  7060  7060 I BluetoothA2dpServiceJni: cleanupNative
08-11 17:48:30.558  7060  7551 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-11 17:48:30.559  7060  7060 I GKI_LINUX: GKI_exit_task 2 done
08-11 17:48:30.559  7060  7060 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-11 17:48:30.559  7060  7060 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-11 17:48:30.559  7060  7060 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-11 17:48:30.559  7060  7060 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-11 17:48:30.560  7060  7060 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-11 17:48:30.560  7060  7060 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-11 17:48:30.560  7060  7060 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-11 17:48:30.560  7060  7060 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-11 17:48:30.565  7060  7060 V BluetoothMapService: Handler(): got msg=4
08-11 17:48:30.565  7060  7060 D BluetoothMapService: MAP Service closeService in
08-11 17:48:30.565  7060  7060 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-11 17:48:30.565  7060  7060 V BluetoothMapService: MAP Service closeService out
,08-11 17:48:30.567  7060  7499 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-11 17:48:30.568  7060  7499 D BluetoothAdapterProperties: Setting state to 10
08-11 17:48:30.568  7060  7499 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-11 17:48:30.568  7060  7060 D BluetoothMapService: cleanup()
08-11 17:48:30.568  7060  7060 D BluetoothMapService: MAP Service closeService in
08-11 17:48:30.568  7060  7060 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-11 17:48:30.568  7060  7060 V BluetoothMapService: MAP Service closeService out
08-11 17:48:30.569  1036  1119 D BluetoothManagerService: Message: 60
08-11 17:48:30.569  1036  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-11 17:48:30.570  1036  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-11 17:48:30.570  7060  7499 I BluetoothAdapterState: Entering OffState
08-11 17:48:30.570  1856  1871 D BluetoothHeadset: onBluetoothStateChange: up=false
08-11 17:48:30.571  6940  6956 D BluetoothHeadset: onBluetoothStateChange: up=false
08-11 17:48:30.572  6940  6956 D BluetoothMap: onBluetoothStateChange: up=false
08-11 17:48:30.573  1856  1872 D BluetoothHeadset: onBluetoothStateChange: up=false
08-11 17:48:30.574  6940  6956 D BluetoothPbap: onBluetoothStateChange: up=false
08-11 17:48:30.577  1036  1119 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-11 17:48:30.579  6940  6956 D BluetoothPan: onBluetoothStateChange on: false
08-11 17:48:30.580  6940  6956 D BluetoothA2dp: onBluetoothStateChange: up=false
08-11 17:48:30.581  6940  6956 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-11 17:48:30.581  1036  1119 D BluetoothHeadset: onBluetoothStateChange: up=false
08-11 17:48:30.582  1856  4059 D BluetoothHeadset: onBluetoothStateChange: up=false
08-11 17:48:30.583  1036  1119 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-11 17:48:30.583  1036  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-11 17:48:30.585  1036  1119 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-11 17:48:30.585  1036  1119 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-11 17:48:30.585  1036  1119 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@251c677a mBinding = false
08-11 17:48:30.586  1036  1119 D BluetoothManagerService: Sending unbind request.
08-11 17:48:30.591  7060  7503 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-11 17:48:30.593  7060  7060 I GKI_LINUX: GKI_exit_task 1 done
08-11 17:48:30.593  7060  7060 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-11 17:48:30.594  7060  7060 I BluetoothServiceJni: cleanupNative: return from cleanup
08-11 17:48:30.594  7060  7060 I art     : --- WEIRD: removing null entry 248
08-11 17:48:30.594  7060  7060 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-11 17:48:30.594  7060  7060 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-11 17:48:30.595  7060  7060 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-11 17:48:30.596  1036  1119 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-11 17:48:30.599  7060  7060 I art     : System.exit called, status: 0
08-11 17:48:30.599  7060  7060 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-11 17:48:30.618   322  1383 V AudioFlinger: 7060 died, releasing its sessions
08-11 17:48:30.618   322  1383 V AudioFlinger:  pid 1856 @ 0
08-11 17:48:30.618   322  1383 V AudioFlinger:  pid 3521 @ 1
08-11 17:48:30.618   322  1383 V AudioFlinger:  pid 3521 @ 2
,08-11 17:48:30.622  1944  1944 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-11 17:48:30.622  1944  2082 D LGBluetoothAPIService: Message: 101
08-11 17:48:30.622  1944  2082 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-11 17:48:30.622  1944  2082 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-11 17:48:30.622  1944  2082 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-11 17:48:30.626  6940  6940 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-11 17:48:30.654  1036  1975 I ActivityManager: Process com.android.bluetooth (pid 7060) has died
08-11 17:48:30.654  1036  1975 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
08-11 17:48:30.654  1036  1975 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 14000ms
,08-11 17:48:30.661  1944  1944 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-11 17:48:30.661  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-11 17:48:30.662  1944  2082 D LGBluetoothAPIService: Message: 2
08-11 17:48:30.662  1944  2082 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-11 17:48:30.664  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:48:30.665  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:48:30.665  6940  6940 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-11 17:48:30.665  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:48:30.665  6940  6940 D LGBluetoothEventManager: [BTUI] clear device connection state
08-11 17:48:30.668  1603  1603 D BluetoothAdapter: 511128530: getState() :  mService = null. Returning STATE_OFF
08-11 17:48:30.668  1603  1603 D BluetoothAdapter: 511128530: getState() :  mService = null. Returning STATE_OFF
,08-11 17:48:30.673  6940  6940 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-11 17:48:30.730  1036  1052 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7706 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-11 17:48:30.732  6940  6940 D DockEventReceiver: finishStartingService: stopping service
,08-11 17:48:30.816  7706  7706 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-11 17:48:30.817  7706  7706 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-11 17:48:30.817  7706  7706 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,08-11 17:48:30.818  7706  7706 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-11 17:48:30.838  7706  7706 D BluetoothAdapterApp: Loading JNI Library
,08-11 17:48:30.879  7706  7706 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@3cd2f233 Instance Count = 1
,08-11 17:48:30.886  7706  7706 D BluetoothAdapterApp: onCreate
,08-11 17:48:30.912  7706  7706 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,08-11 17:48:30.912  7706  7706 D ProfileConfigQcom: Adding HeadsetService
08-11 17:48:30.912  7706  7706 D ProfileConfigQcom: [BTUI] A2dpService is supported
,08-11 17:48:30.912  7706  7706 D ProfileConfigQcom: Adding A2dpService
08-11 17:48:30.913  7706  7706 D ProfileConfigQcom: [BTUI] HidService is supported
,08-11 17:48:30.913  7706  7706 D ProfileConfigQcom: Adding HidService
08-11 17:48:30.913  7706  7706 D ProfileConfigQcom: [BTUI] HealthService is supported
,08-11 17:48:30.914  7706  7706 D ProfileConfigQcom: Adding HealthService
08-11 17:48:30.914  7706  7706 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-11 17:48:30.915  7706  7706 D ProfileConfigQcom: [BTUI] PanService is supported
,08-11 17:48:30.915  7706  7706 D ProfileConfigQcom: Adding PanService
08-11 17:48:30.916  7706  7706 D ProfileConfigQcom: [BTUI] GattService is supported
,08-11 17:48:30.916  7706  7706 D ProfileConfigQcom: Adding GattService
08-11 17:48:30.916  7706  7706 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-11 17:48:30.916  7706  7706 D ProfileConfigQcom: Adding BluetoothMapService
,08-11 17:48:30.917  7706  7706 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-11 17:48:30.919  7706  7706 V BluetoothPbapReceiver: PbapReceiver onReceive 
,08-11 17:48:30.921  7706  7706 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-11 17:48:30.922  7706  7706 V BluetoothPbapReceiver: ***********state = 10
,08-11 17:48:30.930  7706  7706 V LGMDMManagerInternal: Create singleton instance
,08-11 17:48:31.048  2184  2184 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-11 17:48:31.049  6940  6940 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-11 17:48:31.052  7706  7706 D LGBluetoothAPIServer: [BTUI] onCreate()
,08-11 17:48:31.053  7706  7706 D LGBluetoothAPIServer: [BTUI] onBind()
,08-11 17:48:31.056  1944  1944 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-11 17:48:31.057  1944  2082 D LGBluetoothAPIService: Message: 100
08-11 17:48:31.057  1944  2082 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-11 17:48:31.089  6940  6940 D BluetoothPermissionRequest: onReceive
08-11 17:48:31.093  6940  6940 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-11 17:48:31.093  6940  6940 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
,08-11 17:48:31.097  6940  6940 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-11 17:48:31.103  7706  7706 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-11 17:48:31.108  7706  7706 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-11 17:48:31.112  7706  7706 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-11 17:48:31.112  7706  7706 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-11 17:48:31.112  7706  7706 V BluetoothSapReceiver: SapReceiver onReceive 
08-11 17:48:31.115  7706  7706 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,08-11 17:48:31.115  7706  7706 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-11 17:48:31.126  7567  7567 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-11 17:48:34.502  6670  6809 D io.jxcore.node.ConnectivityMonitor: stop
,08-11 17:48:34.502  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 17:48:39.517  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 17:48:39.517  6670  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@134c1f35 removed from the list
,08-11 17:48:39.517  6670  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:48:39.517  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:48:39.517  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:48:39.520  6670  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-11 17:48:39.520  6670  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3264c53b added. We now have 4 listener(s)
08-11 17:48:39.521  6670  6809 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-11 17:48:39.530  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 17:48:39.530  6670  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3264c53b removed from the list
,08-11 17:48:39.530  6670  6809 D io.jxcore.node.ConnectivityMonitor: stop
,08-11 17:48:39.530  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 17:48:39.530  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:48:39.531  6670  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 17:48:39.531  6670  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2fa22458 added. We now have 4 listener(s)
08-11 17:48:39.531  6670  6809 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 17:48:39.534  1036  2035 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 17:48:39.534  1036  2035 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-11 17:48:39.534  1036  1119 D BluetoothManagerService: Message: 2
,08-11 17:48:41.537  6670  6809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 17:48:41.553  1036  1914 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 17:48:41.553  1036  1914 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
08-11 17:48:41.579  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-11 17:48:41.580  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-11 17:48:41.580  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,08-11 17:48:41.583  1036  1119 D BluetoothManagerService: Message: 1
08-11 17:48:41.583  1036  1119 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-11 17:48:41.616  1036  1119 D BluetoothManagerService: Message: 20
08-11 17:48:41.616  1036  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e3c6bd2:true
,08-11 17:48:41.619  7706  7706 D BluetoothAdapterState: make
08-11 17:48:41.624  7706  7706 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-11 17:48:41.624  7706  7706 I bluedroid-qcom: init
08-11 17:48:41.626  7706  7746 I BluetoothAdapterState: Entering OffState
08-11 17:48:41.626  7706  7706 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-11 17:48:41.626  7706  7706 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-11 17:48:41.626  7706  7706 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-11 17:48:41.626  7706  7706 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-11 17:48:41.626  7706  7706 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-11 17:48:41.628  7706  7706 I bluedroid-qcom: get_profile_interface socket
08-11 17:48:41.628  7706  7706 I bluedroid-qcom: get_profile_interface map_client
,08-11 17:48:41.633  7706  7750 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-11 17:48:41.624  7749  7749 W bdaddr_loader: type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-11 17:48:41.624  7749  7749 W bdaddr_loader: type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-11 17:48:41.643  7749  7749 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
,08-11 17:48:41.649  7706  7750 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-11 17:48:41.650  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-11 17:48:41.650  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-11 17:48:41.652  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-11 17:48:41.652  1036  1119 D BluetoothManagerService: Message: 40
08-11 17:48:41.652  1036  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-11 17:48:41.653  7706  7721 I bluedroid-qcom: config_hci_snoop_log
08-11 17:48:41.655  1036  1119 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-11 17:48:41.655  1036  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-11 17:48:41.655  7749  7749 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-11 17:48:41.655  7749  7749 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-11 17:48:41.657  7749  7749 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,08-11 17:48:41.662  7706  7750 D BluetoothAdapterProperties: Name is: G3
08-11 17:48:41.664  7749  7749 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-11 17:48:41.664  7749  7749 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-11 17:48:41.669  7706  7746 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-11 17:48:41.669  7706  7746 D BluetoothAdapterProperties: Setting state to 11
08-11 17:48:41.669  7706  7746 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-11 17:48:41.673  7706  7746 I LGBluetoothServiceJni: classInitNative: succeeds
08-11 17:48:41.677  1036  1119 D BluetoothManagerService: Message: 60
08-11 17:48:41.677  1036  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-11 17:48:41.677  1036  1119 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-11 17:48:41.681  1944  1944 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-11 17:48:41.684  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-11 17:48:41.687  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:48:41.688  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:48:41.690  6940  6940 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-11 17:48:41.706  7706  7706 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-11 17:48:41.706  7706  7746 D BluetoothBondStateMachine: make
08-11 17:48:41.707  7706  7706 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-11 17:48:41.707  7706  7706 V BluetoothPbapReceiver: ***********state = 11
,08-11 17:48:41.713  2184  2184 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-11 17:48:41.716  7706  7763 I BluetoothBondStateMachine: StableState(): Entering Off State
08-11 17:48:41.716  7706  7746 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@250ff708
08-11 17:48:41.716  7706  7746 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
,08-11 17:48:41.716  7706  7746 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@250ff708
08-11 17:48:41.716  7706  7746 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-11 17:48:41.717  7706  7746 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-11 17:48:41.721  7706  7746 E BluetoothAdapterService: File transfer profiles supported!!
,08-11 17:48:41.730  7706  7746 E BluetoothAdapterService: File transfer profiles supported!!
08-11 17:48:41.731  7706  7706 D HeadsetService: Received start request. Starting profile...
08-11 17:48:41.732  7706  7706 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-11 17:48:41.732  7706  7706 D LGBluetoothHfpAdapter: Version 1.6
,08-11 17:48:41.735  7706  7706 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-11 17:48:41.737  7706  7706 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-11 17:48:41.737  7706  7706 D HeadsetStateMachine: make
08-11 17:48:41.741  6940  6940 D BluetoothPermissionRequest: onReceive
08-11 17:48:41.744  7706  7746 E BluetoothAdapterService: File transfer profiles supported!!
08-11 17:48:41.751  7706  7746 E BluetoothAdapterService: File transfer profiles supported!!
,08-11 17:48:41.751  6940  6940 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-11 17:48:41.757  7706  7746 E BluetoothAdapterService: File transfer profiles supported!!
08-11 17:48:41.762  7706  7746 E BluetoothAdapterService: File transfer profiles supported!!
08-11 17:48:41.767  7706  7746 E BluetoothAdapterService: File transfer profiles supported!!
,08-11 17:48:41.775  7706  7706 D LgDataFeature: LgDataFeature() Constructor: none
08-11 17:48:41.776  7706  7706 D LgDataFeature: LgDataFeature() Constructor Done, null
08-11 17:48:41.780  7706  7706 D HeadsetStateMachine: max_hf_connections = 1
08-11 17:48:41.780  7706  7706 I bluedroid-qcom: get_profile_interface handsfree
08-11 17:48:41.780  7706  7746 V LGMDMManager: Create singleton instance
08-11 17:48:41.782  7706  7706 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-11 17:48:41.782  7706  7746 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-11 17:48:41.783   322  1384 V AudioPolicyService: registerClient() client 0xb1021d20, uid 1002
08-11 17:48:41.783   322  1383 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-11 17:48:41.783   322  1383 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-11 17:48:41.783   322  1383 V AudioPolicyManagerEx: getOutput() returns output 2
08-11 17:48:41.783  7706  7706 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-11 17:48:41.784   322  1783 V AudioFlinger: registerClient() client 0xb101fbf8, pid 7706
08-11 17:48:41.784   322  1378 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-11 17:48:41.784   322  1378 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-11 17:48:41.784  7706  7706 V ToneGenerator: Create Track: 0xb4928a80
08-11 17:48:41.785  7706  7706 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-11 17:48:41.785  7706  7706 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-11 17:48:41.785   322   322 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-11 17:48:41.785   322   322 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-11 17:48:41.785   322   322 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-11 17:48:41.785   322   322 V AudioPolicyManagerEx: getOutput() returns output 2
08-11 17:48:41.785  7706  7721 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-11 17:48:41.785  7706  7721 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-11 17:48:41.785  1036  2016 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-11 17:48:41.785  1036  2016 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-11 17:48:41.785   322  1383 I AudioFlinger: isAudioPlaybackHookOn() false
08-11 17:48:41.785  3521  3541 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-11 17:48:41.785  3521  3541 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-11 17:48:41.785   322  2157 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-11 17:48:41.785  1856  1872 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-11 17:48:41.785  1856  1872 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-11 17:48:41.785   322  2157 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-11 17:48:41.785   322  2157 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-11 17:48:41.785   322  2157 V AudioPolicyManagerEx: getOutput() returns output 2
08-11 17:48:41.786   322  1379 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-11 17:48:41.786   322  1379 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-11 17:48:41.786  7706  7706 V AudioSystem: getLatency() output 2, latency 50
08-11 17:48:41.786  7706  7706 V AudioSystem: getFrameCount() output 2, frameCount 960
08-11 17:48:41.786  7706  7706 V AudioTrack: createTrack_l() output 2 afLatency 50
08-11 17:48:41.786  1856  4059 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-11 17:48:41.786  1856  4059 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-11 17:48:41.786  1036  1789 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-11 17:48:41.786  1036  1789 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-11 17:48:41.786  3521  3540 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-11 17:48:41.786   322  1384 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-11 17:48:41.786   322  1384 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-11 17:48:41.786  3521  3540 V AudioSystem: ioConfigChanged() o,pening already existing output! 4
08-11 17:48:41.786   322  1384 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-11 17:48:41.786   322  1384 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-11 17:48:41.786   322  1384 V AudioFlinger: createTrack() lSessionId: 23
08-11 17:48:41.787  7706  7722 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-11 17:48:41.787  7706  7722 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-11 17:48:41.787  7706  7706 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-11 17:48:41.788   322  1783 V AudioFlinger: acquiring 23 from 7706, for 7706
08-11 17:48:41.788   322  1783 V AudioFlinger:  added new entry for 23
08-11 17:48:41.788  7706  7706 V ToneGenerator: ToneGenerator INIT OK, time: 200714
08-11 17:48:41.788  7706  7706 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@250ff708
08-11 17:48:41.788  7706  7767 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-11 17:48:41.789  7706  7767 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-11 17:48:41.789  7706  7767 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-11 17:48:41.789  7706  7767 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-11 17:48:41.789   322  1383 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7706
08-11 17:48:41.789   322  1383 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-11 17:48:41.789   322  1383 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-11 17:48:41.790   322  1383 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-11 17:48:41.790   322  1383 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-11 17:48:41.790   322  1383 V voice   : voice_set_parameters: exit with code(0)
08-11 17:48:41.790   322  1383 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-11 17:48:41.790   322  1383 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-11 17:48:41.790   322  1383 V msm8974_platform: platform_set_parameters: exit with code(0)
08-11 17:48:41.790   322  1383 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-11 17:48:41.790   322  1383 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-11 17:48:41.790   322  1383 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-11 17:48:41.790  7706  7767 V ToneGenerator: ToneGenerator destructor
08-11 17:48:41.790  7706  7767 V ToneGenerator: stopTone
08-11 17:48:41.790  7706  7767 V ToneGenerator: Delete Track: 0xb4928a80
08-11 17:48:41.791  7706  7706 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@250ff708
08-11 17:48:41.791  7706  7767 V AudioTrack: ~AudioTrack, releasing session id from 7706 on behalf of 7706
08-11 17:48:41.791   322  1384 V AudioPolicyService: AudioCommandThread() adding release output 2
08-11 17:48:41.791   322  1384 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-11 17:48:41.791   322   322 V AudioFlinger: releasing 23 from 7706 for 7706
08-11 17:48:41.791   322   322 V AudioFlinger:  decremented refcount to 0
08-11 17:48:41.791   322   322 V AudioFlinger: purging stale effects
,08-11 17:48:41.792  1603  2272 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-11 17:48:41.792  1603  2272 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-11 17:48:41.792  1603  2272 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-11 17:48:41.792  1603  2272 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-11 17:48:41.792  7706  7706 D A2dpService: Received start request. Starting profile...
08-11 17:48:41.792   322  1275 V AudioPolicyService: AudioCommandThread() waking up
08-11 17:48:41.792   322  1275 V AudioPolicyService: AudioCommandThread() processing release output 2
08-11 17:48:41.792   322  1275 V AudioPolicyManager: releaseOutput() 2
08-11 17:48:41.792   322  1275 V AudioPolicyService: AudioCommandThread() going to sleep
08-11 17:48:41.792   322  1384 V AudioFlinger: PlaybackThread::Track destructor
08-11 17:48:41.793   322  1384 V AudioFlinger: removeClient_l() pid 7706, calling pid 322
08-11 17:48:41.793  7706  7706 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-11 17:48:41.794  7706  7706 V Avrcp   : make
,08-11 17:48:41.794  7706  7706 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-11 17:48:41.795  7706  7706 I bluedroid-qcom: get_profile_interface avrcp
08-11 17:48:41.795  1036  1940 W Process : Unable to open /proc/7768/status
,08-11 17:48:41.802  7706  7706 V AudioManager: registerRemoteController: size of Media player list: 0
,08-11 17:48:41.804  7706  7706 E AudioManager: No RCC entry present to update
08-11 17:48:41.804  7706  7706 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-11 17:48:41.807  7706  7706 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-11 17:48:41.808  7706  7706 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-11 17:48:41.808  7706  7706 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
,08-11 17:48:41.811  7706  7706 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-11 17:48:41.905  1036  1789 V SIM_STK : Menu title from STK is T-Mobile
08-11 17:48:41.905  1036  1789 V SIM_STK : Menu title from STK is T-Mobile
,08-11 17:48:42.029  1036  1577 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-11 17:48:42.040  7706  7706 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-11 17:48:42.045  7706  7706 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-11 17:48:42.046  7706  7706 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-11 17:48:42.047  7706  7706 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-11 17:48:42.047  7706  7706 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
,08-11 17:48:42.047  7706  7706 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
,08-11 17:48:42.047  7706  7706 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-11 17:48:42.047  7706  7706 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-11 17:48:42.047  7706  7706 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-11 17:48:42.047  7706  7706 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-11 17:48:42.047  7706  7706 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-11 17:48:42.048  7706  7706 I BluetoothA2dpServiceJni: classInitNative
08-11 17:48:42.048  7706  7706 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-11 17:48:42.048  7706  7706 D A2dpStateMachine: make
08-11 17:48:42.052  7706  7706 I bluedroid-qcom: get_profile_interface a2dp
08-11 17:48:42.053  7706  7777 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-11 17:48:42.061  7706  7706 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-11 17:48:42.062  7706  7706 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-11 17:48:42.066  7706  7706 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@250ff708
08-11 17:48:42.066  7706  7775 D A2dpStateMachine: Enter Disconnected: -2
,08-11 17:48:42.070  7706  7706 I BluetoothHidServiceJni: classInitNative: succeeds
08-11 17:48:42.077  7706  7706 D HidService: Received start request. Starting profile...
08-11 17:48:42.077  7706  7706 I bluedroid-qcom: get_profile_interface hidhost
08-11 17:48:42.077  7706  7706 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@250ff708
,08-11 17:48:42.085  7706  7706 I BluetoothHealthServiceJni: classInitNative: succeeds
08-11 17:48:42.090  7706  7706 D HealthService: Received start request. Starting profile...
,08-11 17:48:42.092  7706  7706 I bluedroid-qcom: get_profile_interface health
08-11 17:48:42.093  7706  7706 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-11 17:48:42.093  7706  7706 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@250ff708
08-11 17:48:42.094  7706  7706 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-11 17:48:42.097  7706  7706 D PanService: Received start request. Starting profile...
,08-11 17:48:42.097  7706  7706 D BluetoothPanServiceJni: initializeNative(L110): pan
08-11 17:48:42.097  7706  7706 I bluedroid-qcom: get_profile_interface pan
08-11 17:48:42.107  7706  7706 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-11 17:48:42.107  7706  7706 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@250ff708
08-11 17:48:42.109  7706  7706 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-11 17:48:42.116  7706  7706 D BtGatt.DebugUtils: handleDebugAction() action=null
08-11 17:48:42.116  7706  7706 D BtGatt.GattService: Received start request. Starting profile...
08-11 17:48:42.116  7706  7706 D BtGatt.GattService: start()
08-11 17:48:42.116  7706  7706 I bluedroid-qcom: get_profile_interface gatt
,08-11 17:48:42.117  7706  7706 D BtGatt.AdvertiseManager: advertise manager created
,08-11 17:48:42.269  1036  2016 I art     : Explicit concurrent mark sweep GC freed 63854(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 2.120ms total 145.459ms
,08-11 17:48:42.271  7706  7706 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@250ff708
08-11 17:48:42.272  7706  7706 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@250ff708
08-11 17:48:42.273  7706  7706 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-11 17:48:42.273  7706  7706 V BluetoothMapService: BluetoothMapBinder()
08-11 17:48:42.274  7706  7706 D BluetoothMapService: Received start request. Starting profile...
08-11 17:48:42.274  7706  7706 D BluetoothMapService: start()
08-11 17:48:42.279  7706  7706 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-11 17:48:42.279  7706  7706 D BluetoothMapEmailAppObserver: createReceiver()
08-11 17:48:42.280  7706  7706 D BluetoothMapEmailAppObserver: initObservers()
08-11 17:48:42.280  7706  7706 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,08-11 17:48:42.287  7706  7706 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@250ff708
08-11 17:48:42.288  7706  7706 D HeadsetStateMachine: Proxy object connected
08-11 17:48:42.290  7706  7706 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-11 17:48:42.290  7706  7706 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-11 17:48:42.299  7706  7706 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-11 17:48:42.301  7706  7767 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-11 17:48:42.302  7706  7767 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-11 17:48:42.303  7706  7767 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-11 17:48:42.305  7706  7706 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-11 17:48:42.309  7706  7706 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-11 17:48:42.311  7706  7706 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-11 17:48:42.315  7706  7706 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-11 17:48:42.315  7706  7706 V PanService: [BTUI] SIM Extra State :ABSENT
,08-11 17:48:42.319  7706  7706 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-11 17:48:42.322  7706  7706 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-11 17:48:42.323  7706  7706 V BluetoothMapService: Handler(): got msg=1
08-11 17:48:42.323  7706  7706 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-11 17:48:42.323  7706  7706 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-11 17:48:42.323  7706  7706 V BluetoothSapReceiver: SapReceiver onReceive 
08-11 17:48:42.323  7706  7706 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-11 17:48:42.323  7706  7706 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-11 17:48:42.324  7706  7746 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-11 17:48:42.324  7706  7746 I bluedroid-qcom: enable
08-11 17:48:42.325  7706  7784 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-11 17:48:42.326  7706  7784 I bt-btu  : btu_task pending for preload complete event
08-11 17:48:42.327  7706  7746 I bt_hci_bdroid: init
08-11 17:48:42.330  7706  7746 I bt_vendor: bt-vendor : init
08-11 17:48:42.330  7706  7746 I bt_vendor: bt-vendor : get_bt_soc_type
,08-11 17:48:42.330  7706  7746 E bt_vendor: get_bt_soc_type: Failed to get soc type
,08-11 17:48:42.330  7706  7746 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-11 17:48:42.330  7706  7746 D bt_userial_mct: userial_init
08-11 17:48:42.332  7706  7746 D bt_hci_bdroid: set_power 1
08-11 17:48:42.332  7706  7746 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-11 17:48:42.332  7706  7746 I bt_vendor: Starting hciattach daemon
08-11 17:48:42.332  7706  7746 I bt_vendor: try to set true
08-11 17:48:42.324  7787  7787 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-11 17:48:42.324  7787  7787 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-11 17:48:42.367  7788  7788 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-11 17:48:42.489  7794  7794 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-11 17:48:42.504  7795  7795 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-11 17:48:42.531  7797  7797 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-11 17:48:42.545  7798  7798 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-11 17:48:42.559  7799  7799 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-11 17:48:42.587  7803  7803 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-11 17:48:42.608  7805  7805 I libmdmdetect: ESOC framework not supported
,08-11 17:48:42.609  7805  7805 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-11 17:48:42.618  7805  7805 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-11 17:48:42.618  7805  7805 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
,08-11 17:48:42.618  7805  7805 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-11 17:48:42.618  7805  7805 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-11 17:48:42.618  7805  7805 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-11 17:48:42.618  7805  7805 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-11 17:48:42.618  7805  7805 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,08-11 17:48:42.659  7805  7806 E QC-QMI  : qmi_client [7805] 15: failed to locate client data
08-11 17:48:42.660   466   466 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,08-11 17:48:42.660   466   466 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-11 17:48:42.704  7807  7807 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-11 17:48:42.719  7808  7808 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-11 17:48:42.738  7706  7746 I bt_vendor: bluetooth satus is on
08-11 17:48:42.738  7706  7746 D bt_hci_bdroid: preload
,08-11 17:48:42.738  7706  7786 D bt_userial_mct: userial_open(port:0)
08-11 17:48:42.738  7706  7786 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-11 17:48:42.741  7706  7786 I bt_vendor: Done intiailizing UART
08-11 17:48:42.744  7706  7786 I bt_vendor: Done intiailizing UART
08-11 17:48:42.744  7706  7786 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-11 17:48:42.745  7706  7786 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-11 17:48:42.745  7706  7810 D bt_userial_mct: Entering userial_read_thread()
08-11 17:48:42.745  7706  7784 I bt-btu  : btu_task received preload complete event
08-11 17:48:42.745  7706  7784 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-11 17:48:42.745  7706  7784 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-11 17:48:42.747  7706  7784 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-11 17:48:42.751  7706  7784 I         : BTE_InitTraceLevels -- TRC_HCI
08-11 17:48:42.751  7706  7784 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-11 17:48:42.751  7706  7784 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-11 17:48:42.751  7706  7784 I         : BTE_InitTraceLevels -- TRC_AVDT
08-11 17:48:42.751  7706  7784 I         : BTE_InitTraceLevels -- TRC_AVRC
08-11 17:48:42.751  7706  7784 I         : BTE_InitTraceLevels -- TRC_A2D
08-11 17:48:42.751  7706  7784 I         : BTE_InitTraceLevels -- TRC_BNEP
08-11 17:48:42.751  7706  7784 I         : BTE_InitTraceLevels -- TRC_BTM
08-11 17:48:42.751  7706  7784 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-11 17:48:42.751  7706  7784 I         : BTE_InitTraceLevels -- TRC_GAP
08-11 17:48:42.751  7706  7784 I         : BTE_InitTraceLevels -- TRC_PAN
08-11 17:48:42.751  7706  7784 I         : BTE_InitTraceLevels -- TRC_SDP
08-11 17:48:42.751  7706  7784 I         : BTE_InitTraceLevels -- TRC_GATT
08-11 17:48:42.751  7706  7784 I         : BTE_InitTraceLevels -- TRC_SMP
08-11 17:48:42.751  7706  7784 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-11 17:48:42.751  7706  7784 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-11 17:48:42.850  7706  7784 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-11 17:48:42.850  7706  7784 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01e9061 ,
08-11 17:48:42.850  7706  7784 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01e9061 
,08-11 17:48:42.911  7706  7750 E bt-btif : Calling BTA_HhEnable
,08-11 17:48:42.912  7706  7750 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,08-11 17:48:42.912  7706  7750 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-11 17:48:42.923  7706  7784 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-11 17:48:42.923  7706  7784 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-11 17:48:42.923  7706  7784 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-11 17:48:42.927  7706  7784 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-11 17:48:42.927  7706  7784 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-11 17:48:42.929  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-11 17:48:42.930  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-11 17:48:42.935  7706  7750 D BluetoothAdapterProperties: Name is: G3
,08-11 17:48:42.939  7706  7750 D BluetoothAdapterProperties: Scan Mode:20
08-11 17:48:42.939  7706  7750 D BluetoothAdapterProperties: Discoverable Timeout:120
08-11 17:48:42.940  7706  7750 D bt_hci_bdroid: postload
08-11 17:48:42.940  7706  7786 D bt_hci_bdroid: Used up Tx Cmd credits
08-11 17:48:42.941  7706  7750 D bte_conf: Device ID record 1 : primary
08-11 17:48:42.941  7706  7750 D bte_conf:   vendorId            = 00c4
08-11 17:48:42.941  7706  7750 D bte_conf:   vendorIdSource      = 0001
08-11 17:48:42.941  7706  7750 D bte_conf:   product             = 13a1
08-11 17:48:42.941  7706  7750 D bte_conf:   version             = 1000
08-11 17:48:42.941  7706  7750 D bte_conf:   clientExecutableURL = 
08-11 17:48:42.941  7706  7750 D bte_conf:   serviceDescription  = 
08-11 17:48:42.941  7706  7750 D bte_conf:   documentationURL    = 
08-11 17:48:42.941  7706  7750 D bte_conf: bte_load_did_conf no section named DID2.
08-11 17:48:42.942  7706  7784 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-11 17:48:42.945  7706  7746 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-11 17:48:42.945  7706  7746 D BluetoothAdapterProperties: ScanMode =  20
08-11 17:48:42.945  7706  7746 D BluetoothAdapterProperties: State =  11
08-11 17:48:42.945  7706  7746 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-11 17:48:42.946  7706  7746 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-11 17:48:42.946  7706  7746 D BluetoothAdapterProperties: Setting state to 12
08-11 17:48:42.946  7706  7746 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-11 17:48:42.934  7815  7815 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-11 17:48:42.952  7706  7750 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-11 17:48:42.953  7706  7750 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-11 17:48:42.934  7815  7815 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-11 17:48:42.962  1036  1119 D BluetoothManagerService: Message: 60
08-11 17:48:42.962  1036  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-11 17:48:42.962  1036  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
,08-11 17:48:42.966  7706  7786 D bt_hci_bdroid: Used up Tx Cmd credits
08-11 17:48:42.968  7706  7746 I BluetoothAdapterState: Entering On State
08-11 17:48:42.969  1856  1872 D BluetoothHeadset: onBluetoothStateChange: up=true
08-11 17:48:42.969  7706  7786 D bt_hci_bdroid: Used up Tx Cmd credits
08-11 17:48:42.973  7706  7746 D LGBluetoothServiceAdapter: [BTUI] OnState
08-11 17:48:42.973  7706  7746 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-11 17:48:42.974  7706  7746 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-11 17:48:42.974  7706  7746 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
,08-11 17:48:42.979  7706  7784 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-11 17:48:42.979  7706  7784 W bt-smp  : Plain text(LSB ~ MSB) = 31 aa 68 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-11 17:48:42.979  7706  7784 W bt-smp  : Encrypted text(LSB ~ MSB) = 0b af cd 60 71 1c 77 66 8f a5 2e f2 02 a7 e8 fb 
08-11 17:48:42.979  7706  7786 D bt_hci_bdroid: Used up Tx Cmd credits
08-11 17:48:42.979  7706  7784 W bt-btm  : Stopping oneshot timer
08-11 17:48:42.981  7706  7810 E bt_mct  : hci lib postload completed
08-11 17:48:42.998  7706  7750 D BluetoothAdapterProperties: Discoverable Timeout:120
08-11 17:48:42.998  7706  7750 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-11 17:48:43.018  7706  7746 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-11 17:48:43.025  7706  7784 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-11 17:48:43.025  7706  7784 W bt-smp  : Plain text(LSB ~ MSB) = 1f 21 78 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-11 17:48:43.025  7706  7784 W bt-smp  : Encrypted text(LSB ~ MSB) = 8a 85 d3 a8 89 76 90 d6 00 a3 d4 0f 81 19 55 55 
08-11 17:48:43.025  7706  7784 W bt-btm  : Stopping oneshot timer
08-11 17:48:43.025  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:48:43.025  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:48:43.025  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 17:48:43.025  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 17:48:43.025  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 17:48:43.025  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 17:48:43.025  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 17:48:43.025  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 17:48:43.039  6670  6670 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-11 17:48:43.055  7706  7784 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-11 17:48:43.055  7706  7784 W bt-smp  : Plain text(LSB ~ MSB) = e6 d0 4c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-11 17:48:43.055  7706  7784 W bt-smp  : Encrypted text(LSB ~ MSB) = c4 a2 a0 1b 22 b9 75 42 14 11 59 f4 b0 52 4a 73 
,08-11 17:48:43.057  7706  7784 W bt-btm  : Stopping oneshot timer
08-11 17:48:43.060  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:48:43.060  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:48:43.060  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 17:48:43.060  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 17:48:43.060  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 17:48:43.060  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 17:48:43.060  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 17:48:43.060  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 17:48:43.069  7820  7820 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-11 17:48:43.072  7706  7784 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-11 17:48:43.072  7706  7784 W bt-smp  : Plain text(LSB ~ MSB) = cf 82 5f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-11 17:48:43.072  7706  7784 W bt-smp  : Encrypted text(LSB ~ MSB) = 9f e0 a6 9c df 9d 58 44 19 89 b3 fd 18 1f 5c 3e 
08-11 17:48:43.072  7706  7784 W bt-btm  : Stopping oneshot timer
08-11 17:48:43.074  6670  6670 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 17:48:43.081  1856  1856 D BluetoothHeadset: Proxy object connected
08-11 17:48:43.082  6940  6955 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-11 17:48:43.087  7706  7784 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-11 17:48:43.087  7706  7784 W bt-smp  : Plain text(LSB ~ MSB) = 9e 99 42 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-11 17:48:43.087  7706  7784 W bt-smp  : Encrypted text(LSB ~ MSB) = 1a 56 04 23 e0 3b 69 74 4e 78 d4 5b 67 5b da 96 
08-11 17:48:43.088  7706  7784 W bt-btm  : Stopping oneshot timer
08-11 17:48:43.099  6940  6956 D BluetoothMap: onBluetoothStateChange: up=true
08-11 17:48:43.100  6940  6940 D BluetoothHeadset: Proxy object connected
08-11 17:48:43.100  6940  6940 D HeadsetProfile: Bluetooth service connected
,08-11 17:48:43.103  1856  2683 D BluetoothHeadset: onBluetoothStateChange: up=true
08-11 17:48:43.106  1856  1856 D BluetoothHeadset: Proxy object connected
08-11 17:48:43.106  6940  7620 D BluetoothPbap: onBluetoothStateChange: up=true
08-11 17:48:43.107  6940  6940 D BluetoothMap: Proxy object connected
08-11 17:48:43.107  6940  6940 D MapProfile: Bluetooth service connected
08-11 17:48:43.107  6940  6940 D BluetoothMap: getConnectedDevices()
08-11 17:48:43.107  1036  1119 D BluetoothA2dp: onBluetoothStateChange: up=true
08-11 17:48:43.108  6940  6956 D BluetoothPan: onBluetoothStateChange on: true
08-11 17:48:43.108  6940  6956 D BluetoothPan: onBluetoothStateChange call bindService
08-11 17:48:43.108  7706  7722 V BluetoothMapService: getConnectedDevices()
08-11 17:48:43.109  1036  1036 D BluetoothA2dp: Proxy object connected
08-11 17:48:43.110  6940  6955 D BluetoothA2dp: onBluetoothStateChange: up=true
08-11 17:48:43.112  6940  6940 D BluetoothPan: BluetoothPAN Proxy object connected
08-11 17:48:43.112  6940  6940 D PanProfile: Bluetooth service connected
08-11 17:48:43.112  6940  6955 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-11 17:48:43.114  6940  6940 D BluetoothA2dp: Proxy object connected
08-11 17:48:43.114  6940  6940 D A2dpProfile: Bluetooth service connected
,08-11 17:48:43.117  1036  1119 D BluetoothHeadset: onBluetoothStateChange: up=true
08-11 17:48:43.118  6940  6940 D BluetoothInputDevice: Proxy object connected
08-11 17:48:43.118  6940  6940 D HidProfile: Bluetooth service connected
08-11 17:48:43.118  1036  1036 D BluetoothHeadset: Proxy object connected
08-11 17:48:43.118  1856  4051 D BluetoothHeadset: onBluetoothStateChange: up=true
08-11 17:48:43.121  1856  1856 D BluetoothHeadset: Proxy object connected
08-11 17:48:43.122  1036  1119 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-11 17:48:43.122  1036  1119 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-11 17:48:43.124  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-11 17:48:43.125  1944  1944 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-11 17:48:43.125  1944  2082 D LGBluetoothAPIService: Message: 1
08-11 17:48:43.125  1944  2082 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-11 17:48:43.125  1944  2082 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-11 17:48:43.125  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-11 17:48:43.125  1944  2082 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-11 17:48:43.128  7706  7706 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-11 17:48:43.128  7706  7706 D BluetoothMapService: STATE_ON
08-11 17:48:43.128  7706  7706 V BluetoothMapService: Handler(): got msg=1
08-11 17:48:43.129  1036  1119 D BluetoothManagerService: Message: 40
08-11 17:48:43.129  1036  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-11 17:48:43.129  7706  7706 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-11 17:48:43.130  7706  7837 D BluetoothMapMasInstance: MAS initSocket()
08-11 17:48:43.131  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:48:43.133  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:48:43.134  6940  6940 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-11 17:48:43.135  6940  6940 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-11 17:48:43.137  7706  7837 D BluetoothMapMasInstance:   masId = 00
08-11 17:48:43.137  7706  7837 D BluetoothMapMasInstance:   msgTypes = 0e
08-11 17:48:43.137  7706  7837 D BluetoothMapMasInstance:   masName = SMS/MMS
08-11 17:48:43.137  7706  7837 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
,08-11 17:48:43.140  7706  7706 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@250ff708
08-11 17:48:43.140  7706  7706 V BluetoothPbapService: Pbap Service onCreate
08-11 17:48:43.140  1036  1914 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 17:48:43.140  7706  7706 V BluetoothPbapService: Starting PBAP service
08-11 17:48:43.141  7706  7706 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-11 17:48:43.141  7706  7706 V BluetoothPbapService: Pbap Service onBind
08-11 17:48:43.142  7706  7706 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-11 17:48:43.142  7706  7706 V BluetoothPbapService: state: 12
08-11 17:48:43.142  7706  7706 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-11 17:48:43.142  7706  7706 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-11 17:48:43.142  7706  7706 V BluetoothPbapReceiver: ***********state = 12
08-11 17:48:43.143  7706  7706 V BluetoothPbapService: Handler(): got msg=1
08-11 17:48:43.144  7706  7837 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-11 17:48:43.144  7706  7706 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-11 17:48:43.145  7706  7840 V BluetoothPbapService: Pbap Service initSocket
08-11 17:48:43.146  7706  7837 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-11 17:48:43.147  7706  7837 V BluetoothMapMasInstance: Succeed to create listening socket 
08-11 17:48:43.147  7706  7837 D BluetoothMapMasInstance: Accepting socket connection...
08-11 17:48:43.147  7706  7750 D BluetoothAdapterProperties: Scan Mode:21
08-11 17:48:43.147  7706  7750 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-11 17:48:43.147  2184  2184 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-11 17:48:43.148  2184  2184 D c       : Getting all permits...
08-11 17:48:43.148  2184  2184 D a       : Opening database...
08-11 17:48:43.151  2184  2184 D a       : Opening database auth.proximity.permit_store...
,08-11 17:48:43.152  2184  2184 D a       : Closing database...
08-11 17:48:43.152  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:48:43.153  1036  2008 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 17:48:43.154  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:48:43.155  7706  7840 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-11 17:48:43.157  7706  7840 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-11 17:48:43.157  7706  7840 V BluetoothPbapService: Succeed to create listening socket 
08-11 17:48:43.157  7706  7840 V BluetoothPbapService: Accepting socket connection...
08-11 17:48:43.157  6940  6940 D DockEventReceiver: finishStartingService: stopping service
08-11 17:48:43.158  6940  6940 D BluetoothPbap: Proxy object connected
08-11 17:48:43.158  6940  6940 D PbapServerProfile: Bluetooth service connected
08-11 17:48:43.167  6940  6940 D BluetoothPermissionRequest: onReceive
,08-11 17:48:43.169  6940  6940 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-11 17:48:43.170  6940  6940 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-11 17:48:43.173  7706  7706 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-11 17:48:43.174  7706  7706 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-11 17:48:43.178  7706  7706 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-11 17:48:43.191  7706  7706 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-11 17:48:43.191  7706  7706 V BtOppService: onCreate
,08-11 17:48:43.194  7706  7706 V BluetoothOppNotification: send message
08-11 17:48:43.197  7706  7706 V BtOppService: Starting RfcommListener
08-11 17:48:43.200  7706  7706 D BluetoothOppPreference: Dumping Names:  
08-11 17:48:43.200  7706  7706 D BluetoothOppPreference: {}
,08-11 17:48:43.200  7706  7706 D BluetoothOppPreference: Dumping Channels:  
08-11 17:48:43.200  7706  7706 D BluetoothOppPreference: {}
08-11 17:48:43.201  7706  7706 V BtOppService: onStartCommand
08-11 17:48:43.201  7706  7849 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-11 17:48:43.203  7706  7706 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-11 17:48:43.204  7706  7706 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-11 17:48:43.206  7706  7706 V BluetoothOppNotification: new notify threadi!
08-11 17:48:43.207  7706  7706 V BluetoothOppNotification: send delay message
08-11 17:48:43.208  7706  7706 V BtOppService: start RfcommListener
08-11 17:48:43.211  7706  7706 V BtOppService: RfcommListener started
08-11 17:48:43.211  7706  7851 V BtOppRfcommListener: Starting RFCOMM listener....
08-11 17:48:43.211  1036  1914 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 17:48:43.212  7706  7851 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-11 17:48:43.213  7706  7851 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-11 17:48:43.213  7706  7851 V BtOppRfcommListener: Started RFCOMM listener....
08-11 17:48:43.213  7706  7851 I BtOppRfcommListener: Accept thread started.
08-11 17:48:43.213  7706  7851 V BtOppRfcommListener: Accepting connection...
08-11 17:48:43.215  7706  7850 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-11 17:48:43.215  7706  7849 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,08-11 17:48:43.216  7706  7846 V BtOppService: Deleted complete outbound shares, number =  0
,08-11 17:48:43.217  7706  7849 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@13fbf72d on behalf of 
08-11 17:48:43.218  7706  7850 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@204b7a44 on behalf of 
08-11 17:48:43.218  7706  7850 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-11 17:48:43.219  7706  7846 V BtOppService: Deleted complete inbound failed shares, number = 0
08-11 17:48:43.219  7706  7846 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-11 17:48:43.221  7706  7846 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@21662462 on behalf of 
08-11 17:48:43.221  7706  7850 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-11 17:48:43.222  7706  7850 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1d5f89f3 on behalf of 
08-11 17:48:43.223  7706  7849 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-11 17:48:43.223  7706  7849 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-11 17:48:43.224  7706  7850 V BluetoothOppNotification: outbound: succ-0  fail-0
08-11 17:48:43.224  7706  7849 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2a7f6b0 on behalf of 
08-11 17:48:43.225  7706  7706 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@250ff708
08-11 17:48:43.225  7706  7849 V BluetoothOppNotification: update too frequent, put in queue
08-11 17:48:43.225  7706  7706 V BluetoothFtpService: Ftp Service onCreate
08-11 17:48:43.225  7706  7706 I BluetoothFtpService: Ftp Service onCreate
08-11 17:48:43.225  7706  7706 V BluetoothFtpService: Ftp Service onStartCommand
08-11 17:48:43.226  7706  7706 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-11 17:48:43.226  7706  7706 V BluetoothFtpService: Starting Listening on sockets
08-11 17:48:43.226  7706  7849 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-11 17:48:43.226  7706  7706 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-11 17:48:43.226  7706  7706 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-11 17:48:43.226  7706  7706 V BluetoothSapReceiver: SapReceiver onReceive 
08-11 17:48:43.226  7706  7706 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-11 17:48:43.226  7706  7706 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-11 17:48:43.226  7706  7706 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-11 17:48:43.227  7706  7850 V BluetoothOppNotification: outbound notification was removed.
08-11 17:48:43.228  7706  7850 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-11 17:48:43.228  7706  7706 V BtOppService: ContentObserver received notification
08-11 17:48:43.228  7706  7706 V BtOppService: ContentObserver received notification
08-11 17:48:43.228  7706  7706 V BluetoothFtpService: Handler(): got msg=1
,08-11 17:48:43.229  7706  7706 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-11 17:48:43.229  7706  7850 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@308624ae on behalf of 
08-11 17:48:43.229  7706  7706 V BluetoothFtpService: Ftp Service initSocket
08-11 17:48:43.229  7706  7852 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-11 17:48:43.229  7706  7852 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-11 17:48:43.230  7706  7852 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@14ded24f on behalf of 
08-11 17:48:43.231  7706  7852 V BluetoothOppNotification: update too frequent, put in queue
08-11 17:48:43.231  7706  7852 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-11 17:48:43.233  1036  2008 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 17:48:43.234  7706  7706 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-11 17:48:43.234  7706  7850 V BluetoothOppNotification: inbound: succ-0  fail-0
08-11 17:48:43.235  7706  7706 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=78
08-11 17:48:43.235  7706  7706 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-11 17:48:43.235  7706  7850 V BluetoothOppNotification: inbound notification was removed.
08-11 17:48:43.236  7706  7850 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-11 17:48:43.236  7706  7853 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-11 17:48:43.237  7706  7850 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3f0dcddc on behalf of 
08-11 17:48:43.247  7706  7706 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@250ff708
08-11 17:48:43.247  7706  7706 V BluetoothSapService: Sap Service onCreate
08-11 17:48:43.248  7706  7706 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-11 17:48:43.248  7706  7706 V BluetoothSapService: state: 12
,08-11 17:48:43.248  7706  7706 V BluetoothSapService: Starting SAP server process
08-11 17:48:43.250  7706  7706 V BluetoothSapService: SAP Service startRfcommListenerThread
08-11 17:48:43.234  7854  7854 W sapd    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-11 17:48:43.234  7854  7854 W sapd    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-11 17:48:43.252  7706  7855 V BluetoothSapService: Sap Service initRfcommSocket
08-11 17:48:43.252  1036  1624 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 17:48:43.253  7706  7855 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-11 17:48:43.253  7706  7855 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
08-11 17:48:43.254  7706  7855 V BluetoothSapService: Succeed to create listening socket 
,08-11 17:48:43.254  7706  7855 V BluetoothSapService: Accepting socket connection...
08-11 17:48:43.261  7854  7854 V BT_SAP  : Event pipe created
08-11 17:48:43.262  7854  7854 V BT_SAP  : create_server_socket qcom.sap.server
08-11 17:48:43.262  7854  7854 V BT_SAP  : created socket fd 6
,08-11 17:48:43.615  6670  6809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:48:43.615  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:48:43.615  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 17:48:43.615  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 17:48:43.615  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 17:48:43.615  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 17:48:43.615  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 17:48:43.615  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-11 17:48:43.620  6670  6809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 17:48:43.621  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:48:43.621  6670  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2fa22458 removed from the list
08-11 17:48:43.621  6670  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:48:43.621  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:48:43.621  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:48:43.623  6670  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 17:48:43.623  6670  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@232c79b1 added. We now have 4 listener(s)
08-11 17:48:43.623  6670  6809 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 17:48:43.626  1036  1981 D WifiServiceImplEx: setWifiEnabled: false pid=6670, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-11 17:48:43.626  1036  1981 D WifiService: setWifiEnabled: false pid=6670, uid=10118
08-11 17:48:43.626  1036  1981 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-11 17:48:43.630  6670  6809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 17:48:43.635  1036  1577 D WifiServiceImplEx: setWifiEnabled: true pid=6670, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-11 17:48:43.636  1036  1577 D WifiService: setWifiEnabled: true pid=6670, uid=10118
08-11 17:48:43.636  1036  1577 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-11 17:48:43.659  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-11 17:48:43.659  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-11 17:48:43.659  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-11 17:48:43.661  1036  1539 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-11 17:48:43.661  1036  1539 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-11 17:48:43.670  1036  1539 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-11 17:48:43.670  1036  1539 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-11 17:48:43.670  1036  1539 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-11 17:48:43.670  1036  1539 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-11 17:48:43.670  1036  1539 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-11 17:48:43.670  1036  1539 E WifiHW  : unknown target_country: EU , set to default
08-11 17:48:43.670  1036  1539 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-11 17:48:43.670  1036  1539 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-11 17:48:43.670  1036  1539 I WifiUtil: gEnableBmps=1
,08-11 17:48:44.209  7706  7706 V BluetoothOppNotification: new notify threadi!
,08-11 17:48:44.210  7706  7706 V BluetoothOppNotification: send delay message
,08-11 17:48:44.224  7706  7874 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-11 17:48:44.229  7706  7874 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3a97ebc8 on behalf of 
,08-11 17:48:44.271   318   894 D SoftapController: Softap fwReload - Ok
,08-11 17:48:44.298  1036  1539 E NetdConnector: NDC Command {67 softap fwreload wlan0 STA} took too long (619ms)
,08-11 17:48:44.314  1036  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-11 17:48:44.314  1036  1119 D Tethering: InitialState.processMessage what=4
,08-11 17:48:44.325   318   894 D CommandListener: Setting iface cfg
08-11 17:48:44.325   318   894 D CommandListener: Trying to bring down wlan0
08-11 17:48:44.327   318   894 D CommandListener: Clearing all IP addresses on wlan0
,08-11 17:48:44.334  1036  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-11 17:48:44.337  1036  1539 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-11 17:48:44.334  7876  7876 W wpa_supplicant: type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-11 17:48:44.344  7876  7876 W wpa_supplicant: type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-11 17:48:44.370  6940  6940 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-11 17:48:44.370  1036  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-11 17:48:44.370  1036  1539 E WifiStateMachine: useWiFiOffloading() : false
08-11 17:48:44.370  1036  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-11 17:48:44.371  6940  6940 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-11 17:48:44.371  6940  6940 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-11 17:48:44.371  6940  6940 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-11 17:48:44.374  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-11 17:48:44.377  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-11 17:48:44.386  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-11 17:48:44.386  6940  6940 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-11 17:48:44.387  1036  1539 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-11 17:48:44.387  1036  1539 D WifiMonitor: connecting to supplicant
08-11 17:48:44.387  6940  6940 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true,
08-11 17:48:44.388  6940  6940 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-11 17:48:44.388  6940  6940 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-11 17:48:44.388  6940  6940 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-11 17:48:44.388  6940  6940 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-11 17:48:44.388  6940  6940 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-11 17:48:44.388  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:48:44.389  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:48:44.390  7876  7876 I wpa_supplicant: Successfully initialized wpa_supplicant
08-11 17:48:44.391  7706  7874 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-11 17:48:44.393  6940  6940 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-11 17:48:44.393  6940  6940 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-11 17:48:44.393  6940  6940 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-11 17:48:44.393  6940  6940 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-11 17:48:44.394  6940  6940 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-11 17:48:44.395  6940  6940 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-11 17:48:44.395  6940  6940 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-11 17:48:44.395  6940  6940 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-11 17:48:44.395  6940  6940 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-11 17:48:44.395  6940  6940 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-11 17:48:44.396  6940  6940 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-11 17:48:44.402  7706  7874 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-11 17:48:44.406  6922  6922 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-11 17:48:44.408  6940  6940 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-11 17:48:44.410  7706  7874 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@21368461 on behalf of 
08-11 17:48:44.411  7706  7874 V BluetoothOppNotification: outbound: succ-0  fail-0
08-11 17:48:44.414  7706  7874 V BluetoothOppNotification: outbound notification was removed.
,08-11 17:48:44.414  7706  7874 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-11 17:48:44.415  7876  7876 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-11 17:48:44.415  7876  7876 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-11 17:48:44.416  7706  7874 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@4921b86 on behalf of 
08-11 17:48:44.417  7706  7874 V BluetoothOppNotification: inbound: succ-0  fail-0
08-11 17:48:44.419  6940  6940 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-11 17:48:44.419  7706  7874 V BluetoothOppNotification: inbound notification was removed.
08-11 17:48:44.420  7706  7874 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-11 17:48:44.421  7706  7874 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@63cbc47 on behalf of 
08-11 17:48:44.426  7030  7893 W FormManager: Network not available. Please check & try again.
,08-11 17:48:44.429  7030  7894 V FormManager: Network unavailable.
08-11 17:48:44.435  7030  7894 V FormManager: Network unavailable.
08-11 17:48:44.520  7876  7876 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-11 17:48:44.544  7876  7876 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-11 17:48:44.559  1036  1539 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,08-11 17:48:44.559  7876  7876 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-11 17:48:44.560  1036  7896 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
,08-11 17:48:44.560  1036  7896 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-11 17:48:44.560  1036  7896 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-11 17:48:44.560  1036  7896 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-11 17:48:44.560  1036  1539 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
,08-11 17:48:44.561  1036  1539 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-11 17:48:44.561  1036  1539 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
,08-11 17:48:44.562  1036  1539 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-11 17:48:44.563  1036  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-11 17:48:44.564  1036  1539 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-11 17:48:44.565  1036  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-11 17:48:44.565  1036  1539 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-11 17:48:44.565  1036  1539 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-11 17:48:44.566  1036  1539 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-11 17:48:44.566  1036  1539 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-11 17:48:44.566  1036  1539 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-11 17:48:44.567  1036  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-11 17:48:44.567  1036  1539 E WifiStateMachine: useWiFiOffloading() : false
08-11 17:48:44.567  1036  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-11 17:48:44.567  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 17:48:44.567  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 17:48:44.568  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 17:48:44.568  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 17:48:44.568  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-11 17:48:44.568  1036  1539 D WifiNative-wlan0: doBoolean: SET update_config 1
08-11 17:48:44.568  1036  1539 D WifiNative-wlan0: SET update_config 1: returned true
08-11 17:48:44.568  1036  1539 D WifiConfigStore: Loading config and enabling all networks 
08-11 17:48:44.568  1036  1539 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-11 17:48:44.569  1036  1539 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-11 17:48:44.570  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 17:48:44.571  1944  1944 D WfdService: Waiting for WifiP2p enabling
08-11 17:48:44.581  1036  1539 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-11 17:48:44.586  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-11 17:48:44.586  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:48:44.586  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:48:44.586  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 17:48:44.586  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:48:44.586  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 17:48:44.586  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 17:48:44.586  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 17:48:44.586  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 17:48:44.586  1036  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-11 17:48:44.592  1036  1539 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-11 17:48:44.592  1036  1539 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-11 17:48:44.592  6670  6670 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-11 17:48:44.594  1036  1539 D WifiStateMachine: enableVerboseLogging : level 2
08-11 17:48:44.595  1036  1539 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-11 17:48:44.596  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:48:44.596  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:48:44.596  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 17:48:44.596  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:48:44.596  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 17:48:44.596  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 17:48:44.596  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 17:48:44.596  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-11 17:48:44.597  1036  1539 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-11 17:48:44.597  1036  1539 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-11 17:48:44.597  1036  1539 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-11 17:48:44.597  6922  6922 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-11 17:48:44.597  1036  1539 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-11 17:48:44.598  1036  1539 D WifiNative-wlan0: SET model_name LG-D855: returned true
,08-11 17:48:44.598  1036  1539 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-11 17:48:44.599  1036  1539 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-11 17:48:44.599  1036  1539 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-11 17:48:44.599  6670  6670 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-11 17:48:44.599  1036  1539 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-11 17:48:44.599  1036  1539 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-11 17:48:44.600  1036  1539 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-11 17:48:44.600  1036  1539 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-11 17:48:44.600  1036  1539 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-11 17:48:44.602  6940  6940 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-11 17:48:44.603  1036  1539 D WifiStateMachine: Setting OUI to DA-A1-19
08-11 17:48:44.603  1036  1539 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-11 17:48:44.603  1944  1944 D WfdsService: Supplicant Connection state is changed : true
08-11 17:48:44.603  1944  2276 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-11 17:48:44.603  1944  2276 D WfdsService: Set the WFDS Monitor: true
08-11 17:48:44.604  1944  2276 D WfdsMonitor: WfdsMonitorThread create
08-11 17:48:44.604  1944  2276 D WfdsMonitor: WFDS Monitor is created and started
08-11 17:48:44.604  1944  2276 D WfdsService: WiFi: Supplicant connection re-established
08-11 17:48:44.604  1036  1539 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-11 17:48:44.604  1036  1539 D WifiNative-HAL: Setting external_sim to 1
08-11 17:48:44.604  1036  1539 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-11 17:48:44.605  1036  1539 D WifiNative-wlan0: SET external_sim 1: returned true
08-11 17:48:44.605  1036  1539 I WifiNative-HAL: startHal
08-11 17:48:44.605  1036  1539 D wifi    : setting scan oui 0xaf6a0a40
08-11 17:48:44.605  1036  1539 D WifiStateMachine: Setting OUI to DA-A1-19
08-11 17:48:44.605  1036  1539 I WifiNative-HAL: startHal
08-11 17:48:44.605  1036  1539 D wifi    : setting scan oui 0xaf6a0a40
08-11 17:48:44.605  1036  1539 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-11 17:48:44.606  1944  7899 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-11 17:48:44.606  1944  7899 E CtrlSupplicant: Succeed to open control connection
08-11 17:48:44.606  1036  1539 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-11 17:48:44.606  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-11 17:48:44.606  1944  7899 E CtrlSupplicant: Succeed to open monitor connection
08-11 17:48:44.607  7876  7876 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-11 17:48:44.607  1036  1539 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-11 17:48:44.607  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-11 17:48:44.608  7876  7876 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-11 17:48:44.608  1944  7899 D WfdsMonitor: Supplicant connection established
08-11 17:48:44.608  1944  2276 D WfdsService: Connected to the supplicant for wfds
08-11 17:48:44.608  1036  1539 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-11 17:48:44.608  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-11 17:48:44.608  7876  7876 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-11 17:48:44.609  1036  1539 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-11 17:48:44.609  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-11 17:48:44.609  7876  7876 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-11 17:48:44.609  7030  7898 W FormManager: Network not available. Please check & try, again.
08-11 17:48:44.610  1036  1539 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-11 17:48:44.610  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-11 17:48:44.610  7876  7876 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-11 17:48:44.610  1036  1539 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-11 17:48:44.610  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-11 17:48:44.611  7876  7876 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-11 17:48:44.611  1036  1539 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-11 17:48:44.611  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-11 17:48:44.611  7876  7876 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-11 17:48:44.611  6940  6940 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-11 17:48:44.612  1036  1539 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-11 17:48:44.613  1036  1539 E WifiNative: : [203,524,495 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-11 17:48:44.613  1036  1539 D WifiNative-wlan0: doBoolean: RECONNECT
,08-11 17:48:44.613  1036  1539 D WifiNative-wlan0: RECONNECT: returned true
,08-11 17:48:44.613  1036  1539 D WifiNative-wlan0: doString: [STATUS]
08-11 17:48:44.614  1036  7896 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-11 17:48:44.614  1036  7896 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-11 17:48:44.615  1036  1539 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-11 17:48:44.615  1036  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-11 17:48:44.615  1036  1539 D WifiNative-wlan0: SET ps 1: returned true
08-11 17:48:44.616  1036  1538 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:44.617   318   894 D CommandListener: Setting iface cfg
08-11 17:48:44.617   318   894 D CommandListener: Trying to bring up p2p0
08-11 17:48:44.617  1036  1538 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-11 17:48:44.617  1036  1538 D LGWifiP2pService: P2pEnablingState
08-11 17:48:44.617  1036  1538 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:44.617  1036  1538 D LGWifiP2pService: P2p socket connection successful
08-11 17:48:44.618  1036  1538 D LGWifiP2pService: P2pEnabledState
08-11 17:48:44.621  7030  7900 V FormManager: Network unavailable.
08-11 17:48:44.622  1036  1538 D LGWifiP2pService: sending p2p connection changed broadcast
08-11 17:48:44.623  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-11 17:48:44.623  1944  1944 D WfdsService: WifiP2pState is changed : true
08-11 17:48:44.623  1944  2276 D WfdsService: Receive the WFDS_ENABLE Method
08-11 17:48:44.623  1944  2276 D WfdsService: Set the WFDS Monitor: true
08-11 17:48:44.624  1944  2276 D WfdsService: Connected to the supplicant for wfds
08-11 17:48:44.624  1944  2276 D WfdsJNI : doCommand: WFDS_SET TRUE
08-11 17:48:44.624  7876  7876 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-11 17:48:44.624  1036  1538 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-11 17:48:44.624  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
08-11 17:48:44.624  1944  2276 D WfdsService: selectPreferredScanChannel [36]
08-11 17:48:44.624  1036  1036 D RttService: SCAN_AVAILABLE : 3
08-11 17:48:44.624  1944  2276 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-11 17:48:44.625  1036  1538 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-11 17:48:44.625  1036  1538 D WifiNative-p2p0: doBoolean: SET device_name G3
08-11 17:48:44.625  1036  1557 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:44.625  1036  1557 I WifiNative-HAL: startHal
08-11 17:48:44.625  1036  1538 D WifiNative-p2p0: SET device_name G3: returned true
08-11 17:48:44.625  1036  1538 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-11 17:48:44.625  1036  1538 D LGWifiP2pService: before postfix = G3
08-11 17:48:44.625  1036  1538 D WifiServerServiceExt: postfix byte check : 2
,08-11 17:48:44.625  1036  1538 D LGWifiP2pService: after postfix = G3
08-11 17:48:44.625  1036  1558 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:44.625  1036  1538 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-11 17:48:44.626  1036  1538 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-11 17:48:44.626  1036  1538 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-11 17:48:44.626  1944  1944 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-11 17:48:44.627  1944  1944 D WfdsService: isConnected: false
08-11 17:48:44.627  1036  1539 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-11 17:48:44.628  1036  1539 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-11 17:48:44.628  1036  1538 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-11 17:48:44.628  1036  1539 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-11 17:48:44.629  1036  1539 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-11 17:48:44.629  1036  1539 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-11 17:48:44.629  1036  1539 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-11 17:48:44.630  1036  1557 D wifi    : getting scan capabilities on interface[1] = 0xaf6a0a40
08-11 17:48:44.630  1036  1557 D wifi    : failed to get capabilities : -3
08-11 17:48:44.630  1036  1557 E WifiScanningService: could not get scan capabilities
08-11 17:48:44.630  1036  1539 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-11 17:48:44.630  1036  1539 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-11 17:48:44.630  1036  1538 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-11 17:48:44.630  7876  7876 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-11 17:48:44.630  1036  1538 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-11 17:48:44.630  1036  1538 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-11 17:48:44.631  1036  1538 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-11 17:48:44.631  1036  1538 D WifiNative-HAL: p2pGetDeviceAddress
08-11 17:48:44.631  1036  1538 D WifiNative-HAL: p2pGetDeviceAddress returning 
08-11 17:48:44.631  7030  7900 V FormManager: Network unavailable.
08-11 17:48:44.631  1036  1538 D LGWifiP2pService: DeviceAddress: 
08-11 17:48:44.631  1036  1538 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-11 17:48:44.631  1036  1538 D WifiNative-p2p0: P2P_FLUSH: returned false
08-11 17:48:44.631  1036  1538 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-11 17:48:44.631  1036  1538 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-11 17:48:44.632  1036  1538 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-11 17:48:44.632  1944  1944 I WfdStateTracker: handleP2pThisDeviceChanged
08-11 17:48:44.632  1944  1944 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-11 17:48:44.632  1036  1538 D WifiNative-p2p0:    returned OK
08-11 17:48:44.632  1944  1944 D WfdsService: Update P2p Interface State: 3
08-11 17:48:44.632  1036  1538 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-11 17:48:44.632  1036  1539 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-11 17:48:44.633  1036  1539 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-11 17:48:44.633  1036  1539 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-11 17:48:44.633  1036  1539 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-11 17:48:44.634  4365  4365 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-11 17:48:44.635  4365  4365 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-11 17:48:44.637  4365  4365 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.conten,t.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-11 17:48:44.639  4365  4365 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-11 17:48:44.643  7433  7433 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-11 17:48:44.643  7433  7433 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-11 17:48:44.643  7433  7433 V [BNRBootReceiver]: Boot Receiver Return
08-11 17:48:44.644  4365  7902 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-11 17:48:44.646  4365  7903 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-11 17:48:44.646  4365  7903 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-11 17:48:44.650  7876  7876 E wpa_supplicant: disconnect_rssi_lvl: -100
08-11 17:48:44.650  1036  1538 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-11 17:48:44.650  1036  1538 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-11 17:48:44.650  1036  1539 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-11 17:48:44.650  1036  1538 D LGWifiP2pService: InactiveState
08-11 17:48:44.650  1036  1538 D LGWifiP2pService: InactiveState{ when=-18ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:44.650  1036  1539 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
,08-11 17:48:44.650  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=-19ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:44.651  1036  1538 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-11 17:48:44.651  7876  7876 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-11 17:48:44.652  7876  7876 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-11 17:48:44.652  1036  7896 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-11 17:48:44.652  1036  7896 E WifiMonitor: WifiMonitor:p2p0 cnt=35 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-11 17:48:44.652  1036  7896 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-11 17:48:44.652  1036  7896 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-11 17:48:44.652  1036  1539 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-11 17:48:44.652  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-11 17:48:44.652  7876  7876 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-11 17:48:44.652  7876  7876 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 17:48:44.652  1036  7896 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-11 17:48:44.652  1036  1538 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-11 17:48:44.652  1036  7896 E WifiMonitor: WifiMonitor:p2p0 cnt=36 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 17:48:44.653  1036  7896 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 17:48:44.653  1036  7896 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 17:48:44.653  1036  1538 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:44.653  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:44.653  1036  1538 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:44.653  1036  1538 D LGWifiP2pService: InactiveState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:44.653  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:44.653  1036  1538 D LGWifiP2pService: DefaultState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:44.653  1036  1538 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:44.653  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:44.653  1036  1538 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:44.653  1036  1538 D LGWifiP2pService: InactiveState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:44.653  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:44.653  1036  1538 D LGWifiP2pService: DefaultState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:44.654  7876  7876 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-11 17:48:44.654  1944  2276 W WfdsService: DefaultState - msg [9441285] is not handled,
08-11 17:48:44.654  1944  7899 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-11 17:48:44.654  1944  7899 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-11 17:48:44.654  1036  1036 E WifiServerServiceExt: No p2p device connected
08-11 17:48:44.654  7876  7876 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-11 17:48:44.654  1036  7896 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-11 17:48:44.654  1036  7896 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-11 17:48:44.654  1036  7896 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-11 17:48:44.654  1036  7896 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-11 17:48:44.655  7876  7876 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-11 17:48:44.655  7876  7876 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 17:48:44.655  1944  7899 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-11 17:48:44.655  1036  7896 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-11 17:48:44.655  1036  7896 E WifiMonitor: WifiMonitor:p2p0 cnt=38 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 17:48:44.655  1036  7896 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 17:48:44.655  1036  7896 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 17:48:44.655  7876  7876 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-11 17:48:44.655  1944  7899 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-11 17:48:44.656  1036  7896 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-11 17:48:44.656  1036  7896 E WifiMonitor: WifiMonitor:p2p0 cnt=39 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 17:48:44.656  1036  7896 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 17:48:44.656  1036  7896 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 17:48:44.656  7876  7876 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 17:48:44.656  1944  7899 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-11 17:48:44.656  1036  7896 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,08-11 17:48:44.656  1036  7896 E WifiMonitor: WifiMonitor:p2p0 cnt=40 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 17:48:44.656  1036  7896 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 17:48:44.656  1036  7896 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 17:48:44.656  1036  1539 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-11 17:48:44.657  1036  1539 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-11 17:48:44.657  1036  1539 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-11 17:48:44.657  1036  1538 D LGWifiP2pService: InactiveState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
,08-11 17:48:44.657  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:44.657  1036  1539 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-11 17:48:44.657  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-11 17:48:44.657  7876  7876 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-11 17:48:44.658  7876  7876 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-11 17:48:44.658  1036  7896 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-11 17:48:44.658  1036  7896 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-11 17:48:44.658  1036  7896 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-11 17:48:44.658  1036  7896 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,08-11 17:48:44.658  1036  1539 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-11 17:48:44.658  1036  1539 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-11 17:48:44.659  1036  1539 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-11 17:48:44.659  1036  1539 D WifiNative-wlan0: doBoolean: SCAN
08-11 17:48:44.659  1036  1539 D WifiNative-wlan0: SCAN: returned false
08-11 17:48:44.659  1036  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=203572  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-11 17:48:44.660  1036  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=203573  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-11 17:48:44.661  1036  1539 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-11 17:48:44.661  1036  1539 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,08-11 17:48:44.662  1036  1539 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-11 17:48:44.662  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-11 17:48:44.662  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-11 17:48:44.662  1036  1539 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-11 17:48:44.663  1036  1539 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-11 17:48:44.663  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-11 17:48:44.664  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 17:48:44.664  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 17:48:44.664  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-11 17:48:44.666  6495  6495 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-11 17:48:44.666  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-11 17:48:44.667  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
08-11 17:48:44.673  6940  6940 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-11 17:48:44.678  6940  6940 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-11 17:48:44.687  6989  6989 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-11 17:48:44.688  6989  6989 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-11 17:48:44.689  6989  6989 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-11 17:48:45.225  7876  7876 E wpa_supplicant: USIM:  scard_init function
08-11 17:48:45.227  7876  7876 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-11 17:48:45.237  1036  7896 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-11 17:48:45.237  1036  7896 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-11 17:48:45.237  1036  7896 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-11 17:48:45.237  1036  7896 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: WPS-AP-AVAILABLE 
08-11 17:48:45.239  1036  1539 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-11 17:48:45.239  1036  1539 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-11 17:48:45.239  1036  1539 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-11 17:48:45.240  1036  1539 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-11 17:48:45.240  1036  1539 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-11 17:48:45.241  1036  7896 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-11 17:48:45.241  1036  7896 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-11 17:48:45.241  1036  7896 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-11 17:48:45.259  1036  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=204171  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-11 17:48:45.268  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 17:48:45.268  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 17:48:45.268  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-11 17:48:45.269  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-11 17:48:45.270  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-11 17:48:45.272  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-11 17:48:45.277  1036  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=204189  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-11 17:48:45.282  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 17:48:45.282  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 17:48:45.282  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-11 17:48:45.283  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-11 17:48:45.283  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-11 17:48:45.288  6940  6940 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-11 17:48:45.296  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-11 17:48:45.296  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-11 17:48:45.299  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-11 17:48:45.310  6940  6940 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-11 17:48:45.315  6495  6495 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-11 17:48:45.329  6940  6940 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-11 17:48:45.337  6940  6940 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-11 17:48:45.344  6989  6989 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-11 17:48:45.345  6989  6989 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-11 17:48:45.348  6989  6989 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-11 17:48:45.355  7876  7876 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-11 17:48:45.359  1036  7896 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-11 17:48:45.359  1036  7896 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-11 17:48:45.359  1036  7896 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-11 17:48:45.359  1036  7896 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-11 17:48:45.359  1036  7896 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-11 17:48:45.359  1036  7896 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-11 17:48:45.363  7876  7876 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-11 17:48:45.363  7876  7876 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-11 17:48:45.368  1036  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=204278  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-11 17:48:45.368  1036  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=204280  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-11 17:48:45.369  1036  1539 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 46 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=204281
08-11 17:48:45.369  1036  1539 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 46 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=204281
08-11 17:48:45.369  1036  1539 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 46 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=204282
08-11 17:48:45.370  1036  1539 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 46 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=204282
08-11 17:48:45.372  1036  7896 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
,08-11 17:48:45.377  1036  7896 E WifiMonitor: WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-11 17:48:45.378  1036  7896 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-11 17:48:45.378  1036  7896 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-11 17:48:45.378  1036  7896 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-11 17:48:45.378  1036  7896 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-11 17:48:45.378  1036  7896 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-11 17:48:45.379  1036  7896 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-11 17:48:45.379  1036  7896 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-11 17:48:45.379  1036  7896 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-11 17:48:45.382  1036  1539 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 46 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=204294
08-11 17:48:45.384  1036  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=204296  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,08-11 17:48:45.393  6495  6495 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-11 17:48:45.396  1036  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-11 17:48:45.397  1036  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=204309  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-11 17:48:45.399  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-11 17:48:45.399  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-11 17:48:45.399  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 17:48:45.399  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 17:48:45.401  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-11 17:48:45.403  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-11 17:48:45.406  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-11 17:48:45.406  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 17:48:45.406  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-11 17:48:45.406  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-11 17:48:45.406  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-11 17:48:45.406  1036  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=204318  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-11 17:48:45.407  1036  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=204319  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-11 17:48:45.407  1036  1539 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=204320
08-11 17:48:45.408  1036  1539 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=204320
08-11 17:48:45.408  1036  1539 D WifiNative-wlan0: doString: [STATUS]
08-11 17:48:45.409  1036  7896 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-11 17:48:45.409  1036  7896 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-11 17:48:45.409  1036  1539 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-11 17:48:45.410  1036  1539 I WifiServiceExtension: setVHTCapabilityType  : false
08-11 17:48:45.413  6940  6940 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-11 17:48:45.417  1036  1539 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-11 17:48:45.417  1036  1539 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-11 17:48:45.420  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-11 17:48:45.420  6940  6940 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-11 17:48:45.420  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-11 17:48:45.422  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 17:48:45.422  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 17:48:45.422  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-11 17:48:45.424  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 17:48:45.425  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 17:48:45.425  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 17:48:45.425  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-11 17:48:45.428  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-11 17:48:45.428  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-11 17:48:45.429  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 17:48:45.430  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-11 17:48:45.430  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-11 17:48:45.431  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 17:48:45.432  6989  6989 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-11 17:48:45.432  6989  6989 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-11 17:48:45.433  1036  1539 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-11 17:48:45.433  1036  1545 D ConnectivityService: Got NetworkAgent Messenger
08-11 17:48:45.433  6989  6989 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-11 17:48:45.433  1036  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-11 17:48:45.433  1036  1545 D ConnectivityService: NetworkAgent connected
08-11 17:48:45.433  1036  1539 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-11 17:48:45.433  1036  1539 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-11 17:48:45.434  1036  1539 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-11 17:48:45.434  1036  1539 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-11 17:48:45.437  6495  6495 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-11 17:48:45.443  6940  6940 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-11 17:48:45.448  6940  6940 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-11 17:48:45.451  1036  1539 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-11 17:48:45.451  1036  1539 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-11 17:48:45.451  1036  1539 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-11 17:48:45.451  1036  1539 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-11 17:48:45.451  1036  1539 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-11 17:48:45.454  6989  6989 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-11 17:48:45.455  6989  6989 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-11 17:48:45.455  6989  6989 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-11 17:48:45.458  1036  1539 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-11 17:48:45.459   318   894 D CommandListener: Setting iface cfg
08-11 17:48:45.460  6940  6940 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-11 17:48:45.460  6940  6940 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-11 17:48:45.460  6940  6940 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-11 17:48:45.460  6940  6940 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-11 17:48:45.460  6940  6940 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-11 17:48:45.461  6940  6940 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-11 17:48:45.461  6940  6940 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-11 17:48:45.461  6940  6940 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-11 17:48:45.461  6940  6940 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-11 17:48:45.461  6940  6940 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-11 17:48:45.461  6940  6940 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-11 17:48:45.461  6940  6940 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-11 17:48:45.464  6495  6495 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-11 17:48:45.464  1036  1539 E WifiStateMachine: Start Dhcp Watchdog 2
08-11 17:48:45.464  1036  7932 D DhcpStateMachine: StoppedState
08-11 17:48:45.464  1036  7932 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:45.464  1036  7932 D DhcpStateMachine: WaitBeforeStartState
08-11 17:48:45.464  1036  1539 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=204377  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-11 17:48:45.465  1036  1539 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=204377  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-11 17:48:45.465  1036  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=204377  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-11 17:48:45.468  1036  1539 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-11 17:48:45.468  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-11 17:48:45.468  1036  1539 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-11 17:48:45.469  1036  1539 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-11 17:48:45.469  1036  1539 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-11 17:48:45.469  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-11 17:48:45.469  1036  1036 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-11 17:48:45.470  1036  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-11 17:48:45.472  6940  6940 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-11 17:48:45.473  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-11 17:48:45.473  1036  1036 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-11 17:48:45.474  1036  1539 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=204386  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-11 17:48:45.474  1036  1539 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=204387  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-11 17:48:45.475  1036  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=204387  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-11 17:48:45.476  1036  1539 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:158596] from screen [on:0 period:2051710244] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-11 17:48:45.476  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:2051710244] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-11 17:48:45.476  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-11 17:48:45.477  6940  6940 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-11 17:48:45.479  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-11 17:48:45.479  1036  1545 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-11 17:48:45.480  1036  1539 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-11 17:48:45.480  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-11 17:48:45.480  1036  1539 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-11 17:48:45.481  1036  1539 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-11 17:48:45.481  1036  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-11 17:48:45.482  1036  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-11 17:48:45.482  6989  6989 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-11 17:48:45.482  1036  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-11 17:48:45.482  6989  6989 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-11 17:48:45.482  1036  1539 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=132,0,0
08-11 17:48:45.482  6989  6989 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-11 17:48:45.482  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=132,0,0
08-11 17:48:45.482  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-11 17:48:45.483  7876  7876 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-11 17:48:45.483  1036  1539 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-11 17:48:45.483  1036  1539 D WifiNative-wlan0: doBoolean: SET ps 0
08-11 17:48:45.483  1036  1539 D WifiNative-wlan0: SET ps 0: returned true
08-11 17:48:45.483  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-11 17:48:45.483  7876  7876 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-11 17:48:45.483  1036  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-11 17:48:45.484  1036  1538 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@f8b631c target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:45.484  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@f8b631c target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:45.484  1036  7932 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:45.484  1036  7932 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-11 17:48:45.485  1036  1539 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-11 17:48:45.485  1036  1539 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-11 17:48:45.485  1036  1539 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-11 17:48:45.486  6495  6495 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-11 17:48:45.486   318   894 D CommandListener: Setting iface cfg
08-11 17:48:45.486   318   894 D CommandListener: Trying to bring up wlan0
08-11 17:48:45.487  1036  1539 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-11 17:48:45.491  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-11 17:48:45.491  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-11 17:48:45.491  6940  6940 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-11 17:48:45.491  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-11 17:48:45.491  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-11 17:48:45.491  1036  1539 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-11 17:48:45.492  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-11 17:48:45.492  1036  1539 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-11 17:48:45.492  1036  1539 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-11 17:48:45.493  1036  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-11 17:48:45.493  1036  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-11 17:48:45.494  1036  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-11 17:48:45.494  1036  1539 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-11 17:48:45.494  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-11 17:48:45.495  1036  1538 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:45.495  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:45.496  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-11 17:48:45.496  7876  7876 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-11 17:48:45.496  1036  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-11 17:48:45.496  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-11 17:48:45.496  6940  6940 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-11 17:48:45.496  7876  7876 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-11 17:48:45.497  1036  1539 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-11 17:48:45.497  1036  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-11 17:48:45.500  6989  6989 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-11 17:48:45.501  6989  6989 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-11 17:48:45.501  6989  6989 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-11 17:48:45.504  6495  6495 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-11 17:48:45.507  6940  6940 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-11 17:48:45.511  6940  6940 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-11 17:48:45.512  1036  1539 D WifiNative-wlan0: SET ps 1: returned true
08-11 17:48:45.513  1036  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-11 17:48:45.513  1036  1539 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-11 17:48:45.513  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-11 17:48:45.513  1036  1539 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-11 17:48:45.514  1036  1545 D ConnectivityService: ignoring duplicate network state non-change
08-11 17:48:45.516  6989  6989 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-11 17:48:45.516  6989  6989 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-11 17:48:45.516  6989  6989 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-11 17:48:45.517  1036  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-11 17:48:45.517  1036  1545 D ConnectivityService: Adding iface wlan0 to network 101
08-11 17:48:45.519  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-11 17:48:45.519  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-11 17:48:45.521  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 17:48:45.521  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 17:48:45.522  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 17:48:45.522  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-11 17:48:45.525  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 17:48:45.525  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 17:48:45.525  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-11 17:48:45.525  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-11 17:48:45.526  1944  1944 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-11 17:48:45.528  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 17:48:45.528  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 17:48:45.529  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-11 17:48:45.533  6495  6495 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-11 17:48:45.533  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-11 17:48:45.536  1036  1539 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-11 17:48:45.537  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 17:48:45.537  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 17:48:45.537  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-11 17:48:45.539  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-11 17:48:45.540  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-11 17:48:45.541  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 17:48:45.543  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-11 17:48:45.543  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-11 17:48:45.543  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 17:48:45.546  1036  1545 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-11 17:48:45.546  1036  1545 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-11 17:48:45.547  1036  1545 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-11 17:48:45.547  6940  6940 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-11 17:48:45.547   318   894 E Netd    : netlink response contains error (File exists)
08-11 17:48:45.548  1036  1545 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-11 17:48:45.548  1036  1545 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-11 17:48:45.548  1036  1545 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-11 17:48:45.548  1036  1545 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-11 17:48:45.548  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-11 17:48:45.549  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-11 17:48:45.549  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 17:48:45.549  1036  1545 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-11 17:48:45.549  1036  1545 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-11 17:48:45.549  1036  1545 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-11 17:48:45.550  1036  7931 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:45.550  1036  7931 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-11 17:48:45.550  1036  7931 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:45.550  1036  7931 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-11 17:48:45.552  1036  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-11 17:48:45.552  1036  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-11 17:48:45.552  1036  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-11 17:48:45.552  1036  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-11 17:48:45.552  1036  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-11 17:48:45.552  1036  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-11 17:48:45.552  1036  1545 D ConnectivityService: currentScore = 0, newScore = 20
08-11 17:48:45.552  1036  1545 D ConnectivityService:    accepting network in place of null
08-11 17:48:45.552  1036  1545 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-11 17:48:45.554  1036  1539 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-11 17:48:45.554  1036  1539 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-11 17:48:45.554   318  7937 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-11 17:48:45.554  1856  1856 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-11 17:48:45.554  1856  1856 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-11 17:48:45.555  1036  1545 E ConnectivityService: [lg_data] Adding agent Network,AgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-11 17:48:45.555  1036  1545 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-11 17:48:45.555  1036  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-11 17:48:45.555  1036  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-11 17:48:45.555  1036  1545 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-11 17:48:45.556  1036  1545 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-11 17:48:45.556  1036  1545 D ConnectivityService: validation of new default Network = false
08-11 17:48:45.557  1036  1545 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-11 17:48:45.557  1036  1545 D DSQN    : enableDataServiceNotify 
08-11 17:48:45.557  1036  1545 D DSQN    : start dsqn bin
08-11 17:48:45.557  1036  1036 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-11 17:48:45.558  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-11 17:48:45.558  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-11 17:48:45.558  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-11 17:48:45.566  1036  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-11 17:48:45.566  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-11 17:48:45.566  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-11 17:48:45.566  1036  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-11 17:48:45.567  1603  2081 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-11 17:48:45.554  7938  7938 W dsqn    : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-11 17:48:45.554  7938  7938 W dsqn    : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-11 17:48:45.569  1036  1537 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-11 17:48:45.571  6940  6940 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-11 17:48:45.581  7938  7938 E DSQN    : DSQN ssw
,08-11 17:48:45.587  6989  6989 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-11 17:48:45.587  6989  6989 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-11 17:48:45.590  6989  6989 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-11 17:48:45.590  1821  7940 I CheckinService: active receiver: enabled
,08-11 17:48:45.600  1821  7940 I CheckinService: Preparing to send checkin request
08-11 17:48:45.600   318  7937 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-11 17:48:45.600  1821  7940 I EventLogService: Accumulating logs since 1470930379520
08-11 17:48:45.601  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-11 17:48:45.601  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-11 17:48:45.602  6495  6495 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-11 17:48:45.602  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 17:48:45.607  6940  6940 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-11 17:48:45.611  6940  6940 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-11 17:48:45.616  6989  6989 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-11 17:48:45.616  6989  6989 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-11 17:48:45.617  6989  6989 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-11 17:48:45.619  6495  6495 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-11 17:48:45.624  6922  6922 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-11 17:48:45.627  6922  6922 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-11 17:48:45.629  6940  6940 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-11 17:48:45.633  1821  7940 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-11 17:48:45.634  6940  6940 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-11 17:48:45.636   318  7937 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-11 17:48:45.639  6989  6989 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-11 17:48:45.640  6989  6989 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-11 17:48:45.640  6989  6989 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-11 17:48:45.641  6989  6989 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-11 17:48:45.641  6989  6989 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-11 17:48:45.646  6495  6495 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-11 17:48:45.649  6922  6922 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-11 17:48:45.649  6922  6922 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,08-11 17:48:45.654  6940  6940 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-11 17:48:45.661  6940  6940 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-11 17:48:45.666   318   893 D LGDataListener: argv[0]=dsqncommand
08-11 17:48:45.666   318   893 D LGDataListener: argv[1]=wlan0
08-11 17:48:45.666   318   893 D LGDataListener: argv[2]=1
08-11 17:48:45.666   318   893 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
,08-11 17:48:45.667  6989  6989 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-11 17:48:45.667  1036  1117 D DSQN    : DSQM DsqnNotification wlan0  1
08-11 17:48:45.667  1036  1117 D DSQN    : start to monitor internet connection
08-11 17:48:45.667  6989  6989 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-11 17:48:45.669  6989  6989 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-11 17:48:45.670  6989  6989 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-11 17:48:45.670  6670  6809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:48:45.670  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:48:45.670  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 17:48:45.670  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:48:45.670  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 17:48:45.670  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 17:48:45.670  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 17:48:45.670  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 17:48:45.670  6989  6989 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-11 17:48:45.672  6670  6809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 17:48:45.673  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:48:45.673  6670  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@232c79b1 removed from the list
08-11 17:48:45.673  6670  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:48:45.673  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:48:45.673  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:48:45.686  1036  7932 D DhcpStateMachine: DHCPV4 request on wlan0
08-11 17:48:45.686  1036  7932 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-11 17:48:45.686  1036  7932 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-11 17:48:45.674  7946  7946 W dhcpcd  : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-11 17:48:45.674  7946  7946 W dhcpcd  : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-11 17:48:45.697  1036  7931 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 11 Aug 2016 15:48:46 GMT], X-Android-Received-Millis=[1470930525697], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470930525666]}
08-11 17:48:45.697  1036  7931 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-11 17:48:45.698  1036  7931 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-11 17:48:45.698  1036  1545 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-11 17:48:45.698  1036  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-11 17:48:45.698  1036  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-11 17:48:45.698  1036  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-11 17:48:45.698  1036  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-11 17:48:45.698  1036  1545 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-11 17:48:45.698  1036  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-11 17:48:45.699  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-11 17:48:45.699  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-11 17:48:45.699  1036  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-11 17:48:45.700  7946  7946 I dhcpcd  : version 5.5.6 starting
08-11 17:48:45.700  1036  1545 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-11 17:48:45.700  1603  2081 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-11 17:48:45.700  1036  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-11 17:48:45.702  1856  1856 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-11 17:48:45.702  1856  1856 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-11 17:48:45.702  7946  7946 E dhcpcd  : get_duid: m
08-11 17:48:45.702  7946  7946 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-11 17:48:45.702  7946  7946 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-11 17:48:45.703  1036  1539 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-11 17:48:45.703  1036  1539 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-11 17:48:45.760  1036  1940 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7951 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-11 17:48:45.774  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-11 17:48:45.775  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 17:48:45.775  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-11 17:48:45.778  7946  7946 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-11 17:48:45.778  7946  7946 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-11 17:48:45.778  7946  7946 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-11 17:48:45.778  7946  7946 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-11 17:48:45.779  7946  7946 D dhcpcd  : wlan0: sending REQUEST (xid 0xf4f0833a), next in 3.75 seconds
,08-11 17:48:45.812  7946  7946 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,08-11 17:48:45.818  7951  7951 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-11 17:48:45.818  7951  7951 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-11 17:48:45.824  7946  7946 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-11 17:48:45.824  7946  7946 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-11 17:48:45.824  7946  7946 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-11 17:48:45.825  7946  7946 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-11 17:48:45.825  7946  7946 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,08-11 17:48:45.826  7946  7946 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-11 17:48:45.826  7946  7946 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-11 17:48:45.826  7946  7946 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-11 17:48:45.845  7951  7951 I MultiDex: VM with version 2.1.0 has multidex support
08-11 17:48:45.845  7951  7951 I MultiDex: install
08-11 17:48:45.845  7951  7951 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-11 17:48:45.854  7951  7951 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-11 17:48:45.858  2184  2184 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-11 17:48:45.871  2184  2184 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-11 17:48:45.872  2184  2184 D c       : Getting all permits...
08-11 17:48:45.872  2184  2184 D a       : Opening database...
,08-11 17:48:45.876  2184  2184 D a       : Opening database auth.proximity.permit_store...
08-11 17:48:45.876  2184  2184 D a       : Closing database...
08-11 17:48:46.089  1036  7932 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-11 17:48:46.094  1036  7932 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
,08-11 17:48:46.095  1036  7932 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-11 17:48:46.095  1036  7932 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-11 17:48:46.095  1036  7932 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
,08-11 17:48:46.095  1036  7932 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-11 17:48:46.095  1036  7932 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-11 17:48:46.095  1036  7932 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-11 17:48:46.096  1036  7932 D DhcpStateMachine: RunningState
08-11 17:48:46.102  7951  7969 D LgDataFeature: LgDataFeature() Constructor: none
08-11 17:48:46.102  7951  7969 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-11 17:48:46.344  8000  8000 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-11 17:48:46.409  8000  8000 I dex2oat : dex2oat took 64.919ms (threads: 4)
,08-11 17:48:46.426  7951  7969 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-11 17:48:46.426  7951  7969 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-11 17:48:46.426  7951  7969 I Adreno-EGL: Build Date: 12/12/14 금
08-11 17:48:46.426  7951  7969 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-11 17:48:46.426  7951  7969 I Adreno-EGL: Remote Branch: 
08-11 17:48:46.426  7951  7969 I Adreno-EGL: Local Patches: 
08-11 17:48:46.426  7951  7969 I Adreno-EGL: Reconstruct Branch: 
,08-11 17:48:46.562  7951  7969 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-11 17:48:46.562  7951  7969 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-11 17:48:46.562  7951  7969 I Adreno-EGL: Build Date: 12/12/14 금
08-11 17:48:46.562  7951  7969 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-11 17:48:46.562  7951  7969 I Adreno-EGL: Remote Branch: 
08-11 17:48:46.562  7951  7969 I Adreno-EGL: Local Patches: 
08-11 17:48:46.562  7951  7969 I Adreno-EGL: Reconstruct Branch: 
,08-11 17:48:46.773  7951  7969 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-11 17:48:46.773  7951  7969 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-11 17:48:46.773  7951  7969 I Adreno-EGL: Build Date: 12/12/14 금
08-11 17:48:46.773  7951  7969 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-11 17:48:46.773  7951  7969 I Adreno-EGL: Remote Branch: 
08-11 17:48:46.773  7951  7969 I Adreno-EGL: Local Patches: 
08-11 17:48:46.773  7951  7969 I Adreno-EGL: Reconstruct Branch: 
,08-11 17:48:46.966   318  8007 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-11 17:48:46.966   318  8007 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,08-11 17:48:47.007   318  8007 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-11 17:48:47.186  1036  1539 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-11 17:48:47.187  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-11 17:48:47.187  1036  1539 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-11 17:48:47.188  1036  1539 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-11 17:48:47.188  1036  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-11 17:48:47.188  1036  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-11 17:48:47.189  1036  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
08-11 17:48:47.190  1036  1545 D ConnectivityService: identical MTU - not setting
08-11 17:48:47.190  1036  1545 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
,08-11 17:48:47.190  1036  1545 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-11 17:48:47.190  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-11 17:48:47.190  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-11 17:48:47.191  1036  1545 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-11 17:48:47.192  1603  2081 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-11 17:48:47.213  1821  7940 I CheckinTask: Sending checkin request (7890 bytes)
,08-11 17:48:47.419  1821  7940 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,08-11 17:48:47.430  1821  7940 I CheckinService: active receiver: disabled
,08-11 17:48:47.462  2184  2184 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-11 17:48:47.481  2184  2184 I GCM     : GCM config loaded
,08-11 17:48:47.498   318  8013 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-11 17:48:47.500   318  8013 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-11 17:48:47.506  7210  7210 V SetupWizard: Connected to Gservices successfully
08-11 17:48:47.533   318  8013 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,08-11 17:48:47.808  2184  8016 D GCM     : Connected
,08-11 17:48:47.844  2184  8016 D GCM     : Message class com.google.e.a.a.q
,08-11 17:48:48.485  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=66.0, 0.0, 0.0  rx=69.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:2051713252] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-11 17:48:48.488  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=66.0, 0.0, 0.0  rx=69.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:2051713255] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-11 17:48:48.488  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-11 17:48:48.508  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-11 17:48:48.528  1036  1540 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-11 17:48:48.557  1036  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-11 17:48:48.573  1036  1119 D Tethering: MasterInitialState.processMessage what=3
,08-11 17:48:48.597  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:48:48.597  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:48:48.597  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 17:48:48.597  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:48:48.597  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 17:48:48.597  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 17:48:48.597  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 17:48:48.597  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 17:48:48.602  6670  6670 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 17:48:48.607  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:48:48.607  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:48:48.607  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 17:48:48.607  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:48:48.607  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 17:48:48.607  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 17:48:48.607  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 17:48:48.607  6670  6670 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 17:48:48.609  6670  6670 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 17:48:48.611  1036  1099 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-11 17:48:48.619  6495  6495 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-11 17:48:48.621  6495  6521 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-11 17:48:48.632  5336  5336 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-11 17:48:48.655  2184  2184 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-11 17:48:48.700  1036  2035 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
,08-11 17:48:48.702  1036  7931 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
,08-11 17:48:48.702  1036  7931 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:48.702  1036  7931 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
,08-11 17:48:48.702  1036  7931 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-11 17:48:48.702  1036  7931 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
,08-11 17:48:48.735  1036  1099 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-11 17:48:48.746  1036  1051 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=8032 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-11 17:48:48.775  1036  7931 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 11 Aug 2016 15:48:49 GMT], X-Android-Received-Millis=[1470930528775], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470930528736]}
,08-11 17:48:48.776  1036  7931 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-11 17:48:48.776  1036  7931 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-11 17:48:48.776  1036  1545 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-11 17:48:48.776  1036  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-11 17:48:48.776  1036  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-11 17:48:48.776  1036  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-11 17:48:48.776  1036  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-11 17:48:48.776  1036  1545 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-11 17:48:48.776  1036  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-11 17:48:48.776  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-11 17:48:48.776  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-11 17:48:48.776  1036  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-11 17:48:48.777  1603  2081 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-11 17:48:48.802  8032  8032 I AppUp4:AppBoxCP: onCreate
08-11 17:48:48.803  8032  8032 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-11 17:48:48.812  8032  8032 I AppUp4:DB:  setFingerPrint start
08-11 17:48:48.812  8032  8032 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-11 17:48:48.822  8032  8032 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-11 17:48:48.822  8032  8032 I AppUp4:DB:  SDK version = 21
08-11 17:48:48.822  8032  8032 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-11 17:48:48.824  8032  8032 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-11 17:48:48.825  8032  8032 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-11 17:48:48.825  8032  8032 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-11 17:48:48.827  8032  8032 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-11 17:48:48.828  8032  8032 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-11 17:48:48.835  8032  8032 I AppUp4:CustModeStarterReceiver: onReceive
,08-11 17:48:48.875  8032  8032 D LgDataFeature: LgDataFeature() Constructor: none
,08-11 17:48:48.875  8032  8032 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-11 17:48:48.883  8032  8032 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@8700525
,08-11 17:48:48.883  8032  8032 D AppUp4:CustFacade: isCustomizationCompleted : false
08-11 17:48:48.883  8032  8032 D AppUp4:CustFacade: isPhone : true
,08-11 17:48:48.883  8032  8032 D AppUp4:CustModeStarterReceiver: begin check event
08-11 17:48:48.884  8032  8032 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-11 17:48:48.884  8032  8032 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-11 17:48:48.885  8032  8052 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
,08-11 17:48:48.885  8032  8052 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-11 17:48:48.885  8032  8052 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-11 17:48:48.887  1036  2053 I ActivityManager: Killing 7184:com.lge.email/u0a23 (adj 15): empty #17
,08-11 17:48:48.981  4365  4365 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-11 17:48:48.982  4365  4365 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-11 17:48:48.982  1036  1975 W libprocessgroup: failed to open /acct/uid_10023/pid_7184/cgroup.procs: No such file or directory
08-11 17:48:48.988  4365  4365 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-11 17:48:48.997  4365  4365 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-11 17:48:49.006  3566  3566 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
08-11 17:48:49.007  4365  8055 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-11 17:48:49.014  3566  3566 V DownloadManager: DownloadService onCreate
,08-11 17:48:49.014  4365  8056 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-11 17:48:49.015  4365  8056 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-11 17:48:49.017  3566  8057 I DownloadManager: in removeSpuriousFiles
08-11 17:48:49.017  3566  8057 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
08-11 17:48:49.019  3566  8057 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@38468fb9 on behalf of 3566
08-11 17:48:49.019  4365  8055 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
08-11 17:48:49.020  3566  8057 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
08-11 17:48:49.020  3566  8057 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
08-11 17:48:49.020  3566  8057 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
08-11 17:48:49.020  3566  8057 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
08-11 17:48:49.020  3566  8057 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
08-11 17:48:49.020  3566  8057 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
08-11 17:48:49.020  3566  8057 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
08-11 17:48:49.020  3566  8057 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
08-11 17:48:49.020  3566  8057 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
08-11 17:48:49.020  3566  8057 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
08-11 17:48:49.020  3566  8057 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
,08-11 17:48:49.027  3566  8057 I DownloadManager: in trimDatabase
08-11 17:48:49.028  3566  8057 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
08-11 17:48:49.030  3566  8057 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@54535f on behalf of 3566
08-11 17:48:49.074  1036  1981 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=8060 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-11 17:48:49.077  3566  3566 V DownloadManager: DownloadService onStartCommand
08-11 17:48:49.078  4365  8055 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
08-11 17:48:49.080  3566  8058 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
08-11 17:48:49.082  4365  4365 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
08-11 17:48:49.082  4365  4365 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
08-11 17:48:49.082  3566  8058 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@30b76e75 on behalf of 3566
08-11 17:48:49.083  4365  4365 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
08-11 17:48:49.085  3566  8058 V DownloadManager: processing inserted download 1
08-11 17:48:49.085  4365  4365 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
08-11 17:48:49.086  3566  8058 V DownloadManager: processing inserted download 4
08-11 17:48:49.087  3566  8058 V DownloadManager: processing inserted download 7
,08-11 17:48:49.090  3566  8058 V DownloadManager: processing inserted download 8
08-11 17:48:49.090  4365  4365 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
08-11 17:48:49.096  3566  8058 V DownloadManager: processing inserted download 9
08-11 17:48:49.097  3566  8058 V DownloadManager: processing inserted download 10
08-11 17:48:49.098  3566  8058 V DownloadManager: processing inserted download 11
08-11 17:48:49.099  3566  8058 V DownloadManager: processing inserted download 12
08-11 17:48:49.100  3566  8058 V DownloadManager: processing inserted download 13
08-11 17:48:49.101  3566  8058 V DownloadManager: processing inserted download 14
,08-11 17:48:49.103  3566  8058 V DownloadManager: processing inserted download 16
08-11 17:48:49.114  3566  3566 V DownloadManager: DownloadService onDestroy
,08-11 17:48:49.155  8060  8060 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-11 17:48:49.155  8060  8060 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-11 17:48:49.157  8060  8060 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-11 17:48:49.157  8060  8060 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-11 17:48:49.237  8060  8060 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-11 17:48:49.249  8060  8060 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-11 17:48:49.303  8060  8060 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-11 17:48:49.340  8060  8060 D LgDataFeature: LgDataFeature() Constructor: none
,08-11 17:48:49.340  8060  8060 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-11 17:48:49.497  8060  8060 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-11 17:48:49.543  3521  3521 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-11 17:48:49.543  3521  3521 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-11 17:48:49.543  3521  3521 I LgeMiscReceiver: networkInfo.isConnected() = true
08-11 17:48:49.543  3521  3521 D PhoneState: setPdpRejectCasuse : false
,08-11 17:48:49.552  7210  7210 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-11 17:48:49.552  7210  7210 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-11 17:48:49.557  8060  8060 I HubEmail: JNI_OnLoad()
08-11 17:48:49.557  8060  8060 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-11 17:48:49.557  8060  8060 I HubEmail: registerNatives()
08-11 17:48:49.557  8060  8060 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-11 17:48:49.557  8060  8060 I HubEmail: registerNativeMethods()
08-11 17:48:49.557  8060  8060 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-11 17:48:49.558  8060  8060 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,08-11 17:48:49.579  7279  7279 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:48:49
,08-11 17:48:49.582  7279  7279 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-11 17:48:49.582  7279  7279 D Weather.Utils: 2 : All the weather widget is gone.
,08-11 17:48:49.583  7279  7279 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-11 17:48:49.583  7279  7279 D WeatherAncestor: connectivity changed - connection : true
08-11 17:48:49.583  7279  7279 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@385074ab
08-11 17:48:49.584  7279  7279 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-11 17:48:49.584  7279  7279 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-11 17:48:49.584  7279  7279 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-11 17:48:49.584  7279  7279 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-11 17:48:49.584  7279  7279 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:48:49
08-11 17:48:49.590  8060  8091 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 17:48:49.622   318  8094 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-11 17:48:49.622   318  8094 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
,08-11 17:48:49.662   318  8094 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
,08-11 17:48:49.712  7030  8090 V FormManager: There are no updated forms. The schedule will be deleted.
,08-11 17:48:49.728  7030  8090 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
,08-11 17:48:49.739   318  8100 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-11 17:48:49.740   318  8100 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
08-11 17:48:49.757  1036  1788 I ActivityManager: Killing 7523:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-11 17:48:49.772   318  8100 D libc-netbsd: res_queryN name = www.google.com succeed
,08-11 17:48:49.778   318  8103 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-11 17:48:49.778   318  8103 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-11 17:48:49.779   318  8103 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-11 17:48:49.816  1036  1051 W libprocessgroup: failed to open /acct/uid_10037/pid_7523/cgroup.procs: No such file or directory
,08-11 17:48:49.841  1036  1541 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,08-11 17:48:50.686  6670  8110 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,08-11 17:48:50.686  6670  8110 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-11 17:48:51.518  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=50.5, 0.0, 0.0  rx=49.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:2051716286] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-11 17:48:51.521  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=50.5, 0.0, 0.0  rx=49.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:2051716289] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-11 17:48:51.521  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-11 17:48:51.966  1036  1789 I ActivityManager: Killing 7567:com.lge.settings.easy/1000 (adj 15): empty #17
,08-11 17:48:51.998  1036  1940 W libprocessgroup: failed to open /acct/uid_1000/pid_7567/cgroup.procs: No such file or directory
,08-11 17:48:53.696  6670  8110 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,08-11 17:48:53.696  6670  8110 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,08-11 17:48:53.700  6670  8110 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-11 17:48:53.701  6670  8110 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-11 17:48:53.701  6670  8110 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-11 17:48:53.703  6670  8111 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
08-11 17:48:53.703  6670  8111 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-11 17:48:53.703  6670  8111 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-11 17:48:53.703  6670  8111 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-11 17:48:53.703  6670  8111 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-11 17:48:53.705  6670  8114 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 855, name: OutgoingSocketThread/Receiver)
08-11 17:48:53.706  6670  8114 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 855, thread name: OutgoingSocketThread/Receiver)
08-11 17:48:53.706  6670  8114 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-11 17:48:53.706  6670  8114 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 855, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-11 17:48:53.708  6670  8113 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 854, name: OutgoingSocketThread/Sender)
08-11 17:48:53.710  6670  8115 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 856, name: IncomingSocketThread/Sender)
,08-11 17:48:53.715  6670  8116 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 857, name: IncomingSocketThread/Receiver)
,08-11 17:48:53.715  6670  8116 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 857, thread name: IncomingSocketThread/Receiver)
,08-11 17:48:53.715  6670  8116 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,08-11 17:48:53.715  6670  8116 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 857, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-11 17:48:54.543  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=33.8, 0.0, 0.0  rx=30.0 bcn=0 [on:0 tx:0 rx:0 period:3007] from screen [on:0 period:2051719311] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-11 17:48:54.546  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=33.8, 0.0, 0.0  rx=30.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:2051719314] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-11 17:48:54.546  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-11 17:48:55.682  1603  1603 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-11 17:48:55.707  1036  1465 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-11 17:48:55.782  1036  1036 D administrator: Handling package changes for user 0
,08-11 17:48:55.800  1036  1100 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=8117 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-11 17:48:55.821  2036  2036 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-11 17:48:55.821  1603  1603 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,08-11 17:48:55.824  1603  1603 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-11 17:48:55.854  2036  2036 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-11 17:48:55.877  8117  8117 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-11 17:48:55.920  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-11 17:48:55.920  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-11 17:48:55.939  8117  8117 D LgDataFeature: LgDataFeature() Constructor: none
08-11 17:48:55.939  8117  8117 D LgDataFeature: LgDataFeature() Constructor Done, null
08-11 17:48:55.969  1036  1099 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-11 17:48:55.978  1036  1099 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-11 17:48:55.987  2036  2036 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-11 17:48:55.988  2477  2477 V GmsNetworkLocationProvi: DISABLE
,08-11 17:48:56.029  2477  2477 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-11 17:48:56.033  1036  1099 D LocationProviderProxy: applying state to connected service
08-11 17:48:56.041  8117  8161 I Babel   : MmsConfig: mnc/mcc: 0/0
,08-11 17:48:56.041  8117  8161 I Babel   : MmsConfig.loadMmsSettings
08-11 17:48:56.045  8117  8161 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-11 17:48:56.045  8117  8161 I Babel   : MmsConfig.loadFromDatabase
,08-11 17:48:56.067  8117  8161 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-11 17:48:56.068  8117  8161 I Babel   : MmsConfig.loadFromResources
08-11 17:48:56.071  8117  8117 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 17:48:56.074  8117  8161 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-11 17:48:56.075  8117  8161 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-11 17:48:56.091  8117  8159 W AudioCapabilities: Unsupported mime audio/evrc
08-11 17:48:56.093  8117  8159 W AudioCapabilities: Unsupported mime audio/qcelp
08-11 17:48:56.096  8117  8159 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-11 17:48:56.108  8117  8159 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,08-11 17:48:56.116  8117  8159 W AudioCapabilities: Unsupported mime audio/qcelp
08-11 17:48:56.117  8117  8159 W AudioCapabilities: Unsupported mime audio/evrc
08-11 17:48:56.131  8117  8159 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-11 17:48:56.133  8117  8159 W VideoCapabilities: Unsupported mime video/divx
08-11 17:48:56.135  8117  8159 W VideoCapabilities: Unsupported mime video/divx311
08-11 17:48:56.137  8117  8159 W VideoCapabilities: Unsupported mime video/divx4
08-11 17:48:56.142  8117  8159 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-11 17:48:56.158  8117  8159 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-11 17:48:56.162  8117  8159 W AudioCapabilities: Unsupported mime audio/eac3
08-11 17:48:56.163  8117  8159 W AudioCapabilities: Unsupported mime audio/ac3
08-11 17:48:56.163  8117  8159 W AudioCapabilities: Unsupported mime audio/g726
08-11 17:48:56.165  8117  8159 W AudioCapabilities: Unsupported mime audio/wma-voice
08-11 17:48:56.166  8117  8159 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-11 17:48:56.166  8117  8159 W AudioCapabilities: Unsupported mime audio/adpcm
08-11 17:48:56.168  8117  8159 W VideoCapabilities: Unsupported mime video/theora
08-11 17:48:56.170  8117  8159 W VideoCapabilities: Unsupported mime video/mjpg
,08-11 17:48:56.182  1036  1975 I art     : Explicit concurrent mark sweep GC freed 86424(4MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 1.745ms total 86.992ms
08-11 17:48:56.185  1821  8165 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-11 17:48:56.185  1821  8165 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,08-11 17:48:56.196  8032  8032 I AppUp4:CustModeStarterReceiver: onReceive
,08-11 17:48:56.199  8032  8032 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@8700525
08-11 17:48:56.199  8032  8032 D AppUp4:CustFacade: isCustomizationCompleted : false
08-11 17:48:56.199  8032  8032 D AppUp4:CustFacade: isPhone : true
08-11 17:48:56.199  8032  8032 D AppUp4:CustModeStarterReceiver: begin check event
08-11 17:48:56.199  8032  8032 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-11 17:48:56.208  1821  4803 I Icing   : updateResources: need to parse e{com.google.android.gms}
,08-11 17:48:56.223  1036  1051 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8167 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-11 17:48:56.247  1036  2008 I ActivityManager: Killing 7433:com.lge.bnr/1000 (adj 15): empty #17
,08-11 17:48:56.320  1036  1788 W libprocessgroup: failed to open /acct/uid_1000/pid_7433/cgroup.procs: No such file or directory
08-11 17:48:56.357  8167  8167 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-11 17:48:56.358  8167  8167 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-11 17:48:56.359  8167  8167 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-11 17:48:56.362  8167  8167 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-11 17:48:56.362  8167  8167 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-11 17:48:56.447  8167  8167 I SystemConfig: BUILD Country: EU
08-11 17:48:56.448  8167  8167 I SystemConfig: BUILD Operator: OPEN
,08-11 17:48:56.496  1036  1577 I ActivityManager: Killing 6922:com.lge.sync/1000 (adj 15): empty #17
,08-11 17:48:56.602  1036  1052 W libprocessgroup: failed to open /acct/uid_1000/pid_6922/cgroup.procs: No such file or directory
,08-11 17:48:56.684  1036  1577 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8188 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-11 17:48:56.693  8167  8186 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
,08-11 17:48:56.693  8167  8186 I SystemConfig: existFile = false
08-11 17:48:56.693  8167  8186 I SystemConfig: canReadFile = false
08-11 17:48:56.694  8167  8186 I SystemConfig: systemFeature RCS result false
08-11 17:48:56.694  8167  8186 D SystemConfig: refreshRcsSupport() :false
,08-11 17:48:56.704   346   346 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 391us total 20.010ms
,08-11 17:48:56.720   346   346 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 297us total 15.827ms
,08-11 17:48:56.735   346   346 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 288us total 13.490ms
08-11 17:48:56.757  8188  8188 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-11 17:48:56.760  8188  8188 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-11 17:48:56.760  8188  8188 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-11 17:48:56.760  8188  8188 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-11 17:48:56.872  8188  8188 I AppConfig: Total System Memory = 2995761152
,08-11 17:48:56.883  8188  8188 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator [],
08-11 17:48:56.980  1036  1940 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8210 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-11 17:48:56.982  1036  1940 I ActivityManager: Killing 6774:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-11 17:48:57.007  6989  6989 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-11 17:48:57.007  6989  6989 W System.err: android.os.DeadObjectException
08-11 17:48:57.008  6989  6989 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-11 17:48:57.008  6989  6989 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-11 17:48:57.008  6989  6989 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-11 17:48:57.008  6989  6989 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-11 17:48:57.008  6989  6989 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-11 17:48:57.008  6989  6989 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-11 17:48:57.008  6989  6989 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-11 17:48:57.008  6989  6989 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-11 17:48:57.008  6989  6989 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-11 17:48:57.008  6989  6989 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-11 17:48:57.008  6989  6989 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 17:48:57.008  6989  6989 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-11 17:48:57.008  6989  6989 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-11 17:48:57.008  6989  6989 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-11 17:48:57.008  6989  6989 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-11 17:48:57.009  6989  6989 W System.err: android.os.DeadObjectException
08-11 17:48:57.009  6989  6989 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-11 17:48:57.009  6989  6989 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-11 17:48:57.009  6989  6989 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-11 17:48:57.009  6989  6989 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-11 17:48:57.009  6989  6989 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-11 17:48:57.009  6989  6989 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-11 17:48:57.009  6989  6989 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-11 17:48:57.009  6989  6989 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-11 17:48:57.009  6989  6989 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-11 17:48:57.009  6989  6989 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-11 17:48:57.009  6989  6989 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 17:48:57.009  6989  6989 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-11 17:48:57.009  6989  6989 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-11 17:48:57.010  6989  6989 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-11 17:48:57.010  6989  6989 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-11 17:48:57.010  6989  6989 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-11 17:48:57.105  1036  1789 W libprocessgroup: failed to open /acct/uid_1000/pid_6774/cgroup.procs: No such file or directory
08-11 17:48:57.106  1036  1789 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-11 17:48:57.113  6989  6989 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-11 17:48:57.114  6989  6989 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-11 17:48:57.171  1036  1577 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=8229 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-11 17:48:57.176  6989  6989 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-11 17:48:57.236  8229  8229 D UEI.SmartControl: Quickset Services start...
,08-11 17:48:57.238  8229  8229 I UEI.SmartControl: Manufacture = LGE
08-11 17:48:57.238  8229  8229 D UEI.SmartControl: Id = LGNevo
08-11 17:48:57.239  8229  8229 D UEI.SmartControl: File observer start...
08-11 17:48:57.240  8229  8229 E UEI.SmartControl: IR Port is disabled: false
08-11 17:48:57.240  8229  8229 D UEI.SmartControl: Starting file observer...
08-11 17:48:57.240  8229  8229 D UEI.SmartControl: Extracting JNI libs...
08-11 17:48:57.241  8229  8229 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-11 17:48:57.289  8210  8210 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-11 17:48:57.336  8229  8229 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,08-11 17:48:57.336  8229  8229 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-11 17:48:57.336  8229  8229 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
08-11 17:48:57.374  8229  8229 I UEI.SmartControl: --- Selecting new region: 6
,08-11 17:48:57.376  8229  8229 I UEI.SmartControl: Model = LG-D855
08-11 17:48:57.377  8229  8229 D UEI.SmartControl: QS Service created
08-11 17:48:57.389  8210  8210 D LgDataFeature: LgDataFeature() Constructor: none
08-11 17:48:57.389  8210  8210 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-11 17:48:57.393  8229  8229 I UEI.SmartControl: Service initServices...
,08-11 17:48:57.399  8229  8229 D UEI.SmartControl: QS start get config
,08-11 17:48:57.440  8229  8229 D UEI.SmartControl: Loading JNI Libs...
,08-11 17:48:57.454  8210  8210 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-11 17:48:57.471  8210  8210 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-11 17:48:57.472  8210  8210 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-11 17:48:57.487  8210  8210 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-11 17:48:57.487  8210  8210 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
08-11 17:48:57.510  1036  1981 I ActivityManager: Killing 6940:com.android.settings/1000 (adj 15): empty #17
,08-11 17:48:57.569  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=17.4, 0.0, 0.0  rx=15.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:2051722337] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-11 17:48:57.570  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=17.4, 0.0, 0.0  rx=15.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:2051722338] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-11 17:48:57.570  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-11 17:48:57.620  1036  1577 W libprocessgroup: failed to open /acct/uid_1000/pid_6940/cgroup.procs: No such file or directory
,08-11 17:48:57.634  3566  3582 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-11 17:48:57.637  4634  8266 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
08-11 17:48:57.642  3566  3582 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3794c67b on behalf of 8210
,08-11 17:48:57.676  1036  1789 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=8267 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-11 17:48:57.693  8210  8210 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-11 17:48:57.710  8210  8210 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-11 17:48:57.740  8229  8229 I UEI.SmartControl: Supports setup maps: true
08-11 17:48:57.743  8229  8229 D UEI.SmartControl: QS start statue = true Error code = 0
,08-11 17:48:57.743  8229  8229 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-11 17:48:57.743  8229  8229 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-11 17:48:57.743  8229  8229 I UEI.SmartControl: ### init IR Blaster...
08-11 17:48:57.748  8229  8229 D serial_port: Configuring serial port
08-11 17:48:57.751  8229  8229 E UEI.SmartControl: UEIBLaster setting for 616
08-11 17:48:57.751  8229  8229 I UEI.SmartControl: Setting serial record hearder size = 2
08-11 17:48:57.751  8229  8229 I UEI.SmartControl: configuring settings for MAXQ616
08-11 17:48:57.751  8229  8229 I UEI.SmartControl: Get version...
08-11 17:48:57.763  8267  8267 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-11 17:48:57.767  8229  8292 D UEI.SmartControl: serial port data available: 21
08-11 17:48:57.782  8267  8267 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-11 17:48:57.782  8267  8267 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-11 17:48:57.782  8267  8267 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
,08-11 17:48:57.782  8267  8267 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-11 17:48:57.782  8267  8267 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-11 17:48:57.782  8267  8267 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
08-11 17:48:57.794  8229  8229 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-11 17:48:57.794  8229  8229 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-11 17:48:57.794  8229  8229 I UEI.SmartControl: QS saving settings...
08-11 17:48:57.795  8229  8229 D UEI.SmartControl: IR Blaster version: 25672567
08-11 17:48:57.799  1036  1940 I ActivityManager: Killing 6989:com.lge.qremote/u0a112 (adj 15): empty #17
08-11 17:48:57.813  8229  8292 D UEI.SmartControl: serial port data available: 4
,08-11 17:48:57.827  1036  2053 W libprocessgroup: failed to open /acct/uid_10112/pid_6989/cgroup.procs: No such file or directory
,08-11 17:48:57.843  8229  8297 I UEI.SmartControl: Device manager: loading config....
,08-11 17:48:57.844  8229  8229 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-11 17:48:57.844  8229  8297 D UEI.SmartControl: ----------- loading internal config...
08-11 17:48:57.846  8229  8229 E UEI.SmartControl: Services init done
08-11 17:48:57.847  8229  8229 D UEI.SmartControl: QS Service init finished
,08-11 17:48:57.847  8229  8229 D UEI.SmartControl: QS Service version name: 2.1.91
08-11 17:48:57.848  8229  8229 D UEI.SmartControl: QS Service version code: 201091
08-11 17:48:57.848  8229  8229 D UEI.SmartControl: Service requested: Control
08-11 17:48:57.851  8229  8297 E UEI.SmartControl: Loading SETTINGS...
08-11 17:48:57.853  8229  8229 D UEI.SmartControl: Request IControl service: devices are loaded...
08-11 17:48:57.854  8229  8229 D UEI.SmartControl: Service.onUnbind: IControl
08-11 17:48:57.855  8229  8229 D UEI.SmartControl: Service.onDestroy
08-11 17:48:57.855  8229  8229 D UEI.SmartControl: Lock is in USE false
08-11 17:48:57.855  8229  8229 D UEI.SmartControl: unbind internal service
,08-11 17:48:57.856  8229  8297 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-11 17:48:57.860  8229  8229 D serial_port: close(fd = 25)
08-11 17:48:57.861  8229  8296 I UEI.SmartControl: Notify AllClients services are ready: 0
08-11 17:48:57.861  8229  8296 D UEI.SmartControl: -----service ready thread exits
08-11 17:48:57.869  8229  8229 I UEI.SmartControl: Serial port is closed.
08-11 17:48:57.869  8229  8229 I UEI.SmartControl: Serial port is closed.
,08-11 17:48:57.870  8229  8229 D UEI.SmartControl: Blaster closed
08-11 17:48:57.870  8229  8229 D UEI.SmartControl: Shut down QS...
08-11 17:48:57.871  8229  8229 D UEI.SmartControl: Stopping QS lib
08-11 17:48:57.871  8229  8229 D UEI.SmartControl: QS lib stop result = true
08-11 17:48:57.871  8229  8229 D UEI.SmartControl: Stopped QS lib
08-11 17:48:57.871  8229  8229 D UEI.SmartControl: Stopped file observer...
,08-11 17:48:57.871  8229  8229 D UEI.SmartControl: QS shutdown complete
08-11 17:48:57.874  8229  8229 D UEI.SmartControl: QS Service created
08-11 17:48:57.885  8229  8229 I UEI.SmartControl: Service initServices...
08-11 17:48:57.885  8229  8229 D UEI.SmartControl: QS start get config
,08-11 17:48:58.004  1036  1905 V SIM_STK : Menu title from STK is T-Mobile
,08-11 17:48:58.019  4634  8266 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 383 ms] updated apps [took 383 ms] 
,08-11 17:48:58.185  8229  8229 I UEI.SmartControl: Supports setup maps: true
,08-11 17:48:58.188  8229  8229 D UEI.SmartControl: QS start statue = true Error code = 0
,08-11 17:48:58.188  8229  8229 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,08-11 17:48:58.189  8229  8229 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-11 17:48:58.189  8229  8229 I UEI.SmartControl: ### init IR Blaster...
,08-11 17:48:58.192  8229  8229 D serial_port: Configuring serial port
08-11 17:48:58.193  8229  8229 E UEI.SmartControl: UEIBLaster setting for 616
08-11 17:48:58.193  8229  8229 I UEI.SmartControl: Setting serial record hearder size = 2
08-11 17:48:58.193  8229  8229 I UEI.SmartControl: configuring settings for MAXQ616
08-11 17:48:58.193  8229  8229 I UEI.SmartControl: Get version...
08-11 17:48:58.198  1036  1413 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1125a0e8 type 2 when 217109 com.google.android.gms} when 217109
08-11 17:48:58.207   318  8302 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-11 17:48:58.207   318  8302 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-11 17:48:58.207   318  8302 D libc-netbsd: res_queryN name = mtalk.google.com succeed
08-11 17:48:58.213  8229  8300 D UEI.SmartControl: serial port data available: 21
,08-11 17:48:58.239  8229  8229 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-11 17:48:58.239  8229  8229 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-11 17:48:58.240  8229  8229 I UEI.SmartControl: QS saving settings...
,08-11 17:48:58.242  8229  8229 D UEI.SmartControl: IR Blaster version: 25672567
08-11 17:48:58.259  8229  8300 D UEI.SmartControl: serial port data available: 4
,08-11 17:48:58.292  8229  8229 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-11 17:48:58.300  8229  8311 I UEI.SmartControl: Device manager: loading config....
,08-11 17:48:58.300  8229  8311 D UEI.SmartControl: ----------- loading internal config...
08-11 17:48:58.311  8229  8229 E UEI.SmartControl: Services init done
08-11 17:48:58.311  8229  8229 D UEI.SmartControl: QS Service init finished
,08-11 17:48:58.316  8229  8311 E UEI.SmartControl: Loading SETTINGS...
08-11 17:48:58.320  8229  8311 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-11 17:48:58.320  8229  8229 D UEI.SmartControl: QS Service version name: 2.1.91
08-11 17:48:58.321  8229  8229 D UEI.SmartControl: QS Service version code: 201091
08-11 17:48:58.321  8229  8229 D UEI.SmartControl: Service requested: Control
08-11 17:48:58.324  1036  1914 I ActivityManager: Killing 8060:com.lge.email/u0a23 (adj 15): empty #17
,08-11 17:48:58.347  8229  8310 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-11 17:48:58.347  8229  8310 D UEI.SmartControl: -----service ready thread exits
,08-11 17:48:58.365  1036  1051 W libprocessgroup: failed to open /acct/uid_10023/pid_8060/cgroup.procs: No such file or directory
,08-11 17:48:58.371  8229  8229 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@3d40cea1 that was originally bound here
08-11 17:48:58.371  8229  8229 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@3d40cea1 that was originally bound here
08-11 17:48:58.371  8229  8229 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
08-11 17:48:58.371  8229  8229 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
08-11 17:48:58.371  8229  8229 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
08-11 17:48:58.371  8229  8229 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
08-11 17:48:58.371  8229  8229 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
08-11 17:48:58.371  8229  8229 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
08-11 17:48:58.371  8229  8229 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
08-11 17:48:58.371  8229  8229 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
08-11 17:48:58.371  8229  8229 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
08-11 17:48:58.371  8229  8229 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
08-11 17:48:58.371  8229  8229 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
08-11 17:48:58.371  8229  8229 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 17:48:58.371  8229  8229 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
08-11 17:48:58.371  8229  8229 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-11 17:48:58.371  8229  8229 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 17:48:58.371  8229  8229 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-11 17:48:58.371  8229  8229 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-11 17:48:58.371  8229  8229 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-11 17:48:58.371  8229  8229 D UEI.SmartControl: Internal service binding...
,08-11 17:48:58.525  2184  8313 D GCM     : Connected
,08-11 17:48:58.575  2184  8313 D GCM     : Message class com.google.e.a.a.q
,08-11 17:48:58.856  8229  8299 D UEI.SmartControl: Internal timer expired: 2
,08-11 17:49:00.056  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-11 17:49:00.056  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
08-11 17:49:00.056  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,08-11 17:49:00.057  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,08-11 17:49:00.071  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
,08-11 17:49:00.072  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
,08-11 17:49:00.074  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-11 17:49:00.076  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,08-11 17:49:00.589  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=9.2, 0.0, 0.0  rx=7.5 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:2051725357] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-11 17:49:00.592  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=9.2, 0.0, 0.0  rx=7.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:2051725360] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0,
08-11 17:49:00.592  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-11 17:49:01.690  6670  6809 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-11 17:49:01.692  6670  6809 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-11 17:49:01.707  6670  6809 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1d04297f Bundle[{}]
,08-11 17:49:01.708  6670  6809 I io.jxcore.node.LifeCycleMonitor: start: OK
08-11 17:49:01.708  6670  6809 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-11 17:49:01.709  6670  6809 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-11 17:49:01.710  6670  6809 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-11 17:49:01.710  6670  6809 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-11 17:49:01.711  6670  6809 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-11 17:49:02.231  8229  8240 E UEI.SmartControl: file observer is disposed!
,08-11 17:49:03.290  8229  8306 D serial_port: close(fd = 24)
,08-11 17:49:03.296  8229  8312 D UEI.SmartControl: Internal timer expired: 3
08-11 17:49:03.297  8229  8312 D UEI.SmartControl: unbind internal service
08-11 17:49:03.310  8229  8229 D UEI.SmartControl: Service.onUnbind: IControl
,08-11 17:49:03.314  8229  8229 D UEI.SmartControl: Service.onDestroy
,08-11 17:49:03.315  8229  8229 D UEI.SmartControl: Lock is in USE false
,08-11 17:49:03.315  8229  8229 D UEI.SmartControl: unbind internal service
08-11 17:49:03.315  8229  8229 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@36449f20
08-11 17:49:03.316  8229  8229 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-11 17:49:03.316  8229  8229 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
,08-11 17:49:03.316  8229  8229 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-11 17:49:03.316  8229  8229 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-11 17:49:03.316  8229  8229 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-11 17:49:03.316  8229  8229 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-11 17:49:03.316  8229  8229 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-11 17:49:03.316  8229  8229 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-11 17:49:03.316  8229  8229 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,08-11 17:49:03.316  8229  8229 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-11 17:49:03.316  8229  8229 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-11 17:49:03.316  8229  8229 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 17:49:03.316  8229  8229 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
,08-11 17:49:03.316  8229  8229 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-11 17:49:03.316  8229  8229 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-11 17:49:03.316  8229  8229 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@36449f20
08-11 17:49:03.321  8229  8306 I UEI.SmartControl: Serial port is closed.
08-11 17:49:03.321  8229  8229 I UEI.SmartControl: Serial port is closed.
08-11 17:49:03.321  8229  8229 I UEI.SmartControl: Serial port is closed.
08-11 17:49:03.321  8229  8229 D UEI.SmartControl: Blaster closed
08-11 17:49:03.321  8229  8229 D UEI.SmartControl: Shut down QS...
,08-11 17:49:03.321  8229  8229 D UEI.SmartControl: Stopping QS lib
08-11 17:49:03.321  8229  8229 D UEI.SmartControl: QS lib stop result = true
08-11 17:49:03.321  8229  8229 D UEI.SmartControl: Stopped QS lib
08-11 17:49:03.321  8229  8229 D UEI.SmartControl: QS shutdown complete
08-11 17:49:03.615  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=8.6, 0.0, 0.0  rx=7.8 bcn=0 [on:0 tx:0 rx:0 period:3007] from screen [on:0 period:2051728383] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-11 17:49:03.618  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=8.6, 0.0, 0.0  rx=7.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:2051728386] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-11 17:49:03.618  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-11 17:49:06.643  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=4.3, 0.0, 0.0  rx=3.9 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:2051731410] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-11 17:49:06.653  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=4.3, 0.0, 0.0  rx=3.9 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:2051731421] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-11 17:49:06.653  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-11 17:49:07.774  1036  1413 D PowerManagerServiceEx: acquireWakeLockInternal: lock=965614699, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,08-11 17:49:07.820  2598  2598 D [Concierge]Service: onStartCommand(). Type : 9
,08-11 17:49:07.849  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=965614699 [*alarm*], flags=0x0
,08-11 17:49:09.675  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=2.1, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:2051734442] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-11 17:49:09.678  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=2.1, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:2051734445] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-11 17:49:09.678  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-11 17:49:11.731  6670  6809 I System.out: Running OutgoingSocketThread
,08-11 17:49:11.743  6670  8317 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,08-11 17:49:11.743  6670  8317 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-11 17:49:12.703  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:2051737471] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-11 17:49:12.707  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:2051737475] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-11 17:49:12.707  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-11 17:49:13.520  1036  1413 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3a114be7 type 2 when 227630 android} when 227630
,08-11 17:49:14.747  6670  8317 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
08-11 17:49:14.747  6670  8317 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-11 17:49:14.747  6670  8317 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-11 17:49:14.747  6670  8317 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-11 17:49:14.747  6670  8317 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-11 17:49:14.752  6670  8318 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
08-11 17:49:14.752  6670  8318 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-11 17:49:14.752  6670  8318 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-11 17:49:14.752  6670  8318 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-11 17:49:14.753  6670  8318 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-11 17:49:14.755  6670  8321 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 867, name: OutgoingSocketThread/Receiver)
08-11 17:49:14.755  6670  8321 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 867, thread name: OutgoingSocketThread/Receiver)
08-11 17:49:14.755  6670  8321 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-11 17:49:14.755  6670  8321 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 867, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-11 17:49:14.757  6670  8320 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 866, name: OutgoingSocketThread/Sender)
08-11 17:49:14.759  6670  8322 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 868, name: IncomingSocketThread/Sender)
08-11 17:49:14.760  6670  8323 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 869, name: IncomingSocketThread/Receiver)
08-11 17:49:14.761  6670  8323 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 869, thread name: IncomingSocketThread/Receiver)
08-11 17:49:14.761  6670  8323 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-11 17:49:14.761  6670  8323 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 869, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-11 17:49:15.733  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:2051740501] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-11 17:49:15.737  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:2051740505] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-11 17:49:15.737  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-11 17:49:18.764  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3007] from screen [on:0 period:2051743532] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-11 17:49:18.768  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:2051743535] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-11 17:49:18.768  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-11 17:49:21.796  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3007] from screen [on:0 period:2051746563] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-11 17:49:21.799  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:2051746566] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
08-11 17:49:21.799  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-11 17:49:22.753  6670  6809 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 878)
,08-11 17:49:22.763  6670  6809 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-11 17:49:22.763  6670  6809 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 879)
,08-11 17:49:24.822  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:2051749590] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-11 17:49:24.835  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:2051749603] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-11 17:49:24.835  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-11 17:49:25.466  1036  1539 E WifiStateMachine:  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,08-11 17:49:25.467  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,08-11 17:49:25.468  1036  1539 E WifiStateMachine:  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0,
,08-11 17:49:25.469  1036  1539 E WifiStateMachine:  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-11 17:49:25.470  1036  1539 E WifiStateMachine:  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-11 17:49:25.472  1036  1539 E WifiStateMachine:  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,08-11 17:49:27.771  6670  6809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-11 17:49:27.771  6670  6809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16e9ee96 added. We now have 3 listener(s)
,08-11 17:49:27.780  1036  2008 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 17:49:27.786  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-11 17:49:27.786  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-11 17:49:27.786  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-11 17:49:27.787  6670  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 17:49:27.787  6670  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26507a17 added. We now have 4 listener(s)
08-11 17:49:27.787  6670  6809 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 17:49:27.788  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-11 17:49:27.791  6670  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-11 17:49:27.798  6670  6809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 17:49:27.798  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:49:27.798  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 17:49:27.798  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:49:27.798  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 17:49:27.798  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 17:49:27.798  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 17:49:27.798  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 17:49:27.800  6670  6809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 17:49:27.800  6670  6809 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 17:49:27.802  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:49:27.804  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 17:49:27.807  6670  6809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 17:49:27.807  6670  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 17:49:27.807  6670  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 17:49:27.808  6670  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:49:27.808  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:49:27.808  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 17:49:27.808  6670  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-11 17:49:27.808  6670  6809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16e9ee96 removed from the list
08-11 17:49:27.808  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:49:27.808  6670  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26507a17 removed from the list
08-11 17:49:27.808  6670  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:49:27.808  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:49:27.809  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:49:27.809  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:49:27.810  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:49:27.810  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 17:49:27.810  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:49:27.810  6670  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26507a17 not in the list
08-11 17:49:27.810  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:49:27.810  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:49:27.811  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 17:49:27.811  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:49:27.811  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:49:27.811  6670  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26507a17 not in the list
08-11 17:49:27.811  6670  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:49:27.811  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:49:27.812  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:49:27.812  6670  6809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16e9ee96 not in the list
08-11 17:49:27.,812  6670  6809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-11 17:49:27.812  6670  6809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24ddffed added. We now have 3 listener(s)
08-11 17:49:27.816  1036  1947 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-11 17:49:27.822  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-11 17:49:27.822  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-11 17:49:27.822  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-11 17:49:27.822  6670  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 17:49:27.822  6670  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34ce5e22 added. We now have 4 listener(s)
08-11 17:49:27.822  6670  6809 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 17:49:27.825  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-11 17:49:27.829  6670  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-11 17:49:27.835  6670  6809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 17:49:27.835  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:49:27.835  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 17:49:27.835  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:49:27.835  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 17:49:27.835  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 17:49:27.835  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 17:49:27.835  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 17:49:27.838  6670  6809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 17:49:27.838  6670  6809 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 17:49:27.840  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:49:27.842  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 17:49:27.843  6670  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-11 17:49:27.844  6670  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-11 17:49:27.844  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-11 17:49:27.844  6670  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 17:49:27.844  6670  6809 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-11 17:49:27.848  6670  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-11 17:49:27.849  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 17:49:27.851  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:2051752618] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-11 17:49:27.851  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:2051752619] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-11 17:49:27.852  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-11 17:49:27.856  6670  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-11 17:49:27.859  6670  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-11 17:49:27.861  6670  6809 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-11 17:49:27.864  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-11 17:49:27.866  6670  6809 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-11 17:49:27.866  6670  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 17:49:27.866  6670  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 17:49:30.870  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:2051755638] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-11 17:49:30.873  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:2051755641] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-11 17:49:30.873  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-11 17:49:30.887  6670  6809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 17:49:30.888  6670  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 17:49:30.888  6670  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 17:49:30.888  6670  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:49:30.888  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:49:30.888  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 17:49:30.888  6670  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-11 17:49:30.888  6670  6809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24ddffed removed from the list
08-11 17:49:30.888  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:49:30.888  6670  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34ce5e22 removed from the list
08-11 17:49:30.889  6670  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:49:30.889  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:49:30.890  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:49:30.890  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:49:30.892  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:49:30.892  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 17:49:30.893  6670  6809 D BluetoothLeScanner: could not find callback wrapper
08-11 17:49:30.893  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 17:49:30.893  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:49:30.893  6670  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34ce5e22 not in the list
08-11 17:49:30.893  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:49:30.893  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:49:30.894  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 17:49:30.895  6670  6809 D BluetoothLeScanner: could not find callback wrapper
08-11 17:49:30.895  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 17:49:30.895  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:49:30.895  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:49:30.895  6670  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34ce5e22 not in the list
08-11 17:49:30.895  6670  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:49:30.895  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listene,r does not exist in the list - probably already removed
08-11 17:49:30.895  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:49:30.895  6670  6809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24ddffed not in the list
08-11 17:49:30.896  6670  6809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-11 17:49:30.896  6670  6809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9983a6e added. We now have 3 listener(s)
08-11 17:49:30.897  1036  1940 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-11 17:49:30.904  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-11 17:49:30.904  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-11 17:49:30.904  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-11 17:49:30.904  6670  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 17:49:30.905  6670  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b2950f added. We now have 4 listener(s)
08-11 17:49:30.905  6670  6809 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 17:49:30.906  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-11 17:49:30.912  6670  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-11 17:49:30.918  6670  6809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 17:49:30.918  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:49:30.918  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 17:49:30.918  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:49:30.918  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 17:49:30.918  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 17:49:30.918  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 17:49:30.918  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 17:49:30.921  6670  6809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 17:49:30.921  6670  6809 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 17:49:30.923  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:49:30.926  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 17:49:30.927  6670  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-11 17:49:30.929  6670  6809 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-11 17:49:30.929  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
08-11 17:49:30.931  6670  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-11 17:49:30.931  6670  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-11 17:49:30.931  6670  6809 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-11 17:49:30.931  6670  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 17:49:30.935  6670  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-11 17:49:30.935  6670  6809 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-11 17:49:30.936  6670  6809 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-11 17:49:30.936  6670  6670 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-11 17:49:30.937  6670  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,08-11 17:49:30.940  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-11 17:49:30.940  6670  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 17:49:30.940  6670  6809 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-11 17:49:30.947  1036  1788 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 17:49:30.949  6670  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-11 17:49:30.950  1036  1975 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 17:49:30.955  6670  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-11 17:49:30.955  6670  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-11 17:49:30.957  6670  6809 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-11 17:49:30.957  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-11 17:49:30.958  6670  8324 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-11 17:49:30.961  7706  7722 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
,08-11 17:49:30.963  6670  8324 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-11 17:49:30.965  6670  6809 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-11 17:49:33.916  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:2051758684] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-11 17:49:33.919  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:2051758687] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-11 17:49:33.919  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL],
,08-11 17:49:33.966  6670  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-11 17:49:33.970  6670  6809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-11 17:49:33.970  6670  6809 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-11 17:49:33.970  6670  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-11 17:49:33.971  6670  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-11 17:49:33.971  6670  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-11 17:49:33.971  6670  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-11 17:49:33.971  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-11 17:49:33.987  6670  8324 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-11 17:49:33.987  6670  8324 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-11 17:49:33.987  6670  8324 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-11 17:49:33.987  6670  6670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-11 17:49:33.989  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 17:49:33.989  6670  6809 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-11 17:49:33.990  6670  6670 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-11 17:49:33.990  6670  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-11 17:49:33.990  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:49:33.990  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 17:49:33.992  6670  6670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 17:49:33.992  6670  6670 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-11 17:49:33.992  6670  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:49:33.992  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:49:33.992  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 17:49:33.992  6670  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-11 17:49:33.993  6670  6809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9983a6e removed from the list
08-11 17:49:33.993  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:49:33.993  6670  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b2950f removed from the list
08-11 17:49:33.993  6670  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:49:33.993  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:49:33.994  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:49:33.994  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:49:33.995  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:49:33.995  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 17:49:33.995  6670  6809 D BluetoothLeScanner: could not find callback wrapper
08-11 17:49:33.995  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 17:49:33.995  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:49:33.995  6670  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b2950f not in the list
08-11 17:49:33.995  6670  6809 W org.thalipro,ject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:49:33.995  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:49:33.997  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-11 17:49:34.002  6670  6809 D BluetoothLeScanner: could not find callback wrapper
08-11 17:49:34.002  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 17:49:34.002  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:49:34.002  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:49:34.002  6670  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b2950f not in the list
08-11 17:49:34.002  6670  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:49:34.002  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:49:34.002  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:49:34.002  6670  6809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9983a6e not in the list
08-11 17:49:34.006  6670  6809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-11 17:49:34.006  6670  6809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@208d732b added. We now have 3 listener(s)
08-11 17:49:34.007  1036  1981 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 17:49:34.010  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-11 17:49:34.010  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-11 17:49:34.010  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-11 17:49:34.010  6670  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 17:49:34.010  6670  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33935388 added. We now have 4 listener(s)
08-11 17:49:34.010  6670  6809 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-11 17:49:34.014  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-11 17:49:34.019  6670  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 17:49:34.022  6670  6809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 17:49:34.022  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:49:34.022  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 17:49:34.022  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:49:34.022  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 17:49:34.022  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 17:49:34.022  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 17:49:34.022  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 17:49:34.027  6670  6809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 17:49:34.027  6670  6809 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 17:49:34.030  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:49:34.032  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:49:34.032  6670  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-11 17:49:34.032  6670  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-11 17:49:34.032  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-11 17:49:34.032  6670  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 17:49:34.032  6670  6809 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-11 17:49:34.036  6670  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-11 17:49:34.039  1036  2053 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 17:49:34.045  6670  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-11 17:49:34.045  6670  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-11 17:49:34.047  6670  6809 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-11 17:49:34.047  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 17:49:34.049  6670  6809 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-11 17:49:36.948  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:2051761716] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-11 17:49:36.951  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:2051761719] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-11 17:49:36.952  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-11 17:49:37.058  6670  6809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-11 17:49:37.059  6670  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 17:49:37.059  6670  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 17:49:37.067  6670  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:49:37.067  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:49:37.067  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 17:49:37.067  6670  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-11 17:49:37.067  6670  6809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@208d732b removed from the list
08-11 17:49:37.067  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:49:37.067  6670  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33935388 removed from the list
08-11 17:49:37.067  6670  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:49:37.067  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:49:37.068  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:49:37.068  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:49:37.071  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:49:37.071  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 17:49:37.072  6670  6809 D BluetoothLeScanner: could not find callback wrapper
08-11 17:49:37.072  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 17:49:37.072  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:49:37.072  6670  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33935388 not in the list
08-11 17:49:37.072  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:49:37.072  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:49:37.073  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 17:49:37.074  6670  6809 D BluetoothLeScanner: could not find callback wrapper
08-11 17:49:37.074  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 17:49:37.074  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:49:37.074  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:49:37.074  6670  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33935388 not in the list
08-11 17:49:37.074  6670  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:49:37.074  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:49:37.074  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:49:37.074  6670  6809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@208d732b not in the list
08-11 17:49:37.075  6670  6809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-11 17:49:37.075  667,0  6809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ece2034 added. We now have 3 listener(s)
08-11 17:49:37.076  1036  1624 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-11 17:49:37.084  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-11 17:49:37.084  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-11 17:49:37.084  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-11 17:49:37.084  6670  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 17:49:37.084  6670  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27cbbe5d added. We now have 4 listener(s)
08-11 17:49:37.084  6670  6809 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 17:49:37.085  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-11 17:49:37.089  6670  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-11 17:49:37.095  6670  6809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 17:49:37.095  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:49:37.095  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 17:49:37.095  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:49:37.095  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 17:49:37.095  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 17:49:37.095  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 17:49:37.095  6670  6809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 17:49:37.097  6670  6809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 17:49:37.097  6670  6809 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 17:49:37.099  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:49:37.101  6670  6670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 17:49:37.105  6670  6809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-11 17:49:37.105  6670  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-11 17:49:37.105  6670  6809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 17:49:37.105  6670  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-11 17:49:37.105  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
,08-11 17:49:37.105  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 17:49:37.105  6670  6809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-11 17:49:37.105  6670  6809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ece2034 removed from the list
08-11 17:49:37.105  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:49:37.105  6670  6809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27cbbe5d removed from the list
08-11 17:49:37.105  6670  6809 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:49:37.106  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-11 17:49:37.107  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:49:37.107  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:49:37.108  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:49:37.108  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-11 17:49:37.108  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:49:37.108  6670  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27cbbe5d not in the list
08-11 17:49:37.108  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:49:37.108  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:49:37.109  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-11 17:49:37.109  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:49:37.109  6670  6809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:49:37.110  6670  6809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27cbbe5d not in the list
08-11 17:49:37.110  6670  6809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:49:37.110  6670  6809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-11 17:49:37.110  6670  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:49:37.110  6670  6809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ece2034 not in the list
08-11 17:49:39.977  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:2051764745] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-11 17:49:39.980  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:2051764748] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-11 17:49:39.980  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-11 17:49:42.113  6670  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-11 17:49:42.113  6670  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-11 17:49:42.123  6670  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,08-11 17:49:42.125  6670  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-11 17:49:42.125  6670  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-11 17:49:42.125  6670  6809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-11 17:49:43.008  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:2051767776] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-11 17:49:43.011  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:2051767779] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
08-11 17:49:43.012  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-11 17:49:46.038  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:2051770806] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-11 17:49:46.041  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:2051770809] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-11 17:49:46.041  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-11 17:49:49.069  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:2051773837] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-11 17:49:49.072  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:2051773840] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-11 17:49:49.073  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-11 17:49:49.150  6670  8325 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 888, name: My test thread name)
,08-11 17:49:51.148  6670  6809 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 888
,08-11 17:49:51.155  6670  6809 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 888, name: My test thread name)
08-11 17:49:51.164  6670  8326 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 889, name: My test thread name)
08-11 17:49:51.165  6670  8326 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 889, thread name: My test thread name)
08-11 17:49:51.165  6670  8326 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 889, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
08-11 17:49:51.172  6670  6809 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-11 17:49:51.180  6670  8327 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 893, name: My test thread name)
08-11 17:49:51.180  6670  8327 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 893, thread name: My test thread name): Test exception.
08-11 17:49:51.180  6670  8327 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 893, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
08-11 17:49:51.186  6670  6809 I jxcore-log: Total number of executed tests:  82
08-11 17:49:51.186  6670  6809 I jxcore-log: 
08-11 17:49:51.187  6670  6809 I jxcore-log: Number of passed tests:  81
08-11 17:49:51.187  6670  6809 I jxcore-log: 
08-11 17:49:51.187  6670  6809 I jxcore-log: Number of failed tests:  1
08-11 17:49:51.187  6670  6809 I jxcore-log: 
08-11 17:49:51.187  6670  6809 I jxcore-log: Number of ignored tests:  0
08-11 17:49:51.187  6670  6809 I jxcore-log: 
08-11 17:49:51.188  6670  6809 I jxcore-log: Total duration:  142794
08-11 17:49:51.188  6670  6809 I jxcore-log: 
08-11 17:49:51.188  6670  6809 I jxcore-log: Failures: 
08-11 17:49:51.188  6670  6809 I jxcore-log:  mCurrentOperation should be null1
08-11 17:49:51.188  6670  6809 I jxcore-log: Expected: is null
08-11 17:49:51.188  6670  6809 I jxcore-log:      but: was <Start operation: Should start/stop everything>
08-11 17:49:51.188  6670  6809 I jxcore-log: 
08-11 17:49:51.188  6670  6809 I jxcore-log: 
08-11 17:49:51.188  6670  6809 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-11 17:49:51.188  6670  6809 I jxcore-log: 
,08-11 17:49:51.206  6670  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 17:49:51.206  6670  6809 I jxcore-log: 
08-11 17:49:51.209  6670  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 17:49:51.209  6670  6809 I jxcore-log: 
08-11 17:49:51.210  6670  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 17:49:51.210  6670  6809 I jxcore-log: 
08-11 17:49:51.211  6670  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 17:49:51.211  6670  6809 I jxcore-log: 
08-11 17:49:51.212  6670  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 17:49:51.212  6670  6809 I jxcore-log: 
,08-11 17:49:51.226  6670  8325 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 888, name: My test thread name), during the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
,08-11 17:49:51.231  6670  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 17:49:51.231  6670  6809 I jxcore-log: 
08-11 17:49:51.235  6670  6670 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-11 17:49:51.236  6670  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-11 17:49:51.236  6670  6809 I jxcore-log: 
08-11 17:49:51.238  6670  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-11 17:49:51.238  6670  6809 I jxcore-log: 
08-11 17:49:51.239  6670  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-11 17:49:51.239  6670  6809 I jxcore-log: 
08-11 17:49:51.240  6670  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-11 17:49:51.240  6670  6809 I jxcore-log: 
08-11 17:49:51.241  6670  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-11 17:49:51.241  6670  6809 I jxcore-log: 
08-11 17:49:51.242  6670  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-11 17:49:51.242  6670  6809 I jxcore-log: 
08-11 17:49:51.243  6670  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-11 17:49:51.243  6670  6809 I jxcore-log: 
08-11 17:49:51.244  6670  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-11 17:49:51.244  6670  6809 I jxcore-log: 
08-11 17:49:51.245  6670  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-11 17:49:51.245  6670  6809 I jxcore-log: 
08-11 17:49:51.246  6670  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-11 17:49:51.246  6670  6809 I jxcore-log: 
08-11 17:49:51.246  6670  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-11 17:49:51.246  6670  6809 I jxcore-log: 
08-11 17:49:51.247  6670  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-11 17:49:51.247  6670  6809 I jxcore-log: 
08-11 17:49:51.248  6670  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-11 17:49:51.248  6670  6809 I jxcore-log: 
08-11 17:49:51.249  6670  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-11 17:49:51.249  6670  6809 I jxcore-log: 
08-11 17:49:51.249  6670  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-11 17:49:51.249  6670  6809 I jxcore-log: 
08-11 17:49:51.250  6670  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-11 17:49:51.250  6670  6809 I jxcore-log: 
08-11 17:49:51.251  6670  6809 I jxcore-log: DEBUG thaliMobil,eNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-11 17:49:51.251  6670  6809 I jxcore-log: 
08-11 17:49:51.251  6670  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-11 17:49:51.251  6670  6809 I jxcore-log: 
08-11 17:49:51.252  6670  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-11 17:49:51.252  6670  6809 I jxcore-log: 
08-11 17:49:51.253  6670  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-11 17:49:51.253  6670  6809 I jxcore-log: 
,08-11 17:49:51.258  6670  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-11 17:49:51.258  6670  6809 I jxcore-log: 
08-11 17:49:51.260  6670  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-11 17:49:51.260  6670  6809 I jxcore-log: 
08-11 17:49:51.260  6670  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-11 17:49:51.260  6670  6809 I jxcore-log: 
08-11 17:49:51.261  6670  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 17:49:51.261  6670  6809 I jxcore-log: 
08-11 17:49:51.262  6670  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 17:49:51.262  6670  6809 I jxcore-log: 
08-11 17:49:51.263  6670  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 17:49:51.263  6670  6809 I jxcore-log: 
08-11 17:49:51.274  6670  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 17:49:51.274  6670  6809 I jxcore-log: 
08-11 17:49:51.275  6670  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 17:49:51.275  6670  6809 I jxcore-log: 
08-11 17:49:51.276  6670  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 17:49:51.276  6670  6809 I jxcore-log: 
08-11 17:49:51.277  6670  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 17:49:51.277  6670  6809 I jxcore-log: 
08-11 17:49:51.278  6670  6809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 17:49:51.278  6670  6809 I jxcore-log: 
,08-11 17:49:51.511  8328  8328 D AndroidRuntime: 
08-11 17:49:51.511  8328  8328 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-11 17:49:51.515  8328  8328 D AndroidRuntime: CheckJNI is OFF
,08-11 17:49:51.676  8328  8328 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-11 17:49:51.690  1036  1100 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-11 17:49:51.693  1036  1100 I ActivityManager: Killing 6670:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-11 17:49:51.777  1036  1464 W InputDispatcher: channel '7f13035 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
08-11 17:49:51.777  1036  1464 E InputDispatcher: channel '7f13035 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,08-11 17:49:51.778  1036  2035 I WindowState: WIN DEATH: Window{7f13035 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-11 17:49:51.778  1036  2035 W InputDispatcher: Attempted to unregister already unregistered input channel '7f13035 com.test.thalitest/com.test.thalitest.MainActivity (server)'
08-11 17:49:51.779  1036  1544 D WifiService: Client connection lost with reason: 4
08-11 17:49:51.784  1036  2035 D InputDispatcher: Window went away: Window{7f13035 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-11 17:49:51.809  1036  1100 I ActivityManager:   Force finishing activity ActivityRecord{823cd5e u0 com.test.thalitest/.MainActivity t6}
,08-11 17:49:51.823   342   358 E GBMv2   : DFP En is all cleared set to be enabled
08-11 17:49:51.823  1036  1125 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
,08-11 17:49:51.825  1036  1125 I ActivityManager:   Force finishing activity ActivityRecord{823cd5e u0 com.test.thalitest/.MainActivity t6 f}
08-11 17:49:51.825  1036  1125 W ActivityManager: Duplicate finish request for ActivityRecord{823cd5e u0 com.test.thalitest/.MainActivity t6 f}
08-11 17:49:51.857  2036  2036 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-11 17:49:51.858  2036  2036 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-11 17:49:51.861  1944  1961 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
,08-11 17:49:51.862  1944  1961 D SplitWindowPolicy: topRunningActivity=ActivityInfo{c743158 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-11 17:49:51.862  1036  1981 W ActivityManager: Spurious death for ProcessRecord{31041d5c 6670:com.test.thalitest/u0a118}, curProc for 6670: null
08-11 17:49:51.864  1944  1960 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-11 17:49:51.864  2036  2036 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-11 17:49:51.865  1944  1960 D SplitWindowPolicy: topRunningActivity=ActivityInfo{369202b1 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-11 17:49:51.865  2036  2087 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-11 17:49:51.868  1603  1603 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-11 17:49:51.871  3897  3897 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-11 17:49:51.879  7706  7706 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-11 17:49:51.879  7706  7706 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-11 17:49:51.880  1998  1998 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-11 17:49:51.880  2477  2684 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-11 17:49:51.905  1036  1465 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-11 17:49:51.922  1036  1905 V SIM_STK : Menu title from STK is T-Mobile
08-11 17:49:51.944  6495  6495 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,08-11 17:49:51.963  1821  1821 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
,08-11 17:49:51.964  1908  1908 D ActionManagerService: notifyUserLog: 1000003
08-11 17:49:51.965  2036  2036 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-11 17:49:51.966  2036  2036 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-11 17:49:51.967  2036  2036 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-11 17:49:51.968  1603  1603 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-11 17:49:51.971  1603  1667 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-11 17:49:51.971  1603  1667 D KeyguardModel: createShortcutInfo...
08-11 17:49:51.971  2184  2184 I ConfigService: onCreate
08-11 17:49:51.971  2184  2184 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-11 17:49:51.972  2036  2036 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-11 17:49:51.974  3897  4526 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
,08-11 17:49:51.975  1603  1667 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-11 17:49:51.975  1603  1667 D KeyguardModel: createShortcutInfo...
08-11 17:49:51.976  2036  2036 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-11 17:49:51.992  4634  4634 I art     : Explicit concurrent mark sweep GC freed 8081(465KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 301us total 121.810ms
,08-11 17:49:51.996  2184  2184 I ConfigService: onBind returning update interface
,08-11 17:49:51.997  1908  1908 D ActionManagerService: notifyUserLog: 1000004
08-11 17:49:52.006  3897  3913 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-11 17:49:52.008  4532  4532 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-11 17:49:52.008  4532  4532 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-11 17:49:52.008  4532  4532 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-11 17:49:52.008  4532  4532 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-11 17:49:52.008  4532  4532 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
,08-11 17:49:52.008  4532  4532 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-11 17:49:52.008  4532  4532 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-11 17:49:52.008  4532  4532 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-11 17:49:52.008  4532  4532 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 17:49:52.009  4532  4532 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-11 17:49:52.009  4532  4532 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-11 17:49:52.009  4532  4532 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-11 17:49:52.010  3897  4526 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-11 17:49:52.015  1603  1667 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-11 17:49:52.015  2036  2036 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-11 17:49:52.015  2036  2036 I GBoardWebViewUtils: , create_time: 1430832262123
08-11 17:49:52.015  2036  2036 I GBoardWebViewUtils: , expire_time: 0
08-11 17:49:52.015  2036  2036 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-11 17:49:52.015  2036  2036 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-11 17:49:52.015  2036  2036 I GBoardWebViewUtils: , display: false
08-11 17:49:52.015  2036  2036 I GBoardWebViewUtils: , animation: false }
08-11 17:49:52.015  2036  2036 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-11 17:49:52.015  2036  2036 I GBoardWebViewUtils: , create_time: 1430832262287
08-11 17:49:52.015  2036  2036 I GBoardWebViewUtils: , expire_time: 0
08-11 17:49:52.015  2036  2036 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-11 17:49:52.015  2036  2036 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-11 17:49:52.015  2036  2036 I GBoardWebViewUtils: , display: false
08-11 17:49:52.015  2036  2036 I GBoardWebViewUtils: , animation: false }
08-11 17:49:52.015  2036  2036 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1470393742816
08-11 17:49:52.015  2036  2036 I GBoardWebViewUtils: , create_time: 1470393743569
08-11 17:49:52.015  2036  2036 I GBoardWebViewUtils: , expire_time: 0
08-11 17:49:52.015  2036  2036 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-11 17:49:52.015  2036  2036 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-11 17:49:52.015  2036  2036 I GBoardWebViewUtils: , display: false
08-11 17:49:52.015  2036  2036 I GBoardWebViewUtils: , animation: false }
08-11 17:49:52.015  1821  1821 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-11 17:49:52.016  2184  2184 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-11 17:49:52.016  2184  2184 I ConfigService: onBind returning config service
08-11 17:49:52.018  1603  1603 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-11 17:49:52.018  1603  1603 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-11 17:49:52.021  1821  1821 I ConfigFetchSe,rvice: service connected
08-11 17:49:52.021  1821  1821 I ConfigClient: service connected
08-11 17:49:52.028  2184  2184 I ConfigService: onDestroy
08-11 17:49:52.028  1603  1667 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-11 17:49:52.028  1603  1667 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-11 17:49:52.029  1603  1667 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-11 17:49:52.029  1603  1667 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 17:49:52.030  1603  1667 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-11 17:49:52.038  1873  1873 D SplitUIManager: split_name #11 / not available #0
08-11 17:49:52.039  1873  1873 D SplitUIService: removed split : 
08-11 17:49:52.042  1603  1667 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-11 17:49:52.042  1603  1667 D KeyguardModel: createShortcutInfo...
08-11 17:49:52.044  1036  1036 I art     : Explicit concurrent mark sweep GC freed 41273(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.959ms total 190.335ms
,08-11 17:49:52.049  2036  8360 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-11 17:49:52.051  2036  2036 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-11 17:49:52.051  2036  2036 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-11 17:49:52.057  1821  8361 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-11 17:49:52.048  1036  1125 I art     : WaitForGcToComplete blocked for 103.551ms for cause Explicit
08-11 17:49:52.066  1603  1667 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-11 17:49:52.066  1603  1667 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-11 17:49:52.075  1603  1667 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 17:49:52.075  1603  1667 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-11 17:49:52.077  1603  1667 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-11 17:49:52.077  1603  1667 D KeyguardModel: createShortcutInfo...
08-11 17:49:52.082  1603  1667 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-11 17:49:52.082  1603  1667 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-11 17:49:52.082  1603  1667 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-11 17:49:52.082  1603  1667 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-11 17:49:52.083  1603  1667 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-11 17:49:52.084  1603  1667 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-11 17:49:52.088  1873  1873 D SplitUIManager: split_name #11 / not available #0
08-11 17:49:52.088  1873  1873 I SplitUIService: split app #11
08-11 17:49:52.089  1603  1667 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-11 17:49:52.089  1603  1667 D KeyguardModel: createShortcutInfo...
08-11 17:49:52.090  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:2051776858] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-11 17:49:52.091  1036  1577 V SIM_STK : Menu title from STK is T-Mobile
08-11 17:49:52.091  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:2051776859] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-11 17:49:52.091  1036  1577 V SIM_STK : Menu title from STK is T-Mobile
08-11 17:49:52.091  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-11 17:49:52.105  8032  8032 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-11 17:49:52.112  1036  1036 D administrator: Handling package changes for user 0
,08-11 17:49:52.117  1603  1603 D KeyguardModel: handleShortcutListChanged...
08-11 17:49:52.117  1603  1603 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-11 17:49:52.127  2036  2036 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-11 17:49:52.129  1603  1667 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-11 17:49:52.129  1603  1667 D KeyguardModel: createShortcutInfo...
,08-11 17:49:52.130  1603  1667 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-11 17:49:52.130  1603  1667 D KeyguardModel: createShortcutInfo...
08-11 17:49:52.131  1603  1667 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 17:49:52.131  1603  1667 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-11 17:49:52.132  1603  1667 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-11 17:49:52.132  1603  1667 D KeyguardModel: createShortcutInfo...
08-11 17:49:52.133  1603  1667 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 17:49:52.133  1603  1667 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-11 17:49:52.134  1603  1667 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-11 17:49:52.134  1603  1667 D KeyguardModel: createShortcutInfo...
,08-11 17:49:52.141   332   436 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-11 17:49:52.141  3178  8368 I Thermal-Lib: Thermal-Lib-Client: Client request sent
,08-11 17:49:52.145  5997  8369 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-11 17:49:52.146  1603  1667 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 17:49:52.146  1603  1667 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-11 17:49:52.148  1603  1667 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-11 17:49:52.148  1603  1667 D KeyguardModel: createShortcutInfo...
08-11 17:49:52.150  1036  1577 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-11 17:49:52.151  7706  7706 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-11 17:49:52.151  7706  7706 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-11 17:49:52.151  7706  7706 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-11 17:49:52.151  7706  7706 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-11 17:49:52.151  7706  7706 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-11 17:49:52.151  7706  7706 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-11 17:49:52.151  7706  7706 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-11 17:49:52.151  7706  7706 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-11 17:49:52.151  7706  7706 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-11 17:49:52.151  7706  7706 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-11 17:49:52.151  7706  7706 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-11 17:49:52.164  1821  8372 I PeopleContactsSync: CP2 sync disabled
,08-11 17:49:52.181  1603  1603 D KeyguardModel: handleShortcutListChanged...
08-11 17:49:52.181  1603  1603 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-11 17:49:52.189  1821  4803 I Icing   : doRemovePackageData com.test.thalitest
08-11 17:49:52.191  1036  1940 V SIM_STK : Menu title from STK is T-Mobile
08-11 17:49:52.220  1036  1914 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8376 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-11 17:49:52.223  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-11 17:49:52.223  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-11 17:49:52.223  1036  1036 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-11 17:49:52.225  2366  8375 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-11 17:49:52.229  1036  1578 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-11 17:49:52.239  1821  8371 W GmsApplication: Using Auth Proxy for data requests.
,08-11 17:49:52.268  2036  2036 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-11 17:49:52.272  2036  2036 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-11 17:49:52.273  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-11 17:49:52.275  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-11 17:49:52.276  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-11 17:49:52.276  1036  1125 I art     : Explicit concurrent mark sweep GC freed 7640(395KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 2.812ms total 215.047ms
08-11 17:49:52.277  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-11 17:49:52.285  8376  8376 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-11 17:49:52.285  8376  8376 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-11 17:49:52.286  8376  8376 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-11 17:49:52.286  8376  8376 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-11 17:49:52.290  1036  1120 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{22b84d70 u0 com.lge.launcher2/.Launcher t5} time:271216
08-11 17:49:52.291  2184  4232 I art     : Explicit concurrent mark sweep GC freed 7196(452KB) AllocSpace objects, 4(64KB) LOS objects, 52% free, 29MB/61MB, paused 2.952ms total 37.945ms
08-11 17:49:52.295  2036  2036 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-11 17:49:52.295  2036  2036 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-11 17:49:52.296  1821  8371 W GmsApplication: Using Auth Proxy for data requests.
08-11 17:49:52.300  2036  2156 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
,08-11 17:49:52.304  2036  2156 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-11 17:49:52.309  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-11 17:49:52.310  2036  2036 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-11 17:49:52.310  2036  2036 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-11 17:49:52.317  2036  2036 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,08-11 17:49:52.319  2598  2598 D [Concierge]Service: onStartCommand(). Type : 8
08-11 17:49:52.319  2598  2598 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-11 17:49:52.320  2598  2598 D [Concierge]Service: Update widget ID : 11
08-11 17:49:52.320  2036  2036 D [Concierge]WidgetView: change position of spinner
08-11 17:49:52.321  2036  2036 I [Concierge]WidgetView: initWebView(). Time : 1470930592321
08-11 17:49:52.322  2598  2598 D [Concierge]Service: onStartCommand(). Type : 0
08-11 17:49:52.335  2036  2036 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 402546567
08-11 17:49:52.335  2036  2036 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-11 17:49:52.335  2036  2036 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-11 17:49:52.338  2036  2036 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@2808f388
08-11 17:49:52.338  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
,08-11 17:49:52.339  2036  2036 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-11 17:49:52.339  2036  2036 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-11 17:49:52.343  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-11 17:49:52.344  2036  2036 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-11 17:49:52.344  2036  2036 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-11 17:49:52.345  2036  2036 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1470930349245, New one : 1470930592321
08-11 17:49:52.345  2036  2036 D [Concierge]WidgetView: Unregister all receivers
08-11 17:49:52.345  2036  2036 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-11 17:49:52.345  2036  2036 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-11 17:49:52.347  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-11 17:49:52.348  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-11 17:49:52.349  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-11 17:49:52.350  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
,08-11 17:49:52.351  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-11 17:49:52.356  2036  2036 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-11 17:49:52.356  2036  2036 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-11 17:49:52.371  8376  8376 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-11 17:49:52.384  8328  8328 D AndroidRuntime: Shutting down VM
,08-11 17:49:52.394  8376  8376 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-11 17:49:52.398  2036  2036 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-11 17:49:52.405  1036  1099 W InputMethodInfo: Duplicated subtype definition found: , voice
08-11 17:49:52.406  2036  2036 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-11 17:49:52.406  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-11 17:49:52.407  2036  2036 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-11 17:49:52.424  8376  8376 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-11 17:49:52.430  2036  2036 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@25414b55 time:271356
08-11 17:49:52.433  1036  1125 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8397 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-11 17:49:52.454  8376  8376 D LgDataFeature: LgDataFeature() Constructor: none
08-11 17:49:52.454  8376  8376 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-11 17:49:52.485  1036  1975 I ActivityManager: Killing 7030:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-11 17:49:52.550  1036  1099 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-11 17:49:52.555  1036  1099 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-11 17:49:52.562  2036  2036 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-11 17:49:52.594  1036  1981 W libprocessgroup: failed to open /acct/uid_10026/pid_7030/cgroup.procs: No such file or directory
,08-11 17:49:52.598  2036  2036 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-11 17:49:52.603  8376  8376 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
08-11 17:49:52.604  2036  2974 I GBoardtInterface: onReloaded()
08-11 17:49:52.606  2036  2036 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
,08-11 17:49:52.606  3897  4076 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-11 17:49:52.608  3897  3913 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-11 17:49:52.612  1036  2016 I ActivityManager: Killing 7210:com.google.android.setupwizard/u0a46 (adj 15): empty #17
08-11 17:49:52.635  1998  1998 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-11 17:49:52.635  1036  1975 W libprocessgroup: failed to open /acct/uid_10046/pid_7210/cgroup.procs: No such file or directory
08-11 17:49:52.635  1998  1998 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-11 17:49:52.635  1908  1908 D ActionManagerService: notifyUserLog: 1000001
,08-11 17:49:52.637  1998  1998 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-11 17:49:52.637  3897  4526 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-11 17:49:52.638  3897  4526 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-11 17:49:52.640  1908  1908 D ActionManagerService: notifyUserLog: 1000001
08-11 17:49:52.640  6495  6495 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-11 17:49:52.641  3897  4526 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-11 17:49:52.641  3897  4526 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-11 17:49:52.641  3897  4526 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-11 17:49:52.641  3897  4526 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-11 17:49:52.641  3897  4076 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-11 17:49:52.670  1036  1577 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=8420 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-11 17:49:52.673  2036  2036 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-11 17:49:52.673  2036  2036 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-11 17:49:52.675  2036  2036 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-11 17:49:52.675  2036  2036 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-11 17:49:52.677  2036  2036 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-11 17:49:52.677  2036  2036 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,08-11 17:49:52.718  8420  8420 E SQLiteDatabase: Failed to open database '/data/data/com.lge.lifetracker/databases/lifetracker2.db'.
08-11 17:49:52.718  8420  8420 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 17:49:52.718  8420  8420 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 17:49:52.718  8420  8420 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-11 17:49:52.718  8420  8420 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-11 17:49:52.718  8420  8420 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 17:49:52.718  8420  8420 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 17:49:52.718  8420  8420 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 17:49:52.718  8420  8420 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-11 17:49:52.718  8420  8420 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-11 17:49:52.718  8420  8420 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-11 17:49:52.718  8420  8420 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-11 17:49:52.718  8420  8420 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-11 17:49:52.718  8420  8420 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 17:49:52.718  8420  8420 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-11 17:49:52.718  8420  8420 E SQLiteDatabase: 	at com.lge.lifetracker.core.provider.LifetrackerProvider2.onCreate(LifetrackerProvider2.java:56)
08-11 17:49:52.718  8420  8420 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-11 17:49:52.718  8420  8420 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-11 17:49:52.718  8420  8420 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-11 17:49:52.718  8420  8420 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-11 17:49:52.718  8420  8420 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-11 17:49:52.718  8420  8420 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-11 17:49:52.718  8420  8420 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-11 17:49:52.718  8420  8420 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 17:49:52.718  8420  8420 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-11 17:49:52.718  8420  8420 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-11 17:49:52.718  8420  8420 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 17:49:52.718  8420  8420 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-11 17:49:52.718  8420  8420 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-11 17:49:52.718  8420  8420 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-11 17:49:52.719  8420  8420 E LifetrackerProvider2: Unable to open database for writing.
08-11 17:49:52.719  8420  8420 E LifetrackerProvider2: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 17:49:52.719  8420  8420 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 17:49:52.719  8420  8420 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-11 17:49:52.719  8420  8420 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-11 17:49:52.719  8420  8420 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 17:49:52.719  8420  8420 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 17:49:52.719  8420  8420 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 17:49:52.719  8420  8420 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-11 17:49:52.719  8420  8420 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-11 17:49:52.719  8420  8420 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-11 17:49:52.719  8420  8420 E LifetrackerProvider2: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-11 17:49:52.719  8420  8420 E LifetrackerProvider2: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-11 17:49:52.719  8420  8420 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 17:49:52.719  8420  8420 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-11 17:49:52.719  8420  8420 E LifetrackerProvider2: 	at com.lge.lifetracker.core.provider.LifetrackerProvider2.onCreate(LifetrackerProvider2.java:56)
08-11 17:49:52.719  8420  8420 E LifetrackerProvider2: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-11 17:49:52.719  8420  8420 E LifetrackerProvider2: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-11 17:49:52.719  8420  8420 E LifetrackerProvider2: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-11 17:49:52.719  8420  8420 E LifetrackerProvider2: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-11 17:49:52.719  8420  8420 E LifetrackerProvider2: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-11 17:49:52.719  8420  8420 E LifetrackerProvider2: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-11 17:49:52.719  8420  8420 E LifetrackerProvider2: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-11 17:49:52.719  8420  8420 E LifetrackerProvider2: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 17:49:52.719  8420  8420 E LifetrackerProvider2: 	at android.os.Looper.loop(Looper.java:135)
08-11 17:49:52.719  8420  8420 E LifetrackerProvider2: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-11 17:49:52.719  8420  8420 E LifetrackerProvider2: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 17:49:52.719  8420  8420 E LifetrackerProvider2: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-11 17:49:52.719  8420  8420 E LifetrackerProvider2: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-11 17:49:52.719  8420  8420 E LifetrackerProvider2: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-11 17:49:52.729  8420  8420 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-11 17:49:52.729  8420  8420 W LG Account v2.2: No Profi,leInfo entries
08-11 17:49:52.729  8420  8420 I LG Account v2.2: isEnabled: false
08-11 17:49:52.729  8420  8420 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-11 17:49:52.729  8420  8420 I Feature : [Lifetracker]Country: EU
08-11 17:49:52.729  8420  8420 I Feature : [Lifetracker]Operator: OPEN
08-11 17:49:52.729  8420  8420 I Feature : [Lifetracker]Ranking support: false
08-11 17:49:52.729  8420  8420 I Feature : [Lifetracker]Comfort support: false
08-11 17:49:52.730  8420  8420 I Feature : [Lifetracker]Accessory: true
08-11 17:49:52.730  8420  8420 I Feature : [Lifetracker]Health device: true
08-11 17:49:52.730  8420  8420 I Feature : [Lifetracker]Extra Pedometer: false
08-11 17:49:52.730  8420  8420 I Feature : [Lifetracker]Blood glucose device: false
08-11 17:49:52.730  8420  8420 I Feature : [Lifetracker]Device Number: 3
08-11 17:49:52.730  8420  8420 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
08-11 17:49:52.759  1036  2016 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=8439 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-11 17:49:52.760  1036  2016 I ActivityManager: Killing 7240:com.android.chrome/u0a57 (adj 15): empty #17

```
