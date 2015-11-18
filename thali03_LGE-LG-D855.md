#### Test 50388019f4ce509_thali03_LGE-LG-D855 Logs


```
--------- beginning of system
I/ActivityManager( 1030): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=4283 uid=10008 gids={50008, 9997, 3003} abi=armeabi-v7a
--------- beginning of main
D/LocationManagerService( 1030): getProviders()=[passive]
I/Velvet.VelvetFactory( 4255): refreshing internal icing corpora
I/ContactAccountLoggerTas( 4255): canRun() : Opted Out
I/ActivityManager( 1030): Killing 3810:com.lge.clock/u0a10 (adj 15): empty #17
I/Velvet.VelvetFactory( 4255): refreshing search history.
D/LgDataFeature( 4255): LgDataFeature() Constructor: none
D/LgDataFeature( 4255): LgDataFeature() Constructor Done, null
W/libprocessgroup( 1030): failed to open /acct/uid_10010/pid_3810/cgroup.procs: No such file or directory
I/ContactAccountLoggerTas( 4255): canRun() : Opted Out
I/ContactAccountLoggerTas( 4255): canRun() : Opted Out
D/WifiService( 1030): New client listening to asynchronous messages
I/MediaRouter( 4255): Found default route: MediaRouter.RouteInfo{ uniqueId=android/mo:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
I/FavoriteContactNamesSup( 4255): get() : Execute runnable (UI thread)
I/ContactLabelSupplier( 4255): get() : Execute runnable (UI thread)
I/UpdateIcingCorporaServi( 4255): Updating corpora: APPS=MAYBE, CONTACTS=MAYBE
D/WiseScreenService( 2011): [OnBootReceiver.java:24:onReceive()] iKeepScreenOn: 0
D/WiseScreenService( 2011): [OnBootReceiver.java:28:onReceive()] iSmartVideo: 0
W/ContextImpl( 2011): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1763 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.lge.keepscreenon.OnBootReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2586 
I/WebViewFactory( 4255): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
W/ContextImpl( 1030): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.dsi.ant.server.AntService.startService:129 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
W/ContextImpl( 1030): Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.dsi.ant.server.AntService.startService:129 
E/ThermalEngine(  339): [GPU_MON] 0 percent. Current Sampling Time is 1 sec
I/ActivityManager( 1030): Start proc com.lge.cloudhub for broadcast com.lge.cloudhub/.service.CloudHubReceiver: pid=4323 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/LibraryLoader( 4255): Loading: webviewchromium
I/LibraryLoader( 4255): Time to load native libraries: 6 ms (timestamps 5970-5976)
I/LibraryLoader( 4255): Expected native library version number "",actual native library version number ""
I/GLSUser ( 2136): [ChannelManager] Attempting to channel bind connection HttpClient.
I/GLSUser ( 2136): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
I/GLSUser ( 2136): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
I/GLSUser ( 2136): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2136): [GLSUser] Extracting token using key: Auth
W/art     ( 4255): Attempt to remove local handle scope entry from IRT, ignoring
W/GLSActivity( 2136): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2136): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 1030): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
W/ActivityManager( 1030): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
I/Icing   ( 2326): Storage manager: low false usage 1.99MB avail 19.92GB capacity 21.67GB
V/CloudHub( 4323): [DATABASE][DBConnection|open] open database
I/NotificationStore( 2136): System rebooted after Notification storage file was last written
I/NotificationStore( 2136): Deleting the file
E/CloudHub( 4323): [DATABASE][DBConnection|getUserId] User id: 0
E/CloudHub( 4323): [DATABASE][DBConnection|getDatabasePath] Database path: /data/user/0/com.lge.cloudhub/databases/cloudhub.db
D/libc-netbsd(  318): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1030): DNSproblemNotiEnabled is disabled ignore DNS fail CB
W/NetworkUtils( 4255): OkHttp exception
I/ContactAccountLoggerTas( 4255): canRun() : Opted Out
V/CloudHub( 4323): [SERVICE][CloudHubReceiver|queryUploadCount] # of contents to upload: 0
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/ZenLog  ( 1030): intercepted: 0|com.google.android.gms|1|null|10005,none
V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GAV2    ( 4255): Thread[Background Non-Blocking-0,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
V/DownloadManager( 3303): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR status='197' OR (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3303): created cursor android.database.sqlite.SQLiteCursor@1456ac5c on behalf of 4323
W/ResourcesManager( 1461): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1461): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 1415): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1415): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/LgeQuickCoverNLService( 1415): onNotificationPosted
W/GAV2    ( 4255): Thread[Background Non-Blocking-0,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
D/SmartCoverUpdateMonitor( 1415): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1415): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1415): handleNotificationPosted(true)
D/QuickCircle( 1415): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1415): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post do add job
D/LgeQuickCoverNotificationData( 1415): add : 2
D/LgeQuickCoverNotificationData( 1415): do add job
D/LgeQuickCoverNotificationData( 1415): showAll3
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1415): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
I/ContactAccountLoggerTas( 4255): canRun() : Opted Out
V/CloudHub( 4323): [SERVICE][CloudHubReceiver|queryDownloadCount] # of contents to download: 0
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  1
W/Search.LoginHelper( 4255): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 4255): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
I/ContactLabelSupplier( 4255): get() : OptedIn = false
I/ContactAccountLoggerTas( 4255): canRun() : Opted Out
I/ActivityManager( 1030): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=4354 uid=10059 gids={50059, 9997, 3003} abi=armeabi-v7a
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1415): updateNotificationData: count=3
D/QuickStatusbarLayout( 1415): Notification difference=198
D/QuickStatusbarLayout( 1415): child = android.widget.LinearLayout{f6efe53 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/art     (  355): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 265us total 14.074ms
I/art     (  355): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 255us total 12.295ms
I/art     (  355): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 254us total 12.021ms
E/UpdateRequestReceiver( 4354): ignoring update request
E/UpdateRequestReceiver( 4354): ignoring update request
E/UpdateRequestReceiver( 4354): ignoring update request
E/UpdateRequestReceiver( 4354): ignoring update request
E/UpdateRequestReceiver( 4354): ignoring update request
E/UpdateRequestReceiver( 4354): ignoring update request
I/ActivityManager( 1030): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4384 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1030): Killing 3892:com.lge.appbox.client:SingleBinaryService/u0a11 (adj 15): empty #17
W/libprocessgroup( 1030): failed to open /acct/uid_10011/pid_3892/cgroup.procs: No such file or directory
I/Icing   ( 2326): updateResources: need to parse f{com.google.android.gms}
V/DrmBroadcastReceiver( 4384): Receive ACTION_BOOT_COMPLETED
V/DrmService( 4384): Service onCreate
D/DrmService( 4384): Received new request = 4
D/DrmServiceHandler( 4384): updateDrmPushNotification() : No notification
D/DrmService( 4384): Completed !! request = 4
D/DrmService( 4384): Request count = 0
I/ActivityManager( 1030): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4401 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/DrmService( 4384): Service onDestroy
I/ActivityManager( 1030): Killing 3919:com.lge.appbox.client/u0a11 (adj 15): empty #17
W/libprocessgroup( 1030): failed to open /acct/uid_10011/pid_3919/cgroup.procs: No such file or directory
I/Icing   ( 2326): Internal init done: storage state 0
I/Icing   ( 2326): Post-init done
,W/ActivityManager( 1030): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/ActivityThread( 4401): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
W/ActivityManager( 1030): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 4401): getAccountsCursor
D/AndroidRuntime( 4424): 
D/AndroidRuntime( 4424): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4424): CheckJNI is OFF
I/art     ( 1030): Explicit concurrent mark sweep GC freed 19901(1019KB) AllocSpace objects, 4(923KB) LOS objects, 33% free, 43MB/65MB, paused 2.420ms total 140.118ms
V/GLSActivity( 2136): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 1030): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager( 1030): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager( 1030): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/GAV2    ( 4401): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/Gmail   ( 4401): Observing account changes for notifications
W/ActivityManager( 1030): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager( 1030): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/Gmail   ( 4401): Error finding the version of the Email provider.....
E/Gmail   ( 4401): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 4401): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 4401): 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1235)
E/Gmail   ( 4401): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:187)
E/Gmail   ( 4401): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 4401): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 4401): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 4401): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 4401): We do not support migrating this version of the Email provider.
I/Gmail   ( 4401): getAccountsCursor
V/GLSActivity( 2136): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 4424): Calling main entry com.android.commands.am.Am
V/SIM_STK ( 1030): Menu title from STK is T-Mobile
I/UpdateIcingCorporaServi( 4255): UpdateCorporaTask done [took 1295 ms] updated apps [took 1295 ms] 
I/ActivityManager( 1030): Start proc com.lge.gnss.airtest for broadcast com.lge.gnss.airtest/.GnssAirTestReceiver: pid=4467 uid=10065 gids={50065, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1030): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
V/GLSActivity( 2136): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/SplitWindowPolicy( 1963): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1030): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
V/ActivityStackEx( 1030): create ActivityStackEx
D/LgeAbsQuickCoverView( 1415): mCoverXPos: 0 ,mCoverYPos: 0
D/LgeAbsQuickCoverView( 1415): mCoverWidth: 0 ,mCoverHeight: 0
D/ActivityManager( 1030): setTaskToReturnTo : TaskRecord{9d076ae #2 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1030): setTaskToReturnTo : TaskRecord{9d076ae #2 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1030): AppWindowTokenEx init.. 
D/ContextHelper( 1030): convertTheme. context->name=com.example.hello themeResourceId=16973833
E/GBMv2   (  351): DFP En is all cleared set to be enabled
I/[LGHome]EVENT( 2083): [Launcher.java:1114:onPause()]onPause
W/ActivityManager( 1030): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/SplitWindow( 1030): check instance of lgWin Window{dbfadc8 u0 Starting com.example.hello}
D/ActionManagerService( 1922): notifyUserLog: 1000004
D/SplitWindowPolicy( 1963): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/LIA_Informant_ActionManagerMessageHandler( 2697): handleMessage: what(1000) actionID(0x1000004)
D/SplitWindowPolicy( 1963): topRunningActivity=ActivityInfo{111663dd co.....Launcher}, taskId=1, activityType=1, bIsSplit=false
D/AndroidRuntime( 4424): Shutting down VM
V/BoardContentProvider( 2697): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
W/ActivityManager( 1030): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/QuickStatusbarLayout( 1415): Notification difference=198
D/QuickStatusbarLayout( 1415): child = android.widget.LinearLayout{f6efe53 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/SQLiteLog( 4401): (283) recovered 357 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
I/ActivityManager( 1030): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4486 uid=10318 gids={50318, 9997, 3003, 3001, 3002} abi=armeabi-v7a
E/ActivityThread( 4401): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@c2f7319 that was originally bound here
E/ActivityThread( 4401): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@c2f7319 that was originally bound here
E/ActivityThread( 4401): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
E/ActivityThread( 4401): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
E/ActivityThread( 4401): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
E/ActivityThread( 4401): 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
E/ActivityThread( 4401): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4401): 	at com.android.emailcommon.service.H.a(SourceFile:181)
E/ActivityThread( 4401): 	at com.android.emailcommon.service.H.mb(SourceFile:224)
E/ActivityThread( 4401): 	at com.android.email.service.n.j(SourceFile:160)
E/ActivityThread( 4401): 	at com.android.email.provider.b.a(SourceFile:171)
E/ActivityThread( 4401): 	at com.android.email.provider.b.F(SourceFile:115)
E/ActivityThread( 4401): 	at com.android.email.service.EmailBroadcastProcessorService.kD(SourceFile:305)
E/ActivityThread( 4401): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:130)
E/ActivityThread( 4401): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4401): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4401): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 4401): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager( 1030): Unbind failed: could not find connection for android.os.BinderProxy@a953899
I/GBoardWebViewUtils( 2083): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2083): , create_time: 1430558575574
I/GBoardWebViewUtils( 2083): , expire_time: 0
I/GBoardWebViewUtils( 2083): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2083): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2083): , display: false
I/GBoardWebViewUtils( 2083): , animation: false }
I/GBoardWebViewUtils( 2083): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2083): , create_time: 1430558575600
I/GBoardWebViewUtils( 2083): , expire_time: 0
I/GBoardWebViewUtils( 2083): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2083): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2083): , display: false
I/GBoardWebViewUtils( 2083): , animation: false }
I/GBoardWebViewUtils( 2083): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1447331016048
I/GBoardWebViewUtils( 2083): , create_time: 1447331016852
I/GBoardWebViewUtils( 2083): , expire_time: 0
I/GBoardWebViewUtils( 2083): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1447331016048&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2083): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2083): , display: false
I/GBoardWebViewUtils( 2083): , animation: false }
I/[LGHome]GBoardWebView( 2083): [GBoardWebView.java:266:writeCacheBitmap()]writeCacheBitmap()
I/WindowStateAnimator( 1030): Starting window displayed
I/SystemUI[Framework]( 1030): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
D/PhoneStatusBar( 1461): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
W/PhoneWindowManagerEx( 1030): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1030): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1030): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1030): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3d2b6ef7,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1030): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1461): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1461):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1461): , Keyguard show=false, IME shown=false, Panel expanded=false
D/AirTest ( 4467): Set airtest_enable to false
D/SplitWindowPolicy( 1963): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1963): topRunningActivity=ActivityInfo{32e40b52 co.....MainActivity}, taskId=2, activityType=0, bIsSplit=false
I/ActivityManager( 1030): Killing 3946:com.android.browser/u0a12 (adj 15): empty #17
I/GoogleHttpClient( 2136): GMS http client unavailable, use old client
I/Gmail   ( 4401): notifyAccountChanged
,I/Gmail   ( 4401): getAccountsCursor
I/Gmail   ( 4401): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 4401): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 4401): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 4401): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/ActivityManager( 1030): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4508 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/ContextHelper( 4486): convertTheme. context->name=com.example.hello themeResourceId=16973833
V/GLSActivity( 2136): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/[LGHome]EVENT( 2083): [Launcher.java:5349:onStop()]onStop
,W/ActivityThread( 2083): Performing stop of activity that is not resumed: {com.lge.launcher2/com.lge.launcher2.Launcher}
W/ActivityThread( 2083): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.lge.launcher2/com.lge.launcher2.Launcher}
W/ActivityThread( 2083): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3321)
W/ActivityThread( 2083): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3407)
W/ActivityThread( 2083): 	at android.app.ActivityThread.access$1100(ActivityThread.java:148)
W/ActivityThread( 2083): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1312)
W/ActivityThread( 2083): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ActivityThread( 2083): 	at android.os.Looper.loop(Looper.java:135)
W/ActivityThread( 2083): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ActivityThread( 2083): 	at java.lang.reflect.Method.invoke(Native Method)
W/ActivityThread( 2083): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ActivityThread( 2083): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ActivityThread( 2083): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/Gmail   ( 4401): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_promo (has extras) }
,I/Gmail   ( 4401): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_social (has extras) }
,W/ResourcesManager( 4508): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/Gmail   ( 4401): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_personal (has extras) }
I/ActivityManager( 1030): Killing 3968:com.android.cellbroadcastreceiver/u0a16 (adj 15): empty #17
,I/WebViewFactory( 4486): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
E/UEI.SmartControl( 4005): file observer is disposed!
,W/libprocessgroup( 1030): failed to open /acct/uid_10016/pid_3968/cgroup.procs: No such file or directory
,I/ActivityManager( 1030): Activity reported stop, but no longer stopping: ActivityRecord{1dd67f9e u0 com.lge.launcher2/.Launcher t1}
I/LibraryLoader( 4486): Loading: webviewchromium
I/LibraryLoader( 4486): Time to load native libraries: 4 ms (timestamps 7704-7708)
,I/LibraryLoader( 4486): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 4486): Binding Chromium to main looper Looper (main, tid 1) {3a047685}
I/LibraryLoader( 4486): Expected native library version number "",actual native library version number ""
I/chromium( 4486): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4486): Initializing chromium process, renderers=0
,D/LgDataFeature( 4508): LgDataFeature() Constructor: none
D/LgDataFeature( 4508): LgDataFeature() Constructor Done, null
W/art     ( 4486): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 4486): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
V/AudioPolicyService(  324): registerClient() client 0xb154f200, uid 10318
W/chromium( 4486): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 4486): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 4486): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothManagerService( 1030): Message: 20
D/BluetoothManagerService( 1030): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8087a09:true
,D/BluetoothAdapter( 4486): 1071721690: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 4486): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4486): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 4486): Build Date: 12/12/14 금
I/Adreno-EGL( 4486): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 4486): Remote Branch: 
I/Adreno-EGL( 4486): Local Patches: 
I/Adreno-EGL( 4486): Reconstruct Branch: 
,I/art     ( 2136): Explicit concurrent mark sweep GC freed 34347(2MB) AllocSpace objects, 3(432KB) LOS objects, 34% free, 30MB/46MB, paused 1.637ms total 48.747ms
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 47783735035; DSPS: 1706571; Offset : -4310197530
I/Gmail   ( 4401): getAccountsCursor
V/GLSActivity( 2136): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConciergeFeature( 2697): Trying to open card setting file : /system/etc/mrg_default_forms/ConciergeBoard/card_settings/card_settings.json
D/ConciergeFeature( 2697): concierge_reconnect_old_contact  : true
D/ConciergeFeature( 2697): concierge_add_contact_proposal  : true
D/ConciergeFeature( 2697): concierge_redial_recommend  : true
D/ConciergeFeature( 2697): concierge_notify_birthday  : true
D/ConciergeFeature( 2697): concierge_qmemo  : true
D/ConciergeFeature( 2697): concierge_weather_newsflash  : false
D/ConciergeFeature( 2697): concierge_spring_cleaning  : true
D/ConciergeFeature( 2697): concierge_my_guide  : true
D/ConciergeFeature( 2697): concierge_my_wellness  : true
D/ConciergeFeature( 2697): concierge_isai_keyword_update  : false
I/LIA_Informant_ConciergeCardManager( 2697): availability of concierge_reconnect_old_contact: true
D/LIA_Informant_FlowManagerPlant( 2697): FAVORITENUM_RECOMMENDER
D/LIA_Informant_FavoriteNumScheduler( 2697): start!
I/LIA_Informant_ActionManagerMessageHandler( 2697): registerListener = concierge_reconnect_old_contact
I/LIA_Informant_ActionManagerMessageHandler( 2697): after add numListener = 6
,D/LIA_Informant_FavoriteNumScheduler( 2697): curentDate : 20151118
D/LIA_Informant_FavoriteNumScheduler( 2697): AlarmReceivedDate : 20151118
D/InformantAlarmUtil( 2697): getFirstAlarm
D/LIA_Informant_InformantCalendarUtil( 2697): getDay()
D/InformantAlarmUtil( 2697): getAlarmListOfDay: day = 5
,I/ActivityManager( 1030): Start proc com.lge.clock for content provider com.lge.clock/.alarmclock.ALProvider: pid=4555 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
I/Babel   ( 4508): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 4508): MmsConfig.loadMmsSettings
,I/Babel   ( 4508): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,I/Babel   ( 4508): MmsConfig.loadFromDatabase
W/chromium( 4486): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 4486): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 4486): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 4486): onDetachedFromWindow called when already detached. Ignoring
E/Babel   ( 4508): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 4508): MmsConfig.loadFromResources
E/Babel   ( 4508): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 4508): MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
D/SystemWebViewEngine( 4486): CordovaWebView is running on device made by: LGE
,W/Settings( 4508): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/AudioCapabilities( 4508): Unsupported mime audio/evrc
W/art     ( 4486): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4486): Attempt to remove local handle scope entry from IRT, ignoring
D/LIA_Informant_FavoriteNumScheduler( 2697): setAlarm
D/LIA_Informant_FavoriteNumScheduler( 2697): Date : Wed Nov 18 08:00:00 GMT+01:00 2015
W/AudioCapabilities( 4508): Unsupported mime audio/qcelp
,D/ConciergeFeature( 2697): Trying to open card setting file : /system/etc/mrg_default_forms/ConciergeBoard/card_settings/card_settings.json
D/ConciergeFeature( 2697): concierge_reconnect_old_contact  : true
D/ConciergeFeature( 2697): concierge_add_contact_proposal  : true
D/ConciergeFeature( 2697): concierge_redial_recommend  : true
D/ConciergeFeature( 2697): concierge_notify_birthday  : true
D/ConciergeFeature( 2697): concierge_qmemo  : true
D/ConciergeFeature( 2697): concierge_weather_newsflash  : false
D/ConciergeFeature( 2697): concierge_spring_cleaning  : true
D/ConciergeFeature( 2697): concierge_my_guide  : true
D/ConciergeFeature( 2697): concierge_my_wellness  : true
D/ConciergeFeature( 2697): concierge_isai_keyword_update  : false
I/LIA_Informant_ConciergeCardManager( 2697): availability of concierge_notify_birthday: true
D/LIA_Informant_FlowManagerPlant( 2697): BIRTHDAY_NOTI
D/LIA_Informant_AnniversaryRequester( 2697): AnniversaryRequester
D/LIA_Informant_AnniversaryMessageGenerator( 2697): AnniversaryMessageGenerator
D/LIA_Informant_DailyScheduler( 2697): AlarmCheckingScheduler = 0
D/LIA_Informant_DailyScheduler( 2697): start!
D/LIA_Informant_DailyScheduler( 2697): curentDate : 20151118
W/VideoCapabilities( 4508): Unrecognized profile 2130706433 for video/avc
D/LIA_Informant_DailyScheduler( 2697): excutedDate : 20151118
I/LIA_Informant_ConciergeCardManager( 2697): after add event [4]
,D/LIA_S4URecommender_LIARemoteService( 2697): onStartCommand() : LIARemoteService started! - (Id :3), Intent { act=com.lge.ia.task.s4urecommender pkg=com.lge.ia.task.s4urecommender (has extras) }
D/LIA_Informant_ConnectionProxy( 2697): onServiceConnected() : com.lge.ia.task.s4urecommender
D/LIA_S4URecommender_LIARemoteManager( 2697): getProperties()
D/LIA_S4URecommender_TaskLauncher( 2697): getTaskPropertyList() - main launcher : false
I/LIA_Informant_ConnectionProxy( 2697): Checking activation option of S4URecommender
I/LIA_Informant_ConnectionProxy( 2697): Task Property : S4URecommender, true
I/LIA_Informant_ConnectionProxy( 2697): Task activation property : S4URecommender, true
I/LIA_Informant_ConnectionProxyHandler( 2697): ConnectionProxyListener - onConnected : 
V/LIA_Informant_ConnectionProxyHandler( 2697): S4URecommender Task Property: Activation:true, AutoExecution:true
D/LIA_Informant_ConnectionProxy( 2697): getTaskConnector(S4URecommender / com.lge.ia.task.s4urecommender) : Thread(1)
D/LIA_S4URecommender_LIARemoteManager( 2697): getTask() : S4URecommender
D/LIA_S4URecommender_TaskLauncher( 2697): getTask() : S4URecommender (main launcher : false)
D/OpenGLRenderer( 4486): Render dirty regions requested: true
I/OpenGLRenderer( 4486): Initialized EGL, version 1.4
I/LIA_S4URecommender_TaskContext( 2697): getNewAppSession() : App session is added - com.lge.ia.manager.session.AppSession@219a60d9
I/LIA_Informant_ConnectionProxyHandler( 2697): setTaskConnectorIntoTask - Success
I/LIA_Informant_ConnectionProxyHandler( 2697): stopTimeoutTimer
I/LIA_Informant_LGIntelligentAgent( 2697): tryConnecting : onTryConnectionSuccess - com.lge.ia.LIAS4URecommender@19138a9e
I/LIA_Informant_LGIntelligentAgent( 2697): tryConnecting onTryConnectionSuccess : map remove - 0
D/LIA_Informant_RedialManager( 2697): S4URecommender onConnected!
I/ActivityManager( 1030): Killing 2972:com.android.contacts/u0a19 (adj 15): empty #17
,D/OpenGLRenderer( 4486): Enabling debug mode 0
,W/AudioCapabilities( 4508): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 4508): Unsupported mime audio/qcelp
W/AudioCapabilities( 4508): Unsupported mime audio/evrc
D/Atlas   ( 4486): Validating map...
D/SplitWindow( 1030): check instance of lgWin Window{bf4589c u0 com.example.hello/com.example.hello.MainActivity}
W/VideoCapabilities( 4508): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 4508): Unsupported mime video/divx
W/VideoCapabilities( 4508): Unsupported mime video/divx311
W/VideoCapabilities( 4508): Unsupported mime video/divx4
W/VideoCapabilities( 4508): Unsupported mime video/mp4v-esdp
D/LgDataFeature( 4486): LgDataFeature() Constructor: none
D/LgDataFeature( 4486): LgDataFeature() Constructor Done, null
,I/VideoCapabilities( 4508): Unsupported profile 4 for video/mp4v-es
W/AudioCapabilities( 4508): Unsupported mime audio/eac3
W/AudioCapabilities( 4508): Unsupported mime audio/ac3
W/AudioCapabilities( 4508): Unsupported mime audio/g726
W/AudioCapabilities( 4508): Unsupported mime audio/wma-voice
W/AudioCapabilities( 4508): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 4508): Unsupported mime audio/adpcm
W/VideoCapabilities( 4508): Unsupported mime video/theora
W/VideoCapabilities( 4508): Unsupported mime video/mjpg
,W/libprocessgroup( 1030): failed to open /acct/uid_10019/pid_2972/cgroup.procs: No such file or directory
I/ActivityManager( 1030): Killing 2506:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
I/Timeline( 4486): Timeline: Activity_idle id: android.os.BinderProxy@2ece808a time:48117
,W/libprocessgroup( 1030): failed to open /acct/uid_10005/pid_2506/cgroup.procs: No such file or directory
,W/ActivityManager( 1030): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
V/AudioPolicyService(  324): registerClient() client 0xb1427b80, uid 10003
I/ActivityManager( 1030): Displayed com.example.hello/.MainActivity: +895ms
I/Timeline( 1030): Timeline: Activity_windows_visible id: ActivityRecord{2a7fbc4f u0 com.example.hello/.MainActivity t2} time:48142
,V/Babel   ( 4508): babel boot account: SMS
V/Babel   ( 4508): babel boot account: thalitester@gmail.com
I/chromium( 4486): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 4486): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/ActivityManager( 1030): Start proc com.lge.hiddenmenu for broadcast com.lge.hiddenmenu/.lgodm.LGODMReceiver: pid=4594 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1030): Killing 4032:com.lge.email/u0a23 (adj 15): empty #17
,D/JsMessageQueue( 4486): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 4486): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 4486): 
,W/ActivityManager( 1030): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
W/libprocessgroup( 1030): failed to open /acct/uid_10023/pid_4032/cgroup.procs: No such file or directory
V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{353c6288 type 2 when 48289 com.google.android.talk} when 48289
V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{deb9421 type 2 when 48310 com.google.android.talk} when 48310
,W/ResourcesManager( 4594): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/chromium( 4486): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 4486): 
,I/ActivityManager( 1030): Killing 3638:com.wsandroid.suite.lge/1000 (adj 15): empty #17
V/LGSC    ( 1871): [101] 102, action=android.intent.action.BOOT_COMPLETED, iccState=null
,W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_3638/cgroup.procs: No such file or directory
D/jxcore_app_log( 4486): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435325696
,D/JX-Cordova( 4486): jxcore cordova android initializing
I/ActivityManager( 1030): Start proc com.lge.defaultaccount for broadcast com.lge.defaultaccount/.receiver.ReceiverBootUp: pid=4616 uid=10073 gids={50073, 9997} abi=armeabi-v7a
,I/InsertAccount( 4616): The account already exists
,W/jxcore-log( 4486): Initializing JXcore engine
W/jxcore-log( 4486): JXcore engine is ready
,W/jxcore-log( 4486): Starting JXcore engine
,I/ActivityManager( 1030): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=4634 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1030): Killing 4005:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
W/m.example.hello( 4486): type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[9742]" dev="sockfs" ino=9742 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/m.example.hello( 4486): type=1400 audit(0.0:149): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,W/m.example.hello( 4486): type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[10434]" dev="sockfs" ino=10434 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/m.example.hello( 4486): type=1400 audit(0.0:151): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/m.example.hello( 4486): type=1400 audit(0.0:152): avc: denied { ioctl } for path="socket:[24010]" dev="sockfs" ino=24010 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_4005/cgroup.procs: No such file or directory
,I/InsertAccount( 4616): The account info in contact DB already exists
,W/ResourcesManager( 4634): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/ActivityManager( 1030): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4651 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi
,W/ActivityManager( 1030): Unable to start service Intent { act=com.lge.contacts.intent.action.BACKUP_DB flg=0x4 cmp=com.android.providers.contacts/com.lge.providers.contacts.backup.DatabaseBackupService (has extras) } U=0: not found
V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{b22faa0 type 0 when 1447661575907 com.android.providers.contacts} when 1447661575907
V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{1e01a659 type 2 when 48046 com.google.android.talk} when 48046
V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{939221e type 2 when 48812 com.google.android.gms} when 48812
W/jxcore-log( 4486): Platform android
W/jxcore-log( 4486): 
W/jxcore-log( 4486): Process ARCH arm
W/jxcore-log( 4486): 
,E/GBMv2   (  351): DFP En is all cleared set to be enabled
E/GBMv2   (  351): Set value is all cleared set the max
I/GBMv2   (  351): DFP Enabled. Ignore VFP set
D/LGBluetoothProfileConnectionReceiver_EasySetting( 4634): [BTUI] ACTION_BOOT_COMPLETED : reset connected device information
,I/ActivityManager( 1030): Killing 4096:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
I/jxcore-log( 4486): JXcore Cordova bridge is ready!
I/jxcore-log( 4486): 
,W/jxcore-log( 4486): JXcore engine is started
,W/ResourcesManager( 4651): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/ActivityManager( 1030): Start proc com.lge.lgfota.permission for broadcast com.lge.lgfota.permission/.DmcTargetValidationReceiver: pid=4669 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1030): Killing 4074:com.lge.lifetracker/u0a37 (adj 15): empty #17
I/art     (  355): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 429us total 21.254ms
,E/jxcore-log( 4486): >> LGE-LG-D855
E/jxcore-log( 4486): 
,I/jxcore-log( 4486): Total memory 2995761152
I/jxcore-log( 4486): 
I/jxcore-log( 4486): Free memory 860700672
I/jxcore-log( 4486): 
I/jxcore-log( 4486): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4486): 
I/jxcore-log( 4486): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4486): 
I/jxcore-log( 4486): userPath [ 'www' ]
I/jxcore-log( 4486): 
I/art     (  355): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 410us total 18.880ms
I/jxcore-log( 4486): Size 1440 2392
I/jxcore-log( 4486): 
I/jxcore-log( 4486): Screen Brightness 50
I/jxcore-log( 4486): 
E/jxcore-log( 4486): Dummy Error Log.
E/jxcore-log( 4486): 
D/CalendarProvider2( 4651): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@363836c9
,I/art     (  355): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 416us total 18.488ms
W/libprocessgroup( 1030): failed to open /acct/uid_10080/pid_4096/cgroup.procs: No such file or directory
,I/ActivityManager( 1030): Waited long enough for: ServiceRecord{4329a75 u0 com.android.mms/.service.SwitchedService}
W/libprocessgroup( 1030): failed to open /acct/uid_10037/pid_4074/cgroup.procs: No such file or directory
D/TARGETVALIDLATION_RECEIVER( 4669): TargetValidationReceiver_ACTION_BOOT_COMPLETETED Received
D/TARGETVALIDLATION_RECEIVER( 4669): updateFlag = new File(TARGET_FLAG_PATH)
D/TARGETVALIDLATION_RECEIVER( 4669): Do Not display result dialog. it is not used Update Tool!!
,I/ActivityManager( 1030): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.LockSettingsReceiver: pid=4686 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1030): Killing 4121:com.android.settings/1000 (adj 15): empty #17
D/CalendarProvider2( 4651): [getOrCreateCalendarAlarmManager]
W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_4121/cgroup.procs: No such file or directory
,I/CalendarProvider2( 4651): Created com.android.providers.calendar.CalendarAlarmManager@3fe12cda(com.android.providers.calendar.CalendarProvider2@363836c9)
I/InsertAccount( 4616): The account info in calendar DB already exists
,I/Process ( 4616): Sending signal. PID: 4616 SIG: 9
I/LockScreenSettings( 4686): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,I/ActivityManager( 1030): Process com.lge.defaultaccount (pid 4616) has died
,I/art     ( 1030): Explicit concurrent mark sweep GC freed 12797(660KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 2.591ms total 148.907ms
,I/LockScreenSettings( 4686): Received Broadcast : android.intent.action.BOOT_COMPLETED
V/LGSC    ( 2209): [104] 401
,I/ActivityManager( 1030): Start proc com.lge.springcleaning for broadcast com.lge.springcleaning/.receiver.BootCompleteReceiver: pid=4708 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/jxcore-log( 4486): getBuffer is called!!!!
I/jxcore-log( 4486): 
,D/BootCompleteReceiver( 4708): hasclipTray = true
,W/ContextImpl( 4708): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.lge.springcleaning.receiver.BootCompleteReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2586 
I/ActivityManager( 1030): Start proc com.lge.springcleaning:AppCleanupService for service com.lge.springcleaning/.service.AppCleanupService: pid=4725 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1030): Killing 4186:com.lge.voicerecorder/u0a42 (adj 15): empty #17
V/SIM_STK ( 1030): Menu title from STK is T-Mobile
V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,W/libprocessgroup( 1030): failed to open /acct/uid_10042/pid_4186/cgroup.procs: No such file or directory
V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,I/ActivityManager( 1030): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=4744 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/AppCleanupService( 4725): registerAlarm
D/AppCleanupService( 4725): noticeInterval = 2592000000
D/AppCleanupService( 4725): notiDateStr = 2015-11-24 08:57:26
D/AppCleanupService( 4725): noticeStart = 2015-11-24 08:57:26
D/AppCleanupService( 4725): noticeStart = 1448351846000
,D/AppUsageDbAdapter( 4725): initPreloadedAppToTheDB() : row count = 90
,I/art     ( 4744): Almond Protected OAT
D/WeatherApplication( 4744): removeAccount
,D/WeatherApplication( 4744): Account.length = 0
E/WeatherApplication( 4744): OPERATOR:OPEN
D/WeatherAncestor( 4744): 2 : onReceive, action: android.intent.action.BOOT_COMPLETED, Time(hour:min:sec) 9:13:18
D/Weather.Utils( 4744): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 4744): 2 : All the weather widget is gone.
,D/UpdateThreadPoolManager( 4744): 2 : This is isUpdating : false
E/ThermalEngine(  339): [GPU_MON] 0 percent. Current Sampling Time is 1 sec
D/WeatherService( 4744): 2 : isServiceAlived():false forecastCache:null
,D/ForecastDataCache( 4744): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 4744): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 4744): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 4744): 2 : set auto-update time : 11/18 12:13
,D/WeatherAncestor( 4744): 2 : onReceive has processed, action: android.intent.action.BOOT_COMPLETED, Time(hour:min:sec) 9:13:18
I/ActivityManager( 1030): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseSIMObserver: pid=4764 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1030): Killing 4231:com.android.managedprovisioning/u0a43 (adj 15): empty #17
W/ActivityManager( 1030): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,W/libprocessgroup( 1030): failed to open /acct/uid_10043/pid_4231/cgroup.procs: No such file or directory
D/SIMObserver( 4764): action:android.intent.action.BOOT_COMPLETED
,D/SIMObserver( 4764): handle ACTION_BOOT_COMPLETED
,D/LgDataFeature( 4764): LgDataFeature() Constructor: none
D/LgDataFeature( 4764): LgDataFeature() Constructor Done, null
,I/ActivityManager( 1030): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.apps.youtube.core.transfer.DownloadService$BootReceiver: pid=4781 uid=10106 gids={50106, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1030): Killing 4283:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10008/pid_4283/cgroup.procs: No such file or directory
,W/ResourcesManager( 4781): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4781): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 4781): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/System  ( 4781): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/app/YouTube/YouTube.apk"],nativeLibraryDirectories=[/system/app/YouTube/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4781): Installed default security provider GmsCore_OpenSSL
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4781): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
D/LgDataFeature( 4781): LgDataFeature() Constructor: none
D/LgDataFeature( 4781): LgDataFeature() Constructor Done, null
,W/CursorWrapperInner( 4323): Cursor finalized without prior close()
,E/YouTube ( 4781): apps.youtube.app.YouTubeApplication.e:196 YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/GAV2    ( 4255): Thread[GAThread,5,main]: No campaign data found.
,D/libc-netbsd(  318): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1030): DNSproblemNotiEnabled is disabled ignore DNS fail CB
E/GoogleConversionPing( 4781): Error sending ping
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4781): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4781): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4781): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
W/ContextImpl( 3249): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.qualcomm.atfwd.AtFwdAutoboot.onReceive:24 android.app.ActivityThread.handleReceiver:2586 
,E/AtFwd AutoBoot( 3249): AtFwd Auto Boot Started Successfully
,W/ContextImpl( 1984): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:2586 
,D/QcrilMsgTunnelAutoboot( 2418): ComponentInfo{com.qualcomm.qcrilmsgtunnel/com.qualcomm.qcrilmsgtunnel.QcrilMsgTunnelService} started successfully
D/SecUISvc( 1984): Thread created.
D/SecUISvc( 1984): Service started flags 0 startId 1
I/ActivityManager( 1030): Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=4858 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,D/SecUISvc.WfdReceiver( 1984): WfdReceiver(), wfdActive=true
D/SecUISvc.WfdReceiver( 1984): Creating service, binding to WFD
D/SecUISvc.WfdReceiver( 1984): service: ComponentInfo{com.qualcomm.wfd.service/com.qualcomm.wfd.service.WfdService}
W/ContextImpl( 1984): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.qualcomm.qti.services.secureui.WfdReceiver.<init>:48 com.qualcomm.qti.services.secureui.SecureUIService.run:95 java.lang.Thread.run:818 
I/ActivityManager( 1030): Killing 4323:com.lge.cloudhub/u0a58 (adj 15): empty #17
,I/ActivityManager( 1030): Start proc com.qualcomm.wfd.service:wfd_service for service com.qualcomm.wfd.service/.WfdService: pid=4878 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
W/libprocessgroup( 1030): failed to open /acct/uid_10058/pid_4323/cgroup.procs: No such file or directory
D/SecUISvc.WfdReceiver( 1984): WfdService binding has started
,D/LgDataFeature( 1984): LgDataFeature() Constructor: none
D/LgDataFeature( 1984): LgDataFeature() Constructor Done, null
,D/WfdService( 4878): onBind()
D/WfdService( 4878): Creating SessionManagerService with context:android.app.Application@1f16c1ce
,D/SessionManagerService( 4878): SessionManagerService ctor
D/SessionManagerService( 4878): Reinitializing callback list
,D/SessionManagerService( 4878): Reinitializing HID callback list
D/SessionManagerService( 4878): WFD_CmdHdlr setup successfully
D/SessionManagerService( 4878): teardown()
D/SessionManagerService( 4878): Teardown session, broadcast intents first
D/SessionManagerService( 4878): broadcastWifiDisplayAudioIntent() - flag: false
E/SessionManagerService( 4878): Calling Audio System Proxy disable
V/AudioPolicyManager(  324): setDeviceConnectionState() device: 2000000, state 0, address 
W/AudioPolicyManager(  324): setDeviceConnectionState() device not connected: 2000000
D/SessionManagerService( 4878): broadcastWifiDisplayVideoEnabled() - flag: false
D/SessionManagerService( 4878): Broadcasting WFD video intent: Intent { act=org.codeaurora.intent.action.WIFI_DISPLAY_VIDEO (has extras) }
W/ContextImpl( 4878): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.qualcomm.wfd.service.SessionManagerService.broadcastWifiDisplayVideoEnabled:1221 com.qualcomm.wfd.service.SessionManagerService.teardown:1053 com.qualcomm.wfd.service.SessionManagerService.<init>:159 
,D/SessionManagerService( 4878): No session in progress
D/SessionManagerService( 4878): Cleanup any existing sessions. ret: 0
D/WFDNative( 4878): try to load libwfdrtsp.so
D/WFDNative( 4878): libwfdrtsp.so loaded.
D/WFDNative( 4878): try to load libwfdnative.so
,W/linker  ( 4878): libaudioeffectsole.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
V/[BNRBootReceiver]( 4858): boot receiver action = android.intent.action.BOOT_COMPLETED
V/[BNRBootReceiver]( 4858): set property sys.lge.bnrd = 1
V/[BNRBootReceiver]( 4858): End of BootComplted IF
V/[BNRBootReceiver]( 4858): Boot Receiver Return
,D/CalendarReceiver( 4651): [onReceive] intent = Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.android.providers.calendar/.CalendarReceiver (has extras) }
D/CalendarReceiver( 4651): [onReceive] WakeLock new : CalendarReceiver_Provider, ReferenceCounted = true
D/CalendarReceiver( 4651): [onReceive] WakeLock acquire : CalendarReceiver_Provider
V/[BNRBootCompletedThread]( 4858): run
D/CalendarReceiver( 4651): [onReceive] android.intent.action.BOOT_COMPLETED
,D/CalendarProvider2( 4651): Scheduling check of next Alarm
D/CalendarProvider2( 4651): SCHEDULE_ALARM_REMOVE
D/CalendarReceiver( 4651): [onReceive] WakeLock release : CalendarReceiver_Provider
,I/ActivityManager( 1030): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4904 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
,V/[BNRBootCompletedThread]( 4858): End of BNRProcess
V/[BNRBootCompletedThread]( 4858): End of BNRViaWifiProcess
V/[BNRBootCompletedThread]( 4858): End of SpriteProcess
V/[BNRBootCompletedThread]( 4858): exit
,E/WFDNative_CPP( 4878): JNI_OnLoad called
E/WFDNative_CPP( 4878): Unable to find field 
E/WFDNative_CPP( 4878): Unable to find field 
E/UIBCManager( 4878): HID payload is null, ignore callback
E/UIBCManager( 4878): HIDCListener is null, ignore callback
D/WFDNative( 4878): libwfdnative.so loaded.
D/WFDNative( 4878): eventCallback triggered
D/WFDNative( 4878): No event info, ignore.
,D/SecUISvc.WfdReceiver( 1984): Connection object created
,D/SessionManagerService( 4878): Received intent: #Intent;action=android.intent.action.HDMI_PLUGGED;launchFlags=0x44000010;B.state=false;end
D/SessionManagerService( 4878): init()
E/SessionManagerService( 4878): listener != null
E/SessionManagerService( 4878): WfdDevice arg can not be null
,I/ActivityManager( 1030): Killing 4354:com.google.android.configupdater/u0a59 (adj 15): empty #17
W/ResourcesManager( 4904): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/CalendarApplication( 4904): CalendarApplication.onCreate()
,I/[SystemUI]LGPowerUI( 1461): onReceive = com.lge.android.intent.action.BATTERYEX
W/libprocessgroup( 1030): failed to open /acct/uid_10059/pid_4354/cgroup.procs: No such file or directory
I/[SystemUI]LGPowerUI( 1461): On Skip Timer : true
W/ActivityManager( 1030): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,I/GAV2    ( 4401): Thread[GAThread,5,main]: No campaign data found.
D/PreferenceKeysParser( 4904): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 4904): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@1f1178ef, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@5237ffc, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@3a047685, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@3fe12cda, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@1926b50b, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@12269fe8, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@149af601, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@2b53ca6, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@2e0996e7, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@23b9d294, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@6bff13d, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@2d687d32, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@324eba83, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@2cab8400, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@1f3f6439, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@1b9d3a7e, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@25387bdf, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@3c44e02c, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@33a90af5, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@2ece808a, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@dd2f6fb, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@2b35d318, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@28cc6171, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@331c1b56, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@dd007d7, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@2b4108c4, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@6f4a3ad, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@4d696e2, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@6234a73, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@25a7ed30, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@15e4cda9, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@2cb3f2e, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@295e1acf, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@1456ac5c, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@3c939b65, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@1950203a, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@17cb94eb, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@1d03248, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@20a788e1, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@32100606, lg_preferences_alerts_vibratetype=com.android.cal,endar.adaptation.PreferenceKey$KeyData@214c94c7, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@1bda2af4
D/GeneralPreferenceUtils( 4904): [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
D/Config  ( 4904): [init]
I/Config  ( 4904): LGCalendar ver.4.40.16
I/Config  ( 4904): start check model
I/Config  ( 4904): start check native_ca
I/Config  ( 4904): Config Operator=OPEN, Country=EU
D/Config  ( 4904): [setDefaultValuesToPref]
D/Config  ( 4904): [parseProfiles]
D/ProfilesParser( 4904): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 4904): [debug_displayParseInfos] profile.operator = null
,D/Config  ( 4904): [updateProfiletoCountryInfo]
D/GeneralPreference( 4904): [checkAndMigrateOldPreference]
D/AlertReceiver( 4904): onReceive: a=android.intent.action.BOOT_COMPLETED Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.android.calendar/.alerts.AlertReceiver (has extras) }
I/InitNotificationRingtoneService( 4904): Start InitializeAlertRingtoneService.onHandleIntent
,I/AlertUtils( 4904): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
I/ActivityManager( 1030): Start proc com.nuance.voicemate for broadcast com.nuance.voicemate/com.nuance.androidcore.manifest.receivers.UploadServiceBootStart: pid=4930 uid=10117 gids={50117, 9997, 1028, 1015, 3003, 3001, 3002} abi=armeabi
,I/AlertUtils( 4904): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 4904): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
I/AlertUtils( 4904): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 4904): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,I/AlertUtils( 4904): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 4904): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
,I/AlertUtils( 4904): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 4904): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 4904): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,I/AlertUtils( 4904): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 4904): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
I/AlertUtils( 4904): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,I/AlertUtils( 4904): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 4904): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 4904): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
,I/AlertUtils( 4904): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 4904): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
I/AlertUtils( 4904): set default noti to content://media/internal/audio/media/41
I/InitNotificationRingtoneService( 4904): End InitializeAlertRingtoneService.onHandleIntent
,W/HolidayIntentService( 4904): onHandleIntent
D/HolidayDataLoader( 4904): readJsonAsset : holiday.json
D/AlertService( 4904): 0 Action = android.intent.action.BOOT_COMPLETED
,D/AlertService( 4904): [Widget]com.android.calendar.widget.CalendarAppWidgetProvider enabled
D/Feature ( 4904): MemoryLevel - 5:NOT_DEF:Not UI4.2 LOS
D/AlertService( 4904): [Widget]com.android.calendar.widget.MonthWidgetProvider enabled
D/AlertService( 4904): [Widget]com.android.calendar.widget.WeekWidgetProvider enabled
D/AlertService( 4904): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 4904): No events found starting within 1 week.
,E/HolidayIntentService( 4904): onHandleIntent:holiday data empty
,D/LgDataFeature( 4930): LgDataFeature() Constructor: none
D/LgDataFeature( 4930): LgDataFeature() Constructor Done, null
,I/LicenseContentProvider( 4764): start selecting data
,D/EULA::SimManager( 4764): SimManager getInstance.
I/EULA::SimManager( 4764): LGMSimTelephonyManager will be used!
I/EULA::SimManager( 4764): sSimInstance : com.lge.telephony.msim.LGMSimTelephonyManager@1f16c1ce
I/EULA::SimManager( 4764): sIsMultiSimEnabled : false
I/EULA::SimManager( 4764): sSIMCount : 1
I/EULA::SimManager( 4764): LGMSimTelephonyManager will be used!
I/EULA::SimManager( 4764): sSimInstance : com.lge.telephony.msim.LGMSimTelephonyManager@1f16c1ce
I/EULA::SimManager( 4764): sIsMultiSimEnabled : false
I/EULA::SimManager( 4764): sSIMCount : 1
D/SIMObserver( 4764): simInfo1
I/ActivityManager( 1030): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4962 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1030): Killing 4384:com.lge.drmservice/u0a62 (adj 15): empty #17
I/art     (  355): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 392us total 22.837ms
,I/art     (  355): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 341us total 15.735ms
,I/art     (  355): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 288us total 15.742ms
,W/libprocessgroup( 1030): failed to open /acct/uid_10062/pid_4384/cgroup.procs: No such file or directory
,I/CalendarProvider2( 4651): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 4651): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager( 1030): Killing 4401:com.google.android.gm/u0a64 (adj 15): empty #17
W/libprocessgroup( 1030): failed to open /acct/uid_10064/pid_4401/cgroup.procs: No such file or directory
,D/Finsky  ( 4962): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/LgDataFeature( 4962): LgDataFeature() Constructor: none
D/LgDataFeature( 4962): LgDataFeature() Constructor Done, null
,D/Finsky  ( 4962): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager( 1030): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5004 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/Settings( 4962): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 4962): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 5004): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5004): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Volley  ( 4962): [556] DiskBasedCache.clear: Cache cleared.
D/Volley  ( 4962): [563] DiskBasedCache.clear: Cache cleared.
,I/ActivityManager( 1030): Killing 2630:com.lge.formmanager/u0a26 (adj 15): empty #17
I/MultiDex( 5004): VM with version 2.1.0 has multidex support
I/MultiDex( 5004): install
I/MultiDex( 5004): VM has multidex support, MultiDex support library is disabled.
W/libprocessgroup( 1030): failed to open /acct/uid_10026/pid_2630/cgroup.procs: No such file or directory
,V/DownloadManager( 3303): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3303): created cursor android.database.sqlite.SQLiteCursor@3c939b65 on behalf of 4962
V/GLSUser ( 2136): [LoginAccountsChangedWakefulBroadcastReceiver] recieved broadcast intent with action: android.intent.action.BOOT_COMPLETED
,D/Finsky  ( 4962): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 4962): [1] 2.run: Finished loading 1 libraries.
D/Finsky  ( 4962): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,V/JNIHelp ( 5004): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
V/GmsCoreStatsServiceLauncher( 2326): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
D/Finsky  ( 4962): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/PersistentNotificationBroadcastReceiver( 2136): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,W/ActivityThread( 5004): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5004): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3d83924: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5004): Installed default security provider GmsCore_OpenSSL
,W/InstanceID/Rpc( 2326): Found 10005
,E/ThermalEngine(  339): [GPU_MON] 0 percent. Current Sampling Time is 1 sec
I/ActivityManager( 1030): Killing 4467:com.lge.gnss.airtest/u0a65 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10065/pid_4467/cgroup.procs: No such file or directory
,D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1030): disable(): mBluetooth = null mBinding = false
W/ActivityManager( 1030): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
D/BluetoothManagerService( 1030): Message: 2
V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{24db6831 type 0 when 1447834402956 com.google.android.gms} when 1447834402956
D/WifiService( 1030): New client listening to asynchronous messages
D/FileApkUtils( 2326): Spent 53ms computing apk sha1.
D/WifiServiceImplEx( 1030): setWifiEnabled: false pid=4486, uid=10318, package= com.example.hello, App Lable : HelloWorld
D/FileApkUtils( 2326): Module already staged or being staged:chimera-modules/MapsModule.apk
D/WifiService( 1030): setWifiEnabled: false pid=4486, uid=10318
E/WifiService( 1030): Invoking mWifiStateMachine.setWifiEnabled
I/art     ( 2326): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-d27787c4e483aadd035a354447c9e84728eb2ab4@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d27787c4e483aadd035a354447c9e84728eb2ab4/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
,I/jxcore-log( 4486): ****TEST TOOK:  5102  ms ****
I/jxcore-log( 4486): 
I/jxcore-log( 4486): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4486): 
D/DexOptUtils( 2326): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d27787c4e483aadd035a354447c9e84728eb2ab4/MapsModule.apk is already optimized. Bailing.
,V/Finsky  ( 4962): [1] GearheadStateMonitor.onReady: sIsProjecting:false
D/FileApkUtils( 2326): Keeping up-to-date module: module-d27787c4e483aadd035a354447c9e84728eb2ab4
,I/art     ( 1030): Explicit concurrent mark sweep GC freed 19872(926KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 2.055ms total 88.369ms
,D/GmsModuleFndr( 2326): Beginning GMS chimera module scan
,D/GmsModuleFndr( 2326): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping
D/ChimeraCfgMgr( 2326): Beginning module configuration check
,I/iu.UploadsManager( 2326): End new media; added: 0, uploading: 0, time: 138 ms
D/ChimeraCfgMgr( 2326): Module APKs unchanged, check complete
D/GCM     ( 2326): COMPAT: Multi user ser=0 current=0
,D/GCM     ( 2136): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,I/CheckinService( 2326): Disabling old GoogleServicesFramework version
,D/ChimeraCfgMgr( 2326): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/GCoreUlr( 2326): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,I/GCoreUlr( 1836): DispatchingService.onCreate()
,D/SystemUpdateService( 2326): onCreate
D/SystemUpdateService( 2326): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,D/AndroidRuntime( 5060): 
D/AndroidRuntime( 5060): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5060): CheckJNI is OFF
I/ConfigService( 2136): onCreate
,I/ConfigFetchService( 2326): onStartCommand Intent { cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
V/AuthZen ( 2326): Handling intent: android.intent.action.BOOT_COMPLETED
,D/ChimeraCfgMgr( 2326): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/AuthZenEventHandler( 2326): Handling event: android.intent.action.BOOT_COMPLETED
,D/LgDataFeature( 2326): LgDataFeature() Constructor: none
D/LgDataFeature( 2326): LgDataFeature() Constructor Done, null
,I/ActivityManager( 1030): Start proc com.lge.qmemoplus for broadcast com.lge.qmemoplus/.ui.editor.reminder.ReminderMaker: pid=5102 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,V/GLSActivity( 2136): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ConfigFetchService( 2326): service connected
,I/Kids    ( 2326): [KidAccountFixer] No network connection
D/ConfigFetchService( 2326): ConfigApi connection successful.
I/SystemUpdateService( 2326): cancelUpdate (empty URL)
I/SystemUpdateService( 2326): active receiver: disabled
I/CheckinService( 2326): Checking schedule, now: 1447834403417 next: 1447886819216
I/CheckinService( 2326): active receiver: disabled
,I/GCoreUlr( 1836): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,D/BluetoothManagerService( 1030): Message: 20
D/BluetoothManagerService( 1030): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2fb6d8b:true
D/AndroidRuntime( 5060): Calling main entry com.android.commands.pm.Pm
,I/GLSActivity( 2136): [ac] getting account id
W/BaseAppContext( 2326): Using Auth Proxy for data requests.
I/GLSUser ( 2136): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
I/ActivityManager( 1030): Force stopping com.example.hello appid=10318 user=-1: uninstall pkg
I/ActivityManager( 1030): Killing 4486:com.example.hello/u0a318 (adj 0): stop com.example.hello
W/ResourcesManager( 5102): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
,W/ResourcesManager( 5102): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/WindowState( 1030): WIN DEATH: Window{bf4589c u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService( 1030): Client connection lost with reason: 4
D/InputDispatcher( 1030): Window went away: Window{bf4589c u0 com.example.hello/com.example.hello.MainActivity}
W/PackageSettings( 1030): Skipping PackageSetting{2f2f3060 com.test.thalitest/10311} due to missing metadata
,W/ActivityManager( 1030): Force removing ActivityRecord{2a7fbc4f u0 com.example.hello/.MainActivity t2}: app died, no saved state
,D/SplitWindowManager( 1030): removeStackAndNeedHomeResume ActivityStack{28e197b2 stackId=1, 0 tasks}
,E/GBMv2   (  351): DFP En is all cleared set to be enabled
W/ActivityManager( 1030): Spurious death for ProcessRecord{29f20303 4486:com.example.hello/u0a318}, curProc for 4486: null
D/SplitWindowPolicy( 1963): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1963): topRunningActivity=ActivityInfo{39f7fe23 co.....MainActivity}, taskId=2, activityType=0, bIsSplit=false
,E/App     ( 5102): [App][onCreate()] 4.40.21
I/ActivityManager( 1030): Force stopping com.example.hello appid=10318 user=0: pkg removed
I/[LGHome]EVENT( 2083): [Launcher.java:5338:onStart()]onStart
,D/SplitWindowPolicy( 1963): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1963): topRunningActivity=ActivityInfo{30180f20 co.....Launcher}, taskId=1, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2083): [Launcher.java:903:onResume()]onResume
D/KeyguardModel( 1461): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
D/LIA_MrGDBLogger_PackageInfoDetector( 2697): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.example.hello
D/LIA_Service_RemotePackageHandler( 2032): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.example.hello
,W/GeofencerStateMachine( 1836): Ignoring removeGeofence because network location is disabled.
I/InputReader( 1030): Reconfiguring input devices.  changes=0x00000010
,W/System.err( 4211): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
W/System.err( 4211): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4211): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4211): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4211): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4211): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4211): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4211): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4211): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4211): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4211): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4211): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/GLSUser ( 2326): [ChannelManager] Attempting to channel bind connection HttpClient.
,D/PowerManagerServiceEx( 1030): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=30000 (24953 ms ago)
D/SystemUpdateService( 2326): onDestroy
I/[LGHome]GBoardWebView( 2083): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,D/KeyguardModel( 1461): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1461): createShortcutInfo...
D/ActionManagerService( 1922): notifyUserLog: 1000003
I/[LGHome]LGActivityUtil( 2083): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 2083): [Launcher.java:1056:onResume()]onResume end
I/[SystemUI]QSlideListController( 1461): onReceive = android.intent.action.PACKAGE_REMOVED
,D/LIA_Informant_ActionManagerMessageHandler( 2697): handleMessage: what(1000) actionID(0x1000003)
D/WallpaperManager( 2083): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
D/KeyguardModel( 1461): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1461): createShortcutInfo...
W/ResourcesManager( 1461): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1461): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1461): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1461): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/art     ( 1836): Explicit concurrent mark sweep GC freed 33734(2017KB) AllocSpace objects, 4(64KB) LOS objects, 50% free, 30MB/62MB, paused 2.908ms total 74.383ms
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1461): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.example.hello
D/KeyguardModel( 1461): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
W/ResourceType( 1461): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1461): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1461): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1461): createShortcutInfo...
I/GLSUser ( 2326): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,W/ResourcesManager( 1461): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1461): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1461): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1461): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
I/[LGHome]EVENT( 2083): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/[LGHome]GBoardWebView( 2083): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,D/administrator( 1030): Handling package changes for user 0
,D/KeyguardModel( 1461): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1461): createShortcutInfo...
W/ResourcesManager( 1461): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1461): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1461): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1461): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,D/SplitUIManager( 1888): split_name #11 / not available #0
D/SplitUIService( 1888): removed split : 
I/art     ( 2136): Explicit concurrent mark sweep GC freed 6041(382KB) AllocSpace objects, 6(96KB) LOS objects, 51% free, 30MB/62MB, paused 1.691ms total 70.587ms
,W/ResourceType( 1461): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1461): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1461): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1461): createShortcutInfo...
,D/KeyguardModel( 1461): handleShortcutListChanged...
I/AuthZen ( 2326): Fetching signing key...
D/KeyguardModel( 1461): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,D/KeyguardModel( 1461): createShortcutInfo...
D/KeyguardModel( 1461): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1461): createShortcutInfo...
I/AuthZen ( 2326): Signing key fetched successfully!
,W/ResourceType( 1461): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1461): Failure retrieving resources for com.android.mms: Resource ID #0x0
,D/KeyguardModel( 1461): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1461): createShortcutInfo...
W/ResourceType( 1461): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1461): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
W/BaseAppContext( 2326): Using Auth Proxy for data requests.
D/KeyguardModel( 1461): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1461): createShortcutInfo...
I/AuthZen ( 2326): Starting Enrollment...
V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,W/ResourceType( 1461): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1461): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
I/NotificationService( 1030): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1030): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService( 1030): Receieved: android.intent.action.PACKAGE_REMOVED
D/AuthZen ( 2326): getting auth token. Attempt 0
D/SplitUIManager( 1888): split_name #11 / not available #0
I/SplitUIService( 1888): split app #11
,D/TaskPersister( 1030): removeObsoleteFile: deleting file=2_task.xml
D/KeyguardModel( 1461): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1461): createShortcutInfo...
D/KeyguardModel( 1461): handleShortcutListChanged...
,I/GLSUser ( 2136): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cryptauth
,I/GLSUser ( 2136): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cryptauth without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2136): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2136): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2136): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Timeline( 2083): Timeline: Activity_idle id: android.os.BinderProxy@16bcc74a time:55268
,I/SystemUI[Framework]( 1030): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1030): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1030): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1030): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1030): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3d2b6ef7,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1030): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1461): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1461): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1461):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1461): , Keyguard show=false, IME shown=false, Panel expanded=false
,E/AuthZen ( 2326): Error getting auth token
E/AuthZen ( 2326): com.google.android.gms.auth.ad: BadAuthentication
E/AuthZen ( 2326): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/AuthZen ( 2326): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/AuthZen ( 2326): 	at com.google.android.gms.auth.p.a(SourceFile:318)
E/AuthZen ( 2326): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:381)
E/AuthZen ( 2326): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:132)
E/AuthZen ( 2326): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
E/AuthZen ( 2326): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
E/AuthZen ( 2326): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
E/AuthZen ( 2326): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
E/AuthZen ( 2326): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
E/AuthZen ( 2326): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
E/AuthZen ( 2326): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
E/AuthZen ( 2326): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/AuthZen ( 2326): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AuthZen ( 2326): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AuthZen ( 2326): 	at android.os.Looper.loop(Looper.java:135)
E/AuthZen ( 2326): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/AuthZen ( 2326): Failed to do enrollment for account: thalitester@gmail.com
E/AuthZen ( 2326): com.google.android.gms.auth.authzen.b.b: Failed to get a token for authzen enrollment
E/AuthZen ( 2326): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:139)
E/AuthZen ( 2326): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
E/AuthZen ( 2326): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
E/AuthZen ( 2326): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
E/AuthZen ( 2326): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
E/AuthZen ( 2326): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
E/AuthZen ( 2326): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
E/AuthZen ( 2326): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
E/AuthZen ( 2326): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/AuthZen ( 2326): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AuthZen ( 2326): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AuthZen ( 2326): 	at android.os.Looper.loop(Looper.java:135)
E/AuthZen ( 2326): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/art     ( 2326): Explicit concurrent mark sweep GC freed 18961(1491KB) AllocSpace objects, 26(416KB) LOS objects, 50% free, 30MB/62MB, paused 862us total 70.783ms
,I/GCoreUlr( 1836): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=10, mName='AuthError'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/art     ( 1030): Explicit concurrent mark sweep GC freed 22160(1487KB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 44MB/66MB, paused 2.743ms total 503.526ms
,D/a       ( 2326): Opening database auth.proximity.permit_store...
,I/GCoreUlr( 1836): Unbound from all location providers
D/AuthZenTransactionCache( 2326): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 2326): Clearing transaction cache
I/GCoreUlr( 1836): DispatchingService.onDestroy()
,I/GCoreUlr( 1836): Unbound from all location providers
D/AccountManager( 5102): setSyncFrequency
D/AndroidRuntime( 5060): Shutting down VM
,W/ResourcesManager( 1030): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ContextImpl( 5102): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.lge.qmemoplus.ui.editor.reminder.ReminderMaker.onReceive:14 android.app.ActivityThread.handleReceiver:2586 
W/ResourceType( 1030): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
D/ReminderService( 5102): [onHandleIntent] action : com.lge.qmemoplus.action.SET_REMINDERS
D/LocationReminderManager( 5102): [connect] Request location client connection.
,W/ContextImpl( 5102): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.google.android.gms.internal.he.a:-1 com.google.android.gms.internal.hc.connect:-1 com.google.android.gms.location.LocationClient.connect:-1 
,I/ActivityManager( 1030): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=5142 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/Timeline( 1030): Timeline: Activity_windows_visible id: ActivityRecord{1dd67f9e u0 com.lge.launcher2/.Launcher t1} time:55554
I/[LGHome]EVENT( 2083): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,D/LocationReminderManager( 5102): location cilent is connected.
D/LocationReminderManager( 5102): [removeAllReminders]
,W/GeofencerStateMachine( 1836): Ignoring removeGeofence because network location is disabled.
W/GCoreFlp( 1836): No location to return for getLastLocation()
D/LocationReminderManager( 5102): [removeAllReminders] statusCode : 1000
D/LocationReminderManager( 5102): [removeAllReminders] Failed to remove reminder
I/ActivityManager( 1030): Killing 4508:com.google.android.talk/u0a72 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10072/pid_4508/cgroup.procs: No such file or directory
W/ResourcesManager( 5142): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 5142): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 5142): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 5142): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
,I/QRemote ( 5142): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 5142): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 5142): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 5142): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 5142): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
V/QRemote ( 5142): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 5142): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:4494
D/QRemote ( 5142): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,D/QRemote ( 5142): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
V/QRemote ( 5142): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 5142): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 5142): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 5142): LgDataFeature() Constructor: none
,D/LgDataFeature( 5142): LgDataFeature() Constructor Done, null
V/SoundPool( 5142): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 5142): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 5142): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 5142): doLoad: loading sample sampleID=1
I/QRemote ( 5142): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/SoundPool( 5142): Start decode
V/MediaPlayer[Native]( 5142): decode(31, 10857164, 17813)
V/MediaPlayerService(  324): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  324): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  324): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  324): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  324): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  324): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  324): player type = 3
V/AwesomePlayer(  324): AwesomePlayer create()
V/AwesomePlayer(  324): reset_l() 
V/AwesomePlayer(  324): cancelPlayerEvents
V/AwesomePlayer(  324): setAudioSink() 
V/AwesomePlayer(  324): reset_l() 
V/AudioCache(  324): notify(0xb1163b00, 8, 0, 0)
V/AudioCache(  324): ignored
V/AwesomePlayer(  324): cancelPlayerEvents
D/Utils   (  324): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  324): setDataSource_l dataSource
V/LGParserOSAL(  324): SniffLGParser start
V/LGParserOSAL(  324): MainType:5, SubType=0
V/LGParserOSAL(  324): #### check Mime : application/ogg
V/LGParserOSAL(  324): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  324): Use LGExtractor :application/ogg 
,E/GBMv2   (  351): DFP En is all cleared set to be enabled
E/GBMv2   (  351): Set value is all cleared set the max
I/GBMv2   (  351): DFP Enabled. Ignore VFP set
,I/ActivityManager( 1030): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=5166 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/QRemote ( 5142): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
E/QRemote ( 5142): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 5142): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,V/LGParserOSAL(  324): supported mime: application/ogg
,V/AwesomePlayer(  324): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  324): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  324): mBitrate = -1 bits/sec
V/AwesomePlayer(  324): AudioTrack Setting
V/AwesomePlayer(  324): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  324): setAudioSource() 
V/MediaPlayerService(  324): prepare
V/AwesomePlayer(  324): prepareAsync_l() 
V/MediaPlayerService(  324): wait for prepare
V/AwesomePlayer(  324): onPrepareAsyncEvent() 
V/AwesomePlayer(  324): initAudioDecoder() 
W/Utils   (  324): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  324): isOffloadSupported()
V/AudioPolicyManager(  324): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  324): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  324): isAudioPlaybackHookOn() false
V/AwesomePlayer(  324): getUseOffload() = 0 
V/OMXCodec(  324): OMXCodec::Create
V/OMXCodec(  324): findMatchingCodecs()
V/OMXCodec(  324): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  324): matchingCodecs.size()=1
V/OMXCodec(  324): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
V/LGMDMManager( 5142): Create singleton instance
D/OMXCodec(  324): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  324): LG Codec Adapter start
V/OMXCodec(  324): OMXCodec Createtor
V/OMXCodec(  324): setComponentRole
V/OMXCodec(  324): configureCodec protected=0
V/LGCodecAdapter(  324): called getLGCodecSpecificData
V/LGCodecOSAL(  324): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  324): Called LGconfigureCodecMETA
V/LGCodecOSAL(  324): Called LGconfigureCodecMSG
V/LGCodecOSAL(  324): Not support LGCodec
V/OMXCodec(  324): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  324): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  324): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  324): Could not offload audio decode, try pcm offload
W/Utils   (  324): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  324): isOffloadSupported()
V/AudioPolicyManager(  324): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  324): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  324): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  324): init()
V/OMXCodec(  324): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  324): allocateBuffers
V/OMXCodec(  324): allocateBuffersOnPort portIndex=0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocated buffer 0xb1434380 on input port
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocated buffer 0xb14344c0 on input port
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocated buffer 0xb1434510 on input port
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocated buffer 0xb1434560 on input port
V/OMXCodec(  324): allocateBuffersOnPort portIndex=1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocated buffer 0xb14345b0 on output port
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocated buffer 0xb1434650 on output port
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocated buffer 0xb14346a0 on output port
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocated buffe,r 0xb1521100 on output port
V/OMXCodec(  324): init() mAsyncCompletion wait!!! 
V/OMXCodec(  324): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  324): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  324): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  324): init() mAsyncCompletion wait!!! 
V/OMXCodec(  324): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  324): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  324): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  324): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  324): finishAsyncPrepare_l() 
V/AudioCache(  324): notify(0xb1163b00, 5, 0, 0)
V/AudioCache(  324): ignored
V/AudioCache(  324): notify(0xb1163b00, 1, 0, 0)
V/AudioCache(  324): prepared
V/AudioCache(  324): wait - success
V/MediaPlayerService(  324): start
V/AwesomePlayer(  324): play_l() 
V/AwesomePlayer(  324): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  324): createAudioPlayer_l
V/AwesomePlayer(  324): seekAudioIfNecessary_l() 
V/AwesomePlayer(  324): startAudioPlayer_l() 
D/AudioPlayer(  324): start of Playback, useOffload 0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  324): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  324): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  324): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  324): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  324): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973975984
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976144
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976224
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974945536
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  324): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  324): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  324): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  324): allocateBuffersOnPort portIndex=1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocated buffer 0xb14346a0 on output port
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocated buffer 0xb1434650 on output port
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocated buffer 0xb14345b0 on output port
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocated buffer 0xb1521240 on output port
V/OMXCodec(  324): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  324): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  324): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  324): notify(0xb1163b00, 6, 0, 0)
V/AudioCache(  324): ignored
V/MediaPlayerService(  324): wait for playback complete
V/AudioCache(  324): write(0xb57df000, 4096)
V/AudioCache(  324): memcpy(0xae804000, 0xb57df000, 4096)
V/AudioCache(  324): write(0xb57df000, 4096)
V/AudioCache(  324): memcpy(0xae805000, 0xb57df000, 4096)
V/AudioCache(  324): write(0xb57df000, 4096)
V/AudioCache(  324): memcpy(0xae806000, 0xb57df000, 4096)
V/AudioCache(  324): write(0xb57df000, 4096)
V/AudioCache(  324): memcpy(0xae807000, 0xb57df000, 4096)
V/AudioCache(  324): write(0xb57df000, 4096)
V/AudioCache(  324): memcpy(0xae808000, 0xb57df000, 4096)
V/AudioCache(  324): write(0xb57df000, 4096)
V/AudioCache(  324): memcpy(0xae809000, 0xb57df000, 4096)
V/AudioCache(  324): write(0xb57df000, 4096)
V/AudioCache(  324): memcpy(0xae80a000, 0xb57df000, 4096)
V/AudioCache(  324): write(0xb57df000, 4096)
V/AudioCache(  324): memcpy(0xae80b000, 0xb57df000, 4096)
V/AudioCache(  324): write(0xb57df000, 4096)
V/AudioCache(  324): memcpy(0xae80c000, 0xb57df000, 4096)
V/AudioCache(  324): write(0xb57df000, 4096)
V/AudioCache(  324): memcpy(0xae80d000, 0xb57df000, 4096)
V/AudioCache(  324): write(0xb57df000, 4096)
V/AudioCache(  324): memcpy(0xae80e000, 0xb57df000, 4096)
V/AudioCache(  324): write(0xb57df000, 4096)
V/AudioCache(  324): memcpy(0xae80f000, 0xb57df000, 4096)
V/AudioCache(  324): write(0xb57df000, 4096)
V/AudioCache(  324): memcpy(0xae810000, 0xb57df000, 4096)
V/AudioCache(  324): write(0xb57df000, 4096)
V/AudioCache(  324): memcpy(0xae811000, 0xb57df000, 4096)
V/AudioCache(  324): write(0xb57df000, 4096)
V/AudioCache(  324): memcpy(0xae812000, 0xb57df000, 4096)
V/AudioCache(  324): write(0xb57df000, 4096)
V/AudioCache(  324): memcpy(0xae813000, 0xb57df000, 4096)
V/AudioCache(  324): write(0xb57df000, 4096)
V/AudioCache(  324): memcpy(0xae814000, 0xb57df000, 4096)
V/AudioCache(  324): write(0xb57df000, 4096)
V/AudioCache(  324): memcpy(0xae815000, 0xb57df000, 4096)
V/AudioCache(  324): write(0xb57df000, 4096)
V/AudioCache(  324): memcpy(0xae816000, 0xb57df000, 4096)
V/AudioCache(  324): write(0xb57df000, 4096)
V/AudioCache(  324): memcpy(0xae817000, 0xb57df000, 4096)
V/AudioCache(  324): write(0xb57df000, 4096)
V/AudioCache(  324): memcpy(0xae818000, 0xb57df000, 4096)
V/AudioCache(  324): write(0xb57df000, 4096)
V/AudioCache(  324): memcpy(0xae819000, 0xb57df000, 4096)
V/AudioCache(  324): write(0xb57df000, 4096)
V/AudioCache(  324): memcpy(0xae81a000, 0xb57df000, 4096)
V/AudioCache(  324): write(0xb57df000, 4096)
V/AudioCache(  324): memcpy(0xae81b000, 0xb57df000, 4096)
V/AudioCache(  324): write(0xb57df000, 4096)
V/AudioCache(  324): memcpy(0xae81c000, 0xb57df000, 4096)
V/AudioCache(  324): write(0xb57df000, 4096)
V/AudioCache(  324): memcpy(0xae81d000, 0xb57df000, 4096)
V/AudioCache(  324): write(0xb57df000, 4096)
V/AudioCache(  324): memcpy(0xae81e000, 0xb57df000, 4096)
V/AudioCache(  324): write(0xb57df000, 4096)
V/AudioCache(  324): memcpy(0xae81f000, 0xb57df000, 4096)
V/AudioCache(  324): write(0xb57df000, 4096)
V/AudioCache(  324): memcpy(0xae820000, 0xb57df000, 4096)
V/AudioCache(  324): write(0xb57df000, 4096)
V/AudioCache(  324): memcpy(0xae821000, 0xb57df000, 4096)
V/AudioCache(  324): write(0xb57df000, 4096)
V/AudioCache(  324): memcpy(0xae822000, 0xb57df000, 4096)
V/AudioCache(  324): write(0xb57df000, 4096)
V/AudioCache(  324): memcpy(0xae823000, 0xb57df000, 4096)
V/AudioCache(  324): write(0xb57df000, 4096)
V/AudioCache(  324): memcpy(0xae824000, 0xb57df000, 4096)
V/AudioCache(  324): write(0xb57df000, 4096)
V/AudioCache(  324): memcpy(0xae825000, 0xb57df000, 4096)
V/AudioCache(  324): write(0xb57df000, 4096)
V/AudioCache(  324): memcpy(0xae826000, 0xb57df000, 4096)
,V/AudioCache(  324): write(0xb57df000, 4096)
V/AudioCache(  324): memcpy(0xae827000, 0xb57df000, 4096)
V/AudioCache(  324): write(0xb57df000, 4096)
V/AudioCache(  324): memcpy(0xae828000, 0xb57df000, 4096)
V/AudioCache(  324): write(0xb57df000, 4096)
V/AudioCache(  324): memcpy(0xae829000, 0xb57df000, 4096)
V/AudioCache(  324): write(0xb57df000, 4096)
V/AudioCache(  324): memcpy(0xae82a000, 0xb57df000, 4096)
V/AudioCache(  324): write(0xb57df000, 4096)
V/AudioCache(  324): memcpy(0xae82b000, 0xb57df000, 4096)
V/AudioCache(  324): write(0xb57df000, 4096)
V/AudioCache(  324): memcpy(0xae82c000, 0xb57df000, 4096)
V/AudioCache(  324): write(0xb57df000, 4096)
V/AudioCache(  324): memcpy(0xae82d000, 0xb57df000, 4096)
V/AudioCache(  324): write(0xb57df000, 4096)
V/AudioCache(  324): memcpy(0xae82e000, 0xb57df000, 4096)
V/AudioCache(  324): write(0xb57df000, 4096)
V/AudioCache(  324): memcpy(0xae82f000, 0xb57df000, 4096)
V/AudioCache(  324): write(0xb57df000, 4096)
V/AudioCache(  324): memcpy(0xae830000, 0xb57df000, 4096)
V/AudioCache(  324): write(0xb57df000, 4096)
V/AudioCache(  324): memcpy(0xae831000, 0xb57df000, 4096)
V/AudioCache(  324): write(0xb57df000, 4096)
V/AudioCache(  324): memcpy(0xae832000, 0xb57df000, 4096)
V/AudioCache(  324): write(0xb57df000, 4096)
V/AudioCache(  324): memcpy(0xae833000, 0xb57df000, 4096)
D/QRemote ( 5142): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
V/AudioCache(  324): write(0xb57df000, 4096)
V/AudioCache(  324): memcpy(0xae834000, 0xb57df000, 4096)
V/AudioCache(  324): write(0xb57df000, 4096)
V/AudioCache(  324): memcpy(0xae835000, 0xb57df000, 4096)
D/QRemote ( 5142): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
V/OMXCodec(  324): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  324): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  324): postAudioEOS() 
V/AudioCache(  324): write(0xb57df000, 280)
V/AudioCache(  324): memcpy(0xae836000, 0xb57df000, 280)
D/QRemote ( 5142): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:5278
V/AwesomePlayer(  324): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  324): onStreamDone
V/AwesomePlayer(  324): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  324): notify(0xb1163b00, 2, 0, 0)
V/AudioCache(  324): playback complete
V/AwesomePlayer(  324): pause_l() 
V/AudioCache(  324): wait - success
V/AudioCache(  324): notify(0xb1163b00, 7, 0, 0)
V/AudioCache(  324): ignored
V/MediaPlayerService(  324): return size 205080, sampleRate=48000, channelCount = 2, format = 1
V/AwesomePlayer(  324): cancelPlayerEvents
D/AudioPlayer(  324): Pause Playback at 1068125
V/AwesomePlayer(  324): reset_l() 
V/AudioCache(  324): notify(0xb1163b00, 8, 0, 0)
V/AudioCache(  324): ignored
V/QRemote ( 5142): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
V/AwesomePlayer(  324): cancelPlayerEvents
D/AudioPlayer(  324): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  324): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  324): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  324): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
D/QRemote ( 5142): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
V/OMXCodec(  324): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  324): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeing buffer 0xb1434560 on port 0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeing buffer 0xb1434510 on port 0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
E/QRemote ( 5142): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeing buffer 0xb14344c0 on port 0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeing buffer 0xb1434380 on port 0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
D/QRemote ( 5142): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeing buffer 0xb1521240 on port 1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeing buffer 0xb14345b0 on port 1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeing buffer 0xb1434650 on port 1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeing buffer 0xb14346a0 on port 1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  324): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  324): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
D/QRemote ( 5142): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
V/OMXCodec(  324): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  324): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
D/QRemote ( 5142): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
D/QRemote ( 5142): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:547
V/OMXCodec(  324): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  324): AudioPlayer releasing audio source
D/AudioPlayer(  324): AudioPlayer done releasing audio source
V/AwesomePlayer(  324): reset_l() 
V/AwesomePlayer(  324): cancelPlayerEvents
V/AwesomePlayer(  324): ~AwesomePlayer call
V/AwesomePlayer(  324): reset_l() 
V/AwesomePlayer(  324): cancelPlayerEvents
V/SoundPool( 5142): close(31)
V/SoundPool( 5142): pointer = 0xa0026000, size = 205080, sampleRate = 48000, numChannels = 2
V/QRemote ( 5142): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 5142): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,D/QRemote ( 5142): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 5142): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 5142): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 5142): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 5142): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 5142): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
I/ActivityManager( 1030): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5176 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/MtpService( 3303): updating state; isCurrentUser=true, mMtpLocked=false
W/ActivityManager( 1030): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0

```
