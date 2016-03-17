#### Test 62509094b685d58_thali04_motorola-XT1072 Logs


```
--------- beginning of system
03-17 12:29:08.142  4716  4767 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-17 12:29:08.161   881  1503 W libprocessgroup: failed to open /acct/uid_10060/pid_4538/cgroup.procs: No such file or directory
03-17 12:29:08.202   881  1588 D WifiService: releaseWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@1ac27eda}
03-17 12:29:08.225   881  1516 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=4778 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,03-17 12:29:08.245   881  1595 I ActivityManager: Killing 4512:com.google.android.gm/u0a63 (adj 15): empty #7
--------- beginning of main
03-17 12:29:08.258  2666  4296 W Settings: Setting dropbox_quota_kb has moved from android.provider.Settings.System to android.provider.Settings.Global
03-17 12:29:08.259   881  1218 D BatteryService: uevent={POWER_SUPPLY_TEMP=340, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2362000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311428, SEQNUM=4358, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-11919, POWER_SUPPLY_CHARGE_COUNTER=-86, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
03-17 12:29:08.260  2666  4296 W Settings: Setting dropbox_quota_kb has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
03-17 12:29:08.260  2666  4296 W Settings: Setting dropbox_max_files has moved from android.provider.Settings.System to android.provider.Settings.Global
03-17 12:29:08.261  2666  4296 W Settings: Setting dropbox_max_files has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
03-17 12:29:08.262  2666  4296 I global frequency: BcsTimer.setTimer(86400000, 86400000)
03-17 12:29:08.263  2666  4296 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
03-17 12:29:08.265  1462  4624 D Central_PollingManager: registerApp(): Checkin
03-17 12:29:08.265  1462  4624 D Central_PollingManager: registerApp(): Checkin already registered.
03-17 12:29:08.265  1462  3147 D Central_PollingManager: modifyApp(): Checkin
03-17 12:29:08.271  1462  3147 D Central_PollingManager: calculateShortestInterval(): shortest interval is 21600000
03-17 12:29:08.276  2666  4296 W MotorolaSettings: no such table to get this name = privacy_droid_blast
03-17 12:29:08.276  2666  4296 W System.err: java.lang.Exception
03-17 12:29:08.277  2666  4296 W System.err: 	at com.motorola.android.provider.MotorolaSettings.getString(MotorolaSettings.java:290)
03-17 12:29:08.277  2666  4296 W System.err: 	at com.motorola.android.provider.MotorolaSettings.getInt(MotorolaSettings.java:328)
03-17 12:29:08.277  2666  4296 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 12:29:08.277  2666  4296 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 12:29:08.277  2666  4296 W System.err: 	at com.motorola.ccc.checkin.MotorolaSettings.getInt(MotorolaSettings.java:106)
03-17 12:29:08.277  2666  4296 W System.err: 	at com.motorola.ccc.checkin.PrivacyHelper.readPrivacy(PrivacyHelper.java:413)
03-17 12:29:08.277  2666  4296 W System.err: 	at com.motorola.ccc.checkin.PrivacyHelper.reconfigurePrivacy(PrivacyHelper.java:160)
03-17 12:29:08.277  2666  4296 W System.err: 	at com.motorola.ccc.checkin.BcsConfigAndroid.handleConfigChange(BcsConfigAndroid.java:996)
03-17 12:29:08.277  2666  4296 W System.err: 	at com.motorola.ccc.checkin.BcsConfigAndroid.update(BcsConfigAndroid.java:518)
03-17 12:29:08.277  2666  4296 W System.err: 	at com.motorola.ccc.checkin.BcsCore.doConfig(BcsCore.java:662)
03-17 12:29:08.277  2666  4296 W System.err: 	at com.motorola.ccc.checkin.BcsCore.handleEvent(BcsCore.java:332)
03-17 12:29:08.277  2666  4296 W System.err: 	at com.motorola.ccc.checkin.BcsPlatformAndroid.handleCceSendSettingsResponse(BcsPlatformAndroid.java:432)
03-17 12:29:08.277  2666  4296 W System.err: 	at com.motorola.ccc.checkin.BcsPlatformAndroid.onReceiveActions(BcsPlatformAndroid.java:403)
03-17 12:29:08.277  2666  4296 W System.err: 	at com.motorola.ccc.checkin.BcsPlatformAndroid.access$000(BcsPlatformAndroid.java:87)
03-17 12:29:08.277  2666  4296 W System.err: 	at com.motorola.ccc.checkin.BcsPlatformAndroid$1.run(BcsPlatformAndroid.java:295)
03-17 12:29:08.277  2666  4296 W System.err: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-17 12:29:08.277  2666  4296 W System.err: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 12:29:08.277  2666  4296 W System.err: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 12:29:08.277  2666  4296 W System.err: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 12:29:08.277  2666  4296 W System.err: 	at java.lang.Thread.run(Thread.java:818)
03-17 12:29:08.281  2666  4296 I global frequency: BcsConfigAndroid:updateAllowedEventTagsForPrivacyProfile Blacklisted tags: (DUMMY_TAG:1416552400)
03-17 12:29:08.282  2666  4296 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
03-17 12:29:08.283  2666  4296 I global frequency: BcsConfigAndroid:updateAllowedEventTagsForPrivacyProfile new whitelisted checkin event tags: MOT_OTA:LOG,MOT_PRIVACY_PROFILE,DEV_ATTRIBS,CHECKIN_SUCCESS,MOT_CCE_STATS:CS_Notif_FFA,DEVICE_PROPERTIES,CHECKIN_FAILURE
03-17 12:29:08.284  2666  4296 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
03-17 12:29:08.286  2666  4296 D Checkin : publish the event [tag = MOT_PRIVACY_PROFILE event name = PRIVACY]
03-17 12:29:08.328   881  1517 W libprocessgroup: failed to open /acct/uid_10063/pid_4512/cgroup.procs: No such file or directory
03-17 12:29:08.334  2567  2630 D HeadsetStateMachine: Disconnected process message: 10, size: 0
03-17 12:29:08.397  4778  4778 D PhoneMonitor: Register our PhoneStateListener
03-17 12:29:08.410  4778  4778 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
03-17 12:29:08.411  4778  4778 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
03-17 12:29:08.413   881  1516 I ActivityManager: Killing 4579:com.motorola.context/u0a8 (adj 15): empty #7
03-17 12:29:08.418  1552  1569 I art     : Explicit concurrent mark sweep GC freed 25034(1656KB) AllocSpace objects, 6(96KB) LOS objects, 39% free, 8MB/13MB, paused 1.319ms total 69.278ms
03-17 12:29:08.491   881   897 W libprocessgroup: failed to open /acct/uid_10008/pid_4579/cgroup.procs: No such file or directory
03-17 12:29:08.494   881  1503 I ActivityManager: Killing 4618:com.android.providers.calendar/u0a5 (adj 15): empty #7
03-17 12:29:08.563  2666  4296 W Settings: Setting dropbox_quota_kb has moved from android.provider.Settings.System to android.provider.Settings.Global
03-17 12:29:08.564  2666  4296 W Settings: Setting dropbox_quota_kb has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
03-17 12:29:08.564  2666  4296 W Settings: Setting dropbox_max_files has moved from android.provider.Settings.System to android.provider.Settings.Global
03-17 12:29:08.565  2666  4296 W Settings: Setting dropbox_max_files has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
03-17 12:29:08.570  2666  4296 W MotorolaSettings: no such table to get this name = privacy_droid_blast
03-17 12:29:08.570  2666  4296 W System.err: java.lang.Exception
03-17 12:29:08.571  2666  4296 W System.err: 	at com.motorola.android.provider.MotorolaSettings.getString(MotorolaSettings.java:290)
03-17 12:29:08.571  2666  4296 W System.err: 	at com.motorola.android.provider.MotorolaSettings.getInt(MotorolaSettings.java:328)
03-17 12:29:08.571  2666  4296 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 12:29:08.571  2666  4296 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 12:29:08.571  2666  4296 W System.err: 	at com.motorola.ccc.checkin.MotorolaSettings.getInt(MotorolaSettings.java:106)
03-17 12:29:08.571  2666  4296 W System.err: 	at com.motorola.ccc.checkin.PrivacyHelper.readPrivacy(PrivacyHelper.java:413)
03-17 12:29:08.571  2666  4296 W System.err: 	at com.motorola.ccc.checkin.PrivacyHelper.reconfigurePrivacy(PrivacyHelper.java:160)
03-17 12:29:08.571  2666  4296 W System.err: 	at com.motorola.ccc.checkin.BcsConfigAndroid.handleConfigChange(BcsConfigAndroid.java:996)
03-17 12:29:08.571  2666  4296 W System.err: 	at com.motorola.ccc.checkin.BcsConfigAndroid.update(BcsConfigAndroid.java:518)
03-17 12:29:08.571  2666  4296 W System.err: 	at com.motorola.ccc.checkin.BcsCore.doConfig(BcsCore.java:662)
03-17 12:29:08.571  2666  4296 W System.err: 	at com.motorola.ccc.checkin.BcsCore.handleEvent(BcsCore.java:332)
03-17 12:29:08.571  2666  4296 W System.err: 	at com.motorola.ccc.checkin.BcsPlatformAndroid.handleCceSendSettingsResponse(BcsPlatformAndroid.java:432)
03-17 12:29:08.571  2666  4296 W System.err: 	at com.motorola.ccc.checkin.BcsPlatformAndroid.onReceiveActions(BcsPlatformAndroid.java:403)
03-17 12:29:08.571  2666  4296 W System.err: 	at com.motorola.ccc.checkin.BcsPlatformAndroid.access$000(BcsPlatformAndroid.java:87)
03-17 12:29:08.571  2666  4296 W System.err: 	at com.motorola.ccc.checkin.BcsPlatformAndroid$1.run(BcsPlatformAndroid.java:295)
03-17 12:29:08.571  2666  4296 W System.err: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-17 12:29:08.571  2666  4296 W System.err: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 12:29:08.571  2666  4296 W System.err: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 12:29:08.571  2666  4296 W System.err: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 12:29:08.571  2666  4296 W System.err: 	at java.lang.Thread.run(Thread.java:818)
03-17 12:29:08.574  2666  4296 I global frequency: BcsConfigAndroid:updateAllowedEventTagsForPrivacyProfile Blacklisted tags: (DUMMY_TAG:1416552400)
03-17 12:29:08.575  2666  4296 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
03-17 12:29:08.576  2666  4296 I global frequency: BcsConfigAndroid:updateAllowedEventTagsForPrivacyProfile new whitelisted checkin event tags: MOT_OTA:LOG,MOT_PRIVACY_PROFILE,DEV_ATTRIBS,CHECKIN_SUCCESS,MOT_CCE_STATS:CS_Notif_FFA,DEVICE_PROPERTIES,CHECKIN_FAILURE
03-17 12:29:08.576  2666  4296 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
03-17 12:29:08.578  2666  4296 D Checkin : publish the event [tag = MOT_PRIVACY_PROFILE event name = PRIVACY]
03-17 12:29:08.632   881  1516 I ActivityManager: Killing 4690:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
03-17 12:29:08.658  2666  4296 W Settings: Setting dropbox_quota_kb has moved from android.provider.Settings.System to android.provider.Settings.Global
03-17 12:29:08.658  2666  4296 W Settings: Setting dropbox_quota_kb has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
03-17 12:29:08.659  2666  4296 W Settings: Setting dropbox_max_files has moved from android.provider.Settings.System to android.provider.Settings.Global
03-17 12:29:08.659  2666  4296 W Settings: Setting dropbox_max_files has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
03-17 12:29:08.666  4797  4797 D AndroidRuntime: 
03-17 12:29:08.666  4797  4797 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-17 12:29:08.670  4797  4797 D AndroidRuntime: CheckJNI is OFF
03-17 12:29:08.706   881  1588 W libprocessgroup: failed to open /acct/uid_10005/pid_4618/cgroup.procs: No such file or directory
03-17 12:29:08.710   881  1299 W libprocessgroup: failed to open /acct/uid_10039/pid_4690/cgroup.procs: No such file or directory
03-17 12:29:08.713  1290  1290 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-17 12:29:08.713  1290  1290 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
03-17 12:29:08.725   881  1517 I ActivityManager: Killing 4349:com.google.android.apps.plus/u0a90 (adj 15): empty #7
03-17 12:29:08.752  1949  3670 I CheckinService: Done disabling old GoogleServicesFramework version
03-17 12:29:08.832   881  1595 W libprocessgroup: failed to open /acct/uid_10090/pid_4349/cgroup.procs: No such file or directory
03-17 12:29:08.851  1949  4817 I CheckinService: Checking schedule, now: 1458214148851 next: 1458214176919
03-17 12:29:08.851  1949  4817 I CheckinService: active receiver: disabled
03-17 12:29:08.874  1949  4818 I iu.SyncManager: SYNC; picasa accounts
03-17 12:29:08.884  1949  1949 D NetworkLogImpl: Loaded NetworkSpeedPredictor
03-17 12:29:08.886  1949  1949 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
03-17 12:29:08.893  1949  4818 I iu.UploadsManager: num queued entries: 0
03-17 12:29:08.894  1949  4818 I iu.UploadsManager: num updated entries: 0
03-17 12:29:08.895  1949  4818 I iu.SyncManager: NEXT; no task
03-17 12:29:08.895  4797  4797 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-17 12:29:08.936   881  1502 I ActivityManager: Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=4823 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
03-17 12:29:08.936   881  1588 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-17 12:29:08.959   278  1148 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (561 us)
03-17 12:29:08.977  1462  4216 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
03-17 12:29:08.991  4797  4797 D AndroidRuntime: Shutting down VM
03-17 12:29:09.038   881  3353 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4840 uid=10109 gids={50109, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-17 12:29:09.061  2666  2666 E ActivityThread: Performing stop of activity that is not resumed: {com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity}
03-17 12:29:09.061  2666  2666 E ActivityThread: java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity}
03-17 12:29:09.061  2666  2666 E ActivityThread: 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3396)
03-17 12:29:09.061  2666  2666 E ActivityThread: 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3477)
03-17 12:29:09.061  2666  2666 E ActivityThread: 	at android.app.ActivityThread.access$1100(ActivityThread.java:148)
03-17 12:29:09.061  2666  2666 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1321)
03-17 12:29:09.061  2666  2666 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 12:29:09.061  2666  2666 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
03-17 12:29:09.061  2666  2666 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5312)
03-17 12:29:09.061  2666  2666 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 12:29:09.061  2666  2666 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 12:29:09.061  2666  2666 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
03-17 12:29:09.061  2666  2666 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
03-17 12:29:09.094  1462  4216 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
03-17 12:29:09.112   881  1503 I ActivityManager: Activity reported stop, but no longer stopping: ActivityRecord{3a992be1 u0 com.motorola.ccc.ota/.ui.DownloadActivity t8}
,03-17 12:29:09.284  2025  4821 I GCM     : GCM config loaded
,03-17 12:29:09.323  4840  4840 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-17 12:29:09.388  4840  4840 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 3384-3388)
03-17 12:29:09.388  4840  4840 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 12:29:09.431  4840  4840 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {76be20f}
,03-17 12:29:09.434  4840  4840 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 12:29:09.445  4840  4840 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-17 12:29:09.469  4840  4840 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-17 12:29:09.473  4840  4840 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 12:29:09.478  4840  4840 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-17 12:29:09.610  4840  4840 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-17 12:29:09.621  4840  4840 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-17 12:29:09.621  4840  4840 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-17 12:29:09.622  4840  4840 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-17 12:29:09.622  4840  4840 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-17 12:29:09.622  4840  4840 I Adreno-EGL: Build Date: 10/28/14 Tue
03-17 12:29:09.622  4840  4840 I Adreno-EGL: Local Branch: 
03-17 12:29:09.622  4840  4840 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-17 12:29:09.622  4840  4840 I Adreno-EGL: Local Patches: NONE
03-17 12:29:09.622  4840  4840 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,03-17 12:29:09.708   881  1093 D BluetoothManagerService: Message: 20
,03-17 12:29:09.709   881  1093 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3935a79e:true
,03-17 12:29:09.847   881  1479 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4882 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 12:29:09.898  4840  4840 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 12:29:09.913  4840  4840 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-17 12:29:09.927  4840  4840 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,03-17 12:29:09.933  4840  4840 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 12:29:09.933  4840  4840 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 12:29:10.028  4840  4909 D OpenGLRenderer: Render dirty regions requested: true
,03-17 12:29:10.054  4840  4840 D Atlas   : Validating map...
,03-17 12:29:10.060  4840  4873 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-17 12:29:10.064   881   896 I ActivityManager: Killing 4646:com.google.android.music:main/u0a80 (adj 15): empty #7
,03-17 12:29:10.094  4399  4880 I Babel   : connection state changed from UNKNOWN to CONNECTED
,03-17 12:29:10.120   881  1479 W libprocessgroup: failed to open /acct/uid_10080/pid_4646/cgroup.procs: No such file or directory
,03-17 12:29:10.134   881  1568 I ActivityManager: Killing 4716:com.android.mms/u0a23 (adj 15): empty #7
,03-17 12:29:10.153   278   727 I SFPerfTracer:      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (44:191 vsyncs) (46:1033)
,03-17 12:29:10.163  4840  4909 I OpenGLRenderer: Initialized EGL, version 1.4
,03-17 12:29:10.173  4840  4909 D OpenGLRenderer: Enabling debug mode 0
,03-17 12:29:10.190   881  1504 W libprocessgroup: failed to open /acct/uid_10023/pid_4716/cgroup.procs: No such file or directory
,03-17 12:29:10.234  1419  1419 I Keyboard.Facilitator: onFinishInput()
,03-17 12:29:10.241   881  1094 I LaunchCheckinHandler: Displayed com.test.thalitest/.MainActivity,cp,ca,1246
03-17 12:29:10.241   881  1094 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s246ms
,03-17 12:29:10.366  4840  4916 E Adreno-ES20: <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
03-17 12:29:10.366  4840  4916 E Adreno-ES20: <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
03-17 12:29:10.366   277   411 E Vold    : Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,03-17 12:29:10.366   277   411 W Vold    : Returning OperationFailed - no handler for errno 0
03-17 12:29:10.367  4882  4917 W ContextImpl: Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,03-17 12:29:10.382   277   411 E Vold    : Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
03-17 12:29:10.382   277   411 W Vold    : Returning OperationFailed - no handler for errno 0
03-17 12:29:10.382  4882  4917 W ContextImpl: Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,03-17 12:29:10.413   277   411 E Vold    : Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
03-17 12:29:10.413   277   411 W Vold    : Returning OperationFailed - no handler for errno 0
03-17 12:29:10.414  4882  4918 W ContextImpl: Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,03-17 12:29:10.418  4840  4840 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 4840
,03-17 12:29:10.426   277   411 E Vold    : Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
03-17 12:29:10.426   277   411 W Vold    : Returning OperationFailed - no handler for errno 0
03-17 12:29:10.427  4882  4918 W ContextImpl: Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,03-17 12:29:10.431  4882  4882 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
03-17 12:29:10.431  4882  4882 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-17 12:29:10.431  4882  4882 I GAv4    :   adb logcat -s GAv4
,03-17 12:29:10.479  4882  4882 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-17 12:29:10.507  4882  4882 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-17 12:29:10.514   881  1502 I ActivityManager: Killing 4743:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,03-17 12:29:10.516  4882  4931 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-17 12:29:10.580   881  1479 W libprocessgroup: failed to open /acct/uid_10019/pid_4743/cgroup.procs: No such file or directory
,03-17 12:29:10.603  4840  4840 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-17 12:29:10.854  4882  4882 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-17 12:29:10.878  4882  4882 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 4877-4878)
03-17 12:29:10.878  4882  4882 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 12:29:10.886  4882  4882 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {290b3573}
,03-17 12:29:10.888  4882  4882 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-17 12:29:10.888  4882  4882 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-17 12:29:10.903  4882  4882 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-17 12:29:10.906  4882  4882 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-17 12:29:10.907  4882  4882 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-17 12:29:10.973  4882  4882 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
03-17 12:29:10.979  4882  4882 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-17 12:29:10.979  4882  4882 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-17 12:29:10.981  4882  4882 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-17 12:29:10.981  4882  4882 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-17 12:29:10.981  4882  4882 I Adreno-EGL: Build Date: 10/28/14 Tue
03-17 12:29:10.981  4882  4882 I Adreno-EGL: Local Branch: 
03-17 12:29:10.981  4882  4882 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-17 12:29:10.981  4882  4882 I Adreno-EGL: Local Patches: NONE
03-17 12:29:10.981  4882  4882 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,03-17 12:29:11.062  4840  4909 E Adreno-ES20: <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
03-17 12:29:11.062  4840  4909 E Adreno-ES20: <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,03-17 12:29:11.086  4882  4970 W AudioManagerAndroid: Requires BLUETOOTH permission
,03-17 12:29:11.092  4840  4912 D jxcore_app_log: JniHelper::setJavaVM(0xb8b58310), pthread_self() = -1192324576
03-17 12:29:11.102  4840  4912 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-17 12:29:11.102  4840  4912 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-17 12:29:11.102  4840  4912 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-17 12:29:11.102  4840  4912 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-17 12:29:11.102  4840  4912 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-17 12:29:11.102  4840  4912 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@277f800b added. We now have 1 listener(s)
03-17 12:29:11.102   881  1479 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
03-17 12:29:11.105  4840  4912 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:80:EB:7B:5A:05
03-17 12:29:11.109  4840  4912 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
03-17 12:29:11.110  4840  4912 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
03-17 12:29:11.110  4840  4912 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
03-17 12:29:11.110  4840  4912 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
03-17 12:29:11.115  4840  4912 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-17 12:29:11.115  4840  4912 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-17 12:29:11.115  4840  4912 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-17 12:29:11.115  4840  4912 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 44:80:EB:7B:5A:05
03-17 12:29:11.115  4840  4912 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-17 12:29:11.115  4840  4912 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-17 12:29:11.115  4840  4912 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-17 12:29:11.115  4840  4912 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-17 12:29:11.115  4840  4912 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-17 12:29:11.115  4840  4912 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-17 12:29:11.115  4840  4912 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b90c3a6 added. We now have 1 listener(s)
03-17 12:29:11.116  4840  4912 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-17 12:29:11.133  4840  4912 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,03-17 12:29:11.139  4840  4912 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
03-17 12:29:11.139  4840  4912 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,03-17 12:29:11.174   881  1076 I ActivityManager: Waited long enough for: ServiceRecord{1f0ae15e u0 com.motorola.ccc.checkin/.CheckinService}
,03-17 12:29:11.220   881  1503 I art     : Explicit concurrent mark sweep GC freed 20888(977KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/31MB, paused 1.770ms total 127.030ms
,03-17 12:29:11.220   881   894 I art     : WaitForGcToComplete blocked for 11.569ms for cause HeapTrim
,03-17 12:29:11.226   881  1237 D WifiService: New client listening to asynchronous messages
,03-17 12:29:11.226  4840  4912 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-17 12:29:11.227   881  1299 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,03-17 12:29:11.228  4840  4912 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:80:EB:7B:5A:05
,03-17 12:29:11.241  4882  4882 I NSApplication: Starting up...
,03-17 12:29:11.243  4840  4912 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-17 12:29:11.243  4840  4912 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-17 12:29:11.243  4840  4912 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-17 12:29:11.243  4840  4912 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-17 12:29:11.243  4840  4912 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-17 12:29:11.243  4840  4912 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-17 12:29:11.243  4840  4912 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-17 12:29:11.243  4840  4912 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-17 12:29:11.244  4840  4912 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-17 12:29:11.244  4840  4912 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-17 12:29:11.292   881  1504 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=4979 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 12:29:11.295   881  1504 I ActivityManager: Killing 4416:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,03-17 12:29:11.336  4840  4840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 12:29:11.339   278   278 I SFPerfTracer:      triggers: (rate: 14:387) (compose: 0:1) (post: 0:2) (render: 0:3) (35:1001 frames) (36:1083)
03-17 12:29:11.339   278   278 D SFPerfTracer:        layers: (3:11) (FocusedStackFrame (0xb73ff7b8): 0:14)* (DimLayer (0xb741dd30): 0:6)* (StatusBar (0xb74246f8): 0:123) (NavigationBar (0xb7428ac8): 0:32) (com.android.systemui.ImageWallpaper (0xb742ee18): 0:5)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb74326f8): 0:47)- (Starting com.test.thalitest (0xb7430a88): 0:40)- (com.test.thalitest/com.test.thalitest.MainActivity (0xb7420120): 36:42) 
03-17 12:29:11.340  4840  4840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 12:29:11.343  4840  4840 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-17 12:29:11.357  1290  1290 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 12:29:11.440   881  1479 W libprocessgroup: failed to open /acct/uid_10057/pid_4416/cgroup.procs: No such file or directory
,03-17 12:29:11.449  1290  1290 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-17 12:29:11.450  1290  1290 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 12:29:11.757   881  1503 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=4998 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,03-17 12:29:11.758   881  1503 I ActivityManager: Killing 4778:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,03-17 12:29:11.779   307   307 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 21.959ms
,03-17 12:29:11.799   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 19.456ms
,03-17 12:29:11.820   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 253us total 20.298ms
,03-17 12:29:11.870   881  1568 W libprocessgroup: failed to open /acct/uid_10035/pid_4778/cgroup.procs: No such file or directory
,03-17 12:29:11.892  4998  4998 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 12:29:12.208  4840  4978 W jxcore-log: Initializing JXcore engine
03-17 12:29:12.208  4840  4978 W jxcore-log: JXcore engine is ready
,03-17 12:29:12.288  4978  4978 W Thread-505: type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10109 path="socket:[9349]" dev="sockfs" ino=9349 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-17 12:29:12.288  4978  4978 W Thread-505: type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10109 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
03-17 12:29:12.288  4978  4978 W Thread-505: type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10109 path="socket:[9537]" dev="sockfs" ino=9537 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-17 12:29:12.288  4978  4978 W Thread-505: type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10109 path="socket:[22620]" dev="sockfs" ino=22620 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,03-17 12:29:12.324  4840  4978 W jxcore-log: Starting JXcore engine
,03-17 12:29:12.358  1290  1290 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 12:29:12.474  4840  4978 W jxcore-log: Platform android
03-17 12:29:12.474  4840  4978 W jxcore-log: 
03-17 12:29:12.475  4840  4978 W jxcore-log: Process ARCH arm
03-17 12:29:12.475  4840  4978 W jxcore-log: 
,03-17 12:29:12.515   303   402 I ThermalEngine: Sensor:xo_therm_pu2:38000 mC
,03-17 12:29:12.536   881   896 I ActivityManager: Start proc com.motorola.context for broadcast com.motorola.context/.receiver.DateChangeBroadcastReceiver: pid=5030 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,03-17 12:29:12.537   881   896 I ActivityManager: Killing 4823:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,03-17 12:29:12.640   881  3353 W libprocessgroup: failed to open /acct/uid_10088/pid_4823/cgroup.procs: No such file or directory
,03-17 12:29:12.641   881  1253 D TaskPersister: removeObsoleteFile: deleting file=8_task_thumbnail.png
,03-17 12:29:12.653  5030  5030 W ResourcesManager: Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,03-17 12:29:12.758   881  1595 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=5049 uid=10096 gids={50096, 9997} abi=armeabi-v7a
,03-17 12:29:12.791   881  1504 I ActivityManager: Killing 4399:com.google.android.talk/u0a70 (adj 15): empty #7
,03-17 12:29:12.793  4840  4978 I jxcore-log: JXcore Cordova bridge is ready!
03-17 12:29:12.793  4840  4978 I jxcore-log: 
,03-17 12:29:12.794  4840  4978 W jxcore-log: JXcore engine is started
,03-17 12:29:12.797  4840  4912 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-17 12:29:12.799  4840  4840 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-17 12:29:12.816  4840  4978 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-17 12:29:12.816  4840  4978 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-17 12:29:12.824  4840  4840 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,03-17 12:29:12.824  4840  4840 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,03-17 12:29:12.878   881  1568 W libprocessgroup: failed to open /acct/uid_10070/pid_4399/cgroup.procs: No such file or directory
03-17 12:29:12.878  1462  4216 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,03-17 12:29:12.880  4840  4912 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 55ms. Plugin should use CordovaInterface.getThreadPool().
,03-17 12:29:12.886  1462  4216 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,03-17 12:29:12.896  5049  5049 I System.out: TimeService: Loaded Library 
,03-17 12:29:12.898  5049  5049 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1458214152897
03-17 12:29:12.898  5049  5049 D         : TimeServiceNative: User Time to be set is 1458214152898
03-17 12:29:12.898  5049  5049 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
03-17 12:29:12.898  5049  5049 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
03-17 12:29:12.898  5049  5049 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1458214152898
,03-17 12:29:12.899  5049  5049 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
,03-17 12:29:12.900   315   830 D QC-time-services: Daemon: Connection accepted:time_genoff
,03-17 12:29:12.901   315  5071 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1458214152898
03-17 12:29:12.901   315  5071 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1458214152898, operation = 0
03-17 12:29:12.901   315  5071 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS2/17/116 11:27:23
,03-17 12:29:12.902   315  5071 D QC-time-services: Daemon:Value read from RTC seconds = 1458214043000
03-17 12:29:12.902   315  5071 D QC-time-services: Daemon:new time 1458214152898 
,03-17 12:29:12.902   315  5071 D QC-time-services: Daemon: delta 109898 genoff 109898 
03-17 12:29:12.902   315  5071 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 109898 to memory
03-17 12:29:12.902   315  5071 D QC-time-services: Daemon:Opening File: /data/time/ats_2
03-17 12:29:12.902   315  5071 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-17 12:29:12.910  2666  2666 D OtaApp  : [debug] > DownloadActivity, FormattedText
,03-17 12:29:12.912  2666  2666 I OtaApp  : [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,03-17 12:29:12.914  2666  2666 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-17 12:29:12.916  2666  2666 I OtaApp  : [info] > Exceed max defer attempts for optional update, suppresing later btn
,03-17 12:29:12.916  2666  2666 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-17 12:29:12.919  2666  2666 D OtaApp  : [debug] > cancelling the previous pending intent set for download later
,03-17 12:29:12.921  2666  2666 I OtaApp  : [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,03-17 12:29:12.922  2666  2666 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-17 12:29:12.931   315  5071 D QC-time-services: Updating the TOD offset
03-17 12:29:12.931   315  5071 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 109898 to memory
03-17 12:29:12.931   315  5071 D QC-time-services: Daemon:Opening File: /data/time/ats_1
03-17 12:29:12.931   315  5071 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-17 12:29:12.947   315  5071 E QC-time-services: Daemon:Update to modem bit set
03-17 12:29:12.947   315  5071 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
,03-17 12:29:12.947   315  5071 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 18446743757744861514
03-17 12:29:12.948  5049  5049 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
03-17 12:29:12.949   881  1299 I ActivityManager: Killing 4882:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,03-17 12:29:12.951   315   828 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
03-17 12:29:12.952   315   830 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,03-17 12:29:12.975  1419  1419 I Keyboard.Facilitator: onFinishInput()
,03-17 12:29:12.976  4840  4840 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-17 12:29:13.165  5069  5069 D AndroidRuntime: 
03-17 12:29:13.165  5069  5069 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,03-17 12:29:13.173  5069  5069 D AndroidRuntime: CheckJNI is OFF
,03-17 12:29:13.231   881  1595 W libprocessgroup: failed to open /acct/uid_10081/pid_4882/cgroup.procs: No such file or directory
,03-17 12:29:13.373  5069  5069 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-17 12:29:13.392   881  1076 I ActivityManager: Force stopping com.test.thalitest appid=10109 user=-1: uninstall pkg
03-17 12:29:13.392   881  1076 I ActivityManager: Killing 4840:com.test.thalitest/u0a109 (adj 1): stop com.test.thalitest
,03-17 12:29:13.437   881  1237 D WifiService: Client connection lost with reason: 4
,03-17 12:29:13.471   881   897 I WindowState: WIN DEATH: Window{3dd5767c u0 com.test.thalitest/com.test.thalitest.MainActivity EXITING}
,03-17 12:29:13.506   881  1115 W PackageSettings: Skipping PackageSetting{39058666 com.example.hello/10568} due to missing metadata
,03-17 12:29:13.640   881  1595 W ActivityManager: Spurious death for ProcessRecord{21e636d3 4840:com.test.thalitest/u0a109}, curProc for 4840: null
,03-17 12:29:13.703   881   896 I ActivityManager: Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=5104 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,03-17 12:29:13.704   881  1115 I ActivityManager: Force stopping com.test.thalitest appid=10109 user=0: pkg removed
,03-17 12:29:13.773  3245  3245 I art     : Explicit concurrent mark sweep GC freed 4142(223KB) AllocSpace objects, 3(48KB) LOS objects, 39% free, 7MB/12MB, paused 804us total 58.840ms
,03-17 12:29:13.813   881  1225 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-17 12:29:13.815  1552  1552 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 12:29:13.824  2025  2202 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-17 12:29:13.827  1419  1419 I Keyboard.Facilitator: resetDictionaries() : en_US
,03-17 12:29:13.831  1419  5130 I Keyboard.Facilitator.DecoderInitializer: run()
,03-17 12:29:13.843  1571  1571 I art     : Explicit concurrent mark sweep GC freed 2056(109KB) AllocSpace objects, 2(72KB) LOS objects, 25% free, 13MB/17MB, paused 450us total 75.673ms
,03-17 12:29:13.852  1419  5130 I Decoder : createOrResetDecoder
,03-17 12:29:13.933  1419  5130 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,03-17 12:29:13.961  5104  5104 I GAv4    : Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
03-17 12:29:13.961  5104  5104 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-17 12:29:13.961  5104  5104 I GAv4    :   adb logcat -s GAv4
,03-17 12:29:13.986  5104  5104 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-17 12:29:13.990  1419  5130 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,03-17 12:29:14.003  1419  5130 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
03-17 12:29:14.003  1419  5130 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,03-17 12:29:14.009  1419  5130 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
03-17 12:29:14.009  1419  5130 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,03-17 12:29:14.013  1419  5130 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,03-17 12:29:14.014  1419  5130 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,03-17 12:29:14.017  5104  5104 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-17 12:29:14.019  1419  5130 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,03-17 12:29:14.022  1419  5130 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
03-17 12:29:14.022  1419  5130 I Keyboard.Facilitator.Delight2FileSweeper: run()
03-17 12:29:14.022  1419  5130 I Keyboard.Facilitator.RecurringTaskScheduler: run()
03-17 12:29:14.022  1419  5130 I StatsUtilsManager: startPeriodStatsRecorder() : Success
03-17 12:29:14.022  1419  5130 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
03-17 12:29:14.023   881   881 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
03-17 12:29:14.023   881   881 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,03-17 12:29:14.027  5104  5134 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-17 12:29:14.071   881  1299 I ActivityManager: Killing 4438:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,03-17 12:29:14.101   881  1115 I art     : Explicit concurrent mark sweep GC freed 22919(1656KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 21MB/32MB, paused 6.374ms total 304.300ms
,03-17 12:29:14.149  5069  5069 D AndroidRuntime: Shutting down VM
,03-17 12:29:14.161   881  1504 W libprocessgroup: failed to open /acct/uid_10016/pid_4438/cgroup.procs: No such file or directory
,03-17 12:29:14.167  2666  2666 D EmailService.MarketingOptInSetter: received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,03-17 12:29:14.168  1571  1571 I Launcher: Deferring update until onResume
,03-17 12:29:14.173  2666  2666 D GetNotificationsWS: bindWebServices(): registering our AIDL callback...
,03-17 12:29:14.175  2666  5139 I SundryService: onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,03-17 12:29:14.175  2666  5139 E SQLiteLog: (284) automatic index on registration(APP_ID)
03-17 12:29:14.176  2666  5139 D WaitableIntentService: ServiceHandler.handleMessage: mWaitCount=0
,03-17 12:29:14.178  2666  2666 D GetNotificationsWS: onServiceConnected()
,03-17 12:29:14.179  2666  2666 D GetNotificationsWS: onServiceConnected(): Registered for remote service callbacks...
,03-17 12:29:14.181  2666  2666 D GetNotificationsWS: unbindWebServices(): un-registering our AIDL callback...
,03-17 12:29:14.182  2666  5140 I PushService: started with background data enabled, making sure notification mechanism is enabled
,03-17 12:29:14.184  1462  1462 D Central_PollingManager: wake lock released
,03-17 12:29:14.186   881  1253 D TaskPersister: removeObsoleteFile: deleting file=9_task.xml
,03-17 12:29:14.186   881  1253 D TaskPersister: removeObsoleteFile: deleting file=8_task.xml
,03-17 12:29:14.186   881  1253 D TaskPersister: removeObsoleteFile: deleting file=9_task_thumbnail.png
,03-17 12:29:14.209  2666  2666 D OtaApp  : [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,03-17 12:29:14.211  2666  2666 D OtaApp  : [debug] > UpdateReceiver: Received true from doSanityCheck.
03-17 12:29:14.212  2666  2666 D OtaApp  : [debug] > In cancelAnyPendingIntentSetPreviously
,03-17 12:29:14.215   881   897 I ActivityManager: START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,03-17 12:29:14.224  2666  2666 D OtaApp  : [debug] > DownloadActivity, FormattedText
,03-17 12:29:14.226  2666  2666 I OtaApp  : [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,03-17 12:29:14.227  2666  2666 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-17 12:29:14.229  2666  2666 I OtaApp  : [info] > Exceed max defer attempts for optional update, suppresing later btn
03-17 12:29:14.230  2666  2666 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-17 12:29:14.265   881  3353 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5141 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 12:29:14.268  2666  2666 D OtaApp  : [debug] > cancelling the previous pending intent set for download later
,03-17 12:29:14.292  2666  2666 I OtaApp  : [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,03-17 12:29:14.293  2666  2666 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-17 12:29:14.320   278   727 I SFPerfTracer:      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (62:313 vsyncs) (64:1168)
,03-17 12:29:14.327  5141  5141 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-17 12:29:14.360  1290  1290 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 12:29:14.361  2666  4296 E global frequency: no tags to log
,03-17 12:29:14.363  2666  4296 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,03-17 12:29:14.364  5141  5141 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@37a65f70(com.android.providers.calendar.CalendarProvider2@238af2e9)
,03-17 12:29:14.410   881  1115 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=5162 uid=10010 gids={50010, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,03-17 12:29:14.461  1290  1290 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-17 12:29:14.461  1290  1290 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 12:29:14.466  5141  5161 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,03-17 12:29:14.471  2666  2666 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-17 12:29:14.473  5141  5158 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,03-17 12:29:14.477  1552  2503 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,--------- beginning of crash
03-17 12:29:14.483  5141  5161 E AndroidRuntime: FATAL EXCEPTION: Thread-516
03-17 12:29:14.483  5141  5161 E AndroidRuntime: Process: com.android.providers.calendar, PID: 5141
03-17 12:29:14.483  5141  5161 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-17 12:29:14.483  5141  5161 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-17 12:29:14.483  5141  5161 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-17 12:29:14.483  5141  5161 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-17 12:29:14.483  5141  5161 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-17 12:29:14.483  5141  5161 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-17 12:29:14.483  5141  5161 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-17 12:29:14.483  5141  5161 E AndroidRuntime: 	at com.android.providers.calendar.CalendarProvider2.removeStaleAccounts(CalendarProvider2.java:5003)
03-17 12:29:14.483  5141  5161 E AndroidRuntime: 	at com.android.providers.calendar.CalendarProvider2.verifyAccounts(CalendarProvider2.java:599)
03-17 12:29:14.483  5141  5161 E AndroidRuntime: 	at com.android.providers.calendar.CalendarProvider2.access$300(CalendarProvider2.java:88)
03-17 12:29:14.483  5141  5161 E AndroidRuntime: 	at com.android.providers.calendar.CalendarProvider2$PostInitializeThread.run(CalendarProvider2.java:584)
,03-17 12:29:14.486  5141  5158 E DatabaseUtils: Writing exception to parcel
03-17 12:29:14.486  5141  5158 E DatabaseUtils: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-17 12:29:14.486  5141  5158 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-17 12:29:14.486  5141  5158 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-17 12:29:14.486  5141  5158 E DatabaseUtils: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-17 12:29:14.486  5141  5158 E DatabaseUtils: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-17 12:29:14.486  5141  5158 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-17 12:29:14.486  5141  5158 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-17 12:29:14.486  5141  5158 E DatabaseUtils: 	at com.android.providers.calendar.CalendarProvider2.acquireInstanceRange(CalendarProvider2.java:1351)
03-17 12:29:14.486  5141  5158 E DatabaseUtils: 	at com.android.providers.calendar.CalendarProvider2.handleInstanceQuery(CalendarProvider2.java:1104)
03-17 12:29:14.486  5141  5158 E DatabaseUtils: 	at com.android.providers.calendar.CalendarProvider2.queryInternal(CalendarProvider2.java:938)
03-17 12:29:14.486  5141  5158 E DatabaseUtils: 	at com.android.providers.calendar.CalendarProvider2.query(CalendarProvider2.java:839)
03-17 12:29:14.486  5141  5158 E DatabaseUtils: 	at android.content.ContentProvider.query(ContentProvider.java:950)
03-17 12:29:14.486  5141  5158 E DatabaseUtils: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:210)
03-17 12:29:14.486  5141  5158 E DatabaseUtils: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
03-17 12:29:14.486  5141  5158 E DatabaseUtils: 	at android.os.Binder.execTransact(Binder.java:446)
,03-17 12:29:14.488  3344  3376 W AsyncQuery: Exception thrown during handling EVENT_ARG_QUERY
03-17 12:29:14.488  3344  3376 W AsyncQuery: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-17 12:29:14.488  3344  3376 W AsyncQuery: 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:179)
03-17 12:29:14.488  3344  3376 W AsyncQuery: 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
03-17 12:29:14.488  3344  3376 W AsyncQuery: 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
03-17 12:29:14.488  3344  3376 W AsyncQuery: 	at android.content.ContentResolver.query(ContentResolver.java:478)
03-17 12:29:14.488  3344  3376 W AsyncQuery: 	at android.content.ContentResolver.query(ContentResolver.java:422)
03-17 12:29:14.488  3344  3376 W AsyncQuery: 	at android.content.AsyncQueryHandler$WorkerHandler.handleMessage(AsyncQueryHandler.java:79)
03-17 12:29:14.488  3344  3376 W AsyncQuery: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 12:29:14.488  3344  3376 W AsyncQuery: 	at android.os.Looper.loop(Looper.java:135)
03-17 12:29:14.488  3344  3376 W AsyncQuery: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-17 12:29:14.490   881  1504 I ActivityManager: Killing 4979:com.android.chrome/u0a52 (adj 15): empty #7
03-17 12:29:14.502   881  5182 E DropBoxManagerService: Can't write: system_app_crash
03-17 12:29:14.502   881  5182 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop105.tmp: open failed: EROFS (Read-only file system)
03-17 12:29:14.502   881  5182 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-17 12:29:14.502   881  5182 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-17 12:29:14.502   881  5182 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-17 12:29:14.502   881  5182 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-17 12:29:14.502   881  5182 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-17 12:29:14.502   881  5182 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12258)
03-17 12:29:14.502   881  5182 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-17 12:29:14.502   881  5182 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-17 12:29:14.502   881  5182 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-17 12:29:14.502   881  5182 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-17 12:29:14.502   881  5182 E DropBoxManagerService: 	... 5 more
,03-17 12:29:14.582  1462  2695 I art     : Explicit concurrent mark sweep GC freed 4936(219KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 592us total 27.063ms
,03-17 12:29:14.585  2666  2666 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-17 12:29:14.597  2666  2666 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,03-17 12:29:14.728   881  1222 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,03-17 12:29:14.729   881  1222 E CheckinProvider: SQLiteDiskIOException:
03-17 12:29:14.729   881  1222 E CheckinProvider: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-17 12:29:14.729   881  1222 E CheckinProvider: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-17 12:29:14.729   881  1222 E CheckinProvider: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-17 12:29:14.729   881  1222 E CheckinProvider: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-17 12:29:14.729   881  1222 E CheckinProvider: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-17 12:29:14.729   881  1222 E CheckinProvider: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-17 12:29:14.729   881  1222 E CheckinProvider: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-17 12:29:14.729   881  1222 E CheckinProvider: 	at com.motorola.android.server.checkin.CheckinProvider.insertEvents(CheckinProvider.java:776)
03-17 12:29:14.729   881  1222 E CheckinProvider: 	at com.motorola.android.server.checkin.CheckinProvider.access$000(CheckinProvider.java:67)
03-17 12:29:14.729   881  1222 E CheckinProvider: 	at com.motorola.android.server.checkin.CheckinProvider$EventInsertThread.run(CheckinProvider.java:910)
,03-17 12:29:14.731   881  1222 E CheckinProvider: Exception:
03-17 12:29:14.731   881  1222 E CheckinProvider: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
03-17 12:29:14.731   881  1222 E CheckinProvider: 	at android.database.sqlite.SQLiteSession.throwIfNoTransaction(SQLiteSession.java:915)
03-17 12:29:14.731   881  1222 E CheckinProvider: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:398)
03-17 12:29:14.731   881  1222 E CheckinProvider: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
03-17 12:29:14.731   881  1222 E CheckinProvider: 	at com.motorola.android.server.checkin.CheckinProvider.insertEvents(CheckinProvider.java:799)
03-17 12:29:14.731   881  1222 E CheckinProvider: 	at com.motorola.android.server.checkin.CheckinProvider.access$000(CheckinProvider.java:67)
03-17 12:29:14.731   881  1222 E CheckinProvider: 	at com.motorola.android.server.checkin.CheckinProvider$EventInsertThread.run(CheckinProvider.java:910)
,03-17 12:29:14.858   278   709 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
