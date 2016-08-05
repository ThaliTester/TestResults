#### Test 794266509fa1f7f_thali05_LGE-LG-D855 Logs


```
--------- beginning of main
08-05 02:10:09.417  6481  6481 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
08-05 02:10:09.996  1590  1590 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-05 02:10:09.996  1590  1590 I [SystemUI]LGPowerUI: On Skip Timer : true
08-05 02:10:10.011  1590  1590 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 288
08-05 02:10:10.011  1590  1590 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
--------- beginning of system
08-05 02:10:10.012  1962  2143 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-05 02:10:10.013  1045  1045 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 02:10:10.013  1045  1045 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 02:10:10.015  1045  1532 D WifiController: battery changed pluggedType: 2
08-05 02:10:10.016  3842  3981 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-05 02:10:10.013  1962  2143 D LEDHandler: Battery Level Remaining: 100%
08-05 02:10:10.017  1962  2143 D LEDHandler: Battery Temp: 288, mChargingStatus=5, mChargingStop=false
08-05 02:10:10.018  1590  1590 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-05 02:10:10.210  1830  4762 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
08-05 02:10:10.255  1830  4762 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-05 02:10:10.310  1830  4762 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
,08-05 02:10:10.622  2155  2155 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19996
08-05 02:10:10.839  6515  6515 D AndroidRuntime: 
08-05 02:10:10.839  6515  6515 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-05 02:10:10.839  6481  6481 D LgDataFeature: LgDataFeature() Constructor: none
08-05 02:10:10.840  6481  6481 D LgDataFeature: LgDataFeature() Constructor Done, null
08-05 02:10:10.842  6515  6515 D AndroidRuntime: CheckJNI is OFF
08-05 02:10:10.948  6515  6515 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-05 02:10:10.958  1045  2043 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-05 02:10:10.969  1962  2507 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-05 02:10:10.971  1045  2043 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-05 02:10:10.972  1045  2043 D ActivityManager: setTaskToReturnTo : TaskRecord{14f7b10 #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-05 02:10:10.972  1045  2043 D ActivityManager: setTaskToReturnTo : TaskRecord{14f7b10 #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-05 02:10:10.973  1045  2043 D WindowStateEx: AppWindowTokenEx init.. 
08-05 02:10:10.974   348   354 E GBMv2   : DFP En is all cleared set to be enabled
08-05 02:10:11.012  1045  2043 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6538 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-05 02:10:11.016  6515  6515 D AndroidRuntime: Shutting down VM
08-05 02:10:11.027  6137  6137 I LockScreenSettings: New app installed broadcast received ..
08-05 02:10:11.030  6137  6137 I LockScreenSettings: Number of installed packages  1
08-05 02:10:11.068  6481  6481 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
08-05 02:10:11.080  1962  2507 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-05 02:10:11.080  1962  2507 D SplitWindowPolicy: topRunningActivity=ActivityInfo{250751c5 co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
08-05 02:10:11.081  1962  1977 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-05 02:10:11.082  1962  1977 D SplitWindowPolicy: topRunningActivity=ActivityInfo{266071a co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
08-05 02:10:11.104  1045  1933 V SIM_STK : Menu title from STK is T-Mobile
08-05 02:10:11.159  1045  1718 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6568 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-05 02:10:11.164  6538  6538 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-05 02:10:11.234  6568  6568 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-05 02:10:11.234  6568  6568 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
08-05 02:10:11.243  6538  6538 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-05 02:10:11.294  1045  1979 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6587 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-05 02:10:11.295  1045  1979 I ActivityManager: Killing 5838:com.google.android.gm/u0a64 (adj 15): empty #17
08-05 02:10:11.331  1045  2102 W libprocessgroup: failed to open /acct/uid_10064/pid_5838/cgroup.procs: No such file or directory
08-05 02:10:11.341  6538  6538 I LibraryLoader: Loading: webviewchromium
08-05 02:10:11.346  6538  6538 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 7209-7215)
08-05 02:10:11.346  6538  6538 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-05 02:10:11.381  6587  6587 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
08-05 02:10:11.384  6538  6538 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2106b4bb}
08-05 02:10:11.386  6538  6538 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-05 02:10:11.386  6538  6538 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-05 02:10:11.395  6587  6587 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-05 02:10:11.400  6360  6360 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-05 02:10:11.402  6538  6538 I BrowserStartupController: Initializing chromium process, renderers=0
08-05 02:10:11.403  6538  6538 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-05 02:10:11.417   329  1369 V AudioPolicyService: registerClient() client 0xb558a8c0, uid 10118
08-05 02:10:11.418  6538  6538 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-05 02:10:11.418  6538  6538 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-05 02:10:11.419  6538  6538 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-05 02:10:11.420  1045  1979 I ActivityManager: Killing 5883:com.google.android.talk/u0a72 (adj 15): empty #17
08-05 02:10:11.424  1045  1181 D BluetoothManagerService: Message: 20
08-05 02:10:11.424  1045  1181 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@208f9772:true
08-05 02:10:11.435  6538  6538 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 02:10:11.435  6538  6538 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 02:10:11.435  6538  6538 I Adreno-EGL: Build Date: 12/12/14 금
08-05 02:10:11.435  6538  6538 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-05 02:10:11.435  6538  6538 I Adreno-EGL: Remote Branch: 
08-05 02:10:11.435  6538  6538 I Adreno-EGL: Local Patches: 
08-05 02:10:11.435  6538  6538 I Adreno-EGL: Reconstruct Branch: 
08-05 02:10:11.482  1045  2101 W libprocessgroup: failed to open /acct/uid_10072/pid_5883/cgroup.procs: No such file or directory
08-05 02:10:11.540  6538  6617 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
08-05 02:10:11.543  6538  6538 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-05 02:10:11.562  6538  6538 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-05 02:10:11.568  6538  6538 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-05 02:10:11.572  6538  6538 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-05 02:10:11.575  6538  6538 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-05 02:10:11.575  6538  6538 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-05 02:10:11.577  1045  1175 W ActivityManager: Activity pause timeout for ActivityRecord{4b67609 u0 com.test.thalitest/.MainActivity t40}
08-05 02:10:11.592  6538  6538 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-05 02:10:11.601  6538  6538 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-05 02:10:11.601  6538  6538 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-05 02:10:11.646  6538  6629 D OpenGLRenderer: Render dirty regions requested: true
08-05 02:10:11.646  6538  6629 I OpenGLRenderer: Initialized EGL, version 1.4
08-05 02:10:11.652  6538  6629 D OpenGLRenderer: Enabling debug mode 0
08-05 02:10:11.664  6538  6538 D Atlas   : Validating map...
08-05 02:10:11.671  1045  1088 D SplitWindow: check instance of lgWin Window{350d849c u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-05 02:10:11.676  1045  2082 I ActivityManager: Killing 5676:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-05 02:10:11.706  5649  5649 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-05 02:10:11.708  5649  5649 W System.err: android.os.DeadObjectException
08-05 02:10:11.708  5649  5649 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-05 02:10:11.708  5649  5649 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-05 02:10:11.708  5649  5649 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-05 02:10:11.708  5649  5649 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-05 02:10:11.709  5649  5649 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-05 02:10:11.709  5649  5649 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-05 02:10:11.709  5649  5649 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-05 02:10:11.709  5649  5649 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-05 02:10:11.709  5649  5649 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-05 02:10:11.709  5649  5649 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-05 02:10:11.709  5649  5649 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 02:10:11.709  5649  5649 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 02:10:11.709  5649  5649 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-05 02:10:11.709  5649  5649 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-05 02:10:11.709  5649  5649 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-05 02:10:11.709  5649  5649 W System.err: android.os.DeadObjectException
08-05 02:10:11.710  5649  5649 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-05 02:10:11.710  5649  5649 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-05 02:10:11.710  5649  5649 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-05 02:10:11.710  5649  5649 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-05 02:10:11.710  5649  5649 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-05 02:10:11.710  5649  5649 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-05 02:10:11.710  5649  5649 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-05 02:10:11.710  5649  5649 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-05 02:10:11.710  5649  5649 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-05 02:10:11.710  5649  5649 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-05 02:10:11.710  5649  5649 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 02:10:11.710  5649  5649 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 02:10:11.710  5649  5649 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-05 02:10:11.710  5649  5649 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-05 02:10:11.710  5649  5649 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-05 02:10:11.711  5649  5649 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-05 02:10:11.718  6538  6627 D LgDataFeature: LgDataFeature() Constructor: none
08-05 02:10:11.718  6538  6627 D LgDataFeature: LgDataFeature() Constructor Done, null
08-05 02:10:11.784  1045  1087 W libprocessgroup: failed to open /acct/uid_1000/pid_5676/cgroup.procs: No such file or directory
08-05 02:10:11.785  1045  1087 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-05 02:10:11.789  5649  5649 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-05 02:10:11.790  5649  5649 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-05 02:10:11.862  1045  2025 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6638 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-05 02:10:11.863  5649  5649 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-05 02:10:11.894  1045  1182 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +816ms (total +919ms)
08-05 02:10:11.895  6538  6538 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3ef9dec6 time:117764
08-05 02:10:11.895  1045  1182 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{4b67609 u0 com.test.thalitest/.MainActivity t40} time:117764
08-05 02:10:11.937  6638  6638 D UEI.SmartControl: Quickset Services start...
08-05 02:10:11.939  6638  6638 I UEI.SmartControl: Manufacture = LGE
08-05 02:10:11.939  6638  6638 D UEI.SmartControl: Id = LGNevo
08-05 02:10:11.941  6638  6638 D UEI.SmartControl: File observer start...
08-05 02:10:11.942  6638  6638 E UEI.SmartControl: IR Port is disabled: false
08-05 02:10:11.942  6638  6638 D UEI.SmartControl: Starting file observer...
08-05 02:10:11.943  6638  6638 D UEI.SmartControl: Extracting JNI libs...
08-05 02:10:11.943  6638  6638 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-05 02:10:11.983   348   356 E GBMv2   : DFP En is all cleared set to be enabled
08-05 02:10:11.983   348   356 E GBMv2   : Set value is all cleared set the max
08-05 02:10:11.983   348   356 I GBMv2   : DFP Enabled. Ignore VFP set
,08-05 02:10:12.014  6538  6538 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-05 02:10:12.014  6538  6538 I chromium: 
08-05 02:10:12.018  6638  6638 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-05 02:10:12.018  6638  6638 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-05 02:10:12.018  6638  6638 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-05 02:10:12.043  6638  6638 I UEI.SmartControl: --- Selecting new region: 6
08-05 02:10:12.045  6638  6638 I UEI.SmartControl: Model = LG-D855
08-05 02:10:12.046  6638  6638 D UEI.SmartControl: QS Service created
,08-05 02:10:12.057  6638  6638 I UEI.SmartControl: Service initServices...
,08-05 02:10:12.060  6638  6638 D UEI.SmartControl: QS start get config
08-05 02:10:12.060  6538  6538 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-05 02:10:12.108  6638  6638 D UEI.SmartControl: Loading JNI Libs...
,08-05 02:10:12.136  6538  6627 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-05 02:10:12.136  6538  6627 I chromium: 
,08-05 02:10:12.271  6538  6661 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435145216
,08-05 02:10:12.286  6538  6661 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-05 02:10:12.286  6538  6661 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-05 02:10:12.286  6538  6661 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-05 02:10:12.286  6538  6661 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-05 02:10:12.286  6538  6661 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-05 02:10:12.286  6538  6661 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22b788aa added. We now have 1 listener(s)
08-05 02:10:12.289  1045  2070 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 02:10:12.292  6538  6661 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-05 02:10:12.293  6538  6661 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 02:10:12.294  6538  6661 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 02:10:12.294  6538  6661 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-05 02:10:12.302  6538  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-05 02:10:12.302  6538  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-05 02:10:12.302  6538  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-05 02:10:12.302  6538  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-05 02:10:12.302  6538  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-05 02:10:12.302  6538  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-05 02:10:12.302  6538  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-05 02:10:12.302  6538  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-05 02:10:12.302  6538  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-05 02:10:12.302  6538  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-05 02:10:12.302  6538  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-05 02:10:12.302  6538  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-05 02:10:12.302  6538  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-05 02:10:12.302  6538  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-05 02:10:12.302  6538  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3626a011 added. We now have 1 listener(s)
08-05 02:10:12.302  6538  6661 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 02:10:12.309  1045  1532 D WifiService: New client listening to asynchronous messages
,08-05 02:10:12.314  6538  6661 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 02:10:12.314  6538  6661 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-05 02:10:12.316  6538  6661 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-05 02:10:12.316  6538  6661 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-05 02:10:12.317  6538  6661 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-05 02:10:12.320  6538  6661 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-05 02:10:12.322  1045  2082 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 02:10:12.322  6538  6661 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-05 02:10:12.330  6538  6661 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-05 02:10:12.330  6538  6661 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 02:10:12.330  6538  6661 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 02:10:12.330  6538  6661 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 02:10:12.330  6538  6661 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 02:10:12.330  6538  6661 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 02:10:12.330  6538  6661 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 02:10:12.330  6538  6661 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 02:10:12.330  6538  6661 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 02:10:12.330  6538  6661 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-05 02:10:12.331  6538  6661 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 02:10:12.333  6538  6538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 02:10:12.333  6538  6661 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-05 02:10:12.338  6538  6538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 02:10:12.355  6638  6638 I UEI.SmartControl: Supports setup maps: true
,08-05 02:10:12.368  6538  6538 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
08-05 02:10:12.376  6638  6638 D UEI.SmartControl: QS start statue = true Error code = 0
08-05 02:10:12.376  6638  6638 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-05 02:10:12.376  6638  6638 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-05 02:10:12.377  6638  6638 I UEI.SmartControl: ### init IR Blaster...
,08-05 02:10:12.384  6638  6638 D serial_port: Configuring serial port
08-05 02:10:12.388  6638  6638 E UEI.SmartControl: UEIBLaster setting for 616
08-05 02:10:12.388  6638  6638 I UEI.SmartControl: Setting serial record hearder size = 2
08-05 02:10:12.389  6638  6638 I UEI.SmartControl: configuring settings for MAXQ616
08-05 02:10:12.389  6638  6638 I UEI.SmartControl: Get version...
,08-05 02:10:12.405  6638  6665 D UEI.SmartControl: serial port data available: 21
,08-05 02:10:12.432  6638  6638 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-05 02:10:12.432  6638  6638 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-05 02:10:12.433  6638  6638 I UEI.SmartControl: QS saving settings...
,08-05 02:10:12.434  6638  6638 D UEI.SmartControl: IR Blaster version: 25672567
08-05 02:10:12.451  6638  6665 D UEI.SmartControl: serial port data available: 4
,08-05 02:10:12.490  6638  6668 I UEI.SmartControl: Device manager: loading config....
,08-05 02:10:12.491  6638  6668 D UEI.SmartControl: ----------- loading internal config...
08-05 02:10:12.503  6638  6638 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-05 02:10:12.508  6638  6638 E UEI.SmartControl: Services init done
08-05 02:10:12.508  6638  6638 D UEI.SmartControl: QS Service init finished
08-05 02:10:12.511  6638  6638 D UEI.SmartControl: QS Service version name: 2.1.91
08-05 02:10:12.511  6638  6638 D UEI.SmartControl: QS Service version code: 201091
08-05 02:10:12.512  6638  6638 D UEI.SmartControl: Service requested: Control
08-05 02:10:12.514  6638  6668 E UEI.SmartControl: Loading SETTINGS...
,08-05 02:10:12.519  6638  6638 D UEI.SmartControl: Request IControl service: devices are loaded...
08-05 02:10:12.521  5649  5649 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-05 02:10:12.522  1045  1088 I ActivityManager: Killing 5649:com.lge.qremote/u0a112 (adj 15): empty #17
08-05 02:10:12.527  6638  6655 I UEI.SmartControl: ------ IControl API: 11
08-05 02:10:12.528  6638  6655 I UEI.SmartControl: Registering callback...
08-05 02:10:12.529  6638  6668 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-05 02:10:12.554  6638  6667 I UEI.SmartControl: Notify AllClients services are ready: 0
08-05 02:10:12.554  6638  6667 D UEI.SmartControl: -----service ready thread exits
,08-05 02:10:12.601  1045  1768 W libprocessgroup: failed to open /acct/uid_10112/pid_5649/cgroup.procs: No such file or directory
08-05 02:10:12.601  6638  6638 D UEI.SmartControl: Internal service binding...
,08-05 02:10:13.038  6538  6664 W jxcore-log: Initializing JXcore engine
08-05 02:10:13.038  6538  6664 W jxcore-log: JXcore engine is ready
,08-05 02:10:13.063  6664  6664 W Thread-752: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[10453]" dev="sockfs" ino=10453 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-05 02:10:13.063  6664  6664 W Thread-752: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-05 02:10:13.063  6664  6664 W Thread-752: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[9861]" dev="sockfs" ino=9861 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-05 02:10:13.063  6664  6664 W Thread-752: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-05 02:10:13.063  6664  6664 W Thread-752: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[31843]" dev="sockfs" ino=31843 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-05 02:10:13.089  6538  6664 W jxcore-log: Starting JXcore engine
,08-05 02:10:13.164  6538  6664 W jxcore-log: Platform android
08-05 02:10:13.164  6538  6664 W jxcore-log: 
08-05 02:10:13.164  6538  6664 W jxcore-log: Process ARCH arm
08-05 02:10:13.164  6538  6664 W jxcore-log: 
,08-05 02:10:13.388  6538  6664 I jxcore-log: JXcore Cordova bridge is ready!
08-05 02:10:13.388  6538  6664 I jxcore-log: 
08-05 02:10:13.388  6538  6664 W jxcore-log: JXcore engine is started
,08-05 02:10:13.403  6538  6661 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-05 02:10:13.407  6538  6538 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-05 02:10:14.937  6481  6481 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-05 02:10:14.939  1045  2043 I ActivityManager: Killing 5208:com.android.calendar/u0a13 (adj 15): empty #17
08-05 02:10:15.061  1045  2101 W libprocessgroup: failed to open /acct/uid_10013/pid_5208/cgroup.procs: No such file or directory
,08-05 02:10:15.923  6481  6517 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-05 02:10:17.490  6638  6666 D serial_port: close(fd = 25)
,08-05 02:10:17.496  6638  6669 D UEI.SmartControl: Internal timer expired: 1
08-05 02:10:17.496  6638  6669 D UEI.SmartControl: unbind internal service
08-05 02:10:17.502  6638  6638 D UEI.SmartControl: Service.onUnbind: IControl
,08-05 02:10:17.504  6638  6638 D UEI.SmartControl: Service.onDestroy
08-05 02:10:17.505  6638  6638 D UEI.SmartControl: Lock is in USE false
08-05 02:10:17.505  6638  6638 D UEI.SmartControl: unbind internal service
08-05 02:10:17.505  6638  6638 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@31e1e197
08-05 02:10:17.505  6638  6638 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-05 02:10:17.505  6638  6638 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-05 02:10:17.505  6638  6638 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-05 02:10:17.506  6638  6638 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-05 02:10:17.506  6638  6638 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-05 02:10:17.506  6638  6638 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-05 02:10:17.506  6638  6638 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-05 02:10:17.506  6638  6638 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-05 02:10:17.506  6638  6638 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 02:10:17.506  6638  6638 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-05 02:10:17.506  6638  6638 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-05 02:10:17.506  6638  6638 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 02:10:17.506  6638  6638 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 02:10:17.506  6638  6638 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-05 02:10:17.506  6638  6638 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-05 02:10:17.506  6638  6638 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@31e1e197
08-05 02:10:17.508  6638  6666 I UEI.SmartControl: Serial port is closed.
08-05 02:10:17.508  6638  6638 I UEI.SmartControl: Serial port is closed.
08-05 02:10:17.508  6638  6638 I UEI.SmartControl: Serial port is closed.
08-05 02:10:17.508  6638  6638 D UEI.SmartControl: Blaster closed
08-05 02:10:17.508  6638  6638 D UEI.SmartControl: Shut down QS...
08-05 02:10:17.509  6638  6638 D UEI.SmartControl: Stopping QS lib
08-05 02:10:17.509  6638  6638 D UEI.SmartControl: QS lib stop result = true
08-05 02:10:17.509  6638  6638 D UEI.SmartControl: Stopped QS lib
08-05 02:10:17.509  6638  6638 D UEI.SmartControl: Stopped file observer...
08-05 02:10:17.509  6638  6638 D UEI.SmartControl: QS shutdown complete
08-05 02:10:18.505  1830  6390 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-05 02:10:18.510   324  6678 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-05 02:10:18.510   324  6678 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-05 02:10:18.510   324  6678 D libc-netbsd: res_queryN name = android.clients.google.com succeed
08-05 02:10:18.789  1830  1830 I ConfigFetchService: fetch service done; releasing wakelock
,08-05 02:10:18.794  1830  1830 I ConfigFetchService: stopping self
08-05 02:10:18.802  2228  2228 I ConfigService: onDestroy
,08-05 02:10:23.603  1045  1175 I ActivityManager: Waited long enough for: ServiceRecord{3058aed6 u0 com.google.android.gms/.wearable.service.WearableService}
,08-05 02:10:29.427  6538  6664 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-05 02:10:29.427  6538  6664 I jxcore-log: 
,08-05 02:10:29.429  6538  6664 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-05 02:10:29.429  6538  6664 I jxcore-log: 
08-05 02:10:29.434  6538  6664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 02:10:29.434  6538  6664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 02:10:29.434  6538  6664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 02:10:29.434  6538  6664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 02:10:29.434  6538  6664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 02:10:29.434  6538  6664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 02:10:29.434  6538  6664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 02:10:29.434  6538  6664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 02:10:29.437  6538  6664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 02:10:29.439  6538  6664 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-05 02:10:29.439  6538  6664 I jxcore-log: 
08-05 02:10:29.441  6538  6664 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-05 02:10:29.441  6538  6664 I jxcore-log: 
,08-05 02:10:29.778  6538  6664 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests
08-05 02:10:29.778  6538  6664 I jxcore-log: Failed to execute UT.
08-05 02:10:29.778  6538  6664 I jxcore-log: 
08-05 02:10:29.779  6538  6664 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-05 02:10:29.779  6538  6664 I jxcore-log: 
08-05 02:10:29.781  6538  6664 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 02:10:29.781  6538  6664 I jxcore-log: 
,08-05 02:10:29.797  6538  6538 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-05 02:10:30.147  6680  6680 D AndroidRuntime: 
08-05 02:10:30.147  6680  6680 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-05 02:10:30.154  6680  6680 D AndroidRuntime: CheckJNI is OFF
08-05 02:10:30.340  6680  6680 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-05 02:10:30.354  1045  1175 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
,08-05 02:10:30.356  1045  1175 I ActivityManager: Killing 6538:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-05 02:10:30.396  1045  1961 I WindowState: WIN DEATH: Window{350d849c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-05 02:10:30.399  1045  1532 D WifiService: Client connection lost with reason: 4
08-05 02:10:30.405  1045  1961 D InputDispatcher: Window went away: Window{350d849c u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-05 02:10:30.453  1045  1175 I ActivityManager:   Force finishing activity ActivityRecord{4b67609 u0 com.test.thalitest/.MainActivity t40}
,08-05 02:10:30.518   348   354 E GBMv2   : DFP En is all cleared set to be enabled
08-05 02:10:30.520  1045  2102 W ActivityManager: Spurious death for ProcessRecord{dd26964 6538:com.test.thalitest/u0a118}, curProc for 6538: null
08-05 02:10:30.525  1045  1260 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
,08-05 02:10:30.526  1045  1260 I ActivityManager:   Force finishing activity ActivityRecord{4b67609 u0 com.test.thalitest/.MainActivity t40 f}
08-05 02:10:30.526  1045  1260 W ActivityManager: Duplicate finish request for ActivityRecord{4b67609 u0 com.test.thalitest/.MainActivity t40 f}
08-05 02:10:30.560  4614  4614 I art     : Explicit concurrent mark sweep GC freed 459(31KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 294us total 26.239ms
,08-05 02:10:30.572  2083  2083 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-05 02:10:30.573  2083  2083 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-05 02:10:30.576  1962  1977 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-05 02:10:30.576  1962  1977 D SplitWindowPolicy: topRunningActivity=ActivityInfo{33b7224b co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
08-05 02:10:30.577  1962  1978 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-05 02:10:30.578  1962  1978 D SplitWindowPolicy: topRunningActivity=ActivityInfo{226ea428 co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
,08-05 02:10:30.580  2083  2083 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-05 02:10:30.582  2083  2172 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-05 02:10:30.585  1916  1916 D ActionManagerService: notifyUserLog: 1000003
08-05 02:10:30.585  2083  2083 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-05 02:10:30.585  3800  4495 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-05 02:10:30.586  1590  1590 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-05 02:10:30.592  1045  1457 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-05 02:10:30.613  2463  2671 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-05 02:10:30.615  3842  3842 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-05 02:10:30.615  3842  3842 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-05 02:10:30.615  2026  2026 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-05 02:10:30.617  3800  3800 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-05 02:10:30.620  2155  2155 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
08-05 02:10:30.622  2155  2155 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
08-05 02:10:30.637  1045  1768 V SIM_STK : Menu title from STK is T-Mobile
08-05 02:10:30.650  2083  2083 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,08-05 02:10:30.658  2083  2083 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-05 02:10:30.661  2083  2083 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-05 02:10:30.664  4503  4503 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-05 02:10:30.664  4503  4503 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-05 02:10:30.664  4503  4503 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-05 02:10:30.664  4503  4503 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-05 02:10:30.664  4503  4503 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-05 02:10:30.664  4503  4503 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-05 02:10:30.664  4503  4503 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-05 02:10:30.664  4503  4503 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-05 02:10:30.664  4503  4503 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 02:10:30.664  4503  4503 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 02:10:30.664  4503  4503 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-05 02:10:30.664  4503  4503 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-05 02:10:30.665  6360  6360 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,08-05 02:10:30.683  1045  1045 I art     : Explicit concurrent mark sweep GC freed 25314(1592KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 2.665ms total 120.536ms
08-05 02:10:30.683  1045  1768 I art     : WaitForGcToComplete blocked for 24.469ms for cause Explicit
,08-05 02:10:30.717  1830  1830 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-05 02:10:30.719  1590  1590 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-05 02:10:30.725  1882  1882 D SplitUIManager: split_name #11 / not available #0
08-05 02:10:30.726  1882  1882 D SplitUIService: removed split : 
08-05 02:10:30.748  2228  2228 I ConfigService: onCreate
,08-05 02:10:30.748  2228  2228 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-05 02:10:30.751  1830  1830 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-05 02:10:30.755  2228  2228 I ConfigService: onBind returning update interface
08-05 02:10:30.757  2228  2228 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-05 02:10:30.757  2228  2228 I ConfigService: onBind returning config service
08-05 02:10:30.760  1882  1882 D SplitUIManager: split_name #11 / not available #0
08-05 02:10:30.760  1882  1882 I SplitUIService: split app #11
,08-05 02:10:30.775  2228  2228 I ConfigService: onDestroy
,08-05 02:10:30.783  1830  6716 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-05 02:10:30.793  1045  1045 D administrator: Handling package changes for user 0
08-05 02:10:30.809  1045  1768 I art     : Explicit concurrent mark sweep GC freed 5695(501KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 1.904ms total 123.434ms
,08-05 02:10:30.811  1045  1260 I art     : WaitForGcToComplete blocked for 130.290ms for cause Explicit
08-05 02:10:30.813  1590  1638 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-05 02:10:30.813  1590  1638 D KeyguardModel: createShortcutInfo...
08-05 02:10:30.819  1916  1916 D ActionManagerService: notifyUserLog: 1000004
08-05 02:10:30.820  2083  2083 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-05 02:10:30.820  3800  4495 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
,08-05 02:10:30.821  1590  1638 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-05 02:10:30.821  1590  1638 D KeyguardModel: createShortcutInfo...
08-05 02:10:30.822  1045  1173 W InputMethodInfo: Duplicated subtype definition found: , voice
08-05 02:10:30.822  1045  1981 V SIM_STK : Menu title from STK is T-Mobile
08-05 02:10:30.822  1045  1981 V SIM_STK : Menu title from STK is T-Mobile
08-05 02:10:30.824  1590  1638 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-05 02:10:30.825  1590  1638 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 02:10:30.825  1590  1638 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-05 02:10:30.826  1590  1638 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-05 02:10:30.826  1590  1638 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 02:10:30.826  1590  1638 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-05 02:10:30.831  1590  1638 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-05 02:10:30.831  1590  1638 D KeyguardModel: createShortcutInfo...
08-05 02:10:30.838  1590  1638 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-05 02:10:30.838  1590  1638 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 02:10:30.840  1590  1638 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 02:10:30.840  1590  1638 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,08-05 02:10:30.842  1590  1638 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-05 02:10:30.842  1590  1638 D KeyguardModel: createShortcutInfo...
08-05 02:10:30.846  1590  1638 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 02:10:30.846  1590  1638 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-05 02:10:30.846  1590  1638 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-05 02:10:30.846  1590  1638 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-05 02:10:30.847  1590  1638 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 02:10:30.847  1590  1638 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-05 02:10:30.849  1590  1638 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-05 02:10:30.849  1590  1638 D KeyguardModel: createShortcutInfo...
08-05 02:10:30.852  3800  3816 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,08-05 02:10:30.856  1590  1590 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-05 02:10:30.856  1590  1590 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-05 02:10:30.857  1590  1590 D KeyguardModel: handleShortcutListChanged...
08-05 02:10:30.857  1590  1590 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-05 02:10:30.860  2083  2083 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-05 02:10:30.860  2083  2083 I GBoardWebViewUtils: , create_time: 1430832262123
08-05 02:10:30.860  2083  2083 I GBoardWebViewUtils: , expire_time: 0
08-05 02:10:30.860  2083  2083 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-05 02:10:30.860  2083  2083 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-05 02:10:30.860  2083  2083 I GBoardWebViewUtils: , display: false
08-05 02:10:30.860  2083  2083 I GBoardWebViewUtils: , animation: false }
08-05 02:10:30.861  2083  2083 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-05 02:10:30.861  2083  2083 I GBoardWebViewUtils: , create_time: 1430832262287
08-05 02:10:30.861  2083  2083 I GBoardWebViewUtils: , expire_time: 0
08-05 02:10:30.861  2083  2083 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-05 02:10:30.861  2083  2083 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-05 02:10:30.861  2083  2083 I GBoardWebViewUtils: , display: false
08-05 02:10:30.861  2083  2083 I GBoardWebViewUtils: , animation: false }
08-05 02:10:30.861  2083  2083 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1469801564706
08-05 02:10:30.861  2083  2083 I GBoardWebViewUtils: , create_time: 1469801565454
08-05 02:10:30.861  2083  2083 I GBoardWebViewUtils: , expire_time: 0
08-05 02:10:30.861  2083  2083 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide.html?id=guide_1111111111116_1469801564706&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-05 02:10:30.861  2083  2083 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-05 02:10:30.861  2083  2083 I GBoardWebViewUtils: , display: false
08-05 02:10:30.861  2083  2083 I GBoardWebViewUtils: , animation: false }
08-05 02:10:30.868  1045  2025 V SIM_STK : Menu title from STK is T-Mobile
,08-05 02:10:30.879  2083  2083 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-05 02:10:30.880  2083  6722 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-05 02:10:30.883  1045  1980 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-05 02:10:30.883  3842  3842 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-05 02:10:30.884  3842  3842 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-05 02:10:30.884  3842  3842 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-05 02:10:30.884  3842  3842 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-05 02:10:30.884  3842  3842 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-05 02:10:30.884  3842  3842 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-05 02:10:30.884  3842  3842 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-05 02:10:30.884  3842  3842 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-05 02:10:30.884  3842  3842 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-05 02:10:30.884  3842  3842 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-05 02:10:30.884  3842  3842 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
,08-05 02:10:30.896  1590  1638 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-05 02:10:30.896  1590  1638 D KeyguardModel: createShortcutInfo...
08-05 02:10:30.896  5965  6723 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-05 02:10:30.899  1590  1638 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-05 02:10:30.899  1590  1638 D KeyguardModel: createShortcutInfo...
08-05 02:10:30.900  1590  1638 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 02:10:30.900  1590  1638 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,08-05 02:10:30.905  1590  1638 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-05 02:10:30.905  1590  1638 D KeyguardModel: createShortcutInfo...
08-05 02:10:30.906  1590  1638 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 02:10:30.906  1590  1638 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-05 02:10:30.908  1590  1638 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-05 02:10:30.908  1590  1638 D KeyguardModel: createShortcutInfo...
08-05 02:10:30.911  1590  1638 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 02:10:30.911  1590  1638 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-05 02:10:30.920  1590  1638 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-05 02:10:30.920  1590  1638 D KeyguardModel: createShortcutInfo...
,08-05 02:10:30.926  1590  1590 D KeyguardModel: handleShortcutListChanged...
08-05 02:10:30.926  1590  1590 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-05 02:10:30.931  1830  6728 I PeopleContactsSync: CP2 sync disabled
08-05 02:10:30.936  1830  6725 W GmsApplication: Using Auth Proxy for data requests.
,08-05 02:10:30.944  2083  2083 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-05 02:10:30.946  2083  2083 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-05 02:10:30.946  1830  6725 W GmsApplication: Using Auth Proxy for data requests.
08-05 02:10:30.960   338   416 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-05 02:10:30.960  3203  6729 I Thermal-Lib: Thermal-Lib-Client: Client request sent
,08-05 02:10:30.963  1830  4762 I Icing   : doRemovePackageData com.test.thalitest
08-05 02:10:30.964  1045  1045 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-05 02:10:30.964  1045  1045 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-05 02:10:30.964  1045  1045 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-05 02:10:30.974  6029  6029 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-05 02:10:30.986  1045  1565 D TaskPersister: removeObsoleteFile: deleting file=40_task.xml,
,08-05 02:10:30.993  6447  6447 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
08-05 02:10:30.996  2302  6730 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-05 02:10:31.003  2026  2026 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
,08-05 02:10:31.003  2026  2026 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-05 02:10:31.004  2026  2026 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-05 02:10:31.007  6360  6360 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-05 02:10:31.036  2083  2083 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-05 02:10:31.040  2083  2083 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 02:10:31.042  2083  2083 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-05 02:10:31.043  2083  2083 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
,08-05 02:10:31.043  1045  1980 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=6733 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-05 02:10:31.044  2083  2083 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-05 02:10:31.045  2083  2083 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-05 02:10:31.058  1045  1182 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3d4434f6 u0 com.lge.launcher2/.Launcher t39} time:136928
08-05 02:10:31.060  2083  2083 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-05 02:10:31.060  2083  2083 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 02:10:31.060  2083  2261 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-05 02:10:31.061  2083  2261 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,08-05 02:10:31.075  2083  2083 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,08-05 02:10:31.076  2083  2083 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-05 02:10:31.076  2083  2083 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 02:10:31.084  2083  2083 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-05 02:10:31.086  2572  2572 D [Concierge]Service: onStartCommand(). Type : 8
08-05 02:10:31.086  2572  2572 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-05 02:10:31.087  2572  2572 D [Concierge]Service: Update widget ID : 11
,08-05 02:10:31.088  2083  2083 D [Concierge]WidgetView: change position of spinner
08-05 02:10:31.089  2083  2083 I [Concierge]WidgetView: initWebView(). Time : 1470355831089
08-05 02:10:31.089  2572  2572 D [Concierge]Service: onStartCommand(). Type : 0
08-05 02:10:31.100  1045  1260 I art     : Explicit concurrent mark sweep GC freed 10076(557KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.413ms total 286.545ms
08-05 02:10:31.100  2083  2083 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 775353918
08-05 02:10:31.101  2083  2083 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-05 02:10:31.101  2083  2083 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-05 02:10:31.104  2083  2083 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@2e71279
08-05 02:10:31.104  2083  2083 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-05 02:10:31.105  2083  2083 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-05 02:10:31.105  2083  2083 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 02:10:31.110  2083  2083 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-05 02:10:31.110  2083  2083 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-05 02:10:31.111  2083  2083 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-05 02:10:31.111  2083  2083 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1470355722652, New one : 1470355831089
08-05 02:10:31.111  2083  2083 D [Concierge]WidgetView: Unregister all receivers
08-05 02:10:31.111  2083  2083 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-05 02:10:31.113  2083  2083 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-05 02:10:31.115  2083  2083 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-05 02:10:31.116  2083  2083 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-05 02:10:31.117  2083  2083 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-05 02:10:31.118  2083  2083 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-05 02:10:31.119  6733  6733 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-05 02:10:31.119  6733  6733 W LG Account v2.2: No ProfileInfo entries
08-05 02:10:31.119  6733  6733 I LG Account v2.2: isEnabled: false
08-05 02:10:31.119  2083  2083 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-05 02:10:31.119  6733  6733 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-05 02:10:31.119  6733  6733 I Feature : [Lifetracker]Country: EU
08-05 02:10:31.119  6733  6733 I Feature : [Lifetracker]Operator: OPEN
08-05 02:10:31.119  6733  6733 I Feature : [Lifetracker]Ranking support: false
08-05 02:10:31.119  6733  6733 I Feature : [Lifetracker]Comfort support: false
08-05 02:10:31.119  6733  6733 I Feature : [Lifetracker]Accessory: true
08-05 02:10:31.119  6733  6733 I Feature : [Lifetracker]Health device: true
08-05 02:10:31.119  6733  6733 I Feature : [Lifetracker]Extra Pedometer: false
08-05 02:10:31.119  6733  6733 I Feature : [Lifetracker]Blood glucose device: false
08-05 02:10:31.120  6733  6733 I Feature : [Lifetracker]Device Number: 3
08-05 02:10:31.120  6733  6733 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
08-05 02:10:31.122  2083  2083 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 02:10:31.123  2083  2083 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 02:10:31.140  1045  1979 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=6754 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-05 02:10:31.141  1045  1979 I ActivityManager: Killing 5929:com.android.providers.calendar/u0a14 (adj 15): empty #17
,08-05 02:10:31.171  2083  2083 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-05 02:10:31.178  2083  2083 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-05 02:10:31.179  2083  2083 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
,08-05 02:10:31.180  2083  2083 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 02:10:31.199  2083  2083 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@19d8126b time:137069
,08-05 02:10:31.205  6680  6680 D AndroidRuntime: Shutting down VM
08-05 02:10:31.208  1045  1173 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 02:10:31.212  1045  1173 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-05 02:10:31.264  1045  1088 W libprocessgroup: failed to open /acct/uid_10014/pid_5929/cgroup.procs: No such file or directory
08-05 02:10:31.267  2083  2083 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-05 02:10:31.275  6754  6754 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 02:10:31.275  6754  6754 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,08-05 02:10:31.276  6754  6754 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 02:10:31.276  6754  6754 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-05 02:10:31.277  6754  6754 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-05 02:10:31.277  6754  6754 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-05 02:10:31.313  2083  2083 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-05 02:10:31.346  2083  2857 I GBoardtInterface: onReloaded()
,08-05 02:10:31.347  6754  6754 D PackageIntentReceiver: Not supported Hotkey customization function 
08-05 02:10:31.348  2083  2083 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-05 02:10:31.349  3800  3816 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-05 02:10:31.351  3800  4490 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-05 02:10:31.354  6754  6754 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
08-05 02:10:31.354  6754  6754 D HideNavigationAppsReceiver: replacing : false
08-05 02:10:31.356  6754  6754 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
08-05 02:10:31.356  1916  1916 D ActionManagerService: notifyUserLog: 1000001
08-05 02:10:31.358  3800  4495 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-05 02:10:31.358  3800  4495 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-05 02:10:31.358  6754  6754 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
08-05 02:10:31.358  6754  6754 D ButtonCombinationReceiver: replacing : false
,08-05 02:10:31.361  1916  1916 D ActionManagerService: notifyUserLog: 1000001
08-05 02:10:31.363  3800  4495 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-05 02:10:31.363  3800  4495 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-05 02:10:31.363  3800  4495 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-05 02:10:31.364  3800  3816 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-05 02:10:31.366  3800  4495 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-05 02:10:31.367  2083  2083 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-05 02:10:31.367  2083  2083 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-05 02:10:31.369  2083  2083 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-05 02:10:31.369  2083  2083 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-05 02:10:31.370  1045  1718 I ActivityManager: Killing 2155:com.lge.music/u0a34 (adj 15): empty #17
08-05 02:10:31.371  2083  2083 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1469801564706&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-05 02:10:31.371  2083  2083 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1469801564706&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,08-05 02:10:31.381   329   329 V AudioFlinger: 2155 died, releasing its sessions
08-05 02:10:31.381   329   329 V AudioFlinger:  pid 1865 @ 0
08-05 02:10:31.381   329   329 V AudioFlinger:  pid 3412 @ 1
08-05 02:10:31.381   329   329 V AudioFlinger:  pid 3412 @ 2
,08-05 02:10:31.415  1045  2025 W libprocessgroup: failed to open /acct/uid_10034/pid_2155/cgroup.procs: No such file or directory
,08-05 02:10:31.421  4614  6772 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-05 02:10:31.441  1045  2102 V SIM_STK : Menu title from STK is T-Mobile
,08-05 02:10:31.452  1045  2082 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6773 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-05 02:10:31.483  6773  6773 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2586 
,08-05 02:10:31.488  6137  6137 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-05 02:10:31.488  6137  6137 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-05 02:10:31.488  6137  6137 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-05 02:10:31.488  6137  6137 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-05 02:10:31.488  6137  6137 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-05 02:10:31.488  6137  6137 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
08-05 02:10:31.499  6587  6587 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_REMOVED : com.test.thalitest
,08-05 02:10:31.504  6754  6754 D PackageIntentReceiver: Not supported Hotkey customization function 
,08-05 02:10:31.523  1045  2025 I ActivityManager: Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=6794 uid=10060 gids={50060, 9997, 1028, 4002} abi=armeabi-v7a
08-05 02:10:31.529  1045  1933 I ActivityManager: Killing 6399:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-05 02:10:31.533  4614  6772 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-05 02:10:31.546  4614  6772 E IcingCorporaProvider: Exception thrown from notifyTableChanged
08-05 02:10:31.546  4614  6772 E IcingCorporaProvider: java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-05 02:10:31.546  4614  6772 E IcingCorporaProvider: 	at beg.a(PG:301)
08-05 02:10:31.546  4614  6772 E IcingCorporaProvider: 	at beg.c(PG:222)
08-05 02:10:31.546  4614  6772 E IcingCorporaProvider: 	at cun.b(PG:660)
08-05 02:10:31.546  4614  6772 E IcingCorporaProvider: 	at cun.a(PG:651)
08-05 02:10:31.546  4614  6772 E IcingCorporaProvider: 	at cun.g(PG:597)
08-05 02:10:31.546  4614  6772 E IcingCorporaProvider: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(PG:301)
08-05 02:10:31.546  4614  6772 E IcingCorporaProvider: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
08-05 02:10:31.546  4614  6772 E IcingCorporaProvider: 	at android.content.ContentResolver.update(ContentResolver.java:1349)
08-05 02:10:31.546  4614  6772 E IcingCorporaProvider: 	at cuw.Tg(PG:368)
08-05 02:10:31.546  4614  6772 E IcingCorporaProvider: 	at cuy.ub(PG:301)
08-05 02:10:31.546  4614  6772 E IcingCorporaProvider: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(PG:268)
08-05 02:10:31.546  4614  6772 E IcingCorporaProvider: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(PG:186)
08-05 02:10:31.546  4614  6772 E IcingCorporaProvider: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-05 02:10:31.546  4614  6772 E IcingCorporaProvider: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 02:10:31.546  4614  6772 E IcingCorporaProvider: 	at android.os.Looper.loop(Looper.java:135)
08-05 02:10:31.546  4614  6772 E IcingCorporaProvider: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-05 02:10:31.546  4614  6772 E IcingCorporaProvider: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-05 02:10:31.546  4614  6772 E IcingCorporaProvider: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-05 02:10:31.546  4614  6772 E IcingCorporaProvider: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
08-05 02:10:31.546  4614  6772 E IcingCorporaProvider: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-05 02:10:31.546  4614  6772 E IcingCorporaProvider: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-05 02:10:31.546  4614  6772 E IcingCorporaProvider: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-05 02:10:31.546  4614  6772 E IcingCorporaProvider: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-05 02:10:31.546  4614  6772 E IcingCorporaProvider: 	at bea.a(PG:382)
08-05 02:10:31.546  4614  6772 E IcingCorporaProvider: 	at beg.i(PG:325)
08-05 02:10:31.546  4614  6772 E IcingCorporaProvider: 	at beh.call(PG:215)
08-05 02:10:31.546  4614  6772 E IcingCorporaProvider: 	at beg.a(PG:299)
08-05 02:10:31.546  4614  6772 E IcingCorporaProvider: 	... 15 more
08-05 02:10:31.546  4614  6772 W IcingCorporaProvider: notifyTableChanged failed.
08-05 02:10:31.546  4614  6772 W IcingCorporaProvider: Table change notification failed for TableStorageSpec[applications]
08-05 02:10:31.546  4614  6772 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 125 ms] updated apps [took 125 ms] 
,08-05 02:10:31.600  1045  1563 W libprocessgroup: failed to open /acct/uid_10008/pid_6399/cgroup.procs: No such file or directory
,08-05 02:10:31.620  2228  4017 W FileUtils: Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,08-05 02:10:31.621  2228  4017 W ServiceConnection: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/service.connections: open failed: EROFS (Read-only file system)
08-05 02:10:31.621  2228  4017 W ServiceConnection: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-05 02:10:31.621  2228  4017 W ServiceConnection: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-05 02:10:31.621  2228  4017 W ServiceConnection: 	at android.app.ContextImpl.openFileOutput(ContextImpl.java:1047)
08-05 02:10:31.621  2228  4017 W ServiceConnection: 	at android.content.ContextWrapper.openFileOutput(ContextWrapper.java:181)
08-05 02:10:31.621  2228  4017 W ServiceConnection: 	at com.google.android.gms.common.internal.bf.b(SourceFile:56)
08-05 02:10:31.621  2228  4017 W ServiceConnection: 	at com.google.android.gms.common.internal.bf.a(SourceFile:48)
08-05 02:10:31.621  2228  4017 W ServiceConnection: 	at com.google.android.gms.common.internal.be.a(SourceFile:45)
08-05 02:10:31.621  2228  4017 W ServiceConnection: 	at com.google.android.gms.icing.service.n.b(SourceFile:118)
08-05 02:10:31.621  2228  4017 W ServiceConnection: 	at com.google.android.gms.common.internal.bd.b(SourceFile:218)
08-05 02:10:31.621  2228  4017 W ServiceConnection: 	at com.google.android.gms.common.internal.ao.onTransact(SourceFile:460)
08-05 02:10:31.621  2228  4017 W ServiceConnection: 	at android.os.Binder.execTransact(Binder.java:446)
08-05 02:10:31.621  2228  4017 W ServiceConnection: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-05 02:10:31.621  2228  4017 W ServiceConnection: 	at libcore.io.Posix.open(Native Method)
08-05 02:10:31.621  2228  4017 W ServiceConnection: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-05 02:10:31.621  2228  4017 W ServiceConnection: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-05 02:10:31.621  2228  4017 W ServiceConnection: 	... 10 more
08-05 02:10:31.627  1830  4762 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-1 for write failed: Read-only file system
08-05 02:10:31.627  1830  4762 E Icing   : Could not init tag ds.tag.corpusid-1
08-05 02:10:31.628  1830  4762 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-13 for write failed: Read-only file system
08-05 02:10:31.628  1830  4762 E Icing   : Could not init tag ds.tag.corpusid-13
08-05 02:10:31.628  1830  4762 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-7 for write failed: Read-only file system
08-05 02:10:31.628  1830  4762 E Icing   : Could not init tag ds.tag.corpusid-7
08-05 02:10:31.628  1830  4762 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-8 for write failed: Read-only file system
08-05 02:10:31.628  1830  4762 E Icing   : Could not init tag ds.tag.corpusid-8
08-05 02:10:31.628  1830  4762 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-9 for write failed: Read-only file system
08-05 02:10:31.628  1830  4762 E Icing   : Could not init tag ds.tag.corpusid-9
08-05 02:10:31.628  1830  4762 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
08-05 02:10:31.628  1830  4762 E Icing   : Could not init tag ds.tag.deleted
08-05 02:10:31.628  1830  4762 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
08-05 02:10:31.628  1830  4762 E Icing   : Writing status failed
08-05 02:10:31.655  6794  6794 E SQLiteDatabase: Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
08-05 02:10:31.655  6794  6794 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-05 02:10:31.655  6794  6794 E SQLiteDatabas,e: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-05 02:10:31.655  6794  6794 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-05 02:10:31.655  6794  6794 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-05 02:10:31.655  6794  6794 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-05 02:10:31.655  6794  6794 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-05 02:10:31.655  6794  6794 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-05 02:10:31.655  6794  6794 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-05 02:10:31.655  6794  6794 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-05 02:10:31.655  6794  6794 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-05 02:10:31.655  6794  6794 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-05 02:10:31.655  6794  6794 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-05 02:10:31.655  6794  6794 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-05 02:10:31.655  6794  6794 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-05 02:10:31.655  6794  6794 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
08-05 02:10:31.655  6794  6794 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
08-05 02:10:31.655  6794  6794 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
08-05 02:10:31.655  6794  6794 E SQLiteDatabase: 	at android.content.ContentResolver.call(ContentResolver.java:1388)
08-05 02:10:31.655  6794  6794 E SQLiteDatabase: 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
08-05 02:10:31.655  6794  6794 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2586)
08-05 02:10:31.655  6794  6794 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
08-05 02:10:31.655  6794  6794 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1360)
08-05 02:10:31.655  6794  6794 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 02:10:31.655  6794  6794 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-05 02:10:31.655  6794  6794 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-05 02:10:31.655  6794  6794 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 02:10:31.655  6794  6794 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 02:10:31.655  6794  6794 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-05 02:10:31.655  6794  6794 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-05 02:10:31.655  6794  6794 D AndroidRuntime: Shutting down VM
,--------- beginning of crash
08-05 02:10:31.656  6794  6794 E AndroidRuntime: FATAL EXCEPTION: main
08-05 02:10:31.656  6794  6794 E AndroidRuntime: Process: com.android.documentsui, PID: 6794
08-05 02:10:31.656  6794  6794 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-05 02:10:31.656  6794  6794 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2593)
08-05 02:10:31.656  6794  6794 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
08-05 02:10:31.656  6794  6794 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1360)
08-05 02:10:31.656  6794  6794 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 02:10:31.656  6794  6794 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-05 02:10:31.656  6794  6794 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-05 02:10:31.656  6794  6794 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 02:10:31.656  6794  6794 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 02:10:31.656  6794  6794 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-05 02:10:31.656  6794  6794 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-05 02:10:31.656  6794  6794 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-05 02:10:31.656  6794  6794 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-05 02:10:31.656  6794  6794 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-05 02:10:31.656  6794  6794 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-05 02:10:31.656  6794  6794 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-05 02:10:31.656  6794  6794 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-05 02:10:31.656  6794  6794 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-05 02:10:31.656  6794  6794 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-05 02:10:31.656  6794  6794 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-05 02:10:31.656  6794  6794 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-05 02:10:31.656  6794  6794 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-05 02:10:31.656  6794  6794 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-05 02:10:31.656  6794  6794 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-05 02:10:31.656  6794  6794 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-05 02:10:31.656  6794  6794 E AndroidRuntime: 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
08-05 02:10:31.656  6794  6794 E AndroidRuntime: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
08-05 02:10:31.656  6794  6794 E AndroidRuntime: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
08-05 02:10:31.656  6794  6794 E AndroidRuntime: 	at android.content.ContentResolver.call(ContentResolver.java:1388)
08-05 02:10:31.656  6794  6794 E AndroidRuntime: 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.jav,a:35)
08-05 02:10:31.656  6794  6794 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2586)
08-05 02:10:31.656  6794  6794 E AndroidRuntime: 	... 9 more
08-05 02:10:31.686  1045  1087 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6814 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-05 02:10:31.687  1045  1087 I ActivityManager: Killing 6568:com.lge.eula/1000 (adj 15): empty #17
08-05 02:10:31.695  2083  2857 I GBoardtInterface: exportHTML()
08-05 02:10:31.698   352   352 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 195us total 9.777ms
08-05 02:10:31.707   352   352 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 184us total 8.879ms

```
