#### Test 627544039ea0a99_thali04_motorola-XT1072 Logs


```
--------- beginning of system
03-17 12:56:31.831   880   896 I ActivityManager: Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=4707 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,--------- beginning of main
03-17 12:56:32.017  2022  4702 I GCM     : GCM config loaded
03-17 12:56:32.401  4729  4729 D AndroidRuntime: 
03-17 12:56:32.401  4729  4729 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-17 12:56:32.405  4729  4729 D AndroidRuntime: CheckJNI is OFF
03-17 12:56:32.512   880  1240 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=4756 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
03-17 12:56:32.685   880  1546 I ActivityManager: Killing 3577:com.android.defcontainer/u0a10 (adj 15): empty #7
03-17 12:56:32.728  4729  4729 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-17 12:56:32.732   880  1513 W libprocessgroup: failed to open /acct/uid_10010/pid_3577/cgroup.procs: No such file or directory
03-17 12:56:32.781   880  3224 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4787 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 12:56:32.782   880  1502 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-17 12:56:32.808   279  1956 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (205 us)
03-17 12:56:32.831  1459  4227 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
03-17 12:56:32.843  4729  4729 D AndroidRuntime: Shutting down VM
03-17 12:56:32.851   880  1216 D BatteryService: uevent={POWER_SUPPLY_TEMP=344, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2362000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312559, SEQNUM=4347, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-14723, POWER_SUPPLY_CHARGE_COUNTER=-114, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
03-17 12:56:32.866  1948  3674 I CheckinService: Done disabling old GoogleServicesFramework version
03-17 12:56:32.893   880  1593 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4806 uid=10109 gids={50109, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-17 12:56:32.904   880  1502 D WifiService: releaseWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@63f2b25}
03-17 12:56:32.908  2746  2746 E ActivityThread: Performing stop of activity that is not resumed: {com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity}
03-17 12:56:32.908  2746  2746 E ActivityThread: java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity}
03-17 12:56:32.908  2746  2746 E ActivityThread: 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3396)
03-17 12:56:32.908  2746  2746 E ActivityThread: 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3477)
03-17 12:56:32.908  2746  2746 E ActivityThread: 	at android.app.ActivityThread.access$1100(ActivityThread.java:148)
03-17 12:56:32.908  2746  2746 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1321)
03-17 12:56:32.908  2746  2746 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 12:56:32.908  2746  2746 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
03-17 12:56:32.908  2746  2746 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5312)
03-17 12:56:32.908  2746  2746 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 12:56:32.908  2746  2746 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 12:56:32.908  2746  2746 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
03-17 12:56:32.908  2746  2746 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
03-17 12:56:32.914  2588  2658 D HeadsetStateMachine: Disconnected process message: 10, size: 0
03-17 12:56:32.917   880  3224 I ActivityManager: Killing 4623:com.android.mms/u0a23 (adj 15): empty #7
03-17 12:56:32.973  4297  4786 I Babel   : connection state changed from UNKNOWN to CONNECTED
03-17 12:56:33.050   880  3224 I ActivityManager: Killing 4572:com.google.android.music:main/u0a80 (adj 15): empty #8
,03-17 12:56:33.097  1459  4227 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,03-17 12:56:33.115   880  1479 W libprocessgroup: failed to open /acct/uid_10023/pid_4623/cgroup.procs: No such file or directory
,03-17 12:56:33.147   880   896 W libprocessgroup: failed to open /acct/uid_10080/pid_4572/cgroup.procs: No such file or directory
,03-17 12:56:33.296   880  1479 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4826 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 12:56:33.297   880  3224 I ActivityManager: Activity reported stop, but no longer stopping: ActivityRecord{3f7e0b70 u0 com.motorola.ccc.ota/.ui.DownloadActivity t8}
,03-17 12:56:33.312   880  3224 I ActivityManager: Killing 4653:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,03-17 12:56:33.376   880  1498 W libprocessgroup: failed to open /acct/uid_10035/pid_4653/cgroup.procs: No such file or directory
,03-17 12:56:33.394  4826  4826 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-17 12:56:33.436   278   402 E Vold    : Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,03-17 12:56:33.436   278   402 W Vold    : Returning OperationFailed - no handler for errno 0
03-17 12:56:33.436  4787  4847 W ContextImpl: Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,03-17 12:56:33.441   278   402 E Vold    : Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
03-17 12:56:33.442   278   402 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 12:56:33.442  4787  4847 W ContextImpl: Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,03-17 12:56:33.446  4806  4806 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-17 12:56:33.452  4826  4826 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@1024c64d(com.android.providers.calendar.CalendarProvider2@a21502)
,03-17 12:56:33.463   278   402 E Vold    : Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
03-17 12:56:33.463   278   402 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 12:56:33.464  1289  1289 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-17 12:56:33.464  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 12:56:33.467  4787  4848 W ContextImpl: Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,03-17 12:56:33.470   278   402 E Vold    : Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
03-17 12:56:33.470   278   402 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 12:56:33.471  4787  4848 W ContextImpl: Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,03-17 12:56:33.497  4787  4787 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
03-17 12:56:33.497  4787  4787 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-17 12:56:33.497  4787  4787 I GAv4    :   adb logcat -s GAv4
,03-17 12:56:33.511   880  1515 I ActivityManager: Killing 4684:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,03-17 12:56:33.540  4806  4806 I LibraryLoader: Time to load native libraries: 10 ms (timestamps 2959-2969)
,03-17 12:56:33.540  4806  4806 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 12:56:33.561   880  3224 W libprocessgroup: failed to open /acct/uid_10039/pid_4684/cgroup.procs: No such file or directory
,03-17 12:56:33.564  4787  4787 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-17 12:56:33.564  4806  4806 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {263de850}
03-17 12:56:33.565  4806  4806 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 12:56:33.577  4806  4806 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-17 12:56:33.595  4806  4806 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-17 12:56:33.598  4806  4806 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 12:56:33.601  4806  4806 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-17 12:56:33.614   880  1575 I ActivityManager: Killing 4707:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,03-17 12:56:33.636  4787  4787 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-17 12:56:33.644  4787  4856 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-17 12:56:33.661   880  1296 W libprocessgroup: failed to open /acct/uid_10088/pid_4707/cgroup.procs: No such file or directory
,03-17 12:56:33.684  4806  4806 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-17 12:56:33.690  4806  4806 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-17 12:56:33.690  4806  4806 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-17 12:56:33.691  4806  4806 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-17 12:56:33.691  4806  4806 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-17 12:56:33.691  4806  4806 I Adreno-EGL: Build Date: 10/28/14 Tue
03-17 12:56:33.691  4806  4806 I Adreno-EGL: Local Branch: 
03-17 12:56:33.691  4806  4806 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-17 12:56:33.691  4806  4806 I Adreno-EGL: Local Patches: NONE
03-17 12:56:33.691  4806  4806 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,03-17 12:56:33.768   880  1096 D BluetoothManagerService: Message: 20
,03-17 12:56:33.768   880  1096 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2d0e4ea:true
,03-17 12:56:33.944  4806  4806 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 12:56:33.958  4806  4806 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-17 12:56:33.975  4806  4806 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,03-17 12:56:33.982  4806  4806 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-17 12:56:33.982  4806  4806 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 12:56:33.985  4787  4787 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-17 12:56:34.006  4787  4787 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 3433-3436)
03-17 12:56:34.006  4787  4787 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 12:56:34.012  4787  4787 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2cb3c2a4}
,03-17 12:56:34.012  4787  4787 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 12:56:34.013  4787  4787 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
03-17 12:56:34.025  4787  4787 I BrowserStartupController: Initializing chromium process, singleProcess=true
03-17 12:56:34.026  4787  4787 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-17 12:56:34.027  4787  4787 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-17 12:56:34.043  4806  4902 D OpenGLRenderer: Render dirty regions requested: true
,03-17 12:56:34.046  4787  4787 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-17 12:56:34.051  4787  4787 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-17 12:56:34.051  4787  4787 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-17 12:56:34.052  4787  4787 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-17 12:56:34.052  4787  4787 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-17 12:56:34.052  4787  4787 I Adreno-EGL: Build Date: 10/28/14 Tue
03-17 12:56:34.052  4787  4787 I Adreno-EGL: Local Branch: 
03-17 12:56:34.052  4787  4787 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-17 12:56:34.052  4787  4787 I Adreno-EGL: Local Patches: NONE
03-17 12:56:34.052  4787  4787 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,03-17 12:56:34.062  4806  4806 D Atlas   : Validating map...
,03-17 12:56:34.069  4806  4867 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-17 12:56:34.111  4806  4902 I OpenGLRenderer: Initialized EGL, version 1.4
,03-17 12:56:34.117  4806  4902 D OpenGLRenderer: Enabling debug mode 0
,03-17 12:56:34.146  4787  4911 W AudioManagerAndroid: Requires BLUETOOTH permission
,03-17 12:56:34.167  4787  4787 I NSApplication: Starting up...
03-17 12:56:34.168  1416  1416 I Keyboard.Facilitator: onFinishInput()
,03-17 12:56:34.174   880  1097 I LaunchCheckinHandler: Displayed com.test.thalitest/.MainActivity,cp,ca,1329
03-17 12:56:34.174   880  1097 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s329ms
,03-17 12:56:34.228   880  1502 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=4919 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 12:56:34.229   880  1502 I ActivityManager: Killing 4400:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,03-17 12:56:34.249  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 12:56:34.261   330   330 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 521us total 32.723ms
,03-17 12:56:34.284   330   330 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 22.239ms
,03-17 12:56:34.307   330   330 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 308us total 22.400ms
,03-17 12:56:34.318  4806  4941 E Adreno-ES20: <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
03-17 12:56:34.318  4806  4941 E Adreno-ES20: <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,03-17 12:56:34.346  4806  4806 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 4806
,03-17 12:56:34.395   880  1498 W libprocessgroup: failed to open /acct/uid_10090/pid_4400/cgroup.procs: No such file or directory
,03-17 12:56:34.478  4826  4826 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
03-17 12:56:34.478  4826  4826 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-17 12:56:34.481   880  1593 I ActivityManager: Killing 4756:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,03-17 12:56:34.524  4806  4806 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-17 12:56:34.551   880  1296 W libprocessgroup: failed to open /acct/uid_10019/pid_4756/cgroup.procs: No such file or directory
,03-17 12:56:34.783   880  1513 I art     : Explicit concurrent mark sweep GC freed 21591(1058KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/31MB, paused 1.430ms total 149.933ms
,03-17 12:56:34.878   880  1479 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=4952 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
03-17 12:56:34.879   880  1479 I ActivityManager: Killing 4297:com.google.android.talk/u0a70 (adj 15): empty #7
,03-17 12:56:34.921   279   739 I SFPerfTracer:      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (42:210 vsyncs) (44:1154)
,03-17 12:56:34.930  4806  4902 E Adreno-ES20: <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
,03-17 12:56:34.930  4806  4902 E Adreno-ES20: <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,03-17 12:56:34.951   880  1594 W libprocessgroup: failed to open /acct/uid_10070/pid_4297/cgroup.procs: No such file or directory
,03-17 12:56:34.982  4952  4952 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 12:56:34.998  4806  4918 D jxcore_app_log: JniHelper::setJavaVM(0xb8b81310), pthread_self() = -1192292240
,03-17 12:56:35.008  4806  4918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-17 12:56:35.008  4806  4918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-17 12:56:35.008  4806  4918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-17 12:56:35.008  4806  4918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-17 12:56:35.008  4806  4918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-17 12:56:35.008  4806  4918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e2f25dc added. We now have 1 listener(s)
,03-17 12:56:35.010   880  1479 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,03-17 12:56:35.015  4806  4918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:80:EB:7B:5A:05
,03-17 12:56:35.018  4806  4918 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
,03-17 12:56:35.019  4806  4918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
03-17 12:56:35.019  4806  4918 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
,03-17 12:56:35.019  4806  4918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
,03-17 12:56:35.023  4806  4918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-17 12:56:35.023  4806  4918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-17 12:56:35.023  4806  4918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-17 12:56:35.023  4806  4918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 44:80:EB:7B:5A:05
03-17 12:56:35.023  4806  4918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-17 12:56:35.023  4806  4918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-17 12:56:35.023  4806  4918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-17 12:56:35.023  4806  4918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-17 12:56:35.023  4806  4918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-17 12:56:35.023  4806  4918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,03-17 12:56:35.023  4806  4918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a937c6b added. We now have 1 listener(s)
03-17 12:56:35.024  4806  4918 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-17 12:56:35.028   880  1234 D WifiService: New client listening to asynchronous messages
,03-17 12:56:35.029  4806  4918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,03-17 12:56:35.042  4806  4918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
,03-17 12:56:35.043  4806  4918 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,03-17 12:56:35.047  4806  4918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-17 12:56:35.048   880  1502 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,03-17 12:56:35.049  4806  4918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:80:EB:7B:5A:05
,03-17 12:56:35.055  4806  4918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-17 12:56:35.055  4806  4918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-17 12:56:35.055  4806  4918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-17 12:56:35.055  4806  4918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-17 12:56:35.055  4806  4918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-17 12:56:35.055  4806  4918 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-17 12:56:35.055  4806  4918 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-17 12:56:35.055  4806  4918 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-17 12:56:35.055  4806  4918 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-17 12:56:35.055  4806  4918 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-17 12:56:35.240   279   279 I SFPerfTracer:      triggers: (rate: 13:261) (compose: 0:1) (post: 0:1) (render: 0:2) (31:1077 frames) (32:1155)
03-17 12:56:35.240   279   279 D SFPerfTracer:        layers: (3:12) (FocusedStackFrame (0xb8a81b30): 0:14)* (DimLayer (0xb8a9a118): 0:7)* (StatusBar (0xb8af8db0): 0:114) (NavigationBar (0xb8afc650): 0:34) (com.android.systemui.ImageWallpaper (0xb8b12808): 0:7)* (Starting com.motorola.ccc.ota (0xb8b3c768): 0:29)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb8b17a38): 0:56)- (Starting com.test.thalitest (0xb8b3c768): 0:40)- (com.test.thalitest/com.test.thalitest.MainActivity (0xb8a9e2a8): 32:37) 
,03-17 12:56:35.243  4806  4806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 12:56:35.247  4806  4806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
03-17 12:56:35.249  4806  4806 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
03-17 12:56:35.250  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 12:56:35.431  4806  4821 I art     : Background partial concurrent mark sweep GC freed 9677(650KB) AllocSpace objects, 6(256KB) LOS objects, 40% free, 10MB/17MB, paused 5.033ms total 56.627ms
,03-17 12:56:35.555   880  1081 I ActivityManager: Waited long enough for: ServiceRecord{136c4887 u0 com.motorola.ccc.checkin/.CheckinService}
,03-17 12:56:35.611   880  1515 I ActivityManager: Start proc com.motorola.context for broadcast com.motorola.context/.receiver.DateChangeBroadcastReceiver: pid=4984 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
03-17 12:56:35.612   880  1515 I ActivityManager: Killing 4787:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,03-17 12:56:35.860   880  1502 W libprocessgroup: failed to open /acct/uid_10081/pid_4787/cgroup.procs: No such file or directory
,03-17 12:56:35.883  4984  4984 W ResourcesManager: Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,03-17 12:56:35.988   880  1546 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=5006 uid=10096 gids={50096, 9997} abi=armeabi-v7a
,03-17 12:56:36.002   880  1593 I ActivityManager: Killing 4544:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,03-17 12:56:36.041  4806  4976 W jxcore-log: Initializing JXcore engine
03-17 12:56:36.041  4806  4976 W jxcore-log: JXcore engine is ready
,03-17 12:56:36.103   880   896 W libprocessgroup: failed to open /acct/uid_10057/pid_4544/cgroup.procs: No such file or directory
,03-17 12:56:36.100  4976  4976 W Thread-511: type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10109 path="socket:[7351]" dev="sockfs" ino=7351 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-17 12:56:36.100  4976  4976 W Thread-511: type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10109 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
03-17 12:56:36.100  4976  4976 W Thread-511: type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10109 path="socket:[9455]" dev="sockfs" ino=9455 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-17 12:56:36.100  4976  4976 W Thread-511: type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10109 path="socket:[22180]" dev="sockfs" ino=22180 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,03-17 12:56:36.136  5006  5006 I System.out: TimeService: Loaded Library 
,03-17 12:56:36.137  5006  5006 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1458215796136
03-17 12:56:36.137  5006  5006 D         : TimeServiceNative: User Time to be set is 1458215796137
03-17 12:56:36.137  5006  5006 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
03-17 12:56:36.137  5006  5006 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
03-17 12:56:36.137  5006  5006 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1458215796137
03-17 12:56:36.137  5006  5006 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
03-17 12:56:36.138   342   828 D QC-time-services: Daemon: Connection accepted:time_genoff
,03-17 12:56:36.139   342  5024 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1458215796137
03-17 12:56:36.140   342  5024 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1458215796137, operation = 0
,03-17 12:56:36.140   342  5024 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS2/17/116 11:54:46
03-17 12:56:36.141   342  5024 D QC-time-services: Daemon:Value read from RTC seconds = 1458215686000
03-17 12:56:36.141   342  5024 D QC-time-services: Daemon:new time 1458215796137 
03-17 12:56:36.141   342  5024 D QC-time-services: Daemon: delta 110137 genoff 110137 
03-17 12:56:36.141   342  5024 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 110137 to memory
03-17 12:56:36.141   342  5024 D QC-time-services: Daemon:Opening File: /data/time/ats_2
03-17 12:56:36.141   342  5024 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-17 12:56:36.147   342  5024 D QC-time-services: Updating the TOD offset
03-17 12:56:36.147   342  5024 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 110137 to memory
03-17 12:56:36.147   342  5024 D QC-time-services: Daemon:Opening File: /data/time/ats_1
03-17 12:56:36.147   342  5024 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-17 12:56:36.149   342  5024 E QC-time-services: Daemon:Update to modem bit set
03-17 12:56:36.149   342  5024 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
03-17 12:56:36.149   342  5024 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 18446743757744861753
,03-17 12:56:36.150  5006  5006 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,03-17 12:56:36.151   880  1296 I ActivityManager: Killing 4826:com.android.providers.calendar/u0a5 (adj 15): empty #7
,03-17 12:56:36.153   342   826 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,03-17 12:56:36.155   342   828 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,03-17 12:56:36.162  4806  4976 W jxcore-log: Starting JXcore engine
,03-17 12:56:36.261   880  1593 W libprocessgroup: failed to open /acct/uid_10005/pid_4826/cgroup.procs: No such file or directory
,03-17 12:56:36.312  4806  4976 W jxcore-log: Platform android
03-17 12:56:36.312  4806  4976 W jxcore-log: 
03-17 12:56:36.313  4806  4976 W jxcore-log: Process ARCH arm
03-17 12:56:36.313  4806  4976 W jxcore-log: 
,03-17 12:56:36.517   880   895 I ActivityManager: Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=5026 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,03-17 12:56:36.553   880  1251 D TaskPersister: removeObsoleteFile: deleting file=8_task_thumbnail.png
,03-17 12:56:36.556  1289  1289 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,03-17 12:56:36.557  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 12:56:36.655  5026  5026 I GAv4    : Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
03-17 12:56:36.655  5026  5026 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-17 12:56:36.655  5026  5026 I GAv4    :   adb logcat -s GAv4
03-17 12:56:36.655  4806  4976 I jxcore-log: JXcore Cordova bridge is ready!
03-17 12:56:36.655  4806  4976 I jxcore-log: 
,03-17 12:56:36.656  4806  4976 W jxcore-log: JXcore engine is started
,03-17 12:56:36.662  4806  4918 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-17 12:56:36.671  4806  4976 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-17 12:56:36.671  4806  4976 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-17 12:56:36.677  4806  4806 I chromium: [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,03-17 12:56:36.693  1459  4227 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,03-17 12:56:36.700  5026  5026 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-17 12:56:36.701  1459  4227 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,03-17 12:56:36.716  2746  2746 D OtaApp  : [debug] > DownloadActivity, FormattedText
,03-17 12:56:36.719  2746  2746 I OtaApp  : [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,03-17 12:56:36.720  2746  2746 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-17 12:56:36.723  2746  2746 I OtaApp  : [info] > Exceed max defer attempts for optional update, suppresing later btn
,03-17 12:56:36.724  2746  2746 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-17 12:56:36.726  2746  2746 D OtaApp  : [debug] > cancelling the previous pending intent set for download later
,03-17 12:56:36.727  2746  2746 I OtaApp  : [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,03-17 12:56:36.728  2746  2746 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-17 12:56:36.729  5026  5026 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-17 12:56:36.734  5026  5050 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-17 12:56:36.758  1416  1416 I Keyboard.Facilitator: onFinishInput()
,03-17 12:56:36.759  4806  4806 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-17 12:56:36.813   880  1296 I ActivityManager: Killing 4334:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,03-17 12:56:36.871   880  1479 W libprocessgroup: failed to open /acct/uid_10016/pid_4334/cgroup.procs: No such file or directory
,03-17 12:56:36.907  2746  2746 D EmailService.MarketingOptInSetter: received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,03-17 12:56:36.919  2746  2746 D GetNotificationsWS: bindWebServices(): registering our AIDL callback...
,03-17 12:56:36.924  2746  5056 I SundryService: onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,03-17 12:56:36.929  2746  5056 E SQLiteLog: (284) automatic index on registration(APP_ID)
,03-17 12:56:36.930  2746  2746 D GetNotificationsWS: onServiceConnected()
,03-17 12:56:36.931  2746  5056 D WaitableIntentService: ServiceHandler.handleMessage: mWaitCount=0
,03-17 12:56:36.932  2746  2746 D GetNotificationsWS: onServiceConnected(): Registered for remote service callbacks...
,03-17 12:56:36.935  2746  5057 I PushService: started with background data enabled, making sure notification mechanism is enabled
,03-17 12:56:36.936  1459  1459 D Central_PollingManager: wake lock released
,03-17 12:56:36.937  2746  2746 D GetNotificationsWS: unbindWebServices(): un-registering our AIDL callback...
,03-17 12:56:36.949   323   377 I ThermalEngine: Sensor:xo_therm_pu2:39000 mC
,03-17 12:56:36.964  2746  2746 D OtaApp  : [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,03-17 12:56:36.966  2746  2746 D OtaApp  : [debug] > UpdateReceiver: Received true from doSanityCheck.
,03-17 12:56:36.967  2746  2746 D OtaApp  : [debug] > In cancelAnyPendingIntentSetPreviously
,03-17 12:56:36.971   880   896 I ActivityManager: START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,03-17 12:56:37.009  2746  4320 E global frequency: no tags to log
,03-17 12:56:37.011  2746  4320 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,03-17 12:56:37.017  2746  2746 D OtaApp  : [debug] > DownloadActivity, FormattedText
,03-17 12:56:37.020  2746  2746 I OtaApp  : [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,03-17 12:56:37.022  2746  2746 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-17 12:56:37.025  2746  2746 I OtaApp  : [info] > Exceed max defer attempts for optional update, suppresing later btn
,03-17 12:56:37.026  2746  2746 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-17 12:56:37.030  2746  2746 D OtaApp  : [debug] > cancelling the previous pending intent set for download later
,03-17 12:56:37.031  2746  2746 I OtaApp  : [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,03-17 12:56:37.032  2746  2746 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-17 12:56:37.058  2746  2746 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-17 12:56:37.061  2022  2022 D WearableService: callingUid 10016, callindPid: 2022
,03-17 12:56:37.067  1551  1596 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,03-17 12:56:37.071  1948  5060 D LocationInitializer: Restart initialization of location
,03-17 12:56:37.071  2022  5059 E MDM     : [229] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-17 12:56:37.079  2022  2022 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-17 12:56:37.097  2022  2022 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 12:56:37.113   880   880 V AlarmManager: done {13459f14, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [10522ms]
,03-17 12:56:37.163   880  1498 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5064 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 12:56:37.173  2022  2094 W GCoreFlp: No location to return for getLastLocation()
03-17 12:56:37.173  2022  5061 W FusedLocationProvider: location=null
,03-17 12:56:37.196  2746  2746 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-17 12:56:37.248  1459  4505 I art     : Explicit concurrent mark sweep GC freed 4549(204KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 723us total 38.751ms
,03-17 12:56:37.251  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 12:56:37.252  2746  2746 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,03-17 12:56:37.268  2746  2746 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-17 12:56:37.270  1551  1596 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,03-17 12:56:37.343  5064  5083 I Gmail   : getAccountsCursor
,03-17 12:56:37.346  5064  5084 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,03-17 12:56:37.351  2746  2746 I art     : Explicit concurrent mark sweep GC freed 22292(1370KB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 11MB/18MB, paused 1.122ms total 70.099ms
,03-17 12:56:37.359  2022  2022 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 12:56:37.448   880  1498 I ActivityManager: Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=5086 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 12:56:37.597   880  1566 I art     : Explicit concurrent mark sweep GC freed 12255(602KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 21MB/31MB, paused 3.949ms total 154.399ms
,03-17 12:56:37.604  2746  2746 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-17 12:56:37.618  2746  2746 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
03-17 12:56:37.619  5064  5064 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-17 12:56:37.630   880  1515 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,03-17 12:56:37.631  4806  4806 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@4e87c61 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 12:56:37.631  4806  4806 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@4e87c61 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 12:56:37.631  4806  4806 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:907)
03-17 12:56:37.631  4806  4806 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:708)
03-17 12:56:37.631  4806  4806 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1771)
03-17 12:56:37.631  4806  4806 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1751)
03-17 12:56:37.631  4806  4806 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1745)
03-17 12:56:37.631  4806  4806 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.initialize(BluetoothManager.java:275)
03-17 12:56:37.631  4806  4806 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.bind(BluetoothManager.java:103)
03-17 12:56:37.631  4806  4806 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:75)
03-17 12:56:37.631  4806  4806 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-17 12:56:37.631  4806  4806 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-17 12:56:37.631  4806  4806 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-17 12:56:37.631  4806  4806 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-17 12:56:37.631  4806  4806 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-17 12:56:37.631  4806  4806 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-17 12:56:37.631  4806  4806 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-17 12:56:37.631  4806  4806 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-17 12:56:37.631  4806  4806 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-17 12:56:37.631  4806  4806 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-17 12:56:37.631  4806  4806 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 12:56:37.631  4806  4806 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
03-17 12:56:37.631  4806  4806 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 12:56:37.636  4806  4806 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@2676c3c8 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 12:56:37.636  4806  4806 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@2676c3c8 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 12:56:37.636  4806  4806 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:907)
03-17 12:56:37.636  4806  4806 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:708)
03-17 12:56:37.636  4806  4806 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1771)
03-17 12:56:37.636  4806  4806 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1751)
03-17 12:56:37.636  4806  4806 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1745)
03-17 12:56:37.636  4806  4806 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:488)
03-17 12:56:37.636  4806  4806 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:67)
03-17 12:56:37.636  4806  4806 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-17 12:56:37.636  4806  4806 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-17 12:56:37.636  4806  4806 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-17 12:56:37.636  4806  4806 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-17 12:56:37.636  4806  4806 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-17 12:56:37.636  4806  4806 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-17 12:56:37.636  4806  4806 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-17 12:56:37.636  4806  4806 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-17 12:56:37.636  4806  4806 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-17 12:56:37.636  4806  4806 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-17 12:56:37.636  4806  4806 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 12:56:37.636  4806  4806 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
03-17 12:56:37.636  4806  4806 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-17 12:56:37.637  2746  2746 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
03-17 12:56:37.643  5064  5108 I Gmail   : Observing account changes for notifications
03-17 12:56:37.644  1551  1568 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
03-17 12:56:37.644  5086  5086 I Exchange: EasService.onCreate
03-17 12:56:37.654  5086  5110 I Exchange: RestartPingTask
,03-17 12:56:37.667  5086  5086 I Exchange: RestartPingsTask did not start any pings.
03-17 12:56:37.667  5086  5086 I Exchange: PSS stopIfIdle
03-17 12:56:37.667  5086  5086 I Exchange: PSS has no active accounts; stopping service.
03-17 12:56:37.685   880  1594 I ActivityManager: Killing 4919:com.android.chrome/u0a52 (adj 15): empty #7
,03-17 12:56:37.720  2746  2746 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-17 12:56:37.752  1459  1497 I art     : Explicit concurrent mark sweep GC freed 3299(131KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 596us total 25.764ms
,03-17 12:56:37.763  2746  2746 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,03-17 12:56:37.769   880  1479 W libprocessgroup: failed to open /acct/uid_10052/pid_4919/cgroup.procs: No such file or directory
,03-17 12:56:37.773  2746  4320 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,03-17 12:56:37.778  2746  4320 I global frequency: BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,03-17 12:56:37.780  2746  4320 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,03-17 12:56:37.781  2746  4320 E global frequency: BcsDSCheckin.logProperties: BL State from property is null or empty
03-17 12:56:37.782  2746  4320 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,03-17 12:56:37.784  5064  5116 I Gmail   : getAccountsCursor
,03-17 12:56:37.786  5086  5086 I Exchange: onDestroy
03-17 12:56:37.786  2746  4320 D Checkin : publish the event [tag = DEV_ATTRIBS event name = SW]
,03-17 12:56:37.794   880   895 I ActivityManager: Killing 4952:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,03-17 12:56:37.797  2022  2022 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 12:56:37.805  2746  4320 D Checkin : publish the event [tag = MOT_CCE_STATS event name = DataUsage]
,03-17 12:56:37.817  2746  4320 I global frequency: BcsCore.doCallHomeCore: Exceeded maximum number of checkins for one hour. Bailing out
,03-17 12:56:37.817  2746  4320 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,03-17 12:56:37.832   880  1515 W libprocessgroup: failed to open /acct/uid_10090/pid_4952/cgroup.procs: No such file or directory
,03-17 12:56:37.840  2022  2022 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 12:56:37.866  5064  5121 E SQLiteLog: (283) recovered 37 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,03-17 12:56:37.869  4984  5124 I CE-UpdateModelService: ACTION_REGISTRATION_COMPLETE
,03-17 12:56:37.909   880  1498 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=5125 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,03-17 12:56:37.922   880  1515 I ActivityManager: Killing 5006:com.qualcomm.timeservice/u0a96 (adj 15): empty #7
,03-17 12:56:37.924  5064  5123 I Gmail   : notifyAccountChanged
,03-17 12:56:37.927  5064  5114 I Gmail   : getAccountsCursor
,03-17 12:56:37.942  5064  5123 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-17 12:56:37.946  5064  5123 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-17 12:56:37.953  5064  5123 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-17 12:56:37.954  5064  5123 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-17 12:56:37.962   880   895 W libprocessgroup: failed to open /acct/uid_10096/pid_5006/cgroup.procs: No such file or directory
,03-17 12:56:37.964  2022  2022 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 12:56:37.988  2022  2022 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 12:56:37.989  2022  2022 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 12:56:38.036  5064  5083 I Gmail   : getAccountsCursor
,03-17 12:56:38.040  2022  2022 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 12:56:38.258  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 12:56:38.279   880  1513 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5151 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,03-17 12:56:38.321   880  1479 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=5168 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,03-17 12:56:38.323   880  1479 I ActivityManager: Killing 5026:com.google.android.deskclock/u0a55 (adj 15): empty #7
,03-17 12:56:38.363   880  3224 I ActivityManager: Killing 4806:com.test.thalitest/u0a109 (adj 15): empty #7
,03-17 12:56:38.397   880  1234 D WifiService: Client connection lost with reason: 4
,03-17 12:56:38.482   880  1515 W libprocessgroup: failed to open /acct/uid_10055/pid_5026/cgroup.procs: No such file or directory
,03-17 12:56:38.483   880  1594 W libprocessgroup: failed to open /acct/uid_10109/pid_4806/cgroup.procs: No such file or directory
,03-17 12:56:38.498  5168  5168 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 12:56:38.546  1787  1805 I art     : Explicit concurrent mark sweep GC freed 3162(130KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 424us total 28.284ms
,03-17 12:56:38.652  5168  5192 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
03-17 12:56:38.652  5168  5192 I Babel_SMS: MmsConfig.loadMmsSettings
03-17 12:56:38.653  5168  5192 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
03-17 12:56:38.653  5168  5192 I Babel_SMS: MmsConfig.loadFromDatabase
,03-17 12:56:38.665  5168  5192 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,03-17 12:56:38.665  5168  5192 I Babel_SMS: MmsConfig.loadFromResources
03-17 12:56:38.667  5168  5192 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,03-17 12:56:38.667  5168  5192 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,03-17 12:56:38.734  5168  5168 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,03-17 12:56:38.742  5168  5168 I Babel_Crash: startup - clean
,03-17 12:56:38.761  5168  5195 I Babel   : deleted: false for 0
,03-17 12:56:38.882  5168  5168 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-17 12:56:38.894  5168  5168 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,03-17 12:56:38.899   880  1240 I ActivityManager: Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5197 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 12:56:38.921  5168  5168 W VideoCapabilities: Unsupported mime video/mpeg2
,03-17 12:56:38.947  5168  5168 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,03-17 12:56:38.955  5168  5168 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-17 12:56:38.958  5168  5168 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-17 12:56:38.961  5168  5168 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-17 12:56:38.965  5168  5168 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-17 12:56:38.969  5197  5197 W asset   : Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
03-17 12:56:38.969  5197  5197 W ResourcesManager: Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
03-17 12:56:38.969  5197  5197 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 12:56:38.970  5197  5197 W ResourcesManager: Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,03-17 12:56:39.031  5168  5168 I vclib   : onServiceConnected
,03-17 12:56:39.034  5168  5168 W Babel   : Attempted to change video mute state without an active call.
,03-17 12:56:39.052  5168  5168 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-17 12:56:39.052  5168  5168 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 12:56:39.112  5168  5168 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-17 12:56:39.125   880  1498 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5221 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 12:56:39.146   330   330 I art     : Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 301us total 21.834ms
,03-17 12:56:39.166   330   330 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 625us total 20.170ms
,03-17 12:56:39.168   880  1594 I ActivityManager: Killing 5086:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,03-17 12:56:39.200   330   330 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 243us total 32.988ms
,03-17 12:56:39.231  5168  5168 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,03-17 12:56:39.231  5168  5168 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-17 12:56:39.259  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 12:56:39.280   880  3224 W libprocessgroup: failed to open /acct/uid_10060/pid_5086/cgroup.procs: No such file or directory
,03-17 12:56:39.463   880  1515 I art     : Explicit concurrent mark sweep GC freed 8898(440KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 21MB/31MB, paused 1.535ms total 112.830ms
,03-17 12:56:39.493  1289  1289 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,03-17 12:56:39.494  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 12:56:39.560  5221  5221 I Finsky  : [1] com.google.android.finsky.FinskyApp.onCreate(358): Initializing network with DFE https://android.clients.google.com/fdfe/
,03-17 12:56:39.678  5221  5221 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(122): No need to run daily hygiene.
,03-17 12:56:39.692  5221  5221 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
03-17 12:56:39.693  5221  5221 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-17 12:56:39.767  5221  5221 I Finsky  : [1] com.google.android.finsky.receivers.h.a(1107): Installer kick - no action, not running yet
03-17 12:56:39.768  5221  5221 I Finsky  : [1] com.google.android.finsky.g.j.run(208): Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
03-17 12:56:39.768  5221  5221 I Finsky  : [1] com.google.android.finsky.g.j.run(214): Finished loading 1 libraries.
,03-17 12:56:39.782  5221  5272 D Ads     : Skipping gmscore version check
,03-17 12:56:39.800  5221  5221 I Finsky  : [1] com.google.android.finsky.b.j.a(273): result=false type=4
,03-17 12:56:39.816  1569  1569 W Launcher: setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1e117205 new=com.google.android.velvet.VelvetApplication@1e117205
,03-17 12:56:39.820  5125  5283 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,03-17 12:56:39.832  5221  5221 I Finsky  : [1] com.google.android.finsky.services.ar.a(1049): Restore complete with 0 success and 0 failed.
,03-17 12:56:39.859  1948  5288 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,03-17 12:56:39.862  1948  5288 I PkgBroadcastIntentOp: Null package name or gms related package.  Ignoreing.
,03-17 12:56:39.870   880  1593 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5289 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,03-17 12:56:39.886  1948  5288 D WearableController: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,03-17 12:56:39.904  1948  2083 I Icing   : updateResources: need to parse f{com.google.android.gms}
,03-17 12:56:39.927  5289  5289 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 12:56:40.012  5125  5283 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 190 ms] updated apps [took 190 ms] 
,03-17 12:56:40.015   880  1593 I ActivityManager: Killing 5064:com.google.android.gm/u0a63 (adj 15): empty #7
,03-17 12:56:40.133   880  3224 W libprocessgroup: failed to open /acct/uid_10063/pid_5064/cgroup.procs: No such file or directory
,03-17 12:56:40.160  2746  2746 D 3CDM.DeviceAdminPushReceiver: Received an Intent - Action: com.motorola.cce.Actions.CCE_SEND_SETTINGS_RESPONSE
03-17 12:56:40.160  2746  2746 D 3CDM.DeviceAdminPushReceiver: Type: null
,03-17 12:56:40.160  2746  2746 D 3CDM.DeviceAdminPushReceiver: Data: null
,03-17 12:56:40.162  2746  2875 D 3CDM.Service: com.motorola.cce.Actions.CCE_SEND_SETTINGS_RESPONSE
03-17 12:56:40.163  2746  2875 D 3CDM.Service: Received settings reponse intent with responsecode code: com.motorola.cce.sharedsettings.errorOk
,03-17 12:56:40.163  2746  2875 D 3CDM.Service: DeviceAdmin - syncWithCCC
03-17 12:56:40.163  2746  2875 D 3CDM.Service: blur.service.littlesister.gpsFixWaitTime = 60000
03-17 12:56:40.163  2746  2875 D 3CDM.Service: com.motorola.ccc.devicemanagement.capabilities = LOST,LOCK,RING,LOCATE,PING,MULTIPLE-LOCATE,WIPE,SYNC,CALL-FORWARDING,STOP-RING
03-17 12:56:40.163  2746  2875 D 3CDM.Service: blur.service.cred.locationToken = null
03-17 12:56:40.163  2746  2875 D 3CDM.Service: com.motorola.ccc.cce.email.marketing.optin.default = false
03-17 12:56:40.163  2746  2875 D 3CDM.Service: blur.service.littlesister.reportLevel2 = NONE
03-17 12:56:40.163  2746  2875 D 3CDM.Service: com.motorola.blur.adminfeed.device_admin_always_allowed = 1
03-17 12:56:40.163  2746  2875 D 3CDM.Service: com.motorola.ccc.devicemanagement.motocare.url = www.motorola.com/support
,03-17 12:56:40.165  2746  2875 D 3CDM.Service: Sync to CCE settings done, instantiate Locate now.
,03-17 12:56:40.201   880  1593 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5319 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,03-17 12:56:40.225  2746  2875 D BSUtils : set .setup.DeviceAdminSetupReceiver enabled
,03-17 12:56:40.269   880  1296 I ActivityManager: Killing 4984:com.motorola.context/u0a8 (adj 15): empty #7
,03-17 12:56:40.276  5319  5319 D PhoneMonitor: Register our PhoneStateListener
,03-17 12:56:40.324  3366  3389 D Checkin : publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,03-17 12:56:40.352   880  1515 W libprocessgroup: failed to open /acct/uid_10008/pid_4984/cgroup.procs: No such file or directory
,03-17 12:56:40.373   880  1222 I InputReader: Reconfiguring input devices.  changes=0x00000010
03-17 12:56:40.373  1551  1551 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 12:56:40.404  5319  5319 V SetupWizard: Connected to Gservices successfully
,03-17 12:56:40.407   880  1575 I ActivityManager: Killing 5151:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,03-17 12:56:40.479   880   880 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
03-17 12:56:40.479   880   880 I BackupManagerService: Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-17 12:56:40.532   880  1566 W libprocessgroup: failed to open /acct/uid_10019/pid_5151/cgroup.procs: No such file or directory
,03-17 12:56:40.534   880   880 I BackupManagerService: Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-17 12:56:40.545   880   880 V BackupManagerService: Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-17 12:56:40.546   880   880 V BackupManagerService: Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@8fc408d
,03-17 12:56:40.556  2022  2022 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,03-17 12:56:40.594   880   896 I ActivityManager: Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=5340 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 12:56:40.634  1569  1569 I Launcher: Deferring update until onResume
,03-17 12:56:40.638  5340  5340 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-17 12:56:40.653  2022  2539 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,03-17 12:56:40.678  5340  5340 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@1024c64d(com.android.providers.calendar.CalendarProvider2@a21502)
,03-17 12:56:40.687   880   880 V AlarmManager: done {630733e, *walarm*:com.android.providers.calendar.intent.CalendarProvider2} [10369ms]
,03-17 12:56:40.694  5340  5359 E SQLiteLog: (284) automatic index on view_events(_id)
,03-17 12:56:40.731   880  1240 I ActivityManager: Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=5360 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,03-17 12:56:40.794  5221  5221 I Finsky  : [1] com.google.android.finsky.utils.ExternalReferrer.a(4312): Package state data is missing for com.test.thalitest
,03-17 12:56:40.800  5125  5381 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,03-17 12:56:40.808  1948  5288 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,03-17 12:56:40.841  1948  5288 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,03-17 12:56:40.898  1948  1948 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.permission.PermissionUtils$1>
,03-17 12:56:40.945   880  1251 D TaskPersister: removeObsoleteFile: deleting file=8_task.xml
,03-17 12:56:41.066  1948  1948 D AsyncTaskServiceImpl: Submit a task: k
,03-17 12:56:41.087  1948  5391 D k       : Processing package: com.test.thalitest
,03-17 12:56:41.098  1948  5391 D GassUtils: Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
03-17 12:56:41.099  1948  5391 D k       : Found info for package com.test.thalitest in db.
,03-17 12:56:41.123  5125  5381 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 323 ms] updated apps [took 323 ms] 
,03-17 12:56:41.130   880  1594 I ActivityManager: Killing 5289:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,03-17 12:56:41.150  1948  2083 I Icing   : Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,03-17 12:56:41.236   880  1498 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5394 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,03-17 12:56:41.237   880  1566 W libprocessgroup: failed to open /acct/uid_10090/pid_5289/cgroup.procs: No such file or directory
,03-17 12:56:41.254  1948  5389 W BaseAppContext: Using Auth Proxy for data requests.
03-17 12:56:41.254  1948  5389 W BaseAppContext: Using Auth Proxy for data requests.
,03-17 12:56:41.258  1948  5389 W BaseAppContext: Using Auth Proxy for data requests.
,03-17 12:56:41.267  1948  5389 W BaseAppContext: Using Auth Proxy for data requests.
,03-17 12:56:41.296  1948  5389 W BaseAppContext: Using Auth Proxy for data requests.
,03-17 12:56:41.319  1948  5386 I PeopleDatabaseHelper: cleanUpNonGplusAccounts done.
,03-17 12:56:41.437  1948  2083 I Icing   : Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,03-17 12:56:41.647  5394  5394 I GAv4    : Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
03-17 12:56:41.647  5394  5394 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-17 12:56:41.647  5394  5394 I GAv4    :   adb logcat -s GAv4
,03-17 12:56:41.661  5394  5394 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-17 12:56:41.682  5394  5394 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-17 12:56:41.688  5340  5340 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
03-17 12:56:41.688  5340  5340 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-17 12:56:41.691   880  1240 I ActivityManager: Killing 5319:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,03-17 12:56:41.693  5394  5423 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-17 12:56:41.709  5394  5394 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,03-17 12:56:41.737  5394  5425 E SQLiteLog: (283) recovered 2 frames from WAL file /data/data/com.google.android.apps.docs/databases/DocList.db-wal
,03-17 12:56:41.859   880  1515 W libprocessgroup: failed to open /acct/uid_10035/pid_5319/cgroup.procs: No such file or directory
,03-17 12:56:41.874   278   402 E Vold    : Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.docs/cache/
03-17 12:56:41.874   278   402 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 12:56:41.874  5394  5431 W ContextImpl: Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs/cache
,03-17 12:56:41.886  5394  5432 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-17 12:56:41.886  5394  5432 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 12:56:41.911   880  1575 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5434 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,03-17 12:56:41.935   880  1546 I ActivityManager: Killing 5340:com.android.providers.calendar/u0a5 (adj 15): empty #7
,03-17 12:56:41.959  5394  5432 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-17 12:56:42.021   880  1593 W libprocessgroup: failed to open /acct/uid_10005/pid_5340/cgroup.procs: No such file or directory
,03-17 12:56:42.023  5394  5432 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-17 12:56:42.023  5394  5432 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-17 12:56:42.039  5434  5434 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 12:56:42.068   880  1513 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5455 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 12:56:42.084  2022  2022 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 12:56:42.123  1948  2083 I Icing   : Indexing AF3945E421480F00A6230F0533E769ED0E1C70AE from com.google.android.googlequicksearchbox
,03-17 12:56:42.219   880  1575 I art     : Explicit concurrent mark sweep GC freed 19541(971KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 21MB/32MB, paused 1.387ms total 116.194ms
,03-17 12:56:42.250  5455  5455 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-17 12:56:42.289  5455  5455 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@1024c64d(com.android.providers.calendar.CalendarProvider2@a21502)
,03-17 12:56:42.322   880  1566 I ActivityManager: Killing 3429:com.google.android.calendar/u0a49 (adj 15): empty #7
,03-17 12:56:42.472   880  1575 W libprocessgroup: failed to open /acct/uid_10049/pid_3429/cgroup.procs: No such file or directory
,03-17 12:56:42.505  1948  2083 I Icing   : Indexing done AF3945E421480F00A6230F0533E769ED0E1C70AE
03-17 12:56:42.506  1948  2083 I Icing   : Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
03-17 12:56:42.509  1948  2083 I Icing   : Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
03-17 12:56:42.509  1289  1289 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,03-17 12:56:42.510  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 12:56:42.536   880  1231 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=6.72 rxSuccessRate=5.94 targetRoamBSSID=any RSSI=-45
03-17 12:56:42.536   880  1231 E WifiStateMachine: WifiStateMachine CMD_START_SCAN with age=18031 interval=30000 maxinterval=300000
,03-17 12:56:42.536   880  1231 E WifiStateMachine: WifiStateMachine CMD_START_SCAN full=false
03-17 12:56:42.537   880  1231 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2457
03-17 12:56:42.537  1423  1423 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
03-17 12:56:42.538   307  1630 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
03-17 12:56:42.538   307  1630 D MDMCTBK : Event received = CTRL-EVENT-SCAN-STARTED 
,03-17 12:56:42.540   880   880 V AlarmManager: done {25ff50b1, *alarm*:com.android.server.WifiManager.action.START_SCAN} [10832ms]
,03-17 12:56:42.540   880  1231 E WifiStateMachine: [1,458,215,802,540 ms] noteScanstart no scan source
,03-17 12:56:42.586   880  1594 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5487 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,03-17 12:56:42.601   307  1630 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
03-17 12:56:42.601   307  1630 D MDMCTBK : Event received = CTRL-EVENT-SCAN-RESULTS 
,03-17 12:56:42.601   498   526 D TCMD    : NL - Read 56 bytes from update socket.
03-17 12:56:42.601   498   526 D TCMD    : NL - message type is RTM_NEWLINK
03-17 12:56:42.602   498   526 D TCMD    : Listening for incoming client connection request
,03-17 12:56:42.605   880  1231 E WifiStateMachine: [1,458,215,802,604 ms] noteScanEnd no scan source
,03-17 12:56:42.609   880  1231 E WifiStateMachine: wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@3a878070 sup_state=COMPLETED debouncing=false
,03-17 12:56:42.639   880  1575 I ActivityManager: Killing 5360:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,03-17 12:56:42.647  5487  5487 D PhoneMonitor: Register our PhoneStateListener
,03-17 12:56:42.731   880  1498 W libprocessgroup: failed to open /acct/uid_10019/pid_5360/cgroup.procs: No such file or directory
,03-17 12:56:42.744   880  1566 I ActivityManager: Killing 5197:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,03-17 12:56:42.822   880  1240 W libprocessgroup: failed to open /acct/uid_10027/pid_5197/cgroup.procs: No such file or directory
,03-17 12:56:42.844  2022  2583 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,03-17 12:56:42.893   880  1515 I ActivityManager: Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=5511 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,03-17 12:56:42.894  1948  5510 I CheckinService: Checking schedule, now: 1458215802894 next: 1458215820134
03-17 12:56:42.894  1948  5510 I CheckinService: active receiver: disabled
,03-17 12:56:43.191   880   896 I ActivityManager: Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=5533 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,03-17 12:56:43.225  5533  5533 W ResourcesManager: Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,03-17 12:56:43.248   880  1240 I ActivityManager: Killing 5221:com.android.vending/u0a32 (adj 15): empty #7
,03-17 12:56:43.296   880   896 W libprocessgroup: failed to open /acct/uid_10032/pid_5221/cgroup.procs: No such file or directory
,03-17 12:56:43.320  5455  5455 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
03-17 12:56:43.321  5455  5455 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-17 12:56:43.330   880  1220 I ActivityManager: Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.DailyHygiene: pid=5556 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 12:56:43.330   880  1220 V AlarmManager: send {24aa8b4e, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene}
03-17 12:56:43.332   880  1220 V AlarmManager: send {25ff50b1, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,03-17 12:56:43.332   880   880 V AlarmManager: done {24aa8b4e, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene} [66ms]
,03-17 12:56:43.353   330   330 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 278us total 22.028ms
,03-17 12:56:43.372   330   330 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 19.062ms
,03-17 12:56:43.393   330   330 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 19.431ms
,03-17 12:56:43.433   880   895 I ActivityManager: Start proc com.google.android.calendar for broadcast com.google.android.calendar/com.android.calendar.alerts.AlertReceiver: pid=5575 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 12:56:43.445   880  1515 I ActivityManager: Killing 5394:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,03-17 12:56:43.501   880  1515 I ActivityManager: Killing 5125:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,03-17 12:56:43.584   880   895 W libprocessgroup: failed to open /acct/uid_10057/pid_5394/cgroup.procs: No such file or directory
,03-17 12:56:43.585   880  3224 W libprocessgroup: failed to open /acct/uid_10039/pid_5125/cgroup.procs: No such file or directory
,03-17 12:56:43.663  5556  5556 I Finsky  : [1] com.google.android.finsky.FinskyApp.onCreate(358): Initializing network with DFE https://android.clients.google.com/fdfe/
,03-17 12:56:43.691  5575  5575 E SQLiteLog: (283) recovered 18 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,03-17 12:56:43.796  5556  5556 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(122): No need to run daily hygiene.
,03-17 12:56:43.814  5556  5556 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-17 12:56:43.816  5556  5556 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-17 12:56:43.821  5575  5575 I AnalyticsLogBase: PlayLogger.onLoggerConnected
,03-17 12:56:43.888   880  1566 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5625 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 12:56:43.921  5556  5556 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.onStartCommand(150): Beginning daily hygiene
,03-17 12:56:43.945  5556  5648 D Ads     : Skipping gmscore version check
,03-17 12:56:43.949  2022  2022 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 12:56:43.953  5556  5556 I Finsky  : [1] com.google.android.finsky.receivers.h.a(1107): Installer kick - no action, not running yet
,03-17 12:56:43.954  5556  5556 I Finsky  : [1] com.google.android.finsky.g.j.run(208): Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
03-17 12:56:43.954  5556  5556 I Finsky  : [1] com.google.android.finsky.g.j.run(214): Finished loading 1 libraries.
,03-17 12:56:43.957  2022  2022 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 12:56:43.959  2022  2022 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 12:56:43.969  5556  5556 I Finsky  : [1] com.google.android.finsky.b.j.a(273): result=false type=4
,03-17 12:56:43.987  5556  5556 I Finsky  : [1] com.google.android.finsky.services.ar.a(1049): Restore complete with 0 success and 0 failed.
,03-17 12:56:44.043  5625  5660 I Gmail   : getAccountsCursor
,03-17 12:56:44.044  5625  5661 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,03-17 12:56:44.107   880  1515 I ActivityManager: Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=5663 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 12:56:44.144  2022  2038 I art     : Explicit concurrent mark sweep GC freed 35584(2MB) AllocSpace objects, 35(560KB) LOS objects, 40% free, 13MB/22MB, paused 1.178ms total 83.993ms
,03-17 12:56:44.184  2022  2022 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 12:56:44.228   880  1593 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,03-17 12:56:44.235  5625  5686 I Gmail   : Observing account changes for notifications
,03-17 12:56:44.246  5663  5663 I Exchange: EasService.onCreate
,03-17 12:56:44.251  5663  5690 I Exchange: RestartPingTask
03-17 12:56:44.251  5625  5625 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-17 12:56:44.261  5663  5663 I Exchange: RestartPingsTask did not start any pings.
03-17 12:56:44.261  5663  5663 I Exchange: PSS stopIfIdle
03-17 12:56:44.261  5663  5663 I Exchange: PSS has no active accounts; stopping service.
,03-17 12:56:44.265  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 12:56:44.297  5663  5663 I Exchange: onDestroy
03-17 12:56:44.297  5625  5693 I Gmail   : getAccountsCursor
,03-17 12:56:44.299   880  1240 I ActivityManager: Killing 5434:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,03-17 12:56:44.324  2022  2022 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-17 12:56:44.324   880   896 W libprocessgroup: failed to open /acct/uid_10090/pid_5434/cgroup.procs: No such file or directory
,03-17 12:56:44.327   880   895 I ActivityManager: Killing 5487:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,03-17 12:56:44.455   880  1240 W libprocessgroup: failed to open /acct/uid_10035/pid_5487/cgroup.procs: No such file or directory
,03-17 12:56:44.461  2746  2746 D 3CDM.DeviceAdminSetupReceiver: received com.motorola.ccc.devicemanagement.setup.action.ENABLED
,03-17 12:56:44.462  2746  2746 D 3CDM.DeviceAdminSetupReceiver: time to show notification
,03-17 12:56:44.465   880   895 I ActivityManager: Killing 5168:com.google.android.talk/u0a70 (adj 15): empty #7
,03-17 12:56:44.467  2022  2022 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 12:56:44.502   880  1593 W libprocessgroup: failed to open /acct/uid_10070/pid_5168/cgroup.procs: No such file or directory
,03-17 12:56:44.515  1289  4832 W ResourcesManager: Asset path '/system/framework/protobufs-2.3.0.jar' does not exist or contains no resources.
,03-17 12:56:44.534  5625  5702 E SQLiteLog: (283) recovered 38 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,03-17 12:56:44.557   880  1566 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=5704 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,03-17 12:56:44.608  5625  5703 I Gmail   : notifyAccountChanged
,03-17 12:56:44.610  5625  5694 I Gmail   : getAccountsCursor
,03-17 12:56:44.612  5625  5703 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-17 12:56:44.616  5625  5703 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-17 12:56:44.624  5625  5703 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-17 12:56:44.625  5625  5703 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-17 12:56:44.684  5556  5602 I qtaguid : Failed write_ctrl(u 39) res=-1 errno=22
,03-17 12:56:44.684  5556  5602 I qtaguid : Untagging socket 39 failed errno=-22
,03-17 12:56:44.684  5556  5602 W NetworkManagementSocketTagger: untagSocket(39) failed with errno -22
,03-17 12:56:44.690  5556  5556 I Finsky  : [1] com.google.android.finsky.utils.hn.a(147): Skipping DFE self-update. Local Version [80621400] >= Server Version [-1]
,03-17 12:56:44.722   880  1546 I art     : Explicit concurrent mark sweep GC freed 14845(754KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 21MB/32MB, paused 1.515ms total 121.086ms
,03-17 12:56:44.729  2022  2022 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 12:56:44.742  1289  1289 E ActivatableNotificationView:  oops Width=0 ActualHeight=128
,03-17 12:56:44.791  5625  5660 I Gmail   : getAccountsCursor
,03-17 12:56:44.797  2022  2022 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 12:56:44.839   880   896 I ActivityManager: Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5724 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,03-17 12:56:44.902  5724  5724 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-17 12:56:44.902  5724  5724 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 12:56:44.947  5724  5724 I MultiDex: VM with version 2.1.0 has multidex support
03-17 12:56:44.947  5724  5724 I MultiDex: install
03-17 12:56:44.947  5724  5724 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-17 12:56:44.968  5724  5724 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-17 12:56:45.029   880  1593 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5747 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,03-17 12:56:45.036  5724  5724 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
03-17 12:56:45.036  5724  5724 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@16185474: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,03-17 12:56:45.036  5724  5724 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-17 12:56:45.071   880  5670 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=5764 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,03-17 12:56:45.078   880  1240 I ActivityManager: Killing 5511:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,03-17 12:56:45.111   880  1594 W libprocessgroup: failed to open /acct/uid_10088/pid_5511/cgroup.procs: No such file or directory
,03-17 12:56:45.128  5556  5601 I qtaguid : Failed write_ctrl(u 39) res=-1 errno=22
03-17 12:56:45.128  5556  5601 I qtaguid : Untagging socket 39 failed errno=-22
03-17 12:56:45.129  5556  5601 W NetworkManagementSocketTagger: untagSocket(39) failed with errno -22
,03-17 12:56:45.132  5724  5724 D ChimeraCfgMgr: Reading stored module config
,03-17 12:56:45.136  5764  5764 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 12:56:45.362  5724  5724 D CAR.SERVICE: Connecting to CarCallService...
,03-17 12:56:45.395  5724  5781 D NativeLibraryUtils: Install completed successfully. count=14 extracted=0
,03-17 12:56:45.399  5724  5724 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,03-17 12:56:45.399  5724  5724 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,03-17 12:56:45.412  5764  5792 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
03-17 12:56:45.412  5764  5792 I Babel_SMS: MmsConfig.loadMmsSettings
03-17 12:56:45.413  5764  5792 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
03-17 12:56:45.413  5764  5792 I Babel_SMS: MmsConfig.loadFromDatabase
,03-17 12:56:45.437  5764  5792 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
03-17 12:56:45.437  5764  5792 I Babel_SMS: MmsConfig.loadFromResources
,03-17 12:56:45.447  5724  5724 D CAR.SERVICE: com.google.android.projection.gearhead isn't installed.
03-17 12:56:45.447  5764  5792 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
03-17 12:56:45.447  5764  5792 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,03-17 12:56:45.486  5724  5724 D CAR.TEL.Service: Creating a new CarCallService.
03-17 12:56:45.488  5724  5724 D CAR.TEL.PhoneAdapter: Creating a new PhoneAdapter instance
03-17 12:56:45.490   880  3224 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,03-17 12:56:45.492  5724  5724 D CAR.TEL.PhoneAdapter: setListener: com.google.android.gms.car.dn@3bc6510
,03-17 12:56:45.492   880  1515 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,03-17 12:56:45.497  5724  5724 D CAR.TEL.PhoneAdapter: Returning an existing PhoneAdapter instance.
03-17 12:56:45.497  5724  5724 D CAR.TEL.Service: Starting CarCallService with initial phone null
,03-17 12:56:45.519  1289  1289 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,03-17 12:56:45.520  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 12:56:45.540  5724  5739 W art     : Suspending all threads took: 11.648ms
,03-17 12:56:45.579  5764  5764 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,03-17 12:56:45.583  5764  5764 I Babel_Crash: startup - clean
,03-17 12:56:45.595  5764  5799 I Babel   : deleted: false for 0
,03-17 12:56:45.615  5724  5741 D CAR.SERVICE: Package validated; name: com.android.vending
,03-17 12:56:45.665   880  1593 I ActivityManager: Killing 5533:com.motorola.context/u0a8 (adj 15): empty #7
,03-17 12:56:45.857  5764  5764 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-17 12:56:45.869   880   896 I ActivityManager: Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5802 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
03-17 12:56:45.870   880  1575 W libprocessgroup: failed to open /acct/uid_10008/pid_5533/cgroup.procs: No such file or directory
,03-17 12:56:45.967  5764  5764 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,03-17 12:56:45.976  5764  5764 W VideoCapabilities: Unsupported mime video/mpeg2
,03-17 12:56:46.010  5802  5802 W asset   : Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
03-17 12:56:46.011  5802  5802 W ResourcesManager: Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
,03-17 12:56:46.011  5802  5802 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-17 12:56:46.011  5802  5802 W ResourcesManager: Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,03-17 12:56:46.026  5764  5764 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,03-17 12:56:46.032  5764  5764 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-17 12:56:46.034  5764  5764 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-17 12:56:46.037  5764  5764 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-17 12:56:46.042  5764  5764 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-17 12:56:46.073  5704  5826 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
03-17 12:56:46.074  1569  1569 W Launcher: setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1e117205 new=com.google.android.velvet.VelvetApplication@1e117205
,03-17 12:56:46.080  1948  5288 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
03-17 12:56:46.080  1948  5288 I PkgBroadcastIntentOp: Null package name or gms related package.  Ignoreing.
,03-17 12:56:46.123   880   895 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5827 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,03-17 12:56:46.207  1948  5288 D WearableController: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,03-17 12:56:46.219  5764  5764 I vclib   : onServiceConnected
03-17 12:56:46.219  5764  5764 W Babel   : Attempted to change video mute state without an active call.
,03-17 12:56:46.237  1948  2083 I Icing   : updateResources: need to parse f{com.google.android.gms}
,03-17 12:56:46.249   880  1220 V AlarmManager: send {3cad86e8, *walarm*:com.android.providers.calendar.intent.CalendarProvider2}
,03-17 12:56:46.256  5764  5764 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-17 12:56:46.257  5764  5764 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 12:56:46.267  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 12:56:46.274  5827  5827 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 12:56:46.296  5764  5764 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-17 12:56:46.327  5704  5826 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 252 ms] updated apps [took 252 ms] 
,03-17 12:56:46.329   880  5670 I ActivityManager: Killing 5455:com.android.providers.calendar/u0a5 (adj 15): empty #7
,03-17 12:56:46.385  5764  5764 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-17 12:56:46.385  5764  5764 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-17 12:56:46.400   880   896 W libprocessgroup: failed to open /acct/uid_10005/pid_5455/cgroup.procs: No such file or directory
,03-17 12:56:46.417  2022  2022 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 12:56:46.611   880  1479 I ActivityManager: Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=5859 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,03-17 12:56:46.650   880  1296 I ActivityManager: Killing 5663:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,03-17 12:56:46.655  5859  5859 W ResourcesManager: Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,03-17 12:56:46.700   880  1575 W libprocessgroup: failed to open /acct/uid_10060/pid_5663/cgroup.procs: No such file or directory
,03-17 12:56:46.748   880  1566 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5882 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,03-17 12:56:46.762   880  1575 I ActivityManager: Killing 5625:com.google.android.gm/u0a63 (adj 15): empty #7
,03-17 12:56:46.771   330   330 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 251us total 21.592ms
,03-17 12:56:46.792   330   330 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 244us total 19.932ms
,03-17 12:56:46.805  5556  5602 I qtaguid : Failed write_ctrl(u 39) res=-1 errno=22
03-17 12:56:46.805  5556  5602 I qtaguid : Untagging socket 39 failed errno=-22
03-17 12:56:46.805  5556  5602 W NetworkManagementSocketTagger: untagSocket(39) failed with errno -22
,03-17 12:56:46.814   330   330 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 257us total 20.125ms
,03-17 12:56:46.834   880  3224 W libprocessgroup: failed to open /acct/uid_10063/pid_5625/cgroup.procs: No such file or directory
,03-17 12:56:46.838   880   895 W ActivityManager: getRecentTasks: caller 10032 is using old GET_TASKS but privileged; allowing
,03-17 12:56:46.862  5882  5882 D PhoneMonitor: Register our PhoneStateListener
,03-17 12:56:46.874   880  1479 I ActivityManager: Killing 5747:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,03-17 12:56:46.904  5556  5556 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-17 12:56:46.904  5556  5556 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 12:56:46.912   880  1566 W libprocessgroup: failed to open /acct/uid_10019/pid_5747/cgroup.procs: No such file or directory
,03-17 12:56:46.927  2022  3700 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,03-17 12:56:46.932  1948  5900 I CheckinService: Checking schedule, now: 1458215806932 next: 1458215820134
03-17 12:56:46.932  1948  5900 I CheckinService: active receiver: disabled
,03-17 12:56:46.942   880   880 V AlarmManager: done {25ff50b1, *alarm*:com.android.server.WifiManager.action.START_SCAN} [3676ms]
,03-17 12:56:46.942   880  1231 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=15.86 rxSuccessRate=13.97 targetRoamBSSID=any RSSI=-45
03-17 12:56:46.942   880  1231 E WifiStateMachine: WifiStateMachine CMD_START_SCAN with age=22437 interval=30000 maxinterval=300000
03-17 12:56:46.942   880  1231 E WifiStateMachine: WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
03-17 12:56:46.942   880  1231 E WifiStateMachine: WifiStateMachine CMD_START_SCAN full=false
03-17 12:56:46.943   880  1231 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2457
,03-17 12:56:46.943  1423  1423 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
03-17 12:56:46.944   307  1630 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
03-17 12:56:46.944   307  1630 D MDMCTBK : Event received = CTRL-EVENT-SCAN-STARTED 
,03-17 12:56:46.944   880  1231 E WifiStateMachine: [1,458,215,806,944 ms] noteScanstart no scan source
,03-17 12:56:46.954   323   377 I ThermalEngine: Sensor:xo_therm_pu2:38000 mC
,03-17 12:56:46.980   880  1502 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5902 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 12:56:47.003   498   526 D TCMD    : NL - Read 56 bytes from update socket.
03-17 12:56:47.003   498   526 D TCMD    : NL - message type is RTM_NEWLINK
03-17 12:56:47.003   498   526 D TCMD    : Listening for incoming client connection request
03-17 12:56:47.003   307  1630 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
03-17 12:56:47.003   307  1630 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 1
03-17 12:56:47.003   307  1630 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
03-17 12:56:47.003   307  1630 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 2
03-17 12:56:47.003   307  1630 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
03-17 12:56:47.003   307  1630 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 8
03-17 12:56:47.003   307  1630 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
03-17 12:56:47.003   307  1630 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 1
03-17 12:56:47.003   307  1630 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
03-17 12:56:47.003   307  1630 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 1
03-17 12:56:47.003   307  1630 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5
03-17 12:56:47.003   307  1630 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 5
03-17 12:56:47.003   307  1630 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
03-17 12:56:47.003   307  1630 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 6
03-17 12:56:47.003   307  1630 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
03-17 12:56:47.003   307  1630 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 1
03-17 12:56:47.003   307  1630 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 7
03-17 12:56:47.003   307  1630 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 7
03-17 12:56:47.003   307  1630 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
03-17 12:56:47.003   307  1630 D MDMCTBK : Event received = CTRL-EVENT-SCAN-RESULTS 
,03-17 12:56:47.006   880  1231 E WifiStateMachine: [1,458,215,807,006 ms] noteScanEnd no scan source
,03-17 12:56:47.007   880  1231 E WifiStateMachine: wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@3a878070 sup_state=COMPLETED debouncing=false
,03-17 12:56:47.037   880   895 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5919 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 12:56:47.125  5902  5902 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-17 12:56:47.163  5902  5902 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@1024c64d(com.android.providers.calendar.CalendarProvider2@a21502)
,03-17 12:56:47.232  5556  5556 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 12:56:47.264  5556  5556 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.b(10426): Logging device features
,03-17 12:56:47.272  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 12:56:47.276  5919  5941 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,03-17 12:56:47.276   880  1220 V AlarmManager: send {6a64506, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver}
,03-17 12:56:47.279  5919  5940 I Gmail   : getAccountsCursor
,03-17 12:56:47.319  2022  2037 D DeviceConnectionService: client connected with version: 8298000
,03-17 12:56:47.404   279   739 I SFPerfTracer:      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (31:302 vsyncs) (33:1264)
,03-17 12:56:47.412   279   279 I SFPerfTracer:      triggers: (rate: 13:262) (compose: 0:1) (post: 0:1) (render: 0:2) (37:1170 frames) (38:1264)
03-17 12:56:47.412   279   279 D SFPerfTracer:        layers: (3:10) (FocusedStackFrame (0xb8a81b30): 0:18)* (DimLayer (0xb8a9a118): 0:10)* (StatusBar (0xb8af8db0): 38:171) (NavigationBar (0xb8afc650): 0:47) (com.android.systemui.ImageWallpaper (0xb8b12808): 0:7)* (com.test.thalitest/com.test.thalitest.MainActivity (0xb8a9e2a8): 0:83)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb8b3c768): 0:32) 
,03-17 12:56:47.414   880  1575 I art     : Explicit concurrent mark sweep GC freed 17639(900KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 21MB/31MB, paused 1.700ms total 127.710ms
,03-17 12:56:47.418  2022  2022 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 12:56:47.457  1948  2083 I Icing   : Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,03-17 12:56:47.462   880  1593 I ActivityManager: Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=5948 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 12:56:47.471  2022  2022 D WearableService: callingUid 10016, callindPid: 2022
,03-17 12:56:47.480  5556  5556 E Finsky  : [1] com.google.android.finsky.wear.ba.a(689): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
03-17 12:56:47.480  5556  5556 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6302): Dropping command=hygiene due to Gms not connected
,03-17 12:56:47.483   880  3224 I ActivityManager: Killing 5704:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,03-17 12:56:47.517  1948  2083 I Icing   : Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,03-17 12:56:47.552   880  3224 I ActivityManager: Killing 5802:com.motorola.MotGallery2/u0a27 (adj 15): empty #8
,03-17 12:56:47.585   880  1575 W libprocessgroup: failed to open /acct/uid_10039/pid_5704/cgroup.procs: No such file or directory
,03-17 12:56:47.586   880  1296 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
03-17 12:56:47.587   880  1240 W libprocessgroup: failed to open /acct/uid_10027/pid_5802/cgroup.procs: No such file or directory
,03-17 12:56:47.602  5919  5969 I Gmail   : Observing account changes for notifications
,03-17 12:56:47.630  5948  5948 I Exchange: EasService.onCreate
,03-17 12:56:47.637  5948  5972 I Exchange: RestartPingTask
,03-17 12:56:47.644  5919  5919 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-17 12:56:47.649  5948  5948 I Exchange: RestartPingsTask did not start any pings.
03-17 12:56:47.649  5948  5948 I Exchange: PSS stopIfIdle
03-17 12:56:47.650  5948  5948 I Exchange: PSS has no active accounts; stopping service.
,03-17 12:56:47.697  5919  5940 I Gmail   : getAccountsCursor
,03-17 12:56:47.701  2022  2022 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 12:56:47.705  5948  5948 I Exchange: onDestroy
,03-17 12:56:47.708   880  1240 I ActivityManager: Killing 5827:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,03-17 12:56:47.733   880  1513 W libprocessgroup: failed to open /acct/uid_10090/pid_5827/cgroup.procs: No such file or directory
,03-17 12:56:47.742  2022  2022 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-17 12:56:47.742   880  1240 I ActivityManager: Killing 5882:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,03-17 12:56:47.821   880  1479 W libprocessgroup: failed to open /acct/uid_10035/pid_5882/cgroup.procs: No such file or directory
,03-17 12:56:47.838  1948  5987 D LocationInitializer: Restart initialization of location
,03-17 12:56:47.844  2022  2022 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
03-17 12:56:47.845  2022  4284 E MDM     : [210] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-17 12:56:47.852  5919  5985 E SQLiteLog: (283) recovered 39 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,03-17 12:56:47.859  2022  2022 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 12:56:47.871   880   880 V AlarmManager: done {3cad86e8, *walarm*:com.android.providers.calendar.intent.CalendarProvider2} [1622ms]
,03-17 12:56:47.873  2022  2094 W GCoreFlp: No location to return for getLastLocation()
03-17 12:56:47.874  2022  5988 W FusedLocationProvider: location=null
,03-17 12:56:47.877  5902  5991 E SQLiteLog: (284) automatic index on view_events(_id)
,03-17 12:56:47.924   880  1240 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5993 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,03-17 12:56:47.931  5919  5986 I Gmail   : notifyAccountChanged
,03-17 12:56:47.934  5919  5941 I Gmail   : getAccountsCursor
,03-17 12:56:47.939  2022  2022 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 12:56:47.945  5919  5986 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-17 12:56:47.957  5919  5986 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-17 12:56:47.967  5919  5986 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-17 12:56:47.968  5919  5986 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-17 12:56:47.981  5993  5993 D PhoneMonitor: Register our PhoneStateListener
,03-17 12:56:47.995   880  1479 I ActivityManager: Killing 5859:com.motorola.context/u0a8 (adj 15): empty #7
,03-17 12:56:48.082   880   895 W libprocessgroup: failed to open /acct/uid_10008/pid_5859/cgroup.procs: No such file or directory
03-17 12:56:48.083  2022  5059 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,03-17 12:56:48.106  1948  6013 I CheckinService: Checking schedule, now: 1458215808106 next: 1458215820134
,03-17 12:56:48.108  5919  5976 I Gmail   : getAccountsCursor
,03-17 12:56:48.109  1948  6013 I CheckinService: active receiver: disabled
,03-17 12:56:48.111   880   880 V AlarmManager: done {6a64506, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver} [835ms]
,03-17 12:56:48.120  2022  2022 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 12:56:48.124  5556  6015 I Finsky  : [635] com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService.onHandleIntent(164): Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-17 12:56:48.137  2022  2022 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 12:56:48.173  2022  2539 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,03-17 12:56:48.181  5902  5902 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,03-17 12:56:48.181  5902  5902 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-17 12:56:48.223   880  1081 I ActivityManager: Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=6022 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,03-17 12:56:48.257  6022  6022 W ResourcesManager: Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,03-17 12:56:48.315   880  1220 V AlarmManager: send {bff8c7f, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,03-17 12:56:48.317   880   880 V AlarmManager: done {bff8c7f, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [1ms]
,03-17 12:56:48.483   307   508 I MDMCTBK : NetlinkHandler, power_supply subsys
03-17 12:56:48.483   307   508 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-17 12:56:48.483   307   508 I MDMCTBK : checkDefaultInst, current pid is = 307
03-17 12:56:48.483   307   508 I MDMCTBK : checkDefaultInst, pid match
03-17 12:56:48.483   307   508 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-17 12:56:48.484   307   508 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-17 12:56:48.484   307   508 E MDMCTBK : MdmCutbackHndler,Could not open ''
03-17 12:56:48.484   307   508 I MDMCTBK : NetlinkHandler, power_supply subsys
03-17 12:56:48.484   307   508 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-17 12:56:48.484   307   508 I MDMCTBK : checkDefaultInst, current pid is = 307
03-17 12:56:48.484   307   508 I MDMCTBK : checkDefaultInst, pid match
03-17 12:56:48.484   307   508 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-17 12:56:48.484   307   508 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-17 12:56:48.484   307   508 E MDMCTBK : MdmCutbackHndler,Could not open ''
03-17 12:56:48.484   307   508 I MDMCTBK : NetlinkHandler, power_supply subsys
03-17 12:56:48.484   307   508 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-17 12:56:48.484   307   508 I MDMCTBK : checkDefaultInst, current pid is = 307
03-17 12:56:48.484   307   508 I MDMCTBK : checkDefaultInst, pid match
03-17 12:56:48.484   307   508 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-17 12:56:48.484   307   508 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-17 12:56:48.484   307   508 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-17 12:56:48.525  1289  1289 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-17 12:56:48.525  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 12:56:48.705   880  1479 I ActivityManager: Killing 5902:com.android.providers.calendar/u0a5 (adj 15): empty #7
,03-17 12:56:48.721   880  1479 I ActivityManager: Killing 5948:com.google.android.gm.exchange/u0a60 (adj 15): empty #8
,03-17 12:56:48.739  5575  5606 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,03-17 12:56:48.751   880  1575 W libprocessgroup: failed to open /acct/uid_10005/pid_5902/cgroup.procs: No such file or directory
,03-17 12:56:48.753   880  1502 W libprocessgroup: failed to open /acct/uid_10060/pid_5948/cgroup.procs: No such file or directory
,03-17 12:56:48.762  5575  5606 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-17 12:56:48.860   880  5670 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6048 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 12:56:48.887  6048  6048 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-17 12:56:48.915  6048  6048 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@1024c64d(com.android.providers.calendar.CalendarProvider2@a21502)
,03-17 12:56:49.928  6048  6048 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
03-17 12:56:49.928  6048  6048 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-17 12:56:49.981   880  5670 I ActivityManager: Killing 5724:com.google.android.gms:car/u0a16 (adj 15): empty #7
,03-17 12:56:50.001   880  1594 W libprocessgroup: failed to open /acct/uid_10016/pid_5724/cgroup.procs: No such file or directory
,03-17 12:56:50.007   880  1594 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.car.CarService in 1000ms
,03-17 12:56:50.271  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 12:56:51.432   880  1296 I ActivityManager: Killing 5764:com.google.android.talk/u0a70 (adj 15): empty #7
,03-17 12:56:51.463   880   896 W libprocessgroup: failed to open /acct/uid_10070/pid_5764/cgroup.procs: No such file or directory
,03-17 12:56:51.543  1289  1289 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-17 12:56:51.543  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 12:56:52.663  5919  5971 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-17 12:56:54.558  1289  1289 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-17 12:56:54.559  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 12:56:55.547   880  1220 V AlarmManager: send {141c2d49, *walarm*:android.content.syncmanager.SYNC_ALARM}
,03-17 12:56:55.553   880   880 V AlarmManager: done {141c2d49, *walarm*:android.content.syncmanager.SYNC_ALARM} [5ms]
,03-17 12:56:56.959   323   377 I ThermalEngine: Sensor:xo_therm_pu2:37000 mC
,03-17 12:56:57.574  1289  1289 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-17 12:56:57.575  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 12:56:58.279  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 12:56:58.801   880  1081 I ActivityManager: Waited long enough for: ServiceRecord{22601d68 u0 com.google.android.calendar/com.android.calendar.alerts.AlertService}
,03-17 12:56:59.281  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 12:57:00.001   880  1220 V AlarmManager: send {1827c859, *alarm*:android.intent.action.TIME_TICK}
,03-17 12:57:00.046   880   880 V AlarmManager: done {1827c859, *alarm*:android.intent.action.TIME_TICK} [46ms]
,03-17 12:57:00.589  1289  1289 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-17 12:57:00.590  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 12:57:03.223   880  1220 V AlarmManager: send {3541b64e, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,03-17 12:57:03.236   880  1220 V AlarmManager: send {2cd6c87c, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService}
,03-17 12:57:03.239   880  1220 V AlarmManager: send {25ff50b1, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,03-17 12:57:03.241   880   880 V AlarmManager: done {2cd6c87c, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService} [18ms]
,03-17 12:57:03.258   880   880 V AlarmManager: done {3541b64e, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [36ms]
03-17 12:57:03.259   880   880 V AlarmManager: done {25ff50b1, *alarm*:com.android.server.WifiManager.action.START_SCAN} [36ms]
,03-17 12:57:03.261   880  1231 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=2.31 rxSuccessRate=3.22 targetRoamBSSID=any RSSI=-44
03-17 12:57:03.261   880  1231 E WifiStateMachine: WifiStateMachine CMD_START_SCAN with age=38756 interval=30000 maxinterval=300000
03-17 12:57:03.261   880  1231 E WifiStateMachine: WifiStateMachine CMD_START_SCAN try full band scan age=38756 interval=30000 maxinterval=300000
03-17 12:57:03.261   880  1231 E WifiStateMachine: WifiStateMachine CMD_START_SCAN full=true
03-17 12:57:03.262   880  1231 E WifiStateMachine: WifiStateMachine CMD_START_SCAN bump interval =45000
03-17 12:57:03.262  1423  1423 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,03-17 12:57:03.263   307  1630 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
03-17 12:57:03.263   307  1630 D MDMCTBK : Event received = CTRL-EVENT-SCAN-STARTED 
,03-17 12:57:03.265   880  1231 E WifiStateMachine: [1,458,215,823,265 ms] noteScanstart no scan source
,03-17 12:57:03.279  1948  6081 I CheckinService: Checking schedule, now: 1458215823279 next: 1458215820134
03-17 12:57:03.279  1948  6081 I CheckinService: active receiver: enabled
,03-17 12:57:03.293  1948  6081 I CheckinService: Preparing to send checkin request
03-17 12:57:03.293  1948  6081 I EventLogService: Accumulating logs since 1458215785713
,03-17 12:57:03.342  1948  6081 I CheckinRequestBuilder: Checkin reason type: 8 attempt count: 1
,03-17 12:57:03.344  1948  6081 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,03-17 12:57:03.448  5556  5619 I Finsky  : [625] com.google.android.finsky.b.c.a(289): Completed 0 account content syncs with 0 successful.
,03-17 12:57:03.450  5556  5556 I Finsky  : [1] com.google.android.finsky.services.j.a(150): Installation state replication succeeded.
,03-17 12:57:03.498   880  3224 I art     : Explicit concurrent mark sweep GC freed 18869(892KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 21MB/32MB, paused 1.487ms total 119.414ms
,03-17 12:57:03.547  2022  2022 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 12:57:03.548  2022  2022 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 12:57:03.623   880  1515 I LaunchCheckinHandler: cleanup(): cleared. Last call was 14763 ms ago
,03-17 12:57:03.624   880  1515 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6093 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,03-17 12:57:03.651  6093  6093 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-17 12:57:03.651  6093  6093 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 12:57:03.688  6093  6093 I MultiDex: VM with version 2.1.0 has multidex support
03-17 12:57:03.688  6093  6093 I MultiDex: install
03-17 12:57:03.688  6093  6093 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-17 12:57:03.706  6093  6093 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-17 12:57:03.737   498   526 D TCMD    : NL - Read 56 bytes from update socket.
03-17 12:57:03.737   498   526 D TCMD    : NL - message type is RTM_NEWLINK
03-17 12:57:03.737   498   526 D TCMD    : Listening for incoming client connection request
,03-17 12:57:03.738   307  1630 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 13 
03-17 12:57:03.738   307  1630 D MDMCTBK : Event received = CTRL-EVENT-BSS-ADDED 13 
03-17 12:57:03.738   307  1630 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 14 
03-17 12:57:03.738   307  1630 D MDMCTBK : Event received = CTRL-EVENT-BSS-ADDED 14 
03-17 12:57:03.738   307  1630 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 15 
03-17 12:57:03.738   307  1630 D MDMCTBK : Event received = CTRL-EVENT-BSS-ADDED 15 
03-17 12:57:03.738   307  1630 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 16 
03-17 12:57:03.738   307  1630 D MDMCTBK : Event received = CTRL-EVENT-BSS-ADDED 16 
03-17 12:57:03.739   307  1630 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 17 
03-17 12:57:03.739   307  1630 D MDMCTBK : Event received = CTRL-EVENT-BSS-ADDED 17 
03-17 12:57:03.739   307  1630 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 18 
03-17 12:57:03.739   307  1630 D MDMCTBK : Event received = CTRL-EVENT-BSS-ADDED 18 
03-17 12:57:03.739   307  1630 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 19 
03-17 12:57:03.739   307  1630 D MDMCTBK : Event received = CTRL-EVENT-BSS-ADDED 19 
03-17 12:57:03.739   307  1630 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 20 
03-17 12:57:03.739   307  1630 D MDMCTBK : Event received = CTRL-EVENT-BSS-ADDED 20 
03-17 12:57:03.739   307  1630 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
03-17 12:57:03.739   307  1630 D MDMCTBK : Event received = CTRL-EVENT-SCAN-RESULTS 
,03-17 12:57:03.741  1289  1289 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-17 12:57:03.741  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 12:57:03.744   880  1231 E WifiStateMachine: [1,458,215,823,744 ms] noteScanEnd no scan source
,03-17 12:57:03.747   880  1231 E WifiStateMachine: wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@3a878070 sup_state=COMPLETED debouncing=false
,03-17 12:57:03.763  6093  6093 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
03-17 12:57:03.764  6093  6093 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@16185474: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,03-17 12:57:03.764  6093  6093 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-17 12:57:03.781  2022  2022 D WearableService: callingUid 10016, callindPid: 2022
,03-17 12:57:03.784  1948  6113 D LocationInitializer: Restart initialization of location
03-17 12:57:03.787  2022  2022 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-17 12:57:03.797  2022  2583 E MDM     : [190] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-17 12:57:03.802  2022  2022 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 12:57:03.820  2022  2094 W GCoreFlp: No location to return for getLastLocation()
,03-17 12:57:03.821  2022  6114 W FusedLocationProvider: location=null
,03-17 12:57:03.828  6093  6093 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,03-17 12:57:03.828  6093  6093 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,03-17 12:57:03.926  6093  6112 D NativeLibraryUtils: Install completed successfully. count=14 extracted=0
,03-17 12:57:04.033   309  1241 D WVCdm   : Instantiating CDM.
03-17 12:57:04.034   309   309 I WVCdm   : CdmEngine::OpenSession
03-17 12:57:04.034   309   309 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,03-17 12:57:04.042   309   309 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,03-17 12:57:04.068   309   309 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
,03-17 12:57:04.068   309   309 D DrmWidevineDash: Service_Initialize: starts!
03-17 12:57:04.068   309   309 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
03-17 12:57:04.068   309   309 D QSEECOMAPI: : App is not loaded in QSEE
03-17 12:57:04.068   309   309 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
03-17 12:57:04.068   309   309 E QSEECOMAPI: : Error::Loading image failed with ret = -1
03-17 12:57:04.069   309   309 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,03-17 12:57:04.069   309   309 D QSEECOMAPI: : App is not loaded in QSEE
03-17 12:57:04.069   309   309 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
03-17 12:57:04.069   309   309 E QSEECOMAPI: : Error::Loading image failed with ret = -1
03-17 12:57:04.069   309   309 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
03-17 12:57:04.069   309   309 D QSEECOMAPI: : App is not loaded in QSEE
,03-17 12:57:04.098   309   309 D QSEECOMAPI: : Loaded image: APP id = 3
,03-17 12:57:04.100   309   309 D DrmWidevineDash: Service_Initialize: ends! returns 0
03-17 12:57:04.100   309   309 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4e94000
03-17 12:57:04.100   309   309 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4e94000
,03-17 12:57:04.109   309   309 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
,03-17 12:57:04.109   309   309 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,03-17 12:57:04.109   309   309 D DrmWidevineDash: hlos api version =  9
03-17 12:57:04.109   309   309 D DrmWidevineDash: tz api version =  8
03-17 12:57:04.109   309   309 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
03-17 12:57:04.109   309   309 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,03-17 12:57:04.116   309   309 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
,03-17 12:57:04.116   309   309 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
03-17 12:57:04.117   309   309 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xbee7a4e0
03-17 12:57:04.117   309   309 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
03-17 12:57:04.117   309   309 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
03-17 12:57:04.117   309   309 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb9060e08, dataLength=8
,03-17 12:57:04.117   309   309 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,03-17 12:57:04.119   309   309 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb9146518, wrapped_rsa_key_length=1280
,03-17 12:57:04.122   309   309 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,03-17 12:57:04.122   309   309 I WVCdm   : CdmEngine::QueryKeyControlInfo
03-17 12:57:04.123   309  1422 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
03-17 12:57:04.123   309  1422 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
03-17 12:57:04.123   309  1422 I WVCdm   : CdmEngine::GenerateKeyRequest
03-17 12:57:04.123   309  1422 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb9191df0, idLength=0xb12e5730
,03-17 12:57:04.131   309  1422 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
03-17 12:57:04.131   309  1422 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
,03-17 12:57:04.131   309  1422 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
03-17 12:57:04.131   309  1422 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 25
03-17 12:57:04.131   309  1422 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
03-17 12:57:04.131   309  1422 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!
03-17 12:57:04.131   309  1422 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0x0
03-17 12:57:04.131   309  1422 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
03-17 12:57:04.132   309  1422 D DrmWidevineDash: hlos api version =  9
,03-17 12:57:04.132   309  1422 D DrmWidevineDash: tz api version =  8
03-17 12:57:04.132   309  1422 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
03-17 12:57:04.132   309  1422 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
03-17 12:57:04.132   309  1422 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
03-17 12:57:04.132   309  1422 D WVCdm   : PrepareKeyRequest: nonce=3707848038
03-17 12:57:04.132   309  1422 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb9097448
,03-17 12:57:04.132   309  1422 D DrmWidevineDash: message_length=1591, signature=0xb91564f0, signature_length=2972604180
,03-17 12:57:04.321   309  1422 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,03-17 12:57:04.322   309   979 I WVCdm   : CdmEngine::CloseSession
03-17 12:57:04.322   309   979 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
03-17 12:57:04.322   309   979 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
,03-17 12:57:04.323   309   979 I WVCdm   : L3 Terminate.
03-17 12:57:04.323   309   979 D DrmWidevineDash: OEMCrypto_Terminate: starts!
03-17 12:57:04.323   309   979 D DrmWidevineDash: Service_Uninitialize: starts!
03-17 12:57:04.323   309   979 D QSEECOMAPI: : QSEECom_dealloc_memory 
03-17 12:57:04.323   309   979 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
03-17 12:57:04.323   309   979 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
,03-17 12:57:04.324   309   979 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,03-17 12:57:04.608  6131  6131 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=28 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,03-17 12:57:04.702  6131  6131 I dex2oat : dex2oat took 93.891ms (threads: 4)
,03-17 12:57:04.718  6093  6108 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-17 12:57:04.718  6093  6108 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-17 12:57:04.718  6093  6108 I Adreno-EGL: Build Date: 10/28/14 Tue
03-17 12:57:04.718  6093  6108 I Adreno-EGL: Local Branch: 
03-17 12:57:04.718  6093  6108 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-17 12:57:04.718  6093  6108 I Adreno-EGL: Local Patches: NONE
03-17 12:57:04.718  6093  6108 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,03-17 12:57:04.812  6093  6108 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-17 12:57:04.812  6093  6108 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-17 12:57:04.812  6093  6108 I Adreno-EGL: Build Date: 10/28/14 Tue
03-17 12:57:04.812  6093  6108 I Adreno-EGL: Local Branch: 
03-17 12:57:04.812  6093  6108 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-17 12:57:04.812  6093  6108 I Adreno-EGL: Local Patches: NONE
03-17 12:57:04.812  6093  6108 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,03-17 12:57:05.037  6093  6108 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-17 12:57:05.037  6093  6108 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-17 12:57:05.037  6093  6108 I Adreno-EGL: Build Date: 10/28/14 Tue
03-17 12:57:05.037  6093  6108 I Adreno-EGL: Local Branch: 
03-17 12:57:05.037  6093  6108 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-17 12:57:05.037  6093  6108 I Adreno-EGL: Local Patches: NONE
03-17 12:57:05.037  6093  6108 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,03-17 12:57:05.097  6093  6108 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-17 12:57:05.097  6093  6108 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-17 12:57:05.097  6093  6108 I Adreno-EGL: Build Date: 10/28/14 Tue
03-17 12:57:05.097  6093  6108 I Adreno-EGL: Local Branch: 
03-17 12:57:05.097  6093  6108 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-17 12:57:05.097  6093  6108 I Adreno-EGL: Local Patches: NONE
03-17 12:57:05.097  6093  6108 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,03-17 12:57:05.318   309   979 I WVCdm   : CdmEngine::OpenSession
03-17 12:57:05.318   309   979 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,03-17 12:57:05.320   309   979 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,03-17 12:57:05.338   309   979 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
03-17 12:57:05.338   309   979 D DrmWidevineDash: Service_Initialize: starts!
03-17 12:57:05.338   309   979 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
03-17 12:57:05.338   309   979 D QSEECOMAPI: : App is not loaded in QSEE
,03-17 12:57:05.338   309   979 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
,03-17 12:57:05.338   309   979 E QSEECOMAPI: : Error::Loading image failed with ret = -1
03-17 12:57:05.338   309   979 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
03-17 12:57:05.338   309   979 D QSEECOMAPI: : App is not loaded in QSEE
03-17 12:57:05.338   309   979 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
03-17 12:57:05.338   309   979 E QSEECOMAPI: : Error::Loading image failed with ret = -1
03-17 12:57:05.339   309   979 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
03-17 12:57:05.339   309   979 D QSEECOMAPI: : App is not loaded in QSEE
,03-17 12:57:05.367   309   979 D QSEECOMAPI: : Loaded image: APP id = 3
,03-17 12:57:05.369   309   979 D DrmWidevineDash: Service_Initialize: ends! returns 0
,03-17 12:57:05.369   309   979 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4e94000
,03-17 12:57:05.369   309   979 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4e94000
,03-17 12:57:05.374   309   979 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
,03-17 12:57:05.374   309   979 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
03-17 12:57:05.375   309   979 D DrmWidevineDash: hlos api version =  9
03-17 12:57:05.375   309   979 D DrmWidevineDash: tz api version =  8
03-17 12:57:05.375   309   979 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
,03-17 12:57:05.375   309   979 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,03-17 12:57:05.381   309   979 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
,03-17 12:57:05.381   309   979 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
03-17 12:57:05.381   309   979 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb54cf960
03-17 12:57:05.381   309   979 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
03-17 12:57:05.381   309   979 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
,03-17 12:57:05.381   309   979 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb9156f08, dataLength=8
03-17 12:57:05.382   309   979 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
03-17 12:57:05.382   309   979 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb9146518, wrapped_rsa_key_length=1280
03-17 12:57:05.385   309   979 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,03-17 12:57:05.385   309   979 I WVCdm   : CdmEngine::QueryKeyControlInfo
,03-17 12:57:05.387   309  2229 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,03-17 12:57:05.387   309  2229 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
03-17 12:57:05.387   309  2229 I WVCdm   : CdmEngine::GenerateKeyRequest
03-17 12:57:05.387   309  2229 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb9191e10, idLength=0xb5029730
,03-17 12:57:05.393   309  2229 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
,03-17 12:57:05.393   309  2229 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
,03-17 12:57:05.394   309  2229 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
03-17 12:57:05.394   309  2229 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 25
03-17 12:57:05.394   309  2229 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
03-17 12:57:05.394   309  2229 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!
,03-17 12:57:05.394   309  2229 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0x0
03-17 12:57:05.394   309  2229 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
03-17 12:57:05.394   309  2229 D DrmWidevineDash: hlos api version =  9
03-17 12:57:05.394   309  2229 D DrmWidevineDash: tz api version =  8
03-17 12:57:05.394   309  2229 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
,03-17 12:57:05.394   309  2229 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
,03-17 12:57:05.395   309  2229 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
,03-17 12:57:05.395   309  2229 D WVCdm   : PrepareKeyRequest: nonce=3483812938
03-17 12:57:05.395   309  2229 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb9097448
03-17 12:57:05.395   309  2229 D DrmWidevineDash: message_length=1622, signature=0xb9150310, signature_length=3036845844
,03-17 12:57:05.582   309  2229 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,03-17 12:57:05.584   309   309 I WVCdm   : CdmEngine::CloseSession
,03-17 12:57:05.584   309   309 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
03-17 12:57:05.584   309   309 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
03-17 12:57:05.584   309   309 I WVCdm   : L3 Terminate.
03-17 12:57:05.584   309   309 D DrmWidevineDash: OEMCrypto_Terminate: starts!
,03-17 12:57:05.584   309   309 D DrmWidevineDash: Service_Uninitialize: starts!
03-17 12:57:05.584   309   309 D QSEECOMAPI: : QSEECom_dealloc_memory 
03-17 12:57:05.584   309   309 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
03-17 12:57:05.585   309   309 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
03-17 12:57:05.585   309   309 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,03-17 12:57:05.604  1948  6081 I CheckinRequestBuilder: Classify the device as Phone.
,03-17 12:57:05.777  1948  6081 I CheckinTask: Sending checkin request (9674 bytes)
,03-17 12:57:06.285  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 12:57:06.302  1948  6081 I CheckinRequestBuilder: Checkin reason type: 8 attempt count: 1
,03-17 12:57:06.304  1948  6081 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,03-17 12:57:06.439  1948  6081 I CheckinRequestBuilder: Classify the device as Phone.
,03-17 12:57:06.466  1948  6081 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,03-17 12:57:06.475  1948  6081 I CheckinService: Checking schedule, now: 1458215826475 next: 1458816963466
03-17 12:57:06.475  1948  6081 I CheckinService: active receiver: disabled
,03-17 12:57:06.494  1948  1948 D CheckinService: Recording last checkin time for package unspecified as 1458215826493
,03-17 12:57:06.508  5993  5993 V SetupWizard: Connected to Gservices successfully
,03-17 12:57:06.540  2022  3700 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,03-17 12:57:06.758  1289  1289 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-17 12:57:06.759  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 12:57:06.963   323   377 I ThermalEngine: Sensor:xo_therm_pu2:36000 mC
,03-17 12:57:08.286  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 12:57:09.122   880  1515 I ActivityManager: Killing 6048:com.android.providers.calendar/u0a5 (adj 13): empty #7
,03-17 12:57:09.140   880  1515 I ActivityManager: Killing 6022:com.motorola.context/u0a8 (adj 15): empty #8
,03-17 12:57:09.161   880  1515 I ActivityManager: Killing 5919:com.google.android.gm/u0a63 (adj 15): empty #9
,03-17 12:57:09.181   880  5670 W libprocessgroup: failed to open /acct/uid_10005/pid_6048/cgroup.procs: No such file or directory
,03-17 12:57:09.184   880  1546 W libprocessgroup: failed to open /acct/uid_10008/pid_6022/cgroup.procs: No such file or directory
,03-17 12:57:09.186   880  1296 W libprocessgroup: failed to open /acct/uid_10063/pid_5919/cgroup.procs: No such file or directory
,03-17 12:57:09.774  1289  1289 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-17 12:57:09.775  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 12:57:12.113  1459  1459 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,03-17 12:57:12.782   880  1216 D BatteryService: uevent={POWER_SUPPLY_TEMP=323, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311383, SEQNUM=4387, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-11318, POWER_SUPPLY_CHARGE_COUNTER=-247, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,03-17 12:57:12.794  1289  1289 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,03-17 12:57:12.794  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 12:57:12.865  2588  2658 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-17 12:57:12.900  2588  2658 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-17 12:57:13.361   880  1222 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-17 12:57:13.433   880  1081 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=6176 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,03-17 12:57:13.534   880   880 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
03-17 12:57:13.534   880   880 I BackupManagerService: Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-17 12:57:13.540   880   880 I BackupManagerService: Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-17 12:57:13.548   880   880 V BackupManagerService: Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-17 12:57:13.550   880   880 V BackupManagerService: Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@29f597d2
,03-17 12:57:13.563  2022  2022 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,03-17 12:57:13.577  1569  1569 I Launcher: Deferring update until onResume
,03-17 12:57:13.822   880  1575 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=6209 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,03-17 12:57:13.870   880   895 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6222 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,03-17 12:57:13.872   880   895 I ActivityManager: Killing 5575:com.google.android.calendar/u0a49 (adj 15): empty #7
,03-17 12:57:13.964   880  1546 I ActivityManager: Killing 5556:com.android.vending/u0a32 (adj 15): empty #7
,03-17 12:57:14.000   880  3224 W libprocessgroup: failed to open /acct/uid_10049/pid_5575/cgroup.procs: No such file or directory
,03-17 12:57:14.008   880   896 W libprocessgroup: failed to open /acct/uid_10032/pid_5556/cgroup.procs: No such file or directory
,03-17 12:57:14.023  6222  6222 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 12:57:14.226  6222  6253 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
03-17 12:57:14.226  6222  6253 I Babel_SMS: MmsConfig.loadMmsSettings
03-17 12:57:14.226  6222  6253 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
03-17 12:57:14.226  6222  6253 I Babel_SMS: MmsConfig.loadFromDatabase
,03-17 12:57:14.271  6222  6253 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
03-17 12:57:14.271  6222  6253 I Babel_SMS: MmsConfig.loadFromResources
,03-17 12:57:14.278  6222  6253 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
03-17 12:57:14.278  6222  6253 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,03-17 12:57:14.291  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 12:57:14.340  6222  6222 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,03-17 12:57:14.345  6222  6222 I Babel_Crash: startup - clean
,03-17 12:57:14.363  6222  6260 I Babel   : deleted: false for 0
,03-17 12:57:14.447  6222  6222 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-17 12:57:14.454   880  1502 I ActivityManager: Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=6262 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 12:57:14.475   330   330 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 256us total 20.793ms
,03-17 12:57:14.495   330   330 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 18.892ms
,03-17 12:57:14.508  6222  6222 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
03-17 12:57:14.511  6222  6222 W VideoCapabilities: Unsupported mime video/mpeg2
,03-17 12:57:14.517   330   330 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 19.753ms
,03-17 12:57:14.545  6262  6262 W asset   : Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
03-17 12:57:14.545  6262  6262 W ResourcesManager: Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
,03-17 12:57:14.545  6262  6262 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-17 12:57:14.545  6262  6262 W ResourcesManager: Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,03-17 12:57:14.557  6222  6222 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
03-17 12:57:14.564  6222  6222 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
03-17 12:57:14.566  6222  6222 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
03-17 12:57:14.568  6222  6222 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-17 12:57:14.584  6222  6222 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-17 12:57:14.640   880  1546 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6287 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 12:57:14.655   880  1296 I ActivityManager: Killing 5993:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,03-17 12:57:14.750   880  1502 W libprocessgroup: failed to open /acct/uid_10035/pid_5993/cgroup.procs: No such file or directory
,03-17 12:57:14.760  6222  6222 I vclib   : onServiceConnected
,03-17 12:57:14.761  6222  6222 W Babel   : Attempted to change video mute state without an active call.
,03-17 12:57:14.777  6222  6222 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-17 12:57:14.778  6222  6222 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 12:57:14.817  6222  6222 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-17 12:57:14.880  6222  6222 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,03-17 12:57:14.880  6222  6222 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-17 12:57:14.931   880  1566 I art     : Explicit concurrent mark sweep GC freed 24327(1275KB) AllocSpace objects, 2(123KB) LOS objects, 33% free, 21MB/32MB, paused 1.322ms total 122.432ms
,03-17 12:57:14.967  6287  6287 I Finsky  : [1] com.google.android.finsky.FinskyApp.onCreate(358): Initializing network with DFE https://android.clients.google.com/fdfe/
,03-17 12:57:15.066  6287  6287 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(122): No need to run daily hygiene.
,03-17 12:57:15.081  6287  6287 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-17 12:57:15.081  6287  6287 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-17 12:57:15.124  6287  6287 I Finsky  : [1] com.google.android.finsky.receivers.h.a(1107): Installer kick - no action, not running yet
03-17 12:57:15.124  6287  6336 D Ads     : Skipping gmscore version check
,03-17 12:57:15.124  6287  6287 I Finsky  : [1] com.google.android.finsky.g.j.run(208): Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
03-17 12:57:15.125  6287  6287 I Finsky  : [1] com.google.android.finsky.g.j.run(214): Finished loading 1 libraries.
,03-17 12:57:15.129  6287  6287 I Finsky  : [1] com.google.android.finsky.b.j.a(273): result=false type=4
,03-17 12:57:15.148  1569  1569 W Launcher: setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1e117205 new=com.google.android.velvet.VelvetApplication@1e117205
03-17 12:57:15.148  6176  6337 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,03-17 12:57:15.153  6287  6287 I Finsky  : [1] com.google.android.finsky.services.ar.a(1049): Restore complete with 0 success and 0 failed.
,03-17 12:57:15.161  1948  6340 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
03-17 12:57:15.161  1948  6340 I PkgBroadcastIntentOp: Null package name or gms related package.  Ignoreing.
,03-17 12:57:15.200   880  1498 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6342 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,03-17 12:57:15.224  1948  6340 D WearableController: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,03-17 12:57:15.242  1948  2083 I Icing   : updateResources: need to parse f{com.google.android.gms}
,03-17 12:57:15.270  6342  6342 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 12:57:15.279  6176  6337 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 129 ms] updated apps [took 129 ms] 
,03-17 12:57:15.292  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 12:57:15.527   880  1296 I ActivityManager: Killing 6093:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,03-17 12:57:15.556   880  1515 W libprocessgroup: failed to open /acct/uid_10016/pid_6093/cgroup.procs: No such file or directory
,03-17 12:57:15.811  1289  1289 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-17 12:57:15.811  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 12:57:16.343  1948  2083 I Icing   : Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,03-17 12:57:16.394  1948  2083 I Icing   : Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,03-17 12:57:16.968   323   377 I ThermalEngine: Sensor:xo_therm_pu2:35000 mC
,03-17 12:57:18.826  1289  1289 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-17 12:57:18.827  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 12:57:19.955   880  1594 I ActivityManager: Killing 6209:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,03-17 12:57:19.972   880  1575 W libprocessgroup: failed to open /acct/uid_10019/pid_6209/cgroup.procs: No such file or directory
,03-17 12:57:21.842  1289  1289 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-17 12:57:21.843  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 12:57:22.233   880  1498 I ActivityManager: Killing 6262:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,03-17 12:57:22.252   880  1502 W libprocessgroup: failed to open /acct/uid_10027/pid_6262/cgroup.procs: No such file or directory
,03-17 12:57:23.298  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 12:57:24.305  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 12:57:24.858  1289  1289 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-17 12:57:24.858  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 12:57:25.558   880  1220 V AlarmManager: send {141c2d49, *walarm*:android.content.syncmanager.SYNC_ALARM}
,03-17 12:57:25.562   880   880 V AlarmManager: done {141c2d49, *walarm*:android.content.syncmanager.SYNC_ALARM} [3ms]
,03-17 12:57:25.614   880  1079 I ActivityManager: Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=6377 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,03-17 12:57:25.629  1948  6386 E ActivityThread: Failed to find provider info for com.android.contacts.metadata
,03-17 12:57:25.707   880  1079 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 198586, reason: UserStart
,03-17 12:57:25.939  6377  6377 I GAv4    : Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
03-17 12:57:25.939  6377  6377 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-17 12:57:25.939  6377  6377 I GAv4    :   adb logcat -s GAv4
,03-17 12:57:25.959  6377  6377 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-17 12:57:25.978  6377  6377 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-17 12:57:25.983  6377  6412 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-17 12:57:26.006  6377  6377 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,03-17 12:57:26.106   880  1220 V AlarmManager: send {38cc1324, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
03-17 12:57:26.106   880  1220 V AlarmManager: send {25ff50b1, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,03-17 12:57:26.111   880   880 V AlarmManager: done {38cc1324, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [5ms]
,03-17 12:57:26.112   880  1231 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.88 rxSuccessRate=0.75 targetRoamBSSID=any RSSI=-45
03-17 12:57:26.112   880  1231 E WifiStateMachine: WifiStateMachine CMD_START_SCAN with age=22851 interval=45000 maxinterval=300000
03-17 12:57:26.112   880  1231 E WifiStateMachine: WifiStateMachine CMD_START_SCAN full=false
03-17 12:57:26.112   880  1231 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2457
,03-17 12:57:26.113  1423  1423 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
03-17 12:57:26.113   307  1630 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
03-17 12:57:26.113   307  1630 D MDMCTBK : Event received = CTRL-EVENT-SCAN-STARTED 
,03-17 12:57:26.114   880  1231 E WifiStateMachine: [1,458,215,846,114 ms] noteScanstart no scan source
,03-17 12:57:26.115   880   880 V AlarmManager: done {25ff50b1, *alarm*:com.android.server.WifiManager.action.START_SCAN} [10ms]
,03-17 12:57:26.148   278   402 E Vold    : Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.docs/cache/
03-17 12:57:26.148   278   402 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 12:57:26.150  6377  6420 W ContextImpl: Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs/cache
,03-17 12:57:26.181   307  1630 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 9
03-17 12:57:26.181   307  1630 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 9
03-17 12:57:26.181   307  1630 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
,03-17 12:57:26.181   307  1630 D MDMCTBK : Event received = CTRL-EVENT-SCAN-RESULTS 
03-17 12:57:26.181   498   526 D TCMD    : NL - Read 56 bytes from update socket.
03-17 12:57:26.181   498   526 D TCMD    : NL - message type is RTM_NEWLINK
03-17 12:57:26.181   498   526 D TCMD    : Listening for incoming client connection request
,03-17 12:57:26.183  6377  6377 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-17 12:57:26.183  6377  6377 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 12:57:26.186   880  1231 E WifiStateMachine: [1,458,215,846,186 ms] noteScanEnd no scan source
,03-17 12:57:26.187  6377  6421 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-17 12:57:26.188  6377  6421 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 12:57:26.191   880  1231 E WifiStateMachine: wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@3a878070 sup_state=COMPLETED debouncing=false
,03-17 12:57:26.262  6377  6377 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-17 12:57:26.321  6377  6377 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,03-17 12:57:26.321  6377  6377 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-17 12:57:26.344  2022  2022 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 12:57:26.352  2022  6434 I VacuumService: Vacuum at: now=1458215846352 tag=VacuumService
,03-17 12:57:26.381   880  1575 I ActivityManager: Killing 6222:com.google.android.talk/u0a70 (adj 15): empty #7
,03-17 12:57:26.422   880  5670 W libprocessgroup: failed to open /acct/uid_10070/pid_6222/cgroup.procs: No such file or directory
,03-17 12:57:26.436  2022  2022 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 12:57:26.814  2022  6450 I PhenotypeConfigurator: Scheduling Phenotype for one-off execution 13367 seconds from now (1458215846814)
,03-17 12:57:26.936  2022  6445 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,03-17 12:57:26.944  2022  6445 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-17 12:57:26.972   323   377 I ThermalEngine: Sensor:xo_therm_pu2:35000 mC
,03-17 12:57:27.307  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 12:57:27.870  1289  1289 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-17 12:57:27.870  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 12:57:28.792  2022  2022 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 12:57:28.794  2022  2022 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 12:57:30.886  1289  1289 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-17 12:57:30.887  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 12:57:30.981   880  1242 E BackupManagerService: Timeout restoring application @pm@
03-17 12:57:30.982   880  1242 W BackupManagerService: Tried to clear data for @pm@ but not found
,03-17 12:57:30.989  2022  2103 W GmsBackupTransport: Restore processing aborted, no more packages
,03-17 12:57:30.992   880  1242 E BackupManagerService: Failure getting next package name
03-17 12:57:30.992   880  1242 E BackupManagerService: Duplicate finish
,03-17 12:57:31.311  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 12:57:32.781   880  1216 D BatteryService: uevent={POWER_SUPPLY_TEMP=317, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311831, SEQNUM=4409, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-11318, POWER_SUPPLY_CHARGE_COUNTER=-311, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,03-17 12:57:32.844  2588  2658 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-17 12:57:33.902  1289  1289 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-17 12:57:33.902  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 12:57:36.498   307   508 I MDMCTBK : NetlinkHandler, power_supply subsys
03-17 12:57:36.498   307   508 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-17 12:57:36.498   307   508 I MDMCTBK : checkDefaultInst, current pid is = 307
03-17 12:57:36.498   307   508 I MDMCTBK : checkDefaultInst, pid match
03-17 12:57:36.498   307   508 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-17 12:57:36.498   307   508 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-17 12:57:36.498   307   508 E MDMCTBK : MdmCutbackHndler,Could not open ''
03-17 12:57:36.498   307   508 I MDMCTBK : NetlinkHandler, power_supply subsys
03-17 12:57:36.498   307   508 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-17 12:57:36.499   307   508 I MDMCTBK : checkDefaultInst, current pid is = 307
03-17 12:57:36.499   307   508 I MDMCTBK : checkDefaultInst, pid match
03-17 12:57:36.499   307   508 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-17 12:57:36.499   307   508 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-17 12:57:36.499   307   508 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-17 12:57:36.761  1416  1607 I Keyboard.Facilitator.LanguageModelFlusher: run()
,03-17 12:57:36.767  1416  1607 I Keyboard.Facilitator: flushDynamicLanguageModels()
,03-17 12:57:36.818  2022  2022 I ConfigService: onCreate
,03-17 12:57:36.916  1289  1289 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-17 12:57:36.917  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 12:57:36.977   323   377 I ThermalEngine: Sensor:xo_therm_pu2:35000 mC
,03-17 12:57:39.932  1289  1289 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-17 12:57:39.932  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 12:57:41.874  2022  2022 I ConfigService: onDestroy
,03-17 12:57:42.947  1289  1289 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-17 12:57:42.947  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 12:57:43.224   880  1220 V AlarmManager: send {25ff50b1, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,03-17 12:57:43.227   880   880 V AlarmManager: done {25ff50b1, *alarm*:com.android.server.WifiManager.action.START_SCAN} [3ms]
,03-17 12:57:43.230   880  1231 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.86 rxSuccessRate=0.46 targetRoamBSSID=any RSSI=-44
03-17 12:57:43.230   880  1231 E WifiStateMachine: WifiStateMachine CMD_START_SCAN with age=39969 interval=45000 maxinterval=300000
03-17 12:57:43.231   880  1231 E WifiStateMachine: WifiStateMachine CMD_START_SCAN full=false
03-17 12:57:43.231   880  1231 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2457
03-17 12:57:43.232  1423  1423 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,03-17 12:57:43.232   307  1630 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
03-17 12:57:43.232   307  1630 D MDMCTBK : Event received = CTRL-EVENT-SCAN-STARTED 
,03-17 12:57:43.236   880  1231 E WifiStateMachine: [1,458,215,863,236 ms] noteScanstart no scan source
,03-17 12:57:43.302   307  1630 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
03-17 12:57:43.302   307  1630 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 1
03-17 12:57:43.302   307  1630 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
03-17 12:57:43.302   307  1630 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 1
03-17 12:57:43.302   307  1630 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
03-17 12:57:43.302   307  1630 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 1
03-17 12:57:43.302   307  1630 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
03-17 12:57:43.302   307  1630 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 1
03-17 12:57:43.302   307  1630 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
03-17 12:57:43.302   307  1630 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 1
03-17 12:57:43.302   307  1630 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
03-17 12:57:43.302   307  1630 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 1
03-17 12:57:43.302   307  1630 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
03-17 12:57:43.302   307  1630 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 1
03-17 12:57:43.302   307  1630 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
03-17 12:57:43.302   307  1630 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 2
03-17 12:57:43.302   307  1630 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
03-17 12:57:43.302   307  1630 D MDMCTBK : Event received = CTRL-EVENT-SCAN-RESULTS 
03-17 12:57:43.303   498   526 D TCMD    : NL - Read 56 bytes from update socket.
03-17 12:57:43.303   498   526 D TCMD    : NL - message type is RTM_NEWLINK
03-17 12:57:43.303   498   526 D TCMD    : Listening for incoming client connection request
,03-17 12:57:43.309   880  1231 E WifiStateMachine: [1,458,215,863,309 ms] noteScanEnd no scan source
,03-17 12:57:43.311   880  1231 E WifiStateMachine: wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@3a878070 sup_state=COMPLETED debouncing=false
,03-17 12:57:45.962  1289  1289 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-17 12:57:45.962  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 12:57:46.982   323   377 I ThermalEngine: Sensor:xo_therm_pu2:34000 mC
,03-17 12:57:48.978  1289  1289 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,03-17 12:57:48.978  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 12:57:51.993  1289  1289 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-17 12:57:51.994  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
03-17 12:57:51.994  1289  1289 I SBar.MotoNetworkCtrlr: refreshSignalCluster[0]: mobile: Signal=0x00000000=( none ) Roaming=0x00000000=( none ) mSimIconId=0x00000000=( none ) Accessibility="Airplane mode.","",""
03-17 12:57:51.994  1289  1289 I SBar.MotoNetworkCtrlr: refreshSignalCluster[0]: mobile: mHasMobileDataFeature=true DataTypeShown=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility=""
,03-17 12:57:54.481   880  1100 I PowerManagerService: Nap time (uid 1000)...
03-17 12:57:54.481   880  1100 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,03-17 12:57:54.507   880  1100 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-17 12:57:54.507   880  1100 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-17 12:57:54.507   880  1100 I Adreno-EGL: Build Date: 10/28/14 Tue
03-17 12:57:54.507   880  1100 I Adreno-EGL: Local Branch: 
03-17 12:57:54.507   880  1100 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-17 12:57:54.507   880  1100 I Adreno-EGL: Local Patches: NONE
03-17 12:57:54.507   880  1100 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,03-17 12:57:55.009   880  1100 D         : activate, handle: 1598182242, enabled: 0, index 2
03-17 12:57:55.009   880  1100 D         : BstSensorExt: id=1598182242, en=0
,03-17 12:57:55.012   880  1100 D         : enable ID_SORI, path /sys/class/srot_sensor/g_sensor/en_disp_rotation, fd 223
,03-17 12:57:55.014  1289  1289 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-17 12:57:55.014  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 12:57:55.019   880  1100 D         : activate, handle: 2, enabled: 0, index 5
,03-17 12:57:55.026   880  1097 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,03-17 12:57:55.028   880   880 V ActivityManager: Display changed displayId=0
,03-17 12:57:55.056   279   279 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb89ff550
,03-17 12:57:55.058   279   279 D qdhwcomposer: hwc_blank: Blanking display: 0
,03-17 12:57:55.177   301   301 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb74d4820
03-17 12:57:55.177   301   301 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
03-17 12:57:55.178   301   301 I rmt_storage: wakelock acquired: 1, error no: 42
,03-17 12:57:55.178   301   819 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1219671928)
,03-17 12:57:55.287   301   819 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
03-17 12:57:55.287   301   819 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,03-17 12:57:55.289   301   819 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1219671928) wakelock released: 1, error no: 0
03-17 12:57:55.289   301   819 I rmt_storage: 
,03-17 12:57:55.292   301   301 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb74d4820
,03-17 12:57:55.390   279   700 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,03-17 12:57:55.392   279   279 I qdhwcomposer: enable_dcabc: Done setting OFF mode
,03-17 12:57:55.392   279   279 D qdhwcomposer: hwc_blank: Done blanking display: 0
,03-17 12:57:55.394   880  1250 D SurfaceControl: Excessive delay in setPowerMode(): 368ms
,03-17 12:57:55.401   880   880 I WindowManager: AOD feature not enabled!
,03-17 12:57:55.414  1459  4227 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,03-17 12:57:55.424   279   279 I SFPerfTracer:       trigger: frame rate (-30.845%)	(41.493 fps)	(24.100 ms) 	(4 drops)	(16 frames)
03-17 12:57:55.424   279   279 I SFPerfTracer:      triggers: (rate: 14:266) (compose: 0:2) (post: 0:1) (render: 0:3) (16:1188 frames) (17:1292)
03-17 12:57:55.425   279   279 D SFPerfTracer:        layers: (4:10) (FocusedStackFrame (0xb8a81b30): 0:18)* (DimLayer (0xb8a9a118): 0:10)* (StatusBar (0xb8af8db0): 0:175) (NavigationBar (0xb8afc650): 0:47) (com.android.systemui.ImageWallpaper (0xb8b12808): 0:7)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb8b3c768): 0:32) (ColorFade (0xb8a9e2a8): 17:19) 
,03-17 12:57:55.450   880  1100 I PowerManagerService: Sleeping (uid 1000)...
,03-17 12:57:55.480   880  1231 D WifiStateMachine: backgroundScan enabled=false startBackgroundScanIfNeeded:false
03-17 12:57:55.480   880  1231 E WifiStateMachine: handleScreenStateChanged Exit: true
,03-17 12:57:55.482   309  1422 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,03-17 12:57:55.490   309  1422 V msm8974_platform: platform_set_parameters: enter: screen_state=on
03-17 12:57:55.490   309  1422 V msm8974_platform: platform_set_parameters: exit with code(0)
03-17 12:57:55.490   309  1422 E msm8974_platform: platform_update_tpa_poll: Could not get ctl for mixer cmd - TPA6165 POLL ACC DET
03-17 12:57:55.491   309  1422 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
,03-17 12:57:55.493   309  1422 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
,03-17 12:57:55.497   880  1231 E WifiStateMachine: setSuspendOptimizationsNative: 4 false -want true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
03-17 12:57:55.497   880  1231 E native  : do suspend false
,03-17 12:57:55.615   880  1220 V AlarmManager: send {141c2d49, *walarm*:android.content.syncmanager.SYNC_ALARM}
,03-17 12:57:55.617   880   880 V AlarmManager: done {141c2d49, *walarm*:android.content.syncmanager.SYNC_ALARM} [2ms]
,03-17 12:57:55.818   880   880 D         : activate, handle: 1598182229, enabled: 0, index 0
,03-17 12:57:55.818   880   880 E         : <BST> disable accel, orig state: 1
03-17 12:57:55.818   880   880 I         : <BST> disable sensor <BOSCH BMC150 Acceleration Sensor>
,03-17 12:57:55.820   309   978 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
03-17 12:57:55.820   309   978 V msm8974_platform: platform_set_parameters: enter: screen_state=off
03-17 12:57:55.820   309   978 V msm8974_platform: platform_set_parameters: exit with code(0)
03-17 12:57:55.820   309   978 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
03-17 12:57:55.820   309   978 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
,03-17 12:57:55.827  1416  1416 I Keyboard.Facilitator: onFinishInput()
,03-17 12:57:55.834   880  1231 D WifiStateMachine: backgroundScan enabled=true startBackgroundScanIfNeeded:false
03-17 12:57:55.834   880  1231 E WifiStateMachine: handleScreenStateChanged Exit: false
,03-17 12:57:55.839   880  1231 E WifiStateMachine: setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
,03-17 12:57:55.840   880  1231 E WifiStateMachine: setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
03-17 12:57:55.840   880  1231 E native  : do suspend true
,03-17 12:57:56.986   323   377 I ThermalEngine: Sensor:xo_therm_pu2:34000 mC
,03-17 12:57:57.907  1459  1459 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,03-17 12:57:58.029  1459  1459 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,03-17 12:58:00.434   880  1220 V AlarmManager: send {1827c859, *alarm*:android.intent.action.TIME_TICK}
,03-17 12:58:00.437   880  1220 V AlarmManager: send {3e1ec725, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD}
,03-17 12:58:00.442   880   880 V AlarmManager: done {3e1ec725, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD} [8ms]
,03-17 12:58:00.477   880   880 V AlarmManager: done {1827c859, *alarm*:android.intent.action.TIME_TICK} [44ms]
,03-17 12:58:01.911   880  1216 D BatteryService: uevent={POWER_SUPPLY_TEMP=307, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312523, SEQNUM=4421, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-14623, POWER_SUPPLY_CHARGE_COUNTER=-416, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,03-17 12:58:01.981  2588  2658 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-17 12:58:06.991   323   377 I ThermalEngine: Sensor:xo_therm_pu2:33000 mC
,03-17 12:58:14.509   307   508 I MDMCTBK : NetlinkHandler, power_supply subsys
03-17 12:58:14.509   307   508 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-17 12:58:14.509   307   508 I MDMCTBK : checkDefaultInst, current pid is = 307
03-17 12:58:14.509   307   508 I MDMCTBK : checkDefaultInst, pid match
03-17 12:58:14.509   307   508 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-17 12:58:14.510   307   508 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-17 12:58:14.510   307   508 E MDMCTBK : MdmCutbackHndler,Could not open ''
03-17 12:58:14.510   307   508 I MDMCTBK : NetlinkHandler, power_supply subsys
03-17 12:58:14.510   307   508 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-17 12:58:14.510   307   508 I MDMCTBK : checkDefaultInst, current pid is = 307
03-17 12:58:14.510   307   508 I MDMCTBK : checkDefaultInst, pid match
03-17 12:58:14.510   307   508 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-17 12:58:14.510   307   508 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-17 12:58:14.510   307   508 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-17 12:58:16.995   323   377 I ThermalEngine: Sensor:xo_therm_pu2:33000 mC
,03-17 12:58:25.859   880  1220 V AlarmManager: send {3f6640fa, *walarm*:com.google.android.intent.action.SEND_IDLE}
,03-17 12:58:25.866   880   880 V AlarmManager: done {3f6640fa, *walarm*:com.google.android.intent.action.SEND_IDLE} [7ms]
,03-17 12:58:27.000   323   377 I ThermalEngine: Sensor:xo_therm_pu2:33000 mC
,03-17 12:58:30.009  2746  4320 E global frequency: no tags to log
,03-17 12:58:30.012  2746  4320 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,03-17 12:58:30.028  2746  2746 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-17 12:58:30.033  1551  1568 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,03-17 12:58:30.207   880  1296 I art     : Explicit concurrent mark sweep GC freed 47432(2MB) AllocSpace objects, 2(218KB) LOS objects, 33% free, 21MB/32MB, paused 1.387ms total 134.442ms
,03-17 12:58:30.233  2746  2746 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-17 12:58:30.245  2746  2746 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,03-17 12:58:30.253  2746  2746 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-17 12:58:30.255  1551  1567 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,03-17 12:58:30.345  1459  2835 I art     : Explicit concurrent mark sweep GC freed 56113(3MB) AllocSpace objects, 36(1245KB) LOS objects, 39% free, 7MB/12MB, paused 987us total 45.253ms
,03-17 12:58:30.358  2746  2746 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-17 12:58:30.368  2746  2746 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,03-17 12:58:30.432  2746  2746 I art     : Explicit concurrent mark sweep GC freed 10064(550KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 11MB/18MB, paused 997us total 57.175ms
,03-17 12:58:30.434  2746  2746 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-17 12:58:30.436  1551  2230 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,03-17 12:58:30.494  2746  2746 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-17 12:58:30.506  2746  2746 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,03-17 12:58:30.510  2746  4320 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,03-17 12:58:30.512  2746  4320 I global frequency: BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,03-17 12:58:30.513  2746  4320 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,03-17 12:58:30.514  2746  4320 E global frequency: BcsDSCheckin.logProperties: BL State from property is null or empty
,03-17 12:58:30.515  2746  4320 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,03-17 12:58:30.517  2746  4320 D Checkin : publish the event [tag = DEV_ATTRIBS event name = SW]
,03-17 12:58:30.528  2746  4320 I global frequency: BcsCore.doCallHomeCore: Exceeded maximum number of checkins for one hour. Bailing out
,03-17 12:58:30.528  2746  4320 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,03-17 12:58:30.942  2022  2504 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,03-17 12:58:33.606   880  1220 V AlarmManager: send {384772c6, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,03-17 12:58:33.609   880   880 V AlarmManager: done {384772c6, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [4ms]
,03-17 12:58:35.515   307   508 I MDMCTBK : NetlinkHandler, power_supply subsys
03-17 12:58:35.515   307   508 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-17 12:58:35.516   307   508 I MDMCTBK : checkDefaultInst, current pid is = 307
03-17 12:58:35.516   307   508 I MDMCTBK : checkDefaultInst, pid match
03-17 12:58:35.516   307   508 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-17 12:58:35.516   307   508 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-17 12:58:35.516   307   508 E MDMCTBK : MdmCutbackHndler,Could not open ''
03-17 12:58:35.516   307   508 I MDMCTBK : NetlinkHandler, power_supply subsys
03-17 12:58:35.516   307   508 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-17 12:58:35.516   307   508 I MDMCTBK : checkDefaultInst, current pid is = 307
03-17 12:58:35.516   307   508 I MDMCTBK : checkDefaultInst, pid match
03-17 12:58:35.516   307   508 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-17 12:58:35.516   307   508 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-17 12:58:35.516   307   508 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-17 12:58:37.005   323   377 I ThermalEngine: Sensor:xo_therm_pu2:32000 mC
,03-17 12:58:45.519   307   508 I MDMCTBK : NetlinkHandler, power_supply subsys
03-17 12:58:45.519   307   508 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-17 12:58:45.519   307   508 I MDMCTBK : checkDefaultInst, current pid is = 307
03-17 12:58:45.519   307   508 I MDMCTBK : checkDefaultInst, pid match
03-17 12:58:45.519   307   508 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-17 12:58:45.519   307   508 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-17 12:58:45.519   307   508 E MDMCTBK : MdmCutbackHndler,Could not open ''
03-17 12:58:45.519   307   508 I MDMCTBK : NetlinkHandler, power_supply subsys
03-17 12:58:45.519   307   508 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-17 12:58:45.519   307   508 I MDMCTBK : checkDefaultInst, current pid is = 307
03-17 12:58:45.519   307   508 I MDMCTBK : checkDefaultInst, pid match
03-17 12:58:45.519   307   508 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-17 12:58:45.519   307   508 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-17 12:58:45.519   307   508 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-17 12:58:47.009   323   377 I ThermalEngine: Sensor:xo_therm_pu2:32000 mC
,03-17 12:58:53.768   880  1216 D BatteryService: uevent={POWER_SUPPLY_TEMP=295, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312048, SEQNUM=4425, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-15725, POWER_SUPPLY_CHARGE_COUNTER=-638, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
03-17 12:58:53.770   307   508 I MDMCTBK : NetlinkHandler, power_supply subsys
03-17 12:58:53.770   307   508 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-17 12:58:53.770   307   508 I MDMCTBK : checkDefaultInst, current pid is = 307
03-17 12:58:53.770   307   508 I MDMCTBK : checkDefaultInst, pid match
03-17 12:58:53.770   307   508 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-17 12:58:53.770   307   508 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-17 12:58:53.770   307   508 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-17 12:58:53.817  2588  2658 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-17 12:58:53.859   307   508 I MDMCTBK : NetlinkHandler, power_supply subsys
03-17 12:58:53.859   307   508 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-17 12:58:53.859   307   508 I MDMCTBK : checkDefaultInst, current pid is = 307
03-17 12:58:53.859   307   508 I MDMCTBK : checkDefaultInst, pid match
03-17 12:58:53.859   307   508 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-17 12:58:53.859   307   508 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-17 12:58:53.859   307   508 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-17 12:58:53.916  2588  2658 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-17 12:58:55.828  1416  1607 I Keyboard.Facilitator.LanguageModelFlusher: run()
03-17 12:58:55.828  1416  1607 I Keyboard.Facilitator: flushDynamicLanguageModels()
,03-17 12:58:55.845  2022  2022 I ConfigService: onCreate
,03-17 12:58:57.014   323   377 I ThermalEngine: Sensor:xo_therm_pu2:32000 mC
,03-17 12:59:00.892  2022  2022 I ConfigService: onDestroy
,03-17 12:59:07.019   323   377 I ThermalEngine: Sensor:xo_therm_pu2:32000 mC
,03-17 12:59:17.023   323   377 I ThermalEngine: Sensor:xo_therm_pu2:32000 mC
,03-17 12:59:27.028   323   377 I ThermalEngine: Sensor:xo_therm_pu2:32000 mC
,03-17 12:59:37.032   323   377 I ThermalEngine: Sensor:xo_therm_pu2:32000 mC
,03-17 12:59:47.037   323   377 I ThermalEngine: Sensor:xo_therm_pu2:32000 mC
,03-17 12:59:57.041   323   377 I ThermalEngine: Sensor:xo_therm_pu2:32000 mC
,03-17 13:00:01.001   880  1220 V AlarmManager: send {1827c859, *alarm*:android.intent.action.TIME_TICK}
03-17 13:00:01.003   880  1220 V AlarmManager: send {9b7f552, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,03-17 13:00:01.044   880  1081 I ActivityManager: Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=6521 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,03-17 13:00:01.083   880   880 V AlarmManager: done {1827c859, *alarm*:android.intent.action.TIME_TICK} [83ms]
,03-17 13:00:01.118  6521  6521 I GAv4    : Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
03-17 13:00:01.118  6521  6521 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-17 13:00:01.118  6521  6521 I GAv4    :   adb logcat -s GAv4
,03-17 13:00:01.133  6521  6521 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-17 13:00:01.153  6521  6521 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-17 13:00:01.177  6521  6540 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
03-17 13:00:01.178   880  1502 I ActivityManager: Killing 6287:com.android.vending/u0a32 (adj 15): empty #7
,03-17 13:00:01.178   880   880 V AlarmManager: done {9b7f552, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [178ms]
,03-17 13:00:01.301   880  5670 W libprocessgroup: failed to open /acct/uid_10032/pid_6287/cgroup.procs: No such file or directory
,03-17 13:00:07.046   323   377 I ThermalEngine: Sensor:xo_therm_pu2:32000 mC
,03-17 13:00:13.888   880  1216 D BatteryService: uevent={POWER_SUPPLY_TEMP=287, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312546, SEQNUM=4429, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5408, POWER_SUPPLY_CHARGE_COUNTER=-932, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
03-17 13:00:13.890   307   508 I MDMCTBK : NetlinkHandler, power_supply subsys
03-17 13:00:13.890   307   508 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-17 13:00:13.890   307   508 I MDMCTBK : checkDefaultInst, current pid is = 307
03-17 13:00:13.890   307   508 I MDMCTBK : checkDefaultInst, pid match
03-17 13:00:13.890   307   508 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-17 13:00:13.890   307   508 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-17 13:00:13.890   307   508 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-17 13:00:13.939  2588  2658 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-17 13:00:13.981   307   508 I MDMCTBK : NetlinkHandler, power_supply subsys
03-17 13:00:13.981   307   508 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-17 13:00:13.981   307   508 I MDMCTBK : checkDefaultInst, current pid is = 307
03-17 13:00:13.981   307   508 I MDMCTBK : checkDefaultInst, pid match
03-17 13:00:13.981   307   508 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-17 13:00:13.981   307   508 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-17 13:00:13.981   307   508 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-17 13:00:17.051   323   377 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-17 13:00:27.055   323   377 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-17 13:00:37.060   323   377 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-17 13:00:47.065   323   377 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-17 13:00:57.069   323   377 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-17 13:01:07.074   323   377 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-17 13:01:17.078   323   377 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-17 13:01:27.083   323   377 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-17 13:01:37.088   323   377 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-17 13:01:47.092   323   377 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-17 13:01:57.097   323   377 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-17 13:02:07.101   323   377 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-17 13:02:17.106   323   377 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-17 13:02:27.111   323   377 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-17 13:02:37.115   323   377 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-17 13:02:47.120   323   377 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-17 13:02:57.124   323   377 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-17 13:03:07.129   323   377 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-17 13:03:17.134   323   377 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-17 13:03:27.138   323   377 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-17 13:03:37.143   323   377 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-17 13:03:47.147   323   377 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-17 13:03:57.152   323   377 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-17 13:04:07.156   323   377 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-17 13:04:17.161   323   377 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-17 13:04:27.166   323   377 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-17 13:04:37.170   323   377 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-17 13:04:47.175   323   377 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-17 13:04:54.728   880  1216 D BatteryService: uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312122, SEQNUM=4431, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4306, POWER_SUPPLY_CHARGE_COUNTER=-1263, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
03-17 13:04:54.730   307   508 I MDMCTBK : NetlinkHandler, power_supply subsys
03-17 13:04:54.730   307   508 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-17 13:04:54.730   307   508 I MDMCTBK : checkDefaultInst, current pid is = 307
03-17 13:04:54.730   307   508 I MDMCTBK : checkDefaultInst, pid match
03-17 13:04:54.730   307   508 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-17 13:04:54.731   307   508 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-17 13:04:54.731   307   508 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-17 13:04:54.795   307   508 I MDMCTBK : NetlinkHandler, power_supply subsys
03-17 13:04:54.795   307   508 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-17 13:04:54.795   307   508 I MDMCTBK : checkDefaultInst, current pid is = 307
03-17 13:04:54.796   307   508 I MDMCTBK : checkDefaultInst, pid match
03-17 13:04:54.796   307   508 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-17 13:04:54.796   307   508 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-17 13:04:54.796   307   508 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-17 13:04:54.822  2588  2658 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-17 13:04:57.180   323   377 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-17 13:05:07.184   323   377 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-17 13:05:17.189   323   377 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-17 13:05:27.193   323   377 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-17 13:05:37.198   323   377 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-17 13:05:47.203   323   377 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-17 13:05:57.207   323   377 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-17 13:06:07.212   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:06:17.217   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:06:27.221   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:06:37.226   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:06:47.230   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:06:57.235   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:07:07.240   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:07:17.244   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:07:27.249   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:07:37.253   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:07:47.258   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:07:57.262   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:08:07.267   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:08:17.272   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:08:27.276   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:08:37.281   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:08:47.285   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:08:57.290   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:09:07.295   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:09:17.299   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:09:27.304   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:09:37.308   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:09:47.313   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:09:57.317   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:10:07.322   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:10:17.327   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:10:27.331   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:10:37.336   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:10:47.340   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:10:57.345   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:11:07.350   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:11:17.354   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:11:27.359   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:11:37.363   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:11:47.368   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:11:57.373   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:12:07.377   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:12:17.382   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:12:26.215   880  1216 D BatteryService: uevent={POWER_SUPPLY_TEMP=274, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311781, SEQNUM=4433, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1602, POWER_SUPPLY_CHARGE_COUNTER=-284, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
03-17 13:12:26.217   307   508 I MDMCTBK : NetlinkHandler, power_supply subsys
03-17 13:12:26.217   307   508 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-17 13:12:26.217   307   508 I MDMCTBK : checkDefaultInst, current pid is = 307
03-17 13:12:26.217   307   508 I MDMCTBK : checkDefaultInst, pid match
03-17 13:12:26.217   307   508 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-17 13:12:26.217   307   508 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-17 13:12:26.218   307   508 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-17 13:12:26.264  2588  2658 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-17 13:12:27.386   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:12:37.391   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:12:47.396   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:12:57.400   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:13:07.405   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:13:17.409   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:13:27.414   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:13:37.418   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:13:47.423   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:13:57.428   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:14:07.432   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:14:17.437   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:14:27.441   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:14:37.446   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:14:47.450   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:14:57.455   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:15:07.460   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:15:17.464   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:15:27.469   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:15:31.089   880  1220 V AlarmManager: send {1827c859, *alarm*:android.intent.action.TIME_TICK}
03-17 13:15:31.091   880  1220 V AlarmManager: send {bff8c7f, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
03-17 13:15:31.092   880  1220 V AlarmManager: send {3f7ea023, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
03-17 13:15:31.092   880  1220 V AlarmManager: send {1bc70920, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,03-17 13:15:31.108   880   880 V AlarmManager: done {bff8c7f, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [19ms]
,03-17 13:15:31.134   880   880 V AlarmManager: done {1827c859, *alarm*:android.intent.action.TIME_TICK} [45ms]
,03-17 13:15:31.136   880   880 V AlarmManager: done {3f7ea023, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [48ms]
,03-17 13:15:31.142   880   880 V AlarmManager: done {1bc70920, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [53ms]
,03-17 13:15:31.160  1948  6555 I EventLogService: Aggregate from 1458215823316 (log), 1458215131047 (data)
,03-17 13:15:37.473   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:15:46.691   880  1079 I UsageStatsService: User[0] Flushing usage stats to disk
,03-17 13:15:47.478   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:15:57.483   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:16:07.487   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:16:17.492   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:16:27.496   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:16:37.501   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:16:47.506   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:16:57.510   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:17:07.515   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:17:17.519   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:17:27.524   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:17:37.528   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:17:47.533   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:17:57.538   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:18:07.543   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:18:17.548   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:18:27.552   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:18:37.557   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:18:47.562   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:18:57.566   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:19:07.571   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:19:17.575   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:19:27.580   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:19:37.585   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:19:47.589   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-17 13:19:57.594   323   377 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,TIME-OUT KILL (timeout was 1400000ms),03-17 13:20:03.489  6566  6566 D AndroidRuntime: 
03-17 13:20:03.489  6566  6566 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-17 13:20:03.493  6566  6566 D AndroidRuntime: CheckJNI is OFF
03-17 13:20:03.656  6566  6566 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
03-17 13:20:03.667   880  1081 I ActivityManager: Force stopping com.test.thalitest appid=10109 user=-1: uninstall pkg
03-17 13:20:03.721   880  1133 W PackageSettings: Skipping PackageSetting{3d10c2b com.example.hello/10568} due to missing metadata
03-17 13:20:03.735   880  1133 I ActivityManager: Force stopping com.test.thalitest appid=10109 user=0: pkg removed
03-17 13:20:03.772  3366  3366 I art     : Explicit concurrent mark sweep GC freed 10340(2MB) AllocSpace objects, 20(320KB) LOS objects, 39% free, 7MB/12MB, paused 896us total 30.481ms
03-17 13:20:03.792  2022  2106 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
03-17 13:20:03.792  1416  1416 I Keyboard.Facilitator: resetDictionaries() : en_US
03-17 13:20:03.800   880  1222 I InputReader: Reconfiguring input devices.  changes=0x00000010
03-17 13:20:03.821  1416  6584 I Keyboard.Facilitator.DecoderInitializer: run()
03-17 13:20:03.828  1416  6584 I Decoder : createOrResetDecoder
03-17 13:20:03.851  1622  6594 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
03-17 13:20:03.872   880   895 I ActivityManager: Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=6596 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
03-17 13:20:03.878  1569  1569 I art     : Explicit concurrent mark sweep GC freed 2847(149KB) AllocSpace objects, 4(184KB) LOS objects, 25% free, 13MB/17MB, paused 1.211ms total 132.720ms
03-17 13:20:03.907  1948  1948 I art     : Explicit concurrent mark sweep GC freed 20784(1244KB) AllocSpace objects, 6(96KB) LOS objects, 25% free, 14MB/19MB, paused 980us total 169.215ms
03-17 13:20:03.918   880   880 I art     : Explicit concurrent mark sweep GC freed 18378(1304KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 21MB/32MB, paused 1.922ms total 154.810ms
03-17 13:20:03.919   880  1133 I art     : WaitForGcToComplete blocked for 36.876ms for cause Explicit
03-17 13:20:03.922  1948  1964 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
03-17 13:20:03.932  2022  2022 I ConfigService: onCreate
03-17 13:20:03.971  6596  6596 W asset   : Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
03-17 13:20:03.971  6596  6596 W ResourcesManager: Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
03-17 13:20:03.972  6596  6596 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-17 13:20:03.973  6596  6596 W ResourcesManager: Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
03-17 13:20:03.980  1416  6584 I Keyboard.Facilitator.MainLanguageModelLoader: run()
03-17 13:20:04.032  1416  6584 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
03-17 13:20:04.035  1416  6584 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
03-17 13:20:04.035  1416  6584 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
03-17 13:20:04.038  1416  6584 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
03-17 13:20:04.038  1416  6584 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
03-17 13:20:04.041  1416  6584 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
03-17 13:20:04.041  1416  6584 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
03-17 13:20:04.041   880   880 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
03-17 13:20:04.041   880   880 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-17 13:20:04.043  1416  6584 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
03-17 13:20:04.043  1416  6584 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
03-17 13:20:04.043  1416  6584 I Keyboard.Facilitator.Delight2FileSweeper: run()
03-17 13:20:04.043  1416  6584 I Keyboard.Facilitator.RecurringTaskScheduler: run()
03-17 13:20:04.043  1416  6584 I StatsUtilsManager: startPeriodStatsRecorder() : Success
03-17 13:20:04.043  1416  6584 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
03-17 13:20:04.057   880  1502 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6624 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
03-17 13:20:04.060   880  1251 D TaskPersister: removeObsoleteFile: deleting file=9_task.xml
03-17 13:20:04.060   880  1251 D TaskPersister: removeObsoleteFile: deleting file=9_task_thumbnail.png
03-17 13:20:04.113   880  1240 I ActivityManager: Killing 6176:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
03-17 13:20:04.120   880  1133 I art     : Explicit concurrent mark sweep GC freed 8574(642KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 21MB/32MB, paused 1.799ms total 200.250ms
03-17 13:20:04.123  1569  1569 I Launcher: Deferring update until onResume
03-17 13:20:04.201  6566  6566 D AndroidRuntime: Shutting down VM
03-17 13:20:04.204   880  1479 W libprocessgroup: failed to open /acct/uid_10039/pid_6176/cgroup.procs: No such file or directory
03-17 13:20:04.234  6624  6624 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
03-17 13:20:04.259   880  1133 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6641 uid=10010 gids={50010, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
03-17 13:20:04.312   880  1479 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6659 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 13:20:04.324   880  1502 I ActivityManager: Killing 6342:com.google.android.apps.plus/u0a90 (adj 15): empty #7
03-17 13:20:04.361   880  3224 W libprocessgroup: failed to open /acct/uid_10090/pid_6342/cgroup.procs: No such file or directory
03-17 13:20:04.366   880  1502 I ActivityManager: Killing 6377:com.google.android.apps.docs/u0a57 (adj 15): empty #7
03-17 13:20:04.451   880   896 W libprocessgroup: failed to open /acct/uid_10057/pid_6377/cgroup.procs: No such file or directory
03-17 13:20:04.532  6659  6659 I Finsky  : [1] com.google.android.finsky.FinskyApp.onCreate(358): Initializing network with DFE https://android.clients.google.com/fdfe/
03-17 13:20:04.643  6659  6659 E RollingFileStream: Could not create a temp file with prefix: "eventlog.store" and suffix: ".log" in dir: "/data/data/com.android.vending/cache/logs/com.google.thalitester%40gmail.com".
03-17 13:20:04.653  6659  6659 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(122): No need to run daily hygiene.
03-17 13:20:04.668  6659  6659 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
03-17 13:20:04.669  6659  6659 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
03-17 13:20:04.673  6659  6705 E SQLiteDatabase: Failed to open database '/data/data/com.android.vending/databases/library.db'.
03-17 13:20:04.673  6659  6705 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 13:20:04.673  6659  6705 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 13:20:04.673  6659  6705 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-17 13:20:04.673  6659  6705 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-17 13:20:04.673  6659  6705 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-17 13:20:04.673  6659  6705 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-17 13:20:04.673  6659  6705 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-17 13:20:04.673  6659  6705 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-17 13:20:04.673  6659  6705 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-17 13:20:04.673  6659  6705 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-17 13:20:04.673  6659  6705 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
03-17 13:20:04.673  6659  6705 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-17 13:20:04.673  6659  6705 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 13:20:04.673  6659  6705 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 13:20:04.673  6659  6705 E SQLiteDatabase: 	at com.google.android.finsky.g.av.iterator(SourceFile:15308)
03-17 13:20:04.673  6659  6705 E SQLiteDatabase: 	at com.google.android.finsky.g.w.run(SourceFile:1078)
03-17 13:20:04.673  6659  6705 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-17 13:20:04.673  6659  6705 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-17 13:20:04.673  6659  6705 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
03-17 13:20:04.673  6659  6705 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-17 13:20:04.678  6659  6705 W Finsky.CrashDetector: Failed to write crash file cnt=0 ts=0 cause=null.
03-17 13:20:04.678  6659  6705 W Finsky.CrashDetector: java.io.FileNotFoundException: /data/data/com.android.vending/cache/crash806214: open failed: EROFS (Read-only file system)
03-17 13:20:04.678  6659  6705 W Finsky.CrashDetector: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-17 13:20:04.678  6659  6705 W Finsky.CrashDetector: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-17 13:20:04.678  6659  6705 W Finsky.CrashDetector: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-17 13:20:04.678  6659  6705 W Finsky.CrashDetector: 	at com.google.android.finsky.a.a(SourceFile:179)
03-17 13:20:04.678  6659  6705 W Finsky.CrashDetector: 	at com.google.android.finsky.a.uncaughtException(SourceFile:97)
03-17 13:20:04.678  6659  6705 W Finsky.CrashDetector: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
03-17 13:20:04.678  6659  6705 W Finsky.CrashDetector: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
03-17 13:20:04.678  6659  6705 W Finsky.CrashDetector: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-17 13:20:04.678  6659  6705 W Finsky.CrashDetector: 	at libcore.io.Posix.open(Native Method)
03-17 13:20:04.678  6659  6705 W Finsky.CrashDetector: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-17 13:20:04.678  6659  6705 W Finsky.CrashDetector: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-17 13:20:04.678  6659  6705 W Finsky.CrashDetector: 	... 6 more
03-17 13:20:04.683  6659  6706 E SQLiteDatabase: Failed to open database '/data/data/com.android.vending/databases/localappstate.db'.
03-17 13:20:04.683  6659  6706 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 13:20:04.683  6659  6706 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 13:20:04.683  6659  6706 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-17 13:20:04.683  6659  6706 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-17 13:20:04.683  6659  6706 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-17 13:20:04.683  6659  6706 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-17 13:20:04.683  6659  6706 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-17 13:20:04.683  6659  6706 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-17 13:20:04.683  6659  6706 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-17 13:20:04.683  6659  6706 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-17 13:20:04.683  6659  6706 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
03-17 13:20:04.683  6659  6706 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-17 13:20:04.683  6659  6706 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 13:20:04.683  6659  6706 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 13:20:04.683  6659  6706 E SQLiteDatabase: 	at com.google.android.finsky.b.x.a(SourceFile:2298)
03-17 13:20:04.683  6659  6706 E SQLiteDatabase: 	at com.google.android.finsky.b.z.c(SourceFile:55)
03-17 13:20:04.683  6659  6706 E SQLiteDatabase: 	at com.google.android.finsky.receivers.j.doInBackground(SourceFile:3083)
03-17 13:20:04.683  6659  6706 E SQLiteDatabase: 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
03-17 13:20:04.683  6659  6706 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 13:20:04.683  6659  6706 E SQLiteDatabase: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
03-17 13:20:04.683  6659  6706 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 13:20:04.683  6659  6706 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 13:20:04.683  6659  6706 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-17 13:20:04.683  6659  6706 I Process : Sending signal. PID: 6659 SIG: 9
03-17 13:20:04.692   279   700 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
