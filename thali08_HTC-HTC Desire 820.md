#### Test 50388019385b4d9_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/CalendarApplication( 3242): onCreate
D/ProviderChangeReceiver( 3242): ---------------------------------------------------
D/ProviderChangeReceiver( 3242): ProviderChangeReceiver onReceive, start to update notification!
D/AlertService( 3242): start to updateAlertNotification!
E/ExternalAccountType( 3198): Unsupported attribute readOnly
--------- beginning of /dev/log/system
W/ContextImpl( 3025): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
D/GCM     ( 1346): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AlertService( 3242): No fired or scheduled alerts
D/HtcAlertUtils( 3242): -- cancelReminderNotification --
I/ActivityManager(  904): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
D/HtcAlertUtils( 3242): broadcastExistReminder!
D/DotMatrix( 1533): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/ActivityManager(  904): Resuming delayed broadcast
I/AdsMeasurementBroadcastReceiver( 1195): Reporting settings might have changed, alerting AdsMeasurementService
D/AdsMeasurementBroadcastReceiver( 1195): Unauthorized to start the main service
W/AccTypeManager( 3198): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 3198): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/ActivityManager(  904): Recipient 2875
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/AccTypeManager( 3198): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/ActivityManager(  904): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.WeatherClock4x1: pid=3262 uid=10042 gids={50042, 3002, 3001, 3003, 5012}
D/Process (  904): killProcessQuiet, pid=2952
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 2952:com.google.android.talk/u0a111 (adj 15): empty #17
,E/ExternalAccountType( 3198): Unsupported attribute readOnly
I/ActivityManager(  904): Recipient 2952
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver: pid=3277 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
W/WeatherUtility( 3262): can't get weather sync account
W/WeatherRequest( 3262): request cur loc, but there is no sys cur
W/Settings( 3262): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/DemoRecovery.RestoreReceiver( 3277): onReceive: com.htc.launcher.intent.LOADING_COMPLETE
W/ContextImpl( 3277): Implicit intents with startService are not safe: Intent { act=com.htc.demorecovery.LOADING_COMPLETE } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.demoflopackageinstaller.demorecovery.RestoreReceiver.onReceive:26 
I/ActivityManager(  904): Delay finish: com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver
I/RestoreService( 3277): onHandleIntent: com.htc.demorecovery.LOADING_COMPLETE
I/ActivityManager(  904): Resuming delayed broadcast
D/Process (  904): killProcessQuiet, pid=2979
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  904): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3293 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
I/ActivityManager(  904): Killing 2979:com.htc.backupreset/1000 (adj 15): empty #17
D/AppWidgetHostView( 1245): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
I/RemoteViews( 1245): com.htc.widget.weatherclock (true,33751552)
I/RemoteViews.Performance( 1245): com.htc.widget.weatherclock 1 9 17
D/PMS     (  904): acquireWL(42f698e8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3293 10070 null
I/ActivityManager(  904): Recipient 2979
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Delay finish: com.htc.task/.TodoReceiver
D/PMS     (  904): acquireWL(4300af78): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3293 10070 null
D/TodoTaskshortcut( 3293): update TASK shortcut>
D/PMS     (  904): releaseWL(42f698e8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
I/TodoTaskNotifyService( 3293): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
D/DotMatrix( 1533): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  904): releaseWL(4300af78): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  904): Resuming delayed broadcast
W/NotifyReceiver( 3293): stopSelfResult true
D/Process (  904): killProcessQuiet, pid=2996
I/ActivityManager(  904): Start proc com.htc.stock for broadcast com.htc.stock/.receiver.StockReceiver: pid=3308 uid=10081 gids={50081, 3003, 5012}
I/ActivityManager(  904): Killing 2996:com.htc.htccupd/u0a17 (adj 15): empty #17
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Recipient 2996
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Start proc com.htc.stock:remote for content provider com.htc.stock/.provider.StockProvider: pid=3320 uid=10081 gids={50081, 3003, 5012}
E/cutils-trace( 3283): Error opening trace file: No such file or directory (2)
D/Process (  904): killProcessQuiet, pid=3050
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/Process (  904): killProcessQuiet, pid=3011
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/AdsMeasurementBroadcastReceiver( 1195): Reporting settings might have changed, alerting AdsMeasurementService
I/ActivityManager(  904): Killing 3050:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
I/ActivityManager(  904): Killing 3011:com.zoodles.kidmode/u0a149 (adj 15): empty #18
D/AdsMeasurementBroadcastReceiver( 1195): Unauthorized to start the main service
I/Prism.ItemManager( 1245): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1245): loadItems() com.htc.launcher.pageview.WidgetManager@42395f70 +
I/Prism.WidgetManager( 1245): onLoadItems() +
I/ActivityManager(  904): Recipient 3050
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/SMSBackup( 3230): Got a database change event
I/ActivityManager(  904): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=3339 uid=10075 gids={50075, 3003, 5012, 1028, 1015, 5001, 1023}
D/RemoteDisplayProvider(  904): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  904): start
D/ContactMessageStore( 1212): MSG_NOTIFY_CS_TO_SYNC >>
D/ContactMessageStore( 1212): MSG_NOTIFY_CS_TO_SYNC <<
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/CustomizationManager( 3283): ====startRecUseTime====
D/htc.customization.log.level( 3283):  is 
W/CustomizationLogLevel( 3283): Level value is invalid, use default level 2
I/ImageRamCache( 3339): create image Cache, size: 31457280.
I/ImageRamCache( 3339): [resize] ImageRamCache resized to: 12Mb.
I/ImageRamCache( 3339): create image Cache, size: 12582912.
I/ActivityManager(  904): Recipient 3011
I/FeedSettings( 3339): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 3339): GroupBudget 0.500000 0.380000
I/FeedSettings( 3339): GroupBudget 60 45 15
I/Prism.ExternalStringMa_( 3339): changeLocale(): en_GB
I/Prism.AllAppsOptionsMa_( 3339): loadSortType() with Custom
I/Prism.AllAppsOptionsMa_( 3339): loadGridSize() with Alternative
D/MessagingNotification( 2629): New incoming message, can't cancel notification now
D/MessagingNotification( 2629): newMsgCnt: 0, false
D/CustomizationManager( 3283):  Read ACC file spent 0.070 (s)
D/CIDMapFileReader( 3283): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3283): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3283): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3283): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3283): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3283): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3283): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3283): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3283): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3283): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3283): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3283): Parsing tag category name = system
I/CustomizationCIDLoader( 3283): Parsing tag category name = application
I/CustomizationCIDLoader( 3283): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3283): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3283): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3283): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3283): Parsing tag category name = Settings
D/CustomizationManager( 3283):  Read CID file spent 0.116 (s)
D/CustomizationManager( 3283):  All configurations done spent 0.116 (s)
W/HtcNativeFlag( 3283): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3283): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3283): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3283): Fail to get flag for type 'language', use default value: -1
D/CustomHighlightReceiver( 3339): [custom highlight] onReceive
D/CustomHighlightService( 3339): [custom highlight] onHandleIntent
D/NewsDB  ( 3339): set custom highlight []
I/ActivityManager(  904): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
D/CustomHighlightService( 3339): [custom highlight] set tags 
D/MessagingShortcutReceiver( 2629): keep hiding shortcut bubble
D/MessagingShortcut( 2629): updateMsgShortcut, msg count> -1
D/MessagingShortcut( 2629): After query: 0
D/MessagingShortcut( 2629): mPresentUnreadCount: -1
D/MessagingShortcut( 2629): setMsgShortcutDrawable> 0
D/MessagingShortcut( 2629): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
D/DotMatrix( 1533): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/ActivityManager(  904): Resuming delayed broadcast
W/CpuWake (  904): >>nativeAcquireCpuPerfWakeLock()
D/DotMatrix( 1533): [EventService] reorderNotification, total:0
D/DotMatrix( 1533): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1533): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
W/asset   (  904): Copying FileAsset 0x6951eb98 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/Intent  (  904): @test_code: getHtcIntentFlag: 0 obj: 1123904712
W/CpuWake (  904): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  904): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  904): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  904): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  904): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  904): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3283
D/PMS     (  904): acquireHCC(4307cec0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 904 1000 null
D/PMS     (  904): acquireHCC(42ffeda0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 904 1000 null
I/FeedHostManager( 1245): [onPause]
I/FeedProviderManager( 1245): onPause
I/FeedHostManager( 1245): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@42ac4808
I/SocialFeedProvider( 1245): +onPause
I/SocialFeedProvider( 1245): -onPause
D/PMS     (  904): acquireWL(42f83e10): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 904 1000 null
I/ActivityManager(  904): Delay finish: com.htc.task/.TodoReceiver
D/TodoTaskshortcut( 3293): update TASK shortcut>
I/ActivityManager(  904): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3357 uid=10356 gids={50356, 3003, 5012, 3001, 3002}
D/HtcBroadcastReceiver( 1212): onReceive: com.htc.launcher.action.ACTION_ITEM_ADDED
D/Process (  904): killProcessQuiet, pid=3069
I/ActivityManager(  904): Resuming delayed broadcast
I/ActivityManager(  904): Killing 3069:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Recipient 3069
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3369 uid=10091 gids={50091, 3003, 5012}
W/asset   ( 3357): Copying FileAsset 0x5c6e5428 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/TrimMemoryManager( 1245): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 3357): Binding Chromium to main looper Looper (main, tid 1) {42304160}
I/LibraryLoader( 3357): Expected native library version number "",actual native library version number ""
I/ActivityManager(  904): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
I/chromium( 3357): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3357): Initializing chromium process, renderers=0
D/BluetoothManagerService(  904): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  904): java.lang.Throwable: stack dump
W/System.err(  904): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  904): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  904): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  904): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  904): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  904): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42d53928:true
D/PMS     (  904): acquireWL(42dd4db0): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  904): acquireWL(42dd47f0): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  904): releaseWL(42dd4db0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/BluetoothAdapter( 3357): 1110551216: getState() :  mService = null. Returning STATE_OFF
E/Prism.WidgetManager( 1245): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1245): onLoadItems() -
I/Prism.ItemManager( 1245): loadItems() com.htc.launcher.pageview.WidgetManager@42395f70 -
I/Adreno-EGL( 3357): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3357): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3357): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3357): Local Branch: 
I/Adreno-EGL( 3357): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3357): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3357):                  aa63bbd948f41d15fc72f585e
I/ActivityManager(  904): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3392 uid=10091 gids={50091, 3003, 5012}
W/chromium( 3357): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 3357): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3357): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3357): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3357): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3357): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3357): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3357): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3357): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3357): CordovaWebView is running on device made by: HTC
D/MdScBoot( 3369): [588.1.] 30@-152112 -> 40@-152142
D/Process (  904): killProcessQuiet, pid=3083
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  904): Resuming delayed broadcast
I/ActivityManager(  904): Killing 3083:com.android.smith/u0a163 (adj 15): empty #17
D/GCM     ( 1346): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/Process (  904): killProcessQuiet, pid=3095
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3095:com.google.android.youtube/u0a168 (adj 15): empty #17
I/ActivityManager(  904): Recipient 3083
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  904): Resuming delayed broadcast
D/CustomHighlightReceiver( 3339): [custom highlight] onReceive
I/ActivityManager(  904): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
D/CustomHighlightService( 3339): [custom highlight] onHandleIntent
D/NewsDB  ( 3339): set custom highlight []
,D/CustomHighlightService( 3339): [custom highlight] set tags 
D/CustomHighlightReceiver( 3339): [custom highlight] onReceive
I/ActivityManager(  904): Resuming delayed broadcast
D/CustomHighlightService( 3339): [custom highlight] onHandleIntent
D/NewsDB  ( 3339): set custom highlight []
I/ActivityManager(  904): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
W/AwContents( 3357): nativeOnDraw failed; clearing to background color.
D/CustomHighlightService( 3339): [custom highlight] set tags 
D/GCM     ( 1346): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  904): Recipient 3095
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  904): Client com.google.android.youtube (pid 3095): Died!
I/ActivityManager(  904): Resuming delayed broadcast
I/InputMethodManagerService(  904): Disable input method client, pid=1245
W/ResourceType( 3357): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 3357): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@4234be38, mServedView=org.apache.cordova.engine.SystemWebView{42311dd0 VFEDH.C. .F....I. 0,0-720,1134 #64}
I/InputMethodManagerService(  904): Enable input method client, pid=3357
D/ConnectivityService(  904): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1751/10178)
W/XT9_C   ( 1182): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1182): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1182): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1182): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/MtpReceiver( 2105): [MTP][MtpReceiver][onReceive]+
D/MtpReceiver( 2105): [MTP][handleMessage][startService]
D/MtpReceiver( 2105): [MTP][MtpReceiver][onReceive]1-
D/MtpReceiver( 2105): [MTP][handleMessage][UsbManager.USB_CONNECTED][insert]+
D/MtpReceiver( 2105): [MTP][handleMessage]-
W/AwContents( 3357): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  904): Displayed com.example.hello/.MainActivity: +282ms
D/MtpService( 2105): [MTP] startForeground
D/DotMatrix( 1533): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
I/ActivityManager(  904): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3427 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
D/PMS     (  904): releaseWL(42f83e10): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/MtpService( 2105): updating state; isCurrentUser=true, mMtpLocked=false
D/MtpDatabase( 2105): TotalSize=1918604,MediaCacheLimit=6000
D/MtpService( 2105): [isMtpConnected] connected: true
I/RemoteViews( 1107): com.android.providers.media (false,0)
I/RemoteViews.Performance( 1107): com.android.providers.media 0 1 10
I/RemoteViews( 1107): com.android.providers.media (false,0)
I/RemoteViews.Performance( 1107): com.android.providers.media 0 1 15
D/SyncApplication( 3427): Loading default preferences
W/Resources( 3427): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
D/WifiService(  904): New client listening to asynchronous messages
D/Process (  904): killProcessQuiet, pid=3039
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3039:com.android.settings/1000 (adj 15): empty #17
D/SyncApplication( 3427): Overriding preferences with custom values
D/SyncApplication( 3427): Updating preferences succeeded
E/SyncApplication( 3427): Application created.
D/VolumeInfo( 3427): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
D/VolumeInfo( 3427): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 3427): Found 0 mount point(s)
V/VolumeInfo( 3427): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
D/VolumeInfo( 3427): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
D/PhoneApp( 1212): EVENT_QUERY_MO_PACKAGES
D/PhoneApp( 1212): -- N1 =0
D/PhoneApp( 1212): -- N2 =0
D/PhoneApp( 1212): -- N3 =0
D/VolumeInfo( 3427): Read the volume-id from the sd card: {61911E1D-261C-4FB6-8207-55BA8B8D5E9C}
W/VolumeInfo( 3427): Can not create volume ID for unmounted volume null
I/CalendarDefines( 3427): getNewCalendarAuthority()...
D/SyncApplication( 3427): enableAppOperation()+
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3427, uid=10008, userID:0
W/PackageManager(  904): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3427, uid=10008, userID:0
W/PackageManager(  904): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
D/SyncApplication( 3427): enableAppOperation()-
D/HTCUtilities( 3427): isNeorSinged() + 
D/HTCUtilities( 3427): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
E/AndroidProtocolHandler( 3357): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/HTCUtilities( 3427): isNeorSinged() return false
D/CDMountReceiver( 3427): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
D/CDMountReceiver( 3427): USB connected to PC
I/chromium( 3357): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/FOTAReceiver( 3427): onReceive() enter 
D/FOTAReceiver( 3427): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
D/Process (  904): killProcessQuiet, pid=3146
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  904): Killing 3146:com.htc.sense.browser/u0a12 (adj 15): empty #17
E/JavaBinder(  904): !!! FAILED BINDER TRANSACTION !!!
W/BroadcastQueue(  904): Exception when sending broadcast to ComponentInfo{com.android.settings/com.android.settings.MLReceiver}
W/BroadcastQueue(  904): android.os.TransactionTooLargeException
W/BroadcastQueue(  904): 	at android.os.BinderProxy.transact(Native Method)
W/BroadcastQueue(  904): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:966)
W/BroadcastQueue(  904): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:246)
W/BroadcastQueue(  904): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:974)
W/BroadcastQueue(  904): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:15076)
W/BroadcastQueue(  904): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:401)
W/BroadcastQueue(  904): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2330)
W/BroadcastQueue(  904): 	at android.os.Binder.execTransact(Binder.java:412)
W/BroadcastQueue(  904): 	at dalvik.system.NativeStart.run(Native Method)
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Start proc com.android.settings for broadcast com.android.settings/.MLReceiver: pid=3450 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/JsMessageQueue( 3357): Set native->JS mode to OnlineEventsBridgeMode
I/ActivityManager(  904): Recipient 3146
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/HtcFingerPrintQuickLaunchProvider( 3450): -onCreate()
D/jxcore_app_log( 3357): JniHelper::setJavaVM(0x41ec2010), pthread_self() = 1657979896
D/JX-Cordova( 3357): jxcore cordova android initializing
V/Settings:HtcSettingsApplication( 3450): [3450/3450] onCreate()
D/TetherSettings( 3450): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3450): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3450): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3450): Cust_ConnectToPC   : spcsc>false
D/        ( 3450): Cust_ConnectToPC   : IPT>true
D/        ( 3450): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3450): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/TetherSettings( 3450): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3450): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3450): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3450): Cust_ConnectToPC   : spcsc>false
D/        ( 3450): Cust_ConnectToPC   : IPT>true
D/        ( 3450): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3450): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3450): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3450): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3450): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
D/SmartNS_Utility( 3450): usb_cable_connect = 1
D/SmartNS_Utility( 3450): usb_denied = 0
I/SmartNS_NSReceiver( 3450): locked:falsesecurity:falseisLocked:false
D/SmartNS_NSReceiver( 3450): USB = true hasTethered = false isNSOpening: false
I/PSReceiver( 3450): onReceive:com.htc.intent.action.USB_CONNECT2PC
W/ContextImpl( 3450): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 3450): onReceive:com.htc.intent.action.USB_CONNECT2PC
W/Settings( 3450): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3450):  defaultType:0
I/SmartNS_PSService( 3450): fail notificaiton:false
D/SmartNS_Utility( 3450): usb_cable_connect = 1
D/SmartNS_Utility( 3450): usb_denied = 0
I/SmartNS_PSService( 3450): usb notificaiton:true
V/Tethering(  904): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Tethering(  904): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  904): bSetPropertyMultiRAB:false
D/ConnectivityService(  904): getActiveNetworkInfo called by com.android.settings (3450/1000)
D/SmartNS_Utility( 3450): usb_cable_connect = 1
D/SmartNS_Utility( 3450): usb_denied = 0
I/SmartNS_PSService( 3450): usb notificaiton:true
V/Tethering(  904): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/DotMatrix( 1533): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
D/Tethering(  904): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  904): bSetPropertyMultiRAB:false
I/RemoteViews( 1107): com.android.settings (true,33751552)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.android.settings (3450/1000)
I/RemoteViews.Performance( 1107): com.android.settings 0 1 10
D/DotMatrix( 1533): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
D/SmartNS_Utility( 3450): usb_cable_connect = 1
D/SmartNS_Utility( 3450): usb_denied = 0
I/SmartNS_PSService( 3450): KeyGuard locked:falseKeyGuard is secured:false
D/SmartNS_PSService( 3450): USB Plugged, Set USBPlugged=  truePSenabled:false
D/Process (  904): killProcessQuiet, pid=3186
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/RemoteViews( 1107): com.android.settings (true,33751552)
I/ActivityManager(  904): Killing 3186:com.google.android.partnersetup/u0a31 (adj 15): empty #17
I/RemoteViews.Performance( 1107): com.android.settings 1 1 10
I/ActivityManager(  904): Recipient 3186
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/WeatherUtility( 3262): can't get weather sync account
D/AppWidgetHostView( 1245): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider})
I/RemoteViews( 1245): com.google.android.googlequicksearchbox (false,0)
I/RemoteViews.Performance( 1245): com.google.android.googlequicksearchbox 1 3 5
W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
I/ActivityManager(  904): Delay finish: pl.k2.droidoaudioteka/.ui.widgets.BigWidgetProvider
D/AppWidgetHostView( 1245): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{pl.k2.droidoaudioteka/pl.k2.droidoaudioteka.ui.widgets.BigWidgetProvider})
I/RemoteViews( 1245): pl.k2.droidoaudioteka (false,0)
I/RemoteViews.Performance( 1245): pl.k2.droidoaudioteka 1 0 8
W/WeatherRequest( 3262): request cur loc, but there is no sys cur
W/Settings( 3262): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/jxcore-log( 3357): Initializing JXcore engine
W/jxcore-log( 3357): JXcore engine is ready
I/ActivityManager(  904): Resuming delayed broadcast
D/AppWidgetHostView( 1245): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
I/RemoteViews( 1245): com.htc.widget.weatherclock (true,33751552)
W/jxcore-log( 3357): Starting JXcore engine
I/ActivityManager(  904): Delay finish: com.google.android.gms/.playlog.service.MonitorAlarmReceiver
I/RemoteViews.Performance( 1245): com.htc.widget.weatherclock 0 7 17
D/LocationManagerService(  904): getAllProviders()=[passive, gps, network]
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1195/10028)
I/ActivityManager(  904): Resuming delayed broadcast
I/ActivityManager(  904): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1195/10028)
I/ActivityManager(  904): Resuming delayed broadcast
I/ActivityManager(  904): Delay finish: com.google.android.gms/.security.snet.SnetBootCompletedReceiver
V/AlarmManager(  904): sending alarm PendingIntent{42d85ed0: PendingIntentRecord{42dcc1e8 com.google.android.gms startService}}, i=null, t=0, cnt=17077, w=84918423, Int=84918423
I/ActivityManager(  904): Resuming delayed broadcast
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1195/10028)
D/SnetService( 1195): snet destroyed
D/PackageBroadcastService( 1195): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
I/ActivityManager(  904): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
D/PMS     (  904): acquireWL(4301ef80): PARTIAL_WAKE_LOCK  Icing 0x1 1195 10028 null
D/PMS     (  904): releaseWL(4301ef80): PARTIAL_WAKE_LOCK  Icing 0x1 null
W/jxcore-log( 3357): Platform android
W/jxcore-log( 3357): 
W/jxcore-log( 3357): Process ARCH arm
W/jxcore-log( 3357): 
I/PeopleContactsSync( 1195): CP2 sync disabled
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1195, uid=10028, userID:0
I/jxcore-log( 3357): JXcore Cordova bridge is ready!
I/jxcore-log( 3357): 
W/jxcore-log( 3357): JXcore engine is started
E/jxcore-log( 3357): >> HTC-HTC Desire 820
E/jxcore-log( 3357): 
I/jxcore-log( 3357): Total memory 1964650496
I/jxcore-log( 3357): 
I/jxcore-log( 3357): Free memory 718315520
I/jxcore-log( 3357): 
I/jxcore-log( 3357): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3357): 
I/jxcore-log( 3357): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3357): 
I/jxcore-log( 3357): userPath [ 'www' ]
I/jxcore-log( 3357): 
I/jxcore-log( 3357): Size 720 1184
I/jxcore-log( 3357): 
I/jxcore-log( 3357): Screen Brightness 10
I/jxcore-log( 3357): 
E/jxcore-log( 3357): Dummy Error Log.
E/jxcore-log( 3357): 
I/HtcModeClient( 1486): handler message = 4011
E/HtcModeClient( 1486): Check connection and retry 5 times.
I/ActivityManager(  904): Resuming delayed broadcast
I/ActivityManager(  904): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=3486 uid=10031 gids={50031, 3003, 5012}
I/ActivityManager(  904): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
I/ActivityManager(  904): Resuming delayed broadcast
I/ActivityManager(  904): Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
I/ActivityManager(  904): Resuming delayed broadcast
I/[PluginManager]RegisterService( 1411): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.example.hello
I/[PluginManager]RegisterService( 1411): handle notify Blinkfeed plugin client changed
I/ActivityManager(  904): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  904): Resuming delayed broadcast
I/ActivityManager(  904): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=3502 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=3502, uid=10073, userID:0
D/Finsky  ( 3502): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  904): getAllNetworkInfo called by com.android.vending (3502/10073)
D/ConnectivityService(  904): getAllNetworkInfo called by com.android.vending (3502/10073)
,D/Finsky  ( 3502): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 3502): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3502): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=3502, uid=10073, userID:0
,D/Process (  904): killProcessQuiet, pid=3198
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/Prism.PackageStateRece_( 1245): action: android.intent.action.PACKAGE_ADDED
,I/ActivityManager(  904): Killing 3198:com.htc.contacts/u0a41 (adj 15): empty #17
D/Finsky  ( 3502): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3502): [1] 2.run: Finished loading 1 libraries.
,I/IcingCorporaProvider( 2750): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
I/ActivityManager(  904): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
I/ActivityManager(  904): Recipient 3198
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Finsky  ( 3502): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager(  904): Delaying start of: ServiceRecord{42dfc470 u0 com.android.vending/com.google.android.finsky.services.RestoreService}
,D/PMS     (  904): acquireWL(42f67fa0): PARTIAL_WAKE_LOCK  Icing 0x1 1195 10028 null
,D/PMS     (  904): releaseWL(42f67fa0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  904): acquireWL(42c5bff8): PARTIAL_WAKE_LOCK  Icing 0x1 1195 10028 null
,D/PMS     (  904): releaseWL(42c5bff8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  904): acquireWL(42f75b20): PARTIAL_WAKE_LOCK  Icing 0x1 1195 10028 null
,D/PMS     (  904): releaseWL(42f75b20): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  904): acquireWL(42f83708): PARTIAL_WAKE_LOCK  Icing 0x1 1195 10028 null
D/PMS     (  904): releaseWL(42f83708): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  904): acquireWL(42e8f5f8): PARTIAL_WAKE_LOCK  Icing 0x1 1195 10028 null
,D/PMS     (  904): releaseWL(42e8f5f8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  904): acquireWL(42d4e028): PARTIAL_WAKE_LOCK  Icing 0x1 1195 10028 null
,D/PMS     (  904): releaseWL(42d4e028): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  904): acquireWL(42e0f218): PARTIAL_WAKE_LOCK  Icing 0x1 1195 10028 null
,D/PMS     (  904): releaseWL(42e0f218): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  904): acquireWL(42d70fe8): PARTIAL_WAKE_LOCK  Icing 0x1 1195 10028 null
,D/PMS     (  904): releaseWL(42d70fe8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/jxcore-log( 3357): getBuffer is called!!!!
I/jxcore-log( 3357): 
D/PMS     (  904): acquireWL(42d73a18): PARTIAL_WAKE_LOCK  Icing 0x1 1195 10028 null
D/PMS     (  904): releaseWL(42d73a18): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  904): acquireWL(42ff8710): PARTIAL_WAKE_LOCK  Icing 0x1 1195 10028 null
,D/PMS     (  904): releaseWL(42ff8710): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  904): acquireWL(4306d890): PARTIAL_WAKE_LOCK  Icing 0x1 1195 10028 null
,D/PMS     (  904): releaseWL(4306d890): PARTIAL_WAKE_LOCK  Icing 0x1 null
,W/asset   ( 2750): Copying FileAsset 0x6475bed8 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,I/IcingCorporaProvider( 2750): UpdateCorporaTask done [took 249 ms] updated apps [took 249 ms] 
,D/Finsky  ( 3502): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=3539 uid=10098 gids={50098, 3003, 5012}
,I/DeviceManagement( 3539): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=3539 dbg=false s=true
,I/DeviceManagement( 3539): PackageUpdateReceiver: vvv Package added: [com.example.hello]
,I/ActivityManager(  904): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=3552 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,D/Process (  904): killProcessQuiet, pid=3242
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  904): Killing 3242:com.htc.calendar/u0a13 (adj 15): empty #17
I/ActivityManager(  904): Recipient 3242
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  904): killProcessQuiet, pid=3025
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3025:com.android.settings:remote/1000 (adj 15): empty #17
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Recipient 3025
,W/CpuWake (  904): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  904): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  904): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  904): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  904): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  904): <<release mCpuPerf_Freq wakelock
D/PMS     (  904): releaseHCC(4307cec0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  904): releaseHCC(42ffeda0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/GAV2    ( 3552): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  904): Start proc com.htc.backup for broadcast com.htc.backup/.task.restore.PackageInstallReceiver: pid=3573 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,V/AlarmManager(  904): sending alarm PendingIntent{42e3cf70: PendingIntentRecord{42aa2118 com.android.vending startService}}, i=null, t=0, cnt=1, w=1450189304468, Int=0
,I/htcbackup-core( 3573): ModelRegistry: Loading model meta data from resources...
,W/ContextImpl( 3573): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
W/ContextImpl( 3573): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 com.htc.cs.dm.config.ConfigManager.getConfig:322 
,I/DeviceManagement( 3539): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=44]
,I/DeviceManagement( 3539): ConfigManagerBoundService: Caller: uid=android.uid.system:1000 (1000) packages=[com.htc.guide, com.qualcomm.timeservice, com.htc.mirrorlinkserver, com.htc.backup, com.android.CSDFunctionG, com.qualcomm.privinit, com.htc.lockscreen, com.htc.usage, android, com.htc.android.htcsetupwizard, com.android.providers.settings, com.htc.android.htcloglevel, com.android.keychain, com.android.location.fused, com.htc.feedback, com.htc.home.personalize, com.htc.autobot.cargps.provider, com.htc.cirmodule, com.android.settings, com.htc.smartdim, com.htc.backupreset, com.htc.drive.activator, com.android.inputdevices, com.htc.checkinprovider, com.htc.htcpowermanager]
,I/DeviceManagement( 3539): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=44], appID=com.htc.backup}]]
,I/ActivityManager(  904): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=3592 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
,I/DeviceManagement( 3539): WorkflowService: Starting workflow service
I/DeviceManagement( 3539): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@42338848] args=[Bundle[mParcelledData.dataSize=144]]
,I/DeviceManagement( 3539): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=144]
,I/DeviceManagement( 3539): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 3539): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 3539): SessionStateController: Checking invariants...
,W/GLSUser ( 1346): GoogleAccountDataService.getToken()
,D/HtcCupdReceiver(Provider)( 3592):  @@@@@ receive action=android.intent.action.PACKAGE_ADDED
W/GLSActivity( 1346): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1346): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1346): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/ActivityManager(  904): Delay finish: com.htc.providers.settings/.HtcCupdReceiver
,I/ActivityManager(  904): Resuming delayed broadcast
,W/GLSUser ( 1346): GoogleAccountDataService.getToken()
I/ActivityManager(  904): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=3606 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,W/GAV2    ( 3552): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,D/Process (  904): killProcessQuiet, pid=3277
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  904): Killing 3277:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
W/GLSActivity( 1346): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1346): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1346): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/ActivityManager(  904): Recipient 3277
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Finsky  ( 3502): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3502): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,I/DeviceManagement( 3539): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
,I/DeviceManagement( 3539): SessionStateController: Checking invariants...
,I/ActivityManager(  904): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  904): acquireWL(42423040): PARTIAL_WAKE_LOCK  AsyncService 0x1 3606 10160 null
,D/PMS     (  904): releaseWL(42423040): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  904): Resuming delayed broadcast
,D/PMS     (  904): acquireWL(42cb5230): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 3606 10160 null
,I/DeviceManagement( 3539): ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 3539): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@42338848]
,I/DeviceManagement( 3539): WorkflowService: Stopping workflow service
,D/Process (  904): killProcessQuiet, pid=3308
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3308:com.htc.stock/u0a81 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3308
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/AdsMeasurementBroadcastReceiver( 1195): Reporting settings might have changed, alerting AdsMeasurementService
,D/AdsMeasurementBroadcastReceiver( 1195): Unauthorized to start the main service
,I/ActivityManager(  904): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=3635 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/PMS     (  904): acquireWL(42a16638): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 3606 10160 null
,D/PMS     (  904): releaseWL(42cb5230): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.plus (3606/10160)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.plus (3606/10160)
,D/Settings:HtcWirelessFeatureFlags( 3450): id/is att sku: 99/false
,W/SystemReader( 3450): Cannot find devicepolicy_lower_fp_quality, use default value instead
,D/Process (  904): killProcessQuiet, pid=3320
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  904): releaseWL(42a16638): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
I/ActivityManager(  904): Killing 3320:com.htc.stock:remote/u0a81 (adj 15): empty #17
W/ContextImpl( 3635): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PowerUsageService( 3635): call getInstance()
I/ActivityManager(  904): Recipient 3320
,W/SystemReader( 3450): Cannot find support_harman, use default value instead
,W/SystemReader( 3450): Cannot find effect_manager_id, use default value instead
,D/PowerUsageList:PowerUsageHelper( 3635): MY_DEBUG = false
,W/WeatherUtility( 1107): can't get weather sync account
,D/PMS     (  904): acquireWL(4285e208): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3635 1000 null
,D/WeatherUtility( 1411): Weather sync is On
E/Settings:HtcWrapHeaderInfo( 3450): no such activity!
,D/WSP     ( 1411): [Receiver] auto sync agent, auto sync is enabled, reset schedule
I/ActivityManager(  904): Delay finish: com.htc.widget.weatherclock/.util.WidgetReceiver
,W/WeatherUtility( 3262): can't get weather sync account
W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3450): The wrap header doesn't exist in header list.
W/BatSI   (  904): Couldn't get kernel wake lock stats
E/Settings:HtcWrapHeaderInfo( 3450): updateDevelopment, bPrefShow = true
W/WeatherRequest( 3262): request cur loc, but there is no sys cur
W/Settings( 3262): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/Settings:HtcUmcWidgetEnabler( 3450): isSupportMusicChannel(): false
,D/AppWidgetHostView( 1245): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3450): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3450): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3450): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3450): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3450): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3450): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3450): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3450): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3450): [supportHomeButton]support         :false
,I/RemoteViews( 1245): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1245): com.htc.widget.weatherclock 8 9 17
,W/FingerprintManager( 3450): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
,E/Settings:HtcVoWifiWidgetEnabler( 3450): isSupportVoWifi: null
I/ActivityManager(  904): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3450): Failed to find provider info for com.htc.vowifi
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,W/GLSUser ( 1346): GoogleAccountDataService.getToken()
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3450): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3450): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 3450): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3450): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3450): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3450): [supportRecentAppsButton]support         :false
,W/GLSActivity( 1346): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/BatSI   (  904): Couldn't get kernel wake lock stats
,D/PMS     (  904): releaseWL(42dd47f0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/GLSUser ( 1346): GLS error: BadAuthentication thalitester@gmail.com androidmarket
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3450): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3450): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3450): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3450): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3450): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3450): [supportHomeButton]support         :false
W/GLSActivity( 1346): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/FingerprintManager( 3450): hasFingerprint() - sSensorCode = 0
,E/Settings:HtcVoWifiWidgetEnabler( 3450): isSupportVoWifi: null
,W/Finsky  ( 3502): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
I/ActivityManager(  904): Cannot resolve ContentProvider=com.htc.vowifi
,E/ActivityThread( 3450): Failed to find provider info for com.htc.vowifi
D/Finsky  ( 3502): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 3502): [1] DailyHygiene.reschedule: Scheduling new run in 92 minutes (failures=3)
,I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=3657 uid=10032 gids={50032, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
,D/Process (  904): killProcessQuiet, pid=3214
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3214:com.htc.widget.hmsproc1/u0a38 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3214
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=3674 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,V/AlarmManager(  904): sending alarm PendingIntent{42d2c050: PendingIntentRecord{42b91f90 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1450189306088, Int=0
,D/Process (  904): killProcessQuiet, pid=3230
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3230:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3230
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  904): killProcessQuiet, pid=2629
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 2629:com.htc.sense.mms/u0a64 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 2629
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/MusicStore( 3674): Database version: 95
,W/ContextImpl( 3674): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 3674): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3674): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3674): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,W/Vold    (  348): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3674): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=3674, uid=10154, userID:0
,D/WifiDisplayAdapter(  904): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  904):     Client/Owner: Client
D/WifiDisplayAdapter(  904):     GroupId: 
D/WifiDisplayAdapter(  904):     Passphrase: 
D/WifiDisplayAdapter(  904):     SessionId: 0
D/WifiDisplayAdapter(  904):     IP Address: }
,D/MediaRouterService(  904): Client com.google.android.music (pid 3674): Registered
,D/WifiDisplayAdapter(  904): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  904):     Client/Owner: Client
D/WifiDisplayAdapter(  904):     GroupId: 
D/WifiDisplayAdapter(  904):     Passphrase: 
D/WifiDisplayAdapter(  904):     SessionId: 0
D/WifiDisplayAdapter(  904):     IP Address: }
I/MediaRouter( 3674): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/ActivityManager(  904): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=3693 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.music (3674/10154)
,D/MediaRouter( 3674): getSelectedRoute
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=3674, uid=10154, userID:0
D/Process (  904): killProcessQuiet, pid=3293
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3293:com.htc.task/u0a70 (adj 15): empty #17
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Recipient 3293
,D/DFPI.PIReciver( 3693): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/DFPI.ApkInstallService( 3693): onHandleIntent
,I/DFPI.ApkInstallService( 3693): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3693): check CID = HTC__032
,I/DFPI.ApkInstallService( 3693): There is no Demo.apk in sd card or phone storage
,I/ActivityManager(  904): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=3709 uid=10051 gids={50051, 1028, 1015, 3003, 5012}
,I/ActivityManager(  904): Delay finish: com.htc.musicenhancer/.provider.MScannerReceiver
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.musicenhancer (3709/10051)
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3709): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,I/SocialFeedProvider( 1245): +disConnect socialManager
,I/SocialFeedProvider( 1245): disconnect socialManager
,I/SocialFeedProvider( 1245): -disConnect socialManager
,D/PMS     (  904): releaseWL(4285e208): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/SensorManager(  904): mEventCount = 300
,I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=3727 uid=10080 gids={50080, 5001, 1028, 1015}
,V/AlarmManager(  904): sending alarm PendingIntent{42903d98: PendingIntentRecord{42c395a0 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1450189307682, Int=0
,I/SocialManager[SocialBiLogHelper]( 3339): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 3339): last commit ulog time 1450072758933
,I/SocialManager[SocialBiLogHelper]( 3339): do commit ulog
,I/SoundPicker( 3727): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3727): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3727): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3727): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3727): TurnFileToMediaUriService fromMediaScanned = true
,I/SoundPicker( 3727): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
I/ActivityManager(  904): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,D/RingtoneManager( 3727): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,D/RingtoneManager( 3727): MODE_GSM access default DB
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3727): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
,D/RingtoneManager( 3727): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3727): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
,D/RingtoneManager( 3727): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3727): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
,D/RingtoneManager( 3727): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3727): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
,D/RingtoneManager( 3727): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,W/SoundPicker( 3727): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
,I/ActivityManager(  904): Delaying start of: ServiceRecord{42dd6158 u0 com.htc.launcher/com.htc.BiLogClient.BiLogUploadService}
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 3727): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 3727): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 3727): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3727): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3727): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3727): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3727): MODE_GSM access default DB
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3727): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3727): getActualDefaultRingtoneUri(context, 1, mode_cdma)
,I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
,I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3727): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3727): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
,I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3727): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3727): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
,I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3727): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,D/RingtoneManager( 3727): getActualDefaultRingtoneUri(context, 4)
,I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
,I/SoundPicker( 3727): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
,I/SoundPicker( 3727): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
,I/SoundPicker( 3727): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
,I/SoundPicker( 3727): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
,I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3727): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,V/SocialManagerService( 1411): getDataSources
,I/SocialManagerService( 1411): plugin added: com.facebook.auth.login
,I/SocialManagerService( 1411): plugin added: com.twitter.android.auth.login
I/SocialManagerService( 1411): plugin added: com.htc.linkedin
I/SocialManagerService( 1411): plugin added: com.htc.venuesrecommend
I/SocialManagerService( 1411): plugin added: com.htc.sense.socialnetwork.instagram
I/SocialManagerService( 1411): plugin added: pl.k2.droidoaudioteka.blinkfeed.AudiotekaPlugin
I/SocialManagerService( 1411): plugin added: com.htc.drive.activator
I/SocialManagerService( 1411): plugin added: com.htc.socialnetwork.rss.octopus
I/SocialManagerService( 1411): plugin added: com.htc.opensense.htcnews
,I/SocialManagerService( 1411): plugin added: com.google
,I/SocialManagerService( 1411): device total memory: 1873M
,D/Process (  904): killProcessQuiet, pid=3369
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/SocialManagerService( 1411): groupAccounts
I/ActivityManager(  904): Start proc com.htc.launcher:biclient for service com.htc.launcher/com.htc.BiLogClient.BiLogUploadService: pid=3745 uid=10075 gids={50075, 3003, 5012, 1028, 1015, 5001, 1023}
I/ActivityManager(  904): Killing 3369:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3369
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/SocialManagerService( 1411): cannot find this plugin service: com.htc.drive.activator
E/SocialManagerService( 1411): error when get process name! process name is null!
,E/SocialManagerService( 1411): skip binding the plugin without process namecom.htc.drive.activator
,I/SocialManagerService( 1411): add com.facebook.auth.login to pending queue!
I/SocialManagerService( 1411): add com.htc.linkedin to pending queue!
I/SocialManagerService( 1411): add com.twitter.android.auth.login to pending queue!
I/SocialManagerService( 1411): add com.htc.venuesrecommend to pending queue!
I/SocialManagerService( 1411): add pl.k2.droidoaudioteka.blinkfeed.AudiotekaPlugin to pending queue!
I/SocialManagerService( 1411): add com.htc.sense.socialnetwork.instagram to pending queue!
I/SocialManagerService( 1411): add com.htc.socialnetwork.rss.octopus to pending queue!
I/SocialManagerService( 1411): add com.htc.opensense.htcnews to pending queue!
I/SocialManagerService( 1411): add com.google to pending queue!
I/SocialManagerService( 1411): consume pending plugin session
I/SocialManagerService( 1411): add com.facebook.auth.login to process map!
,V/SocialManagerService( 1411): initiating bind to plugin type com.facebook.auth.login
,I/SocialManagerService( 1411): com.facebook.auth.login connecting, adding msg, has message?true
,I/ImageRamCache( 3745): create image Cache, size: 31457280.
I/ImageRamCache( 3745): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 3745): create image Cache, size: 12582912.
I/SocialManagerService( 1411): add com.htc.linkedin to process map!
V/SocialManagerService( 1411): initiating bind to plugin type com.htc.linkedin
,I/SocialManagerService( 1411): com.htc.linkedin connecting, adding msg, has message?true
I/SocialManagerService( 1411): add com.twitter.android.auth.login to process map!
,V/SocialManagerService( 1411): initiating bind to plugin type com.twitter.android.auth.login
,I/SocialManagerService( 1411): com.twitter.android.auth.login connecting, adding msg, has message?true
,I/FeedSettings( 3745): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
,I/FeedSettings( 3745): GroupBudget 0.500000 0.380000
I/SocialManagerService( 1411): add com.htc.venuesrecommend to process map!
I/FeedSettings( 3745): GroupBudget 60 45 15
V/SocialManagerService( 1411): initiating bind to plugin type com.htc.venuesrecommend
,I/SocialManagerService( 1411): com.htc.venuesrecommend connecting, adding msg, has message?true
,I/ActivityManager(  904): Start proc com.htc.sense.socialplugins for service com.htc.sense.socialnetwork.facebook/com.htc.plugin.facebook.FacebookSocialPluginService: pid=3758 uid=10025 gids={50025, 3003, 5012, 1028, 1015, 1023}
I/Prism.ExternalStringMa_( 3745): changeLocale(): en_GB
I/SocialManagerService( 1411): add pl.k2.droidoaudioteka.blinkfeed.AudiotekaPlugin to process map!
V/SocialManagerService( 1411): initiating bind to plugin type pl.k2.droidoaudioteka.blinkfeed.AudiotekaPlugin
I/SocialManagerService( 1411): pl.k2.droidoaudioteka.blinkfeed.AudiotekaPlugin connecting, adding msg, has message?true
I/SocialManagerService( 1411): skip to add com.htc.sense.socialnetwork.instagram, plugin per process full!
I/SocialManagerService( 1411): add com.htc.socialnetwork.rss.octopus to process map!
V/SocialManagerService( 1411): initiating bind to plugin type com.htc.socialnetwork.rss.octopus
I/SocialManagerService( 1411): com.htc.socialnetwork.rss.octopus connecting, adding msg, has message?true
D/LocationSocialPlugin( 3339): onBind
I/SocialManagerService( 1411): add com.htc.opensense.htcnews to process map!
V/SocialManagerService( 1411): initiating bind to plugin type com.htc.opensense.htcnews
I/SocialManagerService( 1411): com.htc.opensense.htcnews connecting, adding msg, has message?true
I/SocialManagerService( 1411): com.htc.venuesrecommend connected, removed msg, has message?false
I/Prism.AllAppsOptionsMa_( 3745): loadSortType() with Custom
I/Prism.AllAppsOptionsMa_( 3745): loadGridSize() with Alternative
I/SocialManagerService( 1411): skip to add com.google, plugin per process full!
,I/SocialManagerService( 1411): pl.k2.droidoaudioteka.blinkfeed.AudiotekaPlugin connected, removed msg, has message?false
,D/LocationIdentityProvider( 3339): is_approved false
D/LocationSocialPlugin( 3339): account null
,I/SocialManagerService( 1411): com.htc.socialnetwork.rss.octopus connected, removed msg, has message?false
D/BlinkFeedPluginService( 1751): Set icon to :2130837679
D/BlinkFeedPluginService( 1751): class com.htc.blinkfeed.provider.DummyIdentityProvider
,D/BlinkFeedPluginService( 1751): Not filterable
,D/SocialManagerService( 1411): handling plugin: pl.k2.droidoaudioteka.blinkfeed.AudiotekaPlugin set result in bg
I/SocialManagerService( 1411): remove account type: pl.k2.droidoaudioteka.blinkfeed.AudiotekaPlugin from process map!
I/SocialManagerService( 1411): remove process: pl.k2.droidoaudioteka from process map!
,D/StreamPluginService( 3339): getDataSources start
V/SocialManagerService( 1411): on plugin completed! plugin session type pl.k2.droidoaudioteka.blinkfeed.AudiotekaPlugin
,I/SocialManagerService( 1411): consume pending plugin session
I/SocialManagerService( 1411): skip to add com.google, plugin per process full!
,I/SocialManagerService( 1411): skip to add com.htc.sense.socialnetwork.instagram, plugin per process full!
,D/LocationSocialPlugin( 3339): URI:intent:#Intent;component=com.htc.launcher/com.htc.venuesrecommend.AuthActivity;end
,D/SocialManagerService( 1411): handling plugin: com.htc.venuesrecommend set result in bg
,I/SocialManagerService( 1411): remove account type: com.htc.venuesrecommend from process map!
V/SocialManagerService( 1411): on plugin completed! plugin session type com.htc.venuesrecommend
I/SocialManagerService( 1411): consume pending plugin session
I/SocialManagerService( 1411): skip to add com.google, plugin per process full!
,I/SocialManagerService( 1411): skip to add com.htc.sense.socialnetwork.instagram, plugin per process full!
D/SocialManagerService( 1411): handling plugin: com.htc.socialnetwork.rss.octopus set result in bg
,I/SocialManagerService( 1411): remove account type: com.htc.socialnetwork.rss.octopus from process map!
V/SocialManagerService( 1411): on plugin completed! plugin session type com.htc.socialnetwork.rss.octopus
I/SocialManagerService( 1411): consume pending plugin session
I/SocialManagerService( 1411): skip to add com.google, plugin per process full!
,I/SocialManagerService( 1411): skip to add com.htc.sense.socialnetwork.instagram, plugin per process full!
,I/SocialManagerService( 1411): com.htc.opensense.htcnews connected, removed msg, has message?false
,D/SocialManagerService( 1411): handling plugin: com.htc.opensense.htcnews set result in bg
I/SocialManagerService( 1411): remove account type: com.htc.opensense.htcnews from process map!
,I/SocialManagerService( 1411): remove process: com.htc.sense.news from process map!
,V/SocialManagerService( 1411): on plugin completed! plugin session type com.htc.opensense.htcnews
I/SocialManagerService( 1411): consume pending plugin session
I/SocialManagerService( 1411): skip to add com.google, plugin per process full!
,I/SocialManagerService( 1411): skip to add com.htc.sense.socialnetwork.instagram, plugin per process full!
,I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,D/LinkedIn( 3758): contentprovider oncreate getReadableDatabase
,I/SocialManagerService( 1411): com.facebook.auth.login connected, removed msg, has message?false
,D/LinkedIn( 3758): service onBind
,I/SocialManagerService( 1411): com.htc.linkedin connected, removed msg, has message?false
D/g       ( 3758): get htcisdemo: false
,D/FacebookSocialPluginService( 3758): get htcisdemo: false
D/Facebook_Session( 3758): MSG_QUERY_ACCOUNT
D/Facebook_Session( 3758): queryAccount
,D/Facebook_Session( 3758): queryAccount enter lock
I/SocialManagerService( 1411): com.twitter.android.auth.login connected, removed msg, has message?false
,D/Facebook_Session( 3758): Facebook Session created
,D/Facebook_Session( 3758): queryAccount
,D/SocialManagerService( 1411): handling plugin: com.htc.linkedin set result in bg
,I/SocialManagerService( 1411): remove account type: com.htc.linkedin from process map!
V/SocialManagerService( 1411): on plugin completed! plugin session type com.htc.linkedin
I/SocialManagerService( 1411): consume pending plugin session
,I/SocialManagerService( 1411): add com.google to process map!
V/SocialManagerService( 1411): initiating bind to plugin type com.google
,I/SocialManagerService( 1411): com.google connecting, adding msg, has message?true
,I/SocialManagerService( 1411): skip to add com.htc.sense.socialnetwork.instagram, plugin per process full!
D/Facebook_Session( 3758): Query Facebook account complete
D/Facebook_Session( 3758): queryAccount enter lock
,D/GooglePlusSocialPluginService( 3758): Bind
,I/SocialManagerService( 1411): com.google connected, removed msg, has message?false
D/Facebook_Session( 3758): Query Facebook account complete
,I/GooglePlusSocialPluginService( 3758): getDataSources start
,D/SocialManagerService( 1411): handling plugin: com.twitter.android.auth.login set result in bg
,I/SocialManagerService( 1411): remove account type: com.twitter.android.auth.login from process map!
V/SocialManagerService( 1411): on plugin completed! plugin session type com.twitter.android.auth.login
I/SocialManagerService( 1411): consume pending plugin session
I/SocialManagerService( 1411): add com.htc.sense.socialnetwork.instagram to process map!
,V/SocialManagerService( 1411): initiating bind to plugin type com.htc.sense.socialnetwork.instagram
,I/SocialManagerService( 1411): com.htc.sense.socialnetwork.instagram connecting, adding msg, has message?true
,D/SocialManagerService( 1411): handling plugin: com.facebook.auth.login set result in bg
,I/GooglePlusSocialPluginService( 3758): getDataSources end
,I/SocialManagerService( 1411): remove account type: com.facebook.auth.login from process map!
,I/SocialManagerService( 1411): com.htc.sense.socialnetwork.instagram connected, removed msg, has message?false
V/SocialManagerService( 1411): on plugin completed! plugin session type com.facebook.auth.login
,D/SocialManagerService( 1411): handling plugin: com.google set result in bg
,I/SocialManagerService( 1411): remove account type: com.google from process map!
,D/GooglePlusSocialPluginService( 3758): Unbind
V/SocialManagerService( 1411): on plugin completed! plugin session type com.google
,D/SocialManagerService( 1411): handling plugin: com.htc.sense.socialnetwork.instagram set result in bg
,I/SocialManagerService( 1411): remove account type: com.htc.sense.socialnetwork.instagram from process map!
,I/SocialManagerService( 1411): remove process: com.htc.sense.socialplugins from process map!
,V/SocialManagerService( 1411): on plugin completed! plugin session type com.htc.sense.socialnetwork.instagram
,I/SocialManagerService( 1411): onSessionCompleted
D/Process (  904): killProcessQuiet, pid=3392
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  904): Killing 3392:com.htc.mobiledata/u0a91 (adj 15): empty #17
I/SocialManager[SocialBiLogHelper]( 3339): social manager disconnect
,I/ActivityManager(  904): Delaying start of: ServiceRecord{42cf7f90 u0 com.htc.launcher/com.htc.BiLogClient.BiLogUploadService}
,D/Process (  904): killProcessQuiet, pid=3427
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3427:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3392
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Recipient 3427
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  904): Client connection lost with reason: 4
,D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  904): disable(): mBluetooth = null mBinding = false
W/HtcDLNAServiceManager(  904): Settings:AgentMONITOR_LOG
,W/HtcDLNAServiceManager(  904): Settings:Agentname: bluetooth_on
W/HtcDLNAServiceManager(  904): Settings:Agentvalue: 0
W/Settings:Agent(  904): >> traceCallingStack()
,W/Settings:Agent(  904): Process.myPid(): 904
W/Settings:Agent(  904): Process.myTid(): 1410
,W/Settings:Agent(  904): Process.myUid(): 1000
W/Settings:Agent(  904): 
W/Settings:Agent(  904): 
,W/System.err(  904): java.lang.Throwable: stack dump
,W/System.err(  904): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  904): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
,W/System.err(  904): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  904): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
,W/System.err(  904): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  904): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
,W/System.err(  904): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
,W/System.err(  904): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:583)
W/System.err(  904): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  904): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  904): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  904): 
,W/Settings:Agent(  904): << traceCallingStack(): 6(ms)
,D/BluetoothManagerService(  904): Message: MESSAGE_DISABLE
,D/WifiManager( 3357): setWifiEnabled: Base Package Name=com.example.hello, uid=10356
D/WifiService(  904): New client listening to asynchronous messages
W/HtcDLNAServiceManager(  904): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  904): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  904): Settings:Agentvalue: 0
W/Settings:Agent(  904): >> traceCallingStack()
W/Settings:Agent(  904): Process.myPid(): 904
W/Settings:Agent(  904): Process.myTid(): 1266
W/Settings:Agent(  904): Process.myUid(): 1000
W/Settings:Agent(  904): 
W/Settings:Agent(  904): 
,W/System.err(  904): java.lang.Throwable: stack dump,
W/System.err(  904): ,	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  904): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
,W/System.err(  904): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
,W/System.err(  904): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
,W/System.err(  904): 	at android.provider.Settings$Global.putString(Settings.java:6170)
,W/System.err(  904): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
,W/System.err(  904): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
D/WifiService(  904): setWifiEnabled: false pid=3357, uid=10356
E/WifiService(  904): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  904): isSprintWifiRestricted(): false
I/WifiService(  904): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  904): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/System.err(  904): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:114)
W/System.err(  904): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  904): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  904): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  904): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  904): 
W/Settings:Agent(  904): << traceCallingStack(): 12(ms)
I/jxcore-log( 3357): ****TEST TOOK:  5057  ms ****
I/jxcore-log( 3357): 
I/jxcore-log( 3357): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3357): 
,I/HtcModeClient( 1486): handler message = 4011
E/HtcModeClient( 1486): Check connection and retry 6 times.
,I/ActivityManager(  904): Resuming delayed broadcast
,D/DFPI.PIReciver( 3693): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3693): onHandleIntent
,I/DFPI.ApkInstallService( 3693): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3693): check CID = HTC__032
,I/DFPI.ApkInstallService( 3693): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  904): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  904): Resuming delayed broadcast
I/ActivityManager(  904): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,D/CustomizationManager( 3792): ====startRecUseTime====
D/htc.customization.log.level( 3792):  is 
,W/CustomizationLogLevel( 3792): Level value is invalid, use default level 2
,D/CustomizationManager( 3792):  Read ACC file spent 0.052 (s)
D/CIDMapFileReader( 3792): Parsing tag item name = HTC__001
,D/CIDMapFileReader( 3792): Parsing tag item name = HTC__102,
D/CIDMapFileReader( 3792): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3792): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3792): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3792): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3792): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3792): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3792): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 3792): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 3792): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 3792): Parsing tag category name = system
,I/CustomizationCIDLoader( 3792): Parsing tag category name = application
,I/CustomizationCIDLoader( 3792): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3792): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3792): Parsing tag category name = AudioService
,I/CustomizationCIDLoader( 3792): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 3792): Parsing tag category name = Settings
D/CustomizationManager( 3792):  Read CID file spent 0.091 (s)
,D/CustomizationManager( 3792):  All configurations done spent 0.091 (s)
W/HtcNativeFlag( 3792): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3792): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3792): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 3792): Fail to get flag for type 'language', use default value: -1
,D/PackageManager(  904): deletePackageAsUser: pkg=com.example.hello, pid=3792, uid=2000 user=0
,I/ActivityManager(  904): Force stopping com.example.hello appid=10356 user=-1: uninstall pkg
,D/Process (  904): killProcessQuiet, pid=3357
,W/asset   (  904): Copying FileAsset 0x672385b8 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  904): Killing 3357:com.example.hello/u0a356 (adj 0): stop com.example.hello
W/ActivityManager(  904): Force removing ActivityRecord{42a1da50 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,E/JavaBinder(  904): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  904): !!! FAILED BINDER TRANSACTION !!!
,W/ActivityManager(  904): handleTopAppChanged(): The previous AP is died unexpectedly.
,W/PackageSettings(  904): Skipping PackageSetting{42a57f50 com.test.thalitest/10348} due to missing metadata
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/InputDispatcher(  904): channel '42c9ce78 com.example.hello.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  904): channel '42c9ce78 com.example.hello.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  904): Attempted to unregister already unregistered input channel '42c9ce78 com.example.hello.MainActivity (s)'
I/WindowState(  904): WIN DEATH: Window{42c9ce78 u0 com.example.hello/com.example.hello.MainActivity}
D/WifiService(  904): Client connection lost with reason: 4
I/WindowManager(  904): WINDOW DIED Window{42c9ce78 u0 com.example.hello/com.example.hello.MainActivity}
I/ActivityManager(  904): Force stopping com.example.hello appid=10356 user=0: pkg removed
,I/ActivityManager(  904): Waited long enough for: ServiceRecord{42de3010 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,I/ActivityManager(  904): Resuming delayed broadcast
I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver packageName:com.example.hello
I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1533): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1533): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1533): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
,I/acms    ( 1769): Unregistering com.example.hello
,E/acms    ( 1769): Could not unregister removed application com.example.hello
,W/AccTypeManager( 1303): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1303): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/GeofencerStateMachine( 1427): Ignoring removeGeofence because network location is disabled.
I/Prism.ItemManager( 3745): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Prism.ItemManager( 3745): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/FeedHostManager( 1245): [onResume]
,I/FeedProviderManager( 1245): onResume
,I/SocialFeedProvider( 1245): +onResume
,I/SocialFeedProvider( 1245): updateAccounts - Accounts is no change
,D/PMS     (  904): acquireWL(42f54030): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1427 10028 null
I/SocialFeedProvider( 1245): -onResume
I/SoundPicker( 3727): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
W/ContextImpl( 3727): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
I/Prism.ItemManager( 3339): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Prism.ItemManager( 3339): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/ConnectivityHelper( 1245): [getCurrentConnectionType] no network connection
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.launcher (1245/10075)
D/PMS     (  904): releaseWL(42f54030): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/SoundPicker( 3727): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 3727): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3727): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3727): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3727): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3727): MODE_GSM access default DB
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3727): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3727): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
,W/SoundPicker( 3727): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3727): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3727): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3727): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3727): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
,D/RingtoneManager( 3727): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 3727): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 3727): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,W/SoundPicker( 3727): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 3727): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3727): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3727): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3727): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3727): MODE_GSM access default DB
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,W/SystemReader( 1225): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/ActivityManager(  904): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
E/cutils-trace( 3792): Error opening trace file: No such file or directory (2)
D/AccTypeManager( 1303): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/Prism.ItemManager( 1245): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1245): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "sms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1212 :
,I/SoundPicker( 3727): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3727): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
,I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3727): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3727): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
,I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/InputMethodManagerService(  904): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "smsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1212 :
,I/SoundPicker( 3727): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mms"
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3727): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
,I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3727): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3727): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1212 :
,I/SoundPicker( 3727): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "mmsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1212 :
,E/ExternalAccountType( 1303): Unsupported attribute readOnly
,I/SoundPicker( 3727): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
,I/SoundPicker( 3727): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
,I/SoundPicker( 3727): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/GAV2    ( 3552): Thread[GAThread,5,main]: No campaign data found.
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/PackageManager(  904):   Scheme: "sms"
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
,I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3727): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1212 :
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,W/Binder  ( 1182): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1182): java.lang.NullPointerException
W/Binder  ( 1182): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1182): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1182): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1182): 	at dalvik.system.NativeStart.run(Native Method)
I/ActivityManager(  904): Resuming delayed broadcast
W/InputMethodManagerService(  904): Got RemoteException sending setActive(false) notification to pid 3357 uid 10356
I/InputMethodManagerService(  904): Enable input method client, pid=1245
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "smsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1212 :
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1212 :
I/PackageManager(  904):   Scheme: "mms"
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "mmsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1212 :
,D/PhoneApp( 1212): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  904): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,D/DFPI.PIReciver( 3693): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/DFPI.ApkInstallService( 3693): onHandleIntent
I/DFPI.ApkInstallService( 3693): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3693): check CID = HTC__032
,I/DFPI.ApkInstallService( 3693): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  904): Resuming delayed broadcast
,I/SoundPicker( 3727): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3727): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3727): SoundPickerReceiver [onReceive] startService
,I/ActivityManager(  904): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3727): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3727): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3727): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3727): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3727): MODE_GSM access default DB
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3727): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3727): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3727): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3727): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3727): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3727): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3727): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 3727): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 3727): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 3727): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 3727): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 3727): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3727): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3727): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3727): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3727): MODE_GSM access default DB
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3727): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac,
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3727): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3727): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3727): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3727): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3727): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/SoundPicker( 3727): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3727): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
I/SoundPicker( 3727): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
I/SoundPicker( 3727): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
I/SoundPicker( 3727): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
I/SoundPicker( 3727): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/SoundPicker( 3727): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/MediaStoreImporter( 3674): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,D/TelephonyReceiver( 1212): bind: true
I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=3820 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
,I/ActivityManager(  904): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.GenericMessagesProvider: pid=3832 uid=10064 gids={50064, 3003, 5012, 1028, 1015, 1023}
W/PackageManager(  904): Unable to load service info ResolveInfo{42d9b960 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  904): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  904): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  904): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  904): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  904): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  904): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  904): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  904): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  904): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  904): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  904): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  904): 	at dalvik.system.NativeStart.main(Native Method)
,I/ActivityManager(  904): Delay finish: com.htc.task/.TodoTaskReceiver
,D/MessageFrequencyProvider( 3832): onCreate
,V/GetPrviateResource( 3832): GetPrviateResource
,V/GetPrviateResource( 3832): GetPrviateResource
,D/GenericMessagesProvider( 3832): query uri: content://htc-messages/wappush/count
E/SQLiteLog( 3832): (14) cannot open file at line 30190 of [00bb9c9ce4]
,E/SQLiteLog( 3832): (14) os_unix.c:30190: (2) open(/data/data/com.htc.sense.mms/databases/wappush.db) - 
E/SQLiteConnection( 3832): DB info: sqlite3_open_v2, path: /data/data/com.htc.sense.mms/databases/wappush.db, flag: 1, ret: 14
,E/SQLiteConnection( 3832): DB info: errno = 2, errno message = No such file or directory
,E/SQLiteDatabase( 3832): Failed to open database '/data/data/com.htc.sense.mms/databases/wappush.db'.
E/SQLiteDatabase( 3832): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 3832): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3832): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3832): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3832): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3832): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3832): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3832): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3832): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3832): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3832): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
E/SQLiteDatabase( 3832): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
E/SQLiteDatabase( 3832): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 3832): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 3832): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
E/SQLiteDatabase( 3832): 	at android.os.Binder.execTransact(Binder.java:412)
E/SQLiteDatabase( 3832): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 3832): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
W/System.err( 3832): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 3832): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/System.err( 3832): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/System.err( 3832): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/System.err( 3832): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/System.err( 3832): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/System.err( 3832): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/System.err( 3832): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/System.err( 3832): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/System.err( 3832): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
W/System.err( 3832): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
W/System.err( 3832): 	at android.content.ContentProvider.query(ContentProvider.java:869)
W/System.err( 3832): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
W/System.err( 3832): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
W/System.err( 3832): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err( 3832): 	at dalvik.system.NativeStart.run(Native Method)
,D/Process (  904): killProcessQuiet, pid=3486
,I/ActivityManager(  904): Killing 3486:com.google.android.partnersetup/u0a31 (adj 15): empty #17
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
D/TelephonyReceiver( 1212): switchBindHtcMsgCursor: null
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Recipient 3486
,I/ActivityManager(  904): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=3847 uid=10063 gids={50063, 3003, 5012, 1023, 1028, 1015}
,D/MessageCustFlag( 3832): sense_version=6.0
,D/BTAccessoryUtil( 3832): createReceiver
,D/BTAccessoryUtil( 3832): registerReceiver return intent = null
D/MessageCustFlag( 3832): sku_id=99
,W/SystemReader( 3832): Cannot find message_ambs_application_id, use default value instead
,D/Messaging( 3832): supportCMAS(SIE)/init? false/true
D/MmsConfig( 3832): networkCode: 
,D/MessageCustFlag( 3832): sku_id=99
D/MmsConfig( 3832): SIE smsPri: null
,D/MmsConfig( 3832): networkCode: 
,D/DFPI.PIReciver( 3693): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
D/HtcTelephonyCapability( 3832): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 3832): The project is not dual project , phone_feature_type_stand_by = 0
,D/HtcBuildUtils( 3832): getRATByHtcTelephonyCapability:1
,W/SystemReader( 3832): Cannot find qct_8960_interface, use default value instead
I/ActivityManager(  904): Resuming delayed broadcast
I/DFPI.ApkInstallService( 3693): onHandleIntent
I/DFPI.ApkInstallService( 3693): Media Scan Finished Case 
,D/DFPI.ApkInstallService( 3693): check CID = HTC__032
,I/DFPI.ApkInstallService( 3693): There is no Demo.apk in sd card or phone storage
,D/Process (  904): killProcessQuiet, pid=3552
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  904): Resuming delayed broadcast
I/ActivityManager(  904): Killing 3552:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,I/SoundPicker( 3727): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3727): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3727): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3727): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3727): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3727): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3727): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3727): MODE_GSM access default DB
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3727): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3727): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3727): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3727): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3727): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3727): getActualDefaultRingtoneUri(context, 2)
,I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3727): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 3727): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 3727): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 3727): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 3727): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 3727): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3727): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3727): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3727): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3727): MODE_GSM access default DB
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
,I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/ActivityManager(  904): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3727): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3727): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3727): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3727): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/EASAppSvc( 3847): [ NA ]- onCreate()
I/SoundPicker( 3727): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3727): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/EASAppSvc( 3847): [ NA ]> onUpgrade: version = 63
I/SoundPicker( 3727): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3727): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
I/SoundPicker( 3727): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
I/SoundPicker( 3727): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3727): TurnFileToMediaUriServ,ice [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
,I/SoundPicker( 3727): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
,I/SoundPicker( 3727): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3727): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
,I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3727): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3727): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,D/ORMLib  ( 3820): put()
D/RemoteDisplayProvider(  904): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  904): start
,I/ActivityManager(  904): Resuming delayed broadcast
,D/WifiService(  904): New client listening to asynchronous messages
,D/ConnectivityService(  904): getNetworkInfo networkType=1 called by com.htc.android.mail (3847/10063)
,D/ConnectivityService(  904): getNetworkInfo networkType=0 called by com.htc.android.mail (3847/10063)
,I/ActivityManager(  904): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,D/ConnectivityService(  904): getNetworkInfo networkType=55 called by com.htc.android.mail (3847/10063)
I/ActivityManager(  904): Recipient 3552
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/EASAppSvc( 3847): [ NA ]- onDestroy()
,I/EASAppSvc( 3847): [ NA ]> uninitEASService
,I/EASRequestController( 3847): [ NA ]release
,I/EASAppSvc( 3847): [ NA ]< uninitEASService
,I/EASAppSvc( 3847): [ NA ]- onCreate()
,I/EASAppSvc( 3847): [ NA ]> onUpgrade: version = 63
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by com.htc.android.mail (3847/10063)
D/ConnectivityService(  904): getNetworkInfo networkType=0 called by com.htc.android.mail (3847/10063)
D/ConnectivityService(  904): getNetworkInfo networkType=55 called by com.htc.android.mail (3847/10063)
,D/ORMLib  ( 3820): put()
,I/MediaStoreImporter( 3674): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,D/Process (  904): killProcessQuiet, pid=3573
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Resuming delayed broadcast
I/ActivityManager(  904): Killing 3573:com.htc.backup/1000 (adj 15): empty #17
,D/PMS     (  904): acquireWL(42fcea78): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 1486 10014 null
I/EASAppSvc( 3847): [ NA ]- onDestroy()
I/EASAppSvc( 3847): [ NA ]> uninitEASService
I/ActivityManager(  904): Recipient 3573
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=3882 uid=10067 gids={50067, 3003, 5012}
I/EASRequestController( 3847): [ NA ]release
,I/EASAppSvc( 3847): [ NA ]< uninitEASService
I/ActivityManager(  904): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,D/PMS     (  904): releaseWL(42fcea78): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=3900 uid=10084 gids={50084, 3003, 5012, 1028, 1015, 1023, 2001, 5006, 5001}
,D/Process (  904): killProcessQuiet, pid=3502
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/TelephonyReceiver( 1212): bind: false
,D/TelephonyReceiver( 1212): switchBindHtcMsgCursor: null
I/ActivityManager(  904): Killing 3502:com.android.vending/u0a73 (adj 15): empty #17
,I/ActivityManager(  904): Start proc com.google.android.gm for broadcast com.google.android.gm/.MailIntentReceiver: pid=3914 uid=10107 gids={50107, 3003, 5012, 1028, 1015}
I/ActivityManager(  904): Recipient 3502
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  904): killProcessQuiet, pid=3539
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3539:com.htc.cs.dm/u0a98 (adj 15): empty #17
,D/ORMLib  ( 3820): put()
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Recipient 3539
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,W/GAV2    ( 3914): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  904): Delay finish: com.google.android.gm/.MailIntentReceiver
,D/PMS     (  904): acquireWL(42fd16b8): PARTIAL_WAKE_LOCK  Icing 0x1 1195 10028 null
,D/PMS     (  904): releaseWL(42fd16b8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/RemoteViews( 1107): com.htc.updater (true,33751552)
,D/NotificationService(  904): notification sound not played, stream=5 volume=0 always=false
D/DotMatrix( 1533): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false
D/OnDemandProgressBar( 1107): release indeterminate drawable android.widget.OnDemandProgressBar{42356688 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1107): com.htc.updater 8 9 1 10
I/RemoteViews( 1107): com.htc.updater (true,33751552)
,D/OnDemandProgressBar( 1107): release indeterminate drawable android.widget.OnDemandProgressBar{42451218 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1107): com.htc.updater 2 6 1 10
I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Delay finish: com.google.android.gm/.GmailReceiver
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,D/AutoSetting( 1411): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 1411): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1411): service - requestNLP() NetworkLocationProvider not enabled
,I/Gmail   ( 3914): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 3914): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 3914): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3914): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Delay finish: com.google.android.gm/.GmailReceiver
,I/NotifUtils( 3914): Validating Notification, mapSize: 0 getAttention: true ignoreUnobtrusive: false
,I/Prism.ItemManager( 3745): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 3745): loadItems() com.htc.launcher.pageview.WidgetManager@4236c818 +
,I/Prism.WidgetManager( 3745): onLoadItems() +
,I/Prism.ItemManager( 3339): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 3339): loadItems() com.htc.launcher.pageview.WidgetManager@42376cb8 +
,I/Prism.WidgetManager( 3339): onLoadItems() +
,I/NotifUtils( 3914): validateNotifications - cancelling account 61035162 / folder -317575340
I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver: pid=3956 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,D/Process (  904): killProcessQuiet, pid=3592
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3592:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3592
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/AlarmManager(  904): sending alarm PendingIntent{42bba158: PendingIntentRecord{42bae310 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1450189310596, Int=0
,I/Prism.ItemManager( 1245): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1245): loadItems() com.htc.launcher.pageview.WidgetManager@42395f70 +
,I/Prism.WidgetManager( 1245): onLoadItems() +
,E/dalvikvm( 3956): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
,E/ProviderInstaller( 3956): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
,E/dalvikvm( 3956): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
,E/ProviderInstaller( 3956): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
,V/JNIHelp ( 3956): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
,I/Babel   ( 3956): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 3956): MmsConfig.loadMmsSettings
,D/MmsCustomizationProvider( 3832): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 3832): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/Babel   ( 3956): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 3956): MmsConfig.loadFromDatabase
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=3956, uid=10111, userID:0
,E/Babel   ( 3956): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 3956): MmsConfig.loadFromResources
,W/Settings( 3956): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/Babel   ( 3956): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 3956): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=3956, uid=10111, userID:0
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=3956, uid=10111, userID:0
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=3956, uid=10111, userID:0
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=3956, uid=10111, userID:0
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=3956, uid=10111, userID:0
,D/PMS     (  904): acquireWL(42cc0210): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 3956 10111 null
,I/ActivityManager(  904): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,I/ProviderInstaller( 3956): Installed default security provider GmsCore_OpenSSL
,D/PMS     (  904): releaseWL(42cc0210): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  904): Resuming delayed broadcast
,D/PMS     (  904): acquireWL(42b41b40): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 3956 10111 null
,I/ActivityManager(  904): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,W/asset   ( 3745): Copying FileAsset 0x680dc640 (zip:/data/app/com.gameloft.android.gdc-2.apk:/resources.arsc) to buffer size 405676 to make it aligned.
I/Prism.WidgetManager( 3745): onLoadItems() -
,I/Prism.ItemManager( 3745): loadItems() com.htc.launcher.pageview.WidgetManager@4236c818 -
,D/Process (  904): killProcessQuiet, pid=3606
D/PMS     (  904): releaseWL(42b41b40): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
I/ActivityManager(  904): Resuming delayed broadcast
D/PMS     (  904): acquireWL(42e0a698): PARTIAL_WAKE_LOCK  NetworkStats 0x1 904 1000 null
,I/ActivityManager(  904): Killing 3606:com.google.android.apps.plus/u0a160 (adj 15): empty #17
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
W/asset   ( 3339): Copying FileAsset 0x683dbc48 (zip:/data/app/com.gameloft.android.gdc-2.apk:/resources.arsc) to buffer size 405676 to make it aligned.
I/Prism.WidgetManager( 3339): onLoadItems() -
,I/Prism.ItemManager( 3339): loadItems() com.htc.launcher.pageview.WidgetManager@42376cb8 -
D/PMS     (  904): releaseWL(42e0a698): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/PMS     (  904): acquireWL(42ca8740): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 3956 10111 null
I/ActivityManager(  904): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,W/asset   ( 1245): Copying FileAsset 0x681789a0 (zip:/data/app/com.gameloft.android.gdc-2.apk:/resources.arsc) to buffer size 405676 to make it aligned.
E/Prism.WidgetManager( 1245): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1245): onLoadItems() -
,I/Prism.ItemManager( 1245): loadItems() com.htc.launcher.pageview.WidgetManager@42395f70 -
,D/PMS     (  904): releaseWL(42ca8740): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.talk (3956/10111)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.talk (3956/10111)
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Recipient 3606
,D/PhoneApp( 1212): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1212): -- N1 =0
,D/PhoneApp( 1212): -- N2 =0
,D/PhoneApp( 1212): -- N3 =0
,D/Messaging( 3832): mNeedToUpdateDate2 start
,D/MmsConfig( 3832): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 3832): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 3832): 
D/MmsAsyncWorkHandler( 3832): HM tk = 20001
,D/ReportIndicatorCache( 3832): MSG_QUERY_REPORTS >>
D/SettingsManager( 3832): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@4230d400
,D/TelephUtils( 1212): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
D/MmsSmsV2Provider( 1212):  phoneType = -1
,D/MmsSmsV2Provider( 1212): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null,
,I/Messaging( 3832): mccmnc> 
,D/DraftCache( 3832): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 3832): [DraftCache/1] refresh
,D/MmsConfig( 3832): networkCode: ,
,D/Messaging( 3832): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1212): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
,D/AccFlag ( 1212): sku_id=99
,D/PhoneStorageUtil( 3832): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 3832): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 3832): createReceiver
,D/DraftCache( 3832): [DraftCache/388] rebuildCache
,D/TelephUtils( 1212): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
D/MmsSmsV2Provider( 1212):  phoneType = -1
,D/MessageCustFlag( 3832): sense_version=6.0
D/Jerry   ( 3832): start to preload cursor >>>>>>>
,D/MmsSmsV2Provider( 1212): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/TelephUtils( 1212): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
V/MmsProvider( 1212): Update uri=content://mms, match=0
,V/MmsProvider( 1212): selection=st=129 AND m_type!=134
,D/Messaging( 3832): Reset downloading state: 0
,V/MmsSystemEventReceiver( 3832): TransactionService is going to be woken up.
,D/Messaging( 3832): mNeedToUpdateDate2: false
D/TelephUtils( 1212): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
D/MmsSmsV2Provider( 1212):  phoneType = -1
,D/MmsSmsV2Provider( 1212): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/TelephUtils( 1212): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
,I/ActivityManager(  904): Delaying start of: ServiceRecord{42b697b8 u0 com.htc.sense.mms/.transaction.TransactionService}
D/Jerry   ( 1212): URI_DRAFT
D/DraftCache( 3832): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 3832): [DraftCache/388] rebuildCache time: 3
,D/MmsAsyncWorkHandler( 3832): 
D/MmsAsyncWorkHandler( 3832): HM tk = 20002
,D/TelephUtils( 1212): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
,D/MmsSmsV2Provider( 1212):  phoneType = -1
,D/TelephUtils( 1212): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
D/MmsSmsV2Provider( 1212):  phoneType = -1
,D/MmsSmsV2Provider( 1212): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
D/Messaging( 3832): ViewCache CreatePreload
,D/Messaging( 3832): ViewCache CreatePreloadOnlyMultipleOpsList
,D/Cust_MMSMS( 3832): _has_set_default_values_2=true
,D/Messaging( 3832): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/TelephUtils( 1212): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
,D/AccFlag ( 1212): sku_id=99
,D/MsgPreferenceUtils( 3832): def_index: 0
,D/MsgPreferenceUtils( 3832): globalIndex = 1
D/MsgPreferenceUtils( 3832): phone state: true
D/MsgPreferenceUtils( 3832): sd state: false
,D/MsgPreferenceUtils( 3832): vIndex = 0
,D/TelephUtils( 1212): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
,D/AccFlag ( 1212): sku_id=99
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.talk (3956/10111)
,D/PMS     (  904): acquireWL(42dd9790): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,D/DotMatrix( 1533): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1533): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1533): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1107): closing low battery warning: level=100
D/PMS     (  904): releaseWL(42dd9790): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,V/TransactionService( 3832): 1-Creating TransactionService
,V/TransactionService( 3832): onStartCommand: 1
,D/MmsSystemEventReceiver( 3832): unRegisterForConnectionStateChanges
V/TransactionService( 3832): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 3832): Loading previous transactions.
,D/TelephUtils( 1212): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
,D/AccFlag ( 1212): device_type: 1
D/TransactionService( 3832): Force set service start id to 1
V/TransactionService( 3832): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 3832): unRegisterForConnectionStateChanges
,D/TransactionService( 3832): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 3832): Destroying TransactionService
,V/TransactionService( 3832): 4-Handling incoming message: { when=0 what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
I/ActivityManager(  904): Resuming delayed broadcast
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 4
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,D/ConnectivityService(  904): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  904): Done.
,D/ConnectivityService(  904): Setting timer for 720seconds
,D/PackageBroadcastService( 1195): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.aurora
I/ActivityManager(  904): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,I/PeopleContactsSync( 1195): CP2 sync disabled
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1195, uid=10028, userID:0
D/PMS     (  904): acquireWL(42f8d520): PARTIAL_WAKE_LOCK  Icing 0x1 1195 10028 null
,D/PMS     (  904): releaseWL(42f8d520): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ActivityManager(  904): Resuming delayed broadcast
,I/[PluginManager]RegisterService( 1411): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.aurora
,I/[PluginManager]RegisterService( 1411): handle notify Blinkfeed plugin client changed
I/ActivityManager(  904): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4026 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4026, uid=10073, userID:0
,D/Finsky  ( 4026): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  904): getAllNetworkInfo called by com.android.vending (4026/10073)
,D/ConnectivityService(  904): getAllNetworkInfo called by com.android.vending (4026/10073)
,D/Finsky  ( 4026): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 4026): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4026): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4026, uid=10073, userID:0
,D/Finsky  ( 4026): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4026): [1] 2.run: Finished loading 1 libraries.
,D/Process (  904): killProcessQuiet, pid=3450
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  904): Killing 3450:com.android.settings/1000 (adj 15): empty #17
,I/ActivityManager(  904): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
I/IcingCorporaProvider( 2750): Updating corpora: APPS=com.htc.aurora, CONTACTS=MAYBE
,D/Finsky  ( 4026): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager(  904): Delaying start of: ServiceRecord{42d53350 u0 com.android.vending/com.google.android.finsky.services.RestoreService}
,I/IcingCorporaProvider( 2750): UpdateCorporaTask done [took 47 ms] updated apps [took 47 ms] 
,D/Finsky  ( 4026): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  904): Resuming delayed broadcast
,I/HtcModeClient( 1486): handler message = 4011
,E/HtcModeClient( 1486): Check connection and retry 7 times.
I/ActivityManager(  904): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4061 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Recipient 3450
,I/ActivityManager(  904): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  904): acquireWL(42f5f520): PARTIAL_WAKE_LOCK  AsyncService 0x1 4061 10160 null
,D/PMS     (  904): releaseWL(42f5f520): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  904): Resuming delayed broadcast
,D/PMS     (  904): acquireWL(42f62c80): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 4061 10160 null
,D/Process (  904): killProcessQuiet, pid=3635
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=4083 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  904): Killing 3635:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,D/PMS     (  904): acquireWL(42ff46c8): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 4061 10160 null
,D/PMS     (  904): releaseWL(42f62c80): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.plus (4061/10160)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.plus (4061/10160)
,I/ActivityManager(  904): Recipient 3635
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/HtcFingerPrintQuickLaunchProvider( 4083): -onCreate()
,D/PMS     (  904): releaseWL(42ff46c8): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
V/Settings:HtcSettingsApplication( 4083): [4083/4083] onCreate()
,D/PMS     (  904): acquireWL(42f1edd0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3820 10070 null
,D/PMS     (  904): acquireWL(42ff5408): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3820 10070 null
,D/Process (  904): killProcessQuiet, pid=3262
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  904): Killing 3262:com.htc.widget.hmsproc2/u0a42 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3262
,E/TodoTaskNotifyService( 3820): java.lang.NullPointerException
,W/System.err( 3820): java.lang.NullPointerException
W/System.err( 3820): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3820): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3820): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3820): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 3820): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Settings:HtcWirelessFeatureFlags( 4083): id/is att sku: 99/false
,W/SystemReader( 4083): Cannot find devicepolicy_lower_fp_quality, use default value instead
,W/SystemReader( 4083): Cannot find support_harman, use default value instead
,W/SystemReader( 4083): Cannot find effect_manager_id, use default value instead
,E/Settings:HtcWrapHeaderInfo( 4083): no such activity!
I/ActivityManager(  904): Delay finish: com.htc.launcher/.receiver.NotificationReceiver
D/PMS     (  904): releaseWL(42f1edd0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  904): releaseWL(42ff5408): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,I/ActivityManager(  904): Resuming delayed broadcast
W/NotifyReceiver( 3820): stopSelfResult true
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4083): The wrap header doesn't exist in header list.
I/WSP     ( 1411): [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
D/WeatherUtility( 1411): Weather sync is On
I/WSP     ( 1411): [Receiver] next auto-sync alarm event is 60 mins later, at time: Tue Dec 15 16:21:53 CET 2015
,E/Settings:HtcWrapHeaderInfo( 4083): updateDevelopment, bPrefShow = true
,W/WSP     ( 1411): [Receiver] can't get active network info
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.sense.hsp (1411/10053)
I/ActivityManager(  904): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,E/Settings:HtcUmcWidgetEnabler( 4083): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4083): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4083): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4083): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4083): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4083): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4083): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4083): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4083): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4083): [supportHomeButton]support         :false
,V/WSP     ( 1411): [SyncService] no data connection, stop sync service
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.sense.hsp (1411/10053)
,W/FingerprintManager( 4083): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
,E/Settings:HtcVoWifiWidgetEnabler( 4083): isSupportVoWifi: null
I/ActivityManager(  904): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 4083): Failed to find provider info for com.htc.vowifi
,W/MediaManager( 3657): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  904): Resuming delayed broadcast
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4083): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 4083): updateDevelopment, bPrefShow = true
,D/VoicemailCleanupService( 1258): Cleaning up data for package: com.example.hello
,E/Settings:HtcUmcWidgetEnabler( 4083): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4083): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4083): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4083): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4083): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4083): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4083): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4083): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4083): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4083): [supportHomeButton]support         :false
,D/PackageBroadcastService( 1195): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
I/ActivityManager(  904): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,W/FingerprintManager( 4083): hasFingerprint() - sSensorCode = 0
,E/Settings:HtcVoWifiWidgetEnabler( 4083): isSupportVoWifi: null
I/ActivityManager(  904): Cannot resolve ContentProvider=com.htc.vowifi
,E/ActivityThread( 4083): Failed to find provider info for com.htc.vowifi
,I/ActivityManager(  904): Delaying start of: ServiceRecord{42e90498 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/PeopleContactsSync( 1195): CP2 sync disabled
,I/Icing   ( 1195): doRemovePackageData com.example.hello
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1195, uid=10028, userID:0
D/PMS     (  904): acquireWL(42fc45c8): PARTIAL_WAKE_LOCK  Icing 0x1 1195 10028 null
D/PMS     (  904): releaseWL(42fc45c8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ActivityManager(  904): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4114 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/MultiDex( 4114): install
,I/MultiDex( 4114): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4114): loading existing secondary dex files
,I/MultiDex( 4114): load found 1 secondary dex files
,I/MultiDex( 4114): install done
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.talk (3956/10111)
,I/ProviderInstaller( 4114): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,I/ActivityManager(  904): Resuming delayed broadcast
,D/Process (  904): killProcessQuiet, pid=3339
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4129 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/ActivityManager(  904): Killing 3339:com.htc.sense.news/u0a75 (adj 15): empty #17
,V/AlarmManager(  904): sending alarm PendingIntent{42e1e020: PendingIntentRecord{42aa2118 com.android.vending startService}}, i=null, t=0, cnt=1, w=1450189314105, Int=0
,I/MultiDex( 4129): install
,I/MultiDex( 4129): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4129): loading existing secondary dex files
,I/MultiDex( 4129): load found 1 secondary dex files
,I/MultiDex( 4129): install done
,I/ProviderInstaller( 4129): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,W/GLSUser ( 1346): GoogleAccountDataService.getToken()
I/ActivityManager(  904): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
,W/GLSActivity( 1346): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1346): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1346): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Recipient 3339
,W/GLSUser ( 1346): GoogleAccountDataService.getToken()
,W/GLSActivity( 1346): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1346): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1346): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4026): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4026): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,I/ActivityManager(  904): Resuming delayed broadcast
,I/[PluginManager]RegisterService( 1411): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.example.hello
I/ActivityManager(  904): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,I/[PluginManager]RegisterService( 1411): handle notify Blinkfeed plugin client changed
I/ActivityManager(  904): Resuming delayed broadcast
,D/Prism.PackageStateRece_( 1245): action: android.intent.action.PACKAGE_REMOVED
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4129): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.gms/files
,I/IcingCorporaProvider( 2750): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
I/ActivityManager(  904): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (4129/10028)
,E/SQLiteDBG( 2750): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x6475fe60
,W/dalvikvm( 2750): threadid=26: thread exiting with uncaught exception (group=0x41ed3e30)
,E/ActivityManager(  904): App crashed! Process: com.google.android.googlequicksearchbox:search
E/AndroidRuntime( 2750): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2750): Process: com.google.android.googlequicksearchbox:search, PID: 2750
E/AndroidRuntime( 2750): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/AndroidRuntime( 2750): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2750): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2750): 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
E/AndroidRuntime( 2750): 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
E/AndroidRuntime( 2750): 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:562)
E/AndroidRuntime( 2750): 	at cid.d(PG:192)
E/AndroidRuntime( 2750): 	at clo.g(PG:594)
E/AndroidRuntime( 2750): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2750): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2750): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2750): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2750): 	at clr.tL(PG:827)
E/AndroidRuntime( 2750): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2750): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2750): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2750): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2750): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2750): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/DropBoxManagerService(  904): Can't write: system_app_crash
E/DropBoxManagerService(  904): java.io.FileNotFoundException: /data/system/dropbox/drop121.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  904): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  904): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  904): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  904): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  904): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  904): 	... 5 more
,W/GLSUser ( 1346): GoogleAccountDataService.getToken()
,W/GLSActivity( 1346): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1346): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1346): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4026): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4026): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4026): [1] DailyHygiene.reschedule: Scheduling new run in 284 minutes (failures=4)
,E/SharedPreferencesImpl( 4026): Couldn't rename file /data/data/com.android.vending/shared_prefs/finsky.xml to backup file /data/data/com.android.vending/shared_prefs/finsky.xml.bak
,I/GAV2    ( 3914): Thread[GAThread,5,main]: No campaign data found.

```
