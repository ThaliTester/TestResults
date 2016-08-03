#### Test 7968977505886a0_thali05_LGE-LG-D855 Logs


```
--------- beginning of main
08-03 19:09:50.211   324   422 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-03 19:09:50.212  3215  6619 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-03 19:09:50.331  1815  4735 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
08-03 19:09:50.375  1815  4735 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-03 19:09:50.436  1815  4735 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
,08-03 19:09:50.711  1602  1602 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-03 19:09:50.712  1602  1602 I [SystemUI]LGPowerUI: On Skip Timer : true
--------- beginning of system
08-03 19:09:50.724  1031  1542 D WifiController: battery changed pluggedType: 2
08-03 19:09:50.728  1602  1602 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 289
08-03 19:09:50.728  1602  1602 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-03 19:09:50.731  1939  2093 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-03 19:09:50.731  1939  2093 D LEDHandler: Battery Level Remaining: 100%
08-03 19:09:50.731  1939  2093 D LEDHandler: Battery Temp: 289, mChargingStatus=5, mChargingStop=false
08-03 19:09:50.736  1602  1602 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-03 19:09:50.742  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:09:50.742  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:09:50.742  3861  3963 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-03 19:09:50.865  6626  6626 D AndroidRuntime: 
08-03 19:09:50.865  6626  6626 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-03 19:09:50.868  6626  6626 D AndroidRuntime: CheckJNI is OFF
08-03 19:09:50.930  6586  6586 D LgDataFeature: LgDataFeature() Constructor: none
08-03 19:09:50.930  6586  6586 D LgDataFeature: LgDataFeature() Constructor Done, null
08-03 19:09:50.971  6626  6626 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-03 19:09:50.975  1031  1047 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-03 19:09:50.984  1939  1956 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-03 19:09:50.986  1031  1047 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-03 19:09:50.987  1031  1047 D ActivityManager: setTaskToReturnTo : TaskRecord{38aed79d #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-03 19:09:50.988  1031  1047 D ActivityManager: setTaskToReturnTo : TaskRecord{38aed79d #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-03 19:09:50.988  1031  1047 D WindowStateEx: AppWindowTokenEx init.. 
08-03 19:09:50.989   330   353 E GBMv2   : DFP En is all cleared set to be enabled
08-03 19:09:51.021  1031  1047 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6643 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-03 19:09:51.022  6626  6626 D AndroidRuntime: Shutting down VM
08-03 19:09:51.065  1939  1957 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-03 19:09:51.065  1939  1957 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2ad6647 co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
08-03 19:09:51.066  1939  2773 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-03 19:09:51.067  1939  2773 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1ae85e74 co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
08-03 19:09:51.081  6182  6182 I LockScreenSettings: New app installed broadcast received ..
08-03 19:09:51.091  6182  6182 I LockScreenSettings: Number of installed packages  1
08-03 19:09:51.101  6643  6643 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-03 19:09:51.115  6586  6586 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
08-03 19:09:51.169  1031  1047 V SIM_STK : Menu title from STK is T-Mobile
08-03 19:09:51.206  6643  6643 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-03 19:09:51.218  1031  1943 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6680 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-03 19:09:51.236  6643  6643 I LibraryLoader: Loading: webviewchromium
08-03 19:09:51.242  6643  6643 I LibraryLoader: Time to load native libraries: 8 ms (timestamps 3713-3721)
08-03 19:09:51.242  6643  6643 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-03 19:09:51.260  6643  6643 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1fe2068d}
08-03 19:09:51.262  6643  6643 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-03 19:09:51.262  6643  6643 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-03 19:09:51.273  6643  6643 I BrowserStartupController: Initializing chromium process, renderers=0
08-03 19:09:51.274  6643  6643 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-03 19:09:51.275  6680  6680 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-03 19:09:51.275  6680  6680 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
08-03 19:09:51.291   310  2157 V AudioPolicyService: registerClient() client 0xb1023460, uid 10118
08-03 19:09:51.293  6643  6643 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-03 19:09:51.294  6643  6643 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-03 19:09:51.294  6643  6643 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-03 19:09:51.296  1031  1095 D BluetoothManagerService: Message: 20
08-03 19:09:51.296  1031  1095 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2bb90f8:true
08-03 19:09:51.301  1031  1725 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6705 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-03 19:09:51.302  1031  1725 I ActivityManager: Killing 5880:com.google.android.talk/u0a72 (adj 15): empty #17
08-03 19:09:51.315  6643  6643 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-03 19:09:51.315  6643  6643 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-03 19:09:51.315  6643  6643 I Adreno-EGL: Build Date: 12/12/14 금
08-03 19:09:51.315  6643  6643 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-03 19:09:51.315  6643  6643 I Adreno-EGL: Remote Branch: 
08-03 19:09:51.315  6643  6643 I Adreno-EGL: Local Patches: 
08-03 19:09:51.315  6643  6643 I Adreno-EGL: Reconstruct Branch: 
08-03 19:09:51.381  1031  1938 W libprocessgroup: failed to open /acct/uid_10072/pid_5880/cgroup.procs: No such file or directory
08-03 19:09:51.449  6643  6718 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
08-03 19:09:51.455  6705  6705 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
08-03 19:09:51.457  6643  6643 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-03 19:09:51.471  6705  6705 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-03 19:09:51.475  6454  6454 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-03 19:09:51.477  6643  6643 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-03 19:09:51.482  6643  6643 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-03 19:09:51.485  6643  6643 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-03 19:09:51.488  6643  6643 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-03 19:09:51.488  6643  6643 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-03 19:09:51.504  6643  6643 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-03 19:09:51.507  6454  6454 D PostponalbeReceiver: OasPackageInstalledReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-03 19:09:51.509  1031  1725 I ActivityManager: Killing 5690:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-03 19:09:51.521  5666  5666 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-03 19:09:51.522  5666  5666 W System.err: android.os.DeadObjectException
08-03 19:09:51.522  5666  5666 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-03 19:09:51.522  5666  5666 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-03 19:09:51.522  5666  5666 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-03 19:09:51.522  5666  5666 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-03 19:09:51.522  5666  5666 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-03 19:09:51.522  5666  5666 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-03 19:09:51.522  5666  5666 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-03 19:09:51.522  5666  5666 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-03 19:09:51.523  5666  5666 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-03 19:09:51.523  5666  5666 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-03 19:09:51.523  5666  5666 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 19:09:51.523  5666  5666 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-03 19:09:51.523  5666  5666 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-03 19:09:51.523  5666  5666 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-03 19:09:51.523  5666  5666 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-03 19:09:51.523  5666  5666 W System.err: android.os.DeadObjectException
08-03 19:09:51.523  5666  5666 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-03 19:09:51.523  5666  5666 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-03 19:09:51.523  5666  5666 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-03 19:09:51.523  5666  5666 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-03 19:09:51.524  5666  5666 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-03 19:09:51.524  5666  5666 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-03 19:09:51.524  5666  5666 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-03 19:09:51.524  5666  5666 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-03 19:09:51.524  5666  5666 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-03 19:09:51.524  5666  5666 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-03 19:09:51.524  5666  5666 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 19:09:51.524  5666  5666 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-03 19:09:51.524  5666  5666 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-03 19:09:51.524  5666  5666 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-03 19:09:51.524  5666  5666 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-03 19:09:51.524  5666  5666 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-03 19:09:51.572  1031  1090 W ActivityManager: Activity pause timeout for ActivityRecord{891d412 u0 com.test.thalitest/.MainActivity t40}
08-03 19:09:51.574  1031  1941 W libprocessgroup: failed to open /acct/uid_1000/pid_5690/cgroup.procs: No such file or directory
08-03 19:09:51.574  1031  1941 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-03 19:09:51.576  6643  6643 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-03 19:09:51.576  6643  6643 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-03 19:09:51.577  5666  5666 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-03 19:09:51.577  5666  5666 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-03 19:09:51.624  1031  1902 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6744 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-03 19:09:51.628  5666  5666 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-03 19:09:51.631  6643  6754 D OpenGLRenderer: Render dirty regions requested: true
08-03 19:09:51.631  6643  6754 I OpenGLRenderer: Initialized EGL, version 1.4
08-03 19:09:51.636  6643  6754 D OpenGLRenderer: Enabling debug mode 0
08-03 19:09:51.647  6643  6643 D Atlas   : Validating map...
08-03 19:09:51.651  1031  1046 D SplitWindow: check instance of lgWin Window{2027391f u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-03 19:09:51.701  6744  6744 D UEI.SmartControl: Quickset Services start...
08-03 19:09:51.703  6744  6744 I UEI.SmartControl: Manufacture = LGE
08-03 19:09:51.703  6744  6744 D UEI.SmartControl: Id = LGNevo
08-03 19:09:51.705  6744  6744 D UEI.SmartControl: File observer start...
08-03 19:09:51.705  6643  6742 D LgDataFeature: LgDataFeature() Constructor: none
08-03 19:09:51.705  6643  6742 D LgDataFeature: LgDataFeature() Constructor Done, null
08-03 19:09:51.705  6744  6744 E UEI.SmartControl: IR Port is disabled: false
08-03 19:09:51.706  6744  6744 D UEI.SmartControl: Starting file observer...
08-03 19:09:51.706  6744  6744 D UEI.SmartControl: Extracting JNI libs...
08-03 19:09:51.706  6744  6744 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-03 19:09:51.776  1031  1096 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +711ms (total +786ms)
08-03 19:09:51.776  1031  1096 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{891d412 u0 com.test.thalitest/.MainActivity t40} time:134256
08-03 19:09:51.776  6643  6643 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3c1742c0 time:134256
08-03 19:09:51.799  6744  6744 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-03 19:09:51.799  6744  6744 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-03 19:09:51.800  6744  6744 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
08-03 19:09:51.824  6744  6744 I UEI.SmartControl: --- Selecting new region: 6
08-03 19:09:51.825  6744  6744 I UEI.SmartControl: Model = LG-D855
08-03 19:09:51.826  6744  6744 D UEI.SmartControl: QS Service created
08-03 19:09:51.849  6744  6744 I UEI.SmartControl: Service initServices...
08-03 19:09:51.853  6744  6744 D UEI.SmartControl: QS start get config
08-03 19:09:51.897  6744  6744 D UEI.SmartControl: Loading JNI Libs...
08-03 19:09:51.929  6643  6643 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-03 19:09:52.002  6643  6742 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-03 19:09:52.002  6643  6742 I chromium: 
,08-03 19:09:52.070  6643  6771 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435145216
,08-03 19:09:52.080  6643  6771 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-03 19:09:52.080  6643  6771 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-03 19:09:52.080  6643  6771 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-03 19:09:52.080  6643  6771 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-03 19:09:52.080  6643  6771 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-03 19:09:52.080  6643  6771 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e48b84 added. We now have 1 listener(s)
08-03 19:09:52.083  1031  2040 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-03 19:09:52.085  6643  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-03 19:09:52.087  6643  6771 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 19:09:52.087  6643  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 19:09:52.088  6643  6771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 19:09:52.092  6643  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-03 19:09:52.092  6643  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-03 19:09:52.092  6643  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-03 19:09:52.092  6643  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-03 19:09:52.092  6643  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-03 19:09:52.092  6643  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-03 19:09:52.092  6643  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-03 19:09:52.092  6643  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-03 19:09:52.092  6643  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-03 19:09:52.092  6643  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-03 19:09:52.092  6643  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-03 19:09:52.092  6643  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-03 19:09:52.092  6643  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-03 19:09:52.092  6643  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-03 19:09:52.092  6643  6771 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3883bc33 added. We now have 1 listener(s)
08-03 19:09:52.093  6643  6771 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 19:09:52.098  1031  1542 D WifiService: New client listening to asynchronous messages
,08-03 19:09:52.101  6643  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-03 19:09:52.101  6643  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-03 19:09:52.102  6643  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-03 19:09:52.102  6643  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-03 19:09:52.103  6643  6771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-03 19:09:52.107  6643  6771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 19:09:52.107  1031  1975 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:09:52.108  6643  6771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-03 19:09:52.121  6643  6771 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-03 19:09:52.123  6643  6771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 19:09:52.123  6643  6771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:09:52.123  6643  6771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:09:52.123  6643  6771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:09:52.123  6643  6771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:09:52.123  6643  6771 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 19:09:52.123  6643  6771 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 19:09:52.123  6643  6771 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 19:09:52.123  6643  6771 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-03 19:09:52.123  6643  6771 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 19:09:52.124  6643  6771 I io.jxcore.node.LifeCycleMonitor: start: OK
08-03 19:09:52.126  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:09:52.128  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:09:52.135  6643  6643 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-03 19:09:52.135  6643  6643 I chromium: 
,08-03 19:09:52.152  6643  6643 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-03 19:09:52.247  6744  6744 I UEI.SmartControl: Supports setup maps: true
,08-03 19:09:52.253  6744  6744 D UEI.SmartControl: QS start statue = true Error code = 0
08-03 19:09:52.253  6744  6744 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-03 19:09:52.253  6744  6744 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-03 19:09:52.253  6744  6744 I UEI.SmartControl: ### init IR Blaster...
08-03 19:09:52.259  6744  6744 D serial_port: Configuring serial port
08-03 19:09:52.263  6744  6744 E UEI.SmartControl: UEIBLaster setting for 616
08-03 19:09:52.263  6744  6744 I UEI.SmartControl: Setting serial record hearder size = 2
08-03 19:09:52.264  6744  6744 I UEI.SmartControl: configuring settings for MAXQ616
08-03 19:09:52.264  6744  6744 I UEI.SmartControl: Get version...
,08-03 19:09:52.272   330   361 E GBMv2   : DFP En is all cleared set to be enabled
08-03 19:09:52.273   330   361 E GBMv2   : Set value is all cleared set the max
08-03 19:09:52.273   330   361 I GBMv2   : DFP Enabled. Ignore VFP set
08-03 19:09:52.280  6744  6775 D UEI.SmartControl: serial port data available: 21
,08-03 19:09:52.313  6744  6744 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-03 19:09:52.314  6744  6744 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-03 19:09:52.314  6744  6744 I UEI.SmartControl: QS saving settings...
,08-03 19:09:52.316  6744  6744 D UEI.SmartControl: IR Blaster version: 25672567
08-03 19:09:52.338  6744  6775 D UEI.SmartControl: serial port data available: 4
,08-03 19:09:52.374  6744  6778 I UEI.SmartControl: Device manager: loading config....
08-03 19:09:52.374  6744  6744 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-03 19:09:52.375  6744  6778 D UEI.SmartControl: ----------- loading internal config...
08-03 19:09:52.377  6744  6744 E UEI.SmartControl: Services init done
08-03 19:09:52.377  6744  6744 D UEI.SmartControl: QS Service init finished
,08-03 19:09:52.383  6744  6744 D UEI.SmartControl: QS Service version name: 2.1.91
08-03 19:09:52.383  6744  6744 D UEI.SmartControl: QS Service version code: 201091
08-03 19:09:52.385  6744  6744 D UEI.SmartControl: Service requested: Control
08-03 19:09:52.391  6744  6778 E UEI.SmartControl: Loading SETTINGS...
,08-03 19:09:52.395  6744  6744 D UEI.SmartControl: Request IControl service: devices are loaded...
08-03 19:09:52.398  1031  1574 I ActivityManager: Killing 5666:com.lge.qremote/u0a112 (adj 15): empty #17
08-03 19:09:52.401  6744  6778 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-03 19:09:52.424  6744  6777 I UEI.SmartControl: Notify AllClients services are ready: 0
08-03 19:09:52.424  6744  6777 D UEI.SmartControl: -----service ready thread exits
,08-03 19:09:52.472  1031  2010 W libprocessgroup: failed to open /acct/uid_10112/pid_5666/cgroup.procs: No such file or directory
,08-03 19:09:52.476  6744  6744 D UEI.SmartControl: Internal service binding...
08-03 19:09:53.046  6643  6774 W jxcore-log: Initializing JXcore engine
,08-03 19:09:53.046  6643  6774 W jxcore-log: JXcore engine is ready
08-03 19:09:53.087  6774  6774 W Thread-756: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10340]" dev="sockfs" ino=10340 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-03 19:09:53.087  6774  6774 W Thread-756: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2864 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,08-03 19:09:53.087  6774  6774 W Thread-756: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[9551]" dev="sockfs" ino=9551 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-03 19:09:53.087  6774  6774 W Thread-756: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-03 19:09:53.087  6774  6774 W Thread-756: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[31508]" dev="sockfs" ino=31508 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-03 19:09:53.103  6643  6774 W jxcore-log: Starting JXcore engine
08-03 19:09:53.179  6643  6774 W jxcore-log: Platform android
08-03 19:09:53.179  6643  6774 W jxcore-log: 
08-03 19:09:53.179  6643  6774 W jxcore-log: Process ARCH arm
08-03 19:09:53.179  6643  6774 W jxcore-log: 
,08-03 19:09:53.491  6643  6774 I jxcore-log: JXcore Cordova bridge is ready!
08-03 19:09:53.491  6643  6774 I jxcore-log: 
,08-03 19:09:53.491  6643  6774 W jxcore-log: JXcore engine is started
,08-03 19:09:53.504  6643  6771 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-03 19:09:53.508  6643  6643 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-03 19:09:53.612  2150  2150 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,08-03 19:09:53.612  2150  2150 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,08-03 19:09:55.007  6586  6586 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-03 19:09:55.013  1031  1975 I ActivityManager: Killing 6294:com.android.calendar/u0a13 (adj 15): empty #17
08-03 19:09:55.094  1031  2030 W libprocessgroup: failed to open /acct/uid_10013/pid_6294/cgroup.procs: No such file or directory
,08-03 19:09:56.007  6586  6638 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-03 19:09:57.373  6744  6779 D UEI.SmartControl: Internal timer expired: 1
,08-03 19:09:57.373  6744  6779 D UEI.SmartControl: unbind internal service
,08-03 19:09:57.409  6744  6744 D UEI.SmartControl: Service.onUnbind: IControl
08-03 19:09:57.415  6744  6776 D serial_port: close(fd = 25)
08-03 19:09:57.419  6744  6776 I UEI.SmartControl: Serial port is closed.
,08-03 19:09:57.421  6744  6744 D UEI.SmartControl: Service.onDestroy
08-03 19:09:57.421  6744  6744 D UEI.SmartControl: Lock is in USE false
08-03 19:09:57.421  6744  6744 D UEI.SmartControl: unbind internal service
08-03 19:09:57.422  6744  6744 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@12f57e89
08-03 19:09:57.422  6744  6744 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-03 19:09:57.422  6744  6744 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-03 19:09:57.422  6744  6744 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-03 19:09:57.422  6744  6744 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-03 19:09:57.422  6744  6744 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-03 19:09:57.422  6744  6744 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-03 19:09:57.422  6744  6744 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-03 19:09:57.422  6744  6744 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-03 19:09:57.422  6744  6744 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 19:09:57.422  6744  6744 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-03 19:09:57.422  6744  6744 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-03 19:09:57.422  6744  6744 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 19:09:57.423  6744  6744 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-03 19:09:57.423  6744  6744 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-03 19:09:57.423  6744  6744 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-03 19:09:57.423  6744  6744 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@12f57e89
08-03 19:09:57.423  6744  6744 I UEI.SmartControl: Serial port is closed.
08-03 19:09:57.423  6744  6744 I UEI.SmartControl: Serial port is closed.
08-03 19:09:57.423  6744  6744 D UEI.SmartControl: Blaster closed
08-03 19:09:57.423  6744  6744 D UEI.SmartControl: Shut down QS...
08-03 19:09:57.423  6744  6744 D UEI.SmartControl: Stopping QS lib
08-03 19:09:57.423  6744  6744 D UEI.SmartControl: QS lib stop result = true
08-03 19:09:57.423  6744  6744 D UEI.SmartControl: Stopped QS lib
08-03 19:09:57.424  6744  6744 D UEI.SmartControl: Stopped file observer...
08-03 19:09:57.424  6744  6744 D UEI.SmartControl: QS shutdown complete
,08-03 19:10:00.000  1031  1374 D PowerManagerServiceEx: acquireWakeLockInternal: lock=799958746, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,08-03 19:10:00.033  2598  2598 D [Concierge]Service: onStartCommand(). Type : 9
,08-03 19:10:00.057  1031  1031 D PowerManagerServiceEx: releaseWakeLockInternal: lock=799958746 [*alarm*], flags=0x0
08-03 19:10:00.058  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-03 19:10:00.058  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-03 19:10:00.058  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-03 19:10:00.058  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
08-03 19:10:00.059  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-03 19:10:00.059  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-03 19:10:00.060  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
,08-03 19:10:00.062  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
08-03 19:10:00.083  4488  6811 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,08-03 19:10:03.730  1031  1090 I ActivityManager: Waited long enough for: ServiceRecord{1ebc868b u0 com.google.android.gms/.wearable.service.WearableService}
,08-03 19:10:06.493  1031  1374 V AlarmManager: RTC_WAKEUP set : Alarm{1abe0aa5 type 0 when 1470244204155 com.android.vending} when 1470244204155
,08-03 19:10:06.558  1031  1046 V SIM_STK : Menu title from STK is T-Mobile
,08-03 19:10:06.674  6128  6128 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-03 19:10:10.427  6643  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-03 19:10:10.427  6643  6774 I jxcore-log: 
,08-03 19:10:10.430  6643  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-03 19:10:10.430  6643  6774 I jxcore-log: 
08-03 19:10:10.435  6643  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 19:10:10.435  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:10:10.435  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:10:10.435  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:10:10.435  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:10:10.435  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 19:10:10.435  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 19:10:10.435  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 19:10:10.438  6643  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 19:10:10.440  6643  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-03 19:10:10.440  6643  6774 I jxcore-log: 
08-03 19:10:10.441  6643  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-03 19:10:10.441  6643  6774 I jxcore-log: 
,08-03 19:10:10.775  6643  6774 D ExecuteNativeTests: Running unit tests
,08-03 19:10:10.861  6643  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-03 19:10:10.861  6643  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32e7182d added. We now have 2 listener(s)
,08-03 19:10:10.862  1031  1975 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-03 19:10:10.864  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 19:10:10.864  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 19:10:10.864  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 19:10:10.864  6643  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 19:10:10.864  6643  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35913162 added. We now have 2 listener(s)
08-03 19:10:10.864  6643  6774 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-03 19:10:10.865  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported,
08-03 19:10:10.867  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 19:10:10.868  6643  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,08-03 19:10:10.868  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:10:10.868  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:10:10.868  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
,08-03 19:10:10.868  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:10:10.868  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 19:10:10.868  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
,08-03 19:10:10.868  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 19:10:10.869  6643  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-03 19:10:10.870  6643  6774 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 19:10:10.872  6643  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-03 19:10:10.873  6643  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-03 19:10:10.873  6643  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1,
08-03 19:10:10.874  6643  6774 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-03 19:10:10.875  6643  6774 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-03 19:10:10.875  6643  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-03 19:10:10.875  6643  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-03 19:10:10.875  6643  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-03 19:10:10.875  6643  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:10:10.876  6643  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:10:10.876  6643  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:10:10.876  6643  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:10:10.877  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:10.877  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 19:10:10.877  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 19:10:10.877  6643  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32e7182d removed from the list
08-03 19:10:10.877  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:10.877  6643  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35913162 removed from the list
08-03 19:10:10.877  6643  6774 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:10:10.877  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:10.878  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:10.878  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:10.878  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:10:10.878  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:10:10.878  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:10.878  6643  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35913162 not in the list
08-03 19:10:10.880  6643  6774 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-03 19:10:10.881  6643  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:10:10.881  6643  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:10:10.881  6643  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this opera,tion, skipping...
08-03 19:10:10.881  6643  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:10:10.881  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:10.881  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:10.881  6643  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32e7182d not in the list
08-03 19:10:10.881  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:10.881  6643  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35913162 not in the list
08-03 19:10:10.881  6643  6774 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:10:10.881  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:10.881  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:10.881  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:10.881  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 19:10:10.882  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:10:10.882  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:10:10.882  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:10.882  6643  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35913162 not in the list
08-03 19:10:10.888  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-03 19:10:10.888  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-03 19:10:10.888  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-03 19:10:10.888  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-03 19:10:10.888  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-03 19:10:10.888  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-03 19:10:10.888  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-03 19:10:10.888  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-03 19:10:10.888  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-03 19:10:10.888  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-03 19:10:10.888  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-03 19:10:10.888  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-03 19:10:10.888  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-03 19:10:10.888  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-03 19:10:10.888  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-03 19:10:10.888  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-03 19:10:10.888  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-03 19:10:10.888  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-03 19:10:10.888  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-03 19:10:10.888  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-03 19:10:10.888  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-03 19:10:10.888  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-03 19:10:10.888  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-03 19:10:10.888  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoing,Connections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-03 19:10:10.888  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-03 19:10:10.888  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-03 19:10:10.888  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-03 19:10:10.888  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-03 19:10:10.888  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-03 19:10:10.888  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-03 19:10:10.889  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-03 19:10:10.889  6643  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:10:10.889  6643  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:10:10.889  6643  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:10:10.889  6643  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:10:10.889  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:10.889  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:10.889  6643  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32e7182d not in the list
08-03 19:10:10.889  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:10.889  6643  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35913162 not in the list
08-03 19:10:10.889  6643  6774 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:10:10.889  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:10.889  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:10.889  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:10.889  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:10.889  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:10:10.890  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:10:10.890  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:10.890  6643  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35913162 not in the list
08-03 19:10:10.890  6643  6774 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-03 19:10:10.892  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 19:10:10.894  6643  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 19:10:10.894  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:10:10.894  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:10:10.894  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:10:10.894  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:10:10.894  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 19:10:10.894  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 19:10:10.894  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 19:10:10.895  6643  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 19:10:10.895  6643  6774 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 19:10:10.896  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:10:10.897  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:10:10.897  6643  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 19:10:10.897  6643  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-03 19:10:10.897  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-03 19:10:10.897  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 19:10:10.897  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-03 19:10:10.900  6643  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-03 19:10:10.900  1031  1975 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:10:10.904  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-03 19:10:10.907  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-03 19:10:10.908  6643  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-03 19:10:10.909  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-03 19:10:10.910  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 19:10:10.911  6643  6774 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-03 19:10:10.911  6643  6774 I io.jxcore.node.ConnectionHelper: start: OK
08-03 19:10:10.913  6643  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:10:10.913  6643  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:10:10.913  6643  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:10:10.914  6643  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:10:10.914  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:10.914  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 19:10:10.914  6643  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32e7182d not in the list
08-03 19:10:10.914  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:10.914  6643  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35913162 not in the list
08-03 19:10:10.914  6643  6774 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:10:10.914  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:10.914  6643  6774 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-03 19:10:10.915  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 19:10:10.917  6643  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 19:10:10.917  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:10:10.917  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:10:10.917  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:10:10.917  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:10:10.917  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 19:10:10.917  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 19:10:10.917  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 19:10:10.918  6643  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 19:10:10.918  6643  6774 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 19:10:10.919  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:10:10.920  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:10:10.921  6643  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 19:10:10.921  6643  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-03 19:10:10.921  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-03 19:10:10.921  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 19:10:10.921  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-03 19:10:10.924  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-03 19:10:10.924  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 19:10:10.925  6643  6774 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-03 19:10:10.925  6643  6774 I io.jxcore.node.ConnectionHelper: start: OK
08-03 19:10:10.926  6643  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:10:10.926  6643  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:10:10.926  6643  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:10:10.926  6643  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:10:10.926  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:10.926  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 19:10:10.926  6643  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32e7182d not in the list
08-03 19:10:10.926  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:10.926  6643  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35913162 not in the list
08-03 19:10:10.926  6643  6774 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:10:10.926  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:10.926  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:10.926  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:10.927  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:10:10.927  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:10:10.928  6643  6774 D BluetoothLeScanner: could not find callback wrapper
08-03 19:10:10.928  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 19:10:10.928  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:10.928  6643  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35913162 not in the list
08-03 19:10:10.928  6643  6774 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-03 19:10:10.930  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 19:10:10.932  6643  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 19:10:10.932  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:10:10.932  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:10:10.932  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:10:10.932  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:10:10.932  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 19:10:10.932  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 19:10:10.932  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 19:10:10.933  6643  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 19:10:10.933  6643  6774 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 19:10:10.934  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:10:10.935  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:10:10.935  6643  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 19:10:10.935  6643  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-03 19:10:10.935  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-03 19:10:10.935  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 19:10:10.935  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-03 19:10:10.938  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-03 19:10:10.938  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 19:10:10.939  6643  6774 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-03 19:10:10.939  6643  6774 I io.jxcore.node.ConnectionHelper: start: OK
08-03 19:10:10.939  6643  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:10:10.939  6643  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:10:10.939  6643  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:10:10.940  6643  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:10:10.940  6643  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:10:10.940  6643  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:10:10.940  6643  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:10:10.940  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:10.940  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 19:10:10.940  6643  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32e7182d not in the list
08-03 19:10:10.940  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:10.940  6643  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35913162 not in the list
08-03 19:10:10.940  6643  6774 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:10:10.940  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:10.941  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:10.941  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:10.941  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:10:10.941  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:10:10.942  6643  6774 D BluetoothLeScanner: could not find callback wrapper
08-03 19:10:10.942  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 19:10:10.942  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:10.942  6643  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35913162 not in the list
08-03 19:10:10.942  6643  6774 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-03 19:10:10.942  6643  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:10:10.942  6643  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:10:10.942  6643  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:10:10.943  6643  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:10:10.943  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:10.943  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:10.943  6643  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32e7182d not in the list
08-03 19:10:10.943  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:10.943  6643  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35913162 not in the list
08-03 19:10:10.943  6643  6774 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:10:10.943  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:10.943  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:10.943  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:10.943  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:10.943  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:10:10.944  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:10:10.944  6643  6774 D BluetoothLeScanner: could not find callback wrapper
08-03 19:10:10.944  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 19:10:10.944  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:10.944  6643  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35913162 not in the list
08-03 19:10:10.945  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-03 19:10:10.945  6643  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:10:10.945  6643  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:10:10.945  6643  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:10:10.945  6643  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:10:10.945  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:10.945  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:10.945  6643  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32e7182d not in the list
08-03 19:10:10.945  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:10.945  6643  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35913162 not in the list
08-03 19:10:10.945  6643  6774 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:10:10.945  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:10.945  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:10.945  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:10.945  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:10.946  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:10:10.946  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:10:10.946  6643  6774 D BluetoothLeScanner: could not find callback wrapper
08-03 19:10:10.946  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 19:10:10.946  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:10.946  6643  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35913162 not in the list
08-03 19:10:10.947  6643  6774 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-03 19:10:10.947  6643  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:10:10.947  6643  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:10:10.947  6643  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:10:10.947  6643  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:10:10.947  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:10.947  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:10.947  6643  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32e7182d not in the list
08-03 19:10:10.947  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:10.948  6643  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35913162 not in the list
08-03 19:10:10.948  6643  6774 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:10:10.948  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:10.948  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:10.948  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:10.948  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:10.948  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:10:10.948  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:10:10.949  6643  6774 D BluetoothLeScanner: could not find callback wrapper
08-03 19:10:10.949  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 19:10:10.949  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:10.949  6643  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35913162 not in the list
08-03 19:10:10.949  6643  6774 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-03 19:10:10.949  6643  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:10:10.949  6643  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:10:10.949  6643  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:10:10.950  6643  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:10:10.950  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:10.950  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:10.950  6643  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32e7182d not in the list
08-03 19:10:10.950  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:10.950  6643  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35913162 not in the list
08-03 19:10:10.950  6643  6774 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:10:10.950  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:10.950  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:10.950  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:10.950  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:10.951  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:10:10.951  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:10:10.951  6643  6774 D BluetoothLeScanner: could not find callback wrapper
08-03 19:10:10.951  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 19:10:10.951  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:10.951  6643  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35913162 not in the list
08-03 19:10:10.952  6643  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-03 19:10:10.953  6643  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-03 19:10:10.953  6643  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-03 19:10:10.953  6643  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-03 19:10:10.953  6643  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-03 19:10:10.953  6643  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-03 19:10:10.953  6643  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:10:10.953  6643  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:10:10.953  6643  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:10:10.953  6643  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:10:10.953  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:10.953  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:10.953  6643  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32e7182d not in the list
08-03 19:10:10.953  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:10.954  6643  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35913162 not in the list
08-03 19:10:10.954  6643  6774 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:10:10.954  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:10.954  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:10.954  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:10.954  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:10.954  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:10:10.954  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:10:10.955  6643  6774 D BluetoothLeScanner: could not find callback wrapper
08-03 19:10:10.955  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 19:10:10.955  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:10.955  6643  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35913162 not in the list
08-03 19:10:10.955  6643  6774 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-03 19:10:10.955  6643  6774 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-03 19:10:10.955  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-03 19:10:10.957  6643  6774 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-03 19:10:10.957  6643  6774 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-03 19:10:10.958  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-03 19:10:10.958  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-03 19:10:10.958  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-03 19:10:10.958  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-03 19:10:10.958  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-03 19:10:10.958  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-03 19:10:10.958  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-03 19:10:10.958  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-03 19:10:10.958  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-03 19:10:10.958  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-03 19:10:10.958  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-03 19:10:10.958  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-03 19:10:10.958  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-03 19:10:10.958  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-03 19:10:10.958  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-03 19:10:10.958  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-03 19:10:10.958  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-03 19:10:10.958  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-03 19:10:10.958  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-03 19:10:10.958  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-03 19:10:10.958  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-03 19:10:10.958  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-03 19:10:10.958  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-03 19:10:10.958  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-03 19:10:10.958  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-03 19:10:10.958  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-03 19:10:10.958  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-03 19:10:10.958  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-03 19:10:10.958  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-03 19:10:10.958  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-03 19:10:10.958  6643  6774 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-03 19:10:10.958  6643  6774 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-03 19:10:10.958  6643  6774 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-03 19:10:10.959  6643  6774 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-03 19:10:10.959  6643  6774 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-03 19:10:10.959  6643  6774 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-03 19:10:10.959  6643  6774 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-03 19:10:10.959  6643  6774 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-03 19:10:10.959  6643  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-03 19:10:10.961  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-03 19:10:10.962  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-03 19:10:10.962  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-03 19:10:10.962  6643  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-03 19:10:10.962  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-03 19:10:10.962  6643  6774 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-03 19:10:10.963  6643  6774 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-03 19:10:10.963  6643  6774 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-03 19:10:10.963  6643  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:10:10.963  6643  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:10:10.963  6643  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:10:10.964  6643  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:10:10.964  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:10.964  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:10.964  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-03 19:10:10.967  6643  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32e7182d not in the list
08-03 19:10:10.967  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:10.967  6643  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35913162 not in the list
08-03 19:10:10.967  6643  6774 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:10:10.967  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:10.967  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:10.968  6643  6858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 820)
08-03 19:10:10.968  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:10.968  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:10.971  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:10:10.971  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:10:10.972  6643  6774 D BluetoothLeScanner: could not find callback wrapper
08-03 19:10:10.972  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 19:10:10.972  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:10.972  6643  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35913162 not in the list
08-03 19:10:10.974  6643  6774 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-03 19:10:10.975  6643  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:10:10.975  6643  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:10:10.975  6643  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:10:10.976  6643  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:10:10.976  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:10.976  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:10.976  6643  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32e7182d not in the list
08-03 19:10:10.976  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:10.976  6643  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35913162 not in the list
08-03 19:10:10.976  6643  6774 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:10:10.976  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:10.977  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:10.977  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:10.977  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:10.978  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:10:10.978  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:10:10.978  6643  6774 D BluetoothLeScanner: could not find callback wrapper
08-03 19:10:10.979  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 19:10:10.979  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:10.979  6643  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35913162 not in the list
08-03 19:10:10.979  6643  6774 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-03 19:10:10.980  6643  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:10:10.980  6643  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:10:10.980  6643  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:10:10.983  6643  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-03 19:10:10.984  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:10.984  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:10.984  6643  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32e7182d not in the list
08-03 19:10:10.984  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:10.984  6643  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35913162 not in the list
08-03 19:10:10.984  6643  6774 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:10:10.984  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:10.984  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:10.984  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:10.984  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:10.985  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:10:10.985  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:10:10.985  6643  6774 D BluetoothLeScanner: could not find callback wrapper
08-03 19:10:10.985  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 19:10:10.985  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:10.985  6643  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35913162 not in the list
08-03 19:10:10.986  6643  6774 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-03 19:10:10.986  6643  6774 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-03 19:10:10.986  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-03 19:10:10.986  6643  6774 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-03 19:10:10.986  6643  6774 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-03 19:10:10.986  6643  6859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 820
08-03 19:10:10.986  6643  6774 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-03 19:10:10.987  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-03 19:10:10.987  6643  6859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 820)
08-03 19:10:10.987  6643  6774 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-03 19:10:10.987  6643  6774 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-03 19:10:10.987  6643  6774 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to, find an outgoing connection to peer with ID 00:11:22:33:44:55
08-03 19:10:10.987  6643  6859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 820)
08-03 19:10:10.987  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-03 19:10:10.987  6643  6774 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-03 19:10:10.987  6643  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:10:10.987  6643  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:10:10.987  6643  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:10:10.988  6643  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:10:10.988  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:10.988  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:10.988  6643  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32e7182d not in the list
08-03 19:10:10.988  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:10.988  6643  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35913162 not in the list
08-03 19:10:10.988  6643  6774 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:10:10.988  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:10.988  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:10.988  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:10.988  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:10.989  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:10:10.989  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:10:10.989  6643  6774 D BluetoothLeScanner: could not find callback wrapper
08-03 19:10:10.989  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 19:10:10.989  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:10.989  6643  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35913162 not in the list
08-03 19:10:10.990  6643  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:10:10.990  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:10.990  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:10.990  6643  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32e7182d not in the list
08-03 19:10:10.990  6643  6,774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:10.990  6643  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35913162 not in the list
08-03 19:10:10.990  6643  6774 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:10:10.990  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:10.990  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:10.990  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:10.990  6643  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35913162 not in the list
08-03 19:10:10.990  6643  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:10:10.990  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:10.991  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:10.991  6643  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32e7182d not in the list
08-03 19:10:10.991  6643  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:10:10.991  6643  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:10:10.991  6643  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:10:10.991  6643  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:10:10.991  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:10.991  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:10.991  6643  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32e7182d not in the list
08-03 19:10:10.991  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:10.991  6643  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35913162 not in the list
08-03 19:10:10.991  6643  6774 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:10:10.991  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:10.991  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:10.991  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:10.991  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:10.992  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:10:10.992  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:10:10.992  6643  6774 D BluetoothLeScanner: could not find callback wrapper
08-03 19:10:10.992  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 19:10:10.992  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:10.992  6643  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35913162 not in the list
08-03 19:10:10.994  6643  6774 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-03 19:10:10.994  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 19:10:10.994  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-03 19:10:10.995  6643  6774 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-03 19:10:10.995  6643  6774 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-03 19:10:10.995  6643  6643 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-03 19:10:10.995  6643  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-03 19:10:10.996  6643  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-03 19:10:10.996  6643  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:10:10.996  6643  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-03 19:10:10.996  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-03 19:10:10.996  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-03 19:10:10.996  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:10.996  6643  6774 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-03 19:10:10.997  6643  6643 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-03 19:10:10.997  6643  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32e7182d not in the list
08-03 19:10:10.997  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:10.997  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-03 19:10:10.997  6643  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-03 19:10:10.997  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-03 19:10:10.997  6643  6869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-03 19:10:10.998  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-03 19:10:10.998  6643  6869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-03 19:10:10.998  6643  6774 D BluetoothLeScanner: could not find callback wrapper
08-03 19:10:10.998  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 19:10:10.998  6643  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-03 19:10:10.998  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:10.998  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:10.999  6643  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 19:10:10.999  6643  6643 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 19:10:10.999  6643  6643 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 19:10:10.999  6643  6643 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-03 19:10:10.999  6643  6643 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 19:10:10.999  6643  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35913162 not in the list
08-03 19:10:10.999  6643  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:10:10.999  6643  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:10:10.999  6643  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:10:10.999  6643  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:10:10.999  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:10.999  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:10.999  6643  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32e7182d not in the list
08-03 19:10:10.999  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:10.999  6643  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35913162 not in the list
08-03 19:10:10.999  6643  6774 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:10:10.999  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:10.999  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:10.999  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:10.999  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:11.000  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:10:11.000  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:10:11.000  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:11.000  6643  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35913162 not in the list
08-03 19:10:11.001  6643  6774 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-03 19:10:11.001  6643  6774 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-03 19:10:11.002  6643  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-03 19:10:11.003  6643  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-03 19:10:11.003  6643  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:10:11.003  6643  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:10:11.003  6643  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:10:11.003  6643  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:10:11.003  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:11.003  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:11.003  6643  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32e7182d not in the list
08-03 19:10:11.003  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:11.003  6643  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35913162 not in the list
08-03 19:10:11.003  6643  6774 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:10:11.003  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:11.003  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:11.003  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:11.003  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:11.004  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:10:11.004  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:10:11.004  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:11.004  6643  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35913162 not in the list
08-03 19:10:11.004  1031  1574 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:10:11.005  1031  1725 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:10:11.005  1031  1986 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:10:11.006  6643  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:10:11.006  6643  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:10:11.006  6643  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:10:11.006  6643  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:10:11.006  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:11.006  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:11.006  6643  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32e7182d not in the list
08-03 19:10:11.006  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:11.006  6643  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35913162 not in the list
08-03 19:10:11.006  6643  6774 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:10:11.006  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:11.006  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:11.006  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:11.006  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:11.007  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:10:11.007  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:10:11.007  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:11.007  6643  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35913162 not in the list
08-03 19:10:11.007  6643  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:10:11.007  6643  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:10:11.007  6643  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:10:11.008  6643  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:10:11.008  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:11.008  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:11.008  6643  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32e7182d not in the list
08-03 19:10:11.008  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:11.008  6643  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35913162 not in the list
08-03 19:10:11.008  6643  6774 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:10:11.008  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:11.008  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:11.008  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:11.008  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:11.008  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:10:11.008  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:10:11.008  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:11.008  6643  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35913162 not in the list
08-03 19:10:11.009  6643  6774 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-03 19:10:11.009  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-03 19:10:11.010  6643  6774 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-03 19:10:11.010  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-03 19:10:11.010  6643  6774 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-03 19:10:11.010  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-03 19:10:11.011  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-03 19:10:11.011  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-03 19:10:11.012  6643  6774 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-03 19:10:11.012  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-03 19:10:11.012  6643  6774 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-03 19:10:11.012  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-03 19:10:11.012  6643  6774 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-03 19:10:11.012  6643  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-03 19:10:11.013  6643  6774 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-03 19:10:11.013  6643  6774 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-03 19:10:11.021  6643  6774 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-03 19:10:11.021  6643  6774 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-03 19:10:11.021  6643  6774 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-03 19:10:11.021  6643  6774 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-03 19:10:11.022  6643  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 19:10:11.022  6643  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2152ed6b added. We now have 2 listener(s)
08-03 19:10:11.022  6643  6774 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 19:10:11.023  6643  6774 D BluetoothAdapter: enable(): BT is already enabled..!
08-03 19:10:11.024  1031  1046 D WifiServiceImplEx: setWifiEnabled: true pid=6643, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-03 19:10:11.024  1031  1046 D WifiService: setWifiEnabled: true pid=6643, uid=10118
08-03 19:10:11.024  1031  1046 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-03 19:10:11.025  6643  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 19:10:11.025  6643  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@67e0c8 added. We now have 3 listener(s)
08-03 19:10:11.026  6643  6774 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 19:10:11.028  6643  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 19:10:11.028  6643  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3567d561 added. We now have 4 listener(s)
08-03 19:10:11.028  6643  6774 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 19:10:11.030  6643  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 19:10:11.030  6643  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a3f9886 added. We now have 5 listener(s)
08-03 19:10:11.030  6643  6774 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 19:10:11.032  1031  1943 D WifiServiceImplEx: setWifiEnabled: false pid=6643, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-03 19:10:11.032  1031  1943 D WifiService: setWifiEnabled: false pid=6643, uid=10118
08-03 19:10:11.032  1031  1943 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-03 19:10:11.038  6643  6858 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-03 19:10:11.039  6643  6858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 820)
08-03 19:10:11.048  1031  2010 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-03 19:10:11.048  1031  2010 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@291b02f7 mBinding = false
08-03 19:10:11.048  1031  1537 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-03 19:10:11.048  1031  1537 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-03 19:10:11.048  1031  1537 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-03 19:10:11.048  1031  1537 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-03 19:10:11.049  1031  1537 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-03 19:10:11.049  1031  1537 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-03 19:10:11.049  1031  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-03 19:10:11.049  1031  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-03 19:10:11.050  1031  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-03 19:10:11.050  1031  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-03 19:10:11.050  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-03 19:10:11.050  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-03 19:10:11.050  1031  1031 D Ulp_jni : JNI:system_update. Event-4
08-03 19:10:11.057  1031  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-03 19:10:11.057  1031  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-03 19:10:11.057  1031  1536 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:11.057  1031  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:11.058  2704  2704 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-03 19:10:11.058  1031  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-03 19:10:11.058  1031  1537 D WifiNative-wlan0: doBoolean: SET ps 1
08-03 19:10:11.059  1031  1537 D WifiNative-wlan0: SET ps 1: returned true
08-03 19:10:11.060  1031  2841 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:11.060   305   891 D CommandListener: Clearing all IP addresses on wlan0
08-03 19:10:11.067  1031  1095 D BluetoothManagerService: Message: 2
08-03 19:10:11.068  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-03 19:10:11.068  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-03 19:10:11.068  1031  1031 D Ulp_jni : JNI:system_update. Event-4
08-03 19:10:11.069  1031  1095 D BluetoothManagerService: Sending off request.
08-03 19:10:11.069  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 19:10:11.070  3861  3880 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-03 19:10:11.071  3861  3943 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-03 19:10:11.071  3861  3943 D BluetoothAdapterProperties: Setting state to 13
08-03 19:10:11.071  3861  3943 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-03 19:10:11.071  3861  3943 D BluetoothAdapterProperties: onBluetoothDisable()
08-03 19:10:11.071  3861  3943 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-03 19:10:11.074  3861  3947 D BluetoothAdapterProperties: Scan Mode:20
08-03 19:10:11.074  3861  3943 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-03 19:10:11.075  3861  4160 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 19:10:11.075  3861  3943 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-03 19:10:11.075  3861  4013 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-03 19:10:11.075  3861  4199 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 19:10:11.076  3861  4013 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-03 19:10:11.077  3861  4194 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 19:10:11.078  3861  4197 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 19:10:11.079  1031  1095 D BluetoothManagerService: Message: 60
08-03 19:10:11.080  1031  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-03 19:10:11.080  1031  1095 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-03 19:10:11.081  3861  4158 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-03 19:10:11.081  3861  4158 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 19:10:11.081  3861  4158 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-03 19:10:11.081  3861  4158 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-03 19:10:11.081  3861  4158 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-03 19:10:11.081  3861  4158 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-03 19:10:11.081  3861  4158 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-03 19:10:11.081  3861  4158 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-03 19:10:11.082  3861  4013 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-03 19:10:11.082  3861  4013 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-03 19:10:11.082  3861  4013 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-03 19:10:11.082  3861  4013 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-03 19:10:11.082  3861  4013 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 19:10:11.082  3861  4013 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-03 19:10:11.082  3861  4013 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-03 19:10:11.082  3861  4013 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-03 19:10:11.082  3861  4013 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-03 19:10:11.082  3861  4013 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-03 19:10:11.082  3861  4013 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-03 19:10:11.083  3861  4013 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,08-03 19:10:11.086  1031  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-03 19:10:11.086  1031  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-03 19:10:11.093  1031  1943 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-03 19:10:11.093  1031  2840 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:11.093  1031  2840 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:11.094  1031  2840 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-03 19:10:11.094  1031  2840 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:11.094  1031  2840 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
08-03 19:10:11.098  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:10:11.098  6643  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 19:10:11.098  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:10:11.098  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:10:11.098  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:10:11.098  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 19:10:11.098  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 19:10:11.098  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 19:10:11.098  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 19:10:11.107  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:10:11.107  6643  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 19:10:11.108  6643  6774 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 19:10:11.111  1031  1090 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6877 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-03 19:10:11.114  1031  1536 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:11.114  1031  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:11.114  1031  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:10:11.114  1031  1536 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@319af9f3
08-03 19:10:11.114  1031  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:10:11.114  1031  1536 D LGWifiP2pService: P2pDisablingState
08-03 19:10:11.115  1031  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:10:11.115  1031  1536 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:11.115  1031  1536 D LGWifiP2pService: p2p socket connection lost
08-03 19:10:11.115  1031  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:10:11.115  1031  1536 D LGWifiP2pService: P2pDisabledState
08-03 19:10:11.115  1031  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:10:11.115  1031  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:10:11.117  3861  3861 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:10:11.118  3861  3861 D BluetoothMapService: STATE_TURNING_OFF
08-03 19:10:11.118  1939  1939 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:10:11.118  3861  3861 V BtOppService: Receiver DISABLED_ACTION 
08-03 19:10:11.118  3861  3861 V BluetoothMapService: Handler(): got msg=4
08-03 19:10:11.118  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-03 19:10:11.118  3861  3861 D BluetoothMapService: MAP Service closeService in
08-03 19:10:11.118  3861  3861 D BluetoothMapMasInstance: MAP Service shutdown
08-03 19:10:11.118  3861  3861 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-03 19:10:11.118  3861  3861 V BluetoothMapService: MAP Service closeService out
08-03 19:10:11.118  3861  3861 I BtOppRfcommListener: stopping Accept Thread
08-03 19:10:11.118  3861  3861 V BtOppRfcommListener: close mBtServerSocket
08-03 19:10:11.118  3861  3861 V BtOppRfcommListener: waiting for thread to terminate
08-03 19:10:11.118  6643  6643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:10:11.118  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:10:11.118  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:10:11.118  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:10:11.118  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:10:11.118  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 19:10:11.118  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:10:11.118  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:10:11.118  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 19:10:11.119  6643  6643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:10:11.119  6643  6643 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08,-03 19:10:11.120  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:10:11.120  3861  4194 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-03 19:10:11.121  3861  3861 V BtOppRfcommListener: done waiting for thread to terminate
08-03 19:10:11.122  6643  6643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:10:11.122  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:10:11.122  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:10:11.122  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:10:11.122  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:10:11.122  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 19:10:11.122  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:10:11.122  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:10:11.122  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 19:10:11.122  6643  6643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:10:11.122  6643  6643 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-03 19:10:11.125  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:10:11.126  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:10:11.127  1031  1537 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-03 19:10:11.127  1031  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:10:11.128  1031  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:10:11.128  1031  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:10:11.129  1031  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-03 19:10:11.129  1031  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-03 19:10:11.129  2704  2704 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-03 19:10:11.130  1031  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-03 19:10:11.130  1031  1537 D WifiNative-wlan0: doBoolean: SET ps 1
08-03 19:10:11.130  1031  1537 D WifiNative-wlan0: SET ps 1: returned true
08-03 19:10:11.130  1031  1536 D LGWifiP2pService: P2pDisabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:11.131  1031  1536 D LGWifiP2pService: DefaultState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:11.131  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:10:11.135   305   891 D CommandListener: Clearing all IP addresses on wlan0
08-03 19:10:11.135  1031  1543 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-03 19:10:11.135  1031  1543 D DSQN    : disableDataServiceNotify
08-03 19:10:11.135  1031  1543 D DSQN    : stop dsqn bin
,08-03 19:10:11.137   305  6890 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-03 19:10:11.137  1031  1093 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-03 19:10:11.139  1031  2840 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-03 19:10:11.150  1031  1090 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6897 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-03 19:10:11.151  1031  1031 D WifiHS20: hidePasspointNotification off =false
08-03 19:10:11.152  1939  1939 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-03 19:10:11.152  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:11.152  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:11.152  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-03 19:10:11.152  1031  1031 D WifiHS20: hidePasspointNotification off =false
08-03 19:10:11.154  1031  1374 V AlarmManager: ELAPSED_WAKEUP set : Alarm{c46c3d0 type 2 when 153604 com.google.android.gms} when 153604
08-03 19:10:11.154  1031  1537 D WifiNative-p2p0: doBoolean: TERMINATE
08-03 19:10:11.154  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:11.155  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:11.155  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-03 19:10:11.155  1031  1031 D WifiScanningService: SCAN_AVAILABLE : 1
08-03 19:10:11.155  1031  1537 D WifiNative-p2p0: TERMINATE: returned true
08-03 19:10:11.155  1031  1031 D RttService: SCAN_AVAILABLE : 1
08-03 19:10:11.155  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-03 19:10:11.155  1031  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-03 19:10:11.155  1031  1537 E WifiStateMachine: useWiFiOffloading() : false
08-03 19:10:11.155  1031  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-03 19:10:11.155  1939  1939 D WfdsService: WifiP2pState is changed : false
08-03 19:10:11.155  1031  1556 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:11.155  1031  1555 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:11.155  3861  3861 V BtOppService: onDestroy
08-03 19:10:11.156  1939  2356 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-03 19:10:11.156  1939  2356 D WfdsService: Set the WFDS Monitor: false
08-03 19:10:11.157  1939  2356 D WfdsMonitor: WFDS Monitor is stopped
08-03 19:10:11.157  1939  2770 D CtrlSupplicant: Received on exit socket, terminate
08-03 19:10:11.157  1939  2770 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-03 19:10:11.157  1939  2356 D WfdsService: STATE : WfdsDisabledState - enter
08-03 19:10:11.157  1939  2770 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-03 19:10:11.157  1939  2770 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-03 19:10:11.157  1939  2356 W WfdsService: DefaultState - msg [9445378] is not handled
08-03 19:10:11.157  1939  2357 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-03 19:10:11.158  1031  1543 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-03 19:10:11.158  1031  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:10:11.158  1031  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 19:10:11.158  1031  1543 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 19:10:11.158  1031  1031 D WifiHS20: hidePasspointNotification off =false
08-03 19:10:11.158  1031  1543 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-03 19:10:11.158  16,02  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-03 19:10:11.159  1031  1543 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-03 19:10:11.159  1031  1543 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-03 19:10:11.159  1031  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-03 19:10:11.159  1031  2840 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:11.159  1031  2840 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:11.159  1031  2840 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-03 19:10:11.160  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:11.160  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:11.160  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-03 19:10:11.164  1031  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
,08-03 19:10:11.165  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
,08-03 19:10:11.165  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 19:10:11.165  1031  1031 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-03 19:10:11.165  1031  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-03 19:10:11.166  1031  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-03 19:10:11.166  1031  1535 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-03 19:10:11.167  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-03 19:10:11.167  1031  1031 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-03 19:10:11.168  1031  1031 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-03 19:10:11.168  1031  1535 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-03 19:10:11.168  1031  1031 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-03 19:10:11.168  1031  1031 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-03 19:10:11.168  6643  6643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:10:11.168  1031  1031 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-03 19:10:11.168  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:10:11.168  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:10:11.168  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:10:11.168  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 19:10:11.168  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 19:10:11.168  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:10:11.168  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:10:11.168  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 19:10:11.169  1031  1031 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-03 19:10:11.169  1031  1031 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-03 19:10:11.169  1031  1031 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-03 19:10:11.169  1031  1543 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:10:11.170  1031  1543 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:10:11.170  1031  1537 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:10:11.170  1031  1537 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-03 19:10:11.171  6643  6643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:10:11.171  6643  6643 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellu,lar: DO_NOT_CARE, BSSID name: null
08-03 19:10:11.171  1850  1850 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:10:11.171  1031  1543 D NetworkManagementService: Removing idletimer
08-03 19:10:11.171  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-03 19:10:11.171  1031  1543 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:11.172  1031  1543 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-03 19:10:11.172  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 19:10:11.172  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 19:10:11.173  6643  6643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:10:11.173  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:10:11.173  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:10:11.173  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:10:11.173  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 19:10:11.173  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 19:10:11.173  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:10:11.173  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:10:11.173  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 19:10:11.173  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:10:11.173  6643  6643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:10:11.173  6643  6643 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-03 19:10:11.223  1031  1725 I art     : Explicit concurrent mark sweep GC freed 37358(1954KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.584ms total 136.786ms
,08-03 19:10:11.232  3861  3861 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-03 19:10:11.250  6897  6897 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-03 19:10:11.250  6897  6897 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,08-03 19:10:11.251  6897  6897 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-03 19:10:11.251  6897  6897 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-03 19:10:11.252  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 19:10:11.252  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 19:10:11.252  6897  6897 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-03 19:10:11.253  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:10:11.253  6897  6897 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-03 19:10:11.257  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-03 19:10:11.257  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 19:10:11.258  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:10:11.259  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:10:11.267  1031  2841 D DhcpStateMachine: StoppedState
08-03 19:10:11.267  1031  2841 D DhcpStateMachine: StoppedState{ when=-138ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:11.268  1031  1537 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-03 19:10:11.268  1031  1537 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,08-03 19:10:11.271  2704  2704 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-03 19:10:11.271  2704  2704 I wpa_supplicant: monitor socket send errors count : 1
08-03 19:10:11.271  2704  2704 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1939-2\x00 that cannot receive messages
08-03 19:10:11.272  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-03 19:10:11.272  1031  2765 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-03 19:10:11.272  1031  2765 D WifiMonitor: Dropping event because (p2p0) is stopped
08-03 19:10:11.272  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:10:11.273  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:10:11.283  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-03 19:10:11.284  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:10:11.284  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-03 19:10:11.308  2704  2704 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-03 19:10:11.309  1031  2765 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-03 19:10:11.309  1031  2765 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-03 19:10:11.309  1031  2765 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-03 19:10:11.309  1031  2765 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-03 19:10:11.309  2704  2704 W wpa_supplicant: USIM:  scard_deinit function
08-03 19:10:11.309  1031  1095 D Tethering: InitialState.processMessage what=4
08-03 19:10:11.309  1031  2765 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-03 19:10:11.309  1031  2765 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-03 19:10:11.310  1031  1537 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=153777
08-03 19:10:11.310  1031  1537 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=153777
08-03 19:10:11.311  1031  1537 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=153777  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-03 19:10:11.311  1031  1095 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-03 19:10:11.311  1031  1537 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=153779  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-03 19:10:11.312  1031  1537 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-03 19:10:11.312  1031  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-03 19:10:11.320  6877  6877 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-03 19:10:11.321  6877  6877 W LG Account v2.2: No ProfileInfo entries
08-03 19:10:11.321  6877  6877 I LG Account v2.2: isEnabled: false
08-03 19:10:11.321  6877  6877 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-03 19:10:11.321  6877  6877 I Feature : [Lifetracker]Country: EU
08-03 19:10:11.321  6877  6877 I Feature : [Lifetracker]Operator: OPEN
08-03 19:10:11.321  6877  6877 I Feature : [Lifetracker]Ranking support: false
08-03 19:10:11.321  6877  6877 I Feature : [Lifetracker]Comfort support: false
08-03 19:10:11.321  6877  6877 I Feature : [Lifetracker]Accessory: true
08-03 19:10:11.321  6877  6877 I Feature : [Lifetracker]Health device: true
08-03 19:10:11.321  6877  6877 I Feature : [Lifetracker]Extra Pedometer: false
08-03 19:10:11.321  6877  6877 I Feature : [Lifetracker]Blood glucose device: false
08-03 19:10:11.321  6877  6877 I Feature : [Lifetracker]Device Number: 3
,08-03 19:10:11.328  6454  6454 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 19:10:11.344  6897  6897 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-03 19:10:11.347  1031  1938 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6918 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-03 19:10:11.347  1031  1938 I ActivityManager: Killing 6260:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-03 19:10:11.386  1031  1902 W libprocessgroup: failed to open /acct/uid_10014/pid_6260/cgroup.procs: No such file or directory
,08-03 19:10:11.392  3861  3861 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-03 19:10:11.393  3861  3861 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:10:11.393  3861  3861 V BluetoothPbapReceiver: ***********state = 13
08-03 19:10:11.393  1031  1095 D BluetoothManagerService: Message: 20
,08-03 19:10:11.393  1031  1095 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@296959ef:true
,08-03 19:10:11.397  3861  3861 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-03 19:10:11.398  3861  3861 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:10:11.398  3861  3861 V BluetoothPbapService: state: 13
08-03 19:10:11.398  3861  3861 V BluetoothPbapService: Pbap Service closeService in
08-03 19:10:11.399  2195  2195 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-03 19:10:11.399  3861  3861 V BluetoothPbapService: successfully stopped pbap service
08-03 19:10:11.400  3861  3861 V BluetoothPbapService: Pbap Service closeService out
,08-03 19:10:11.403  3861  3861 V BluetoothPbapService: Pbap Service onDestroy
08-03 19:10:11.403  3861  3861 V BluetoothPbapService: Pbap Service closeService in
,08-03 19:10:11.403  3861  3861 V BluetoothPbapService: Pbap Service closeService out
08-03 19:10:11.403  3861  3861 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-03 19:10:11.407  1031  1095 D BluetoothManagerService: Message: 30
08-03 19:10:11.411  1031  1095 D BluetoothManagerService: Message: 30
08-03 19:10:11.413  6897  6897 D LocalBluetoothProfileManager: Adding local MAP profile
08-03 19:10:11.414  6897  6897 D BluetoothMap: Create BluetoothMap proxy object
08-03 19:10:11.415  1031  1095 D BluetoothManagerService: Message: 30
,08-03 19:10:11.418  1031  1095 D BluetoothManagerService: Message: 30
08-03 19:10:11.420  6897  6897 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-03 19:10:11.421  6897  6897 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-03 19:10:11.431  2704  2704 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-03 19:10:11.432  1031  2765 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-03 19:10:11.432  1031  2765 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-03 19:10:11.432  1031  2765 D WifiMonitor: Disconnecting from the supplicant, no more events
08-03 19:10:11.433  1031  1537 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
,08-03 19:10:11.437  6897  6897 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-03 19:10:11.439  6897  6897 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-03 19:10:11.452  6897  6897 D DockEventReceiver: finishStartingService: stopping service
,08-03 19:10:11.458  6918  6918 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-03 19:10:11.464  6918  6918 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-03 19:10:11.464  6918  6918 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-03 19:10:11.466  6897  6897 D BluetoothInputDevice: Proxy object connected
,08-03 19:10:11.466  6897  6897 D HidProfile: Bluetooth service connected
08-03 19:10:11.466  1031  1046 I ActivityManager: Killing 2150:com.lge.music/u0a34 (adj 15): empty #17
,08-03 19:10:11.467  6897  6897 D BluetoothPan: BluetoothPAN Proxy object connected
08-03 19:10:11.468  6897  6897 D PanProfile: Bluetooth service connected
08-03 19:10:11.468  6897  6897 D BluetoothMap: Proxy object connected
08-03 19:10:11.469  6897  6897 D MapProfile: Bluetooth service connected
08-03 19:10:11.469  6897  6897 D BluetoothMap: getConnectedDevices()
08-03 19:10:11.470  6897  6897 D BluetoothMap: Bluetooth is Not enabled
08-03 19:10:11.470  6897  6897 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-03 19:10:11.479   310  1380 V AudioFlinger: 2150 died, releasing its sessions
08-03 19:10:11.479   310  1380 V AudioFlinger:  pid 1850 @ 0
08-03 19:10:11.479   310  1380 V AudioFlinger:  pid 3487 @ 1
08-03 19:10:11.479   310  1380 V AudioFlinger:  pid 3487 @ 2
,08-03 19:10:11.499  6643  6643 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-03 19:10:11.511  1031  2010 W libprocessgroup: failed to open /acct/uid_10034/pid_2150/cgroup.procs: No such file or directory
,08-03 19:10:11.525  6897  6897 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-03 19:10:11.534  1031  1537 D WifiOffDelayIfNotUsed: stopMonitoring
08-03 19:10:11.534  1031  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-03 19:10:11.534  1031  1537 E WifiStateMachine: useWiFiOffloading() : false
08-03 19:10:11.534  1031  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-03 19:10:11.548  1939  1939 D WfdsService: Supplicant Connection state is changed : false
,08-03 19:10:11.549  1939  2356 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-03 19:10:11.549  1939  2356 D WfdsService: Set the WFDS Monitor: false
08-03 19:10:11.549  1939  2356 D WfdsMonitor: WFDS Monitor is stopped
,08-03 19:10:11.549  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:10:11.550  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-03 19:10:11.550  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-03 19:10:11.550  1031  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-03 19:10:11.551  1031  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-03 19:10:11.553  6643  6643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:10:11.553  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:10:11.553  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:10:11.553  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:10:11.553  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 19:10:11.553  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 19:10:11.553  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:10:11.553  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:10:11.553  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 19:10:11.554  2504  2504 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:11.561  6643  6643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:10:11.561  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:10:11.561  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:10:11.561  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:10:11.561  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 19:10:11.561  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 19:10:11.561  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:10:11.561  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:10:11.561  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 19:10:11.581  6897  6897 D LgDataFeature: LgDataFeature() Constructor: none
08-03 19:10:11.581  6897  6897 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 19:10:11.601  6897  6897 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:10:11.607  6897  6897 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-03 19:10:11.613  6897  6897 D BluetoothPermissionRequest: onReceive
08-03 19:10:11.618  6897  6897 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-03 19:10:11.634  6897  6897 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-03 19:10:11.634  1031  1938 I ActivityManager: Killing 6387:com.android.defcontainer/u0a4 (adj 15): empty #17
,08-03 19:10:11.693  1031  1986 W libprocessgroup: failed to open /acct/uid_10004/pid_6387/cgroup.procs: No such file or directory
,08-03 19:10:11.695  3861  3861 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-03 19:10:11.696  3861  3861 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-03 19:10:11.698  3861  3861 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-03 19:10:11.803  1031  2040 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6952 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-03 19:10:11.803  3861  3861 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:10:11.803  3861  3861 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-03 19:10:11.808  3861  3861 V BluetoothFtpService: Ftp Service onStartCommand
08-03 19:10:11.808  3861  3861 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:10:11.808  3861  3861 V BluetoothFtpService: Ftp Service closeService
08-03 19:10:11.808  3861  3861 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
,08-03 19:10:11.810  3861  3861 V BluetoothFtpService: successfully stopped ftp service
08-03 19:10:11.811  3861  3861 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-03 19:10:11.811  3861  3861 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-03 19:10:11.811  3861  3861 V BluetoothSapReceiver: SapReceiver onReceive 
08-03 19:10:11.811  3861  3861 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:10:11.811  3861  3861 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-03 19:10:11.811  3861  3861 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-03 19:10:11.813  3861  3861 V BluetoothFtpService: Ftp Service onDestroy
08-03 19:10:11.813  3861  3861 V BluetoothFtpService: Ftp Service closeService
08-03 19:10:11.824   342   342 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 476us total 21.910ms
,08-03 19:10:11.848   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 446us total 20.708ms
,08-03 19:10:11.870   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 448us total 20.714ms
,08-03 19:10:11.925  1031  1975 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6969 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-03 19:10:11.926  3861  3861 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:10:11.926  3861  3861 V BluetoothSapService: state: 13
08-03 19:10:11.926  3861  3861 V BluetoothSapService: Stopping SAP server process
08-03 19:10:11.931  3861  3861 V BluetoothSapService: Sap Service closeSapService in
08-03 19:10:11.931  3861  3861 V BluetoothSapService: Close listen Socket : 
08-03 19:10:11.931  3861  3861 V BluetoothSapService: Close rfcomm Socket : 
08-03 19:10:11.932  3861  3861 V BluetoothSapService: Close sapd  Socket : 
08-03 19:10:11.937  3861  3861 V BluetoothSapService: Sap Service closeSapService out
,08-03 19:10:11.937  3861  3861 V BluetoothSapService: Sap Service onDestroy
08-03 19:10:11.937  3861  3861 V BluetoothSapService: Sap Service closeSapService in
08-03 19:10:11.937  3861  3861 V BluetoothSapService: Close listen Socket : 
08-03 19:10:11.937  3861  3861 V BluetoothSapService: Close rfcomm Socket : 
08-03 19:10:11.937  3861  3861 V BluetoothSapService: Close sapd  Socket : 
08-03 19:10:11.938  3861  3861 V BluetoothSapService: Sap Service closeSapService out
,08-03 19:10:11.986  6952  6952 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-03 19:10:12.001  6969  6969 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-03 19:10:12.015  6952  6952 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-03 19:10:12.019  1031  1884 I ActivityManager: Killing 6498:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-03 19:10:12.049  1031  1574 W libprocessgroup: failed to open /acct/uid_10008/pid_6498/cgroup.procs: No such file or directory
,08-03 19:10:12.086  3861  4015 I bt_lpm  : LPM is already off!!!
08-03 19:10:12.086  3861  3947 D bt_hci_bdroid: cleanup
,08-03 19:10:12.087  3861  4141 I bt_userial_mct: exiting userial_read_thread
08-03 19:10:12.087  3861  4141 D bt_userial_mct: Leaving userial_evt_read_thread()
08-03 19:10:12.087  6952  6952 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-03 19:10:12.088  6952  6952 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-03 19:10:12.088  3861  4013 W bt-btif : ag scb idx 1 not allocated
08-03 19:10:12.088  3861  4013 E bt-btif : BTA AG is already disabled, ignoring ...
08-03 19:10:12.088  3861  4013 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-03 19:10:12.088  3861  4013 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 19:10:12.088  3861  4013 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-03 19:10:12.088  3861  4013 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-03 19:10:12.088  3861  4013 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-03 19:10:12.088  6952  6952 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-03 19:10:12.088  3861  4013 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-03 19:10:12.088  3861  4013 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-03 19:10:12.088  3861  4013 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 19:10:12.088  3861  4013 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-03 19:10:12.088  3861  4013 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-03 19:10:12.089  3861  4013 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-03 19:10:12.089  3861  4013 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-03 19:10:12.089  6952  6952 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-03 19:10:12.089  3861  4013 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-03 19:10:12.089  3861  4013 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 19:10:12.089  3861  4013 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-03 19:10:12.089  3861  4013 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-03 19:10:12.089  3861  4013 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-03 19:10:12.089  3861  4013 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-03 19:10:12.089  6952  6952 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-03 19:10:12.089  3861  4013 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-03 19:10:12.089  3861  3947 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-03 19:10:12.089  3861  4015 I bt_vendor: hw_epilog_process
08-03 19:10:12.090  3861  3947 D bt_hci_bdroid: cleanup Finalizing cleanup
08-03 19:10:12.090  3861  3947 D bt_userial_mct: userial_close
08-03 19:10:12.090  3861  3947 E bt_userial_mct: pthread_join() FAILED result:3
08-03 19:10:12.090  3861  3947 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-03 19:10:12.091  6952  6952 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-03 19:10:12.097  6952  6952 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-03 19:10:12.105  6952  6952 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-03 19:10:12.109  6952  6952 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 19:10:12.131  6952  6952 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-03 19:10:12.135  6454  6454 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.,
08-03 19:10:12.139  6952  6952 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-03 19:10:12.141  6918  6918 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-03 19:10:12.142  6918  6918 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-03 19:10:12.142  6918  6918 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-03 19:10:12.143  6952  6952 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-03 19:10:12.148  6897  6897 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 19:10:12.156  6897  6897 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:10:12.166  6952  6952 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 19:10:12.166  6952  6952 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 19:10:12.168  6952  6952 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-03 19:10:12.175  6454  6454 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 19:10:12.179   305  6991 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-03 19:10:12.181  1031  1093 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-03 19:10:12.184  6918  6918 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-03 19:10:12.184  6918  6918 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-03 19:10:12.184  6918  6918 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-03 19:10:12.188  6897  6897 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-03 19:10:12.191  3861  3947 D bt_hci_bdroid: set_power 0
08-03 19:10:12.191  3861  3947 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-03 19:10:12.191  3861  3947 I bt_vendor: bluetooth satus is on
08-03 19:10:12.191  3861  3947 I bt_vendor: bt-vendor : resetting BT status
08-03 19:10:12.191  3861  3947 I bt_vendor: Starting hciattach daemon
08-03 19:10:12.191  3861  3947 I bt_vendor: try to set false
08-03 19:10:12.192  3861  3947 I bt_vendor: Starting hciattach daemon
08-03 19:10:12.192  3861  3947 I bt_vendor: try to set false
,08-03 19:10:12.193  3861  3947 I bt_vendor: cleanup
08-03 19:10:12.195  3861  4013 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-03 19:10:12.199  6897  6897 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:10:12.201  3861  3947 I GKI_LINUX: GKI_exit_task 0 done
08-03 19:10:12.201  3861  3947 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-03 19:10:12.202  3861  3943 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-03 19:10:12.206  6952  6952 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-03 19:10:12.208  6952  6952 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-03 19:10:12.209  3861  3861 D HeadsetService: Received stop request...Stopping profile...
08-03 19:10:12.210  3861  3861 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-03 19:10:12.210  3861  3861 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-03 19:10:12.210  3861  3861 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f49f042
08-03 19:10:12.210  3861  3963 D HeadsetStateMachine: Exit Disconnected: -1
08-03 19:10:12.211  1031  1031 D BluetoothHeadset: Proxy object disconnected
08-03 19:10:12.211  1031  1031 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-03 19:10:12.212  1850  1850 D BluetoothHeadset: Proxy object disconnected
08-03 19:10:12.212  1850  1850 D BluetoothHeadset: Proxy object disconnected
08-03 19:10:12.212  1850  1850 D BluetoothHeadset: Proxy object disconnected
08-03 19:10:12.212  6952  6952 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-03 19:10:12.213  3861  3861 D A2dpService: Received stop request...Stopping profile...
08-03 19:10:12.213  3861  3996 D A2dpStateMachine: Exit Disconnected: -1
08-03 19:10:12.214  3861  3861 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-03 19:10:12.259  1031  1918 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6992 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
08-03 19:10:12.260  3861  3943 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-03 19:10:12.264  3861  3861 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-03 19:10:12.264  3861  3861 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-03 19:10:12.264  3861  3861 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f49f042
08-03 19:10:12.266  1031  1031 D BluetoothA2dp: Proxy object disconnected
08-03 19:10:12.266  1031  1031 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-03 19:10:12.267  1031  1374 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2d198be2 type 2 when 154733 com.google.android.gms} when 154733
08-03 19:10:12.267  3861  3861 D HidService: Received stop request...Stopping profile...
08-03 19:10:12.267  3861  3861 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f49f042
08-03 19:10:12.269  6897  6897 D BluetoothInputDevice: Proxy object disconnected
08-03 19:10:12.269  3861  3861 D HealthService: Received stop request...Stopping profile...
08-03 19:10:12.269  3861  3861 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f49f042
08-03 19:10:12.270  6897  6897 D HidProfile: Bluetooth service disconnected
08-03 19:10:12.271  3861  3861 D HeadsetStateMachine: Unbinding service...
08-03 19:10:12.273  3861  3861 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-03 19:10:12.273  3861  3861 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-03 19:10:12.273  3861  3861 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-03 19:10:12.273  3861  3861 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-03 19:10:12.273  3861  3861 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-03 19:10:12.273  3861  3861 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-03 19:10:12.273  3861  3861 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-03 19:10:12.275  3861  3861 D PanService: Received stop request...Stopping profile...
08-03 19:10:12.275  3861  3861 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f49f042
,08-03 19:10:12.277  6897  6897 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-03 19:10:12.277  3861  3861 D BtGatt.DebugUtils: handleDebugAction() action=null
08-03 19:10:12.277  6897  6897 D PanProfile: Bluetooth service disconnected
08-03 19:10:12.278  3861  3861 D BtGatt.GattService: Received stop request...Stopping profile...
08-03 19:10:12.278  3861  3861 D BtGatt.GattService: stop()
08-03 19:10:12.278  3861  3861 D BtGatt.AdvertiseManager: advertise clients cleared
08-03 19:10:12.279  3861  3861 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f49f042
08-03 19:10:12.281  3861  3861 D BluetoothMapService: Received stop request...Stopping profile...
08-03 19:10:12.281  3861  3861 D BluetoothMapService: stop()
08-03 19:10:12.282  3861  3861 D BluetoothMapEmailAppObserver: deinitObservers()
08-03 19:10:12.282  3861  3861 D BluetoothMapEmailAppObserver: removeReceiver()
08-03 19:10:12.283  3861  3861 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f49f042
08-03 19:10:12.283  6897  6897 D BluetoothMap: Proxy object disconnected
08-03 19:10:12.283  6897  6897 D MapProfile: Bluetooth service disconnected
08-03 19:10:12.284  3861  3861 I BluetoothA2dpServiceJni: cleanupNative
08-03 19:10:12.284  3861  3997 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-03 19:10:12.284  3861  3861 I GKI_LINUX: GKI_exit_task 2 done
08-03 19:10:12.284  3861  3861 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-03 19:10:12.285  3861  3861 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-03 19:10:12.285  3861  3861 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-03 19:10:12.285  3861  3861 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-03 19:10:12.285  3861  3861 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-03 19:10:12.285  3861  3861 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-03 19:10:12.285  3861  3861 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-03 19:10:12.285  3861  3861 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-03 19:10:12.287  3861  3861 V BluetoothMapService: Handler(): got msg=4
08-03 19:10:12.287  3861  3861 D BluetoothMapService: MAP Service closeService in
08-03 19:10:12.287  3861  3861 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-03 19:10:12.287  3861  3861 V BluetoothMapService: MAP Service closeService out
08-03 19:10:12.287  3861  3861 D BluetoothMapService: cleanup()
08-03 19:10:12.287  3861  3861 D BluetoothMapService: MAP Service closeService in
08-03 19:10:12.287  3861  3861 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-03 19:10:12.287  3861  3861 V BluetoothMapService: MAP Service closeService out
08-03 19:10:12.287  3861  3943 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-03 19:10:12.287  3861  3943 D BluetoothAdapterProperties: Setting state to 10
08-03 19:10:12.287  3861  3943 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-03 19:10:12.288  1031  1095 D BluetoothManagerService: Message: 60
08-03 19:10:12.288  1031  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-03 19:10:12.288  1031  1095 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-03 19:10:12.288  1031  1095 D BluetoothA2dp: onBluetoothStateChange: up=false
08-03 19:10:12.289  3861  3943 I BluetoothAdapterState: Entering OffState
08-03 19:10:12.289  6897  6914 D BluetoothMap: onBluetoothStateChange: up=false
08-03 19:10:12.290  6897  6913 D BluetoothPan: onBluetoothStateChange on: false
08-03 19:10:12.290  1850  3973 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-03 19:10:12.291  1031  1095 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 19:10:12.291  6897  6914 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-03 19:10:12.292  6897  6913 D BluetoothPbap: onBluetoothStateChange: up=false
08-03 19:10:12.293  1850  2674 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 19:10:12.294  1850  1865 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 19:10:12.295  1031  1095 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-03 19:10:12.295  1031  1095 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-03 19:10:12.298  1031  1095 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-03 19:10:12.298  1031  1095 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-03 19:10:12.298  1031  1095 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@291b02f7 mBinding = false
08-03 19:10:12.299  1031  1095 D BluetoothManagerService: Sending unbind request.
08-03 19:10:12.300  1031  1095 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-03 19:10:12.305  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:10:12.305  1939  1939 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:10:12.305  1939  2132 D LGBluetoothAPIService: Message: 2
08-03 19:10:12.306  1939  2132 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@36fbf9d mBinding = false
08-03 19:10:12.306  1939  2132 D LGBluetoothAPIService: Sending unbind request.
,08-03 19:10:12.308  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-03 19:10:12.310  3861  3947 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-03 19:10:12.310  3861  3861 I GKI_LINUX: GKI_exit_task 1 done
08-03 19:10:12.310  3861  3861 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-03 19:10:12.311  3861  3861 I BluetoothServiceJni: cleanupNative: return from cleanup
08-03 19:10:12.311  3861  3861 I art     : --- WEIRD: removing null entry 246
08-03 19:10:12.311  3861  3861 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-03 19:10:12.311  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:10:12.311  3861  3861 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-03 19:10:12.312  3861  3861 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-03 19:10:12.312  6897  6897 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-03 19:10:12.313  6897  6897 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-03 19:10:12.313  6897  6897 D LGBluetoothEventManager: [BTUI] clear device connection state
08-03 19:10:12.316  3861  3861 I art     : System.exit called, status: 0
08-03 19:10:12.316  3861  3861 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-03 19:10:12.318  1602  1602 D BluetoothAdapter: 342004933: getState() :  mService = null. Returning STATE_OFF
08-03 19:10:12.318  1602  1602 D BluetoothAdapter: 342004933: getState() :  mService = null. Returning STATE_OFF
08-03 19:10:12.319  6897  6897 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-03 19:10:12.327  6897  6897 D DockEventReceiver: finishStartingService: stopping service
,08-03 19:10:12.345   310  1381 V AudioFlinger: 3861 died, releasing its sessions
08-03 19:10:12.345   310  1381 V AudioFlinger:  pid 1850 @ 0
08-03 19:10:12.345   310  1381 V AudioFlinger:  pid 3487 @ 1
08-03 19:10:12.345   310  1381 V AudioFlinger:  pid 3487 @ 2
08-03 19:10:12.346  6897  6897 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,08-03 19:10:12.431  1031  1902 I ActivityManager: Process com.android.bluetooth (pid 3861) has died
08-03 19:10:12.432  1031  1902 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-03 19:10:12.446  2195  2195 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-03 19:10:12.466  6918  6918 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-03 19:10:12.484  6897  6897 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-03 19:10:12.490  6897  6897 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:10:12.494  6897  6897 D BluetoothPermissionRequest: onReceive
08-03 19:10:12.497  6897  6897 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-03 19:10:12.497  6897  6897 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
,08-03 19:10:12.501  6897  6897 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-03 19:10:12.501  6992  7017 W FormManager: Network not available. Please check & try again.
,08-03 19:10:12.562  1031  1941 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7022 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-03 19:10:12.573  6992  7018 V FormManager: Network unavailable.
08-03 19:10:12.582  6992  7018 V FormManager: Network unavailable.
,08-03 19:10:12.593  6897  6897 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-03 19:10:12.594  6897  6897 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-03 19:10:12.594  6897  6897 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-03 19:10:12.594  6897  6897 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-03 19:10:12.595  6897  6897 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-03 19:10:12.620  6897  6897 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-03 19:10:12.621  6897  6897 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-03 19:10:12.621  6897  6897 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-03 19:10:12.621  6897  6897 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-03 19:10:12.621  6897  6897 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-03 19:10:12.621  6897  6897 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-03 19:10:12.623  1031  1938 I ActivityManager: Killing 6030:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-03 19:10:12.654  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-03 19:10:12.654  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-03 19:10:12.657  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 19:10:12.657  1031  1902 W libprocessgroup: failed to open /acct/uid_10011/pid_6030/cgroup.procs: No such file or directory
08-03 19:10:12.664  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 19:10:12.674  4297  7043 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-03 19:10:12.675  6918  6918 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-03 19:10:12.675  6918  6918 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-03 19:10:12.675  6918  6918 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-03 19:10:12.676  7022  7022 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-03 19:10:12.676  7022  7022 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-03 19:10:12.676  4297  7044 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-03 19:10:12.677  7022  7022 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-03 19:10:12.677  4297  7044 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-03 19:10:12.677  7022  7022 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-03 19:10:12.682  6897  6897 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-03 19:10:12.692  6897  6897 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:10:12.701  7022  7022 D BluetoothAdapterApp: Loading JNI Library
,08-03 19:10:12.706  6992  7046 W FormManager: Network not available. Please check & try again.
08-03 19:10:12.713  6952  6952 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-03 19:10:12.714  6992  7047 V FormManager: Network unavailable.
08-03 19:10:12.714  6952  6952 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-03 19:10:12.714  6952  6952 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-03 19:10:12.715  6992  7047 V FormManager: Network unavailable.
,08-03 19:10:12.747  7022  7022 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1b5ae8db Instance Count = 1
,08-03 19:10:12.752  6952  6952 D LgDataFeature: LgDataFeature() Constructor: none
08-03 19:10:12.752  6952  6952 D LgDataFeature: LgDataFeature() Constructor Done, null
08-03 19:10:12.754  7022  7022 D BluetoothAdapterApp: onCreate
08-03 19:10:12.761  6952  6952 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,08-03 19:10:12.762  6952  6952 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-03 19:10:12.762  6952  6952 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-03 19:10:12.762  6952  6952 V SoundPool: doLoad: loading sample sampleID=1
08-03 19:10:12.762  6952  6952 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-03 19:10:12.764  6952  7054 V SoundPool: Start decode
08-03 19:10:12.764  6952  7054 V MediaPlayer[Native]: decode(31, 10857164, 17813)
,08-03 19:10:12.768   310  1380 V MediaPlayerService: decode(23, 10857164, 17813)
08-03 19:10:12.768   310  1380 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-03 19:10:12.768   310  1380 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-03 19:10:12.768   310  1380 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-03 19:10:12.768   310  1380 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-03 19:10:12.768   310  1380 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-03 19:10:12.768   310  1380 V MediaPlayerService: player type = 3
08-03 19:10:12.768   310  1380 V AwesomePlayer: AwesomePlayer create()
08-03 19:10:12.769   310  1380 V AwesomePlayer: reset_l() 
08-03 19:10:12.769   310  1380 V AwesomePlayer: cancelPlayerEvents
08-03 19:10:12.769   310  1380 V AwesomePlayer: setAudioSink() 
08-03 19:10:12.769   310  1380 V AwesomePlayer: reset_l() 
08-03 19:10:12.769   310  1380 V AudioCache: notify(0xb5474940, 8, 0, 0)
08-03 19:10:12.769   310  1380 V AudioCache: ignored
08-03 19:10:12.769   310  1380 V AwesomePlayer: cancelPlayerEvents
08-03 19:10:12.769   310  1380 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-03 19:10:12.769   310  1380 V AwesomePlayer: setDataSource_l dataSource
08-03 19:10:12.769   310  1380 V LGParserOSAL: SniffLGParser start
08-03 19:10:12.769   310  1380 V LGParserOSAL: MainType:5, SubType=0
08-03 19:10:12.769   310  1380 V LGParserOSAL: #### check Mime : application/ogg
08-03 19:10:12.769   310  1380 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-03 19:10:12.769   310  1380 E MediaExtractor: Use LGExtractor :application/ogg 
08-03 19:10:12.773  6744  6744 D UEI.SmartControl: QS Service created
,08-03 19:10:12.781  6952  6952 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-03 19:10:12.783  7022  7022 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-03 19:10:12.783  7022  7022 D ProfileConfigQcom: Adding HeadsetService
08-03 19:10:12.783  7022  7022 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-03 19:10:12.783  7022  7022 D ProfileConfigQcom: Adding A2dpService
08-03 19:10:12.783  7022  7022 D ProfileConfigQcom: [BTUI] HidService is supported
08-03 19:10:12.784  7022  7022 D ProfileConfigQcom: Adding HidService
08-03 19:10:12.784  7022  7022 D ProfileConfigQcom: [BTUI] HealthService is supported
08-03 19:10:12.784  7022  7022 D ProfileConfigQcom: Adding HealthService
08-03 19:10:12.784  7022  7022 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-03 19:10:12.785  7022  7022 D ProfileConfigQcom: [BTUI] PanService is supported
08-03 19:10:12.785  7022  7022 D ProfileConfigQcom: Adding PanService
08-03 19:10:12.786  7022  7022 D ProfileConfigQcom: [BTUI] GattService is supported
08-03 19:10:12.786  7022  7022 D ProfileConfigQcom: Adding GattService
08-03 19:10:12.786  7022  7022 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-03 19:10:12.786  7022  7022 D ProfileConfigQcom: Adding BluetoothMapService
08-03 19:10:12.787  7022  7022 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-03 19:10:12.789  7022  7022 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-03 19:10:12.793  6952  6952 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-03 19:10:12.793  6897  6897 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-03 19:10:12.793  6952  6952 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-03 19:10:12.795  7022  7022 V LGMDMManagerInternal: Create singleton instance
,08-03 19:10:12.802  6744  6744 I UEI.SmartControl: Service initServices...
08-03 19:10:12.802  6744  6744 D UEI.SmartControl: QS start get config
08-03 19:10:12.808  6952  6952 V LGMDMManager: Create singleton instance
08-03 19:10:12.817   310  1380 V LGParserOSAL: supported mime: application/ogg
08-03 19:10:12.817   310  1380 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-03 19:10:12.817   310  1380 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-03 19:10:12.817   310  1380 V AwesomePlayer: mBitrate = -1 bits/sec
08-03 19:10:12.817   310  1380 V AwesomePlayer: AudioTrack Setting
08-03 19:10:12.817   310  1380 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-03 19:10:12.817   310  1380 V AwesomePlayer: setAudioSource() 
08-03 19:10:12.817   310  1380 V MediaPlayerService: prepare
08-03 19:10:12.817   310  1380 V AwesomePlayer: prepareAsync_l() 
08-03 19:10:12.817   310  1380 V MediaPlayerService: wait for prepare
,08-03 19:10:12.817   310  7057 V AwesomePlayer: onPrepareAsyncEvent() 
08-03 19:10:12.817   310  7057 V AwesomePlayer: initAudioDecoder() 
08-03 19:10:12.817   310  7057 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-03 19:10:12.817   310  7057 V AudioSystem: isOffloadSupported()
08-03 19:10:12.817   310  7057 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-03 19:10:12.818   310  7057 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-03 19:10:12.818   310  7057 I AudioFlinger: isAudioPlaybackHookOn() false
08-03 19:10:12.818   310  7057 V AwesomePlayer: getUseOffload() = 0 
08-03 19:10:12.818   310  7057 V OMXCodec: OMXCodec::Create
08-03 19:10:12.818   310  7057 V OMXCodec: findMatchingCodecs()
08-03 19:10:12.818   310  7057 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-03 19:10:12.818   310  7057 V OMXCodec: matchingCodecs.size()=1
08-03 19:10:12.818   310  7057 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-03 19:10:12.819   310  7057 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-03 19:10:12.819   310  7057 V LGCodecAdapter: LG Codec Adapter start
08-03 19:10:12.819   310  7057 V OMXCodec: OMXCodec Createtor
08-03 19:10:12.819   310  7057 V OMXCodec: setComponentRole
08-03 19:10:12.819   310  7057 V OMXCodec: configureCodec protected=0
08-03 19:10:12.819   310  7057 V LGCodecAdapter: called getLGCodecSpecificData
08-03 19:10:12.819   310  7057 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-03 19:10:12.819   310  7057 V LGCodecOSAL: Called LGconfigureCodecMETA
08-03 19:10:12.819   310  7057 V LGCodecOSAL: Called LGconfigureCodecMSG
08-03 19:10:12.819   310  7057 V LGCodecOSAL: Not support LGCodec
08-03 19:10:12.819   310  7057 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-03 19:10:12.819   310  7057 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-03 19:10:12.820   310  7057 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-03 19:10:12.820   310  7057 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-03 19:10:12.820   310  7057 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-03 19:10:12.820   310  7057 V AudioSystem: isOffloadSupported()
08-03 19:10:12.820   310  7057 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-03 19:10:12.820   310  7057 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-03 19:10:12.820   310  7057 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-03 19:10:12.820   310  7057 V OMXCodec: init()
08-03 19:10:12.820   310  7057 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-03 19:10:12.820   310  7057 V OMXCodec: allocateBuffers
08-03 19:10:12.820   310  7057 V OMXCodec: allocateBuffersOnPort portIndex=0
08-03 19:10:12.820   310  7057 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-03 19:10:12.820   310  7057 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f77e0 on input port
08-03 19:10:12.820   310  7057 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7830 on input port
08-03 19:10:12.820   310  7057 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f78d0 on input port
08-03 19:10:12.820   310  7057 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on input port
08-03 19:10:12.820   31,0  7057 V OMXCodec: allocateBuffersOnPort portIndex=1
08-03 19:10:12.820   310  7057 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-03 19:10:12.820   310  7057 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on output port
08-03 19:10:12.820   310  7057 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-03 19:10:12.820   310  7057 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
08-03 19:10:12.820   310  7057 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f60 on output port
08-03 19:10:12.820   310  7057 V OMXCodec: init() mAsyncCompletion wait!!! 
08-03 19:10:12.820   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-03 19:10:12.820   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-03 19:10:12.820   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-03 19:10:12.820   310  7057 V OMXCodec: init() mAsyncCompletion wait!!! 
08-03 19:10:12.824   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-03 19:10:12.824   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-03 19:10:12.824   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-03 19:10:12.824   310  7057 V OMXCodec: init() mAsyncCompletion wait free! 
08-03 19:10:12.824   310  7057 V AwesomePlayer: finishAsyncPrepare_l() 
08-03 19:10:12.824   310  7057 V AudioCache: notify(0xb5474940, 5, 0, 0)
08-03 19:10:12.824   310  7057 V AudioCache: ignored
08-03 19:10:12.824   310  7057 V AudioCache: notify(0xb5474940, 1, 0, 0)
08-03 19:10:12.824   310  7057 V AudioCache: prepared
08-03 19:10:12.824   310  1380 V AudioCache: wait - success
08-03 19:10:12.824   310  1380 V MediaPlayerService: start
08-03 19:10:12.824   310  1380 V AwesomePlayer: play_l() 
08-03 19:10:12.824   310  1380 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-03 19:10:12.824   310  1380 V AwesomePlayer: createAudioPlayer_l
08-03 19:10:12.824   310  1380 V AwesomePlayer: seekAudioIfNecessary_l() 
08-03 19:10:12.824   310  1380 V AwesomePlayer: startAudioPlayer_l() 
08-03 19:10:12.824   310  1380 D AudioPlayer: start of Playback, useOffload 0
08-03 19:10:12.824   310  1380 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-03 19:10:12.824   310  1380 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-03 19:10:12.827   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-03 19:10:12.827   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-03 19:10:12.827   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-03 19:10:12.827   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-03 19:10:12.827   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-03 19:10:12.827   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
,08-03 19:10:12.827   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884608
08-03 19:10:12.827   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-03 19:10:12.827   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885008
08-03 19:10:12.827   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-03 19:10:12.827   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885648
08-03 19:10:12.827   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-03 19:10:12.827   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041886048
08-03 19:10:12.827   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-03 19:10:12.827   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-03 19:10:12.827   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-03 19:10:12.827   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-03 19:10:12.827   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-03 19:10:12.827   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-03 19:10:12.827   310  7059 V OMXCodec: allocateBuffersOnPort portIndex=1
,08-03 19:10:12.828   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-03 19:10:12.828   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
08-03 19:10:12.828   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-03 19:10:12.828   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on output port
08-03 19:10:12.828   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57f9470 on output port
08-03 19:10:12.828   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-03 19:10:12.828   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
,08-03 19:10:12.829   310  1380 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-03 19:10:12.830   310  1380 V AudioCache: notify(0xb5474940, 6, 0, 0)
08-03 19:10:12.830   310  1380 V AudioCache: ignored
08-03 19:10:12.830   310  1380 V MediaPlayerService: wait for playback complete
08-03 19:10:12.834   310  7060 V AudioCache: write(0xb16a8000, 4096)
08-03 19:10:12.834   310  7060 V AudioCache: memcpy(0xac300000, 0xb16a8000, 4096)
08-03 19:10:12.837   310  7060 V AudioCache: write(0xb16a8000, 4096)
08-03 19:10:12.837   310  7060 V AudioCache: memcpy(0xac301000, 0xb16a8000, 4096)
08-03 19:10:12.837   310  7060 V AudioCache: write(0xb16a8000, 4096)
08-03 19:10:12.837   310  7060 V AudioCache: memcpy(0xac302000, 0xb16a8000, 4096)
08-03 19:10:12.838   310  7060 V AudioCache: write(0xb16a8000, 4096)
08-03 19:10:12.838   310  7060 V AudioCache: memcpy(0xac303000, 0xb16a8000, 4096)
08-03 19:10:12.838   310  7060 V AudioCache: write(0xb16a8000, 4096)
08-03 19:10:12.838   310  7060 V AudioCache: memcpy(0xac304000, 0xb16a8000, 4096)
08-03 19:10:12.838   310  7060 V AudioCache: write(0xb16a8000, 4096)
08-03 19:10:12.838   310  7060 V AudioCache: memcpy(0xac305000, 0xb16a8000, 4096)
08-03 19:10:12.839   310  7060 V AudioCache: write(0xb16a8000, 4096)
08-03 19:10:12.839   310  7060 V AudioCache: memcpy(0xac306000, 0xb16a8000, 4096)
08-03 19:10:12.839   310  7060 V AudioCache: write(0xb16a8000, 4096)
08-03 19:10:12.839   310  7060 V AudioCache: memcpy(0xac307000, 0xb16a8000, 4096)
08-03 19:10:12.839   310  7060 V AudioCache: write(0xb16a8000, 4096)
08-03 19:10:12.839   310  7060 V AudioCache: memcpy(0xac308000, 0xb16a8000, 4096)
,08-03 19:10:12.840   310  7060 V AudioCache: write(0xb16a8000, 4096)
08-03 19:10:12.840   310  7060 V AudioCache: memcpy(0xac309000, 0xb16a8000, 4096)
08-03 19:10:12.841   310  7060 V AudioCache: write(0xb16a8000, 4096)
08-03 19:10:12.841   310  7060 V AudioCache: memcpy(0xac30a000, 0xb16a8000, 4096)
08-03 19:10:12.841   310  7060 V AudioCache: write(0xb16a8000, 4096)
08-03 19:10:12.841   310  7060 V AudioCache: memcpy(0xac30b000, 0xb16a8000, 4096)
08-03 19:10:12.841   310  7060 V AudioCache: write(0xb16a8000, 4096)
08-03 19:10:12.841   310  7060 V AudioCache: memcpy(0xac30c000, 0xb16a8000, 4096)
08-03 19:10:12.841   310  7060 V AudioCache: write(0xb16a8000, 4096)
08-03 19:10:12.841   310  7060 V AudioCache: memcpy(0xac30d000, 0xb16a8000, 4096)
08-03 19:10:12.842   310  7060 V AudioCache: write(0xb16a8000, 4096)
08-03 19:10:12.842   310  7060 V AudioCache: memcpy(0xac30e000, 0xb16a8000, 4096)
08-03 19:10:12.842   310  7060 V AudioCache: write(0xb16a8000, 4096)
08-03 19:10:12.842   310  7060 V AudioCache: memcpy(0xac30f000, 0xb16a8000, 4096)
08-03 19:10:12.843   310  7060 V AudioCache: write(0xb16a8000, 4096)
08-03 19:10:12.843   310  7060 V AudioCache: memcpy(0xac310000, 0xb16a8000, 4096)
08-03 19:10:12.843   310  7060 V AudioCache: write(0xb16a8000, 4096)
08-03 19:10:12.843   310  7060 V AudioCache: memcpy(0xac311000, 0xb16a8000, 4096)
08-03 19:10:12.844   310  7060 V AudioCache: write(0xb16a8000, 4096)
08-03 19:10:12.844   310  7060 V AudioCache: memcpy(0xac312000, 0xb16a8000, 4096)
08-03 19:10:12.845   310  7060 V AudioCache: write(0xb16a8000, 4096)
08-03 19:10:12.845   310  7060 V AudioCache: memcpy(0xac313000, 0xb16a8000, 4096)
08-03 19:10:12.845   310  7060 V AudioCache: write(0xb16a8000, 4096)
08-03 19:10:12.845   310  7060 V AudioCache: memcpy(0xac314000, 0xb16a8000, 4096)
08-03 19:10:12.846   310  7060 V AudioCache: write(0xb16a8000, 4096)
08-03 19:10:12.846   310  7060 V AudioCache: memcpy(0xac315000, 0xb16a8000, 4096)
08-03 19:10:12.846   310  7060 V AudioCache: write(0xb16a8000, 4096)
08-03 19:10:12.846   310  7060 V AudioCache: memcpy(0xac316000, 0xb16a8000, 4096)
08-03 19:10:12.847   310  7060 V AudioCache: write(0xb16a8000, 4096)
08-03 19:10:12.847   310  7060 V AudioCache: memcpy(0xac317000, 0xb16a8000, 4096)
08-03 19:10:12.847   310  7060 V AudioCache: write(0xb16a8000, 4096)
08-03 19:10:12.847   310  7060 V AudioCache: memcpy(0xac318000, 0xb16a8000, 4096)
08-03 19:10:12.848   310  7060 V AudioCache: write(0xb16a8000, 4096)
08-03 19:10:12.848   310  7060 V AudioCache: memcpy(0xac319000, 0xb16a8000, 4096)
08-03 19:10:12.849   310  7060 V AudioCache: write(0xb16a8000, 4096)
08-03 19:10:12.849   310  7060 V AudioCache: memcpy(0xac31a000, 0xb16a8000, 4096)
08-03 19:10:12.849   310  7060 V AudioCache: write(0xb16a8000, 4096)
08-03 19:10:12.849   310  7060 V AudioCache: memcpy(0xac31b000, 0xb16a8000, 4096)
08-03 19:10:12.850   310  7060 V AudioCache: write(0xb16a8000, 4096)
08-03 19:10:12.850   310  7060 V AudioCache: memcpy(0xac31c000, 0xb16a8000, 4096)
08-03 19:10:12.850   310  7060 V AudioCache: write(0xb16a8000, 4096)
08-03 19:10:12.850   310  7060 V AudioCache: memcpy(0xac31d000, 0xb16a8000, 4096)
08-03 19:10:12.851   310  7060 V AudioCache: write(0xb16a8000, 4096)
08-03 19:10:12.851   310  7060 V AudioCache: memcpy(0xac31e000, 0xb16a8000, 4096)
08-03 19:10:12.852   310  7060 V AudioCache: write(0xb16a8000, 4096)
08-03 19:10:12.852   310  7060 V AudioCache: memcpy(0xac31f000, 0xb16a8000, 4096)
08-03 19:10:12.852   310  7060 V AudioCache: write(0xb16a8000, 4096)
08-03 19:10:12.852   310  7060 V AudioCache: memcpy(0xac320000, 0xb16a8000, 4096)
08-03 19:10:12.852   310  7060 V AudioCache: write(0xb16a8000, 4096)
08-03 19:10:12.852   310  7060 V AudioCache: memcpy(0xac321000, 0xb16a8000, 4096)
08-03 19:10:12.853   310  7060 V AudioCache: write(0xb16a8000, 4096)
08-03 19:10:12.853   310  7060 V AudioCache: memcpy(0xac322000, 0xb16a8000, 4096)
08-03 19:10:12.853   310  7060 V AudioCache: write(0xb16a8000, 4096)
08-03 19:10:12.853   310  7060 V AudioCache: mem,cpy(0xac323000, 0xb16a8000, 4096)
08-03 19:10:12.854   310  7060 V AudioCache: write(0xb16a8000, 4096)
08-03 19:10:12.854   310  7060 V AudioCache: memcpy(0xac324000, 0xb16a8000, 4096)
08-03 19:10:12.854   310  7060 V AudioCache: write(0xb16a8000, 4096)
08-03 19:10:12.854   310  7060 V AudioCache: memcpy(0xac325000, 0xb16a8000, 4096)
08-03 19:10:12.855   310  7060 V AudioCache: write(0xb16a8000, 4096)
08-03 19:10:12.855   310  7060 V AudioCache: memcpy(0xac326000, 0xb16a8000, 4096)
08-03 19:10:12.855   310  7060 V AudioCache: write(0xb16a8000, 4096)
08-03 19:10:12.855   310  7060 V AudioCache: memcpy(0xac327000, 0xb16a8000, 4096)
08-03 19:10:12.856   310  7060 V AudioCache: write(0xb16a8000, 4096)
08-03 19:10:12.856   310  7060 V AudioCache: memcpy(0xac328000, 0xb16a8000, 4096)
08-03 19:10:12.856   310  7060 V AudioCache: write(0xb16a8000, 4096)
08-03 19:10:12.856   310  7060 V AudioCache: memcpy(0xac329000, 0xb16a8000, 4096)
08-03 19:10:12.857   310  7060 V AudioCache: write(0xb16a8000, 4096)
08-03 19:10:12.857   310  7060 V AudioCache: memcpy(0xac32a000, 0xb16a8000, 4096)
08-03 19:10:12.857   310  7060 V AudioCache: write(0xb16a8000, 4096)
08-03 19:10:12.857   310  7060 V AudioCache: memcpy(0xac32b000, 0xb16a8000, 4096)
08-03 19:10:12.857   310  7060 V AudioCache: write(0xb16a8000, 4096)
08-03 19:10:12.857   310  7060 V AudioCache: memcpy(0xac32c000, 0xb16a8000, 4096)
08-03 19:10:12.858   310  7060 V AudioCache: write(0xb16a8000, 4096)
08-03 19:10:12.858   310  7060 V AudioCache: memcpy(0xac32d000, 0xb16a8000, 4096)
08-03 19:10:12.858   310  7060 V AudioCache: write(0xb16a8000, 4096)
08-03 19:10:12.858   310  7060 V AudioCache: memcpy(0xac32e000, 0xb16a8000, 4096)
,08-03 19:10:12.859   310  7060 V AudioCache: write(0xb16a8000, 4096)
,08-03 19:10:12.859   310  7060 V AudioCache: memcpy(0xac32f000, 0xb16a8000, 4096)
08-03 19:10:12.859   310  7060 V AudioCache: write(0xb16a8000, 4096)
08-03 19:10:12.859   310  7060 V AudioCache: memcpy(0xac330000, 0xb16a8000, 4096)
08-03 19:10:12.860   310  7060 V AudioCache: write(0xb16a8000, 4096)
08-03 19:10:12.860   310  7060 V AudioCache: memcpy(0xac331000, 0xb16a8000, 4096)
08-03 19:10:12.860   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-03 19:10:12.860   310  7060 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-03 19:10:12.860   310  7060 V AwesomePlayer: postAudioEOS() 
08-03 19:10:12.860   310  7060 V AudioCache: write(0xb16a8000, 280)
08-03 19:10:12.860   310  7060 V AudioCache: memcpy(0xac332000, 0xb16a8000, 280)
08-03 19:10:12.868   310  7057 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-03 19:10:12.868   310  7057 V AwesomePlayer: onStreamDone
08-03 19:10:12.868   310  7057 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-03 19:10:12.868   310  7057 V AudioCache: notify(0xb5474940, 2, 0, 0)
08-03 19:10:12.868   310  7057 V AudioCache: playback complete
,08-03 19:10:12.868   310  7057 V AwesomePlayer: pause_l() 
08-03 19:10:12.868   310  1380 V AudioCache: wait - success
08-03 19:10:12.868   310  7057 V AudioCache: notify(0xb5474940, 7, 0, 0)
08-03 19:10:12.868   310  7057 V AudioCache: ignored
08-03 19:10:12.868   310  1380 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-03 19:10:12.868   310  7057 V AwesomePlayer: cancelPlayerEvents
08-03 19:10:12.868   310  7057 D AudioPlayer: Pause Playback at 1068125
08-03 19:10:12.869   310  1380 V AwesomePlayer: reset_l() 
08-03 19:10:12.869   310  1380 V AudioCache: notify(0xb5474940, 8, 0, 0)
08-03 19:10:12.869   310  1380 V AudioCache: ignored
08-03 19:10:12.869   310  1380 V AwesomePlayer: cancelPlayerEvents
08-03 19:10:12.869   310  1380 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-03 19:10:12.869   310  1380 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-03 19:10:12.869   310  1380 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-03 19:10:12.869   310  1380 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-03 19:10:12.869   310  1380 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-03 19:10:12.869   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-03 19:10:12.869   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-03 19:10:12.869   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-03 19:10:12.869   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 0
08-03 19:10:12.869   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-03 19:10:12.869   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f78d0 on port 0
08-03 19:10:12.869   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-03 19:10:12.869   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7830 on port 0
08-03 19:10:12.869   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-03 19:10:12.869   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f77e0 on port 0
08-03 19:10:12.869   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-03 19:10:12.869   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-03 19:10:12.869   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57f9470 on port 1
08-03 19:10:12.869   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-03 19:10:12.869   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 1
08-03 19:10:12.869   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-03 19:10:12.869   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 1
08-03 19:10:12.869   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-03 19:10:12.869   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7dd0 on port 1
08-03 19:10:12.869   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-03 19:10:12.869   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-03 19:10:12.870   310  1380 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-03 19:10:12.870   310  1380 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-03 19:10:12.870   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-03 19:10:12.870   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-03 19:10:12.870   310  7059 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-03 19:10:12.870   310  1380 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-03 19:10:12.870   310  1380 V OMXCodec: [OMX.google.vorbis.decoder] stopped i,n state 1
08-03 19:10:12.870   310  1380 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-03 19:10:12.871   310  1380 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-03 19:10:12.872   310  1380 D AudioPlayer: AudioPlayer releasing audio source
08-03 19:10:12.872   310  1380 D AudioPlayer: AudioPlayer done releasing audio source
08-03 19:10:12.872   310  1380 V AwesomePlayer: reset_l() 
08-03 19:10:12.872   310  1380 V AwesomePlayer: cancelPlayerEvents
08-03 19:10:12.872   310  1380 V AwesomePlayer: ~AwesomePlayer call
08-03 19:10:12.872   310  1380 V AwesomePlayer: reset_l() 
08-03 19:10:12.872   310  1380 V AwesomePlayer: cancelPlayerEvents
08-03 19:10:12.872  6952  7054 V SoundPool: close(31)
08-03 19:10:12.872  6952  7054 V SoundPool: pointer = 0x9fffe000, size = 205080, sampleRate = 48000, numChannels = 2
,08-03 19:10:12.886  7022  7022 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:10:12.887  6952  6952 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-03 19:10:12.887  6952  6952 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,08-03 19:10:12.889  7022  7022 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-03 19:10:12.889  7022  7022 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-03 19:10:12.889  7022  7022 V BluetoothSapReceiver: SapReceiver onReceive 
08-03 19:10:12.890  6952  6952 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:7109
08-03 19:10:12.890  7022  7022 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:10:12.890  7022  7022 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-03 19:10:12.896  6969  6969 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-03 19:10:13.062  1031  1374 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3d0eb06 type 2 when 155527 com.google.android.gms} when 155527
,08-03 19:10:13.074  6744  6744 I UEI.SmartControl: Supports setup maps: true
08-03 19:10:13.091  6744  6744 D UEI.SmartControl: QS start statue = true Error code = 0
08-03 19:10:13.091  6744  6744 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-03 19:10:13.091  6744  6744 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-03 19:10:13.091  6744  6744 I UEI.SmartControl: ### init IR Blaster...
,08-03 19:10:13.094  6744  6744 D serial_port: Configuring serial port
,08-03 19:10:13.095  6744  6744 E UEI.SmartControl: UEIBLaster setting for 616
08-03 19:10:13.095  6744  6744 I UEI.SmartControl: Setting serial record hearder size = 2
08-03 19:10:13.095  6744  6744 I UEI.SmartControl: configuring settings for MAXQ616
08-03 19:10:13.095  6744  6744 I UEI.SmartControl: Get version...
08-03 19:10:13.114  6744  7064 D UEI.SmartControl: serial port data available: 21
,08-03 19:10:13.139  6744  6744 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-03 19:10:13.140  6744  6744 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-03 19:10:13.140  6744  6744 I UEI.SmartControl: QS saving settings...
08-03 19:10:13.141  6744  6744 D UEI.SmartControl: IR Blaster version: 25672567
,08-03 19:10:13.157  6744  7064 D UEI.SmartControl: serial port data available: 4
,08-03 19:10:13.186  6744  7070 I UEI.SmartControl: Device manager: loading config....
,08-03 19:10:13.187  6744  6744 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-03 19:10:13.188  6744  7070 D UEI.SmartControl: ----------- loading internal config...
,08-03 19:10:13.190  6744  6744 E UEI.SmartControl: Services init done
08-03 19:10:13.190  6744  6744 D UEI.SmartControl: QS Service init finished
08-03 19:10:13.191  6744  6744 D UEI.SmartControl: QS Service version name: 2.1.91
08-03 19:10:13.191  6744  6744 D UEI.SmartControl: QS Service version code: 201091
08-03 19:10:13.191  6744  6744 D UEI.SmartControl: Service requested: Control
08-03 19:10:13.196  6744  7070 E UEI.SmartControl: Loading SETTINGS...
08-03 19:10:13.197  6744  6744 D UEI.SmartControl: Request IControl service: devices are loaded...
08-03 19:10:13.199  6744  6744 D UEI.SmartControl: Internal service binding...
08-03 19:10:13.201  6952  6952 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,08-03 19:10:13.202  6744  6764 I UEI.SmartControl: ------ IControl API: 11
08-03 19:10:13.203  6744  6764 D UEI.SmartControl: File observer start...
08-03 19:10:13.204  6744  6764 E UEI.SmartControl: IR Port is disabled: false
08-03 19:10:13.205  6744  6764 D UEI.SmartControl: Starting file observer...
08-03 19:10:13.205  6744  7070 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-03 19:10:13.207  6744  6764 I UEI.SmartControl: Registering callback...
08-03 19:10:13.208  6744  6765 I UEI.SmartControl: ------ IControl API: 19
08-03 19:10:13.209  6744  6765 I UEI.SmartControl: Registering Services Ready callback...
08-03 19:10:13.226  6744  7069 I UEI.SmartControl: Notify AllClients services are ready: 0
08-03 19:10:13.226  6744  7069 D UEI.SmartControl: -----service ready thread exits
08-03 19:10:13.227  6952  6968 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-03 19:10:13.228  6952  7052 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-03 19:10:13.228  6952  7052 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
,08-03 19:10:13.229  6952  6952 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-03 19:10:13.229  6952  6952 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-03 19:10:13.230  6744  6764 I UEI.SmartControl: ------ IControl API: 8
08-03 19:10:13.233  6952  6952 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-03 19:10:13.233  6952  6952 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-03 19:10:13.234  6952  6952 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-03 19:10:13.234  6952  6952 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-03 19:10:13.235  6952  6952 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-03 19:10:13.236  6952  6952 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
,08-03 19:10:13.238  6952  6952 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-03 19:10:13.243  6952  6952 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-03 19:10:13.245  6952  6952 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-03 19:10:13.248  6952  6952 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-03 19:10:13.248  6952  6952 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-03 19:10:13.249  6952  6952 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-03 19:10:13.252  6952  6952 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-03 19:10:13.253  6952  6952 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-03 19:10:13.256  6952  6952 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1470244213255]
,08-03 19:10:13.263  6952  6952 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-03 19:10:13.268  1031  1918 I ActivityManager: Killing 6544:com.lge.email/u0a23 (adj 15): empty #17
,08-03 19:10:13.291  6952  7072 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-03 19:10:13.324  1031  1918 I ActivityManager: Killing 6053:com.android.contacts/u0a19 (adj 15): empty #18
,08-03 19:10:13.363  1031  2040 W libprocessgroup: failed to open /acct/uid_10023/pid_6544/cgroup.procs: No such file or directory
,08-03 19:10:13.367  1031  2010 W libprocessgroup: failed to open /acct/uid_10019/pid_6053/cgroup.procs: No such file or directory
08-03 19:10:13.373  6952  6952 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-03 19:10:13.374  6952  6952 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-03 19:10:13.375  6952  6952 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-03 19:10:13.376  6952  6952 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-03 19:10:13.377  6952  6952 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
,08-03 19:10:13.377  6952  6952 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-03 19:10:13.378  6952  6952 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-03 19:10:13.396  6952  6952 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-03 19:10:13.402  1031  1374 V AlarmManager: ELAPSED_WAKEUP set : Alarm{840bb1d type 2 when 155867 com.google.android.gms} when 155867
,08-03 19:10:14.073  1031  1374 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1200b192 type 2 when 156533 com.google.android.gms} when 156533
,08-03 19:10:14.112  1031  1574 D WifiServiceImplEx: setWifiEnabled: true pid=6643, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-03 19:10:14.113  1031  1574 D WifiService: setWifiEnabled: true pid=6643, uid=10118
08-03 19:10:14.113  1031  1574 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-03 19:10:14.141  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-03 19:10:14.141  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-03 19:10:14.142  1031  1031 D Ulp_jni : JNI:system_update. Event-4
08-03 19:10:14.143  1031  1537 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-03 19:10:14.143  1031  1537 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-03 19:10:14.152  1031  1537 E WifiUtil: wfc_util_ffile_check_copy(): pid[1031] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-03 19:10:14.152  1031  1537 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-03 19:10:14.152  1031  1537 E WifiUtil: wfc_util_ffile_check_copy(): pid[1031] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-03 19:10:14.152  1031  1537 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-03 19:10:14.152  1031  1537 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-03 19:10:14.152  1031  1537 E WifiHW  : unknown target_country: EU , set to default
08-03 19:10:14.153  1031  1537 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-03 19:10:14.153  1031  1537 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-03 19:10:14.153  1031  1537 I WifiUtil: gEnableBmps=1
,08-03 19:10:14.165  1031  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-03 19:10:14.172  1031  1095 D Tethering: MasterInitialState.processMessage what=3
08-03 19:10:14.179  1031  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-03 19:10:14.185  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:10:14.186  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:10:14.191  1031  1089 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-03 19:10:14.194  1031  1095 D Tethering: MasterInitialState.processMessage what=3
08-03 19:10:14.203  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 19:10:14.206  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:10:14.208  6454  6454 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-03 19:10:14.213  6454  6488 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-03 19:10:14.225  5790  5790 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-03 19:10:14.233  5790  5790 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-03 19:10:14.251  2195  2195 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-03 19:10:14.301  1031  1089 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-03 19:10:14.333  1031  1975 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7097 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-03 19:10:14.336  1031  1089 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 19:10:14.338  1031  1089 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-03 19:10:14.408  7097  7097 I AppUp4:AppBoxCP: onCreate
08-03 19:10:14.409  7097  7097 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-03 19:10:14.418  7097  7097 I AppUp4:DB:  setFingerPrint start
,08-03 19:10:14.419  7097  7097 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-03 19:10:14.427  7097  7097 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,08-03 19:10:14.427  7097  7097 I AppUp4:DB:  SDK version = 21
08-03 19:10:14.427  7097  7097 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-03 19:10:14.430  7097  7097 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-03 19:10:14.432  7097  7097 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-03 19:10:14.432  7097  7097 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-03 19:10:14.434  7097  7097 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-03 19:10:14.435  7097  7097 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-03 19:10:14.441  7097  7097 I AppUp4:CustModeStarterReceiver: onReceive
,08-03 19:10:14.493  7097  7097 D LgDataFeature: LgDataFeature() Constructor: none
08-03 19:10:14.493  7097  7097 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 19:10:14.504  7097  7097 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1fe2068d
,08-03 19:10:14.504  7097  7097 D AppUp4:CustFacade: isCustomizationCompleted : false
08-03 19:10:14.504  7097  7097 D AppUp4:CustFacade: isPhone : true
08-03 19:10:14.505  7097  7097 D AppUp4:CustModeStarterReceiver: begin check event
08-03 19:10:14.505  7097  7097 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-03 19:10:14.506  7097  7097 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-03 19:10:14.506  7097  7114 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-03 19:10:14.507  7097  7114 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-03 19:10:14.507  7097  7114 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-03 19:10:14.511  1031  2030 I ActivityManager: Killing 6083:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-03 19:10:14.592  1031  1047 W libprocessgroup: failed to open /acct/uid_10027/pid_6083/cgroup.procs: No such file or directory
08-03 19:10:14.593  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-03 19:10:14.594  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-03 19:10:14.602  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 19:10:14.606  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 19:10:14.613  4297  7122 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-03 19:10:14.617  4297  7123 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-03 19:10:14.617  4297  7123 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-03 19:10:14.660  1031  1902 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7124 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-03 19:10:14.730  7124  7124 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-03 19:10:14.731  7124  7124 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-03 19:10:14.732  7124  7124 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-03 19:10:14.733  7124  7124 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-03 19:10:14.835  7124  7124 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-03 19:10:14.864  1031  1095 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-03 19:10:14.867   305   891 D SoftapController: Softap fwReload - Ok
,08-03 19:10:14.869  1031  1537 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (706ms)
08-03 19:10:14.871  7124  7124 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-03 19:10:14.877   305   891 D CommandListener: Setting iface cfg
08-03 19:10:14.878   305   891 D CommandListener: Trying to bring down wlan0
,08-03 19:10:14.879   305   891 D CommandListener: Clearing all IP addresses on wlan0
08-03 19:10:14.882  1031  1537 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-03 19:10:14.877  7149  7149 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6496 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 19:10:14.877  7149  7149 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6496 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-03 19:10:14.906  7149  7149 I wpa_supplicant: Successfully initialized wpa_supplicant
08-03 19:10:14.921  7124  7124 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-03 19:10:14.934  7149  7149 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-03 19:10:14.935  7149  7149 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-03 19:10:14.938  1031  1095 D Tethering: InitialState.processMessage what=4
08-03 19:10:14.939  1031  1095 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-03 19:10:14.959  7124  7124 D LgDataFeature: LgDataFeature() Constructor: none
08-03 19:10:14.959  7124  7124 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 19:10:14.983  1031  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-03 19:10:14.983  1031  1537 E WifiStateMachine: useWiFiOffloading() : false
08-03 19:10:14.983  1031  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-03 19:10:14.984  1031  1537 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-03 19:10:14.984  1031  1537 D WifiMonitor: connecting to supplicant
08-03 19:10:14.984  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-03 19:10:14.985  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-03 19:10:14.987  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:10:14.988  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-03 19:10:14.988  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:10:15.010  7149  7149 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-03 19:10:15.070  7124  7124 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-03 19:10:15.079  7149  7149 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-03 19:10:15.093  7149  7149 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-03 19:10:15.094  7149  7149 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,08-03 19:10:15.095  1031  1537 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-03 19:10:15.096  1031  7153 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-03 19:10:15.096  1031  7153 D WifiMonitor: Dropping event because (p2p0) is stopped
08-03 19:10:15.096  1031  7153 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-03 19:10:15.096  1031  7153 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-03 19:10:15.097  1031  1537 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-03 19:10:15.098  1031  1537 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-03 19:10:15.098  1031  1537 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-03 19:10:15.099  1031  1537 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-03 19:10:15.099  1031  7153 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-03 19:10:15.099  1031  7153 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-03 19:10:15.101  1031  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-03 19:10:15.102  1031  1537 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-03 19:10:15.103  1031  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-03 19:10:15.105  1031  1537 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-03 19:10:15.105  1031  1537 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-03 19:10:15.105  1031  1537 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-03 19:10:15.106  1031  1537 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-03 19:10:15.106  1031  1537 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-03 19:10:15.107  1031  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-03 19:10:15.107  1031  1537 E WifiStateMachine: useWiFiOffloading() : false
08-03 19:10:15.107  1031  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-03 19:10:15.108  1031  1537 D WifiNative-wlan0: doBoolean: SET update_config 1
08-03 19:10:15.108  1031  1537 D WifiNative-wlan0: SET update_config 1: returned true
08-03 19:10:15.108  1031  1537 D WifiConfigStore: Loading config and enabling all networks 
08-03 19:10:15.108  1031  1537 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-03 19:10:15.109  1031  1537 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-03 19:10:15.109  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:15.109  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:15.110  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:15.110  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:15.110  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-03 19:10:15.111  1939  1939 D WfdService: Waiting for WifiP2p enabling
08-03 19:10:15.112  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:10:15.116  6643  6643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:10:15.116  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:10:15.116  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:10:15.116  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:10:15.116  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:10:15.116  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 19:10:15.116  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:10:15.116  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:10:15.116  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 19:10:15.116  6643  6643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:10:15.116  6643  6643 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-03 19:10:15.117  1031  1537 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-03 19:10:15.117  6643  6643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:10:15.118  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:10:15.118  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:10:15.118  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:10:15.118  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:10:15.118  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 19:10:15.118  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:10:15.118  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:10:15.118  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 19:10:15.118  6643  6643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:10:15.118  6643  6643 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-03 19:10:15.120  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
,08-03 19:10:15.121  1031  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-03 19:10:15.125  3487  3487 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-03 19:10:15.125  3487  3487 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-03 19:10:15.126  3487  3487 I LgeMiscReceiver: networkInfo.isConnected() = false
08-03 19:10:15.127  1031  1537 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-03 19:10:15.127  1031  1537 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-03 19:10:15.134  7124  7124 I HubEmail: JNI_OnLoad()
08-03 19:10:15.134  7124  7124 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-03 19:10:15.134  7124  7124 I HubEmail: registerNatives()
08-03 19:10:15.134  7124  7124 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-03 19:10:15.134  7124  7124 I HubEmail: registerNativeMethods()
08-03 19:10:15.134  7124  7124 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-03 19:10:15.134  7124  7124 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,08-03 19:10:15.176  1031  1975 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7159 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-03 19:10:15.180  1031  1537 D WifiStateMachine: enableVerboseLogging : level 2
08-03 19:10:15.180  1031  1537 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-03 19:10:15.181  1031  1537 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-03 19:10:15.182  1031  1537 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-03 19:10:15.182  1031  1537 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-03 19:10:15.182  1031  1537 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-03 19:10:15.183  1031  1537 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-03 19:10:15.183  1031  1537 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-03 19:10:15.183  1031  1537 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-03 19:10:15.183  1031  1537 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-03 19:10:15.184  1031  1537 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-03 19:10:15.184  6992  7156 W FormManager: Network not available. Please check & try again.
08-03 19:10:15.184  1031  1537 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-03 19:10:15.184  1031  1537 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-03 19:10:15.184  1031  1537 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-03 19:10:15.185  1031  1537 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-03 19:10:15.186  1031  1537 D WifiStateMachine: Setting OUI to DA-A1-19
08-03 19:10:15.186  1031  1537 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-03 19:10:15.187  1031  1537 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-03 19:10:15.187  1031  1537 D WifiNative-HAL: Setting external_sim to 1
08-03 19:10:15.187  1031  1537 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-03 19:10:15.187  1031  1537 D WifiNative-wlan0: SET external_sim 1: returned true
08-03 19:10:15.187  1031  1537 I WifiNative-HAL: startHal
08-03 19:10:15.187  1031  1537 D wifi    : setting scan oui 0xaf6dc500
08-03 19:10:15.188  1031  1537 D WifiStateMachine: Setting OUI to DA-A1-19
08-03 19:10:15.188  1031  1537 I WifiNative-HAL: startHal
08-03 19:10:15.188  1031  1537 D wifi    : setting scan oui 0xaf6dc500
08-03 19:10:15.188  1031  1537 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-03 19:10:15.189  1031  1537 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-03 19:10:15.189  1031  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-03 19:10:15.189  7149  7149 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-03 19:10:15.190  1031  1537 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-03 19:10:15.190  1031  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-03 19:10:15.190  7149  7149 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-03 19:10:15.190  1939  1939 D WfdsService: Supplicant Connection state is changed : true
08-03 19:10:15.191  1031  1537 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-03 19:10:15.191  1031  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-03 19:10:15.191  7149  7149 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-03 19:10:15.191  1031  1537 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-03 19:10:15.191  1031  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-03 19:10:15.192  7149  7149 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-03 19:10:15.192  1031  1537 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-03 19:10:15.192  1031  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-03 19:10:15.192  7149  7149 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
,08-03 19:10:15.193  1031  1537 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-03 19:10:15.193  1031  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-03 19:10:15.193  7149  7149 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-03 19:10:15.193  1939  2356 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-03 19:10:15.193  1939  2356 D WfdsService: Set the WFDS Monitor: true
08-03 19:10:15.193  1939  2356 D WfdsMonitor: WfdsMonitorThread create
08-03 19:10:15.193  1031  1537 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-03 19:10:15.193  1031  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-03 19:10:15.193  7149  7149 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-03 19:10:15.194  1031  1537 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-03 19:10:15.195  1031  1537 E WifiNative: : [157,661,712 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
,08-03 19:10:15.195  1031  1537 D WifiNative-wlan0: doBoolean: RECONNECT
08-03 19:10:15.195  1031  1537 D WifiNative-wlan0: RECONNECT: returned true
08-03 19:10:15.195  1031  1537 D WifiNative-wlan0: doString: [STATUS]
08-03 19:10:15.196  1031  7153 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-03 19:10:15.196  1031  7153 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-03 19:10:15.196  1031  1537 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-03 19:10:15.196  1031  1537 D WifiNative-wlan0: doBoolean: SET ps 1
08-03 19:10:15.196  1939  2356 D WfdsMonitor: WFDS Monitor is created and started
08-03 19:10:15.196  1939  2356 D WfdsService: WiFi: Supplicant connection re-established
08-03 19:10:15.197  1031  1537 D WifiNative-wlan0: SET ps 1: returned true
,08-03 19:10:15.197  1031  1536 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:15.198  1031  1537 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-03 19:10:15.198  1031  1031 D WifiScanningService: SCAN_AVAILABLE : 3
08-03 19:10:15.198  1031  1031 D RttService: SCAN_AVAILABLE : 3
08-03 19:10:15.198  1031  1555 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:15.198  1031  1555 I WifiNative-HAL: startHal
08-03 19:10:15.198  1031  1537 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-03 19:10:15.198  1031  1555 D wifi    : getting scan capabilities on interface[1] = 0xaf6dc500
08-03 19:10:15.198  1031  1555 D wifi    : failed to get capabilities : -3
08-03 19:10:15.198  1031  1555 E WifiScanningService: could not get scan capabilities
08-03 19:10:15.199  1031  1556 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:15.199  1031  1537 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-03 19:10:15.199  1031  1537 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-03 19:10:15.199   305   891 D CommandListener: Setting iface cfg
08-03 19:10:15.199   305   891 D CommandListener: Trying to bring up p2p0
08-03 19:10:15.200  1031  1537 E WifiStateMachine:  DisconnectedState what:132106 1 0
,08-03 19:10:15.200  1031  1536 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-03 19:10:15.200  1031  1536 D LGWifiP2pService: P2pEnablingState
08-03 19:10:15.200  1031  1536 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:15.200  1031  1536 D LGWifiP2pService: P2p socket connection successful
08-03 19:10:15.200  1031  1536 D LGWifiP2pService: P2pEnabledState
,08-03 19:10:15.200  1031  1536 D LGWifiP2pService: sending p2p connection changed broadcast
08-03 19:10:15.201  1939  7167 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-03 19:10:15.201  1031  1536 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-03 19:10:15.202  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
,08-03 19:10:15.202  1031  1537 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-03 19:10:15.202  1939  7167 E CtrlSupplicant: Succeed to open control connection
08-03 19:10:15.202  1031  1537 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-03 19:10:15.202  1031  1537 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
,08-03 19:10:15.202  1939  1939 D WfdsService: WifiP2pState is changed : true
08-03 19:10:15.202  1939  2356 D WfdsService: Receive the WFDS_ENABLE Method
08-03 19:10:15.202  7149  7149 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-03 19:10:15.202  1939  2356 D WfdsService: Set the WFDS Monitor: true
,08-03 19:10:15.202  1939  2356 D WfdsService: Connected to the supplicant for wfds
08-03 19:10:15.202  1939  2356 D WfdsJNI : doCommand: WFDS_SET TRUE
08-03 19:10:15.202  7149  7149 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-03 19:10:15.203  1939  2356 D WfdsService: selectPreferredScanChannel [36]
,08-03 19:10:15.203  1939  2356 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-03 19:10:15.203  1031  1537 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-03 19:10:15.203  1939  1939 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-03 19:10:15.203  1939  7167 E CtrlSupplicant: Succeed to open monitor connection
,08-03 19:10:15.204  1031  1537 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-03 19:10:15.204  1939  7167 D WfdsMonitor: Supplicant connection established
08-03 19:10:15.204  1939  1939 D WfdsService: isConnected: false
08-03 19:10:15.204  1031  1537 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-03 19:10:15.204  1031  1537 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100,
08-03 19:10:15.204  7149  7149 E wpa_supplicant: disconnect_rssi_lvl: -100
08-03 19:10:15.204  1939  2356 D WfdsService: Received the Event that WfdsMonitor is connected to supplicant
08-03 19:10:15.205  1031  1537 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-03 19:10:15.205  1031  1537 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
,08-03 19:10:15.205  1031  1537 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-03 19:10:15.205  1031  1537 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-03 19:10:15.206  1031  1536 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-03 19:10:15.207  7149  7149 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,08-03 19:10:15.208  1031  1536 D WifiNative-p2p0: doBoolean: SET device_name G3
,08-03 19:10:15.208  7149  7149 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 19:10:15.209  1031  7153 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-03 19:10:15.209  1031  7153 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 19:10:15.209  1031  7153 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 19:10:15.209  1031  7153 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 19:10:15.209  7149  7149 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-03 19:10:15.209  7149  7149 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:10:15.209  1031  7153 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 19:10:15.209  1031  7153 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:10:15.210  1031  7153 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:10:15.210  1031  7153 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:10:15.210  7149  7149 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:10:15.211  1939  7167 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 19:10:15.212  1939  7167 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 19:10:15.212  1031  7153 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,08-03 19:10:15.212  1031  7153 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:10:15.212  1031  7153 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:10:15.212  1031  7153 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:10:15.212  1031  1537 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-03 19:10:15.213  1031  1537 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-03 19:10:15.213  1031  1537 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
,08-03 19:10:15.214  1031  1537 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-03 19:10:15.214  1031  1537 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-03 19:10:15.214  1031  1536 D WifiNative-p2p0: SET device_name G3: returned true
08-03 19:10:15.214  1031  1536 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-03 19:10:15.214  1031  1536 D LGWifiP2pService: before postfix = G3
08-03 19:10:15.214  1031  1536 D WifiServerServiceExt: postfix byte check : 2
08-03 19:10:15.214  1031  1536 D LGWifiP2pService: after postfix = G3
08-03 19:10:15.214  1031  1536 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-03 19:10:15.214  1031  1536 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-03 19:10:15.214  1031  1536 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-03 19:10:15.215  1031  1536 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-03 19:10:15.215  1031  1536 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-03 19:10:15.215  1031  1536 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-03 19:10:15.215  1031  1536 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-03 19:10:15.216  1031  1536 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-03 19:10:15.216  1031  1536 D WifiNative-HAL: p2pGetDeviceAddress
08-03 19:10:15.216  1031  1536 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-03 19:10:15.218  1939  1939 I WfdStateTracker: handleP2pThisDeviceChanged
08-03 19:10:15.218  7149  7149 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-03 19:10:15.218  7149  7149 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-03 19:10:15.219  7124  7158 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:15.219  1031  7153 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-03 19:10:15.219  1031  7153 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-03 19:10:15.219  1031  1537 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-03 19:10:15.219  1031  7153 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-03 19:10:15.219  1031  1537 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-03 19:10:15.219  1031  7153 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-03 19:10:15.220  1939  1939 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
,08-03 19:10:15.220  1939  1939 D WfdsService: Update P2p Interface State: 3
08-03 19:10:15.221  1031  1536 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-03 19:10:15.221  1031  1536 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-03 19:10:15.221  6992  7157 V FormManager: Network unavailable.
08-03 19:10:15.222  1031  1537 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-03 19:10:15.222  1031  1537 D WifiNative-wlan0: doBoolean: SCAN
08-03 19:10:15.222  1031  1537 D WifiNative-wlan0: SCAN: returned false
08-03 19:10:15.223  1031  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=157690  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-03 19:10:15.224  1031  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=157691  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-03 19:10:15.224  1031  1537 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-03 19:10:15.225  1031  1537 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-03 19:10:15.225  1031  1537 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-03 19:10:15.225  1031  1537 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-03 19:10:15.226  1031  1537 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-03 19:10:15.227  1031  1536 D WifiNative-p2p0: P2P_FLUSH: returned true
08-03 19:10:15.227  1031  1536 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-03 19:10:15.228  1031  1536 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-03 19:10:15.228  1031  1536 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-03 19:10:15.228  1031  1536 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-03 19:10:15.228  1031  1536 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-03 19:10:15.230  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 19:10:15.230  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 19:10:15.232  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:10:15.234  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:15.234  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:15.234  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-03 19:10:15.234  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 19:10:15.234  1031  1031 D WifiServerServiceExt: setSupplicantStateSCANNING
,08-03 19:10:15.235  6992  7157 V FormManager: Network unavailable.
08-03 19:10:15.246  1031  1046 I ActivityManager: Killing 6182:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-03 19:10:15.249  1031  1536 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-03 19:10:15.249  1031  1536 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-03 19:10:15.281  1031  1536 D LGWifiP2pService: InactiveState
08-03 19:10:15.281  1031  1536 D LGWifiP2pService: InactiveState{ when=-69ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:15.281  1031  1536 D LGWifiP2pService: P2pEnabledState{ when=-69ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:15.281  1031  1536 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-03 19:10:15.283  7149  7149 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-03 19:10:15.283  7149  7149 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-03 19:10:15.284  7149  7149 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-03 19:10:15.284  7149  7149 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:10:15.284  1031  1536 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-03 19:10:15.285  1031  1536 D LGWifiP2pService: InactiveState{ when=-57ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:15.285  1031  1536 D LGWifiP2pService: P2pEnabledState{ when=-57ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:15.285  1031  1536 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:15.285  1031  1536 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:15.285  1031  1536 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:15.285  7149  7149 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:10:15.285  1031  1536 D LGWifiP2pService: InactiveState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:15.285  1031  1536 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:15.285  1031  1536 D LGWifiP2pService: DefaultState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:15.285  1031  1536 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:15.286  1031  1536 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:15.286  1031  1536 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:15.286  1939  7167 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-03 19:10:15.286  1939  7167 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 19:10:15.286  1939  7167 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 19:10:15.286  1031  7153 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-03 19:10:15.286  1031  7153 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 19:10:15.286  1031  7153 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 19:10:15.286  1031  7153 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 19:10:15.286  1031  7153 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 19:10:15.286  1031  7153 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:10:15.286  1031  7153 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:10:15.286  1031  1941 W libprocessgroup: failed to open /acct/uid_10080/pid_6182/cgroup.procs: No such file or directory
08-03 19:10:15.286  1031  7153 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:10:15.286  1031  7153 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 19:10:15.286  1031  7153 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:10:15.287  1031  7153 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:10:15.287  1031  7153 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:10:15.287  1031  1536 D LGWifiP2pService: InactiveState{ when=-2ms what=139283, arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:15.287  1031  1536 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:15.287  1031  1536 D LGWifiP2pService: DefaultState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:15.287  1031  1031 E WifiServerServiceExt: No p2p device connected
08-03 19:10:15.288  1939  2356 W WfdsService: DefaultState - msg [9441285] is not handled
08-03 19:10:15.369  7159  7159 D LgDataFeature: LgDataFeature() Constructor: none
,08-03 19:10:15.370  7159  7159 D LgDataFeature: LgDataFeature() Constructor Done, null
08-03 19:10:15.380  7159  7159 D PhoneMonitor: Register our PhoneStateListener
,08-03 19:10:15.415  7159  7159 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-03 19:10:15.419  7159  7159 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-03 19:10:15.448  7159  7159 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-03 19:10:15.451  7159  7159 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-03 19:10:15.453  7159  7159 D TelephonyAutoProfiling: [parse] Load xml
08-03 19:10:15.458  7159  7159 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-03 19:10:15.458  7159  7159 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-03 19:10:15.458  7159  7159 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-03 19:10:15.458  7159  7159 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-03 19:10:15.459  7159  7159 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-03 19:10:15.459  7159  7159 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-03 19:10:15.459  7159  7159 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
,08-03 19:10:15.459  7159  7159 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-03 19:10:15.459  7159  7159 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-03 19:10:15.459  7159  7159 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-03 19:10:15.459  7159  7159 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-03 19:10:15.459  7159  7159 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-03 19:10:15.459  7159  7159 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-03 19:10:15.459  7159  7159 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-03 19:10:15.459  7159  7159 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-03 19:10:15.460  7159  7159 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-03 19:10:15.460  7159  7159 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
08-03 19:10:15.473  7159  7159 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-03 19:10:15.492  1031  1941 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7179 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-03 19:10:15.492  1031  1941 I ActivityManager: Killing 6586:com.google.android.apps.docs/u0a61 (adj 15): empty #17
08-03 19:10:15.551  1031  1918 W libprocessgroup: failed to open /acct/uid_10061/pid_6586/cgroup.procs: No such file or directory
,08-03 19:10:15.666  1031  7153 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-03 19:10:15.666  1031  7153 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-03 19:10:15.667  1031  7153 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-03 19:10:15.667  1031  7153 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
08-03 19:10:15.667  7149  7149 E wpa_supplicant: USIM:  scard_init function
08-03 19:10:15.667  1031  7153 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-03 19:10:15.668  7149  7149 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-03 19:10:15.670  1031  7153 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
,08-03 19:10:15.670  1031  7153 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-03 19:10:15.672  1031  1537 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
08-03 19:10:15.673  1031  1537 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
08-03 19:10:15.674  1031  1537 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
08-03 19:10:15.675  1031  1537 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
08-03 19:10:15.675  1031  1537 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-03 19:10:15.690  1031  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=158157  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-03 19:10:15.695  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 19:10:15.695  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 19:10:15.697  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:15.697  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:10:15.698  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:15.698  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-03 19:10:15.727  1031  1943 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7197 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-03 19:10:15.730  1031  1943 I ActivityManager: Killing 6211:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-03 19:10:15.797  1031  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=158264  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-03 19:10:15.798  7149  7149 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-03 19:10:15.801  1031  7153 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-03 19:10:15.802  1031  7153 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-03 19:10:15.802  1031  7153 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-03 19:10:15.802  1031  7153 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-03 19:10:15.803  1031  7153 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-03 19:10:15.804  1031  1902 W libprocessgroup: failed to open /acct/uid_10097/pid_6211/cgroup.procs: No such file or directory
08-03 19:10:15.808  1031  7153 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-03 19:10:15.811  1031  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=158278  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-03 19:10:15.811  1031  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=158279  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-03 19:10:15.812  1031  1537 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=158279
,08-03 19:10:15.812  1031  1537 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=158280
08-03 19:10:15.814  7149  7149 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-03 19:10:15.815  7149  7149 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-03 19:10:15.816  1031  1537 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=158283
08-03 19:10:15.816  1031  1537 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=158284
08-03 19:10:15.817  1031  1537 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=158284
08-03 19:10:15.818  1031  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=158285  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-03 19:10:15.819  1031  7153 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-03 19:10:15.819  1031  7153 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-03 19:10:15.819  1031  7153 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-03 19:10:15.819  1031  7153 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-03 19:10:15.820  1031  7153 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-03 19:10:15.820  1031  7153 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-03 19:10:15.820  1031  7153 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-03 19:10:15.820  1031  7153 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-03 19:10:15.821  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 19:10:15.821  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 19:10:15.822  1031  7153 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-03 19:10:15.822  1031  7153 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-03 19:10:15.823  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:10:15.824  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:15.824  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:15.824  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-03 19:10:15.824  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 19:10:15.824  1031  1031 D WifiServerServiceExt: setSupplicantStateASSOCIATING
,08-03 19:10:15.829  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:15.829  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:15.829  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-03 19:10:15.830  1031  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=158297  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-03 19:10:15.832  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:15.832  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:15.833  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-03 19:10:15.833  1031  1095 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-03 19:10:15.834  1031  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=158301  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-03 19:10:15.834  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 19:10:15.834  1031  1031 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-03 19:10:15.835  1031  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=158303  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-03 19:10:15.836  1031  1537 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=158304
08-03 19:10:15.837  1031  1537 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=158304
08-03 19:10:15.837  1031  1537 D WifiNative-wlan0: doString: [STATUS]
08-03 19:10:15.838  1031  1537 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-03 19:10:15.838  1031  7153 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-03 19:10:15.838  1031  7153 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-03 19:10:15.840  1031  1537 I WifiServiceExtension: setVHTCapabilityType  : false
08-03 19:10:15.847  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 19:10:15.847  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 19:10:15.848  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:10:15.850  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 19:10:15.850  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 19:10:15.852  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-03 19:10:15.856  1031  1537 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-03 19:10:15.856  1031  1537 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-03 19:10:15.859  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:15.860  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:15.860  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-03 19:10:15.869  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-03 19:10:15.869  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 19:10:15.870  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:15.870  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:15.870  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-03 19:10:15.872  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:10:15.872  1031  1537 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-03 19:10:15.872  1031  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-03 19:10:15.872  1031  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-03 19:10:15.873  1031  1543 D ConnectivityService: Got NetworkAgent Messenger
08-03 19:10:15.873  1031  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-03 19:10:15.873  1031  1543 D ConnectivityService: NetworkAgent connected
08-03 19:10:15.873  1031  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-03 19:10:15.873  1031  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-03 19:10:15.874  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 19:10:15.874  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 19:10:15.875  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:10:15.884  1031  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-03 19:10:15.884  1031  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-03 19:10:15.884  1031  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,08-03 19:10:15.884  1031  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-03 19:10:15.884  1031  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-03 19:10:15.892  1031  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-03 19:10:15.893   305   891 D CommandListener: Setting iface cfg
08-03 19:10:15.962  1031  1941 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7221 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-03 19:10:15.964  1031  1941 I ActivityManager: Killing 6680:com.lge.eula/1000 (adj 15): empty #17
,08-03 19:10:16.013  1031  1725 W libprocessgroup: failed to open /acct/uid_1000/pid_6680/cgroup.procs: No such file or directory
,08-03 19:10:16.019  1031  1537 E WifiStateMachine: Start Dhcp Watchdog 2
08-03 19:10:16.019  1031  7219 D DhcpStateMachine: StoppedState
08-03 19:10:16.019  1031  7219 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:16.019  1031  7219 D DhcpStateMachine: WaitBeforeStartState
08-03 19:10:16.021  1031  1537 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=158488  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-03 19:10:16.023  1031  1537 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=158490  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-03 19:10:16.024  1031  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=158491  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-03 19:10:16.026  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 19:10:16.026  1031  1031 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-03 19:10:16.027  1031  1537 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-03 19:10:16.028  1031  1537 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-03 19:10:16.029  1031  1537 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-03 19:10:16.030  1031  1537 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-03 19:10:16.032  1031  1537 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-03 19:10:16.033  1031  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-03 19:10:16.034  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 19:10:16.034  1031  1031 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-03 19:10:16.035  1031  1537 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=158502  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-03 19:10:16.036  1031  1537 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=158503  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-03 19:10:16.037  1031  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=158505  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-03 19:10:16.040  1031  1537 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:112985] from screen [on:0 period:1365400808] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-03 19:10:16.042  1031  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:1365400810] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-03 19:10:16.042  1031  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-03 19:10:16.056  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:10:16.058  1031  1543 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-03 19:10:16.059  1031  1537 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:10:16.059  1031  1537 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:10:16.060  1031  1537 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:10:16.060  1031  1537 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:10:16.061  1031  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:10:16.061  1031  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:10:16.062  1031  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-03 19:10:16.063  1031  1537 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=127,0,0
08-03 19:10:16.063  1031  1537 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=127,0,0
08-03 19:10:16.063  1031  1537 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
,08-03 19:10:16.064  7149  7149 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-03 19:10:16.064  1031  1537 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-03 19:10:16.064  1031  1537 D WifiNative-wlan0: doBoolean: SET ps 0
08-03 19:10:16.065  1031  1537 D WifiNative-wlan0: SET ps 0: returned true
08-03 19:10:16.065  1031  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-03 19:10:16.065  7149  7149 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-03 19:10:16.065  1031  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-03 19:10:16.065  1031  1537 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-03 19:10:16.065  1031  1537 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-03 19:10:16.065  1031  1537 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-03 19:10:16.065  1031  1536 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@350ecc20 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:16.066  1031  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@350ecc20 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:16.066  1031  7219 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:16.066   305   891 D CommandListener: Setting iface cfg
08-03 19:10:16.066  1031  7219 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-03 19:10:16.066   305   891 D CommandListener: Trying to bring up wlan0
08-03 19:10:16.068  1031  1537 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-03 19:10:16.069  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 19:10:16.069  1031  1031 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-03 19:10:16.069  1031  1537 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:10:16.070  1031  1537 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:10:16.070  1031  1537 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:10:16.071  1031  1537 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:10:16.071  1031  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:10:16.072  1031  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:10:16.073  1031  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,08-03 19:10:16.073  1031  1537 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-03 19:10:16.074  1031  1537 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-03 19:10:16.074  1031  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-03 19:10:16.074  7149  7149 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-03 19:10:16.074  1031  1536 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:16.075  1031  1536 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:16.075  1031  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-03 19:10:16.075  1031  1537 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
,08-03 19:10:16.075  7149  7149 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
,08-03 19:10:16.080  1031  1537 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-03 19:10:16.080  1031  1537 D WifiNative-wlan0: doBoolean: SET ps 1
08-03 19:10:16.088  7221  7221 I art     : Almond Protected OAT
,08-03 19:10:16.095  1031  1537 D WifiNative-wlan0: SET ps 1: returned true
08-03 19:10:16.096  1031  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-03 19:10:16.097  1031  1537 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-03 19:10:16.098  1031  1537 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-03 19:10:16.098  1031  1537 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-03 19:10:16.099  1031  1543 D ConnectivityService: ignoring duplicate network state non-change
08-03 19:10:16.103  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 19:10:16.103  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-03 19:10:16.105  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:10:16.109  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:16.109  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:16.109  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-03 19:10:16.111  1031  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-03 19:10:16.112  1031  1543 D ConnectivityService: Adding iface wlan0 to network 101
08-03 19:10:16.116  1031  1536 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:16.116  1031  1536 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:16.116  1031  1536 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-03 19:10:16.117  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:16.117  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:16.117  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-03 19:10:16.122  1031  1537 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-03 19:10:16.124  1031  1031 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-03 19:10:16.129  1939  1939 V WfdStateTracker: handleWifiStateChangedEvent: 1
,08-03 19:10:16.132  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 19:10:16.132  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 19:10:16.133  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:10:16.133  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:16.133  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:16.133  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-03 19:10:16.135  1031  1031 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-03 19:10:16.139  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 19:10:16.139  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-03 19:10:16.139  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:10:16.140  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:16.141  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:16.141  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-03 19:10:16.158  1031  1543 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-03 19:10:16.158  1031  1543 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-03 19:10:16.159  1031  1537 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-03 19:10:16.159  1031  1537 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-03 19:10:16.159  1031  1537 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-03 19:10:16.159  1031  1543 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-03 19:10:16.160  1031  1537 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-03 19:10:16.160  1031  1537 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-03 19:10:16.160   305   891 E Netd    : netlink response contains error (File exists)
08-03 19:10:16.161  1031  1537 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-03 19:10:16.161  1031  1543 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-03 19:10:16.162  1031  1543 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-03 19:10:16.162  1031  1543 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-03 19:10:16.162  1031  1543 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-03 19:10:16.163  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 19:10:16.163  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-03 19:10:16.163  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:10:16.168  1031  1543 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-03 19:10:16.168  1031  1543 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-03 19:10:16.169  1031  1543 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-03 19:10:16.169  1031  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-03 19:10:16.169  1031  7214 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:16.169  1031  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-03 19:10:16.169  1031  7214 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-03 19:10:16.169  1031  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 19:10:16.169  1031  7214 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:16.169  1031  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-03 19:10:16.169  1031  7214 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-03 19:10:16.169  1031  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:10:16.169  1031  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-03 19:10:16.169  1031  1543 D ConnectivityService: currentScore = 0, newScore = 20
08-03 19:10:16.169  1031  1543 D ConnectivityService:    accepting network in place of null
08-03 19:10:16.169  1031  1543 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:10:16.171  1850  1850 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:10:16.171  1031  1537 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:10:16.171  1031  1537 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-03 19:10:16.171  7221  7221 D WeatherApplication: removeAccount
08-03 19:10:16.171  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-03 19:10:16.171  1031  1543 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNEC,TED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-03 19:10:16.171  1031  1543 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-03 19:10:16.171  1031  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-03 19:10:16.172   305  7242 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-03 19:10:16.173  1031  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-03 19:10:16.173  1031  1543 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-03 19:10:16.174  1031  1543 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-03 19:10:16.175  1031  1543 D ConnectivityService: validation of new default Network = false
08-03 19:10:16.175  1031  1543 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-03 19:10:16.175  1031  1543 D DSQN    : enableDataServiceNotify 
08-03 19:10:16.175  1031  1543 D DSQN    : start dsqn bin
,08-03 19:10:16.176  1031  1031 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-03 19:10:16.176  1031  1031 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-03 19:10:16.176  1031  1031 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-03 19:10:16.176  1031  1031 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-03 19:10:16.177  7221  7221 D WeatherApplication: Account.length = 0
08-03 19:10:16.179  7221  7221 E WeatherApplication: OPERATOR:OPEN
08-03 19:10:16.188  7221  7221 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:10:16
,08-03 19:10:16.196  1031  1535 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-03 19:10:16.201  7221  7221 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-03 19:10:16.201  7221  7221 D Weather.Utils: 2 : All the weather widget is gone.
,08-03 19:10:16.205  7221  7221 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-03 19:10:16.208  7221  7221 D WeatherAncestor: connectivity changed - connection : true
08-03 19:10:16.209  7221  7221 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-03 19:10:16.210  1815  7243 I CheckinService: active receiver: enabled
08-03 19:10:16.225   305  7242 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-03 19:10:16.258   305  7242 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-03 19:10:16.265  1031  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-03 19:10:16.266  1031  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:10:16.266  1031  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 19:10:16.257  7245  7245 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6496 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 19:10:16.257  7245  7245 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6496 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 19:10:16.270  1031  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 19:10:16.270  1031  7219 D DhcpStateMachine: DHCPV4 request on wlan0
,08-03 19:10:16.271  1031  7219 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-03 19:10:16.271  1031  7219 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-03 19:10:16.271  1602  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-03 19:10:16.273  7221  7221 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-03 19:10:16.273  7221  7221 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-03 19:10:16.273  7221  7221 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-03 19:10:16.267  7246  7246 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6496 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 19:10:16.267  7246  7246 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6496 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 19:10:16.276  1815  7243 I CheckinService: Preparing to send checkin request
08-03 19:10:16.276  1815  7243 I EventLogService: Accumulating logs since 1470244115301
08-03 19:10:16.279  7246  7246 I dhcpcd  : version 5.5.6 starting
08-03 19:10:16.280  7245  7245 E DSQN    : DSQN ssw
08-03 19:10:16.280  7246  7246 E dhcpcd  : get_duid: m
08-03 19:10:16.280  7246  7246 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-03 19:10:16.280  7246  7246 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-03 19:10:16.286  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-03 19:10:16.287  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:10:16.288  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:10:16.289  7221  7221 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-03 19:10:16.289  7221  7221 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:10:16
08-03 19:10:16.305   305   890 D LGDataListener: argv[0]=dsqncommand
08-03 19:10:16.305   305   890 D LGDataListener: argv[1]=wlan0
08-03 19:10:16.305   305   890 D LGDataListener: argv[2]=1
08-03 19:10:16.305   305   890 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-03 19:10:16.306  1031  1093 D DSQN    : DSQM DsqnNotification wlan0  1
08-03 19:10:16.306  1031  1093 D DSQN    : start to monitor internet connection
,08-03 19:10:16.320  1031  2010 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7259 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-03 19:10:16.321  1031  2010 I ActivityManager: Killing 6705:com.lge.bnr/1000 (adj 15): empty #17
08-03 19:10:16.324  7246  7246 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-03 19:10:16.324  7246  7246 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-03 19:10:16.324  7246  7246 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-03 19:10:16.325  7246  7246 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-03 19:10:16.325  7246  7246 D dhcpcd  : wlan0: sending REQUEST (xid 0xdcf882d2), next in 3.84 seconds
08-03 19:10:16.349  7246  7246 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,08-03 19:10:16.350  1031  7214 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 03 Aug 2016 17:10:16 GMT], X-Android-Received-Millis=[1470244216349], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470244216302]}
08-03 19:10:16.350  1031  7214 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-03 19:10:16.350  1031  7214 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-03 19:10:16.350  1031  1543 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-03 19:10:16.350  1031  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-03 19:10:16.350  1031  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-03 19:10:16.351  1031  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 19:10:16.351  1031  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-03 19:10:16.351  1031  1543 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-03 19:10:16.351  1031  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-03 19:10:16.351  1031  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:10:16.351  1031  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 19:10:16.351  1031  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 19:10:16.351  1031  1543 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:10:16.352  1602  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-03 19:10:16.352  1031  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-03 19:10:16.352  1031  1537 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:10:16.352  1031  1537 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-03 19:10:16.352  1850  1850 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:10:16.352  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-03 19:10:16.360  7246  7246 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-03 19:10:16.360  7246  7246 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
,08-03 19:10:16.361  1031  1938 W libprocessgroup: failed to open /acct/uid_1000/pid_6705/cgroup.procs: No such file or directory
08-03 19:10:16.361  7246  7246 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-03 19:10:16.361  7246  7246 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-03 19:10:16.361  7246  7246 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-03 19:10:16.362  7246  7246 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-03 19:10:16.362  7246  7246 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-03 19:10:16.362  7246  7246 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-03 19:10:16.363  1815  7243 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-03 19:10:16.385  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-03 19:10:16.386  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:10:16.387  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-03 19:10:16.438   278   364 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-03 19:10:16.438   278   364 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,08-03 19:10:16.438   278   364 W Vold    : Returning OperationFailed - no handler for errno 0
,08-03 19:10:16.438  7259  7285 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-03 19:10:16.439   278   364 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-03 19:10:16.439   278   364 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-03 19:10:16.439   278   364 W Vold    : Returning OperationFailed - no handler for errno 0
08-03 19:10:16.439  7259  7285 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-03 19:10:16.450   278   364 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-03 19:10:16.450   278   364 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-03 19:10:16.450   278   364 W Vold    : Returning OperationFailed - no handler for errno 0
08-03 19:10:16.451  7259  7287 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-03 19:10:16.453   278   364 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-03 19:10:16.453   278   364 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-03 19:10:16.453   278   364 W Vold    : Returning OperationFailed - no handler for errno 0
08-03 19:10:16.454  7259  7287 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-03 19:10:16.472  1031  1725 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7293 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-03 19:10:16.486   342   342 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 297us total 14.831ms
08-03 19:10:16.497   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 184us total 9.931ms
,08-03 19:10:16.507   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 186us total 9.137ms
,08-03 19:10:16.524  7293  7293 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-03 19:10:16.525  7293  7293 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-03 19:10:16.545  7293  7293 I MultiDex: VM with version 2.1.0 has multidex support
08-03 19:10:16.545  7293  7293 I MultiDex: install
08-03 19:10:16.545  7293  7293 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-03 19:10:16.551  7293  7293 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-03 19:10:16.652  7259  7259 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-03 19:10:16.661  7259  7259 I LibraryLoader: Loading: webviewchromium
08-03 19:10:16.665  7259  7259 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 9140-9144)
08-03 19:10:16.665  7259  7259 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-03 19:10:16.670  7259  7259 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2e8dcaec}
08-03 19:10:16.672  7259  7259 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-03 19:10:16.672  7259  7259 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-03 19:10:16.673  1031  7219 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-03 19:10:16.674  1031  7219 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-03 19:10:16.674  1031  7219 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-03 19:10:16.675  1031  7219 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-03 19:10:16.675  1031  7219 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-03 19:10:16.675  1031  7219 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-03 19:10:16.675  1031  7219 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-03 19:10:16.675  1031  7219 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-03 19:10:16.675  1031  7219 D DhcpStateMachine: RunningState
08-03 19:10:16.680  7259  7259 I BrowserStartupController: Initializing chromium process, renderers=0
,08-03 19:10:16.683  7259  7259 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-03 19:10:16.702  7259  7259 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-03 19:10:16.703  7259  7259 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-03 19:10:16.703  7259  7259 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,08-03 19:10:16.709   310  1381 V AudioPolicyService: registerClient() client 0xb1019460, uid 10093
08-03 19:10:16.710  7259  7340 W AudioManagerAndroid: Requires BLUETOOTH permission
08-03 19:10:16.723  7259  7259 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-03 19:10:16.723  7259  7259 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-03 19:10:16.723  7259  7259 I Adreno-EGL: Build Date: 12/12/14 금
08-03 19:10:16.723  7259  7259 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-03 19:10:16.723  7259  7259 I Adreno-EGL: Remote Branch: 
08-03 19:10:16.723  7259  7259 I Adreno-EGL: Local Patches: 
08-03 19:10:16.723  7259  7259 I Adreno-EGL: Reconstruct Branch: 
,08-03 19:10:16.781  7293  7314 D LgDataFeature: LgDataFeature() Constructor: none
08-03 19:10:16.781  7293  7314 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 19:10:16.799  7259  7259 I NSApplication: Starting up...
,08-03 19:10:16.860  1031  1941 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7354 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-03 19:10:16.861  1031  1941 I ActivityManager: Killing 6128:com.android.vending/u0a44 (adj 15): empty #17
08-03 19:10:16.862  7353  7353 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-03 19:10:16.908  7353  7353 I dex2oat : dex2oat took 45.841ms (threads: 4)
,08-03 19:10:16.923  7293  7314 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-03 19:10:16.923  7293  7314 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-03 19:10:16.923  7293  7314 I Adreno-EGL: Build Date: 12/12/14 금
08-03 19:10:16.923  7293  7314 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-03 19:10:16.923  7293  7314 I Adreno-EGL: Remote Branch: 
08-03 19:10:16.923  7293  7314 I Adreno-EGL: Local Patches: 
08-03 19:10:16.923  7293  7314 I Adreno-EGL: Reconstruct Branch: 
,08-03 19:10:16.961  1031  1047 W libprocessgroup: failed to open /acct/uid_10044/pid_6128/cgroup.procs: No such file or directory
08-03 19:10:16.961  1031  1374 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3b5b03 type 2 when 159353 com.google.android.gms} when 159353
,08-03 19:10:17.098  1031  1975 I art     : Explicit concurrent mark sweep GC freed 88411(4MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 1.615ms total 132.171ms
,08-03 19:10:17.119  7354  7354 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-03 19:10:17.145  1031  1047 D WifiServiceImplEx: setWifiEnabled: false pid=6643, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-03 19:10:17.146  1031  1047 D WifiService: setWifiEnabled: false pid=6643, uid=10118
08-03 19:10:17.146  1031  1047 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-03 19:10:17.165  1031  1537 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-03 19:10:17.165  1031  1537 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-03 19:10:17.166  1031  1537 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-03 19:10:17.166  1031  1537 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-03 19:10:17.166  1031  1537 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-03 19:10:17.166  1031  1537 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-03 19:10:17.166  1031  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-03 19:10:17.166  1031  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-03 19:10:17.166  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-03 19:10:17.167  1031  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-03 19:10:17.167  1031  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-03 19:10:17.167  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-03 19:10:17.167  1031  1031 D Ulp_jni : JNI:system_update. Event-4
08-03 19:10:17.176  1031  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-03 19:10:17.176  1031  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-03 19:10:17.176  1031  1536 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:17.176  1031  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:17.176  7149  7149 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,08-03 19:10:17.176  1031  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-03 19:10:17.177  1031  1537 D WifiNative-wlan0: doBoolean: SET ps 1
08-03 19:10:17.177  1031  1537 D WifiNative-wlan0: SET ps 1: returned true
08-03 19:10:17.177  1031  7219 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:17.177   305   891 D CommandListener: Clearing all IP addresses on wlan0
08-03 19:10:17.198  1031  1536 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:17.198  1031  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:17.198  1031  1536 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@319af9f3
08-03 19:10:17.198  1031  1536 D LGWifiP2pService: P2pDisablingState
08-03 19:10:17.198  1031  1536 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:17.198  1031  1536 D LGWifiP2pService: p2p socket connection lost
08-03 19:10:17.198  1031  1536 D LGWifiP2pService: P2pDisabledState
08-03 19:10:17.198  1031  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:10:17.198  1031  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:10:17.199  1031  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:10:17.199  1031  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:10:17.200  1031  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-03 19:10:17.203  1031  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-03 19:10:17.203  1031  1543 D ConnectivityService: ignoring duplicate network state non-change
08-03 19:10:17.203  1031  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
08-03 19:10:17.203  1031  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:10:17.204  1031  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-03 19:10:17.204  1031  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-03 19:10:17.204  1031  1536 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:17.204  1031  1536 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:17.204  7149  7149 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-03 19:10:17.206  1031  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-03 19:10:17.206  1031  1537 D WifiNative-wlan0: doBoolean: SET ps 1
08-03 19:10:17.207  1031  1537 D WifiNative-wlan0: SET ps 1: returned true
08-03 19:10:17.232   305   891 D CommandListener: Clearing all IP addresses on wlan0
08-03 19:10:17.233  1031  1543 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-03 19:10:17.233  1031  1543 D DSQN    : disableDataServiceNotify
08-03 19:10:17.233  1031  1543 D DSQN    : stop dsqn bin
,08-03 19:10:17.234  1031  1537 D WifiNative-p2p0: doBoolean: TERMINATE
08-03 19:10:17.234  1031  1537 D WifiNative-p2p0: TERMINATE: returned true
08-03 19:10:17.234  1031  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-03 19:10:17.234  1031  1537 E WifiStateMachine: useWiFiOffloading() : false
08-03 19:10:17.234  1031  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-03 19:10:17.234  1031  1537 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-03 19:10:17.237  1031  1090 W ProcessCpuTracker: Skipping unknown process pid 7246
08-03 19:10:17.238  1031  1031 D WifiHS20: hidePasspointNotification off =false
08-03 19:10:17.239  1939  1939 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-03 19:10:17.239  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 19:10:17.239  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 19:10:17.240  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:10:17.240  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:17.241  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:17.241  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-03 19:10:17.241  1031  1031 D WifiHS20: hidePasspointNotification off =false
08-03 19:10:17.244  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:17.244  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:17.244  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-03 19:10:17.244  1031  1031 D WifiScanningService: SCAN_AVAILABLE : 1
08-03 19:10:17.244  1031  1555 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:17.245  1031  1031 D RttService: SCAN_AVAILABLE : 1
08-03 19:10:17.245  1031  1556 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:17.246  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-03 19:10:17.246  1031  1543 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-03 19:10:17.246  1031  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:10:17.246  1031  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 19:10:17.246  1031  1543 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 19:10:17.246  1031  1543 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-03 19:10:17.246  1939  1939 D WfdsService: WifiP2pState is changed : false
08-03 19:10:17.246  1939  2356 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-03 19:10:17.247  1939  2356 D WfdsService: Set the WFDS Monitor: false
08-03 19:10:17.247  1031  1543 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::,/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-03 19:10:17.247  1031  1543 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-03 19:10:17.247  1031  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-03 19:10:17.247  1602  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-03 19:10:17.247  1031  7214 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:17.247  1031  7214 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:17.247  1031  7214 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-03 19:10:17.248  1031  1031 D WifiHS20: hidePasspointNotification off =false
08-03 19:10:17.248  1939  2356 D WfdsMonitor: WFDS Monitor is stopped
08-03 19:10:17.248  1939  2356 D WfdsService: STATE : WfdsDisabledState - enter
08-03 19:10:17.248  1939  7167 D CtrlSupplicant: Received on exit socket, terminate
08-03 19:10:17.248  1939  7167 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-03 19:10:17.248  1939  7167 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
,08-03 19:10:17.248  1939  7167 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-03 19:10:17.248  1939  2357 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-03 19:10:17.249  1939  2356 W WfdsService: DefaultState - msg [9445378] is not handled
08-03 19:10:17.250  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:17.250  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:17.250  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-03 19:10:17.251  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-03 19:10:17.253  1031  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-03 19:10:17.253  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-03 19:10:17.253  1031  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-03 19:10:17.253  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 19:10:17.253  1031  1031 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-03 19:10:17.253  1031  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-03 19:10:17.253  1031  1543 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:10:17.253  1031  1543 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:10:17.253  1031  1543 D NetworkManagementService: Removing idletimer
08-03 19:10:17.253  1031  1543 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:17.253  1850  1850 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:10:17.254  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-03 19:10:17.255  1031  1537 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:10:17.255  1031  1537 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-03 19:10:17.255  6643  6643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:10:17.256  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:10:17.256  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:10:17.256  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:10:17.256  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 19:10:17.256  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 19:10:17.256  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:10:17.256  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:10:17.256  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - active n,etwork type is Wi-Fi: true
08-03 19:10:17.256  6643  6643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:10:17.256  6643  6643 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 19:10:17.256  6643  6643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:10:17.256  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:10:17.256  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:10:17.256  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:10:17.256  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 19:10:17.256  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 19:10:17.256  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:10:17.256  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:10:17.256  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 19:10:17.256  6643  6643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:10:17.256  6643  6643 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 19:10:17.257  1031  1535 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-03 19:10:17.257  1031  1535 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-03 19:10:17.257  1031  1031 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-03 19:10:17.257  1031  1031 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-03 19:10:17.257  1031  1031 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-03 19:10:17.257  1031  1031 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-03 19:10:17.257  1031  1031 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-03 19:10:17.257  1031  1031 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-03 19:10:17.257  1031  1031 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-03 19:10:17.257  1031  1031 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-03 19:10:17.259  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 19:10:17.259  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 19:10:17.260  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-03 19:10:17.264  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-03 19:10:17.264  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 19:10:17.264  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:10:17.265  1031  1543 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
08-03 19:10:17.271  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-03 19:10:17.283  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-03 19:10:17.284  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:10:17.285  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:10:17.298  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-03 19:10:17.299  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:10:17.299  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-03 19:10:17.321  7149  7149 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-03 19:10:17.321  7149  7149 I wpa_supplicant: monitor socket send errors count : 1
08-03 19:10:17.321  7149  7149 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1939-4\x00 that cannot receive messages
,08-03 19:10:17.322  1031  7153 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-03 19:10:17.323  1031  7153 D WifiMonitor: Dropping event because (p2p0) is stopped
08-03 19:10:17.335  6454  6454 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-03 19:10:17.337  6454  6488 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-03 19:10:17.343  7149  7149 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-03 19:10:17.343  1031  7153 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-03 19:10:17.343  1031  7153 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-03 19:10:17.343  1031  7153 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-03 19:10:17.344  1031  7153 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-03 19:10:17.344  1031  1095 D Tethering: InitialState.processMessage what=4
08-03 19:10:17.344  7149  7149 W wpa_supplicant: USIM:  scard_deinit function
08-03 19:10:17.344  1031  1537 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=159811
08-03 19:10:17.344  1031  1537 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=159812
08-03 19:10:17.344  1031  1095 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-03 19:10:17.344  1031  7153 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-03 19:10:17.344  1031  7153 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-03 19:10:17.345  1031  1537 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=159812  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-03 19:10:17.345  1031  1537 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=159813  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
,08-03 19:10:17.346  1031  1537 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-03 19:10:17.346  1031  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-03 19:10:17.353  2195  2195 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-03 19:10:17.359  7097  7097 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-03 19:10:17.359  7097  7097 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-03 19:10:17.360  7097  7097 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-03 19:10:17.360  7097  7097 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-03 19:10:17.360  7293  7314 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-03 19:10:17.360  7293  7314 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-03 19:10:17.360  7293  7314 I Adreno-EGL: Build Date: 12/12/14 금
08-03 19:10:17.360  7293  7314 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-03 19:10:17.360  7293  7314 I Adreno-EGL: Remote Branch: 
08-03 19:10:17.360  7293  7314 I Adreno-EGL: Local Patches: 
08-03 19:10:17.360  7293  7314 I Adreno-EGL: Reconstruct Branch: 
08-03 19:10:17.361  7097  7097 I AppUp4:CustModeStarterReceiver: onReceive
08-03 19:10:17.364  7097  7097 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1fe2068d
08-03 19:10:17.364  7097  7097 D AppUp4:CustFacade: isCustomizationCompleted : false
08-03 19:10:17.364  7097  7097 D AppUp4:CustFacade: isPhone : true
08-03 19:10:17.365  7097  7097 D AppUp4:CustModeStarterReceiver: begin check event
08-03 19:10:17.365  7097  7097 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,08-03 19:10:17.368  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-03 19:10:17.368  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-03 19:10:17.370  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 19:10:17.372  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-03 19:10:17.376  7124  7124 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-03 19:10:17.380  1031  7219 D DhcpStateMachine: StoppedState
08-03 19:10:17.380  1031  7219 D DhcpStateMachine: StoppedState{ when=-174ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:17.381  1031  1537 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-03 19:10:17.381  1031  1537 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-03 19:10:17.383  4297  7390 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-03 19:10:17.383  4297  7392 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-03 19:10:17.383  4297  7392 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-03 19:10:17.390  7124  7393 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:17.395  3487  3487 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-03 19:10:17.395  3487  3487 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-03 19:10:17.395  3487  3487 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-03 19:10:17.402  7159  7159 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-03 19:10:17.402  7159  7159 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-03 19:10:17.403  7293  7314 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-03 19:10:17.403  7293  7314 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-03 19:10:17.403  7293  7314 I Adreno-EGL: Build Date: 12/12/14 금
08-03 19:10:17.403  7293  7314 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-03 19:10:17.403  7293  7314 I Adreno-EGL: Remote Branch: 
08-03 19:10:17.403  7293  7314 I Adreno-EGL: Local Patches: 
08-03 19:10:17.403  7293  7314 I Adreno-EGL: Reconstruct Branch: 
08-03 19:10:17.408  6992  7397 W FormManager: Network not available. Please check & try again.
,08-03 19:10:17.416  7221  7221 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:10:17
08-03 19:10:17.417  7221  7221 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-03 19:10:17.417  7221  7221 D Weather.Utils: 2 : All the weather widget is gone.
08-03 19:10:17.418  7221  7221 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-03 19:10:17.418  7221  7221 D WeatherAncestor: connectivity changed - connection : true
08-03 19:10:17.418  7221  7221 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1ebb9853
08-03 19:10:17.418  7221  7221 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-03 19:10:17.418  7221  7221 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-03 19:10:17.418  7221  7221 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-03 19:10:17.418  7221  7221 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-03 19:10:17.418  7221  7221 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:10:17
08-03 19:10:17.419  6992  7398 V FormManager: Network unavailable.
08-03 19:10:17.423  6992  7398 V FormManager: Network unavailable.
,08-03 19:10:17.436  6897  6897 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-03 19:10:17.436  6897  6897 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,08-03 19:10:17.436  6897  6897 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-03 19:10:17.436  6897  6897 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-03 19:10:17.437  6897  6897 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-03 19:10:17.441  6897  6897 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-03 19:10:17.441  6897  6897 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-03 19:10:17.441  6897  6897 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-03 19:10:17.441  6897  6897 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-03 19:10:17.441  6897  6897 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-03 19:10:17.441  6897  6897 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-03 19:10:17.447  6918  6918 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-03 19:10:17.450  6897  6897 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-03 19:10:17.452  6992  7402 W FormManager: Network not available. Please check & try again.
08-03 19:10:17.456  6992  7403 V FormManager: Network unavailable.
,08-03 19:10:17.457  6897  6897 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:10:17.457  6992  7403 V FormManager: Network unavailable.
08-03 19:10:17.461  7149  7149 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-03 19:10:17.464  1031  7153 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-03 19:10:17.464  1031  7153 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
08-03 19:10:17.464  1031  7153 D WifiMonitor: Disconnecting from the supplicant, no more events
08-03 19:10:17.465  1031  1537 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
08-03 19:10:17.469   305  7405 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-03 19:10:17.469  1031  1093 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-03 19:10:17.469  1815  7243 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-03 19:10:17.473  6918  6918 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-03 19:10:17.475  6897  6897 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-03 19:10:17.478  6992  7407 W FormManager: Network not available. Please check & try again.
,08-03 19:10:17.480  1815  7243 I CheckinService: active receiver: disabled
08-03 19:10:17.481  6897  6897 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-03 19:10:17.496  6992  7408 V FormManager: Network unavailable.
08-03 19:10:17.498  6992  7408 V FormManager: Network unavailable.
08-03 19:10:17.506  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-03 19:10:17.506  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-03 19:10:17.507  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-03 19:10:17.509  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 19:10:17.512  4297  7409 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-03 19:10:17.514  4297  7410 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-03 19:10:17.514  4297  7410 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-03 19:10:17.541  1031  2030 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7411 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-03 19:10:17.565  1031  1537 D WifiOffDelayIfNotUsed: stopMonitoring
08-03 19:10:17.566  1031  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-03 19:10:17.566  1031  1537 E WifiStateMachine: useWiFiOffloading() : false
08-03 19:10:17.566  1031  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-03 19:10:17.567  1939  1939 D WfdsService: Supplicant Connection state is changed : false
08-03 19:10:17.567  1939  2356 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-03 19:10:17.567  1939  2356 D WfdsService: Set the WFDS Monitor: false
08-03 19:10:17.567  1939  2356 D WfdsMonitor: WFDS Monitor is stopped
,08-03 19:10:17.569  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-03 19:10:17.569  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:10:17.569  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-03 19:10:17.570  1031  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-03 19:10:17.570  1031  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-03 19:10:17.570  2504  2504 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:17.571  6643  6643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:10:17.571  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:10:17.571  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:10:17.571  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:10:17.571  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 19:10:17.571  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 19:10:17.571  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:10:17.571  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:10:17.571  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 19:10:17.572  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 19:10:17.657  7411  7411 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-03 19:10:17.657  7411  7411 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-03 19:10:17.675  7411  7411 V [BNRBootReceiver]: Boot Receiver Return
,08-03 19:10:17.676  7411  7411 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-03 19:10:17.680  6454  6454 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 19:10:17.687  6897  6897 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 19:10:17.695  6897  6897 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:10:17.708  6952  6952 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 19:10:17.708  6952  6952 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-03 19:10:17.710  6952  6952 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-03 19:10:17.717  6897  6897 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-03 19:10:17.720  6897  6897 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,08-03 19:10:17.725  6454  6454 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 19:10:17.739  6897  6897 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 19:10:17.748  6897  6897 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-03 19:10:17.763  6952  6952 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-03 19:10:17.764  6952  6952 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 19:10:17.767  6952  6952 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-03 19:10:17.775  6454  6454 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 19:10:17.789  6897  6897 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 19:10:17.798  6897  6897 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-03 19:10:17.808  6952  6952 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 19:10:17.808  6952  6952 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 19:10:17.809  6952  6952 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-03 19:10:17.818  6454  6454 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 19:10:17.830  6897  6897 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 19:10:17.837  6897  6897 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:10:17.845  6952  6952 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 19:10:17.846  6952  6952 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-03 19:10:17.846  6952  6952 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-03 19:10:17.852  6454  6454 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 19:10:17.866  6897  6897 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 19:10:17.875  6897  6897 D WiFiOffLoadBroadcast: MCCMNC not supported: null,
08-03 19:10:17.884  6952  6952 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 19:10:17.884  6952  6952 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-03 19:10:17.885  6952  6952 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-03 19:10:17.888  6454  6454 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 19:10:17.897  6897  6897 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 19:10:17.905  6897  6897 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:10:17.913  6952  6952 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 19:10:17.913  6952  6952 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-03 19:10:17.914  6952  6952 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-03 19:10:17.919  6454  6454 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 19:10:17.928  6897  6897 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 19:10:17.938  6897  6897 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:10:17.949  6952  6952 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 19:10:17.949  6952  6952 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 19:10:17.950  6952  6952 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-03 19:10:17.964  6454  6454 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-03 19:10:17.979  6897  6897 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 19:10:17.987  6897  6897 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:10:17.999  6952  6952 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-03 19:10:18.000  6952  6952 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 19:10:18.007  6952  6952 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-03 19:10:18.015  6454  6454 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-03 19:10:18.028  6897  6897 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 19:10:18.038  6897  6897 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-03 19:10:18.050  6952  6952 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 19:10:18.051  6952  6952 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 19:10:18.052  6952  6952 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-03 19:10:18.060  6454  6454 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 19:10:18.069  6918  6918 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-03 19:10:18.085  1031  1542 D WifiService: New client listening to asynchronous messages
,08-03 19:10:18.085  6918  6918 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-03 19:10:18.090  6897  6897 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 19:10:18.106  6897  6897 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:10:18.118  6952  6952 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 19:10:18.119  6952  6952 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 19:10:18.121  6952  6952 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-03 19:10:18.123  6952  6952 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-03 19:10:18.124  6952  6952 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-03 19:10:18.133  6454  6454 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 19:10:18.145  6918  6918 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-03 19:10:18.147  6918  6918 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-03 19:10:18.157  6897  6897 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 19:10:18.168  6897  6897 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-03 19:10:18.184  6952  6952 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 19:10:18.185  6952  6952 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-03 19:10:18.187  6952  6952 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-03 19:10:18.188  6744  7071 D UEI.SmartControl: Internal timer expired: 2
08-03 19:10:18.189  6952  6952 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-03 19:10:18.189  6744  7071 D UEI.SmartControl: unbind internal service
08-03 19:10:18.190  6952  6952 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-03 19:10:18.197  1031  1941 I ActivityManager: Killing 6877:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-03 19:10:18.229  1031  1975 W libprocessgroup: failed to open /acct/uid_10037/pid_6877/cgroup.procs: No such file or directory
,08-03 19:10:18.234  6744  7065 D serial_port: close(fd = 24)
08-03 19:10:18.238  2195  2195 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE,
08-03 19:10:18.241  6744  7065 I UEI.SmartControl: Serial port is closed.
08-03 19:10:18.256  2195  2195 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-03 19:10:18.257  2195  2195 D c       : Getting all permits...
08-03 19:10:18.258  2195  2195 D a       : Opening database...
08-03 19:10:18.270  2195  2195 D a       : Opening database auth.proximity.permit_store...
,08-03 19:10:18.271  2195  2195 D a       : Closing database...
08-03 19:10:18.287  6454  6454 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-03 19:10:18.288   305  7436 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-03 19:10:18.291  1031  1093 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-03 19:10:18.296  6918  6918 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-03 19:10:18.296  6918  6918 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-03 19:10:18.296  6918  6918 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-03 19:10:18.301  6897  6897 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 19:10:18.310  6897  6897 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:10:18.320  6952  6952 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 19:10:18.321  6952  6952 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-03 19:10:18.323  6952  6952 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-03 19:10:18.330  6454  6454 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 19:10:18.337  6918  6918 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-03 19:10:18.337  6918  6918 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-03 19:10:18.337  6918  6918 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-03 19:10:18.343  6897  6897 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-03 19:10:18.350  6897  6897 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-03 19:10:18.364  6952  6952 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-03 19:10:18.364  6952  6952 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-03 19:10:18.368  6952  6952 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-03 19:10:18.374  6454  6454 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 19:10:18.378  6918  6918 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-03 19:10:18.378  6918  6918 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-03 19:10:18.378  6918  6918 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-03 19:10:18.382  6897  6897 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 19:10:18.390  6897  6897 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:10:18.399  6952  6952 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 19:10:18.400  6952  6952 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-03 19:10:18.405  6952  6952 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-03 19:10:18.419  6918  6918 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-03 19:10:18.427  6897  6897 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-03 19:10:18.437  6992  7438 W FormManager: Network not available. Please check & try again.
08-03 19:10:18.438  6897  6897 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:10:18.449  6992  7439 V FormManager: Network unavailable.
,08-03 19:10:18.465  6992  7439 V FormManager: Network unavailable.
,08-03 19:10:18.467  2195  2195 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
08-03 19:10:18.489  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-03 19:10:18.490  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-03 19:10:18.495  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 19:10:18.502  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 19:10:18.508  4297  7440 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-03 19:10:18.511  4297  7441 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,08-03 19:10:18.512  4297  7441 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-03 19:10:18.522  6918  6918 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-03 19:10:18.522  6918  6918 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-03 19:10:18.522  6918  6918 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-03 19:10:18.530  6897  6897 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-03 19:10:18.537  6992  7443 W FormManager: Network not available. Please check & try again.
,08-03 19:10:18.540  6897  6897 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:10:18.548  6992  7444 V FormManager: Network unavailable.
,08-03 19:10:18.562  6992  7444 V FormManager: Network unavailable.
,08-03 19:10:19.063  1031  1537 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:1365403831] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-03 19:10:19.065  1031  1537 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:1365403833] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-03 19:10:19.176  1031  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-03 19:10:19.188  1031  1095 D Tethering: MasterInitialState.processMessage what=3
08-03 19:10:19.199  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 19:10:19.203  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:10:19.206  1031  1089 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-03 19:10:19.209  6454  6454 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-03 19:10:19.211  6454  6488 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-03 19:10:19.224  5790  5790 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-03 19:10:19.241  2195  2195 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-03 19:10:19.261  7097  7097 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-03 19:10:19.261  7097  7097 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-03 19:10:19.261  7097  7097 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-03 19:10:19.261  7097  7097 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-03 19:10:19.266  7097  7097 I AppUp4:CustModeStarterReceiver: onReceive
08-03 19:10:19.270  7097  7097 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1fe2068d
08-03 19:10:19.270  7097  7097 D AppUp4:CustFacade: isCustomizationCompleted : false
08-03 19:10:19.270  7097  7097 D AppUp4:CustFacade: isPhone : true
08-03 19:10:19.271  7097  7097 D AppUp4:CustModeStarterReceiver: begin check event
08-03 19:10:19.271  7097  7097 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-03 19:10:19.275  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-03 19:10:19.276  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-03 19:10:19.280  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 19:10:19.283  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 19:10:19.290  7124  7124 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-03 19:10:19.316  4297  7452 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-03 19:10:19.333  4297  7456 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-03 19:10:19.334  4297  7456 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-03 19:10:19.339  7124  7453 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:19.342  1031  1089 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 19:10:19.357  3487  3487 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-03 19:10:19.358  3487  3487 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-03 19:10:19.358  3487  3487 I LgeMiscReceiver: networkInfo.isConnected() = true
08-03 19:10:19.358  3487  3487 D PhoneState: setPdpRejectCasuse : false
,08-03 19:10:19.365  7159  7159 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-03 19:10:19.368  6992  7454 W FormManager: Network not available. Please check & try again.
08-03 19:10:19.368  7159  7159 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-03 19:10:19.368  6992  7455 V FormManager: Network unavailable.
08-03 19:10:19.384  6992  7455 V FormManager: Network unavailable.
,08-03 19:10:19.391  7221  7221 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:10:19
,08-03 19:10:19.395  7221  7221 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-03 19:10:19.395  7221  7221 D Weather.Utils: 2 : All the weather widget is gone.
,08-03 19:10:19.396  7221  7221 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-03 19:10:19.396  7221  7221 D WeatherAncestor: connectivity changed - connection : true
08-03 19:10:19.396  7221  7221 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1ebb9853
08-03 19:10:19.397  7221  7221 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-03 19:10:19.397  7221  7221 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-03 19:10:19.397  7221  7221 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-03 19:10:19.397  7221  7221 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-03 19:10:19.397  7221  7221 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:10:19
08-03 19:10:20.166  1031  1986 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:10:20.167  1031  1986 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-03 19:10:20.206  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-03 19:10:20.206  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-03 19:10:20.206  1031  1031 D Ulp_jni : JNI:system_update. Event-4
08-03 19:10:20.207  1031  1095 D BluetoothManagerService: Message: 1
08-03 19:10:20.207  1031  1095 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-03 19:10:20.234  1031  1095 D BluetoothManagerService: Message: 20
08-03 19:10:20.234  1031  1095 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3e968a5e:true
,08-03 19:10:20.239  7022  7022 D BluetoothAdapterState: make
,08-03 19:10:20.244  7022  7022 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-03 19:10:20.244  7022  7022 I bluedroid-qcom: init
08-03 19:10:20.245  7022  7484 I BluetoothAdapterState: Entering OffState
08-03 19:10:20.246  7022  7022 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-03 19:10:20.246  7022  7022 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-03 19:10:20.246  7022  7022 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-03 19:10:20.246  7022  7022 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-03 19:10:20.246  7022  7022 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-03 19:10:20.248  7022  7022 I bluedroid-qcom: get_profile_interface socket
08-03 19:10:20.248  7022  7022 I bluedroid-qcom: get_profile_interface map_client
,08-03 19:10:20.253  7022  7488 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-03 19:10:20.254  1031  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-03 19:10:20.247  7487  7487 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6496 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 19:10:20.258  1031  1095 D Tethering: MasterInitialState.processMessage what=3
08-03 19:10:20.247  7487  7487 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6496 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 19:10:20.268  1031  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-03 19:10:20.277  7487  7487 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-03 19:10:20.277  7487  7487 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-03 19:10:20.277  7487  7487 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-03 19:10:20.278  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:10:20.279  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:10:20.284  7487  7487 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,08-03 19:10:20.289  1031  1095 D Tethering: MasterInitialState.processMessage what=3
08-03 19:10:20.294  7487  7487 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-03 19:10:20.294  7487  7487 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-03 19:10:20.296  7022  7488 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-03 19:10:20.304  1031  1031 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-03 19:10:20.305  1031  1031 D BluetoothManagerService: Stored Bluetooth name: G3
,08-03 19:10:20.308  6454  6454 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-03 19:10:20.335  1031  1089 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-03 19:10:20.339  6454  6488 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-03 19:10:20.339  1031  1031 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-03 19:10:20.339  1031  1095 D BluetoothManagerService: Message: 40
,08-03 19:10:20.340  1031  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-03 19:10:20.340  7022  7488 D BluetoothAdapterProperties: Name is: G3
08-03 19:10:20.342  1031  1089 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-03 19:10:20.347  7022  7037 I bluedroid-qcom: config_hci_snoop_log
08-03 19:10:20.347  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:10:20.348  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:10:20.348  1031  1095 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-03 19:10:20.348  1031  1095 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,08-03 19:10:20.355  7022  7484 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-03 19:10:20.356  7022  7484 D BluetoothAdapterProperties: Setting state to 11
08-03 19:10:20.356  7022  7484 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-03 19:10:20.357  1031  1095 D BluetoothManagerService: Message: 60
08-03 19:10:20.357  1031  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-03 19:10:20.358  1031  1095 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-03 19:10:20.358  7022  7484 I LGBluetoothServiceJni: classInitNative: succeeds
08-03 19:10:20.361  5790  5790 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-03 19:10:20.362  1939  1939 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:10:20.364  6897  6897 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-03 19:10:20.365  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-03 19:10:20.368  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:10:20.370  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:10:20.377  7022  7022 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-03 19:10:20.378  1031  1089 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 19:10:20.378  1031  1089 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 19:10:20.378  7022  7022 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:10:20.378  7022  7022 V BluetoothPbapReceiver: ***********state = 11
,08-03 19:10:20.379  7022  7484 D BluetoothBondStateMachine: make
08-03 19:10:20.383  7022  7484 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ebb9853
08-03 19:10:20.383  7022  7484 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-03 19:10:20.383  7022  7484 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ebb9853
08-03 19:10:20.383  7022  7484 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-03 19:10:20.383  2195  2195 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-03 19:10:20.384  7022  7484 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-03 19:10:20.384  7022  7506 I BluetoothBondStateMachine: StableState(): Entering Off State
08-03 19:10:20.386  5790  5790 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-03 19:10:20.390  7022  7484 E BluetoothAdapterService: File transfer profiles supported!!
,08-03 19:10:20.433  1031  1884 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7508 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-03 19:10:20.439  7022  7484 E BluetoothAdapterService: File transfer profiles supported!!
08-03 19:10:20.443  7022  7022 D HeadsetService: Received start request. Starting profile...
08-03 19:10:20.443  7022  7022 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-03 19:10:20.444  7022  7022 D LGBluetoothHfpAdapter: Version 1.6
08-03 19:10:20.447  7022  7022 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-03 19:10:20.448  7022  7022 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-03 19:10:20.449  7022  7022 D HeadsetStateMachine: make
08-03 19:10:20.450  2195  2195 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-03 19:10:20.451  7022  7484 E BluetoothAdapterService: File transfer profiles supported!!
08-03 19:10:20.457  7022  7484 E BluetoothAdapterService: File transfer profiles supported!!
08-03 19:10:20.465  7022  7484 E BluetoothAdapterService: File transfer profiles supported!!
,08-03 19:10:20.473  7022  7484 E BluetoothAdapterService: File transfer profiles supported!!
08-03 19:10:20.474  7097  7097 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-03 19:10:20.475  7097  7097 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-03 19:10:20.475  7097  7097 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-03 19:10:20.475  7097  7097 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-03 19:10:20.482  7022  7484 E BluetoothAdapterService: File transfer profiles supported!!
,08-03 19:10:20.484  7097  7097 I AppUp4:CustModeStarterReceiver: onReceive
08-03 19:10:20.488  7097  7097 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1fe2068d
08-03 19:10:20.488  7097  7097 D AppUp4:CustFacade: isCustomizationCompleted : false
08-03 19:10:20.488  7097  7097 D AppUp4:CustFacade: isPhone : true
08-03 19:10:20.492  7022  7022 D LgDataFeature: LgDataFeature() Constructor: none
08-03 19:10:20.492  7022  7022 D LgDataFeature: LgDataFeature() Constructor Done, null
08-03 19:10:20.493  7097  7097 D AppUp4:CustModeStarterReceiver: begin check event
08-03 19:10:20.495  7097  7097 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-03 19:10:20.495  7022  7484 V LGMDMManager: Create singleton instance
08-03 19:10:20.497  7022  7022 D HeadsetStateMachine: max_hf_connections = 1
08-03 19:10:20.497  7022  7022 I bluedroid-qcom: get_profile_interface handsfree
08-03 19:10:20.497  7022  7484 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-03 19:10:20.499  7022  7022 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-03 19:10:20.501   310  2158 V AudioPolicyService: registerClient() client 0xb1023580, uid 1002
08-03 19:10:20.501   310  1380 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-03 19:10:20.501   310  1380 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-03 19:10:20.501   310  1380 V AudioPolicyManagerEx: getOutput() returns output 2
08-03 19:10:20.501  7022  7022 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-03 19:10:20.502   310  1381 V AudioFlinger: registerClient() client 0xb1433790, pid 7022
08-03 19:10:20.502  7022  7022 V ToneGenerator: Create Track: 0xb4928a80
08-03 19:10:20.502  7022  7022 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-03 19:10:20.502  7022  7022 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-03 19:10:20.502   310  1375 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 19:10:20.502   310   310 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-03 19:10:20.502   310  1375 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-03 19:10:20.502   310   310 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-03 19:10:20.502   310   310 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-03 19:10:20.502   310   310 V AudioPolicyManagerEx: getOutput() returns output 2
08-03 19:10:20.502  7022  7022 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-03 19:10:20.503  1602  1624 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 19:10:20.503  1602  1624 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-03 19:10:20.503  1031  1986 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 19:10:20.503  1031  1986 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-03 19:10:20.503   310  1381 I AudioFlinger: isAudioPlaybackHookOn() false
08-03 19:10:20.503   310  2157 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-03 19:10:20.503   310  2157 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-03 19:10:20.503   310  2157 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-03 19:10:20.503   310  2157 V AudioPolicyManagerEx: getOutput() returns output 2
08-03 19:10:20.503  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-03 19:10:20.504  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-03 19:10:20.504  1850  3970 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 19:10:20.504  1850  3970 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-03 19:10:20.504  7022  7038 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 19:10:20.504  7022  7038 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-03 19:10:20.504  3487  3503 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 19:10:20.504  3487  3503 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-03 19:10:20.504   310  1376 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 19:10:20.504   310  1376 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-03 19:10:20.504  7022  7022 V AudioSystem: getLatency() output 2, latency 50
08-03 19:10:20.504  7022  7022 V AudioSystem: getFrameCount() output 2, frameCount 960
08-03 19:10:20.504  7022  7022 V AudioTrack: createTrack_l() output 2 afLatency 50
08-03 19:10:20.504  1031  1943 V AudioSystem: ioConfigChang,ed() event 0, ioHandle 4
08-03 19:10:20.504  1031  1943 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-03 19:10:20.504  7022  7504 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 19:10:20.504  7022  7504 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-03 19:10:20.504  1850  1865 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 19:10:20.504  1850  1865 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-03 19:10:20.504  3487  3504 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 19:10:20.505  3487  3504 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-03 19:10:20.505   310   310 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-03 19:10:20.505   310   310 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-03 19:10:20.505  1602  2100 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 19:10:20.505  1602  2100 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-03 19:10:20.505   310   310 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-03 19:10:20.505   310   310 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-03 19:10:20.505   310   310 V AudioFlinger: createTrack() lSessionId: 22
08-03 19:10:20.506  7022  7022 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-03 19:10:20.506   310   310 V AudioFlinger: acquiring 22 from 7022, for 7022
08-03 19:10:20.506  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 19:10:20.506   310   310 V AudioFlinger:  added new entry for 22
08-03 19:10:20.506  7022  7022 V ToneGenerator: ToneGenerator INIT OK, time: 162986
08-03 19:10:20.506  7022  7022 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ebb9853
08-03 19:10:20.509  7022  7022 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ebb9853
08-03 19:10:20.509  7022  7523 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-03 19:10:20.510  7022  7523 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-03 19:10:20.510  7022  7523 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-03 19:10:20.510  7022  7523 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-03 19:10:20.511  7022  7022 D A2dpService: Received start request. Starting profile...
,08-03 19:10:20.512  7022  7022 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-03 19:10:20.512  7022  7022 V Avrcp   : make
08-03 19:10:20.513  7022  7022 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-03 19:10:20.513  7022  7022 I bluedroid-qcom: get_profile_interface avrcp
08-03 19:10:20.514   310  1380 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7022
08-03 19:10:20.514   310  1380 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-03 19:10:20.514   310  1380 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-03 19:10:20.514   310  1380 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-03 19:10:20.514   310  1380 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-03 19:10:20.514   310  1380 V voice   : voice_set_parameters: exit with code(0)
08-03 19:10:20.514   310  1380 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-03 19:10:20.514   310  1380 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-03 19:10:20.515   310  1380 V msm8974_platform: platform_set_parameters: exit with code(0)
08-03 19:10:20.515   310  1380 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-03 19:10:20.515   310  1380 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-03 19:10:20.515   310  1380 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-03 19:10:20.515  7022  7523 V ToneGenerator: ToneGenerator destructor
08-03 19:10:20.515  7022  7523 V ToneGenerator: stopTone
08-03 19:10:20.515  7022  7523 V ToneGenerator: Delete Track: 0xb4928a80
08-03 19:10:20.516  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 19:10:20.516  7022  7523 V AudioTrack: ~AudioTrack, releasing session id from 7022 on behalf of 7022
08-03 19:10:20.516   310  1381 V AudioPolicyService: AudioCommandThread() adding release output 2
08-03 19:10:20.516   310  1381 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-03 19:10:20.516   310  1381 V AudioFlinger: PlaybackThread::Track destructor
08-03 19:10:20.516   310  1381 V AudioFlinger: removeClient_l() pid 7022, calling pid 310
08-03 19:10:20.516   310  2157 V AudioFlinger: releasing 22 from 7022 for 7022
08-03 19:10:20.516   310  2157 V AudioFlinger:  decremented refcount to 0
08-03 19:10:20.516   310  2157 V AudioFlinger: purging stale effects
08-03 19:10:20.516   310  1105 V AudioPolicyService: AudioCommandThread() waking up
08-03 19:10:20.516   310  1105 V AudioPolicyService: AudioCommandThread() processing release output 2
08-03 19:10:20.516   310  1105 V AudioPolicyManager: releaseOutput() 2
08-03 19:10:20.516   310  1105 V AudioPolicyService: AudioCommandThread() going to sleep
08-03 19:10:20.519  4297  7529 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-03 19:10:20.521  7022  7022 V AudioManager: registerRemoteController: size of Media player list: 0
,08-03 19:10:20.523  7022  7022 E AudioManager: No RCC entry present to update
,08-03 19:10:20.523  7022  7022 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-03 19:10:20.523  7124  7124 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-03 19:10:20.526  7022  7022 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-03 19:10:20.527  7022  7022 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-03 19:10:20.527  7022  7022 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-03 19:10:20.532  7022  7022 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-03 19:10:20.533  4297  7530 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-03 19:10:20.533  4297  7530 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-03 19:10:20.577  3487  3487 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-03 19:10:20.577  3487  3487 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-03 19:10:20.578  3487  3487 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-03 19:10:20.586  7159  7159 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-03 19:10:20.587  7159  7159 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-03 19:10:20.587  7508  7508 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-03 19:10:20.587  7508  7508 W LG Account v2.2: No ProfileInfo entries
08-03 19:10:20.587  7508  7508 I LG Account v2.2: isEnabled: false
08-03 19:10:20.587  7508  7508 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-03 19:10:20.587  7508  7508 I Feature : [Lifetracker]Country: EU
08-03 19:10:20.587  7508  7508 I Feature : [Lifetracker]Operator: OPEN
08-03 19:10:20.587  7508  7508 I Feature : [Lifetracker]Ranking support: false
08-03 19:10:20.587  7508  7508 I Feature : [Lifetracker]Comfort support: false
08-03 19:10:20.587  7508  7508 I Feature : [Lifetracker]Accessory: true
08-03 19:10:20.587  7508  7508 I Feature : [Lifetracker]Health device: true
08-03 19:10:20.587  7508  7508 I Feature : [Lifetracker]Extra Pedometer: false
08-03 19:10:20.588  7508  7508 I Feature : [Lifetracker]Blood glucose device: false
08-03 19:10:20.588  7508  7508 I Feature : [Lifetracker]Device Number: 3
08-03 19:10:20.588  6992  7535 W FormManager: Network not available. Please check & try again.
08-03 19:10:20.593  7124  7534 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-03 19:10:20.608  7221  7221 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:10:20
,08-03 19:10:20.610  6992  7536 V FormManager: Network unavailable.
08-03 19:10:20.610  7221  7221 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-03 19:10:20.610  7221  7221 D Weather.Utils: 2 : All the weather widget is gone.
08-03 19:10:20.610  7221  7221 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-03 19:10:20.611  7221  7221 D WeatherAncestor: connectivity changed - connection : true
08-03 19:10:20.611  7221  7221 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1ebb9853
08-03 19:10:20.611  7221  7221 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-03 19:10:20.611  6897  6897 D BluetoothPermissionRequest: onReceive
08-03 19:10:20.611  7221  7221 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-03 19:10:20.611  7221  7221 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-03 19:10:20.612  7221  7221 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-03 19:10:20.612  7221  7221 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:10:20
08-03 19:10:20.617  6992  7536 V FormManager: Network unavailable.
08-03 19:10:20.619  6897  6897 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-03 19:10:20.629  1031  2010 V SIM_STK : Menu title from STK is T-Mobile
08-03 19:10:20.629  1031  2010 V SIM_STK : Menu title from STK is T-Mobile
,08-03 19:10:20.636  6454  6454 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-03 19:10:20.638  6454  6488 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-03 19:10:20.648  2195  2195 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-03 19:10:20.655  7097  7097 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-03 19:10:20.655  7097  7097 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-03 19:10:20.655  7097  7097 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-03 19:10:20.656  7097  7097 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-03 19:10:20.657  7097  7097 I AppUp4:CustModeStarterReceiver: onReceive
08-03 19:10:20.660  7097  7097 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1fe2068d
08-03 19:10:20.660  7097  7097 D AppUp4:CustFacade: isCustomizationCompleted : false
08-03 19:10:20.660  7097  7097 D AppUp4:CustFacade: isPhone : true
08-03 19:10:20.661  7097  7097 D AppUp4:CustModeStarterReceiver: begin check event
,08-03 19:10:20.661  7097  7097 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-03 19:10:20.664  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-03 19:10:20.665  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-03 19:10:20.666  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 19:10:20.668  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 19:10:20.674  4297  7539 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-03 19:10:20.674  7124  7124 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-03 19:10:20.687  4297  7540 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,08-03 19:10:20.687  4297  7540 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-03 19:10:20.694  7124  7541 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:20.700  3487  3487 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-03 19:10:20.700  3487  3487 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-03 19:10:20.700  3487  3487 I LgeMiscReceiver: networkInfo.isConnected() = false
08-03 19:10:20.703  7159  7159 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-03 19:10:20.703  7159  7159 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-03 19:10:20.708  1031  1943 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-03 19:10:20.709  6992  7544 W FormManager: Network not available. Please check & try again.
08-03 19:10:20.714  7022  7022 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-03 19:10:20.715  7221  7221 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:10:20
,08-03 19:10:20.717  7221  7221 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-03 19:10:20.717  7221  7221 D Weather.Utils: 2 : All the weather widget is gone.
08-03 19:10:20.717  7022  7022 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-03 19:10:20.718  7022  7022 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-03 19:10:20.718  7221  7221 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-03 19:10:20.718  7022  7022 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-03 19:10:20.718  7022  7022 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-03 19:10:20.718  7221  7221 D WeatherAncestor: connectivity changed - connection : true
08-03 19:10:20.718  7221  7221 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1ebb9853
08-03 19:10:20.718  7022  7022 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-03 19:10:20.718  7022  7022 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-03 19:10:20.718  7022  7022 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-03 19:10:20.718  7022  7022 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-03 19:10:20.719  7022  7022 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-03 19:10:20.719  7022  7022 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-03 19:10:20.719  7221  7221 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-03 19:10:20.719  7221  7221 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-03 19:10:20.719  7221  7221 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-03 19:10:20.719  7221  7221 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-03 19:10:20.719  7022  7022 I BluetoothA2dpServiceJni: classInitNative
08-03 19:10:20.719  7221  7221 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:10:20
08-03 19:10:20.719  7022  7022 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-03 19:10:20.719  7022  7022 D A2dpStateMachine: make
08-03 19:10:20.721  7022  7022 I bluedroid-qcom: get_profile_interface a2dp
08-03 19:10:20.721  7022  7547 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-03 19:10:20.723  7022  7022 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-03 19:10:20.723  7022  7022 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-03 19:10:20.724  6992  7545 V FormManager: Network unavailable.
08-03 19:10:20.724  7022  7022 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ebb9853
08-03 19:10:20.724  7022  7546 D A2dpStateMachine: Enter Disconnected: -2
08-03 19:10:20.725  7022  7022 I BluetoothHidServiceJni: classInitNative: succeeds
08-03 19:10:20.727  7022  7022 D HidService: Received start request. Starting profile...
08-03 19:10:20.727  7022  7022 I bluedroid-qcom: get_profile_interface hidhost
08-03 19:10:20.727  7022  7022 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ebb9853
08-03 19:10:20.728  7022  7022 I BluetoothHealthServiceJni: classInitNative: succeeds
08-03 19:10:20.729  7022  7022 D HealthService: Received start request. Starting profile...
,08-03 19:10:20.731  7022  7022 I bluedroid-qcom: get_profile_interface health
08-03 19:10:20.731  7022  7022 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-03 19:10:20.731  7022  7022 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ebb9853
08-03 19:10:20.732  7022  7022 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-03 19:10:20.732  6992  7545 V FormManager: Network unavailable.
08-03 19:10:20.733  7022  7022 D PanService: Received start request. Starting profile...
08-03 19:10:20.733  7022  7022 D BluetoothPanServiceJni: initializeNative(L110): pan
08-03 19:10:20.733  7022  7022 I bluedroid-qcom: get_profile_interface pan
08-03 19:10:20.738  7022  7022 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-03 19:10:20.738  7022  7022 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ebb9853
08-03 19:10:20.738  7022  7022 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-03 19:10:20.742  7022  7022 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-03 19:10:20.742  7022  7022 D BtGatt.GattService: Received start request. Starting profile...
08-03 19:10:20.742  7022  7022 D BtGatt.GattService: start()
08-03 19:10:20.743  7022  7022 I bluedroid-qcom: get_profile_interface gatt
08-03 19:10:20.743  7022  7022 D BtGatt.AdvertiseManager: advertise manager created
08-03 19:10:20.748  7022  7022 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ebb9853
08-03 19:10:20.749  7022  7022 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ebb9853
08-03 19:10:20.749  7022  7022 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-03 19:10:20.750  7022  7022 V BluetoothMapService: BluetoothMapBinder()
08-03 19:10:20.751  7022  7022 D BluetoothMapService: Received start request. Starting profile...
08-03 19:10:20.751  7022  7022 D BluetoothMapService: start()
08-03 19:10:20.753  7022  7022 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-03 19:10:20.753  7022  7022 D BluetoothMapEmailAppObserver: createReceiver()
,08-03 19:10:20.754  7022  7022 D BluetoothMapEmailAppObserver: initObservers()
08-03 19:10:20.754  7022  7022 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-03 19:10:20.762  7022  7022 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ebb9853
08-03 19:10:20.763  7022  7022 D HeadsetStateMachine: Proxy object connected
08-03 19:10:20.763  7022  7022 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-03 19:10:20.763  7022  7022 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-03 19:10:20.767  7022  7022 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-03 19:10:20.767  7022  7523 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-03 19:10:20.768  7022  7523 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-03 19:10:20.768  7022  7523 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-03 19:10:20.770  7022  7022 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-03 19:10:20.773  7022  7022 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-03 19:10:20.775  7022  7022 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-03 19:10:20.778  7022  7022 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-03 19:10:20.778  7022  7022 V PanService: [BTUI] SIM Extra State :ABSENT
08-03 19:10:20.781  7022  7022 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-03 19:10:20.781  7022  7022 V BluetoothMapService: Handler(): got msg=1
08-03 19:10:20.782  7022  7484 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-03 19:10:20.782  7022  7484 I bluedroid-qcom: enable
08-03 19:10:20.783  7022  7484 I bt_hci_bdroid: init
08-03 19:10:20.783  7022  7022 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:10:20.785  7022  7484 I bt_vendor: bt-vendor : init
08-03 19:10:20.785  7022  7484 I bt_vendor: bt-vendor : get_bt_soc_type
08-03 19:10:20.785  7022  7484 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-03 19:10:20.785  7022  7484 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-03 19:10:20.785  7022  7484 D bt_userial_mct: userial_init
08-03 19:10:20.785  7022  7554 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-03 19:10:20.785  7022  7484 D bt_hci_bdroid: set_power 1
08-03 19:10:20.785  7022  7484 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-03 19:10:20.785  7022  7484 I bt_vendor: Starting hciattach daemon
08-03 19:10:20.786  7022  7484 I bt_vendor: try to set true
08-03 19:10:20.786  7022  7022 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-03 19:10:20.786  7022  7022 V BluetoothSapReceiver: [BTUI] region:EU country:EU
,08-03 19:10:20.786  7022  7022 V BluetoothSapReceiver: SapReceiver onReceive 
08-03 19:10:20.786  7022  7022 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,08-03 19:10:20.786  7022  7022 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-03 19:10:20.777  7557  7557 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6496 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 19:10:20.777  7557  7557 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6496 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 19:10:20.789  7022  7554 I bt-btu  : btu_task pending for preload complete event
08-03 19:10:20.829  7558  7558 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-03 19:10:20.935  7564  7564 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-03 19:10:20.961  7565  7565 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-03 19:10:21.010  7570  7570 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-03 19:10:21.027  7571  7571 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-03 19:10:21.043  7572  7572 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-03 19:10:21.055  7576  7576 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-03 19:10:21.087  7578  7578 I libmdmdetect: ESOC framework not supported
,08-03 19:10:21.088  7578  7578 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-03 19:10:21.094  7578  7578 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-03 19:10:21.094  7578  7578 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-03 19:10:21.094  7578  7578 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-03 19:10:21.094  7578  7578 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-03 19:10:21.094  7578  7578 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-03 19:10:21.094  7578  7578 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-03 19:10:21.095  7578  7578 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-03 19:10:21.136  7578  7579 E QC-QMI  : qmi_client [7578] 14: failed to locate client data
08-03 19:10:21.138   439   439 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-03 19:10:21.138   439   439 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-03 19:10:21.171  7580  7580 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-03 19:10:21.197  7581  7581 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-03 19:10:21.249  7022  7484 I bt_vendor: bluetooth satus is on
,08-03 19:10:21.249  7022  7484 D bt_hci_bdroid: preload
,08-03 19:10:21.250  7022  7556 D bt_userial_mct: userial_open(port:0)
,08-03 19:10:21.250  7022  7556 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-03 19:10:21.255  7022  7556 I bt_vendor: Done intiailizing UART
,08-03 19:10:21.258  7022  7556 I bt_vendor: Done intiailizing UART
,08-03 19:10:21.258  7022  7556 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-03 19:10:21.259  7022  7556 I bt_vendor: Bluetooth Firmware and transport layer are initialized,
,08-03 19:10:21.260  7022  7554 I bt-btu  : btu_task received preload complete event
,08-03 19:10:21.262  7022  7554 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
,08-03 19:10:21.262  7022  7554 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-03 19:10:21.266  7022  7583 D bt_userial_mct: Entering userial_read_thread()
08-03 19:10:21.269  7022  7554 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-03 19:10:21.277  7022  7554 I         : BTE_InitTraceLevels -- TRC_HCI
08-03 19:10:21.277  7022  7554 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-03 19:10:21.277  7022  7554 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-03 19:10:21.277  7022  7554 I         : BTE_InitTraceLevels -- TRC_AVDT
08-03 19:10:21.277  7022  7554 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-03 19:10:21.277  7022  7554 I         : BTE_InitTraceLevels -- TRC_A2D
08-03 19:10:21.277  7022  7554 I         : BTE_InitTraceLevels -- TRC_BNEP
08-03 19:10:21.277  7022  7554 I         : BTE_InitTraceLevels -- TRC_BTM
08-03 19:10:21.277  7022  7554 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-03 19:10:21.277  7022  7554 I         : BTE_InitTraceLevels -- TRC_GAP
,08-03 19:10:21.277  7022  7554 I         : BTE_InitTraceLevels -- TRC_PAN
,08-03 19:10:21.278  7022  7554 I         : BTE_InitTraceLevels -- TRC_SDP
,08-03 19:10:21.278  7022  7554 I         : BTE_InitTraceLevels -- TRC_GATT
,08-03 19:10:21.278  7022  7554 I         : BTE_InitTraceLevels -- TRC_SMP
,08-03 19:10:21.278  7022  7554 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-03 19:10:21.278  7022  7554 I         : BTE_InitTraceLevels -- TRC_BTIF
08-03 19:10:21.391  7022  7554 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-03 19:10:21.391  7022  7554 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa020c061 
08-03 19:10:21.391  7022  7554 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa020c061 
,08-03 19:10:21.418  7022  7488 E bt-btif : Calling BTA_HhEnable
,08-03 19:10:21.418  7022  7488 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-03 19:10:21.419  7022  7488 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-03 19:10:21.423  7022  7554 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-03 19:10:21.423  7022  7554 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-03 19:10:21.423  7022  7554 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-03 19:10:21.424  7022  7554 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-03 19:10:21.424  7022  7554 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-03 19:10:21.425  1031  1031 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-03 19:10:21.425  1031  1031 D BluetoothManagerService: Stored Bluetooth name: G3
08-03 19:10:21.426  7022  7488 D BluetoothAdapterProperties: Name is: G3
08-03 19:10:21.427  7022  7488 D BluetoothAdapterProperties: Scan Mode:20
08-03 19:10:21.427  7022  7488 D BluetoothAdapterProperties: Discoverable Timeout:120
08-03 19:10:21.427  7022  7488 D bt_hci_bdroid: postload
08-03 19:10:21.427  7022  7556 D bt_hci_bdroid: Used up Tx Cmd credits
08-03 19:10:21.428  7022  7556 D bt_hci_bdroid: Used up Tx Cmd credits
08-03 19:10:21.429  7022  7556 D bt_hci_bdroid: Used up Tx Cmd credits
08-03 19:10:21.429  7022  7556 D bt_hci_bdroid: Used up Tx Cmd credits
08-03 19:10:21.429  7022  7554 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-03 19:10:21.430  7022  7556 D bt_hci_bdroid: Used up Tx Cmd credits
08-03 19:10:21.430  7022  7488 D bte_conf: Device ID record 1 : primary
08-03 19:10:21.430  7022  7488 D bte_conf:   vendorId            = 00c4
08-03 19:10:21.430  7022  7488 D bte_conf:   vendorIdSource      = 0001
08-03 19:10:21.430  7022  7488 D bte_conf:   product             = 13a1
08-03 19:10:21.430  7022  7488 D bte_conf:   version             = 1000
08-03 19:10:21.430  7022  7488 D bte_conf:   clientExecutableURL = 
08-03 19:10:21.430  7022  7488 D bte_conf:   serviceDescription  = 
08-03 19:10:21.430  7022  7488 D bte_conf:   documentationURL    = 
08-03 19:10:21.430  7022  7488 D bte_conf: bte_load_did_conf no section named DID2.
08-03 19:10:21.431  7022  7583 E bt_mct  : hci lib postload completed
08-03 19:10:21.435  7022  7484 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-03 19:10:21.435  7022  7484 D BluetoothAdapterProperties: ScanMode =  20
08-03 19:10:21.435  7022  7484 D BluetoothAdapterProperties: State =  11
08-03 19:10:21.435  7022  7484 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-03 19:10:21.435  7022  7484 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-03 19:10:21.435  7022  7484 D BluetoothAdapterProperties: Setting state to 12
08-03 19:10:21.435  7022  7484 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-03 19:10:21.441  7022  7488 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-03 19:10:21.441  7022  7488 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-03 19:10:21.437  7588  7588 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6496 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 19:10:21.437  7588  7588 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6496 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 19:10:21.451  1031  1095 D BluetoothManagerService: Message: 60
08-03 19:10:21.451  1031  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-03 19:10:21.451  1031  1095 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-03 19:10:21.451  1031  1095 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-03 19:10:21.455  7022  7554 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-03 19:10:21.455  7022  7554 W bt-smp  : Plain text(LSB ~ MSB) = e2 34 7d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-03 19:10:21.455  7022  7554 W bt-smp  : Encrypted text(LSB ~ MSB) = a7 8b 78 df 97 87 8c cd 0d 2e 4e ee 64 a7 ee 1c 
08-03 19:10:21.455  7022  7554 W bt-btm  : Stopping oneshot timer
08-03 19:10:21.458  7022  7484 I BluetoothAdapterState: Entering On State
08-03 19:10:21.482  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:10:21.482  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:10:21.482  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:10:21.482  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 19:10:21.482  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:10:21.482  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:10:21.482  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:10:21.482  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 19:10:21.485  7022  7554 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-03 19:10:21.485  7022  7554 W bt-smp  : Plain text(LSB ~ MSB) = bb 60 7f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-03 19:10:21.485  7022  7554 W bt-smp  : Encrypted text(LSB ~ MSB) = e9 f2 0f cb 0b 7c 01 e7 4e ee 45 e9 ee 60 21 6f 
08-03 19:10:21.485  7022  7554 W bt-btm  : Stopping oneshot timer
08-03 19:10:21.492  7022  7488 D BluetoothAdapterProperties: Discoverable Timeout:120
08-03 19:10:21.492  7022  7488 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-03 19:10:21.493  6643  6643 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 19:10:21.507  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:10:21.507  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:10:21.507  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:10:21.507  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 19:10:21.507  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:10:21.507  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:10:21.507  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:10:21.507  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 19:10:21.510  7022  7554 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-03 19:10:21.510  7022  7554 W bt-smp  : Plain text(LSB ~ MSB) = b3 18 6a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-03 19:10:21.511  7022  7554 W bt-smp  : Encrypted text(LSB ~ MSB) = 51 ea f7 fe b3 e5 5f c2 85 6b df 96 4b 11 46 ed 
08-03 19:10:21.511  7022  7554 W bt-btm  : Stopping oneshot timer
08-03 19:10:21.515  6643  6643 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 19:10:21.527  7022  7484 D LGBluetoothServiceAdapter: [BTUI] OnState
08-03 19:10:21.527  7022  7484 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-03 19:10:21.527  7022  7484 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-03 19:10:21.531  7022  7484 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-03 19:10:21.531  7022  7484 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-03 19:10:21.531  1031  1031 D BluetoothA2dp: Proxy object connected
08-03 19:10:21.546  7022  7554 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-03 19:10:21.546  7022  7554 W bt-smp  : Plain text(LSB ~ MSB) = c4 4c 6d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-03 19:10:21.546  7022  7554 W bt-smp  : Encrypted text(LSB ~ MSB) = 9d 19 7c d7 d9 87 e5 df 13 ca 76 ec b1 2a 6b 2e 
08-03 19:10:21.546  7022  7554 W bt-btm  : Stopping oneshot timer
,08-03 19:10:21.552  6897  6913 D BluetoothMap: onBluetoothStateChange: up=true
08-03 19:10:21.561  7601  7601 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-03 19:10:21.563  6897  6914 D BluetoothPan: onBluetoothStateChange on: true
08-03 19:10:21.563  6897  6914 D BluetoothPan: onBluetoothStateChange call bindService
,08-03 19:10:21.565  6897  6897 D BluetoothMap: Proxy object connected
08-03 19:10:21.565  6897  6897 D MapProfile: Bluetooth service connected
08-03 19:10:21.565  6897  6897 D BluetoothMap: getConnectedDevices()
08-03 19:10:21.566  7022  7554 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-03 19:10:21.566  7022  7554 W bt-smp  : Plain text(LSB ~ MSB) = d2 a6 7b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-03 19:10:21.566  7022  7554 W bt-smp  : Encrypted text(LSB ~ MSB) = 43 89 a3 78 88 c1 e1 84 f3 d6 79 a7 d0 9f 25 3b 
08-03 19:10:21.566  7022  7554 W bt-btm  : Stopping oneshot timer
08-03 19:10:21.569  1850  3970 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 19:10:21.571  7022  7037 V BluetoothMapService: getConnectedDevices()
08-03 19:10:21.573  1031  1095 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 19:10:21.573  1850  1850 D BluetoothHeadset: Proxy object connected
08-03 19:10:21.573  6897  6897 D BluetoothPan: BluetoothPAN Proxy object connected
08-03 19:10:21.573  6897  6897 D PanProfile: Bluetooth service connected
08-03 19:10:21.574  1031  1031 D BluetoothHeadset: Proxy object connected
08-03 19:10:21.574  6897  7604 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-03 19:10:21.581  6897  6913 D BluetoothPbap: onBluetoothStateChange: up=true
08-03 19:10:21.585  1850  2674 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 19:10:21.588  1850  1850 D BluetoothHeadset: Proxy object connected
08-03 19:10:21.588  1850  1866 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 19:10:21.590  1850  1850 D BluetoothHeadset: Proxy object connected
08-03 19:10:21.592  6897  6897 D BluetoothInputDevice: Proxy object connected
08-03 19:10:21.592  6897  6897 D HidProfile: Bluetooth service connected
,08-03 19:10:21.594  1031  1095 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-03 19:10:21.594  1031  1095 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-03 19:10:21.595  1939  1939 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:10:21.596  1031  1031 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-03 19:10:21.596  1939  2132 D LGBluetoothAPIService: Message: 1
08-03 19:10:21.596  1939  2132 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-03 19:10:21.601  7022  7022 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:10:21.601  7022  7022 D BluetoothMapService: STATE_ON
08-03 19:10:21.601  7022  7022 V BluetoothMapService: Handler(): got msg=1
08-03 19:10:21.602  7022  7022 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-03 19:10:21.603  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-03 19:10:21.603  6643  6643 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
,08-03 19:10:21.607  7022  7611 D BluetoothMapMasInstance: MAS initSocket()
08-03 19:10:21.607  7022  7611 D BluetoothMapMasInstance:   masId = 00
08-03 19:10:21.607  7022  7611 D BluetoothMapMasInstance:   msgTypes = 0e
08-03 19:10:21.607  7022  7611 D BluetoothMapMasInstance:   masName = SMS/MMS
08-03 19:10:21.607  7022  7611 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-03 19:10:21.612  1031  1574 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:10:21.613  1939  2132 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-03 19:10:21.615  7022  7611 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 19:10:21.615  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:10:21.616  7022  7611 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-03 19:10:21.617  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:10:21.617  1031  1095 D BluetoothManagerService: Message: 40
08-03 19:10:21.617  1031  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-03 19:10:21.619  6897  6897 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-03 19:10:21.622  7022  7022 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ebb9853
08-03 19:10:21.622  7022  7022 V BluetoothPbapService: Pbap Service onCreate
08-03 19:10:21.622  7022  7022 V BluetoothPbapService: Starting PBAP service
08-03 19:10:21.623  7022  7611 V BluetoothMapMasInstance: Succeed to create listening socket 
08-03 19:10:21.623  7022  7611 D BluetoothMapMasInstance: Accepting socket connection...
08-03 19:10:21.624  7022  7022 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-03 19:10:21.624  7022  7022 V BluetoothPbapService: Pbap Service onBind
08-03 19:10:21.625  7022  7488 D BluetoothAdapterProperties: Scan Mode:21
08-03 19:10:21.625  7022  7488 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-03 19:10:21.625  1031  1095 D BluetoothManagerService: Message: 30
08-03 19:10:21.626  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:10:21.627  7022  7022 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:10:21.627  7022  7022 V BluetoothPbapService: state: 12
08-03 19:10:21.629  7022  7022 D LGBluetoothAPIServer: [BTUI] onCreate()
08-03 19:10:21.629  7022  7022 D LGBluetoothAPIServer: [BTUI] onBind()
08-03 19:10:21.635  7022  7022 V BluetoothPbapService: Handler(): got msg=1
,08-03 19:10:21.635  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:10:21.636  7022  7022 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-03 19:10:21.637  1939  1939 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-03 19:10:21.637  1939  2132 D LGBluetoothAPIService: Message: 100
08-03 19:10:21.637  1939  2132 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-03 19:10:21.639  7022  7613 V BluetoothPbapService: Pbap Service initSocket
08-03 19:10:21.639  1031  2040 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:10:21.640  6897  6897 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-03 19:10:21.641  7022  7613 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 19:10:21.642  1031  1095 D BluetoothManagerService: Message: 30
08-03 19:10:21.643  7022  7613 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-03 19:10:21.643  7022  7613 V BluetoothPbapService: Succeed to create listening socket 
08-03 19:10:21.643  7022  7613 V BluetoothPbapService: Accepting socket connection...
08-03 19:10:21.647  6897  6897 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-03 19:10:21.647  7259  7289 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-03 19:10:21.648  6897  6897 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-03 19:10:21.651  6897  6897 D BluetoothPbap: Proxy object connected
08-03 19:10:21.651  6897  6897 D PbapServerProfile: Bluetooth service connected
08-03 19:10:21.651  6897  6897 D BluetoothA2dp: Proxy object connected
08-03 19:10:21.652  7022  7022 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-03 19:10:21.652  6897  6897 D A2dpProfile: Bluetooth service connected
08-03 19:10:21.652  7022  7022 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:10:21.652  7022  7022 V BluetoothPbapReceiver: ***********state = 12
08-03 19:10:21.655  2195  2195 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-03 19:10:21.656  2195  2195 D c       : Getting all permits...
08-03 19:10:21.656  2195  2195 D a       : Opening database...
08-03 19:10:21.656  6897  6897 D BluetoothHeadset: Proxy object connected
08-03 19:10:21.657  6897  6897 D HeadsetProfile: Bluetooth service connected
08-03 19:10:21.659  2195  2195 D a       : Opening database auth.proximity.permit_store...
08-03 19:10:21.661  2195  2195 D a       : Closing database...
,08-03 19:10:21.667  6897  6897 D DockEventReceiver: finishStartingService: stopping service
08-03 19:10:21.672  6897  6897 D BluetoothPermissionRequest: onReceive
,08-03 19:10:21.673  6897  6897 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-03 19:10:21.675  6897  6897 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-03 19:10:21.678  7022  7022 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-03 19:10:21.679  7022  7022 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-03 19:10:21.685  7022  7022 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-03 19:10:21.703  7022  7022 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-03 19:10:21.703  7022  7022 V BtOppService: onCreate
08-03 19:10:21.707  7022  7022 V BluetoothOppNotification: send message
08-03 19:10:21.710  7022  7022 V BtOppService: Starting RfcommListener
08-03 19:10:21.713  7022  7022 D BluetoothOppPreference: Dumping Names:  
08-03 19:10:21.713  7022  7022 D BluetoothOppPreference: {}
08-03 19:10:21.713  7022  7022 D BluetoothOppPreference: Dumping Channels:  
08-03 19:10:21.713  7022  7022 D BluetoothOppPreference: {}
08-03 19:10:21.714  7022  7022 V BtOppService: onStartCommand
08-03 19:10:21.715  7022  7022 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:10:21.716  7022  7022 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-03 19:10:21.717  7022  7022 V BluetoothOppNotification: new notify threadi!
08-03 19:10:21.718  7022  7022 V BluetoothOppNotification: send delay message
08-03 19:10:21.719  7022  7022 V BtOppService: start RfcommListener
08-03 19:10:21.722  7022  7623 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-03 19:10:21.723  7022  7022 V BtOppService: RfcommListener started
08-03 19:10:21.724  7022  7625 V BtOppRfcommListener: Starting RFCOMM listener....
08-03 19:10:21.726  7022  7624 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-03 19:10:21.727  1031  1884 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-03 19:10:21.728  7022  7625 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 19:10:21.728  7022  7624 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@7e12f4c on behalf of 
08-03 19:10:21.729  7022  7620 V BtOppService: Deleted complete outbound shares, number =  0
08-03 19:10:21.730  7022  7625 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-03 19:10:21.730  7022  7623 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-03 19:10:21.730  7022  7625 V BtOppRfcommListener: Started RFCOMM listener....
08-03 19:10:21.730  7022  7625 I BtOppRfcommListener: Accept thread started.
08-03 19:10:21.731  7022  7625 V BtOppRfcommListener: Accepting connection...
08-03 19:10:21.731  7022  7620 V BtOppService: Deleted complete inbound failed shares, number = 0
08-03 19:10:21.731  7022  7624 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-03 19:10:21.731  7022  7620 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-03 19:10:21.732  7022  7624 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-03 19:10:21.735  7022  7623 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@18127b95 on behalf of 
08-03 19:10:21.735  7022  7620 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@bc434aa on behalf of 
08-03 19:10:21.736  7022  7624 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3012689b on behalf of 
08-03 19:10:21.736  7022  7623 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-03 19:10:21.737  7022  7624 V BluetoothOppNotification: outbound: succ-0  fail-0
08-03 19:10:21.739  7022  7624 V BluetoothOppNotification: outbound notification was removed.
,08-03 19:10:21.739  7022  7624 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-03 19:10:21.740  7022  7624 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1697f438 on behalf of 
08-03 19:10:21.741  7022  7624 V BluetoothOppNotification: inbound: succ-0  fail-0
08-03 19:10:21.742  7022  7022 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ebb9853
08-03 19:10:21.742  7022  7022 V BluetoothFtpService: Ftp Service onCreate
08-03 19:10:21.742  7022  7022 I BluetoothFtpService: Ftp Service onCreate
08-03 19:10:21.742  7022  7022 V BluetoothFtpService: Ftp Service onStartCommand
08-03 19:10:21.742  7022  7624 V BluetoothOppNotification: inbound notification was removed.
08-03 19:10:21.743  7022  7624 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-03 19:10:21.743  7022  7022 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:10:21.743  7022  7022 V BluetoothFtpService: Starting Listening on sockets
08-03 19:10:21.743  7022  7022 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-03 19:10:21.743  7022  7022 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-03 19:10:21.743  7022  7022 V BluetoothSapReceiver: SapReceiver onReceive 
08-03 19:10:21.743  7022  7022 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:10:21.743  7022  7022 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-03 19:10:21.743  7022  7022 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-03 19:10:21.745  7022  7624 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3c88f176 on behalf of 
08-03 19:10:21.745  7022  7022 V BtOppService: ContentObserver received notification
08-03 19:10:21.745  7022  7022 V BtOppService: ContentObserver received notification
08-03 19:10:21.746  7022  7022 V BluetoothFtpService: Handler(): got msg=1
08-03 19:10:21.746  7022  7626 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-03 19:10:21.746  7022  7022 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-03 19:10:21.746  7022  7626 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-03 19:10:21.747  7022  7022 V BluetoothFtpService: Ftp Service initSocket
08-03 19:10:21.750  7022  7626 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3724f377 on behalf of 
08-03 19:10:21.750  7022  7626 V BluetoothOppNotification: update too frequent, put in queue
08-03 19:10:21.751  1031  1918 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:10:21.751  7022  7626 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,08-03 19:10:21.753  7022  7022 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 19:10:21.754  7022  7022 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
08-03 19:10:21.755  7022  7022 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-03 19:10:21.759  7022  7627 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-03 19:10:21.768  7022  7022 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ebb9853
,08-03 19:10:21.768  7022  7022 V BluetoothSapService: Sap Service onCreate
08-03 19:10:21.770  7022  7022 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:10:21.770  7022  7022 V BluetoothSapService: state: 12
08-03 19:10:21.770  7022  7022 V BluetoothSapService: Starting SAP server process
08-03 19:10:21.767  7628  7628 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6496 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 19:10:21.772  7022  7022 V BluetoothSapService: SAP Service startRfcommListenerThread
08-03 19:10:21.767  7628  7628 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6496 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 19:10:21.774  7022  7629 V BluetoothSapService: Sap Service initRfcommSocket
08-03 19:10:21.774  1031  1938 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:10:21.775  7022  7629 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 19:10:21.777  7022  7629 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-03 19:10:21.777  7022  7629 V BluetoothSapService: Succeed to create listening socket 
08-03 19:10:21.777  7022  7629 V BluetoothSapService: Accepting socket connection...
08-03 19:10:21.783  7628  7628 V BT_SAP  : Event pipe created
08-03 19:10:21.783  7628  7628 V BT_SAP  : create_server_socket qcom.sap.server
08-03 19:10:21.783  7628  7628 V BT_SAP  : created socket fd 6
,08-03 19:10:22.203  1031  1536 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-03 19:10:22.203  1031  1536 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-03 19:10:22.235  1031  1537 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-03 19:10:22.237  1031  1537 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-03 19:10:22.339  1031  1902 I ActivityManager: Killing 7411:com.lge.bnr/1000 (adj 15): empty #17
,08-03 19:10:22.372  1031  1941 W libprocessgroup: failed to open /acct/uid_1000/pid_7411/cgroup.procs: No such file or directory
,08-03 19:10:22.461  1031  1574 I ActivityManager: Killing 6744:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-03 19:10:22.491  6952  6952 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,08-03 19:10:22.492  6952  6952 W System.err: android.os.DeadObjectException
08-03 19:10:22.492  6952  6952 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-03 19:10:22.492  6952  6952 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
,08-03 19:10:22.492  6952  6952 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
,08-03 19:10:22.492  6952  6952 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-03 19:10:22.492  6952  6952 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-03 19:10:22.492  6952  6952 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-03 19:10:22.492  6952  6952 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-03 19:10:22.493  6952  6952 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-03 19:10:22.493  6952  6952 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-03 19:10:22.493  6952  6952 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-03 19:10:22.493  6952  6952 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 19:10:22.493  6952  6952 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-03 19:10:22.493  6952  6952 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-03 19:10:22.493  6952  6952 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-03 19:10:22.493  6952  6952 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-03 19:10:22.493  6952  6952 W System.err: android.os.DeadObjectException
08-03 19:10:22.493  6952  6952 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-03 19:10:22.494  6952  6952 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-03 19:10:22.494  6952  6952 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-03 19:10:22.494  6952  6952 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-03 19:10:22.494  6952  6952 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-03 19:10:22.494  6952  6952 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-03 19:10:22.494  6952  6952 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-03 19:10:22.494  6952  6952 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-03 19:10:22.494  6952  6952 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-03 19:10:22.494  6952  6952 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-03 19:10:22.494  6952  6952 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 19:10:22.494  6952  6952 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-03 19:10:22.494  6952  6952 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-03 19:10:22.494  6952  6952 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-03 19:10:22.494  6952  6952 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-03 19:10:22.495  6952  6952 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-03 19:10:22.531  1031  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_6744/cgroup.procs: No such file or directory
08-03 19:10:22.531  1031  1046 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-03 19:10:22.538  6952  6952 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-03 19:10:22.539  6952  6952 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-03 19:10:22.589  1031  1975 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7639 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-03 19:10:22.621  6952  6952 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-03 19:10:22.664  7639  7639 D UEI.SmartControl: Quickset Services start...
08-03 19:10:22.666  7639  7639 I UEI.SmartControl: Manufacture = LGE
08-03 19:10:22.666  7639  7639 D UEI.SmartControl: Id = LGNevo
08-03 19:10:22.667  7639  7639 D UEI.SmartControl: File observer start...
08-03 19:10:22.668  7639  7639 E UEI.SmartControl: IR Port is disabled: false
08-03 19:10:22.668  7639  7639 D UEI.SmartControl: Starting file observer...
08-03 19:10:22.668  7639  7639 D UEI.SmartControl: Extracting JNI libs...
,08-03 19:10:22.703  7639  7639 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,08-03 19:10:22.720  7022  7022 V BluetoothOppNotification: new notify threadi!
08-03 19:10:22.721  7022  7022 V BluetoothOppNotification: send delay message
08-03 19:10:22.725  7022  7666 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-03 19:10:22.811  7639  7639 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-03 19:10:22.811  7639  7639 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-03 19:10:22.811  7639  7639 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-03 19:10:22.851  7639  7639 I UEI.SmartControl: --- Selecting new region: 6
,08-03 19:10:22.853  7639  7639 I UEI.SmartControl: Model = LG-D855
,08-03 19:10:22.854  7639  7639 D UEI.SmartControl: QS Service created
,08-03 19:10:22.871  7639  7639 I UEI.SmartControl: Service initServices...
,08-03 19:10:22.876  7639  7639 D UEI.SmartControl: QS start get config
,08-03 19:10:22.889  1031  1046 I art     : Explicit concurrent mark sweep GC freed 93160(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 2.324ms total 159.631ms
,08-03 19:10:22.889  7022  7666 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2b6b5013 on behalf of 
,08-03 19:10:22.895  7022  7666 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-03 19:10:22.899  7022  7666 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-03 19:10:22.902  7022  7666 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@30c91250 on behalf of 
08-03 19:10:22.903  7022  7666 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-03 19:10:22.907  7022  7666 V BluetoothOppNotification: outbound notification was removed.
08-03 19:10:22.907  7022  7666 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-03 19:10:22.910  7022  7666 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3115c49 on behalf of 
08-03 19:10:22.911  7022  7666 V BluetoothOppNotification: inbound: succ-0  fail-0
08-03 19:10:22.912  7022  7666 V BluetoothOppNotification: inbound notification was removed.
08-03 19:10:22.913  7022  7666 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-03 19:10:22.913  7022  7666 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1f8b94e on behalf of 
08-03 19:10:22.932  7639  7639 D UEI.SmartControl: Loading JNI Libs...
,08-03 19:10:23.183  7639  7639 I UEI.SmartControl: Supports setup maps: true
,08-03 19:10:23.186  7639  7639 D UEI.SmartControl: QS start statue = true Error code = 0
,08-03 19:10:23.187  7639  7639 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,08-03 19:10:23.187  7639  7639 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
,08-03 19:10:23.187  7639  7639 I UEI.SmartControl: ### init IR Blaster...
,08-03 19:10:23.192  7639  7639 D serial_port: Configuring serial port
,08-03 19:10:23.195  7639  7639 E UEI.SmartControl: UEIBLaster setting for 616
,08-03 19:10:23.196  7639  7639 I UEI.SmartControl: Setting serial record hearder size = 2
08-03 19:10:23.196  7639  7639 I UEI.SmartControl: configuring settings for MAXQ616
,08-03 19:10:23.196  7639  7639 I UEI.SmartControl: Get version...
08-03 19:10:23.212  7639  7673 D UEI.SmartControl: serial port data available: 21
,08-03 19:10:23.223  1031  1574 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:10:23.223  1031  1574 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@13041171 mBinding = false
08-03 19:10:23.239  7639  7639 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-03 19:10:23.239  7639  7639 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-03 19:10:23.239  7639  7639 I UEI.SmartControl: QS saving settings...
08-03 19:10:23.240  7639  7639 D UEI.SmartControl: IR Blaster version: 25672567
,08-03 19:10:23.251  1031  1095 D BluetoothManagerService: Message: 2
08-03 19:10:23.252  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-03 19:10:23.252  1031  1095 D BluetoothManagerService: Sending off request.
08-03 19:10:23.252  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-03 19:10:23.252  1031  1031 D Ulp_jni : JNI:system_update. Event-4
08-03 19:10:23.252  7022  7037 D LGBluetoothServiceAdapter: [BTUI] Precleanup
,08-03 19:10:23.253  7022  7484 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-03 19:10:23.254  7022  7484 D BluetoothAdapterProperties: Setting state to 13
08-03 19:10:23.254  7022  7484 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-03 19:10:23.255  7022  7484 D BluetoothAdapterProperties: onBluetoothDisable()
08-03 19:10:23.256  7022  7484 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-03 19:10:23.257  7022  7488 D BluetoothAdapterProperties: Scan Mode:20
08-03 19:10:23.257  7022  7484 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-03 19:10:23.259  7022  7611 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-03 19:10:23.259  7022  7611 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 19:10:23.259  7022  7611 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-03 19:10:23.259  7022  7611 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-03 19:10:23.259  7022  7611 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-03 19:10:23.259  7022  7611 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-03 19:10:23.259  7022  7611 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-03 19:10:23.259  7022  7611 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-03 19:10:23.260  7022  7484 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-03 19:10:23.261  7022  7629 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 19:10:23.261  7022  7627 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 19:10:23.262  7022  7625 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 19:10:23.262  7022  7613 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 19:10:23.262  7022  7554 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-03 19:10:23.262  7022  7554 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-03 19:10:23.263  7022  7554 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-03 19:10:23.263  7022  7554 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-03 19:10:23.263  7022  7554 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-03 19:10:23.263  7022  7554 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-03 19:10:23.264  7022  7554 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 19:10:23.264  7022  7554 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-03 19:10:23.264  7022  7554 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-03 19:10:23.264  7022  7554 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-03 19:10:23.264  7022  7554 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-03 19:10:23.264  7022  7554 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
,08-03 19:10:23.264  7022  7554 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-03 19:10:23.264  7022  7554 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-03 19:10:23.269  7639  7673 D UEI.SmartControl: serial port data available: 4
08-03 19:10:23.270  1031  1095 D BluetoothManagerService: Message: 60
08-03 19:10:23.270  1031  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-03 19:10:23.270  1031  1095 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-03 19:10:23.273  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-03 19:10:23.274  7022  7022 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:10:23.274  7022  7022 D BluetoothMapService: STATE_TURNING_OFF
08-03 19:10:23.274  7022  7022 V BluetoothMapService: Handler(): got msg=4
08-03 19:10:23.274  7022  7022 D BluetoothMapService: MAP Service closeService in
08-03 19:10:23.274  7022  7022 D BluetoothMapMasInstance: MAP Service shutdown
08-03 19:10:23.275  7022  7022 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-03 19:10:23.275  7022  7022 V BluetoothMapService: MAP Service closeService out
08-03 19:10:23.275  6643  6643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:10:23.275  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:10:23.275  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:10:23.275  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:10:23.275  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 19:10:23.275  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 19:10:23.275  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:10:23.275  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:10:23.275  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 19:10:23.275  7022  7022 V BtOppService: Receiver DISABLED_ACTION 
08-03 19:10:23.275  7022  7022 I BtOppRfcommListener: stopping Accept Thread
08-03 19:10:23.275  7022  7022 V BtOppRfcommListener: close mBtServerSocket
08-03 19:10:23.276  7022  7022 V BtOppRfcommListener: waiting for thread to terminate
08-03 19:10:23.276  7022  7625 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-03 19:10:23.276  1939  1939 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:10:23.276  6643  6643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:10:23.276  6643  6643 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 19:10:23.276  7022  7022 V BtOppRfcommListener: done waiting for thread to terminate
08-03 19:10:23.278  7022  7022 V BtOppService: onDestroy
08-03 19:10:23.278  6897  6897 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
,08-03 19:10:23.282  6897  6897 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-03 19:10:23.284  6643  6643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:10:23.284  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:10:23.284  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:10:23.284  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:10:23.284  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 19:10:23.284  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 19:10:23.284  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:10:23.284  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:10:23.284  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 19:10:23.285  6643  6643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:10:23.285  6643  6643 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 19:10:23.286  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:10:23.287  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:10:23.289  7022  7022 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-03 19:10:23.293  7022  7022 V BluetoothPbapReceiver: PbapReceiver onReceive 
,08-03 19:10:23.294  7022  7022 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:10:23.294  7022  7022 V BluetoothPbapReceiver: ***********state = 13
08-03 19:10:23.296  6897  6897 D DockEventReceiver: finishStartingService: stopping service
08-03 19:10:23.297  7022  7022 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-03 19:10:23.299  2195  2195 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-03 19:10:23.299  7022  7022 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:10:23.299  7022  7022 V BluetoothPbapService: state: 13
08-03 19:10:23.299  7022  7022 V BluetoothPbapService: Pbap Service closeService in
08-03 19:10:23.303  7639  7639 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-03 19:10:23.304  7639  7678 I UEI.SmartControl: Device manager: loading config....
08-03 19:10:23.305  7639  7678 D UEI.SmartControl: ----------- loading internal config...
08-03 19:10:23.305  6897  6897 D BluetoothPbap: Proxy object disconnected
08-03 19:10:23.305  6897  6897 D PbapServerProfile: Bluetooth service disconnected
08-03 19:10:23.305  7022  7022 V BluetoothPbapService: successfully stopped pbap service
,08-03 19:10:23.306  7022  7022 V BluetoothPbapService: Pbap Service closeService out
,08-03 19:10:23.306  7022  7022 V BluetoothPbapService: Pbap Service onDestroy
08-03 19:10:23.306  7022  7022 V BluetoothPbapService: Pbap Service closeService in
08-03 19:10:23.306  7022  7022 V BluetoothPbapService: Pbap Service closeService out
08-03 19:10:23.306  7022  7022 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-03 19:10:23.315  7639  7678 E UEI.SmartControl: Loading SETTINGS...
08-03 19:10:23.315  7639  7639 E UEI.SmartControl: Services init done
08-03 19:10:23.315  7639  7639 D UEI.SmartControl: QS Service init finished
08-03 19:10:23.316  7639  7639 D UEI.SmartControl: QS Service version name: 2.1.91
08-03 19:10:23.317  7639  7639 D UEI.SmartControl: QS Service version code: 201091
08-03 19:10:23.317  7639  7639 D UEI.SmartControl: Service requested: Control
08-03 19:10:23.320  6897  6897 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-03 19:10:23.326  6952  6952 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-03 19:10:23.331  7639  7655 I UEI.SmartControl: ------ IControl API: 11
08-03 19:10:23.331  6897  6897 D BluetoothPermissionRequest: onReceive
08-03 19:10:23.332  6897  6897 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-03 19:10:23.336  7639  7639 D UEI.SmartControl: Internal service binding...
08-03 19:10:23.336  7639  7655 I UEI.SmartControl: Registering callback...
08-03 19:10:23.337  7639  7654 I UEI.SmartControl: ------ IControl API: 19
08-03 19:10:23.338  7639  7654 I UEI.SmartControl: Registering Services Ready callback...
08-03 19:10:23.344  6897  6897 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-03 19:10:23.346  1031  1943 I ActivityManager: Killing 6952:com.lge.qremote/u0a112 (adj 15): empty #17
,08-03 19:10:23.404  7022  7022 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-03 19:10:23.404  1031  1046 W libprocessgroup: failed to open /acct/uid_10112/pid_6952/cgroup.procs: No such file or directory
,08-03 19:10:23.404  7022  7022 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-03 19:10:23.405  7022  7022 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-03 19:10:23.412  7022  7022 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:10:23.412  7022  7022 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-03 19:10:23.415  7022  7022 V BluetoothFtpService: Ftp Service onStartCommand
08-03 19:10:23.415  7022  7022 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:10:23.415  7022  7022 V BluetoothFtpService: Ftp Service closeService
08-03 19:10:23.415  7022  7022 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-03 19:10:23.420  7022  7022 V BluetoothFtpService: successfully stopped ftp service
08-03 19:10:23.420  7022  7022 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-03 19:10:23.420  7022  7022 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-03 19:10:23.420  7022  7022 V BluetoothSapReceiver: SapReceiver onReceive 
08-03 19:10:23.421  7022  7022 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:10:23.421  7022  7022 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-03 19:10:23.421  7022  7022 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-03 19:10:23.423  7639  7678 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-03 19:10:23.428  7022  7022 V BluetoothFtpService: Ftp Service onDestroy
08-03 19:10:23.428  7022  7022 V BluetoothFtpService: Ftp Service closeService
08-03 19:10:23.431  7639  7677 I UEI.SmartControl: Notify AllClients services are ready: 0
08-03 19:10:23.431  7639  7677 D UEI.SmartControl: -----service ready thread exits
08-03 19:10:23.432  7022  7022 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:10:23.432  7022  7022 V BluetoothSapService: state: 13
08-03 19:10:23.432  7022  7022 V BluetoothSapService: Stopping SAP server process
08-03 19:10:23.433  7022  7022 V BluetoothSapService: Sap Service closeSapService in
08-03 19:10:23.433  7022  7022 V BluetoothSapService: Close listen Socket : 
08-03 19:10:23.434  7022  7022 V BluetoothSapService: Close rfcomm Socket : 
08-03 19:10:23.434  7022  7022 V BluetoothSapService: Close sapd  Socket : 
08-03 19:10:23.439  7022  7022 V BluetoothSapService: Sap Service closeSapService out
08-03 19:10:23.440  7022  7022 V BluetoothSapService: Sap Service onDestroy
08-03 19:10:23.440  7022  7022 V BluetoothSapService: Sap Service closeSapService in
08-03 19:10:23.440  7022  7022 V BluetoothSapService: Close listen Socket : 
08-03 19:10:23.440  7022  7022 V BluetoothSapService: Close rfcomm Socket : 
08-03 19:10:23.440  7022  7022 V BluetoothSapService: Close sapd  Socket : 
,08-03 19:10:23.441  7022  7022 V BluetoothSapService: Sap Service closeSapService out
,08-03 19:10:24.168  7022  7488 D bt_hci_bdroid: cleanup
,08-03 19:10:24.177  7022  7556 I bt_lpm  : LPM is already off!!!
08-03 19:10:24.178  7022  7583 I bt_userial_mct: exiting userial_read_thread
08-03 19:10:24.179  7022  7583 D bt_userial_mct: Leaving userial_evt_read_thread()
08-03 19:10:24.180  7022  7554 W bt-btif : ag scb idx 1 not allocated
08-03 19:10:24.180  7022  7554 E bt-btif : BTA AG is already disabled, ignoring ...
08-03 19:10:24.180  7022  7554 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-03 19:10:24.180  7022  7554 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 19:10:24.180  7022  7554 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-03 19:10:24.180  7022  7554 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-03 19:10:24.181  7022  7554 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-03 19:10:24.181  7022  7554 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-03 19:10:24.181  7022  7554 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-03 19:10:24.181  7022  7554 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 19:10:24.181  7022  7554 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-03 19:10:24.181  7022  7554 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-03 19:10:24.181  7022  7554 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-03 19:10:24.181  7022  7554 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-03 19:10:24.181  7022  7554 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-03 19:10:24.181  7022  7554 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 19:10:24.181  7022  7554 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-03 19:10:24.181  7022  7554 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-03 19:10:24.181  7022  7554 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-03 19:10:24.181  7022  7554 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-03 19:10:24.182  7022  7554 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-03 19:10:24.188  7022  7488 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-03 19:10:24.188  7022  7556 I bt_vendor: hw_epilog_process
08-03 19:10:24.191  7022  7488 D bt_hci_bdroid: cleanup Finalizing cleanup
08-03 19:10:24.191  7022  7488 D bt_userial_mct: userial_close
08-03 19:10:24.191  7022  7488 E bt_userial_mct: pthread_join() FAILED result:3
08-03 19:10:24.191  7022  7488 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-03 19:10:24.201  7022  7488 D bt_hci_bdroid: set_power 0
08-03 19:10:24.201  7022  7488 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-03 19:10:24.201  7022  7488 I bt_vendor: bluetooth satus is on
08-03 19:10:24.201  7022  7488 I bt_vendor: bt-vendor : resetting BT status
08-03 19:10:24.201  7022  7488 I bt_vendor: Starting hciattach daemon
08-03 19:10:24.201  7022  7488 I bt_vendor: try to set false
08-03 19:10:24.203  7022  7488 I bt_vendor: Starting hciattach daemon
08-03 19:10:24.203  7022  7488 I bt_vendor: try to set false
08-03 19:10:24.205  7022  7488 I bt_vendor: cleanup
,08-03 19:10:24.209  7022  7554 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-03 19:10:24.209  7022  7488 I GKI_LINUX: GKI_exit_task 0 done
08-03 19:10:24.209  7022  7488 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-03 19:10:24.211  7022  7484 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-03 19:10:24.215  7022  7022 D HeadsetService: Received stop request...Stopping profile...
08-03 19:10:24.216  7022  7022 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-03 19:10:24.216  7022  7022 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-03 19:10:24.216  7022  7022 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ebb9853
08-03 19:10:24.217  7022  7523 D HeadsetStateMachine: Exit Disconnected: -1
,08-03 19:10:24.226  7022  7484 D BluetoothAdapterState: Stopping profile services that were post enabled
08-03 19:10:24.228  1031  1031 D BluetoothHeadset: Proxy object disconnected
08-03 19:10:24.228  1031  1031 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-03 19:10:24.228  1850  1850 D BluetoothHeadset: Proxy object disconnected
08-03 19:10:24.229  1850  1850 D BluetoothHeadset: Proxy object disconnected
08-03 19:10:24.229  1850  1850 D BluetoothHeadset: Proxy object disconnected
08-03 19:10:24.230  7022  7022 D A2dpService: Received stop request...Stopping profile...
,08-03 19:10:24.232  7022  7546 D A2dpStateMachine: Exit Disconnected: -1
08-03 19:10:24.234  7022  7022 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-03 19:10:24.235  7022  7022 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-03 19:10:24.235  7022  7022 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-03 19:10:24.235  7022  7022 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ebb9853
08-03 19:10:24.238  1031  1031 D BluetoothA2dp: Proxy object disconnected
08-03 19:10:24.238  1031  1031 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-03 19:10:24.240  7022  7022 D HidService: Received stop request...Stopping profile...
08-03 19:10:24.240  7022  7022 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ebb9853
08-03 19:10:24.243  7022  7022 D HeadsetStateMachine: Unbinding service...
,08-03 19:10:24.246  7022  7022 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-03 19:10:24.246  7022  7022 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-03 19:10:24.246  7022  7022 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-03 19:10:24.246  7022  7022 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-03 19:10:24.246  7022  7022 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-03 19:10:24.246  7022  7022 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-03 19:10:24.246  7022  7022 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-03 19:10:24.248  7022  7022 D HealthService: Received stop request...Stopping profile...
08-03 19:10:24.248  7022  7022 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ebb9853
08-03 19:10:24.250  7022  7022 D PanService: Received stop request...Stopping profile...
08-03 19:10:24.251  7022  7022 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ebb9853
08-03 19:10:24.253  7022  7022 D BtGatt.DebugUtils: handleDebugAction() action=null
08-03 19:10:24.253  7022  7022 D BtGatt.GattService: Received stop request...Stopping profile...
08-03 19:10:24.253  7022  7022 D BtGatt.GattService: stop()
08-03 19:10:24.253  7022  7022 D BtGatt.AdvertiseManager: advertise clients cleared
08-03 19:10:24.255  7022  7022 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ebb9853
,08-03 19:10:24.258  7022  7022 D BluetoothMapService: Received stop request...Stopping profile...
08-03 19:10:24.258  7022  7022 D BluetoothMapService: stop()
08-03 19:10:24.259  7022  7022 D BluetoothMapEmailAppObserver: deinitObservers()
08-03 19:10:24.259  7022  7022 D BluetoothMapEmailAppObserver: removeReceiver()
08-03 19:10:24.260  7022  7022 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ebb9853
08-03 19:10:24.262  7022  7022 V BluetoothMapService: Handler(): got msg=4
08-03 19:10:24.262  7022  7022 D BluetoothMapService: MAP Service closeService in
08-03 19:10:24.262  7022  7022 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-03 19:10:24.262  7022  7022 V BluetoothMapService: MAP Service closeService out
08-03 19:10:24.264  7022  7484 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-03 19:10:24.264  7022  7484 D BluetoothAdapterProperties: Setting state to 10
08-03 19:10:24.264  7022  7484 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-03 19:10:24.266  1031  1095 D BluetoothManagerService: Message: 60
08-03 19:10:24.266  1031  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-03 19:10:24.266  1031  1095 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-03 19:10:24.267  1031  1095 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-03 19:10:24.270  7022  7484 I BluetoothAdapterState: Entering OffState
08-03 19:10:24.272  6897  6914 D BluetoothMap: onBluetoothStateChange: up=false
08-03 19:10:24.273  7022  7022 I BluetoothA2dpServiceJni: cleanupNative
08-03 19:10:24.273  7022  7547 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-03 19:10:24.274  7022  7022 I GKI_LINUX: GKI_exit_task 2 done
08-03 19:10:24.274  7022  7022 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-03 19:10:24.275  6897  6914 D BluetoothPan: onBluetoothStateChange on: false
08-03 19:10:24.277  7022  7022 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-03 19:10:24.277  7022  7022 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-03 19:10:24.277  7022  7022 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-03 19:10:24.278  7022  7022 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-03 19:10:24.278  7022  7022 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-03 19:10:24.279  1850  3970 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-03 19:10:24.281  6897  6914 D BluetoothA2dp: onBluetoothStateChange: up=false
08-03 19:10:24.282  1031  1095 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 19:10:24.282  6897  6914 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 19:10:24.283  7022  7022 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-03 19:10:24.283  7022  7022 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-03 19:10:24.285  6897  6914 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-03 19:10:24.286  6897  6914 D BluetoothPbap: onBluetoothStateChange: up=false
08-03 19:10:24.288  1850  1865 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 19:10:24.288  1850  2450 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 19:10:24.289  7022  7022 D BluetoothMapService: cleanup()
08-03 19:10:24.289  7022  7022 D BluetoothMapService: MAP Service closeService in
08-03 19:10:24.289  7022  7022 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-03 19:10:24.289  7022  7022 V BluetoothMapService: MAP Service closeService out
08-03 19:10:24.290  1031  1095 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-03 19:10:24.290  1031  1095 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,08-03 19:10:24.294  1031  1095 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-03 19:10:24.294  1031  1095 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-03 19:10:24.295  1031  1095 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@13041171 mBinding = false
08-03 19:10:24.295  1031  1095 D BluetoothManagerService: Sending unbind request.
08-03 19:10:24.300  7022  7488 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-03 19:10:24.301  7022  7022 I GKI_LINUX: GKI_exit_task 1 done
08-03 19:10:24.301  7022  7022 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-03 19:10:24.301  7022  7022 I BluetoothServiceJni: cleanupNative: return from cleanup
08-03 19:10:24.302  7022  7022 I art     : --- WEIRD: removing null entry 248
08-03 19:10:24.302  7022  7022 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-03 19:10:24.302  7022  7022 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-03 19:10:24.303  7022  7022 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
,08-03 19:10:24.306  1031  1095 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-03 19:10:24.308  7022  7022 I art     : System.exit called, status: 0
08-03 19:10:24.308  7022  7022 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-03 19:10:24.337  1939  1939 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:10:24.338  1939  2132 D LGBluetoothAPIService: Message: 2
08-03 19:10:24.338  1939  2132 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@13649c12 mBinding = false
08-03 19:10:24.338  1939  1939 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-03 19:10:24.338  1939  2132 D LGBluetoothAPIService: Sending unbind request.
08-03 19:10:24.339   310   310 V AudioFlinger: 7022 died, releasing its sessions
08-03 19:10:24.339   310   310 V AudioFlinger:  pid 1850 @ 0
08-03 19:10:24.339   310   310 V AudioFlinger:  pid 3487 @ 1
08-03 19:10:24.339   310   310 V AudioFlinger:  pid 3487 @ 2
08-03 19:10:24.341  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-03 19:10:24.342  6897  6897 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-03 19:10:24.344  6897  6897 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-03 19:10:24.344  6897  6897 D LGBluetoothEventManager: [BTUI] clear device connection state
08-03 19:10:24.346  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:10:24.347  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:10:24.350  6897  6897 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-03 19:10:24.353  1602  1602 D BluetoothAdapter: 342004933: getState() :  mService = null. Returning STATE_OFF
08-03 19:10:24.353  1602  1602 D BluetoothAdapter: 342004933: getState() :  mService = null. Returning STATE_OFF
08-03 19:10:24.380  1031  2030 I ActivityManager: Process com.android.bluetooth (pid 7022) has died
08-03 19:10:24.381  1031  2030 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
08-03 19:10:24.381  1031  2030 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
,08-03 19:10:24.385  1939  2132 D LGBluetoothAPIService: Message: 101
08-03 19:10:24.385  1939  2132 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-03 19:10:24.445  1031  1574 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7722 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-03 19:10:24.447  6897  6897 D DockEventReceiver: finishStartingService: stopping service
,08-03 19:10:24.517  7722  7722 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-03 19:10:24.518  7722  7722 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-03 19:10:24.518  7722  7722 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,08-03 19:10:24.520  7722  7722 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-03 19:10:24.541  7722  7722 D BluetoothAdapterApp: Loading JNI Library
,08-03 19:10:24.578  7722  7722 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1b5ae8db Instance Count = 1
,08-03 19:10:24.584  7722  7722 D BluetoothAdapterApp: onCreate
,08-03 19:10:24.608  7722  7722 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-03 19:10:24.608  7722  7722 D ProfileConfigQcom: Adding HeadsetService
,08-03 19:10:24.608  7722  7722 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-03 19:10:24.608  7722  7722 D ProfileConfigQcom: Adding A2dpService
08-03 19:10:24.608  7722  7722 D ProfileConfigQcom: [BTUI] HidService is supported
08-03 19:10:24.608  7722  7722 D ProfileConfigQcom: Adding HidService
08-03 19:10:24.609  7722  7722 D ProfileConfigQcom: [BTUI] HealthService is supported
08-03 19:10:24.609  7722  7722 D ProfileConfigQcom: Adding HealthService
08-03 19:10:24.609  7722  7722 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-03 19:10:24.610  7722  7722 D ProfileConfigQcom: [BTUI] PanService is supported
08-03 19:10:24.610  7722  7722 D ProfileConfigQcom: Adding PanService
08-03 19:10:24.610  7722  7722 D ProfileConfigQcom: [BTUI] GattService is supported
08-03 19:10:24.611  7722  7722 D ProfileConfigQcom: Adding GattService
08-03 19:10:24.611  7722  7722 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-03 19:10:24.611  7722  7722 D ProfileConfigQcom: Adding BluetoothMapService
08-03 19:10:24.611  7722  7722 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-03 19:10:24.612  7722  7722 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-03 19:10:24.613  7722  7722 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:10:24.613  7722  7722 V BluetoothPbapReceiver: ***********state = 10
08-03 19:10:24.614  7722  7722 V LGMDMManagerInternal: Create singleton instance
08-03 19:10:24.678  2195  2195 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-03 19:10:24.685  6897  6897 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-03 19:10:24.687  1031  1725 I ActivityManager: Killing 6918:com.lge.sync/1000 (adj 15): empty #17
08-03 19:10:24.721  1031  1542 D WifiService: Client connection lost with reason: 4
,08-03 19:10:24.772  1031  1047 W libprocessgroup: failed to open /acct/uid_1000/pid_6918/cgroup.procs: No such file or directory
,08-03 19:10:24.807  6897  6897 D BluetoothPermissionRequest: onReceive
,08-03 19:10:24.813  6897  6897 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-03 19:10:24.813  6897  6897 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-03 19:10:24.817  6897  6897 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-03 19:10:24.824  7722  7722 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-03 19:10:24.832  7722  7722 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:10:24.836  7722  7722 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-03 19:10:24.836  7722  7722 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-03 19:10:24.836  7722  7722 V BluetoothSapReceiver: SapReceiver onReceive 
08-03 19:10:24.838  7722  7722 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:10:24.838  7722  7722 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,08-03 19:10:24.845  6969  6969 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-03 19:10:26.251  6643  6774 D io.jxcore.node.ConnectivityMonitor: stop
,08-03 19:10:26.252  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 19:10:26.339  1602  1602 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-03 19:10:26.374  1031  1427 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-03 19:10:26.437  1031  1090 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7750 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-03 19:10:26.448  2031  2031 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-03 19:10:26.490  1602  1602 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,08-03 19:10:26.492  1602  1602 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,08-03 19:10:26.514  2031  2031 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-03 19:10:26.526  1031  1031 D administrator: Handling package changes for user 0
,08-03 19:10:26.532  7750  7750 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-03 19:10:26.622  7750  7750 D LgDataFeature: LgDataFeature() Constructor: none
08-03 19:10:26.622  7750  7750 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 19:10:26.629  1031  1031 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,08-03 19:10:26.629  1031  1031 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-03 19:10:26.677  1031  1089 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-03 19:10:26.696  1031  1089 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-03 19:10:26.707  7750  7793 I Babel   : MmsConfig: mnc/mcc: 0/0
08-03 19:10:26.707  7750  7793 I Babel   : MmsConfig.loadMmsSettings
,08-03 19:10:26.711  7750  7793 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-03 19:10:26.711  7750  7793 I Babel   : MmsConfig.loadFromDatabase
08-03 19:10:26.719  2031  2031 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-03 19:10:26.732  2504  2504 V GmsNetworkLocationProvi: DISABLE
,08-03 19:10:26.739  7750  7793 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-03 19:10:26.739  7750  7793 I Babel   : MmsConfig.loadFromResources
08-03 19:10:26.741  7750  7793 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-03 19:10:26.742  7750  7793 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-03 19:10:26.746  7750  7750 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:26.752  1031  1089 D LocationProviderProxy: applying state to connected service
,08-03 19:10:26.754  2504  2504 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-03 19:10:26.769  7750  7791 W AudioCapabilities: Unsupported mime audio/evrc
08-03 19:10:26.771  7750  7791 W AudioCapabilities: Unsupported mime audio/qcelp
08-03 19:10:26.773  7750  7791 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-03 19:10:26.776  1815  7797 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-03 19:10:26.776  1815  7797 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-03 19:10:26.777  7097  7097 I AppUp4:CustModeStarterReceiver: onReceive
,08-03 19:10:26.781  7097  7097 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1fe2068d
08-03 19:10:26.781  7097  7097 D AppUp4:CustFacade: isCustomizationCompleted : false
08-03 19:10:26.781  7097  7097 D AppUp4:CustFacade: isPhone : true
08-03 19:10:26.782  7097  7097 D AppUp4:CustModeStarterReceiver: begin check event
08-03 19:10:26.782  7097  7097 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-03 19:10:26.785  1815  4735 I Icing   : updateResources: need to parse e{com.google.android.gms}
,08-03 19:10:26.792  7750  7791 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-03 19:10:26.793  7750  7791 W AudioCapabilities: Unsupported mime audio/qcelp
08-03 19:10:26.794  7750  7791 W AudioCapabilities: Unsupported mime audio/evrc
,08-03 19:10:26.809  7750  7791 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-03 19:10:26.813  7750  7791 W VideoCapabilities: Unsupported mime video/divx
08-03 19:10:26.813  1031  1884 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7801 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-03 19:10:26.816  1031  1918 I ActivityManager: Killing 7124:com.lge.email/u0a23 (adj 15): empty #17
08-03 19:10:26.820  7750  7791 W VideoCapabilities: Unsupported mime video/divx311
08-03 19:10:26.822  7750  7791 W VideoCapabilities: Unsupported mime video/divx4
08-03 19:10:26.831  7750  7791 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-03 19:10:26.846  7750  7791 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-03 19:10:26.849  7750  7791 W AudioCapabilities: Unsupported mime audio/eac3
08-03 19:10:26.849  7750  7791 W AudioCapabilities: Unsupported mime audio/ac3
08-03 19:10:26.850  7750  7791 W AudioCapabilities: Unsupported mime audio/g726
08-03 19:10:26.851  7750  7791 W AudioCapabilities: Unsupported mime audio/wma-voice
08-03 19:10:26.852  7750  7791 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-03 19:10:26.852  7750  7791 W AudioCapabilities: Unsupported mime audio/adpcm
08-03 19:10:26.854  7750  7791 W VideoCapabilities: Unsupported mime video/theora
08-03 19:10:26.855  7750  7791 W VideoCapabilities: Unsupported mime video/mjpg
08-03 19:10:26.942  1031  1938 W libprocessgroup: failed to open /acct/uid_10023/pid_7124/cgroup.procs: No such file or directory
,08-03 19:10:26.990  7801  7801 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-03 19:10:26.991  7801  7801 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-03 19:10:26.991  7801  7801 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-03 19:10:26.992  7801  7801 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-03 19:10:26.993  7801  7801 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-03 19:10:27.082  7801  7801 I SystemConfig: BUILD Country: EU
08-03 19:10:27.082  7801  7801 I SystemConfig: BUILD Operator: OPEN
,08-03 19:10:27.145  1031  1725 I ActivityManager: Killing 6992:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-03 19:10:27.247  1031  1902 W libprocessgroup: failed to open /acct/uid_10026/pid_6992/cgroup.procs: No such file or directory
,08-03 19:10:27.327  1031  1975 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7824 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-03 19:10:27.333  7801  7822 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-03 19:10:27.333  7801  7822 I SystemConfig: existFile = false
08-03 19:10:27.333  7801  7822 I SystemConfig: canReadFile = false
08-03 19:10:27.334  7801  7822 I SystemConfig: systemFeature RCS result false
08-03 19:10:27.334  7801  7822 D SystemConfig: refreshRcsSupport() :false
,08-03 19:10:27.417  7824  7824 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-03 19:10:27.417  7824  7824 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-03 19:10:27.417  7824  7824 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-03 19:10:27.418  7824  7824 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-03 19:10:27.551  7824  7824 I AppConfig: Total System Memory = 2995761152
,08-03 19:10:27.562  7824  7824 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,08-03 19:10:27.636  1031  2010 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7843 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-03 19:10:27.638  1031  2010 I ActivityManager: Killing 6454:com.wsandroid.suite.lge/1000 (adj 15): empty #17
08-03 19:10:27.742  1031  1938 W libprocessgroup: failed to open /acct/uid_1000/pid_6454/cgroup.procs: No such file or directory
,08-03 19:10:27.957  7843  7843 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-03 19:10:28.040  7843  7843 D LgDataFeature: LgDataFeature() Constructor: none
,08-03 19:10:28.040  7843  7843 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 19:10:28.108  7843  7843 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-03 19:10:28.136  7843  7843 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-03 19:10:28.140  7843  7843 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-03 19:10:28.156  7843  7843 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-03 19:10:28.157  7843  7843 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-03 19:10:28.180  1031  2040 I ActivityManager: Killing 7159:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-03 19:10:28.213  1031  1047 W libprocessgroup: failed to open /acct/uid_10046/pid_7159/cgroup.procs: No such file or directory
,08-03 19:10:28.217  2846  2862 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-03 19:10:28.218  2846  2862 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3108e8a1 on behalf of 7843
08-03 19:10:28.228  7843  7843 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-03 19:10:28.232  4589  7883 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
08-03 19:10:28.250  7843  7843 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-03 19:10:28.278  1031  1943 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7886 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-03 19:10:28.305  7639  7679 D UEI.SmartControl: Internal timer expired: 1
08-03 19:10:28.306  7639  7679 D UEI.SmartControl: unbind internal service
,08-03 19:10:28.314  7639  7639 D UEI.SmartControl: Service.onUnbind: IControl
08-03 19:10:28.327  7639  7639 D UEI.SmartControl: Service.onDestroy
08-03 19:10:28.327  7639  7639 D UEI.SmartControl: Lock is in USE false
08-03 19:10:28.327  7639  7639 D UEI.SmartControl: unbind internal service
08-03 19:10:28.327  7639  7639 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@12f57e89
08-03 19:10:28.327  7639  7639 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-03 19:10:28.327  7639  7639 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-03 19:10:28.327  7639  7639 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-03 19:10:28.328  7639  7639 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-03 19:10:28.328  7639  7639 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-03 19:10:28.328  7639  7639 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-03 19:10:28.328  7639  7639 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-03 19:10:28.328  7639  7639 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-03 19:10:28.328  7639  7639 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 19:10:28.328  7639  7639 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-03 19:10:28.328  7639  7639 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-03 19:10:28.328  7639  7639 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 19:10:28.328  7639  7639 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-03 19:10:28.328  7639  7639 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-03 19:10:28.328  7639  7639 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-03 19:10:28.328  7639  7639 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@12f57e89
,08-03 19:10:28.331  7639  7639 D serial_port: close(fd = 25)
08-03 19:10:28.334  7639  7639 I UEI.SmartControl: Serial port is closed.
08-03 19:10:28.334  7639  7639 I UEI.SmartControl: Serial port is closed.
08-03 19:10:28.334  7639  7639 D UEI.SmartControl: Blaster closed
08-03 19:10:28.335  7639  7639 D UEI.SmartControl: Shut down QS...
08-03 19:10:28.335  7639  7639 D UEI.SmartControl: Stopping QS lib
08-03 19:10:28.335  7639  7639 D UEI.SmartControl: QS lib stop result = true
08-03 19:10:28.335  7639  7639 D UEI.SmartControl: Stopped QS lib
08-03 19:10:28.335  7639  7639 D UEI.SmartControl: Stopped file observer...
08-03 19:10:28.335  7639  7639 D UEI.SmartControl: QS shutdown complete
,08-03 19:10:28.384  7886  7886 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-03 19:10:28.415  7886  7886 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,08-03 19:10:28.415  7886  7886 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-03 19:10:28.415  7886  7886 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-03 19:10:28.415  7886  7886 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-03 19:10:28.415  7886  7886 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-03 19:10:28.415  7886  7886 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-03 19:10:28.436  1031  1938 I ActivityManager: Killing 7179:com.android.chrome/u0a57 (adj 15): empty #17
,08-03 19:10:28.466  1031  2040 W libprocessgroup: failed to open /acct/uid_10057/pid_7179/cgroup.procs: No such file or directory
,08-03 19:10:28.680  1031  1941 V SIM_STK : Menu title from STK is T-Mobile
,08-03 19:10:28.704  4589  7883 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 472 ms] updated apps [took 472 ms] 
,08-03 19:10:29.269  6643  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-03 19:10:29.269  6643  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1a7e4174 added. We now have 6 listener(s)
,08-03 19:10:29.269  6643  6774 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-03 19:10:29.283  6643  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 19:10:29.283  6643  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@136b669d added. We now have 7 listener(s)
08-03 19:10:29.283  6643  6774 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 19:10:29.284  6643  6774 I System.out: IsBluetoothEnabled
08-03 19:10:29.285  1031  2040 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:10:29.285  1031  2040 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-03 19:10:29.286  1031  1095 D BluetoothManagerService: Message: 2
08-03 19:10:29.289  6643  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:10:29.290  1031  1975 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:10:29.291  1031  1975 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-03 19:10:29.309  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-03 19:10:29.309  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-03 19:10:29.310  1031  1031 D Ulp_jni : JNI:system_update. Event-4
08-03 19:10:29.310  1031  1095 D BluetoothManagerService: Message: 1
08-03 19:10:29.310  1031  1095 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-03 19:10:29.337  1031  1095 D BluetoothManagerService: Message: 20
08-03 19:10:29.337  1031  1095 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@143b5a44:true
,08-03 19:10:29.341  7722  7722 D BluetoothAdapterState: make
08-03 19:10:29.346  7722  7722 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-03 19:10:29.346  7722  7722 I bluedroid-qcom: init
08-03 19:10:29.348  7722  7929 I BluetoothAdapterState: Entering OffState
08-03 19:10:29.348  7722  7722 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-03 19:10:29.348  7722  7722 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-03 19:10:29.348  7722  7722 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-03 19:10:29.349  7722  7722 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-03 19:10:29.349  7722  7722 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-03 19:10:29.351  7722  7722 I bluedroid-qcom: get_profile_interface socket
08-03 19:10:29.351  7722  7722 I bluedroid-qcom: get_profile_interface map_client
,08-03 19:10:29.355  7722  7933 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-03 19:10:29.347  7932  7932 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6496 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 19:10:29.357  7932  7932 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6496 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 19:10:29.368  7932  7932 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-03 19:10:29.368  7932  7932 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-03 19:10:29.368  7932  7932 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-03 19:10:29.374  1031  1031 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-03 19:10:29.374  1031  1095 D BluetoothManagerService: Message: 40
08-03 19:10:29.374  1031  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-03 19:10:29.375  7722  7933 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-03 19:10:29.375  7722  7737 I bluedroid-qcom: config_hci_snoop_log
08-03 19:10:29.377  1031  1095 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-03 19:10:29.377  1031  1095 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-03 19:10:29.379  7932  7932 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-03 19:10:29.382  1031  1031 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-03 19:10:29.383  1031  1031 D BluetoothManagerService: Stored Bluetooth name: G3
,08-03 19:10:29.386  7722  7933 D BluetoothAdapterProperties: Name is: G3
08-03 19:10:29.387  7932  7932 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-03 19:10:29.388  7932  7932 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-03 19:10:29.392  7722  7929 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-03 19:10:29.392  7722  7929 D BluetoothAdapterProperties: Setting state to 11
08-03 19:10:29.393  7722  7929 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-03 19:10:29.393  1031  1095 D BluetoothManagerService: Message: 60
08-03 19:10:29.393  1031  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-03 19:10:29.393  1031  1095 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-03 19:10:29.395  7722  7929 I LGBluetoothServiceJni: classInitNative: succeeds
,08-03 19:10:29.404  1939  1939 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:10:29.405  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-03 19:10:29.408  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:10:29.410  6897  6897 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-03 19:10:29.418  7722  7722 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-03 19:10:29.418  7722  7722 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:10:29.418  7722  7722 V BluetoothPbapReceiver: ***********state = 11
08-03 19:10:29.433  7722  7929 D BluetoothBondStateMachine: make
,08-03 19:10:29.434  2195  2195 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-03 19:10:29.436  7722  7929 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ebb9853
08-03 19:10:29.437  7722  7929 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-03 19:10:29.437  7722  7929 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ebb9853
08-03 19:10:29.437  7722  7929 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-03 19:10:29.437  7722  7929 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-03 19:10:29.438  7722  7947 I BluetoothBondStateMachine: StableState(): Entering Off State
08-03 19:10:29.442  7722  7929 E BluetoothAdapterService: File transfer profiles supported!!
08-03 19:10:29.449  7722  7929 E BluetoothAdapterService: File transfer profiles supported!!
,08-03 19:10:29.451  7722  7722 D HeadsetService: Received start request. Starting profile...
08-03 19:10:29.452  6897  6897 D BluetoothPermissionRequest: onReceive
08-03 19:10:29.452  7722  7722 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-03 19:10:29.452  7722  7722 D LGBluetoothHfpAdapter: Version 1.6
08-03 19:10:29.455  6897  6897 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-03 19:10:29.455  7722  7722 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-03 19:10:29.456  7722  7722 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-03 19:10:29.457  7722  7722 D HeadsetStateMachine: make
08-03 19:10:29.463  7722  7929 E BluetoothAdapterService: File transfer profiles supported!!
,08-03 19:10:29.469  7722  7929 E BluetoothAdapterService: File transfer profiles supported!!
08-03 19:10:29.474  7722  7929 E BluetoothAdapterService: File transfer profiles supported!!
08-03 19:10:29.479  7722  7929 E BluetoothAdapterService: File transfer profiles supported!!
,08-03 19:10:29.485  7722  7929 E BluetoothAdapterService: File transfer profiles supported!!
08-03 19:10:29.497  7722  7722 D LgDataFeature: LgDataFeature() Constructor: none
08-03 19:10:29.497  7722  7722 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 19:10:29.502  7722  7722 D HeadsetStateMachine: max_hf_connections = 1
08-03 19:10:29.502  7722  7722 I bluedroid-qcom: get_profile_interface handsfree
08-03 19:10:29.505  7722  7722 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-03 19:10:29.505   310   310 V AudioPolicyService: registerClient() client 0xb1019080, uid 1002
08-03 19:10:29.505   310   310 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-03 19:10:29.505   310   310 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-03 19:10:29.506   310   310 V AudioPolicyManagerEx: getOutput() returns output 2
08-03 19:10:29.506  7722  7722 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-03 19:10:29.506   310  2157 V AudioFlinger: registerClient() client 0xb101a3b8, pid 7722
08-03 19:10:29.507  7722  7722 V ToneGenerator: Create Track: 0xb4928a80
08-03 19:10:29.507  7722  7722 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-03 19:10:29.507  7722  7722 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-03 19:10:29.507   310  1375 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 19:10:29.507   310  1375 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-03 19:10:29.507  1602  1621 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 19:10:29.507  1602  1621 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-03 19:10:29.508  1850  2450 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 19:10:29.508  1850  2450 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-03 19:10:29.508  3487  3503 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 19:10:29.508  3487  3503 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-03 19:10:29.508  1031  1975 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 19:10:29.508  1031  1975 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-03 19:10:29.508  7722  7738 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 19:10:29.508  7722  7738 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-03 19:10:29.508   310  1380 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-03 19:10:29.508   310  1380 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-03 19:10:29.508   310  1380 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-03 19:10:29.508   310  1376 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 19:10:29.508   310  1380 V AudioPolicyManagerEx: getOutput() returns output 2
08-03 19:10:29.508   310  1376 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-03 19:10:29.509  1031  1941 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 19:10:29.509  1031  1941 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-03 19:10:29.509  7722  7737 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 19:10:29.509  7722  7737 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-03 19:10:29.509  1602  1624 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 19:10:29.509  1602  1624 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-03 19:10:29.509   310  1381 I AudioFlinger: isAudioPlaybackHookOn() false
08-03 19:10:29.509  1850  3975 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 19:10:29.509  1850  3975 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-03 19:10:29.509  3487  3504 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 19:10:29.509  3487  3504 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-03 ,19:10:29.509   310  1381 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-03 19:10:29.509   310  1381 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-03 19:10:29.509   310  1381 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-03 19:10:29.509   310  1381 V AudioPolicyManagerEx: getOutput() returns output 2
08-03 19:10:29.509  7722  7722 V AudioSystem: getLatency() output 2, latency 50
08-03 19:10:29.509  7722  7722 V AudioSystem: getFrameCount() output 2, frameCount 960
08-03 19:10:29.509  7722  7722 V AudioTrack: createTrack_l() output 2 afLatency 50
08-03 19:10:29.510   310  1380 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-03 19:10:29.510   310  1380 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-03 19:10:29.510   310  1380 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-03 19:10:29.510   310  1380 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-03 19:10:29.510   310  1380 V AudioFlinger: createTrack() lSessionId: 23
08-03 19:10:29.511  7722  7722 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-03 19:10:29.511   310  1380 V AudioFlinger: acquiring 23 from 7722, for 7722
08-03 19:10:29.511   310  1380 V AudioFlinger:  added new entry for 23
08-03 19:10:29.511  7722  7722 V ToneGenerator: ToneGenerator INIT OK, time: 171991
08-03 19:10:29.511  7722  7722 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ebb9853
08-03 19:10:29.512  7722  7950 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-03 19:10:29.512  7722  7950 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-03 19:10:29.513  7722  7950 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-03 19:10:29.513  7722  7950 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
,08-03 19:10:29.513  7722  7722 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ebb9853
08-03 19:10:29.514   310  1381 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7722
08-03 19:10:29.516  7722  7722 D A2dpService: Received start request. Starting profile...
08-03 19:10:29.516   310  1381 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-03 19:10:29.516   310  1381 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-03 19:10:29.516   310  1381 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-03 19:10:29.516   310  1381 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-03 19:10:29.516   310  1381 V voice   : voice_set_parameters: exit with code(0)
08-03 19:10:29.516   310  1381 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-03 19:10:29.516   310  1381 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-03 19:10:29.516   310  1381 V msm8974_platform: platform_set_parameters: exit with code(0)
08-03 19:10:29.516   310  1381 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-03 19:10:29.516   310  1381 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-03 19:10:29.516   310  1381 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-03 19:10:29.516  7722  7722 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-03 19:10:29.516  7722  7950 V ToneGenerator: ToneGenerator destructor
08-03 19:10:29.516  7722  7950 V ToneGenerator: stopTone
08-03 19:10:29.516  7722  7950 V ToneGenerator: Delete Track: 0xb4928a80
08-03 19:10:29.517  7722  7950 V AudioTrack: ~AudioTrack, releasing session id from 7722 on behalf of 7722
08-03 19:10:29.517   310  1380 V AudioFlinger: releasing 23 from 7722 for 7722
08-03 19:10:29.517   310  1380 V AudioFlinger:  decremented refcount to 0
08-03 19:10:29.517   310  1380 V AudioFlinger: purging stale effects
08-03 19:10:29.517   310  1380 V AudioPolicyService: AudioCommandThread() adding release output 2
08-03 19:10:29.517   310  1380 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-03 19:10:29.517   310  1105 V AudioPolicyService: AudioCommandThread() waking up
08-03 19:10:29.517   310  1105 V AudioPolicyService: AudioCommandThread() processing release output 2
08-03 19:10:29.517   310  1105 V AudioPolicyManager: releaseOutput() 2
08-03 19:10:29.517   310  1105 V AudioPolicyService: AudioCommandThread() going to sleep
08-03 19:10:29.517   310  1380 V AudioFlinger: PlaybackThread::Track destructor
08-03 19:10:29.517   310  1380 V AudioFlinger: removeClient_l() pid 7722, calling pid 310
08-03 19:10:29.517  7722  7722 V Avrcp   : make
08-03 19:10:29.519  7722  7722 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-03 19:10:29.519  7722  7722 I bluedroid-qcom: get_profile_interface avrcp
08-03 19:10:29.519  1031  1943 W Process : Unable to open /proc/7954/status
08-03 19:10:29.520  7722  7929 V LGMDMManager: Create singleton instance
08-03 19:10:29.523  7722  7929 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-03 19:10:29.528  7722  7722 V AudioManager: registerRemoteController: size of Media player list: 0
,08-03 19:10:29.529  7722  7722 E AudioManager: No RCC entry present to update
08-03 19:10:29.529  7722  7722 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-03 19:10:29.532  7722  7722 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
,08-03 19:10:29.533  7722  7722 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
,08-03 19:10:29.533  7722  7722 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-03 19:10:29.537  7722  7722 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-03 19:10:29.653  1031  1046 V SIM_STK : Menu title from STK is T-Mobile
08-03 19:10:29.653  1031  1046 V SIM_STK : Menu title from STK is T-Mobile
,08-03 19:10:29.783  1031  1941 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-03 19:10:29.792  7722  7722 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-03 19:10:29.797  7722  7722 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-03 19:10:29.797  7722  7722 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-03 19:10:29.797  7722  7722 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-03 19:10:29.797  7722  7722 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-03 19:10:29.797  7722  7722 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-03 19:10:29.797  7722  7722 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-03 19:10:29.797  7722  7722 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-03 19:10:29.797  7722  7722 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-03 19:10:29.797  7722  7722 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-03 19:10:29.798  7722  7722 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-03 19:10:29.798  7722  7722 I BluetoothA2dpServiceJni: classInitNative
08-03 19:10:29.798  7722  7722 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-03 19:10:29.798  7722  7722 D A2dpStateMachine: make
08-03 19:10:29.801  7722  7722 I bluedroid-qcom: get_profile_interface a2dp
,08-03 19:10:29.801  7722  7961 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-03 19:10:29.804  7722  7722 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-03 19:10:29.804  7722  7722 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-03 19:10:29.805  7722  7722 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ebb9853
08-03 19:10:29.805  7722  7960 D A2dpStateMachine: Enter Disconnected: -2
08-03 19:10:29.806  7722  7722 I BluetoothHidServiceJni: classInitNative: succeeds
08-03 19:10:29.808  7722  7722 D HidService: Received start request. Starting profile...
08-03 19:10:29.808  7722  7722 I bluedroid-qcom: get_profile_interface hidhost
08-03 19:10:29.808  7722  7722 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ebb9853
08-03 19:10:29.808  7722  7722 I BluetoothHealthServiceJni: classInitNative: succeeds
08-03 19:10:29.810  7722  7722 D HealthService: Received start request. Starting profile...
08-03 19:10:29.813  7722  7722 I bluedroid-qcom: get_profile_interface health
08-03 19:10:29.813  7722  7722 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-03 19:10:29.813  7722  7722 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ebb9853
08-03 19:10:29.814  7722  7722 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-03 19:10:29.816  7722  7722 D PanService: Received start request. Starting profile...
08-03 19:10:29.816  7722  7722 D BluetoothPanServiceJni: initializeNative(L110): pan
08-03 19:10:29.816  7722  7722 I bluedroid-qcom: get_profile_interface pan
08-03 19:10:29.823  7722  7722 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-03 19:10:29.823  7722  7722 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ebb9853
08-03 19:10:29.824  7722  7722 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-03 19:10:29.828  7722  7722 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-03 19:10:29.832  7722  7722 D BtGatt.GattService: Received start request. Starting profile...
08-03 19:10:29.832  7722  7722 D BtGatt.GattService: start()
08-03 19:10:29.832  7722  7722 I bluedroid-qcom: get_profile_interface gatt
08-03 19:10:29.833  7722  7722 D BtGatt.AdvertiseManager: advertise manager created
08-03 19:10:29.841  7722  7722 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ebb9853
08-03 19:10:29.843  7722  7722 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ebb9853
08-03 19:10:29.843  7722  7722 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-03 19:10:29.844  7722  7722 V BluetoothMapService: BluetoothMapBinder()
08-03 19:10:29.845  7722  7722 D BluetoothMapService: Received start request. Starting profile...
08-03 19:10:29.845  7722  7722 D BluetoothMapService: start()
,08-03 19:10:29.847  7722  7722 D BluetoothMapEmailSettingsLoader: Found 0 applications
,08-03 19:10:29.847  7722  7722 D BluetoothMapEmailAppObserver: createReceiver()
,08-03 19:10:29.848  7722  7722 D BluetoothMapEmailAppObserver: initObservers()
08-03 19:10:29.848  7722  7722 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-03 19:10:29.857  7722  7722 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ebb9853
,08-03 19:10:29.858  7722  7722 D HeadsetStateMachine: Proxy object connected
08-03 19:10:29.859  7722  7722 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-03 19:10:29.859  7722  7722 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-03 19:10:29.864  7722  7722 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-03 19:10:29.865  7722  7950 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-03 19:10:29.865  7722  7950 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-03 19:10:29.865  7722  7950 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-03 19:10:29.866  7722  7722 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:10:29.871  7722  7722 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-03 19:10:29.878  7722  7722 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-03 19:10:29.880  7722  7722 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-03 19:10:29.882  7722  7722 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-03 19:10:29.882  7722  7722 V PanService: [BTUI] SIM Extra State :ABSENT
08-03 19:10:29.887  7722  7722 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-03 19:10:29.887  7722  7722 V BluetoothMapService: Handler(): got msg=1
,08-03 19:10:29.889  7722  7722 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-03 19:10:29.889  7722  7722 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-03 19:10:29.889  7722  7722 V BluetoothSapReceiver: SapReceiver onReceive 
08-03 19:10:29.889  7722  7722 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:10:29.889  7722  7929 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-03 19:10:29.890  7722  7929 I bluedroid-qcom: enable
08-03 19:10:29.890  7722  7722 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-03 19:10:29.890  7722  7929 I bt_hci_bdroid: init
08-03 19:10:29.891  7722  7929 I bt_vendor: bt-vendor : init
08-03 19:10:29.891  7722  7929 I bt_vendor: bt-vendor : get_bt_soc_type
08-03 19:10:29.891  7722  7929 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-03 19:10:29.891  7722  7929 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-03 19:10:29.891  7722  7929 D bt_userial_mct: userial_init
08-03 19:10:29.892  7722  7929 D bt_hci_bdroid: set_power 1
08-03 19:10:29.892  7722  7929 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-03 19:10:29.892  7722  7929 I bt_vendor: Starting hciattach daemon
08-03 19:10:29.892  7722  7929 I bt_vendor: try to set true
08-03 19:10:29.893  7722  7972 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-03 19:10:29.893  7722  7972 I bt-btu  : btu_task pending for preload complete event
08-03 19:10:29.887  7975  7975 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6496 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 19:10:29.887  7975  7975 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6496 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 19:10:29.918  7976  7976 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-03 19:10:30.026  7987  7987 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-03 19:10:30.041  7988  7988 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-03 19:10:30.068  7990  7990 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-03 19:10:30.081  7991  7991 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-03 19:10:30.105  7992  7992 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-03 19:10:30.118  7993  7993 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-03 19:10:30.140  7995  7995 I libmdmdetect: ESOC framework not supported
,08-03 19:10:30.141  7995  7995 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-03 19:10:30.150  7995  7995 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-03 19:10:30.150  7995  7995 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-03 19:10:30.150  7995  7995 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-03 19:10:30.150  7995  7995 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-03 19:10:30.150  7995  7995 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-03 19:10:30.150  7995  7995 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-03 19:10:30.150  7995  7995 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-03 19:10:30.193  7995  7997 E QC-QMI  : qmi_client [7995] 15: failed to locate client data
08-03 19:10:30.196   439   439 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-03 19:10:30.196   439   439 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-03 19:10:30.249  8001  8001 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-03 19:10:30.264  8005  8005 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-03 19:10:30.295  7722  7929 I bt_vendor: bluetooth satus is on
08-03 19:10:30.295  7722  7929 D bt_hci_bdroid: preload
08-03 19:10:30.296  7722  7974 D bt_userial_mct: userial_open(port:0)
08-03 19:10:30.296  7722  7974 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-03 19:10:30.299  7722  7974 I bt_vendor: Done intiailizing UART
,08-03 19:10:30.300  7722  7974 I bt_vendor: Done intiailizing UART
,08-03 19:10:30.300  7722  7974 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-03 19:10:30.301  7722  7974 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-03 19:10:30.301  7722  7972 I bt-btu  : btu_task received preload complete event
,08-03 19:10:30.302  7722  7972 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
,08-03 19:10:30.302  7722  7972 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-03 19:10:30.307  7722  7972 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-03 19:10:30.311  7722  8007 D bt_userial_mct: Entering userial_read_thread()
,08-03 19:10:30.324  7722  7972 I         : BTE_InitTraceLevels -- TRC_HCI
08-03 19:10:30.324  7722  7972 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-03 19:10:30.324  7722  7972 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-03 19:10:30.324  7722  7972 I         : BTE_InitTraceLevels -- TRC_AVDT
08-03 19:10:30.324  7722  7972 I         : BTE_InitTraceLevels -- TRC_AVRC
08-03 19:10:30.324  7722  7972 I         : BTE_InitTraceLevels -- TRC_A2D
08-03 19:10:30.324  7722  7972 I         : BTE_InitTraceLevels -- TRC_BNEP
08-03 19:10:30.324  7722  7972 I         : BTE_InitTraceLevels -- TRC_BTM
08-03 19:10:30.324  7722  7972 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-03 19:10:30.324  7722  7972 I         : BTE_InitTraceLevels -- TRC_GAP
08-03 19:10:30.324  7722  7972 I         : BTE_InitTraceLevels -- TRC_PAN
08-03 19:10:30.324  7722  7972 I         : BTE_InitTraceLevels -- TRC_SDP
08-03 19:10:30.324  7722  7972 I         : BTE_InitTraceLevels -- TRC_GATT
08-03 19:10:30.324  7722  7972 I         : BTE_InitTraceLevels -- TRC_SMP
08-03 19:10:30.324  7722  7972 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-03 19:10:30.324  7722  7972 I         : BTE_InitTraceLevels -- TRC_BTIF
08-03 19:10:30.378  7722  7972 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-03 19:10:30.379  7722  7972 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa020c061 
08-03 19:10:30.379  7722  7972 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa020c061 
,08-03 19:10:30.406  7722  7933 E bt-btif : Calling BTA_HhEnable
08-03 19:10:30.407  7722  7933 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-03 19:10:30.407  7722  7933 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-03 19:10:30.414  7722  7933 D BluetoothAdapterProperties: Name is: G3
08-03 19:10:30.417  1031  1031 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-03 19:10:30.420  1031  1031 D BluetoothManagerService: Stored Bluetooth name: G3
,08-03 19:10:30.426  7722  7933 D BluetoothAdapterProperties: Scan Mode:20
,08-03 19:10:30.426  7722  7933 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-03 19:10:30.426  7722  7933 D bt_hci_bdroid: postload
08-03 19:10:30.428  7722  7933 D bte_conf: Device ID record 1 : primary
08-03 19:10:30.428  7722  7933 D bte_conf:   vendorId            = 00c4
,08-03 19:10:30.428  7722  7933 D bte_conf:   vendorIdSource      = 0001
08-03 19:10:30.428  7722  7933 D bte_conf:   product             = 13a1
08-03 19:10:30.428  7722  7933 D bte_conf:   version             = 1000
08-03 19:10:30.428  7722  7933 D bte_conf:   clientExecutableURL = 
08-03 19:10:30.428  7722  7933 D bte_conf:   serviceDescription  = 
08-03 19:10:30.428  7722  7933 D bte_conf:   documentationURL    = 
08-03 19:10:30.429  7722  7974 D bt_hci_bdroid: Used up Tx Cmd credits
08-03 19:10:30.429  7722  7933 D bte_conf: bte_load_did_conf no section named DID2.
08-03 19:10:30.431  7722  7974 D bt_hci_bdroid: Used up Tx Cmd credits
08-03 19:10:30.427  8009  8009 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6496 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-03 19:10:30.445  7722  8007 E bt_mct  : hci lib postload completed
08-03 19:10:30.445  7722  7929 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-03 19:10:30.445  7722  7929 D BluetoothAdapterProperties: ScanMode =  20
08-03 19:10:30.445  7722  7929 D BluetoothAdapterProperties: State =  11
08-03 19:10:30.446  7722  7929 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-03 19:10:30.446  7722  7929 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-03 19:10:30.446  7722  7929 D BluetoothAdapterProperties: Setting state to 12
08-03 19:10:30.446  7722  7929 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-03 19:10:30.447  7722  7933 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-03 19:10:30.437  8009  8009 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6496 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 19:10:30.454  1031  1095 D BluetoothManagerService: Message: 60
08-03 19:10:30.454  1031  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-03 19:10:30.455  1031  1095 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-03 19:10:30.455  1031  1095 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-03 19:10:30.459  7722  7929 I BluetoothAdapterState: Entering On State
,08-03 19:10:30.478  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:10:30.478  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:10:30.478  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:10:30.478  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 19:10:30.478  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:10:30.478  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:10:30.478  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:10:30.478  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 19:10:30.486  7722  7933 D BluetoothAdapterProperties: Discoverable Timeout:120
08-03 19:10:30.486  7722  7933 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-03 19:10:30.487  6643  6643 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 19:10:30.498  1031  1031 D BluetoothA2dp: Proxy object connected
,08-03 19:10:30.508  7722  7929 D LGBluetoothServiceAdapter: [BTUI] OnState
08-03 19:10:30.508  7722  7929 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-03 19:10:30.508  7722  7929 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-03 19:10:30.509  7722  7929 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-03 19:10:30.509  7722  7929 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-03 19:10:30.513  7722  7972 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-03 19:10:30.513  7722  7972 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-03 19:10:30.513  7722  7972 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-03 19:10:30.514  7722  7972 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-03 19:10:30.514  7722  7972 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-03 19:10:30.514  7722  7972 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-03 19:10:30.515  7722  7933 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-03 19:10:30.524  6897  6913 D BluetoothMap: onBluetoothStateChange: up=true
,08-03 19:10:30.535  7722  7972 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-03 19:10:30.535  7722  7972 W bt-smp  : Plain text(LSB ~ MSB) = f9 88 46 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-03 19:10:30.535  7722  7972 W bt-smp  : Encrypted text(LSB ~ MSB) = 06 7d 54 0d e6 dd ac 4d e4 21 f6 a2 b2 6c 11 22 
08-03 19:10:30.535  7722  7972 W bt-btm  : Stopping oneshot timer
08-03 19:10:30.551  6897  6913 D BluetoothPan: onBluetoothStateChange on: true
08-03 19:10:30.551  6897  6913 D BluetoothPan: onBluetoothStateChange call bindService
,08-03 19:10:30.568  8014  8014 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-03 19:10:30.575  1850  3970 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 19:10:30.579  6897  6897 D BluetoothMap: Proxy object connected
08-03 19:10:30.579  6897  6897 D MapProfile: Bluetooth service connected
08-03 19:10:30.579  6897  6897 D BluetoothMap: getConnectedDevices()
08-03 19:10:30.580  1850  1850 D BluetoothHeadset: Proxy object connected
08-03 19:10:30.582  6897  7604 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-03 19:10:30.583  7722  7972 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-03 19:10:30.584  7722  7972 W bt-smp  : Plain text(LSB ~ MSB) = 22 0f 7a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-03 19:10:30.584  7722  7972 W bt-smp  : Encrypted text(LSB ~ MSB) = 0c 8b f5 29 3d fd 98 94 0a 1a fc 85 17 1e 5b 0f 
08-03 19:10:30.584  7722  7972 W bt-btm  : Stopping oneshot timer
08-03 19:10:30.588  1031  1095 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 19:10:30.588  1031  1031 D BluetoothHeadset: Proxy object connected
08-03 19:10:30.590  6897  6914 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 19:10:30.596  7722  7738 V BluetoothMapService: getConnectedDevices()
,08-03 19:10:30.599  6897  6897 D BluetoothPan: BluetoothPAN Proxy object connected
08-03 19:10:30.599  6897  6897 D PanProfile: Bluetooth service connected
08-03 19:10:30.601  6897  7604 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-03 19:10:30.602  6897  6897 D BluetoothA2dp: Proxy object connected
,08-03 19:10:30.602  6897  6897 D A2dpProfile: Bluetooth service connected
08-03 19:10:30.603  7722  7972 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-03 19:10:30.604  7722  7972 W bt-smp  : Plain text(LSB ~ MSB) = 56 7d 6f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-03 19:10:30.604  7722  7972 W bt-smp  : Encrypted text(LSB ~ MSB) = 8b f6 8a 27 49 de 91 f0 31 42 1a e5 01 51 c0 23 
08-03 19:10:30.604  7722  7972 W bt-btm  : Stopping oneshot timer
08-03 19:10:30.606  6897  6897 D BluetoothHeadset: Proxy object connected
08-03 19:10:30.606  6897  6897 D HeadsetProfile: Bluetooth service connected
08-03 19:10:30.606  6897  6913 D BluetoothPbap: onBluetoothStateChange: up=true
08-03 19:10:30.607  6897  6897 D BluetoothInputDevice: Proxy object connected
08-03 19:10:30.607  6897  6897 D HidProfile: Bluetooth service connected
08-03 19:10:30.611  1850  1866 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-03 19:10:30.614  1850  1850 D BluetoothHeadset: Proxy object connected
08-03 19:10:30.614  1850  2450 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 19:10:30.615  1850  1850 D BluetoothHeadset: Proxy object connected
08-03 19:10:30.616  1031  1095 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-03 19:10:30.616  1031  1095 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-03 19:10:30.617  7722  7972 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-03 19:10:30.617  7722  7972 W bt-smp  : Plain text(LSB ~ MSB) = 2a 0f 49 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-03 19:10:30.617  7722  7972 W bt-smp  : Encrypted text(LSB ~ MSB) = ed 25 e1 63 83 e0 d0 1c 25 1d e4 7a 74 92 b6 a4 
08-03 19:10:30.617  7722  7972 W bt-btm  : Stopping oneshot timer
08-03 19:10:30.618  1031  1031 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-03 19:10:30.618  1939  1939 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:10:30.619  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-03 19:10:30.621  1939  2132 D LGBluetoothAPIService: Message: 1
08-03 19:10:30.621  1939  2132 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-03 19:10:30.622  1031  1095 D BluetoothManagerService: Message: 40
08-03 19:10:30.622  1031  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-03 19:10:30.623  7722  7722 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:10:30.623  7722  7722 D BluetoothMapService: STATE_ON
08-03 19:10:30.623  7722  7722 V BluetoothMapService: Handler(): got msg=1
08-03 19:10:30.624  7722  7722 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
,08-03 19:10:30.625  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:10:30.627  7722  7972 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-03 19:10:30.627  7722  7972 W bt-smp  : Plain text(LSB ~ MSB) = 8a fe 5e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-03 19:10:30.627  7722  7972 W bt-smp  : Encrypted text(LSB ~ MSB) = 56 c0 be b9 bc 95 97 0e b7 e0 97 80 26 37 c1 ad 
08-03 19:10:30.627  7722  7972 W bt-btm  : Stopping oneshot timer
08-03 19:10:30.630  7722  8029 D BluetoothMapMasInstance: MAS initSocket()
08-03 19:10:30.630  7722  8029 D BluetoothMapMasInstance:   masId = 00
08-03 19:10:30.630  7722  8029 D BluetoothMapMasInstance:   msgTypes = 0e
08-03 19:10:30.630  7722  8029 D BluetoothMapMasInstance:   masName = SMS/MMS
08-03 19:10:30.630  7722  8029 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-03 19:10:30.631  6897  6897 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-03 19:10:30.632  1031  1902 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:10:30.632  1939  2132 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-03 19:10:30.633  7722  8029 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 19:10:30.634  7722  8029 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0,
08-03 19:10:30.635  7722  8029 V BluetoothMapMasInstance: Succeed to create listening socket 
08-03 19:10:30.635  7722  8029 D BluetoothMapMasInstance: Accepting socket connection...
08-03 19:10:30.635  7722  7933 D BluetoothAdapterProperties: Scan Mode:21
08-03 19:10:30.635  7722  7933 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
,08-03 19:10:30.637  6897  6897 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-03 19:10:30.645  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:10:30.646  6897  6897 D DockEventReceiver: finishStartingService: stopping service
08-03 19:10:30.658  7722  7722 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ebb9853
08-03 19:10:30.658  7722  7722 V BluetoothPbapService: Pbap Service onCreate
08-03 19:10:30.658  7722  7722 V BluetoothPbapService: Starting PBAP service
,08-03 19:10:30.659  7722  7722 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-03 19:10:30.659  7722  7722 V BluetoothPbapService: Pbap Service onBind
08-03 19:10:30.661  7722  7722 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:10:30.661  6897  6897 D BluetoothPbap: Proxy object connected
08-03 19:10:30.661  6897  6897 D PbapServerProfile: Bluetooth service connected
08-03 19:10:30.661  7722  7722 V BluetoothPbapService: state: 12
08-03 19:10:30.662  7722  7722 D LGBluetoothAPIServer: [BTUI] onCreate()
08-03 19:10:30.663  7722  7722 D LGBluetoothAPIServer: [BTUI] onBind()
08-03 19:10:30.663  7722  7722 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-03 19:10:30.663  1939  1939 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-03 19:10:30.663  7722  7722 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:10:30.663  1939  2132 D LGBluetoothAPIService: Message: 100
08-03 19:10:30.663  1939  2132 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-03 19:10:30.663  7722  7722 V BluetoothPbapReceiver: ***********state = 12
08-03 19:10:30.665  7722  7722 V BluetoothPbapService: Handler(): got msg=1
08-03 19:10:30.666  7722  7722 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-03 19:10:30.666  2195  2195 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-03 19:10:30.667  2195  2195 D c       : Getting all permits...
08-03 19:10:30.667  2195  2195 D a       : Opening database...
08-03 19:10:30.667  7722  8033 V BluetoothPbapService: Pbap Service initSocket
08-03 19:10:30.668  1031  1938 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:10:30.668  7722  8033 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 19:10:30.670  7722  8033 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-03 19:10:30.670  7722  8033 V BluetoothPbapService: Succeed to create listening socket 
08-03 19:10:30.670  7722  8033 V BluetoothPbapService: Accepting socket connection...
,08-03 19:10:30.670  2195  2195 D a       : Opening database auth.proximity.permit_store...
08-03 19:10:30.671  2195  2195 D a       : Closing database...
08-03 19:10:30.680  6897  6897 D BluetoothPermissionRequest: onReceive
08-03 19:10:30.681  6897  6897 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-03 19:10:30.683  6897  6897 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-03 19:10:30.686  7722  7722 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-03 19:10:30.687  7722  7722 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-03 19:10:30.692  7722  7722 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-03 19:10:30.712  7722  7722 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-03 19:10:30.712  7722  7722 V BtOppService: onCreate
,08-03 19:10:30.842  1031  1943 I art     : Explicit concurrent mark sweep GC freed 26412(1288KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.771ms total 127.587ms
08-03 19:10:30.843  7722  7722 V BluetoothOppNotification: send message
,08-03 19:10:30.846  7722  7722 V BtOppService: Starting RfcommListener
08-03 19:10:30.852  7722  7722 D BluetoothOppPreference: Dumping Names:  
08-03 19:10:30.852  7722  7722 D BluetoothOppPreference: {}
08-03 19:10:30.852  7722  7722 D BluetoothOppPreference: Dumping Channels:  
08-03 19:10:30.852  7722  7722 D BluetoothOppPreference: {}
08-03 19:10:30.853  7722  7722 V BtOppService: onStartCommand
08-03 19:10:30.860  7722  7722 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:10:30.861  7722  7722 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-03 19:10:30.864  7722  8036 V BtOppService: Deleted complete outbound shares, number =  0
08-03 19:10:30.865  7722  8040 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-03 19:10:30.865  7722  8040 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,08-03 19:10:30.867  7722  8036 V BtOppService: Deleted complete inbound failed shares, number = 0
08-03 19:10:30.867  7722  8036 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-03 19:10:30.868  7722  8036 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@7e12f4c on behalf of 
08-03 19:10:30.869  7722  8040 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@18127b95 on behalf of 
08-03 19:10:30.870  7722  7722 V BluetoothOppNotification: new notify threadi!
08-03 19:10:30.872  7722  7722 V BluetoothOppNotification: send delay message
08-03 19:10:30.873  7722  8040 V BluetoothOppNotification: update too frequent, put in queue
08-03 19:10:30.873  7722  8041 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-03 19:10:30.874  7722  7722 V BtOppService: start RfcommListener
08-03 19:10:30.875  7722  8040 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-03 19:10:30.875  7722  8041 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@bc434aa on behalf of 
08-03 19:10:30.876  7722  7722 V BtOppService: RfcommListener started
08-03 19:10:30.876  7722  7722 V BtOppService: ContentObserver received notification
08-03 19:10:30.877  7722  8042 V BtOppRfcommListener: Starting RFCOMM listener....
08-03 19:10:30.877  1031  2010 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-03 19:10:30.878  7722  8042 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 19:10:30.879  7722  8041 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-03 19:10:30.879  7722  8042 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=75
08-03 19:10:30.880  7722  8042 V BtOppRfcommListener: Started RFCOMM listener....
08-03 19:10:30.880  7722  8042 I BtOppRfcommListener: Accept thread started.
08-03 19:10:30.880  7722  8042 V BtOppRfcommListener: Accepting connection...
,08-03 19:10:30.888  7722  7722 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ebb9853
08-03 19:10:30.888  7722  7722 V BluetoothFtpService: Ftp Service onCreate
08-03 19:10:30.888  7722  7722 I BluetoothFtpService: Ftp Service onCreate
08-03 19:10:30.888  7722  7722 V BluetoothFtpService: Ftp Service onStartCommand
08-03 19:10:30.888  7722  7722 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:10:30.888  7722  8043 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-03 19:10:30.888  7722  7722 V BluetoothFtpService: Starting Listening on sockets
08-03 19:10:30.888  7722  7722 V BtOppService: ContentObserver received notification
08-03 19:10:30.888  7722  8043 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-03 19:10:30.888  7722  7722 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-03 19:10:30.889  7722  7722 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-03 19:10:30.889  7722  7722 V BluetoothSapReceiver: SapReceiver onReceive 
08-03 19:10:30.889  7722  7722 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:10:30.889  7722  7722 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-03 19:10:30.889  7722  7722 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-03 19:10:30.889  7722  8041 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-03 19:10:30.891  7722  8041 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1697f438 on behalf of 
08-03 19:10:30.891  7722  8043 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@66c3c11 on behalf of 
08-03 19:10:30.891  7722  8041 V BluetoothOppNotification: outbound: succ-0  fail-0
08-03 19:10:30.892  7722  8043 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-03 19:10:30.892  7722  8043 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-03 19:10:30.892  7722  7722 V BluetoothFtpService: Handler(): got msg=1
,08-03 19:10:30.893  7722  7722 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-03 19:10:30.893  7722  7722 V BluetoothFtpService: Ftp Service initSocket
08-03 19:10:30.893  7722  8043 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3c88f176 on behalf of 
08-03 19:10:30.894  7722  8043 V BluetoothOppNotification: update too frequent, put in queue
08-03 19:10:30.895  7722  8041 V BluetoothOppNotification: outbound notification was removed.
08-03 19:10:30.895  7722  8043 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-03 19:10:30.895  7722  8041 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-03 19:10:30.896  1031  2030 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:10:30.896  7722  7722 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 19:10:30.897  7722  7722 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-03 19:10:30.899  7722  8044 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-03 19:10:30.900  7722  8041 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3724f377 on behalf of 
08-03 19:10:30.901  7722  8041 V BluetoothOppNotification: inbound: succ-0  fail-0
08-03 19:10:30.903  7722  8041 V BluetoothOppNotification: inbound notification was removed.
08-03 19:10:30.903  7722  8041 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-03 19:10:30.904  7722  8041 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1f41be4 on behalf of 
08-03 19:10:30.907  7722  7722 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ebb9853
08-03 19:10:30.907  7722  7722 V BluetoothSapService: Sap Service onCreate
08-03 19:10:30.908  7722  7722 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:10:30.908  7722  7722 V BluetoothSapService: state: 12
08-03 19:10:30.908  7722  7722 V BluetoothSapService: Starting SAP server process
,08-03 19:10:30.911  7722  7722 V BluetoothSapService: SAP Service startRfcommListenerThread
,08-03 19:10:30.907  8045  8045 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6496 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-03 19:10:30.907  8045  8045 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6496 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-03 19:10:30.912  7722  8047 V BluetoothSapService: Sap Service initRfcommSocket
,08-03 19:10:30.912  1031  1047 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-03 19:10:30.913  7722  8047 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback,
,08-03 19:10:30.914  7722  8047 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-03 19:10:30.914  7722  8047 V BluetoothSapService: Succeed to create listening socket 
08-03 19:10:30.914  7722  8047 V BluetoothSapService: Accepting socket connection...
08-03 19:10:30.918  8045  8045 V BT_SAP  : Event pipe created
,08-03 19:10:30.918  8045  8045 V BT_SAP  : create_server_socket qcom.sap.server
08-03 19:10:30.918  8045  8045 V BT_SAP  : created socket fd 6
08-03 19:10:31.347  6643  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:10:31.347  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,08-03 19:10:31.347  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:10:31.347  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 19:10:31.347  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:10:31.347  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:10:31.347  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:10:31.347  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 19:10:31.367  6643  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 19:10:31.369  6643  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 19:10:31.370  6643  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@386cb712 added. We now have 8 listener(s)
08-03 19:10:31.370  6643  6774 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 19:10:31.373  1031  2030 D WifiServiceImplEx: setWifiEnabled: false pid=6643, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-03 19:10:31.376  1031  2030 D WifiService: setWifiEnabled: false pid=6643, uid=10118
08-03 19:10:31.376  1031  2030 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-03 19:10:31.381  6643  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:10:31.384  1031  1918 D WifiServiceImplEx: setWifiEnabled: true pid=6643, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-03 19:10:31.384  1031  1918 D WifiService: setWifiEnabled: true pid=6643, uid=10118
08-03 19:10:31.384  1031  1918 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-03 19:10:31.403  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-03 19:10:31.403  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-03 19:10:31.403  1031  1031 D Ulp_jni : JNI:system_update. Event-4
,08-03 19:10:31.405  1031  1537 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
,08-03 19:10:31.405  1031  1537 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,08-03 19:10:31.407  1031  1537 E WifiUtil: wfc_util_ffile_check_copy(): pid[1031] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-03 19:10:31.407  1031  1537 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
,08-03 19:10:31.407  1031  1537 E WifiUtil: wfc_util_ffile_check_copy(): pid[1031] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-03 19:10:31.407  1031  1537 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
,08-03 19:10:31.408  1031  1537 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-03 19:10:31.408  1031  1537 E WifiHW  : unknown target_country: EU , set to default
08-03 19:10:31.408  1031  1537 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
,08-03 19:10:31.408  1031  1537 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-03 19:10:31.408  1031  1537 I WifiUtil: gEnableBmps=1
08-03 19:10:31.875  7722  7722 V BluetoothOppNotification: new notify threadi!
08-03 19:10:31.876  7722  7722 V BluetoothOppNotification: send delay message
,08-03 19:10:31.911  7722  8060 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-03 19:10:31.920  7722  8060 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@30c91250 on behalf of 
,08-03 19:10:31.938  7722  8060 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-03 19:10:31.942  7722  8060 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-03 19:10:31.944  7722  8060 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3115c49 on behalf of 
08-03 19:10:31.944  7722  8060 V BluetoothOppNotification: outbound: succ-0  fail-0
08-03 19:10:31.946  7722  8060 V BluetoothOppNotification: outbound notification was removed.
08-03 19:10:31.946  7722  8060 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-03 19:10:31.947  7722  8060 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1f8b94e on behalf of 
08-03 19:10:31.948  7722  8060 V BluetoothOppNotification: inbound: succ-0  fail-0
08-03 19:10:31.949  7722  8060 V BluetoothOppNotification: inbound notification was removed.
08-03 19:10:31.949  7722  8060 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-03 19:10:31.951  7722  8060 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3fb0da6f on behalf of 
,08-03 19:10:32.117   305   891 D SoftapController: Softap fwReload - Ok
,08-03 19:10:32.121  1031  1537 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (709ms)
,08-03 19:10:32.140   305   891 D CommandListener: Setting iface cfg
08-03 19:10:32.140   305   891 D CommandListener: Trying to bring down wlan0
08-03 19:10:32.149  1031  1095 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-03 19:10:32.149  1031  1095 D Tethering: InitialState.processMessage what=4
08-03 19:10:32.150  1031  1095 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-03 19:10:32.154   305   891 D CommandListener: Clearing all IP addresses on wlan0
08-03 19:10:32.163  1031  1537 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-03 19:10:32.167  8068  8068 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6496 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-03 19:10:32.177  8068  8068 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6496 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 19:10:32.201  1031  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-03 19:10:32.201  1031  1537 E WifiStateMachine: useWiFiOffloading() : false
08-03 19:10:32.201  1031  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-03 19:10:32.206  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-03 19:10:32.212  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-03 19:10:32.221  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-03 19:10:32.232  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 19:10:32.234  1031  1537 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-03 19:10:32.234  1031  1537 D WifiMonitor: connecting to supplicant
08-03 19:10:32.252  8068  8068 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-03 19:10:32.272  6897  6897 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-03 19:10:32.273  6897  6897 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-03 19:10:32.273  6897  6897 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-03 19:10:32.273  6897  6897 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-03 19:10:32.277  6897  6897 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-03 19:10:32.278  6897  6897 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-03 19:10:32.278  6897  6897 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-03 19:10:32.278  6897  6897 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-03 19:10:32.279  6897  6897 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-03 19:10:32.279  6897  6897 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-03 19:10:32.279  6897  6897 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-03 19:10:32.280  6897  6897 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-03 19:10:32.284  6897  6897 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-03 19:10:32.284  6897  6897 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,08-03 19:10:32.284  6897  6897 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-03 19:10:32.284  6897  6897 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-03 19:10:32.284  6897  6897 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-03 19:10:32.285  6897  6897 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-03 19:10:32.285  6897  6897 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-03 19:10:32.285  6897  6897 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-03 19:10:32.285  6897  6897 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-03 19:10:32.285  6897  6897 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-03 19:10:32.285  6897  6897 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-03 19:10:32.302  8068  8068 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-03 19:10:32.303  8068  8068 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-03 19:10:32.328  1031  1918 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8086 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-03 19:10:32.344   342   342 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 365us total 20.255ms
,08-03 19:10:32.361   342   342 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 351us total 16.416ms
,08-03 19:10:32.377   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 292us total 14.784ms
08-03 19:10:32.387  8068  8068 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-03 19:10:32.447  1031  2040 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8108 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-03 19:10:32.450  8068  8068 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-03 19:10:32.461  8086  8106 W FormManager: Network not available. Please check & try again.
,08-03 19:10:32.464  8068  8068 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-03 19:10:32.465  1031  1537 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-03 19:10:32.465  8086  8107 V FormManager: Network unavailable.
08-03 19:10:32.465  1031  1537 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-03 19:10:32.465  1031  8126 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-03 19:10:32.466  1031  8126 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-03 19:10:32.466  1031  8126 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-03 19:10:32.466  1031  8126 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-03 19:10:32.466  1031  1537 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-03 19:10:32.466  1031  1537 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-03 19:10:32.467  1031  1537 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-03 19:10:32.467  1031  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-03 19:10:32.468  1031  1537 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-03 19:10:32.468  1031  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-03 19:10:32.468  1031  1537 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-03 19:10:32.468  1031  1537 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-03 19:10:32.470  1031  1537 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-03 19:10:32.470  1031  1537 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-03 19:10:32.470  1031  1537 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-03 19:10:32.471  1031  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-03 19:10:32.471  1031  1537 E WifiStateMachine: useWiFiOffloading() : false
08-03 19:10:32.471  1031  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-03 19:10:32.471  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:32.471  8086  8107 V FormManager: Network unavailable.
08-03 19:10:32.471  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:32.472  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:32.472  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:32.472  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-03 19:10:32.472  1031  1537 D WifiNative-wlan0: doBoolean: SET update_config 1
08-03 19:10:32.473  1031  1537 D WifiNative-wlan0: SET update_config 1: returned true
08-03 19:10:32.473  1031  1537 D WifiConfigStore: Loading config and enabling all networks 
08-03 19:10:32.473  1031  1537 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-03 19:10:32.474  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:10:32.474  1939  1939 D WfdService: Waiting for WifiP2p enabling
08-03 19:10:32.475  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-03 19:10:32.475  1031  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-03 19:10:32.476  1031  1537 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
,08-03 19:10:32.481  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:10:32.481  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:10:32.481  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:10:32.481  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:10:32.481  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:10:32.481  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:10:32.481  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:10:32.481  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 19:10:32.482  1031  1537 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-03 19:10:32.483  6643  6643 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-03 19:10:32.491  1031  1537 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-03 19:10:32.492  1031  1537 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-03 19:10:32.493  1031  1537 D WifiStateMachine: enableVerboseLogging : level 2
08-03 19:10:32.493  1031  1537 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-03 19:10:32.493  1031  1537 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-03 19:10:32.493  1031  1537 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-03 19:10:32.494  1031  1537 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-03 19:10:32.494  1031  1537 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-03 19:10:32.495  1031  1537 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-03 19:10:32.495  1031  1537 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-03 19:10:32.495  1031  1537 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-03 19:10:32.495  1031  1537 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-03 19:10:32.496  1031  1537 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-03 19:10:32.496  1031  1537 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-03 19:10:32.496  1031  1537 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-03 19:10:32.496  1031  1537 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-03 19:10:32.497  1031  1537 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-03 19:10:32.497  1031  1537 D WifiStateMachine: Setting OUI to DA-A1-19
08-03 19:10:32.497  1031  1537 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-03 19:10:32.497  1939  1939 D WfdsService: Supplicant Connection state is changed : true
08-03 19:10:32.497  1939  2356 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-03 19:10:32.498  1939  2356 D WfdsService: Set the WFDS Monitor: true
08-03 19:10:32.498  1939  2356 D WfdsMonitor: WfdsMonitorThread create
08-03 19:10:32.498  1939  2356 D WfdsMonitor: WFDS Monitor is created and started
08-03 19:10:32.498  1939  2356 D WfdsService: WiFi: Supplicant connection re-established
08-03 19:10:32.498  7750  7750 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:32.498  1031  1537 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-03 19:10:32.498  1031  1537 D WifiNative-HAL: Setting external_sim to 1
08-03 19:10:32.498  1031  1537 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-03 19:10:32.499  1031  1537 D WifiNative-wlan0: SET external_sim 1: returned true
08-03 19:10:32.499  1031  1537 I WifiNative-HAL: startHal
08-03 19:10:32.499  1939  8127 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-03 19:10:32.499  1031  1537 D wifi    : setting scan oui 0xaf6dc500
08-03 19:10:32.499  1939  8127 E CtrlSupplicant: Succeed to open control connection
08-03 19:10:32.499  1031  1537 D WifiStateMachine: Setting OUI to DA-A1-19
08-03 19:10:32.499  1031  1537 I WifiNative-HAL: startHal
08-03 19:10:32.499  1031  1537 D wifi    : setting scan oui 0xaf6dc500
08-03 19:10:32.499  1939  8127 E CtrlSupplicant: Succeed to open monitor connection
08-03 19:10:32.499  1031  1537 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-03 19:10:32.500  1939  8127 D WfdsMonitor: Supplicant connection established
08-03 19:10:32.500  1939  2356 D WfdsService: Connected to the supplicant for wfds
08-03 19:10:32.500  1031  1537 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-03 19:10:32.500  1031  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-03 19:10:32.500  8068  8068 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-03 19:10:32.500  1031  1537 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-03 19:10:32.501  1031  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-03 19:10:32.501  8068  8068 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-03 19:10:32.501  1031  1537 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-03 19:10:32.501  1031  1537 D W,ifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-03 19:10:32.501  8068  8068 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-03 19:10:32.502  1031  1537 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-03 19:10:32.502  1031  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-03 19:10:32.502  8068  8068 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-03 19:10:32.502  1031  1537 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-03 19:10:32.502  1031  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-03 19:10:32.502  8068  8068 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-03 19:10:32.503  1031  1537 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-03 19:10:32.503  1031  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-03 19:10:32.503  8068  8068 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
,08-03 19:10:32.506  1031  1537 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-03 19:10:32.506  1031  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-03 19:10:32.506  8068  8068 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-03 19:10:32.507  1031  1537 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-03 19:10:32.507  1031  1537 E WifiNative: : [174,974,596 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-03 19:10:32.507  1031  1537 D WifiNative-wlan0: doBoolean: RECONNECT
08-03 19:10:32.508  1031  1537 D WifiNative-wlan0: RECONNECT: returned true
08-03 19:10:32.508  1031  1537 D WifiNative-wlan0: doString: [STATUS]
08-03 19:10:32.508  1031  8126 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-03 19:10:32.508  1031  8126 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-03 19:10:32.508  1031  1537 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-03 19:10:32.508  1031  1537 D WifiNative-wlan0: doBoolean: SET ps 1
08-03 19:10:32.508  1031  1537 D WifiNative-wlan0: SET ps 1: returned true
08-03 19:10:32.509  1031  1536 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:32.509  1031  1031 D WifiScanningService: SCAN_AVAILABLE : 3
08-03 19:10:32.509  1031  1031 D RttService: SCAN_AVAILABLE : 3
08-03 19:10:32.509  1031  1555 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:32.509  1031  1555 I WifiNative-HAL: startHal
08-03 19:10:32.509  1031  1555 D wifi    : getting scan capabilities on interface[1] = 0xaf6dc500
08-03 19:10:32.509  1031  1555 D wifi    : failed to get capabilities : -3
08-03 19:10:32.509  1031  1555 E WifiScanningService: could not get scan capabilities
08-03 19:10:32.509  1031  1537 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-03 19:10:32.509  1031  1556 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:32.510  1031  1537 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-03 19:10:32.510  1031  1537 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-03 19:10:32.510   305   891 D CommandListener: Setting iface cfg
08-03 19:10:32.510   305   891 D CommandListener: Trying to bring up p2p0
08-03 19:10:32.510  1031  1536 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-03 19:10:32.510  1031  1536 D LGWifiP2pService: P2pEnablingState
08-03 19:10:32.510  1031  1536 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:32.510  8108  8108 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-03 19:10:32.510  1031  1536 D LGWifiP2pService: P2p socket connection successful
08-03 19:10:32.511  1031  1536 D LGWifiP2pService: P2pEnabledState
08-03 19:10:32.511  1031  1536 D LGWifiP2pService: sending p2p connection changed broadcast
08-03 19:10:32.511  1031  1537 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-03 19:10:32.511  1031  1537 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-03 19:10:32.511  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-03 19:10:32.511  1031  1537 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-03 19:10:32.512  1939  1939 D WfdsService: WifiP2pState is changed : true
08-03 19:10:32.512  1031  1537 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-03 19:10:32.512  1031  1537 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-03 19:10:32.512  8068  8068 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-03 19,:10:32.512  1939  2356 D WfdsService: Receive the WFDS_ENABLE Method
08-03 19:10:32.512  1939  2356 D WfdsService: Set the WFDS Monitor: true
08-03 19:10:32.512  1939  2356 D WfdsService: Connected to the supplicant for wfds
08-03 19:10:32.512  1939  2356 D WfdsJNI : doCommand: WFDS_SET TRUE
08-03 19:10:32.512  8068  8068 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-03 19:10:32.513  1939  2356 D WfdsService: selectPreferredScanChannel [36]
08-03 19:10:32.513  1939  2356 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-03 19:10:32.513  1031  1537 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-03 19:10:32.513  1031  1537 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-03 19:10:32.513  1031  1537 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-03 19:10:32.513  1031  1537 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-03 19:10:32.513  8068  8068 E wpa_supplicant: disconnect_rssi_lvl: -100
08-03 19:10:32.514  6897  6897 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-03 19:10:32.514  1031  1537 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
,08-03 19:10:32.515  1031  1537 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-03 19:10:32.515  1031  1537 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-03 19:10:32.515  1031  1537 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-03 19:10:32.515  1031  1536 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-03 19:10:32.516  8068  8068 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-03 19:10:32.516  8068  8068 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 19:10:32.517  8068  8068 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-03 19:10:32.517  8068  8068 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:10:32.517  1031  8126 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-03 19:10:32.517  1031  8126 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 19:10:32.517  1031  8126 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 19:10:32.517  1031  8126 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 19:10:32.518  8068  8068 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:10:32.518  1031  8126 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 19:10:32.518  1031  8126 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:10:32.518  1031  8126 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:10:32.518  1031  8126 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:10:32.518  1031  8126 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 19:10:32.518  1031  8126 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:10:32.518  1031  8126 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:10:32.518  1031  8126 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:10:32.518  1939  8127 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 19:10:32.518  1939  8127 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 19:10:32.518  1031  1537 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-03 19:10:32.519  1031  1536 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-03 19:10:32.519  1031  1536 D WifiNative-p2p0: doBoolean: SET device_name G3
08-03 19:10:32.519  1939  1939 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-03 19:10:32.519  1031  1536 D WifiNative-p2p0: SET device_name G3: returned true
08-03 19:10:32.519  1031  1536 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-03 19:10:32.519  1031  1536 D LGWifiP2pService: before postfix = G3
08-03 19:10:32.519  1031  1536 D WifiServerServiceExt: postfix byte check : 2
08-03 19:10:32.519  1031  1536 D LGWifiP2pService: after postfix = G3
08-03 19:10:32.519  1031  1536 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-03 19:10:32.520  1031  1536 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-03 19:10:32.520  1031  1536 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-03 19:10:32.520  1939  1939 D WfdsService: isConnected: false
08-03 19:10:32.520  1031  1536 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-03 19:10:32.520  1031  1536 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-03 19:10:32.521  1031  1536 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-03 19:10:32.521  1031  1536 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-03 19:10:32.521,  1031  1536 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-03 19:10:32.521  1031  1536 D WifiNative-HAL: p2pGetDeviceAddress
08-03 19:10:32.521  1031  1536 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-03 19:10:32.521  1031  1536 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-03 19:10:32.521  1031  1536 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-03 19:10:32.522  1031  1537 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-03 19:10:32.522  6897  6897 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:10:32.522  1031  1536 D WifiNative-p2p0: P2P_FLUSH: returned true
08-03 19:10:32.522  1031  1536 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-03 19:10:32.523  1939  1939 I WfdStateTracker: handleP2pThisDeviceChanged
08-03 19:10:32.523  1031  1537 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-03 19:10:32.523  1939  1939 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-03 19:10:32.523  1031  1536 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-03 19:10:32.523  1939  1939 D WfdsService: Update P2p Interface State: 3
08-03 19:10:32.523  1031  1536 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-03 19:10:32.523  1031  1537 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-03 19:10:32.523  1031  1537 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-03 19:10:32.523  1031  1536 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-03 19:10:32.523  1031  1938 I ActivityManager: Killing 7197:com.lge.drmservice/u0a62 (adj 15): empty #17
08-03 19:10:32.523  1031  1536 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-03 19:10:32.529  1031  1536 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-03 19:10:32.529  1031  1536 D LGWifiP2pService: sending p2p persistent groups changed broadcast
,08-03 19:10:32.529  8068  8068 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-03 19:10:32.529  8068  8068 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-03 19:10:32.530  1031  8126 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-03 19:10:32.530  1031  8126 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-03 19:10:32.530  1031  8126 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-03 19:10:32.530  1031  8126 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-03 19:10:32.530  1031  1537 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-03 19:10:32.530  1031  1537 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-03 19:10:32.530  1031  1537 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-03 19:10:32.530  1031  1537 D WifiNative-wlan0: doBoolean: SCAN
08-03 19:10:32.531  1031  1537 D WifiNative-wlan0: SCAN: returned false
08-03 19:10:32.531  1031  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=174998  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-03 19:10:32.552  1031  1536 D LGWifiP2pService: InactiveState
,08-03 19:10:32.552  1031  1536 D LGWifiP2pService: InactiveState{ when=-30ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:32.552  1031  1536 D LGWifiP2pService: P2pEnabledState{ when=-30ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:32.552  1031  1536 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-03 19:10:32.552  8068  8068 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,08-03 19:10:32.553  8068  8068 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 19:10:32.553  1031  1986 W libprocessgroup: failed to open /acct/uid_10062/pid_7197/cgroup.procs: No such file or directory
08-03 19:10:32.553  1031  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=175021  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-03 19:10:32.553  8068  8068 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-03 19:10:32.554  8068  8068 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:10:32.554  1031  1536 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-03 19:10:32.554  1031  8126 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-03 19:10:32.554  1031  8126 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 19:10:32.554  1031  1536 D LGWifiP2pService: InactiveState{ when=-31ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:32.554  1031  1536 D LGWifiP2pService: P2pEnabledState{ when=-31ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:32.554  1031  8126 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 19:10:32.554  1031  8126 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 19:10:32.554  1031  1536 D LGWifiP2pService: InactiveState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:32.554  1031  8126 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 19:10:32.554  1031  1536 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:32.554  1031  8126 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:10:32.554  1031  1536 D LGWifiP2pService: DefaultState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:32.554  1031  1537 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-03 19:10:32.554  1031  8126 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:10:32.554  1031  8126 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:10:32.554  8068  8068 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:10:32.554  1939  8127 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-03 19:10:32.554  1939  8127 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 19:10:32.554  1031  1537 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-03 19:10:32.554  1939  8127 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 19:10:32.554  1031  8126 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 19:10:32.555  1031  8126 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:10:32.555  1031  8126 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:10:32.555  1031  8126 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 19:10:32.555  1031  1537 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-03 19:10:32.555  1031  1537 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-03 19:10:32.555  1031  1537 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-03 19:10:32.556  1031  1536 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=5 target=com.androi,d.internal.util.StateMachine$SmHandler }
08-03 19:10:32.556  1031  1536 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:32.556  1031  1536 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:32.556  1031  1536 D LGWifiP2pService: InactiveState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:32.556  1031  1536 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:32.556  1031  1536 D LGWifiP2pService: DefaultState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:32.556  1031  1536 D LGWifiP2pService: InactiveState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:32.556  1031  1536 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,08-03 19:10:32.556  1031  1536 D LGWifiP2pService: DefaultState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:32.556  1031  1031 E WifiServerServiceExt: No p2p device connected
08-03 19:10:32.556  1939  2356 W WfdsService: DefaultState - msg [9441285] is not handled
,08-03 19:10:32.562  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 19:10:32.562  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 19:10:32.563  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-03 19:10:32.563  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:32.563  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-03 19:10:32.563  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 19:10:32.564  1031  1031 D WifiServerServiceExt: setSupplicantStateSCANNING
08-03 19:10:32.567  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:10:32.578  8108  8108 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-03 19:10:32.582  6897  6897 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-03 19:10:32.587  8086  8131 W FormManager: Network not available. Please check & try again.
08-03 19:10:32.590  8086  8132 V FormManager: Network unavailable.
08-03 19:10:32.592  8086  8132 V FormManager: Network unavailable.
,08-03 19:10:32.594  6897  6897 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:10:32.610  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-03 19:10:32.610  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-03 19:10:32.612  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 19:10:32.615  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 19:10:32.622  4297  8133 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-03 19:10:32.625  4297  8134 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-03 19:10:32.626  4297  8134 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-03 19:10:32.665  1031  1986 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8135 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-03 19:10:32.807  8135  8135 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-03 19:10:32.807  8135  8135 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-03 19:10:32.818  8135  8135 V [BNRBootReceiver]: Boot Receiver Return
08-03 19:10:32.820  8135  8135 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-03 19:10:32.900  1031  1943 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8156 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-03 19:10:32.904  1031  1943 I ActivityManager: Killing 7221:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-03 19:10:32.943  1031  8126 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-03 19:10:32.944  1031  8126 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-03 19:10:32.944  1031  8126 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
,08-03 19:10:32.944  1031  8126 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: WPS-AP-AVAILABLE 
08-03 19:10:32.944  1031  8126 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
,08-03 19:10:32.944  8068  8068 E wpa_supplicant: USIM:  scard_init function
08-03 19:10:32.944  1031  1537 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-03 19:10:32.945  1031  1537 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-03 19:10:32.945  1031  1537 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-03 19:10:32.945  8068  8068 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-03 19:10:32.946  1031  1537 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
,08-03 19:10:32.946  1031  1537 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-03 19:10:32.946  1031  8126 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-03 19:10:32.946  1031  8126 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,08-03 19:10:32.987  1031  1941 W libprocessgroup: failed to open /acct/uid_10085/pid_7221/cgroup.procs: No such file or directory
08-03 19:10:32.990  1031  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=175457  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-03 19:10:32.995  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:32.995  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:32.995  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-03 19:10:32.997  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 19:10:32.997  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-03 19:10:33.001  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:10:33.007  1031  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=175474  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-03 19:10:33.007  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:33.007  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:33.007  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-03 19:10:33.009  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 19:10:33.009  1031  1031 D WifiServerServiceExt: setSupplicantStateASSOCIATING
,08-03 19:10:33.023  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-03 19:10:33.023  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 19:10:33.023  8156  8156 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-03 19:10:33.025  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:10:33.048  8156  8156 D PluginManager: init()
,08-03 19:10:33.101  8068  8068 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-03 19:10:33.105  1031  8126 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-03 19:10:33.105  1031  8126 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-03 19:10:33.106  1031  8126 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-03 19:10:33.106  1031  8126 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-03 19:10:33.106  1031  8126 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-03 19:10:33.106  1031  8126 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-03 19:10:33.107  1031  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=175574  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-03 19:10:33.109  1031  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=175576  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-03 19:10:33.110  1031  1537 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=175578
08-03 19:10:33.111  1031  1537 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=175579
08-03 19:10:33.111  1031  8126 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-03 19:10:33.111  1031  8126 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-03 19:10:33.112  8068  8068 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-03 19:10:33.112  1031  8126 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-03 19:10:33.112  1031  8126 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-03 19:10:33.112  8068  8068 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-03 19:10:33.112  1031  8126 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-03 19:10:33.112  1031  1537 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=175580
08-03 19:10:33.114  1031  1095 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-03 19:10:33.115  1031  8126 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-03 19:10:33.115  1031  8126 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-03 19:10:33.115  1031  8126 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-03 19:10:33.116  1031  8126 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-03 19:10:33.116  1031  8126 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-03 19:10:33.125  1031  1537 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=175593
08-03 19:10:33.126  1031  1537 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=175593
08-03 19:10:33.126  1031  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=175594  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-03 19:10:33.130  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:33.130  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:33.131  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-03 19:10:33.131  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 19:10:33.131  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 19:10:33.133  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:10:33.134  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:33.134  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:33.134  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
,08-03 19:10:33.136  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 19:10:33.136  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 19:10:33.137  1031  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=175605  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-03 19:10:33.138  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:10:33.139  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 19:10:33.139  1031  1031 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-03 19:10:33.140  1031  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=175607  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-03 19:10:33.141  1031  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=175608  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-03 19:10:33.141  1031  1537 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=175609
08-03 19:10:33.142  1031  1537 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=175609
08-03 19:10:33.142  1031  1537 D WifiNative-wlan0: doString: [STATUS]
08-03 19:10:33.143  1031  8126 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-03 19:10:33.143  1031  8126 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-03 19:10:33.143  1031  1537 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-03 19:10:33.145  1031  1537 I WifiServiceExtension: setVHTCapabilityType  : false
08-03 19:10:33.149  1031  1537 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-03 19:10:33.149  1031  1537 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-03 19:10:33.159  1031  1537 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-03 19:10:33.159  1031  1543 D ConnectivityService: Got NetworkAgent Messenger
08-03 19:10:33.159  1031  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-03 19:10:33.159  1031  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-03 19:10:33.159  1031  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-03 19:10:33.159  1031  1543 D ConnectivityService: NetworkAgent connected
08-03 19:10:33.159  1031  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-03 19:10:33.160  1031  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-03 19:10:33.162  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-03 19:10:33.162  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 19:10:33.164  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:33.164  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:33.164  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-03 19:10:33.164  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:10:33.166  1031  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-03 19:10:33.166  1031  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-03 19:10:33.166  1031  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-03 19:10:33.167  1031  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-03 19:10:33.167  1031  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-03 19:10:33.168  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:33.169  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:33.169  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-03 19:10:33.170  1031  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-03 19:10:33.172   305   891 D CommandListener: Setting iface cfg
08-03 19:10:33.178  1031  1537 E WifiStateMachine: Start Dhcp Watchdog 3
08-03 19:10:33.178  1031  1537 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=175646  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-03 19:10:33.179  1031  1537 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=175646  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-03 19:10:33.179  1031  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=175647  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-03 19:10:33.180  1031  1537 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-03 19:10:33.180  1031  8177 D DhcpStateMachine: StoppedState
08-03 19:10:33.181  1031  8177 D DhcpStateMachine: StoppedState{ when=-3ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:33.181  1031  1537 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-03 19:10:33.181  1031  8177 D DhcpStateMachine: WaitBeforeStartState
08-03 19:10:33.181  1031  1537 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-03 19:10:33.182  1031  1537 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-03 19:10:33.182  1031  1537 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-03 19:10:33.182  1031  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-03 19:10:33.183  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 19:10:33.183  1031  1031 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
,08-03 19:10:33.186  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 19:10:33.186  1031  1031 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-03 19:10:33.188  1031  1537 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=175655  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-03 19:10:33.188  1031  1537 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=175655  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-03 19:10:33.189  1031  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=175656  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-03 19:10:33.190  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 19:10:33.190  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 19:10:33.190  1031  1537 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14124] from screen [on:0 period:1365417958] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-03 19:10:33.191  1031  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1365417959] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-03 19:10:33.191  1031  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-03 19:10:33.192  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:10:33.199  1031  1543 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,08-03 19:10:33.199  1031  1537 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:10:33.202  1031  1537 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:10:33.202  1031  1537 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:10:33.203  1031  1537 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:10:33.204  1031  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:10:33.205  1031  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 19:10:33.205  1031  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-03 19:10:33.206  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 19:10:33.206  1031  1031 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-03 19:10:33.207  1031  1537 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=136,0,0
08-03 19:10:33.207  1031  1537 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=136,0,0
08-03 19:10:33.207  1031  1537 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-03 19:10:33.208  8068  8068 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-03 19:10:33.208  1031  1537 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-03 19:10:33.208  1031  1537 D WifiNative-wlan0: doBoolean: SET ps 0
08-03 19:10:33.209  1031  1537 D WifiNative-wlan0: SET ps 0: returned true
08-03 19:10:33.209  1031  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-03 19:10:33.209  8068  8068 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-03 19:10:33.209  1031  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-03 19:10:33.210  1031  1536 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3258d618 target=com.android.internal.util.StateMachine$SmHandler }
,08-03 19:10:33.210  1031  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3258d618 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:33.210  1031  1537 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-03 19:10:33.210  1031  1537 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-03 19:10:33.210  1031  1537 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-03 19:10:33.211  1031  8177 D DhcpStateMachine: WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:33.211  1031  8177 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-03 19:10:33.212   305   891 D CommandListener: Setting iface cfg
08-03 19:10:33.213   305   891 D CommandListener: Trying to bring up wlan0
08-03 19:10:33.213  1031  1537 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-03 19:10:33.214  1031  1537 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
08-03 19:10:33.214  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 19:10:33.214  1031  1031 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-03 19:10:33.214  1031  1537 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
08-03 19:10:33.214  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:10:33.215  1031  1536 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:33.215  1031  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:33.215  1031  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-03 19:10:33.215  8068  8068 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-03 19:10:33.215  1031  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-03 19:10:33.215  1031  1537 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-03 19:10:33.216  8068  8068 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-03 19:10:33.216  1031  1537 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-03 19:10:33.216  1031  1537 D WifiNative-wlan0: doBoolean: SET ps 1
08-03 19:10:33.237  1031  1537 D WifiNative-wlan0: SET ps 1: returned true
08-03 19:10:33.237  1031  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-03 19:10:33.238  1031  1537 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-03 19:10:33.238  1031  1537 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-03 19:10:33.239  1031  1537 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-03 19:10:33.239  1031  1537 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-03 19:10:33.240  1031  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-03 19:10:33.241  1031  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-03 19:10:33.241  1031  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-03 19:10:33.242  1031  1537 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-03 19:10:33.242  1031  1537 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-03 19:10:33.242  1031  1537 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-03 19:10:33.243  1031  1543 D ConnectivityService: ignoring duplicate network state non-change
08-03 19:10:33.245  1031  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-03 19:10:33.246  1031  1543 D ConnectivityService: Adding iface wlan0 to network 102
08-03 19:10:33.247  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 19:10:33.247  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 19:10:33.248  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:10:33.250  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:33.251  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:33.251  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,08-03 19:10:33.262  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:33.262  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:33.262  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-03 19:10:33.264  1031  1537 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-03 19:10:33.266  1031  1031 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-03 19:10:33.270  1939  1939 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-03 19:10:33.272  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:33.272  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:33.272  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-03 19:10:33.273  1031  1031 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-03 19:10:33.275  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 19:10:33.275  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 19:10:33.278  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:10:33.279  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:33.279  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:33.279  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,08-03 19:10:33.280  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 19:10:33.280  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-03 19:10:33.281  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:10:33.284  1031  1543 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-03 19:10:33.284  1031  1543 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-03 19:10:33.285  1031  1543 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-03 19:10:33.285  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 19:10:33.285  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-03 19:10:33.286  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:10:33.286   305   891 E Netd    : netlink response contains error (File exists)
08-03 19:10:33.286  1031  1543 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-03 19:10:33.287  1031  1543 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-03 19:10:33.287  1031  1543 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-03 19:10:33.287  1031  1543 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-03 19:10:33.288  1031  1543 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-03 19:10:33.288  1031  1543 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-03 19:10:33.288  1031  1543 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-03 19:10:33.288  1031  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-03 19:10:33.288  1031  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-03 19:10:33.288  1031  8173 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:33.288  1031  8173 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-03 19:10:33.288  1031  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 19:10:33.288  1031  8173 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-03 19:10:33.288  1031  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-03 19:10:33.288  1031  8173 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-03 19:10:33.289  1031  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:10:33.289  1031  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-03 19:10:33.289  1031  1543 D ConnectivityService: currentScore = 0, newScore = 20
08-03 19:10:33.289  1031  1543 D ConnectivityService:    accepting network in place of null
08-03 19:10:33.289  1031  1543 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:10:33.290  1031  1537 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:10:33.290  1031  1537 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-03 19:10:33.290  1850  1850 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:10:33.290  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specif,ier: <-1>]
08-03 19:10:33.290  1031  1543 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-03 19:10:33.290  1031  1543 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-03 19:10:33.291  1031  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-03 19:10:33.291   305  8183 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-03 19:10:33.292  1031  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-03 19:10:33.292  1031  1543 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-03 19:10:33.292  1031  1543 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-03 19:10:33.294  1031  1543 D ConnectivityService: validation of new default Network = false
08-03 19:10:33.294  1031  1543 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
,08-03 19:10:33.294  1031  1543 D DSQN    : enableDataServiceNotify 
08-03 19:10:33.294  1031  1543 D DSQN    : start dsqn bin
08-03 19:10:33.301  1031  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-03 19:10:33.301  1031  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:10:33.301  1031  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 19:10:33.302  1031  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 19:10:33.302  1602  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-03 19:10:33.297  8185  8185 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6496 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 19:10:33.297  8185  8185 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6496 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 19:10:33.315  8185  8185 E DSQN    : DSQN ssw
,08-03 19:10:33.318  1031  1031 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-03 19:10:33.318  1031  1031 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-03 19:10:33.319  1031  1031 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-03 19:10:33.319  1031  1031 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-03 19:10:33.332  1031  1535 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-03 19:10:33.337  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-03 19:10:33.338  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:10:33.339  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:10:33.344   305  8183 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-03 19:10:33.390   305  8183 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-03 19:10:33.413  1031  8177 D DhcpStateMachine: DHCPV4 request on wlan0
,08-03 19:10:33.415  1031  8177 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-03 19:10:33.415  1031  8177 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-03 19:10:33.420  6643  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:10:33.420  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:10:33.420  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:10:33.420  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:10:33.420  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:10:33.420  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 19:10:33.420  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 19:10:33.420  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 19:10:33.417  8189  8189 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6496 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 19:10:33.417  8189  8189 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6496 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 19:10:33.422  6643  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 19:10:33.436  8189  8189 I dhcpcd  : version 5.5.6 starting
08-03 19:10:33.438  8189  8189 E dhcpcd  : get_duid: m
08-03 19:10:33.438  8189  8189 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-03 19:10:33.438  8189  8189 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-03 19:10:33.440  6643  8190 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
08-03 19:10:33.441  6643  8190 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-03 19:10:33.447   305   890 D LGDataListener: argv[0]=dsqncommand
,08-03 19:10:33.447   305   890 D LGDataListener: argv[1]=wlan0
08-03 19:10:33.447   305   890 D LGDataListener: argv[2]=1
08-03 19:10:33.447   305   890 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-03 19:10:33.447  1031  1093 D DSQN    : DSQM DsqnNotification wlan0  1
08-03 19:10:33.447  1031  1093 D DSQN    : start to monitor internet connection
08-03 19:10:33.491  8189  8189 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-03 19:10:33.491  8189  8189 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-03 19:10:33.491  8189  8189 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-03 19:10:33.492  8189  8189 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-03 19:10:33.492  8189  8189 D dhcpcd  : wlan0: sending REQUEST (xid 0xd5c9d43b), next in 4.32 seconds
,08-03 19:10:33.495  1031  8173 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 03 Aug 2016 17:10:33 GMT], X-Android-Received-Millis=[1470244233494], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470244233446]}
,08-03 19:10:33.495  1031  8173 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-03 19:10:33.495  1031  8173 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-03 19:10:33.495  1031  1543 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-03 19:10:33.495  1031  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-03 19:10:33.495  1031  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-03 19:10:33.495  1031  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 19:10:33.495  1031  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-03 19:10:33.495  1031  1543 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-03 19:10:33.495  1031  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-03 19:10:33.495  1031  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:10:33.495  1031  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 19:10:33.496  1031  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 19:10:33.496  1031  1543 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:10:33.496  1602  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-03 19:10:33.496  1031  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-03 19:10:33.496  1031  1537 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:10:33.497  1031  1537 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-03 19:10:33.497  1850  1850 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:10:33.497  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-03 19:10:33.515  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-03 19:10:33.516  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-03 19:10:33.517  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 19:10:33.519  8189  8189 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
08-03 19:10:33.521  8156  8156 W ExternalStrings: load override strings
08-03 19:10:33.521  8156  8156 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-03 19:10:33.521  8156  8156 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-03 19:10:33.521  8156  8156 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-03 19:10:33.521  8156  8156 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-03 19:10:33.521  8156  8156 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-03 19:10:33.521  8156  8156 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-03 19:10:33.521  8156  8156 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-03 19:10:33.521  8156  8156 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-03 19:10:33.521  8156  8156 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-03 19:10:33.521  8156  8156 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-03 19:10:33.521  8156  8156 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-03 19:10:33.521  8156  8156 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 19:10:33.521  8156  8156 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-03 19:10:33.521  8156  8156 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-03 19:10:33.521  8156  8156 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 19:10:33.521  8156  8156 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-03 19:10:33.521  8156  8156 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-03 19:10:33.521  8156  8156 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-03 19:10:33.523  8156  8156 D StatusProvider: onCreate
08-03 19:10:33.577  8156  8156 V Signer  : override build config not found
08-03 19:10:33.578  8156  8156 D Signer  : value of property debug is false
,08-03 19:10:33.590  8189  8189 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
,08-03 19:10:33.591  8189  8189 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-03 19:10:33.591  8189  8189 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-03 19:10:33.592  8189  8189 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-03 19:10:33.592  8189  8189 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-03 19:10:33.592  8189  8189 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-03 19:10:33.593  8189  8189 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-03 19:10:33.593  8189  8189 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-03 19:10:33.609  8156  8156 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-03 19:10:33.609  8156  8156 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-03 19:10:33.609  8156  8156 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
,08-03 19:10:33.610  8156  8156 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-03 19:10:33.610  8156  8156 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-03 19:10:33.610  8156  8156 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-03 19:10:33.610  8156  8156 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-03 19:10:33.610  8156  8156 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-03 19:10:33.611  8156  8156 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-03 19:10:33.611  8156  8156 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-03 19:10:33.611  8156  8156 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-03 19:10:33.611  8156  8156 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-03 19:10:33.612  8156  8156 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
,08-03 19:10:33.621  8156  8156 V LGMDMManager: Create singleton instance
08-03 19:10:33.660  8156  8156 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-03 19:10:33.738  8156  8156 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-03 19:10:33.739  8156  8212 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-03 19:10:33.747  6897  6897 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 19:10:33.752  6897  6897 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:10:33.816  1031  2010 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8224 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-03 19:10:33.818  1031  2010 I ActivityManager: Killing 7259:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-03 19:10:33.819  1031  8177 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-03 19:10:33.820  1031  8177 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-03 19:10:33.821  1031  8177 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-03 19:10:33.821  1031  8177 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-03 19:10:33.821  1031  8177 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-03 19:10:33.821  1031  8177 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-03 19:10:33.821  1031  8177 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-03 19:10:33.821  1031  8177 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-03 19:10:33.821  1031  8177 D DhcpStateMachine: RunningState
08-03 19:10:33.875  8156  8211 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-03 19:10:34.031  1031  1046 W libprocessgroup: failed to open /acct/uid_10093/pid_7259/cgroup.procs: No such file or directory
,08-03 19:10:34.080  8224  8224 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-03 19:10:34.107  8224  8224 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-03 19:10:34.143  8224  8224 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-03 19:10:34.144  8224  8224 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
,08-03 19:10:34.144  8224  8224 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-03 19:10:34.144  8224  8224 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-03 19:10:34.145  8224  8224 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-03 19:10:34.147  8224  8224 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-03 19:10:34.152  8224  8224 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-03 19:10:34.159  8224  8224 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-03 19:10:34.163  8224  8224 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 19:10:34.175  8224  8224 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-03 19:10:34.177  8224  8224 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,08-03 19:10:34.177  6897  6897 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-03 19:10:34.180  8224  8224 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-03 19:10:34.181  6897  6897 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-03 19:10:34.185  8156  8156 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 19:10:34.189  8156  8212 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-03 19:10:34.192  6897  6897 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 19:10:34.198  6897  6897 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:10:34.206  8156  8211 D LgDataFeature: LgDataFeature() Constructor: none
,08-03 19:10:34.206  8156  8211 D LgDataFeature: LgDataFeature() Constructor Done, null
08-03 19:10:34.207  8224  8224 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 19:10:34.207  8224  8224 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 19:10:34.209  8224  8224 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-03 19:10:34.212  8156  8156 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 19:10:34.213  8156  8212 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-03 19:10:34.219  6897  6897 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 19:10:34.228  6897  6897 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:10:34.236  8224  8224 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 19:10:34.236  8224  8224 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 19:10:34.237  8224  8224 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-03 19:10:34.239  6897  6897 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-03 19:10:34.239  6897  6897 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,08-03 19:10:34.239  6897  6897 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-03 19:10:34.239  6897  6897 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-03 19:10:34.240  6897  6897 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-03 19:10:34.240  6897  6897 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-03 19:10:34.241  6897  6897 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-03 19:10:34.241  6897  6897 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-03 19:10:34.241  6897  6897 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-03 19:10:34.241  6897  6897 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-03 19:10:34.241  6897  6897 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-03 19:10:34.241  6897  6897 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-03 19:10:34.244  8156  8156 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 19:10:34.244  8156  8212 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-03 19:10:34.254  6897  6897 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 19:10:34.264  6897  6897 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:10:34.273  8224  8224 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 19:10:34.274  8224  8224 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 19:10:34.274  8224  8224 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-03 19:10:34.279  8156  8156 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-03 19:10:34.281  8156  8212 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-03 19:10:34.291  6897  6897 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 19:10:34.297  6897  6897 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:10:34.303  8224  8224 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 19:10:34.305  8224  8224 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-03 19:10:34.305  8224  8224 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-03 19:10:34.308  8156  8156 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 19:10:34.309  8156  8212 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-03 19:10:34.316  6897  6897 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 19:10:34.322  6897  6897 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:10:34.331  8224  8224 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 19:10:34.331  8224  8224 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 19:10:34.331  8224  8224 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-03 19:10:34.335  8156  8156 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 19:10:34.336  8156  8212 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-03 19:10:34.342  6897  6897 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 19:10:34.352  6897  6897 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-03 19:10:34.358  8224  8224 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 19:10:34.360  8224  8224 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 19:10:34.360  8224  8224 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-03 19:10:34.370  8156  8156 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 19:10:34.371  8156  8212 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-03 19:10:34.387  8156  8211 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
08-03 19:10:34.388  6897  6897 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 19:10:34.395  6897  6897 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:10:34.406  8224  8224 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 19:10:34.406  8224  8224 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-03 19:10:34.414  8224  8224 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-03 19:10:34.415  8156  8211 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-03 19:10:34.420  8156  8212 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-03 19:10:34.422  8156  8156 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-03 19:10:34.424  8156  8211 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-03 19:10:34.425  8156  8211 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-03 19:10:34.426  8156  8211 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-03 19:10:34.426  8156  8211 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-03 19:10:34.427  8156  8211 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
,08-03 19:10:34.432  6897  6897 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-03 19:10:34.434  8156  8211 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
,08-03 19:10:34.437  8156  8211 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-03 19:10:34.439  6897  6897 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:10:34.447  8224  8224 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 19:10:34.448  8224  8224 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-03 19:10:34.449  8224  8224 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-03 19:10:34.453  8156  8156 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 19:10:34.453  8156  8212 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-03 19:10:34.457  8108  8108 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-03 19:10:34.461  8108  8108 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,08-03 19:10:34.465  6897  6897 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-03 19:10:34.472  6897  6897 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:10:34.481  8224  8224 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-03 19:10:34.483  8224  8224 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 19:10:34.484  8224  8224 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-03 19:10:34.486  8224  8224 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-03 19:10:34.486  8224  8224 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-03 19:10:34.491  8156  8156 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 19:10:34.492  8156  8212 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-03 19:10:34.498  8108  8108 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-03 19:10:34.498  8108  8108 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,08-03 19:10:34.501  6897  6897 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 19:10:34.512  6897  6897 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 19:10:34.520  8224  8224 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 19:10:34.521  8224  8224 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 19:10:34.522  8224  8224 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-03 19:10:34.522  8224  8224 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-03 19:10:34.523  8224  8224 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-03 19:10:34.527  8156  8156 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-03 19:10:34.532  1031  1537 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-03 19:10:34.533  1031  1537 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-03 19:10:34.534  1031  1537 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-03 19:10:34.534  8224  8224 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-03 19:10:34.535  1031  1537 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-03 19:10:34.535  1031  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-03 19:10:34.535  8224  8224 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-03 19:10:34.536  1031  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-03 19:10:34.536  8224  8224 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-03 19:10:34.536  1031  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-03 19:10:34.536  1031  1543 D ConnectivityService: identical MTU - not setting
08-03 19:10:34.536  1031  1543 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-03 19:10:34.537  1031  1543 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-03 19:10:34.537  1031  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 19:10:34.537  1031  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 19:10:34.538  1031  1543 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 19:10:34.538  1602  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-03 19:10:34.577  8224  8224 D LgDataFeature: LgDataFeature() Constructor: none
08-03 19:10:34.577  8224  8224 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 19:10:34.584  8224  8224 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-03 19:10:34.585  8224  8224 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
,08-03 19:10:34.585  8224  8224 V SoundPool: create sampleID=1, fd=32, offset=17813 length=10857164
08-03 19:10:34.585  8224  8224 V SoundPool: doLoad: loading sample sampleID=1
08-03 19:10:34.586  8224  8224 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-03 19:10:34.586  8224  8263 V SoundPool: Start decode
08-03 19:10:34.587  8224  8263 V MediaPlayer[Native]: decode(32, 10857164, 17813)
08-03 19:10:34.587   310  2157 V MediaPlayerService: decode(23, 10857164, 17813)
08-03 19:10:34.587   310  2157 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-03 19:10:34.587   310  2157 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-03 19:10:34.587   310  2157 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-03 19:10:34.587   310  2157 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-03 19:10:34.588   310  2157 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-03 19:10:34.588   310  2157 V MediaPlayerService: player type = 3
08-03 19:10:34.588   310  2157 V AwesomePlayer: AwesomePlayer create()
08-03 19:10:34.588   310  2157 V AwesomePlayer: reset_l() 
08-03 19:10:34.588   310  2157 V AwesomePlayer: cancelPlayerEvents
08-03 19:10:34.588   310  2157 V AwesomePlayer: setAudioSink() 
08-03 19:10:34.588   310  2157 V AwesomePlayer: reset_l() 
08-03 19:10:34.588   310  2157 V AudioCache: notify(0xb5474900, 8, 0, 0)
08-03 19:10:34.588   310  2157 V AudioCache: ignored
08-03 19:10:34.588   310  2157 V AwesomePlayer: cancelPlayerEvents
08-03 19:10:34.588   310  2157 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-03 19:10:34.588   310  2157 V AwesomePlayer: setDataSource_l dataSource
08-03 19:10:34.589   310  2157 V LGParserOSAL: SniffLGParser start
08-03 19:10:34.589   310  2157 V LGParserOSAL: MainType:5, SubType=0
08-03 19:10:34.589   310  2157 V LGParserOSAL: #### check Mime : application/ogg
08-03 19:10:34.589   310  2157 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-03 19:10:34.589   310  2157 E MediaExtractor: Use LGExtractor :application/ogg 
08-03 19:10:34.590  8224  8224 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-03 19:10:34.590  7639  7639 D UEI.SmartControl: QS Service created
,08-03 19:10:34.592  8224  8224 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-03 19:10:34.592  8224  8224 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-03 19:10:34.605  8224  8224 V LGMDMManager: Create singleton instance
08-03 19:10:34.620  7639  7639 I UEI.SmartControl: Service initServices...
08-03 19:10:34.620  7639  7639 D UEI.SmartControl: QS start get config
08-03 19:10:34.641   310  2157 V LGParserOSAL: supported mime: application/ogg
08-03 19:10:34.641   310  2157 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-03 19:10:34.641   310  2157 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-03 19:10:34.641   310  2157 V AwesomePlayer: mBitrate = -1 bits/sec
08-03 19:10:34.641   310  2157 V AwesomePlayer: AudioTrack Setting
08-03 19:10:34.641   310  2157 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-03 19:10:34.641   310  2157 V AwesomePlayer: setAudioSource() 
08-03 19:10:34.641   310  2157 V MediaPlayerService: prepare
08-03 19:10:34.641   310  2157 V AwesomePlayer: prepareAsync_l() 
08-03 19:10:34.642   310  2157 V MediaPlayerService: wait for prepare
08-03 19:10:34.642   310  8264 V AwesomePlayer: onPrepareAsyncEvent() 
08-03 19:10:34.642   310  8264 V AwesomePlayer: initAudioDecoder() 
08-03 19:10:34.642   310  8264 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-03 19:10:34.642   310  8264 V AudioSystem: isOffloadSupported()
08-03 19:10:34.642   310  8264 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-03 19:10:34.642   310  8264 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-03 19:10:34.642   310  8264 I AudioFlinger: isAudioPlaybackHookOn() false
08-03 19:10:34.642   310  8264 V AwesomePlayer: getUseOffload() = 0 
08-03 19:10:34.642   310  8264 V OMXCodec: OMXCodec::Create
08-03 19:10:34.642   310  8264 V OMXCodec: findMatchingCodecs()
08-03 19:10:34.642   310  8264 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-03 19:10:34.642   310  8264 V OMXCodec: matchingCodecs.size()=1
08-03 19:10:34.643   310  8264 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-03 19:10:34.645   310  8264 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-03 19:10:34.645   310  8264 V LGCodecAdapter: LG Codec Adapter start
08-03 19:10:34.645   310  8264 V OMXCodec: OMXCodec Createtor
08-03 19:10:34.645   310  8264 V OMXCodec: setComponentRole
08-03 19:10:34.645   310  8264 V OMXCodec: configureCodec protected=0
08-03 19:10:34.645   310  8264 V LGCodecAdapter: called getLGCodecSpecificData
08-03 19:10:34.645   310  8264 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
,08-03 19:10:34.645   310  8264 V LGCodecOSAL: Called LGconfigureCodecMETA
08-03 19:10:34.645   310  8264 V LGCodecOSAL: Called LGconfigureCodecMSG
08-03 19:10:34.645   310  8264 V LGCodecOSAL: Not support LGCodec
08-03 19:10:34.645   310  8264 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-03 19:10:34.645   310  8264 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-03 19:10:34.645   310  8264 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-03 19:10:34.645   310  8264 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-03 19:10:34.645   310  8264 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-03 19:10:34.645   310  8264 V AudioSystem: isOffloadSupported()
08-03 19:10:34.645   310  8264 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-03 19:10:34.645   310  8264 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-03 19:10:34.645   310  8264 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-03 19:10:34.645   310  8264 V OMXCodec: init()
08-03 19:10:34.645   310  8264 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-03 19:10:34.645   310  8264 V OMXCodec: allocateBuffers
08-03 19:10:34.645   310  8264 V OMXCodec: allocateBuffersOnPort portIndex=0
,08-03 19:10:34.645   310  8264 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-03 19:10:34.646   310  8264 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f77e0 on input port
08-03 19:10:34.646   310  8264 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7830 on input port
08-03 19:10:34.646   310  8264 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f78d0 on input port
08-03 19:10:34.646   310  8264 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on input port
08-03 19:10:34.646   310  8264 V OMXCodec: allocateBuffersOnPort portIndex=1
08-03 19:10:34.646   310  8264 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-03 19:10:34.646   310  8264 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on output port
08-03 19:10:34.646   310  8264 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-03 19:10:34.646   310  8264 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
08-03 19:10:34.646   310  8264 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57f9060 on output port
08-03 19:10:34.646   310  8264 V OMXCodec: init() mAsyncCompletion wait!!! 
08-03 19:10:34.646   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-03 19:10:34.646   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-03 19:10:34.647   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-03 19:10:34.647   310  8264 V OMXCodec: init() mAsyncCompletion wait!!! 
08-03 19:10:34.647   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-03 19:10:34.647   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-03 19:10:34.647   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-03 19:10:34.647   310  8264 V OMXCodec: init() mAsyncCompletion wait free! 
08-03 19:10:34.647   310  8264 V AwesomePlayer: finishAsyncPrepare_l() 
08-03 19:10:34.647   310  8264 V AudioCache: notify(0xb5474900, 5, 0, 0)
08-03 19:10:34.647   310  8264 V AudioCache: ignored
08-03 19:10:34.647   310  8264 V AudioCache: notify(0xb5474900, 1, 0, 0)
08-03 19:10:34.647   310  8264 V AudioCache: prepared
08-03 19:10:34.647   310  2157 V AudioCache: wait - success
08-03 19:10:34.647   310  2157 V MediaPlayerService: start
08-03 19:10:34.647   310  2157 V AwesomePlayer: play_l() 
08-03 19:10:34.647   310  2157 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-03 19:10:34.647   310  2157 V AwesomePlayer: createAudioPlayer_l
08-03 19:10:34.647   310  2157 V AwesomePlayer: seekAudioIfNecessary_l() 
08-03 19:10:34.647   310  2157 V AwesomePlayer: startAudioPlayer_l() 
08-03 19:10:34.647   310  2157 D AudioPlayer: start of Playback, useOffload 0
08-03 19:10:34.647   310  2157 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-03 19:10:34.647   310  2157 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-03 19:10:34.650   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-03 19:10:34.650   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-03 19:10:34.650   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-03 19:10:34.650   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-03 19:10:34.650   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-03 19:10:34.650   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-03 19:10:34.650   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884608
08-03 19:10:34.650   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-03 19:10:34.650   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, fre,eing buffer 3041885008
08-03 19:10:34.650   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-03 19:10:34.650   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885648
08-03 19:10:34.650   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-03 19:10:34.650   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3045036128
08-03 19:10:34.650   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-03 19:10:34.651   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-03 19:10:34.651   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-03 19:10:34.651   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-03 19:10:34.651   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-03 19:10:34.651   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-03 19:10:34.651   310  8266 V OMXCodec: allocateBuffersOnPort portIndex=1
08-03 19:10:34.651   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-03 19:10:34.651   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
08-03 19:10:34.651   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-03 19:10:34.651   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on output port
08-03 19:10:34.651   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f1f0 on output port
08-03 19:10:34.652   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-03 19:10:34.652   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-03 19:10:34.653   310  2157 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-03 19:10:34.654   310  2157 V AudioCache: notify(0xb5474900, 6, 0, 0)
08-03 19:10:34.654   310  2157 V AudioCache: ignored
08-03 19:10:34.654   310  2157 V MediaPlayerService: wait for playback complete
08-03 19:10:34.655   310  8267 V AudioCache: write(0xb178b000, 4096)
08-03 19:10:34.655   310  8267 V AudioCache: memcpy(0xac300000, 0xb178b000, 4096)
08-03 19:10:34.656   310  8267 V AudioCache: write(0xb178b000, 4096)
08-03 19:10:34.657   310  8267 V AudioCache: memcpy(0xac301000, 0xb178b000, 4096)
08-03 19:10:34.657   310  8267 V AudioCache: write(0xb178b000, 4096)
,08-03 19:10:34.657   310  8267 V AudioCache: memcpy(0xac302000, 0xb178b000, 4096)
,08-03 19:10:34.661   310  8267 V AudioCache: write(0xb178b000, 4096),
08-03 19:10:34.661   310  8267 V AudioCache: memcpy(0xac303000, 0xb178b000, 4096)
08-03 19:10:34.661   310  8267 V AudioCache: write(0xb178b000, 4096)
08-03 19:10:34.661   310  8267 V AudioCache: memcpy(0xac304000, 0xb178b000, 4096)
08-03 19:10:34.661   310  8267 V AudioCache: write(0xb178b000, 4096)
08-03 19:10:34.661   310  8267 V AudioCache: memcpy(0xac305000, 0xb178b000, 4096)
08-03 19:10:34.662   310  8267 V AudioCache: write(0xb178b000, 4096)
08-03 19:10:34.662   310  8267 V AudioCache: memcpy(0xac306000, 0xb178b000, 4096)
08-03 19:10:34.663   310  8267 V AudioCache: write(0xb178b000, 4096)
08-03 19:10:34.663   310  8267 V AudioCache: memcpy(0xac307000, 0xb178b000, 4096)
08-03 19:10:34.663   310  8267 V AudioCache: write(0xb178b000, 4096)
,08-03 19:10:34.663   310  8267 V AudioCache: memcpy(0xac308000, 0xb178b000, 4096)
08-03 19:10:34.663   310  8267 V AudioCache: write(0xb178b000, 4096)
08-03 19:10:34.663   310  8267 V AudioCache: memcpy(0xac309000, 0xb178b000, 4096)
08-03 19:10:34.664   310  8267 V AudioCache: write(0xb178b000, 4096)
08-03 19:10:34.664   310  8267 V AudioCache: memcpy(0xac30a000, 0xb178b000, 4096)
08-03 19:10:34.664   310  8267 V AudioCache: write(0xb178b000, 4096)
08-03 19:10:34.664   310  8267 V AudioCache: memcpy(0xac30b000, 0xb178b000, 4096)
08-03 19:10:34.665   310  8267 V AudioCache: write(0xb178b000, 4096)
,08-03 19:10:34.665   310  8267 V AudioCache: memcpy(0xac30c000, 0xb178b000, 4096)
08-03 19:10:34.666   310  8267 V AudioCache: write(0xb178b000, 4096)
08-03 19:10:34.666   310  8267 V AudioCache: memcpy(0xac30d000, 0xb178b000, 4096)
08-03 19:10:34.666   310  8267 V AudioCache: write(0xb178b000, 4096)
08-03 19:10:34.666   310  8267 V AudioCache: memcpy(0xac30e000, 0xb178b000, 4096)
08-03 19:10:34.667   310  8267 V AudioCache: write(0xb178b000, 4096)
08-03 19:10:34.667   310  8267 V AudioCache: memcpy(0xac30f000, 0xb178b000, 4096)
,08-03 19:10:34.667   310  8267 V AudioCache: write(0xb178b000, 4096)
08-03 19:10:34.667   310  8267 V AudioCache: memcpy(0xac310000, 0xb178b000, 4096)
08-03 19:10:34.668   310  8267 V AudioCache: write(0xb178b000, 4096)
08-03 19:10:34.668   310  8267 V AudioCache: memcpy(0xac311000, 0xb178b000, 4096)
08-03 19:10:34.669   310  8267 V AudioCache: write(0xb178b000, 4096)
08-03 19:10:34.669   310  8267 V AudioCache: memcpy(0xac312000, 0xb178b000, 4096)
,08-03 19:10:34.669   310  8267 V AudioCache: write(0xb178b000, 4096)
,08-03 19:10:34.669   310  8267 V AudioCache: memcpy(0xac313000, 0xb178b000, 4096)
08-03 19:10:34.670   310  8267 V AudioCache: write(0xb178b000, 4096)
08-03 19:10:34.670   310  8267 V AudioCache: memcpy(0xac314000, 0xb178b000, 4096)
08-03 19:10:34.671   310  8267 V AudioCache: write(0xb178b000, 4096)
08-03 19:10:34.671   310  8267 V AudioCache: memcpy(0xac315000, 0xb178b000, 4096)
08-03 19:10:34.681   310  8267 V AudioCache: write(0xb178b000, 4096)
08-03 19:10:34.681   310  8267 V AudioCache: memcpy(0xac316000, 0xb178b000, 4096)
,08-03 19:10:34.681   310  8267 V AudioCache: write(0xb178b000, 4096)
08-03 19:10:34.681   310  8267 V AudioCache: memcpy(0xac317000, 0xb178b000, 4096)
08-03 19:10:34.682   310  8267 V AudioCache: write(0xb178b000, 4096)
08-03 19:10:34.682   310  8267 V AudioCache: memcpy(0xac318000, 0xb178b000, 4096)
08-03 19:10:34.682   310  8267 V AudioCache: write(0xb178b000, 4096)
08-03 19:10:34.682   310  8267 V AudioCache: memcpy(0xac319000, 0xb178b000, 4096)
08-03 19:10:34.682   310  8267 V AudioCache: write(0xb178b000, 4096)
08-03 19:10:34.682   310  8267 V AudioCache: memcpy(0xac31a000, 0xb178b000, 4096)
08-03 19:10:34.683   310  8267 V AudioCache: write(0xb178b000, 4096)
08-03 19:10:34.683   310  8267 V AudioCache: memcpy(0xac31b000, 0xb178b000, 4096)
08-03 19:10:34.683   310  8267 V AudioCache: write(0xb178b000, 4096)
08-03 19:10:34.683   310  8267 V AudioCache: memcpy(0xac31c000, 0xb178b000, 4096)
08-03 19:10:34.684   310  8267 V AudioCache: write(0xb178b000, 4096)
08-03 19:10:34.684   310  8267 V AudioCache: memcpy(0xac31d000, 0xb178b000, 4096)
08-03 19:10:34.684   310  8267 V AudioCache: write(0xb178b000, 4096)
08-03 19:10:34.684   310  8267 V AudioCache: memcpy(0xac31e000, 0xb178b000, 4096)
08-03 19:10:34.684   310  8267 V AudioCache: write(0xb178b000, 4096)
08-03 19:10:34.684   310  8267 V AudioCache: memcpy(0xac31f000, 0xb178b000, 4096)
08-03 19:10:34.685   310  8267 V AudioCache: write(0xb178b000, 4096)
08-03 19:10:34.685   310  8267 V AudioCache: memcpy(0xac320000, 0xb178b000, 4096)
08-03 19:10:34.685   310  8267 V AudioCache: write(0xb178b000, 4096)
08-03 19:10:34.685   310  8267 V AudioCache: memcpy(0xac321000, 0xb178b000, 4096)
08-03 19:10:34.685   310  8267 V AudioCache: write(0xb178b000, 4096)
08-03 19:10:34.685   310  8267 V AudioCache: memcpy(0xac322000, 0xb178b000, 4096)
08-03 19:10:34.686   310  8267 V AudioCache: write(0xb178b000, 4096)
08-03 19:10:34.686   310  8267 V AudioCache: memcpy(0xac323000, 0xb178b000, 4096)
08-03 19:10:34.686   310  8267 V AudioCache: write(0xb178b000, 4096)
08-03 19:10:34.686   310  8267 V AudioCache: memcpy(0xac324000, 0xb178b000, 4096)
08-03 19:10:34.686   310  8267 V AudioCache: write(0xb178b000, 4096)
08-03 19:10:34.686   310  8267 V AudioCache: memcpy(0xac325000, 0xb178b000, 4096)
08-03 19:10:34.687   310  8267 V AudioCache: write(0xb178b000, 4096)
08-03 19:10:34.687   310  8267 V AudioCache: memcpy(0xac326000, 0xb178b000, 4096)
08-03 19:10:34.687   310  8267 V AudioCache: write(0xb178b000, 4096)
08-03 19:10:34.687   310  8267 V AudioCache: memcpy(0xac327000, 0xb178b000, 4096)
08-03 19:10:34.688   310  8267 V AudioCache: write(0xb178b000, 4096)
08-03 19:10:34.688   310  8267 V AudioCache: memcpy(0xac328000, 0xb178b000, 4096)
08-03 19:10:34.688   310  8267 V AudioCache: write(0xb178b000, 4096)
08-03 19:10:34.688   310  8267 V AudioCache: memcpy(0xac329000, 0xb178b000, 4096),
08-03 19:10:34.688   310  8267 V AudioCache: write(0xb178b000, 4096)
08-03 19:10:34.688   310  8267 V AudioCache: memcpy(0xac32a000, 0xb178b000, 4096)
08-03 19:10:34.689   310  8267 V AudioCache: write(0xb178b000, 4096)
08-03 19:10:34.689   310  8267 V AudioCache: memcpy(0xac32b000, 0xb178b000, 4096)
08-03 19:10:34.689   310  8267 V AudioCache: write(0xb178b000, 4096)
08-03 19:10:34.689   310  8267 V AudioCache: memcpy(0xac32c000, 0xb178b000, 4096)
08-03 19:10:34.689   310  8267 V AudioCache: write(0xb178b000, 4096)
08-03 19:10:34.689   310  8267 V AudioCache: memcpy(0xac32d000, 0xb178b000, 4096)
08-03 19:10:34.690   310  8267 V AudioCache: write(0xb178b000, 4096)
08-03 19:10:34.690   310  8267 V AudioCache: memcpy(0xac32e000, 0xb178b000, 4096)
08-03 19:10:34.696   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-03 19:10:34.697   310  8267 V AudioCache: write(0xb178b000, 4096)
08-03 19:10:34.697   310  8267 V AudioCache: memcpy(0xac32f000, 0xb178b000, 4096)
08-03 19:10:34.697   310  8267 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-03 19:10:34.697   310  8267 V AudioCache: write(0xb178b000, 4096)
08-03 19:10:34.697   310  8267 V AudioCache: memcpy(0xac330000, 0xb178b000, 4096)
08-03 19:10:34.697   310  8267 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-03 19:10:34.697   310  8267 V AudioCache: write(0xb178b000, 4096)
08-03 19:10:34.697   310  8267 V AudioCache: memcpy(0xac331000, 0xb178b000, 4096)
08-03 19:10:34.697   310  8267 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-03 19:10:34.697   310  8267 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-03 19:10:34.697   310  8267 V AwesomePlayer: postAudioEOS() 
08-03 19:10:34.697   310  8267 V AudioCache: write(0xb178b000, 280)
08-03 19:10:34.697   310  8267 V AudioCache: memcpy(0xac332000, 0xb178b000, 280)
08-03 19:10:34.700   310  8264 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-03 19:10:34.700   310  8264 V AwesomePlayer: onStreamDone
08-03 19:10:34.700   310  8264 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-03 19:10:34.700   310  8264 V AudioCache: notify(0xb5474900, 2, 0, 0)
08-03 19:10:34.700   310  8264 V AudioCache: playback complete
08-03 19:10:34.700   310  8264 V AwesomePlayer: pause_l() 
08-03 19:10:34.700   310  8264 V AudioCache: notify(0xb5474900, 7, 0, 0)
08-03 19:10:34.700   310  8264 V AudioCache: ignored
08-03 19:10:34.700   310  8264 V AwesomePlayer: cancelPlayerEvents
08-03 19:10:34.700   310  2157 V AudioCache: wait - success
08-03 19:10:34.700   310  2157 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-03 19:10:34.700   310  8264 D AudioPlayer: Pause Playback at 1068125
08-03 19:10:34.701   310  2157 V AwesomePlayer: reset_l() 
08-03 19:10:34.701   310  2157 V AudioCache: notify(0xb5474900, 8, 0, 0)
08-03 19:10:34.701   310  2157 V AudioCache: ignored
08-03 19:10:34.701   310  2157 V AwesomePlayer: cancelPlayerEvents
08-03 19:10:34.701   310  2157 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-03 19:10:34.701   310  2157 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-03 19:10:34.701   310  2157 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-03 19:10:34.701   310  2157 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-03 19:10:34.701   310  2157 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-03 19:10:34.701   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-03 19:10:34.701   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-03 19:10:34.701   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-03 19:10:34.701   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 0
08-03, 19:10:34.701   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-03 19:10:34.701   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f78d0 on port 0
08-03 19:10:34.701   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-03 19:10:34.701   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7830 on port 0
08-03 19:10:34.701   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-03 19:10:34.702   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f77e0 on port 0
08-03 19:10:34.702   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-03 19:10:34.702   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-03 19:10:34.702   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f1f0 on port 1
08-03 19:10:34.702   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-03 19:10:34.702   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 1
08-03 19:10:34.702   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-03 19:10:34.702   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 1
08-03 19:10:34.702   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-03 19:10:34.702   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7dd0 on port 1
08-03 19:10:34.702   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-03 19:10:34.702   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-03 19:10:34.702   310  2157 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-03 19:10:34.702   310  2157 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-03 19:10:34.702   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-03 19:10:34.702   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-03 19:10:34.702   310  8266 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-03 19:10:34.702   310  2157 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!,
,08-03 19:10:34.702   310  2157 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-03 19:10:34.702   310  2157 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-03 19:10:34.708   310  2157 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
,08-03 19:10:34.710   310  2157 D AudioPlayer: AudioPlayer releasing audio source
08-03 19:10:34.710   310  2157 D AudioPlayer: AudioPlayer done releasing audio source
08-03 19:10:34.710   310  2157 V AwesomePlayer: reset_l() 
08-03 19:10:34.710   310  2157 V AwesomePlayer: cancelPlayerEvents
08-03 19:10:34.710   310  2157 V AwesomePlayer: ~AwesomePlayer call
08-03 19:10:34.711   310  2157 V AwesomePlayer: reset_l() 
08-03 19:10:34.711   310  2157 V AwesomePlayer: cancelPlayerEvents
08-03 19:10:34.711  8224  8263 V SoundPool: close(32)
08-03 19:10:34.711  8224  8263 V SoundPool: pointer = 0x9fffe000, size = 205080, sampleRate = 48000, numChannels = 2
08-03 19:10:34.722  8224  8224 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-03 19:10:34.723  8224  8224 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,08-03 19:10:34.726  8224  8224 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:1741
,08-03 19:10:34.730  8156  8156 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 19:10:34.763  8156  8156 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-03 19:10:34.767  8156  8156 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-03 19:10:34.771  8156  8156 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 19:10:34.775  8156  8156 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 19:10:34.781  8156  8156 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-03 19:10:34.787  8156  8156 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 19:10:34.791  8156  8156 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 19:10:34.795  8156  8156 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-03 19:10:34.799  8156  8156 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-03 19:10:34.965  7639  7639 I UEI.SmartControl: Supports setup maps: true
08-03 19:10:34.968  7639  7639 D UEI.SmartControl: QS start statue = true Error code = 0
08-03 19:10:34.968  7639  7639 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-03 19:10:34.968  7639  7639 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-03 19:10:34.968  7639  7639 I UEI.SmartControl: ### init IR Blaster...
,08-03 19:10:34.972  7639  7639 D serial_port: Configuring serial port
08-03 19:10:34.972  7639  7639 E UEI.SmartControl: UEIBLaster setting for 616
08-03 19:10:34.972  7639  7639 I UEI.SmartControl: Setting serial record hearder size = 2
08-03 19:10:34.973  7639  7639 I UEI.SmartControl: configuring settings for MAXQ616
08-03 19:10:34.973  7639  7639 I UEI.SmartControl: Get version...
08-03 19:10:34.991  7639  8275 D UEI.SmartControl: serial port data available: 21
,08-03 19:10:35.018  7639  7639 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-03 19:10:35.019  7639  7639 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-03 19:10:35.019  7639  7639 I UEI.SmartControl: QS saving settings...
,08-03 19:10:35.021  7639  7639 D UEI.SmartControl: IR Blaster version: 25672567
,08-03 19:10:35.038  7639  8275 D UEI.SmartControl: serial port data available: 4
,08-03 19:10:35.069  7639  8281 I UEI.SmartControl: Device manager: loading config....
,08-03 19:10:35.069  7639  8281 D UEI.SmartControl: ----------- loading internal config...
,08-03 19:10:35.071  7639  7639 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-03 19:10:35.075  7639  7639 E UEI.SmartControl: Services init done
08-03 19:10:35.076  7639  7639 D UEI.SmartControl: QS Service init finished
08-03 19:10:35.079  7639  8281 E UEI.SmartControl: Loading SETTINGS...
08-03 19:10:35.079  7639  7639 D UEI.SmartControl: QS Service version name: 2.1.91
08-03 19:10:35.079  7639  7639 D UEI.SmartControl: QS Service version code: 201091
08-03 19:10:35.080  7639  7639 D UEI.SmartControl: Service requested: Control
08-03 19:10:35.083  8224  8224 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-03 19:10:35.083  7639  7639 D UEI.SmartControl: Internal service binding...
08-03 19:10:35.084  7639  7654 I UEI.SmartControl: ------ IControl API: 11
08-03 19:10:35.084  7639  7654 D UEI.SmartControl: File observer start...
08-03 19:10:35.085  7639  7654 E UEI.SmartControl: IR Port is disabled: false
08-03 19:10:35.085  7639  7654 D UEI.SmartControl: Starting file observer...
08-03 19:10:35.085  7639  7654 I UEI.SmartControl: Registering callback...
,08-03 19:10:35.086  7639  7655 I UEI.SmartControl: ------ IControl API: 19
08-03 19:10:35.086  7639  7655 I UEI.SmartControl: Registering Services Ready callback...
08-03 19:10:35.088  7639  8281 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-03 19:10:35.108  7639  8280 I UEI.SmartControl: Notify AllClients services are ready: 0
08-03 19:10:35.110  8224  8240 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,08-03 19:10:35.110  7639  8280 D UEI.SmartControl: -----service ready thread exits
08-03 19:10:35.110  8224  8261 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-03 19:10:35.110  8224  8261 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-03 19:10:35.111  8224  8224 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-03 19:10:35.111  8224  8224 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-03 19:10:35.112  7639  7690 I UEI.SmartControl: ------ IControl API: 8
08-03 19:10:35.114  8224  8224 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-03 19:10:35.114  8224  8224 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-03 19:10:35.114  8224  8224 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-03 19:10:35.114  8224  8224 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-03 19:10:35.116  8224  8224 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-03 19:10:35.116  8224  8224 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-03 19:10:35.117  8224  8224 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-03 19:10:35.120  8224  8224 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-03 19:10:35.121  8224  8224 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-03 19:10:35.123  8224  8224 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-03 19:10:35.124  8224  8224 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-03 19:10:35.126  8224  8224 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-03 19:10:35.128  8224  8224 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-03 19:10:35.129  8224  8224 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-03 19:10:35.131  8224  8224 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1470244235130]
08-03 19:10:35.134  8224  8224 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-03 19:10:35.137  1031  1975 I ActivityManager: Killing 7293:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
,08-03 19:10:35.164  8224  8283 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-03 19:10:35.195  1031  2010 W libprocessgroup: failed to open /acct/uid_10005/pid_7293/cgroup.procs: No such file or directory
,08-03 19:10:35.205  8224  8224 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-03 19:10:35.206  8224  8224 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-03 19:10:35.207  8224  8224 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-03 19:10:35.207  8224  8224 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-03 19:10:35.207  8224  8224 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-03 19:10:35.208  8224  8224 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-03 19:10:35.208  8224  8224 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-03 19:10:35.221  8224  8224 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-03 19:10:36.204  1031  1537 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=68.0, 0.0, 0.0  rx=60.5 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:1365420972] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-03 19:10:36.207  1031  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=68.0, 0.0, 0.0  rx=60.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1365420975] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-03 19:10:36.207  1031  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-03 19:10:36.224  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-03 19:10:36.269  1031  1538 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-03 19:10:36.293  1031  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-03 19:10:36.298  1031  1095 D Tethering: MasterInitialState.processMessage what=3
,08-03 19:10:36.314  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:10:36.314  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:10:36.314  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:10:36.314  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:10:36.314  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:10:36.314  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 19:10:36.314  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 19:10:36.314  6643  6643 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 19:10:36.320  6643  6643 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-03 19:10:36.329  1031  1089 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-03 19:10:36.337  8156  8156 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-03 19:10:36.346  5790  5790 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-03 19:10:36.362  2195  2195 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-03 19:10:36.376  7097  7097 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-03 19:10:36.376  7097  7097 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-03 19:10:36.376  7097  7097 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-03 19:10:36.376  7097  7097 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-03 19:10:36.382  7097  7097 I AppUp4:CustModeStarterReceiver: onReceive
08-03 19:10:36.386  7097  7097 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1fe2068d
08-03 19:10:36.386  7097  7097 D AppUp4:CustFacade: isCustomizationCompleted : false
08-03 19:10:36.386  7097  7097 D AppUp4:CustFacade: isPhone : true
08-03 19:10:36.386  7097  7097 D AppUp4:CustModeStarterReceiver: begin check event
08-03 19:10:36.386  7097  7097 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-03 19:10:36.392  8156  8211 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-03 19:10:36.401  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-03 19:10:36.401  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-03 19:10:36.403  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 19:10:36.408  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-03 19:10:36.415  2846  2846 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
08-03 19:10:36.427  2846  2846 V DownloadManager: DownloadService onCreate
,08-03 19:10:36.435  4297  8303 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-03 19:10:36.438  4297  8303 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
08-03 19:10:36.440  2846  8304 I DownloadManager: in removeSpuriousFiles
,08-03 19:10:36.446  2846  8304 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
08-03 19:10:36.449  4297  8307 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-03 19:10:36.450  4297  8307 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-03 19:10:36.451   305  8314 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-03 19:10:36.451   305  8314 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-03 19:10:36.453  6643  8190 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
08-03 19:10:36.453  6643  8190 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-03 19:10:36.454  6643  8190 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-03 19:10:36.454  6643  8190 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-03 19:10:36.454  6643  8190 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-03 19:10:36.458  2846  8304 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@25324ac6 on behalf of 2846
08-03 19:10:36.459  6643  8308 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
08-03 19:10:36.459  2846  8304 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
08-03 19:10:36.459  6643  8308 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-03 19:10:36.459  2846  8304 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
08-03 19:10:36.459  6643  8308 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-03 19:10:36.459  2846  8304 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
08-03 19:10:36.459  2846  8304 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
,08-03 19:10:36.459  2846  8304 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
08-03 19:10:36.459  2846  8304 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
08-03 19:10:36.459  1031  2040 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=8316 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-03 19:10:36.459  2846  8304 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
08-03 19:10:36.459  2846  8304 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
08-03 19:10:36.459  2846  8304 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
08-03 19:10:36.459  2846  8304 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
08-03 19:10:36.459  2846  8304 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
08-03 19:10:36.462  6643  8308 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-03 19:10:36.462  6643  8308 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-03 19:10:36.462  2846  2846 V DownloadManager: DownloadService onStartCommand
08-03 19:10:36.464  6643  8317 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 851, name: OutgoingSocketThread/Receiver)
08-03 19:10:36.464  6643  8324 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 852, name: IncomingSocketThread/Sender)
08-03 19:10:36.465  2846  8305 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
08-03 19:10:36.465  6643  8317 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 851, thread name: OutgoingSocketThread/Receiver)
08-03 19:10:36.466  6643  8315 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 850, name: OutgoingSocketThread/Sender)
08-03 19:10:36.467  1031  1089 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 19:10:36.468  6643  8325 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 853, name: IncomingSocketThread/Receiver)
08-03 19:10:36.468  6643  8325 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 853, thread name: IncomingSocketThread/Receiver)
08-03 19:10:36.468  6643  8325 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-03 19:10:36.469  6643  8325 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 853, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-03 19:10:36.469  6643  8317 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-03 19:10:36.470  6643  8317 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 851, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-03 19:10:36.472  2846  8304 I DownloadManager: in trimDatabase
08-03 19:10:36.473  2846  8304 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
08-03 19:10:36.474  2846  8305 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@252a6ddd on behalf of 2846
08-03 19:10:36.476  2846  8304 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@16784d52 on behalf of 2846
08-03 19:10:36.476  2846  8305 V DownloadManager: processing inserted download 1
08-03 19:10:36.481  2846  8305 V DownloadManager: processing inserted download 4
08-03 19:10:36.482  2846  8305 V DownloadManager: processing inserted download 7
08-03 19:10:36.484  2846  8305 V DownloadManager: processing inserted download 8
08-03 19:10:36.485  2846  8305 V DownloadManager: processing inserted download 9
08-03 19:10:36.486  2846  8305 V DownloadManager: processing inserted download 10
08-03 19:10:36.487  2846  8305 V DownloadManager: processing inserted download 11
08-03 19:10:36.488  2846  8305 V DownloadManager: processing inserted download 12
08-03 19:10:36.489  2846  8305 V DownloadManager: processing inserted download 13
08-03 19:10:36.490   305  8314 D libc-netbsd: res_queryN name = mtalk.google.com succeed
08-03 19:10:36.491  4297  8303 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
08-03 19:10:36.491  2846  8305 V DownloadManager: processing inserted download 14
08-03 19:10:36.492  2846  8305 V DownloadManager: processing inserted download 16
,08-03 19:10:36.496  4297  4297 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
08-03 19:10:36.497  4297  4297 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
08-03 19:10:36.497  4297  4297 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
08-03 19:10:36.499  4297  4297 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
08-03 19:10:36.502  4297  4297 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
08-03 19:10:36.505  2846  2846 V DownloadManager: DownloadService onDestroy
,08-03 19:10:36.521  8316  8316 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-03 19:10:36.522  8316  8316 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-03 19:10:36.523  8316  8316 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-03 19:10:36.524  8316  8316 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-03 19:10:36.597  8316  8316 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-03 19:10:36.610  8316  8316 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-03 19:10:36.672  8316  8316 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-03 19:10:36.709  8316  8316 D LgDataFeature: LgDataFeature() Constructor: none
,08-03 19:10:36.709  8316  8316 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 19:10:36.824  2195  8340 D GCM     : Connected
,08-03 19:10:36.843  8316  8316 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-03 19:10:36.858  2195  8340 D GCM     : Message class com.google.e.a.a.q
,08-03 19:10:36.876  8316  8316 I HubEmail: JNI_OnLoad()
08-03 19:10:36.876  8316  8316 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-03 19:10:36.876  8316  8316 I HubEmail: registerNatives()
08-03 19:10:36.876  8316  8316 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-03 19:10:36.876  8316  8316 I HubEmail: registerNativeMethods()
,08-03 19:10:36.876  8316  8316 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-03 19:10:36.876  8316  8316 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,08-03 19:10:36.883  8316  8351 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:36.897  3487  3487 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-03 19:10:36.898  3487  3487 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-03 19:10:36.898  3487  3487 I LgeMiscReceiver: networkInfo.isConnected() = true
08-03 19:10:36.898  3487  3487 D PhoneState: setPdpRejectCasuse : false
,08-03 19:10:36.911   305  8357 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-03 19:10:36.911   305  8357 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
,08-03 19:10:36.931  1031  1046 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=8358 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-03 19:10:36.954   305  8357 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
,08-03 19:10:36.989  8086  8353 V FormManager: There are no updated forms. The schedule will be deleted.
,08-03 19:10:36.992  8086  8353 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
08-03 19:10:37.016  1031  1047 I ActivityManager: Killing 7750:com.google.android.talk/u0a72 (adj 15): empty #17
,08-03 19:10:37.024  8358  8358 D LgDataFeature: LgDataFeature() Constructor: none
08-03 19:10:37.024  8358  8358 D LgDataFeature: LgDataFeature() Constructor Done, null
08-03 19:10:37.027  8358  8358 D PhoneMonitor: Register our PhoneStateListener
,08-03 19:10:37.045  1031  1574 W libprocessgroup: failed to open /acct/uid_10072/pid_7750/cgroup.procs: No such file or directory
,08-03 19:10:37.057  8358  8358 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-03 19:10:37.062  8358  8358 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-03 19:10:37.090  8358  8358 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-03 19:10:37.091  8358  8358 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-03 19:10:37.092  8358  8358 D TelephonyAutoProfiling: [parse] Load xml
08-03 19:10:37.096  8358  8358 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,08-03 19:10:37.096  8358  8358 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-03 19:10:37.096  8358  8358 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-03 19:10:37.097  8358  8358 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-03 19:10:37.097  8358  8358 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-03 19:10:37.097  8358  8358 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-03 19:10:37.097  8358  8358 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-03 19:10:37.097  8358  8358 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-03 19:10:37.097  8358  8358 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-03 19:10:37.097  8358  8358 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-03 19:10:37.097  8358  8358 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-03 19:10:37.097  8358  8358 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-03 19:10:37.097  8358  8358 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-03 19:10:37.097  8358  8358 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-03 19:10:37.097  8358  8358 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-03 19:10:37.097  8358  8358 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-03 19:10:37.097  8358  8358 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-03 19:10:37.107  8358  8358 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,08-03 19:10:37.128  1031  1938 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=8383 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-03 19:10:37.130  1031  1938 I ActivityManager: Killing 7801:com.android.contacts/u0a19 (adj 15): empty #17
,08-03 19:10:37.209  1031  1725 W libprocessgroup: failed to open /acct/uid_10019/pid_7801/cgroup.procs: No such file or directory
,08-03 19:10:37.218  1815  8400 I CheckinService: active receiver: enabled
,08-03 19:10:37.232  1815  8400 I CheckinService: Preparing to send checkin request
08-03 19:10:37.232  1815  8400 I EventLogService: Accumulating logs since 1470244216285
08-03 19:10:37.282  1815  8400 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-03 19:10:37.410  1031  1918 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=8403 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-03 19:10:37.414  1031  1918 I ActivityManager: Killing 7824:com.android.gallery3d/u0a27 (adj 15): empty #17
08-03 19:10:37.485   305  8420 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-03 19:10:37.485   305  8420 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
,08-03 19:10:37.511  1031  1884 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8421 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-03 19:10:37.512  1031  2010 W libprocessgroup: failed to open /acct/uid_10027/pid_7824/cgroup.procs: No such file or directory
,08-03 19:10:37.519   305  8420 D libc-netbsd: res_queryN name = www.google.com succeed
08-03 19:10:37.524   305  8437 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-03 19:10:37.524   305  8437 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-03 19:10:37.525   305  8437 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-03 19:10:37.580  8421  8421 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-03 19:10:37.581  8421  8421 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-03 19:10:37.613  8421  8421 I MultiDex: VM with version 2.1.0 has multidex support
,08-03 19:10:37.613  8421  8421 I MultiDex: install
08-03 19:10:37.613  8421  8421 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-03 19:10:37.615  1031  1539 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,08-03 19:10:37.638  1031  1725 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=8441 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-03 19:10:37.640  1031  1725 I ActivityManager: Killing 7843:com.android.vending/u0a44 (adj 15): empty #17
08-03 19:10:37.703  1031  2010 W libprocessgroup: failed to open /acct/uid_10044/pid_7843/cgroup.procs: No such file or directory
,08-03 19:10:37.727  8421  8421 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-03 19:10:37.770  8441  8441 I art     : Almond Protected OAT
,08-03 19:10:37.831  8441  8441 D WeatherApplication: removeAccount
08-03 19:10:37.833  8441  8441 D WeatherApplication: Account.length = 0
08-03 19:10:37.833  8441  8441 E WeatherApplication: OPERATOR:OPEN
,08-03 19:10:37.839  8441  8441 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:10:37
,08-03 19:10:37.843  8441  8441 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-03 19:10:37.843  8441  8441 D Weather.Utils: 2 : All the weather widget is gone.
,08-03 19:10:37.845  8441  8441 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-03 19:10:37.848  8441  8441 D WeatherAncestor: connectivity changed - connection : true
08-03 19:10:37.849  8441  8441 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,08-03 19:10:37.863  8441  8441 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-03 19:10:37.863  8441  8441 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-03 19:10:37.863  8441  8441 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-03 19:10:37.886  8441  8441 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,08-03 19:10:37.886  8441  8441 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:10:37
08-03 19:10:37.957  1031  1975 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8459 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-03 19:10:37.958  1031  1975 I ActivityManager: Killing 7886:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-03 19:10:37.977   342   342 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 451us total 26.321ms
08-03 19:10:38.000   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 448us total 21.569ms
,08-03 19:10:38.022   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 443us total 21.065ms
,08-03 19:10:38.110  1031  2040 W libprocessgroup: failed to open /acct/uid_10080/pid_7886/cgroup.procs: No such file or directory
08-03 19:10:38.176  8421  8439 D LgDataFeature: LgDataFeature() Constructor: none
08-03 19:10:38.177  8421  8439 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 19:10:38.191   278   364 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-03 19:10:38.192   278   364 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-03 19:10:38.192   278   364 W Vold    : Returning OperationFailed - no handler for errno 0
08-03 19:10:38.192  8459  8482 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-03 19:10:38.193   278   364 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-03 19:10:38.193   278   364 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-03 19:10:38.193   278   364 W Vold    : Returning OperationFailed - no handler for errno 0
08-03 19:10:38.194  8459  8482 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-03 19:10:38.210   278   364 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-03 19:10:38.210   278   364 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-03 19:10:38.210   278   364 W Vold    : Returning OperationFailed - no handler for errno 0
,08-03 19:10:38.211  8459  8486 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-03 19:10:38.214   278   364 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-03 19:10:38.214   278   364 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-03 19:10:38.214   278   364 W Vold    : Returning OperationFailed - no handler for errno 0
08-03 19:10:38.215  8459  8486 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-03 19:10:38.248  8487  8487 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-03 19:10:38.305  8487  8487 I dex2oat : dex2oat took 56.094ms (threads: 4)
08-03 19:10:38.317  8421  8439 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-03 19:10:38.317  8421  8439 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-03 19:10:38.317  8421  8439 I Adreno-EGL: Build Date: 12/12/14 금
08-03 19:10:38.317  8421  8439 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-03 19:10:38.317  8421  8439 I Adreno-EGL: Remote Branch: 
08-03 19:10:38.317  8421  8439 I Adreno-EGL: Local Patches: 
08-03 19:10:38.317  8421  8439 I Adreno-EGL: Reconstruct Branch: 
,08-03 19:10:38.403  1031  2010 I art     : Explicit concurrent mark sweep GC freed 77817(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 1.488ms total 104.329ms
,08-03 19:10:38.451  8459  8459 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-03 19:10:38.459  8459  8459 I LibraryLoader: Loading: webviewchromium
08-03 19:10:38.461  8459  8459 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 938-941)
08-03 19:10:38.461  8459  8459 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-03 19:10:38.466  8459  8459 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2e8dcaec}
08-03 19:10:38.467  8459  8459 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-03 19:10:38.467  8459  8459 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-03 19:10:38.479  8459  8459 I BrowserStartupController: Initializing chromium process, renderers=0
08-03 19:10:38.480  8459  8459 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-03 19:10:38.488  8459  8459 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-03 19:10:38.489  8459  8459 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-03 19:10:38.489  8459  8459 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-03 19:10:38.491   310   310 V AudioPolicyService: registerClient() client 0xb1019200, uid 10093
08-03 19:10:38.492  8459  8514 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-03 19:10:38.504  8459  8459 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-03 19:10:38.504  8459  8459 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-03 19:10:38.504  8459  8459 I Adreno-EGL: Build Date: 12/12/14 금
08-03 19:10:38.504  8459  8459 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-03 19:10:38.504  8459  8459 I Adreno-EGL: Remote Branch: 
08-03 19:10:38.504  8459  8459 I Adreno-EGL: Local Patches: 
08-03 19:10:38.504  8459  8459 I Adreno-EGL: Reconstruct Branch: 
,08-03 19:10:38.584  8459  8459 I NSApplication: Starting up...
,08-03 19:10:38.610  8421  8439 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-03 19:10:38.610  8421  8439 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-03 19:10:38.610  8421  8439 I Adreno-EGL: Build Date: 12/12/14 금
08-03 19:10:38.610  8421  8439 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-03 19:10:38.610  8421  8439 I Adreno-EGL: Remote Branch: 
08-03 19:10:38.610  8421  8439 I Adreno-EGL: Local Patches: 
08-03 19:10:38.610  8421  8439 I Adreno-EGL: Reconstruct Branch: 
,08-03 19:10:38.639  1031  1574 I ActivityManager: Killing 7508:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-03 19:10:38.666  8421  8439 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-03 19:10:38.666  8421  8439 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-03 19:10:38.666  8421  8439 I Adreno-EGL: Build Date: 12/12/14 금
08-03 19:10:38.666  8421  8439 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-03 19:10:38.666  8421  8439 I Adreno-EGL: Remote Branch: 
08-03 19:10:38.666  8421  8439 I Adreno-EGL: Local Patches: 
08-03 19:10:38.666  8421  8439 I Adreno-EGL: Reconstruct Branch: 
,08-03 19:10:38.728  1031  2040 W libprocessgroup: failed to open /acct/uid_10037/pid_7508/cgroup.procs: No such file or directory
,08-03 19:10:38.776  2195  2195 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-03 19:10:38.786   305  8529 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-03 19:10:38.787   305  8529 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-03 19:10:38.799  2195  2195 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-03 19:10:38.799  2195  2195 D c       : Getting all permits...
08-03 19:10:38.799  2195  2195 D a       : Opening database...
,08-03 19:10:38.808  2195  2195 D a       : Opening database auth.proximity.permit_store...
,08-03 19:10:38.810  2195  2195 D a       : Closing database...
,08-03 19:10:39.234  1031  1537 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=39.0, 0.0, 0.0  rx=33.8 bcn=0 [on:0 tx:0 rx:0 period:3008] from screen [on:0 period:1365424002] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-03 19:10:39.238  1031  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=39.0, 0.0, 0.0  rx=33.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1365424005] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-03 19:10:39.238  1031  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-03 19:10:39.458  6643  6774 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-03 19:10:39.465  6643  6774 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-03 19:10:39.467  6643  6774 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@28ad7ca7 Bundle[{}]
08-03 19:10:39.468  6643  6774 I io.jxcore.node.LifeCycleMonitor: start: OK
08-03 19:10:39.469  6643  6774 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-03 19:10:39.469  6643  6774 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-03 19:10:39.470  6643  6774 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-03 19:10:39.471  6643  6774 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-03 19:10:39.472  6643  6774 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-03 19:10:39.478  6643  6774 I System.out: Running OutgoingSocketThread
08-03 19:10:39.481  6643  8541 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
08-03 19:10:39.481  6643  8541 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-03 19:10:39.743  8224  8224 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,08-03 19:10:39.745  8224  8224 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:1741
,08-03 19:10:39.756  8224  8224 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,08-03 19:10:39.756  8224  8224 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:1741
,08-03 19:10:40.069  7639  8282 D UEI.SmartControl: Internal timer expired: 2
,08-03 19:10:40.069  7639  8282 D UEI.SmartControl: unbind internal service
,08-03 19:10:40.236  7639  8279 D serial_port: close(fd = 24)
,08-03 19:10:40.246  7639  8279 I UEI.SmartControl: Serial port is closed.
,08-03 19:10:40.300   305  8529 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-03 19:10:40.473  1815  8400 I CheckinTask: Sending checkin request (7829 bytes)
,08-03 19:10:40.701  1815  8400 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,08-03 19:10:40.718  1815  8400 I CheckinService: active receiver: disabled
,08-03 19:10:40.746  2195  2195 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-03 19:10:40.761  2195  2195 I GCM     : GCM config loaded
,08-03 19:10:40.779  8358  8358 V SetupWizard: Connected to Gservices successfully
,08-03 19:10:42.257  1031  1537 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=30.5, 0.0, 0.0  rx=25.9 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1365427025] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-03 19:10:42.258  1031  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=30.5, 0.0, 0.0  rx=25.9 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1365427026] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-03 19:10:42.258  1031  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-03 19:10:42.493  6643  8541 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,08-03 19:10:42.493  6643  8541 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,08-03 19:10:42.493  6643  8541 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-03 19:10:42.494  6643  8541 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-03 19:10:42.498  6643  8541 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-03 19:10:42.500  6643  8544 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
08-03 19:10:42.500  6643  8544 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-03 19:10:42.500  6643  8544 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-03 19:10:42.500  6643  8544 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-03 19:10:42.500  6643  8544 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-03 19:10:42.505  6643  8547 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 863, name: OutgoingSocketThread/Receiver)
08-03 19:10:42.506  6643  8547 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 863, thread name: OutgoingSocketThread/Receiver)
08-03 19:10:42.506  6643  8547 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-03 19:10:42.506  6643  8547 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 863, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-03 19:10:42.508  6643  8546 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 862, name: OutgoingSocketThread/Sender)
,08-03 19:10:42.513  6643  8549 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 865, name: IncomingSocketThread/Receiver)
,08-03 19:10:42.513  6643  8549 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 865, thread name: IncomingSocketThread/Receiver)
08-03 19:10:42.513  6643  8549 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-03 19:10:42.513  6643  8549 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 865, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-03 19:10:42.516  6643  8548 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 864, name: IncomingSocketThread/Sender)
08-03 19:10:43.207  8459  8484 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-03 19:10:43.728  1031  1047 I ActivityManager: Killing 6969:com.lge.settings.easy/1000 (adj 15): empty #17
,08-03 19:10:43.764  1031  1918 W libprocessgroup: failed to open /acct/uid_1000/pid_6969/cgroup.procs: No such file or directory
,08-03 19:10:45.282  1031  1537 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=21.8, 0.0, 0.0  rx=17.9 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:1365430049] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-03 19:10:45.285  1031  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=21.8, 0.0, 0.0  rx=17.9 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1365430053] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-03 19:10:45.285  1031  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-03 19:10:45.503  6643  6774 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 874)
,08-03 19:10:45.504  6643  6774 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-03 19:10:45.504  6643  6774 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 875)
08-03 19:10:45.508  6643  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 19:10:45.508  6643  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ffd9ee3 added. We now have 2 listener(s)
,08-03 19:10:45.512  1031  1986 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:10:45.515  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 19:10:45.515  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 19:10:45.515  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 19:10:45.515  6643  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 19:10:45.515  6643  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bf800e0 added. We now have 9 listener(s)
08-03 19:10:45.515  6643  6774 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 19:10:45.516  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-03 19:10:45.519  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 19:10:45.523  6643  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 19:10:45.523  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:10:45.523  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:10:45.523  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:10:45.523  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:10:45.523  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 19:10:45.523  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 19:10:45.523  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 19:10:45.528  6643  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 19:10:45.529  6643  6774 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 19:10:45.531  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:10:45.533  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:10:45.533  6643  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 19:10:45.533  6643  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adb325e added. We now have 3 listener(s)
08-03 19:10:45.533  1031  1943 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:10:45.536  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 19:10:45.536  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 19:10:45.536  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 19:10:45.536  6643  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 19:10:45.536  6643  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b61463f added. We now have 10 listener(s)
08-03 19:10:45.536  6643  6774 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 19:10:45.536  6643  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:10:45.537  6643  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:10:45.537  6643  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-03 19:10:45.542  6643  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:10:45.542  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:45.542  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 19:10:45.542  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 19:10:45.542  6643  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ffd9ee3 removed from the list
08-03 19:10:45.542  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:45.543  6643  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bf800e0 removed from the list
08-03 19:10:45.543  6643  6774 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:10:45.543  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:45.543  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:45.543  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:45.544  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:10:45.544  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:10:45.544  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:45.545  6643  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bf800e0 not in the list
08-03 19:10:45.545  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:45.545  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:45.546  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:10:45.546  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:10:45.546  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:45.546  6643  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b61463f removed from the list
08-03 19:10:45.546  6643  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:10:45.546  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:45.546  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:45.546  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 19:10:45.546  6643  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adb325e removed from the list
08-03 19:10:45.547  6643  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 19:10:45.547  6643  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f8c4b0c added. We now have 2 listener(s)
08-03 19:10:45.547  1031  1918 D BluetoothManagerService: checkIfCalle,rIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:10:45.550  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 19:10:45.550  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 19:10:45.550  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-03 19:10:45.554  6643  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 19:10:45.554  6643  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24e1cc55 added. We now have 9 listener(s)
08-03 19:10:45.554  6643  6774 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 19:10:45.557  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-03 19:10:45.560  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 19:10:45.563  6643  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 19:10:45.563  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:10:45.563  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:10:45.563  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:10:45.563  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:10:45.563  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 19:10:45.563  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 19:10:45.563  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 19:10:45.567  6643  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 19:10:45.567  6643  6774 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 19:10:45.570  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:10:45.572  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:10:45.572  6643  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 19:10:45.573  6643  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e075b added. We now have 3 listener(s)
08-03 19:10:45.573  1031  2040 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:10:45.575  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 19:10:45.575  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 19:10:45.575  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 19:10:45.576  6643  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 19:10:45.576  6643  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12390bf8 added. We now have 10 listener(s)
08-03 19:10:45.576  6643  6774 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 19:10:45.576  6643  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 19:10:45.576  6643  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-03 19:10:45.576  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-03 19:10:45.576  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 19:10:45.576  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-03 19:10:45.583  6643  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-03 19:10:45.584  1031  1941 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:10:45.588  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-03 19:10:45.591  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-03 19:10:45.592  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-03 19:10:45.593  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 19:10:45.594  6643  6774 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-03 19:10:45.595  6643  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:10:45.596  6643  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:10:45.598  6643  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:10:45.598  6643  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:10:45.598  6643  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:10:45.598  6643  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:10:45.598  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:45.598  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 19:10:45.598  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 19:10:45.598  6643  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f8c4b0c removed from the list
08-03 19:10:45.598  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:45.598  6643  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24e1cc55 removed from the list
08-03 19:10:45.598  6643  6774 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:10:45.598  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:45.599  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:45.599  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:45.600  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:10:45.600  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:10:45.600  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:45.600  6643  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24e1cc55 not in the list
08-03 19:10:45.600  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:45.600  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 19:10:45.604  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:10:45.605  6643  6774 D BluetoothLeScanner: could not find callback wrapper
08-03 19:10:45.605  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 19:10:45.605  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:10:45.605  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:45.605  6643  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12390bf8 removed from the list
08-03 19:10:45.605  6643  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:10:45.605  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:45.605  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:45.605  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 19:10:45.605  6643  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e075b removed from the list
08-03 19:10:45.606  6643  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 19:10:45.606  6643  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@63bbe37 added. We now have 2 listener(s)
08-03 19:10:45.607  1031  1975 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:10:45.611  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 19:10:45.611  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 19:10:45.611  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 19:10:45.611  6643  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 19:10:45.611  6643  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30eeefa4 added. We now have 9 listener(s)
08-03 19:10:45.611  6643  6774 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 19:10:45.612  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-03 19:10:45.618  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 19:10:45.621  6643  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 19:10:45.621  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:10:45.621  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:10:45.621  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:10:45.621  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:10:45.621  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 19:10:45.621  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 19:10:45.621  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 19:10:45.624  6643  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 19:10:45.624  6643  6774 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-03 19:10:45.627  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:10:45.629  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:10:45.629  6643  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 19:10:45.629  6643  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fcd08c2 added. We now have 3 listener(s)
08-03 19:10:45.629  1031  1941 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:10:45.632  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 19:10:45.632  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 19:10:45.632  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 19:10:45.632  6643  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 19:10:45.632  6643  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b0406d3 added. We now have 10 listener(s)
08-03 19:10:45.632  6643  6774 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 19:10:45.632  6643  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 19:10:45.633  6643  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 19:10:45.633  6643  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-03 19:10:45.633  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-03 19:10:45.633  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 19:10:45.633  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-03 19:10:45.637  6643  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-03 19:10:45.645  1031  1046 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-03 19:10:45.657  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-03 19:10:45.662  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-03 19:10:45.665  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-03 19:10:45.670  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 19:10:45.672  6643  6774 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-03 19:10:45.675  6643  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-03 19:10:45.675  6643  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-03 19:10:45.675  6643  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:10:45.675  6643  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:10:45.675  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:45.675  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 19:10:45.675  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 19:10:45.676  6643  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@63bbe37 removed from the list
08-03 19:10:45.676  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:45.676  6643  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30eeefa4 removed from the list
08-03 19:10:45.676  6643  6774 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:10:45.676  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:45.676  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:45.676  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:45.677  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:10:45.677  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:10:45.677  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:45.677  6643  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30eeefa4 not in the list
08-03 19:10:45.677  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:45.677  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:45.678  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:10:45.679  6643  6774 D BluetoothLeScanner: could not find callback wrapper
08-03 19:10:45.679  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 19:10:45.679  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:10:45.679  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:45.679  6643  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b0406d3 removed from the list
08-03 19:10:45.679  6643  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:10:45.679  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:45.679  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:45.679  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 19:10:45.679  6643  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fcd08c2 removed from the list
08-03 19:10:4,5.680  6643  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 19:10:45.680  6643  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ae6ef0e added. We now have 2 listener(s)
08-03 19:10:45.680  1031  1884 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:10:45.683  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 19:10:45.683  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 19:10:45.683  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 19:10:45.683  6643  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 19:10:45.683  6643  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13fe3d2f added. We now have 9 listener(s)
08-03 19:10:45.683  6643  6774 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 19:10:45.683  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-03 19:10:45.687  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 19:10:45.691  6643  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 19:10:45.691  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:10:45.691  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:10:45.691  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:10:45.691  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:10:45.691  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 19:10:45.691  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 19:10:45.691  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 19:10:45.693  6643  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 19:10:45.693  6643  6774 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 19:10:45.695  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:10:45.697  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:10:45.697  6643  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 19:10:45.697  6643  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@daf74c5 added. We now have 3 listener(s)
08-03 19:10:45.697  1031  1918 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:10:45.700  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 19:10:45.701  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 19:10:45.701  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 19:10:45.701  6643  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 19:10:45.701  6643  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ea6ee1a added. We now have 10 listener(s)
08-03 19:10:45.701  6643  6774 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 19:10:45.701  6643  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 19:10:45.701  6643  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-03 19:10:45.701  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-03 19:10:45.701  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 19:10:45.701  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-03 19:10:45.705  6643  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-03 19:10:45.706  1031  1975 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:10:45.710  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-03 19:10:45.711  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-03 19:10:45.712  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-03 19:10:45.713  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 19:10:45.715  6643  6774 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-03 19:10:45.717  6643  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:10:45.717  6643  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:10:45.717  6643  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:10:45.717  6643  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:10:45.717  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:45.717  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 19:10:45.717  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 19:10:45.717  6643  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ae6ef0e removed from the list
08-03 19:10:45.717  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:45.717  6643  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13fe3d2f removed from the list
08-03 19:10:45.717  6643  6774 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:10:45.717  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:45.718  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:45.718  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:45.719  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:10:45.719  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:10:45.719  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:45.719  6643  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13fe3d2f not in the list
08-03 19:10:45.719  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:45.719  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 19:10:45.720  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:10:45.721  6643  6774 D BluetoothLeScanner: could not find callback wrapper
08-03 19:10:45.721  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 19:10:45.721  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:10:45.721  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:45.721  6643  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ea6ee1a removed from the list
08-03 19:10:45.721  6643  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:10:45.721  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:45.721  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:45.721  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 19:10:45.721  6643  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@daf74c5 removed from the list
08-03 19:10:45.722  6643  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 19:10:45.722  6643  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c979841 added. We now have 2 listener(s)
08-03 19:10:45.723  1031  1725 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:10:45.725  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 19:10:45.725  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 19:10:45.725  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 19:10:45.726  6643  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 19:10:45.726  6643  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3035d1e6 added. We now have 9 listener(s)
08-03 19:10:45.726  6643  6774 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 19:10:45.726  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-03 19:10:45.729  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 19:10:45.733  6643  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 19:10:45.733  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:10:45.733  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 19:10:45.733  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:10:45.733  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:10:45.733  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 19:10:45.733  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 19:10:45.733  6643  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 19:10:45.735  6643  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 19:10:45.735  6643  6774 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 19:10:45.737  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:10:45.738  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:10:45.739  6643  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 19:10:45.739  6643  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19bf89d4 added. We now have 3 listener(s)
08-03 19:10:45.739  1031  1975 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 19:10:45.744  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 19:10:45.744  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 19:10:45.745  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 19:10:45.745  6643  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 19:10:45.745  6643  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84777d added. We now have 10 listener(s)
08-03 19:10:45.745  6643  6774 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 19:10:45.746  6643  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:10:45.747  6643  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:10:45.747  6643  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:10:45.747  6643  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:10:45.747  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:45.747  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 19:10:45.747  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 19:10:45.747  6643  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c979841 removed from the list
08-03 19:10:45.747  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:45.747  6643  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3035d1e6 removed from the list
08-03 19:10:45.747  6643  6774 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:10:45.748  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:45.748  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:45.749  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:45.751  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:10:45.751  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:10:45.751  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:45.751  6643  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3035d1e6 not in the list
08-03 19:10:45.751  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:45.751  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:45.752  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:10:45.752  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-03 19:10:45.752  6643  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:10:45.752  6643  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84777d removed from the list
08-03 19:10:45.752  6643  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:10:45.752  6643  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:10:45.752  6643  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:10:45.752  6643  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-03 19:10:45.752  6643  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19bf89d4 removed from the list
08-03 19:10:45.754  6643  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-03 19:10:45.754  6643  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-03 19:10:45.754  6643  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-03 19:10:45.754  6643  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 19:10:45.754  6643  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-03 19:10:45.755  6643  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-03 19:10:45.768  6643  8564 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 883, name: My test thread name)
,08-03 19:10:45.868  1602  1602 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-03 19:10:45.868  1602  1602 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-03 19:10:45.884  1031  1542 D WifiController: battery changed pluggedType: 2
,08-03 19:10:45.884  1602  1602 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 294
,08-03 19:10:45.884  1602  1602 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-03 19:10:45.886  1939  2093 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-03 19:10:45.886  1939  2093 D LEDHandler: Battery Level Remaining: 100%
08-03 19:10:45.886  1939  2093 D LEDHandler: Battery Temp: 294, mChargingStatus=5, mChargingStop=false
,08-03 19:10:45.891  1602  1602 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,08-03 19:10:45.899  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:45.899  7722  7950 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-03 19:10:45.899  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:45.900  8135  8135 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-03 19:10:47.308  1602  1602 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-03 19:10:47.332  1031  1427 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-03 19:10:47.405  1031  1031 D administrator: Handling package changes for user 0
,08-03 19:10:47.411   342   342 I art     : Background concurrent mark sweep GC freed 84(3KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 11.398ms total 46.346ms
08-03 19:10:47.448  1031  1090 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=8571 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
08-03 19:10:47.454  1602  1602 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-03 19:10:47.456  1602  1602 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,08-03 19:10:47.463  2031  2031 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-03 19:10:47.468  2031  2031 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-03 19:10:47.515  8571  8571 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-03 19:10:47.544  1031  1031 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-03 19:10:47.544  1031  1031 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-03 19:10:47.605  8571  8571 D LgDataFeature: LgDataFeature() Constructor: none
08-03 19:10:47.605  8571  8571 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 19:10:47.610  1031  1089 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-03 19:10:47.616  1031  1089 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-03 19:10:47.624  2031  2031 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-03 19:10:47.625  2504  2504 V GmsNetworkLocationProvi: DISABLE
,08-03 19:10:47.650  2504  2504 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-03 19:10:47.681  2195  2210 I art     : Explicit concurrent mark sweep GC freed 7043(436KB) AllocSpace objects, 4(64KB) LOS objects, 52% free, 29MB/61MB, paused 1.225ms total 22.062ms
08-03 19:10:47.683  1031  1089 D LocationProviderProxy: applying state to connected service
,08-03 19:10:47.747  8571  8616 I Babel   : MmsConfig: mnc/mcc: 0/0
08-03 19:10:47.747  8571  8616 I Babel   : MmsConfig.loadMmsSettings
,08-03 19:10:47.751  8571  8616 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-03 19:10:47.751  8571  8616 I Babel   : MmsConfig.loadFromDatabase
08-03 19:10:47.765  6643  6774 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 883
08-03 19:10:47.765  6643  6774 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 883, name: My test thread name)
08-03 19:10:47.767  6643  8618 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 884, name: My test thread name)
08-03 19:10:47.768  6643  8618 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 884, thread name: My test thread name)
08-03 19:10:47.768  6643  8618 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 884, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,08-03 19:10:47.769  6643  6774 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-03 19:10:47.773  6643  8619 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 888, name: My test thread name)
08-03 19:10:47.774  6643  8619 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 888, thread name: My test thread name): Test exception.
08-03 19:10:47.774  6643  8619 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 888, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
08-03 19:10:47.775  6643  6774 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 82
08-03 19:10:47.776  6643  6774 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 82
08-03 19:10:47.776  6643  6774 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-03 19:10:47.776  6643  6774 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-03 19:10:47.776  6643  6774 D com.test.thalitest.ThaliTestRunner: Total duration: 36916 ms
08-03 19:10:47.777  6643  6774 I jxcore-log: Total number of executed tests:  82
08-03 19:10:47.777  6643  6774 I jxcore-log: 
08-03 19:10:47.777  6643  6774 I jxcore-log: Number of passed tests:  82
08-03 19:10:47.777  6643  6774 I jxcore-log: 
08-03 19:10:47.777  6643  6774 I jxcore-log: Number of failed tests:  0
08-03 19:10:47.777  6643  6774 I jxcore-log: 
08-03 19:10:47.777  6643  6774 I jxcore-log: Number of ignored tests:  0
08-03 19:10:47.777  6643  6774 I jxcore-log: 
08-03 19:10:47.778  6643  6774 I jxcore-log: Total duration:  36916
08-03 19:10:47.778  6643  6774 I jxcore-log: 
08-03 19:10:47.780  6643  6774 I jxcore-log: Unit Test app is loaded
08-03 19:10:47.780  6643  6774 I jxcore-log: 
,08-03 19:10:47.787  6643  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 19:10:47.787  6643  6774 I jxcore-log: 
08-03 19:10:47.790  8571  8616 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-03 19:10:47.790  8571  8616 I Babel   : MmsConfig.loadFromResources
08-03 19:10:47.791  8571  8616 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-03 19:10:47.792  8571  8616 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-03 19:10:47.796  6643  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 19:10:47.796  6643  6774 I jxcore-log: 
08-03 19:10:47.797  6643  6643 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-03 19:10:47.800  6643  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 19:10:47.800  6643  6774 I jxcore-log: 
,08-03 19:10:47.803  6643  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 19:10:47.803  6643  6774 I jxcore-log: 
08-03 19:10:47.806  6643  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 19:10:47.806  6643  6774 I jxcore-log: 
08-03 19:10:47.810  8571  8571 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:10:47.810  6643  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-03 19:10:47.810  6643  6774 I jxcore-log: 
08-03 19:10:47.813  8571  8615 W AudioCapabilities: Unsupported mime audio/evrc
08-03 19:10:47.813  6643  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-03 19:10:47.813  6643  6774 I jxcore-log: 
08-03 19:10:47.814  8571  8615 W AudioCapabilities: Unsupported mime audio/qcelp
,08-03 19:10:47.815  8571  8615 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-03 19:10:47.815  6643  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 19:10:47.815  6643  6774 I jxcore-log: 
08-03 19:10:47.816  6643  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 19:10:47.816  6643  6774 I jxcore-log: 
08-03 19:10:47.817  6643  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 19:10:47.817  6643  6774 I jxcore-log: 
,08-03 19:10:47.819  6643  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-03 19:10:47.819  6643  6774 I jxcore-log: 
08-03 19:10:47.820  6643  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-03 19:10:47.820  6643  6774 I jxcore-log: 
08-03 19:10:47.821  6643  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-03 19:10:47.821  6643  6774 I jxcore-log: 
08-03 19:10:47.822  6643  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 19:10:47.822  6643  6774 I jxcore-log: 
08-03 19:10:47.823  6643  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 19:10:47.823  6643  6774 I jxcore-log: 
08-03 19:10:47.824  6643  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-03 19:10:47.824  6643  6774 I jxcore-log: 
08-03 19:10:47.825  6643  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-03 19:10:47.825  6643  6774 I jxcore-log: 
08-03 19:10:47.825  8571  8615 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-03 19:10:47.826  6643  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 19:10:47.826  6643  6774 I jxcore-log: 
08-03 19:10:47.826  8571  8615 W AudioCapabilities: Unsupported mime audio/qcelp
08-03 19:10:47.826  6643  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 19:10:47.826  6643  6774 I jxcore-log: 
08-03 19:10:47.826  8571  8615 W AudioCapabilities: Unsupported mime audio/evrc
08-03 19:10:47.827  6643  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-03 19:10:47.827  6643  6774 I jxcore-log: 
08-03 19:10:47.828  6643  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-03 19:10:47.828  6643  6774 I jxcore-log: 
08-03 19:10:47.829  6643  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-03 19:10:47.829  6643  6774 I jxcore-log: 
08-03 19:10:47.829  6643  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 19:10:47.829  6643  6774 I jxcore-log: 
08-03 19:10:47.831  6643  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 19:10:47.831  6643  6774 I jxcore-log: 
,08-03 19:10:47.832  6643  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 19:10:47.832  6643  6774 I jxcore-log: 
08-03 19:10:47.833  6643  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 19:10:47.833  6643  6774 I jxcore-log: 
08-03 19:10:47.833  6643  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 19:10:47.833  6643  6774 I jxcore-log: 
08-03 19:10:47.834  6643  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 19:10:47.834  6643  6774 I jxcore-log: 
08-03 19:10:47.835  8571  8615 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-03 19:10:47.835  6643  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 19:10:47.835  6643  6774 I jxcore-log: 
08-03 19:10:47.838  8571  8615 W VideoCapabilities: Unsupported mime video/divx
08-03 19:10:47.838  6643  6774 I jxcore-log: My device name is: LGE-LG-D855
08-03 19:10:47.838  6643  6774 I jxcore-log: 
08-03 19:10:47.839  6643  6774 I jxcore-log: WARN testUtils: myNameCallback not set!
08-03 19:10:47.839  6643  6774 I jxcore-log: 
08-03 19:10:47.842  7097  7097 I AppUp4:CustModeStarterReceiver: onReceive
08-03 19:10:47.842  1815  8621 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-03 19:10:47.842  1815  8621 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,08-03 19:10:47.854  1815  4735 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-03 19:10:47.854  7097  7097 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1fe2068d
08-03 19:10:47.854  7097  7097 D AppUp4:CustFacade: isCustomizationCompleted : false
08-03 19:10:47.854  7097  7097 D AppUp4:CustFacade: isPhone : true
08-03 19:10:47.861  7097  7097 D AppUp4:CustModeStarterReceiver: begin check event
08-03 19:10:47.861  7097  7097 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-03 19:10:47.861  8571  8615 W VideoCapabilities: Unsupported mime video/divx311
,08-03 19:10:47.865  8571  8615 W VideoCapabilities: Unsupported mime video/divx4
08-03 19:10:47.869  8571  8615 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-03 19:10:47.875  6643  8564 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 883, name: My test thread name), during the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,08-03 19:10:47.880  8571  8615 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
08-03 19:10:47.883  8571  8615 W AudioCapabilities: Unsupported mime audio/eac3
08-03 19:10:47.884  8571  8615 W AudioCapabilities: Unsupported mime audio/ac3
08-03 19:10:47.885  8571  8615 W AudioCapabilities: Unsupported mime audio/g726
08-03 19:10:47.885  8571  8615 W AudioCapabilities: Unsupported mime audio/wma-voice
08-03 19:10:47.886  8571  8615 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-03 19:10:47.887  8571  8615 W AudioCapabilities: Unsupported mime audio/adpcm
,08-03 19:10:47.889  8571  8615 W VideoCapabilities: Unsupported mime video/theora
08-03 19:10:47.890  8571  8615 W VideoCapabilities: Unsupported mime video/mjpg
08-03 19:10:47.896  1031  1574 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8624 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-03 19:10:47.921  1031  2010 I ActivityManager: Killing 8135:com.lge.bnr/1000 (adj 15): empty #17
,08-03 19:10:48.156  1031  1574 W libprocessgroup: failed to open /acct/uid_1000/pid_8135/cgroup.procs: No such file or directory
08-03 19:10:48.183  8624  8624 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-03 19:10:48.184  8624  8624 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-03 19:10:48.186  8624  8624 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-03 19:10:48.187  8624  8624 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-03 19:10:48.187  8624  8624 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-03 19:10:48.248  8624  8624 I SystemConfig: BUILD Country: EU
08-03 19:10:48.249  8624  8624 I SystemConfig: BUILD Operator: OPEN
,08-03 19:10:48.295  1031  1918 I ActivityManager: Killing 8108:com.lge.sync/1000 (adj 15): empty #17
,08-03 19:10:48.309  1031  1537 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=11.4, 0.0, 0.0  rx=9.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1365433077] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-03 19:10:48.311  1031  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=11.4, 0.0, 0.0  rx=9.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:1365433079] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-03 19:10:48.312  1031  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-03 19:10:48.495  1031  1902 W libprocessgroup: failed to open /acct/uid_1000/pid_8108/cgroup.procs: No such file or directory
,08-03 19:10:48.520  8624  8645 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-03 19:10:48.520  8624  8645 I SystemConfig: existFile = false
08-03 19:10:48.521  8624  8645 I SystemConfig: canReadFile = false
08-03 19:10:48.521  8624  8645 I SystemConfig: systemFeature RCS result false
08-03 19:10:48.521  8624  8645 D SystemConfig: refreshRcsSupport() :false
,08-03 19:10:48.561  1031  1918 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8647 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-03 19:10:48.609  8647  8647 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-03 19:10:48.609  8647  8647 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-03 19:10:48.610  8647  8647 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-03 19:10:48.610  8647  8647 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-03 19:10:48.736  8647  8647 I AppConfig: Total System Memory = 2995761152
,08-03 19:10:48.748  8647  8647 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,08-03 19:10:48.812  1031  1938 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8666 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-03 19:10:48.817  1031  1938 I ActivityManager: Killing 6897:com.android.settings/1000 (adj 15): empty #17
,08-03 19:10:49.043  1031  1902 W libprocessgroup: failed to open /acct/uid_1000/pid_6897/cgroup.procs: No such file or directory
,08-03 19:10:49.245  8666  8666 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-03 19:10:49.321  8666  8666 D LgDataFeature: LgDataFeature() Constructor: none
08-03 19:10:49.322  8666  8666 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 19:10:49.380  8666  8666 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-03 19:10:49.400  8666  8666 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-03 19:10:49.401  8666  8666 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-03 19:10:49.416  8666  8666 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-03 19:10:49.416  8666  8666 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-03 19:10:49.442  1031  1884 I ActivityManager: Killing 8316:com.lge.email/u0a23 (adj 15): empty #17
,08-03 19:10:49.590  1031  1046 W libprocessgroup: failed to open /acct/uid_10023/pid_8316/cgroup.procs: No such file or directory
,08-03 19:10:49.609  4589  8713 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-03 19:10:49.654  1031  1902 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=8714 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-03 19:10:49.663  2846  5860 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-03 19:10:49.671  2846  5860 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3b9b2120 on behalf of 8666
,08-03 19:10:49.710  8666  8666 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-03 19:10:49.731  8666  8666 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-03 19:10:49.740  8714  8714 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
08-03 19:10:49.770  8714  8714 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-03 19:10:49.770  8714  8714 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-03 19:10:49.770  8714  8714 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-03 19:10:49.770  8714  8714 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-03 19:10:49.770  8714  8714 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-03 19:10:49.770  8714  8714 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-03 19:10:49.783  1031  1902 I ActivityManager: Killing 8086:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-03 19:10:49.906  1031  1046 W libprocessgroup: failed to open /acct/uid_10026/pid_8086/cgroup.procs: No such file or directory
,08-03 19:10:50.071  1031  2040 V SIM_STK : Menu title from STK is T-Mobile
,08-03 19:10:50.083  4589  8713 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 474 ms] updated apps [took 474 ms] 
,08-03 19:10:50.320  6643  6774 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-03 19:10:50.320  6643  6774 I jxcore-log: 
,08-03 19:10:51.042  6643  6774 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-03 19:10:51.042  6643  6774 I jxcore-log: 
,08-03 19:10:51.068  6643  6774 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-03 19:10:51.068  6643  6774 I jxcore-log: 
,08-03 19:10:51.330  1031  1537 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=5.7, 0.0, 0.0  rx=4.5 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1365436098] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-03 19:10:51.341  1031  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=5.7, 0.0, 0.0  rx=4.5 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1365436109] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-03 19:10:51.341  1031  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-03 19:10:52.387  6643  6774 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-03 19:10:52.387  6643  6774 I jxcore-log: 
,08-03 19:10:52.619  6643  6774 I jxcore-log: ERROR runTests: 
08-03 19:10:52.619  6643  6774 I jxcore-log: 
,08-03 19:10:52.620  6643  6774 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thaliLogger'
08-03 19:10:52.620  6643  6774 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"39","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:39:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
,08-03 19:10:52.621  6643  6774 I jxcore-log: WARN testUtils: logCallback not set!
08-03 19:10:52.621  6643  6774 I jxcore-log: 
,08-03 19:10:52.633  6643  6774 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-03 19:10:52.633  6643  6774 I jxcore-log:     _functionName: 'loadFile',
08-03 19:10:52.633  6643  6774 I jxcore-log:     _lineNumber: '26',
08-03 19:10:52.633  6643  6774 I jxcore-log:     _columnNumber: '11',
08-03 19:10:52.633  6643  6774 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-03 19:10:52.633  6643  6774 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-03 19:10:52.633  6643  6774 I jxcore-log:     _functionName: '',
08-03 19:10:52.633  6643  6774 I jxcore-log:     _lineNumber: '39',
08-03 19:10:52.633  6643  6774 I jxcore-log:     _columnNumber: '7',
08-03 19:10:52.633  6643  6774 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:39:7' },
08-03 19:10:52.633  6643  6774 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-03 19:10:52.633  6643  6774 I jxcore-log:     _functionName: '',
08-03 19:10:52.633  6643  6774 I jxcore-log:     _lineNumber: '35',
08-03 19:10:52.633  6643  6774 I jxcore-log:     _columnNumber: '3',
08-03 19:10:52.633  6643  6774 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-03 19:10:52.633  6643  6774 I jxcore-log:   { _fileName: 'module.js',
08-03 19:10:52.633  6643  6774 I jxcore-log:     _functionName: '$w.prototype._compile',
08-03 19:10:52.633  6643  6774 I jxcore-log:     _lineNumber: '621',
08-03 19:10:52.633  6643  6774 I jxcore-log:     _columnNumber: '8',
08-03 19:10:52.633  6643  6774 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-03 19:10:52.633  6643  6774 I jxcore-log:   { _fileName: 'module.js',
08-03 19:10:52.633  6643  6774 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-03 19:10:52.633  6643  6774 I jxcore-log:     _lineNumber: '651',
08-03 19:10:52.633  6643  6774 I jxcore-log:     _columnNumber: '1',
08-03 19:10:52.633  6643  6774 I jxcore-log:    
,08-03 19:10:52.633  6643  6774 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****,
08-03 19:10:52.633  6643  6774 I jxcore-log: 
08-03 19:10:52.633  6643  6774 E jxcore-log: Error: 
08-03 19:10:52.633  6643  6774 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thaliLogger'
08-03 19:10:52.633  6643  6774 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-03 19:10:52.633  6643  6774 E jxcore-log: 
08-03 19:10:54.357  1031  1537 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=3.8, 0.0, 0.0  rx=2.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1365439125] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-03 19:10:54.380  1031  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=3.8, 0.0, 0.0  rx=2.7 bcn=0 [on:0 tx:0 rx:0 period:23] from screen [on:0 period:1365439148] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-03 19:10:54.380  1031  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-03 19:10:54.695  8749  8749 D AndroidRuntime: 
08-03 19:10:54.695  8749  8749 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-03 19:10:54.701  8749  8749 D AndroidRuntime: CheckJNI is OFF
08-03 19:10:54.856  8749  8749 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-03 19:10:54.867  1031  1090 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-03 19:10:54.867  1031  1090 I ActivityManager: Killing 6643:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-03 19:10:54.929  1031  1975 I WindowState: WIN DEATH: Window{2027391f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-03 19:10:54.931  1031  1542 D WifiService: Client connection lost with reason: 4
08-03 19:10:54.940  1031  1975 D InputDispatcher: Window went away: Window{2027391f u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-03 19:10:55.082  1031  1090 I ActivityManager:   Force finishing activity ActivityRecord{891d412 u0 com.test.thalitest/.MainActivity t40}
,08-03 19:10:55.133   330   353 E GBMv2   : DFP En is all cleared set to be enabled
,08-03 19:10:55.137  1031  1102 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-03 19:10:55.140  1031  1102 I ActivityManager:   Force finishing activity ActivityRecord{891d412 u0 com.test.thalitest/.MainActivity t40 f}
08-03 19:10:55.141  1031  1102 W ActivityManager: Duplicate finish request for ActivityRecord{891d412 u0 com.test.thalitest/.MainActivity t40 f}
,08-03 19:10:55.167  1939  1956 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-03 19:10:55.167  2031  2031 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-03 19:10:55.167  1939  1956 D SplitWindowPolicy: topRunningActivity=ActivityInfo{25dad73f co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
08-03 19:10:55.170  2031  2031 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-03 19:10:55.180  1031  1941 W ActivityManager: Spurious death for ProcessRecord{117546ef 6643:com.test.thalitest/u0a118}, curProc for 6643: null
08-03 19:10:55.182  1939  2773 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-03 19:10:55.183  1939  2773 D SplitWindowPolicy: topRunningActivity=ActivityInfo{57d080c co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
,08-03 19:10:55.186  2031  2031 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-03 19:10:55.187  2031  2102 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-03 19:10:55.189  1602  1602 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-03 19:10:55.194  1031  1089 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-03 19:10:55.196  1031  1427 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-03 19:10:55.205  1994  1994 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-03 19:10:55.207  7722  7722 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-03 19:10:55.207  7722  7722 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-03 19:10:55.210  3803  3803 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,08-03 19:10:55.217  2504  2613 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-03 19:10:55.266  1903  1903 D ActionManagerService: notifyUserLog: 1000003
,08-03 19:10:55.268  8156  8156 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-03 19:10:55.270  2031  2031 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-03 19:10:55.270  3803  4455 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-03 19:10:55.271  2031  2031 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-03 19:10:55.272  2031  2031 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-03 19:10:55.273  2031  2031 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-03 19:10:55.274  4488  4488 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-03 19:10:55.275  4488  4488 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-03 19:10:55.275  4488  4488 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-03 19:10:55.275  4488  4488 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-03 19:10:55.275  4488  4488 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-03 19:10:55.275  4488  4488 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-03 19:10:55.275  4488  4488 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-03 19:10:55.275  4488  4488 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-03 19:10:55.275  4488  4488 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 19:10:55.275  4488  4488 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-03 19:10:55.275  4488  4488 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-03 19:10:55.275  4488  4488 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-03 19:10:55.282  2031  2031 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
,08-03 19:10:55.287  3803  3819 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-03 19:10:55.287  1815  1815 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-03 19:10:55.293  1602  1602 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-03 19:10:55.295  1903  1903 D ActionManagerService: notifyUserLog: 1000004
08-03 19:10:55.295  3803  4455 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-03 19:10:55.297  1602  1656 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-03 19:10:55.297  1602  1656 D KeyguardModel: createShortcutInfo...
08-03 19:10:55.300  2031  2031 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-03 19:10:55.300  2031  2031 I GBoardWebViewUtils: , create_time: 1430832262123
08-03 19:10:55.300  2031  2031 I GBoardWebViewUtils: , expire_time: 0
08-03 19:10:55.300  2031  2031 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-03 19:10:55.300  2031  2031 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-03 19:10:55.300  2031  2031 I GBoardWebViewUtils: , display: false
08-03 19:10:55.300  2031  2031 I GBoardWebViewUtils: , animation: false }
08-03 19:10:55.300  2031  2031 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-03 19:10:55.300  2031  2031 I GBoardWebViewUtils: , create_time: 1430832262287
08-03 19:10:55.300  2031  2031 I GBoardWebViewUtils: , expire_time: 0
08-03 19:10:55.300  2031  2031 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-03 19:10:55.300  2031  2031 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-03 19:10:55.300  2031  2031 I GBoardWebViewUtils: , display: false
08-03 19:10:55.300  2031  2031 I GBoardWebViewUtils: , animation: false }
08-03 19:10:55.300  2031  2031 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1469801564706
08-03 19:10:55.300  2031  2031 I GBoardWebViewUtils: , create_time: 1469801565454
08-03 19:10:55.300  2031  2031 I GBoardWebViewUtils: , expire_time: 0
08-03 19:10:55.300  2031  2031 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide.html?id=guide_1111111111116_1469801564706&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-03 19:10:55.300  2031  2031 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-03 19:10:55.300  2031  2031 I GBoardWebViewUtils: , display: false
08-03 19:10:55.300  2031  2031 I GBoardWebViewUtils: , animation: false }
,08-03 19:10:55.311  2195  2195 I ConfigService: onCreate
08-03 19:10:55.311  1602  1656 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-03 19:10:55.311  1602  1656 D KeyguardModel: createShortcutInfo...
08-03 19:10:55.312  2195  2195 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-03 19:10:55.315  1815  1815 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,08-03 19:10:55.321  2031  8780 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-03 19:10:55.323  1602  1656 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-03 19:10:55.323  1602  1656 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-03 19:10:55.324  1602  1656 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-03 19:10:55.325  1602  1656 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-03 19:10:55.326  1602  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-03 19:10:55.326  1602  1656 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-03 19:10:55.330  1602  1656 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-03 19:10:55.330  1602  1656 D KeyguardModel: createShortcutInfo...
,08-03 19:10:55.336  2031  2031 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-03 19:10:55.336  1602  1656 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-03 19:10:55.336  1602  1656 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-03 19:10:55.336  2031  2031 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-03 19:10:55.337  1602  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-03 19:10:55.337  1602  1656 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-03 19:10:55.338  1602  1656 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-03 19:10:55.338  1602  1656 D KeyguardModel: createShortcutInfo...
08-03 19:10:55.343  1602  1656 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-03 19:10:55.343  1602  1656 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-03 19:10:55.343  1602  1656 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-03 19:10:55.343  1602  1656 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-03 19:10:55.344  1602  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-03 19:10:55.344  1602  1656 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-03 19:10:55.346  1602  1656 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-03 19:10:55.346  1602  1656 D KeyguardModel: createShortcutInfo...
08-03 19:10:55.352  1602  1602 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-03 19:10:55.352  1602  1602 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-03 19:10:55.354  1602  1602 D KeyguardModel: handleShortcutListChanged...
08-03 19:10:55.354  1602  1602 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-03 19:10:55.358  1867  1867 D SplitUIManager: split_name #11 / not available #0
08-03 19:10:55.358  1867  1867 D SplitUIService: removed split : 
,08-03 19:10:55.366  4589  4589 I art     : Explicit concurrent mark sweep GC freed 15426(885KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 534us total 168.583ms
08-03 19:10:55.366  1602  1656 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-03 19:10:55.366  1602  1656 D KeyguardModel: createShortcutInfo...
08-03 19:10:55.369  1031  2040 V SIM_STK : Menu title from STK is T-Mobile
08-03 19:10:55.376  1602  1656 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-03 19:10:55.376  1602  1656 D KeyguardModel: createShortcutInfo...
,08-03 19:10:55.381  2195  2195 I ConfigService: onBind returning update interface
08-03 19:10:55.383  2195  2195 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-03 19:10:55.383  2195  2195 I ConfigService: onBind returning config service
08-03 19:10:55.389  1602  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-03 19:10:55.390  1602  1656 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-03 19:10:55.392  1602  1656 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-03 19:10:55.392  1602  1656 D KeyguardModel: createShortcutInfo...
,08-03 19:10:55.394  1602  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-03 19:10:55.394  1602  1656 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-03 19:10:55.396  2195  2195 I ConfigService: onDestroy
08-03 19:10:55.398  1815  8785 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-03 19:10:55.414  1602  1656 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-03 19:10:55.414  1602  1656 D KeyguardModel: createShortcutInfo...
,08-03 19:10:55.416  1867  1867 D SplitUIManager: split_name #11 / not available #0
08-03 19:10:55.416  1867  1867 I SplitUIService: split app #11
08-03 19:10:55.417  1031  1031 I art     : Explicit concurrent mark sweep GC freed 43762(2MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 4.565ms total 256.664ms
08-03 19:10:55.418  2031  2046 I art     : Background sticky concurrent mark sweep GC freed 3401(183KB) AllocSpace objects, 4(320KB) LOS objects, 0% free, 80MB/80MB, paused 14.954ms total 19.455ms
08-03 19:10:55.420  1602  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-03 19:10:55.420  1602  1656 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-03 19:10:55.422  1031  1102 I art     : WaitForGcToComplete blocked for 248.268ms for cause Explicit
08-03 19:10:55.423  1602  1656 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-03 19:10:55.423  1602  1656 D KeyguardModel: createShortcutInfo...
08-03 19:10:55.431  1031  1975 V SIM_STK : Menu title from STK is T-Mobile
08-03 19:10:55.431  1031  1975 V SIM_STK : Menu title from STK is T-Mobile
,08-03 19:10:55.443  1602  1602 D KeyguardModel: handleShortcutListChanged...
08-03 19:10:55.443  1602  1602 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-03 19:10:55.476   324   422 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-03 19:10:55.477  3215  8792 I Thermal-Lib: Thermal-Lib-Client: Client request sent
,08-03 19:10:55.486  1031  1725 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-03 19:10:55.487  7722  7722 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-03 19:10:55.487  7722  7722 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-03 19:10:55.487  7722  7722 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-03 19:10:55.487  7722  7722 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-03 19:10:55.487  7722  7722 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-03 19:10:55.487  7722  7722 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-03 19:10:55.487  7722  7722 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-03 19:10:55.487  7722  7722 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-03 19:10:55.487  7722  7722 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-03 19:10:55.487  7722  7722 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-03 19:10:55.487  7722  7722 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-03 19:10:55.489  5962  8793 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-03 19:10:55.492  7097  7097 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-03 19:10:55.494  1815  8794 I PeopleContactsSync: CP2 sync disabled
,08-03 19:10:55.507  2031  2031 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-03 19:10:55.509  2031  2031 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-03 19:10:55.511  2031  2031 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-03 19:10:55.513  2031  2031 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-03 19:10:55.514  2031  2031 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-03 19:10:55.514  2031  2031 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-03 19:10:55.531  2031  2031 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-03 19:10:55.532  2031  2031 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-03 19:10:55.532  2031  2031 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-03 19:10:55.534  2031  2170 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-03 19:10:55.535  2031  2170 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,08-03 19:10:55.536  1815  4735 I Icing   : doRemovePackageData com.test.thalitest
08-03 19:10:55.540  2328  8797 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-03 19:10:55.543  1031  1031 D administrator: Handling package changes for user 0
08-03 19:10:55.547  2031  2031 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,08-03 19:10:55.548  2031  2031 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-03 19:10:55.548  2031  2031 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-03 19:10:55.558  1031  1574 V SIM_STK : Menu title from STK is T-Mobile
08-03 19:10:55.558  2031  2031 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-03 19:10:55.558  1031  1725 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8799 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-03 19:10:55.559  1031  1096 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{302da63c u0 com.lge.launcher2/.Launcher t39} time:198039
08-03 19:10:55.564  2031  2031 D [Concierge]WidgetView: change position of spinner
08-03 19:10:55.564  2598  2598 D [Concierge]Service: onStartCommand(). Type : 8
08-03 19:10:55.564  2598  2598 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-03 19:10:55.565  2598  2598 D [Concierge]Service: Update widget ID : 11
08-03 19:10:55.568  2031  2031 I [Concierge]WidgetView: initWebView(). Time : 1470244255568
08-03 19:10:55.568  2598  2598 D [Concierge]Service: onStartCommand(). Type : 0
08-03 19:10:55.578  1815  8790 W GmsApplication: Using Auth Proxy for data requests.
,08-03 19:10:55.582  2031  2031 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 782491068
08-03 19:10:55.582  2031  2031 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-03 19:10:55.582  2031  2031 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-03 19:10:55.583  1815  8790 W GmsApplication: Using Auth Proxy for data requests.
08-03 19:10:55.585  2031  2031 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@fb6abf8
08-03 19:10:55.585  2031  2031 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-03 19:10:55.586  2031  2031 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-03 19:10:55.586  2031  2031 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-03 19:10:55.592  2031  2031 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-03 19:10:55.593  2031  2031 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-03 19:10:55.593  2031  2031 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1470244084857, New one : 1470244255568
08-03 19:10:55.593  2031  2031 D [Concierge]WidgetView: Unregister all receivers
08-03 19:10:55.593  2031  2031 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-03 19:10:55.594  2031  2031 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-03 19:10:55.596  2031  2031 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-03 19:10:55.597  2031  2031 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-03 19:10:55.598  2031  2031 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
,08-03 19:10:55.599  2031  2031 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-03 19:10:55.600  2031  2031 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-03 19:10:55.602  2031  2031 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-03 19:10:55.603  2031  2031 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-03 19:10:55.636  2031  2031 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-03 19:10:55.644  2031  2031 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-03 19:10:55.644  2031  2031 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-03 19:10:55.646  2031  2031 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-03 19:10:55.647  1031  1031 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-03 19:10:55.647  1031  1031 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-03 19:10:55.648  1031  1031 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-03 19:10:55.651  1031  1577 D TaskPersister: removeObsoleteFile: deleting file=40_task.xml
,08-03 19:10:55.663  2031  2031 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-03 19:10:55.667  2031  2031 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2bd81ebd time:198146
,08-03 19:10:55.689  8799  8799 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-03 19:10:55.691  8799  8799 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-03 19:10:55.694  8799  8799 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-03 19:10:55.695  8799  8799 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-03 19:10:55.697  1815  8816 I art     : Explicit concurrent mark sweep GC freed 36420(2MB) AllocSpace objects, 27(432KB) LOS objects, 51% free, 30MB/62MB, paused 1.825ms total 33.015ms
08-03 19:10:55.700  1815  1827 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/history_query.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-03 19:10:55.701  1815  1827 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/help_responses.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-03 19:10:55.701  1815  1827 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/metrics.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,08-03 19:10:55.721  1031  1102 I art     : Explicit concurrent mark sweep GC freed 10203(541KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.692ms total 297.638ms
,08-03 19:10:55.757  8799  8799 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-03 19:10:55.765  8799  8799 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-03 19:10:55.790  8749  8749 D AndroidRuntime: Shutting down VM
,08-03 19:10:55.796  8799  8799 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-03 19:10:55.810  2031  2031 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-03 19:10:55.822  1031  1089 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-03 19:10:55.825  1031  1102 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8818 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-03 19:10:55.835  1031  1089 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-03 19:10:55.842  2031  2031 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-03 19:10:55.849  8799  8799 D LgDataFeature: LgDataFeature() Constructor: none
08-03 19:10:55.849  8799  8799 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 19:10:55.856  2031  2870 I GBoardtInterface: onReloaded()
08-03 19:10:55.857  2031  2031 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-03 19:10:55.858  3803  3818 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-03 19:10:55.861  3803  3819 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-03 19:10:55.864  1031  1725 I ActivityManager: Killing 8383:com.android.chrome/u0a57 (adj 15): empty #17
,08-03 19:10:55.911  1031  1941 W libprocessgroup: failed to open /acct/uid_10057/pid_8383/cgroup.procs: No such file or directory
,08-03 19:10:55.911  1903  1903 D ActionManagerService: notifyUserLog: 1000001
08-03 19:10:55.914  3803  4455 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
,08-03 19:10:55.914  3803  4455 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-03 19:10:55.916  1903  1903 D ActionManagerService: notifyUserLog: 1000001
08-03 19:10:55.916  3803  4455 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-03 19:10:55.916  3803  4455 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-03 19:10:55.916  3803  4455 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-03 19:10:55.917  3803  4455 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-03 19:10:55.917  3803  3818 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-03 19:10:55.919  2031  2031 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-03 19:10:55.919  2031  2031 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-03 19:10:55.921  2031  2031 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-03 19:10:55.921  2031  2031 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-03 19:10:55.922  2031  2031 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1469801564706&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-03 19:10:55.923  2031  2031 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1469801564706&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,08-03 19:10:55.943  8799  8799 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-03 19:10:55.953  1031  1986 I ActivityManager: Killing 8403:com.lge.drmservice/u0a62 (adj 15): empty #17
08-03 19:10:56.001  1994  1994 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-03 19:10:56.001  1994  1994 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-03 19:10:56.001  1031  1884 W libprocessgroup: failed to open /acct/uid_10062/pid_8403/cgroup.procs: No such file or directory
,08-03 19:10:56.003  1994  1994 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-03 19:10:56.005  8156  8156 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-03 19:10:56.020  1031  1537 E WifiStateMachine:  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,08-03 19:10:56.021  1031  1537 E WifiStateMachine:  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-03 19:10:56.021  1031  1537 E WifiStateMachine:  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-03 19:10:56.021  1031  1537 E WifiStateMachine:  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-03 19:10:56.021  1031  1537 E WifiStateMachine:  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-03 19:10:56.021  1031  1537 E WifiStateMachine:  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-03 19:10:56.036  1031  2040 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=8840 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-03 19:10:56.080  8840  8840 E SQLiteDatabase: Failed to open database '/data/data/com.lge.lifetracker/databases/lifetracker2.db'.
08-03 19:10:56.080  8840  8840 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 19:10:56.080  8840  8840 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-03 19:10:56.080  8840  8840 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-03 19:10:56.080  8840  8840 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-03 19:10:56.080  8840  8840 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-03 19:10:56.080  8840  8840 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-03 19:10:56.080  8840  8840 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-03 19:10:56.080  8840  8840 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-03 19:10:56.080  8840  8840 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-03 19:10:56.080  8840  8840 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-03 19:10:56.080  8840  8840 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-03 19:10:56.080  8840  8840 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-03 19:10:56.080  8840  8840 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-03 19:10:56.080  8840  8840 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-03 19:10:56.080  8840  8840 E SQLiteDatabase: 	at com.lge.lifetracker.core.provider.LifetrackerProvider2.onCreate(LifetrackerProvider2.java:56)
08-03 19:10:56.080  8840  8840 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-03 19:10:56.080  8840  8840 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-03 19:10:56.080  8840  8840 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-03 19:10:56.080  8840  8840 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-03 19:10:56.080  8840  8840 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-03 19:10:56.080  8840  8840 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-03 19:10:56.080  8840  8840 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-03 19:10:56.080  8840  8840 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 19:10:56.080  8840  8840 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-03 19:10:56.080  8840  8840 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-03 19:10:56.080  8840  8840 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 19:10:56.080  8840  8840 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-03 19:10:56.080  8840  8840 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-03 19:10:56.080  8840  8840 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-03 19:10:56.081  8840  8840 E LifetrackerProvider2: Unable to open database for writing.
08-03 19:10:56.081  8840  8840 E LifetrackerProvider2: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 19:10:56.081  8840  8840 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-03 19:10:56.081  8840  8840 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-03 19:10:56.081  8840  8840 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-03 19:10:56.081  8840  8840 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-03 19:10:56.081  8840  8840 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-03 19:10:56.081  8840  8840 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-03 19:10:56.081  8840  8840 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-03 19:10:56.081  8840  8840 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-03 19:10:56.081  8840  8840 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-03 19:10:56.081  8840  8840 E LifetrackerProvider2: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-03 19:10:56.081  8840  8840 E LifetrackerProvider2: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-03 19:10:56.081  8840  8840 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-03 19:10:56.081  8840  8840 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-03 19:10:56.081  8840  8840 E LifetrackerProvider2: 	at com.lge.lifetracker.core.provider.LifetrackerProvider2.onCreate(LifetrackerProvider2.java:56)
08-03 19:10:56.081  8840  8840 E LifetrackerProvider2: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-03 19:10:56.081  8840  8840 E LifetrackerProvider2: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-03 19:10:56.081  8840  8840 E LifetrackerProvider2: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-03 19:10:56.081  8840  8840 E LifetrackerProvider2: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-03 19:10:56.081  8840  8840 E LifetrackerProvider2: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-03 19:10:56.081  8840  8840 E LifetrackerProvider2: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-03 19:10:56.081  8840  8840 E LifetrackerProvider2: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-03 19:10:56.081  8840  8840 E LifetrackerProvider2: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 19:10:56.081  8840  8840 E LifetrackerProvider2: 	at android.os.Looper.loop(Looper.java:135)
08-03 19:10:56.081  8840  8840 E LifetrackerProvider2: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-03 19:10:56.081  8840  8840 E LifetrackerProvider2: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 19:10:56.081  8840  8840 E LifetrackerProvider2: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-03 19:10:56.081  8840  8840 E LifetrackerProvider2: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-03 19:10:56.081  8840  8840 E LifetrackerProvider2: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-03 19:10:56.090  8840  8840 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-03 19:10:56.090  8840  8840 W LG Account v2.2: No Profi,leInfo entries
08-03 19:10:56.090  8840  8840 I LG Account v2.2: isEnabled: false
08-03 19:10:56.090  8840  8840 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-03 19:10:56.090  8840  8840 I Feature : [Lifetracker]Country: EU
08-03 19:10:56.090  8840  8840 I Feature : [Lifetracker]Operator: OPEN
08-03 19:10:56.090  8840  8840 I Feature : [Lifetracker]Ranking support: false
08-03 19:10:56.090  8840  8840 I Feature : [Lifetracker]Comfort support: false
08-03 19:10:56.090  8840  8840 I Feature : [Lifetracker]Accessory: true
08-03 19:10:56.091  8840  8840 I Feature : [Lifetracker]Health device: true
08-03 19:10:56.091  8840  8840 I Feature : [Lifetracker]Extra Pedometer: false
08-03 19:10:56.091  8840  8840 I Feature : [Lifetracker]Blood glucose device: false
08-03 19:10:56.091  8840  8840 I Feature : [Lifetracker]Device Number: 3
08-03 19:10:56.091  8840  8840 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
08-03 19:10:56.120  1031  1918 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=8861 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a

```
