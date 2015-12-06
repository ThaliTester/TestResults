#### Test 50242285576d0b0_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
D/LocationInitializer( 4279): Restart initialization of location
D/TelephUtils( 1452): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 88
D/AccFlag ( 1452): sku_id=118
W/art     ( 4530): Suspending all threads took: 16.299ms
--------- beginning of system
W/ResourcesManager( 4653): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4653): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  958): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=4685 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a
I/MultiDex( 4653): VM with version 2.1.0 has multidex support
I/MultiDex( 4653): install
I/MultiDex( 4653): VM has multidex support, MultiDex support library is disabled.
D/TelephUtils( 1452): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 49
D/AccFlag ( 1452): sku_id=118
V/JNIHelp ( 4653): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/GLSUser ( 1890): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
I/GLSUser ( 1890): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1890): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1890): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/TelephUtils( 1452): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 92
D/AccFlag ( 1452): sku_id=118
V/GLSActivity( 1890): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActionCombine( 1890): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
I/WebViewFactory( 4530): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
D/TelephUtils( 1452): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 88
D/AccFlag ( 1452): sku_id=118
W/ResourcesManager( 1301): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
D/DotMatrix( 1301): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
W/ResourcesManager( 1301): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/DotMatrix( 1301): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/ActivityThread( 4653): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 4653): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2510001b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4653): Installed default security provider GmsCore_OpenSSL
W/ResourcesManager( 1215): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1215): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/Search.LoginHelper( 4530): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 4530): com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
W/Search.LoginHelper( 4530): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 4530): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4530): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4530): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 4530): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 4530): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 4530): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 4530): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 4530): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 4530): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4530): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 4530): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4530): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 4530): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 4530): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 4530): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
W/Search.LoginHelper( 4530): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 4530): com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
W/Search.LoginHelper( 4530): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 4530): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4530): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4530): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 4530): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 4530): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 4530): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 4530): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 4530): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 4530): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4530): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 4530): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4530): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 4530): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 4530): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 4530): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
D/WearableService( 4653): callingUid 10024, callindPid: 4653
I/art     ( 1890): Explicit concurrent mark sweep GC freed 13931(831KB) AllocSpace objects, 1(20KB) LOS objects, 48% free, 4MB/8MB, paused 1.721ms total 63.740ms
I/RemoteViews( 1215): apply : com.google.android.gms 0 23 7 40
E/MDM     ( 1786): [135] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
W/Search.LoginHelper( 4530): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 4530): com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
W/Search.LoginHelper( 4530): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 4530): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4530): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4530): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 4530): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 4530): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 4530): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 4530): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 4530): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 4530): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4530): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 4530): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4530): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 4530): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 4530): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 4530): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
D/DotMatrix( 1301): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1301): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1215): reapply : com.google.android.gms 3 40
W/Search.LoginHelper( 4530): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 4530): com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
W/Search.LoginHelper( 4530): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 4530): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4530): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4530): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 4530): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 4530): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 4530): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 4530): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 4530): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 4530): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4530): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 4530): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4530): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 4530): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 4530): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 4530): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
E/Icing   ( 4279): Loading extension by file descriptor -1 failed
W/ResourcesManager( 4530): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/ImageRamCache( 4685): create image Cache, size: 31457280.
I/ImageRamCache( 4685): [resize] ImageRamCache resized to: 30Mb.
I/ImageRamCache( 4685): create image Cache, size: 31457280.
I/FeedSettings( 4685): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 4685): GroupBudget 0.500000 0.380000
I/FeedSettings( 4685): GroupBudget 60 45 15
I/LibraryLoader( 4530): Time to load native libraries: 47 ms (timestamps 6723-6770)
I/Prism.ExternalStringMa_( 4685): changeLocale(): en_GB
I/LibraryLoader( 4530): Expected native library version number "",actual native library version number ""
I/Prism.AllAppsOptionsMa_( 4685): loadSortType() with Custom
I/Prism.AllAppsOptionsMa_( 4685): loadGridSize() with Alternative
D/CustomHighlightReceiver( 4685): [custom highlight] onReceive
D/CustomHighlightService( 4685): [custom highlight] onHandleIntent
D/NewsDB  ( 4685): set custom highlight []
I/ActivityManager(  958): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=4730 uid=10035 gids={50035, 9997} abi=arm64-v8a
W/art     ( 4530): Attempt to remove local handle scope entry from IRT, ignoring
E/cutils-trace( 4716): Error opening trace file: Permission denied (13)
I/ActivityManager(  958): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=4768 uid=10076 gids={50076, 9997} abi=arm64-v8a
D/CustomHighlightService( 4685): [custom highlight] set tags 
I/ActivityManager(  958): Killing 4028:com.htc.backupreset/1000 (adj 15): empty #17
D/Process (  958): killProcessQuiet, pid=4028
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/art     (  430): Explicit concurrent mark sweep GC freed 8642(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 294us total 35.662ms
W/ResourcesManager( 4530): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/art     (  430): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 117us total 17.096ms
I/art     (  430): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 146us total 15.924ms
D/CustomizationManager( 4716): ====startRecUseTime====
D/htc.customization.log.level( 4716):  is 
W/CustomizationLogLevel( 4716): Level value is invalid, use default level 2
I/Icing   ( 4279): updateResources: need to parse f{com.google.android.gms}
I/ActivityManager(  958): Recipient 4028
D/SMSBackup( 4768): Got a database change event
D/CustomizationManager( 4716):  Read ACC file spent 0.042 (s)
D/CIDMapFileReader( 4716): Parsing tag item name = HTC__001
I/ActivityManager(  958): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=4790 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
D/CIDMapFileReader( 4716): Parsing tag item name = HTC__102
W/ResourcesManager( 4530): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/CIDMapFileReader( 4716): Parsing tag item name = HTC__Y13
I/ActivityManager(  958): Killing 4056:com.htc.htccupd/u0a13 (adj 15): empty #17
D/CIDMapFileReader( 4716): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4716): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4716): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4716): Parsing tag item name = HTC__031
D/Process (  958): killProcessQuiet, pid=4056
V/CustomizationCIDLoader( 4716): full path : /system/customize/CID/HTC__102.xml
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/CustomizationCIDLoader( 4716): Parsing tag category name = system
I/CustomizationCIDLoader( 4716): Parsing tag category name = application
I/CustomizationCIDLoader( 4716): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4716): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4716): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4716): Parsing tag category name = Settings
I/CustomizationCIDLoader( 4716): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4716): add string-array item, value = 42507
I/CustomizationCIDLoader( 4716): add string-array item, value = 21902
I/CustomizationCIDLoader( 4716): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 4716): add string-array item, value = 23420
I/CustomizationCIDLoader( 4716): add string-array item, value = 22299
I/CustomizationCIDLoader( 4716): add string-array item, value = 24002
I/CustomizationCIDLoader( 4716): add string-array item, value = 23210
I/CustomizationCIDLoader( 4716): add string-array item, value = 23205
I/CustomizationCIDLoader( 4716): add string-array item, value = 23806
I/CustomizationCIDLoader( 4716): add string-array item, value = 23430
I/CustomizationCIDLoader( 4716): add string-array item, value = 23408
I/CustomizationCIDLoader( 4716): add string-array item, value = 27205
I/CustomizationCIDLoader( 4716): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 4716): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 4716): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 4716): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 4716): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 4716): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 4716): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 4716): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 4716): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 4716): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 4716): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 4716): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 4716):  Read CID file spent 0.096 (s)
D/CustomizationManager( 4716):  All configurations done spent 0.097 (s)
W/art     ( 4530): Attempt to remove local handle scope entry from IRT, ignoring
W/RefreshDomainCookieTask( 4530): Search parameters fetch failed: com.google.android.apps.gsa.shared.api.io.GsaIOException: Error code: 262160 | The connection was not attempted due to lack of network connectivity.
W/RefreshDomainCookieTask( 4530): Search parameters fetch failed
I/ActivityManager(  958): Recipient 4056
I/ActivityManager(  958): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 pid 4716 on display 0
D/PMS     (  958): acquireHCC(3a4afc0e): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 958 1000 null
D/PMS     (  958): acquireHCC(2b8dc62f): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 958 1000 null
W/asset   (  958): Copying FileAsset 0x557a8ca740 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/PMS     (  958): acquireWL(14becb1a): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 958 1000 null
I/FeedHostManager( 1513): [onPause]
I/FeedProviderManager( 1513): onPause
I/SocialFeedProvider( 1513): +onPause
I/FeedHostManager( 1513): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@3a8d2354
I/SocialFeedProvider( 1513): -onPause
I/AnimationUtil(  958): isHTCRecent(HelloWorld/Recent screens.)/5
W/HtcSystemUPManager(  958): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  958): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4819 uid=10373 gids={50373, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/MessagingShortcutReceiver( 3770): keep hiding shortcut bubble
D/MessagingShortcut( 3770): updateMsgShortcut, msg count> -1
D/MessagingShortcut( 3770): After query: 0
D/MessagingShortcut( 3770): mPresentUnreadCount: -1
D/MessageUtils( 3770): [getShortcut] com.htc.sense.mms.ui.ConversationList, false
D/MessagingShortcut( 3770): setMsgShortcutDrawable> 0, false
D/MessagingShortcut( 3770): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
I/Icing   ( 4279): Internal init done: storage state 0
D/DotMatrix( 1301): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1301): [EventService] reorderNotification, total:0
D/DotMatrix( 1301): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1301): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/ActivityManager(  958): Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=4843 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a
W/asset   ( 4530): Copying FileAsset 0x557a753360 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
V/AlarmManager(  958): sending alarm PendingIntent{17986f79: PendingIntentRecord{376c8afb com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=57321, Int=0
I/Icing   ( 4279): Post-init done
D/StatusBarManagerService(  958): setSystemUiVisibility(0x0)
W/asset   ( 4819): Copying FileAsset 0xac44a170 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/StatusBarManagerService(  958): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  958): hiding MENU key
I/TrimMemoryManager( 1513): [trimMemory] 20
W/ResourcesManager( 4843): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/PMS     (  958): releaseWL(2b5fcb7f): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 null
I/Icing   ( 4279): Query from com.google.android.googlequicksearchbox start 0 num 1000
I/ActivityManager(  958): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=4867 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
D/TodoTaskshortcut( 4843): update TASK shortcut>
D/PMS     (  958): acquireWL(2cbb4504): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4843 10069 null
D/PMS     (  958): acquireWL(3fdbcaed): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4843 10069 null
E/Icing   ( 4279): No scoring data for corpus [20]
,D/PMS     (  958): releaseWL(2cbb4504): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
W/asset   ( 4530): Copying FileAsset 0x557a78b7c0 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
E/TodoTaskNotifyService( 4843): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
W/System.err( 4843): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
W/System.err( 4843): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4843): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4843): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/PMS     (  958): releaseWL(3fdbcaed): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
W/System.err( 4843): 	at android.os.Looper.loop(Looper.java:155)
W/System.err( 4843): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/NotifyReceiver( 4843): stopSelfResult true
E/Icing   ( 4279): Loading extension by file descriptor -1 failed
D/PMS     (  958): acquireWL(c29ad70): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1890 10024 WorkSource{10024 com.google.android.gms}
D/libc    ( 1890): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1890): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1890): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1890): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1890): [NET] android_getaddrinfo_proxy+
D/libc    ( 1890): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  396): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  396): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1890): [NET] android_getaddrinfo_proxy-, NODATA
I/Icing   ( 4279): Query from com.google.android.googlequicksearchbox start 0 num 1000
D/PMS     (  958): releaseWL(c29ad70): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
D/Process (  958): killProcessQuiet, pid=4125
I/ActivityManager(  958): Killing 4125:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
E/Icing   ( 4279): Loading extension by file descriptor -1 failed
D/PMS     (  958): releaseWL(1db2fad6): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
I/ApplicationLogger( 4530): logBytes() : Old Hash = -407635623 : New Hash = 1936733727
I/WebViewFactory( 4819): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
I/ActivityManager(  958): Recipient 4125
D/PMS     (  958): acquireWL(353728e9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1890 10024 WorkSource{10024 com.google.android.gms}
D/MtpReceiver( 3710): [MTP][handleUsbStateAsync]+
D/MtpReceiver( 3710): [MTP][handleUsbStateAsync]1:1-
D/MtpReceiver( 3710): [MTP][handleUsbState]+
I/ActivityManager(  958): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4898 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=arm64-v8a
D/MtpReceiver( 3710): [MTP][scanExternalVolumeIfNeed] scan external volume
D/MtpService( 3710): updating state; isCurrentUser=true, mMtpLocked=false
D/PMS     (  958): acquireWL(36e9162b): PARTIAL_WAKE_LOCK  Icing 0x1 4279 10024 WorkSource{10024 com.google.android.gms}
D/MtpDatabase( 3710): TotalSize=1886532,MediaCacheLimit=6000
D/MtpReceiver( 3710): [MTP][handleUsbState]-
D/MtpReceiver( 3710): [MTP][handleMessage]-
D/PMS     (  958): releaseWL(353728e9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/MtpService( 3710): [isMtpConnected] connected: true
D/MdScBoot( 4790): [20d.1.] 30@-140923 -> 40
D/MdScBootUi( 4790): [20d.1.2.] boot 118
D/PMS     (  958): releaseWL(36e9162b): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
I/ApplicationLogger( 4530): logEvent(): Logged 2782 bytes in 1793 ms
I/LibraryLoader( 4819): Time to load native libraries: 15 ms (timestamps 7657-7672)
D/MdScSimSt( 4790): [20d.1.2.] qry 118: 0+1 running 0
I/LibraryLoader( 4819): Expected native library version number "",actual native library version number ""
E/MediaScannerService( 3710): [onStartCommand] --- Should not be here, redirect request. ----
E/MediaScannerService( 3710): [handleMessage] --- Should not be here, ignore request. ----
D/Process (  958): killProcessQuiet, pid=4146
I/ActivityManager(  958): Killing 4146:com.android.settings:remote/1000 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
I/art     (  958): Explicit concurrent mark sweep GC freed 13293(625KB) AllocSpace objects, 1(84KB) LOS objects, 33% free, 15MB/23MB, paused 1.285ms total 142.161ms
V/WebViewChromiumFactoryProvider( 4819): Binding Chromium to main looper Looper (main, tid 1) {18c59c0e}
I/LibraryLoader( 4819): Expected native library version number "",actual native library version number ""
I/chromium( 4819): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4819): Initializing chromium process, singleProcess=true
W/art     ( 4819): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 4819): ApplicationContext is null in ApplicationStatus
I/ActivityManager(  958): Recipient 4146
D/PMS     (  958): acquireWL(1ce0ea07): PARTIAL_WAKE_LOCK  Icing 0x1 4279 10024 WorkSource{10024 com.google.android.gms}
I/ActivityManager(  958): Killing 4170:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
D/Process (  958): killProcessQuiet, pid=4170
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/UpdateIcingCorporaServi( 4530): UpdateCorporaTask done [took 1685 ms] updated apps [took 1685 ms] 
W/chromium( 4819): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 4819): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 4819): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4819): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 4819): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 4819): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 4819): Build Date: 03/09/15 Mon
I/Adreno-EGL( 4819): Local Branch: 
I/Adreno-EGL( 4819): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 4819): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 4819):                  d74aa161a12b9c6fc6332151
W/System.err(  958): java.lang.Throwable: stack dump
W/System.err(  958): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  958): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  958): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  958): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  958): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothAdapter( 4819): 1009501637: getState() :  mService = null. Returning STATE_OFF
D/BluetoothManagerService(  958): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@351c2d2:true
E/MediaScannerServiceEx( 3710): [getStorageMaskIdFromPath] path is null
D/MediaScannerServiceEx( 3710): [ServiceHandler][handleMessage] , action: null, Id: 0, path: /storage/emulated/0
D/MediaScannerServiceEx( 3710): [handleExternalVolume] ext storage
D/MediaProviderUtils( 3710): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3710): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3710): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3710): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
D/MediaScannerServiceEx( 3710): [AliveExtStorageRows]+65537, 11223344
D/MediaProvider( 3710): [update][4]#0#
D/MediaProvider( 3710): [update][1]#0#
I/ActivityManager(  958): Recipient 4170
D/MediaProvider( 3710): [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted
D/MtpService( 3710): [sendStorageAdded] Already send to MTP: /storage/emulated/0
D/MediaProvider( 3710): [update][9]#1#
D/MediaScannerServiceEx( 3710): [AliveExtStorageRows]-0, 0
D/PMS     (  958): acquireWL(13981fa3): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 3710 10017 null
D/ContactMessageStore( 1452): MSG_NOTIFY_CS_TO_SYNC >>
D/Process (  958): killProcessQuiet, pid=4193
I/ActivityManager(  958): Killing 4193:com.android.smith/1000 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/SyncApplication( 4898): Loading default preferences
D/MediaScanner( 3710): =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1
D/ContactMessageStore( 1452): MSG_NOTIFY_CS_TO_SYNC <<
W/Resources( 4898): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
E/WifiTrafficPoller(  958): ADD_CLIENT: 7
D/WifiService(  958): New client listening to asynchronous messages
D/SyncApplication( 4898): Overriding preferences with custom values
D/SyncApplication( 4898): Updating preferences succeeded
I/ActivityManager(  958): Recipient 4193
E/SyncApplication( 4898): Application created.
W/VolumeInfo( 4898): Unable to read mount points
W/VolumeInfo( 4898): java.io.FileNotFoundException: /etc/vold.fstab: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 4898): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/VolumeInfo( 4898): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/VolumeInfo( 4898): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
W/VolumeInfo( 4898): 	at java.io.FileReader.<init>(FileReader.java:66)
W/VolumeInfo( 4898): 	at com.nero.android.common.VolumeInfo.getVolumeMountPoints(VolumeInfo.java:194)
W/VolumeInfo( 4898): 	at com.nero.android.common.VolumeInfo.getVolumes(VolumeInfo.java:153)
W/VolumeInfo( 4898): 	at com.nero.android.common.VolumeInfo.initializeVolumeIDs(VolumeInfo.java:474)
W/VolumeInfo( 4898): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:51)
W/VolumeInfo( 4898): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:1)
W/VolumeInfo( 4898): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/VolumeInfo( 4898): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/VolumeInfo( 4898): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/VolumeInfo( 4898): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/VolumeInfo( 4898): 	at java.lang.Thread.run(Thread.java:818)
W/VolumeInfo( 4898): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 4898): 	at libcore.io.Posix.open(Native Method)
W/VolumeInfo( 4898): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/VolumeInfo( 4898): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/VolumeInfo( 4898): 	... 13 more
V/VolumeInfo( 4898): Found 0 mount point(s)
V/VolumeInfo( 4898): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
D/VolumeInfo( 4898): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
I/CalendarDefines( 4898): getNewCalendarAuthority()...
I/PackageManager(  958):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=4898, uid=10005, userID:0
W/PackageManager(  958): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  958):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=4898, uid=10005, userID:0
W/PackageManager(  958): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
D/SyncApplication( 4898): enableAppOperation()+
D/SyncApplication( 4898): enableAppOperation()-
D/VolumeInfo( 4898): Read the volume-id from the sd card: {9B5E872B-8520-47C6-8BD3-3081C2E38355}
W/VolumeInfo( 4898): Can not create volume ID for unmounted volume null
D/HTCUtilities( 4898): isNeorSinged() + 
D/HTCUtilities( 4898): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
D/HTCUtilities( 4898): isNeorSinged() return false
D/CDMountReceiver( 4898): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
D/CDMountReceiver( 4898): USB connected to PC
D/FOTAReceiver( 4898): onReceive() enter 
D/FOTAReceiver( 4898): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
D/TetherSettings( 4104): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4104): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4104): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4104): Cust_ConnectToPC   : spcsc>false
D/        ( 4104): Cust_ConnectToPC   : IPT>true
D/        ( 4104): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 4104): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4104): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4104): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4104): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
D/SmartNS_Utility( 4104): usb_cable_connect = 1
D/SmartNS_Utility( 4104): usb_denied = 0
I/SmartNS_NSReceiver( 4104): locked:falsesecurity:falseisLocked:false
D/SmartNS_NSReceiver( 4104): USB = true hasTethered = false isNSOpening: false
I/PSReceiver( 4104): onReceive:com.htc.intent.action.USB_CONNECT2PC
W/art     ( 4819): Attempt to remove local handle scope entry from IRT, ignoring
W/ContextImpl( 4104): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2712 
I/SmartNS_PSService( 4104): onReceive:com.htc.intent.action.USB_CONNECT2PC
W/Settings( 4104): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 4104):  defaultType:0
I/SmartNS_PSService( 4104): fail notificaiton:false
D/SmartNS_Utility( 4104): usb_cable_connect = 1
D/SmartNS_Utility( 4104): usb_denied = 0
I/SmartNS_PSService( 4104): usb notificaiton:true
E/WifiStateMachine(  958): WiFiDisplay: getWifidisplayApEnabled=false
W/AwContents( 4819): onDetachedFromWindow called when already detached. Ignoring
I/ActivityManager(  958): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=4955 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
D/SmartNS_Utility( 4104): usb_cable_connect = 1
D/SmartNS_Utility( 4104): usb_denied = 0
I/SmartNS_PSService( 4104): usb notificaiton:true
D/SystemWebViewEngine( 4819): CordovaWebView is running on device made by: HTC
E/WifiStateMachine(  958): WiFiDisplay: getWifidisplayApEnabled=false
D/DotMatrix( 1301): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/RemoteViews( 1215): reapply : com.android.settings 1 36
D/SmartNS_Utility( 4104): usb_cable_connect = 1
D/SmartNS_Utility( 4104): usb_denied = 0
D/DotMatrix( 1301): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/ActivityManager(  958): Killing 4253:com.google.android.gms:car/u0a24 (adj 15): empty #17
W/art     ( 4819): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4819): Attempt to remove local handle scope entry from IRT, ignoring
I/SmartNS_PSService( 4104): KeyGuard locked:falseKeyGuard is secured:false
D/SmartNS_PSService( 4104): USB Plugged, Set USBPlugged=  truePSenabled:false
D/Process (  958): killProcessQuiet, pid=4253
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/RemoteViews( 1215): reapply : com.android.settings 0 36
I/ActivityManager(  958): Recipient 4253
W/chromium( 4819): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
W/ContextImpl( 4955): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.backupreset.receiver.BackupResetReceiver.onReceive:45 android.app.ActivityThread.handleReceiver:2712 
I/ActivityManager(  958): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=4982 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
I/ActivityManager(  958): Killing 4216:com.android.vending/u0a72 (adj 15): empty #17
D/Process (  958): killProcessQuiet, pid=4216
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/FindExtension( 4819): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/ActivityManager(  958): Recipient 4216
I/InputMethodManager( 4819): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@38c1c83b, mServedView=org.apache.cordova.engine.SystemWebView{e266b58 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@1920b4b1
I/InputMethodManagerService(  958): Disable input method client, pid=1513
D/StatusBarManagerService(  958): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  958): Enable input method client, pid=4819
I/PhoneStatusBar( 1215): setImeWindowStatus(false,false)
I/ActivityManager(  958): Displayed com.example.hello/.MainActivity: +1s594ms
W/ResourcesManager( 4982): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/PMS     (  958): releaseWL(14becb1a): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
W/BindingManager( 4819): Cannot call determinedVisibility() - never saw a connection for the pid: 4819
I/chromium( 4819): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
W/XT9_C   ( 1353): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1353): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1353): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1353): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/Icing   ( 4279): Indexing FBE7E5D8BA1B80556F1315772AF6A2582D6BF376 from com.google.android.googlequicksearchbox
I/CalendarProvider2( 4982): Created com.android.providers.calendar.CalendarAlarmManager@32cd1209(com.htc.providers.calendar.HtcCalendarProvider@18c59c0e)
D/CalendarProvider2( 4982): wait start:true
D/JsMessageQueue( 4819): Set native->JS mode to OnlineEventsBridgeMode
E/AndroidProtocolHandler( 4819): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/Icing   ( 4279): Indexing done FBE7E5D8BA1B80556F1315772AF6A2582D6BF376
D/FlexNetS( 4982): updateSvcAllowedInSettings:false
D/PMS     (  958): releaseWL(1ce0ea07): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
D/CalendarProvider2( 4982): wait end:false
I/ActivityManager(  958): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncScreenOnOffTimeReceiver: pid=5013 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
D/jxcore_app_log( 4819): JniHelper::setJavaVM(0xab2ef8f8), pthread_self() = -1401705664
D/JX-Cordova( 4819): jxcore cordova android initializing
D/PMS     (  958): releaseHCC(3a4afc0e): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
D/PMS     (  958): releaseHCC(2b8dc62f): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
D/PMS     (  958): acquireWL(3d4cacad): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5013 1000 null
W/ContextImpl( 5013): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
I/ActivityManager(  958): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=5039 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a
W/Atfwd_Sendcmd(  456): AtCmdFwd service not published, waiting... retryCnt : 4
D/PowerUsageList:PowerUsageHelper( 5013): MY_DEBUG = false
W/jxcore-log( 4819): Initializing JXcore engine
W/jxcore-log( 4819): JXcore engine is ready
W/jxcore-log( 4819): Starting JXcore engine
D/PowerUsageService( 5013): repeat time = 1449411893206
D/WeatherUtility( 1413): Weather sync is On
D/WSP     ( 1413): [Receiver] auto sync agent, auto sync is enabled, reset schedule
I/ActivityManager(  958): Waited long enough for: ServiceRecord{3f5f8a7b u0 com.htc.HTCSpeaker/.NGFService}
,D/WeatherUtility( 5039): Weather sync is On
,W/WeatherRequest( 5039): request cur loc, but there is no sys cur
,W/Settings( 5039): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/Prism.PackageStateRece_( 1513): action: android.intent.action.PACKAGE_ADDED
,I/ActionCombine( 5039): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,I/[PluginManager]RegisterService( 1413): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.example.hello,
,I/[PluginManager]RegisterService( 1413): handle notify Blinkfeed plugin client changed,
,I/ActivityManager(  958): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5067 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/PowerUsageList:PowerUsageHelper( 5013): PowerProfile::POWER_SCREEN_FULL = 154.8
,I/RemoteViews( 1513): reapply : com.htc.widget.weatherclock 9 17
,D/PowerUsageList:BatterySipperExt( 5013): gen(), null == sipper.uidObj, userId = 0
,W/jxcore-log( 4819): Platform android
W/jxcore-log( 4819): 
W/jxcore-log( 4819): Process ARCH arm
W/jxcore-log( 4819): 
,I/DeviceManagement( 5067): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=5067 dbg=false s=true,
,I/DeviceManagement( 5067): PackageUpdateReceiver: vvv Package added: [com.example.hello]
I/ActivityManager(  958): Killing 3367:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  958): killProcessQuiet, pid=3367
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/jxcore-log( 4819): JXcore Cordova bridge is ready!,
I/jxcore-log( 4819): 
W/jxcore-log( 4819): JXcore engine is started
,E/jxcore-log( 4819): >> HTC-HTC One M8s
E/jxcore-log( 4819): 
I/jxcore-log( 4819): Total memory 1931808768
I/jxcore-log( 4819): 
I/jxcore-log( 4819): Free memory 89554944
I/jxcore-log( 4819): 
I/jxcore-log( 4819): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4819): 
I/jxcore-log( 4819): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4819): 
I/jxcore-log( 4819): userPath [ 'www' ]
I/jxcore-log( 4819): 
I/ActivityManager(  958): Recipient 3367
I/jxcore-log( 4819): Size 1080 1776
I/jxcore-log( 4819): 
I/jxcore-log( 4819): Screen Brightness 142
I/jxcore-log( 4819): 
D/MediaProvider( 3710): [update][17]#1#
E/jxcore-log( 4819): Dummy Error Log.
E/jxcore-log( 4819): 
D/MediaScanner( 3710):  prescan time: 292ms
D/MediaScanner( 3710):     scan time: 1124ms
D/MediaScanner( 3710): postscan time: 2ms
D/MediaScanner( 3710):    total time: 1418ms
D/MediaScanner( 3710): -----------------------------------------------------------------
D/MediaScanner( 3710): firstscan(media) time: 662ms
D/MediaScanner( 3710): secondscan(non-media) time: 462ms
D/MediaScanner( 3710):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 1
D/MediaScanner( 3710):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3710):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3710):  [Total]    File(Image+Video+Audio+Others) in database : 1546
,D/MediaProvider( 3710): [delete][9]
,D/MediaProvider( 3710): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
,D/MediaProvider( 3710): [recoverParentNodes] - 0,
D/MediaProvider( 3710): [update][4]
D/MediaScannerServiceEx( 3710): [scan] Recover Parent Node is finished!
D/MediaScannerServiceEx( 3710): [updateImage]+
,I/ActivityManager(  958): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=5089 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a
,D/MediaScannerServiceEx( 3710): [updateImage]-0
,D/Process (  958): killProcessQuiet, pid=4411
I/ActivityManager(  958): Killing 4411:com.google.android.youtube/u0a176 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/PMS     (  958): releaseWL(13981fa3): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
D/MediaScannerServiceEx( 3710): [1] scan finished
,D/MediaProviderUtils( 3710): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3710): calcVolumeId: /storage/ext_sd
,D/MediaProviderUtils( 3710): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3710): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #1
W/MediaScannerServiceEx( 3710): Process mounted intent for unmounted storage: /storage/ext_sd
,I/HtcModeClient( 3151): handler message = 4011
,E/HtcModeClient( 3151): Check connection and retry 4 times.
,I/ActivityManager(  958): Recipient 4411
,D/MediaScannerServiceEx( 3710): [disAliveExtStorageRows]+131073
,D/MediaProvider( 3710): [sendStorageAddedIfNeed]: /storage/ext_sd : unmounted
,D/MediaProvider( 3710): [update][5]#1#
,D/HtcCupdReceiver(Provider)( 5089):  @@@@@ receive action=android.intent.action.PACKAGE_ADDED
,D/MediaProvider( 3710): [update][25]#0#
,D/MediaScannerServiceEx( 3710): [disAliveExtStorageRows]--1, 0
,D/MediaProviderUtils( 3710): calcVolumeId: /storage/emulated/0,
D/MediaProviderUtils( 3710): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3710): calcVolumeId: /storage/usb
,D/MediaScannerServiceEx( 3710): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #2
W/MediaScannerServiceEx( 3710): Process mounted intent for unmounted storage: /storage/usb
,D/MediaScannerServiceEx( 3710): [disAliveExtStorageRows]+196609
,D/MediaProvider( 3710): [sendStorageAddedIfNeed]: /storage/usb : unmounted
,D/MediaProvider( 3710): [update][26]#1#
,I/ActivityManager(  958): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5111 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
D/Process (  958): killProcessQuiet, pid=4489
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  958): Killing 4489:com.google.android.gm/u0a106 (adj 15): empty #17
,I/art     (  430): Explicit concurrent mark sweep GC freed 8664(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 251us total 29.782ms
,D/MediaProvider( 3710): [update][53]#0#,
,D/MediaScannerServiceEx( 3710): [disAliveExtStorageRows]--1, 0,
,I/art     (  430): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 205us total 23.448ms
,I/art     (  430): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 190us total 24.469ms,
I/CalendarProvider2( 4982): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
W/ContentResolver( 4982): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/Settings:HtcWirelessFeatureFlags( 4104): id/is att sku: 118/false
,I/ActivityManager(  958): Recipient 4489
,E/Settings:HtcWrapHeaderInfo( 4104): no such activity!,
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4104): The wrap header doesn't exist in header list.
,I/jxcore-log( 4819): getBuffer is called!!!!,
I/jxcore-log( 4819): 
E/Settings:HtcWrapHeaderInfo( 4104): updateDevelopment, bPrefShow = true
,D/Process (  958): killProcessQuiet, pid=4530
I/ActivityManager(  958): Killing 4530:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
,D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/Settings:HtcUmcWidgetEnabler( 4104): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4104): [supportRecentAppsButton]hasNavigationBar:true,
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4104): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4104): [supportRecentAppsButton]support         :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4104): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4104): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4104): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4104): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4104): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4104): [supportHomeButton]support         :false
,I/ActivityManager(  958): Recipient 4530
D/WifiService(  958): Client connection lost with reason: 4
,V/AlarmManager(  958): sending alarm PendingIntent{e4f953a: PendingIntentRecord{3c3665eb com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1449410994221, Int=0,
,I/GAv4-SVC( 4279): Google Analytics 7.8.99 is starting up.
,I/ActivityManager(  958): Cannot resolve ContentProvider=com.htc.vowifi
E/Settings:HtcVoWifiWidgetEnabler( 4104): isSupportVoWifi: null,
E/ActivityThread( 4104): Failed to find provider info for com.htc.vowifi
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4104): The wrap header doesn't exist in header list.
E/Settings:HtcWrapHeaderInfo( 4104): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 4104): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4104): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4104): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4104): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4104): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4104): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4104): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4104): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4104): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4104): [supportHomeButton]support         :false
,I/ActivityManager(  958): Cannot resolve ContentProvider=com.htc.vowifi
,E/ActivityThread( 4104): Failed to find provider info for com.htc.vowifi
E/Settings:HtcVoWifiWidgetEnabler( 4104): isSupportVoWifi: null
,I/ActivityManager(  958): Killing 4685:com.htc.sense.news/u0a74 (adj 15): empty #17
,D/Process (  958): killProcessQuiet, pid=4685
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=5111, uid=10072, userID:0
,W/global  ( 5111): [apache-http] Connection GC has been deprecated!,
,I/ActivityManager(  958): Recipient 4685,
,D/Finsky  ( 5111): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/,
,W/global  ( 5111): [apache-http] Connection GC has been deprecated!,
,W/global  ( 5111): [apache-http] Connection GC has been deprecated!
,D/Finsky  ( 5111): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.,
,I/ActivityManager(  958): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5156 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,W/Settings( 5111): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5111): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 5156): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 5156): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=5111, uid=10072, userID:0,
,I/MultiDex( 5156): VM with version 2.1.0 has multidex support,
I/MultiDex( 5156): install
I/MultiDex( 5156): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 5156): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/Process (  958): killProcessQuiet, pid=4730
I/ActivityManager(  958): Killing 4730:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17,
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,W/ActivityThread( 5156): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 5156): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2510001b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5156): Installed default security provider GmsCore_OpenSSL,
,I/ActivityManager(  958): Recipient 4730,
,D/PMS     (  958): releaseWL(3d4cacad): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null,
,D/Finsky  ( 5111): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5111): [1] 2.run: Finished loading 1 libraries.,
,D/Finsky  ( 5111): [1] GmsCoreHelper.cleanupNlp: result=false type=4,
,D/ChimeraCfgMgr( 4279): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/PackageBroadcastService( 4279): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
D/ChimeraModuleLdr( 4279): Loading module APK com.google.android.play.games
,D/PMS     (  958): acquireWL(2b4790d5): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4279 10024 null
,D/Finsky  ( 5111): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.,
,I/ConfigFetchService( 4279): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigFetchService( 4279): launchTask,
D/PMS     (  958): acquireWL(3e214624): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 4279 10024 WorkSource{10373 com.example.hello}
D/PMS     (  958): releaseWL(2b4790d5): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null,
,I/PeopleContactsSync( 4279): CP2 sync disabled
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4279, uid=10024, userID:0
,V/ConfigFetchTask( 4279): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1XBQFge2or0AMgJEGfeMC9gD1e0m9KS9pTMYWxveHWDWkxYEATwfMxDBVn0gMNirtf9HriX7JKX8HWK9uNnTO4ezNfmgoHlB793tJXTNI1jpBVzZ6-0Ovut4-pRCe05hd2pt4GfhUVsTvNcDa9cW2cd-fuojCOj2Suum46PPqc0kjGi9tHX_NDpExq-wQhFyXcZE87ARbBuU1hb6GB-QHWZzcujJC6tRssj3Uatb474rPR0Lf8
,I/GoogleURLConnFactory( 4279): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  958): Killing 4768:com.htc.mms.backupagent/u0a76 (adj 15): empty #17,
D/Process (  958): killProcessQuiet, pid=4768
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/art     (  958): Explicit concurrent mark sweep GC freed 25641(1246KB) AllocSpace objects, 3(340KB) LOS objects, 33% free, 15MB/23MB, paused 1.439ms total 150.356ms
D/PMS     (  958): acquireWL(10856daf): PARTIAL_WAKE_LOCK  Icing 0x1 4279 10024 WorkSource{10024 com.google.android.gms}
D/ChimeraCfgMgr( 4279): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4279): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 4279): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/PMS     (  958): releaseWL(10856daf): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
,I/ActivityManager(  958): Recipient 4768
,D/Vision  ( 4279): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package: flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) },
D/Vision  ( 4279): Failed to find package metadata for com.example.hello
D/Vision  ( 4279): No vision deps
,I/ActivityManager(  958): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5195 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a,
,V/Finsky  ( 5111): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,D/libc    ( 4279): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4279): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 4279): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024,
D/libc    ( 4279): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4279): [NET] android_getaddrinfo_proxy+
D/libc    ( 4279): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  396): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  396): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 4279): [NET] android_getaddrinfo_proxy-, NODATA
,W/ConfigFetchTask( 4279): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,I/ConfigFetchService( 4279): fetch service done; releasing wakelock
,D/PMS     (  958): releaseWL(3e214624): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 WorkSource{10373 com.example.hello}
I/ConfigFetchService( 4279): stopping self
,W/BaseAppContext( 4279): Using Auth Proxy for data requests.
,W/BaseAppContext( 4279): Using Auth Proxy for data requests.
,W/BaseAppContext( 4279): Using Auth Proxy for data requests.,
,D/Finsky  ( 5111): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager(  958): sending alarm PendingIntent{254f5945: PendingIntentRecord{205a389a com.android.vending startService}}, i=null, t=0, cnt=1, w=1449410995570, Int=0,
,W/BaseAppContext( 4279): Using Auth Proxy for data requests.
,V/GLSActivity( 1890): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BaseAppContext( 4279): Using Auth Proxy for data requests.
,W/BaseAppContext( 4279): Using Auth Proxy for data requests.
,I/GLSUser ( 1890): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1890): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1890): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1890): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1890): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/Finsky  ( 5111): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1890): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1890): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1890): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1890): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1890): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1890): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1890): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1890): Explicit concurrent mark sweep GC freed 13341(721KB) AllocSpace objects, 6(504KB) LOS objects, 49% free, 4MB/8MB, paused 669us total 41.514ms
,I/GLSUser ( 1890): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1890): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1890): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1890): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1890): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/Finsky  ( 5111): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,E/AndroidHttpClient( 5111): Leak found
E/AndroidHttpClient( 5111): java.lang.IllegalStateException: AndroidHttpClient created and never closed
E/AndroidHttpClient( 5111): 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
E/AndroidHttpClient( 5111): 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
E/AndroidHttpClient( 5111): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
E/AndroidHttpClient( 5111): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
E/AndroidHttpClient( 5111): 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
E/AndroidHttpClient( 5111): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/AndroidHttpClient( 5111): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/AndroidHttpClient( 5111): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidHttpClient( 5111): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidHttpClient( 5111): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidHttpClient( 5111): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidHttpClient( 5111): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidHttpClient( 5111): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidHttpClient( 5111): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidHttpClient( 5111): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidHttpClient( 5111): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService, state=2, flag=1, pid=4279, uid=10024, userID:0
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateActivity, state=2, flag=1, pid=4279, uid=10024, userID:0
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$SecretCodeReceiver, state=2, flag=1, pid=4279, uid=10024, userID:0,
I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$Receiver, state=2, flag=1, pid=4279, uid=10024, userID:0
,I/GAv4    ( 5195): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5195):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5195):   adb logcat -s GAv4
,W/GAv4    ( 5195): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5195): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5195): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,D/ChimeraCfgMgr( 4279): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4279): Module APK com.google.android.play.games already loaded
,W/AnalyticsTrackerProxyImpl( 5195): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.25.45
,D/AccTypeManager( 1671): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
W/SystemReader(  958): Cannot find grip_rejection_width, use default value instead,
,W/ResourcesManager( 1452): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/AccTypeManager( 1671): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/ResourcesManager(  958): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/Prism.ItemManager( 1513): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1513): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/Prism.AllAppsManager( 1513): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/Launcher( 1513): Deferring update until onResume
,D/Launcher( 1513): waitUntilResume // bindAppsUpdated
,D/AccTypeManager( 1671): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin,
,D/PhoneApp( 1452): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,E/ExternalAccountType( 1671): Unsupported attribute readOnly,
,W/PackageManager(  958): Unable to load service info ResolveInfo{62cddbd com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  958): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  958): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  958): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  958): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  958): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
,W/PackageManager(  958): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  958): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  958): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  958): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  958): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  958): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  958): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  958): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  958): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  958): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  958): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,V/GLSActivity( 1890): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GmsNetworkLocationProvi( 1786): DISABLE,
,I/BackupManagerService(  958): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/GCoreNlp( 1786): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  958): applying state to connected service
D/VoldConnector(  958): SND -> {16 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/}
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/
W/ContextImpl( 5195): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.docs/cache
,I/ActivityManager(  958): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5242 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/GLSUser ( 1890): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
W/ResourcesManager( 5195): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
I/GLSUser ( 1890): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
W/ResourcesManager( 5195): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/GLSUser ( 1890): [GLSUser] Extracting token using key: Auth
D/PMS     (  958): acquireWL(1b68bea3): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1786 10024 WorkSource{10024 com.google.android.gms}
W/GLSActivity( 1890): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/PMS     (  958): releaseWL(1b68bea3): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,V/GLSActivity( 1890): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SocialFeedProvider( 1513): +disConnect socialManager
I/SocialFeedProvider( 1513): disconnect socialManager
,I/SocialFeedProvider( 1513): -disConnect socialManager,
D/LocationProviderProxy(  958): applying state to connected service
,D/PMS     (  958): acquireWL(8bc5691): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1786 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  958): acquireWL(1fb739f6): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1786 10024 WorkSource{10024 com.google.android.gms}
,W/Finsky  ( 5111): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/PMS     (  958): releaseWL(8bc5691): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
D/Finsky  ( 5111): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
D/PMS     (  958): releaseWL(1fb739f6): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/Finsky  ( 5111): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/JNIHelp ( 5195): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/Finsky  ( 5111): [1] DailyHygiene.reschedule: Giving up. (failures=6)
,W/ResourcesManager( 5242): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,D/Process (  958): killProcessQuiet, pid=3770
I/ActivityManager(  958): Killing 3770:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/DeviceConnectionService( 1786): client connected with version: 7571000
W/art     ( 5195): Suspending all threads took: 11.403ms
,W/System  ( 5195): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5195): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  958): Recipient 3770
,D/Process (  958): killProcessQuiet, pid=4790,
I/ActivityManager(  958): Killing 4790:com.htc.mobiledata:remote/u0a46 (adj 15): empty #18
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  958): Recipient 4790,
,V/GLSActivity( 1890): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/ActivityManager(  958): Start proc com.htc.sense.news for service com.htc.launcher/com.htc.plugin.news.SocialBiLogHelper: pid=5269 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a,
V/AlarmManager(  958): sending alarm PendingIntent{2cd78685: PendingIntentRecord{129efcda com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1449410996547, Int=0
,I/ImageRamCache( 5269): create image Cache, size: 31457280.,
I/ImageRamCache( 5269): [resize] ImageRamCache resized to: 30Mb.
I/ImageRamCache( 5269): create image Cache, size: 31457280.
,I/FeedSettings( 5269): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
,I/FeedSettings( 5269): GroupBudget 0.500000 0.380000,
I/FeedSettings( 5269): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 5269): changeLocale(): en_GB,
,I/Prism.AllAppsOptionsMa_( 5269): loadSortType() with Custom,
I/Prism.AllAppsOptionsMa_( 5269): loadGridSize() with Alternative
,I/SocialManager[SocialBiLogHelper]( 5269): action: com.htc.sense.hsp.HANDLE_ULOG,
I/SocialManager[SocialBiLogHelper]( 5269): last commit ulog time 1449381160756,
I/SocialManager[SocialBiLogHelper]( 5269): skip commit this time
,D/Process (  958): killProcessQuiet, pid=4378
I/ActivityManager(  958): Killing 4378:com.google.android.talk/u0a112 (adj 15): empty #17
,D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 ,
,I/ActivityManager(  958): Recipient 4378
,D/PMS     (  958): acquireWL(19b50bdf): PARTIAL_WAKE_LOCK  AsyncService 0x1 5242 10167 null
,D/PMS     (  958): releaseWL(19b50bdf): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  958): acquireWL(9601af5): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 5242 10167 null
,D/PMS     (  958): releaseWL(9601af5): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,I/ActivityManager(  958): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5304 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
,D/Process (  958): killProcessQuiet, pid=4843,
I/ActivityManager(  958): Killing 4843:com.htc.task/u0a69 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 ,
,I/ActivityManager(  958): Recipient 4843
,I/ActivityManager(  958): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=5326 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a,
,W/ResourcesManager( 5326): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Prism.ItemManager( 1513): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1513): loadItems() com.htc.launcher.pageview.WidgetManager@2d5d896a +
I/Prism.WidgetManager( 1513): onLoadItems() +
,I/ActivityManager(  958): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=5349 uid=10028 gids={50028, 9997, 1028, 1015, 1023, 3003, 2001, 3002} abi=armeabi-v7a
,W/ResourcesManager( 1513): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/art     (  958): Explicit concurrent mark sweep GC freed 22658(1171KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.445ms total 164.661ms,
,D/LocationManagerService(  958): getProviders()=[passive]
,W/ResourcesManager( 5349): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  958): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=5374 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a,
,D/Process (  958): killProcessQuiet, pid=4867
I/ActivityManager(  958): Killing 4867:com.htc.mobiledata/u0a46 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/ResourcesManager( 1513): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  958): Recipient 4867
,I/UpdateIcingCorporaServi( 5304): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,W/asset   ( 1513): Copying FileAsset 0x557a82b700 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.,
,W/asset   ( 5304): Copying FileAsset 0x557a508230 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,I/UpdateIcingCorporaServi( 5304): UpdateCorporaTask done [took 116 ms] updated apps [took 115 ms] 
,I/ActivityManager(  958): Killing 4898:com.nero.android.htc.sync/u0a5 (adj 15): empty #17,
D/Process (  958): killProcessQuiet, pid=4898
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  958): Recipient 4898
,D/WifiService(  958): Client connection lost with reason: 4
,E/Prism.WidgetManager( 1513): The same lists. No need to update. skip it.,
I/Prism.WidgetManager( 1513): onLoadItems() -
I/Prism.ItemManager( 1513): loadItems() com.htc.launcher.pageview.WidgetManager@2d5d896a -
,D/PhoneApp( 1452): EVENT_QUERY_MO_PACKAGES
D/PhoneApp( 1452): -- N1 =0
D/PhoneApp( 1452): -- N2 =0
,I/ActivityManager(  958): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=5402 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
D/PhoneApp( 1452): -- N3 =0
,I/EASAppSvc( 5374): [ NA ]onCreate,
,I/VersionUtil( 5374): [ NA ]setIsFOTAing: true
,E/SQLiteLog( 5349): (283) recovered 15 frames from WAL file /data/data/com.htc.album/databases/MMexternal.db-wal
,I/VersionUtil( 5374): [ NA ]onUpgrade: current version=100, latest version=100
,I/VersionUtil( 5374): [ NA ]setIsFOTAing: false
,D/ORMLib  ( 5326): put()
,D/HtcAdjCursorFactory( 5374): Set CursorWindow size to: 4194304 KB, Tid: 5425
,I/ActivityManager(  958): Killing 4955:com.htc.backupreset/1000 (adj 15): empty #17,
D/Process (  958): killProcessQuiet, pid=4955
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  958): Recipient 4955,
,I/EASAppSvc( 5374): [ NA ]onDestroy
,I/EASAppSvc( 5374): [ NA ]onCreate,
,D/WifiService(  958): New client listening to asynchronous messages
E/WifiTrafficPoller(  958): ADD_CLIENT: 6
,I/VersionUtil( 5374): [ NA ]setIsFOTAing: true
W/EAS_NetworkUtil( 5374): [ NA ]getNetworkInfo: NetworkInfo is null
,I/EASAppSvc( 5374): [ NA ]> uninitEASService,
I/EASRequestController( 5374): [ NA ]release
,I/VersionUtil( 5374): [ NA ]onUpgrade: current version=100, latest version=100
,I/VersionUtil( 5374): [ NA ]setIsFOTAing: false
,W/EAS_NetworkUtil( 5374): [ NA ]getNetworkInfo: NetworkInfo is null
,D/ORMLib  ( 5326): put(),
I/MusicStore( 5402): Database version: 120
,D/EASPublicBinder( 5374): [ NA ]release
,D/TaskBinder( 5374): [ NA ]release
D/TaskBinder( 5374): [ NA ]release
I/EASAppSvc( 5374): [ NA ]< uninitEASService
,D/BluetoothManagerService(  958): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  958): disable(): mBluetooth = null mBinding = false
W/Settings:Agent(  958): MONITOR_LOG
W/Settings:Agent(  958): name: bluetooth_on
W/Settings:Agent(  958): value: 0
W/Settings:Agent(  958): >> traceCallingStack(),
W/Settings:Agent(  958): Process.myPid(): 958
W/Settings:Agent(  958): Process.myTid(): 1475
W/Settings:Agent(  958): Process.myUid(): 1000
W/Settings:Agent(  958): 
,W/Settings:Agent(  958): 
W/System.err(  958): java.lang.Throwable: stack dump,
,W/System.err(  958): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  958): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  958): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  958): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  958): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  958): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  958): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:378)
,W/System.err(  958): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:624)
W/System.err(  958): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  958): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  958): 
W/Settings:Agent(  958): << traceCallingStack(): 17(ms)
D/BluetoothManagerService(  958): Message: MESSAGE_DISABLE
,E/WifiTrafficPoller(  958): ADD_CLIENT: 7,
D/WifiService(  958): New client listening to asynchronous messages
D/WifiManager( 4819): setWifiEnabled: Base Package Name=com.example.hello, uid=10373
,D/WifiService(  958): setWifiEnabled: false pid=4819, uid=10373,
E/WifiService(  958): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  958): isSprintWifiRestricted(): false
I/WifiService(  958): isMdmWifiRestricted(): false
,W/Settings:Agent(  958): MONITOR_LOG,
W/Settings:Agent(  958): name: wifi_on
W/Settings:Agent(  958): value: 0
W/Settings:Agent(  958): >> traceCallingStack()
W/Settings:Agent(  958): Process.myPid(): 958,
W/Settings:Agent(  958): Process.myTid(): 4215
W/Settings:Agent(  958): Process.myUid(): 1000
W/Settings:Agent(  958): 
W/Settings:Agent(  958): 
W/System.err(  958): java.lang.Throwable: stack dump
,W/System.err(  958): ,	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  958): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  958): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  958): ,	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  958): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  958): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  958): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  958): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:112),
W/System.err(  958): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  958): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  958): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  958): 
,W/Settings:Agent(  958): << traceCallingStack(): 9(ms)
D/WifiController(  958): handleMessage: E msg.what=155656
D/WifiController(  958): processMsg: ApStaDisabledState
D/WifiController(  958): handleMessage: X
,I/jxcore-log( 4819): ****TEST TOOK:  5092  ms ****
I/jxcore-log( 4819): 
I/jxcore-log( 4819): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4819): 
,I/EASAppSvc( 5374): [ NA ]onDestroy,
,I/EASAppSvc( 5374): [ NA ]> uninitEASService
,I/ActivityManager(  958): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=5447 uid=10066 gids={50066, 9997, 3003} abi=arm64-v8a
I/EASRequestController( 5374): [ NA ]release
,D/PMS     (  958): acquireWL(3eba37d5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 958 1000 null
I/BatteryService(  958): n_update end
,D/UsbnetService(  958): BroadcastReceiver::onReceive+
D/PMS     (  958): releaseWL(3eba37d5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  958): onReceive BATTERY_CHANGED
D/NotificationService(  958): plugged=true pluggin=true,
D/UsbnetService(  958):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  958): updateBatteryInfo
D/UsbnetService(  958): BroadcastReceiver::onReceive-
D/PowerUI ( 1215): closing low battery warning: level=100,
D/WifiController(  958): handleMessage: E msg.what=155652
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  958): battery changed pluggedType: 2
D/DotMatrix( 1301): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  958): runPSCheck
D/DotMatrix( 1301): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  958): Checking...
D/DotMatrix( 1301): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  958): >> updateStatus
D/WifiController(  958): processMsg: ApStaDisabledState
D/WifiController(  958): processMsg: DefaultState
D/WifiController(  958): handleMessage: X
,I/HtcPowerSaver(  958): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  958): << updateStatus
,D/EASPublicBinder( 5374): [ NA ]release
,D/TaskBinder( 5374): [ NA ]release
D/TaskBinder( 5374): [ NA ]release
I/EASAppSvc( 5374): [ NA ]< uninitEASService
,I/HtcModeClient( 3151): handler message = 4011
E/HtcModeClient( 3151): Check connection and retry 5 times.
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,D/VoldConnector(  958): SND -> {17 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 5402): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/Process (  958): killProcessQuiet, pid=4982
I/ActivityManager(  958): Killing 4982:com.htc.bgp/u0a11 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/ORMLib  ( 5326): put()
,D/VoldConnector(  958): SND -> {18 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 5402): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  958): SND -> {19 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/,
W/ContextImpl( 5402): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,I/ActivityManager(  958): Recipient 4982,
,E/cutils-trace( 5473): Error opening trace file: Permission denied (13),
,I/ActivityManager(  958): Killing 5013:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/Process (  958): killProcessQuiet, pid=5013
,D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/CustomizationManager( 5473): ====startRecUseTime====,
D/htc.customization.log.level( 5473):  is 
W/CustomizationLogLevel( 5473): Level value is invalid, use default level 2
,I/ActivityManager(  958): Recipient 5013
,D/CustomizationManager( 5473):  Read ACC file spent 0.033 (s),
,D/CIDMapFileReader( 5473): Parsing tag item name = HTC__001
,D/CIDMapFileReader( 5473): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5473): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5473): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5473): Parsing tag item name = HTC__M27,
D/CIDMapFileReader( 5473): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5473): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 5473): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 5473): Parsing tag category name = system
,I/CustomizationCIDLoader( 5473): Parsing tag category name = application
I/CustomizationCIDLoader( 5473): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5473): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5473): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5473): Parsing tag category name = Settings
I/CustomizationCIDLoader( 5473): Parsing tag category name = ACC
I/CustomizationCIDLoader( 5473): add string-array item, value = 42507
I/CustomizationCIDLoader( 5473): add string-array item, value = 21902
I/CustomizationCIDLoader( 5473): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 5473): add string-array item, value = 23420
I/CustomizationCIDLoader( 5473): add string-array item, value = 22299
I/CustomizationCIDLoader( 5473): add string-array item, value = 24002
I/CustomizationCIDLoader( 5473): add string-array item, value = 23210
I/CustomizationCIDLoader( 5473): add string-array item, value = 23205
I/CustomizationCIDLoader( 5473): add string-array item, value = 23806
I/CustomizationCIDLoader( 5473): add string-array item, value = 23430
I/CustomizationCIDLoader( 5473): add string-array item, value = 23408
I/CustomizationCIDLoader( 5473): add string-array item, value = 27205
I/CustomizationCIDLoader( 5473): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 5473): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 5473): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 5473): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 5473): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 5473): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 5473): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 5473): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 5473): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 5473): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 5473): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 5473): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 5473):  Read CID file spent 0.071 (s)
D/CustomizationManager( 5473):  All configurations done spent 0.071 (s)
,W/ResourcesManager( 5402): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5402): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/PackageManager(  958): deletePackageAsUser: pkg=com.example.hello, pid=5473, uid=2000 userid=0,
,V/JNIHelp ( 5402): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ActivityManager(  958): Force stopping com.example.hello appid=10373 user=-1: uninstall pkg,
,D/Process (  958): killProcessQuiet, pid=4819
I/ActivityManager(  958): Killing 4819:com.example.hello/u0a373 (adj 0): stop com.example.hello
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
,W/ActivityThread( 5402): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 5402): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@26ebccad: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5402): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5402): GMSCore installation verified
,W/PackageSettings(  958): Skipping PackageSetting{372e5458 com.test.thalitest/10366} due to missing metadata,
,I/ActivityManager(  958): Recipient 4819
E/InputEventReceiver( 1353): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{144b1f94 uid 10373 pid 4819} (c)'
I/WindowState(  958): WIN DEATH: Window{3bb081a6 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  958): Client connection lost with reason: 4
,W/ActivityManager(  958): Force removing ActivityRecord{3519e43c u0 com.example.hello/.MainActivity t8}: app died, no saved state
,I/ActivityManager(  958): Force stopping com.example.hello appid=10373 user=0: pkg removed
,D/DotMatrix( 1301): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
W/ActivityManager(  958): Spurious death for ProcessRecord{1d386489 4819:com.example.hello/u0a373}, curProc for 4819: null
D/DotMatrix( 1301): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1301): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
,D/PMS     (  958): acquireWL(2a9abc8e): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1786 10024 WorkSource{10024 com.google.android.gms}
I/ConfigStore( 5402): Config Database version: 1
,D/AccTypeManager( 1671): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
I/FeedHostManager( 1513): [onResume]
I/FeedProviderManager( 1513): onResume
,I/SocialFeedProvider( 1513): +onResume
,I/SocialFeedProvider( 1513): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1513): -onResume
W/SystemReader(  958): Cannot find grip_rejection_width, use default value instead
,I/Prism.ItemManager( 5269): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/PMS     (  958): releaseWL(2a9abc8e): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,I/ConnectivityHelper( 1513): [getCurrentConnectionType] no network connection
W/GeofencerStateMachine( 1786): Ignoring removeGeofence because network location is disabled.
I/Prism.ItemManager( 5269): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false,
I/Prism.ItemManager( 1513): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1513): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,D/AccTypeManager( 1671): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/StatusBarManagerService(  958): setSystemUiVisibility(0x700)
,D/StatusBarManagerService(  958): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  958): hiding MENU key
D/FindExtension( 1513): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/InputMethodManagerService(  958): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,D/AccTypeManager( 1671): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/ThreadedRenderer( 1513): Defer allocateBuffers to drawing time,
D/PhoneApp( 1452): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,E/ExternalAccountType( 1671): Unsupported attribute readOnly,
W/ResourcesManager(  958): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/InputMethodManagerService(  958): Got RemoteException sending setActive(false) notification to pid 4819 uid 10373
D/StatusBarManagerService(  958): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  958): Enable input method client, pid=1513
,I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=5402, uid=10159, userID:0
,D/WifiDisplayAdapter(  958): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  958):     Client/Owner: Client
D/WifiDisplayAdapter(  958):     GroupId: 
,D/WifiDisplayAdapter(  958):     Passphrase: 
D/WifiDisplayAdapter(  958):     SessionId: 0
D/WifiDisplayAdapter(  958):     IP Address: }
,D/MediaRouterService(  958): Client com.google.android.music (pid 5402): Registered
,D/WifiDisplayAdapter(  958): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  958):     Client/Owner: Client
D/WifiDisplayAdapter(  958):     GroupId: 
D/WifiDisplayAdapter(  958):     Passphrase: 
D/WifiDisplayAdapter(  958):     SessionId: 0
D/WifiDisplayAdapter(  958):     IP Address: }
,D/StatusBarManagerService(  958): setSystemUiVisibility(0xc0000700)
,D/StatusBarManagerService(  958): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  958): hiding MENU key
W/PackageManager(  958): Unable to load service info ResolveInfo{16df1f76 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  958): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  958): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  958): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  958): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  958): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  958): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  958): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  958): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  958): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  958): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  958): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  958): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  958): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  958): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  958): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  958): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/MediaRouter( 5402): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
I/art     (  958): Explicit concurrent mark sweep GC freed 20689(1505KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 16MB/24MB, paused 9.986ms total 209.773ms
W/asset   (  958): Copying FileAsset 0x557a8c1240 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.,
,I/ActivityManager(  958): Start proc com.htc.bgp for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=5500 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
,W/ResourcesManager( 5500): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/PackageManager(  958):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=5402, uid=10159, userID:0
,I/GHttpClientFactory( 5402): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 5402): Using platform SSLCertificateSocketFactory,
,I/CalendarProvider2( 5500): Created com.android.providers.calendar.CalendarAlarmManager@32cd1209(com.htc.providers.calendar.HtcCalendarProvider@18c59c0e),
,D/CalendarProvider2( 5500): wait start:true,
,D/Process (  958): killProcessQuiet, pid=5039,
I/ActivityManager(  958): Killing 5039:com.htc.widget.hmsproc2/u0a40 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/JobSchedulerService(  958): Receieved: android.intent.action.PACKAGE_REMOVED
,I/ActivityManager(  958): Recipient 5039
,I/PhoneStatusBar( 1215): setImeWindowStatus(false,false)
,D/PMS     (  958): acquireWL(242438a5): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 5500 10011 null
,D/CalendarProvider2( 5500): wait end:false
,D/TaskPersister(  958): removeObsoleteFile: deleting file=8_task.xml
,D/TelephonyReceiver( 1452): bind: true,
,E/SQLiteLog( 5500): (284) automatic index on view_events(_id),
,I/ActivityManager(  958): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=5532 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,W/OpenGLRenderer( 1513): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,I/ActivityManager(  958): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.GenericMessagesProvider: pid=5551 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
V/AlarmManager(  958): sending alarm PendingIntent{1334942b: PendingIntentRecord{36ca6088 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=66046, Int=0
,I/ClockController( 1215): schedule update now=1449411000034 next=59966
,I/Clock   ( 1215): updateClock:15:10 Europe/Warsaw
I/Clock   ( 1215): updateClock:15:10 Europe/Warsaw,
I/Clock   ( 1215): updateClock:15:10 Europe/Warsaw
,D/DFPI.PIReciver( 5532): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,D/PMS     (  958): releaseWL(242438a5): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,I/DFPI.ApkInstallService( 5532): onHandleIntent
I/DFPI.ApkInstallService( 5532): Media Scan Finished Case 
,D/WeatherUtility( 1215): Weather sync is On,
W/WeatherTimeKeeper( 1215): [refreshWeatherData] no weather data
D/DFPI.ApkInstallService( 5532): check CID = HTC__102
I/DFPI.ApkInstallService( 5532): There is no Demo.apk in sd card or phone storage
W/HtcWrapAdjustableCursorFactory( 5551): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.
,D/MessageFrequencyProvider( 5551): onCreate,
,I/ActivityManager(  958): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=5578 uid=10049 gids={50049, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,V/GetPrviateResource( 5551): GetPrviateResource
,V/GetPrviateResource( 5551): GetPrviateResource
,D/GenericMessagesProvider( 5551): query uri: content://htc-messages/wappush/count
,E/SQLiteLog( 5551): (14) cannot open file at line 30058 of [9491ba7d73],
E/SQLiteLog( 5551): (14) os_unix.c:30058: (2) open(/data/data/com.htc.sense.mms/databases/wappush.db) - 
E/SQLiteConnection( 5551): DB info: sqlite3_open_v2, path: /data/data/com.htc.sense.mms/databases/wappush.db, flag: 1, ret: 14
E/SQLiteConnection( 5551): DB info: errno = 2, errno message = No such file or directory
,D/MessageCustFlag( 5551): sense_version=6.0,
,E/SQLiteDatabase( 5551): Failed to open database '/data/data/com.htc.sense.mms/databases/wappush.db'.
E/SQLiteDatabase( 5551): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 5551): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5551): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 5551): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 5551): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5551): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5551): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5551): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5551): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5551): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5551): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:712)
E/SQLiteDatabase( 5551): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
E/SQLiteDatabase( 5551): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 5551): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 5551): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
E/SQLiteDatabase( 5551): 	at android.os.Binder.execTransact(Binder.java:454)
D/BTAccessoryUtil( 5551): createReceiver
,D/BTAccessoryUtil( 5551): registerReceiver return intent = null
W/System.err( 5551): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
W/System.err( 5551): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 5551): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
,W/System.err( 5551): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
W/System.err( 5551): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
I/ActivityManager(  958): Killing 4567:com.google.android.partnersetup/u0a27 (adj 15): empty #17
W/System.err( 5551): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/System.err( 5551): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/System.err( 5551): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
W/System.err( 5551): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
W/System.err( 5551): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
W/System.err( 5551): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:712)
W/System.err( 5551): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
W/System.err( 5551): 	at android.content.ContentProvider.query(ContentProvider.java:960)
W/System.err( 5551): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
W/System.err( 5551): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
W/System.err( 5551): 	at android.os.Binder.execTransact(Binder.java:454)
D/MessageCustFlag( 5551): sku_id=118
D/Process (  958): killProcessQuiet, pid=4567
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
D/HtcBuildUtils( 5551): getRATByHtcTelephonyCapability:1
W/SystemReader( 5551): Cannot find qct_8960_interface, use default value instead
,I/ActivityManager(  958): Recipient 4567
,D/TelephonyReceiver( 1452): switchBindHtcMsgCursor: null
,I/ActivityManager(  958): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=5602 uid=10079 gids={50079, 9997, 5001, 1028, 1015} abi=arm64-v8a
,D/VoldConnector(  958): SND -> {20 volume mkdirs /storage/ext_sd/Android/data/com.htc.musicenhancer/cache/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.htc.musicenhancer/cache/
,W/ContextImpl( 5578): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
,V/AlarmManager(  958): sending alarm PendingIntent{10cb40f7: PendingIntentRecord{a601b64 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1449411000356, Int=0,
,I/SoundPicker( 5602): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED,
,I/SoundPicker( 5602): SoundPickerReceiver [onReceive] startService,
,I/SoundPicker( 5602): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5602): TurnFileToMediaUriService fromMediaScanned = true
,I/SoundPicker( 5602): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
,D/RingtoneManager( 5602): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,I/ActivityManager(  958): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=5628 uid=10084 gids={50084, 9997, 3003, 1028, 1015, 1023, 2001, 5006, 5001} abi=arm64-v8a
,I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5602): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122,
D/RingtoneManager( 5602): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5602): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5602): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5602): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5602): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5602): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5602): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5602): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
,I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6,
W/SoundPicker( 5602): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5602): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5602): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5602): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5602): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5602): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5602): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac,
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 5602): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
,I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
I/art     (  430): Explicit concurrent mark sweep GC freed 8669(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 327us total 32.204ms
,I/SoundPicker( 5602): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac,
D/RingtoneManager( 5602): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5602): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac,
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5602): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
,I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98,
,I/SoundPicker( 5602): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/art     (  430): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 318us total 25.004ms
,I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,D/RingtoneManager( 5602): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 5602): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac,
,I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
,I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
I/SoundPicker( 5602): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
D/DFPI.PIReciver( 5532): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
I/art     (  430): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 280us total 23.328ms
I/DFPI.ApkInstallService( 5532): onHandleIntent
I/DFPI.ApkInstallService( 5532): Media Scan Finished Case 
,I/SoundPicker( 5602): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
D/DFPI.ApkInstallService( 5532): check CID = HTC__102
I/DFPI.ApkInstallService( 5532): There is no Demo.apk in sd card or phone storage
,I/SoundPicker( 5602): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED,
,I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/ActivityManager(  958): Killing 5067:com.htc.cs.dm/u0a99 (adj 15): empty #17
,I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
D/Process (  958): killProcessQuiet, pid=5067
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/SQLiteDatabase( 5628): Failed to open database '/data/data/com.htc.updater/databases/fota.db'.
E/SQLiteDatabase( 5628): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5628): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5628): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 5628): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 5628): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
,E/SQLiteDatabase( 5628): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5628): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5628): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5628): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5628): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5628): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 5628): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 5628): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5628): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 5628): 	at com.htc.updater.db.UpdaterProvider.query(UpdaterProvider.java:473)
E/SQLiteDatabase( 5628): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 5628): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 5628): 	at android.content.ContentResolver.query(ContentResolver.java:491)
E/SQLiteDatabase( 5628): 	at android.content.ContentResolver.query(ContentResolver.java:435)
E/SQLiteDatabase( 5628): 	at com.htc.updater.db.FOTASettings$NameValueCache.getString(FOTASettings.java:310)
E/SQLiteDatabase( 5628): 	at com.htc.updater.db.FOTASettings.getString(FOTASettings.java:185)
E/SQLiteDatabase( 5628): 	at com.htc.updater.db.FOTASettings.getBoolean(FOTASettings.java:257)
E/SQLiteDatabase( 5628): 	at com.htc.updater.UpdaterReceiver$CheckActionThread.run(UpdaterReceiver.java:183)
E/SQLiteOpenHelper( 5628): Couldn't open fota.db for writing (will try read-only):
E/SQLiteOpenHelper( 5628): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5628): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5628): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteOpenHelper( 5628): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteOpenHelper( 5628): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
,E/SQLiteOpenHelper( 5628): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5628): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5628): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteOpenHelper( 5628): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteOpenHelper( 5628): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteOpenHelper( 5628): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteOpenHelper( 5628): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 5628): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 5628): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 5628): 	at com.htc.updater.db.UpdaterProvider.query(UpdaterProvider.java:473)
E/SQLiteOpenHelper( 5628): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteOpenHelper( 5628): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteOpenHelper( 5628): 	at android.content.ContentResolver.query(ContentResolver.java:491)
E/SQLiteOpenHelper( 5628): 	at android.content.ContentResolver.query(ContentResolver.java:435)
E/SQLiteOpenHelper( 5628): 	at com.htc.updater.db.FOTASettings$NameValueCache.getString(FOTASettings.java:310)
E/SQLiteOpenHelper( 5628): 	at com.htc.updater.db.FOTASettings.getString(FOTASettings.java:185)
E/SQLiteOpenHelper( 5628): 	at com.htc.updater.db.FOTASettings.getBoolean(FOTASettings.java:257)
E/SQLiteOpenHelper( 5628): 	at com.htc.updater.UpdaterReceiver$CheckActionThread.run(UpdaterReceiver.java:183)
W/SQLiteOpenHelper( 5628): Opened fota.db in read-only mode
E/UpdaterAPK | COTASettings( 5628): Can't set key cota_notify_download
E/UpdaterAPK | COTASettings( 5628): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/UpdaterAPK | COTASettings( 5628): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/UpdaterAPK | COTASettings( 5628): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/UpdaterAPK | COTASettings( 5628): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/UpdaterAPK | COTASettings( 5628): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/UpdaterAPK | COTASettings( 5628): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/UpdaterAPK | COTASettings( 5628): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:823)
E/UpdaterAPK | COTASettings( 5628): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
E/UpdaterAPK | COTASettings( 5628): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/UpdaterAPK | COTASettings( 5628): 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:480)
E/UpdaterAPK | COTASettings( 5628): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
E/UpdaterAPK | COTASettings( 5628): 	at android.content.ContentResolver.update(ContentResolver.java:1354)
E/UpdaterAPK | COTASettings( 5628): 	at com.htc.updater.db.COTASettings$NameValueCache.putString(COTASettings.java:91)
E/UpdaterAPK | COTASettings( 5628): 	at com.htc.updater.db.COTASettings.putString(COTASettings.java:146)
E/UpdaterAPK | COTASettings( 5628): 	at com.htc.updater.db.COTASettings.putBoolean(COTASettings.java:160)
E/UpdaterAPK | COTASettings( 5628): 	at com.htc.updater.UpdaterReceiver.checkConfirmStatus(UpdaterReceiver.java:687)
E/UpdaterAPK | COTASettings( 5628): 	at com.htc.updater.UpdaterReceiver.access$200(UpdaterReceiver.java:53)
E/UpdaterAPK | COTASettings( 5628): 	at com.htc.updater.UpdaterReceiver$CheckActionThread.run(UpdaterReceiver.java:192)
,I/ActivityManager(  958): Recipient 5067
,I/SoundPicker( 5602): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 5602): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/ConfigService( 1890): onDestroy
,I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
E/SharedPreferencesImpl( 5402): Couldn't rename file /data/data/com.google.android.music/shared_prefs/store.preferences.xml to backup file /data/data/com.google.android.music/shared_prefs/store.preferences.xml.bak
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5602): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac,
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,D/DFPI.PIReciver( 5532): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/ActivityManager(  958): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/DFPI.ApkInstallService( 5532): onHandleIntent
I/DFPI.ApkInstallService( 5532): Media Scan Finished Case 
,D/DFPI.ApkInstallService( 5532): check CID = HTC__102,
I/ActivityManager(  958): Resuming delayed broadcast
I/SoundPicker( 5602): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
I/DFPI.ApkInstallService( 5532): There is no Demo.apk in sd card or phone storage
V/SoundPicker( 5602): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5602): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5602): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5602): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5602): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5602): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5602): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5602): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5602): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5602): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5602): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5602): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5602): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5602): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5602): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5602): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5602): TurnFileToMediaUriService [checkFileExistence]
E/SQLiteDatabase(  958): Failed to open database '/data/data/com.htc.checkinprovider/databases/htcCheckin.db'.
E/SQLiteDatabase(  958): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(  958): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(  958): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase(  958): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase(  958): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase(  958): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase(  958): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.j,ava:177)
E/SQLiteDatabase(  958): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase(  958): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase(  958): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase(  958): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase(  958): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(  958): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(  958): 	at com.htc.checkinprovider.htcCheckinProvider.query(htcCheckinProvider.java:335)
E/SQLiteDatabase(  958): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase(  958): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase(  958): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
E/SQLiteDatabase(  958): 	at android.os.Binder.execTransact(Binder.java:454)
D/RingtoneManager( 5602): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
E/SQLiteOpenHelper(  958): Couldn't open htcCheckin.db for writing (will try read-only):
E/SQLiteOpenHelper(  958): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(  958): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(  958): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteOpenHelper(  958): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteOpenHelper(  958): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper(  958): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper(  958): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper(  958): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteOpenHelper(  958): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteOpenHelper(  958): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteOpenHelper(  958): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteOpenHelper(  958): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(  958): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(  958): 	at com.htc.checkinprovider.htcCheckinProvider.query(htcCheckinProvider.java:335)
E/SQLiteOpenHelper(  958): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteOpenHelper(  958): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteOpenHelper(  958): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
E/SQLiteOpenHelper(  958): 	at android.os.Binder.execTransact(Binder.java:454)
W/SQLiteOpenHelper(  958): Opened htcCheckin.db in read-only mode
,I/SoundPicker( 5602): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
E/SQLiteDatabase( 5402): Failed to open database '/data/data/com.google.android.music/databases/music.db'.
E/SQLiteDatabase( 5402): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5402): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5402): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 5402): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 5402): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5402): 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5402): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5402): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5402): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5402): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5402): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 5402): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 5402): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5402): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5402): 	at com.google.android.music.store.Store.getDatabase(Store.java:287)
E/SQLiteDatabase( 5402): 	at com.google.android.music.store.BaseStore.beginRead(BaseStore.java:28)
E/SQLiteDatabase( 5402): 	at com.google.android.music.store.Store.createDatabase(Store.java:262)
E/SQLiteDatabase( 5402): 	at com.google.android.music.store.MediaStoreImporter.doImport(MediaStoreImporter.java:220)
E/SQLiteDatabase( 5402): 	at com.google.android.music.store.Store.importMediaStore(Store.java:10438)
E/SQLiteDatabase( 5402): 	at com.google.android.music.store.MediaStoreImportService.importMediaStore(MediaStoreImportService.java:75)
E/SQLiteDatabase( 5402): 	at com.google.android.music.store.MediaStoreImportService.access$100(MediaStoreImportService.java:34)
E/SQLiteDatabase( 5402): 	at com.google.android.music.store.MediaStoreImportService$4.run(MediaStoreImportService.java:140)
E/SQLiteDatabase( 5402): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 5402): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 5402): 	at com.google.android.music.utils.LoggableHandler.dispatchMessage(LoggableHandler.java:82)
E/SQLiteDatabase( 5402): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 5402): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5602): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
I/SoundPicker( 5602): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
I/SoundPicker( 5602): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 5602): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
E/AndroidRuntime( 5402): FATAL EXCEPTION: MediaStoreImportService
E/AndroidRuntime( 5402): Process: com.google.android.music:main, PID: 5402
E/AndroidRuntime( 5402): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5402): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5402): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 5402): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 5402): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5402): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5402): 	at android.database.sqlite.SQLiteConnectionPool.ope,n(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5402): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 5402): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 5402): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 5402): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 5402): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 5402): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 5402): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 5402): 	at com.google.android.music.store.Store.getDatabase(Store.java:287)
E/AndroidRuntime( 5402): 	at com.google.android.music.store.BaseStore.beginRead(BaseStore.java:28)
E/AndroidRuntime( 5402): 	at com.google.android.music.store.Store.createDatabase(Store.java:262)
E/AndroidRuntime( 5402): 	at com.google.android.music.store.MediaStoreImporter.doImport(MediaStoreImporter.java:220)
E/AndroidRuntime( 5402): 	at com.google.android.music.store.Store.importMediaStore(Store.java:10438)
E/AndroidRuntime( 5402): 	at com.google.android.music.store.MediaStoreImportService.importMediaStore(MediaStoreImportService.java:75)
E/AndroidRuntime( 5402): 	at com.google.android.music.store.MediaStoreImportService.access$100(MediaStoreImportService.java:34)
E/AndroidRuntime( 5402): 	at com.google.android.music.store.MediaStoreImportService$4.run(MediaStoreImportService.java:140)
E/AndroidRuntime( 5402): 	at android.os.Handler.handleCallback(Handler.java:739)
E/AndroidRuntime( 5402): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 5402): 	at com.google.android.music.utils.LoggableHandler.dispatchMessage(LoggableHandler.java:82)
E/AndroidRuntime( 5402): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 5402): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5602): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
E/ActivityManager(  958): App crashed! Process: com.google.android.music:main
,I/SoundPicker( 5602): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
E/DropBoxManagerService(  958): Can't write: system_app_crash
E/DropBoxManagerService(  958): java.io.FileNotFoundException: /data/system/dropbox/drop116.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  958): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  958): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  958): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  958): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  958): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  958): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  958): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  958): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  958): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  958): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  958): 	... 5 more
,I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5602): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,E/UpdaterAPK | FOTASettings( 5628): Can't set key backup_uri_string
E/UpdaterAPK | FOTASettings( 5628): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:823)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:480)
E/UpdaterAPK | FOTASettings( 5628): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
E/UpdaterAPK | FOTASettings( 5628): 	at android.content.ContentResolver.update(ContentResolver.java:1354)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:296)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:199)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:180)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:70)
E/UpdaterAPK | FOTASettings( 5628): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/UpdaterAPK | FOTASettings( 5628): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/UpdaterAPK | FOTASettings( 5628): 	at android.os.Looper.loop(Looper.java:155)
E/UpdaterAPK | FOTASettings( 5628): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/UpdaterAPK | FOTASettings( 5628): Can't set key download_sdcard
E/UpdaterAPK | FOTASettings( 5628): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:823)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:480)
E/UpdaterAPK | FOTASettings( 5628): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
E/UpdaterAPK | FOTASettings( 5628): 	at android.content.ContentResolver.update(ContentResolver.java:1354)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:296)
E/Upda,terAPK | FOTASettings( 5628): 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:199)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.db.FOTASettings.putBoolean(FOTASettings.java:280)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:181)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:70)
E/UpdaterAPK | FOTASettings( 5628): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/UpdaterAPK | FOTASettings( 5628): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/UpdaterAPK | FOTASettings( 5628): 	at android.os.Looper.loop(Looper.java:155)
E/UpdaterAPK | FOTASettings( 5628): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/UpdaterAPK | FOTASettings( 5628): Can't set key fota_prompt_version
E/UpdaterAPK | FOTASettings( 5628): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:823)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:480)
E/UpdaterAPK | FOTASettings( 5628): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
E/UpdaterAPK | FOTASettings( 5628): 	at android.content.ContentResolver.update(ContentResolver.java:1354)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:296)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:199)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:182)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:70)
E/UpdaterAPK | FOTASettings( 5628): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/UpdaterAPK | FOTASettings( 5628): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/UpdaterAPK | FOTASettings( 5628): 	at android.os.Looper.loop(Looper.java:155)
E/UpdaterAPK | FOTASettings( 5628): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/UpdaterAPK | FOTASettings( 5628): Can't set key fota_prompt_feature
E/UpdaterAPK | FOTASettings( 5628): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLi,teConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:823)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:480)
E/UpdaterAPK | FOTASettings( 5628): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
E/UpdaterAPK | FOTASettings( 5628): 	at android.content.ContentResolver.update(ContentResolver.java:1354)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:296)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:199)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:183)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:70)
E/UpdaterAPK | FOTASettings( 5628): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/UpdaterAPK | FOTASettings( 5628): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/UpdaterAPK | FOTASettings( 5628): 	at android.os.Looper.loop(Looper.java:155)
E/UpdaterAPK | FOTASettings( 5628): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/StatusBarManagerService(  958): setSystemUiVisibility(0xc0000000)
E/UpdaterAPK | FOTASettings( 5628): Can't set key fota_prompt_size
E/UpdaterAPK | FOTASettings( 5628): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:823)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:480)
E/UpdaterAPK | FOTASettings( 5628): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
E/UpdaterAPK | FOTASettings( 5628): 	at android.content.ContentResolver.update(ContentResolver.java:1354)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:296)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:199)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:184)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:70)
E/UpdaterAPK | FOTASettings( 5628): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/UpdaterAPK | FOTASettings( 5628): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/UpdaterAPK | FOTASettings( 5628): 	at android.os.Looper.loop(Looper.java:155)
E/UpdaterAPK | FOTASettings( 5628): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/StatusBarManagerService(  958): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
E/UpdaterAPK | FOTASettings( 5628): Can't set key fota_force_update
E/UpdaterAPK | FOTASettings( 5628): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:823)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:480)
E/UpdaterAPK | FOTASettings( 5628): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
E/UpdaterAPK | FOTASettings( 5628): 	at android.content.ContentResolver.update(ContentResolver.java:1354)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:296)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:199)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:185)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:70)
E/UpdaterAPK | FOTASettings( 5628): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/UpdaterAPK | FOTASettings( 5628): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/UpdaterAPK | FOTASettings( 5628): 	at android.os.Looper.loop(Looper.java:155)
E/UpdaterAPK | FOTASettings( 5628): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/StatusBarManagerService(  958): hiding MENU key
E/UpdaterAPK | FOTASettings( 5628): Can't set key fota_notify_download
E/UpdaterAPK | FOTASettings( 5628): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:823)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:480)
E/UpdaterAPK | FOTASettings( 5628): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
E/UpdaterAPK | FOTASettings( 5628): 	at android.content.ContentResolver.update(ContentResolver.java:1354)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:296)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:199)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.db.FOTASettings.putBoolean(FOTASettings.java:280)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:186)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:70)
E/UpdaterAPK | FOTASettings( 5628): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/UpdaterAPK | FOTASettings( 5628): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/UpdaterAPK | FOTASettings( 5628): 	at android.os.Looper.loop(Looper.java:155)
E/UpdaterAPK | FOTASettings( 5628): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/UpdaterAPK | FOTASettings( 5628): Can't set key fota_need_token
E/UpdaterAPK | FOTASettings( 5628): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:823)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:480)
E/UpdaterAPK | FOTASettings( 5628): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
E/UpdaterAPK | FOTASettings( 5628): 	at android.content.ContentResolver.update(ContentResolver.java:1354)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:296)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:199)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.db.FOTASettings.putBoolean(FOTASettings.java:280)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:189)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:70)
E/UpdaterAPK | FOTASettings( 5628): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/UpdaterAPK | FOTASettings( 5628): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/UpdaterAPK | FOTASettings( 5628): 	at android.os.Looper.loop(Looper.java:155)
E/UpdaterAPK | FOTASettings( 5628): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/UpdaterAPK | FOTASettings( 5628): Can't set key fota_reserve_data_size
E/UpdaterAPK | FOTASettings( 5628): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:823)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:480)
E/UpdaterAPK | FOTASettings( 5628): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
E/UpdaterAPK | FOTASettings( 5628): 	at android.content.ContentResolver.update(ContentResolver.java:1354)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:296)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:199)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.db.FOTASettings.putInt(FOTASettings.java:239)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:194)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:70)
E/UpdaterAPK | FOTASettings( 5628): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/UpdaterAPK | FOTASettings( 5628): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/UpdaterAPK | FOTASettings( 5628): 	at android.os.Looper.loop(Looper.java:155)
E/UpdaterAPK | FOTASettings( 5628): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/UpdaterAPK | FOTASettings( 5628): Can't set key fota_package_download_via_wifi
E/UpdaterAPK | FOTASettings( 5628): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:823)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:480)
E/UpdaterAPK | FOTASettings( 5628): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
E/UpdaterAPK | FOTASettings( 5628): 	at android.content.ContentResolver.update(ContentResolver.java:1354)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:296)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:199)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.db.FOTASettings.putBoolean(FOTASettings.java:280)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:200)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:70)
E/UpdaterAPK | FOTASettings( 5628): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/UpdaterAPK | FOTASettings( 5628): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/UpdaterAPK | FOTASettings( 5628): 	at android.os.Looper.loop(Looper.java:155)
E/UpdaterAPK | FOTASettings( 5628): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/UpdaterAPK | FOTASettings( 5628): Can't set key fota_prompt_message
E/UpdaterAPK | FOTASettings( 5628): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:823)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:480)
E/UpdaterAPK | FOTASettings( 5628): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
E/UpdaterAPK | FOTASettings( 5628): 	at android.content.ContentResolver.update(ContentResolver.java:1354)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:296)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:199)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:202)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:70)
E/UpdaterAPK | FOTASettings( 5628): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/UpdaterAPK | FOTASettings( 5628): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/UpdaterAPK | FOTASettings( 5628): 	at android.os.Looper.loop(Looper.java:155)
E/UpdaterAPK | FOTASettings( 5628): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/SoundPicker( 5602): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5602): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
I/SoundPicker( 5602): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
I/SoundPicker( 5602): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
I/ActionCombine( 5628): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
I/SoundPicker( 5602): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/SoundPicker( 5602): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
E/UpdaterAPK | FOTASettings( 5628): Can't set key fota_optional
E/UpdaterAPK | FOTASettings( 5628): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:823)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
E/UpdaterAPK | FOTASettings( 5628): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:480)
E/UpdaterAPK | FOTASettings( 5628): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
E/UpdaterAPK | FOTASettings( 5628): 	at android.content.ContentResolver.update(ContentResolver.java:1354)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:296)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:199)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:282)
E/UpdaterAPK | FOTASettings( 5628): 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:70)
E/UpdaterAPK | FOTASettings( 5628): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/UpdaterAPK | FOTASettings( 5628): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/UpdaterAPK | FOTASettings( 5628): 	at android.os.Looper.loop(Looper.java:155)
E/UpdaterAPK | FOTASettings( 5628): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
I/SoundPicker( 5602): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
D/DotMatrix( 1301): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/RemoteViews( 1215): setHTCTheme(com.htc.updater,true,33751145)
I/SoundPicker( 5602): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5602): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5602): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5602): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5602): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5602): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5602): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5602): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5602): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5602): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5602): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5602): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5602): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5602): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5602): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5602): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5602): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5602): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5602): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
I/SoundPicker( 5602): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5602): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
I/RemoteViews( 1215): apply : com.htc.updater 1 15 3 36
,I/SoundPicker( 5602): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/Prism.ItemManager( 5269): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 5269): loadItems() com.htc.launcher.pageview.WidgetManager@1507f941 +
I/Prism.WidgetManager( 5269): onLoadItems() +
,I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5602): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5602): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/Prism.ItemManager( 1513): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1513): loadItems() com.htc.launcher.pageview.WidgetManager@2d5d896a +
I/Prism.WidgetManager( 1513): onLoadItems() +
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5602): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
,I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/CalendarProvider2( 5500): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
W/ContentResolver( 5500): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/SoundPicker( 5602): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,D/DFPI.PIReciver( 5532): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,D/RingtoneManager( 5602): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/DFPI.ApkInstallService( 5532): onHandleIntent,
I/DFPI.ApkInstallService( 5532): Media Scan Finished Case 
I/SoundPicker( 5602): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,D/DFPI.ApkInstallService( 5532): check CID = HTC__102
,I/DFPI.ApkInstallService( 5532): There is no Demo.apk in sd card or phone storage
,I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5602): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
I/SoundPicker( 5602): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 5602): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
W/ResourcesManager( 5269): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/SoundPicker( 5602): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,D/FindExtension( 1215): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
D/TelephonyReceiver( 1452): bind: false
D/TelephonyReceiver( 1452): switchBindHtcMsgCursor: null
,D/DFPI.PIReciver( 5532): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/ThreadedRenderer( 1215): Defer allocateBuffers to drawing time
,I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/DFPI.ApkInstallService( 5532): onHandleIntent
I/DFPI.ApkInstallService( 5532): Media Scan Finished Case 
,D/DFPI.ApkInstallService( 5532): check CID = HTC__102
I/DFPI.ApkInstallService( 5532): There is no Demo.apk in sd card or phone storage
,I/SoundPicker( 5602): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5602): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5602): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5602): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5602): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5602): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5602): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5602): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5602): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5602): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5602): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5602): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5602): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5602): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5602): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5602): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5602): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5602): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5602): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5602): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5602): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5602): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5602): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,D/DFPI.PIReciver( 5532): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5602): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac,
,I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac,
D/RingtoneManager( 5602): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
I/DFPI.ApkInstallService( 5532): onHandleIntent
I/DFPI.ApkInstallService( 5532): Media Scan Finished Case 
D/DFPI.ApkInstallService( 5532): check CID = HTC__102
I/DFPI.ApkInstallService( 5532): There is no Demo.apk in sd card or phone storage
,I/SoundPicker( 5602): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5602): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 5602): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5602): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5602): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5602): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac,
,I/SoundPicker( 5602): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac

```
