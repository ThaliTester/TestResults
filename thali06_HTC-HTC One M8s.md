#### Test 625090941eef958_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
03-17 08:36:31.418  4235  4235 V TransactionService: 1-Creating TransactionService
03-17 08:36:31.418   921   921 D htcCheckinService: onStartCommand()
03-17 08:36:31.418   921   921 D htcCheckinService: onStartCommand() the action name = null
03-17 08:36:31.418   921  4520 D htcCheckinService: InitThread start
03-17 08:36:31.418   921   921 D htcCheckinService: ConnectivityReceiver - onReceive() - original mNetworkConnected = false
03-17 08:36:31.418   921   921 D htcCheckinService: ConnectivityReceiver - onReceive() - new mNetworkConnected = true
03-17 08:36:31.428  4235  4235 V TransactionService: onStartCommand: 1
03-17 08:36:31.428  4235  4235 D MmsSystemEventReceiver: unRegisterForConnectionStateChanges
03-17 08:36:31.428  4235  4519 V TransactionService: 4-Handling incoming message: { when=-1ms what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
03-17 08:36:31.428  4235  4519 V TransactionService: Loading previous transactions.
03-17 08:36:31.438   921  1721 D Process : killProcessQuiet, pid=3890
03-17 08:36:31.438   921  1721 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
--------- beginning of system
03-17 08:36:31.438   921  1721 I ActivityManager: Killing 3890:com.htc.csrecommend/u0a31 (adj 15): empty #17
03-17 08:36:31.498   921  1514 I ActivityManager: Recipient 3890
,03-17 08:36:31.558  1433  2424 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
03-17 08:36:31.558  1433  2424 D AccFlag : device_type: 1
03-17 08:36:31.568  4235  4519 D TransactionService: Force clearing mTransactionList
03-17 08:36:31.568  4235  4519 D TransactionService: Force set service start id to 1
03-17 08:36:31.568  4235  4519 V TransactionService: stopSelfIfIdle: unRegisterForConnectionStateChanges
03-17 08:36:31.568  4235  4519 D MmsSystemEventReceiver: unRegisterForConnectionStateChanges
03-17 08:36:31.568  4235  4235 V TransactionService: Destroying TransactionService
03-17 08:36:31.568  4235  4519 D TransactionService: stopSelfResult: true, mLastHandledServiceId: 1
03-17 08:36:31.578  4235  4519 V TransactionService: 4-Handling incoming message: { when=-6ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
03-17 08:36:31.688   921  2373 D PMS     : acquireWL(3be990be): PARTIAL_WAKE_LOCK  AlarmAlertWakeLock_600 0x1 4502 10090 null
03-17 08:36:31.708  4502  4502 I WorldClock.Global: isHEPDevice = true
03-17 08:36:31.708  4502  4502 W SystemReader: Cannot find support_china_sense_feature, use default value instead
03-17 08:36:31.718   921   921 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.dsi.ant.server.AntService.startService:129 
03-17 08:36:31.718   921   921 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.dsi.ant.server.AntService.startService:129 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
03-17 08:36:31.728  4407  4407 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
03-17 08:36:31.738   921   921 I ActivityManager: Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=4538 uid=10098 gids={50098, 9997, 3003} abi=arm64-v8a
03-17 08:36:31.748  4502  4502 I WorldClock.AlarmUtils: saveSupportOffAlarmInPreference: isSupport = false
03-17 08:36:31.758  4502  4502 I WorldClock.AlarmService: isDeviceEncryptionEnabled = false
03-17 08:36:31.758   921  1712 D PMS     : releaseWL(3be990be): PARTIAL_WAKE_LOCK  AlarmAlertWakeLock_600 0x1 null
03-17 08:36:31.758  4502  4537 W WorldClock.AlarmService: updateAlarms: AlarmUtils.disableExpiredAlarms fail e = java.lang.NullPointerException: Attempt to invoke virtual method 'int java.util.ArrayList.size()' on a null object reference
03-17 08:36:31.758   921  1719 I ActivityManager: Killing 3912:com.htc.home.personalize/1000 (adj 15): empty #17
03-17 08:36:31.758   921  1719 D Process : killProcessQuiet, pid=3912
03-17 08:36:31.758   439   439 I art     : Explicit concurrent mark sweep GC freed 8607(365KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 197us total 22.612ms
03-17 08:36:31.758   921  1719 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
03-17 08:36:31.768  4502  4537 I WorldClock.AlarmUtils: Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
03-17 08:36:31.778   439   439 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 142us total 16.743ms
03-17 08:36:31.798  4407  4407 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
03-17 08:36:31.798  4407  4407 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@5742635: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-17 08:36:31.798  4407  4407 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
03-17 08:36:31.798   439   439 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 143us total 16.746ms
03-17 08:36:31.858  1491  2067 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
03-17 08:36:31.858  1491  2067 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@3508dd95 +
03-17 08:36:31.858  1491  2067 I Prism.WidgetManager: onLoadItems() +
03-17 08:36:31.878  4533  4563 E cutils-trace: Error opening trace file: Permission denied (13)
03-17 08:36:31.898   921  1721 I ActivityManager: Recipient 3912
03-17 08:36:31.898   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 5
03-17 08:36:31.898   921   921 E WifiTrafficPoller:  packet count Tx=58 Rx=115
03-17 08:36:31.898  1212  1212 D WIFI_ICON: WifiActivity: 0
03-17 08:36:31.898   921   921 E WifiTrafficPoller: notifying of data activity 0
03-17 08:36:31.898  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
03-17 08:36:31.928  1491  2067 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
03-17 08:36:31.968  4502  4537 I WorldClock.AlarmUtils: Cancel any alarm from alarm manager
03-17 08:36:31.978  4502  4537 I WorldClock.AlarmUtils: broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
03-17 08:36:31.988  1212  1616 I IntentController: receive(android.intent.action.ALARM_CHANGED,1,false)
03-17 08:36:31.988  4533  4533 D CustomizationManager: ====startRecUseTime====
03-17 08:36:31.988  4533  4533 D htc.customization.log.level:  is 
03-17 08:36:31.988  4533  4533 W CustomizationLogLevel: Level value is invalid, use default level 2
03-17 08:36:32.018  4502  4537 I WorldClock.AlarmUtils: isDeviceEncryptionEnabled = false
03-17 08:36:32.018  4502  4537 I WorldClock.AlarmUtils: Calculate next off alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
03-17 08:36:32.018  4502  4537 I WorldClock.AlarmService: resetStopwatchToDefault
03-17 08:36:32.048  4502  4577 I WorldClock.DmdCmd: This version is general off mode alarm function
03-17 08:36:32.048  4502  4577 W WorldClock.DmdCmd: Conn: fail e = java.io.IOException: No such file or directory
03-17 08:36:32.098  4533  4533 D CustomizationManager:  Read ACC file spent 0.067 (s)
03-17 08:36:32.098  4533  4533 D CIDMapFileReader: Parsing tag item name = HTC__001
03-17 08:36:32.098  4533  4533 D CIDMapFileReader: Parsing tag item name = HTC__102
03-17 08:36:32.098  4533  4533 D CIDMapFileReader: Parsing tag item name = HTC__Y13
03-17 08:36:32.098  4533  4533 D CIDMapFileReader: Parsing tag item name = HTC__032
03-17 08:36:32.108  4533  4533 D CIDMapFileReader: Parsing tag item name = HTC__M27
03-17 08:36:32.108  3496  3571 I HtcModeClient: handler message = 4011
03-17 08:36:32.108  3496  3571 E HtcModeClient: Check connection and retry 2 times.
03-17 08:36:32.108  4533  4533 D CIDMapFileReader: Parsing tag item name = HTC__002
03-17 08:36:32.108  4533  4533 D CIDMapFileReader: Parsing tag item name = HTC__031
03-17 08:36:32.108  4533  4533 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__102.xml
03-17 08:36:32.108  4533  4533 I CustomizationCIDLoader: Parsing tag category name = system
03-17 08:36:32.108  4533  4533 I CustomizationCIDLoader: Parsing tag category name = application
03-17 08:36:32.108  4533  4533 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
03-17 08:36:32.108  4533  4533 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
03-17 08:36:32.108  4533  4533 I CustomizationCIDLoader: Parsing tag category name = AudioService
03-17 08:36:32.108  4533  4533 I CustomizationCIDLoader: Parsing tag category name = Settings
03-17 08:36:32.108  4533  4533 I CustomizationCIDLoader: Parsing tag category name = ACC
03-17 08:36:32.108  4407  4426 I art     : Background sticky concurrent mark sweep GC freed 33047(1573KB) AllocSpace objects, 2(40KB) LOS objects, 21% free, 3MB/4MB, paused 22.351ms total 101.715ms
03-17 08:36:32.108  4533  4533 I CustomizationCIDLoader: add string-array item, value = 42507
03-17 08:36:32.108  4533  4533 I CustomizationCIDLoader: add string-array item, value = 21902
03-17 08:36:32.108  4533  4533 I CustomizationCIDLoader: add string-array item, value = 26006:26001.26002.26003
03-17 08:36:32.108  4533  4533 I CustomizationCIDLoader: add string-array item, value = 23420
03-17 08:36:32.108  4533  4533 I CustomizationCIDLoader: add string-array item, value = 22299
03-17 08:36:32.108  4533  4533 I CustomizationCIDLoader: add string-array item, value = 24002
03-17 08:36:32.108  4533  4533 I CustomizationCIDLoader: add string-array item, value = 23210
03-17 08:36:32.108  4533  4533 I CustomizationCIDLoader: add string-array item, value = 23205
03-17 08:36:32.108  4533  4533 I CustomizationCIDLoader: add string-array item, value = 23806
03-17 08:36:32.108  4533  4533 I CustomizationCIDLoader: add string-array item, value = 23430
03-17 08:36:32.108  4533  4533 I CustomizationCIDLoader: add string-array item, value = 23408
03-17 08:36:32.108  4533  4533 I CustomizationCIDLoader: add string-array item, value = 27205
03-17 08:36:32.108  4533  4533 I CustomizationCIDLoader: add string-array item, value = 42507:C:1:0
03-17 08:36:32.108  4533  4533 I CustomizationCIDLoader: add string-array item, value = 21902:C:1:0
03-17 08:36:32.108  4533  4533 I CustomizationCIDLoader: add string-array item, value = 26006:D:1:0
03-17 08:36:32.108  4533  4533 I CustomizationCIDLoader: add string-array item, value = 23420:D:0:0
03-17 08:36:32.108  4533  4533 I CustomizationCIDLoader: add string-array item, value = 22299:D:0:0
03-17 08:36:32.108  4533  4533 I CustomizationCIDLoader: add string-array item, value = 24002:D:0:0
03-17 08:36:32.108  4533  4533 I CustomizationCIDLoader: add string-array item, value = 23210:D:2:0
03-17 08:36:32.108  4533  4533 I CustomizationCIDLoader: add string-array item, value = 23205:D:0:0
03-17 08:36:32.108  4533  4533 I CustomizationCIDLoader: add string-array item, value = 23806:D:0:0
03-17 08:36:32.108  4533  4533 I CustomizationCIDLoader: add string-array item, value = 23430:C:1:0
03-17 08:36:32.108  4533  4533 I CustomizationCIDLoader: add string-array item, value = 23408:C:1:0
03-17 08:36:32.108  4533  4533 I CustomizationCIDLoader: add string-array item, value = 27205:C:1:0
03-17 08:36:32.118  4533  4533 D CustomizationManager:  Read CID file spent 0.122 (s)
03-17 08:36:32.118  4533  4533 D CustomizationManager:  All configurations done spent 0.123 (s)
03-17 08:36:32.118  4502  4537 I WorldClock.AlarmService: resetTimerToDefault
03-17 08:36:32.118  4538  4538 E UpdateRequestReceiver: ignoring update request
03-17 08:36:32.128  4538  4538 E UpdateRequestReceiver: ignoring update request
03-17 08:36:32.158   921  1157 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 4533 on display 0
03-17 08:36:32.158  4538  4538 E UpdateRequestReceiver: ignoring update request
03-17 08:36:32.158   921  1057 D PMS     : acquireHCC(325f1922): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 921 1000 null
03-17 08:36:32.168   921  1057 D PMS     : acquireHCC(3e723fb3): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 921 1000 null
03-17 08:36:32.178   921  1046 I AnimationUtil: isHTCRecent(ThaliTest/Recent screens.)/4
03-17 08:36:32.178   921  1157 D PMS     : acquireWL(ef9a56e): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 921 1000 null
03-17 08:36:32.178  1491  1491 I FeedHostManager: [onPause]
03-17 08:36:32.188  1491  1491 I FeedProviderManager: onPause
03-17 08:36:32.188  1491  1491 I FeedHostManager: [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@117222c9
03-17 08:36:32.188  1491  2431 I SocialFeedProvider: +onPause
03-17 08:36:32.188  1491  2431 I SocialFeedProvider: -onPause
03-17 08:36:32.188   921  1555 W HtcSystemUPManager: HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
03-17 08:36:32.188  4538  4538 E UpdateRequestReceiver: ignoring update request
03-17 08:36:32.198   921  1515 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4594 uid=10195 gids={50195, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-17 08:36:32.218  1491  2067 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-17 08:36:32.228  4538  4538 E UpdateRequestReceiver: ignoring update request
03-17 08:36:32.258  1491  1491 I TrimMemoryManager: [trimMemory] 20
03-17 08:36:32.258  4538  4538 E UpdateRequestReceiver: ignoring update request
03-17 08:36:32.258  4334  4334 I DeviceManagement: WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.BootCompletedWorkflow] args=[null]
03-17 08:36:32.268  4334  4334 I DeviceManagement: WorkflowService: Starting workflow service
03-17 08:36:32.278  4334  4619 I DeviceManagement: WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.BootCompletedWorkflow@1b6d21b8] args=[Bundle[EMPTY_PARCEL]]
03-17 08:36:32.278  4334  4619 I DeviceManagement: BootCompletedWorkflow: ==================================================
03-17 08:36:32.278  4334  4619 I DeviceManagement: BootCompletedWorkflow: Boot completed
03-17 08:36:32.278  4334  4619 I DeviceManagement: BootCompletedWorkflow: ==================================================
03-17 08:36:32.298   921  1044 D StatusBarManagerService: setSystemUiVisibility(0x8600)
03-17 08:36:32.298   921  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-17 08:36:32.298   921  1044 D StatusBarManagerService: hiding MENU key
03-17 08:36:32.298  4334  4619 I DeviceManagement: BackgroundController: *** Update after boot...
03-17 08:36:32.298  4334  4619 I DeviceManagement: SessionStateController: Checking invariants...
03-17 08:36:32.308  4235  4293 V SmsReceiverService: updateNotificationAndShortcutStatus: 
03-17 08:36:32.308  1882  4620 I GoogleHttpClient: GMS http client unavailable, use old client
03-17 08:36:32.308  4235  4293 D MessagingNotification: New incoming message, can't cancel notification now
03-17 08:36:32.308  4235  4293 D MessagingNotification: newMsgCnt: 0, false
03-17 08:36:32.328   921  1712 I ActivityManager: Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=4623 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
03-17 08:36:32.338   921  1720 D Process : killProcessQuiet, pid=2859
03-17 08:36:32.338   921  1720 I ActivityManager: Killing 2859:com.htc.contacts/u0a38 (adj 15): empty #17
03-17 08:36:32.338   921  1720 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
03-17 08:36:32.348  4309  4622 I ActionCombine: replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
03-17 08:36:32.378  4334  4619 I DeviceManagement: BackgroundController: Invariants are unchanged.
03-17 08:36:32.378  4334  4619 I DeviceManagement: Perf: *** Cache update - start...
03-17 08:36:32.378  4334  4619 I DeviceManagement: Perf: *** Enabled app cache update - start...
03-17 08:36:32.378  4334  4619 I DeviceManagement: EnabledAppController: *** Updating enabled app database...
03-17 08:36:32.378  4334  4619 I DeviceManagement: EnabledAppController: Enabled app scan is pending...
03-17 08:36:32.378  4334  4619 I DeviceManagement: Perf: Scan enabled apps - start...
,03-17 08:36:32.428  4594  4594 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
03-17 08:36:32.428  4334  4619 I DeviceManagement: EnabledAppBuilder: Examining 270 installed apps for DM enabled apps...
03-17 08:36:32.448  1491  2067 W asset   : Copying FileAsset 0x559e93a2a0 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
03-17 08:36:32.448  4334  4619 I DeviceManagement: EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs, versionKey=c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17, versionCode=649500100, versionName=6.5.853822
03-17 08:36:32.458   921  4355 I ActivityManager: Recipient 2859
03-17 08:36:32.468  4334  4619 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 08:36:32.478  4334  4619 I DeviceManagement: EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, versionCode=658031464, versionName=6.3.860159
03-17 08:36:32.508  1433  2172 D PhoneApp: EVENT_QUERY_MO_PACKAGES
03-17 08:36:32.508  1433  2172 D PhoneApp: -- N1 =0
03-17 08:36:32.508  1433  2172 D PhoneApp: -- N2 =0
03-17 08:36:32.508  4334  4619 I DeviceManagement: EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, versionCode=444607021, versionName=4.2.857167
03-17 08:36:32.508  1433  2172 D PhoneApp: -- N3 =0
03-17 08:36:32.518  1491  2067 I Prism.WidgetManager: onLoadItems() -
03-17 08:36:32.518  1491  2067 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@3508dd95 -
03-17 08:36:32.528  1491  2067 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
03-17 08:36:32.528  1491  2067 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
03-17 08:36:32.538  1491  1491 I Launcher: Deferring update until onResume
03-17 08:36:32.538  1491  1491 D Launcher: waitUntilResume // bindAppsAdded
03-17 08:36:32.548   921  1514 D PMS     : releaseWL(3f366c9d): PARTIAL_WAKE_LOCK  StartingAlertService_0 0x1 null
03-17 08:36:32.558  4334  4619 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
03-17 08:36:32.658  4185  4227 D MediaProvider: [update][97]#1#
03-17 08:36:32.678  1306  1345 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.htc.backup, id: 100, tag: null, isClearable: true
03-17 08:36:32.678  1306  1345 D DotMatrix: [EventService] get3rdNotificationByPkgName, com.htc.backup does not support DotMatrix
03-17 08:36:32.698  4309  4645 I htcbackup-core: CommonUtil: Scheduling Auto-Backup Promotion Notification: interval start=[2015.11.05 at 12:06:52.457 CET] interval end=[2015.11.12 at 12:06:52.457 CET]
03-17 08:36:32.708   921  1137 V AlarmManager: sending alarm PendingIntent{30bf2eff: PendingIntentRecord{19f2e4cc com.htc.backup startService}}, i=com.htc.backup.scheduleAutoBackupNotification, t=0, cnt=18, w=1447326412457, Int=604800000
03-17 08:36:32.738  4334  4619 I DeviceManagement: EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.sense.socialnetwork.facebook, versionKey=2adae5da-a4df-4cc3-b772-ea9aaa6301b2, versionCode=658011289, versionName=7.00.515351
03-17 08:36:32.738   921   921 I art     : Explicit concurrent mark sweep GC freed 30153(1670KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 4.540ms total 185.909ms
03-17 08:36:32.738  4594  4594 I LibraryLoader: Time to load native libraries: 12 ms (timestamps 5385-5397)
03-17 08:36:32.748  4594  4594 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-17 08:36:32.778   921  1514 I ActivityManager: Start proc com.htc.htccupd for broadcast com.htc.htccupd/.HtcCupdReceiver: pid=4655 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a
03-17 08:36:32.778  4594  4594 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1ef50413}
03-17 08:36:32.778  4594  4594 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-17 08:36:32.778  1212  1212 I RemoteViews: setHTCTheme(com.htc.backup,true,33751145)
03-17 08:36:32.778   921  1514 I ActivityManager: Killing 3933:com.htc.widget.hmsproc2/u0a40 (adj 15): empty #17
03-17 08:36:32.778   921  1514 D Process : killProcessQuiet, pid=3933
03-17 08:36:32.778   921  1514 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
03-17 08:36:32.788  4594  4594 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
03-17 08:36:32.808  1212  1212 I RemoteViews: apply : com.htc.backup 1 21 8 38
03-17 08:36:32.808  1212  1212 I RemoteViews: setHTCTheme(com.htc.backup,true,33751145)
03-17 08:36:32.818  4594  4594 I BrowserStartupController: Initializing chromium process, singleProcess=true
03-17 08:36:32.828  4594  4594 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-17 08:36:32.828  4594  4594 E SysUtils: ApplicationContext is null in ApplicationStatus
03-17 08:36:32.828  1212  1212 I RemoteViews: setHTCTheme(com.htc.backup,true,33751145)
03-17 08:36:32.838  1212  1212 I RemoteViews: apply : com.htc.backup 0 10 3 5
03-17 08:36:32.848  1212  1212 I RemoteViews: setHTCTheme(com.htc.backup,true,33751145)
03-17 08:36:32.848  4334  4619 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 08:36:32.848  1212  1212 I RemoteViews: apply : com.htc.backup 0 2 1 5
03-17 08:36:32.848  1212  1212 I RemoteViews: setHTCTheme(com.htc.backup,true,33751145)
03-17 08:36:32.848  1212  1212 I RemoteViews: apply : com.htc.backup 0 2 1 5
03-17 08:36:32.848  1212  1212 I RemoteViews: apply : com.htc.backup 1 17 24 50
03-17 08:36:32.888  4334  4619 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-17 08:36:32.888  4334  4619 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
03-17 08:36:32.898  4334  4619 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 08:36:32.898   921  1719 I ActivityManager: Recipient 3933
03-17 08:36:32.898  4594  4594 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
03-17 08:36:32.908  4594  4594 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-17 08:36:32.908  4594  4594 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-17 08:36:32.908  4594  4594 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
03-17 08:36:32.908  4594  4594 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.01
03-17 08:36:32.908  4594  4594 I Adreno-EGL: Build Date: 03/09/15 Mon
03-17 08:36:32.908  4594  4594 I Adreno-EGL: Local Branch: 
03-17 08:36:32.908  4594  4594 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
03-17 08:36:32.908  4594  4594 I Adreno-EGL: Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
03-17 08:36:32.908  4594  4594 I Adreno-EGL:                  d74aa161a12b9c6fc6332151
03-17 08:36:32.918  4334  4619 I DeviceManagement: EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.identity, versionKey=887a7f5610a36712ed50f1fb1911e4b5da8368ea, versionCode=658001316, versionName=6.5.860193
03-17 08:36:32.968   921  1045 D BluetoothManagerService: Message: MESSAGE_REGISTER_ADAPTER
03-17 08:36:32.968   921  2373 W System.err: java.lang.Throwable: stack dump
03-17 08:36:32.968   921  1045 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@13cf81b8:true
03-17 08:36:32.968   921  2373 W System.err: 	at java.lang.Thread.dumpStack(Thread.java:490)
03-17 08:36:32.968   921  2373 W System.err: 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
03-17 08:36:32.968   921  2373 W System.err: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
03-17 08:36:32.968   921  2373 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
03-17 08:36:32.968  4594  4687 D BluetoothAdapter: 914685262: getState(). Returning 12
03-17 08:36:32.968  4334  4619 W ResourceType: ResTable_typeSpec entry count inconsistent: given 2, previously 1426
03-17 08:36:32.988   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 5
03-17 08:36:32.998   921   921 E WifiTrafficPoller:  packet count Tx=58 Rx=116
03-17 08:36:32.998   921   921 E WifiTrafficPoller: notifying of data activity 1
03-17 08:36:32.998  1212  1212 D WIFI_ICON: WifiActivity: 1
03-17 08:36:32.998  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
03-17 08:36:32.998  4334  4619 I DeviceManagement: EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.pns, versionKey=55580870d4ecef7adc0bfac442bc01d880550489, versionCode=148001224, versionName=1.2.853019
03-17 08:36:33.008  1306  1715 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.htc.backup, id: 100, tag: null, isClearable: true
03-17 08:36:33.008  1306  1715 D DotMatrix: [EventService] get3rdNotificationByPkgName, com.htc.backup does not support DotMatrix
03-17 08:36:33.008  1212  1212 I RemoteViews: reapply : com.htc.backup 2 38
03-17 08:36:33.008  1212  1212 I RemoteViews: setHTCTheme(com.htc.backup,true,33751145)
03-17 08:36:33.008  1212  1212 I RemoteViews: apply : com.htc.backup 0 2 0 5
03-17 08:36:33.008  1212  1212 I RemoteViews: setHTCTheme(com.htc.backup,true,33751145)
03-17 08:36:33.008  1212  1212 I RemoteViews: apply : com.htc.backup 0 2 0 5
03-17 08:36:33.018  1212  1212 I RemoteViews: setHTCTheme(com.htc.backup,true,33751145)
03-17 08:36:33.018  1212  1212 I RemoteViews: apply : com.htc.backup 0 2 0 5
03-17 08:36:33.018  1212  1212 I RemoteViews: reapply : com.htc.backup 10 50
03-17 08:36:33.058  1433  1433 D ResetNotifyBootCompleteReceiver: userSerialNumber = 0
03-17 08:36:33.058  1433  1433 D ResetNotifyBootCompleteReceiver: Receive bootcomplete intent
03-17 08:36:33.058  1433  1433 D ResetNotifyBootCompleteReceiver: isOwnerUser = true
03-17 08:36:33.078   921   951 I ActivityManager: Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.weekly.AlarmReceiver: pid=4698 uid=10155 gids={50155, 9997, 3003, 1028, 1015} abi=arm64-v8a
03-17 08:36:33.078  4334  4619 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 08:36:33.078  4655  4694 I HtcCupdXmlParser: java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdalarmgroup.so: open failed: ENOENT (No such file or directory)
03-17 08:36:33.088  4655  4694 D ActivityThread: Loading provider com.htc.htccupd_settings: com.htc.providers.settings.HtcCupdProvider
03-17 08:36:33.088  4594  4594 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-17 08:36:33.108  4594  4594 W AwContents: onDetachedFromWindow called when already detached. Ignoring
03-17 08:36:33.108  4334  4619 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 08:36:33.118  4334  4619 I DeviceManagement: EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.csrecommend, versionKey=f26b54be-e9ca-4494-ba25-56712573f3ab, versionCode=240000080, versionName=2.0.837715
03-17 08:36:33.128  4594  4594 D SystemWebViewEngine: CordovaWebView is running on device made by: HTC
03-17 08:36:33.138  4594  4594 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-17 08:36:33.138  4594  4594 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 08:36:33.148  4334  4619 W ResourcesManager: Asset path '/system/framework/com.htc.musicvismodule.jar' does not exist or contains no resources.,
,03-17 08:36:33.158  4334  4619 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 08:36:33.188  4594  4685 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-17 08:36:33.238  4334  4619 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 08:36:33.238  4594  4594 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,03-17 08:36:33.258  4334  4619 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-17 08:36:33.268  4334  4619 W ResourcesManager: Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,03-17 08:36:33.308  1433  1433 D QXDM2SD:HtcNative: JNI lib [/system/lib/libhtcqxdm2sd.so] exists: true
,03-17 08:36:33.308  4334  4619 I DeviceManagement: EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.dm, versionKey=b5b04a47-d585-4433-9a63-6f3f39989144, versionCode=250001208, versionName=2.2.848686
,03-17 08:36:33.328   921  1401 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.framework.app.HtcIntentReceiver: pid=4730 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,03-17 08:36:33.338  4334  4619 I DeviceManagement: EnabledAppBuilder: Found 8 DM enabled apps.
,03-17 08:36:33.348  4334  4619 I DeviceManagement: EnabledAppController: Nothing appears to have changed for appID=com.htc.cs
,03-17 08:36:33.348  4334  4619 I DeviceManagement: EnabledAppController: Nothing appears to have changed for appID=com.htc.launcher,
,03-17 08:36:33.358  4334  4619 I DeviceManagement: EnabledAppController: Nothing appears to have changed for appID=com.htc.backup
,03-17 08:36:33.358  4334  4619 I DeviceManagement: EnabledAppController: Nothing appears to have changed for appID=com.htc.sense.socialnetwork.facebook
,03-17 08:36:33.368  4334  4619 I DeviceManagement: EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.identity
,03-17 08:36:33.368  4334  4619 I DeviceManagement: EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.pns,
,03-17 08:36:33.428  4185  4227 D MediaScanner:  prescan time: 1559ms
03-17 08:36:33.428  4185  4227 D MediaScanner:     scan time: 2488ms
03-17 08:36:33.428  4185  4227 D MediaScanner: postscan time: 30ms
03-17 08:36:33.428  4185  4227 D MediaScanner:    total time: 4077ms
,03-17 08:36:33.428  4185  4227 D MediaScanner: -----------------------------------------------------------------
03-17 08:36:33.428  4185  4227 D MediaScanner: firstscan(media) time: 1633ms
03-17 08:36:33.428  4185  4227 D MediaScanner: secondscan(non-media) time: 855ms
03-17 08:36:33.428  4185  4227 D MediaScanner:  [Update]   Image: 0 Video: 0 Audio: 0 Other: 0
03-17 08:36:33.428  4185  4227 D MediaScanner:  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
03-17 08:36:33.428  4185  4227 D MediaScanner:  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
03-17 08:36:33.428  4185  4227 D MediaScanner:  [Total]    File(Image+Video+Audio+Others) in database : 1549
03-17 08:36:33.428  4594  4594 I InputMethodManager: [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@2479847b, mServedView=org.apache.cordova.engine.SystemWebView{3d1298 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@2f3b6af1
03-17 08:36:33.428  4334  4619 I DeviceManagement: EnabledAppController: Nothing appears to have changed for appID=com.htc.csrecommend
,03-17 08:36:33.438   921  1515 I InputMethodManagerService: Disable input method client, pid=1491
03-17 08:36:33.438   921  1515 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
03-17 08:36:33.438  4334  4619 I DeviceManagement: EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.dm
,03-17 08:36:33.438  4334  4619 I DeviceManagement: Perf: Scan enabled apps - complete: 1061 ms
,03-17 08:36:33.438  4334  4619 I DeviceManagement: Perf: *** Enabled app cache update - complete: 1062 ms
03-17 08:36:33.438  4334  4619 I DeviceManagement: Perf: *** Config cache update - start...
,03-17 08:36:33.448  4334  4619 I DeviceManagement: ConfigCacheController: *** Updating config cache...
03-17 08:36:33.448  4334  4619 I DeviceManagement: ConfigCacheController: *** Updating stale config cache entries...
,03-17 08:36:33.448   921  1515 I InputMethodManagerService: Enable input method client, pid=4594
,03-17 08:36:33.448  1212  1212 I PhoneStatusBar: setImeWindowStatus(false,false)
,03-17 08:36:33.448   921  1046 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s263ms
03-17 08:36:33.448  4334  4619 I DeviceManagement: ConfigCacheController: *** Update config cache: updating 0 entries...
,03-17 08:36:33.448  4334  4619 I DeviceManagement: ConfigCacheController: No changes need to be broadcasted.
,03-17 08:36:33.458  4334  4619 I DeviceManagement: AlarmController: Scheduling TTL alarm for: 2016.03.17 at 09:37:58.969 CET (due to: com.htc.cs)
,03-17 08:36:33.468   921  1719 D PMS     : releaseWL(ef9a56e): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null,
03-17 08:36:33.468   921  2373 I PackageManager:  setEnabledSetting(), pkgName=com.htc.cs.dm, clsName=com.htc.cs.dm.receiver.NetworkChangeReceiver, state=2, flag=1, pid=4334, uid=10099, userID:0
03-17 08:36:33.468  4334  4619 I DeviceManagement: Perf: *** Config cache update - complete: 23 ms
,03-17 08:36:33.468  4334  4619 I DeviceManagement: Perf: *** Cache update - complete: 1088 ms
03-17 08:36:33.468  4334  4619 I DeviceManagement: WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.BootCompletedWorkflow@1b6d21b8]
03-17 08:36:33.468  4730  4730 D Fingerprint/ HtcFingerPrintQuickLaunchProvider: -onCreate()
03-17 08:36:33.468  4334  4334 I DeviceManagement: WorkflowService: Stopping workflow service
,03-17 08:36:33.498  4730  4730 V Settings:HtcSettingsApplication: [4730/4730] onCreate()
,03-17 08:36:33.518  4730  4730 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.framework.app.HtcIntentReceiver.onReceive:54 android.app.ActivityThread.handleReceiver:2712 ,
03-17 08:36:33.518  1378  1378 W XT9_C   : [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
03-17 08:36:33.518  1378  1378 I XT9_C   : [T9_ReleaseBuffer] Reset LDB#0
03-17 08:36:33.518  1378  1378 I XT9_C   : [T9_ReleaseBuffer] Reset LDB#1
03-17 08:36:33.518  1378  1378 D XT9_C   : [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
03-17 08:36:33.518  4594  4594 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 4594
,03-17 08:36:33.528  4185  4227 D MediaProvider: [delete][103],
03-17 08:36:33.528  4185  4227 D MediaProvider: [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
,03-17 08:36:33.538  4185  4227 D MediaProvider: [recoverParentNodes] - 0
,03-17 08:36:33.538   921  1716 I ActivityManager: Start proc com.android.settings:remote for service com.android.settings/.framework.app.HtcIntentService: pid=4754 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
03-17 08:36:33.538  4185  4227 D MediaProvider: [update][6]
03-17 08:36:33.538  4185  4227 D MediaScannerServiceEx: [scan] Recover Parent Node is finished!
03-17 08:36:33.538   921  1514 I ActivityManager: Killing 3954:com.htc.mobiledata:remote/u0a46 (adj 15): empty #17
03-17 08:36:33.538  4185  4227 D MediaScannerServiceEx: [updateImage]+
03-17 08:36:33.538   921  1514 D Process : killProcessQuiet, pid=3954
03-17 08:36:33.538   921  1514 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-17 08:36:33.548  4655  4694 I HtcCupdXmlParser: java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdepsalarmqueuinglist.so: open failed: ENOENT (No such file or directory)
03-17 08:36:33.558  4185  4227 D MediaScannerServiceEx: [updateImage]-0
,03-17 08:36:33.668   921  1712 I ActivityManager: Recipient 3954,
,03-17 08:36:33.688  4594  4594 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode,
,03-17 08:36:33.758   921   921 I AlarmManager: [AlarmQueuing] AlarmListUpdateReceiver onReceive: com.htc.intent.action.CUPD_CONF_CHANGED,
,03-17 08:36:33.758   921   921 I AlarmManager: [AlarmQueuing] post alarm-list load task
03-17 08:36:33.758   921   921 I AlarmManager: [AlarmQueuing] init alarm queuing list
,03-17 08:36:33.768  4730  4730 D TetherSettings: CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
03-17 08:36:33.768  4730  4730 D         : Cust_ConnectToPC   : Internet_Sharing>true
,03-17 08:36:33.768  4730  4730 D         : Cust_ConnectToPC   : Modem_Link>false
03-17 08:36:33.768  4730  4730 D         : Cust_ConnectToPC   : spcsc>false
03-17 08:36:33.768  4730  4730 D         : Cust_ConnectToPC   : IPT>true
03-17 08:36:33.768  4730  4730 D         : Cust_ConnectToPC   : Singel_USB>false
,03-17 08:36:33.788  4730  4730 W Settings: Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-17 08:36:33.828   921  1720 D PMS     : releaseWL(33df14e3): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null,
03-17 08:36:33.828  4185  4227 D MediaScannerServiceEx: [2] scan finished
03-17 08:36:33.838  4185  4227 D MediaProviderUtils: calcVolumeId: /storage/emulated/0
03-17 08:36:33.838  4185  4227 D MediaProviderUtils: calcVolumeId: /storage/ext_sd
03-17 08:36:33.838  4185  4227 D MediaProviderUtils: calcVolumeId: /storage/usb
03-17 08:36:33.838  4185  4227 D MediaScannerServiceEx: [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #1
03-17 08:36:33.838  4185  4227 W MediaScannerServiceEx: Process mounted intent for unmounted storage: /storage/ext_sd
,03-17 08:36:33.858   921   921 I ActivityManager: Start proc com.htc.providers.settings:remote for content provider com.htc.providers.settings/.HtcCupdProvider: pid=4780 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a
,03-17 08:36:33.868   921  1514 D Process : killProcessQuiet, pid=3977
,03-17 08:36:33.868   921  1514 I ActivityManager: Killing 3977:com.htc.music:mediaplaybackservice/u0a48 (adj 15): empty #17
03-17 08:36:33.868  4185  4227 D MediaScannerServiceEx: [disAliveExtStorageRows]+131073
03-17 08:36:33.868   921  1514 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
03-17 08:36:33.868  4730  4730 E SmartNS_Utility: hasRemovableStorageSlot: true
03-17 08:36:33.868  4730  4730 D SmartNS_Utility: [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
03-17 08:36:33.868  4730  4730 D SmartNS_NSReceiver: onReceive : android.intent.action.BOOT_COMPLETED hasTethered:false isNSOpening:false
03-17 08:36:33.878  4754  4754 V Settings:HtcSettingsApplication: [4754/4754] onCreate()
,03-17 08:36:33.878  4730  4730 I SmartNS_Utility: setISNotification
,03-17 08:36:33.888  4730  4730 D SmartNS_Utility: usb_cable_connect = 1
,03-17 08:36:33.888  4730  4730 D SmartNS_Utility: usb_denied = 0
,03-17 08:36:33.888  4730  4730 I SmartNS_PSService: usb notificaiton:true
,03-17 08:36:33.888   921  2373 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false
,03-17 08:36:33.898  4594  4752 D jxcore_app_log: JniHelper::setJavaVM(0xab33a8f8), pthread_self() = -1402668032
,03-17 08:36:33.908  4594  4752 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-17 08:36:33.908  4594  4752 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-17 08:36:33.908  4594  4752 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-17 08:36:33.908  4594  4752 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-17 08:36:33.908  4594  4752 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-17 08:36:33.908  4594  4752 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9f0826b added. We now have 1 listener(s)
03-17 08:36:33.908  4185  4227 D MediaProvider: [sendStorageAddedIfNeed]: /storage/ext_sd : unmounted
,03-17 08:36:33.908  4185  4227 D MediaProvider: [update][26]#1#
,03-17 08:36:33.938  4185  4227 D MediaProvider: [update][29]#0#
,03-17 08:36:33.938  4185  4227 D MediaScannerServiceEx: [disAliveExtStorageRows]--1, 0
03-17 08:36:33.948   921  1148 E WifiStateMachine: handleMessage: E msg.what=131155
03-17 08:36:33.948   921  1148 E WifiStateMachine: processMsg: ConnectedState
03-17 08:36:33.948   921  1148 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-54 f=2457 sc=60 link=150 tx=3.4, 0.0, 0.0  rx=15.6 bcn=0 [on:0 tx:0 rx:0 period:2959] from screen [on:0 period:-2088686683] gl hn u24 rssi=-49 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
03-17 08:36:33.948   921  1148 E WifiStateMachine: processMsg: L2ConnectedState
03-17 08:36:33.948   921  1148 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-54 f=2457 sc=60 link=150 tx=3.4, 0.0, 0.0  rx=15.6 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-2088686681] gl hn u24 rssi=-49 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
03-17 08:36:33.948   921  1148 E WifiStateMachine:  get link layer stats 0
03-17 08:36:33.948   921  1148 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
03-17 08:36:33.948  1346  1346 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
,03-17 08:36:33.968  1346  1346 I wpa_supplicant: environment dirty rate=0 [0][0][0],
03-17 08:36:33.968   921  1148 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 150
03-17 08:36:33.968   921  1148 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-55 linkspeed=150
03-17 08:36:33.968   921  1148 E WifiConfigStore: updateConfiguration freq=2457 BSSID=f4:f2:6d:22:99:3e RSSI=-54 "NG700"WPA_PSK
,03-17 08:36:33.968   921  1148 E WifiStateMachine: calculateWifiScore freq=2457 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=1.69 txretriesrate=0.00 rxrate=9.82 userTriggerdPenalty0
03-17 08:36:33.968   921  1148 E WifiStateMachine:  good link -> stuck count =0
03-17 08:36:33.968   921  1148 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 56
03-17 08:36:33.968   921  1148 E WifiStateMachine:  isHighRSSI       ---> score=61
,03-17 08:36:33.988   921  1720 I ActivityManager: Recipient 3977
,03-17 08:36:34.028  1491  2067 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
03-17 08:36:34.028  1491  2067 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@3508dd95 +
03-17 08:36:34.028  1491  2067 I Prism.WidgetManager: onLoadItems() +
,03-17 08:36:34.078  4730  4730 I ActionCombine: replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
03-17 08:36:34.088   921  1148 E WifiStateMachine: handleMessage: X
,03-17 08:36:34.088   921  1718 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
03-17 08:36:34.088  1212  1212 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3
03-17 08:36:34.088  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,03-17 08:36:34.098  4185  4227 D MediaProviderUtils: calcVolumeId: /storage/emulated/0
03-17 08:36:34.098  4185  4227 D MediaProviderUtils: calcVolumeId: /storage/ext_sd
,03-17 08:36:34.098  4185  4227 D MediaProviderUtils: calcVolumeId: /storage/usb
03-17 08:36:34.098  4185  4227 D MediaScannerServiceEx: [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #2
03-17 08:36:34.098  4185  4227 W MediaScannerServiceEx: Process mounted intent for unmounted storage: /storage/usb
,03-17 08:36:34.098  4185  4227 D MediaScannerServiceEx: [disAliveExtStorageRows]+196609
,03-17 08:36:34.098  4594  4752 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 90:E7:C4:F6:69:77
03-17 08:36:34.098  4730  4730 D SmartNS_Utility: usb_cable_connect = 1
,03-17 08:36:34.098  4730  4730 D SmartNS_Utility: usb_denied = 0
03-17 08:36:34.098  4730  4730 I SmartNS_PSService: usb notificaiton:true
03-17 08:36:34.098   921   951 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false
,03-17 08:36:34.098  4594  4752 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"90:E7:C4:F6:69:77"}
,03-17 08:36:34.098  4594  4752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"90:E7:C4:F6:69:77"}
03-17 08:36:34.098  4594  4752 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
03-17 08:36:34.098  4594  4752 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
,03-17 08:36:34.108  4185  4227 D MediaProvider: [sendStorageAddedIfNeed]: /storage/usb : unmounted
,03-17 08:36:34.108  4594  4752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-17 08:36:34.108  4594  4752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-17 08:36:34.108  4594  4752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-17 08:36:34.108  4594  4752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 90:E7:C4:F6:69:77
03-17 08:36:34.108  4594  4752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-17 08:36:34.108  4594  4752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-17 08:36:34.108  4594  4752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-17 08:36:34.108  4594  4752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-17 08:36:34.108  4594  4752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-17 08:36:34.108  4594  4752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-17 08:36:34.108  4594  4752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c15f186 added. We now have 1 listener(s)
03-17 08:36:34.108  4594  4752 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-17 08:36:34.108  4185  4227 D MediaProvider: [update][8]#1#
03-17 08:36:34.108   921  1149 D WifiService: New client listening to asynchronous messages
03-17 08:36:34.118   921  1710 I ActivityManager: Killing 4001:com.htc.musicenhancer/u0a49 (adj 15): empty #17
03-17 08:36:34.118   921  1710 D Process : killProcessQuiet, pid=4001
03-17 08:36:34.118   921  1710 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
03-17 08:36:34.118  4594  4752 D BluetoothAdapter: 914685262: getState(). Returning 12
03-17 08:36:34.118  4594  4752 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
03-17 08:36:34.118  4594  4752 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-17 08:36:34.118  4594  4752 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-17 08:36:34.118  4594  4752 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-17 08:36:34.118  4594  4752 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
03-17 08:36:34.128  4185  4227 D MediaProvider: [update][20]#0#
03-17 08:36:34.128  4185  4227 D MediaScannerServiceEx: [disAliveExtStorageRows]--1, 0
,03-17 08:36:34.178   921  1157 I ActivityManager: Recipient 4001
,03-17 08:36:34.218  4594  4752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-17 08:36:34.218   921  1057 D PMS     : releaseHCC(325f1922): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
,03-17 08:36:34.228   921  1720 D Process : killProcessQuiet, pid=4023
03-17 08:36:34.228   921  1057 D PMS     : releaseHCC(3e723fb3): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,03-17 08:36:34.228   921  1720 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
03-17 08:36:34.228   921  1720 I ActivityManager: Killing 4023:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,03-17 08:36:34.258  1491  2067 E Prism.WidgetManager: The same lists. No need to update. skip it.,
03-17 08:36:34.258  1491  2067 I Prism.WidgetManager: onLoadItems() -
03-17 08:36:34.258  1491  2067 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@3508dd95 -
,03-17 08:36:34.348   921  1515 I ActivityManager: Recipient 4023
,03-17 08:36:34.438   921  1514 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
03-17 08:36:34.438  4594  4752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 90:E7:C4:F6:69:77
03-17 08:36:34.438  4185  4227 E MediaScannerServiceEx: [getStorageMaskIdFromPath] path is null
03-17 08:36:34.438  4185  4227 D MediaScannerServiceEx: [ServiceHandler][handleMessage] , action: null, Id: 0, path: /storage/emulated/0
,03-17 08:36:34.448  4185  4227 D MediaScannerServiceEx: [handleExternalVolume] ext storage
,03-17 08:36:34.448  4185  4227 D MediaProviderUtils: calcVolumeId: /storage/emulated/0
03-17 08:36:34.448  4185  4227 D MediaProviderUtils: calcVolumeId: /storage/ext_sd
,03-17 08:36:34.448  4185  4227 D MediaProviderUtils: calcVolumeId: /storage/usb
03-17 08:36:34.458  4185  4227 D MediaScannerServiceEx: [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
03-17 08:36:34.458  4185  4227 D MediaScannerServiceEx: [AliveExtStorageRows]+65537, 11223344
,03-17 08:36:34.458  4594  4752 D BluetoothAdapter: 914685262: getState(). Returning 12
03-17 08:36:34.458  4594  4752 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-17 08:36:34.458  4594  4752 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-17 08:36:34.458  4594  4752 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-17 08:36:34.458  4594  4752 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-17 08:36:34.458  4594  4752 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-17 08:36:34.458  4594  4752 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-17 08:36:34.458  4594  4752 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-17 08:36:34.458  4594  4752 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-17 08:36:34.458  4594  4752 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-17 08:36:34.458  4594  4752 D io.jxcore.node.ConnectivityMonitor: start: OK
03-17 08:36:34.458  4185  4227 D MediaProvider: [update][6]#0#
03-17 08:36:34.468   921   921 I AlarmManager: [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@26c17de1
03-17 08:36:34.468  4185  4227 D MediaProvider: [update][3]#0#
,03-17 08:36:34.468  4594  4594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 08:36:34.468  4594  4594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 08:36:34.478  4185  4227 D MediaProvider: [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted
03-17 08:36:34.478   921   921 I AlarmManager: [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@31c35706
03-17 08:36:34.478  4185  4227 D MtpService: [sendStorageAdded] Already send to MTP: /storage/emulated/0
03-17 08:36:34.478  4185  4227 D MediaProvider: [update][9]#1#
03-17 08:36:34.478  4185  4227 D MediaScannerServiceEx: [AliveExtStorageRows]-0, 0
,03-17 08:36:34.478   921  1515 D PMS     : acquireWL(95411c7): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 4185 10017 null
,03-17 08:36:34.498   921   921 I AlarmManager: [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@1d2063f4
,03-17 08:36:34.498   921   921 I AlarmManager: [AlarmQueuing] add queuing package: com.google.android.apps.maps,
03-17 08:36:34.498   921   921 I AlarmManager: [AlarmQueuing] add queuing package: com.google.android.gsf
03-17 08:36:34.498   921   921 I AlarmManager: [AlarmQueuing] add queuing package: com.google.android.location
03-17 08:36:34.498   921   921 I AlarmManager: [AlarmQueuing] add queuing package: com.htc.CruiserPwrExpert
03-17 08:36:34.498   921   921 I AlarmManager: [AlarmQueuing] add queuing package: com.facebook.katana
03-17 08:36:34.498   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 5
03-17 08:36:34.498   921   921 I AlarmManager: [AlarmQueuing] add queuing package: jp.naver.line.android
03-17 08:36:34.498   921   921 E WifiTrafficPoller:  packet count Tx=58 Rx=119
03-17 08:36:34.498   921   921 I AlarmManager: [AlarmQueuing] add queuing package: com.viber.voip
03-17 08:36:34.498   921  1166 D WifiWatchdogStateMachine: RSSI current: 3 new: -55, 3
03-17 08:36:34.498   921   921 I AlarmManager: [AlarmQueuing] add queuing package: com.tencent.mm
03-17 08:36:34.498   921   921 I AlarmManager: [AlarmQueuing] add queuing package: com.htc.android.mail
03-17 08:36:34.498   921   921 I AlarmManager: [AlarmQueuing] add queuing package: com.sina.weibo
03-17 08:36:34.498   921   921 I AlarmManager: [AlarmQueuing] add queuing package: com.facebook.orca
03-17 08:36:34.498   921   921 I AlarmManager: [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.intent.action.GCM_RECONNECT
03-17 08:36:34.498   921   921 I AlarmManager: [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.gms.nlp.ALARM_WAKEUP_LOCATOR
03-17 08:36:34.498   921   921 I AlarmManager: [AlarmQueuing] Adding target to EPS screen off list: package=android, action=android.appwidget.action.APPWIDGET_UPDATE
03-17 08:36:34.508   921   921 E WifiTrafficPoller: ADD_CLIENT: 6
,03-17 08:36:34.508  4185  4227 D MediaScanner: =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1
03-17 08:36:34.518  4594  4594 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
03-17 08:36:34.538   921   921 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
,03-17 08:36:34.568   921   921 I ActivityManager: Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=4805 uid=9987 gids={49987, 9997} abi=arm64-v8a,
03-17 08:36:34.578   921   921 D Process : killProcessQuiet, pid=4055
03-17 08:36:34.578   921   921 I ActivityManager: Killing 4055:com.htc.HTCSpeaker/u0a54 (adj 15): empty #17
03-17 08:36:34.578   921   921 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,03-17 08:36:34.658   921  1515 I ActivityManager: Recipient 4055
,03-17 08:36:34.698  1306  1715 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
03-17 08:36:34.698  1212  1212 I RemoteViews: reapply : com.android.settings 3 36
,03-17 08:36:34.698  1306  1715 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,03-17 08:36:34.708   921   921 D SmartDim: Init customizeScreenOffDelayClass error
,03-17 08:36:34.718  1212  1212 I RemoteViews: reapply : com.android.settings 1 36
,03-17 08:36:34.718   921  1021 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.htc.cover.closed flg=0x10 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_DEFAULT due to registered receiver BroadcastFilter{1a4840de u0 ReceiverList{32f30819 921 system/1000/u0 local:6d9cb60}},
,03-17 08:36:34.718   921  4827 I SensorManager: registerListenerImpl: listener = com.htc.smartdim.sensor_eye@2aaddd92, sensor = {Sensor name="Accelerometer Sensor", vendor="hTC Corp.", version=1, type=1, maxRange=39.2266, resolution=0.01, power=0.17, minDelay=10000}, delay = 66667, handler = null
03-17 08:36:34.718   921  4827 W SensorService: Following SensorService logs are not warning, just make sure they are printed
03-17 08:36:34.718   921  4827 W SensorService: enable: get sensor name = Accelerometer Sensor
,03-17 08:36:34.718   921  4827 W SensorService: pid=921, uid=1000
,03-17 08:36:34.718   921  4827 W SensorService: Active sensors: size = 3
03-17 08:36:34.718   921  4827 W SensorService: Accelerometer Sensor (handle=0x00000000, connections=2)
03-17 08:36:34.718   921  4827 W SensorService: CM32181 Light sensor (handle=0x00000003, connections=1)
03-17 08:36:34.718   921  4827 W SensorService: Significant Motion (handle=0x0000000d, connections=1)
03-17 08:36:34.718   921  4827 W SensorService: SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@2aaddd92, eanble = 1, strlen(mName) = 36
03-17 08:36:34.718   921  4827 W SensorService: Active Listeners: mActiveListeners.size() = 3
03-17 08:36:34.718   921  4827 W SensorService: Listener[0] = com.android.server.display.AutomaticBrightnessController$1@1669982a
03-17 08:36:34.718   921  4827 W SensorService: Listener[1] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@33cfa620
,03-17 08:36:34.718   921  4827 W SensorService: Listener[2] = com.htc.smartdim.sensor_eye@2aaddd92
03-17 08:36:34.718   921  4827 W SensorService: void android::SensorService::listenerSensor(const char*, int32_t)--:
03-17 08:36:34.718   921  4827 I SensorManager: registerListenerImpl: listener = com.htc.smartdim.sensor_eye@2aaddd92, sensor = {Sensor name="CM36686 Proximity sensor", vendor="Capella Microsystems", version=1, type=8, maxRange=9.0, resolution=9.0, power=0.18, minDelay=0}, delay = 66667, handler = null
03-17 08:36:34.718   921  4827 W SensorService: Following SensorService logs are not warning, just make sure they are printed
03-17 08:36:34.718   921  4827 W SensorService: enable: get sensor name = CM36686 Proximity sensor
03-17 08:36:34.728   921  4827 W SensorService: pid=921, uid=1000
03-17 08:36:34.728   921  4827 W SensorService: Active sensors: size = 4
03-17 08:36:34.728   921  4827 W SensorService: Accelerometer Sensor (handle=0x00000000, connections=2)
03-17 08:36:34.728   921  4827 W SensorService: CM32181 Light sensor (handle=0x00000003, connections=1)
03-17 08:36:34.728   921  4827 W SensorService: CM36686 Proximity sensor (handle=0x00000004, connections=1)
03-17 08:36:34.728   921  4827 W SensorService: Significant Motion (handle=0x0000000d, connections=1)
03-17 08:36:34.728   921  4827 W SensorService: SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@2aaddd92, eanble = 1, strlen(mName) = 36
03-17 08:36:34.728   921  4827 W SensorService: Active Listeners: mActiveListeners.size() = 3
03-17 08:36:34.728   921  4827 W SensorService: Listener[0] = com.android.server.display.AutomaticBrightnessController$1@1669982a
03-17 08:36:34.728   921  4827 W SensorService: Listener[1] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@33cfa620
03-17 08:36:34.728   921  4827 W SensorService: Listener[2] = com.htc.smartdim.sensor_eye@2aaddd92
03-17 08:36:34.728   921  4827 W SensorService: void android::SensorService::listenerSensor(const char*, int32_t)--:
,03-17 08:36:34.748   921  1515 I ActivityManager: Start proc com.android.smith for broadcast com.android.smith/.BootCompleteReceiver: pid=4828 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
03-17 08:36:34.748   921  1515 I ActivityManager: Killing 4094:com.htc.lmw/u0a58 (adj 15): empty #17
03-17 08:36:34.748   921  1515 D Process : killProcessQuiet, pid=4094
03-17 08:36:34.748   921  1515 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,03-17 08:36:34.788   921   921 E WifiDataStallTracker: DATA_MONITOR_POLL true Token 1
,03-17 08:36:34.788   921  4849 D WifiDataStallTracker: updateDataStallInfo: mDataStallTxRxSum={txSum=44 rxSum=33} preTxRxSum={txSum=44 rxSum=33}
03-17 08:36:34.788   921  4849 D WifiDataStallTracker: updateDataStallInfo: NONE
03-17 08:36:34.788   921  4849 D WifiDataStallTracker: onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5,
,03-17 08:36:34.838   921   951 I ActivityManager: Recipient 4094
,03-17 08:36:34.978   921  1515 D Process : killProcessQuiet, pid=4124
03-17 08:36:34.978   921  1515 I ActivityManager: Killing 4124:com.android.managedprovisioning/u0a63 (adj 15): empty #17
03-17 08:36:34.988   921  1515 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-17 08:36:34.988   921   921 I SensorManager: dispatchSensorEvent: Proximity = 9.0, mListener = com.htc.smartdim.sensor_eye@2aaddd92
,03-17 08:36:35.088  4594  4804 W jxcore-log: Initializing JXcore engine,
03-17 08:36:35.088  4594  4804 W jxcore-log: JXcore engine is ready
,03-17 08:36:35.118   921  1720 I ActivityManager: Recipient 4124
,03-17 08:36:35.148  4594  4804 W jxcore-log: Starting JXcore engine
,03-17 08:36:35.228   921  1401 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4850 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a,
03-17 08:36:35.238   921  1401 D Process : killProcessQuiet, pid=4272
03-17 08:36:35.238   921  1401 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
03-17 08:36:35.238   921  1401 I ActivityManager: Killing 4272:com.htc.cs.pns/u0a71 (adj 15): empty #17
,03-17 08:36:35.248  4594  4804 W jxcore-log: Platform android,
03-17 08:36:35.248  4594  4804 W jxcore-log: 
03-17 08:36:35.248  4594  4804 W jxcore-log: Process ARCH arm
03-17 08:36:35.248  4594  4804 W jxcore-log: 
,03-17 08:36:35.298   921  1712 I ActivityManager: Recipient 4272
,03-17 08:36:35.378  4185  4227 D MediaScanner:  prescan time: 485ms
,03-17 08:36:35.378  4185  4227 D MediaScanner:     scan time: 384ms
03-17 08:36:35.378  4185  4227 D MediaScanner: postscan time: 1ms
,03-17 08:36:35.378  4185  4227 D MediaScanner:    total time: 870ms
03-17 08:36:35.378  4185  4227 D MediaScanner: -----------------------------------------------------------------
03-17 08:36:35.378  4185  4227 D MediaScanner: firstscan(media) time: 221ms
03-17 08:36:35.378  4185  4227 D MediaScanner: secondscan(non-media) time: 163ms
03-17 08:36:35.378  4185  4227 D MediaScanner:  [Update]   Image: 0 Video: 0 Audio: 0 Other: 0
03-17 08:36:35.378  4185  4227 D MediaScanner:  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
03-17 08:36:35.378  4185  4227 D MediaScanner:  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
03-17 08:36:35.378  4185  4227 D MediaScanner:  [Total]    File(Image+Video+Audio+Others) in database : 1549
,03-17 08:36:35.408  4185  4227 D MediaProvider: [delete][27]
,03-17 08:36:35.408  4185  4227 D MediaProvider: [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
03-17 08:36:35.408  4185  4227 D MediaProvider: [recoverParentNodes] - 0,
03-17 08:36:35.408  4185  4227 D MediaProvider: [update][3]
03-17 08:36:35.408  4185  4227 D MediaScannerServiceEx: [scan] Recover Parent Node is finished!
03-17 08:36:35.408  4185  4227 D MediaScannerServiceEx: [updateImage]+
,03-17 08:36:35.418  4185  4227 D MediaScannerServiceEx: [updateImage]-0
,03-17 08:36:35.418   921   951 D PMS     : releaseWL(95411c7): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
,03-17 08:36:35.418  4185  4227 D MediaScannerServiceEx: [3] scan finished
03-17 08:36:35.418  4185  4227 D MediaProviderUtils: calcVolumeId: /storage/emulated/0
03-17 08:36:35.418  4185  4227 D MediaProviderUtils: calcVolumeId: /storage/ext_sd
03-17 08:36:35.418  4185  4227 D MediaProviderUtils: calcVolumeId: /storage/usb
03-17 08:36:35.418  4185  4227 D MediaScannerServiceEx: [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #1
03-17 08:36:35.418  4185  4227 W MediaScannerServiceEx: Process mounted intent for unmounted storage: /storage/ext_sd,
03-17 08:36:35.418  4185  4227 D MediaScannerServiceEx: [disAliveExtStorageRows]+131073
,03-17 08:36:35.428  4594  4804 I jxcore-log: JXcore Cordova bridge is ready!
03-17 08:36:35.428  4594  4804 I jxcore-log: 
03-17 08:36:35.428  4594  4804 W jxcore-log: JXcore engine is started
,03-17 08:36:35.428  4594  4752 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-17 08:36:35.438  4594  4594 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-17 08:36:35.468  4185  4227 D MediaProvider: [sendStorageAddedIfNeed]: /storage/ext_sd : unmounted
,03-17 08:36:35.468  4185  4227 D MediaProvider: [update][47]#1#,
,03-17 08:36:35.488  4185  4227 D MediaProvider: [update][18]#0#
03-17 08:36:35.488  4185  4227 D MediaScannerServiceEx: [disAliveExtStorageRows]--1, 0
,03-17 08:36:35.488  4185  4227 D MediaProviderUtils: calcVolumeId: /storage/emulated/0
03-17 08:36:35.488  4185  4227 D MediaProviderUtils: calcVolumeId: /storage/ext_sd
,03-17 08:36:35.488  4185  4227 D MediaProviderUtils: calcVolumeId: /storage/usb
03-17 08:36:35.488  4185  4227 D MediaScannerServiceEx: [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #2
03-17 08:36:35.488  4185  4227 W MediaScannerServiceEx: Process mounted intent for unmounted storage: /storage/usb,
03-17 08:36:35.498  4185  4227 D MediaScannerServiceEx: [disAliveExtStorageRows]+196609
,03-17 08:36:35.498   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 6
,03-17 08:36:35.498   921   921 E WifiTrafficPoller:  packet count Tx=58 Rx=120
,03-17 08:36:35.508  4185  4227 D MediaProvider: [sendStorageAddedIfNeed]: /storage/usb : unmounted,
03-17 08:36:35.508  4185  4227 D MediaProvider: [update][14]#1#
,03-17 08:36:35.528  4185  4227 D MediaProvider: [update][20]#0#
,03-17 08:36:35.528  4185  4227 D MediaScannerServiceEx: [disAliveExtStorageRows]--1, 0
,03-17 08:36:35.538   921   950 I PackageManager:  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4850, uid=10072, userID:0
,03-17 08:36:35.548  4850  4850 W global  : [apache-http] Connection GC has been deprecated!,
,03-17 08:36:35.568  4850  4850 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,03-17 08:36:35.578  4850  4850 W global  : [apache-http] Connection GC has been deprecated!
,03-17 08:36:35.638  1433  1703 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC >>,
,03-17 08:36:35.638  1433  1703 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC <<
,03-17 08:36:35.658  4850  4850 W global  : [apache-http] Connection GC has been deprecated!
,03-17 08:36:35.678  4850  4850 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.,
,03-17 08:36:35.858   921  1515 I art     : Explicit concurrent mark sweep GC freed 20084(1040KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 16MB/24MB, paused 1.411ms total 136.557ms,
,03-17 08:36:35.868   921  1515 I ActivityManager: Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=4887 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,03-17 08:36:35.898  4850  4850 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-17 08:36:35.898  4887  4887 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-17 08:36:35.898  4887  4887 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
03-17 08:36:35.898  4850  4850 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-17 08:36:35.918   921  1157 I PackageManager:  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4850, uid=10072, userID:0
,03-17 08:36:35.918  4887  4887 I MultiDex: VM with version 2.1.0 has multidex support
,03-17 08:36:35.918  4887  4887 I MultiDex: install
03-17 08:36:35.918  4887  4887 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-17 08:36:35.948  4887  4887 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-17 08:36:35.948  4850  4874 D Volley  : [439] DiskBasedCache.clear: Cache cleared.
03-17 08:36:35.948  4850  4880 D Volley  : [445] DiskBasedCache.clear: Cache cleared.
03-17 08:36:35.948   921  1514 I ActivityManager: Killing 4358:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
03-17 08:36:35.948   921  1514 D Process : killProcessQuiet, pid=4358
,03-17 08:36:35.948   921  1514 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 ,
,03-17 08:36:35.978  4887  4887 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
03-17 08:36:35.978  4887  4887 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3c7acb3f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-17 08:36:35.988  4887  4887 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
03-17 08:36:35.998   921  1721 I ActivityManager: Recipient 4358
,03-17 08:36:36.008  4850  4850 D Finsky  : [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
03-17 08:36:36.008  4850  4850 D Finsky  : [1] 2.run: Finished loading 1 libraries.
,03-17 08:36:36.018  4850  4850 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,03-17 08:36:36.068  4850  4850 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,03-17 08:36:36.078  1882  1882 V GLSUser : [LoginAccountsChangedWakefulBroadcastReceiver] recieved broadcast intent with action: android.intent.action.BOOT_COMPLETED,
,03-17 08:36:36.088   921   950 D PMS     : acquireWL(31392989): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 1882 10024 null
,03-17 08:36:36.098  4407  4407 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) },
,03-17 08:36:36.118   921  1710 D PMS     : releaseWL(31392989): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 null
,03-17 08:36:36.138  1882  1882 D PersistentNotificationBroadcastReceiver: Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,03-17 08:36:36.218  4407  4407 W InstanceID/Rpc: Found 10024,
,03-17 08:36:36.288   921  1515 D Process : killProcessQuiet, pid=4384
,03-17 08:36:36.288   921  1515 I ActivityManager: Killing 4384:com.htc.showme/u0a81 (adj 15): empty #17
03-17 08:36:36.288   921  1515 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-17 08:36:36.318  4407  4926 D FileApkUtils: Spent 18ms computing apk sha1.
,03-17 08:36:36.318  4407  4926 D FileApkUtils: Module already staged or being staged:chimera-modules/MapsModule.apk
,03-17 08:36:36.318  4407  4926 I art     : DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm64/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-dd5b1d6850a09abe29b143730d133d3d1f4c4971@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-dd5b1d6850a09abe29b143730d133d3d1f4c4971/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
,03-17 08:36:36.328  4407  4926 D DexOptUtils: Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-dd5b1d6850a09abe29b143730d133d3d1f4c4971/MapsModule.apk is already optimized. Bailing.
,03-17 08:36:36.328  4407  4926 D FileApkUtils: Keeping up-to-date module: module-dd5b1d6850a09abe29b143730d133d3d1f4c4971
,03-17 08:36:36.388   467   467 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,03-17 08:36:36.398   921   950 I ActivityManager: Recipient 4384
,03-17 08:36:36.498   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 6
,03-17 08:36:36.498   921   921 E WifiTrafficPoller:  packet count Tx=58 Rx=120
,03-17 08:36:36.498   921   921 E WifiTrafficPoller: notifying of data activity 0
03-17 08:36:36.508  1212  1212 D WIFI_ICON: WifiActivity: 0
03-17 08:36:36.508  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,03-17 08:36:36.508  4407  4926 D GmsModuleFndr: Beginning GMS chimera module scan
,03-17 08:36:36.528  4850  4850 V Finsky  : [1] GearheadStateMonitor.onReady: sIsProjecting:false
,03-17 08:36:36.528  4407  4926 W asset   : Copying FileAsset 0x559e4b6b20 (zip:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-dd5b1d6850a09abe29b143730d133d3d1f4c4971/MapsModule.apk:/resources.arsc) to buffer size 364264 to make it aligned.,
,03-17 08:36:36.558  4407  4926 D GmsModuleFndr: Module pkg com.google.android.apps.kids.familylink not installed, skipping
,03-17 08:36:36.558  4407  4926 D ChimeraCfgMgr: Beginning module configuration check
03-17 08:36:36.558  4407  4926 D ChimeraCfgMgr: Module APKs unchanged, check complete
,03-17 08:36:36.598   921  1720 D PMS     : acquireWL(b24ec54): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4407 10024 WorkSource{10024 com.google.android.gms}
,03-17 08:36:36.608   921  1401 D PMS     : acquireWL(ab0ef43): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 4407 10024 null
,03-17 08:36:36.618   921  1716 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.nearby.sharing.sharesheet.ShareActivity, state=2, flag=1, pid=1882, uid=10024, userID:0,
,03-17 08:36:36.618   921  1719 D PMS     : acquireWL(70e79c0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4407 10024 WorkSource{10024 com.google.android.gms}
,03-17 08:36:36.618   921  1716 D PMS     : releaseWL(b24ec54): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
,03-17 08:36:36.618   921  1720 D PMS     : acquireWL(14c286f9): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 4407 10024 WorkSource{10024 com.google.android.gms}
,03-17 08:36:36.628   921  2373 D PMS     : acquireWL(174171ec): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4407 10024 null
,03-17 08:36:36.628  4407  4933 D GCM     : COMPAT: Multi user not supported
,03-17 08:36:36.638  1882  4937 D GCM     : GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED,
,03-17 08:36:36.648  4407  4939 I CheckinService: Disabling old GoogleServicesFramework version
,03-17 08:36:36.648   921  1514 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$Receiver, state=2, flag=1, pid=4407, uid=10024, userID:0
,03-17 08:36:36.648   921  4355 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$TriggerReceiver, state=2, flag=1, pid=4407, uid=10024, userID:0
,03-17 08:36:36.648   921  1721 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$SecretCodeReceiver, state=2, flag=1, pid=4407, uid=10024, userID:0
,03-17 08:36:36.668  4407  4933 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,03-17 08:36:36.678  4407  4944 I CheckinService: Checking schedule, now: 1458200196682 next: 1458737016215
03-17 08:36:36.678   921  1515 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4407, uid=10024, userID:0
,03-17 08:36:36.678  4407  4944 I CheckinService: active receiver: disabled
,03-17 08:36:36.688  4407  4426 I art     : Background sticky concurrent mark sweep GC freed 3227(226KB) AllocSpace objects, 4(80KB) LOS objects, 6% free, 3MB/4MB, paused 5.188ms total 34.329ms
,03-17 08:36:36.698   921  1515 D PMS     : acquireWL(9b91c31): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 4407 10024 WorkSource{10024 com.google.android.gms}
,03-17 08:36:36.728  4407  4407 D SystemUpdateService: onCreate
,03-17 08:36:36.728  1882  1904 I art     : Explicit concurrent mark sweep GC freed 5968(328KB) AllocSpace objects, 4(80KB) LOS objects, 49% free, 4MB/8MB, paused 1.399ms total 41.452ms,
,03-17 08:36:36.728   921  1719 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivity, state=1, flag=1, pid=4407, uid=10024, userID:0
,03-17 08:36:36.728   921   951 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivityPermissionTrampoline, state=1, flag=1, pid=4407, uid=10024, userID:0
03-17 08:36:36.728   921   951 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=1, flag=1, pid=4407, uid=10024, userID:0
,03-17 08:36:36.748  4407  4407 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) },
,03-17 08:36:36.758   921  1718 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.ConnectivityReceiver, state=1, flag=1, pid=4407, uid=10024, userID:0
,03-17 08:36:36.758   921  1514 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GmsRegisteredReceiver, state=1, flag=1, pid=4407, uid=10024, userID:0
,03-17 08:36:36.758   921  2373 D PMS     : releaseWL(ab0ef43): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
03-17 08:36:36.758   921  1712 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=4407, uid=10024, userID:0
03-17 08:36:36.758   921   950 D PMS     : acquireWL(248516a2): PARTIAL_WAKE_LOCK  copresGcore_EventLoop 0x1 1810 10024 WorkSource{10024 com.google.android.gms}
03-17 08:36:36.758   921  1721 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GservicesReceiver, state=1, flag=1, pid=4407, uid=10024, userID:0
03-17 08:36:36.768   921  1710 D PMS     : releaseWL(9b91c31): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10024 com.google.android.gms}
,03-17 08:36:36.768   921  1514 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmDeviceAdminReceiver, state=1, flag=1, pid=4407, uid=10024, userID:0
03-17 08:36:36.768   921  1720 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmPhoneWearInitializer, state=1, flag=1, pid=4407, uid=10024, userID:0
03-17 08:36:36.768   921  1515 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.RetryAfterAlarmReceiver, state=1, flag=1, pid=4407, uid=10024, userID:0
,03-17 08:36:36.768  1882  1882 I ConfigService: onCreate
03-17 08:36:36.768   921   950 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.DeviceManagerApiService, state=1, flag=1, pid=4407, uid=10024, userID:0
03-17 08:36:36.768   921  1718 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.GcmReceiverService, state=1, flag=1, pid=4407, uid=10024, userID:0
03-17 08:36:36.768   921  1401 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LockscreenMessageService, state=1, flag=1, pid=4407, uid=10024, userID:0
,03-17 08:36:36.768   921  2373 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.RingService, state=1, flag=1, pid=4407, uid=10024, userID:0
,03-17 08:36:36.768   921  1716 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.SitrepService, state=1, flag=1, pid=4407, uid=10024, userID:0
03-17 08:36:36.778   921  1712 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.receiver.GoogleAccountChangeReceiver, state=1, flag=1, pid=4407, uid=10024, userID:0
03-17 08:36:36.778   921  1721 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.GcmReceiverService, state=1, flag=1, pid=4407, uid=10024, userID:0
,03-17 08:36:36.778  1810  1810 I GCoreUlr: DispatchingService.onCreate()
03-17 08:36:36.778   921  2373 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.WifiUpdateRetryTaskService, state=1, flag=1, pid=4407, uid=10024, userID:0
03-17 08:36:36.778  4407  4407 I ConfigFetchService: onStartCommand Intent { cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,03-17 08:36:36.788   921  1710 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4407, uid=10024, userID:0
,03-17 08:36:36.788  4407  4957 V AuthZen : Handling intent: android.intent.action.BOOT_COMPLETED
,03-17 08:36:36.798  4407  4957 D AuthZenEventHandler: Handling event: android.intent.action.BOOT_COMPLETED
03-17 08:36:36.798  4407  4426 I art     : Background sticky concurrent mark sweep GC freed 205(11KB) AllocSpace objects, 0(0B) LOS objects, 0% free, 4MB/4MB, paused 5.914ms total 27.490ms
,03-17 08:36:36.808  4407  4952 I SystemUpdateService: cancelUpdate (empty URL)
,03-17 08:36:36.808  4407  4952 I SystemUpdateService: active receiver: disabled
03-17 08:36:36.808   921  4355 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=4407, uid=10024, userID:0
03-17 08:36:36.808   921  1514 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=4407, uid=10024, userID:0
,03-17 08:36:36.818   921  2373 D PMS     : acquireWL(21b1008): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1810 10024 WorkSource{10024 com.google.android.gms}
,03-17 08:36:36.838  4407  4426 I art     : Background sticky concurrent mark sweep GC freed 178(11KB) AllocSpace objects, 0(0B) LOS objects, 0% free, 4MB/4MB, paused 16.761ms total 32.656ms
,03-17 08:36:36.838   921  1021 I ActivityManager: Waited long enough for: ServiceRecord{280e6396 u0 com.htc.autobot/.htcmodeclient.HtcModeService}
,03-17 08:36:36.838   921  1515 D PMS     : acquireWL(375524b4): PARTIAL_WAKE_LOCK  Icing 0x1 4407 10024 WorkSource{10024 com.google.android.gms}
,03-17 08:36:36.898   921  1718 D PMS     : releaseWL(375524b4): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,03-17 08:36:36.908  4407  4426 I art     : Background partial concurrent mark sweep GC freed 3079(264KB) AllocSpace objects, 6(120KB) LOS objects, 49% free, 4MB/8MB, paused 7.373ms total 68.788ms
03-17 08:36:36.908  4407  4957 W BaseAppContext: Using Auth Proxy for data requests.
03-17 08:36:36.908  4407  4407 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,03-17 08:36:36.928  4407  4407 I Kids    : [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
,03-17 08:36:36.928  4407  4407 I ConfigFetchService: service connected
,03-17 08:36:36.928  1810  2178 I art     : Explicit concurrent mark sweep GC freed 22350(1373KB) AllocSpace objects, 6(120KB) LOS objects, 47% free, 4MB/8MB, paused 1.568ms total 88.397ms,
03-17 08:36:36.938   921  1719 D PMS     : releaseWL(14c286f9): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 WorkSource{10024 com.google.android.gms}
03-17 08:36:36.938   921  1712 W System.err: java.lang.Throwable: stack dump
03-17 08:36:36.938   921  1712 W System.err: 	at java.lang.Thread.dumpStack(Thread.java:490)
03-17 08:36:36.938   921  1712 W System.err: 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
03-17 08:36:36.938   921  1712 W System.err: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
03-17 08:36:36.938   921  1712 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
03-17 08:36:36.938   921  1045 D BluetoothManagerService: Message: MESSAGE_REGISTER_ADAPTER
03-17 08:36:36.938   921  1045 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1f9c1695:true
,03-17 08:36:36.948  4407  4957 I GLSUser : [ChannelManager] Attempting to channel bind connection HttpClient.
,03-17 08:36:36.958   921  1718 D PMS     : releaseWL(70e79c0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms},
,03-17 08:36:36.958  4407  4957 I GLSUser : [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true,
,03-17 08:36:36.958  1810  4959 I GCoreUlr: WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,03-17 08:36:36.968  4407  4407 D SystemUpdateService: onDestroy
,03-17 08:36:36.968   921  1148 E WifiStateMachine: handleMessage: E msg.what=131155
03-17 08:36:36.968   921  1148 E WifiStateMachine: processMsg: ConnectedState
,03-17 08:36:36.968   921  1148 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2457 sc=60 link=150 tx=1.7, 0.0, 0.0  rx=9.8 bcn=0 [on:0 tx:0 rx:0 period:2886] from screen [on:0 period:-2088683660] gl hn u24 rssi=-50 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
03-17 08:36:36.968   921  1148 E WifiStateMachine: processMsg: L2ConnectedState
,03-17 08:36:36.978   921  1148 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2457 sc=60 link=150 tx=1.7, 0.0, 0.0  rx=9.8 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-2088683659] gl hn u24 rssi=-50 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
,03-17 08:36:36.978   921  1148 E WifiStateMachine:  get link layer stats 0
03-17 08:36:36.978   921  1148 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
03-17 08:36:36.978  1346  1346 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
,03-17 08:36:36.988  1346  1346 I wpa_supplicant: environment dirty rate=0 [0][0][0],
03-17 08:36:36.988   921  1401 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4974 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,03-17 08:36:36.988   921  1148 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 150
03-17 08:36:36.988   921  1148 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-52 linkspeed=150
,03-17 08:36:36.988   921  1148 E WifiConfigStore: updateConfiguration freq=2457 BSSID=f4:f2:6d:22:99:3e RSSI=-52 "NG700"WPA_PSK
03-17 08:36:36.988  1212  1212 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3
03-17 08:36:36.988   921  1148 E WifiStateMachine: calculateWifiScore freq=2457 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.84 txretriesrate=0.00 rxrate=5.41 userTriggerdPenalty0
03-17 08:36:36.988  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
03-17 08:36:36.988   921  1148 E WifiStateMachine:  good link -> stuck count =0
03-17 08:36:36.988   921  1148 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 56
03-17 08:36:36.988   921  1148 E WifiStateMachine:  isHighRSSI       ---> score=61
03-17 08:36:36.988   921  1166 D WifiWatchdogStateMachine: RSSI current: 3 new: -52, 3,
03-17 08:36:36.988   921  1148 E WifiStateMachine: handleMessage: X
,03-17 08:36:36.998  4407  4407 D ConfigFetchService: ConfigApi connection successful.
,03-17 08:36:37.018  4407  4957 I AuthZen : Fetching signing key...
,03-17 08:36:37.028   921  1720 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.location.reporting.service.LocationHistoryInjectorService, state=1, flag=1, pid=1810, uid=10024, userID:0
,03-17 08:36:37.038  4974  4974 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-17 08:36:37.038  1882  3574 I GLSActivity: [ac] getting account id
03-17 08:36:37.038  4407  4957 I AuthZen : Signing key fetched successfully!
,03-17 08:36:37.048  4407  4957 W BaseAppContext: Using Auth Proxy for data requests.,
,03-17 08:36:37.058  4407  4957 I AuthZen : Starting Enrollment...,
,03-17 08:36:37.068   921  1137 I ActivityManager: Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=4998 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
03-17 08:36:37.068   921  1137 V AlarmManager: sending alarm PendingIntent{a7f3268: PendingIntentRecord{1df45681 com.htc.mobiledata startService}}, i=com.htc.mobiledata.intent.REQUEST, t=2, cnt=1, w=59703, Int=0
,03-17 08:36:37.068  1882  3574 I GLSUser : [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,03-17 08:36:37.078  4407  4957 D AuthZen : getting auth token. Attempt 0
,03-17 08:36:37.088   439   439 I art     : Explicit concurrent mark sweep GC freed 8710(370KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 181us total 27.395ms,
,03-17 08:36:37.098   921  4355 D PMS     : releaseWL(248516a2): PARTIAL_WAKE_LOCK  copresGcore_EventLoop 0x1 WorkSource{10024 com.google.android.gms}
,03-17 08:36:37.108   439   439 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 149us total 17.327ms
03-17 08:36:37.128   439   439 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 156us total 16.662ms
03-17 08:36:37.128  3496  3571 I HtcModeClient: handler message = 4011
03-17 08:36:37.128  3496  3571 E HtcModeClient: Check connection and retry 3 times.
03-17 08:36:37.128  1882  1904 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cryptauth
03-17 08:36:37.138  1882  1904 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cryptauth without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-17 08:36:37.138  1882  1904 I GLSUser : [GLSUser] Extracting token using key: Auth
03-17 08:36:37.138  1882  1904 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
03-17 08:36:37.138  1882  1904 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-17 08:36:37.158  1810  4959 I GCoreUlr: WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
03-17 08:36:37.158   921  4355 D PMS     : acquireWL(2553bc57): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1810 10024 WorkSource{10024 com.google.android.gms}
03-17 08:36:37.168   921  1721 D PMS     : releaseWL(2553bc57): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
03-17 08:36:37.168  1810  4959 I GCoreUlr: Unbound from all location providers
03-17 08:36:37.168   921  1514 D PMS     : releaseWL(21b1008): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 WorkSource{10024 com.google.android.gms}
,03-17 08:36:37.178  4407  4957 E AuthZen : Error getting auth token
03-17 08:36:37.178  4407  4957 E AuthZen : com.google.android.gms.auth.ad: BadAuthentication
03-17 08:36:37.178  4407  4957 E AuthZen : 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-17 08:36:37.178  4407  4957 E AuthZen : 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-17 08:36:37.178  4407  4957 E AuthZen : 	at com.google.android.gms.auth.p.a(SourceFile:318)
03-17 08:36:37.178  4407  4957 E AuthZen : 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:381)
03-17 08:36:37.178  4407  4957 E AuthZen : 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:132)
03-17 08:36:37.178  4407  4957 E AuthZen : 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
03-17 08:36:37.178  4407  4957 E AuthZen : 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
03-17 08:36:37.178  4407  4957 E AuthZen : 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
03-17 08:36:37.178  4407  4957 E AuthZen : 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
03-17 08:36:37.178  4407  4957 E AuthZen : 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
03-17 08:36:37.178  4407  4957 E AuthZen : 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
03-17 08:36:37.178  4407  4957 E AuthZen : 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
03-17 08:36:37.178  4407  4957 E AuthZen : 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
03-17 08:36:37.178  4407  4957 E AuthZen : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-17 08:36:37.178  4407  4957 E AuthZen : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 08:36:37.178  4407  4957 E AuthZen : 	at android.os.Looper.loop(Looper.java:155)
03-17 08:36:37.178  4407  4957 E AuthZen : 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-17 08:36:37.178  4407  4957 E AuthZen : Failed to do enrollment for account: thalitester@gmail.com
03-17 08:36:37.178  4407  4957 E AuthZen : com.google.android.gms.auth.authzen.b.b: Failed to get a token for authzen enrollment
03-17 08:36:37.178  4407  4957 E AuthZen : 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:139)
03-17 08:36:37.178  4407  4957 E AuthZen : 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
03-17 08:36:37.178  4407  4957 E AuthZen : 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
03-17 08:36:37.178  4407  4957 E AuthZen : 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
03-17 08:36:37.178  4407  4957 E AuthZen : 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
03-17 08:36:37.178  4407  4957 E AuthZen : 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
03-17 08:36:37.178  4407  4957 E AuthZen : 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
03-17 08:36:37.178  4407  4957 E AuthZen : 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
03-17 08:36:37.178  4407  4957 E AuthZen : 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
03-17 08:36:37.178  4407  4957 E AuthZen : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-17 08:36:37.178  4407  4957 E AuthZen : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 08:36:37.178  4407  4957 E AuthZen : 	at android.os.Looper.loop(Looper.java:155)
03-17 08:36:37.178  4407  4957 E AuthZen : 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-17 08:36:37.198   921   950 I ActivityManager: Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=5025 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,03-17 08:36:37.208   921  1020 D PMS     : acquireWL(276dc6f3): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 921 1000 null
03-17 08:36:37.218   921  1020 D PMS     : acquireWL(f4defb0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 921 1000 WorkSource{10024}
03-17 08:36:37.228  1212  1616 I IntentController: receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
03-17 08:36:37.228   921  1020 D PMS     : releaseWL(276dc6f3): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
03-17 08:36:37.238  1810  1810 I GCoreUlr: DispatchingService.onDestroy()
03-17 08:36:37.238   921  1020 D PMS     : acquireWL(2c5633e5): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 921 1000 null
03-17 08:36:37.238   921  2373 D PMS     : acquireWL(2ca20eba): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1810 10024 WorkSource{10024 com.google.android.gms}
03-17 08:36:37.248   921  1020 D PMS     : releaseWL(2c5633e5): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null,
03-17 08:36:37.248   921  1514 D PMS     : releaseWL(2ca20eba): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,03-17 08:36:37.248  4407  4957 D a       : Opening database auth.proximity.permit_store...
03-17 08:36:37.248  1810  1810 I GCoreUlr: Unbound from all location providers
,03-17 08:36:37.258  4407  4957 D AuthZenTransactionCache: Initialized cache in: /data/data/com.google.android.gms/files
,03-17 08:36:37.258  4407  4957 D AuthZenTransactionCache: Clearing transaction cache
,03-17 08:36:37.268  4974  5051 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,03-17 08:36:37.268  4974  5051 I Babel_SMS: MmsConfig.loadMmsSettings
,03-17 08:36:37.288  4235  4255 D MmsCustomizationProvider: query uri: content://htc-mms-customization/mms-ua/ua_string,
,03-17 08:36:37.298  1212  1212 D PhoneStatusBar: addIcon slot=sync_active index=7 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020653 level=0 visible=true num=0 ) name=stat_sys_sync_anim0 vis=true
,03-17 08:36:37.298  4235  4255 D MmsCustomizationProvider: query uri: content://htc-mms-customization/mms-ua/ua_profile
,03-17 08:36:37.308   921  1710 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4974, uid=10112, userID:0
,03-17 08:36:37.308  4974  5051 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
03-17 08:36:37.308  4974  5051 I Babel_SMS: MmsConfig.loadFromDatabase
,03-17 08:36:37.318  4974  5051 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,03-17 08:36:37.318  4974  5051 I Babel_SMS: MmsConfig.loadFromResources
,03-17 08:36:37.318  4974  5051 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,03-17 08:36:37.318  4974  5051 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
,03-17 08:36:37.348  4998  5023 D MdScBoot: [11.1.] 30@-073607 -> 40
,03-17 08:36:37.358  4998  5023 D MdScBootUi: [11.1.2.] boot 118
,03-17 08:36:37.358  4974  4974 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,03-17 08:36:37.358  4974  4974 I Babel_Crash: startup - clean,
,03-17 08:36:37.368  4998  5058 D MdScSimSt: [11.1.2.] qry 118: 0+1 running 0
,03-17 08:36:37.378  4974  5059 I Babel   : deleted: false for 0
,03-17 08:36:37.408   921  1020 D PMS     : acquireWL(754a4e0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 921 1000 null
,03-17 08:36:37.408   921  1020 D PMS     : releaseWL(f4defb0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10024}
,03-17 08:36:37.408   921  1020 D PMS     : releaseWL(754a4e0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
03-17 08:36:37.408  1212  1616 I IntentController: receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
,03-17 08:36:37.408   921  4355 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=4974, uid=10112, userID:0
03-17 08:36:37.408   921  1718 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=4974, uid=10112, userID:0
03-17 08:36:37.418   921  1721 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=4974, uid=10112, userID:0,
03-17 08:36:37.418   921  1716 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4974, uid=10112, userID:0
03-17 08:36:37.418   921  1719 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4974, uid=10112, userID:0
,03-17 08:36:37.428   921  2373 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=4974, uid=10112, userID:0
,03-17 08:36:37.428   921  1514 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=4974, uid=10112, userID:0
03-17 08:36:37.428   921  1720 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=4974, uid=10112, userID:0
,03-17 08:36:37.428   921   950 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4974, uid=10112, userID:0
,03-17 08:36:37.428   921  1515 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4974, uid=10112, userID:0
,03-17 08:36:37.448  4974  4974 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-17 08:36:37.478  4974  4974 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,03-17 08:36:37.488  4974  4974 W Utils   : could not parse size range '64x64-1920X1080',
,03-17 08:36:37.488  4974  4974 W AudioCapabilities: Unsupported mime audio/qcelp
,03-17 08:36:37.488  4974  4974 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,03-17 08:36:37.488  4974  4974 W AudioCapabilities: Unsupported mime audio/qcelp
,03-17 08:36:37.488  4974  4974 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,03-17 08:36:37.508   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 6
,03-17 08:36:37.508   921   921 E WifiTrafficPoller:  packet count Tx=58 Rx=120
,03-17 08:36:37.508   921  4355 D Process : killProcessQuiet, pid=4429
,03-17 08:36:37.508   921  4355 I ActivityManager: Killing 4429:com.htc.feedback/u0a83 (adj 15): empty #17
03-17 08:36:37.508   921  4355 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,03-17 08:36:37.538  4974  4974 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,03-17 08:36:37.548  4974  4974 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-17 08:36:37.548  4974  4974 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-17 08:36:37.548  4974  4974 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-17 08:36:37.558  4974  4974 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-17 08:36:37.578   921  1514 I ActivityManager: Recipient 4429
,03-17 08:36:37.618   921  1401 I ActivityManager: Killing 4461:com.htc.updater/u0a84 (adj 15): empty #17
,03-17 08:36:37.618   921  1401 D Process : killProcessQuiet, pid=4461
03-17 08:36:37.618   921  1401 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-17 08:36:37.628  4974  4974 I vclib   : onServiceConnected,
03-17 08:36:37.628  4974  4974 W Babel   : Attempted to change video mute state without an active call.
,03-17 08:36:37.728   921  4355 I ActivityManager: Recipient 4461
,03-17 08:36:37.848   921  1401 I ActivityManager: Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=5061 uid=10176 gids={50176, 9997, 3003, 1028, 1015} abi=arm64-v8a,
03-17 08:36:37.848   921  1401 D Process : killProcessQuiet, pid=4502
03-17 08:36:37.848   921  1401 I ActivityManager: Killing 4502:com.htc.android.worldclock/u0a90 (adj 15): empty #17
,03-17 08:36:37.848   921  1401 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,03-17 08:36:37.978   921  1716 I ActivityManager: Recipient 4502
,03-17 08:36:38.198   921  1720 I art     : Explicit concurrent mark sweep GC freed 19239(1066KB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 16MB/24MB, paused 1.400ms total 133.792ms,
,03-17 08:36:38.358  5061  5083 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-17 08:36:38.358  5061  5083 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 08:36:38.388  5061  5083 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,03-17 08:36:38.438  5061  5083 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
03-17 08:36:38.438  5061  5083 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-17 08:36:38.508   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 6,
03-17 08:36:38.508  1212  1212 D WIFI_ICON: WifiActivity: 1
03-17 08:36:38.508   921   921 E WifiTrafficPoller:  packet count Tx=58 Rx=121
03-17 08:36:38.508  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
03-17 08:36:38.508   921   921 E WifiTrafficPoller: notifying of data activity 1
,03-17 08:36:38.558  5061  5088 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
03-17 08:36:38.558  5061  5088 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 08:36:38.628  5093  5093 E cutils-trace: Error opening trace file: Permission denied (13),
03-17 08:36:38.628  5093  5093 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-1520366352.jar --oat-fd=32 --oat-location=/data/data/com.google.android.youtube/cache/ads-1520366352.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
03-17 08:36:38.628  5093  5093 I dex2oat : dex2oat: override thread count:4
,03-17 08:36:38.678  5093  5093 I dex2oat : dex2oat took 41.380ms (threads: 4)
,03-17 08:36:38.678  5061  5061 E YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,03-17 08:36:38.688  5061  5061 D libc    : [NET] android_getaddrinfofornet+,hn 9(0x3132372e302e30),sn(),hints(known),family 0,flags 4,
03-17 08:36:38.688  5061  5061 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
,03-17 08:36:38.748   921   950 D VoldConnector: SND -> {19 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/},
03-17 08:36:38.748   383   657 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
,03-17 08:36:38.748  5061  5061 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,03-17 08:36:38.968   921  1712 D VoldConnector: SND -> {20 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/},
03-17 08:36:38.968   383   657 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
,03-17 08:36:38.968  5061  5061 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,03-17 08:36:38.968   921  1720 D VoldConnector: SND -> {21 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/files/},
03-17 08:36:38.978   383   657 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/files/
03-17 08:36:38.978  5061  5061 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/files
,03-17 08:36:38.978   921  1710 D VoldConnector: SND -> {22 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/files/}
03-17 08:36:38.978   383   657 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/files/
,03-17 08:36:38.978  5061  5061 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/files
,03-17 08:36:38.988  5061  5061 W InstanceID/Rpc: Found 10024
,03-17 08:36:39.008   921  2373 D VoldConnector: SND -> {23 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/},
03-17 08:36:39.008   383   657 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
03-17 08:36:39.018  5061  5061 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,03-17 08:36:39.128   921  1157 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=5142 uid=10106 gids={50106, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,03-17 08:36:39.128  5061  5137 D libc    : [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
03-17 08:36:39.128  5061  5137 D libc    : [NET] android_getaddrinfofornet-, err=8,
03-17 08:36:39.128  5061  5137 D libc    : [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
03-17 08:36:39.128  5061  5137 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
,03-17 08:36:39.128  5061  5137 D libc    : [NET] android_getaddrinfo_proxy+
03-17 08:36:39.128  5061  5137 D libc    : [NET] android_getaddrinfo_proxy get netid:0
03-17 08:36:39.128   408  5155 D libc    : [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
03-17 08:36:39.128   408  5155 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
,03-17 08:36:39.158   921   950 I ActivityManager: Killing 4538:com.google.android.configupdater/u0a98 (adj 15): empty #17
,03-17 08:36:39.158   921   950 D Process : killProcessQuiet, pid=4538
03-17 08:36:39.158   921   950 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-17 08:36:39.208   408  5155 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS)
,03-17 08:36:39.208   408  5155 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
03-17 08:36:39.208  5061  5137 D libc    : [NET] android_getaddrinfo_proxy-, success
,03-17 08:36:39.208  5061  5137 D libc    : [NET] android_getaddrinfofornet+,hn 14(0x3137322e323137),sn(),hints(known),family 0,flags 4
03-17 08:36:39.208  5061  5137 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
,03-17 08:36:39.258   921  1712 I ActivityManager: Recipient 4538
,03-17 08:36:39.368   921  1718 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
,03-17 08:36:39.468  5142  5168 I Gmail   : getAccountsCursor,
,03-17 08:36:39.478  5142  5142 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-17 08:36:39.488  1882  1882 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-17 08:36:39.488  5061  5137 D libc    : [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
03-17 08:36:39.488  5061  5137 D libc    : [NET] android_getaddrinfofornet-, err=8
,03-17 08:36:39.508   921  4355 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.AttachmentService, state=2, flag=1, pid=5142, uid=10106, userID:0,
03-17 08:36:39.508   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 6
03-17 08:36:39.508   921  1157 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
03-17 08:36:39.508   921   921 E WifiTrafficPoller:  packet count Tx=68 Rx=128
03-17 08:36:39.508  1212  1212 D WIFI_ICON: WifiActivity: 3
03-17 08:36:39.508   921   921 E WifiTrafficPoller: notifying of data activity 3
03-17 08:36:39.508  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,03-17 08:36:39.518  5142  5176 I Gmail   : Observing account changes for notifications
,03-17 08:36:39.528   921  1719 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 08:36:39.528   921  1719 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 08:36:39.528   921  1719 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=5142, uid=10106, userID:0
03-17 08:36:39.528   921  4355 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=5142, uid=10106, userID:0
,03-17 08:36:39.548  5142  5178 E Gmail   : Error finding the version of the Email provider.....
03-17 08:36:39.548  5142  5178 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
03-17 08:36:39.548  5142  5178 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
03-17 08:36:39.548  5142  5178 E Gmail   : 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
03-17 08:36:39.548  5142  5178 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
03-17 08:36:39.548  5142  5178 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
,03-17 08:36:39.548  5142  5178 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 08:36:39.548  5142  5178 E Gmail   : 	at android.os.Looper.loop(Looper.java:155)
03-17 08:36:39.548  5142  5178 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-17 08:36:39.548  5142  5178 W EmailMigration: We do not support migrating this version of the Email provider.
03-17 08:36:39.548   921  2373 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GoogleMailWidgetProvider, state=2, flag=1, pid=5142, uid=10106, userID:0
03-17 08:36:39.548   921  1721 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GmailWidgetProvider, state=1, flag=1, pid=5142, uid=10106, userID:0
,03-17 08:36:39.548   921   950 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGoogleMail, state=2, flag=1, pid=5142, uid=10106, userID:0
03-17 08:36:39.548   921  1718 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGmail, state=1, flag=1, pid=5142, uid=10106, userID:0
,03-17 08:36:39.548  5142  5180 I Gmail   : getAccountsCursor
,03-17 08:36:39.558  1882  1882 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 08:36:39.578   921  1716 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=5183 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
,03-17 08:36:39.578   921  1515 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
03-17 08:36:39.578   921  1710 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=5142, uid=10106, userID:0
03-17 08:36:39.578   921  2373 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=5142, uid=10106, userID:0
,03-17 08:36:39.588   921   951 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 08:36:39.588  5142  5142 E ActivityThread: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@2a47304f that was originally bound here
03-17 08:36:39.588  5142  5142 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@2a47304f that was originally bound here
03-17 08:36:39.588  5142  5142 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1183)
03-17 08:36:39.588  5142  5142 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1077)
03-17 08:36:39.588  5142  5142 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1906)
03-17 08:36:39.588  5142  5142 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1889)
03-17 08:36:39.588  5142  5142 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
03-17 08:36:39.588  5142  5142 E ActivityThread: 	at com.android.emailcommon.service.ak.a(SourceFile:181)
03-17 08:36:39.588  5142  5142 E ActivityThread: 	at com.android.emailcommon.service.ak.e(SourceFile:224)
03-17 08:36:39.588  5142  5142 E ActivityThread: 	at com.android.email.service.n.c(SourceFile:177)
03-17 08:36:39.588  5142  5142 E ActivityThread: 	at com.android.email.provider.b.a(SourceFile:198)
03-17 08:36:39.588  5142  5142 E ActivityThread: 	at com.android.email.provider.b.a(SourceFile:142)
03-17 08:36:39.588  5142  5142 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
03-17 08:36:39.588  5142  5142 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
03-17 08:36:39.588  5142  5142 E ActivityThread: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-17 08:36:39.588  5142  5142 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 08:36:39.588  5142  5142 E ActivityThread: 	at android.os.Looper.loop(Looper.java:155)
03-17 08:36:39.588  5142  5142 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 08:36:39.588   921   951 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@644b11e
,03-17 08:36:39.608  1882  1882 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-17 08:36:39.708  5142  5181 E SQLiteLog: (283) recovered 1710 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal,
,03-17 08:36:39.788   921   921 E WifiDataStallTracker: DATA_MONITOR_POLL true Token 1,
,03-17 08:36:39.788   921  5208 D WifiDataStallTracker: updateDataStallInfo: mDataStallTxRxSum={txSum=56 rxSum=42} preTxRxSum={txSum=44 rxSum=33}
03-17 08:36:39.788   921  5208 D WifiDataStallTracker: updateDataStallInfo: IN/OUT
03-17 08:36:39.788   921  5208 D WifiDataStallTracker: onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,03-17 08:36:39.948  5142  5205 I Gmail   : notifyAccountChanged,
,03-17 08:36:39.958  5142  5210 I Gmail   : getAccountsCursor
,03-17 08:36:39.958  5142  5205 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-17 08:36:39.968  1882  1882 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 08:36:39.978  5142  5205 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-17 08:36:39.998   921  1148 E WifiStateMachine: handleMessage: E msg.what=131155
03-17 08:36:39.998   921  1148 E WifiStateMachine: processMsg: ConnectedState
,03-17 08:36:39.998   921  1148 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-52 f=2457 sc=60 link=150 tx=0.8, 0.0, 0.0  rx=5.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2088680637] gl hn u24 rssi=-47 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0,
03-17 08:36:39.998   921  1720 D PMS     : acquireWL(846df7): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 5142 10106 null
03-17 08:36:39.998   921  1148 E WifiStateMachine: processMsg: L2ConnectedState
03-17 08:36:39.998   921  1148 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-52 f=2457 sc=60 link=150 tx=0.8, 0.0, 0.0  rx=5.4 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-2088680636] gl hn u24 rssi=-47 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
03-17 08:36:39.998   921  1148 E WifiStateMachine:  get link layer stats 0,
03-17 08:36:39.998   921  1148 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
03-17 08:36:39.998  1346  1346 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
03-17 08:36:39.998  5142  5181 I Gmail   : Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: (has extras) }
,03-17 08:36:40.008  1346  1346 I wpa_supplicant: environment dirty rate=0 [13][0][0]
,03-17 08:36:40.008   921  1148 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 150
03-17 08:36:40.008  1491  2758 I SocialFeedProvider: +disConnect socialManager
03-17 08:36:40.008  1491  2758 I SocialFeedProvider: disconnect socialManager
03-17 08:36:40.008   921  1148 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-53 linkspeed=150
03-17 08:36:40.018   921  1148 E WifiConfigStore: updateConfiguration freq=2457 BSSID=f4:f2:6d:22:99:3e RSSI=-52 "NG700"WPA_PSK
,03-17 08:36:40.018   921  1148 E WifiStateMachine: calculateWifiScore freq=2457 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=6.92 txretriesrate=0.00 rxrate=8.71 userTriggerdPenalty0
03-17 08:36:40.018   921  1148 E WifiStateMachine:  good link -> stuck count =0
03-17 08:36:40.018  1212  1212 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3
03-17 08:36:40.018   921  1148 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 60
03-17 08:36:40.018  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
03-17 08:36:40.018   921  1148 E WifiStateMachine:  isHighRSSI       ---> score=65
03-17 08:36:40.018  1491  2758 I SocialFeedProvider: -disConnect socialManager
03-17 08:36:40.018   921  1148 E WifiStateMachine: handleMessage: X
03-17 08:36:40.018   921  1166 D WifiWatchdogStateMachine: RSSI current: 3 new: -53, 3
,03-17 08:36:40.018   921  1721 D PMS     : acquireWL(846df7): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 5142 10106 null
03-17 08:36:40.018  5142  5181 I Gmail   : Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: (has extras) }
,03-17 08:36:40.028  5142  5205 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-17 08:36:40.028  5142  5205 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-17 08:36:40.028   921  4355 D PMS     : acquireWL(846df7): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 5142 10106 null
,03-17 08:36:40.028  5142  5181 I Gmail   : Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: (has extras) }
,03-17 08:36:40.028   921  1157 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.ComposeActivityGmail, state=1, flag=1, pid=5142, uid=10106, userID:0
,03-17 08:36:40.028   921  1514 I ActivityManager: Killing 4334:com.htc.cs.dm/u0a99 (adj 15): empty #17
03-17 08:36:40.028   921  1514 D Process : killProcessQuiet, pid=4334
,03-17 08:36:40.038   921  1514 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-17 08:36:40.058  1882  3574 I art     : Explicit concurrent mark sweep GC freed 7598(404KB) AllocSpace objects, 0(0B) LOS objects, 49% free, 4MB/8MB, paused 741us total 35.451ms
,03-17 08:36:40.118   921  1718 I ActivityManager: Recipient 4334
,03-17 08:36:40.138   921  1137 V AlarmManager: sending alarm PendingIntent{281e0285: PendingIntentRecord{3169c8da com.google.android.talk broadcastIntent}}, i=com.google.android.apps.hangouts.RENEW_ACCOUNT_REGISTRATION, t=2, cnt=1, w=60079, Int=259200000,
,03-17 08:36:40.158   921  1137 I ActivityManager: Start proc com.htc.sense.news for service com.htc.launcher/com.htc.plugin.news.SocialBiLogHelper: pid=5214 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a
03-17 08:36:40.158   921  1137 V AlarmManager: sending alarm PendingIntent{37d9210b: PendingIntentRecord{18c14201 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1458200200111, Int=0
,03-17 08:36:40.168   921  2373 D LocationManagerService: getProviders()=[passive]
,03-17 08:36:40.208  5142  5210 I Gmail   : master sync=false, engine sync=true,
,03-17 08:36:40.228   921  1712 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5237 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a
,03-17 08:36:40.288  5142  5264 I Gmail   : getAccountsCursor
,03-17 08:36:40.288  1882  1882 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-17 08:36:40.288   921   950 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.googlequicksearchbox.SearchActivity, state=1, flag=1, pid=5183, uid=10085, userID:0
03-17 08:36:40.298   921   951 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.googlequicksearchbox.VoiceSearchActivity, state=1, flag=1, pid=5183, uid=10085, userID:0
03-17 08:36:40.298   921   950 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.search.core.icingsync.ApplicationLaunchReceiver, state=1, flag=1, pid=5183, uid=10085, userID:0
03-17 08:36:40.298  5142  5264 I Gmail   : master sync=false, engine sync=true
,03-17 08:36:40.308  5214  5214 I ImageRamCache: create image Cache, size: 31457280.
,03-17 08:36:40.308  5214  5214 I ImageRamCache: [resize] ImageRamCache resized to: 30Mb.
03-17 08:36:40.308  5214  5214 I ImageRamCache: create image Cache, size: 31457280.
,03-17 08:36:40.318  5214  5214 I FeedSettings: [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
,03-17 08:36:40.318  5214  5214 I FeedSettings: GroupBudget 0.500000 0.380000
03-17 08:36:40.318  5214  5214 I FeedSettings: GroupBudget 60 45 15
,03-17 08:36:40.328  5214  5214 I Prism.ExternalStringMa_: changeLocale(): en_GB
,03-17 08:36:40.348  5214  5214 I Prism.AllAppsOptionsMa_: loadSortType() with Custom
,03-17 08:36:40.348  5214  5214 I Prism.AllAppsOptionsMa_: loadGridSize() with Alternative
,03-17 08:36:40.368   921   921 E WifiTrafficPoller: ADD_CLIENT: 7,
03-17 08:36:40.368   921  1149 D WifiService: New client listening to asynchronous messages
,03-17 08:36:40.378   921  1157 W BroadcastQueue: Permission Denial: receiving Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 (has extras) } to pl.k2.droidoaudioteka/.ford.AppLinkReceiver requires android.permission.RECEIVE_BOOT_COMPLETED due to sender null (uid 1000)
,03-17 08:36:40.388  4850  4865 E AndroidHttpClient: Leak found,
03-17 08:36:40.388  4850  4865 E AndroidHttpClient: java.lang.IllegalStateException: AndroidHttpClient created and never closed
03-17 08:36:40.388  4850  4865 E AndroidHttpClient: 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
03-17 08:36:40.388  4850  4865 E AndroidHttpClient: 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
03-17 08:36:40.388  4850  4865 E AndroidHttpClient: 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
03-17 08:36:40.388  4850  4865 E AndroidHttpClient: 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
03-17 08:36:40.388  4850  4865 E AndroidHttpClient: 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
03-17 08:36:40.388  4850  4865 E AndroidHttpClient: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
03-17 08:36:40.388  4850  4865 E AndroidHttpClient: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
03-17 08:36:40.388  4850  4865 E AndroidHttpClient: 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
03-17 08:36:40.388  4850  4865 E AndroidHttpClient: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
03-17 08:36:40.388  4850  4865 E AndroidHttpClient: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 08:36:40.388  4850  4865 E AndroidHttpClient: 	at android.os.Looper.loop(Looper.java:155)
03-17 08:36:40.388  4850  4865 E AndroidHttpClient: 	at android.app.ActivityThread.main(ActivityThread.java:5721)
03-17 08:36:40.388  4850  4865 E AndroidHttpClient: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 08:36:40.388  4850  4865 E AndroidHttpClient: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 08:36:40.388  4850  4865 E AndroidHttpClient: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
03-17 08:36:40.388  4850  4865 E AndroidHttpClient: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,03-17 08:36:40.398   921  1021 I ActivityManager: Start proc com.htc.club for broadcast com.htc.club/com.mcrm.autonotification.Autostart: pid=5279 uid=10181 gids={50181, 9997, 3003, 1028, 1015} abi=arm64-v8a
,03-17 08:36:40.398   921  1401 I ActivityManager: Killing 4623:com.htc.backupreset/1000 (adj 15): empty #17
03-17 08:36:40.398   921  1401 D Process : killProcessQuiet, pid=4623
03-17 08:36:40.398   921  1401 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
03-17 08:36:40.398  5214  5277 I SocialManager[SocialBiLogHelper]: action: com.htc.sense.hsp.HANDLE_ULOG
03-17 08:36:40.398  5214  5277 I SocialManager[SocialBiLogHelper]: last commit ulog time 1458123495685
03-17 08:36:40.398  5214  5277 I SocialManager[SocialBiLogHelper]: skip commit this time
,03-17 08:36:40.508   921  1718 I ActivityManager: Recipient 4623
,03-17 08:36:40.508   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 7,
03-17 08:36:40.508   921   921 E WifiTrafficPoller:  packet count Tx=71 Rx=132
,03-17 08:36:40.618   921  1712 D Process : killProcessQuiet, pid=4655
03-17 08:36:40.618   921  1712 I ActivityManager: Killing 4655:com.htc.htccupd/u0a13 (adj 15): empty #17
03-17 08:36:40.618   921  1712 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-17 08:36:40.708   921  2373 I ActivityManager: Recipient 4655
,03-17 08:36:40.738  1882  5304 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE,
,03-17 08:36:40.748  1882  1882 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-17 08:36:40.758  4407  4407 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-17 08:36:40.778  5279  5279 D libc    : [NET] android_getaddrinfofornet+,hn 48(0x6874632d636c75),sn(),hints(known),family 0,flags 4
,03-17 08:36:40.778  5279  5279 D libc    : [NET] android_getaddrinfofornet-, err=8
03-17 08:36:40.778  5279  5279 D libc    : [NET] android_getaddrinfofornet+,hn 48(0x6874632d636c75),sn(),hints(known),family 0,flags 1024
03-17 08:36:40.778  5279  5279 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
03-17 08:36:40.778  5279  5279 D libc    : [NET] android_getaddrinfo_proxy+
03-17 08:36:40.778  5279  5279 D libc    : [NET] android_getaddrinfo_proxy get netid:0
03-17 08:36:40.778   408  5306 D libc    : [NET] android_getaddrinfofornet+,hn 48(0x6874632d636c75),sn(),hints(known),family 0,flags 1024
03-17 08:36:40.778   408  5306 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
,03-17 08:36:40.808  5183  5303 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,03-17 08:36:40.808   921  1157 I ActivityManager: Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=5308 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,03-17 08:36:40.838  5183  5303 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 3487-3490)
,03-17 08:36:40.838  5183  5303 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 08:36:40.848  5183  5303 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 08:36:40.988   921  1157 I art     : Explicit concurrent mark sweep GC freed 13027(656KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.414ms total 138.769ms,
,03-17 08:36:40.998   921  1515 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4407, uid=10024, userID:0
,03-17 08:36:41.008  5308  5308 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-17 08:36:41.008  5308  5308 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 08:36:41.028  5308  5308 I MultiDex: VM with version 2.1.0 has multidex support
03-17 08:36:41.028  5308  5308 I MultiDex: install
03-17 08:36:41.028  5308  5308 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-17 08:36:41.058  1882  3488 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow,
03-17 08:36:41.058  1882  3488 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-17 08:36:41.058   921  2373 I ActivityManager: Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=5343 uid=10035 gids={50035, 9997} abi=arm64-v8a
03-17 08:36:41.058  1882  3488 I GLSUser : [GLSUser] Extracting token using key: Auth
03-17 08:36:41.058  1882  3488 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
03-17 08:36:41.068  1433  2424 D TelephUtils: QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 92
03-17 08:36:41.068  4407  5341 D LocationInitializer: Restart initialization of location
03-17 08:36:41.068  1433  2424 D AccFlag : sku_id=118
03-17 08:36:41.068  5183  5303 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-17 08:36:41.068  1882  3488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 08:36:41.078  5308  5308 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-17 08:36:41.078  1433  1993 D TelephUtils: QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 62
,03-17 08:36:41.078  1433  1993 D AccFlag : sku_id=118
,03-17 08:36:41.108  1433  2424 D TelephUtils: QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 92,
03-17 08:36:41.108  1433  2424 D AccFlag : sku_id=118
,03-17 08:36:41.118  1433  1993 D TelephUtils: QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 62
03-17 08:36:41.118  1433  1993 D AccFlag : sku_id=118
,03-17 08:36:41.128   408  5306 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS)
03-17 08:36:41.128   408  5306 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
,03-17 08:36:41.128  5279  5279 D libc    : [NET] android_getaddrinfo_proxy-, success
03-17 08:36:41.128  5279  5279 D libc    : [NET] android_getaddrinfofornet+,hn 13(0x35342e3233312e),sn(),hints(known),family 0,flags 4
03-17 08:36:41.128  5279  5279 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
,03-17 08:36:41.138  1306  1345 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
03-17 08:36:41.138  1306  1345 D DotMatrix: [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
03-17 08:36:41.138  1212  1212 I RemoteViews: reapply : com.google.android.gms 3 40
,03-17 08:36:41.138  5183  5273 W Search.LoginHelper: User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
03-17 08:36:41.138  5183  5273 W Search.LoginHelper: com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
03-17 08:36:41.138  5183  5273 W Search.LoginHelper: 	at com.google.android.gms.auth.b.c(Unknown Source)
03-17 08:36:41.138  5183  5273 W Search.LoginHelper: 	at com.google.android.gms.auth.b.a(Unknown Source)
03-17 08:36:41.138  5183  5273 W Search.LoginHelper: 	at com.google.android.gms.auth.b.a(Unknown Source)
03-17 08:36:41.138  5183  5273 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
,03-17 08:36:41.138  5183  5273 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
03-17 08:36:41.138  5183  5273 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
03-17 08:36:41.138  5183  5273 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
03-17 08:36:41.138  5183  5273 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
03-17 08:36:41.138  5183  5273 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
03-17 08:36:41.138  5183  5273 W Search.LoginHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 08:36:41.138  5183  5273 W Search.LoginHelper: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-17 08:36:41.138  5183  5273 W Search.LoginHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 08:36:41.138  5183  5273 W Search.LoginHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 08:36:41.138  5183  5273 W Search.LoginHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 08:36:41.138  5183  5273 W Search.LoginHelper: 	at java.lang.Thread.run(Thread.java:818)
03-17 08:36:41.138  5183  5273 W Search.LoginHelper: 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
03-17 08:36:41.138  5183  5262 E VelvetNetworkClient: Failed to get auth token
,03-17 08:36:41.148  5308  5308 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-17 08:36:41.148  5308  5308 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3c7acb3f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-17 08:36:41.148  5308  5308 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-17 08:36:41.158  5183  5367 D libc    : [NET] android_getaddrinfofornet+,hn 13(0x7777772e676f6f),sn(),hints(known),family 2,flags 1024,
03-17 08:36:41.158  5183  5367 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
03-17 08:36:41.158  5183  5367 D libc    : [NET] android_getaddrinfo_proxy+,
03-17 08:36:41.158  5183  5367 D libc    : [NET] android_getaddrinfo_proxy get netid:0
03-17 08:36:41.158   408  5372 D libc    : [NET] android_getaddrinfofornet+,hn 13(0x7777772e676f6f),sn(),hints(known),family 2,flags 1024
03-17 08:36:41.158   408  5372 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
,03-17 08:36:41.168  5308  5308 D WearableService: callingUid 10024, callindPid: 5308
,03-17 08:36:41.188   921  1712 I ActivityManager: Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=5375 uid=10076 gids={50076, 9997} abi=arm64-v8a,
03-17 08:36:41.188   921  1712 D Process : killProcessQuiet, pid=4754
03-17 08:36:41.188   921  1712 I ActivityManager: Killing 4754:com.android.settings:remote/1000 (adj 15): empty #17
,03-17 08:36:41.188   921  1712 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,03-17 08:36:41.248   408  5372 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS)
03-17 08:36:41.248   408  5372 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
03-17 08:36:41.248  5279  5279 D libc    : [NET] android_getaddrinfofornet+,hn 3,sn(),hints(known),family 0,flags 4
03-17 08:36:41.248  5183  5367 D libc    : [NET] android_getaddrinfo_proxy-, success
03-17 08:36:41.248  5279  5279 D libc    : [NET] android_getaddrinfofornet-, err=8
,03-17 08:36:41.318   921   951 I ActivityManager: Recipient 4754
,03-17 08:36:41.428  1810  5307 E MDM     : [142] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
,03-17 08:36:41.438  5375  5375 D SMSBackup: Got a database change event,
,03-17 08:36:41.438  5214  5214 D CustomHighlightReceiver: [custom highlight] onReceive
,03-17 08:36:41.448  5214  5396 D CustomHighlightService: [custom highlight] onHandleIntent
,03-17 08:36:41.448  5214  5396 D NewsDB  : set custom highlight []
,03-17 08:36:41.488  4235  4235 D MessagingShortcutReceiver: keep hiding shortcut bubble
,03-17 08:36:41.498  4235  4235 D MessagingShortcut: updateMsgShortcut, msg count> -1
,03-17 08:36:41.498  4235  4235 D MessagingShortcut: After query: 0
03-17 08:36:41.498  4235  4235 D MessagingShortcut: mPresentUnreadCount: -1
,03-17 08:36:41.498  4235  4235 D MessageUtils: [getShortcut] com.htc.sense.mms.ui.ConversationList, false
03-17 08:36:41.498  4235  4235 D MessagingShortcut: setMsgShortcutDrawable> 0, false
,03-17 08:36:41.498  4235  4235 D MessagingShortcut: Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2,
03-17 08:36:41.508  1306  1306 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,03-17 08:36:41.508  1306  1306 D DotMatrix: [EventService] reorderNotification, total:0
,03-17 08:36:41.508  1306  1306 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-17 08:36:41.508  1306  1306 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,03-17 08:36:41.508  5214  5396 D CustomHighlightService: [custom highlight] set tags 
,03-17 08:36:41.518   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 7,
03-17 08:36:41.518   921   921 E WifiTrafficPoller:  packet count Tx=91 Rx=154
,03-17 08:36:41.518   921  1157 D PMS     : acquireWL(253bea53): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 921 1000 null
,03-17 08:36:41.528   921  1157 I BatteryService: n_update end
,03-17 08:36:41.528   921  1157 D PMS     : releaseWL(253bea53): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,03-17 08:36:41.528   921  4355 I ActivityManager: Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=5398 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a,
,03-17 08:36:41.528   921  1716 D Process : killProcessQuiet, pid=4780
03-17 08:36:41.528   921  1716 I ActivityManager: Killing 4780:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
,03-17 08:36:41.528   921  1716 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-17 08:36:41.548   439   439 I art     : Explicit concurrent mark sweep GC freed 8642(366KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 163us total 22.841ms
,03-17 08:36:41.568   439   439 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 149us total 15.775ms,
,03-17 08:36:41.578   439   439 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 154us total 16.016ms,
,03-17 08:36:41.638   921   951 I ActivityManager: Recipient 4780,
,03-17 08:36:41.738   921   921 D UsbnetService: BroadcastReceiver::onReceive+,
,03-17 08:36:41.738   921  1053 D HtcPowerSaver: updateBatteryInfo
03-17 08:36:41.738   921   921 D UsbnetService: onReceive BATTERY_CHANGED
,03-17 08:36:41.738   921   921 D NotificationService: plugged=true pluggin=true
03-17 08:36:41.738   921   921 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
03-17 08:36:41.738   921   921 D PMS     : runPSCheck
03-17 08:36:41.738   921   921 D UsbnetService: BroadcastReceiver::onReceive-
03-17 08:36:41.738   921  1149 D WifiController: battery changed pluggedType: 2
03-17 08:36:41.738   921  1149 D WifiController: handleMessage: E msg.what=155652
03-17 08:36:41.738   921   921 D HtcPowerSaver: Checking...
03-17 08:36:41.738   921  1149 D WifiController: processMsg: DeviceActiveState
03-17 08:36:41.738   921   921 I HtcPowerSaver: >> updateStatus
03-17 08:36:41.738   921  1149 D WifiController: processMsg: StaEnabledState
,03-17 08:36:41.748  1212  1212 D PowerUI : closing low battery warning: level=100
03-17 08:36:41.738   921  1149 D WifiController: processMsg: DefaultState
03-17 08:36:41.748  1212  1212 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
03-17 08:36:41.738   921  1149 D WifiController: handleMessage: X
03-17 08:36:41.748   921   921 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
03-17 08:36:41.748  1306  1306 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-17 08:36:41.748   921   921 I HtcPowerSaver: << updateStatus
03-17 08:36:41.748  1306  1306 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-17 08:36:41.748  1306  1306 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
03-17 08:36:41.748  3387  3524 D HeadsetStateMachine: Disconnected process message: 10, size: 0
03-17 08:36:41.748  1212  1616 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
,03-17 08:36:41.758   921  1720 D Process : killProcessQuiet, pid=4805
03-17 08:36:41.758   921  1720 I ActivityManager: Killing 4805:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
03-17 08:36:41.758   921  1720 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-17 08:36:41.758  5398  5398 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 08:36:41.758  5279  5279 D libc    : [NET] android_getaddrinfofornet+,hn 28(0x6874632d636c75),sn(),hints(known),family 0,flags 4
03-17 08:36:41.758  5279  5279 D libc    : [NET] android_getaddrinfofornet-, err=8
03-17 08:36:41.768  5279  5279 D libc    : [NET] android_getaddrinfofornet+,hn 28(0x6874632d636c75),sn(),hints(known),family 0,flags 1024
03-17 08:36:41.768  5279  5279 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
03-17 08:36:41.768  5279  5279 D libc    : [NET] android_getaddrinfo_proxy+
03-17 08:36:41.768  5279  5279 D libc    : [NET] android_getaddrinfo_proxy get netid:0
03-17 08:36:41.768   408  5421 D libc    : [NET] android_getaddrinfofornet+,hn 28(0x6874632d636c75),sn(),hints(known),family 0,flags 1024
03-17 08:36:41.768   408  5421 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
,03-17 08:36:41.798  1212  1212 I BatteryController: status:5 level:100 unsupport:false plugged:true
,03-17 08:36:41.818   921   951 I ActivityManager: Recipient 4805
,03-17 08:36:41.868  5398  5422 D TodoTaskshortcut: update TASK shortcut>
,03-17 08:36:41.878   408  5421 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS)
03-17 08:36:41.878   408  5421 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
03-17 08:36:41.878  5279  5279 D libc    : [NET] android_getaddrinfo_proxy-, success
,03-17 08:36:41.878  5279  5279 D libc    : [NET] android_getaddrinfofornet+,hn 13(0x3130342e38312e),sn(),hints(known),family 0,flags 4
03-17 08:36:41.878  5279  5279 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
,03-17 08:36:41.978   921  1721 D PMS     : acquireWL(12eb2089): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 5398 10069 null,
,03-17 08:36:41.978   921  1718 D Process : killProcessQuiet, pid=3649
03-17 08:36:41.978   921  1718 I ActivityManager: Killing 3649:com.android.defcontainer/u0a15 (adj 15): empty #17
03-17 08:36:41.978   921  1718 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,03-17 08:36:41.988   921  1720 D PMS     : acquireWL(24fcc88e): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 5398 10069 null
,03-17 08:36:42.038   921  1401 D PMS     : releaseWL(846df7): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 null,
,03-17 08:36:42.058   921  1710 I ActivityManager: Recipient 3649
,03-17 08:36:42.088   921  1719 D PMS     : releaseWL(12eb2089): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,03-17 08:36:42.098  5398  5424 E TodoTaskNotifyService: java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
,03-17 08:36:42.098  5398  5424 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
03-17 08:36:42.098  5398  5424 W System.err: 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
03-17 08:36:42.098  5398  5424 W System.err: 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
,03-17 08:36:42.098  5398  5424 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 08:36:42.098  5398  5424 W System.err: 	at android.os.Looper.loop(Looper.java:155)
03-17 08:36:42.098  5398  5424 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 08:36:42.098   921  1721 D PMS     : releaseWL(24fcc88e): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,03-17 08:36:42.098  5398  5424 W NotifyReceiver: stopSelfResult true
,03-17 08:36:42.158  3496  3571 I HtcModeClient: handler message = 4011
03-17 08:36:42.158  3496  3571 E HtcModeClient: Check connection and retry 4 times.
,03-17 08:36:42.158   921  1721 D PMS     : acquireWL(160bc4bc): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1882 10024 WorkSource{10024 com.google.android.gms},
,03-17 08:36:42.168   921  1720 D PMS     : releaseWL(160bc4bc): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,03-17 08:36:42.168  1882  5425 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-17 08:36:42.178  1882  1882 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.,
,03-17 08:36:42.178  4407  4407 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-17 08:36:42.198   921  1157 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4407, uid=10024, userID:0,
,03-17 08:36:42.208  1810  5426 E MDM     : [143] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
,03-17 08:36:42.208  4407  5427 D LocationInitializer: Restart initialization of location
03-17 08:36:42.208  4185  4185 D MtpReceiver: [MTP][handleUsbStateAsync]+,
03-17 08:36:42.208  4185  4185 D MtpReceiver: [MTP][handleUsbStateAsync]1:1-
03-17 08:36:42.208  4185  5428 D MtpReceiver: [MTP][handleUsbState]+
,03-17 08:36:42.218   921   950 I ActivityManager: Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=5430 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=arm64-v8a
,03-17 08:36:42.228  4185  5428 D MtpReceiver: [MTP][scanExternalVolumeIfNeed] scan external volume
03-17 08:36:42.228  4185  4185 D MtpService: updating state; isCurrentUser=true, mMtpLocked=false
,03-17 08:36:42.228  4185  5428 D MtpReceiver: [MTP][handleUsbState]-
03-17 08:36:42.228  4185  5428 D MtpReceiver: [MTP][handleMessage]-
,03-17 08:36:42.228  4185  4185 D MtpDatabase: TotalSize=1886532,MediaCacheLimit=6000
,03-17 08:36:42.238  4185  4185 D MtpService: [isMtpConnected] connected: true
,03-17 08:36:42.248   921  1712 D PMS     : acquireWL(2c0957c1): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 4407 10024 null
,03-17 08:36:42.318  4407  5444 I iu.UploadsManager: #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400,
,03-17 08:36:42.328  5430  5430 D SyncApplication: Loading default preferences
,03-17 08:36:42.338  5430  5430 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a},
,03-17 08:36:42.348  4185  4185 E MediaScannerService: [onStartCommand] --- Should not be here, redirect request. ----
,03-17 08:36:42.348  4185  5450 E MediaScannerService: [handleMessage] --- Should not be here, ignore request. ----
,03-17 08:36:42.368  4407  5444 I iu.UploadsManager: End new media; added: 0, uploading: 0, time: 44 ms
,03-17 08:36:42.368   921  2373 D PMS     : releaseWL(2c0957c1): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 null
,03-17 08:36:42.368   921   921 E WifiTrafficPoller: ADD_CLIENT: 8
,03-17 08:36:42.368   921  1149 D WifiService: New client listening to asynchronous messages
,03-17 08:36:42.388  5430  5430 D SyncApplication: Overriding preferences with custom values
,03-17 08:36:42.408  5430  5430 D SyncApplication: Updating preferences succeeded
,03-17 08:36:42.408  5430  5430 E SyncApplication: Application created.,
,03-17 08:36:42.408  5430  5460 W VolumeInfo: Unable to read mount points,
03-17 08:36:42.408  5430  5460 W VolumeInfo: java.io.FileNotFoundException: /etc/vold.fstab: open failed: ENOENT (No such file or directory)
03-17 08:36:42.408  5430  5460 W VolumeInfo: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-17 08:36:42.408  5430  5460 W VolumeInfo: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
03-17 08:36:42.408  5430  5460 W VolumeInfo: 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
03-17 08:36:42.408  5430  5460 W VolumeInfo: 	at java.io.FileReader.<init>(FileReader.java:66)
03-17 08:36:42.408  5430  5460 W VolumeInfo: 	at com.nero.android.common.VolumeInfo.getVolumeMountPoints(VolumeInfo.java:194)
03-17 08:36:42.408  5430  5460 W VolumeInfo: 	at com.nero.android.common.VolumeInfo.getVolumes(VolumeInfo.java:153)
03-17 08:36:42.408  5430  5460 W VolumeInfo: 	at com.nero.android.common.VolumeInfo.initializeVolumeIDs(VolumeInfo.java:474)
03-17 08:36:42.408  5430  5460 W VolumeInfo: 	,at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:51)
03-17 08:36:42.408  5430  5460 W VolumeInfo: 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:1)
03-17 08:36:42.408  5430  5460 W VolumeInfo: 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
03-17 08:36:42.408  5430  5460 W VolumeInfo: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 08:36:42.408  5430  5460 W VolumeInfo: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 08:36:42.408  5430  5460 W VolumeInfo: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 08:36:42.408  5430  5460 W VolumeInfo: 	at java.lang.Thread.run(Thread.java:818)
03-17 08:36:42.408  5430  5460 W VolumeInfo: Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
03-17 08:36:42.408  5430  5460 W VolumeInfo: 	at libcore.io.Posix.open(Native Method)
03-17 08:36:42.408  5430  5460 W VolumeInfo: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-17 08:36:42.408  5430  5460 W VolumeInfo: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-17 08:36:42.408  5430  5460 W VolumeInfo: 	,... 13 more
03-17 08:36:42.408  5430  5460 V VolumeInfo: Found 0 mount point(s)
03-17 08:36:42.408  5430  5460 V VolumeInfo: New VolumeInfo with mount point /storage/emulated/0 and sys path null created
03-17 08:36:42.408  5430  5430 I CalendarDefines: getNewCalendarAuthority()...
,03-17 08:36:42.418   921  4355 I PackageManager:  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=5430, uid=10005, userID:0
,03-17 08:36:42.418  5430  5430 D SyncApplication: enableAppOperation()+
03-17 08:36:42.418   921  4355 W PackageManager: Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
03-17 08:36:42.418   921  1716 I PackageManager:  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=5430, uid=10005, userID:0
03-17 08:36:42.418   921  1716 W PackageManager: Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,03-17 08:36:42.418  5430  5430 D SyncApplication: enableAppOperation()-
,03-17 08:36:42.418  5430  5460 D VolumeInfo: read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,03-17 08:36:42.418  5430  5430 D HTCUtilities: isNeorSinged() + 
,03-17 08:36:42.418  5430  5460 D VolumeInfo: Read the volume-id from the sd card: {9B5E872B-8520-47C6-8BD3-3081C2E38355},
03-17 08:36:42.418  5430  5460 W VolumeInfo: Can not create volume ID for unmounted volume null
,03-17 08:36:42.428  5430  5430 D HTCUtilities: sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,03-17 08:36:42.428  5430  5430 D HTCUtilities: isNeorSinged() return false
,03-17 08:36:42.428  5430  5430 D CDMountReceiver: receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,03-17 08:36:42.428  5430  5430 D CDMountReceiver: USB connected to PC
,03-17 08:36:42.448  5430  5430 D FOTAReceiver: onReceive() enter ,
03-17 08:36:42.448  5430  5430 D FOTAReceiver: receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,03-17 08:36:42.448  4730  4730 D TetherSettings: CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse,
03-17 08:36:42.448  4730  4730 D         : Cust_ConnectToPC   : Internet_Sharing>true
03-17 08:36:42.448  4730  4730 D         : Cust_ConnectToPC   : Modem_Link>false
03-17 08:36:42.448  4730  4730 D         : Cust_ConnectToPC   : spcsc>false
03-17 08:36:42.448  4730  4730 D         : Cust_ConnectToPC   : IPT>true
03-17 08:36:42.448  4730  4730 D         : Cust_ConnectToPC   : Singel_USB>false
03-17 08:36:42.448  4730  4730 W Settings: Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
03-17 08:36:42.448  4730  4730 E SmartNS_Utility: hasRemovableStorageSlot: true
03-17 08:36:42.448  4730  4730 D SmartNS_Utility: [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
03-17 08:36:42.448  4730  4730 D SmartNS_NSReceiver: onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
03-17 08:36:42.448  4730  4730 D SmartNS_Utility: usb_cable_connect = 1
03-17 08:36:42.448  4730  4730 D SmartNS_Utility: usb_denied = 0
,03-17 08:36:42.458  4185  5458 E MediaScannerServiceEx: [getStorageMaskIdFromPath] path is null
,03-17 08:36:42.458  4730  4730 I SmartNS_NSReceiver: locked:falsesecurity:falseisLocked:false
03-17 08:36:42.458  4730  4730 D SmartNS_NSReceiver: USB = true hasTethered = false isNSOpening: false
03-17 08:36:42.458  4185  5458 D MediaScannerServiceEx: [ServiceHandler][handleMessage] , action: null, Id: 0, path: /storage/emulated/0
,03-17 08:36:42.458  4730  4730 I PSReceiver: onReceive:com.htc.intent.action.USB_CONNECT2PC
,03-17 08:36:42.458  4730  4730 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2712 
,03-17 08:36:42.458  4185  5458 D MediaScannerServiceEx: [handleExternalVolume] ext storage
,03-17 08:36:42.458  4730  4730 I SmartNS_PSService: onReceive:com.htc.intent.action.USB_CONNECT2PC
03-17 08:36:42.468  4730  4730 W Settings: Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
03-17 08:36:42.468  4730  4730 I SmartNS_PSService:  defaultType:0
03-17 08:36:42.468  4730  4730 I SmartNS_PSService: fail notificaiton:false
03-17 08:36:42.468  4730  4730 D SmartNS_Utility: usb_cable_connect = 1
,03-17 08:36:42.468  4185  5458 D MediaProviderUtils: calcVolumeId: /storage/emulated/0
03-17 08:36:42.468  4185  5458 D MediaProviderUtils: calcVolumeId: /storage/ext_sd
03-17 08:36:42.468  4185  5458 D MediaProviderUtils: calcVolumeId: /storage/usb
03-17 08:36:42.468  4185  5458 D MediaScannerServiceEx: [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
,03-17 08:36:42.468  4185  5458 D MediaScannerServiceEx: [AliveExtStorageRows]+65537, 11223344
03-17 08:36:42.468  4730  4730 D SmartNS_Utility: usb_denied = 0
03-17 08:36:42.468  4730  4730 I SmartNS_PSService: usb notificaiton:true
,03-17 08:36:42.468   921  2373 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false
,03-17 08:36:42.468  4185  5458 D MediaProvider: [update][4]#0#
,03-17 08:36:42.468  4185  5458 D MediaProvider: [update][1]#0#
,03-17 08:36:42.478   921   950 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver: pid=5463 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
,03-17 08:36:42.478  4185  5458 D MediaProvider: [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted
03-17 08:36:42.478  4185  5458 D MtpService: [sendStorageAdded] Already send to MTP: /storage/emulated/0
03-17 08:36:42.488  4185  5458 D MediaProvider: [update][11]#1#
,03-17 08:36:42.488  4730  4730 D SmartNS_Utility: usb_cable_connect = 1
03-17 08:36:42.488  1306  1715 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,03-17 08:36:42.488  4730  4730 D SmartNS_Utility: usb_denied = 0
,03-17 08:36:42.488  4185  5458 D MediaScannerServiceEx: [AliveExtStorageRows]-0, 0
03-17 08:36:42.488  4730  4730 I SmartNS_PSService: usb notificaiton:true
03-17 08:36:42.488  1212  1212 I RemoteViews: reapply : com.android.settings 0 36
03-17 08:36:42.488   921  1720 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false
03-17 08:36:42.488   921  1157 D PMS     : acquireWL(2844acc0): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 4185 10017 null
,03-17 08:36:42.498  4185  5458 D MediaScanner: =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1
,03-17 08:36:42.498  4730  4730 D SmartNS_Utility: usb_cable_connect = 1
03-17 08:36:42.498  4730  4730 D SmartNS_Utility: usb_denied = 0
,03-17 08:36:42.498  1306  1717 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
03-17 08:36:42.498  1212  1212 I RemoteViews: reapply : com.android.settings 1 36
,03-17 08:36:42.508  4730  4730 I SmartNS_PSService: KeyGuard locked:falseKeyGuard is secured:false,
03-17 08:36:42.508  4730  4730 D SmartNS_PSService: USB Plugged, Set USBPlugged=  truePSenabled:false
,03-17 08:36:42.508   921  1401 D Process : killProcessQuiet, pid=4828
03-17 08:36:42.508   921  1401 I ActivityManager: Killing 4828:com.android.smith/1000 (adj 15): empty #17
03-17 08:36:42.508   921  1401 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-17 08:36:42.518   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8
,03-17 08:36:42.518   921   921 E WifiTrafficPoller:  packet count Tx=123 Rx=190
,03-17 08:36:42.558   921  1716 I ActivityManager: Recipient 4828
,03-17 08:36:42.758  5463  5463 I MusicStore: Database version: 120
,03-17 08:36:42.878   921  1710 D VoldConnector: SND -> {24 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
03-17 08:36:42.878   383   657 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
03-17 08:36:42.878  5463  5463 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,03-17 08:36:42.938   921  1716 D VoldConnector: SND -> {25 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
03-17 08:36:42.938   383   657 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,03-17 08:36:42.938  5463  5463 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,03-17 08:36:42.948   921   950 D VoldConnector: SND -> {26 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
03-17 08:36:42.948   383   657 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,03-17 08:36:42.948  5463  5463 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,03-17 08:36:42.978  5463  5463 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
03-17 08:36:42.978  5463  5463 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 08:36:42.988   921  1021 I ActivityManager: Waited long enough for: ServiceRecord{39de754d u0 com.htc.HTCSpeaker/.NGFService},
,03-17 08:36:42.998  5463  5463 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-17 08:36:43.018   921  1148 E WifiStateMachine: handleMessage: E msg.what=131155
03-17 08:36:43.018   921  1148 E WifiStateMachine: processMsg: ConnectedState
03-17 08:36:43.018   921  1148 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-53 f=2457 sc=60 link=150 tx=6.9, 0.0, 0.0  rx=8.7 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-2088677609] gl hn u24 rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
03-17 08:36:43.028   921  1148 E WifiStateMachine: processMsg: L2ConnectedState
,03-17 08:36:43.028   921  1148 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-53 f=2457 sc=60 link=150 tx=6.9, 0.0, 0.0  rx=8.7 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-2088677607] gl hn u24 rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,03-17 08:36:43.028   921  1148 E WifiStateMachine:  get link layer stats 0
03-17 08:36:43.028   921  1148 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
03-17 08:36:43.028  1346  1346 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
,03-17 08:36:43.038  1346  1346 I wpa_supplicant: environment dirty rate=3 [52][2][0]
03-17 08:36:43.038   921  1148 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 150
03-17 08:36:43.048  1212  1212 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3
03-17 08:36:43.038   921  1148 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-51 linkspeed=150
03-17 08:36:43.048  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
03-17 08:36:43.038   921  1148 E WifiConfigStore: updateConfiguration freq=2457 BSSID=f4:f2:6d:22:99:3e RSSI=-51 "NG700"WPA_PSK
03-17 08:36:43.038   921  1148 E WifiStateMachine: calculateWifiScore freq=2457 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=29.46 txretriesrate=0.00 rxrate=33.35 userTriggerdPenalty0
03-17 08:36:43.038   921  1148 E WifiStateMachine:  good link -> stuck count =0
03-17 08:36:43.038   921  1148 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 60
03-17 08:36:43.038   921  1148 E WifiStateMachine:  isHighRSSI       ---> score=65
03-17 08:36:43.038   921  1148 E WifiStateMachine: handleMessage: X
03-17 08:36:43.048   921  1166 D WifiWatchdogStateMachine: RSSI current: 3 new: -51, 3
,03-17 08:36:43.058  5463  5463 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
03-17 08:36:43.058  5463  5463 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3d4df0b1: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-17 08:36:43.058  5463  5463 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
03-17 08:36:43.058  5463  5463 D AndroidMusic: GMSCore installation verified
,03-17 08:36:43.068  5463  5463 I ConfigStore: Config Database version: 1
,03-17 08:36:43.148   921  1157 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=5463, uid=10159, userID:0,
,03-17 08:36:43.158   921  1720 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
03-17 08:36:43.158   921  1720 D WifiDisplayAdapter:     Client/Owner: Client
03-17 08:36:43.158   921  1720 D WifiDisplayAdapter:     GroupId: 
03-17 08:36:43.158   921  1720 D WifiDisplayAdapter:     Passphrase: 
03-17 08:36:43.158   921  1720 D WifiDisplayAdapter:     SessionId: 0
03-17 08:36:43.158   921  1720 D WifiDisplayAdapter:     IP Address: }
,03-17 08:36:43.168   921  1721 D MediaRouterService: Client com.google.android.music (pid 5463): Registered
,03-17 08:36:43.168   921  1716 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
03-17 08:36:43.168   921  1716 D WifiDisplayAdapter:     Client/Owner: Client
03-17 08:36:43.168   921  1716 D WifiDisplayAdapter:     GroupId: 
03-17 08:36:43.168   921  1716 D WifiDisplayAdapter:     Passphrase: 
03-17 08:36:43.168   921  1716 D WifiDisplayAdapter:     SessionId: 0
03-17 08:36:43.168   921  1716 D WifiDisplayAdapter:     IP Address: }
,03-17 08:36:43.178  5463  5463 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android },
,03-17 08:36:43.188   921  1720 D PMS     : acquireWL(51e2752): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 5463 10159 null,
,03-17 08:36:43.188  5463  5463 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true,
,03-17 08:36:43.278  5463  5463 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true,
,03-17 08:36:43.298   921  1157 I ActivityManager: Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=5498 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,03-17 08:36:43.298   921  1720 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=5463, uid=10159, userID:0
,03-17 08:36:43.398   921  1719 I art     : Explicit concurrent mark sweep GC freed 13496(675KB) AllocSpace objects, 2(104KB) LOS objects, 33% free, 16MB/24MB, paused 1.490ms total 140.834ms
,03-17 08:36:43.418  4185  5458 D MediaProvider: [update][70]#1#
,03-17 08:36:43.418  5463  5463 I MusicLeanback: Stop autocaching.
,03-17 08:36:43.418  5463  5486 I MusicLeanback: Stop autocaching.
,03-17 08:36:43.438  5498  5498 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.backupreset.receiver.BackupResetReceiver.onReceive:45 android.app.ActivityThread.handleReceiver:2712 
,03-17 08:36:43.448  5463  5486 I MusicLeanback: Stop autocaching.
,03-17 08:36:43.448   921  1157 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=5463, uid=10159, userID:0
,03-17 08:36:43.458   921  1514 I ActivityManager: Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=5523 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
,03-17 08:36:43.468   921  2373 D PMS     : releaseWL(51e2752): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null,
,03-17 08:36:43.468  5463  5495 I MusicLeanback: Conditions not met for autocaching. okToAttempt=false
03-17 08:36:43.468  5463  5495 I MusicLeanback: Stop autocaching.
,03-17 08:36:43.478  5463  5463 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient,
,03-17 08:36:43.478  5463  5463 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-17 08:36:43.488   921   950 I ActivityManager: Killing 4887:com.google.android.gms:car/u0a24 (adj 15): empty #17
03-17 08:36:43.488   921   950 D Process : killProcessQuiet, pid=4887
,03-17 08:36:43.488   921   950 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-17 08:36:43.518   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8,
03-17 08:36:43.518   921   921 E WifiTrafficPoller:  packet count Tx=123 Rx=191
03-17 08:36:43.518  1212  1212 D WIFI_ICON: WifiActivity: 1
03-17 08:36:43.518   921   921 E WifiTrafficPoller: notifying of data activity 1
03-17 08:36:43.518  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,03-17 08:36:43.598   921  1514 I ActivityManager: Recipient 4887
,03-17 08:36:43.598   921  2373 D Process : killProcessQuiet, pid=4850
,03-17 08:36:43.598   921  2373 I ActivityManager: Killing 4850:com.android.vending/u0a72 (adj 15): empty #17
03-17 08:36:43.608   921  2373 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-17 08:36:43.628  5523  5523 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-17 08:36:43.648   921  1148 E WifiStateMachine: handleMessage: E msg.what=131165
,03-17 08:36:43.648   921  1148 E WifiStateMachine: processMsg: ConnectedState
03-17 08:36:43.648   921  1148 E WifiStateMachine:  ConnectedState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
03-17 08:36:43.648   921  1148 E WifiStateMachine: processMsg: L2ConnectedState
03-17 08:36:43.648   921  1148 E WifiStateMachine:  L2ConnectedState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
03-17 08:36:43.648   921  1148 E WifiStateMachine: processMsg: ConnectModeState
03-17 08:36:43.648   921  1148 E WifiStateMachine:  ConnectModeState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
03-17 08:36:43.648   921  1148 E WifiStateMachine: processMsg: DriverStartedState
03-17 08:36:43.648   921  1148 E WifiStateMachine:  DriverStartedState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
03-17 08:36:43.648   921  1148 E WifiStateMachine: processMsg: SupplicantStartedState
03-17 08:36:43.648   921  1148 E WifiStateMachine:  SupplicantStartedState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
03-17 08:36:43.648   921  1148 E WifiStateMachine: processMsg: DefaultState
03-17 08:36:43.648   921  1148 E WifiStateMachine:  DefaultState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
03-17 08:36:43.648   921  1148 E WifiStateMachine: handleMessage: X
,03-17 08:36:43.688   921  1718 I ActivityManager: Recipient 4850
,03-17 08:36:43.748  4185  5458 D MediaProvider: [update][12]#1#,
,03-17 08:36:43.748  5523  5523 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@31451c4d(com.htc.providers.calendar.HtcCalendarProvider@399ab302)
,03-17 08:36:43.748  4185  5458 D MediaScanner:  prescan time: 308ms
03-17 08:36:43.748  4185  5458 D MediaScanner:     scan time: 944ms
03-17 08:36:43.748  4185  5458 D MediaScanner: postscan time: 3ms
03-17 08:36:43.748  4185  5458 D MediaScanner:    total time: 1255ms
03-17 08:36:43.748  4185  5458 D MediaScanner: -----------------------------------------------------------------
03-17 08:36:43.748  4185  5458 D MediaScanner: firstscan(media) time: 532ms
03-17 08:36:43.748  4185  5458 D MediaScanner: secondscan(non-media) time: 412ms
03-17 08:36:43.748  4185  5458 D MediaScanner:  [Update]   Image: 0 Video: 0 Audio: 0 Other: 1
03-17 08:36:43.748  4185  5458 D MediaScanner:  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
03-17 08:36:43.748  4185  5458 D MediaScanner:  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
03-17 08:36:43.748  4185  5458 D MediaScanner:  [Total]    File(Image+Video+Audio+Others) in database : 1549
,03-17 08:36:43.758  5463  5463 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-17 08:36:43.758  5523  5550 D CalendarProvider2: wait start:true
03-17 08:36:43.758  5463  5548 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-17 08:36:43.758   921   951 D Process : killProcessQuiet, pid=5025,
03-17 08:36:43.758   921   951 I ActivityManager: Killing 5025:com.htc.mobiledata/u0a46 (adj 15): empty #17
03-17 08:36:43.758   921   951 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-17 08:36:43.768  4185  5458 D MediaProvider: [delete][16]
03-17 08:36:43.768  4185  5458 D MediaProvider: [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
03-17 08:36:43.768  4185  5458 D MediaProvider: [recoverParentNodes] - 0
03-17 08:36:43.768  4185  5458 D MediaProvider: [update][4]
03-17 08:36:43.768  4185  5458 D MediaScannerServiceEx: [scan] Recover Parent Node is finished!
03-17 08:36:43.768  4185  5458 D MediaScannerServiceEx: [updateImage]+
,03-17 08:36:43.778  4185  5458 D MediaScannerServiceEx: [updateImage]-0,
,03-17 08:36:43.818  4594  4804 I jxcore-log: INFO thaliMobileNativeWrapper Method peerAvailabilityChanged registered to native,
03-17 08:36:43.818  4594  4804 I jxcore-log: 
,03-17 08:36:43.818  4594  4804 I jxcore-log: INFO thaliMobileNativeWrapper Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-17 08:36:43.818  4594  4804 I jxcore-log: 
,03-17 08:36:43.818  4594  4804 D BluetoothAdapter: 914685262: getState(). Returning 12
,03-17 08:36:43.818  4594  4804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-17 08:36:43.818  4594  4804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-17 08:36:43.818  4594  4804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-17 08:36:43.818  4594  4804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-17 08:36:43.818  4594  4804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-17 08:36:43.818  4594  4804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-17 08:36:43.818  4594  4804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-17 08:36:43.818  4594  4804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-17 08:36:43.828  4594  4804 D BluetoothAdapter: 914685262: getState(). Returning 12
,03-17 08:36:43.828  4594  4804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-17 08:36:43.828  4594  4804 I jxcore-log: INFO thaliMobileNativeWrapper Method networkChanged registered to native
03-17 08:36:43.828  4594  4804 I jxcore-log: 
03-17 08:36:43.828  4594  4804 I jxcore-log: INFO thaliMobileNativeWrapper Method incomingConnectionToPortNumberFailed registered to native
03-17 08:36:43.828  4594  4804 I jxcore-log: 
,03-17 08:36:43.858   921  4355 I ActivityManager: Recipient 5025,
,03-17 08:36:43.868   921  1720 D PMS     : releaseWL(2844acc0): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
03-17 08:36:43.868  4185  5458 D MediaScannerServiceEx: [1] scan finished
,03-17 08:36:43.878  4185  5458 D MediaProviderUtils: calcVolumeId: /storage/emulated/0
,03-17 08:36:43.878  4185  5458 D MediaProviderUtils: calcVolumeId: /storage/ext_sd
03-17 08:36:43.878  4185  5458 D MediaProviderUtils: calcVolumeId: /storage/usb
03-17 08:36:43.878  4185  5458 D MediaScannerServiceEx: [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #1
03-17 08:36:43.878  4185  5458 W MediaScannerServiceEx: Process mounted intent for unmounted storage: /storage/ext_sd
03-17 08:36:43.878  4185  5458 D MediaScannerServiceEx: [disAliveExtStorageRows]+131073
,03-17 08:36:43.888  4185  5458 D MediaProvider: [sendStorageAddedIfNeed]: /storage/ext_sd : unmounted,
,03-17 08:36:43.888  4185  5458 D MediaProvider: [update][9]#1#
,03-17 08:36:43.908  5523  5523 D FlexNetS: updateSvcAllowedInSettings:false,
,03-17 08:36:43.908  5523  5550 D CalendarProvider2: wait end:false
,03-17 08:36:43.918  4185  5458 D MediaProvider: [update][31]#0#,
,03-17 08:36:43.928  4185  5458 D MediaScannerServiceEx: [disAliveExtStorageRows]--1, 0
,03-17 08:36:43.928   921  1718 I ActivityManager: Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=5554 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,03-17 08:36:43.928  4185  5458 D MediaProviderUtils: calcVolumeId: /storage/emulated/0
,03-17 08:36:43.928  4185  5458 D MediaProviderUtils: calcVolumeId: /storage/ext_sd
03-17 08:36:43.928  4185  5458 D MediaProviderUtils: calcVolumeId: /storage/usb
03-17 08:36:43.928  4185  5458 D MediaScannerServiceEx: [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #2
03-17 08:36:43.928  4185  5458 W MediaScannerServiceEx: Process mounted intent for unmounted storage: /storage/usb
03-17 08:36:43.928  4185  5458 D MediaScannerServiceEx: [disAliveExtStorageRows]+196609
,03-17 08:36:43.948  4185  5458 D MediaProvider: [sendStorageAddedIfNeed]: /storage/usb : unmounted,
,03-17 08:36:43.948  4185  5458 D MediaProvider: [update][9]#1#
,03-17 08:36:43.968  5554  5554 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,03-17 08:36:43.968  4185  5458 D MediaProvider: [update][24]#0#
,03-17 08:36:43.978  4185  5458 D MediaScannerServiceEx: [disAliveExtStorageRows]--1, 0
,03-17 08:36:43.998  5554  5554 D CalendarApplication: onCreate
,03-17 08:36:44.008  5554  5554 D ProviderChangeReceiver: ---------------------------------------------------,
03-17 08:36:44.008  5554  5554 D ProviderChangeReceiver: ProviderChangeReceiver onReceive, start HtcAlertService to update notification!,
,03-17 08:36:44.018   921  1401 D Process : killProcessQuiet, pid=5061,
03-17 08:36:44.018   921  1401 I ActivityManager: Killing 5061:com.google.android.youtube/u0a176 (adj 15): empty #17
03-17 08:36:44.018   921  1401 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
03-17 08:36:44.018  5554  5576 D HtcAlertService: start to updateAlertNotification!
,03-17 08:36:44.128   921   950 I ActivityManager: Recipient 5061
,03-17 08:36:44.258   921  1401 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5577 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a,
03-17 08:36:44.258  5554  5576 D HtcAlertService: No fired or scheduled alerts
03-17 08:36:44.258  5554  5576 D HtcAlertUtils: -- cancelReminderNotification --
,03-17 08:36:44.258  5554  5576 D HtcAlertUtils: broadcastExistReminder!,
03-17 08:36:44.258  1306  1306 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,03-17 08:36:44.338  5577  5577 D PhoneMonitor: Register our PhoneStateListener
,03-17 08:36:44.358  5577  5577 V SetupWizard: Connected to Gservices successfully,
03-17 08:36:44.368   921  1712 D Process : killProcessQuiet, pid=5142
03-17 08:36:44.368   921  1712 I ActivityManager: Killing 5142:com.google.android.gm/u0a106 (adj 15): empty #17,
03-17 08:36:44.368   921  1712 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,03-17 08:36:44.368  5577  5577 D PhoneMonitor: onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,03-17 08:36:44.378  5577  5577 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,03-17 08:36:44.468   921   950 I ActivityManager: Recipient 5142
,03-17 08:36:44.508  4407  4407 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms,
03-17 08:36:44.508  4407  4407 I Kids    : [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
03-17 08:36:44.508   921   921 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
03-17 08:36:44.508   921   921 D WifiDisplayAdapter:     Client/Owner: Client
03-17 08:36:44.508   921   921 D WifiDisplayAdapter:     GroupId: 
03-17 08:36:44.508   921   921 D WifiDisplayAdapter:     Passphrase: 
03-17 08:36:44.508   921   921 D WifiDisplayAdapter:     SessionId: 0
,03-17 08:36:44.508   921   921 D WifiDisplayAdapter:     IP Address: }
03-17 08:36:44.508   921   921 E WifiStateMachine: WiFiStateMachine SCAN ALARM
03-17 08:36:44.508   921  1148 E WifiStateMachine: handleMessage: E msg.what=131143
03-17 08:36:44.508   921  1148 E WifiStateMachine: processMsg: ConnectedState
03-17 08:36:44.508   921  1148 E WifiStateMachine:  ConnectedState !CMD_START_SCAN -2 -2 ic=2 proc(ms):1 dur:73 rssi=-51 f=2457 sc=60 link=150 tx=29.5, 0.0, 0.0  rx=33.4 list=2457 [on:0 tx:0 rx:0 period:1471] from screen [on:0 period:-2088676119]
03-17 08:36:44.508   921  1148 E WifiStateMachine: processMsg: L2ConnectedState
03-17 08:36:44.518   921  1148 E WifiStateMachine:  L2ConnectedState !CMD_START_SCAN -2 -2 ic=2 proc(ms):2 dur:73 rssi=-51 f=2457 sc=60 link=150 tx=29.5, 0.0, 0.0  rx=33.4 list=2457 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-2088676119]
03-17 08:36:44.518   921  1148 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=29.46 rxSuccessRate=33.35 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-51
03-17 08:36:44.518   921  1148 E WifiStateMachine: WifiStateMachine CMD_START_SCAN with age=1458200204522 interval=40000 maxinterval=300000
03-17 08:36:44.518   921  1148 E WifiStateMachine: WifiStateMachine CMD_START_SCAN try full band scan age=1458200204522 interval=40000 maxinterval=300000
03-17 08:36:44.518   921  1148 E WifiStateMachine: WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
03-17 08:36:44.518   921  1148 E WifiStateMachine: WifiStateMachine CMD_START_SCAN full=false
03-17 08:36:44.518   921  1148 E WifiConfigStore: makeChannelList age=3600000 for "NG700"WPA_PSK max=6 bssids=1
03-17 08:36:44.518   921  1148 E WifiConfigStore: has f4:f2:6d:22:99:3e freq=2457 age=1475 ?=true
03-17 08:36:44.518   921  1148 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2457
03-17 08:36:44.518   921  1148 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY freq=2457"
03-17 08:36:44.518  1346  1346 D wpa_supplicant: wlan0: Control interface command 'SCAN TYPE=ONLY freq=2457'
03-17 08:36:44.518  1346  1346 D wpa_supplicant: wlan0: Setting scan request: 0.000000 sec
03-17 08:36:44.518  1346  1346 I wpa_supplicant: wpa_supplicant_scan enter
03-17 08:36:44.518  1346  1346 D wpa_supplicant: wlan0: Starting AP scan for wildcard SSID
03-17 08:36:44.518  1346  1346 D wpa_supplicant: WPS: Building WPS IE for Probe Request
03-17 08:36:44.518  1346  1346 D wpa_supplicant: WPS:  * Version (hardcoded 0x10)
03-17 08:36:44.518  1346  1346 D wpa_supplicant: WPS:  * Request Type
03-17 08:36:44.518  1346  1346 D wpa_supplicant: WPS:  * Config Methods (4288)
03-17 08:36:44.518  1346  1346 D wpa_supplicant: WPS:  * UUID-E
03-17 08:36:44.518  1346  1346 D wpa_supplicant: WPS:  * Primary Device Type
03-17 08:36:44.518  1346  1346 D wpa_supplicant: WPS:  * RF Bands (3)
03-17 08:36:44.518  1346  1346 D wpa_supplicant: WPS:  * Association State
03-17 08:36:44.518  1346  1346 D wpa_supplicant: WPS:  * Configuration Error (0)
03-17 08:36:44.518  1346  1346 D wpa_supplicant: WPS:  * Device Password ID (0)
03-17 08:36:44.518  1346  1346 D wpa_supplicant: WPS:  * Manufacturer
03-17 08:36:44.518  1346  1346 D wpa_supplicant: WPS:  * Model Name
03-17 08:36:44.518  1346  1346 D wpa_supplicant: WPS:  * Model Number
03-17 08:36:44.518  1346  1346 D wpa_supplicant: WPS:  * Device Name
03-17 08:36:44.518  1346  1346 D wpa_supplicant: WPS:  * Version2 (0x20)
03-17 08:36:44.518  1346  1346 D wpa_supplicant: P2P: * P2P IE header
03-17 08:36:44.518  1346  1346 D wpa_supplicant: P2P: * Capability dev=25 group=00
03-17 08:36:44.518  1346  1346 D wpa_supplicant: P2P: * Listen Channel: Regulatory Class 81 Channel 6
03-17 08:36:44.518  1346  1346 D wpa_supplicant: wlan0: Limit manual scan to specified channels
03-17 08:36:44.518  1346  1346 D wpa_supplicant: wlan0: Add radio work 'scan'@0x55687bd680
03-17 08:36:44.518  1346  1346 D wpa_supplicant: wlan0: First radio work item in the queue - schedule start immediately
03-17 0,8:36:44.518  1346  1346 D wpa_supplicant: wlan0: Starting radio work 'scan'@0x55687bd680 after 0.000054 second wait
03-17 08:36:44.518  1346  1346 D wpa_supplicant: wlan0: nl80211: scan request
03-17 08:36:44.518  1346  1346 D wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
03-17 08:36:44.518  1346  1346 D wpa_supplicant: nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
03-17 08:36:44.518  1346  1346 D wpa_supplicant: wlan0: nl80211: Scan trigger
03-17 08:36:44.518  1346  1346 D wpa_supplicant: wlan0: Event SCAN_STARTED (49) received
03-17 08:36:44.518  1346  1346 D wpa_supplicant: wlan0: Own scan request started a scan in 0.000084 seconds
03-17 08:36:44.518  1346  1346 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
03-17 08:36:44.518   921  1644 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
03-17 08:36:44.518   921  1644 E WifiMonitor: WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
03-17 08:36:44.518   921  1644 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
03-17 08:36:44.518   921  1644 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
03-17 08:36:44.518   921  1148 E WifiStateMachine: [1,458,200,204,528 ms] noteScanstart no scan source
03-17 08:36:44.518   921  1148 E WifiStateMachine: handleMessage: X
03-17 08:36:44.528  1882  5605 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
03-17 08:36:44.538   921   921 I ActivityManager: Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncScreenOnOffTimeReceiver: pid=5606 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
03-17 08:36:44.538   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8
03-17 08:36:44.538   921   921 E WifiTrafficPoller:  packet count Tx=124 Rx=192
03-17 08:36:44.538   921   921 E WifiTrafficPoller: notifying of data activity 3
03-17 08:36:44.538  1212  1212 D WIFI_ICON: WifiActivity: 3
03-17 08:36:44.538  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,03-17 08:36:44.598  1346  1346 D wpa_supplicant: nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0,
03-17 08:36:44.598  1346  1346 D wpa_supplicant: wlan0: nl80211: New scan results available
03-17 08:36:44.598  1346  1346 D wpa_supplicant: nl80211: Scan included frequencies: 2457
,03-17 08:36:44.598  1346  1346 D wpa_supplicant: wlan0: Event SCAN_RESULTS (3) received
03-17 08:36:44.598  1346  1346 I wpa_supplicant: Got an original EVENT_SCAN_RESULTS
03-17 08:36:44.598  1346  1346 D wpa_supplicant: wlan0: Scan completed in 0.083565 seconds
,03-17 08:36:44.598  1346  1346 D wpa_supplicant: nl80211: Associated on 2457 MHz
03-17 08:36:44.598  1346  1346 D wpa_supplicant: nl80211: Associated with f4:f2:6d:22:99:3e
03-17 08:36:44.598  1346  1346 D wpa_supplicant: nl80211: Received scan results (5 BSSes)
03-17 08:36:44.598  1346  1346 D wpa_supplicant: nl80211: Scan results indicate BSS status with f4:f2:6d:22:99:3e as associated
03-17 08:36:44.598  1346  1346 I wpa_supplicant: [NULL] f0:f2:6d:22:99:3e freq=2457 level=-49
03-17 08:36:44.598  1346  1346 I wpa_supplicant: [NULL] f4:f2:6d:22:99:3e freq=2457 level=-51
03-17 08:36:44.598  1346  1346 I wpa_supplicant: [NULL] 00:1f:27:54:70:c0 freq=2412 level=-67
03-17 08:36:44.598  1346  1346 I wpa_supplicant: [NULL] 00:1f:27:54:70:c1 freq=2412 level=-69
03-17 08:36:44.598  1346  1346 I wpa_supplicant: [NULL] 00:1f:27:54:dd:e3 freq=2437 level=-73
03-17 08:36:44.608   921  1148 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
03-17 08:36:44.598  1346  1346 D wpa_supplicant: wlan0: BSS: Start scan result update 3
,03-17 08:36:44.598  1346  1346 D wpa_supplicant: wlan0: BSS: Add new id 4 BSSID f0:f2:6d:22:99:3e SSID 'NG700_GUEST'
03-17 08:36:44.598  1346  1346 D wpa_supplicant: BSS: last_scan_res_used=5/32
03-17 08:36:44.598  1346  1346 D wpa_supplicant: wlan0: Scan-only results received
03-17 08:36:44.598  1346  1346 D wpa_supplicant: wlan0: Radio work 'scan'@0x55687bd680 done in 0.084503 seconds
03-17 08:36:44.598   921  1644 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 4 f0:f2:6d:22:99:3e]
03-17 08:36:44.598   921  1644 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
03-17 08:36:44.598   921  1644 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
03-17 08:36:44.598   921  1148 E WifiStateMachine: handleMessage: E msg.what=147461
03-17 08:36:44.598   921  1148 E WifiStateMachine: processMsg: ConnectedState
03-17 08:36:44.598   921  1148 E WifiStateMachine:  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
,03-17 08:36:44.598   921  1148 E WifiStateMachine: processMsg: L2ConnectedState
03-17 08:36:44.598   921  1148 E WifiStateMachine:  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
03-17 08:36:44.598   921  1148 E WifiStateMachine: processMsg: ConnectModeState
03-17 08:36:44.598   921  1148 E WifiStateMachine:  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
03-17 08:36:44.598   921  1148 E WifiStateMachine: processMsg: DriverStartedState
03-17 08:36:44.598   921  1148 E WifiStateMachine:  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
03-17 08:36:44.598   921  1148 E WifiStateMachine: processMsg: SupplicantStartedState
03-17 08:36:44.598   921  1148 E WifiStateMachine:  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
03-17 08:36:44.598   921  1148 D WifiStateMachine: [MLHD] enter handleMediaLinkEvent SupplicantStartedState
03-17 08:36:44.608   921  1148 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,03-17 08:36:44.608  1346  1346 D wpa_supplicant: wlan0: Control interface command 'LIST_DONGLES'
,03-17 08:36:44.668   921  1148 E WifiStateMachine: [1,458,200,204,674 ms] noteScanEnd no scan source,
03-17 08:36:44.668   921  1148 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
03-17 08:36:44.668  1346  1346 D wpa_supplicant: wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
03-17 08:36:44.668   921  1148 E WifiStateMachine: wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@2081c785 sup_state=COMPLETED debouncing=false
03-17 08:36:44.668   921  1148 E WifiAutoJoinController : NG700 f4:f2:6d:22:99:3e rssi=-51 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
03-17 08:36:44.668   921  1148 E WifiConfigStore: updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
03-17 08:36:44.668   921  1148 E WifiConfigStore: updateSavedNetworkHistory: HTC improve mode
03-17 08:36:44.668   921  1148 E WifiConfigStore:         got known scan result f4:f2:6d:22:99:3e key : "NG700"WPA_PSK num: 1 rssi=-51 freq=2457
03-17 08:36:44.668   921  1148 E WifiAutoJoinController : ktwtestwifi 00:1f:27:54:70:c0 rssi=-67 cap [WPA2-EAP-CCMP+TKIP][ESS] is not scored
03-17 08:36:44.668   921  1148 E WifiAutoJoinController : TEST_KTW01 00:1f:27:54:70:c1 rssi=-69 cap [WPA2-EAP-TKIP][ESS] is not scored
03-17 08:36:44.668   921  1148 E WifiAutoJoinController : RA-WINGS 00:1f:27:54:dd:e3 rssi=-73 cap [ESS] is not scored
03-17 08:36:44.668   921  1148 E WifiAutoJoinController : NG700_GUEST f0:f2:6d:22:99:3e rssi=-49 cap [WPA2-PSK-CCMP][ESS] is not scored
03-17 08:36:44.668   921  1148 E WifiAutoJoinController : ageScanResultsOut delay 40000 size 5 now 1458200204677
03-17 08:36:44.668   921  1148 E WifiAutoJoinController : newSupplicantResults size=5 known=1 true
,03-17 08:36:44.668   921  1148 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
,03-17 08:36:44.668  1346  1346 D wpa_supplicant: wlan0: Control interface command 'STATUS-NO_EVENTS'
03-17 08:36:44.668   921  1148 E WifiAutoJoinController : attemptAutoJoin() status=bssid=f4:f2:6d:22:99:3e
03-17 08:36:44.668   921  1148 E WifiAutoJoinController : ssid=NG700
03-17 08:36:44.668   921  1148 E WifiAutoJoinController : id=0
03-17 08:36:44.668   921  1148 E WifiAutoJoinController : mode=station
03-17 08:36:44.668   921  1148 E WifiAutoJoinController : pairwise_cipher=CCMP
03-17 08:36:44.668   921  1148 E WifiAutoJoinController : group_cipher=CCMP
03-17 08:36:44.668   921  1148 E WifiAutoJoinController : key_mgmt=WPA2-PSK
03-17 08:36:44.668   921  1148 E WifiAutoJoinController : wpa_state=COMPLETED
03-17 08:36:44.668   921  1148 E WifiAutoJoinController : ip_address=192.168.1.102
03-17 08:36:44.668   921  1148 E WifiAutoJoinController : p2p_device_address=92:e7:c4:e6:4c:f8
,03-17 08:36:44.668   921  1148 E WifiAutoJoinController : address=XX:XX:XX:XX:XX:XX
03-17 08:36:44.668   921  1148 E WifiAutoJoinController : uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
,03-17 08:36:44.668   921  1148 E WifiAutoJoinController : attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
,03-17 08:36:44.668   921  1148 E WifiAutoJoinController : attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-51,-127) num=(1,0)
03-17 08:36:44.668   921  1148 E WifiAutoJoinController : attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
03-17 08:36:44.668   921  1148 E WifiAutoJoinController : attemptRoam: "NG700"WPA_PSK Found f4:f2:6d:22:99:3e rssi=-51 freq=2457 Current: f4:f2:6d:22:99:3e
03-17 08:36:44.668   921  1148 D HtcWifiControlRoamOffload: : roamCandidate: nullcurrentBSSID: f4:f2:6d:22:99:3e
,03-17 08:36:44.668   921  1148 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false
03-17 08:36:44.668   921  1148 E WifiAutoJoinController : Done attemptAutoJoin status=0
03-17 08:36:44.668   921  1148 E WifiConfigStore:  writeKnownNetworkHistory() num networks:1 needWrite=false
03-17 08:36:44.668   921  1148 E WifiStateMachine: handleMessage: X
,03-17 08:36:44.708  5606  5606 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,03-17 08:36:44.708   921  1721 D PMS     : acquireWL(3f9da5f3): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5606 1000 null
,03-17 08:36:44.728   921  1514 I ActivityManager: Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=5632 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a
,03-17 08:36:44.728  5606  5630 D PowerUsageList:PowerUsageHelper: MY_DEBUG = false
,03-17 08:36:44.728  1568  5631 D WeatherUtility: Weather sync is On
,03-17 08:36:44.738  1568  5631 D WSP     : [Receiver] auto sync agent, auto sync is enabled, reset schedule
,03-17 08:36:44.748  5606  5630 D PowerUsageService: repeat time = 1458201104751,
,03-17 08:36:44.788   921   921 E WifiDataStallTracker: DATA_MONITOR_POLL true Token 1,
,03-17 08:36:44.788   921  5654 D WifiDataStallTracker: updateDataStallInfo: mDataStallTxRxSum={txSum=106 rxSum=97} preTxRxSum={txSum=56 rxSum=42}
03-17 08:36:44.788   921  5654 D WifiDataStallTracker: updateDataStallInfo: IN/OUT
,03-17 08:36:44.788   921  5654 D WifiDataStallTracker: onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,03-17 08:36:44.808   921  1710 D PMS     : acquireWL(2efff0ae): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 5523 10011 null,
,03-17 08:36:44.818  5523  5658 E SQLiteLog: (284) automatic index on view_events(_id)
,03-17 08:36:44.828   921  1157 I ActivityManager: Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=5660 uid=10028 gids={50028, 9997, 1028, 1015, 1023, 3003, 2001, 3002} abi=armeabi-v7a,
,03-17 08:36:44.828  5606  5630 I PowerUsageList:PowerUsageHelper: PowerProfile::POWER_SCREEN_FULL = 154.8
,03-17 08:36:44.838   921  1401 D PMS     : releaseWL(2efff0ae): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,03-17 08:36:44.848  5632  5656 D WeatherUtility: Weather sync is On
,03-17 08:36:44.858  5606  5630 D PowerUsageList:BatterySipperExt: gen(), null == sipper.uidObj, userId = 0
,03-17 08:36:44.868  5606  5630 D PowerUsageList:BatterySipperExt: gen(), null == sipper.uidObj, userId = 0
,03-17 08:36:44.868  5523  5523 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: },
,03-17 08:36:44.868  5523  5523 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-17 08:36:44.868  5660  5660 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 08:36:44.878  5606  5630 D PowerUsageList:BatterySipperExt: gen(), null == sipper.uidObj, userId = 0
,03-17 08:36:44.878  5632  5656 W WeatherRequest: request cur loc, but there is no sys cur
,03-17 08:36:44.878  5632  5656 W Settings: Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,03-17 08:36:44.888  5632  5656 I ActionCombine: replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal],
,03-17 08:36:44.898   921  4355 I ActivityManager: Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=5681 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a
,03-17 08:36:44.918  1491  1491 I RemoteViews: reapply : com.htc.widget.weatherclock 7 17,
,03-17 08:36:44.928   921  1720 D Process : killProcessQuiet, pid=5237,
03-17 08:36:44.928   921  1720 I ActivityManager: Killing 5237:com.google.android.partnersetup/u0a27 (adj 15): empty #17
03-17 08:36:44.928   921  1720 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-17 08:36:45.028   921  1712 I ActivityManager: Recipient 5237
,03-17 08:36:45.098  5681  5681 I EASAppSvc: [ NA ]onCreate,
,03-17 08:36:45.108  5681  5705 I VersionUtil: [ NA ]setIsFOTAing: true,
,03-17 08:36:45.118  5681  5705 I VersionUtil: [ NA ]onUpgrade: current version=100, latest version=100
,03-17 08:36:45.118  5681  5705 I VersionUtil: [ NA ]setIsFOTAing: false
,03-17 08:36:45.128  5681  5705 D HtcAdjCursorFactory: Set CursorWindow size to: 4194304 KB, Tid: 5705
,03-17 08:36:45.138  5606  5630 D PowerUsageService: calcPower(), no data
,03-17 08:36:45.148   921  4355 I ActivityManager: Killing 5183:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
,03-17 08:36:45.148   921  4355 D Process : killProcessQuiet, pid=5183
03-17 08:36:45.148   921  4355 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
03-17 08:36:45.148  5398  5706 D ORMLib  : put()
,03-17 08:36:45.288   921  2373 I ActivityManager: Recipient 5183
03-17 08:36:45.288   921  1149 D WifiService: Client connection lost with reason: 4
,03-17 08:36:45.368   921  1720 I ActivityManager: Killing 5279:com.htc.club/u0a181 (adj 15): empty #17
,03-17 08:36:45.368   921  1720 D Process : killProcessQuiet, pid=5279
03-17 08:36:45.368   921  1720 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-17 08:36:45.368   921   921 E WifiTrafficPoller: ADD_CLIENT: 8
,03-17 08:36:45.368   921  1149 D WifiService: New client listening to asynchronous messages
,03-17 08:36:45.438   921  1515 I ActivityManager: Recipient 5279,
,03-17 08:36:45.478  5681  5681 I EASAppSvc: [ NA ]onDestroy,
03-17 08:36:45.478  5681  5705 I EASAppSvc: [ NA ]> uninitEASService
,03-17 08:36:45.478  5681  5681 I EASAppSvc: [ NA ]onCreate
,03-17 08:36:45.488  5681  5705 I EASRequestController: [ NA ]release
03-17 08:36:45.488  5681  5714 I VersionUtil: [ NA ]setIsFOTAing: true
03-17 08:36:45.488  5681  5714 I VersionUtil: [ NA ]onUpgrade: current version=100, latest version=100
,03-17 08:36:45.488  5681  5714 I VersionUtil: [ NA ]setIsFOTAing: false
,03-17 08:36:45.498  5681  5705 D EASPublicBinder: [ NA ]release
03-17 08:36:45.498  5681  5705 D TaskBinder: [ NA ]release
,03-17 08:36:45.498  5681  5705 D TaskBinder: [ NA ]release
03-17 08:36:45.498  5681  5705 I EASAppSvc: [ NA ]< uninitEASService
03-17 08:36:45.498  1433  1433 D TelephonyReceiver: bind: true
,03-17 08:36:45.508  5398  5715 D ORMLib  : put(),
,03-17 08:36:45.518   921  1401 I ActivityManager: Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=5724 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=arm64-v8a
,03-17 08:36:45.518  4235  4718 D GenericMessagesProvider: query uri: content://htc-messages/wappush/count,
,03-17 08:36:45.518  4235  4718 E SQLiteLog: (14) cannot open file at line 30058 of [9491ba7d73]
,03-17 08:36:45.518  4235  4718 E SQLiteLog: (14) os_unix.c:30058: (2) open(/data/data/com.htc.sense.mms/databases/wappush.db) - 
03-17 08:36:45.518  4235  4718 E SQLiteConnection: DB info: sqlite3_open_v2, path: /data/data/com.htc.sense.mms/databases/wappush.db, flag: 1, ret: 14
03-17 08:36:45.518  4235  4718 E SQLiteConnection: DB info: errno = 2, errno message = No such file or directory
,03-17 08:36:45.528  4235  4718 E SQLiteDatabase: Failed to open database '/data/data/com.htc.sense.mms/databases/wappush.db'.
03-17 08:36:45.528  4235  4718 E SQLiteDatabase: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
03-17 08:36:45.528  4235  4718 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 08:36:45.528  4235  4718 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
03-17 08:36:45.528  4235  4718 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
03-17 08:36:45.528  4235  4718 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-17 08:36:45.528  4235  4718 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-17 08:36:45.528  4235  4718 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-17 08:36:45.528  4235  4718 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
03-17 08:36:45.528  4235  4718 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
03-17 08:36:45.528  4235  4718 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
03-17 08:36:45.528  4235  4718 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:712)
03-17 08:36:45.528  4235  4718 E SQLiteDatabase: 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
03-17 08:36:45.528  4235  4718 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:960)
03-17 08:36:45.528  4235  4718 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
03-17 08:36:45.528  4235  4718 E SQLiteDatabase: 	at android.content.ContentProvider,Native.onTransact(ContentProviderNative.java:142)
03-17 08:36:45.528  4235  4718 E SQLiteDatabase: 	at android.os.Binder.execTransact(Binder.java:454)
03-17 08:36:45.528  4235  4718 W System.err: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
03-17 08:36:45.528  4235  4718 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 08:36:45.528  4235  4718 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
03-17 08:36:45.528  4235  4718 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
03-17 08:36:45.528  4235  4718 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-17 08:36:45.528  4235  4718 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-17 08:36:45.528  4235  4718 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-17 08:36:45.528  4235  4718 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
03-17 08:36:45.528  4235  4718 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
03-17 08:36:45.528  4235  4718 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
03-17 08:36:45.528  4235  4718 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:712)
03-17 08:36:45.528  4235  4718 W System.err: 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
03-17 08:36:45.528  4235  4718 W System.err: 	at android.content.ContentProvider.query(ContentProvider.java:960)
03-17 08:36:45.528  4235  4718 W System.err: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
03-17 08:36:45.528  4235  4718 W System.err: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
03-17 08:36:45.528  4235  4718 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
03-17 08:36:45.528  1433  1433 D TelephonyReceiver: switchBindHtcMsgCursor: null
,03-17 08:36:45.538   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8,
03-17 08:36:45.538   921   921 E WifiTrafficPoller:  packet count Tx=130 Rx=195
03-17 08:36:45.538  5681  5681 I EASAppSvc: [ NA ]onDestroy
03-17 08:36:45.538  5681  5714 I EASAppSvc: [ NA ]> uninitEASService
,03-17 08:36:45.538  5681  5714 I EASRequestController: [ NA ]release,
,03-17 08:36:45.558  5681  5714 D EASPublicBinder: [ NA ]release
03-17 08:36:45.558  5681  5714 D TaskBinder: [ NA ]release
03-17 08:36:45.558  5681  5714 D TaskBinder: [ NA ]release
03-17 08:36:45.558  5681  5714 I EASAppSvc: [ NA ]< uninitEASService
,03-17 08:36:45.558   921   951 I ActivityManager: Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=5749 uid=10066 gids={50066, 9997, 3003} abi=arm64-v8a
,03-17 08:36:45.578  5724  5724 D DFPI.PIReciver: onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,03-17 08:36:45.588  5724  5773 I DFPI.ApkInstallService: onHandleIntent
03-17 08:36:45.588  5724  5773 I DFPI.ApkInstallService: Media Scan Finished Case 
,03-17 08:36:45.598  5724  5773 D DFPI.ApkInstallService: check CID = HTC__102,
03-17 08:36:45.598  5724  5773 I DFPI.ApkInstallService: There is no Demo.apk in sd card or phone storage
,03-17 08:36:45.598   921  1721 D Process : killProcessQuiet, pid=5343
03-17 08:36:45.598   921  1721 I ActivityManager: Killing 5343:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17
,03-17 08:36:45.598   921  1721 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-17 08:36:45.658   921  1515 I ActivityManager: Recipient 5343
,03-17 08:36:45.708   921   950 D Process : killProcessQuiet, pid=5375
,03-17 08:36:45.708   921   950 I ActivityManager: Killing 5375:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
03-17 08:36:45.708   921   950 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-17 08:36:45.718  5398  5776 D ORMLib  : put(),
,03-17 08:36:45.838   921  2373 I ActivityManager: Recipient 5375,
,03-17 08:36:45.928  5660  5713 E SQLiteLog: (283) recovered 15 frames from WAL file /data/data/com.htc.album/databases/MMexternal.db-wal,
,03-17 08:36:45.938   921  1712 I ActivityManager: Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=5777 uid=10049 gids={50049, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,03-17 08:36:45.948   921  1137 V AlarmManager: sending alarm PendingIntent{1cc287c2: PendingIntentRecord{63d19d3 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1458200205745, Int=0
,03-17 08:36:45.948   921  1710 D Process : killProcessQuiet, pid=5214
03-17 08:36:45.948   921  1710 I ActivityManager: Killing 5214:com.htc.sense.news/u0a74 (adj 15): empty #17
03-17 08:36:45.948   921  1710 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-17 08:36:46.038   921  1712 I ActivityManager: Recipient 5214,
,03-17 08:36:46.038   921  1148 E WifiStateMachine: handleMessage: E msg.what=131155,
03-17 08:36:46.038   921  1148 E WifiStateMachine: processMsg: ConnectedState
03-17 08:36:46.048   921  1148 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-51 f=2457 sc=60 link=150 tx=29.5, 0.0, 0.0  rx=33.4 bcn=0 [on:0 tx:0 rx:0 period:1523] from screen [on:0 period:-2088674588] gl hn u24 rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
03-17 08:36:46.048   921  1148 E WifiStateMachine: processMsg: L2ConnectedState
,03-17 08:36:46.048   921  1148 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-51 f=2457 sc=60 link=150 tx=29.5, 0.0, 0.0  rx=33.4 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-2088674587] gl hn u24 rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
03-17 08:36:46.048   921  1148 E WifiStateMachine:  get link layer stats 0
03-17 08:36:46.048   921  1148 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,03-17 08:36:46.048  1346  1346 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
,03-17 08:36:46.048  1346  1346 I wpa_supplicant: environment dirty rate=12 [8][1][0],
03-17 08:36:46.048   921  1148 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 150
03-17 08:36:46.048   921  1148 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-53 linkspeed=150
03-17 08:36:46.048   921  1148 E WifiConfigStore: updateConfiguration freq=2457 BSSID=f4:f2:6d:22:99:3e RSSI=-52 "NG700"WPA_PSK
03-17 08:36:46.048   921  1148 E WifiStateMachine: calculateWifiScore freq=2457 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=18.73 txretriesrate=0.00 rxrate=19.68 userTriggerdPenalty0
03-17 08:36:46.048   921  1148 E WifiStateMachine:  good link -> stuck count =0
03-17 08:36:46.048   921  1148 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 60
03-17 08:36:46.048   921  1148 E WifiStateMachine:  isHighRSSI       ---> score=65
,03-17 08:36:46.058   921  1148 E WifiStateMachine: handleMessage: X,
03-17 08:36:46.058   921  1166 D WifiWatchdogStateMachine: RSSI current: 3 new: -53, 3
,03-17 08:36:46.068  1212  1212 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3
03-17 08:36:46.068  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,03-17 08:36:46.108   921  1719 I ActivityManager: Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=5801 uid=10079 gids={50079, 9997, 5001, 1028, 1015} abi=arm64-v8a,
,03-17 08:36:46.128   921  1021 W BroadcastQueue: Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_MEDIA due to registered receiver BroadcastFilter{371cc341 u0 ReceiverList{2a065a28 5777 com.htc.musicenhancer/10049/u0 remote:3ca3f04b}}
,03-17 08:36:46.138   921   950 D VoldConnector: SND -> {27 volume mkdirs /storage/ext_sd/Android/data/com.htc.musicenhancer/cache/},
03-17 08:36:46.138   383   657 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.htc.musicenhancer/cache/
03-17 08:36:46.138  5777  5815 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache,
,03-17 08:36:46.158  5801  5801 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED,
,03-17 08:36:46.158  5801  5801 I SoundPicker: SoundPickerReceiver [onReceive] startService
,03-17 08:36:46.158  5801  5826 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
03-17 08:36:46.158  5801  5826 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true
03-17 08:36:46.158  5801  5826 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
,03-17 08:36:46.178   921  1710 D PMS     : acquireWL(147af0d4): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4974 10112 null,
03-17 08:36:46.178  5801  5826 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
,03-17 08:36:46.178  5801  5826 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1,
03-17 08:36:46.178  5801  5826 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
03-17 08:36:46.178  5801  5826 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
,03-17 08:36:46.178  5801  5826 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
03-17 08:36:46.178  5801  5826 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
03-17 08:36:46.178  5801  5826 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
03-17 08:36:46.178  5801  5826 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
03-17 08:36:46.178  5801  5826 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
03-17 08:36:46.178  5801  5826 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
,03-17 08:36:46.178  5801  5826 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
03-17 08:36:46.178  5801  5826 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
03-17 08:36:46.178  5801  5826 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
03-17 08:36:46.178  5801  5826 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
03-17 08:36:46.178  5801  5826 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
,03-17 08:36:46.178  5801  5826 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
03-17 08:36:46.178  5801  5826 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
,03-17 08:36:46.178  5801  5826 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
03-17 08:36:46.178  5801  5826 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
03-17 08:36:46.178  5801  5826 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
03-17 08:36:46.178  5801  5826 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
,03-17 08:36:46.188  5801  5826 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
03-17 08:36:46.188  5801  5826 W SoundPicker: TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
03-17 08:36:46.188  5801  5826 I SoundPicker: TurnFileToMediaUriService [checkFileExistence]
,03-17 08:36:46.188  5801  5826 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
03-17 08:36:46.188  5801  5826 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
03-17 08:36:46.188  5801  5826 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,03-17 08:36:46.188  5801  5826 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,03-17 08:36:46.198  5801  5826 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,03-17 08:36:46.198  5801  5826 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:46.198  5801  5826 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
03-17 08:36:46.198  5801  5826 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
,03-17 08:36:46.198  5801  5826 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,03-17 08:36:46.228   921  1716 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=5829 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
,03-17 08:36:46.248   439   439 I art     : Explicit concurrent mark sweep GC freed 8653(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 174us total 19.513ms
,03-17 08:36:46.258  4974  4974 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-17 08:36:46.258  4974  4974 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 08:36:46.258   921  2373 D PMS     : releaseWL(147af0d4): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,03-17 08:36:46.258   439   439 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 160us total 17.060ms
,03-17 08:36:46.278   439   439 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 150us total 16.003ms
,03-17 08:36:46.348   921  1718 I art     : Explicit concurrent mark sweep GC freed 23918(1150KB) AllocSpace objects, 2(368KB) LOS objects, 33% free, 16MB/24MB, paused 1.777ms total 148.749ms
,03-17 08:36:46.348  5801  5826 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,03-17 08:36:46.348  5801  5826 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:46.348  5801  5826 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:46.348  5801  5826 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
,03-17 08:36:46.348  5801  5826 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
03-17 08:36:46.348  5801  5826 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,03-17 08:36:46.358  5801  5826 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,03-17 08:36:46.358  5801  5826 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:46.358  5801  5826 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:46.358  5801  5826 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
,03-17 08:36:46.358  5801  5826 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4,
03-17 08:36:46.358  5801  5826 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,03-17 08:36:46.368  5801  5826 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac,
,03-17 08:36:46.368  5801  5826 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,03-17 08:36:46.368  5801  5826 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
03-17 08:36:46.368  5801  5826 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
03-17 08:36:46.368  5801  5826 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
,03-17 08:36:46.368  5801  5826 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,03-17 08:36:46.378  5801  5826 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac,
,03-17 08:36:46.378  5801  5826 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,03-17 08:36:46.378  5801  5826 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac,
,03-17 08:36:46.378  5801  5826 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
03-17 08:36:46.378  5801  5826 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,03-17 08:36:46.388  5801  5826 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,03-17 08:36:46.388  5801  5826 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,03-17 08:36:46.388  5801  5826 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
03-17 08:36:46.388  5801  5826 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
03-17 08:36:46.388  5801  5826 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,03-17 08:36:46.398  5801  5826 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac,
,03-17 08:36:46.398  5801  5826 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
03-17 08:36:46.398  5801  5826 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
03-17 08:36:46.398  5801  5826 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
03-17 08:36:46.398  5801  5826 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104,
,03-17 08:36:46.398  5801  5826 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,03-17 08:36:46.398  5801  5826 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
03-17 08:36:46.398  5801  5826 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
,03-17 08:36:46.398  5801  5826 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
03-17 08:36:46.398  5801  5826 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,03-17 08:36:46.408  5801  5826 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,03-17 08:36:46.408  5801  5826 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,03-17 08:36:46.408  5801  5826 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,03-17 08:36:46.468  4974  4974 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-17 08:36:46.478   921   951 D LocationManagerService: getProviders()=[passive]
,03-17 08:36:46.528   921  1514 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5858 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a,
,03-17 08:36:46.538   921  1515 D Process : killProcessQuiet, pid=4998,
03-17 08:36:46.538   921  1515 I ActivityManager: Killing 4998:com.htc.mobiledata:remote/u0a46 (adj 15): empty #17,
03-17 08:36:46.538   921  1515 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 ,
03-17 08:36:46.538   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8
03-17 08:36:46.538   921   921 E WifiTrafficPoller:  packet count Tx=131 Rx=196
,03-17 08:36:46.598  4974  4974 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-17 08:36:46.598  4974  4974 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-17 08:36:46.648   921  1720 I ActivityManager: Recipient 4998,
,03-17 08:36:46.658   921  1401 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService, state=2, flag=1, pid=4407, uid=10024, userID:0
,03-17 08:36:46.658   921  1712 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateActivity, state=2, flag=1, pid=4407, uid=10024, userID:0
03-17 08:36:46.658   921  1719 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$SecretCodeReceiver, state=2, flag=1, pid=4407, uid=10024, userID:0
,03-17 08:36:46.658   921  4355 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$Receiver, state=2, flag=1, pid=4407, uid=10024, userID:0
,03-17 08:36:46.728   921  4355 D PMS     : releaseWL(3f9da5f3): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null,
,03-17 08:36:46.748   921   951 D Process : killProcessQuiet, pid=5430,
03-17 08:36:46.748   921   951 I ActivityManager: Killing 5430:com.nero.android.htc.sync/u0a5 (adj 15): empty #17
,03-17 08:36:46.758   921   951 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.attachApplicationLocked:6650 
,03-17 08:36:46.828   921  1515 I ActivityManager: Recipient 5430
,03-17 08:36:46.828   921  1149 D WifiService: Client connection lost with reason: 4
,03-17 08:36:46.918  1722  2168 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,03-17 08:36:46.918  1433  1433 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 08:36:46.938  1568  5880 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
03-17 08:36:46.938  1568  5880 I [PluginManager]RegisterService: handle notify Blinkfeed plugin client changed
,03-17 08:36:46.938  1722  2168 D AccTypeManager: Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,03-17 08:36:46.948   921  1140 W SystemReader: Cannot find grip_rejection_width, use default value instead
,03-17 08:36:46.958  1491  2067 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,03-17 08:36:46.968   921  1020 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
03-17 08:36:46.968  1491  2067 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,03-17 08:36:46.968  1491  1491 W Prism.AllAppsManager: AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,03-17 08:36:46.968  1491  1491 I Launcher: Deferring update until onResume
,03-17 08:36:46.968  1491  1491 D Launcher: waitUntilResume // bindAppsUpdated
,03-17 08:36:46.978  1433  1433 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,03-17 08:36:46.978  1722  2168 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,03-17 08:36:46.998   921  1719 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5884 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
,03-17 08:36:46.998  1722  2168 E ExternalAccountType: Unsupported attribute readOnly
,03-17 08:36:47.068  4730  5907 D Settings:HtcWirelessFeatureFlags: id/is att sku: 118/false
,03-17 08:36:47.078   921   921 W PackageManager: Unable to load service info ResolveInfo{310a5193 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
03-17 08:36:47.078   921   921 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
03-17 08:36:47.078   921   921 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
03-17 08:36:47.078   921   921 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
03-17 08:36:47.078   921   921 W PackageManager: 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
03-17 08:36:47.078   921   921 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
03-17 08:36:47.078   921   921 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
03-17 08:36:47.078   921   921 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
03-17 08:36:47.078   921   921 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739)
03-17 08:36:47.078   921   921 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-17 08:36:47.078   921   921 W PackageManager: 	at android.os.Looper.loop(Looper.java:155)
03-17 08:36:47.078   921   921 W PackageManager: 	at com.android.server.SystemServer.run(SystemServer.java:324)
03-17 08:36:47.078   921   921 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:225)
03-17 08:36:47.078   921   921 W PackageManager: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 08:36:47.078   921   921 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 08:36:47.078   921   921 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
03-17 08:36:47.078   921   921 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,03-17 08:36:47.098  1810  1810 V GmsNetworkLocationProvi: DISABLE
,03-17 08:36:47.108  1810  1810 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,03-17 08:36:47.108   921   951 I PackageManager:  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=5884, uid=10072, userID:0
,03-17 08:36:47.118  5884  5884 W global  : [apache-http] Connection GC has been deprecated!
,03-17 08:36:47.128  4730  5907 E Settings:HtcWrapHeaderInfo: no such activity!
03-17 08:36:47.138   921  1401 D PMS     : acquireWL(26eef5fd): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1810 10024 WorkSource{10024 com.google.android.gms}
03-17 08:36:47.138  5884  5884 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,03-17 08:36:47.138   921   950 D PMS     : releaseWL(26eef5fd): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms},
,03-17 08:36:47.148  5884  5884 W global  : [apache-http] Connection GC has been deprecated!,
03-17 08:36:47.148   921   921 I BackupManagerService: Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService},
,03-17 08:36:47.148   921  1020 D LocationProviderProxy: applying state to connected service
,03-17 08:36:47.148   921  1020 D LocationProviderProxy: applying state to connected service
03-17 08:36:47.158   921  1716 D PMS     : acquireWL(289be7b5): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1810 10024 WorkSource{10024 com.google.android.gms},
,03-17 08:36:47.158   921  1157 D PMS     : releaseWL(289be7b5): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,03-17 08:36:47.158   921  1020 D PMS     : acquireWL(35f8fe4a): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1810 10024 WorkSource{10024 com.google.android.gms}
,03-17 08:36:47.158   921   921 D PMS     : acquireWL(c0dfe97): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1810 10024 WorkSource{10024 com.google.android.gms}
,03-17 08:36:47.158   921  1720 D PMS     : releaseWL(35f8fe4a): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,03-17 08:36:47.168   921  1719 D PMS     : releaseWL(c0dfe97): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,03-17 08:36:47.168  4730  5891 W Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub: The wrap header doesn't exist in header list.
,03-17 08:36:47.178  3496  3571 I HtcModeClient: handler message = 4011,
03-17 08:36:47.178  3496  3571 E HtcModeClient: Check connection and retry 5 times.
,03-17 08:36:47.178  4730  5891 E Settings:HtcWrapHeaderInfo: updateDevelopment, bPrefShow = true
,03-17 08:36:47.188  4730  5891 E Settings:HtcUmcWidgetEnabler: isSupportMusicChannel(): false
,03-17 08:36:47.198  4730  5891 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportRecentAppsButton]hasNavigationBar:true
03-17 08:36:47.198  4730  5891 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportRecentAppsButton]hasRecentAppsKey:false
03-17 08:36:47.198  4730  5891 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportRecentAppsButton]support         :false
,03-17 08:36:47.198  4730  5891 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasNavigationBar:true,
03-17 08:36:47.198  4730  5891 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasMenuKey      :false
03-17 08:36:47.198  4730  5891 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasRecentAppKey :false
03-17 08:36:47.198  4730  5891 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasBackKey      :false
03-17 08:36:47.198  4730  5891 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasHomeKey      :false
03-17 08:36:47.198  4730  5891 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]support         :false
,03-17 08:36:47.208   921  1515 D Process : killProcessQuiet, pid=5498
03-17 08:36:47.208   921  1515 I ActivityManager: Killing 5498:com.htc.backupreset/1000 (adj 15): empty #17,
03-17 08:36:47.208   921  1515 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-17 08:36:47.228  5884  5884 W global  : [apache-http] Connection GC has been deprecated!,
,03-17 08:36:47.248  5884  5884 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.,
,03-17 08:36:47.298   921  1721 I ActivityManager: Recipient 5498
,03-17 08:36:47.318   921  1716 I ActivityManager: Cannot resolve ContentProvider=com.htc.vowifi,
03-17 08:36:47.318  4730  5891 E ActivityThread: Failed to find provider info for com.htc.vowifi,
03-17 08:36:47.318  4730  5891 E Settings:HtcVoWifiWidgetEnabler: isSupportVoWifi: null
,03-17 08:36:47.338  4730  5888 W Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub: The wrap header doesn't exist in header list.,
03-17 08:36:47.338  4730  5888 E Settings:HtcWrapHeaderInfo: updateDevelopment, bPrefShow = true,
,03-17 08:36:47.338  4730  5888 E Settings:HtcUmcWidgetEnabler: isSupportMusicChannel(): false,
,03-17 08:36:47.338  4730  5888 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportRecentAppsButton]hasNavigationBar:true
03-17 08:36:47.338  4730  5888 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportRecentAppsButton]hasRecentAppsKey:false
03-17 08:36:47.338  4730  5888 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportRecentAppsButton]support         :false
,03-17 08:36:47.348  4730  5888 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasNavigationBar:true
03-17 08:36:47.348  4730  5888 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasMenuKey      :false
03-17 08:36:47.348  4730  5888 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasRecentAppKey :false
03-17 08:36:47.348  4730  5888 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasBackKey      :false
03-17 08:36:47.348  4730  5888 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasHomeKey      :false
03-17 08:36:47.348  4730  5888 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]support         :false
,03-17 08:36:47.358   921  4355 I ActivityManager: Cannot resolve ContentProvider=com.htc.vowifi
,03-17 08:36:47.358  4730  5888 E Settings:HtcVoWifiWidgetEnabler: isSupportVoWifi: null
03-17 08:36:47.358  4730  5888 E ActivityThread: Failed to find provider info for com.htc.vowifi
,03-17 08:36:47.368   921  1157 I ActivityManager: Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5926 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,03-17 08:36:47.388  5884  5884 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-17 08:36:47.388  5884  5884 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-17 08:36:47.408   921  1712 I PackageManager:  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=5884, uid=10072, userID:0,
,03-17 08:36:47.418  5926  5926 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-17 08:36:47.418  5926  5926 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 08:36:47.438  5884  5884 D Finsky  : [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U],
03-17 08:36:47.438  5884  5884 D Finsky  : [1] 2.run: Finished loading 1 libraries.
,03-17 08:36:47.438  5884  5884 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4,
,03-17 08:36:47.438  5926  5926 I MultiDex: VM with version 2.1.0 has multidex support
03-17 08:36:47.438  5926  5926 I MultiDex: install
03-17 08:36:47.438  5926  5926 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-17 08:36:47.468  4407  5953 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,03-17 08:36:47.468  5926  5926 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
03-17 08:36:47.468  5884  5884 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,03-17 08:36:47.478   921  4355 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5954 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,03-17 08:36:47.478  4407  5953 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
03-17 08:36:47.488   921  1716 D PMS     : acquireWL(260e2ab4): PARTIAL_WAKE_LOCK  Icing 0x1 4407 10024 WorkSource{10024 com.google.android.gms}
,03-17 08:36:47.508  5926  5926 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
,03-17 08:36:47.508  5926  5926 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3c7acb3f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-17 08:36:47.508   921  1515 I ActivityManager: Killing 5554:com.htc.calendar/u0a10 (adj 15): empty #17
03-17 08:36:47.508  5926  5926 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
03-17 08:36:47.508   921  1515 D Process : killProcessQuiet, pid=5554
03-17 08:36:47.508   921  1515 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-17 08:36:47.538   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 7,
03-17 08:36:47.538  1212  1212 D WIFI_ICON: WifiActivity: 1
03-17 08:36:47.538   921   921 E WifiTrafficPoller:  packet count Tx=131 Rx=197
03-17 08:36:47.538  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
03-17 08:36:47.538   921   921 E WifiTrafficPoller: notifying of data activity 1
,03-17 08:36:47.598   921  4355 I ActivityManager: Recipient 5554,
,03-17 08:36:47.638  5954  5954 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 08:36:47.688  4407  4962 I Icing   : Storage manager: low false usage 2.00MB avail 5.78GB capacity 7.95GB
,03-17 08:36:47.728  4407  4962 W Icing   : Received bad json for section weights override -- ignoring.,
,03-17 08:36:47.748  4407  4962 W Icing   : Received bad json for corpus context scoring override -- ignoring.,
03-17 08:36:47.748  4407  4962 W Icing   : Received bad json for section weights override -- ignoring.,
,03-17 08:36:47.748  4407  4962 W Icing   : Received bad json for corpus context scoring override -- ignoring.
,03-17 08:36:47.798  1882  1904 I art     : Explicit concurrent mark sweep GC freed 9690(490KB) AllocSpace objects, 3(252KB) LOS objects, 49% free, 4MB/8MB, paused 677us total 36.216ms
,03-17 08:36:47.888  4185  4209 I art     : Background sticky concurrent mark sweep GC freed 2950(162KB) AllocSpace objects, 0(0B) LOS objects, 6% free, 3MB/4MB, paused 7.031ms total 12.599ms
,03-17 08:36:47.888  4407  4962 E Icing   : Loading extension by file descriptor -1 failed
,03-17 08:36:47.928   921  1401 D Process : killProcessQuiet, pid=5577
03-17 08:36:47.928   921  1401 I ActivityManager: Killing 5577:com.google.android.setupwizard/u0a77 (adj 15): empty #17
03-17 08:36:47.928   921  1401 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-17 08:36:48.038   921   950 I ActivityManager: Recipient 5577
,03-17 08:36:48.168   921  2373 D PMS     : acquireWL(35881c4c): PARTIAL_WAKE_LOCK  AsyncService 0x1 5954 10167 null
,03-17 08:36:48.178   921  1514 D PMS     : releaseWL(35881c4c): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
03-17 08:36:48.178   921  1721 D PMS     : acquireWL(29cd69aa): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 5954 10167 null
,03-17 08:36:48.198  5829  5994 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,03-17 08:36:48.218   921  1721 D PMS     : releaseWL(29cd69aa): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,03-17 08:36:48.248   921  1137 V AlarmManager: sending alarm PendingIntent{d658402: PendingIntentRecord{3dfe0113 com.android.vending startService}}, i=null, t=0, cnt=1, w=1458200208255, Int=0,
,03-17 08:36:48.258  5884  5884 V Finsky  : [1] GearheadStateMonitor.onReady: sIsProjecting:false
,03-17 08:36:48.268  5884  5884 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene,
,03-17 08:36:48.278  1491  1491 D Prism.PackageStateRece_: action: android.intent.action.PACKAGE_ADDED,
03-17 08:36:48.278  1568  6000 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.test.thalitest
,03-17 08:36:48.278  1568  6000 I [PluginManager]RegisterService: handle notify Blinkfeed plugin client changed
,03-17 08:36:48.328   921  1720 I ActivityManager: Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=6003 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a,
,03-17 08:36:48.358  1882  1882 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-17 08:36:48.388  4407  4962 I Icing   : updateResources: need to parse f{com.google.android.gms}
,03-17 08:36:48.408  1882  3488 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
03-17 08:36:48.408  1882  3488 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-17 08:36:48.408  1882  3488 I GLSUser : [GLSUser] Extracting token using key: Auth
03-17 08:36:48.408  1882  3488 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-17 08:36:48.418  6003  6003 I DeviceManagement: DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6003 dbg=false s=true
,03-17 08:36:48.418  1882  3488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 08:36:48.418  6003  6003 I DeviceManagement: PackageUpdateReceiver: vvv Package added: [com.test.thalitest]
,03-17 08:36:48.448  5884  5884 W Finsky  : [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-17 08:36:48.458  5829  5994 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 254 ms] updated apps [took 254 ms] ,
,03-17 08:36:48.468  1491  2067 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
03-17 08:36:48.468  1491  2067 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@3508dd95 +
03-17 08:36:48.468   921  1515 I ActivityManager: Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=6025 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a
03-17 08:36:48.468  1491  2067 I Prism.WidgetManager: onLoadItems() +
,03-17 08:36:48.468   921  1710 D Process : killProcessQuiet, pid=5606,
,03-17 08:36:48.468   921  1710 I ActivityManager: Killing 5606:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
03-17 08:36:48.468   921  1710 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
03-17 08:36:48.478  1882  1882 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 08:36:48.498  1491  2067 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-17 08:36:48.528   921  1157 I ActivityManager: Recipient 5606
,03-17 08:36:48.538   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 7
03-17 08:36:48.538   921   921 E WifiTrafficPoller:  packet count Tx=131 Rx=197
03-17 08:36:48.538   921   921 E WifiTrafficPoller: notifying of data activity 0
,03-17 08:36:48.538  1212  1212 D WIFI_ICON: WifiActivity: 0
03-17 08:36:48.538  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,03-17 08:36:48.608  1882  1904 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
03-17 08:36:48.608  1882  1904 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-17 08:36:48.608  1882  1904 I GLSUser : [GLSUser] Extracting token using key: Auth
03-17 08:36:48.608  1882  1904 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-17 08:36:48.618  1882  1904 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-17 08:36:48.628  6025  6025 D HtcCupdReceiver(Provider):  @@@@@ receive action=android.intent.action.PACKAGE_ADDED
,03-17 08:36:48.668  4407  4962 I art     : Explicit concurrent mark sweep GC freed 28952(2MB) AllocSpace objects, 24(480KB) LOS objects, 47% free, 4MB/8MB, paused 2.110ms total 79.325ms
,03-17 08:36:48.708  1491  2067 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,03-17 08:36:48.768   921  1716 I art     : Explicit concurrent mark sweep GC freed 22871(1209KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/25MB, paused 1.447ms total 146.563ms,
,03-17 08:36:48.788   921  1712 I ActivityManager: Killing 5632:com.htc.widget.hmsproc2/u0a40 (adj 15): empty #17
03-17 08:36:48.788   921  1712 D Process : killProcessQuiet, pid=5632
03-17 08:36:48.788   921  1712 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-17 08:36:48.798  4594  4804 I jxcore-log: Unit Test app is loaded
03-17 08:36:48.798  4594  4804 I jxcore-log: 
,03-17 08:36:48.808  4594  4804 I jxcore-log: INFO thaliMobileNativeWrapper networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
03-17 08:36:48.808  4594  4804 I jxcore-log: 
,03-17 08:36:48.808  4594  4804 D BluetoothAdapter: 914685262: getState(). Returning 12
,03-17 08:36:48.818  4594  4804 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,03-17 08:36:48.818  4594  4804 I jxcore-log: INFO testUtils BLE multiple advertisement supported
03-17 08:36:48.818  4594  4804 I jxcore-log: 
,03-17 08:36:48.828  4594  4804 I jxcore-log: My device name is: HTC-HTC One M8s,
03-17 08:36:48.828  4594  4804 I jxcore-log: 
,03-17 08:36:48.838  4594  4594 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74),
,03-17 08:36:48.848  1491  2067 W asset   : Copying FileAsset 0x559e966380 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,03-17 08:36:48.888   921  4355 I ActivityManager: Recipient 5632
,03-17 08:36:48.908  1491  2067 E Prism.WidgetManager: The same lists. No need to update. skip it.
,03-17 08:36:48.908  1491  2067 I Prism.WidgetManager: onLoadItems() -
03-17 08:36:48.908  1491  2067 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@3508dd95 -
03-17 08:36:48.908  4407  4962 I Icing   : Internal init done: storage state 0
,03-17 08:36:48.928  4407  4962 I Icing   : Post-init done,
,03-17 08:36:48.928  4407  6048 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest,
03-17 08:36:48.928  4407  4962 I Icing   : updateResources: need to parse f{com.google.android.gms}
,03-17 08:36:48.938   921  4355 D PMS     : acquireWL(3caf9a57): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4407 10024 null
,03-17 08:36:48.938  4407  4407 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,03-17 08:36:48.938  4407  4407 D ChimeraModuleLdr: Loading module APK com.google.android.play.games
,03-17 08:36:48.948   921  1716 D PMS     : releaseWL(260e2ab4): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,03-17 08:36:48.978  1882  1882 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 08:36:48.988  1433  2172 D PhoneApp: EVENT_QUERY_MO_PACKAGES
03-17 08:36:48.988  1433  2172 D PhoneApp: -- N1 =0
,03-17 08:36:48.988  1433  2172 D PhoneApp: -- N2 =0
,03-17 08:36:48.998  1433  2172 D PhoneApp: -- N3 =0
,03-17 08:36:49.008  1882  2013 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,03-17 08:36:49.008  1882  2013 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-17 08:36:49.008  1882  2013 I GLSUser : [GLSUser] Extracting token using key: Auth
03-17 08:36:49.008  1882  2013 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-17 08:36:49.008  1882  2013 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 08:36:49.028  5884  5884 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-17 08:36:49.048   921  1148 E WifiStateMachine: handleMessage: E msg.what=131155,
03-17 08:36:49.048   921  1148 E WifiStateMachine: processMsg: ConnectedState
03-17 08:36:49.058   921  1148 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-53 f=2457 sc=60 link=150 tx=18.7, 0.0, 0.0  rx=19.7 bcn=0 [on:0 tx:0 rx:0 period:2993] from screen [on:0 period:-2088671578] gl hn u24 rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
03-17 08:36:49.058   921  1148 E WifiStateMachine: processMsg: L2ConnectedState
03-17 08:36:49.058   921  1148 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-53 f=2457 sc=60 link=150 tx=18.7, 0.0, 0.0  rx=19.7 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-2088671576] gl hn u24 rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,03-17 08:36:49.058   921  1148 E WifiStateMachine:  get link layer stats 0
03-17 08:36:49.058   921  1148 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
03-17 08:36:49.058  1346  1346 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
,03-17 08:36:49.068  1346  1346 I wpa_supplicant: environment dirty rate=0 [0][0][0]
03-17 08:36:49.068   921  1148 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 150
03-17 08:36:49.068   921  1148 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-53 linkspeed=150
03-17 08:36:49.068  1212  1212 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3
03-17 08:36:49.068   921  1148 E WifiConfigStore: updateConfiguration freq=2457 BSSID=f4:f2:6d:22:99:3e RSSI=-52 "NG700"WPA_PSK
,03-17 08:36:49.068  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
03-17 08:36:49.068   921  1148 E WifiStateMachine: calculateWifiScore freq=2457 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=9.37 txretriesrate=0.00 rxrate=11.84 userTriggerdPenalty0
03-17 08:36:49.068   921  1148 E WifiStateMachine:  good link -> stuck count =0
03-17 08:36:49.068   921  1148 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 60
03-17 08:36:49.068   921  1148 E WifiStateMachine:  isHighRSSI       ---> score=65
03-17 08:36:49.068   921  1148 E WifiStateMachine: handleMessage: X
03-17 08:36:49.068   921  1166 D WifiWatchdogStateMachine: RSSI current: 3 new: -53, 3
,03-17 08:36:49.128  5884  5901 E AndroidHttpClient: Leak found
03-17 08:36:49.128  5884  5901 E AndroidHttpClient: java.lang.IllegalStateException: AndroidHttpClient created and never closed
03-17 08:36:49.128  5884  5901 E AndroidHttpClient: 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
03-17 08:36:49.128  5884  5901 E AndroidHttpClient: 	,at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
03-17 08:36:49.128  5884  5901 E AndroidHttpClient: 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
03-17 08:36:49.128  5884  5901 E AndroidHttpClient: 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
03-17 08:36:49.128  5884  5901 E AndroidHttpClient: 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
03-17 08:36:49.128  5884  5901 E AndroidHttpClient: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
03-17 08:36:49.128  5884  5901 E AndroidHttpClient: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
03-17 08:36:49.128  5884  5901 E AndroidHttpClient: 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
03-17 08:36:49.128  5884  5901 E AndroidHttpClient: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
03-17 08:36:49.128  5884  5901 E AndroidHttpClient: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 08:36:49.128  5884  5901 E AndroidHttpClient: 	at android.os.Looper.loop(Looper.java:155)
03-17 08:36:49.128  5884  5901 E AndroidHttpClient: 	at android.app.ActivityThread.main(ActivityThread.java:5721)
03-17 08:36:49.128  5884  5901 E AndroidHttpClient: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 08:36:49.128  5884  5901 E AndroidHttpClient: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 08:36:49.128  5884  5901 E AndroidHttpClient: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
03-17 08:36:49.128  5884  5901 E AndroidHttpClient: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,03-17 08:36:49.168  4407  4407 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,03-17 08:36:49.168   921  1515 D PMS     : acquireWL(34f7d761): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 4407 10024 WorkSource{10195 com.test.thalitest},
03-17 08:36:49.168  4407  4407 I ConfigFetchService: launchTask
03-17 08:36:49.168   921  4355 D PMS     : releaseWL(3caf9a57): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,03-17 08:36:49.178   921  1720 D PMS     : acquireWL(72c7286): PARTIAL_WAKE_LOCK  Icing 0x1 4407 10024 WorkSource{10024 com.google.android.gms}
,03-17 08:36:49.188  4407  4407 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,03-17 08:36:49.188  4407  4407 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,03-17 08:36:49.198  4407  4407 D ChimeraCfgMgr: Loading module com.google.android.gms.vision from APK com.google.android.gms
,03-17 08:36:49.198   921  1720 D PMS     : releaseWL(72c7286): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,03-17 08:36:49.208  4407  4407 D Vision  : Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package: flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) },
03-17 08:36:49.208  4407  4407 D Vision  : Failed to find package metadata for com.test.thalitest
03-17 08:36:49.208  4407  4407 D Vision  : No vision deps
03-17 08:36:49.208  4407  6052 I PeopleContactsSync: CP2 sync disabled
03-17 08:36:49.208  4407  6051 V ConfigFetchTask: ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1X6VbO7rmcei1BoCYvtR4BcNJ40b4erLfGbuK0wdE2mDD0PJhGTvlk2Byl1zu9YE65Nq56IcflvpyT-6SMoH-RPacADbgdNbTnt4qfw7tkcPoiwIAsOq3FHv_mKS67rTNGspCb2aI5CyoT1aJwSELiOtD5n2GdLqyw-8-G551ZO2M7kbyYt3M8Pp3EBxX-oXvHg7cAD
03-17 08:36:49.218   921  1721 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4407, uid=10024, userID:0
,03-17 08:36:49.218  4407  6051 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-17 08:36:49.228   921  1157 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6056 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a
,03-17 08:36:49.268  4407  6051 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
,03-17 08:36:49.268  4407  6051 D libc    : [NET] android_getaddrinfofornet-, err=8
,03-17 08:36:49.268  4407  6051 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024,
,03-17 08:36:49.268  4407  6051 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
03-17 08:36:49.268  4407  6051 D libc    : [NET] android_getaddrinfo_proxy+
03-17 08:36:49.268  4407  6051 D libc    : [NET] android_getaddrinfo_proxy get netid:0
03-17 08:36:49.268   408  6078 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
03-17 08:36:49.268   408  6078 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
,03-17 08:36:49.378  4407  6054 W BaseAppContext: Using Auth Proxy for data requests.
,03-17 08:36:49.378  4407  6054 W BaseAppContext: Using Auth Proxy for data requests.
,03-17 08:36:49.388  1882  1882 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 08:36:49.418  1882  3574 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
03-17 08:36:49.418  1882  3574 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-17 08:36:49.418  1882  3574 I GLSUser : [GLSUser] Extracting token using key: Auth
03-17 08:36:49.418  1882  3574 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
03-17 08:36:49.418  4407  6054 W BaseAppContext: Using Auth Proxy for data requests.
,03-17 08:36:49.418  1882  3574 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 08:36:49.438  4407  6054 W BaseAppContext: Using Auth Proxy for data requests.
03-17 08:36:49.438  5884  5884 W Finsky  : [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-17 08:36:49.438  4407  6054 W BaseAppContext: Using Auth Proxy for data requests.
,03-17 08:36:49.448  5884  5884 D Finsky  : [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,03-17 08:36:49.448   408  6078 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS)
03-17 08:36:49.448   408  6078 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
03-17 08:36:49.448  4407  6051 D libc    : [NET] android_getaddrinfo_proxy-, success
,03-17 08:36:49.458  5884  5884 D Finsky  : [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-17 08:36:49.458  5884  5884 D Finsky  : [1] DailyHygiene.reschedule: Giving up. (failures=6),
03-17 08:36:49.458  4407  6054 W BaseAppContext: Using Auth Proxy for data requests.
,03-17 08:36:49.468  1810  1838 D DeviceConnectionService: client connected with version: 7571000,
03-17 08:36:49.468   921  1515 I ActivityManager: Killing 5398:com.htc.task/u0a69 (adj 15): empty #17
03-17 08:36:49.468   921  1515 D Process : killProcessQuiet, pid=5398
,03-17 08:36:49.468   921  1515 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 ,
,03-17 08:36:49.538   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 7,
03-17 08:36:49.538   921   921 E WifiTrafficPoller:  packet count Tx=133 Rx=205
03-17 08:36:49.548  1212  1212 D WIFI_ICON: WifiActivity: 3
03-17 08:36:49.548   921   921 E WifiTrafficPoller: notifying of data activity 3
03-17 08:36:49.548  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,03-17 08:36:49.548   921  1712 I ActivityManager: Recipient 5398
,03-17 08:36:49.578   921  1515 D Process : killProcessQuiet, pid=5523
03-17 08:36:49.578   921  1515 I ActivityManager: Killing 5523:com.htc.bgp/u0a11 (adj 15): empty #18
03-17 08:36:49.578   921  1515 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-17 08:36:49.698   921  1721 I ActivityManager: Recipient 5523
,03-17 08:36:49.788   921   921 E WifiDataStallTracker: DATA_MONITOR_POLL true Token 1
,03-17 08:36:49.798   921  6082 D WifiDataStallTracker: updateDataStallInfo: mDataStallTxRxSum={txSum=120 rxSum=107} preTxRxSum={txSum=106 rxSum=97},
03-17 08:36:49.798   921  6082 D WifiDataStallTracker: updateDataStallInfo: IN/OUT
03-17 08:36:49.798   921  6082 D WifiDataStallTracker: onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,03-17 08:36:49.888  4407  6051 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
03-17 08:36:49.888  4407  6051 D libc    : [NET] android_getaddrinfofornet-, err=8
,03-17 08:36:49.888  4407  6051 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
03-17 08:36:49.888  4407  6051 D libc    : [NET] android_getaddrinfofornet-, err=8
,03-17 08:36:49.888  6056  6056 I GAv4    : Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
03-17 08:36:49.888  6056  6056 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-17 08:36:49.888  6056  6056 I GAv4    :   adb logcat -s GAv4
,03-17 08:36:49.908  6056  6056 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-17 08:36:49.918  6056  6056 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,03-17 08:36:49.928  6056  6090 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-17 08:36:49.948  6056  6056 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.25.45
,03-17 08:36:50.028  4407  4407 I ConfigFetchService: fetch service done; releasing wakelock
,03-17 08:36:50.028  4407  4407 I ConfigFetchService: stopping self
03-17 08:36:50.028   921  1515 D PMS     : releaseWL(34f7d761): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 WorkSource{10195 com.test.thalitest}
,03-17 08:36:50.098   921  1515 D VoldConnector: SND -> {28 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/}
,03-17 08:36:50.098   383   657 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/
03-17 08:36:50.098  6056  6095 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.docs/cache
,03-17 08:36:50.108   921  1716 D PMS     : acquireWL(2869309): PARTIAL_WAKE_LOCK  AsyncService 0x1 5954 10167 null,
,03-17 08:36:50.108   921  1514 D PMS     : releaseWL(2869309): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,03-17 08:36:50.108   921  4355 D PMS     : acquireWL(2f33cf2f): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 5954 10167 null
,03-17 08:36:50.128  6056  6096 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-17 08:36:50.128  6056  6096 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 08:36:50.128   921   951 D PMS     : releaseWL(2f33cf2f): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,03-17 08:36:50.168  6056  6096 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-17 08:36:50.188  4407  6054 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
03-17 08:36:50.188  4407  6054 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,03-17 08:36:50.208   921  1712 I ActivityManager: Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=6102 uid=10084 gids={50084, 9997, 3003, 1028, 1015, 1023, 2001, 5006, 5001} abi=arm64-v8a,
03-17 08:36:50.208  5829  6100 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
03-17 08:36:50.218  6056  6096 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-17 08:36:50.218  6056  6096 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-17 08:36:50.258  1882  1882 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 08:36:50.308   921  1721 D PMS     : acquireWL(a22a072): PARTIAL_WAKE_LOCK  Icing 0x1 4407 10024 WorkSource{10024 com.google.android.gms}
,03-17 08:36:50.318   921  1718 D PMS     : releaseWL(a22a072): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,03-17 08:36:50.318   921  1716 I ActivityManager: Killing 5681:com.htc.android.mail:sync/u0a62 (adj 15): empty #17
03-17 08:36:50.318   921  1716 D Process : killProcessQuiet, pid=5681
03-17 08:36:50.318   921  1716 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,03-17 08:36:50.448   921  2373 I ActivityManager: Recipient 5681
,03-17 08:36:50.448   921  1149 D WifiService: Client connection lost with reason: 4
,03-17 08:36:50.528   921  1137 V AlarmManager: sending alarm PendingIntent{3cb87940: PendingIntentRecord{16fd5079 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1458200210452, Int=0
,03-17 08:36:50.538  1882  6130 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE,
03-17 08:36:50.538   921  1720 D PMS     : acquireWL(2bce21f): PARTIAL_WAKE_LOCK  Icing 0x1 4407 10024 WorkSource{10024 com.google.android.gms}
,03-17 08:36:50.548   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 6
03-17 08:36:50.548   921   921 E WifiTrafficPoller:  packet count Tx=143 Rx=221
03-17 08:36:50.548  1882  1882 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-17 08:36:50.558  4407  4407 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-17 08:36:50.588  5308  5308 D WearableService: callingUid 10024, callindPid: 5308
,03-17 08:36:50.598   921  1514 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4407, uid=10024, userID:0
,03-17 08:36:50.608  1810  6132 E MDM     : [147] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
03-17 08:36:50.608  1433  1433 D TelephonyReceiver: bind: false
03-17 08:36:50.608  1433  1433 D TelephonyReceiver: switchBindHtcMsgCursor: null
03-17 08:36:50.618  5724  5724 D DFPI.PIReciver: onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,03-17 08:36:50.618  4407  6133 D LocationInitializer: Restart initialization of location
,03-17 08:36:50.628  5724  6134 I DFPI.ApkInstallService: onHandleIntent
,03-17 08:36:50.628  5724  6134 I DFPI.ApkInstallService: Media Scan Finished Case 
,03-17 08:36:50.638  5801  5801 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,03-17 08:36:50.638  5724  6134 D DFPI.ApkInstallService: check CID = HTC__102
03-17 08:36:50.638  5724  6134 I DFPI.ApkInstallService: There is no Demo.apk in sd card or phone storage
,03-17 08:36:50.648  5801  5801 I SoundPicker: SoundPickerReceiver [onReceive] startService
,03-17 08:36:50.648  5801  6138 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
03-17 08:36:50.648  5801  6138 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true
03-17 08:36:50.648  5801  6138 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
03-17 08:36:50.658  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
03-17 08:36:50.658  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
03-17 08:36:50.658  5801  6138 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
03-17 08:36:50.658  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
03-17 08:36:50.658  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
03-17 08:36:50.658  5801  6138 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
03-17 08:36:50.658  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
03-17 08:36:50.658  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
03-17 08:36:50.658  5801  6138 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
03-17 08:36:50.658  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
03-17 08:36:50.658  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
03-17 08:36:50.658  5801  6138 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
03-17 08:36:50.658  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
03-17 08:36:50.658  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
03-17 08:36:50.658  5801  6138 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
03-17 08:36:50.658  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
03-17 08:36:50.658  5801  6138 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
03-17 08:36:50.658  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
03-17 08:36:50.658  5801  6138 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
03-17 08:36:50.658  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
03-17 08:36:50.658  5801  6138 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
03-17 08:36:50.658  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
03-17 08:36:50.658  5801  6138 W SoundPicker: TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
03-17 08:36:50.658  5801  6138 I SoundPicker: TurnFileToMediaUriService [checkFileExistence]
03-17 08:36:50.658  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
03-17 08:36:50.658  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
03-17 08:36:50.658  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/interna,l/audio/media/122
03-17 08:36:50.658  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:50.658  5829  6100 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 452 ms] updated apps [took 452 ms] 
03-17 08:36:50.668  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:50.668  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:50.668  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
03-17 08:36:50.668  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
03-17 08:36:50.668  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
03-17 08:36:50.668  5724  5724 D DFPI.PIReciver: onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
03-17 08:36:50.678  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:50.678  5724  6140 I DFPI.ApkInstallService: onHandleIntent
03-17 08:36:50.678  5724  6140 I DFPI.ApkInstallService: Media Scan Finished Case 
03-17 08:36:50.678  5724  6140 D DFPI.ApkInstallService: check CID = HTC__102
03-17 08:36:50.678  5724  6140 I DFPI.ApkInstallService: There is no Demo.apk in sd card or phone storage
03-17 08:36:50.678  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:50.678  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:50.678  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
03-17 08:36:50.678  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
03-17 08:36:50.678  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
03-17 08:36:50.688  5801  5801 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
03-17 08:36:50.688  5801  5801 I SoundPicker: SoundPickerReceiver [onReceive] startService
,03-17 08:36:50.688  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:50.698  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:50.698  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:50.698  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
,03-17 08:36:50.698  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
03-17 08:36:50.698  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,03-17 08:36:50.698  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac,
03-17 08:36:50.708  5724  5724 D DFPI.PIReciver: onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,03-17 08:36:50.708  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,03-17 08:36:50.708  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac,
03-17 08:36:50.708  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
03-17 08:36:50.708  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
03-17 08:36:50.708  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,03-17 08:36:50.708  5724  6141 I DFPI.ApkInstallService: onHandleIntent
,03-17 08:36:50.708  5724  6141 I DFPI.ApkInstallService: Media Scan Finished Case 
03-17 08:36:50.718  5724  6141 D DFPI.ApkInstallService: check CID = HTC__102
03-17 08:36:50.718  5724  6141 I DFPI.ApkInstallService: There is no Demo.apk in sd card or phone storage
,03-17 08:36:50.718  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,03-17 08:36:50.718  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
03-17 08:36:50.718  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
03-17 08:36:50.718  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
03-17 08:36:50.718  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,03-17 08:36:50.718  5801  5801 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,03-17 08:36:50.728  5801  5801 I SoundPicker: SoundPickerReceiver [onReceive] startService,
,03-17 08:36:50.728  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,03-17 08:36:50.728  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,03-17 08:36:50.728  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
03-17 08:36:50.728  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
03-17 08:36:50.728  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,03-17 08:36:50.738  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac,
,03-17 08:36:50.738  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,03-17 08:36:50.738  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
03-17 08:36:50.738  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
03-17 08:36:50.738  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,03-17 08:36:50.748  5724  5724 D DFPI.PIReciver: onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,03-17 08:36:50.748  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,03-17 08:36:50.758  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
03-17 08:36:50.758  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
03-17 08:36:50.758  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
03-17 08:36:50.758  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,03-17 08:36:50.758  5724  6142 I DFPI.ApkInstallService: onHandleIntent
,03-17 08:36:50.758  5801  5801 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,03-17 08:36:50.758  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
03-17 08:36:50.758  5801  5801 I SoundPicker: SoundPickerReceiver [onReceive] startService
03-17 08:36:50.768  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
03-17 08:36:50.768  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
03-17 08:36:50.768  5801  6138 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
03-17 08:36:50.768  5801  6138 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true
03-17 08:36:50.768  5801  6138 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
03-17 08:36:50.768  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
03-17 08:36:50.768  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
03-17 08:36:50.768  5801  6138 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
03-17 08:36:50.768  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
03-17 08:36:50.768  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
03-17 08:36:50.768  5801  6138 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
03-17 08:36:50.768  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
03-17 08:36:50.768  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
03-17 08:36:50.768  5801  6138 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
03-17 08:36:50.768  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
03-17 08:36:50.768  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
03-17 08:36:50.768  5801  6138 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
03-17 08:36:50.768  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
03-17 08:36:50.768  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
03-17 08:36:50.768  5801  6138 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
03-17 08:36:50.768  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
03-17 08:36:50.768  5801  6138 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
03-17 08:36:50.768  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
03-17 08:36:50.768  5801  6138 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
03-17 08:36:50.768  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
03-17 08:36:50.768  5801  6138 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
03-17 08:36:50.768  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
03-17 08:36:50.768  5801  6138 W SoundPicker: TurnFileToMediaUriServic,e [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
03-17 08:36:50.768  5801  6138 I SoundPicker: TurnFileToMediaUriService [checkFileExistence]
03-17 08:36:50.768  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
03-17 08:36:50.768  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
03-17 08:36:50.768  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
03-17 08:36:50.768  5724  6142 I DFPI.ApkInstallService: Media Scan Finished Case 
03-17 08:36:50.768  5724  6142 D DFPI.ApkInstallService: check CID = HTC__102
03-17 08:36:50.768  5724  6142 I DFPI.ApkInstallService: There is no Demo.apk in sd card or phone storage
03-17 08:36:50.778  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:50.778  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:50.778  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:50.778  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
03-17 08:36:50.778  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
03-17 08:36:50.778  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
03-17 08:36:50.788  5724  5724 D DFPI.PIReciver: onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
03-17 08:36:50.788  6102  6129 I ActionCombine: replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
03-17 08:36:50.788  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:50.788  5724  6144 I DFPI.ApkInstallService: onHandleIntent
03-17 08:36:50.788  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:50.788  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:50.788  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
03-17 08:36:50.788  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
03-17 08:36:50.788  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
03-17 08:36:50.788  5724  6144 I DFPI.ApkInstallService: Media Scan Finished Case 
03-17 08:36:50.798  5724  6144 D DFPI.ApkInstallService: check CID = HTC__102
03-17 08:36:50.798  5724  6144 I DFPI.ApkInstallService: There is no Demo.apk in sd card or phone storage
03-17 08:36:50.798  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,03-17 08:36:50.798  5463  6139 I MediaStoreImporter: Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,03-17 08:36:50.808  5801  5801 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
03-17 08:36:50.808  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:50.808  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:50.808  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
03-17 08:36:50.808  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
03-17 08:36:50.808  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
03-17 08:36:50.808  5801  5801 I SoundPicker: SoundPickerReceiver [onReceive] startService
03-17 08:36:50.808  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,03-17 08:36:50.808  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
03-17 08:36:50.808  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
03-17 08:36:50.808  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
03-17 08:36:50.808  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5,
03-17 08:36:50.808  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,03-17 08:36:50.818  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,03-17 08:36:50.818  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,03-17 08:36:50.818  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
03-17 08:36:50.818  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
03-17 08:36:50.818  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,03-17 08:36:50.818  1306  1345 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false
,03-17 08:36:50.828  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,03-17 08:36:50.828  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,03-17 08:36:50.828  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
03-17 08:36:50.828  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
03-17 08:36:50.828  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,03-17 08:36:50.838  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,03-17 08:36:50.838  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
03-17 08:36:50.838  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
03-17 08:36:50.838  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
03-17 08:36:50.838  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
03-17 08:36:50.838  1212  1212 I RemoteViews: setHTCTheme(com.htc.updater,true,33751145)
,03-17 08:36:50.848  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,03-17 08:36:50.848  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,03-17 08:36:50.848  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
03-17 08:36:50.848  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
03-17 08:36:50.848  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,03-17 08:36:50.858  5724  5724 D DFPI.PIReciver: onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,03-17 08:36:50.858  1212  1212 I RemoteViews: apply : com.htc.updater 1 18 2 36
,03-17 08:36:50.928  1212  1212 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,03-17 08:36:50.938  1212  1212 I ThreadedRenderer: Defer allocateBuffers to drawing time
,03-17 08:36:50.998   921  1401 I art     : Explicit concurrent mark sweep GC freed 17787(825KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/25MB, paused 1.588ms total 141.785ms
03-17 08:36:50.998  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
03-17 08:36:50.998  5724  6147 I DFPI.ApkInstallService: onHandleIntent
03-17 08:36:50.998  5724  6147 I DFPI.ApkInstallService: Media Scan Finished Case 
03-17 08:36:51.008  5724  6147 D DFPI.ApkInstallService: check CID = HTC__102
03-17 08:36:51.008  5724  6147 I DFPI.ApkInstallService: There is no Demo.apk in sd card or phone storage
03-17 08:36:51.008  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
03-17 08:36:51.008  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
03-17 08:36:51.008  5801  6138 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
03-17 08:36:51.008  5801  6138 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true
03-17 08:36:51.008  5801  6138 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
03-17 08:36:51.008  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
03-17 08:36:51.008  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
03-17 08:36:51.008  5801  6138 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
03-17 08:36:51.008  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
03-17 08:36:51.008  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
03-17 08:36:51.008  5801  6138 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
03-17 08:36:51.008  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
03-17 08:36:51.008  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
03-17 08:36:51.008  5801  6138 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
03-17 08:36:51.008  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
03-17 08:36:51.008  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
03-17 08:36:51.008  5801  6138 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
03-17 08:36:51.008  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
03-17 08:36:51.008  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
03-17 08:36:51.008  5801  6138 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
03-17 08:36:51.008  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
03-17 08:36:51.008  5801  6138 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
03-17 08:36:51.008  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
03-17 08:36:51.008  5801  6138 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
03-17 08:36:51.008  5801  6138 I SoundPicker: SoundPickerUtil [,getRingtone] uri=content://media/internal/audio/media/104 type=8
03-17 08:36:51.008  5801  6138 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
03-17 08:36:51.008  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
03-17 08:36:51.008  5801  6138 W SoundPicker: TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
03-17 08:36:51.008  5801  6138 I SoundPicker: TurnFileToMediaUriService [checkFileExistence]
03-17 08:36:51.008  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
03-17 08:36:51.008  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
03-17 08:36:51.008  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
03-17 08:36:51.018  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:51.018  5801  5801 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
03-17 08:36:51.018  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:51.018  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:51.018  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
03-17 08:36:51.018  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
03-17 08:36:51.018  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
03-17 08:36:51.018  5801  5801 I SoundPicker: SoundPickerReceiver [onReceive] startService
03-17 08:36:51.028  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:51.028  5463  6139 I MediaStoreImporter: Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
03-17 08:36:51.028  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:51.028  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:51.028  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
03-17 08:36:51.028  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
03-17 08:36:51.028  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
03-17 08:36:51.038  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:51.038  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:51.038  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:51.038  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
03-17 08:36:51.048  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
03-17 08:36:51.048  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
03-17 08:36:51.048  1882  6149 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-17 08:36:51.058  1882  1882 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
03-17 08:36:51.058  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
03-17 08:36:51.058  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
03-17 08:36:51.058  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
03-17 08:36:51.058  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
03-17 08:36:51.058  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
03-17 08:36:51.058  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
03-17 08:36:51.068  4407  4407 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
03-17 08:36:51.068  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
03-17 08:36:51.068  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
03-17 08:36:51.068  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
03-17 08:36:51.068  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
03-17 08:36:51.068  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
03-17 08:36:51.078   921   951 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4407, uid=10024, userID:0
03-17 08:36:51.088  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
03-17 08:36:51.088  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
03-17 08:36:51.088  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
03-17 08:36:51.088  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
,03-17 08:36:51.088  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
03-17 08:36:51.088  1810  6150 E MDM     : [148] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-17 08:36:51.098  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,03-17 08:36:51.098  4407  6151 D LocationInitializer: Restart initialization of location
03-17 08:36:51.108  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
03-17 08:36:51.108  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
03-17 08:36:51.108  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
03-17 08:36:51.108  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,03-17 08:36:51.108  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,03-17 08:36:51.108  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,03-17 08:36:51.118  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
03-17 08:36:51.118  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
03-17 08:36:51.118  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,03-17 08:36:51.118  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac,
,03-17 08:36:51.128  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,03-17 08:36:51.128  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
03-17 08:36:51.128  5801  6138 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) },
03-17 08:36:51.128   921  4355 D PMS     : acquireWL(301997a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1882 10024 WorkSource{10024 com.google.android.gms}
03-17 08:36:51.128  5801  6138 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true
03-17 08:36:51.128  5801  6138 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
,03-17 08:36:51.128  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
03-17 08:36:51.128  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
03-17 08:36:51.128  5801  6138 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
03-17 08:36:51.128  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
03-17 08:36:51.128  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2,
03-17 08:36:51.128  5801  6138 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
03-17 08:36:51.128  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
03-17 08:36:51.128  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
03-17 08:36:51.128  5801  6138 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
03-17 08:36:51.128  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
03-17 08:36:51.128  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
03-17 08:36:51.128  5801  6138 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
03-17 08:36:51.128  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
03-17 08:36:51.128  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
03-17 08:36:51.128  5801  6138 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30,
03-17 08:36:51.128  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
03-17 08:36:51.128  5801  6138 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
03-17 08:36:51.128  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
03-17 08:36:51.128  5801  6138 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
03-17 08:36:51.128  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
03-17 08:36:51.128  5801  6138 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
03-17 08:36:51.128  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
03-17 08:36:51.128  5801  6138 W SoundPicker: TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98,
03-17 08:36:51.128  5801  6138 I SoundPicker: TurnFileToMediaUriService [checkFileExistence],
03-17 08:36:51.128  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
03-17 08:36:51.128  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
03-17 08:36:51.128  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
03-17 08:36:51.138  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:51.138   921  1716 D PMS     : releaseWL(301997a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,03-17 08:36:51.138  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:51.138  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:51.138  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
03-17 08:36:51.138  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
03-17 08:36:51.138  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,03-17 08:36:51.138   921  1710 D PMS     : acquireWL(2cd87f59): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1882 10024 WorkSource{10024 com.google.android.gms}
,03-17 08:36:51.148   921   950 D PMS     : releaseWL(2cd87f59): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,03-17 08:36:51.148  5463  6139 I MediaStoreImporter: Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,03-17 08:36:51.168  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:51.168  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:51.168  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,03-17 08:36:51.168  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
03-17 08:36:51.168  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
03-17 08:36:51.168  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,03-17 08:36:51.178  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,03-17 08:36:51.188  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:51.188  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:51.188  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
,03-17 08:36:51.188  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
03-17 08:36:51.188  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,03-17 08:36:51.208   921  1719 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6158 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a
,03-17 08:36:51.208  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,03-17 08:36:51.208  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
03-17 08:36:51.208  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
03-17 08:36:51.208  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
03-17 08:36:51.208  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
03-17 08:36:51.208  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,03-17 08:36:51.218   921   951 D PMS     : acquireWL(3208b815): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 4407 10024 WorkSource{10024 com.google.android.gms}
,03-17 08:36:51.228  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,03-17 08:36:51.228  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac,
,03-17 08:36:51.228  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
03-17 08:36:51.228  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
03-17 08:36:51.228  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,03-17 08:36:51.238   921  1137 V AlarmManager: sending alarm PendingIntent{2b0af72a: PendingIntentRecord{3f76391b android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=73895, Int=0
,03-17 08:36:51.238  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,03-17 08:36:51.248  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
03-17 08:36:51.248  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
,03-17 08:36:51.248  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
03-17 08:36:51.248  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,03-17 08:36:51.258  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,03-17 08:36:51.258  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
03-17 08:36:51.258  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
03-17 08:36:51.258  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
03-17 08:36:51.258  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,03-17 08:36:51.268  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
03-17 08:36:51.268  6158  6158 D PhoneMonitor: Register our PhoneStateListener
03-17 08:36:51.268  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
03-17 08:36:51.268  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
03-17 08:36:51.268  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
03-17 08:36:51.268  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
03-17 08:36:51.268  5463  6139 I MediaStoreImporter: Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,03-17 08:36:51.278  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
03-17 08:36:51.278  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
03-17 08:36:51.278  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
03-17 08:36:51.278  5801  6138 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
03-17 08:36:51.278  5801  6138 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true
03-17 08:36:51.278  5801  6138 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
03-17 08:36:51.278  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
03-17 08:36:51.278  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
03-17 08:36:51.278  5801  6138 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
03-17 08:36:51.278  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
03-17 08:36:51.278  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
03-17 08:36:51.278  5801  6138 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
03-17 08:36:51.278  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
03-17 08:36:51.278  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
03-17 08:36:51.278  5801  6138 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
03-17 08:36:51.278  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
03-17 08:36:51.278  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
03-17 08:36:51.278  5801  6138 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
03-17 08:36:51.278  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
03-17 08:36:51.278  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
03-17 08:36:51.278  5801  6138 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
03-17 08:36:51.278  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
03-17 08:36:51.278  5801  6138 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
03-17 08:36:51.278  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
03-17 08:36:51.278  5801  6138 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
03-17 08:36:51.278  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
03-17 08:36:51.278  5801  6138 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
03-17 08:36:51.278  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
03-17 08:36:51.278  5801  6138 W SoundPicker: TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audi,o/media/98
03-17 08:36:51.278  5801  6138 I SoundPicker: TurnFileToMediaUriService [checkFileExistence]
03-17 08:36:51.278  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
03-17 08:36:51.278  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
03-17 08:36:51.278  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
03-17 08:36:51.288  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,03-17 08:36:51.298  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,03-17 08:36:51.308  1882  2768 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
03-17 08:36:51.308  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:51.308  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
03-17 08:36:51.308  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
03-17 08:36:51.308  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
03-17 08:36:51.308  4407  4407 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,03-17 08:36:51.308  4407  4407 I Kids    : [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
03-17 08:36:51.318  6158  6158 D PhoneMonitor: onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,03-17 08:36:51.318  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,03-17 08:36:51.318  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,03-17 08:36:51.318  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:51.318  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
03-17 08:36:51.318  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
03-17 08:36:51.318  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,03-17 08:36:51.338  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,03-17 08:36:51.338  6158  6158 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,03-17 08:36:51.338  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,03-17 08:36:51.338  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:51.338  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
03-17 08:36:51.338  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4,
03-17 08:36:51.338  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,03-17 08:36:51.348   921   950 D PMS     : acquireWL(3c174182): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4407 10024 WorkSource{10024 com.google.android.gms}
,03-17 08:36:51.348  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,03-17 08:36:51.348   921  1515 D PMS     : releaseWL(3208b815): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 WorkSource{10024 com.google.android.gms}
,03-17 08:36:51.348  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac,
03-17 08:36:51.348  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
03-17 08:36:51.348  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
03-17 08:36:51.348  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
03-17 08:36:51.348  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,03-17 08:36:51.358   921  1721 D PMS     : acquireWL(2f1228d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1882 10024 WorkSource{10024 com.google.android.gms}
,03-17 08:36:51.358  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,03-17 08:36:51.358   921   951 D PMS     : acquireWL(340af0c9): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4407 10024 WorkSource{10024 com.google.android.gms}
03-17 08:36:51.368   921  1710 D PMS     : releaseWL(3c174182): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
,03-17 08:36:51.368  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac,
03-17 08:36:51.368  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
03-17 08:36:51.368   921  1718 D PMS     : releaseWL(2f1228d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
03-17 08:36:51.368  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
03-17 08:36:51.368  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,03-17 08:36:51.368  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
03-17 08:36:51.378  5463  6139 I MediaStoreImporter: Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,03-17 08:36:51.388   921  1718 I ActivityManager: Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForAndroidIntent: pid=6182 uid=10035 gids={50035, 9997} abi=arm64-v8a
,03-17 08:36:51.388  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,03-17 08:36:51.388  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
,03-17 08:36:51.388  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
03-17 08:36:51.388  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,03-17 08:36:51.388  4407  6181 I CheckinService: Checking schedule, now: 1458200211398 next: 1458200214215
03-17 08:36:51.388  4407  6181 I CheckinService: active receiver: disabled
,03-17 08:36:51.388   921  1718 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4407, uid=10024, userID:0
,03-17 08:36:51.388  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,03-17 08:36:51.398  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
03-17 08:36:51.398  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
,03-17 08:36:51.398  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
03-17 08:36:51.398   921  1718 D PMS     : releaseWL(340af0c9): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
03-17 08:36:51.398  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,03-17 08:36:51.408  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,03-17 08:36:51.408  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,03-17 08:36:51.408  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
03-17 08:36:51.408  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
03-17 08:36:51.408  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,03-17 08:36:51.418  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,03-17 08:36:51.418  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac,
03-17 08:36:51.418  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,03-17 08:36:51.428  5801  6138 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) },
03-17 08:36:51.428  5801  6138 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true
03-17 08:36:51.428  5801  6138 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
03-17 08:36:51.428  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
03-17 08:36:51.428  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
03-17 08:36:51.428  5801  6138 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
03-17 08:36:51.428  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
03-17 08:36:51.428  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
,03-17 08:36:51.428  5801  6138 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
03-17 08:36:51.428  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
03-17 08:36:51.428  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
03-17 08:36:51.428  5801  6138 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
03-17 08:36:51.428  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
03-17 08:36:51.428  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
03-17 08:36:51.428  5801  6138 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
03-17 08:36:51.428  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
03-17 08:36:51.428  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
03-17 08:36:51.428  5801  6138 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
03-17 08:36:51.428  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
03-17 08:36:51.428  5801  6138 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
03-17 08:36:51.428  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
03-17 08:36:51.428  5801  6138 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
03-17 08:36:51.428  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
03-17 08:36:51.428  5801  6138 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
,03-17 08:36:51.428  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
03-17 08:36:51.428  5801  6138 W SoundPicker: TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
03-17 08:36:51.428  5801  6138 I SoundPicker: TurnFileToMediaUriService [checkFileExistence]
03-17 08:36:51.428  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
03-17 08:36:51.428  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
03-17 08:36:51.428  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,03-17 08:36:51.428  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac,
,03-17 08:36:51.428  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:51.428  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,03-17 08:36:51.428  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
03-17 08:36:51.428  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
03-17 08:36:51.428  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,03-17 08:36:51.438  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,03-17 08:36:51.438  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:51.438  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,03-17 08:36:51.438  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
03-17 08:36:51.438  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
03-17 08:36:51.438  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,03-17 08:36:51.448  5463  6139 I MediaStoreImporter: Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,03-17 08:36:51.458  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,03-17 08:36:51.458  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:51.458  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:51.458  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 2),
03-17 08:36:51.458  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
03-17 08:36:51.458  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,03-17 08:36:51.458  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,03-17 08:36:51.468  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac,
03-17 08:36:51.468  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
03-17 08:36:51.468  5801  6138 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
,03-17 08:36:51.468  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
,03-17 08:36:51.468  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,03-17 08:36:51.478   921  4355 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6205 uid=10106 gids={50106, 9997, 3003, 1028, 1015} abi=arm64-v8a
,03-17 08:36:51.478  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,03-17 08:36:51.488  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,03-17 08:36:51.488  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
,03-17 08:36:51.488  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
03-17 08:36:51.488  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96,
,03-17 08:36:51.498  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,03-17 08:36:51.498  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
03-17 08:36:51.498  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
03-17 08:36:51.498  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
03-17 08:36:51.498  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,03-17 08:36:51.508  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,03-17 08:36:51.508  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
03-17 08:36:51.508  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
03-17 08:36:51.508  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
,03-17 08:36:51.508  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,03-17 08:36:51.508  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,03-17 08:36:51.518  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
03-17 08:36:51.518  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
03-17 08:36:51.518  5801  6138 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
03-17 08:36:51.518  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,03-17 08:36:51.518  5801  6138 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
03-17 08:36:51.518  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
03-17 08:36:51.528   921  1719 I ActivityManager: Killing 4235:com.htc.sense.mms/u0a64 (adj 15): empty #17
,03-17 08:36:51.518  5801  6138 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
03-17 08:36:51.528   921  1719 D Process : killProcessQuiet, pid=4235
03-17 08:36:51.528   921  1719 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-17 08:36:51.548   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 6,
03-17 08:36:51.548  1212  1212 D WIFI_ICON: WifiActivity: 0
03-17 08:36:51.548   921   921 E WifiTrafficPoller:  packet count Tx=143 Rx=221
03-17 08:36:51.548  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
03-17 08:36:51.548   921   921 E WifiTrafficPoller: notifying of data activity 0
,03-17 08:36:51.628   921  1712 I ActivityManager: Recipient 4235,
,03-17 08:36:51.658  4407  4962 I Icing   : Indexing FBE7E5D8BA1B80556F1315772AF6A2582D6BF376 from com.google.android.googlequicksearchbox,
,03-17 08:36:51.738  4407  4962 I Icing   : Indexing done FBE7E5D8BA1B80556F1315772AF6A2582D6BF376,
,03-17 08:36:51.748   921  1157 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
03-17 08:36:51.748   921  1710 D PMS     : releaseWL(2bce21f): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,03-17 08:36:51.848  6205  6229 I Gmail   : getAccountsCursor,
,03-17 08:36:51.858  1882  1882 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 08:36:51.858  1882  3488 I art     : Explicit concurrent mark sweep GC freed 16098(890KB) AllocSpace objects, 0(0B) LOS objects, 49% free, 4MB/8MB, paused 740us total 37.745ms
,03-17 08:36:51.878  6205  6205 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-17 08:36:52.008   921  1719 I art     : Explicit concurrent mark sweep GC freed 10103(515KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/25MB, paused 1.907ms total 147.443ms
,03-17 08:36:52.008   921  1710 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.AttachmentService, state=2, flag=1, pid=6205, uid=10106, userID:0,
03-17 08:36:52.008   921  1514 D Process : killProcessQuiet, pid=5749,
,03-17 08:36:52.008   921  1514 I ActivityManager: Killing 5749:com.htc.task.gtask/u0a66 (adj 15): empty #17
03-17 08:36:52.008   921  1514 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-17 08:36:52.078   921  1148 E WifiStateMachine: handleMessage: E msg.what=131155
,03-17 08:36:52.078   921  1148 E WifiStateMachine: processMsg: ConnectedState
,03-17 08:36:52.078   921  1148 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-53 f=2457 sc=60 link=150 tx=9.4, 0.0, 0.0  rx=11.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2088668557] gl hn u24 rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,03-17 08:36:52.078   921  1148 E WifiStateMachine: processMsg: L2ConnectedState
03-17 08:36:52.078   921  1721 I ActivityManager: Recipient 5749
03-17 08:36:52.078   921  1148 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-53 f=2457 sc=60 link=150 tx=9.4, 0.0, 0.0  rx=11.8 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-2088668556] gl hn u24 rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
03-17 08:36:52.078   921  1148 E WifiStateMachine:  get link layer stats 0
03-17 08:36:52.078   921  1148 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
03-17 08:36:52.078  1346  1346 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
,03-17 08:36:52.088  1346  1346 I wpa_supplicant: environment dirty rate=0 [12][0][0],
03-17 08:36:52.088   921  1148 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 150
03-17 08:36:52.088   921  1148 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-53 linkspeed=150
03-17 08:36:52.088   921  1148 E WifiConfigStore: updateConfiguration freq=2457 BSSID=f4:f2:6d:22:99:3e RSSI=-52 "NG700"WPA_PSK
03-17 08:36:52.088   921  1148 E WifiStateMachine: calculateWifiScore freq=2457 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=10.68 txretriesrate=0.00 rxrate=16.42 userTriggerdPenalty0,
03-17 08:36:52.088   921  1148 E WifiStateMachine:  good link -> stuck count =0
03-17 08:36:52.088   921  1148 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 60
03-17 08:36:52.088   921  1148 E WifiStateMachine:  isHighRSSI       ---> score=65
,03-17 08:36:52.118   921  1719 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
,03-17 08:36:52.128   921  1148 E WifiStateMachine: handleMessage: X
03-17 08:36:52.128   921  1166 D WifiWatchdogStateMachine: RSSI current: 3 new: -53, 3
03-17 08:36:52.128  1212  1212 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3
03-17 08:36:52.128  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
03-17 08:36:52.128   921  1712 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,03-17 08:36:52.138  6205  6239 I Gmail   : Observing account changes for notifications
,03-17 08:36:52.138   921   951 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 08:36:52.148   921  1157 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=6205, uid=10106, userID:0
,03-17 08:36:52.148   921   950 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=6205, uid=10106, userID:0
,03-17 08:36:52.158  6205  6240 E Gmail   : Error finding the version of the Email provider.....
03-17 08:36:52.158  6205  6240 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
03-17 08:36:52.158  6205  6240 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
03-17 08:36:52.158  6205  6240 E Gmail   : 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
03-17 08:36:52.158  6205  6240 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
03-17 08:36:52.158  6205  6240 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-17 08:36:52.158  6205  6240 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 08:36:52.158  6205  6240 E Gmail   : 	at android.os.Looper.loop(Looper.java:155)
03-17 08:36:52.158  6205  6240 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-17 08:36:52.158  6205  6240 W EmailMigration: We do not support migrating this version of the Email provider.
,03-17 08:36:52.168  6205  6242 I Gmail   : getAccountsCursor
,03-17 08:36:52.178  1882  1882 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 08:36:52.198  3496  3571 I HtcModeClient: handler message = 4011,
03-17 08:36:52.198  3496  3571 E HtcModeClient: Check connection and retry 6 times.
,03-17 08:36:52.198   921  1710 D PMS     : acquireWL(3fa96600): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4974 10112 null
,03-17 08:36:52.208  1882  2916 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-17 08:36:52.208  1882  1882 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 08:36:52.218  1882  1882 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-17 08:36:52.218  4407  4407 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-17 08:36:52.228  4974  4974 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-17 08:36:52.228  4974  4974 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 08:36:52.228   921  1137 V AlarmManager: sending alarm PendingIntent{df60d56: PendingIntentRecord{105811d7 com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1458200212237, Int=0
03-17 08:36:52.228   921  1137 V AlarmManager: sending alarm PendingIntent{3a4bcbda: PendingIntentRecord{2efe680b android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1458200204984, Int=20000
,03-17 08:36:52.238  1810  6253 E MDM     : [149] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
03-17 08:36:52.238   921  1712 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4407, uid=10024, userID:0
,03-17 08:36:52.258  4407  6255 D LocationInitializer: Restart initialization of location
,03-17 08:36:52.288  5724  5724 D DFPI.PIReciver: onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,03-17 08:36:52.288  1433  2424 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.,
,03-17 08:36:52.288  5724  6258 I DFPI.ApkInstallService: onHandleIntent
03-17 08:36:52.298  5724  6258 I DFPI.ApkInstallService: Media Scan Finished Case 
03-17 08:36:52.298  5724  6258 D DFPI.ApkInstallService: check CID = HTC__102
03-17 08:36:52.298  5724  6258 I DFPI.ApkInstallService: There is no Demo.apk in sd card or phone storage
03-17 08:36:52.298  4974  6247 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-17 08:36:52.298  4974  6247 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-17 08:36:52.308  6205  6243 E SQLiteLog: (283) recovered 1711 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,03-17 08:36:52.308  4974  6247 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-17 08:36:52.308  5801  5801 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,03-17 08:36:52.308  5801  5801 I SoundPicker: SoundPickerReceiver [onReceive] startService,
,03-17 08:36:52.328  5801  6259 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
,03-17 08:36:52.328  5801  6259 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true
03-17 08:36:52.328  5801  6259 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
03-17 08:36:52.328  5801  6259 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
03-17 08:36:52.328  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
03-17 08:36:52.328  5801  6259 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
03-17 08:36:52.328  5801  6259 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
03-17 08:36:52.328  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
03-17 08:36:52.328  5801  6259 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
03-17 08:36:52.328  5801  6259 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
03-17 08:36:52.328  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
03-17 08:36:52.328  5801  6259 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
03-17 08:36:52.328  5801  6259 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
03-17 08:36:52.328  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
,03-17 08:36:52.328  5801  6259 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
03-17 08:36:52.328  5801  6259 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
03-17 08:36:52.328  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
03-17 08:36:52.328  5801  6259 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
03-17 08:36:52.328  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
03-17 08:36:52.328  5801  6259 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
03-17 08:36:52.328  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
03-17 08:36:52.328  5801  6259 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
03-17 08:36:52.328  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
03-17 08:36:52.328  5801  6259 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
03-17 08:36:52.328  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
03-17 08:36:52.328  5801  6259 W SoundPicker: TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
03-17 08:36:52.328  5801  6259 I SoundPicker: TurnFileToMediaUriService [checkFileExistence]
03-17 08:36:52.328  5801  6259 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
03-17 08:36:52.328  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
03-17 08:36:52.328  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,03-17 08:36:52.338  5801  6259 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac,
03-17 08:36:52.338  5724  5724 D DFPI.PIReciver: onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,03-17 08:36:52.348  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,03-17 08:36:52.348  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:52.348  5801  6259 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma),
03-17 08:36:52.348  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
03-17 08:36:52.348  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
03-17 08:36:52.348  4407  6254 I iu.UploadsManager: End new media; added: 0, uploading: 0, time: 112 ms
,03-17 08:36:52.358  5724  6262 I DFPI.ApkInstallService: onHandleIntent,
03-17 08:36:52.358  5724  6262 I DFPI.ApkInstallService: Media Scan Finished Case 
,03-17 08:36:52.358  5724  6262 D DFPI.ApkInstallService: check CID = HTC__102
,03-17 08:36:52.358  5801  6259 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,03-17 08:36:52.358  5724  6262 I DFPI.ApkInstallService: There is no Demo.apk in sd card or phone storage
03-17 08:36:52.358  5801  5801 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
03-17 08:36:52.368  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:52.368  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:52.368  5801  6259 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
03-17 08:36:52.368  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
03-17 08:36:52.368  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,03-17 08:36:52.368  5801  5801 I SoundPicker: SoundPickerReceiver [onReceive] startService
,03-17 08:36:52.378  5801  6259 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,03-17 08:36:52.378  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:52.378  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:52.378  5801  6259 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
03-17 08:36:52.378  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
,03-17 08:36:52.378  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,03-17 08:36:52.388  5724  5724 D DFPI.PIReciver: onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,03-17 08:36:52.388   921  1710 D PMS     : releaseWL(3fa96600): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,03-17 08:36:52.398  5724  6263 I DFPI.ApkInstallService: onHandleIntent
,03-17 08:36:52.398  5801  6259 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,03-17 08:36:52.398  5724  6263 I DFPI.ApkInstallService: Media Scan Finished Case 
,03-17 08:36:52.398  5724  6263 D DFPI.ApkInstallService: check CID = HTC__102,
03-17 08:36:52.398  5724  6263 I DFPI.ApkInstallService: There is no Demo.apk in sd card or phone storage
,03-17 08:36:52.398  5801  5801 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
03-17 08:36:52.408  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
03-17 08:36:52.408  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
03-17 08:36:52.408  5801  6259 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
03-17 08:36:52.408  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
03-17 08:36:52.408  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,03-17 08:36:52.408  5801  5801 I SoundPicker: SoundPickerReceiver [onReceive] startService
,03-17 08:36:52.408  5801  6259 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,03-17 08:36:52.418  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
03-17 08:36:52.418  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
03-17 08:36:52.418  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
,03-17 08:36:52.418  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,03-17 08:36:52.428  6205  6248 I Gmail   : notifyAccountChanged
03-17 08:36:52.428  6205  6271 I Gmail   : getAccountsCursor
03-17 08:36:52.438  6205  6248 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-17 08:36:52.448   921  1718 I ActivityManager: Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=6266 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,03-17 08:36:52.448  5801  6259 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,03-17 08:36:52.458   442   442 I art     : Explicit concurrent mark sweep GC freed 8659(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 277us total 21.038ms
,03-17 08:36:52.458  1882  1882 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-17 08:36:52.458  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
03-17 08:36:52.458  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
03-17 08:36:52.458  6205  6248 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
03-17 08:36:52.458  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
03-17 08:36:52.458  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,03-17 08:36:52.468  5801  6259 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,03-17 08:36:52.468   442   442 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 239us total 14.471ms
03-17 08:36:52.468  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
03-17 08:36:52.468  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
03-17 08:36:52.468  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
03-17 08:36:52.468  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,03-17 08:36:52.488  5801  6259 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
03-17 08:36:52.488   442   442 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 277us total 15.397ms
,03-17 08:36:52.488  5463  6260 I MediaStoreImporter: Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,03-17 08:36:52.488  6205  6248 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-17 08:36:52.498  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,03-17 08:36:52.498  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac,
03-17 08:36:52.498  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
03-17 08:36:52.498  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,03-17 08:36:52.498  6266  6266 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-17 08:36:52.498  6205  6248 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-17 08:36:52.508  5801  6259 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,03-17 08:36:52.508  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,03-17 08:36:52.508  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
03-17 08:36:52.508  5801  6259 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
03-17 08:36:52.508  5801  6259 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true
03-17 08:36:52.508  5801  6259 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
03-17 08:36:52.508  5801  6259 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
03-17 08:36:52.508  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
03-17 08:36:52.508  5801  6259 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
03-17 08:36:52.508  5801  6259 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
03-17 08:36:52.508  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
03-17 08:36:52.508  5801  6259 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
03-17 08:36:52.508  5801  6259 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
03-17 08:36:52.508  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
03-17 08:36:52.508  5801  6259 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
03-17 08:36:52.508  5801  6259 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
03-17 08:36:52.508  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
03-17 08:36:52.508  5801  6259 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
03-17 08:36:52.508  5801  6259 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
03-17 08:36:52.508  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
03-17 08:36:52.508  5801  6259 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
03-17 08:36:52.508  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
03-17 08:36:52.508  5801  6259 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
03-17 08:36:52.508  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
03-17 08:36:52.508  5801  6259 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
03-17 08:36:52.508  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
03-17 08:36:52.508  5801  6259 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
03-17 08:36:52.508  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
03-17 08:36:52.508  5801  6259 W SoundPicker: TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
03-17 08:36:52.508  5801  6259 I SoundPicker: TurnFileToMediaUriService [checkFileExistence]
03-17 08:36:52.508  5801  6259 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
03-17 08:36:52.508  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/1,22 type=1
03-17 08:36:52.508  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,03-17 08:36:52.518  5801  6259 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,03-17 08:36:52.528  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,03-17 08:36:52.528  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac,
03-17 08:36:52.528  5801  6259 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
03-17 08:36:52.528  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
03-17 08:36:52.528  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,03-17 08:36:52.538  5801  6259 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:52.538  6266  6266 D CalendarApplication: onCreate
03-17 08:36:52.538  6266  6266 D ProviderChangeReceiver: ---------------------------------------------------
03-17 08:36:52.538  6266  6266 D ProviderChangeReceiver: ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,03-17 08:36:52.538  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:52.538  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:52.538  5801  6259 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
03-17 08:36:52.538  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
,03-17 08:36:52.538  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,03-17 08:36:52.548   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 6
,03-17 08:36:52.548   921   921 E WifiTrafficPoller:  packet count Tx=143 Rx=221
,03-17 08:36:52.548  6266  6290 D HtcAlertService: start to updateAlertNotification!
,03-17 08:36:52.558  5801  6259 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,03-17 08:36:52.568   921  1401 I ActivityManager: Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=6293 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a,
,03-17 08:36:52.568  1568  6292 I WSP     : [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
,03-17 08:36:52.578  1568  6292 D WeatherUtility: Weather sync is On
03-17 08:36:52.578  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,03-17 08:36:52.578  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,03-17 08:36:52.578  5801  6259 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
03-17 08:36:52.578  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
03-17 08:36:52.578  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,03-17 08:36:52.588   439   439 I art     : Explicit concurrent mark sweep GC freed 8645(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 161us total 21.780ms
,03-17 08:36:52.608   439   439 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 135us total 16.241ms,
,03-17 08:36:52.618   439   439 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 134us total 15.625ms,
,03-17 08:36:52.638   921  1515 I ActivityManager: Start proc com.htc.bgp for content provider com.android.providers.calendar/com.htc.providers.calendar.HtcCalendarProvider: pid=6314 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a,
,03-17 08:36:52.648  1568  6292 I WSP     : [Receiver] next auto-sync alarm event is 60 mins later, at time: Thu Mar 17 09:36:52 CET 2016
,03-17 08:36:52.668  5801  6259 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,03-17 08:36:52.668  6293  6293 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 08:36:52.668  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
03-17 08:36:52.668  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
03-17 08:36:52.668  5801  6259 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
,03-17 08:36:52.668  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
,03-17 08:36:52.668  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,03-17 08:36:52.688  6205  6271 I Gmail   : master sync=false, engine sync=true,
,03-17 08:36:52.688  1882  1904 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
03-17 08:36:52.688  1882  1904 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-17 08:36:52.688  1882  1904 I GLSUser : [GLSUser] Extracting token using key: Auth
03-17 08:36:52.688  1882  1904 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-17 08:36:52.698  5801  6259 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,03-17 08:36:52.698  1882  1904 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 08:36:52.698  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,03-17 08:36:52.698  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
03-17 08:36:52.698  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
03-17 08:36:52.698  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,03-17 08:36:52.708  6205  6337 I Gmail   : getAccountsCursor
,03-17 08:36:52.708  5801  6259 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,03-17 08:36:52.718  1882  1882 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-17 08:36:52.718  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
03-17 08:36:52.718  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
03-17 08:36:52.718  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
03-17 08:36:52.718  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,03-17 08:36:52.718  6314  6314 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,03-17 08:36:52.728  6205  6337 I Gmail   : master sync=false, engine sync=true,
03-17 08:36:52.728  5801  6259 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,03-17 08:36:52.728  5463  6260 I MediaStoreImporter: Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0,
,03-17 08:36:52.728  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac,
03-17 08:36:52.728  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
,03-17 08:36:52.738  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
03-17 08:36:52.738  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,03-17 08:36:52.738  4974  6264 E Babel   : UserRecoverableAuthException.
,03-17 08:36:52.738  4974  6264 E Babel   : eei: BadAuthentication
03-17 08:36:52.738  4974  6264 E Babel   : 	at eeg.a(Unknown Source)
03-17 08:36:52.738  4974  6264 E Babel   : 	at eeg.a(Unknown Source)
03-17 08:36:52.738  4974  6264 E Babel   : 	at eeg.a(Unknown Source)
03-17 08:36:52.738  4974  6264 E Babel   : 	at g.a(Unknown Source)
03-17 08:36:52.738  4974  6264 E Babel   : 	at cae.a(SourceFile:3089)
03-17 08:36:52.738  4974  6264 E Babel   : 	at cae.a(SourceFile:1131)
03-17 08:36:52.738  4974  6264 E Babel   : 	at cws.a(SourceFile:4333)
03-17 08:36:52.738  4974  6264 E Babel   : 	at cws.a(SourceFile:1419)
03-17 08:36:52.738  4974  6264 E Babel   : 	at crl.a(SourceFile:492)
03-17 08:36:52.738  4974  6264 E Babel   : 	at crl.a(SourceFile:1468)
03-17 08:36:52.738  4974  6264 E Babel   : 	at cqu.a(SourceFile:4416)
03-17 08:36:52.738  4974  6264 E Babel   : 	at cas.b(SourceFile:106)
03-17 08:36:52.738  4974  6264 E Babel   : 	at cap.d(SourceFile:335)
03-17 08:36:52.738  4974  6264 E Babel   : 	at caq.run(SourceFile:81)
03-17 08:36:52.738  4974  6264 E Babel   : Error getting auth token
03-17 08:36:52.738  4974  6264 E Babel   : dvm
03-17 08:36:52.738  4974  6264 E Babel   : 	at g.a(Unknown Source)
03-17 08:36:52.738  4974  6264 E Babel   : 	at cae.a(SourceFile:3089)
03-17 08:36:52.738  4974  6264 E Babel   : 	at cae.a(SourceFile:1131)
03-17 08:36:52.738  4974  6264 E Babel   : 	at cws.a(SourceFile:4333)
03-17 08:36:52.738  4974  6264 E Babel   : 	at cws.a(SourceFile:1419)
03-17 08:36:52.738  4974  6264 E Babel   : 	at crl.a(SourceFile:492)
03-17 08:36:52.738  4974  6264 E Babel   : 	at crl.a(SourceFile:1468)
03-17 08:36:52.738  4974  6264 E Babel   : 	at cqu.a(SourceFile:4416)
03-17 08:36:52.738  4974  6264 E Babel   : 	at cas.b(SourceFile:106)
03-17 08:36:52.738  4974  6264 E Babel   : ,	at cap.d(SourceFile:335)
03-17 08:36:52.738  4974  6264 E Babel   : 	at caq.run(SourceFile:81)
,03-17 08:36:52.748  5801  6259 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,03-17 08:36:52.748  6205  6243 I NotifUtils: Validating Notification, mapSize: 0 getAttention: true ignoreUnobtrusive: false
03-17 08:36:52.758  4974  6264 E Babel   : Account registration failed 1-Redacted-21
,03-17 08:36:52.758  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
03-17 08:36:52.758  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
03-17 08:36:52.758  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
03-17 08:36:52.758  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,03-17 08:36:52.758  4974  6264 E Babel   : cyp: null -- null
03-17 08:36:52.758  4974  6264 E Babel   : 	at cae.a(SourceFile:3121)
03-17 08:36:52.758  4974  6264 E Babel   : 	at cae.a(SourceFile:1131)
03-17 08:36:52.758  4974  6264 E Babel   : 	at cws.a(SourceFile:4333)
03-17 08:36:52.758  4974  6264 E Babel   : 	at cws.a(SourceFile:1419)
03-17 08:36:52.758  4974  6264 E Babel   : 	at crl.a(SourceFile:492)
03-17 08:36:52.758  4974  6264 E Babel   : 	at crl.a(SourceFile:1468)
03-17 08:36:52.758  4974  6264 E Babel   : 	at cqu.a(SourceFile:4416)
03-17 08:36:52.758  4974  6264 E Babel   : 	at cas.b(SourceFile:106)
03-17 08:36:52.758  4974  6264 E Babel   : 	at cap.d(SourceFile:335)
03-17 08:36:52.758  4974  6264 E Babel   : 	at caq.run(SourceFile:81)
,03-17 08:36:52.768  5801  6259 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,03-17 08:36:52.768   921  1718 D PMS     : acquireWL(30bf0abc): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4974 10112 null,
,03-17 08:36:52.768  4974  6343 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
03-17 08:36:52.768  4974  6343 D libc    : [NET] android_getaddrinfofornet-, err=8,
03-17 08:36:52.768  4974  6343 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
03-17 08:36:52.768  4974  6343 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
03-17 08:36:52.768  4974  6343 D libc    : [NET] android_getaddrinfo_proxy+
03-17 08:36:52.768  4974  6343 D libc    : [NET] android_getaddrinfo_proxy get netid:0
03-17 08:36:52.768   408  6347 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
,03-17 08:36:52.768   408  6347 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
03-17 08:36:52.778   921   950 I ActivityManager: Delay finish: com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver
03-17 08:36:52.778   408  6347 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS)
03-17 08:36:52.778   408  6347 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
03-17 08:36:52.778  4974  6343 D libc    : [NET] android_getaddrinfo_proxy-, success,
,03-17 08:36:52.788  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
03-17 08:36:52.788  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
03-17 08:36:52.788  4974  6264 I art     : Note: end time exceeds epoch: 
03-17 08:36:52.788  5801  6259 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
03-17 08:36:52.788  5801  6259 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true
03-17 08:36:52.788  5801  6259 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
03-17 08:36:52.788  5801  6259 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
,03-17 08:36:52.788  6314  6314 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@31451c4d(com.htc.providers.calendar.HtcCalendarProvider@399ab302)
03-17 08:36:52.788   921  4355 D PMS     : releaseWL(30bf0abc): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,03-17 08:36:52.788  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
03-17 08:36:52.788  5801  6259 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
03-17 08:36:52.788  5801  6259 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
03-17 08:36:52.788   921  1710 I ActivityManager: Resuming delayed broadcast
03-17 08:36:52.788  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
03-17 08:36:52.788  5801  6259 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
03-17 08:36:52.788  5801  6259 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
,03-17 08:36:52.798  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
03-17 08:36:52.798  5801  6259 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
03-17 08:36:52.798  5801  6259 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
,03-17 08:36:52.808  6314  6352 D CalendarProvider2: wait start:true
,03-17 08:36:52.808  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
,03-17 08:36:52.808  5801  6259 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
03-17 08:36:52.808  5801  6259 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
,03-17 08:36:52.818  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
,03-17 08:36:52.818  5801  6259 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
,03-17 08:36:52.818  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
03-17 08:36:52.818  5801  6259 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
03-17 08:36:52.818  1568  6354 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
03-17 08:36:52.818  1568  6354 I [PluginManager]RegisterService: handle notify Blinkfeed plugin client changed
,03-17 08:36:52.828  6293  6344 I Task_Calendar: Set ICALENDAR_UID to sync_data7 due to SDK_INT is 21
,03-17 08:36:52.828  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
03-17 08:36:52.828  5801  6259 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
03-17 08:36:52.828  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
03-17 08:36:52.828  5801  6259 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
03-17 08:36:52.828  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
03-17 08:36:52.828  5801  6259 W SoundPicker: TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
03-17 08:36:52.828  5801  6259 I SoundPicker: TurnFileToMediaUriService [checkFileExistence]
03-17 08:36:52.828  5801  6259 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
03-17 08:36:52.828  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
03-17 08:36:52.828  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
03-17 08:36:52.828  6205  6243 I NotifUtils: validateNotifications - cancelling 1729800001 for 61035162 / -317575340
,03-17 08:36:52.858  1882  3488 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native,
03-17 08:36:52.858  1882  3488 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-17 08:36:52.858  1882  3488 I GLSUser : [GLSUser] Extracting token using key: Auth
03-17 08:36:52.858  1882  3488 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-17 08:36:52.978   921  2373 I art     : Explicit concurrent mark sweep GC freed 11671(605KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/25MB, paused 1.942ms total 142.105ms
03-17 08:36:52.978   921   951 I ActivityManager: Delay finish: com.android.vending/com.google.android.finsky.widget.consumption.NowPlayingWidgetProvider
,03-17 08:36:52.978   921  4355 I ActivityManager: Resuming delayed broadcast
,03-17 08:36:52.988  1882  3488 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 08:36:52.998  4407  6356 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,03-17 08:36:52.998  4974  6343 I Babel   : connection state changed from UNKNOWN to CONNECTED
,03-17 08:36:53.008  4407  6356 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,03-17 08:36:53.008  6314  6352 D CalendarProvider2: wait end:false
03-17 08:36:53.008   921  1710 I ActivityManager: Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
03-17 08:36:53.008   921  1157 I ActivityManager: Resuming delayed broadcast
03-17 08:36:53.008   921  1515 D PMS     : acquireWL(3c65f6d): PARTIAL_WAKE_LOCK  AsyncService 0x1 5954 10167 null
03-17 08:36:53.018   921  2373 D PMS     : releaseWL(3c65f6d): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
03-17 08:36:53.018   921   950 D PMS     : acquireWL(329acc33): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 5954 10167 null
03-17 08:36:53.018  5801  6259 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,03-17 08:36:53.028   921  1716 D PMS     : acquireWL(1892abf0): PARTIAL_WAKE_LOCK  Icing 0x1 4407 10024 WorkSource{10024 com.google.android.gms}
,03-17 08:36:53.028  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac,
03-17 08:36:53.028  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:53.028  5801  6259 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
03-17 08:36:53.028  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
03-17 08:36:53.028  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122,
,03-17 08:36:53.028  6293  6344 D TodoTaskshortcut: update TASK shortcut>,
03-17 08:36:53.038  1882  3488 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 08:36:53.038   921   950 I ActivityManager: Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver
,03-17 08:36:53.038  4407  4962 I Icing   : updateResources: need to parse f{com.google.android.gms}
03-17 08:36:53.038   921  1716 D PMS     : releaseWL(329acc33): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,03-17 08:36:53.038  6266  6290 D HtcAlertService: No fired or scheduled alerts
03-17 08:36:53.038  6266  6290 D HtcAlertUtils: -- cancelReminderNotification --
,03-17 08:36:53.038   921  2373 I ActivityManager: Resuming delayed broadcast
,03-17 08:36:53.048  6266  6290 D HtcAlertUtils: broadcastExistReminder!
,03-17 08:36:53.048  5801  6259 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:53.048  1306  1306 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
03-17 08:36:53.048  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:53.048  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:53.048  5801  6259 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
,03-17 08:36:53.048  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
03-17 08:36:53.048  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,03-17 08:36:53.048  1882  2921 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-17 08:36:53.058  5829  6362 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
03-17 08:36:53.058  1882  1882 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-17 08:36:53.058  5463  6260 I MediaStoreImporter: Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,03-17 08:36:53.068  4407  4407 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-17 08:36:53.068  5801  6259 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,03-17 08:36:53.068  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
03-17 08:36:53.068  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,03-17 08:36:53.068  5801  6259 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
03-17 08:36:53.068  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4,
03-17 08:36:53.068  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
03-17 08:36:53.078   921  1157 D PMS     : releaseWL(1892abf0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,03-17 08:36:53.078  4974  6348 E Babel   : Unexpected exception while authenticating.
,03-17 08:36:53.078  4974  6348 E Babel   : eej: User intervention required. Notification has been pushed.
03-17 08:36:53.078  4974  6348 E Babel   : 	at eeg.b(Unknown Source)
03-17 08:36:53.078  4974  6348 E Babel   : 	,at eeg.b(Unknown Source)
03-17 08:36:53.078  4974  6348 E Babel   : 	at g.a(Unknown Source)
03-17 08:36:53.078  4974  6348 E Babel   : 	at cae.b(SourceFile:1146)
03-17 08:36:53.078  4974  6348 E Babel   : 	at dcg.run(SourceFile:5617)
03-17 08:36:53.078  4974  6348 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 08:36:53.078  4974  6348 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 08:36:53.078  4974  6348 E Babel   : 	at java.lang.Thread.run(Thread.java:818)
03-17 08:36:53.078  5801  6259 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
03-17 08:36:53.088  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
03-17 08:36:53.088  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
03-17 08:36:53.088  5801  6259 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
03-17 08:36:53.088  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
03-17 08:36:53.088  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,03-17 08:36:53.088  1212  1212 I RemoteViews: reapply : com.google.android.gms 4 40
,03-17 08:36:53.098  1306  1715 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
03-17 08:36:53.098  1306  1715 D DotMatrix: [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,03-17 08:36:53.098   921  1721 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4407, uid=10024, userID:0
03-17 08:36:53.098  5801  6259 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
03-17 08:36:53.098  1810  6363 E MDM     : [150] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-17 08:36:53.108  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
03-17 08:36:53.108  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
,03-17 08:36:53.108  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
03-17 08:36:53.108  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,03-17 08:36:53.108  5829  6362 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 57 ms] updated apps [took 56 ms] 
,03-17 08:36:53.118  4407  6364 D LocationInitializer: Restart initialization of location
,03-17 08:36:53.118   921  2373 I ActivityManager: Killing 5858:com.google.android.partnersetup/u0a27 (adj 15): empty #17
03-17 08:36:53.118   921  2373 D Process : killProcessQuiet, pid=5858
03-17 08:36:53.118   921  2373 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-17 08:36:53.228   921  1712 I ActivityManager: Recipient 5858,
,03-17 08:36:53.338  5801  6259 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,03-17 08:36:53.348  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
03-17 08:36:53.348  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
03-17 08:36:53.348  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
03-17 08:36:53.348  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,03-17 08:36:53.348   921  1401 D PMS     : acquireWL(1376e8fa): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 5463 10159 null
,03-17 08:36:53.368  5801  6259 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,03-17 08:36:53.368  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,03-17 08:36:53.378  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
,03-17 08:36:53.378  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8,
03-17 08:36:53.378  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
03-17 08:36:53.378   921  1712 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=5463, uid=10159, userID:0
,03-17 08:36:53.398   921  1401 I ActivityManager: Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=6368 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=arm64-v8a
,03-17 08:36:53.408  5801  6259 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,03-17 08:36:53.408   921  1719 D PMS     : releaseWL(1376e8fa): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,03-17 08:36:53.408  5463  6367 I MusicLeanback: Conditions not met for autocaching. okToAttempt=false
03-17 08:36:53.408  5463  6367 I MusicLeanback: Stop autocaching.
,03-17 08:36:53.408  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,03-17 08:36:53.408  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
,03-17 08:36:53.408  5801  6259 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
,03-17 08:36:53.408  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,03-17 08:36:53.418  5801  6259 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,03-17 08:36:53.418  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
03-17 08:36:53.418  5801  6259 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,03-17 08:36:53.438  5463  5463 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-17 08:36:53.438  5463  6391 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-17 08:36:53.438   921  1514 D Process : killProcessQuiet, pid=6003
03-17 08:36:53.438   921  1514 I ActivityManager: Killing 6003:com.htc.cs.dm/u0a99 (adj 15): empty #17
03-17 08:36:53.438   921  1514 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-17 08:36:53.498   921  2373 I ActivityManager: Recipient 6003
,03-17 08:36:53.498  6368  6368 D SyncApplication: Loading default preferences
,03-17 08:36:53.518  6368  6368 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,03-17 08:36:53.548   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 6,
03-17 08:36:53.548  1212  1212 D WIFI_ICON: WifiActivity: 3
03-17 08:36:53.548   921   921 E WifiTrafficPoller:  packet count Tx=147 Rx=225
03-17 08:36:53.548  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
03-17 08:36:53.548   921   921 E WifiTrafficPoller: notifying of data activity 3
,03-17 08:36:53.558   921   921 E WifiTrafficPoller: ADD_CLIENT: 7,
03-17 08:36:53.558   921  1149 D WifiService: New client listening to asynchronous messages
,03-17 08:36:53.578  6368  6368 D SyncApplication: Overriding preferences with custom values
,03-17 08:36:53.598  6368  6368 D SyncApplication: Updating preferences succeeded
,03-17 08:36:53.598  6368  6368 E SyncApplication: Application created.
,03-17 08:36:53.608  6368  6400 W VolumeInfo: Unable to read mount points,
03-17 08:36:53.608  6368  6400 W VolumeInfo: java.io.FileNotFoundException: /etc/vold.fstab: open failed: ENOENT (No such file or directory)
03-17 08:36:53.608  6368  6400 W VolumeInfo: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-17 08:36:53.608  6368  6400 W VolumeInfo: 	,at java.io.FileInputStream.<init>(FileInputStream.java:76)
03-17 08:36:53.608  6368  6400 W VolumeInfo: 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
03-17 08:36:53.608  6368  6400 W VolumeInfo: 	at java.io.FileReader.<init>(FileReader.java:66)
03-17 08:36:53.608  6368  6400 W VolumeInfo: 	at com.nero.android.common.VolumeInfo.getVolumeMountPoints(VolumeInfo.java:194)
03-17 08:36:53.608  6368  6400 W VolumeInfo: 	at com.nero.android.common.VolumeInfo.getVolumes(VolumeInfo.java:153)
03-17 08:36:53.608  6368  6400 W VolumeInfo: 	at com.nero.android.common.VolumeInfo.initializeVolumeIDs(VolumeInfo.java:474)
03-17 08:36:53.608  6368  6400 W VolumeInfo: 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:51)
03-17 08:36:53.608  6368  6400 W VolumeInfo: 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:1)
03-17 08:36:53.608  6368  6400 W VolumeInfo: 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
03-17 08:36:53.608  6368  6400 W VolumeInfo: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 08:36:53.608  6368  6400 W VolumeInfo: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 08:36:53.608  6368  6400 W VolumeInfo: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 08:36:53.608  6368  6400 W VolumeInfo: 	at java.lang.Thread.run(Thread.java:818)
03-17 08:36:53.608  6368  6400 W VolumeInfo: Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
03-17 08:36:53.608  6368  6400 W VolumeInfo: 	at libcore.io.Posix.open(Native Method)
03-17 08:36:53.608  6368  6400 W VolumeInfo: 	,at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-17 08:36:53.608  6368  6400 W VolumeInfo: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-17 08:36:53.608  6368  6400 W VolumeInfo: 	... 13 more
03-17 08:36:53.608  6368  6400 V VolumeInfo: Found 0 mount point(s)
03-17 08:36:53.608  6368  6400 V VolumeInfo: New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,03-17 08:36:53.608  6368  6400 D VolumeInfo: read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,03-17 08:36:53.618  6368  6368 I CalendarDefines: getNewCalendarAuthority()...
,03-17 08:36:53.618   921  1514 I PackageManager:  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=6368, uid=10005, userID:0
,03-17 08:36:53.618   921  1514 W PackageManager: Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
03-17 08:36:53.618   921  1157 I PackageManager:  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=6368, uid=10005, userID:0
03-17 08:36:53.618   921  1157 W PackageManager: Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,03-17 08:36:53.618  6368  6368 D SyncApplication: enableAppOperation()+
,03-17 08:36:53.618  6368  6400 D VolumeInfo: Read the volume-id from the sd card: {9B5E872B-8520-47C6-8BD3-3081C2E38355}
03-17 08:36:53.618  6368  6400 W VolumeInfo: Can not create volume ID for unmounted volume null
03-17 08:36:53.618  6368  6368 D SyncApplication: enableAppOperation()-,
,03-17 08:36:53.628  6368  6368 D HTCUtilities: isNeorSinged() + 
,03-17 08:36:53.628  5660  6366 W MediaManager: [DualLensScanUtil]	mmpCursor count is 0
,03-17 08:36:53.628  6368  6368 D HTCUtilities: sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,03-17 08:36:53.638  6368  6368 D HTCUtilities: isNeorSinged() return false
,03-17 08:36:53.648  6368  6368 D CDMountReceiver: whether to enable CD Auto-mount: true,
03-17 08:36:53.648  6368  6368 D CDMountReceiver: showNotification() contentText=If HTC Sync Manager setup doesn't start automatically on your computer, download it from www.htc.com/hsm
,03-17 08:36:53.648  6368  6368 I ActionCombine: replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal],
,03-17 08:36:53.668  6368  6368 D CDMountReceiver: enable CD Auto-mount: true
03-17 08:36:53.668   921   921 D PMS     : acquireWL(19a7cc11): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 921 1000 null,
03-17 08:36:53.668  6368  6404 D HTCUtilities: enable auto-mount
03-17 08:36:53.668   921  1020 D PMS     : acquireWL(32c54176): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 921 1000 null
03-17 08:36:53.678   921  1020 D PMS     : releaseWL(19a7cc11): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,03-17 08:36:53.678   921  1020 D PMS     : releaseWL(32c54176): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,03-17 08:36:53.678  6368  6404 I HtcMountManagerAdapter: mHtcMountManager is  null
03-17 08:36:53.678  6368  6404 I HtcMountManagerAdapter: mStorageManager is  not null
03-17 08:36:53.678  1306  1345 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
,03-17 08:36:53.688  6368  6403 D HTCUtilities: enable auto-mount
03-17 08:36:53.688  6368  6403 I HtcMountManagerAdapter: mHtcMountManager is  null
03-17 08:36:53.688  6368  6403 I HtcMountManagerAdapter: mStorageManager is  not null
,03-17 08:36:53.688   921  1515 D VoldConnector: SND -> {29 mountISO mount /system/etc/PCTOOL.ISO /sys/class/android_usb/f_mass_storage/lun0/file}
03-17 08:36:53.688   921  1721 D VoldConnector: SND -> {30 mountISO mount /system/etc/PCTOOL.ISO /sys/class/android_usb/f_mass_storage/lun0/file}
,03-17 08:36:53.688  1882  4937 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
03-17 08:36:53.698   921  1515 D MountService: mountISO: /system/etc/PCTOOL.ISO
03-17 08:36:53.698  4407  4407 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
03-17 08:36:53.698   921  1721 D MountService: mountISO: /system/etc/PCTOOL.ISO
,03-17 08:36:53.698  4407  4407 I Kids    : [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
,03-17 08:36:53.698  1212  1212 I RemoteViews: apply : com.nero.android.htc.sync 0 12 3 38
,03-17 08:36:53.708   921   921 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
03-17 08:36:53.708   921   921 D WifiDisplayAdapter:     Client/Owner: Client
03-17 08:36:53.708   921   921 D WifiDisplayAdapter:     GroupId: ,
03-17 08:36:53.708   921   921 D WifiDisplayAdapter:     Passphrase: 
03-17 08:36:53.708   921   921 D WifiDisplayAdapter:     SessionId: 0
03-17 08:36:53.708   921   921 D WifiDisplayAdapter:     IP Address: }
03-17 08:36:53.708   921   921 E WifiStateMachine: WiFiStateMachine SCAN ALARM
,03-17 08:36:53.718   921  1148 E WifiStateMachine: handleMessage: E msg.what=131143
03-17 08:36:53.718   921   921 D PMS     : releaseWL(eca5e42): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
03-17 08:36:53.718   921  1148 E WifiStateMachine: processMsg: ConnectedState
03-17 08:36:53.718   921  1148 E WifiStateMachine:  ConnectedState !CMD_START_SCAN -2 -2 ic=3 proc(ms):2 dur:146 rssi=-53 f=2457 sc=60 link=150 tx=10.7, 0.0, 0.0  rx=16.4 list=2457 [on:0 tx:0 rx:0 period:1592] from screen [on:0 period:-2088666916]
03-17 08:36:53.718   921  1148 E WifiStateMachine: processMsg: L2ConnectedState
03-17 08:36:53.718   921  1148 E WifiStateMachine:  L2ConnectedState !CMD_START_SCAN -2 -2 ic=3 proc(ms):4 dur:146 rssi=-53 f=2457 sc=60 link=150 tx=10.7, 0.0, 0.0  rx=16.4 list=2457 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-2088666915]
03-17 08:36:53.718   921  1148 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=10.68 rxSuccessRate=16.42 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-53
03-17 08:36:53.718   921  1148 E WifiStateMachine: WifiStateMachine CMD_START_SCAN with age=1458200213725 interval=40000 maxinterval=300000
03-17 08:36:53.718   921  1148 E WifiStateMachine: WifiStateMachine CMD_START_SCAN try full band scan age=1458200213725 interval=40000 maxinterval=300000
03-17 08:36:53.718   921  1148 E WifiStateMachine: WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
03-17 08:36:53.718   921  1148 E WifiStateMachine: WifiStateMachine CMD_START_SCAN full=false
03-17 08:36:53.718   921  1148 E WifiConfigStore: makeChannelList age=3600000 for "NG700"WPA_PSK max=6 bssids=1
03-17 08:36:53.718   921  1148 E WifiConfigStore: has f4:f2:6d:22:99:3e freq=2457 age=1632 ?=true
03-17 08:36:53.718   921  1148 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2457
03-17 08:36:53.718   921  1148 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY freq=2457"
03-17 08:36:53.718  1346  1346 D wpa_supplicant: wlan0: Control interface command 'SCAN TYPE=ONLY freq=2457'
03-17 08:36:53.718  1346  1346 D wpa_supplicant: wlan0: Setting scan request: 0.000000 sec
03-17 08:36:53.718  1346  1346 I wpa_supplicant: wpa_supplicant_scan enter
03-17 08:36:53.718  1346  1346 D wpa_supplicant: wlan0: Starting AP scan for wildcard SSID
03-17 08:36:53.718  1346  1346 D wpa_supplicant: WPS: Building WPS IE for Probe Request
03-17 08:36:53.718  1346  1346 D wpa_supplicant: WPS:  * Version (hardcoded 0x10)
03-17 08:36:53.718  1346  1346 D wpa_supplicant: WPS:  * Request Type
03-17 08:36:53.718  1346  1346 D wpa_supplicant: WPS:  * Config Methods (4288)
03-17 08:36:53.718  1346  1346 D wpa_supplicant: WPS:  * UUID-E
03-17 08:36:53.718  1346  1346 D wpa_supplicant: WPS:  * Primary Device Type
03-17 08:36:53.718  1346  1346 D wpa_supplicant: WPS:  * RF Bands (3)
03-17 08:36:53.718  1346  1346 D wpa_supplicant: WPS:  * Association State
03-17 08:36:53.718  1346  1346 D wpa_supplicant: WPS:  * Configuration Error (0)
03-17 08:36:53.718  1346  1346 D wpa_supplicant: WPS:  * Device Password ID (0)
03-17 08:36:53.718  1346  1346 D wpa_supplicant: WPS:  * Manufacturer
03-17 08:36:53.718  1346  1346 D wpa_supplicant: WPS:  * Model Name
03-17 08:36:53.718  1346  1346 D wpa_supplicant: WPS:  * Model Number
03-17 08:36:53.718  1346  1346 D wpa_supplicant: WPS:  * Device Name
03-17 08:36:53.718  1346  1346 D wpa_supplicant: WPS:  * Version2 (0x20)
03-17 08:36:53.718  1346  1346 D wpa_supplicant: P2P: * P2P IE header
03-17 08:36:53.718  1346  1346 D wpa_supplicant: P2P: * Capability dev=25 group=00
03-17 08:36:53.718  1346  1346 D wpa_supplicant: P2P: * Listen Channel: Regulatory Class 81 Channel 6
03-17 08:36:53.718  1346  1346 D wpa_supplicant: wlan0: Limit manual scan to specified channels
03-17 08:36:53.718  1346  1346 D wpa_supplicant: wlan0: Add radio work 'scan'@0x55687bd680
03-17 08:36:53.718  1346  1346 D wpa_supplicant: wlan0: First radio work item in the queue - schedule start immediately
03-17 08:36:53.718  1346  1346 D wpa_supplica,nt: wlan0: Starting radio work 'scan'@0x55687bd680 after 0.000031 second wait
03-17 08:36:53.718  1346  1346 D wpa_supplicant: wlan0: nl80211: scan request
03-17 08:36:53.718  1346  1346 D wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
03-17 08:36:53.718  1346  1346 D wpa_supplicant: nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
03-17 08:36:53.718  1346  1346 D wpa_supplicant: wlan0: nl80211: Scan trigger
03-17 08:36:53.718  1346  1346 D wpa_supplicant: wlan0: Event SCAN_STARTED (49) received
03-17 08:36:53.718  1346  1346 D wpa_supplicant: wlan0: Own scan request started a scan in 0.000077 seconds
03-17 08:36:53.718  1346  1346 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
03-17 08:36:53.718  1212  1212 I RemoteViews: apply : com.nero.android.htc.sync 1 12 3 53
03-17 08:36:53.718   921  1148 E WifiStateMachine: [1,458,200,213,728 ms] noteScanstart no scan source
03-17 08:36:53.718   921  1644 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
03-17 08:36:53.718   921  1644 E WifiMonitor: WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
03-17 08:36:53.728   921  1644 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
03-17 08:36:53.728   921  1644 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,03-17 08:36:53.728   921  1148 E WifiStateMachine: handleMessage: X
,03-17 08:36:53.728   921   951 I ActivityManager: Killing 6025:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
,03-17 08:36:53.728   921   951 D Process : killProcessQuiet, pid=6025
03-17 08:36:53.728   921   951 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-17 08:36:53.798  1346  1346 D wpa_supplicant: nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
03-17 08:36:53.798  1346  1346 D wpa_supplicant: wlan0: nl80211: New scan results available
03-17 08:36:53.798  1346  1346 D wpa_supplicant: nl80211: Scan included frequencies: 2457
03-17 08:36:53.798  1346  1346 D wpa_supplicant: wlan0: Event SCAN_RESULTS (3) received
03-17 08:36:53.798  1346  1346 I wpa_supplicant: Got an original EVENT_SCAN_RESULTS
03-17 08:36:53.798  1346  1346 D wpa_supplicant: wlan0: Scan completed in 0.082012 seconds
03-17 08:36:53.798  1346  1346 D wpa_supplicant: nl80211: Associated on 2457 MHz
03-17 08:36:53.798  1346  1346 D wpa_supplicant: nl80211: Associated with f4:f2:6d:22:99:3e
03-17 08:36:53.798  1346  1346 D wpa_supplicant: nl80211: Received scan results (5 BSSes)
03-17 08:36:53.798  1346  1346 D wpa_supplicant: nl80211: Scan results indicate BSS status with f4:f2:6d:22:99:3e as associated
03-17 08:36:53.798  1346  1346 I wpa_supplicant: [NULL] f0:f2:6d:22:99:3e freq=2457 level=-49
03-17 08:36:53.798  1346  1346 I wpa_supplicant: [NULL] f4:f2:6d:22:99:3e freq=2457 level=-53
03-17 08:36:53.798  1346  1346 I wpa_supplicant: [NULL] 00:1f:27:54:70:c0 freq=2412 level=-67
03-17 08:36:53.798  1346  1346 I wpa_supplicant: [NULL] 00:1f:27:54:70:c1 freq=2412 level=-69
03-17 08:36:53.798  1346  1346 I wpa_supplicant: [NULL] 00:1f:27:54:dd:e3 freq=2437 level=-73
03-17 08:36:53.798  1346  1346 D wpa_supplicant: wlan0: BSS: Start scan result update 4
03-17 08:36:53.798  1346  1346 D wpa_supplicant: BSS: last_scan_res_used=5/32
03-17 08:36:53.798  1346  1346 D wpa_supplicant: wlan0: Scan-only results received
,03-17 08:36:53.798  1346  1346 D wpa_supplicant: wlan0: Radio work 'scan'@0x55687bd680 done in 0.082747 seconds
03-17 08:36:53.798   921  1644 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
03-17 08:36:53.798   921  1644 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
03-17 08:36:53.798   921  1148 E WifiStateMachine: handleMessage: E msg.what=147461
03-17 08:36:53.798   921  1148 E WifiStateMachine: processMsg: ConnectedState
03-17 08:36:53.798   921  1148 E WifiStateMachine:  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
03-17 08:36:53.798   921  1148 E WifiStateMachine: processMsg: L2ConnectedState
03-17 08:36:53.798   921  1148 E WifiStateMachine:  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
03-17 08:36:53.798   921  1148 E WifiStateMachine: processMsg: ConnectModeState
03-17 08:36:53.798   921  1148 E WifiStateMachine:  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
03-17 08:36:53.798   921  1148 E WifiStateMachine: processMsg: DriverStartedState
03-17 08:36:53.798   921  1148 E WifiStateMachine:  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
03-17 08:36:53.798   921  1148 E WifiStateMachine: processMsg: SupplicantStartedState
03-17 08:36:53.798   921  1148 E WifiStateMachine:  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
03-17 08:36:53.798   921  1148 D WifiStateMachine: [MLHD] enter handleMediaLinkEvent SupplicantStartedState
03-17 08:36:53.798   921  1148 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
03-17 08:36:53.808  1346  1346 D wpa_supplicant: wlan0: Control interface command 'LIST_DONGLES'
03-17 08:36:53.808   921  1148 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
,03-17 08:36:53.838   921  1718 I ActivityManager: Recipient 6025,
,03-17 08:36:53.938   921  1148 E WifiStateMachine: [1,458,200,213,946 ms] noteScanEnd no scan source
03-17 08:36:53.938   921  1148 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
03-17 08:36:53.938  1346  1346 D wpa_supplicant: wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
03-17 08:36:53.938   921  1148 E WifiStateMachine: wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@2081c785 sup_state=COMPLETED debouncing=false
03-17 08:36:53.938   921  1148 E WifiAutoJoinController : NG700 f4:f2:6d:22:99:3e rssi=-53 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
03-17 08:36:53.938   921  1148 E WifiConfigStore: updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
03-17 08:36:53.938   921  1148 E WifiConfigStore: updateSavedNetworkHistory: HTC improve mode
03-17 08:36:53.938   921  1148 E WifiConfigStore:         got known scan result f4:f2:6d:22:99:3e key : "NG700"WPA_PSK num: 1 rssi=-53 freq=2457
03-17 08:36:53.938   921  1148 E WifiAutoJoinController : ktwtestwifi 00:1f:27:54:70:c0 rssi=-67 cap [WPA2-EAP-CCMP+TKIP][ESS] is not scored
03-17 08:36:53.938   921  1148 E WifiAutoJoinController : TEST_KTW01 00:1f:27:54:70:c1 rssi=-69 cap [WPA2-EAP-TKIP][ESS] is not scored
03-17 08:36:53.948   921  1148 E WifiAutoJoinController : RA-WINGS 00:1f:27:54:dd:e3 rssi=-73 cap [ESS] is not scored
,03-17 08:36:53.948   921  1148 E WifiAutoJoinController : NG700_GUEST f0:f2:6d:22:99:3e rssi=-49 cap [WPA2-PSK-CCMP][ESS] is not scored
03-17 08:36:53.948   921  1148 E WifiAutoJoinController : ageScanResultsOut delay 40000 size 5 now 1458200213952
03-17 08:36:53.948   921  1148 E WifiAutoJoinController : newSupplicantResults size=5 known=1 true
03-17 08:36:53.948   921  1148 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
03-17 08:36:53.948  1346  1346 D wpa_supplicant: wlan0: Control interface command 'STATUS-NO_EVENTS'
03-17 08:36:53.948   921  1148 E WifiAutoJoinController : attemptAutoJoin() status=bssid=f4:f2:6d:22:99:3e
03-17 08:36:53.948   921  1148 E WifiAutoJoinController : ssid=NG700
03-17 08:36:53.948   921  1148 E WifiAutoJoinController : id=0
03-17 08:36:53.948   921  1148 E WifiAutoJoinController : mode=station
03-17 08:36:53.948   921  1148 E WifiAutoJoinController : pairwise_cipher=CCMP
03-17 08:36:53.948   921  1148 E WifiAutoJoinController : group_cipher=CCMP
03-17 08:36:53.948   921  1148 E WifiAutoJoinController : key_mgmt=WPA2-PSK
03-17 08:36:53.948   921  1148 E WifiAutoJoinController : wpa_state=COMPLETED
03-17 08:36:53.948   921  1148 E WifiAutoJoinController : ip_address=192.168.1.102
03-17 08:36:53.948   921  1148 E WifiAutoJoinController : p2p_device_address=92:e7:c4:e6:4c:f8
03-17 08:36:53.948   921  1148 E WifiAutoJoinController : address=XX:XX:XX:XX:XX:XX
03-17 08:36:53.948   921  1148 E WifiAutoJoinController : uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
03-17 08:36:53.948   921  1148 E WifiAutoJoinController : attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
03-17 08:36:53.948   921  1148 E WifiAutoJoinController : attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-53,-127) num=(1,0)
03-17 08:36:53.948   921  1148 E WifiAutoJoinController : attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
03-17 08:36:53.948   921  1148 E WifiAutoJoinController : attemptRoam: "NG700"WPA_PSK Found f4:f2:6d:22:99:3e rssi=-53 freq=2457 Current: f4:f2:6d:22:99:3e
03-17 08:36:53.948   921  1148 D HtcWifiControlRoamOffload: : roamCandidate: nullcurrentBSSID: f4:f2:6d:22:99:3e
03-17 08:36:53.948   921  1148 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false
03-17 08:36:53.948   921  1148 E WifiAutoJoinController : Done attemptAutoJoin status=0
03-17 08:36:53.948   921  1148 E WifiConfigStore:  writeKnownNetworkHistory() num networks:1 needWrite=false
03-17 08:36:53.948   921  1148 E WifiStateMachine: handleMessage: X
,03-17 08:36:53.978  6314  6314 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: },
03-17 08:36:53.978  6314  6314 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
03-17 08:36:53.978  6266  6266 D ProviderChangeReceiver: ---------------------------------------------------
03-17 08:36:53.978  6266  6266 D ProviderChangeReceiver: ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,03-17 08:36:53.988  6266  6407 D HtcAlertService: start to updateAlertNotification!
,03-17 08:36:53.988   921  1515 D Process : killProcessQuiet, pid=6056
,03-17 08:36:53.988   921  1515 I ActivityManager: Killing 6056:com.google.android.apps.docs/u0a101 (adj 15): empty #17
03-17 08:36:53.988   921  1515 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-17 08:36:54.088   921  1514 I ActivityManager: Recipient 6056,
,03-17 08:36:54.108  6266  6407 D HtcAlertService: No fired or scheduled alerts
03-17 08:36:54.108  6266  6407 D HtcAlertUtils: -- cancelReminderNotification --
03-17 08:36:54.108  6266  6407 D HtcAlertUtils: broadcastExistReminder!
,03-17 08:36:54.108  1306  1306 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,03-17 08:36:54.548   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 7
03-17 08:36:54.548   921   921 E WifiTrafficPoller:  packet count Tx=147 Rx=225
03-17 08:36:54.548   921   921 E WifiTrafficPoller: notifying of data activity 0
03-17 08:36:54.558  1212  1212 D WIFI_ICON: WifiActivity: 0
,03-17 08:36:54.558  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,03-17 08:36:54.618  4594  4804 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js,
03-17 08:36:54.618  4594  4804 I jxcore-log: 
,03-17 08:36:54.788   921   921 E WifiDataStallTracker: DATA_MONITOR_POLL true Token 1
,03-17 08:36:54.798   921  6408 D WifiDataStallTracker: updateDataStallInfo: mDataStallTxRxSum={txSum=128 rxSum=114} preTxRxSum={txSum=120 rxSum=107},
03-17 08:36:54.798   921  6408 D WifiDataStallTracker: updateDataStallInfo: IN/OUT,
03-17 08:36:54.798   921  6408 D WifiDataStallTracker: onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,03-17 08:36:55.038  1882  1882 I ConfigService: onDestroy,
,03-17 08:36:55.088   921  1148 E WifiStateMachine: handleMessage: E msg.what=131155,
03-17 08:36:55.088   921  1148 E WifiStateMachine: processMsg: ConnectedState
03-17 08:36:55.088   921  1148 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-53 f=2457 sc=60 link=150 tx=10.7, 0.0, 0.0  rx=16.4 bcn=0 [on:0 tx:0 rx:0 period:1364] from screen [on:0 period:-2088665543] gl hn u24 rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
03-17 08:36:55.088   921  1148 E WifiStateMachine: processMsg: L2ConnectedState
03-17 08:36:55.088   921  1148 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-53 f=2457 sc=60 link=150 tx=10.7, 0.0, 0.0  rx=16.4 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-2088665542] gl hn u24 rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
03-17 08:36:55.088   921  1148 E WifiStateMachine:  get link layer stats 0
03-17 08:36:55.088   921  1148 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
03-17 08:36:55.088  1346  1346 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL',
,03-17 08:36:55.098  1346  1346 I wpa_supplicant: environment dirty rate=0 [4][0][0]
,03-17 08:36:55.108   921  1148 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 150
03-17 08:36:55.108   921  1148 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-54 linkspeed=150
,03-17 08:36:55.108   921  1148 E WifiConfigStore: updateConfiguration freq=2457 BSSID=f4:f2:6d:22:99:3e RSSI=-53 "NG700"WPA_PSK
03-17 08:36:55.108  1212  1212 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3
03-17 08:36:55.108   921  1148 E WifiStateMachine: calculateWifiScore freq=2457 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=7.34 txretriesrate=0.00 rxrate=10.21 userTriggerdPenalty0
03-17 08:36:55.108  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
03-17 08:36:55.108   921  1148 E WifiStateMachine:  good link -> stuck count =0
03-17 08:36:55.108   921  1148 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 60
,03-17 08:36:55.108   921  1148 E WifiStateMachine:  isHighRSSI       ---> score=65
03-17 08:36:55.108   921  1148 E WifiStateMachine: handleMessage: X
03-17 08:36:55.108   921  1166 D WifiWatchdogStateMachine: RSSI current: 3 new: -54, 3
,03-17 08:36:55.558   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 7,
03-17 08:36:55.558   921   921 E WifiTrafficPoller:  packet count Tx=147 Rx=225
,03-17 08:36:56.048  4594  4804 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js,
03-17 08:36:56.048  4594  4804 I jxcore-log: 
,03-17 08:36:56.068  4594  4804 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js,
03-17 08:36:56.068  4594  4804 I jxcore-log: 
,03-17 08:36:56.068  4594  4804 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js,
03-17 08:36:56.068  4594  4804 I jxcore-log: 
,03-17 08:36:56.118  4594  4804 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js,
03-17 08:36:56.118  4594  4804 I jxcore-log: 
,03-17 08:36:56.138  4594  4804 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js,
03-17 08:36:56.138  4594  4804 I jxcore-log: 
,03-17 08:36:56.138  4594  4804 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js,
03-17 08:36:56.138  4594  4804 I jxcore-log: 
,03-17 08:36:56.558   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 7
,03-17 08:36:56.558   921   921 E WifiTrafficPoller:  packet count Tx=147 Rx=226
03-17 08:36:56.558  1212  1212 D WIFI_ICON: WifiActivity: 1
,03-17 08:36:56.558   921   921 E WifiTrafficPoller: notifying of data activity 1
03-17 08:36:56.558  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,03-17 08:36:56.658   921   950 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=4407, uid=10024, userID:0,
03-17 08:36:56.658   921   951 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=4407, uid=10024, userID:0
,03-17 08:36:56.658   921  1515 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=4407, uid=10024, userID:0
03-17 08:36:56.658  4407  4939 I CheckinService: Done disabling old GoogleServicesFramework version
,03-17 08:36:56.888  6205  6234 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-17 08:36:56.898  4407  4407 I GAv4-SVC: Google Analytics 7.8.99 is starting up.
,03-17 08:36:57.218  3496  3571 I HtcModeClient: handler message = 4011,
03-17 08:36:57.218  3496  3571 E HtcModeClient: Check connection and retry 7 times.
,03-17 08:36:57.558   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 7
03-17 08:36:57.558  1212  1212 D WIFI_ICON: WifiActivity: 0
03-17 08:36:57.558   921   921 E WifiTrafficPoller:  packet count Tx=147 Rx=226
03-17 08:36:57.558  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,03-17 08:36:57.558   921   921 E WifiTrafficPoller: notifying of data activity 0
,03-17 08:36:57.798   921  1718 D Process : killProcessQuiet, pid=6102
03-17 08:36:57.798   921  1718 I ActivityManager: Killing 6102:com.htc.updater/u0a84 (adj 15): empty #17
,03-17 08:36:57.798   921  1718 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-17 08:36:57.878  1568  1809 D AutoSetting: service - handleMessage() stop self,
,03-17 08:36:57.908   921  1157 I ActivityManager: Recipient 6102,
,03-17 08:36:58.008  1568  1809 D AutoSetting: service - handleMessage() quit looper
,03-17 08:36:58.018  1568  1568 D AutoSetting: service - onDestroy() END
,03-17 08:36:58.108   921  1716 D Process : killProcessQuiet, pid=6182
03-17 08:36:58.108   921  1716 I ActivityManager: Killing 6182:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17
03-17 08:36:58.108   921  1716 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-17 08:36:58.108   921  1148 E WifiStateMachine: handleMessage: E msg.what=131155
03-17 08:36:58.108   921  1148 E WifiStateMachine: processMsg: ConnectedState
,03-17 08:36:58.108   921  1148 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-54 f=2457 sc=60 link=150 tx=7.3, 0.0, 0.0  rx=10.2 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-2088662520] gl hn u24 rssi=-49 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
03-17 08:36:58.108   921  1148 E WifiStateMachine: processMsg: L2ConnectedState
03-17 08:36:58.118   921  1148 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-54 f=2457 sc=60 link=150 tx=7.3, 0.0, 0.0  rx=10.2 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-2088662519] gl hn u24 rssi=-49 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
03-17 08:36:58.118   921  1148 E WifiStateMachine:  get link layer stats 0
03-17 08:36:58.118   921  1148 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
03-17 08:36:58.118  1346  1346 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
,03-17 08:36:58.128  1346  1346 I wpa_supplicant: environment dirty rate=0 [0][0][0]
03-17 08:36:58.128   921  1148 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 150
03-17 08:36:58.128   921  1148 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-53 linkspeed=150
,03-17 08:36:58.128   921  1148 E WifiConfigStore: updateConfiguration freq=2457 BSSID=f4:f2:6d:22:99:3e RSSI=-53 "NG700"WPA_PSK
03-17 08:36:58.128   921  1148 E WifiStateMachine: calculateWifiScore freq=2457 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=3.67 txretriesrate=0.00 rxrate=5.60 userTriggerdPenalty0
03-17 08:36:58.128   921  1148 E WifiStateMachine:  good link -> stuck count =0
03-17 08:36:58.128   921  1148 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 56
03-17 08:36:58.128   921  1148 E WifiStateMachine:  isHighRSSI       ---> score=61
,03-17 08:36:58.148  4594  4804 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js,
03-17 08:36:58.148  4594  4804 I jxcore-log: 
,03-17 08:36:58.158  4594  4804 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js,
03-17 08:36:58.158  4594  4804 I jxcore-log: 
,03-17 08:36:58.158  4594  4804 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js,
03-17 08:36:58.158  4594  4804 I jxcore-log: 
,03-17 08:36:58.208   921  2373 I ActivityManager: Recipient 6182,
,03-17 08:36:58.318   921  1148 E WifiStateMachine: handleMessage: X,
03-17 08:36:58.318  1212  1212 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3
03-17 08:36:58.318   921  1166 D WifiWatchdogStateMachine: RSSI current: 3 new: -53, 3
03-17 08:36:58.318  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
03-17 08:36:58.318   921  1401 D Process : killProcessQuiet, pid=5724
03-17 08:36:58.318   921  1401 I ActivityManager: Killing 5724:com.htc.demoflopackageinstaller/u0a16 (adj 15): empty #17
03-17 08:36:58.318   921  1401 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-17 08:36:58.428   921  1720 I ActivityManager: Recipient 5724
,03-17 08:36:58.518  4594  4804 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js,
03-17 08:36:58.518  4594  4804 I jxcore-log: 
,03-17 08:36:58.558   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 7,
03-17 08:36:58.558   921   921 E WifiTrafficPoller:  packet count Tx=147 Rx=226
,03-17 08:36:58.708  4594  4804 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js,
03-17 08:36:58.708  4594  4804 I jxcore-log: 
,03-17 08:36:58.748  4594  4804 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js,
03-17 08:36:58.748  4594  4804 I jxcore-log: 
,03-17 08:36:58.788  4594  4804 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js,
03-17 08:36:58.788  4594  4804 I jxcore-log: 
,03-17 08:36:58.808  4594  4804 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js,
03-17 08:36:58.808  4594  4804 I jxcore-log: 
,03-17 08:36:58.828  4594  4804 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js,
03-17 08:36:58.828  4594  4804 I jxcore-log: 
,03-17 08:36:58.948  4594  4804 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js,
03-17 08:36:58.948  4594  4804 I jxcore-log: 
,03-17 08:36:58.958  4594  4804 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js,
03-17 08:36:58.958  4594  4804 I jxcore-log: 
,03-17 08:36:58.988  4594  4804 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js,
03-17 08:36:58.988  4594  4804 I jxcore-log: 
,03-17 08:36:59.558   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 7
03-17 08:36:59.558   921   921 E WifiTrafficPoller:  packet count Tx=148 Rx=228
03-17 08:36:59.558  1212  1212 D WIFI_ICON: WifiActivity: 3
03-17 08:36:59.558   921   921 E WifiTrafficPoller: notifying of data activity 3
,03-17 08:36:59.558  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,03-17 08:36:59.798   921   921 E WifiDataStallTracker: DATA_MONITOR_POLL true Token 1
,03-17 08:36:59.798   921  6414 D WifiDataStallTracker: updateDataStallInfo: mDataStallTxRxSum={txSum=129 rxSum=115} preTxRxSum={txSum=128 rxSum=114}
,03-17 08:36:59.798   921  6414 D WifiDataStallTracker: updateDataStallInfo: IN/OUT
03-17 08:36:59.798   921  6414 D WifiDataStallTracker: onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,03-17 08:36:59.988   921  1137 D PMS     : acquireWL(30a2e250): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 921 1000 WorkSource{1000}
,03-17 08:36:59.988   921  1137 V AlarmManager: sending alarm PendingIntent{4939042: PendingIntentRecord{3dd4b853 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=82648, Int=0
,03-17 08:37:00.038   921   921 D PMS     : releaseWL(30a2e250): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,03-17 08:37:00.038  1212  2488 D WeatherUtility: Weather sync is On
,03-17 08:37:00.038  1212  2488 W WeatherTimeKeeper: [refreshWeatherData] no weather data
,03-17 08:37:00.048  1212  2086 I ClockController: schedule update now=1458200220055 next=59945
,03-17 08:37:00.048  1212  1212 I Clock   : updateClock:08:37 Europe/Warsaw
03-17 08:37:00.048  1212  1212 I Clock   : updateClock:08:37 Europe/Warsaw
03-17 08:37:00.048  1212  1212 I Clock   : updateClock:08:37 Europe/Warsaw,
,03-17 08:37:00.558   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 7
03-17 08:37:00.558   921   921 E WifiTrafficPoller:  packet count Tx=149 Rx=229,
,03-17 08:37:01.098   921  1021 I ActivityManager: Waited long enough for: ServiceRecord{12147910 u0 com.htc.musicenhancer/.EnhancerService}
,03-17 08:37:01.128   921  1148 E WifiStateMachine: handleMessage: E msg.what=131155
03-17 08:37:01.128   921  1148 E WifiStateMachine: processMsg: ConnectedState
,03-17 08:37:01.138   921  1148 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-53 f=2457 sc=60 link=150 tx=3.7, 0.0, 0.0  rx=5.6 bcn=0 [on:0 tx:0 rx:0 period:2816] from screen [on:0 period:-2088659498] gl hn u24 rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
03-17 08:37:01.138   921  1148 E WifiStateMachine: processMsg: L2ConnectedState,
03-17 08:37:01.138   921  1148 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-53 f=2457 sc=60 link=150 tx=3.7, 0.0, 0.0  rx=5.6 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-2088659497] gl hn u24 rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
03-17 08:37:01.138   921  1148 E WifiStateMachine:  get link layer stats 0
03-17 08:37:01.138   921  1148 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
03-17 08:37:01.138  1346  1346 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
,03-17 08:37:01.148  1346  1346 I wpa_supplicant: environment dirty rate=0 [2][0][0]
,03-17 08:37:01.148   921  1148 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 150
03-17 08:37:01.158  1212  1212 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3
03-17 08:37:01.148   921  1148 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-54 linkspeed=150
03-17 08:37:01.158  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
03-17 08:37:01.148   921  1148 E WifiConfigStore: updateConfiguration freq=2457 BSSID=f4:f2:6d:22:99:3e RSSI=-53 "NG700"WPA_PSK
03-17 08:37:01.148   921  1148 E WifiStateMachine: calculateWifiScore freq=2457 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=2.84 txretriesrate=0.00 rxrate=4.30 userTriggerdPenalty0
03-17 08:37:01.148   921  1148 E WifiStateMachine:  good link -> stuck count =0
,03-17 08:37:01.148   921  1148 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 56
03-17 08:37:01.148   921  1148 E WifiStateMachine:  isHighRSSI       ---> score=61
03-17 08:37:01.148   921  1148 E WifiStateMachine: handleMessage: X
03-17 08:37:01.158   921  1166 D WifiWatchdogStateMachine: RSSI current: 3 new: -54, 3
,03-17 08:37:01.388   467   467 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,03-17 08:37:01.558   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 7,
03-17 08:37:01.558   921   921 E WifiTrafficPoller:  packet count Tx=149 Rx=229
03-17 08:37:01.568  1212  1212 D WIFI_ICON: WifiActivity: 0
03-17 08:37:01.568   921   921 E WifiTrafficPoller: notifying of data activity 0
,03-17 08:37:01.568  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,03-17 08:37:01.978   921  1137 D PMS     : acquireWL(302eec49): PARTIAL_WAKE_LOCK  *alarm* 0x1 921 1000 WorkSource{10024},
03-17 08:37:01.988   921  1137 V AlarmManager: sending alarm PendingIntent{196f094e: PendingIntentRecord{2970ea6f com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1458200214215, Int=536832000
03-17 08:37:01.988   921  1137 V AlarmManager: sending alarm PendingIntent{d5bd37c: PendingIntentRecord{38710405 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=84639, Int=0
,03-17 08:37:01.988  4407  4407 V CheckinService: unknown intent received for checkin (Intent { flg=0x14 cmp=com.google.android.gms/.checkin.CheckinService$Receiver (has extras) })
,03-17 08:37:01.988   921  1710 D PMS     : acquireWL(18366c5a): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4407 10024 WorkSource{10024 com.google.android.gms},
,03-17 08:37:01.998   921  1718 D PMS     : acquireWL(450ab68): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4407 10024 WorkSource{10024 com.google.android.gms},
03-17 08:37:01.998   921  1401 D PMS     : releaseWL(18366c5a): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
,03-17 08:37:02.008   921   921 D PMS     : releaseWL(302eec49): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,03-17 08:37:02.018  4407  6415 I CheckinService: Checking schedule, now: 1458200222023 next: 1458200214215
03-17 08:37:02.018  4407  6415 I CheckinService: active receiver: enabled
03-17 08:37:02.018   921  1712 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=4407, uid=10024, userID:0
,03-17 08:37:02.028  4407  6415 I CheckinService: Preparing to send checkin request,
03-17 08:37:02.028  4407  6415 I EventLogService: Accumulating logs since 1458200177396
,03-17 08:37:02.108  4407  6415 I CheckinRequestBuilder: Checkin reason type: 11 attempt count: 1,
,03-17 08:37:02.108   921  1149 D WifiService: New client listening to asynchronous messages,
03-17 08:37:02.118   921   921 E WifiTrafficPoller: ADD_CLIENT: 8
,03-17 08:37:02.118   921  1720 I ActivityManager: Cannot resolve ContentProvider=com.google.android.wearable.settings
03-17 08:37:02.118  4407  6415 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,03-17 08:37:02.248  3496  3571 I HtcModeClient: handler message = 4011,
03-17 08:37:02.248  3496  3571 E HtcModeClient: Check connection and retry 8 times.
,03-17 08:37:02.298   921  1719 I art     : Explicit concurrent mark sweep GC freed 20464(1065KB) AllocSpace objects, 3(124KB) LOS objects, 33% free, 16MB/25MB, paused 1.674ms total 163.727ms
,03-17 08:37:02.398  1882  1903 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer,
03-17 08:37:02.398  1882  1903 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-17 08:37:02.398  1882  1903 I GLSUser : [GLSUser] Extracting token using key: Auth
03-17 08:37:02.398  1882  1903 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-17 08:37:02.408  1882  1903 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 08:37:02.438  4407  6415 W CheckinRequestBuilder: awaiting user notification for token,
03-17 08:37:02.438  1306  1717 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
03-17 08:37:02.438  1306  1717 D DotMatrix: [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix,
,03-17 08:37:02.438  1212  1212 I RemoteViews: reapply : com.google.android.gms 2 40
,03-17 08:37:02.498   921  4355 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6418 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,03-17 08:37:02.538  6418  6418 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
03-17 08:37:02.538  6418  6418 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 08:37:02.568   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8
03-17 08:37:02.568  1212  1212 D WIFI_ICON: WifiActivity: 1
03-17 08:37:02.568   921   921 E WifiTrafficPoller:  packet count Tx=149 Rx=232
03-17 08:37:02.568   921   921 E WifiTrafficPoller: notifying of data activity 1
,03-17 08:37:02.568  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,03-17 08:37:02.568  6418  6418 I MultiDex: VM with version 2.1.0 has multidex support
03-17 08:37:02.568  6418  6418 I MultiDex: install
03-17 08:37:02.568  6418  6418 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-17 08:37:02.598  6418  6418 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,03-17 08:37:02.648  6418  6418 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
03-17 08:37:02.648  6418  6418 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3c7acb3f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-17 08:37:02.648  6418  6418 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-17 08:37:02.658  1882  5304 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-17 08:37:02.658  1882  1882 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-17 08:37:02.668  4407  4407 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher },
,03-17 08:37:02.698  5308  5308 D WearableService: callingUid 10024, callindPid: 5308
03-17 08:37:02.698   921  1718 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4407, uid=10024, userID:0
,03-17 08:37:02.708  1810  2774 E MDM     : [126] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-17 08:37:02.718  4407  6442 D LocationInitializer: Restart initialization of location
,03-17 08:37:02.868   424  1673 I WVCdm   : CdmEngine::OpenSession
03-17 08:37:02.868   424  1673 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,03-17 08:37:02.878   424  1673 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,03-17 08:37:02.888   424  1673 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
,03-17 08:37:02.888   424  1673 D DrmWidevineDash: Service_Initialize: starts!
03-17 08:37:02.888   424  1673 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
03-17 08:37:02.888   424  1673 D QSEECOMAPI: : App is not loaded in QSEE
03-17 08:37:02.888   424  1673 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
03-17 08:37:02.888   424  1673 E QSEECOMAPI: : Error::Loading image failed with ret = -1
03-17 08:37:02.888   424  1673 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
03-17 08:37:02.888   424  1673 D QSEECOMAPI: : App is not loaded in QSEE
,03-17 08:37:02.908   424  1673 D QSEECOMAPI: : Loaded image: APP id = 8,
03-17 08:37:02.918   424  1673 D DrmWidevineDash: Service_Initialize: ends! returns 0
,03-17 08:37:02.918   424  1673 D QSAPPSVER: qsapps_get_capabilities: Capability from secure side: 0x0,
03-17 08:37:02.918   424  1673 D QSAPPSVER: qsapps_get_capabilities: returns 0
03-17 08:37:02.918   424  1673 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf47da000
03-17 08:37:02.918   424  1673 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf47da000
03-17 08:37:02.918   424  1673 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,03-17 08:37:02.918   553   563 D DrmLibTime: got the req here! ret=0,
03-17 08:37:02.918   553   563 D DrmLibTime: command id, time_cmd_id = 770
03-17 08:37:02.918   553   563 D DrmLibTime: time_getutcsec starts!
03-17 08:37:02.918   553   563 D DrmLibTime: QSEE Time Listener: time_getutcsec
03-17 08:37:02.918   553   563 D DrmLibTime: QSEE Time Listener: get_utc_seconds
03-17 08:37:02.918   553   563 D DrmLibTime: QSEE Time Listener: time_get_modem_time
03-17 08:37:02.918   553   563 D DrmLibTime: QSEE Time Listener: Checking if ATS_MODEM is set or not.
03-17 08:37:02.928   553   563 E QC-time-services: Receive Passed == base = 13, unit = 1, operation = 2, result = 0
03-17 08:37:02.928   553   563 D DrmLibTime: QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
03-17 08:37:02.928   553   563 D DrmLibTime: QSEE Time Listener: Retrieved Android system time: 1458200222
03-17 08:37:02.928   553   563 D DrmLibTime: time_getutcsec returns 0, sec = 1458200222; nsec = 0
,03-17 08:37:02.928   553   563 D DrmLibTime: time_getutcsec finished! 
03-17 08:37:02.928   553   563 D DrmLibTime: iotcl_continue_command finished! and return 0 
03-17 08:37:02.928   553   563 D DrmLibTime: before calling ioctl to read the next time_cmd
03-17 08:37:02.928   471   591 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
03-17 08:37:02.928   424  1673 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,03-17 08:37:02.928   424  1673 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0,
03-17 08:37:02.928   424  1673 D DrmWidevineDash: OEMCrypto_APIVersion: starts!,
03-17 08:37:02.928   424  1673 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-17 08:37:02.928   424  1673 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-17 08:37:02.928   424  1673 D DrmWidevineDash: hlos api version =  9
03-17 08:37:02.928   424  1673 D DrmWidevineDash: tz api version =  9
03-17 08:37:02.928   424  1673 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
03-17 08:37:02.928   424  1673 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
03-17 08:37:02.928   424  1673 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,03-17 08:37:02.968   424  1673 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
03-17 08:37:02.968   424  1673 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
03-17 08:37:02.968   424  1673 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
03-17 08:37:02.968   424  1673 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xf3e99928
03-17 08:37:02.968   424  1673 D DrmWidevineDash: OEMCrypto_OpenSession Session ID = 0
03-17 08:37:02.968   424  1673 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-17 08:37:02.968   424  1673 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-17 08:37:02.968   424  1673 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
03-17 08:37:02.968   424  1673 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
03-17 08:37:02.968   424  1673 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xab56ac98, dataLength=8,
03-17 08:37:02.968   424  1673 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-17 08:37:02.968   424  1673 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-17 08:37:02.968   424  1673 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
03-17 08:37:02.968   424  1673 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab44a858, wrapped_rsa_key_length=1280
03-17 08:37:02.968   424  1673 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,03-17 08:37:02.978   424  1673 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,03-17 08:37:02.978   424  1673 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
03-17 08:37:02.978   424  1673 I WVCdm   : CdmEngine::QueryKeyControlInfo
,03-17 08:37:02.978   424  1039 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4),
03-17 08:37:02.978   424  1039 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
03-17 08:37:02.978   424  1039 I WVCdm   : CdmEngine::GenerateKeyRequest
03-17 08:37:02.978   424  1039 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xab45eea8, idLength=0xf4b4d6f8
03-17 08:37:02.978   424  1039 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,03-17 08:37:02.998   424  1039 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
03-17 08:37:02.998   424  1039 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
03-17 08:37:02.998   424  1039 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
03-17 08:37:02.998   424  1039 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-17 08:37:02.998   424  1039 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-17 08:37:02.998   424  1039 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
03-17 08:37:02.998   424  1039 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 24,
03-17 08:37:02.998   424  1039 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0
03-17 08:37:02.998   424  1039 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!, current = 0xf4b4d70e, maximum = 0xf4b4d70f
03-17 08:37:02.998   424  1039 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-17 08:37:02.998   424  1039 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-17 08:37:02.998   424  1039 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0
03-17 08:37:02.998   424  1039 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
03-17 08:37:02.998   424  1039 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-17 08:37:02.998   424  1039 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-17 08:37:02.998   424  1039 D DrmWidevineDash: hlos api version =  9
03-17 08:37:02.998   424  1039 D DrmWidevineDash: tz api version =  9
,03-17 08:37:02.998   424  1039 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
03-17 08:37:02.998   424  1039 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf4b4d77c
03-17 08:37:02.998   424  1039 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-17 08:37:02.998   424  1039 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-17 08:37:02.998   424  1039 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
03-17 08:37:02.998   424  1039 D WVCdm   : PrepareKeyRequest: nonce=3052992382
03-17 08:37:02.998   424  1039 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab4cc450
03-17 08:37:02.998   424  1039 D DrmWidevineDash: message_length=1611, signature=0xab4ccaa0, signature_length=0xf4b4d6dc
,03-17 08:37:02.998   424  1039 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,03-17 08:37:03.148   424  1039 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
03-17 08:37:03.148   424  1039 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
03-17 08:37:03.148   424   424 I WVCdm   : CdmEngine::CloseSession
03-17 08:37:03.148   424   424 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
03-17 08:37:03.148   424   424 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-17 08:37:03.148   424   424 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-17 08:37:03.148   424   424 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
03-17 08:37:03.148   424   424 I WVCdm   : L3 Terminate.
03-17 08:37:03.148   424   424 D DrmWidevineDash: OEMCrypto_Terminate: starts!
03-17 08:37:03.148   424   424 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-17 08:37:03.148   424   424 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-17 08:37:03.148   424   424 D DrmWidevineDash: Service_Uninitialize: starts!
03-17 08:37:03.148   424   424 D QSEECOMAPI: : QSEECom_dealloc_memory ,
03-17 08:37:03.148   424   424 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 8
03-17 08:37:03.148   424   424 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
03-17 08:37:03.148   424   424 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,03-17 08:37:03.368  6447  6447 E cutils-trace: Error opening trace file: Permission denied (13),
03-17 08:37:03.368  6447  6447 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=36 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
03-17 08:37:03.368  6447  6447 I dex2oat : dex2oat: override thread count:4
,03-17 08:37:03.428  6447  6447 I dex2oat : dex2oat took 57.875ms (threads: 4),
,03-17 08:37:03.448  6418  6439 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
03-17 08:37:03.448  6418  6439 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.01
03-17 08:37:03.448  6418  6439 I Adreno-EGL: Build Date: 03/09/15 Mon
03-17 08:37:03.448  6418  6439 I Adreno-EGL: Local Branch: 
03-17 08:37:03.448  6418  6439 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
03-17 08:37:03.448  6418  6439 I Adreno-EGL: Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
03-17 08:37:03.448  6418  6439 I Adreno-EGL:                  d74aa161a12b9c6fc6332151
,03-17 08:37:03.558  6418  6439 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
03-17 08:37:03.558  6418  6439 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.01
03-17 08:37:03.558  6418  6439 I Adreno-EGL: Build Date: 03/09/15 Mon
03-17 08:37:03.558  6418  6439 I Adreno-EGL: Local Branch: 
03-17 08:37:03.558  6418  6439 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
03-17 08:37:03.558  6418  6439 I Adreno-EGL: Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
03-17 08:37:03.558  6418  6439 I Adreno-EGL:                  d74aa161a12b9c6fc6332151
,03-17 08:37:03.568   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8,
03-17 08:37:03.568   921   921 E WifiTrafficPoller:  packet count Tx=150 Rx=234
03-17 08:37:03.568  1212  1212 D WIFI_ICON: WifiActivity: 3
03-17 08:37:03.568   921   921 E WifiTrafficPoller: notifying of data activity 3
03-17 08:37:03.568  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,03-17 08:37:03.628   424  2002 I WVCdm   : CdmEngine::OpenSession
03-17 08:37:03.628   424  2002 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
03-17 08:37:03.628   424  2002 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,03-17 08:37:03.648   424  2002 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15,
03-17 08:37:03.648   424  2002 D DrmWidevineDash: Service_Initialize: starts!
,03-17 08:37:03.648   424  2002 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
03-17 08:37:03.648   424  2002 D QSEECOMAPI: : App is not loaded in QSEE
03-17 08:37:03.648   424  2002 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
03-17 08:37:03.648   424  2002 E QSEECOMAPI: : Error::Loading image failed with ret = -1
03-17 08:37:03.648   424  2002 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
03-17 08:37:03.648   424  2002 D QSEECOMAPI: : App is not loaded in QSEE
,03-17 08:37:03.668   921  1148 E WifiStateMachine: handleMessage: E msg.what=131326
03-17 08:37:03.668   921  1148 E WifiStateMachine: processMsg: ConnectedState
03-17 08:37:03.668   424  2002 D QSEECOMAPI: : Loaded image: APP id = 9
03-17 08:37:03.668   921  1148 E WifiStateMachine:  ConnectedState !what:131326 1 0
03-17 08:37:03.668   424  2002 D DrmWidevineDash: Service_Initialize: ends! returns 0
03-17 08:37:03.668   921  1148 E WifiStateMachine: processMsg: L2ConnectedState
03-17 08:37:03.668   921  1148 E WifiStateMachine:  L2ConnectedState !what:131326 1 0
,03-17 08:37:03.678   424  2002 D QSAPPSVER: qsapps_get_capabilities: Capability from secure side: 0x0
03-17 08:37:03.678   424  2002 D QSAPPSVER: qsapps_get_capabilities: returns 0
03-17 08:37:03.678   424  2002 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf47da000
,03-17 08:37:03.678   424  2002 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf47da000
03-17 08:37:03.678   424  2002 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,03-17 08:37:03.678   553   563 D DrmLibTime: got the req here! ret=0
03-17 08:37:03.678   553   563 D DrmLibTime: command id, time_cmd_id = 770
03-17 08:37:03.678   553   563 D DrmLibTime: time_getutcsec starts!
03-17 08:37:03.678   553   563 D DrmLibTime: QSEE Time Listener: time_getutcsec
03-17 08:37:03.678   553   563 D DrmLibTime: QSEE Time Listener: get_utc_seconds
03-17 08:37:03.678   553   563 D DrmLibTime: QSEE Time Listener: time_get_modem_time
,03-17 08:37:03.678   553   563 D DrmLibTime: QSEE Time Listener: Checking if ATS_MODEM is set or not.
03-17 08:37:03.678   921  1148 E WifiStateMachine: handleMessage: X
03-17 08:37:03.678   553   563 E QC-time-services: Receive Passed == base = 13, unit = 1, operation = 2, result = 0
03-17 08:37:03.678   553   563 D DrmLibTime: QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
03-17 08:37:03.678   553   563 D DrmLibTime: QSEE Time Listener: Retrieved Android system time: 1458200223
03-17 08:37:03.678   553   563 D DrmLibTime: time_getutcsec returns 0, sec = 1458200223; nsec = 0
03-17 08:37:03.678   553   563 D DrmLibTime: time_getutcsec finished! 
03-17 08:37:03.678   553   563 D DrmLibTime: iotcl_continue_command finished! and return 0 
03-17 08:37:03.678   553   563 D DrmLibTime: before calling ioctl to read the next time_cmd
03-17 08:37:03.678   471   591 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,03-17 08:37:03.688   424  2002 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,03-17 08:37:03.688   424  2002 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
03-17 08:37:03.688   424  2002 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
03-17 08:37:03.688   424  2002 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-17 08:37:03.688   424  2002 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-17 08:37:03.688   424  2002 D DrmWidevineDash: hlos api version =  9
03-17 08:37:03.688   424  2002 D DrmWidevineDash: tz api version =  9
03-17 08:37:03.688   424  2002 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
03-17 08:37:03.688   424  2002 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
03-17 08:37:03.688   424  2002 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,03-17 08:37:03.708   424  2002 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
03-17 08:37:03.708   424  2002 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
03-17 08:37:03.708   424  2002 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
03-17 08:37:03.708   424  2002 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xf3565928
03-17 08:37:03.708   424  2002 D DrmWidevineDash: OEMCrypto_OpenSession Session ID = 0
,03-17 08:37:03.708   424  2002 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-17 08:37:03.708   424  2002 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-17 08:37:03.708   424  2002 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
03-17 08:37:03.708   424  2002 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
03-17 08:37:03.708   424  2002 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xab56ae10, dataLength=8
03-17 08:37:03.708   424  2002 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-17 08:37:03.708   424  2002 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-17 08:37:03.708   424  2002 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
03-17 08:37:03.708   424  2002 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab46dcb0, wrapped_rsa_key_length=1280
,03-17 08:37:03.708   424  2002 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-17 08:37:03.708   424  2002 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,03-17 08:37:03.708   424  2002 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
03-17 08:37:03.708   424  2002 I WVCdm   : CdmEngine::QueryKeyControlInfo
,03-17 08:37:03.718   424  1039 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
03-17 08:37:03.718   424  1039 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
03-17 08:37:03.718   424  1039 I WVCdm   : CdmEngine::GenerateKeyRequest
03-17 08:37:03.718   424  1039 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xab45eec8, idLength=0xf4b4d6f8
03-17 08:37:03.718   424  1039 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,03-17 08:37:03.738   424  1039 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
03-17 08:37:03.738   424  1039 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
03-17 08:37:03.738   424  1039 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
03-17 08:37:03.738   424  1039 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-17 08:37:03.738   424  1039 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,03-17 08:37:03.738   424  1039 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
03-17 08:37:03.738   424  1039 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 24
03-17 08:37:03.738   424  1039 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0
03-17 08:37:03.738   424  1039 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!, current = 0xf4b4d70e, maximum = 0xf4b4d70f
03-17 08:37:03.738   424  1039 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-17 08:37:03.738   424  1039 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-17 08:37:03.738   424  1039 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0
03-17 08:37:03.738   424  1039 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
03-17 08:37:03.738   424  1039 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-17 08:37:03.738   424  1039 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-17 08:37:03.738   424  1039 D DrmWidevineDash: hlos api version =  9
03-17 08:37:03.738   424  1039 D DrmWidevineDash: tz api version =  9
03-17 08:37:03.738   424  1039 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
03-17 08:37:03.738   424  1039 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf4b4d77c
,03-17 08:37:03.738   424  1039 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-17 08:37:03.738   424  1039 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-17 08:37:03.738   424  1039 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
03-17 08:37:03.738   424  1039 D WVCdm   : PrepareKeyRequest: nonce=1050869975
03-17 08:37:03.738   424  1039 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab44a858
03-17 08:37:03.738   424  1039 D DrmWidevineDash: message_length=1642, signature=0xab574ea8, signature_length=0xf4b4d6dc
03-17 08:37:03.738   424  1039 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,03-17 08:37:03.898   424  1039 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-17 08:37:03.898   424  1039 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,03-17 08:37:03.908   424   424 I WVCdm   : CdmEngine::CloseSession
,03-17 08:37:03.908   424   424 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
03-17 08:37:03.908   424   424 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-17 08:37:03.908   424   424 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-17 08:37:03.908   424   424 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
03-17 08:37:03.908   424   424 I WVCdm   : L3 Terminate.
03-17 08:37:03.908   424   424 D DrmWidevineDash: OEMCrypto_Terminate: starts!
03-17 08:37:03.908   424   424 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-17 08:37:03.908   424   424 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-17 08:37:03.908   424   424 D DrmWidevineDash: Service_Uninitialize: starts!
03-17 08:37:03.908   424   424 D QSEECOMAPI: : QSEECom_dealloc_memory 
03-17 08:37:03.908   424   424 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 9
03-17 08:37:03.908   424   424 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
,03-17 08:37:03.908   424   424 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,03-17 08:37:03.938  4407  6415 I CheckinRequestBuilder: Classify the device as Phone.,
,03-17 08:37:03.988  4407  6415 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
03-17 08:37:03.988  4407  6415 D libc    : [NET] android_getaddrinfofornet-, err=8
,03-17 08:37:03.988  4407  6415 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
03-17 08:37:03.988  4407  6415 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
03-17 08:37:03.988  4407  6415 D libc    : [NET] android_getaddrinfo_proxy+
03-17 08:37:03.988  4407  6415 D libc    : [NET] android_getaddrinfo_proxy get netid:0
03-17 08:37:03.988   408  6459 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
,03-17 08:37:03.988   408  6459 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604,
03-17 08:37:03.988   408  6459 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS)
03-17 08:37:03.988   408  6459 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
03-17 08:37:03.988  4407  6415 D libc    : [NET] android_getaddrinfo_proxy-, success
,03-17 08:37:04.028   921  1137 D PMS     : acquireWL(27dd46ae): PARTIAL_WAKE_LOCK  *alarm* 0x1 921 1000 WorkSource{10072},
03-17 08:37:04.028   921  1137 V AlarmManager: sending alarm PendingIntent{3d544c4f: PendingIntentRecord{203ebfdc com.android.vending startService}}, i=null, t=0, cnt=1, w=1458200224035, Int=0
03-17 08:37:04.028   921   921 D PMS     : releaseWL(27dd46ae): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10072}
,03-17 08:37:04.098  4407  6415 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
03-17 08:37:04.098  4407  6415 D libc    : [NET] android_getaddrinfofornet-, err=8
,03-17 08:37:04.148   921  1148 E WifiStateMachine: handleMessage: E msg.what=131155,
03-17 08:37:04.148   921  1148 E WifiStateMachine: processMsg: ConnectedState
,03-17 08:37:04.158   921  1148 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-54 f=2457 sc=60 link=150 tx=2.8, 0.0, 0.0  rx=4.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2088656479] gl hn u24 rssi=-49 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
03-17 08:37:04.158   921  1148 E WifiStateMachine: processMsg: L2ConnectedState
03-17 08:37:04.158   921  1148 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-54 f=2457 sc=60 link=150 tx=2.8, 0.0, 0.0  rx=4.3 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-2088656477] gl hn u24 rssi=-49 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
03-17 08:37:04.158   921  1148 E WifiStateMachine:  get link layer stats 0
03-17 08:37:04.158   921  1148 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,03-17 08:37:04.158  1346  1346 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
03-17 08:37:04.158  1346  1346 I wpa_supplicant: environment dirty rate=0 [4][0][0]
03-17 08:37:04.158   921  1148 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 150
03-17 08:37:04.158   921  1148 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-55 linkspeed=150
03-17 08:37:04.158   921  1148 E WifiConfigStore: updateConfiguration freq=2457 BSSID=f4:f2:6d:22:99:3e RSSI=-54 "NG700"WPA_PSK
03-17 08:37:04.158   921  1148 E WifiStateMachine: calculateWifiScore freq=2457 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=3.42 txretriesrate=0.00 rxrate=5.15 userTriggerdPenalty0
03-17 08:37:04.158   921  1148 E WifiStateMachine:  good link -> stuck count =0
03-17 08:37:04.158   921  1148 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 56
03-17 08:37:04.158   921  1148 E WifiStateMachine:  isHighRSSI       ---> score=61
,03-17 08:37:04.158   921  1148 E WifiStateMachine: handleMessage: X
03-17 08:37:04.158  1212  1212 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3
03-17 08:37:04.158   921  1166 D WifiWatchdogStateMachine: RSSI current: 3 new: -55, 3
03-17 08:37:04.158  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,03-17 08:37:04.268  5660  6460 W MediaManager: [DualLensScanUtil],	mmpCursor count is 0
,03-17 08:37:04.278  4407  6415 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
,03-17 08:37:04.278  4407  6415 D libc    : [NET] android_getaddrinfofornet-, err=8
03-17 08:37:04.278  4407  6415 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
03-17 08:37:04.278  4407  6415 D libc    : [NET] android_getaddrinfofornet-, err=8
,03-17 08:37:04.298  4407  6415 I CheckinTask: Sending checkin request (8473 bytes)
,03-17 08:37:04.368  5884  5932 D Finsky  : [582] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.,
,03-17 08:37:04.368  5884  5884 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.,
,03-17 08:37:04.568   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8
03-17 08:37:04.568   921   921 E WifiTrafficPoller:  packet count Tx=166 Rx=244,
,03-17 08:37:04.708  4407  6415 I CheckinRequestBuilder: Checkin reason type: 11 attempt count: 1,
,03-17 08:37:04.708   921  2373 I ActivityManager: Cannot resolve ContentProvider=com.google.android.wearable.settings,
03-17 08:37:04.708  4407  6415 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,03-17 08:37:04.768  1882  1903 I art     : Explicit concurrent mark sweep GC freed 14322(829KB) AllocSpace objects, 6(504KB) LOS objects, 49% free, 4MB/8MB, paused 984us total 51.460ms,
,03-17 08:37:04.798   921   921 E WifiDataStallTracker: DATA_MONITOR_POLL true Token 1
,03-17 08:37:04.798   921  6461 D WifiDataStallTracker: updateDataStallInfo: mDataStallTxRxSum={txSum=149 rxSum=129} preTxRxSum={txSum=129 rxSum=115}
03-17 08:37:04.798   921  6461 D WifiDataStallTracker: updateDataStallInfo: IN/OUT
03-17 08:37:04.798   921  6461 D WifiDataStallTracker: onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,03-17 08:37:04.878  1882  1903 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer,
03-17 08:37:04.878  1882  1903 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-17 08:37:04.878  1882  1903 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-17 08:37:04.878  1882  1903 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-17 08:37:04.878  1882  1903 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 08:37:04.908  4407  6415 W CheckinRequestBuilder: awaiting user notification for token
,03-17 08:37:04.918  1306  1715 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
,03-17 08:37:04.918  1306  1715 D DotMatrix: [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,03-17 08:37:04.918  1212  1212 I RemoteViews: reapply : com.google.android.gms 2 40
,03-17 08:37:04.938  4407  6415 I CheckinRequestBuilder: Classify the device as Phone.
,03-17 08:37:04.958  4407  6415 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent),
,03-17 08:37:04.968  4407  6415 I CheckinService: Checking schedule, now: 1458200224976 next: 1458737056970,
03-17 08:37:04.968  4407  6415 I CheckinService: active receiver: disabled
03-17 08:37:04.968   921  1719 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4407, uid=10024, userID:0
,03-17 08:37:04.978   921  1137 D PMS     : acquireWL(23412e74): PARTIAL_WAKE_LOCK  *alarm* 0x1 921 1000 WorkSource{1000},
03-17 08:37:04.978   921   921 E WifiStateMachine: WiFiStateMachine SCAN ALARM
03-17 08:37:04.978   921  1137 V AlarmManager: sending alarm PendingIntent{3a4bcbda: PendingIntentRecord{2efe680b android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1458200224984, Int=20000
03-17 08:37:04.978   921  1148 E WifiStateMachine: handleMessage: E msg.what=131143
03-17 08:37:04.978   921   921 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
03-17 08:37:04.978   921   921 D WifiDisplayAdapter:     Client/Owner: Client
03-17 08:37:04.978   921   921 D WifiDisplayAdapter:     GroupId: 
03-17 08:37:04.978   921   921 D WifiDisplayAdapter:     Passphrase: 
03-17 08:37:04.978   921   921 D WifiDisplayAdapter:     SessionId: 0
03-17 08:37:04.978   921   921 D WifiDisplayAdapter:     IP Address: }
03-17 08:37:04.978   921  1148 E WifiStateMachine: processMsg: ConnectedState
03-17 08:37:04.978   921  1148 E WifiStateMachine:  ConnectedState !CMD_START_SCAN -2 -2 ic=4 proc(ms):0 dur:218 rssi=-55 f=2457 sc=60 link=150 tx=3.4, 0.0, 0.0  rx=5.2 list=2457 [on:0 tx:0 rx:0 period:819] from screen [on:0 period:-2088655652]
03-17 08:37:04.978   921  1148 E WifiStateMachine: processMsg: L2ConnectedState
03-17 08:37:04.978   921  1148 E WifiStateMachine:  L2ConnectedState !CMD_START_SCAN -2 -2 ic=4 proc(ms):1 dur:218 rssi=-55 f=2457 sc=60 link=150 tx=3.4, 0.0, 0.0  rx=5.2 list=2457 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-2088655651]
03-17 08:37:04.978   921  1148 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=3.42 rxSuccessRate=5.15 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-55
03-17 08:37:04.978   921  1148 E WifiStateMachine: WifiStateMachine CMD_START_SCAN with age=1458200224989 interval=40000 maxinterval=300000
03-17 08:37:04.978   921  1148 E WifiStateMachine: WifiStateMachine CMD_START_SCAN try full band scan age=1458200224989 interval=40000 maxinterval=300000
03-17 08:37:04.978   921  1148 E WifiStateMachine: WifiStateMachine CMD_START_SCAN full=true
03-17 08:37:04.978   921  1148 E WifiStateMachine: WifiStateMachine CMD_START_SCAN bump interval =60000
03-17 08:37:04.978   921  1148 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
03-17 08:37:04.978  1346  1346 D wpa_supplicant: wlan0: Control interface command 'SCAN TYPE=ONLY'
,03-17 08:37:04.978  1346  1346 D wpa_supplicant: wlan0: Setting scan request: 0.000000 sec
03-17 08:37:04.978  1346  1346 I wpa_supplicant: wpa_supplicant_scan enter
03-17 08:37:04.978  1346  1346 D wpa_supplicant: wlan0: Starting AP scan for wildcard SSID
03-17 08:37:04.988   921   921 D PMS     : releaseWL(23412e74): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
03-17 08:37:04.978  1346  1346 D wpa_supplicant: WPS: Building WPS IE for Probe Request
03-17 08:37:04.978  1346  1346 D wpa_supplicant: WPS:  * Version (hardcoded 0x10)
03-17 08:37:04.978  1346  1346 D wpa_supplicant: WPS:  * Request Type
03-17 08:37:04.978  1346  1346 D wpa_supplicant: WPS:  * Config Methods (4288)
03-17 08:37:04.978  1346  1346 D wpa_supplicant: WPS:  * UUID-E
03-17 08:37:04.978  1346  1346 D wpa_supplicant: WPS:  * Primary Device Type
03-17 08:37:04.978  1346  1346 D wpa_supplicant: WPS:  * RF Bands (3)
03-17 08:37:04.978  1346  1346 D wpa_supplicant: WPS:  * Association State
03-17 08:37:04.978  1346  1346 D wpa_supplicant: WPS:  * Configuration Error (0)
03-17 08:37:04.978  1346  1346 D wpa_supplicant: WPS:  * Device Password ID (0)
03-17 08:37:04.978  1346  1346 D wpa_supplicant: WPS:  * Manufacturer
03-17 08:37:04.978  1346  1346 D wpa_supplicant: WPS:  * Model Name
03-17 08:37:04.978  1346  1346 D wpa_supplicant: WPS:  * Model Number
03-17 08:37:04.978  1346  1346 D wpa_supplicant: WPS:  * Device Name
03-17 08:37:04.978  1346  1346 D wpa_supplicant: WPS:  * Version2 (0x20)
03-17 08:37:04.978  1346  1346 D wpa_supplicant: P2P: * P2P IE header
03-17 08:37:04.978  1346  1346 D wpa_supplicant: P2P: * Capability dev=25 group=00
03-17 08:37:04.978  1346  1346 D wpa_supplicant: P2P: * Listen Channel: Regulatory Class 81 Channel 6
03-17 08:37:04.978  1346  1346 D wpa_supplicant: wlan0: Add radio work 'scan'@0x55687bd680
,03-17 08:37:04.978  1346  1346 D wpa_supplicant: wlan0: First radio work item in the queue - schedule start immediately
03-17 08:37:04.978  1346  1346 D wpa_supplicant: wlan0: Starting radio work 'scan'@0x55687bd680 after 0.000045 second wait
03-17 08:37:04.978  1346  1346 D wpa_supplicant: wlan0: nl80211: scan request
03-17 08:37:04.978  1346  1346 D wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
03-17 08:37:04.978  1346  1346 D wpa_supplicant: nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
03-17 08:37:04.978  1346  1346 D wpa_supplicant: wlan0: nl80211: Scan trigger
03-17 08:37:04.978  1346  1346 D wpa_supplicant: wlan0: Event SCAN_STARTED (49) received
03-17 08:37:04.978  1346  1346 D wpa_supplicant: wlan0: Own scan request started a scan in 0.000088 seconds
03-17 08:37:04.978  1346  1346 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
03-17 08:37:04.978   921  1644 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
03-17 08:37:04.978   921  1644 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
03-17 08:37:04.978   921  1644 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
03-17 08:37:04.978   921  1644 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
03-17 08:37:04.978   921  1148 E WifiStateMachine: [1,458,200,224,991 ms] noteScanstart no scan source
03-17 08:37:04.978   921  1148 E WifiStateMachine: handleMessage: X
,03-17 08:37:04.988   921  1157 D PMS     : releaseWL(450ab68): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
,03-17 08:37:05.018  6158  6158 V SetupWizard: Connected to Gservices successfully
,03-17 08:37:05.028  4407  4407 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms,
03-17 08:37:05.028  4407  4407 I Kids    : [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
,03-17 08:37:05.038  1882  5425 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE,
,03-17 08:37:05.568   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8,
03-17 08:37:05.568   921   921 E WifiTrafficPoller:  packet count Tx=168 Rx=247
,03-17 08:37:05.738  1433  1703 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC >>,
03-17 08:37:05.738  1433  1703 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC <<
,03-17 08:37:06.568   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8
,03-17 08:37:06.568   921   921 E WifiTrafficPoller:  packet count Tx=168 Rx=247
03-17 08:37:06.568  1212  1212 D WIFI_ICON: WifiActivity: 0
03-17 08:37:06.568   921   921 E WifiTrafficPoller: notifying of data activity 0
03-17 08:37:06.568  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,03-17 08:37:07.158   921  1148 E WifiStateMachine: handleMessage: E msg.what=131155
03-17 08:37:07.158   921  1148 E WifiStateMachine: processMsg: ConnectedState
,03-17 08:37:07.168   921  1148 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2457 sc=60 link=150 tx=3.4, 0.0, 0.0  rx=5.2 bcn=0 [on:0 tx:0 rx:0 period:2181] from screen [on:0 period:-2088653468] gl hn u24 rssi=-50 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
03-17 08:37:07.168   921  1148 E WifiStateMachine: processMsg: L2ConnectedState
,03-17 08:37:07.168   921  1148 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2457 sc=60 link=150 tx=3.4, 0.0, 0.0  rx=5.2 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-2088653467] gl hn u24 rssi=-50 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
03-17 08:37:07.168   921  1148 E WifiStateMachine:  get link layer stats 0
03-17 08:37:07.168   921  1148 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
03-17 08:37:07.168  1346  1346 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
,03-17 08:37:07.248  1346  1346 I wpa_supplicant: environment dirty rate=0 [16][0][0]
03-17 08:37:07.248  1346  1346 D wpa_supplicant: nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
03-17 08:37:07.248  1346  1346 D wpa_supplicant: wlan0: nl80211: New scan results available
03-17 08:37:07.248  1346  1346 D wpa_supplicant: nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
03-17 08:37:07.248  1212  1212 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3
03-17 08:37:07.248  1346  1346 D wpa_supplicant: wlan0: Event SCAN_RESULTS (3) received
03-17 08:37:07.248  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
03-17 08:37:07.248  1346  1346 I wpa_supplicant: Got an original EVENT_SCAN_RESULTS
03-17 08:37:07.248   921  1148 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 150
03-17 08:37:07.248  1346  1346 D wpa_supplicant: wlan0: Scan completed in 2.261842 seconds
03-17 08:37:07.248   921  1148 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-54 linkspeed=150
03-17 08:37:07.248  1346  1346 D wpa_supplicant: nl80211: Associated on 2457 MHz
03-17 08:37:07.248  1346  1346 D wpa_supplicant: nl80211: Associated with f4:f2:6d:22:99:3e
03-17 08:37:07.248   921  1148 E WifiConfigStore: updateConfiguration freq=2457 BSSID=f4:f2:6d:22:99:3e RSSI=-54 "NG700"WPA_PSK
03-17 08:37:07.248  1346  1346 D wpa_supplicant: nl80211: Received scan results (9 BSSes)
03-17 08:37:07.248  1346  1346 D wpa_supplicant: nl80211: Scan results indicate BSS status with f4:f2:6d:22:99:3e as associated
03-17 08:37:07.248  1346  1346 I wpa_supplicant: [NULL] f0:f2:6d:22:99:3e freq=2457 level=-50
03-17 08:37:07.248  1346  1346 I wpa_supplicant: [NULL] f4:f2:6d:22:99:3e freq=2457 level=-54
03-17 08:37:07.248  1346  1346 I wpa_supplicant: [NULL] 00:1f:27:54:70:c1 freq=2412 level=-55
03-17 08:37:07.248  1346  1346 I wpa_supplicant: [NULL] 00:1f:27:54:70:c0 freq=2412 level=-55
03-17 08:37:07.248  1346  1346 I wpa_supplicant: [NULL] 00:1f:27:54:dd:ef freq=5240 level=-74
03-17 08:37:07.248  1346  1346 I wpa_supplicant: [NULL] 00:1f:27:54:dd:e0 freq=2437 level=-72
03-17 08:37:07.248  1346  1346 I wpa_supplicant: [NULL] 00:1f:27:54:dd:e3 freq=2437 level=-73,
03-17 08:37:07.248  1346  1346 I wpa_supplicant: [NULL] 00:1f:27:54:e0:43 freq=2462 level=-77
03-17 08:37:07.248  1346  1346 I wpa_supplicant: [NULL] 00:22:0d:46:1c:a3 freq=2462 level=-81
03-17 08:37:07.248  1346  1346 D wpa_supplicant: wlan0: BSS: Start scan result update 5
03-17 08:37:07.248   921  1148 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
03-17 08:37:07.248  1346  1346 D wpa_supplicant: wlan0: BSS: Add new id 5 BSSID 00:1f:27:54:dd:ef SSID '\x00',
03-17 08:37:07.248  1346  1346 D wpa_supplicant: wlan0: BSS: Add new id 6 BSSID 00:1f:27:54:dd:e0 SSID '\x00'
03-17 08:37:07.248  1346  1346 D wpa_supplicant: wlan0: BSS: Add new id 7 BSSID 00:1f:27:54:e0:43 SSID 'RA-WINGS'
03-17 08:37:07.248  1346  1346 D wpa_supplicant: wlan0: BSS: Add new id 8 BSSID 00:22:0d:46:1c:a3 SSID 'RA-WINGS'
03-17 08:37:07.248  1346  1346 D wpa_supplicant: BSS: last_scan_res_used=9/32
03-17 08:37:07.248  1346  1346 D wpa_supplicant: wlan0: Scan-only results received
03-17 08:37:07.248  1346  1346 D wpa_supplicant: wlan0: Radio work 'scan'@0x55687bd680 done in 2.263088 seconds
03-17 08:37:07.248   921  1148 E WifiStateMachine: calculateWifiScore freq=2457 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=9.71 txretriesrate=0.00 rxrate=8.58 userTriggerdPenalty0
03-17 08:37:07.248   921  1148 E WifiStateMachine:  good link -> stuck count =0
03-17 08:37:07.248   921  1148 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 60
03-17 08:37:07.248   921  1148 E WifiStateMachine:  isHighRSSI       ---> score=65
03-17 08:37:07.248   921  1148 E WifiStateMachine: handleMessage: X
03-17 08:37:07.248   921  1644 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 5 00:1f:27:54:dd:ef]
03-17 08:37:07.248   921  1644 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 6 00:1f:27:54:dd:e0]
03-17 08:37:07.248   921  1644 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 7 00:1f:27:54:e0:43]
03-17 08:37:07.248   921  1644 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 8 00:22:0d:46:1c:a3]
03-17 08:37:07.248   921  1644 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
03-17 08:37:07.248   921  1644 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
03-17 08:37:07.248   921  1148 E WifiStateMachine: handleMessage: E msg.what=147461
03-17 08:37:07.248   921  1166 D WifiWatchdogStateMachine: RSSI current: 3 new: -54, 3
03-17 08:37:07.248   921  1148 E WifiStateMachine: processMsg: ConnectedState
03-17 08:37:07.248   921  1148 E WifiStateMachine:  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
03-17 08:37:07.248   921  1148 E WifiStateMachine: processMsg: L2ConnectedState
03-17 08:37:07.248   921  1148 E WifiStateMachine:  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
03-17 08:37:07.248   921  1148 E WifiStateMachine: processMsg: ConnectModeState
03-17 08:37:07.248   921  1148 E WifiStateMachine:  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
03-17 08:37:07.248   921  1148 E WifiStateMachine: processMsg: DriverStartedState
03-17 08:37:07.248   921  1148 E WifiStateMachine:  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
03-17 08:37:07.248   921  1148 E WifiStateMachine: processMsg: SupplicantStartedState
03-17 08:37:07.248   921  1148 E WifiStateMachine:  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
03-17 08:37:07.248   921  1148 D WifiStateMachine: [MLHD] enter handleMediaLinkEvent SupplicantStartedState
03-17 08:37:07.248   921  1148 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
03-17 08:37:07.248  1346  1346 D wpa_supplicant: wlan0: Control interface command 'LIST_DONGLES'
03-17 08:37:07.248   921  1148 E WifiStateMachine: [1,458,200,227,261 ms] noteScanEnd no scan source
03-17 08:37:07.248   921  1148 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
03-17 08:37:07.258  1346  1346 D wpa_supplicant: wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
03-17 08:37:07.258   921  1148 E WifiStateMachine: wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@2081c785 sup_state=COMPLETED debouncing=false
03-17 08:37:07.258   921  1148 E WifiAutoJoinController : NG700 f4:f2:6d:22:99:3e rssi=-54 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
03-17 08:37:07.258   921  1148 E WifiConfigStore: updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
03-17 08:37:07.,258   921  1148 E WifiConfigStore: updateSavedNetworkHistory: HTC improve mode
03-17 08:37:07.258   921  1148 E WifiConfigStore:         got known scan result f4:f2:6d:22:99:3e key : "NG700"WPA_PSK num: 1 rssi=-54 freq=2457
03-17 08:37:07.258   921  1148 E WifiAutoJoinController : ktwtestwifi 00:1f:27:54:70:c0 rssi=-55 cap [WPA2-EAP-CCMP+TKIP][ESS] is not scored
03-17 08:37:07.258   921  1148 E WifiAutoJoinController : TEST_KTW01 00:1f:27:54:70:c1 rssi=-55 cap [WPA2-EAP-TKIP][ESS] is not scored
03-17 08:37:07.258   921  1148 E WifiAutoJoinController : RA-WINGS 00:1f:27:54:dd:e3 rssi=-73 cap [ESS] is not scored
03-17 08:37:07.258   921  1148 E WifiAutoJoinController : NG700_GUEST f0:f2:6d:22:99:3e rssi=-50 cap [WPA2-PSK-CCMP][ESS] is not scored
03-17 08:37:07.258   921  1148 E WifiAutoJoinController :  00:1f:27:54:dd:ef rssi=-74 cap [WPA-EAP-TKIP][WPA2-EAP-CCMP][ESS] is not scored
03-17 08:37:07.258   921  1148 E WifiAutoJoinController :  00:1f:27:54:dd:e0 rssi=-72 cap [WPA-EAP-TKIP][WPA2-EAP-CCMP][ESS] is not scored
03-17 08:37:07.258   921  1148 E WifiAutoJoinController : RA-WINGS 00:1f:27:54:e0:43 rssi=-77 cap [ESS] is not scored
03-17 08:37:07.258   921  1148 E WifiAutoJoinController : RA-WINGS 00:22:0d:46:1c:a3 rssi=-81 cap [ESS] is not scored
03-17 08:37:07.258   921  1148 E WifiAutoJoinController : ageScanResultsOut delay 40000 size 9 now 1458200227265
03-17 08:37:07.258   921  1148 E WifiAutoJoinController : newSupplicantResults size=9 known=1 true
03-17 08:37:07.258   921  1148 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
03-17 08:37:07.258  1346  1346 D wpa_supplicant: wlan0: Control interface command 'STATUS-NO_EVENTS'
03-17 08:37:07.258   921  1148 E WifiAutoJoinController : attemptAutoJoin() status=bssid=f4:f2:6d:22:99:3e
03-17 08:37:07.258   921  1148 E WifiAutoJoinController : ssid=NG700
03-17 08:37:07.258   921  1148 E WifiAutoJoinController : id=0
03-17 08:37:07.258   921  1148 E WifiAutoJoinController : mode=station
03-17 08:37:07.258   921  1148 E WifiAutoJoinController : pairwise_cipher=CCMP
03-17 08:37:07.258   921  1148 E WifiAutoJoinController : group_cipher=CCMP
03-17 08:37:07.258   921  1148 E WifiAutoJoinController : key_mgmt=WPA2-PSK
03-17 08:37:07.258   921  1148 E WifiAutoJoinController : wpa_state=COMPLETED
03-17 08:37:07.258   921  1148 E WifiAutoJoinController : ip_address=192.168.1.102
03-17 08:37:07.258   921  1148 E WifiAutoJoinController : p2p_device_address=92:e7:c4:e6:4c:f8
03-17 08:37:07.258   921  1148 E WifiAutoJoinController : address=XX:XX:XX:XX:XX:XX
03-17 08:37:07.258   921  1148 E WifiAutoJoinController : uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
03-17 08:37:07.258   921  1148 E WifiAutoJoinController : attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
03-17 08:37:07.258   921  1148 E WifiAutoJoinController : attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-54,-127) num=(1,0)
03-17 08:37:07.258   921  1148 E WifiAutoJoinController : attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
03-17 08:37:07.258   921  1148 E WifiAutoJoinController : attemptRoam: "NG700"WPA_PSK Found f4:f2:6d:22:99:3e rssi=-54 freq=2457 Current: f4:f2:6d:22:99:3e
03-17 08:37:07.258   921  1148 D HtcWifiControlRoamOffload: : roamCandidate: nullcurrentBSSID: f4:f2:6d:22:99:3e
03-17 08:37:07.258   921  1148 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false
03-17 08:37:07.258   921  1148 E WifiAutoJoinController : Done attemptAutoJoin status=0
03-17 08:37:07.258   921  1148 E WifiConfigStore:  writeKnownNetworkHistory() num networks:1 needWrite=false
03-17 08:37:07.258   921  1148 E WifiStateMachine: handleMessage: X
,03-17 08:37:07.258  3496  3571 I HtcModeClient: handler message = 4011
03-17 08:37:07.258  3496  3571 E HtcModeClient: Check connection and retry 9 times.
,03-17 08:37:07.268  1810  1810 D WifiManager: getScanResults: Base Package Name=com.google.android.gms, uid=10024
,03-17 08:37:07.568   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8
03-17 08:37:07.578  1212  1212 D WIFI_ICON: WifiActivity: 3
,03-17 08:37:07.568   921   921 E WifiTrafficPoller:  packet count Tx=169 Rx=249
03-17 08:37:07.578  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
03-17 08:37:07.568   921   921 E WifiTrafficPoller: notifying of data activity 3
,03-17 08:37:07.748   921  2373 D Process : killProcessQuiet, pid=6293
03-17 08:37:07.748   921  2373 I ActivityManager: Killing 6293:com.htc.task/u0a69 (adj 15): empty #17
,03-17 08:37:07.748   921  2373 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-17 08:37:07.858   921  1719 I ActivityManager: Recipient 6293
,03-17 08:37:07.958   921  2373 D Process : killProcessQuiet, pid=5801
03-17 08:37:07.958   921  2373 I ActivityManager: Killing 5801:com.htc.sdm/u0a79 (adj 15): empty #18
,03-17 08:37:07.958   921  2373 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-17 08:37:08.058   921   951 I ActivityManager: Recipient 5801
,03-17 08:37:08.568   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8
03-17 08:37:08.578   921   921 E WifiTrafficPoller:  packet count Tx=169 Rx=251
,03-17 08:37:08.578   921   921 E WifiTrafficPoller: notifying of data activity 1
03-17 08:37:08.578  1212  1212 D WIFI_ICON: WifiActivity: 1
03-17 08:37:08.578  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,03-17 08:37:09.578   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8,
03-17 08:37:09.578  1212  1212 D WIFI_ICON: WifiActivity: 0
03-17 08:37:09.578   921   921 E WifiTrafficPoller:  packet count Tx=169 Rx=251
03-17 08:37:09.578  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
03-17 08:37:09.578   921   921 E WifiTrafficPoller: notifying of data activity 0
,03-17 08:37:09.798   921   921 E WifiDataStallTracker: DATA_MONITOR_POLL true Token 1,
03-17 08:37:09.798   921  6465 D WifiDataStallTracker: updateDataStallInfo: mDataStallTxRxSum={txSum=150 rxSum=130} preTxRxSum={txSum=149 rxSum=129},
03-17 08:37:09.798   921  6465 D WifiDataStallTracker: updateDataStallInfo: IN/OUT
03-17 08:37:09.798   921  6465 D WifiDataStallTracker: onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,03-17 08:37:10.248   921  1148 E WifiStateMachine: handleMessage: E msg.what=131155,
03-17 08:37:10.248   921  1148 E WifiStateMachine: processMsg: ConnectedState
,03-17 08:37:10.248   921  1148 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-54 f=2457 sc=60 link=150 tx=9.7, 0.0, 0.0  rx=8.6 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-2088650381] gl hn u24 rssi=-49 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
03-17 08:37:10.248   921  1148 E WifiStateMachine: processMsg: L2ConnectedState
03-17 08:37:10.248   921  1148 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-54 f=2457 sc=60 link=150 tx=9.7, 0.0, 0.0  rx=8.6 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-2088650380] gl hn u24 rssi=-49 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
03-17 08:37:10.248   921  1148 E WifiStateMachine:  get link layer stats 0
03-17 08:37:10.248   921  1148 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
03-17 08:37:10.248  1346  1346 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
,03-17 08:37:10.268  1346  1346 I wpa_supplicant: environment dirty rate=0 [0][0][0]
03-17 08:37:10.268  1212  1212 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3
03-17 08:37:10.268   921  1148 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 150
,03-17 08:37:10.268  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
03-17 08:37:10.268   921  1148 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-55 linkspeed=150
03-17 08:37:10.268   921  1148 E WifiConfigStore: updateConfiguration freq=2457 BSSID=f4:f2:6d:22:99:3e RSSI=-54 "NG700"WPA_PSK
03-17 08:37:10.268   921  1148 E WifiStateMachine: calculateWifiScore freq=2457 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=4.85 txretriesrate=0.00 rxrate=9.29 userTriggerdPenalty0
03-17 08:37:10.268   921  1148 E WifiStateMachine:  good link -> stuck count =0
03-17 08:37:10.268   921  1148 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 56
,03-17 08:37:10.268   921  1148 E WifiStateMachine:  isHighRSSI       ---> score=61
03-17 08:37:10.268   921  1148 E WifiStateMachine: handleMessage: X
03-17 08:37:10.268   921  1166 D WifiWatchdogStateMachine: RSSI current: 3 new: -55, 3,
,03-17 08:37:10.578   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8,
03-17 08:37:10.578   921   921 E WifiTrafficPoller:  packet count Tx=169 Rx=260
03-17 08:37:10.578  1212  1212 D WIFI_ICON: WifiActivity: 1
03-17 08:37:10.578   921   921 E WifiTrafficPoller: notifying of data activity 1
03-17 08:37:10.578  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T],
,03-17 08:37:11.578   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8
,03-17 08:37:11.578   921   921 E WifiTrafficPoller:  packet count Tx=169 Rx=266
,03-17 08:37:12.088  1722  2168 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,03-17 08:37:12.088   921  1140 W SystemReader: Cannot find grip_rejection_width, use default value instead,
03-17 08:37:12.098   921  1719 D PMS     : acquireWL(20db2fe3): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4974 10112 null
,03-17 08:37:12.108  1722  2168 D AccTypeManager: Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,03-17 08:37:12.118  1491  2067 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false,
03-17 08:37:12.118  1491  2067 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
03-17 08:37:12.118  1491  1491 W Prism.AllAppsManager: AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
03-17 08:37:12.118   921  1020 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
03-17 08:37:12.128  1491  1491 I Launcher: Deferring update until onResume
03-17 08:37:12.128  1491  1491 D Launcher: waitUntilResume // bindAppsUpdated
,03-17 08:37:12.138  1722  2168 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,03-17 08:37:12.138   921   951 D PMS     : releaseWL(20db2fe3): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,03-17 08:37:12.148  1433  1433 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,03-17 08:37:12.158  1568  6470 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms,
03-17 08:37:12.158  1568  6470 I [PluginManager]RegisterService: handle notify Blinkfeed plugin client changed
,03-17 08:37:12.158  1722  2168 E ExternalAccountType: Unsupported attribute readOnly
,03-17 08:37:12.178  4407  6472 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,03-17 08:37:12.188  4407  6472 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.,
,03-17 08:37:12.198   921  1716 D PMS     : acquireWL(1bd3cbe): PARTIAL_WAKE_LOCK  AsyncService 0x1 5954 10167 null
03-17 08:37:12.198   921  1157 D PMS     : releaseWL(1bd3cbe): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,03-17 08:37:12.198   921  1710 D PMS     : acquireWL(d404c6c): PARTIAL_WAKE_LOCK  Icing 0x1 4407 10024 WorkSource{10024 com.google.android.gms}
,03-17 08:37:12.228  4407  4962 I Icing   : updateResources: need to parse f{com.google.android.gms}
,03-17 08:37:12.258   921   921 W PackageManager: Unable to load service info ResolveInfo{1ad3a570 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
,03-17 08:37:12.258   921   921 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
03-17 08:37:12.258   921   921 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
03-17 08:37:12.258   921   921 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
03-17 08:37:12.258   921   921 W PackageManager: 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
03-17 08:37:12.258   921   921 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
03-17 08:37:12.258   921   921 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
03-17 08:37:12.258   921   921 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
03-17 08:37:12.258   921   921 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739)
03-17 08:37:12.258   921   921 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-17 08:37:12.258   921   921 W PackageManager: 	at android.os.Looper.loop(Looper.java:155)
03-17 08:37:12.258   921   921 W PackageManager: 	at com.android.server.SystemServer.run(SystemServer.java:324)
03-17 08:37:12.258   921   921 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:225)
03-17 08:37:12.258   921   921 W PackageManager: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 08:37:12.258   921   921 W PackageManager: ,	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 08:37:12.258   921   921 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
03-17 08:37:12.258   921   921 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
03-17 08:37:12.268  3496  3571 I HtcModeClient: handler message = 4011
03-17 08:37:12.268  3496  3571 E HtcModeClient: Check connection and retry 10 times.
,03-17 08:37:12.288  1810  1810 V GmsNetworkLocationProvi: DISABLE
,03-17 08:37:12.298  1810  1810 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,03-17 08:37:12.318   921   921 I BackupManagerService: Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService},
,03-17 08:37:12.328   921  1020 D LocationProviderProxy: applying state to connected service
,03-17 08:37:12.368   921  1719 I art     : Explicit concurrent mark sweep GC freed 29889(1605KB) AllocSpace objects, 3(188KB) LOS objects, 33% free, 16MB/25MB, paused 1.584ms total 173.231ms
,03-17 08:37:12.368   921  1719 D PMS     : acquireWL(1e7f8ea): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 5954 10167 null
03-17 08:37:12.368   921  1514 D PMS     : releaseWL(d404c6c): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
03-17 08:37:12.368   921  1712 D PMS     : acquireWL(2c9877db): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1810 10024 WorkSource{10024 com.google.android.gms}
03-17 08:37:12.378   921  2373 D PMS     : releaseWL(2c9877db): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,03-17 08:37:12.378   921  1020 D LocationProviderProxy: applying state to connected service
,03-17 08:37:12.388   921  1157 D PMS     : releaseWL(1e7f8ea): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,03-17 08:37:12.388   921  1020 D PMS     : acquireWL(2514fd51): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1810 10024 WorkSource{10024 com.google.android.gms}
,03-17 08:37:12.388   921  1719 D PMS     : acquireWL(2cc4b9b6): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1810 10024 WorkSource{10024 com.google.android.gms}
03-17 08:37:12.398   921  1712 D PMS     : releaseWL(2cc4b9b6): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,03-17 08:37:12.398   921  1514 D PMS     : releaseWL(2514fd51): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,03-17 08:37:12.398   921   921 D PMS     : acquireWL(35dabb42): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1810 10024 WorkSource{10024 com.google.android.gms}
,03-17 08:37:12.398  5829  6477 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
03-17 08:37:12.408   921  1515 D PMS     : releaseWL(35dabb42): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,03-17 08:37:12.448  5829  6477 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 45 ms] updated apps [took 45 ms] 
,03-17 08:37:12.578   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8
03-17 08:37:12.578   921   921 E WifiTrafficPoller:  packet count Tx=170 Rx=267
03-17 08:37:12.578   921   921 E WifiTrafficPoller: notifying of data activity 3
,03-17 08:37:12.578  1212  1212 D WIFI_ICON: WifiActivity: 3
03-17 08:37:12.578  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,03-17 08:37:13.268   921  1148 E WifiStateMachine: handleMessage: E msg.what=131155
03-17 08:37:13.268   921  1148 E WifiStateMachine: processMsg: ConnectedState
,03-17 08:37:13.268   921  1148 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2457 sc=60 link=150 tx=4.9, 0.0, 0.0  rx=9.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2088647360] gl hn u24 rssi=-50 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
03-17 08:37:13.268   921  1148 E WifiStateMachine: processMsg: L2ConnectedState
03-17 08:37:13.278   921  1148 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2457 sc=60 link=150 tx=4.9, 0.0, 0.0  rx=9.3 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-2088647358] gl hn u24 rssi=-50 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
03-17 08:37:13.278   921  1148 E WifiStateMachine:  get link layer stats 0
03-17 08:37:13.278   921  1148 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
03-17 08:37:13.278  1346  1346 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
,03-17 08:37:13.288  1346  1346 I wpa_supplicant: environment dirty rate=0 [1][0][0]
,03-17 08:37:13.288   921  1148 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 150
03-17 08:37:13.288   921  1148 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-54 linkspeed=150
03-17 08:37:13.288   921  1148 E WifiConfigStore: updateConfiguration freq=2457 BSSID=f4:f2:6d:22:99:3e RSSI=-54 "NG700"WPA_PSK
,03-17 08:37:13.288   921  1148 E WifiStateMachine: calculateWifiScore freq=2457 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=2.93 txretriesrate=0.00 rxrate=9.64 userTriggerdPenalty0
03-17 08:37:13.288  1212  1212 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3
03-17 08:37:13.288   921  1148 E WifiStateMachine:  good link -> stuck count =0
03-17 08:37:13.288  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,03-17 08:37:13.288   921  1148 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 56
03-17 08:37:13.288   921  1148 E WifiStateMachine:  isHighRSSI       ---> score=61
03-17 08:37:13.288   921  1148 E WifiStateMachine: handleMessage: X
03-17 08:37:13.288   921  1166 D WifiWatchdogStateMachine: RSSI current: 3 new: -54, 3
,03-17 08:37:13.578   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8
03-17 08:37:13.578  1212  1212 D WIFI_ICON: WifiActivity: 0
,03-17 08:37:13.578   921   921 E WifiTrafficPoller:  packet count Tx=170 Rx=267
03-17 08:37:13.578  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
03-17 08:37:13.578   921   921 E WifiTrafficPoller: notifying of data activity 0
,03-17 08:37:13.618  1491  2067 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
03-17 08:37:13.618  1491  2067 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@3508dd95 +
03-17 08:37:13.618  1491  2067 I Prism.WidgetManager: onLoadItems() +
,03-17 08:37:13.658  1491  2067 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,03-17 08:37:13.848  1491  2067 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,03-17 08:37:13.968  1491  2067 W asset   : Copying FileAsset 0x559ea13cd0 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.,
,03-17 08:37:14.038  1491  2067 E Prism.WidgetManager: The same lists. No need to update. skip it.
,03-17 08:37:14.038  1491  2067 I Prism.WidgetManager: onLoadItems() -
03-17 08:37:14.038  1491  2067 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@3508dd95 -
,03-17 08:37:14.158  1433  2172 D PhoneApp: EVENT_QUERY_MO_PACKAGES,
03-17 08:37:14.158  1433  2172 D PhoneApp: -- N1 =0,
03-17 08:37:14.158  1433  2172 D PhoneApp: -- N2 =0,
03-17 08:37:14.158  1433  2172 D PhoneApp: -- N3 =0,
,03-17 08:37:14.578   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8
03-17 08:37:14.578  1212  1212 D WIFI_ICON: WifiActivity: 1
,03-17 08:37:14.578   921   921 E WifiTrafficPoller:  packet count Tx=170 Rx=269
03-17 08:37:14.588  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
03-17 08:37:14.578   921   921 E WifiTrafficPoller: notifying of data activity 1
,03-17 08:37:14.798   921   921 E WifiDataStallTracker: DATA_MONITOR_POLL true Token 1,
03-17 08:37:14.798   921  6479 D WifiDataStallTracker: updateDataStallInfo: mDataStallTxRxSum={txSum=151 rxSum=131} preTxRxSum={txSum=150 rxSum=130}
03-17 08:37:14.798   921  6479 D WifiDataStallTracker: updateDataStallInfo: IN/OUT
03-17 08:37:14.798   921  6479 D WifiDataStallTracker: onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,03-17 08:37:15.578   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8
03-17 08:37:15.578   921   921 E WifiTrafficPoller:  packet count Tx=170 Rx=269
03-17 08:37:15.588  1212  1212 D WIFI_ICON: WifiActivity: 0
03-17 08:37:15.578   921   921 E WifiTrafficPoller: notifying of data activity 0
03-17 08:37:15.588  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,03-17 08:37:16.288   921  1148 E WifiStateMachine: handleMessage: E msg.what=131155,
03-17 08:37:16.288   921  1148 E WifiStateMachine: processMsg: ConnectedState
03-17 08:37:16.288   921  1148 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-54 f=2457 sc=60 link=150 tx=2.9, 0.0, 0.0  rx=9.6 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2088644340] gl hn u24 rssi=-49 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
03-17 08:37:16.288   921  1148 E WifiStateMachine: processMsg: L2ConnectedState
03-17 08:37:16.288   921  1148 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-54 f=2457 sc=60 link=150 tx=2.9, 0.0, 0.0  rx=9.6 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-2088644339] gl hn u24 rssi=-49 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
03-17 08:37:16.288   921  1148 E WifiStateMachine:  get link layer stats 0
03-17 08:37:16.298   921  1148 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
03-17 08:37:16.298  1346  1346 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
,03-17 08:37:16.308  1346  1346 I wpa_supplicant: environment dirty rate=0 [0][0][0],
03-17 08:37:16.308   921  1148 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 150
03-17 08:37:16.308   921  1148 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-54 linkspeed=150
03-17 08:37:16.308   921  1148 E WifiConfigStore: updateConfiguration freq=2457 BSSID=f4:f2:6d:22:99:3e RSSI=-54 "NG700"WPA_PSK
,03-17 08:37:16.308   921  1148 E WifiStateMachine: calculateWifiScore freq=2457 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=1.46 txretriesrate=0.00 rxrate=5.82 userTriggerdPenalty0
03-17 08:37:16.308   921  1148 E WifiStateMachine:  good link -> stuck count =0,
03-17 08:37:16.308   921  1148 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 56
03-17 08:37:16.308   921  1148 E WifiStateMachine:  isHighRSSI       ---> score=61
03-17 08:37:16.308   921  1148 E WifiStateMachine: handleMessage: X
,03-17 08:37:16.308  1212  1212 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3
03-17 08:37:16.308   921  1166 D WifiWatchdogStateMachine: RSSI current: 3 new: -54, 3
03-17 08:37:16.308  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,03-17 08:37:16.588   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8
,03-17 08:37:16.588   921   921 E WifiTrafficPoller:  packet count Tx=170 Rx=269
,03-17 08:37:17.288  3496  3571 I HtcModeClient: handler message = 4011,
03-17 08:37:17.288  3496  3571 E HtcModeClient: Check connection and retry 11 times.
,03-17 08:37:17.588   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8
03-17 08:37:17.588  1212  1212 D WIFI_ICON: WifiActivity: 3
03-17 08:37:17.588   921   921 E WifiTrafficPoller:  packet count Tx=171 Rx=271
03-17 08:37:17.588   921   921 E WifiTrafficPoller: notifying of data activity 3
,03-17 08:37:17.588  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,03-17 08:37:18.588   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8
03-17 08:37:18.588  1212  1212 D WIFI_ICON: WifiActivity: 0
,03-17 08:37:18.588   921   921 E WifiTrafficPoller:  packet count Tx=171 Rx=271
03-17 08:37:18.588  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
03-17 08:37:18.588   921   921 E WifiTrafficPoller: notifying of data activity 0
,03-17 08:37:19.308   921  1148 E WifiStateMachine: handleMessage: E msg.what=131155,
03-17 08:37:19.308   921  1148 E WifiStateMachine: processMsg: ConnectedState
03-17 08:37:19.308   921  1148 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-54 f=2457 sc=60 link=150 tx=1.5, 0.0, 0.0  rx=5.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2088641320] gl hn u24 rssi=-49 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
03-17 08:37:19.308   921  1148 E WifiStateMachine: processMsg: L2ConnectedState
03-17 08:37:19.318   921  1148 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-54 f=2457 sc=60 link=150 tx=1.5, 0.0, 0.0  rx=5.8 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-2088641318] gl hn u24 rssi=-49 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
03-17 08:37:19.318   921  1148 E WifiStateMachine:  get link layer stats 0
03-17 08:37:19.318   921  1148 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,03-17 08:37:19.318  1346  1346 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
,03-17 08:37:19.328  1346  1346 I wpa_supplicant: environment dirty rate=0 [1][0][0]
03-17 08:37:19.328  1212  1212 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3
03-17 08:37:19.328   921  1148 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 150
03-17 08:37:19.338  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
03-17 08:37:19.328   921  1148 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-54 linkspeed=150
03-17 08:37:19.328   921  1148 E WifiConfigStore: updateConfiguration freq=2457 BSSID=f4:f2:6d:22:99:3e RSSI=-54 "NG700"WPA_PSK
03-17 08:37:19.328   921  1148 E WifiStateMachine: calculateWifiScore freq=2457 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=1.23 txretriesrate=0.00 rxrate=3.91 userTriggerdPenalty0
03-17 08:37:19.328   921  1148 E WifiStateMachine:  good link -> stuck count =0
03-17 08:37:19.328   921  1148 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 56
03-17 08:37:19.328   921  1148 E WifiStateMachine:  isHighRSSI       ---> score=61
03-17 08:37:19.328   921  1166 D WifiWatchdogStateMachine: RSSI current: 3 new: -54, 3
,03-17 08:37:19.338   921  1148 E WifiStateMachine: handleMessage: X
,03-17 08:37:19.588   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8,
03-17 08:37:19.588   921   921 E WifiTrafficPoller:  packet count Tx=171 Rx=271
,03-17 08:37:19.798   921   921 E WifiDataStallTracker: DATA_MONITOR_POLL true Token 1,
03-17 08:37:19.798   921  6480 D WifiDataStallTracker: updateDataStallInfo: mDataStallTxRxSum={txSum=152 rxSum=132} preTxRxSum={txSum=151 rxSum=131}
03-17 08:37:19.798   921  6480 D WifiDataStallTracker: updateDataStallInfo: IN/OUT
03-17 08:37:19.798   921  6480 D WifiDataStallTracker: onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,03-17 08:37:20.588   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8
,03-17 08:37:20.588   921   921 E WifiTrafficPoller:  packet count Tx=171 Rx=272
03-17 08:37:20.588   921   921 E WifiTrafficPoller: notifying of data activity 1
03-17 08:37:20.588  1212  1212 D WIFI_ICON: WifiActivity: 1
03-17 08:37:20.598  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,03-17 08:37:21.508   921   921 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,03-17 08:37:21.588   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8
,03-17 08:37:21.598   921   921 E WifiTrafficPoller:  packet count Tx=171 Rx=272
03-17 08:37:21.598  1212  1212 D WIFI_ICON: WifiActivity: 0
03-17 08:37:21.598   921   921 E WifiTrafficPoller: notifying of data activity 0
03-17 08:37:21.598  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,03-17 08:37:22.318  3496  3571 I HtcModeClient: handler message = 4011,
03-17 08:37:22.318  3496  3571 E HtcModeClient: Check connection and retry 12 times.
,03-17 08:37:22.328   921  1148 E WifiStateMachine: handleMessage: E msg.what=131155,
03-17 08:37:22.328   921  1148 E WifiStateMachine: processMsg: ConnectedState
,03-17 08:37:22.338   921  1148 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-54 f=2457 sc=60 link=150 tx=1.2, 0.0, 0.0  rx=3.9 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:-2088638298] gl hn u24 rssi=-49 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
03-17 08:37:22.338   921  1148 E WifiStateMachine: processMsg: L2ConnectedState
03-17 08:37:22.338   921  1148 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-54 f=2457 sc=60 link=150 tx=1.2, 0.0, 0.0  rx=3.9 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-2088638296] gl hn u24 rssi=-49 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
03-17 08:37:22.338   921  1148 E WifiStateMachine:  get link layer stats 0
03-17 08:37:22.338   921  1148 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
03-17 08:37:22.338  1346  1346 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
,03-17 08:37:22.348  1346  1346 I wpa_supplicant: environment dirty rate=0 [0][0][0]
03-17 08:37:22.348   921  1148 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 150
,03-17 08:37:22.358  1212  1212 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3
03-17 08:37:22.348   921  1148 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-54 linkspeed=150
03-17 08:37:22.358  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
03-17 08:37:22.348   921  1148 E WifiConfigStore: updateConfiguration freq=2457 BSSID=f4:f2:6d:22:99:3e RSSI=-54 "NG700"WPA_PSK
03-17 08:37:22.348   921  1148 E WifiStateMachine: calculateWifiScore freq=2457 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.62 txretriesrate=0.00 rxrate=2.46 userTriggerdPenalty0
03-17 08:37:22.348   921  1148 E WifiStateMachine:  good link -> stuck count =0
03-17 08:37:22.348   921  1148 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 56
03-17 08:37:22.348   921  1148 E WifiStateMachine:  isHighRSSI       ---> score=61
03-17 08:37:22.358   921  1166 D WifiWatchdogStateMachine: RSSI current: 3 new: -54, 3
03-17 08:37:22.358   921  1148 E WifiStateMachine: handleMessage: X
,03-17 08:37:22.598   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8,
03-17 08:37:22.598  1212  1212 D WIFI_ICON: WifiActivity: 2
03-17 08:37:22.598   921   921 E WifiTrafficPoller:  packet count Tx=172 Rx=272
03-17 08:37:22.598  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
03-17 08:37:22.598   921   921 E WifiTrafficPoller: notifying of data activity 2
,03-17 08:37:23.128   921   951 D PMS     : acquireWL(d68709a): PARTIAL_WAKE_LOCK  Icing 0x1 4407 10024 WorkSource{10024 com.google.android.gms},
,03-17 08:37:23.168   921  1721 D PMS     : releaseWL(d68709a): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,03-17 08:37:23.198   921  1515 D PMS     : acquireWL(3d50f854): PARTIAL_WAKE_LOCK  Icing 0x1 4407 10024 WorkSource{10024 com.google.android.gms},
,03-17 08:37:23.208   921  1720 D PMS     : releaseWL(3d50f854): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
,03-17 08:37:23.228   921  2373 D PMS     : acquireWL(3c9c78f2): PARTIAL_WAKE_LOCK  Icing 0x1 4407 10024 WorkSource{10024 com.google.android.gms},
,03-17 08:37:23.248   921  1157 D PMS     : releaseWL(3c9c78f2): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,03-17 08:37:23.258   921   951 D PMS     : acquireWL(3def45c0): PARTIAL_WAKE_LOCK  Icing 0x1 4407 10024 WorkSource{10024 com.google.android.gms},
,03-17 08:37:23.268   921  2373 D PMS     : releaseWL(3def45c0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,03-17 08:37:23.278   921  1718 D PMS     : acquireWL(e75323e): PARTIAL_WAKE_LOCK  Icing 0x1 4407 10024 WorkSource{10024 com.google.android.gms}
,03-17 08:37:23.298   921  1514 D PMS     : releaseWL(e75323e): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,03-17 08:37:23.598   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8,
03-17 08:37:23.598  1212  1212 D WIFI_ICON: WifiActivity: 1
03-17 08:37:23.598   921   921 E WifiTrafficPoller:  packet count Tx=172 Rx=274
03-17 08:37:23.598  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
03-17 08:37:23.598   921   921 E WifiTrafficPoller: notifying of data activity 1
,03-17 08:37:24.598   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8,
03-17 08:37:24.598   921   921 E WifiTrafficPoller:  packet count Tx=172 Rx=274
03-17 08:37:24.598  1212  1212 D WIFI_ICON: WifiActivity: 0
03-17 08:37:24.598   921   921 E WifiTrafficPoller: notifying of data activity 0
03-17 08:37:24.598  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,03-17 08:37:24.798   921   921 E WifiDataStallTracker: DATA_MONITOR_POLL true Token 1,
,03-17 08:37:24.798   921  6482 D WifiDataStallTracker: updateDataStallInfo: mDataStallTxRxSum={txSum=153 rxSum=133} preTxRxSum={txSum=152 rxSum=132}
03-17 08:37:24.798   921  6482 D WifiDataStallTracker: updateDataStallInfo: IN/OUT
03-17 08:37:24.798   921  6482 D WifiDataStallTracker: onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,03-17 08:37:24.978   921   921 E WifiStateMachine: WiFiStateMachine SCAN ALARM
03-17 08:37:24.978   921  1137 D PMS     : acquireWL(3729789f): PARTIAL_WAKE_LOCK  *alarm* 0x1 921 1000 WorkSource{1000}
03-17 08:37:24.978   921  1148 E WifiStateMachine: handleMessage: E msg.what=131143
03-17 08:37:24.978   921   921 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
03-17 08:37:24.978   921   921 D WifiDisplayAdapter:     Client/Owner: Client
03-17 08:37:24.978   921   921 D WifiDisplayAdapter:     GroupId: 
03-17 08:37:24.978   921   921 D WifiDisplayAdapter:     Passphrase: 
03-17 08:37:24.978   921   921 D WifiDisplayAdapter:     SessionId: 0
03-17 08:37:24.978   921   921 D WifiDisplayAdapter:     IP Address: }
03-17 08:37:24.978   921  1148 E WifiStateMachine: processMsg: ConnectedState
03-17 08:37:24.978   921  1137 V AlarmManager: sending alarm PendingIntent{3a4bcbda: PendingIntentRecord{2efe680b android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1458200244984, Int=20000
03-17 08:37:24.978   921  1148 E WifiStateMachine:  ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):1 dur:2270 rssi=-54 f=2457 sc=60 link=150 tx=0.6, 0.0, 0.0  rx=2.5 fiv=60000 [on:0 tx:0 rx:0 period:2624] from screen [on:0 period:-2088635653]
03-17 08:37:24.978   921   921 D PMS     : releaseWL(3729789f): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
03-17 08:37:24.978   921  1148 E WifiStateMachine: processMsg: L2ConnectedState
03-17 08:37:24.978   921  1148 E WifiStateMachine:  L2ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):2 dur:2270 rssi=-54 f=2457 sc=60 link=150 tx=0.6, 0.0, 0.0  rx=2.5 fiv=60000 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-2088635653]
,03-17 08:37:24.978   921  1148 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.62 rxSuccessRate=2.46 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-54
03-17 08:37:24.978   921  1148 E WifiStateMachine: WifiStateMachine CMD_START_SCAN with age=19999 interval=60000 maxinterval=300000
03-17 08:37:24.978   921  1148 E WifiStateMachine: WifiStateMachine CMD_START_SCAN full=false
03-17 08:37:24.978   921  1148 E WifiConfigStore: makeChannelList age=3600000 for "NG700"WPA_PSK max=6 bssids=1
03-17 08:37:24.978   921  1148 E WifiConfigStore: has f4:f2:6d:22:99:3e freq=2457 age=2629 ?=true
03-17 08:37:24.978   921  1148 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2457
03-17 08:37:24.978   921  1148 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY freq=2457"
03-17 08:37:24.978  1346  1346 D wpa_supplicant: wlan0: Control interface command 'SCAN TYPE=ONLY freq=2457'
03-17 08:37:24.978  1346  1346 D wpa_supplicant: wlan0: Setting scan request: 0.000000 sec
03-17 08:37:24.978  1346  1346 I wpa_supplicant: wpa_supplicant_scan enter
03-17 08:37:24.978  1346  1346 D wpa_supplicant: wlan0: Starting AP scan for wildcard SSID
03-17 08:37:24.978  1346  1346 D wpa_supplicant: WPS: Building WPS IE for Probe Request
03-17 08:37:24.978  1346  1346 D wpa_supplicant: WPS:  * Version (hardcoded 0x10)
03-17 08:37:24.978  1346  1346 D wpa_supplicant: WPS:  * Request Type
03-17 08:37:24.978  1346  1346 D wpa_supplicant: WPS:  * Config Methods (4288)
03-17 08:37:24.978  1346  1346 D wpa_supplicant: WPS:  * UUID-E
03-17 08:37:24.978  1346  1346 D wpa_supplicant: WPS:  * Primary Device Type
,03-17 08:37:24.978  1346  1346 D wpa_supplicant: WPS:  * RF Bands (3)
03-17 08:37:24.978  1346  1346 D wpa_supplicant: WPS:  * Association State
03-17 08:37:24.978  1346  1346 D wpa_supplicant: WPS:  * Configuration Error (0)
03-17 08:37:24.978  1346  1346 D wpa_supplicant: WPS:  * Device Password ID (0)
03-17 08:37:24.978  1346  1346 D wpa_supplicant: WPS:  * Manufacturer
03-17 08:37:24.978  1346  1346 D wpa_supplicant: WPS:  * Model Name
03-17 08:37:24.978  1346  1346 D wpa_supplicant: WPS:  * Model Number
03-17 08:37:24.978  1346  1346 D wpa_supplicant: WPS:  * Device Name
03-17 08:37:24.978  1346  1346 D wpa_supplicant: WPS:  * Version2 (0x20)
03-17 08:37:24.978  1346  1346 D wpa_supplicant: P2P: * P2P IE header
03-17 08:37:24.978  1346  1346 D wpa_supplicant: P2P: * Capability dev=25 group=00
03-17 08:37:24.978  1346  1346 D wpa_supplicant: P2P: * Listen Channel: Regulatory Class 81 Channel 6
03-17 08:37:24.978  1346  1346 D wpa_supplicant: wlan0: Limit manual scan to specified channels
03-17 08:37:24.978  1346  1346 D wpa_supplicant: wlan0: Add radio work 'scan'@0x55687bd680
03-17 08:37:24.978  1346  1346 D wpa_supplicant: wlan0: First radio work item in the queue - schedule start immediately
03-17 08:37:24.978  1346  1346 D wpa_supplicant: wlan0: Starting radio work 'scan'@0x55687bd680 after 0.000052 second wait
03-17 08:37:24.978  1346  1346 D wpa_supplicant: wlan0: nl80211: scan request
03-17 08:37:24.978   921  1148 E WifiStateMachine: [1,458,200,244,989 ms] noteScanstart no scan source
03-17 08:37:24.978  1346  1346 D wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
03-17 08:37:24.978  1346  1346 D wpa_supplicant: nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,03-17 08:37:24.978  1346  1346 D wpa_supplicant: wlan0: nl80211: Scan trigger
03-17 08:37:24.978  1346  1346 D wpa_supplicant: wlan0: Event SCAN_STARTED (49) received
03-17 08:37:24.978  1346  1346 D wpa_supplicant: wlan0: Own scan request started a scan in 0.000113 seconds
03-17 08:37:24.978  1346  1346 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
03-17 08:37:24.978   921  1148 E WifiStateMachine: handleMessage: X
03-17 08:37:24.978   921  1644 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
03-17 08:37:24.978   921  1644 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
03-17 08:37:24.978   921  1644 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
03-17 08:37:24.978   921  1644 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,03-17 08:37:25.058  1346  1346 D wpa_supplicant: nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
03-17 08:37:25.058  1346  1346 D wpa_supplicant: wlan0: nl80211: New scan results available
03-17 08:37:25.058  1346  1346 D wpa_supplicant: nl80211: Scan included frequencies: 2457
03-17 08:37:25.058  1346  1346 D wpa_supplicant: wlan0: Event SCAN_RESULTS (3) received
03-17 08:37:25.058  1346  1346 I wpa_supplicant: Got an original EVENT_SCAN_RESULTS
03-17 08:37:25.058  1346  1346 D wpa_supplicant: wlan0: Scan completed in 0.078417 seconds
03-17 08:37:25.058  1346  1346 D wpa_supplicant: nl80211: Associated on 2457 MHz
03-17 08:37:25.058  1346  1346 D wpa_supplicant: nl80211: Associated with f4:f2:6d:22:99:3e
03-17 08:37:25.058  1346  1346 D wpa_supplicant: nl80211: Received scan results (9 BSSes)
03-17 08:37:25.058  1346  1346 D wpa_supplicant: nl80211: Scan results indicate BSS status with f4:f2:6d:22:99:3e as associated
03-17 08:37:25.058  1346  1346 I wpa_supplicant: [NULL] f0:f2:6d:22:99:3e freq=2457 level=-49
03-17 08:37:25.058  1346  1346 I wpa_supplicant: [NULL] f4:f2:6d:22:99:3e freq=2457 level=-54
03-17 08:37:25.058  1346  1346 I wpa_supplicant: [NULL] 00:1f:27:54:70:c1 freq=2412 level=-55
03-17 08:37:25.058  1346  1346 I wpa_supplicant: [NULL] 00:1f:27:54:70:c0 freq=2412 level=-55
03-17 08:37:25.058  1346  1346 I wpa_supplicant: [NULL] 00:1f:27:54:dd:ef freq=5240 level=-74
03-17 08:37:25.058  1346  1346 I wpa_supplicant: [NULL] 00:1f:27:54:dd:e0 freq=2437 level=-72
03-17 08:37:25.058  1346  1346 I wpa_supplicant: [NULL] 00:1f:27:54:dd:e3 freq=2437 level=-73
03-17 08:37:25.058  1346  1346 I wpa_supplicant: [NULL] 00:1f:27:54:e0:43 freq=2462 level=-77
03-17 08:37:25.058  1346  1346 I wpa_supplicant: [NULL] 00:22:0d:46:1c:a3 freq=2462 level=-81
03-17 08:37:25.058  1346  1346 D wpa_supplicant: wlan0: BSS: Start scan result update 6
03-17 08:37:25.058  1346  1346 D wpa_supplicant: BSS: last_scan_res_used=9/32
03-17 08:37:25.058  1346  1346 D wpa_supplicant: wlan0: Scan-only results received
03-17 08:37:25.058  1346  1346 D wpa_supplicant: wlan0: Radio work 'scan'@0x55687bd680 done in 0.079696 seconds
03-17 08:37:25.058   921  1644 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
03-17 08:37:25.058   921  1644 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
03-17 08:37:25.058   921  1148 E WifiStateMachine: handleMessage: E msg.what=147461
03-17 08:37:25.058   921  1148 E WifiStateMachine: processMsg: ConnectedState
,03-17 08:37:25.058   921  1148 E WifiStateMachine:  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=9 known=1 got=9 bcn=0
03-17 08:37:25.058   921  1148 E WifiStateMachine: processMsg: L2ConnectedState
03-17 08:37:25.058   921  1148 E WifiStateMachine:  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=9 known=1 got=9 bcn=0
03-17 08:37:25.058   921  1148 E WifiStateMachine: processMsg: ConnectModeState
03-17 08:37:25.058   921  1148 E WifiStateMachine:  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=9 known=1 got=9 bcn=0
03-17 08:37:25.058   921  1148 E WifiStateMachine: processMsg: DriverStartedState
03-17 08:37:25.068   921  1148 E WifiStateMachine:  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=9 known=1 got=9 bcn=0
03-17 08:37:25.068   921  1148 E WifiStateMachine: processMsg: SupplicantStartedState
03-17 08:37:25.068   921  1148 E WifiStateMachine:  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=9 known=1 got=9 bcn=0
03-17 08:37:25.068   921  1148 D WifiStateMachine: [MLHD] enter handleMediaLinkEvent SupplicantStartedState
03-17 08:37:25.068   921  1148 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
03-17 08:37:25.068  1346  1346 D wpa_supplicant: wlan0: Control interface command 'LIST_DONGLES'
,03-17 08:37:25.068   921  1148 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
03-17 08:37:25.068   921  1148 E WifiStateMachine: [1,458,200,245,074 ms] noteScanEnd no scan source
03-17 08:37:25.068   921  1148 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
03-17 08:37:25.068  1346  1346 D wpa_supplicant: wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
,03-17 08:37:25.068   921  1148 E WifiStateMachine: wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@2081c785 sup_state=COMPLETED debouncing=false
03-17 08:37:25.068   921  1148 E WifiAutoJoinController : NG700 f4:f2:6d:22:99:3e rssi=-54 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
03-17 08:37:25.068   921  1148 E WifiConfigStore: updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
03-17 08:37:25.068   921  1148 E WifiConfigStore: updateSavedNetworkHistory: HTC improve mode
03-17 08:37:25.068   921  1148 E WifiConfigStore:         got known scan result f4:f2:6d:22:99:3e key : "NG700"WPA_PSK num: 1 rssi=-54 freq=2457
03-17 08:37:25.068   921  1148 E WifiAutoJoinController : ktwtestwifi 00:1f:27:54:70:c0 rssi=-55 cap [WPA2-EAP-CCMP+TKIP][ESS] is not scored,
03-17 08:37:25.068   921  1148 E WifiAutoJoinController : TEST_KTW01 00:1f:27:54:70:c1 rssi=-55 cap [WPA2-EAP-TKIP][ESS] is not scored
03-17 08:37:25.068   921  1148 E WifiAutoJoinController : RA-WINGS 00:1f:27:54:dd:e3 rssi=-73 cap [ESS] is not scored
03-17 08:37:25.068   921  1148 E WifiAutoJoinController : NG700_GUEST f0:f2:6d:22:99:3e rssi=-49 cap [WPA2-PSK-CCMP][ESS] is not scored
03-17 08:37:25.068   921  1148 E WifiAutoJoinController :  00:1f:27:54:dd:ef rssi=-74 cap [WPA-EAP-TKIP][WPA2-EAP-CCMP][ESS] is not scored
03-17 08:37:25.068   921  1148 E WifiAutoJoinController :  00:1f:27:54:dd:e0 rssi=-72 cap [WPA-EAP-TKIP][WPA2-EAP-CCMP][ESS] is not scored
03-17 08:37:25.068   921  1148 E WifiAutoJoinController : RA-WINGS 00:1f:27:54:e0:43 rssi=-77 cap [ESS] is not scored
03-17 08:37:25.068   921  1148 E WifiAutoJoinController : RA-WINGS 00:22:0d:46:1c:a3 rssi=-81 cap [ESS] is not scored
03-17 08:37:25.068   921  1148 E WifiAutoJoinController : ageScanResultsOut delay 40000 size 9 now 1458200245078
03-17 08:37:25.068   921  1148 E WifiAutoJoinController : newSupplicantResults size=9 known=1 true
03-17 08:37:25.068   921  1148 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
03-17 08:37:25.068  1346  1346 D wpa_supplicant: wlan0: Control interface command 'STATUS-NO_EVENTS'
03-17 08:37:25.068   921  1148 E WifiAutoJoinController : attemptAutoJoin() status=bssid=f4:f2:6d:22:99:3e
03-17 08:37:25.068   921  1148 E WifiAutoJoinController : ssid=NG700
03-17 08:37:25.068   921  1148 E WifiAutoJoinController : id=0
03-17 08:37:25.068   921  1148 E WifiAutoJoinController : mode=station
03-17 08:37:25.068   921  1148 E WifiAutoJoinController : pairwise_cipher=CCMP
03-17 08:37:25.068   921  1148 E WifiAutoJoinController : group_cipher=CCMP
03-17 08:37:25.068   921  1148 E WifiAutoJoinController : key_mgmt=WPA2-PSK
03-17 08:37:25.068   921  1148 E WifiAutoJoinController : wpa_state=COMPLETED
03-17 08:37:25.068   921  1148 E WifiAutoJoinController : ip_address=192.168.1.102
03-17 08:37:25.068   921  1148 E WifiAutoJoinController : p2p_device_address=92:e7:c4:e6:4c:f8
03-17 08:37:25.068   921  1148 E WifiAutoJoinController : address=XX:XX:XX:XX:XX:XX
03-17 08:37:25.068   921  1148 E WifiAutoJoinController : uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
03-17 08:37:25.068   921  1148 E WifiAutoJoinController : attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
03-17 08:37:25.068   921  1148 E WifiAutoJoinController : attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-54,-127) num=(1,0)
03-17 08:37:25.068   921  1148 E WifiAutoJoinController : attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
03-17 08:37:25.068   921  1148 E WifiAutoJoinController : attemptRoam: "NG700"WPA_PSK Found f4:f2:6d:22:99:3e rssi=-54 freq=2457 Current: f4:f2:6d:22:99:3e
,03-17 08:37:25.068   921  1148 D HtcWifiControlRoamOffload: : roamCandidate: nullcurrentBSSID: f4:f2:6d:22:99:3e
03-17 08:37:25.068   921  1148 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false
03-17 08:37:25.068   921  1148 E WifiAutoJoinController : Done attemptAutoJoin status=0
03-17 08:37:25.068   921  1148 E WifiConfigStore:  writeKnownNetworkHistory() num networks:1 needWrite=false
03-17 08:37:25.068   921  1148 E WifiStateMachine: handleMessage: X
,03-17 08:37:25.348   921  1148 E WifiStateMachine: handleMessage: E msg.what=131155
,03-17 08:37:25.348   921  1148 E WifiStateMachine: processMsg: ConnectedState
03-17 08:37:25.358   921  1148 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-54 f=2457 sc=60 link=150 tx=0.6, 0.0, 0.0  rx=2.5 bcn=0 [on:0 tx:0 rx:0 period:373] from screen [on:0 period:-2088635278] gl hn u24 rssi=-49 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
03-17 08:37:25.358   921  1148 E WifiStateMachine: processMsg: L2ConnectedState
,03-17 08:37:25.358   921  1148 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-54 f=2457 sc=60 link=150 tx=0.6, 0.0, 0.0  rx=2.5 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-2088635276] gl hn u24 rssi=-49 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
03-17 08:37:25.358   921  1148 E WifiStateMachine:  get link layer stats 0
03-17 08:37:25.358   921  1148 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
03-17 08:37:25.358  1346  1346 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
,03-17 08:37:25.358  1346  1346 I wpa_supplicant: environment dirty rate=0 [1][0][0],
03-17 08:37:25.368   921  1148 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 150
03-17 08:37:25.368   921  1148 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-54 linkspeed=150
03-17 08:37:25.368   921  1148 E WifiConfigStore: updateConfiguration freq=2457 BSSID=f4:f2:6d:22:99:3e RSSI=-54 "NG700"WPA_PSK
,03-17 08:37:25.368   921  1148 E WifiStateMachine: calculateWifiScore freq=2457 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.81 txretriesrate=0.00 rxrate=2.23 userTriggerdPenalty0
03-17 08:37:25.368   921  1148 E WifiStateMachine:  good link -> stuck count =0
03-17 08:37:25.368  1212  1212 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3
03-17 08:37:25.368   921  1148 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 56
03-17 08:37:25.368  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
03-17 08:37:25.368   921  1148 E WifiStateMachine:  isHighRSSI       ---> score=61
,03-17 08:37:25.368   921  1148 E WifiStateMachine: handleMessage: X
03-17 08:37:25.368   921  1166 D WifiWatchdogStateMachine: RSSI current: 3 new: -54, 3
,03-17 08:37:25.598   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8,
03-17 08:37:25.598   921   921 E WifiTrafficPoller:  packet count Tx=172 Rx=274
,03-17 08:37:26.598   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8,
03-17 08:37:26.608   921   921 E WifiTrafficPoller:  packet count Tx=172 Rx=275
03-17 08:37:26.608   921   921 E WifiTrafficPoller: notifying of data activity 1
03-17 08:37:26.608  1212  1212 D WIFI_ICON: WifiActivity: 1
,03-17 08:37:26.608  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,03-17 08:37:27.338  3496  3571 I HtcModeClient: handler message = 4011
,03-17 08:37:27.348  3496  3571 E HtcModeClient: Check connection and retry 12 times. Stop service and kill this process.,
,03-17 08:37:27.358  3496  3496 D HtcModeClient: Don't start project servcice,
03-17 08:37:27.358  3496  3496 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
03-17 08:37:27.358  3496  3496 D HtcModeClient: connectState: CONNECTION_READY = false
03-17 08:37:27.358  3496  3496 D SilentMusic: call stop
03-17 08:37:27.358  3496  3496 D HtcModeClient: close connection
03-17 08:37:27.358  3496  3496 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
03-17 08:37:27.358  3496  3578 W CANMesgAgentLocalSocket: read the terminate packet, so break,
03-17 08:37:27.358   921  4355 I ActivityManager: Killing 3496:com.htc.autobot/u0a47 (adj 15): empty #17
03-17 08:37:27.358   921  4355 D Process : killProcessQuiet, pid=3496
,03-17 08:37:27.358   921  4355 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-17 08:37:27.438   921   951 I ActivityManager: Recipient 3496
,03-17 08:37:27.608   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8
,03-17 08:37:27.608   921   921 E WifiTrafficPoller:  packet count Tx=172 Rx=275
03-17 08:37:27.608  1212  1212 D WIFI_ICON: WifiActivity: 0
03-17 08:37:27.608   921   921 E WifiTrafficPoller: notifying of data activity 0
03-17 08:37:27.608  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,03-17 08:37:28.368   921  1148 E WifiStateMachine: handleMessage: E msg.what=131155
03-17 08:37:28.368   921  1148 E WifiStateMachine: processMsg: ConnectedState
,03-17 08:37:28.368   921  1148 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-54 f=2457 sc=60 link=150 tx=0.8, 0.0, 0.0  rx=2.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2088632264] gl hn u24 rssi=-49 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
03-17 08:37:28.368   921  1148 E WifiStateMachine: processMsg: L2ConnectedState
,03-17 08:37:28.368   921  1148 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-54 f=2457 sc=60 link=150 tx=0.8, 0.0, 0.0  rx=2.2 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-2088632264] gl hn u24 rssi=-49 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
03-17 08:37:28.368   921  1148 E WifiStateMachine:  get link layer stats 0
03-17 08:37:28.368   921  1148 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
03-17 08:37:28.368  1346  1346 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
,03-17 08:37:28.378  1346  1346 I wpa_supplicant: environment dirty rate=0 [1][0][0]
03-17 08:37:28.378   921  1148 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 150
03-17 08:37:28.378   921  1148 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-54 linkspeed=150
03-17 08:37:28.378   921  1148 E WifiConfigStore: updateConfiguration freq=2457 BSSID=f4:f2:6d:22:99:3e RSSI=-54 "NG700"WPA_PSK
,03-17 08:37:28.378   921  1148 E WifiStateMachine: calculateWifiScore freq=2457 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.90 txretriesrate=0.00 rxrate=2.11 userTriggerdPenalty0
03-17 08:37:28.378   921  1148 E WifiStateMachine:  good link -> stuck count =0
03-17 08:37:28.388   921  1148 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 56
03-17 08:37:28.388   921  1148 E WifiStateMachine:  isHighRSSI       ---> score=61
03-17 08:37:28.388   921  1166 D WifiWatchdogStateMachine: RSSI current: 3 new: -54, 3
03-17 08:37:28.388   921  1148 E WifiStateMachine: handleMessage: X
03-17 08:37:28.388  1212  1212 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3
03-17 08:37:28.388  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,03-17 08:37:28.608   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8
,03-17 08:37:28.608   921   921 E WifiTrafficPoller:  packet count Tx=173 Rx=276
03-17 08:37:28.608  1212  1212 D WIFI_ICON: WifiActivity: 3
03-17 08:37:28.608   921   921 E WifiTrafficPoller: notifying of data activity 3
03-17 08:37:28.608  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,03-17 08:37:29.608   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8
03-17 08:37:29.608  1212  1212 D WIFI_ICON: WifiActivity: 1
03-17 08:37:29.608   921   921 E WifiTrafficPoller:  packet count Tx=173 Rx=277
03-17 08:37:29.608  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
03-17 08:37:29.608   921   921 E WifiTrafficPoller: notifying of data activity 1
,03-17 08:37:29.798   921   921 E WifiDataStallTracker: DATA_MONITOR_POLL true Token 1,
,03-17 08:37:29.798   921  6483 D WifiDataStallTracker: updateDataStallInfo: mDataStallTxRxSum={txSum=154 rxSum=134} preTxRxSum={txSum=153 rxSum=133}
03-17 08:37:29.798   921  6483 D WifiDataStallTracker: updateDataStallInfo: IN/OUT,
03-17 08:37:29.798   921  6483 D WifiDataStallTracker: onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,03-17 08:37:30.598   921  1137 I ActivityManager: Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=6484 uid=10076 gids={50076, 9997} abi=arm64-v8a,
03-17 08:37:30.598   921  1137 D PMS     : acquireWL(962fdec): PARTIAL_WAKE_LOCK  *alarm* 0x1 921 1000 WorkSource{10076}
03-17 08:37:30.598   921  1137 V AlarmManager: sending alarm PendingIntent{390c35b5: PendingIntentRecord{18e344a com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1458200250586, Int=60000
,03-17 08:37:30.598   921   921 D PMS     : releaseWL(962fdec): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076}
,03-17 08:37:30.608   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8
,03-17 08:37:30.608   921   921 E WifiTrafficPoller:  packet count Tx=173 Rx=277
03-17 08:37:30.608   921   921 E WifiTrafficPoller: notifying of data activity 0
03-17 08:37:30.608  1212  1212 D WIFI_ICON: WifiActivity: 0
03-17 08:37:30.608  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,03-17 08:37:30.658  6484  6505 D SMSBackup: SMSBackupAgentService started
,03-17 08:37:30.658  6484  6505 D SMSBackup: Checking restore status
,03-17 08:37:30.658  6484  6505 D SMSBackup: Restore complete
03-17 08:37:30.658  6484  6505 D SMSBackup: cancelCheckAlarm
,03-17 08:37:30.658  6484  6505 D SMSBackup: SMSBackupAgentService completed: completed in 0.0 seconds
,03-17 08:37:30.668   921  1718 D Process : killProcessQuiet, pid=5926
03-17 08:37:30.668   921  1718 I ActivityManager: Killing 5926:com.google.android.gms:car/u0a24 (adj 15): empty #17
03-17 08:37:30.668   921  1718 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-17 08:37:30.718   921  1719 I ActivityManager: Recipient 5926,
,03-17 08:37:31.388   921  1148 E WifiStateMachine: handleMessage: E msg.what=131155,
03-17 08:37:31.388   921  1148 E WifiStateMachine: processMsg: ConnectedState
,03-17 08:37:31.388   921  1148 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-54 f=2457 sc=60 link=150 tx=0.9, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2088629244] gl hn u24 rssi=-49 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
03-17 08:37:31.388   921  1148 E WifiStateMachine: processMsg: L2ConnectedState
03-17 08:37:31.388   921  1148 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-54 f=2457 sc=60 link=150 tx=0.9, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-2088629243] gl hn u24 rssi=-49 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
03-17 08:37:31.388   921  1148 E WifiStateMachine:  get link layer stats 0
03-17 08:37:31.388   921  1148 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
03-17 08:37:31.388  1346  1346 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
,03-17 08:37:31.408  1346  1346 I wpa_supplicant: environment dirty rate=0 [0][0][0]
03-17 08:37:31.408  1212  1212 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3
03-17 08:37:31.408   921  1148 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 150
03-17 08:37:31.408  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
03-17 08:37:31.408   921  1148 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-56 linkspeed=150
03-17 08:37:31.408   921  1148 E WifiConfigStore: updateConfiguration freq=2457 BSSID=f4:f2:6d:22:99:3e RSSI=-55 "NG700"WPA_PSK
03-17 08:37:31.408   921  1148 E WifiStateMachine: calculateWifiScore freq=2457 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.45 txretriesrate=0.00 rxrate=4.56 userTriggerdPenalty0
03-17 08:37:31.408   921  1148 E WifiStateMachine:  good link -> stuck count =0
03-17 08:37:31.408   921  1148 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 56
,03-17 08:37:31.408   921  1148 E WifiStateMachine:  isHighRSSI       ---> score=61
03-17 08:37:31.408   921  1148 E WifiStateMachine: handleMessage: X
03-17 08:37:31.408   921  1166 D WifiWatchdogStateMachine: RSSI current: 3 new: -56, 3
,03-17 08:37:31.608   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8
,03-17 08:37:31.608   921   921 E WifiTrafficPoller:  packet count Tx=173 Rx=283
03-17 08:37:31.608  1212  1212 D WIFI_ICON: WifiActivity: 1
,03-17 08:37:31.608   921   921 E WifiTrafficPoller: notifying of data activity 1
03-17 08:37:31.618  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,03-17 08:37:32.618   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8
03-17 08:37:32.618   921   921 E WifiTrafficPoller:  packet count Tx=173 Rx=289
,03-17 08:37:33.618   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8,
03-17 08:37:33.618   921   921 E WifiTrafficPoller:  packet count Tx=174 Rx=290
03-17 08:37:33.618  1212  1212 D WIFI_ICON: WifiActivity: 3
,03-17 08:37:33.618   921   921 E WifiTrafficPoller: notifying of data activity 3
03-17 08:37:33.618  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,03-17 08:37:34.408   921  1148 E WifiStateMachine: handleMessage: E msg.what=131155,
03-17 08:37:34.408   921  1148 E WifiStateMachine: processMsg: ConnectedState
03-17 08:37:34.408   921  1148 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2457 sc=60 link=150 tx=0.5, 0.0, 0.0  rx=4.6 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2088626223] gl hn u24 rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
03-17 08:37:34.408   921  1148 E WifiStateMachine: processMsg: L2ConnectedState,
03-17 08:37:34.408   921  1148 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2457 sc=60 link=150 tx=0.5, 0.0, 0.0  rx=4.6 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-2088626222] gl hn u24 rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
03-17 08:37:34.408   921  1148 E WifiStateMachine:  get link layer stats 0
03-17 08:37:34.408   921  1148 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
03-17 08:37:34.408  1346  1346 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
,03-17 08:37:34.418  1346  1346 I wpa_supplicant: environment dirty rate=0 [2][0][0]
,03-17 08:37:34.428   921  1148 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 150
03-17 08:37:34.428   921  1148 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-55 linkspeed=150
03-17 08:37:34.428   921  1148 E WifiConfigStore: updateConfiguration freq=2457 BSSID=f4:f2:6d:22:99:3e RSSI=-55 "NG700"WPA_PSK
,03-17 08:37:34.428   921  1148 E WifiStateMachine: calculateWifiScore freq=2457 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.73 txretriesrate=0.00 rxrate=5.78 userTriggerdPenalty0,
03-17 08:37:34.428  1212  1212 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3
03-17 08:37:34.428   921  1148 E WifiStateMachine:  good link -> stuck count =0
03-17 08:37:34.428  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
03-17 08:37:34.428   921  1148 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 56,
03-17 08:37:34.428   921  1148 E WifiStateMachine:  isHighRSSI       ---> score=61
03-17 08:37:34.428   921  1166 D WifiWatchdogStateMachine: RSSI current: 3 new: -55, 3
03-17 08:37:34.428   921  1148 E WifiStateMachine: handleMessage: X
,03-17 08:37:34.618   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8,
03-17 08:37:34.618  1212  1212 D WIFI_ICON: WifiActivity: 0
03-17 08:37:34.618   921   921 E WifiTrafficPoller:  packet count Tx=174 Rx=290,
03-17 08:37:34.618  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
03-17 08:37:34.618   921   921 E WifiTrafficPoller: notifying of data activity 0
,03-17 08:37:34.798   921   921 E WifiDataStallTracker: DATA_MONITOR_POLL true Token 1,
03-17 08:37:34.798   921  6506 D WifiDataStallTracker: updateDataStallInfo: mDataStallTxRxSum={txSum=155 rxSum=135} preTxRxSum={txSum=154 rxSum=134}
03-17 08:37:34.798   921  6506 D WifiDataStallTracker: updateDataStallInfo: IN/OUT
,03-17 08:37:34.798   921  6506 D WifiDataStallTracker: onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,03-17 08:37:35.618   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8
03-17 08:37:35.618  1212  1212 D WIFI_ICON: WifiActivity: 1
03-17 08:37:35.618   921   921 E WifiTrafficPoller:  packet count Tx=174 Rx=291
03-17 08:37:35.618  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
03-17 08:37:35.618   921   921 E WifiTrafficPoller: notifying of data activity 1
,03-17 08:37:35.818   921   921 I SensorManager: unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@33cfa620,
,03-17 08:37:35.818   921  1053 I PMS     : Going to sleep due to screen timeout (uid 1000)...
03-17 08:37:35.818   921   921 W SensorService: Following SensorService logs are not warning, just make sure they are printed
03-17 08:37:35.818   921   921 W SensorService: disable: get sensor name = Accelerometer Sensor
03-17 08:37:35.818   921   921 W SensorService: pid=921, uid=1000
03-17 08:37:35.818   921   921 W SensorService: Active sensors: size = 4
03-17 08:37:35.818   921   921 W SensorService: Accelerometer Sensor (handle=0x00000000, connections=1)
03-17 08:37:35.818   921   921 W SensorService: CM32181 Light sensor (handle=0x00000003, connections=1)
03-17 08:37:35.818   921   921 W SensorService: CM36686 Proximity sensor (handle=0x00000004, connections=1)
03-17 08:37:35.818   921   921 W SensorService: Significant Motion (handle=0x0000000d, connections=1)
03-17 08:37:35.818   921   921 W SensorService: SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@33cfa620, eanble = 0, strlen(mName) = 91
,03-17 08:37:35.818   921   921 W SensorService: Active Listeners: mActiveListeners.size() = 2
03-17 08:37:35.828   921   921 W SensorService: Listener[0] = com.android.server.display.AutomaticBrightnessController$1@1669982a
03-17 08:37:35.828   921   921 W SensorService: Listener[1] = com.htc.smartdim.sensor_eye@2aaddd92
03-17 08:37:35.828   921   921 W SensorService: void android::SensorService::listenerSensor(const char*, int32_t)--:
03-17 08:37:35.828   921   921 W PMN     : goingToSleep
,03-17 08:37:35.838  1212  1247 W HtcLockScreen: KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,03-17 08:37:35.868   921  1055 W PMS     : mWirelessDisplayManager is null
,03-17 08:37:35.868   921   921 D PMS     : acquireWL(2d780cd8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 921 1000 null
03-17 08:37:35.868   921  1055 W PMS     : mWirelessDisplayManager is still null
03-17 08:37:35.868   921   921 W PMN     : goingToSleep done
,03-17 08:37:35.868   921  1053 I PMS     : Sleeping (uid 1000)...
03-17 08:37:35.868   921  1053 D XAN-DPS : prepareColorFade 1
,03-17 08:37:35.888   921  1555 W HtcSystemUPManager: HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
03-17 08:37:35.888   921   921 D AlarmManager: ACTION_SCREEN_ON
,03-17 08:37:35.898   921  1515 D PMS     : releaseWL(2d780cd8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
03-17 08:37:35.898   921   921 I AlarmManager: [AlarmQueuing] recover blocked alarms
03-17 08:37:35.898   921   921 I AlarmManager: [AlarmQueuing] done recovering
03-17 08:37:35.898   921   921 I AlarmManager: [AlarmQueuing] recover EPS screen off blocked alarms
03-17 08:37:35.898   921   921 I AlarmManager: [AlarmQueuing] done EPS screen off alarm recovering
,03-17 08:37:35.898   921  1053 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
03-17 08:37:35.898   921  1053 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.01
03-17 08:37:35.898   921  1053 I Adreno-EGL: Build Date: 03/09/15 Mon
03-17 08:37:35.898   921  1053 I Adreno-EGL: Local Branch: 
03-17 08:37:35.898   921  1053 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
03-17 08:37:35.898   921  1053 I Adreno-EGL: Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
03-17 08:37:35.898   921  1053 I Adreno-EGL:                  d74aa161a12b9c6fc6332151
,03-17 08:37:35.928   921   921 E WifiTrafficPoller: ENABLE_TRAFFIC_STATS_POLL true Token 11,
03-17 08:37:35.928   921   921 E WifiTrafficPoller:  packet count Tx=174 Rx=291
03-17 08:37:35.928   921   921 E WifiTrafficPoller: notifying of data activity 0,
03-17 08:37:35.928   921   921 E WifiDataStallTracker: ENABLE_DATA_MONITOR_POLL true Token 1
03-17 08:37:35.928   921  1148 E WifiStateMachine: handleMessage: E msg.what=131167
03-17 08:37:35.928   921  1148 E WifiStateMachine: processMsg: ConnectedState
03-17 08:37:35.938   921  1148 E WifiStateMachine:  ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
03-17 08:37:35.938   921  1148 E WifiStateMachine: processMsg: L2ConnectedState
03-17 08:37:35.938   921  6509 D WifiDataStallTracker: updateDataStallInfo: mDataStallTxRxSum={txSum=155 rxSum=135} preTxRxSum={txSum=155 rxSum=135}
03-17 08:37:35.938  1212  1212 D WIFI_ICON: WifiActivity: 0
03-17 08:37:35.938   921  6509 D WifiDataStallTracker: updateDataStallInfo: NONE
03-17 08:37:35.938   921  6509 D WifiDataStallTracker: onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,03-17 08:37:35.938   921  1148 E WifiStateMachine:  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
03-17 08:37:35.938  1212  1212 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
03-17 08:37:35.938   921  1148 E WifiStateMachine: processMsg: ConnectModeState
,03-17 08:37:35.938   921  1148 E WifiStateMachine:  ConnectModeState !CMD_SCREEN_STATE_CHANGED 1 0
03-17 08:37:35.938   424   424 V SRS_Proc: ParamSet string: screen_state=on
03-17 08:37:35.938   921  1148 E WifiStateMachine: processMsg: DriverStartedState
03-17 08:37:35.938   424   424 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
03-17 08:37:35.938   921  1148 E WifiStateMachine:  DriverStartedState !CMD_SCREEN_STATE_CHANGED 1 0
,03-17 08:37:35.938   921  1148 E WifiStateMachine: processMsg: SupplicantStartedState
03-17 08:37:35.938   921  1148 E WifiStateMachine:  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 1 0
03-17 08:37:35.938   921  1148 E WifiStateMachine: processMsg: DefaultState
,03-17 08:37:35.938   921  1148 E WifiStateMachine:  DefaultState !CMD_SCREEN_STATE_CHANGED 1 0
03-17 08:37:35.938   921  1148 E WifiStateMachine:  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
03-17 08:37:35.938   921  1148 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
03-17 08:37:35.938  1346  1346 D wpa_supplicant: wlan0: Control interface command 'SET_SCREEN_ON 1'
03-17 08:37:35.938   921  1149 D WifiController: handleMessage: E msg.what=155650
03-17 08:37:35.938  1346  1346 I wpa_supplicant: SET_SCREEN_ON:On
03-17 08:37:35.938  1346  1346 I wpa_supplicant: htc_wext_set_keepalive +
03-17 08:37:35.938  1346  1346 I wpa_supplicant: htc_wext_set_keepalive: enable=0, type=2, interval=15
03-17 08:37:35.938  1346  1346 D wpa_supplicant: getPrivFuncNum +	
03-17 08:37:35.938  1346  1346 I wpa_supplicant: getPrivFuncNum -, cmd = 0x8bf6
03-17 08:37:35.938  1346  1346 I wpa_supplicant: htc_wext_set_keepalive fnum = 0x8bf6
03-17 08:37:35.938  1346  1346 I wpa_supplicant: htc_wext_set_keepalive - ret = 0
03-17 08:37:35.938  1346  1346 I wpa_supplicant: htc_wext_set_TX_TRACKING (1)+
03-17 08:37:35.938  1346  1346 I wpa_supplicant: htc_wext_set_TX_TRACKING - ret = 0
03-17 08:37:35.938   921  1149 D WifiController: processMsg: DeviceActiveState
03-17 08:37:35.938   921  1148 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
03-17 08:37:35.938   921  1148 D WifiDisplayAdapter:     Client/Owner: Client
03-17 08:37:35.938   921  1148 D WifiDisplayAdapter:     GroupId: 
03-17 08:37:35.938   921  1148 D WifiDisplayAdapter:     Passphrase: 
03-17 08:37:35.938   921  1148 D WifiDisplayAdapter:     SessionId: 0
03-17 08:37:35.938   921  1148 D WifiDisplayAdapter:     IP Address: }
03-17 08:37:35.938   921  1149 D WifiController: processMsg: StaEnabledState
03-17 08:37:35.938   921  1148 E WifiStateMachine: setScanAlarm true period 20000 initial delay 200mAlarmEnabledtrue
03-17 08:37:35.938   921  1148 D WifiStateMachine: backgroundScan enabled=false startBackgroundScanIfNeeded:false
03-17 08:37:35.938   921  1148 E WifiStateMachine: handleScreenStateChanged Exit: true
03-17 08:37:35.948   921  1148 E WifiStateMachine: handleMessage: X
03-17 08:37:35.948   921  1148 E WifiStateMachine: handleMessage: E msg.what=131154
03-17 08:37:35.948   921  1148 E WifiStateMachine: processMsg: ConnectedState
03-17 08:37:35.948   921  1149 D WifiController: processMsg: DefaultState
03-17 08:37:35.948   921  1148 E WifiStateMachine:  ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
03-17 08:37:35.948   921  1148 E WifiStateMachine: processMsg: L2ConnectedState
03-17 08:37:35.948   921  1148 E WifiStateMachine:  L2ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
03-17 08:37:35.948   921  1148 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
03-17 08:37:35.948  1346  1346 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
03-17 08:37:35.948   921  1149 D WifiController: handleMessage: X
,03-17 08:37:35.948   921  1146 D NetworkPolicy: updateScreenOn: false
,03-17 08:37:35.948   921  1146 V NetworkPolicy: updateIfacesLocked()
,03-17 08:37:35.948   921  1146 D NetworkManagementService: isBandwidthControlEnabled: doneSignal.getCount()= 0
,03-17 08:37:35.958  1346  1346 I wpa_supplicant: environment dirty rate=0 [0][0][0]
,03-17 08:37:35.958   921  1148 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 150
03-17 08:37:35.958   921  1148 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-54 linkspeed=150
03-17 08:37:35.958   921  1148 E WifiConfigStore: updateConfiguration freq=2457 BSSID=f4:f2:6d:22:99:3e RSSI=-54 "NG700"WPA_PSK
03-17 08:37:35.958   921  1148 E WifiStateMachine: handleMessage: X
03-17 08:37:35.958   921  1148 E WifiStateMachine: handleMessage: E msg.what=131127
03-17 08:37:35.958   921  1148 E WifiStateMachine: processMsg: ConnectedState
03-17 08:37:35.958   921  1148 E WifiStateMachine:  ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
,03-17 08:37:35.958   921  1148 E WifiStateMachine: processMsg: L2ConnectedState
03-17 08:37:35.958   921  1148 E WifiStateMachine:  L2ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
03-17 08:37:35.958   921  1148 E WifiStateMachine: processMsg: ConnectModeState
,03-17 08:37:35.958   921  1148 E WifiStateMachine:  ConnectModeState !CMD_ENABLE_ALL_NETWORKS 0 0
03-17 08:37:35.958   921  1148 E WifiStateMachine: handleMessage: X
03-17 08:37:35.958   921  1148 E WifiStateMachine: handleMessage: E msg.what=131129
03-17 08:37:35.958   921  1148 E WifiStateMachine: processMsg: ConnectedState
,03-17 08:37:35.958   921  1148 E WifiStateMachine:  ConnectedState !CMD_CLEAR_BLACKLIST 0 0
03-17 08:37:35.958   921  1148 E WifiStateMachine: processMsg: L2ConnectedState
,03-17 08:37:35.958   921  1148 E WifiStateMachine:  L2ConnectedState !CMD_CLEAR_BLACKLIST 0 0
03-17 08:37:35.958   921  1148 E WifiStateMachine: processMsg: ConnectModeState
03-17 08:37:35.958   921  1148 E WifiStateMachine:  ConnectModeState !CMD_CLEAR_BLACKLIST 0 0
03-17 08:37:35.958   921  1148 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
03-17 08:37:35.958  1346  1346 D wpa_supplicant: wlan0: Control interface command 'BLACKLIST clear'
03-17 08:37:35.958  1346  1346 E wpa_supplicant: wlan0: BLACKLIST CLEAR 
03-17 08:37:35.958   921  1644 D WifiMonitor: Event [IFNAME=wlan0 BLACKLIST CLEAR ]
03-17 08:37:35.958   921  1644 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: BLACKLIST CLEAR 
03-17 08:37:35.958   921  1148 E WifiStateMachine: handleMessage: X
,03-17 08:37:35.978   921  1020 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
,03-17 08:37:35.998   921  1401 I ActivityManager: Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=6512 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
,03-17 08:37:35.998  1306  1306 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,03-17 08:37:36.018  1212  1616 I IntentController: receive(android.intent.action.SCREEN_ON,1,false)
,03-17 08:37:36.168   921  1053 D XAN-DPS : prepareColorFade done
,03-17 08:37:36.168   921  1173 D XAN-DPS : setBrightness to 0
,03-17 08:37:36.178  6512  6512 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,03-17 08:37:36.188   921  1053 I SensorManager: unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@1669982a
,03-17 08:37:36.188   921  1053 W SensorService: Following SensorService logs are not warning, just make sure they are printed
03-17 08:37:36.188   921  1046 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
03-17 08:37:36.188   921  1053 W SensorService: disable: get sensor name = CM32181 Light sensor
,03-17 08:37:36.188   921   921 V ActivityManager: Display changed displayId=0
03-17 08:37:36.188   921  1053 W SensorService: pid=921, uid=1000
,03-17 08:37:36.188  1306  1306 D DotMatrix: [EventService]  onDisplayChanged: 0
03-17 08:37:36.188   921  1053 W SensorService: Active sensors: size = 3
03-17 08:37:36.188   921  1053 W SensorService: Accelerometer Sensor (handle=0x00000000, connections=1)
03-17 08:37:36.188   921  1053 W SensorService: CM36686 Proximity sensor (handle=0x00000004, connections=1)
03-17 08:37:36.188   921  1053 W SensorService: Significant Motion (handle=0x0000000d, connections=1)
03-17 08:37:36.188   921  1053 W SensorService: SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@1669982a, eanble = 0, strlen(mName) = 67
03-17 08:37:36.188   921  1053 W SensorService: Active Listeners: mActiveListeners.size() = 1
03-17 08:37:36.188   921  1053 W SensorService: Listener[0] = com.htc.smartdim.sensor_eye@2aaddd92
03-17 08:37:36.188   921  1053 W SensorService: void android::SensorService::listenerSensor(const char*, int32_t)--:
03-17 08:37:36.198  1306  1306 D DotMatrix: [EventService] mbHDMIConnect: false, mCoverOn:false
,03-17 08:37:36.198   385   385 E qdutils : int qdutils::getHDMINode(): Failed to open fb node 2,
03-17 08:37:36.198  6512  6512 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
03-17 08:37:36.198   385   385 E qdutils : int qdutils::getHDMINode(): Failed to find HDMI node
03-17 08:37:36.198   921  1720 D PMS     : acquireWL(3ee7ab33): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1810 10024 WorkSource{10024 com.google.android.gms}
03-17 08:37:36.198  6512  6534 D PowerUsageList:PowerUsageHelper: MY_DEBUG = false
,03-17 08:37:36.208   921  1720 D PMS     : acquireWL(3a23fc69): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1810 10024 WorkSource{10024 com.google.android.gms}
03-17 08:37:36.208   921  1712 D PMS     : releaseWL(3ee7ab33): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,03-17 08:37:36.208   921  1401 D PMS     : releaseWL(3a23fc69): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,03-17 08:37:36.228  6512  6535 D SmartSyncUtils: isEpsOn(), nState = 0
,03-17 08:37:36.238   921  1401 D PMS     : acquireWL(1a70a6ee): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6512 1000 null,
,03-17 08:37:36.248  1212  1212 I SensorManager: registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@a7b2f97, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null
03-17 08:37:36.248   921   921 D AlarmManager: ACTION_SCREEN_OFF
,03-17 08:37:36.248   921  1157 W SensorService: Following SensorService logs are not warning, just make sure they are printed
03-17 08:37:36.248   921  1157 W SensorService: enable: get sensor name = hTC Gesture Motion HIDI
,03-17 08:37:36.258   921   921 I AlarmManager: [AlarmQueuing] screen off now: ,
03-17 08:37:36.258   921   921 I AlarmManager: [AlarmQueuing] data connection: true
03-17 08:37:36.258   921   921 I AlarmManager: [AlarmQueuing] wifi connection: true
03-17 08:37:36.258   921   921 E WifiTrafficPoller: ENABLE_TRAFFIC_STATS_POLL false Token 12
03-17 08:37:36.258   921   921 D WifiDataStallTracker: stopDataStallAlarm 
,03-17 08:37:36.258   921   921 E WifiDataStallTracker: ENABLE_DATA_MONITOR_POLL false Token 2
03-17 08:37:36.258   921  1148 E WifiStateMachine: handleMessage: E msg.what=131167
03-17 08:37:36.258   921  1157 W SensorService: pid=1212, uid=10041
03-17 08:37:36.258   921  1157 W SensorService: Active sensors: size = 4
03-17 08:37:36.258   921  1157 W SensorService: Accelerometer Sensor (handle=0x00000000, connections=1)
03-17 08:37:36.258   921  1157 W SensorService: CM36686 Proximity sensor (handle=0x00000004, connections=1)
03-17 08:37:36.258   921  1157 W SensorService: Significant Motion (handle=0x0000000d, connections=1)
03-17 08:37:36.258   921  1157 W SensorService: hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
03-17 08:37:36.258   921  1148 E WifiStateMachine: processMsg: ConnectedState
03-17 08:37:36.258   921  1148 E WifiStateMachine:  ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
03-17 08:37:36.258   921  1148 E WifiStateMachine: processMsg: L2ConnectedState
03-17 08:37:36.258   921  1148 E WifiStateMachine:  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
03-17 08:37:36.258   921  1148 E WifiStateMachine: processMsg: ConnectModeState
03-17 08:37:36.258   921  1148 E WifiStateMachine:  ConnectModeState !CMD_SCREEN_STATE_CHANGED 0 0
03-17 08:37:36.258   921  1148 E WifiStateMachine: processMsg: DriverStartedState
03-17 08:37:36.258   921  1148 E WifiStateMachine:  DriverStartedState !CMD_SCREEN_STATE_CHANGED 0 0
03-17 08:37:36.258   921  1148 E WifiStateMachine: processMsg: SupplicantStartedState
03-17 08:37:36.258   921  1148 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
03-17 08:37:36.258   921  1148 D WifiDisplayAdapter:     Client/Owner: Client
03-17 08:37:36.258   921  1148 D WifiDisplayAdapter:     GroupId: 
03-17 08:37:36.258   921  1148 D WifiDisplayAdapter:     Passphrase: 
03-17 08:37:36.258   921  1148 D WifiDisplayAdapter:     SessionId: 0
03-17 08:37:36.258   921  1148 D WifiDisplayAdapter:     IP Address: }
03-17 08:37:36.258   921  1148 E WifiStateMachine:  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 0 0
03-17 08:37:36.258   921  1148 E WifiStateMachine: processMsg: DefaultState
03-17 08:37:36.258   921  1148 E WifiStateMachine:  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
03-17 08:37:36.258   921  1148 E WifiStateMachine:  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
03-17 08:37:36.258   921  1148 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
03-17 08:37:36.258  1346  1346 D wpa_supplicant: wlan0: Control interface command 'SET_SCREEN_ON 0'
03-17 08:37:36.258  1346  1346 I wpa_supplicant: SET_SCREEN_ON:Off
03-17 08:37:36.258  1346  1346 I wpa_supplicant: htc_wext_set_keepalive +
03-17 08:37:36.258  1346  1346 I wpa_supplicant: htc_wext_set_keepalive: enable=1, type=2, interval=15
03-17 08:37:36.258  1346  1346 D wpa_supplicant: getPrivFuncNum +	
03-17 08:37:36.258  1346  1346 I wpa_supplicant: getPrivFuncNum -, cmd = 0x8bf6
03-17 08:37:36.258  1346  1346 I wpa_supplicant: htc_wext_set_keepalive fnum = 0x8bf6
03-17 08:37:36.258  1346  1346 I wpa_supplicant: get_ip_address source addr = c0a80166
03-17 08:37:36.258  1346  1346 I wpa_supplicant: htc_wext_set_keepalive gateway addr = c0a80101
03-17 08:37:36.258  1346  1346 I wpa_supplicant: htc_wext_set_keepalive - ret = 0
03-17 08:37:36.258   921  1148 E WifiStateMachine: setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
03-17 08:37:36.258   921   951 W SensorService: SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@a7b2f97, eanble = 1, strlen(mName) = 56
03-17 08:37:36.258   921   951 W SensorService: Active Listeners: mActiveListeners.size() = 2
03-17 08:37:36.258   921   951 W SensorService: Listener[0] = com.htc.smartdim.sensor_eye@2aaddd92
03-17 08:37:36.258   9,21   951 W SensorService: Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@a7b2f97
03-17 08:37:36.258   921   951 W SensorService: void android::SensorService::listenerSensor(const char*, int32_t)--:
03-17 08:37:36.258   424  2002 V SRS_Proc: ParamSet string: screen_state=off
03-17 08:37:36.258   424  2002 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
03-17 08:37:36.258   921  1148 D WifiStateMachine: backgroundScan enabled=true startBackgroundScanIfNeeded:false
03-17 08:37:36.258   921  1148 E WifiStateMachine: handleScreenStateChanged Exit: false
03-17 08:37:36.258   921  1148 E WifiStateMachine: handleMessage: X
03-17 08:37:36.258   921  1148 E WifiStateMachine: handleMessage: E msg.what=131154
03-17 08:37:36.258   921  1148 E WifiStateMachine: processMsg: ConnectedState
03-17 08:37:36.258   921  1148 E WifiStateMachine:  ConnectedState CMD_ENABLE_RSSI_POLL 0 0
03-17 08:37:36.258   921  1148 E WifiStateMachine: processMsg: L2ConnectedState
03-17 08:37:36.258   921  1148 E WifiStateMachine:  L2ConnectedState CMD_ENABLE_RSSI_POLL 0 0
03-17 08:37:36.268   921  1149 D WifiController: handleMessage: E msg.what=155651
03-17 08:37:36.268   921  1149 D WifiController: processMsg: DeviceActiveState
03-17 08:37:36.268   921  1149 D WifiController: processMsg: StaEnabledState
03-17 08:37:36.268   921  1149 D WifiController: processMsg: DefaultState
03-17 08:37:36.268   921  1149 D WifiController: handleMessage: X
,03-17 08:37:36.268   921  1515 D PMS     : releaseWL(1a70a6ee): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
03-17 08:37:36.268   921  1020 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
03-17 08:37:36.268   921  1148 E WifiStateMachine: handleMessage: X
03-17 08:37:36.268   921  1146 D NetworkPolicy: updateScreenOn: false
,03-17 08:37:36.268   921  1146 V NetworkPolicy: updateIfacesLocked()
03-17 08:37:36.268   921  1146 D NetworkManagementService: isBandwidthControlEnabled: doneSignal.getCount()= 0
,03-17 08:37:36.278   921   921 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 
,03-17 08:37:36.278  1306  1306 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,03-17 08:37:36.278  1306  1306 D DotMatrix: [EventService] getTotalRam: 1842 Mb
,03-17 08:37:36.278   921   921 D SmartDim: Init customizeScreenOffDelayClass error
,03-17 08:37:36.288  1433  6541 D ContactMessageStore: start background delete task...
,03-17 08:37:36.288  1212  1616 I IntentController: receive(android.intent.action.SCREEN_OFF,1,false)
,03-17 08:37:36.298  1433  6541 D ContactMessageStore: size: 0 , 0,
03-17 08:37:36.298  1433  6541 D ContactMessageStore: Background delete complete
,03-17 08:37:36.298  6512  6512 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,03-17 08:37:36.308  6512  6512 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
03-17 08:37:36.308   921  1721 D PMS     : acquireWL(1ee7c78f): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1810 10024 WorkSource{10024 com.google.android.gms}
03-17 08:37:36.308   921   950 D PMS     : releaseWL(1ee7c78f): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,03-17 08:37:36.318  6512  6512 D SmartSyncUtils: isEpsOn(), nState = 0,
03-17 08:37:36.318   921  2373 D PMS     : acquireWL(1576f625): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1810 10024 WorkSource{10024 com.google.android.gms}
,03-17 08:37:36.318  6512  6542 D SmartSyncUtils: isEpsOn(), nState = 0
,03-17 08:37:36.318   921  1157 D PMS     : releaseWL(1576f625): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
03-17 08:37:36.318  6512  6512 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
03-17 08:37:36.328   921   921 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 
03-17 08:37:36.338   921   921 I SensorManager: unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@2aaddd92
03-17 08:37:36.338   921   921 W SensorService: Following SensorService logs are not warning, just make sure they are printed
03-17 08:37:36.338   921   921 W SensorService: disable: get sensor name = Accelerometer Sensor
,03-17 08:37:36.338   921   921 W SensorService: pid=921, uid=1000,
03-17 08:37:36.338   921   921 W SensorService: Active sensors: size = 3
03-17 08:37:36.338   921   921 W SensorService: CM36686 Proximity sensor (handle=0x00000004, connections=1)
03-17 08:37:36.338   921   921 W SensorService: Significant Motion (handle=0x0000000d, connections=1),
03-17 08:37:36.338   921   921 W SensorService: hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
03-17 08:37:36.338   921   921 W SensorService: SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@2aaddd92, eanble = 0, strlen(mName) = 36
03-17 08:37:36.338   921   921 W SensorService: Active Listeners: mActiveListeners.size() = 1
03-17 08:37:36.338   921   921 W SensorService: Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@a7b2f97
03-17 08:37:36.338   921   921 W SensorService: void android::SensorService::listenerSensor(const char*, int32_t)--:
03-17 08:37:36.338   921   921 W SensorService: Following SensorService logs are not warning, just make sure they are printed
03-17 08:37:36.338   921   921 W SensorService: disable: get sensor name = CM36686 Proximity sensor
,03-17 08:37:36.338   921   921 W SensorService: pid=921, uid=1000
03-17 08:37:36.338   921   921 W SensorService: Active sensors: size = 2
03-17 08:37:36.338   921   921 W SensorService: Significant Motion (handle=0x0000000d, connections=1)
03-17 08:37:36.338   921   921 W SensorService: hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
03-17 08:37:36.348   921   921 W SensorService: SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@2aaddd92, eanble = 0, strlen(mName) = 36
03-17 08:37:36.348   921   921 W SensorService: Active Listeners: mActiveListeners.size() = 1
03-17 08:37:36.348   921   921 W SensorService: Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@a7b2f97
03-17 08:37:36.348   921   921 W SensorService: void android::SensorService::listenerSensor(const char*, int32_t)--:
,03-17 08:37:36.348   921  6544 I SensorManager: unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@2aaddd92
,03-17 08:37:36.348   921   921 E ActivityThread: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@16760363 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 08:37:36.348   921   921 E ActivityThread: android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@16760363 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 08:37:36.348   921   921 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
03-17 08:37:36.348   921   921 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
03-17 08:37:36.348   921   921 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
03-17 08:37:36.348   921   921 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
03-17 08:37:36.348   921   921 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
03-17 08:37:36.348   921   921 E ActivityThread: 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
03-17 08:37:36.348   921   921 E ActivityThread: 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
03-17 08:37:36.348   921   921 E ActivityThread: 	at android.app.Service.onStartCommand(Service.java:458)
03-17 08:37:36.348   921   921 E ActivityThread: 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3072)
03-17 08:37:36.348   921   921 E ActivityThread: 	at android.app.ActivityThread.access$2100(ActivityThread.java:144)
03-17 08:37:36.348   921   921 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1470)
03-17 08:37:36.348   921   921 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 08:37:36.348   921   921 E ActivityThread: 	at android.os.Looper.loop(Looper.java:155)
03-17 08:37:36.348   921   921 E ActivityThread: 	at com.android.server.SystemServer.run(SystemServer.java:324)
03-17 08:37:36.348   921   921 E ActivityThread: 	at com.android.server.SystemServer.main(SystemServer.java:225)
03-17 08:37:36.348   921   921 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 08:37:36.348   921   921 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 08:37:36.348   921   921 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
03-17 08:37:36.348   921   921 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,03-17 08:37:36.358  1212  1212 I RemoteViews: setHTCTheme(com.htc.updater,true,33751145)
,03-17 08:37:36.368   921  1719 I ActivityManager: Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=6545 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,03-17 08:37:36.368  6512  6534 I PowerUsageList:PowerUsageHelper: PowerProfile::POWER_SCREEN_FULL = 154.8
,03-17 08:37:36.368  1212  1212 I RemoteViews: apply : com.htc.updater 1 12 0 36,
,03-17 08:37:36.388   467   467 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,03-17 08:37:36.398  6512  6534 D PowerUsageList:BatterySipperExt: gen(), null == sipper.uidObj, userId = 0,
,03-17 08:37:36.408  6512  6534 D PowerUsageList:BatterySipperExt: gen(), null == sipper.uidObj, userId = 0,
,03-17 08:37:36.408  6512  6534 D PowerUsageList:BatterySipperExt: gen(), null == sipper.uidObj, userId = 0,
,03-17 08:37:36.448  6512  6534 D PowerUsageService: calcPower(), no data,
,03-17 08:37:36.468  6512  6534 D PowerUsageList:PowerUsageHelper: MY_DEBUG = false,
03-17 08:37:36.468   921  1718 I ActivityManager: Killing 5463:com.google.android.music:main/u0a159 (adj 15): empty #17
03-17 08:37:36.468   921  1718 D Process : killProcessQuiet, pid=5463
,03-17 08:37:36.468   921  1718 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
03-17 08:37:36.468  6512  6542 D SmartSyncUtils: getMobilePolicyEnabled, result = true
,03-17 08:37:36.478   385   864 E qdutils : int qdutils::getHDMINode(): Failed to open fb node 2
03-17 08:37:36.478   385   864 E qdutils : int qdutils::getHDMINode(): Failed to find HDMI node
,03-17 08:37:36.478   921  1173 D SurfaceControl: Excessive delay in setPowerMode(): 292ms
03-17 08:37:36.478   921  1173 D PMS     : Setting HAL interactive mode to false
03-17 08:37:36.488   921  1173 D PMS     : Setting HAL interactive mode to false done
03-17 08:37:36.488   921  1173 D PMS     : Setting HAL auto-suspend mode to true
03-17 08:37:36.488   921  1173 D PMS     : Setting HAL auto-suspend mode done
,03-17 08:37:36.488   921  1149 D WifiService: New client listening to asynchronous messages
03-17 08:37:36.488   921   921 E WifiTrafficPoller: ADD_CLIENT: 9
,03-17 08:37:36.498   921  1712 D PMS     : acquireWL(3f234dab): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 921 1000 null,
03-17 08:37:36.498   921  1712 I BatteryService: n_update end
,03-17 08:37:36.498   921  1712 D PMS     : releaseWL(3f234dab): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,03-17 08:37:36.558   921  1712 I ActivityManager: Recipient 5463
03-17 08:37:36.558   921  1721 D MediaRouterService: Client com.google.android.music (pid 5463): Died!
,03-17 08:37:36.578   921  1555 W HtcSystemUPManager: HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006,
03-17 08:37:36.578   921  1040 I InputMethodManagerService: screenObserver, isScreenOn=false
03-17 08:37:36.578   921  1040 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
03-17 08:37:36.578   921  1040 I InputMethodManagerService: Disable input method client, pid=4594
,03-17 08:37:36.588  1212  1212 I PhoneStatusBar: setImeWindowStatus(false,false)
,03-17 08:37:36.588  4594  4594 I InputMethodManager: [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{3d1298 VFEDH.C. .F...... 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@3b1efd27
,03-17 08:37:36.588   921  1173 D HABCtrl : TPE algorithm. remove timeout.
03-17 08:37:36.588   921  1173 D PMS     : OOBE c monitor 11,
03-17 08:37:36.588   921  1053 D HtcPowerSaver: updateBatteryInfo
,03-17 08:37:36.588  1306  1306 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
03-17 08:37:36.588  1306  1306 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-17 08:37:36.588  1306  1306 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
03-17 08:37:36.588  1212  1212 D PowerUI : closing low battery warning: level=100
03-17 08:37:36.588  1212  1616 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
03-17 08:37:36.588   921   921 I InputManager: Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false
,03-17 08:37:36.598  1212  1212 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
03-17 08:37:36.598  1212  1616 I IntentController: receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
03-17 08:37:36.598   921   921 D NotificationService: plugged=true pluggin=true
03-17 08:37:36.598  3387  3524 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-17 08:37:36.598   921   921 D UsbnetService: BroadcastReceiver::onReceive+
03-17 08:37:36.598  1458  1706 D NfcService: ScreenObserver: OFF
03-17 08:37:36.598   921   921 D UsbnetService: onReceive BATTERY_CHANGED
03-17 08:37:36.598   921   921 D PMS     : runPSCheck
03-17 08:37:36.598   921   921 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
03-17 08:37:36.598   921  1149 D WifiController: battery changed pluggedType: 2
03-17 08:37:36.598   921   921 D UsbnetService: BroadcastReceiver::onReceive-
03-17 08:37:36.598   921   921 D HtcPowerSaver: Checking...
03-17 08:37:36.598   921  1149 D WifiController: handleMessage: E msg.what=155652
03-17 08:37:36.598   921   921 I HtcPowerSaver: >> updateStatus
03-17 08:37:36.598   921  1149 D WifiController: processMsg: DeviceActiveState
03-17 08:37:36.598   921  1149 D WifiController: processMsg: StaEnabledState
03-17 08:37:36.598   921  1149 D WifiController: processMsg: DefaultState
03-17 08:37:36.598   921  1149 D WifiController: handleMessage: X
03-17 08:37:36.598  1458  6569 D NfcService: applyRouting - 0
,03-17 08:37:36.608   921  1514 D PMS     : acquireWL(20f45c08): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1458 1027 null
,03-17 08:37:36.608  1458  6569 D NfcService: applyRouting -2
,03-17 08:37:36.608  1458  6569 D NfcService: applyRouting
03-17 08:37:36.608   921   921 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
03-17 08:37:36.608   921   921 I HtcPowerSaver: << updateStatus
03-17 08:37:36.608  1458  6569 D NfcService: Ignore this applyRouting...
,03-17 08:37:36.608   921  1710 D PMS     : releaseWL(20f45c08): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,03-17 08:37:36.618   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL false Token 13 num clients 9
,03-17 08:37:36.628   921  1720 D Process : killProcessQuiet, pid=6368,
03-17 08:37:36.628   921  1720 I ActivityManager: Killing 6368:com.nero.android.htc.sync/u0a5 (adj 15): empty #17
03-17 08:37:36.638   921  1720 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-17 08:37:36.638   921  1721 D PMS     : releaseWL(174171ec): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,03-17 08:37:36.638  1212  1212 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,03-17 08:37:36.648  1212  1212 I ClockController: stop clock update:screen off
,03-17 08:37:36.738   921  2373 I ActivityManager: Recipient 6368
03-17 08:37:36.738   921  1149 D WifiService: Client connection lost with reason: 4,
,03-17 08:37:36.928   921   921 E WifiTrafficPoller: TRAFFIC_STATS_POLL false Token 13 num clients 8
,03-17 08:37:37.428   921  1148 E WifiStateMachine: handleMessage: E msg.what=131155
03-17 08:37:37.428   921  1148 E WifiStateMachine: processMsg: ConnectedState
03-17 08:37:37.428   921  1148 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-54 f=2457 sc=60 link=150 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2088623202] gl hn u24 rssi=-50 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
03-17 08:37:37.428   921  1148 E WifiStateMachine: processMsg: L2ConnectedState
03-17 08:37:37.428   921  1148 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-54 f=2457 sc=60 link=150 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-2088623200] gl hn u24 rssi=-50 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
03-17 08:37:37.438   921  1148 E WifiStateMachine: handleMessage: X
,03-17 08:37:38.958   921  1148 E WifiStateMachine: handleMessage: E msg.what=131155
03-17 08:37:38.958   921  1148 E WifiStateMachine: processMsg: ConnectedState,
03-17 08:37:38.958   921  1148 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-54 f=2457 sc=60 link=150 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1527] from screen [on:0 period:-2088621671] gl hn u24 rssi=-50 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
03-17 08:37:38.958   921  1148 E WifiStateMachine: processMsg: L2ConnectedState
03-17 08:37:38.958   921  1148 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-54 f=2457 sc=60 link=150 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-2088621669] gl hn u24 rssi=-50 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
03-17 08:37:38.968   921  1148 E WifiStateMachine: handleMessage: X
,03-17 08:37:39.348  1212  1212 D HtcUPManager: HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60,
,03-17 08:37:39.808   921   921 E WifiDataStallTracker: DATA_MONITOR_POLL false Token 3,
,03-17 08:37:40.938   921   921 E WifiDataStallTracker: DATA_MONITOR_POLL false Token 3
,03-17 08:37:46.238   921  1157 D Process : killProcessQuiet, pid=5777,
03-17 08:37:46.238   921  1157 I ActivityManager: Killing 5777:com.htc.musicenhancer/u0a49 (adj 15): empty #17
03-17 08:37:46.238   921  1157 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-17 08:37:46.318   921  1719 I ActivityManager: Recipient 5777,
,03-17 08:37:46.398   467   467 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,03-17 08:38:01.398   467   467 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,03-17 08:38:02.458   921  1020 D GpsLocationProvider: [handleMessage] DOWNLOAD_XTRA_DATA
03-17 08:38:02.458   921  1020 D GpsLocationProvider: [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
03-17 08:38:02.458   921  1020 D PMS     : acquireWL(3245cfa1): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 921 1000 null
,03-17 08:38:02.508   921  6570 D libc    : [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4
,03-17 08:38:02.508   921  6570 D libc    : [NET] android_getaddrinfofornet-, err=8
,03-17 08:38:02.508   921  6570 D libc    : [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
03-17 08:38:02.508   921  6570 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
03-17 08:38:02.508   921  6570 D libc    : [NET] android_getaddrinfo_proxy+
03-17 08:38:02.508   921  6570 D libc    : [NET] android_getaddrinfo_proxy get netid:0
03-17 08:38:02.508   408  6571 D libc    : [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
03-17 08:38:02.508   408  6571 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
,03-17 08:38:02.628   408  6571 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS),
03-17 08:38:02.628   408  6571 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
03-17 08:38:02.628   921  6570 D libc    : [NET] android_getaddrinfo_proxy-, success
,03-17 08:38:02.628   921  6570 D libc    : [NET] android_getaddrinfofornet+,hn 14(0x35342e3139322e),sn(),hints(known),family 0,flags 4,
,03-17 08:38:02.628   921  6570 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
,03-17 08:38:02.988   921  6570 D GpsLocationProvider: [handleDownloadXtraData] calling native_inject_xtra_data,
,03-17 08:38:03.308   921  1424 D GpsLocationProvider: [reportHTCStatus] eventMask = 3 , status = 0,
03-17 08:38:03.308   921  1424 D GpsLocationProvider: [reportHTCStatus] INJECT_XTRA_DATA, status: 0
03-17 08:38:03.308   921  6570 D PMS     : acquireWL(1acec4dd): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 921 1000 null
03-17 08:38:03.308   921  6570 D GpsLocationProvider:  [handleDownloadXtraData]inject done.
03-17 08:38:03.308   921  6570 D PMS     : releaseWL(3245cfa1): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
03-17 08:38:03.308   921  1020 D GpsLocationProvider: [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,03-17 08:38:03.308   921  1020 D PMS     : releaseWL(1acec4dd): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,03-17 08:38:06.328   921  1137 D PMS     : acquireWL(9f35852): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 921 1000 WorkSource{1000},
03-17 08:38:06.328   921  1137 V AlarmManager: sending alarm PendingIntent{4939042: PendingIntentRecord{3dd4b853 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=142648, Int=0
,03-17 08:38:06.328   921  1137 V AlarmManager: sending alarm PendingIntent{2f1c723: PendingIntentRecord{13b0a420 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=148984, Int=0
,03-17 08:38:06.358   921   921 D PMS     : releaseWL(9f35852): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,03-17 08:38:06.358  1212  2488 D WeatherUtility: Weather sync is On
,03-17 08:38:06.358  1212  2488 W WeatherTimeKeeper: [refreshWeatherData] no weather data
,03-17 08:38:21.408   467   467 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,03-17 08:38:21.528   921   921 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,03-17 08:38:33.418   921  1137 D PMS     : acquireWL(4f7d1d9): PARTIAL_WAKE_LOCK  *alarm* 0x1 921 1000 WorkSource{1000},
03-17 08:38:33.418   921  1137 V AlarmManager: sending alarm PendingIntent{64aa79e: PendingIntentRecord{2f0fb27f android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1458200292422, Int=0
03-17 08:38:33.418   921   921 D PMS     : acquireWL(1f4be24c): PARTIAL_WAKE_LOCK  *backup* 0x1 921 1000 null,
,03-17 08:38:33.418   921  1137 V AlarmManager: sending alarm PendingIntent{50ab295: PendingIntentRecord{1c359faa android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=176069, Int=0
,03-17 08:38:33.418   921   921 D PMS     : releaseWL(4f7d1d9): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
,03-17 08:38:33.428   921  1161 W BackupManagerService: Requested unavailable transport: com.google.android.gms.backup.BackupTransportService,
03-17 08:38:33.428   921  1161 E BackupManagerService: Requested init for com.google.android.gms.backup.BackupTransportService but not found
,03-17 08:38:33.438   921  1161 D PMS     : releaseWL(1f4be24c): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,03-17 08:38:36.728   921  4355 D PMS     : acquireWL(f6f79b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 921 1000 null
03-17 08:38:36.728   921   921 D UsbnetService: BroadcastReceiver::onReceive+,
03-17 08:38:36.728   921  4355 I BatteryService: n_update end
,03-17 08:38:36.728   921   921 D UsbnetService: onReceive BATTERY_CHANGED
03-17 08:38:36.728   921  4355 D PMS     : releaseWL(f6f79b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
03-17 08:38:36.728   921   921 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
03-17 08:38:36.728   921   921 D NotificationService: plugged=true pluggin=true
03-17 08:38:36.728   921   921 D UsbnetService: BroadcastReceiver::onReceive-
03-17 08:38:36.738  1212  1212 D PowerUI : closing low battery warning: level=100
03-17 08:38:36.738   921  1149 D WifiController: handleMessage: E msg.what=155652
03-17 08:38:36.738   921  1053 D HtcPowerSaver: updateBatteryInfo
,03-17 08:38:36.738  1306  1306 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-17 08:38:36.738   921   921 D PMS     : runPSCheck
03-17 08:38:36.738  1306  1306 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-17 08:38:36.738   921   921 D HtcPowerSaver: Checking...
03-17 08:38:36.738  1306  1306 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
03-17 08:38:36.738   921   921 I HtcPowerSaver: >> updateStatus
03-17 08:38:36.738   921  1149 D WifiController: processMsg: DeviceActiveState
03-17 08:38:36.738   921  1149 D WifiController: battery changed pluggedType: 2
03-17 08:38:36.738  1212  1616 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
,03-17 08:38:36.738  1212  1212 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
03-17 08:38:36.738   921  1149 D WifiController: processMsg: StaEnabledState
03-17 08:38:36.738   921  1149 D WifiController: processMsg: DefaultState
03-17 08:38:36.738   921  1149 D WifiController: handleMessage: X
03-17 08:38:36.748   921   921 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
03-17 08:38:36.738  3387  3524 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-17 08:38:36.748   921   921 I HtcPowerSaver: << updateStatus
,03-17 08:38:36.788  1212  1212 I BatteryController: status:5 level:100 unsupport:false plugged:true
,03-17 08:38:45.528  1433  1433 D TelephonyReceiver: switchBindHtcMsgCursor: null,
,03-17 08:38:46.408   467   467 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,03-17 08:38:51.118   921  1137 D PMS     : acquireWL(57ad738): PARTIAL_WAKE_LOCK  *alarm* 0x1 921 1000 WorkSource{10024},
,03-17 08:38:51.128   921  1137 V AlarmManager: sending alarm PendingIntent{3030e311: PendingIntentRecord{1a260c76 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=193777, Int=0,
03-17 08:38:51.128   921  1401 D PMS     : acquireWL(13437277): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1882 10024 WorkSource{10024 com.google.android.gms}
03-17 08:38:51.128   921   921 D PMS     : releaseWL(57ad738): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,03-17 08:38:51.168   921  1401 D PMS     : acquireWL(3fa22ee4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1882 10024 WorkSource{10024 com.google.android.gms}
,03-17 08:38:51.198   921  1514 D PMS     : releaseWL(13437277): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,03-17 08:38:51.218  1882  1882 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 08:38:51.248   921  4355 D PMS     : releaseWL(3fa22ee4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,03-17 08:38:51.248   921   951 D PMS     : acquireWL(3cbe344e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1882 10024 WorkSource{10024 com.google.android.gms}
,03-17 08:38:51.258   921  1710 D PMS     : releaseWL(3cbe344e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,03-17 08:38:51.258   921  1157 D PMS     : acquireWL(1340396f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1882 10024 WorkSource{10024 com.google.android.gms}
,03-17 08:38:51.268   921  2373 D PMS     : releaseWL(1340396f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,03-17 08:38:51.268   921  1515 D PMS     : acquireWL(1eb2767c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1882 10024 WorkSource{10024 com.google.android.gms}
,03-17 08:38:51.338   921  1720 D PMS     : acquireWL(11fe6b05): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1882 10024 WorkSource{10024 com.google.android.gms},
,03-17 08:38:51.438   921  1718 D PMS     : acquireWL(4c0fd8b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1882 10024 WorkSource{10024 com.google.android.gms}
,03-17 08:38:51.468   921  1718 D PMS     : releaseWL(1eb2767c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,03-17 08:38:51.478  1882  6575 I VacuumService: Vacuum at: now=1458200331484 tag=VacuumService,
,03-17 08:38:51.508   921  1721 D PMS     : releaseWL(4c0fd8b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,03-17 08:38:51.508   921   950 D PMS     : acquireWL(277fb281): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1882 10024 WorkSource{10024 com.google.android.gms}
,03-17 08:38:51.518   921  1710 D PMS     : releaseWL(11fe6b05): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,03-17 08:38:51.528   921  1401 D PMS     : releaseWL(277fb281): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
03-17 08:38:51.528   921  1716 D PMS     : acquireWL(a887f26): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1882 10024 WorkSource{10024 com.google.android.gms}
,03-17 08:38:51.568   921  1515 D PMS     : releaseWL(a887f26): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
03-17 08:38:51.568   921  1514 D PMS     : acquireWL(103fe767): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1882 10024 WorkSource{10024 com.google.android.gms}
,03-17 08:38:51.578   921  1716 D PMS     : releaseWL(103fe767): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,03-17 08:39:08.408  1212  2517 D HtcUPManager: HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,03-17 08:39:08.408  1212  2517 D HtcUPManager: HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
03-17 08:39:08.408  1568  1568 D HtcAppUPService: HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@8b2371a
,03-17 08:39:08.418   921  1720 D Process : killProcessQuiet, pid=6205
,03-17 08:39:08.418   921  1720 I ActivityManager: Killing 6205:com.google.android.gm/u0a106 (adj 15): empty #17
03-17 08:39:08.418   921  1720 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-17 08:39:08.538   921  1718 I ActivityManager: Recipient 6205
,03-17 08:39:26.418   467   467 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,03-17 08:39:36.418   467   467 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,03-17 08:39:36.878  3387  3524 D HeadsetStateMachine: Disconnected process message: 10, size: 0
03-17 08:39:36.878   921  1157 D PMS     : acquireWL(4611914): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 921 1000 null
03-17 08:39:36.878   921  1157 I BatteryService: n_update end
03-17 08:39:36.888  1212  1616 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
03-17 08:39:36.878   921  1157 D PMS     : releaseWL(4611914): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
03-17 08:39:36.888  1306  1306 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-17 08:39:36.888  1306  1306 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-17 08:39:36.888   921   921 D NotificationService: plugged=true pluggin=true
03-17 08:39:36.888  1306  1306 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
03-17 08:39:36.888  1212  1212 D PowerUI : closing low battery warning: level=100
03-17 08:39:36.888   921   921 D UsbnetService: BroadcastReceiver::onReceive+
03-17 08:39:36.888   921  1149 D WifiController: battery changed pluggedType: 2
03-17 08:39:36.888   921   921 D UsbnetService: onReceive BATTERY_CHANGED
03-17 08:39:36.888  1212  1212 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
03-17 08:39:36.888   921   921 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
03-17 08:39:36.888   921   921 D UsbnetService: BroadcastReceiver::onReceive-
03-17 08:39:36.888   921  1149 D WifiController: handleMessage: E msg.what=155652
03-17 08:39:36.888   921  1149 D WifiController: processMsg: DeviceActiveState
03-17 08:39:36.888   921  1149 D WifiController: processMsg: StaEnabledState
,03-17 08:39:36.888   921  1149 D WifiController: processMsg: DefaultState
03-17 08:39:36.888   921  1053 D HtcPowerSaver: updateBatteryInfo
03-17 08:39:36.888   921  1149 D WifiController: handleMessage: X
,03-17 08:39:36.888   921   921 D PMS     : runPSCheck
03-17 08:39:36.888   921   921 D HtcPowerSaver: Checking...
03-17 08:39:36.888   921   921 I HtcPowerSaver: >> updateStatus
,03-17 08:39:36.888   921   921 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
,03-17 08:39:36.898   921   921 I HtcPowerSaver: << updateStatus
,03-17 08:39:36.938  1212  1212 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,03-17 08:39:43.368  4594  4804 I jxcore-log: Reconnected to the test server,
03-17 08:39:43.368  4594  4804 I jxcore-log: 
,03-17 08:39:46.628  4594  4804 I jxcore-log: TAP version 13,
03-17 08:39:46.628  4594  4804 I jxcore-log: 
,03-17 08:39:46.628  4594  4804 I jxcore-log: # setup,
03-17 08:39:46.628  4594  4804 I jxcore-log: 
,03-17 08:39:46.628  4594  4804 I jxcore-log: # 1. calling createNativeListener directly rejects,
03-17 08:39:46.628  4594  4804 I jxcore-log: 
,03-17 08:39:46.768  4594  4804 I jxcore-log: # teardown,
03-17 08:39:46.768  4594  4804 I jxcore-log: 
,03-17 08:39:46.968  4594  4804 I jxcore-log: ok 1 Should throw,
03-17 08:39:46.968  4594  4804 I jxcore-log: 
,03-17 08:39:46.978  4594  4804 I jxcore-log: # setup,
03-17 08:39:46.978  4594  4804 I jxcore-log: 
,03-17 08:39:47.138  4594  4804 I jxcore-log: # 2. emits incomingConnectionState,
03-17 08:39:47.138  4594  4804 I jxcore-log: 
,03-17 08:39:47.268  4594  4804 I jxcore-log: # teardown,
03-17 08:39:47.268  4594  4804 I jxcore-log: 
,03-17 08:39:47.488  4594  4804 I jxcore-log: ok 2 initial connection state should be CONNECTED,
03-17 08:39:47.488  4594  4804 I jxcore-log: 
,03-17 08:39:47.508  4594  4804 I jxcore-log: ok 3 final connection state should be DISCONNECTED,
03-17 08:39:47.508  4594  4804 I jxcore-log: 
,03-17 08:39:47.518  4594  4804 I jxcore-log: # setup,
03-17 08:39:47.518  4594  4804 I jxcore-log: 
,03-17 08:39:47.698  4594  4804 I jxcore-log: # 3. emits routerPortConnectionFailed,
03-17 08:39:47.698  4594  4804 I jxcore-log: 
,03-17 08:39:47.868  4594  4804 I jxcore-log: # teardown,
03-17 08:39:47.868  4594  4804 I jxcore-log: 
,03-17 08:39:48.128  4594  4804 I jxcore-log: ok 4 tried to connect to right port,
03-17 08:39:48.128  4594  4804 I jxcore-log: 
,03-17 08:39:48.128  4594  4804 I jxcore-log: ok 5 failed due to refused connection
03-17 08:39:48.128  4594  4804 I jxcore-log: 
03-17 08:39:48.128  4594  4804 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
03-17 08:39:48.128  4594  4804 I jxcore-log: 
,03-17 08:39:48.158  4594  4804 I jxcore-log: # setup,
03-17 08:39:48.158  4594  4804 I jxcore-log: 
,03-17 08:39:48.278  4594  4804 I jxcore-log: # 4. native server connections all up,
03-17 08:39:48.278  4594  4804 I jxcore-log: 
,03-17 08:39:48.458  4594  4804 I jxcore-log: # teardown,
03-17 08:39:48.458  4594  4804 I jxcore-log: 
,03-17 08:39:48.718  4594  4804 I jxcore-log: ok 7 Send/recvd #1 should be equal length,
03-17 08:39:48.718  4594  4804 I jxcore-log: 
,03-17 08:39:48.718  4594  4804 I jxcore-log: ok 8 Send/recvd #1 should be same
03-17 08:39:48.718  4594  4804 I jxcore-log: 
03-17 08:39:48.728  4594  4804 I jxcore-log: ok 9 Send/recvd #2 should be equal length
03-17 08:39:48.728  4594  4804 I jxcore-log: 
,03-17 08:39:48.728  4594  4804 I jxcore-log: ok 10 Send/recvd #2 should be same
03-17 08:39:48.728  4594  4804 I jxcore-log: 
03-17 08:39:48.728  4594  4804 I jxcore-log: ok 11 Should be exactly 2 client sockets
03-17 08:39:48.728  4594  4804 I jxcore-log: 
,03-17 08:39:48.738  4594  4804 I jxcore-log: # setup,
03-17 08:39:48.738  4594  4804 I jxcore-log: 
,03-17 08:39:48.858  4594  4804 I jxcore-log: # 5. native server - closing incoming stream cleans outgoing socket,
03-17 08:39:48.858  4594  4804 I jxcore-log: 
,03-17 08:39:49.008  4594  4804 I jxcore-log: # teardown,
03-17 08:39:49.008  4594  4804 I jxcore-log: 
,03-17 08:39:49.208  4594  4804 I jxcore-log: ok 12 socket shouldn't close until after stream,
03-17 08:39:49.208  4594  4804 I jxcore-log: ,
03-17 08:39:49.208  4594  4804 I jxcore-log: ok 13 incoming remains open
03-17 08:39:49.208  4594  4804 I jxcore-log: 
03-17 08:39:49.208  4594  4804 I jxcore-log: # setup
03-17 08:39:49.208  4594  4804 I jxcore-log: 
,03-17 08:39:49.338  4594  4804 I jxcore-log: # 6. native server - closing incoming connection cleans outgoing socket,
03-17 08:39:49.338  4594  4804 I jxcore-log: 
,03-17 08:39:49.538  4594  4804 I jxcore-log: # teardown,
03-17 08:39:49.538  4594  4804 I jxcore-log: 
,03-17 08:39:50.318  4594  4804 I jxcore-log: ok 14 we should not have gotten an error,
03-17 08:39:50.318  4594  4804 I jxcore-log: 
,03-17 08:39:50.358  4594  4804 I jxcore-log: ok 15 socket shouldn't close until after incoming,
03-17 08:39:50.358  4594  4804 I jxcore-log: 
,03-17 08:39:50.358  4594  4804 I jxcore-log: ok 16 incoming is cleaned up
03-17 08:39:50.358  4594  4804 I jxcore-log: 
,03-17 08:39:50.358  4594  4804 I jxcore-log: # setup,
03-17 08:39:50.358  4594  4804 I jxcore-log: 
,03-17 08:39:50.538  4594  4804 I jxcore-log: # 7. native server - closing outgoing socket cleans associated mux stream,
03-17 08:39:50.538  4594  4804 I jxcore-log: 
,03-17 08:39:50.658  4594  4804 I jxcore-log: # teardown,
03-17 08:39:50.658  4594  4804 I jxcore-log: 
,03-17 08:39:50.858  4594  4804 I jxcore-log: ok 17 stream was closed,
03-17 08:39:50.858  4594  4804 I jxcore-log: 
,03-17 08:39:50.858  4594  4804 I jxcore-log: ok 18 incoming should survive
03-17 08:39:50.858  4594  4804 I jxcore-log: 
03-17 08:39:50.858  4594  4804 I jxcore-log: ok 19 mux should have no streams
03-17 08:39:50.858  4594  4804 I jxcore-log: 
,03-17 08:39:50.868  4594  4804 I jxcore-log: # setup,
03-17 08:39:50.868  4594  4804 I jxcore-log: 
,03-17 08:39:50.988  4594  4804 I jxcore-log: # 8. native server - closing the whole server cleans everything up,
03-17 08:39:50.988  4594  4804 I jxcore-log: 
,03-17 08:39:51.088  4594  4804 I jxcore-log: # teardown,
03-17 08:39:51.088  4594  4804 I jxcore-log: 
,03-17 08:39:51.258  4594  4804 I jxcore-log: ok 20 we should not have gotten an error,
03-17 08:39:51.258  4594  4804 I jxcore-log: 
,03-17 08:39:51.278  4594  4804 I jxcore-log: ok 21 Buffers are identical,
,03-17 08:39:51.278  4594  4804 I jxcore-log: 
03-17 08:39:51.288  4594  4804 I jxcore-log: ok 22 native server is nulled out
03-17 08:39:51.288  4594  4804 I jxcore-log: 
03-17 08:39:51.288  4594  4804 I jxcore-log: ok 23 native server should be closed
03-17 08:39:51.288  4594  4804 I jxcore-log: 
03-17 08:39:51.288  4594  4804 I jxcore-log: ok 24 incoming has been removed
03-17 08:39:51.288  4594  4804 I jxcore-log: 
03-17 08:39:51.288  4594  4804 I jxcore-log: ok 25 Incoming should be done
03-17 08:39:51.288  4594  4804 I jxcore-log: 
03-17 08:39:51.298  4594  4804 I jxcore-log: ok 26 The mux object should be closed
03-17 08:39:51.298  4594  4804 I jxcore-log: 
,03-17 08:39:51.298  4594  4804 I jxcore-log: ok 27 The mux stream should be closed
03-17 08:39:51.298  4594  4804 I jxcore-log: 
,03-17 08:39:51.308  4594  4804 I jxcore-log: # setup,
03-17 08:39:51.308  4594  4804 I jxcore-log: 
,03-17 08:39:51.418   467   467 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,03-17 08:39:51.458  4594  4804 I jxcore-log: # 9. native server - we can get a ton of connections and data through and still clean up the server completely,
03-17 08:39:51.458  4594  4804 I jxcore-log: 
,03-17 08:39:51.638  4594  4804 I jxcore-log: # teardown,
03-17 08:39:51.638  4594  4804 I jxcore-log: 
,03-17 08:39:52.208  4594  4804 I jxcore-log: ok 28 native server is nulled out,
03-17 08:39:52.208  4594  4804 I jxcore-log: 
03-17 08:39:52.208  4594  4804 I jxcore-log: ok 29 native server should be closed
03-17 08:39:52.208  4594  4804 I jxcore-log: 
03-17 08:39:52.208  4594  4804 I jxcore-log: ok 30 incoming has been removed
03-17 08:39:52.208  4594  4804 I jxcore-log: 
,03-17 08:39:52.328  4594  4804 I jxcore-log: # setup,
03-17 08:39:52.328  4594  4804 I jxcore-log: 
,03-17 08:39:52.428  4594  4804 I jxcore-log: # 10. native server - simulate mux failure, make sure everything is cleaned up,
03-17 08:39:52.428  4594  4804 I jxcore-log: 
,03-17 08:39:52.638  4594  4804 I jxcore-log: # teardown,
03-17 08:39:52.638  4594  4804 I jxcore-log: 
,03-17 08:39:52.858  4594  4804 I jxcore-log: ok 31 we should not have gotten an error,
03-17 08:39:52.858  4594  4804 I jxcore-log: 
,03-17 08:39:52.868  4594  4804 I jxcore-log: ok 32 Buffers are identical,
03-17 08:39:52.868  4594  4804 I jxcore-log: 
,03-17 08:39:52.898  4594  4804 I jxcore-log: ok 33 server should be fine,
03-17 08:39:52.898  4594  4804 I jxcore-log: 
03-17 08:39:52.898  4594  4804 I jxcore-log: ok 34 server should be open
03-17 08:39:52.898  4594  4804 I jxcore-log: 
03-17 08:39:52.898  4594  4804 I jxcore-log: ok 35 incoming has been removed
03-17 08:39:52.898  4594  4804 I jxcore-log: 
03-17 08:39:52.898  4594  4804 I jxcore-log: ok 36 The mux object should be closed
03-17 08:39:52.898  4594  4804 I jxcore-log: 
,03-17 08:39:52.898  4594  4804 I jxcore-log: ok 37 The mux stream should be closed
03-17 08:39:52.898  4594  4804 I jxcore-log: 
,03-17 08:39:52.908  4594  4804 I jxcore-log: # setup,
03-17 08:39:52.908  4594  4804 I jxcore-log: 
,03-17 08:39:53.068  4594  4804 I jxcore-log: # 11. native server - timing out the incoming connection cleans everything up,
03-17 08:39:53.068  4594  4804 I jxcore-log: 
,03-17 08:39:53.298  4594  4804 I jxcore-log: # teardown,
03-17 08:39:53.298  4594  4804 I jxcore-log: 
,03-17 08:39:53.528  4594  4804 I jxcore-log: ok 38 we should not have gotten an error,
03-17 08:39:53.528  4594  4804 I jxcore-log: 
,03-17 08:39:53.548  4594  4804 I jxcore-log: ok 39 Buffers are identical,
03-17 08:39:53.548  4594  4804 I jxcore-log: 
,03-17 08:39:53.558  4594  4804 I jxcore-log: ok 40 server should be fine,
03-17 08:39:53.558  4594  4804 I jxcore-log: 
03-17 08:39:53.558  4594  4804 I jxcore-log: ok 41 server should be open
03-17 08:39:53.558  4594  4804 I jxcore-log: 
03-17 08:39:53.558  4594  4804 I jxcore-log: ok 42 incoming has been removed
03-17 08:39:53.558  4594  4804 I jxcore-log: 
,03-17 08:39:53.558  4594  4804 I jxcore-log: ok 43 The mux object should be closed
03-17 08:39:53.558  4594  4804 I jxcore-log: 
03-17 08:39:53.558  4594  4804 I jxcore-log: ok 44 The mux stream should be closed
03-17 08:39:53.558  4594  4804 I jxcore-log: 
,03-17 08:39:53.568  4594  4804 I jxcore-log: # setup,
03-17 08:39:53.568  4594  4804 I jxcore-log: 
,03-17 08:39:53.708  4594  4804 I jxcore-log: # 12. closeAll can close even when connections open,
03-17 08:39:53.708  4594  4804 I jxcore-log: 
,03-17 08:39:53.888  4594  4804 I jxcore-log: # teardown,
03-17 08:39:53.888  4594  4804 I jxcore-log: 
,03-17 08:39:54.048  4594  4804 I jxcore-log: ok 45 not possible to connect to the server anymore,
03-17 08:39:54.048  4594  4804 I jxcore-log: 
,03-17 08:39:54.058  4594  4804 I jxcore-log: # setup,
03-17 08:39:54.058  4594  4804 I jxcore-log: 
,03-17 08:39:54.158  4594  4804 I jxcore-log: # 13. closeAll with promise,
03-17 08:39:54.158  4594  4804 I jxcore-log: 
,03-17 08:39:54.288  4594  4804 I jxcore-log: # teardown,
03-17 08:39:54.288  4594  4804 I jxcore-log: 
,03-17 08:39:54.558  4594  4804 I jxcore-log: ok 46 not possible to connect to the server anymore,
03-17 08:39:54.558  4594  4804 I jxcore-log: 
,03-17 08:39:54.558  4594  4804 I jxcore-log: # setup,
03-17 08:39:54.558  4594  4804 I jxcore-log: 
,03-17 08:39:54.718  4594  4804 I jxcore-log: # 14. multiplex can send data,
03-17 08:39:54.718  4594  4804 I jxcore-log: 
,03-17 08:39:54.878  4594  4804 I jxcore-log: # teardown,
03-17 08:39:54.878  4594  4804 I jxcore-log: 
,03-17 08:39:55.128  4594  4804 I jxcore-log: ok 47 String should be length:200,
03-17 08:39:55.128  4594  4804 I jxcore-log: 
,03-17 08:39:55.138  4594  4804 I jxcore-log: # setup,
03-17 08:39:55.138  4594  4804 I jxcore-log: 
,03-17 08:39:55.298  4594  4804 I jxcore-log: # 15. enqueue and run in order,
03-17 08:39:55.298  4594  4804 I jxcore-log: 
,03-17 08:39:55.498  4594  4804 I jxcore-log: # teardown,
03-17 08:39:55.498  4594  4804 I jxcore-log: 
,03-17 08:39:55.758  4594  4804 I jxcore-log: ok 48 firstPromise setTimeout,
03-17 08:39:55.758  4594  4804 I jxcore-log: 
,03-17 08:39:55.758  4594  4804 I jxcore-log: ok 49 firstPromise result
,03-17 08:39:55.758  4594  4804 I jxcore-log: ,
03-17 08:39:55.758  4594  4804 I jxcore-log: ok 50 firstPromise testValue
03-17 08:39:55.758  4594  4804 I jxcore-log: 
,03-17 08:39:55.878  4594  4804 I jxcore-log: ok 51 secondPromise setTimeout,
03-17 08:39:55.878  4594  4804 I jxcore-log: ,
,03-17 08:39:55.878  4594  4804 I jxcore-log: ok 52 secondPromise result
03-17 08:39:55.878  4594  4804 I jxcore-log: 
03-17 08:39:55.878  4594  4804 I jxcore-log: ok 53 secondPromise testValue
03-17 08:39:55.878  4594  4804 I jxcore-log: 
03-17 08:39:55.878  4594  4804 I jxcore-log: ok 54 thirdPromise in promise
03-17 08:39:55.878  4594  4804 I jxcore-log: 
03-17 08:39:55.878  4594  4804 I jxcore-log: ok 55 thirdPromise result
03-17 08:39:55.878  4594  4804 I jxcore-log: 
,03-17 08:39:55.888  4594  4804 I jxcore-log: ok 56 thirdPromise testValue
03-17 08:39:55.888  4594  4804 I jxcore-log: 
,03-17 08:39:55.888  4594  4804 I jxcore-log: # setup
03-17 08:39:55.888  4594  4804 I jxcore-log: 
,03-17 08:39:55.998  4594  4804 I jxcore-log: # 16. enqueueAtTop and run backwards,
03-17 08:39:55.998  4594  4804 I jxcore-log: 
,03-17 08:39:56.188  4594  4804 I jxcore-log: # teardown,
03-17 08:39:56.188  4594  4804 I jxcore-log: 
,03-17 08:39:56.328  4594  4804 I jxcore-log: ok 57 thirdPromise - first to run,
03-17 08:39:56.328  4594  4804 I jxcore-log: 
,03-17 08:39:56.328  4594  4804 I jxcore-log: ok 58 thirdPromise - in resolve,
,03-17 08:39:56.328  4594  4804 I jxcore-log: 
03-17 08:39:56.338  4594  4804 I jxcore-log: ok 59 secondPromise - second to run
03-17 08:39:56.338  4594  4804 I jxcore-log: 
03-17 08:39:56.338  4594  4804 I jxcore-log: ok 60 secondPromise - in catch
03-17 08:39:56.338  4594  4804 I jxcore-log: 
,03-17 08:39:56.338  4594  4804 I jxcore-log: ok 61 firstPromise - third to run
03-17 08:39:56.338  4594  4804 I jxcore-log: 
03-17 08:39:56.338  4594  4804 I jxcore-log: ok 62 firstPromise - in then
03-17 08:39:56.338  4594  4804 I jxcore-log: 
03-17 08:39:56.348  4594  4804 I jxcore-log: ok 63 testing promises
03-17 08:39:56.348  4594  4804 I jxcore-log: 
,03-17 08:39:56.348  4594  4804 I jxcore-log: # setup
03-17 08:39:56.348  4594  4804 I jxcore-log: 
,03-17 08:39:56.558  4594  4804 I jxcore-log: # 17. mix enqueue and enqueueAtTop,
03-17 08:39:56.558  4594  4804 I jxcore-log: 
,03-17 08:39:56.748  4594  4804 I jxcore-log: # teardown,
03-17 08:39:56.748  4594  4804 I jxcore-log: 
,03-17 08:39:56.848  4594  4804 I jxcore-log: ok 64 fourth,
03-17 08:39:56.848  4594  4804 I jxcore-log: 
,03-17 08:39:56.848  4594  4804 I jxcore-log: ok 65 fourth,
03-17 08:39:56.848  4594  4804 I jxcore-log: 
,03-17 08:39:56.858  4594  4804 I jxcore-log: ok 66 second,
,03-17 08:39:56.858  4594  4804 I jxcore-log: 
03-17 08:39:56.858  4594  4804 I jxcore-log: ok 67 secondPromise - in then
03-17 08:39:56.858  4594  4804 I jxcore-log: 
,03-17 08:39:56.958  4594  4804 I jxcore-log: ok 68 first,
03-17 08:39:56.958  4594  4804 I jxcore-log: 
03-17 08:39:56.958  4594  4804 I jxcore-log: ok 69 firstPromise - in catch
03-17 08:39:56.958  4594  4804 I jxcore-log: 
,03-17 08:39:56.968  4594  4804 I jxcore-log: ok 70 third,
03-17 08:39:56.968  4594  4804 I jxcore-log: 
03-17 08:39:56.968  4594  4804 I jxcore-log: ok 71 thirdPromise - in then
03-17 08:39:56.968  4594  4804 I jxcore-log: 
03-17 08:39:56.968  4594  4804 I jxcore-log: ok 72 testingPromises
03-17 08:39:56.968  4594  4804 I jxcore-log: 
,03-17 08:39:56.978  4594  4804 I jxcore-log: # setup
03-17 08:39:56.978  4594  4804 I jxcore-log: 
,03-17 08:39:57.118  4594  4804 I jxcore-log: # 18. queues handled independently,
,03-17 08:39:57.118  4594  4804 I jxcore-log: 
,03-17 08:39:57.278  4594  4804 I jxcore-log: # teardown,
03-17 08:39:57.278  4594  4804 I jxcore-log: 
,03-17 08:39:57.438  4594  4804 I jxcore-log: ok 73 all short operations completed before the long resolves,
03-17 08:39:57.438  4594  4804 I jxcore-log: 
,03-17 08:39:57.438  4594  4804 I jxcore-log: # setup,
03-17 08:39:57.438  4594  4804 I jxcore-log: 
,03-17 08:39:57.618  4594  4804 I jxcore-log: # 19. basic,
03-17 08:39:57.618  4594  4804 I jxcore-log: 
,03-17 08:39:57.728  4594  4804 I jxcore-log: # teardown,
03-17 08:39:57.728  4594  4804 I jxcore-log: 
,03-17 08:39:57.848  4594  4804 I jxcore-log: ok 74 sane
,03-17 08:39:57.848  4594  4804 I jxcore-log: 
,03-17 08:39:57.848  4594  4804 I jxcore-log: # setup
,03-17 08:39:57.848  4594  4804 I jxcore-log: 
,03-17 08:39:57.948  4594  4804 I jxcore-log: # 20. another
03-17 08:39:57.948  4594  4804 I jxcore-log: ,
,03-17 08:39:58.078  4594  4804 I jxcore-log: # teardown
03-17 08:39:58.078  4594  4804 I jxcore-log: ,
,03-17 08:39:58.178  4594  4804 I jxcore-log: ok 75 sane
,03-17 08:39:58.178  4594  4804 I jxcore-log: 
,03-17 08:39:58.178  4594  4804 I jxcore-log: # setup
03-17 08:39:58.178  4594  4804 I jxcore-log: ,
,03-17 08:39:58.338  4594  4804 I jxcore-log: # 21. #startListeningForAdvertisements should fail if start not called
,03-17 08:39:58.338  4594  4804 I jxcore-log: 
,03-17 08:39:58.478  4594  4804 I jxcore-log: # teardown
03-17 08:39:58.478  4594  4804 I jxcore-log: ,
,03-17 08:39:58.628  4594  4804 I jxcore-log: ok 76 specific error should be returned,
03-17 08:39:58.628  4594  4804 I jxcore-log: 
,03-17 08:39:58.638  4594  4804 I jxcore-log: # setup
03-17 08:39:58.638  4594  4804 I jxcore-log: ,
,03-17 08:39:58.798  4594  4804 I jxcore-log: ok 77 error should be null
,03-17 08:39:58.798  4594  4804 I jxcore-log: 
,03-17 08:39:58.798  4594  4804 I jxcore-log: ok 78 error should be null
03-17 08:39:58.798  4594  4804 I jxcore-log: 
,03-17 08:39:58.808  4594  4804 I jxcore-log: # 22. #startUpdateAdvertisingAndListening should fail if start not called
,03-17 08:39:58.808  4594  4804 I jxcore-log: 
,03-17 08:39:59.008  4594  4804 I jxcore-log: # teardown
,03-17 08:39:59.008  4594  4804 I jxcore-log: 
,03-17 08:39:59.268  4594  4804 I jxcore-log: ok 79 specific error should be returned
03-17 08:39:59.268  4594  4804 I jxcore-log: ,
,03-17 08:39:59.268  4594  4804 I jxcore-log: # setup
,03-17 08:39:59.268  4594  4804 I jxcore-log: 
,03-17 08:39:59.458  4594  4804 I jxcore-log: ok 80 error should be null
,03-17 08:39:59.458  4594  4804 I jxcore-log: 
,03-17 08:39:59.458  4594  4804 I jxcore-log: ok 81 error should be null,
03-17 08:39:59.458  4594  4804 I jxcore-log: 
,03-17 08:39:59.458  4594  4804 I jxcore-log: # 23. should be able to call #stopListeningForAdvertisements many times
03-17 08:39:59.458  4594  4804 I jxcore-log: ,
,03-17 08:39:59.828  4594  4804 I jxcore-log: # teardown
,03-17 08:39:59.828  4594  4804 I jxcore-log: 
,03-17 08:40:00.318  4594  4804 I jxcore-log: ok 82 error should be null
03-17 08:40:00.318  4594  4804 I jxcore-log: ,
,03-17 08:40:00.318  4594  4804 I jxcore-log: ok 83 error should be null,
03-17 08:40:00.318  4594  4804 I jxcore-log: ,
,03-17 08:40:00.328  4594  4804 I jxcore-log: ok 84 error should be null
,03-17 08:40:00.328  4594  4804 I jxcore-log: 
03-17 08:40:00.328  4594  4804 I jxcore-log: ok 85 error should be null
03-17 08:40:00.328  4594  4804 I jxcore-log: 
,03-17 08:40:00.328  4594  4804 I jxcore-log: # setup,
03-17 08:40:00.328  4594  4804 I jxcore-log: 
,03-17 08:40:00.518  4594  4804 I jxcore-log: ok 86 error should be null
,03-17 08:40:00.518  4594  4804 I jxcore-log: 
,03-17 08:40:00.518  4594  4804 I jxcore-log: ok 87 error should be null,
03-17 08:40:00.518  4594  4804 I jxcore-log: 
,03-17 08:40:00.528  4594  4804 I jxcore-log: # 24. should be able to call #startListeningForAdvertisements many times
,03-17 08:40:00.528  4594  4804 I jxcore-log: 
,03-17 08:40:00.708  4594  4804 I jxcore-log: # teardown
,03-17 08:40:00.708  4594  4804 I jxcore-log: 
,03-17 08:40:00.888  4594  4804 I jxcore-log: ok 88 error should be null
03-17 08:40:00.888  4594  4804 I jxcore-log: ,
,03-17 08:40:00.898  4594  4804 I jxcore-log: ok 89 error should be null,
03-17 08:40:00.898  4594  4804 I jxcore-log: ,
,03-17 08:40:00.898  4594  4804 I jxcore-log: ok 90 error should be null
,03-17 08:40:00.898  4594  4804 I jxcore-log: 
03-17 08:40:00.898  4594  4804 I jxcore-log: ok 91 error should be null
03-17 08:40:00.898  4594  4804 I jxcore-log: 
,03-17 08:40:00.908  4594  4804 I jxcore-log: # setup
03-17 08:40:00.908  4594  4804 I jxcore-log: 
,03-17 08:40:01.048  4594  4804 I jxcore-log: INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).,
03-17 08:40:01.048  4594  4804 I jxcore-log: 
,03-17 08:40:01.048  4594  4804 I jxcore-log: ok 92 error should be null,
03-17 08:40:01.048  4594  4804 I jxcore-log: 
,03-17 08:40:01.058  4594  4804 I jxcore-log: ok 93 error should be null
03-17 08:40:01.058  4594  4804 I jxcore-log: ,
,03-17 08:40:01.058  4594  4804 I jxcore-log: # 25. should be able to call #startUpdateAdvertisingAndListening many times
,03-17 08:40:01.058  4594  4804 I jxcore-log: 
,03-17 08:40:01.278  4594  4804 I jxcore-log: # teardown
,03-17 08:40:01.278  4594  4804 I jxcore-log: 
,03-17 08:40:01.498  4594  4804 I jxcore-log: ok 94 error should be null,
03-17 08:40:01.498  4594  4804 I jxcore-log: 
,03-17 08:40:01.498  4594  4804 I jxcore-log: ok 95 error should be null
03-17 08:40:01.498  4594  4804 I jxcore-log: 
,03-17 08:40:01.508  4594  4804 I jxcore-log: ok 96 error should be null
03-17 08:40:01.508  4594  4804 I jxcore-log: 
03-17 08:40:01.508  4594  4804 I jxcore-log: ok 97 error should be null
03-17 08:40:01.508  4594  4804 I jxcore-log: 
03-17 08:40:01.508  4594  4804 I jxcore-log: # setup
03-17 08:40:01.508  4594  4804 I jxcore-log: 
,03-17 08:40:01.648  4594  4804 I jxcore-log: INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-17 08:40:01.648  4594  4804 I jxcore-log: 
,03-17 08:40:01.648  4594  4804 I jxcore-log: ok 98 error should be null
,03-17 08:40:01.648  4594  4804 I jxcore-log: ,
03-17 08:40:01.648  4594  4804 I jxcore-log: ok 99 error should be null
03-17 08:40:01.648  4594  4804 I jxcore-log: 
,03-17 08:40:01.658  4594  4804 I jxcore-log: # 26. should be able to call #stopAdvertisingAndListening many times
,03-17 08:40:01.658  4594  4804 I jxcore-log: 
,03-17 08:40:01.848  4594  4804 I jxcore-log: # teardown
03-17 08:40:01.848  4594  4804 I jxcore-log: 
,03-17 08:40:02.028  4594  4804 I jxcore-log: ok 100 error should be null
03-17 08:40:02.028  4594  4804 I jxcore-log: ,
,03-17 08:40:02.028  4594  4804 I jxcore-log: ok 101 error should be null
,03-17 08:40:02.028  4594  4804 I jxcore-log: 
03-17 08:40:02.028  4594  4804 I jxcore-log: ok 102 error should be null,
03-17 08:40:02.028  4594  4804 I jxcore-log: 
03-17 08:40:02.038  4594  4804 I jxcore-log: ok 103 error should be null
03-17 08:40:02.038  4594  4804 I jxcore-log: 
,03-17 08:40:02.038  4594  4804 I jxcore-log: # setup,
03-17 08:40:02.038  4594  4804 I jxcore-log: 
,03-17 08:40:02.168  4594  4804 I jxcore-log: ok 104 error should be null,
03-17 08:40:02.168  4594  4804 I jxcore-log: 
,03-17 08:40:02.178  4594  4804 I jxcore-log: ok 105 error should be null
,03-17 08:40:02.178  4594  4804 I jxcore-log: ,
03-17 08:40:02.178  4594  4804 I jxcore-log: # 27. #start should fail if called twice in a row
03-17 08:40:02.178  4594  4804 I jxcore-log: 
,03-17 08:40:02.338  4594  4804 I jxcore-log: # teardown
03-17 08:40:02.338  4594  4804 I jxcore-log: ,
,03-17 08:40:02.498  4594  4804 I jxcore-log: ok 106 first call should succeed
03-17 08:40:02.498  4594  4804 I jxcore-log: 
,03-17 08:40:02.498  4594  4804 I jxcore-log: ok 107 first call should succeed
03-17 08:40:02.498  4594  4804 I jxcore-log: ,
,03-17 08:40:02.508  4594  4804 I jxcore-log: ok 108 specific error should be returned,
03-17 08:40:02.508  4594  4804 I jxcore-log: 
,03-17 08:40:02.508  4594  4804 I jxcore-log: # setup
03-17 08:40:02.508  4594  4804 I jxcore-log: 
,03-17 08:40:02.738  4594  4804 I jxcore-log: ok 109 error should be null,
03-17 08:40:02.738  4594  4804 I jxcore-log: 
,03-17 08:40:02.738  4594  4804 I jxcore-log: ok 110 error should be null
,03-17 08:40:02.738  4594  4804 I jxcore-log: 
03-17 08:40:02.738  4594  4804 I jxcore-log: # 28. does not emit duplicate discoveryAdvertisingStateUpdate,
03-17 08:40:02.738  4594  4804 I jxcore-log: 
,03-17 08:40:02.858  4594  4804 I jxcore-log: # teardown,
03-17 08:40:02.858  4594  4804 I jxcore-log: 
,03-17 08:40:03.028  4594  4804 I jxcore-log: ok 111 called only once
03-17 08:40:03.028  4594  4804 I jxcore-log: 
,03-17 08:40:03.028  4594  4804 I jxcore-log: ok 112 discovery state matches
03-17 08:40:03.028  4594  4804 I jxcore-log: 
,03-17 08:40:03.028  4594  4804 I jxcore-log: ok 113 advertising state matches
03-17 08:40:03.028  4594  4804 I jxcore-log: 
,03-17 08:40:03.038  4594  4804 I jxcore-log: # setup
03-17 08:40:03.038  4594  4804 I jxcore-log: 
,03-17 08:40:03.288  4594  4804 I jxcore-log: INFO thaliMobile Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
03-17 08:40:03.288  4594  4804 I jxcore-log: ,
,03-17 08:40:03.288  4594  4804 I jxcore-log: INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).,
,03-17 08:40:03.288  4594  4804 I jxcore-log: 
,03-17 08:40:03.298  4594  4804 I jxcore-log: INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-17 08:40:03.298  4594  4804 I jxcore-log: ,
,03-17 08:40:03.298  4594  4804 I jxcore-log: ok 114 error should be null
03-17 08:40:03.298  4594  4804 I jxcore-log: ,
03-17 08:40:03.298  4594  4804 I jxcore-log: ok 115 error should be null
03-17 08:40:03.298  4594  4804 I jxcore-log: 
,03-17 08:40:03.308  4594  4804 I jxcore-log: # 29. does not send duplicate availability changes
03-17 08:40:03.308  4594  4804 I jxcore-log: ,
,03-17 08:40:03.448  4594  4804 I jxcore-log: # teardown
,03-17 08:40:03.448  4594  4804 I jxcore-log: 
,03-17 08:40:03.708  4594  4804 I jxcore-log: ok 116 should be called once
,03-17 08:40:03.708  4594  4804 I jxcore-log: 
,03-17 08:40:03.708  4594  4804 I jxcore-log: ok 117 should not have been called more than once
03-17 08:40:03.708  4594  4804 I jxcore-log: ,
03-17 08:40:03.708  4594  4804 I jxcore-log: # setup
03-17 08:40:03.708  4594  4804 I jxcore-log: 
,03-17 08:40:03.828  4594  4804 I jxcore-log: ok 118 error should be null
03-17 08:40:03.828  4594  4804 I jxcore-log: 
,03-17 08:40:03.838  4594  4804 I jxcore-log: ok 119 error should be null
03-17 08:40:03.838  4594  4804 I jxcore-log: ,
03-17 08:40:03.838  4594  4804 I jxcore-log: # 30. can get the network status
03-17 08:40:03.838  4594  4804 I jxcore-log: 
,03-17 08:40:03.948  4594  4804 I jxcore-log: # teardown,
03-17 08:40:03.948  4594  4804 I jxcore-log: 
,03-17 08:40:04.028  4594  4804 I jxcore-log: ok 120 network status should have certain non-empty properties
03-17 08:40:04.028  4594  4804 I jxcore-log: ,
,03-17 08:40:04.028  4594  4804 I jxcore-log: # setup
,03-17 08:40:04.028  4594  4804 I jxcore-log: ,
,03-17 08:40:04.148  4594  4804 I jxcore-log: ok 121 error should be null
03-17 08:40:04.148  4594  4804 I jxcore-log: ,
,03-17 08:40:04.158  4594  4804 I jxcore-log: ok 122 error should be null,
03-17 08:40:04.158  4594  4804 I jxcore-log: ,
,03-17 08:40:04.158  4594  4804 I jxcore-log: # 31. wifi peer is marked unavailable if announcements stop
03-17 08:40:04.158  4594  4804 I jxcore-log: 
,03-17 08:40:04.288  4594  4804 I jxcore-log: # teardown
,03-17 08:40:04.288  4594  4804 I jxcore-log: 
,03-17 08:40:04.468  4594  4804 I jxcore-log: ok 123 host address should match
03-17 08:40:04.468  4594  4804 I jxcore-log: 
,03-17 08:40:04.468  4594  4804 I jxcore-log: ok 124 port should match
03-17 08:40:04.468  4594  4804 I jxcore-log: 
,03-17 08:40:05.438  4594  4804 I jxcore-log: ok 125 host address should be null
03-17 08:40:05.438  4594  4804 I jxcore-log: ,
,03-17 08:40:05.438  4594  4804 I jxcore-log: ok 126 port should should be null,
03-17 08:40:05.438  4594  4804 I jxcore-log: 
,03-17 08:40:05.458  4594  4804 I jxcore-log: # setup
03-17 08:40:05.458  4594  4804 I jxcore-log: ,
,03-17 08:40:05.548  4594  4804 I jxcore-log: INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-17 08:40:05.548  4594  4804 I jxcore-log: ,
,03-17 08:40:05.558  4594  4804 I jxcore-log: ok 127 error should be null
03-17 08:40:05.558  4594  4804 I jxcore-log: ,
,03-17 08:40:05.558  4594  4804 I jxcore-log: ok 128 error should be null
,03-17 08:40:05.558  4594  4804 I jxcore-log: 
03-17 08:40:05.558  4594  4804 I jxcore-log: # 32. Can call start/stopListeningForAdvertisements
03-17 08:40:05.558  4594  4804 I jxcore-log: 
,03-17 08:40:05.708  4594  4804 I jxcore-log: # teardown,
03-17 08:40:05.708  4594  4804 I jxcore-log: 
,03-17 08:40:05.788  4594  4804 D BluetoothAdapter: 914685262: getState(). Returning 12,
,03-17 08:40:05.798  4594  4804 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
,03-17 08:40:05.798  4594  4804 V io.jxcore.node.ConnectivityMonitor: start: Already started,
03-17 08:40:05.798  4594  4804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only,
,03-17 08:40:05.798  4594  4804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
03-17 08:40:05.798  4594  4804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-17 08:40:05.798  4594  4804 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-17 08:40:05.808  4594  4804 D BluetoothAdapter: 914685262: getState(). Returning 12
03-17 08:40:05.808  4594  4804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-17 08:40:05.808   921  1514 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
03-17 08:40:05.818  4594  4804 D BluetoothAdapter: 914685262: getState(). Returning 12
,03-17 08:40:05.818  4594  4804 D BluetoothAdapter: 914685262: getState(). Returning 12
03-17 08:40:05.818  4594  4804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-17 08:40:05.838  4594  4804 D BluetoothAdapter: 914685262: getState(). Returning 12
,03-17 08:40:05.838  4594  4804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-17 08:40:05.838  4594  4804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", use manufacturer ID: false
03-17 08:40:05.838  4594  4804 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=b6a44ad1-d319-4b3a-815d-8b805a47fb51, mUuidMask=11111111-1111-1111-1110-000000000000, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-17 08:40:05.838  4594  4804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-17 08:40:05.838  4594  4804 D BluetoothAdapter: 914685262: getState(). Returning 12
03-17 08:40:05.838  4594  4804 D BluetoothAdapter: 914685262: getState(). Returning 12
03-17 08:40:05.838  4594  4594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onScanFailed: Feature is not supported, error code is 4
03-17 08:40:05.838  4594  4804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-17 08:40:05.838  4594  4804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-17 08:40:05.838  4594  4804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-17 08:40:05.848  4594  4804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-17 08:40:05.848  4594  4804 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-17 08:40:05.848  4594  4804 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-17 08:40:05.848  4594  4594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-17 08:40:05.848  4594  4594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-17 08:40:05.848  4594  4594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-17 08:40:05.848  4594  4594 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-17 08:40:05.848   921  4355 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,03-17 08:40:05.848  4594  4804 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-17 08:40:05.848  4594  4804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-17 08:40:05.848  4594  4594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-17 08:40:05.848  4594  4594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onScannerFailed: 4
03-17 08:40:05.848  4594  4594 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-17 08:40:05.848  4594  4594 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-17 08:40:05.848  4594  4594 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-17 08:40:05.848  4594  4594 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-17 08:40:05.848  4594  4594 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-17 08:40:05.848  4594  4594 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-17 08:40:05.848  4594  4804 I io.jxcore.node.ConnectionHelper: start: OK
,03-17 08:40:05.848  4594  4804 I jxcore-log: INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-17 08:40:05.848  4594  4804 I jxcore-log: 
,03-17 08:40:05.848  4594  4804 I jxcore-log: INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-17 08:40:05.848  4594  4804 I jxcore-log: ,
,03-17 08:40:05.858  4594  4804 I jxcore-log: INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-17 08:40:05.858  4594  4804 I jxcore-log: 
,03-17 08:40:08.848  4594  4804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only,
03-17 08:40:08.848  4594  4804 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
,03-17 08:40:08.858  4594  4804 I jxcore-log: not ok 129 Can call startListeningForAdvertisements without error,
03-17 08:40:08.858  4594  4804 I jxcore-log: 
03-17 08:40:08.868  4594  4804 I jxcore-log:   ---
03-17 08:40:08.868  4594  4804 I jxcore-log: 
03-17 08:40:08.868  4594  4804 I jxcore-log:     operator: notOk
03-17 08:40:08.868  4594  4804 I jxcore-log: 
03-17 08:40:08.868  4594  4804 I jxcore-log:     expected: |-
03-17 08:40:08.868  4594  4804 I jxcore-log: 
03-17 08:40:08.868  4594  4804 I jxcore-log:       false
03-17 08:40:08.868  4594  4804 I jxcore-log: 
03-17 08:40:08.868  4594  4804 I jxcore-log:     actual: |-
03-17 08:40:08.868  4594  4804 I jxcore-log: 
03-17 08:40:08.868  4594  4804 I jxcore-log:       'Operation timeout, state error: Discovery manager not started'
03-17 08:40:08.868  4594  4804 I jxcore-log: 
03-17 08:40:08.868  4594  4804 I jxcore-log:   ...
03-17 08:40:08.868  4594  4804 I jxcore-log: 
,03-17 08:40:08.868  4594  4804 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-17 08:40:08.868  4594  4804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-17 08:40:08.868  4594  4804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-17 08:40:08.868  4594  4804 I jxcore-log: ok 130 Can call stopListeningForAdvertisements without error,
03-17 08:40:08.868  4594  4804 I jxcore-log: 
,03-17 08:40:08.878  4594  4804 I jxcore-log: # setup,
03-17 08:40:08.878  4594  4804 I jxcore-log: 
,03-17 08:40:08.988  4594  4804 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
03-17 08:40:08.988  4594  4804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only,
,03-17 08:40:08.988  4594  4804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-17 08:40:08.998  4594  4804 I jxcore-log: ok 131 Should be able to call stopListeningForAdvertisments in teardown
03-17 08:40:08.998  4594  4804 I jxcore-log: 
,03-17 08:40:08.998  4594  4804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
,03-17 08:40:08.998  4594  4804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
03-17 08:40:08.998  4594  4804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-17 08:40:08.998  4594  4804 D io.jxcore.node.HandshakeHelper: shutdown
03-17 08:40:08.998  4594  4804 I jxcore-log: ok 132 Should be able to call stopAdvertisingAndListening in teardown
03-17 08:40:08.998  4594  4804 I jxcore-log: 
,03-17 08:40:09.008  4594  4804 I jxcore-log: # 33. Calling startListeningForAdvertisements twice is NOT an error,
03-17 08:40:09.008  4594  4804 I jxcore-log: 
,03-17 08:40:09.248  4594  4804 I jxcore-log: # teardown,
03-17 08:40:09.248  4594  4804 I jxcore-log: 
,03-17 08:40:09.408  4594  4804 D BluetoothAdapter: 914685262: getState(). Returning 12,
,03-17 08:40:09.418  4594  4804 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
,03-17 08:40:09.418  4594  4804 D io.jxcore.node.HandshakeHelper: reinitiate,
,03-17 08:40:09.418  4594  4804 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-17 08:40:09.418  4594  4804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-17 08:40:09.418  4594  4804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
03-17 08:40:09.418  4594  4804 D BluetoothAdapter: 914685262: getState(). Returning 12
03-17 08:40:09.418  4594  4804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-17 08:40:09.418  4594  4804 D BluetoothAdapter: 914685262: getState(). Returning 12
03-17 08:40:09.418  4594  4804 D BluetoothAdapter: 914685262: getState(). Returning 12
03-17 08:40:09.428  4594  4804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-17 08:40:09.428  4594  4594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onScanFailed: Feature is not supported, error code is 4
,03-17 08:40:09.428  4594  4804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-17 08:40:09.428  4594  4804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-17 08:40:09.428  4594  4804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-17 08:40:09.428  4594  4804 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-17 08:40:09.428  4594  4804 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-17 08:40:09.428  4594  4594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-17 08:40:09.428  4594  4594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-17 08:40:09.428  4594  4594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-17 08:40:09.428  4594  4594 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-17 08:40:09.428   921  1716 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,03-17 08:40:09.428  4594  4804 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-17 08:40:09.428  4594  4804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-17 08:40:09.428  4594  4594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-17 08:40:09.428  4594  4594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onScannerFailed: 4
03-17 08:40:09.428  4594  4594 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-17 08:40:09.428  4594  4594 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-17 08:40:09.428  4594  4594 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-17 08:40:09.428  4594  4594 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-17 08:40:09.428  4594  4594 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-17 08:40:09.428  4594  4594 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-17 08:40:09.438  4594  4804 I io.jxcore.node.ConnectionHelper: start: OK
,03-17 08:40:09.438  4594  4804 I jxcore-log: INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
,03-17 08:40:09.438  4594  4804 I jxcore-log: 
,03-17 08:40:09.438  4594  4804 I jxcore-log: INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-17 08:40:09.438  4594  4804 I jxcore-log: 
,03-17 08:40:09.438  4594  4804 I jxcore-log: INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-17 08:40:09.438  4594  4804 I jxcore-log: ,
,03-17 08:40:11.428   467   467 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,03-17 08:40:12.428  4594  4804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-17 08:40:12.438  4594  4804 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started,
,03-17 08:40:12.438  4594  4804 I jxcore-log: not ok 133 Can call startListeningForAdvertisements without error
,03-17 08:40:12.438  4594  4804 I jxcore-log: 
03-17 08:40:12.438  4594  4804 I jxcore-log:   ---
03-17 08:40:12.438  4594  4804 I jxcore-log: 
03-17 08:40:12.438  4594  4804 I jxcore-log:     operator: notOk
03-17 08:40:12.438  4594  4804 I jxcore-log: 
03-17 08:40:12.438  4594  4804 I jxcore-log:     expected: |-
03-17 08:40:12.438  4594  4804 I jxcore-log: 
03-17 08:40:12.438  4594  4804 I jxcore-log:       false
03-17 08:40:12.438  4594  4804 I jxcore-log: 
03-17 08:40:12.438  4594  4804 I jxcore-log:     actual: |-
03-17 08:40:12.438  4594  4804 I jxcore-log: 
03-17 08:40:12.448  4594  4804 I jxcore-log:       'Operation timeout, state error: Discovery manager not started'
,03-17 08:40:12.448  4594  4804 I jxcore-log: 
03-17 08:40:12.448  4594  4804 I jxcore-log:   ...
03-17 08:40:12.448  4594  4804 I jxcore-log: 
03-17 08:40:12.448  4594  4804 D BluetoothAdapter: 914685262: getState(). Returning 12
03-17 08:40:12.448  4594  4804 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
03-17 08:40:12.448  4594  4804 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-17 08:40:12.448  4594  4804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-17 08:40:12.448  4594  4804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-17 08:40:12.458  4594  4804 D BluetoothAdapter: 914685262: getState(). Returning 12
03-17 08:40:12.458  4594  4804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-17 08:40:12.458  4594  4804 D BluetoothAdapter: 914685262: getState(). Returning 12
03-17 08:40:12.458  4594  4804 D BluetoothAdapter: 914685262: getState(). Returning 12
,03-17 08:40:12.458  4594  4804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-17 08:40:12.458  4594  4804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-17 08:40:12.458  4594  4804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-17 08:40:12.458  4594  4804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-17 08:40:12.458  4594  4804 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-17 08:40:12.458  4594  4804 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-17 08:40:12.458  4594  4594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onScanFailed: Feature is not supported, error code is 4
03-17 08:40:12.458  4594  4594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-17 08:40:12.458  4594  4594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-17 08:40:12.458  4594  4594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-17 08:40:12.458   921  1721 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
03-17 08:40:12.458  4594  4594 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,03-17 08:40:12.468  4594  4804 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-17 08:40:12.468  4594  4804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-17 08:40:12.468  4594  4594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-17 08:40:12.468  4594  4594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onScannerFailed: 4
03-17 08:40:12.468  4594  4594 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-17 08:40:12.468  4594  4594 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-17 08:40:12.468  4594  4594 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-17 08:40:12.468  4594  4594 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-17 08:40:12.468  4594  4594 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-17 08:40:12.468  4594  4594 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-17 08:40:12.468  4594  4804 I io.jxcore.node.ConnectionHelper: start: OK
,03-17 08:40:12.468  4594  4804 I jxcore-log: INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-17 08:40:12.468  4594  4804 I jxcore-log: 
,03-17 08:40:12.468  4594  4804 I jxcore-log: INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-17 08:40:12.468  4594  4804 I jxcore-log: 
,03-17 08:40:12.468  4594  4804 I jxcore-log: INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-17 08:40:12.468  4594  4804 I jxcore-log: 
,03-17 08:40:15.468  4594  4804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-17 08:40:15.468  4594  4804 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started,
,03-17 08:40:15.478  4594  4804 I jxcore-log: not ok 134 Can call startListeningForAdvertisements twice without error
,03-17 08:40:15.478  4594  4804 I jxcore-log: 
03-17 08:40:15.478  4594  4804 I jxcore-log:   ---
03-17 08:40:15.478  4594  4804 I jxcore-log: 
03-17 08:40:15.478  4594  4804 I jxcore-log:     operator: notOk
03-17 08:40:15.478  4594  4804 I jxcore-log: 
03-17 08:40:15.478  4594  4804 I jxcore-log:     expected: |-
03-17 08:40:15.478  4594  4804 I jxcore-log: 
03-17 08:40:15.478  4594  4804 I jxcore-log:       false
03-17 08:40:15.478  4594  4804 I jxcore-log: 
03-17 08:40:15.478  4594  4804 I jxcore-log:     actual: |-
03-17 08:40:15.478  4594  4804 I jxcore-log: 
03-17 08:40:15.478  4594  4804 I jxcore-log:       'Operation timeout, state error: Discovery manager not started'
03-17 08:40:15.478  4594  4804 I jxcore-log: 
,03-17 08:40:15.478  4594  4804 I jxcore-log:   ...
03-17 08:40:15.478  4594  4804 I jxcore-log: 
,03-17 08:40:15.488  4594  4804 I jxcore-log: # setup
03-17 08:40:15.488  4594  4804 I jxcore-log: 
,03-17 08:40:15.568  4594  4804 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
03-17 08:40:15.568  4594  4804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only,
03-17 08:40:15.568  4594  4804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
,03-17 08:40:15.578  4594  4804 I jxcore-log: ok 135 Should be able to call stopListeningForAdvertisments in teardown
03-17 08:40:15.578  4594  4804 I jxcore-log: 
,03-17 08:40:15.578  4594  4804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-17 08:40:15.578  4594  4804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-17 08:40:15.578  4594  4804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-17 08:40:15.578  4594  4804 D io.jxcore.node.HandshakeHelper: shutdown
,03-17 08:40:15.578  4594  4804 I jxcore-log: ok 136 Should be able to call stopAdvertisingAndListening in teardown
03-17 08:40:15.578  4594  4804 I jxcore-log: 
,03-17 08:40:15.598  4594  4804 I jxcore-log: # 34. Can call start/stopUpdateAdvertisingAndListening,
03-17 08:40:15.598  4594  4804 I jxcore-log: ,
,03-17 08:40:15.918  4594  4804 I jxcore-log: # teardown,
03-17 08:40:15.918  4594  4804 I jxcore-log: 
,03-17 08:40:16.088  4594  4804 D BluetoothAdapter: 914685262: getState(). Returning 12
,03-17 08:40:16.088  4594  4804 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true,
,03-17 08:40:16.088  4594  4804 D io.jxcore.node.HandshakeHelper: reinitiate,
03-17 08:40:16.088  4594  4804 V io.jxcore.node.ConnectivityMonitor: start: Already started,
03-17 08:40:16.088  4594  4804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-17 08:40:16.088  4594  4804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
03-17 08:40:16.088  4594  4804 D BluetoothAdapter: 914685262: getState(). Returning 12
03-17 08:40:16.098  4594  4804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-17 08:40:16.098  4594  4804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-17 08:40:16.098  4594  4804 D BluetoothAdapter: 914685262: getState(). Returning 12
03-17 08:40:16.098  4594  4804 D BluetoothAdapter: 914685262: getState(). Returning 12
03-17 08:40:16.098  4594  4594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onScanFailed: Feature is not supported, error code is 4
,03-17 08:40:16.098  4594  4804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-17 08:40:16.098  4594  4804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-17 08:40:16.098  4594  4804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-17 08:40:16.098  4594  4804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-17 08:40:16.098  4594  4804 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-17 08:40:16.098  4594  4594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-17 08:40:16.098  4594  4594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-17 08:40:16.108  4594  4804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-17 08:40:16.108  4594  4804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "90:E7:C4:F6:69:77"
03-17 08:40:16.108  4594  4804 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 90 E7 C4 F6 69 77
,03-17 08:40:16.108  4594  4804 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -112, -25, -60, -10, 105, 119]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-17 08:40:16.108  4594  4804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -112, -25, -60, -10, 105, 119]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-17 08:40:16.108  4594  4804 D BluetoothAdapter: 914685262: getState(). Returning 12
,03-17 08:40:16.108  4594  4804 D BluetoothAdapter: 914685262: getState(). Returning 12
03-17 08:40:16.118  4594  4804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-17 08:40:16.118  4594  4804 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-17 08:40:16.118  4594  4594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [ADVERTISING],
03-17 08:40:16.118  4594  4594 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [ADVERTISING]
03-17 08:40:16.118   921  1721 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,03-17 08:40:16.118  4594  4804 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-17 08:40:16.118  4594  4804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-17 08:40:16.118  4594  4594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: true
03-17 08:40:16.118  4594  4594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onScannerFailed: 4
03-17 08:40:16.118  4594  4594 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-17 08:40:16.118  4594  4804 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-17 08:40:16.128  4594  4804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-17 08:40:16.128  4594  4804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-17 08:40:16.128  4594  4804 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-17 08:40:16.128  4594  4804 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING,
03-17 08:40:16.128  4594  4804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-17 08:40:16.128  4594  4804 I io.jxcore.node.ConnectionHelper: start: OK
03-17 08:40:16.128   921  1719 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,03-17 08:40:16.128  4594  4594 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
03-17 08:40:16.128  4594  4594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartFailure: The advertise data to be broadcast is larger than 31 bytes, error code is 1
03-17 08:40:16.128  4594  4594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-17 08:40:16.128  4594  4594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-17 08:40:16.128  4594  4594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-17 08:40:16.128  4594  4594 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-17 08:40:16.128  4594  4594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-17 08:40:16.128  4594  4594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onAdvertiserFailedToStart: 1
03-17 08:40:16.128  4594  4594 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-17 08:40:16.128  4594  4594 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-17 08:40:16.138  4594  4594 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: true
03-17 08:40:16.138  4594  4594 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-17 08:40:16.138  4594  4594 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-17 08:40:16.138  4594  4594 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-17 08:40:16.138  4594  4804 I jxcore-log: INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-17 08:40:16.138  4594  4804 I jxcore-log: 
03-17 08:40:16.138  4594  4594 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-17 08:40:16.138  4594  4594 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-17 08:40:16.138  4594  6584 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-17 08:40:16.138  3387  3523 I bt-btif : BTA_JvCreateRecordByUser,
03-17 08:40:16.138  3387  3611 D bt-btm  : BTM_AllocateSCN
03-17 08:40:16.138  3387  3611 D bt-sdp  : SDP_CreateRecord ok, num_records:16
03-17 08:40:16.138  3387  3611 I bt-btif : BTA_JvRfcommStartServer
03-17 08:40:16.138  3387  3611 I bt-btm  : BTM_SEC_REG[19]: id 61, is_orig 0, psm 0x0003, proto_id 3, chan_id 6
03-17 08:40:16.138  3387  3611 I bt-btm  :                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
03-17 08:40:16.138  4594  4804 I jxcore-log: INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-17 08:40:16.138  4594  4804 I jxcore-log: 
,03-17 08:40:16.148  4594  6584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-17 08:40:16.148  4594  4804 I jxcore-log: INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-17 08:40:16.148  4594  4804 I jxcore-log: 
,03-17 08:40:16.148  4594  4804 I jxcore-log: INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-17 08:40:16.148  4594  4804 I jxcore-log: 
,03-17 08:40:19.128  4594  4804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything,
03-17 08:40:19.128  4594  4804 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
,03-17 08:40:19.138  4594  4804 I jxcore-log: not ok 137 Can call startUpdateAdvertisingAndListening without error,
03-17 08:40:19.138  4594  4804 I jxcore-log: 
,03-17 08:40:19.138  4594  4804 I jxcore-log:   ---
03-17 08:40:19.138  4594  4804 I jxcore-log: 
03-17 08:40:19.138  4594  4804 I jxcore-log:     operator: notOk
03-17 08:40:19.138  4594  4804 I jxcore-log: 
03-17 08:40:19.138  4594  4804 I jxcore-log:     expected: |-
03-17 08:40:19.138  4594  4804 I jxcore-log: 
03-17 08:40:19.138  4594  4804 I jxcore-log:       false
03-17 08:40:19.138  4594  4804 I jxcore-log: 
03-17 08:40:19.138  4594  4804 I jxcore-log:     actual: |-
03-17 08:40:19.138  4594  4804 I jxcore-log: 
03-17 08:40:19.138  4594  4804 I jxcore-log:       'Operation timeout, state error: Discovery manager not started'
03-17 08:40:19.138  4594  4804 I jxcore-log: 
,03-17 08:40:19.138  4594  4804 I jxcore-log:   ...
03-17 08:40:19.138  4594  4804 I jxcore-log: 
03-17 08:40:19.138  4594  4804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-17 08:40:19.138  4594  4804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-17 08:40:19.138  4594  4804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-17 08:40:19.138  4594  4804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-17 08:40:19.148  4594  4804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-17 08:40:19.148  4594  4804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-17 08:40:19.148  3387  3688 I bt-btif : BTA_JvDeleteRecord
03-17 08:40:19.148  4594  4804 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-17 08:40:19.148  3387  3688 I bt-btif : BTA_JvRfcommStopServer
03-17 08:40:19.148  3387  3611 D bt-sdp  : SDP_DeleteRecord ok, num_records:15
03-17 08:40:19.148  4594  4804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-17 08:40:19.148  4594  4804 D io.jxcore.node.HandshakeHelper: shutdown
03-17 08:40:19.148  4594  6584 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Bluetooth server socket closed
03-17 08:40:19.148  4594  6584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-17 08:40:19.148  4594  6584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-17 08:40:19.148  4594  4594 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-17 08:40:19.148  4594  4594 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-17 08:40:19.148  4594  4594 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-17 08:40:19.148  3387  3688 D bt-btm  : BTM_FreeSCN 
03-17 08:40:19.148  4594  4594 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-17 08:40:19.148  4594  4594 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-17 08:40:19.148  4594  4804 I jxcore-log: ok 138 Can call stopAdvertisingAndListening without error
03-17 08:40:19.148  4594  4804 I jxcore-log: 
,03-17 08:40:19.158  3387  3611 I bt-btm  : BTM_SEC_CLR[19]: id 61,
,03-17 08:40:19.158  4594  4804 I jxcore-log: # setup
03-17 08:40:19.158  4594  4804 I jxcore-log: 
,03-17 08:40:19.428  4594  4804 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
03-17 08:40:19.428  4594  4804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only,
,03-17 08:40:19.428  4594  4804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-17 08:40:19.428  4594  4804 I jxcore-log: ok 139 Should be able to call stopListeningForAdvertisments in teardown
03-17 08:40:19.428  4594  4804 I jxcore-log: 
03-17 08:40:19.428  4594  4804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-17 08:40:19.428  4594  4804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
03-17 08:40:19.438  4594  4804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-17 08:40:19.438  4594  4804 I jxcore-log: ok 140 Should be able to call stopAdvertisingAndListening in teardown
03-17 08:40:19.438  4594  4804 I jxcore-log: 
,03-17 08:40:19.448  4594  4804 I jxcore-log: # 35. Calling startUpdateAdvertisingAndListening twice is NOT an error,
03-17 08:40:19.448  4594  4804 I jxcore-log: 
,03-17 08:40:19.538  4594  4804 I jxcore-log: # teardown,
03-17 08:40:19.538  4594  4804 I jxcore-log: 
,03-17 08:40:19.648  4594  4804 D BluetoothAdapter: 914685262: getState(). Returning 12,
,03-17 08:40:19.648  4594  4804 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
,03-17 08:40:19.648  4594  4804 D io.jxcore.node.HandshakeHelper: reinitiate,
,03-17 08:40:19.648  4594  4804 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-17 08:40:19.648  4594  4804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-17 08:40:19.648  4594  4804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-17 08:40:19.648  4594  4804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
03-17 08:40:19.648  4594  4804 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
03-17 08:40:19.658  4594  4804 D BluetoothAdapter: 914685262: getState(). Returning 12
03-17 08:40:19.658  4594  4804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-17 08:40:19.658  4594  4804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-17 08:40:19.658  4594  4804 D BluetoothAdapter: 914685262: getState(). Returning 12
03-17 08:40:19.658  4594  4804 D BluetoothAdapter: 914685262: getState(). Returning 12
03-17 08:40:19.658  4594  4594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onScanFailed: Feature is not supported, error code is 4
03-17 08:40:19.658  4594  4804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-17 08:40:19.658  4594  4804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-17 08:40:19.668  4594  4804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-17 08:40:19.668  4594  4804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-17 08:40:19.668  4594  4804 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-17 08:40:19.668  4594  4804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-17 08:40:19.668  4594  4804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "90:E7:C4:F6:69:77"
03-17 08:40:19.668  4594  4804 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 90 E7 C4 F6 69 77
03-17 08:40:19.668  4594  4804 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -112, -25, -60, -10, 105, 119]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-17 08:40:19.668  4594  4804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -112, -25, -60, -10, 105, 119]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-17 08:40:19.668  4594  4594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-17 08:40:19.668  4594  4804 D BluetoothAdapter: 914685262: getState(). Returning 12
03-17 08:40:19.668  4594  4594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-17 08:40:19.668  4594  4804 D BluetoothAdapter: 914685262: getState(). Returning 12
,03-17 08:40:19.668  4594  4804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-17 08:40:19.668  4594  4804 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-17 08:40:19.668  4594  4594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [ADVERTISING]
03-17 08:40:19.668  4594  4594 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [ADVERTISING]
,03-17 08:40:19.668   921   951 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
03-17 08:40:19.678  4594  4804 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-17 08:40:19.678  4594  4804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-17 08:40:19.678  4594  4594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: true
03-17 08:40:19.678  4594  4594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onScannerFailed: 4
03-17 08:40:19.678  4594  4594 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-17 08:40:19.678  4594  4804 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-17 08:40:19.678  4594  4804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-17 08:40:19.678  4594  4804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-17 08:40:19.678  4594  4804 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-17 08:40:19.678  4594  4804 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-17 08:40:19.678  4594  4804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-17 08:40:19.678  4594  4804 I io.jxcore.node.ConnectionHelper: start: OK
03-17 08:40:19.678  4594  4594 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
03-17 08:40:19.678  4594  4594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartFailure: The advertise data to be broadcast is larger than 31 bytes, error code is 1
03-17 08:40:19.678  4594  4594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-17 08:40:19.678  4594  4594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-17 08:40:19.678  4594  4594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-17 08:40:19.678  4594  4594 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-17 08:40:19.678  4594  4594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-17 08:40:19.678  4594  4594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onAdvertiserFailedToStart: 1
03-17 08:40:19.678  4594  4594 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-17 08:40:19.678  4594  4594 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-17 08:40:19.678  4594  4804 I jxcore-log: INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-17 08:40:19.678  4594  4804 I jxcore-log: 
03-17 08:40:19.678  4594  4594 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: true
03-17 08:40:19.678  4594  4594 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-17 08:40:19.678  4594 , 4594 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-17 08:40:19.678  4594  4594 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-17 08:40:19.678  4594  4594 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-17 08:40:19.678  4594  4594 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-17 08:40:19.678  4594  4804 I jxcore-log: INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-17 08:40:19.678  4594  4804 I jxcore-log: 
03-17 08:40:19.688   921  1720 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
03-17 08:40:19.688  4594  4804 I jxcore-log: INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
,03-17 08:40:19.688  4594  4804 I jxcore-log: 
03-17 08:40:19.688  4594  6585 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-17 08:40:19.688  4594  4804 I jxcore-log: INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-17 08:40:19.688  4594  4804 I jxcore-log: 
03-17 08:40:19.688  3387  3422 I bt-btif : BTA_JvCreateRecordByUser
03-17 08:40:19.688  3387  3611 D bt-btm  : BTM_AllocateSCN
03-17 08:40:19.688  3387  3611 D bt-sdp  : SDP_CreateRecord ok, num_records:16
03-17 08:40:19.688  3387  3611 I bt-btif : BTA_JvRfcommStartServer
,03-17 08:40:19.688  3387  3611 I bt-btm  : BTM_SEC_REG[19]: id 61, is_orig 0, psm 0x0003, proto_id 3, chan_id 6
03-17 08:40:19.688  3387  3611 I bt-btm  :                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
03-17 08:40:19.688  4594  6585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-17 08:40:22.678  4594  4804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything,
03-17 08:40:22.678  4594  4804 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
,03-17 08:40:22.678  4594  4804 I jxcore-log: not ok 141 Can call startUpdateAdvertisingAndListening without error
03-17 08:40:22.678  4594  4804 I jxcore-log: 
03-17 08:40:22.688  4594  4804 I jxcore-log:   ---,
03-17 08:40:22.688  4594  4804 I jxcore-log: 
03-17 08:40:22.688  4594  4804 I jxcore-log:     operator: notOk
,03-17 08:40:22.688  4594  4804 I jxcore-log: ,
03-17 08:40:22.688  4594  4804 I jxcore-log:     expected: |-
03-17 08:40:22.688  4594  4804 I jxcore-log: 
03-17 08:40:22.688  4594  4804 I jxcore-log:       false
03-17 08:40:22.688  4594  4804 I jxcore-log: 
03-17 08:40:22.688  4594  4804 I jxcore-log:     actual: |-
03-17 08:40:22.688  4594  4804 I jxcore-log: 
03-17 08:40:22.688  4594  4804 I jxcore-log:       'Operation timeout, state error: Discovery manager not started'
03-17 08:40:22.688  4594  4804 I jxcore-log: 
03-17 08:40:22.688  4594  4804 I jxcore-log:   ...
03-17 08:40:22.688  4594  4804 I jxcore-log: 
03-17 08:40:22.688  4594  4804 D BluetoothAdapter: 914685262: getState(). Returning 12
03-17 08:40:22.688  4594  4804 I io.jxcore.node.ConnectionHelper: start: Port number: 4243, start advertisements: true
03-17 08:40:22.688  4594  4804 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-17 08:40:22.688  4594  4804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-17 08:40:22.688  4594  4804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-17 08:40:22.688  4594  4804 D BluetoothAdapter: 914685262: getState(). Returning 12
,03-17 08:40:22.688  4594  4804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-17 08:40:22.688  4594  4804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-17 08:40:22.688  4594  4804 D BluetoothAdapter: 914685262: getState(). Returning 12
03-17 08:40:22.698  4594  4804 D BluetoothAdapter: 914685262: getState(). Returning 12
03-17 08:40:22.698  4594  4804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-17 08:40:22.698  4594  4804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-17 08:40:22.698  4594  4804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-17 08:40:22.698  4594  4804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-17 08:40:22.698  4594  4804 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-17 08:40:22.698  4594  4804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-17 08:40:22.698  4594  4804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "90:E7:C4:F6:69:77"
03-17 08:40:22.698  4594  4804 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 90 E7 C4 F6 69 77
03-17 08:40:22.698  4594  4804 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -112, -25, -60, -10, 105, 119]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-17 08:40:22.698  4594  4804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -112, -25, -60, -10, 105, 119]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-17 08:40:22.698  4594  4594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onScanFailed: Feature is not supported, error code is 4
03-17 08:40:22.698  4594  4804 D BluetoothAdapter: 914685262: getState(). Returning 12
03-17 08:40:22.698  4594  4594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-17 08:40:22.698  4594  4594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-17 08:40:22.698  4594  4804 D BluetoothAdapter: 914685262: getState(). Returning 12
,03-17 08:40:22.698  4594  4804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-17 08:40:22.698  4594  4804 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-17 08:40:22.698  4594  4594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [ADVERTISING]
03-17 08:40:22.698  4594  4594 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [ADVERTISING]
03-17 08:40:22.698   921  1718 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,03-17 08:40:22.698  4594  4804 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-17 08:40:22.698  4594  4804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-17 08:40:22.698  4594  4804 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-17 08:40:22.698  4594  4804 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: Already running, call stopListeningForIncomingConnections() first in order to restart
03-17 08:40:22.698  4594  4804 I io.jxcore.node.ConnectionHelper: start: OK
03-17 08:40:22.698  4594  4594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: true
03-17 08:40:22.698  4594  4594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onScannerFailed: 4
03-17 08:40:22.698  4594  4594 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-17 08:40:22.698  4594  4594 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,03-17 08:40:22.708  4594  4594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartFailure: The advertise data to be broadcast is larger than 31 bytes, error code is 1
03-17 08:40:22.708  4594  4594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-17 08:40:22.708  4594  4594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-17 08:40:22.708  4594  4594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-17 08:40:22.708  4594  4594 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-17 08:40:22.708  4594  4594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-17 08:40:22.708  4594  4594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onAdvertiserFailedToStart: 1
03-17 08:40:22.708  4594  4594 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-17 08:40:22.708  4594  4594 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-17 08:40:22.708  4594  4594 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: true
03-17 08:40:22.708  4594  4594 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-17 08:40:22.708  4594  4594 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-17 08:40:22.708  4594  4594 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-17 08:40:22.708  4594  4804 I jxcore-log: INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-17 08:40:22.708  4594  4804 I jxcore-log: 
,03-17 08:40:22.708  4594  4804 I jxcore-log: INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-17 08:40:22.708  4594  4804 I jxcore-log: 
,03-17 08:40:22.708  4594  4804 I jxcore-log: INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-17 08:40:22.708  4594  4804 I jxcore-log: 
,03-17 08:40:22.708  4594  4804 I jxcore-log: INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-17 08:40:22.708  4594  4804 I jxcore-log: 
,03-17 08:40:25.698  4594  4804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything,
03-17 08:40:25.698  4594  4804 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
,03-17 08:40:25.718  4594  4804 I jxcore-log: not ok 142 Can call startUpdateAdvertisingAndListening twice without error,
03-17 08:40:25.718  4594  4804 I jxcore-log: 
,03-17 08:40:25.718  4594  4804 I jxcore-log:   ---
03-17 08:40:25.718  4594  4804 I jxcore-log: 
03-17 08:40:25.718  4594  4804 I jxcore-log:     operator: notOk
03-17 08:40:25.718  4594  4804 I jxcore-log: 
03-17 08:40:25.718  4594  4804 I jxcore-log:     expected: |-
03-17 08:40:25.718  4594  4804 I jxcore-log: 
03-17 08:40:25.718  4594  4804 I jxcore-log:       false
03-17 08:40:25.718  4594  4804 I jxcore-log: 
03-17 08:40:25.718  4594  4804 I jxcore-log:     actual: |-
03-17 08:40:25.718  4594  4804 I jxcore-log: 
,03-17 08:40:25.718  4594  4804 I jxcore-log:       'Operation timeout, state error: Discovery manager not started'
03-17 08:40:25.718  4594  4804 I jxcore-log: 
03-17 08:40:25.718  4594  4804 I jxcore-log:   ...
03-17 08:40:25.718  4594  4804 I jxcore-log: 
,03-17 08:40:25.728  4594  4804 I jxcore-log: # setup
03-17 08:40:25.728  4594  4804 I jxcore-log: 
,03-17 08:40:26.038  4594  4804 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-17 08:40:26.038  4594  4804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only,
03-17 08:40:26.038  4594  4804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-17 08:40:26.048  4594  4804 I jxcore-log: ok 143 Should be able to call stopListeningForAdvertisments in teardown
03-17 08:40:26.048  4594  4804 I jxcore-log: 
,03-17 08:40:26.048  4594  4804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-17 08:40:26.048  4594  4804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-17 08:40:26.048  4594  4804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-17 08:40:26.048  4594  4804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-17 08:40:26.048  4594  4804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-17 08:40:26.048  4594  4804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-17 08:40:26.048  4594  4804 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-17 08:40:26.048  4594  6585 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Bluetooth server socket closed
03-17 08:40:26.048  4594  6585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-17 08:40:26.048  4594  6585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-17 08:40:26.048  3387  3688 I bt-btif : BTA_JvDeleteRecord
03-17 08:40:26.048  3387  3688 I bt-btif : BTA_JvRfcommStopServer
03-17 08:40:26.048  4594  4804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-17 08:40:26.048  4594  4804 D io.jxcore.node.HandshakeHelper: shutdown
,03-17 08:40:26.048  3387  3688 D bt-btm  : BTM_FreeSCN 
03-17 08:40:26.048  3387  3611 D bt-sdp  : SDP_DeleteRecord ok, num_records:15
03-17 08:40:26.048  3387  3611 I bt-btm  : BTM_SEC_CLR[19]: id 61
03-17 08:40:26.048  4594  4594 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-17 08:40:26.048  4594  4594 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-17 08:40:26.048  4594  4594 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-17 08:40:26.048  4594  4594 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-17 08:40:26.048  4594  4594 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-17 08:40:26.058  4594  4804 I jxcore-log: ok 144 Should be able to call stopAdvertisingAndListening in teardown
03-17 08:40:26.058  4594  4804 I jxcore-log: 
,03-17 08:40:26.068  4594  4804 I jxcore-log: # 36. peerAvailabilityChange is called
03-17 08:40:26.068  4594  4804 I jxcore-log: 
,03-17 08:40:26.238  4594  4804 I jxcore-log: # teardown
,03-17 08:40:26.238  4594  4804 I jxcore-log: 
,03-17 08:40:26.488  4594  4804 D BluetoothAdapter: 914685262: getState(). Returning 12
,03-17 08:40:26.498  4594  4804 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true,
03-17 08:40:26.498  4594  4804 D io.jxcore.node.HandshakeHelper: reinitiate,
03-17 08:40:26.498  4594  4804 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-17 08:40:26.498  4594  4804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-17 08:40:26.498  4594  4804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
03-17 08:40:26.498  4594  4804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-17 08:40:26.498  4594  4804 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-17 08:40:26.498  4594  4804 D BluetoothAdapter: 914685262: getState(). Returning 12
03-17 08:40:26.508  4594  4804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-17 08:40:26.508  4594  4804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-17 08:40:26.508  4594  4804 D BluetoothAdapter: 914685262: getState(). Returning 12
,03-17 08:40:26.508  4594  4804 D BluetoothAdapter: 914685262: getState(). Returning 12
,03-17 08:40:26.508  4594  4804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-17 08:40:26.508  4594  4594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onScanFailed: Feature is not supported, error code is 4
03-17 08:40:26.508  4594  4804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-17 08:40:26.508  4594  4804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-17 08:40:26.508  4594  4804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-17 08:40:26.508  4594  4804 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-17 08:40:26.508  4594  4804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-17 08:40:26.508  4594  4804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "90:E7:C4:F6:69:77"
03-17 08:40:26.508  4594  4804 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 90 E7 C4 F6 69 77
03-17 08:40:26.508  4594  4804 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -112, -25, -60, -10, 105, 119]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-17 08:40:26.508  4594  4804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -112, -25, -60, -10, 105, 119]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-17 08:40:26.508  4594  4594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-17 08:40:26.508  4594  4594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-17 08:40:26.508  4594  4804 D BluetoothAdapter: 914685262: getState(). Returning 12
03-17 08:40:26.518  4594  4804 D BluetoothAdapter: 914685262: getState(). Returning 12
,03-17 08:40:26.518  4594  4804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-17 08:40:26.518  4594  4804 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-17 08:40:26.518  4594  4594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [ADVERTISING]
03-17 08:40:26.518  4594  4594 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [ADVERTISING]
,03-17 08:40:26.518   921  1710 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,03-17 08:40:26.518  4594  4804 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-17 08:40:26.518  4594  4804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-17 08:40:26.518  4594  4594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: true
03-17 08:40:26.518  4594  4594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onScannerFailed: 4
03-17 08:40:26.518  4594  4594 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-17 08:40:26.518  4594  4804 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-17 08:40:26.518  4594  4804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-17 08:40:26.518  4594  4804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-17 08:40:26.518  4594  4804 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-17 08:40:26.518  4594  4804 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-17 08:40:26.518  4594  4804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-17 08:40:26.528  4594  4594 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
03-17 08:40:26.528  4594  4594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartFailure: The advertise data to be broadcast is larger than 31 bytes, error code is 1
03-17 08:40:26.528  4594  4594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-17 08:40:26.528  4594  4594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-17 08:40:26.528  4594  4594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-17 08:40:26.528  4594  4594 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-17 08:40:26.528  4594  4594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-17 08:40:26.528  4594  4594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onAdvertiserFailedToStart: 1
03-17 08:40:26.528  4594  4594 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-17 08:40:26.528  4594  4594 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-17 08:40:26.528  4594  4594 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: true
03-17 08:40:26.528  4594  4594 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-17 08:40:26.528  4594  4594 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-17 08:40:26.528  4594  4594 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-17 08:40:26.528  4594  4594 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTE,D, is discovering: false, is advertising: false
03-17 08:40:26.528  4594  4594 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-17 08:40:26.528  4594  4804 I io.jxcore.node.ConnectionHelper: start: OK
03-17 08:40:26.528   921  1157 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
03-17 08:40:26.528  4594  4804 I jxcore-log: INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-17 08:40:26.528  4594  4804 I jxcore-log: 
,03-17 08:40:26.528  4594  6586 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-17 08:40:26.528  4594  4804 I jxcore-log: INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-17 08:40:26.528  4594  4804 I jxcore-log: 
03-17 08:40:26.528  4594  4804 I jxcore-log: INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-17 08:40:26.528  4594  4804 I jxcore-log: 
03-17 08:40:26.528  3387  3523 I bt-btif : BTA_JvCreateRecordByUser
03-17 08:40:26.528  3387  3611 D bt-btm  : BTM_AllocateSCN
,03-17 08:40:26.528  4594  4804 I jxcore-log: INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-17 08:40:26.528  4594  4804 I jxcore-log: 
03-17 08:40:26.538  3387  3611 D bt-sdp  : SDP_CreateRecord ok, num_records:16
03-17 08:40:26.538  3387  3611 I bt-btif : BTA_JvRfcommStartServer
03-17 08:40:26.538  3387  3611 I bt-btm  : BTM_SEC_REG[19]: id 61, is_orig 0, psm 0x0003, proto_id 3, chan_id 6
03-17 08:40:26.538  3387  3611 I bt-btm  :                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
03-17 08:40:26.538  4594  6586 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-17 08:40:29.518  4594  4804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-17 08:40:29.528  4594  4804 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started,
,03-17 08:40:29.528  4594  4804 I jxcore-log: not ok 145 Can call startUpdateAdvertisingAndListeningwithout error
,03-17 08:40:29.528  4594  4804 I jxcore-log: 
03-17 08:40:29.528  4594  4804 I jxcore-log:   ---
03-17 08:40:29.528  4594  4804 I jxcore-log: 
03-17 08:40:29.528  4594  4804 I jxcore-log:     operator: notOk
03-17 08:40:29.528  4594  4804 I jxcore-log: 
03-17 08:40:29.528  4594  4804 I jxcore-log:     expected: |-
03-17 08:40:29.528  4594  4804 I jxcore-log: 
03-17 08:40:29.528  4594  4804 I jxcore-log:       false
03-17 08:40:29.528  4594  4804 I jxcore-log: 
,03-17 08:40:29.528  4594  4804 I jxcore-log:     actual: |-
03-17 08:40:29.528  4594  4804 I jxcore-log: 
03-17 08:40:29.528  4594  4804 I jxcore-log:       'Operation timeout, state error: Discovery manager not started'
03-17 08:40:29.528  4594  4804 I jxcore-log: 
03-17 08:40:29.538  4594  4804 I jxcore-log:   ...
03-17 08:40:29.538  4594  4804 I jxcore-log: 
03-17 08:40:29.538  4594  4804 D BluetoothAdapter: 914685262: getState(). Returning 12
03-17 08:40:29.538  4594  4804 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: false
03-17 08:40:29.538  4594  4804 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-17 08:40:29.538  4594  4804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-17 08:40:29.538  4594  4804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
03-17 08:40:29.538  4594  4804 D BluetoothAdapter: 914685262: getState(). Returning 12
03-17 08:40:29.548  4594  4804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-17 08:40:29.548  4594  4804 D BluetoothAdapter: 914685262: getState(). Returning 12
03-17 08:40:29.548  4594  4804 D BluetoothAdapter: 914685262: getState(). Returning 12
,03-17 08:40:29.548  4594  4804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-17 08:40:29.548  4594  4804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-17 08:40:29.548  4594  4804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-17 08:40:29.548  4594  4804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-17 08:40:29.548  4594  4804 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-17 08:40:29.548  4594  4804 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-17 08:40:29.548  4594  4594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onScanFailed: Feature is not supported, error code is 4
03-17 08:40:29.548   921  1721 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
03-17 08:40:29.548  4594  4594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-17 08:40:29.548  4594  4594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-17 08:40:29.548  4594  4594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-17 08:40:29.548  4594  4594 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,03-17 08:40:29.558  4594  4804 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-17 08:40:29.558  4594  4804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-17 08:40:29.558  4594  4594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-17 08:40:29.558  4594  4594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onScannerFailed: 4
03-17 08:40:29.558  4594  4594 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-17 08:40:29.558  4594  4804 I io.jxcore.node.ConnectionHelper: start: OK
03-17 08:40:29.558  4594  4594 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-17 08:40:29.558  4594  4594 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-17 08:40:29.558  4594  4594 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-17 08:40:29.558  4594  4594 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-17 08:40:29.558  4594  4594 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-17 08:40:29.558  4594  4804 I jxcore-log: INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-17 08:40:29.558  4594  4804 I jxcore-log: 
,03-17 08:40:29.558  4594  4804 I jxcore-log: INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-17 08:40:29.558  4594  4804 I jxcore-log: 
,03-17 08:40:29.558  4594  4804 I jxcore-log: INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-17 08:40:29.558  4594  4804 I jxcore-log: 
,03-17 08:40:32.558  4594  4804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only,
03-17 08:40:32.558  4594  4804 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started,
,03-17 08:40:32.558  4594  4804 I jxcore-log: not ok 146 Can call startListeningForAdvertisements without error
03-17 08:40:32.558  4594  4804 I jxcore-log: 
03-17 08:40:32.568  4594  4804 I jxcore-log:   ---
,03-17 08:40:32.568  4594  4804 I jxcore-log: 
03-17 08:40:32.568  4594  4804 I jxcore-log:     operator: notOk
03-17 08:40:32.568  4594  4804 I jxcore-log: 
03-17 08:40:32.568  4594  4804 I jxcore-log:     expected: |-
03-17 08:40:32.568  4594  4804 I jxcore-log: 
03-17 08:40:32.568  4594  4804 I jxcore-log:       false
03-17 08:40:32.568  4594  4804 I jxcore-log: 
03-17 08:40:32.568  4594  4804 I jxcore-log:     actual: |-
03-17 08:40:32.568  4594  4804 I jxcore-log: 
03-17 08:40:32.568  4594  4804 I jxcore-log:       'Operation timeout, state error: Discovery manager not started'
03-17 08:40:32.568  4594  4804 I jxcore-log: 
03-17 08:40:32.568  4594  4804 I jxcore-log:   ...
03-17 08:40:32.568  4594  4804 I jxcore-log: 
,03-17 08:40:32.738  1346  1346 D wpa_supplicant: wlan0: BSS: Remove id 4 BSSID f0:f2:6d:22:99:3e SSID 'NG700_GUEST' due to wpa_bss_flush_by_age,
03-17 08:40:32.738  1346  1346 D wpa_supplicant: wlan0: BSS: Remove id 2 BSSID 00:1f:27:54:70:c1 SSID 'TEST_KTW01' due to wpa_bss_flush_by_age
03-17 08:40:32.738  1346  1346 D wpa_supplicant: wlan0: BSS: Remove id 1 BSSID 00:1f:27:54:70:c0 SSID 'ktwtestwifi' due to wpa_bss_flush_by_age
03-17 08:40:32.738  1346  1346 D wpa_supplicant: wlan0: BSS: Remove id 5 BSSID 00:1f:27:54:dd:ef SSID '\x00' due to wpa_bss_flush_by_age
03-17 08:40:32.738  1346  1346 D wpa_supplicant: wlan0: BSS: Remove id 6 BSSID 00:1f:27:54:dd:e0 SSID '\x00' due to wpa_bss_flush_by_age
03-17 08:40:32.738   921  1644 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 f0:f2:6d:22:99:3e]
03-17 08:40:32.738  1346  1346 D wpa_supplicant: wlan0: BSS: Remove id 3 BSSID 00:1f:27:54:dd:e3 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
03-17 08:40:32.738   921  1644 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-BSS-REMOVED 4 f0:f2:6d:22:99:3e
03-17 08:40:32.738  1346  1346 D wpa_supplicant: wlan0: BSS: Remove id 7 BSSID 00:1f:27:54:e0:43 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
03-17 08:40:32.738  1346  1346 D wpa_supplicant: wlan0: BSS: Remove id 8 BSSID 00:22:0d:46:1c:a3 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
03-17 08:40:32.738   921  1644 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 00:1f:27:54:70:c1]
03-17 08:40:32.738   921  1644 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 00:1f:27:54:70:c1
03-17 08:40:32.738   921  1644 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 00:1f:27:54:70:c0]
03-17 08:40:32.738   921  1644 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-BSS-REMOVED 1 00:1f:27:54:70:c0
03-17 08:40:32.738   921  1644 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 00:1f:27:54:dd:ef]
03-17 08:40:32.738   921  1644 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-BSS-REMOVED 5 00:1f:27:54:dd:ef
03-17 08:40:32.738   921  1644 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 00:1f:27:54:dd:e0]
03-17 08:40:32.738   921  1644 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-BSS-REMOVED 6 00:1f:27:54:dd:e0
03-17 08:40:32.738   921  1644 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 00:1f:27:54:dd:e3]
03-17 08:40:32.738   921  1644 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 00:1f:27:54:dd:e3
03-17 08:40:32.738   921  1644 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 00:1f:27:54:e0:43]
03-17 08:40:32.738   921  1644 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-BSS-REMOVED 7 00:1f:27:54:e0:43
03-17 08:40:32.738   921  1644 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 8 00:22:0d:46:1c:a3]
,03-17 08:40:32.738   921  1644 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-BSS-REMOVED 8 00:22:0d:46:1c:a3
,03-17 08:40:36.428   467   467 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,03-17 08:40:37.048   921  1157 D PMS     : acquireWL(a363b0a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 921 1000 null,
03-17 08:40:37.048   921  1157 I BatteryService: n_update end
03-17 08:40:37.048   921  1157 D PMS     : releaseWL(a363b0a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,03-17 08:40:37.048  1306  1306 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-17 08:40:37.048  1212  1212 D PowerUI : closing low battery warning: level=100
03-17 08:40:37.048  1212  1616 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
03-17 08:40:37.048   921   921 D NotificationService: plugged=true pluggin=true
03-17 08:40:37.048  3387  3524 D HeadsetStateMachine: Disconnected process message: 10, size: 0
03-17 08:40:37.058  1212  1212 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
03-17 08:40:37.048  1306  1306 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-17 08:40:37.058   921  1149 D WifiController: battery changed pluggedType: 2
03-17 08:40:37.048   921   921 D UsbnetService: BroadcastReceiver::onReceive+
03-17 08:40:37.058   921  1053 D HtcPowerSaver: updateBatteryInfo
03-17 08:40:37.048  1306  1306 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
03-17 08:40:37.058   921   921 D UsbnetService: onReceive BATTERY_CHANGED
03-17 08:40:37.058   921   921 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
03-17 08:40:37.058   921   921 D UsbnetService: BroadcastReceiver::onReceive-
03-17 08:40:37.058   921  1149 D WifiController: handleMessage: E msg.what=155652
03-17 08:40:37.058   921  1149 D WifiController: processMsg: DeviceActiveState
03-17 08:40:37.058   921  1149 D WifiController: processMsg: StaEnabledState
03-17 08:40:37.058   921  1149 D WifiController: processMsg: DefaultState
03-17 08:40:37.058   921  1149 D WifiController: handleMessage: X
,03-17 08:40:37.068   921   921 D PMS     : runPSCheck,
03-17 08:40:37.068   921   921 D HtcPowerSaver: Checking...
03-17 08:40:37.068   921   921 I HtcPowerSaver: >> updateStatus
,03-17 08:40:37.068   921   921 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
03-17 08:40:37.068   921   921 I HtcPowerSaver: << updateStatus
,03-17 08:40:37.098  1212  1212 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,03-17 08:41:21.438   467   467 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,03-17 08:41:31.438   467   467 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,03-17 08:41:37.208   921  2373 D PMS     : acquireWL(12d05f7b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 921 1000 null
03-17 08:41:37.208   921  2373 I BatteryService: n_update end
03-17 08:41:37.208   921  2373 D PMS     : releaseWL(12d05f7b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,03-17 08:41:37.208  1212  1616 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
03-17 08:41:37.208  1212  1212 D PowerUI : closing low battery warning: level=100
03-17 08:41:37.208  1306  1306 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-17 08:41:37.208   921  1053 D HtcPowerSaver: updateBatteryInfo
03-17 08:41:37.208  1306  1306 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-17 08:41:37.208   921   921 D NotificationService: plugged=true pluggin=true
03-17 08:41:37.208  1306  1306 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
03-17 08:41:37.208   921   921 D PMS     : runPSCheck
03-17 08:41:37.208   921   921 D UsbnetService: BroadcastReceiver::onReceive+
03-17 08:41:37.208   921   921 D HtcPowerSaver: Checking...
03-17 08:41:37.208   921   921 D UsbnetService: onReceive BATTERY_CHANGED
03-17 08:41:37.208   921   921 I HtcPowerSaver: >> updateStatus
03-17 08:41:37.208   921   921 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
03-17 08:41:37.218  1212  1212 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
03-17 08:41:37.208   921   921 D UsbnetService: BroadcastReceiver::onReceive-
03-17 08:41:37.218   921  1149 D WifiController: battery changed pluggedType: 2
03-17 08:41:37.208  3387  3524 D HeadsetStateMachine: Disconnected process message: 10, size: 0
03-17 08:41:37.208   921  1149 D WifiController: handleMessage: E msg.what=155652
03-17 08:41:37.208   921  1149 D WifiController: processMsg: DeviceActiveState
03-17 08:41:37.218   921  1149 D WifiController: processMsg: StaEnabledState
03-17 08:41:37.218   921  1149 D WifiController: processMsg: DefaultState
03-17 08:41:37.218   921  1149 D WifiController: handleMessage: X
,03-17 08:41:37.218   921   921 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
03-17 08:41:37.218   921   921 I HtcPowerSaver: << updateStatus
,03-17 08:41:37.258  1212  1212 I BatteryController: status:5 level:100 unsupport:false plugged:true
,03-17 08:41:46.448   467   467 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,03-17 08:41:47.368  1882  1882 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-17 08:41:47.418  1882  3574 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
03-17 08:41:47.418  1882  3574 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-17 08:41:47.418  1882  3574 I GLSUser : [GLSUser] Extracting token using key: Auth
03-17 08:41:47.418  1882  3574 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-17 08:41:47.428  1882  3574 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 08:41:47.488  1306  1328 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
03-17 08:41:47.488  1306  1328 D DotMatrix: [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,03-17 08:41:47.488  1212  1212 I RemoteViews: reapply : com.google.android.gms 2 40
,03-17 08:41:47.488  1882  3574 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-17 08:41:47.488  1882  3574 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268),
03-17 08:41:47.488  1882  3574 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-17 08:41:47.488  1882  3574 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
03-17 08:41:47.488  1882  3574 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
03-17 08:41:47.488  1882  3574 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
03-17 08:41:47.488  1882  3574 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:454)
,03-17 08:41:47.498  5884  5924 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
03-17 08:41:47.498  5884  5924 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
03-17 08:41:47.498  5884  5924 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
03-17 08:41:47.498  5884  5924 E PlayEventLogger: 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
03-17 08:41:47.498  5884  5924 E PlayEventLogger: 	,at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
03-17 08:41:47.498  5884  5924 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
03-17 08:41:47.498  5884  5924 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:454)
,03-17 08:41:47.548  5884  5924 W System  : Ignoring header User-Agent because its value was null.
,03-17 08:41:47.548  5884  5924 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
03-17 08:41:47.548  5884  5924 D libc    : [NET] android_getaddrinfofornet-, err=8
,03-17 08:41:47.548  5884  5924 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
03-17 08:41:47.548  5884  5924 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
,03-17 08:41:47.548  5884  5924 D libc    : [NET] android_getaddrinfo_proxy+
,03-17 08:41:47.548  5884  5924 D libc    : [NET] android_getaddrinfo_proxy get netid:0
,03-17 08:41:47.548   408  6588 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
03-17 08:41:47.548   408  6588 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
,03-17 08:41:47.638   408  6588 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS),
03-17 08:41:47.638   408  6588 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
03-17 08:41:47.638  5884  5924 D libc    : [NET] android_getaddrinfo_proxy-, success
,03-17 08:41:59.988   921  1137 D PMS     : acquireWL(7a1cfe5): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 921 1000 WorkSource{1000},
03-17 08:41:59.998   921  1137 V AlarmManager: sending alarm PendingIntent{4939042: PendingIntentRecord{3dd4b853 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=202648, Int=0
,03-17 08:42:00.028   921   921 D PMS     : releaseWL(7a1cfe5): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,03-17 08:42:00.028  1212  2488 D WeatherUtility: Weather sync is On,
03-17 08:42:00.038  1212  2488 W WeatherTimeKeeper: [refreshWeatherData] no weather data
,03-17 08:42:06.448   467   467 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,03-17 08:42:23.548   921  1137 D PMS     : acquireWL(25341d6b): PARTIAL_WAKE_LOCK  *alarm* 0x1 921 1000 WorkSource{10109},
,03-17 08:42:23.548   921  1137 V AlarmManager: sending alarm PendingIntent{23e950c8: PendingIntentRecord{23a48561 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1458200482658, Int=0
,03-17 08:42:23.548   921  1137 V AlarmManager: sending alarm PendingIntent{17b68886: PendingIntentRecord{13f52547 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1458200543550, Int=1800000,
,03-17 08:42:23.558   921  1718 D PMS     : acquireWL(ca6b174): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4407 10024 WorkSource{10024 com.google.android.gms}
,03-17 08:42:23.568   921   921 D PMS     : releaseWL(25341d6b): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,03-17 08:42:23.568   921  1716 D PMS     : acquireWL(3e62a712): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4407 10024 WorkSource{10024 com.google.android.gms},
03-17 08:42:23.578   921  1514 D PMS     : releaseWL(ca6b174): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
,03-17 08:42:23.598  4407  6591 I EventLogService: Aggregate from 1458200222088 (log), 1458198743508 (data)
,03-17 08:42:23.618   921  4355 I DropBoxManagerService: Usage (1282) > Quota (1280)
,03-17 08:42:23.678   921  1712 D PMS     : releaseWL(3e62a712): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms}
,03-17 08:42:31.458   467   467 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,03-17 08:42:37.368   921  1720 D PMS     : acquireWL(1240225e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 921 1000 null
,03-17 08:42:37.368   921  1720 I BatteryService: n_update end
03-17 08:42:37.368   921  1720 D PMS     : releaseWL(1240225e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,03-17 08:42:37.378  1306  1306 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-17 08:42:37.378   921  1053 D HtcPowerSaver: updateBatteryInfo
03-17 08:42:37.378  1306  1306 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-17 08:42:37.378  1212  1212 D PowerUI : closing low battery warning: level=100
03-17 08:42:37.378  1306  1306 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
03-17 08:42:37.378   921   921 D NotificationService: plugged=true pluggin=true
03-17 08:42:37.378   921   921 D UsbnetService: BroadcastReceiver::onReceive+
03-17 08:42:37.378   921   921 D PMS     : runPSCheck
03-17 08:42:37.378   921   921 D UsbnetService: onReceive BATTERY_CHANGED
03-17 08:42:37.378   921   921 D HtcPowerSaver: Checking...
03-17 08:42:37.378   921   921 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
03-17 08:42:37.378   921   921 I HtcPowerSaver: >> updateStatus
03-17 08:42:37.378   921   921 D UsbnetService: BroadcastReceiver::onReceive-
,03-17 08:42:37.378   921  1149 D WifiController: battery changed pluggedType: 2
03-17 08:42:37.378   921  1149 D WifiController: handleMessage: E msg.what=155652
03-17 08:42:37.378  1212  1212 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
03-17 08:42:37.378   921  1149 D WifiController: processMsg: DeviceActiveState
03-17 08:42:37.378   921  1149 D WifiController: processMsg: StaEnabledState
03-17 08:42:37.378   921  1149 D WifiController: processMsg: DefaultState
03-17 08:42:37.378   921  1149 D WifiController: handleMessage: X
03-17 08:42:37.378  3387  3524 D HeadsetStateMachine: Disconnected process message: 10, size: 0
03-17 08:42:37.378  1212  1616 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
03-17 08:42:37.388   921   921 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
,03-17 08:42:37.388   921   921 I HtcPowerSaver: << updateStatus
,03-17 08:42:37.428  1212  1212 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,03-17 08:43:21.458   467   467 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,03-17 08:43:31.468   467   467 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,03-17 08:43:37.528   921  1401 D PMS     : acquireWL(27b763f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 921 1000 null
03-17 08:43:37.528   921  1401 I BatteryService: n_update end
03-17 08:43:37.528   921  1401 D PMS     : releaseWL(27b763f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
03-17 08:43:37.528   921  1053 D HtcPowerSaver: updateBatteryInfo
03-17 08:43:37.528   921   921 D PMS     : runPSCheck
03-17 08:43:37.528   921   921 D HtcPowerSaver: Checking...
03-17 08:43:37.528   921   921 I HtcPowerSaver: >> updateStatus
03-17 08:43:37.528  1212  1212 D PowerUI : closing low battery warning: level=100
03-17 08:43:37.538  1306  1306 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-17 08:43:37.538  1306  1306 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-17 08:43:37.538  1306  1306 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
03-17 08:43:37.538  1212  1212 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
03-17 08:43:37.538  1212  1616 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
03-17 08:43:37.538   921   921 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
03-17 08:43:37.538   921   921 D UsbnetService: BroadcastReceiver::onReceive+
03-17 08:43:37.538   921   921 I HtcPowerSaver: << updateStatus
03-17 08:43:37.538   921   921 D UsbnetService: onReceive BATTERY_CHANGED
03-17 08:43:37.538   921   921 D NotificationService: plugged=true pluggin=true
03-17 08:43:37.538   921   921 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
03-17 08:43:37.538   921  1149 D WifiController: battery changed pluggedType: 2
03-17 08:43:37.538   921   921 D UsbnetService: BroadcastReceiver::onReceive-
03-17 08:43:37.538   921  1149 D WifiController: handleMessage: E msg.what=155652
03-17 08:43:37.538   921  1149 D WifiController: processMsg: DeviceActiveState
03-17 08:43:37.538   921  1149 D WifiController: processMsg: StaEnabledState
03-17 08:43:37.538   921  1149 D WifiController: processMsg: DefaultState
03-17 08:43:37.538   921  1149 D WifiController: handleMessage: X
03-17 08:43:37.538  3387  3524 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-17 08:43:37.588  1212  1212 I BatteryController: status:5 level:100 unsupport:false plugged:true
,03-17 08:43:46.468   467   467 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,03-17 08:44:06.468   467   467 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,03-17 08:44:31.478   467   467 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,03-17 08:44:37.688   921  1718 D PMS     : acquireWL(2052bb0c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 921 1000 null
03-17 08:44:37.698  1306  1306 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-17 08:44:37.698   921  1718 I BatteryService: n_update end
03-17 08:44:37.698  1306  1306 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-17 08:44:37.698   921  1718 D PMS     : releaseWL(2052bb0c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
03-17 08:44:37.698  1306  1306 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
03-17 08:44:37.698   921  1053 D HtcPowerSaver: updateBatteryInfo
03-17 08:44:37.698   921   921 D UsbnetService: BroadcastReceiver::onReceive+
03-17 08:44:37.698   921   921 D NotificationService: plugged=true pluggin=true
03-17 08:44:37.698   921   921 D UsbnetService: onReceive BATTERY_CHANGED
03-17 08:44:37.698   921   921 D PMS     : runPSCheck
03-17 08:44:37.698   921   921 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
03-17 08:44:37.698   921   921 D HtcPowerSaver: Checking...
03-17 08:44:37.698   921   921 D UsbnetService: BroadcastReceiver::onReceive-
03-17 08:44:37.698   921   921 I HtcPowerSaver: >> updateStatus
03-17 08:44:37.698   921  1149 D WifiController: handleMessage: E msg.what=155652
03-17 08:44:37.698   921  1149 D WifiController: battery changed pluggedType: 2
03-17 08:44:37.698   921  1149 D WifiController: processMsg: DeviceActiveState
03-17 08:44:37.698  1212  1212 D PowerUI : closing low battery warning: level=100
03-17 08:44:37.698   921  1149 D WifiController: processMsg: StaEnabledState
03-17 08:44:37.698  1212  1212 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
03-17 08:44:37.698   921  1149 D WifiController: processMsg: DefaultState
03-17 08:44:37.698   921  1149 D WifiController: handleMessage: X
03-17 08:44:37.698  3387  3524 D HeadsetStateMachine: Disconnected process message: 10, size: 0
03-17 08:44:37.698  1212  1616 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
,03-17 08:44:37.698   921   921 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
03-17 08:44:37.698   921   921 I HtcPowerSaver: << updateStatus
,03-17 08:44:37.748  1212  1212 I BatteryController: status:5 level:100 unsupport:false plugged:true
,03-17 08:45:37.848   921   951 D PMS     : acquireWL(2f7f7c55): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 921 1000 null
03-17 08:45:37.848   921   951 I BatteryService: n_update end
03-17 08:45:37.848   921   951 D PMS     : releaseWL(2f7f7c55): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,03-17 08:45:37.858  1212  1616 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
03-17 08:45:37.858   921  1053 D HtcPowerSaver: updateBatteryInfo
03-17 08:45:37.858  3387  3524 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-17 08:45:37.858  1212  1212 D PowerUI : closing low battery warning: level=100
03-17 08:45:37.858  1306  1306 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-17 08:45:37.858   921   921 D NotificationService: plugged=true pluggin=true
,03-17 08:45:37.858  1306  1306 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-17 08:45:37.858   921   921 D PMS     : runPSCheck
03-17 08:45:37.858  1306  1306 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
03-17 08:45:37.858   921   921 D HtcPowerSaver: Checking...
03-17 08:45:37.858   921   921 D UsbnetService: BroadcastReceiver::onReceive+
03-17 08:45:37.858   921   921 I HtcPowerSaver: >> updateStatus
03-17 08:45:37.858   921   921 D UsbnetService: onReceive BATTERY_CHANGED
03-17 08:45:37.858   921  1149 D WifiController: battery changed pluggedType: 2
03-17 08:45:37.858   921   921 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
03-17 08:45:37.858  1212  1212 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
03-17 08:45:37.858   921   921 D UsbnetService: BroadcastReceiver::onReceive-
03-17 08:45:37.868   921   921 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
03-17 08:45:37.858   921  1149 D WifiController: handleMessage: E msg.what=155652
03-17 08:45:37.868   921   921 I HtcPowerSaver: << updateStatus
03-17 08:45:37.858   921  1149 D WifiController: processMsg: DeviceActiveState
03-17 08:45:37.858   921  1149 D WifiController: processMsg: StaEnabledState
03-17 08:45:37.858   921  1149 D WifiController: processMsg: DefaultState
,03-17 08:45:37.858   921  1149 D WifiController: handleMessage: X
,03-17 08:45:37.908  1212  1212 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,03-17 08:45:44.168   386   397 E PNP_UPDATERD: inotify_add_watch failed. (No such file or directory),
,03-17 08:46:05.638  1433  1703 D ContactMessageStore: MSG_CHECK_DELETION >>
03-17 08:46:05.638  1433  1703 D ContactMessageStore: mDeleteTask = null, bDeleting = false
03-17 08:46:05.638  1433  1703 D AccFlag : sku_id=118
03-17 08:46:05.638  1433  1703 D ContactMessageStore: MSG_CHECK_DELETION <<
,03-17 08:46:05.638  1433  6593 D ContactMessageStore: start background delete task...
,03-17 08:46:05.638  1433  6593 D ContactMessageStore: size: 0 , 0
,03-17 08:46:05.638  1433  6593 D ContactMessageStore: Background delete complete
,03-17 08:46:37.998   921  1515 D PMS     : acquireWL(fe8066a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 921 1000 null,
03-17 08:46:37.998   921  1515 I BatteryService: n_update end
03-17 08:46:37.998   921  1515 D PMS     : releaseWL(fe8066a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
03-17 08:46:38.008   921  1053 D HtcPowerSaver: updateBatteryInfo
03-17 08:46:38.008  1212  1616 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
,03-17 08:46:38.008  1212  1212 D PowerUI : closing low battery warning: level=100
03-17 08:46:38.008  1306  1306 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-17 08:46:38.008  1212  1212 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
03-17 08:46:38.008  1306  1306 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-17 08:46:38.008   921   921 D NotificationService: plugged=true pluggin=true
03-17 08:46:38.008   921   921 D UsbnetService: BroadcastReceiver::onReceive+
03-17 08:46:38.008   921   921 D PMS     : runPSCheck
03-17 08:46:38.008  1306  1306 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
03-17 08:46:38.008   921   921 D HtcPowerSaver: Checking...
03-17 08:46:38.008   921   921 D UsbnetService: onReceive BATTERY_CHANGED
03-17 08:46:38.008   921   921 I HtcPowerSaver: >> updateStatus
03-17 08:46:38.008   921   921 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
03-17 08:46:38.008   921  1149 D WifiController: battery changed pluggedType: 2
03-17 08:46:38.008   921   921 D UsbnetService: BroadcastReceiver::onReceive-
,03-17 08:46:38.008  3387  3524 D HeadsetStateMachine: Disconnected process message: 10, size: 0,
03-17 08:46:38.008   921  1149 D WifiController: handleMessage: E msg.what=155652
03-17 08:46:38.008   921   921 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
03-17 08:46:38.008   921  1149 D WifiController: processMsg: DeviceActiveState
03-17 08:46:38.008   921   921 I HtcPowerSaver: << updateStatus
03-17 08:46:38.008   921  1149 D WifiController: processMsg: StaEnabledState
03-17 08:46:38.008   921  1149 D WifiController: processMsg: DefaultState
03-17 08:46:38.008   921  1149 D WifiController: handleMessage: X
,03-17 08:46:38.058  1212  1212 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,03-17 08:47:38.178   921  1157 D PMS     : acquireWL(17bb375b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 921 1000 null
03-17 08:47:38.178   921  1157 I BatteryService: n_update end
,03-17 08:47:38.178   921  1157 D PMS     : releaseWL(17bb375b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,03-17 08:47:38.178   921   921 D UsbnetService: BroadcastReceiver::onReceive+
03-17 08:47:38.178   921  1053 D HtcPowerSaver: updateBatteryInfo
03-17 08:47:38.178   921   921 D UsbnetService: onReceive BATTERY_CHANGED
03-17 08:47:38.178   921   921 D NotificationService: plugged=true pluggin=true
03-17 08:47:38.178   921   921 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
03-17 08:47:38.178   921   921 D PMS     : runPSCheck
03-17 08:47:38.178   921   921 D UsbnetService: BroadcastReceiver::onReceive-
03-17 08:47:38.178   921   921 D HtcPowerSaver: Checking...
03-17 08:47:38.178  1306  1306 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-17 08:47:38.178   921   921 I HtcPowerSaver: >> updateStatus
03-17 08:47:38.188  1306  1306 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-17 08:47:38.188   921  1149 D WifiController: battery changed pluggedType: 2
,03-17 08:47:38.188   921  1149 D WifiController: handleMessage: E msg.what=155652
03-17 08:47:38.188  1212  1212 D PowerUI : closing low battery warning: level=100
03-17 08:47:38.188   921  1149 D WifiController: processMsg: DeviceActiveState
03-17 08:47:38.188  1212  1212 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
03-17 08:47:38.188   921  1149 D WifiController: processMsg: StaEnabledState
03-17 08:47:38.188   921   921 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
03-17 08:47:38.188   921  1149 D WifiController: processMsg: DefaultState
03-17 08:47:38.188   921   921 I HtcPowerSaver: << updateStatus
03-17 08:47:38.188   921  1149 D WifiController: handleMessage: X
03-17 08:47:38.188  1306  1306 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
03-17 08:47:38.188  3387  3524 D HeadsetStateMachine: Disconnected process message: 10, size: 0
03-17 08:47:38.188  1212  1616 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
,03-17 08:47:38.238  1212  1212 I BatteryController: status:5 level:100 unsupport:false plugged:true
,03-17 08:48:38.328   921  2373 D PMS     : acquireWL(10f67bf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 921 1000 null
03-17 08:48:38.328   921  2373 I BatteryService: n_update end
03-17 08:48:38.328   921  2373 D PMS     : releaseWL(10f67bf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,03-17 08:48:38.328  1306  1306 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-17 08:48:38.328  1306  1306 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-17 08:48:38.328  1306  1306 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
03-17 08:48:38.328  1212  1616 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
03-17 08:48:38.328  3387  3524 D HeadsetStateMachine: Disconnected process message: 10, size: 0
03-17 08:48:38.328   921   921 D UsbnetService: BroadcastReceiver::onReceive+
03-17 08:48:38.328   921   921 D NotificationService: plugged=true pluggin=true
03-17 08:48:38.328   921   921 D UsbnetService: onReceive BATTERY_CHANGED
03-17 08:48:38.328  1212  1212 D PowerUI : closing low battery warning: level=100
03-17 08:48:38.328   921   921 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
03-17 08:48:38.328   921  1149 D WifiController: battery changed pluggedType: 2
03-17 08:48:38.328   921   921 D UsbnetService: BroadcastReceiver::onReceive-
03-17 08:48:38.328   921  1053 D HtcPowerSaver: updateBatteryInfo
03-17 08:48:38.328   921  1149 D WifiController: handleMessage: E msg.what=155652
03-17 08:48:38.328   921   921 D PMS     : runPSCheck
03-17 08:48:38.328   921  1149 D WifiController: processMsg: DeviceActiveState
03-17 08:48:38.328   921   921 D HtcPowerSaver: Checking...
03-17 08:48:38.328   921  1149 D WifiController: processMsg: StaEnabledState
03-17 08:48:38.328   921   921 I HtcPowerSaver: >> updateStatus
03-17 08:48:38.328   921  1149 D WifiController: processMsg: DefaultState
03-17 08:48:38.328  1212  1212 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
03-17 08:48:38.328   921  1149 D WifiController: handleMessage: X
,03-17 08:48:38.338   921   921 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
03-17 08:48:38.338   921   921 I HtcPowerSaver: << updateStatus
,03-17 08:48:38.378  1212  1212 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,03-17 08:49:38.488   921   950 D PMS     : acquireWL(2c8888d1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 921 1000 null
,03-17 08:49:38.488   921   950 I BatteryService: n_update end
03-17 08:49:38.488   921   950 D PMS     : releaseWL(2c8888d1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,03-17 08:51:22.708   921  1137 D PMS     : acquireWL(32781f36): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 921 1000 WorkSource{1000}
03-17 08:51:22.708   921  1137 V AlarmManager: sending alarm PendingIntent{4939042: PendingIntentRecord{3dd4b853 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=442649, Int=0
,03-17 08:51:22.708   921  1137 V AlarmManager: sending alarm PendingIntent{306bee37: PendingIntentRecord{36135fa4 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=945365, Int=0
,03-17 08:51:22.748  3387  3611 I bt-btm  : Received oneshot timer event complete
03-17 08:51:22.748   921  1515 D PMS     : acquireWL(a3be10d): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3387 1002 null
03-17 08:51:22.748  3387  3611 I bt-btm  : btm_ble_timeout
03-17 08:51:22.748   921   921 D PMS     : releaseWL(32781f36): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
03-17 08:51:22.748  3387  3611 I bt-btm  : btm_gen_resolvable_private_addr
03-17 08:51:22.758  1212  2488 D WeatherUtility: Weather sync is On
03-17 08:51:22.758  1212  2488 W WeatherTimeKeeper: [refreshWeatherData] no weather data
,03-17 08:51:22.758  3387  3611 D bt-btm  : btm_ble_rand_enc_complete,
03-17 08:51:22.758  3387  3611 I bt-btm  : btm_gen_resolve_paddr_low
03-17 08:51:22.758  3387  3611 D bt-smp  : smp_encrypt_data
03-17 08:51:22.758  3387  3611 W bt-smp  : Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
03-17 08:51:22.758  3387  3611 W bt-smp  : Plain text(LSB ~ MSB) = 60 ef 45 00 00 00 00 00 00 00 00 00 00 00 00 00 
03-17 08:51:22.758  3387  3611 W bt-smp  : Encrypted text(LSB ~ MSB) = 23 aa 05 b2 53 bf 4c e3 a9 76 6c 2e ee b5 1b 52 
03-17 08:51:22.758  3387  3611 I bt-btm  : btm_gen_resolve_paddr_cmpl,
03-17 08:51:22.758  3387  3611 W bt-btm  : Stopping oneshot timer
03-17 08:51:22.758  3387  3611 D bt-btm  : Starting oneshot timer type:103 timeout:900s
,03-17 08:51:23.758   921  1401 D PMS     : releaseWL(a3be10d): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,03-17 08:51:38.808   921  1721 D PMS     : acquireWL(371ef8c2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 921 1000 null
03-17 08:51:38.808   921  1721 I BatteryService: n_update end
03-17 08:51:38.808   921  1721 D PMS     : releaseWL(371ef8c2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,03-17 08:51:38.808   921  1053 D HtcPowerSaver: updateBatteryInfo
,03-17 08:51:38.808   921   921 D UsbnetService: BroadcastReceiver::onReceive+
03-17 08:51:38.808   921   921 D NotificationService: plugged=true pluggin=true
03-17 08:51:38.808   921   921 D UsbnetService: onReceive BATTERY_CHANGED
03-17 08:51:38.808   921   921 D PMS     : runPSCheck
03-17 08:51:38.808   921   921 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
03-17 08:51:38.808   921   921 D HtcPowerSaver: Checking...
03-17 08:51:38.808   921   921 D UsbnetService: BroadcastReceiver::onReceive-
03-17 08:51:38.808   921   921 I HtcPowerSaver: >> updateStatus
03-17 08:51:38.818   921  1149 D WifiController: handleMessage: E msg.what=155652
03-17 08:51:38.818   921   921 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1),
03-17 08:51:38.818  1306  1306 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-17 08:51:38.818   921   921 I HtcPowerSaver: << updateStatus
03-17 08:51:38.818  1306  1306 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-17 08:51:38.818  1212  1212 D PowerUI : closing low battery warning: level=100
03-17 08:51:38.818  1306  1306 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
03-17 08:51:38.818   921  1149 D WifiController: battery changed pluggedType: 2
03-17 08:51:38.818  1212  1616 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
03-17 08:51:38.818  1212  1212 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
03-17 08:51:38.818   921  1149 D WifiController: processMsg: DeviceActiveState
03-17 08:51:38.818  3387  3524 D HeadsetStateMachine: Disconnected process message: 10, size: 0
03-17 08:51:38.818   921  1149 D WifiController: processMsg: StaEnabledState
03-17 08:51:38.818   921  1149 D WifiController: processMsg: DefaultState
03-17 08:51:38.818   921  1149 D WifiController: handleMessage: X
,03-17 08:51:38.868  1212  1212 I BatteryController: status:5 level:100 unsupport:false plugged:true
,03-17 08:51:44.748   921  1137 D PMS     : acquireWL(100736d3): PARTIAL_WAKE_LOCK  *alarm* 0x1 921 1000 WorkSource{10024},
03-17 08:51:44.748   921  1137 V AlarmManager: sending alarm PendingIntent{3ff8d210: PendingIntentRecord{15528109 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=933416, Int=0
,03-17 08:51:44.748   921  4355 D PMS     : acquireWL(d67df0e): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1882 10024 WorkSource{10024 com.google.android.gms}
03-17 08:51:44.748   921  1137 V AlarmManager: sending alarm PendingIntent{d5bd37c: PendingIntentRecord{38710405 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=804677, Int=0
,03-17 08:51:44.758   921  1515 D PMS     : releaseWL(d67df0e): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,03-17 08:51:44.778   921  1137 I ActivityManager: Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6595 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,03-17 08:51:44.778   921  1137 V AlarmManager: sending alarm PendingIntent{2e046d2f: PendingIntentRecord{1280ff3c com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1458200995602, Int=0
03-17 08:51:44.778   921  1137 V AlarmManager: sending alarm PendingIntent{131924c5: PendingIntentRecord{218e9ce4 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1458201104751, Int=0
,03-17 08:51:44.788   921  1719 D PMS     : acquireWL(46de1a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1882 10024 WorkSource{10024 com.google.android.gms}
,03-17 08:51:44.798  6512  6512 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,03-17 08:51:44.808   921   921 D PMS     : releaseWL(100736d3): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,03-17 08:51:44.808  6512  6611 D PowerUsageList:PowerUsageHelper: MY_DEBUG = false,
,03-17 08:51:44.818  6512  6611 D PowerUsageService: repeat time = 1458202004827
,03-17 08:51:44.848   921  4355 D PMS     : acquireWL(16ec4841): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1882 10024 WorkSource{10024 com.google.android.gms},
,03-17 08:51:44.858  1882  2810 D GCM     : Message class com.google.f.a.a.i,
03-17 08:51:44.858   921  1710 D PMS     : acquireWL(23e4c1e6): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1882 10024 WorkSource{10024 com.google.android.gms}
,03-17 08:51:44.868   921  1157 D PMS     : releaseWL(23e4c1e6): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,03-17 08:51:44.868   921   950 D PMS     : releaseWL(46de1a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,03-17 08:51:44.888  1882  6617 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory,
,03-17 08:51:44.908  1882  6617 W Uploader: No account for auth token provided,
,03-17 08:51:44.928  1882  6617 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
03-17 08:51:44.928  1882  6617 D libc    : [NET] android_getaddrinfofornet-, err=8
03-17 08:51:44.928  1882  6617 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,03-17 08:51:44.928  1882  6617 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
03-17 08:51:44.928  1882  6617 D libc    : [NET] android_getaddrinfo_proxy+
03-17 08:51:44.928  1882  6617 D libc    : [NET] android_getaddrinfo_proxy get netid:0
03-17 08:51:44.928   408  6619 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
03-17 08:51:44.928   408  6619 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
,03-17 08:51:44.958  6512  6611 I PowerUsageList:PowerUsageHelper: PowerProfile::POWER_SCREEN_FULL = 154.8,
,03-17 08:51:44.968  6512  6611 D PowerUsageList:BatterySipperExt: gen(), null == sipper.uidObj, userId = 0,
,03-17 08:51:44.978  6512  6611 D PowerUsageList:BatterySipperExt: gen(), null == sipper.uidObj, userId = 0
,03-17 08:51:44.978  6512  6611 D PowerUsageList:BatterySipperExt: gen(), null == sipper.uidObj, userId = 0
,03-17 08:51:45.008  6620  6620 E cutils-trace: Error opening trace file: Permission denied (13),
03-17 08:51:45.008  6620  6620 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,03-17 08:51:45.008  6620  6620 I dex2oat : dex2oat: override thread count:4
,03-17 08:51:45.018  6512  6611 D PowerUsageService: calcPower(), no data,
,03-17 08:51:45.058   408  6619 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS),
03-17 08:51:45.058   408  6619 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
03-17 08:51:45.058  1882  6617 D libc    : [NET] android_getaddrinfo_proxy-, success
,03-17 08:51:45.448  1882  6617 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
03-17 08:51:45.448  1882  6617 D libc    : [NET] android_getaddrinfofornet-, err=8
03-17 08:51:45.448  1882  6617 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
03-17 08:51:45.448  1882  6617 D libc    : [NET] android_getaddrinfofornet-, err=8
,03-17 08:51:45.678  1882  6617 W Uploader: No account for auth token provided
,03-17 08:51:45.698  6620  6620 I dex2oat : dex2oat took 688.714ms (threads: 4),
,03-17 08:51:45.738  6595  6595 I PushClient: ApplicationMonitor {3421ce6f}: logBasicAppInfo(): PackageName:             com.htc.cs.pns,
,03-17 08:51:45.738  6595  6595 I PushClient: ApplicationMonitor {3421ce6f}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns,
,03-17 08:51:45.738  6595  6595 I PushClient: ApplicationMonitor {3421ce6f}: logBasicAppInfo(): VersionName:             1.2.853019
,03-17 08:51:45.738  6595  6595 I PushClient: ApplicationMonitor {3421ce6f}: logBasicAppInfo(): VersionCode:             148001224,
03-17 08:51:45.748  6595  6595 I PushClient: ApplicationMonitor {3421ce6f}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
03-17 08:51:45.748  6595  6595 I PushClient: ApplicationMonitor {3421ce6f}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files,
03-17 08:51:45.748  6595  6595 I PushClient: ApplicationMonitor {3421ce6f}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
03-17 08:51:45.748  6595  6595 I PushClient: ApplicationMonitor {3421ce6f}: logBasicAppInfo(): Htc_DEBUG_flag:          false
,03-17 08:51:45.748  6595  6595 I PushClient: ApplicationMonitor {3421ce6f}: logBasicAppInfo(): BuildConfig.DEBUG:       false,
,03-17 08:51:45.758  6595  6626 I PushClient: PnsModel {3684fd4e}: update(): Update registration caused by: alarm,
,03-17 08:51:45.778  6595  6626 I PushClient: PnsConfigModel {25e2b2bd}: <init>(): Use dm-client for provisioning.
,03-17 08:51:45.788  1882  6617 W Uploader: No account for auth token provided,
,03-17 08:51:45.808  6595  6626 W System.err: SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
03-17 08:51:45.808  6595  6626 W System.err: SLF4J: Defaulting to no-operation (NOP) logger implementation
03-17 08:51:45.808  6595  6626 W System.err: SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,03-17 08:51:45.838  6595  6626 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 ,
,03-17 08:51:45.868   921  1712 I ActivityManager: Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6628 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a,
,03-17 08:51:45.918  1882  6617 W Uploader: No account for auth token provided,
,03-17 08:51:45.928  6628  6628 I DeviceManagement: DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6628 dbg=false s=true,
,03-17 08:51:46.098   921  1721 I art     : Explicit concurrent mark sweep GC freed 55137(2MB) AllocSpace objects, 8(1080KB) LOS objects, 33% free, 18MB/28MB, paused 1.857ms total 161.418ms
,03-17 08:51:46.098  6628  6648 I DeviceManagement: ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL]
,03-17 08:51:46.108  6628  6648 I DeviceManagement: ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns],
,03-17 08:51:46.108  6628  6651 I DeviceManagement: WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]],
,03-17 08:51:46.118  6628  6628 I DeviceManagement: WorkflowService: Starting workflow service
,03-17 08:51:46.118  6628  6652 I DeviceManagement: WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@3684fd4e] args=[Bundle[mParcelledData.dataSize=88]]
,03-17 08:51:46.118  6628  6652 I DeviceManagement: ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,03-17 08:51:46.128  6628  6652 I DeviceManagement: ModelRegistry: Loading model meta data from resources...
,03-17 08:51:46.158  6628  6652 I DeviceManagement: ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,03-17 08:51:46.158  1882  6617 W Uploader: No account for auth token provided
,03-17 08:51:46.168  6628  6653 I DeviceManagement: SessionStateController: Checking invariants...
,03-17 08:51:46.298  1882  6617 W Uploader:  no longer exists, so no auth token.,
,03-17 08:51:46.308  6628  6653 I DeviceManagement: ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
,03-17 08:51:46.378  6628  6652 I DeviceManagement: SessionStateController: Checking invariants...,
,03-17 08:51:46.438  6628  6652 I DeviceManagement: ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,03-17 08:51:46.448  6628  6652 I DeviceManagement: WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@3684fd4e]
03-17 08:51:46.448  1882  6617 W Uploader: No account for auth token provided
,03-17 08:51:46.448  6628  6628 I DeviceManagement: WorkflowService: Stopping workflow service,
,03-17 08:51:46.458   921  2373 D Process : killProcessQuiet, pid=6266
03-17 08:51:46.458   921  2373 I ActivityManager: Killing 6266:com.htc.calendar/u0a10 (adj 15): empty #17
,03-17 08:51:46.458   921  2373 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-17 08:51:46.538   921   950 I ActivityManager: Recipient 6266,
,03-17 08:51:46.548  6595  6626 I PushClient: PnsModel {3684fd4e}: update(): The registration record has not expired yet. No need to update.,
,03-17 08:51:46.568   921  1157 I ActivityManager: Killing 5660:com.htc.mediamanager/u0a28 (adj 15): empty #17
,03-17 08:51:46.568   921  1157 D Process : killProcessQuiet, pid=5660
03-17 08:51:46.568   921  1157 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-17 08:51:46.688   921  4355 I ActivityManager: Recipient 5660
,03-17 08:51:46.828  1882  6617 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
03-17 08:51:46.828  1882  6617 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-17 08:51:46.828  1882  6617 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-17 08:51:46.828  1882  6617 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
03-17 08:51:46.838  1882  6617 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 08:51:46.888  1882  6617 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.,
03-17 08:51:46.888  1882  6617 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-17 08:51:46.888  1882  6617 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-17 08:51:46.888  1882  6617 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-17 08:51:46.888  1882  6617 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-17 08:51:46.888  1882  6617 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-17 08:51:46.888  1882  6617 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-17 08:51:46.888  1882  6617 E Uploader: ,	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-17 08:51:46.888  1882  6617 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-17 08:51:46.888  1882  6617 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-17 08:51:46.888  1882  6617 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-17 08:51:46.888  1882  6617 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-17 08:51:46.888  1882  6617 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-17 08:51:46.898  1306  1715 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
03-17 08:51:46.898  1306  1715 D DotMatrix: [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
03-17 08:51:46.898  1212  1212 I RemoteViews: reapply : com.google.android.gms 4 40
,03-17 08:51:46.988   921  1157 D PMS     : releaseWL(16ec4841): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
03-17 08:51:46.988   921  1718 D PMS     : acquireWL(10602f0f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1882 10024 WorkSource{10024 com.google.android.gms}
,03-17 08:51:47.018   921  1719 D PMS     : releaseWL(10602f0f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,03-17 08:51:47.018   921   950 D PMS     : acquireWL(3be4cb9c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1882 10024 WorkSource{10024 com.google.android.gms}
,03-17 08:51:47.038   921  1710 D PMS     : releaseWL(3be4cb9c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,03-17 08:52:36.318   921  1137 D PMS     : acquireWL(d1c69a5): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 921 1000 WorkSource{1000}
,03-17 08:52:36.318   921  1137 V AlarmManager: sending alarm PendingIntent{4939042: PendingIntentRecord{3dd4b853 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=982648, Int=0,
03-17 08:52:36.318   921  1137 V AlarmManager: sending alarm PendingIntent{17e7717a: PendingIntentRecord{307aad2b com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1458201156325, Int=0
,03-17 08:52:36.328  6512  6512 D SmartSyncUtils: isEpsOn(), nState = 0
,03-17 08:52:36.338   921  1710 D PMS     : acquireWL(1f410588): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6512 1000 null,
,03-17 08:52:36.348  1212  2488 D WeatherUtility: Weather sync is On
03-17 08:52:36.348  1212  2488 W WeatherTimeKeeper: [refreshWeatherData] no weather data
03-17 08:52:36.348   921   921 D PMS     : releaseWL(d1c69a5): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,03-17 08:52:36.348  6512  6655 D SmartSyncScreenOnOffTimeReceiver: [updateNmRange] bManual = false,
,03-17 08:52:36.358  6512  6655 D SmartSyncScreenOnOffTimeReceiver: [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true,
,03-17 08:52:36.358  6512  6655 D SmartSyncScreenOnOffTimeReceiver: AlarmOnTime = -1,
,03-17 08:52:36.358  6512  6655 D SmartSyncScreenOnOffTimeReceiver: SettingOnTime = 1458280800000, randomSettingOnTime = 1458277705000
,03-17 08:52:36.358  6512  6655 D SmartSyncScreenOnOffTimeReceiver: SettingOffTime = 1458259200000, randomSettingOffTime = 1458264394000
,03-17 08:52:36.358  6512  6655 D SmartSyncScreenOnOffTimeReceiver: bDayMode = false
,03-17 08:52:36.368  6512  6655 D SmartSyncScreenOnOffTimeReceiver: bNightMode = true
03-17 08:52:36.368  6512  6655 D SmartSyncScreenOnOffTimeReceiver: bNightModeTurnOffOnce = false
,03-17 08:52:36.368   921  1719 D PMS     : releaseWL(1f410588): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null,
,03-17 08:52:38.958   921  1514 D PMS     : acquireWL(2d8efb21): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 921 1000 null,
03-17 08:52:38.958   921  1514 I BatteryService: n_update end
03-17 08:52:38.958   921  1514 D PMS     : releaseWL(2d8efb21): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
03-17 08:52:38.968  1212  1616 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
03-17 08:52:38.968   921  1053 D HtcPowerSaver: updateBatteryInfo
03-17 08:52:38.968   921   921 D UsbnetService: BroadcastReceiver::onReceive+
,03-17 08:52:38.968   921   921 D NotificationService: plugged=true pluggin=true,
03-17 08:52:38.968   921   921 D UsbnetService: onReceive BATTERY_CHANGED
,03-17 08:52:38.968   921   921 D PMS     : runPSCheck
03-17 08:52:38.968   921   921 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
03-17 08:52:38.968   921   921 D HtcPowerSaver: Checking...
03-17 08:52:38.968   921   921 D UsbnetService: BroadcastReceiver::onReceive-
,03-17 08:52:38.968   921   921 I HtcPowerSaver: >> updateStatus
03-17 08:52:38.968   921  1149 D WifiController: handleMessage: E msg.what=155652
03-17 08:52:38.968   921  1149 D WifiController: battery changed pluggedType: 2
03-17 08:52:38.968   921  1149 D WifiController: processMsg: DeviceActiveState
,03-17 08:52:38.968  1212  1212 D PowerUI : closing low battery warning: level=100
03-17 08:52:38.968   921  1149 D WifiController: processMsg: StaEnabledState
03-17 08:52:38.978  1212  1212 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,03-17 08:52:38.968   921  1149 D WifiController: processMsg: DefaultState
03-17 08:52:38.968   921  1149 D WifiController: handleMessage: X
03-17 08:52:38.978   921   921 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
03-17 08:52:38.968  1306  1306 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,03-17 08:52:38.978   921   921 I HtcPowerSaver: << updateStatus
03-17 08:52:38.968  1306  1306 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-17 08:52:38.968  1306  1306 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
03-17 08:52:38.978  3387  3524 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-17 08:52:39.018  1212  1212 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,03-17 08:53:39.128   921  1716 D PMS     : acquireWL(12eb2b46): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 921 1000 null,
03-17 08:53:39.128  1306  1306 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-17 08:53:39.128   921  1716 I BatteryService: n_update end
,03-17 08:53:39.128  1306  1306 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-17 08:53:39.128   921  1716 D PMS     : releaseWL(12eb2b46): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
03-17 08:53:39.128  1306  1306 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
03-17 08:53:39.128   921   921 D NotificationService: plugged=true pluggin=true
03-17 08:53:39.128  1212  1616 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
03-17 08:53:39.128  1212  1212 D PowerUI : closing low battery warning: level=100
03-17 08:53:39.128  1212  1212 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
03-17 08:53:39.138  3387  3524 D HeadsetStateMachine: Disconnected process message: 10, size: 0
03-17 08:53:39.138   921   921 D UsbnetService: BroadcastReceiver::onReceive+
03-17 08:53:39.138   921  1053 D HtcPowerSaver: updateBatteryInfo
03-17 08:53:39.138   921   921 D UsbnetService: onReceive BATTERY_CHANGED
03-17 08:53:39.138   921   921 D PMS     : runPSCheck
,03-17 08:53:39.138   921   921 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
03-17 08:53:39.138   921   921 D HtcPowerSaver: Checking...
03-17 08:53:39.138   921   921 D UsbnetService: BroadcastReceiver::onReceive-
03-17 08:53:39.138   921   921 I HtcPowerSaver: >> updateStatus
03-17 08:53:39.138   921  1149 D WifiController: handleMessage: E msg.what=155652
03-17 08:53:39.138   921  1149 D WifiController: battery changed pluggedType: 2
03-17 08:53:39.138   921  1149 D WifiController: processMsg: DeviceActiveState
03-17 08:53:39.138   921  1149 D WifiController: processMsg: StaEnabledState
03-17 08:53:39.138   921  1149 D WifiController: processMsg: DefaultState
03-17 08:53:39.138   921  1149 D WifiController: handleMessage: X
03-17 08:53:39.138   921   921 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
03-17 08:53:39.138   921   921 I HtcPowerSaver: << updateStatus
,03-17 08:53:39.188  1212  1212 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,03-17 08:54:03.498   921  1137 D PMS     : acquireWL(3374f107): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 921 1000 WorkSource{1000}
03-17 08:54:03.508   921  1137 V AlarmManager: sending alarm PendingIntent{4939042: PendingIntentRecord{3dd4b853 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1042648, Int=0
03-17 08:54:03.508   921  1137 V AlarmManager: sending alarm PendingIntent{3ca4f234: PendingIntentRecord{1c3f285d android broadcastIntent}}, i=com.htc.intent.action.UPM_REGULAR_ALARM_INEXACT, t=3, cnt=1, w=1106158, Int=0
,03-17 08:54:03.518   921  1555 D HtcSystemUPManager: UPAlarmListener onAlarmArrival,
,03-17 08:54:03.518   921  1555 D HtcSystemUPManager: UPAlarmListener [SYSTEM_UP_FLUSH] cur = 1458201243525, last = 1458179643510, freq = 21600000
03-17 08:54:03.518   921  1564 D HtcSystemUPManager: AlarmScheduler_INEXACT [onReceive] end
03-17 08:54:03.518   921  1564 D HtcSystemUPManager: com.htc.upm.AlarmScheduler$SchedulerBase$1@39c06bbf
,03-17 08:54:03.528   921   921 D PMS     : releaseWL(3374f107): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,03-17 08:54:03.528  1212  2488 D WeatherUtility: Weather sync is On
,03-17 08:54:03.528  1212  2488 W WeatherTimeKeeper: [refreshWeatherData] no weather data
,03-17 08:54:03.538   921  1555 D HtcSystemUPManager: HtcSystemUPHandler sendService() has been called
,03-17 08:54:03.538   921  1555 D HtcSystemUPManager: HtcSystemUPDataStore [sendToService] No data needs to be sent to service
03-17 08:54:03.538   921  1555 D HtcSystemUPManager: HtcSystemUPHandler send to UPService takes: 2 ms
,03-17 08:54:39.288   921  1719 D PMS     : acquireWL(1a1eb5d2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 921 1000 null
03-17 08:54:39.288   921  1719 I BatteryService: n_update end
03-17 08:54:39.288   921  1719 D PMS     : releaseWL(1a1eb5d2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,03-17 08:54:39.288  1212  1616 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false),
03-17 08:54:39.288   921   921 D NotificationService: plugged=true pluggin=true
03-17 08:54:39.288  1306  1306 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-17 08:54:39.288  1212  1212 D PowerUI : closing low battery warning: level=100
03-17 08:54:39.288  1306  1306 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-17 08:54:39.288   921  1053 D HtcPowerSaver: updateBatteryInfo
03-17 08:54:39.288  1306  1306 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
03-17 08:54:39.288  1212  1212 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
03-17 08:54:39.288   921   921 D UsbnetService: BroadcastReceiver::onReceive+
03-17 08:54:39.298   921   921 D PMS     : runPSCheck
03-17 08:54:39.298   921   921 D UsbnetService: onReceive BATTERY_CHANGED
03-17 08:54:39.298   921   921 D HtcPowerSaver: Checking...
,03-17 08:54:39.298  3387  3524 D HeadsetStateMachine: Disconnected process message: 10, size: 0
03-17 08:54:39.298   921   921 I HtcPowerSaver: >> updateStatus
03-17 08:54:39.298   921   921 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
03-17 08:54:39.298   921  1149 D WifiController: battery changed pluggedType: 2
03-17 08:54:39.298   921   921 D UsbnetService: BroadcastReceiver::onReceive-
03-17 08:54:39.298   921  1149 D WifiController: handleMessage: E msg.what=155652
03-17 08:54:39.298   921  1149 D WifiController: processMsg: DeviceActiveState
03-17 08:54:39.298   921  1149 D WifiController: processMsg: StaEnabledState
03-17 08:54:39.298   921  1149 D WifiController: processMsg: DefaultState
03-17 08:54:39.298   921  1149 D WifiController: handleMessage: X
,03-17 08:54:39.298   921   921 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
03-17 08:54:39.298   921   921 I HtcPowerSaver: << updateStatus
,03-17 08:54:39.338  1212  1212 I BatteryController: status:5 level:100 unsupport:false plugged:true
,03-17 08:55:44.178   386   397 E PNP_UPDATERD: inotify_add_watch failed. (No such file or directory)
,03-17 08:56:00.178   921  1020 I UsageStatsService: User[0] Flushing usage stats to disk
,03-17 08:56:39.618   921  1515 D PMS     : acquireWL(2ce596a3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 921 1000 null,
,03-17 08:56:39.618   921   921 D UsbnetService: BroadcastReceiver::onReceive+
03-17 08:56:39.618   921  1515 I BatteryService: n_update end
03-17 08:56:39.618   921   921 D UsbnetService: onReceive BATTERY_CHANGED
03-17 08:56:39.618   921  1515 D PMS     : releaseWL(2ce596a3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
03-17 08:56:39.618   921   921 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
03-17 08:56:39.618   921   921 D NotificationService: plugged=true pluggin=true
,03-17 08:56:39.618   921   921 D UsbnetService: BroadcastReceiver::onReceive-
03-17 08:56:39.618   921  1053 D HtcPowerSaver: updateBatteryInfo
03-17 08:56:39.618   921  1149 D WifiController: handleMessage: E msg.what=155652
03-17 08:56:39.618   921   921 D PMS     : runPSCheck
03-17 08:56:39.618  1306  1306 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-17 08:56:39.628   921   921 D HtcPowerSaver: Checking...
03-17 08:56:39.618  1306  1306 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-17 08:56:39.628   921   921 I HtcPowerSaver: >> updateStatus
03-17 08:56:39.618  1306  1306 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
03-17 08:56:39.628   921  1149 D WifiController: battery changed pluggedType: 2
03-17 08:56:39.618   921  1149 D WifiController: processMsg: DeviceActiveState
03-17 08:56:39.628  1212  1212 D PowerUI : closing low battery warning: level=100
03-17 08:56:39.628  3387  3524 D HeadsetStateMachine: Disconnected process message: 10, size: 0
03-17 08:56:39.628   921  1149 D WifiController: processMsg: StaEnabledState
03-17 08:56:39.628   921  1149 D WifiController: processMsg: DefaultState
03-17 08:56:39.628   921  1149 D WifiController: handleMessage: X
03-17 08:56:39.628  1212  1212 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
03-17 08:56:39.628  1212  1616 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
,03-17 08:56:39.628   921   921 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1),
03-17 08:56:39.628   921   921 I HtcPowerSaver: << updateStatus
,03-17 08:56:39.678  1212  1212 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,03-17 08:58:39.928   921  1721 D PMS     : acquireWL(36b8fda0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 921 1000 null
03-17 08:58:39.928   921  1721 I BatteryService: n_update end
03-17 08:58:39.928   921  1721 D PMS     : releaseWL(36b8fda0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,03-17 08:58:39.928   921  1053 D HtcPowerSaver: updateBatteryInfo
03-17 08:58:39.928  1306  1306 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-17 08:58:39.928  1212  1616 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
03-17 08:58:39.928  1212  1212 D PowerUI : closing low battery warning: level=100
03-17 08:58:39.928  1306  1306 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-17 08:58:39.928  1212  1212 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
03-17 08:58:39.928  3387  3524 D HeadsetStateMachine: Disconnected process message: 10, size: 0
03-17 08:58:39.928   921   921 D NotificationService: plugged=true pluggin=true
03-17 08:58:39.928  1306  1306 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
03-17 08:58:39.938   921   921 D PMS     : runPSCheck
03-17 08:58:39.928   921   921 D UsbnetService: BroadcastReceiver::onReceive+
03-17 08:58:39.938   921   921 D HtcPowerSaver: Checking...
03-17 08:58:39.938   921   921 D UsbnetService: onReceive BATTERY_CHANGED
03-17 08:58:39.938   921   921 I HtcPowerSaver: >> updateStatus
03-17 08:58:39.938   921   921 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
03-17 08:58:39.938   921   921 D UsbnetService: BroadcastReceiver::onReceive-
,03-17 08:58:39.938   921  1149 D WifiController: handleMessage: E msg.what=155652
03-17 08:58:39.938   921  1149 D WifiController: battery changed pluggedType: 2
03-17 08:58:39.938   921  1149 D WifiController: processMsg: DeviceActiveState
03-17 08:58:39.938   921  1149 D WifiController: processMsg: StaEnabledState
03-17 08:58:39.938   921  1149 D WifiController: processMsg: DefaultState
03-17 08:58:39.938   921  1149 D WifiController: handleMessage: X
,03-17 08:58:39.938   921   921 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
03-17 08:58:39.938   921   921 I HtcPowerSaver: << updateStatus
,03-17 08:58:39.978  1212  1212 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,TIME-OUT KILL (timeout was 1400000ms),03-17 09:00:04.038  6657  6660 E cutils-trace: Error opening trace file: Permission denied (13)
03-17 09:00:04.188  6657  6657 D CustomizationManager: ====startRecUseTime====
03-17 09:00:04.188  6657  6657 D htc.customization.log.level:  is 
03-17 09:00:04.188  6657  6657 W CustomizationLogLevel: Level value is invalid, use default level 2
03-17 09:00:04.318  6657  6657 D CustomizationManager:  Read ACC file spent 0.071 (s)
03-17 09:00:04.328  6657  6657 D CIDMapFileReader: Parsing tag item name = HTC__001
03-17 09:00:04.328  6657  6657 D CIDMapFileReader: Parsing tag item name = HTC__102
03-17 09:00:04.338  6657  6657 D CIDMapFileReader: Parsing tag item name = HTC__Y13
03-17 09:00:04.338  6657  6657 D CIDMapFileReader: Parsing tag item name = HTC__032
03-17 09:00:04.338  6657  6657 D CIDMapFileReader: Parsing tag item name = HTC__M27
03-17 09:00:04.338  6657  6657 D CIDMapFileReader: Parsing tag item name = HTC__002
03-17 09:00:04.338  6657  6657 D CIDMapFileReader: Parsing tag item name = HTC__031
03-17 09:00:04.338  6657  6657 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__102.xml
03-17 09:00:04.338  6657  6657 I CustomizationCIDLoader: Parsing tag category name = system
03-17 09:00:04.338  6657  6657 I CustomizationCIDLoader: Parsing tag category name = application
03-17 09:00:04.348  6657  6657 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
03-17 09:00:04.348  6657  6657 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
03-17 09:00:04.348  6657  6657 I CustomizationCIDLoader: Parsing tag category name = AudioService
03-17 09:00:04.348  6657  6657 I CustomizationCIDLoader: Parsing tag category name = Settings
03-17 09:00:04.348  6657  6657 I CustomizationCIDLoader: Parsing tag category name = ACC
03-17 09:00:04.348  6657  6657 I CustomizationCIDLoader: add string-array item, value = 42507
03-17 09:00:04.348  6657  6657 I CustomizationCIDLoader: add string-array item, value = 21902
03-17 09:00:04.348  6657  6657 I CustomizationCIDLoader: add string-array item, value = 26006:26001.26002.26003
03-17 09:00:04.348  6657  6657 I CustomizationCIDLoader: add string-array item, value = 23420
03-17 09:00:04.348  6657  6657 I CustomizationCIDLoader: add string-array item, value = 22299
03-17 09:00:04.348  6657  6657 I CustomizationCIDLoader: add string-array item, value = 24002
03-17 09:00:04.348  6657  6657 I CustomizationCIDLoader: add string-array item, value = 23210
03-17 09:00:04.348  6657  6657 I CustomizationCIDLoader: add string-array item, value = 23205
03-17 09:00:04.348  6657  6657 I CustomizationCIDLoader: add string-array item, value = 23806
03-17 09:00:04.348  6657  6657 I CustomizationCIDLoader: add string-array item, value = 23430
03-17 09:00:04.348  6657  6657 I CustomizationCIDLoader: add string-array item, value = 23408
03-17 09:00:04.348  6657  6657 I CustomizationCIDLoader: add string-array item, value = 27205
03-17 09:00:04.348  6657  6657 I CustomizationCIDLoader: add string-array item, value = 42507:C:1:0
03-17 09:00:04.348  6657  6657 I CustomizationCIDLoader: add string-array item, value = 21902:C:1:0
03-17 09:00:04.348  6657  6657 I CustomizationCIDLoader: add string-array item, value = 26006:D:1:0
03-17 09:00:04.348  6657  6657 I CustomizationCIDLoader: add string-array item, value = 23420:D:0:0
03-17 09:00:04.348  6657  6657 I CustomizationCIDLoader: add string-array item, value = 22299:D:0:0
03-17 09:00:04.348  6657  6657 I CustomizationCIDLoader: add string-array item, value = 24002:D:0:0
03-17 09:00:04.348  6657  6657 I CustomizationCIDLoader: add string-array item, value = 23210:D:2:0
03-17 09:00:04.348  6657  6657 I CustomizationCIDLoader: add string-array item, value = 23205:D:0:0
03-17 09:00:04.348  6657  6657 I CustomizationCIDLoader: add string-array item, value = 23806:D:0:0
03-17 09:00:04.358  6657  6657 I CustomizationCIDLoader: add string-array item, value = 23430:C:1:0
03-17 09:00:04.358  6657  6657 I CustomizationCIDLoader: add string-array item, value = 23408:C:1:0
03-17 09:00:04.358  6657  6657 I CustomizationCIDLoader: add string-array item, value = 27205:C:1:0
03-17 09:00:04.358  6657  6657 D CustomizationManager:  Read CID file spent 0.164 (s)
03-17 09:00:04.358  6657  6657 D CustomizationManager:  All configurations done spent 0.164 (s)
03-17 09:00:04.518   921  1712 D PackageManager: deletePackageAsUser: pkg=com.test.thalitest, pid=6657, uid=2000 userid=0
03-17 09:00:04.538   921  1021 I ActivityManager: Force stopping com.test.thalitest appid=10195 user=-1: uninstall pkg
03-17 09:00:04.538   921  1021 D Process : killProcessQuiet, pid=4594
03-17 09:00:04.538   921  1021 I ActivityManager: Killing 4594:com.test.thalitest/u0a195 (adj 0): stop com.test.thalitest
03-17 09:00:04.538   921  1021 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
03-17 09:00:04.618   921  1075 W PackageSettings: Skipping PackageSetting{3d6980ac com.example.hello/10374} due to missing metadata
03-17 09:00:04.678   921  1710 I ActivityManager: Recipient 4594
03-17 09:00:04.678   921   950 I WindowState: WIN DEATH: Window{1ec3cd00 u0 com.test.thalitest/com.test.thalitest.MainActivity}
03-17 09:00:04.678   921  1149 D WifiService: Client connection lost with reason: 4
03-17 09:00:04.688  1378  1378 E InputEventReceiver: Looper::removeFd(68) is failed, result(0), input channel 'ClientState{28e92c56 uid 10195 pid 4594} (c)'
03-17 09:00:04.698  3387  3688 I bt-btif : BTA_JvDeleteRecord
03-17 09:00:04.698  3387  3611 D bt-sdp  : SDP_DeleteRecord ok, num_records:15
03-17 09:00:04.698  3387  3688 I bt-btif : BTA_JvRfcommStopServer
03-17 09:00:04.698  3387  3611 I bt-btm  : BTM_SEC_CLR[19]: id 61
03-17 09:00:04.698  3387  3688 D bt-btm  : BTM_FreeSCN 
03-17 09:00:04.758   921  1021 I ActivityManager:   Force finishing activity ActivityRecord{1d7fd970 u0 com.test.thalitest/.MainActivity t12}
03-17 09:00:04.778   921  1075 I ActivityManager: Force stopping com.test.thalitest appid=10195 user=0: pkg removed
03-17 09:00:04.778   921  1075 I ActivityManager:   Force finishing activity ActivityRecord{1d7fd970 u0 com.test.thalitest/.MainActivity t12 f}
03-17 09:00:04.788   921  1075 W ActivityManager: Duplicate finish request for ActivityRecord{1d7fd970 u0 com.test.thalitest/.MainActivity t12 f}
03-17 09:00:04.798   921  1710 W ActivityManager: Spurious death for ProcessRecord{33caed59 4594:com.test.thalitest/u0a195}, curProc for 4594: null
03-17 09:00:04.808  1306  1306 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
03-17 09:00:04.808  1306  1306 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
03-17 09:00:04.808  1306  1306 D DotMatrix: [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
03-17 09:00:04.818  1810  2237 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
03-17 09:00:04.818   921  1721 D PMS     : acquireWL(930f9ff): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1810 10024 WorkSource{10024 com.google.android.gms}
03-17 09:00:04.818   921  1140 W SystemReader: Cannot find grip_rejection_width, use default value instead
03-17 09:00:04.828   921   950 D PMS     : releaseWL(930f9ff): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
03-17 09:00:04.828  1722  2168 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
03-17 09:00:04.848  1722  2168 D AccTypeManager: Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
03-17 09:00:04.858   921  1145 D PMS     : acquireWL(30bfe2cd): PARTIAL_WAKE_LOCK  NetworkStats 0x1 921 1000 null
03-17 09:00:04.868  1679  6675 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
03-17 09:00:04.888  5829  5829 I art     : Explicit concurrent mark sweep GC freed 9469(573KB) AllocSpace objects, 0(0B) LOS objects, 44% free, 2MB/4MB, paused 424us total 95.207ms
03-17 09:00:04.888   921  1146 V NetworkPolicy: ACTION_UID_REMOVED for uid=10195
03-17 09:00:04.898  1722  2168 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
03-17 09:00:04.898  1491  1491 I art     : Explicit concurrent mark sweep GC freed 22212(1324KB) AllocSpace objects, 8(784KB) LOS objects, 34% free, 29MB/45MB, paused 1.233ms total 107.413ms
03-17 09:00:04.908  1491  2067 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
03-17 09:00:04.908  1491  2067 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
03-17 09:00:04.918  1433  1433 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
03-17 09:00:04.918  1568  6676 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
03-17 09:00:04.918  1491  1491 I Launcher: Deferring update until onResume
03-17 09:00:04.918  1491  1491 D Launcher: waitUntilResume // bindAppsRemoved
03-17 09:00:04.918  1491  1491 D Prism.PackageStateRece_: action: android.intent.action.PACKAGE_REMOVED
03-17 09:00:04.928  1722  2168 E ExternalAccountType: Unsupported attribute readOnly
03-17 09:00:04.928  1568  6676 I [PluginManager]RegisterService: handle notify Blinkfeed plugin client changed
03-17 09:00:04.948   921  1716 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6677 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
03-17 09:00:04.948   921  1145 D PMS     : releaseWL(30bfe2cd): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
03-17 09:00:04.948   921  1146 V NetworkPolicy: writePolicyLocked()
03-17 09:00:04.958   921  1146 V NetworkPolicy: updateNetworkEnabledLocked()
03-17 09:00:04.958   921  1146 V NetworkPolicy: updateNotificationsLocked()
03-17 09:00:04.988   921   921 W PackageManager: Unable to load service info ResolveInfo{178d9a94 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
03-17 09:00:04.988   921   921 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
03-17 09:00:04.988   921   921 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
03-17 09:00:04.988   921   921 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
03-17 09:00:04.988   921   921 W PackageManager: 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
03-17 09:00:04.988   921   921 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
03-17 09:00:04.988   921   921 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
03-17 09:00:04.988   921   921 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
03-17 09:00:04.988   921   921 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739)
03-17 09:00:04.988   921   921 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-17 09:00:04.988   921   921 W PackageManager: 	at android.os.Looper.loop(Looper.java:155)
03-17 09:00:04.988   921   921 W PackageManager: 	at com.android.server.SystemServer.run(SystemServer.java:324)
03-17 09:00:04.988   921   921 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:225)
03-17 09:00:04.988   921   921 W PackageManager: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 09:00:04.988   921   921 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 09:00:04.988   921   921 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
03-17 09:00:04.988   921   921 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
03-17 09:00:04.998   921  1020 I InputMethodManagerService: [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
03-17 09:00:05.038   921   921 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-17 09:00:05.058   921  1175 D TaskPersister: removeObsoleteFile: deleting file=12_task.xml
03-17 09:00:05.058   921  1175 D TaskPersister: removeObsoleteFile: deleting file=12_task_thumbnail.png
03-17 09:00:05.088   921  1044 D StatusBarManagerService: setSystemUiVisibility(0x8700)
03-17 09:00:05.088   921  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-17 09:00:05.088   921  1044 D StatusBarManagerService: hiding MENU key
03-17 09:00:05.088   921  1075 I art     : Explicit concurrent mark sweep GC freed 28746(2MB) AllocSpace objects, 8(224KB) LOS objects, 33% free, 18MB/28MB, paused 8.037ms total 239.852ms
03-17 09:00:05.088   921  1044 D StatusBarManagerService: setSystemUiVisibility(0xc0000700)
03-17 09:00:05.088   921  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-17 09:00:05.088   921  1044 D StatusBarManagerService: hiding MENU key
03-17 09:00:05.098  1491  1491 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
03-17 09:00:05.118  1491  1491 I ThreadedRenderer: Defer allocateBuffers to drawing time
03-17 09:00:05.128   921  1157 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 4594 uid 10195
03-17 09:00:05.128   921  1157 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
03-17 09:00:05.138  1212  1212 I PhoneStatusBar: setImeWindowStatus(false,false)
03-17 09:00:05.138  6677  6677 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 
03-17 09:00:05.178   921  1020 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
03-17 09:00:05.198   921  1401 D Process : killProcessQuiet, pid=6158
03-17 09:00:05.198   921  1401 I ActivityManager: Killing 6158:com.google.android.setupwizard/u0a77 (adj 15): empty #17
03-17 09:00:05.198   921  1401 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
03-17 09:00:05.348   921  1716 I ActivityManager: Recipient 6158
03-17 09:00:05.448   921  1075 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6704 uid=10015 gids={50015, 9997, 1028, 1015, 1023, 2001, 1035, 5001} abi=arm64-v8a
03-17 09:00:05.458  1882  1882 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
03-17 09:00:05.458   921  1719 D PMS     : acquireWL(263f968f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1882 10024 WorkSource{10024 com.google.android.gms}
03-17 09:00:05.458  1882  1882 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
03-17 09:00:05.478   921  1515 D PMS     : releaseWL(263f968f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
03-17 09:00:05.498  4407  6727 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
03-17 09:00:05.498  4407  4407 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
03-17 09:00:05.508  4407  4407 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
03-17 09:00:05.508  4407  6727 D AccountUtils: Clearing selected account for com.test.thalitest
03-17 09:00:05.508  4407  4407 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
03-17 09:00:05.508  4407  4407 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
03-17 09:00:05.528   921  1514 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6731 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a
03-17 09:00:05.568  4407  6727 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
03-17 09:00:05.588  4407  6753 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
03-17 09:00:05.588  4407  6753 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
03-17 09:00:05.598  4407  6753 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
03-17 09:00:05.598  4407  6753 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
03-17 09:00:05.608  4407  6753 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
03-17 09:00:05.608  4407  6753 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
03-17 09:00:05.608  4407  6753 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
03-17 09:00:05.618   921  1157 D PMS     : acquireWL(22ad08d9): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4407 10024 null
03-17 09:00:05.618  1882  1882 I ConfigService: onCreate
03-17 09:00:05.618  4407  4407 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
03-17 09:00:05.618   921  2373 D PMS     : releaseWL(22ad08d9): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
03-17 09:00:05.618  4407  6753 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
03-17 09:00:05.618  4407  6753 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
03-17 09:00:05.618  4407  6753 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
03-17 09:00:05.628  4407  6753 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
03-17 09:00:05.628  4407  6753 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
03-17 09:00:05.628  4407  6753 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
03-17 09:00:05.648  4407  6755 W BaseAppContext: Using Auth Proxy for data requests.
03-17 09:00:05.658  4407  6761 I PeopleContactsSync: CP2 sync disabled
03-17 09:00:05.658  4407  6755 W BaseAppContext: Using Auth Proxy for data requests.
03-17 09:00:05.668   921   950 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4407, uid=10024, userID:0
03-17 09:00:05.668   921  1718 D PMS     : acquireWL(3092d776): PARTIAL_WAKE_LOCK  Icing 0x1 4407 10024 WorkSource{10024 com.google.android.gms}
03-17 09:00:05.668  4407  4962 I Icing   : doRemovePackageData com.test.thalitest
03-17 09:00:05.678   921   950 D PMS     : releaseWL(3092d776): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
03-17 09:00:05.868  1882  1903 I art     : Explicit concurrent mark sweep GC freed 34582(1919KB) AllocSpace objects, 12(772KB) LOS objects, 47% free, 4MB/8MB, paused 867us total 60.672ms
03-17 09:00:05.898  4407  6746 W DriveInitializer: Awaiting to be initialized
03-17 09:00:05.898  4407  6767 W DriveInitializer: Background init thread started
03-17 09:00:05.908  4407  6767 E SQLiteLog: (3850) statement aborts at 4: [DELETE FROM ContentFileDeletionLock112] disk I/O error
03-17 09:00:05.908  4407  6767 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/DocList.db, handle: 0x559e76c690
03-17 09:00:05.938  4407  6767 E DocListDatabase: Failed to delete from ContentFileDeletionLock112
03-17 09:00:05.938  4407  6767 E DocListDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-17 09:00:05.938  4407  6767 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-17 09:00:05.938  4407  6767 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
03-17 09:00:05.938  4407  6767 E DocListDatabase: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-17 09:00:05.938  4407  6767 E DocListDatabase: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-17 09:00:05.938  4407  6767 E DocListDatabase: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
03-17 09:00:05.938  4407  6767 E DocListDatabase: 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
03-17 09:00:05.938  4407  6767 E DocListDatabase: 	at com.google.android.gms.drive.database.f.h(SourceFile:1056)
03-17 09:00:05.938  4407  6767 E DocListDatabase: 	at com.google.android.gms.drive.r.run(SourceFile:69)
03-17 09:00:05.938  4407  6767 W DriveInitializer: Background init thread ended
03-17 09:00:05.938  4407  6746 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
03-17 09:00:05.938  4407  6746 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/DocList.db, handle: 0x559e76c690
03-17 09:00:05.938  4407  6746 E DriveAsyncService: disk I/O error (code 3850)
03-17 09:00:05.938  4407  6746 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-17 09:00:05.938  4407  6746 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-17 09:00:05.938  4407  6746 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
03-17 09:00:05.938  4407  6746 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-17 09:00:05.938  4407  6746 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-17 09:00:05.938  4407  6746 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:548)
03-17 09:00:05.938  4407  6746 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:459)
03-17 09:00:05.938  4407  6746 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
03-17 09:00:05.938  4407  6746 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
03-17 09:00:05.938  4407  6746 E DriveAsyncService: 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
03-17 09:00:05.938  4407  6746 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
03-17 09:00:05.938  4407  6746 E DriveAsyncService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-17 09:00:05.938  4407  6746 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 09:00:05.938  4407  6746 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 09:00:05.938  4407  6746 E DriveAsyncService: 	at java.lang.Thread.run(Thread.java:818)
03-17 09:00:05.938  4407  6767 E AndroidRuntime: FATAL EXCEPTION: Background initialization thread
03-17 09:00:05.938  4407  6767 E AndroidRuntime: Process: com.google.android.gms, PID: 4407
03-17 09:00:05.938  4407  6767 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-17 09:00:05.938  4407  6767 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-17 09:00:05.938  4407  6767 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
03-17 09:00:05.938  4407  6767 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-17 09:00:05.938  4407  6767 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-17 09:00:05.938  4407  6767 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
03-17 09:00:05.938  4407  6767 E AndroidRuntime: 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
03-17 09:00:05.938  4407  6767 E AndroidRuntime: 	at com.google.android.gms.drive.database.f.h(SourceFile:1056)
03-17 09:00:05.938  4407  6767 E AndroidRuntime: 	at com.google.android.gms.drive.r.run(SourceFile:69)
03-17 09:00:05.938   921  1401 E ActivityManager: App crashed! Process: com.google.android.gms
03-17 09:00:05.948  6731  6731 I GAv4    : Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
03-17 09:00:05.948  6731  6731 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-17 09:00:05.948  6731  6731 I GAv4    :   adb logcat -s GAv4
03-17 09:00:05.948  4407  6767 D Process : killProcess, pid=4407
03-17 09:00:05.958  4407  6767 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
03-17 09:00:05.968  6731  6731 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
03-17 09:00:05.968   921  6769 E DropBoxManagerService: Can't write: system_app_crash
03-17 09:00:05.968   921  6769 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop145.tmp: open failed: EROFS (Read-only file system)
03-17 09:00:05.968   921  6769 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-17 09:00:05.968   921  6769 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-17 09:00:05.968   921  6769 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-17 09:00:05.968   921  6769 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
03-17 09:00:05.968   921  6769 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-17 09:00:05.968   921  6769 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
03-17 09:00:05.968   921  6769 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-17 09:00:05.968   921  6769 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-17 09:00:05.968   921  6769 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-17 09:00:05.968   921  6769 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-17 09:00:05.968   921  6769 E DropBoxManagerService: 	... 5 more
03-17 09:00:06.008  6731  6731 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
03-17 09:00:06.008  6731  6771 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-17 09:00:06.008  6731  6771 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-17 09:00:06.028  6731  6772 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
03-17 09:00:06.028  6731  6771 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-17 09:00:06.038  6731  6772 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
03-17 09:00:06.038  6731  6772 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:00:06.038  6731  6772 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:00:06.038  6731  6772 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
03-17 09:00:06.038  6731  6772 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
03-17 09:00:06.038  6731  6772 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-17 09:00:06.038  6731  6772 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-17 09:00:06.038  6731  6772 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-17 09:00:06.038  6731  6772 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
03-17 09:00:06.038  6731  6772 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
03-17 09:00:06.038  6731  6772 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
03-17 09:00:06.038  6731  6772 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
03-17 09:00:06.038  6731  6772 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-17 09:00:06.038  6731  6772 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:00:06.038  6731  6772 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 09:00:06.038  6731  6772 E SQLiteDatabase: 	at fdw$a.getWritableDatabase(Unknown Source)
03-17 09:00:06.038  6731  6772 E SQLiteDatabase: 	at fdw.g(Unknown Source)
03-17 09:00:06.038  6731  6772 E SQLiteDatabase: 	at fdw.a(Unknown Source)
03-17 09:00:06.038  6731  6772 E SQLiteDatabase: 	at fdw.e(Unknown Source)
03-17 09:00:06.038  6731  6772 E SQLiteDatabase: 	at fdy.b(Unknown Source)
03-17 09:00:06.038  6731  6772 E SQLiteDatabase: 	at feb.run(Unknown Source)
03-17 09:00:06.038  6731  6772 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-17 09:00:06.038  6731  6772 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 09:00:06.038  6731  6772 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 09:00:06.038  6731  6772 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 09:00:06.038  6731  6772 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-17 09:00:06.038  6731  6772 E SQLiteDatabase: 	at gir$c.run(Unknown Source)
03-17 09:00:06.048  6731  6772 E GAv4    : Opening the database failed, dropping the table and recreating it
03-17 09:00:06.048  6731  6771 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-17 09:00:06.048  6731  6731 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.25.45
03-17 09:00:06.048  6731  6772 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
03-17 09:00:06.048  6731  6772 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:00:06.048  6731  6772 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:00:06.048  6731  6772 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
03-17 09:00:06.048  6731  6772 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
03-17 09:00:06.048  6731  6772 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-17 09:00:06.048  6731  6772 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-17 09:00:06.048  6731  6772 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-17 09:00:06.048  6731  6772 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
03-17 09:00:06.048  6731  6772 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
03-17 09:00:06.048  6731  6772 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
03-17 09:00:06.048  6731  6772 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
03-17 09:00:06.048  6731  6772 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-17 09:00:06.048  6731  6772 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:00:06.048  6731  6772 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 09:00:06.048  6731  6772 E SQLiteDatabase: 	at fdw$a.getWritableDatabase(Unknown Source)
03-17 09:00:06.048  6731  6772 E SQLiteDatabase: 	at fdw.g(Unknown Source)
03-17 09:00:06.048  6731  6772 E SQLiteDatabase: 	at fdw.a(Unknown Source)
03-17 09:00:06.048  6731  6772 E SQLiteDatabase: 	at fdw.e(Unknown Source)
03-17 09:00:06.048  6731  6772 E SQLiteDatabase: 	at fdy.b(Unknown Source)
03-17 09:00:06.048  6731  6772 E SQLiteDatabase: 	at feb.run(Unknown Source)
03-17 09:00:06.048  6731  6772 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-17 09:00:06.048  6731  6772 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 09:00:06.048  6731  6772 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 09:00:06.048  6731  6772 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 09:00:06.048  6731  6772 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-17 09:00:06.048  6731  6772 E SQLiteDatabase: 	at gir$c.run(Unknown Source)
03-17 09:00:06.058  6731  6772 E GAv4    : Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:00:06.058  6731  6772 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:00:06.058  6731  6771 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-17 09:00:06.058  6731  6772 E GAv4    : Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:00:06.058  6731  6771 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-17 09:00:06.058  6731  6771 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-17 09:00:06.088   921  1712 I ActivityManager: Recipient 4407
03-17 09:00:06.088   921  1149 D WifiService: Client connection lost with reason: 4
03-17 09:00:06.088   921  1712 I ActivityManager: Process com.google.android.gms (pid 4407) has died
03-17 09:00:06.088   921  1712 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
03-17 09:00:06.098   921  1712 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
03-17 09:00:06.098  1882  1882 I ConfigService: onDestroy
03-17 09:00:06.098   921  1712 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
03-17 09:00:06.098  6731  6773 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
03-17 09:00:06.098  6731  6773 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:00:06.098  6731  6773 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:00:06.098  6731  6773 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
03-17 09:00:06.098  6731  6773 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
03-17 09:00:06.098  6731  6773 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-17 09:00:06.098  6731  6773 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-17 09:00:06.098  6731  6773 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-17 09:00:06.098  6731  6773 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
03-17 09:00:06.098  6731  6773 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
03-17 09:00:06.098  6731  6773 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
03-17 09:00:06.098  6731  6773 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
03-17 09:00:06.098  6731  6773 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-17 09:00:06.098  6731  6773 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:00:06.098  6731  6773 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 09:00:06.098  6731  6773 E SQLiteDatabase: 	at aev.getWritableDatabase(PG:238)
03-17 09:00:06.098  6731  6773 E SQLiteDatabase: 	at ael.a(PG:1521)
03-17 09:00:06.098  6731  6773 E SQLiteDatabase: 	at hix$a.a(PG:125)
03-17 09:00:06.098  6731  6773 E SQLiteDatabase: 	at aen.run(PG:536)
03-17 09:00:06.148   921   951 I ActivityManager: Start proc com.google.android.gms for service com.google.android.gms/.analytics.service.AnalyticsService: pid=6774 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
03-17 09:00:06.158   439   439 I art     : Explicit concurrent mark sweep GC freed 8672(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 210us total 25.928ms
03-17 09:00:06.188   439   439 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 170us total 24.075ms
03-17 09:00:06.188  6774  6774 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-17 09:00:06.188  6774  6774 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
03-17 09:00:06.208   439   439 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 196us total 23.674ms
03-17 09:00:06.218   921  2373 D VoldConnector: SND -> {31 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/}
03-17 09:00:06.218   383   657 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/
03-17 09:00:06.218  6731  6798 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.docs/cache
03-17 09:00:06.218  6731  6798 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
03-17 09:00:06.218  6731  6798 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:00:06.218  6731  6798 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:00:06.218  6731  6798 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
03-17 09:00:06.218  6731  6798 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
03-17 09:00:06.218  6731  6798 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-17 09:00:06.218  6731  6798 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-17 09:00:06.218  6731  6798 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-17 09:00:06.218  6731  6798 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
03-17 09:00:06.218  6731  6798 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
03-17 09:00:06.218  6731  6798 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
03-17 09:00:06.218  6731  6798 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
03-17 09:00:06.218  6731  6798 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-17 09:00:06.218  6731  6798 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:00:06.218  6731  6798 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 09:00:06.218  6731  6798 E SQLiteDatabase: 	at aev.getWritableDatabase(PG:238)
03-17 09:00:06.218  6731  6798 E SQLiteDatabase: 	at ael.a(PG:1521)
03-17 09:00:06.218  6731  6798 E SQLiteDatabase: 	at hix$a.a(PG:125)
03-17 09:00:06.218  6731  6798 E SQLiteDatabase: 	at aej.c(PG:139)
03-17 09:00:06.218  6731  6798 E SQLiteDatabase: 	at aej.b(PG:398)
03-17 09:00:06.218  6731  6798 E SQLiteDatabase: 	at agf.f(PG:417)
03-17 09:00:06.218  6731  6798 E SQLiteDatabase: 	at oe.run(PG:1112)
03-17 09:00:06.218  6731  6798 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-17 09:00:06.218  6731  6798 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 09:00:06.218  6731  6798 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 09:00:06.218  6731  6798 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 09:00:06.218  6731  6798 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-17 09:00:06.218  6731  6798 E AbstractDatabaseInstance: Failed to delete from CachedSearch133
03-17 09:00:06.218  6731  6798 E AbstractDatabaseInstance: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:00:06.218  6731  6798 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:00:06.218  6731  6798 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
03-17 09:00:06.218  6731  6798 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
03-17 09:00:06.218  6731  6798 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-17 09:00:06.218  6731  6798 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-17 09:00:06.218  6731  6798 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-17 09:00:06.218  6731  6798 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
03-17 09:00:06.218  6731  6798 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
03-17 09:00:06.218  6731  6798 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
03-17 09:00:06.218  6731  6798 E AbstractDatabaseInstance: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
03-17 09:00:06.218  6731  6798 E AbstractDatabaseInstance: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-17 09:00:06.218  6731  6798 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:00:06.218  6731  6798 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 09:00:06.218  6731  6798 E AbstractDatabaseInstance: 	at aev.getWritableDatabase(PG:238)
03-17 09:00:06.218  6731  6798 E AbstractDatabaseInstance: 	at ael.a(PG:1521)
03-17 09:00:06.218  6731  6798 E AbstractDatabaseInstance: 	at hix$a.a(PG:125)
03-17 09:00:06.218  6731  6798 E AbstractDatabaseInstance: 	at aej.c(PG:139)
03-17 09:00:06.218  6731  6798 E AbstractDatabaseInstance: 	at aej.b(PG:398)
03-17 09:00:06.218  6731  6798 E AbstractDatabaseInstance: 	at agf.f(PG:417)
03-17 09:00:06.218  6731  6798 E AbstractDatabaseInstance: 	at oe.run(PG:1112)
03-17 09:00:06.218  6731  6798 E AbstractDatabaseInstance: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-17 09:00:06.218  6731  6798 E AbstractDatabaseInstance: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 09:00:06.218  6731  6798 E AbstractDatabaseInstance: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 09:00:06.218  6731  6798 E AbstractDatabaseInstance: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 09:00:06.218  6731  6798 E AbstractDatabaseInstance: 	at java.lang.Thread.run(Thread.java:818)
03-17 09:00:06.228  6774  6774 I MultiDex: VM with version 2.1.0 has multidex support
03-17 09:00:06.228  6774  6774 I MultiDex: install
03-17 09:00:06.228  6774  6774 I MultiDex: VM has multidex support, MultiDex support library is disabled.
03-17 09:00:06.238  6731  6799 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-17 09:00:06.238   921  2373 D PMS     : acquireWL(1ab0225a): PARTIAL_WAKE_LOCK  AsyncService 0x1 5954 10167 null
03-17 09:00:06.238  6731  6799 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.

```
