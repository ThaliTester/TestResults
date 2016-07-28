#### Test 77622416c9749bc_thali05_LGE-LG-D855 Logs


```
--------- beginning of main
07-28 12:04:58.051  6474  6474 D DocsApplication: Installing DEX configuration.
07-28 12:04:58.067  6474  6474 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
07-28 12:04:58.071  6474  6474 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{147d4f1a com.google.android.apps.docs}
07-28 12:04:58.087  6474  6474 D TAG     : onCreate()
07-28 12:04:58.115  6474  6474 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
07-28 12:04:58.671   338   422 I ThermalEngine: Thermal-Server: Thermal received msg from  override
07-28 12:04:58.671  3207  6506 I Thermal-Lib: Thermal-Lib-Client: Client request sent
07-28 12:04:58.724  1602  1602 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-28 12:04:58.724  1602  1602 I [SystemUI]LGPowerUI: On Skip Timer : true
--------- beginning of system
07-28 12:04:58.732  1940  2115 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-28 12:04:58.732  1940  2115 D LEDHandler: Battery Level Remaining: 100%
07-28 12:04:58.732  1940  2115 D LEDHandler: Battery Temp: 287, mChargingStatus=5, mChargingStop=false
07-28 12:04:58.732  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:04:58.732  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:04:58.732  1032  1544 D WifiController: battery changed pluggedType: 2
07-28 12:04:58.734  3885  3998 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-28 12:04:58.734  1602  1602 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
07-28 12:04:58.734  1602  1602 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-28 12:04:58.736  1602  1602 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-28 12:04:58.979  1816  4756 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
07-28 12:04:59.024  1816  4756 D Icing   : Loaded CLD2 Version V2.0 - 20140131
,07-28 12:04:59.073  1816  4756 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
07-28 12:04:59.235  6507  6507 D AndroidRuntime: 
07-28 12:04:59.235  6507  6507 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-28 12:04:59.237  6507  6507 D AndroidRuntime: CheckJNI is OFF
07-28 12:04:59.321  6474  6474 D LgDataFeature: LgDataFeature() Constructor: none
07-28 12:04:59.321  6474  6474 D LgDataFeature: LgDataFeature() Constructor Done, null
07-28 12:04:59.335  6507  6507 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-28 12:04:59.338  1032  1975 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-28 12:04:59.347  1940  6337 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
07-28 12:04:59.350  1032  1975 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
07-28 12:04:59.351  1032  1975 D ActivityManager: setTaskToReturnTo : TaskRecord{3ce0ad8c #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
07-28 12:04:59.351  1032  1975 D ActivityManager: setTaskToReturnTo : TaskRecord{3ce0ad8c #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
07-28 12:04:59.353  1032  1975 D WindowStateEx: AppWindowTokenEx init.. 
07-28 12:04:59.354   345   357 E GBMv2   : DFP En is all cleared set to be enabled
07-28 12:04:59.393  1032  1975 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6524 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-28 12:04:59.394  6507  6507 D AndroidRuntime: Shutting down VM
07-28 12:04:59.434  1940  6337 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
07-28 12:04:59.434  1940  6337 D SplitWindowPolicy: topRunningActivity=ActivityInfo{295ac5b6 co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
07-28 12:04:59.436  1940  1955 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
07-28 12:04:59.436  1940  1955 D SplitWindowPolicy: topRunningActivity=ActivityInfo{24a7d2b7 co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
07-28 12:04:59.470  6524  6524 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
07-28 12:04:59.504  6152  6152 I LockScreenSettings: New app installed broadcast received ..
07-28 12:04:59.506  6152  6152 I LockScreenSettings: Number of installed packages  1
07-28 12:04:59.527  6474  6474 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
07-28 12:04:59.543  6524  6524 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
07-28 12:04:59.552  6524  6524 I LibraryLoader: Loading: webviewchromium
07-28 12:04:59.555  6524  6524 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9603-9606)
07-28 12:04:59.555  6524  6524 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-28 12:04:59.565  6524  6524 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2e3ae2d4}
07-28 12:04:59.566  6524  6524 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-28 12:04:59.567  6524  6524 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
07-28 12:04:59.573  6524  6524 I BrowserStartupController: Initializing chromium process, renderers=0
07-28 12:04:59.574  6524  6524 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-28 12:04:59.585  6524  6524 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
07-28 12:04:59.585  6524  6524 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
07-28 12:04:59.586  6524  6524 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
07-28 12:04:59.592  1032  1975 V SIM_STK : Menu title from STK is T-Mobile
07-28 12:04:59.594   329  1387 V AudioPolicyService: registerClient() client 0xb558a960, uid 10118
07-28 12:04:59.608  1032  1097 D BluetoothManagerService: Message: 20
07-28 12:04:59.608  1032  1097 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b43bb53:true
07-28 12:04:59.610  6524  6524 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-28 12:04:59.610  6524  6524 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-28 12:04:59.610  6524  6524 I Adreno-EGL: Build Date: 12/12/14 금
07-28 12:04:59.610  6524  6524 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-28 12:04:59.610  6524  6524 I Adreno-EGL: Remote Branch: 
07-28 12:04:59.610  6524  6524 I Adreno-EGL: Local Patches: 
07-28 12:04:59.610  6524  6524 I Adreno-EGL: Reconstruct Branch: 
07-28 12:04:59.637  1032  1048 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6575 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
07-28 12:04:59.682  6524  6572 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
07-28 12:04:59.683  6524  6524 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
07-28 12:04:59.698  6524  6524 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-28 12:04:59.701  6524  6524 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-28 12:04:59.704  6524  6524 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
07-28 12:04:59.706  6524  6524 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
07-28 12:04:59.706  6524  6524 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
07-28 12:04:59.710  6575  6575 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
07-28 12:04:59.710  6575  6575 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
07-28 12:04:59.723  6524  6524 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
07-28 12:04:59.759  1032  1939 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6598 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
07-28 12:04:59.761  1032  1939 I ActivityManager: Killing 5924:com.google.android.talk/u0a72 (adj 15): empty #17
07-28 12:04:59.860  1032  1921 W libprocessgroup: failed to open /acct/uid_10072/pid_5924/cgroup.procs: No such file or directory
07-28 12:04:59.864  6524  6524 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-28 12:04:59.864  6524  6524 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-28 12:04:59.926  6524  6623 D OpenGLRenderer: Render dirty regions requested: true
07-28 12:04:59.926  6524  6623 I OpenGLRenderer: Initialized EGL, version 1.4
07-28 12:04:59.926  6598  6598 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
07-28 12:04:59.932  6524  6623 D OpenGLRenderer: Enabling debug mode 0
07-28 12:04:59.932  1032  1092 W ActivityManager: Activity pause timeout for ActivityRecord{26d2bcd5 u0 com.test.thalitest/.MainActivity t40}
07-28 12:04:59.939  6524  6524 D Atlas   : Validating map...
07-28 12:04:59.943  1032  1939 D SplitWindow: check instance of lgWin Window{14b930d8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-28 12:04:59.971  6598  6598 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-28 12:04:59.974  6338  6338 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
07-28 12:04:59.989  6524  6621 D LgDataFeature: LgDataFeature() Constructor: none
07-28 12:04:59.990  6524  6621 D LgDataFeature: LgDataFeature() Constructor Done, null
07-28 12:04:59.996  1032  1975 I ActivityManager: Killing 5671:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
07-28 12:05:00.014  5647  5647 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
07-28 12:05:00.015  5647  5647 W System.err: android.os.DeadObjectException
07-28 12:05:00.015  5647  5647 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
07-28 12:05:00.015  5647  5647 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
07-28 12:05:00.015  5647  5647 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
07-28 12:05:00.015  5647  5647 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
07-28 12:05:00.015  5647  5647 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
07-28 12:05:00.015  5647  5647 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
07-28 12:05:00.015  5647  5647 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-28 12:05:00.015  5647  5647 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-28 12:05:00.015  5647  5647 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-28 12:05:00.015  5647  5647 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-28 12:05:00.015  5647  5647 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:05:00.015  5647  5647 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:05:00.015  5647  5647 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-28 12:05:00.015  5647  5647 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-28 12:05:00.016  5647  5647 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
07-28 12:05:00.016  5647  5647 W System.err: android.os.DeadObjectException
07-28 12:05:00.016  5647  5647 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
07-28 12:05:00.016  5647  5647 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
07-28 12:05:00.016  5647  5647 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
07-28 12:05:00.016  5647  5647 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
07-28 12:05:00.016  5647  5647 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
07-28 12:05:00.016  5647  5647 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
07-28 12:05:00.016  5647  5647 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-28 12:05:00.016  5647  5647 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-28 12:05:00.016  5647  5647 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-28 12:05:00.016  5647  5647 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-28 12:05:00.017  5647  5647 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:05:00.017  5647  5647 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:05:00.017  5647  5647 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-28 12:05:00.017  5647  5647 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-28 12:05:00.017  5647  5647 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
07-28 12:05:00.017  5647  5647 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
07-28 12:05:00.036  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-28 12:05:00.036  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
07-28 12:05:00.036  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-28 12:05:00.037  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
07-28 12:05:00.038  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
07-28 12:05:00.038  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
07-28 12:05:00.039  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
07-28 12:05:00.040  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
07-28 12:05:00.058  6524  6524 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@250c97b3 time:120110
07-28 12:05:00.150  1032  1378 D PowerManagerServiceEx: acquireWakeLockInternal: lock=184320644, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1032
07-28 12:05:00.154   277   277 E lowmemorykiller: Error opening /proc/5671/oom_score_adj; errno=2
07-28 12:05:00.159  1032  1921 W ActivityManager: Exception when unbinding service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service
07-28 12:05:00.159  1032  1921 W ActivityManager: android.os.DeadObjectException
07-28 12:05:00.159  1032  1921 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
07-28 12:05:00.159  1032  1921 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:496)
07-28 12:05:00.159  1032  1921 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleUnbindService(ApplicationThreadNative.java:917)
07-28 12:05:00.159  1032  1921 W ActivityManager: 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1776)
07-28 12:05:00.159  1032  1921 W ActivityManager: 	at com.android.server.am.ActiveServices.unbindServiceLocked(ActiveServices.java:901)
07-28 12:05:00.159  1032  1921 W ActivityManager: 	at com.android.server.am.ActivityManagerService.unbindService(ActivityManagerService.java:15417)
07-28 12:05:00.159  1032  1921 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:963)
07-28 12:05:00.159  1032  1921 W ActivityManager: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2560)
07-28 12:05:00.159  1032  1921 W ActivityManager: 	at com.android.server.am.ActivityManagerServiceEx.onTransact(ActivityManagerServiceEx.java:421)
07-28 12:05:00.159  1032  1921 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:446)
07-28 12:05:00.163  1032  1886 W libprocessgroup: failed to open /acct/uid_1000/pid_5671/cgroup.procs: No such file or directory
07-28 12:05:00.165  6524  6524 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
07-28 12:05:00.165  6524  6524 I chromium: 
07-28 12:05:00.168  5647  5647 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
07-28 12:05:00.168  5647  5647 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
07-28 12:05:00.168  1032  1098 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +735ms (total +814ms)
07-28 12:05:00.169  1032  1098 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{26d2bcd5 u0 com.test.thalitest/.MainActivity t40} time:120220
07-28 12:05:00.189  6524  6524 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
07-28 12:05:00.208  1032  1575 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6636 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
07-28 12:05:00.212  5647  5647 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
07-28 12:05:00.232  4480  6633 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
07-28 12:05:00.237  2614  2614 D [Concierge]Service: onStartCommand(). Type : 9
07-28 12:05:00.266  6524  6621 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
07-28 12:05:00.266  6524  6621 I chromium: 
07-28 12:05:00.275  1032  1032 D PowerManagerServiceEx: releaseWakeLockInternal: lock=184320644 [*alarm*], flags=0x0
07-28 12:05:00.324  6636  6636 D UEI.SmartControl: Quickset Services start...
07-28 12:05:00.325  6636  6636 I UEI.SmartControl: Manufacture = LGE
07-28 12:05:00.326  6636  6636 D UEI.SmartControl: Id = LGNevo
07-28 12:05:00.326  6636  6636 D UEI.SmartControl: File observer start...
07-28 12:05:00.327  6636  6636 E UEI.SmartControl: IR Port is disabled: false
07-28 12:05:00.327  6636  6636 D UEI.SmartControl: Starting file observer...
07-28 12:05:00.327  6636  6636 D UEI.SmartControl: Extracting JNI libs...
07-28 12:05:00.327  6636  6636 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
07-28 12:05:00.352  6524  6661 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435153408
07-28 12:05:00.362  6524  6661 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-28 12:05:00.362  6524  6661 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-28 12:05:00.362  6524  6661 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-28 12:05:00.362  6524  6661 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-28 12:05:00.362  6524  6661 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-28 12:05:00.362  6524  6661 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e305e07 added. We now have 1 listener(s)
07-28 12:05:00.367  1032  1975 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:05:00.370  6524  6661 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
07-28 12:05:00.372  6524  6661 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 12:05:00.373  6524  6661 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:05:00.374  6524  6661 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:05:00.381  6524  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-28 12:05:00.381  6524  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-28 12:05:00.381  6524  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-28 12:05:00.381  6524  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
07-28 12:05:00.381  6524  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-28 12:05:00.381  6524  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-28 12:05:00.381  6524  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
07-28 12:05:00.381  6524  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
07-28 12:05:00.381  6524  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
07-28 12:05:00.381  6524  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-28 12:05:00.381  6524  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-28 12:05:00.381  6524  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-28 12:05:00.381  6524  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-28 12:05:00.381  6524  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-28 12:05:00.381  6524  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3daec6d2 added. We now have 1 listener(s)
07-28 12:05:00.381  6524  6661 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:05:00.386  6636  6636 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
07-28 12:05:00.386  6636  6636 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
07-28 12:05:00.386  1032  1544 D WifiService: New client listening to asynchronous messages
07-28 12:05:00.386  6636  6636 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
07-28 12:05:00.389  6524  6661 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-28 12:05:00.389  6524  6661 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-28 12:05:00.391  6524  6661 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-28 12:05:00.391  6524  6661 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
07-28 12:05:00.394  6524  6661 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:05:00.394  1032  2037 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:05:00.395  6524  6661 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
07-28 12:05:00.405  6524  6661 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
07-28 12:05:00.406  6524  6661 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:05:00.406  6524  6661 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:05:00.406  6524  6661 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:00.406  6524  6661 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:05:00.406  6524  6661 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:05:00.406  6524  6661 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:05:00.406  6524  6661 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:05:00.406  6524  6661 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:05:00.406  6524  6661 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,07-28 12:05:00.406  6524  6661 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:05:00.407  6524  6661 I io.jxcore.node.LifeCycleMonitor: start: OK
07-28 12:05:00.408  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:00.410  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:00.410  6636  6636 I UEI.SmartControl: --- Selecting new region: 6
07-28 12:05:00.412  6636  6636 I UEI.SmartControl: Model = LG-D855
07-28 12:05:00.412  6636  6636 D UEI.SmartControl: QS Service created
07-28 12:05:00.424  6636  6636 I UEI.SmartControl: Service initServices...
,07-28 12:05:00.426  6636  6636 D UEI.SmartControl: QS start get config
07-28 12:05:00.444  6524  6524 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-28 12:05:00.455  6636  6636 D UEI.SmartControl: Loading JNI Libs...
07-28 12:05:00.678  6636  6636 I UEI.SmartControl: Supports setup maps: true
,07-28 12:05:00.681  6636  6636 D UEI.SmartControl: QS start statue = true Error code = 0
07-28 12:05:00.681  6636  6636 I UEI.SmartControl: QS version = v2.7.10.1_RC1
07-28 12:05:00.681  6636  6636 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
07-28 12:05:00.682  6636  6636 I UEI.SmartControl: ### init IR Blaster...
07-28 12:05:00.686   345   359 E GBMv2   : DFP En is all cleared set to be enabled
07-28 12:05:00.686   345   359 E GBMv2   : Set value is all cleared set the max
07-28 12:05:00.686   345   359 I GBMv2   : DFP Enabled. Ignore VFP set
07-28 12:05:00.687  6636  6636 D serial_port: Configuring serial port
07-28 12:05:00.691  6636  6636 E UEI.SmartControl: UEIBLaster setting for 616
07-28 12:05:00.691  6636  6636 I UEI.SmartControl: Setting serial record hearder size = 2
07-28 12:05:00.692  6636  6636 I UEI.SmartControl: configuring settings for MAXQ616
07-28 12:05:00.692  6636  6636 I UEI.SmartControl: Get version...
,07-28 12:05:00.711  6636  6668 D UEI.SmartControl: serial port data available: 21
,07-28 12:05:00.739  6636  6636 D UEI.SmartControl: MAXQ616 A2-X4 software.
07-28 12:05:00.740  6636  6636 I UEI.SmartControl: IR Blaster version: 256702256704300002
07-28 12:05:00.740  6636  6636 I UEI.SmartControl: QS saving settings...
,07-28 12:05:00.743  6636  6636 D UEI.SmartControl: IR Blaster version: 25672567
07-28 12:05:00.761  6636  6668 D UEI.SmartControl: serial port data available: 4
,07-28 12:05:00.795  6636  6674 I UEI.SmartControl: Device manager: loading config....
07-28 12:05:00.796  6636  6674 D UEI.SmartControl: ----------- loading internal config...
07-28 12:05:00.797  6636  6636 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,07-28 12:05:00.810  6636  6636 E UEI.SmartControl: Services init done
07-28 12:05:00.810  6636  6636 D UEI.SmartControl: QS Service init finished
,07-28 12:05:00.814  6636  6636 D UEI.SmartControl: QS Service version name: 2.1.91
,07-28 12:05:00.814  6636  6636 D UEI.SmartControl: QS Service version code: 201091
07-28 12:05:00.817  6636  6636 D UEI.SmartControl: Service requested: Control
07-28 12:05:00.820  6636  6674 E UEI.SmartControl: Loading SETTINGS...
07-28 12:05:00.822  6636  6636 D UEI.SmartControl: Request IControl service: devices are loaded...
07-28 12:05:00.823  1032  1921 I ActivityManager: Killing 5647:com.lge.qremote/u0a112 (adj 15): empty #17
,07-28 12:05:00.831  6636  6674 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
07-28 12:05:00.855  6636  6673 I UEI.SmartControl: Notify AllClients services are ready: 0
07-28 12:05:00.855  6636  6673 D UEI.SmartControl: -----service ready thread exits
,07-28 12:05:00.900  1032  2051 W libprocessgroup: failed to open /acct/uid_10112/pid_5647/cgroup.procs: No such file or directory
07-28 12:05:00.900  6636  6636 D UEI.SmartControl: Internal service binding...
,07-28 12:05:01.286  6524  6666 W jxcore-log: Initializing JXcore engine
,07-28 12:05:01.286  6524  6666 W jxcore-log: JXcore engine is ready
,07-28 12:05:01.315  6666  6666 W Thread-741: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[6130]" dev="sockfs" ino=6130 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
07-28 12:05:01.315  6666  6666 W Thread-741: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,07-28 12:05:01.315  6666  6666 W Thread-741: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[10325]" dev="sockfs" ino=10325 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,07-28 12:05:01.315  6666  6666 W Thread-741: type=1400 audit(0.0:169): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
07-28 12:05:01.315  6666  6666 W Thread-741: type=1400 audit(0.0:170): avc: denied { ioctl } for path="socket:[31153]" dev="sockfs" ino=31153 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
07-28 12:05:01.335  6524  6666 W jxcore-log: Starting JXcore engine
07-28 12:05:01.411  6524  6666 W jxcore-log: Platform android
07-28 12:05:01.411  6524  6666 W jxcore-log: 
07-28 12:05:01.411  6524  6666 W jxcore-log: Process ARCH arm
07-28 12:05:01.411  6524  6666 W jxcore-log: 
,07-28 12:05:01.579  6524  6666 I jxcore-log: JXcore Cordova bridge is ready!
07-28 12:05:01.579  6524  6666 I jxcore-log: 
07-28 12:05:01.579  6524  6666 W jxcore-log: JXcore engine is started
,07-28 12:05:01.589  6524  6661 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
07-28 12:05:01.595  6524  6524 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-28 12:05:03.423  6474  6474 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,07-28 12:05:03.430  1032  2013 I ActivityManager: Killing 5196:com.android.calendar/u0a13 (adj 15): empty #17
07-28 12:05:03.501  1032  1575 W libprocessgroup: failed to open /acct/uid_10013/pid_5196/cgroup.procs: No such file or directory
,07-28 12:05:04.407  6474  6522 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-28 12:05:05.796  6636  6675 D UEI.SmartControl: Internal timer expired: 1
,07-28 12:05:05.796  6636  6675 D UEI.SmartControl: unbind internal service
,07-28 12:05:05.805  6636  6636 D UEI.SmartControl: Service.onUnbind: IControl
07-28 12:05:05.806  6636  6636 D UEI.SmartControl: Service.onDestroy
07-28 12:05:05.806  6636  6636 D UEI.SmartControl: Lock is in USE false
07-28 12:05:05.806  6636  6636 D UEI.SmartControl: unbind internal service
07-28 12:05:05.808  6636  6672 D serial_port: close(fd = 25)
07-28 12:05:05.811  6636  6672 I UEI.SmartControl: Serial port is closed.
,07-28 12:05:05.814  6636  6636 I UEI.SmartControl: Serial port is closed.
07-28 12:05:05.814  6636  6636 I UEI.SmartControl: Serial port is closed.
07-28 12:05:05.815  6636  6636 D UEI.SmartControl: Blaster closed
07-28 12:05:05.815  6636  6636 D UEI.SmartControl: Shut down QS...
07-28 12:05:05.815  6636  6636 D UEI.SmartControl: Stopping QS lib
07-28 12:05:05.815  6636  6636 D UEI.SmartControl: QS lib stop result = true
07-28 12:05:05.815  6636  6636 D UEI.SmartControl: Stopped QS lib
07-28 12:05:05.816  6636  6636 D UEI.SmartControl: Stopped file observer...
07-28 12:05:05.816  6636  6636 D UEI.SmartControl: QS shutdown complete
07-28 12:05:06.971  1816  6380 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,07-28 12:05:06.976   324  6698 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,07-28 12:05:06.976   324  6698 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,07-28 12:05:06.976   324  6698 D libc-netbsd: res_queryN name = android.clients.google.com succeed
07-28 12:05:07.219  1816  1816 I ConfigFetchService: fetch service done; releasing wakelock
,07-28 12:05:07.227  1816  1816 I ConfigFetchService: stopping self
07-28 12:05:07.236  2126  2126 I ConfigService: onDestroy
,07-28 12:05:11.846  6524  6666 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-28 12:05:11.846  6524  6666 I jxcore-log: 
,07-28 12:05:11.849  6524  6666 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-28 12:05:11.849  6524  6666 I jxcore-log: 
,07-28 12:05:11.854  6524  6666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:05:11.854  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:05:11.854  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:11.854  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:05:11.854  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:05:11.854  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:05:11.854  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:05:11.854  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:05:11.857  6524  6666 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-28 12:05:11.860  6524  6666 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-28 12:05:11.860  6524  6666 I jxcore-log: 
,07-28 12:05:11.862  6524  6666 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-28 12:05:11.862  6524  6666 I jxcore-log: 
,07-28 12:05:12.116  1032  1092 I ActivityManager: Waited long enough for: ServiceRecord{15b9fb94 u0 com.google.android.gms/.wearable.service.WearableService}
,07-28 12:05:12.210  6524  6666 D ExecuteNativeTests: Running unit tests
,07-28 12:05:12.284  6524  6666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:05:12.284  6524  6666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b275159 added. We now have 2 listener(s)
,07-28 12:05:12.285  1032  1575 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:05:12.286  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 12:05:12.286  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:05:12.286  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:05:12.287  6524  6666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:05:12.287  6524  6666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e5cf11e added. We now have 2 listener(s)
07-28 12:05:12.287  6524  6666 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:05:12.287  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-28 12:05:12.288  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:05:12.291  6524  6666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:05:12.291  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:05:12.291  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:12.291  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:05:12.291  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:05:12.291  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:05:12.291  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:05:12.291  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:05:12.292  6524  6666 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:05:12.292  6524  6666 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:05:12.293  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:12.294  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:12.296  6524  6666 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,07-28 12:05:12.296  6524  6666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-28 12:05:12.296  6524  6666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-28 12:05:12.297  6524  6666 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
07-28 12:05:12.298  6524  6666 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-28 12:05:12.298  6524  6666 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-28 12:05:12.298  6524  6666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-28 12:05:12.298  6524  6666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-28 12:05:12.299  6524  6666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:05:12.300  6524  6666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:12.300  6524  6666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:05:12.300  6524  6666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:12.300  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.300  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:05:12.300  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:05:12.300  6524  6666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b275159 removed from the list
07-28 12:05:12.300  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.301  6524  6666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e5cf11e removed from the list
07-28 12:05:12.301  6524  6666 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:05:12.301  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.301  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.301  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.301  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:12.302  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:12.302  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.302  6524  6666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e5cf11e not in the list
07-28 12:05:12.303  6524  6666 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
07-28 12:05:12.303  6524  6666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:05:12.303  6524  6666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity:, NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:12.303  6524  6666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:05:12.303  6524  6666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:12.303  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.303  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.304  6524  6666 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b275159 not in the list
07-28 12:05:12.304  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.304  6524  6666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e5cf11e not in the list
07-28 12:05:12.304  6524  6666 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:05:12.304  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.304  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.304  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
07-28 12:05:12.304  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.306  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:12.306  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:12.306  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.306  6524  6666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e5cf11e not in the list
,07-28 12:05:12.310  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-28 12:05:12.310  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-28 12:05:12.310  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-28 12:05:12.310  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-28 12:05:12.310  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-28 12:05:12.310  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-28 12:05:12.310  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-28 12:05:12.310  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-28 12:05:12.310  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-28 12:05:12.311  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-28 12:05:12.311  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-28 12:05:12.311  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-28 12:05:12.311  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-28 12:05:12.311  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-28 12:05:12.311  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-28 12:05:12.311  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-28 12:05:12.311  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-28 12:05:12.311  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-28 12:05:12.311  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-28 12:05:12.311  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-28 12:05:12.311  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-28 12:05:12.311  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-28 12:05:12.311  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-28 12:05:12.311  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-28 12:05:12.311  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-28 12:05:12.311  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-28 12:05:12.311  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 3,5:2510:2510:2510:2510:2510]
07-28 12:05:12.311  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-28 12:05:12.311  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-28 12:05:12.311  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-28 12:05:12.311  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-28 12:05:12.311  6524  6666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:05:12.311  6524  6666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:12.311  6524  6666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:05:12.311  6524  6666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:12.311  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.311  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:05:12.311  6524  6666 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b275159 not in the list
07-28 12:05:12.311  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.311  6524  6666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e5cf11e not in the list
07-28 12:05:12.311  6524  6666 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:05:12.311  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.311  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.311  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 12:05:12.312  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.313  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:12.313  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:12.313  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.313  6524  6666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e5cf11e not in the list
07-28 12:05:12.313  6524  6666 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-28 12:05:12.315  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
07-28 12:05:12.316  6524  6666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:05:12.316  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:05:12.316  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:12.316  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:05:12.316  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:05:12.316  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:05:12.316  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:05:12.316  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:05:12.317  6524  6666 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
07-28 12:05:12.317  6524  6666 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:05:12.319  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:12.319  6524  6666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:05:12.319  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 12:05:12.319  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:05:12.319  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
07-28 12:05:12.321  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:05:12.322  6524  6666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-28 12:05:12.323  1032  1921 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:05:12.326  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-28 12:05:12.329  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-28 12:05:12.331  6524  6666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
07-28 12:05:12.331  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-28 12:05:12.332  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-28 12:05:12.334  6524  6666 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-28 12:05:12.334  6524  6666 I io.jxcore.node.ConnectionHelper: start: OK
07-28 12:05:12.336  6524  6666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:05:12.336  6524  6666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:12.336  6524  6666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:05:12.336  6524  6666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:12.336  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.336  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:05:12.336  6524  6666 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b275159 not in the list
07-28 12:05:12.336  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.336  6524  6666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e5cf11e not in the list
07-28 12:05:12.336  6524  6666 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:05:12.336  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.336  6524  6666 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-28 12:05:12.337  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:05:12.339  6524  6666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:05:12.339  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:05:12.339  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:12.339  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:05:12.339  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:05:12.339  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:05:12.339  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:05:12.339  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:05:12.340  6524  6666 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:05:12.340  6524  6666 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:05:12.341  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:12.342  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:12.342  6524  6666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:05:12.342  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 12:05:12.342  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28, 12:05:12.342  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-28 12:05:12.345  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-28 12:05:12.345  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:05:12.346  6524  6666 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-28 12:05:12.346  6524  6666 I io.jxcore.node.ConnectionHelper: start: OK
07-28 12:05:12.348  6524  6666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:05:12.348  6524  6666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:12.348  6524  6666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:05:12.348  6524  6666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:12.348  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.348  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:05:12.348  6524  6666 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b275159 not in the list
07-28 12:05:12.348  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.348  6524  6666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e5cf11e not in the list
07-28 12:05:12.348  6524  6666 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:05:12.348  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.348  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.348  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.349  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:12.349  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:12.350  6524  6666 D BluetoothLeScanner: could not find callback wrapper
07-28 12:05:12.350  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:05:12.350  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.350  6524  6666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e5cf11e not in the list
07-28 12:05:12.350  6524  6666 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-28 12:05:12.351  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:05:12.353  6524  6666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:05:12.353  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:05:12.353  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:12.353  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:05:12.353  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:05:12.353  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:05:12.353  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:05:12.353  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:05:12.354  6524  6666 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:05:12.354  6524  6666 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:05:12.354  6524  6666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:05:12.354  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 12:05:12.354  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:05:12.354  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-28 12:05:12.356  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:12.358  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:12.359  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-28 12:05:12.359  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:05:12.360  6524  6666 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-28 12:05:12.360  6524  6666 I io.jxcore.node.ConnectionHelper: start: OK
07-28 12:05:12.360  6524  6666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:05:12.360  6524  6666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:12.360  6524  6666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:05:12.361  6524  6666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:05:12.361  6524  6666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:12.361  6524  6666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:05:12.361  6524  6666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:12.361  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.361  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:05:12.361  6524  6666 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b275159 not in the list
07-28 12:05:12.361  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.361  6524  6666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e5cf11e not in the list
07-28 12:05:12.361  6524  6666 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:05:12.361  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.361  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.361  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.362  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:12.362  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:12.362  6524  6666 D BluetoothLeScanner: could not find callback wrapper
07-28 12:05:12.362  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:05:12.362  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.362  6524  6666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e5cf11e not in the list
07-28 12:05:12.363  6524  6666 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
07-28 12:05:12.363  6524  6666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:05:12.363  6524  6666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:12.363  6524  6666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:05:12.363  6524  6666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:12.363  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.363  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.363  6524  6666 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b275159 not in the list
07-28 12:05:12.363  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.363  6524  6666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e5cf11e not in the list
07-28 12:05:12.363  6524  6666 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:05:12.363  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.363  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.364  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.364  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.364  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:12.364  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:12.365  6524  6666 D BluetoothLeScanner: could not find callback wrapper
07-28 12:05:12.365  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:05:12.365  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.365  6524  6666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e5cf11e not in the list
07-28 12:05:12.365  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-28 12:05:12.365  6524  6666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:05:12.365  6524  6666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:12.365  6524  6666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:05:12.366  6524  6666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:12.366  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.366  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.366  6524  6666 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b275159 not in the list
07-28 12:05:12.366  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.366  6524  6666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e5cf11e not in the list
07-28 12:05:12.366  6524  6666 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:05:12.366  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.366  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.366  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.366  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.367  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
07-28 12:05:12.367  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:12.367  6524  6666 D BluetoothLeScanner: could not find callback wrapper
07-28 12:05:12.367  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:05:12.367  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.367  6524  6666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e5cf11e not in the list
07-28 12:05:12.367  6524  6666 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
07-28 12:05:12.368  6524  6666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:05:12.368  6524  6666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:12.368  6524  6666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:05:12.368  6524  6666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:12.368  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.368  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.368  6524  6666 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b275159 not in the list
07-28 12:05:12.368  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.368  6524  6666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e5cf11e not in the list
07-28 12:05:12.368  6524  6666 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:05:12.368  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.368  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.368  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.368  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.369  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:12.369  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:12.369  6524  6666 D BluetoothLeScanner: could not find callback wrapper
07-28 12:05:12.369  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:05:12.369  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.369  6524  6666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e5cf11e not in the list
07-28 12:05:12.370  6524  6666 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
07-28 12:05:12.370  6524  6666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:05:12.370  6524  6666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:12.370  6524  6666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:05:12.370  6524  6666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:12.370  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.370  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.370  6524  6666 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b275159 not in the list
07-28 12:05:12.370  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.370  6524  6666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e5cf11e not in the list
07-28 12:05:12.371  6524  6666 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:05:12.371  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.371  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.371  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.371  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.371  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:12.371  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:12.372  6524  6666 D BluetoothLeScanner: could not find callback wrapper
07-28 12:05:12.372  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:05:12.372  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.372  6524  6666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e5cf11e not in the list
07-28 12:05:12.372  6524  6666 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-28 12:05:12.373  6524  6666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-28 12:05:12.373  6524  6666 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-28 12:05:12.373  6524  6666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-28 12:05:12.373  6524  6666 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-28 12:05:12.373  6524  6666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-28 12:05:12.373  6524  6666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:05:12.373  6524  6666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:12.373  6524  6666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:05:12.374  6524  6666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:12.374  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.374  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.374  6524  6666 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b275159 not in the list
07-28 12:05:12.374  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.374  6524  6666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e5cf11e not in the list
07-28 12:05:12.374  6524  6666 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:05:12.374  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.374  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.374  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.374  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.375  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:12.375  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:12.375  6524  6666 D BluetoothLeScanner: could not find callback wrapper
07-28 12:05:12.375  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:05:12.375  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.375  6524  6666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e5cf11e not in the list
07-28 12:05:12.376  6524  6666 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-28 12:05:12.376  6524  6666 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
07-28 12:05:12.376  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-28 12:05:12.379  6524  6666 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-28 12:05:12.380  6524  6666 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
07-28 12:05:12.380  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-28 12:05:12.380  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-28 12:05:12.380  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-28 12:05:12.380  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-28 12:05:12.380  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-28 12:05:12.380  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-28 12:05:12.380  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-28 12:05:12.380  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-28 12:05:12.380  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-28 12:05:12.380  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-28 12:05:12.380  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-28 12:05:12.381  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-28 12:05:12.381  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-28 12:05:12.381  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-28 12:05:12.381  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-28 12:05:12.381  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-28 12:05:12.381  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-28 12:05:12.381  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-28 12:05:12.381  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-28 12:05:12.381  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-28 12:05:12.381  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-28 12:05:12.381  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-28 12:05:12.381  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-28 12:05:12.382  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-28 12:05:12.382  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-28 12:05:12.382  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-28 12:05:12.382  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-28 12:05:12.382  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-28 12:05:12.382  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-28 12:05:12.382  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-28 12:05:12.382  6524  6666 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
07-28 12:05:12.382  6524  6666 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-28 12:05:12.382  6524  6666 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
07-28 12:05:12.382  6524  6666 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-28 12:05:12.382  6524  6666 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-28 12:05:12.382  6524  6666 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
07-28 12:05:12.382  6524  6666 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-28 12:05:12.382  6524  6666 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-28 12:05:12.382  6524  6666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
07-28 12:05:12.384  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
07-28 12:05:12.385  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
07-28 12:05:12.385  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
07-28 12:05:12.385  6524  6666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
07-28 12:05:12.385  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
07-28 12:05:12.385  6524  6666 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
07-28 12:05:12.386  6524  6666 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-28 12:05:12.386  6524  6666 E io.jxcore.node.ConnectionHelper: connect: Callback is null
07-28 12:05:12.386  6524  6666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:05:12.386  6524  6666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:12.386  6524  6666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:05:12.387  6524  6666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:12.387  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.387  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.387  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
07-28 12:05:12.388  6524  6666 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b275159 not in the list
07-28 12:05:12.388  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.388  6524  6666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e5cf11e not in the list
07-28 12:05:12.388  6524  6666 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:05:12.388  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.388  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.388  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.388  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.389  6524  6699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 805)
07-28 12:05:12.392  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:12.392  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:12.393  6524  6666 D BluetoothLeScanner: could not find callback wrapper
07-28 12:05:12.393  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:05:12.393  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.393  6524  6666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e5cf11e not in the list
07-28 12:05:12.393  6524  6666 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
07-28 12:05:12.394  6524  6666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:05:12.394  6524  6666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:12.394  6524  6666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:05:12.394  6524  6666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:12.394  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.394  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.394  6524  6666 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b275159 not in the list
07-28 12:05:12.394  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.394  6524  6666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e5cf11e not in the list
07-28 12:05:12.394  6524  6666 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:05:12.394  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.394  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.394  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.394  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.395  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:12.395  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:12.395  6524  6666 D BluetoothLeScanner: could not find callback wrapper
07-28 12:05:12.395  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:05:12.395  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.395  6524  6666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e5cf11e not in the list
07-28 12:05:12.396  6524  6666 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
07-28 12:05:12.396  6524  6666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:05:12.397  6524  6666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:12.397  6524  6666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:05:12.397  6524  6666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:12.397  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.397  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:05:12.397  6524  6666 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b275159 not in the list
07-28 12:05:12.397  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.397  6524  6666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e5cf11e not in the list
07-28 12:05:12.397  6524  6666 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:05:12.397  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.397  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.397  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.397  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.398  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:12.398  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:12.399  6524  6666 D BluetoothLeScanner: could not find callback wrapper
07-28 12:05:12.399  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:05:12.399  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.399  6524  6666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e5cf11e not in the list
07-28 12:05:12.399  6524  6666 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
07-28 12:05:12.399  6524  6666 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
07-28 12:05:12.399  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-28 12:05:12.400  6524  6666 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
07-28 12:05:12.400  6524  6666 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-28 12:05:12.400  6524  6666 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
07-28 12:05:12.400  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-28 12:05:12.400  6524  6666 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
07-28 12:05:12.400  6524  6666 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-28 12:05:12.400  6524  6666 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
07-28 12:05:12.400  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-28 12:05:12.400  6524  6666 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
07-28 12:05:12.400  6524  6666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:05:12.400  6524  6666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:12.400  6524  6666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:05:12.401  6524  6666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:12.401  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.401  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.401  6524  6666 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b275159 not in the list
07-28 12:05:12.401  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.401  6524  6666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e5cf11e not in the list
07-28 12:05:12.401  6524  6666 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:05:12.401  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.401  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.401  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.401  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.402  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:12.402  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:12.403  6524  6666 D BluetoothLeScanner: could not find callback wrapper
07-28 12:05:12.403  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:05:12.403  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.403  6524  6666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e5cf11e not in the list
07-28 12:05:12.403  6524  6666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:12.403  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.403  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.403  6524  6666 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b275159 not in the list
07-28 12:05:12.403  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.403  6524  6666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e5cf11e not in the list
07-28 12:05:12.403  6524  6666 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:05:12.403  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.403  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.403  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.403  6524  6666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e5cf11e not in the list
07-28 12:05:12.403  6524  6666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:12.403  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.403  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.403  6524  6666 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b275159 not in the list
07-28 12:05:12.403  6524  6666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:05:12.403  6524  6666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:12.403  6524  6666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:05:12.404  6524  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 805
07-28 12:05:12.404  6524  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 805)
07-28 12:05:12.404  6524  6666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:12.404  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.404  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.404  6524  6666 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b275159 not in the list
07-28 12:05:12.404  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.404  6524  6666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e5cf11e not in the list
07-28 12:05:12.404  6524  6666 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:05:12.404  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.404  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.404  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.404  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.405  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:12.405  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:12.405  6524  6666 D BluetoothLeScanner: could not find callback wrapper
07-28 12:05:12.405  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:05:12.405  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.405  6524  6666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e5cf11e not in the list
07-28 12:05:12.405  6524  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 805)
07-28 12:05:12.406  6524  6666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-28 12:05:12.407  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:05:12.408  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
07-28 12:05:12.409  6524  6666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-28 12:05:12.409  6524  6666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-28 12:05:12.409  6524  6524 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-28 12:05:12.410  6524  6666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-28 12:05:12.410  6524  6666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-28 12:05:12.411  6524  6666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:12.411  6524  6666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-28 12:05:12.411  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-28 12:05:12.411  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-28 12:05:12.411  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.411  6524  6666 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-28 12:05:12.411  6524  6524 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-28 12:05:12.411  6524  6666 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b275159 not in the list
07-28 12:05:12.411  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.411  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-28 12:05:12.411  6524  6666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-28 12:05:12.411  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-28 12:05:12.412  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-28 12:05:12.412  6524  6666 D BluetoothLeScanner: could not find callback wrapper
07-28 12:05:12.412  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:05:12.412  6524  6666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-28 12:05:12.412  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.412  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.413  6524  6666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-28 12:05:12.413  6524  6524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-28 12:05:12.413  6524  6524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-28 12:05:12.413  6524  6524 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-28 12:05:12.414  6524  6666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e5cf11e not in the list
07-28 12:05:12.414  6524  6666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:05:12.414  6524  6666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:12.414  6524  6666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:05:12.414  6524  6666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:12.414  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.414  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.414  6524  6666 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b275159 not in the list
07-28 12:05:12.414  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.414  6524  6666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e5cf11e not in the list
07-28 12:05:12.414  6524  6666 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:05:12.414  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.414  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.414  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.414  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.415  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:12.415  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:12.415  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.415  6524  6666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e5cf11e not in the list
07-28 12:05:12.416  6524  6666 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
07-28 12:05:12.416  6524  6666 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-28 12:05:12.416  6524  6666 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-28 12:05:12.421  6524  6666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-28 12:05:12.421  6524  6666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:05:12.421  6524  6666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:12.421  6524  6666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:05:12.422  6524  6666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:12.422  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.422  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.422  6524  6666 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b275159 not in the list
07-28 12:05:12.422  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.422  6524  6666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e5cf11e not in the list
07-28 12:05:12.422  6524  6666 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:05:12.422  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.422  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.422  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.422  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.423  6524  6701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-28 12:05:12.423  6524  6701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-28 12:05:12.424  6524  6524 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-28 12:05:12.426  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:12.426  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:12.426  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.426  6524  6666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e5cf11e not in the list
07-28 12:05:12.427  1032  1047 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:05:12.427  1032  1939 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:05:12.428  1032  1886 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:05:12.428  6524  6666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:05:12.428  6524  6666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:12.428  6524  6666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:05:12.429  6524  6666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:12.429  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.429  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.429  6524  6666 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b275159 not in the list
07-28 12:05:12.429  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.429  6524  6666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e5cf11e not in the list
07-28 12:05:12.429  6524  6666 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:05:12.429  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.429  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.429  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.429  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.430  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:12.430  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:12.430  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.430  6524  6666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e5cf11e not in the list
07-28 12:05:12.437  6524  6666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:05:12.437  6524  6666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:12.437  6524  6666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:05:12.437  6524  6666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:12.437  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.437  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.437  6524  6666 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b275159 not in the list
07-28 12:05:12.437  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.437  6524  6666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e5cf11e not in the list
07-28 12:05:12.437  6524  6666 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:05:12.437  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.437  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.437  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.437  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.438  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:12.438  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:12.438  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.438  6524  6666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e5cf11e not in the list
07-28 12:05:12.445  6524  6666 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
07-28 12:05:12.446  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-28 12:05:12.447  6524  6666 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
07-28 12:05:12.447  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-28 12:05:12.447  6524  6666 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
07-28 12:05:12.447  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-28 12:05:12.449  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-28 12:05:12.449  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
07-28 12:05:12.450  6524  6666 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,07-28 12:05:12.450  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-28 12:05:12.451  6524  6666 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
07-28 12:05:12.451  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-28 12:05:12.451  6524  6666 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
07-28 12:05:12.451  6524  6666 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
07-28 12:05:12.452  6524  6666 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
07-28 12:05:12.452  6524  6666 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
07-28 12:05:12.453  6524  6666 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
07-28 12:05:12.453  6524  6666 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
07-28 12:05:12.453  6524  6666 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
07-28 12:05:12.453  6524  6666 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
07-28 12:05:12.454  6524  6666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:05:12.454  6524  6666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@357fadf7 added. We now have 2 listener(s)
07-28 12:05:12.454  6524  6666 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:05:12.456  6524  6666 D BluetoothAdapter: enable(): BT is already enabled..!
07-28 12:05:12.457  1032  1885 D WifiServiceImplEx: setWifiEnabled: true pid=6524, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-28 12:05:12.457  1032  1885 D WifiService: setWifiEnabled: true pid=6524, uid=10118
07-28 12:05:12.457  1032  1885 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-28 12:05:12.459  6524  6666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:05:12.459  6524  6666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@32688464 added. We now have 3 listener(s)
07-28 12:05:12.459  6524  6666 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:05:12.466  6524  6666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:05:12.466  6524  6666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@182f06cd added. We now have 4 listener(s)
07-28 12:05:12.466  6524  6666 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:05:12.468  6524  6666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:05:12.468  6524  6666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2fa68b82 added. We now have 5 listener(s)
07-28 12:05:12.468  6524  6666 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:05:12.470  1032  1885 D WifiServiceImplEx: setWifiEnabled: false pid=6524, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-28 12:05:12.470  1032  1885 D WifiService: setWifiEnabled: false pid=6524, uid=10118
07-28 12:05:12.470  1032  1885 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-28 12:05:12.481  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-28 12:05:12.482  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-28 12:05:12.482  1032  1032 D Ulp_jni : JNI:system_update. Event-4
07-28 12:05:12.483  1032  1538 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
07-28 12:05:12.484  1032  1538 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
07-28 12:05:12.484  1032  1538 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
07-28 12:05:12.484  1032  2026 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:05:12.484  1032  1538 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
07-28 12:05:12.485  1032  1538 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
07-28 12:05:12.485  1032  2026 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2973cb5a mBinding = false
07-28 12:05:12.485  1032  1538 E WifiStateMachine: WifiStateMachine: Leaving Connected state
07-28 12:05:12.485  1032  1538 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-28 12:05:12.485  1032  1538 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-28 12:05:12.486  1032  1538 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-28 12:05:12.486  1032  1538 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-28 12:05:12.493  1032  1538 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-28 12:05:12.493  1032  1537 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:12.493  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:12.494  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-28 12:05:12.494  2698  2698 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,07-28 12:05:12.496  1032  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-28 12:05:12.496  1032  1538 D WifiNative-wlan0: doBoolean: SET ps 1
07-28 12:05:12.497  1032  1538 D WifiNative-wlan0: SET ps 1: returned true
07-28 12:05:12.498  1032  2821 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:12.499   324   891 D CommandListener: Clearing all IP addresses on wlan0
,07-28 12:05:12.511  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-28 12:05:12.511  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-28 12:05:12.512  1032  1032 D Ulp_jni : JNI:system_update. Event-4
07-28 12:05:12.513  1032  1097 D BluetoothManagerService: Message: 2
07-28 12:05:12.523  1032  1097 D BluetoothManagerService: Sending off request.
07-28 12:05:12.523  3885  3906 D LGBluetoothServiceAdapter: [BTUI] Precleanup
07-28 12:05:12.524  3885  3963 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
07-28 12:05:12.525  3885  3963 D BluetoothAdapterProperties: Setting state to 13
07-28 12:05:12.525  3885  3963 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-28 12:05:12.525  3885  3963 D BluetoothAdapterProperties: onBluetoothDisable()
07-28 12:05:12.525  3885  3963 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
07-28 12:05:12.526  1032  1097 D BluetoothManagerService: Message: 60
07-28 12:05:12.526  1032  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
07-28 12:05:12.530  1032  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,07-28 12:05:12.530  1032  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
07-28 12:05:12.533  1032  1097 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
07-28 12:05:12.540  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-28 12:05:12.541  3885  3885 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:12.541  3885  3885 D BluetoothMapService: STATE_TURNING_OFF
07-28 12:05:12.541  3885  3885 V BluetoothMapService: Handler(): got msg=4
07-28 12:05:12.541  3885  3885 D BluetoothMapService: MAP Service closeService in
07-28 12:05:12.541  3885  3885 D BluetoothMapMasInstance: MAP Service shutdown
07-28 12:05:12.542  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:05:12.549  3885  4198 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
07-28 12:05:12.549  3885  4198 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 12:05:12.549  3885  4198 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
07-28 12:05:12.549  3885  4198 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
07-28 12:05:12.549  3885  4198 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
07-28 12:05:12.549  3885  4198 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
07-28 12:05:12.549  3885  4198 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
07-28 12:05:12.549  3885  4198 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
07-28 12:05:12.550  3885  3885 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-28 12:05:12.550  3885  3885 V BluetoothMapService: MAP Service closeService out
07-28 12:05:12.552  6524  6524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:05:12.553  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:05:12.553  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:05:12.553  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:12.553  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:05:12.553  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:05:12.553  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:05:12.553  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:05:12.553  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:05:12.554  6524  6524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:05:12.554  6524  6524 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:05:12.555  3885  3885 V BtOppService: Receiver DISABLED_ACTION 
07-28 12:05:12.556  3885  3885 I BtOppRfcommListener: stopping Accept Thread
07-28 12:05:12.556  3885  3885 V BtOppRfcommListener: close mBtServerSocket
,07-28 12:05:12.556  3885  4223 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 12:05:12.556  3885  4223 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-28 12:05:12.556  3885  3885 V BtOppRfcommListener: waiting for thread to terminate
07-28 12:05:12.557  3885  3885 V BtOppRfcommListener: done waiting for thread to terminate
07-28 12:05:12.580  1032  1545 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
07-28 12:05:12.580  1032  1545 D DSQN    : disableDataServiceNotify
07-28 12:05:12.580  1032  1545 D DSQN    : stop dsqn bin
,07-28 12:05:12.587  1032  1545 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
07-28 12:05:12.587  1032  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:05:12.587  1032  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-28 12:05:12.587  1032  1545 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:05:12.588  1032  1545 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
07-28 12:05:12.588  1602  2072 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
07-28 12:05:12.588  1032  2819 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:12.588  1032  2819 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:12.588  1032  2819 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
07-28 12:05:12.588  1032  1545 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
,07-28 12:05:12.588  1032  1545 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
07-28 12:05:12.589  1032  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-28 12:05:12.589  6524  6699 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
07-28 12:05:12.590  6524  6699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 805)
07-28 12:05:12.591  1032  1092 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6720 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
07-28 12:05:12.592  1032  1032 D WifiHS20: hidePasspointNotification off =false
07-28 12:05:12.593  1940  1940 V WfdStateTracker: handleWifiStateChangedEvent: 0
07-28 12:05:12.594  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:12.594  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:12.594  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-28 12:05:12.596  1032  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-28 12:05:12.596  1032  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-28 12:05:12.597  1032  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:05:12.597  1032  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:05:12.597  1032  1536 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
,07-28 12:05:12.597  1032  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:05:12.597  1032  1538 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
07-28 12:05:12.598  1032  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:05:12.598  1032  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,07-28 12:05:12.598  3885  3885 V BtOppService: onDestroy
07-28 12:05:12.598  1032  1537 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:12.599  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:12.599  1032  1537 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2f1b9392
07-28 12:05:12.600  1032  1032 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
07-28 12:05:12.600  1032  1032 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-28 12:05:12.600  1032  1032 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-28 12:05:12.600  1032  1032 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-28 12:05:12.602  1032  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:05:12.602  1032  1032 D WifiHS20: hidePasspointNotification off =false
07-28 12:05:12.602  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:12.602  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:05:12.603  1032  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:05:12.603  1032  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:05:12.603  1032  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,07-28 12:05:12.609  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:12.610  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:12.610  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-28 12:05:12.610  1032  1032 D WifiScanningService: SCAN_AVAILABLE : 1
07-28 12:05:12.610  1032  1032 D RttService: SCAN_AVAILABLE : 1
07-28 12:05:12.610  1032  1556 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:12.610  1032  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-28 12:05:12.610  1032  1537 D LGWifiP2pService: P2pDisablingState
07-28 12:05:12.610  1032  1537 D LGWifiP2pService: P2pDisablingState{ when=-12ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:12.610  1032  1545 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:05:12.610  1032  1537 D LGWifiP2pService: p2p socket connection lost
07-28 12:05:12.610  1032  1545 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:05:12.610  1032  1537 D LGWifiP2pService: P2pDisabledState
07-28 12:05:12.611  1032  1545 D NetworkManagementService: Removing idletimer
07-28 12:05:12.611  1032  1545 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:12.611  1032  1545 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
07-28 12:05:12.612  1032  1557 D RttService: EnabledState got{ when=-2ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:12.612  1032  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
07-28 12:05:12.612  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-28 12:05:12.612  2698  2698 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-28 12:05:12.612  1032  1537 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:12.612  1032  1537 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:12.613  1032  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-28 12:05:12.613  1032  1538 D WifiNative-wlan0: doBoolean: SET ps 1
,07-28 12:05:12.613  1032  1538 D WifiNative-wlan0: SET ps 1: returned true
07-28 12:05:12.613   324   891 D CommandListener: Clearing all IP addresses on wlan0
07-28 12:05:12.614  1851  1851 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:05:12.614  1851  1851 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-28 12:05:12.614  1032  1536 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
07-28 12:05:12.615  1032  1032 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
07-28 12:05:12.615  1032  1032 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-28 12:05:12.615  1032  1032 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-28 12:05:12.615  1032  1032 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-28 12:05:12.616  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
07-28 12:05:12.616  1940  1940 D WfdsService: WifiP2pState is changed : false
07-28 12:05:12.616  1940  2302 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
07-28 12:05:12.616  1940  2302 D WfdsService: Set the WFDS Monitor: false
07-28 12:05:12.616  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:05:12.617  1032  1538 D WifiNative-p2p0: doBoolean: TERMINATE
07-28 12:05:12.618  1032  1538 D WifiNative-p2p0: TERMINATE: returned true
07-28 12:05:12.618  1032  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-28 12:05:12.618  1032  1538 E WifiStateMachine: useWiFiOffloading() : false
07-28 12:05:12.618  1032  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-28 12:05:12.618  1032  1032 D WifiHS20: hidePasspointNotification off =false
07-28 12:05:12.619  1940  2302 D WfdsMonitor: WFDS Monitor is stopped
07-28 12:05:12.619  1940  2743 D CtrlSupplicant: Received on exit socket, terminate
07-28 12:05:12.619  1940  2743 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
07-28 12:05:12.619  1940  2302 D WfdsService: STATE : WfdsDisabledState - enter
07-28 12:05:12.619  1940  2743 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
07-28 12:05:12.619  1940  2743 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
07-28 12:05:12.619  1940  2302 W WfdsService: DefaultState - msg [9445378] is not handled
07-28 12:05:12.620  1940  2304 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
07-28 12:05:12.620  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:12.620  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:12.620  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-28 12:05:12.620  1032  1538 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:05:12.620  1032  1538 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:05:12.623  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
07-28 12:05:12.624  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
07-28 12:05:12.624  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 12:,05:12.624  1032  1032 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
07-28 12:05:12.624  6524  6524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:05:12.624  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:05:12.624  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:05:12.624  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:12.624  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:05:12.624  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:05:12.624  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:05:12.624  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:05:12.624  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:05:12.625  6524  6524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:05:12.625  6524  6524 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:05:12.640  6338  6338 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-28 12:05:12.651  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-28 12:05:12.651  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:05:12.652  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:05:12.655  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:12.655  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:05:12.656  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:05:12.674  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-28 12:05:12.675  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:05:12.675  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:05:12.675  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-28 12:05:12.675  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:05:12.676  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:05:12.677  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:05:12.686  1032  1642 I art     : Explicit concurrent mark sweep GC freed 39486(1992KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.472ms total 169.381ms
07-28 12:05:12.688  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:05:12.691  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:05:12.691  6524  6666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:05:12.691  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:05:12.691  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:12.691  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:05:12.691  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:05:12.691  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:05:12.691  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:05:12.691  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:05:12.691  3885  3885 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
07-28 12:05:12.691  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:05:12.691  6524  6666 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:05:12.692  6524  6666 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:05:12.693  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:12.694  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:12.707  6720  6720 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-28 12:05:12.707  6720  6720 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
07-28 12:05:12.707  6720  6720 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-28 12:05:12.708  6720  6720 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
07-28 12:05:12.709  6720  6720 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,07-28 12:05:12.710  6720  6720 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
07-28 12:05:12.711  1032  2821 D DhcpStateMachine: StoppedState
07-28 12:05:12.711  1032  2821 D DhcpStateMachine: StoppedState{ when=-99ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,07-28 12:05:12.729  1032  1092 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6737 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
07-28 12:05:12.729  3885  3966 D BluetoothAdapterProperties: Scan Mode:20
07-28 12:05:12.729  3885  3963 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
07-28 12:05:12.730  3885  4228 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 12:05:12.730  3885  3963 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
07-28 12:05:12.730  3885  4202 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 12:05:12.731  3885  4080 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
07-28 12:05:12.731  3885  4080 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
07-28 12:05:12.731  3885  4080 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-28 12:05:12.731  3885  4080 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-28 12:05:12.731  3885  4080 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-28 12:05:12.731  3885  4080 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-28 12:05:12.731  3885  4080 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:05:12.731  3885  4080 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-28 12:05:12.731  3885  4080 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:05:12.731  3885  4080 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-28 12:05:12.731  3885  4080 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 12:05:12.731  3885  4080 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
07-28 12:05:12.731  3885  4080 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
07-28 12:05:12.731  3885  4080 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
07-28 12:05:12.732  3885  4230 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 12:05:12.734  1032  1538 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
07-28 12:05:12.735  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:12.735  1032  1538 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
07-28 12:05:12.736  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:12.740  2698  2698 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
07-28 12:05:12.740  2698  2698 I wpa_supplicant: monitor socket send errors count : 1
07-28 12:05:12.740  2698  2698 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1940-2\x00 that cannot receive messages
,07-28 12:05:12.742  1032  2741 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
07-28 12:05:12.742  1032  2741 D WifiMonitor: Dropping event because (p2p0) is stopped
07-28 12:05:12.742  1032  1378 V AlarmManager: RTC_WAKEUP set : Alarm{10d5b67 type 0 when 1469700312730 com.android.vending} when 1469700312730
,07-28 12:05:12.780  2698  2698 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-28 12:05:12.781  1032  1097 D Tethering: InitialState.processMessage what=4
,07-28 12:05:12.781  2698  2698 W wpa_supplicant: USIM:  scard_deinit function
07-28 12:05:12.782  1032  2741 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
07-28 12:05:12.782  1032  2741 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-28 12:05:12.782  1032  2741 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-28 12:05:12.782  1032  1097 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
07-28 12:05:12.782  1032  2741 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
07-28 12:05:12.782  1032  2741 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-28 12:05:12.782  1032  2741 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-28 12:05:12.783  1032  1538 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=132821
07-28 12:05:12.783  1032  1538 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=132821
07-28 12:05:12.784  1032  1538 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=132822  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
07-28 12:05:12.784  1032  1538 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=132823  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
07-28 12:05:12.785  1032  1538 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:05:12.786  1032  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:05:12.789  6737  6737 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-28 12:05:12.791  6737  6737 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-28 12:05:12.793  6737  6737 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-28 12:05:12.802  1032  1957 V SIM_STK : Menu title from STK is T-Mobile
,07-28 12:05:12.808  6720  6720 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-28 12:05:12.811  3885  3885 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-28 12:05:12.811  3885  3885 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:12.811  3885  3885 V BluetoothPbapReceiver: ***********state = 13
07-28 12:05:12.812  3885  3885 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
07-28 12:05:12.813  3885  3885 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:12.813  3885  3885 V BluetoothPbapService: state: 13
07-28 12:05:12.813  3885  3885 V BluetoothPbapService: Pbap Service closeService in
07-28 12:05:12.814  2126  2126 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-28 12:05:12.815  3885  3885 V BluetoothPbapService: successfully stopped pbap service
07-28 12:05:12.815  3885  3885 V BluetoothPbapService: Pbap Service closeService out
07-28 12:05:12.815  3885  3885 V BluetoothPbapService: Pbap Service onDestroy
07-28 12:05:12.815  3885  3885 V BluetoothPbapService: Pbap Service closeService in
07-28 12:05:12.815  3885  3885 V BluetoothPbapService: Pbap Service closeService out
07-28 12:05:12.815  3885  3885 D LGBluetoothPbapAdapter: [BTUI] cleanup
,07-28 12:05:12.817  6720  6720 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-28 12:05:12.843  6720  6720 D LgDataFeature: LgDataFeature() Constructor: none
07-28 12:05:12.843  6720  6720 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-28 12:05:12.850  1032  2013 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6758 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
07-28 12:05:12.852  6720  6720 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:05:12.861  1032  1097 D BluetoothManagerService: Message: 20
,07-28 12:05:12.861  1032  1097 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@15e06bb2:true
,07-28 12:05:12.874  1032  1097 D BluetoothManagerService: Message: 30
07-28 12:05:12.878  1032  1097 D BluetoothManagerService: Message: 30
07-28 12:05:12.880  6720  6720 D LocalBluetoothProfileManager: Adding local MAP profile
07-28 12:05:12.883  6720  6720 D BluetoothMap: Create BluetoothMap proxy object
07-28 12:05:12.884  1032  1097 D BluetoothManagerService: Message: 30
,07-28 12:05:12.888  1032  1097 D BluetoothManagerService: Message: 30
07-28 12:05:12.890  2698  2698 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
07-28 12:05:12.890  1032  2741 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
07-28 12:05:12.890  1032  2741 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
07-28 12:05:12.890  1032  2741 D WifiMonitor: Disconnecting from the supplicant, no more events
07-28 12:05:12.890  6720  6720 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
07-28 12:05:12.891  6720  6720 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
07-28 12:05:12.891  1032  1538 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
07-28 12:05:12.901  6720  6720 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,07-28 12:05:12.904  6720  6720 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
07-28 12:05:12.911  6720  6720 D DockEventReceiver: finishStartingService: stopping service
07-28 12:05:12.918  6720  6720 D BluetoothInputDevice: Proxy object connected
,07-28 12:05:12.919  6720  6720 D HidProfile: Bluetooth service connected
07-28 12:05:12.920  6720  6720 D BluetoothPan: BluetoothPAN Proxy object connected
07-28 12:05:12.920  6720  6720 D PanProfile: Bluetooth service connected
07-28 12:05:12.921  6720  6720 D BluetoothMap: Proxy object connected
07-28 12:05:12.921  6720  6720 D MapProfile: Bluetooth service connected
07-28 12:05:12.921  6720  6720 D BluetoothMap: getConnectedDevices()
07-28 12:05:12.922  6720  6720 D BluetoothMap: Bluetooth is Not enabled
07-28 12:05:12.922  6720  6720 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
07-28 12:05:12.950  5820  5820 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,07-28 12:05:12.953  1032  1047 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6782 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
07-28 12:05:12.955  1032  1047 I ActivityManager: Killing 5967:com.android.providers.calendar/u0a14 (adj 15): empty #17
07-28 12:05:13.000  1032  1047 I ActivityManager: Killing 2145:com.lge.music/u0a34 (adj 15): empty #17
,07-28 12:05:13.017   329  2216 V AudioFlinger: 2145 died, releasing its sessions
,07-28 12:05:13.017   329  2216 V AudioFlinger:  pid 1851 @ 0
,07-28 12:05:13.017   329  2216 V AudioFlinger:  pid 3454 @ 1
07-28 12:05:13.017   329  2216 V AudioFlinger:  pid 3454 @ 2
07-28 12:05:13.039  1032  2026 W libprocessgroup: failed to open /acct/uid_10014/pid_5967/cgroup.procs: No such file or directory
,07-28 12:05:13.054  6758  6758 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
07-28 12:05:13.055  6758  6758 W LG Account v2.2: No ProfileInfo entries
,07-28 12:05:13.055  6758  6758 I LG Account v2.2: isEnabled: false
07-28 12:05:13.056  1940  1940 D WfdsService: Supplicant Connection state is changed : false
07-28 12:05:13.056  6758  6758 I Feature : [Lifetracker]ver: 4.21.112(40211120)
07-28 12:05:13.056  1940  2302 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
07-28 12:05:13.056  1940  2302 D WfdsService: Set the WFDS Monitor: false
07-28 12:05:13.056  1940  2302 D WfdsMonitor: WFDS Monitor is stopped
07-28 12:05:13.056  6758  6758 I Feature : [Lifetracker]Country: EU
07-28 12:05:13.056  6758  6758 I Feature : [Lifetracker]Operator: OPEN
07-28 12:05:13.056  1032  1993 W libprocessgroup: failed to open /acct/uid_10034/pid_2145/cgroup.procs: No such file or directory
07-28 12:05:13.056  6758  6758 I Feature : [Lifetracker]Ranking support: false
07-28 12:05:13.057  6758  6758 I Feature : [Lifetracker]Comfort support: false
07-28 12:05:13.057  6758  6758 I Feature : [Lifetracker]Accessory: true
07-28 12:05:13.057  6758  6758 I Feature : [Lifetracker]Health device: true
07-28 12:05:13.057  6758  6758 I Feature : [Lifetracker]Extra Pedometer: false
07-28 12:05:13.057  6758  6758 I Feature : [Lifetracker]Blood glucose device: false
07-28 12:05:13.058  6758  6758 I Feature : [Lifetracker]Device Number: 3
07-28 12:05:13.066  1032  1538 D WifiOffDelayIfNotUsed: stopMonitoring
07-28 12:05:13.067  1032  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-28 12:05:13.067  1032  1538 E WifiStateMachine: useWiFiOffloading() : false
07-28 12:05:13.067  1032  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,07-28 12:05:13.073  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
07-28 12:05:13.074  6782  6782 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-28 12:05:13.074  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
07-28 12:05:13.075  1032  1542 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
07-28 12:05:13.075  1032  1542 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
07-28 12:05:13.076  2455  2455 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:13.077  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:13.078  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:05:13.079  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:13.079  6720  6720 D LGBluetoothAuthorization: [BTUI] cancel All Notification
07-28 12:05:13.084  6720  6720 D BluetoothPermissionRequest: onReceive
,07-28 12:05:13.089  6720  6720 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,07-28 12:05:13.099  6720  6720 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,07-28 12:05:13.101  1032  1957 I ActivityManager: Killing 6384:com.google.android.partnersetup/u0a8 (adj 15): empty #17
07-28 12:05:13.175  3885  3885 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,07-28 12:05:13.175  3885  3885 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
07-28 12:05:13.176  1032  2037 W libprocessgroup: failed to open /acct/uid_10008/pid_6384/cgroup.procs: No such file or directory
07-28 12:05:13.179  3885  3885 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
07-28 12:05:13.186  6782  6782 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
07-28 12:05:13.194  3885  3885 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:13.196  3885  3885 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,07-28 12:05:13.203  3885  3885 V BluetoothFtpService: Ftp Service onStartCommand
07-28 12:05:13.203  3885  3885 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:13.204  3885  3885 V BluetoothFtpService: Ftp Service closeService
07-28 12:05:13.204  3885  3885 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
07-28 12:05:13.206  3885  3885 V BluetoothFtpService: successfully stopped ftp service
07-28 12:05:13.206  3885  3885 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-28 12:05:13.207  3885  3885 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-28 12:05:13.207  3885  3885 V BluetoothSapReceiver: SapReceiver onReceive 
07-28 12:05:13.207  3885  3885 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:05:13.207  3885  3885 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
07-28 12:05:13.207  3885  3885 V BluetoothSapReceiver: Calling SAP service start service with action = null
07-28 12:05:13.209  3885  3885 V BluetoothFtpService: Ftp Service onDestroy
07-28 12:05:13.209  3885  3885 V BluetoothFtpService: Ftp Service closeService
07-28 12:05:13.248  6782  6782 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,07-28 12:05:13.249  6782  6782 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
07-28 12:05:13.249  6782  6782 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
07-28 12:05:13.250  6782  6782 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
07-28 12:05:13.250  6782  6782 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
07-28 12:05:13.253  6782  6782 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,07-28 12:05:13.259  6782  6782 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
,07-28 12:05:13.266  1032  1575 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6801 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,07-28 12:05:13.266  3885  3885 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:13.266  3885  3885 V BluetoothSapService: state: 13
07-28 12:05:13.267  3885  3885 V BluetoothSapService: Stopping SAP server process
07-28 12:05:13.268  3885  3885 V BluetoothSapService: Sap Service closeSapService in
07-28 12:05:13.268  3885  3885 V BluetoothSapService: Close listen Socket : 
07-28 12:05:13.268  3885  3885 V BluetoothSapService: Close rfcomm Socket : 
07-28 12:05:13.268  3885  3885 V BluetoothSapService: Close sapd  Socket : 
07-28 12:05:13.269  3885  3885 V BluetoothSapService: Sap Service closeSapService out
07-28 12:05:13.269  3885  3885 V BluetoothSapService: Sap Service onDestroy
07-28 12:05:13.270  3885  3885 V BluetoothSapService: Sap Service closeSapService in
07-28 12:05:13.270  3885  3885 V BluetoothSapService: Close listen Socket : 
07-28 12:05:13.270  3885  3885 V BluetoothSapService: Close rfcomm Socket : 
07-28 12:05:13.270  3885  3885 V BluetoothSapService: Close sapd  Socket : 
07-28 12:05:13.270  3885  3885 V BluetoothSapService: Sap Service closeSapService out
07-28 12:05:13.275  6782  6782 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:05:13.277  6782  6782 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:05:13.300  6782  6782 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,07-28 12:05:13.304  6338  6338 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:05:13.307  6782  6782 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
07-28 12:05:13.307  6737  6737 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-28 12:05:13.307  6737  6737 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-28 12:05:13.307  6737  6737 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-28 12:05:13.310  6782  6782 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
07-28 12:05:13.312  6720  6720 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:05:13.322  6720  6720 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:05:13.330  6782  6782 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:05:13.330  6782  6782 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-28 12:05:13.333  6782  6782 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-28 12:05:13.334  6801  6801 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-28 12:05:13.338  6338  6338 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:05:13.341  6737  6737 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-28 12:05:13.341  6737  6737 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-28 12:05:13.341  6737  6737 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-28 12:05:13.345  6720  6720 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:05:13.357  6720  6720 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:05:13.362  1032  2026 I ActivityManager: Killing 6081:com.lge.appbox.client/u0a11 (adj 15): empty #17
,07-28 12:05:13.403  6782  6782 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-28 12:05:13.404  6782  6782 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:05:13.405  1032  2051 W libprocessgroup: failed to open /acct/uid_10011/pid_6081/cgroup.procs: No such file or directory
07-28 12:05:13.411  6782  6782 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-28 12:05:13.483  1032  1885 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6822 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,07-28 12:05:13.593  6737  6737 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-28 12:05:13.603  6720  6720 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:05:13.618  6720  6720 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-28 12:05:13.633  6822  6844 W FormManager: Network not available. Please check & try again.
,07-28 12:05:13.662  6720  6720 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-28 12:05:13.663  6720  6720 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-28 12:05:13.663  6720  6720 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
,07-28 12:05:13.663  6720  6720 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-28 12:05:13.664  6720  6720 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-28 12:05:13.679  6822  6845 V FormManager: Network unavailable.
,07-28 12:05:13.685  6822  6845 V FormManager: Network unavailable.
07-28 12:05:13.689  6720  6720 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,07-28 12:05:13.690  6720  6720 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
07-28 12:05:13.690  6720  6720 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-28 12:05:13.690  6720  6720 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-28 12:05:13.690  6720  6720 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-28 12:05:13.690  6720  6720 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false,
07-28 12:05:13.694  4323  4323 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
07-28 12:05:13.694  4323  4323 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-28 12:05:13.696  4323  4323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 12:05:13.699  4323  4323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 12:05:13.706  6737  6737 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
07-28 12:05:13.706  6737  6737 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-28 12:05:13.706  6737  6737 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-28 12:05:13.708  4323  6848 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-28 12:05:13.711  6720  6720 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-28 12:05:13.715  4323  6849 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
07-28 12:05:13.716  4323  6849 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,07-28 12:05:13.720  6720  6720 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-28 12:05:13.727  6822  6850 W FormManager: Network not available. Please check & try again.
07-28 12:05:13.732  6822  6851 V FormManager: Network unavailable.
,07-28 12:05:13.736  6822  6851 V FormManager: Network unavailable.
07-28 12:05:13.740  3885  3966 D bt_hci_bdroid: cleanup
07-28 12:05:13.740  3885  4082 I bt_lpm  : LPM is already off!!!
07-28 12:05:13.740  3885  4175 I bt_userial_mct: exiting userial_read_thread
07-28 12:05:13.740  3885  4175 D bt_userial_mct: Leaving userial_evt_read_thread()
07-28 12:05:13.740  6782  6782 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
07-28 12:05:13.740  3885  4080 W bt-btif : ag scb idx 1 not allocated
07-28 12:05:13.740  3885  4080 E bt-btif : BTA AG is already disabled, ignoring ...
07-28 12:05:13.740  3885  4080 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-28 12:05:13.740  3885  4080 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:05:13.740  3885  4080 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-28 12:05:13.741  3885  4080 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:05:13.741  3885  4080 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-28 12:05:13.741  3885  4080 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 12:05:13.741  3885  4080 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-28 12:05:13.741  3885  4080 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:05:13.741  3885  4080 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-28 12:05:13.741  3885  4080 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:05:13.741  3885  4080 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-28 12:05:13.741  3885  4080 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 12:05:13.741  3885  4080 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-28 12:05:13.741  3885  4080 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:05:13.741  3885  4080 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-28 12:05:13.741  3885  4080 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:05:13.741  3885  4080 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-28 12:05:13.741  3885  4080 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 12:05:13.741  3885  4080 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
07-28 12:05:13.741  3885  3966 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
07-28 12:05:13.741  3885  4082 I bt_vendor: hw_epilog_process
07-28 12:05:13.741  6782  6782 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
07-28 12:05:13.741  3885  3966 D bt_hci_bdroid: cleanup Finalizing cleanup
07-28 12:05:13.741  3885  3966 D bt_userial_mct: userial_close
07-28 12:05:13.741  3885  3966 E bt_userial_mct: pthread_join() FAILED result:3
07-28 12:05:13.741  3885  3966 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
07-28 12:05:13.742  6782  6782 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,07-28 12:05:13.744  1032  1575 I ActivityManager: Killing 6104:com.android.contacts/u0a19 (adj 15): empty #17
07-28 12:05:13.780  6782  6782 D LgDataFeature: LgDataFeature() Constructor: none
,07-28 12:05:13.780  6782  6782 D LgDataFeature: LgDataFeature() Constructor Done, null
07-28 12:05:13.787  6782  6782 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
07-28 12:05:13.789  6782  6782 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
07-28 12:05:13.789  6782  6782 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
07-28 12:05:13.789  6782  6782 V SoundPool: doLoad: loading sample sampleID=1
07-28 12:05:13.790  6782  6782 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
07-28 12:05:13.790  6782  6855 V SoundPool: Start decode
07-28 12:05:13.790  6782  6855 V MediaPlayer[Native]: decode(31, 10857164, 17813)
07-28 12:05:13.791   329  1387 V MediaPlayerService: decode(23, 10857164, 17813)
07-28 12:05:13.791   329  1387 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
07-28 12:05:13.791   329  1387 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
07-28 12:05:13.791   329  1387 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
,07-28 12:05:13.791   329  1387 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
07-28 12:05:13.791   329  1387 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
07-28 12:05:13.791   329  1387 V MediaPlayerService: player type = 3
07-28 12:05:13.791   329  1387 V AwesomePlayer: AwesomePlayer create()
07-28 12:05:13.794   329  1387 V AwesomePlayer: reset_l() 
07-28 12:05:13.794   329  1387 V AwesomePlayer: cancelPlayerEvents
07-28 12:05:13.794   329  1387 V AwesomePlayer: setAudioSink() 
07-28 12:05:13.794   329  1387 V AwesomePlayer: reset_l() 
07-28 12:05:13.794   329  1387 V AudioCache: notify(0xb54749c0, 8, 0, 0)
07-28 12:05:13.794   329  1387 V AudioCache: ignored
07-28 12:05:13.794   329  1387 V AwesomePlayer: cancelPlayerEvents
07-28 12:05:13.795   329  1387 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk,
07-28 12:05:13.795   329  1387 V AwesomePlayer: setDataSource_l dataSource
07-28 12:05:13.795   329  1387 V LGParserOSAL: SniffLGParser start
07-28 12:05:13.795   329  1387 V LGParserOSAL: MainType:5, SubType=0
07-28 12:05:13.795   329  1387 V LGParserOSAL: #### check Mime : application/ogg
07-28 12:05:13.795   329  1387 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
07-28 12:05:13.795   329  1387 E MediaExtractor: Use LGExtractor :application/ogg 
07-28 12:05:13.800  1032  2037 W libprocessgroup: failed to open /acct/uid_10019/pid_6104/cgroup.procs: No such file or directory
07-28 12:05:13.805  6782  6782 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
07-28 12:05:13.806  6636  6636 D UEI.SmartControl: QS Service created
,07-28 12:05:13.811  6782  6782 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
07-28 12:05:13.812  6782  6782 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
07-28 12:05:13.825  6636  6636 I UEI.SmartControl: Service initServices...
07-28 12:05:13.825  6636  6636 D UEI.SmartControl: QS start get config
07-28 12:05:13.829  6782  6782 V LGMDMManager: Create singleton instance
,07-28 12:05:13.849   329  1387 V LGParserOSAL: supported mime: application/ogg
07-28 12:05:13.849   329  1387 V AwesomePlayer: setDataSource_l() extractor countTracks=1
07-28 12:05:13.849   329  1387 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
07-28 12:05:13.849   329  1387 V AwesomePlayer: mBitrate = -1 bits/sec
07-28 12:05:13.849   329  1387 V AwesomePlayer: AudioTrack Setting
07-28 12:05:13.849   329  1387 V AwesomePlayer: AudioTrack Setting channelCount = 2
07-28 12:05:13.849   329  1387 V AwesomePlayer: setAudioSource() 
07-28 12:05:13.849   329  1387 V MediaPlayerService: prepare
07-28 12:05:13.849   329  1387 V AwesomePlayer: prepareAsync_l() 
07-28 12:05:13.849   329  1387 V MediaPlayerService: wait for prepare
07-28 12:05:13.850   329  6856 V AwesomePlayer: onPrepareAsyncEvent() 
07-28 12:05:13.850   329  6856 V AwesomePlayer: initAudioDecoder() 
07-28 12:05:13.850   329  6856 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
07-28 12:05:13.850   329  6856 V AudioSystem: isOffloadSupported()
07-28 12:05:13.850   329  6856 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
07-28 12:05:13.850   329  6856 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
07-28 12:05:13.850   329  6856 I AudioFlinger: isAudioPlaybackHookOn() false
07-28 12:05:13.850   329  6856 V AwesomePlayer: getUseOffload() = 0 
07-28 12:05:13.850   329  6856 V OMXCodec: OMXCodec::Create
07-28 12:05:13.850   329  6856 V OMXCodec: findMatchingCodecs()
07-28 12:05:13.850   329  6856 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
07-28 12:05:13.851   329  6856 V OMXCodec: matchingCodecs.size()=1
07-28 12:05:13.851   329  6856 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
07-28 12:05:13.852   329  6856 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
07-28 12:05:13.853   329  6856 V LGCodecAdapter: LG Codec Adapter start
07-28 12:05:13.853   329  6856 V OMXCodec: OMXCodec Createtor
07-28 12:05:13.853   329  6856 V OMXCodec: setComponentRole
07-28 12:05:13.853   329  6856 V OMXCodec: configureCodec protected=0
07-28 12:05:13.853   329  6856 V LGCodecAdapter: called getLGCodecSpecificData
07-28 12:05:13.853   329  6856 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
07-28 12:05:13.853   329  6856 V LGCodecOSAL: Called LGconfigureCodecMETA
07-28 12:05:13.853   329  6856 V LGCodecOSAL: Called LGconfigureCodecMSG
07-28 12:05:13.853   329  6856 V LGCodecOSAL: Not support LGCodec
07-28 12:05:13.853   329  6856 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
07-28 12:05:13.853   329  6856 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
07-28 12:05:13.853   329  6856 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
07-28 12:05:13.853   329  6856 I AwesomePlayer: Could not offload audio decode, try pcm offload
07-28 12:05:13.853   329  6856 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
07-28 12:05:13.853   329  6856 V AudioSystem: isOffloadSupported()
07-28 12:05:13.853   329  6856 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
07-28 12:05:13.853   329  6856 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
07-28 12:05:13.853   329  6856 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
07-28 12:05:13.853   329  6856 V OMXCodec: init()
07-28 12:05:13.853   329  6856 V OMXCodec: [OMX.google.vorbis.decoder] set,State mState=1 , newState=2
07-28 12:05:13.853   329  6856 V OMXCodec: allocateBuffers
07-28 12:05:13.853   329  6856 V OMXCodec: allocateBuffersOnPort portIndex=0
07-28 12:05:13.853   329  6856 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
07-28 12:05:13.854   329  6856 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7830 on input port
07-28 12:05:13.854   329  6856 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f78d0 on input port
07-28 12:05:13.854   329  6856 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
07-28 12:05:13.854   329  6856 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
07-28 12:05:13.854   329  6856 V OMXCodec: allocateBuffersOnPort portIndex=1
07-28 12:05:13.854   329  6856 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
07-28 12:05:13.854   329  6856 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
07-28 12:05:13.854   329  6856 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
07-28 12:05:13.854   329  6856 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bd240 on output port
07-28 12:05:13.854   329  6856 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bd2e0 on output port
07-28 12:05:13.854   329  6856 V OMXCodec: init() mAsyncCompletion wait!!! 
07-28 12:05:13.854   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
07-28 12:05:13.854   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
07-28 12:05:13.855   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
07-28 12:05:13.855   329  6856 V OMXCodec: init() mAsyncCompletion wait!!! 
07-28 12:05:13.855   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
07-28 12:05:13.855   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
07-28 12:05:13.855   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
07-28 12:05:13.855   329  6856 V OMXCodec: init() mAsyncCompletion wait free! 
07-28 12:05:13.855   329  6856 V AwesomePlayer: finishAsyncPrepare_l() 
07-28 12:05:13.855   329  6856 V AudioCache: notify(0xb54749c0, 5, 0, 0)
07-28 12:05:13.855   329  6856 V AudioCache: ignored
07-28 12:05:13.855   329  6856 V AudioCache: notify(0xb54749c0, 1, 0, 0)
07-28 12:05:13.855   329  6856 V AudioCache: prepared
,07-28 12:05:13.856   329  1387 V AudioCache: wait - success
07-28 12:05:13.856   329  1387 V MediaPlayerService: start
07-28 12:05:13.856   329  1387 V AwesomePlayer: play_l() 
07-28 12:05:13.856   329  1387 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
07-28 12:05:13.856   329  1387 V AwesomePlayer: createAudioPlayer_l
07-28 12:05:13.856   329  1387 V AwesomePlayer: seekAudioIfNecessary_l() 
07-28 12:05:13.856   329  1387 V AwesomePlayer: startAudioPlayer_l() 
07-28 12:05:13.856   329  1387 D AudioPlayer: start of Playback, useOffload 0
07-28 12:05:13.856   329  1387 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
07-28 12:05:13.856   329  1387 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
07-28 12:05:13.858  3885  3966 D bt_hci_bdroid: set_power 0
07-28 12:05:13.858  3885  3966 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
07-28 12:05:13.858  3885  3966 I bt_vendor: bluetooth satus is on
07-28 12:05:13.858  3885  3966 I bt_vendor: bt-vendor : resetting BT status
07-28 12:05:13.858  3885  3966 I bt_vendor: Starting hciattach daemon
07-28 12:05:13.858  3885  3966 I bt_vendor: try to set false
07-28 12:05:13.860  3885  3966 I bt_vendor: Starting hciattach daemon
07-28 12:05:13.860  3885  3966 I bt_vendor: try to set false
07-28 12:05:13.860   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
07-28 12:05:13.860   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
07-28 12:05:13.860   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
07-28 12:05:13.860   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
07-28 12:05:13.860   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
07-28 12:05:13.860  3885  3966 I bt_vendor: cleanup
07-28 12:05:13.861  3885  4080 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
07-28 12:05:13.861  3885  3966 I GKI_LINUX: GKI_exit_task 0 done
07-28 12:05:13.861  3885  3966 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
07-28 12:05:13.861   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
07-28 12:05:13.862  3885  3963 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
07-28 12:05:13.864  3885  3885 D HeadsetService: Received stop request...Stopping profile...
07-28 12:05:13.864   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884848
07-28 12:05:13.864   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-28 12:05:13.865   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885088
07-28 12:05:13.865   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-28 12:05:13.865   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044790848
07-28 12:05:13.865  3885  3885 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
07-28 12:05:13.865   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-28 12:05:13.865  3885  3885 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-28 12:05:13.865   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044791008
07-28 12:05:13.865   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-28 12:05:13.865  3885  3885 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24275c7d
07-28 12:05:13.865   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
07-28 12:05:13.865   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
07-28 12:05:13.865   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
07-28 12:05:13.865   329  6858 V OMXCodec: [OMX.google.vorbi,s.decoder] enablePortAsync portIndex=1
07-28 12:05:13.865   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
07-28 12:05:13.866  3885  3998 D HeadsetStateMachine: Exit Disconnected: -1
07-28 12:05:13.866  1851  1851 D BluetoothHeadset: Proxy object disconnected
07-28 12:05:13.866  1851  1851 D BluetoothHeadset: Proxy object disconnected
07-28 12:05:13.866  1851  1851 D BluetoothHeadset: Proxy object disconnected
07-28 12:05:13.866  1032  1032 D BluetoothHeadset: Proxy object disconnected
07-28 12:05:13.867  1032  1032 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,07-28 12:05:13.872  3885  3885 D A2dpService: Received stop request...Stopping profile...
07-28 12:05:13.873  3885  4038 D A2dpStateMachine: Exit Disconnected: -1
07-28 12:05:13.873  3885  3885 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
07-28 12:05:13.874   329  6858 V OMXCodec: allocateBuffersOnPort portIndex=1
07-28 12:05:13.874   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
07-28 12:05:13.874   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bd240 on output port
07-28 12:05:13.874   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
07-28 12:05:13.874   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
07-28 12:05:13.874   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bd600 on output port
07-28 12:05:13.876   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
07-28 12:05:13.876   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
07-28 12:05:13.876  3885  3885 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
07-28 12:05:13.876  3885  3885 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
07-28 12:05:13.876  3885  3885 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24275c7d
07-28 12:05:13.877  1032  1032 D BluetoothA2dp: Proxy object disconnected
07-28 12:05:13.877  1032  1032 D AudioService: onServiceDisconnected: Bluetooth profile: 2
07-28 12:05:13.877  3885  3963 D BluetoothAdapterState: Stopping profile services that were post enabled
07-28 12:05:13.878  3885  3885 D HidService: Received stop request...Stopping profile...
07-28 12:05:13.878  3885  3885 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24275c7d
07-28 12:05:13.879  6720  6720 D BluetoothInputDevice: Proxy object disconnected
07-28 12:05:13.879  6720  6720 D HidProfile: Bluetooth service disconnected
07-28 12:05:13.879  3885  3885 D HeadsetStateMachine: Unbinding service...
07-28 12:05:13.879   329  1387 V AudioCache: open(48000, 2, 0x0, 1, 4)
07-28 12:05:13.879   329  1387 V AudioCache: notify(0xb54749c0, 6, 0, 0)
07-28 12:05:13.880   329  1387 V AudioCache: ignored
,07-28 12:05:13.881   329  6859 V AudioCache: write(0xb0005000, 4096)
07-28 12:05:13.881   329  6859 V AudioCache: memcpy(0xb046e000, 0xb0005000, 4096)
07-28 12:05:13.882  3885  3885 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-28 12:05:13.882  3885  3885 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-28 12:05:13.882  3885  3885 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-28 12:05:13.882  3885  3885 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-28 12:05:13.882  3885  3885 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-28 12:05:13.882  3885  3885 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,07-28 12:05:13.882  3885  3885 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
07-28 12:05:13.883  3885  3885 D HealthService: Received stop request...Stopping profile...
07-28 12:05:13.883  3885  3885 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24275c7d
07-28 12:05:13.884   329  1387 V MediaPlayerService: wait for playback complete
07-28 12:05:13.884  3885  3885 D PanService: Received stop request...Stopping profile...
07-28 12:05:13.885  3885  3885 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24275c7d
07-28 12:05:13.886  3885  3885 D BtGatt.DebugUtils: handleDebugAction() action=null
07-28 12:05:13.886  6720  6720 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-28 12:05:13.886  6720  6720 D PanProfile: Bluetooth service disconnected
07-28 12:05:13.886  3885  3885 D BtGatt.GattService: Received stop request...Stopping profile...
07-28 12:05:13.886  3885  3885 D BtGatt.GattService: stop()
07-28 12:05:13.886  3885  3885 D BtGatt.AdvertiseManager: advertise clients cleared
07-28 12:05:13.888  3885  3885 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24275c7d
07-28 12:05:13.889  3885  3885 D BluetoothMapService: Received stop request...Stopping profile...
07-28 12:05:13.889  3885  3885 D BluetoothMapService: stop()
07-28 12:05:13.889  3885  3885 D BluetoothMapEmailAppObserver: deinitObservers()
07-28 12:05:13.889   329  6859 V AudioCache: write(0xb0005000, 4096)
07-28 12:05:13.889   329  6859 V AudioCache: memcpy(0xb046f000, 0xb0005000, 4096)
07-28 12:05:13.890  3885  3885 D BluetoothMapEmailAppObserver: removeReceiver()
07-28 12:05:13.890  3885  3885 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24275c7d
07-28 12:05:13.890   329  6859 V AudioCache: write(0xb0005000, 4096)
07-28 12:05:13.890   329  6859 V AudioCache: memcpy(0xb0470000, 0xb0005000, 4096)
07-28 12:05:13.891  3885  3885 I BluetoothA2dpServiceJni: cleanupNative
07-28 12:05:13.891  3885  4039 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
07-28 12:05:13.891   329  6859 V AudioCache: write(0xb0005000, 4096)
07-28 12:05:13.891   329  6859 V AudioCache: memcpy(0xb0471000, 0xb0005000, 4096)
07-28 12:05:13.892  3885  3885 I GKI_LINUX: GKI_exit_task 2 done
07-28 12:05:13.892  3885  3885 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
07-28 12:05:13.892  3885  3885 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-28 12:05:13.892  3885  3885 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-28 12:05:13.892   329  6859 V AudioCache: write(0xb0005000, 4096)
07-28 12:05:13.892   329  6859 V AudioCache: memcpy(0xb0472000, 0xb0005000, 4096)
07-28 12:05:13.892  3885  3885 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-28 12:05:13.893   329  6859 V AudioCache: write(0xb0005000, 4096)
07-28 12:05:13.893   329  6859 V AudioCache: memcpy(0xb0473000, 0xb0005000, 4096)
07-28 12:05:13.893  3885  3885 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-28 12:05:13.893  3885  3885 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-28 12:05:13.893  3885  3885 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-28 12:05:13.893  3885  3885 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-28 12:05:13.894   329  6859 V AudioCache: write(0xb0005000, 4096)
07-28 12:05:13.894   329  6859 V AudioCache: memcpy(0xb0474000, 0xb0005000, 4096)
07-28 12:05:13.895   329  6859 V AudioCache: write(0xb0005000, 4096)
07-28 12:05:13.895   329  6859 V AudioCache: memcpy(0xb0475000, 0xb0005000, 4096)
,07-28 12:05:13.895   329  6859 V AudioCache: write(0xb0005000, 4096)
07-28 12:05:13.895   329  6859 V AudioCache: memcpy(0xb0476000, 0xb0005000, 4096)
07-28 12:05:13.896  3885  3885 V BluetoothMapService: Handler(): got msg=4
07-28 12:05:13.896  3885  3885 D BluetoothMapService: MAP Service closeService in
07-28 12:05:13.896  3885  3885 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-28 12:05:13.896  3885  3885 V BluetoothMapService: MAP Service closeService out
07-28 12:05:13.896   329  6859 V AudioCache: write(0xb0005000, 4096)
07-28 12:05:13.896   329  6859 V AudioCache: memcpy(0xb0477000, 0xb0005000, 4096)
07-28 12:05:13.896  3885  3885 D BluetoothMapService: cleanup()
07-28 12:05:13.896  3885  3885 D BluetoothMapService: MAP Service closeService in
07-28 12:05:13.896  3885  3885 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-28 12:05:13.896  3885  3885 V BluetoothMapService: MAP Service closeService out
07-28 12:05:13.897  3885  3963 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
07-28 12:05:13.897  3885  3963 D BluetoothAdapterProperties: Setting state to 10
07-28 12:05:13.897  3885  3963 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
07-28 12:05:13.897  1032  1097 D BluetoothManagerService: Message: 60
07-28 12:05:13.897  1032  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
07-28 12:05:13.897  1032  1097 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
07-28 12:05:13.897  1032  1097 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 12:05:13.897  3885  3963 I BluetoothAdapterState: Entering OffState
07-28 12:05:13.898   329  6859 V AudioCache: write(0xb0005000, 4096)
07-28 12:05:13.898   329  6859 V AudioCache: memcpy(0xb0478000, 0xb0005000, 4096)
07-28 12:05:13.898  6720  6736 D BluetoothPan: onBluetoothStateChange on: false
07-28 12:05:13.899   329  6859 V AudioCache: write(0xb0005000, 4096)
07-28 12:05:13.899   329  6859 V AudioCache: memcpy(0xb0479000, 0xb0005000, 4096)
07-28 12:05:13.900   329  6859 V AudioCache: write(0xb0005000, 4096)
07-28 12:05:13.900   329  6859 V AudioCache: memcpy(0xb047a000, 0xb0005000, 4096)
07-28 12:05:13.900  6720  6735 D BluetoothPbap: onBluetoothStateChange: up=false
07-28 12:05:13.900   329  6859 V AudioCache: write(0xb0005000, 4096)
07-28 12:05:13.900   329  6859 V AudioCache: memcpy(0xb047b000, 0xb0005000, 4096)
07-28 12:05:13.901  1851  1867 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 12:05:13.901  1851  1866 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 12:05:13.901   329  6859 V AudioCache: write(0xb0005000, 4096)
07-28 12:05:13.902   329  6859 V AudioCache: memcpy(0xb047c000, 0xb0005000, 4096)
07-28 12:05:13.902  6720  6736 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-28 12:05:13.902   329  6859 V AudioCache: write(0xb0005000, 4096)
07-28 12:05:13.902   329  6859 V AudioCache: memcpy(0xb047d000, 0xb0005000, 4096)
07-28 12:05:13.902   329  6859 V AudioCache: write(0xb0005000, 4096)
07-28 12:05:13.902   329  6859 V AudioCache: memcpy(0xb047e000, 0xb0005000, 4096)
07-28 12:05:13.902   329  6859 V AudioCache: write(0xb0005000, 4096)
07-28 12:05:13.902   329  6859 V AudioCache: memcpy(0xb047f000, 0xb0005000, 4096)
07-28 12:05:13.902  6720  6735 D BluetoothMap: onBluetoothStateChange: up=false
07-28 12:05:13.903  1032  1097 D BluetoothA2dp: onBluetoothStateChange: up=false
07-28 12:05:13.903  1851  4000 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 12:05:13.904  1032  1097 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
07-28 12:05:13.904  1032  1097 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
07-28 12:05:13.905   329  6859 V AudioCache: write(0xb0005000, 4096)
07-28 12:05:13.905   329  6859 V AudioCache: memcpy(0xb0480000, 0xb0005000, 4096)
07-28 12:05:13.905   329  6859 V AudioCache: write(0xb0005000, 4096)
07-28 12:05:1,3.905   329  6859 V AudioCache: memcpy(0xb0481000, 0xb0005000, 4096)
07-28 12:05:13.905   329  6859 V AudioCache: write(0xb0005000, 4096)
07-28 12:05:13.905   329  6859 V AudioCache: memcpy(0xb0482000, 0xb0005000, 4096)
07-28 12:05:13.905   329  6859 V AudioCache: write(0xb0005000, 4096)
07-28 12:05:13.905   329  6859 V AudioCache: memcpy(0xb0483000, 0xb0005000, 4096)
07-28 12:05:13.906   329  6859 V AudioCache: write(0xb0005000, 4096)
07-28 12:05:13.906   329  6859 V AudioCache: memcpy(0xb0484000, 0xb0005000, 4096)
,07-28 12:05:13.909   329  6859 V AudioCache: write(0xb0005000, 4096)
07-28 12:05:13.909   329  6859 V AudioCache: memcpy(0xb0485000, 0xb0005000, 4096)
07-28 12:05:13.909   329  6859 V AudioCache: write(0xb0005000, 4096)
07-28 12:05:13.909   329  6859 V AudioCache: memcpy(0xb0486000, 0xb0005000, 4096)
07-28 12:05:13.910   329  6859 V AudioCache: write(0xb0005000, 4096)
07-28 12:05:13.910   329  6859 V AudioCache: memcpy(0xb0487000, 0xb0005000, 4096)
07-28 12:05:13.910   329  6859 V AudioCache: write(0xb0005000, 4096)
07-28 12:05:13.910   329  6859 V AudioCache: memcpy(0xb0488000, 0xb0005000, 4096)
07-28 12:05:13.910   329  6859 V AudioCache: write(0xb0005000, 4096)
07-28 12:05:13.910   329  6859 V AudioCache: memcpy(0xb0489000, 0xb0005000, 4096)
07-28 12:05:13.912   329  6859 V AudioCache: write(0xb0005000, 4096)
07-28 12:05:13.912   329  6859 V AudioCache: memcpy(0xb048a000, 0xb0005000, 4096)
07-28 12:05:13.912  1032  1097 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
07-28 12:05:13.912  1032  1097 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
,07-28 12:05:13.912  1032  1097 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@2973cb5a mBinding = false
07-28 12:05:13.913   329  6859 V AudioCache: write(0xb0005000, 4096)
07-28 12:05:13.913   329  6859 V AudioCache: memcpy(0xb048b000, 0xb0005000, 4096)
07-28 12:05:13.913   329  6859 V AudioCache: write(0xb0005000, 4096)
07-28 12:05:13.913   329  6859 V AudioCache: memcpy(0xb048c000, 0xb0005000, 4096)
07-28 12:05:13.914  1032  1097 D BluetoothManagerService: Sending unbind request.
07-28 12:05:13.915  1032  1097 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
07-28 12:05:13.916  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:13.917  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-28 12:05:13.920   329  6859 V AudioCache: write(0xb0005000, 4096)
07-28 12:05:13.920   329  6859 V AudioCache: memcpy(0xb048d000, 0xb0005000, 4096)
07-28 12:05:13.920   329  6859 V AudioCache: write(0xb0005000, 4096)
07-28 12:05:13.920   329  6859 V AudioCache: memcpy(0xb048e000, 0xb0005000, 4096)
07-28 12:05:13.920  1940  2165 D LGBluetoothAPIService: Message: 2
07-28 12:05:13.921  1940  2165 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@2e32aa24 mBinding = false
07-28 12:05:13.921  1940  2165 D LGBluetoothAPIService: Sending unbind request.
07-28 12:05:13.921  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:13.928  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:13.929  3885  3966 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
07-28 12:05:13.929  3885  3885 I GKI_LINUX: GKI_exit_task 1 done
07-28 12:05:13.929  3885  3885 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
07-28 12:05:13.929  3885  3885 I BluetoothServiceJni: cleanupNative: return from cleanup
07-28 12:05:13.930  3885  3885 I art     : --- WEIRD: removing null entry 246
07-28 12:05:13.930  3885  3885 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
07-28 12:05:13.930  3885  3885 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
07-28 12:05:13.930   329  6859 V AudioCache: write(0xb0005000, 4096)
07-28 12:05:13.930   329  6859 V AudioCache: memcpy(0xb048f000, 0xb0005000, 4096)
07-28 12:05:13.930  3885  3885 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
,07-28 12:05:13.933   329  6859 V AudioCache: write(0xb0005000, 4096)
07-28 12:05:13.933   329  6859 V AudioCache: memcpy(0xb0490000, 0xb0005000, 4096)
07-28 12:05:13.933  6720  6720 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-28 12:05:13.934   329  6859 V AudioCache: write(0xb0005000, 4096)
07-28 12:05:13.934   329  6859 V AudioCache: memcpy(0xb0491000, 0xb0005000, 4096)
07-28 12:05:13.934  6720  6720 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
07-28 12:05:13.934  6720  6720 D LGBluetoothEventManager: [BTUI] clear device connection state
07-28 12:05:13.934   329  6859 V AudioCache: write(0xb0005000, 4096)
07-28 12:05:13.934   329  6859 V AudioCache: memcpy(0xb0492000, 0xb0005000, 4096)
07-28 12:05:13.935   329  6859 V AudioCache: write(0xb0005000, 4096)
07-28 12:05:13.935   329  6859 V AudioCache: memcpy(0xb0493000, 0xb0005000, 4096)
07-28 12:05:13.935  3885  3885 I art     : System.exit called, status: 0
07-28 12:05:13.935  3885  3885 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
07-28 12:05:13.936  6720  6720 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-28 12:05:13.937   329  6859 V AudioCache: write(0xb0005000, 4096)
07-28 12:05:13.937   329  6859 V AudioCache: memcpy(0xb0494000, 0xb0005000, 4096)
07-28 12:05:13.938   329  6859 V AudioCache: write(0xb0005000, 4096)
07-28 12:05:13.938   329  6859 V AudioCache: memcpy(0xb0495000, 0xb0005000, 4096)
07-28 12:05:13.938  1602  1602 D BluetoothAdapter: 64968885: getState() :  mService = null. Returning STATE_OFF
07-28 12:05:13.938  1602  1602 D BluetoothAdapter: 64968885: getState() :  mService = null. Returning STATE_OFF
07-28 12:05:13.940   329  6859 V AudioCache: write(0xb0005000, 4096)
07-28 12:05:13.940   329  6859 V AudioCache: memcpy(0xb0496000, 0xb0005000, 4096)
07-28 12:05:13.940   329  6859 V AudioCache: write(0xb0005000, 4096)
07-28 12:05:13.940   329  6859 V AudioCache: memcpy(0xb0497000, 0xb0005000, 4096)
07-28 12:05:13.941   329  6859 V AudioCache: write(0xb0005000, 4096)
07-28 12:05:13.941   329  6859 V AudioCache: memcpy(0xb0498000, 0xb0005000, 4096)
07-28 12:05:13.942   329  6859 V AudioCache: write(0xb0005000, 4096)
07-28 12:05:13.942   329  6859 V AudioCache: memcpy(0xb0499000, 0xb0005000, 4096)
,07-28 12:05:13.943   329  6859 V AudioCache: write(0xb0005000, 4096)
07-28 12:05:13.943   329  6859 V AudioCache: memcpy(0xb049a000, 0xb0005000, 4096)
07-28 12:05:13.944   329  6859 V AudioCache: write(0xb0005000, 4096)
07-28 12:05:13.944   329  6859 V AudioCache: memcpy(0xb049b000, 0xb0005000, 4096)
07-28 12:05:13.945   329  6859 V AudioCache: write(0xb0005000, 4096)
07-28 12:05:13.945  6720  6720 D DockEventReceiver: finishStartingService: stopping service
07-28 12:05:13.945   329  6859 V AudioCache: memcpy(0xb049c000, 0xb0005000, 4096)
07-28 12:05:13.946   329  6859 V AudioCache: write(0xb0005000, 4096)
07-28 12:05:13.946   329  6859 V AudioCache: memcpy(0xb049d000, 0xb0005000, 4096)
07-28 12:05:13.946   329  6859 V AudioCache: write(0xb0005000, 4096)
07-28 12:05:13.946   329  6859 V AudioCache: memcpy(0xb049e000, 0xb0005000, 4096)
07-28 12:05:13.947   329  6859 V AudioCache: write(0xb0005000, 4096)
07-28 12:05:13.947   329  6859 V AudioCache: memcpy(0xb049f000, 0xb0005000, 4096)
07-28 12:05:13.948   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
07-28 12:05:13.948   329  6859 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
07-28 12:05:13.948   329  6859 V AwesomePlayer: postAudioEOS() 
07-28 12:05:13.948   329  6859 V AudioCache: write(0xb0005000, 280)
07-28 12:05:13.948   329  6859 V AudioCache: memcpy(0xb04a0000, 0xb0005000, 280)
07-28 12:05:13.949   329  6856 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
07-28 12:05:13.949   329  6856 V AwesomePlayer: onStreamDone
07-28 12:05:13.949   329  6856 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
07-28 12:05:13.950   329  6856 V AudioCache: notify(0xb54749c0, 2, 0, 0)
07-28 12:05:13.950   329  6856 V AudioCache: playback complete
07-28 12:05:13.950   329  6856 V AwesomePlayer: pause_l() 
07-28 12:05:13.950   329  6856 V AudioCache: notify(0xb54749c0, 7, 0, 0)
07-28 12:05:13.950   329  6856 V AudioCache: ignored
07-28 12:05:13.950   329  6856 V AwesomePlayer: cancelPlayerEvents
07-28 12:05:13.950   329  1387 V AudioCache: wait - success
07-28 12:05:13.950   329  1387 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
07-28 12:05:13.950   329  6856 D AudioPlayer: Pause Playback at 1068125
07-28 12:05:13.950   329  1387 V AwesomePlayer: reset_l() 
07-28 12:05:13.950   329  1387 V AudioCache: notify(0xb54749c0, 8, 0, 0)
07-28 12:05:13.950   329  1387 V AudioCache: ignored
07-28 12:05:13.950   329  1387 V AwesomePlayer: cancelPlayerEvents
07-28 12:05:13.950   329  1387 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
07-28 12:05:13.950   329  1387 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
07-28 12:05:13.950   329  1387 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
07-28 12:05:13.950   329  1387 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
07-28 12:05:13.950   329  1387 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
07-28 12:05:13.951   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
07-28 12:05:13.951   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
07-28 12:05:13.951   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
07-28 12:05:13.951   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
07-28 12:05:13.951   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
07-28 12:05:13.951   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
07-28 12:05:13.951   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
07-28 12:05:13.951   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f78d0 on port 0
,07-28 12:05:13.951   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
07-28 12:05:13.951   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7830 on port 0
07-28 12:05:13.951   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
07-28 12:05:13.951   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
07-28 12:05:13.951   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57bd600 on port 1
07-28 12:05:13.952   329  2215 V AudioFlinger: 3885 died, releasing its sessions
07-28 12:05:13.952   329  2215 V AudioFlinger:  pid 1851 @ 0
07-28 12:05:13.952   329  2215 V AudioFlinger:  pid 3454 @ 1
07-28 12:05:13.952   329  2215 V AudioFlinger:  pid 3454 @ 2
07-28 12:05:13.952   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
07-28 12:05:13.952   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 1
07-28 12:05:13.952   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
07-28 12:05:13.952  6720  6720 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
07-28 12:05:13.952   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 1
07-28 12:05:13.952   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
07-28 12:05:13.952   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57bd240 on port 1
07-28 12:05:13.952   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-28 12:05:13.952   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
07-28 12:05:13.952   329  1387 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
07-28 12:05:13.952   329  1387 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
07-28 12:05:13.952   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
07-28 12:05:13.952   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
07-28 12:05:13.952   329  6858 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
07-28 12:05:13.952   329  1387 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
07-28 12:05:13.952   329  1387 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
07-28 12:05:13.953   329  1387 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
07-28 12:05:13.953   329  1387 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
07-28 12:05:13.953   329  1387 D AudioPlayer: AudioPlayer releasing audio source
07-28 12:05:13.953   329  1387 D AudioPlayer: AudioPlayer done releasing audio source
07-28 12:05:13.954   329  1387 V AwesomePlayer: reset_l() 
07-28 12:05:13.954   329  1387 V AwesomePlayer: cancelPlayerEvents
07-28 12:05:13.954   329  1387 V AwesomePlayer: ~AwesomePlayer call
07-28 12:05:13.954   329  1387 V AwesomePlayer: reset_l() 
07-28 12:05:13.954   329  1387 V AwesomePlayer: cancelPlayerEvents
07-28 12:05:13.957  6782  6855 V SoundPool: close(31)
07-28 12:05:13.957  6782  6855 V SoundPool: pointer = 0x9fe38000, size = 205080, sampleRate = 48000, numChannels = 2
07-28 12:05:13.979  6782  6782 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,07-28 12:05:13.981  6782  6782 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
07-28 12:05:14.079  1032  1885 I ActivityManager: Process com.android.bluetooth (pid 3885) has died
07-28 12:05:14.079  1032  1885 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,07-28 12:05:14.087  6782  6782 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:5713
,07-28 12:05:14.087  2126  2126 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-28 12:05:14.105  6720  6720 D BluetoothPermissionRequest: onReceive
,07-28 12:05:14.108  6720  6720 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
07-28 12:05:14.109  6720  6720 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
07-28 12:05:14.112  6720  6720 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-28 12:05:14.172  1032  1975 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6868 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,07-28 12:05:14.190   350   350 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 462us total 20.729ms
,07-28 12:05:14.197  6636  6636 I UEI.SmartControl: Supports setup maps: true
07-28 12:05:14.199  6868  6868 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
07-28 12:05:14.200  6868  6868 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-28 12:05:14.200  6868  6868 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
07-28 12:05:14.200  6868  6868 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
07-28 12:05:14.203  6636  6636 D UEI.SmartControl: QS start statue = true Error code = 0
07-28 12:05:14.203  6636  6636 I UEI.SmartControl: QS version = v2.7.10.1_RC1
07-28 12:05:14.203  6636  6636 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
07-28 12:05:14.203  6636  6636 I UEI.SmartControl: ### init IR Blaster...
,07-28 12:05:14.207  6636  6636 D serial_port: Configuring serial port
07-28 12:05:14.207  6636  6636 E UEI.SmartControl: UEIBLaster setting for 616
07-28 12:05:14.207  6636  6636 I UEI.SmartControl: Setting serial record hearder size = 2
07-28 12:05:14.207  6636  6636 I UEI.SmartControl: configuring settings for MAXQ616
07-28 12:05:14.207  6636  6636 I UEI.SmartControl: Get version...
07-28 12:05:14.210  6868  6868 D BluetoothAdapterApp: Loading JNI Library
07-28 12:05:14.211   350   350 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 402us total 19.176ms
07-28 12:05:14.225  6636  6885 D UEI.SmartControl: serial port data available: 21
,07-28 12:05:14.227  6868  6868 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@147d4f1a Instance Count = 1
,07-28 12:05:14.230  6868  6868 D BluetoothAdapterApp: onCreate
07-28 12:05:14.232   350   350 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 428us total 19.956ms
07-28 12:05:14.241  6868  6868 D ProfileConfigQcom: [BTUI] HeadsetService is supported
07-28 12:05:14.241  6868  6868 D ProfileConfigQcom: Adding HeadsetService
07-28 12:05:14.241  6868  6868 D ProfileConfigQcom: [BTUI] A2dpService is supported
07-28 12:05:14.241  6868  6868 D ProfileConfigQcom: Adding A2dpService
07-28 12:05:14.242  6868  6868 D ProfileConfigQcom: [BTUI] HidService is supported
07-28 12:05:14.242  6868  6868 D ProfileConfigQcom: Adding HidService
,07-28 12:05:14.242  6868  6868 D ProfileConfigQcom: [BTUI] HealthService is supported
07-28 12:05:14.242  6868  6868 D ProfileConfigQcom: Adding HealthService
07-28 12:05:14.242  6868  6868 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
07-28 12:05:14.242  6868  6868 D ProfileConfigQcom: [BTUI] PanService is supported
07-28 12:05:14.243  6868  6868 D ProfileConfigQcom: Adding PanService
07-28 12:05:14.243  6868  6868 D ProfileConfigQcom: [BTUI] GattService is supported
07-28 12:05:14.243  6868  6868 D ProfileConfigQcom: Adding GattService
07-28 12:05:14.243  6868  6868 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
07-28 12:05:14.243  6868  6868 D ProfileConfigQcom: Adding BluetoothMapService
07-28 12:05:14.243  6868  6868 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
07-28 12:05:14.244  6868  6868 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
07-28 12:05:14.246  6720  6720 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
07-28 12:05:14.247  6868  6868 V LGMDMManagerInternal: Create singleton instance
07-28 12:05:14.252  6636  6636 D UEI.SmartControl: MAXQ616 A2-X4 software.
07-28 12:05:14.252  6636  6636 I UEI.SmartControl: IR Blaster version: 256702256704300002
07-28 12:05:14.252  6636  6636 I UEI.SmartControl: QS saving settings...
07-28 12:05:14.253  6636  6636 D UEI.SmartControl: IR Blaster version: 25672567
,07-28 12:05:14.267  6636  6885 D UEI.SmartControl: serial port data available: 4
,07-28 12:05:14.287  6868  6868 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:05:14.291  6868  6868 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-28 12:05:14.291  6868  6868 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-28 12:05:14.292  6868  6868 V BluetoothSapReceiver: SapReceiver onReceive 
07-28 12:05:14.294  6636  6892 I UEI.SmartControl: Device manager: loading config....
07-28 12:05:14.294  6636  6892 D UEI.SmartControl: ----------- loading internal config...
,07-28 12:05:14.296  6636  6636 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
07-28 12:05:14.297  6636  6636 E UEI.SmartControl: Services init done
07-28 12:05:14.297  6636  6636 D UEI.SmartControl: QS Service init finished
07-28 12:05:14.295  6868  6868 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:14.298  6636  6636 D UEI.SmartControl: QS Service version name: 2.1.91
07-28 12:05:14.298  6636  6636 D UEI.SmartControl: QS Service version code: 201091
07-28 12:05:14.299  6636  6636 D UEI.SmartControl: Service requested: Control
07-28 12:05:14.299  6868  6868 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
07-28 12:05:14.300  6636  6892 E UEI.SmartControl: Loading SETTINGS...
07-28 12:05:14.308  6636  6636 D UEI.SmartControl: Request IControl service: devices are loaded...
07-28 12:05:14.309  6782  6782 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,07-28 12:05:14.311  6801  6801 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
07-28 12:05:14.312  6636  6636 D UEI.SmartControl: Internal service binding...
07-28 12:05:14.313  6636  6652 I UEI.SmartControl: ------ IControl API: 11
07-28 12:05:14.313  6636  6652 D UEI.SmartControl: File observer start...
07-28 12:05:14.313  6636  6652 E UEI.SmartControl: IR Port is disabled: false
07-28 12:05:14.314  6636  6652 D UEI.SmartControl: Starting file observer...
07-28 12:05:14.314  6636  6652 I UEI.SmartControl: Registering callback...
07-28 12:05:14.315  6636  6651 I UEI.SmartControl: ------ IControl API: 19
07-28 12:05:14.315  6636  6651 I UEI.SmartControl: Registering Services Ready callback...
07-28 12:05:14.317  6636  6892 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
07-28 12:05:14.335  6636  6891 I UEI.SmartControl: Notify AllClients services are ready: 0
07-28 12:05:14.335  6636  6891 D UEI.SmartControl: -----service ready thread exits
07-28 12:05:14.335  6782  6797 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,07-28 12:05:14.336  6782  6853 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
,07-28 12:05:14.337  6782  6853 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
07-28 12:05:14.337  6782  6782 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
07-28 12:05:14.337  6782  6782 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
,07-28 12:05:14.337  6636  6895 I UEI.SmartControl: ------ IControl API: 8
07-28 12:05:14.339  6782  6782 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
07-28 12:05:14.339  6782  6782 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
07-28 12:05:14.339  6782  6782 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
07-28 12:05:14.339  6782  6782 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
07-28 12:05:14.340  6782  6782 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
07-28 12:05:14.340  6782  6782 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
07-28 12:05:14.341  6782  6782 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
07-28 12:05:14.346  6782  6782 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
07-28 12:05:14.346  6782  6782 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
07-28 12:05:14.347  6782  6782 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
07-28 12:05:14.347  6782  6782 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
07-28 12:05:14.348  6782  6782 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,07-28 12:05:14.349  6782  6782 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
,07-28 12:05:14.349  6782  6782 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
07-28 12:05:14.350  6782  6782 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1469700314349]
07-28 12:05:14.350  6782  6782 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
07-28 12:05:14.357  1032  2037 I ActivityManager: Killing 6127:com.android.gallery3d/u0a27 (adj 15): empty #17
07-28 12:05:14.367  6782  6896 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,07-28 12:05:14.389  1032  2037 I ActivityManager: Killing 6440:com.lge.email/u0a23 (adj 15): empty #18
,07-28 12:05:14.425  1032  2013 W libprocessgroup: failed to open /acct/uid_10023/pid_6440/cgroup.procs: No such file or directory
,07-28 12:05:14.425  6782  6782 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,07-28 12:05:14.427  6782  6782 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
07-28 12:05:14.428  6782  6782 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
07-28 12:05:14.428  1032  1939 W libprocessgroup: failed to open /acct/uid_10027/pid_6127/cgroup.procs: No such file or directory
07-28 12:05:14.429  6782  6782 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
07-28 12:05:14.430  6782  6782 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
07-28 12:05:14.431  6782  6782 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
07-28 12:05:14.432  6782  6782 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
07-28 12:05:14.452  6782  6782 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,07-28 12:05:15.016  1032  1378 V AlarmManager: ELAPSED_WAKEUP set : Alarm{29249055 type 2 when 135050 com.google.android.gms} when 135050
,07-28 12:05:15.035   324  6904 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,07-28 12:05:15.042  1032  1095 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,07-28 12:05:15.599  1032  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:05:15.614  1032  1097 D Tethering: MasterInitialState.processMessage what=3
07-28 12:05:15.631  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:05:15.636  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:15.638  1032  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-28 12:05:15.640  1032  1097 D Tethering: MasterInitialState.processMessage what=3
07-28 12:05:15.648  1032  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:05:15.653  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:15.654  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:15.655  6338  6338 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
07-28 12:05:15.664  6338  6374 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,07-28 12:05:15.669  5792  5792 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,07-28 12:05:15.683  5792  5792 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
07-28 12:05:15.694  1032  1921 D WifiServiceImplEx: setWifiEnabled: true pid=6524, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-28 12:05:15.695  1032  1921 D WifiService: setWifiEnabled: true pid=6524, uid=10118
,07-28 12:05:15.695  1032  1921 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-28 12:05:15.705  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-28 12:05:15.705  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-28 12:05:15.705  1032  1032 D Ulp_jni : JNI:system_update. Event-4
07-28 12:05:15.707  1032  1538 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
07-28 12:05:15.707  1032  1538 I LGFTMITEM: [GET_FTM][id=6], offset=12288
07-28 12:05:15.708  1032  1538 E WifiUtil: wfc_util_ffile_check_copy(): pid[1032] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
07-28 12:05:15.708  1032  1538 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
07-28 12:05:15.708  1032  1538 E WifiUtil: wfc_util_ffile_check_copy(): pid[1032] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
07-28 12:05:15.708  1032  1538 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
07-28 12:05:15.708  1032  1538 I WifiUtil: Intf0MacAddress=C49A027FFB5D
07-28 12:05:15.708  1032  1538 E WifiHW  : unknown target_country: EU , set to default
07-28 12:05:15.708  1032  1538 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
,07-28 12:05:15.708  1032  1538 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
07-28 12:05:15.711  1032  1538 I WifiUtil: gEnableBmps=1
07-28 12:05:15.721  2126  2126 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:05:15.773  1032  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:05:15.796  1032  1642 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6920 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
07-28 12:05:15.801  1032  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:15.802  1032  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:15.864  6920  6920 I AppUp4:AppBoxCP: onCreate
,07-28 12:05:15.865  6920  6920 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,07-28 12:05:15.874  6920  6920 I AppUp4:DB:  setFingerPrint start
,07-28 12:05:15.875  6920  6920 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
07-28 12:05:15.882  6920  6920 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
07-28 12:05:15.882  6920  6920 I AppUp4:DB:  SDK version = 21
,07-28 12:05:15.882  6920  6920 I AppUp4:DB:  beforefinger == newfinger no write in DB
07-28 12:05:15.884  6920  6920 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
07-28 12:05:15.886  6920  6920 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
07-28 12:05:15.886  6920  6920 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
07-28 12:05:15.888  6920  6920 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-28 12:05:15.888  6920  6920 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
07-28 12:05:15.895  6920  6920 I AppUp4:CustModeStarterReceiver: onReceive
07-28 12:05:15.954  6920  6920 D LgDataFeature: LgDataFeature() Constructor: none
07-28 12:05:15.954  6920  6920 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-28 12:05:15.962  6920  6920 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2e3ae2d4
07-28 12:05:15.963  6920  6920 D AppUp4:CustFacade: isCustomizationCompleted : false
07-28 12:05:15.963  6920  6920 D AppUp4:CustFacade: isPhone : true
07-28 12:05:15.963  6920  6920 D AppUp4:CustModeStarterReceiver: begin check event
07-28 12:05:15.964  6920  6920 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
07-28 12:05:15.964  6920  6920 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
07-28 12:05:15.965  6920  6939 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
07-28 12:05:15.966  6920  6939 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
07-28 12:05:15.966  6920  6939 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
07-28 12:05:15.968  1032  1575 I ActivityManager: Killing 6281:com.android.defcontainer/u0a4 (adj 15): empty #17
,07-28 12:05:16.062  1032  2037 W libprocessgroup: failed to open /acct/uid_10004/pid_6281/cgroup.procs: No such file or directory
07-28 12:05:16.065  4323  4323 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
07-28 12:05:16.066  4323  4323 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,07-28 12:05:16.074  4323  4323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 12:05:16.081  4323  4323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,07-28 12:05:16.097  4323  6942 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,07-28 12:05:16.104  4323  6943 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
07-28 12:05:16.104  4323  6943 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-28 12:05:16.146  1032  2026 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6944 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,07-28 12:05:16.254  6944  6944 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-28 12:05:16.255  6944  6944 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,07-28 12:05:16.257  6944  6944 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-28 12:05:16.258  6944  6944 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
07-28 12:05:16.384  6944  6944 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,07-28 12:05:16.399  6944  6944 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
07-28 12:05:16.440  6944  6944 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-28 12:05:16.479  6944  6944 D LgDataFeature: LgDataFeature() Constructor: none
07-28 12:05:16.480  6944  6944 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-28 12:05:16.561   324   891 D SoftapController: Softap fwReload - Ok
,07-28 12:05:16.564  1032  1538 E NetdConnector: NDC Command {52 softap fwreload wlan0 STA} took too long (846ms)
07-28 12:05:16.572  1032  1097 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
07-28 12:05:16.572  1032  1097 D Tethering: InitialState.processMessage what=4
07-28 12:05:16.574  1032  1097 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,07-28 12:05:16.577   324   891 D CommandListener: Setting iface cfg
07-28 12:05:16.577   324   891 D CommandListener: Trying to bring down wlan0
07-28 12:05:16.578   324   891 D CommandListener: Clearing all IP addresses on wlan0
07-28 12:05:16.583  1032  1538 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
07-28 12:05:16.585  1032  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-28 12:05:16.585  1032  1538 E WifiStateMachine: useWiFiOffloading() : false
07-28 12:05:16.585  1032  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-28 12:05:16.585  6979  6979 W wpa_supplicant: type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:05:16.585  6979  6979 W wpa_supplicant: type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,07-28 12:05:16.598  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
07-28 12:05:16.600  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-28 12:05:16.601  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,07-28 12:05:16.604  1032  1538 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
07-28 12:05:16.604  1032  1538 D WifiMonitor: connecting to supplicant
07-28 12:05:16.609  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:16.609  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:05:16.631  6979  6979 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-28 12:05:16.665  6979  6979 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-28 12:05:16.665  6979  6979 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,07-28 12:05:16.686  6944  6944 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,07-28 12:05:16.717  3454  3454 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
07-28 12:05:16.717  3454  3454 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:05:16.719  6944  6944 I HubEmail: JNI_OnLoad()
07-28 12:05:16.719  6944  6944 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-28 12:05:16.719  6944  6944 I HubEmail: registerNatives()
07-28 12:05:16.719  6944  6944 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-28 12:05:16.719  6944  6944 I HubEmail: registerNativeMethods()
07-28 12:05:16.720  6944  6944 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-28 12:05:16.720  3454  3454 I LgeMiscReceiver: networkInfo.isConnected() = false
07-28 12:05:16.720  6944  6944 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
07-28 12:05:16.725  6979  6979 I wpa_supplicant: rfkill: Cannot open RFKILL control device
07-28 12:05:16.771  1032  2051 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6997 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,07-28 12:05:16.780  6944  6996 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:16.780  6822  6994 W FormManager: Network not available. Please check & try again.
07-28 12:05:16.780  6979  6979 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
07-28 12:05:16.784  6979  6979 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
07-28 12:05:16.784  6979  6979 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,07-28 12:05:16.785  1032  1538 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,07-28 12:05:16.785  1032  1538 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
07-28 12:05:16.786  1032  7014 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
07-28 12:05:16.786  1032  1538 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
07-28 12:05:16.786  1032  7014 D WifiMonitor: Dropping event because (p2p0) is stopped
07-28 12:05:16.786  1032  7014 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
07-28 12:05:16.786  1032  7014 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
07-28 12:05:16.786  1032  7014 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
07-28 12:05:16.786  1032  1538 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
07-28 12:05:16.786  1032  7014 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
07-28 12:05:16.786  1032  1538 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:05:16.787  1032  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:05:16.787  6822  6995 V FormManager: Network unavailable.
07-28 12:05:16.787  1032  1538 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:05:16.787  1032  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:05:16.788  1032  1538 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
07-28 12:05:16.788  1032  1538 D WifiNative-wlan0: doString: [DRIVER MACADDR]
07-28 12:05:16.789  6822  6995 V FormManager: Network unavailable.
07-28 12:05:16.789  1032  1538 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
07-28 12:05:16.790  1032  1538 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
07-28 12:05:16.790  1032  1538 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
07-28 12:05:16.790  1032  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-28 12:05:16.790  1032  1538 E WifiStateMachine: useWiFiOffloading() : false
07-28 12:05:16.790  1032  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-28 12:05:16.790  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:16.790  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:16.790  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:16.790  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:16.790  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-28 12:05:16.791  1032  1538 D WifiNative-wlan0: doBoolean: SET update_config 1
07-28 12:05:16.791  1032  1538 D WifiNative-wlan0: SET update_config 1: returned true
07-28 12:05:16.791  1032  1538 D WifiConfigStore: Loading config and enabling all networks 
07-28 12:05:16.791  1032  1538 D WifiNative-wlan0: doString: [LIST_NETWORKS]
07-28 12:05:16.792  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:05:16.792  1940  1940 D WfdService: Waiting for WifiP2p enabling
07-28 12:05:16.794  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
07-28 12:05:16.794  6524  6524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:05:16.794  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:05:16.794  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:05:16.794  6524  6524 V io.jxcore.node.ConnectivityMonitor,:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:16.794  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:05:16.794  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:05:16.794  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:05:16.794  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:05:16.794  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:05:16.794  6524  6524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:05:16.794  6524  6524 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:05:16.794  1032  1538 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
07-28 12:05:16.795  1032  1542 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
07-28 12:05:16.796  6524  6524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:05:16.796  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:05:16.796  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:05:16.796  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:16.796  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:05:16.796  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:05:16.796  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:05:16.796  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:05:16.796  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:05:16.796  6524  6524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:05:16.796  6524  6524 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:05:16.800  1032  1538 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
07-28 12:05:16.805  1032  2026 I ActivityManager: Killing 6152:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
07-28 12:05:16.807  1032  1538 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
07-28 12:05:16.807  1032  1538 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
07-28 12:05:16.859  1032  2051 W libprocessgroup: failed to open /acct/uid_10080/pid_6152/cgroup.procs: No such file or directory
,07-28 12:05:16.859  1032  1538 D WifiStateMachine: enableVerboseLogging : level 2
07-28 12:05:16.859  1032  1538 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
07-28 12:05:16.860  1032  1538 D WifiNative-wlan0: SET device_name g3_global_com: returned true
07-28 12:05:16.860  1032  1538 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
07-28 12:05:16.861  1032  1538 D WifiNative-wlan0: SET manufacturer LGE: returned true
07-28 12:05:16.861  1032  1538 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
07-28 12:05:16.861  6997  6997 D LgDataFeature: LgDataFeature() Constructor: none
07-28 12:05:16.861  6997  6997 D LgDataFeature: LgDataFeature() Constructor Done, null
07-28 12:05:16.861  1032  1538 D WifiNative-wlan0: SET model_name LG-D855: returned true
07-28 12:05:16.861  1032  1538 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
07-28 12:05:16.861  1032  1538 D WifiNative-wlan0: SET model_number LG-D855: returned true
07-28 12:05:16.861  1032  1538 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
07-28 12:05:16.862  1032  1538 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
07-28 12:05:16.862  1032  1538 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
07-28 12:05:16.862  1032  1538 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
07-28 12:05:16.862  1032  1538 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
07-28 12:05:16.863  1032  1538 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
07-28 12:05:16.863  1032  1538 D WifiStateMachine: Setting OUI to DA-A1-19
07-28 12:05:16.863  1032  1538 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
07-28 12:05:16.864  1940  1940 D WfdsService: Supplicant Connection state is changed : true
07-28 12:05:16.864  1940  2302 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
07-28 12:05:16.864  1940  2302 D WfdsService: Set the WFDS Monitor: true
07-28 12:05:16.864  1940  2302 D WfdsMonitor: WfdsMonitorThread create
07-28 12:05:16.864  1032  1538 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
07-28 12:05:16.864  1032  1538 D WifiNative-HAL: Setting external_sim to 1
07-28 12:05:16.864  1940  2302 D WfdsMonitor: WFDS Monitor is created and started
07-28 12:05:16.864  1032  1538 D WifiNative-wlan0: doBoolean: SET external_sim 1
07-28 12:05:16.864  1940  2302 D WfdsService: WiFi: Supplicant connection re-established
07-28 12:05:16.864  1032  1538 D WifiNative-wlan0: SET external_sim 1: returned true
07-28 12:05:16.864  1032  1538 I WifiNative-HAL: startHal
07-28 12:05:16.864  1032  1538 D wifi    : setting scan oui 0x953cf3c0
07-28 12:05:16.865  1032  1538 D WifiStateMachine: Setting OUI to DA-A1-19
07-28 12:05:16.865  1032  1538 I WifiNative-HAL: startHal
07-28 12:05:16.865  1032  1538 D wifi    : setting scan oui 0x953cf3c0
07-28 12:05:16.865  6997  6997 D PhoneMonitor: Register our PhoneStateListener
07-28 12:05:16.865  1032  1538 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
07-28 12:05:16.866  1032  1538 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
07-28 12:05:16.866  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
07-28 12:05:16.866  6979  6979 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
07-28 12:05:16.866  1032  1538 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
07-28 12:05:16.866  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
,07-28 12:05:16.866  6979  6979 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
07-28 12:05:16.867  1032  1538 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
07-28 12:05:16.867  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
07-28 12:05:16.867  6979  6979 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
07-28 12:05:16.867  1032  1538 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
07-28 12:05:16.867  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
07-28 12:05:16.868  6979  6979 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
,07-28 12:05:16.868  1032  1538 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
07-28 12:05:16.868  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
07-28 12:05:16.868  6979  6979 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
07-28 12:05:16.868  1032  1538 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
07-28 12:05:16.868  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
07-28 12:05:16.869  6979  6979 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
07-28 12:05:16.869  1032  1538 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
07-28 12:05:16.869  1940  7015 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
07-28 12:05:16.869  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
,07-28 12:05:16.870  6979  6979 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
07-28 12:05:16.870  1032  1538 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
07-28 12:05:16.870  1940  7015 E CtrlSupplicant: Succeed to open control connection
07-28 12:05:16.871  1940  7015 E CtrlSupplicant: Succeed to open monitor connection
07-28 12:05:16.872  1940  7015 D WfdsMonitor: Supplicant connection established
07-28 12:05:16.872  1940  2302 D WfdsService: Connected to the supplicant for wfds
,07-28 12:05:16.875  1032  1538 E WifiNative: : [136,909,033 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
07-28 12:05:16.875  1032  1538 D WifiNative-wlan0: doBoolean: RECONNECT
07-28 12:05:16.876  1032  1538 D WifiNative-wlan0: RECONNECT: returned true
07-28 12:05:16.876  1032  1538 D WifiNative-wlan0: doString: [STATUS]
07-28 12:05:16.877  1032  7014 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
07-28 12:05:16.877  1032  7014 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
07-28 12:05:16.878  1032  1538 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
07-28 12:05:16.878  1032  1538 D WifiNative-wlan0: doBoolean: SET ps 1
07-28 12:05:16.879  1032  1538 D WifiNative-wlan0: SET ps 1: returned true
07-28 12:05:16.880  1032  1537 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:16.881  6997  6997 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
07-28 12:05:16.882  1032  1032 D WifiScanningService: SCAN_AVAILABLE : 3
07-28 12:05:16.882  1032  1032 D RttService: SCAN_AVAILABLE : 3
07-28 12:05:16.882  1032  1556 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:16.882  1032  1556 I WifiNative-HAL: startHal
07-28 12:05:16.882  1032  1557 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:16.882  1032  1556 D wifi    : getting scan capabilities on interface[1] = 0x953cf3c0
07-28 12:05:16.882  1032  1556 D wifi    : failed to get capabilities : -3
07-28 12:05:16.882  1032  1556 E WifiScanningService: could not get scan capabilities
07-28 12:05:16.883  1032  1538 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
07-28 12:05:16.883  6997  6997 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,07-28 12:05:16.884   324   891 D CommandListener: Setting iface cfg
07-28 12:05:16.884   324   891 D CommandListener: Trying to bring up p2p0
07-28 12:05:16.885  1032  1537 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-28 12:05:16.885  1032  1537 D LGWifiP2pService: P2pEnablingState
07-28 12:05:16.885  1032  1537 D LGWifiP2pService: P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:16.885  1032  1537 D LGWifiP2pService: P2p socket connection successful
07-28 12:05:16.885  1032  1537 D LGWifiP2pService: P2pEnabledState
07-28 12:05:16.886  1032  1538 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
07-28 12:05:16.886  1032  1538 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
07-28 12:05:16.887  1032  1538 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
07-28 12:05:16.887  1032  1538 E WifiStateMachine:  DisconnectedState what:132106 1 0
07-28 12:05:16.887  1032  1538 E WifiStateMachine:  ConnectModeState what:132106 1 0
07-28 12:05:16.888  1032  1538 E WifiStateMachine:  DriverStartedState what:132106 1 0
07-28 12:05:16.888  1032  1538 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
07-28 12:05:16.889  6979  6979 E wpa_supplicant: nWIFIDualbandAPConnection: 1
07-28 12:05:16.889  1032  1538 E WifiStateMachine:  DisconnectedState what:132096 -100 0
07-28 12:05:16.890  1032  1538 E WifiStateMachine:  ConnectModeState what:132096 -100 0
07-28 12:05:16.890  1032  1538 E WifiStateMachine:  DriverStartedState what:132096 -100 0
07-28 12:05:16.890  1032  1538 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
07-28 12:05:16.890  6979  6979 E wpa_supplicant: disconnect_rssi_lvl: -100
07-28 12:05:16.891  1032  1538 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
07-28 12:05:16.892  1032  1538 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
07-28 12:05:16.892  1032  1538 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
07-28 12:05:16.892  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
07-28 12:05:16.893  6979  6979 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
07-28 12:05:16.894  6979  6979 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:05:16.895  6979  6979 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
07-28 12:05:16.895  6979  6979 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,07-28 12:05:16.895  6979  6979 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:05:16.897  1940  7015 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,07-28 12:05:16.897  1940  7015 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:05:16.897  1032  7014 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-28 12:05:16.897  1032  7014 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:05:16.897  1032  7014 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:05:16.897  1032  7014 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:05:16.897  1032  7014 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:05:16.897  1032  7014 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:05:16.897  1032  7014 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:05:16.897  1032  7014 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:05:16.897  1032  7014 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:05:16.897  1032  7014 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:05:16.897  1032  7014 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:05:16.897  1032  7014 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:05:16.898  1032  1538 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
07-28 12:05:16.899  1032  1538 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
07-28 12:05:16.899  1032  1538 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
07-28 12:05:16.899  1032  1538 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
07-28 12:05:16.900  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
07-28 12:05:16.900  6997  6997 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
07-28 12:05:16.900  6979  6979 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
07-28 12:05:16.900  6979  6979 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-28 12:05:16.900  6997  6997 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
07-28 12:05:16.901  6997  6997 D TelephonyAutoProfiling: [parse] Load xml
07-28 12:05:16.901  1032  7014 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
07-28 12:05:16.901  1032  7014 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-28 12:05:16.901  1032  7014 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-28 12:05:16.901  1032  7014 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-28 12:05:16.901  1032  1538 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
07-28 12:05:16.901  1032  1538 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
07-28 12:05:16.902  1032  1538 D WifiNative-wlan0: BSS_FLUSH 0: returned true
07-28 12:05:16.902  1032  1538 D WifiNative-wlan0: doBoolean: SCAN
07-28 12:05:16.902  1032  1538 D WifiNative-wlan0: SCAN: returned false
07-28 12:05:16.903  1032  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=136941  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-28 12:05:16.904  6997  6997 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
07-28 12:05:16.904  6997  6997 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
07-28 12:05:16.904  6997  6997 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
07-28 12:05:16.904  6997  6997 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
07-28 12:05:16.904  6997  6997 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
07-28 12:05:16.904  6997  6997 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
07-28 12:05:16.904  6997  6997 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
07-28 12:05:16.904  6997  6997 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
07-28 12:05:16.904  6997  6997 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
07-28 12:05:16.904  6997  6997 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
07-28 12:05:16.904  6997  6997 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
07-28 12:05:16.904  6997  6997 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
07-28 12:05:16.904  6997  6997 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
07-28 12:05:16.904  6997  6997 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
07-28 12:05:16.904  6997  6997 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
07-28 12:05:16.904  6997  6997 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
07-28 12:05:16.904  6997  6997 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,07-28 12:05:16.912  6997  6997 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
07-28 12:05:16.935  1032  1781 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7018 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-28 12:05:16.936  1032  1781 I ActivityManager: Killing 6474:com.google.android.apps.docs/u0a61 (adj 15): empty #17
07-28 12:05:16.998  1032  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=137036  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,07-28 12:05:16.999  1032  1537 D LGWifiP2pService: sending p2p connection changed broadcast
07-28 12:05:17.002  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:17.002  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:05:17.005  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:05:17.006  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:17.006  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:17.006  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
07-28 12:05:17.010  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
07-28 12:05:17.011  1032  1975 W libprocessgroup: failed to open /acct/uid_10061/pid_6474/cgroup.procs: No such file or directory
07-28 12:05:17.011  1940  1940 D WfdsService: WifiP2pState is changed : true
,07-28 12:05:17.011  1940  2302 D WfdsService: Receive the WFDS_ENABLE Method
07-28 12:05:17.011  1940  2302 D WfdsService: Set the WFDS Monitor: true
07-28 12:05:17.011  1940  2302 D WfdsService: Connected to the supplicant for wfds
07-28 12:05:17.011  1940  2302 D WfdsJNI : doCommand: WFDS_SET TRUE
07-28 12:05:17.012  6979  6979 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
07-28 12:05:17.012  1940  2302 D WfdsService: selectPreferredScanChannel [36]
07-28 12:05:17.013  1940  2302 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
07-28 12:05:17.036  1032  1537 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
07-28 12:05:17.036  1032  1538 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,07-28 12:05:17.037  1032  1537 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
07-28 12:05:17.037  1032  1538 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-28 12:05:17.038  1032  1537 D WifiNative-p2p0: doBoolean: SET device_name G3
07-28 12:05:17.039  1032  1537 D WifiNative-p2p0: SET device_name G3: returned true
07-28 12:05:17.039  1032  1537 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
07-28 12:05:17.039  1032  1537 D LGWifiP2pService: before postfix = G3
07-28 12:05:17.039  1032  1537 D WifiServerServiceExt: postfix byte check : 2
07-28 12:05:17.039  1032  1537 D LGWifiP2pService: after postfix = G3
07-28 12:05:17.040  1032  1537 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
07-28 12:05:17.041  1940  1940 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
07-28 12:05:17.041  1032  1538 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-28 12:05:17.041  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 12:05:17.041  1032  1032 D WifiServerServiceExt: setSupplicantStateSCANNING
07-28 12:05:17.042  1032  1537 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
07-28 12:05:17.042  1032  1537 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
07-28 12:05:17.042  1032  1538 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-28 12:05:17.043  1032  1538 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-28 12:05:17.043  1940  1940 D WfdsService: isConnected: false
07-28 12:05:17.044  1032  1537 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
07-28 12:05:17.044  1032  1537 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
07-28 12:05:17.045  1032  1537 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
07-28 12:05:17.045  1032  1537 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
07-28 12:05:17.046  1032  1537 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
,07-28 12:05:17.048  1032  1537 D WifiNative-HAL: p2pGetDeviceAddress
07-28 12:05:17.048  1032  1537 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
07-28 12:05:17.050  1032  1537 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
07-28 12:05:17.050  1032  1537 D WifiNative-p2p0: doBoolean: P2P_FLUSH
07-28 12:05:17.051  1032  1537 D WifiNative-p2p0: P2P_FLUSH: returned true
,07-28 12:05:17.051  1032  1537 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
07-28 12:05:17.051  1940  1940 I WfdStateTracker: handleP2pThisDeviceChanged
07-28 12:05:17.051  1940  1940 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
07-28 12:05:17.051  1940  1940 D WfdsService: Update P2p Interface State: 3
07-28 12:05:17.052  1032  1537 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
,07-28 12:05:17.052  1032  1537 D WifiNative-p2p0: doString: [LIST_NETWORKS]
,07-28 12:05:17.053  1032  1537 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
07-28 12:05:17.053  1032  1537 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
07-28 12:05:17.065  1032  1537 D WifiNative-p2p0: SAVE_CONFIG: returned true
,07-28 12:05:17.065  1032  1537 D LGWifiP2pService: sending p2p persistent groups changed broadcast
07-28 12:05:17.065  1032  1537 D LGWifiP2pService: InactiveState
07-28 12:05:17.065  1032  1537 D LGWifiP2pService: InactiveState{ when=-168ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:17.066  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=-168ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:17.066  1032  1537 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
07-28 12:05:17.067  6979  6979 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
07-28 12:05:17.069  6979  6979 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:05:17.070  6979  6979 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
07-28 12:05:17.070  6979  6979 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:05:17.070  6979  6979 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:05:17.071  1940  7015 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-28 12:05:17.072  1940  7015 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:05:17.072  1940  7015 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:05:17.072  1032  7014 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-28 12:05:17.072  1032  7014 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:05:17.072  1032  7014 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:05:17.072  1032  7014 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:05:17.072  1032  7014 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:05:17.072  1032  7014 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:05:17.072  1032  7014 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:05:17.072  1032  7014 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:05:17.072  1032  7014 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:05:17.072  1032  7014 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:05:17.073  1032  7014 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:05:17.073  1032  7014 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:05:17.073  1032  1537 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
07-28 12:05:17.074  1032  1537 D LGWifiP2pService: InactiveState{ when=-22ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:17.074  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=-22ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:17.074  1032  1537 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:17.074  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:17.074  1032  1537 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:17.074  1032  1537 D LGWifiP2pService: InactiveState{ when=0 what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:17.074  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:17.074  1032  1537 D LGWifiP2pService: DefaultState{ when=-1ms wh,at=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:17.075  1940  2302 W WfdsService: DefaultState - msg [9441285] is not handled
07-28 12:05:17.075  1032  1537 D LGWifiP2pService: InactiveState{ when=-2ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:17.075  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:17.075  1032  1537 D LGWifiP2pService: DefaultState{ when=-2ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:17.075  1032  1537 D LGWifiP2pService: InactiveState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:17.076  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:17.076  1032  1537 D LGWifiP2pService: DefaultState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:17.076  1032  1032 E WifiServerServiceExt: No p2p device connected
07-28 12:05:17.254  1032  1939 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7036 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
07-28 12:05:17.256  1032  1939 I ActivityManager: Killing 6180:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,07-28 12:05:17.332  6979  6979 E wpa_supplicant: USIM:  scard_init function
07-28 12:05:17.332  1032  7014 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
07-28 12:05:17.332  1032  7014 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
07-28 12:05:17.332  6979  6979 I wpa_supplicant: Trying to associate with SSID 'NG700'
07-28 12:05:17.332  1032  7014 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
07-28 12:05:17.333  1032  7014 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
07-28 12:05:17.333  1032  7014 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
07-28 12:05:17.334  1032  1538 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
07-28 12:05:17.335  1032  1538 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
07-28 12:05:17.336  1032  1538 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
,07-28 12:05:17.337  1032  1538 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
07-28 12:05:17.337  1032  1538 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
07-28 12:05:17.338  1032  7014 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
07-28 12:05:17.338  1032  7014 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
07-28 12:05:17.343  1032  2026 W libprocessgroup: failed to open /acct/uid_10097/pid_6180/cgroup.procs: No such file or directory
07-28 12:05:17.357  1032  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=137395  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,07-28 12:05:17.361  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:17.361  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:05:17.366  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:17.367  1032  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=137405  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
07-28 12:05:17.368  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:17.368  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
07-28 12:05:17.368  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:05:17.369  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:17.369  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:17.369  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
07-28 12:05:17.369  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 12:05:17.369  1032  1032 D WifiServerServiceExt: setSupplicantStateASSOCIATING
07-28 12:05:17.371  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:17.371  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,07-28 12:05:17.372  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:05:17.444  6979  6979 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
07-28 12:05:17.445  1032  7014 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
07-28 12:05:17.445  1032  7014 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
07-28 12:05:17.445  1032  7014 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
07-28 12:05:17.446  1032  7014 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
07-28 12:05:17.446  1032  7014 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-28 12:05:17.446  1032  7014 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,07-28 12:05:17.449  1032  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=137487  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
07-28 12:05:17.451  1032  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=137489  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
07-28 12:05:17.453  1032  1538 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=137491
07-28 12:05:17.454  1032  7014 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-28 12:05:17.454  1032  7014 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-28 12:05:17.454  6979  6979 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-28 12:05:17.454  6979  6979 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-28 12:05:17.454  1032  7014 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
07-28 12:05:17.455  1032  7014 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-28 12:05:17.455  1032  7014 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-28 12:05:17.455  1032  7014 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
07-28 12:05:17.455  1032  7014 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-28 12:05:17.455  1032  7014 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-28 12:05:17.456  1032  7014 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-28 12:05:17.456  1032  7014 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-28 12:05:17.456  1032  1538 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=137495
07-28 12:05:17.458  1032  1538 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=137496
07-28 12:05:17.459  1032  1538 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=137497
07-28 12:05:17.460  1032  1538 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=137498
07-28 12:05:17.460  1032  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=137498  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,07-28 12:05:17.466  1032  1939 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7053 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-28 12:05:17.467  1032  1097 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
07-28 12:05:17.471  1032  1939 I ActivityManager: Killing 6575:com.lge.eula/1000 (adj 15): empty #17
07-28 12:05:17.521  1032  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=137559  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,07-28 12:05:17.521  1032  2026 W libprocessgroup: failed to open /acct/uid_1000/pid_6575/cgroup.procs: No such file or directory
07-28 12:05:17.522  1032  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=137560  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
07-28 12:05:17.523  1032  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=137561  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
07-28 12:05:17.524  1032  1538 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=137562
07-28 12:05:17.524  1032  1538 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=137562
07-28 12:05:17.525  1032  1538 D WifiNative-wlan0: doString: [STATUS]
07-28 12:05:17.526  1032  1538 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
07-28 12:05:17.528  1032  1538 I WifiServiceExtension: setVHTCapabilityType  : false
07-28 12:05:17.528  1032  7014 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-28 12:05:17.529  1032  7014 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-28 12:05:17.536  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:17.536  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:05:17.540  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:05:17.542  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:17.542  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:17.542  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
07-28 12:05:17.545  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:17.545  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:17.545  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
07-28 12:05:17.545  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 12:05:17.545  1032  1032 D WifiServerServiceExt: setSupplicantStateASSOCIATED
07-28 12:05:17.546  1032  1538 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
07-28 12:05:17.546  1032  1538 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
07-28 12:05:17.555  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:17.556  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:17.556  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,07-28 12:05:17.560  1032  1538 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
07-28 12:05:17.560  1032  1545 D ConnectivityService: Got NetworkAgent Messenger
07-28 12:05:17.560  1032  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
07-28 12:05:17.560  1032  1545 D ConnectivityService: NetworkAgent connected
07-28 12:05:17.560  1032  1538 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-28 12:05:17.561  1032  1538 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-28 12:05:17.561  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:17.561  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:17.561  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
07-28 12:05:17.561  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:17.561  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:05:17.561  1032  1538 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-28 12:05:17.561  1032  1538 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-28 12:05:17.562  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:05:17.564  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:17.565  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:05:17.566  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:05:17.567  1032  1538 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-28 12:05:17.567  1032  1538 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-28 12:05:17.567  1032  1538 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-28 12:05:17.568  1032  1538 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-28 12:05:17.568  1032  1538 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,07-28 12:05:17.572  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:17.572  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:05:17.573  1032  1538 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-28 12:05:17.574  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:05:17.575   324   891 D CommandListener: Setting iface cfg
07-28 12:05:17.578  1032  1538 E WifiStateMachine: Start Dhcp Watchdog 2
07-28 12:05:17.578  1032  7071 D DhcpStateMachine: StoppedState
07-28 12:05:17.578  1032  7071 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:17.578  1032  7071 D DhcpStateMachine: WaitBeforeStartState
07-28 12:05:17.578  1032  1538 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=137617  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 12:05:17.579  7053  7053 I art     : Almond Protected OAT
,07-28 12:05:17.579  1032  1538 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=137617  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 12:05:17.580  1032  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=137618  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 12:05:17.580  1032  1538 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:05:17.581  1032  1538 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:05:17.581  1032  1538 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:05:17.581  1032  1538 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:05:17.582  1032  1538 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:05:17.582  1032  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:05:17.583  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 12:05:17.583  1032  1032 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
,07-28 12:05:17.584  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 12:05:17.584  1032  1032 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
07-28 12:05:17.585  1032  1538 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=137623  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 12:05:17.586  1032  1538 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=137624  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 12:05:17.586  1032  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=137624  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 12:05:17.587  1032  1538 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:92339] from screen [on:0 period:821502355] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-28 12:05:17.589  1032  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:821502356] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-28 12:05:17.589  1032  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-28 12:05:17.592  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:05:17.594  1032  1545 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
07-28 12:05:17.594  1032  1538 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,07-28 12:05:17.594  1032  1538 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:05:17.595  1032  1538 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:05:17.595  1032  1538 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:05:17.595  1032  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:05:17.596  1032  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:05:17.596  1032  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
07-28 12:05:17.597  1032  1538 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=125,0,0
07-28 12:05:17.597  1032  1538 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=125,0,0
07-28 12:05:17.597  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
07-28 12:05:17.597  6979  6979 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
07-28 12:05:17.598  1032  1538 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
07-28 12:05:17.598  1032  1538 D WifiNative-wlan0: doBoolean: SET ps 0
07-28 12:05:17.598  1032  1538 D WifiNative-wlan0: SET ps 0: returned true
07-28 12:05:17.598  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
07-28 12:05:17.599  6979  6979 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
07-28 12:05:17.608  1032  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
07-28 12:05:17.609  1032  1538 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
07-28 12:05:17.609  1032  1538 V DhcpStateMachine: Current State is mWaitBeforeStartState.
07-28 12:05:17.609  1032  1537 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@21b66b1b target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:17.609  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@21b66b1b target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:17.609  1032  1538 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
07-28 12:05:17.609  1032  7071 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:17.609  1032  7071 D DhcpStateMachine: DHCP Start wake lock is acquired.
,07-28 12:05:17.611   324   891 D CommandListener: Setting iface cfg
07-28 12:05:17.611   324   891 D CommandListener: Trying to bring up wlan0
07-28 12:05:17.611  1032  1537 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:17.611  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:17.611  1032  1537 D LGWifiP2pService: DefaultState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:17.612  1032  1538 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
07-28 12:05:17.613  1032  1538 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,07-28 12:05:17.613  1032  1538 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:05:17.613  1032  1538 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:05:17.614  1032  1538 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:05:17.614  1032  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:05:17.615  1032  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:05:17.616  1032  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
07-28 12:05:17.616  1032  1538 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
07-28 12:05:17.616  1032  1538 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
07-28 12:05:17.617  1032  1537 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:17.617  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:17.617  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-28 12:05:17.617  6979  6979 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-28 12:05:17.617  1032  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-28 12:05:17.617  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
07-28 12:05:17.618  6979  6979 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
07-28 12:05:17.618  1032  1538 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
07-28 12:05:17.618  1032  1538 D WifiNative-wlan0: doBoolean: SET ps 1
07-28 12:05:17.627  7053  7053 D WeatherApplication: removeAccount
07-28 12:05:17.628  7053  7053 D WeatherApplication: Account.length = 0
07-28 12:05:17.628  7053  7053 E WeatherApplication: OPERATOR:OPEN
07-28 12:05:17.632  7053  7053 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:5:17
,07-28 12:05:17.634  7053  7053 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
07-28 12:05:17.634  7053  7053 D Weather.Utils: 2 : All the weather widget is gone.
07-28 12:05:17.634  1032  1538 D WifiNative-wlan0: SET ps 1: returned true
07-28 12:05:17.635  1032  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
07-28 12:05:17.635  1032  1538 E WifiStateMachine:  ObtainingIpState CMD_STOP_SUPPLICANT_FAILED 1 0
07-28 12:05:17.635  7053  7053 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-28 12:05:17.636  1032  1538 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
07-28 12:05:17.636  1032  1538 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
07-28 12:05:17.637  1032  1538 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
07-28 12:05:17.637  1032  1538 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
07-28 12:05:17.637  7053  7053 D WeatherAncestor: connectivity changed - connection : true
07-28 12:05:17.638  1032  1538 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
07-28 12:05:17.638  1032  1538 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
07-28 12:05:17.638  7053  7053 D WeatherService: 2 : isServiceAlived():false forecastCache:null
07-28 12:05:17.639  1032  1538 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
07-28 12:05:17.639  1032  1538 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
07-28 12:05:17.640  1032  1545 D ConnectivityService: ignoring duplicate network state non-change
07-28 12:05:17.642  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 12:05:17.642  1032  1032 D WifiServerServiceExt: setSupplicantStateCOMPLETED
07-28 12:05:17.642  1032  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
07-28 12:05:17.643  1032  1545 D ConnectivityService: Adding iface wlan0 to network 101
,07-28 12:05:17.646  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:17.646  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:05:17.647  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:05:17.649  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:17.649  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:17.649  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
07-28 12:05:17.652  7053  7053 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
07-28 12:05:17.652  7053  7053 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
07-28 12:05:17.652  7053  7053 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,07-28 12:05:17.656  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:17.656  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:17.656  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
07-28 12:05:17.657  1032  1538 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
07-28 12:05:17.659  1032  1032 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,07-28 12:05:17.661  1940  1940 V WfdStateTracker: handleWifiStateChangedEvent: 1
07-28 12:05:17.662  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:17.663  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:17.663  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
07-28 12:05:17.663  1032  1032 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
07-28 12:05:17.667  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:17.668  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:17.668  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,07-28 12:05:17.671  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:17.671  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:05:17.671  7053  7053 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-28 12:05:17.671  7053  7053 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:5:17
07-28 12:05:17.672  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:05:17.677  1032  1545 E ConnectivityService: Unexpected mtu value: 0, wlan0
07-28 12:05:17.677  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:17.677  1032  1545 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
07-28 12:05:17.677  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
07-28 12:05:17.677  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:05:17.678  1032  1545 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
07-28 12:05:17.678   324   891 E Netd    : netlink response contains error (File exists)
07-28 12:05:17.679  1032  1545 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,07-28 12:05:17.680  1032  1545 D ConnectivityService: addLocalRoutetoDefaultNetwork
07-28 12:05:17.680  1032  1545 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
07-28 12:05:17.680  1032  1545 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
07-28 12:05:17.680  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:17.681  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
07-28 12:05:17.681  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:05:17.710  1032  1993 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7075 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-28 12:05:17.710  1032  1545 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
07-28 12:05:17.710  1032  1545 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
07-28 12:05:17.710  1032  1545 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
07-28 12:05:17.710  1032  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
07-28 12:05:17.710  1032  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:05:17.710  1032  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:05:17.710  1032  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
07-28 12:05:17.710  1032  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:05:17.710  1032  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
07-28 12:05:17.710  1032  1545 D ConnectivityService: currentScore = 0, newScore = 20
07-28 12:05:17.710  1032  1545 D ConnectivityService:    accepting network in place of null
07-28 12:05:17.710  1032  1545 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:05:17.710  1032  1538 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:05:17.710  1032  1538 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:05:17.711  1032  7070 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:17.711  1032  7070 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
07-28 12:05:17.711  1032  7070 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:17.711  1032  7070 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
07-28 12:05:17.711  1032  1993 I ActivityManager: Killing 6598:com.lge.bnr/1000 (adj 15): empty #17
,07-28 12:05:17.712  1032  1545 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
07-28 12:05:17.712  1032  1545 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
07-28 12:05:17.712  1032  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-28 12:05:17.713  1851  1851 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:05:17.713  1851  1851 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-28 12:05:17.714   324  7085 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
07-28 12:05:17.767   324  7085 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,07-28 12:05:17.781  1032  1092 W ActivityManager: Failed to clear dns cache for: com.lge.bnr
,07-28 12:05:17.784  1032  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-28 12:05:17.784  1032  1545 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
07-28 12:05:17.784  1032  1781 W libprocessgroup: failed to open /acct/uid_1000/pid_6598/cgroup.procs: No such file or directory
07-28 12:05:17.785  1032  1545 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
07-28 12:05:17.788  1032  1545 D ConnectivityService: validation of new default Network = false
07-28 12:05:17.788  1032  1545 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
07-28 12:05:17.789  1032  1545 D DSQN    : enableDataServiceNotify 
07-28 12:05:17.789  1032  1545 D DSQN    : start dsqn bin
07-28 12:05:17.797  1032  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
07-28 12:05:17.797  1032  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:05:17.797  1032  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:05:17.798  1032  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-28 12:05:17.795  7094  7094 W dsqn    : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:05:17.795  7094  7094 W dsqn    : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:05:17.799  1602  2072 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-28 12:05:17.802   324  7085 D libc-netbsd: res_queryN name = clients3.google.com succeed
07-28 12:05:17.804  1032  1032 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
07-28 12:05:17.805  1032  1032 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-28 12:05:17.805  1032  1032 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-28 12:05:17.805  1032  1032 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,07-28 12:05:17.813  1032  7071 D DhcpStateMachine: DHCPV4 request on wlan0
07-28 12:05:17.815  1032  7071 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
07-28 12:05:17.815  1032  7071 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
07-28 12:05:17.819  7094  7094 E DSQN    : DSQN ssw
,07-28 12:05:17.815  7098  7098 W dhcpcd  : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:05:17.815  7098  7098 W dhcpcd  : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:05:17.830  7098  7098 I dhcpcd  : version 5.5.6 starting
07-28 12:05:17.832  7098  7098 E dhcpcd  : get_duid: m
07-28 12:05:17.832  7098  7098 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
07-28 12:05:17.832  7098  7098 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,07-28 12:05:17.841  1032  1536 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
07-28 12:05:17.844   324   890 D LGDataListener: argv[0]=dsqncommand
07-28 12:05:17.845   324   890 D LGDataListener: argv[1]=wlan0
07-28 12:05:17.845   324   890 D LGDataListener: argv[2]=1
07-28 12:05:17.845   324   890 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
07-28 12:05:17.845  1032  1095 D DSQN    : DSQM DsqnNotification wlan0  1
07-28 12:05:17.845  1032  1095 D DSQN    : start to monitor internet connection
,07-28 12:05:17.850  1816  7099 I CheckinService: active receiver: enabled
,07-28 12:05:17.862  1816  7099 I CheckinService: Preparing to send checkin request
07-28 12:05:17.862  1816  7099 I EventLogService: Accumulating logs since 1469700237200
07-28 12:05:17.866  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-28 12:05:17.867  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:05:17.868  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:05:17.879  1032  7070 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 28 Jul 2016 10:05:17 GMT], X-Android-Received-Millis=[1469700317878], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1469700317847]}
07-28 12:05:17.879  1032  7070 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
07-28 12:05:17.879  1032  7070 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
07-28 12:05:17.879  1032  1545 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
07-28 12:05:17.879  1032  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
07-28 12:05:17.879  1032  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:05:17.879  1032  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:05:17.879  1032  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
07-28 12:05:17.879  1032  1545 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
,07-28 12:05:17.879  1032  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
07-28 12:05:17.879  1032  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:05:17.880  1032  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:05:17.880  1032  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:05:17.880  1032  1545 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:05:17.880  1032  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
07-28 12:05:17.880  1032  1538 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:05:17.881  1032  1538 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:05:17.882  1602  2072 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-28 12:05:17.883  1851  1851 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:05:17.883  1851  1851 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-28 12:05:17.885  7098  7098 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
07-28 12:05:17.885  7098  7098 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
07-28 12:05:17.885  7098  7098 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
07-28 12:05:17.885  7098  7098 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
07-28 12:05:17.885  7098  7098 D dhcpcd  : wlan0: sending REQUEST (xid 0x1b4feda7), next in 3.55 seconds
,07-28 12:05:17.898  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-28 12:05:17.899  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:05:17.900  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:05:17.905  1816  7099 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
07-28 12:05:17.907  7098  7098 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,07-28 12:05:17.918   279   343 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-28 12:05:17.918   279   343 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
07-28 12:05:17.919   279   343 W Vold    : Returning OperationFailed - no handler for errno 0
07-28 12:05:17.919  7075  7110 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
07-28 12:05:17.920   279   343 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-28 12:05:17.920   279   343 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
07-28 12:05:17.920   279   343 W Vold    : Returning OperationFailed - no handler for errno 0
07-28 12:05:17.920  7075  7110 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
07-28 12:05:17.921  7098  7098 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
07-28 12:05:17.921  7098  7098 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
07-28 12:05:17.922  7098  7098 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
07-28 12:05:17.922  7098  7098 D dhcpcd  : wlan0: adding default route via 192.168.1.1
07-28 12:05:17.922  7098  7098 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
07-28 12:05:17.922  7098  7098 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
07-28 12:05:17.922  7098  7098 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
07-28 12:05:17.922  7098  7098 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,07-28 12:05:17.936   279   343 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-28 12:05:17.936   279   343 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
07-28 12:05:17.936   279   343 W Vold    : Returning OperationFailed - no handler for errno 0
,07-28 12:05:17.937  7075  7113 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
07-28 12:05:17.940   279   343 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-28 12:05:17.940   279   343 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
07-28 12:05:17.940   279   343 W Vold    : Returning OperationFailed - no handler for errno 0
07-28 12:05:17.940  7075  7113 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
07-28 12:05:17.995  1032  1047 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7127 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,07-28 12:05:18.034  7127  7127 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,07-28 12:05:18.034  7127  7127 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
07-28 12:05:18.054  7127  7127 I MultiDex: VM with version 2.1.0 has multidex support
07-28 12:05:18.055  7127  7127 I MultiDex: install
,07-28 12:05:18.055  7127  7127 I MultiDex: VM has multidex support, MultiDex support library is disabled.
07-28 12:05:18.062  7127  7127 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
07-28 12:05:18.123  7075  7075 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,07-28 12:05:18.130  7075  7075 I LibraryLoader: Loading: webviewchromium
,07-28 12:05:18.132  7075  7075 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 8181-8184)
07-28 12:05:18.133  7075  7075 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-28 12:05:18.137  7075  7075 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3aefc0f}
07-28 12:05:18.138  7075  7075 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-28 12:05:18.138  7075  7075 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
07-28 12:05:18.147  7075  7075 I BrowserStartupController: Initializing chromium process, renderers=0
07-28 12:05:18.148  7075  7075 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-28 12:05:18.161  7075  7075 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
07-28 12:05:18.161  7075  7075 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
07-28 12:05:18.161  7075  7075 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,07-28 12:05:18.178   329  2216 V AudioPolicyService: registerClient() client 0xb558a720, uid 10093
,07-28 12:05:18.180  7075  7172 W AudioManagerAndroid: Requires BLUETOOTH permission
07-28 12:05:18.183  7075  7075 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-28 12:05:18.183  7075  7075 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-28 12:05:18.183  7075  7075 I Adreno-EGL: Build Date: 12/12/14 금
07-28 12:05:18.183  7075  7075 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-28 12:05:18.183  7075  7075 I Adreno-EGL: Remote Branch: 
07-28 12:05:18.183  7075  7075 I Adreno-EGL: Local Patches: 
07-28 12:05:18.183  7075  7075 I Adreno-EGL: Reconstruct Branch: 
07-28 12:05:18.220  1032  7071 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,07-28 12:05:18.223  1032  7071 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
07-28 12:05:18.223  1032  7071 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
07-28 12:05:18.223  1032  7071 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
07-28 12:05:18.223  1032  7071 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
07-28 12:05:18.223  1032  7071 V DhcpStateMachine: Current State is mWaitBeforeStartState.
07-28 12:05:18.223  1032  7071 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
07-28 12:05:18.223  1032  7071 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
07-28 12:05:18.223  1032  7071 D DhcpStateMachine: RunningState
07-28 12:05:18.285  7075  7075 I NSApplication: Starting up...
,07-28 12:05:18.307  7127  7144 D LgDataFeature: LgDataFeature() Constructor: none
07-28 12:05:18.307  7127  7144 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-28 12:05:18.372  1032  1957 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7185 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
07-28 12:05:18.373  1032  1957 I ActivityManager: Killing 5820:com.android.vending/u0a44 (adj 15): empty #17
,07-28 12:05:18.439  7202  7202 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,07-28 12:05:18.460  1032  1885 W libprocessgroup: failed to open /acct/uid_10044/pid_5820/cgroup.procs: No such file or directory
,07-28 12:05:18.492  7202  7202 I dex2oat : dex2oat took 53.506ms (threads: 4)
,07-28 12:05:18.505  7185  7185 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-28 12:05:18.506  7127  7144 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-28 12:05:18.506  7127  7144 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-28 12:05:18.506  7127  7144 I Adreno-EGL: Build Date: 12/12/14 금
07-28 12:05:18.506  7127  7144 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-28 12:05:18.506  7127  7144 I Adreno-EGL: Remote Branch: 
07-28 12:05:18.506  7127  7144 I Adreno-EGL: Local Patches: 
07-28 12:05:18.506  7127  7144 I Adreno-EGL: Reconstruct Branch: 
,07-28 12:05:18.624  7127  7144 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-28 12:05:18.624  7127  7144 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-28 12:05:18.624  7127  7144 I Adreno-EGL: Build Date: 12/12/14 금
07-28 12:05:18.624  7127  7144 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-28 12:05:18.624  7127  7144 I Adreno-EGL: Remote Branch: 
07-28 12:05:18.624  7127  7144 I Adreno-EGL: Local Patches: 
07-28 12:05:18.624  7127  7144 I Adreno-EGL: Reconstruct Branch: 
,07-28 12:05:18.643  1032  1642 I art     : Explicit concurrent mark sweep GC freed 82478(4MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 1.730ms total 85.397ms
,07-28 12:05:18.707  1032  1886 D WifiServiceImplEx: setWifiEnabled: false pid=6524, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-28 12:05:18.707  1032  1886 D WifiService: setWifiEnabled: false pid=6524, uid=10118
07-28 12:05:18.707  1032  1886 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-28 12:05:18.714  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-28 12:05:18.714  1032  1538 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
07-28 12:05:18.714  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-28 12:05:18.714  1032  1032 D Ulp_jni : JNI:system_update. Event-4
07-28 12:05:18.715  1032  1538 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
07-28 12:05:18.715  1032  1538 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
07-28 12:05:18.715  1032  1538 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
07-28 12:05:18.716  1032  1538 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
07-28 12:05:18.716  1032  1538 E WifiStateMachine: WifiStateMachine: Leaving Connected state
07-28 12:05:18.716  1032  1538 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-28 12:05:18.716  1032  1538 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-28 12:05:18.717  1032  1538 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-28 12:05:18.717  1032  1538 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-28 12:05:18.720  1032  1538 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-28 12:05:18.720  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-28 12:05:18.720  6979  6979 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,07-28 12:05:18.723  1032  1537 D LGWifiP2pService: InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:18.723  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:18.723  1032  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-28 12:05:18.724  1032  1538 D WifiNative-wlan0: doBoolean: SET ps 1
07-28 12:05:18.724  1032  1538 D WifiNative-wlan0: SET ps 1: returned true
07-28 12:05:18.724  1032  7071 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:18.728   324   891 D CommandListener: Clearing all IP addresses on wlan0
07-28 12:05:18.730  7127  7144 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-28 12:05:18.730  7127  7144 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-28 12:05:18.730  7127  7144 I Adreno-EGL: Build Date: 12/12/14 금
07-28 12:05:18.730  7127  7144 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-28 12:05:18.730  7127  7144 I Adreno-EGL: Remote Branch: 
07-28 12:05:18.730  7127  7144 I Adreno-EGL: Local Patches: 
07-28 12:05:18.730  7127  7144 I Adreno-EGL: Reconstruct Branch: 
,07-28 12:05:18.777  1032  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
07-28 12:05:18.778  1032  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,07-28 12:05:18.780  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:18.780  1032  1032 D WifiHS20: hidePasspointNotification off =false
07-28 12:05:18.780  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:05:18.783  1032  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:05:18.783  1940  1940 V WfdStateTracker: handleWifiStateChangedEvent: 0
07-28 12:05:18.783  1032  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:05:18.783  1032  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:05:18.783  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:18.784  1032  1538 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
07-28 12:05:18.784  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:18.784  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-28 12:05:18.784  1032  1537 D LGWifiP2pService: InactiveState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:18.784  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:18.784  1032  1537 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2f1b9392
07-28 12:05:18.784  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:05:18.784  1032  1537 D LGWifiP2pService: P2pDisablingState
07-28 12:05:18.785  1032  1537 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:18.785  1032  1537 D LGWifiP2pService: p2p socket connection lost
07-28 12:05:18.785  1032  1537 D LGWifiP2pService: P2pDisabledState
07-28 12:05:18.786  1032  1032 D WifiHS20: hidePasspointNotification off =false
07-28 12:05:18.786  1032  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
07-28 12:05:18.786  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-28 12:05:18.787  6979  6979 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-28 12:05:18.787  1032  1537 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:18.787  1032  1537 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:18.787  1032  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-28 12:05:18.787  1032  1538 D WifiNative-wlan0: doBoolean: SET ps 1
07-28 12:05:18.788  1032  1538 D WifiNative-wlan0: SET ps 1: returned true
07-28 12:05:18.790  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:18.790  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:18.790  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-28 12:05:18.790  1032  1032 D WifiScanningService: SCAN_AVAILABLE : 1
,07-28 12:05:18.792  1032  1556 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:18.793  1032  1032 D RttService: SCAN_AVAILABLE : 1
07-28 12:05:18.793  1032  1557 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:18.797  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
07-28 12:05:18.797  1940  1940 D WfdsService: WifiP2pState is changed : false
07-28 12:05:18.797  1940  2302 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
07-28 12:05:18.797  1940  2302 D WfdsService: Set the WFDS Monitor: false
07-28 12:05:18.798  1940  2302 D WfdsMonitor: WFDS Monitor is stopped
07-28 12:05:18.798  1940  2302 D WfdsService: STATE : WfdsDisabledState - enter
07-28 12:05:18.798  1940  2304 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
07-28 12:05:18.798  1940  7015 D CtrlSupplicant: Received on exit socket, terminate
07-28 12:05:18.798  1940  7015 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
07-28 12:05:18.798  1940  7015 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
07-28 12:05:18.799  1940  7015 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
07-28 12:05:18.799  1940  2302 W WfdsService: DefaultState - msg [9445378] is not handled
,07-28 12:05:18.811  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:18.811  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:05:18.813  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:05:18.829   324   891 D CommandListener: Clearing all IP addresses on wlan0
07-28 12:05:18.829  1032  1545 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
07-28 12:05:18.829  1032  1545 D DSQN    : disableDataServiceNotify
07-28 12:05:18.829  1032  1545 D DSQN    : stop dsqn bin
07-28 12:05:18.830  1032  1538 D WifiNative-p2p0: doBoolean: TERMINATE
07-28 12:05:18.831  1032  1538 D WifiNative-p2p0: TERMINATE: returned true
07-28 12:05:18.831  1032  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-28 12:05:18.831  1032  1538 E WifiStateMachine: useWiFiOffloading() : false
07-28 12:05:18.831  1032  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-28 12:05:18.832  1032  1032 D WifiHS20: hidePasspointNotification off =false
,07-28 12:05:18.833  1032  1545 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
07-28 12:05:18.833  1032  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:05:18.833  1032  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:05:18.834  1032  1545 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:05:18.834  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-28 12:05:18.834  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:05:18.835  6338  6338 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
07-28 12:05:18.836  6338  6374 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
07-28 12:05:18.839  1032  1545 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
07-28 12:05:18.839  1032  7070 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:18.839  1032  7070 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:18.839  1032  7070 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
07-28 12:05:18.839  1032  1545 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
07-28 12:05:18.839  1032  1545 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
07-28 12:05:18.839  1032  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-28 12:05:18.844  1602  2072 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
07-28 12:05:18.845  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:05:18.846  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:18.846  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:18.846  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,07-28 12:05:18.848  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
07-28 12:05:18.852  1032  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-28 12:05:18.853  1032  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-28 12:05:18.853  1032  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-28 12:05:18.853  1032  1545 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:05:18.853  1032  1545 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:05:18.853  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
07-28 12:05:18.853  1032  1545 D NetworkManagementService: Removing idletimer
07-28 12:05:18.853  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 12:05:18.853  1032  1545 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:18.853  1032  1032 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
07-28 12:05:18.853  1032  1545 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
07-28 12:05:18.853  1032  1545 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
07-28 12:05:18.854  1032  1538 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:05:18.854  1032  1538 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:05:18.854  1032  1536 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
07-28 12:05:18.855  1851  1851 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:05:18.855  1851  1851 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-28 12:05:18.855  6524  6524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:05:18.855  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:05:18.855  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:05:18.855  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:18.855  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:05:18.855  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:05:18.855  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:05:18.855  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:05:18.855  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:05:18.855  6524  6524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:05:18.855  6524  6524 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:05:18.858  1032  1032 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
07-28 12:05:18.859  1032  1032 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-28 12:05:18.859  1032  1032 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-28 12:05:18.859  1032  1032 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-28 12:05:18.859  1032  1536 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
07-28 12:05:18.859  1032  1032 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
07-28 12:05:18.859  1032  1032 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-28 12:05:18.859  1032  1032 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-28 12:05:18.859  1032  1032 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-28 12:05:18.859  6524  6524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:05:18.859  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:05:18.859  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:05:18.859  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:18.859  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:05:18.859  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:05:18.859  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:05:18.859  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:05:18.859  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:05:18.860  6524  6524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:05:18.860  6524  6524 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:05:18.864  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:05:18.880  2126  2126 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:05:18.891  6920  6920 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
07-28 12:05:18.891  6920  6920 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
07-28 12:05:18.892  6920  6920 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-28 12:05:18.892  6920  6920 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
07-28 12:05:18.894  6920  6920 I AppUp4:CustModeStarterReceiver: onReceive
07-28 12:05:18.897  6920  6920 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2e3ae2d4
07-28 12:05:18.897  6920  6920 D AppUp4:CustFacade: isCustomizationCompleted : false
07-28 12:05:18.897  6920  6920 D AppUp4:CustFacade: isPhone : true
07-28 12:05:18.897  6920  6920 D AppUp4:CustModeStarterReceiver: begin check event
07-28 12:05:18.897  6920  6920 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
07-28 12:05:18.901  4323  4323 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
07-28 12:05:18.901  4323  4323 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-28 12:05:18.904  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-28 12:05:18.904  4323  4323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 12:05:18.905  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:05:18.905  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:05:18.908  4323  4323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 12:05:18.913  4323  7235 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-28 12:05:18.916  6944  6944 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
07-28 12:05:18.919  6979  6979 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
07-28 12:05:18.919  6979  6979 I wpa_supplicant: monitor socket send errors count : 1
07-28 12:05:18.919  6979  6979 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1940-4\x00 that cannot receive messages
07-28 12:05:18.920  1032  7014 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
07-28 12:05:18.920  1032  7014 D WifiMonitor: Dropping event because (p2p0) is stopped
07-28 12:05:18.922  4323  7236 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:05:18.922  4323  7236 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-28 12:05:18.933  6944  7238 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:18.933  1032  7071 D DhcpStateMachine: StoppedState
07-28 12:05:18.934  1032  7071 D DhcpStateMachine: StoppedState{ when=-145ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:18.934  1032  1538 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
07-28 12:05:18.934  1032  1538 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,07-28 12:05:18.936  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-28 12:05:18.937  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:05:18.937  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:05:18.946  3454  3454 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
07-28 12:05:18.946  3454  3454 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
07-28 12:05:18.946  3454  3454 I LgeMiscReceiver: networkInfo.isConnected() = false
,07-28 12:05:18.949  6997  6997 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,07-28 12:05:18.949  6997  6997 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
07-28 12:05:18.951  6822  7240 W FormManager: Network not available. Please check & try again.
07-28 12:05:18.954  6979  6979 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-28 12:05:18.954  6979  6979 W wpa_supplicant: USIM:  scard_deinit function
07-28 12:05:18.955  1032  7014 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
07-28 12:05:18.955  1032  7014 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-28 12:05:18.955  1032  7014 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-28 12:05:18.955  1032  7014 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
,07-28 12:05:18.955  1032  7014 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-28 12:05:18.955  1032  7014 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-28 12:05:18.956  1032  1538 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=138994
07-28 12:05:18.956  1032  1538 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=138994
07-28 12:05:18.956  1032  1538 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=138994  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
07-28 12:05:18.957  1032  1538 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=138995  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
07-28 12:05:18.957  1032  1097 D Tethering: InitialState.processMessage what=4
07-28 12:05:18.959  7053  7053 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:5:18
07-28 12:05:18.959  1032  1097 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
07-28 12:05:18.960  6822  7241 V FormManager: Network unavailable.
,07-28 12:05:18.962  1032  1538 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:05:18.962  1032  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:05:18.968  6822  7241 V FormManager: Network unavailable.
07-28 12:05:18.969  7053  7053 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
07-28 12:05:18.969  7053  7053 D Weather.Utils: 2 : All the weather widget is gone.
07-28 12:05:18.969  7053  7053 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-28 12:05:18.969  7053  7053 D WeatherAncestor: connectivity changed - connection : true
07-28 12:05:18.969  7053  7053 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@289ea772
07-28 12:05:18.970  7053  7053 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
07-28 12:05:18.970  7053  7053 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
07-28 12:05:18.970  7053  7053 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
07-28 12:05:18.970  7053  7053 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-28 12:05:18.970  7053  7053 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:5:18
07-28 12:05:18.988  6720  6720 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-28 12:05:18.988  6720  6720 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-28 12:05:18.988  6720  6720 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-28 12:05:18.988  6720  6720 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,07-28 12:05:18.988  6720  6720 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,07-28 12:05:18.989  6720  6720 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-28 12:05:18.989  6720  6720 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
07-28 12:05:18.989  6720  6720 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-28 12:05:18.989  6720  6720 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-28 12:05:18.989  6720  6720 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-28 12:05:18.989  6720  6720 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-28 12:05:18.995  6737  6737 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-28 12:05:18.997  6720  6720 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-28 12:05:18.999  6822  7244 W FormManager: Network not available. Please check & try again.
,07-28 12:05:19.003  6720  6720 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:05:19.004  6822  7245 V FormManager: Network unavailable.
07-28 12:05:19.010  6822  7245 V FormManager: Network unavailable.
07-28 12:05:19.019  6737  6737 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-28 12:05:19.022  6720  6720 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-28 12:05:19.024  6822  7247 W FormManager: Network not available. Please check & try again.
07-28 12:05:19.025  6822  7248 V FormManager: Network unavailable.
07-28 12:05:19.027  6822  7248 V FormManager: Network unavailable.
07-28 12:05:19.032  6720  6720 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-28 12:05:19.041  4323  4323 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
07-28 12:05:19.041  4323  4323 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-28 12:05:19.042  4323  4323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 12:05:19.043  4323  4323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,07-28 12:05:19.046  6338  6338 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:05:19.048  4323  7249 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-28 12:05:19.050  6720  6720 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-28 12:05:19.053  4323  7250 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
07-28 12:05:19.053  4323  7250 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-28 12:05:19.053  6720  6720 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:05:19.061  6782  6782 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-28 12:05:19.061  6782  6782 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:05:19.062  6782  6782 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-28 12:05:19.089  6979  6979 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
07-28 12:05:19.089  1032  7014 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
07-28 12:05:19.089  1032  7014 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
07-28 12:05:19.089  1032  7014 D WifiMonitor: Disconnecting from the supplicant, no more events
07-28 12:05:19.090  1032  1538 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
,07-28 12:05:19.107  1032  1886 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7251 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,07-28 12:05:19.140   324  7269 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
07-28 12:05:19.140  1032  1095 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,07-28 12:05:19.144  1816  7099 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
07-28 12:05:19.151  1816  7099 I CheckinService: active receiver: disabled
,07-28 12:05:19.191  1032  1538 D WifiOffDelayIfNotUsed: stopMonitoring
07-28 12:05:19.192  1032  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-28 12:05:19.192  1032  1538 E WifiStateMachine: useWiFiOffloading() : false
07-28 12:05:19.192  1032  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,07-28 12:05:19.195  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:05:19.195  1940  1940 D WfdsService: Supplicant Connection state is changed : false
07-28 12:05:19.195  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
07-28 12:05:19.195  1940  2302 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
07-28 12:05:19.195  1940  2302 D WfdsService: Set the WFDS Monitor: false
07-28 12:05:19.195  1940  2302 D WfdsMonitor: WFDS Monitor is stopped
07-28 12:05:19.196  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
07-28 12:05:19.196  1032  1542 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
07-28 12:05:19.197  1032  1542 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
07-28 12:05:19.198  2455  2455 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:19.198  6524  6524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:05:19.198  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:05:19.198  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:05:19.198  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:19.198  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:05:19.198  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:05:19.198  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:05:19.198  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:05:19.198  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:05:19.200  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:19.212  7251  7251 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
07-28 12:05:19.212  7251  7251 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,07-28 12:05:19.224  7251  7251 V [BNRBootReceiver]: Boot Receiver Return
,07-28 12:05:19.225  7251  7251 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-28 12:05:19.229  6720  6720 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
07-28 12:05:19.232  6720  6720 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
07-28 12:05:19.238  6338  6338 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-28 12:05:19.249  6720  6720 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:05:19.256  6720  6720 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:05:19.263  6782  6782 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:05:19.264  6782  6782 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-28 12:05:19.265  6782  6782 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,07-28 12:05:19.270  6338  6338 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:05:19.278  6720  6720 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:05:19.288  6720  6720 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-28 12:05:19.294  6636  6893 D UEI.SmartControl: Internal timer expired: 2
07-28 12:05:19.294  6636  6893 D UEI.SmartControl: unbind internal service
,07-28 12:05:19.298  6782  6782 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:05:19.299  6782  6782 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:05:19.300  6782  6782 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-28 12:05:19.307  6338  6338 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-28 12:05:19.324  6720  6720 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:05:19.336  6720  6720 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-28 12:05:19.350  6782  6782 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:05:19.351  6782  6782 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-28 12:05:19.352  6782  6782 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-28 12:05:19.362  6338  6338 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:05:19.376  6720  6720 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:05:19.384  6720  6720 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-28 12:05:19.393  6782  6782 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:05:19.394  6782  6782 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:05:19.394  6782  6782 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-28 12:05:19.397  6338  6338 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:05:19.405  6720  6720 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:05:19.415  6720  6720 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:05:19.427  6782  6782 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-28 12:05:19.427  6782  6782 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:05:19.428  6782  6782 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-28 12:05:19.430  6338  6338 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:05:19.441  6720  6720 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:05:19.450  6720  6720 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:05:19.460  6782  6782 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:05:19.460  6782  6782 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-28 12:05:19.460  6782  6782 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-28 12:05:19.469  6338  6338 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:05:19.477  6636  6890 D serial_port: close(fd = 24)
07-28 12:05:19.483  6636  6890 I UEI.SmartControl: Serial port is closed.
,07-28 12:05:19.491  6720  6720 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-28 12:05:19.497  6720  6720 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-28 12:05:19.505  6782  6782 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:05:19.506  6782  6782 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:05:19.514  6782  6782 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,07-28 12:05:19.523  6338  6338 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:05:19.536  6720  6720 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:05:19.546  6720  6720 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-28 12:05:19.553  6782  6782 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:05:19.553  6782  6782 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:05:19.554  6782  6782 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,07-28 12:05:19.558  6338  6338 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-28 12:05:19.564  6737  6737 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
07-28 12:05:19.581  1032  1544 D WifiService: New client listening to asynchronous messages
,07-28 12:05:19.582  6737  6737 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-28 12:05:19.592  6720  6720 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:05:19.611  6720  6720 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:05:19.621  6782  6782 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:05:19.622  6782  6782 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-28 12:05:19.625  6782  6782 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
07-28 12:05:19.627  6782  6782 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
07-28 12:05:19.628  6782  6782 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
07-28 12:05:19.635  6338  6338 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-28 12:05:19.641  6737  6737 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
07-28 12:05:19.643  6737  6737 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-28 12:05:19.648  6720  6720 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:05:19.656  6720  6720 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:05:19.669  6782  6782 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-28 12:05:19.670  6782  6782 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:05:19.671  6782  6782 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,07-28 12:05:19.672  6782  6782 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,07-28 12:05:19.673  6782  6782 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
07-28 12:05:19.681  1032  2037 I ActivityManager: Killing 6758:com.lge.lifetracker/u0a37 (adj 15): empty #17
07-28 12:05:19.833  1032  1575 W libprocessgroup: failed to open /acct/uid_10037/pid_6758/cgroup.procs: No such file or directory
,07-28 12:05:19.842  2126  2126 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
07-28 12:05:19.859  2126  2126 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,07-28 12:05:19.862  2126  2126 D c       : Getting all permits...
07-28 12:05:19.862  2126  2126 D a       : Opening database...
07-28 12:05:19.866  2126  2126 D a       : Opening database auth.proximity.permit_store...
07-28 12:05:19.867  2126  2126 D a       : Closing database...
07-28 12:05:19.885  6338  6338 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-28 12:05:19.894  6737  6737 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-28 12:05:19.894  6737  6737 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-28 12:05:19.894  6737  6737 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-28 12:05:19.899  6720  6720 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:05:19.908  6720  6720 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:05:19.916  6782  6782 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:05:19.917  6782  6782 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-28 12:05:19.921  6782  6782 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-28 12:05:19.926  6338  6338 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:05:19.931  6737  6737 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-28 12:05:19.931  6737  6737 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-28 12:05:19.931  6737  6737 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-28 12:05:19.938  6720  6720 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:05:19.945  6720  6720 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:05:19.953  6782  6782 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:05:19.953  6782  6782 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:05:19.955  6782  6782 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,07-28 12:05:19.961  6338  6338 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:05:19.966  6737  6737 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-28 12:05:19.966  6737  6737 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-28 12:05:19.966  6737  6737 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-28 12:05:19.973  6720  6720 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:05:19.981  6720  6720 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:05:19.989  6782  6782 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:05:19.989  6782  6782 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-28 12:05:19.992  6782  6782 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-28 12:05:20.000  6737  6737 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-28 12:05:20.003  6720  6720 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:05:20.010  6720  6720 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:05:20.029  2126  2126 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
07-28 12:05:20.036  6822  7289 W FormManager: Network not available. Please check & try again.
,07-28 12:05:20.041  6822  7294 V FormManager: Network unavailable.
07-28 12:05:20.043  6822  7294 V FormManager: Network unavailable.
07-28 12:05:20.047  4323  4323 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
07-28 12:05:20.047  4323  4323 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-28 12:05:20.049  4323  4323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,07-28 12:05:20.051  4323  4323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 12:05:20.058  6737  6737 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
07-28 12:05:20.058  6737  6737 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-28 12:05:20.058  6737  6737 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-28 12:05:20.060  4323  7297 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-28 12:05:20.062  6720  6720 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:05:20.065  6822  7299 W FormManager: Network not available. Please check & try again.
07-28 12:05:20.066  4323  7301 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
07-28 12:05:20.068  4323  7301 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-28 12:05:20.068  6822  7300 V FormManager: Network unavailable.
07-28 12:05:20.070  6720  6720 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:05:20.080  6822  7300 V FormManager: Network unavailable.
,07-28 12:05:20.596  1032  1538 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:821505364] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-28 12:05:20.601  1032  1538 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:5] from screen [on:0 period:821505369] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-28 12:05:20.787  1032  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:05:20.803  1032  1097 D Tethering: MasterInitialState.processMessage what=3
07-28 12:05:20.810  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:05:20.813  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:20.818  1032  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-28 12:05:20.821  6338  6338 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,07-28 12:05:20.826  6338  6374 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
07-28 12:05:20.839  5792  5792 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,07-28 12:05:20.857  2126  2126 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:05:20.889  1032  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:20.902  6920  6920 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
07-28 12:05:20.902  6920  6920 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
07-28 12:05:20.903  6920  6920 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-28 12:05:20.903  6920  6920 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,07-28 12:05:20.907  6920  6920 I AppUp4:CustModeStarterReceiver: onReceive
07-28 12:05:20.911  6920  6920 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2e3ae2d4
07-28 12:05:20.911  6920  6920 D AppUp4:CustFacade: isCustomizationCompleted : false
07-28 12:05:20.911  6920  6920 D AppUp4:CustFacade: isPhone : true
07-28 12:05:20.913  6920  6920 D AppUp4:CustModeStarterReceiver: begin check event
07-28 12:05:20.913  6920  6920 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
07-28 12:05:20.917  4323  4323 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
07-28 12:05:20.918  4323  4323 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,07-28 12:05:20.922  4323  4323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 12:05:20.925  4323  4323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 12:05:20.932  6944  6944 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,07-28 12:05:20.952  4323  7324 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,07-28 12:05:20.960  4323  7326 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
07-28 12:05:20.960  4323  7326 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-28 12:05:20.961  3454  3454 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
07-28 12:05:20.961  3454  3454 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
07-28 12:05:20.961  3454  3454 I LgeMiscReceiver: networkInfo.isConnected() = true
07-28 12:05:20.961  3454  3454 D PhoneState: setPdpRejectCasuse : false
07-28 12:05:20.968  6997  6997 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) },
07-28 12:05:20.969  6997  6997 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,07-28 12:05:20.982  6944  7330 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-28 12:05:20.986  7053  7053 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:5:20
07-28 12:05:20.990  7053  7053 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
07-28 12:05:20.990  7053  7053 D Weather.Utils: 2 : All the weather widget is gone.
07-28 12:05:20.990  7053  7053 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-28 12:05:20.990  7053  7053 D WeatherAncestor: connectivity changed - connection : true
07-28 12:05:20.990  7053  7053 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@289ea772
07-28 12:05:20.991  7053  7053 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
07-28 12:05:20.991  7053  7053 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
07-28 12:05:20.991  7053  7053 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
07-28 12:05:20.991  7053  7053 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-28 12:05:20.991  7053  7053 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:5:20
07-28 12:05:20.991  6822  7331 W FormManager: Network not available. Please check & try again.
07-28 12:05:20.999  6822  7332 V FormManager: Network unavailable.
,07-28 12:05:21.008  6822  7332 V FormManager: Network unavailable.
,07-28 12:05:21.716  1032  1642 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-28 12:05:21.717  1032  1642 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,07-28 12:05:21.744  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-28 12:05:21.744  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-28 12:05:21.744  1032  1032 D Ulp_jni : JNI:system_update. Event-4
,07-28 12:05:21.747  1032  1097 D BluetoothManagerService: Message: 1
07-28 12:05:21.747  1032  1097 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,07-28 12:05:21.778  1032  1097 D BluetoothManagerService: Message: 20
07-28 12:05:21.778  1032  1097 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@194699b7:true
,07-28 12:05:21.781  6868  6868 D BluetoothAdapterState: make
07-28 12:05:21.786  6868  6868 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
07-28 12:05:21.786  6868  6868 I bluedroid-qcom: init
07-28 12:05:21.787  6868  7340 I BluetoothAdapterState: Entering OffState
07-28 12:05:21.788  6868  6868 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
07-28 12:05:21.789  6868  6868 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-28 12:05:21.789  6868  6868 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-28 12:05:21.789  6868  6868 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-28 12:05:21.789  6868  6868 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
07-28 12:05:21.791  6868  6868 I bluedroid-qcom: get_profile_interface socket
07-28 12:05:21.791  6868  6868 I bluedroid-qcom: get_profile_interface map_client
,07-28 12:05:21.795  6868  7344 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
07-28 12:05:21.785  7343  7343 W bdaddr_loader: type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:05:21.795  7343  7343 W bdaddr_loader: type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:05:21.813  7343  7343 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
07-28 12:05:21.813  7343  7343 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
07-28 12:05:21.813  7343  7343 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,07-28 12:05:21.816  7343  7343 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
07-28 12:05:21.820  1032  1032 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
07-28 12:05:21.821  7343  7343 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
07-28 12:05:21.821  7343  7343 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
07-28 12:05:21.821  1032  1097 D BluetoothManagerService: Message: 40
07-28 12:05:21.823  1032  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
07-28 12:05:21.824  6868  6883 I bluedroid-qcom: config_hci_snoop_log
07-28 12:05:21.825  1032  1097 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
07-28 12:05:21.825  1032  1097 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,07-28 12:05:21.833  6868  7340 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
07-28 12:05:21.833  6868  7340 D BluetoothAdapterProperties: Setting state to 11
07-28 12:05:21.833  6868  7340 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
07-28 12:05:21.836  6868  7340 I LGBluetoothServiceJni: classInitNative: succeeds
07-28 12:05:21.840  6868  7344 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,07-28 12:05:21.842  1032  1097 D BluetoothManagerService: Message: 60
07-28 12:05:21.842  1032  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
07-28 12:05:21.842  1032  1097 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
07-28 12:05:21.848  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:21.849  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-28 12:05:21.852  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:05:21.854  1032  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-28 12:05:21.855  6868  7344 D BluetoothAdapterProperties: Name is: G3
07-28 12:05:21.856  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:21.859  6720  6720 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
07-28 12:05:21.862  1032  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-28 12:05:21.867  6868  6868 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-28 12:05:21.868  6868  6868 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:21.868  6868  6868 V BluetoothPbapReceiver: ***********state = 11
,07-28 12:05:21.880  1032  1032 D BluetoothManagerService: Bluetooth Adapter name changed to G3
,07-28 12:05:21.883  1032  1032 D BluetoothManagerService: Stored Bluetooth name: G3
07-28 12:05:21.883  1032  1097 D Tethering: MasterInitialState.processMessage what=3
07-28 12:05:21.884  1032  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-28 12:05:21.887  1032  1097 D Tethering: MasterInitialState.processMessage what=3
07-28 12:05:21.889  6868  7340 D BluetoothBondStateMachine: make
07-28 12:05:21.892  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:21.893  6868  7359 I BluetoothBondStateMachine: StableState(): Entering Off State
07-28 12:05:21.893  6868  7340 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@289ea772
07-28 12:05:21.893  6868  7340 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
07-28 12:05:21.893  6868  7340 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@289ea772
07-28 12:05:21.893  6868  7340 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
07-28 12:05:21.896  6868  7340 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
07-28 12:05:21.896  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:05:21.901  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:21.902  6338  6338 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
07-28 12:05:21.903  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:21.904  6868  7340 E BluetoothAdapterService: File transfer profiles supported!!
07-28 12:05:21.905  6338  6374 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
07-28 12:05:21.907  2126  2126 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-28 12:05:21.916  6868  7340 E BluetoothAdapterService: File transfer profiles supported!!
,07-28 12:05:21.918  6868  6868 D HeadsetService: Received start request. Starting profile...
07-28 12:05:21.919  6868  6868 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
07-28 12:05:21.919  6868  6868 D LGBluetoothHfpAdapter: Version 1.6
07-28 12:05:21.922  6868  6868 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-28 12:05:21.923  6868  7340 E BluetoothAdapterService: File transfer profiles supported!!
07-28 12:05:21.923  1032  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-28 12:05:21.923  6868  6868 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-28 12:05:21.924  6868  6868 D HeadsetStateMachine: make
07-28 12:05:21.925  5792  5792 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,07-28 12:05:21.960  6868  6868 D LgDataFeature: LgDataFeature() Constructor: none
07-28 12:05:21.960  6868  6868 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-28 12:05:21.969  1032  1048 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7365 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
07-28 12:05:21.975  6868  6868 D HeadsetStateMachine: max_hf_connections = 1
07-28 12:05:21.975  6868  6868 I bluedroid-qcom: get_profile_interface handsfree
07-28 12:05:21.977  6868  6868 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
07-28 12:05:21.979   329  1386 V AudioPolicyService: registerClient() client 0xb558a3e0, uid 1002
07-28 12:05:21.979   350   350 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 388us total 17.810ms
07-28 12:05:21.979   329  1387 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
07-28 12:05:21.979   329  1387 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-28 12:05:21.979   329  1387 V AudioPolicyManagerEx: getOutput() returns output 2
07-28 12:05:21.980  6868  6868 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
07-28 12:05:21.980   329  2216 V AudioFlinger: registerClient() client 0xb1433688, pid 6868
07-28 12:05:21.981  5792  5792 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,07-28 12:05:21.981  1032  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:21.981  1032  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:21.982   329  1382 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 12:05:21.982   329  1382 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-28 12:05:21.983   329  1381 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 12:05:21.983   329  1381 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-28 12:05:21.983  6868  6884 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 12:05:21.983  1851  1866 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 12:05:21.983  1851  1866 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-28 12:05:21.983  1851  1866 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 12:05:21.983  1851  1866 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-28 12:05:21.984  1032  1886 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 12:05:21.985  1032  1886 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-28 12:05:21.985  1032  1886 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 12:05:21.985  1032  1886 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-28 12:05:21.986  6868  7340 E BluetoothAdapterService: File transfer profiles supported!!
07-28 12:05:21.986  3454  3471 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 12:05:21.986  3454  3471 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-28 12:05:21.986  3454  3471 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 12:05:21.986  3454  3471 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-28 12:05:21.986  6868  6868 V ToneGenerator: Create Track: 0xb4928a80
07-28 12:05:21.986  6868  6884 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
07-28 12:05:21.986  6868  6868 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
07-28 12:05:21.986  6868  6868 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
07-28 12:05:21.986  6868  6884 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 12:05:21.987  6868  6884 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
07-28 12:05:21.987   329  2215 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
07-28 12:05:21.987   329  2215 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
07-28 12:05:21.987   329  2215 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-28 12:05:21.987   329  2215 V AudioPolicyManagerEx: getOutput() returns output 2
07-28 12:05:21.987  1602  1625 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 12:05:21.987  1602  1625 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-28 12:05:21.987  1602  1625 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 12:05:21.987  1602  1625 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-28 12:05:21.988   329  1386 I AudioFlinger: isAudioPlaybackHookOn() false
07-28 12:05:21.988   329  1387 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
07-28 12:05:21.988   329  1387 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
07-28 12:05:21.,988   329  1387 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-28 12:05:21.988   329  1387 V AudioPolicyManagerEx: getOutput() returns output 2
07-28 12:05:21.988  6868  6868 V AudioSystem: getLatency() output 2, latency 50
07-28 12:05:21.988  6868  6868 V AudioSystem: getFrameCount() output 2, frameCount 960
07-28 12:05:21.988  6868  6868 V AudioTrack: createTrack_l() output 2 afLatency 50
07-28 12:05:21.989   329  2216 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
07-28 12:05:21.989   329  2216 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
07-28 12:05:21.989   329  2216 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
07-28 12:05:21.989   329  2216 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
07-28 12:05:21.989   329  2216 V AudioFlinger: createTrack() lSessionId: 22
07-28 12:05:21.992  6868  6868 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
07-28 12:05:21.992   329   329 V AudioFlinger: acquiring 22 from 6868, for 6868
,07-28 12:05:21.992   329   329 V AudioFlinger:  added new entry for 22
07-28 12:05:21.992  6868  6868 V ToneGenerator: ToneGenerator INIT OK, time: 142044
07-28 12:05:21.992  6868  6868 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@289ea772
07-28 12:05:21.993  6868  7340 E BluetoothAdapterService: File transfer profiles supported!!
07-28 12:05:21.995  6868  6868 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@289ea772
07-28 12:05:21.995   350   350 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 334us total 15.513ms
07-28 12:05:21.997  6868  6868 D A2dpService: Received start request. Starting profile...
07-28 12:05:21.998  6868  6868 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-28 12:05:21.999  6868  6868 V Avrcp   : make
07-28 12:05:22.000  6868  6868 D Avrcp   : [BTUI] Use Native AVRCP : init jni
07-28 12:05:22.000  6868  6868 I bluedroid-qcom: get_profile_interface avrcp
07-28 12:05:22.000  6868  7363 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
07-28 12:05:22.000  6868  7363 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-28 12:05:22.000  6868  7363 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-28 12:05:22.000  6868  7363 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
07-28 12:05:22.002   329  2216 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6868
07-28 12:05:22.003   329  2216 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
07-28 12:05:22.003   329  2216 V voice   : voice_set_parameters: enter: bt_samplerate=8000
07-28 12:05:22.003   329  2216 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
07-28 12:05:22.003   329  2216 V compress_voip: voice_extn_compress_voip_set_parameters: exit
07-28 12:05:22.003   329  2216 V voice   : voice_set_parameters: exit with code(0)
07-28 12:05:22.003   329  2216 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
07-28 12:05:22.003   329  2216 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
07-28 12:05:22.003   329  2216 V msm8974_platform: platform_set_parameters: exit with code(0)
07-28 12:05:22.003   329  2216 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
07-28 12:05:22.003   329  2216 V audio_hw_primary: adev_set_parameters: exit with code(0)
07-28 12:05:22.003   329  2216 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
07-28 12:05:22.004  6868  7363 V ToneGenerator: ToneGenerator destructor
07-28 12:05:22.004  6868  7363 V ToneGenerator: stopTone
07-28 12:05:22.004  6868  7363 V ToneGenerator: Delete Track: 0xb4928a80
,07-28 12:05:22.006  6868  7363 V AudioTrack: ~AudioTrack, releasing session id from 6868 on behalf of 6868
07-28 12:05:22.006   329  2215 V AudioFlinger: releasing 22 from 6868 for 6868
07-28 12:05:22.006   329  2215 V AudioFlinger:  decremented refcount to 0
07-28 12:05:22.006   329  2215 V AudioFlinger: purging stale effects
07-28 12:05:22.006   329  2215 V AudioPolicyService: AudioCommandThread() adding release output 2
07-28 12:05:22.007   329  2215 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
07-28 12:05:22.007   329  1105 V AudioPolicyService: AudioCommandThread() waking up
07-28 12:05:22.007   329  1105 V AudioPolicyService: AudioCommandThread() processing release output 2
07-28 12:05:22.007   329  1105 V AudioPolicyManager: releaseOutput() 2
07-28 12:05:22.007   329  1105 V AudioPolicyService: AudioCommandThread() going to sleep
07-28 12:05:22.007   329  2215 V AudioFlinger: PlaybackThread::Track destructor
07-28 12:05:22.007   329  2215 V AudioFlinger: removeClient_l() pid 6868, calling pid 329
07-28 12:05:22.007  6868  7340 E BluetoothAdapterService: File transfer profiles supported!!
07-28 12:05:22.010   350   350 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 285us total 13.038ms
07-28 12:05:22.011  6868  6868 V AudioManager: registerRemoteController: size of Media player list: 0
07-28 12:05:22.013  6868  6868 E AudioManager: No RCC entry present to update
07-28 12:05:22.013  6868  6868 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
07-28 12:05:22.015  6868  7340 E BluetoothAdapterService: File transfer profiles supported!!
07-28 12:05:22.015  6868  6868 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
07-28 12:05:22.016  6868  6868 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
07-28 12:05:22.016  6868  6868 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
,07-28 12:05:22.020  6868  6868 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
07-28 12:05:22.029  6868  7340 V LGMDMManager: Create singleton instance
07-28 12:05:22.031  6868  7340 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,07-28 12:05:22.058  2126  2126 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:05:22.068  6920  6920 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
07-28 12:05:22.068  6920  6920 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
07-28 12:05:22.068  6920  6920 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-28 12:05:22.068  6920  6920 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
07-28 12:05:22.070  6920  6920 I AppUp4:CustModeStarterReceiver: onReceive
,07-28 12:05:22.072  6920  6920 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2e3ae2d4
07-28 12:05:22.072  6920  6920 D AppUp4:CustFacade: isCustomizationCompleted : false
07-28 12:05:22.072  6920  6920 D AppUp4:CustFacade: isPhone : true
07-28 12:05:22.072  6920  6920 D AppUp4:CustModeStarterReceiver: begin check event
07-28 12:05:22.073  6920  6920 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
07-28 12:05:22.079  4323  4323 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
07-28 12:05:22.079  4323  4323 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-28 12:05:22.080  4323  4323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 12:05:22.081  4323  4323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 12:05:22.085  4323  7386 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,07-28 12:05:22.091  4323  7387 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
07-28 12:05:22.091  6944  6944 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
07-28 12:05:22.091  4323  7387 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-28 12:05:22.102  1032  2037 V SIM_STK : Menu title from STK is T-Mobile
07-28 12:05:22.102  1032  2037 V SIM_STK : Menu title from STK is T-Mobile
,07-28 12:05:22.111  3454  3454 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
07-28 12:05:22.111  3454  3454 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:05:22.111  3454  3454 I LgeMiscReceiver: networkInfo.isConnected() = false
07-28 12:05:22.115  6997  6997 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
07-28 12:05:22.116  6944  7392 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:22.117  6997  6997 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
07-28 12:05:22.117  6822  7391 W FormManager: Network not available. Please check & try again.
07-28 12:05:22.121  7365  7365 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,07-28 12:05:22.122  7365  7365 W LG Account v2.2: No ProfileInfo entries
07-28 12:05:22.122  7365  7365 I LG Account v2.2: isEnabled: false
07-28 12:05:22.122  7365  7365 I Feature : [Lifetracker]ver: 4.21.112(40211120)
07-28 12:05:22.122  7365  7365 I Feature : [Lifetracker]Country: EU
07-28 12:05:22.122  7365  7365 I Feature : [Lifetracker]Operator: OPEN
07-28 12:05:22.122  7365  7365 I Feature : [Lifetracker]Ranking support: false
07-28 12:05:22.122  7365  7365 I Feature : [Lifetracker]Comfort support: false
07-28 12:05:22.122  7365  7365 I Feature : [Lifetracker]Accessory: true
07-28 12:05:22.122  7365  7365 I Feature : [Lifetracker]Health device: true
07-28 12:05:22.122  7365  7365 I Feature : [Lifetracker]Extra Pedometer: false
07-28 12:05:22.122  7365  7365 I Feature : [Lifetracker]Blood glucose device: false
07-28 12:05:22.122  7365  7365 I Feature : [Lifetracker]Device Number: 3
07-28 12:05:22.128  6822  7393 V FormManager: Network unavailable.
07-28 12:05:22.128  6720  6720 D BluetoothPermissionRequest: onReceive
07-28 12:05:22.128  7053  7053 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:5:22
07-28 12:05:22.130  6720  6720 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,07-28 12:05:22.131  7053  7053 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
07-28 12:05:22.131  7053  7053 D Weather.Utils: 2 : All the weather widget is gone.
07-28 12:05:22.131  7053  7053 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-28 12:05:22.131  7053  7053 D WeatherAncestor: connectivity changed - connection : true
07-28 12:05:22.131  7053  7053 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@289ea772
07-28 12:05:22.132  7053  7053 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
07-28 12:05:22.132  7053  7053 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
07-28 12:05:22.132  7053  7053 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
07-28 12:05:22.132  7053  7053 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-28 12:05:22.132  7053  7053 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:5:22
07-28 12:05:22.133  6822  7393 V FormManager: Network unavailable.
07-28 12:05:22.148  6338  6338 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
07-28 12:05:22.149  6338  6374 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,07-28 12:05:22.158  2126  2126 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
07-28 12:05:22.163  6920  6920 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,07-28 12:05:22.163  6920  6920 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
07-28 12:05:22.163  6920  6920 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-28 12:05:22.163  6920  6920 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
07-28 12:05:22.164  6920  6920 I AppUp4:CustModeStarterReceiver: onReceive
07-28 12:05:22.167  6920  6920 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2e3ae2d4
07-28 12:05:22.167  6920  6920 D AppUp4:CustFacade: isCustomizationCompleted : false
07-28 12:05:22.167  6920  6920 D AppUp4:CustFacade: isPhone : true
07-28 12:05:22.167  6920  6920 D AppUp4:CustModeStarterReceiver: begin check event
07-28 12:05:22.167  6920  6920 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
07-28 12:05:22.169  4323  4323 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
07-28 12:05:22.169  4323  4323 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-28 12:05:22.171  4323  4323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 12:05:22.173  4323  4323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 12:05:22.177  4323  7395 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,07-28 12:05:22.177  6944  6944 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
07-28 12:05:22.180  4323  7396 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
07-28 12:05:22.180  4323  7396 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-28 12:05:22.184  1032  2013 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
07-28 12:05:22.191  6868  6868 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,07-28 12:05:22.194  6868  6868 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
07-28 12:05:22.195  6868  6868 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
07-28 12:05:22.195  6868  6868 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
07-28 12:05:22.195  6868  6868 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
07-28 12:05:22.195  6868  6868 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-28 12:05:22.195  6868  6868 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
07-28 12:05:22.195  6868  6868 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
07-28 12:05:22.195  6868  6868 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
07-28 12:05:22.195  6868  6868 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-28 12:05:22.195  6868  6868 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
07-28 12:05:22.196  6868  6868 I BluetoothA2dpServiceJni: classInitNative
07-28 12:05:22.196  6868  6868 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-28 12:05:22.196  6868  6868 D A2dpStateMachine: make
07-28 12:05:22.196  6822  7398 W FormManager: Network not available. Please check & try again.
07-28 12:05:22.196  3454  3454 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
07-28 12:05:22.196  3454  3454 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
07-28 12:05:22.196  3454  3454 I LgeMiscReceiver: networkInfo.isConnected() = false
07-28 12:05:22.197  6868  6868 I bluedroid-qcom: get_profile_interface a2dp
07-28 12:05:22.197  6868  7403 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
07-28 12:05:22.199  6822  7399 V FormManager: Network unavailable.
07-28 12:05:22.199  6868  6868 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
07-28 12:05:22.199  6868  6868 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
07-28 12:05:22.200  6944  7400 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:22.200  6868  6868 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@289ea772
07-28 12:05:22.200  6868  7402 D A2dpStateMachine: Enter Disconnected: -2
07-28 12:05:22.201  6868  6868 I BluetoothHidServiceJni: classInitNative: succeeds
07-28 12:05:22.202  6822  7399 V FormManager: Network unavailable.
,07-28 12:05:22.202  6997  6997 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
07-28 12:05:22.202  6997  6997 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
07-28 12:05:22.204  6868  6868 D HidService: Received start request. Starting profile...
,07-28 12:05:22.204  6868  6868 I bluedroid-qcom: get_profile_interface hidhost
07-28 12:05:22.204  6868  6868 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@289ea772
07-28 12:05:22.205  6868  6868 D HeadsetStateMachine: Proxy object connected
07-28 12:05:22.206  6868  6868 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
07-28 12:05:22.206  6868  6868 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
07-28 12:05:22.207  6868  6868 I BluetoothHealthServiceJni: classInitNative: succeeds
07-28 12:05:22.208  6868  6868 D HealthService: Received start request. Starting profile...
07-28 12:05:22.210  6868  6868 I bluedroid-qcom: get_profile_interface health
07-28 12:05:22.210  6868  6868 I LGBluetoothHealthServiceJni: classInitNative: succeeds
07-28 12:05:22.210  6868  6868 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@289ea772
07-28 12:05:22.212  7053  7053 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:5:22
07-28 12:05:22.213  7053  7053 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
07-28 12:05:22.214  7053  7053 D Weather.Utils: 2 : All the weather widget is gone.
07-28 12:05:22.214  7053  7053 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-28 12:05:22.214  7053  7053 D WeatherAncestor: connectivity changed - connection : true
07-28 12:05:22.214  7053  7053 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@289ea772
07-28 12:05:22.215  7053  7053 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
07-28 12:05:22.215  7053  7053 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
,07-28 12:05:22.215  7053  7053 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
,07-28 12:05:22.215  7053  7053 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-28 12:05:22.215  7053  7053 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:5:22
07-28 12:05:22.216  6868  6868 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-28 12:05:22.216  6868  7363 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-28 12:05:22.216  6868  6868 I BluetoothPanServiceJni: classInitNative(L105): succeeds
07-28 12:05:22.218  6868  7363 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-28 12:05:22.218  6868  7363 D HeadsetStateMachine: Disconnected process message: 11, size: 0
07-28 12:05:22.218  6868  6868 D PanService: Received start request. Starting profile...
07-28 12:05:22.218  6868  6868 D BluetoothPanServiceJni: initializeNative(L110): pan
07-28 12:05:22.218  6868  6868 I bluedroid-qcom: get_profile_interface pan
07-28 12:05:22.222  6868  6868 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
07-28 12:05:22.222  6868  6868 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@289ea772
07-28 12:05:22.223  6868  6868 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
07-28 12:05:22.227  6868  6868 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-28 12:05:22.227  6868  6868 D BtGatt.GattService: Received start request. Starting profile...
07-28 12:05:22.227  6868  6868 D BtGatt.GattService: start()
07-28 12:05:22.227  6868  6868 I bluedroid-qcom: get_profile_interface gatt
07-28 12:05:22.227  6868  6868 D BtGatt.AdvertiseManager: advertise manager created
07-28 12:05:22.232  6868  6868 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@289ea772
07-28 12:05:22.232  6868  6868 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@289ea772
07-28 12:05:22.233  6868  6868 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
07-28 12:05:22.233  6868  6868 V BluetoothMapService: BluetoothMapBinder()
07-28 12:05:22.234  6868  6868 D BluetoothMapService: Received start request. Starting profile...
07-28 12:05:22.234  6868  6868 D BluetoothMapService: start()
07-28 12:05:22.236  6868  6868 D BluetoothMapEmailSettingsLoader: Found 0 applications
07-28 12:05:22.236  6868  6868 D BluetoothMapEmailAppObserver: createReceiver()
07-28 12:05:22.237  6868  6868 D BluetoothMapEmailAppObserver: initObservers()
07-28 12:05:22.237  6868  6868 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
07-28 12:05:22.243  6868  6868 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@289ea772
,07-28 12:05:22.246  6868  6868 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-28 12:05:22.248  6868  6868 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-28 12:05:22.250  6868  6868 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-28 12:05:22.251  6868  6868 V PanService: [BTUI] SIM Extra State :ABSENT
07-28 12:05:22.253  6868  6868 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-28 12:05:22.255  6868  6868 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
07-28 12:05:22.256  6868  6868 V BluetoothMapService: Handler(): got msg=1
,07-28 12:05:22.257  6868  7340 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,07-28 12:05:22.257  6868  7340 I bluedroid-qcom: enable
07-28 12:05:22.257  6868  7410 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
07-28 12:05:22.257  6868  7410 I bt-btu  : btu_task pending for preload complete event
07-28 12:05:22.257  6868  7340 I bt_hci_bdroid: init
07-28 12:05:22.258  6868  7340 I bt_vendor: bt-vendor : init
07-28 12:05:22.258  6868  6868 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:22.258  6868  7340 I bt_vendor: bt-vendor : get_bt_soc_type
07-28 12:05:22.258  6868  7340 E bt_vendor: get_bt_soc_type: Failed to get soc type
07-28 12:05:22.258  6868  7340 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
07-28 12:05:22.258  6868  7340 D bt_userial_mct: userial_init
07-28 12:05:22.260  6868  7340 D bt_hci_bdroid: set_power 1
07-28 12:05:22.260  6868  7340 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
07-28 12:05:22.260  6868  7340 I bt_vendor: Starting hciattach daemon
07-28 12:05:22.260  6868  7340 I bt_vendor: try to set true
07-28 12:05:22.260  6868  6868 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-28 12:05:22.260  6868  6868 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-28 12:05:22.260  6868  6868 V BluetoothSapReceiver: SapReceiver onReceive 
07-28 12:05:22.260  6868  6868 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:22.260  6868  6868 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
07-28 12:05:22.255  7413  7413 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:05:22.255  7413  7413 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:05:22.279  7414  7414 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,07-28 12:05:22.390  7420  7420 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,07-28 12:05:22.403  7421  7421 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,07-28 12:05:22.459  7423  7423 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,07-28 12:05:22.490  7424  7424 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,07-28 12:05:22.504  7428  7428 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,07-28 12:05:22.517  7429  7429 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,07-28 12:05:22.550  7431  7431 I libmdmdetect: ESOC framework not supported
07-28 12:05:22.551  7431  7431 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,07-28 12:05:22.559  7431  7431 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,07-28 12:05:22.559  7431  7431 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
07-28 12:05:22.559  7431  7431 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
,07-28 12:05:22.559  7431  7431 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
07-28 12:05:22.559  7431  7431 D bthci_qcomm_common: [BTUI]     LE: Class 2
07-28 12:05:22.559  7431  7431 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
07-28 12:05:22.559  7431  7431 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
07-28 12:05:22.602  7431  7435 E QC-QMI  : qmi_client [7431] 14: failed to locate client data
07-28 12:05:22.603   467   467 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
07-28 12:05:22.603   467   467 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,07-28 12:05:22.649  1032  1092 W ProcessCpuTracker: Skipping unknown process pid 7351
,07-28 12:05:22.650  1032  1092 W ProcessCpuTracker: Skipping unknown process pid 7352
07-28 12:05:22.650  1032  1092 W ProcessCpuTracker: Skipping unknown process pid 7358
,07-28 12:05:22.653  1032  1092 W ProcessCpuTracker: Skipping unknown process pid 7362
07-28 12:05:22.655  1032  1092 W ProcessCpuTracker: Skipping unknown process pid 7430
07-28 12:05:22.656  1032  1092 W ProcessCpuTracker: Skipping unknown process pid 7431
07-28 12:05:22.656  1032  1092 W ProcessCpuTracker: Skipping unknown process pid 7432
07-28 12:05:22.672  7436  7436 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,07-28 12:05:22.686  7437  7437 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,07-28 12:05:22.713  6868  7340 I bt_vendor: bluetooth satus is on
07-28 12:05:22.713  6868  7340 D bt_hci_bdroid: preload
07-28 12:05:22.713  6868  7412 D bt_userial_mct: userial_open(port:0)
07-28 12:05:22.713  6868  7412 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,07-28 12:05:22.716  6868  7412 I bt_vendor: Done intiailizing UART
,07-28 12:05:22.717  6868  7412 I bt_vendor: Done intiailizing UART
07-28 12:05:22.717  6868  7412 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
,07-28 12:05:22.718  6868  7412 I bt_vendor: Bluetooth Firmware and transport layer are initialized
07-28 12:05:22.718  6868  7410 I bt-btu  : btu_task received preload complete event
07-28 12:05:22.718  6868  7439 D bt_userial_mct: Entering userial_read_thread()
07-28 12:05:22.718  6868  7410 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
07-28 12:05:22.718  6868  7410 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
07-28 12:05:22.720  6868  7410 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
07-28 12:05:22.724  6868  7410 I         : BTE_InitTraceLevels -- TRC_HCI
07-28 12:05:22.724  6868  7410 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-28 12:05:22.724  6868  7410 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-28 12:05:22.724  6868  7410 I         : BTE_InitTraceLevels -- TRC_AVDT
07-28 12:05:22.724  6868  7410 I         : BTE_InitTraceLevels -- TRC_AVRC
07-28 12:05:22.724  6868  7410 I         : BTE_InitTraceLevels -- TRC_A2D
07-28 12:05:22.724  6868  7410 I         : BTE_InitTraceLevels -- TRC_BNEP
07-28 12:05:22.724  6868  7410 I         : BTE_InitTraceLevels -- TRC_BTM
07-28 12:05:22.724  6868  7410 I         : BTE_InitTraceLevels -- TRC_HID_HOST
07-28 12:05:22.724  6868  7410 I         : BTE_InitTraceLevels -- TRC_GAP
07-28 12:05:22.724  6868  7410 I         : BTE_InitTraceLevels -- TRC_PAN
07-28 12:05:22.724  6868  7410 I         : BTE_InitTraceLevels -- TRC_SDP
07-28 12:05:22.724  6868  7410 I         : BTE_InitTraceLevels -- TRC_GATT
07-28 12:05:22.724  6868  7410 I         : BTE_InitTraceLevels -- TRC_SMP
07-28 12:05:22.724  6868  7410 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-28 12:05:22.724  6868  7410 I         : BTE_InitTraceLevels -- TRC_BTIF
07-28 12:05:22.783  6868  7410 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
07-28 12:05:22.783  6868  7410 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa014e061 
07-28 12:05:22.783  6868  7410 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa014e061 
,07-28 12:05:22.800  6868  7344 E bt-btif : Calling BTA_HhEnable
07-28 12:05:22.800  6868  7344 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,07-28 12:05:22.800  6868  7344 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,07-28 12:05:22.801  6868  7410 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
07-28 12:05:22.801  6868  7410 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
07-28 12:05:22.801  6868  7410 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
,07-28 12:05:22.801  6868  7410 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
07-28 12:05:22.801  6868  7410 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
07-28 12:05:22.803  6868  7344 D BluetoothAdapterProperties: Name is: G3
07-28 12:05:22.805  6868  7344 D BluetoothAdapterProperties: Scan Mode:20
07-28 12:05:22.805  6868  7344 D BluetoothAdapterProperties: Discoverable Timeout:120
07-28 12:05:22.805  6868  7344 D bt_hci_bdroid: postload
07-28 12:05:22.805  6868  7412 D bt_hci_bdroid: Used up Tx Cmd credits
07-28 12:05:22.805  1032  1032 D BluetoothManagerService: Bluetooth Adapter name changed to G3
07-28 12:05:22.806  6868  7412 D bt_hci_bdroid: Used up Tx Cmd credits
07-28 12:05:22.807  6868  7410 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
07-28 12:05:22.808  6868  7412 D bt_hci_bdroid: Used up Tx Cmd credits
07-28 12:05:22.808  6868  7344 D bte_conf: Device ID record 1 : primary
07-28 12:05:22.808  6868  7344 D bte_conf:   vendorId            = 00c4
07-28 12:05:22.808  6868  7344 D bte_conf:   vendorIdSource      = 0001
07-28 12:05:22.808  6868  7344 D bte_conf:   product             = 13a1
07-28 12:05:22.808  6868  7344 D bte_conf:   version             = 1000
07-28 12:05:22.808  6868  7344 D bte_conf:   clientExecutableURL = 
07-28 12:05:22.808  6868  7344 D bte_conf:   serviceDescription  = 
07-28 12:05:22.808  6868  7344 D bte_conf:   documentationURL    = 
07-28 12:05:22.809  6868  7344 D bte_conf: bte_load_did_conf no section named DID2.
07-28 12:05:22.810  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:22.811  6868  7412 D bt_hci_bdroid: Used up Tx Cmd credits
07-28 12:05:22.812  6868  7439 E bt_mct  : hci lib postload completed
07-28 12:05:22.805  7441  7441 W sh      : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:05:22.805  7441  7441 W sh      : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:05:22.822  6868  7340 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
07-28 12:05:22.822  6868  7340 D BluetoothAdapterProperties: ScanMode =  20
07-28 12:05:22.822  6868  7340 D BluetoothAdapterProperties: State =  11
07-28 12:05:22.822  6868  7340 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
07-28 12:05:22.823  6868  7340 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
07-28 12:05:22.823  6868  7340 D BluetoothAdapterProperties: Setting state to 12
07-28 12:05:22.823  6868  7340 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-28 12:05:22.823  6868  7344 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-28 12:05:22.824  6868  7344 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
07-28 12:05:22.827  1032  1097 D BluetoothManagerService: Message: 60
07-28 12:05:22.827  1032  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
07-28 12:05:22.827  1032  1097 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
07-28 12:05:22.827  1032  1097 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-28 12:05:22.830  1032  1032 D BluetoothManagerService: Stored Bluetooth name: G3
07-28 12:05:22.833  6868  7410 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-28 12:05:22.833  6868  7410 W bt-smp  : Plain text(LSB ~ MSB) = 4b 79 4a 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-28 12:05:22.833  6868  7410 W bt-smp  : Encrypted text(LSB ~ MSB) = 8b c2 c2 88 31 2b 21 fd 30 8e 3b 2d 19 28 9c d4 
07-28 12:05:22.833  6868  7410 W bt-btm  : Stopping oneshot timer
07-28 12:05:22.835  6868  7340 I BluetoothAdapterState: Entering On State
07-28 12:05:22.839  6868  7340 D LGBluetoothServiceAdapter: [BTUI] OnState
07-28 12:05:22.840  6868  7340 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
07-28 12:05:22.840  6868  7340 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
07-28 12:05:22.841  6868  7340 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
,07-28 12:05:22.846  1032  1032 D BluetoothHeadset: Proxy object connected
07-28 12:05:22.847  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:05:22.847  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:05:22.847  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:22.847  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:05:22.847  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:05:22.847  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:05:22.847  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:05:22.847  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:05:22.850  6524  6524 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:05:22.852  6868  7344 D BluetoothAdapterProperties: Discoverable Timeout:120
07-28 12:05:22.852  6868  7344 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
07-28 12:05:22.853  6720  6735 D BluetoothPan: onBluetoothStateChange on: true
07-28 12:05:22.853  6720  6735 D BluetoothPan: onBluetoothStateChange call bindService
,07-28 12:05:22.854  6868  7410 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-28 12:05:22.854  6868  7410 W bt-smp  : Plain text(LSB ~ MSB) = 3f b4 47 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-28 12:05:22.855  6868  7410 W bt-smp  : Encrypted text(LSB ~ MSB) = 18 dd 56 07 19 83 fc b0 5b bb c1 4c 1d a3 1d 69 
07-28 12:05:22.855  6868  7410 W bt-btm  : Stopping oneshot timer
07-28 12:05:22.860  6720  6736 D BluetoothPbap: onBluetoothStateChange: up=true
07-28 12:05:22.863  1851  1866 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 12:05:22.865  1851  1851 D BluetoothHeadset: Proxy object connected
07-28 12:05:22.867  6868  7410 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-28 12:05:22.867  6868  7410 W bt-smp  : Plain text(LSB ~ MSB) = 81 02 7c 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-28 12:05:22.867  6868  7410 W bt-smp  : Encrypted text(LSB ~ MSB) = 26 e2 bf 54 6c 4a 8f b3 31 d4 b6 fe e8 d7 af 6d 
07-28 12:05:22.867  6868  7410 W bt-btm  : Stopping oneshot timer
,07-28 12:05:22.869  1851  3997 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 12:05:22.871  6720  6720 D BluetoothPan: BluetoothPAN Proxy object connected
07-28 12:05:22.871  6720  6720 D PanProfile: Bluetooth service connected
07-28 12:05:22.872  1851  1851 D BluetoothHeadset: Proxy object connected
07-28 12:05:22.874  6720  6735 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-28 12:05:22.885  6868  7340 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
07-28 12:05:22.889  6868  7410 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-28 12:05:22.889  6868  7410 W bt-smp  : Plain text(LSB ~ MSB) = 39 03 7e 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-28 12:05:22.889  6868  7410 W bt-smp  : Encrypted text(LSB ~ MSB) = f1 7b 9a 8b de 8f b0 5c 70 e2 99 c1 0a b4 f8 36 
07-28 12:05:22.889  6868  7410 W bt-btm  : Stopping oneshot timer
,07-28 12:05:22.895  6720  6736 D BluetoothMap: onBluetoothStateChange: up=true
07-28 12:05:22.895  6720  6720 D BluetoothInputDevice: Proxy object connected
07-28 12:05:22.895  6720  6720 D HidProfile: Bluetooth service connected
07-28 12:05:22.899  7451  7451 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
07-28 12:05:22.900  1032  1097 D BluetoothA2dp: onBluetoothStateChange: up=true
07-28 12:05:22.900  6720  6720 D BluetoothMap: Proxy object connected
07-28 12:05:22.900  6720  6720 D MapProfile: Bluetooth service connected
07-28 12:05:22.901  6720  6720 D BluetoothMap: getConnectedDevices()
07-28 12:05:22.902  6868  7345 V BluetoothMapService: getConnectedDevices()
07-28 12:05:22.903  1032  1032 D BluetoothA2dp: Proxy object connected
07-28 12:05:22.904  1851  1866 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 12:05:22.907  1851  1851 D BluetoothHeadset: Proxy object connected
,07-28 12:05:22.909  1032  1097 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
07-28 12:05:22.909  1032  1097 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
07-28 12:05:22.910  1032  1032 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
07-28 12:05:22.910  6868  7410 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-28 12:05:22.910  6868  7410 W bt-smp  : Plain text(LSB ~ MSB) = 64 48 52 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-28 12:05:22.910  6868  7410 W bt-smp  : Encrypted text(LSB ~ MSB) = ab 88 de 8c f2 ed 15 b2 81 ce 17 37 4d 05 5e 82 
07-28 12:05:22.910  6868  7410 W bt-btm  : Stopping oneshot timer
07-28 12:05:22.911  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:22.911  1940  2165 D LGBluetoothAPIService: Message: 1
07-28 12:05:22.911  1940  2165 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
07-28 12:05:22.912  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-28 12:05:22.918  6524  6524 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
07-28 12:05:22.920  1940  2165 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
,07-28 12:05:22.922  6868  6868 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:22.922  6868  6868 D BluetoothMapService: STATE_ON
07-28 12:05:22.922  1032  1097 D BluetoothManagerService: Message: 40
07-28 12:05:22.922  1032  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
07-28 12:05:22.924  6868  6868 D LGBluetoothAPIServer: [BTUI] onCreate()
07-28 12:05:22.924  6868  6868 D LGBluetoothAPIServer: [BTUI] onBind()
07-28 12:05:22.925  1940  1940 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
07-28 12:05:22.925  1940  2165 D LGBluetoothAPIService: Message: 100
07-28 12:05:22.925  1940  2165 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
07-28 12:05:22.936  6720  6720 D LocalBluetoothProfileManager: Adding local A2DP profile
,07-28 12:05:22.939  1032  1097 D BluetoothManagerService: Message: 30
07-28 12:05:22.942  6720  6720 D LocalBluetoothProfileManager: Adding local HEADSET profile
07-28 12:05:22.943  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:05:22.943  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:05:22.943  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:22.943  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:05:22.943  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:05:22.943  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:05:22.943  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:05:22.943  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:05:22.943  6868  6868 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@289ea772
07-28 12:05:22.943  6868  6868 V BluetoothPbapService: Pbap Service onCreate
07-28 12:05:22.943  6868  6868 V BluetoothPbapService: Starting PBAP service
,07-28 12:05:22.944  6868  6868 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
,07-28 12:05:22.944  6868  6868 V BluetoothMapService: Handler(): got msg=1
07-28 12:05:22.945  7075  7112 I art     : WaitForGcToComplete blocked for 7.704ms for cause DisableMovingGc
07-28 12:05:22.946  1032  1097 D BluetoothManagerService: Message: 30
07-28 12:05:22.947  6868  6868 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
07-28 12:05:22.948  6868  6868 V BluetoothPbapService: Pbap Service onBind
07-28 12:05:22.949  6868  7459 D BluetoothMapMasInstance: MAS initSocket()
07-28 12:05:22.949  6868  7459 D BluetoothMapMasInstance:   masId = 00
07-28 12:05:22.949  6868  7459 D BluetoothMapMasInstance:   msgTypes = 0e
07-28 12:05:22.949  6868  7459 D BluetoothMapMasInstance:   masName = SMS/MMS
07-28 12:05:22.949  6868  7459 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
,07-28 12:05:22.950  6868  6868 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:22.950  6868  6868 V BluetoothPbapService: state: 12
07-28 12:05:22.950  6868  6868 V BluetoothPbapService: Handler(): got msg=1
07-28 12:05:22.951  6524  6524 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:05:22.951  6868  6868 V BluetoothPbapService: Pbap Service startRfcommSocketListener
07-28 12:05:22.952  1032  1939 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:05:22.953  6868  7459 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 12:05:22.953  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:22.953  6868  7462 V BluetoothPbapService: Pbap Service initSocket
07-28 12:05:22.954  1032  1921 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:05:22.954  6868  7459 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
07-28 12:05:22.954  6868  7459 V BluetoothMapMasInstance: Succeed to create listening socket 
07-28 12:05:22.954  6868  7459 D BluetoothMapMasInstance: Accepting socket connection...
07-28 12:05:22.955  6868  7344 D BluetoothAdapterProperties: Scan Mode:21
07-28 12:05:22.955  6868  7344 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
07-28 12:05:22.956  6868  7462 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 12:05:22.956  6720  6720 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
07-28 12:05:22.957  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:22.957  6868  7462 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
07-28 12:05:22.958  6868  7462 V BluetoothPbapService: Succeed to create listening socket 
07-28 12:05:22.958  6868  7462 V BluetoothPbapService: Accepting socket connection...
07-28 12:05:22.958  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:22.958  6720  6720 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-28 12:05:22.959  7075  7112 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
07-28 12:05:22.963  6720  6720 D BluetoothA2dp: Proxy object connected
,07-28 12:05:22.964  6868  6868 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-28 12:05:22.965  6868  6868 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:22.965  6868  6868 V BluetoothPbapReceiver: ***********state = 12
07-28 12:05:22.965  6720  6720 D A2dpProfile: Bluetooth service connected
07-28 12:05:22.968  2126  2126 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-28 12:05:22.969  2126  2126 D c       : Getting all permits...
07-28 12:05:22.969  2126  2126 D a       : Opening database...
07-28 12:05:22.972  2126  2126 D a       : Opening database auth.proximity.permit_store...
07-28 12:05:22.973  6720  6720 D BluetoothPbap: Proxy object connected
07-28 12:05:22.973  2126  2126 D a       : Closing database...
07-28 12:05:22.973  6720  6720 D PbapServerProfile: Bluetooth service connected
,07-28 12:05:22.973  6720  6720 D BluetoothHeadset: Proxy object connected
07-28 12:05:22.974  6720  6720 D HeadsetProfile: Bluetooth service connected
07-28 12:05:22.981  6720  6720 D DockEventReceiver: finishStartingService: stopping service
07-28 12:05:22.985  6720  6720 D BluetoothPermissionRequest: onReceive
07-28 12:05:22.987  6720  6720 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,07-28 12:05:22.988  6720  6720 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-28 12:05:22.991  6868  6868 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
07-28 12:05:22.992  6868  6868 I LGBluetoothOppAdapter: [BTUI] startOppService()
07-28 12:05:22.996  6868  6868 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
07-28 12:05:23.010  6868  6868 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,07-28 12:05:23.010  6868  6868 V BtOppService: onCreate
07-28 12:05:23.014  6868  6868 V BluetoothOppNotification: send message
07-28 12:05:23.016  6868  6868 V BtOppService: Starting RfcommListener
07-28 12:05:23.021  6868  6868 D BluetoothOppPreference: Dumping Names:  
07-28 12:05:23.021  6868  6868 D BluetoothOppPreference: {}
07-28 12:05:23.021  6868  6868 D BluetoothOppPreference: Dumping Channels:  
07-28 12:05:23.021  6868  6868 D BluetoothOppPreference: {}
07-28 12:05:23.022  6868  6868 V BtOppService: onStartCommand
07-28 12:05:23.025  6868  7470 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,07-28 12:05:23.025  6868  7470 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-28 12:05:23.026  6868  7470 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1abbadef on behalf of 
07-28 12:05:23.027  6868  7467 V BtOppService: Deleted complete outbound shares, number =  0
07-28 12:05:23.027  6868  7470 V BluetoothOppNotification: update too frequent, put in queue
07-28 12:05:23.029  6868  7470 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
07-28 12:05:23.031  6868  7467 V BtOppService: Deleted complete inbound failed shares, number = 0
07-28 12:05:23.031  6868  6868 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:23.031  6868  7467 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
07-28 12:05:23.031  6868  6868 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
07-28 12:05:23.032  6868  7467 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@6c210fc on behalf of 
07-28 12:05:23.036  6868  6868 V BluetoothOppNotification: new notify threadi!
07-28 12:05:23.038  6868  6868 V BluetoothOppNotification: send delay message
,07-28 12:05:23.039  6868  6868 V BtOppService: start RfcommListener
07-28 12:05:23.040  6868  7471 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
07-28 12:05:23.042  6868  7471 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@20b63385 on behalf of 
07-28 12:05:23.043  6868  7471 V BluetoothOppNotification: mUpdateCompleteNotification = true
07-28 12:05:23.044  6868  7471 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
07-28 12:05:23.046  6868  6868 V BtOppService: RfcommListener started
07-28 12:05:23.047  6868  6868 V BtOppService: ContentObserver received notification
07-28 12:05:23.047  6868  7472 V BtOppRfcommListener: Starting RFCOMM listener....
07-28 12:05:23.047  6868  7471 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@f24a5da on behalf of 
07-28 12:05:23.047  6868  6868 V BtOppService: ContentObserver received notification
07-28 12:05:23.047  1032  1886 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:05:23.048  6868  7472 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 12:05:23.049  6868  7472 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=75
,07-28 12:05:23.049  6868  7472 V BtOppRfcommListener: Started RFCOMM listener....
07-28 12:05:23.049  6868  7472 I BtOppRfcommListener: Accept thread started.
07-28 12:05:23.049  6868  7472 V BtOppRfcommListener: Accepting connection...
07-28 12:05:23.050  6868  7471 V BluetoothOppNotification: outbound: succ-0  fail-0
07-28 12:05:23.050  6868  7473 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
07-28 12:05:23.051  6868  7473 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-28 12:05:23.052  6868  7473 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3dbf3a0b on behalf of 
07-28 12:05:23.053  6868  7471 V BluetoothOppNotification: outbound notification was removed.
07-28 12:05:23.053  6868  7473 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
07-28 12:05:23.053  6868  7471 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
07-28 12:05:23.055  6868  7471 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3d9d40e8 on behalf of 
07-28 12:05:23.056  6868  7471 V BluetoothOppNotification: inbound: succ-0  fail-0
07-28 12:05:23.058  6868  7471 V BluetoothOppNotification: inbound notification was removed.
07-28 12:05:23.058  6868  7471 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
07-28 12:05:23.060  6868  7471 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@12b8301 on behalf of 
,07-28 12:05:23.063  6868  6868 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@289ea772
07-28 12:05:23.063  6868  6868 V BluetoothFtpService: Ftp Service onCreate
,07-28 12:05:23.063  6868  6868 I BluetoothFtpService: Ftp Service onCreate
07-28 12:05:23.063  6868  6868 V BluetoothFtpService: Ftp Service onStartCommand
07-28 12:05:23.063  6868  6868 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:23.064  6868  6868 V BluetoothFtpService: Starting Listening on sockets
07-28 12:05:23.064  6868  6868 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-28 12:05:23.064  6868  6868 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-28 12:05:23.064  6868  6868 V BluetoothSapReceiver: SapReceiver onReceive 
07-28 12:05:23.064  6868  6868 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:23.064  6868  6868 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
07-28 12:05:23.064  6868  6868 V BluetoothSapReceiver: Calling SAP service start service with action = null
07-28 12:05:23.067  6868  6868 V BluetoothFtpService: Handler(): got msg=1
07-28 12:05:23.067  6868  6868 V BluetoothFtpService: Ftp Service startRfcommSocketListener
07-28 12:05:23.067  6868  6868 V BluetoothFtpService: Ftp Service initSocket
07-28 12:05:23.072  1032  2026 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:05:23.073  6868  6868 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-28 12:05:23.074  6868  6868 V BluetoothFtpService: Succeed to create listening socket on channel 20
07-28 12:05:23.076  6868  7474 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
07-28 12:05:23.089  6868  6868 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@289ea772
07-28 12:05:23.089  6868  6868 V BluetoothSapService: Sap Service onCreate
07-28 12:05:23.091  6868  6868 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:23.091  6868  6868 V BluetoothSapService: state: 12
07-28 12:05:23.091  6868  6868 V BluetoothSapService: Starting SAP server process
,07-28 12:05:23.093  6868  6868 V BluetoothSapService: SAP Service startRfcommListenerThread
07-28 12:05:23.085  7476  7476 W sapd    : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:05:23.095  6868  7475 V BluetoothSapService: Sap Service initRfcommSocket
07-28 12:05:23.085  7476  7476 W sapd    : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:05:23.096  1032  1885 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:05:23.097  6868  7475 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 12:05:23.098  6868  7475 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
07-28 12:05:23.099  6868  7475 V BluetoothSapService: Succeed to create listening socket 
07-28 12:05:23.099  6868  7475 V BluetoothSapService: Accepting socket connection...
07-28 12:05:23.110  7476  7476 V BT_SAP  : Event pipe created
07-28 12:05:23.110  7476  7476 V BT_SAP  : create_server_socket qcom.sap.server
07-28 12:05:23.110  7476  7476 V BT_SAP  : created socket fd 6
,07-28 12:05:23.789  1032  1537 D LGWifiP2pService: P2pDisabledState{ when=-4ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,07-28 12:05:23.789  1032  1537 D LGWifiP2pService: DefaultState{ when=-4ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,07-28 12:05:23.836  1032  1538 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,07-28 12:05:23.843  1032  1538 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
07-28 12:05:23.853  1032  1975 I ActivityManager: Killing 7251:com.lge.bnr/1000 (adj 15): empty #17
,07-28 12:05:23.884  1032  1885 W libprocessgroup: failed to open /acct/uid_1000/pid_7251/cgroup.procs: No such file or directory
,07-28 12:05:24.039  6868  6868 V BluetoothOppNotification: new notify threadi!
,07-28 12:05:24.041  6868  6868 V BluetoothOppNotification: send delay message
07-28 12:05:24.045  6868  7486 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
07-28 12:05:24.046  6868  7486 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@20821632 on behalf of 
07-28 12:05:24.047  6868  7486 V BluetoothOppNotification: mUpdateCompleteNotification = true
07-28 12:05:24.048  6868  7486 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
07-28 12:05:24.055  6868  7486 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@16d2df83 on behalf of 
07-28 12:05:24.056  6868  7486 V BluetoothOppNotification: outbound: succ-0  fail-0
,07-28 12:05:24.060  6868  7486 V BluetoothOppNotification: outbound notification was removed.
07-28 12:05:24.060  6868  7486 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
07-28 12:05:24.061  6868  7486 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1a354500 on behalf of 
07-28 12:05:24.061  6868  7486 V BluetoothOppNotification: inbound: succ-0  fail-0
07-28 12:05:24.062  6868  7486 V BluetoothOppNotification: inbound notification was removed.
07-28 12:05:24.062  6868  7486 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
07-28 12:05:24.063  6868  7486 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1b49139 on behalf of 
07-28 12:05:24.072  1032  1781 I ActivityManager: Killing 6636:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,07-28 12:05:24.090  6782  6782 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
07-28 12:05:24.090  6782  6782 W System.err: android.os.DeadObjectException
07-28 12:05:24.090  6782  6782 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
07-28 12:05:24.090  6782  6782 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
07-28 12:05:24.090  6782  6782 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
07-28 12:05:24.090  6782  6782 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
07-28 12:05:24.090  6782  6782 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
07-28 12:05:24.090  6782  6782 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
07-28 12:05:24.090  6782  6782 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-28 12:05:24.090  6782  6782 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-28 12:05:24.090  6782  6782 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-28 12:05:24.090  6782  6782 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-28 12:05:24.090  6782  6782 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:05:24.090  6782  6782 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:05:24.090  6782  6782 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-28 12:05:24.090  6782  6782 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-28 12:05:24.091  6782  6782 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
07-28 12:05:24.091  6782  6782 W System.err: android.os.DeadObjectException
07-28 12:05:24.091  6782  6782 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
07-28 12:05:24.091  6782  6782 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
07-28 12:05:24.091  6782  6782 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
07-28 12:05:24.091  6782  6782 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
07-28 12:05:24.091  6782  6782 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
07-28 12:05:24.091  6782  6782 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
07-28 12:05:24.091  6782  6782 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-28 12:05:24.091  6782  6782 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-28 12:05:24.091  6782  6782 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-28 12:05:24.091  6782  6782 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-28 12:05:24.091  6782  6782 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:05:24.091  6782  6782 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:05:24.091  6782  6782 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-28 12:05:24.091  6782  6782 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-28 12:05:24.091  6782  6782 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
07-28 12:05:24.091  6782  6782 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,07-28 12:05:24.119  1032  1975 W libprocessgroup: failed to open /acct/uid_1000/pid_6636/cgroup.procs: No such file or directory
07-28 12:05:24.119  1032  1975 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,07-28 12:05:24.123  6782  6782 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
07-28 12:05:24.124  6782  6782 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
07-28 12:05:24.154  1032  2037 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7491 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,07-28 12:05:24.160  6782  6782 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,07-28 12:05:24.210  7491  7491 D UEI.SmartControl: Quickset Services start...
,07-28 12:05:24.212  7491  7491 I UEI.SmartControl: Manufacture = LGE
07-28 12:05:24.212  7491  7491 D UEI.SmartControl: Id = LGNevo
07-28 12:05:24.216  7491  7491 D UEI.SmartControl: File observer start...
07-28 12:05:24.217  7491  7491 E UEI.SmartControl: IR Port is disabled: false
07-28 12:05:24.218  7491  7491 D UEI.SmartControl: Starting file observer...
07-28 12:05:24.219  7491  7491 D UEI.SmartControl: Extracting JNI libs...
,07-28 12:05:24.219  7491  7491 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,07-28 12:05:24.314  7491  7491 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
07-28 12:05:24.314  7491  7491 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
07-28 12:05:24.314  7491  7491 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,07-28 12:05:24.343  7491  7491 I UEI.SmartControl: --- Selecting new region: 6
,07-28 12:05:24.344  7491  7491 I UEI.SmartControl: Model = LG-D855
07-28 12:05:24.346  7491  7491 D UEI.SmartControl: QS Service created
07-28 12:05:24.489  1032  1781 I art     : Explicit concurrent mark sweep GC freed 91607(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 1.823ms total 139.030ms
,07-28 12:05:24.501  7491  7491 I UEI.SmartControl: Service initServices...
07-28 12:05:24.504  7491  7491 D UEI.SmartControl: QS start get config
07-28 12:05:24.546  7491  7491 D UEI.SmartControl: Loading JNI Libs...
,07-28 12:05:24.762  1032  2037 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-28 12:05:24.762  1032  2037 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1f72e0ae mBinding = false
,07-28 12:05:24.792  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-28 12:05:24.793  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-28 12:05:24.793  1032  1032 D Ulp_jni : JNI:system_update. Event-4
,07-28 12:05:24.795  1032  1097 D BluetoothManagerService: Message: 2
07-28 12:05:24.796  1032  1097 D BluetoothManagerService: Sending off request.
07-28 12:05:24.797  6868  7345 D LGBluetoothServiceAdapter: [BTUI] Precleanup
07-28 12:05:24.797  6868  7340 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
07-28 12:05:24.797  6868  7340 D BluetoothAdapterProperties: Setting state to 13
07-28 12:05:24.797  6868  7340 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-28 12:05:24.798  6868  7340 D BluetoothAdapterProperties: onBluetoothDisable()
07-28 12:05:24.798  1032  1097 D BluetoothManagerService: Message: 60
07-28 12:05:24.798  6868  7340 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
07-28 12:05:24.799  6868  7344 D BluetoothAdapterProperties: Scan Mode:20
07-28 12:05:24.799  6868  7340 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
07-28 12:05:24.800  6868  7340 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,07-28 12:05:24.806  6868  7459 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
07-28 12:05:24.806  6868  7459 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 12:05:24.806  6868  7459 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
07-28 12:05:24.806  6868  7459 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
07-28 12:05:24.806  6868  7459 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
07-28 12:05:24.806  6868  7459 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
07-28 12:05:24.806  6868  7459 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
07-28 12:05:24.806  6868  7459 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
07-28 12:05:24.807  6868  7462 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 12:05:24.807  6868  7472 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 12:05:24.807  6868  7474 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 12:05:24.808  6868  7475 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 12:05:24.811  6868  7410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
07-28 12:05:24.811  6868  7410 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
07-28 12:05:24.812  6868  7410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-28 12:05:24.812  6868  7410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-28 12:05:24.812  6868  7410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
,07-28 12:05:24.812  6868  7410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-28 12:05:24.812  6868  7410 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:05:24.812  6868  7410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-28 12:05:24.812  6868  7410 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:05:24.812  6868  7410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-28 12:05:24.812  6868  7410 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 12:05:24.812  6868  7410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
07-28 12:05:24.812  6868  7410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
07-28 12:05:24.813  6868  7410 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
07-28 12:05:24.818  6524  6524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:05:24.818  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:05:24.818  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:05:24.818  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:24.818  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:05:24.818  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:05:24.818  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:05:24.818  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:05:24.818  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:05:24.819  6524  6524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:05:24.820  6524  6524 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:05:24.824  6524  6524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:05:24.824  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:05:24.824  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:05:24.824  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:24.824  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:05:24.824  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:05:24.824  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:05:24.824  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:05:24.824  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:05:24.826  6524  6524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:05:24.826  6524  6524 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:05:24.827  1032  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
07-28 12:05:24.827  1032  1097 D BluetoothManagerService: Bluetooth State Change Inten,t: 12 -> 13
07-28 12:05:24.829  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:24.830  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,07-28 12:05:24.843  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:05:24.844  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:24.846  6868  6868 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:24.847  6868  6868 D BluetoothMapService: STATE_TURNING_OFF
07-28 12:05:24.847  6868  6868 V BluetoothMapService: Handler(): got msg=4
07-28 12:05:24.847  6868  6868 D BluetoothMapService: MAP Service closeService in
07-28 12:05:24.847  6868  6868 D BluetoothMapMasInstance: MAP Service shutdown
,07-28 12:05:24.847  6868  6868 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-28 12:05:24.847  6868  6868 V BluetoothMapService: MAP Service closeService out
07-28 12:05:24.851  6868  6868 V BtOppService: Receiver DISABLED_ACTION 
07-28 12:05:24.851  6868  6868 I BtOppRfcommListener: stopping Accept Thread
07-28 12:05:24.851  6868  6868 V BtOppRfcommListener: close mBtServerSocket
07-28 12:05:24.851  6868  7472 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-28 12:05:24.852  6868  6868 V BtOppRfcommListener: waiting for thread to terminate
07-28 12:05:24.852  6868  6868 V BtOppRfcommListener: done waiting for thread to terminate
,07-28 12:05:24.859  6720  6720 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
07-28 12:05:24.861  6868  6868 V BtOppService: onDestroy
07-28 12:05:24.863  6720  6720 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-28 12:05:24.864  6868  6868 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
07-28 12:05:24.867  6868  6868 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-28 12:05:24.867  6868  6868 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:24.867  6868  6868 V BluetoothPbapReceiver: ***********state = 13
07-28 12:05:24.870  6868  6868 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,07-28 12:05:24.872  6868  6868 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:24.872  6868  6868 V BluetoothPbapService: state: 13
07-28 12:05:24.872  6868  6868 V BluetoothPbapService: Pbap Service closeService in
07-28 12:05:24.873  6720  6720 D DockEventReceiver: finishStartingService: stopping service
07-28 12:05:24.873  2126  2126 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-28 12:05:24.876  6868  6868 V BluetoothPbapService: successfully stopped pbap service
07-28 12:05:24.876  6868  6868 V BluetoothPbapService: Pbap Service closeService out
07-28 12:05:24.876  6868  6868 V BluetoothPbapService: Pbap Service onDestroy
07-28 12:05:24.876  6868  6868 V BluetoothPbapService: Pbap Service closeService in
07-28 12:05:24.876  6868  6868 V BluetoothPbapService: Pbap Service closeService out
,07-28 12:05:24.876  6868  6868 D LGBluetoothPbapAdapter: [BTUI] cleanup
07-28 12:05:24.877  6720  6720 D BluetoothPbap: Proxy object disconnected
07-28 12:05:24.877  6720  6720 D PbapServerProfile: Bluetooth service disconnected
07-28 12:05:24.883  6720  6720 D LGBluetoothAuthorization: [BTUI] cancel All Notification
07-28 12:05:24.887  6720  6720 D BluetoothPermissionRequest: onReceive
07-28 12:05:24.887  6720  6720 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,07-28 12:05:24.896  6720  6720 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-28 12:05:24.901  6868  6868 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,07-28 12:05:24.901  6868  6868 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
07-28 12:05:24.901  6868  6868 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
07-28 12:05:24.904  6868  6868 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:24.904  6868  6868 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
07-28 12:05:24.905  6868  6868 V BluetoothFtpService: Ftp Service onStartCommand
07-28 12:05:24.905  6868  6868 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:24.906  6868  6868 V BluetoothFtpService: Ftp Service closeService
07-28 12:05:24.906  6868  6868 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
07-28 12:05:24.906  6868  6868 V BluetoothFtpService: successfully stopped ftp service
07-28 12:05:24.907  6868  6868 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-28 12:05:24.907  6868  6868 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-28 12:05:24.907  6868  6868 V BluetoothSapReceiver: SapReceiver onReceive 
07-28 12:05:24.907  6868  6868 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:24.907  6868  6868 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
07-28 12:05:24.907  6868  6868 V BluetoothSapReceiver: Calling SAP service start service with action = null
07-28 12:05:24.909  6868  6868 V BluetoothFtpService: Ftp Service onDestroy
07-28 12:05:24.909  6868  6868 V BluetoothFtpService: Ftp Service closeService
07-28 12:05:24.910  6868  6868 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:24.910  6868  6868 V BluetoothSapService: state: 13
07-28 12:05:24.910  6868  6868 V BluetoothSapService: Stopping SAP server process
07-28 12:05:24.912  6868  6868 V BluetoothSapService: Sap Service closeSapService in
07-28 12:05:24.912  6868  6868 V BluetoothSapService: Close listen Socket : 
07-28 12:05:24.912  6868  6868 V BluetoothSapService: Close rfcomm Socket : 
07-28 12:05:24.912  6868  6868 V BluetoothSapService: Close sapd  Socket : 
07-28 12:05:24.912  6868  6868 V BluetoothSapService: Sap Service closeSapService out
07-28 12:05:24.913  6868  6868 V BluetoothSapService: Sap Service onDestroy
07-28 12:05:24.913  6868  6868 V BluetoothSapService: Sap Service closeSapService in
07-28 12:05:24.913  6868  6868 V BluetoothSapService: Close listen Socket : 
07-28 12:05:24.913  6868  6868 V BluetoothSapService: Close rfcomm Socket : 
07-28 12:05:24.913  6868  6868 V BluetoothSapService: Close sapd  Socket : 
,07-28 12:05:24.915  7491  7491 I UEI.SmartControl: Supports setup maps: true
07-28 12:05:24.916  6868  6868 V BluetoothSapService: Sap Service closeSapService out
07-28 12:05:24.921  7491  7491 D UEI.SmartControl: QS start statue = true Error code = 0
07-28 12:05:24.921  7491  7491 I UEI.SmartControl: QS version = v2.7.10.1_RC1
07-28 12:05:24.921  7491  7491 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
,07-28 12:05:24.921  7491  7491 I UEI.SmartControl: ### init IR Blaster...
07-28 12:05:24.926  7491  7491 D serial_port: Configuring serial port
,07-28 12:05:24.930  7491  7491 E UEI.SmartControl: UEIBLaster setting for 616
07-28 12:05:24.930  7491  7491 I UEI.SmartControl: Setting serial record hearder size = 2
07-28 12:05:24.930  7491  7491 I UEI.SmartControl: configuring settings for MAXQ616
07-28 12:05:24.931  7491  7491 I UEI.SmartControl: Get version...
07-28 12:05:24.947  7491  7541 D UEI.SmartControl: serial port data available: 21
,07-28 12:05:24.975  7491  7491 D UEI.SmartControl: MAXQ616 A2-X4 software.
07-28 12:05:24.975  7491  7491 I UEI.SmartControl: IR Blaster version: 256702256704300002
07-28 12:05:24.975  7491  7491 I UEI.SmartControl: QS saving settings...
,07-28 12:05:24.978  7491  7491 D UEI.SmartControl: IR Blaster version: 25672567
,07-28 12:05:24.995  7491  7541 D UEI.SmartControl: serial port data available: 4
,07-28 12:05:25.035  7491  7544 I UEI.SmartControl: Device manager: loading config....
,07-28 12:05:25.036  7491  7544 D UEI.SmartControl: ----------- loading internal config...
,07-28 12:05:25.045  7491  7491 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
07-28 12:05:25.050  7491  7491 E UEI.SmartControl: Services init done
07-28 12:05:25.050  7491  7491 D UEI.SmartControl: QS Service init finished
07-28 12:05:25.052  7491  7491 D UEI.SmartControl: QS Service version name: 2.1.91
07-28 12:05:25.052  7491  7491 D UEI.SmartControl: QS Service version code: 201091
07-28 12:05:25.053  7491  7491 D UEI.SmartControl: Service requested: Control
07-28 12:05:25.059  7491  7491 D UEI.SmartControl: Request IControl service: devices are loaded...
07-28 12:05:25.060  7491  7544 E UEI.SmartControl: Loading SETTINGS...
,07-28 12:05:25.068  1032  1993 I ActivityManager: Killing 6782:com.lge.qremote/u0a112 (adj 15): empty #17
07-28 12:05:25.068  6782  6782 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
07-28 12:05:25.069  7491  7507 I UEI.SmartControl: ------ IControl API: 11
07-28 12:05:25.071  7491  7507 I UEI.SmartControl: Registering callback...
07-28 12:05:25.077  7491  7544 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,07-28 12:05:25.092  7491  7543 I UEI.SmartControl: Notify AllClients services are ready: 0
,07-28 12:05:25.092  7491  7543 D UEI.SmartControl: -----service ready thread exits
,07-28 12:05:25.171  1032  1957 W libprocessgroup: failed to open /acct/uid_10112/pid_6782/cgroup.procs: No such file or directory
,07-28 12:05:25.171  7491  7491 D UEI.SmartControl: Internal service binding...
,07-28 12:05:25.732  6868  7344 D bt_hci_bdroid: cleanup
,07-28 12:05:25.738  6868  7412 I bt_lpm  : LPM is already off!!!
07-28 12:05:25.739  6868  7439 I bt_userial_mct: exiting userial_read_thread
07-28 12:05:25.739  6868  7439 D bt_userial_mct: Leaving userial_evt_read_thread()
07-28 12:05:25.741  6868  7410 W bt-btif : ag scb idx 1 not allocated
07-28 12:05:25.741  6868  7410 E bt-btif : BTA AG is already disabled, ignoring ...
07-28 12:05:25.741  6868  7410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-28 12:05:25.741  6868  7410 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:05:25.742  6868  7410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-28 12:05:25.742  6868  7410 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:05:25.742  6868  7410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-28 12:05:25.742  6868  7410 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 12:05:25.742  6868  7410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-28 12:05:25.742  6868  7410 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:05:25.742  6868  7410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-28 12:05:25.742  6868  7410 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:05:25.742  6868  7410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-28 12:05:25.742  6868  7410 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 12:05:25.742  6868  7410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
,07-28 12:05:25.742  6868  7410 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration,
,07-28 12:05:25.742  6868  7410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
,07-28 12:05:25.742  6868  7410 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:05:25.742  6868  7410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
,07-28 12:05:25.742  6868  7410 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration,
07-28 12:05:25.743  6868  7410 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif,
,07-28 12:05:25.746  6868  7344 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
07-28 12:05:25.746  6868  7412 I bt_vendor: hw_epilog_process
07-28 12:05:25.748  6868  7344 D bt_hci_bdroid: cleanup Finalizing cleanup
07-28 12:05:25.748  6868  7344 D bt_userial_mct: userial_close,
,07-28 12:05:25.748  6868  7344 E bt_userial_mct: pthread_join() FAILED result:3
07-28 12:05:25.748  6868  7344 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
07-28 12:05:25.761  6868  7344 D bt_hci_bdroid: set_power 0
07-28 12:05:25.762  6868  7344 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,07-28 12:05:25.762  6868  7344 I bt_vendor: bluetooth satus is on
07-28 12:05:25.776  6868  7344 I bt_vendor: bt-vendor : resetting BT status
07-28 12:05:25.776  6868  7344 I bt_vendor: Starting hciattach daemon,
,07-28 12:05:25.776  6868  7344 I bt_vendor: try to set false
,07-28 12:05:25.782  6868  7344 I bt_vendor: Starting hciattach daemon
07-28 12:05:25.782  6868  7344 I bt_vendor: try to set false
07-28 12:05:25.785  6868  7344 I bt_vendor: cleanup
07-28 12:05:25.786  6868  7410 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
07-28 12:05:25.786  6868  7344 I GKI_LINUX: GKI_exit_task 0 done
07-28 12:05:25.786  6868  7344 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
07-28 12:05:25.788  6868  7340 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
07-28 12:05:25.793  6868  6868 D HeadsetService: Received stop request...Stopping profile...
,07-28 12:05:25.798  6868  6868 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
07-28 12:05:25.798  6868  6868 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-28 12:05:25.798  6868  6868 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@289ea772
07-28 12:05:25.800  6868  7363 D HeadsetStateMachine: Exit Disconnected: -1
07-28 12:05:25.802  1851  1851 D BluetoothHeadset: Proxy object disconnected
07-28 12:05:25.802  1851  1851 D BluetoothHeadset: Proxy object disconnected
07-28 12:05:25.803  1851  1851 D BluetoothHeadset: Proxy object disconnected
07-28 12:05:25.804  1032  1032 D BluetoothHeadset: Proxy object disconnected
07-28 12:05:25.804  1032  1032 D AudioService: onServiceDisconnected: Bluetooth profile: 1
07-28 12:05:25.805  6868  6868 D A2dpService: Received stop request...Stopping profile...
,07-28 12:05:25.808  6868  7402 D A2dpStateMachine: Exit Disconnected: -1
07-28 12:05:25.810  6868  7340 D BluetoothAdapterState: Stopping profile services that were post enabled
07-28 12:05:25.811  6868  6868 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
07-28 12:05:25.814  6868  6868 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
07-28 12:05:25.814  6868  6868 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
07-28 12:05:25.814  6868  6868 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@289ea772
07-28 12:05:25.816  1032  1032 D BluetoothA2dp: Proxy object disconnected
07-28 12:05:25.816  1032  1032 D AudioService: onServiceDisconnected: Bluetooth profile: 2
07-28 12:05:25.817  6868  6868 D HidService: Received stop request...Stopping profile...
07-28 12:05:25.817  6868  6868 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@289ea772
,07-28 12:05:25.822  6868  6868 D HealthService: Received stop request...Stopping profile...
07-28 12:05:25.822  6868  6868 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@289ea772
07-28 12:05:25.825  6868  6868 D PanService: Received stop request...Stopping profile...
07-28 12:05:25.826  6868  6868 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@289ea772
07-28 12:05:25.827  6868  6868 D HeadsetStateMachine: Unbinding service...
07-28 12:05:25.830  6868  6868 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-28 12:05:25.830  6868  6868 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-28 12:05:25.830  6868  6868 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-28 12:05:25.830  6868  6868 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-28 12:05:25.830  6868  6868 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-28 12:05:25.830  6868  6868 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-28 12:05:25.830  6868  6868 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
07-28 12:05:25.831  6868  6868 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-28 12:05:25.835  6868  6868 D BtGatt.GattService: Received stop request...Stopping profile...
07-28 12:05:25.835  6868  6868 D BtGatt.GattService: stop()
07-28 12:05:25.836  6868  6868 D BtGatt.AdvertiseManager: advertise clients cleared
07-28 12:05:25.838  6868  6868 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@289ea772
07-28 12:05:25.839  6868  6868 D BluetoothMapService: Received stop request...Stopping profile...
07-28 12:05:25.839  6868  6868 D BluetoothMapService: stop()
07-28 12:05:25.840  6868  6868 D BluetoothMapEmailAppObserver: deinitObservers()
07-28 12:05:25.840  6868  6868 D BluetoothMapEmailAppObserver: removeReceiver()
07-28 12:05:25.841  6868  6868 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@289ea772
07-28 12:05:25.842  6868  6868 I BluetoothA2dpServiceJni: cleanupNative
07-28 12:05:25.842  6868  7403 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
07-28 12:05:25.842  6868  6868 I GKI_LINUX: GKI_exit_task 2 done
07-28 12:05:25.842  6868  6868 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
07-28 12:05:25.843  6868  6868 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-28 12:05:25.843  6868  6868 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-28 12:05:25.843  6868  6868 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,07-28 12:05:25.846  6868  6868 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-28 12:05:25.846  6868  6868 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-28 12:05:25.847  6868  6868 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-28 12:05:25.847  6868  6868 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-28 12:05:25.849  6868  6868 V BluetoothMapService: Handler(): got msg=4
07-28 12:05:25.849  6868  6868 D BluetoothMapService: MAP Service closeService in
07-28 12:05:25.849  6868  6868 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-28 12:05:25.849  6868  6868 V BluetoothMapService: MAP Service closeService out
07-28 12:05:25.850  6868  7340 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
07-28 12:05:25.850  6868  7340 D BluetoothAdapterProperties: Setting state to 10
07-28 12:05:25.850  6868  7340 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
07-28 12:05:25.851  1032  1097 D BluetoothManagerService: Message: 60
07-28 12:05:25.851  1032  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
07-28 12:05:25.851  1032  1097 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
07-28 12:05:25.851  1032  1097 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 12:05:25.851  6868  7340 I BluetoothAdapterState: Entering OffState
07-28 12:05:25.852  6720  6736 D BluetoothPan: onBluetoothStateChange on: false
07-28 12:05:25.853  6868  6868 D BluetoothMapService: cleanup()
07-28 12:05:25.853  6868  6868 D BluetoothMapService: MAP Service closeService in
07-28 12:05:25.853  6868  6868 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-28 12:05:25.853  6868  6868 V BluetoothMapService: MAP Service closeService out
07-28 12:05:25.854  6720  6736 D BluetoothPbap: onBluetoothStateChange: up=false
07-28 12:05:25.855  1851  1867 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-28 12:05:25.858  1851  1866 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 12:05:25.859  6720  6736 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-28 12:05:25.860  6720  6736 D BluetoothMap: onBluetoothStateChange: up=false
07-28 12:05:25.861  1032  1097 D BluetoothA2dp: onBluetoothStateChange: up=false
07-28 12:05:25.861  6720  6736 D BluetoothA2dp: onBluetoothStateChange: up=false
07-28 12:05:25.862  1851  2473 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 12:05:25.862  6720  6736 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 12:05:25.863  1032  1097 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
07-28 12:05:25.863  1032  1097 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
07-28 12:05:25.867  1032  1097 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
07-28 12:05:25.867  1032  1097 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
07-28 12:05:25.867  1032  1097 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@1f72e0ae mBinding = false
,07-28 12:05:25.869  1032  1097 D BluetoothManagerService: Sending unbind request.
07-28 12:05:25.874  6868  7344 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
07-28 12:05:25.875  6868  6868 I GKI_LINUX: GKI_exit_task 1 done
07-28 12:05:25.875  6868  6868 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
07-28 12:05:25.876  6868  6868 I BluetoothServiceJni: cleanupNative: return from cleanup
07-28 12:05:25.876  6868  6868 I art     : --- WEIRD: removing null entry 248
07-28 12:05:25.876  6868  6868 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
07-28 12:05:25.876  6868  6868 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
07-28 12:05:25.877  6868  6868 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
07-28 12:05:25.879  1032  1097 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,07-28 12:05:25.882  6868  6868 I art     : System.exit called, status: 0
07-28 12:05:25.882  6868  6868 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
07-28 12:05:25.901   329  2216 V AudioFlinger: 6868 died, releasing its sessions
07-28 12:05:25.901   329  2216 V AudioFlinger:  pid 1851 @ 0
07-28 12:05:25.901   329  2216 V AudioFlinger:  pid 3454 @ 1
07-28 12:05:25.901   329  2216 V AudioFlinger:  pid 3454 @ 2
,07-28 12:05:25.904  1940  1940 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
07-28 12:05:25.905  1940  2165 D LGBluetoothAPIService: Message: 101
07-28 12:05:25.905  1940  2165 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
07-28 12:05:25.905  1940  2165 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
07-28 12:05:25.905  1940  2165 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
07-28 12:05:25.906  6720  6720 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
07-28 12:05:25.909  1032  2026 I ActivityManager: Process com.android.bluetooth (pid 6868) has died
07-28 12:05:25.910  1032  2026 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
07-28 12:05:25.910  1032  2026 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 14000ms
07-28 12:05:25.915  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:05:25.919  1940  2165 D LGBluetoothAPIService: Message: 2
07-28 12:05:25.919  1940  2165 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
07-28 12:05:25.919  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:25.920  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:25.920  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-28 12:05:25.925  6720  6720 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
07-28 12:05:25.925  6720  6720 D LGBluetoothEventManager: [BTUI] clear device connection state
07-28 12:05:25.927  6720  6720 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,07-28 12:05:25.941  1602  1602 D BluetoothAdapter: 64968885: getState() :  mService = null. Returning STATE_OFF
07-28 12:05:25.941  1602  1602 D BluetoothAdapter: 64968885: getState() :  mService = null. Returning STATE_OFF
,07-28 12:05:25.982  1032  2037 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7574 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
07-28 12:05:25.984  6720  6720 D DockEventReceiver: finishStartingService: stopping service
,07-28 12:05:26.033  7574  7574 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,07-28 12:05:26.033  7574  7574 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-28 12:05:26.034  7574  7574 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
07-28 12:05:26.034  7574  7574 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
07-28 12:05:26.052  7574  7574 D BluetoothAdapterApp: Loading JNI Library
,07-28 12:05:26.088  7574  7574 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@147d4f1a Instance Count = 1
,07-28 12:05:26.094  7574  7574 D BluetoothAdapterApp: onCreate
07-28 12:05:26.119  7574  7574 D ProfileConfigQcom: [BTUI] HeadsetService is supported
07-28 12:05:26.119  7574  7574 D ProfileConfigQcom: Adding HeadsetService
,07-28 12:05:26.119  7574  7574 D ProfileConfigQcom: [BTUI] A2dpService is supported
07-28 12:05:26.119  7574  7574 D ProfileConfigQcom: Adding A2dpService
07-28 12:05:26.120  7574  7574 D ProfileConfigQcom: [BTUI] HidService is supported
07-28 12:05:26.120  7574  7574 D ProfileConfigQcom: Adding HidService
07-28 12:05:26.120  7574  7574 D ProfileConfigQcom: [BTUI] HealthService is supported
07-28 12:05:26.120  7574  7574 D ProfileConfigQcom: Adding HealthService
07-28 12:05:26.120  7574  7574 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
07-28 12:05:26.121  7574  7574 D ProfileConfigQcom: [BTUI] PanService is supported
07-28 12:05:26.122  7574  7574 D ProfileConfigQcom: Adding PanService
07-28 12:05:26.122  7574  7574 D ProfileConfigQcom: [BTUI] GattService is supported
07-28 12:05:26.122  7574  7574 D ProfileConfigQcom: Adding GattService
07-28 12:05:26.122  7574  7574 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
07-28 12:05:26.122  7574  7574 D ProfileConfigQcom: Adding BluetoothMapService
07-28 12:05:26.123  7574  7574 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
07-28 12:05:26.124  7574  7574 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-28 12:05:26.125  7574  7574 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:26.125  7574  7574 V BluetoothPbapReceiver: ***********state = 10
07-28 12:05:26.127  7574  7574 V LGMDMManagerInternal: Create singleton instance
07-28 12:05:26.196  2126  2126 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-28 12:05:26.202  6720  6720 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,07-28 12:05:26.205  7574  7574 D LGBluetoothAPIServer: [BTUI] onCreate()
07-28 12:05:26.205  7574  7574 D LGBluetoothAPIServer: [BTUI] onBind()
07-28 12:05:26.213  1940  1940 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
07-28 12:05:26.214  1940  2165 D LGBluetoothAPIService: Message: 100
07-28 12:05:26.214  1940  2165 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,07-28 12:05:26.222  6720  6720 D BluetoothPermissionRequest: onReceive
,07-28 12:05:26.224  6720  6720 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
07-28 12:05:26.224  6720  6720 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
07-28 12:05:26.227  6720  6720 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-28 12:05:26.238  7574  7574 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,07-28 12:05:26.246  7574  7574 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:26.250  7574  7574 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-28 12:05:26.250  7574  7574 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-28 12:05:26.251  7574  7574 V BluetoothSapReceiver: SapReceiver onReceive 
07-28 12:05:26.252  7574  7574 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:26.252  7574  7574 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,07-28 12:05:26.255  6801  6801 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,07-28 12:05:27.792  6524  6666 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:05:27.792  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:05:27.918  1602  1602 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,07-28 12:05:28.016  1032  1092 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7603 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,07-28 12:05:28.022  1602  1602 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,07-28 12:05:28.023  1602  1602 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
07-28 12:05:28.050  1032  1426 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-28 12:05:28.056  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
07-28 12:05:28.068  1032  1032 D administrator: Handling package changes for user 0
,07-28 12:05:28.076  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,07-28 12:05:28.111  7603  7603 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,07-28 12:05:28.166  1032  1032 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,07-28 12:05:28.166  1032  1032 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,07-28 12:05:28.175  7603  7603 D LgDataFeature: LgDataFeature() Constructor: none
07-28 12:05:28.175  7603  7603 D LgDataFeature: LgDataFeature() Constructor Done, null
07-28 12:05:28.217  1032  1091 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-28 12:05:28.223  1032  1091 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
07-28 12:05:28.232  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,07-28 12:05:28.236  2455  2455 V GmsNetworkLocationProvi: DISABLE
07-28 12:05:28.265  1032  1091 D LocationProviderProxy: applying state to connected service
,07-28 12:05:28.267  2455  2455 E GCoreFlp: Bound FusedProviderService with LocationManager
,07-28 12:05:28.297  7603  7649 I Babel   : MmsConfig: mnc/mcc: 0/0
07-28 12:05:28.298  7603  7649 I Babel   : MmsConfig.loadMmsSettings
07-28 12:05:28.309  7603  7649 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
07-28 12:05:28.310  7603  7649 I Babel   : MmsConfig.loadFromDatabase
,07-28 12:05:28.320  7603  7603 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:28.324  7603  7649 E Babel   : canonicalizeMccMnc: invalid mccmnc 
07-28 12:05:28.324  7603  7649 I Babel   : MmsConfig.loadFromResources
,07-28 12:05:28.326  7603  7649 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
07-28 12:05:28.326  7603  7649 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
07-28 12:05:28.331  7603  7647 W AudioCapabilities: Unsupported mime audio/evrc
07-28 12:05:28.332  7603  7647 W AudioCapabilities: Unsupported mime audio/qcelp
07-28 12:05:28.335  7603  7647 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-28 12:05:28.357  1816  7651 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
07-28 12:05:28.357  1816  7651 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,07-28 12:05:28.360  6920  6920 I AppUp4:CustModeStarterReceiver: onReceive
07-28 12:05:28.365  6920  6920 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2e3ae2d4
07-28 12:05:28.365  6920  6920 D AppUp4:CustFacade: isCustomizationCompleted : false
07-28 12:05:28.365  6920  6920 D AppUp4:CustFacade: isPhone : true
07-28 12:05:28.365  6920  6920 D AppUp4:CustModeStarterReceiver: begin check event
,07-28 12:05:28.365  7603  7647 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
07-28 12:05:28.365  6920  6920 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
07-28 12:05:28.367  7603  7647 W AudioCapabilities: Unsupported mime audio/qcelp
07-28 12:05:28.370  1816  4756 I Icing   : updateResources: need to parse e{com.google.android.gms}
07-28 12:05:28.370  7603  7647 W AudioCapabilities: Unsupported mime audio/evrc
,07-28 12:05:28.383  7603  7647 W VideoCapabilities: Unsupported mime video/x-ms-wmv
07-28 12:05:28.385  7603  7647 W VideoCapabilities: Unsupported mime video/divx
07-28 12:05:28.389  7603  7647 W VideoCapabilities: Unsupported mime video/divx311
,07-28 12:05:28.392  7603  7647 W VideoCapabilities: Unsupported mime video/divx4
07-28 12:05:28.399  7603  7647 W VideoCapabilities: Unsupported mime video/mp4v-esdp
07-28 12:05:28.401  1032  2013 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7654 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,07-28 12:05:28.403  1032  2013 I ActivityManager: Killing 6737:com.lge.sync/1000 (adj 15): empty #17
,07-28 12:05:28.422  1032  1544 D WifiService: Client connection lost with reason: 4
,07-28 12:05:28.428  7603  7647 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
07-28 12:05:28.431  7603  7647 W AudioCapabilities: Unsupported mime audio/eac3
07-28 12:05:28.432  7603  7647 W AudioCapabilities: Unsupported mime audio/ac3
07-28 12:05:28.433  7603  7647 W AudioCapabilities: Unsupported mime audio/g726
07-28 12:05:28.433  7603  7647 W AudioCapabilities: Unsupported mime audio/wma-voice
07-28 12:05:28.434  7603  7647 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,07-28 12:05:28.435  7603  7647 W AudioCapabilities: Unsupported mime audio/adpcm
,07-28 12:05:28.436  7603  7647 W VideoCapabilities: Unsupported mime video/theora
07-28 12:05:28.438  7603  7647 W VideoCapabilities: Unsupported mime video/mjpg
,07-28 12:05:28.520  1032  1047 W libprocessgroup: failed to open /acct/uid_1000/pid_6737/cgroup.procs: No such file or directory
07-28 12:05:28.559  7654  7654 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-28 12:05:28.560  7654  7654 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,07-28 12:05:28.560  7654  7654 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
07-28 12:05:28.564  7654  7654 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
07-28 12:05:28.565  7654  7654 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-28 12:05:28.646  7654  7654 I SystemConfig: BUILD Country: EU
,07-28 12:05:28.646  7654  7654 I SystemConfig: BUILD Operator: OPEN
07-28 12:05:28.699  1032  1921 I ActivityManager: Killing 6944:com.lge.email/u0a23 (adj 15): empty #17
,07-28 12:05:28.761  1032  2037 W libprocessgroup: failed to open /acct/uid_10023/pid_6944/cgroup.procs: No such file or directory
,07-28 12:05:28.767  7654  7675 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
07-28 12:05:28.767  7654  7675 I SystemConfig: existFile = false
07-28 12:05:28.767  7654  7675 I SystemConfig: canReadFile = false
07-28 12:05:28.767  7654  7675 I SystemConfig: systemFeature RCS result false
07-28 12:05:28.767  7654  7675 D SystemConfig: refreshRcsSupport() :false
07-28 12:05:28.808  1032  1921 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7677 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,07-28 12:05:28.886  7677  7677 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-28 12:05:28.887  7677  7677 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,07-28 12:05:28.887  7677  7677 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
07-28 12:05:28.887  7677  7677 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
07-28 12:05:28.999  7677  7677 I AppConfig: Total System Memory = 2995761152
,07-28 12:05:29.015  7677  7677 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,07-28 12:05:29.116  1032  1957 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7699 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-28 12:05:29.117  1032  1957 I ActivityManager: Killing 6822:com.lge.formmanager/u0a26 (adj 15): empty #17
07-28 12:05:29.200  1032  1939 W libprocessgroup: failed to open /acct/uid_10026/pid_6822/cgroup.procs: No such file or directory
,07-28 12:05:29.432  7699  7699 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,07-28 12:05:29.563  7699  7699 D LgDataFeature: LgDataFeature() Constructor: none
07-28 12:05:29.563  7699  7699 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-28 12:05:29.615  7699  7699 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,07-28 12:05:29.636  7699  7699 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-28 12:05:29.637  7699  7699 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
07-28 12:05:29.654  7699  7699 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
07-28 12:05:29.655  7699  7699 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,07-28 12:05:29.685  1032  1957 I ActivityManager: Killing 6338:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,07-28 12:05:29.771  1032  2013 W libprocessgroup: failed to open /acct/uid_1000/pid_6338/cgroup.procs: No such file or directory
,07-28 12:05:29.779  2858  4468 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,07-28 12:05:29.780  4595  7744 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
07-28 12:05:29.786  2858  4468 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1d5bf9b8 on behalf of 7699
,07-28 12:05:29.831  1032  2051 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7745 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,07-28 12:05:29.878  7699  7699 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,07-28 12:05:29.907  7699  7699 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,07-28 12:05:29.928  7745  7745 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,07-28 12:05:29.974  7745  7745 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,07-28 12:05:29.975  7745  7745 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
07-28 12:05:29.975  7745  7745 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
07-28 12:05:29.975  7745  7745 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
07-28 12:05:29.975  7745  7745 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
07-28 12:05:29.975  7745  7745 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,07-28 12:05:29.995  1032  2037 I ActivityManager: Killing 6997:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,07-28 12:05:30.039  7491  7545 D UEI.SmartControl: Internal timer expired: 1
07-28 12:05:30.039  7491  7545 D UEI.SmartControl: unbind internal service
,07-28 12:05:30.114  1032  1047 W libprocessgroup: failed to open /acct/uid_10046/pid_6997/cgroup.procs: No such file or directory
,07-28 12:05:30.128  7491  7491 D UEI.SmartControl: Service.onUnbind: IControl
07-28 12:05:30.129  7491  7491 D UEI.SmartControl: Service.onDestroy
,07-28 12:05:30.130  7491  7491 D UEI.SmartControl: Lock is in USE false
07-28 12:05:30.130  7491  7491 D UEI.SmartControl: unbind internal service
07-28 12:05:30.134  7491  7491 D serial_port: close(fd = 25)
07-28 12:05:30.141  7491  7491 I UEI.SmartControl: Serial port is closed.
07-28 12:05:30.141  7491  7491 I UEI.SmartControl: Serial port is closed.
07-28 12:05:30.142  7491  7491 D UEI.SmartControl: Blaster closed
07-28 12:05:30.143  7491  7491 D UEI.SmartControl: Shut down QS...
,07-28 12:05:30.145  7491  7491 D UEI.SmartControl: Stopping QS lib
07-28 12:05:30.146  7491  7491 D UEI.SmartControl: QS lib stop result = true
07-28 12:05:30.146  7491  7491 D UEI.SmartControl: Stopped QS lib
07-28 12:05:30.147  7491  7491 D UEI.SmartControl: Stopped file observer...
07-28 12:05:30.147  7491  7491 D UEI.SmartControl: QS shutdown complete
07-28 12:05:30.304  1032  1993 V SIM_STK : Menu title from STK is T-Mobile
,07-28 12:05:30.332  4595  7744 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 551 ms] updated apps [took 551 ms] 
,07-28 12:05:30.802  6524  6666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-28 12:05:30.803  6524  6666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1b5b82d0 added. We now have 6 listener(s)
07-28 12:05:30.803  6524  6666 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:05:30.812  6524  6666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:05:30.812  6524  6666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4b242c9 added. We now have 7 listener(s)
07-28 12:05:30.812  6524  6666 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:05:30.813  6524  6666 I System.out: IsBluetoothEnabled
07-28 12:05:30.814  1032  2051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:05:30.814  1032  2051 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
07-28 12:05:30.814  1032  1097 D BluetoothManagerService: Message: 2
07-28 12:05:30.817  6524  6666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:30.818  1032  1885 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:05:30.818  1032  1885 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,07-28 12:05:30.835  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-28 12:05:30.835  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-28 12:05:30.835  1032  1032 D Ulp_jni : JNI:system_update. Event-4
07-28 12:05:30.836  1032  1097 D BluetoothManagerService: Message: 1
07-28 12:05:30.836  1032  1097 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
07-28 12:05:30.860  1032  1097 D BluetoothManagerService: Message: 20
07-28 12:05:30.860  1032  1097 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@25d4c5cf:true
,07-28 12:05:30.864  7574  7574 D BluetoothAdapterState: make
07-28 12:05:30.869  7574  7574 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
07-28 12:05:30.869  7574  7574 I bluedroid-qcom: init
07-28 12:05:30.871  7574  7790 I BluetoothAdapterState: Entering OffState
07-28 12:05:30.871  7574  7574 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
07-28 12:05:30.871  7574  7574 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-28 12:05:30.871  7574  7574 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-28 12:05:30.871  7574  7574 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-28 12:05:30.871  7574  7574 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
07-28 12:05:30.873  7574  7574 I bluedroid-qcom: get_profile_interface socket
07-28 12:05:30.873  7574  7574 I bluedroid-qcom: get_profile_interface map_client
,07-28 12:05:30.878  7574  7794 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
07-28 12:05:30.875  7793  7793 W bdaddr_loader: type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:05:30.883  7574  7794 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
07-28 12:05:30.875  7793  7793 W bdaddr_loader: type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:05:30.894  7793  7793 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
07-28 12:05:30.894  7793  7793 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
07-28 12:05:30.894  7793  7793 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,07-28 12:05:30.899  1032  1032 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
07-28 12:05:30.899  1032  1032 D BluetoothManagerService: Bluetooth Adapter name changed to G3
07-28 12:05:30.899  1032  1032 D BluetoothManagerService: Stored Bluetooth name: G3
07-28 12:05:30.899  1032  1097 D BluetoothManagerService: Message: 40
07-28 12:05:30.899  1032  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
07-28 12:05:30.900  7574  7590 I bluedroid-qcom: config_hci_snoop_log
07-28 12:05:30.902  1032  1097 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
07-28 12:05:30.902  1032  1097 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
07-28 12:05:30.902  7793  7793 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
07-28 12:05:30.909  7793  7793 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
07-28 12:05:30.909  7793  7793 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,07-28 12:05:30.915  7574  7790 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
07-28 12:05:30.915  7574  7794 D BluetoothAdapterProperties: Name is: G3
07-28 12:05:30.916  7574  7790 D BluetoothAdapterProperties: Setting state to 11
07-28 12:05:30.916  7574  7790 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
07-28 12:05:30.917  1032  1097 D BluetoothManagerService: Message: 60
07-28 12:05:30.917  1032  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
07-28 12:05:30.917  1032  1097 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
07-28 12:05:30.918  7574  7790 I LGBluetoothServiceJni: classInitNative: succeeds
07-28 12:05:30.925  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:05:30.928  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-28 12:05:30.929  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:30.934  6720  6720 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
07-28 12:05:30.940  7574  7574 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-28 12:05:30.940  7574  7574 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:30.940  7574  7574 V BluetoothPbapReceiver: ***********state = 11
,07-28 12:05:30.959  2126  2126 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-28 12:05:30.959  7574  7790 D BluetoothBondStateMachine: make
,07-28 12:05:30.964  7574  7790 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16be37c3
07-28 12:05:30.964  7574  7807 I BluetoothBondStateMachine: StableState(): Entering Off State
07-28 12:05:30.964  7574  7790 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
07-28 12:05:30.964  7574  7790 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16be37c3
07-28 12:05:30.965  7574  7790 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
07-28 12:05:30.965  7574  7790 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
07-28 12:05:30.971  7574  7790 E BluetoothAdapterService: File transfer profiles supported!!
07-28 12:05:30.979  7574  7790 E BluetoothAdapterService: File transfer profiles supported!!
,07-28 12:05:30.983  7574  7574 D HeadsetService: Received start request. Starting profile...
07-28 12:05:30.983  7574  7574 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
07-28 12:05:30.984  7574  7574 D LGBluetoothHfpAdapter: Version 1.6
07-28 12:05:30.985  7574  7790 E BluetoothAdapterService: File transfer profiles supported!!
07-28 12:05:30.987  7574  7574 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-28 12:05:30.988  7574  7574 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-28 12:05:30.989  7574  7574 D HeadsetStateMachine: make
07-28 12:05:30.992  7574  7790 E BluetoothAdapterService: File transfer profiles supported!!
,07-28 12:05:31.000  7574  7790 E BluetoothAdapterService: File transfer profiles supported!!
07-28 12:05:31.000  6720  6720 D BluetoothPermissionRequest: onReceive
07-28 12:05:31.007  7574  7790 E BluetoothAdapterService: File transfer profiles supported!!
,07-28 12:05:31.012  6720  6720 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-28 12:05:31.017  7574  7790 E BluetoothAdapterService: File transfer profiles supported!!
07-28 12:05:31.025  7574  7574 D LgDataFeature: LgDataFeature() Constructor: none
07-28 12:05:31.026  7574  7574 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-28 12:05:31.030  7574  7574 D HeadsetStateMachine: max_hf_connections = 1
07-28 12:05:31.030  7574  7574 I bluedroid-qcom: get_profile_interface handsfree
07-28 12:05:31.031  7574  7574 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
07-28 12:05:31.031   329  1387 V AudioPolicyService: registerClient() client 0xb558a740, uid 1002
07-28 12:05:31.032   329   329 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
07-28 12:05:31.032   329   329 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-28 12:05:31.032   329   329 V AudioPolicyManagerEx: getOutput() returns output 2
07-28 12:05:31.032  7574  7574 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
07-28 12:05:31.032   329  2215 V AudioFlinger: registerClient() client 0xb57d92e0, pid 7574
07-28 12:05:31.032   329  1381 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 12:05:31.032   329  1381 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-28 12:05:31.033   329  1382 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 12:05:31.033   329  1382 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-28 12:05:31.033  1602  1625 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 12:05:31.033  1602  1625 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-28 12:05:31.033  1851  1866 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 12:05:31.033  1851  1866 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-28 12:05:31.033  1602  1625 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 12:05:31.033  1602  1625 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-28 12:05:31.033  1851  1866 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 12:05:31.033  1851  1866 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-28 12:05:31.033  3454  3470 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 12:05:31.033  3454  3470 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-28 12:05:31.033  3454  3470 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 12:05:31.033  3454  3470 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-28 12:05:31.033  1032  2037 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 12:05:31.033  1032  2037 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-28 12:05:31.033  1032  2037 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 12:05:31.033  1032  2037 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-28 12:05:31.033  7574  7591 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 12:05:31.034  7574  7591 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
07-28 12:05:31.034  7574  7591 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 12:05:31.034  7574  7790 V LGMDMManager: Create singleton instance
07-28 12:05:31.034  7574  7591 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
07-28 12:05:31.034  7574  7574 V ToneGenerator: Create Track: 0xb4928a80
07-28 12:05:31.034  7574  7574 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
07-28 12:05:31.034  7574  7574 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
07-28 12:05:31.034   329  2216 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
07-28 12:05:31.034   329  2216 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
07-28 12:05:31.034   329  2216 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-28 12:05:31.034   329  2216 V AudioPolicyManagerEx: getOutput() returns output 2
07-28 12:0,5:31.034   329  1387 I AudioFlinger: isAudioPlaybackHookOn() false
07-28 12:05:31.034   329   329 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
07-28 12:05:31.034   329   329 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
07-28 12:05:31.035   329   329 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-28 12:05:31.035   329   329 V AudioPolicyManagerEx: getOutput() returns output 2
07-28 12:05:31.035  7574  7574 V AudioSystem: getLatency() output 2, latency 50
07-28 12:05:31.035  7574  7574 V AudioSystem: getFrameCount() output 2, frameCount 960
07-28 12:05:31.035  7574  7574 V AudioTrack: createTrack_l() output 2 afLatency 50
07-28 12:05:31.035   329  2215 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
07-28 12:05:31.035   329  2215 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
07-28 12:05:31.035   329  2215 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
07-28 12:05:31.035   329  2215 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
07-28 12:05:31.035   329  2215 V AudioFlinger: createTrack() lSessionId: 23
07-28 12:05:31.036  7574  7574 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
07-28 12:05:31.036   329  2215 V AudioFlinger: acquiring 23 from 7574, for 7574
07-28 12:05:31.036   329  2215 V AudioFlinger:  added new entry for 23
07-28 12:05:31.036  7574  7574 V ToneGenerator: ToneGenerator INIT OK, time: 151088
07-28 12:05:31.036  7574  7574 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16be37c3
07-28 12:05:31.037  7574  7812 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
07-28 12:05:31.037  7574  7812 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-28 12:05:31.037  7574  7812 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-28 12:05:31.038  7574  7812 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
,07-28 12:05:31.039   329  1386 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7574
07-28 12:05:31.039   329  1386 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
07-28 12:05:31.039   329  1386 V voice   : voice_set_parameters: enter: bt_samplerate=8000
07-28 12:05:31.039   329  1386 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
07-28 12:05:31.039   329  1386 V compress_voip: voice_extn_compress_voip_set_parameters: exit
07-28 12:05:31.039   329  1386 V voice   : voice_set_parameters: exit with code(0)
07-28 12:05:31.039   329  1386 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
07-28 12:05:31.039   329  1386 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
07-28 12:05:31.040   329  1386 V msm8974_platform: platform_set_parameters: exit with code(0)
07-28 12:05:31.040   329  1386 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
07-28 12:05:31.040   329  1386 V audio_hw_primary: adev_set_parameters: exit with code(0)
07-28 12:05:31.040   329  1386 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
07-28 12:05:31.040  7574  7812 V ToneGenerator: ToneGenerator destructor
07-28 12:05:31.040  7574  7812 V ToneGenerator: stopTone
07-28 12:05:31.040  7574  7812 V ToneGenerator: Delete Track: 0xb4928a80
07-28 12:05:31.040  7574  7812 V AudioTrack: ~AudioTrack, releasing session id from 7574 on behalf of 7574
07-28 12:05:31.040   329  2216 V AudioPolicyService: AudioCommandThread() adding release output 2
07-28 12:05:31.040   329  2216 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
07-28 12:05:31.040   329  2216 V AudioFlinger: PlaybackThread::Track destructor
07-28 12:05:31.040   329  1105 V AudioPolicyService: AudioCommandThread() waking up
07-28 12:05:31.040   329  2216 V AudioFlinger: removeClient_l() pid 7574, calling pid 329
07-28 12:05:31.040   329  1105 V AudioPolicyService: AudioCommandThread() processing release output 2
07-28 12:05:31.040   329  1105 V AudioPolicyManager: releaseOutput() 2
07-28 12:05:31.040  7574  7574 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16be37c3
07-28 12:05:31.040   329  1105 V AudioPolicyService: AudioCommandThread() going to sleep
07-28 12:05:31.041   329  2215 V AudioFlinger: releasing 23 from 7574 for 7574
07-28 12:05:31.041   329  2215 V AudioFlinger:  decremented refcount to 0
07-28 12:05:31.041   329  2215 V AudioFlinger: purging stale effects
07-28 12:05:31.041  7574  7790 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
07-28 12:05:31.043  7574  7574 D A2dpService: Received start request. Starting profile...
07-28 12:05:31.043  1032  2013 W Process : Unable to open /proc/7814/status
07-28 12:05:31.043  7574  7574 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-28 12:05:31.044  7574  7574 V Avrcp   : make
07-28 12:05:31.045  7574  7574 D Avrcp   : [BTUI] Use Native AVRCP : init jni
07-28 12:05:31.045  7574  7574 I bluedroid-qcom: get_profile_interface avrcp
07-28 12:05:31.052  7574  7574 V AudioManager: registerRemoteController: size of Media player list: 0
,07-28 12:05:31.055  7574  7574 E AudioManager: No RCC entry present to update
07-28 12:05:31.055  7574  7574 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
07-28 12:05:31.058  7574  7574 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
07-28 12:05:31.059  7574  7574 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
07-28 12:05:31.059  7574  7574 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
07-28 12:05:31.062  7574  7574 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
07-28 12:05:31.166  1032  1642 V SIM_STK : Menu title from STK is T-Mobile
07-28 12:05:31.166  1032  1642 V SIM_STK : Menu title from STK is T-Mobile
,07-28 12:05:31.284  1032  2013 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,07-28 12:05:31.304  7574  7574 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,07-28 12:05:31.310  7574  7574 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
07-28 12:05:31.310  7574  7574 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
07-28 12:05:31.310  7574  7574 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
07-28 12:05:31.310  7574  7574 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
07-28 12:05:31.311  7574  7574 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-28 12:05:31.311  7574  7574 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
07-28 12:05:31.311  7574  7574 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
07-28 12:05:31.311  7574  7574 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
07-28 12:05:31.311  7574  7574 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-28 12:05:31.311  7574  7574 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
07-28 12:05:31.311  7574  7574 I BluetoothA2dpServiceJni: classInitNative
07-28 12:05:31.311  7574  7574 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-28 12:05:31.311  7574  7574 D A2dpStateMachine: make
07-28 12:05:31.314  7574  7574 I bluedroid-qcom: get_profile_interface a2dp
07-28 12:05:31.314  7574  7821 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
07-28 12:05:31.317  7574  7574 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
07-28 12:05:31.317  7574  7574 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
07-28 12:05:31.318  7574  7574 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16be37c3
07-28 12:05:31.318  7574  7820 D A2dpStateMachine: Enter Disconnected: -2
07-28 12:05:31.319  7574  7574 I BluetoothHidServiceJni: classInitNative: succeeds
,07-28 12:05:31.320  7574  7574 D HidService: Received start request. Starting profile...
07-28 12:05:31.320  7574  7574 I bluedroid-qcom: get_profile_interface hidhost
,07-28 12:05:31.320  7574  7574 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16be37c3
07-28 12:05:31.321  7574  7574 I BluetoothHealthServiceJni: classInitNative: succeeds
07-28 12:05:31.322  7574  7574 D HealthService: Received start request. Starting profile...
07-28 12:05:31.325  7574  7574 I bluedroid-qcom: get_profile_interface health
07-28 12:05:31.325  7574  7574 I LGBluetoothHealthServiceJni: classInitNative: succeeds
07-28 12:05:31.325  7574  7574 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16be37c3
07-28 12:05:31.326  7574  7574 I BluetoothPanServiceJni: classInitNative(L105): succeeds
07-28 12:05:31.327  7574  7574 D PanService: Received start request. Starting profile...
07-28 12:05:31.327  7574  7574 D BluetoothPanServiceJni: initializeNative(L110): pan
07-28 12:05:31.327  7574  7574 I bluedroid-qcom: get_profile_interface pan
07-28 12:05:31.334  7574  7574 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
07-28 12:05:31.334  7574  7574 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16be37c3
07-28 12:05:31.335  7574  7574 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,07-28 12:05:31.339  7574  7574 D BtGatt.DebugUtils: handleDebugAction() action=null
07-28 12:05:31.340  7574  7574 D BtGatt.GattService: Received start request. Starting profile...
07-28 12:05:31.340  7574  7574 D BtGatt.GattService: start()
07-28 12:05:31.340  7574  7574 I bluedroid-qcom: get_profile_interface gatt
07-28 12:05:31.340  7574  7574 D BtGatt.AdvertiseManager: advertise manager created
07-28 12:05:31.348  7574  7574 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16be37c3
07-28 12:05:31.352  7574  7574 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16be37c3
,07-28 12:05:31.353  7574  7574 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
07-28 12:05:31.355  7574  7574 V BluetoothMapService: BluetoothMapBinder()
07-28 12:05:31.357  7574  7574 D BluetoothMapService: Received start request. Starting profile...
07-28 12:05:31.357  7574  7574 D BluetoothMapService: start()
07-28 12:05:31.360  7574  7574 D BluetoothMapEmailSettingsLoader: Found 0 applications
07-28 12:05:31.360  7574  7574 D BluetoothMapEmailAppObserver: createReceiver()
07-28 12:05:31.361  7574  7574 D BluetoothMapEmailAppObserver: initObservers()
07-28 12:05:31.361  7574  7574 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,07-28 12:05:31.368  7574  7574 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16be37c3
,07-28 12:05:31.368  7574  7574 D HeadsetStateMachine: Proxy object connected
07-28 12:05:31.369  7574  7574 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
07-28 12:05:31.369  7574  7574 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
07-28 12:05:31.370  7574  7812 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-28 12:05:31.371  7574  7812 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-28 12:05:31.372  7574  7812 D HeadsetStateMachine: Disconnected process message: 11, size: 0
07-28 12:05:31.375  7574  7574 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,07-28 12:05:31.383  7574  7574 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,07-28 12:05:31.386  7574  7574 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-28 12:05:31.392  7574  7574 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-28 12:05:31.395  7574  7574 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-28 12:05:31.395  7574  7574 V PanService: [BTUI] SIM Extra State :ABSENT
,07-28 12:05:31.397  7574  7574 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:31.401  7574  7574 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
07-28 12:05:31.401  7574  7574 V BluetoothMapService: Handler(): got msg=1
07-28 12:05:31.402  7574  7574 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-28 12:05:31.402  7574  7574 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-28 12:05:31.402  7574  7574 V BluetoothSapReceiver: SapReceiver onReceive 
07-28 12:05:31.402  7574  7574 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:31.402  7574  7790 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
07-28 12:05:31.402  7574  7574 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
07-28 12:05:31.403  7574  7790 I bluedroid-qcom: enable
07-28 12:05:31.404  7574  7790 I bt_hci_bdroid: init
07-28 12:05:31.406  7574  7829 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
07-28 12:05:31.409  7574  7790 I bt_vendor: bt-vendor : init
07-28 12:05:31.409  7574  7790 I bt_vendor: bt-vendor : get_bt_soc_type
07-28 12:05:31.409  7574  7790 E bt_vendor: get_bt_soc_type: Failed to get soc type
,07-28 12:05:31.409  7574  7790 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
07-28 12:05:31.409  7574  7790 D bt_userial_mct: userial_init
07-28 12:05:31.410  7574  7829 I bt-btu  : btu_task pending for preload complete event
07-28 12:05:31.411  7574  7790 D bt_hci_bdroid: set_power 1
07-28 12:05:31.411  7574  7790 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
07-28 12:05:31.411  7574  7790 I bt_vendor: Starting hciattach daemon
07-28 12:05:31.411  7574  7790 I bt_vendor: try to set true
07-28 12:05:31.405  7832  7832 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:05:31.405  7832  7832 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:05:31.450  7833  7833 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,07-28 12:05:31.603  7839  7839 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,07-28 12:05:31.624  7840  7840 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,07-28 12:05:31.650  7845  7845 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,07-28 12:05:31.663  7846  7846 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,07-28 12:05:31.677  7847  7847 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,07-28 12:05:31.693  7848  7848 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,07-28 12:05:31.715  7850  7850 I libmdmdetect: ESOC framework not supported
,07-28 12:05:31.715  7850  7850 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,07-28 12:05:31.724  7850  7850 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
07-28 12:05:31.724  7850  7850 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
07-28 12:05:31.724  7850  7850 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
07-28 12:05:31.724  7850  7850 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
07-28 12:05:31.724  7850  7850 D bthci_qcomm_common: [BTUI]     LE: Class 2
07-28 12:05:31.724  7850  7850 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
07-28 12:05:31.724  7850  7850 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
07-28 12:05:31.760  7850  7851 E QC-QMI  : qmi_client [7850] 15: failed to locate client data
07-28 12:05:31.762   467   467 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
07-28 12:05:31.762   467   467 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,07-28 12:05:31.820  7852  7852 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,07-28 12:05:31.847  7853  7853 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,07-28 12:05:31.865  7574  7790 I bt_vendor: bluetooth satus is on
,07-28 12:05:31.865  7574  7790 D bt_hci_bdroid: preload
,07-28 12:05:31.866  7574  7831 D bt_userial_mct: userial_open(port:0)
07-28 12:05:31.866  7574  7831 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,07-28 12:05:31.870  7574  7831 I bt_vendor: Done intiailizing UART
,07-28 12:05:31.871  7574  7831 I bt_vendor: Done intiailizing UART
,07-28 12:05:31.871  7574  7831 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
07-28 12:05:31.871  7574  7831 I bt_vendor: Bluetooth Firmware and transport layer are initialized
07-28 12:05:31.871  7574  7829 I bt-btu  : btu_task received preload complete event
07-28 12:05:31.872  7574  7829 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
07-28 12:05:31.872  7574  7829 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
07-28 12:05:31.876  7574  7829 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
07-28 12:05:31.876  7574  7855 D bt_userial_mct: Entering userial_read_thread()
07-28 12:05:31.881  7574  7829 I         : BTE_InitTraceLevels -- TRC_HCI
07-28 12:05:31.881  7574  7829 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-28 12:05:31.881  7574  7829 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-28 12:05:31.881  7574  7829 I         : BTE_InitTraceLevels -- TRC_AVDT
07-28 12:05:31.881  7574  7829 I         : BTE_InitTraceLevels -- TRC_AVRC
07-28 12:05:31.881  7574  7829 I         : BTE_InitTraceLevels -- TRC_A2D
07-28 12:05:31.881  7574  7829 I         : BTE_InitTraceLevels -- TRC_BNEP
07-28 12:05:31.881  7574  7829 I         : BTE_InitTraceLevels -- TRC_BTM
07-28 12:05:31.881  7574  7829 I         : BTE_InitTraceLevels -- TRC_HID_HOST
07-28 12:05:31.881  7574  7829 I         : BTE_InitTraceLevels -- TRC_GAP
07-28 12:05:31.881  7574  7829 I         : BTE_InitTraceLevels -- TRC_PAN
07-28 12:05:31.881  7574  7829 I         : BTE_InitTraceLevels -- TRC_SDP
07-28 12:05:31.881  7574  7829 I         : BTE_InitTraceLevels -- TRC_GATT
07-28 12:05:31.881  7574  7829 I         : BTE_InitTraceLevels -- TRC_SMP
07-28 12:05:31.881  7574  7829 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-28 12:05:31.881  7574  7829 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-28 12:05:31.991  7574  7829 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,07-28 12:05:31.991  7574  7829 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa014e061 
,07-28 12:05:31.991  7574  7829 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa014e061 
,07-28 12:05:32.022  7574  7794 E bt-btif : Calling BTA_HhEnable
07-28 12:05:32.022  7574  7794 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
07-28 12:05:32.022  7574  7794 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,07-28 12:05:32.026  1032  1032 D BluetoothManagerService: Bluetooth Adapter name changed to G3
,07-28 12:05:32.026  1032  1032 D BluetoothManagerService: Stored Bluetooth name: G3
,07-28 12:05:32.027  7574  7794 D BluetoothAdapterProperties: Name is: G3
,07-28 12:05:32.028  7574  7794 D BluetoothAdapterProperties: Scan Mode:20
07-28 12:05:32.028  7574  7794 D BluetoothAdapterProperties: Discoverable Timeout:120
07-28 12:05:32.028  7574  7794 D bt_hci_bdroid: postload
07-28 12:05:32.029  7574  7794 D bte_conf: Device ID record 1 : primary
07-28 12:05:32.029  7574  7794 D bte_conf:   vendorId            = 00c4
07-28 12:05:32.029  7574  7794 D bte_conf:   vendorIdSource      = 0001
07-28 12:05:32.029  7574  7794 D bte_conf:   product             = 13a1
07-28 12:05:32.029  7574  7794 D bte_conf:   version             = 1000
07-28 12:05:32.030  7574  7794 D bte_conf:   clientExecutableURL = 
07-28 12:05:32.030  7574  7794 D bte_conf:   serviceDescription  = 
07-28 12:05:32.030  7574  7794 D bte_conf:   documentationURL    = 
07-28 12:05:32.030  7574  7831 D bt_hci_bdroid: Used up Tx Cmd credits
07-28 12:05:32.030  7574  7794 D bte_conf: bte_load_did_conf no section named DID2.
07-28 12:05:32.033  7574  7790 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
07-28 12:05:32.033  7574  7790 D BluetoothAdapterProperties: ScanMode =  20
07-28 12:05:32.034  7574  7790 D BluetoothAdapterProperties: State =  11
07-28 12:05:32.034  7574  7790 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
07-28 12:05:32.034  7574  7790 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
07-28 12:05:32.034  7574  7790 D BluetoothAdapterProperties: Setting state to 12
,07-28 12:05:32.034  7574  7790 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12,
07-28 12:05:32.035  7574  7794 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,07-28 12:05:32.035  7860  7860 W sh      : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:05:32.045  7860  7860 W sh      : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:05:32.058  7574  7831 D bt_hci_bdroid: Used up Tx Cmd credits
,07-28 12:05:32.071  1032  1097 D BluetoothManagerService: Message: 60
07-28 12:05:32.071  1032  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
07-28 12:05:32.071  1032  1097 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
07-28 12:05:32.071  1032  1097 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-28 12:05:32.079  7574  7855 E bt_mct  : hci lib postload completed
07-28 12:05:32.079  7574  7790 I BluetoothAdapterState: Entering On State
07-28 12:05:32.087  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:05:32.087  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:05:32.087  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:32.087  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:05:32.087  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:05:32.087  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:05:32.087  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:05:32.087  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:05:32.093  7574  7794 D BluetoothAdapterProperties: Discoverable Timeout:120
07-28 12:05:32.094  7574  7794 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
07-28 12:05:32.099  6524  6524 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:05:32.115  7574  7790 D LGBluetoothServiceAdapter: [BTUI] OnState
07-28 12:05:32.115  7574  7790 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
07-28 12:05:32.115  7574  7790 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,07-28 12:05:32.123  6720  6735 D BluetoothPan: onBluetoothStateChange on: true
07-28 12:05:32.123  6720  6735 D BluetoothPan: onBluetoothStateChange call bindService
07-28 12:05:32.126  6720  7444 D BluetoothPbap: onBluetoothStateChange: up=true
07-28 12:05:32.128  1032  1032 D BluetoothHeadset: Proxy object connected
,07-28 12:05:32.132  7574  7829 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
07-28 12:05:32.132  7574  7829 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
07-28 12:05:32.132  7574  7829 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
07-28 12:05:32.132  7574  7829 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
07-28 12:05:32.132  7574  7829 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
07-28 12:05:32.132  7574  7829 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
07-28 12:05:32.132  7574  7794 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-28 12:05:32.133  7574  7790 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
07-28 12:05:32.134  7574  7790 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
07-28 12:05:32.149  1851  4005 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 12:05:32.152  1851  1851 D BluetoothHeadset: Proxy object connected
07-28 12:05:32.153  1851  4000 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 12:05:32.154  7574  7829 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-28 12:05:32.154  7574  7829 W bt-smp  : Plain text(LSB ~ MSB) = 42 69 7b 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-28 12:05:32.154  7574  7829 W bt-smp  : Encrypted text(LSB ~ MSB) = bc d5 1a 63 91 4a d8 7a 21 4e 77 97 6f ca 01 ae 
07-28 12:05:32.154  7574  7829 W bt-btm  : Stopping oneshot timer
07-28 12:05:32.154  7874  7874 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,07-28 12:05:32.157  6720  6720 D BluetoothPan: BluetoothPAN Proxy object connected
07-28 12:05:32.157  6720  6720 D PanProfile: Bluetooth service connected
07-28 12:05:32.158  1851  1851 D BluetoothHeadset: Proxy object connected
07-28 12:05:32.159  6720  6735 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-28 12:05:32.162  6720  7444 D BluetoothMap: onBluetoothStateChange: up=true
07-28 12:05:32.164  6720  6720 D BluetoothInputDevice: Proxy object connected
07-28 12:05:32.164  6720  6720 D HidProfile: Bluetooth service connected
07-28 12:05:32.165  1032  1097 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-28 12:05:32.169  6720  6736 D BluetoothA2dp: onBluetoothStateChange: up=true
07-28 12:05:32.169  1032  1032 D BluetoothA2dp: Proxy object connected
07-28 12:05:32.171  6720  6720 D BluetoothMap: Proxy object connected
07-28 12:05:32.172  6720  6720 D MapProfile: Bluetooth service connected
07-28 12:05:32.172  6720  6720 D BluetoothMap: getConnectedDevices()
07-28 12:05:32.173  1851  1866 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 12:05:32.173  7574  7875 V BluetoothMapService: getConnectedDevices()
07-28 12:05:32.174  6720  6720 D BluetoothA2dp: Proxy object connected
07-28 12:05:32.174  6720  6720 D A2dpProfile: Bluetooth service connected
07-28 12:05:32.175  1851  1851 D BluetoothHeadset: Proxy object connected
07-28 12:05:32.176  6720  6735 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 12:05:32.177  6720  6720 D BluetoothHeadset: Proxy object connected
07-28 12:05:32.177  6720  6720 D HeadsetProfile: Bluetooth service connected
,07-28 12:05:32.179  1032  1032 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
07-28 12:05:32.179  1032  1097 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
07-28 12:05:32.180  1032  1097 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
07-28 12:05:32.180  7574  7829 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-28 12:05:32.180  7574  7829 W bt-smp  : Plain text(LSB ~ MSB) = 6e ef 4a 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-28 12:05:32.180  7574  7829 W bt-smp  : Encrypted text(LSB ~ MSB) = d3 a8 f9 fd 84 b7 19 d8 e4 41 39 ca e4 e3 dc f8 
07-28 12:05:32.180  7574  7829 W bt-btm  : Stopping oneshot timer
07-28 12:05:32.180  1032  1097 D BluetoothManagerService: Message: 40
07-28 12:05:32.180  1032  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
07-28 12:05:32.181  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:32.182  1940  2165 D LGBluetoothAPIService: Message: 1
07-28 12:05:32.182  1940  2165 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
07-28 12:05:32.182  1940  2165 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
07-28 12:05:32.183  1940  2165 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
07-28 12:05:32.183  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-28 12:05:32.187  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:32.191  7574  7574 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:32.191  7574  7574 D BluetoothMapService: STATE_ON
07-28 12:05:32.192  7574  7829 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-28 12:05:32.192  7574  7829 W bt-smp  : Plain text(LSB ~ MSB) = c9 7c 58 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-28 12:05:32.192  7574  7829 W bt-smp  : Encrypted text(LSB ~ MSB) = 95 92 19 e4 0c 04 30 4d 3f 11 59 ee 23 4b 38 40 
07-28 12:05:32.192  7574  7829 W bt-btm  : Stopping oneshot timer
07-28 12:05:32.192  6720  6720 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
07-28 12:05:32.194  6720  6720 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,07-28 12:05:32.201  7574  7829 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-28 12:05:32.201  7574  7829 W bt-smp  : Plain text(LSB ~ MSB) = cc a8 67 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-28 12:05:32.201  7574  7829 W bt-smp  : Encrypted text(LSB ~ MSB) = 05 6c b5 47 dc b5 5f 45 a5 b2 2b c8 86 9c 76 bf 
07-28 12:05:32.201  7574  7829 W bt-btm  : Stopping oneshot timer
07-28 12:05:32.205  6720  6720 D DockEventReceiver: finishStartingService: stopping service
07-28 12:05:32.207  7574  7574 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16be37c3
07-28 12:05:32.207  7574  7574 V BluetoothPbapService: Pbap Service onCreate
07-28 12:05:32.207  7574  7574 V BluetoothPbapService: Starting PBAP service
,07-28 12:05:32.209  7574  7574 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
07-28 12:05:32.209  7574  7574 V BluetoothPbapService: Pbap Service onBind
07-28 12:05:32.210  6720  6720 D BluetoothPbap: Proxy object connected
07-28 12:05:32.210  7574  7574 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:32.210  6720  6720 D PbapServerProfile: Bluetooth service connected
07-28 12:05:32.210  7574  7574 V BluetoothPbapService: state: 12
07-28 12:05:32.211  7574  7574 V BluetoothMapService: Handler(): got msg=1
,07-28 12:05:32.211  7574  7574 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
07-28 12:05:32.212  7574  7574 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-28 12:05:32.212  7574  7574 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:05:32.212  7574  7574 V BluetoothPbapReceiver: ***********state = 12
07-28 12:05:32.212  7574  7883 D BluetoothMapMasInstance: MAS initSocket()
07-28 12:05:32.213  7574  7883 D BluetoothMapMasInstance:   masId = 00
07-28 12:05:32.213  7574  7883 D BluetoothMapMasInstance:   msgTypes = 0e
07-28 12:05:32.213  7574  7883 D BluetoothMapMasInstance:   masName = SMS/MMS
07-28 12:05:32.213  7574  7883 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
07-28 12:05:32.213  7574  7574 V BluetoothPbapService: Handler(): got msg=1
07-28 12:05:32.214  7574  7574 V BluetoothPbapService: Pbap Service startRfcommSocketListener
07-28 12:05:32.215  2126  2126 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-28 12:05:32.215  7574  7829 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-28 12:05:32.215  7574  7829 W bt-smp  : Plain text(LSB ~ MSB) = e7 20 72 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-28 12:05:32.215  7574  7829 W bt-smp  : Encrypted text(LSB ~ MSB) = dd 71 b9 b4 2b 1e d9 f4 63 01 0b cc 45 be 57 3e 
07-28 12:05:32.215  7574  7829 W bt-btm  : Stopping oneshot timer
07-28 12:05:32.216  2126  2126 D c       : Getting all permits...
07-28 12:05:32.216  2126  2126 D a       : Opening database...
07-28 12:05:32.217  7574  7884 V BluetoothPbapService: Pbap Service initSocket
07-28 12:05:32.218  1032  1886 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:05:32.218  1032  1885 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:05:32.219  7574  7884 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 12:05:32.219  7574  7883 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 12:05:32.220  2126  2126 D a       : Opening database auth.proximity.permit_store...
07-28 12:05:32.221  7574  7794 D BluetoothAdapterProperties: Scan Mode:21
07-28 12:05:32.221  7574  7883 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
07-28 12:05:32.221  7574  7794 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
07-28 12:05:32.221  7574  7883 V BluetoothMapMasInstance: Succeed to create listening socket 
07-28 12:05:32.221  7574  7883 D BluetoothMapMasInstance: Accepting socket connection...
07-28 12:05:32.222  7574  7884 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
07-28 12:05:32.222  7574  7884 V BluetoothPbapService: Succeed to create listening socket 
07-28 12:05:32.222  7574  7884 V BluetoothPbapService: Accepting socket connection...
,07-28 12:05:32.226  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:05:32.229  2126  2126 D a       : Closing database...
07-28 12:05:32.242  6720  6720 D BluetoothPermissionRequest: onReceive
,07-28 12:05:32.244  6720  6720 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,07-28 12:05:32.245  6720  6720 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-28 12:05:32.249  7574  7574 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
07-28 12:05:32.250  7574  7574 I LGBluetoothOppAdapter: [BTUI] startOppService()
07-28 12:05:32.257  7574  7574 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,07-28 12:05:32.284  7574  7574 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,07-28 12:05:32.284  7574  7574 V BtOppService: onCreate
,07-28 12:05:32.289  7574  7574 V BluetoothOppNotification: send message
07-28 12:05:32.294  7574  7574 V BtOppService: Starting RfcommListener
07-28 12:05:32.302  7574  7574 D BluetoothOppPreference: Dumping Names:  
07-28 12:05:32.302  7574  7574 D BluetoothOppPreference: {}
07-28 12:05:32.302  7574  7574 D BluetoothOppPreference: Dumping Channels:  
07-28 12:05:32.302  7574  7574 D BluetoothOppPreference: {}
07-28 12:05:32.304  7574  7574 V BtOppService: onStartCommand
,07-28 12:05:32.307  7574  7893 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
07-28 12:05:32.311  7574  7574 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:32.312  7574  7574 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
07-28 12:05:32.312  7574  7890 V BtOppService: Deleted complete outbound shares, number =  0
07-28 12:05:32.313  7574  7893 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-28 12:05:32.314  7574  7890 V BtOppService: Deleted complete inbound failed shares, number = 0
07-28 12:05:32.314  7574  7890 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
07-28 12:05:32.316  7574  7893 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1abbadef on behalf of 
,07-28 12:05:32.316  7574  7574 V BluetoothOppNotification: new notify threadi!
07-28 12:05:32.317  7574  7890 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@6c210fc on behalf of 
,07-28 12:05:32.318  7574  7574 V BluetoothOppNotification: send delay message
07-28 12:05:32.319  7574  7574 V BtOppService: start RfcommListener
07-28 12:05:32.320  7574  7894 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
07-28 12:05:32.327  7574  7574 V BtOppService: RfcommListener started
07-28 12:05:32.328  7574  7574 V BtOppService: ContentObserver received notification
07-28 12:05:32.328  7574  7574 V BtOppService: ContentObserver received notification
07-28 12:05:32.329  7574  7895 V BtOppRfcommListener: Starting RFCOMM listener....
,07-28 12:05:32.330  1032  1642 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:05:32.332  7574  7895 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 12:05:32.334  7574  7895 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=75
07-28 12:05:32.335  7574  7895 V BtOppRfcommListener: Started RFCOMM listener....
07-28 12:05:32.335  7574  7895 I BtOppRfcommListener: Accept thread started.
07-28 12:05:32.335  7574  7895 V BtOppRfcommListener: Accepting connection...
07-28 12:05:32.339  7574  7894 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@20b63385 on behalf of 
07-28 12:05:32.339  7574  7893 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
07-28 12:05:32.340  7574  7893 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-28 12:05:32.340  7574  7894 V BluetoothOppNotification: mUpdateCompleteNotification = true
07-28 12:05:32.342  7574  7894 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,07-28 12:05:32.344  7574  7893 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@f24a5da on behalf of 
07-28 12:05:32.345  7574  7893 V BluetoothOppNotification: update too frequent, put in queue
07-28 12:05:32.345  7574  7574 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16be37c3
07-28 12:05:32.345  7574  7574 V BluetoothFtpService: Ftp Service onCreate
07-28 12:05:32.345  7574  7574 I BluetoothFtpService: Ftp Service onCreate
07-28 12:05:32.346  7574  7574 V BluetoothFtpService: Ftp Service onStartCommand
07-28 12:05:32.346  7574  7574 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:32.346  7574  7574 V BluetoothFtpService: Starting Listening on sockets
,07-28 12:05:32.346  7574  7574 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-28 12:05:32.346  7574  7574 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-28 12:05:32.346  7574  7574 V BluetoothSapReceiver: SapReceiver onReceive 
07-28 12:05:32.346  7574  7574 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:32.346  7574  7574 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
07-28 12:05:32.347  7574  7574 V BluetoothSapReceiver: Calling SAP service start service with action = null
07-28 12:05:32.461  1032  2026 I art     : Explicit concurrent mark sweep GC freed 26052(1275KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.963ms total 117.130ms
07-28 12:05:32.462  7574  7893 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
07-28 12:05:32.462  7574  7894 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3d9d40e8 on behalf of 
07-28 12:05:32.463  7574  7894 V BluetoothOppNotification: outbound: succ-0  fail-0
,07-28 12:05:32.465  7574  7574 V BluetoothFtpService: Handler(): got msg=1
07-28 12:05:32.466  7574  7574 V BluetoothFtpService: Ftp Service startRfcommSocketListener
07-28 12:05:32.467  7574  7574 V BluetoothFtpService: Ftp Service initSocket
07-28 12:05:32.468  7574  7894 V BluetoothOppNotification: outbound notification was removed.
07-28 12:05:32.468  7574  7894 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
07-28 12:05:32.469  7574  7894 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@12b8301 on behalf of 
07-28 12:05:32.469  7574  7894 V BluetoothOppNotification: inbound: succ-0  fail-0
07-28 12:05:32.470  7574  7894 V BluetoothOppNotification: inbound notification was removed.
07-28 12:05:32.470  7574  7894 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
07-28 12:05:32.472  7574  7894 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@153745a6 on behalf of 
07-28 12:05:32.477  1032  1047 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:05:32.480  7574  7574 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-28 12:05:32.485  7574  7574 V BluetoothFtpService: Succeed to create listening socket on channel 20
07-28 12:05:32.489  7574  7899 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
07-28 12:05:32.495  7574  7574 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16be37c3
07-28 12:05:32.495  7574  7574 V BluetoothSapService: Sap Service onCreate
07-28 12:05:32.497  7574  7574 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:32.497  7574  7574 V BluetoothSapService: state: 12
07-28 12:05:32.497  7574  7574 V BluetoothSapService: Starting SAP server process
07-28 12:05:32.498  7574  7574 V BluetoothSapService: SAP Service startRfcommListenerThread
07-28 12:05:32.495  7900  7900 W sapd    : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:05:32.495  7900  7900 W sapd    : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:05:32.499  7574  7901 V BluetoothSapService: Sap Service initRfcommSocket
,07-28 12:05:32.501  1032  1048 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-28 12:05:32.502  7574  7901 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-28 12:05:32.503  7574  7901 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
07-28 12:05:32.503  7574  7901 V BluetoothSapService: Succeed to create listening socket 
,07-28 12:05:32.503  7574  7901 V BluetoothSapService: Accepting socket connection...
07-28 12:05:32.506  7900  7900 V BT_SAP  : Event pipe created
,07-28 12:05:32.506  7900  7900 V BT_SAP  : create_server_socket qcom.sap.server
,07-28 12:05:32.506  7900  7900 V BT_SAP  : created socket fd 6
,07-28 12:05:32.866  6524  6666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:05:32.866  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,07-28 12:05:32.866  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:32.866  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:05:32.866  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
,07-28 12:05:32.866  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:05:32.866  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:05:32.866  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:05:32.888  6524  6666 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:05:32.892  6524  6666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:05:32.892  6524  6666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b5ddce added. We now have 8 listener(s)
07-28 12:05:32.892  6524  6666 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:05:32.897  1032  1048 D WifiServiceImplEx: setWifiEnabled: false pid=6524, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-28 12:05:32.897  1032  1048 D WifiService: setWifiEnabled: false pid=6524, uid=10118
07-28 12:05:32.897  1032  1048 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-28 12:05:32.902  6524  6666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:32.905  1032  1781 D WifiServiceImplEx: setWifiEnabled: true pid=6524, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-28 12:05:32.905  1032  1781 D WifiService: setWifiEnabled: true pid=6524, uid=10118
07-28 12:05:32.905  1032  1781 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-28 12:05:32.919  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-28 12:05:32.919  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-28 12:05:32.919  1032  1032 D Ulp_jni : JNI:system_update. Event-4
,07-28 12:05:32.922  1032  1538 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
,07-28 12:05:32.922  1032  1538 I LGFTMITEM: [GET_FTM][id=6], offset=12288
07-28 12:05:32.924  1032  1538 E WifiUtil: wfc_util_ffile_check_copy(): pid[1032] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
07-28 12:05:32.925  1032  1538 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
,07-28 12:05:32.925  1032  1538 E WifiUtil: wfc_util_ffile_check_copy(): pid[1032] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
07-28 12:05:32.925  1032  1538 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
07-28 12:05:32.925  1032  1538 I WifiUtil: Intf0MacAddress=C49A027FFB5D
07-28 12:05:32.925  1032  1538 E WifiHW  : unknown target_country: EU , set to default
07-28 12:05:32.925  1032  1538 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
07-28 12:05:32.925  1032  1538 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
07-28 12:05:32.925  1032  1538 I WifiUtil: gEnableBmps=1
07-28 12:05:33.323  7574  7574 V BluetoothOppNotification: new notify threadi!
07-28 12:05:33.323  7574  7574 V BluetoothOppNotification: send delay message
,07-28 12:05:33.334  7574  7917 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
07-28 12:05:33.358  1032  1092 W ProcessCpuTracker: Skipping unknown process pid 7911
,07-28 12:05:33.362  7574  7917 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@20821632 on behalf of 
07-28 12:05:33.363  7574  7917 V BluetoothOppNotification: mUpdateCompleteNotification = true
07-28 12:05:33.364  7574  7917 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
07-28 12:05:33.365  7574  7917 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@16d2df83 on behalf of 
07-28 12:05:33.366  7574  7917 V BluetoothOppNotification: outbound: succ-0  fail-0
07-28 12:05:33.367  7574  7917 V BluetoothOppNotification: outbound notification was removed.
07-28 12:05:33.367  7574  7917 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
07-28 12:05:33.368  7574  7917 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1a354500 on behalf of 
07-28 12:05:33.369  7574  7917 V BluetoothOppNotification: inbound: succ-0  fail-0
,07-28 12:05:33.372  7574  7917 V BluetoothOppNotification: inbound notification was removed.
,07-28 12:05:33.372  7574  7917 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,07-28 12:05:33.374  7574  7917 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1b49139 on behalf of 
07-28 12:05:33.505   324   891 D SoftapController: Softap fwReload - Ok
,07-28 12:05:33.516  1032  1538 E NetdConnector: NDC Command {83 softap fwreload wlan0 STA} took too long (587ms)
07-28 12:05:33.547  1032  1097 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,07-28 12:05:33.568   324   891 D CommandListener: Setting iface cfg
07-28 12:05:33.568   324   891 D CommandListener: Trying to bring down wlan0
,07-28 12:05:33.598   324   891 D CommandListener: Clearing all IP addresses on wlan0
,07-28 12:05:33.601  1032  1097 D Tethering: InitialState.processMessage what=4
07-28 12:05:33.602  1032  1097 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,07-28 12:05:33.641  1032  1538 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,07-28 12:05:33.645  7919  7919 W wpa_supplicant: type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:05:33.645  7919  7919 W wpa_supplicant: type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,07-28 12:05:33.667  6720  6720 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-28 12:05:33.667  6720  6720 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-28 12:05:33.667  6720  6720 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-28 12:05:33.667  6720  6720 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-28 12:05:33.672  6720  6720 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,07-28 12:05:33.674  6720  6720 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-28 12:05:33.675  6720  6720 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
07-28 12:05:33.675  6720  6720 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-28 12:05:33.675  6720  6720 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-28 12:05:33.675  6720  6720 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-28 12:05:33.675  6720  6720 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
07-28 12:05:33.676  6720  6720 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-28 12:05:33.680  6720  6720 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-28 12:05:33.680  6720  6720 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-28 12:05:33.680  6720  6720 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-28 12:05:33.680  6720  6720 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-28 12:05:33.681  6720  6720 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-28 12:05:33.683  6720  6720 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-28 12:05:33.683  6720  6720 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
07-28 12:05:33.683  6720  6720 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-28 12:05:33.683  6720  6720 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-28 12:05:33.683  6720  6720 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-28 12:05:33.683  6720  6720 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-28 12:05:33.687  7919  7919 I wpa_supplicant: Successfully initialized wpa_supplicant
07-28 12:05:33.687  1032  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-28 12:05:33.687  1032  1538 E WifiStateMachine: useWiFiOffloading() : false
07-28 12:05:33.687  1032  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-28 12:05:33.690  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
07-28 12:05:33.692  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:05:33.695  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:05:33.698  1032  1538 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
07-28 12:05:33.698  1032  1538 D WifiMonitor: connecting to supplicant
07-28 12:05:33.714  7919  7919 I wpa_supplicant: rfkill: Cannot open RFKILL control device
07-28 12:05:33.714  7919  7919 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
07-28 12:05:33.733  1032  1092 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7937 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
07-28 12:05:33.733  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,07-28 12:05:33.784  7919  7919 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-28 12:05:33.831  7919  7919 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,07-28 12:05:33.835  1032  1885 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7959 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
07-28 12:05:33.838  1032  1538 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
07-28 12:05:33.839  1032  1538 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
07-28 12:05:33.839  1032  1538 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
07-28 12:05:33.840  1032  1538 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
07-28 12:05:33.841  1032  1538 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:05:33.841  1032  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,07-28 12:05:33.841  7937  7957 W FormManager: Network not available. Please check & try again.
07-28 12:05:33.842  1032  1538 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:05:33.842  1032  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:05:33.843  7937  7958 V FormManager: Network unavailable.
07-28 12:05:33.843  1032  1538 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
07-28 12:05:33.843  1032  1538 D WifiNative-wlan0: doString: [DRIVER MACADDR]
07-28 12:05:33.845  1032  1538 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
07-28 12:05:33.845  1032  1538 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
07-28 12:05:33.845  1032  1538 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
07-28 12:05:33.846  7937  7958 V FormManager: Network unavailable.
07-28 12:05:33.847  1032  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-28 12:05:33.847  1032  1538 E WifiStateMachine: useWiFiOffloading() : false
07-28 12:05:33.847  1032  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-28 12:05:33.847  1032  1538 D WifiNative-wlan0: doBoolean: SET update_config 1
07-28 12:05:33.848  1032  1538 D WifiNative-wlan0: SET update_config 1: returned true
07-28 12:05:33.848  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:33.848  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:33.848  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:33.848  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:33.848  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-28 12:05:33.849  1032  1538 D WifiConfigStore: Loading config and enabling all networks 
07-28 12:05:33.849  1032  1538 D WifiNative-wlan0: doString: [LIST_NETWORKS]
07-28 12:05:33.850  7919  7919 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
07-28 12:05:33.850  1032  7965 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
07-28 12:05:33.850  1032  7965 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
07-28 12:05:33.850  1032  7965 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
07-28 12:05:33.850  1032  7965 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
07-28 12:05:33.850  1032  7965 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
07-28 12:05:33.850  1032  7965 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
07-28 12:05:33.851  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:05:33.851  1032  1538 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
07-28 12:05:33.852  1940  1940 D WfdService: Waiting for WifiP2p enabling
07-28 12:05:33.852  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:05:33.852  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:05:33.852  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:33.852  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:05:33.852  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:05:33.852  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:05:33.852  6524  6524 V io.jxcore.node,.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:05:33.852  6524  6524 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:05:33.853  6524  6524 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:05:33.854  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
07-28 12:05:33.854  1032  1542 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
07-28 12:05:33.858  1032  1538 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,07-28 12:05:33.871  1032  2037 I ActivityManager: Killing 7018:com.android.chrome/u0a57 (adj 15): empty #17
07-28 12:05:33.874  1032  1538 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
07-28 12:05:33.874  1032  1538 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,07-28 12:05:33.909  1032  1538 D WifiStateMachine: enableVerboseLogging : level 2
07-28 12:05:33.909  1032  1047 W libprocessgroup: failed to open /acct/uid_10057/pid_7018/cgroup.procs: No such file or directory
07-28 12:05:33.909  1032  1538 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
07-28 12:05:33.910  1032  1538 D WifiNative-wlan0: SET device_name g3_global_com: returned true
07-28 12:05:33.910  1032  1538 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
07-28 12:05:33.910  1032  1538 D WifiNative-wlan0: SET manufacturer LGE: returned true
,07-28 12:05:33.910  1032  1538 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
07-28 12:05:33.911  1032  1538 D WifiNative-wlan0: SET model_name LG-D855: returned true
07-28 12:05:33.911  1032  1538 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
07-28 12:05:33.911  1032  1538 D WifiNative-wlan0: SET model_number LG-D855: returned true
07-28 12:05:33.911  1032  1538 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
07-28 12:05:33.912  1032  1538 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
07-28 12:05:33.912  1032  1538 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
07-28 12:05:33.912  1032  1538 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
07-28 12:05:33.912  1032  1538 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
07-28 12:05:33.913  1032  1538 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
07-28 12:05:33.913  1032  1538 D WifiStateMachine: Setting OUI to DA-A1-19
07-28 12:05:33.913  1032  1538 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
07-28 12:05:33.914  1032  1538 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
07-28 12:05:33.914  1032  1538 D WifiNative-HAL: Setting external_sim to 1
07-28 12:05:33.914  1032  1538 D WifiNative-wlan0: doBoolean: SET external_sim 1
07-28 12:05:33.914  1032  1538 D WifiNative-wlan0: SET external_sim 1: returned true
07-28 12:05:33.914  1032  1538 I WifiNative-HAL: startHal
07-28 12:05:33.914  1032  1538 D wifi    : setting scan oui 0x953cf3c0
07-28 12:05:33.914  1940  1940 D WfdsService: Supplicant Connection state is changed : true
07-28 12:05:33.914  7603  7603 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:33.914  1940  2302 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
07-28 12:05:33.914  1940  2302 D WfdsService: Set the WFDS Monitor: true
07-28 12:05:33.914  1940  2302 D WfdsMonitor: WfdsMonitorThread create
07-28 12:05:33.915  1940  2302 D WfdsMonitor: WFDS Monitor is created and started
07-28 12:05:33.915  1940  2302 D WfdsService: WiFi: Supplicant connection re-established
07-28 12:05:33.915  1032  1538 D WifiStateMachine: Setting OUI to DA-A1-19
07-28 12:05:33.915  1032  1538 I WifiNative-HAL: startHal
07-28 12:05:33.915  1032  1538 D wifi    : setting scan oui 0x953cf3c0
07-28 12:05:33.915  1032  1538 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
07-28 12:05:33.915  1940  7978 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
07-28 12:05:33.916  1940  7978 E CtrlSupplicant: Succeed to open control connection
07-28 12:05:33.916  1940  7978 E CtrlSupplicant: Succeed to open monitor connection
07-28 12:05:33.916  1940  7978 D WfdsMonitor: Supplicant connection established
07-28 12:05:33.916  1940  2302 D WfdsService: Connected to the supplicant for wfds
07-28 12:05:33.916  1032  1538 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
07-28 12:05:33.916  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
07-28 12:05:33.916  7919  7919 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
07-28 12:05:33.916  1032  1538 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
07-28 12:05:33.917  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
07-28 12:05:33.917  7919  7919 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
07-28 12:05:33.917  1032  1538 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
07-28 12:05:33.917  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
07-28 12:05:33.917  7919  7919 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
07-28 12:05:33.917  1032  1538 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
07-28 12:05:33.917  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
07-28 12:05:33.917  7919  7919 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
07-28 12:05:3,3.917  1032  1538 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
07-28 12:05:33.917  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
07-28 12:05:33.917  7919  7919 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
07-28 12:05:33.918  1032  1538 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
07-28 12:05:33.918  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
07-28 12:05:33.918  7919  7919 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
07-28 12:05:33.918  1032  1538 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
07-28 12:05:33.918  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
07-28 12:05:33.918  7919  7919 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
07-28 12:05:33.918  1032  1538 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
07-28 12:05:33.919  1032  1538 E WifiNative: : [153,956,931 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
07-28 12:05:33.919  1032  1538 D WifiNative-wlan0: doBoolean: RECONNECT
07-28 12:05:33.919  1032  1538 D WifiNative-wlan0: RECONNECT: returned true
07-28 12:05:33.919  1032  1538 D WifiNative-wlan0: doString: [STATUS]
07-28 12:05:33.919  1032  7965 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
07-28 12:05:33.919  1032  7965 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
07-28 12:05:33.919  1032  1538 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
07-28 12:05:33.920  1032  1538 D WifiNative-wlan0: doBoolean: SET ps 1
07-28 12:05:33.920  1032  1538 D WifiNative-wlan0: SET ps 1: returned true
07-28 12:05:33.920  1032  1537 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler },
07-28 12:05:33.921   324   891 D CommandListener: Setting iface cfg
07-28 12:05:33.921   324   891 D CommandListener: Trying to bring up p2p0
07-28 12:05:33.921  1032  1537 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-28 12:05:33.921  1032  1537 D LGWifiP2pService: P2pEnablingState
07-28 12:05:33.921  1032  1537 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:33.921  1032  1537 D LGWifiP2pService: P2p socket connection successful
07-28 12:05:33.921  1032  1537 D LGWifiP2pService: P2pEnabledState
07-28 12:05:33.921  1032  1537 D LGWifiP2pService: sending p2p connection changed broadcast,
07-28 12:05:33.922  1032  1537 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
07-28 12:05:33.924  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
07-28 12:05:33.924  1940  1940 D WfdsService: WifiP2pState is changed : true
,07-28 12:05:33.924  1940  2302 D WfdsService: Receive the WFDS_ENABLE Method
07-28 12:05:33.924  1940  2302 D WfdsService: Set the WFDS Monitor: true
07-28 12:05:33.924  1940  1940 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
07-28 12:05:33.924  1940  2302 D WfdsService: Connected to the supplicant for wfds
07-28 12:05:33.924  1940  2302 D WfdsJNI : doCommand: WFDS_SET TRUE
07-28 12:05:33.924  7919  7919 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
07-28 12:05:33.924  1940  2302 D WfdsService: selectPreferredScanChannel [36]
07-28 12:05:33.924  1940  2302 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
07-28 12:05:33.924  1940  1940 D WfdsService: isConnected: false
07-28 12:05:33.926  1032  1537 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
07-28 12:05:33.926  1032  1537 D WifiNative-p2p0: doBoolean: SET device_name G3
07-28 12:05:33.926  1032  1537 D WifiNative-p2p0: SET device_name G3: returned true
07-28 12:05:33.926  1032  1537 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
07-28 12:05:33.926  1032  1537 D LGWifiP2pService: before postfix = G3
07-28 12:05:33.926  1032  1537 D WifiServerServiceExt: postfix byte check : 2
07-28 12:05:33.926  1032  1537 D LGWifiP2pService: after postfix = G3
07-28 12:05:33.926  1032  1537 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
07-28 12:05:33.926  1032  1537 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
07-28 12:05:33.926  1032  1537 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
07-28 12:05:33.926  1032  1537 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
07-28 12:05:33.926  1032  1537 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
07-28 12:05:33.927  1032  1537 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
07-28 12:05:33.927  1032  1537 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
07-28 12:05:33.927  1032  1537 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
07-28 12:05:33.927  1032  1537 D WifiNative-HAL: p2pGetDeviceAddress
07-28 12:05:33.927  1032  1537 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
07-28 12:05:33.928  1940  1940 I WfdStateTracker: handleP2pThisDeviceChanged
07-28 12:05:33.928  1032  1537 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
07-28 12:05:33.928  1032  1537 D WifiNative-p2p0: doBoolean: P2P_FLUSH
07-28 12:05:33.929  1940  1940 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
07-28 12:05:33.929  1940  1940 D WfdsService: Update P2p Interface State: 3
07-28 12:05:33.929  1032  1537 D WifiNative-p2p0: P2P_FLUSH: returned true
07-28 12:05:33.929  1032  1537 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
07-28 12:05:33.930  1032  1032 D WifiScanningService: SCAN_AVAILABLE : 3
07-28 12:05:33.930  1032  1556 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:33.930  1032  1556 I WifiNative-HAL: startHal
07-28 12:05:33.930  1032  1032 D RttService: SCAN_AVAILABLE : 3
07-28 12:05:33.930  1032  1538 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
,07-28 12:05:33.931  1032  1557 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:33.931  1032  1538 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
07-28 12:05:33.931  1032  1538 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
07-28 12:05:33.932  1032  1538 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
07-28 12:05:33.932  1032  1537 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
07-28 12:05:33.932  1032  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=153970  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-28 12:05:33.933  6524  6666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:05:33.933  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:05:33.933  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:33.933  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:05:33.933  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:05:33.933  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:05:33.933  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:05:33.933  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:05:33.933  1032  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=153971  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-28 12:05:33.933  1032  1538 E WifiStateMachine:  DisconnectedState what:132106 1 0
07-28 12:05:33.934  1032  1538 E WifiStateMachine:  ConnectModeState what:132106 1 0
07-28 12:05:33.934  6524  6666 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:05:33.934  1032  1538 E WifiStateMachine:  DriverStartedState what:132106 1 0
07-28 12:05:33.934  1032  1538 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
07-28 12:05:33.934  7919  7919 E wpa_supplicant: nWIFIDualbandAPConnection: 1
07-28 12:05:33.935  1032  1556 D wifi    : getting scan capabilities on interface[1] = 0x953cf3c0
07-28 12:05:33.935  1032  1556 D wifi    : failed to get capabilities : -3
07-28 12:05:33.935  1032  1556 E WifiScanningService: could not get scan capabilities
07-28 12:05:33.935  1032  1537 D WifiNative-p2p0: doString: [LIST_NETWORKS]
07-28 12:05:33.935  1032  1537 D WifiNative-p2p0:    returned OK
07-28 12:05:33.935  1032  1537 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
07-28 12:05:33.936  1032  1537 D WifiNative-p2p0: SAVE_CONFIG: returned false
07-28 12:05:33.936  1032  1537 D LGWifiP2pService: sending p2p persistent groups changed broadcast
07-28 12:05:33.936  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:33.936  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:33.936  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
07-28 12:05:33.936  1032  1537 D LGWifiP2pService: InactiveState
07-28 12:05:33.936  1032  1537 D LGWifiP2pService: InactiveState{ when=-1ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:33.936  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:33.936  1032  1537 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
,07-28 12:05:33.939  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:33.939  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:05:33.940  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:05:33.943  6524  6666 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
07-28 12:05:33.943  1032  1537 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
07-28 12:05:33.943  1032  1537 D LGWifiP2pService: InactiveState{ when=-6ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:33.943  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:33.943  1032  1537 D LGWifiP2pService: DefaultState{ when=-7ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:33.943  7919  7919 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
07-28 12:05:33.943  1032  1537 D LGWifiP2pService: InactiveState{ when=-7ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:33.943  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:33.943  1032  1537 D LGWifiP2pService: DefaultState{ when=-7ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:33.943  1032  1537 D LGWifiP2pService: InactiveState{ when=-7ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:33.943  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:33.944  1032  1537 D LGWifiP2pService: DefaultState{ when=-7ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:33.944  7919  7919 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:05:33.944  6524  6666 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
07-28 12:05:33.944  7919  7919 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
07-28 12:05:33.944  7919  7919 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:05:33.944  7919  7919 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:05:33.945  1940  7978 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-28 12:05:33.945  1032  1538 E WifiStateMachine:  DisconnectedState what:132096 -100 0
07-28 12:05:33.945  1940  7978 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:05:33.945  1940  7978 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:05:33.945  1032  7965 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-28 12:05:33.945  1032  7965 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:05:33.945  1032  7965 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:05:33.945  1032  7965 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:05:33.945  6524  6666 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1b263196 Bundle[{}]
07-28 12:05:33.945  1032  7965 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:05:33.945  1032  7965 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:05:33.945  1032  7965 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:0,5:33.945  1032  7965 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:05:33.945  1032  1538 E WifiStateMachine:  ConnectModeState what:132096 -100 0
07-28 12:05:33.945  1032  7965 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:05:33.945  1032  7965 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:05:33.945  1032  7965 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:05:33.945  1032  7965 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:05:33.945  1940  2302 W WfdsService: DefaultState - msg [9441285] is not handled
07-28 12:05:33.946  1032  1537 D LGWifiP2pService: InactiveState{ when=-9ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:33.946  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:33.946  1032  1537 D LGWifiP2pService: DefaultState{ when=-9ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:33.946  1032  1538 E WifiStateMachine:  DriverStartedState what:132096 -100 0
07-28 12:05:33.946  1032  1538 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
07-28 12:05:33.946  1032  1032 E WifiServerServiceExt: No p2p device connected
07-28 12:05:33.946  7919  7919 E wpa_supplicant: disconnect_rssi_lvl: -100
07-28 12:05:33.946  6524  6666 I io.jxcore.node.LifeCycleMonitor: start: OK
07-28 12:05:33.946  6524  6666 I io.jxcore.node.LifeCycleMonitor: stop: OK
07-28 12:05:33.946  1032  1538 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
07-28 12:05:33.947  1032  1538 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
07-28 12:05:33.947  6524  6666 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
07-28 12:05:33.947  1032  1538 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
07-28 12:05:33.947  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
07-28 12:05:33.947  6524  6666 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-28 12:05:33.947  7919  7919 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
07-28 12:05:33.948  7919  7919 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:05:33.948  6524  6666 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
07-28 12:05:33.948  1032  7965 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-28 12:05:33.948  1032  7965 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,07-28 12:05:33.948  1032  7965 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:05:33.948  7919  7919 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
07-28 12:05:33.948  1032  7965 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:05:33.948  7919  7919 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:05:33.949  1032  7965 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:05:33.949  1032  7965 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:05:33.949  1032  7965 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:05:33.949  1032  7965 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,07-28 12:05:33.949  7919  7919 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:05:33.949  1032  7965 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:05:33.949  1032  7965 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:05:33.949  1032  7965 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:05:33.949  1032  7965 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:05:33.949  1940  7978 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:05:33.949  1940  7978 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:05:33.949  1032  1538 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
07-28 12:05:33.950  1032  1537 D LGWifiP2pService: InactiveState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
,07-28 12:05:33.950  6524  6666 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
07-28 12:05:33.950  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:33.950  1032  1538 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
07-28 12:05:33.950  1032  1538 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
07-28 12:05:33.950  1032  1538 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
07-28 12:05:33.950  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
07-28 12:05:33.950  7919  7919 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
07-28 12:05:33.950  7919  7919 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-28 12:05:33.950  1032  7965 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
,07-28 12:05:33.950  1032  7965 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-28 12:05:33.951  1032  7965 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-28 12:05:33.951  1032  7965 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-28 12:05:33.951  1032  1538 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
07-28 12:05:33.951  1032  1538 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
07-28 12:05:33.951  1032  1538 D WifiNative-wlan0: BSS_FLUSH 0: returned true
,07-28 12:05:33.951  1032  1538 D WifiNative-wlan0: doBoolean: SCAN
07-28 12:05:33.951  1032  1538 D WifiNative-wlan0: SCAN: returned false
07-28 12:05:33.952  1032  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=153990  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,07-28 12:05:33.954  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:33.954  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:33.954  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
07-28 12:05:33.955  1032  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=153993  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-28 12:05:33.955  1032  1538 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-28 12:05:33.955  1032  1538 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-28 12:05:33.955  1032  1538 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-28 12:05:33.956  1032  1538 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-28 12:05:33.956  6524  6666 I System.out: Running OutgoingSocketThread
07-28 12:05:33.956  1032  1538 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-28 12:05:33.957  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 12:05:33.957  1032  1032 D WifiServerServiceExt: setSupplicantStateSCANNING
07-28 12:05:33.957  6524  7979 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 835)
07-28 12:05:33.958  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 12:05:33.958  1032  1032 D WifiServerServiceExt: setSupplicantStateSCANNING
07-28 12:05:33.959  6524  7979 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 52138
07-28 12:05:33.959  6524  7979 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
07-28 12:05:33.960  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:33.960  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:05:33.961  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:05:33.966  7959  7959 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-28 12:05:33.968  6720  6720 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-28 12:05:33.971  6720  6720 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:05:33.972  1032  2051 I ActivityManager: Killing 7036:com.lge.drmservice/u0a62 (adj 15): empty #17
07-28 12:05:34.010  1032  1048 W libprocessgroup: failed to open /acct/uid_10062/pid_7036/cgroup.procs: No such file or directory
,07-28 12:05:34.025  7959  7959 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-28 12:05:34.033  6720  6720 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-28 12:05:34.037  6720  6720 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:05:34.037  7937  7983 W FormManager: Network not available. Please check & try again.
,07-28 12:05:34.046  7937  7984 V FormManager: Network unavailable.
,07-28 12:05:34.048  7937  7984 V FormManager: Network unavailable.
,07-28 12:05:34.052  4323  4323 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,07-28 12:05:34.052  4323  4323 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-28 12:05:34.054  4323  4323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 12:05:34.057  4323  4323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 12:05:34.062  4323  7985 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-28 12:05:34.064  4323  7986 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,07-28 12:05:34.064  4323  7986 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,07-28 12:05:34.114  1032  1993 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7987 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,07-28 12:05:34.229  7987  7987 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
07-28 12:05:34.229  7987  7987 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,07-28 12:05:34.238  7987  7987 V [BNRBootReceiver]: Boot Receiver Return
07-28 12:05:34.239  7987  7987 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-28 12:05:34.286  1032  1993 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8005 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
07-28 12:05:34.287  1032  1993 I ActivityManager: Killing 7053:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,07-28 12:05:34.302   350   350 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 291us total 15.384ms
,07-28 12:05:34.316   350   350 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 283us total 13.079ms
,07-28 12:05:34.329   350   350 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 264us total 12.329ms
,07-28 12:05:34.344  1032  2037 W libprocessgroup: failed to open /acct/uid_10085/pid_7053/cgroup.procs: No such file or directory
,07-28 12:05:34.374  8005  8005 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,07-28 12:05:34.399  8005  8005 D PluginManager: init()
,07-28 12:05:34.485  1032  7965 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
,07-28 12:05:34.485  1032  7965 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
,07-28 12:05:34.485  1032  7965 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
07-28 12:05:34.485  1032  7965 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: WPS-AP-AVAILABLE 
07-28 12:05:34.485  1032  7965 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
07-28 12:05:34.486  7919  7919 E wpa_supplicant: USIM:  scard_init function
07-28 12:05:34.487  1032  1538 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
07-28 12:05:34.487  1032  1538 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
,07-28 12:05:34.487  1032  1538 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
07-28 12:05:34.487  7919  7919 I wpa_supplicant: Trying to associate with SSID 'NG700'
07-28 12:05:34.488  1032  1538 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
07-28 12:05:34.488  1032  1538 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
,07-28 12:05:34.488  1032  7965 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
07-28 12:05:34.488  1032  7965 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,07-28 12:05:34.519  1032  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=154557  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
07-28 12:05:34.520  1032  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=154558  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,07-28 12:05:34.524  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:34.524  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:05:34.526  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:05:34.528  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:34.528  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:34.528  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
07-28 12:05:34.529  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 12:05:34.529  1032  1032 D WifiServerServiceExt: setSupplicantStateASSOCIATING
07-28 12:05:34.606  1032  7965 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
07-28 12:05:34.606  1032  7965 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
07-28 12:05:34.606  7919  7919 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
07-28 12:05:34.606  1032  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=154645  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
07-28 12:05:34.607  1032  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=154645  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
07-28 12:05:34.608  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 12:05:34.608  1032  1032 D WifiServerServiceExt: setSupplicantStateASSOCIATED
07-28 12:05:34.608  1032  7965 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
07-28 12:05:34.608  1032  7965 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: Associated with f4:f2:6d:22:99:3e
,07-28 12:05:34.609  1032  1538 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=154647
07-28 12:05:34.609  1032  1538 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=154647
07-28 12:05:34.609  1032  1538 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=154647
07-28 12:05:34.609  1032  1538 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=154648
07-28 12:05:34.610  1032  1538 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=154648
07-28 12:05:34.610  1032  7965 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-28 12:05:34.610  1032  7965 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-28 12:05:34.611  1032  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=154649  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
07-28 12:05:34.612  1032  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=154650  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
07-28 12:05:34.615  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:34.615  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:34.615  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
07-28 12:05:34.615  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:34.615  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:34.615  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
07-28 12:05:34.615  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 12:05:34.615  1032  1032 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
07-28 12:05:34.615  1032  1097 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
07-28 12:05:34.619  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:34.619  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:05:34.619  1032  1538 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:05:34.620  1032  1538 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:05:34.620  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:05:34.621  1032  1538 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:05:34.622  1032  1538 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:05:34.622  1032  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:05:34.623  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:34.623  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:05:34.624  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-28 12:05:34.627  1032  7965 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-28 12:05:34.627  1032  7965 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-28 12:05:34.627  1032  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=154665  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
07-28 12:05:34.628  1032  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=154666  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
07-28 12:05:34.628  7919  7919 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-28 12:05:34.629  7919  7919 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-28 12:05:34.629  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 12:05:34.629  1032  1032 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
07-28 12:05:34.631  1032  7965 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
07-28 12:05:34.631  1032  7965 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-28 12:05:34.631  1032  7965 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-28 12:05:34.631  1032  7965 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
07-28 12:05:34.631  1032  7965 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-28 12:05:34.631  1032  7965 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-28 12:05:34.631  1032  7965 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-28 12:05:34.631  1032  7965 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-28 12:05:34.632  1032  1538 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=154670
07-28 12:05:34.632  1032  1538 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=154670
07-28 12:05:34.633  1032  1538 D WifiNative-wlan0: doString: [STATUS]
07-28 12:05:34.633  1032  1538 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
07-28 12:05:34.633  1032  7965 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-28 12:05:34.634  1032  7965 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-28 12:05:34.634  1032  1538 I WifiServiceExtension: setVHTCapabilityType  : false
07-28 12:05:34.639  1032  1538 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,07-28 12:05:34.639  1032  1538 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,07-28 12:05:34.644  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:34.644  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:34.644  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
07-28 12:05:34.644  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:34.644  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:05:34.644  1032  1538 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
07-28 12:05:34.644  1032  1538 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-28 12:05:34.645  1032  1538 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-28 12:05:34.645  1032  1545 D ConnectivityService: Got NetworkAgent Messenger
07-28 12:05:34.645  1032  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
07-28 12:05:34.645  1032  1545 D ConnectivityService: NetworkAgent connected
07-28 12:05:34.645  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:05:34.646  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:34.646  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:34.646  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
07-28 12:05:34.647  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:34.647  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:05:34.648  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:05:34.649  1032  1538 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-28 12:05:34.649  1032  1538 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-28 12:05:34.651  1032  1538 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-28 12:05:34.652  1032  1538 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-28 12:05:34.652  1032  1538 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-28 12:05:34.652  1032  1538 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-28 12:05:34.652  1032  1538 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,07-28 12:05:34.655  1032  1538 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-28 12:05:34.656   324   891 D CommandListener: Setting iface cfg
07-28 12:05:34.658  1032  1538 E WifiStateMachine: Start Dhcp Watchdog 3
07-28 12:05:34.658  1032  8023 D DhcpStateMachine: StoppedState
07-28 12:05:34.658  1032  8023 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:34.658  1032  8023 D DhcpStateMachine: WaitBeforeStartState
07-28 12:05:34.658  1032  1538 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=154696  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 12:05:34.659  1032  1538 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=154697  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 12:05:34.659  1032  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=154697  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 12:05:34.659  1032  1538 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=154697  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 12:05:34.659  1032  1538 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=154698  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 12:05:34.660  1032  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=154698  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 12:05:34.660  1032  1538 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14059] from screen [on:0 period:821519428] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-28 12:05:34.661  1032  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:821519429] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-28 12:05:34.661  1032  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-28 12:05:34.664  1032  1538 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:05:34.664  1032  1538 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:05:34.665  1032  1538 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:05:34.665  1032  1538 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:05:34.665  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:05:34.665  1032  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:05:34.665  1032  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:05:34.665  1032  1545 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
07-28 12:05:34.665  1032  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
07-28 12:05:34.666  1032  1538 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=133,0,0
07-28 12:05:34.666  1032  1538 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=133,0,0
07-28 12:05:34.666  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
07-28 12:05:34.666  7919  7919 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
07-28 12:05:34.666  1032  1538 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
,07-28 12:05:34.666  1032  1538 D WifiNative-wlan0: doBoolean: SET ps 0
07-28 12:05:34.667  1032  1538 D WifiNative-wlan0: SET ps 0: returned true
07-28 12:05:34.667  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
07-28 12:05:34.667  7919  7919 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
07-28 12:05:34.667  1032  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
07-28 12:05:34.668  1032  1537 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@10fbd944 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:34.668  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@10fbd944 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:34.668  1032  1538 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
07-28 12:05:34.668  1032  1538 V DhcpStateMachine: Current State is mWaitBeforeStartState.
07-28 12:05:34.668  1032  8023 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:34.668  1032  8023 D DhcpStateMachine: DHCP Start wake lock is acquired.
07-28 12:05:34.668  1032  1538 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
07-28 12:05:34.668   324   891 D CommandListener: Setting iface cfg
07-28 12:05:34.669   324   891 D CommandListener: Trying to bring up wlan0
07-28 12:05:34.669  1032  1538 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
07-28 12:05:34.670  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 12:05:34.670  1032  1032 D WifiServerServiceExt: setSupplicantStateCOMPLETED
07-28 12:05:34.671  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 12:05:34.671  1032  1032 D WifiServerServiceExt: setSupplicantStateCOMPLETED
07-28 12:05:34.671  1032  1538 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
07-28 12:05:34.672  1032  1538 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
07-28 12:05:34.672  1032  1537 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:34.672  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:34.672  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-28 12:05:34.672  7919  7919 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-28 12:05:34.673  1032  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-28 12:05:34.673  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
07-28 12:05:34.673  7919  7919 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
07-28 12:05:34.673  1032  1538 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
07-28 12:05:34.673  1032  1538 D WifiNative-wlan0: doBoolean: SET ps 1
07-28 12:05:34.693  1032  1538 D WifiNative-wlan0: SET ps 1: returned true
07-28 12:05:34.694  1032  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
,07-28 12:05:34.694  1032  1538 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-28 12:05:34.694  1032  1538 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-28 12:05:34.695  1032  1538 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-28 12:05:34.695  1032  1538 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-28 12:05:34.695  1032  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-28 12:05:34.696  1032  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-28 12:05:34.697  1032  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
07-28 12:05:34.697  1032  1538 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
07-28 12:05:34.697  1032  1538 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
07-28 12:05:34.698  1032  1538 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
07-28 12:05:34.699  1032  1545 D ConnectivityService: ignoring duplicate network state non-change
07-28 12:05:34.706  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:34.707  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:05:34.707  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:34.707  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-28 12:05:34.707  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
07-28 12:05:34.709  1032  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
07-28 12:05:34.710  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:05:34.711  1032  1545 D ConnectivityService: Adding iface wlan0 to network 102
07-28 12:05:34.712  1032  1538 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
07-28 12:05:34.725  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:34.725  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:34.725  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
07-28 12:05:34.725  1032  1032 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
07-28 12:05:34.726  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:34.726  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:34.726  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
07-28 12:05:34.726  1032  1032 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,07-28 12:05:34.732  1940  1940 V WfdStateTracker: handleWifiStateChangedEvent: 1
07-28 12:05:34.732  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:34.732  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:05:34.734  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:05:34.736  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:34.736  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:34.736  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
07-28 12:05:34.737  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:34.737  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
07-28 12:05:34.737  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:05:34.739  1032  1545 E ConnectivityService: Unexpected mtu value: 0, wlan0
07-28 12:05:34.739  1032  1545 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,07-28 12:05:34.740  1032  1545 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
07-28 12:05:34.741  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:34.741  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
07-28 12:05:34.741  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:05:34.741   324   891 E Netd    : netlink response contains error (File exists)
07-28 12:05:34.741  1032  1545 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
07-28 12:05:34.742  1032  1545 D ConnectivityService: addLocalRoutetoDefaultNetwork
07-28 12:05:34.742  1032  1545 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
07-28 12:05:34.742  1032  1545 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
07-28 12:05:34.746  1032  1545 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
07-28 12:05:34.747  1032  1545 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
07-28 12:05:34.747  1032  1545 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
07-28 12:05:34.747  1032  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
07-28 12:05:34.747  1032  8022 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:34.747  1032  8022 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
07-28 12:05:34.747  1032  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:05:34.747  1032  8022 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,07-28 12:05:34.747  1032  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:05:34.747  1032  8022 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
07-28 12:05:34.747  1032  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
07-28 12:05:34.747  1032  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:05:34.747  1032  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
07-28 12:05:34.747  1032  1545 D ConnectivityService: currentScore = 0, newScore = 20
07-28 12:05:34.747  1032  1545 D ConnectivityService:    accepting network in place of null
07-28 12:05:34.747  1032  1545 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:05:34.748  1851  1851 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:05:34.748  1032  1538 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:05:34.748  1032  1538 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:05:34.748  1851  1851 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-28 12:05:34.749   324  8027 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
07-28 12:05:34.749  1032  1545 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
07-28 12:05:34.749  1032  1545 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
07-28 12:05:34.749  1032  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-28 12:05:34.750  1032  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-28 12:05:34.750  1032  1545 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
07-28 12:05:34.750   324  8027 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
07-28 12:05:34.751   324  8027 D libc-netbsd: res_queryN name = clients3.google.com., class = 1, type = 28
07-28 12:05:34.751  1032  1545 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU,: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
07-28 12:05:34.752   324  8027 D libc-netbsd: res_queryN name = clients3.google.com., class = 1, type = 1
07-28 12:05:34.752  1032  1545 D ConnectivityService: validation of new default Network = false
07-28 12:05:34.752  1032  1545 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
07-28 12:05:34.752  1032  1545 D DSQN    : enableDataServiceNotify 
07-28 12:05:34.752  1032  1545 D DSQN    : start dsqn bin
,07-28 12:05:34.753  1032  1095 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-28 12:05:34.754  1032  8022 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
07-28 12:05:34.755  1032  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
07-28 12:05:34.755  1032  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:05:34.755  1032  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:05:34.755  1032  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:05:34.745  8028  8028 W dsqn    : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:05:34.745  8028  8028 W dsqn    : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:05:34.757  1032  1032 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
07-28 12:05:34.757  1032  1032 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-28 12:05:34.757  1032  1032 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-28 12:05:34.757  1032  1032 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-28 12:05:34.760  1602  2072 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,07-28 12:05:34.769  8028  8028 E DSQN    : DSQN ssw
07-28 12:05:34.771  1032  1536 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,07-28 12:05:34.781  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-28 12:05:34.782  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:05:34.783  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:05:34.784  8005  8005 W ExternalStrings: load override strings
07-28 12:05:34.784  8005  8005 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
07-28 12:05:34.784  8005  8005 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
07-28 12:05:34.784  8005  8005 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
07-28 12:05:34.784  8005  8005 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
07-28 12:05:34.784  8005  8005 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
07-28 12:05:34.784  8005  8005 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
07-28 12:05:34.784  8005  8005 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
07-28 12:05:34.784  8005  8005 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
07-28 12:05:34.784  8005  8005 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
07-28 12:05:34.784  8005  8005 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
07-28 12:05:34.784  8005  8005 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
07-28 12:05:34.784  8005  8005 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:05:34.784  8005  8005 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
07-28 12:05:34.784  8005  8005 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-28 12:05:34.784  8005  8005 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:05:34.784  8005  8005 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:05:34.784  8005  8005 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-28 12:05:34.784  8005  8005 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-28 12:05:34.786  8005  8005 D StatusProvider: onCreate
07-28 12:05:34.827  8005  8005 V Signer  : override build config not found
,07-28 12:05:34.827  8005  8005 D Signer  : value of property debug is false
07-28 12:05:34.854  8005  8005 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
07-28 12:05:34.854  8005  8005 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
,07-28 12:05:34.854  8005  8005 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
07-28 12:05:34.854  8005  8005 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
07-28 12:05:34.854  8005  8005 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
07-28 12:05:34.855  8005  8005 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
07-28 12:05:34.855  8005  8005 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
07-28 12:05:34.855  8005  8005 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
,07-28 12:05:34.855  8005  8005 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
07-28 12:05:34.855  8005  8005 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
07-28 12:05:34.855  8005  8005 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
07-28 12:05:34.856  8005  8005 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
,07-28 12:05:34.856  8005  8005 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
07-28 12:05:34.863  8005  8005 V LGMDMManager: Create singleton instance
07-28 12:05:34.871  1032  8023 D DhcpStateMachine: DHCPV4 request on wlan0
07-28 12:05:34.873  1032  8023 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
07-28 12:05:34.873  1032  8023 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,07-28 12:05:34.875  8032  8032 W dhcpcd  : type=1400 audit(0.0:197): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:05:34.875  8032  8032 W dhcpcd  : type=1400 audit(0.0:198): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:05:34.898  8032  8032 I dhcpcd  : version 5.5.6 starting
07-28 12:05:34.901  8032  8032 E dhcpcd  : get_duid: m
07-28 12:05:34.901  8032  8032 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
07-28 12:05:34.901  8032  8032 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,07-28 12:05:34.908  8005  8005 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
07-28 12:05:34.948  8032  8032 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
07-28 12:05:34.949  8032  8032 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
07-28 12:05:34.949  8032  8032 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,07-28 12:05:34.949  8032  8032 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
07-28 12:05:34.949  8032  8032 D dhcpcd  : wlan0: sending REQUEST (xid 0x62d145e5), next in 3.85 seconds
07-28 12:05:34.957  6524  6666 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 836)
07-28 12:05:34.957  6524  6666 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 836)
07-28 12:05:34.957  6524  6666 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 836)
07-28 12:05:34.958  6524  6666 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 836)
07-28 12:05:34.960  6524  6666 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 841)
07-28 12:05:34.960  6524  6666 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Nothing to close (thread ID: 841)
07-28 12:05:34.960  6524  6666 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 841)
07-28 12:05:34.961  6524  6666 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Closing... (thread ID: 842)
07-28 12:05:34.962  6524  6666 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 844)
,07-28 12:05:34.964  6524  6666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:05:34.964  6524  6666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@125864ef added. We now have 2 listener(s)
07-28 12:05:34.965  1032  1642 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:05:34.967  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 12:05:34.968  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:05:34.968  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:05:34.968  6524  6666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:05:34.968  6524  6666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e3dfbfc added. We now have 9 listener(s)
07-28 12:05:34.968  6524  6666 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:05:34.969  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-28 12:05:34.970  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:05:34.973  6524  6666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:05:34.973  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:05:34.973  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:34.973  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:05:34.973  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:05:34.973  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:05:34.973  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:05:34.973  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:05:34.975  6524  6666 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:05:34.975  6524  6666 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:05:34.975  6524  6666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:05:34.975  6524  6666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@125608da added. We now have 3 listener(s)
07-28 12:05:34.975  1032  1047 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:05:34.978  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:05:34.979  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:34.980  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 12:05:34.980  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:05:34.980  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:05:34.980  6524  6666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:05:34.980  6524  6666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37f0610b added. We now have 10 listener(s)
07-28 12:05:34.980  6524  6666 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:05:34.980  6524  6666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:05:34.980  6524  6666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:34.980  6524  6666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:05:34.981  6524  6666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:34.981  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:34.981  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:05:34.981  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:05:34.981  6524  6666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@125864ef removed from the list
07-28 12:05:34.981  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:34.981  6524  6666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e3dfbfc removed from the list
07-28 12:05:34.981  6524  6666 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:05:34.981  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:34.982  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:34.982  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:34.983  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:34.983  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:34.984  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:34.984  6524  6666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e3dfbfc not in the list
07-28 12:05:34.984  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:34.984  6524  6666 D org.thaliproject.p2p.btc,onnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:34.985  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:34.985  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:34.985  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:34.985  6524  6666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37f0610b removed from the list
07-28 12:05:34.985  6524  6666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:34.985  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:34.985  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:34.985  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:05:34.985  6524  6666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@125608da removed from the list
07-28 12:05:34.985  6524  6666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:05:34.985  6524  6666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@286cdbe8 added. We now have 2 listener(s)
07-28 12:05:34.986  1032  1886 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:05:34.988  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 12:05:34.988  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:05:34.988  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:05:34.988  6524  6666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:05:34.988  6524  6666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eca8201 added. We now have 9 listener(s)
07-28 12:05:34.988  6524  6666 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:05:34.988  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-28 12:05:34.990  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:05:34.990  8005  8005 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-28 12:05:34.991  8005  8041 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-28 12:05:34.992  8032  8032 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
07-28 12:05:34.996  6524  6666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:05:34.996  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:05:34.996  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:34.996  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:05:34.996  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:05:34.996  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:05:34.996  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:05:34.996  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:05:34.997  6524  6666 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:05:34.997  6524  6666 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:05:34.997  6524  6666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:05:34.997  6524  6666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc202e7 added. We now have 3 listener(s)
07-28 12:05:34.997  1032  1047 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:05:34.999  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:34.999  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 12:05:34.999  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:05:34.999  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:05:34.999  6524  6666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:05:35.000  6524  6666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e27ce94 added. We now have 10 listener(s)
07-28 12:05:35.000  6524  6666 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:05:35.000  6524  6666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:05:35.000  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 12:05:35.000  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:05:35.000  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-28 12:05:35.000  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:35.002  6524  6666 V org.thaliproject.p,2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-28 12:05:35.004  1032  1781 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-28 12:05:35.007  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-28 12:05:35.007  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-28 12:05:35.008  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-28 12:05:35.009  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:05:35.010  6524  6666 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-28 12:05:35.010  6524  6666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:35.010  6524  6666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:05:35.012  6524  6666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:05:35.012  6524  6666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:35.012  6524  6666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:05:35.013  6524  6666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:35.013  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:35.013  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:05:35.013  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:05:35.013  6524  6666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@286cdbe8 removed from the list
07-28 12:05:35.013  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:35.014  6524  6666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eca8201 removed from the list
07-28 12:05:35.014  6524  6666 D io.jxcore.node.ConnectivityMonitor: stop
,07-28 12:05:35.014  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:35.014  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:35.014  6720  6720 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-28 12:05:35.014  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:05:35.018  8032  8032 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
07-28 12:05:35.018  8032  8032 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
07-28 12:05:35.018  8032  8032 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
07-28 12:05:35.019  8032  8032 D dhcpcd  : wlan0: adding default route via 192.168.1.1
07-28 12:05:35.019  8032  8032 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
07-28 12:05:35.019  8032  8032 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
07-28 12:05:35.019  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:35.019  8032  8032 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
07-28 12:05:35.019  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:35.019  8032  8032 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
07-28 12:05:35.019  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:35.019  6524  6666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eca8201 not in the list
07-28 12:05:35.019  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:35.019  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:35.020  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:35.021  6524  6666 D BluetoothLeScanner: could not find callback wrapper
07-28 12:05:35.021  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:05:35.021  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:35.021  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:35.021  6524  6666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e27ce94 removed from the list
07-28 12:05:35.021  6524  6666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:35.021  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:35.021  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:35.021  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:05:35.021  6524  6666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc202e7 removed from the list
07-28 12:05:35.022  6524  6666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:05:35.022  6524  6666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1321e683 added. We now have 2 listener(s)
07-28 12:05:35.022  1032  2026 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:05:35.023  6720  6720 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:05:35.025  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 12:05:35.025  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
07-28 12:05:35.025  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:05:35.025  6524  6666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:05:35.025  6524  6666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5fd4000 added. We now have 9 listener(s)
07-28 12:05:35.025  6524  6666 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:05:35.025  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-28 12:05:35.058  1032  2051 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8047 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,07-28 12:05:35.064  1032  2051 I ActivityManager: Killing 7075:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
07-28 12:05:35.152  8005  8040 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,07-28 12:05:35.279  1032  8023 D DhcpStateMachine: DHCPV4 succeeded on wlan0
07-28 12:05:35.280  1032  8023 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
07-28 12:05:35.281  1032  8023 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
,07-28 12:05:35.281  1032  8023 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
,07-28 12:05:35.281  1032  8023 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
,07-28 12:05:35.281  1032  8023 V DhcpStateMachine: Current State is mWaitBeforeStartState.
,07-28 12:05:35.281  1032  8023 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
07-28 12:05:35.281  1032  8023 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
07-28 12:05:35.281  1032  8023 D DhcpStateMachine: RunningState
07-28 12:05:35.342  1032  1886 W libprocessgroup: failed to open /acct/uid_10093/pid_7075/cgroup.procs: No such file or directory
07-28 12:05:35.342  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 12:05:35.355  6524  6666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:05:35.355  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:05:35.355  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:35.355  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:05:35.355  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:05:35.355  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:05:35.355  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:05:35.355  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:05:35.364  6524  6666 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:05:35.364  6524  6666 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:05:35.364  6524  6666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:05:35.364  6524  6666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@213b567e added. We now have 3 listener(s)
,07-28 12:05:35.370  1032  1993 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:05:35.374  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:35.378  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 12:05:35.379  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:05:35.379  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:05:35.379  6524  6666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:05:35.379  6524  6666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e1267df added. We now have 10 listener(s)
07-28 12:05:35.379  6524  6666 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:05:35.379  6524  6666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:05:35.380  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:35.380  6524  6666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:05:35.380  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 12:05:35.380  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:05:35.380  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-28 12:05:35.390  6524  6666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-28 12:05:35.390  1032  2026 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:05:35.396  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-28 12:05:35.397  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-28 12:05:35.400  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-28 12:05:35.401  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:05:35.403  6524  6666 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-28 12:05:35.403  6524  6666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:05:35.403  6524  6666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:35.403  6524  6666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:05:35.403  6524  6666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:35.403  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:35.403  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:05:35.403  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:05:35.403  6524  6666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1321e683 removed from the list
07-28 12:05:35.403  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:35.403  6524  6666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5fd4000 removed from the list
07-28 12:05:35.403  6524  6666 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:05:35.403  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:35.404  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:35.404  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:35.405  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:35.405  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:35.405  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:35.405  6524  6666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5fd4000 not in the list
07-28 12:05:35.405  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:35.405  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:35.406  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:35.406  6524  6666 D BluetoothLeScanner: could not find callback wrapper
07-28 12:05:35.407  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:05:35.407  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:35.407  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:35.407  6524  6666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e1267df removed from the list
07-28 12:05:35.407  6524  6666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:35.407  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:35.407  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:35.407  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:05:35.407  6524  6666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@213b567e removed from the list
07-28 12:05:35.408  6524  6666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:05:35.408  6524  6666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26325c8a added. We now have 2 listener(s)
07-28 12:05:35.408  1032  1642 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:05:35.409  8047  8047 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-28 12:05:35.411  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 12:05:35.411  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:05:35.411  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:05:35.411  6524  6666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:05:35.412  6524  6666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@385fa2fb added. We now have 9 listener(s)
07-28 12:05:35.412  6524  6666 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:05:35.412  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-28 12:05:35.419  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:05:35.424  6524  6666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:05:35.424  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:05:35.424  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:35.424  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:05:35.424  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:05:35.424  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:05:35.424  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:05:35.424  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-28 12:05:35.426  6524  6666 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:05:35.426  6524  6666 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:05:35.428  6524  6666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:05:35.428  6524  6666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13f6ed71 added. We now have 3 listener(s)
07-28 12:05:35.428  1032  1885 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:05:35.430  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:35.431  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 12:05:35.431  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:05:35.431  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:05:35.431  6524  6666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:05:35.431  6524  6666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12e1b756 added. We now have 10 listener(s)
07-28 12:05:35.431  6524  6666 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:05:35.431  6524  6666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:05:35.431  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 12:05:35.431  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:05:35.431  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-28 12:05:35.432  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:35.434  6524  6666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-28 12:05:35.435  1032  1048 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:05:35.439  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-28 12:05:35.440  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-28 12:05:35.441  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-28 12:05:35.442  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:05:35.443  6524  6666 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-28 12:05:35.446  6524  6666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:05:35.446  6524  6666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:35.446  6524  6666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:05:35.446  6524  6666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:35.446  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:35.446  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:05:35.446  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:05:35.446  6524  6666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26325c8a removed from the list
07-28 12:05:35.446  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:35.446  6524  6666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@385fa2fb removed from the list
07-28 12:05:35.446  6524  6666 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:05:35.446  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:35.447  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:35.447  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:35.447  8047  8047 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
07-28 12:05:35.448  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:35.448  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:35.448  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:35.448  6524  6666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@385fa2fb not in the list
07-28 12:05:35.448  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:35.448  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:35.449  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:35.450  6524  6666 D BluetoothLeScanner: could not find callback wrapper
07-28 12:05:35.450  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:05:35.450  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:35.450  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:35.450  6524  6666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSet,tings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12e1b756 removed from the list
07-28 12:05:35.450  6524  6666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:35.450  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:35.450  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:35.450  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:05:35.450  6524  6666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13f6ed71 removed from the list
07-28 12:05:35.451  6524  6666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:05:35.451  6524  6666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@83befad added. We now have 2 listener(s)
07-28 12:05:35.451  1032  1993 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-28 12:05:35.454  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 12:05:35.454  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:05:35.454  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:05:35.455  6524  6666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:05:35.455  6524  6666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1159f2e2 added. We now have 9 listener(s)
07-28 12:05:35.455  6524  6666 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:05:35.455  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-28 12:05:35.463  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:05:35.466  6524  6666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:05:35.466  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:05:35.466  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:35.466  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:05:35.466  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:05:35.466  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:05:35.466  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:05:35.466  6524  6666 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-28 12:05:35.467  6524  6666 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:05:35.467  6524  6666 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:05:35.468  6524  6666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:05:35.468  6524  6666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4e0a930 added. We now have 3 listener(s)
07-28 12:05:35.468  1032  1885 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:05:35.469  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:35.470  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 12:05:35.470  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:05:35.470  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:05:35.471  6524  6666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:05:35.471  6524  6666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1254d9a9 added. We now have 10 listener(s)
07-28 12:05:35.471  6524  6666 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:05:35.471  6524  6524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:35.471  6524  6666 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:05:35.472  6524  6666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:35.472  6524  6666 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:05:35.472  6524  6666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:35.472  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:35.472  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:05:35.472  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:05:35.472  6524  6666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@83befad removed from the list
07-28 12:05:35.472  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:35.472  6524  6666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1159f2e2 removed from the list
07-28 12:05:35.472  6524  6666 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:05:35.472  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:35.472  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:35.472  6524  6666 D org.,thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:35.473  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:35.473  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:35.473  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:35.473  6524  6666 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1159f2e2 not in the list
07-28 12:05:35.473  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:35.473  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:35.474  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:35.474  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:35.474  6524  6666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:35.474  6524  6666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1254d9a9 removed from the list
07-28 12:05:35.474  6524  6666 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:35.474  6524  6666 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:35.474  6524  6666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:35.474  6524  6666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:05:35.474  6524  6666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4e0a930 removed from the list
07-28 12:05:35.475  6524  6666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-28 12:05:35.475  6524  6666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
07-28 12:05:35.475  6524  6666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-28 12:05:35.475  6524  6666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
07-28 12:05:35.476  6524  6666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
07-28 12:05:35.476  6524  6666 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:35.484  6524  8089 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 850, name: My test thread name)
07-28 12:05:35.484  6524  8089 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 850, thread name: My test thread name)
07-28 12:05:35.485  6524  8089 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 850, name: My test thread name)
,07-28 12:05:35.490  6524  8090 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 852, name: My test thread name)
07-28 12:05:35.490  6524  8090 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 852, thread name: My test thread name)
07-28 12:05:35.490  6524  8090 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 852, name: My test thread name)
07-28 12:05:35.492  6524  6666 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
07-28 12:05:35.493  6524  6666 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
07-28 12:05:35.493  6524  6666 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
07-28 12:05:35.493  6524  6666 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
07-28 12:05:35.493  6524  6666 D com.test.thalitest.ThaliTestRunner: Total duration: 23210 ms
07-28 12:05:35.494  6524  6666 I jxcore-log: Total number of executed tests:  80
07-28 12:05:35.494  6524  6666 I jxcore-log: 
07-28 12:05:35.494  6524  6666 I jxcore-log: Number of passed tests:  80
07-28 12:05:35.494  6524  6666 I jxcore-log: 
07-28 12:05:35.494  6524  6666 I jxcore-log: Number of failed tests:  0
07-28 12:05:35.494  6524  6666 I jxcore-log: 
07-28 12:05:35.494  6524  6666 I jxcore-log: Number of ignored tests:  0
07-28 12:05:35.494  6524  6666 I jxcore-log: 
07-28 12:05:35.495  6524  6666 I jxcore-log: Total duration:  23210
07-28 12:05:35.495  6524  6666 I jxcore-log: 
07-28 12:05:35.495  6524  6666 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
07-28 12:05:35.495  6524  6666 I jxcore-log: 
07-28 12:05:35.499  6524  6666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:05:35.499  6524  6666 I jxcore-log: 
,07-28 12:05:35.502  6524  6666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:05:35.502  6524  6666 I jxcore-log: 
07-28 12:05:35.503  6524  6666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:05:35.503  6524  6666 I jxcore-log: 
07-28 12:05:35.504  6524  6666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:05:35.504  6524  6666 I jxcore-log: 
07-28 12:05:35.504  8047  8047 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
07-28 12:05:35.505  8047  8047 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
07-28 12:05:35.505  6524  6666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:05:35.505  6524  6666 I jxcore-log: 
07-28 12:05:35.505  8047  8047 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
07-28 12:05:35.506  8047  8047 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
07-28 12:05:35.506  8047  8047 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
07-28 12:05:35.507  6524  6666 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
07-28 12:05:35.507  6524  6666 I jxcore-log: 
07-28 12:05:35.508  8047  8047 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
07-28 12:05:35.509  6524  6524 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
07-28 12:05:35.509  6524  6666 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-28 12:05:35.509  6524  6666 I jxcore-log: 
07-28 12:05:35.511  6524  6666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-28 12:05:35.511  6524  6666 I jxcore-log: 
07-28 12:05:35.512  6524  6666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:05:35.512  6524  6666 I jxcore-log: 
07-28 12:05:35.513  8047  8047 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
07-28 12:05:35.513  6524  6666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:05:35.513  6524  6666 I jxcore-log: 
07-28 12:05:35.514  6524  6666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-28 12:05:35.514  6524  6666 I jxcore-log: 
07-28 12:05:35.515  6524  6666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-28 12:05:35.515  6524  6666 I jxcore-log: 
07-28 12:05:35.516  6524  6666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:05:35.516  6524  6666 I jxcore-log: 
07-28 12:05:35.517  6524  6666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:05:35.517  6524  6666 I jxcore-log: 
07-28 12:05:35.518  6524  6666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-28 12:05:35.518  6524  6666 I jxcore-log: 
07-28 12:05:35.519  8047  8047 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:05:35.519  6524  6666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-28 12:05:35.519  6524  6666 I jxcore-log: 
07-28 12:05:35.520  6524  6666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:05:35.520  6524  6666 I jxcore-log: 
07-28 12:05:35.520  8047  8047 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:05:35.520  6524  6666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:05:35.520  6524  6666 I jxcore-log: 
07-28 12:05:35.521  6524  6666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-28 12:05:35.521  6524  6666 I jxcore-log: 
07-28 12:05:35.522  6524  6666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-28 12:05:35.522  6524  6666 I jxcore-log: 
07-28 12:05:35.523  6524  6666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 12:05:35.523  6524  6666 I jxcore-log: 
07-28 12:05:35.523  6524  6666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 12:05:35.523  6524  6666 I jxcore-log: 
07-28 12:05:35.524  6524  6666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:05:35.524  6524  6666 I jxcore-log: 
,07-28 12:05:35.525  6524  6666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:05:35.525  6524  6666 I jxcore-log: 
07-28 12:05:35.526  6524  6666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:05:35.526  6524  6666 I jxcore-log: 
07-28 12:05:35.526  6524  6666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:05:35.526  6524  6666 I jxcore-log: 
07-28 12:05:35.527  6524  6666 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:05:35.527  6524  6666 I jxcore-log: 
07-28 12:05:35.529  8047  8047 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-28 12:05:35.531  8005  8005 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:05:35.531  8005  8041 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-28 12:05:35.532  8047  8047 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
07-28 12:05:35.533  8005  8040 D LgDataFeature: LgDataFeature() Constructor: none
07-28 12:05:35.533  8005  8040 D LgDataFeature: LgDataFeature() Constructor Done, null
07-28 12:05:35.534  8047  8047 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
07-28 12:05:35.536  6720  6720 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:05:35.541  6720  6720 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:05:35.545  8047  8047 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:05:35.545  8047  8047 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:05:35.546  8047  8047 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,07-28 12:05:35.548  6720  6720 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
07-28 12:05:35.551  6720  6720 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
07-28 12:05:35.553  8005  8005 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:05:35.553  8005  8041 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-28 12:05:35.558  6720  6720 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:05:35.564  6720  6720 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:05:35.569  8047  8047 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:05:35.569  8047  8047 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:05:35.569  8047  8047 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-28 12:05:35.572  8005  8005 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:05:35.572  8005  8041 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-28 12:05:35.578  6720  6720 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:05:35.584  6720  6720 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:05:35.590  8047  8047 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:05:35.591  8047  8047 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:05:35.591  8047  8047 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,07-28 12:05:35.596  8005  8005 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:05:35.596  8005  8041 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-28 12:05:35.603  6720  6720 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:05:35.612  6720  6720 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:05:35.620  8047  8047 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-28 12:05:35.620  8047  8047 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:05:35.621  8047  8047 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-28 12:05:35.624  6720  6720 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-28 12:05:35.624  6720  6720 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-28 12:05:35.624  6720  6720 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-28 12:05:35.625  6720  6720 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-28 12:05:35.625  6720  6720 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-28 12:05:35.626  6720  6720 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-28 12:05:35.626  6720  6720 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
07-28 12:05:35.626  6720  6720 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-28 12:05:35.626  6720  6720 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-28 12:05:35.626  6720  6720 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-28 12:05:35.626  6720  6720 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
07-28 12:05:35.626  6720  6720 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-28 12:05:35.629  8005  8005 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:05:35.630  8005  8041 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-28 12:05:35.648  6720  6720 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:05:35.653  6720  6720 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-28 12:05:35.658  8047  8047 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:05:35.659  8047  8047 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:05:35.659  8047  8047 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-28 12:05:35.661  8005  8005 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:05:35.662  8005  8041 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,07-28 12:05:35.669  6720  6720 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-28 12:05:35.672  8005  8040 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
07-28 12:05:35.674  6720  6720 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-28 12:05:35.679  8047  8047 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:05:35.679  8047  8047 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:05:35.679  8047  8047 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-28 12:05:35.687  8005  8041 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-28 12:05:35.687  8005  8005 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-28 12:05:35.696  8005  8040 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
07-28 12:05:35.702  6720  6720 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:05:35.707  6720  6720 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:05:35.709  8005  8040 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
07-28 12:05:35.709  8005  8040 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
07-28 12:05:35.710  8005  8040 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
07-28 12:05:35.710  8005  8040 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
07-28 12:05:35.711  8005  8040 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
07-28 12:05:35.713  8047  8047 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:05:35.713  8047  8047 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:05:35.718  8047  8047 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,07-28 12:05:35.721  8005  8040 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
07-28 12:05:35.721  8005  8005 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:05:35.722  8005  8041 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-28 12:05:35.723  8005  8040 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
07-28 12:05:35.727  6720  6720 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:05:35.732  6720  6720 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:05:35.738  8047  8047 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:05:35.739  8047  8047 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:05:35.739  8047  8047 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-28 12:05:35.742  8005  8005 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-28 12:05:35.743  8005  8041 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-28 12:05:35.745  7959  7959 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
07-28 12:05:35.749  7959  7959 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
07-28 12:05:35.751  6720  6720 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:05:35.757  6720  6720 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:05:35.763  8047  8047 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:05:35.763  8047  8047 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:05:35.764  8047  8047 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
07-28 12:05:35.765  8047  8047 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
07-28 12:05:35.765  8047  8047 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
07-28 12:05:35.769  8005  8005 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:05:35.769  8005  8041 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,07-28 12:05:35.773  7959  7959 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
07-28 12:05:35.774  7959  7959 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
07-28 12:05:35.777  6720  6720 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-28 12:05:35.777  8094  8094 D AndroidRuntime: 
07-28 12:05:35.777  8094  8094 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-28 12:05:35.780  8094  8094 D AndroidRuntime: CheckJNI is OFF
07-28 12:05:35.783  6720  6720 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:05:35.790  8047  8047 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:05:35.791  8047  8047 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:05:35.792  8047  8047 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
07-28 12:05:35.794  8047  8047 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
07-28 12:05:35.794  8047  8047 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
07-28 12:05:35.797  8005  8005 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
07-28 12:05:35.803  8047  8047 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
07-28 12:05:35.804  8047  8047 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
07-28 12:05:35.804  8047  8047 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
07-28 12:05:35.809  1032  1538 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-28 12:05:35.810  1032  1538 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-28 12:05:35.810  1032  1538 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-28 12:05:35.811  1032  1538 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-28 12:05:35.811  1032  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-28 12:05:35.811  1032  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-28 12:05:35.812  1032  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
07-28 12:05:35.812  1032  1545 D ConnectivityService: identical MTU - not setting
07-28 12:05:35.812  1032  1545 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
07-28 12:05:35.813  1032  1545 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
07-28 12:05:35.813  1032  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:05:35.813  1032  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:05:35.813  1032  1545 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:05:35.814  1602  2072 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,07-28 12:05:35.844  8047  8047 D LgDataFeature: LgDataFeature() Constructor: none
07-28 12:05:35.844  8047  8047 D LgDataFeature: LgDataFeature() Constructor Done, null
07-28 12:05:35.850  8047  8047 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
07-28 12:05:35.852  8047  8047 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
07-28 12:05:35.852  8047  8047 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
07-28 12:05:35.852  8047  8047 V SoundPool: doLoad: loading sample sampleID=1
07-28 12:05:35.852  8047  8047 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
07-28 12:05:35.853  8047  8113 V SoundPool: Start decode
07-28 12:05:35.853  8047  8113 V MediaPlayer[Native]: decode(31, 10857164, 17813)
07-28 12:05:35.854   329  2215 V MediaPlayerService: decode(23, 10857164, 17813)
07-28 12:05:35.854   329  2215 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
,07-28 12:05:35.854   329  2215 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
07-28 12:05:35.854   329  2215 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
07-28 12:05:35.854   329  2215 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
07-28 12:05:35.854   329  2215 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
07-28 12:05:35.854   329  2215 V MediaPlayerService: player type = 3
07-28 12:05:35.854   329  2215 V AwesomePlayer: AwesomePlayer create()
07-28 12:05:35.855   329  2215 V AwesomePlayer: reset_l() 
07-28 12:05:35.855   329  2215 V AwesomePlayer: cancelPlayerEvents
07-28 12:05:35.855   329  2215 V AwesomePlayer: setAudioSink() 
07-28 12:05:35.855   329  2215 V AwesomePlayer: reset_l() 
07-28 12:05:35.855   329  2215 V AudioCache: notify(0xb16a6040, 8, 0, 0)
07-28 12:05:35.855   329  2215 V AudioCache: ignored
07-28 12:05:35.855   329  2215 V AwesomePlayer: cancelPlayerEvents
07-28 12:05:35.855   329  2215 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
07-28 12:05:35.855   329  2215 V AwesomePlayer: setDataSource_l dataSource
07-28 12:05:35.855   329  2215 V LGParserOSAL: SniffLGParser start
07-28 12:05:35.855  8047  8047 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
07-28 12:05:35.855   329  2215 V LGParserOSAL: MainType:5, SubType=0
07-28 12:05:35.855   329  2215 V LGParserOSAL: #### check Mime : application/ogg
07-28 12:05:35.855   329  2215 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
07-28 12:05:35.855   329  2215 E MediaExtractor: Use LGExtractor :application/ogg 
07-28 12:05:35.856  8047  8047 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
07-28 12:05:35.856  8047  8047 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
07-28 12:05:35.867  8047  8047 V LGMDMManager: Create singleton instance
,07-28 12:05:35.868  7491  7491 D UEI.SmartControl: QS Service created
07-28 12:05:35.880  7491  7491 I UEI.SmartControl: Service initServices...
07-28 12:05:35.881  7491  7491 D UEI.SmartControl: QS start get config
07-28 12:05:35.893   329  2215 V LGParserOSAL: supported mime: application/ogg
07-28 12:05:35.893   329  2215 V AwesomePlayer: setDataSource_l() extractor countTracks=1
07-28 12:05:35.893   329  2215 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
07-28 12:05:35.893   329  2215 V AwesomePlayer: mBitrate = -1 bits/sec
07-28 12:05:35.893   329  2215 V AwesomePlayer: AudioTrack Setting
,07-28 12:05:35.894   329  2215 V AwesomePlayer: AudioTrack Setting channelCount = 2
07-28 12:05:35.894   329  2215 V AwesomePlayer: setAudioSource() 
07-28 12:05:35.894   329  2215 V MediaPlayerService: prepare
07-28 12:05:35.894   329  2215 V AwesomePlayer: prepareAsync_l() 
07-28 12:05:35.894   329  2215 V MediaPlayerService: wait for prepare
07-28 12:05:35.895   329  8114 V AwesomePlayer: onPrepareAsyncEvent() 
07-28 12:05:35.895   329  8114 V AwesomePlayer: initAudioDecoder() 
07-28 12:05:35.895   329  8114 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
07-28 12:05:35.895   329  8114 V AudioSystem: isOffloadSupported()
07-28 12:05:35.895   329  8114 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
07-28 12:05:35.895   329  8114 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
07-28 12:05:35.895   329  8114 I AudioFlinger: isAudioPlaybackHookOn() false
07-28 12:05:35.895   329  8114 V AwesomePlayer: getUseOffload() = 0 
07-28 12:05:35.895   329  8114 V OMXCodec: OMXCodec::Create
07-28 12:05:35.895   329  8114 V OMXCodec: findMatchingCodecs()
07-28 12:05:35.895   329  8114 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
07-28 12:05:35.895   329  8114 V OMXCodec: matchingCodecs.size()=1
07-28 12:05:35.895   329  8114 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
07-28 12:05:35.897   329  8114 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
07-28 12:05:35.897   329  8114 V LGCodecAdapter: LG Codec Adapter start
07-28 12:05:35.897   329  8114 V OMXCodec: OMXCodec Createtor
07-28 12:05:35.897   329  8114 V OMXCodec: setComponentRole
07-28 12:05:35.897   329  8114 V OMXCodec: configureCodec protected=0
07-28 12:05:35.897   329  8114 V LGCodecAdapter: called getLGCodecSpecificData
07-28 12:05:35.897   329  8114 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
07-28 12:05:35.897   329  8114 V LGCodecOSAL: Called LGconfigureCodecMETA
07-28 12:05:35.897   329  8114 V LGCodecOSAL: Called LGconfigureCodecMSG
07-28 12:05:35.897   329  8114 V LGCodecOSAL: Not support LGCodec
07-28 12:05:35.897   329  8114 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
07-28 12:05:35.897   329  8114 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
07-28 12:05:35.897   329  8114 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
07-28 12:05:35.897   329  8114 I AwesomePlayer: Could not offload audio decode, try pcm offload
07-28 12:05:35.897   329  8114 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
07-28 12:05:35.897   329  8114 V AudioSystem: isOffloadSupported()
07-28 12:05:35.897   329  8114 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
07-28 12:05:35.897   329  8114 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
07-28 12:05:35.897   329  8114 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
07-28 12:05:35.897   329  8114 V OMXCodec: init()
07-28 12:05:35.898   329  8114 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
07-28 12:05:35.898   329  8114 V OMXCodec: allocateBuffers
07-28 12:05:35.898   329  8114 V OMXCodec: allocateBuffersOnPort portIndex=0
07-28 12:05:35.898   329  8114 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
07-28 12:05:35.898   329  8114 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7650 on input port
07-28 12:05:3,5.898   329  8114 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7790 on input port
07-28 12:05:35.898   329  8114 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f77e0 on input port
07-28 12:05:35.898   329  8114 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7830 on input port
07-28 12:05:35.898   329  8114 V OMXCodec: allocateBuffersOnPort portIndex=1
07-28 12:05:35.898   329  8114 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
07-28 12:05:35.899   329  8114 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f78d0 on output port
07-28 12:05:35.899   329  8114 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
07-28 12:05:35.899   329  8114 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
07-28 12:05:35.899   329  8114 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
07-28 12:05:35.899   329  8114 V OMXCodec: init() mAsyncCompletion wait!!! 
07-28 12:05:35.899   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
07-28 12:05:35.899   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
07-28 12:05:35.899   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
07-28 12:05:35.899   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
07-28 12:05:35.899   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
07-28 12:05:35.899   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
07-28 12:05:35.899   329  8114 V OMXCodec: init() mAsyncCompletion wait free! 
07-28 12:05:35.899   329  8114 V AwesomePlayer: finishAsyncPrepare_l() 
07-28 12:05:35.899   329  8114 V AudioCache: notify(0xb16a6040, 5, 0, 0)
07-28 12:05:35.899   329  8114 V AudioCache: ignored
07-28 12:05:35.899   329  8114 V AudioCache: notify(0xb16a6040, 1, 0, 0)
07-28 12:05:35.899   329  8114 V AudioCache: prepared
07-28 12:05:35.899   329  2215 V AudioCache: wait - success
07-28 12:05:35.899   329  2215 V MediaPlayerService: start
07-28 12:05:35.899   329  2215 V AwesomePlayer: play_l() 
07-28 12:05:35.899   329  2215 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
07-28 12:05:35.899   329  2215 V AwesomePlayer: createAudioPlayer_l
07-28 12:05:35.899   329  2215 V AwesomePlayer: seekAudioIfNecessary_l() 
07-28 12:05:35.899   329  2215 V AwesomePlayer: startAudioPlayer_l() 
07-28 12:05:35.899   329  2215 D AudioPlayer: start of Playback, useOffload 0
07-28 12:05:35.899   329  2215 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
07-28 12:05:35.900   329  2215 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
07-28 12:05:35.902   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
07-28 12:05:35.902   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
07-28 12:05:35.902   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
07-28 12:05:35.902   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
07-28 12:05:35.902   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
07-28 12:05:35.902   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
07-28 12:05:35.902   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884368
07-28 12:05:35.902   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-28 12:05:35.902   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884768
07-28 12:05:35.902   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-28 12:05:35.902   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884848
07-28 12:05:35.902   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-28 12:05:35.902   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884928
07-28 12:05:35.902   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-28 12:05:35.902   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
07-28 12:05:35.902   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
07-28 12:05:35.902   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
07-28 12:05:35.902   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
07-28 12:05:35.903   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
07-28 12:05:35.903   329  8116 V OMXCodec: allocateBuffersOnPort portIndex=1
07-28 12:05:35.903   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
07-28 12:05:35.903   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
07-28 12:05:35.903   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
07-28 12:05:35.903   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f78d0 on output port
07-28 12:05:35.903   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000fa10 on output port
07-28 12:05:35.903   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
07-28 12:05:35.903   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
07-28 12:05:35.904  8094  8094 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
07-28 12:05:35.904   329  2215 V AudioCache: open(48000, 2, 0x0, 1, 4)
07-28 12:05:35.906   329  2215 V AudioCache: notify(0xb16a6040, 6, 0, 0)
07-28 12:05:35.906   329  2215 V AudioCache: ignored
07-28 12:05:35.906   329  2215 V MediaPlayerService: wait for playback complete
07-28 12:05:35.907   329  8119 V AudioCache: write(0xb17fd000, 4096)
07-28 12:05:35.907   329  8119 V AudioCache: memcpy(0xb046e000, 0xb17fd000, 4096)
07-28 12:05:35.911   329  8119 V AudioCache: write(0xb17fd000, 4096)
07-28 12:05:35.911   329  8119 V AudioCache: memcpy(0xb046f000, 0xb17fd000, 4096)
07-28 12:05:35.912   329  8119 V AudioCache: write(0xb17fd000, 4096)
07-28 12:05:35.912   329  8119 V AudioCache: memcpy(0xb0470000, 0xb17fd000, 4096)
07-28 12:05:35.912   329  8119 V AudioCache: write(0xb17fd000, 4096)
07-28 12:05:35.912   329  8119 V AudioCache: memcpy(0xb0471000, 0xb17fd000, 4096)
07-28 12:05:35.913   329  8119 V AudioCache: write(0xb17fd000, 4096)
07-28 12:05:35.913   329  8119 V AudioCache: memcpy(0xb0472000, 0xb17fd000, 4096)
07-28 12:05:35.914   329  8119 V AudioCache: write(0xb17fd000, 4096)
07-28 12:05:35.914   329  8119 V AudioCache: memcpy(0xb0473000, 0xb17fd000, 4096)
07-28 12:05:35.915   329  8119 V AudioCache: write(0xb17fd000, 4096)
07-28 12:05:35.915   329  8119 V AudioCache: memcpy(0xb0474000, 0xb17fd000, 4096)
07-28 12:05:35.915   329  8119 V AudioCache: write(0xb17fd000, 4096)
07-28 12:05:35.915   329  8119 V AudioCache: memcpy(0xb0475000, 0xb17fd000, 4096)
07-28 12:05:35.916   329  8119 V AudioCache: write(0xb17fd000, 4096)
07-28 12:05:35.916   329  8119 V AudioCache: memcpy(0xb0476000, 0xb17fd000, 4096)
07-28 12:05:35.917   329  8119 V AudioCache: write(0xb17fd000, 4096)
07-28 12:05:35.917   329  8119 V AudioCache: memcpy(0xb0477000, 0xb17fd000, 4096)
07-28 12:05:35.918   329  8119 V AudioCache: write(0xb17fd000, 4096)
07-28 12:05:35.918   329  8119 V AudioCache: memcpy(0xb0478000, 0xb17fd000, 4096)
07-28 12:05:35.919   329  8119 V AudioCache: write(0xb17fd000, 4096)
07-28 12:05:35.919   329  8119 V AudioCache: memcpy(0xb0479000, 0xb17fd000, 4096)
07-28 12:05:35.920   329  8119 V AudioCache: write(0xb17fd000, 4096)
07-28 12:05:35.920   329  8119 V AudioCache: memcpy(0xb047a000, 0xb17fd000, 4096)
07-28 12:05:35.920   329  8119 V AudioCache: write(0xb17fd000, 4096)
07-28 12:05:35.920   329  8119 V AudioCache: memcpy(0xb047b000, 0xb17fd000, 4096)
07-28 12:05:35.921   329  8119 V AudioCache: write(0xb17fd000, 4096)
07-28 12:05:35.921   329  8119 V AudioCache: memcpy(0xb047c000, 0xb17fd000, 4096)
07-28 12:05:35.921   329  8119 V AudioCache: write(0xb17fd000, 4096)
07-28 12:05:35.921   329  8119 V AudioCache: memcpy(0xb047d000, 0xb17fd000, 4096)
07-28 12:05:35.922   329  8119 V AudioCache: write(0xb17fd000, 4096)
07-28 12:05:35.922   329  8119 V AudioCache: memcpy(0xb047e000, 0xb17fd000, 4096)
07-28 12:05:35.923   329  8119 V AudioCache: write(0xb17fd000, 4096)
07-28 12:05:35.923   329  8119 V AudioCache: memcpy(0xb047f000, 0xb17fd000, 4096)
07-28 12:05:35.924   329  8119 V AudioCache: write(0xb17fd000, 4096)
07-28 12:05:35.924   329  8119 V AudioCache: memcpy(0xb0480000, 0xb17fd000, 4096)
07-28 12:05:35.925   329  8119 V AudioCache: write(0xb17fd000, 4096)
07-28 12:05:35.925   329  8119 V AudioCache: memcpy(0xb0481000, 0xb17fd000, 4096)
07-28 12:05:35.925   329  8119 V AudioCache: write(0xb17fd000, 4096)
07-28 12:05:35.925   329  8119 V AudioCache: memcpy(0xb0482000, 0xb17fd000, 4096)
07-28 12:05:35.926   329  8119 V AudioCache: write(0xb17fd000, 4096)
07-28 12:05:35.926   329  8119 V AudioCache: memcpy(0xb0483000, 0xb17fd000, 4096)
07-28 12:05:35.927   329  8119 V AudioCache: write(0xb17fd000, 4096)
07-28 12:05:35.927   329  8119 V AudioCache: memcpy(0xb0484000, 0xb17fd000, 4096)
07-28 12:05:35.927   329  8119 V AudioCache: write(0xb17fd000, 4096)
07-28 12:05:35.927   329  8119 V AudioCache: memcpy(0xb0485000, 0xb17fd000, 4096)
07-28 12:05:35.928   329  8119 V AudioCache: write(0xb17fd000, 4096)
07-28 12:05:35.928   329  8119 V AudioCache: memcpy(0xb0486000, 0xb17fd000, 4096)
07-28 12:05:35.929   329  8119 V AudioCache: write(0xb17fd000, 4096)
07-28 12:05:35.929   329  8119 V AudioCache: memcpy(0xb0487000, 0xb17fd000, 4096)
07-28 12:05:35.929  1032  1092 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
07-28 12:05:35.929   329  8119 V AudioCache: write(0xb17fd000, 4096)
07-28 12:05:35.929   329  8119 V AudioCache: memcpy(0xb0488000, 0xb17fd000, 4096)
07-28 12:05:35.929  1032  1092 I ActivityManager: Killing 6524:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
07-28 12:05:35.930   329  8119 V AudioCache: write(0xb17fd000, 4096)
07-28 12:05:35.930   329  8119 V AudioCache: memcpy(0xb0489000, 0xb17fd000, 4096)
07-28 12:05:35.931   329  8119 V AudioCache: write(0xb17fd000, 4096)
07-28 12:05:35.931   329  8119 V AudioCache: memcpy(0xb048a000, 0xb17fd000, 4096)
07-28 12:05:35.931   329  8119 V AudioCache: write(0xb17fd000, 4096)
07-28 12:05:35.931   329  8119 V AudioCache: memcpy(0xb048b000, 0xb17fd000, 4096)
07-28 12:05:35.931   329  8119 V AudioCache: write(0xb17fd000, 4096)
07-28 12:05:35.931   329  8119 V AudioCache: memcpy(0xb048c000, 0xb17fd000, 4096)
07-28 12:05:35.931   329  8119 V AudioCache: write(0xb17fd000, 4096)
07-28 12:05:35.931   329  8119 V AudioCache: memcpy(0xb048d000, 0xb17fd000, 4096)
07-28 12:05:35.933   329  8119 V AudioCache: write(0xb17fd000, 4096)
07-28 12:05:35.933   329  8119 V AudioCache: memcpy(0xb048e000, 0xb17fd000, 4096)
07-28 12:05:35.933   329  8119 V AudioCache: write(0xb17fd000, 4096)
07-28 12:05:35.933   329  8119 V AudioCache: memcpy(0xb048f000, 0xb17fd000, 4096)
,07-28 12:05:35.933   329  8119 V AudioCache: write(0xb17fd000, 4096)
07-28 12:05:35.933   329  8119 V AudioCache: memcpy(0xb0490000, 0xb17fd000, 4096)
07-28 12:05:35.933   329  8119 V AudioCache: write(0xb17fd000, 4096)
07-28 12:05:35.933   329  8119 V AudioCache: memcpy(0xb0491000, 0xb17fd000, 4096)
07-28 12:05:35.935   329  8119 V AudioCache: write(0xb17fd000, 4096)
07-28 12:05:35.935   329  8119 V AudioCache: memcpy(0xb0492000, 0xb17fd000, 4096)
07-28 12:05:35.935   329  8119 V AudioCache: write(0xb17fd000, 4096)
07-28 12:05:35.935   329  8119 V AudioCache: memcpy(0xb0493000, 0xb17fd000, 4096)
07-28 12:05:35.935   329  8119 V AudioCache: write(0xb17fd000, 4096)
07-28 12:05:35.935   329  8119 V AudioCache: memcpy(0xb0494000, 0xb17fd000, 4096)
07-28 12:05:35.936   329  8119 V AudioCache: write(0xb17fd000, 4096)
07-28 12:05:35.936   329  8119 V AudioCache: memcpy(0xb0495000, 0xb17fd000, 4096)
07-28 12:05:35.938   329  8119 V AudioCache: write(0xb17fd000, 4096)
07-28 12:05:35.938   329  8119 V AudioCache: memcpy(0xb0496000, 0xb17fd000, 4096)
07-28 12:05:35.938   329  8119 V AudioCache: write(0xb17fd000, 4096)
07-28 12:05:35.938   329  8119 V AudioCache: memcpy(0xb0497000, 0xb17fd000, 4096)
07-28 12:05:35.938   329  8119 V AudioCache: write(0xb17fd000, 4096)
07-28 12:05:35.938   329  8119 V AudioCache: memcpy(0xb0498000, 0xb17fd000, 4096)
07-28 12:05:35.939   329  8119 V AudioCache: write(0xb17fd000, 4096)
07-28 12:05:35.939   329  8119 V AudioCache: memcpy(0xb0499000, 0xb17fd000, 4096)
07-28 12:05:35.939   329  8119 V AudioCache: write(0xb17fd000, 4096)
07-28 12:05:35.939   329  8119 V AudioCache: memcpy(0xb049a000, 0xb17fd000, 4096)
07-28 12:05:35.940   329  8119 V AudioCache: write(0xb17fd000, 4096)
07-28 12:05:35.940   329  8119 V AudioCache: memcpy(0xb049b000, 0xb17fd000, 4096)
07-28 12:05:35.940   329  8119 V AudioCache: write(0xb17fd000, 4096)
07-28 12:05:35.942   329  8119 V AudioCache: memcpy(0xb049c000, 0xb17fd000, 4096)
07-28 12:05:35.943   329  8119 V AudioCache: write(0xb17fd000, 4096)
07-28 12:05:35.943   329  8119 V AudioCache: memcpy(0xb049d000, 0xb17fd000, 4096)
07-28 12:05:35.943   329  8119 V AudioCache: write(0xb17fd000, 4096)
07-28 12:05:35.943   329  8119 V AudioCache: memcpy(0xb049e000, 0xb17fd000, 4096)
07-28 12:05:35.944   329  8119 V AudioCache: write(0xb17fd000, 4096)
07-28 12:05:35.944   329  8119 V AudioCache: memcpy(0xb049f000, 0xb17fd000, 4096)
07-28 12:05:35.944   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
07-28 12:05:35.944   329  8119 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
07-28 12:05:35.944   329  8119 V AwesomePlayer: postAudioEOS() 
07-28 12:05:35.944   329  8119 V AudioCache: write(0xb17fd000, 280)
07-28 12:05:35.944   329  8119 V AudioCache: memcpy(0xb04a0000, 0xb17fd000, 280)
07-28 12:05:35.946   329  8114 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
07-28 12:05:35.946   329  8114 V AwesomePlayer: onStreamDone
07-28 12:05:35.946   329  8114 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
07-28 12:05:35.946   329  8114 V AudioCache: notify(0xb16a6040, 2, 0, 0)
07-28 12:05:35.946   329  8114 V AudioCache: playback complete
07-28 12:05:35.946   329  8114 V AwesomePlayer: pause_l() 
07-28 12:05:35.946   329  2215 V AudioCache: wait - success
07-28 12:05:35.946   329  8114 V AudioCache: notify(0xb16a6040, 7, 0, 0)
07-28 12:05:35.946   329  2215 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
07-28 12:05:35.946   329  8114 V AudioCache: ignored
07-28 12:05:35.946   329  8114 V AwesomePlayer: cancelPlayerEvents
07-28 12:05:35.946   329  8114 D AudioPlayer: Pause Playback at 1068125
07-28 12:05:35.946   329  2215 V AwesomePlayer: reset_l() 
07-28 12:05:35.946   329  2215 V AudioCache: notify(0xb16a6040, 8, 0, 0)
07-28 12:05:35.946   329  2215 V AudioCache: ignored
07-28 12:05:35.946   329  2215 V AwesomePlayer: cancelPlayerEvents
07-28 12:05:35.946   329  2215 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
07-28 12:05:35.946   329  2215 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
07-28 12:05:35.946   329  2215 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
07-28 12:05:35.946   329  2215 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
07-28 12:05:35.946   329  2215 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
07-28 12:05:35.946   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
07-28 12:05:35.946   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
07-28 12:05:35.946   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
07-28 12:05:35.946   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7830 on port 0
07-28 12:05:35.946   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
07-28 12:05:35.946   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f77e0 on port 0
07-28 12:05:35.946   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
07-28 12:05:35.946   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7790 on port 0
07-28 12:05:35.947   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
07-28 12:05:35.947   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7650 on port 0
07-28 12:05:35.947   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
07-28 12:05:35.947   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
07-28 12:05:35.947   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb000fa10 on port 1
07-28 12:05:35.947   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
07-28 12:05:35.947   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f78d0 on port 1
07-28 12:05:35.947   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
07-28 12:05:35.947   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 1
07-28 12:05:35.947   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
07-28 12:05:35.947   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 1
07-28 12:05:35.947   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-28 12:05:35.947   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
07-28 12:05:35.947   329  2215 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
07-28 12:05:35.947   329  2215 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
07-28 12:05:35.947   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
07-28 12:05:35.947   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
07-28 12:05:35.947   329  8116 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
07-28 12:05:35.947   329  2215 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
07-28 12:05:35.947   329  2215 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
07-28 12:05:35.947   329  2215 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
07-28 12:05:35.947   329  2215 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
07-28 12:05:35.948   329  2215 D AudioPlayer: AudioPlayer releasing audio source
07-28 12:05:35.948   329  2215 D AudioPlayer: AudioPlayer done releasing audio source
07-28 12:05:35.948   329  2215 V AwesomePlayer: reset_l() 
07-28 12:05:35.948   329  2215 V AwesomePlayer: cancelPlayerEvents
07-28 12:05:35.948   329  2215 V AwesomePlayer: ~AwesomePlayer call
07-28 12:05:35.948   329  2215 V AwesomePlayer: reset_l() 
07-28 12:05:35.948   329  2215 V AwesomePlayer: cancelPlayerEvents
07-28 12:05:35.948  8047  8113 V SoundPool: close(31)
07-28 12:05:35.948  8047  8113 V SoundPool: pointer = 0x9fe38000, size = 205080, sampleRate = 48000, numChannels = 2
07-28 12:05:35.958  8047  8047 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
07-28 12:05:35.959  8047  8047 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,07-28 12:05:36.011  1032  1425 W InputDispatcher: channel '14b930d8 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
07-28 12:05:36.011  1032  1425 E InputDispatcher: channel '14b930d8 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
07-28 12:05:36.012  1032  1993 I WindowState: WIN DEATH: Window{14b930d8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-28 12:05:36.012  1032  1993 W InputDispatcher: Attempted to unregister already unregistered input channel '14b930d8 com.test.thalitest/com.test.thalitest.MainActivity (server)'
07-28 12:05:36.012  1032  1544 D WifiService: Client connection lost with reason: 4
07-28 12:05:36.029  1032  1993 D InputDispatcher: Window went away: Window{14b930d8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,07-28 12:05:36.032  1032  1092 I ActivityManager:   Force finishing activity ActivityRecord{26d2bcd5 u0 com.test.thalitest/.MainActivity t40}
,07-28 12:05:36.047   345   357 E GBMv2   : DFP En is all cleared set to be enabled
07-28 12:05:36.048  1032  1939 W ActivityManager: Spurious death for ProcessRecord{b709be6 6524:com.test.thalitest/u0a118}, curProc for 6524: null
07-28 12:05:36.052  1032  1106 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
07-28 12:05:36.056  1032  1106 I ActivityManager:   Force finishing activity ActivityRecord{26d2bcd5 u0 com.test.thalitest/.MainActivity t40 f}
,07-28 12:05:36.057  1032  1106 W ActivityManager: Duplicate finish request for ActivityRecord{26d2bcd5 u0 com.test.thalitest/.MainActivity t40 f}
07-28 12:05:36.068  1940  1955 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
,07-28 12:05:36.069  1940  1955 D SplitWindowPolicy: topRunningActivity=ActivityInfo{195ce353 co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
07-28 12:05:36.069  2033  2033 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
07-28 12:05:36.070  1940  6337 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
07-28 12:05:36.070  1940  6337 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3f024490 co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
07-28 12:05:36.070  2033  2033 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
07-28 12:05:36.074  1602  1602 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
07-28 12:05:36.075  8047  8047 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:3763
07-28 12:05:36.077  3829  3829 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
07-28 12:05:36.077  1996  1996 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
07-28 12:05:36.080  7574  7574 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
07-28 12:05:36.080  7574  7574 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
07-28 12:05:36.087  1032  1426 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-28 12:05:36.090  2455  2623 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-28 12:05:36.099  4480  4480 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-28 12:05:36.099  4480  4480 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
07-28 12:05:36.099  4480  4480 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
07-28 12:05:36.099  4480  4480 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
07-28 12:05:36.099  4480  4480 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-28 12:05:36.099  4480  4480 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-28 12:05:36.099  4480  4480 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-28 12:05:36.099  4480  4480 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-28 12:05:36.099  4480  4480 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:05:36.099  4480  4480 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:05:36.099  4480  4480 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-28 12:05:36.099  4480  4480 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,07-28 12:05:36.114  1032  1939 V SIM_STK : Menu title from STK is T-Mobile
07-28 12:05:36.136  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
,07-28 12:05:36.138  2033  2147 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
07-28 12:05:36.138  4595  4595 I art     : Explicit concurrent mark sweep GC freed 8214(470KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 370us total 59.314ms
07-28 12:05:36.156  1602  1602 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,07-28 12:05:36.157  8005  8005 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:05:36.164  1032  1091 W InputMethodInfo: Duplicated subtype definition found: , voice
07-28 12:05:36.170  1602  1602 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
,07-28 12:05:36.170  1602  1602 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
07-28 12:05:36.181  1032  1032 D administrator: Handling package changes for user 0
07-28 12:05:36.188  1868  1868 D SplitUIManager: split_name #11 / not available #0
,07-28 12:05:36.188  1868  1868 D SplitUIService: removed split : 
07-28 12:05:36.202  1904  1904 D ActionManagerService: notifyUserLog: 1000003
07-28 12:05:36.202  2033  2033 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
,07-28 12:05:36.202  3829  4474 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
07-28 12:05:36.203  2033  2033 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
07-28 12:05:36.203  1602  1654 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
07-28 12:05:36.204  1602  1654 D KeyguardModel: createShortcutInfo...
07-28 12:05:36.204  2033  2033 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
07-28 12:05:36.205  2033  2033 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
07-28 12:05:36.207  8005  8005 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:05:36.210  2033  2033 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
07-28 12:05:36.210  1602  1654 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
07-28 12:05:36.210  1602  1654 D KeyguardModel: createShortcutInfo...
07-28 12:05:36.210  1904  1904 D ActionManagerService: notifyUserLog: 1000004
07-28 12:05:36.211  3829  4474 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
07-28 12:05:36.214  1602  1654 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
07-28 12:05:36.215  1602  1654 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-28 12:05:36.215  1602  1654 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
07-28 12:05:36.216  1602  1654 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
07-28 12:05:36.217  1602  1654 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-28 12:05:36.217  1602  1654 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
07-28 12:05:36.218  8005  8005 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-28 12:05:36.219  3829  4472 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
07-28 12:05:36.220  1602  1654 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
07-28 12:05:36.220  1602  1654 D KeyguardModel: createShortcutInfo...
07-28 12:05:36.221  1868  1868 D SplitUIManager: split_name #11 / not available #0
07-28 12:05:36.221  1868  1868 I SplitUIService: split app #11
07-28 12:05:36.224  1602  1654 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
07-28 12:05:36.224  1602  1654 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-28 12:05:36.224  1602  1654 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-28 12:05:36.225  1602  1654 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
07-28 12:05:36.225  8005  8005 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:05:36.229  2033  2033 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
07-28 12:05:36.229  2033  2033 I GBoardWebViewUtils: , create_time: 1430832262123
07-28 12:05:36.229  2033  2033 I GBoardWebViewUtils: , expire_time: 0
07-28 12:05:36.229  2033  2033 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
07-28 12:05:36.229  2033  2033 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
07-28 12:05:36.229  2033  2033 I GBoardWebViewUtils: , display: false
07-28 12:05:36.229  2033  2033 I GBoardWebViewUtils: , animation: false }
07-28 12:05:36.229  2033  2033 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
07-28 12:05:36.229  2033  2033 I GBoardWebViewUtils: , create_time: 1430832262287
07-28 12:05:36.229  2033  2033 I GBoardWebViewUtils: , expire_time: 0
07-28 12:05:36.229  2033  2033 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
07-28 12:05:36.229  2033  2033 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
07-28 12:05:36.229  2033  2033 I GBoardWebViewUtils: , display: false
07-28 12:05:36.229  2033  2033 I GBoardWebViewUtils: , animation: false }
07-28 12:05:36.229  2033  2033 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1469186101390
07-28 12:05:36.229  2033  2033 I GBoardWebViewUtils: , create_time: 1469186101943
07-28 12:05:36.229  2033  2033 I GBoardWebViewUtils: , expire_time: 0
07-28 12:05:36.229  2033  2033 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1469186101390&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
07-28 12:05:36.229  2033  2033 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
07-28 12:05:36.229  2033  2033 I GBoardWebViewUtils: , display: false
07-28 12:05:36.229  2033  2033 I GBoardWebViewUtils: , animation: false }
07-28 12:05:36.229  1602  1654 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
07-28 12:05:36.229  1602  1654 D KeyguardModel: createShortcutInfo...
07-28 12:05:36.233  1602  1654 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-28 12:05:36.233  1602  1654 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-28 12:05:36.233  1602  1654 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
07-28 12:05:,36.233  1602  1654 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
07-28 12:05:36.237  1602  1654 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-28 12:05:36.237  1602  1654 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
07-28 12:05:36.238  1602  1654 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
07-28 12:05:36.239  1602  1654 D KeyguardModel: createShortcutInfo...
07-28 12:05:36.241  2033  8122 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
07-28 12:05:36.244  1602  1602 D KeyguardModel: handleShortcutListChanged...
07-28 12:05:36.244  1602  1602 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
07-28 12:05:36.244  8005  8005 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-28 12:05:36.250  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-28 12:05:36.250  2033  2033 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
07-28 12:05:36.251  1602  1654 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
07-28 12:05:36.251  1602  1654 D KeyguardModel: createShortcutInfo...
07-28 12:05:36.255  1602  1654 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
07-28 12:05:36.255  1602  1654 D KeyguardModel: createShortcutInfo...
07-28 12:05:36.256  1602  1654 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-28 12:05:36.256  1602  1654 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
07-28 12:05:36.257  1602  1654 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
07-28 12:05:36.257  1602  1654 D KeyguardModel: createShortcutInfo...
07-28 12:05:36.258  1602  1654 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-28 12:05:36.258  1602  1654 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
07-28 12:05:36.259  1602  1654 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
07-28 12:05:36.259  1602  1654 D KeyguardModel: createShortcutInfo...
07-28 12:05:36.260  1602  1654 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-28 12:05:36.260  1602  1654 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
07-28 12:05:36.261  1032  2051 V SIM_STK : Menu title from STK is T-Mobile
07-28 12:05:36.261  1032  2051 V SIM_STK : Menu title from STK is T-Mobile
07-28 12:05:36.261  1602  1654 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
07-28 12:05:36.261  1602  1654 D KeyguardModel: createShortcutInfo...
,07-28 12:05:36.273  8005  8005 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:05:36.284  7491  7491 I UEI.SmartControl: Supports setup maps: true
,07-28 12:05:36.286  1032  1993 V SIM_STK : Menu title from STK is T-Mobile
07-28 12:05:36.286  7491  7491 D UEI.SmartControl: QS start statue = true Error code = 0
07-28 12:05:36.286  7491  7491 I UEI.SmartControl: QS version = v2.7.10.1_RC1
07-28 12:05:36.286  7491  7491 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
07-28 12:05:36.286  7491  7491 I UEI.SmartControl: ### init IR Blaster...
07-28 12:05:36.290  8005  8005 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:05:36.292  8005  8005 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:05:36.294  8005  8005 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:05:36.296  8005  8005 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:05:36.298  8005  8005 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,07-28 12:05:36.300  1816  1816 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
07-28 12:05:36.306  2126  2126 I ConfigService: onCreate
07-28 12:05:36.306  2126  2126 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
07-28 12:05:36.310  1816  1816 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,07-28 12:05:36.327  2126  2126 I ConfigService: onBind returning update interface
07-28 12:05:36.329  1602  1602 D KeyguardModel: handleShortcutListChanged...
07-28 12:05:36.329  1602  1602 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,07-28 12:05:36.331  7491  7491 D serial_port: Configuring serial port
07-28 12:05:36.332  7491  7491 E UEI.SmartControl: UEIBLaster setting for 616
07-28 12:05:36.332  7491  7491 I UEI.SmartControl: Setting serial record hearder size = 2
07-28 12:05:36.332  7491  7491 I UEI.SmartControl: configuring settings for MAXQ616
07-28 12:05:36.332  7491  7491 I UEI.SmartControl: Get version...
07-28 12:05:36.335  2126  2126 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
07-28 12:05:36.335  2126  2126 I ConfigService: onBind returning config service
07-28 12:05:36.335  2033  2033 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
07-28 12:05:36.337  1032  2051 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
07-28 12:05:36.337  7574  7574 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
07-28 12:05:36.337  7574  7574 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
07-28 12:05:36.337  7574  7574 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
07-28 12:05:36.337  7574  7574 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
07-28 12:05:36.337  7574  7574 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
07-28 12:05:36.337  7574  7574 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-28 12:05:36.337  7574  7574 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
07-28 12:05:36.337  7574  7574 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
07-28 12:05:36.338  7574  7574 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
07-28 12:05:36.338  7574  7574 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-28 12:05:36.338  7574  7574 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
07-28 12:05:36.347  2126  2126 I ConfigService: onDestroy
,07-28 12:05:36.349  1816  8126 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
07-28 12:05:36.351  7491  8125 D UEI.SmartControl: serial port data available: 21
,07-28 12:05:36.373  6003  8131 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,07-28 12:05:36.382  7491  7491 D UEI.SmartControl: MAXQ616 A2-X4 software.
07-28 12:05:36.382  7491  7491 I UEI.SmartControl: IR Blaster version: 256702256704300002
07-28 12:05:36.382  7491  7491 I UEI.SmartControl: QS saving settings...
07-28 12:05:36.382  1816  8133 I PeopleContactsSync: CP2 sync disabled
07-28 12:05:36.384  7491  7491 D UEI.SmartControl: IR Blaster version: 25672567
07-28 12:05:36.390  1032  1032 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
,07-28 12:05:36.390  1032  1032 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-28 12:05:36.391  1032  1032 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-28 12:05:36.391   338   422 I ThermalEngine: Thermal-Server: Thermal received msg from  override
07-28 12:05:36.391  3207  8135 I Thermal-Lib: Thermal-Lib-Client: Client request sent
07-28 12:05:36.393  1032  1577 D TaskPersister: removeObsoleteFile: deleting file=40_task.xml
07-28 12:05:36.394  1816  4756 I Icing   : doRemovePackageData com.test.thalitest
07-28 12:05:36.399  7491  8125 D UEI.SmartControl: serial port data available: 4
07-28 12:05:36.403  6920  6920 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,07-28 12:05:36.410  1816  8132 W GmsApplication: Using Auth Proxy for data requests.
07-28 12:05:36.417  1816  8132 W GmsApplication: Using Auth Proxy for data requests.
,07-28 12:05:36.427  7491  8140 I UEI.SmartControl: Device manager: loading config....
07-28 12:05:36.428  7491  8140 D UEI.SmartControl: ----------- loading internal config...
07-28 12:05:36.426  7491  7491 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,07-28 12:05:36.429  2367  8138 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
07-28 12:05:36.431  7491  8140 E UEI.SmartControl: Loading SETTINGS...
07-28 12:05:36.445  7491  8140 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,07-28 12:05:36.449  1032  1642 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8142 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
07-28 12:05:36.449  7491  8139 I UEI.SmartControl: Notify AllClients services are ready: 0
07-28 12:05:36.449  7491  8139 D UEI.SmartControl: -----service ready thread exits
07-28 12:05:36.452  7491  7491 E UEI.SmartControl: Services init done
07-28 12:05:36.452  7491  7491 D UEI.SmartControl: QS Service init finished
07-28 12:05:36.454  7491  7491 D UEI.SmartControl: QS Service version name: 2.1.91
07-28 12:05:36.454  7491  7491 D UEI.SmartControl: QS Service version code: 201091
07-28 12:05:36.454  7491  7491 D UEI.SmartControl: Service requested: Control
07-28 12:05:36.456  7491  7491 D UEI.SmartControl: Internal service binding...
07-28 12:05:36.459  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
07-28 12:05:36.462  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,07-28 12:05:36.464  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
07-28 12:05:36.465  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
07-28 12:05:36.466  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
07-28 12:05:36.467  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
07-28 12:05:36.482  8047  8047 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
07-28 12:05:36.483  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
07-28 12:05:36.483  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-28 12:05:36.483  7491  7507 I UEI.SmartControl: ------ IControl API: 11
07-28 12:05:36.483  7491  7507 D UEI.SmartControl: File observer start...
07-28 12:05:36.483  7491  7507 E UEI.SmartControl: IR Port is disabled: false
,07-28 12:05:36.483  7491  7507 D UEI.SmartControl: Starting file observer...
07-28 12:05:36.483  7491  7507 I UEI.SmartControl: Registering callback...
07-28 12:05:36.483  2033  2298 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
07-28 12:05:36.484  2033  2298 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
07-28 12:05:36.485  1032  1098 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{5ee5266 u0 com.lge.launcher2/.Launcher t39} time:156536
07-28 12:05:36.491  7491  7508 I UEI.SmartControl: ------ IControl API: 19
07-28 12:05:36.491  7491  7508 I UEI.SmartControl: Registering Services Ready callback...
07-28 12:05:36.491  7491  7508 I UEI.SmartControl: Notify client services are ready...
07-28 12:05:36.492  8047  8065 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
07-28 12:05:36.493  8047  8111 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
07-28 12:05:36.497  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
07-28 12:05:36.497  8047  8111 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
,07-28 12:05:36.498  8047  8047 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
07-28 12:05:36.498  8047  8047 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
07-28 12:05:36.498  7491  7507 I UEI.SmartControl: ------ IControl API: 8
07-28 12:05:36.498  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
07-28 12:05:36.498  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-28 12:05:36.502  8047  8047 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
07-28 12:05:36.503  8047  8047 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
07-28 12:05:36.503  8047  8047 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
07-28 12:05:36.503  8047  8047 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
07-28 12:05:36.506  8047  8047 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
07-28 12:05:36.506  8047  8047 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
07-28 12:05:36.507  2033  2033 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
07-28 12:05:36.507  8047  8047 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,07-28 12:05:36.508  8047  8047 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
07-28 12:05:36.508  2614  2614 D [Concierge]Service: onStartCommand(). Type : 8
07-28 12:05:36.508  2614  2614 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
07-28 12:05:36.509  2614  2614 D [Concierge]Service: Update widget ID : 11
07-28 12:05:36.510  1032  1781 I ActivityManager: Killing 7127:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
07-28 12:05:36.511  2033  2033 D [Concierge]WidgetView: change position of spinner
,07-28 12:05:36.519  8142  8142 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-28 12:05:36.519  8142  8142 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-28 12:05:36.520  8142  8142 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-28 12:05:36.520  8142  8142 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
07-28 12:05:36.525  1032  1106 I art     : Explicit concurrent mark sweep GC freed 81196(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 44MB/66MB, paused 2.721ms total 386.222ms
,07-28 12:05:36.526  1032  1091 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-28 12:05:36.549  8094  8094 D AndroidRuntime: Shutting down VM
,07-28 12:05:36.570  1032  1091 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
07-28 12:05:36.570  1032  2026 W libprocessgroup: failed to open /acct/uid_10005/pid_7127/cgroup.procs: No such file or directory
07-28 12:05:36.570  2614  2614 D [Concierge]Service: onStartCommand(). Type : 0
,07-28 12:05:36.571  2033  2033 I [Concierge]WidgetView: initWebView(). Time : 1469700336570
07-28 12:05:36.573  8142  8142 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
07-28 12:05:36.581  8142  8142 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
07-28 12:05:36.584  2033  2033 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 508365131
,07-28 12:05:36.585  2033  2033 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
07-28 12:05:36.585  2033  2033 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
07-28 12:05:36.587  2033  2033 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@212da8cb
07-28 12:05:36.587  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
07-28 12:05:36.589  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
07-28 12:05:36.589  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-28 12:05:36.590  2126  2795 I art     : Explicit concurrent mark sweep GC freed 4857(293KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 866us total 16.031ms
07-28 12:05:36.594  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
07-28 12:05:36.594  2033  2033 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
07-28 12:05:36.594  2033  2033 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
07-28 12:05:36.595  2033  2033 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1469700208555, New one : 1469700336570
07-28 12:05:36.595  2033  2033 D [Concierge]WidgetView: Unregister all receivers
07-28 12:05:36.595  2033  2033 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
07-28 12:05:36.595  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
07-28 12:05:36.597  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-28 12:05:36.599  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
07-28 12:05:36.600  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
07-28 12:05:36.601  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
07-28 12:05:36.602  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
07-28 12:05:36.603  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
,07-28 12:05:36.606  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-28 12:05:36.606  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-28 12:05:36.609  8142  8142 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-28 12:05:36.630  8142  8142 D LgDataFeature: LgDataFeature() Constructor: none
,07-28 12:05:36.630  8142  8142 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-28 12:05:36.639  2033  2033 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
07-28 12:05:36.647  2033  2033 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
07-28 12:05:36.647  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
07-28 12:05:36.649  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,07-28 12:05:36.668  2033  2033 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@29cef9c4 time:156719
,07-28 12:05:36.691  8142  8142 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,07-28 12:05:36.699  1032  2037 I ActivityManager: Killing 7603:com.google.android.talk/u0a72 (adj 15): empty #17
,07-28 12:05:36.778  2033  2033 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,07-28 12:05:36.813  2033  2930 I GBoardtInterface: onReloaded()
,07-28 12:05:36.815  2033  2033 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
07-28 12:05:36.821  1996  1996 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
07-28 12:05:36.821  1996  1996 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
07-28 12:05:36.822  1032  1975 W libprocessgroup: failed to open /acct/uid_10072/pid_7603/cgroup.procs: No such file or directory
07-28 12:05:36.852  1032  1106 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8167 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,07-28 12:05:36.854  3829  4472 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
07-28 12:05:36.854  1996  1996 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
07-28 12:05:36.857  3829  3847 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
07-28 12:05:36.858  8005  8005 E SQLiteDatabase: Failed to open database '/data/data/com.wsandroid.suite.lge/databases/CLOUDREPUTATIONDB'.
07-28 12:05:36.858  8005  8005 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-28 12:05:36.858  8005  8005 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-28 12:05:36.858  8005  8005 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
07-28 12:05:36.858  8005  8005 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
07-28 12:05:36.858  8005  8005 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-28 12:05:36.858  8005  8005 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-28 12:05:36.858  8005  8005 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-28 12:05:36.858  8005  8005 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
07-28 12:05:36.858  8005  8005 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
07-28 12:05:36.858  8005  8005 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
07-28 12:05:36.858  8005  8005 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
07-28 12:05:36.858  8005  8005 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-28 12:05:36.858  8005  8005 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-28 12:05:36.858  8005  8005 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-28 12:05:36.858  8005  8005 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.i.a(Unknown Source)
07-28 12:05:36.858  8005  8005 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.ad.a(Unknown Source)
07-28 12:05:36.858  8005  8005 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.ab.j(Unknown Source)
07-28 12:05:36.858  8005  8005 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.k.b(Unknown Source)
07-28 12:05:36.858  8005  8005 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.k.a(Unknown Source)
07-28 12:05:36.858  8005  8005 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.CloudScanReceiver.onReceive(Unknown Source)
07-28 12:05:36.858  8005  8005 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2586)
07-28 12:05:36.858  8005  8005 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
07-28 12:05:36.858  8005  8005 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1360)
07-28 12:05:36.858  8005  8005 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:05:36.858  8005  8005 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
07-28 12:05:36.858  8005  8005 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-28 12:05:36.858  8005  8005 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:05:36.858  8005  8005 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:05:36.858  8005  8005 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.j,ava:909)
07-28 12:05:36.858  8005  8005 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-28 12:05:36.860  8005  8005 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
07-28 12:05:36.864  1904  1904 D ActionManagerService: notifyUserLog: 1000001
,07-28 12:05:36.866  3829  4474 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
07-28 12:05:36.866  3829  4474 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
07-28 12:05:36.869  1904  1904 D ActionManagerService: notifyUserLog: 1000001
07-28 12:05:36.870  3829  4474 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
07-28 12:05:36.870  3829  4474 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
07-28 12:05:36.870  3829  4474 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
07-28 12:05:36.870  7365  7365 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
07-28 12:05:36.870  3829  4474 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
07-28 12:05:36.871  3829  4472 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
07-28 12:05:36.873  2033  2033 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
07-28 12:05:36.873  2033  2033 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
07-28 12:05:36.873  6720  6720 D PackageIntentReceiver: Not supported Hotkey customization function 
07-28 12:05:36.875  2033  2033 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
07-28 12:05:36.876  2033  2033 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
07-28 12:05:36.878  2033  2033 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1469186101390&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
07-28 12:05:36.878  2033  2033 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1469186101390&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,07-28 12:05:36.880  6720  6720 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
07-28 12:05:36.880  6720  6720 D HideNavigationAppsReceiver: replacing : false
07-28 12:05:36.887  6720  6720 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
07-28 12:05:36.889  6720  6720 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
07-28 12:05:36.889  6720  6720 D ButtonCombinationReceiver: replacing : false
,07-28 12:05:36.905  4595  8187 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
07-28 12:05:36.925  1032  1048 V SIM_STK : Menu title from STK is T-Mobile
,07-28 12:05:36.934  1032  1047 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=8188 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-28 12:05:36.935  4595  8187 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
07-28 12:05:36.937  1032  1939 I ActivityManager: Killing 7185:com.google.android.apps.plus/u0a97 (adj 15): empty #17

```
