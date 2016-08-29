#### Test 8289468223f5822_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-29 15:11:23.531  6461  6461 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_ADDED'.
--------- beginning of system
08-29 15:11:23.536  6461  6461 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsm.mss.OasPackageScanReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:2586 
08-29 15:11:23.574  4603  6611 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-29 15:11:23.656  1034  1560 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6621 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 15:11:23.667  1034  1758 V SIM_STK : Menu title from STK is T-Mobile
08-29 15:11:23.825  1801  1801 I art     : Explicit concurrent mark sweep GC freed 22579(1495KB) AllocSpace objects, 15(240KB) LOS objects, 51% free, 29MB/61MB, paused 1.223ms total 73.420ms
08-29 15:11:23.835  4603  6611 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 261 ms] updated apps [took 261 ms] 
08-29 15:11:23.889  6621  6621 D DocsApplication: Installing DEX configuration.
08-29 15:11:23.905  6621  6621 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
08-29 15:11:23.908  6621  6621 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{69537da com.google.android.apps.docs}
08-29 15:11:23.924  6621  6621 D TAG     : onCreate()
08-29 15:11:23.942  6621  6621 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,08-29 15:11:24.712  6656  6656 D AndroidRuntime: 
08-29 15:11:24.712  6656  6656 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-29 15:11:24.717  6656  6656 D AndroidRuntime: CheckJNI is OFF
08-29 15:11:24.843  6656  6656 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-29 15:11:24.844  1801  4734 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
08-29 15:11:24.855  1034  1874 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-29 15:11:24.866  1925  1941 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-29 15:11:24.870  1034  1874 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-29 15:11:24.872  1034  1874 D ActivityManager: setTaskToReturnTo : TaskRecord{2aa932dd #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-29 15:11:24.872  1034  1874 D ActivityManager: setTaskToReturnTo : TaskRecord{2aa932dd #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-29 15:11:24.873  1034  1874 D WindowStateEx: AppWindowTokenEx init.. 
08-29 15:11:24.878   338   350 E GBMv2   : DFP En is all cleared set to be enabled
08-29 15:11:24.891  1801  4734 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-29 15:11:24.916  1034  1874 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6671 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-29 15:11:24.918  6656  6656 D AndroidRuntime: Shutting down VM
08-29 15:11:24.963  1925  1941 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-29 15:11:24.963  1925  1941 D SplitWindowPolicy: topRunningActivity=ActivityInfo{10634a76 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-29 15:11:24.964  1925  1942 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-29 15:11:24.964  1925  1942 D SplitWindowPolicy: topRunningActivity=ActivityInfo{83ad877 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-29 15:11:24.981  1801  4734 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
08-29 15:11:25.027  6671  6671 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-29 15:11:25.148  6671  6671 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-29 15:11:25.156  6671  6671 I LibraryLoader: Loading: webviewchromium
,08-29 15:11:25.159  6671  6671 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 5421-5425)
08-29 15:11:25.159  6671  6671 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 15:11:25.190  6671  6671 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c958594}
,08-29 15:11:25.191  6671  6671 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 15:11:25.192  6671  6671 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-29 15:11:25.197  6621  6621 D LgDataFeature: LgDataFeature() Constructor: none
08-29 15:11:25.197  6621  6621 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 15:11:25.203  6671  6671 I BrowserStartupController: Initializing chromium process, renderers=0
,08-29 15:11:25.204  6671  6671 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-29 15:11:25.215  6671  6671 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-29 15:11:25.216  6671  6671 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
,08-29 15:11:25.216  6671  6671 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-29 15:11:25.217   316  2154 V AudioPolicyService: registerClient() client 0xb558a700, uid 10118
08-29 15:11:25.221  1034  1116 D BluetoothManagerService: Message: 20
08-29 15:11:25.221  1034  1116 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1de6b07f:true
08-29 15:11:25.228  6671  6671 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-29 15:11:25.228  6671  6671 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-29 15:11:25.228  6671  6671 I Adreno-EGL: Build Date: 12/12/14 금
08-29 15:11:25.228  6671  6671 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-29 15:11:25.228  6671  6671 I Adreno-EGL: Remote Branch: 
08-29 15:11:25.228  6671  6671 I Adreno-EGL: Local Patches: 
08-29 15:11:25.228  6671  6671 I Adreno-EGL: Reconstruct Branch: 
,08-29 15:11:25.296  6671  6713 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-29 15:11:25.303  6671  6671 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-29 15:11:25.318  6150  6150 I LockScreenSettings: New app installed broadcast received ..
,08-29 15:11:25.320  6671  6671 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-29 15:11:25.321  6150  6150 I LockScreenSettings: Number of installed packages  1
08-29 15:11:25.327  6671  6671 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-29 15:11:25.331  6671  6671 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-29 15:11:25.335  6671  6671 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-29 15:11:25.335  6671  6671 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-29 15:11:25.351  6621  6621 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
08-29 15:11:25.353  6671  6671 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-29 15:11:25.365  6671  6671 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-29 15:11:25.365  6671  6671 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-29 15:11:25.367  1034  1560 V SIM_STK : Menu title from STK is T-Mobile
,08-29 15:11:25.432  1034  2032 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6746 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-29 15:11:25.439  6671  6760 D OpenGLRenderer: Render dirty regions requested: true
08-29 15:11:25.439  6671  6760 I OpenGLRenderer: Initialized EGL, version 1.4
08-29 15:11:25.447  6671  6736 D LgDataFeature: LgDataFeature() Constructor: none
08-29 15:11:25.447  6671  6736 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 15:11:25.447  6671  6760 D OpenGLRenderer: Enabling debug mode 0
,08-29 15:11:25.453  6671  6671 D Atlas   : Validating map...
08-29 15:11:25.458  1034  1758 D SplitWindow: check instance of lgWin Window{8153db2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-29 15:11:25.462  1034  1112 W ActivityManager: Activity pause timeout for ActivityRecord{2b782e52 u0 com.test.thalitest/.MainActivity t6}
,08-29 15:11:25.486  6746  6746 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-29 15:11:25.486  6746  6746 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,08-29 15:11:25.527  1034  1922 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6767 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-29 15:11:25.527  1034  1922 I ActivityManager: Killing 5487:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
,08-29 15:11:25.580  1034  1758 W libprocessgroup: failed to open /acct/uid_10005/pid_5487/cgroup.procs: No such file or directory
,08-29 15:11:25.582  1034  1117 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +620ms (total +703ms)
08-29 15:11:25.582  6671  6671 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@ee9973 time:105848
08-29 15:11:25.582  1034  1117 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2b782e52 u0 com.test.thalitest/.MainActivity t6} time:105848
08-29 15:11:25.622  6767  6767 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
,08-29 15:11:25.639  6767  6767 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-29 15:11:25.641  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-29 15:11:25.659  1034  1560 I ActivityManager: Killing 5681:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-29 15:11:25.670  5652  5652 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-29 15:11:25.670  5652  5652 W System.err: android.os.DeadObjectException
,08-29 15:11:25.670  5652  5652 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-29 15:11:25.670  5652  5652 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-29 15:11:25.670  5652  5652 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-29 15:11:25.670  5652  5652 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-29 15:11:25.670  5652  5652 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-29 15:11:25.670  5652  5652 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-29 15:11:25.670  5652  5652 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 15:11:25.670  5652  5652 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 15:11:25.671  5652  5652 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-29 15:11:25.671  5652  5652 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 15:11:25.671  5652  5652 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 15:11:25.671  5652  5652 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 15:11:25.671  5652  5652 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 15:11:25.671  5652  5652 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 15:11:25.671  5652  5652 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-29 15:11:25.671  5652  5652 W System.err: android.os.DeadObjectException
08-29 15:11:25.671  5652  5652 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-29 15:11:25.671  5652  5652 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-29 15:11:25.671  5652  5652 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-29 15:11:25.671  5652  5652 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-29 15:11:25.671  5652  5652 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-29 15:11:25.671  5652  5652 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-29 15:11:25.672  5652  5652 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 15:11:25.672  5652  5652 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 15:11:25.672  5652  5652 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-29 15:11:25.672  5652  5652 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 15:11:25.672  5652  5652 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 15:11:25.672  5652  5652 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 15:11:25.672  5652  5652 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 15:11:25.672  5652  5652 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 15:11:25.672  5652  5652 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-29 15:11:25.672  5652  5652 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-29 15:11:25.692  6671  6671 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-29 15:11:25.692  6671  6671 I chromium: 
,08-29 15:11:25.724  6671  6671 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-29 15:11:25.818   278   278 E lowmemorykiller: Error opening /proc/5681/oom_score_adj; errno=2
,08-29 15:11:25.827  1034  1874 W ActivityManager: Exception when unbinding service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service
08-29 15:11:25.827  1034  1874 W ActivityManager: android.os.DeadObjectException
08-29 15:11:25.827  1034  1874 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
08-29 15:11:25.827  1034  1874 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:496)
08-29 15:11:25.827  1034  1874 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleUnbindService(ApplicationThreadNative.java:917)
08-29 15:11:25.827  1034  1874 W ActivityManager: 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1776)
08-29 15:11:25.827  1034  1874 W ActivityManager: 	at com.android.server.am.ActiveServices.unbindServiceLocked(ActiveServices.java:901)
08-29 15:11:25.827  1034  1874 W ActivityManager: 	at com.android.server.am.ActivityManagerService.unbindService(ActivityManagerService.java:15417)
08-29 15:11:25.827  1034  1874 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:963)
08-29 15:11:25.827  1034  1874 W ActivityManager: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2560)
08-29 15:11:25.827  1034  1874 W ActivityManager: 	at com.android.server.am.ActivityManagerServiceEx.onTransact(ActivityManagerServiceEx.java:421)
08-29 15:11:25.827  1034  1874 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:446)
08-29 15:11:25.830  1034  1991 W libprocessgroup: failed to open /acct/uid_1000/pid_5681/cgroup.procs: No such file or directory
,08-29 15:11:25.836  5652  5652 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-29 15:11:25.837  5652  5652 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-29 15:11:25.883  1034  1922 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6795 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-29 15:11:25.885  5652  5652 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-29 15:11:25.892  6671  6794 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435048448
08-29 15:11:25.903  6671  6794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-29 15:11:25.903  6671  6794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-29 15:11:25.903  6671  6794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-29 15:11:25.903  6671  6794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-29 15:11:25.903  6671  6794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-29 15:11:25.903  6671  6794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e06b3c7 added. We now have 1 listener(s)
08-29 15:11:25.908  1034  1929 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 15:11:25.911  6671  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-29 15:11:25.914  6671  6794 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 15:11:25.916  6671  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 15:11:25.917  6671  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 15:11:25.927  6671  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-29 15:11:25.927  6671  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-29 15:11:25.927  6671  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-29 15:11:25.927  6671  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-29 15:11:25.927  6671  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-29 15:11:25.927  6671  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-29 15:11:25.927  6671  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-29 15:11:25.927  6671  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-29 15:11:25.927  6671  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-29 15:11:25.927  6671  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-29 15:11:25.927  6671  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-29 15:11:25.927  6671  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-29 15:11:25.927  6671  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-29 15:11:25.927  6671  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-29 15:11:25.928  6671  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f26792 added. We now have 1 listener(s)
,08-29 15:11:25.928  6671  6794 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 15:11:25.932  1034  1440 D WifiService: New client listening to asynchronous messages
08-29 15:11:25.935  6671  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 15:11:25.935  6671  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-29 15:11:25.937  6671  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-29 15:11:25.937  6671  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-29 15:11:25.937  6671  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-29 15:11:25.942  6671  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 15:11:25.943  1034  1560 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-29 15:11:25.944  6671  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-29 15:11:25.956  6671  6794 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-29 15:11:25.956  6671  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 15:11:25.956  6671  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:25.956  6671  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 15:11:25.956  6671  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:11:25.956  6671  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:11:25.956  6671  6794 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 15:11:25.956  6671  6794 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 15:11:25.956  6671  6794 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 15:11:25.957  6671  6794 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-29 15:11:25.957  6671  6794 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 15:11:25.959  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:25.961  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:25.962  6671  6794 I io.jxcore.node.LifeCycleMonitor: start: OK
08-29 15:11:25.971  6795  6795 D UEI.SmartControl: Quickset Services start...
08-29 15:11:25.973  6795  6795 I UEI.SmartControl: Manufacture = LGE
08-29 15:11:25.974  6795  6795 D UEI.SmartControl: Id = LGNevo
08-29 15:11:25.975  6795  6795 D UEI.SmartControl: File observer start...
08-29 15:11:25.975  6795  6795 E UEI.SmartControl: IR Port is disabled: false
08-29 15:11:25.976  6795  6795 D UEI.SmartControl: Starting file observer...
08-29 15:11:25.976  6795  6795 D UEI.SmartControl: Extracting JNI libs...
08-29 15:11:25.976  6795  6795 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,08-29 15:11:25.990  6671  6736 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-29 15:11:25.990  6671  6736 I chromium: 
08-29 15:11:26.029  6671  6671 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-29 15:11:26.062  6795  6795 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-29 15:11:26.062  6795  6795 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-29 15:11:26.062  6795  6795 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-29 15:11:26.098  6795  6795 I UEI.SmartControl: --- Selecting new region: 6
,08-29 15:11:26.100  6795  6795 I UEI.SmartControl: Model = LG-D855
08-29 15:11:26.102  6795  6795 D UEI.SmartControl: QS Service created
08-29 15:11:26.119  6795  6795 I UEI.SmartControl: Service initServices...
,08-29 15:11:26.124  6795  6795 D UEI.SmartControl: QS start get config
08-29 15:11:26.196  6795  6795 D UEI.SmartControl: Loading JNI Libs...
,08-29 15:11:26.484  2779  2779 I MusicWidget: mDelayedStopHandler : unbind
,08-29 15:11:26.491  2134  2134 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
08-29 15:11:26.491  2134  2134 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
08-29 15:11:26.491  2134  2134 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
08-29 15:11:26.493  2134  2134 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
08-29 15:11:26.493  2134  2134 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
08-29 15:11:26.493  2134  2134 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
08-29 15:11:26.495  2134  2134 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
08-29 15:11:26.495  2134  2134 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
08-29 15:11:26.497  1034  1929 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@6459aadcom.lge.music.MediaPlaybackService$5@2f91c1e2
,08-29 15:11:26.497  2134  2134 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
08-29 15:11:26.498  2134  2134 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 15:11:26.503  2134  2134 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 15:11:26.504  6795  6795 I UEI.SmartControl: Supports setup maps: true,
08-29 15:11:26.504  2134  2134 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 15:11:26.505  2134  2134 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@130f6700
08-29 15:11:26.505  2134  2134 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 15:11:26.506  2134  2134 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
08-29 15:11:26.507  6795  6795 D UEI.SmartControl: QS start statue = true Error code = 0
08-29 15:11:26.507  2134  2134 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 15:11:26.507  6795  6795 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-29 15:11:26.507  6795  6795 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-29 15:11:26.507  6795  6795 I UEI.SmartControl: ### init IR Blaster...
08-29 15:11:26.507  2134  2134 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
08-29 15:11:26.507  2134  2134 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
08-29 15:11:26.508  2134  2134 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 15:11:26.508  2134  2134 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 15:11:26.509  2134  2134 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,08-29 15:11:26.511  2134  2134 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 15:11:26.512  2134  2134 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 15:11:26.512  6795  6795 D serial_port: Configuring serial port
08-29 15:11:26.514  2134  2134 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
08-29 15:11:26.516  6795  6795 E UEI.SmartControl: UEIBLaster setting for 616
08-29 15:11:26.516  6795  6795 I UEI.SmartControl: Setting serial record hearder size = 2
08-29 15:11:26.516  2134  2134 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
08-29 15:11:26.516  6795  6795 I UEI.SmartControl: configuring settings for MAXQ616
08-29 15:11:26.517  2134  2134 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
08-29 15:11:26.517  6795  6795 I UEI.SmartControl: Get version...
08-29 15:11:26.517  2134  2134 V MediaPlayer[Native]: reset
,08-29 15:11:26.523  2134  2134 V MediaPlayer[Native]: setListener
08-29 15:11:26.523  2134  2134 V MediaPlayer[Native]: disconnect
08-29 15:11:26.523  2134  2134 V MediaPlayer[Native]: destructor
,08-29 15:11:26.523   316  1381 V AudioFlinger: releasing 18 from 2134 for -1
08-29 15:11:26.524   316  1381 V AudioFlinger:  decremented refcount to 0
08-29 15:11:26.524   316  1381 V AudioFlinger: purging stale effects
08-29 15:11:26.524  2134  2134 V MediaPlayer[Native]: disconnect
08-29 15:11:26.525  2134  2134 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
08-29 15:11:26.526  2134  2134 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
08-29 15:11:26.526  2134  2134 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
08-29 15:11:26.527  2134  2134 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
08-29 15:11:26.527  2134  2134 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
08-29 15:11:26.527  2134  2134 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
08-29 15:11:26.527  2134  2134 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 15636851
08-29 15:11:26.528  2134  2134 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 15636851
08-29 15:11:26.531  2134  2134 I SmartShareClient: [SmartShareManagerClient] terminate service: 2134/MediaPlaybackService/136247206
08-29 15:11:26.535  2134  2134 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
08-29 15:11:26.535  2134  2134 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@3a4a9030
,08-29 15:11:26.537  6795  6824 D UEI.SmartControl: serial port data available: 21
08-29 15:11:26.537  2134  2134 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
08-29 15:11:26.538  2134  2134 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
08-29 15:11:26.539  2134  2134 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
08-29 15:11:26.539  2134  2134 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
08-29 15:11:26.541  1034  2011 I ActivityManager: Killing 5652:com.lge.qremote/u0a112 (adj 15): empty #17
08-29 15:11:26.542  2134  2134 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29997
08-29 15:11:26.545   338   352 E GBMv2   : DFP En is all cleared set to be enabled
08-29 15:11:26.545   338   352 E GBMv2   : Set value is all cleared set the max
08-29 15:11:26.545   338   352 I GBMv2   : DFP Enabled. Ignore VFP set
08-29 15:11:26.563  6795  6795 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-29 15:11:26.563  6795  6795 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-29 15:11:26.564  6795  6795 I UEI.SmartControl: QS saving settings...
08-29 15:11:26.565  6795  6795 D UEI.SmartControl: IR Blaster version: 25672567
08-29 15:11:26.582  6795  6824 D UEI.SmartControl: serial port data available: 4
,08-29 15:11:26.594  1034  1889 W libprocessgroup: failed to open /acct/uid_10112/pid_5652/cgroup.procs: No such file or directory
,08-29 15:11:26.614  6795  6795 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-29 15:11:26.615  6795  6795 E UEI.SmartControl: Services init done
08-29 15:11:26.615  6795  6795 D UEI.SmartControl: QS Service init finished
08-29 15:11:26.616  6795  6795 D UEI.SmartControl: QS Service version name: 2.1.91
08-29 15:11:26.616  6795  6795 D UEI.SmartControl: QS Service version code: 201091
08-29 15:11:26.617  6795  6795 D UEI.SmartControl: Service requested: Control
08-29 15:11:26.617  6795  6827 I UEI.SmartControl: Device manager: loading config....
08-29 15:11:26.618  6795  6827 D UEI.SmartControl: ----------- loading internal config...
08-29 15:11:26.622  6795  6827 E UEI.SmartControl: Loading SETTINGS...
08-29 15:11:26.622  6795  6795 D UEI.SmartControl: Request IControl service: devices are loaded...
08-29 15:11:26.623  6795  6795 D UEI.SmartControl: Service.onUnbind: IControl
08-29 15:11:26.623  6795  6795 D UEI.SmartControl: Service.onDestroy
08-29 15:11:26.623  6795  6795 D UEI.SmartControl: Lock is in USE false
08-29 15:11:26.623  6795  6795 D UEI.SmartControl: unbind internal service
08-29 15:11:26.623  6795  6795 D serial_port: close(fd = 25)
08-29 15:11:26.627  6795  6795 I UEI.SmartControl: Serial port is closed.
08-29 15:11:26.627  6795  6795 I UEI.SmartControl: Serial port is closed.
08-29 15:11:26.627  6795  6795 D UEI.SmartControl: Blaster closed
08-29 15:11:26.627  6795  6795 D UEI.SmartControl: Shut down QS...
08-29 15:11:26.627  6795  6795 D UEI.SmartControl: Stopping QS lib
08-29 15:11:26.627  6795  6795 D UEI.SmartControl: QS lib stop result = true
08-29 15:11:26.627  6795  6795 D UEI.SmartControl: Stopped QS lib
,08-29 15:11:26.628  6795  6795 D UEI.SmartControl: Stopped file observer...
08-29 15:11:26.628  6795  6795 D UEI.SmartControl: QS shutdown complete
08-29 15:11:26.628  6795  6795 D UEI.SmartControl: QS Service created
08-29 15:11:26.633  6795  6826 I UEI.SmartControl: Notify AllClients services are ready: 11
08-29 15:11:26.633  6795  6826 D UEI.SmartControl: -----service ready thread exits
08-29 15:11:26.637  6795  6795 I UEI.SmartControl: Service initServices...
08-29 15:11:26.638  6795  6795 D UEI.SmartControl: QS start get config
,08-29 15:11:26.645  6795  6827 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-29 15:11:26.671  6671  6818 W jxcore-log: Initializing JXcore engine
08-29 15:11:26.671  6671  6818 W jxcore-log: JXcore engine is ready
,08-29 15:11:26.734  6818  6818 W Thread-757: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[10577]" dev="sockfs" ino=10577 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-29 15:11:26.734  6818  6818 W Thread-757: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-29 15:11:26.734  6818  6818 W Thread-757: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[9708]" dev="sockfs" ino=9708 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-29 15:11:26.734  6818  6818 W Thread-757: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-29 15:11:26.734  6818  6818 W Thread-757: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[29289]" dev="sockfs" ino=29289 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-29 15:11:26.767  6671  6818 W jxcore-log: Starting JXcore engine
,08-29 15:11:26.871  6795  6795 I UEI.SmartControl: Supports setup maps: true
,08-29 15:11:26.891  6671  6818 W jxcore-log: Platform android
08-29 15:11:26.891  6671  6818 W jxcore-log: 
08-29 15:11:26.891  6671  6818 W jxcore-log: Process ARCH arm
08-29 15:11:26.891  6671  6818 W jxcore-log: 
,08-29 15:11:26.893  6795  6795 D UEI.SmartControl: QS start statue = true Error code = 0
08-29 15:11:26.893  6795  6795 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-29 15:11:26.893  6795  6795 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-29 15:11:26.893  6795  6795 I UEI.SmartControl: ### init IR Blaster...
,08-29 15:11:26.898  6795  6795 D serial_port: Configuring serial port
08-29 15:11:26.898  6795  6795 E UEI.SmartControl: UEIBLaster setting for 616
08-29 15:11:26.898  6795  6795 I UEI.SmartControl: Setting serial record hearder size = 2
08-29 15:11:26.898  6795  6795 I UEI.SmartControl: configuring settings for MAXQ616
08-29 15:11:26.898  6795  6795 I UEI.SmartControl: Get version...
08-29 15:11:26.916  6795  6830 D UEI.SmartControl: serial port data available: 21
,08-29 15:11:26.942  6795  6795 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-29 15:11:26.942  6795  6795 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-29 15:11:26.943  6795  6795 I UEI.SmartControl: QS saving settings...
,08-29 15:11:26.943  6795  6795 D UEI.SmartControl: IR Blaster version: 25672567
08-29 15:11:26.962  6795  6830 D UEI.SmartControl: serial port data available: 4
,08-29 15:11:26.994  6795  6795 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-29 15:11:26.995  6795  6839 I UEI.SmartControl: Device manager: loading config....
08-29 15:11:26.996  6795  6839 D UEI.SmartControl: ----------- loading internal config...
08-29 15:11:27.000  6795  6795 E UEI.SmartControl: Services init done
08-29 15:11:27.000  6795  6795 D UEI.SmartControl: QS Service init finished
08-29 15:11:27.002  6795  6795 D UEI.SmartControl: QS Service version name: 2.1.91
08-29 15:11:27.002  6795  6795 D UEI.SmartControl: QS Service version code: 201091
08-29 15:11:27.003  6795  6839 E UEI.SmartControl: Loading SETTINGS...
08-29 15:11:27.004  6795  6795 D UEI.SmartControl: Service requested: Control
08-29 15:11:27.005  1034  1957 I ActivityManager: Killing 5871:com.google.android.talk/u0a72 (adj 15): empty #17
08-29 15:11:27.012  6795  6839 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-29 15:11:27.034  6795  6838 I UEI.SmartControl: Notify AllClients services are ready: 0
08-29 15:11:27.035  6795  6838 D UEI.SmartControl: -----service ready thread exits
,08-29 15:11:27.098  6671  6818 I jxcore-log: JXcore Cordova bridge is ready!
08-29 15:11:27.098  6671  6818 I jxcore-log: 
08-29 15:11:27.099  6671  6818 W jxcore-log: JXcore engine is started
,08-29 15:11:27.106  1034  1560 W libprocessgroup: failed to open /acct/uid_10072/pid_5871/cgroup.procs: No such file or directory
08-29 15:11:27.109  6795  6795 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@130f6700 that was originally bound here
08-29 15:11:27.109  6795  6795 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@130f6700 that was originally bound here
08-29 15:11:27.109  6795  6795 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
08-29 15:11:27.109  6795  6795 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
08-29 15:11:27.109  6795  6795 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
08-29 15:11:27.109  6795  6795 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
08-29 15:11:27.109  6795  6795 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
08-29 15:11:27.109  6795  6795 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
08-29 15:11:27.109  6795  6795 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
08-29 15:11:27.109  6795  6795 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
08-29 15:11:27.109  6795  6795 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
08-29 15:11:27.109  6795  6795 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
08-29 15:11:27.109  6795  6795 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
08-29 15:11:27.109  6795  6795 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:11:27.109  6795  6795 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
08-29 15:11:27.109  6795  6795 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 15:11:27.109  6795  6795 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 15:11:27.109  6795  6795 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 15:11:27.109  6795  6795 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 15:11:27.109  6795  6795 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 15:11:27.110  6795  6795 D UEI.SmartControl: Internal service binding...
08-29 15:11:27.110  6671  6794 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-29 15:11:27.114  6671  6671 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-29 15:11:27.624  6795  6829 D UEI.SmartControl: Internal timer expired: 2
,08-29 15:11:28.187   330   415 I ThermalEngine: Thermal-Server: Thermal received msg from  override
,08-29 15:11:28.194  3182  6848 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-29 15:11:29.262  6621  6621 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-29 15:11:29.263  1034  1991 I ActivityManager: Killing 6303:com.android.calendar/u0a13 (adj 15): empty #17
08-29 15:11:29.334  1034  2034 W libprocessgroup: failed to open /acct/uid_10013/pid_6303/cgroup.procs: No such file or directory
,08-29 15:11:30.264  6621  6712 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-29 15:11:30.988  6795  6807 E UEI.SmartControl: file observer is disposed!
,08-29 15:11:31.994  6795  6840 D UEI.SmartControl: Internal timer expired: 3
08-29 15:11:31.994  6795  6840 D UEI.SmartControl: unbind internal service
,08-29 15:11:32.003  6795  6795 D UEI.SmartControl: Service.onUnbind: IControl
08-29 15:11:32.006  6795  6835 D serial_port: close(fd = 24)
08-29 15:11:32.009  6795  6795 D UEI.SmartControl: Service.onDestroy
08-29 15:11:32.009  6795  6795 D UEI.SmartControl: Lock is in USE false
08-29 15:11:32.009  6795  6795 D UEI.SmartControl: unbind internal service
,08-29 15:11:32.014  6795  6835 I UEI.SmartControl: Serial port is closed.
08-29 15:11:32.014  6795  6795 I UEI.SmartControl: Serial port is closed.
08-29 15:11:32.014  6795  6795 I UEI.SmartControl: Serial port is closed.
08-29 15:11:32.014  6795  6795 D UEI.SmartControl: Blaster closed
08-29 15:11:32.014  6795  6795 D UEI.SmartControl: Shut down QS...
08-29 15:11:32.014  6795  6795 D UEI.SmartControl: Stopping QS lib
08-29 15:11:32.014  6795  6795 D UEI.SmartControl: QS lib stop result = true
08-29 15:11:32.014  6795  6795 D UEI.SmartControl: Stopped QS lib
08-29 15:11:32.014  6795  6795 D UEI.SmartControl: QS shutdown complete
08-29 15:11:32.703  1801  6508 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-29 15:11:32.707   310  6852 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-29 15:11:32.707   310  6852 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-29 15:11:32.707   310  6852 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-29 15:11:36.544  2134  2134 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19996
,08-29 15:11:37.229  6671  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-29 15:11:37.229  6671  6818 I jxcore-log: 
,08-29 15:11:37.232  6671  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-29 15:11:37.232  6671  6818 I jxcore-log: 
08-29 15:11:37.237  6671  6818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 15:11:37.237  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:37.237  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 15:11:37.237  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:11:37.237  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:11:37.237  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 15:11:37.237  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 15:11:37.237  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 15:11:37.239  6671  6818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 15:11:37.241  6671  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-29 15:11:37.241  6671  6818 I jxcore-log: 
08-29 15:11:37.243  6671  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-29 15:11:37.243  6671  6818 I jxcore-log: 
,08-29 15:11:37.747  6671  6818 D executeNativeTests: Running unit tests
,08-29 15:11:37.828  6671  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 15:11:37.828  6671  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30628ad7 added. We now have 2 listener(s)
,08-29 15:11:37.828  1034  1962 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-29 15:11:37.830  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17",
,08-29 15:11:37.830  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
,08-29 15:11:37.830  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
,08-29 15:11:37.830  6671  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 15:11:37.830  6671  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@198ccfc4 added. We now have 2 listener(s),
,08-29 15:11:37.830  6671  6818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 15:11:37.830  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 15:11:37.832  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 15:11:37.834  6671  6818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 15:11:37.834  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true,
08-29 15:11:37.834  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 15:11:37.834  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:11:37.834  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:11:37.834  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 15:11:37.834  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 15:11:37.834  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 15:11:37.834  1034  1112 I ActivityManager: Waited long enough for: ServiceRecord{c48f9a7 u0 com.google.android.gms/.wearable.service.WearableService}
08-29 15:11:37.835  6671  6818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 15:11:37.835  6671  6818 D io.jxcore.node.ConnectivityMonitor: start: OK,
08-29 15:11:37.838  6671  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 15:11:37.840  6671  6818 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 15:11:37.840  6671  6818 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 15:11:37.842  6671  6818 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-29 15:11:37.843  6671  6818 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-29 15:11:37.843  6671  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 15:11:37.843  6671  6818 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 15:11:37.843  6671  6818 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-29 15:11:37.845  6671  6818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:11:37.845  6671  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:11:37.846  6671  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:11:37.848  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:37.848  6671  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:11:37.849  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:37.849  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:11:37.849  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 15:11:37.849  6671  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30628ad7 removed from the list
08-29 15:11:37.849  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:37.849  6671  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@198ccfc4 removed from the list
08-29 15:11:37.851  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:37.851  6671  6818 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:11:37.851  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:37.852  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:37.852  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 15:11:37.852  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:11:37.852  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:11:37.852  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:37.853  6671  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@198ccfc4 not in the list
08-29 15:11:37.855  6671  6818 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-29 15:11:37.855  6671  6818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:11:37.855  6671  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:11:37.855  6671  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 15:11:37.856  6671  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:11:37.856  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:37.856  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:37.856  6671  6818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30628ad7 not in the list
08-29 15:11:37.856  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:37.856  6671  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@198ccfc4 not in the list
08-29 15:11:37.856  6671  6818 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:11:37.856  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:37.856  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:37.856  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:37.856  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:37.857  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:11:37.857  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:11:37.857  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:37.857  6671  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@198ccfc4 not in the list
08-29 15:11:37.864  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 15:11:37.864  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 15:11:37.864  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 15:11:37.864  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 15:11:37.864  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 15:11:37.864  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 15:11:37.864  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 15:11:37.864  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 15:11:37.864  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 15:11:37.864  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 15:11:37.864  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 15:11:37.864  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 15:11:37.864  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-29 15:11:37.864  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 15:11:37.864  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 15:11:37.864  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 15:11:37.864  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 15:11:37.865  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 15:11:37.865  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 15:11:37.865  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 15:11:37.865  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 15:11:37.865  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 15:11:37.865  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 15:11:37.865  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 15:11:37.865  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 15:11:37.865  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 15:11:37.865  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 15:11:37.865  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 15:11:37.865  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 15:11:37.865  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 15:11:37.865  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 15:11:37.865  6671  6818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:11:37.865  6671  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:11:37.865  6671  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:11:37.866  6671  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:11:37.866  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:37.866  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:37.866  6671  6818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30628ad7 not in the list
08-29 15:11:37.866  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:37.866  6671  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@198ccfc4 not in the list
08-29 15:11:37.866  6671  6818 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:11:37.866  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:37.866  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:37.866  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:37.866  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:37.868  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:11:37.868  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:11:37.868  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:37.868  6671  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@198ccfc4 not in the list
08-29 15:11:37.870  6671  6818 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 15:11:37.871  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 15:11:37.873  6671  6818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 15:11:37.873  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:37.873  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 15:11:37.873  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:11:37.873  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:11:37.873  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 15:11:37.873  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 15:11:37.873  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 15:11:37.874  6671  6818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 15:11:37.874  6671  6818 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 15:11:37.875  6671  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 15:11:37.875  6671  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 15:11:37.875  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 15:11:37.875  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 15:11:37.875  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:37.875  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 15:11:37.877  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:37.878  6671  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 15:11:37.879  1034  1889 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 15:11:37.885  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 15:11:37.891  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 15:11:37.893  6671  6818 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-29 15:11:37.894  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 15:11:37.895  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:11:37.896  6671  6818 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-29 15:11:37.896  6671  6818 I io.jxcore.node.ConnectionHelper: start: OK
08-29 15:11:37.898  6671  6818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:11:37.898  6671  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:11:37.898  6671  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:11:37.898  6671  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:11:37.898  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:37.898  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:11:37.898  6671  6818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30628ad7 not in the list
08-29 15:11:37.898  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:37.898  6671  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@198ccfc4 not in the list
08-29 15:11:37.898  6671  6818 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:11:37.898  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:37.899  6671  6818 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 15:11:37.988  1034  1922 I art     : Explicit concurrent mark sweep GC freed 21779(1120KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 1.472ms total 83.919ms
,08-29 15:11:37.994  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 15:11:37.996  6671  6818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 15:11:37.996  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:37.996  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 15:11:37.996  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:11:37.996  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:11:37.996  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 15:11:37.996  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 15:11:37.996  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 15:11:37.997  6671  6818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 15:11:37.997  6671  6818 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 15:11:37.998  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:37.999  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:37.999  6671  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 15:11:37.999  6671  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 15:11:37.999  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 15:11:37.999  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 15:11:37.999  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 15:11:38.002  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 15:11:38.003  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:11:38.004  6671  6818 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-29 15:11:38.004  6671  6818 I io.jxcore.node.ConnectionHelper: start: OK
08-29 15:11:38.005  6671  6818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:11:38.005  6671  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:11:38.005  6671  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:11:38.006  6671  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:11:38.006  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:38.006  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:11:38.006  6671  6818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30628ad7 not in the list
08-29 15:11:38.006  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:38.006  6671  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@198ccfc4 not in the list
08-29 15:11:38.006  6671  6818 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:11:38.006  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:38.006  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:38.006  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:38.007  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:11:38.007  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:11:38.008  6671  6818 D BluetoothLeScanner: could not find callback wrapper
08-29 15:11:38.008  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 15:11:38.008  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:38.008  6671  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@198ccfc4 not in the list
08-29 15:11:38.009  6671  6818 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 15:11:38.010  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 15:11:38.012  6671  6818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 15:11:38.012  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:38.012  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 15:11:38.012  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:11:38.012  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:11:38.012  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 15:11:38.012  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-,29 15:11:38.012  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 15:11:38.013  6671  6818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 15:11:38.013  6671  6818 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 15:11:38.014  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:38.015  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:38.016  6671  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 15:11:38.016  6671  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 15:11:38.016  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 15:11:38.016  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 15:11:38.016  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 15:11:38.018  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 15:11:38.019  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:11:38.019  6671  6818 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-29 15:11:38.020  6671  6818 I io.jxcore.node.ConnectionHelper: start: OK
08-29 15:11:38.020  6671  6818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:11:38.020  6671  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:11:38.020  6671  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:11:38.020  6671  6818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:11:38.021  6671  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:11:38.021  6671  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:11:38.021  6671  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:11:38.021  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:38.021  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:11:38.021  6671  6818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30628ad7 not in the list
08-29 15:11:38.021  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:38.021  6671  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@198ccfc4 not in the list
08-29 15:11:38.021  6671  6818 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:11:38.021  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:38.021  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:38.021  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 l,istener(s) left
08-29 15:11:38.022  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:11:38.022  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:11:38.022  6671  6818 D BluetoothLeScanner: could not find callback wrapper
08-29 15:11:38.022  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 15:11:38.022  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:38.022  6671  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@198ccfc4 not in the list
08-29 15:11:38.023  6671  6818 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-29 15:11:38.023  6671  6818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:11:38.023  6671  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:11:38.023  6671  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:11:38.023  6671  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:11:38.023  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:38.023  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:38.023  6671  6818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30628ad7 not in the list
08-29 15:11:38.023  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:38.023  6671  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@198ccfc4 not in the list
08-29 15:11:38.024  6671  6818 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 15:11:38.024  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:38.024  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:38.024  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:38.024  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:38.024  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:11:38.024  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 15:11:38.025  6671  6818 D BluetoothLeScanner: could not find callback wrapper
08-29 15:11:38.025  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 15:11:38.026  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:38.026  6671  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@198ccfc4 not in the list
08-29 15:11:38.026  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 15:11:38.026  6671  6818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:11:38.026  6671  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:11:38.026  6671  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:11:38.027  6671  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:11:38.027  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:38.027  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:38.027  6671  6818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30628ad7 not in the list
08-29 15:11:38.027  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:38.027  6671  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@198ccfc4 not in the list
08-29 15:11:38.027  6671  6818 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:11:38.027  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:38.027  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:38.027  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:38.027  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:38.028  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:11:38.028  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:11:38.028  6671  6818 D BluetoothLeScanner: could not find callback wrapper
08-29 15:11:38.028  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 15:11:38.028  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:38.028  6671  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@198ccfc4 not in the list
08-29 15:11:38.029  6671  6818 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-29 15:11:38.029  6671  6818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:11:38.029  6671  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:11:38.029  6671  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already mat,ches the desired outcome of this operation, skipping...
08-29 15:11:38.029  6671  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:11:38.029  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:38.029  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:38.029  6671  6818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30628ad7 not in the list
08-29 15:11:38.029  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:38.029  6671  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@198ccfc4 not in the list
08-29 15:11:38.029  6671  6818 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:11:38.029  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:38.029  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:38.029  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:38.029  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:38.030  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 15:11:38.030  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:11:38.030  6671  6818 D BluetoothLeScanner: could not find callback wrapper
08-29 15:11:38.030  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 15:11:38.030  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:38.030  6671  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@198ccfc4 not in the list
08-29 15:11:38.031  6671  6818 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,08-29 15:11:38.031  6671  6818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:11:38.031  6671  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:11:38.031  6671  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:11:38.032  6671  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 15:11:38.032  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:38.032  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:38.032  6671  6818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30628ad7 not in the list
08-29 15:11:38.032  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 15:11:38.032  6671  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@198ccfc4 not in the list
08-29 15:11:38.032  6671  6818 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:11:38.032  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-29 15:11:38.032  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:38.032  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-29 15:11:38.032  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:38.032  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 15:11:38.032  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:11:38.033  6671  6818 D BluetoothLeScanner: could not find callback wrapper
08-29 15:11:38.033  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 15:11:38.033  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:38.033  6671  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@198ccfc4 not in the list,
08-29 15:11:38.033  6671  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 15:11:38.034  6671  6818 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 15:11:38.034  6671  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 15:11:38.034  6671  6818 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 15:11:38.034  6671  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-29 15:11:38.034  6671  6818 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 15:11:38.035  6671  6818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:11:38.035  6671  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
08-29 15:11:38.035  6671  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:11:38.035  6671  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:11:38.035  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:38.035  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:38.035  6671  6818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30628ad7 not in the list,
08-29 15:11:38.035  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:38.035  6671  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@198ccfc4 not in the list
08-29 15:11:38.035  6671  6818 D io.jxcore.node.ConnectivityMonitor: stop,
08-29 15:11:38.035  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:38.035  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:38.035  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:38.035  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:38.036  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 15:11:38.036  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:11:38.037  6671  6818 D BluetoothLeScanner: could not find callback wrapper
08-29 15:11:38.037  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 15:11:38.037  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-29 15:11:38.037  6671  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@198ccfc4 not in the list
08-29 15:11:38.038  6671  6818 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 15:11:38.038  6671  6818 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 15:11:38.038  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 15:11:38.040  6671  6818 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55,
,08-29 15:11:38.040  6671  6818 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-29 15:11:38.040  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 15:11:38.040  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 15:11:38.040  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 15:11:38.040  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310],
08-29 15:11:38.040  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 15:11:38.040  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 15:11:38.040  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 15:11:38.040  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 15:11:38.040  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810],
08-29 15:11:38.040  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 15:11:38.040  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 15:11:38.040  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 15:11:38.040  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 15:11:38.040  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-29 15:11:38.040  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 15:11:38.040  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 15:11:38.040  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 15:11:38.040  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-29 15:11:38.041  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 15:11:38.041  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 15:11:38.041  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 15:11:38.041  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 15:11:38.041  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210],
08-29 15:11:38.041  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310],
08-29 15:11:38.041  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 15:11:38.041  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 15:11:38.041  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 15:11:38.041  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-29 15:11:38.041  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 15:11:38.041  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 15:11:38.041  6671  6818 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-29 15:11:38.041  6671  6818 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 15:11:38.041  6671  6818 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,08-29 15:11:38.043  6671  6818 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 15:11:38.043  6671  6818 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 15:11:38.043  6671  6818 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-29 15:11:38.043  6671  6818 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 15:11:38.043  6671  6818 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-29 15:11:38.043  6671  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-29 15:11:38.045  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-29 15:11:38.045  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-29 15:11:38.046  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-29 15:11:38.047  6671  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,08-29 15:11:38.047  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-29 15:11:38.048  6671  6818 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,08-29 15:11:38.049  6671  6818 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 15:11:38.049  6671  6818 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-29 15:11:38.049  6671  6818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:11:38.049  6671  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:11:38.049  6671  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:11:38.049  6671  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:11:38.049  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:38.049  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:38.050  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-29 15:11:38.050  6671  6818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30628ad7 not in the list
08-29 15:11:38.050  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:38.050  6671  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@198ccfc4 not in the list
08-29 15:11:38.050  6671  6818 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:11:38.050  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:38.050  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:38.050  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:38.050  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:38.051  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:11:38.051  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:11:38.052  6671  6818 D BluetoothLeScanner: could not find callback wrapper
08-29 15:11:38.052  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 15:11:38.052  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:38.052  6671  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@198ccfc4 not in the list
08-29 15:11:38.052  6671  6818 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-29 15:11:38.052  6671  6818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:11:38.053  6671  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:11:38.053  6671  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:11:38.053  6671  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:11:38.053  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:38.053  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:38.053  6671  6818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30628ad7 not in the list
08-29 15:11:38.053  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:38.053  6671  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@198ccfc4 not in the list
08-29 15:11:38.053  6671  6818 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:11:38.053  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:38.053  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:38.053  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably a,lready removed
08-29 15:11:38.053  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:38.054  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:11:38.054  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:11:38.054  6671  6818 D BluetoothLeScanner: could not find callback wrapper
08-29 15:11:38.054  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 15:11:38.054  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:38.054  6671  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@198ccfc4 not in the list
08-29 15:11:38.055  6671  6818 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-29 15:11:38.055  6671  6818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:11:38.055  6671  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:11:38.055  6671  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:11:38.056  6671  6853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 821)
08-29 15:11:38.064  6671  6854 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 821
08-29 15:11:38.064  6671  6854 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 821),
08-29 15:11:38.064  6671  6854 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 821)
08-29 15:11:38.065  6671  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:11:38.065  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:38.065  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:38.065  6671  6818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30628ad7 not in the list
08-29 15:11:38.065  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-29 15:11:38.065  6671  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@198ccfc4 not in the list
08-29 15:11:38.065  6671  6818 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:11:38.065  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:38.065  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:38.065  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 15:11:38.065  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:38.066  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:11:38.066  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 15:11:38.066  6671  6818 D BluetoothLeScanner: could not find callback wrapper
08-29 15:11:38.066  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 15:11:38.066  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:38.066  6671  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@198ccfc4 not in the list
08-29 15:11:38.067  6671  6818 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-29 15:11:38.067  6671  6818 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-29 15:11:38.067  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 15:11:38.067  6671  6818 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-29 15:11:38.067  6671  6818 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 15:11:38.067  6671  6818 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-29 15:11:38.067  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 15:11:38.067  6671  6818 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-29 15:11:38.067  6671  6818 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 15:11:38.067  6671  6818 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 15:11:38.067  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 15:11:38.067  6671  6818 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-29 15:11:38.067  6671  6818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:11:38.067  6671  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:11:38.067  6671  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:11:38.068  6671  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:11:38.068  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:38.068  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:38.068  6671  6818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30628ad7 not in the list
08-29 15:11:38.068  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:38.068  6671  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@198ccfc4 not in the list
08-29 15:11:38.068  6671  6818 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:11:38.068  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given lis,tener does not exist in the list - probably already removed
08-29 15:11:38.068  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:38.068  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:38.068  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:38.069  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:11:38.069  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:11:38.069  6671  6818 D BluetoothLeScanner: could not find callback wrapper,
,08-29 15:11:38.069  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 15:11:38.069  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:38.069  6671  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@198ccfc4 not in the list
08-29 15:11:38.070  6671  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 15:11:38.070  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:38.070  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:38.070  6671  6818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30628ad7 not in the list
08-29 15:11:38.070  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:38.070  6671  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@198ccfc4 not in the list
08-29 15:11:38.070  6671  6818 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:11:38.070  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:38.070  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:38.070  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:38.070  6671  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@198ccfc4 not in the list
08-29 15:11:38.070  6671  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:11:38.070  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:38.070  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:38.070  6671  6818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30628ad7 not in the list
08-29 15:11:38.070  6671  6818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:11:38.070  6671  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:11:38.070  6671  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:11:38.071  6671  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:11:38.071  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:38.071  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:38.071  6671  6818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30628ad7 not in the list
08-29 15:11:38.071  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:38.071  6671  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@198ccfc4 not in the list
08-29 15:11:38.071  6671  6818 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:11:38.071  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:38.071  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:38.071  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: rele,ase: The given listener does not exist in the list - probably already removed
08-29 15:11:38.071  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:38.071  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:11:38.072  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:11:38.072  6671  6818 D BluetoothLeScanner: could not find callback wrapper
08-29 15:11:38.072  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 15:11:38.072  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:38.072  6671  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@198ccfc4 not in the list
08-29 15:11:38.073  6671  6818 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-29 15:11:38.074  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 15:11:38.074  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-29 15:11:38.074  6671  6818 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-29 15:11:38.074  6671  6818 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-29 15:11:38.075  6671  6671 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-29 15:11:38.075  6671  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 15:11:38.075  6671  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 15:11:38.076  6671  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:11:38.076  6671  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-29 15:11:38.076  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-29 15:11:38.076  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-29 15:11:38.076  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:38.076  6671  6818 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-29 15:11:38.076  6671  6671 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-29 15:11:38.076  6671  6818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30628ad7 not in the list
08-29 15:11:38.076  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:38.076  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 15:11:38.076  6671  6818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 15:11:38.076  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 15:11:38.077  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 15:11:38.077  6671  6818 D BluetoothLeScanner: could not find callback wrapper
08-29 15:11:38.077  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 15:11:38.077  6671  6818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 15:11:38.077  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the li,st - probably already removed
08-29 15:11:38.077  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:38.078  6671  6818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 15:11:38.078  6671  6671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 15:11:38.078  6671  6671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 15:11:38.078  6671  6671 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 15:11:38.078  6671  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@198ccfc4 not in the list
08-29 15:11:38.079  6671  6818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:11:38.079  6671  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:11:38.079  6671  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:11:38.079  6671  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:11:38.079  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:38.079  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:38.079  6671  6818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30628ad7 not in the list
08-29 15:11:38.079  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:38.079  6671  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@198ccfc4 not in the list
08-29 15:11:38.079  6671  6818 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:11:38.079  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:38.079  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:38.079  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:38.079  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:38.080  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:11:38.080  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:11:38.080  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:38.080  6671  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@198ccfc4 not in the list
08-29 15:11:38.080  6671  6818 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-29 15:11:38.081  6671  6818 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 15:11:38.081  6671  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 15:11:38.082  6671  6818 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 15:11:38.082  6671  6818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:11:38.082  6671  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:11:38.082  6671  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:11:38.082  6671  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:11:38.082  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:38.082  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:38.082  6671  6818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30628ad7 not in the list
08-29 15:11:38.082  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:38.082  6671  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@198ccfc4 not in the list
08-29 15:11:38.082  6671  6818 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:11:38.082  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:38.082  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:38.082  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:38.082  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:38.083  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:11:38.083  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:11:38.083  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:38.083  6671  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@198ccfc4 not in the list
08-29 15:11:38.084  1034  1560 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 15:11:38.085  1034  2032 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 15:11:38.085  1034  1962 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 15:11:38.086  6671  6818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:11:38.086  6671  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:11:38.086  6671  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:11:38.086  6671  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:11:38.086  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:38.086  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:38.086  6671  6818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30628ad7 not in the list
08-29 15:11:38.086  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:38.086  6671  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@198ccfc4 not in the list
08-29 15:11:38.086  6671  6818 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:11:38.086  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:38.086  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:38.086  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:38.086  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:38.087  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:11:38.087  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:11:38.087  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:38.087  6671  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@198ccfc4 not in the list
08-29 15:11:38.088  6671  6818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:11:38.088  6671  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:11:38.088  6671  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:11:38.088  6671  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:11:38.088  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:38.088  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:38.089  6671  6818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30628ad7 not in the list
08-29 15:11:38.089  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:38.089  6671  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@198ccfc4 not in the list
08-29 15:11:38.089  6671  6818 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:11:38.089  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:38.089  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:38.089  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:11:38.089  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:11:38.090  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:11:38.090  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:11:38.090  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:11:38.090  6671  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@198ccfc4 not in the list
,08-29 15:11:38.091  6671  6818 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-29 15:11:38.091  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 15:11:38.091  6671  6818 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-29 15:11:38.091  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 15:11:38.091  6671  6818 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-29 15:11:38.091  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 15:11:38.096  6671  6855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-29 15:11:38.096  6671  6855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-29 15:11:38.096  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 15:11:38.096  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-29 15:11:38.097  6671  6818 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-29 15:11:38.097  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 15:11:38.097  6671  6818 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-29 15:11:38.097  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 15:11:38.097  6671  6818 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-29 15:11:38.097  6671  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-29 15:11:38.097  6671  6671 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-29 15:11:38.098  6671  6818 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-29 15:11:38.098  6671  6818 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-29 15:11:38.133  6671  6818 W art     : No such thread id for suspend: 35
08-29 15:11:38.133  6671  6818 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-29 15:11:38.134  6671  6818 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-29 15:11:38.134  6671  6818 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-29 15:11:38.135  6671  6818 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-29 15:11:38.138  6671  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 15:11:38.138  6671  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1d15b665 added. We now have 2 listener(s)
08-29 15:11:38.138  6671  6818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 15:11:38.142  6671  6818 D BluetoothAdapter: enable(): BT is already enabled..!
08-29 15:11:38.144  1034  1049 D WifiServiceImplEx: setWifiEnabled: true pid=6671, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-29 15:11:38.145  1034  1049 D WifiService: setWifiEnabled: true pid=6671, uid=10118
08-29 15:11:38.145  1034  1049 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 15:11:38.147  6671  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 15:11:38.147  6671  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@36ef9f3a added. We now have 3 listener(s)
08-29 15:11:38.147  6671  6818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 15:11:38.151  6671  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 15:11:38.151  6671  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@766a7eb added. We now have 4 listener(s)
08-29 15:11:38.151  6671  6818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 15:11:38.153  6671  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 15:11:38.153  6671  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@38a14948 added. We now have 5 listener(s)
,08-29 15:11:38.153  6671  6818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 15:11:38.157  1034  1889 D WifiServiceImplEx: setWifiEnabled: false pid=6671, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-29 15:11:38.157  1034  1889 D WifiService: setWifiEnabled: false pid=6671, uid=10118
,08-29 15:11:38.157  1034  1889 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 15:11:38.160  6671  6853 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-29 15:11:38.160  6671  6853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 821)
,08-29 15:11:38.168  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-29 15:11:38.169  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 15:11:38.169  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-29 15:11:38.170  1034  1376 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-29 15:11:38.170  1034  1376 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-29 15:11:38.171  1034  1376 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-29 15:11:38.171  1034  1376 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-29 15:11:38.172  1034  1376 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-29 15:11:38.172  1034  1376 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-29 15:11:38.172  1034  1376 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 15:11:38.172  1034  1376 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-29 15:11:38.173  1034  1376 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 15:11:38.173  1034  1376 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-29 15:11:38.173  1034  2032 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 15:11:38.174  1034  2032 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@24534f09 mBinding = false
08-29 15:11:38.180  1034  1376 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-29 15:11:38.180  1034  1376 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-29 15:11:38.180  1034  1374 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:38.180  1034  1374 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:38.180  2722  2722 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-29 15:11:38.180  1034  1376 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-29 15:11:38.180  1034  1376 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 15:11:38.181  1034  1376 D WifiNative-wlan0: SET ps 1: returned true
08-29 15:11:38.181  1034  2828 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:38.181   310   892 D CommandListener: Clearing all IP addresses on wlan0
08-29 15:11:38.187  1034  1116 D BluetoothManagerService: Message: 2
08-29 15:11:38.188  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 15:11:38.188  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 15:11:38.188  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-29 15:11:38.189  1034  1116 D BluetoothManagerService: Sending off request.
08-29 15:11:38.191  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 15:11:38.191  3819  3838 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-29 15:11:38.192  3819  3900 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-29 15:11:38.192  3819  3900 D BluetoothAdapterProperties: Setting state to 13
08-29 15:11:38.192  3819  3900 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 15:11:38.193  3819  3900 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 15:11:38.193  3819  3900 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-29 15:11:38.194  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:11:38.194  6671  6818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 15:11:38.194  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:38.194  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 15:11:38.194  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:11:38.194  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:11:38.194  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 15:11:38.194  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 15:11:38.194  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 15:11:38.196  3819  3905 D BluetoothAdapterProperties: Scan Mode:20
08-29 15:11:38.196  3819  3900 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-29 15:11:38.197  1034  1116 D BluetoothManagerService: Message: 60
08-29 15:11:38.197  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-29 15:11:38.197  1034  1116 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-29 15:11:38.197  3819  3900 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-29 15:11:38.197  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:11:38.197  6671  6818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 15:11:38.197  6671  6818 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 15:11:38.198  3819  4237 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-29 15:11:38.198  3819  4237 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 15:11:38.198  3819  4237 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-29 15:11:38.198  3819  4237 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-29 15:11:38.198  3819  4237 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-29 15:11:38.198  3819  4237 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-29 15:11:38.198  3819  4237 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-29 15:11:38.198  3819  4237 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-29 15:11:38.199  3819  4238 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 15:11:,38.199  3819  4276 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 15:11:38.199  3819  4277 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 15:11:38.200  3819  4279 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 15:11:38.200  3819  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-29 15:11:38.200  3819  3999 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-29 15:11:38.201  6671  6671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:11:38.201  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:11:38.201  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:38.201  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 15:11:38.201  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:11:38.201  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 15:11:38.201  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 15:11:38.201  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 15:11:38.201  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 15:11:38.201  3819  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 15:11:38.201  3819  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 15:11:38.201  3819  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 15:11:38.201  3819  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 15:11:38.201  3819  3999 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 15:11:38.201  3819  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 15:11:38.201  3819  3999 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 15:11:38.201  3819  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 15:11:38.201  3819  3999 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 15:11:38.201  3819  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-29 15:11:38.201  3819  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-29 15:11:38.201  3819  3999 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-29 15:11:38.201  6671  6671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:11:38.201  6671  6671 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 15:11:38.204  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:11:38.207  6671  6671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:11:38.207  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:11:38.207  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:38.207  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 15:11:38.207  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:11:38.207  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 15:11:38.207  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 15:11:38.207  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 15:11:38.207  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 15:11:38.207  6671  6671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:11:38.207  6671  6671 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 15:11:38.209  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:38.210  1034  1452 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-29 15:11:38.211  1034  1452 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-29 15:11:38.215  1034  1957 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-29 15:11:38.215  1034  2826 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:38.215  1034  2826 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:38.215  1034  2826 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-29 15:11:38.215  1034  2826 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:38.215  1034  2826 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
08-29 15:11:38.219  1801  6508 W ConfigFetchTask: exception on config fetch: javax.net.ssl.SSLException: Read error: ssl=0xaf4f1800: I/O error during system call, Connection timed out
08-29 15:11:38.219  1801  6508 W ConfigFetchTask: javax.net.ssl.SSLException: Read error: ssl=0xaf4f1800: I/O error during system call, Connection timed out
08-29 15:11:38.219  1801  6508 W ConfigFetchTask: 	at com.android.org.conscrypt.NativeCrypto.SSL_read(Native Method)
08-29 15:11:38.219  1801  6508 W ConfigFetchTask: 	at com.android.org.conscrypt.OpenSSLSocketImpl$SSLInputStream.read(OpenSSLSocketImpl.java:674)
08-29 15:11:38.219  1801  6508 W ConfigFetchTask: 	at com.android.okio.Okio$2.read(Okio.java:113)
08-29 15:11:38.219  1801  6508 W ConfigFetchTask: 	at com.android.okio.RealBufferedSource.indexOf(RealBufferedSource.java:147)
08-29 15:11:38.219  1801  6508 W ConfigFetchTask: 	at com.android.okio.RealBufferedSource.readUtf8LineStrict(RealBufferedSource.java:94)
08-29 15:11:38.219  1801  6508 W ConfigFetchTask: 	at com.android.okhttp.internal.http.HttpConnection.readResponse(HttpConnection.java:175)
08-29 15:11:38.219  1801  6508 W ConfigFetchTask: 	at com.android.okhttp.internal.http.HttpTransport.readRespons,eHeaders(HttpTransport.java:101)
08-29 15:11:38.219  1801  6508 W ConfigFetchTask: 	at com.android.okhttp.internal.http.HttpEngine.readResponse(HttpEngine.java:616)
08-29 15:11:38.219  1801  6508 W ConfigFetchTask: 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:379)
08-29 15:11:38.219  1801  6508 W ConfigFetchTask: 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.getResponse(HttpURLConnectionImpl.java:323)
08-29 15:11:38.219  1801  6508 W ConfigFetchTask: 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.getResponseCode(HttpURLConnectionImpl.java:491)
08-29 15:11:38.219  1801  6508 W ConfigFetchTask: 	at com.android.okhttp.internal.http.DelegatingHttpsURLConnection.getResponseCode(DelegatingHttpsURLConnection.java:105)
08-29 15:11:38.219  1801  6508 W ConfigFetchTask: 	at com.android.okhttp.internal.http.HttpsURLConnectionImpl.getResponseCode(HttpsURLConnectionImpl.java:25)
08-29 15:11:38.219  1801  6508 W ConfigFetchTask: 	at com.google.android.gms.config.f.a(SourceFile:120)
08-29 15:11:38.219  1801  6508 W ConfigFetchTask: 	at com.google.android.gms.config.f.doInBackground(SourceFile:39)
08-29 15:11:38.219  1801  6508 W ConfigFetchTask: 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
08-29 15:11:38.219  1801  6508 W ConfigFetchTask: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 15:11:38.219  1801  6508 W ConfigFetchTask: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
08-29 15:11:38.219  1801  6508 W ConfigFetchTask: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
08-29 15:11:38.219  1801  6508 W ConfigFetchTask: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
08-29 15:11:38.219  1801  6508 W ConfigFetchTask: 	at java.lang.Thread.run(Thread.java:818)
,08-29 15:11:38.235  1034  1112 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6872 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-29 15:11:38.237  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 15:11:38.238  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 15:11:38.238  3819  3819 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 15:11:38.238  3819  3819 D BluetoothMapService: STATE_TURNING_OFF
08-29 15:11:38.239  3819  3819 V BtOppService: Receiver DISABLED_ACTION 
08-29 15:11:38.239  3819  3819 V BluetoothMapService: Handler(): got msg=4
08-29 15:11:38.239  3819  3819 D BluetoothMapService: MAP Service closeService in
08-29 15:11:38.239  3819  3819 D BluetoothMapMasInstance: MAP Service shutdown
08-29 15:11:38.239  3819  3819 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 15:11:38.239  3819  3819 V BluetoothMapService: MAP Service closeService out
08-29 15:11:38.239  3819  3819 I BtOppRfcommListener: stopping Accept Thread
08-29 15:11:38.239  3819  3819 V BtOppRfcommListener: close mBtServerSocket
08-29 15:11:38.239  3819  3819 V BtOppRfcommListener: waiting for thread to terminate
08-29 15:11:38.239  3819  4276 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 15:11:38.240  3819  3819 V BtOppRfcommListener: done waiting for thread to terminate
08-29 15:11:38.242  6671  6671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:11:38.242  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:11:38.242  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:38.242  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 15:11:38.242  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:11:38.242  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 15:11:38.242  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:11:38.242  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:11:38.242  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 15:11:38.243  6671  6671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:11:38.244  6671  6671 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 15:11:38.247  6671  6671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:11:38.247  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:11:38.247  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:38.247  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 15:11:38.247  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:11:38.247  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 15:11:38.247  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:11:38.247  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:11:38.247  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 15:11:38.247  6671  6671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:11:38.248  6671  6671 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 15:11:38.270  1034  1112 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6892 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-29 15:11:38.273  3819  3819 V BtOppService: onDestroy
08-29 15:11:38.273  1801  1801 I ConfigFetchService: fetch service done; releasing wakelock
08-29 15:11:38.274  1801  1801 I ConfigFetchService: stopping self
08-29 15:11:38.276  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-29 15:11:38.277  1925  1925 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-29 15:11:38.277  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:11:38.277  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:11:38.277  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 15:11:38.278  3819  3819 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-29 15:11:38.280  1034  1376 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 15:11:38.280  1034  1376 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 15:11:38.280  1034  1376 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 15:11:38.280  1034  1376 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 15:11:38.281  1034  1376 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 15:11:38.281  1034  1376 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 15:11:38.281  1034  1376 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-29 15:11:38.281  1034  1376 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 15:11:38.282  1034  1376 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 15:11:38.282  1034  1376 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 15:11:38.282  1034  1374 D LGWifiP2pService: InactiveState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:38.282  2198  2198 I ConfigService: onDestroy
08-29 15:11:38.282  1034  1374 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:38.282  1034  1374 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@144bf452
08-29 15:11:38.283  1034  1374 D LGWifiP2pService: P2pDisablingState
08-29 15:11:38.283  1034  1374 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:38.283  1034  1374 D LGWifiP2pService: p2p socket connection lost
08-29 15:11:38.283  1034  1374 D LGWifiP2pService: P2pDisabledState
,08-29 15:11:38.284  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-29 15:11:38.285  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:11:38.285  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:11:38.285  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 15:11:38.285  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 1
08-29 15:11:38.285  1034  1034 D RttService: SCAN_AVAILABLE : 1
08-29 15:11:38.285  1034  1542 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:38.286  1034  1541 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:38.286  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-29 15:11:38.286  1034  1452 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-29 15:11:38.286  1925  1925 D WfdsService: WifiP2pState is changed : false
08-29 15:11:38.286   310  6907 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-29 15:11:38.286  1034  1452 D DSQN    : disableDataServiceNotify
08-29 15:11:38.287  1925  2271 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-29 15:11:38.287  1034  1452 D DSQN    : stop dsqn bin
08-29 15:11:38.287  1925  2271 D WfdsService: Set the WFDS Monitor: false
08-29 15:11:38.287  1034  1376 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-29 15:11:38.287  1034  1114 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-29 15:11:38.287  1034  2826 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-29 15:11:38.287  1034  1374 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:38.287  1034  1374 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:38.287  1034  1376 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-29 15:11:38.287  2722  2722 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-29 15:11:38.288  1034  1376 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-29 15:11:38.288  1034  1376 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 15:11:38.288  1925  2271 D WfdsMonitor: WFDS Monitor is stopped
08-29 15:11:38.288  1034  1376 D WifiNative-wlan0: SET ps 1: returned true
08-29 15:11:38.288  1925  2271 D WfdsService: STATE : WfdsDisabledState - enter
08-29 15:11:38.288  1925  2755 D CtrlSupplicant: Received on exit socket, terminate
08-29 15:11:38.288  1925  2755 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-29 15:11:38.288  1925  2755 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-29 15:11:38.288  1925  2755 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-29 15:11:38.288  1925  2271 W WfdsService: DefaultState - msg [9445378] is not handled
08-29 15:11:38.288   310   892 D CommandListener: Clearing all IP addresses on wlan0
08-29 15:11:38.288  1925  2273 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-29 15:11:38.291  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-29 15:11:38.292  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:11:38.292  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:11,:38.292  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 15:11:38.293  1034  1452 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-29 15:11:38.293  1034  1376 D WifiNative-p2p0: doBoolean: TERMINATE
08-29 15:11:38.293  1034  1452 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 15:11:38.293  1034  1452 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 15:11:38.293  1034  1376 D WifiNative-p2p0: TERMINATE: returned true
08-29 15:11:38.294  1034  1376 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 15:11:38.294  1034  1376 E WifiStateMachine: useWiFiOffloading() : false
08-29 15:11:38.294  1034  1376 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 15:11:38.294  1034  1452 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 15:11:38.294  1034  1452 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-29 15:11:38.294  1587  2055 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-29 15:11:38.294  1034  1452 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-29 15:11:38.294  1034  1452 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-29 15:11:38.295  1034  1452 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-29 15:11:38.295  1034  2826 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:38.295  1034  2826 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:38.295  1034  2826 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-29 15:11:38.295  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-29 15:11:38.296  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-29 15:11:38.296  1034  1452 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-29 15:11:38.296  1034  1452 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-29 15:11:38.296  1034  1452 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-29 15:11:38.296  1034  1452 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 15:11:38.296  1034  1452 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 15:11:38.297  1034  1452 D NetworkManagementService: Removing idletimer
08-29 15:11:38.297  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 15:11:38.297  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 15:11:38.297  1836  1836 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 15:11:38.297  1034  1452 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:11:38.297  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-29 15:11:38.298  1034  1452 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-29 15:11:38.298  1034  1373 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-29 15:11:38.298  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 15:11:38.299  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-29 15:11:38.299  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-29 15:11:38.299  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-29 15:11:38.299  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-29 15:11:38.300  1034  1373 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-29 15:11:38.301  1034  1376 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 15:11:38.301  1034  1376 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 15:11:38.301  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-29 15:11:38.301  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-29 15:11:38.301  1034  1034 D LocSvc_java: updateNetworkState ,connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-29 15:11:38.301  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-29 15:11:38.303  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 15:11:38.303  1034  1034 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-29 15:11:38.306  6671  6671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:11:38.306  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:11:38.306  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:38.306  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 15:11:38.306  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 15:11:38.306  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 15:11:38.306  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:11:38.306  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:11:38.306  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 15:11:38.306  6671  6671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:11:38.306  6671  6671 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 15:11:38.308  6671  6671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:11:38.308  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:11:38.308  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:38.308  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 15:11:38.308  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 15:11:38.308  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 15:11:38.308  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:11:38.308  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:11:38.308  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 15:11:38.308  6671  6671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:11:38.308  6671  6671 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 15:11:38.320  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 15:11:38.320  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-29 15:11:38.321  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 15:11:38.326  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-29 15:11:38.326  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 15:11:38.326  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 15:11:38.327  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 15:11:38.328  6892  6892 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 15:11:38.328  6892  6892 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-29 15:11:38.328  6892  6892 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 15:11:38.329  6892  6892 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-29 15:11:38.329  6892  6892 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-29 15:11:38.330  6892  6892 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-29 15:11:38.340  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 15:11:38.341  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 15:11:38.341  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 15:11:38.352  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 15:11:38.352  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 15:11:38.353  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 15:11:38.367  2722  2722 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-29 15:11:38.367  2722  2722 I wpa_supplicant: monitor socket send errors count : 1
08-29 15:11:38.367  2722  2722 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1925-2\x00 that cannot receive messages
08-29 15:11:38.367  1034  2754 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-29 15:11:38.368  1034  2754 D WifiMonitor: Dropping event because (p2p0) is stopped
,08-29 15:11:38.379  6872  6872 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-29 15:11:38.379  6872  6872 W LG Account v2.2: No ProfileInfo entries
08-29 15:11:38.379  6872  6872 I LG Account v2.2: isEnabled: false
08-29 15:11:38.380  6872  6872 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-29 15:11:38.380  6872  6872 I Feature : [Lifetracker]Country: EU
08-29 15:11:38.380  6872  6872 I Feature : [Lifetracker]Operator: OPEN
08-29 15:11:38.380  6872  6872 I Feature : [Lifetracker]Ranking support: false
08-29 15:11:38.380  6872  6872 I Feature : [Lifetracker]Comfort support: false
08-29 15:11:38.380  6872  6872 I Feature : [Lifetracker]Accessory: true
08-29 15:11:38.380  6872  6872 I Feature : [Lifetracker]Health device: true
08-29 15:11:38.380  6872  6872 I Feature : [Lifetracker]Extra Pedometer: false
08-29 15:11:38.380  6872  6872 I Feature : [Lifetracker]Blood glucose device: false
08-29 15:11:38.380  6872  6872 I Feature : [Lifetracker]Device Number: 3
08-29 15:11:38.385  1034  2828 D DhcpStateMachine: StoppedState
08-29 15:11:38.385  1034  2828 D DhcpStateMachine: StoppedState{ when=-97ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:38.385  1034  1376 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-29 15:11:38.385  1034  1376 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,08-29 15:11:38.388  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 15:11:38.405  2722  2722 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 15:11:38.406  6892  6892 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-29 15:11:38.406  1034  2754 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-29 15:11:38.406  1034  2754 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 15:11:38.406  1034  2754 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 15:11:38.406  2722  2722 W wpa_supplicant: USIM:  scard_deinit function
08-29 15:11:38.406  1034  2754 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-29 15:11:38.406  1034  2754 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 15:11:38.406  1034  2754 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 15:11:38.407  1034  1116 D Tethering: InitialState.processMessage what=4
08-29 15:11:38.407  1034  1376 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=118659
08-29 15:11:38.407  1034  1376 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=118659
08-29 15:11:38.408  1034  1376 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=118659  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-29 15:11:38.408  1034  1376 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=118659  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-29 15:11:38.423  1034  1922 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6913 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-29 15:11:38.424  1034  1922 I ActivityManager: Killing 6226:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-29 15:11:38.455  1034  1116 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-29 15:11:38.459  1034  1376 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-29 15:11:38.459  1034  1376 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 15:11:38.460  3819  3819 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 15:11:38.461  3819  3819 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 15:11:38.461  3819  3819 V BluetoothPbapReceiver: ***********state = 13
08-29 15:11:38.462  1034  2011 W libprocessgroup: failed to open /acct/uid_10014/pid_6226/cgroup.procs: No such file or directory
08-29 15:11:38.462  3819  3819 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-29 15:11:38.464  2722  2722 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-29 15:11:38.464  1034  2754 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-29 15:11:38.465  1034  2754 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-29 15:11:38.465  1034  2754 D WifiMonitor: Disconnecting from the supplicant, no more events
08-29 15:11:38.465  1034  1376 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-29 15:11:38.469  1034  1116 D BluetoothManagerService: Message: 20
08-29 15:11:38.469  1034  1116 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6cad928:true
,08-29 15:11:38.472  3819  3819 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 15:11:38.472  3819  3819 V BluetoothPbapService: state: 13
08-29 15:11:38.472  3819  3819 V BluetoothPbapService: Pbap Service closeService in
08-29 15:11:38.475  3819  3819 V BluetoothPbapService: successfully stopped pbap service
08-29 15:11:38.475  3819  3819 V BluetoothPbapService: Pbap Service closeService out
08-29 15:11:38.475  3819  3819 V BluetoothPbapService: Pbap Service onDestroy
08-29 15:11:38.475  3819  3819 V BluetoothPbapService: Pbap Service closeService in
08-29 15:11:38.475  3819  3819 V BluetoothPbapService: Pbap Service closeService out
08-29 15:11:38.475  3819  3819 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-29 15:11:38.477  2198  2198 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 15:11:38.492  1034  1116 D BluetoothManagerService: Message: 30
,08-29 15:11:38.498  1034  1116 D BluetoothManagerService: Message: 30
08-29 15:11:38.500  6892  6892 D LocalBluetoothProfileManager: Adding local MAP profile
08-29 15:11:38.504  6892  6892 D BluetoothMap: Create BluetoothMap proxy object
,08-29 15:11:38.504  1034  1116 D BluetoothManagerService: Message: 30
08-29 15:11:38.509  1034  1116 D BluetoothManagerService: Message: 30
08-29 15:11:38.511  6892  6892 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-29 15:11:38.512  6892  6892 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-29 15:11:38.522  6913  6913 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-29 15:11:38.529  6892  6892 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
08-29 15:11:38.532  6892  6892 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-29 15:11:38.535  6913  6913 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-29 15:11:38.536  6913  6913 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 15:11:38.542  1034  1050 I ActivityManager: Killing 6285:com.android.defcontainer/u0a4 (adj 15): empty #17
08-29 15:11:38.579  6671  6671 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 15:11:38.632  1034  1957 W libprocessgroup: failed to open /acct/uid_10004/pid_6285/cgroup.procs: No such file or directory
,08-29 15:11:38.633  6892  6892 D DockEventReceiver: finishStartingService: stopping service
08-29 15:11:38.655  1034  1362 V AlarmManager: RTC_WAKEUP set : Alarm{315cde70 type 0 when 1472476298546 com.android.vending} when 1472476298546
,08-29 15:11:38.657  6892  6892 D BluetoothInputDevice: Proxy object connected
08-29 15:11:38.659  1034  1376 D WifiOffDelayIfNotUsed: stopMonitoring
08-29 15:11:38.659  1034  1376 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 15:11:38.659  1034  1376 E WifiStateMachine: useWiFiOffloading() : false
08-29 15:11:38.659  1034  1376 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 15:11:38.660  1925  1925 D WfdsService: Supplicant Connection state is changed : false
08-29 15:11:38.660  6892  6892 D HidProfile: Bluetooth service connected
08-29 15:11:38.660  1925  2271 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-29 15:11:38.660  1925  2271 D WfdsService: Set the WFDS Monitor: false
08-29 15:11:38.660  1925  2271 D WfdsMonitor: WFDS Monitor is stopped
08-29 15:11:38.663  6892  6892 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 15:11:38.665  6892  6892 D PanProfile: Bluetooth service connected
08-29 15:11:38.666  6892  6892 D BluetoothMap: Proxy object connected
,08-29 15:11:38.669  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 15:11:38.672  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-29 15:11:38.672  1034  1424 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-29 15:11:38.672  1034  1424 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-29 15:11:38.673  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-29 15:11:38.674  2473  2473 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 15:11:38.674  6671  6671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:11:38.674  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:11:38.674  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:38.674  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 15:11:38.674  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 15:11:38.674  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 15:11:38.674  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:11:38.674  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:11:38.674  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 15:11:38.677  6892  6892 D MapProfile: Bluetooth service connected
08-29 15:11:38.677  6892  6892 D BluetoothMap: getConnectedDevices()
08-29 15:11:38.677  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:38.678  6892  6892 D BluetoothMap: Bluetooth is Not enabled
08-29 15:11:38.679  6892  6892 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-29 15:11:38.700  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 15:11:38.729  1034  1957 V SIM_STK : Menu title from STK is T-Mobile
,08-29 15:11:38.736  6892  6892 D LgDataFeature: LgDataFeature() Constructor: none
08-29 15:11:38.736  6892  6892 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 15:11:38.745  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 15:11:38.747  6892  6892 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-29 15:11:38.751  6892  6892 D BluetoothPermissionRequest: onReceive
08-29 15:11:38.753  6892  6892 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-29 15:11:38.760  6892  6892 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 15:11:38.764  3819  3819 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-29 15:11:38.764  3819  3819 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-29 15:11:38.764  3819  3819 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-29 15:11:38.815  1034  1889 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6941 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-29 15:11:38.818  3819  3819 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 15:11:38.818  3819  3819 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-29 15:11:38.820  3819  3819 V BluetoothFtpService: Ftp Service onStartCommand
08-29 15:11:38.820  3819  3819 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 15:11:38.821  3819  3819 V BluetoothFtpService: Ftp Service closeService
08-29 15:11:38.821  3819  3819 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-29 15:11:38.822  3819  3819 V BluetoothFtpService: successfully stopped ftp service
08-29 15:11:38.822  3819  3819 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 15:11:38.823  3819  3819 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 15:11:38.823  3819  3819 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 15:11:38.823  3819  3819 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 15:11:38.823  3819  3819 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-29 15:11:38.823  3819  3819 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-29 15:11:38.824  3819  3819 V BluetoothFtpService: Ftp Service onDestroy
08-29 15:11:38.824  3819  3819 V BluetoothFtpService: Ftp Service closeService
08-29 15:11:38.854   348   348 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 457us total 39.373ms
,08-29 15:11:38.874   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 403us total 19.864ms
,08-29 15:11:38.893   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 368us total 17.835ms
,08-29 15:11:38.904  6101  6101 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
08-29 15:11:38.939  1034  1929 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6959 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-29 15:11:38.947  3819  3819 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 15:11:38.947  3819  3819 V BluetoothSapService: state: 13
08-29 15:11:38.947  3819  3819 V BluetoothSapService: Stopping SAP server process
08-29 15:11:38.949  3819  3819 V BluetoothSapService: Sap Service closeSapService in
08-29 15:11:38.949  3819  3819 V BluetoothSapService: Close listen Socket : 
08-29 15:11:38.949  3819  3819 V BluetoothSapService: Close rfcomm Socket : 
08-29 15:11:38.949  3819  3819 V BluetoothSapService: Close sapd  Socket : 
08-29 15:11:38.951  1034  1957 I ActivityManager: Killing 6532:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-29 15:11:38.981  6941  6941 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-29 15:11:39.005  1034  1050 W libprocessgroup: failed to open /acct/uid_10008/pid_6532/cgroup.procs: No such file or directory
,08-29 15:11:39.005  3819  3819 V BluetoothSapService: Sap Service closeSapService out
08-29 15:11:39.006  3819  3819 V BluetoothSapService: Sap Service onDestroy
08-29 15:11:39.006  3819  3819 V BluetoothSapService: Sap Service closeSapService in
08-29 15:11:39.006  3819  3819 V BluetoothSapService: Close listen Socket : 
08-29 15:11:39.006  3819  3819 V BluetoothSapService: Close rfcomm Socket : 
08-29 15:11:39.006  3819  3819 V BluetoothSapService: Close sapd  Socket : 
08-29 15:11:39.014  3819  3819 V BluetoothSapService: Sap Service closeSapService out
08-29 15:11:39.016  6941  6941 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-29 15:11:39.033  6959  6959 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-29 15:11:39.050  1034  1874 I ActivityManager: Killing 6027:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-29 15:11:39.086  6941  6941 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-29 15:11:39.087  6941  6941 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
,08-29 15:11:39.087  6941  6941 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
,08-29 15:11:39.087  6941  6941 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-29 15:11:39.088  6941  6941 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-29 15:11:39.090  6941  6941 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,08-29 15:11:39.096  6941  6941 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast,
08-29 15:11:39.195  1034  2011 W libprocessgroup: failed to open /acct/uid_10011/pid_6027/cgroup.procs: No such file or directory,
,08-29 15:11:39.208  3819  3999 W bt-btif : ag scb idx 1 not allocated
,08-29 15:11:39.208  3819  3905 D bt_hci_bdroid: cleanup
,08-29 15:11:39.208  3819  3999 E bt-btif : BTA AG is already disabled, ignoring ...
08-29 15:11:39.208  3819  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 15:11:39.208  3819  3999 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 15:11:39.208  3819  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 15:11:39.208  3819  3999 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 15:11:39.208  3819  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 15:11:39.208  3819  3999 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 15:11:39.209  3819  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 15:11:39.209  3819  3999 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 15:11:39.209  3819  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 15:11:39.209  3819  3999 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 15:11:39.209  3819  4003 I bt_lpm  : LPM is already off!!!
08-29 15:11:39.209  3819  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 15:11:39.209  3819  3999 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-29 15:11:39.209  3819  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 15:11:39.209  3819  3999 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 15:11:39.209  3819  4209 I bt_userial_mct: exiting userial_read_thread
08-29 15:11:39.209  3819  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 15:11:39.209  3819  4209 D bt_userial_mct: Leaving userial_evt_read_thread()
08-29 15:11:39.209  3819  3999 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 15:11:39.209  3819  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 15:11:39.209  3819  3999 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 15:11:39.209  3819  3999 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-29 15:11:39.210  3819  3905 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-29 15:11:39.210  3819  4003 I bt_vendor: hw_epilog_process
08-29 15:11:39.211  3819  3905 D bt_hci_bdroid: cleanup Finalizing cleanup
08-29 15:11:39.211  3819  3905 D bt_userial_mct: userial_close
08-29 15:11:39.211  3819  3905 E bt_userial_mct: pthread_join() FAILED result:3
08-29 15:11:39.211  3819  3905 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-29 15:11:39.233  6941  6941 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 15:11:39.236  6941  6941 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 15:11:39.255  6941  6941 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-29 15:11:39.259  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 15:11:39.264  6913  6913 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-29 15:11:39.264  6913  6913 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 15:11:39.265  6913  6913 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 15:11:39.269  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 15:11:39.278  6941  6941 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-29 15:11:39.280  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 15:11:39.290  6941  6941 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,08-29 15:11:39.292  6941  6941 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 15:11:39.293  6941  6941 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 15:11:39.295  6941  6941 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 15:11:39.298  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 15:11:39.302  6913  6913 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-29 15:11:39.302  6913  6913 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 15:11:39.302  6913  6913 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 15:11:39.318  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 15:11:39.325  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 15:11:39.332  6941  6941 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 15:11:39.332  6941  6941 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 15:11:39.337  6941  6941 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-29 15:11:39.375  3819  3905 D bt_hci_bdroid: set_power 0
08-29 15:11:39.375  3819  3905 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-29 15:11:39.375  3819  3905 I bt_vendor: bluetooth satus is on
08-29 15:11:39.375  3819  3905 I bt_vendor: bt-vendor : resetting BT status
08-29 15:11:39.375  3819  3905 I bt_vendor: Starting hciattach daemon
08-29 15:11:39.375  3819  3905 I bt_vendor: try to set false
,08-29 15:11:39.380  3819  3905 I bt_vendor: Starting hciattach daemon
08-29 15:11:39.381  3819  3905 I bt_vendor: try to set false
08-29 15:11:39.382  3819  3905 I bt_vendor: cleanup
08-29 15:11:39.384  3819  3999 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-29 15:11:39.385  3819  3905 I GKI_LINUX: GKI_exit_task 0 done
08-29 15:11:39.385  3819  3905 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-29 15:11:39.388  3819  3900 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-29 15:11:39.408  1034  2032 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6994 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-29 15:11:39.417  3819  3819 D HeadsetService: Received stop request...Stopping profile...
08-29 15:11:39.418  3819  3819 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-29 15:11:39.418  3819  3819 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 15:11:39.419  3819  3819 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ed5283d
08-29 15:11:39.420  3819  3923 D HeadsetStateMachine: Exit Disconnected: -1
08-29 15:11:39.426  1836  1836 D BluetoothHeadset: Proxy object disconnected
08-29 15:11:39.426  1836  1836 D BluetoothHeadset: Proxy object disconnected
08-29 15:11:39.427  1836  1836 D BluetoothHeadset: Proxy object disconnected
,08-29 15:11:39.428  1034  1034 D BluetoothHeadset: Proxy object disconnected
08-29 15:11:39.428  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-29 15:11:39.431  3819  3819 D HeadsetStateMachine: Unbinding service...
08-29 15:11:39.434  3819  3819 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 15:11:39.434  3819  3819 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 15:11:39.434  3819  3819 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 15:11:39.434  3819  3819 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 15:11:39.435  3819  3819 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 15:11:39.435  3819  3819 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 15:11:39.435  3819  3819 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-29 15:11:39.436  3819  3819 D A2dpService: Received stop request...Stopping profile...
08-29 15:11:39.437  3819  3965 D A2dpStateMachine: Exit Disconnected: -1
08-29 15:11:39.438  3819  3819 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-29 15:11:39.438  3819  3900 D BluetoothAdapterState: Stopping profile services that were post enabled
08-29 15:11:39.439  3819  3819 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-29 15:11:39.439  3819  3819 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 15:11:39.439  3819  3819 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ed5283d
08-29 15:11:39.440  1034  1034 D BluetoothA2dp: Proxy object disconnected
08-29 15:11:39.440  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-29 15:11:39.442  3819  3819 D HidService: Received stop request...Stopping profile...
08-29 15:11:39.442  3819  3819 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ed5283d
08-29 15:11:39.443  3819  3819 D HealthService: Received stop request...Stopping profile...
08-29 15:11:39.443  3819  3819 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ed5283d
08-29 15:11:39.444  6892  6892 D BluetoothInputDevice: Proxy object disconnected
08-29 15:11:39.444  6892  6892 D HidProfile: Bluetooth service disconnected
08-29 15:11:39.445  3819  3819 D PanService: Received stop request...Stopping profile...
08-29 15:11:39.445  3819  3819 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ed5283d
08-29 15:11:39.446  3819  3819 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 15:11:39.447  3819  3819 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 15:11:39.447  3819  3819 D BtGatt.GattService: stop()
08-29 15:11:39.447  3819  3819 D BtGatt.AdvertiseManager: advertise clients cleared
08-29 15:11:39.448  6892  6892 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 15:11:39.448  6892  6892 D PanProfile: Bluetooth service disconnected
08-29 15:11:39.448  3819  3819 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ed5283d
08-29 15:11:39.449  3819  3819 D BluetoothMapService: Received stop request...Stopping profile...
08-29 15:11:39.449  3819  3819 D BluetoothMapService: stop()
08-29 15:11:39.449  3819  3819 D BluetoothMapEmailAppObserver: deinitObservers()
08-29 15:11:39.449  3819  3819 D BluetoothMapEmailAppObserver: removeReceiver()
08-29 15:11:39.450  3819  3819 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ed5283d
08-29 15:11:39.451  3819  3819 I BluetoothA2dpServiceJni: cleanupNative
,08-29 15:11:39.453  3819  3966 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-29 15:11:39.453  6892  6892 D BluetoothMap: Proxy object disconnected
08-29 15:11:39.453  6892  6892 D MapProfile: Bluetooth service disconnected
08-29 15:11:39.454  3819  3819 I GKI_LINUX: GKI_exit_task 2 done
08-29 15:11:39.454  3819  3819 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-29 15:11:39.454  3819  3819 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 15:11:39.454  3819  3819 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 15:11:39.454  3819  3819 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 15:11:39.454  3819  3819 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 15:11:39.455  3819  3819 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 15:11:39.455  3819  3819 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 15:11:39.455  3819  3819 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 15:11:39.456  3819  3819 V BluetoothMapService: Handler(): got msg=4
08-29 15:11:39.456  3819  3819 D BluetoothMapService: MAP Service closeService in
08-29 15:11:39.456  3819  3819 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 15:11:39.456  3819  3819 V BluetoothMapService: MAP Service closeService out
08-29 15:11:39.456  3819  3819 D BluetoothMapService: cleanup()
08-29 15:11:39.456  3819  3819 D BluetoothMapService: MAP Service closeService in
08-29 15:11:39.456  3819  3819 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 15:11:39.456  3819  3819 V BluetoothMapService: MAP Service closeService out
08-29 15:11:39.456  3819  3900 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-29 15:11:39.456  3819  3900 D BluetoothAdapterProperties: Setting state to 10
08-29 15:11:39.456  3819  3900 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-29 15:11:39.457  1034  1116 D BluetoothManagerService: Message: 60
08-29 15:11:39.457  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-29 15:11:39.457  3819  3900 I BluetoothAdapterState: Entering OffState
08-29 15:11:39.457  1034  1116 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-29 15:11:39.457  1836  1852 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 15:11:39.457  1034  1116 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 15:11:39.457  1034  1116 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 15:11:39.458  6892  6908 D BluetoothMap: onBluetoothStateChange: up=false
08-29 15:11:39.458  6892  6909 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 15:11:39.459  6892  6908 D BluetoothPan: onBluetoothStateChange on: false
08-29 15:11:39.459  6892  6909 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 15:11:39.460  1836  4430 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 15:11:39.460  1836  2416 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 15:11:39.461  1034  1116 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-29 15:11:39.461  1034  1116 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-29 15:11:39.464  1034  1116 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-29 15:11:39.464  1034  1116 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-29 15:11:39.464  1034  1116 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@24534f09 mBinding = false
08-29 15:11:39.464  1034  1116 D BluetoothManagerService: Sending unbind request.
,08-29 15:11:39.474  1034  1116 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-29 15:11:39.477  3819  3905 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-29 15:11:39.478  3819  3819 I GKI_LINUX: GKI_exit_task 1 done
08-29 15:11:39.478  3819  3819 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-29 15:11:39.479  3819  3819 I BluetoothServiceJni: cleanupNative: return from cleanup
08-29 15:11:39.479  3819  3819 I art     : --- WEIRD: removing null entry 246
08-29 15:11:39.479  3819  3819 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-29 15:11:39.479  3819  3819 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-29 15:11:39.479  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 15:11:39.480  1925  2110 D LGBluetoothAPIService: Message: 2
08-29 15:11:39.480  1925  2110 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@120c9ce4 mBinding = false
08-29 15:11:39.480  1925  2110 D LGBluetoothAPIService: Sending unbind request.
08-29 15:11:39.481  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 15:11:39.484  6892  6892 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-29 15:11:39.485  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:39.485  6892  6892 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-29 15:11:39.485  6892  6892 D LGBluetoothEventManager: [BTUI] clear device connection state
08-29 15:11:39.485  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:39.486  3819  3819 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-29 15:11:39.487  6892  6892 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-29 15:11:39.490  1587  1587 D BluetoothAdapter: 805133429: getState() :  mService = null. Returning STATE_OFF
08-29 15:11:39.490  1587  1587 D BluetoothAdapter: 805133429: getState() :  mService = null. Returning STATE_OFF
,08-29 15:11:39.494  6892  6892 D DockEventReceiver: finishStartingService: stopping service
08-29 15:11:39.495  3819  3819 I art     : System.exit called, status: 0
08-29 15:11:39.495  3819  3819 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-29 15:11:39.516   316  2153 V AudioFlinger: 3819 died, releasing its sessions
08-29 15:11:39.516   316  2153 V AudioFlinger:  pid 1836 @ 0
08-29 15:11:39.516   316  2153 V AudioFlinger:  pid 3379 @ 1
08-29 15:11:39.516   316  2153 V AudioFlinger:  pid 3379 @ 2
,08-29 15:11:39.518  6892  6892 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-29 15:11:39.534  1034  1957 I ActivityManager: Process com.android.bluetooth (pid 3819) has died
08-29 15:11:39.534  1034  1957 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-29 15:11:39.538  2198  2198 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 15:11:39.549  6913  6913 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 15:11:39.559  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-29 15:11:39.565  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 15:11:39.566  6892  6892 D BluetoothPermissionRequest: onReceive
08-29 15:11:39.569  6892  6892 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-29 15:11:39.569  6892  6892 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-29 15:11:39.570  6994  7027 W FormManager: Network not available. Please check & try again.
08-29 15:11:39.571  6892  6892 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 15:11:39.614  1034  1598 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7029 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-29 15:11:39.632  6994  7028 V FormManager: Network unavailable.
,08-29 15:11:39.638  6892  6892 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 15:11:39.639  6892  6892 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 15:11:39.639  6892  6892 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 15:11:39.639  6892  6892 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 15:11:39.641  6892  6892 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 15:11:39.641  6994  7028 V FormManager: Network unavailable.
08-29 15:11:39.651  6892  6892 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,08-29 15:11:39.653  6892  6892 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-29 15:11:39.653  6892  6892 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 15:11:39.654  6892  6892 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 15:11:39.654  6892  6892 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 15:11:39.654  6892  6892 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 15:11:39.658  4308  4308 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 15:11:39.659  4308  4308 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 15:11:39.660  1034  2032 I ActivityManager: Killing 6050:com.android.contacts/u0a19 (adj 15): empty #17
08-29 15:11:39.661  4308  4308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 15:11:39.692  4308  4308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-29 15:11:39.695  1034  1962 W libprocessgroup: failed to open /acct/uid_10019/pid_6050/cgroup.procs: No such file or directory
08-29 15:11:39.708  4308  7049 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-29 15:11:39.714  4308  7050 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 15:11:39.714  4308  7050 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 15:11:39.718  6913  6913 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-29 15:11:39.718  6913  6913 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 15:11:39.718  6913  6913 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 15:11:39.723  7029  7029 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-29 15:11:39.724  7029  7029 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 15:11:39.724  7029  7029 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-29 15:11:39.725  7029  7029 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-29 15:11:39.726  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-29 15:11:39.729  6994  7052 W FormManager: Network not available. Please check & try again.
08-29 15:11:39.732  6994  7053 V FormManager: Network unavailable.
,08-29 15:11:39.735  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 15:11:39.736  6994  7053 V FormManager: Network unavailable.
08-29 15:11:39.746  7029  7029 D BluetoothAdapterApp: Loading JNI Library
,08-29 15:11:39.759  6941  6941 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-29 15:11:39.760  6941  6941 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-29 15:11:39.760  6941  6941 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-29 15:11:39.780  4494  7054 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,08-29 15:11:39.781  7029  7029 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@69537da Instance Count = 1
08-29 15:11:39.786  7029  7029 D BluetoothAdapterApp: onCreate
08-29 15:11:39.790  6941  6941 D LgDataFeature: LgDataFeature() Constructor: none
08-29 15:11:39.790  6941  6941 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 15:11:39.797  6941  6941 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-29 15:11:39.798  6941  6941 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-29 15:11:39.798  6941  6941 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-29 15:11:39.798  6941  6941 V SoundPool: doLoad: loading sample sampleID=1
08-29 15:11:39.798  6941  6941 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-29 15:11:39.800  6941  7062 V SoundPool: Start decode
08-29 15:11:39.800  6941  7062 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-29 15:11:39.801   316  1382 V MediaPlayerService: decode(23, 10857164, 17813)
08-29 15:11:39.801   316  1382 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-29 15:11:39.801   316  1382 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-29 15:11:39.801   316  1382 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-29 15:11:39.801   316  1382 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-29 15:11:39.801   316  1382 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-29 15:11:39.801   316  1382 V MediaPlayerService: player type = 3
08-29 15:11:39.801   316  1382 V AwesomePlayer: AwesomePlayer create()
,08-29 15:11:39.802   316  1382 V AwesomePlayer: reset_l() 
08-29 15:11:39.802   316  1382 V AwesomePlayer: cancelPlayerEvents
08-29 15:11:39.802   316  1382 V AwesomePlayer: setAudioSink() 
08-29 15:11:39.802   316  1382 V AwesomePlayer: reset_l() 
08-29 15:11:39.802   316  1382 V AudioCache: notify(0xb5474480, 8, 0, 0)
08-29 15:11:39.802   316  1382 V AudioCache: ignored
08-29 15:11:39.802   316  1382 V AwesomePlayer: cancelPlayerEvents
08-29 15:11:39.802   316  1382 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-29 15:11:39.802   316  1382 V AwesomePlayer: setDataSource_l dataSource
08-29 15:11:39.802   316  1382 V LGParserOSAL: SniffLGParser start
08-29 15:11:39.802   316  1382 V LGParserOSAL: MainType:5, SubType=0
08-29 15:11:39.802   316  1382 V LGParserOSAL: #### check Mime : application/ogg
08-29 15:11:39.802   316  1382 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-29 15:11:39.802   316  1382 E MediaExtractor: Use LGExtractor :application/ogg 
08-29 15:11:39.804  6795  6795 D UEI.SmartControl: QS Service created
08-29 15:11:39.806  7029  7029 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-29 15:11:39.806  7029  7029 D ProfileConfigQcom: Adding HeadsetService
08-29 15:11:39.806  7029  7029 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-29 15:11:39.807  7029  7029 D ProfileConfigQcom: Adding A2dpService
08-29 15:11:39.807  7029  7029 D ProfileConfigQcom: [BTUI] HidService is supported
08-29 15:11:39.807  7029  7029 D ProfileConfigQcom: Adding HidService
08-29 15:11:39.807  7029  7029 D ProfileConfigQcom: [BTUI] HealthService is supported
08-29 15:11:39.807  7029  7029 D ProfileConfigQcom: Adding HealthService
08-29 15:11:39.808  7029  7029 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-29 15:11:39.808  7029  7029 D ProfileConfigQcom: [BTUI] PanService is supported
08-29 15:11:39.808  7029  7029 D ProfileConfigQcom: Adding PanService
08-29 15:11:39.808  7029  7029 D ProfileConfigQcom: [BTUI] GattService is supported
08-29 15:11:39.808  7029  7029 D ProfileConfigQcom: Adding GattService
08-29 15:11:39.809  7029  7029 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-29 15:11:39.809  7029  7029 D ProfileConfigQcom: Adding BluetoothMapService
08-29 15:11:39.809  7029  7029 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-29 15:11:39.810  7029  7029 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-29 15:11:39.814  6892  6892 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-29 15:11:39.814  6941  6941 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-29 15:11:39.815  7029  7029 V LGMDMManagerInternal: Create singleton instance
08-29 15:11:39.816  6941  6941 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-29 15:11:39.816  6941  6941 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-29 15:11:39.839   316  1382 V LGParserOSAL: supported mime: application/ogg
08-29 15:11:39.839   316  1382 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-29 15:11:39.839   316  1382 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-29 15:11:39.839   316  1382 V AwesomePlayer: mBitrate = -1 bits/sec
08-29 15:11:39.839   316  1382 V AwesomePlayer: AudioTrack Setting
08-29 15:11:39.839   316  1382 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-29 15:11:39.840   316  1382 V AwesomePlayer: setAudioSource() 
08-29 15:11:39.840   316  1382 V MediaPlayerService: prepare
08-29 15:11:39.840   316  1382 V AwesomePlayer: prepareAsync_l() 
08-29 15:11:39.840   316  1382 V MediaPlayerService: wait for prepare
08-29 15:11:39.840   316  7064 V AwesomePlayer: onPrepareAsyncEvent() 
08-29 15:11:39.840   316  7064 V AwesomePlayer: initAudioDecoder() 
08-29 15:11:39.840   316  7064 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-29 15:11:39.840   316  7064 V AudioSystem: isOffloadSupported()
08-29 15:11:39.840   316  7064 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-29 15:11:39.840   316  7064 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-29 15:11:39.840   316  7064 I AudioFlinger: isAudioPlaybackHookOn() false
08-29 15:11:39.840   316  7064 V AwesomePlayer: getUseOffload() = 0 
08-29 15:11:39.840   316  7064 V OMXCodec: OMXCodec::Create
08-29 15:11:39.840   316  7064 V OMXCodec: findMatchingCodecs()
08-29 15:11:39.840   316  7064 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-29 15:11:39.840   316  7064 V OMXCodec: matchingCodecs.size()=1
08-29 15:11:39.840   316  7064 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-29 15:11:39.841   316  7064 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-29 15:11:39.842   316  7064 V LGCodecAdapter: LG Codec Adapter start
08-29 15:11:39.842   316  7064 V OMXCodec: OMXCodec Createtor
08-29 15:11:39.842   316  7064 V OMXCodec: setComponentRole
08-29 15:11:39.842   316  7064 V OMXCodec: configureCodec protected=0
08-29 15:11:39.842   316  7064 V LGCodecAdapter: called getLGCodecSpecificData
08-29 15:11:39.842   316  7064 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-29 15:11:39.842   316  7064 V LGCodecOSAL: Called LGconfigureCodecMETA
08-29 15:11:39.842   316  7064 V LGCodecOSAL: Called LGconfigureCodecMSG
08-29 15:11:39.842   316  7064 V LGCodecOSAL: Not support LGCodec
08-29 15:11:39.842   316  7064 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-29 15:11:39.842   316  7064 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-29 15:11:39.842   316  7064 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-29 15:11:39.842   316  7064 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-29 15:11:39.842   316  7064 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-29 15:11:39.842   316  7064 V AudioSystem: isOffloadSupported()
08-29 15:11:39.842   316  7064 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-29 15:11:39.842   316  7064 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-29 15:11:39.842   316  7064 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-29 15:11:39.842   316  7064 V OMXCodec: init()
08-29 15:11:39.842   316  7064 V OMXCodec: [OMX.google.vorbis.decoder] set,State mState=1 , newState=2
08-29 15:11:39.842   316  7064 V OMXCodec: allocateBuffers
08-29 15:11:39.842   316  7064 V OMXCodec: allocateBuffersOnPort portIndex=0
08-29 15:11:39.842   316  7064 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-29 15:11:39.842   316  7064 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7880 on input port
08-29 15:11:39.842   316  7064 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on input port
08-29 15:11:39.842   316  7064 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
08-29 15:11:39.842   316  7064 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
,08-29 15:11:39.842   316  7064 V OMXCodec: allocateBuffersOnPort portIndex=1
08-29 15:11:39.842   316  7064 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-29 15:11:39.843   316  7064 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
08-29 15:11:39.843   316  7064 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-29 15:11:39.843   316  7064 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
08-29 15:11:39.843   316  7064 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c1060 on output port
08-29 15:11:39.843   316  7064 V OMXCodec: init() mAsyncCompletion wait!!! 
08-29 15:11:39.843   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-29 15:11:39.843   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-29 15:11:39.843   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-29 15:11:39.843   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-29 15:11:39.843   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-29 15:11:39.843   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-29 15:11:39.843   316  7064 V OMXCodec: init() mAsyncCompletion wait free! 
08-29 15:11:39.843   316  7064 V AwesomePlayer: finishAsyncPrepare_l() 
08-29 15:11:39.843   316  7064 V AudioCache: notify(0xb5474480, 5, 0, 0)
08-29 15:11:39.843   316  7064 V AudioCache: ignored
08-29 15:11:39.843   316  7064 V AudioCache: notify(0xb5474480, 1, 0, 0)
08-29 15:11:39.843   316  7064 V AudioCache: prepared
08-29 15:11:39.843   316  1382 V AudioCache: wait - success
08-29 15:11:39.843   316  1382 V MediaPlayerService: start
08-29 15:11:39.844   316  1382 V AwesomePlayer: play_l() 
08-29 15:11:39.844   316  1382 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-29 15:11:39.844   316  1382 V AwesomePlayer: createAudioPlayer_l
08-29 15:11:39.844   316  1382 V AwesomePlayer: seekAudioIfNecessary_l() 
08-29 15:11:39.844   316  1382 V AwesomePlayer: startAudioPlayer_l() 
08-29 15:11:39.844   316  1382 D AudioPlayer: start of Playback, useOffload 0
08-29 15:11:39.844   316  1382 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-29 15:11:39.844   316  1382 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-29 15:11:39.846   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-29 15:11:39.846   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-29 15:11:39.847   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-29 15:11:39.847   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-29 15:11:39.847   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-29 15:11:39.847   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-29 15:11:39.847   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884768
08-29 15:11:39.847   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 15:11:39.847   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885008
08-29 15:11:39.847   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 15:11:39.847   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885648
08-29 15:11:39.847   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 15:11:39.847   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044806752
08-29 15:11:39.847   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 15:11:39.847   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DIS,ABLED(1)
08-29 15:11:39.847   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-29 15:11:39.847   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-29 15:11:39.847   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-29 15:11:39.847   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-29 15:11:39.848   316  7066 V OMXCodec: allocateBuffersOnPort portIndex=1
08-29 15:11:39.848   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-29 15:11:39.848   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
08-29 15:11:39.848   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-29 15:11:39.848   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
08-29 15:11:39.848   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f1f0 on output port
08-29 15:11:39.848   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-29 15:11:39.848   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-29 15:11:39.849   316  1382 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-29 15:11:39.849   316  1382 V AudioCache: notify(0xb5474480, 6, 0, 0)
08-29 15:11:39.849   316  1382 V AudioCache: ignored
08-29 15:11:39.850   316  1382 V MediaPlayerService: wait for playback complete
08-29 15:11:39.850   316  7067 V AudioCache: write(0xb17fa000, 4096)
08-29 15:11:39.850   316  7067 V AudioCache: memcpy(0xaf006000, 0xb17fa000, 4096)
08-29 15:11:39.851   316  7067 V AudioCache: write(0xb17fa000, 4096)
08-29 15:11:39.851   316  7067 V AudioCache: memcpy(0xaf007000, 0xb17fa000, 4096)
08-29 15:11:39.851   316  7067 V AudioCache: write(0xb17fa000, 4096)
08-29 15:11:39.851   316  7067 V AudioCache: memcpy(0xaf008000, 0xb17fa000, 4096)
08-29 15:11:39.852  6941  6941 V LGMDMManager: Create singleton instance
08-29 15:11:39.852   316  7067 V AudioCache: write(0xb17fa000, 4096)
08-29 15:11:39.852   316  7067 V AudioCache: memcpy(0xaf009000, 0xb17fa000, 4096)
08-29 15:11:39.852   316  7067 V AudioCache: write(0xb17fa000, 4096)
08-29 15:11:39.852   316  7067 V AudioCache: memcpy(0xaf00a000, 0xb17fa000, 4096)
08-29 15:11:39.852   316  7067 V AudioCache: write(0xb17fa000, 4096)
08-29 15:11:39.852   316  7067 V AudioCache: memcpy(0xaf00b000, 0xb17fa000, 4096)
08-29 15:11:39.853   316  7067 V AudioCache: write(0xb17fa000, 4096)
08-29 15:11:39.853   316  7067 V AudioCache: memcpy(0xaf00c000, 0xb17fa000, 4096)
08-29 15:11:39.853   316  7067 V AudioCache: write(0xb17fa000, 4096)
08-29 15:11:39.853   316  7067 V AudioCache: memcpy(0xaf00d000, 0xb17fa000, 4096)
08-29 15:11:39.854   316  7067 V AudioCache: write(0xb17fa000, 4096)
08-29 15:11:39.854   316  7067 V AudioCache: memcpy(0xaf00e000, 0xb17fa000, 4096)
08-29 15:11:39.854   316  7067 V AudioCache: write(0xb17fa000, 4096)
08-29 15:11:39.854   316  7067 V AudioCache: memcpy(0xaf00f000, 0xb17fa000, 4096)
08-29 15:11:39.854   316  7067 V AudioCache: write(0xb17fa000, 4096)
08-29 15:11:39.854   316  7067 V AudioCache: memcpy(0xaf010000, 0xb17fa000, 4096)
,08-29 15:11:39.855   316  7067 V AudioCache: write(0xb17fa000, 4096)
08-29 15:11:39.855   316  7067 V AudioCache: memcpy(0xaf011000, 0xb17fa000, 4096)
08-29 15:11:39.855   316  7067 V AudioCache: write(0xb17fa000, 4096)
08-29 15:11:39.855   316  7067 V AudioCache: memcpy(0xaf012000, 0xb17fa000, 4096)
08-29 15:11:39.855   316  7067 V AudioCache: write(0xb17fa000, 4096)
08-29 15:11:39.855   316  7067 V AudioCache: memcpy(0xaf013000, 0xb17fa000, 4096)
08-29 15:11:39.856   316  7067 V AudioCache: write(0xb17fa000, 4096)
08-29 15:11:39.856   316  7067 V AudioCache: memcpy(0xaf014000, 0xb17fa000, 4096)
08-29 15:11:39.856   316  7067 V AudioCache: write(0xb17fa000, 4096)
08-29 15:11:39.856   316  7067 V AudioCache: memcpy(0xaf015000, 0xb17fa000, 4096)
08-29 15:11:39.856   316  7067 V AudioCache: write(0xb17fa000, 4096)
,08-29 15:11:39.856   316  7067 V AudioCache: memcpy(0xaf016000, 0xb17fa000, 4096)
,08-29 15:11:39.857   316  7067 V AudioCache: write(0xb17fa000, 4096)
08-29 15:11:39.857   316  7067 V AudioCache: memcpy(0xaf017000, 0xb17fa000, 4096)
08-29 15:11:39.858   316  7067 V AudioCache: write(0xb17fa000, 4096)
08-29 15:11:39.858   316  7067 V AudioCache: memcpy(0xaf018000, 0xb17fa000, 4096)
08-29 15:11:39.858   316  7067 V AudioCache: write(0xb17fa000, 4096)
08-29 15:11:39.858   316  7067 V AudioCache: memcpy(0xaf019000, 0xb17fa000, 4096)
08-29 15:11:39.859   316  7067 V AudioCache: write(0xb17fa000, 4096)
08-29 15:11:39.859   316  7067 V AudioCache: memcpy(0xaf01a000, 0xb17fa000, 4096)
08-29 15:11:39.859   316  7067 V AudioCache: write(0xb17fa000, 4096)
08-29 15:11:39.859   316  7067 V AudioCache: memcpy(0xaf01b000, 0xb17fa000, 4096)
08-29 15:11:39.859   316  7067 V AudioCache: write(0xb17fa000, 4096)
08-29 15:11:39.859   316  7067 V AudioCache: memcpy(0xaf01c000, 0xb17fa000, 4096)
08-29 15:11:39.860   316  7067 V AudioCache: write(0xb17fa000, 4096)
08-29 15:11:39.860   316  7067 V AudioCache: memcpy(0xaf01d000, 0xb17fa000, 4096)
08-29 15:11:39.861   316  7067 V AudioCache: write(0xb17fa000, 4096)
08-29 15:11:39.861   316  7067 V AudioCache: memcpy(0xaf01e000, 0xb17fa000, 4096)
08-29 15:11:39.862   316  7067 V AudioCache: write(0xb17fa000, 4096)
08-29 15:11:39.862   316  7067 V AudioCache: memcpy(0xaf01f000, 0xb17fa000, 4096)
08-29 15:11:39.863   316  7067 V AudioCache: write(0xb17fa000, 4096)
08-29 15:11:39.863   316  7067 V AudioCache: memcpy(0xaf020000, 0xb17fa000, 4096)
08-29 15:11:39.864   316  7067 V AudioCache: write(0xb17fa000, 4096)
08-29 15:11:39.864   316  7067 V AudioCache: memcpy(0xaf021000, 0xb17fa000, 4096)
08-29 15:11:39.865   316  7067 V AudioCache: write(0xb17fa000, 4096)
08-29 15:11:39.865   316  7067 V AudioCache: memcpy(0xaf022000, 0xb17fa000, 4096)
08-29 15:11:39.865   316  7067 V AudioCache: write(0xb17fa000, 4096)
08-29 15:11:39.865   316  7067 V AudioCache: memcpy(0xaf023000, 0xb17fa000, 4096)
08-29 15:11:39.865  7029  7029 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 15:11:39.866   316  7067 V AudioCache: write(0xb17fa000, 4096)
08-29 15:11:39.866   316  7067 V AudioCache: memcpy(0xaf024000, 0xb17fa000, 4096)
,08-29 15:11:39.866   316  7067 V AudioCache: write(0xb17fa000, 4096)
08-29 15:11:39.866   316  7067 V AudioCache: memcpy(0xaf025000, 0xb17fa000, 4096)
08-29 15:11:39.867   316  7067 V AudioCache: write(0xb17fa000, 4096)
08-29 15:11:39.867   316  7067 V AudioCache: memcpy(0xaf026000, 0xb17fa000, 4096)
08-29 15:11:39.868  7029  7029 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 15:11:39.868  6795  6795 I UEI.SmartControl: Service initServices...
08-29 15:11:39.868   316  7067 V AudioCache: write(0xb17fa000, 4096)
08-29 15:11:39.868  6795  6795 D UEI.SmartControl: QS start get config
08-29 15:11:39.868   316  7067 V AudioCache: memcpy(0xaf027000, 0xb17fa000, 4096)
08-29 15:11:39.868  7029  7029 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 15:11:39.868  7029  7029 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 15:11:39.868   316  7067 V AudioCache: write(0xb17fa000, 4096)
08-29 15:11:39.868   316  7067 V AudioCache: memcpy(0xaf028000, 0xb17fa000, 4096)
08-29 15:11:39.869   316  7067 V AudioCache: write(0xb17fa000, 4096)
08-29 15:11:39.869   316  7067 V AudioCache: memcpy(0xaf029000, 0xb17fa000, 4096)
08-29 15:11:39.869  7029  7029 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 15:11:39.869  7029  7029 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-29 15:11:39.870   316  7067 V AudioCache: write(0xb17fa000, 4096)
08-29 15:11:39.870   316  7067 V AudioCache: memcpy(0xaf02a000, 0xb17fa000, 4096)
08-29 15:11:39.870   316  7067 V AudioCache: write(0xb17fa000, 4096)
08-29 15:11:39.870   316  7067 V AudioCache: memcpy(0xaf02b000, 0xb17fa000, 4096)
08-29 15:11:39.871   316  7067 V AudioCache: write(0xb17fa000, 4096)
08-29 15:11:39.871   316  7067 V AudioCache: memcpy(0xaf02c000, 0xb17fa000, 4096)
08-29 15:11:39.871   316  7067 V AudioCache: write(0xb17fa000, 4096)
08-29 15:11:39.871   316  7067 V AudioCache: memcpy(0xaf02d000, 0xb17fa000, 4096)
08-29 15:11:39.872   316  7067 V AudioCache: write(0xb17fa000, 4096)
08-29 15:11:39.872   316  7067 V AudioCache: memcpy(0xaf02e000, 0xb17fa000, 4096)
08-29 15:11:39.873   316  7067 V AudioCache: write(0xb17fa000, 4096)
08-29 15:11:39.873   316  7067 V AudioCache: memcpy(0xaf02f000, 0xb17fa000, 4096)
08-29 15:11:39.873   316  7067 V AudioCache: write(0xb17fa000, 4096)
08-29 15:11:39.873   316  7067 V AudioCache: memcpy(0xaf030000, 0xb17fa000, 4096)
08-29 15:11:39.874   316  7067 V AudioCache: write(0xb17fa000, 4096)
08-29 15:11:39.874   316  7067 V AudioCache: memcpy(0xaf031000, 0xb17fa000, 4096)
08-29 15:11:39.875   316  7067 V AudioCache: write(0xb17fa000, 4096)
08-29 15:11:39.875   316  7067 V AudioCache: memcpy(0xaf032000, 0xb17fa000, 4096)
08-29 15:11:39.875   316  7067 V AudioCache: write(0xb17fa000, 4096)
08-29 15:11:39.875   316  7067 V AudioCache: memcpy(0xaf033000, 0xb17fa000, 4096)
08-29 15:11:39.876   316  7067 V AudioCache: write(0xb17fa000, 4096)
08-29 15:11:39.876   316  7067 V AudioCache: memcpy(0xaf034000, 0xb17fa000, 4096)
08-29 15:11:39.877   316  7067 V AudioCache: write(0xb17fa000, 4096)
08-29 15:11:39.877   316  7067 V AudioCache: memcpy(0xaf035000, 0xb17fa000, 4096)
08-29 15:11:39.877   316  7067 V AudioCache: write(0xb17fa000, 4096)
08-29 15:11:39.877   316  7067 V AudioCache: memcpy(0xaf036000, 0xb17fa000, 4096)
08-29 15:11:39.878   316  7067 V AudioCache: write(0xb17fa000, 4096)
08-29 15:11:39.878   316  7067 V AudioCache: memcpy(0xaf037000, 0xb17fa000, 4096)
08-29 15:11:39.878   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-29 15:11:39.878   316  7067 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-29 15:11:39.878   316  7067 V AwesomePlayer: postAudioEOS() 
08-29 15:11:39.878   316  7067 V AudioCache: write(0xb17fa000, 280)
08-29 15:11:39.878   316  7067 V AudioCache: memcpy(0xaf038000, 0xb17fa000, 280)
08-29 15:11:39.879  6959  6959 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings,
08-29 15:11:39.883   316  7064 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-29 15:11:39.883   316  7064 V AwesomePlayer: onStreamDone
08-29 15:11:39.883   316  7064 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-29 15:11:39.883   316  7064 V AudioCache: notify(0xb5474480, 2, 0, 0)
08-29 15:11:39.883   316  7064 V AudioCache: playback complete
08-29 15:11:39.883   316  7064 V AwesomePlayer: pause_l() 
08-29 15:11:39.883   316  7064 V AudioCache: notify(0xb5474480, 7, 0, 0)
08-29 15:11:39.883   316  7064 V AudioCache: ignored
08-29 15:11:39.884   316  7064 V AwesomePlayer: cancelPlayerEvents
08-29 15:11:39.884   316  1382 V AudioCache: wait - success
08-29 15:11:39.884   316  1382 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-29 15:11:39.884   316  7064 D AudioPlayer: Pause Playback at 1068125
08-29 15:11:39.884   316  1382 V AwesomePlayer: reset_l() 
08-29 15:11:39.884   316  1382 V AudioCache: notify(0xb5474480, 8, 0, 0)
08-29 15:11:39.884   316  1382 V AudioCache: ignored
08-29 15:11:39.884   316  1382 V AwesomePlayer: cancelPlayerEvents
08-29 15:11:39.884   316  1382 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-29 15:11:39.884   316  1382 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-29 15:11:39.884   316  1382 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-29 15:11:39.884   316  1382 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-29 15:11:39.884   316  1382 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-29 15:11:39.885   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-29 15:11:39.885   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-29 15:11:39.885   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-29 15:11:39.885   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
08-29 15:11:39.885   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-29 15:11:39.885   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
08-29 15:11:39.885   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-29 15:11:39.885   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 0
08-29 15:11:39.885   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-29 15:11:39.885   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7880 on port 0
08-29 15:11:39.885   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-29 15:11:39.885   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-29 15:11:39.885   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f1f0 on port 1
08-29 15:11:39.885   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-29 15:11:39.885   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 1
08-29 15:11:39.885   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-29 15:11:39.885   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 1
08-29 15:11:39.885   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-29 15:11:39.885   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7dd0 on port 1
08-29 15:11:39.885   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 15:11:39.885   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-29 15:11:39.885   316  1382 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-29 15:11:39.885   316  1382 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-29 15:11:39.886   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-,29 15:11:39.886   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-29 15:11:39.886   316  7066 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-29 15:11:39.886   316  1382 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-29 15:11:39.886   316  1382 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-29 15:11:39.886   316  1382 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-29 15:11:39.886   316  1382 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-29 15:11:39.887   316  1382 D AudioPlayer: AudioPlayer releasing audio source
08-29 15:11:39.887   316  1382 D AudioPlayer: AudioPlayer done releasing audio source
08-29 15:11:39.887   316  1382 V AwesomePlayer: reset_l() 
08-29 15:11:39.887   316  1382 V AwesomePlayer: cancelPlayerEvents
08-29 15:11:39.887   316  1382 V AwesomePlayer: ~AwesomePlayer call
08-29 15:11:39.887   316  1382 V AwesomePlayer: reset_l() 
08-29 15:11:39.887   316  1382 V AwesomePlayer: cancelPlayerEvents
08-29 15:11:39.887  6941  7062 V SoundPool: close(31)
08-29 15:11:39.887  6941  7062 V SoundPool: pointer = 0x9fe70000, size = 205080, sampleRate = 48000, numChannels = 2
08-29 15:11:39.934  6941  6941 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-29 15:11:39.934  6941  6941 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,08-29 15:11:39.935  6941  6941 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:2602
08-29 15:11:40.105  6795  6795 I UEI.SmartControl: Supports setup maps: true
,08-29 15:11:40.108  6795  6795 D UEI.SmartControl: QS start statue = true Error code = 0
08-29 15:11:40.108  6795  6795 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-29 15:11:40.108  6795  6795 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-29 15:11:40.108  6795  6795 I UEI.SmartControl: ### init IR Blaster...
08-29 15:11:40.111  6795  6795 D serial_port: Configuring serial port
08-29 15:11:40.111  6795  6795 E UEI.SmartControl: UEIBLaster setting for 616
08-29 15:11:40.111  6795  6795 I UEI.SmartControl: Setting serial record hearder size = 2
08-29 15:11:40.111  6795  6795 I UEI.SmartControl: configuring settings for MAXQ616
08-29 15:11:40.112  6795  6795 I UEI.SmartControl: Get version...
08-29 15:11:40.130  6795  7070 D UEI.SmartControl: serial port data available: 21
,08-29 15:11:40.157  6795  6795 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-29 15:11:40.157  6795  6795 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-29 15:11:40.157  6795  6795 I UEI.SmartControl: QS saving settings...
08-29 15:11:40.158  6795  6795 D UEI.SmartControl: IR Blaster version: 25672567
08-29 15:11:40.178  6795  7070 D UEI.SmartControl: serial port data available: 4
,08-29 15:11:40.211  6795  6795 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-29 15:11:40.214  6795  7076 I UEI.SmartControl: Device manager: loading config....
08-29 15:11:40.215  6795  7076 D UEI.SmartControl: ----------- loading internal config...
08-29 15:11:40.216  6795  6795 E UEI.SmartControl: Services init done
08-29 15:11:40.216  6795  6795 D UEI.SmartControl: QS Service init finished
08-29 15:11:40.217  6795  6795 D UEI.SmartControl: QS Service version name: 2.1.91
08-29 15:11:40.217  6795  6795 D UEI.SmartControl: QS Service version code: 201091
08-29 15:11:40.218  6795  6795 D UEI.SmartControl: Service requested: Control
08-29 15:11:40.226  6795  7076 E UEI.SmartControl: Loading SETTINGS...
08-29 15:11:40.228  6795  6795 D UEI.SmartControl: Request IControl service: devices are loaded...
08-29 15:11:40.237  6941  6941 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-29 15:11:40.238  6795  6795 D UEI.SmartControl: Internal service binding...
08-29 15:11:40.239  6795  6812 I UEI.SmartControl: ------ IControl API: 11
08-29 15:11:40.239  6795  6812 D UEI.SmartControl: File observer start...
08-29 15:11:40.241  6795  6812 E UEI.SmartControl: IR Port is disabled: false
08-29 15:11:40.241  6795  6812 D UEI.SmartControl: Starting file observer...
08-29 15:11:40.242  6795  6812 I UEI.SmartControl: Registering callback...
,08-29 15:11:40.244  6795  6811 I UEI.SmartControl: ------ IControl API: 19
08-29 15:11:40.245  6795  6811 I UEI.SmartControl: Registering Services Ready callback...
08-29 15:11:40.246  6795  7076 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-29 15:11:40.250  6795  7075 I UEI.SmartControl: Notify AllClients services are ready: 0
08-29 15:11:40.251  6941  6956 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-29 15:11:40.252  6941  7060 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-29 15:11:40.252  6941  7060 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-29 15:11:40.252  6795  7075 D UEI.SmartControl: -----service ready thread exits
08-29 15:11:40.253  6941  6941 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-29 15:11:40.253  6941  6941 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-29 15:11:40.254  6795  6841 I UEI.SmartControl: ------ IControl API: 8
,08-29 15:11:40.255  6941  6941 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-29 15:11:40.256  6941  6941 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-29 15:11:40.256  6941  6941 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-29 15:11:40.257  6941  6941 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-29 15:11:40.258  6941  6941 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-29 15:11:40.258  6941  6941 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-29 15:11:40.261  6941  6941 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-29 15:11:40.263  6941  6941 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-29 15:11:40.264  6941  6941 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-29 15:11:40.266  6941  6941 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-29 15:11:40.266  6941  6941 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-29 15:11:40.269  6941  6941 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-29 15:11:40.270  6941  6941 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-29 15:11:40.270  6941  6941 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-29 15:11:40.271  6941  6941 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472476300271]
08-29 15:11:40.274  6941  6941 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-29 15:11:40.276  1034  1962 I ActivityManager: Killing 6076:com.android.gallery3d/u0a27 (adj 15): empty #17
08-29 15:11:40.297  6941  7081 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-29 15:11:40.305  1034  1962 I ActivityManager: Killing 6571:com.lge.email/u0a23 (adj 15): empty #18
08-29 15:11:40.334  1034  1874 W libprocessgroup: failed to open /acct/uid_10027/pid_6076/cgroup.procs: No such file or directory
,08-29 15:11:40.337  1034  1598 W libprocessgroup: failed to open /acct/uid_10023/pid_6571/cgroup.procs: No such file or directory
08-29 15:11:40.343  6941  6941 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-29 15:11:40.344  6941  6941 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-29 15:11:40.344  6941  6941 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
,08-29 15:11:40.345  6941  6941 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
,08-29 15:11:40.345  6941  6941 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
,08-29 15:11:40.345  6941  6941 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-29 15:11:40.346  6941  6941 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
,08-29 15:11:40.356  6941  6941 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3],
08-29 15:11:41.202  1034  1922 D WifiServiceImplEx: setWifiEnabled: true pid=6671, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-29 15:11:41.216  1034  1922 D WifiService: setWifiEnabled: true pid=6671, uid=10118
08-29 15:11:41.216  1034  1922 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 15:11:41.233  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 15:11:41.234  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 15:11:41.234  1034  1034 D Ulp_jni : JNI:system_update. Event-4
,08-29 15:11:41.238  1034  1376 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
,08-29 15:11:41.238  1034  1376 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,08-29 15:11:41.240  1034  1376 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-29 15:11:41.240  1034  1376 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-29 15:11:41.241  1034  1376 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-29 15:11:41.241  1034  1376 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-29 15:11:41.241  1034  1376 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-29 15:11:41.241  1034  1376 E WifiHW  : unknown target_country: EU , set to default
08-29 15:11:41.241  1034  1376 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-29 15:11:41.241  1034  1376 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-29 15:11:41.241  1034  1376 I WifiUtil: gEnableBmps=1
08-29 15:11:41.299  1034  1452 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 15:11:41.311  1034  1116 D Tethering: MasterInitialState.processMessage what=3
08-29 15:11:41.315  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:41.321  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:11:41.328  1034  1452 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-29 15:11:41.331  1034  1116 D Tethering: MasterInitialState.processMessage what=3
08-29 15:11:41.339  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:11:41.342  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:41.343  1034  1111 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-29 15:11:41.344  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-29 15:11:41.347  6461  6496 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-29 15:11:41.365  5777  5777 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-29 15:11:41.378  5777  5777 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-29 15:11:41.399  2198  2198 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-29 15:11:41.435  1034  1111 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-29 15:11:41.466  1034  1929 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7094 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-29 15:11:41.472  1034  1111 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 15:11:41.473  1034  1111 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-29 15:11:41.570  7094  7094 I AppUp4:AppBoxCP: onCreate
08-29 15:11:41.571  7094  7094 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-29 15:11:41.583  7094  7094 I AppUp4:DB:  setFingerPrint start
08-29 15:11:41.583  7094  7094 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21,
08-29 15:11:41.591  7094  7094 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-29 15:11:41.591  7094  7094 I AppUp4:DB:  SDK version = 21
08-29 15:11:41.591  7094  7094 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-29 15:11:41.594  7094  7094 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,08-29 15:11:41.595  7094  7094 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-29 15:11:41.595  7094  7094 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-29 15:11:41.598  7094  7094 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-29 15:11:41.598  7094  7094 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-29 15:11:41.605  7094  7094 I AppUp4:CustModeStarterReceiver: onReceive
,08-29 15:11:41.649  7094  7094 D LgDataFeature: LgDataFeature() Constructor: none
,08-29 15:11:41.650  7094  7094 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 15:11:41.659  7094  7094 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@c958594
08-29 15:11:41.659  7094  7094 D AppUp4:CustFacade: isCustomizationCompleted : false
08-29 15:11:41.660  7094  7094 D AppUp4:CustFacade: isPhone : true
08-29 15:11:41.660  7094  7094 D AppUp4:CustModeStarterReceiver: begin check event
08-29 15:11:41.661  7094  7094 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-29 15:11:41.661  7094  7094 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-29 15:11:41.662  7094  7114 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-29 15:11:41.662  7094  7114 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-29 15:11:41.663  7094  7114 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-29 15:11:41.667  1034  1929 I ActivityManager: Killing 6150:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-29 15:11:41.749  4308  4308 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-29 15:11:41.749  4308  4308 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 15:11:41.751  4308  4308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 15:11:41.751  1034  2032 W libprocessgroup: failed to open /acct/uid_10080/pid_6150/cgroup.procs: No such file or directory
,08-29 15:11:41.765  4308  4308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 15:11:41.771  4308  7126 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-29 15:11:41.777  4308  7127 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-29 15:11:41.778  4308  7127 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 15:11:41.811  1034  1991 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7128 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-29 15:11:41.886  7128  7128 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 15:11:41.886  7128  7128 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 15:11:41.888  7128  7128 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-29 15:11:41.889  7128  7128 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-29 15:11:41.900  1034  1116 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-29 15:11:41.905   310   892 D SoftapController: Softap fwReload - Ok
08-29 15:11:41.906  1034  1376 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (659ms)
,08-29 15:11:41.911   310   892 D CommandListener: Setting iface cfg
08-29 15:11:41.912   310   892 D CommandListener: Trying to bring down wlan0
08-29 15:11:41.912   310   892 D CommandListener: Clearing all IP addresses on wlan0
08-29 15:11:41.915  1034  1376 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-29 15:11:41.917  1034  1376 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 15:11:41.917  1034  1376 E WifiStateMachine: useWiFiOffloading() : false
08-29 15:11:41.917  1034  1376 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 15:11:41.921  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,08-29 15:11:41.924  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 15:11:41.904  7151  7151 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 15:11:41.904  7151  7151 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 15:11:41.926  1034  1376 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-29 15:11:41.926  1034  1376 D WifiMonitor: connecting to supplicant
08-29 15:11:41.928  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-29 15:11:41.929  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:41.930  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:41.944  7151  7151 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-29 15:11:41.978  7151  7151 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-29 15:11:41.979  7151  7151 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-29 15:11:41.982  1034  1116 D Tethering: InitialState.processMessage what=4
08-29 15:11:41.983  1034  1116 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 15:11:42.012  7128  7128 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-29 15:11:42.029  7128  7128 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-29 15:11:42.041  7151  7151 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-29 15:11:42.077  7128  7128 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-29 15:11:42.102  7151  7151 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-29 15:11:42.111  7128  7128 D LgDataFeature: LgDataFeature() Constructor: none
08-29 15:11:42.111  7128  7128 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 15:11:42.117  1034  1376 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-29 15:11:42.118  1034  1376 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-29 15:11:42.118  1034  1376 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-29 15:11:42.119  1034  1376 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
,08-29 15:11:42.119  7151  7151 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-29 15:11:42.119  7151  7151 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-29 15:11:42.120  1034  1376 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-29 15:11:42.121  1034  1376 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 15:11:42.122  1034  1376 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-29 15:11:42.123  1034  1376 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 15:11:42.124  1034  7159 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-29 15:11:42.125  1034  7159 D WifiMonitor: Dropping event because (p2p0) is stopped
08-29 15:11:42.125  1034  1376 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-29 15:11:42.125  1034  7159 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-29 15:11:42.125  1034  1376 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-29 15:11:42.125  1034  7159 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-29 15:11:42.125  1034  1376 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-29 15:11:42.126  1034  1376 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-29 15:11:42.126  1034  7159 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-29 15:11:42.126  1034  7159 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-29 15:11:42.126  1034  1376 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-29 15:11:42.126  1034  1376 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 15:11:42.126  1034  1376 E WifiStateMachine: useWiFiOffloading() : false
08-29 15:11:42.126  1034  1376 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 15:11:42.127  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:11:42.127  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:11:42.127  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:11:42.127  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:11:42.127  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 15:11:42.127  1034  1376 D WifiNative-wlan0: doBoolean: SET update_config 1
08-29 15:11:42.128  1034  1376 D WifiNative-wlan0: SET update_config 1: returned true
08-29 15:11:42.128  1034  1376 D WifiConfigStore: Loading config and enabling all networks 
08-29 15:11:42.128  1034  1376 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-29 15:11:42.128  1034  1376 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-29 15:11:42.129  1925  1925 D WfdService: Waiting for WifiP2p enabling
,08-29 15:11:42.133  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 15:11:42.136  1034  1376 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-29 15:11:42.138  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
,08-29 15:11:42.139  1034  1424 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
,08-29 15:11:42.140  6671  6671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:11:42.140  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:11:42.140  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:42.140  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 15:11:42.140  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:11:42.140  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 15:11:42.140  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:11:42.140  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:11:42.140  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 15:11:42.140  6671  6671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:11:42.140  6671  6671 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 15:11:42.141  6671  6671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:11:42.141  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:11:42.141  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:42.141  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 15:11:42.141  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:11:42.141  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 15:11:42.141  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:11:42.141  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:11:42.141  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 15:11:42.141  6671  6671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:11:42.141  6671  6671 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 15:11:42.146  1034  1376 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-29 15:11:42.146  1034  1376 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-29 15:11:42.147  1034  1376 D WifiStateMachine: enableVerboseLogging : level 2
08-29 15:11:42.147  1034  1376 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-29 15:11:42.148  1034  1376 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-29 15:11:42.148  1034  1376 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-29 15:11:42.148  1034  1376 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-29 15:11:42.148  1034  1376 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-29 15:11:42.148  1034  1376 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-29 15:11:42.149  1034  1376 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-29 15:11:42.149  1034  1376 D WifiNative-wl,an0: SET model_number LG-D855: returned true
08-29 15:11:42.149  1034  1376 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-29 15:11:42.149  1034  1376 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-29 15:11:42.149  1034  1376 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-29 15:11:42.150  1034  1376 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-29 15:11:42.150  1034  1376 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-29 15:11:42.150  1034  1376 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-29 15:11:42.151  1034  1376 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 15:11:42.151  1034  1376 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-29 15:11:42.152  1034  1376 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-29 15:11:42.152  1034  1376 D WifiNative-HAL: Setting external_sim to 1
08-29 15:11:42.152  1034  1376 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-29 15:11:42.152  1034  1376 D WifiNative-wlan0: SET external_sim 1: returned true
08-29 15:11:42.152  1034  1376 I WifiNative-HAL: startHal
08-29 15:11:42.152  1925  1925 D WfdsService: Supplicant Connection state is changed : true
08-29 15:11:42.152  1034  1376 D wifi    : setting scan oui 0xaf6d4540
08-29 15:11:42.152  1925  2271 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-29 15:11:42.152  1925  2271 D WfdsService: Set the WFDS Monitor: true
08-29 15:11:42.152  1925  2271 D WfdsMonitor: WfdsMonitorThread create
08-29 15:11:42.153  1034  1376 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 15:11:42.153  1034  1376 I WifiNative-HAL: startHal
08-29 15:11:42.153  1034  1376 D wifi    : setting scan oui 0xaf6d4540
08-29 15:11:42.153  1925  2271 D WfdsMonitor: WFDS Monitor is created and started
08-29 15:11:42.153  1925  2271 D WfdsService: WiFi: Supplicant connection re-established
08-29 15:11:42.153  1034  1376 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-29 15:11:42.154  1925  7161 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-29 15:11:42.154  1034  1376 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-29 15:11:42.155  1034  1376 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-29 15:11:42.155  7151  7151 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-29 15:11:42.155  1925  7161 E CtrlSupplicant: Succeed to open control connection
08-29 15:11:42.155  1034  1376 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-29 15:11:42.155  1925  7161 E CtrlSupplicant: Succeed to open monitor connection
08-29 15:11:42.155  1925  7161 D WfdsMonitor: Supplicant connection established
08-29 15:11:42.155  1034  1376 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-29 15:11:42.156  1925  2271 D WfdsService: Connected to the supplicant for wfds
08-29 15:11:42.156  7151  7151 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-29 15:11:42.156  1034  1376 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-29 15:11:42.156  1034  1376 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-29 15:11:42.156  7151  7151 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-29 15:11:42.157  1034  1376 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-29 15:11:42.157  1034  1376 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-29 15:11:42.157  7151  7151 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-29 15:11:42.157  1034  1376 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-29 15:11:42.158  1034  1376 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-29 15:11:42.158  7151  7151 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-29 15:11:42.158  1034  1376 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-29 15:11:42.158  1034  1376 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-29 15:11:42.158  7151  7151 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-29 15:11:42.159  1034  1376 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-29 15:11:42.159  1034  1376 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-29 15:11:42.159  7151  7151 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-29 15:11:42.159  1034  1376 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-29 15:11:42.160  1034  1376 E WifiNative: : [122,411,657 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-29 15:11:42.160  1034  1376 D WifiNative-wlan0: doBoolean: RECONNECT
08-29 15:11:42.161  1034  1376 D WifiNative-wlan0: RECONNECT: returned true
08-29 15:11:42.161  1034  1376 D WifiNative-wlan0: doString: [STATUS]
08-29 15:11:42.162  1034  7159 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-29 15:11:42.162  1034  7159 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-29 15:11:42.162  1034  1376 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-29 15:11:42.162  1034  1376 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 15:11:42.163  1034  1376 D WifiNative-wlan0: SET ps 1: returned true
08-29 15:11:42.164  1034  1374 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:42.164  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 3
08-29 15:11:42.164  1034  1034 D RttService: SCAN_AVAILABLE : 3
08-29 15:11:42.164  1034  1376 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-29 15:11:42.165  1034  1541 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:42.165  1034  1541 I WifiNative-HAL: startHal
08-29 15:11:42.165  1034  1541 D wifi    : getting scan capabilities on interface[1] = 0xaf6d4540
08-29 15:11:42.165  1034  1541 D wifi    : failed to get capabilities : -3
08-29 15:11:42.165  1034  1376 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-29 15:11:42.165  1034  1541 E WifiScanningService: could not get scan capabilities
08-29 15:11:42.165  1034  1542 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:42.165  1034  1376 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-29 15:11:42.166  1034  1376 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-29 15:11:42.166  1034  1376 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-29 15:11:42.167  1034  1376 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-29 15:11:42.167  1034  1376 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-29 15:11:42.167   310   892 D CommandListener: Setting iface cfg
08-29 15:11:42.167  1034  1376 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-29 15:11:42.167   310   892 D CommandListener: Trying to bring up p2p0
08-29 15:11:42.167  7151  7151 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-29 15:11:42.167  1034  1374 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-29 15:11:42.168  1034  1374 D LGWifiP2pService: P2pEnablingState
08-29 15:11:42.168  1034  1374 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:42.168  1034  1374 D LGWifiP2pService: P2p socket connection successful
08-29 15:11:42.168  1034  1376 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-29 15:11:42.168  1034  1374 D LGWifiP2pService: P2pEnabledState
08-29 15:11:42.168  1034  1376 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-29 15:11:42.169  1034  1376 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-29 15:11:42.169  1034  1376 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-29 15:11:42.169  7151  7151 E wpa_supplicant: disconnect_rssi_lvl: -100
08-29 15:11:42.169  1034  1376 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-29 15:11:42.170  1034  1376 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-29 15:11:42.170  1034  1376 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-29 15:11:42.170  1034  1376 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-29 15:11:42.172  7151  7151 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-29 15:11:42.173  7151  7151 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 15:11:42.173  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-29 15:11:42.173  1925  1925 D WfdsService: WifiP2pState is changed : true
08-29 15:11:42.173  1925  2271 D WfdsService: Receive the WFDS_ENABLE Method
08-29 15:11:42.173  7151  7151 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-29 15:11:42.173  7151  7151 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 15:11:42.173  1925  2271 D WfdsService: Set the WFDS Monitor: true
08-29 15:11:42.174  1925  2271 D WfdsService: Connected to the supplicant for wfds
08-29 15:11:42.174  1034  7159 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 15:11:42.174  1925  2271 D WfdsJNI : doCommand: WFDS_SET TRUE
08-29 15:11:42.174  1034  7159 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 15:11:42.174  1034  7159 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 15:11:42.174  1034  7159 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 15:11:42.174  1034  7159 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 15:11:42.174  1034  7159 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 15:11:42.174  1034  7159 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 15:11:42.174  1034  7159 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 15:11:42.174  7151  7151 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-29 15:11:42.174  7151  7151 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 15:11:42.174  1925  2271 D WfdsService: selectPreferredScanChannel [36]
08-29 15:11:42.174  1925  2271 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-29 15:11:42.175  1034  7159 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 15:11:42.175  1034  7159 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 15:11:42.175  1034  7159 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 15:11:42.175  1034  7159 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 15:11:42.175  1034  1376 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-29 15:11:42.176  1034  1376 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-29 15:11:42.176  1034  1376 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-29 15:11:42.176  1034  1376 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-29 15:11:42.176  1925  7161 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 15:11:42.176  1034  1376 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-29 15:11:42.176  7151  7151 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-29 15:11:42.177  7151  7151 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 15:11:42.177  1034  7159 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-29 15:11:42.177  1034  7159 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 15:11:42.177  1034  1376 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-29 15:11:42.177  1034  1376 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-29 15:11:42.177  1034  7159 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 15:11:42.176  1925  7161 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 15:11:42.177  1034  7159 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 15:11:42.178  1034  1374 D LGWifiP2pService: sending p2p connection changed broadcast
08-29 15:11:42.178  1034  1376 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-29 15:11:42.178  1034  1376 D WifiNative-wlan0: doBoolean: SCAN
08-29 15:11:42.179  1034  1376 D WifiNative-wlan0: SCAN: returned false
08-29 15:11:42.179  1034  1376 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=122431  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-29 15:11:42.182  1034  1374 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-29 15:11:42.183  1034  1374 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-29 15:11:42.183  1034  1376 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=122434  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-29 15:11:42.183  1034  1374 D WifiNative-p2p0: doBoolean: SET device_name G3
08-29 15:11:42.184  1034  1374 D WifiNative-p2p0: SET device_name G3: returned true
08-29 15:11:42.184  1034  1374 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-29 15:11:42.184  1034  1374 D LGWifiP2pService: before postfix = G3
08-29 15:11:42.184  1034  1374 D WifiServerServiceExt: postfix byte check : 2
08-29 15:11:42.184  1034  1374 D LGWifiP2pService: after postfix = G3
08-29 15:11:42.184  1034  1374 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-29 15:11:42.184  1034  1376 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 15:11:42.184  1034  1376 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 15:11:42.185  1034  1376 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 15:11:42.185  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 15:11:42.185  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 15:11:42.185  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:11:42.186  1925  1925 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-29 15:11:42.186  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:11:42.186  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-29 15:11:42.186  1925  1925 D WfdsService: isConnected: false
08-29 15:11:42.187  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 15:11:42.188  1034  1374 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-29 15:11:42.188  1034  1374 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-29 15:11:42.189  1034  1374 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-29 15:11:42.189  1034  1374 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-29 15:11:42.190  1034  1374 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-29 15:11:42.190  1034  1374 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
,08-29 15:11:42.190  1034  1374 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-29 15:11:42.190  1034  1374 D WifiNative-HAL: p2pGetDeviceAddress
08-29 15:11:42.190  1034  1376 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 15:11:42.191  1034  1376 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 15:11:42.191  1034  1374 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-29 15:11:42.191  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 15:11:42.192  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING
08-29 15:11:42.192  1034  1374 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-29 15:11:42.192  1034  1374 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-29 15:11:42.192  1034  1374 D WifiNative-p2p0: P2P_FLUSH: returned true
08-29 15:11:42.193  1034  1374 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-29 15:11:42.193  1034  1374 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-29 15:11:42.193  1034  1374 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-29 15:11:42.193  1034  1374 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-29 15:11:42.194  1925  1925 I WfdStateTracker: handleP2pThisDeviceChanged
08-29 15:11:42.194  1034  1374 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-29 15:11:42.194  1925  1925 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-29 15:11:42.195  1925  1925 D WfdsService: Update P2p Interface State: 3
08-29 15:11:42.201  1034  1374 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-29 15:11:42.201  1034  1374 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-29 15:11:42.201  1034  1374 D LGWifiP2pService: InactiveState
08-29 15:11:42.201  1034  1374 D LGWifiP2pService: InactiveState{ when=-26ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:42.201  1034  1374 D LGWifiP2pService: P2pEnabledState{ when=-27ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:42.201  1034  1374 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-29 15:11:42.202  7151  7151 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-29 15:11:42.203  7151  7151 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 15:11:42.203  1925  7161 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 15:11:42.203  7151  7151 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-29 15:11:42.204  7151  7151 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 15:11:42.204  1034  7159 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 15:11:42.204  1034  7159 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 15:11:42.204  1034  7159 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 15:11:42.204  1034  7159 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 15:11:42.204  1034  7159 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 15:11:42.204  7151  7151 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 15:11:42.205  1034  7159 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 15:11:42.205  1034  7159 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 15:11:42.205  1034  7159 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 15:11:42.205  1034  7159 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 15:11:42.205  1925  7161 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 15:11:42.205  1034  7159 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 15:11:42.205  1925  7161 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 15:11:42.205  1034  7159 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 15:11:42.205  1034  7159 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 15:11:42.205  1034  1374 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-29 15:11:42.205  1034  1374 D LGWifiP2pService: InactiveState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:42.205  1034  1374 D LGWifiP2pService: P2pEnabledState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:42.205  1034  1374 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:42.205  1034  1374 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:42.205  1034  1374 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:42.206  1034  1374 D LGWifiP2pService: InactiveState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:42.206  1034  1374 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:42.206  1034  1374 D LGWifiP2pService: DefaultState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:42.206  1034  1374 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:42.206  1034  1374 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:42.206  1034  1374 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:42.206  1034  1374 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:42.206  1034  1374 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:42.206  1034  1374 D LGWifiP2pService: DefaultState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:42.206  1034  1034 E WifiServerServiceExt: No p2p device connected
08-29 15:11:42.207  1925  2271 W WfdsService: DefaultState - msg [9441285] is not handled
,08-29 15:11:42.251  7128  7128 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-29 15:11:42.285  7128  7128 I HubEmail: JNI_OnLoad()
08-29 15:11:42.285  7128  7128 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-29 15:11:42.285  7128  7128 I HubEmail: registerNatives()
08-29 15:11:42.285  7128  7128 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-29 15:11:42.285  7128  7128 I HubEmail: registerNativeMethods()
08-29 15:11:42.285  7128  7128 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-29 15:11:42.285  7128  7128 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,08-29 15:11:42.295  3379  3379 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-29 15:11:42.295  3379  3379 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-29 15:11:42.295  3379  3379 I LgeMiscReceiver: networkInfo.isConnected() = false
08-29 15:11:42.364  1034  1874 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7170 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-29 15:11:42.370  7128  7167 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 15:11:42.372  6994  7168 W FormManager: Network not available. Please check & try again.
08-29 15:11:42.384  6994  7169 V FormManager: Network unavailable.
,08-29 15:11:42.389  6994  7169 V FormManager: Network unavailable.
08-29 15:11:42.397  1034  2034 I ActivityManager: Killing 6621:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-29 15:11:42.457  1034  1598 W libprocessgroup: failed to open /acct/uid_10061/pid_6621/cgroup.procs: No such file or directory
08-29 15:11:42.554  7170  7170 D LgDataFeature: LgDataFeature() Constructor: none
08-29 15:11:42.554  7170  7170 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 15:11:42.558  7170  7170 D PhoneMonitor: Register our PhoneStateListener
,08-29 15:11:42.584  7170  7170 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-29 15:11:42.588  7170  7170 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-29 15:11:42.620  7170  7170 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-29 15:11:42.621  7170  7170 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-29 15:11:42.622  7170  7170 D TelephonyAutoProfiling: [parse] Load xml
,08-29 15:11:42.627  7170  7170 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-29 15:11:42.627  7170  7170 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-29 15:11:42.627  7170  7170 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-29 15:11:42.627  7170  7170 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-29 15:11:42.628  7170  7170 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-29 15:11:42.628  7170  7170 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-29 15:11:42.628  7170  7170 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-29 15:11:42.628  7170  7170 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-29 15:11:42.628  7170  7170 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-29 15:11:42.628  7170  7170 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-29 15:11:42.628  7170  7170 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-29 15:11:42.628  7170  7170 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-29 15:11:42.628  7170  7170 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-29 15:11:42.628  7170  7170 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-29 15:11:42.628  7170  7170 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-29 15:11:42.628  7170  7170 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-29 15:11:42.628  7170  7170 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-29 15:11:42.640  7170  7170 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-29 15:11:42.666  1034  2011 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7193 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 15:11:42.668  1034  2011 I ActivityManager: Killing 6171:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-29 15:11:42.715  1034  1049 W libprocessgroup: failed to open /acct/uid_10097/pid_6171/cgroup.procs: No such file or directory
,08-29 15:11:42.775  1034  7159 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-29 15:11:42.776  7151  7151 E wpa_supplicant: USIM:  scard_init function
08-29 15:11:42.776  1034  7159 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-29 15:11:42.776  7151  7151 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-29 15:11:42.776  1034  7159 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-29 15:11:42.776  1034  7159 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
08-29 15:11:42.776  1034  7159 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
,08-29 15:11:42.776  1034  7159 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-29 15:11:42.776  1034  7159 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-29 15:11:42.779  1034  1376 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
08-29 15:11:42.781  1034  1376 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
08-29 15:11:42.782  1034  1376 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
08-29 15:11:42.784  1034  1376 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
08-29 15:11:42.784  1034  1376 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-29 15:11:42.789  1034  1376 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=123041  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-29 15:11:42.796  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 15:11:42.796  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-29 15:11:42.799  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 15:11:42.801  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:11:42.801  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:11:42.801  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
,08-29 15:11:42.804  1034  1376 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=123055  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-29 15:11:42.806  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:11:42.807  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 15:11:42.807  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-29 15:11:42.809  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 15:11:42.809  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-29 15:11:42.821  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 15:11:42.821  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 15:11:42.822  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 15:11:42.903  1034  7159 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-29 15:11:42.903  7151  7151 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-29 15:11:42.903  1034  7159 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,08-29 15:11:42.906  1034  7159 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-29 15:11:42.906  1034  7159 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-29 15:11:42.906  1034  7159 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 15:11:42.906  1034  7159 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 15:11:42.907  1034  1376 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=123158  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-29 15:11:42.907  1034  1376 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=123159  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-29 15:11:42.908  1034  1376 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=123159
08-29 15:11:42.908  1034  1376 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=123160
08-29 15:11:42.909  1034  1376 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=123160
08-29 15:11:42.909  1034  1376 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=123161
08-29 15:11:42.909  1034  1376 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=123161
08-29 15:11:42.910  1034  1376 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=123161  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-29 15:11:42.926  7151  7151 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 15:11:42.926  1034  7159 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 15:11:42.926  7151  7151 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 15:11:42.926  1034  7159 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 15:11:42.927  1034  7159 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-29 15:11:42.927  1034  7159 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 15:11:42.927  1034  7159 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 15:11:42.927  1034  7159 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-29 15:11:42.927  1034  7159 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-29 15:11:42.927  1034  7159 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 15:11:42.928  1034  7159 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 15:11:42.928  1034  7159 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 15:11:42.964  1034  1758 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7211 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-29 15:11:42.970  1034  1758 I ActivityManager: Killing 6746:com.lge.eula/1000 (adj 15): empty #17
08-29 15:11:43.006  1034  1376 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=123258  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-29 15:11:43.008  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 15:11:43.008  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-29 15:11:43.010  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 15:11:43.011  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:11:43.011  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:11:43.011  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-29 15:11:43.017  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:11:43.017  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:11:43.017  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-29 15:11:43.018  1034  1874 W libprocessgroup: failed to open /acct/uid_1000/pid_6746/cgroup.procs: No such file or directory
,08-29 15:11:43.027  1034  1376 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=123278  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-29 15:11:43.027  1034  1116 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-29 15:11:43.028  1034  1376 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=123279  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-29 15:11:43.028  1034  1376 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=123280
08-29 15:11:43.029  1034  1376 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=123280
08-29 15:11:43.029  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 15:11:43.029  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-29 15:11:43.029  1034  1376 D WifiNative-wlan0: doString: [STATUS]
,08-29 15:11:43.030  1034  7159 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 15:11:43.030  1034  7159 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 15:11:43.031  1034  1376 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-29 15:11:43.032  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 15:11:43.032  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 15:11:43.033  1034  1376 I WifiServiceExtension: setVHTCapabilityType  : false
08-29 15:11:43.034  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 15:11:43.041  1034  1376 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-29 15:11:43.041  1034  1376 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-29 15:11:43.044  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:11:43.045  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:11:43.045  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-29 15:11:43.053  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:11:43.053  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:11:43.053  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-29 15:11:43.055  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 15:11:43.055  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 15:11:43.056  1034  1376 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-29 15:11:43.057  1034  1376 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 15:11:43.057  1034  1376 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-29 15:11:43.057  1034  1452 D ConnectivityService: Got NetworkAgent Messenger
08-29 15:11:43.057  1034  1452 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-29 15:11:43.057  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 15:11:43.057  1034  1452 D ConnectivityService: NetworkAgent connected
,08-29 15:11:43.057  1034  1376 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 15:11:43.057  1034  1376 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-29 15:11:43.060  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 15:11:43.060  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 15:11:43.061  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 15:11:43.067  1034  1376 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-29 15:11:43.067  1034  1376 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 15:11:43.067  1034  1376 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-29 15:11:43.067  1034  1376 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 15:11:43.067  1034  1376 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-29 15:11:43.074  1034  1376 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-29 15:11:43.076   310   892 D CommandListener: Setting iface cfg
08-29 15:11:43.078  1034  1376 E WifiStateMachine: Start Dhcp Watchdog 2
08-29 15:11:43.078  1034  7229 D DhcpStateMachine: StoppedState
,08-29 15:11:43.079  1034  7229 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 15:11:43.079  1034  7229 D DhcpStateMachine: WaitBeforeStartState
08-29 15:11:43.079  1034  1376 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=123331  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 15:11:43.080  1034  1376 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=123331  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 15:11:43.080  1034  1376 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=123332  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 15:11:43.081  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 15:11:43.081  1034  1034 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-29 15:11:43.084  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 15:11:43.084  1034  1034 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-29 15:11:43.084  1034  1376 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-29 15:11:43.084  1034  1376 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-29 15:11:43.085  1034  1376 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-29 15:11:43.085  1034  1376 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-29 15:11:43.086  1034  1376 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-29 15:11:43.086  1034  1376 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 15:11:43.087  1034  1376 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=123338  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 15:11:43.087  1034  1376 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=123339  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 15:11:43.088  1034  1376 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=123339  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 15:11:43.089  1034  1376 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:77400] from screen [on:0 period:-697479439] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-29 15:11:43.090  1034  1376 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-697479438] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-29 15:11:43.090  1034  1376 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-29 15:11:43.094  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 15:11:43.095  1034  1376 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 15:11:43.096  1034  1452 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-29 15:11:43.096  1034  1376 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 15:11:43.097  1034  1376 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 15:11:43.098  1034  1376 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 15:11:43.098  1034  1376 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 15:11:43.099  1034  1376 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 15:11:43.099  1034  1452 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-29 15:11:43.100  1034  1376 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=109,0,0
08-29 15:11:43.100  1034  1376 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=109,0,0
08-29 15:11:43.101  1034  1376 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-29 15:11:43.101  7151  7151 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-29 15:11:43.101  1034  1376 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-29 15:11:43.102  1034  1376 D WifiNative-wlan0: doBoolean: SET ps 0
08-29 15:11:43.102  1034  1376 D WifiNative-wlan0: SET ps 0: returned true
08-29 15:11:43.103  1034  1376 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-29 15:11:43.103  7151  7151 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-29 15:11:43.103  1034  1376 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-29 15:11:43.104  1034  1374 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@16513bbf target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:43.104  1034  1374 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@16513bbf target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:43.104  1034  7229 D DhcpStateMachine: WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:43.104  1034  7229 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-29 15:11:43.105  1034  1376 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-29 15:11:43.105  1034  1376 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-29 15:11:43.106  1034  1376 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-29 15:11:43.107   310   892 D CommandListener: Setting iface cfg
08-29 15:11:43.107   310   892 D CommandListener: Trying to bring up wlan0
,08-29 15:11:43.109  1034  1376 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-29 15:11:43.139  1034  1889 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7230 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 15:11:43.140  1034  1889 I ActivityManager: Killing 6767:com.lge.bnr/1000 (adj 15): empty #17
08-29 15:11:43.258  1034  1376 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,08-29 15:11:43.259  1034  1376 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 15:11:43.261  1034  1376 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 15:11:43.262  1034  1376 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 15:11:43.263  1034  1376 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 15:11:43.264  1034  1376 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 15:11:43.265  1034  1452 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-29 15:11:43.267  1034  1376 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-29 15:11:43.268  1034  1957 W libprocessgroup: failed to open /acct/uid_1000/pid_6767/cgroup.procs: No such file or directory
08-29 15:11:43.273  1034  1376 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
,08-29 15:11:43.273  1034  1376 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-29 15:11:43.273  1034  1374 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:43.273  1034  1374 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:43.274  7151  7151 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-29 15:11:43.274  1034  1376 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-29 15:11:43.274  1034  1376 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-29 15:11:43.274  7151  7151 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-29 15:11:43.275  1034  1376 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-29 15:11:43.275  1034  1376 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 15:11:43.283  1034  1374 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:43.284  1034  1374 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:43.284  1034  1374 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:43.291  1034  1376 D WifiNative-wlan0: SET ps 1: returned true
08-29 15:11:43.292  1034  1376 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-29 15:11:43.292  1034  1376 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-29 15:11:43.292  1034  1376 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,08-29 15:11:43.296  1034  1452 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,08-29 15:11:43.296  1034  1452 D ConnectivityService: ignoring duplicate network state non-change
08-29 15:11:43.297  1034  1452 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-29 15:11:43.298  1034  1452 D ConnectivityService: Adding iface wlan0 to network 101
08-29 15:11:43.300  1034  1376 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-29 15:11:43.306  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 15:11:43.306  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-29 15:11:43.308  7230  7230 I art     : Almond Protected OAT
,08-29 15:11:43.315  1034  7229 D DhcpStateMachine: DHCPV4 request on wlan0
08-29 15:11:43.316  1034  7229 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-29 15:11:43.316  1034  7229 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,08-29 15:11:43.304  7249  7249 W dhcpcd  : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 15:11:43.304  7249  7249 W dhcpcd  : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 15:11:43.327  1034  1376 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 15:11:43.327  1034  1376 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 15:11:43.328  1034  1376 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 15:11:43.328  1034  1376 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 15:11:43.329  1034  1376 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 15:11:43.329  1034  1376 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 15:11:43.329  1034  1452 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-29 15:11:43.330  1034  1452 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-29 15:11:43.330  7249  7249 I dhcpcd  : version 5.5.6 starting
08-29 15:11:43.330  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:11:43.330  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:11:43.330  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,08-29 15:11:43.332  7249  7249 E dhcpcd  : get_duid: m
08-29 15:11:43.332  7249  7249 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-29 15:11:43.332  7249  7249 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-29 15:11:43.334  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 15:11:43.334  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 15:11:43.338  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 15:11:43.341  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 15:11:43.341  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:11:43.341  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 15:11:43.341  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:11:43.341  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-29 15:11:43.342  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 15:11:43.344  1034  1452 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-29 15:11:43.344  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-29 15:11:43.345   310   892 E Netd    : netlink response contains error (File exists)
08-29 15:11:43.345  1034  1452 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-29 15:11:43.346  1034  1452 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-29 15:11:43.346  1034  1452 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-29 15:11:43.346  1034  1452 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-29 15:11:43.347  1925  1925 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-29 15:11:43.354  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:11:43.354  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:11:43.354  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-29 15:11:43.354  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-29 15:11:43.362  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:11:43.362  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 15:11:43.363  1034  1452 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-29 15:11:43.363  1034  1452 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-29 15:11:43.363  1034  1452 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-29 15:11:43.363  1034  1452 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-29 15:11:43.364  1034  7228 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:43.364  1034  7228 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-29 15:11:43.364  1034  7228 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:43.364  1034  7228 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-29 15:11:43.366  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-29 15:11:43.367  1034  1452 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 15:11:43.367  1034  1452 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 15:11:43.367  1034  1452 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-29 15:11:43.367  1034  1452 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 15:11:43.367  1034  1452 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-29 15:11:43.367  1034  1452 D ConnectivityService: currentScore = 0, newScore = 20
08-29 15:11:43.367  1034  1452 D ConnectivityService:    accepting network in place of null
08-29 15:11:43.367  1034  1452 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 15:11:43.370  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 15:11:43.370  1587  1587 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-29 15:11:43.370  1034  1376 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 15:11:43.370  1034  1376 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 15:11:43.371  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 15:11:43.371   310  7260 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-29 15:11:43.373  1034  1452 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for, legacy network type 1
08-29 15:11:43.373  1034  1452 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-29 15:11:43.373  1034  1452 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-29 15:11:43.376  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 15:11:43.376  1587  1587 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-29 15:11:43.377  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 15:11:43.383  1836  1836 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 15:11:43.387  1034  1452 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-29 15:11:43.387  1034  1452 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-29 15:11:43.389  1034  1034 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-29 15:11:43.391  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-29 15:11:43.391  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-29 15:11:43.391  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-29 15:11:43.391  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-29 15:11:43.395  1034  1452 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-29 15:11:43.396  1034  1452 D ConnectivityService: validation of new default Network = false
08-29 15:11:43.397  1034  1452 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-29 15:11:43.397  1034  1452 D DSQN    : enableDataServiceNotify 
08-29 15:11:43.397  1034  1452 D DSQN    : start dsqn bin
08-29 15:11:43.399  7249  7249 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-29 15:11:43.399  7249  7249 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-29 15:11:43.399  7249  7249 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-29 15:11:43.399  7249  7249 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-29 15:11:43.399  7249  7249 D dhcpcd  : wlan0: sending REQUEST (xid 0x5c17f133), next in 4.89 seconds
08-29 15:11:43.402  1034  1452 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-29 15:11:43.402  1034  1452 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 15:11:43.402  1034  1452 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 15:11:43.402  1034  1452 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 15:11:43.384  7264  7264 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 15:11:43.384  7264  7264 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 15:11:43.402  1587  2055 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-29 15:11:43.405  1034  1373 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-29 15:11:43.417  7264  7264 E DSQN    : DSQN ssw
,08-29 15:11:43.437  7230  7230 D WeatherApplication: removeAccount
08-29 15:11:43.438  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 15:11:43.438  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 15:11:43.439  1801  7268 I CheckinService: active receiver: enabled
08-29 15:11:43.439  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 15:11:43.447  7230  7230 D WeatherApplication: Account.length = 0
08-29 15:11:43.448  7230  7230 E WeatherApplication: OPERATOR:OPEN
08-29 15:11:43.449  1801  7268 I CheckinService: Preparing to send checkin request
08-29 15:11:43.449  1801  7268 I EventLogService: Accumulating logs since 1472476238385
08-29 15:11:43.451  7249  7249 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
08-29 15:11:43.451  7230  7230 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:11:43
08-29 15:11:43.454  7230  7230 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-29 15:11:43.454  7230  7230 D Weather.Utils: 2 : All the weather widget is gone.
08-29 15:11:43.456  7230  7230 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-29 15:11:43.458  7230  7230 D WeatherAncestor: connectivity changed - connection : true
,08-29 15:11:43.459  7230  7230 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-29 15:11:43.468  7230  7230 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-29 15:11:43.468  7230  7230 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-29 15:11:43.468  7230  7230 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-29 15:11:43.473  7249  7249 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-29 15:11:43.474  7249  7249 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-29 15:11:43.474  7249  7249 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-29 15:11:43.474  7249  7249 D dhcpcd  : wlan0: adding default route via 192.168.1.1
,08-29 15:11:43.475  7249  7249 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-29 15:11:43.475  7249  7249 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-29 15:11:43.475  7249  7249 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-29 15:11:43.475  7249  7249 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-29 15:11:43.491  1801  7268 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-29 15:11:43.501  7230  7230 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-29 15:11:43.501  7230  7230 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:11:43
,08-29 15:11:43.545  1034  2034 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7276 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 15:11:43.547  1034  2034 I ActivityManager: Killing 2134:com.lge.music/u0a34 (adj 15): empty #17
08-29 15:11:43.566   316  2154 V AudioFlinger: 2134 died, releasing its sessions
08-29 15:11:43.566   316  2154 V AudioFlinger:  pid 1836 @ 0
08-29 15:11:43.566   316  2154 V AudioFlinger:  pid 3379 @ 1
08-29 15:11:43.566   316  2154 V AudioFlinger:  pid 3379 @ 2
,08-29 15:11:43.618  1034  1889 W libprocessgroup: failed to open /acct/uid_10034/pid_2134/cgroup.procs: No such file or directory
08-29 15:11:43.719  1034  7229 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-29 15:11:43.720  1034  7229 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-29 15:11:43.721  1034  7229 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-29 15:11:43.721  1034  7229 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-29 15:11:43.721  1034  7229 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-29 15:11:43.721  1034  7229 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-29 15:11:43.721  1034  7229 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false,
08-29 15:11:43.721  1034  7229 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-29 15:11:43.721  1034  7229 D DhcpStateMachine: RunningState
,08-29 15:11:43.722  1034  1049 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7309 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
08-29 15:11:43.741   348   348 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 440us total 19.748ms
,08-29 15:11:43.759   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 363us total 17.014ms
,08-29 15:11:43.762   280   438 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-29 15:11:43.762   280   438 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-29 15:11:43.762   280   438 W Vold    : Returning OperationFailed - no handler for errno 0
08-29 15:11:43.763  7276  7327 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-29 15:11:43.765   280   438 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-29 15:11:43.765   280   438 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-29 15:11:43.765   280   438 W Vold    : Returning OperationFailed - no handler for errno 0
08-29 15:11:43.765  7276  7327 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-29 15:11:43.773   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 285us total 14.032ms
08-29 15:11:43.782   280   438 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-29 15:11:43.782   280   438 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-29 15:11:43.782   280   438 W Vold    : Returning OperationFailed - no handler for errno 0
08-29 15:11:43.782  7276  7331 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-29 15:11:43.784   280   438 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-29 15:11:43.785   280   438 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-29 15:11:43.785   280   438 W Vold    : Returning OperationFailed - no handler for errno 0
08-29 15:11:43.785  7276  7331 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-29 15:11:43.791  7309  7309 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-29 15:11:43.791  7309  7309 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-29 15:11:43.811  7309  7309 I MultiDex: VM with version 2.1.0 has multidex support
08-29 15:11:43.811  7309  7309 I MultiDex: install
,08-29 15:11:43.811  7309  7309 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-29 15:11:43.818  7309  7309 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-29 15:11:44.006  7276  7276 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-29 15:11:44.020  7276  7276 I LibraryLoader: Loading: webviewchromium
,08-29 15:11:44.024  7276  7276 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 4286-4290)
08-29 15:11:44.024  7276  7276 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 15:11:44.032  7276  7276 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {70f59cf}
,08-29 15:11:44.034  7276  7276 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 15:11:44.034  7276  7276 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-29 15:11:44.048  7276  7276 I BrowserStartupController: Initializing chromium process, renderers=0
08-29 15:11:44.049  7276  7276 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-29 15:11:44.069  7276  7276 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-29 15:11:44.071  7276  7276 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-29 15:11:44.071  7276  7276 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-29 15:11:44.072   316   316 V AudioPolicyService: registerClient() client 0xb558a620, uid 10093
08-29 15:11:44.073  7276  7352 W AudioManagerAndroid: Requires BLUETOOTH permission
08-29 15:11:44.090  7276  7276 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-29 15:11:44.090  7276  7276 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-29 15:11:44.090  7276  7276 I Adreno-EGL: Build Date: 12/12/14 금
08-29 15:11:44.090  7276  7276 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-29 15:11:44.090  7276  7276 I Adreno-EGL: Remote Branch: 
08-29 15:11:44.090  7276  7276 I Adreno-EGL: Local Patches: 
08-29 15:11:44.090  7276  7276 I Adreno-EGL: Reconstruct Branch: 
,08-29 15:11:44.197  7309  7325 D LgDataFeature: LgDataFeature() Constructor: none
08-29 15:11:44.197  7309  7325 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 15:11:44.241  1034  1929 D WifiServiceImplEx: setWifiEnabled: false pid=6671, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-29 15:11:44.241  1034  1929 D WifiService: setWifiEnabled: false pid=6671, uid=10118
08-29 15:11:44.241  1034  1929 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 15:11:44.258  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 15:11:44.258  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 15:11:44.258  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-29 15:11:44.258  1034  1376 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-29 15:11:44.258  1034  1376 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-29 15:11:44.259  1034  1376 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-29 15:11:44.259  1034  1376 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-29 15:11:44.259  1034  1376 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-29 15:11:44.259  1034  1376 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-29 15:11:44.259  1034  1376 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 15:11:44.259  1034  1376 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-29 15:11:44.260  1034  1376 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
,08-29 15:11:44.260  1034  1376 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-29 15:11:44.266  1034  1376 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-29 15:11:44.266  1034  1376 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-29 15:11:44.266  1034  1374 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:44.266  1034  1374 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:44.266  7151  7151 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-29 15:11:44.267  1034  1376 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-29 15:11:44.267  1034  1376 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 15:11:44.267  1034  1376 D WifiNative-wlan0: SET ps 1: returned true
08-29 15:11:44.268  1034  7229 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:44.268   310   892 D CommandListener: Clearing all IP addresses on wlan0
,08-29 15:11:44.274  7364  7364 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
08-29 15:11:44.296  1034  1376 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 15:11:44.297  1034  1376 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 15:11:44.297  1034  1376 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 15:11:44.298  1034  1376 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 15:11:44.298  1034  1376 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 15:11:44.299  1034  1376 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,08-29 15:11:44.302  1034  1452 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-29 15:11:44.302  1034  1452 D ConnectivityService: ignoring duplicate network state non-change
08-29 15:11:44.302  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-29 15:11:44.303  1034  1374 D LGWifiP2pService: InactiveState{ when=-8ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:44.304  1034  1374 D LGWifiP2pService: P2pEnabledState{ when=-8ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:44.304  1034  1374 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@144bf452
08-29 15:11:44.304  1925  1925 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-29 15:11:44.302  1034  1452 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
08-29 15:11:44.304  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 15:11:44.304  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 15:11:44.305  1034  1376 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-29 15:11:44.310  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 15:11:44.313  1034  1598 I art     : Explicit concurrent mark sweep GC freed 102649(4MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 2.207ms total 146.131ms
,08-29 15:11:44.319  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:11:44.319  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:11:44.319  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 15:11:44.319  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-29 15:11:44.319  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:11:44.319  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:11:44.319  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 15:11:44.319  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 1
08-29 15:11:44.319  1034  1034 D RttService: SCAN_AVAILABLE : 1
08-29 15:11:44.320  1034  1541 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:44.320  1034  1542 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:44.320  1034  1374 D LGWifiP2pService: P2pDisablingState
08-29 15:11:44.320  1034  1374 D LGWifiP2pService: P2pDisablingState{ when=-17ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:44.320  1034  1374 D LGWifiP2pService: p2p socket connection lost
08-29 15:11:44.321  1034  1374 D LGWifiP2pService: P2pDisabledState
08-29 15:11:44.321  1034  1376 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-29 15:11:44.322  1034  1376 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-29 15:11:44.322  7151  7151 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-29 15:11:44.322  1034  1376 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-29 15:11:44.322  1034  1376 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 15:11:44.322  1034  1376 D WifiNative-wlan0: SET ps 1: returned true
08-29 15:11:44.322  1034  1374 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:44.322  1034  1374 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:44.323  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-29 15:11:44.323  1925  1925 D WfdsService: WifiP2pState is changed : false
08-29 15:11:44.323  1925  2271 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-29 15:11:44.323  1925  2271 D WfdsService: Set the WFDS Monitor: false
08-29 15:11:44.324  1925  2271 D WfdsMonitor: WFDS Monitor is stopped
08-29 15:11:44.324  1925  2271 D WfdsService: STATE : WfdsDisabledState - enter
08-29 15:11:44.324  1925  7161 D CtrlSupplicant: Received on exit socket, terminate
08-29 15:11:44.324  1925  7161 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-29 15:11:44.324  1925  7161 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-29 15:11:44.324  1925  7161 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-29 15:11:44.325  1925  2273 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-29 15:11:44.326  1925  2271 W WfdsService: DefaultState - msg [9445378] is not handled
08-29 15:11:44.334  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 15:11:44.334  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 15:11:44.338  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 15:11:44.339  7276  7276 I NSApplication: Starting up...
08-29 15:11:44.340  7364  7364 I dex2oat : dex2oat took 66.557ms (threads: 4)
08-29 15:11:44.354   310   892 D CommandListener: Clearing all IP addresses on wlan0
,08-29 15:11:44.355  1034  1452 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-29 15:11:44.355  1034  1452 D DSQN    : disableDataServiceNotify
08-29 15:11:44.355  1034  1452 D DSQN    : stop dsqn bin
08-29 15:11:44.356  7309  7325 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-29 15:11:44.356  7309  7325 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-29 15:11:44.356  7309  7325 I Adreno-EGL: Build Date: 12/12/14 금
08-29 15:11:44.356  7309  7325 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-29 15:11:44.356  7309  7325 I Adreno-EGL: Remote Branch: 
08-29 15:11:44.356  7309  7325 I Adreno-EGL: Local Patches: 
08-29 15:11:44.356  7309  7325 I Adreno-EGL: Reconstruct Branch: 
08-29 15:11:44.369  1034  1929 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7376 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-29 15:11:44.370  1034  1929 I ActivityManager: Killing 6101:com.android.vending/u0a44 (adj 15): empty #17
08-29 15:11:44.383  1034  1452 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-29 15:11:44.383  1034  1452 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 15:11:44.383  1034  1452 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-29 15:11:44.383  1034  1452 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-29 15:11:44.383  1034  1452 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-29 15:11:44.383  1587  2055 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-29 15:11:44.383  1034  1452 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-29 15:11:44.383  1034  1452 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-29 15:11:44.384  1034  1452 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-29 15:11:44.428  7309  7325 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-29 15:11:44.428  7309  7325 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-29 15:11:44.428  7309  7325 I Adreno-EGL: Build Date: 12/12/14 금
08-29 15:11:44.428  7309  7325 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-29 15:11:44.428  7309  7325 I Adreno-EGL: Remote Branch: 
08-29 15:11:44.428  7309  7325 I Adreno-EGL: Local Patches: 
08-29 15:11:44.428  7309  7325 I Adreno-EGL: Reconstruct Branch: 
,08-29 15:11:44.447  1034  1376 D WifiNative-p2p0: doBoolean: TERMINATE
08-29 15:11:44.448  1034  1376 D WifiNative-p2p0: TERMINATE: returned true
08-29 15:11:44.448  1034  1376 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 15:11:44.448  1034  1376 E WifiStateMachine: useWiFiOffloading() : false
08-29 15:11:44.448  1034  1376 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-29 15:11:44.448  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-29 15:11:44.451  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,08-29 15:11:44.451  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 15:11:44.455  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:11:44.455  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:11:44.455  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 15:11:44.455  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 15:11:44.468  1034  1049 W libprocessgroup: failed to open /acct/uid_10044/pid_6101/cgroup.procs: No such file or directory
,08-29 15:11:44.478  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 15:11:44.478  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-29 15:11:44.478  1034  1452 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-29 15:11:44.479  1034  1452 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-29 15:11:44.479  1034  1452 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-29 15:11:44.479  1034  1452 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 15:11:44.479  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-29 15:11:44.479  1034  1452 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 15:11:44.479  1034  1376 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 15:11:44.479  1034  1452 D NetworkManagementService: Removing idletimer
08-29 15:11:44.479  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 15:11:44.479  1034  1376 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 15:11:44.479  1034  1452 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:11:44.479  1034  1034 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-29 15:11:44.480  1836  1836 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 15:11:44.480  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-29 15:11:44.480  1034  1452 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
08-29 15:11:44.481  6671  6671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:11:44.481  1034  7229 D DhcpStateMachine: StoppedState
08-29 15:11:44.481  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:11:44.481  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:44.481  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 15:11:44.481  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 15:11:44.481  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 15:11:44.481  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:11:44.481  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:11:44.481  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 15:11:44.481  6671  6671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:11:44.481  1034  7229 D DhcpStateMachine: StoppedState{ when=-158ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-29 ,15:11:44.481  6671  6671 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 15:11:44.483  6671  6671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:11:44.483  1034  1373 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-29 15:11:44.483  1034  1373 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-29 15:11:44.483  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:11:44.483  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:44.483  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 15:11:44.483  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 15:11:44.483  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 15:11:44.483  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:11:44.483  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:11:44.483  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 15:11:44.483  6671  6671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:11:44.483  6671  6671 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 15:11:44.484  1034  1376 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-29 15:11:44.484  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-29 15:11:44.484  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-29 15:11:44.484  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-29 15:11:44.484  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-29 15:11:44.484  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-29 15:11:44.484  1034  1376 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-29 15:11:44.484  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-29 15:11:44.484  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-29 15:11:44.484  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-29 15:11:44.505  7376  7376 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 15:11:44.515  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 15:11:44.516  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 15:11:44.517  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 15:11:44.531  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 15:11:44.533  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 15:11:44.533  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 15:11:44.535  7151  7151 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-29 15:11:44.535  7151  7151 I wpa_supplicant: monitor socket send errors count : 1
08-29 15:11:44.535  7151  7151 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1925-4\x00 that cannot receive messages
08-29 15:11:44.536  1034  7159 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-29 15:11:44.536  1034  7159 D WifiMonitor: Dropping event because (p2p0) is stopped
08-29 15:11:44.557  7151  7151 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 15:11:44.558  7151  7151 W wpa_supplicant: USIM:  scard_deinit function
08-29 15:11:44.558  1034  1116 D Tethering: InitialState.processMessage what=4
08-29 15:11:44.559  1034  1116 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 15:11:44.559  1034  7159 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-29 15:11:44.559  1034  7159 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 15:11:44.559  1034  7159 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 15:11:44.559  1034  7159 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-29 15:11:44.559  1034  7159 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 15:11:44.560  1034  7159 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 15:11:44.560  1034  1376 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-29 15:11:44.560  1034  1376 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 15:11:44.561  1034  1376 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=124812
08-29 15:11:44.561  1034  1376 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=124813
08-29 15:11:44.561  1034  1376 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=124813  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
,08-29 15:11:44.561  1034  1376 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=124813  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
,08-29 15:11:44.753  7151  7151 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-29 15:11:44.754  1034  7159 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-29 15:11:44.754  1034  7159 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
08-29 15:11:44.754  1034  7159 D WifiMonitor: Disconnecting from the supplicant, no more events
08-29 15:11:44.754  1034  1376 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
08-29 15:11:44.762  7309  7325 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-29 15:11:44.762  7309  7325 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-29 15:11:44.762  7309  7325 I Adreno-EGL: Build Date: 12/12/14 금
08-29 15:11:44.762  7309  7325 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-29 15:11:44.762  7309  7325 I Adreno-EGL: Remote Branch: 
08-29 15:11:44.762  7309  7325 I Adreno-EGL: Local Patches: 
08-29 15:11:44.762  7309  7325 I Adreno-EGL: Reconstruct Branch: 
,08-29 15:11:44.786  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-29 15:11:44.791  6461  6496 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-29 15:11:44.799  2198  2198 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-29 15:11:44.809  7094  7094 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,08-29 15:11:44.809  7094  7094 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-29 15:11:44.809  7094  7094 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-29 15:11:44.809  7094  7094 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-29 15:11:44.810  7094  7094 I AppUp4:CustModeStarterReceiver: onReceive
,08-29 15:11:44.813  7094  7094 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@c958594
08-29 15:11:44.813  7094  7094 D AppUp4:CustFacade: isCustomizationCompleted : false
08-29 15:11:44.813  7094  7094 D AppUp4:CustFacade: isPhone : true
08-29 15:11:44.814  7094  7094 D AppUp4:CustModeStarterReceiver: begin check event
08-29 15:11:44.815  7094  7094 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-29 15:11:44.818  4308  4308 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-29 15:11:44.818  4308  4308 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 15:11:44.819  4308  4308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 15:11:44.821  4308  4308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-29 15:11:44.827  7128  7128 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-29 15:11:44.830  4308  7404 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-29 15:11:44.830  4308  7404 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-29 15:11:44.831  4308  7403 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-29 15:11:44.837  1034  1362 V AlarmManager: ELAPSED_WAKEUP set : Alarm{27d925d8 type 2 when 125088 com.google.android.gms} when 125088
08-29 15:11:44.846  7128  7407 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 15:11:44.847  6994  7409 W FormManager: Network not available. Please check & try again.
08-29 15:11:44.849  3379  3379 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-29 15:11:44.849  3379  3379 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-29 15:11:44.850  3379  3379 I LgeMiscReceiver: networkInfo.isConnected() = false
08-29 15:11:44.852  7170  7170 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-29 15:11:44.852  7170  7170 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-29 15:11:44.856  1925  1925 D WfdsService: Supplicant Connection state is changed : false
08-29 15:11:44.857  1034  1376 D WifiOffDelayIfNotUsed: stopMonitoring
08-29 15:11:44.857  1925  2271 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-29 15:11:44.857  1034  1376 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 15:11:44.857  1034  1376 E WifiStateMachine: useWiFiOffloading() : false
08-29 15:11:44.857  1034  1376 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 15:11:44.857  1925  2271 D WfdsService: Set the WFDS Monitor: false
08-29 15:11:44.857  1925  2271 D WfdsMonitor: WFDS Monitor is stopped
08-29 15:11:44.859  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 15:11:44.860  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-29 15:11:44.860  2473  2473 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:11:44.861  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-29 15:11:44.861  6671  6671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:11:44.861  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:11:44.861  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:44.861  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 15:11:44.861  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 15:11:44.861  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 15:11:44.861  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:11:44.861  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:11:44.861  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 15:11:44.861  1034  1424 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-29 15:11:44.861  1034  1424 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
,08-29 15:11:44.862  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:44.876  7230  7230 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:11:44
08-29 15:11:44.877  6994  7410 V FormManager: Network unavailable.
,08-29 15:11:44.880  6994  7410 V FormManager: Network unavailable.
,08-29 15:11:44.881  7230  7230 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-29 15:11:44.881  7230  7230 D Weather.Utils: 2 : All the weather widget is gone.
08-29 15:11:44.881  7230  7230 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-29 15:11:44.882  7230  7230 D WeatherAncestor: connectivity changed - connection : true
08-29 15:11:44.882  7230  7230 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1f32e832
08-29 15:11:44.882  7230  7230 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-29 15:11:44.882  7230  7230 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-29 15:11:44.882  7230  7230 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-29 15:11:44.883  7230  7230 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-29 15:11:44.883  7230  7230 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:11:44
08-29 15:11:44.885   310  7416 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-29 15:11:44.885  1034  1114 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-29 15:11:44.886  1801  7268 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,08-29 15:11:44.897  1801  7268 I CheckinService: active receiver: disabled
,08-29 15:11:44.918  6892  6892 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 15:11:44.918  6892  6892 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 15:11:44.918  6892  6892 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 15:11:44.918  6892  6892 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 15:11:44.919  6892  6892 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 15:11:44.919  6892  6892 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 15:11:44.919  6892  6892 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-29 15:11:44.919  6892  6892 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 15:11:44.919  6892  6892 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 15:11:44.919  6892  6892 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 15:11:44.920  6892  6892 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 15:11:44.927  6913  6913 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 15:11:44.929  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-29 15:11:44.935  6994  7418 W FormManager: Network not available. Please check & try again.
08-29 15:11:44.935  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 15:11:44.943  6994  7419 V FormManager: Network unavailable.
,08-29 15:11:44.945  6994  7419 V FormManager: Network unavailable.
08-29 15:11:44.951  6913  6913 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 15:11:44.954  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-29 15:11:44.956  6994  7420 W FormManager: Network not available. Please check & try again.
08-29 15:11:44.958  6994  7421 V FormManager: Network unavailable.
08-29 15:11:44.961  6994  7421 V FormManager: Network unavailable.
08-29 15:11:44.964  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 15:11:44.977  4308  4308 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 15:11:44.977  4308  4308 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 15:11:44.979  4308  4308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 15:11:44.981  4308  4308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-29 15:11:44.988  4308  7422 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-29 15:11:44.992  4308  7423 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 15:11:44.992  4308  7423 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 15:11:45.026  1034  2032 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7424 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-29 15:11:45.131  7424  7424 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-29 15:11:45.131  7424  7424 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-29 15:11:45.139  7424  7424 V [BNRBootReceiver]: Boot Receiver Return
08-29 15:11:45.139  7424  7424 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-29 15:11:45.145  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 15:11:45.156  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 15:11:45.163  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 15:11:45.174  6941  6941 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 15:11:45.174  6941  6941 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 15:11:45.176  6941  6941 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 15:11:45.181  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-29 15:11:45.185  6892  6892 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-29 15:11:45.190  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 15:11:45.206  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 15:11:45.211  6795  7077 D UEI.SmartControl: Internal timer expired: 4
08-29 15:11:45.211  6795  7077 D UEI.SmartControl: unbind internal service
08-29 15:11:45.215  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 15:11:45.224  6941  6941 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 15:11:45.224  6941  6941 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 15:11:45.226  6941  6941 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-29 15:11:45.229  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 15:11:45.245  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 15:11:45.254  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 15:11:45.265  6941  6941 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 15:11:45.265  6941  6941 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 15:11:45.266  6941  6941 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-29 15:11:45.274  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 15:11:45.275  6795  7071 D serial_port: close(fd = 24)
08-29 15:11:45.279  6795  7071 I UEI.SmartControl: Serial port is closed.
,08-29 15:11:45.299  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 15:11:45.311  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 15:11:45.322  6941  6941 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 15:11:45.322  6941  6941 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 15:11:45.323  6941  6941 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-29 15:11:45.330  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 15:11:45.342  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 15:11:45.349  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 15:11:45.357  6941  6941 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 15:11:45.358  6941  6941 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 15:11:45.358  6941  6941 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-29 15:11:45.362  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 15:11:45.371  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 15:11:45.377  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 15:11:45.390  6941  6941 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 15:11:45.391  6941  6941 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 15:11:45.392  6941  6941 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 15:11:45.397  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 15:11:45.407  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 15:11:45.416  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 15:11:45.428  6941  6941 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 15:11:45.429  6941  6941 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 15:11:45.430  6941  6941 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 15:11:45.445  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 15:11:45.472  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 15:11:45.488  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 15:11:45.502  6941  6941 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 15:11:45.503  6941  6941 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 15:11:45.510  6941  6941 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 15:11:45.519  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 15:11:45.530  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 15:11:45.536  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 15:11:45.553  6941  6941 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 15:11:45.553  6941  6941 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 15:11:45.555  6941  6941 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 15:11:45.564  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 15:11:45.572  6913  6913 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-29 15:11:45.587  1034  1440 D WifiService: New client listening to asynchronous messages
08-29 15:11:45.589  6913  6913 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 15:11:45.597  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 15:11:45.609  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 15:11:45.622  6941  6941 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 15:11:45.623  6941  6941 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 15:11:45.625  6941  6941 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-29 15:11:45.628  6941  6941 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-29 15:11:45.629  6941  6941 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-29 15:11:45.640  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 15:11:45.648  6913  6913 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-29 15:11:45.650  6913  6913 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 15:11:45.657  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 15:11:45.670  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 15:11:45.683  6941  6941 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 15:11:45.684  6941  6941 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 15:11:45.685  6941  6941 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-29 15:11:45.687  6941  6941 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-29 15:11:45.688  6941  6941 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-29 15:11:45.692  1034  1853 I ActivityManager: Killing 6872:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-29 15:11:45.753  1034  1049 W libprocessgroup: failed to open /acct/uid_10037/pid_6872/cgroup.procs: No such file or directory
,08-29 15:11:45.763  2198  2198 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-29 15:11:45.775  2198  2198 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-29 15:11:45.776  2198  2198 D c       : Getting all permits...
,08-29 15:11:45.776  2198  2198 D a       : Opening database...
08-29 15:11:45.783  2198  2198 D a       : Opening database auth.proximity.permit_store...
08-29 15:11:45.784  2198  2198 D a       : Closing database...
08-29 15:11:45.801  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 15:11:45.807  6913  6913 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-29 15:11:45.808  6913  6913 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 15:11:45.808  6913  6913 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 15:11:45.814  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 15:11:45.826  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 15:11:45.840  6941  6941 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 15:11:45.841  6941  6941 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 15:11:45.846  6941  6941 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 15:11:45.855  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 15:11:45.856  1034  1362 V AlarmManager: ELAPSED_WAKEUP set : Alarm{b5d831c type 2 when 126100 com.google.android.gms} when 126100
,08-29 15:11:45.867  6913  6913 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-29 15:11:45.867  6913  6913 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 15:11:45.867  6913  6913 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 15:11:45.872  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 15:11:45.878  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 15:11:45.889  6941  6941 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 15:11:45.889  6941  6941 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 15:11:45.893  6941  6941 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 15:11:45.900  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 15:11:45.909  6913  6913 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-29 15:11:45.909  6913  6913 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 15:11:45.909  6913  6913 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 15:11:45.918  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 15:11:45.927  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 15:11:45.942  6941  6941 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 15:11:45.942  6941  6941 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 15:11:45.946  6941  6941 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 15:11:45.961  6913  6913 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 15:11:45.967  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-29 15:11:45.972  6994  7449 W FormManager: Network not available. Please check & try again.
,08-29 15:11:45.981  6994  7450 V FormManager: Network unavailable.
08-29 15:11:45.983  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 15:11:45.990  6994  7450 V FormManager: Network unavailable.
,08-29 15:11:46.005   310  7452 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-29 15:11:46.006  1034  1114 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-29 15:11:46.009  4308  4308 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 15:11:46.009  4308  4308 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 15:11:46.011  4308  4308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 15:11:46.013  4308  4308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 15:11:46.019  4308  7453 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-29 15:11:46.021  4308  7454 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 15:11:46.021  4308  7454 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-29 15:11:46.025  6913  6913 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
,08-29 15:11:46.025  6913  6913 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 15:11:46.025  6913  6913 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 15:11:46.028  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-29 15:11:46.034  6994  7457 V FormManager: Network unavailable.
08-29 15:11:46.036  6994  7456 W FormManager: Network not available. Please check & try again.
08-29 15:11:46.037  6994  7457 V FormManager: Network unavailable.
08-29 15:11:46.038  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 15:11:46.056  2198  2198 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-29 15:11:46.076  6941  6941 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,08-29 15:11:46.077  6941  6941 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:2602
08-29 15:11:46.096  1034  1376 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-697476432] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-29 15:11:46.097  1034  1376 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-697476431] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-29 15:11:46.390  1034  1452 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 15:11:46.403  1034  1116 D Tethering: MasterInitialState.processMessage what=3
08-29 15:11:46.413  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:11:46.417  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:46.420  1034  1111 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-29 15:11:46.423  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-29 15:11:46.425  6461  6496 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-29 15:11:46.439  5777  5777 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-29 15:11:46.457  2198  2198 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-29 15:11:46.477  7094  7094 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-29 15:11:46.477  7094  7094 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-29 15:11:46.477  7094  7094 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-29 15:11:46.477  7094  7094 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-29 15:11:46.482  7094  7094 I AppUp4:CustModeStarterReceiver: onReceive
08-29 15:11:46.486  7094  7094 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@c958594
08-29 15:11:46.486  7094  7094 D AppUp4:CustFacade: isCustomizationCompleted : false
08-29 15:11:46.486  7094  7094 D AppUp4:CustFacade: isPhone : true
08-29 15:11:46.486  7094  7094 D AppUp4:CustModeStarterReceiver: begin check event
08-29 15:11:46.487  7094  7094 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-29 15:11:46.491  4308  4308 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-29 15:11:46.491  4308  4308 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 15:11:46.493  4308  4308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-29 15:11:46.498  4308  4308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 15:11:46.506  7128  7128 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-29 15:11:46.547  4308  7467 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-29 15:11:46.556  4308  7479 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-29 15:11:46.556  4308  7479 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 15:11:46.556  7128  7466 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:11:46.574  1034  1111 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-29 15:11:46.579  6994  7477 W FormManager: Network not available. Please check & try again.
08-29 15:11:46.582  6994  7478 V FormManager: Network unavailable.
08-29 15:11:46.584  6994  7478 V FormManager: Network unavailable.
,08-29 15:11:46.588  3379  3379 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-29 15:11:46.588  3379  3379 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-29 15:11:46.588  3379  3379 I LgeMiscReceiver: networkInfo.isConnected() = true
08-29 15:11:46.588  3379  3379 D PhoneState: setPdpRejectCasuse : false
08-29 15:11:46.592  7170  7170 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-29 15:11:46.592  7170  7170 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-29 15:11:46.607  7230  7230 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:11:46
,08-29 15:11:46.608  7230  7230 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-29 15:11:46.608  7230  7230 D Weather.Utils: 2 : All the weather widget is gone.
,08-29 15:11:46.609  7230  7230 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-29 15:11:46.609  7230  7230 D WeatherAncestor: connectivity changed - connection : true
,08-29 15:11:46.609  7230  7230 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1f32e832
08-29 15:11:46.610  7230  7230 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-29 15:11:46.610  7230  7230 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-29 15:11:46.610  7230  7230 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-29 15:11:46.610  7230  7230 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-29 15:11:46.610  7230  7230 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:11:46
08-29 15:11:47.260  1034  1853 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 15:11:47.261  1034  1853 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-29 15:11:47.300  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 15:11:47.301  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 15:11:47.301  1034  1034 D Ulp_jni : JNI:system_update. Event-4
,08-29 15:11:47.304  1034  1116 D BluetoothManagerService: Message: 1
08-29 15:11:47.304  1034  1116 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-29 15:11:47.334  1034  1116 D BluetoothManagerService: Message: 20
08-29 15:11:47.335  1034  1116 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3cce8795:true
,08-29 15:11:47.339  7029  7029 D BluetoothAdapterState: make
08-29 15:11:47.344  7029  7029 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-29 15:11:47.344  7029  7029 I bluedroid-qcom: init
08-29 15:11:47.345  7029  7499 I BluetoothAdapterState: Entering OffState
08-29 15:11:47.346  7029  7029 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-29 15:11:47.346  7029  7029 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-29 15:11:47.346  7029  7029 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 15:11:47.346  7029  7029 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 15:11:47.346  7029  7029 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-29 15:11:47.348  7029  7029 I bluedroid-qcom: get_profile_interface socket
08-29 15:11:47.348  7029  7029 I bluedroid-qcom: get_profile_interface map_client
,08-29 15:11:47.354  7029  7503 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-29 15:11:47.344  7502  7502 W bdaddr_loader: type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 15:11:47.359  7029  7503 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-29 15:11:47.344  7502  7502 W bdaddr_loader: type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 15:11:47.369  7502  7502 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-29 15:11:47.369  7502  7502 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-29 15:11:47.369  7502  7502 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-29 15:11:47.373  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-29 15:11:47.373  1034  1116 D BluetoothManagerService: Message: 40
08-29 15:11:47.373  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-29 15:11:47.374  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-29 15:11:47.375  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-29 15:11:47.375  7029  7047 I bluedroid-qcom: config_hci_snoop_log
08-29 15:11:47.377  1034  1116 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-29 15:11:47.377  1034  1116 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-29 15:11:47.378  7502  7502 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-29 15:11:47.385  7029  7499 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,08-29 15:11:47.388  7029  7503 D BluetoothAdapterProperties: Name is: G3
08-29 15:11:47.389  7502  7502 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-29 15:11:47.389  7502  7502 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-29 15:11:47.391  7029  7499 D BluetoothAdapterProperties: Setting state to 11
08-29 15:11:47.391  7029  7499 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-29 15:11:47.392  1034  1116 D BluetoothManagerService: Message: 60
08-29 15:11:47.392  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-29 15:11:47.392  1034  1116 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-29 15:11:47.394  7029  7499 I LGBluetoothServiceJni: classInitNative: succeeds
08-29 15:11:47.400  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-29 15:11:47.403  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 15:11:47.405  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:47.406  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:47.411  6892  6892 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-29 15:11:47.422  7029  7029 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 15:11:47.422  7029  7029 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 15:11:47.423  7029  7029 V BluetoothPbapReceiver: ***********state = 11
,08-29 15:11:47.427  7029  7499 D BluetoothBondStateMachine: make
08-29 15:11:47.430  2198  2198 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 15:11:47.439  7029  7512 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 15:11:47.441  7029  7499 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f32e832
08-29 15:11:47.441  7029  7499 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-29 15:11:47.442  7029  7499 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f32e832
08-29 15:11:47.442  7029  7499 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-29 15:11:47.442  7029  7499 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-29 15:11:47.447  7029  7499 E BluetoothAdapterService: File transfer profiles supported!!
08-29 15:11:47.480  1034  1452 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 15:11:47.494  1034  1957 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7519 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-29 15:11:47.500  7029  7499 E BluetoothAdapterService: File transfer profiles supported!!
08-29 15:11:47.502  7029  7029 D HeadsetService: Received start request. Starting profile...
08-29 15:11:47.502  7029  7029 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 15:11:47.503  7029  7029 D LGBluetoothHfpAdapter: Version 1.6
08-29 15:11:47.505  1034  1452 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-29 15:11:47.506  7029  7029 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-29 15:11:47.507  7029  7029 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 15:11:47.508  7029  7029 D HeadsetStateMachine: make
,08-29 15:11:47.513  1034  1116 D Tethering: MasterInitialState.processMessage what=3
08-29 15:11:47.514  1034  1111 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-29 15:11:47.518  1034  1116 D Tethering: MasterInitialState.processMessage what=3
08-29 15:11:47.520  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:11:47.523  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:47.525  7029  7499 E BluetoothAdapterService: File transfer profiles supported!!
08-29 15:11:47.528  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:47.529  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-29 15:11:47.531  6461  6496 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-29 15:11:47.534  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:11:47.537  7029  7499 E BluetoothAdapterService: File transfer profiles supported!!,
08-29 15:11:47.540  5777  5777 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-29 15:11:47.543  7029  7029 D LgDataFeature: LgDataFeature() Constructor: none
08-29 15:11:47.543  7029  7029 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 15:11:47.544  5777  5777 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-29 15:11:47.545  7029  7499 E BluetoothAdapterService: File transfer profiles supported!!
,08-29 15:11:47.550  7029  7029 D HeadsetStateMachine: max_hf_connections = 1
08-29 15:11:47.550  7029  7029 I bluedroid-qcom: get_profile_interface handsfree
08-29 15:11:47.551  7029  7029 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-29 15:11:47.552   316  1382 V AudioPolicyService: registerClient() client 0xb1025c80, uid 1002
08-29 15:11:47.553   316  2154 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-29 15:11:47.553   316  2154 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 15:11:47.553   316  2154 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 15:11:47.553  7029  7029 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-29 15:11:47.554   316   316 V AudioFlinger: registerClient() client 0xb1024ad8, pid 7029
08-29 15:11:47.554   316  1375 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 15:11:47.554   316  1375 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 15:11:47.554  1034  2011 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 15:11:47.554  1034  2011 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 15:11:47.554   316  1377 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 15:11:47.554   316  1377 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 15:11:47.554  1587  1606 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 15:11:47.554  1587  1606 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 15:11:47.554  7029  7538 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 15:11:47.554  1587  1606 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 15:11:47.554  1587  1606 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 15:11:47.555  1034  1874 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 15:11:47.555  1034  1874 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 15:11:47.555  1836  4430 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 15:11:47.555  1836  4430 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 15:11:47.555  1836  4430 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 15:11:47.555  1836  4430 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 15:11:47.555  7029  7499 E BluetoothAdapterService: File transfer profiles supported!!
08-29 15:11:47.555  7029  7538 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-29 15:11:47.555  7029  7538 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 15:11:47.555  7029  7538 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-29 15:11:47.555  7029  7029 V ToneGenerator: Create Track: 0xb4928a80
08-29 15:11:47.555  7029  7029 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-29 15:11:47.555  7029  7029 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-29 15:11:47.555  3379  3394 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 15:11:47.555  3379  3394 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 15:11:47.555  3379  3394 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 15:11:47.555   316  2153 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-29 15:11:47.555  3379  3394 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 15:11:47.555   316  2153 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-29 15:11:47.555   316  2153 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 15:11:47.555   316  2153 V AudioPolicyManagerEx: getOutput() returns ,output 2
08-29 15:11:47.556   316  1382 I AudioFlinger: isAudioPlaybackHookOn() false
08-29 15:11:47.556   316  2154 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-29 15:11:47.556   316  2154 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-29 15:11:47.556   316  2154 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 15:11:47.556   316  2154 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 15:11:47.556  7029  7029 V AudioSystem: getLatency() output 2, latency 50
08-29 15:11:47.556  7029  7029 V AudioSystem: getFrameCount() output 2, frameCount 960
08-29 15:11:47.556  7029  7029 V AudioTrack: createTrack_l() output 2 afLatency 50
08-29 15:11:47.557   316   316 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-29 15:11:47.557   316   316 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-29 15:11:47.557   316   316 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-29 15:11:47.557   316   316 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-29 15:11:47.557   316   316 V AudioFlinger: createTrack() lSessionId: 22
08-29 15:11:47.557  7029  7029 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-29 15:11:47.558   316   316 V AudioFlinger: acquiring 22 from 7029, for 7029
08-29 15:11:47.558   316   316 V AudioFlinger:  added new entry for 22
08-29 15:11:47.558  7029  7029 V ToneGenerator: ToneGenerator INIT OK, time: 127824
08-29 15:11:47.558  7029  7029 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f32e832
08-29 15:11:47.559  7029  7530 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-29 15:11:47.559  7029  7530 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 15:11:47.559  7029  7530 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 15:11:47.559  7029  7530 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
,08-29 15:11:47.561   316  1381 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7029
08-29 15:11:47.561   316  1381 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-29 15:11:47.561   316  1381 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-29 15:11:47.561   316  1381 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-29 15:11:47.561   316  1381 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-29 15:11:47.561   316  1381 V voice   : voice_set_parameters: exit with code(0)
08-29 15:11:47.561   316  1381 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-29 15:11:47.561   316  1381 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-29 15:11:47.562   316  1381 V msm8974_platform: platform_set_parameters: exit with code(0)
08-29 15:11:47.562   316  1381 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-29 15:11:47.562   316  1381 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-29 15:11:47.562   316  1381 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-29 15:11:47.563  7029  7530 V ToneGenerator: ToneGenerator destructor
08-29 15:11:47.563  7029  7530 V ToneGenerator: stopTone
08-29 15:11:47.563  7029  7530 V ToneGenerator: Delete Track: 0xb4928a80
08-29 15:11:47.564  7029  7530 V AudioTrack: ~AudioTrack, releasing session id from 7029 on behalf of 7029
08-29 15:11:47.564   316  2153 V AudioFlinger: releasing 22 from 7029 for 7029
08-29 15:11:47.564   316  2153 V AudioFlinger:  decremented refcount to 0
08-29 15:11:47.564   316  2153 V AudioFlinger: purging stale effects
08-29 15:11:47.565   316  2153 V AudioPolicyService: AudioCommandThread() adding release output 2
08-29 15:11:47.565   316  2153 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-29 15:11:47.565   316  1270 V AudioPolicyService: AudioCommandThread() waking up
08-29 15:11:47.565   316  1270 V AudioPolicyService: AudioCommandThread() processing release output 2
08-29 15:11:47.565   316  1270 V AudioPolicyManager: releaseOutput() 2
08-29 15:11:47.565   316  1270 V AudioPolicyService: AudioCommandThread() going to sleep
08-29 15:11:47.565   316  2153 V AudioFlinger: PlaybackThread::Track destructor
08-29 15:11:47.565   316  2153 V AudioFlinger: removeClient_l() pid 7029, calling pid 316
08-29 15:11:47.565  1034  1962 W Process : Unable to open /proc/7540/status
08-29 15:11:47.566  7029  7029 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f32e832
08-29 15:11:47.568  7029  7029 D A2dpService: Received start request. Starting profile...
08-29 15:11:47.568  7029  7029 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 15:11:47.569  1034  1111 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-29 15:11:47.569  7029  7029 V Avrcp   : make
08-29 15:11:47.569  7029  7029 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-29 15:11:47.569  7029  7029 I bluedroid-qcom: get_profile_interface avrcp
08-29 15:11:47.571  2198  2198 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-29 15:11:47.574  7029  7499 E BluetoothAdapterService: File transfer profiles supported!!
08-29 15:11:47.573  1034  1111 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 15:11:47.578  7029  7029 V AudioManager: registerRemoteController: size of Media player list: 0
08-29 15:11:47.578  1034  1111 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 15:11:47.580  7029  7029 E AudioManager: No RCC entry present to update
08-29 15:11:47.580  7029  7029 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-29 15:11:47.584  7029  7029 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-29 15:11:47.585  7029  7029 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-29 15:11:47.585  7029  7029 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
,08-29 15:11:47.586  7094  7094 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-29 15:11:47.587  7094  7094 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-29 15:11:47.587  7094  7094 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-29 15:11:47.587  7094  7094 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-29 15:11:47.589  7094  7094 I AppUp4:CustModeStarterReceiver: onReceive
08-29 15:11:47.589  7029  7029 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-29 15:11:47.593  7029  7499 V LGMDMManager: Create singleton instance
08-29 15:11:47.595  7029  7499 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-29 15:11:47.596  7094  7094 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@c958594
08-29 15:11:47.596  7094  7094 D AppUp4:CustFacade: isCustomizationCompleted : false
08-29 15:11:47.596  7094  7094 D AppUp4:CustFacade: isPhone : true
,08-29 15:11:47.630  7094  7094 D AppUp4:CustModeStarterReceiver: begin check event
,08-29 15:11:47.630  7094  7094 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-29 15:11:47.632  4308  4308 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-29 15:11:47.632  4308  4308 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 15:11:47.633  4308  4308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 15:11:47.637  4308  4308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 15:11:47.650  4308  7544 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-29 15:11:47.655  7128  7128 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-29 15:11:47.656  4308  7545 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-29 15:11:47.656  4308  7545 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 15:11:47.680  3379  3379 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-29 15:11:47.680  3379  3379 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-29 15:11:47.680  3379  3379 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-29 15:11:47.683  7128  7546 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:11:47.684  1034  1049 V SIM_STK : Menu title from STK is T-Mobile
08-29 15:11:47.684  1034  1049 V SIM_STK : Menu title from STK is T-Mobile
08-29 15:11:47.685  7519  7519 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-29 15:11:47.686  7519  7519 W LG Account v2.2: No ProfileInfo entries
08-29 15:11:47.686  7519  7519 I LG Account v2.2: isEnabled: false
08-29 15:11:47.686  6994  7548 W FormManager: Network not available. Please check & try again.
08-29 15:11:47.686  7519  7519 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-29 15:11:47.686  7519  7519 I Feature : [Lifetracker]Country: EU
08-29 15:11:47.686  7519  7519 I Feature : [Lifetracker]Operator: OPEN
08-29 15:11:47.686  7519  7519 I Feature : [Lifetracker]Ranking support: false
08-29 15:11:47.686  7519  7519 I Feature : [Lifetracker]Comfort support: false
08-29 15:11:47.686  7519  7519 I Feature : [Lifetracker]Accessory: true
08-29 15:11:47.686  7519  7519 I Feature : [Lifetracker]Health device: true
08-29 15:11:47.687  7519  7519 I Feature : [Lifetracker]Extra Pedometer: false
08-29 15:11:47.687  7519  7519 I Feature : [Lifetracker]Blood glucose device: false
08-29 15:11:47.687  7519  7519 I Feature : [Lifetracker]Device Number: 3
08-29 15:11:47.689  7170  7170 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-29 15:11:47.689  7170  7170 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-29 15:11:47.697  6994  7549 V FormManager: Network unavailable.
,08-29 15:11:47.703  6994  7549 V FormManager: Network unavailable.
08-29 15:11:47.704  6892  6892 D BluetoothPermissionRequest: onReceive
08-29 15:11:47.706  7230  7230 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:11:47
08-29 15:11:47.710  7230  7230 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-29 15:11:47.710  7230  7230 D Weather.Utils: 2 : All the weather widget is gone.
,08-29 15:11:47.711  7230  7230 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-29 15:11:47.711  7230  7230 D WeatherAncestor: connectivity changed - connection : true
08-29 15:11:47.711  7230  7230 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1f32e832
08-29 15:11:47.712  7230  7230 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-29 15:11:47.712  7230  7230 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-29 15:11:47.713  7230  7230 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-29 15:11:47.713  7230  7230 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-29 15:11:47.713  7230  7230 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:11:47
08-29 15:11:47.713  6892  6892 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 15:11:47.732  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-29 15:11:47.733  6461  6496 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-29 15:11:47.747  2198  2198 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-29 15:11:47.755  1034  1922 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-29 15:11:47.760  7094  7094 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-29 15:11:47.760  7094  7094 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-29 15:11:47.760  7094  7094 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-29 15:11:47.760  7094  7094 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-29 15:11:47.761  7029  7029 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-29 15:11:47.761  7094  7094 I AppUp4:CustModeStarterReceiver: onReceive
08-29 15:11:47.764  7094  7094 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@c958594
,08-29 15:11:47.764  7094  7094 D AppUp4:CustFacade: isCustomizationCompleted : false
08-29 15:11:47.764  7094  7094 D AppUp4:CustFacade: isPhone : true
08-29 15:11:47.764  7094  7094 D AppUp4:CustModeStarterReceiver: begin check event
08-29 15:11:47.764  7094  7094 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-29 15:11:47.767  4308  4308 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-29 15:11:47.768  4308  4308 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 15:11:47.768  7029  7029 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-29 15:11:47.769  7029  7029 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-29 15:11:47.769  7029  7029 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-29 15:11:47.769  7029  7029 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-29 15:11:47.769  4308  4308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 15:11:47.769  7029  7029 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 15:11:47.769  7029  7029 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-29 15:11:47.769  7029  7029 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-29 15:11:47.769  7029  7029 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-29 15:11:47.769  7029  7029 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 15:11:47.769  7029  7029 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-29 15:11:47.769  7029  7029 I BluetoothA2dpServiceJni: classInitNative
08-29 15:11:47.770  7029  7029 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 15:11:47.770  7029  7029 D A2dpStateMachine: make
08-29 15:11:47.770  4308  4308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 15:11:47.771  7029  7029 I bluedroid-qcom: get_profile_interface a2dp
08-29 15:11:47.771  7029  7554 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-29 15:11:47.772  7029  7029 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-29 15:11:47.773  7029  7029 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-29 15:11:47.773  7029  7029 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f32e832
08-29 15:11:47.774  7029  7029 I BluetoothHidServiceJni: classInitNative: succeeds
08-29 15:11:47.775  7029  7553 D A2dpStateMachine: Enter Disconnected: -2
08-29 15:11:47.775  7029  7029 D HidService: Received start request. Starting profile...
08-29 15:11:47.776  7029  7029 I bluedroid-qcom: get_profile_interface hidhost
08-29 15:11:47.776  7029  7029 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f32e832
08-29 15:11:47.776  7029  7029 I BluetoothHealthServiceJni: classInitNative: succeeds
08-29 15:11:47.777  7029  7029 D HealthService: Received start request. Starting profile...
08-29 15:11:47.778  4308  7556 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-29 15:11:47.778  7128  7128 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-29 15:11:47.778  7029  7029 I bluedroid-qcom: get_profile_interface health
08-29 15:11:47.778  7029  7029 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-29 15:11:47.778  7029  7029 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f32e832
08-29 15:11:47.779  7029  7029 D HeadsetStateMachine: Proxy object connected
08-29 15:11:47.779  7029  7029 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-29 15:11:47.779  7029  7029 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-29 15:11:47.780  7029  7029 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-29 15:11:47.781  7029  7029 D PanService: Received start request. Starting profile...
08-29 15:11:47.781  7029  7029 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 15:11:47.781  7029  7029 I bluedroid-qcom: get_profile_interface pan
08-29 15:11:47.782  4308  7558 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-29 15:11:47.782  4308  7558 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 15:11:47.786  7029  7029 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
,08-29 15:11:47.786  7029  7029 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f32e832
08-29 15:11:47.786  7029  7029 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-29 15:11:47.790  7029  7029 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 15:11:47.791  7029  7029 D BtGatt.GattService: Received start request. Starting profile...
08-29 15:11:47.791  7029  7029 D BtGatt.GattService: start()
08-29 15:11:47.791  7029  7029 I bluedroid-qcom: get_profile_interface gatt
08-29 15:11:47.791  7029  7029 D BtGatt.AdvertiseManager: advertise manager created
08-29 15:11:47.792  7128  7561 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:11:47.798  7029  7029 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f32e832
,08-29 15:11:47.799  7029  7530 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-29 15:11:47.800  7029  7530 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 15:11:47.801  7029  7530 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-29 15:11:47.802  3379  3379 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-29 15:11:47.802  3379  3379 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-29 15:11:47.802  3379  3379 I LgeMiscReceiver: networkInfo.isConnected() = false
08-29 15:11:47.802  7029  7029 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 15:11:47.804  7029  7029 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f32e832
08-29 15:11:47.804  7029  7029 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-29 15:11:47.805  7029  7029 V BluetoothMapService: BluetoothMapBinder()
08-29 15:11:47.805  7029  7029 D BluetoothMapService: Received start request. Starting profile...
08-29 15:11:47.805  7029  7029 D BluetoothMapService: start()
08-29 15:11:47.806  7170  7170 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-29 15:11:47.806  7170  7170 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-29 15:11:47.811  7029  7029 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-29 15:11:47.811  7029  7029 D BluetoothMapEmailAppObserver: createReceiver()
,08-29 15:11:47.814  7029  7029 D BluetoothMapEmailAppObserver: initObservers()
08-29 15:11:47.814  7029  7029 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-29 15:11:47.817  6994  7565 W FormManager: Network not available. Please check & try again.
08-29 15:11:47.820  7230  7230 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:11:47
08-29 15:11:47.822  7230  7230 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-29 15:11:47.823  7230  7230 D Weather.Utils: 2 : All the weather widget is gone.
,08-29 15:11:47.823  6994  7567 V FormManager: Network unavailable.
08-29 15:11:47.823  7029  7029 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f32e832
,08-29 15:11:47.825  7230  7230 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-29 15:11:47.825  7230  7230 D WeatherAncestor: connectivity changed - connection : true
08-29 15:11:47.825  7230  7230 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1f32e832
08-29 15:11:47.826  7230  7230 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-29 15:11:47.826  7230  7230 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-29 15:11:47.826  7230  7230 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-29 15:11:47.826  7230  7230 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-29 15:11:47.827  7230  7230 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:11:47
08-29 15:11:47.828  7029  7029 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 15:11:47.831  7029  7029 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 15:11:47.832  6994  7567 V FormManager: Network unavailable.
08-29 15:11:47.835  7029  7029 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-29 15:11:47.839  7029  7029 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 15:11:47.839  7029  7029 V PanService: [BTUI] SIM Extra State :ABSENT
08-29 15:11:47.844  7029  7029 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-29 15:11:47.845  7029  7029 V BluetoothMapService: Handler(): got msg=1
08-29 15:11:47.846  7029  7499 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-29 15:11:47.846  7029  7499 I bluedroid-qcom: enable
,08-29 15:11:47.846  7029  7568 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-29 15:11:47.846  7029  7568 I bt-btu  : btu_task pending for preload complete event
08-29 15:11:47.846  7029  7499 I bt_hci_bdroid: init
08-29 15:11:47.847  7029  7499 I bt_vendor: bt-vendor : init
08-29 15:11:47.847  7029  7499 I bt_vendor: bt-vendor : get_bt_soc_type
08-29 15:11:47.847  7029  7499 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-29 15:11:47.847  7029  7499 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-29 15:11:47.847  7029  7499 D bt_userial_mct: userial_init
08-29 15:11:47.848  7029  7499 D bt_hci_bdroid: set_power 1
08-29 15:11:47.848  7029  7499 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-29 15:11:47.848  7029  7499 I bt_vendor: Starting hciattach daemon
08-29 15:11:47.848  7029  7499 I bt_vendor: try to set true
,08-29 15:11:47.834  7571  7571 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-29 15:11:47.851  7029  7029 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 15:11:47.834  7571  7571 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 15:11:47.854  7029  7029 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 15:11:47.854  7029  7029 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 15:11:47.854  7029  7029 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 15:11:47.854  7029  7029 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 15:11:47.854  7029  7029 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-29 15:11:47.872  7572  7572 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-29 15:11:47.915  1587  1587 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-29 15:11:47.915  1587  1587 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-29 15:11:47.924  1587  1587 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 316
08-29 15:11:47.924  1587  1587 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-29 15:11:47.925  1034  1440 D WifiController: battery changed pluggedType: 2
08-29 15:11:47.927  1587  1587 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-29 15:11:47.927  1925  2057 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-29 15:11:47.927  1925  2057 D LEDHandler: Battery Level Remaining: 100%
08-29 15:11:47.927  1925  2057 D LEDHandler: Battery Temp: 316, mChargingStatus=5, mChargingStop=false
,08-29 15:11:47.933  7029  7530 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-29 15:11:47.934  7424  7424 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-29 15:11:47.959  7579  7579 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-29 15:11:47.970  7580  7580 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-29 15:11:47.994  7582  7582 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-29 15:11:48.008  7583  7583 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-29 15:11:48.023  7584  7584 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-29 15:11:48.050  7585  7585 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-29 15:11:48.075  7587  7587 I libmdmdetect: ESOC framework not supported
,08-29 15:11:48.077  7587  7587 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-29 15:11:48.091  7587  7587 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-29 15:11:48.091  7587  7587 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-29 15:11:48.091  7587  7587 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
,08-29 15:11:48.091  7587  7587 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
,08-29 15:11:48.091  7587  7587 D bthci_qcomm_common: [BTUI]     LE: Class 2
,08-29 15:11:48.091  7587  7587 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-29 15:11:48.091  7587  7587 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-29 15:11:48.145  7587  7588 E QC-QMI  : qmi_client [7587] 14: failed to locate client data
08-29 15:11:48.147   469   469 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,08-29 15:11:48.147   469   469 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-29 15:11:48.252  7598  7598 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-29 15:11:48.272  7599  7599 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-29 15:11:48.302  7029  7499 I bt_vendor: bluetooth satus is on
08-29 15:11:48.302  7029  7499 D bt_hci_bdroid: preload
,08-29 15:11:48.305  7029  7570 D bt_userial_mct: userial_open(port:0)
08-29 15:11:48.305  7029  7570 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-29 15:11:48.308  7029  7570 I bt_vendor: Done intiailizing UART
08-29 15:11:48.309  7029  7570 I bt_vendor: Done intiailizing UART
08-29 15:11:48.309  7029  7570 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-29 15:11:48.310  7029  7570 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-29 15:11:48.310  7029  7568 I bt-btu  : btu_task received preload complete event
08-29 15:11:48.310  7029  7568 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-29 15:11:48.310  7029  7568 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-29 15:11:48.312  7029  7568 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-29 15:11:48.319  7029  7601 D bt_userial_mct: Entering userial_read_thread()
,08-29 15:11:48.323  7029  7568 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 15:11:48.323  7029  7568 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-29 15:11:48.323  7029  7568 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-29 15:11:48.323  7029  7568 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 15:11:48.323  7029  7568 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 15:11:48.324  7029  7568 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 15:11:48.324  7029  7568 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-29 15:11:48.324  7029  7568 I         : BTE_InitTraceLevels -- TRC_BTM,
,08-29 15:11:48.324  7029  7568 I         : BTE_InitTraceLevels -- TRC_HID_HOST
,08-29 15:11:48.324  7029  7568 I         : BTE_InitTraceLevels -- TRC_GAP,
08-29 15:11:48.324  7029  7568 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 15:11:48.324  7029  7568 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 15:11:48.324  7029  7568 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 15:11:48.324  7029  7568 I         : BTE_InitTraceLevels -- TRC_SMP,
08-29 15:11:48.324  7029  7568 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 15:11:48.324  7029  7568 I         : BTE_InitTraceLevels -- TRC_BTIF
08-29 15:11:48.373   310  7260 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-29 15:11:48.375   310  7260 D libc-netbsd: res_queryN name = clients3.google.com., class = 1, type = 28
,08-29 15:11:48.377   310  7260 D libc-netbsd: res_queryN name = clients3.google.com., class = 1, type = 1
,08-29 15:11:48.398  1034  7228 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-29 15:11:48.399  1034  7228 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-4s16ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:48.399  1034  7228 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-4s16ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:48.399  1034  7228 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-29 15:11:48.401  1034  1114 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-29 15:11:48.421  7029  7568 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-29 15:11:48.421  7029  7568 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa017c061 
08-29 15:11:48.421  7029  7568 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa017c061 
,08-29 15:11:48.438  7029  7503 E bt-btif : Calling BTA_HhEnable
08-29 15:11:48.438  7029  7503 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-29 15:11:48.438  7029  7503 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-29 15:11:48.441  7029  7568 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-29 15:11:48.441  7029  7568 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-29 15:11:48.441  7029  7568 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-29 15:11:48.442  7029  7568 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-29 15:11:48.442  7029  7568 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-29 15:11:48.443  7029  7503 D BluetoothAdapterProperties: Name is: G3
08-29 15:11:48.444  7029  7503 D BluetoothAdapterProperties: Scan Mode:20
08-29 15:11:48.444  7029  7503 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 15:11:48.444  7029  7503 D bt_hci_bdroid: postload
08-29 15:11:48.445  7029  7570 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 15:11:48.445  7029  7570 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 15:11:48.446  7029  7568 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-29 15:11:48.446  7029  7570 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 15:11:48.446  7029  7570 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 15:11:48.447  7029  7503 D bte_conf: Device ID record 1 : primary
08-29 15:11:48.447  7029  7503 D bte_conf:   vendorId            = 00c4
08-29 15:11:48.447  7029  7503 D bte_conf:   vendorIdSource      = 0001
08-29 15:11:48.447  7029  7503 D bte_conf:   product             = 13a1
08-29 15:11:48.447  7029  7503 D bte_conf:   version             = 1000
08-29 15:11:48.447  7029  7503 D bte_conf:   clientExecutableURL = 
08-29 15:11:48.447  7029  7503 D bte_conf:   serviceDescription  = 
08-29 15:11:48.447  7029  7503 D bte_conf:   documentationURL    = 
08-29 15:11:48.447  7029  7503 D bte_conf: bte_load_did_conf no section named DID2.
08-29 15:11:48.448  7029  7570 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 15:11:48.451  7029  7601 E bt_mct  : hci lib postload completed
,08-29 15:11:48.444  7603  7603 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 15:11:48.458  7029  7499 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-29 15:11:48.458  7029  7499 D BluetoothAdapterProperties: ScanMode =  20
08-29 15:11:48.458  7029  7499 D BluetoothAdapterProperties: State =  11
08-29 15:11:48.458  7029  7499 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-29 15:11:48.459  7029  7499 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-29 15:11:48.459  7029  7499 D BluetoothAdapterProperties: Setting state to 12
08-29 15:11:48.459  7029  7499 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 15:11:48.459  7029  7503 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-29 15:11:48.460  7029  7503 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-29 15:11:48.444  7603  7603 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 15:11:48.464  1034  1116 D BluetoothManagerService: Message: 60
08-29 15:11:48.464  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-29 15:11:48.464  1034  1116 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
,08-29 15:11:48.468  7029  7568 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 15:11:48.468  7029  7568 W bt-smp  : Plain text(LSB ~ MSB) = ab 30 65 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 15:11:48.468  7029  7568 W bt-smp  : Encrypted text(LSB ~ MSB) = 28 4a 35 8f 1f fb 4e 93 24 0f 35 da 95 9e 55 a6 
08-29 15:11:48.469  7029  7568 W bt-btm  : Stopping oneshot timer
08-29 15:11:48.473  7029  7499 I BluetoothAdapterState: Entering On State
08-29 15:11:48.474  1836  4430 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 15:11:48.482  7029  7499 D LGBluetoothServiceAdapter: [BTUI] OnState
08-29 15:11:48.482  7029  7499 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-29 15:11:48.482  7029  7499 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-29 15:11:48.489  7029  7499 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-29 15:11:48.503  7029  7568 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 15:11:48.503  7029  7568 W bt-smp  : Plain text(LSB ~ MSB) = 1c 33 48 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 15:11:48.504  7029  7568 W bt-smp  : Encrypted text(LSB ~ MSB) = ff 57 9a e0 ad 82 f9 06 4c 1a 5c 65 24 1c a2 aa 
,08-29 15:11:48.506  7029  7568 W bt-btm  : Stopping oneshot timer
08-29 15:11:48.507  1836  1836 D BluetoothHeadset: Proxy object connected
08-29 15:11:48.508  1034  1116 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 15:11:48.516  7029  7503 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 15:11:48.516  7029  7503 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-29 15:11:48.520  1034  1034 D BluetoothA2dp: Proxy object connected
08-29 15:11:48.523  7029  7499 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-29 15:11:48.524  7029  7568 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 15:11:48.524  7029  7568 W bt-smp  : Plain text(LSB ~ MSB) = 0b 29 72 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 15:11:48.524  7029  7568 W bt-smp  : Encrypted text(LSB ~ MSB) = 67 85 bb 81 e6 b3 d6 00 69 32 a0 05 13 5a 30 1a 
08-29 15:11:48.525  7029  7568 W bt-btm  : Stopping oneshot timer
08-29 15:11:48.525  1034  1116 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 15:11:48.528  1034  1034 D BluetoothHeadset: Proxy object connected
,08-29 15:11:48.554  7029  7568 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 15:11:48.554  7029  7568 W bt-smp  : Plain text(LSB ~ MSB) = 33 07 6c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 15:11:48.554  7029  7568 W bt-smp  : Encrypted text(LSB ~ MSB) = 87 24 68 04 eb 34 b6 4b 22 23 2e ab 4b 36 f3 a1 
08-29 15:11:48.555  7029  7568 W bt-btm  : Stopping oneshot timer
,08-29 15:11:48.570  6892  6909 D BluetoothMap: onBluetoothStateChange: up=true
,08-29 15:11:48.579  6892  6909 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 15:11:48.580  6892  6892 D BluetoothMap: Proxy object connected
08-29 15:11:48.580  6892  6892 D MapProfile: Bluetooth service connected
08-29 15:11:48.580  6892  6892 D BluetoothMap: getConnectedDevices()
08-29 15:11:48.584  6892  6908 D BluetoothPan: onBluetoothStateChange on: true
08-29 15:11:48.584  6892  6908 D BluetoothPan: onBluetoothStateChange call bindService
,08-29 15:11:48.589  6892  6908 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 15:11:48.590  7622  7622 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-29 15:11:48.590  7029  7568 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 15:11:48.590  7029  7568 W bt-smp  : Plain text(LSB ~ MSB) = 9b 89 4c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 15:11:48.590  7029  7568 W bt-smp  : Encrypted text(LSB ~ MSB) = 19 f0 13 75 2a 2e ca f9 41 db 55 2f d2 22 b1 62 
08-29 15:11:48.592  7029  7568 W bt-btm  : Stopping oneshot timer
08-29 15:11:48.593  1836  1851 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 15:11:48.594  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-29 15:11:48.594  7029  7047 V BluetoothMapService: getConnectedDevices()
08-29 15:11:48.594  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-29 15:11:48.597  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:11:48.597  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:48.597  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 15:11:48.597  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 15:11:48.597  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:11:48.597  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:11:48.597  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:11:48.597  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 15:11:48.600  6671  6671 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 15:11:48.601  1836  1836 D BluetoothHeadset: Proxy object connected
,08-29 15:11:48.602  1836  4429 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 15:11:48.604  6892  6892 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 15:11:48.604  6892  6892 D PanProfile: Bluetooth service connected
08-29 15:11:48.606  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:11:48.606  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:48.606  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 15:11:48.606  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 15:11:48.606  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:11:48.606  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:11:48.606  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:11:48.606  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 15:11:48.606  1836  1836 D BluetoothHeadset: Proxy object connected
08-29 15:11:48.608  1034  1116 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-29 15:11:48.608  1034  1116 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
,08-29 15:11:48.608  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-29 15:11:48.608  6671  6671 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 15:11:48.609  1034  1116 D BluetoothManagerService: Message: 40
08-29 15:11:48.609  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-29 15:11:48.609  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 15:11:48.609  1925  2110 D LGBluetoothAPIService: Message: 1
08-29 15:11:48.609  1925  2110 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-29 15:11:48.610  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 15:11:48.613  6892  6892 D BluetoothInputDevice: Proxy object connected
08-29 15:11:48.613  6892  6892 D HidProfile: Bluetooth service connected
,08-29 15:11:48.615  6671  6671 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-29 15:11:48.619  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:48.623  1925  2110 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-29 15:11:48.625  7029  7029 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 15:11:48.626  7029  7029 D BluetoothMapService: STATE_ON
08-29 15:11:48.627  7029  7029 D LGBluetoothAPIServer: [BTUI] onCreate()
08-29 15:11:48.628  7029  7029 D LGBluetoothAPIServer: [BTUI] onBind()
,08-29 15:11:48.629  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:48.629  7029  7029 V BluetoothMapService: Handler(): got msg=1
08-29 15:11:48.631  1925  1925 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-29 15:11:48.631  1925  2110 D LGBluetoothAPIService: Message: 100
08-29 15:11:48.631  1925  2110 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-29 15:11:48.631  7029  7029 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-29 15:11:48.634  6892  6892 D LocalBluetoothProfileManager: Adding local A2DP profile
08-29 15:11:48.636  1034  1116 D BluetoothManagerService: Message: 30
08-29 15:11:48.646  7029  7628 D BluetoothMapMasInstance: MAS initSocket()
08-29 15:11:48.646  7029  7628 D BluetoothMapMasInstance:   masId = 00
08-29 15:11:48.646  7029  7628 D BluetoothMapMasInstance:   msgTypes = 0e
08-29 15:11:48.646  7029  7628 D BluetoothMapMasInstance:   masName = SMS/MMS
08-29 15:11:48.646  7029  7628 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-29 15:11:48.648  7029  7029 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f32e832
08-29 15:11:48.648  1034  1853 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 15:11:48.648  7029  7029 V BluetoothPbapService: Pbap Service onCreate
08-29 15:11:48.649  7029  7029 V BluetoothPbapService: Starting PBAP service
08-29 15:11:48.650  7029  7628 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 15:11:48.650  7029  7029 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-29 15:11:48.650  7029  7029 V BluetoothPbapService: Pbap Service onBind
08-29 15:11:48.653  7029  7628 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-29 15:11:48.653  7029  7029 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 15:11:48.653  7029  7628 V BluetoothMapMasInstance: Succeed to create listening socket 
08-29 15:11:48.653  7029  7628 D BluetoothMapMasInstance: Accepting socket connection...
08-29 15:11:48.653  7029  7029 V BluetoothPbapService: state: 12
08-29 15:11:48.653  7029  7029 V BluetoothPbapService: Handler(): got msg=1
08-29 15:11:48.654  6892  6892 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-29 15:11:48.654  7029  7503 D BluetoothAdapterProperties: Scan Mode:21
08-29 15:11:48.654  7029  7503 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-29 15:11:48.657  1034  1116 D BluetoothManagerService: Message: 30
08-29 15:11:48.658  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:48.660  7029  7029 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-29 15:11:48.661  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:48.662  7029  7629 V BluetoothPbapService: Pbap Service initSocket,
08-29 15:11:48.662  1034  1758 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-29 15:11:48.664  7029  7629 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 15:11:48.667  7029  7629 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-29 15:11:48.668  7029  7629 V BluetoothPbapService: Succeed to create listening socket 
08-29 15:11:48.668  7029  7629 V BluetoothPbapService: Accepting socket connection...
08-29 15:11:48.668  6892  6892 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-29 15:11:48.669  6892  6892 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-29 15:11:48.673  7029  7029 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 15:11:48.673  7029  7029 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 15:11:48.673  7029  7029 V BluetoothPbapReceiver: ***********state = 12
08-29 15:11:48.674  6892  6892 D BluetoothA2dp: Proxy object connected
08-29 15:11:48.674  6892  6892 D A2dpProfile: Bluetooth service connected
,08-29 15:11:48.677  2198  2198 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 15:11:48.677  2198  2198 D c       : Getting all permits...
08-29 15:11:48.677  2198  2198 D a       : Opening database...
08-29 15:11:48.680  2198  2198 D a       : Opening database auth.proximity.permit_store...
08-29 15:11:48.681  2198  2198 D a       : Closing database...
08-29 15:11:48.682  6892  6892 D BluetoothPbap: Proxy object connected
08-29 15:11:48.682  6892  6892 D PbapServerProfile: Bluetooth service connected
08-29 15:11:48.682  6892  6892 D BluetoothHeadset: Proxy object connected
08-29 15:11:48.683  6892  6892 D HeadsetProfile: Bluetooth service connected
08-29 15:11:48.690  6892  6892 D DockEventReceiver: finishStartingService: stopping service
,08-29 15:11:48.694  6892  6892 D BluetoothPermissionRequest: onReceive
08-29 15:11:48.696  6892  6892 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-29 15:11:48.697  6892  6892 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 15:11:48.700  7029  7029 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-29 15:11:48.701  7029  7029 I LGBluetoothOppAdapter: [BTUI] startOppService()
,08-29 15:11:48.707  7029  7029 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-29 15:11:48.733  7029  7029 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-29 15:11:48.733  7029  7029 V BtOppService: onCreate
08-29 15:11:48.738  7029  7029 V BluetoothOppNotification: send message
08-29 15:11:48.743  7029  7029 V BtOppService: Starting RfcommListener
08-29 15:11:48.757  7029  7029 D BluetoothOppPreference: Dumping Names:  
,08-29 15:11:48.757  7029  7029 D BluetoothOppPreference: {}
,08-29 15:11:48.758  7029  7029 D BluetoothOppPreference: Dumping Channels:  
08-29 15:11:48.758  7029  7029 D BluetoothOppPreference: {}
08-29 15:11:48.759  7029  7029 V BtOppService: onStartCommand
08-29 15:11:48.761  7029  7638 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-29 15:11:48.767  7029  7029 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 15:11:48.767  7029  7635 V BtOppService: Deleted complete outbound shares, number =  0
08-29 15:11:48.767  7029  7029 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-29 15:11:48.769  7029  7638 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-29 15:11:48.770  7029  7635 V BtOppService: Deleted complete inbound failed shares, number = 0
08-29 15:11:48.771  7029  7635 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
,08-29 15:11:48.775  7029  7638 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2e1debaf on behalf of 
08-29 15:11:48.776  7029  7635 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@38e6dbbc on behalf of 
08-29 15:11:48.778  7029  7029 V BluetoothOppNotification: new notify threadi!
08-29 15:11:48.779  7029  7029 V BluetoothOppNotification: send delay message
08-29 15:11:48.780  7029  7640 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-29 15:11:48.780  7029  7029 V BtOppService: start RfcommListener
08-29 15:11:48.781  7029  7640 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@a70745 on behalf of 
08-29 15:11:48.781  7029  7638 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-29 15:11:48.782  7029  7638 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-29 15:11:48.782  7029  7640 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-29 15:11:48.784  7029  7029 V BtOppService: RfcommListener started
08-29 15:11:48.784  7029  7029 V BtOppService: ContentObserver received notification
08-29 15:11:48.784  7029  7638 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@fb34e9a on behalf of 
08-29 15:11:48.784  7029  7029 V BtOppService: ContentObserver received notification
08-29 15:11:48.786  7029  7638 V BluetoothOppNotification: update too frequent, put in queue
,08-29 15:11:48.790  7276  7329 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-29 15:11:48.793  7029  7638 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-29 15:11:48.794  7029  7640 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-29 15:11:48.794  7029  7641 V BtOppRfcommListener: Starting RFCOMM listener....
08-29 15:11:48.795  1034  1957 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 15:11:48.795  7029  7640 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@366793cb on behalf of 
08-29 15:11:48.796  7029  7640 V BluetoothOppNotification: outbound: succ-0  fail-0
08-29 15:11:48.796  7029  7641 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 15:11:48.797  7029  7638 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-29 15:11:48.798  7029  7641 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-29 15:11:48.798  7029  7641 V BtOppRfcommListener: Started RFCOMM listener....
08-29 15:11:48.798  7029  7641 I BtOppRfcommListener: Accept thread started.
08-29 15:11:48.799  7029  7641 V BtOppRfcommListener: Accepting connection...
08-29 15:11:48.799  7029  7638 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1323f7a8 on behalf of 
,08-29 15:11:48.801  7029  7640 V BluetoothOppNotification: outbound notification was removed.
08-29 15:11:48.801  7029  7640 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-29 15:11:48.801  7029  7638 V BluetoothOppNotification: update too frequent, put in queue
08-29 15:11:48.802  7029  7638 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-29 15:11:48.803  7029  7640 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@fb5d2c1 on behalf of 
08-29 15:11:48.803  7029  7640 V BluetoothOppNotification: inbound: succ-0  fail-0
08-29 15:11:48.805  7029  7640 V BluetoothOppNotification: inbound notification was removed.
08-29 15:11:48.805  7029  7640 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-29 15:11:48.807  7029  7029 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f32e832
08-29 15:11:48.807  7029  7029 V BluetoothFtpService: Ftp Service onCreate
08-29 15:11:48.807  7029  7029 I BluetoothFtpService: Ftp Service onCreate
08-29 15:11:48.807  7029  7029 V BluetoothFtpService: Ftp Service onStartCommand
08-29 15:11:48.807  7029  7029 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 15:11:48.807  7029  7029 V BluetoothFtpService: Starting Listening on sockets
08-29 15:11:48.808  7029  7029 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 15:11:48.808  7029  7029 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 15:11:48.808  7029  7029 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 15:11:48.808  7029  7029 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 15:11:48.808  7029  7029 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-29 15:11:48.808  7029  7029 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-29 15:11:48.817  7029  7029 V BluetoothFtpService: Handler(): got msg=1
,08-29 15:11:48.819  7029  7029 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-29 15:11:48.819  7029  7029 V BluetoothFtpService: Ftp Service initSocket
08-29 15:11:48.825  1034  1560 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 15:11:48.826  7029  7029 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 15:11:48.827  7029  7029 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
08-29 15:11:48.827  7029  7029 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-29 15:11:48.830  7029  7643 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-29 15:11:48.844  7029  7029 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f32e832
08-29 15:11:48.845  7029  7029 V BluetoothSapService: Sap Service onCreate
,08-29 15:11:48.847  7029  7029 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 15:11:48.847  7029  7029 V BluetoothSapService: state: 12
08-29 15:11:48.847  7029  7029 V BluetoothSapService: Starting SAP server process
08-29 15:11:48.850  7029  7029 V BluetoothSapService: SAP Service startRfcommListenerThread
08-29 15:11:48.834  7644  7644 W sapd    : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 15:11:48.834  7644  7644 W sapd    : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 15:11:48.851  7029  7645 V BluetoothSapService: Sap Service initRfcommSocket
08-29 15:11:48.852  1034  1889 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 15:11:48.853  7029  7645 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 15:11:48.854  7029  7645 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
,08-29 15:11:48.854  7029  7645 V BluetoothSapService: Succeed to create listening socket 
08-29 15:11:48.854  7029  7645 V BluetoothSapService: Accepting socket connection...
08-29 15:11:48.872  7644  7644 V BT_SAP  : Event pipe created
08-29 15:11:48.872  7644  7644 V BT_SAP  : create_server_socket qcom.sap.server
08-29 15:11:48.872  7644  7644 V BT_SAP  : created socket fd 6
,08-29 15:11:48.954  1034  1991 I art     : Explicit concurrent mark sweep GC freed 90387(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 2.244ms total 143.085ms
,08-29 15:11:48.954  7029  7640 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@25a516f2 on behalf of 
,08-29 15:11:49.328  1034  1374 D LGWifiP2pService: P2pDisabledState{ when=-8ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 15:11:49.336  1034  1374 D LGWifiP2pService: DefaultState{ when=-8ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 15:11:49.449  1034  1376 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-29 15:11:49.451  1034  1376 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-29 15:11:49.781  7029  7029 V BluetoothOppNotification: new notify threadi!
,08-29 15:11:49.782  7029  7029 V BluetoothOppNotification: send delay message
,08-29 15:11:49.809  7029  7656 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-29 15:11:49.815  1034  1889 I ActivityManager: Killing 7424:com.lge.bnr/1000 (adj 15): empty #17
08-29 15:11:49.832  7029  7656 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@574b143 on behalf of 
,08-29 15:11:49.838  7029  7656 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-29 15:11:49.839  7029  7656 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-29 15:11:49.841  7029  7656 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3d8413c0 on behalf of 
08-29 15:11:49.841  7029  7656 V BluetoothOppNotification: outbound: succ-0  fail-0
08-29 15:11:49.843  7029  7656 V BluetoothOppNotification: outbound notification was removed.
08-29 15:11:49.843  7029  7656 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-29 15:11:49.844  7029  7656 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@35c118f9 on behalf of 
08-29 15:11:49.845  7029  7656 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-29 15:11:49.849  7029  7656 V BluetoothOppNotification: inbound notification was removed.
08-29 15:11:49.849  7029  7656 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-29 15:11:49.850  7029  7656 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@269b03e on behalf of 
08-29 15:11:49.855  1034  1874 W libprocessgroup: failed to open /acct/uid_1000/pid_7424/cgroup.procs: No such file or directory
08-29 15:11:49.863  1034  1049 I ActivityManager: Killing 6913:com.lge.sync/1000 (adj 15): empty #17
,08-29 15:11:49.882  1034  1440 D WifiService: Client connection lost with reason: 4
,08-29 15:11:49.895  1034  1991 W libprocessgroup: failed to open /acct/uid_1000/pid_6913/cgroup.procs: No such file or directory
,08-29 15:11:50.318  1034  1922 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-29 15:11:50.318  1034  1922 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@d8668b1 mBinding = false
,08-29 15:11:50.358  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 15:11:50.358  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 15:11:50.358  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-29 15:11:50.359  1034  1116 D BluetoothManagerService: Message: 2
08-29 15:11:50.360  1034  1116 D BluetoothManagerService: Sending off request.
08-29 15:11:50.360  7029  7538 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-29 15:11:50.361  7029  7499 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-29 15:11:50.361  7029  7499 D BluetoothAdapterProperties: Setting state to 13
08-29 15:11:50.361  7029  7499 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 15:11:50.362  7029  7499 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 15:11:50.362  7029  7499 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-29 15:11:50.364  7029  7503 D BluetoothAdapterProperties: Scan Mode:20
08-29 15:11:50.365  7029  7499 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-29 15:11:50.370  7029  7499 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-29 15:11:50.373  7029  7629 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 15:11:50.374  7029  7641 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 15:11:50.374  7029  7643 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 15:11:50.375  7029  7568 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-29 15:11:50.376  7029  7645 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 15:11:50.376  7029  7568 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-29 15:11:50.376  7029  7628 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-29 15:11:50.376  7029  7628 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 15:11:50.376  7029  7628 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-29 15:11:50.376  7029  7628 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-29 15:11:50.376  7029  7628 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-29 15:11:50.376  7029  7628 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-29 15:11:50.376  7029  7628 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-29 15:11:50.376  7029  7628 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-29 15:11:50.379  7029  7568 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 15:11:50.379  7029  7568 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 15:11:50.379  7029  7568 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 15:11:50.379  7029  7568 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 15:11:50.379  7029  7568 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 15:11:50.379  7029  7568 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 15:11:50.379  7029  7568 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 15:11:50.379  7029  7568 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
,08-29 15:11:50.379  7029  7568 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 15:11:50.382  7029  7568 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-29 15:11:50.382  7029  7568 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-29 15:11:50.382  7029  7568 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-29 15:11:50.387  6671  6671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:11:50.387  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:11:50.387  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:50.387  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 15:11:50.387  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 15:11:50.387  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 15:11:50.387  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:11:50.387  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:11:50.387  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 15:11:50.390  6671  6671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:11:50.390  6671  6671 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 15:11:50.398  6671  6671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 15:11:50.402  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:11:50.402  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:50.402  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 15:11:50.402  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 15:11:50.402  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 15:11:50.402  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:11:50.402  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:11:50.402  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 15:11:50.404  6671  6671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:11:50.404  6671  6671 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 15:11:50.406  1034  1116 D BluetoothManagerService: Message: 60
08-29 15:11:50.406  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-29 15:11:50.406  1034  1116 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-29 15:11:50.409  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-29 15:11:50.415  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 15:11:50.419  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:50.420  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:50.422  7029  7029 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 15:11:50.422  7029  7029 D BluetoothMapService: STATE_TURNING_OFF
08-29 15:11:50.422  7029  7029 V BluetoothMapService: Handler(): got msg=4
08-29 15:11:50.422  7029  7029 D BluetoothMapService: MAP Service closeService in
08-29 15:11:50.422  7029  7029 D BluetoothMapMasInstance: MAP Service shutdown
08-29 15:11:50.423  7029  7029 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 15:11:50.423  7029  7029 V BluetoothMapService: MAP Service closeService out
08-29 15:11:50.424  7029  7029 V BtOppService: Receiver DISABLED_ACTION 
08-29 15:11:50.425  7029  7029 I BtOppRfcommListener: stopping Accept Thread
08-29 15:11:50.425  7029  7029 V BtOppRfcommListener: close mBtServerSocket
,08-29 15:11:50.428  7029  7641 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 15:11:50.428  7029  7029 V BtOppRfcommListener: waiting for thread to terminate
08-29 15:11:50.429  7029  7029 V BtOppRfcommListener: done waiting for thread to terminate
08-29 15:11:50.432  6892  6892 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-29 15:11:50.441  6892  6892 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-29 15:11:50.445  7029  7029 V BtOppService: onDestroy
08-29 15:11:50.446  7029  7029 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-29 15:11:50.451  7029  7029 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 15:11:50.451  7029  7029 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 15:11:50.451  7029  7029 V BluetoothPbapReceiver: ***********state = 13
08-29 15:11:50.453  7029  7029 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,08-29 15:11:50.457  7029  7029 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 15:11:50.457  7029  7029 V BluetoothPbapService: state: 13
08-29 15:11:50.457  7029  7029 V BluetoothPbapService: Pbap Service closeService in
08-29 15:11:50.460  2198  2198 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 15:11:50.462  7029  7029 V BluetoothPbapService: successfully stopped pbap service
08-29 15:11:50.462  7029  7029 V BluetoothPbapService: Pbap Service closeService out
08-29 15:11:50.463  7029  7029 V BluetoothPbapService: Pbap Service onDestroy
08-29 15:11:50.463  7029  7029 V BluetoothPbapService: Pbap Service closeService in
08-29 15:11:50.463  7029  7029 V BluetoothPbapService: Pbap Service closeService out
08-29 15:11:50.463  7029  7029 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-29 15:11:50.486  6892  6892 D DockEventReceiver: finishStartingService: stopping service
,08-29 15:11:50.489  6892  6892 D BluetoothPbap: Proxy object disconnected
08-29 15:11:50.489  6892  6892 D PbapServerProfile: Bluetooth service disconnected
08-29 15:11:50.496  6892  6892 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-29 15:11:50.503  6892  6892 D BluetoothPermissionRequest: onReceive
08-29 15:11:50.503  6892  6892 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-29 15:11:50.509  6892  6892 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 15:11:50.512  7029  7029 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-29 15:11:50.512  7029  7029 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-29 15:11:50.512  7029  7029 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-29 15:11:50.516  7029  7029 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 15:11:50.516  7029  7029 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-29 15:11:50.518  7029  7029 V BluetoothFtpService: Ftp Service onStartCommand
08-29 15:11:50.518  7029  7029 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 15:11:50.518  7029  7029 V BluetoothFtpService: Ftp Service closeService
08-29 15:11:50.518  7029  7029 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-29 15:11:50.520  7029  7029 V BluetoothFtpService: successfully stopped ftp service
08-29 15:11:50.521  7029  7029 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 15:11:50.521  7029  7029 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 15:11:50.521  7029  7029 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 15:11:50.521  7029  7029 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 15:11:50.521  7029  7029 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-29 15:11:50.521  7029  7029 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-29 15:11:50.522  7029  7029 V BluetoothFtpService: Ftp Service onDestroy
08-29 15:11:50.522  7029  7029 V BluetoothFtpService: Ftp Service closeService
08-29 15:11:50.526  7029  7029 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 15:11:50.526  7029  7029 V BluetoothSapService: state: 13
08-29 15:11:50.526  7029  7029 V BluetoothSapService: Stopping SAP server process
,08-29 15:11:50.527  7029  7029 V BluetoothSapService: Sap Service closeSapService in
,08-29 15:11:50.528  7029  7029 V BluetoothSapService: Close listen Socket : 
,08-29 15:11:50.529  7029  7029 V BluetoothSapService: Close rfcomm Socket : 
08-29 15:11:50.529  7029  7029 V BluetoothSapService: Close sapd  Socket : 
,08-29 15:11:50.530  7029  7029 V BluetoothSapService: Sap Service closeSapService out
,08-29 15:11:50.530  7029  7029 V BluetoothSapService: Sap Service onDestroy
,08-29 15:11:50.530  7029  7029 V BluetoothSapService: Sap Service closeSapService in
,08-29 15:11:50.530  7029  7029 V BluetoothSapService: Close listen Socket : 
,08-29 15:11:50.530  7029  7029 V BluetoothSapService: Close rfcomm Socket : 
,08-29 15:11:50.530  7029  7029 V BluetoothSapService: Close sapd  Socket : ,
08-29 15:11:50.531  7029  7029 V BluetoothSapService: Sap Service closeSapService out
,08-29 15:11:51.339  7029  7503 D bt_hci_bdroid: cleanup
,08-29 15:11:51.356  7029  7601 I bt_userial_mct: exiting userial_read_thread
08-29 15:11:51.356  7029  7601 D bt_userial_mct: Leaving userial_evt_read_thread()
08-29 15:11:51.357  7029  7570 I bt_lpm  : LPM is already off!!!
08-29 15:11:51.357  7029  7568 W bt-btif : ag scb idx 1 not allocated
08-29 15:11:51.357  7029  7568 E bt-btif : BTA AG is already disabled, ignoring ...
08-29 15:11:51.357  7029  7568 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 15:11:51.357  7029  7568 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 15:11:51.357  7029  7568 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 15:11:51.357  7029  7568 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 15:11:51.357  7029  7568 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 15:11:51.357  7029  7568 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 15:11:51.357  7029  7568 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 15:11:51.357  7029  7568 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 15:11:51.358  7029  7568 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 15:11:51.358  7029  7568 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 15:11:51.358  7029  7568 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 15:11:51.358  7029  7568 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 15:11:51.358  7029  7568 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 15:11:51.358  7029  7568 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 15:11:51.358  7029  7568 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 15:11:51.358  7029  7568 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 15:11:51.358  7029  7568 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 15:11:51.358  7029  7568 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 15:11:51.358  7029  7568 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-29 15:11:51.362  7029  7503 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-29 15:11:51.362  7029  7570 I bt_vendor: hw_epilog_process
08-29 15:11:51.364  7029  7503 D bt_hci_bdroid: cleanup Finalizing cleanup
08-29 15:11:51.364  7029  7503 D bt_userial_mct: userial_close
08-29 15:11:51.364  7029  7503 E bt_userial_mct: pthread_join() FAILED result:3
08-29 15:11:51.364  7029  7503 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-29 15:11:51.374  7029  7503 D bt_hci_bdroid: set_power 0
08-29 15:11:51.374  7029  7503 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-29 15:11:51.375  7029  7503 I bt_vendor: bluetooth satus is on
08-29 15:11:51.375  7029  7503 I bt_vendor: bt-vendor : resetting BT status
,08-29 15:11:51.377  7029  7503 I bt_vendor: Starting hciattach daemon
08-29 15:11:51.377  7029  7503 I bt_vendor: try to set false
08-29 15:11:51.379  7029  7503 I bt_vendor: Starting hciattach daemon
08-29 15:11:51.379  7029  7503 I bt_vendor: try to set false
08-29 15:11:51.380  7029  7503 I bt_vendor: cleanup
08-29 15:11:51.380  7029  7568 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-29 15:11:51.381  7029  7503 I GKI_LINUX: GKI_exit_task 0 done
08-29 15:11:51.381  7029  7503 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-29 15:11:51.382  7029  7499 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-29 15:11:51.387  7029  7029 D HeadsetService: Received stop request...Stopping profile...
,08-29 15:11:51.391  7029  7029 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-29 15:11:51.391  7029  7029 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 15:11:51.391  7029  7029 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f32e832
08-29 15:11:51.392  7029  7530 D HeadsetStateMachine: Exit Disconnected: -1
08-29 15:11:51.394  1034  1034 D BluetoothHeadset: Proxy object disconnected
08-29 15:11:51.394  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-29 15:11:51.394  1836  1836 D BluetoothHeadset: Proxy object disconnected
08-29 15:11:51.395  1836  1836 D BluetoothHeadset: Proxy object disconnected
08-29 15:11:51.395  1836  1836 D BluetoothHeadset: Proxy object disconnected
08-29 15:11:51.399  7029  7029 D A2dpService: Received stop request...Stopping profile...
,08-29 15:11:51.402  7029  7553 D A2dpStateMachine: Exit Disconnected: -1
08-29 15:11:51.406  7029  7499 D BluetoothAdapterState: Stopping profile services that were post enabled
08-29 15:11:51.406  7029  7029 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-29 15:11:51.408  7029  7029 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-29 15:11:51.408  7029  7029 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 15:11:51.408  7029  7029 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f32e832
08-29 15:11:51.409  1034  1034 D BluetoothA2dp: Proxy object disconnected
08-29 15:11:51.409  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-29 15:11:51.410  7029  7029 D HidService: Received stop request...Stopping profile...
08-29 15:11:51.410  7029  7029 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f32e832
08-29 15:11:51.413  7029  7029 D HeadsetStateMachine: Unbinding service...
,08-29 15:11:51.416  7029  7029 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 15:11:51.416  7029  7029 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 15:11:51.416  7029  7029 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 15:11:51.417  7029  7029 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 15:11:51.417  7029  7029 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 15:11:51.417  7029  7029 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 15:11:51.417  7029  7029 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-29 15:11:51.419  7029  7029 D HealthService: Received stop request...Stopping profile...
08-29 15:11:51.419  7029  7029 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f32e832
08-29 15:11:51.420  7029  7029 D PanService: Received stop request...Stopping profile...
08-29 15:11:51.421  7029  7029 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f32e832
08-29 15:11:51.422  7029  7029 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 15:11:51.422  7029  7029 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 15:11:51.423  7029  7029 D BtGatt.GattService: stop()
08-29 15:11:51.423  7029  7029 D BtGatt.AdvertiseManager: advertise clients cleared
08-29 15:11:51.424  7029  7029 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f32e832
08-29 15:11:51.425  7029  7029 D BluetoothMapService: Received stop request...Stopping profile...
08-29 15:11:51.425  7029  7029 D BluetoothMapService: stop()
,08-29 15:11:51.429  7029  7029 D BluetoothMapEmailAppObserver: deinitObservers()
08-29 15:11:51.429  7029  7029 D BluetoothMapEmailAppObserver: removeReceiver()
08-29 15:11:51.431  7029  7029 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f32e832
08-29 15:11:51.434  7029  7029 I BluetoothA2dpServiceJni: cleanupNative
08-29 15:11:51.434  7029  7554 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-29 15:11:51.435  7029  7029 I GKI_LINUX: GKI_exit_task 2 done
08-29 15:11:51.435  7029  7029 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-29 15:11:51.435  7029  7029 V BluetoothMapService: Handler(): got msg=4
08-29 15:11:51.435  7029  7029 D BluetoothMapService: MAP Service closeService in
08-29 15:11:51.435  7029  7029 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 15:11:51.435  7029  7029 V BluetoothMapService: MAP Service closeService out
08-29 15:11:51.437  7029  7499 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-29 15:11:51.437  7029  7499 D BluetoothAdapterProperties: Setting state to 10
08-29 15:11:51.437  7029  7499 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-29 15:11:51.437  7029  7029 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 15:11:51.437  7029  7029 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 15:11:51.438  7029  7029 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-29 15:11:51.440  7029  7029 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 15:11:51.440  7029  7029 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 15:11:51.443  1034  1116 D BluetoothManagerService: Message: 60
08-29 15:11:51.443  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-29 15:11:51.443  1034  1116 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-29 15:11:51.445  7029  7029 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 15:11:51.445  7029  7029 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 15:11:51.447  7029  7499 I BluetoothAdapterState: Entering OffState
08-29 15:11:51.447  1836  2416 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 15:11:51.449  6892  7621 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 15:11:51.451  1034  1116 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 15:11:51.452  6892  7621 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 15:11:51.452  1034  1116 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 15:11:51.453  7029  7029 D BluetoothMapService: cleanup()
08-29 15:11:51.453  7029  7029 D BluetoothMapService: MAP Service closeService in
08-29 15:11:51.453  7029  7029 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 15:11:51.453  7029  7029 V BluetoothMapService: MAP Service closeService out
08-29 15:11:51.454  6892  7621 D BluetoothMap: onBluetoothStateChange: up=false
08-29 15:11:51.454  6892  7621 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 15:11:51.456  6892  7621 D BluetoothPan: onBluetoothStateChange on: false
08-29 15:11:51.457  6892  7621 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 15:11:51.457  1836  4429 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 15:11:51.458  1836  4430 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 15:11:51.459  1034  1116 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-29 15:11:51.459  1034  1116 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-29 15:11:51.461  1034  1116 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-29 15:11:51.461  1034  1116 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-29 15:11:51.461  1034  1116 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@d8668b1 mBinding = false
,08-29 15:11:51.463  1034  1116 D BluetoothManagerService: Sending unbind request.
08-29 15:11:51.468  7029  7503 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-29 15:11:51.469  7029  7029 I GKI_LINUX: GKI_exit_task 1 done
08-29 15:11:51.469  7029  7029 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-29 15:11:51.470  7029  7029 I BluetoothServiceJni: cleanupNative: return from cleanup
08-29 15:11:51.470  7029  7029 I art     : --- WEIRD: removing null entry 248
08-29 15:11:51.470  7029  7029 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-29 15:11:51.470  7029  7029 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-29 15:11:51.471  7029  7029 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-29 15:11:51.472  1034  1116 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,08-29 15:11:51.476  7029  7029 I art     : System.exit called, status: 0
08-29 15:11:51.476  7029  7029 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-29 15:11:51.496   316  1381 V AudioFlinger: 7029 died, releasing its sessions
08-29 15:11:51.496   316  1381 V AudioFlinger:  pid 1836 @ 0
08-29 15:11:51.496   316  1381 V AudioFlinger:  pid 3379 @ 1
08-29 15:11:51.496   316  1381 V AudioFlinger:  pid 3379 @ 2
,08-29 15:11:51.500  1925  1925 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-29 15:11:51.500  1925  2110 D LGBluetoothAPIService: Message: 101
08-29 15:11:51.500  1925  2110 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-29 15:11:51.500  1925  2110 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-29 15:11:51.500  1925  2110 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-29 15:11:51.503  6892  6892 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-29 15:11:51.505  1034  1758 I ActivityManager: Process com.android.bluetooth (pid 7029) has died
08-29 15:11:51.505  1034  1758 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
08-29 15:11:51.505  1034  1758 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
08-29 15:11:51.512  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-29 15:11:51.515  1925  2110 D LGBluetoothAPIService: Message: 2
08-29 15:11:51.515  1925  2110 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-29 15:11:51.516  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:51.516  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:51.517  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 15:11:51.522  6892  6892 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-29 15:11:51.522  6892  6892 D LGBluetoothEventManager: [BTUI] clear device connection state
08-29 15:11:51.526  6892  6892 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-29 15:11:51.548  1587  1587 D BluetoothAdapter: 805133429: getState() :  mService = null. Returning STATE_OFF
08-29 15:11:51.548  1587  1587 D BluetoothAdapter: 805133429: getState() :  mService = null. Returning STATE_OFF
,08-29 15:11:51.601  1034  1957 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7702 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-29 15:11:51.603  6892  6892 D DockEventReceiver: finishStartingService: stopping service
,08-29 15:11:51.672  7702  7702 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-29 15:11:51.672  7702  7702 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 15:11:51.673  7702  7702 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-29 15:11:51.674  7702  7702 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-29 15:11:51.694  7702  7702 D BluetoothAdapterApp: Loading JNI Library
,08-29 15:11:51.727  7702  7702 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@69537da Instance Count = 1
,08-29 15:11:51.732  7702  7702 D BluetoothAdapterApp: onCreate
,08-29 15:11:51.751  7702  7702 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-29 15:11:51.752  7702  7702 D ProfileConfigQcom: Adding HeadsetService
,08-29 15:11:51.752  7702  7702 D ProfileConfigQcom: [BTUI] A2dpService is supported
,08-29 15:11:51.752  7702  7702 D ProfileConfigQcom: Adding A2dpService
,08-29 15:11:51.752  7702  7702 D ProfileConfigQcom: [BTUI] HidService is supported
08-29 15:11:51.752  7702  7702 D ProfileConfigQcom: Adding HidService
,08-29 15:11:51.752  7702  7702 D ProfileConfigQcom: [BTUI] HealthService is supported
08-29 15:11:51.752  7702  7702 D ProfileConfigQcom: Adding HealthService
,08-29 15:11:51.753  7702  7702 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-29 15:11:51.753  7702  7702 D ProfileConfigQcom: [BTUI] PanService is supported
08-29 15:11:51.754  7702  7702 D ProfileConfigQcom: Adding PanService
08-29 15:11:51.754  7702  7702 D ProfileConfigQcom: [BTUI] GattService is supported
,08-29 15:11:51.754  7702  7702 D ProfileConfigQcom: Adding GattService
08-29 15:11:51.754  7702  7702 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-29 15:11:51.754  7702  7702 D ProfileConfigQcom: Adding BluetoothMapService
08-29 15:11:51.754  7702  7702 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
,08-29 15:11:51.755  7702  7702 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 15:11:51.756  7702  7702 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 15:11:51.756  7702  7702 V BluetoothPbapReceiver: ***********state = 10
08-29 15:11:51.758  7702  7702 V LGMDMManagerInternal: Create singleton instance
,08-29 15:11:51.812  7702  7702 D LGBluetoothAPIServer: [BTUI] onCreate(),
08-29 15:11:51.812  7702  7702 D LGBluetoothAPIServer: [BTUI] onBind()
,08-29 15:11:51.816  2198  2198 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 15:11:51.817  1925  1925 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-29 15:11:51.818  1925  2110 D LGBluetoothAPIService: Message: 100
08-29 15:11:51.818  1925  2110 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-29 15:11:51.820  6892  6892 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-29 15:11:51.844  6892  6892 D BluetoothPermissionRequest: onReceive
,08-29 15:11:51.848  6892  6892 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-29 15:11:51.848  6892  6892 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-29 15:11:51.852  6892  6892 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 15:11:51.861  7702  7702 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-29 15:11:51.869  7702  7702 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 15:11:51.872  7702  7702 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 15:11:51.873  7702  7702 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 15:11:51.873  7702  7702 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 15:11:51.874  7702  7702 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 15:11:51.874  7702  7702 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-29 15:11:51.881  6959  6959 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-29 15:11:53.205  1034  1362 V AlarmManager: ELAPSED_WAKEUP set : Alarm{a5b2904 type 2 when 133445 com.google.android.gms} when 133445
,08-29 15:11:53.213   310  7734 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-29 15:11:53.218  1034  1114 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-29 15:11:53.432  6671  6818 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 15:11:53.433  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 15:11:53.468  1587  1587 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-29 15:11:53.500  1034  1364 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-29 15:11:53.580  1034  1112 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7735 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-29 15:11:53.598  2016  2016 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-29 15:11:53.606  1587  1587 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-29 15:11:53.610  1034  1034 D administrator: Handling package changes for user 0
08-29 15:11:53.614  1587  1587 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,08-29 15:11:53.660  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-29 15:11:53.668  7735  7735 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-29 15:11:53.704  1034  1034 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,08-29 15:11:53.705  1034  1034 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-29 15:11:53.748  7735  7735 D LgDataFeature: LgDataFeature() Constructor: none
08-29 15:11:53.748  7735  7735 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 15:11:53.749  1034  1111 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 15:11:53.754  1034  1111 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-29 15:11:53.760  2016  2016 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-29 15:11:53.762  2473  2473 V GmsNetworkLocationProvi: DISABLE
,08-29 15:11:53.806  1034  1111 D LocationProviderProxy: applying state to connected service
,08-29 15:11:53.808  2473  2473 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-29 15:11:53.836  7735  7781 I Babel   : MmsConfig: mnc/mcc: 0/0
08-29 15:11:53.836  7735  7781 I Babel   : MmsConfig.loadMmsSettings
08-29 15:11:53.838  7735  7781 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-29 15:11:53.838  7735  7781 I Babel   : MmsConfig.loadFromDatabase
,08-29 15:11:53.856  7735  7781 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-29 15:11:53.856  7735  7781 I Babel   : MmsConfig.loadFromResources
08-29 15:11:53.858  7735  7781 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-29 15:11:53.859  7735  7781 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-29 15:11:53.869  7735  7779 W AudioCapabilities: Unsupported mime audio/evrc
,08-29 15:11:53.870  7735  7735 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:11:53.870  7735  7779 W AudioCapabilities: Unsupported mime audio/qcelp
08-29 15:11:53.878  7735  7779 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 15:11:53.889  1801  7783 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-29 15:11:53.889  1801  7783 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-29 15:11:53.890  7735  7779 W AudioCapabilities: Unsupported mime audio/amr-wb-plus,
08-29 15:11:53.890  7735  7779 W AudioCapabilities: Unsupported mime audio/qcelp
08-29 15:11:53.891  7735  7779 W AudioCapabilities: Unsupported mime audio/evrc
08-29 15:11:53.895  7094  7094 I AppUp4:CustModeStarterReceiver: onReceive
,08-29 15:11:53.905  7094  7094 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@c958594
08-29 15:11:53.905  7094  7094 D AppUp4:CustFacade: isCustomizationCompleted : false
08-29 15:11:53.905  7094  7094 D AppUp4:CustFacade: isPhone : true
08-29 15:11:53.905  7094  7094 D AppUp4:CustModeStarterReceiver: begin check event
08-29 15:11:53.906  7094  7094 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-29 15:11:53.907  1801  4734 I Icing   : updateResources: need to parse e{com.google.android.gms}
,08-29 15:11:53.918  7735  7779 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-29 15:11:53.923  7735  7779 W VideoCapabilities: Unsupported mime video/divx
08-29 15:11:53.926  7735  7779 W VideoCapabilities: Unsupported mime video/divx311
08-29 15:11:53.927  7735  7779 W VideoCapabilities: Unsupported mime video/divx4
08-29 15:11:53.934  7735  7779 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-29 15:11:53.953  1034  1889 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7786 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-29 15:11:53.958  1034  2011 I ActivityManager: Killing 6795:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-29 15:11:53.962  7735  7779 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
08-29 15:11:53.965  7735  7779 W AudioCapabilities: Unsupported mime audio/eac3
08-29 15:11:53.965  7735  7779 W AudioCapabilities: Unsupported mime audio/ac3
08-29 15:11:53.966  7735  7779 W AudioCapabilities: Unsupported mime audio/g726
08-29 15:11:53.967  7735  7779 W AudioCapabilities: Unsupported mime audio/wma-voice
08-29 15:11:53.967  7735  7779 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-29 15:11:53.968  7735  7779 W AudioCapabilities: Unsupported mime audio/adpcm
08-29 15:11:53.970  7735  7779 W VideoCapabilities: Unsupported mime video/theora
08-29 15:11:53.971  7735  7779 W VideoCapabilities: Unsupported mime video/mjpg
08-29 15:11:53.976  6941  6941 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-29 15:11:53.976  6941  6941 W System.err: android.os.DeadObjectException
08-29 15:11:53.976  6941  6941 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-29 15:11:53.976  6941  6941 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-29 15:11:53.976  6941  6941 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-29 15:11:53.976  6941  6941 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-29 15:11:53.976  6941  6941 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-29 15:11:53.976  6941  6941 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-29 15:11:53.976  6941  6941 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 15:11:53.976  6941  6941 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 15:11:53.976  6941  6941 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-29 15:11:53.976  6941  6941 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 15:11:53.976  6941  6941 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 15:11:53.976  6941  6941 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 15:11:53.976  6941  6941 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 15:11:53.976  6941  6941 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 15:11:53.976  6941  6941 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-29 15:11:53.977  6941  6941 W System.err: android.os.DeadObjectException
08-29 15:11:53.977  6941  6941 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-29 15:11:53.977  6941  6941 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-29 15:11:53.977  6941  6941 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-29 15:11:53.977  6941  6941 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-29 15:11:53.977  6941  6941 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-29 15:11:53.977  6941  6941 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-29 15:11:53.977  6941  6941 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 15:11:53.977  6941  6941 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 15:11:53.977  6941  6941 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-29 15:11:53.977  6941  6941 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 15:11:53.977  6941  6941 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 15:11:53.977  6941  6941 W System.err: 	at java,.lang.reflect.Method.invoke(Method.java:372)
08-29 15:11:53.977  6941  6941 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 15:11:53.977  6941  6941 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 15:11:53.977  6941  6941 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-29 15:11:53.977  6941  6941 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-29 15:11:54.164  1034  2011 E libprocessgroup: failed to kill 1 processes for processgroup 6795
,08-29 15:11:54.405  1034  1922 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-29 15:11:54.434  6941  6941 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-29 15:11:54.434  6941  6941 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-29 15:11:54.457  7786  7786 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 15:11:54.457  7786  7786 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 15:11:54.458  7786  7786 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-29 15:11:54.459  7786  7786 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-29 15:11:54.459  7786  7786 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-29 15:11:54.483  1034  1962 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7810 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-29 15:11:54.485  6941  6941 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-29 15:11:54.570  7810  7810 D UEI.SmartControl: Quickset Services start...
,08-29 15:11:54.574  7810  7810 I UEI.SmartControl: Manufacture = LGE
08-29 15:11:54.575  7810  7810 D UEI.SmartControl: Id = LGNevo
08-29 15:11:54.576  7810  7810 D UEI.SmartControl: File observer start...
,08-29 15:11:54.576  7810  7810 E UEI.SmartControl: IR Port is disabled: false
08-29 15:11:54.577  7810  7810 D UEI.SmartControl: Starting file observer...
08-29 15:11:54.577  7810  7810 D UEI.SmartControl: Extracting JNI libs...
08-29 15:11:54.577  7810  7810 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-29 15:11:54.602  7786  7786 I SystemConfig: BUILD Country: EU
08-29 15:11:54.603  7786  7786 I SystemConfig: BUILD Operator: OPEN
,08-29 15:11:54.665  7810  7810 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-29 15:11:54.665  7810  7810 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
,08-29 15:11:54.665  7810  7810 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
08-29 15:11:54.671  1034  1598 I ActivityManager: Killing 6941:com.lge.qremote/u0a112 (adj 15): empty #17
08-29 15:11:54.692  7810  7810 I UEI.SmartControl: --- Selecting new region: 6
08-29 15:11:54.694  7810  7810 I UEI.SmartControl: Model = LG-D855
,08-29 15:11:54.696  7810  7810 D UEI.SmartControl: QS Service created
,08-29 15:11:54.773  1034  1049 W libprocessgroup: failed to open /acct/uid_10112/pid_6941/cgroup.procs: No such file or directory
,08-29 15:11:54.805  7810  7810 I UEI.SmartControl: Service initServices...
,08-29 15:11:54.811  7810  7810 D UEI.SmartControl: QS start get config
08-29 15:11:54.857  1034  1598 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7842 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-29 15:11:54.874  7786  7840 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-29 15:11:54.874  7786  7840 I SystemConfig: existFile = false
08-29 15:11:54.874  7786  7840 I SystemConfig: canReadFile = false
08-29 15:11:54.874  7786  7840 I SystemConfig: systemFeature RCS result false
08-29 15:11:54.874  7786  7840 D SystemConfig: refreshRcsSupport() :false
,08-29 15:11:54.884  7810  7810 D UEI.SmartControl: Loading JNI Libs...
,08-29 15:11:54.930  7842  7842 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 15:11:54.930  7842  7842 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-29 15:11:54.930  7842  7842 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,08-29 15:11:54.931  7842  7842 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-29 15:11:55.026  7842  7842 I AppConfig: Total System Memory = 2995761152
,08-29 15:11:55.035  7842  7842 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-29 15:11:55.117  7810  7810 I UEI.SmartControl: Supports setup maps: true
08-29 15:11:55.119  1034  1922 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7861 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 15:11:55.120  7810  7810 D UEI.SmartControl: QS start statue = true Error code = 0
08-29 15:11:55.120  7810  7810 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-29 15:11:55.120  7810  7810 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-29 15:11:55.120  7810  7810 I UEI.SmartControl: ### init IR Blaster...
08-29 15:11:55.121  1034  1922 I ActivityManager: Killing 7128:com.lge.email/u0a23 (adj 15): empty #17
08-29 15:11:55.126  7810  7810 D serial_port: Configuring serial port
08-29 15:11:55.129  7810  7810 E UEI.SmartControl: UEIBLaster setting for 616
08-29 15:11:55.129  7810  7810 I UEI.SmartControl: Setting serial record hearder size = 2
08-29 15:11:55.129  7810  7810 I UEI.SmartControl: configuring settings for MAXQ616
08-29 15:11:55.129  7810  7810 I UEI.SmartControl: Get version...
08-29 15:11:55.145  7810  7871 D UEI.SmartControl: serial port data available: 21
,08-29 15:11:55.172  7810  7810 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-29 15:11:55.172  7810  7810 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-29 15:11:55.172  7810  7810 I UEI.SmartControl: QS saving settings...
08-29 15:11:55.172  7810  7810 D UEI.SmartControl: IR Blaster version: 25672567
08-29 15:11:55.174  1034  1929 W libprocessgroup: failed to open /acct/uid_10023/pid_7128/cgroup.procs: No such file or directory
,08-29 15:11:55.186  7810  7871 D UEI.SmartControl: serial port data available: 4
,08-29 15:11:55.217  7810  7810 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-29 15:11:55.219  7810  7810 E UEI.SmartControl: Services init done
08-29 15:11:55.219  7810  7810 D UEI.SmartControl: QS Service init finished
08-29 15:11:55.221  7810  7810 D UEI.SmartControl: QS Service version name: 2.1.91
08-29 15:11:55.221  7810  7810 D UEI.SmartControl: QS Service version code: 201091
08-29 15:11:55.221  7810  7885 I UEI.SmartControl: Device manager: loading config....
,08-29 15:11:55.222  7810  7885 D UEI.SmartControl: ----------- loading internal config...
08-29 15:11:55.224  7810  7810 D UEI.SmartControl: Service requested: Control
08-29 15:11:55.227  7810  7885 E UEI.SmartControl: Loading SETTINGS...
,08-29 15:11:55.230  7810  7810 D UEI.SmartControl: Request IControl service: devices are loaded...
08-29 15:11:55.230  7810  7810 D UEI.SmartControl: Service.onUnbind: IControl
08-29 15:11:55.232  7810  7810 D UEI.SmartControl: Service.onDestroy
08-29 15:11:55.232  7810  7810 D UEI.SmartControl: Lock is in USE false
08-29 15:11:55.233  7810  7810 D UEI.SmartControl: unbind internal service
08-29 15:11:55.233  7810  7810 D serial_port: close(fd = 25)
,08-29 15:11:55.236  7810  7884 I UEI.SmartControl: Notify AllClients services are ready: 0
08-29 15:11:55.236  7810  7884 D UEI.SmartControl: -----service ready thread exits
08-29 15:11:55.237  7810  7810 I UEI.SmartControl: Serial port is closed.
08-29 15:11:55.237  7810  7810 I UEI.SmartControl: Serial port is closed.
08-29 15:11:55.237  7810  7810 D UEI.SmartControl: Blaster closed
08-29 15:11:55.237  7810  7810 D UEI.SmartControl: Shut down QS...
08-29 15:11:55.237  7810  7810 D UEI.SmartControl: Stopping QS lib
08-29 15:11:55.238  7810  7810 D UEI.SmartControl: QS lib stop result = true
08-29 15:11:55.238  7810  7810 D UEI.SmartControl: Stopped QS lib
08-29 15:11:55.238  7810  7810 D UEI.SmartControl: Stopped file observer...
08-29 15:11:55.238  7810  7810 D UEI.SmartControl: QS shutdown complete
,08-29 15:11:55.238  7810  7810 D UEI.SmartControl: QS Service created
08-29 15:11:55.241  7810  7885 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-29 15:11:55.247  7810  7810 I UEI.SmartControl: Service initServices...
08-29 15:11:55.247  7810  7810 D UEI.SmartControl: QS start get config
,08-29 15:11:55.364  7861  7861 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-29 15:11:55.470  7861  7861 D LgDataFeature: LgDataFeature() Constructor: none
08-29 15:11:55.470  7861  7861 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 15:11:55.489  7810  7810 I UEI.SmartControl: Supports setup maps: true
,08-29 15:11:55.493  7810  7810 D UEI.SmartControl: QS start statue = true Error code = 0
,08-29 15:11:55.493  7810  7810 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-29 15:11:55.493  7810  7810 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-29 15:11:55.493  7810  7810 I UEI.SmartControl: ### init IR Blaster...
08-29 15:11:55.496  7810  7810 D serial_port: Configuring serial port
08-29 15:11:55.496  7810  7810 E UEI.SmartControl: UEIBLaster setting for 616
08-29 15:11:55.496  7810  7810 I UEI.SmartControl: Setting serial record hearder size = 2
08-29 15:11:55.496  7810  7810 I UEI.SmartControl: configuring settings for MAXQ616
08-29 15:11:55.496  7810  7810 I UEI.SmartControl: Get version...
08-29 15:11:55.513  7810  7909 D UEI.SmartControl: serial port data available: 21
,08-29 15:11:55.538  7810  7810 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-29 15:11:55.538  7810  7810 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-29 15:11:55.538  7810  7810 I UEI.SmartControl: QS saving settings...
08-29 15:11:55.539  7810  7810 D UEI.SmartControl: IR Blaster version: 25672567
08-29 15:11:55.545  7861  7861 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-29 15:11:55.556  7810  7909 D UEI.SmartControl: serial port data available: 4
08-29 15:11:55.576  7861  7861 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-29 15:11:55.577  7861  7861 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-29 15:11:55.586  7810  7810 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-29 15:11:55.588  7810  7810 E UEI.SmartControl: Services init done
,08-29 15:11:55.588  7810  7810 D UEI.SmartControl: QS Service init finished
08-29 15:11:55.591  7810  7915 I UEI.SmartControl: Device manager: loading config....
08-29 15:11:55.591  7810  7915 D UEI.SmartControl: ----------- loading internal config...
08-29 15:11:55.593  7810  7810 D UEI.SmartControl: QS Service version name: 2.1.91
08-29 15:11:55.593  7810  7810 D UEI.SmartControl: QS Service version code: 201091
08-29 15:11:55.594  7810  7810 D UEI.SmartControl: Service requested: Control
08-29 15:11:55.595  7861  7861 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-29 15:11:55.595  7861  7861 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
08-29 15:11:55.598  7810  7915 E UEI.SmartControl: Loading SETTINGS...
08-29 15:11:55.600  7810  7810 D UEI.SmartControl: Request IControl service: devices are loaded...
08-29 15:11:55.604  1034  1962 I ActivityManager: Killing 6994:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-29 15:11:55.615  7810  7915 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-29 15:11:55.625  7810  7914 I UEI.SmartControl: Notify AllClients services are ready: 0
08-29 15:11:55.626  7810  7914 D UEI.SmartControl: -----service ready thread exits
,08-29 15:11:55.645  7810  7810 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@130f6700 that was originally bound here
08-29 15:11:55.645  7810  7810 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@130f6700 that was originally bound here
08-29 15:11:55.645  7810  7810 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
08-29 15:11:55.645  7810  7810 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
08-29 15:11:55.645  7810  7810 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
08-29 15:11:55.645  7810  7810 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
08-29 15:11:55.645  7810  7810 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
08-29 15:11:55.645  7810  7810 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
08-29 15:11:55.645  7810  7810 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
08-29 15:11:55.645  7810  7810 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
08-29 15:11:55.645  7810  7810 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
08-29 15:11:55.645  7810  7810 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
08-29 15:11:55.645  7810  7810 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
08-29 15:11:55.645  7810  7810 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:11:55.645  7810  7810 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
08-29 15:11:55.645  7810  7810 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 15:11:55.645  7810  7810 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 15:11:55.645  7810  7810 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 15:11:55.645  7810  7810 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 15:11:55.645  7810  7810 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 15:11:55.647  7810  7810 D UEI.SmartControl: Internal service binding...
,08-29 15:11:55.648  1034  1598 W libprocessgroup: failed to open /acct/uid_10026/pid_6994/cgroup.procs: No such file or directory
,08-29 15:11:55.655  1034  2032 I ActivityManager: Killing 6461:com.wsandroid.suite.lge/1000 (adj 15): empty #17
08-29 15:11:55.752  1034  1889 W libprocessgroup: failed to open /acct/uid_1000/pid_6461/cgroup.procs: No such file or directory
,08-29 15:11:55.759  2830  2845 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-29 15:11:55.761  2830  2845 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@23938078 on behalf of 7861
08-29 15:11:55.768  4603  7922 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-29 15:11:55.840  1034  1957 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7923 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-29 15:11:55.872  7861  7861 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-29 15:11:55.894  7861  7861 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-29 15:11:55.924  7923  7923 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-29 15:11:55.948  7923  7923 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,08-29 15:11:55.949  7923  7923 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-29 15:11:55.949  7923  7923 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-29 15:11:55.949  7923  7923 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-29 15:11:55.949  7923  7923 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-29 15:11:55.949  7923  7923 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-29 15:11:55.972  1034  1874 I ActivityManager: Killing 7170:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-29 15:11:56.005  1034  1050 W libprocessgroup: failed to open /acct/uid_10046/pid_7170/cgroup.procs: No such file or directory
,08-29 15:11:56.205  1034  1962 V SIM_STK : Menu title from STK is T-Mobile
,08-29 15:11:56.232  7810  7887 D UEI.SmartControl: Internal timer expired: 2
,08-29 15:11:56.252  4603  7922 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 484 ms] updated apps [took 484 ms] 
,08-29 15:11:56.448  6671  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 15:11:56.448  6671  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3a87506 added. We now have 6 listener(s)
08-29 15:11:56.448  6671  6818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 15:11:56.453  6671  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 15:11:56.453  6671  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2b05d7c7 added. We now have 7 listener(s)
08-29 15:11:56.453  6671  6818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 15:11:56.464  6671  6818 I System.out: IsBluetoothEnabled
,08-29 15:11:56.468  1034  1049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 15:11:56.468  1034  1049 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-29 15:11:56.469  1034  1116 D BluetoothManagerService: Message: 2
08-29 15:11:56.485  6671  6818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:11:56.488  1034  1889 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 15:11:56.488  1034  1889 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-29 15:11:56.510  1034  1116 D BluetoothManagerService: Message: 1
08-29 15:11:56.510  1034  1116 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-29 15:11:56.513  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 15:11:56.513  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 15:11:56.513  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-29 15:11:56.541  1034  1116 D BluetoothManagerService: Message: 20
08-29 15:11:56.541  1034  1116 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3e67caf0:true
,08-29 15:11:56.545  7702  7702 D BluetoothAdapterState: make
08-29 15:11:56.549  7702  7702 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-29 15:11:56.549  7702  7702 I bluedroid-qcom: init
08-29 15:11:56.551  7702  7953 I BluetoothAdapterState: Entering OffState
08-29 15:11:56.551  7702  7702 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-29 15:11:56.551  7702  7702 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-29 15:11:56.551  7702  7702 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 15:11:56.551  7702  7702 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 15:11:56.551  7702  7702 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-29 15:11:56.553  7702  7702 I bluedroid-qcom: get_profile_interface socket
08-29 15:11:56.553  7702  7702 I bluedroid-qcom: get_profile_interface map_client
,08-29 15:11:56.557  7702  7957 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-29 15:11:56.544  7956  7956 W bdaddr_loader: type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 15:11:56.544  7956  7956 W bdaddr_loader: type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 15:11:56.565  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-29 15:11:56.566  1034  1116 D BluetoothManagerService: Message: 40
08-29 15:11:56.566  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-29 15:11:56.567  7702  7717 I bluedroid-qcom: config_hci_snoop_log
,08-29 15:11:56.574  1034  1116 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-29 15:11:56.574  1034  1116 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-29 15:11:56.580  7702  7957 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-29 15:11:56.591  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-29 15:11:56.591  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-29 15:11:56.592  7956  7956 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-29 15:11:56.592  7956  7956 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
,08-29 15:11:56.592  7956  7956 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-29 15:11:56.592  7702  7957 D BluetoothAdapterProperties: Name is: G3
08-29 15:11:56.598  7702  7953 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-29 15:11:56.598  7702  7953 D BluetoothAdapterProperties: Setting state to 11
08-29 15:11:56.599  7702  7953 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-29 15:11:56.599  7956  7956 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-29 15:11:56.600  1034  1116 D BluetoothManagerService: Message: 60
08-29 15:11:56.600  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-29 15:11:56.600  1034  1116 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-29 15:11:56.601  7702  7953 I LGBluetoothServiceJni: classInitNative: succeeds
08-29 15:11:56.603  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 15:11:56.604  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-29 15:11:56.608  7956  7956 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-29 15:11:56.608  7956  7956 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-29 15:11:56.610  6892  6892 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-29 15:11:56.610  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:56.614  7702  7953 D BluetoothBondStateMachine: make
08-29 15:11:56.614  7702  7702 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 15:11:56.615  7702  7702 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 15:11:56.615  7702  7702 V BluetoothPbapReceiver: ***********state = 11
08-29 15:11:56.619  2198  2198 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 15:11:56.620  7702  7953 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14184983
08-29 15:11:56.621  7702  7953 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-29 15:11:56.621  7702  7953 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14184983
08-29 15:11:56.621  7702  7953 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-29 15:11:56.622  7702  7953 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-29 15:11:56.623  7702  7974 I BluetoothBondStateMachine: StableState(): Entering Off State
08-29 15:11:56.627  7702  7953 E BluetoothAdapterService: File transfer profiles supported!!
08-29 15:11:56.632  6892  6892 D BluetoothPermissionRequest: onReceive
,08-29 15:11:56.639  6892  6892 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 15:11:56.641  7702  7702 D HeadsetService: Received start request. Starting profile...
08-29 15:11:56.641  7702  7953 E BluetoothAdapterService: File transfer profiles supported!!
08-29 15:11:56.642  7702  7702 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 15:11:56.642  7702  7702 D LGBluetoothHfpAdapter: Version 1.6
08-29 15:11:56.645  7702  7702 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-29 15:11:56.646  7702  7702 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-29 15:11:56.647  7702  7702 D HeadsetStateMachine: make
,08-29 15:11:56.649  7702  7953 E BluetoothAdapterService: File transfer profiles supported!!
08-29 15:11:56.654  7702  7953 E BluetoothAdapterService: File transfer profiles supported!!
08-29 15:11:56.659  7702  7953 E BluetoothAdapterService: File transfer profiles supported!!
,08-29 15:11:56.666  7702  7953 E BluetoothAdapterService: File transfer profiles supported!!
08-29 15:11:56.671  7702  7953 E BluetoothAdapterService: File transfer profiles supported!!
,08-29 15:11:56.687  7702  7702 D LgDataFeature: LgDataFeature() Constructor: none
,08-29 15:11:56.687  7702  7702 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 15:11:56.687  7702  7953 V LGMDMManager: Create singleton instance
08-29 15:11:56.689  7702  7953 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-29 15:11:56.692  7702  7702 D HeadsetStateMachine: max_hf_connections = 1
08-29 15:11:56.692  7702  7702 I bluedroid-qcom: get_profile_interface handsfree
,08-29 15:11:56.694  7702  7702 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-29 15:11:56.695   316  2153 V AudioPolicyService: registerClient() client 0xb1025c40, uid 1002
08-29 15:11:56.695   316  1382 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-29 15:11:56.695   316  1382 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 15:11:56.695   316  1382 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 15:11:56.696  7702  7702 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-29 15:11:56.696   316  2154 V AudioFlinger: registerClient() client 0xb1024d48, pid 7702
08-29 15:11:56.697   316  1375 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 15:11:56.697   316  1375 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 15:11:56.697  1587  1606 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 15:11:56.697   316  1377 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 15:11:56.697  3379  3396 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 15:11:56.697   316  1377 V AudioSystem: ioConfigChanged() opening already existing output! 4
,08-29 15:11:56.697  3379  3396 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 15:11:56.697  1034  1598 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 15:11:56.697  1034  1598 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 15:11:56.697  1034  1598 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 15:11:56.697  1034  1598 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 15:11:56.697  3379  3394 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
,08-29 15:11:56.697  3379  3394 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 15:11:56.697  7702  7972 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 15:11:56.697  7702  7972 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-29 15:11:56.697  7702  7972 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 15:11:56.697  7702  7972 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-29 15:11:56.698  7702  7702 V ToneGenerator: Create Track: 0xb4928a80
08-29 15:11:56.698  7702  7702 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-29 15:11:56.698  7702  7702 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-29 15:11:56.698   316  1381 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-29 15:11:56.698   316  1381 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-29 15:11:56.698   316  1381 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 15:11:56.698   316  1381 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 15:11:56.698  1836  4429 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 15:11:56.698  1836  4429 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 15:11:56.698  1836  4429 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 15:11:56.698  1836  4429 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 15:11:56.698   316  2153 I AudioFlinger: isAudioPlaybackHookOn() false
08-29 15:11:56.698  1587  1606 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 15:11:56.698  1587  1606 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 15:11:56.698  1587  1606 V AudioSystem: ioConfigChanged() opening already existing output! 4
,08-29 15:11:56.698   316  1382 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-29 15:11:56.698   316  1382 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-29 15:11:56.698   316  1382 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 15:11:56.698   316  1382 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 15:11:56.699  7702  7702 V AudioSystem: getLatency() output 2, latency 50
08-29 15:11:56.699  7702  7702 V AudioSystem: getFrameCount() output 2, frameCount 960
,08-29 15:11:56.699  7702  7702 V AudioTrack: createTrack_l() output 2 afLatency 50
08-29 15:11:56.699   316  2154 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-29 15:11:56.699   316  2154 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-29 15:11:56.699   316  2154 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-29 15:11:56.699   316  2154 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-29 15:11:56.699   316  2154 V AudioFlinger: createTrack() lSessionId: 23
,08-29 15:11:56.700  7702  7702 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-29 15:11:56.700   316  2154 V AudioFlinger: acquiring 23 from 7702, for 7702
08-29 15:11:56.700   316  2154 V AudioFlinger:  added new entry for 23
08-29 15:11:56.700  7702  7702 V ToneGenerator: ToneGenerator INIT OK, time: 136966
08-29 15:11:56.700  7702  7702 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14184983
08-29 15:11:56.702  7702  7977 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
,08-29 15:11:56.702  7702  7977 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 15:11:56.702  7702  7977 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 15:11:56.702  7702  7977 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
,08-29 15:11:56.703  7702  7702 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14184983
08-29 15:11:56.703   316   316 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7702
08-29 15:11:56.703   316   316 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-29 15:11:56.703   316   316 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-29 15:11:56.703   316   316 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-29 15:11:56.703   316   316 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-29 15:11:56.703   316   316 V voice   : voice_set_parameters: exit with code(0)
08-29 15:11:56.704   316   316 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-29 15:11:56.704   316   316 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-29 15:11:56.704   316   316 V msm8974_platform: platform_set_parameters: exit with code(0)
08-29 15:11:56.704   316   316 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-29 15:11:56.704   316   316 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-29 15:11:56.704   316   316 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-29 15:11:56.705  7702  7977 V ToneGenerator: ToneGenerator destructor
08-29 15:11:56.705  7702  7977 V ToneGenerator: stopTone
08-29 15:11:56.705  7702  7977 V ToneGenerator: Delete Track: 0xb4928a80
08-29 15:11:56.705  7702  7977 V AudioTrack: ~AudioTrack, releasing session id from 7702 on behalf of 7702
08-29 15:11:56.706   316  1381 V AudioFlinger: releasing 23 from 7702 for 7702
08-29 15:11:56.706   316  1381 V AudioFlinger:  decremented refcount to 0
08-29 15:11:56.706   316  1381 V AudioFlinger: purging stale effects
08-29 15:11:56.706   316  1381 V AudioPolicyService: AudioCommandThread() adding release output 2
08-29 15:11:56.706   316  1381 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-29 15:11:56.706   316  1381 V AudioFlinger: PlaybackThread::Track destructor
08-29 15:11:56.706   316  1381 V AudioFlinger: removeClient_l() pid 7702, calling pid 316
08-29 15:11:56.706   316  1270 V AudioPolicyService: AudioCommandThread() waking up
08-29 15:11:56.706   316  1270 V AudioPolicyService: AudioCommandThread() processing release output 2
08-29 15:11:56.707   316  1270 V AudioPolicyManager: releaseOutput() 2
08-29 15:11:56.707   316  1270 V AudioPolicyService: AudioCommandThread() going to sleep
08-29 15:11:56.707  7702  7702 D A2dpService: Received start request. Starting profile...
08-29 15:11:56.707  1034  2032 W Process : Unable to open /proc/7978/status
08-29 15:11:56.707  7702  7702 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 15:11:56.708  7702  7702 V Avrcp   : make
08-29 15:11:56.709  7702  7702 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-29 15:11:56.709  7702  7702 I bluedroid-qcom: get_profile_interface avrcp
08-29 15:11:56.720  7702  7702 V AudioManager: registerRemoteController: size of Media player list: 0
,08-29 15:11:56.722  7702  7702 E AudioManager: No RCC entry present to update
,08-29 15:11:56.722  7702  7702 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-29 15:11:56.727  7702  7702 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-29 15:11:56.728  7702  7702 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-29 15:11:56.728  7702  7702 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-29 15:11:56.733  7702  7702 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-29 15:11:56.868  1034  1991 V SIM_STK : Menu title from STK is T-Mobile
,08-29 15:11:56.868  1034  1991 V SIM_STK : Menu title from STK is T-Mobile
,08-29 15:11:56.990  1034  2032 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-29 15:11:56.997  7702  7702 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-29 15:11:57.002  7702  7702 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-29 15:11:57.003  7702  7702 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-29 15:11:57.003  7702  7702 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-29 15:11:57.003  7702  7702 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-29 15:11:57.003  7702  7702 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
,08-29 15:11:57.003  7702  7702 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-29 15:11:57.003  7702  7702 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-29 15:11:57.003  7702  7702 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-29 15:11:57.003  7702  7702 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 15:11:57.004  7702  7702 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-29 15:11:57.005  7702  7702 I BluetoothA2dpServiceJni: classInitNative
08-29 15:11:57.005  7702  7702 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-29 15:11:57.005  7702  7702 D A2dpStateMachine: make
08-29 15:11:57.009  7702  7702 I bluedroid-qcom: get_profile_interface a2dp
08-29 15:11:57.009  7702  7986 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-29 15:11:57.015  7702  7702 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-29 15:11:57.015  7702  7702 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
,08-29 15:11:57.018  7702  7702 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14184983
08-29 15:11:57.018  7702  7985 D A2dpStateMachine: Enter Disconnected: -2
08-29 15:11:57.020  7702  7702 I BluetoothHidServiceJni: classInitNative: succeeds
,08-29 15:11:57.024  7702  7702 D HidService: Received start request. Starting profile...
08-29 15:11:57.024  7702  7702 I bluedroid-qcom: get_profile_interface hidhost
08-29 15:11:57.025  7702  7702 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14184983
08-29 15:11:57.025  7702  7702 I BluetoothHealthServiceJni: classInitNative: succeeds
08-29 15:11:57.027  7702  7702 D HealthService: Received start request. Starting profile...
08-29 15:11:57.030  7702  7702 I bluedroid-qcom: get_profile_interface health
08-29 15:11:57.030  7702  7702 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-29 15:11:57.030  7702  7702 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14184983
08-29 15:11:57.031  7702  7702 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-29 15:11:57.033  7702  7702 D PanService: Received start request. Starting profile...
08-29 15:11:57.033  7702  7702 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 15:11:57.033  7702  7702 I bluedroid-qcom: get_profile_interface pan
,08-29 15:11:57.044  7702  7702 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-29 15:11:57.044  7702  7702 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14184983
,08-29 15:11:57.045  7702  7702 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-29 15:11:57.051  7702  7702 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 15:11:57.052  7702  7702 D BtGatt.GattService: Received start request. Starting profile...
08-29 15:11:57.052  7702  7702 D BtGatt.GattService: start()
08-29 15:11:57.052  7702  7702 I bluedroid-qcom: get_profile_interface gatt
08-29 15:11:57.052  7702  7702 D BtGatt.AdvertiseManager: advertise manager created
08-29 15:11:57.059  7702  7702 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14184983
08-29 15:11:57.061  7702  7702 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14184983
08-29 15:11:57.062  7702  7702 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
,08-29 15:11:57.063  7702  7702 V BluetoothMapService: BluetoothMapBinder()
08-29 15:11:57.064  7702  7702 D BluetoothMapService: Received start request. Starting profile...
08-29 15:11:57.064  7702  7702 D BluetoothMapService: start()
08-29 15:11:57.068  7702  7702 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-29 15:11:57.068  7702  7702 D BluetoothMapEmailAppObserver: createReceiver()
08-29 15:11:57.069  7702  7702 D BluetoothMapEmailAppObserver: initObservers()
08-29 15:11:57.069  7702  7702 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-29 15:11:57.079  7702  7702 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14184983
08-29 15:11:57.080  7702  7702 D HeadsetStateMachine: Proxy object connected
,08-29 15:11:57.081  7702  7702 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-29 15:11:57.081  7702  7702 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-29 15:11:57.086  7702  7702 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-29 15:11:57.087  7702  7977 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-29 15:11:57.087  7702  7977 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 15:11:57.088  7702  7977 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-29 15:11:57.090  7702  7702 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 15:11:57.095  7702  7702 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-29 15:11:57.100  7702  7702 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 15:11:57.104  7702  7702 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 15:11:57.104  7702  7702 V PanService: [BTUI] SIM Extra State :ABSENT
08-29 15:11:57.108  7702  7702 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-29 15:11:57.112  7702  7702 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-29 15:11:57.112  7702  7702 V BluetoothMapService: Handler(): got msg=1
08-29 15:11:57.113  7702  7702 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 15:11:57.113  7702  7702 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 15:11:57.113  7702  7702 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 15:11:57.113  7702  7953 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-29 15:11:57.113  7702  7702 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 15:11:57.113  7702  7953 I bluedroid-qcom: enable
08-29 15:11:57.113  7702  7702 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-29 15:11:57.114  7702  7953 I bt_hci_bdroid: init
08-29 15:11:57.114  7702  7993 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-29 15:11:57.114  7702  7993 I bt-btu  : btu_task pending for preload complete event
08-29 15:11:57.120  7702  7953 I bt_vendor: bt-vendor : init
08-29 15:11:57.120  7702  7953 I bt_vendor: bt-vendor : get_bt_soc_type
08-29 15:11:57.120  7702  7953 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-29 15:11:57.120  7702  7953 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-29 15:11:57.120  7702  7953 D bt_userial_mct: userial_init
08-29 15:11:57.121  7702  7953 D bt_hci_bdroid: set_power 1
08-29 15:11:57.121  7702  7953 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-29 15:11:57.121  7702  7953 I bt_vendor: Starting hciattach daemon
08-29 15:11:57.121  7702  7953 I bt_vendor: try to set true
,08-29 15:11:57.114  7996  7996 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 15:11:57.114  7996  7996 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 15:11:57.171  7997  7997 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-29 15:11:57.305  8003  8003 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-29 15:11:57.320  8004  8004 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-29 15:11:57.359  8006  8006 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-29 15:11:57.385  8007  8007 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-29 15:11:57.410  8008  8008 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-29 15:11:57.443  8012  8012 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-29 15:11:57.472  8014  8014 I libmdmdetect: ESOC framework not supported
08-29 15:11:57.473  8014  8014 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-29 15:11:57.484  8014  8014 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-29 15:11:57.484  8014  8014 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-29 15:11:57.484  8014  8014 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-29 15:11:57.484  8014  8014 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-29 15:11:57.484  8014  8014 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-29 15:11:57.484  8014  8014 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-29 15:11:57.484  8014  8014 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-29 15:11:57.517  8014  8018 E QC-QMI  : qmi_client [8014] 15: failed to locate client data
,08-29 15:11:57.520   469   469 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,08-29 15:11:57.520   469   469 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
08-29 15:11:57.547  8019  8019 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-29 15:11:57.564  8020  8020 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-29 15:11:57.581  7702  7953 I bt_vendor: bluetooth satus is on
08-29 15:11:57.581  7702  7953 D bt_hci_bdroid: preload
,08-29 15:11:57.584  7702  7995 D bt_userial_mct: userial_open(port:0)
08-29 15:11:57.584  7702  7995 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-29 15:11:57.588  7702  7995 I bt_vendor: Done intiailizing UART
08-29 15:11:57.589  7702  7995 I bt_vendor: Done intiailizing UART
08-29 15:11:57.589  7702  7995 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-29 15:11:57.589  7702  7995 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-29 15:11:57.589  7702  7993 I bt-btu  : btu_task received preload complete event
08-29 15:11:57.589  7702  7993 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-29 15:11:57.590  7702  7993 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-29 15:11:57.592  7702  7993 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-29 15:11:57.593  7702  8022 D bt_userial_mct: Entering userial_read_thread()
,08-29 15:11:57.599  7702  7993 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 15:11:57.599  7702  7993 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-29 15:11:57.599  7702  7993 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-29 15:11:57.599  7702  7993 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 15:11:57.599  7702  7993 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 15:11:57.599  7702  7993 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 15:11:57.599  7702  7993 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 15:11:57.599  7702  7993 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 15:11:57.599  7702  7993 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-29 15:11:57.599  7702  7993 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 15:11:57.599  7702  7993 I         : BTE_InitTraceLevels -- TRC_PAN
,08-29 15:11:57.599  7702  7993 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 15:11:57.599  7702  7993 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 15:11:57.599  7702  7993 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 15:11:57.599  7702  7993 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 15:11:57.599  7702  7993 I         : BTE_InitTraceLevels -- TRC_BTIF
08-29 15:11:57.658  7702  7993 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-29 15:11:57.658  7702  7993 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa017c061 
08-29 15:11:57.658  7702  7993 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa017c061 
,08-29 15:11:57.685  7702  7957 E bt-btif : Calling BTA_HhEnable
08-29 15:11:57.685  7702  7957 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-29 15:11:57.686  7702  7957 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-29 15:11:57.690  7702  7993 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
,08-29 15:11:57.690  7702  7993 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
,08-29 15:11:57.690  7702  7993 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-29 15:11:57.691  7702  7993 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
,08-29 15:11:57.691  7702  7993 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-29 15:11:57.693  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-29 15:11:57.693  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-29 15:11:57.695  7702  7957 D BluetoothAdapterProperties: Name is: G3
08-29 15:11:57.696  7702  7957 D BluetoothAdapterProperties: Scan Mode:20
08-29 15:11:57.697  7702  7957 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 15:11:57.697  7702  7957 D bt_hci_bdroid: postload
08-29 15:11:57.697  7702  7995 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 15:11:57.698  7702  7995 D bt_hci_bdroid: Used up Tx Cmd credits
,08-29 15:11:57.704  7702  7995 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 15:11:57.706  7702  7993 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-29 15:11:57.707  7702  7957 D bte_conf: Device ID record 1 : primary
08-29 15:11:57.707  7702  7957 D bte_conf:   vendorId            = 00c4
08-29 15:11:57.707  7702  7957 D bte_conf:   vendorIdSource      = 0001
08-29 15:11:57.707  7702  7957 D bte_conf:   product             = 13a1
08-29 15:11:57.707  7702  7957 D bte_conf:   version             = 1000
08-29 15:11:57.707  7702  7957 D bte_conf:   clientExecutableURL = 
08-29 15:11:57.707  7702  7957 D bte_conf:   serviceDescription  = 
08-29 15:11:57.707  7702  7957 D bte_conf:   documentationURL    = 
08-29 15:11:57.707  7702  7957 D bte_conf: bte_load_did_conf no section named DID2.
08-29 15:11:57.711  7702  7953 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-29 15:11:57.711  7702  7953 D BluetoothAdapterProperties: ScanMode =  20
08-29 15:11:57.711  7702  7953 D BluetoothAdapterProperties: State =  11
08-29 15:11:57.711  7702  7953 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-29 15:11:57.712  7702  7953 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-29 15:11:57.712  7702  7953 D BluetoothAdapterProperties: Setting state to 12
08-29 15:11:57.712  7702  7953 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 15:11:57.712  7702  7957 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-29 15:11:57.704  8024  8024 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-29 15:11:57.719  7702  7953 I BluetoothAdapterState: Entering On State
08-29 15:11:57.704  8024  8024 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 15:11:57.728  7702  8022 E bt_mct  : hci lib postload completed
,08-29 15:11:57.734  7702  7953 D LGBluetoothServiceAdapter: [BTUI] OnState
08-29 15:11:57.734  7702  7953 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-29 15:11:57.734  7702  7953 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-29 15:11:57.735  7702  7993 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 15:11:57.735  7702  7993 W bt-smp  : Plain text(LSB ~ MSB) = d2 43 42 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 15:11:57.736  7702  7993 W bt-smp  : Encrypted text(LSB ~ MSB) = fe b7 04 ab d9 05 ee 75 c3 56 08 d1 cb 75 54 ca 
08-29 15:11:57.736  7702  7993 W bt-btm  : Stopping oneshot timer
08-29 15:11:57.736  7702  7953 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-29 15:11:57.736  1034  1116 D BluetoothManagerService: Message: 60
08-29 15:11:57.737  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-29 15:11:57.737  1034  1116 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-29 15:11:57.737  1836  4430 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 15:11:57.738  7702  7957 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-29 15:11:57.764  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:11:57.764  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:57.764  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 15:11:57.764  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 15:11:57.764  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:11:57.764  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:11:57.764  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:11:57.764  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 15:11:57.769  7702  7953 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-29 15:11:57.769  7702  7993 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 15:11:57.769  7702  7993 W bt-smp  : Plain text(LSB ~ MSB) = 70 f8 6f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 15:11:57.769  7702  7993 W bt-smp  : Encrypted text(LSB ~ MSB) = 1a 8f e1 c2 6c a1 2a f6 73 51 a2 bf db 30 6b a4 
08-29 15:11:57.770  7702  7993 W bt-btm  : Stopping oneshot timer
08-29 15:11:57.776  6671  6671 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 15:11:57.782  7702  7993 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 15:11:57.782  7702  7993 W bt-smp  : Plain text(LSB ~ MSB) = 0d 32 5c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 15:11:57.782  7702  7993 W bt-smp  : Encrypted text(LSB ~ MSB) = a6 2f 9c 20 f9 2f 74 ce 31 93 28 f3 b0 ef 51 a0 
,08-29 15:11:57.785  7702  7993 W bt-btm  : Stopping oneshot timer
08-29 15:11:57.796  1836  1836 D BluetoothHeadset: Proxy object connected
,08-29 15:11:57.825  7702  7993 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 15:11:57.825  7702  7993 W bt-smp  : Plain text(LSB ~ MSB) = 68 a8 79 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 15:11:57.825  7702  7993 W bt-smp  : Encrypted text(LSB ~ MSB) = de 29 4a 83 07 dd a0 16 6c 64 4b ce 0e a2 3d 74 
08-29 15:11:57.825  7702  7993 W bt-btm  : Stopping oneshot timer
,08-29 15:11:57.828  6892  7621 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 15:11:57.837  8029  8029 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-29 15:11:57.853  6892  6892 D BluetoothHeadset: Proxy object connected
08-29 15:11:57.853  6892  6892 D HeadsetProfile: Bluetooth service connected
08-29 15:11:57.854  1034  1116 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 15:11:57.858  1034  1034 D BluetoothA2dp: Proxy object connected
08-29 15:11:57.858  6892  6908 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 15:11:57.859  7702  7993 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 15:11:57.859  7702  7993 W bt-smp  : Plain text(LSB ~ MSB) = b6 df 70 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 15:11:57.859  7702  7993 W bt-smp  : Encrypted text(LSB ~ MSB) = b7 76 d7 0d fe fd 35 ca 5a d3 bf bb d6 9f 2d 2e 
08-29 15:11:57.859  7702  7993 W bt-btm  : Stopping oneshot timer
08-29 15:11:57.864  6892  6892 D BluetoothA2dp: Proxy object connected
08-29 15:11:57.864  6892  6892 D A2dpProfile: Bluetooth service connected
08-29 15:11:57.865  1034  1116 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 15:11:57.866  1034  1034 D BluetoothHeadset: Proxy object connected
08-29 15:11:57.870  6892  6909 D BluetoothMap: onBluetoothStateChange: up=true
08-29 15:11:57.873  6892  7621 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 15:11:57.875  6892  6892 D BluetoothMap: Proxy object connected
08-29 15:11:57.875  6892  6892 D MapProfile: Bluetooth service connected
08-29 15:11:57.875  6892  6892 D BluetoothMap: getConnectedDevices()
08-29 15:11:57.876  6892  6909 D BluetoothPan: onBluetoothStateChange on: true
08-29 15:11:57.876  7702  7972 V BluetoothMapService: getConnectedDevices()
08-29 15:11:57.876  6892  6909 D BluetoothPan: onBluetoothStateChange call bindService
08-29 15:11:57.879  6892  6908 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-29 15:11:57.881  6892  6892 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 15:11:57.881  6892  6892 D PanProfile: Bluetooth service connected
08-29 15:11:57.885  1836  2416 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 15:11:57.886  6892  6892 D BluetoothInputDevice: Proxy object connected
08-29 15:11:57.886  6892  6892 D HidProfile: Bluetooth service connected
08-29 15:11:57.887  1836  1851 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 15:11:57.888  1836  1836 D BluetoothHeadset: Proxy object connected
,08-29 15:11:57.928  7702  7957 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 15:11:57.929  7702  7957 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-29 15:11:57.996  1034  1116 I art     : Explicit concurrent mark sweep GC freed 26695(1319KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.528ms total 106.112ms
08-29 15:11:57.996  1836  1836 D BluetoothHeadset: Proxy object connected
,08-29 15:11:57.998  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-29 15:11:57.998  1034  1116 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-29 15:11:57.998  1034  1116 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-29 15:11:57.999  1034  1116 D BluetoothManagerService: Message: 40
08-29 15:11:57.999  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-29 15:11:58.001  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 15:11:58.001  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 15:11:58.002  1925  2110 D LGBluetoothAPIService: Message: 1
08-29 15:11:58.002  1925  2110 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-29 15:11:58.002  1925  2110 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-29 15:11:58.002  1925  2110 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-29 15:11:58.011  7702  7702 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 15:11:58.011  7702  7702 D BluetoothMapService: STATE_ON
08-29 15:11:58.013  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:11:58.018  6892  6892 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-29 15:11:58.020  7702  7702 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14184983
08-29 15:11:58.021  7702  7702 V BluetoothPbapService: Pbap Service onCreate
08-29 15:11:58.021  7702  7702 V BluetoothPbapService: Starting PBAP service
08-29 15:11:58.022  7702  7702 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-29 15:11:58.022  7702  7702 V BluetoothMapService: Handler(): got msg=1
08-29 15:11:58.022  7702  7702 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-29 15:11:58.023  7702  7702 V BluetoothPbapService: Pbap Service onBind
08-29 15:11:58.023  6892  6892 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-29 15:11:58.024  7702  7702 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 15:11:58.024  7702  7702 V BluetoothPbapService: state: 12
08-29 15:11:58.024  7702  7702 V BluetoothPbapService: Handler(): got msg=1
08-29 15:11:58.025  7702  8049 D BluetoothMapMasInstance: MAS initSocket()
,08-29 15:11:58.025  7702  8049 D BluetoothMapMasInstance:   masId = 00
08-29 15:11:58.025  7702  8049 D BluetoothMapMasInstance:   msgTypes = 0e
08-29 15:11:58.025  7702  8049 D BluetoothMapMasInstance:   masName = SMS/MMS
08-29 15:11:58.025  7702  8049 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-29 15:11:58.026  7702  7702 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-29 15:11:58.027  1034  1991 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 15:11:58.029  7702  7702 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 15:11:58.029  7702  7702 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 15:11:58.029  7702  7702 V BluetoothPbapReceiver: ***********state = 12
08-29 15:11:58.029  6892  6892 D BluetoothPbap: Proxy object connected
08-29 15:11:58.029  6892  6892 D PbapServerProfile: Bluetooth service connected
08-29 15:11:58.029  7702  8050 V BluetoothPbapService: Pbap Service initSocket
08-29 15:11:58.030  1034  1560 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 15:11:58.032  7702  8049 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 15:11:58.034  7702  8050 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 15:11:58.036  2198  2198 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 15:11:58.037  6892  6892 D DockEventReceiver: finishStartingService: stopping service
,08-29 15:11:58.037  2198  2198 D c       : Getting all permits...
08-29 15:11:58.037  2198  2198 D a       : Opening database...
08-29 15:11:58.041  2198  2198 D a       : Opening database auth.proximity.permit_store...
08-29 15:11:58.041  7702  7957 D BluetoothAdapterProperties: Scan Mode:21
08-29 15:11:58.041  7702  7957 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-29 15:11:58.042  7702  8050 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-29 15:11:58.042  2198  2198 D a       : Closing database...
08-29 15:11:58.044  7702  8049 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-29 15:11:58.045  7702  8049 V BluetoothMapMasInstance: Succeed to create listening socket 
08-29 15:11:58.045  7702  8049 D BluetoothMapMasInstance: Accepting socket connection...
08-29 15:11:58.045  7702  8050 V BluetoothPbapService: Succeed to create listening socket 
08-29 15:11:58.045  7702  8050 V BluetoothPbapService: Accepting socket connection...
08-29 15:11:58.045  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:58.052  6892  6892 D BluetoothPermissionRequest: onReceive
,08-29 15:11:58.054  6892  6892 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-29 15:11:58.055  6892  6892 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 15:11:58.059  7702  7702 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-29 15:11:58.061  7702  7702 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-29 15:11:58.067  7702  7702 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-29 15:11:58.077  7702  7702 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-29 15:11:58.077  7702  7702 V BtOppService: onCreate
,08-29 15:11:58.080  7702  7702 V BluetoothOppNotification: send message
,08-29 15:11:58.082  7702  7702 V BtOppService: Starting RfcommListener
08-29 15:11:58.086  7702  7702 D BluetoothOppPreference: Dumping Names:  
08-29 15:11:58.086  7702  7702 D BluetoothOppPreference: {}
08-29 15:11:58.086  7702  7702 D BluetoothOppPreference: Dumping Channels:  
08-29 15:11:58.086  7702  7702 D BluetoothOppPreference: {}
08-29 15:11:58.087  7702  7702 V BtOppService: onStartCommand
08-29 15:11:58.089  7702  7702 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 15:11:58.089  7702  7702 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-29 15:11:58.091  7702  7702 V BluetoothOppNotification: new notify threadi!
08-29 15:11:58.091  7702  7702 V BluetoothOppNotification: send delay message
08-29 15:11:58.091  7702  8057 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-29 15:11:58.092  7702  7702 V BtOppService: start RfcommListener
08-29 15:11:58.092  7702  8054 V BtOppService: Deleted complete outbound shares, number =  0
,08-29 15:11:58.093  7702  7702 V BtOppService: RfcommListener started
08-29 15:11:58.095  7702  8059 V BtOppRfcommListener: Starting RFCOMM listener....
08-29 15:11:58.095  7702  8054 V BtOppService: Deleted complete inbound failed shares, number = 0
08-29 15:11:58.096  7702  8054 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-29 15:11:58.097  1034  1929 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 15:11:58.097  7702  8054 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2e1debaf on behalf of 
08-29 15:11:58.098  7702  8059 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 15:11:58.098  7702  8057 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-29 15:11:58.099  7702  8059 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-29 15:11:58.100  7702  8057 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@38e6dbbc on behalf of 
08-29 15:11:58.100  7702  8058 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-29 15:11:58.101  7702  8059 V BtOppRfcommListener: Started RFCOMM listener....
08-29 15:11:58.101  7702  8059 I BtOppRfcommListener: Accept thread started.
08-29 15:11:58.101  7702  8059 V BtOppRfcommListener: Accepting connection...
08-29 15:11:58.101  7702  8058 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@a70745 on behalf of 
08-29 15:11:58.102  7702  8058 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-29 15:11:58.102  7702  7702 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14184983
08-29 15:11:58.102  7702  7702 V BluetoothFtpService: Ftp Service onCreate
08-29 15:11:58.102  7702  7702 I BluetoothFtpService: Ftp Service onCreate
08-29 15:11:58.102  7702  7702 V BluetoothFtpService: Ftp Service onStartCommand
08-29 15:11:58.102  7702  7702 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 15:11:58.102  7702  7702 V BluetoothFtpService: Starting Listening on sockets
08-29 15:11:58.103  7702  7702 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 15:11:58.103  7702  7702 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 15:11:58.103  7702  7702 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 15:11:58.103  7702  7702 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 15:11:58.103  7702  7702 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-29 15:11:58.103  7702  7702 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-29 15:11:58.104  7702  8057 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-29 15:11:58.104  7702  8058 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-29 15:11:58.105  7702  8058 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@366793cb on behalf of 
08-29 15:11:58.105  7702  7702 V BtOppService: ContentObserver received notification
08-29 15:11:58.106  7702  8058 V BluetoothOppNotification: outbound: succ-0  fail-0
08-29 15:11:58.106  7702  7702 V BtOppService: ContentObserver received notification
08-29 15:11:58.106  7702  7702 V BluetoothFtpService: Handler(): got msg=1
08-29 15:11:58.106  7702  8060 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is tr,ue
08-29 15:11:58.106  7702  8060 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-29 15:11:58.106  7702  7702 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-29 15:11:58.107  7702  7702 V BluetoothFtpService: Ftp Service initSocket
08-29 15:11:58.107  7702  8060 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1323f7a8 on behalf of 
,08-29 15:11:58.110  7702  8060 V BluetoothOppNotification: update too frequent, put in queue
08-29 15:11:58.111  7702  8060 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-29 15:11:58.112  7702  8058 V BluetoothOppNotification: outbound notification was removed.
08-29 15:11:58.112  7702  8058 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-29 15:11:58.113  7702  8058 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@fb5d2c1 on behalf of 
08-29 15:11:58.113  1034  2032 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 15:11:58.114  7702  7702 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 15:11:58.114  7702  8058 V BluetoothOppNotification: inbound: succ-0  fail-0
08-29 15:11:58.116  7702  8058 V BluetoothOppNotification: inbound notification was removed.
08-29 15:11:58.116  7702  8058 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-29 15:11:58.117  7702  8058 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@18e7ba66 on behalf of 
08-29 15:11:58.119  7702  7702 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-29 15:11:58.119  7702  7702 V BluetoothFtpService: Succeed to create listening socket on channel 20
,08-29 15:11:58.121  7702  8061 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-29 15:11:58.134  7702  7702 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14184983
,08-29 15:11:58.134  7702  7702 V BluetoothSapService: Sap Service onCreate
08-29 15:11:58.136  7702  7702 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 15:11:58.136  7702  7702 V BluetoothSapService: state: 12
08-29 15:11:58.136  7702  7702 V BluetoothSapService: Starting SAP server process
08-29 15:11:58.138  7702  7702 V BluetoothSapService: SAP Service startRfcommListenerThread
08-29 15:11:58.124  8062  8062 W sapd    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 15:11:58.124  8062  8062 W sapd    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 15:11:58.140  7702  8063 V BluetoothSapService: Sap Service initRfcommSocket
08-29 15:11:58.142  1034  1758 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 15:11:58.142  7702  8063 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 15:11:58.144  7702  8063 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-29 15:11:58.144  7702  8063 V BluetoothSapService: Succeed to create listening socket 
08-29 15:11:58.144  7702  8063 V BluetoothSapService: Accepting socket connection...
08-29 15:11:58.148  8062  8062 V BT_SAP  : Event pipe created
08-29 15:11:58.148  8062  8062 V BT_SAP  : create_server_socket qcom.sap.server
08-29 15:11:58.148  8062  8062 V BT_SAP  : created socket fd 6
,08-29 15:11:58.558  6671  6818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:11:58.558  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:58.558  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 15:11:58.558  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 15:11:58.558  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:11:58.558  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:11:58.558  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:11:58.558  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 15:11:58.573  6671  6818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 15:11:58.576  6671  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 15:11:58.576  6671  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@425b1f4 added. We now have 8 listener(s)
08-29 15:11:58.577  6671  6818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 15:11:58.581  1034  1758 D WifiServiceImplEx: setWifiEnabled: false pid=6671, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-29 15:11:58.581  1034  1758 D WifiService: setWifiEnabled: false pid=6671, uid=10118
08-29 15:11:58.581  1034  1758 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 15:11:58.589  6671  6818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:58.590  1034  1991 D WifiServiceImplEx: setWifiEnabled: true pid=6671, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-29 15:11:58.591  1034  1991 D WifiService: setWifiEnabled: true pid=6671, uid=10118
08-29 15:11:58.591  1034  1991 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 15:11:58.611  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-29 15:11:58.611  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 15:11:58.611  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-29 15:11:58.615  1034  1376 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-29 15:11:58.615  1034  1376 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-29 15:11:58.618  1034  1376 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-29 15:11:58.618  1034  1376 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-29 15:11:58.618  1034  1376 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-29 15:11:58.618  1034  1376 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-29 15:11:58.618  1034  1376 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-29 15:11:58.618  1034  1376 E WifiHW  : unknown target_country: EU , set to default
08-29 15:11:58.618  1034  1376 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-29 15:11:58.618  1034  1376 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-29 15:11:58.618  1034  1376 I WifiUtil: gEnableBmps=1
08-29 15:11:59.095  7702  7702 V BluetoothOppNotification: new notify threadi!
,08-29 15:11:59.101  7702  7702 V BluetoothOppNotification: send delay message
08-29 15:11:59.111  7702  8076 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-29 15:11:59.129  7702  8076 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@25a516f2 on behalf of 
08-29 15:11:59.129  7702  8076 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-29 15:11:59.133  7702  8076 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-29 15:11:59.135  7702  8076 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@574b143 on behalf of 
08-29 15:11:59.136  7702  8076 V BluetoothOppNotification: outbound: succ-0  fail-0
08-29 15:11:59.138  7702  8076 V BluetoothOppNotification: outbound notification was removed.
08-29 15:11:59.138  7702  8076 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-29 15:11:59.140  7702  8076 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3d8413c0 on behalf of 
08-29 15:11:59.140  7702  8076 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-29 15:11:59.144  7702  8076 V BluetoothOppNotification: inbound notification was removed.
,08-29 15:11:59.144  7702  8076 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-29 15:11:59.146  7702  8076 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@35c118f9 on behalf of 
08-29 15:11:59.311   310   892 D SoftapController: Softap fwReload - Ok
,08-29 15:11:59.318  1034  1376 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (695ms)
08-29 15:11:59.325   310   892 D CommandListener: Setting iface cfg
08-29 15:11:59.325   310   892 D CommandListener: Trying to bring down wlan0
08-29 15:11:59.327   310   892 D CommandListener: Clearing all IP addresses on wlan0
,08-29 15:11:59.356  1034  1116 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-29 15:11:59.358  1034  1376 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-29 15:11:59.354  8084  8084 W wpa_supplicant: type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-29 15:11:59.354  8084  8084 W wpa_supplicant: type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 15:11:59.384  1034  1376 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 15:11:59.384  1034  1376 E WifiStateMachine: useWiFiOffloading() : false
08-29 15:11:59.384  1034  1376 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-29 15:11:59.396  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,08-29 15:11:59.404  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 15:11:59.414  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,08-29 15:11:59.425  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:11:59.426  1034  1376 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-29 15:11:59.426  1034  1376 D WifiMonitor: connecting to supplicant
,08-29 15:11:59.440  8084  8084 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-29 15:11:59.475  6892  6892 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 15:11:59.475  6892  6892 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 15:11:59.475  6892  6892 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 15:11:59.476  6892  6892 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 15:11:59.479  6892  6892 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 15:11:59.481  6892  6892 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 15:11:59.481  6892  6892 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-29 15:11:59.481  6892  6892 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 15:11:59.481  6892  6892 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
,08-29 15:11:59.481  6892  6892 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 15:11:59.482  6892  6892 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-29 15:11:59.483  6892  6892 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 15:11:59.507  8084  8084 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-29 15:11:59.508  8084  8084 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-29 15:11:59.511  1034  1116 D Tethering: InitialState.processMessage what=4
08-29 15:11:59.544  1034  1758 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8101 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-29 15:11:59.548  1034  1116 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-29 15:11:59.562   348   348 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 4.506ms total 25.722ms
,08-29 15:11:59.583   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 408us total 18.931ms
,08-29 15:11:59.604  7810  7821 E UEI.SmartControl: file observer is disposed!
08-29 15:11:59.605  8084  8084 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-29 15:11:59.605   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 423us total 21.188ms
,08-29 15:11:59.669  1034  2034 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8123 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-29 15:11:59.674  8101  8121 W FormManager: Network not available. Please check & try again.
08-29 15:11:59.678  8101  8122 V FormManager: Network unavailable.
08-29 15:11:59.680  8101  8122 V FormManager: Network unavailable.
08-29 15:11:59.680  8084  8084 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-29 15:11:59.690  1034  1758 I ActivityManager: Killing 7193:com.android.chrome/u0a57 (adj 15): empty #17
,08-29 15:11:59.704  8084  8084 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
,08-29 15:11:59.704  8084  8084 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,08-29 15:11:59.707  1034  8142 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-29 15:11:59.707  1034  8142 D WifiMonitor: Dropping event because (p2p0) is stopped
08-29 15:11:59.707  1034  8142 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-29 15:11:59.707  1034  8142 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-29 15:11:59.707  1034  8142 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-29 15:11:59.707  1034  8142 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-29 15:11:59.708  1034  1376 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-29 15:11:59.708  1034  1376 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-29 15:11:59.709  1034  1376 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-29 15:11:59.709  1034  1376 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-29 15:11:59.710  1034  1376 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-29 15:11:59.711  1034  1376 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 15:11:59.711  1034  1376 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-29 15:11:59.712  1034  1376 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 15:11:59.712  1034  1376 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-29 15:11:59.713  1034  1376 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-29 15:11:59.713  1034  1376 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-29 15:11:59.714  1034  1376 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-29 15:11:59.714  1034  1376 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
,08-29 15:11:59.739  1034  1991 W libprocessgroup: failed to open /acct/uid_10057/pid_7193/cgroup.procs: No such file or directory
08-29 15:11:59.742  1034  1376 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 15:11:59.742  1034  1376 E WifiStateMachine: useWiFiOffloading() : false
08-29 15:11:59.742  1034  1376 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 15:11:59.743  1034  1376 D WifiNative-wlan0: doBoolean: SET update_config 1
08-29 15:11:59.743  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:11:59.743  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:11:59.743  1034  1376 D WifiNative-wlan0: SET update_config 1: returned true
08-29 15:11:59.743  1034  1376 D WifiConfigStore: Loading config and enabling all networks 
08-29 15:11:59.744  1034  1376 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-29 15:11:59.744  1925  1925 D WfdService: Waiting for WifiP2p enabling
08-29 15:11:59.744  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:11:59.744  1034  1376 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-29 15:11:59.744  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:11:59.744  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 15:11:59.745  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 15:11:59.749  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-29 15:11:59.753  1034  1424 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-29 15:11:59.755  1034  1376 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-29 15:11:59.757  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:11:59.757  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:11:59.757  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 15:11:59.757  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:11:59.757  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:11:59.757  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:11:59.757  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:11:59.757  6671  6671 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 15:11:59.761  6671  6671 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 15:11:59.768  1034  1376 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-29 15:11:59.769  1034  1376 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-29 15:11:59.769  1034  1376 D WifiStateMachine: enableVerboseLogging : level 2
08-29 15:11:59.770  1034  1376 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-29 15:11:59.770  1034  1376 D WifiNative-wlan0: SET device_name g3_global_com: returned true
,08-29 15:11:59.770  1034  1376 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-29 15:11:59.770  1034  1376 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-29 15:11:59.771  1034  1376 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-29 15:11:59.771  1034  1376 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-29 15:11:59.771  1034  1376 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-29 15:11:59.772  1034  1376 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-29 15:11:59.772  1034  1376 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-29 15:11:59.772  1034  1376 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-29 15:11:59.772  1034  1376 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-29 15:11:59.773  1034  1376 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-29 15:11:59.773  1034  1376 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-29 15:11:59.774  1034  1376 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-29 15:11:59.774  1034  1376 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 15:11:59.774  1034  1376 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-29 15:11:59.775  1034  1376 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-29 15:11:59.775  1034  1376 D WifiNative-HAL: Setting external_sim to 1
,08-29 15:11:59.775  1034  1376 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-29 15:11:59.776  1034  1376 D WifiNative-wlan0: SET external_sim 1: returned true
08-29 15:11:59.776  1034  1376 I WifiNative-HAL: startHal
08-29 15:11:59.776  1034  1376 D wifi    : setting scan oui 0xaf6d4540
08-29 15:11:59.776  1034  1376 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 15:11:59.776  1034  1376 I WifiNative-HAL: startHal
08-29 15:11:59.776  1034  1376 D wifi    : setting scan oui 0xaf6d4540
08-29 15:11:59.777  1034  1376 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-29 15:11:59.777  1034  1376 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-29 15:11:59.777  1034  1376 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-29 15:11:59.777  1925  1925 D WfdsService: Supplicant Connection state is changed : true
08-29 15:11:59.778  8084  8084 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-29 15:11:59.778  1925  2271 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-29 15:11:59.778  1925  2271 D WfdsService: Set the WFDS Monitor: true
08-29 15:11:59.778  1925  2271 D WfdsMonitor: WfdsMonitorThread create
08-29 15:11:59.778  1925  2271 D WfdsMonitor: WFDS Monitor is created and started
08-29 15:11:59.778  1925  2271 D WfdsService: WiFi: Supplicant connection re-established
08-29 15:11:59.778  1034  1376 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-29 15:11:59.778  7735  7735 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:11:59.779  1034  1376 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-29 15:11:59.779  8084  8084 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-29 15:11:59.779  1925  8143 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-29 15:11:59.779  1034  1376 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-29 15:11:59.779  1034  1376 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-29 15:11:59.779  8084  8084 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-29 15:11:59.780  1925  8143 E CtrlSupplicant: Succeed to open control connection
08-29 15:11:59.780  1925  8143 E CtrlSupplicant: Succeed to open monitor connection
08-29 15:11:59.780  1034  1376 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-29 15:11:59.780  1034  1376 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-29 15:11:59.780  1925  8143 D WfdsMonitor: Supplicant connection established
08-29 15:11:59.780  8084  8084 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-29 15:11:59.781  1034  1376 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-29 15:11:59.781  1034  1376 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-29 15:11:59.781  8084  8084 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-29 15:11:59.781  1925  2271 D WfdsService: Connected to the supplicant for wfds
08-29 15:11:59.781  1034  1376 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-29 15:11:59.781  1034  1376 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-29 15:11:59.781  8084  8084 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-29 15:11:59.782  1034  1376 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-29 15:11:59.782  1034  1376 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-29 15:11:59.782  8084  8084 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-29 15:11:59.782  1034  1376 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-29 15:11:59.783  1034  1376 E WifiNative: : [140,034,457 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-29 15:11:59.783  1034  1376 D WifiNative-wlan0: doBoolean: RECONNECT
08-29 15:11:59.784  1034  1376 D WifiNative-wlan0: RECONNECT: returned true
08-29 15:11:59.784  1034  1376 D WifiNative-wlan0: doString: [STATUS]
08-29 15:11:59.784  103,4  8142 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-29 15:11:59.785  1034  8142 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-29 15:11:59.785  1034  1376 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-29 15:11:59.785  1034  1376 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 15:11:59.786  1034  1376 D WifiNative-wlan0: SET ps 1: returned true
08-29 15:11:59.786  1034  1374 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 15:11:59.786  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 3
08-29 15:11:59.787  1034  1034 D RttService: SCAN_AVAILABLE : 3
08-29 15:11:59.787  1034  1541 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:59.787  1034  1541 I WifiNative-HAL: startHal
08-29 15:11:59.787  1034  1541 D wifi    : getting scan capabilities on interface[1] = 0xaf6d4540
08-29 15:11:59.787  1034  1541 D wifi    : failed to get capabilities : -3
08-29 15:11:59.787  1034  1541 E WifiScanningService: could not get scan capabilities
08-29 15:11:59.787  1034  1376 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-29 15:11:59.787  1034  1542 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:59.787  1034  1376 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-29 15:11:59.788  1034  1376 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-29 15:11:59.788  1034  1376 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-29 15:11:59.789  1034  1376 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-29 15:11:59.789   310   892 D CommandListener: Setting iface cfg
08-29 15:11:59.789   310   892 D CommandListener: Trying to bring up p2p0
08-29 15:11:59.789  1034  1376 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-29 15:11:59.789  1034  1374 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-29 15:11:59.789  1034  1374 D LGWifiP2pService: P2pEnablingState
08-29 15:11:59.790  1034  1374 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:59.790  1034  1376 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-29 15:11:59.790  1034  1374 D LGWifiP2pService: P2p socket connection successful
08-29 15:11:59.790  1034  1376 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-29 15:11:59.790  1034  1374 D LGWifiP2pService: P2pEnabledState
08-29 15:11:59.790  8084  8084 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-29 15:11:59.791  1034  1376 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-29 15:11:59.791  1034  1376 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-29 15:11:59.791  1034  1376 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-29 15:11:59.791  1034  1376 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-29 15:11:59.792  8084  8084 E wpa_supplicant: disconnect_rssi_lvl: -100
08-29 15:11:59.794  1034  1376 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-29 15:11:59.794  1034  1376 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-29 15:11:59.794  1034  1376 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-29 15:11:59.795  1034  1376 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-29 15:11:59.795  8084  8084 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-29 15:11:59.795  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-29 15:11:59.795  1925  1925 D WfdsService: WifiP2pState is changed : true
08-29 15:11:59.796  8084  8084 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 15:11:59.795  1925  2271 D WfdsService: Receive the WFDS_ENABLE Method
08-29 15:11:59.796  1925  2271 D WfdsService: Set the WFDS Monitor: true
08-29 15:11:59.796  1925  2271 D WfdsService: Connected to the supplicant for wfds
08-29 15:11:59.796  1925  2271 D WfdsJNI : doCommand: WFDS_SET TRUE
08-29 15:11:59.796  8084  8084 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-29 15:11:59.797  8084  8084 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-29 15:11:59.797  8084  8084 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 15:11:59.797  1925  2271 D WfdsService: selectPreferredScanChannel [36]
08-29 15:11:59.797  1925  2271 D WfdsService: STATE : Wfd,sEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-29 15:11:59.797  8084  8084 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 15:11:59.798  1034  1374 D LGWifiP2pService: sending p2p connection changed broadcast
08-29 15:11:59.798  1034  1374 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-29 15:11:59.798  1925  8143 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 15:11:59.798  1925  8143 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 15:11:59.798  1034  8142 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 15:11:59.798  1034  8142 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 15:11:59.799  1034  8142 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 15:11:59.799  1034  8142 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 15:11:59.799  1034  8142 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 15:11:59.799  1034  8142 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 15:11:59.799  1034  8142 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 15:11:59.799  1034  8142 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 15:11:59.799  1034  8142 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 15:11:59.799  1034  8142 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 15:11:59.799  1034  8142 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 15:11:59.799  1034  8142 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 15:11:59.799  1034  1376 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-29 15:11:59.799  1925  1925 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-29 15:11:59.800  1925  1925 D WfdsService: isConnected: false
08-29 15:11:59.800  1034  1374 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-29 15:11:59.800  1034  1374 D WifiNative-p2p0: doBoolean: SET device_name G3
08-29 15:11:59.800  1034  1376 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-29 15:11:59.800  1034  1374 D WifiNative-p2p0: SET device_name G3: returned true
08-29 15:11:59.800  1034  1374 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-29 15:11:59.800  1034  1374 D LGWifiP2pService: before postfix = G3
08-29 15:11:59.801  1034  1374 D WifiServerServiceExt: postfix byte check : 2
08-29 15:11:59.801  1034  1374 D LGWifiP2pService: after postfix = G3
08-29 15:11:59.801  1034  1374 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-29 15:11:59.801  1034  1376 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-29 15:11:59.801  1034  1374 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-29 15:11:59.801  1034  1374 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-29 15:11:59.801  1034  1376 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
,08-29 15:11:59.801  1034  1374 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-29 15:11:59.801  1034  1374 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-29 15:11:59.801  1034  1376 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-29 15:11:59.802  1034  1374 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-29 15:11:59.802  1034  1374 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-29 15:11:59.802  1034  1374 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-29 15:11:59.802  1034  1374 D WifiNative-HAL: p2pGetDeviceAddress
08-29 15:11:59.803  1034  1374 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
,08-29 15:11:59.804  1925  1925 I WfdStateTracker: handleP2pThisDeviceChanged
08-29 15:11:59.805  1925  1925 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-29 15:11:59.805  1034  1374 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-29 15:11:59.805  1034  1374 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-29 15:11:59.805  1925  1925 D WfdsService: Update P2p Interface State: 3
08-29 15:11:59.805  1034  1374 D WifiNative-p2p0: P2P_FLUSH: returned true
08-29 15:11:59.805  1034  1374 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-29 15:11:59.806  1034  1374 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-29 15:11:59.806  1034  1374 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-29 15:11:59.806  1034  1374 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-29 15:11:59.806  1034  1374 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-29 15:11:59.814  1034  1374 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-29 15:11:59.814  1034  1374 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-29 15:11:59.814  8084  8084 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-29 15:11:59.814  1034  1374 D LGWifiP2pService: InactiveState
08-29 15:11:59.814  8084  8084 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 15:11:59.814  1034  1374 D LGWifiP2pService: InactiveState{ when=-14ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:59.814  1034  1374 D LGWifiP2pService: P2pEnabledState{ when=-14ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:59.814  1034  1374 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-29 15:11:59.814  1034  8142 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
,08-29 15:11:59.814  1034  8142 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 15:11:59.814  1034  8142 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 15:11:59.814  1034  8142 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 15:11:59.815  1034  1376 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-29 15:11:59.815  1034  1376 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-29 15:11:59.816  1034  1376 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-29 15:11:59.816  8123  8123 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 15:11:59.816  1034  1376 D WifiNative-wlan0: doBoolean: SCAN
08-29 15:11:59.816  1034  1376 D WifiNative-wlan0: SCAN: returned false
08-29 15:11:59.817  1034  1376 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=140068  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-29 15:11:59.818  8084  8084 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-29 15:11:59.818  8084  8084 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 15:11:59.818  1034  8142 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 15:11:59.818  1034  8142 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 15:11:59.818  1034  8142 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 15:11:59.818  1034  8142 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 15:11:59.819  1925  8143 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 15:11:59.819  8084  8084 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-29 15:11:59.819  8084  8084 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 15:11:59.819  1034  8142 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 15:11:59.819  1034  8142 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 15:11:59.819  1034  8142 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 15:11:59.819  1034  8142 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 15:11:59.820  8084  8084 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 15:11:59.820  1034  1374 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-29 15:11:59.820  1034  1374 D LGWifiP2pService: InactiveState{ when=-14ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:59.820  1034  1374 D LGWifiP2pService: P2pEnabledState{ when=-14ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:59.820  1034  1374 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:59.820  1034  1374 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:59.820  1034  1374 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:59.820  1034  1374 D LGWifiP2pService: InactiveState{ when=-1ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:59.821  1034  1374 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:59.821  1034  1374 D LGWifiP2pService: DefaultState{ when=-1ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:59.821  1925  8143 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 15:11,:59.821  1925  8143 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 15:11:59.821  1034  1374 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:59.821  1034  8142 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 15:11:59.821  1034  1374 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:59.821  1034  8142 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 15:11:59.821  1034  1374 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:59.821  1034  8142 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 15:11:59.821  1034  8142 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 15:11:59.821  1034  1374 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:59.821  1034  1374 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:59.821  1034  1374 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:11:59.821  1034  1034 E WifiServerServiceExt: No p2p device connected
,08-29 15:11:59.821  1034  1376 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=140073  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-29 15:11:59.822  1034  1376 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 15:11:59.822  1034  1376 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 15:11:59.823  1925  2271 W WfdsService: DefaultState - msg [9441285] is not handled
08-29 15:11:59.824  1034  1376 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 15:11:59.825  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-29 15:11:59.825  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 15:11:59.825  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 15:11:59.826  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:11:59.826  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:11:59.826  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING],
08-29 15:11:59.826  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 15:11:59.827  1034  1376 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 15:11:59.827  1034  1376 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 15:11:59.828  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,08-29 15:11:59.828  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING
,08-29 15:11:59.831  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 15:11:59.833  1034  1962 I ActivityManager: Killing 7211:com.lge.drmservice/u0a62 (adj 15): empty #17
08-29 15:11:59.863  1034  1922 W libprocessgroup: failed to open /acct/uid_10062/pid_7211/cgroup.procs: No such file or directory
,08-29 15:11:59.888  6892  6892 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-29 15:11:59.888  6892  6892 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 15:11:59.888  6892  6892 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 15:11:59.888  6892  6892 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 15:11:59.889  6892  6892 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 15:11:59.891  6892  6892 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 15:11:59.891  6892  6892 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
,08-29 15:11:59.891  6892  6892 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 15:11:59.891  6892  6892 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 15:11:59.891  6892  6892 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 15:11:59.891  6892  6892 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 15:11:59.899  8123  8123 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 15:11:59.911  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-29 15:11:59.912  8101  8147 W FormManager: Network not available. Please check & try again.
08-29 15:11:59.915  8101  8148 V FormManager: Network unavailable.
08-29 15:11:59.920  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 15:11:59.932  8101  8148 V FormManager: Network unavailable.
,08-29 15:11:59.934  4308  4308 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 15:11:59.934  4308  4308 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 15:11:59.936  4308  4308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 15:11:59.940  4308  4308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 15:11:59.946  4308  8150 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 15:11:59.946  4308  8150 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 15:11:59.947  4308  8149 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-29 15:11:59.992  1034  2011 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8151 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-29 15:12:00.048  1587  1587 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-29 15:12:00.048  1587  1587 I KeyguardUpdateMonitor: called onTimeUpdated()
08-29 15:12:00.048  1587  1587 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-29 15:12:00.049  1587  1587 I [SystemUI]Clock: called onTimeUpdated()
08-29 15:12:00.052  1587  1587 I LgeClockWidgetControlView: called onTimeUpdated()
08-29 15:12:00.052  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
08-29 15:12:00.053  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
08-29 15:12:00.055  1587  1587 D KeyguardUpdateMonitor: handleTimeUpdate
08-29 15:12:00.125  8151  8151 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-29 15:12:00.126  8151  8151 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-29 15:12:00.135  8151  8151 V [BNRBootReceiver]: Boot Receiver Return
08-29 15:12:00.137  8151  8151 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-29 15:12:00.216  1034  1560 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8172 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-29 15:12:00.219  1034  1560 I ActivityManager: Killing 7230:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,08-29 15:12:00.285  1034  1929 W libprocessgroup: failed to open /acct/uid_10085/pid_7230/cgroup.procs: No such file or directory
,08-29 15:12:00.320  8172  8172 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-29 15:12:00.327  1034  8142 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-29 15:12:00.328  1034  8142 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-29 15:12:00.328  1034  8142 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-29 15:12:00.328  1034  8142 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: WPS-AP-AVAILABLE 
08-29 15:12:00.328  1034  8142 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-29 15:12:00.328  8084  8084 E wpa_supplicant: USIM:  scard_init function
08-29 15:12:00.329  1034  1376 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-29 15:12:00.329  1034  1376 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-29 15:12:00.329  8084  8084 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-29 15:12:00.330  1034  1376 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-29 15:12:00.330  1034  1376 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-29 15:12:00.330  1034  1376 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-29 15:12:00.330  1034  8142 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-29 15:12:00.330  1034  8142 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-29 15:12:00.348  1034  1376 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=140599  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-29 15:12:00.349  1034  1376 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=140601  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-29 15:12:00.351  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 15:12:00.351  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 15:12:00.353  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 15:12:00.353  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:12:00.353  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:12:00.357  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-29 15:12:00.357  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:12:00.357  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:12:00.357  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-29 15:12:00.358  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 15:12:00.358  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 15:12:00.360  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 15:12:00.363  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 15:12:00.363  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATING
,08-29 15:12:00.367  8172  8172 D PluginManager: init()
,08-29 15:12:00.446  8084  8084 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-29 15:12:00.446  1034  8142 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-29 15:12:00.446  1034  8142 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-29 15:12:00.447  1034  8142 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-29 15:12:00.447  1034  8142 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-29 15:12:00.449  1034  1376 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=140700  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-29 15:12:00.450  1034  1376 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=140702  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-29 15:12:00.452  1034  8142 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 15:12:00.452  1034  8142 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 15:12:00.455  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 15:12:00.455  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-29 15:12:00.456  1034  1376 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=140707
08-29 15:12:00.456  1034  1376 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=140708
,08-29 15:12:00.457  1034  1376 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=140709
08-29 15:12:00.458  1034  1376 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=140709
08-29 15:12:00.458  1034  1376 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=140710
08-29 15:12:00.459  1034  1376 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=140710  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-29 15:12:00.461  1034  1116 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-29 15:12:00.463  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:12:00.463  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:12:00.463  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-29 15:12:00.465  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 15:12:00.465  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 15:12:00.468  1034  1376 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=140719  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-29 15:12:00.468  1034  1376 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
,08-29 15:12:00.470  8084  8084 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 15:12:00.470  8084  8084 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 15:12:00.471  1034  8142 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 15:12:00.471  1034  8142 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 15:12:00.471  1034  8142 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-29 15:12:00.471  1034  8142 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 15:12:00.471  1034  8142 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 15:12:00.471  1034  8142 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-29 15:12:00.471  1034  8142 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 15:12:00.471  1034  8142 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 15:12:00.472  1034  1376 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-29 15:12:00.473  1034  1376 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-29 15:12:00.474  1034  1376 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-29 15:12:00.474  1034  1376 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 15:12:00.475  1034  8142 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 15:12:00.475  1034  8142 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 15:12:00.477  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 15:12:00.477  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:12:00.477  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:12:00.477  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-29 15:12:00.479  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 15:12:00.480  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 15:12:00.480  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 15:12:00.480  1034  1034 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-29 15:12:00.481  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 15:12:00.481  1034  1376 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=140732  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
,08-29 15:12:00.482  1034  1376 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=140733  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-29 15:12:00.485  1034  1376 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=140736
08-29 15:12:00.486  1034  1376 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=140737
08-29 15:12:00.486  1034  1376 D WifiNative-wlan0: doString: [STATUS]
08-29 15:12:00.487  1034  8142 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 15:12:00.487  1034  8142 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 15:12:00.487  1034  1376 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-29 15:12:00.489  1034  1376 I WifiServiceExtension: setVHTCapabilityType  : false
08-29 15:12:00.495  1034  1376 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-29 15:12:00.495  1034  1376 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-29 15:12:00.500  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 15:12:00.500  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 15:12:00.500  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:12:00.500  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:12:00.500  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-29 15:12:00.502  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 15:12:00.504  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 15:12:00.504  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 15:12:00.504  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:12:00.504  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:12:00.504  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-29 15:12:00.505  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 15:12:00.510  1034  1376 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-29 15:12:00.510  1034  1376 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 15:12:00.510  1034  1376 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,08-29 15:12:00.513  1034  1452 D ConnectivityService: Got NetworkAgent Messenger
08-29 15:12:00.513  1034  1452 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-29 15:12:00.513  1034  1452 D ConnectivityService: NetworkAgent connected
08-29 15:12:00.513  1034  1376 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 15:12:00.513  1034  1376 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-29 15:12:00.519  1034  1376 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-29 15:12:00.519  1034  1376 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 15:12:00.519  1034  1376 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-29 15:12:00.519  1034  1376 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 15:12:00.519  1034  1376 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-29 15:12:00.523  1034  1376 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-29 15:12:00.526   310   892 D CommandListener: Setting iface cfg
08-29 15:12:00.530  1034  1376 E WifiStateMachine: Start Dhcp Watchdog 3
08-29 15:12:00.530  1034  1376 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=140782  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 15:12:00.531  1034  1376 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=140782  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 15:12:00.531  1034  1376 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=140783  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 15:12:00.533  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 15:12:00.533  1034  1034 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-29 15:12:00.534  1034  8190 D DhcpStateMachine: StoppedState
08-29 15:12:00.534  1034  8190 D DhcpStateMachine: StoppedState{ when=-4ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:12:00.534  1034  1376 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=140785  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 15:12:00.534  1034  8190 D DhcpStateMachine: WaitBeforeStartState
08-29 15:12:00.534  1034  1376 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=140786  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 15:12:00.535  1034  1376 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=140786  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-29 15:12:00.536  1034  1376 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14439] from screen [on:0 period:-697461992] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-29 15:12:00.537  1034  1376 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-697461991] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-29 15:12:00.537  1034  1376 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-29 15:12:00.542  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 15:12:00.544  1034  1452 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-29 15:12:00.544  1034  1376 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 15:12:00.545  1034  1376 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 15:12:00.545  1034  1376 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 15:12:00.545  1034  1376 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 15:12:00.546  1034  1376 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 15:12:00.546  1034  1376 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 15:12:00.547  1034  1452 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
,08-29 15:12:00.550  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 15:12:00.550  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-29 15:12:00.551  1034  1376 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=113,0,0
08-29 15:12:00.551  1034  1376 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=113,0,0
08-29 15:12:00.551  1034  1376 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-29 15:12:00.552  8084  8084 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-29 15:12:00.552  1034  1376 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-29 15:12:00.552  1034  1376 D WifiNative-wlan0: doBoolean: SET ps 0
08-29 15:12:00.553  1034  1376 D WifiNative-wlan0: SET ps 0: returned true
08-29 15:12:00.553  1034  1376 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-29 15:12:00.553  8084  8084 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-29 15:12:00.553  1034  1376 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-29 15:12:00.553  1034  1376 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-29 15:12:00.553  1034  1376 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-29 15:12:00.553  1034  1374 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4c5ffb1 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:12:00.554  1034  1374 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4c5ffb1 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:12:00.554  1034  1376 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-29 15:12:00.554  1034  8190 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:12:00.554  1034  8190 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-29 15:12:00.555   310   892 D CommandListener: Setting iface cfg
08-29 15:12:00.555   310   892 D CommandListener: Trying to bring up wlan0
08-29 15:12:00.556  1034  1376 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-29 15:12:00.557  1034  1376 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 15:12:00.557  1034  1376 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 15:12:00.557  1034  1376 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 15:12:00.558  1034  1376 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 15:12:00.558  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 15:12:00.558  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-29 15:12:00.558  1034  1376 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 15:12:00.559  1034  1376 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,08-29 15:12:00.559  1034  1452 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-29 15:12:00.559  1034  1376 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-29 15:12:00.560  1034  1376 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-29 15:12:00.560  1034  1376 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-29 15:12:00.560  1034  1374 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:12:00.560  1034  1374 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:12:00.560  8084  8084 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-29 15:12:00.561  1034  1376 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-29 15:12:00.561  1034  1376 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-29 15:12:00.561  8084  8084 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-29 15:12:00.561  1034  1376 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-29 15:12:00.561  1034  1376 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 15:12:00.580  1034  1376 D WifiNative-wlan0: SET ps 1: returned true
,08-29 15:12:00.580  1034  1452 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-29 15:12:00.581  1034  1376 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-29 15:12:00.581  1034  1376 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-29 15:12:00.581  1034  1376 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-29 15:12:00.582  1034  1452 D ConnectivityService: ignoring duplicate network state non-change
08-29 15:12:00.585  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 15:12:00.586  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 15:12:00.586  7810  7916 D UEI.SmartControl: Internal timer expired: 3
08-29 15:12:00.587  7810  7916 D UEI.SmartControl: unbind internal service
08-29 15:12:00.587  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:12:00.587  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:12:00.587  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-29 15:12:00.588  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 15:12:00.589  7810  7810 D UEI.SmartControl: Service.onUnbind: IControl
08-29 15:12:00.589  7810  7810 D UEI.SmartControl: Service.onDestroy
08-29 15:12:00.589  7810  7810 D UEI.SmartControl: Lock is in USE false
08-29 15:12:00.589  7810  7810 D UEI.SmartControl: unbind internal service
08-29 15:12:00.589  7810  7810 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@2f5f65fb
08-29 15:12:00.590  7810  7810 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-29 15:12:00.590  1034  1452 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-29 15:12:00.590  7810  7810 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-29 15:12:00.590  7810  7810 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-29 15:12:00.590  7810  7810 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-29 15:12:00.590  7810  7810 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-29 15:12:00.590  7810  7810 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-29 15:12:00.590  7810  7810 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-29 15:12:00.590  7810  7810 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-29 15:12:00.590  7810  7810 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:12:00.590  7810  7810 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-29 15:12:00.590  7810  7810 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 15:12:00.590  7810  7810 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 15:12:00.590  7810  7810 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 15:12:00.590  7810  7810 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 15:12:00.590  1034  1452 D ConnectivityService: Adding iface wlan0 to network 102
08-29 15:12:00.590  7810  7810 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 15:12:00.590  7810  7810 E UEI.SmartControl: java.lang.IllegalArgumentException:, Service not registered: com.uei.control.g@2f5f65fb
08-29 15:12:00.591  7810  7810 D serial_port: close(fd = 24)
08-29 15:12:00.592  1034  1376 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-29 15:12:00.597  7810  7810 I UEI.SmartControl: Serial port is closed.
08-29 15:12:00.597  7810  7810 I UEI.SmartControl: Serial port is closed.
08-29 15:12:00.597  7810  7810 D UEI.SmartControl: Blaster closed
08-29 15:12:00.597  7810  7810 D UEI.SmartControl: Shut down QS...
08-29 15:12:00.597  7810  7810 D UEI.SmartControl: Stopping QS lib
08-29 15:12:00.598  7810  7810 D UEI.SmartControl: QS lib stop result = true
08-29 15:12:00.598  7810  7810 D UEI.SmartControl: Stopped QS lib
08-29 15:12:00.598  7810  7810 D UEI.SmartControl: QS shutdown complete
08-29 15:12:00.599  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:12:00.599  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:12:00.599  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-29 15:12:00.603  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-29 15:12:00.605  1925  1925 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-29 15:12:00.610  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 15:12:00.610  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-29 15:12:00.611  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:12:00.611  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:12:00.611  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-29 15:12:00.611  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 15:12:00.611  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-29 15:12:00.611  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:12:00.611  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:12:00.611  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-29 15:12:00.614  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 15:12:00.615  1587  1587 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-29 15:12:00.615  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 15:12:00.618  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 15:12:00.618  1587  1587 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-29 15:12:00.618  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 15:12:00.626  1034  1452 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-29 15:12:00.626  1034  1452 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-29 15:12:00.629  1034  1452 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-29 15:12:00.630   310   892 E Netd    : netlink response contains error (File exists)
,08-29 15:12:00.631  1034  1452 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-29 15:12:00.632  6671  6818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:12:00.632  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:12:00.632  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 15:12:00.632  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:12:00.632  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:12:00.632  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:12:00.632  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:12:00.632  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 15:12:00.633  1034  1452 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-29 15:12:00.633  1034  1452 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-29 15:12:00.633  1034  1452 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-29 15:12:00.634  1034  1452 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-29 15:12:00.634  1034  1452 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-29 15:12:00.634  1034  1452 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-29 15:12:00.634  1034  1452 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-29 15:12:00.634  1034  8189 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:12:00.634  1034  8189 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-29 15:12:00.634  1034  1452 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 15:12:00.634  1034  1452 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 15:12:00.634  1034  8189 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-29 15:12:00.634  1034  1452 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-29 15:12:00.634  1034  8189 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-29 15:12:00.634  1034  1452 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 15:12:00.634  1034  1452 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-29 15:12:00.634  1034  1452 D ConnectivityService: currentScore = 0, newScore = 20
08-29 15:12:00.635  1034  1452 D ConnectivityService:    accepting network in place of null
08-29 15:12:00.635  1034  1452 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 15:12:00.635  1034  1376 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 15:12:00.635  1034  1376 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 15:12:00.636  6671  6818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth,: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 15:12:00.637  1034  1452 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-29 15:12:00.637  1034  1452 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-29 15:12:00.637  1034  1452 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-29 15:12:00.638  1034  1452 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-29 15:12:00.638  1034  1452 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-29 15:12:00.638  1034  1452 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-29 15:12:00.639  1034  1452 D ConnectivityService: validation of new default Network = false
08-29 15:12:00.639  1034  1452 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-29 15:12:00.639  1034  1452 D DSQN    : enableDataServiceNotify 
08-29 15:12:00.639  1034  1452 D DSQN    : start dsqn bin
08-29 15:12:00.642  1836  1836 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 15:12:00.643  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-29 15:12:00.644   310  8200 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
,08-29 15:12:00.634  8201  8201 W dsqn    : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 15:12:00.634  8201  8201 W dsqn    : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 15:12:00.645  6671  6818 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-29 15:12:00.646  6671  6818 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-29 15:12:00.647  1034  1034 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-29 15:12:00.648  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-29 15:12:00.648  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-29 15:12:00.648  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-29 15:12:00.648  6671  6818 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3fea9656 Bundle[{}]
08-29 15:12:00.649  6671  6818 I io.jxcore.node.LifeCycleMonitor: start: OK
08-29 15:12:00.649  6671  6818 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-29 15:12:00.650  6671  6818 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-29 15:12:00.650  6671  6818 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-29 15:12:00.650  1034  1452 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-29 15:12:00.651  1034  1452 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-29 15:12:00.651  1034  1452 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 15:12:00.651  6671  6818 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-29 15:12:00.651  1034  1452 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 15:12:00.651  1587  2055 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-29 15:12:00.655  6671  6818 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-29 15:12:00.661  6671  6818 I System.out: Running OutgoingSocketThread
08-29 15:12:00.662  8201  8201 E DSQN    : DSQN ssw
,08-29 15:12:00.666  6671  8203 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 851)
08-29 15:12:00.667  6671  8203 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 58873
08-29 15:12:00.667  6671  8203 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-29 15:12:00.675  1034  1373 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-29 15:12:00.684  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 15:12:00.685  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 15:12:00.685  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 15:12:00.757  1034  8190 D DhcpStateMachine: DHCPV4 request on wlan0
08-29 15:12:00.759  1034  8190 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
,08-29 15:12:00.759  1034  8190 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-29 15:12:00.754  8206  8206 W dhcpcd  : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 15:12:00.754  8206  8206 W dhcpcd  : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 15:12:00.781  8206  8206 I dhcpcd  : version 5.5.6 starting
08-29 15:12:00.784  8206  8206 E dhcpcd  : get_duid: m
08-29 15:12:00.784  8206  8206 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-29 15:12:00.784  8206  8206 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-29 15:12:00.806  8172  8172 W ExternalStrings: load override strings
08-29 15:12:00.806  8172  8172 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-29 15:12:00.806  8172  8172 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-29 15:12:00.806  8172  8172 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-29 15:12:00.806  8172  8172 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-29 15:12:00.806  8172  8172 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-29 15:12:00.806  8172  8172 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-29 15:12:00.806  8172  8172 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-29 15:12:00.806  8172  8172 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-29 15:12:00.806  8172  8172 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-29 15:12:00.806  8172  8172 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-29 15:12:00.806  8172  8172 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-29 15:12:00.806  8172  8172 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:12:00.806  8172  8172 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-29 15:12:00.806  8172  8172 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 15:12:00.806  8172  8172 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 15:12:00.806  8172  8172 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 15:12:00.806  8172  8172 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 15:12:00.806  8172  8172 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 15:12:00.809  8172  8172 D StatusProvider: onCreate
,08-29 15:12:00.869  8172  8172 V Signer  : override build config not found
,08-29 15:12:00.870  8172  8172 D Signer  : value of property debug is false
,08-29 15:12:00.899  8206  8206 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,08-29 15:12:00.899  8206  8206 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-29 15:12:00.899  8206  8206 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-29 15:12:00.899  8206  8206 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-29 15:12:00.899  8206  8206 D dhcpcd  : wlan0: sending REQUEST (xid 0xea805cc8), next in 3.59 seconds
,08-29 15:12:00.927  8172  8172 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
,08-29 15:12:00.927  8172  8172 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
,08-29 15:12:00.928  8172  8172 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
,08-29 15:12:00.928  8172  8172 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-29 15:12:00.928  8172  8172 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-29 15:12:00.928  8172  8172 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-29 15:12:00.929  8172  8172 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-29 15:12:00.929  8172  8172 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-29 15:12:00.929  8172  8172 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-29 15:12:00.929  8172  8172 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-29 15:12:00.930  8172  8172 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-29 15:12:00.930  8172  8172 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-29 15:12:00.930  8172  8172 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-29 15:12:00.940  8172  8172 V LGMDMManager: Create singleton instance
08-29 15:12:00.975  8206  8206 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-29 15:12:01.014  8172  8172 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
08-29 15:12:01.014  8206  8206 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
,08-29 15:12:01.014  8206  8206 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-29 15:12:01.014  8206  8206 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-29 15:12:01.015  8206  8206 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-29 15:12:01.015  8206  8206 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-29 15:12:01.016  8206  8206 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-29 15:12:01.016  8206  8206 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-29 15:12:01.016  8206  8206 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-29 15:12:01.103  8172  8172 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 15:12:01.103  8172  8227 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-29 15:12:01.113  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 15:12:01.120  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 15:12:01.151  1034  1922 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8234 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-29 15:12:01.155  1034  1922 I ActivityManager: Killing 7276:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
08-29 15:12:01.201   310  8200 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-29 15:12:01.294  8172  8225 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-29 15:12:01.364  1034  1922 E libprocessgroup: failed to kill 1 processes for processgroup 7276
,08-29 15:12:01.365  1034  8190 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-29 15:12:01.368  1034  8190 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
,08-29 15:12:01.368  1034  8190 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-29 15:12:01.369  1034  8190 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-29 15:12:01.369  1034  8190 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
,08-29 15:12:01.369  1034  8190 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-29 15:12:01.369  1034  8190 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
,08-29 15:12:01.369  1034  8190 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-29 15:12:01.371  1034  8190 D DhcpStateMachine: RunningState
,08-29 15:12:01.461  8234  8234 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 15:12:01.483  8234  8234 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-29 15:12:01.516  8234  8234 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-29 15:12:01.517  8234  8234 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-29 15:12:01.517  8234  8234 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-29 15:12:01.517  8234  8234 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-29 15:12:01.518  8234  8234 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-29 15:12:01.519  8234  8234 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-29 15:12:01.522  8172  8225 D LgDataFeature: LgDataFeature() Constructor: none
08-29 15:12:01.522  8172  8225 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 15:12:01.525  8234  8234 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-29 15:12:01.531  8234  8234 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 15:12:01.533  8234  8234 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 15:12:01.543  8234  8234 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-29 15:12:01.546  8234  8234 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-29 15:12:01.546  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-29 15:12:01.549  6892  6892 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-29 15:12:01.551  8172  8172 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 15:12:01.551  8172  8227 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 15:12:01.552  8234  8234 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-29 15:12:01.559  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 15:12:01.564  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 15:12:01.570  8234  8234 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 15:12:01.571  8234  8234 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 15:12:01.572  8234  8234 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-29 15:12:01.574  8172  8227 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 15:12:01.573  8172  8172 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 15:12:01.578  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 15:12:01.586  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 15:12:01.590  8234  8234 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 15:12:01.590  8234  8234 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 15:12:01.590  8234  8234 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 15:12:01.592  8172  8172 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 15:12:01.593  8172  8227 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-29 15:12:01.599  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 15:12:01.608  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 15:12:01.614  8172  8225 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,08-29 15:12:01.617  8234  8234 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 15:12:01.617  8234  8234 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 15:12:01.617  8234  8234 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 15:12:01.619  6892  6892 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 15:12:01.619  6892  6892 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 15:12:01.619  6892  6892 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 15:12:01.619  6892  6892 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 15:12:01.619  6892  6892 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 15:12:01.620  6892  6892 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 15:12:01.620  6892  6892 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-29 15:12:01.620  6892  6892 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 15:12:01.620  6892  6892 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 15:12:01.620  6892  6892 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 15:12:01.620  6892  6892 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-29 15:12:01.620  6892  6892 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 15:12:01.623  8172  8172 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 15:12:01.623  8172  8227 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 15:12:01.628  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 15:12:01.634  8172  8225 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-29 15:12:01.637  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 15:12:01.643  8234  8234 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 15:12:01.643  8234  8234 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 15:12:01.644  8234  8234 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 15:12:01.644  8172  8225 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-29 15:12:01.645  8172  8225 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-29 15:12:01.646  8172  8225 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-29 15:12:01.646  8172  8225 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-29 15:12:01.646  8172  8172 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 15:12:01.647  8172  8225 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-29 15:12:01.647  8172  8227 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 15:12:01.650  8172  8225 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-29 15:12:01.651  8172  8225 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-29 15:12:01.654  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 15:12:01.659  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 15:12:01.662  6671  6818 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 852)
08-29 15:12:01.662  6671  6818 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 852)
08-29 15:12:01.665  6671  6818 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 857)
,08-29 15:12:01.666  6671  6818 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-29 15:12:01.666  6671  6818 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 858)
08-29 15:12:01.667  8234  8234 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 15:12:01.667  8234  8234 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 15:12:01.667  8234  8234 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-29 15:12:01.669  6671  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 15:12:01.669  6671  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16fd4d1d added. We now have 2 listener(s)
08-29 15:12:01.669  1034  1758 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 15:12:01.670  8172  8172 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 15:12:01.670  8172  8227 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 15:12:01.675  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 15:12:01.675  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 15:12:01.675  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 15:12:01.675  6671  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 15:12:01.675  6671  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c6db92 added. We now have 9 listener(s)
08-29 15:12:01.675  6671  6818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 15:12:01.675  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 15:12:01.677  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 15:12:01.678  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 15:12:01.684  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 15:12:01.684  6671  6818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 15:12:01.684  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:12:01.684  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 15:12:01.684  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:12:01.684  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:12:01.684  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 15:12:01.684  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 15:12:01.684  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 15:12:01.686  6671  6818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 15:12:01.686  6671  6818 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 15:12:01.686  6671  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 15:12:01.686  6671  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13e5f960 added. We now have 3 listener(s)
08-29 15:12:01.686  1034  1929 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 15:12:01.688  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:12:01.690  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 15:12:01.690  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 15:12:01.690  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 15:12:01.690  6671  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 15:12:01.690  6671  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b269e19 added. We now have 10 listener(s)
08-29 15:12:01.690  6671  6818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 15:12:01.690  6671  6818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:12:01.690  6671  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:12:01.690  6671  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:12:01.690  6671  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:12:01.690  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:12:01.690  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:12:01.690  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 15:12:01.690  6671  6818 V org.thaliproject.p2p.btconnectorlib.Connectio,nManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16fd4d1d removed from the list
08-29 15:12:01.690  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:12:01.691  6671  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c6db92 removed from the list
08-29 15:12:01.691  8234  8234 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 15:12:01.691  8234  8234 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 15:12:01.691  8234  8234 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 15:12:01.692  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:12:01.692  6671  6818 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:12:01.692  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:12:01.694  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:12:01.694  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:12:01.694  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:12:01.695  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:12:01.695  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:12:01.695  6671  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c6db92 not in the list
08-29 15:12:01.695  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:12:01.695  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 15:12:01.695  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:12:01.695  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:12:01.695  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:12:01.695  6671  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b269e19 removed from the list
08-29 15:12:01.695  6671  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:12:01.695  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:12:01.696  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:12:01.696  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 15:12:01.696  6671  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13e5f960 removed from the list
08-29 15:12:01.696  6671  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 15:12:01.696  6671  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f31ede added. We now have 2 listener(s)
08-29 15:12:01.697  1034  2011 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 15:12:01.700  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 15:12:01.700  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 15:12:01.700  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 15:12:01.700  6671  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 15:12:01.700  6671  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f9ff8bf added. We now have 9 listener(s)
08-29 15:12:01.700  6671  6818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 15:12:01.700  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 15:12:01.703  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 15:12:01.703  8172  8172 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 15:12:01.707  6671  6818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 15:12:01.707  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:12:01.707  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 15:12:01.707  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:12:01.707  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:12:01.707  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 15:12:01.707  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 15:12:01.707  6671  681,8 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 15:12:01.708  8172  8227 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 15:12:01.708  6671  6818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 15:12:01.708  6671  6818 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 15:12:01.708  6671  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 15:12:01.708  6671  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2efa02d5 added. We now have 3 listener(s)
08-29 15:12:01.709  1034  1991 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 15:12:01.711  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:12:01.713  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:12:01.715  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 15:12:01.715  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 15:12:01.715  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 15:12:01.715  6671  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 15:12:01.715  6671  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@330e4aea added. We now have 10 listener(s)
08-29 15:12:01.715  6671  6818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 15:12:01.715  6671  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 15:12:01.715  6671  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 15:12:01.715  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 15:12:01.715  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 15:12:01.715  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 15:12:01.719  6671  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 15:12:01.719  1034  1889 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 15:12:01.724  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 15:12:01.725  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 15:12:01.725  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 15:12:01.726  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 15:12:01.727  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:12:01.729  6671  6818 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-29 15:12:01.729  6671  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:12:01.729  6671  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:12:01.731  6671  6818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:12:01.731  6671  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:12:01.731  6671  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 15:12:01.731  6671  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:12:01.731  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:12:01.731  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:12:01.731  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 15:12:01.731  6671  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f31ede removed from the list
08-29 15:12:01.731  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:12:01.731  6671  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f9ff8bf removed from the list
08-29 15:12:01.731  6671  6818 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:12:01.731  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:12:01.731  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:12:01.731  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:12:01.732  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:12:01.732  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:12:01.732  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:12:01.732  6671  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f9ff8bf not in the list
08-29 15:12:01.732  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:12:01.732  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:12:01.733  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:12:01.734  6671  6818 D BluetoothLeScanner: could not find callback wrapper
08-29 15:12:01.734  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 15:12:01.734  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:12:01.734  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:12:01.734  6671  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@330e4aea removed from the list
08-29 15:12:01.734  6671  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:12:01.734  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:12:01.734  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:12:01.734  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 15:12:01.734  6671  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2efa02d5 removed from the list
08-29 15:12:01.734  6671  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 15:12:01.735  6671  6818 V org.thaliproject.p2p.btconnectorlib.Connection,ManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1364f751 added. We now have 2 listener(s)
08-29 15:12:01.735  1034  1049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 15:12:01.736  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 15:12:01.738  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 15:12:01.738  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 15:12:01.738  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 15:12:01.738  6671  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 15:12:01.738  6671  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1efe2bb6 added. We now have 9 listener(s)
08-29 15:12:01.739  6671  6818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 15:12:01.739  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 15:12:01.744  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 15:12:01.745  8234  8234 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 15:12:01.746  8234  8234 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 15:12:01.751  8234  8234 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 15:12:01.752  6671  6818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 15:12:01.752  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:12:01.752  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 15:12:01.752  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:12:01.752  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:12:01.752  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 15:12:01.752  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 15:12:01.752  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 15:12:01.756  6671  6818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 15:12:01.756  8172  8227 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 15:12:01.756  6671  6818 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 15:12:01.756  6671  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 15:12:01.757  6671  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5938024 added. We now have 3 listener(s)
08-29 15:12:01.757  1034  1874 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 15:12:01.760  8172  8172 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 15:12:01.760  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:12:01.761  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 15:12:01.761  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 15:12:01.761  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 15:12:01.761  6671  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 15:12:01.761  6671  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10b0b78d added. We now have 10 listener(s)
08-29 15:12:01.761  6671  6818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 15:12:01.762  6671  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 15:12:01.762  6671  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 15:12:01.762  6671  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 15:12:01.762  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 15:12:01.762  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 15:12:01.762  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 15:12:01.767  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:12:01.769   310  8200 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-29 15:12:01.771  6671  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 15:12:01.771  1034  2011 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 15:12:01.775  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 15:12:01.777  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 15:12:01.778  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 15:12:01.778  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:12:01.779  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 15:12:01.780  6671  6818 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-29 15:12:01.780  6671  6818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:12:01.780  6671  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:12:01.780  6671  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:12:01.780  6671  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:12:01.780  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:12:01.780  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:12:01.780  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 15:12:01.780  6671  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1364f751 removed from the list
08-29 15:12:01.780  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:12:01.781  6671  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1efe2bb6 removed from the list
08-29 15:12:01.781  6671  6818 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:12:01.781  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:12:01.781  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:12:01.781  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:12:01.782  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:12:01.782  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:12:01.782  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:12:01.782  6671  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1efe2bb6 not in the list
08-29 15:12:01.782  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:12:01.782  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:12:01.784  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:12:01.785  6671  6818 D BluetoothLeScanner: could not find callback wrapper
08-29 15:12:01.785  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 15:12:01.785  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:12:01.785  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:12:01.785  6671  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10b0b78d removed from the list
08-29 15:12:01.785  6671  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:12:01.785  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08,-29 15:12:01.785  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:12:01.785  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 15:12:01.785  6671  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5938024 removed from the list
08-29 15:12:01.786  6671  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 15:12:01.786  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 15:12:01.786  6671  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a9a7a90 added. We now have 2 listener(s)
08-29 15:12:01.788  1034  1962 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 15:12:01.791  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 15:12:01.791  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 15:12:01.791  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 15:12:01.791  6671  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 15:12:01.791  6671  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e3f89 added. We now have 9 listener(s)
08-29 15:12:01.791  6671  6818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 15:12:01.791  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 15:12:01.791  8234  8234 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 15:12:01.792  8234  8234 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 15:12:01.792  8234  8234 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 15:12:01.795  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 15:12:01.797  8172  8172 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 15:12:01.799  6671  6818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 15:12:01.799  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:12:01.799  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 15:12:01.799  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:12:01.799  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:12:01.799  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 15:12:01.799  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 15:12:01.799  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 15:12:01.800  8172  8227 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 15:12:01.800  8123  8123 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-29 15:12:01.801  6671  6818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 15:12:01.801  6671  6818 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 15:12:01.801  6671  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 15:12:01.801  6671  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8e8faf added. We now have 3 listener(s)
08-29 15:12:01.802  1034  1874 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-29 15:12:01.803  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:12:01.805  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:12:01.806  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 15:12:01.806  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 15:12:01.806  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 15:12:01.806  6671  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 15:12:01.806  6671  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cd4afbc added. We now have 10 listener(s)
08-29 15:12:01.806  6671  6818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 15:12:01.806  6671  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 15:12:01.806  6671  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 15:12:01.806  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 15:12:01.806  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 15:12:01.806  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 15:12:01.808  6671  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 15:12:01.808  1034  1929 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 15:12:01.809  8123  8123 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-29 15:12:01.811  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 15:12:01.812  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 15:12:01.812  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 15:12:01.813  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 15:12:01.813  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:12:01.815  6671  6818 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-29 15:12:01.817  6671  6818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:12:01.817  6671  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:12:01.817  6671  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:12:01.817  6671  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:12:01.817  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:12:01.817  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:12:01.817  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 15:12:01.817  6671  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a9a7a90 removed from the list
08-29 15:12:01.817  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:12:01.818  6671  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e3f89 removed from the list
08-29 15:12:01.818  6671  6818 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:12:01.818  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:12:01.818  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:12:01.818  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 15:12:01.819  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:12:01.819  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:12:01.819  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:12:01.819  6671  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e3f89 not in the list
,08-29 15:12:01.819  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:12:01.819  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:12:01.820  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:12:01.821  6671  6818 D BluetoothLeScanner: could not find callback wrapper
08-29 15:12:01.821  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 15:12:01.821  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:12:01.821  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:12:01.821  6671  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cd4afbc removed from the list
08-29 15:12:01.821  6671  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:12:01.821  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 15:12:01.821  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:12:01.821  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 15:12:01.821  6671  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8e8faf removed from the list
08-29 15:12:01.822  6671  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 15:12:01.822  6671  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@293e77cb added. We now have 2 listener(s)
08-29 15:12:01.822  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 15:12:01.822  1034  1962 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 15:12:01.824  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 15:12:01.824  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 15:12:01.824  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 15:12:01.824  6671  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 15:12:01.824  6671  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1b0ba8 added. We now have 9 listener(s)
08-29 15:12:01.824  6671  6818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 15:12:01.825  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 15:12:01.828  8234  8234 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 15:12:01.828  8234  8234 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 15:12:01.828  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 15:12:01.829  8234  8234 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-29 15:12:01.832  6671  6818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 15:12:01.832  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:12:01.832  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 15:12:01.832  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:12:01.832  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:12:01.832  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 15:12:01.832  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 15:12:01.832  6671  6818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 15:12:01.832  8234  8234 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-29 15:12:01.832  8234  8234 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-29 15:12:01.834  6671  6818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 15:12:01.834  6671  6818 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 15:12:01.834  6671  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 15:12:01.834  6671  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e46ee66 added. We now have 3 listener(s)
08-29 15:12:01.836  1034  1922 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 15:12:01.836  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:12:01.837  8172  8227 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 15:12:01.837  8172  8172 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 15:12:01.837  6671  6671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:12:01.838  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 15:12:01.838  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 15:12:01.838  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 15:12:01.838  6671  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 15:12:01.838  6671  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19bac5a7 added. We now have 10 listener(s)
08-29 15:12:01.838  6671  6818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 15:12:01.839  6671  6818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:12:01.839  6671  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:12:01.839  6671  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:12:01.839  6671  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:12:01.839  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:12:01.839  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:12:01.839  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 15:12:01.839  6671  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@293e77cb removed from the list
08-29 15:12:,01.839  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:12:01.839  6671  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1b0ba8 removed from the list
08-29 15:12:01.839  6671  6818 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:12:01.839  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:12:01.840  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:12:01.840  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:12:01.841  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:12:01.841  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:12:01.841  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:12:01.841  8123  8123 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-29 15:12:01.841  6671  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1b0ba8 not in the list
08-29 15:12:01.841  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:12:01.841  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:12:01.841  8123  8123 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 15:12:01.843  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:12:01.843  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:12:01.844  6671  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:12:01.844  6671  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19bac5a7 removed from the list
08-29 15:12:01.844  6671  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:12:01.844  6671  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:12:01.844  6671  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 15:12:01.844  6671  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 15:12:01.844  6671  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e46ee66 removed from the list
08-29 15:12:01.845  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 15:12:01.846  6671  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-29 15:12:01.846  6671  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-29 15:12:01.847  6671  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-29 15:12:01.847  6671  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 15:12:01.847  6671  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-29 15:12:01.847  6671  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 15:12:01.849  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 15:12:01.853  8234  8234 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 15:12:01.854  8234  8234 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 15:12:01.855  8234  8234 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-29 15:12:01.856  8234  8234 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-29 15:12:01.856  8234  8234 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-29 15:12:01.858  8172  8172 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 15:12:01.858  6671  8288 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 865, name: My test thread name)
08-29 15:12:01.859  6671  8288 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 865, thread name: My test thread name)
08-29 15:12:01.859  6671  8288 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 865, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-29 15:12:01.861  6671  8289 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 867, name: My test thread name)
08-29 15:12:01.861  6671  8289 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 867, thread name: My test thread name)
08-29 15:12:01.861  6671  8289 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 867, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-29 15:12:01.863  6671  6818 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-29 15:12:01.864  6671  6818 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-29 15:12:01.864  6671  6818 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-29 15:12:01.864  6671  6818 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-29 15:12:01.864  6671  6818 D com.test.thalitest.ThaliTestRunner: Total duration: 24038 ms
08-29 15:12:01.865  6671  6818 I jxcore-log: *Native tests were executed*
08-29 15:12:01.865  6671  6818 I jxcore-log: 
08-29 15:12:01.865  6671  6818 I jxcore-log: Total number of executed tests:  80
08-29 15:12:01.865  6671  6818 I jxcore-log: 
08-29 15:12:01.865  6671  6818 I jxcore-log: Number of passed tests:  80
08-29 15:12:01.865  6671  6818 I jxcore-log: 
08-29 15:12:01.866  6671  6818 I jxcore-log: Number of failed tests:  0
08-29 15:12:01.866  6671  6818 I jxcore-log: 
08-29 15:12:01.866  6671  6818 I jxcore-log: Number of ignored tests:  0
08-29 15:12:01.866  6671  6818 I jxcore-log: 
08-29 15:12:01.866  6671  6818 I jxcore-log: Total duration:  24038
08-29 15:12:01.866  6671  6818 I jxcore-log: 
08-29 15:12:01.866  6671  6818 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-29 15:12:01.866  6671  6818 I jxcore-log: 
,08-29 15:12:01.870  6671  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 15:12:01.870  6671  6818 I jxcore-log: 
08-29 15:12:01.873  6671  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 15:12:01.873  6671  6818 I jxcore-log: 
08-29 15:12:01.874  6671  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 15:12:01.874  6671  6818 I jxcore-log: 
08-29 15:12:01.875  6671  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 15:12:01.875  6671  6818 I jxcore-log: 
08-29 15:12:01.876  6671  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 15:12:01.876  6671  6818 I jxcore-log: 
08-29 15:12:01.877  6671  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 15:12:01.877  6671  6818 I jxcore-log: 
08-29 15:12:01.880  6671  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 15:12:01.880  6671  6818 I jxcore-log: 
,08-29 15:12:01.881  6671  6671 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-29 15:12:01.884  6671  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 15:12:01.884  6671  6818 I jxcore-log: 
08-29 15:12:01.885  6671  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 15:12:01.885  6671  6818 I jxcore-log: 
08-29 15:12:01.886  6671  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 15:12:01.886  6671  6818 I jxcore-log: 
08-29 15:12:01.887  8234  8234 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-29 15:12:01.888  8234  8234 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-29 15:12:01.888  6671  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 15:12:01.888  6671  6818 I jxcore-log: 
08-29 15:12:01.888  8234  8234 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-29 15:12:01.889  6671  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 15:12:01.889  6671  6818 I jxcore-log: 
08-29 15:12:01.890  6671  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 15:12:01.890  6671  6818 I jxcore-log: 
08-29 15:12:01.892  6671  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 15:12:01.892  6671  6818 I jxcore-log: 
08-29 15:12:01.893  6671  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 15:12:01.893  6671  6818 I jxcore-log: 
08-29 15:12:01.894  6671  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 15:12:01.894  6671  6818 I jxcore-log: 
08-29 15:12:01.895  6671  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 15:12:01.895  6671  6818 I jxcore-log: 
,08-29 15:12:01.895  6671  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 15:12:01.895  6671  6818 I jxcore-log: 
08-29 15:12:01.896  6671  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 15:12:01.896  6671  6818 I jxcore-log: 
08-29 15:12:01.897  6671  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 15:12:01.897  6671  6818 I jxcore-log: 
08-29 15:12:01.898  6671  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 15:12:01.898  6671  6818 I jxcore-log: 
08-29 15:12:01.898  6671  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 15:12:01.898  6671  6818 I jxcore-log: 
08-29 15:12:01.899  6671  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 15:12:01.899  6671  6818 I jxcore-log: 
08-29 15:12:01.900  6671  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 15:12:01.900  6671  6818 I jxcore-log: 
08-29 15:12:01.901  6671  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 15:12:01.901  6671  6818 I jxcore-log: 
08-29 15:12:01.901  6671  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 15:12:01.901  6671  6818 I jxcore-log: 
08-29 15:12:01.902  6671  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 15:12:01.902  6671  6818 I jxcore-log: 
08-29 15:12:01.903  6671  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 15:12:01.903  6671  6818 I jxcore-log: 
08-29 15:12:01.904  6671  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 15:12:01.904  6671  6818 I jxcore-log: 
08-29 15:12:01.904  6671  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 15:12:01.904  6671  6818 I jxcore-log: 
08-29 15:12:01.914  8234  8234 D LgDataFeature: LgDataFeature() Constructor: none
08-29 15:12:01.914  8234  8234 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 15:12:01.919  8234  8234 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-29 15:12:01.921  8234  8234 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-29 15:12:01.921  8234  8234 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-29 15:12:01.921  8234  8234 V SoundPool: doLoad: loading sample sampleID=1
08-29 15:12:01.921  8234  8234 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-29 15:12:01.924  7810  7810 D UEI.SmartControl: QS Service created
08-29 15:12:01.924  8234  8294 V SoundPool: Start decode
08-29 15:12:01.924  8234  8294 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-29 15:12:01.924  8234  8234 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-29 15:12:01.925  8234  8234 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-29 15:12:01.926  8234  8234 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-29 15:12:01.926   316  2154 V MediaPlayerService: decode(23, 10857164, 17813)
08-29 15:12:01.926   316  2154 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-29 15:12:01.926   316  2154 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-29 15:12:01.926   316  2154 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-29 15:12:01.926   316  2154 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-29 15:12:01.926   316  2154 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-29 15:12:01.926   316  2154 V MediaPlayerService: player type = 3
08-29 15:12:01.926   316  2154 V AwesomePlayer: AwesomePlayer create()
08-29 15:12:01.926   316  2154 V AwesomePlayer: reset_l() 
08-29 15:12:01.926   316  2154 V AwesomePlayer: cancelPlayerEvents
08-29 15:12:01.926   316  2154 V AwesomePlayer: setAudioSink() 
08-29 15:12:01.926   316  2154 V AwesomePlayer: reset_l() 
08-29 15:12:01.926   316  2154 V AudioCache: notify(0xb1432380, 8, 0, 0)
08-29 15:12:01.926   316  2154 V AudioCache: ignored
08-29 15:12:01.926   316  2154 V AwesomePlayer: cancelPlayerEvents
08-29 15:12:01.926   316  2154 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-29 15:12:01.926   316  2154 V AwesomePlayer: setDataSource_l dataSource
08-29 15:12:01.926   316  2154 V LGParserOSAL: SniffLGParser start
08-29 15:12:01.926   316  2154 V LGParserOSAL: MainType:5, SubType=0
08-29 15:12:01.926   316  2154 V LGParserOSAL: #### check Mime : application/ogg
08-29 15:12:01.927   316  2154 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-29 15:12:01.927   316  2154 E MediaExtractor: Use LGExtractor :application/ogg 
08-29 15:12:01.933  8234  8234 V LGMDMManager: Create singleton instance
,08-29 15:12:01.938  7810  7810 I UEI.SmartControl: Service initServices...
08-29 15:12:01.939  7810  7810 D UEI.SmartControl: QS start get config
08-29 15:12:01.969   316  2154 V LGParserOSAL: supported mime: application/ogg
08-29 15:12:01.969   316  2154 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-29 15:12:01.969   316  2154 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-29 15:12:01.969   316  2154 V AwesomePlayer: mBitrate = -1 bits/sec
08-29 15:12:01.969   316  2154 V AwesomePlayer: AudioTrack Setting
08-29 15:12:01.969   316  2154 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-29 15:12:01.969   316  2154 V AwesomePlayer: setAudioSource() 
08-29 15:12:01.969   316  2154 V MediaPlayerService: prepare
08-29 15:12:01.969   316  2154 V AwesomePlayer: prepareAsync_l() 
08-29 15:12:01.969   316  2154 V MediaPlayerService: wait for prepare
08-29 15:12:01.969   316  8297 V AwesomePlayer: onPrepareAsyncEvent() 
08-29 15:12:01.969   316  8297 V AwesomePlayer: initAudioDecoder() 
08-29 15:12:01.969   316  8297 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-29 15:12:01.969   316  8297 V AudioSystem: isOffloadSupported()
08-29 15:12:01.969   316  8297 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
,08-29 15:12:01.969   316  8297 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-29 15:12:01.969   316  8297 I AudioFlinger: isAudioPlaybackHookOn() false
08-29 15:12:01.969   316  8297 V AwesomePlayer: getUseOffload() = 0 
08-29 15:12:01.969   316  8297 V OMXCodec: OMXCodec::Create
08-29 15:12:01.969   316  8297 V OMXCodec: findMatchingCodecs()
08-29 15:12:01.969   316  8297 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-29 15:12:01.969   316  8297 V OMXCodec: matchingCodecs.size()=1
08-29 15:12:01.969   316  8297 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-29 15:12:01.970   316  8297 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-29 15:12:01.970   316  8297 V LGCodecAdapter: LG Codec Adapter start
08-29 15:12:01.970   316  8297 V OMXCodec: OMXCodec Createtor
08-29 15:12:01.970   316  8297 V OMXCodec: setComponentRole
08-29 15:12:01.971   316  8297 V OMXCodec: configureCodec protected=0
08-29 15:12:01.971   316  8297 V LGCodecAdapter: called getLGCodecSpecificData
08-29 15:12:01.971   316  8297 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-29 15:12:01.971   316  8297 V LGCodecOSAL: Called LGconfigureCodecMETA
08-29 15:12:01.971   316  8297 V LGCodecOSAL: Called LGconfigureCodecMSG
08-29 15:12:01.971   316  8297 V LGCodecOSAL: Not support LGCodec
08-29 15:12:01.971   316  8297 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-29 15:12:01.971   316  8297 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-29 15:12:01.971   316  8297 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-29 15:12:01.971   316  8297 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-29 15:12:01.971   316  8297 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-29 15:12:01.971   316  8297 V AudioSystem: isOffloadSupported()
08-29 15:12:01.971   316  8297 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-29 15:12:01.971   316  8297 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-29 15:12:01.971   316  8297 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-29 15:12:01.971   316  8297 V OMXCodec: init()
08-29 15:12:01.971   316  8297 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-29 15:12:01.971   316  8297 V OMXCodec: allocateBuffers
08-29 15:12:01.971   316  8297 V OMXCodec: allocateBuffersOnPort portIndex=0
08-29 15:12:01.971   316  8297 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-29 15:12:01.971   316  8297 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f76f0 on input port
08-29 15:12:01.971   316  8297 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7790 on input port
08-29 15:12:01.971   316  8297 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7830 on input port
08-29 15:12:01.971   316  8297 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7880 on input port
08-29 15:12:01.971   316  8297 V OMXCodec: allocateBuffersOnPort portIndex=1
08-29 15:12:01.971   316  8297 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-29 15:12:01.972   316  8297 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on output port
08-29 15:12:01.972   316  8297 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
08-29 15:12:01.972   316  8297 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
08-29 15:12:01.972   316  8297 V OMXCodec: [OMX.google.vorbis.decoder] allocated bu,ffer 0xb54f7b00 on output port
08-29 15:12:01.972   316  8297 V OMXCodec: init() mAsyncCompletion wait!!! 
08-29 15:12:01.972   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-29 15:12:01.972   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-29 15:12:01.972   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-29 15:12:01.972   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-29 15:12:01.972   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-29 15:12:01.972   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-29 15:12:01.972   316  8297 V OMXCodec: init() mAsyncCompletion wait free! 
08-29 15:12:01.972   316  8297 V AwesomePlayer: finishAsyncPrepare_l() 
08-29 15:12:01.972   316  8297 V AudioCache: notify(0xb1432380, 5, 0, 0)
08-29 15:12:01.972   316  8297 V AudioCache: ignored
08-29 15:12:01.972   316  8297 V AudioCache: notify(0xb1432380, 1, 0, 0)
08-29 15:12:01.972   316  8297 V AudioCache: prepared
08-29 15:12:01.973   316  2154 V AudioCache: wait - success
08-29 15:12:01.973   316  2154 V MediaPlayerService: start
08-29 15:12:01.973   316  2154 V AwesomePlayer: play_l() 
08-29 15:12:01.974   316  2154 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-29 15:12:01.974   316  2154 V AwesomePlayer: createAudioPlayer_l
08-29 15:12:01.974   316  2154 V AwesomePlayer: seekAudioIfNecessary_l() 
08-29 15:12:01.974   316  2154 V AwesomePlayer: startAudioPlayer_l() 
08-29 15:12:01.974   316  2154 D AudioPlayer: start of Playback, useOffload 0
08-29 15:12:01.974   316  2154 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-29 15:12:01.974   316  2154 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-29 15:12:01.976   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-29 15:12:01.976   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-29 15:12:01.976   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-29 15:12:01.976   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-29 15:12:01.976   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-29 15:12:01.976   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-29 15:12:01.976   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884448
08-29 15:12:01.976   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 15:12:01.976   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884688
08-29 15:12:01.976   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 15:12:01.976   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884768
08-29 15:12:01.976   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 15:12:01.976   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884928
08-29 15:12:01.976   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,08-29 15:12:01.976   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-29 15:12:01.976   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-29 15:12:01.976   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-29 15:12:01.976   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-29 15:12:01.976   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-29 15:12:01.976   316  8299 V OMXCodec: allocateBuffersOnPort portIndex=1
08-29 15:12:01.976   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-29 15:12:01.976   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
08-29 15:12:01.976   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
08-29 15:12:01.976   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on output port
,08-29 15:12:01.976   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c1290 on output port
08-29 15:12:01.977   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-29 15:12:01.977   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-29 15:12:01.978   316  2154 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-29 15:12:01.978   316  2154 V AudioCache: notify(0xb1432380, 6, 0, 0)
08-29 15:12:01.978   316  2154 V AudioCache: ignored
08-29 15:12:01.978   316  2154 V MediaPlayerService: wait for playback complete
08-29 15:12:01.979   316  8300 V AudioCache: write(0xb16e1000, 4096)
08-29 15:12:01.979   316  8300 V AudioCache: memcpy(0xaf006000, 0xb16e1000, 4096)
08-29 15:12:01.981   316  8300 V AudioCache: write(0xb16e1000, 4096)
,08-29 15:12:01.981   316  8300 V AudioCache: memcpy(0xaf007000, 0xb16e1000, 4096)
08-29 15:12:01.981   316  8300 V AudioCache: write(0xb16e1000, 4096)
08-29 15:12:01.981   316  8300 V AudioCache: memcpy(0xaf008000, 0xb16e1000, 4096)
08-29 15:12:01.982   316  8300 V AudioCache: write(0xb16e1000, 4096)
08-29 15:12:01.982   316  8300 V AudioCache: memcpy(0xaf009000, 0xb16e1000, 4096)
08-29 15:12:01.982   316  8300 V AudioCache: write(0xb16e1000, 4096)
08-29 15:12:01.982   316  8300 V AudioCache: memcpy(0xaf00a000, 0xb16e1000, 4096)
,08-29 15:12:01.995   316  8300 V AudioCache: write(0xb16e1000, 4096)
,08-29 15:12:01.995   316  8300 V AudioCache: memcpy(0xaf00b000, 0xb16e1000, 4096)
08-29 15:12:01.995   316  8300 V AudioCache: write(0xb16e1000, 4096)
,08-29 15:12:01.995   316  8300 V AudioCache: memcpy(0xaf00c000, 0xb16e1000, 4096)
,08-29 15:12:01.996   316  8300 V AudioCache: write(0xb16e1000, 4096)
08-29 15:12:01.996   316  8300 V AudioCache: memcpy(0xaf00d000, 0xb16e1000, 4096)
08-29 15:12:01.997   316  8300 V AudioCache: write(0xb16e1000, 4096)
08-29 15:12:01.997   316  8300 V AudioCache: memcpy(0xaf00e000, 0xb16e1000, 4096)
08-29 15:12:01.998   316  8300 V AudioCache: write(0xb16e1000, 4096)
08-29 15:12:01.998   316  8300 V AudioCache: memcpy(0xaf00f000, 0xb16e1000, 4096)
,08-29 15:12:01.999   316  8300 V AudioCache: write(0xb16e1000, 4096)
,08-29 15:12:01.999   316  8300 V AudioCache: memcpy(0xaf010000, 0xb16e1000, 4096)
08-29 15:12:02.000   316  8300 V AudioCache: write(0xb16e1000, 4096)
08-29 15:12:02.000   316  8300 V AudioCache: memcpy(0xaf011000, 0xb16e1000, 4096)
08-29 15:12:02.001   316  8300 V AudioCache: write(0xb16e1000, 4096)
08-29 15:12:02.001   316  8300 V AudioCache: memcpy(0xaf012000, 0xb16e1000, 4096)
08-29 15:12:02.001   316  8300 V AudioCache: write(0xb16e1000, 4096)
08-29 15:12:02.001   316  8300 V AudioCache: memcpy(0xaf013000, 0xb16e1000, 4096)
,08-29 15:12:02.002   316  8300 V AudioCache: write(0xb16e1000, 4096)
08-29 15:12:02.002   316  8300 V AudioCache: memcpy(0xaf014000, 0xb16e1000, 4096)
08-29 15:12:02.003   316  8300 V AudioCache: write(0xb16e1000, 4096)
08-29 15:12:02.003   316  8300 V AudioCache: memcpy(0xaf015000, 0xb16e1000, 4096)
08-29 15:12:02.004   316  8300 V AudioCache: write(0xb16e1000, 4096)
08-29 15:12:02.004   316  8300 V AudioCache: memcpy(0xaf016000, 0xb16e1000, 4096)
08-29 15:12:02.004   316  8300 V AudioCache: write(0xb16e1000, 4096)
08-29 15:12:02.005   316  8300 V AudioCache: memcpy(0xaf017000, 0xb16e1000, 4096)
08-29 15:12:02.005   316  8300 V AudioCache: write(0xb16e1000, 4096)
08-29 15:12:02.005   316  8300 V AudioCache: memcpy(0xaf018000, 0xb16e1000, 4096)
08-29 15:12:02.006   316  8300 V AudioCache: write(0xb16e1000, 4096)
08-29 15:12:02.006   316  8300 V AudioCache: memcpy(0xaf019000, 0xb16e1000, 4096)
08-29 15:12:02.007   316  8300 V AudioCache: write(0xb16e1000, 4096)
08-29 15:12:02.007   316  8300 V AudioCache: memcpy(0xaf01a000, 0xb16e1000, 4096)
08-29 15:12:02.007   316  8300 V AudioCache: write(0xb16e1000, 4096)
08-29 15:12:02.007   316  8300 V AudioCache: memcpy(0xaf01b000, 0xb16e1000, 4096)
08-29 15:12:02.008   316  8300 V AudioCache: write(0xb16e1000, 4096)
08-29 15:12:02.008   316  8300 V AudioCache: memcpy(0xaf01c000, 0xb16e1000, 4096)
08-29 15:12:02.008   316  8300 V AudioCache: write(0xb16e1000, 4096)
08-29 15:12:02.009   316  8300 V AudioCache: memcpy(0xaf01d000, 0xb16e1000, 4096)
08-29 15:12:02.009   316  8300 V AudioCache: write(0xb16e1000, 4096)
08-29 15:12:02.009   316  8300 V AudioCache: memcpy(0xaf01e000, 0xb16e1000, 4096)
08-29 15:12:02.010   316  8300 V AudioCache: write(0xb16e1000, 4096)
08-29 15:12:02.010   316  8300 V AudioCache: memcpy(0xaf01f000, 0xb16e1000, 4096)
08-29 15:12:02.012   316  8300 V AudioCache: write(0xb16e1000, 4096)
08-29 15:12:02.012   316  8300 V AudioCache: memcpy(0xaf020000, 0xb16e1000, 4096)
08-29 15:12:02.012   316  8300 V AudioCache: write(0xb16e1000, 4096)
08-29 15:12:02.012   316  8300 V AudioCache: memcpy(0xaf021000, 0xb16e1000, 4096)
08-29 15:12:02.013   316  8300 V AudioCache: write(0xb16e1000, 4096)
08-29 15:12:02.013   316  8300 V AudioCache: memcpy(0xaf022000, 0xb16e1000, 4096)
08-29 15:12:02.014   316  8300 V AudioCache: write(0xb16e1000, 4096)
08-29 15:12:02.014   316  8300 V AudioCache: memcpy(0xaf023000, 0xb16e1000, 4096)
08-29 15:12:02.014   316  8300 V AudioCache: write(0xb16e1000, 4096)
,08-29 15:12:02.014   316  8300 V AudioCache: memcpy(0xaf024000, 0xb16e1000, 4096)
08-29 15:12:02.015   316  8300 V AudioCache: write(0xb16e1000, 4096)
08-29 15:12:02.015   316  8300 V AudioCache: memcpy(0xaf025000, 0xb16e1000, 4096)
,08-29 15:12:02.016   316  8300 V AudioCache: write(0xb16e1000, 4096)
08-29 15:12:02.016   316  8300 V AudioCache: memcpy(0xaf026000, 0xb16e1000, 4096)
08-29 15:12:02.016   316  8300 V AudioCache: write(0xb16e1000, 4096)
08-29 15:12:02.016   316  8300 V AudioCache: memcpy(0xaf027000, 0xb16e1000, 4096)
08-29 15:12:02.016   316  8300 V AudioCache: write(0xb16e1000, 4096)
08-29 15:12:02.016   316  8300 V AudioCache: memcpy(0xaf028000, 0xb16e1000, 4096)
08-29 15:12:02.016   316  8300 V AudioCache: write(0xb16e1000, 4096)
08-29 15:12:02.016   316  8300 V AudioCache: memcpy(0xaf029000, 0xb16e1000, 4096)
,08-29 15:12:02.018   316  8300 V AudioCache: write(0xb16e1000, 4096)
08-29 15:12:02.018   316  8300 V AudioCache: memcpy(0xaf02a000, 0xb16e1000, 4096)
08-29 15:12:02.018   316  8300 V AudioCache: write(0xb16e1000, 4096)
08-29 15:12:02.018   316  8300 V AudioCache: memcpy(0xaf02b000, 0xb16e1000, 4096)
08-29 15:12:02.018   316  8300 V AudioCache: write(0xb16e1000, 4096)
08-29 15:12:02.018   316  8300 V AudioCache: memcpy(0xaf02c000, 0xb16e1000, 4096)
08-29 15:12:02.018   316  8300 V AudioCache: write(0xb16e1000, 4096)
08-29 15:12:02.019   316  8300 V AudioCache: memcpy(0xaf02d000, 0xb16e1000, 4096)
,08-29 15:12:02.021   316  8300 V AudioCache: write(0xb16e1000, 4096)
08-29 15:12:02.021   316  8300 V AudioCache: memcpy(0xaf02e000, 0xb16e1000, 4096)
08-29 15:12:02.021   316  8300 V AudioCache: write(0xb16e1000, 4096)
08-29 15:12:02.021   316  8300 V AudioCache: memcpy(0xaf02f000, 0xb16e1000, 4096)
08-29 15:12:02.021   316  8300 V AudioCache: write(0xb16e1000, 4096)
08-29 15:12:02.021   316  8300 V AudioCache: memcpy(0xaf030000, 0xb16e1000, 4096)
08-29 15:12:02.021   316  8300 V AudioCache: write(0xb16e1000, 4096)
08-29 15:12:02.021   316  8300 V AudioCache: memcpy(0xaf031000, 0xb16e1000, 4096)
08-29 15:12:02.022   316  8300 V AudioCache: write(0xb16e1000, 4096)
08-29 15:12:02.022   316  8300 V AudioCache: memcpy(0xaf032000, 0xb16e1000, 4096)
08-29 15:12:02.023   316  8300 V AudioCache: write(0xb16e1000, 4096)
08-29 15:12:02.023   316  8300 V AudioCache: memcpy(0xaf033000, 0xb16e1000, 4096)
08-29 15:12:02.025   316  8300 V AudioCache: write(0xb16e1000, 4096)
08-29 15:12:02.025   316  8300 V AudioCache: memcpy(0xaf034000, 0xb16e1000, 4096)
08-29 15:12:02.025   316  8300 V AudioCache: write(0xb16e1000, 4096)
08-29 15:12:02.025   316  8300 V AudioCache: memcpy(0xaf035000, 0xb16e1000, 4096)
08-29 15:12:02.025   316  8300 V AudioCache: write(0xb16e1000, 4096)
08-29 15:12:02.026   316  8300 V AudioCache: memcpy(0xaf036000, 0xb16e1000, 4096)
08-29 15:12:02.026   316  8300 V AudioCache: write(0xb16e1000, 4096)
08-29 15:12:02.026   316  8300 V AudioCache: memcpy(0xaf037000, 0xb16e1000, 4096)
08-29 15:12:02.026   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-29 15:12:02.026   316  8300 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-29 15:12:02.026   316  8300 V AwesomePlayer: postAudioEOS() 
08-29 15:12:02.026   316  8300 V AudioCache: write(0xb16e1000, 280)
08-29 15:12:02.027   316  8300 V AudioCache: memcpy(0xaf038000, 0xb16e1000, 280)
08-29 15:12:02.028   316  8297 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-29 15:12:02.028   316  8297 V AwesomePlayer: onStreamDone
08-29 15:12:02.028   316  8297 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-29 15:12:02.028   316  8297 V AudioCache: notify(0xb1432380, 2, 0, 0)
08-29 15:12:02.028   316  8297 V AudioCache: playback complete
08-29 15:12:02.028   316  8297 V AwesomePlayer: pause_l() 
08-29 15:12:02.028   316  8297 V AudioCache: notify(0xb1432380, 7, 0, 0)
08-29 15:12:02.028   316  8297 V AudioCache: ignored
08-29 15:12:02.028   316  8297 V AwesomePlayer: cancelPlayerEvents
08-29 15:12:02.028   316  2154 V AudioCache: wait - success
08-29 15:12:02.028   316  2154 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-29 15:12:02.028   316  8297 D AudioPlayer: Pause Playback at 1068125
08-29 15:12:02.028   316  2154 V AwesomePlayer: reset_l() 
08-29 15:12:02.028   316  2154 V AudioCache: notify(0xb1432380, 8, 0, 0)
08-29 15:12:02.028   316  2154 V AudioCache: ignored
08-29 15:12:02.028   316  2154 V AwesomePlayer: cancelPlayerEvents
08-29 15:12:02.028   316  2154 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-29 15:12:02.028   316  2154 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-29 15:12:02.028   316  2154 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-29 15:12:02.028   316  2154 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-29 15:12:02.028   316  2154 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-29 15:12:02.029   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-29 15:12:02.029   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-29 15:12:02.029   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-29 15:12:02.029   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7880 on port 0
08-29 15:12:02.029   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-29 15:12:02.029   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7830 on port 0
08-29 15:12:02.029   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-29 15:12:02.029   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7790 on port 0
08-29 15:12:02.029   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-29 15:12:02.029   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f76f0 on port 0
08-29 15:12:02.029   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-29 15:12:02.029   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-29 15:12:02.029   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57c1290 on port 1
08-29 15:12:02.029   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-29 15:12:02.029   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 1
08-29 15:12:02.029   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-29 15:12:02.029   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 1
08-29 15:12:02.029   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-29 15:12:02.029   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 1
08-29 15:12:02.029   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 15:12:02.029   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-29 15:12:02.029   316  2154 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-29 15:12:02.029   316  2154 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-29 15:12:02.031   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-29 15:12:02.031   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-29 15:12:02.031   316  8299 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-29 15:12:02.031   316  2154 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-29 15:12:02.031   316  2154 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-29 15:12:02.031   316  2154 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-29 15:12:02.032   316  2154 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-29 15:12:02.032   316  2154 D AudioPlayer: AudioPlayer releasing audio source
08-29 15:12:02.032   316  2154 D AudioPlayer: AudioPlayer done releasing audio source
08-29 15:12:02.032   316  2154 V AwesomePlayer: reset_l() 
08-29 15:12:02.032   316  2154 V AwesomePlayer: cancelPlayerEvents
08-29 15:12:02.032   316  2154 V AwesomePlayer: ~AwesomePlayer call
08-29 15:12:02.032   316  2154 V AwesomePlayer: reset_l() 
08-29 15:12:02.032   316  2154 V AwesomePlayer: cancelPlayerEvents
08-29 15:12:02.033  8234  8294 V SoundPool: close(31)
08-29 15:12:02.033  8234  8294 V SoundPool: pointer = 0x9fe70000, size = 205080, sampleRate = 48000, numChannels = 2
08-29 15:12:02.041  8234  8234 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-29 15:12:02.041  8234  8234 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-29 15:12:02.043  8234  8234 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:2789
08-29 15:12:02.045  8172  8172 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 15:12:02.048  8172  8172 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 15:12:02.049  8172  8172 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 15:12:02.051  8172  8172 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 15:12:02.053  8172  8172 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 15:12:02.055  8172  8172 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 15:12:02.058  8172  8172 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 15:12:02.061  8172  8172 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 15:12:02.063  8172  8172 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 15:12:02.075  8172  8172 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 15:12:02.176  8295  8295 D AndroidRuntime: 
08-29 15:12:02.176  8295  8295 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-29 15:12:02.181  8295  8295 D AndroidRuntime: CheckJNI is OFF
,08-29 15:12:02.341  8295  8295 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-29 15:12:02.355  1034  1112 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
,08-29 15:12:02.358  1034  1112 I ActivityManager: Killing 6671:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-29 15:12:02.395  1034  1376 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 15:12:02.396  1034  1376 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 15:12:02.396  1034  1376 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 15:12:02.397  1034  1376 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 15:12:02.397  1034  1376 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 15:12:02.399  1034  1376 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 15:12:02.399  1034  1452 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-29 15:12:02.399  1034  1452 D ConnectivityService: identical MTU - not setting
08-29 15:12:02.399  1034  1452 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-29 15:12:02.399  1034  1452 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-29 15:12:02.400  1034  1452 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 15:12:02.400  1034  1452 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 15:12:02.400  1034  1452 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 15:12:02.401  1587  2055 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-29 15:12:02.436  1034  2011 I WindowState: WIN DEATH: Window{8153db2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-29 15:12:02.437  7810  7810 I UEI.SmartControl: Supports setup maps: true
08-29 15:12:02.437  1034  1440 D WifiService: Client connection lost with reason: 4
08-29 15:12:02.445  1034  2011 D InputDispatcher: Window went away: Window{8153db2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-29 15:12:02.445  7810  7810 D UEI.SmartControl: QS start statue = true Error code = 0
08-29 15:12:02.445  7810  7810 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-29 15:12:02.445  7810  7810 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-29 15:12:02.445  7810  7810 I UEI.SmartControl: ### init IR Blaster...
08-29 15:12:02.450  7810  7810 D serial_port: Configuring serial port
08-29 15:12:02.451  7810  7810 E UEI.SmartControl: UEIBLaster setting for 616
08-29 15:12:02.451  7810  7810 I UEI.SmartControl: Setting serial record hearder size = 2
08-29 15:12:02.451  7810  7810 I UEI.SmartControl: configuring settings for MAXQ616
08-29 15:12:02.451  7810  7810 I UEI.SmartControl: Get version...
,08-29 15:12:02.468  7810  8317 D UEI.SmartControl: serial port data available: 21
,08-29 15:12:02.494  7810  7810 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-29 15:12:02.494  7810  7810 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-29 15:12:02.494  7810  7810 I UEI.SmartControl: QS saving settings...
08-29 15:12:02.495  7810  7810 D UEI.SmartControl: IR Blaster version: 25672567
,08-29 15:12:02.511  7810  8317 D UEI.SmartControl: serial port data available: 4
,08-29 15:12:02.540   310   891 D LGDataListener: argv[0]=dsqncommand
,08-29 15:12:02.540   310   891 D LGDataListener: argv[1]=wlan0
08-29 15:12:02.540   310   891 D LGDataListener: argv[2]=1
08-29 15:12:02.540   310   891 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-29 15:12:02.541  1034  1114 D DSQN    : DSQM DsqnNotification wlan0  1
08-29 15:12:02.541  1034  1114 D DSQN    : start to monitor internet connection
08-29 15:12:02.542  7810  8320 I UEI.SmartControl: Device manager: loading config....
08-29 15:12:02.542  7810  8320 D UEI.SmartControl: ----------- loading internal config...
08-29 15:12:02.545  7810  7810 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-29 15:12:02.551  7810  8320 E UEI.SmartControl: Loading SETTINGS...
08-29 15:12:02.559  7810  8320 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-29 15:12:02.578  1034  1112 I ActivityManager:   Force finishing activity ActivityRecord{2b782e52 u0 com.test.thalitest/.MainActivity t6}
,08-29 15:12:02.579  7810  8319 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-29 15:12:02.579  7810  8319 D UEI.SmartControl: -----service ready thread exits
,08-29 15:12:02.621   338   350 E GBMv2   : DFP En is all cleared set to be enabled
,08-29 15:12:02.627  1034  1874 W ActivityManager: Spurious death for ProcessRecord{2460f90b 6671:com.test.thalitest/u0a118}, curProc for 6671: null
08-29 15:12:02.628  1925  1942 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-29 15:12:02.628  1925  1942 D SplitWindowPolicy: topRunningActivity=ActivityInfo{87a8513 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-29 15:12:02.629  7810  7810 E UEI.SmartControl: Services init done
08-29 15:12:02.629  7810  7810 D UEI.SmartControl: QS Service init finished
08-29 15:12:02.630  7810  7810 D UEI.SmartControl: QS Service version name: 2.1.91
08-29 15:12:02.630  7810  7810 D UEI.SmartControl: QS Service version code: 201091
08-29 15:12:02.631  7810  7810 D UEI.SmartControl: Service requested: Control
08-29 15:12:02.631  1925  3267 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-29 15:12:02.631  1925  3267 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3068a350 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-29 15:12:02.632  1034  1136 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-29 15:12:02.635  1034  1136 I ActivityManager:   Force finishing activity ActivityRecord{2b782e52 u0 com.test.thalitest/.MainActivity t6 f}
08-29 15:12:02.635  1034  1136 W ActivityManager: Duplicate finish request for ActivityRecord{2b782e52 u0 com.test.thalitest/.MainActivity t6 f}
,08-29 15:12:02.659  2016  2016 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-29 15:12:02.662  8234  8234 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-29 15:12:02.662  7810  7810 D UEI.SmartControl: Internal service binding...
08-29 15:12:02.663  2016  2016 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-29 15:12:02.663  7810  7831 I UEI.SmartControl: ------ IControl API: 11
08-29 15:12:02.663  7810  7831 D UEI.SmartControl: File observer start...
08-29 15:12:02.664  7810  7831 E UEI.SmartControl: IR Port is disabled: false
08-29 15:12:02.664  7810  7831 D UEI.SmartControl: Starting file observer...
08-29 15:12:02.665  7810  7831 I UEI.SmartControl: Registering callback...
08-29 15:12:02.667  7810  7917 I UEI.SmartControl: ------ IControl API: 19
08-29 15:12:02.668  7810  7917 I UEI.SmartControl: Registering Services Ready callback...
08-29 15:12:02.668  7810  7917 I UEI.SmartControl: Notify client services are ready...
08-29 15:12:02.670  8234  8253 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,08-29 15:12:02.673  1587  1587 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-29 15:12:02.675  1979  1979 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
,08-29 15:12:02.675  1034  1364 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-29 15:12:02.676  3783  3783 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-29 15:12:02.678  8234  8292 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-29 15:12:02.679  7702  7702 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-29 15:12:02.679  8234  8292 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-29 15:12:02.679  7702  7702 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-29 15:12:02.679  8234  8234 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-29 15:12:02.679  8234  8234 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-29 15:12:02.682  7810  7825 I UEI.SmartControl: ------ IControl API: 8
08-29 15:12:02.683  8234  8234 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-29 15:12:02.684  8234  8234 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-29 15:12:02.684  8234  8234 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-29 15:12:02.684  8234  8234 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-29 15:12:02.687  8234  8234 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-29 15:12:02.687  2473  2663 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-29 15:12:02.688  8234  8234 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-29 15:12:02.691  2016  2016 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-29 15:12:02.693  2016  2085 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-29 15:12:02.696  4494  4494 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-29 15:12:02.697  4494  4494 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-29 15:12:02.697  4494  4494 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-29 15:12:02.698  8172  8172 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-29 15:12:02.697  4494  4494 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-29 15:12:02.698  4494  4494 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 15:12:02.698  4494  4494 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 15:12:02.698  4494  4494 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-29 15:12:02.698  4494  4494 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 15:12:02.698  4494  4494 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 15:12:02.698  4494  4494 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 15:12:02.698  4494  4494 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 15:12:02.698  4494  4494 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 15:12:02.721  1034  8189 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 29 Aug 2016 13:12:02 GMT], X-Android-Received-Millis=[1472476322721], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472476322539]}
08-29 15:12:02.721  1034  8189 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-29 15:12:02.721  1034  8189 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
,08-29 15:12:02.723  1034  1452 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-29 15:12:02.723  1034  1452 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-29 15:12:02.723  1034  1452 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 15:12:02.724  1034  1452 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 15:12:02.724  1034  1452 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-29 15:12:02.724  1034  1452 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-29 15:12:02.724  1034  1452 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-29 15:12:02.724  1034  1452 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 15:12:02.724  1034  1452 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 15:12:02.724  1034  1452 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 15:12:02.724  1034  1452 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 15:12:02.724  1034  1452 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-29 15:12:02.725  1034  1376 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 15:12:02.725  1034  1376 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 15:12:02.726  1587  2055 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-29 15:12:02.746  4603  4603 I art     : Explicit concurrent mark sweep GC freed 8178(467KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 515us total 100.863ms
08-29 15:12:02.746  1034  1962 V SIM_STK : Menu title from STK is T-Mobile
,08-29 15:12:02.752  1034  1034 D administrator: Handling package changes for user 0
08-29 15:12:02.752  1801  1801 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-29 15:12:02.769  1890  1890 D ActionManagerService: notifyUserLog: 1000003
08-29 15:12:02.770  2016  2016 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
,08-29 15:12:02.773  2016  2016 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-29 15:12:02.775  2016  2016 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-29 15:12:02.776  1587  1587 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-29 15:12:02.778  2016  2016 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-29 15:12:02.782  3783  4488 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
,08-29 15:12:02.787  8234  8234 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-29 15:12:02.790  1587  1637 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-29 15:12:02.790  1587  1637 D KeyguardModel: createShortcutInfo...
08-29 15:12:02.791  1890  1890 D ActionManagerService: notifyUserLog: 1000004
08-29 15:12:02.792  3783  4488 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-29 15:12:02.792  2016  2016 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-29 15:12:02.793  2198  2198 I ConfigService: onCreate
08-29 15:12:02.794  2198  2198 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-29 15:12:02.794  3783  3799 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,08-29 15:12:02.800  1587  1637 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-29 15:12:02.800  1587  1637 D KeyguardModel: createShortcutInfo...
08-29 15:12:02.801  2198  2198 I ConfigService: onBind returning update interface
08-29 15:12:02.803  1587  1587 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-29 15:12:02.803  1587  1587 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-29 15:12:02.803  8234  8234 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-29 15:12:02.806  1587  1637 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
,08-29 15:12:02.807  1587  1637 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 15:12:02.807  1587  1637 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-29 15:12:02.808  1854  1854 D SplitUIManager: split_name #11 / not available #0
08-29 15:12:02.808  1587  1637 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-29 15:12:02.808  1854  1854 D SplitUIService: removed split : 
08-29 15:12:02.808  1587  1637 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 15:12:02.808  1587  1637 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-29 15:12:02.813  1587  1637 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-29 15:12:02.813  1587  1637 D KeyguardModel: createShortcutInfo...
08-29 15:12:02.819  1034  1957 V SIM_STK : Menu title from STK is T-Mobile
08-29 15:12:02.819  1034  1957 V SIM_STK : Menu title from STK is T-Mobile
,08-29 15:12:02.825  1587  1637 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-29 15:12:02.825  1587  1637 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 15:12:02.826  1587  1637 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 15:12:02.826  1587  1637 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-29 15:12:02.831  2198  2198 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-29 15:12:02.831  2198  2198 I ConfigService: onBind returning config service
08-29 15:12:02.832  1801  1801 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-29 15:12:02.832  2016  2016 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-29 15:12:02.832  2016  2016 I GBoardWebViewUtils: , create_time: 1430832262123
08-29 15:12:02.832  2016  2016 I GBoardWebViewUtils: , expire_time: 0
08-29 15:12:02.832  2016  2016 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-29 15:12:02.832  2016  2016 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-29 15:12:02.832  2016  2016 I GBoardWebViewUtils: , display: false
08-29 15:12:02.832  2016  2016 I GBoardWebViewUtils: , animation: false }
08-29 15:12:02.833  2016  2016 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-29 15:12:02.833  2016  2016 I GBoardWebViewUtils: , create_time: 1430832262287
08-29 15:12:02.833  2016  2016 I GBoardWebViewUtils: , expire_time: 0
08-29 15:12:02.833  2016  2016 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-29 15:12:02.833  2016  2016 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-29 15:12:02.833  2016  2016 I GBoardWebViewUtils: , display: false
08-29 15:12:02.833  2016  2016 I GBoardWebViewUtils: , animation: false }
08-29 15:12:02.833  2016  2016 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472216587976
08-29 15:12:02.833  2016  2016 I GBoardWebViewUtils: , create_time: 1472216588858
08-29 15:12:02.833  2016  2016 I GBoardWebViewUtils: , expire_time: 0
08-29 15:12:02.833  2016  2016 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-29 15:12:02.833  2016  2016 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-29 15:12:02.833  2016  2016 I GBoardWebViewUtils: , display: false
08-29 15:12:02.833  2016  2016 I GBoardWebViewUtils: , animation: false }
,08-29 15:12:02.842  1836  1836 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 15:12:02.842  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-29 15:12:02.842  2016  8333 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-29 15:12:02.844  1587  1637 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-29 15:12:02.844  1587  1637 D KeyguardModel: createShortcutInfo...
08-29 15:12:02.849  1801  1801 I ConfigFetchService: service connected
08-29 15:12:02.849  1801  1801 I ConfigClient: service connected
,08-29 15:12:02.851  1854  1854 D SplitUIManager: split_name #11 / not available #0
08-29 15:12:02.851  1854  1854 I SplitUIService: split app #11
08-29 15:12:02.855  2016  2016 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-29 15:12:02.856  2016  2016 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-29 15:12:02.862  1587  1637 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 15:12:02.862  1587  1637 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-29 15:12:02.862  1587  1637 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-29 15:12:02.862  1587  1637 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-29 15:12:02.863  1587  1637 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 15:12:02.863  1587  1637 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-29 15:12:02.866  1587  1637 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-29 15:12:02.866  1587  1637 D KeyguardModel: createShortcutInfo...
08-29 15:12:02.875  1034  2032 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-29 15:12:02.877  7702  7702 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-29 15:12:02.877  7702  7702 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-29 15:12:02.877  7702  7702 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-29 15:12:02.877  7702  7702 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-29 15:12:02.877  7702  7702 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-29 15:12:02.877  7702  7702 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 15:12:02.877  7702  7702 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-29 15:12:02.877  7702  7702 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-29 15:12:02.877  7702  7702 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-29 15:12:02.877  7702  7702 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 15:12:02.877  7702  7702 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-29 15:12:02.892  2198  2198 I ConfigService: onDestroy
,08-29 15:12:02.902  1801  8335 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-29 15:12:02.905  1034  1598 V SIM_STK : Menu title from STK is T-Mobile
,08-29 15:12:02.909  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 15:12:02.910  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 15:12:02.911  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 15:12:02.912  1587  1587 D KeyguardModel: handleShortcutListChanged...
08-29 15:12:02.912  1587  1587 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-29 15:12:02.915  1587  1637 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-29 15:12:02.915  1587  1637 D KeyguardModel: createShortcutInfo...
08-29 15:12:02.916  1587  1637 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-29 15:12:02.916  1587  1637 D KeyguardModel: createShortcutInfo...
08-29 15:12:02.918  1587  1637 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 15:12:02.918  1587  1637 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-29 15:12:02.919  1587  1637 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-29 15:12:02.919  1587  1637 D KeyguardModel: createShortcutInfo...
,08-29 15:12:02.920  1034  1111 W InputMethodInfo: Duplicated subtype definition found: , voice
08-29 15:12:02.922  1587  1637 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 15:12:02.922  1587  1637 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-29 15:12:02.925  1587  1637 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-29 15:12:02.925  1587  1637 D KeyguardModel: createShortcutInfo...
08-29 15:12:02.926  1587  1637 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 15:12:02.926  1587  1637 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-29 15:12:02.928  1587  1637 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-29 15:12:02.928  1587  1637 D KeyguardModel: createShortcutInfo...
,08-29 15:12:02.943  1034  1034 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-29 15:12:02.943  1034  1034 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-29 15:12:02.943  1034  1034 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-29 15:12:02.944  2016  2016 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
,08-29 15:12:02.946  1034  1562 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-29 15:12:02.953  5960  8340 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-29 15:12:02.963  1801  8342 I PeopleContactsSync: CP2 sync disabled
,08-29 15:12:02.973  1801  8341 W GmsApplication: Using Auth Proxy for data requests.
08-29 15:12:02.976  1801  4734 I Icing   : doRemovePackageData com.test.thalitest
,08-29 15:12:02.979  1587  1587 D KeyguardModel: handleShortcutListChanged...
08-29 15:12:02.979  1587  1587 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-29 15:12:02.982  1801  8341 W GmsApplication: Using Auth Proxy for data requests.
,08-29 15:12:03.059  2198  2382 I art     : Explicit concurrent mark sweep GC freed 7042(407KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 906us total 21.953ms
,08-29 15:12:03.065   330   415 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-29 15:12:03.066  3182  8345 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-29 15:12:03.067  7094  7094 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-29 15:12:03.067  2016  2016 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-29 15:12:03.070  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 15:12:03.071  1034  1560 I ActivityManager: Killing 7309:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-29 15:12:03.072  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-29 15:12:03.074  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-29 15:12:03.075  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-29 15:12:03.077  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,08-29 15:12:03.095  2016  2016 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
,08-29 15:12:03.095  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 15:12:03.098  2016  2152 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-29 15:12:03.099  2016  2152 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-29 15:12:03.114  1034  1136 I art     : Explicit concurrent mark sweep GC freed 87603(4MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 1.819ms total 233.163ms
,08-29 15:12:03.114  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-29 15:12:03.115  2016  2016 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-29 15:12:03.115  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 15:12:03.121  1034  1111 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 15:12:03.122  2016  2016 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-29 15:12:03.128  1034  1111 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-29 15:12:03.146  8295  8295 D AndroidRuntime: Shutting down VM
,08-29 15:12:03.166  1034  1929 W libprocessgroup: failed to open /acct/uid_10005/pid_7309/cgroup.procs: No such file or directory
,08-29 15:12:03.170  2565  2565 D [Concierge]Service: onStartCommand(). Type : 8
08-29 15:12:03.170  2565  2565 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-29 15:12:03.171  1034  1117 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{9ab7a80 u0 com.lge.launcher2/.Launcher t5} time:143437
08-29 15:12:03.171  2565  2565 D [Concierge]Service: Update widget ID : 11
08-29 15:12:03.172  2016  2016 D [Concierge]WidgetView: change position of spinner
08-29 15:12:03.178  2331  8348 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-29 15:12:03.192  1034  1560 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8349 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-29 15:12:03.194  2565  2565 D [Concierge]Service: onStartCommand(). Type : 0
08-29 15:12:03.194  2016  2016 I [Concierge]WidgetView: initWebView(). Time : 1472476323194
08-29 15:12:03.206  2016  2016 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 514106123
08-29 15:12:03.206  2016  2016 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-29 15:12:03.206  2016  2016 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-29 15:12:03.209  2016  2016 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@1877477c
08-29 15:12:03.209  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
,08-29 15:12:03.210  2016  2016 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-29 15:12:03.210  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 15:12:03.214  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-29 15:12:03.215  2016  2016 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-29 15:12:03.218  2016  2016 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-29 15:12:03.218  2016  2016 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-29 15:12:03.220  2016  2016 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472476208104, New one : 1472476323194
08-29 15:12:03.220  2016  2016 D [Concierge]WidgetView: Unregister all receivers
08-29 15:12:03.220  2016  2016 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-29 15:12:03.220  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 15:12:03.222  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-29 15:12:03.223  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
,08-29 15:12:03.224  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-29 15:12:03.225  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-29 15:12:03.226  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-29 15:12:03.227  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 15:12:03.227  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 15:12:03.237  8349  8349 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 15:12:03.237  8349  8349 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 15:12:03.238  8349  8349 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-29 15:12:03.238  8349  8349 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-29 15:12:03.258  2016  2016 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-29 15:12:03.267  2016  2016 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,08-29 15:12:03.271  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
,08-29 15:12:03.273  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 15:12:03.293  2016  2016 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@22e88c84 time:143560
,08-29 15:12:03.293  8349  8349 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-29 15:12:03.301  8349  8349 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-29 15:12:03.321  8349  8349 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-29 15:12:03.339  8349  8349 D LgDataFeature: LgDataFeature() Constructor: none
,08-29 15:12:03.339  8349  8349 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 15:12:03.384  1034  1136 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8371 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-29 15:12:03.413  8349  8349 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
08-29 15:12:03.428  1034  1874 I ActivityManager: Killing 7735:com.google.android.talk/u0a72 (adj 15): empty #17
,08-29 15:12:03.443  2016  2016 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-29 15:12:03.478  2016  2872 I GBoardtInterface: onReloaded()
,08-29 15:12:03.480  2016  2016 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-29 15:12:03.494  1034  1874 I ActivityManager: Killing 7861:com.android.vending/u0a44 (adj 15): empty #17
,08-29 15:12:03.524  1979  1979 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-29 15:12:03.524  1979  1979 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-29 15:12:03.525  1034  1991 W libprocessgroup: failed to open /acct/uid_10072/pid_7735/cgroup.procs: No such file or directory
,08-29 15:12:03.526  1034  1049 W libprocessgroup: failed to open /acct/uid_10044/pid_7861/cgroup.procs: No such file or directory
08-29 15:12:03.528  3783  3799 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-29 15:12:03.528  1979  1979 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-29 15:12:03.533  3783  3798 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,08-29 15:12:03.533  8172  8172 E SQLiteDatabase: Failed to open database '/data/data/com.wsandroid.suite.lge/databases/CLOUDREPUTATIONDB'.
08-29 15:12:03.533  8172  8172 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 15:12:03.533  8172  8172 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 15:12:03.533  8172  8172 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-29 15:12:03.533  8172  8172 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-29 15:12:03.533  8172  8172 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 15:12:03.533  8172  8172 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 15:12:03.533  8172  8172 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 15:12:03.533  8172  8172 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-29 15:12:03.533  8172  8172 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-29 15:12:03.533  8172  8172 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-29 15:12:03.533  8172  8172 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-29 15:12:03.533  8172  8172 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-29 15:12:03.533  8172  8172 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 15:12:03.533  8172  8172 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 15:12:03.533  8172  8172 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.i.a(Unknown Source)
08-29 15:12:03.533  8172  8172 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.ad.a(Unknown Source)
08-29 15:12:03.533  8172  8172 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.ab.j(Unknown Source)
08-29 15:12:03.533  8172  8172 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.k.b(Unknown Source)
08-29 15:12:03.533  8172  8172 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.k.a(Unknown Source)
08-29 15:12:03.533  8172  8172 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.CloudScanReceiver.onReceive(Unknown Source)
08-29 15:12:03.533  8172  8172 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2586)
08-29 15:12:03.533  8172  8172 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
08-29 15:12:03.533  8172  8172 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1360)
08-29 15:12:03.533  8172  8172 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:12:03.533  8172  8172 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-29 15:12:03.533  8172  8172 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 15:12:03.533  8172  8172 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 15:12:03.533  8172  8172 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 15:12:03.533  8172  8172 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 15:12:03.533  8172  8172 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 15:12:03.536  8172  8172 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,08-29 15:12:03.539  7519  7519 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
08-29 15:12:03.544  1890  1890 D ActionManagerService: notifyUserLog: 1000001
08-29 15:12:03.544  1034  1376 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 link=72 tx=56.5, 0.0, 0.0  rx=50.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-697458984] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-29 15:12:03.544  6892  6892 D PackageIntentReceiver: Not supported Hotkey customization function 
08-29 15:12:03.544  1034  1376 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 link=72 tx=56.5, 0.0, 0.0  rx=50.0 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-697458984] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-29 15:12:03.544  1034  1376 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-29 15:12:03.546  3783  4488 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-29 15:12:03.546  3783  4488 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-29 15:12:03.548  1890  1890 D ActionManagerService: notifyUserLog: 1000001

```
