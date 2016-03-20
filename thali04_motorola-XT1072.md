#### Test 62548124ece3ba0_thali04_motorola-XT1072 Logs


```
--------- beginning of system
03-20 17:20:32.734  4621  4621 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
--------- beginning of main
03-20 17:20:32.783  4621  4621 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@2199a30f(com.android.providers.calendar.CalendarProvider2@ab32f9c)
,03-20 17:20:32.877   887  4532 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4649 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-20 17:20:32.905   321   321 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 341us total 27.064ms
03-20 17:20:32.933   321   321 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 27.060ms
03-20 17:20:32.944   887  4532 I ActivityManager: Killing 4023:com.motorola.context/u0a8 (adj 15): empty #7
03-20 17:20:32.954   321   321 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 319us total 20.863ms
03-20 17:20:32.969  1955  4214 I CheckinRequestBuilder: Checkin reason type: 8 attempt count: 1
03-20 17:20:33.020   887  1554 W libprocessgroup: failed to open /acct/uid_10008/pid_4023/cgroup.procs: No such file or directory
03-20 17:20:33.023  1955  4214 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
03-20 17:20:33.079  4230  4648 I Babel   : connection state changed from UNKNOWN to CONNECTED
03-20 17:20:33.142  1955  4214 I CheckinRequestBuilder: Classify the device as Phone.
03-20 17:20:33.157  1955  4214 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
03-20 17:20:33.163  1955  4214 I CheckinService: Checking schedule, now: 1458490833163 next: 1459091970157
03-20 17:20:33.163  1955  4214 I CheckinService: active receiver: disabled
03-20 17:20:33.215  1955  4682 I CheckinService: Checking schedule, now: 1458490833214 next: 1459091970157
03-20 17:20:33.215  1955  4682 I CheckinService: active receiver: disabled
03-20 17:20:33.217  1955  1955 D CheckinService: Recording last checkin time for package unspecified as 1458490833217
03-20 17:20:33.223   887  1599 I ActivityManager: Killing 3590:com.android.defcontainer/u0a10 (adj 15): empty #7
03-20 17:20:33.261  4655  4655 D AndroidRuntime: 
03-20 17:20:33.261  4655  4655 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-20 17:20:33.265  4655  4655 D AndroidRuntime: CheckJNI is OFF
03-20 17:20:33.344   887  1521 W libprocessgroup: failed to open /acct/uid_10010/pid_3590/cgroup.procs: No such file or directory
03-20 17:20:33.353   887  1805 I ActivityManager: Killing 4469:com.google.android.music:main/u0a80 (adj 15): empty #7
03-20 17:20:33.372   278   397 E Vold    : Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
03-20 17:20:33.372   278   397 W Vold    : Returning OperationFailed - no handler for errno 0
03-20 17:20:33.375  4649  4699 W ContextImpl: Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
03-20 17:20:33.381   278   397 E Vold    : Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
03-20 17:20:33.381   278   397 W Vold    : Returning OperationFailed - no handler for errno 0
03-20 17:20:33.382  4649  4699 W ContextImpl: Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
03-20 17:20:33.399   278   397 E Vold    : Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
03-20 17:20:33.399   278   397 W Vold    : Returning OperationFailed - no handler for errno 0
03-20 17:20:33.399  4649  4700 W ContextImpl: Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
03-20 17:20:33.404   278   397 E Vold    : Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
03-20 17:20:33.404   278   397 W Vold    : Returning OperationFailed - no handler for errno 0
03-20 17:20:33.404  4649  4700 W ContextImpl: Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
03-20 17:20:33.419   887  1227 V AlarmManager: send {24e56e8d, *alarm*:com.android.server.WifiManager.action.START_SCAN}
03-20 17:20:33.429  4649  4649 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
03-20 17:20:33.429  4649  4649 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-20 17:20:33.429  4649  4649 I GAv4    :   adb logcat -s GAv4
03-20 17:20:33.466   887  1227 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for service com.google.android.googlequicksearchbox/com.google.android.voicesearch.logger.EventLoggerService: pid=4702 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
03-20 17:20:33.466   887  1227 V AlarmManager: send {31e38617, *alarm*:send_events}
03-20 17:20:33.466   887  1521 W libprocessgroup: failed to open /acct/uid_10080/pid_4469/cgroup.procs: No such file or directory
03-20 17:20:33.466   887   887 V AlarmManager: done {31e38617, *alarm*:send_events} [105ms]
03-20 17:20:33.490  4649  4649 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
03-20 17:20:33.510  4655  4655 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-20 17:20:33.517   887  1248 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-20 17:20:33.529  4649  4649 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
03-20 17:20:33.530  3318  4620 I CalendarSyncAdapter: Found no pending settings
03-20 17:20:33.537  4649  4721 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
03-20 17:20:33.542   279   428 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (183 us)
03-20 17:20:33.565  1483  4162 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
03-20 17:20:33.582  4655  4655 D AndroidRuntime: Shutting down VM
03-20 17:20:33.632   887  1303 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4722 uid=10109 gids={50109, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-20 17:20:33.676  2813  2813 E ActivityThread: Performing stop of activity that is not resumed: {com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity}
03-20 17:20:33.676  2813  2813 E ActivityThread: java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity}
03-20 17:20:33.676  2813  2813 E ActivityThread: 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3396)
03-20 17:20:33.676  2813  2813 E ActivityThread: 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3477)
03-20 17:20:33.676  2813  2813 E ActivityThread: 	at android.app.ActivityThread.access$1100(ActivityThread.java:148)
03-20 17:20:33.676  2813  2813 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1321)
03-20 17:20:33.676  2813  2813 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-20 17:20:33.676  2813  2813 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
03-20 17:20:33.676  2813  2813 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5312)
03-20 17:20:33.676  2813  2813 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
03-20 17:20:33.676  2813  2813 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-20 17:20:33.676  2813  2813 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
03-20 17:20:33.676  2813  2813 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
03-20 17:20:33.706   887  1579 I ActivityManager: Activity reported stop, but no longer stopping: ActivityRecord{1cfdc12f u0 com.motorola.ccc.ota/.ui.DownloadActivity t8}
03-20 17:20:33.726  1955  3635 I CheckinService: Done disabling old GoogleServicesFramework version
03-20 17:20:33.730  1483  4162 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,03-20 17:20:33.798  4621  4621 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
03-20 17:20:33.798  4621  4621 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-20 17:20:33.822   887  1579 I ActivityManager: Killing 4524:com.android.mms/u0a23 (adj 15): empty #7
,03-20 17:20:33.874   887   902 W libprocessgroup: failed to open /acct/uid_10023/pid_4524/cgroup.procs: No such file or directory
,03-20 17:20:34.086  4722  4722 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-20 17:20:34.125  4722  4722 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 1338-1342)
03-20 17:20:34.125  4722  4722 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-20 17:20:34.187  4722  4722 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1ab6757a}
,03-20 17:20:34.199  4722  4722 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-20 17:20:34.209  4722  4722 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-20 17:20:34.236  4649  4649 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-20 17:20:34.249  4722  4722 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-20 17:20:34.253  4722  4722 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-20 17:20:34.257  4722  4722 E SysUtils: ApplicationContext is null in ApplicationStatus
03-20 17:20:34.259  4649  4649 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 1474-1475)
03-20 17:20:34.259  4649  4649 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-20 17:20:34.270  4649  4649 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {14bd8b2e}
,03-20 17:20:34.271  4649  4649 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-20 17:20:34.271  4649  4649 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-20 17:20:34.284  4649  4649 I BrowserStartupController: Initializing chromium process, singleProcess=true
03-20 17:20:34.285  4649  4649 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-20 17:20:34.287  4649  4649 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-20 17:20:34.362  4649  4649 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-20 17:20:34.372  4649  4649 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-20 17:20:34.372  4649  4649 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-20 17:20:34.373  4649  4649 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-20 17:20:34.373  4649  4649 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-20 17:20:34.373  4649  4649 I Adreno-EGL: Build Date: 10/28/14 Tue
03-20 17:20:34.373  4649  4649 I Adreno-EGL: Local Branch: 
03-20 17:20:34.373  4649  4649 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-20 17:20:34.373  4649  4649 I Adreno-EGL: Local Patches: NONE
03-20 17:20:34.373  4649  4649 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,03-20 17:20:34.379   887  1521 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=4780 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,03-20 17:20:34.552  4722  4722 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-20 17:20:34.559  4722  4722 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-20 17:20:34.559  4722  4722 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-20 17:20:34.561  4722  4722 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-20 17:20:34.561  4722  4722 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-20 17:20:34.561  4722  4722 I Adreno-EGL: Build Date: 10/28/14 Tue
03-20 17:20:34.561  4722  4722 I Adreno-EGL: Local Branch: 
03-20 17:20:34.561  4722  4722 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-20 17:20:34.561  4722  4722 I Adreno-EGL: Local Patches: NONE
03-20 17:20:34.561  4722  4722 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,03-20 17:20:34.573  4649  4810 W AudioManagerAndroid: Requires BLUETOOTH permission
,03-20 17:20:34.615  4649  4649 I NSApplication: Starting up...
,03-20 17:20:34.625  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-20 17:20:34.640   887  1135 D BluetoothManagerService: Message: 20
,03-20 17:20:34.641   887  1135 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3f02322c:true
,03-20 17:20:34.675   887  1248 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=4826 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-20 17:20:34.677   887  1248 I ActivityManager: Killing 4583:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,03-20 17:20:34.794   887  1248 I ActivityManager: Killing 4554:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,03-20 17:20:34.816   887  1925 W libprocessgroup: failed to open /acct/uid_10088/pid_4583/cgroup.procs: No such file or directory
,03-20 17:20:34.821   887   903 W libprocessgroup: failed to open /acct/uid_10035/pid_4554/cgroup.procs: No such file or directory
,03-20 17:20:34.824   887  1248 I ActivityManager: Killing 4230:com.google.android.talk/u0a70 (adj 15): empty #7
,03-20 17:20:34.891   887  1303 W libprocessgroup: failed to open /acct/uid_10070/pid_4230/cgroup.procs: No such file or directory
03-20 17:20:34.891  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-20 17:20:34.891  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-20 17:20:35.055  2697  2783 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-20 17:20:35.064   887  1223 D BatteryService: uevent={POWER_SUPPLY_TEMP=337, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2362000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311250, SEQNUM=4400, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5408, POWER_SUPPLY_CHARGE_COUNTER=-72, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,03-20 17:20:35.080  4722  4722 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-20 17:20:35.095  4722  4722 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-20 17:20:35.113  4722  4722 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
03-20 17:20:35.113  2697  2783 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-20 17:20:35.123  4722  4722 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-20 17:20:35.123  4722  4722 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-20 17:20:35.339   887  1566 I art     : Explicit concurrent mark sweep GC freed 22089(1062KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/31MB, paused 2.235ms total 138.229ms
,03-20 17:20:35.345  4722  4859 D OpenGLRenderer: Render dirty regions requested: true
,03-20 17:20:35.353  2813  2813 D EmailService.MarketingOptInSetter: received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,03-20 17:20:35.364  2813  2889 I SundryService: onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
03-20 17:20:35.365  2813  2889 E SQLiteLog: (284) automatic index on registration(APP_ID)
03-20 17:20:35.366  2813  2889 D WaitableIntentService: ServiceHandler.handleMessage: mWaitCount=1
,03-20 17:20:35.369  4722  4722 D Atlas   : Validating map...
,03-20 17:20:35.375  2813  4860 I PushService: started with background data enabled, making sure notification mechanism is enabled
,03-20 17:20:35.412   887  1467 I ActivityManager: Start proc com.motorola.context for broadcast com.motorola.context/.receiver.DateChangeBroadcastReceiver: pid=4862 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,03-20 17:20:35.413  4722  4822 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-20 17:20:35.418   887  1521 I ActivityManager: Killing 4649:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,03-20 17:20:35.478   887  1554 W libprocessgroup: failed to open /acct/uid_10081/pid_4649/cgroup.procs: No such file or directory
,03-20 17:20:35.493  4862  4862 W ResourcesManager: Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,03-20 17:20:35.519  4722  4859 I OpenGLRenderer: Initialized EGL, version 1.4
,03-20 17:20:35.525  4722  4859 D OpenGLRenderer: Enabling debug mode 0
,03-20 17:20:35.584   887   903 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4883 uid=10096 gids={50096, 9997} abi=armeabi-v7a
,03-20 17:20:35.607   887  1248 I ActivityManager: Killing 4702:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,03-20 17:20:35.623  1423  1423 I Keyboard.Facilitator: onFinishInput()
,03-20 17:20:35.626  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
03-20 17:20:35.641  4722  4890 E Adreno-ES20: <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
03-20 17:20:35.641  4722  4890 E Adreno-ES20: <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,03-20 17:20:35.663   887   902 W libprocessgroup: failed to open /acct/uid_10039/pid_4702/cgroup.procs: No such file or directory
,03-20 17:20:35.670   887  1136 I LaunchCheckinHandler: Displayed com.test.thalitest/.MainActivity,cp,ca,2086
03-20 17:20:35.670   887  1136 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +2s86ms
,03-20 17:20:35.680  4722  4722 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 4722
,03-20 17:20:35.710  4883  4883 I System.out: TimeService: Loaded Library 
,03-20 17:20:35.715  4883  4883 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1458490835715
03-20 17:20:35.716  4883  4883 D         : TimeServiceNative: User Time to be set is 1458490835715
03-20 17:20:35.716  4883  4883 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
03-20 17:20:35.716  4883  4883 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
03-20 17:20:35.716  4883  4883 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1458490835715
03-20 17:20:35.716  4883  4883 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
,03-20 17:20:35.724   332   832 D QC-time-services: Daemon: Connection accepted:time_genoff
,03-20 17:20:35.725   332  4905 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1458490835715
03-20 17:20:35.725   332  4905 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1458490835715, operation = 0
03-20 17:20:35.725   332  4905 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS2/20/116 16:18:44
03-20 17:20:35.725   332  4905 D QC-time-services: Daemon:Value read from RTC seconds = 1458490724000
03-20 17:20:35.725   332  4905 D QC-time-services: Daemon:new time 1458490835715 
03-20 17:20:35.725   332  4905 D QC-time-services: Daemon: delta 111715 genoff 111715 
03-20 17:20:35.725   332  4905 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 111715 to memory
03-20 17:20:35.725   332  4905 D QC-time-services: Daemon:Opening File: /data/time/ats_2
03-20 17:20:35.725   332  4905 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-20 17:20:35.775   332  4905 D QC-time-services: Updating the TOD offset
03-20 17:20:35.775   332  4905 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 111715 to memory
03-20 17:20:35.775   332  4905 D QC-time-services: Daemon:Opening File: /data/time/ats_1
03-20 17:20:35.775   332  4905 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-20 17:20:35.782   332  4905 E QC-time-services: Daemon:Update to modem bit set
,03-20 17:20:35.782   332  4905 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
03-20 17:20:35.782   332  4905 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 18446743757744863331
,03-20 17:20:35.784  4883  4883 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,03-20 17:20:35.786   887  1508 I ActivityManager: Killing 4621:com.android.providers.calendar/u0a5 (adj 15): empty #7
,03-20 17:20:35.787   332   830 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,03-20 17:20:35.788   332   832 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,03-20 17:20:35.846   887  1554 W libprocessgroup: failed to open /acct/uid_10005/pid_4621/cgroup.procs: No such file or directory
,03-20 17:20:35.906  4722  4722 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-20 17:20:35.944   279   731 I SFPerfTracer:      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (13:195 vsyncs) (15:921)
,03-20 17:20:36.312   887  4532 I ActivityManager: Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=4913 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,03-20 17:20:36.338  4722  4859 E Adreno-ES20: <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
03-20 17:20:36.338  4722  4859 E Adreno-ES20: <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,03-20 17:20:36.375  4722  4882 D jxcore_app_log: JniHelper::setJavaVM(0xb8f28310), pthread_self() = -1188302520
,03-20 17:20:36.384  4722  4882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-20 17:20:36.384  4722  4882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-20 17:20:36.384  4722  4882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-20 17:20:36.384  4722  4882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-20 17:20:36.384  4722  4882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-20 17:20:36.384  4722  4882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64f08a6 added. We now have 1 listener(s)
,03-20 17:20:36.385   887  1599 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,03-20 17:20:36.388  4722  4882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:80:EB:7B:5A:05
,03-20 17:20:36.393  4722  4882 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:80:EB:7B:5A:05"
,03-20 17:20:36.395  4722  4882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
03-20 17:20:36.395  4722  4882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-20 17:20:36.400  4722  4882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-20 17:20:36.400  4722  4882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-20 17:20:36.400  4722  4882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-20 17:20:36.400  4722  4882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 44:80:EB:7B:5A:05
03-20 17:20:36.400  4722  4882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-20 17:20:36.400  4722  4882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-20 17:20:36.400  4722  4882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-20 17:20:36.400  4722  4882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-20 17:20:36.400  4722  4882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-20 17:20:36.400  4722  4882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-20 17:20:36.400  4722  4882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-20 17:20:36.400  4722  4882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@204d2d3d added. We now have 1 listener(s)
,03-20 17:20:36.400  4722  4882 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-20 17:20:36.414   887  1241 D WifiService: New client listening to asynchronous messages
,03-20 17:20:36.416  4722  4882 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,03-20 17:20:36.419  4722  4882 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
03-20 17:20:36.419  4722  4882 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,03-20 17:20:36.421  4722  4882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-20 17:20:36.421   887  1554 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,03-20 17:20:36.422  4722  4882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:80:EB:7B:5A:05
,03-20 17:20:36.428  4722  4882 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-20 17:20:36.428  4722  4882 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-20 17:20:36.428  4722  4882 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-20 17:20:36.428  4722  4882 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-20 17:20:36.428  4722  4882 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-20 17:20:36.428  4722  4882 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-20 17:20:36.428  4722  4882 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-20 17:20:36.428  4722  4882 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-20 17:20:36.428  4722  4882 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-20 17:20:36.428  4722  4882 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-20 17:20:36.429  4722  4882 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-20 17:20:36.463  4913  4913 I GAv4    : Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
03-20 17:20:36.463  4913  4913 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-20 17:20:36.463  4913  4913 I GAv4    :   adb logcat -s GAv4
,03-20 17:20:36.488  4913  4913 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-20 17:20:36.509  4913  4913 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-20 17:20:36.519  4913  4936 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-20 17:20:36.585   887  4532 I ActivityManager: Killing 4780:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,03-20 17:20:36.615   887  1925 W libprocessgroup: failed to open /acct/uid_10019/pid_4780/cgroup.procs: No such file or directory
,03-20 17:20:36.629  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-20 17:20:36.632  2813  2813 D OtaApp  : [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,03-20 17:20:36.636  2813  2813 D OtaApp  : [debug] > UpdateReceiver: Received true from doSanityCheck.
,03-20 17:20:36.637  2813  2813 D OtaApp  : [debug] > In cancelAnyPendingIntentSetPreviously
,03-20 17:20:36.641   887  4532 I ActivityManager: START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,03-20 17:20:36.656  1483  4162 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,03-20 17:20:36.679  4722  4722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
03-20 17:20:36.680   279   279 I SFPerfTracer:      triggers: (rate: 12:548) (compose: 0:1) (post: 0:1) (render: 0:2) (25:857 frames) (26:944)
03-20 17:20:36.680   279   279 D SFPerfTracer:        layers: (3:13) (FocusedStackFrame (0xb8483d28): 0:15)* (DimLayer (0xb8534050): 0:6)* (com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (0xb84da3a0): 0:32)- (StatusBar (0xb84df038): 0:119) (NavigationBar (0xb853ae48): 0:35) (com.android.systemui.ImageWallpaper (0xb853f850): 0:6)* (Starting com.motorola.ccc.ota (0xb85186e8): 0:34)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb84d1010): 0:54)- (Starting com.test.thalitest (0xb85186e8): 0:41)- (com.test.thalitest/com.test.thalitest.MainActivity (0xb84dad30): 26:42) 
03-20 17:20:36.682  4722  4722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-20 17:20:36.688  4722  4722 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
03-20 17:20:36.688  4722  4722 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,03-20 17:20:36.689  4722  4722 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,03-20 17:20:36.704   887  1248 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=4939 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-20 17:20:36.735  1483  4162 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,03-20 17:20:36.742   887  1579 I ActivityManager: Killing 4826:com.android.chrome/u0a52 (adj 15): empty #7
,03-20 17:20:36.871  2813  2813 D OtaApp  : [debug] > DownloadActivity, FormattedText
,03-20 17:20:36.873   887  1248 W libprocessgroup: failed to open /acct/uid_10052/pid_4826/cgroup.procs: No such file or directory
,03-20 17:20:36.879  2813  2813 I OtaApp  : [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,03-20 17:20:36.879  2813  2813 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-20 17:20:36.884  2813  2813 I OtaApp  : [info] > Exceed max defer attempts for optional update, suppresing later btn
,03-20 17:20:36.885  2813  2813 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-20 17:20:36.889  2813  2813 D OtaApp  : [debug] > cancelling the previous pending intent set for download later
,03-20 17:20:36.890  2813  2813 I OtaApp  : [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,03-20 17:20:36.891  2813  2813 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-20 17:20:36.900  2813  2813 D OtaApp  : [debug] > DownloadActivity, FormattedText
,03-20 17:20:36.902  2813  2813 I OtaApp  : [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,03-20 17:20:36.906  2813  2813 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-20 17:20:36.909  2813  2813 I OtaApp  : [info] > Exceed max defer attempts for optional update, suppresing later btn
,03-20 17:20:36.910  2813  2813 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-20 17:20:36.914  2813  2813 D OtaApp  : [debug] > cancelling the previous pending intent set for download later
,03-20 17:20:36.919  2813  2813 I OtaApp  : [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
03-20 17:20:36.920  2813  2813 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-20 17:20:36.957  1423  1423 I Keyboard.Facilitator: onFinishInput()
,03-20 17:20:36.964  4722  4722 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-20 17:20:36.990   887  1136 I LaunchCheckinHandler: Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,349
,03-20 17:20:37.088  4939  4960 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,03-20 17:20:37.122  4939  4959 I Gmail   : getAccountsCursor
,03-20 17:20:37.141  2032  2032 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-20 17:20:37.223   887  1925 I ActivityManager: Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=4962 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-20 17:20:37.371  4939  4939 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-20 17:20:37.396   887  1579 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,03-20 17:20:37.403  4962  4962 I Exchange: EasService.onCreate
,03-20 17:20:37.420  4962  4985 I Exchange: RestartPingTask
,03-20 17:20:37.429  4939  4983 I Gmail   : Observing account changes for notifications
,03-20 17:20:37.438  4962  4962 I Exchange: RestartPingsTask did not start any pings.
03-20 17:20:37.438  4962  4962 I Exchange: PSS stopIfIdle
03-20 17:20:37.438  4962  4962 I Exchange: PSS has no active accounts; stopping service.
,03-20 17:20:37.462  4962  4962 I Exchange: onDestroy
,03-20 17:20:37.464   887  1508 I ActivityManager: Killing 4397:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,03-20 17:20:37.629  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-20 17:20:37.676  4722  4933 W jxcore-log: Initializing JXcore engine
03-20 17:20:37.676  4722  4933 W jxcore-log: JXcore engine is ready
,03-20 17:20:37.733   887  1106 I ActivityManager: Waited long enough for: ServiceRecord{33b55cf2 u0 com.motorola.ccc.checkin/.CheckinService}
,03-20 17:20:37.735   887  1566 W libprocessgroup: failed to open /acct/uid_10090/pid_4397/cgroup.procs: No such file or directory
,03-20 17:20:37.747  4939  4989 I Gmail   : getAccountsCursor
,03-20 17:20:37.755  4722  4722 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2afa21a0 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@31291f01, 16908290=android.view.AbsSavedState$1@31291f01}, android:focusedViewId=100}]}]
03-20 17:20:37.755  4722  4722 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
03-20 17:20:37.755  4722  4722 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
03-20 17:20:37.755  4722  4722 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,03-20 17:20:37.765  2032  2032 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-20 17:20:37.801  2032  2032 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-20 17:20:37.793  4933  4933 W Thread-476: type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10109 path="socket:[9375]" dev="sockfs" ino=9375 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-20 17:20:37.793  4933  4933 W Thread-476: type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10109 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,03-20 17:20:37.806  4862  4998 I CE-UpdateModelService: ACTION_REGISTRATION_COMPLETE
03-20 17:20:37.793  4933  4933 W Thread-476: type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10109 path="socket:[9476]" dev="sockfs" ino=9476 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,03-20 17:20:37.793  4933  4933 W Thread-476: type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10109 path="socket:[21524]" dev="sockfs" ino=21524 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,03-20 17:20:37.808   887  1579 I ActivityManager: Killing 4883:com.qualcomm.timeservice/u0a96 (adj 15): empty #7
,03-20 17:20:37.825  4722  4933 W jxcore-log: Starting JXcore engine
,03-20 17:20:37.830  4939  4999 E SQLiteLog: (283) recovered 58 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,03-20 17:20:37.886  4939  5000 I Gmail   : notifyAccountChanged
,03-20 17:20:37.888  4939  4990 I Gmail   : getAccountsCursor
,03-20 17:20:37.891  4939  5000 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-20 17:20:37.895  4939  5000 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-20 17:20:37.904  4939  5000 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-20 17:20:37.905  4939  5000 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-20 17:20:37.937   887  1554 W libprocessgroup: failed to open /acct/uid_10096/pid_4883/cgroup.procs: No such file or directory
,03-20 17:20:37.939  2032  2032 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-20 17:20:37.940  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-20 17:20:37.940  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-20 17:20:37.943  2813  2813 D 3CDM.DeviceAdminPushReceiver: Received an Intent - Action: com.motorola.cce.Actions.CCE_SEND_SETTINGS_RESPONSE
03-20 17:20:37.944  2813  2813 D 3CDM.DeviceAdminPushReceiver: Type: null
03-20 17:20:37.944  2813  2813 D 3CDM.DeviceAdminPushReceiver: Data: null
,03-20 17:20:37.946  2813  2887 D 3CDM.Service: com.motorola.cce.Actions.CCE_SEND_SETTINGS_RESPONSE
,03-20 17:20:37.946  2813  2887 D 3CDM.Service: Received settings reponse intent with responsecode code: com.motorola.cce.sharedsettings.errorOk
,03-20 17:20:37.946  2813  2887 D 3CDM.Service: DeviceAdmin - syncWithCCC
03-20 17:20:37.946  2813  2887 D 3CDM.Service: blur.service.littlesister.gpsFixWaitTime = 60000
03-20 17:20:37.946  2813  2887 D 3CDM.Service: com.motorola.ccc.devicemanagement.capabilities = LOST,LOCK,RING,LOCATE,PING,MULTIPLE-LOCATE,WIPE,SYNC,CALL-FORWARDING,STOP-RING
03-20 17:20:37.946  2813  2887 D 3CDM.Service: blur.service.cred.locationToken = null
03-20 17:20:37.946  2813  2887 D 3CDM.Service: com.motorola.ccc.cce.email.marketing.optin.default = false
03-20 17:20:37.946  2813  2887 D 3CDM.Service: blur.service.littlesister.reportLevel2 = NONE
03-20 17:20:37.946  2813  2887 D 3CDM.Service: com.motorola.blur.adminfeed.device_admin_always_allowed = 1
03-20 17:20:37.946  2813  2887 D 3CDM.Service: com.motorola.ccc.devicemanagement.motocare.url = www.motorola.com/support
,03-20 17:20:37.950  2813  2887 D 3CDM.Service: Sync to CCE settings done, instantiate Locate now.
,03-20 17:20:37.968  1955  5003 D LocationInitializer: Restart initialization of location
,03-20 17:20:37.972  2032  2032 D WearableService: callingUid 10016, callindPid: 2032
,03-20 17:20:37.978  2032  2032 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-20 17:20:37.986  2032  2032 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-20 17:20:37.987  2032  5002 E MDM     : [231] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-20 17:20:37.994  2813  2889 I SundryService: onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
03-20 17:20:37.994  2813  2889 D WaitableIntentService: setWaitEnabled(): mWaitCount=0 isWaitEnabled=false
03-20 17:20:37.994  2813  2889 D SundryService: onHandleIntent(): isWaitEnabled=false
03-20 17:20:37.994  2813  2889 D WaitableIntentService: ServiceHandler.handleMessage: mWaitCount=0
,03-20 17:20:37.997  2813  2813 D GetNotificationsWS: unbindWebServices(): un-registering our AIDL callback...
,03-20 17:20:38.004  2032  2235 W GCoreFlp: No location to return for getLastLocation()
03-20 17:20:38.004  2032  5004 W FusedLocationProvider: location=null
,03-20 17:20:38.016  4722  4933 W jxcore-log: Platform android
03-20 17:20:38.016  4722  4933 W jxcore-log: 
,03-20 17:20:38.016  4722  4933 W jxcore-log: Process ARCH arm
03-20 17:20:38.016  4722  4933 W jxcore-log: 
,03-20 17:20:38.047   887   902 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=5007 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,03-20 17:20:38.079   887  1805 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5013 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-20 17:20:38.100   321   321 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 20.303ms
,03-20 17:20:38.122   321   321 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 263us total 21.254ms
,03-20 17:20:38.143   321   321 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 20.218ms
,03-20 17:20:38.245  3242  3274 D Checkin : publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,03-20 17:20:38.246  2813  2887 D BSUtils : set .setup.DeviceAdminSetupReceiver enabled
,03-20 17:20:38.283  5013  5013 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-20 17:20:38.318  4939  4959 I Gmail   : getAccountsCursor
,03-20 17:20:38.322  2032  2032 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-20 17:20:38.330  5013  5013 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@2199a30f(com.android.providers.calendar.CalendarProvider2@ab32f9c)
,03-20 17:20:38.357  4722  4933 I jxcore-log: JXcore Cordova bridge is ready!
03-20 17:20:38.357  4722  4933 I jxcore-log: 
03-20 17:20:38.358  4722  4933 W jxcore-log: JXcore engine is started
,03-20 17:20:38.366  4722  4882 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-20 17:20:38.368  4722  4722 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-20 17:20:38.379  4722  4933 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-20 17:20:38.379  4722  4933 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-20 17:20:38.385  4722  4722 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
03-20 17:20:38.385  4722  4722 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,03-20 17:20:38.389   887  1508 I ActivityManager: Killing 4913:com.google.android.deskclock/u0a55 (adj 15): empty #7
,03-20 17:20:38.489   887  1248 I art     : Explicit concurrent mark sweep GC freed 12633(667KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 21MB/31MB, paused 1.661ms total 118.946ms
,03-20 17:20:38.524   887  1106 I ActivityManager: Waited long enough for: ServiceRecord{2bf15a58 u0 com.google.android.calendar/com.android.calendar.alerts.AlertService}
,03-20 17:20:38.524  4722  4882 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 139ms. Plugin should use CordovaInterface.getThreadPool().
,03-20 17:20:38.525   887  1579 W libprocessgroup: failed to open /acct/uid_10055/pid_4913/cgroup.procs: No such file or directory
,03-20 17:20:38.526  4722  4722 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
03-20 17:20:38.526  4722  4722 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
03-20 17:20:38.526  4722  4722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
03-20 17:20:38.526  4722  4722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-20 17:20:38.526  4722  4722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-20 17:20:38.526  4722  4722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
03-20 17:20:38.526  4722  4722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64f08a6 removed from the list
03-20 17:20:38.526  4722  4722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
03-20 17:20:38.526  4722  4722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@204d2d3d removed from the list
03-20 17:20:38.526  4722  4722 D io.jxcore.node.ConnectivityMonitor: stop
03-20 17:20:38.526  4722  4722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,03-20 17:20:38.528  4722  4722 I io.jxcore.node.LifeCycleMonitor: stop: OK
,03-20 17:20:38.631  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-20 17:20:38.703  5046  5046 D AndroidRuntime: 
03-20 17:20:38.703  5046  5046 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-20 17:20:38.707  5046  5046 D AndroidRuntime: CheckJNI is OFF
,03-20 17:20:38.798   887  1923 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5064 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,03-20 17:20:38.846   887  1579 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=5083 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,03-20 17:20:38.849   887  1579 I ActivityManager: Killing 4376:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,03-20 17:20:38.866  5046  5046 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-20 17:20:38.887   887  1106 I ActivityManager: Force stopping com.test.thalitest appid=10109 user=-1: uninstall pkg
03-20 17:20:38.887   887  1106 I ActivityManager: Killing 4722:com.test.thalitest/u0a109 (adj 9): stop com.test.thalitest
,03-20 17:20:38.922   887  1241 D WifiService: Client connection lost with reason: 4
,03-20 17:20:38.947   887  1151 W PackageSettings: Skipping PackageSetting{3f10defd com.example.hello/10568} due to missing metadata
,03-20 17:20:38.995   887  1467 W libprocessgroup: failed to open /acct/uid_10016/pid_4376/cgroup.procs: No such file or directory
,03-20 17:20:39.007   887  1599 W ActivityManager: Spurious death for ProcessRecord{1e4fb68 4722:com.test.thalitest/u0a109}, curProc for 4722: null
,03-20 17:20:39.008   887  1151 I ActivityManager: Force stopping com.test.thalitest appid=10109 user=0: pkg removed
,03-20 17:20:39.051  5083  5083 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-20 17:20:39.054   887  1230 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-20 17:20:39.066  3242  3242 I art     : Explicit concurrent mark sweep GC freed 9763(1620KB) AllocSpace objects, 4(64KB) LOS objects, 39% free, 7MB/12MB, paused 770us total 51.879ms
,03-20 17:20:39.069  2032  2362 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-20 17:20:39.072  1423  1423 I Keyboard.Facilitator: resetDictionaries() : en_US
,03-20 17:20:39.089  1423  5107 I Keyboard.Facilitator.DecoderInitializer: run()
,03-20 17:20:39.093  1423  5107 I Decoder : createOrResetDecoder
,03-20 17:20:39.112  1575  1575 I art     : Explicit concurrent mark sweep GC freed 2090(111KB) AllocSpace objects, 2(72KB) LOS objects, 25% free, 13MB/17MB, paused 3.106ms total 82.436ms
,03-20 17:20:39.176  1423  5107 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,03-20 17:20:39.204   887   887 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
03-20 17:20:39.205   887   887 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,03-20 17:20:39.211   887  1259 D TaskPersister: removeObsoleteFile: deleting file=9_task.xml
03-20 17:20:39.211   887  1259 D TaskPersister: removeObsoleteFile: deleting file=8_task.xml
03-20 17:20:39.211   887  1259 D TaskPersister: removeObsoleteFile: deleting file=8_task_thumbnail.png
03-20 17:20:39.212   887  1259 D TaskPersister: removeObsoleteFile: deleting file=9_task_thumbnail.png
,03-20 17:20:39.225  1423  5107 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,03-20 17:20:39.230  1423  5107 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
03-20 17:20:39.230  1423  5107 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,03-20 17:20:39.236  1423  5107 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
03-20 17:20:39.236  1423  5107 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,03-20 17:20:39.243  1423  5107 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
03-20 17:20:39.243  1423  5107 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
03-20 17:20:39.248  1423  5107 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
03-20 17:20:39.248  1423  5107 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
03-20 17:20:39.248  1423  5107 I Keyboard.Facilitator.Delight2FileSweeper: run()
03-20 17:20:39.248  1423  5107 I Keyboard.Facilitator.RecurringTaskScheduler: run()
03-20 17:20:39.248  1423  5107 I StatsUtilsManager: startPeriodStatsRecorder() : Success
03-20 17:20:39.248  1423  5107 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,03-20 17:20:39.268  1575  1575 I Launcher: Deferring update until onResume
,03-20 17:20:39.278   315   385 I ThermalEngine: Sensor:xo_therm_pu2:38000 mC
,03-20 17:20:39.303  5083  5119 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
03-20 17:20:39.303  5083  5119 I Babel_SMS: MmsConfig.loadMmsSettings
,03-20 17:20:39.304  5083  5119 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
03-20 17:20:39.304  5083  5119 I Babel_SMS: MmsConfig.loadFromDatabase
,03-20 17:20:39.323  5083  5119 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
03-20 17:20:39.323  5083  5119 I Babel_SMS: MmsConfig.loadFromResources
,03-20 17:20:39.325  5083  5119 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,03-20 17:20:39.326  5083  5119 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,03-20 17:20:39.327   887  1151 I art     : Explicit concurrent mark sweep GC freed 18947(1465KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 21MB/32MB, paused 2.645ms total 242.976ms
,03-20 17:20:39.341  5013  5013 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
03-20 17:20:39.341  5013  5013 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-20 17:20:39.400  5046  5046 D AndroidRuntime: Shutting down VM
,03-20 17:20:39.448   887  1151 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=5122 uid=10010 gids={50010, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,03-20 17:20:39.494  5083  5083 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,03-20 17:20:39.498  5083  5083 I Babel_Crash: startup - clean
,03-20 17:20:39.509  5083  5136 I Babel   : deleted: false for 0
,03-20 17:20:39.540   887  1521 I ActivityManager: Killing 4962:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,03-20 17:20:39.693   887  1508 W libprocessgroup: failed to open /acct/uid_10060/pid_4962/cgroup.procs: No such file or directory
,03-20 17:20:39.699   887  1579 I ActivityManager: Killing 4939:com.google.android.gm/u0a63 (adj 15): empty #7
,03-20 17:20:39.784   887  1248 W libprocessgroup: failed to open /acct/uid_10063/pid_4939/cgroup.procs: No such file or directory
,03-20 17:20:39.811  5083  5083 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-20 17:20:39.820  5083  5083 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,03-20 17:20:39.824  5083  5083 W VideoCapabilities: Unsupported mime video/mpeg2
,03-20 17:20:39.834   887  1923 I ActivityManager: Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5146 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,03-20 17:20:39.884  5083  5083 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,03-20 17:20:39.893  5083  5083 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
03-20 17:20:39.896  5083  5083 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
03-20 17:20:39.900  5083  5083 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-20 17:20:39.904  5146  5146 W asset   : Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
,03-20 17:20:39.904  5146  5146 W ResourcesManager: Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
,03-20 17:20:39.904  5146  5146 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-20 17:20:39.906  5146  5146 W ResourcesManager: Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,03-20 17:20:39.910  5083  5083 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-20 17:20:40.281   279   695 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
