#### Test 79426650eeb77ae_thali05_LGE-LG-D855 Logs


```
--------- beginning of main
08-05 01:29:16.218  5932  5932 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
08-05 01:29:16.237  5932  5932 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-05 01:29:16.238  5932  5932 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-05 01:29:16.253  5932  5932 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-05 01:29:16.254  5932  5932 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
--------- beginning of system
08-05 01:29:16.265  1032  1048 I ActivityManager: Killing 4785:com.lge.clock/u0a10 (adj 15): empty #17
08-05 01:29:16.296  1032  1886 W libprocessgroup: failed to open /acct/uid_10010/pid_4785/cgroup.procs: No such file or directory
08-05 01:29:16.309  4561  5972 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-05 01:29:16.358  1032  1904 V SIM_STK : Menu title from STK is T-Mobile
08-05 01:29:16.371  1032  1922 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5975 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-05 01:29:16.387  3478  3493 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-05 01:29:16.391  3478  3493 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@34ebdcd2 on behalf of 5932
08-05 01:29:16.404  5932  5932 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
08-05 01:29:16.433  5932  5932 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-05 01:29:16.484  4561  5972 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 175 ms] updated apps [took 175 ms] 
08-05 01:29:16.532  5975  5975 D DocsApplication: Installing DEX configuration.
08-05 01:29:16.551  5975  5975 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
08-05 01:29:16.554  5975  5975 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{bb3fb41 com.google.android.apps.docs}
08-05 01:29:16.569  5975  5975 D TAG     : onCreate()
08-05 01:29:16.585  5975  5975 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
08-05 01:29:17.150  1602  1602 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-05 01:29:17.151  1602  1602 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-05 01:29:17.164  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 01:29:17.165  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 01:29:17.165  1032  1542 D WifiController: battery changed pluggedType: 2
08-05 01:29:17.166  1941  2124 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-05 01:29:17.166  1941  2124 D LEDHandler: Battery Level Remaining: 100%
08-05 01:29:17.166  1941  2124 D LEDHandler: Battery Temp: 288, mChargingStatus=5, mChargingStop=false
08-05 01:29:17.167  1602  1602 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 288
08-05 01:29:17.167  1602  1602 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-05 01:29:17.169  3844  3948 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-05 01:29:17.169  1602  1602 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-05 01:29:17.170  5135  5135 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-05 01:29:17.432  6013  6013 D AndroidRuntime: 
08-05 01:29:17.432  6013  6013 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-05 01:29:17.436  6013  6013 D AndroidRuntime: CheckJNI is OFF
08-05 01:29:17.484  1816  4632 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
08-05 01:29:17.562  1816  4632 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-05 01:29:17.601  6013  6013 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-05 01:29:17.606  1032  1047 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-05 01:29:17.616  1941  1958 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-05 01:29:17.620  1032  1047 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-05 01:29:17.621  1816  4632 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
08-05 01:29:17.621  1032  1047 D ActivityManager: setTaskToReturnTo : TaskRecord{2a15494c #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-05 01:29:17.621  1032  1047 D ActivityManager: setTaskToReturnTo : TaskRecord{2a15494c #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-05 01:29:17.622  1032  1047 D WindowStateEx: AppWindowTokenEx init.. 
08-05 01:29:17.623   342   352 E GBMv2   : DFP En is all cleared set to be enabled
08-05 01:29:17.643  1032  1047 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6039 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-05 01:29:17.644  6013  6013 D AndroidRuntime: Shutting down VM
08-05 01:29:17.668  5975  5975 D LgDataFeature: LgDataFeature() Constructor: none
08-05 01:29:17.668  5975  5975 D LgDataFeature: LgDataFeature() Constructor Done, null
08-05 01:29:17.676  1032  1032 V ActivityManager: Display changed displayId=0
08-05 01:29:17.677  1851  1851 D DSDPConnection: Display #0 changed.
08-05 01:29:17.694  1941  3904 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-05 01:29:17.694  1941  3904 D SplitWindowPolicy: topRunningActivity=ActivityInfo{f5dd0b7 co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
08-05 01:29:17.695  1941  3904 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-05 01:29:17.695  1941  3904 D SplitWindowPolicy: topRunningActivity=ActivityInfo{513d024 co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
08-05 01:29:17.758  6039  6039 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-05 01:29:17.814  5975  5975 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
08-05 01:29:17.823  6039  6039 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-05 01:29:17.847  1032  2051 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6065 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-05 01:29:17.855  6039  6039 I LibraryLoader: Loading: webviewchromium
08-05 01:29:17.858  6039  6039 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 8469-8473)
08-05 01:29:17.858  6039  6039 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-05 01:29:17.860   347   347 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 244us total 11.430ms
08-05 01:29:17.871   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 201us total 10.922ms
,08-05 01:29:17.882   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 199us total 9.843ms
08-05 01:29:17.888  6039  6039 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d6d95c3}
,08-05 01:29:17.889  6039  6039 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-05 01:29:17.889  6039  6039 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-05 01:29:17.901  6039  6039 I BrowserStartupController: Initializing chromium process, renderers=0
,08-05 01:29:17.902  6039  6039 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-05 01:29:17.903  6065  6065 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
08-05 01:29:17.907  6039  6084 W chromium: [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
08-05 01:29:17.910  6065  6065 I LockScreenSettings: New app installed broadcast received ..
08-05 01:29:17.912  6039  6039 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-05 01:29:17.912   322  1384 V AudioPolicyService: registerClient() client 0xb57d4fc0, uid 10118
08-05 01:29:17.912  6039  6039 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-05 01:29:17.912  6039  6039 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,08-05 01:29:17.914  6065  6065 I LockScreenSettings: Number of installed packages  1
08-05 01:29:17.920  1032  1094 D BluetoothManagerService: Message: 20
08-05 01:29:17.920  1032  1094 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2f789902:true
08-05 01:29:17.925  6039  6039 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 01:29:17.925  6039  6039 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 01:29:17.925  6039  6039 I Adreno-EGL: Build Date: 12/12/14 금
08-05 01:29:17.925  6039  6039 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-05 01:29:17.925  6039  6039 I Adreno-EGL: Remote Branch: 
08-05 01:29:17.925  6039  6039 I Adreno-EGL: Local Patches: 
08-05 01:29:17.925  6039  6039 I Adreno-EGL: Reconstruct Branch: 
08-05 01:29:17.943  1032  1573 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6096 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-05 01:29:17.943  1032  1573 I ActivityManager: Killing 4980:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-05 01:29:17.986  1032  1979 W libprocessgroup: failed to open /acct/uid_10085/pid_4980/cgroup.procs: No such file or directory
08-05 01:29:17.994  1032  1048 I ActivityManager: Killing 5135:com.lge.bnr/1000 (adj 15): empty #17
08-05 01:29:18.010  6096  6096 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 01:29:18.036  1032  1047 W libprocessgroup: failed to open /acct/uid_1000/pid_5135/cgroup.procs: No such file or directory
08-05 01:29:18.045  6039  6094 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
08-05 01:29:18.047  6039  6039 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-05 01:29:18.066  6039  6039 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-05 01:29:18.071  6039  6039 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-05 01:29:18.074  6039  6039 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-05 01:29:18.078  6039  6039 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-05 01:29:18.078  6039  6039 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-05 01:29:18.093  6039  6039 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-05 01:29:18.101  6039  6039 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-05 01:29:18.101  6039  6039 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-05 01:29:18.134  6039  6123 D OpenGLRenderer: Render dirty regions requested: true
08-05 01:29:18.135  6039  6123 I OpenGLRenderer: Initialized EGL, version 1.4
08-05 01:29:18.170  6039  6123 D OpenGLRenderer: Enabling debug mode 0
08-05 01:29:18.179  6039  6039 D Atlas   : Validating map...
08-05 01:29:18.183  1032  1922 D SplitWindow: check instance of lgWin Window{32475dac u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-05 01:29:18.193  1032  1090 W ActivityManager: Activity pause timeout for ActivityRecord{242d8d95 u0 com.test.thalitest/.MainActivity t40}
08-05 01:29:18.221  6039  6121 D LgDataFeature: LgDataFeature() Constructor: none
08-05 01:29:18.221  6039  6121 D LgDataFeature: LgDataFeature() Constructor Done, null
08-05 01:29:18.349  1032  1095 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +656ms (total +725ms)
08-05 01:29:18.349  1032  1095 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{242d8d95 u0 com.test.thalitest/.MainActivity t40} time:118964
08-05 01:29:18.356  6039  6039 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@308d36e time:118971
08-05 01:29:18.467  1032  2033 V SIM_STK : Menu title from STK is T-Mobile
08-05 01:29:18.487  6039  6039 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-05 01:29:18.487  6039  6039 I chromium: 
08-05 01:29:18.524  1032  1699 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6146 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-05 01:29:18.537  6039  6039 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-05 01:29:18.600  6146  6146 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-05 01:29:18.600  6146  6146 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
08-05 01:29:18.604  6039  6121 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-05 01:29:18.604  6039  6121 I chromium: 
08-05 01:29:18.644  1032  1573 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6164 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-05 01:29:18.645  1032  1573 I ActivityManager: Killing 5291:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-05 01:29:18.662  5265  5265 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-05 01:29:18.662  5265  5265 W System.err: android.os.DeadObjectException
08-05 01:29:18.662  5265  5265 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-05 01:29:18.662  5265  5265 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-05 01:29:18.662  5265  5265 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-05 01:29:18.662  5265  5265 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-05 01:29:18.662  5265  5265 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-05 01:29:18.662  5265  5265 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-05 01:29:18.662  5265  5265 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-05 01:29:18.662  5265  5265 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-05 01:29:18.662  5265  5265 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-05 01:29:18.662  5265  5265 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-05 01:29:18.662  5265  5265 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 01:29:18.662  5265  5265 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 01:29:18.662  5265  5265 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-05 01:29:18.662  5265  5265 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-05 01:29:18.663  5265  5265 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-05 01:29:18.663  5265  5265 W System.err: android.os.DeadObjectException
08-05 01:29:18.663  5265  5265 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-05 01:29:18.663  5265  5265 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-05 01:29:18.663  5265  5265 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-05 01:29:18.663  5265  5265 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-05 01:29:18.663  5265  5265 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-05 01:29:18.663  5265  5265 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-05 01:29:18.663  5265  5265 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-05 01:29:18.663  5265  5265 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-05 01:29:18.663  5265  5265 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-05 01:29:18.663  5265  5265 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
,08-05 01:29:18.663  5265  5265 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 01:29:18.663  5265  5265 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
,08-05 01:29:18.663  5265  5265 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-05 01:29:18.663  5265  5265 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-05 01:29:18.663  5265  5265 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-05 01:29:18.663  5265  5265 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-05 01:29:18.705  6039  6181 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435137024
,08-05 01:29:18.718  6039  6181 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-05 01:29:18.718  6039  6181 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-05 01:29:18.718  6039  6181 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-05 01:29:18.718  6039  6181 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-05 01:29:18.718  6039  6181 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-05 01:29:18.718  6039  6181 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34ebdcd2 added. We now have 1 listener(s)
08-05 01:29:18.769  1032  1048 W libprocessgroup: failed to open /acct/uid_1000/pid_5291/cgroup.procs: No such file or directory
,08-05 01:29:18.770  1032  1048 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-05 01:29:18.779  5265  5265 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-05 01:29:18.780  5265  5265 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-05 01:29:18.791  1032  2051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-05 01:29:18.797  6039  6181 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-05 01:29:18.800  6039  6181 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 01:29:18.801  6039  6181 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 01:29:18.802  6039  6181 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 01:29:18.808  6039  6181 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-05 01:29:18.808  6039  6181 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-05 01:29:18.808  6039  6181 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-05 01:29:18.808  6039  6181 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-05 01:29:18.808  6039  6181 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-05 01:29:18.808  6039  6181 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-05 01:29:18.808  6039  6181 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-05 01:29:18.808  6039  6181 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-05 01:29:18.808  6039  6181 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-05 01:29:18.808  6039  6181 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-05 01:29:18.808  6039  6181 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-05 01:29:18.808  6039  6181 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-05 01:29:18.808  6039  6181 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-05 01:29:18.808  6039  6181 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-05 01:29:18.809  6039  6181 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a7b8059 added. We now have 1 listener(s)
08-05 01:29:18.809  6039  6181 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-05 01:29:18.814  1032  1542 D WifiService: New client listening to asynchronous messages
08-05 01:29:18.818  6039  6181 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 01:29:18.818  6039  6181 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-05 01:29:18.821  6039  6181 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-05 01:29:18.821  6039  6181 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-05 01:29:18.821  6039  6181 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-05 01:29:18.848  1032  1922 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6184 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-05 01:29:18.848  5265  5265 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-05 01:29:18.849  6039  6181 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-05 01:29:18.850  1032  1868 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 01:29:18.851  6039  6181 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-05 01:29:18.857  6039  6181 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-05 01:29:18.857  6039  6181 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 01:29:18.857  6039  6181 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 01:29:18.857  6039  6181 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 01:29:18.857  6039  6181 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 01:29:18.857  6039  6181 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 01:29:18.857  6039  6181 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 01:29:18.857  6039  6181 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 01:29:18.857  6039  6181 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 01:29:18.857  6039  6181 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-05 01:29:18.857  6039  6181 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 01:29:18.859  6039  6181 I io.jxcore.node.LifeCycleMonitor: start: OK
08-05 01:29:18.859  6039  6039 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 01:29:18.866  6164  6164 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
08-05 01:29:18.887  6039  6039 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-05 01:29:18.899  6164  6164 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-05 01:29:18.900  1032  2014 I ActivityManager: Killing 5462:com.google.android.gm/u0a64 (adj 15): empty #17
08-05 01:29:18.970  1032  2033 I art     : Explicit concurrent mark sweep GC freed 27471(1399KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.167ms total 76.646ms
,08-05 01:29:18.987  6184  6184 D UEI.SmartControl: Quickset Services start...
08-05 01:29:18.988  6184  6184 I UEI.SmartControl: Manufacture = LGE
08-05 01:29:18.988  6184  6184 D UEI.SmartControl: Id = LGNevo
08-05 01:29:18.988  6184  6184 D UEI.SmartControl: File observer start...
08-05 01:29:18.989  6184  6184 E UEI.SmartControl: IR Port is disabled: false
08-05 01:29:18.989  6184  6184 D UEI.SmartControl: Starting file observer...
08-05 01:29:18.989  6184  6184 D UEI.SmartControl: Extracting JNI libs...
08-05 01:29:18.989  6184  6184 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,08-05 01:29:19.036  6184  6184 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-05 01:29:19.036  6184  6184 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-05 01:29:19.037  6184  6184 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-05 01:29:19.048  1032  1904 W libprocessgroup: failed to open /acct/uid_10064/pid_5462/cgroup.procs: No such file or directory
,08-05 01:29:19.059  6184  6184 I UEI.SmartControl: --- Selecting new region: 6
,08-05 01:29:19.061  6184  6184 I UEI.SmartControl: Model = LG-D855
08-05 01:29:19.062  6184  6184 D UEI.SmartControl: QS Service created
08-05 01:29:19.072  6184  6184 I UEI.SmartControl: Service initServices...
,08-05 01:29:19.075  6184  6184 D UEI.SmartControl: QS start get config
08-05 01:29:19.118  6184  6184 D UEI.SmartControl: Loading JNI Libs...
,08-05 01:29:19.195   342   354 E GBMv2   : DFP En is all cleared set to be enabled
08-05 01:29:19.195   342   354 E GBMv2   : Set value is all cleared set the max
08-05 01:29:19.195   342   354 I GBMv2   : DFP Enabled. Ignore VFP set
,08-05 01:29:19.487  6184  6184 I UEI.SmartControl: Supports setup maps: true
,08-05 01:29:19.492  6184  6184 D UEI.SmartControl: QS start statue = true Error code = 0
08-05 01:29:19.493  6184  6184 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-05 01:29:19.493  6184  6184 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-05 01:29:19.493  6184  6184 I UEI.SmartControl: ### init IR Blaster...
08-05 01:29:19.498  6184  6184 D serial_port: Configuring serial port
08-05 01:29:19.502  6184  6184 E UEI.SmartControl: UEIBLaster setting for 616
08-05 01:29:19.502  6184  6184 I UEI.SmartControl: Setting serial record hearder size = 2
08-05 01:29:19.502  6184  6184 I UEI.SmartControl: configuring settings for MAXQ616
08-05 01:29:19.502  6184  6184 I UEI.SmartControl: Get version...
,08-05 01:29:19.517  6184  6206 D UEI.SmartControl: serial port data available: 21
,08-05 01:29:19.546  6184  6184 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-05 01:29:19.546  6184  6184 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-05 01:29:19.546  6184  6184 I UEI.SmartControl: QS saving settings...
,08-05 01:29:19.548  6184  6184 D UEI.SmartControl: IR Blaster version: 25672567
08-05 01:29:19.566  6184  6206 D UEI.SmartControl: serial port data available: 4
,08-05 01:29:19.612  6184  6209 I UEI.SmartControl: Device manager: loading config....
08-05 01:29:19.613  6184  6209 D UEI.SmartControl: ----------- loading internal config...
08-05 01:29:19.613  6184  6184 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-05 01:29:19.615  6184  6184 E UEI.SmartControl: Services init done
,08-05 01:29:19.615  6184  6184 D UEI.SmartControl: QS Service init finished
08-05 01:29:19.625  6184  6184 D UEI.SmartControl: QS Service version name: 2.1.91
08-05 01:29:19.626  6184  6184 D UEI.SmartControl: QS Service version code: 201091
08-05 01:29:19.627  6184  6209 E UEI.SmartControl: Loading SETTINGS...
08-05 01:29:19.630  6184  6184 D UEI.SmartControl: Service requested: Control
,08-05 01:29:19.633  5265  5265 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-05 01:29:19.636  1032  1959 I ActivityManager: Killing 5265:com.lge.qremote/u0a112 (adj 15): empty #17
08-05 01:29:19.639  6184  6201 I UEI.SmartControl: ------ IControl API: 11
08-05 01:29:19.640  6184  6201 I UEI.SmartControl: Registering callback...
08-05 01:29:19.642  6184  6209 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-05 01:29:19.663  6184  6208 I UEI.SmartControl: Notify AllClients services are ready: 0
08-05 01:29:19.663  6184  6208 D UEI.SmartControl: -----service ready thread exits
,08-05 01:29:19.737  1032  2051 W libprocessgroup: failed to open /acct/uid_10112/pid_5265/cgroup.procs: No such file or directory
,08-05 01:29:19.740  6184  6184 D UEI.SmartControl: Internal service binding...
08-05 01:29:19.905  6039  6199 W jxcore-log: Initializing JXcore engine
08-05 01:29:19.905  6039  6199 W jxcore-log: JXcore engine is ready
,08-05 01:29:19.950  6199  6199 W Thread-677: type=1400 audit(0.0:160): avc: denied { ioctl } for path="socket:[10497]" dev="sockfs" ino=10497 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-05 01:29:19.950  6199  6199 W Thread-677: type=1400 audit(0.0:161): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-05 01:29:19.950  6199  6199 W Thread-677: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[8480]" dev="sockfs" ino=8480 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-05 01:29:19.950  6199  6199 W Thread-677: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-05 01:29:19.950  6199  6199 W Thread-677: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[29082]" dev="sockfs" ino=29082 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-05 01:29:19.977  6039  6199 W jxcore-log: Starting JXcore engine
,08-05 01:29:20.077  6039  6199 W jxcore-log: Platform android
08-05 01:29:20.077  6039  6199 W jxcore-log: 
08-05 01:29:20.077  6039  6199 W jxcore-log: Process ARCH arm
08-05 01:29:20.077  6039  6199 W jxcore-log: 
,08-05 01:29:20.289  6039  6199 I jxcore-log: JXcore Cordova bridge is ready!
08-05 01:29:20.289  6039  6199 I jxcore-log: 
08-05 01:29:20.290  6039  6199 W jxcore-log: JXcore engine is started
,08-05 01:29:20.303  6039  6181 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-05 01:29:20.307  6039  6039 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-05 01:29:21.775  5975  5975 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-05 01:29:21.782  1032  1904 I ActivityManager: Killing 5178:com.android.calendar/u0a13 (adj 15): empty #17
08-05 01:29:21.857  1032  1979 W libprocessgroup: failed to open /acct/uid_10013/pid_5178/cgroup.procs: No such file or directory
,08-05 01:29:22.742  5975  6057 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-05 01:29:23.436  1032  1047 I ActivityManager: Killing 4872:com.android.providers.calendar/u0a14 (adj 15): empty #17
,08-05 01:29:23.527  1032  1699 W libprocessgroup: failed to open /acct/uid_10014/pid_4872/cgroup.procs: No such file or directory
,08-05 01:29:24.590  6184  6207 D serial_port: close(fd = 25)
,08-05 01:29:24.597  6184  6207 I UEI.SmartControl: Serial port is closed.
08-05 01:29:24.607  6184  6210 D UEI.SmartControl: Internal timer expired: 1
08-05 01:29:24.608  6184  6210 D UEI.SmartControl: unbind internal service
,08-05 01:29:24.614  6184  6184 D UEI.SmartControl: Service.onUnbind: IControl
08-05 01:29:24.614  6184  6184 D UEI.SmartControl: Service.onDestroy
08-05 01:29:24.615  6184  6184 D UEI.SmartControl: Lock is in USE false
08-05 01:29:24.615  6184  6184 D UEI.SmartControl: unbind internal service
08-05 01:29:24.615  6184  6184 I UEI.SmartControl: Serial port is closed.
08-05 01:29:24.615  6184  6184 I UEI.SmartControl: Serial port is closed.
08-05 01:29:24.615  6184  6184 D UEI.SmartControl: Blaster closed
08-05 01:29:24.616  6184  6184 D UEI.SmartControl: Shut down QS...
08-05 01:29:24.616  6184  6184 D UEI.SmartControl: Stopping QS lib
08-05 01:29:24.616  6184  6184 D UEI.SmartControl: QS lib stop result = true
08-05 01:29:24.617  6184  6184 D UEI.SmartControl: Stopped QS lib
08-05 01:29:24.618  6184  6184 D UEI.SmartControl: Stopped file observer...
08-05 01:29:24.618  6184  6184 D UEI.SmartControl: QS shutdown complete
,08-05 01:29:29.329  1032  1090 I ActivityManager: Waited long enough for: ServiceRecord{24ac0f19 u0 com.google.android.gms/.wearable.service.WearableService}
,08-05 01:29:34.086  6039  6199 E jxcore  : Error!: Cannot find module '../thalilogger'
08-05 01:29:34.086  6039  6199 E jxcore  : Stack: [{"_fileName":"module.js","_functionName":"$w._oldRes","_lineNumber":"802","_columnNumber":"9","_msg":"    at $w._oldRes@module.js:802:9"},{"_fileName":"module.js","_functionName":"$w._resolveFilename","_lineNumber":"1771","_columnNumber":"1","_msg":"    at $w._resolveFilename@module.js:1771:1"},{"_fileName":"module.js","_functionName":"$w._load","_lineNumber":"362","_columnNumber":"4","_msg":"    at $w._load@module.js:362:4"},{"_fileName":"module.js","_functionName":"$w.prototype.require","_lineNumber":"477","_columnNumber":"8","_msg":"    at $w.prototype.require@module.js:477:8"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"495","_columnNumber":"8","_msg":"    at require@module.js:495:8"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/thaliMobile.js","_functionName":"","_lineNumber":"5","_columnNumber":"14","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/thaliMobile.js:5:14"}]
,08-05 01:29:34.101  6039  6039 I chromium: [INFO:CONSOLE(57)] "app.js file failed to load : "Cannot find module '../thalilogger'\nError: Cannot find module '../thalilogger'\n    at $w._oldRes@module.js:802:9\n    at $w._resolveFilename@module.js:1771:1\n    at $w._load@module.js:362:4\n    at $w.prototype.require@module.js:477:8\n    at require@module.js:495:8\n    at @/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/thaliMobile.js:5:14"", source: file:///android_asset/www/js/thali_main.js (57)
,08-05 01:29:34.104  6039  6039 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
08-05 01:29:34.108  1032  2014 I ActivityManager: Killing 5504:com.google.android.talk/u0a72 (adj 15): empty #17
08-05 01:29:34.150  6039  6039 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-05 01:29:34.154  6039  6039 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
08-05 01:29:34.154  1032  1573 W libprocessgroup: failed to open /acct/uid_10072/pid_5504/cgroup.procs: No such file or directory
08-05 01:29:34.156  6039  6039 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 01:29:34.156  6039  6039 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 01:29:34.156  6039  6039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 01:29:34.156  6039  6039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 01:29:34.157  6039  6039 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34ebdcd2 removed from the list
08-05 01:29:34.157  6039  6039 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 01:29:34.157  6039  6039 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a7b8059 removed from the list
08-05 01:29:34.157  6039  6039 D io.jxcore.node.ConnectivityMonitor: stop
08-05 01:29:34.157  6039  6039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
08-05 01:29:34.162  6039  6181 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 57ms. Plugin should use CordovaInterface.getThreadPool().
,08-05 01:29:34.188   342   352 E GBMv2   : DFP En is all cleared set to be enabled
08-05 01:29:34.192  1941  1957 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-05 01:29:34.193  1941  1957 D SplitWindowPolicy: topRunningActivity=ActivityInfo{12b2c78d co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
08-05 01:29:34.194  1941  1958 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-05 01:29:34.194  1941  1958 D SplitWindowPolicy: topRunningActivity=ActivityInfo{12fa1d42 co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
08-05 01:29:34.199  6039  6039 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-05 01:29:34.207  2034  2034 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-05 01:29:34.209  2034  2034 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-05 01:29:34.209  6039  6039 W ScreenOrientationListener: Removing an inexistent observer!
,08-05 01:29:34.211  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-05 01:29:34.213  2034  2128 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-05 01:29:34.220  1905  1905 D ActionManagerService: notifyUserLog: 1000003
08-05 01:29:34.221  3705  4466 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
,08-05 01:29:34.222  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-05 01:29:34.224  2034  2034 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-05 01:29:34.225  2034  2034 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-05 01:29:34.260  1032  1979 D InputDispatcher: Window went away: Window{32475dac u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-05 01:29:34.283  1032  1090 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6233 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-05 01:29:34.285  2034  2034 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-05 01:29:34.288  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-05 01:29:34.290  3705  3721 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-05 01:29:34.292  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-05 01:29:34.292  2034  2034 I GBoardWebViewUtils: , create_time: 1430832262123
08-05 01:29:34.292  2034  2034 I GBoardWebViewUtils: , expire_time: 0
08-05 01:29:34.292  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-05 01:29:34.292  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-05 01:29:34.292  2034  2034 I GBoardWebViewUtils: , display: false
08-05 01:29:34.292  2034  2034 I GBoardWebViewUtils: , animation: false }
08-05 01:29:34.292  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-05 01:29:34.292  2034  2034 I GBoardWebViewUtils: , create_time: 1430832262287
08-05 01:29:34.292  2034  2034 I GBoardWebViewUtils: , expire_time: 0
08-05 01:29:34.292  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-05 01:29:34.292  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-05 01:29:34.292  2034  2034 I GBoardWebViewUtils: , display: false
08-05 01:29:34.292  2034  2034 I GBoardWebViewUtils: , animation: false }
08-05 01:29:34.292  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1469801564706
08-05 01:29:34.292  2034  2034 I GBoardWebViewUtils: , create_time: 1469801565454
08-05 01:29:34.292  2034  2034 I GBoardWebViewUtils: , expire_time: 0
08-05 01:29:34.292  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide.html?id=guide_1111111111116_1469801564706&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-05 01:29:34.292  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-05 01:29:34.292  2034  2034 I GBoardWebViewUtils: , display: false
08-05 01:29:34.292  2034  2034 I GBoardWebViewUtils: , animation: false }
,08-05 01:29:34.296  1905  1905 D ActionManagerService: notifyUserLog: 1000004
08-05 01:29:34.297  3705  4466 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-05 01:29:34.301  2034  6249 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,08-05 01:29:34.329  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-05 01:29:34.348  6233  6233 I art     : Almond Protected OAT
,08-05 01:29:34.388  6233  6233 D WeatherApplication: removeAccount
08-05 01:29:34.389  6233  6233 D WeatherApplication: Account.length = 0
,08-05 01:29:34.390  6233  6233 E WeatherApplication: OPERATOR:OPEN
08-05 01:29:34.393  6233  6233 D WeatherAncestor: 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 1:29:34
08-05 01:29:34.395  6233  6233 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-05 01:29:34.395  6233  6233 D Weather.Utils: 2 : All the weather widget is gone.
08-05 01:29:34.396  6233  6233 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-05 01:29:34.397  6233  6233 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-05 01:29:34.397  6233  6233 D Weather.Utils: 2 : All the weather widget is gone.
08-05 01:29:34.398  6233  6233 D WeatherAncestor: 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 1:29:34
08-05 01:29:34.399  1032  1868 I ActivityManager: Killing 2129:com.lge.music/u0a34 (adj 15): empty #17
,08-05 01:29:34.411   322  1384 V AudioFlinger: 2129 died, releasing its sessions
08-05 01:29:34.411   322  1384 V AudioFlinger:  pid 1851 @ 0
08-05 01:29:34.411   322  1384 V AudioFlinger:  pid 3426 @ 1
08-05 01:29:34.411   322  1384 V AudioFlinger:  pid 3426 @ 2
08-05 01:29:34.416  6230  6230 D AndroidRuntime: 
08-05 01:29:34.416  6230  6230 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-05 01:29:34.418  6230  6230 D AndroidRuntime: CheckJNI is OFF
,08-05 01:29:34.456  1032  1047 W libprocessgroup: failed to open /acct/uid_10034/pid_2129/cgroup.procs: No such file or directory
,08-05 01:29:34.458  2034  2034 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-05 01:29:34.520  6230  6230 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-05 01:29:34.536  1032  1090 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-05 01:29:34.537  1032  1090 I ActivityManager: Killing 6039:com.test.thalitest/u0a118 (adj 9): stop com.test.thalitest
,08-05 01:29:34.549  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-05 01:29:34.553  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 01:29:34.555  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-05 01:29:34.557  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-05 01:29:34.558  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
,08-05 01:29:34.560  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-05 01:29:34.580  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-05 01:29:34.581  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-05 01:29:34.581  2034  2829 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
,08-05 01:29:34.581  2034  2829 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-05 01:29:34.599  1032  1542 D WifiService: Client connection lost with reason: 4
,08-05 01:29:34.601  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-05 01:29:34.603  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-05 01:29:34.603  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-05 01:29:34.650  2034  2034 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,08-05 01:29:34.759  1032  1106 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
,08-05 01:29:34.806  1032  1095 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3eb13431 u0 com.lge.launcher2/.Launcher t39} time:135422
08-05 01:29:34.808  1602  1602 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-05 01:29:34.809  1032  1090 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{38b767e0 u0 android.intent.action.PACKAGE_REMOVED} to ReceiverList{63302bc 1851 com.android.phone/1001/u-1 remote:3f64eaf}: process crashing
08-05 01:29:34.811  3844  3844 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-05 01:29:34.811  3844  3844 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-05 01:29:34.813  1997  1997 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-05 01:29:34.814  3705  3705 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,08-05 01:29:34.817  2670  2670 D [Concierge]Service: onStartCommand(). Type : 8
,08-05 01:29:34.817  2670  2670 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-05 01:29:34.819  2034  2034 D [Concierge]WidgetView: change position of spinner
08-05 01:29:34.826  4561  4561 I art     : Explicit concurrent mark sweep GC freed 298(25KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 666us total 47.721ms
08-05 01:29:34.826  1032  1945 W ActivityManager: Spurious death for ProcessRecord{3efdaa99 6039:com.test.thalitest/u0a118}, curProc for 6039: null
08-05 01:29:34.829  4962  4962 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,08-05 01:29:34.846  1032  1089 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-05 01:29:34.860  1032  1979 V SIM_STK : Menu title from STK is T-Mobile
08-05 01:29:34.875  4441  4441 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-05 01:29:34.875  4441  4441 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-05 01:29:34.875  4441  4441 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-05 01:29:34.875  4441  4441 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
,08-05 01:29:34.875  4441  4441 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-05 01:29:34.875  4441  4441 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-05 01:29:34.875  4441  4441 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-05 01:29:34.875  4441  4441 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-05 01:29:34.875  4441  4441 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 01:29:34.875  4441  4441 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 01:29:34.875  4441  4441 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-05 01:29:34.875  4441  4441 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-05 01:29:34.875  2558  2755 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-05 01:29:34.885  2670  2670 D [Concierge]Service: Update widget ID : 11
08-05 01:29:34.885  1032  1433 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-05 01:29:34.887  2034  2034 I [Concierge]WidgetView: initWebView(). Time : 1470353374887
,08-05 01:29:34.890  1032  2033 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{1a755755 u0 android.intent.action.UID_REMOVED} to ReceiverList{63302bc 1851 com.android.phone/1001/u-1 remote:3f64eaf}: process crashing
08-05 01:29:34.890  2670  2670 D [Concierge]Service: onStartCommand(). Type : 0
08-05 01:29:34.894  1602  1602 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-05 01:29:34.901  1602  1660 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-05 01:29:34.901  1602  1660 D KeyguardModel: createShortcutInfo...
,08-05 01:29:34.902  1816  1816 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-05 01:29:34.907  1602  1660 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-05 01:29:34.907  1602  1660 D KeyguardModel: createShortcutInfo...
08-05 01:29:34.909  2226  2226 I ConfigService: onCreate
08-05 01:29:34.909  2226  2226 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-05 01:29:34.910  1602  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 01:29:34.910  1602  1660 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-05 01:29:34.913  1602  1660 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-05 01:29:34.913  1602  1660 D KeyguardModel: createShortcutInfo...
08-05 01:29:34.913  1816  1816 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,08-05 01:29:34.917  2226  2226 I ConfigService: onBind returning update interface
08-05 01:29:34.920  1602  1602 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-05 01:29:34.920  1602  1602 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-05 01:29:34.927  2226  2226 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
,08-05 01:29:34.927  2226  2226 I ConfigService: onBind returning config service
08-05 01:29:34.929  2034  2034 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 1045115701
08-05 01:29:34.929  2034  2034 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-05 01:29:34.930  2034  2034 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-05 01:29:34.933  2034  2034 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@2e3d9842
08-05 01:29:34.933  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-05 01:29:34.934  1602  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 01:29:34.934  1602  1660 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-05 01:29:34.936  1602  1660 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-05 01:29:34.936  1602  1660 D KeyguardModel: createShortcutInfo...
08-05 01:29:34.938  2226  2226 I ConfigService: onDestroy
08-05 01:29:34.941  1816  6275 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-05 01:29:34.941  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-05 01:29:34.941  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-05 01:29:34.943  1602  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 01:29:34.943  1602  1660 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-05 01:29:34.944  1602  1660 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-05 01:29:34.944  1602  1660 D KeyguardModel: createShortcutInfo...
08-05 01:29:34.948  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-05 01:29:34.949  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-05 01:29:34.949  1869  1869 D SplitUIManager: split_name #11 / not available #0
08-05 01:29:34.950  1869  1869 D SplitUIService: removed split : 
08-05 01:29:34.950  2034  2034 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.PackageUpdateReceiver
08-05 01:29:34.951   318  6279 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-05 01:29:34.952  1032  1092 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-05 01:29:34.955  2034  2034 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-05 01:29:34.959  1602  1602 D KeyguardModel: handleShortcutListChanged...
08-05 01:29:34.959  1602  1602 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-05 01:29:34.960  1032  1032 I art     : Explicit concurrent mark sweep GC freed 14615(1058KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 3.864ms total 170.095ms
08-05 01:29:34.960  1032  1106 I art     : WaitForGcToComplete blocked for 71.792ms for cause Explicit
08-05 01:29:34.964  2034  2034 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1470353267701, New one : 1470353374887
08-05 01:29:34.964  2034  2034 D [Concierge]WidgetView: Unregister all receivers
08-05 01:29:34.965  2034  2034 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-05 01:29:34.965  2034  2034 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.PackageUpdateReceiver
08-05 01:29:34.965  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 01:29:34.967  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-05 01:29:34.968  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
,08-05 01:29:34.969  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-05 01:29:34.970  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-05 01:29:34.971  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-05 01:29:34.971  1032  1959 V SIM_STK : Menu title from STK is T-Mobile
08-05 01:29:34.971  1032  1959 V SIM_STK : Menu title from STK is T-Mobile
08-05 01:29:34.971  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 01:29:34.972  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 01:29:34.982  1602  1660 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-05 01:29:34.982  1602  1660 D KeyguardModel: createShortcutInfo...
,08-05 01:29:34.986  1602  1660 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-05 01:29:34.986  1602  1660 D KeyguardModel: createShortcutInfo...
08-05 01:29:34.987  1602  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 01:29:34.988  1602  1660 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-05 01:29:34.990  1869  1869 D SplitUIManager: split_name #11 / not available #0
08-05 01:29:34.990  1869  1869 I SplitUIService: split app #11
08-05 01:29:34.992  1602  1660 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-05 01:29:34.992  1602  1660 D KeyguardModel: createShortcutInfo...
08-05 01:29:34.995  1602  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-05 01:29:34.995  1602  1660 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-05 01:29:34.996  1602  1660 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-05 01:29:34.996  1602  1660 D KeyguardModel: createShortcutInfo...
08-05 01:29:34.997  1602  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 01:29:34.997  1602  1660 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-05 01:29:34.998  1602  1660 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-05 01:29:34.998  1602  1660 D KeyguardModel: createShortcutInfo...
08-05 01:29:35.012  1032  1032 D administrator: Handling package changes for user 0
08-05 01:29:35.013  2034  2034 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-05 01:29:35.015  1816  4632 I Icing   : doRemovePackageData com.test.thalitest
08-05 01:29:35.019  1816  6284 I PeopleContactsSync: CP2 sync disabled
08-05 01:29:35.025  2034  2034 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-05 01:29:35.025  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-05 01:29:35.026  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-05 01:29:35.036  1032  2033 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-05 01:29:35.038  3844  3844 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-05 01:29:35.038  3844  3844 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-05 01:29:35.038  3844  3844 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-05 01:29:35.038  3844  3844 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-05 01:29:35.038  3844  3844 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-05 01:29:35.038  3844  3844 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-05 01:29:35.038  3844  3844 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-05 01:29:35.038  3844  3844 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-05 01:29:35.038  3844  3844 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-05 01:29:35.038  3844  3844 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-05 01:29:35.038  3844  3844 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
,08-05 01:29:35.039   335   453 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-05 01:29:35.041  3093  6285 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-05 01:29:35.044  1602  1602 D KeyguardModel: handleShortcutListChanged...
08-05 01:29:35.044  1602  1602 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-05 01:29:35.046  1816  6282 W GmsApplication: Using Auth Proxy for data requests.
08-05 01:29:35.047  2034  2034 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1fcb8d73 time:135662
08-05 01:29:35.067  1816  6282 W GmsApplication: Using Auth Proxy for data requests.
,08-05 01:29:35.081  1032  1904 V SIM_STK : Menu title from STK is T-Mobile
08-05 01:29:35.082  1602  1618 I art     : Background sticky concurrent mark sweep GC freed 37354(2022KB) AllocSpace objects, 45(7MB) LOS objects, 5% free, 146MB/155MB, paused 5.567ms total 35.185ms
08-05 01:29:35.091  5593  6283 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-05 01:29:35.118  5832  5832 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-05 01:29:35.133  1032  1032 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
,08-05 01:29:35.133  1032  1032 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-05 01:29:35.138  1032  1032 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-05 01:29:35.139  2034  2034 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-05 01:29:35.139  1032  1576 D TaskPersister: removeObsoleteFile: deleting file=40_task.xml
08-05 01:29:35.142  5876  5876 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
08-05 01:29:35.143  2340  6288 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-05 01:29:35.151  1997  1997 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-05 01:29:35.151  1997  1997 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
,08-05 01:29:35.152  1997  1997 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
,08-05 01:29:35.155  4962  4962 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-05 01:29:35.181  1816  6277 I art     : Explicit concurrent mark sweep GC freed 14355(911KB) AllocSpace objects, 9(144KB) LOS objects, 51% free, 29MB/61MB, paused 1.025ms total 25.739ms
,08-05 01:29:35.184  1816  1828 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/history_query.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-05 01:29:35.184  1816  1828 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/help_responses.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-05 01:29:35.185  1816  1828 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/metrics.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-05 01:29:35.186  1032  1699 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=6290 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-05 01:29:35.197   342   354 E GBMv2   : DFP En is all cleared set to be enabled
08-05 01:29:35.197   342   354 E GBMv2   : Set value is all cleared set the max
08-05 01:29:35.197   342   354 I GBMv2   : DFP Enabled. Ignore VFP set
,08-05 01:29:35.260  6290  6290 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-05 01:29:35.260  6290  6290 W LG Account v2.2: No ProfileInfo entries
08-05 01:29:35.260  6290  6290 I LG Account v2.2: isEnabled: false
08-05 01:29:35.260  6290  6290 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-05 01:29:35.261  6290  6290 I Feature : [Lifetracker]Country: EU
08-05 01:29:35.261  6290  6290 I Feature : [Lifetracker]Operator: OPEN
08-05 01:29:35.261  6290  6290 I Feature : [Lifetracker]Ranking support: false
08-05 01:29:35.261  6290  6290 I Feature : [Lifetracker]Comfort support: false
08-05 01:29:35.261  6290  6290 I Feature : [Lifetracker]Accessory: true
08-05 01:29:35.261  6290  6290 I Feature : [Lifetracker]Health device: true
08-05 01:29:35.261  6290  6290 I Feature : [Lifetracker]Extra Pedometer: false
08-05 01:29:35.261  6290  6290 I Feature : [Lifetracker]Blood glucose device: false
08-05 01:29:35.261  6290  6290 I Feature : [Lifetracker]Device Number: 3
08-05 01:29:35.261  6290  6290 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
,08-05 01:29:35.268  1032  1106 I art     : Explicit concurrent mark sweep GC freed 12573(857KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 1.369ms total 194.539ms
08-05 01:29:35.284  2034  2034 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-05 01:29:35.289  1032  1868 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=6310 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-05 01:29:35.318  6310  6310 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 01:29:35.318  6310  6310 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-05 01:29:35.318  6310  6310 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 01:29:35.318  6310  6310 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-05 01:29:35.319  6310  6310 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-05 01:29:35.319  6310  6310 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-05 01:29:35.329  2034  2957 I GBoardtInterface: onReloaded()
08-05 01:29:35.331  2034  2034 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-05 01:29:35.332  3705  3721 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-05 01:29:35.333  1032  1089 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 01:29:35.335  3705  4438 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-05 01:29:35.338  1032  1089 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-05 01:29:35.340  1905  1905 D ActionManagerService: notifyUserLog: 1000001
08-05 01:29:35.341  3705  4466 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-05 01:29:35.341  3705  4466 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
,08-05 01:29:35.345  1905  1905 D ActionManagerService: notifyUserLog: 1000001
08-05 01:29:35.346  3705  4466 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-05 01:29:35.346  3705  4466 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-05 01:29:35.346  3705  4466 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-05 01:29:35.346  3705  4466 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-05 01:29:35.347  3705  3721 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-05 01:29:35.349  2034  2034 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-05 01:29:35.349  6230  6230 D AndroidRuntime: Shutting down VM
08-05 01:29:35.349  2034  2034 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-05 01:29:35.352  2034  2034 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-05 01:29:35.352  2034  2034 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-05 01:29:35.355  2034  2034 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1469801564706&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-05 01:29:35.355  2034  2034 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1469801564706&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,08-05 01:29:35.358  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-05 01:29:35.404  6310  6310 D PackageIntentReceiver: Not supported Hotkey customization function 
,08-05 01:29:35.412  6310  6310 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
08-05 01:29:35.412  6310  6310 D HideNavigationAppsReceiver: replacing : false
08-05 01:29:35.414  6310  6310 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
08-05 01:29:35.415  6310  6310 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
08-05 01:29:35.415  6310  6310 D ButtonCombinationReceiver: replacing : false
,08-05 01:29:35.422  1032  1960 I ActivityManager: Killing 5799:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,08-05 01:29:35.559  1032  1573 W libprocessgroup: failed to open /acct/uid_10008/pid_5799/cgroup.procs: No such file or directory
,08-05 01:29:35.564  4561  6328 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-05 01:29:35.586  1032  1868 V SIM_STK : Menu title from STK is T-Mobile
,08-05 01:29:35.590  2034  2957 I GBoardtInterface: exportHTML()
08-05 01:29:35.597  1032  1945 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6329 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-05 01:29:35.621  2034  2957 I GBoardtInterface: exportHTML()
08-05 01:29:35.630  4561  6328 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 66 ms] updated apps [took 66 ms] 
,08-05 01:29:35.646  6329  6329 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2586 
,08-05 01:29:35.647  2034  2957 I GBoardtInterface: exportHTML()
08-05 01:29:35.656  6065  6065 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-05 01:29:35.656  6065  6065 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-05 01:29:35.656  6065  6065 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-05 01:29:35.656  6065  6065 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-05 01:29:35.656  6065  6065 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-05 01:29:35.656  6065  6065 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
08-05 01:29:35.662  6329  6349 E SQLiteDatabase: Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
08-05 01:29:35.662  6329  6349 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-05 01:29:35.662  6329  6349 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-05 01:29:35.662  6329  6349 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-05 01:29:35.662  6329  6349 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-05 01:29:35.662  6329  6349 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-05 01:29:35.662  6329  6349 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-05 01:29:35.662  6329  6349 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-05 01:29:35.662  6329  6349 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-05 01:29:35.662  6329  6349 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-05 01:29:35.662  6329  6349 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-05 01:29:35.662  6329  6349 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-05 01:29:35.662  6329  6349 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-05 01:29:35.662  6329  6349 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-05 01:29:35.662  6329  6349 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-05 01:29:35.662  6329  6349 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-05 01:29:35.662  6329  6349 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-05 01:29:35.662  6329  6349 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-05 01:29:35.662  6329  6349 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 01:29:35.662  6329  6349 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-05 01:29:35.662  6329  6349 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
--------- beginning of crash
08-05 01:29:35.662  6329  6349 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
08-05 01:29:35.662  6329  6349 E AndroidRuntime: Process: com.android.keychain, PID: 6329
08-05 01:29:35.662  6329  6349 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-05 01:29:35.662  6329  6349 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native, Method)
08-05 01:29:35.662  6329  6349 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-05 01:29:35.662  6329  6349 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-05 01:29:35.662  6329  6349 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-05 01:29:35.662  6329  6349 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-05 01:29:35.662  6329  6349 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-05 01:29:35.662  6329  6349 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-05 01:29:35.662  6329  6349 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-05 01:29:35.662  6329  6349 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-05 01:29:35.662  6329  6349 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-05 01:29:35.662  6329  6349 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-05 01:29:35.662  6329  6349 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-05 01:29:35.662  6329  6349 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-05 01:29:35.662  6329  6349 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-05 01:29:35.662  6329  6349 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-05 01:29:35.662  6329  6349 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-05 01:29:35.662  6329  6349 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 01:29:35.662  6329  6349 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-05 01:29:35.662  6329  6349 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-05 01:29:35.663  6329  6349 I Process : Sending signal. PID: 6329 SIG: 9
08-05 01:29:35.665  6164  6164 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_REMOVED : com.test.thalitest
08-05 01:29:35.667  1032  6351 E DropBoxManagerService: Can't write: system_app_crash
08-05 01:29:35.667  1032  6351 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop112.tmp: open failed: EROFS (Read-only file system)
08-05 01:29:35.667  1032  6351 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-05 01:29:35.667  1032  6351 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-05 01:29:35.667  1032  6351 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-05 01:29:35.667  1032  6351 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-05 01:29:35.667  1032  6351 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-05 01:29:35.667  1032  6351 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
08-05 01:29:35.667  1032  6351 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-05 01:29:35.667  1032  6351 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-05 01:29:35.667  1032  6351 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-05 01:29:35.667  1032  6351 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-05 01:29:35.667  1032  6351 E DropBoxManagerService: 	... 5 more
08-05 01:29:35.668  6310  6310 D PackageIntentReceiver: Not supported Hotkey customization function 
08-05 01:29:35.698  1032  1945 I ActivityManager: Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=6353 uid=10060 gids={50060, 9997, 1028, 4002} abi=armeabi-v7a

```
