#### Test 57972094912017a_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
I/LibraryLoader( 3517): Time to load native libraries: 40 ms (timestamps 726-766)
I/LibraryLoader( 3517): Expected native library version number "",actual native library version number ""
I/BrowserStartupController( 3517): Initializing chromium process, renderers=9
I/LibraryLoader( 3517): Expected native library version number "",actual native library version number ""
I/chromium( 3517): [INFO:library_loader_hooks.cc(113)] Chromium logging enabled: level = 0, default verbosity = 0
--------- beginning of /dev/log/system
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(42954cb8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/PMS     (  906): releaseWL(42d2d508): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 WorkSource{10029}
I/IntentController( 1127): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
D/PMS     (  906): releaseWL(42954cb8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PhoneStatusBar( 1127): removeIcon slot=sync_active index=7 viewIndex=0
I/Adreno-EGL( 3517): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3517): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3517): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3517): Local Branch: 
I/Adreno-EGL( 3517): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3517): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3517):                  aa63bbd948f41d15fc72f585e
D/Process (  906): killProcessQuiet, pid=3224
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
V/IccIntentReceiver( 1325): IccIntent: android.intent.action.SIM_STATE_CHANGED icc state: ABSENT phone_type: 1 icc slot: -1
I/ActivityManager(  906): Killing 3224:com.htc.backup/1000 (adj 15): empty #17
I/ActivityManager(  906): Recipient 3224
I/SIMStateChangeReceiver( 1538): SIM state: ABSENT
I/SIMStateChangeReceiver( 1538): phoneType = 0
I/SIMStateChangeReceiver( 1538): remove notification
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.PhoneStateReceiver: pid=3564 uid=10032 gids={50032, 3003, 5012}
D/Process (  906): killProcessQuiet, pid=3165
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=3576 uid=10044 gids={50044, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
I/ActivityManager(  906): Killing 3165:com.htc.cs.dm/u0a98 (adj 15): empty #17
W/SystemReader( 2966): Cannot find message_ambs_application_id, use default value instead
D/SmsReceiver( 2966): Don't handle ACTION_SIM_STATE_CHANGED not ready action 
D/ExchangePolicystatus( 2966): onReceive()
D/ExchangePolicystatus( 2966): onReceive(): ACTION_SIM_STATE_CHANGED
D/ExchangePolicystatus( 2966): onReceive(): else
D/Process (  906): killProcessQuiet, pid=2652
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 2652:com.android.defcontainer/u0a19 (adj 15): empty #17
I/ActivityManager(  906): Recipient 2652
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/HtcBroadcastReceiver( 1263): onReceive: android.intent.action.SIM_STATE_CHANGED
W/WeatherUtility( 1127): can't get weather sync account
I/ActivityManager(  906): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3600 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
I/ActivityManager(  906): Recipient 3165
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/AccTypeManager( 3576): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/WeatherRequest( 1127): request cur loc, but there is no sys cur
D/CalendarApplication( 3600): onCreate
D/ProviderChangeReceiver( 3600): ---------------------------------------------------
D/ProviderChangeReceiver( 3600): ProviderChangeReceiver onReceive, start to update notification!
D/AlertService( 3600): start to updateAlertNotification!
W/AccTypeManager( 3576): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 3576): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
W/ContextImpl( 3332): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  906): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3617 uid=10041 gids={50041}
D/AlertService( 3600): No fired or scheduled alerts
D/HtcAlertUtils( 3600): -- cancelReminderNotification --
D/HtcAlertUtils( 3600): broadcastExistReminder!
D/CustomizationManager( 3541): ====startRecUseTime====
D/htc.customization.log.level( 3541):  is 
W/CustomizationLogLevel( 3541): Level value is invalid, use default level 2
D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
E/ExternalAccountType( 3576): Unsupported attribute readOnly
D/Process (  906): killProcessQuiet, pid=3245
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3245:com.google.android.talk/u0a111 (adj 15): empty #17
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3245
D/Process (  906): killProcessQuiet, pid=3272
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3630 uid=10078 gids={50078}
I/ActivityManager(  906): Killing 3272:com.htc.backupreset/1000 (adj 15): empty #17
D/AccTypeManager( 3576): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3272
W/AccTypeManager( 3576): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 3576): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/ExternalAccountType( 3576): Unsupported attribute readOnly
D/SMSBackup( 3630): Got a database change event
D/Process (  906): killProcessQuiet, pid=3289
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.WeatherClock4x1: pid=3642 uid=10045 gids={50045, 3002, 3001, 3003, 5012}
I/ActivityManager(  906): Killing 3289:com.htc.htccupd/u0a17 (adj 15): empty #17
I/ActivityManager(  906): Recipient 3289
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/CustomizationManager( 3541):  Read ACC file spent 0.079 (s)
D/CIDMapFileReader( 3541): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3541): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3541): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3541): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3541): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3541): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3541): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3541): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3541): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3541): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3541): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3541): Parsing tag category name = system
I/CustomizationCIDLoader( 3541): Parsing tag category name = application
I/CustomizationCIDLoader( 3541): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3541): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3541): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3541): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3541): Parsing tag category name = Settings
D/CustomizationManager( 3541):  Read CID file spent 0.126 (s)
D/CustomizationManager( 3541):  All configurations done spent 0.127 (s)
W/HtcNativeFlag( 3541): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3541): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3541): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3541): Fail to get flag for type 'language', use default value: -1
I/ActivityManager(  906): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver: pid=3657 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
W/WeatherUtility( 3642): can't get weather sync account
E/cutils-trace( 3541): Error opening trace file: No such file or directory (2)
W/WeatherRequest( 3642): request cur loc, but there is no sys cur
W/Settings( 3642): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3541
I/DemoRecovery.RestoreReceiver( 3657): onReceive: com.htc.launcher.intent.LOADING_COMPLETE
W/ContextImpl( 3657): Implicit intents with startService are not safe: Intent { act=com.htc.demorecovery.LOADING_COMPLETE } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.demoflopackageinstaller.demorecovery.RestoreReceiver.onReceive:26 
I/RestoreService( 3657): onHandleIntent: com.htc.demorecovery.LOADING_COMPLETE
I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver
D/AppWidgetHostView( 1299): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
I/RemoteViews( 1299): com.htc.widget.weatherclock (true,33751552)
I/ActivityManager(  906): Resuming delayed broadcast
I/RemoteViews.Performance( 1299): com.htc.widget.weatherclock 1 7 17
I/ActivityManager(  906): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3673 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
D/Process (  906): killProcessQuiet, pid=3304
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 3304:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/PMS     (  906): acquireWL(42b65bc8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3673 10071 null
D/PMS     (  906): acquireWL(42c238d8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3673 10071 null
D/PMS     (  906): releaseWL(42b65bc8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/TodoTaskshortcut( 3673): update TASK shortcut>
I/ActivityManager(  906): Delay finish: com.htc.task/.TodoReceiver
I/ActivityManager(  906): Recipient 3304
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/TodoTaskNotifyService( 3673): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  906): releaseWL(42c238d8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  906): Resuming delayed broadcast
W/NotifyReceiver( 3673): stopSelfResult true
D/Process (  906): killProcessQuiet, pid=3318
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Start proc com.htc.stock for broadcast com.htc.stock/.receiver.StockReceiver: pid=3688 uid=10082 gids={50082, 3003, 5012}
I/ActivityManager(  906): Killing 3318:com.zoodles.kidmode/u0a149 (adj 15): empty #17
I/ActivityManager(  906): Recipient 3318
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Start proc com.htc.stock:remote for content provider com.htc.stock/.provider.StockProvider: pid=3700 uid=10082 gids={50082, 3003, 5012}
,D/Process (  906): killProcessQuiet, pid=3375
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 3375:com.android.smith/u0a163 (adj 15): empty #17
D/Process (  906): killProcessQuiet, pid=3361
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 3361:org.simalliance.openmobileapi.service/9987 (adj 15): empty #18
I/ActivityManager(  906): Recipient 3375
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3361
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/LocationInitializer( 2180): Restart initialization of location
D/WearableService( 1247): callingUid 10029, callindPid: 1247
I/ActivityManager(  906): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  906): Resuming delayed broadcast
D/AuthorizationBluetoothService( 1396): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/AuthorizationBluetoothService( 1396): Proximity feature is not enabled.
E/MDM     ( 1247): [93] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
V/GLSActivity( 1396): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/SMSBackup( 3630): Got a database change event
I/ActivityManager(  906): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=3717 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
W/GCoreFlp( 1247): No location to return for getLastLocation()
W/FusedLocationProvider( 1247): location=null
D/PMS     (  906): acquireWL(42d9b740): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1247 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(42d9b740): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031187
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031351
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031596
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031601
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031605
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031608
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033590
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033602
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360036074
D/ContactMessageStore( 1263): MSG_NOTIFY_CS_TO_SYNC >>
D/ContactMessageStore( 1263): MSG_NOTIFY_CS_TO_SYNC <<
I/ImageRamCache( 3717): create image Cache, size: 31457280.
I/ImageRamCache( 3717): [resize] ImageRamCache resized to: 12Mb.
I/ImageRamCache( 3717): create image Cache, size: 12582912.
I/FeedSettings( 3717): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
I/FeedSettings( 3717): GroupBudget 0.500000 0.380000
I/FeedSettings( 3717): GroupBudget 60 45 15
I/Prism.ExternalStringMa_( 3717): changeLocale(): en_GB
I/Prism.AllAppsOptionsMa_( 3717): loadSortType() with Custom
I/Prism.AllAppsOptionsMa_( 3717): loadGridSize() with Alternative
D/CustomHighlightReceiver( 3717): [custom highlight] onReceive
D/CustomHighlightService( 3717): [custom highlight] onHandleIntent
D/NewsDB  ( 3717): set custom highlight []
I/ActivityManager(  906): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
D/CustomHighlightService( 3717): [custom highlight] set tags 
D/MessagingShortcutReceiver( 2966): keep hiding shortcut bubble
I/ActivityManager(  906): Resuming delayed broadcast
D/MessagingShortcut( 2966): updateMsgShortcut, msg count> -1
D/MessagingShortcut( 2966): After query: 0
D/MessagingShortcut( 2966): mPresentUnreadCount: -1
D/MessagingShortcut( 2966): setMsgShortcutDrawable> 0
D/MessagingShortcut( 2966): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderNotification, total:0
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/TodoTaskshortcut( 3673): update TASK shortcut>
I/ActivityManager(  906): Delay finish: com.htc.task/.TodoReceiver
D/HtcBroadcastReceiver( 1263): onReceive: com.htc.launcher.action.ACTION_ITEM_ADDED
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3733 uid=10091 gids={50091, 3003, 5012}
I/ActivityManager(  906): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031187
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031351
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031596
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031601
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031605
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031608
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033590
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033602
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360036074
D/MessagingNotification( 2966): New incoming message, can't cancel notification now
D/MessagingNotification( 2966): newMsgCnt: 0, false
I/ActivityManager(  906): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3747 uid=10091 gids={50091, 3003, 5012}
D/MdScBoot( 3733): [6e0.1.] 30@-144533 -> 40@-144602
D/Process (  906): killProcessQuiet, pid=3387
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Killing 3387:com.google.android.youtube/u0a168 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
D/Process (  906): killProcessQuiet, pid=3437
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3437:com.android.vending/u0a74 (adj 15): empty #17
E/MDM     ( 1247): [95] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 2180): Restart initialization of location
D/AuthorizationBluetoothService( 1396): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/AuthorizationBluetoothService( 1396): Proximity feature is not enabled.
V/GLSActivity( 1396): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GCoreFlp( 1247): No location to return for getLastLocation()
W/FusedLocationProvider( 1247): location=null
D/PMS     (  906): acquireWL(42c14df0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1247 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(42c14df0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031187
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031351
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031596
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031601
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031605
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031608
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033590
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033602
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360036074
E/MDM     ( 1247): [97] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/ActivityManager(  906): Recipient 3387
I/ActivityManager(  906): Recipient 3437
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  906): Client com.google.android.youtube (pid 3387): Died!
D/LocationInitializer( 2180): Restart initialization of location
D/AuthorizationBluetoothService( 1396): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/AuthorizationBluetoothService( 1396): Proximity feature is not enabled.
V/GLSActivity( 1396): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  906): acquireWL(42d06c20): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3673 10071 null
D/PMS     (  906): acquireWL(42c26188): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3673 10071 null
I/ActivityManager(  906): Delay finish: com.htc.launcher/.receiver.NotificationReceiver
E/TodoTaskNotifyService( 3673): java.lang.NullPointerException
W/System.err( 3673): java.lang.NullPointerException
D/PMS     (  906): releaseWL(42d06c20): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
W/System.err( 3673): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3673): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3673): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3673): 	at android.os.Looper.loop(Looper.java:157)
W/System.err( 3673): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/NotifyReceiver( 3673): stopSelfResult true
D/PMS     (  906): releaseWL(42c26188): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  906): Resuming delayed broadcast
D/PMS     (  906): acquireWL(42d26fb0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3673 10071 null
D/PMS     (  906): acquireWL(42d62178): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1247 10029 WorkSource{10029 com.google.android.gms}
W/GCoreFlp( 1247): No location to return for getLastLocation()
W/FusedLocationProvider( 1247): location=null
D/MtpReceiver( 2945): [MTP][MtpReceiver][onReceive]+
D/MtpReceiver( 2945): [MTP][MtpReceiver][onReceive]1-
D/MtpReceiver( 2945): [MTP][handleMessage][startService]
D/PMS     (  906): acquireWL(42d07058): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3673 10071 null
D/PMS     (  906): releaseWL(42d62178): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031187
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031351
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031596
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031601
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031605
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031608
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033590
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033602
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360036074
I/ActivityManager(  906): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3776 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
E/TodoTaskNotifyService( 3673): java.lang.NullPointerException
W/System.err( 3673): java.lang.NullPointerException
W/System.err( 3673): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
D/MtpReceiver( 2945): [MTP][handleMessage][UsbManager.USB_CONNECTED][insert]+
W/System.err( 3673): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3673): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3673): 	at android.os.Looper.loop(Looper.java:157)
W/System.err( 3673): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/MtpReceiver( 2945): [MTP][handleMessage]-
D/PMS     (  906): releaseWL(42d26fb0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  906): releaseWL(42d07058): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
W/NotifyReceiver( 3673): stopSelfResult true
D/MtpService( 2945): [MTP] startForeground
I/RemoteViews( 1127): com.android.providers.media (false,0)
D/DotMatrix( 1590): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
I/RemoteViews.Performance( 1127): com.android.providers.media 1 1 10
D/MtpService( 2945): updating state; isCurrentUser=true, mMtpLocked=false
D/MtpDatabase( 2945): TotalSize=1918604,MediaCacheLimit=6000
I/RemoteViews( 1127): com.android.providers.media (false,0)
I/RemoteViews.Performance( 1127): com.android.providers.media 6 1 15
D/MtpService( 2945): [isMtpConnected] connected: true
D/PMS     (  906): acquireWL(42d9fed8): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 2180 10029 null
D/SyncApplication( 3776): Loading default preferences
I/iu.UploadsManager( 2180): End new media; added: 0, uploading: 0, time: 55 ms
W/Resources( 3776): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
D/PMS     (  906): releaseWL(42d9fed8): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 null
D/WifiService(  906): New client listening to asynchronous messages
D/SyncApplication( 3776): Overriding preferences with custom values
D/SyncApplication( 3776): Updating preferences succeeded
E/SyncApplication( 3776): Application created.
D/VolumeInfo( 3776): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
D/VolumeInfo( 3776): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 3776): Found 0 mount point(s)
V/VolumeInfo( 3776): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
D/VolumeInfo( 3776): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
D/VolumeInfo( 3776): Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
W/VolumeInfo( 3776): Can not create volume ID for unmounted volume null
I/CalendarDefines( 3776): getNewCalendarAuthority()...
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3776, uid=10008, userID:0
W/PackageManager(  906): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
D/SyncApplication( 3776): enableAppOperation()+
D/SyncApplication( 3776): enableAppOperation()-
D/HTCUtilities( 3776): isNeorSinged() + 
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3776, uid=10008, userID:0
W/PackageManager(  906): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/HTCUtilities( 3776): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 3776): isNeorSinged() return false
,D/CDMountReceiver( 3776): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,D/CDMountReceiver( 3776): USB connected to PC
,D/Process (  906): killProcessQuiet, pid=3346
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3346:com.android.settings/1000 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3346
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/FOTAReceiver( 3776): onReceive() enter 
,D/FOTAReceiver( 3776): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,I/ActivityManager(  906): Start proc com.android.settings for broadcast com.android.settings/.MLReceiver: pid=3797 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  906): killProcessQuiet, pid=3517
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 3517:com.htc.sense.browser/u0a12 (adj 15): empty #17
,D/HtcFingerPrintQuickLaunchProvider( 3797): -onCreate()
,V/Settings:HtcSettingsApplication( 3797): [3797/3797] onCreate()
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3517
,D/TetherSettings( 3797): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 3797): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3797): Cust_ConnectToPC   : Modem_Link>false
,D/        ( 3797): Cust_ConnectToPC   : spcsc>false
D/        ( 3797): Cust_ConnectToPC   : IPT>true
,D/        ( 3797): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3797): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/TetherSettings( 3797): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3797): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3797): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3797): Cust_ConnectToPC   : spcsc>false
D/        ( 3797): Cust_ConnectToPC   : IPT>true
D/        ( 3797): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3797): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3797): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 3797): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3797): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 3797): usb_cable_connect = 1
,D/SmartNS_Utility( 3797): usb_denied = 0
,I/SmartNS_NSReceiver( 3797): locked:falsesecurity:falseisLocked:false
,D/SmartNS_NSReceiver( 3797): USB = true hasTethered = false isNSOpening: false
,I/PSReceiver( 3797): onReceive:com.htc.intent.action.USB_CONNECT2PC
,W/ContextImpl( 3797): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 3797): onReceive:com.htc.intent.action.USB_CONNECT2PC
W/Settings( 3797): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3797):  defaultType:0
I/SmartNS_PSService( 3797): fail notificaiton:false
D/SmartNS_Utility( 3797): usb_cable_connect = 1
D/SmartNS_Utility( 3797): usb_denied = 0
I/SmartNS_PSService( 3797): usb notificaiton:true
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/ActivityManager(  906): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
,V/Tethering(  906): bSetPropertyMultiRAB:false
,D/SmartNS_Utility( 3797): usb_cable_connect = 1
D/SmartNS_Utility( 3797): usb_denied = 0
,I/SmartNS_PSService( 3797): usb notificaiton:true
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.settings (3797/1000)
I/ActivityManager(  906): Resuming delayed broadcast
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.settings (3797/1000)
V/Tethering(  906): bSetPropertyMultiRAB:false
,I/RemoteViews( 1127): com.android.settings (true,33751552)
,I/RemoteViews.Performance( 1127): com.android.settings 2 0 10
,D/SmartNS_Utility( 3797): usb_cable_connect = 1
,D/SmartNS_Utility( 3797): usb_denied = 0
,D/DotMatrix( 1590): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
,I/ActivityManager(  906): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
I/RemoteViews( 1127): com.android.settings (true,33751552)
D/DotMatrix( 1590): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
I/RemoteViews.Performance( 1127): com.android.settings 1 1 10
W/WeatherUtility( 3642): can't get weather sync account
I/SmartNS_PSService( 3797): KeyGuard locked:falseKeyGuard is secured:false
D/SmartNS_PSService( 3797): USB Plugged, Set USBPlugged=  truePSenabled:false
I/ActivityManager(  906): Resuming delayed broadcast
D/AppWidgetHostView( 1299): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider})
I/RemoteViews( 1299): com.google.android.googlequicksearchbox (false,0)
I/RemoteViews.Performance( 1299): com.google.android.googlequicksearchbox 2 1 5
D/PMS     (  906): acquireWL(42a06ad0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
W/WeatherRequest( 3642): request cur loc, but there is no sys cur
W/Settings( 3642): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1299): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1299): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1299): com.htc.widget.weatherclock 0 7 17
,D/PMS     (  906): releaseWL(42a06ad0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/WifiDataStallTracker(  906): onReceive: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  906): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  906): updateDataStallInfo: mDataStallTxRxSum={txSum=31 rxSum=29} preTxRxSum={txSum=0 rxSum=0}
D/WifiDataStallTracker(  906): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  906): onDataStallAlarm: tag=21996 Sent 0 pkts since last received, < watchdogTrigger=5
D/WifiDataStallTracker(  906): startDataStallAlarm: tag=21997 delay=15s
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2180/10029)
,D/GCM     ( 1396): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/PMS     (  906): acquireWL(42575838): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1396 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncScreenOnOffTimeReceiver: pid=3818 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1396/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [2][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): releaseWL(42575838): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4218eee0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3818 1000 null
,W/ContextImpl( 3818): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  906): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
D/PowerUsageService( 3818): call getInstance()
,D/PowerUsageList:PowerUsageHelper( 3818): MY_DEBUG = false
,D/WIFI_ICON( 1127): WifiActivity: 3
,D/StatusBar.NetworkController( 1127): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,I/HtcModeClient( 1538): handler message = 4011
,E/HtcModeClient( 1538): Check connection and retry 4 times.
,I/SensorManager(  906): mEventCount = 300
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1118): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=3564
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3564:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,W/WeatherUtility( 1127): can't get weather sync account
,D/WeatherUtility( 1339): Weather sync is On
,D/WSP     ( 1339): [Receiver] auto sync agent, auto sync is enabled, reset schedule
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3564
,I/ActivityManager(  906): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=3835 uid=10034 gids={50034, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
W/WeatherUtility( 3642): can't get weather sync account
,W/WeatherRequest( 3642): request cur loc, but there is no sys cur
,W/Settings( 3642): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1299): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1299): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1299): com.htc.widget.weatherclock 1 10 17
,I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,D/WIFI_ICON( 1127): WifiActivity: 1
,D/StatusBar.NetworkController( 1127): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=3853 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/Process (  906): killProcessQuiet, pid=3576
,I/ActivityManager(  906): Killing 3576:com.htc.contacts/u0a44 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Recipient 3576
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/MusicStore( 3853): Database version: 95
,W/ContextImpl( 3853): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 3853): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3853): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3853): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3853): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=3853, uid=10154, userID:0
,D/WifiDisplayAdapter(  906): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  906):     Client/Owner: Client
D/WifiDisplayAdapter(  906):     GroupId: 
D/WifiDisplayAdapter(  906):     Passphrase: 
D/WifiDisplayAdapter(  906):     SessionId: 0
D/WifiDisplayAdapter(  906):     IP Address: }
,D/MediaRouterService(  906): Client com.google.android.music (pid 3853): Registered
,D/WifiDisplayAdapter(  906): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  906):     Client/Owner: Client
D/WifiDisplayAdapter(  906):     GroupId: 
D/WifiDisplayAdapter(  906):     Passphrase: 
D/WifiDisplayAdapter(  906):     SessionId: 0
D/WifiDisplayAdapter(  906):     IP Address: }
,V/AlarmManager(  906): sending alarm PendingIntent{42b34220: PendingIntentRecord{42dcb1e8 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1454420764503, Int=0
I/MediaRouter( 3853): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/PMS     (  906): acquireWL(42d4e428): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/ActivityManager(  906): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42d4e428): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1127): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/NetworkMonitor( 3853): type=WIFI subType= reason=null isConnected=true
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1127): closing low battery warning: level=100
D/PowerUI ( 1127): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.music (3853/10154)
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,I/ActivityManager(  906): Resuming delayed broadcast
D/TelephonyReceiver( 1263): bind: true
,D/Process (  906): killProcessQuiet, pid=3600
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/DFPI.PIReciver( 3657): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,I/ActivityManager(  906): Killing 3600:com.htc.calendar/u0a13 (adj 15): empty #17
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
I/DFPI.ApkInstallService( 3657): onHandleIntent
,I/DFPI.ApkInstallService( 3657): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3657): check CID = HTC__032
,I/DFPI.ApkInstallService( 3657): There is no Demo.apk in sd card or phone storage
,D/GenericMessagesProvider( 2966): query uri: content://htc-messages/wappush/count
I/ActivityManager(  906): Recipient 3600
I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/SQLiteLog( 2966): (14) cannot open file at line 30190 of [00bb9c9ce4]
E/SQLiteLog( 2966): (14) os_unix.c:30190: (2) open(/data/data/com.htc.sense.mms/databases/wappush.db) - 
E/SQLiteConnection( 2966): DB info: sqlite3_open_v2, path: /data/data/com.htc.sense.mms/databases/wappush.db, flag: 1, ret: 14
,E/SQLiteConnection( 2966): DB info: errno = 2, errno message = No such file or directory
,E/SQLiteDatabase( 2966): Failed to open database '/data/data/com.htc.sense.mms/databases/wappush.db'.
E/SQLiteDatabase( 2966): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 2966): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2966): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2966): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2966): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2966): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2966): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2966): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2966): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2966): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2966): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
E/SQLiteDatabase( 2966): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
E/SQLiteDatabase( 2966): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 2966): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 2966): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
E/SQLiteDatabase( 2966): 	at android.os.Binder.execTransact(Binder.java:412)
E/SQLiteDatabase( 2966): 	at dalvik.system.NativeStart.run(Native Method)
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
W/System.err( 2966): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
W/System.err( 2966): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 2966): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/System.err( 2966): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/System.err( 2966): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/System.err( 2966): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/System.err( 2966): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/System.err( 2966): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/System.err( 2966): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/System.err( 2966): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/System.err( 2966): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
W/System.err( 2966): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
W/System.err( 2966): 	at android.content.ContentProvider.query(ContentProvider.java:869)
W/System.err( 2966): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
I/ActivityManager(  906): Resuming delayed broadcast
W/System.err( 2966): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
W/System.err( 2966): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err( 2966): 	at dalvik.system.NativeStart.run(Native Method)
I/BatteryController( 1127): status:5 level:100 unsupport:false plugged:true
D/TelephonyReceiver( 1263): switchBindHtcMsgCursor: null
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
D/MediaRouter( 3853): getSelectedRoute
I/NetworkMonitor( 3853): type=WIFI subType= reason=null isConnected=true
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (3853/10154)
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=3853, uid=10154, userID:0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(42debba8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
I/ActivityManager(  906): Resuming delayed broadcast
D/PMS     (  906): releaseWL(42debba8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  906): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=3877 uid=10053 gids={50053, 1028, 1015, 3003, 5012}
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  906): Delay finish: com.htc.musicenhancer/.provider.MScannerReceiver
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.musicenhancer (3877/10053)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.musicenhancer (3877/10053)
,W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_MEDIA due to registered receiver BroadcastFilter{42d10da0 u0 ReceiverList{42d10d40 3877 com.htc.musicenhancer/10053/u0 remote:42d10a48}}
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3877): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,D/PMS     (  906): releaseWL(4218eee0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 4
,D/WIFI_ICON( 1127): WifiActivity: 0
,D/StatusBar.NetworkController( 1127): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{429bbac8 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=3896 uid=10081 gids={50081, 5001, 1028, 1015}
,I/SoundPicker( 3896): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3896): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3896): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3896): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3896): TurnFileToMediaUriService fromMediaScanned = true
,I/SoundPicker( 3896): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
I/ActivityManager(  906): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,D/RingtoneManager( 3896): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,D/RingtoneManager( 3896): MODE_GSM access default DB
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3896): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
,D/RingtoneManager( 3896): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3896): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3896): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3896): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3896): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3896): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3896): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3896): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3896): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3896): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3896): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3896): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3896): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3896): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3896): MODE_GSM access default DB
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
,I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3896): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3896): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
,I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3896): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3896): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
,I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
,I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3896): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3896): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
,I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3896): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3896): getActualDefaultRingtoneUri(context, 4)
,I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
,I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
,I/SoundPicker( 3896): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
,I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
,I/SoundPicker( 3896): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
,I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
,I/SoundPicker( 3896): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/ActivityManager(  906): Resuming delayed broadcast
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
,I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
,I/SoundPicker( 3896): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
,I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
I/SoundPicker( 3896): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,D/DFPI.PIReciver( 3657): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3657): onHandleIntent
,I/DFPI.ApkInstallService( 3657): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3657): check CID = HTC__032
,I/DFPI.ApkInstallService( 3657): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=3332
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3332:com.android.settings:remote/1000 (adj 15): empty #17
,I/SoundPicker( 3896): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3896): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3896): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3896): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3896): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3896): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3896): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3896): MODE_GSM access default DB
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3896): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3896): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3896): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3896): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
,I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3896): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3896): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3896): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3896): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3896): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3896): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3896): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3896): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3896): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3896): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3896): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3896): MODE_GSM access default DB
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
,I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3896): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/ActivityManager(  906): Recipient 3332
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3896): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3896): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3896): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3896): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3896): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3896): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3896): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
I/SoundPicker( 3896): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
I/SoundPicker( 3896): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
I/SoundPi,cker( 3896): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
I/SoundPicker( 3896): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3896): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.htc.task/.TodoTaskReceiver
,I/ActivityManager(  906): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=3916 uid=10064 gids={50064, 3003, 5012, 1023, 1028, 1015}
,D/DFPI.PIReciver( 3657): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3657): onHandleIntent
,I/DFPI.ApkInstallService( 3657): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3657): check CID = HTC__032
,I/DFPI.ApkInstallService( 3657): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,I/EASAppSvc( 3916): [ NA ]- onCreate()
I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/EASAppSvc( 3916): [ NA ]> onUpgrade: version = 63
,D/ORMLib  ( 3673): put()
,I/EASAppSvc( 3916): [ NA ]- onDestroy()
,I/EASAppSvc( 3916): [ NA ]> uninitEASService
,D/WifiService(  906): New client listening to asynchronous messages
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.android.mail (3916/10064)
,D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.htc.android.mail (3916/10064)
,I/ActivityManager(  906): Resuming delayed broadcast
,D/ConnectivityService(  906): getNetworkInfo networkType=55 called by com.htc.android.mail (3916/10064)
I/SoundPicker( 3896): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
W/ContextImpl( 3896): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3896): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3896): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3896): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3896): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3896): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3896): MODE_GSM access default DB
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3896): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3896): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3896): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3896): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3896): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
,D/RingtoneManager( 3896): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3896): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3896): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3896): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3896): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3896): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3896): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3896): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3896): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3896): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3896): MODE_GSM access default DB
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
,I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3896): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/ActivityManager(  906): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3896): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3896): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3896): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3896): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3896): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3896): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3896): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
I/SoundPicker( 3896): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
I/SoundPicker( 3896): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
I/SoundPi,cker( 3896): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
I/SoundPicker( 3896): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
I/SoundPicker( 3896): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3896): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/EASRequestController( 3916): [ NA ]release
,I/EASAppSvc( 3916): [ NA ]< uninitEASService
,I/EASAppSvc( 3916): [ NA ]- onCreate()
,I/EASAppSvc( 3916): [ NA ]> onUpgrade: version = 63
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.android.mail (3916/10064)
D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.htc.android.mail (3916/10064)
D/ConnectivityService(  906): getNetworkInfo networkType=55 called by com.htc.android.mail (3916/10064)
,D/ORMLib  ( 3673): put()
,I/MediaStoreImporter( 3853): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,D/Process (  906): killProcessQuiet, pid=3688
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Killing 3688:com.htc.stock/u0a82 (adj 15): empty #17
,I/EASAppSvc( 3916): [ NA ]- onDestroy()
,I/EASAppSvc( 3916): [ NA ]> uninitEASService
,I/EASRequestController( 3916): [ NA ]release
I/ActivityManager(  906): Recipient 3688
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/EASAppSvc( 3916): [ NA ]< uninitEASService
I/SocialFeedProvider( 1299): +disConnect socialManager
,I/SocialFeedProvider( 1299): disconnect socialManager
I/ActivityManager(  906): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=3956 uid=10068 gids={50068, 3003, 5012}
,I/ActivityManager(  906): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/SocialFeedProvider( 1299): -disConnect socialManager
I/ActivityManager(  906): Resuming delayed broadcast
D/PMS     (  906): acquireWL(42d341b8): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 1538 10014 null
I/ActivityManager(  906): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,D/PMS     (  906): releaseWL(42d341b8): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,D/DFPI.PIReciver( 3657): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/ActivityManager(  906): Resuming delayed broadcast
I/DFPI.ApkInstallService( 3657): onHandleIntent
,I/DFPI.ApkInstallService( 3657): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3657): check CID = HTC__032
,I/DFPI.ApkInstallService( 3657): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,I/SoundPicker( 3896): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3896): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3896): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3896): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3896): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3896): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3896): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3896): MODE_GSM access default DB
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3896): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3896): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3896): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3896): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3896): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3896): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3896): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3896): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
,W/SoundPicker( 3896): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3896): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3896): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3896): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3896): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3896): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3896): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3896): MODE_GSM access default DB
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
,I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3896): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/ActivityManager(  906): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3896): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3896): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3896): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3896): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3896): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
D/ORMLib  ( 3673): put()
I/SoundPicker( 3896): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3896): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
,I/SoundPicker( 3896): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
,I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236,
,I/SoundPicker( 3896): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
,I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
,I/SoundPicker( 3896): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
,I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
,I/SoundPicker( 3896): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3896): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
,I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3896): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
D/WIFI_ICON( 1127): WifiActivity: 1
,D/StatusBar.NetworkController( 1127): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3896): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/MediaStoreImporter( 3853): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
D/TelephonyReceiver( 1263): bind: false
,D/TelephonyReceiver( 1263): switchBindHtcMsgCursor: null
,D/Process (  906): killProcessQuiet, pid=3700
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Killing 3700:com.htc.stock:remote/u0a82 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=3975 uid=10085 gids={50085, 3003, 5012, 1028, 1015, 1023, 2001, 5006, 5001}
,D/Process (  906): killProcessQuiet, pid=3617
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 3617:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/[PluginManager]RegisterService( 1339): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.aurora
,I/[PluginManager]RegisterService( 1339): handle notify Blinkfeed plugin client changed
I/ActivityManager(  906): Recipient 3617
I/ActivityManager(  906): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,I/IcingCorporaProvider( 3077): Updating corpora: APPS=com.htc.aurora, CONTACTS=MAYBE
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Recipient 3700
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/ActivityManager(  906): Delaying start of: ServiceRecord{42d60f90 u0 com.htc.updater/.service.UpdaterCheckIntranetService}
,D/PMS     (  906): acquireWL(42539a98): PARTIAL_WAKE_LOCK  Icing 0x1 2180 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42539a98): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(423c6a20): PARTIAL_WAKE_LOCK  Icing 0x1 2180 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(423c6a20): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(424ddf08): PARTIAL_WAKE_LOCK  Icing 0x1 2180 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(424ddf08): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42b30bc8): PARTIAL_WAKE_LOCK  Icing 0x1 2180 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42b30bc8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(429c3458): PARTIAL_WAKE_LOCK  Icing 0x1 2180 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(429c3458): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42a0e868): PARTIAL_WAKE_LOCK  Icing 0x1 2180 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(42a0e868): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1118): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [ScoreAP] + current TXpacket:54, mTXpacketCount:47, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  906): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
D/PMS     (  906): acquireWL(42a84b50): PARTIAL_WAKE_LOCK  Icing 0x1 2180 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(42a84b50): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(429c0148): PARTIAL_WAKE_LOCK  Icing 0x1 2180 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(429c0148): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(427b4168): PARTIAL_WAKE_LOCK  Icing 0x1 2180 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(427b4168): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42b528c0): PARTIAL_WAKE_LOCK  Icing 0x1 2180 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42b528c0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 3077): UpdateCorporaTask done [took 316 ms] updated apps [took 316 ms] 
,I/RemoteViews( 1127): com.htc.updater (true,33751552)
,D/DotMatrix( 1590): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false
V/AlarmManager(  906): sending alarm PendingIntent{429eed88: PendingIntentRecord{42ac6ad0 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1454420766803, Int=0
D/NotificationService(  906): notification sound not played, stream=5 volume=0 always=false
,I/SocialManager[SocialBiLogHelper]( 3717): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 3717): last commit ulog time 1454392527077
,I/SocialManager[SocialBiLogHelper]( 3717): skip commit this time
,D/OnDemandProgressBar( 1127): release indeterminate drawable android.widget.OnDemandProgressBar{420f28d8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1127): com.htc.updater 2 14 1 10
,I/RemoteViews( 1127): com.htc.updater (true,33751552)
I/ActivityManager(  906): Resuming delayed broadcast
,D/OnDemandProgressBar( 1127): release indeterminate drawable android.widget.OnDemandProgressBar{421f71f0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1127): com.htc.updater 1 7 1 10
I/ActivityManager(  906): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=3998 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,I/ActivityManager(  906): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  906): acquireWL(42a4e4d8): PARTIAL_WAKE_LOCK  AsyncService 0x1 3998 10160 null
,D/PMS     (  906): releaseWL(42a4e4d8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): acquireWL(42a03ed8): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 3998 10160 null
,I/ActivityManager(  906): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4026 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,D/Process (  906): killProcessQuiet, pid=3630
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 3630:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,D/PMS     (  906): acquireWL(42cb8640): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 3998 10160 null
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(42a03ed8): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (3998/10160)
,E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (3998/10160)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
,W/dalvikvm( 4026): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/Settings:HtcWirelessFeatureFlags( 3797): id/is att sku: 99/false
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4026, uid=10074, userID:0
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3630
,W/SystemReader( 3797): Cannot find devicepolicy_lower_fp_quality, use default value instead
,W/SystemReader( 3797): Cannot find support_harman, use default value instead
,W/SystemReader( 3797): Cannot find effect_manager_id, use default value instead
,D/Finsky  ( 4026): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (4026/10074)
,E/Settings:HtcWrapHeaderInfo( 3797): no such activity!
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3797): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3797): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 3797): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3797): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3797): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3797): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3797): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3797): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3797): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3797): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3797): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3797): [supportHomeButton]support         :false
,W/dalvikvm( 4026): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,W/FingerprintManager( 3797): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
D/PMS     (  906): releaseWL(42cb8640): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
,E/Settings:HtcVoWifiWidgetEnabler( 3797): isSupportVoWifi: null
,W/dalvikvm( 4026): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
I/ActivityManager(  906): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3797): Failed to find provider info for com.htc.vowifi
D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (4026/10074)
,D/Finsky  ( 4026): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/dalvikvm( 4026): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,W/Settings( 4026): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4026): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/dalvikvm( 4026): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4026): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4026): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4026): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4026, uid=10074, userID:0
,D/Ads     ( 4026): Skipping gmscore version check
,D/Finsky  ( 4026): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4026): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 4026): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/dalvikvm( 4026): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3797): The wrap header doesn't exist in header list.
E/Settings:HtcWrapHeaderInfo( 3797): updateDevelopment, bPrefShow = true
E/Settings:HtcUmcWidgetEnabler( 3797): isSupportMusicChannel(): false
I/ActivityManager(  906): Delay finish: com.android.vending/com.google.android.finsky.widget.consumption.NowPlayingWidgetProvider
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3797): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3797): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3797): [supportRecentAppsButton]support         :false
D/Finsky  ( 4026): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3797): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3797): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3797): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3797): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3797): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3797): [supportHomeButton]support         :false
D/Process (  906): killProcessQuiet, pid=3733
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Killing 3733:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
W/FingerprintManager( 3797): hasFingerprint() - sSensorCode = 0
E/Settings:HtcVoWifiWidgetEnabler( 3797): isSupportVoWifi: null
D/PackageBroadcastService( 2180): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.aurora
I/ActivityManager(  906): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
I/ActivityManager(  906): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3797): Failed to find provider info for com.htc.vowifi
,D/PMS     (  906): acquireWL(42d5df50): PARTIAL_WAKE_LOCK  Icing 0x1 2180 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42d5df50): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42d340c8): PARTIAL_WAKE_LOCK  Icing 0x1 2180 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42d340c8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42d25f58): PARTIAL_WAKE_LOCK  Icing 0x1 2180 10029 WorkSource{10029 com.google.android.gms}
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3733
,W/dalvikvm( 2180): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
,W/dalvikvm( 2180): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 2180): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
W/dalvikvm( 2180): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 2180): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
W/dalvikvm( 2180): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
,W/dalvikvm( 2180): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2180, uid=10029, userID:0
,I/PeopleDatabaseHelper( 2180): cleanUpNonGplusAccounts done.
,I/Icing   ( 2180): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/HtcModeClient( 1538): handler message = 4011
,E/HtcModeClient( 1538): Check connection and retry 5 times.
,I/Icing   ( 2180): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
D/PMS     (  906): releaseWL(42d25f58): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4071 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/Babel   ( 4071): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4071): MmsConfig.loadMmsSettings
,W/dalvikvm( 4071): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4071): VFY: unable to resolve instance field 36
,W/dalvikvm( 4071): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4071): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/MmsCustomizationProvider( 2966): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 2966): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/Babel   ( 4071): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4071): MmsConfig.loadFromDatabase
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4071, uid=10111, userID:0
W/Settings( 4071): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Babel   ( 4071): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4071): MmsConfig.loadFromResources
,E/Babel   ( 4071): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4071): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4071, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4071, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4071, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4071, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4071, uid=10111, userID:0
D/PMS     (  906): acquireWL(4293dcd8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4071 10111 null
I/ActivityManager(  906): Delay finish: com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver
,D/PMS     (  906): releaseWL(4293dcd8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=3747
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3747:com.htc.mobiledata/u0a91 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3747
,I/[PluginManager]RegisterService( 1339): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1339): handle notify Blinkfeed plugin client changed
I/ActivityManager(  906): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,I/IcingCorporaProvider( 3077): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/ProviderInstaller( 4071): Installed default security provider GmsCore_OpenSSL
D/PMS     (  906): acquireWL(42727b58): PARTIAL_WAKE_LOCK  Icing 0x1 2180 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42727b58): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(428bbb00): PARTIAL_WAKE_LOCK  Icing 0x1 2180 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(428bbb00): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(429af178): PARTIAL_WAKE_LOCK  Icing 0x1 2180 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(429af178): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42ada550): PARTIAL_WAKE_LOCK  Icing 0x1 2180 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42ada550): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(429fb1d8): PARTIAL_WAKE_LOCK  Icing 0x1 2180 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(429fb1d8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(429316f0): PARTIAL_WAKE_LOCK  Icing 0x1 2180 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(429316f0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4256d360): PARTIAL_WAKE_LOCK  Icing 0x1 2180 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(4256d360): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 3077): UpdateCorporaTask done [took 227 ms] updated apps [took 227 ms] 
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  906): acquireWL(42999318): PARTIAL_WAKE_LOCK  AsyncService 0x1 3998 10160 null
,D/PMS     (  906): releaseWL(42999318): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PackageBroadcastService( 2180): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2180): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  906): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/PMS     (  906): acquireWL(42bd7f50): PARTIAL_WAKE_LOCK  Icing 0x1 2180 10029 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 2180): updateResources: need to parse f{com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1118): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,I/HtcKeyguardAppUpdateMonitor( 1127): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
,I/HtcKeyguardAppUpdateMonitor( 1127): ApplicationsIntentReceiver packageName:com.google.android.gms
,D/AccTypeManager( 1379): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/HtcKeyguardAppUpdateMonitor( 1127): ApplicationsIntentReceiver replacing:false
,W/SystemReader( 1278): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
,I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1263 :
W/AccTypeManager( 1379): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1379): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/Prism.ItemManager( 3717): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Prism.ItemManager( 3717): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/dalvikvm-heap( 1299): Grow heap (frag case) to 13.211MB for 53840-byte allocation
,I/Prism.ItemManager( 1299): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1299): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1299): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "smsto"
,I/Icing   ( 2180): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1263 :
,E/ExternalAccountType( 1379): Unsupported attribute readOnly
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1263 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1263 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1263 :
,D/Icing   ( 2180): Loaded CLD2 Version V2.0 - 20141016
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1263 :
,I/Icing   ( 2180): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1263 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1263 :
,D/PhoneApp( 1263): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): releaseWL(42bd7f50): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Start proc com.google.android.gm for broadcast com.google.android.gm/.MailIntentReceiver: pid=4110 uid=10107 gids={50107, 3003, 5012, 1028, 1015}
,D/Process (  906): killProcessQuiet, pid=3776
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3776:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3776
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  906): Client connection lost with reason: 4
,W/GAV2    ( 4110): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/PackageManager(  906): Unable to load service info ResolveInfo{42c197e8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  906): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  906): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  906): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  906): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  906): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  906): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  906): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  906): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  906): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  906): 	at dalvik.system.NativeStart.main(Native Method)
,D/PMS     (  906): acquireWL(42d43118): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4071 10111 null
,I/ActivityManager(  906): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,D/PMS     (  906): acquireWL(42c55970): PARTIAL_WAKE_LOCK  Icing 0x1 2180 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42c55970): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): acquireWL(42b544c0): PARTIAL_WAKE_LOCK  Icing 0x1 2180 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42b544c0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42d43118): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/Process (  906): killProcessQuiet, pid=3818
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3818:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,D/AutoSetting( 1339): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 1339): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1339): service - requestNLP() NetworkLocationProvider not enabled
,D/AutoSetting( 1339): service - mHandler: update timezone
,I/ActivityManager(  906): Recipient 3818
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/RemoteDisplayProvider(  906): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  906): start
,D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
,D/PMS     (  906): acquireWL(42dd6b78): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4071 10111 null
,D/PMS     (  906): releaseWL(42dd6b78): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/PMS     (  906): acquireWL(42d25728): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1396 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): Done.
,D/ConnectivityService(  906): Setting timer for 720seconds
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1396/10029)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031187
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031351
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031596
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031601
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031605
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031608
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033590
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033602
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360036074
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
,I/GCoreNlp( 1247): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
V/AlarmManager(  906): sending alarm PendingIntent{42de6350: PendingIntentRecord{42c497d8 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1454420770633, Int=0
D/PMS     (  906): releaseWL(42d25728): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42dc32b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1396 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1396/10029)
,D/PMS     (  906): acquireWL(42ca0868): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1247 10029 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(42ca0868): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031187
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031351
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031596
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031601
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031605
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031608
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033590
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033602
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360036074
,E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(42dc32b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42c6ad68): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1247 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42c6ad68): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/LocationProviderProxy(  906): applying state to connected service
D/LocationProviderProxy(  906): applying state to connected service
,I/Gmail   ( 4110): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 4110): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/GCM     ( 1396): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  906): acquireWL(42c9e598): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1247 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(42c58428): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1247 10029 WorkSource{10029 com.google.android.gms}
,I/Gmail   ( 4110): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 4110): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/PMS     (  906): releaseWL(42c58428): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(42c9e598): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,W/GCoreFlp( 1247): No location to return for getLastLocation()
,W/FusedLocationProvider( 1247): location=null
D/PMS     (  906): acquireWL(42c45870): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1247 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(42c45870): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031187
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031351
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031596
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031601
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031605
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031608
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033590
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033602
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360036074
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2180/10029)
,D/PMS     (  906): acquireWL(42d0f7a8): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 2180 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42cbf750): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1396 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1396/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031187
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031351
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031596
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031601
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031605
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031608
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033590
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033602
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360036074
,D/PMS     (  906): releaseWL(42cbf750): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(42c7e600): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1396 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1396/10029)
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031187
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031351
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031596
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031601
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031605
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031608
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033590
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033602
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360036074
D/PMS     (  906): releaseWL(42c7e600): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(42c3fc78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1396 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1396/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031187
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031351
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031596
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031601
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031605
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031608
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033590
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033602
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360036074
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(42c3fc78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
D/PMS     (  906): acquireWL(42c3afe8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1396 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1396/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031187
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031351
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031596
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031601
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031605
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031608
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033590
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033602
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360036074
,E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(42c3afe8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42d0f7a8): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42c82a18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1396 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForAndroidIntent: pid=4153 uid=10041 gids={50041}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1396/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031187
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031351
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031596
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031601
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031605
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031608
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033590
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033602
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360036074
,E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(42c82a18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
,D/Process (  906): killProcessQuiet, pid=3642
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 3642:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
,D/PMS     (  906): acquireWL(42dbe6b8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3673 10071 null
I/ActivityManager(  906): Recipient 3642
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(42db9f08): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3673 10071 null
,D/PMS     (  906): releaseWL(42dbe6b8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
E/TodoTaskNotifyService( 3673): java.lang.NullPointerException
W/System.err( 3673): java.lang.NullPointerException
I/WSP     ( 1339): [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
W/System.err( 3673): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3673): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3673): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3673): 	at android.os.Looper.loop(Looper.java:157)
W/System.err( 3673): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/WeatherUtility( 1339): Weather sync is On
,W/NotifyReceiver( 3673): stopSelfResult true
,I/WSP     ( 1339): [Receiver] next auto-sync alarm event is 60 mins later, at time: Tue Feb 02 15:46:11 CET 2016
D/PMS     (  906): releaseWL(42db9f08): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1339/10055)
I/ActivityManager(  906): Delay finish: com.htc.task/.TodoReceiver
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1339/10055)
D/PMS     (  906): acquireWL(42d057d8): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 1339 10055 null
,D/TodoTaskshortcut( 3673): update TASK shortcut>
,W/MediaManager( 3835): [DualLensScanUtil]	mmpCursor count is 0
,I/Prism.ItemManager( 3717): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 3717): loadItems() com.htc.launcher.pageview.WidgetManager@4213fc90 +
,I/Prism.WidgetManager( 3717): onLoadItems() +
I/Prism.ItemManager( 1299): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1299): loadItems() com.htc.launcher.pageview.WidgetManager@4215ec98 +
,I/Prism.WidgetManager( 1299): onLoadItems() +
,I/SensorManager(  906): mEventCount = 450
,E/Prism.WidgetManager( 1299): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1299): onLoadItems() -
,I/Prism.ItemManager( 1299): loadItems() com.htc.launcher.pageview.WidgetManager@4215ec98 -
,I/Prism.WidgetManager( 3717): onLoadItems() -
,I/Prism.ItemManager( 3717): loadItems() com.htc.launcher.pageview.WidgetManager@4213fc90 -
,D/PhoneApp( 1263): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1263): -- N1 =0
,D/PhoneApp( 1263): -- N2 =0
,D/PhoneApp( 1263): -- N3 =0
,V/AlarmManager(  906): sending alarm PendingIntent{42b24170: PendingIntentRecord{42dd2ca0 com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1454420772321, Int=0
,I/iu.UploadsManager( 2180): End new media; added: 0, uploading: 0, time: 57 ms
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1118): WiFioffload: SignalStrength: =97,
,D/WifiNative-wlan0(  906):    returned true
,V/AlarmManager(  906): sending alarm PendingIntent{4227bd78: PendingIntentRecord{42ad2770 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=71088, Int=0
,I/HtcModeClient( 1538): handler message = 4011
,E/HtcModeClient( 1538): Check connection and retry 6 times.
,I/GAV4    ( 4071): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  906): acquireWL(42b9f6d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42b9f6d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1127): closing low battery warning: level=100
,D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1127): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1127): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1127): status:5 level:100 unsupport:false plugged:true
,I/GAV2    ( 4110): Thread[GAThread,5,main]: No campaign data found.
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1118): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/Process (  906): killProcessQuiet, pid=3916
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3916:com.htc.android.mail:sync/u0a64 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3916
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  906): Client connection lost with reason: 4
,I/CalendarProvider2( 1538): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 1538): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): acquireWL(42d2ed78): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 3853 10154 null
,I/ActivityManager(  906): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,W/ContextImpl( 3853): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=3853, uid=10154, userID:0
,I/MusicLeanback( 3853): Conditions not met for autocaching.
,I/MusicLeanback( 3853): Stop autocaching.
,W/ContextImpl( 3853): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/PMS     (  906): releaseWL(42d2ed78): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/ActivityManager(  906): Resuming delayed broadcast
D/PMS     (  906): acquireWL(42a53358): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4071 10111 null
I/ActivityManager(  906): Delay finish: com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver
,D/PMS     (  906): releaseWL(42a53358): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,I/[PluginManager]RegisterService( 1339): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1339): handle notify Blinkfeed plugin client changed
,I/IcingCorporaProvider( 3077): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/PMS     (  906): acquireWL(42d98fb0): PARTIAL_WAKE_LOCK  Icing 0x1 2180 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42d98fb0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42c15448): PARTIAL_WAKE_LOCK  Icing 0x1 2180 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42c15448): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42d61510): PARTIAL_WAKE_LOCK  Icing 0x1 2180 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42d61510): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42a40950): PARTIAL_WAKE_LOCK  Icing 0x1 2180 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42a40950): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42c98140): PARTIAL_WAKE_LOCK  Icing 0x1 2180 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42c98140): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42cd5870): PARTIAL_WAKE_LOCK  Icing 0x1 2180 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42cd5870): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42afc220): PARTIAL_WAKE_LOCK  Icing 0x1 2180 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42afc220): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42d9bd88): PARTIAL_WAKE_LOCK  Icing 0x1 2180 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42d9bd88): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42bf4878): PARTIAL_WAKE_LOCK  Icing 0x1 2180 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42bf4878): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 3077): UpdateCorporaTask done [took 282 ms] updated apps [took 282 ms] 
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  906): acquireWL(429b80a8): PARTIAL_WAKE_LOCK  AsyncService 0x1 3998 10160 null
,D/PMS     (  906): releaseWL(429b80a8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PackageBroadcastService( 2180): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2180): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  906): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/PMS     (  906): acquireWL(429b03b8): PARTIAL_WAKE_LOCK  Icing 0x1 2180 10029 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 2180): updateResources: need to parse f{com.google.android.gms}
,D/WIFI_ICON( 1127): WifiActivity: 0
,D/StatusBar.NetworkController( 1127): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/Icing   ( 2180): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2180): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  906): releaseWL(429b03b8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,V/AlarmManager(  906): sending alarm PendingIntent{42a840a0: PendingIntentRecord{42b3b9b8 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=75926, Int=0
,W/MediaManager( 3835): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.google.android.gm/.MailIntentReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,D/AutoSetting( 1538): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1538): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1538): service - onCreate()
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
I/ActivityManager(  906): Delay finish: com.htc.htclocationservice/.AutoSettingReceiver
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1538): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1538): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/AutoSetting( 1538): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1538): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1538): service - mHandler: update timezone
,D/AutoSetting( 1538): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1538): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1538): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1538): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1590): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1590): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1127): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1127): release indeterminate drawable android.widget.OnDemandProgressBar{4227efc0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1127): com.htc.htclocationservice 1 6 3 11
,I/HtcModeClient( 1538): handler message = 4011
,E/HtcModeClient( 1538): Check connection and retry 7 times.
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
,D/WIFI_ICON( 1127): WifiActivity: 1
,E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
,D/StatusBar.NetworkController( 1127): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1118): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
,D/WIFI_ICON( 1127): WifiActivity: 0
,D/StatusBar.NetworkController( 1127): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{42d3ad30 u0 com.htc.musicenhancer/.EnhancerService}
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4204 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/SyncApplication( 4204): Loading default preferences
,W/Resources( 4204): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WifiService(  906): New client listening to asynchronous messages
,D/SyncApplication( 4204): Overriding preferences with custom values
,D/SyncApplication( 4204): Updating preferences succeeded
,E/SyncApplication( 4204): Application created.
D/VolumeInfo( 4204): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 4204): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 4204): Found 0 mount point(s)
,V/VolumeInfo( 4204): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 4204): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,D/VolumeInfo( 4204): Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
,W/VolumeInfo( 4204): Can not create volume ID for unmounted volume null
,I/CalendarDefines( 4204): getNewCalendarAuthority()...
,D/SyncApplication( 4204): enableAppOperation()+
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=4204, uid=10008, userID:0
W/PackageManager(  906): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=4204, uid=10008, userID:0
,W/PackageManager(  906): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
D/SyncApplication( 4204): enableAppOperation()-
D/HTCUtilities( 4204): isNeorSinged() + 
,D/HTCUtilities( 4204): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 4204): isNeorSinged() return false
,D/CDMountReceiver( 4204): whether to enable CD Auto-mount: true
,D/CDMountReceiver( 4204): showNotification() contentText=If HTC Sync Manager setup doesnt start automatically on your computer, download from www.htc.com/hsm
,D/CDMountReceiver( 4204): enable CD Auto-mount: true
,D/DotMatrix( 1590): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
,I/ActivityManager(  906): Delay finish: com.nero.android.htc.sync/.CDMountReceiver
D/HTCUtilities( 4204): enable auto-mount
D/HTCUtilities( 4204): enable auto-mount
,I/RemoteViews( 1127): com.nero.android.htc.sync (false,0)
D/MountService(  906): mountISO: /system/etc/PCTOOL.ISO
I/ActivityManager(  906): Resuming delayed broadcast
,D/OnDemandProgressBar( 1127): release indeterminate drawable android.widget.OnDemandProgressBar{420f8d08 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/MountService(  906): mountISO: /system/etc/PCTOOL.ISO
I/RemoteViews.Performance( 1127): com.nero.android.htc.sync 3 13 3 11
I/RemoteViews( 1127): com.nero.android.htc.sync (false,0)
,D/OnDemandProgressBar( 1127): release indeterminate drawable android.widget.OnDemandProgressBar{424ec110 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1127): com.nero.android.htc.sync 1 8 3 16
,D/PMS     (  906): acquireWL(42a97598): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1396 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1396/10029)
I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031187
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031351
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031596
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031601
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031605
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031608,
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033590
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033602
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360036074
,D/PMS     (  906): releaseWL(42a97598): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42a4eaa8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1396 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1396/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031187
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031351
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031596
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031601
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031605
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031608
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033590
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033602
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360036074
,D/PMS     (  906): releaseWL(42a4eaa8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42a31720): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1396 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1396/10029)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  906): acquireWL(42a30c00): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
I/ActivityManager(  906): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=4225 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031187
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031351
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031596
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031601
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031605
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031608
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033590
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033602
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360036074
D/PMS     (  906): acquireWL(424ba400): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/PMS     (  906): releaseWL(42a30c00): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  906): releaseWL(424ba400): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  906): releaseWL(42a31720): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/CalendarApplication( 4225): onCreate
D/ProviderChangeReceiver( 4225): ---------------------------------------------------
,D/ProviderChangeReceiver( 4225): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 4225): start to updateAlertNotification!
,I/ActivityManager(  906): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=4239 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  906): killProcessQuiet, pid=3956
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 3956:com.htc.task.gtask/u0a68 (adj 15): empty #17
,D/AlertService( 4225): No fired or scheduled alerts
,D/HtcAlertUtils( 4225): -- cancelReminderNotification --
,D/HtcAlertUtils( 4225): broadcastExistReminder!
I/ActivityManager(  906): Recipient 3956
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,V/Settings:HtcSettingsApplication( 4239): [4239/4239] onCreate()
W/ContextImpl( 4239): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  906): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
,D/WifiDataStallTracker(  906): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  906): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
I/ActivityManager(  906): Resuming delayed broadcast
D/WifiDataStallTracker(  906): updateDataStallInfo: mDataStallTxRxSum={txSum=31 rxSum=29} preTxRxSum={txSum=31 rxSum=29}
D/WifiDataStallTracker(  906): updateDataStallInfo: NONE
,D/WifiDataStallTracker(  906): onDataStallAlarm: tag=21997 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=21998 delay=15s
,D/Process (  906): killProcessQuiet, pid=3657
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
D/PMS     (  906): releaseWL(42cfc190): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
I/ActivityManager(  906): Killing 3657:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3657
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WIFI_ICON( 1127): WifiActivity: 1
,D/StatusBar.NetworkController( 1127): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  906): releaseWL(42d057d8): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null
,D/Process (  906): killProcessQuiet, pid=3896
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3896:com.htc.sdm/u0a81 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3896
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1118): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): [ScoreAP] + current TXpacket:54, mTXpacketCount:54, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  906): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,I/SensorManager(  906): mEventCount = 600
,I/HtcModeClient( 1538): handler message = 4011
,E/HtcModeClient( 1538): Check connection and retry 8 times.
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97,
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1118): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true,
,D/WIFI_ICON( 1127): WifiActivity: 0
,D/StatusBar.NetworkController( 1127): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1127): WifiActivity: 1
,D/StatusBar.NetworkController( 1127): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1118): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,I/HtcModeClient( 1538): handler message = 4011
,E/HtcModeClient( 1538): Check connection and retry 9 times.
,D/Finsky  ( 4026): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,W/dalvikvm( 4026): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;,
D/PMS     (  906): acquireWL(42c366c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10074}
V/AlarmManager(  906): sending alarm PendingIntent{42a88308: PendingIntentRecord{429a1af0 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454420789342, Int=0
D/PMS     (  906): releaseWL(42c366c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.vending (4026/10074)
,V/GLSActivity( 1396): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1396): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4026): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4026): [NET] getaddrinfo-,err=8
D/libc    ( 4026): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 4026): [NET] getaddrinfo-, 1
,D/libc    ( 4026): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =4ba3 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4026): [NET] getaddrinfo_proxy-, success
I/global  ( 4026): call createSocket() return a new socket.
D/libc    ( 4026): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4026): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4026): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4,
,D/libc    ( 4026): [NET] getaddrinfo-,err=8
,D/WIFI_ICON( 1127): WifiActivity: 3
,D/StatusBar.NetworkController( 1127): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,V/GLSActivity( 1396): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1396): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4026): untagSocket(69) failed with errno -22
,D/Finsky  ( 4026): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,V/GLSActivity( 1396): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1396): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4026): untagSocket(69) failed with errno -22
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 5
,D/AutoSetting( 1339): service - handleMessage() stop self
,D/AutoSetting( 1339): service - handleMessage() quit looper
,D/AutoSetting( 1339): service - onDestroy() END
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=20 [20][4][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1118): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,V/GLSActivity( 1396): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1396): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4026): untagSocket(69) failed with errno -22
,D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.android.vending (4026/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4026/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4026/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4026/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4026/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4026/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4026/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4026/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4026/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4026/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4026/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4026/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4026/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4026/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4026/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4026/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4026/10074)
,D/Finsky  ( 4026): [1] DailyHygiene.access$600: Logging device features
,D/PMS     (  906): acquireWL(42d09df8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10074}
,V/AlarmManager(  906): sending alarm PendingIntent{42dab5c0: PendingIntentRecord{42dd22f8 com.android.vending broadcastIntent}}, i=null, t=0, cnt=1, w=1454420791410, Int=0
,D/WearableService( 1247): callingUid 10029, callindPid: 1247
D/PMS     (  906): acquireWL(42b4ba08): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 4026 10074 null
,D/Finsky  ( 4026): [426] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/DeviceConnectionService( 1247): client connected with version: 8296000
I/ActivityManager(  906): Delay finish: com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver
,D/Finsky  ( 4026): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 4026): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): releaseWL(42d09df8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,V/GLSActivity( 1396): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1396): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4026): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4026): [NET] getaddrinfo-,err=8
D/libc    ( 4026): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4026): [NET] getaddrinfo-, 1
,D/libc    ( 4026): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =e8f6 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 279
D/libc    (  365): [NET]res_nsend:resplen=87
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS,
,D/libc    ( 4026): [NET] getaddrinfo_proxy-, success,
,D/PMS     (  906): releaseWL(42b4ba08): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 null
,D/Process (  906): killProcessQuiet, pid=3975
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3975:com.htc.updater/u0a85 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3975
,D/ContactMessageStore( 1263): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1263): MSG_NOTIFY_CS_TO_SYNC <<
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{42dd0578 u0 com.htc.htclocationservice/.AutoSettingService}
,I/HtcModeClient( 1538): handler message = 4011
,E/HtcModeClient( 1538): Check connection and retry 10 times.
,D/WIFI_ICON( 1127): WifiActivity: 1
,D/StatusBar.NetworkController( 1127): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=3 [53][2][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1118): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true,
,D/WIFI_ICON( 1127): WifiActivity: 0
,D/StatusBar.NetworkController( 1127): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiDataStallTracker(  906): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  906): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  906): updateDataStallInfo: mDataStallTxRxSum={txSum=103 rxSum=93} preTxRxSum={txSum=31 rxSum=29}
D/WifiDataStallTracker(  906): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  906): onDataStallAlarm: tag=21998 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=21999 delay=15s
D/PMS     (  906): acquireWL(42bc44d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{42aafbb0: PendingIntentRecord{42b3b9b8 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=93342, Int=0
D/PMS     (  906): releaseWL(42bc44d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42d97868): PARTIAL_WAKE_LOCK  Icing 0x1 2180 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42d97868): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42bbe530): PARTIAL_WAKE_LOCK  Icing 0x1 2180 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42bbe530): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms},
,D/PMS     (  906): acquireWL(42db9920): PARTIAL_WAKE_LOCK  Icing 0x1 2180 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42db9920): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42cb0880): PARTIAL_WAKE_LOCK  Icing 0x1 2180 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42cb0880): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42d5ad78): PARTIAL_WAKE_LOCK  Icing 0x1 2180 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42d5ad78): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/WIFI_ICON( 1127): WifiActivity: 1
,D/StatusBar.NetworkController( 1127): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1118): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): [ScoreAP] + current TXpacket:134, mTXpacketCount:54, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  906): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,I/HtcModeClient( 1538): handler message = 4011
,E/HtcModeClient( 1538): Check connection and retry 11 times.
,D/WIFI_ICON( 1127): WifiActivity: 0
,D/StatusBar.NetworkController( 1127): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1118): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WIFI_ICON( 1127): WifiActivity: 1
,D/StatusBar.NetworkController( 1127): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/SensorManager(  906): mEventCount = 750
,D/WIFI_ICON( 1127): WifiActivity: 0
,D/StatusBar.NetworkController( 1127): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1118): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/HtcModeClient( 1538): handler message = 4011
,E/HtcModeClient( 1538): Check connection and retry 12 times.
,D/WIFI_ICON( 1127): WifiActivity: 1
,D/StatusBar.NetworkController( 1127): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1127): WifiActivity: 0
,D/StatusBar.NetworkController( 1127): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1118): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WIFI_ICON( 1127): WifiActivity: 1
,D/StatusBar.NetworkController( 1127): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1127): WifiActivity: 0
,D/StatusBar.NetworkController( 1127): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/AutoSetting( 1538): service - handleMessage() stop self
,D/AutoSetting( 1538): service - onDestroy() END
,D/AutoSetting( 1538): service - handleMessage() quit looper
,I/HtcModeClient( 1538): handler message = 4011
,E/HtcModeClient( 1538): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1538): Don't start project servcice
,D/HtcModeClient( 1538): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1538): connectState: CONNECTION_READY = false
,D/SilentMusic( 1538): call stop
,D/HtcModeClient( 1538): close connection
,W/HtcModeClient( 1538): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1538): read the terminate packet, so break
,D/Process (  906): killProcessQuiet, pid=3717
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3717:com.htc.sense.news/u0a76 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3717
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1118): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WIFI_ICON( 1127): WifiActivity: 1
,D/StatusBar.NetworkController( 1127): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  906): acquireWL(42d52bb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10074}
,V/AlarmManager(  906): sending alarm PendingIntent{42b7b5c8: PendingIntentRecord{42c28d30 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454420805652, Int=0
,I/ActivityManager(  906): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4268 uid=10078 gids={50078}
V/AlarmManager(  906): sending alarm PendingIntent{42b21510: PendingIntentRecord{42b71260 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1454420810021, Int=60000
,D/PMS     (  906): releaseWL(42d52bb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
,D/SMSBackup( 4268): SMSBackupAgentService started
,D/SMSBackup( 4268): Checking restore status
,D/SMSBackup( 4268): Restore complete
,D/SMSBackup( 4268): cancelCheckAlarm
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031187
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031351
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031596
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031601
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031605
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031608
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033590
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033602
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360036074
D/SMSBackup( 4268): SMSBackupAgentService completed: completed in 0.0 seconds
,D/WifiDataStallTracker(  906): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  906): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/PMS     (  906): acquireWL(42d51378): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
D/WifiDataStallTracker(  906): updateDataStallInfo: mDataStallTxRxSum={txSum=103 rxSum=93} preTxRxSum={txSum=103 rxSum=93}
D/WifiDataStallTracker(  906): updateDataStallInfo: NONE
,D/WifiDataStallTracker(  906): onDataStallAlarm: tag=21999 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=22000 delay=15s
V/AlarmManager(  906): sending alarm PendingIntent{42bdcd80: PendingIntentRecord{42b3b9b8 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=108347, Int=0
D/PMS     (  906): releaseWL(42d51378): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Finsky  ( 4026): [416] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4026): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/Process (  906): killProcessQuiet, pid=2966
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 2966:com.htc.sense.mms/u0a65 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 2966
,D/WIFI_ICON( 1127): WifiActivity: 0
,D/StatusBar.NetworkController( 1127): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1118): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [ScoreAP] + current TXpacket:134, mTXpacketCount:134, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  906): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,V/LightsService(  906): setLight #0: color=#3f
,V/LightsService(  906): setLight #0: color=#3c
,V/LightsService(  906): setLight #0: color=#35
,V/LightsService(  906): setLight #0: color=#2f
,V/LightsService(  906): setLight #0: color=#28
,V/LightsService(  906): setLight #0: color=#21
,V/LightsService(  906): setLight #0: color=#1b
,V/LightsService(  906): setLight #0: color=#14
,D/WIFI_ICON( 1127): WifiActivity: 1
,D/StatusBar.NetworkController( 1127): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1127): WifiActivity: 0
,D/StatusBar.NetworkController( 1127): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1118): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WIFI_ICON( 1127): WifiActivity: 1
,D/StatusBar.NetworkController( 1127): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1127): WifiActivity: 0
,D/StatusBar.NetworkController( 1127): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/SensorManager(  906): mEventCount = 900
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1118): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WIFI_ICON( 1127): WifiActivity: 1
,D/StatusBar.NetworkController( 1127): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/PMS     (  906): Going to sleep due to screen timeout...
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42754880
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = CM36282 Light sensor
D/WirelessDisplayService(  906): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  906): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42754880, eanble = 0, strlen(mName) = 59
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  906): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4254bca0
W/SensorService(  906): Listener[1] = com.htc.smartdim.sensor_eye@428ddf30
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/PMS     (  906): mWirelessDisplayManager is null
W/BatSI   (  906): Couldn't get kernel wake lock stats
V/LightsService(  906): setLight #2: color=#0
D/qdlights(  906): set_light_buttons_func: on=0 brightness=0
V/LightsService(  906): setLight #0: color=#0
,D/SurfaceControl(  906): Excessive delay in blankDisplay() while turning screen off: 347ms
,W/PnPMgr  (  358): Write '/proc/sys/kernel/sched_boost' failed (Invalid argument)
D/PMS     (  906): nativeSetInteractive:false
D/PMS     (  906): nativeSetInteractive:false done
D/PMS     (  906): nativeSetAutoSuspend:true
D/PMS     (  906): nativeSetAutoSuspend:true done
D/HABCtrl (  906): TPE algorithm. remove timeout.
I/InputManager(  906): Cancel all due to getting PMS screen off broadcast
D/PMS     (  906): OOBE c monitor 11
I/InputMethodManagerService(  906): screenObserver, isScreenOn=false
D/NfcService( 1278): ScreenObserver: OFF
,D/NfcService( 1278): applyRouting - 0
I/IntentController( 1127): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
V/KeyguardServiceDelegate(  906): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@42d109c8)
,D/NfcService( 1278): applyRouting -2
,V/KeyguardServiceDelegate(  906): **** SHOWN CALLED ****
I/InputMethodManagerService(  906): Disable input method client, pid=1299
D/PMS     (  906): acquireWL(42d10210): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1278 1027 null
D/PMN     (  906): wakingUp
D/PMS     (  906): releaseWL(42d10210): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/WindowManager(  906): No lock screen! windowToken=null
,D/PMN     (  906): onScreenOn
W/XT9_C   ( 1233): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1233): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1233): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1233): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/WirelessDisplayService(  906): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_ON
D/PMS     (  906): acquireWL(42deb788): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
D/AlarmManager(  906): ACTION_SCREEN_ON
I/AlarmManager(  906): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done recovering
I/AlarmManager(  906): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done EPS screen off alarm recovering
,I/BatteryService(  906): n_update end
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=22001 delay=15s
,D/MtpService( 2945): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/PMS     (  906): releaseWL(42deb788): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031187
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031351
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031596
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031601
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031605
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031608
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033590
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033602
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360036074
,D/MtpService( 2945): [MTP][onReceive]-
,D/NfcService( 1278): applyRouting - 0
,I/IntentController( 1127): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/NfcService( 1278): applyRouting -2
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): acquireWL(42d93758): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1278 1027 null
D/PMS     (  906): releaseWL(42d93758): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1118): SET_SCREEN_ON:On
I/wpa_supplicant( 1118): htc_wext_set_keepalive +
I/wpa_supplicant( 1118): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1118): getPrivFuncNum +	
I/wpa_supplicant( 1118): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1118): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1118): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1118): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1118): htc_wext_set_TX_TRACKING - ret = 0
,D/WifiNative-wlan0(  906):    returned true
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
D/PowerUI ( 1127): closing low battery warning: level=100
D/PowerUI ( 1127): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
I/ClockThread( 1127): stop update clock
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4288 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1118): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,V/SRS_Proc(  375): ParamSet string: screen_state=on,
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
D/WIFI_ICON( 1127): WifiActivity: 0
D/StatusBar.NetworkController( 1127): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
V/NotificationService(  906): batLight: Full, plugged,
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,I/BatteryController( 1127): status:5 level:100 unsupport:false plugged:true
,D/NetworkPolicy(  906): updateScreenOn: false
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
W/ContextImpl( 4288): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  906): acquireWL(42d8dfc0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1247 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(42d8dfc0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(42ca3cd8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1247 10029 WorkSource{10029 com.google.android.gms}
,D/SmartSyncUtils( 4288): isEpsOn(), nState = 0
D/PMS     (  906): acquireWL(42ca4d48): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4288 1000 null
D/PMS     (  906): releaseWL(42ca3cd8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1772): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1772): onScreenOn: 1454420819616
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1772): onScreenOn: 1454420819616
,D/PMS     (  906): releaseWL(42ca4d48): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4254bca0
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4254bca0, eanble = 0, strlen(mName) = 91
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  906): Listener[0] = com.htc.smartdim.sensor_eye@428ddf30
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  906): goingToSleep
,D/SmartSyncUtils( 4288): getMobilePolicyEnabled, result = true
,I/FeedHostManager( 1299): [onPause]
I/FeedProviderManager( 1299): onPause
,I/FeedHostManager( 1299): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@421bd190
I/SocialFeedProvider( 1299): +onPause
,I/SocialFeedProvider( 1299): -onPause
D/PMS     (  906): acquireWL(42cf6410): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 906 1000 null
,D/AlarmManager(  906): ACTION_SCREEN_OFF
I/AlarmManager(  906): [AlarmQueuing] screen off now: 
I/AlarmManager(  906): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=22001 mDataStallAlarmIntent=PendingIntent{42a0f200: PendingIntentRecord{42b3b9b8 android broadcastIntent}}
I/AlarmManager(  906): [AlarmQueuing] wifi connection: true
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031187
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031351
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031596
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031601
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031605
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031608
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033590
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033602
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360036074
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/Process (  906): killProcessQuiet, pid=4153
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4153:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 0
D/WifiNative-wlan0(  906): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1118): SET_SCREEN_ON:Off
I/wpa_supplicant( 1118): htc_wext_set_keepalive +
I/wpa_supplicant( 1118): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1118): getPrivFuncNum +	
I/wpa_supplicant( 1118): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1118): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1118): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1118): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1118): htc_wext_set_keepalive - ret = 0
,D/AutoSetting( 1339): receiver - intent: android.intent.action.USER_PRESENT
D/PMS     (  906): releaseWL(42cf6410): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/PMS     (  906): acquireWL(42dd5128): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 906 1000 null
D/WifiNative-wlan0(  906):    returned true
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
,D/TetherSettings( 3797): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 3797): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3797): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3797): Cust_ConnectToPC   : spcsc>false
D/        ( 3797): Cust_ConnectToPC   : IPT>true
D/        ( 3797): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3797): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3797): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 3797): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/AutoSetting( 1339): service - onCreate()
,D/SmartNS_NSReceiver( 3797): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,V/SRS_Proc(  375): ParamSet string: screen_state=off
,D/AutoSetting( 1339): service - AddressCache: using context: com.htc.Weather
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 4153
,I/PSReceiver( 3797): onReceive:android.intent.action.USER_PRESENT
,D/AutoSetting( 1339): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/LocationManagerService(  906): request 42bdfab0 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
,D/LocationManagerService(  906): provider request: passive ProviderRequest[ON interval=0]
W/ContextImpl( 3797): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/SmartNS_PSService( 3797): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3797): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3797):  defaultType:0
D/NetworkPolicy(  906): updateScreenOn: false
,D/wpa_supplicant( 1118): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  906):    returned true
,D/PMS     (  906): releaseWL(42dd5128): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
,I/PhoneStatusBar( 1127): removeHeadsNotification.gc: 54
,W/ContextImpl( 4288): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/ContactMessageStore( 1263): start background delete task...
,D/SmartSyncUtils( 4288): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4288): getMobilePolicyEnabled, result = true
D/ContactMessageStore( 1263): size: 0 , 0
,D/ContactMessageStore( 1263): Background delete complete
,D/SmartSyncUtils( 4288): isEpsOn(), nState = 0
D/WifiService(  906): New client listening to asynchronous messages
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@428ddf30
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 1
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@428ddf30, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 0
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@428ddf30, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@428ddf30
,E/ActivityThread(  906): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42917ef8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42917ef8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  906): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  906): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  906): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  906): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  906): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  906): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  906): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  906): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  906): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  906): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  906): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  906): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  906): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  906): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  906): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  906): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  906): 	at dalvik.system.NativeStart.main(Native Method)
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] getTotalRam: 1873 Mb
D/PMS     (  906): acquireWL(42d59e50): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1247 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(42d59ca0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1247 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(42d59e50): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42d59ca0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1772): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1772): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1772): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1772): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1772): onScreenOff
D/PMS     (  906): acquireWL(42d4d740): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{429994c8: PendingIntentRecord{4296daa0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=118043, Int=0
,I/IntentController( 1127): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42d4d740): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 1
,D/AutoSetting( 1339): service - mRequestRunnable: screen on delay 10s, request NLP now
D/AutoSetting( 1339): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1339): service - requestNLP() NetworkLocationProvider not enabled
,D/PMS     (  906): acquireWL(42d340c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  906): sending alarm PendingIntent{42999368: PendingIntentRecord{429a0690 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=128868, Int=0
,D/PMS     (  906): releaseWL(42d340c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42d18d48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1396 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1396/10029)
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(42cfe580): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1396 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42cfe580): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42d18d48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42cbe450): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1396 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031187
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031351
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031596
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031601
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031605
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031608
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033590
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033602
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360036074
,D/PMS     (  906): releaseWL(42cbe450): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42c45c70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1396 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1396/10029)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031187
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031351
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031596
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031601
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031605
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031608
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033590
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033602
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360036074
,E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
D/PMS     (  906): acquireWL(429c3458): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1396 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(429050e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1396 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1247): Vacuum at: now=1454420831096 tag=VacuumService
,D/PMS     (  906): releaseWL(42c45c70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(429050e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42c07890): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1396 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(429c3458): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031187
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031351
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031596
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031601
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031605
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031608
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033590
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033602
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360036074
,D/PMS     (  906): releaseWL(42c07890): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42c2d288): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1396 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031187
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031351
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031596
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031601
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031605
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031608
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033590
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033602
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360036074
,D/PMS     (  906): releaseWL(42c2d288): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42b09f40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1396 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1396/10029)
I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031187
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031351
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031596
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031601
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031605
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031608
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033590
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033602
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360036074
,E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): releaseWL(42b09f40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42c1dca0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42c1dca0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/IntentController( 1127): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1127): closing low battery warning: level=100
,D/PowerUI ( 1127): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1127): status:5 level:100 unsupport:false plugged:true
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{42dcabd0 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1339): service - handleMessage() stop self
,D/AutoSetting( 1339): service - handleMessage() quit looper
,D/AutoSetting( 1339): service - onDestroy() END
,D/Process (  906): killProcessQuiet, pid=3877
,I/ActivityManager(  906): Killing 3877:com.htc.musicenhancer/u0a53 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Recipient 3877
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(42cafcf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{429439e8: PendingIntentRecord{42b59ff8 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=147248, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{42b6b680: PendingIntentRecord{42bd0158 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=148051, Int=0
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 3
,D/GpsLocationProvider(  906): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  906): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  906): acquireWL(42d96338): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1396/10029)
D/PMS     (  906): acquireWL(42be2668): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1396 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(42cafcf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1396/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [2][0][0]
D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =10c5 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET] NOT IN CACHE
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031187
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031351
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031596
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031601
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031605
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031608
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033590
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033602
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360036074
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1118): environment dirty rate=0 [1][0][0]
,D/PMS     (  906): acquireWL(42cb4238): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1396 10029 WorkSource{10029 com.google.android.gms}
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  365): [NET]res_nsend:resplen=243
D/libc    (  365): [NET]res_queryN: exit 3, ancount=10
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success
I/global  (  906): call createSocket() return a new socket.
D/libc    (  906): [NET] getaddrinfo+,hn 12(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/PMS     (  906): releaseWL(42cb4238): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42db4900): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1396 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42be2668): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42be05b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1396 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031187
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031351
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031596
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031601
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031605
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031608
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033590
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033602
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360036074
,D/PMS     (  906): releaseWL(42be05b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/GpsLocationProvider(  906): [handleDownloadXtraData] calling native_inject_xtra_data
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1247/10029)
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1118): environment dirty rate=0 [46][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1247/10029)
I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1247/10029)
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
,D/GpsLocationProvider(  906): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  906): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  906):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,I/PhenotypeConfigurator( 1247): Scheduling Phenotype for one-off execution 9268 seconds from now (1454420850936)
,D/GetConfigurationSnapshotOperation( 1247): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1247): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1247): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1247): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1247): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1247): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1247): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  906): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1247/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1247/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 1247): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
,D/libc    ( 1247): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1247): [NET] getaddrinfo-,err=8
D/libc    ( 1247): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1247): [NET] getaddrinfo-, 1
,D/libc    ( 1247): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =7f7e +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1247): [NET] getaddrinfo_proxy-, success,
,D/libc    ( 1247): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1247): [NET] getaddrinfo-,err=8
D/libc    ( 1247): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1247): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  906): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1247/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1118): environment dirty rate=0 [10][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1247/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
,D/LocationManagerService(  906): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1247/10029)
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1247/10029)
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): releaseWL(42db4900): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42cbfc38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1396 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031187
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031351
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031596
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031601
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031605
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031608
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033590
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033602
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360036074
,D/PMS     (  906): releaseWL(42cbfc38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42c31798): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1396 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1396/10029)
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1118): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1118): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1118): nl80211: survey data missing!
E/wpa_supplicant( 1118): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1118): environment dirty rate=0 [0][0][0]
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031187
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031351
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031596
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031601
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031605
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031608
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033590
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033602
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360036074
,D/PMS     (  906): releaseWL(42c31798): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42d96338): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/PMS     (  906): acquireWL(42cdf998): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10027}
,V/AlarmManager(  906): sending alarm PendingIntent{42627da8: PendingIntentRecord{42899160 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=159013, Int=0
,D/PMS     (  906): releaseWL(42cdf998): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/ClearcutLoggerApiImpl( 1396): disconnect managed GoogleApiClient
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(42c7c580): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1127): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1127): closing low battery warning: level=100
D/PowerUI ( 1127): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/PMS     (  906): releaseWL(42c7c580): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1127): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42ca79e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{429994c8: PendingIntentRecord{4296daa0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=178043, Int=0
,I/IntentController( 1127): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42ca79e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/TelephonyReceiver( 1263): switchBindHtcMsgCursor: null
,D/PMS     (  906): acquireWL(42c3a990): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/PMS     (  906): releaseWL(42c3a990): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
I/IntentController( 1127): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1127): closing low battery warning: level=100
D/PowerUI ( 1127): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1127): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 5
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(42cea168): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1127): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(42cea168): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1127): closing low battery warning: level=100
D/PowerUI ( 1127): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1127): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42cd2ad0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{429994c8: PendingIntentRecord{4296daa0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=238043, Int=0
,I/IntentController( 1127): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42cd2ad0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(42deaf70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/PMS     (  906): releaseWL(42deaf70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1127): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1127): closing low battery warning: level=100
D/PowerUI ( 1127): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1127): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(42d68700): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/PMS     (  906): releaseWL(42d68700): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
,I/IntentController( 1127): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1127): closing low battery warning: level=100
D/PowerUI ( 1127): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1127): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42cb1688): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{429994c8: PendingIntentRecord{4296daa0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=298043, Int=0
,I/IntentController( 1127): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42cb1688): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(42d517c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42d517c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(42c6ec80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{429994c8: PendingIntentRecord{4296daa0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=358043, Int=0
,I/IntentController( 1127): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42c6ec80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(42d1b590): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42d1b590): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
,D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1127): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1127): closing low battery warning: level=100
D/PowerUI ( 1127): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1127): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(42db5e48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{429994c8: PendingIntentRecord{4296daa0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=418044, Int=0
,I/IntentController( 1127): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42db5e48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42ca3ee0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42ca3ee0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(42d93068): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1127): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  906): releaseWL(42d93068): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1127): closing low battery warning: level=100
,D/PowerUI ( 1127): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1127): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(42d4edb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{429994c8: PendingIntentRecord{4296daa0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=478043, Int=0
,I/IntentController( 1127): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42d4edb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42ca3030): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42ca3030): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1127): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/PowerUI ( 1127): closing low battery warning: level=100
D/PowerUI ( 1127): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1127): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(42c95598): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42c95598): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
I/IntentController( 1127): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1127): closing low battery warning: level=100
,D/PowerUI ( 1127): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1127): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(42c5e828): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{429994c8: PendingIntentRecord{4296daa0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=538043, Int=0
,I/IntentController( 1127): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42c5e828): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(42c602c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): BroadcastReceiver::onReceive+
I/IntentController( 1127): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1127): closing low battery warning: level=100
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(42c602c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1127): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1127): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42d7b6d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42d7b6d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1127): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1127): closing low battery warning: level=100
D/PowerUI ( 1127): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1127): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42c75f58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{429994c8: PendingIntentRecord{4296daa0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=598043, Int=0
,I/IntentController( 1127): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42c75f58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42e05bd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42e05bd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory),
,D/ContactMessageStore( 1263): MSG_CHECK_DELETION >>
D/ContactMessageStore( 1263): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1263): sku_id=99
,D/ContactMessageStore( 1263): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1263): start background delete task...
D/ContactMessageStore( 1263): size: 0 , 0
,D/ContactMessageStore( 1263): Background delete complete
,D/PMS     (  906): acquireWL(42e07aa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{429994c8: PendingIntentRecord{4296daa0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=658043, Int=0
,I/IntentController( 1127): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42e07aa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42e0a9f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
,D/PMS     (  906): releaseWL(42e0a9f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1127): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1127): closing low battery warning: level=100
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1127): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1127): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42e102b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(42e102b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/IntentController( 1127): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1127): closing low battery warning: level=100
D/PowerUI ( 1127): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1127): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42e16228): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{429994c8: PendingIntentRecord{4296daa0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=718043, Int=0
,I/IntentController( 1127): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42e16228): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42e18a70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42e18a70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
,I/IntentController( 1127): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1127): closing low battery warning: level=100
D/PowerUI ( 1127): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1127): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42e1e660): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{429994c8: PendingIntentRecord{4296daa0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=778043, Int=0
,I/IntentController( 1127): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42e1e660): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42e208e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42e208e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
,I/IntentController( 1127): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1127): closing low battery warning: level=100
D/PowerUI ( 1127): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1127): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42e26520): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{429994c8: PendingIntentRecord{4296daa0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=838043, Int=0
,I/IntentController( 1127): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42e26520): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42e27f98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42e27f98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,I/IntentController( 1127): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1127): closing low battery warning: level=100
,D/PowerUI ( 1127): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1127): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42e2d790): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(42e2d790): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
,I/IntentController( 1127): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1127): closing low battery warning: level=100
D/PowerUI ( 1127): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1127): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42e33430): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{429994c8: PendingIntentRecord{4296daa0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=898043, Int=0
,I/IntentController( 1127): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42e33430): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42e34ea8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42e34ea8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/PowerUI ( 1127): closing low battery warning: level=100
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,D/PowerUI ( 1127): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1127): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1127): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42e3a720): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42e3a720): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
I/IntentController( 1127): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1127): closing low battery warning: level=100
D/PowerUI ( 1127): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1127): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42e40430): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  906): sending alarm PendingIntent{4234b230: PendingIntentRecord{42a5fe68 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=788651, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{42a79618: PendingIntentRecord{42b8b7d0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=940025, Int=0
,D/PMS     (  906): acquireWL(42e4c8e0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1396 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): Done.
D/PMS     (  906): releaseWL(42e4c8e0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): Setting timer for 720seconds
,I/ActivityManager(  906): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4359 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  906): sending alarm PendingIntent{42837cd8: PendingIntentRecord{42476c10 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1454420925962, Int=10800000
,D/PMS     (  906): releaseWL(42e40430): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.aurora (4359/10049)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031187
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031351
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031596
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031601
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031605
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031608
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033590
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033602
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360036074
,D/Process (  906): killProcessQuiet, pid=3673
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3673:com.htc.task/u0a71 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3673
,D/PMS     (  906): acquireWL(42e5dda0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1396 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1396/10029)
,D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1396/10029)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1396/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031187
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031351
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031596
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031601
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031605
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360031608
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033590
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360033602
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360036074
,D/PMS     (  906): releaseWL(42e5dda0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/PMS     (  906): acquireWL(42e66920): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{429994c8: PendingIntentRecord{4296daa0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=958043, Int=0
,I/IntentController( 1127): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42e66920): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42e68570): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42e68570): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42e69a28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42e69a28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1127): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1127): closing low battery warning: level=100
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1127): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1127): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42e70498): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42b353c8: PendingIntentRecord{42b27978 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1454421646254, Int=900000
,V/AlarmManager(  906): sending alarm PendingIntent{42b74cf0: PendingIntentRecord{42cf2c40 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1454421719938, Int=0
,W/ContextImpl( 4288): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4288): call getInstance()
,D/SmartSyncUtils( 4288): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4288): MY_DEBUG = false
D/PMS     (  906): releaseWL(42e70498): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  906): acquireWL(42e73450): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4288 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 4288): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4288): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4288): AlarmOnTime = -1
,D/SmartSyncScreenOnOffTimeReceiver( 4288): SettingOnTime = 1454479200000, randomSettingOnTime = 1454476968000,
,D/SmartSyncScreenOnOffTimeReceiver( 4288): SettingOffTime = 1454464800000, randomSettingOffTime = 1454471496000
,D/SmartSyncScreenOnOffTimeReceiver( 4288): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4288): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4288): bNightModeTurnOffOnce = false
W/BatSI   (  906): Couldn't get kernel wake lock stats
D/PMS     (  906): acquireWL(42e74768): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{429994c8: PendingIntentRecord{4296daa0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1018043, Int=0
,I/IntentController( 1127): receive(android.intent.action.TIME_TICK,1,false)
D/PMS     (  906): releaseWL(42e73450): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  906): releaseWL(42e74768): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/PMS     (  906): acquireWL(429af848): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1127): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1127): closing low battery warning: level=100
D/PowerUI ( 1127): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(429af848): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1127): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42759c10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(42759c10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,D/PowerUI ( 1127): closing low battery warning: level=100
,I/IntentController( 1127): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1127): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1127): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42bfbaa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{429994c8: PendingIntentRecord{4296daa0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1078044, Int=0
,I/IntentController( 1127): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42bfbaa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42d36b20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,I/IntentController( 1127): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  906): releaseWL(42d36b20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1127): closing low battery warning: level=100
,D/PowerUI ( 1127): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1127): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42c2cdf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42c2cdf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1127): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1127): closing low battery warning: level=100
D/PowerUI ( 1127): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1127): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42a85b38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{429994c8: PendingIntentRecord{4296daa0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1138043, Int=0
,I/IntentController( 1127): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42a85b38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42c89328): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42c89328): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1127): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HtcPowerSaver(  906): updateBatteryInfo
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1127): closing low battery warning: level=100
D/PowerUI ( 1127): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1127): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42a84b78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42a84b78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1127): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1127): closing low battery warning: level=100
D/PowerUI ( 1127): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1127): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42be7118): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{429994c8: PendingIntentRecord{4296daa0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1198043, Int=0
,I/IntentController( 1127): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42be7118): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42daac68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42daac68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory),
,D/PMS     (  906): acquireWL(42cdb458): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{429994c8: PendingIntentRecord{4296daa0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1258043, Int=0
,I/IntentController( 1127): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42cdb458): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42db6380): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-,
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1127): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): releaseWL(42db6380): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1127): closing low battery warning: level=100
D/PowerUI ( 1127): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1127): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4384): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4384): ====startRecUseTime====
D/htc.customization.log.level( 4384):  is 
W/CustomizationLogLevel( 4384): Level value is invalid, use default level 2
D/CustomizationManager( 4384):  Read ACC file spent 0.105 (s)
D/CIDMapFileReader( 4384): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4384): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4384): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4384): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4384): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4384): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4384): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4384): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4384): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4384): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4384): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4384): Parsing tag category name = system
I/CustomizationCIDLoader( 4384): Parsing tag category name = application
I/CustomizationCIDLoader( 4384): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4384): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4384): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4384): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4384): Parsing tag category name = Settings
D/CustomizationManager( 4384):  Read CID file spent 0.160 (s)
D/CustomizationManager( 4384):  All configurations done spent 0.160 (s)
W/HtcNativeFlag( 4384): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4384): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4384): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4384): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  906): deletePackageAsUser: pkg=com.test.thalitest, pid=4384, uid=2000 user=0
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
W/PackageSettings(  906): Skipping PackageSetting{42793710 com.example.hello/10397} due to missing metadata
W/PackageSettings(  906): Skipping PackageSetting{4279a5d8 com.test.thalitest/10389} due to missing metadata
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/Prism.ItemManager( 1299): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1299): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/HtcKeyguardAppUpdateMonitor( 1127): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1127): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1127): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1590): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1590): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1590): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/GeofencerStateMachine( 1247): Ignoring removeGeofence because network location is disabled.
D/PMS     (  906): acquireWL(42d8d598): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1247 10029 WorkSource{10029 com.google.android.gms}
W/PackageManager(  906): Package source /data/app/com.test.thalitest-2.apk does not exist.
W/PackageManager(  906): Couldn't delete native library directory /data/app-lib/com.test.thalitest-2
D/AccTypeManager( 1379): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  906): releaseWL(42d8d598): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(42f6f538): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
D/PMS     (  906): releaseWL(42f6f538): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/VoicemailCleanupService( 1325): Cleaning up data for package: com.test.thalitest
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1263 :
W/SystemReader( 1278): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1263 :
I/PackageManager(  906):   Scheme: "smsto"
W/AccTypeManager( 1379): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1379): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1263 :
I/[PluginManager]RegisterService( 1339): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1339): handle notify Blinkfeed plugin client changed
D/Prism.PackageStateRece_( 1299): action: android.intent.action.PACKAGE_REMOVED
I/IcingCorporaProvider( 3077): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1263 :
I/ActivityManager(  906): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4399 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1263 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
W/Parcel  ( 1278): Reading a NULL string not supported here.
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1263 :
I/IcingCorporaProvider( 3077): UpdateCorporaTask done [took 103 ms] updated apps [took 103 ms] 
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1263 :
E/ExternalAccountType( 1379): Unsupported attribute readOnly
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1263 :
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/InputMethodManagerService(  906): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/PhoneApp( 1263): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
W/PackageManager(  906): Unable to load service info ResolveInfo{42cb02a0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  906): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  906): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  906): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  906): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  906): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  906): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  906): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  906): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  906): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  906): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteDatabase( 4399): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4399): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4399): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4399): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4399): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4399): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4399): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4399): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4399): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4399): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4399): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4399): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4399): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4399): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4399): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4399): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4399): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4399): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4399): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4399): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4399): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4399): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4399): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4399): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4399): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4399): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4399): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4399): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4399): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4399): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4399): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4399): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4399): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4399): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4399): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4399): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4399): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4399): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4399): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4399): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4399): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4399): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4399): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4399): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4399): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4399): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4399): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4399): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4399): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4399): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4399): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4399): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4399): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4399): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4399): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4399): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4399): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4399): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4399): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4399): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4399): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4399): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4399): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4399): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4399): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4399): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4399): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4399): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4399): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4399): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4399): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4399): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4399): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4399): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4399): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4399): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4399): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4399): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4399): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4399): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4399): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4399): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4399): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4399): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4399): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4399): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4399): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4399): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4399): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4399): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4399): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4399): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4399): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4399): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4399): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4399): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4399): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4399): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4399): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4399): threadid=11: thread exiting with uncaught exception (group=0x41c9ce30)
E/ActivityManager(  906): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4399): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4399): Process: com.google.android.apps.docs, PID: 4399
E/AndroidRuntime( 4399): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4399): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4399): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4399): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4399): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4399): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4399): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4399): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4399): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4399): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4399): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4399): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4399): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4399): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4399): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4399): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4399): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4399): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4399): 	at aho.run(AbstractDatabaseInstance.java:455)
E/SQLiteDatabase( 4399): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4399): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4399): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4399): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4399): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4399): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4399): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4399): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4399): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4399): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4399): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4399): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4399): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4399): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4399): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4399): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4399): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4399): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4399): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4399): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4399): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4399): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4399): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4399): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4399): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4399): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4399): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4399): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4399): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4399): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4399): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4399): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4399): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4399): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4399): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4399): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4399): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4399): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4399): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4399): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4399): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4399): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4399): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4399): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4399): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4399): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4399): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4399): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4399): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4399): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4399): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4399): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4399): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4399): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4399): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4399): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4399): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4399): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4399): Opened ClientFlag.db in read-only mode
D/Process ( 4399): killProcess, pid=4399
D/Process ( 4399): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop138.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  906): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  906): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  906): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  906): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  906): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  906): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  906): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  906): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  906): 	... 5 more
I/ActivityManager(  906): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4418 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  906): Recipient 4399
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/RemoteDisplayProvider(  906): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  906): start
D/Process (  906): killProcessQuiet, pid=3853
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 3853:com.google.android.music:main/u0a154 (adj 15): empty #17
W/AtomicFile(  906): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
I/ActivityManager(  906): Process com.google.android.apps.docs (pid 4399) has died.
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1127): closing low battery warning: level=100
W/AppWidgetServiceImpl(  906): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3853
D/PowerUI ( 1127): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1127): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/MediaRouterService(  906): Client com.google.android.music (pid 3853): Died!
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
W/ContextImpl( 4418): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 4418): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4418): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4418): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4418): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4418): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4418): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4418): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4418): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4418): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4418): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4418): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4418): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4418): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4418): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4418): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4418): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4418): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4418): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4418): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4418): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4418): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4418): threadid=10: thread exiting with uncaught exception (group=0x41c9ce30)
E/AndroidRuntime( 4418): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4418): Process: com.android.keychain, PID: 4418
E/AndroidRuntime( 4418): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4418): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4418): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4418): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4418): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4418): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4418): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4418): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4418): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4418): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4418): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4418): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4418): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4418): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4418): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4418): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4418): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4418): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4418): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4418): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  906): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4432 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/ActivityManager(  906): App crashed! Process: com.android.keychain
D/ErrorReport(  906): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4418): killProcess, pid=4418
D/Process ( 4418): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/BatteryController( 1127): status:5 level:100 unsupport:false plugged:true
E/ErrorReport(  906): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  906): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1454421974843.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  906): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  906): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  906): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  906): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  906): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  906): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  906): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  906): 	... 4 more
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 4418
I/ActivityManager(  906): Process com.android.keychain (pid 4418) has died.
W/ActivityManager(  906): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/AppTag  ( 4432): getInstance(Context context)
D/AppTag  ( 4432): getInstance(Context context)
D/AppTag  ( 4432): onCreate()
D/PMS     (  906): acquireWL(42922b68): PARTIAL_WAKE_LOCK  AsyncService 0x1 3998 10160 null
D/PMS     (  906): releaseWL(42922b68): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
W/dalvikvm( 4026): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PackageBroadcastService( 2180): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2180): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 2180): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2180): Loading module APK com.google.android.play.games
I/LocationSettingsChecker( 2180): Removing dialog suppression flag for package com.test.thalitest
W/dalvikvm( 2180): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
E/SQLiteDatabase( 2180): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 2180): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2180): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2180): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2180): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2180): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2180): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2180): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2180): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2180): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2180): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2180): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2180): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2180): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2180): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2180): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2180): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 2180): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2180): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2180): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2180): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PhenotypeInitializer( 2180): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 2180): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 2180): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 2180): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/PhenotypeInitializer( 2180): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/PhenotypeInitializer( 2180): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 2180): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 2180): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 2180): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/PhenotypeInitializer( 2180): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/PhenotypeInitializer( 2180): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/PhenotypeInitializer( 2180): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/PhenotypeInitializer( 2180): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2180): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2180): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 2180): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 2180): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 2180): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 2180): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 2180): 	at android.os.Looper.loop(Looper.java:157)
E/PhenotypeInitializer( 2180): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 2180): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 2180): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 2180): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
W/dalvikvm( 2180): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
I/Prism.ItemManager( 1299): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1299): loadItems() com.htc.launcher.pageview.WidgetManager@4215ec98 +
I/Prism.WidgetManager( 1299): onLoadItems() +
I/GMPM-SVC( 2180): App measurement is starting up, version: 8489
I/GMPM-SVC( 2180): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
E/SQLiteLog( 2180): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2180): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5c9f4de0
E/DriveAsyncService( 2180): disk I/O error (code 3850)
E/DriveAsyncService( 2180): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2180): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2180): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2180): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2180): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2180): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2180): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2180): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2180): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2180): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2180): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2180): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2180): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2180): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2180): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2180): 	at java.lang.Thread.run(Thread.java:864)
I/ActivityManager(  906): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
D/ChimeraCfgMgr( 2180): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2180): Module APK com.google.android.play.games already loaded
E/SQLiteLog( 2180): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2180): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/pluscontacts.db, handle = 0x65ec41b8
W/dalvikvm( 2180): threadid=49: thread exiting with uncaught exception (group=0x41c9ce30)
E/ActivityManager(  906): App crashed! Process: com.google.android.gms
I/Icing   ( 2180): doRemovePackageData com.test.thalitest
D/Process ( 2180): killProcess, pid=2180
E/SQLiteDatabase( 2180): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 2180): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2180): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2180): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2180): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2180): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2180): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2180): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2180): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2180): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2180): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2180): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2180): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2180): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2180): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 2180): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 2180): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 2180): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 2180): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 2180): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2180): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2180): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2180): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 2180): FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
E/AndroidRuntime( 2180): Process: com.google.android.gms, PID: 2180
E/AndroidRuntime( 2180): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2180): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2180): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2180): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2180): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2180): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2180): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2180): 	at com.google.android.gms.people.c.e.a(SourceFile:110)
E/AndroidRuntime( 2180): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3165)
E/AndroidRuntime( 2180): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/AndroidRuntime( 2180): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/AndroidRuntime( 2180): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2180): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2180): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2180): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  906): acquireWL(42e0bd28): PARTIAL_WAKE_LOCK  Icing 0x1 2180 10029 WorkSource{10029 com.google.android.gms}
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop140.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  906): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  906): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  906): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  906): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  906): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  906): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  906): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  906): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  906): 	... 5 more
D/Process ( 2180): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  906): Recipient 2180
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.google.android.gms (pid 2180) has died.
D/WifiService(  906): Client connection lost with reason: 4
D/PMS     (  906): handleWLDeath(42e0bd28): PARTIAL_WAKE_LOCK  Icing 0x1
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 1000ms
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 11000ms
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 11000ms
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 20999ms
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20999ms
I/ActivityManager(  906): Resuming delayed broadcast

```
