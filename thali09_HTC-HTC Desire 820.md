#### Test 50388019385b4d9_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
E/ExternalAccountType( 3111): Unsupported attribute readOnly
D/CalendarApplication( 3156): onCreate
D/ProviderChangeReceiver( 3156): ---------------------------------------------------
D/ProviderChangeReceiver( 3156): ProviderChangeReceiver onReceive, start to update notification!
D/AlertService( 3156): start to updateAlertNotification!
--------- beginning of /dev/log/system
W/ContextImpl( 2873): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
D/AlertService( 3156): No fired or scheduled alerts
D/HtcAlertUtils( 3156): -- cancelReminderNotification --
D/HtcAlertUtils( 3156): broadcastExistReminder!
D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/ActivityManager(  904): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
I/ActivityManager(  904): Resuming delayed broadcast
D/Process (  904): killProcessQuiet, pid=2832
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.WeatherClock4x1: pid=3173 uid=10045 gids={50045, 3002, 3001, 3003, 5012}
I/ActivityManager(  904): Killing 2832:com.htc.htccupd/u0a17 (adj 15): empty #17
,I/ActivityManager(  904): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
W/WeatherUtility( 3173): can't get weather sync account
W/WeatherRequest( 3173): request cur loc, but there is no sys cur
W/Settings( 3173): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  904): Recipient 2832
D/AppWidgetHostView( 1251): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
I/RemoteViews( 1251): com.htc.widget.weatherclock (true,33751552)
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/RemoteViews.Performance( 1251): com.htc.widget.weatherclock 2 15 17
E/cutils-trace( 3190): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 3190): ====startRecUseTime====
D/htc.customization.log.level( 3190):  is 
W/CustomizationLogLevel( 3190): Level value is invalid, use default level 2
D/CustomizationManager( 3190):  Read ACC file spent 0.064 (s)
D/CIDMapFileReader( 3190): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3190): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3190): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3190): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3190): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3190): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3190): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3190): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3190): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3190): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3190): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3190): Parsing tag category name = system
I/CustomizationCIDLoader( 3190): Parsing tag category name = application
I/CustomizationCIDLoader( 3190): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3190): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3190): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3190): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3190): Parsing tag category name = Settings
D/CustomizationManager( 3190):  Read CID file spent 0.107 (s)
D/CustomizationManager( 3190):  All configurations done spent 0.107 (s)
W/HtcNativeFlag( 3190): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3190): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3190): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3190): Fail to get flag for type 'language', use default value: -1
I/HtcModeClient( 1465): handler message = 4011
E/HtcModeClient( 1465): Check connection and retry 4 times.
W/CpuWake (  904): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  904): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  904): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  904): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  904): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  904): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  904): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3190
D/PMS     (  904): acquireHCC(42650e88): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 904 1000 null
D/PMS     (  904): acquireHCC(4263d9b8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 904 1000 null
W/asset   (  904): Copying FileAsset 0x6be66908 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/Intent  (  904): @test_code: getHtcIntentFlag: 0 obj: 1112840712
I/FeedHostManager( 1251): [onPause]
I/FeedProviderManager( 1251): onPause
I/FeedHostManager( 1251): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c32610
I/SocialFeedProvider( 1251): +onPause
I/SocialFeedProvider( 1251): -onPause
D/PMS     (  904): acquireWL(42587e90): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 904 1000 null
I/ActivityManager(  904): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3201 uid=10397 gids={50397, 3003, 5012, 3001, 3002}
I/TrimMemoryManager( 1251): [trimMemory] 20
W/asset   ( 3201): Copying FileAsset 0x5c836428 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
V/WebViewChromiumFactoryProvider( 3201): Binding Chromium to main looper Looper (main, tid 1) {41af5fc0}
I/LibraryLoader( 3201): Expected native library version number "",actual native library version number ""
I/chromium( 3201): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3201): Initializing chromium process, renderers=0
W/System.err(  904): java.lang.Throwable: stack dump
D/BluetoothManagerService(  904): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  904): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4246e998:true
W/System.err(  904): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  904): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  904): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  904): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  904): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 3201): 1102100904: getState() :  mService = null. Returning STATE_OFF
D/PMS     (  904): acquireWL(425f2f78): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  904): releaseWL(425f2f78): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/PMS     (  904): acquireWL(426b5cd0): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
I/Adreno-EGL( 3201): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3201): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3201): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3201): Local Branch: 
I/Adreno-EGL( 3201): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3201): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3201):                  aa63bbd948f41d15fc72f585e
W/chromium( 3201): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 3201): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3201): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3201): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3201): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3201): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3201): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3201): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3201): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3201): CordovaWebView is running on device made by: HTC
,W/AwContents( 3201): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  904): Disable input method client, pid=1251
W/ResourceType( 3201): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 3201): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b3ccf0, mServedView=org.apache.cordova.engine.SystemWebView{41b02cc8 VFEDH.C. .F....I. 0,0-720,1134 #64}
I/InputMethodManagerService(  904): Enable input method client, pid=3201
W/XT9_C   ( 1185): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1185): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1185): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1185): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/AwContents( 3201): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  904): Displayed com.example.hello/.MainActivity: +255ms
D/PMS     (  904): releaseWL(42587e90): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
E/AndroidProtocolHandler( 3201): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/chromium( 3201): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
I/ActivityManager(  904): Resuming delayed broadcast
D/Process (  904): killProcessQuiet, pid=2846
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 2846:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Recipient 2846
D/JsMessageQueue( 3201): Set native->JS mode to OnlineEventsBridgeMode
I/ActivityManager(  904): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver: pid=3244 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
I/DemoRecovery.RestoreReceiver( 3244): onReceive: com.htc.launcher.intent.LOADING_COMPLETE
W/ContextImpl( 3244): Implicit intents with startService are not safe: Intent { act=com.htc.demorecovery.LOADING_COMPLETE } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.demoflopackageinstaller.demorecovery.RestoreReceiver.onReceive:26 
I/RestoreService( 3244): onHandleIntent: com.htc.demorecovery.LOADING_COMPLETE
I/ActivityManager(  904): Delay finish: com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver
I/ActivityManager(  904): Resuming delayed broadcast
I/ActivityManager(  904): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3258 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
D/Process (  904): killProcessQuiet, pid=2859
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  904): Killing 2859:com.zoodles.kidmode/u0a149 (adj 15): empty #17
I/ActivityManager(  904): Recipient 2859
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/jxcore_app_log( 3201): JniHelper::setJavaVM(0x415cb048), pthread_self() = 1658502400
D/JX-Cordova( 3201): jxcore cordova android initializing
D/PMS     (  904): acquireWL(4265abe0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3258 10071 null
D/PMS     (  904): acquireWL(4260e370): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3258 10071 null
I/ActivityManager(  904): Delay finish: com.htc.task/.TodoReceiver
D/PMS     (  904): releaseWL(4265abe0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/TodoTaskshortcut( 3258): update TASK shortcut>
I/TodoTaskNotifyService( 3258): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
W/NotifyReceiver( 3258): stopSelfResult true
W/jxcore-log( 3201): Initializing JXcore engine
W/jxcore-log( 3201): JXcore engine is ready
D/PMS     (  904): releaseWL(4260e370): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  904): Resuming delayed broadcast
W/jxcore-log( 3201): Starting JXcore engine
D/Process (  904): killProcessQuiet, pid=2499
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Start proc com.htc.stock for broadcast com.htc.stock/.receiver.StockReceiver: pid=3273 uid=10082 gids={50082, 3003, 5012}
I/ActivityManager(  904): Killing 2499:com.android.defcontainer/u0a19 (adj 15): empty #17
I/ActivityManager(  904): Recipient 2499
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Start proc com.htc.stock:remote for content provider com.htc.stock/.provider.StockProvider: pid=3285 uid=10082 gids={50082, 3003, 5012}
W/jxcore-log( 3201): Platform android
W/jxcore-log( 3201): 
W/jxcore-log( 3201): Process ARCH arm
W/jxcore-log( 3201): 
D/Process (  904): killProcessQuiet, pid=2901
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  904): Killing 2901:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
I/ActivityManager(  904): Recipient 2901
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=3297 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
I/ActivityManager(  904): Killing 2915:com.android.smith/u0a163 (adj 15): empty #17
D/Process (  904): killProcessQuiet, pid=2915
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  904): Recipient 2915
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/jxcore-log( 3201): JXcore Cordova bridge is ready!
I/jxcore-log( 3201): 
W/jxcore-log( 3201): JXcore engine is started
I/ImageRamCache( 3297): create image Cache, size: 31457280.
I/ImageRamCache( 3297): [resize] ImageRamCache resized to: 12Mb.
I/ImageRamCache( 3297): create image Cache, size: 12582912.
I/FeedSettings( 3297): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
I/FeedSettings( 3297): GroupBudget 0.500000 0.380000
I/FeedSettings( 3297): GroupBudget 60 45 15
E/jxcore-log( 3201): >> HTC-HTC Desire 820
E/jxcore-log( 3201): 
I/Prism.ExternalStringMa_( 3297): changeLocale(): en_GB
I/jxcore-log( 3201): Total memory 1964650496
I/jxcore-log( 3201): 
I/jxcore-log( 3201): Free memory 693694464
I/jxcore-log( 3201): 
I/jxcore-log( 3201): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3201): 
I/jxcore-log( 3201): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3201): 
I/Prism.AllAppsOptionsMa_( 3297): loadSortType() with Custom
I/Prism.AllAppsOptionsMa_( 3297): loadGridSize() with Alternative
I/jxcore-log( 3201): userPath [ 'www' ]
I/jxcore-log( 3201): 
I/jxcore-log( 3201): Size 720 1184
I/jxcore-log( 3201): 
I/jxcore-log( 3201): Screen Brightness 142
I/jxcore-log( 3201): 
E/jxcore-log( 3201): Dummy Error Log.
E/jxcore-log( 3201): 
D/CustomHighlightReceiver( 3297): [custom highlight] onReceive
D/CustomHighlightService( 3297): [custom highlight] onHandleIntent
I/ActivityManager(  904): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
D/NewsDB  ( 3297): set custom highlight []
D/CustomHighlightService( 3297): [custom highlight] set tags 
D/SMSBackup( 3144): Got a database change event
I/ActivityManager(  904): Resuming delayed broadcast
D/MessagingShortcutReceiver( 2451): keep hiding shortcut bubble
D/MessagingShortcut( 2451): updateMsgShortcut, msg count> -1
D/MessagingShortcut( 2451): After query: 0
D/MessagingShortcut( 2451): mPresentUnreadCount: -1
D/MessagingShortcut( 2451): setMsgShortcutDrawable> 0
D/MessagingShortcut( 2451): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1529): [EventService] reorderNotification, total:0
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/TodoTaskshortcut( 3258): update TASK shortcut>
I/ActivityManager(  904): Delay finish: com.htc.task/.TodoReceiver
D/HtcBroadcastReceiver( 1216): onReceive: com.htc.launcher.action.ACTION_ITEM_ADDED
D/Process (  904): killProcessQuiet, pid=2927
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Resuming delayed broadcast
I/ActivityManager(  904): Killing 2927:com.google.android.youtube/u0a168 (adj 15): empty #17
I/ActivityManager(  904): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3313 uid=10091 gids={50091, 3003, 5012}
D/MessagingNotification( 2451): New incoming message, can't cancel notification now
D/MessagingNotification( 2451): newMsgCnt: 0, false
I/ActivityManager(  904): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024586
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024899
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024997
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024999
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025005
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025010
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026314
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026325
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029257
V/AlarmManager(  904): sending alarm PendingIntent{4205f158: PendingIntentRecord{425b3188 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=21979, Int=1800000
V/AlarmManager(  904): sending alarm PendingIntent{424e6e18: PendingIntentRecord{425587f0 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.RENEW_ACCOUNT_REGISTRATION, t=2, cnt=1, w=44897, Int=259200000
I/ActivityManager(  904): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3327 uid=10091 gids={50091, 3003, 5012}
V/AlarmManager(  904): sending alarm PendingIntent{41d9aec8: PendingIntentRecord{42482780 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=51047, Int=0
V/AlarmManager(  904): sending alarm PendingIntent{424a01f8: PendingIntentRecord{42539b50 com.htc.launcher broadcastIntent}}, i=com.htc.launcher.action.BI_LOG_ALARM, t=1, cnt=1, w=1450177200000, Int=86400000
D/MdScBoot( 3313): [930.1.] 30@-152105 -> 40@-152132
D/Process (  904): killProcessQuiet, pid=2975
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  904): Resuming delayed broadcast
I/ActivityManager(  904): Killing 2975:com.android.vending/u0a74 (adj 15): empty #17
D/Process (  904): killProcessQuiet, pid=2886
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 2886:com.android.settings/1000 (adj 15): empty #17
I/ActivityManager(  904): Recipient 2927
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  904): Client com.google.android.youtube (pid 2927): Died!
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WearableService( 1200): callingUid 10029, callindPid: 1200
D/LocationInitializer( 1960): Restart initialization of location
I/ActivityManager(  904): Recipient 2886
I/ActivityManager(  904): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  904): Resuming delayed broadcast
E/MDM     ( 1200): [88] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1339): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/AuthorizationBluetoothService( 1339): Proximity feature is not enabled.
V/GLSActivity( 1339): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GCoreFlp( 1200): No location to return for getLastLocation()
W/FusedLocationProvider( 1200): location=null
D/PMS     (  904): acquireWL(423a8880): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  904): releaseWL(423a8880): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024586
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024899
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024997
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024999
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025005
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025010
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026314
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026325
E/MDM     ( 1200): [90] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029257
D/LocationInitializer( 1960): Restart initialization of location
D/AuthorizationBluetoothService( 1339): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/AuthorizationBluetoothService( 1339): Proximity feature is not enabled.
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
V/GLSActivity( 1339): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  904): Recipient 2975
D/MtpReceiver( 2164): [MTP][MtpReceiver][onReceive]+
D/MtpReceiver( 2164): [MTP][MtpReceiver][onReceive]1-
D/MtpReceiver( 2164): [MTP][handleMessage][startService]
D/MtpReceiver( 2164): [MTP][handleMessage][UsbManager.USB_CONNECTED][insert]+
D/MtpReceiver( 2164): [MTP][handleMessage]-
W/GCoreFlp( 1200): No location to return for getLastLocation()
W/FusedLocationProvider( 1200): location=null
D/PMS     (  904): acquireWL(41c11340): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  904): releaseWL(41c11340): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/MtpService( 2164): [MTP] startForeground
D/DotMatrix( 1529): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
I/RemoteViews( 1108): com.android.providers.media (false,0)
I/RemoteViews.Performance( 1108): com.android.providers.media 2 1 10
I/ActivityManager(  904): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3350 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
I/RemoteViews( 1108): com.android.providers.media (false,0)
D/MtpService( 2164): updating state; isCurrentUser=true, mMtpLocked=false
D/MtpDatabase( 2164): TotalSize=1918604,MediaCacheLimit=6000
I/RemoteViews.Performance( 1108): com.android.providers.media 2 2 15
D/MtpService( 2164): [isMtpConnected] connected: true
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024586
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024899
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024997
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024999
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025005
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025010
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026314
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026325
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029257
D/PMS     (  904): acquireWL(424530a0): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 1960 10029 null
D/SyncApplication( 3350): Loading default preferences
I/iu.UploadsManager( 1960): End new media; added: 0, uploading: 0, time: 39 ms
W/Resources( 3350): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
D/PMS     (  904): releaseWL(424530a0): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 null
D/WifiService(  904): New client listening to asynchronous messages
D/SyncApplication( 3350): Overriding preferences with custom values
D/SyncApplication( 3350): Updating preferences succeeded
E/SyncApplication( 3350): Application created.
D/VolumeInfo( 3350): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
D/VolumeInfo( 3350): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 3350): Found 0 mount point(s)
V/VolumeInfo( 3350): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
D/VolumeInfo( 3350): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
D/VolumeInfo( 3350): Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
W/VolumeInfo( 3350): Can not create volume ID for unmounted volume null
I/CalendarDefines( 3350): getNewCalendarAuthority()...
D/SyncApplication( 3350): enableAppOperation()+
D/SyncApplication( 3350): enableAppOperation()-
D/HTCUtilities( 3350): isNeorSinged() + 
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3350, uid=10008, userID:0
W/PackageManager(  904): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3350, uid=10008, userID:0
W/PackageManager(  904): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
D/HTCUtilities( 3350): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
D/HTCUtilities( 3350): isNeorSinged() return false
D/CDMountReceiver( 3350): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
D/CDMountReceiver( 3350): USB connected to PC
D/FOTAReceiver( 3350): onReceive() enter 
D/FOTAReceiver( 3350): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
I/ActivityManager(  904): Start proc com.android.settings for broadcast com.android.settings/.MLReceiver: pid=3370 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process (  904): killProcessQuiet, pid=3060
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  904): Killing 3060:com.htc.sense.browser/u0a12 (adj 15): empty #17
I/ActivityManager(  904): Recipient 3060
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/HtcFingerPrintQuickLaunchProvider( 3370): -onCreate()
V/Settings:HtcSettingsApplication( 3370): [3370/3370] onCreate()
I/jxcore-log( 3201): getBuffer is called!!!!
I/jxcore-log( 3201): 
D/TetherSettings( 3370): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3370): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3370): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3370): Cust_ConnectToPC   : spcsc>false
D/        ( 3370): Cust_ConnectToPC   : IPT>true
D/        ( 3370): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3370): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/TetherSettings( 3370): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3370): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3370): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3370): Cust_ConnectToPC   : spcsc>false
D/        ( 3370): Cust_ConnectToPC   : IPT>true
D/        ( 3370): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3370): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3370): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3370): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3370): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
D/SmartNS_Utility( 3370): usb_cable_connect = 1
D/SmartNS_Utility( 3370): usb_denied = 0
I/SmartNS_NSReceiver( 3370): locked:falsesecurity:falseisLocked:false
D/SmartNS_NSReceiver( 3370): USB = true hasTethered = false isNSOpening: false
I/PSReceiver( 3370): onReceive:com.htc.intent.action.USB_CONNECT2PC
I/SmartNS_PSService( 3370): onReceive:com.htc.intent.action.USB_CONNECT2PC
W/Settings( 3370): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3370):  defaultType:0
I/SmartNS_PSService( 3370): fail notificaiton:false
D/SmartNS_Utility( 3370): usb_cable_connect = 1
D/SmartNS_Utility( 3370): usb_denied = 0
I/SmartNS_PSService( 3370): usb notificaiton:true
V/Tethering(  904): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Tethering(  904): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  904): bSetPropertyMultiRAB:false
W/ContextImpl( 3370): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  904): Delay finish: com.android.settings/.PSReceiver
D/ConnectivityService(  904): getActiveNetworkInfo called by com.android.settings (3370/1000)
D/SmartNS_Utility( 3370): usb_cable_connect = 1
D/SmartNS_Utility( 3370): usb_denied = 0
I/SmartNS_PSService( 3370): usb notificaiton:true
V/Tethering(  904): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Tethering(  904): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  904): bSetPropertyMultiRAB:false
I/RemoteViews( 1108): com.android.settings (true,33751552)
I/RemoteViews.Performance( 1108): com.android.settings 1 1 10
D/DotMatrix( 1529): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
D/SmartNS_Utility( 3370): usb_cable_connect = 1
D/SmartNS_Utility( 3370): usb_denied = 0
D/ConnectivityService(  904): getActiveNetworkInfo called by com.android.settings (3370/1000)
D/DotMatrix( 1529): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
I/SmartNS_PSService( 3370): KeyGuard locked:falseKeyGuard is secured:false
D/SmartNS_PSService( 3370): USB Plugged, Set USBPlugged=  truePSenabled:false
I/ActivityManager(  904): Resuming delayed broadcast
I/ActivityManager(  904): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
I/RemoteViews( 1108): com.android.settings (true,33751552)
I/RemoteViews.Performance( 1108): com.android.settings 0 1 10
W/WeatherUtility( 3173): can't get weather sync account
I/ActivityManager(  904): Resuming delayed broadcast
I/ActivityManager(  904): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
W/WeatherRequest( 3173): request cur loc, but there is no sys cur
W/Settings( 3173): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/AppWidgetHostView( 1251): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
I/RemoteViews( 1251): com.htc.widget.weatherclock (true,33751552)
I/RemoteViews.Performance( 1251): com.htc.widget.weatherclock 1 6 17
,I/ActivityManager(  904): Waited long enough for: ServiceRecord{42577a88 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,I/ActivityManager(  904): Resuming delayed broadcast
,D/AppWidgetHostView( 1251): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider})
,I/RemoteViews( 1251): com.google.android.googlequicksearchbox (false,0)
,I/RemoteViews.Performance( 1251): com.google.android.googlequicksearchbox 0 0 5
,I/ActivityManager(  904): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=3387 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,W/CpuWake (  904): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  904): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  904): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  904): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  904): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  904): <<release mCpuPerf_Freq wakelock
D/PMS     (  904): releaseHCC(42650e88): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  904): releaseHCC(4263d9b8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/ContextImpl( 3387): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  904): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
D/PowerUsageService( 3387): call getInstance()
,D/PowerUsageList:PowerUsageHelper( 3387): MY_DEBUG = false
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,I/ActivityManager(  904): Resuming delayed broadcast
,D/Process (  904): killProcessQuiet, pid=3099
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  904): Killing 3099:com.google.android.partnersetup/u0a32 (adj 15): empty #17
D/PMS     (  904): acquireWL(42763ef0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3387 1000 null
,D/Process (  904): killProcessQuiet, pid=3111
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3111:com.htc.contacts/u0a44 (adj 15): empty #17
,W/WeatherUtility( 1108): can't get weather sync account
I/ActivityManager(  904): Recipient 3099
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WeatherUtility( 1295): Weather sync is On
,D/WSP     ( 1295): [Receiver] auto sync agent, auto sync is enabled, reset schedule
,W/WeatherUtility( 3173): can't get weather sync account
,I/ActivityManager(  904): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=3406 uid=10034 gids={50034, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
,I/ActivityManager(  904): Recipient 3111
W/WeatherRequest( 3173): request cur loc, but there is no sys cur
W/Settings( 3173): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AppWidgetHostView( 1251): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1251): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1251): com.htc.widget.weatherclock 1 8 17
,I/ActivityManager(  904): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,D/PMS     (  904): releaseWL(426b5cd0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/ContactMessageStore( 1216): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1216): MSG_NOTIFY_CS_TO_SYNC <<
,I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=3423 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,I/MusicStore( 3423): Database version: 95
,W/ContextImpl( 3423): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 3423): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,V/AlarmManager(  904): sending alarm PendingIntent{423f05f8: PendingIntentRecord{4266e6c8 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1450189294942, Int=0
,E/cutils  (  349): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3423): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  349): Returning OperationFailed - no handler for errno 30
,E/cutils  (  349): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3423): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  349): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3423): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  349): Returning OperationFailed - no handler for errno 30
W/Vold    (  349): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=3423, uid=10154, userID:0
,D/WifiDisplayAdapter(  904): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  904):     Client/Owner: Client
D/WifiDisplayAdapter(  904):     GroupId: 
D/WifiDisplayAdapter(  904):     Passphrase: 
D/WifiDisplayAdapter(  904):     SessionId: 0
D/WifiDisplayAdapter(  904):     IP Address: }
,D/MediaRouterService(  904): Client com.google.android.music (pid 3423): Registered
,D/WifiDisplayAdapter(  904): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  904):     Client/Owner: Client
D/WifiDisplayAdapter(  904):     GroupId: 
D/WifiDisplayAdapter(  904):     Passphrase: 
D/WifiDisplayAdapter(  904):     SessionId: 0
D/WifiDisplayAdapter(  904):     IP Address: }
,I/MediaRouter( 3423): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/ActivityManager(  904): Killing 3156:com.htc.calendar/u0a13 (adj 15): empty #17
D/Process (  904): killProcessQuiet, pid=3156
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  904): Recipient 3156
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/TelephonyReceiver( 1216): bind: true
,D/DFPI.PIReciver( 3244): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,D/GenericMessagesProvider( 2451): query uri: content://htc-messages/wappush/count
E/SQLiteLog( 2451): (14) cannot open file at line 30190 of [00bb9c9ce4]
,E/SQLiteLog( 2451): (14) os_unix.c:30190: (2) open(/data/data/com.htc.sense.mms/databases/wappush.db) - 
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.music (3423/10154)
,I/ActivityManager(  904): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
E/SQLiteConnection( 2451): DB info: sqlite3_open_v2, path: /data/data/com.htc.sense.mms/databases/wappush.db, flag: 1, ret: 14
E/SQLiteConnection( 2451): DB info: errno = 2, errno message = No such file or directory
I/DFPI.ApkInstallService( 3244): onHandleIntent
I/DFPI.ApkInstallService( 3244): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3244): check CID = HTC__032
,I/DFPI.ApkInstallService( 3244): There is no Demo.apk in sd card or phone storage
E/SQLiteDatabase( 2451): Failed to open database '/data/data/com.htc.sense.mms/databases/wappush.db'.
E/SQLiteDatabase( 2451): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 2451): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2451): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2451): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2451): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2451): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2451): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2451): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2451): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2451): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2451): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
E/SQLiteDatabase( 2451): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
E/SQLiteDatabase( 2451): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 2451): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 2451): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
E/SQLiteDatabase( 2451): 	at android.os.Binder.execTransact(Binder.java:412)
E/SQLiteDatabase( 2451): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 2451): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
W/System.err( 2451): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 2451): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
,W/System.err( 2451): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/System.err( 2451): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/System.err( 2451): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/System.err( 2451): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/System.err( 2451): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/System.err( 2451): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/System.err( 2451): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/System.err( 2451): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
W/System.err( 2451): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
W/System.err( 2451): 	at android.content.ContentProvider.query(ContentProvider.java:869)
W/System.err( 2451): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
W/System.err( 2451): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
W/System.err( 2451): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err( 2451): 	at dalvik.system.NativeStart.run(Native Method)
I/ActivityManager(  904): Resuming delayed broadcast
,D/TelephonyReceiver( 1216): switchBindHtcMsgCursor: null
,D/MediaRouter( 3423): getSelectedRoute
I/ActivityManager(  904): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=3423, uid=10154, userID:0
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/PMS     (  904): acquireWL(427e39d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
I/ActivityManager(  904): Resuming delayed broadcast
D/PMS     (  904): releaseWL(427e39d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/ActivityManager(  904): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=3446 uid=10053 gids={50053, 1028, 1015, 3003, 5012}
,I/ActivityManager(  904): Delay finish: com.htc.musicenhancer/.provider.MScannerReceiver
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.musicenhancer (3446/10053)
,E/cutils  (  349): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3446): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
W/Vold    (  349): Returning OperationFailed - no handler for errno 30
,D/PMS     (  904): releaseWL(42763ef0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=3465 uid=10081 gids={50081, 5001, 1028, 1015}
,D/Process (  904): killProcessQuiet, pid=2873
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 2873:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 2873
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/SoundPicker( 3465): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3465): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3465): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3465): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3465): TurnFileToMediaUriService fromMediaScanned = true
,I/SoundPicker( 3465): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
,I/ActivityManager(  904): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
D/RingtoneManager( 3465): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3465): MODE_GSM access default DB
I/SoundPicker( 3465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3465): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3465): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3465): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3465): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3465): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3465): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3465): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3465): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3465): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3465): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3465): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3465): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3465): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3465): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3465): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3465): MODE_GSM access default DB
I/SoundPicker( 3465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3465): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
,I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3465): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
,I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/HtcModeClient( 1465): handler message = 4011
,E/HtcModeClient( 1465): Check connection and retry 5 times.
,I/SoundPicker( 3465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3465): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
,I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3465): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
,I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
I/SoundPicker( 3465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
I/SoundPicker( 3465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
I/SoundPicker( 3465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
I/SoundPicker( 3465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/SensorManager(  904): mEventCount = 450
,I/ActivityManager(  904): Resuming delayed broadcast
,D/DFPI.PIReciver( 3244): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/ActivityManager(  904): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/DFPI.ApkInstallService( 3244): onHandleIntent
I/DFPI.ApkInstallService( 3244): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3244): check CID = HTC__032
,I/DFPI.ApkInstallService( 3244): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  904): disable(): mBluetooth = null mBinding = false
,W/HtcDLNAServiceManager(  904): Settings:AgentMONITOR_LOG
,W/HtcDLNAServiceManager(  904): Settings:Agentname: bluetooth_on
,W/HtcDLNAServiceManager(  904): Settings:Agentvalue: 0
,W/Settings:Agent(  904): >> traceCallingStack()
,W/Settings:Agent(  904): Process.myPid(): 904
,W/Settings:Agent(  904): Process.myTid(): 1337
,W/Settings:Agent(  904): Process.myUid(): 1000
,W/Settings:Agent(  904): 
,W/Settings:Agent(  904): 
,W/System.err(  904): java.lang.Throwable: stack dump
,W/System.err(  904): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  904): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
,W/System.err(  904): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
,W/System.err(  904): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
,W/System.err(  904): 	at android.provider.Settings$Global.putString(Settings.java:6170)
,W/System.err(  904): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
,W/System.err(  904): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
W/System.err(  904): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:583)
,W/System.err(  904): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
,W/System.err(  904): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  904): 	at dalvik.system.NativeStart.run(Native Method)
,W/Settings:Agent(  904): 
,W/Settings:Agent(  904): << traceCallingStack(): 18(ms)
,D/BluetoothManagerService(  904): Message: MESSAGE_DISABLE
,D/WifiManager( 3201): setWifiEnabled: Base Package Name=com.example.hello, uid=10397
,W/HtcDLNAServiceManager(  904): Settings:AgentMONITOR_LOG
,W/HtcDLNAServiceManager(  904): Settings:Agentname: wifi_on
D/WifiService(  904): New client listening to asynchronous messages
D/WifiService(  904): setWifiEnabled: false pid=3201, uid=10397
E/WifiService(  904): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  904): isSprintWifiRestricted(): false
I/WifiService(  904): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  904): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/HtcDLNAServiceManager(  904): Settings:Agentvalue: 0
W/Settings:Agent(  904): >> traceCallingStack()
W/Settings:Agent(  904): Process.myPid(): 904
W/Settings:Agent(  904): Process.myTid(): 1247
W/Settings:Agent(  904): Process.myUid(): 1000
W/Settings:Agent(  904): 
W/Settings:Agent(  904): 
W/System.err(  904): java.lang.Throwable: stack dump
W/System.err(  904): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  904): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  904): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  904): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  904): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  904): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  904): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  904): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:114)
W/System.err(  904): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  904): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  904): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  904): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  904): 
W/Settings:Agent(  904): << traceCallingStack(): 7(ms)
,I/jxcore-log( 3201): ****TEST TOOK:  5081  ms ****
I/jxcore-log( 3201): 
,I/jxcore-log( 3201): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3201): 
,E/cutils-trace( 3483): Error opening trace file: No such file or directory (2)
,D/CustomizationManager( 3483): ====startRecUseTime====
D/htc.customization.log.level( 3483):  is 
,W/CustomizationLogLevel( 3483): Level value is invalid, use default level 2
,D/CustomizationManager( 3483):  Read ACC file spent 0.054 (s)
,D/CIDMapFileReader( 3483): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3483): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3483): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3483): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3483): Parsing tag item name = HTC__032
,D/CIDMapFileReader( 3483): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3483): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3483): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3483): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 3483): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 3483): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 3483): Parsing tag category name = system
,I/CustomizationCIDLoader( 3483): Parsing tag category name = application
,I/CustomizationCIDLoader( 3483): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3483): Parsing tag category name = AutomotiveHome
,I/CustomizationCIDLoader( 3483): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3483): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 3483): Parsing tag category name = Settings
,D/CustomizationManager( 3483):  Read CID file spent 0.101 (s)
,D/CustomizationManager( 3483):  All configurations done spent 0.101 (s)
W/HtcNativeFlag( 3483): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3483): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3483): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 3483): Fail to get flag for type 'language', use default value: -1
,I/ActivityManager(  904): Resuming delayed broadcast
I/SoundPicker( 3465): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3465): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3465): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3465): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3465): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3465): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3465): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,D/RingtoneManager( 3465): MODE_GSM access default DB
I/SoundPicker( 3465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3465): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3465): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3465): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3465): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3465): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3465): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3465): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3465): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3465): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3465): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
,W/SoundPicker( 3465): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3465): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3465): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3465): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3465): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,D/RingtoneManager( 3465): MODE_GSM access default DB
D/PackageManager(  904): deletePackageAsUser: pkg=com.example.hello, pid=3483, uid=2000 user=0
,I/ActivityManager(  904): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3465): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
,I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,W/asset   (  904): Copying FileAsset 0x62cc37f8 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,D/Process (  904): killProcessQuiet, pid=3201
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  904): Force stopping com.example.hello appid=10397 user=-1: uninstall pkg
I/ActivityManager(  904): Killing 3201:com.example.hello/u0a397 (adj 0): stop com.example.hello
W/ActivityManager(  904): Force removing ActivityRecord{424be0b0 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/ActivityManager(  904): handleTopAppChanged(): The previous AP is died unexpectedly.
,W/PackageSettings(  904): Skipping PackageSetting{4223fbf8 com.test.thalitest/10389} due to missing metadata
,I/ActivityManager(  904): Force stopping com.example.hello appid=10397 user=0: pkg removed
,W/InputDispatcher(  904): channel '426bd7e0 com.example.hello.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  904): channel '426bd7e0 com.example.hello.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  904): Attempted to unregister already unregistered input channel '426bd7e0 com.example.hello.MainActivity (s)'
I/WindowManager(  904): WINDOW DIED Window{426bd7e0 u0 com.example.hello/com.example.hello.MainActivity}
D/DotMatrix( 1529): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1529): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1529): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
,I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver packageName:com.example.hello
,I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver replacing:false
D/WifiService(  904): Client connection lost with reason: 4
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/SoundPicker( 3465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3465): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
,I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,W/GeofencerStateMachine( 1200): Ignoring removeGeofence because network location is disabled.
,I/FeedHostManager( 1251): [onResume]
,I/FeedProviderManager( 1251): onResume
,I/SocialFeedProvider( 1251): +onResume
W/WindowManager(  904): Failed looking up window
W/WindowManager(  904): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@4264ff70 does not exist
W/WindowManager(  904): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8463)
W/WindowManager(  904): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8454)
W/WindowManager(  904): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1052)
W/WindowManager(  904): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
W/WindowManager(  904): 	at dalvik.system.NativeStart.run(Native Method)
I/WindowState(  904): WIN DEATH: null
D/PMS     (  904): acquireWL(427a1210): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
I/SocialFeedProvider( 1251): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1251): -onResume
,I/ConnectivityHelper( 1251): [getCurrentConnectionType] no network connection
,W/SystemReader( 1232): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/SoundPicker( 3465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/Prism.ItemManager( 3297): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Prism.ItemManager( 3297): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,D/AccTypeManager( 1317): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3465): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
,I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.launcher (1251/10076)
,D/PMS     (  904): releaseWL(427a1210): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/Prism.ItemManager( 1251): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1251): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/SoundPicker( 3465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3465): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
I/SoundPicker( 3465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
,I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
W/AccTypeManager( 1317): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1317): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "sms"
,I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
I/SoundPicker( 3465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
,I/SoundPicker( 3465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
,I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "smsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,I/SoundPicker( 3465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3465): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
,I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,E/ExternalAccountType( 1317): Unsupported attribute readOnly
,I/SoundPicker( 3465): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3465): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  904): Resuming delayed broadcast
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "mms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "mmsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,I/SocialFeedProvider( 1251): +disConnect socialManager
,I/SocialFeedProvider( 1251): disconnect socialManager
I/InputMethodManagerService(  904): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,I/ActivityManager(  904): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/SocialFeedProvider( 1251): -disConnect socialManager
,W/Binder  ( 1185): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1185): java.lang.NullPointerException
W/Binder  ( 1185): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1185): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1185): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1185): 	at dalvik.system.NativeStart.run(Native Method)
W/InputMethodManagerService(  904): Got RemoteException sending setActive(false) notification to pid 3201 uid 10397
I/InputMethodManagerService(  904): Enable input method client, pid=1251
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "sms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "smsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "mms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
V/AlarmManager(  904): sending alarm PendingIntent{41e476a0: PendingIntentRecord{41e47668 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1450189298406, Int=0
,I/SocialManager[SocialBiLogHelper]( 3297): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 3297): last commit ulog time 1450159070481
,I/SocialManager[SocialBiLogHelper]( 3297): skip commit this time
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "mmsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,D/PhoneApp( 1216): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,W/PackageManager(  904): Unable to load service info ResolveInfo{426ba440 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService, state=2, flag=1, pid=1960, uid=10029, userID:0
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateActivity, state=2, flag=1, pid=1960, uid=10029, userID:0
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$SecretCodeReceiver, state=2, flag=1, pid=1960, uid=10029, userID:0
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$Receiver, state=2, flag=1, pid=1960, uid=10029, userID:0
,I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1317): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "sms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,F/PackageManager(  904): Unable to backup user packages state file, current changes will be lost at reboot
D/ErrorReport(  904): HtcErrorReportManager Begin---add error logs to dropbox
E/ErrorReport(  904): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  904): java.io.FileNotFoundException: /data/misc/SYSTEM_WTF@1450189298849.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  904): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  904): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  904): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:540)
E/ErrorReport(  904): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:227)
E/ErrorReport(  904): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10800)
E/ErrorReport(  904): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10685)
E/ErrorReport(  904): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:379)
E/ErrorReport(  904): 	at android.util.Log$1.onTerribleFailure(Log.java:104)
E/ErrorReport(  904): 	at android.util.Log.wtf(Log.java:293)
E/ErrorReport(  904): 	at android.util.Log.wtf(Log.java:256)
E/ErrorReport(  904): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1134)
E/ErrorReport(  904): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:11872)
E/ErrorReport(  904): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:11928)
E/ErrorReport(  904): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1005)
E/ErrorReport(  904): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2171)
E/ErrorReport(  904): 	at android.os.Binder.execTransact(Binder.java:412)
E/ErrorReport(  904): 	at dalvik.system.NativeStart.run(Native Method)
E/ErrorReport(  904): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  904): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  904): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  904): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  904): 	... 18 more
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "smsto"
,F/PackageManager(  904): Unable to backup user packages state file, current changes will be lost at reboot
,W/SystemReader( 1232): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
,W/AccTypeManager( 1317): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1317): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
D/ErrorReport(  904): HtcErrorReportManager Begin---add error logs to dropbox
E/ErrorReport(  904): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  904): java.io.FileNotFoundException: /data/misc/SYSTEM_WTF@1450189298857.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  904): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  904): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  904): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:540)
E/ErrorReport(  904): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:227)
E/ErrorReport(  904): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10800)
E/ErrorReport(  904): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10685)
E/ErrorReport(  904): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:379)
E/ErrorReport(  904): 	at android.util.Log$1.onTerribleFailure(Log.java:104)
E/ErrorReport(  904): ,	at android.util.Log.wtf(Log.java:293)
E/ErrorReport(  904): 	at android.util.Log.wtf(Log.java:256)
E/ErrorReport(  904): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1134)
E/ErrorReport(  904): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:11872)
E/ErrorReport(  904): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:11928)
E/ErrorReport(  904): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1005)
E/ErrorReport(  904): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2171)
E/ErrorReport(  904): 	at android.os.Binder.execTransact(Binder.java:412)
E/ErrorReport(  904): 	at dalvik.system.NativeStart.run(Native Method)
E/ErrorReport(  904): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  904): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  904): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  904): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  904): 	... 18 more
,I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mms"
,F/PackageManager(  904): Unable to backup user packages state file, current changes will be lost at reboot
D/ErrorReport(  904): HtcErrorReportManager Begin---add error logs to dropbox
,E/ErrorReport(  904): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  904): java.io.FileNotFoundException: /data/misc/SYSTEM_WTF@1450189298872.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  904): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  904): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  904): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:540)
E/ErrorReport(  904): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:227)
E/ErrorReport(  904): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10800)
E/ErrorReport(  904): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10685)
E/ErrorReport(  904): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:379)
E/ErrorReport(  904): 	at android.util.Log$1.onTerribleFailure(Log.java:104)
E/ErrorReport(  904): 	at android.util.Log.wtf(Log.java:293)
E/ErrorReport(  904): 	at android.util.Log.wtf(Log.java:256)
E/ErrorReport(  904): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1134)
E/ErrorReport(  904): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:11872)
E/ErrorReport(  904): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:11928)
E/ErrorReport(  904): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1005)
E/ErrorReport(  904): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2171)
E/ErrorReport(  904): 	at android.os.Binder.execTransact(Binder.java:412)
E/ErrorReport(  904): 	at dalvik.system.NativeStart.run(Native Method)
E/ErrorReport(  904): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  904): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  904): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  904): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  904): 	... 18 more
,I/ActivityManager(  904): Resuming delayed broadcast
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "mmsto"
,F/PackageManager(  904): Unable to backup user packages state file, current changes will be lost at reboot
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
D/ErrorReport(  904): HtcErrorReportManager Begin---add error logs to dropbox
E/ErrorReport(  904): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  904): java.io.FileNotFoundException: /data/misc/SYSTEM_WTF@1450189298886.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  904): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  904): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  904): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:540)
E/ErrorReport(  904): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:227)
E/ErrorReport(  904): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10800)
E/ErrorReport(  904): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10685)
E/ErrorReport(  904): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:379)
E/ErrorReport(  904): 	at android.util.Log$1.onTerribleFailure(Log.java:104)
E/ErrorReport(  904): 	at android.util.Log.wtf(Log.java:293)
E/ErrorReport(  904): 	at android.util.Log.wtf(Log.java:256)
E/ErrorReport(  904): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1134)
E/ErrorReport(  904): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:11872)
E/ErrorReport(  904): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:11928)
E/ErrorReport(  904): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1005)
E/ErrorReport(  904): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2171)
E/ErrorReport(  904): 	at android.os.Binder.execTransact(Binder.java:412)
E/ErrorReport(  904): 	at dalvik.system.NativeStart.run(Native Method)
E/ErrorReport(  904): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  904): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  904): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  904): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  904): 	... 18 more
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "sms"
,F/PackageManager(  904): Unable to backup user packages state file, current changes will be lost at reboot
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,D/ErrorReport(  904): HtcErrorReportManager Begin---add error logs to dropbox
,E/ErrorReport(  904): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  904): java.io.FileNotFoundException: /data/misc/SYSTEM_WTF@1450189298920.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  904): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  904): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  904): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:540)
E/ErrorReport(  904): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:227)
E/ErrorReport(  904): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10800)
E/ErrorReport(  904): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10685)
E/ErrorReport(  904): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:379)
E/ErrorReport(  904): 	at android.util.Log$1.onTerribleFailure(Log.java:104)
E/ErrorReport(  904): 	at android.util.Log.wtf(Log.java:293)
E/ErrorReport(  904): 	at android.util.Log.wtf(Log.java:256)
E/ErrorReport(  904): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1134)
E/ErrorReport(  904): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:11872)
E/ErrorReport(  904): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:11928)
E/ErrorReport(  904): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1005)
E/ErrorReport(  904): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2171)
E/ErrorReport(  904): 	at android.os.Binder.execTransact(Binder.java:412)
E/ErrorReport(  904): 	at dalvik.system.NativeStart.run(Native Method)
E/ErrorReport(  904): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  904): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  904): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  904): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  904): 	... 18 more
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "smsto"
,F/PackageManager(  904): Unable to backup user packages state file, current changes will be lost at reboot
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
D/ErrorReport(  904): HtcErrorReportManager Begin---add error logs to dropbox
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "mms"
,F/PackageManager(  904): Unable to backup user packages state file, current changes will be lost at reboot
E/ErrorReport(  904): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  904): java.io.FileNotFoundException: /data/misc/SYSTEM_WTF@1450189298934.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  904): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  904): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  904): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:540)
E/ErrorReport(  904): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:227)
E/ErrorReport(  904): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10800)
E/ErrorReport(  904): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10685)
E/ErrorReport(  904): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:379)
E/ErrorReport(  904): 	at android.util.Log$1.onTerribleFailure(Log.java:104)
E/ErrorReport(  904): 	at android.util.Log.wtf(Log.java:293)
E/ErrorReport(  904): 	at android.util.Log.wtf(Log.java:256)
E/ErrorReport(  904): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1134)
E/ErrorReport(  904): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:11872)
E/ErrorReport(  904): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:11928)
E/ErrorReport(  904): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1005)
E/ErrorReport(  904): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2171)
E/ErrorReport(  904): 	at android.os.Binder.execTransact(Binder.java:412)
E/ErrorReport(  904): 	at dalvik.system.NativeStart.run(Native Method)
E/ErrorReport(  904): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  904): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  904): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  904): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  904): 	... 18 more
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
I/ActivityManager(  904): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,E/ExternalAccountType( 1317): Unsupported attribute readOnly
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "mmsto"
,F/PackageManager(  904): Unable to backup user packages state file, current changes will be lost at reboot
D/ErrorReport(  904): HtcErrorReportManager Begin---add error logs to dropbox
I/ActivityManager(  904): Resuming delayed broadcast
E/ErrorReport(  904): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  904): java.io.FileNotFoundException: /data/misc/SYSTEM_WTF@1450189298946.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  904): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  904): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  904): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:540)
E/ErrorReport(  904): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:227)
E/ErrorReport(  904): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10800)
E/ErrorReport(  904): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10685)
E/ErrorReport(  904): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:379)
E/ErrorReport(  904): 	at android.util.Log$1.onTerribleFailure(Log.java:104)
E/ErrorReport(  904): 	at android.util.Log.wtf(Log.java:293)
E/ErrorReport(  904): 	at android.util.Log.wtf(Log.java:256)
E/ErrorReport(  904): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1134)
E/ErrorReport(  904): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:11872)
E/ErrorReport(  904): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:11928)
E/ErrorReport(  904): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1005)
E/ErrorReport(  904): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2171)
E/ErrorReport(  904): 	at android.os.Binder.execTransact(Binder.java:412)
E/ErrorReport(  904): 	at dalvik.system.NativeStart.run(Native Method)
E/ErrorReport(  904): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  904): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  904): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  904): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  904): 	... 18 more
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,D/PhoneApp( 1216): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
D/ErrorReport(  904): HtcErrorReportManager Begin---add error logs to dropbox
E/ErrorReport(  904): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  904): java.io.FileNotFoundException: /data/misc/SYSTEM_WTF@1450189298956.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  904): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  904): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  904): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:540)
E/ErrorReport(  904): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:227)
E/ErrorReport(  904): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10800)
E/ErrorReport(  904): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10685)
E/ErrorReport(  904): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:379)
E/ErrorReport(  904): 	at android.util.Log$1.onTerribleFailure(Log.java:104)
E/ErrorReport(  904): 	at android.util.Log.wtf(Log.java:293)
E/ErrorReport(  904): 	at android.util.Log.wtf(Log.java:256)
E/ErrorReport(  904): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1134)
E/ErrorReport(  904): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:11872)
E/ErrorReport(  904): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:11928)
E/ErrorReport(  904): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1005)
E/ErrorReport(  904): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2171)
E/ErrorReport(  904): 	at android.os.Binder.execTransact(Binder.java:412)
E/ErrorReport(  904): 	at dalvik.system.NativeStart.run(Native Method)
E/ErrorReport(  904): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  904): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  904): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  904): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  904): 	... 18 more
I/ActivityManager(  904): Delay finish: com.htc.task/.TodoTaskReceiver
,D/RemoteDisplayProvider(  904): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  904): start
,W/PackageManager(  904): Unable to load service info ResolveInfo{42602270 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
I/ActivityManager(  904): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=3504 uid=10064 gids={50064, 3003, 5012, 1023, 1028, 1015}
,D/RemoteDisplayProvider(  904): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  904): start
,I/ActivityManager(  904): Resuming delayed broadcast
D/DFPI.PIReciver( 3244): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/ActivityManager(  904): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/DFPI.ApkInstallService( 3244): onHandleIntent
I/DFPI.ApkInstallService( 3244): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3244): check CID = HTC__032
I/DFPI.ApkInstallService( 3244): There is no Demo.apk in sd card or phone storage
,I/GCoreNlp( 1200): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/ActivityManager(  904): Resuming delayed broadcast
E/SQLiteLog( 1339): (3850) statement aborts at 46: [INSERT INTO partner(value,name) VALUES (?,?)] disk I/O error
E/SQLiteDBG( 1339): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/user/0/com.google.android.gsf/databases/googlesettings.db, handle = 0x5d6cd388
,E/SQLiteDatabase( 1339): Error inserting ...
E/SQLiteDatabase( 1339): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 1339): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 1339): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 1339): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 1339): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 1339): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 1339): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 1339): 	at com.google.android.gsf.settings.GoogleSettingsProvider.insert(GoogleSettingsProvider.java:236)
E/SQLiteDatabase( 1339): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 1339): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:193)
E/SQLiteDatabase( 1339): 	at android.os.Binder.execTransact(Binder.java:412)
E/SQLiteDatabase( 1339): 	at dalvik.system.NativeStart.run(Native Method)
,W/AtomicFile(  904): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
I/ActivityManager(  904): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,W/AppWidgetServiceImpl(  904): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,W/AtomicFile(  904): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
,D/LocationProviderProxy(  904): applying state to connected service
W/AppWidgetServiceImpl(  904): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
D/PMS     (  904): acquireWL(42928cf0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  904): applying state to connected service
D/PMS     (  904): releaseWL(42928cf0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  904): acquireWL(4292a3c0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  904): releaseWL(4292a3c0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(4292c1d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1200 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(4292c1d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/EASAppSvc( 3504): [ NA ]- onCreate()
,I/EASAppSvc( 3504): [ NA ]> onUpgrade: version = 63
,D/ORMLib  ( 3258): put()
,E/SQLiteLog( 3258): (3850) statement aborts at 31: [UPDATE TaskSource SET last_update=?,Description=?,PackageName=?,VersionCode=?,SupportedColumns=?,IsTimePrecision2Sec=?,VersionName=?,ServiceClassPath=?,AccountType=? WHERE _id=2] disk 
,E/SQLiteDBG( 3258): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.task/databases/MyDB.db, handle = 0x5ca9b6a0
E/DBProvider( 3258): disk I/O error (code 3850)
E/SQLiteDatabase( 3504): Failed to open database '/data/data/com.htc.android.mail/databases/mail.db'.
E/SQLiteDatabase( 3504): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3504): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3504): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3504): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 3504): 	at com.htc.android.mail.MailProvider$DatabaseWrapper.getReadableDatabase(MailProvider.java:5265)
E/SQLiteDatabase( 3504): 	at com.htc.android.mail.MailProvider$DatabaseWrapper.query(MailProvider.java:5330)
E/SQLiteDatabase( 3504): 	at com.htc.android.mail.MailProvider.query(MailProvider.java:2502)
E/SQLiteDatabase( 3504): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 3504): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 3504): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 3504): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 3504): 	at com.htc.android.mail.eassvc.EASAppSvc.createExchangeSources(EASAppSvc.java:3746)
E/SQLiteDatabase( 3504): 	at com.htc.android.mail.eassvc.EASAppSvc.initExchangeSources(EASAppSvc.java:3726)
E/SQLiteDatabase( 3504): 	at com.htc.android.mail.eassvc.EASAppSvc.access$1700(EASAppSvc.java:140)
E/SQLiteDatabase( 3504): 	at com.htc.android.mail.eassvc.EASAppSvc$MainHandlerThread.run(EASAppSvc.java:2265)
,W/System.err( 3258): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
W/System.err( 3258): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
W/System.err( 3258): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
W/System.err( 3258): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
W/System.err( 3258): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
W/System.err( 3258): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1645)
W/System.err( 3258): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1591)
W/System.err( 3258): 	at com.htc.task.dm.DBProvider.update(DBProvider.java:552)
W/System.err( 3258): 	at com.htc.task.APICProviderDecorator.update(APICProviderDecorator.java:490)
W/System.err( 3258): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
W/System.err( 3258): 	at android.content.ContentProviderClient.update(ContentProviderClient.java:251)
W/System.err( 3258): 	at com.htc.orm.Model.put(Model.java:143)
W/System.err( 3258): 	at com.htc.orm.Model.put(Model.java:170)
W/System.err( 3258): 	at com.htc.task.sm.PluginUpdatedServiceConnection.updateDB(PluginUpdatedServiceConnection.java:195)
W/System.err( 3258): 	at com.htc.task.sm.PluginUpdatedServiceConnection$1.run(PluginUpdatedServiceConnection.java:125)
,W/System.err( 3258): 	at java.lang.Thread.run(Thread.java:864)
,E/SQLiteOpenHelper( 3504): Couldn't open mail.db for writing (will try read-only):
E/SQLiteOpenHelper( 3504): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 3504): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 3504): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 3504): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 3504): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 3504): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 3504): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 3504): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 3504): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 3504): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 3504): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 3504): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 3504): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 3504): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 3504): 	at com.htc.android.mail.MailProvider$DatabaseWrapper.getReadableDatabase(MailProvider.java:5265)
E/SQLiteOpenHelper( 3504): 	at com.htc.android.mail.MailProvider$DatabaseWrapper.query(MailProvider.java:5330)
E/SQLiteOpenHelper( 3504): 	at com.htc.android.mail.MailProvider.query(MailProvider.java:2502)
E/SQLiteOpenHelper( 3504): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 3504): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 3504): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 3504): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 3504): 	at com.htc.android.mail.eassvc.EASAppSvc.createExchangeSources(EASAppSvc.java:3746)
E/SQLiteOpenHelper( 3504): 	at com.htc.android.mail.eassvc.EASAppSvc.initExchangeSources(EASAppSvc.java:3726)
E/SQLiteOpenHelper( 3504): 	at com.htc.android.mail.eassvc.EASAppSvc.access$1700(EASAppSvc.java:140)
E/SQLiteOpenHelper( 3504): 	at com.htc.android.mail.eassvc.EASAppSvc$MainHandlerThread.run(EASAppSvc.java:2265)
,I/EASAppSvc( 3504): [ NA ]- onDestroy()
,I/EASAppSvc( 3504): [ NA ]> uninitEASService
,W/SQLiteOpenHelper( 3504): Opened mail.db in read-only mode
,D/WifiService(  904): New client listening to asynchronous messages
,D/ConnectivityService(  904): getNetworkInfo networkType=1 called by com.htc.android.mail (3504/10064)
,D/ConnectivityService(  904): getNetworkInfo networkType=0 called by com.htc.android.mail (3504/10064)
,D/ConnectivityService(  904): getNetworkInfo networkType=55 called by com.htc.android.mail (3504/10064)
,I/EASRequestController( 3504): [ NA ]release
,I/EASAppSvc( 3504): [ NA ]< uninitEASService
,I/EASAppSvc( 3504): [ NA ]- onCreate()
,I/EASAppSvc( 3504): [ NA ]> onUpgrade: version = 63
,D/Process (  904): killProcessQuiet, pid=3273
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by com.htc.android.mail (3504/10064)
I/ActivityManager(  904): Killing 3273:com.htc.stock/u0a82 (adj 15): empty #17
D/ConnectivityService(  904): getNetworkInfo networkType=0 called by com.htc.android.mail (3504/10064)
D/ConnectivityService(  904): getNetworkInfo networkType=55 called by com.htc.android.mail (3504/10064)
,I/ActivityManager(  904): Recipient 3273
,D/ORMLib  ( 3258): put()
E/SQLiteLog( 3258): (3850) statement aborts at 31: [UPDATE TaskSource SET last_update=?,Description=?,PackageName=?,VersionCode=?,SupportedColumns=?,IsTimePrecision2Sec=?,VersionName=?,ServiceClassPath=?,AccountType=? WHERE _id=3] disk 
E/SQLiteDBG( 3258): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.task/databases/MyDB.db, handle = 0x5ca9b6a0
,E/DBProvider( 3258): disk I/O error (code 3850)
W/System.err( 3258): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
W/System.err( 3258): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
W/System.err( 3258): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
W/System.err( 3258): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
,W/System.err( 3258): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
W/System.err( 3258): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1645)
W/System.err( 3258): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1591)
W/System.err( 3258): 	at com.htc.task.dm.DBProvider.update(DBProvider.java:552)
W/System.err( 3258): 	at com.htc.task.APICProviderDecorator.update(APICProviderDecorator.java:490)
W/System.err( 3258): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
W/System.err( 3258): 	at android.content.ContentProviderClient.update(ContentProviderClient.java:251)
W/System.err( 3258): 	at com.htc.orm.Model.put(Model.java:143)
W/System.err( 3258): 	at com.htc.orm.Model.put(Model.java:170)
W/System.err( 3258): 	at com.htc.task.sm.PluginUpdatedServiceConnection.updateDB(PluginUpdatedServiceConnection.java:195)
W/System.err( 3258): 	at com.htc.task.sm.PluginUpdatedServiceConnection$1.run(PluginUpdatedServiceConnection.java:125)
,W/System.err( 3258): 	at java.lang.Thread.run(Thread.java:864)
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/EASAppSvc( 3504): [ NA ]- onDestroy()
I/EASAppSvc( 3504): [ NA ]> uninitEASService
,I/EASRequestController( 3504): [ NA ]release
,I/EASAppSvc( 3504): [ NA ]< uninitEASService
I/ActivityManager(  904): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=3537 uid=10068 gids={50068, 3003, 5012}
,D/Process (  904): killProcessQuiet, pid=3285
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3285:com.htc.stock:remote/u0a82 (adj 15): empty #17
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ORMLib  ( 3258): put()
E/SQLiteLog( 3258): (3850) statement aborts at 31: [UPDATE TaskSource SET last_update=?,Description=?,PackageName=?,VersionCode=?,SupportedColumns=?,IsTimePrecision2Sec=?,VersionName=?,ServiceClassPath=?,AccountType=? WHERE _id=4] disk 
,E/SQLiteDBG( 3258): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.task/databases/MyDB.db, handle = 0x5ca9b6a0
E/DBProvider( 3258): disk I/O error (code 3850)
W/System.err( 3258): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
W/System.err( 3258): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
W/System.err( 3258): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
W/System.err( 3258): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
W/System.err( 3258): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
W/System.err( 3258): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1645)
,W/System.err( 3258): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1591)
W/System.err( 3258): 	at com.htc.task.dm.DBProvider.update(DBProvider.java:552)
W/System.err( 3258): 	at com.htc.task.APICProviderDecorator.update(APICProviderDecorator.java:490)
W/System.err( 3258): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
W/System.err( 3258): 	at android.content.ContentProviderClient.update(ContentProviderClient.java:251)
W/System.err( 3258): 	at com.htc.orm.Model.put(Model.java:143)
W/System.err( 3258): 	at com.htc.orm.Model.put(Model.java:170)
W/System.err( 3258): 	at com.htc.task.sm.PluginUpdatedServiceConnection.updateDB(PluginUpdatedServiceConnection.java:195)
W/System.err( 3258): 	at com.htc.task.sm.PluginUpdatedServiceConnection$1.run(PluginUpdatedServiceConnection.java:125)
,W/System.err( 3258): 	at java.lang.Thread.run(Thread.java:864)
I/ActivityManager(  904): Recipient 3285

```
