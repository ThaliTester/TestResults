#### Test 502422853393492_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
I/art     (  955): Explicit concurrent mark sweep GC freed 11923(613KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 15MB/23MB, paused 1.351ms total 157.416ms
D/LocationManagerService(  955): getProviders()=[passive]
--------- beginning of system
I/ActivityManager(  955): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=4557 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a
I/PackageManager(  955):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.googlequicksearchbox.SearchActivity, state=1, flag=1, pid=4519, uid=10085, userID:0
I/PackageManager(  955):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.googlequicksearchbox.VoiceSearchActivity, state=1, flag=1, pid=4519, uid=10085, userID:0
I/PackageManager(  955):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.search.core.icingsync.ApplicationLaunchReceiver, state=1, flag=1, pid=4519, uid=10085, userID:0
W/BroadcastQueue(  955): Permission Denial: receiving Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 (has extras) } to pl.k2.droidoaudioteka/.ford.AppLinkReceiver requires android.permission.RECEIVE_BOOT_COMPLETED due to sender null (uid 1000)
E/WifiTrafficPoller(  955): ADD_CLIENT: 6
D/WifiService(  955): New client listening to asynchronous messages
I/ActivityManager(  955): Start proc com.htc.club for broadcast com.htc.club/com.mcrm.autonotification.Autostart: pid=4594 uid=10181 gids={50181, 9997, 3003, 1028, 1015} abi=arm64-v8a
I/ActivityManager(  955): Killing 3915:com.google.android.configupdater/u0a98 (adj 15): empty #17
D/Process (  955): killProcessQuiet, pid=3915
D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
I/VelvetNetworkClient( 4519): Network connection not availble
I/ActivityManager(  955): Recipient 3915
I/ActivityManager(  955): Killing 4003:com.htc.backupreset/1000 (adj 15): empty #17
D/Process (  955): killProcessQuiet, pid=4003
D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ActivityManager(  955): Recipient 4003
D/GCM     ( 1867): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 1867): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 4261): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/ActivityManager(  955): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=4617 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
I/PackageManager(  955):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4261, uid=10024, userID:0
W/ResourcesManager( 4617): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
D/TelephUtils( 1457): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 92
W/ResourcesManager( 4617): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/AccFlag ( 1457): sku_id=118
I/MultiDex( 4617): VM with version 2.1.0 has multidex support
I/MultiDex( 4617): install
I/MultiDex( 4617): VM has multidex support, MultiDex support library is disabled.
I/ActivityManager(  955): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=4643 uid=10035 gids={50035, 9997} abi=arm64-v8a
D/LocationInitializer( 4261): Restart initialization of location
D/TelephUtils( 1457): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 88
D/AccFlag ( 1457): sku_id=118
V/JNIHelp ( 4617): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/TelephUtils( 1457): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 50
D/AccFlag ( 1457): sku_id=118
D/TelephUtils( 1457): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 49
D/AccFlag ( 1457): sku_id=118
W/ActivityThread( 4617): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 4617): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@30be681: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4617): Installed default security provider GmsCore_OpenSSL
D/WearableService( 4617): callingUid 10024, callindPid: 4617
I/ActivityManager(  955): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=4667 uid=10076 gids={50076, 9997} abi=arm64-v8a
D/Process (  955): killProcessQuiet, pid=4031
I/ActivityManager(  955): Killing 4031:com.htc.htccupd/u0a13 (adj 15): empty #17
D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  955): Recipient 4031
D/SMSBackup( 4667): Got a database change event
E/MDM     ( 1783): [135] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
I/ActivityManager(  955): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=4690 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a
D/Process (  955): killProcessQuiet, pid=4078
I/ActivityManager(  955): Killing 4078:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/art     (  434): Explicit concurrent mark sweep GC freed 8671(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 178us total 23.115ms
I/art     (  434): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 146us total 19.450ms
I/art     (  434): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 119us total 18.907ms
I/ActivityManager(  955): Recipient 4078
E/cutils-trace( 4688): Error opening trace file: Permission denied (13)
I/ImageRamCache( 4690): create image Cache, size: 31457280.
I/ImageRamCache( 4690): [resize] ImageRamCache resized to: 30Mb.
I/ImageRamCache( 4690): create image Cache, size: 31457280.
I/FeedSettings( 4690): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 4690): GroupBudget 0.500000 0.380000
I/FeedSettings( 4690): GroupBudget 60 45 15
D/CustomizationManager( 4688): ====startRecUseTime====
D/htc.customization.log.level( 4688):  is 
W/CustomizationLogLevel( 4688): Level value is invalid, use default level 2
I/Prism.ExternalStringMa_( 4690): changeLocale(): en_GB
I/Prism.AllAppsOptionsMa_( 4690): loadSortType() with Custom
I/Prism.AllAppsOptionsMa_( 4690): loadGridSize() with Alternative
D/CustomHighlightReceiver( 4690): [custom highlight] onReceive
D/CustomHighlightService( 4690): [custom highlight] onHandleIntent
D/NewsDB  ( 4690): set custom highlight []
I/ActivityManager(  955): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=4731 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
D/CustomizationManager( 4688):  Read ACC file spent 0.036 (s)
D/CIDMapFileReader( 4688): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4688): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4688): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4688): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4688): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4688): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4688): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4688): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 4688): Parsing tag category name = system
I/CustomizationCIDLoader( 4688): Parsing tag category name = application
I/CustomizationCIDLoader( 4688): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4688): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4688): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4688): Parsing tag category name = Settings
I/CustomizationCIDLoader( 4688): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4688): add string-array item, value = 42507
I/CustomizationCIDLoader( 4688): add string-array item, value = 21902
I/CustomizationCIDLoader( 4688): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 4688): add string-array item, value = 23420
I/CustomizationCIDLoader( 4688): add string-array item, value = 22299
I/CustomizationCIDLoader( 4688): add string-array item, value = 24002
I/CustomizationCIDLoader( 4688): add string-array item, value = 23210
I/CustomizationCIDLoader( 4688): add string-array item, value = 23205
I/CustomizationCIDLoader( 4688): add string-array item, value = 23806
I/CustomizationCIDLoader( 4688): add string-array item, value = 23430
I/CustomizationCIDLoader( 4688): add string-array item, value = 23408
I/CustomizationCIDLoader( 4688): add string-array item, value = 27205
I/CustomizationCIDLoader( 4688): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 4688): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 4688): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 4688): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 4688): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 4688): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 4688): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 4688): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 4688): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 4688): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 4688): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 4688): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 4688):  Read CID file spent 0.080 (s)
D/CustomizationManager( 4688):  All configurations done spent 0.081 (s)
D/CustomHighlightService( 4690): [custom highlight] set tags 
D/Process (  955): killProcessQuiet, pid=4121
I/ActivityManager(  955): Killing 4121:com.android.settings:remote/1000 (adj 15): empty #17
D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ActivityManager(  955): Recipient 4121
I/ActivityManager(  955): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 pid 4688 on display 0
D/PMS     (  955): acquireHCC(16d50706): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 955 1000 null
D/PMS     (  955): acquireHCC(157c01c7): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 955 1000 null
W/asset   (  955): Copying FileAsset 0x558219d4c0 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/PMS     (  955): acquireWL(72a8d92): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 955 1000 null
I/AnimationUtil(  955): isHTCRecent(HelloWorld/Recent screens.)/5
I/FeedHostManager( 1515): [onPause]
I/FeedProviderManager( 1515): onPause
I/FeedHostManager( 1515): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@14730704
D/MessagingShortcutReceiver( 3723): keep hiding shortcut bubble
I/SocialFeedProvider( 1515): +onPause
I/SocialFeedProvider( 1515): -onPause
D/MessagingShortcut( 3723): updateMsgShortcut, msg count> -1
D/MessagingShortcut( 3723): After query: 0
D/MessagingShortcut( 3723): mPresentUnreadCount: -1
D/MessageUtils( 3723): [getShortcut] com.htc.sense.mms.ui.ConversationList, false
D/MessagingShortcut( 3723): setMsgShortcutDrawable> 0, false
I/ActivityManager(  955): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4756 uid=10373 gids={50373, 9997, 3003, 3001, 3002} abi=armeabi-v7a
W/HtcSystemUPManager(  955): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
D/MessagingShortcut( 3723): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1304): [EventService] reorderNotification, total:0
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/art     (  435): Explicit concurrent mark sweep GC freed 8677(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 266us total 17.714ms
I/ActivityManager(  955): Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=4776 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a
I/art     (  435): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 225us total 14.588ms
I/art     (  435): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 243us total 14.436ms
W/asset   ( 4756): Copying FileAsset 0xabe726a8 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/ActivityManager(  955): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=4798 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
W/ResourcesManager( 4776): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/StatusBarManagerService(  955): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  955): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  955): hiding MENU key
I/TrimMemoryManager( 1515): [trimMemory] 20
D/TodoTaskshortcut( 4776): update TASK shortcut>
D/PMS     (  955): acquireWL(31b1151): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4776 10069 null
D/PMS     (  955): acquireWL(7733db6): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4776 10069 null
D/PMS     (  955): releaseWL(31b1151): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
E/TodoTaskNotifyService( 4776): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
W/System.err( 4776): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
W/System.err( 4776): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4776): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4776): 	at android.os.Looper.loop(Looper.java:155)
W/System.err( 4776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  955): releaseWL(7733db6): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
W/NotifyReceiver( 4776): stopSelfResult true
D/MdScBoot( 4731): [f43.1.] 30@-145928 -> 40
D/MdScBootUi( 4731): [f43.1.2.] boot 118
I/ActivityManager(  955): Killing 4145:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
D/Process (  955): killProcessQuiet, pid=4145
D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/MdScSimSt( 4731): [f43.1.2.] qry 118: 0+1 running 0
I/WebViewFactory( 4756): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
D/PMS     (  955): acquireWL(2e6be224): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1867 10024 WorkSource{10024 com.google.android.gms}
I/ActivityManager(  955): Recipient 4145
D/PMS     (  955): releaseWL(15a27bc9): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 null
D/PMS     (  955): releaseWL(2e6be224): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  955): acquireWL(3596fc90): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1867 10024 WorkSource{10024 com.google.android.gms}
D/libc    ( 1867): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1867): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1867): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1867): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1867): [NET] android_getaddrinfo_proxy+
D/libc    ( 1867): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  400): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  400): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1867): [NET] android_getaddrinfo_proxy-, NODATA
D/PMS     (  955): releaseWL(3596fc90): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
D/MtpReceiver( 3680): [MTP][handleUsbStateAsync]+
D/MtpReceiver( 3680): [MTP][handleUsbStateAsync]1:1-
D/MtpReceiver( 3680): [MTP][handleUsbState]+
I/ActivityManager(  955): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4832 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=arm64-v8a
I/ActivityManager(  955): Killing 4168:com.android.smith/1000 (adj 15): empty #17
D/Process (  955): killProcessQuiet, pid=4168
D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
I/LibraryLoader( 4756): Time to load native libraries: 10 ms (timestamps 7171-7181)
I/LibraryLoader( 4756): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 4756): Binding Chromium to main looper Looper (main, tid 1) {1a5bd63e}
I/LibraryLoader( 4756): Expected native library version number "",actual native library version number ""
I/chromium( 4756): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4756): Initializing chromium process, singleProcess=true
I/ActivityManager(  955): Recipient 4168
W/art     ( 4756): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 4756): ApplicationContext is null in ApplicationStatus
D/Process (  955): killProcessQuiet, pid=4099
I/ActivityManager(  955): Killing 4099:com.android.settings/1000 (adj 15): empty #17
D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
W/chromium( 4756): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 4756): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 4756): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4756): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 4756): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 4756): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 4756): Build Date: 03/09/15 Mon
I/Adreno-EGL( 4756): Local Branch: 
I/Adreno-EGL( 4756): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 4756): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 4756):                  d74aa161a12b9c6fc6332151
I/ActivityManager(  955): Recipient 4099
D/MtpReceiver( 3680): [MTP][scanExternalVolumeIfNeed] scan external volume
D/MtpService( 3680): updating state; isCurrentUser=true, mMtpLocked=false
D/SyncApplication( 4832): Loading default preferences
D/MtpReceiver( 3680): [MTP][handleUsbState]-
D/MtpReceiver( 3680): [MTP][handleMessage]-
D/MtpDatabase( 3680): TotalSize=1886532,MediaCacheLimit=6000
D/MtpService( 3680): [isMtpConnected] connected: true
W/Resources( 4832): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
D/BluetoothManagerService(  955): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  955): java.lang.Throwable: stack dump
W/System.err(  955): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  955): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  955): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  955): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  955): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f248066:true
D/BluetoothAdapter( 4756): 255531082: getState() :  mService = null. Returning STATE_OFF
D/WifiService(  955): New client listening to asynchronous messages
E/WifiTrafficPoller(  955): ADD_CLIENT: 7
D/SyncApplication( 4832): Overriding preferences with custom values
D/ContactMessageStore( 1457): MSG_NOTIFY_CS_TO_SYNC >>
D/ContactMessageStore( 1457): MSG_NOTIFY_CS_TO_SYNC <<
W/art     ( 4756): Attempt to remove local handle scope entry from IRT, ignoring
D/SyncApplication( 4832): Updating preferences succeeded
E/SyncApplication( 4832): Application created.
E/MediaScannerService( 3680): [onStartCommand] --- Should not be here, redirect request. ----
E/MediaScannerService( 3680): [handleMessage] --- Should not be here, ignore request. ----
W/AwContents( 4756): onDetachedFromWindow called when already detached. Ignoring
W/VolumeInfo( 4832): Unable to read mount points
W/VolumeInfo( 4832): java.io.FileNotFoundException: /etc/vold.fstab: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 4832): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/VolumeInfo( 4832): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/VolumeInfo( 4832): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
W/VolumeInfo( 4832): 	at java.io.FileReader.<init>(FileReader.java:66)
W/VolumeInfo( 4832): 	at com.nero.android.common.VolumeInfo.getVolumeMountPoints(VolumeInfo.java:194)
W/VolumeInfo( 4832): 	at com.nero.android.common.VolumeInfo.getVolumes(VolumeInfo.java:153)
W/VolumeInfo( 4832): 	at com.nero.android.common.VolumeInfo.initializeVolumeIDs(VolumeInfo.java:474)
W/VolumeInfo( 4832): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:51)
W/VolumeInfo( 4832): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:1)
W/VolumeInfo( 4832): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/VolumeInfo( 4832): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/VolumeInfo( 4832): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/VolumeInfo( 4832): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/VolumeInfo( 4832): 	at java.lang.Thread.run(Thread.java:818)
W/VolumeInfo( 4832): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 4832): 	at libcore.io.Posix.open(Native Method)
W/VolumeInfo( 4832): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/VolumeInfo( 4832): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/VolumeInfo( 4832): 	... 13 more
V/VolumeInfo( 4832): Found 0 mount point(s)
V/VolumeInfo( 4832): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
I/CalendarDefines( 4832): getNewCalendarAuthority()...
I/PackageManager(  955):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=4832, uid=10005, userID:0
D/VolumeInfo( 4832): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
W/PackageManager(  955): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  955):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=4832, uid=10005, userID:0
W/PackageManager(  955): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
D/SyncApplication( 4832): enableAppOperation()+
D/SyncApplication( 4832): enableAppOperation()-
D/VolumeInfo( 4832): Read the volume-id from the sd card: {9B5E872B-8520-47C6-8BD3-3081C2E38355}
W/VolumeInfo( 4832): Can not create volume ID for unmounted volume null
D/HTCUtilities( 4832): isNeorSinged() + 
D/SystemWebViewEngine( 4756): CordovaWebView is running on device made by: HTC
D/HTCUtilities( 4832): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
D/HTCUtilities( 4832): isNeorSinged() return false
D/CDMountReceiver( 4832): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
D/CDMountReceiver( 4832): USB connected to PC
W/art     ( 4756): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4756): Attempt to remove local handle scope entry from IRT, ignoring
D/FOTAReceiver( 4832): onReceive() enter 
D/FOTAReceiver( 4832): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
I/ActivityManager(  955): Start proc com.android.settings for broadcast com.android.settings/.NSReceiver: pid=4885 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
I/ActivityManager(  955): Killing 3972:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  955): killProcessQuiet, pid=3972
D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
E/MediaScannerServiceEx( 3680): [getStorageMaskIdFromPath] path is null
D/MediaScannerServiceEx( 3680): [ServiceHandler][handleMessage] , action: null, Id: 0, path: /storage/emulated/0
D/MediaScannerServiceEx( 3680): [handleExternalVolume] ext storage
D/MediaProviderUtils( 3680): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3680): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3680): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3680): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
D/MediaScannerServiceEx( 3680): [AliveExtStorageRows]+65537, 11223344
D/MediaProvider( 3680): [update][5]#0#
D/MediaProvider( 3680): [update][1]#0#
D/MediaProvider( 3680): [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted
D/MtpService( 3680): [sendStorageAdded] Already send to MTP: /storage/emulated/0
D/MediaProvider( 3680): [update][6]#1#
D/MediaScannerServiceEx( 3680): [AliveExtStorageRows]-0, 0
D/PMS     (  955): acquireWL(24ab4284): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 3680 10017 null
I/ActivityManager(  955): Recipient 3972
D/MediaScanner( 3680): =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1
W/chromium( 4756): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 4885): -onCreate()
V/Settings:HtcSettingsApplication( 4885): [4885/4885] onCreate()
D/TetherSettings( 4885): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4885): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4885): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4885): Cust_ConnectToPC   : spcsc>false
D/        ( 4885): Cust_ConnectToPC   : IPT>true
D/        ( 4885): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 4885): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4885): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4885): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4885): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
D/SmartNS_Utility( 4885): usb_cable_connect = 1
D/SmartNS_Utility( 4885): usb_denied = 0
D/FindExtension( 4756): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/SmartNS_NSReceiver( 4885): locked:falsesecurity:falseisLocked:false
D/SmartNS_NSReceiver( 4885): USB = true hasTethered = false isNSOpening: false
I/PSReceiver( 4885): onReceive:com.htc.intent.action.USB_CONNECT2PC
W/ContextImpl( 4885): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2712 
I/SmartNS_PSService( 4885): onReceive:com.htc.intent.action.USB_CONNECT2PC
W/Settings( 4885): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 4885):  defaultType:0
I/SmartNS_PSService( 4885): fail notificaiton:false
D/SmartNS_Utility( 4885): usb_cable_connect = 1
D/SmartNS_Utility( 4885): usb_denied = 0
I/SmartNS_PSService( 4885): usb notificaiton:true
E/WifiStateMachine(  955): WiFiDisplay: getWifidisplayApEnabled=false
I/ActivityManager(  955): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=4912 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
I/ActionCombine( 4885): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
D/SmartNS_Utility( 4885): usb_cable_connect = 1
D/SmartNS_Utility( 4885): usb_denied = 0
I/SmartNS_PSService( 4885): usb notificaiton:true
D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
E/WifiStateMachine(  955): WiFiDisplay: getWifidisplayApEnabled=false
I/RemoteViews( 1222): reapply : com.android.settings 1 36
D/SmartNS_Utility( 4885): usb_cable_connect = 1
D/SmartNS_Utility( 4885): usb_denied = 0
I/SmartNS_PSService( 4885): KeyGuard locked:falseKeyGuard is secured:false
D/SmartNS_PSService( 4885): USB Plugged, Set USBPlugged=  truePSenabled:false
I/ActivityManager(  955): Killing 4235:com.google.android.gms:car/u0a24 (adj 15): empty #17
D/Process (  955): killProcessQuiet, pid=4235
D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/InputMethodManager( 4756): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@3f6ee008, mServedView=org.apache.cordova.engine.SystemWebView{18a803a1 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@202ac9c6
I/InputMethodManagerService(  955): Disable input method client, pid=1515
D/StatusBarManagerService(  955): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  955): Enable input method client, pid=4756
W/BindingManager( 4756): Cannot call determinedVisibility() - never saw a connection for the pid: 4756
I/chromium( 4756): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
I/art     (  955): Explicit concurrent mark sweep GC freed 11477(570KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 15MB/23MB, paused 1.721ms total 146.560ms
I/PhoneStatusBar( 1222): setImeWindowStatus(false,false)
D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/RemoteViews( 1222): reapply : com.android.settings 0 36
W/XT9_C   ( 1347): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1347): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1347): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1347): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/ActivityManager(  955): Recipient 4235
D/PMS     (  955): releaseWL(72a8d92): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
I/ActivityManager(  955): Displayed com.example.hello/.MainActivity: +1s293ms
W/ContextImpl( 4912): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.backupreset.receiver.BackupResetReceiver.onReceive:45 android.app.ActivityThread.handleReceiver:2712 
D/JsMessageQueue( 4756): Set native->JS mode to OnlineEventsBridgeMode
,I/ActivityManager(  955): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=4939 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
,E/AndroidProtocolHandler( 4756): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/ActivityManager(  955): Killing 4191:com.android.vending/u0a72 (adj 15): empty #17
D/Process (  955): killProcessQuiet, pid=4191
D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  955): Recipient 4191,
,W/ResourcesManager( 4939): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/jxcore_app_log( 4756): JniHelper::setJavaVM(0xaad048f8), pthread_self() = -1409133144
D/JX-Cordova( 4756): jxcore cordova android initializing
,W/jxcore-log( 4756): Initializing JXcore engine
W/jxcore-log( 4756): JXcore engine is ready
,W/jxcore-log( 4756): Starting JXcore engine
,I/CalendarProvider2( 4939): Created com.android.providers.calendar.CalendarAlarmManager@26554c9f(com.htc.providers.calendar.HtcCalendarProvider@31a441ec),
,D/CalendarProvider2( 4939): wait start:true
,D/FlexNetS( 4939): updateSvcAllowedInSettings:false,
,D/CalendarProvider2( 4939): wait end:false
,I/ActivityManager(  955): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=4965 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,W/jxcore-log( 4756): Platform android,
W/jxcore-log( 4756): 
W/jxcore-log( 4756): Process ARCH arm
W/jxcore-log( 4756): 
,I/jxcore-log( 4756): JXcore Cordova bridge is ready!,
I/jxcore-log( 4756): 
W/jxcore-log( 4756): JXcore engine is started
,I/ActivityManager(  955): Waited long enough for: ServiceRecord{384a56d7 u0 com.htc.HTCSpeaker/.NGFService}
,W/ContextImpl( 4965): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,E/jxcore-log( 4756): >> HTC-HTC One M8s,
E/jxcore-log( 4756): 
I/jxcore-log( 4756): Total memory 1931808768
I/jxcore-log( 4756): 
I/jxcore-log( 4756): Free memory 83750912,
I/jxcore-log( 4756): 
I/jxcore-log( 4756): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4756): 
I/jxcore-log( 4756): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4756): 
,I/jxcore-log( 4756): userPath [ 'www' ]
I/jxcore-log( 4756): 
,I/jxcore-log( 4756): Size 1080 1776
I/jxcore-log( 4756): 
,I/jxcore-log( 4756): Screen Brightness 142
I/jxcore-log( 4756): 
D/PowerUsageList:PowerUsageHelper( 4965): MY_DEBUG = false
E/jxcore-log( 4756): Dummy Error Log.
E/jxcore-log( 4756): 
D/PMS     (  955): acquireWL(100b8695): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4965 1000 null
,I/ActivityManager(  955): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=4990 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a
,D/PowerUsageService( 4965): repeat time = 1449414897985
,D/WeatherUtility( 1418): Weather sync is On
,D/WSP     ( 1418): [Receiver] auto sync agent, auto sync is enabled, reset schedule
,D/WeatherUtility( 4990): Weather sync is On
,I/PowerUsageList:PowerUsageHelper( 4965): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/Prism.PackageStateRece_( 1515): action: android.intent.action.PACKAGE_ADDED
,I/[PluginManager]RegisterService( 1418): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.example.hello
,I/[PluginManager]RegisterService( 1418): handle notify Blinkfeed plugin client changed
,W/WeatherRequest( 4990): request cur loc, but there is no sys cur
W/Settings( 4990): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActionCombine( 4990): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,D/PowerUsageList:BatterySipperExt( 4965): gen(), null == sipper.uidObj, userId = 0
,I/ActivityManager(  955): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5018 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/RemoteViews( 1515): reapply : com.htc.widget.weatherclock 6 17,
,D/PMS     (  955): releaseHCC(16d50706): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  955): releaseHCC(157c01c7): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,I/DeviceManagement( 5018): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=5018 dbg=false s=true,
,I/DeviceManagement( 5018): PackageUpdateReceiver: vvv Package added: [com.example.hello],
,D/Process (  955): killProcessQuiet, pid=3364
I/ActivityManager(  955): Killing 3364:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  955): Recipient 3364,
,I/HtcModeClient( 3151): handler message = 4011,
,E/HtcModeClient( 3151): Check connection and retry 4 times.
,I/ActivityManager(  955): Killing 4396:com.google.android.youtube/u0a176 (adj 15): empty #17
D/Process (  955): killProcessQuiet, pid=4396
D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/Atfwd_Sendcmd(  475): AtCmdFwd service not published, waiting... retryCnt : 4
,I/ActivityManager(  955): Recipient 4396,
,I/jxcore-log( 4756): getBuffer is called!!!!,
I/jxcore-log( 4756): 
,I/ActivityManager(  955): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=5040 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a,
,I/art     (  434): Explicit concurrent mark sweep GC freed 8657(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 223us total 26.809ms
,I/art     (  434): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 174us total 25.797ms
,D/HtcCupdReceiver(Provider)( 5040):  @@@@@ receive action=android.intent.action.PACKAGE_ADDED
,I/art     (  434): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 149us total 19.033ms
,I/ActivityManager(  955): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5062 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager(  955): Killing 4474:com.google.android.gm/u0a106 (adj 15): empty #17
D/Process (  955): killProcessQuiet, pid=4474,
D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,D/Settings:HtcWirelessFeatureFlags( 4885): id/is att sku: 118/false
,I/CalendarProvider2( 4939): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: },
W/ContentResolver( 4939): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,E/Settings:HtcWrapHeaderInfo( 4885): no such activity!
,D/MediaProvider( 3680): [update][37]#1#
,D/MediaScanner( 3680):  prescan time: 536ms,
D/MediaScanner( 3680):     scan time: 1145ms
D/MediaScanner( 3680): postscan time: 3ms
D/MediaScanner( 3680):    total time: 1684ms
D/MediaScanner( 3680): -----------------------------------------------------------------
D/MediaScanner( 3680): firstscan(media) time: 614ms
D/MediaScanner( 3680): secondscan(non-media) time: 531ms
,D/MediaScanner( 3680):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 1
D/MediaScanner( 3680):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3680):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3680):  [Total]    File(Image+Video+Audio+Others) in database : 1546
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4885): The wrap header doesn't exist in header list.,
,I/ActivityManager(  955): Recipient 4474
,E/Settings:HtcWrapHeaderInfo( 4885): updateDevelopment, bPrefShow = true
,D/MediaProvider( 3680): [delete][19]
,D/MediaProvider( 3680): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
D/MediaProvider( 3680): [recoverParentNodes] - 0
,D/MediaProvider( 3680): [update][4]
D/MediaScannerServiceEx( 3680): [scan] Recover Parent Node is finished!
D/MediaScannerServiceEx( 3680): [updateImage]+
,E/Settings:HtcUmcWidgetEnabler( 4885): isSupportMusicChannel(): false
,D/MediaScannerServiceEx( 3680): [updateImage]-0
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4885): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4885): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4885): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4885): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4885): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4885): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4885): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4885): [supportHomeButton]hasHomeKey      :false,
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4885): [supportHomeButton]support         :false
,D/PMS     (  955): releaseWL(24ab4284): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
,D/MediaScannerServiceEx( 3680): [1] scan finished,
D/MediaProviderUtils( 3680): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3680): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3680): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3680): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #1
W/MediaScannerServiceEx( 3680): Process mounted intent for unmounted storage: /storage/ext_sd
,D/MediaScannerServiceEx( 3680): [disAliveExtStorageRows]+131073
,D/Process (  955): killProcessQuiet, pid=4519
I/ActivityManager(  955): Killing 4519:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/MediaProvider( 3680): [sendStorageAddedIfNeed]: /storage/ext_sd : unmounted
,D/MediaProvider( 3680): [update][7]#1#
,D/MediaProvider( 3680): [update][22]#0#
,D/MediaScannerServiceEx( 3680): [disAliveExtStorageRows]--1, 0
,I/ActivityManager(  955): Recipient 4519,
D/WifiService(  955): Client connection lost with reason: 4
,E/Settings:HtcVoWifiWidgetEnabler( 4885): isSupportVoWifi: null,
I/ActivityManager(  955): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 4885): Failed to find provider info for com.htc.vowifi
,D/MediaProviderUtils( 3680): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3680): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3680): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3680): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #2
W/MediaScannerServiceEx( 3680): Process mounted intent for unmounted storage: /storage/usb
,D/MediaScannerServiceEx( 3680): [disAliveExtStorageRows]+196609
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4885): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 4885): updateDevelopment, bPrefShow = true
,D/MediaProvider( 3680): [sendStorageAddedIfNeed]: /storage/usb : unmounted
,D/MediaProvider( 3680): [update][6]#1#
E/Settings:HtcUmcWidgetEnabler( 4885): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4885): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4885): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4885): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4885): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4885): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4885): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4885): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4885): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4885): [supportHomeButton]support         :false
,V/AlarmManager(  955): sending alarm PendingIntent{8f89076: PendingIntentRecord{3f1da677 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1449413999022, Int=0
,E/Settings:HtcVoWifiWidgetEnabler( 4885): isSupportVoWifi: null
,I/ActivityManager(  955): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 4885): Failed to find provider info for com.htc.vowifi
D/MediaProvider( 3680): [update][24]#0#
,D/MediaScannerServiceEx( 3680): [disAliveExtStorageRows]--1, 0
,I/PackageManager(  955):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=5062, uid=10072, userID:0,
,W/global  ( 5062): [apache-http] Connection GC has been deprecated!,
,D/Finsky  ( 5062): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/global  ( 5062): [apache-http] Connection GC has been deprecated!,
,D/Process (  955): killProcessQuiet, pid=4643
I/ActivityManager(  955): Killing 4643:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17,
D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/global  ( 5062): [apache-http] Connection GC has been deprecated!,
,D/Finsky  ( 5062): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.,
,I/ActivityManager(  955): Recipient 4643
,I/ActivityManager(  955): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5103 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,W/Settings( 5062): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 5062): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PackageManager(  955):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=5062, uid=10072, userID:0
,W/ResourcesManager( 5103): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5103): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.,
,I/MultiDex( 5103): VM with version 2.1.0 has multidex support
,I/MultiDex( 5103): install
I/MultiDex( 5103): VM has multidex support, MultiDex support library is disabled.
,D/Process (  955): killProcessQuiet, pid=4667,
I/ActivityManager(  955): Killing 4667:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  955): Recipient 4667,
,D/Finsky  ( 5062): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5062): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 5062): [1] GmsCoreHelper.cleanupNlp: result=false type=4,
,V/JNIHelp ( 5103): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/ChimeraCfgMgr( 4261): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/PMS     (  955): releaseWL(100b8695): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/ChimeraModuleLdr( 4261): Loading module APK com.google.android.play.games
,D/PackageBroadcastService( 4261): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
,D/Finsky  ( 5062): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.,
,D/PMS     (  955): acquireWL(2066c681): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4261 10024 null
,W/ActivityThread( 5103): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 5103): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@30be681: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5103): Installed default security provider GmsCore_OpenSSL
,I/art     ( 1867): Explicit concurrent mark sweep GC freed 10122(548KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 840us total 45.865ms
,I/ConfigFetchService( 4261): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,D/PMS     (  955): acquireWL(26c01680): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 4261 10024 WorkSource{10373 com.example.hello}
I/ConfigFetchService( 4261): launchTask
,D/PMS     (  955): releaseWL(2066c681): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,D/PMS     (  955): acquireWL(2da4c4b9): PARTIAL_WAKE_LOCK  Icing 0x1 4261 10024 WorkSource{10024 com.google.android.gms}
,D/ChimeraCfgMgr( 4261): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4261): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 4261): Loading module com.google.android.gms.vision from APK com.google.android.gms
,V/ConfigFetchTask( 4261): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1XBQFge2or0AMgJEGfeMC9gD1e0m9KS9pTMYWxveHWDWkxYEATwfMxDBVn0gMNirtf9HriX7JKX8HWK9uNnTO4ezNfmgoHlB793tJXTNI1jpBVzZ6-0Ovut4-pRCe05hd2pt4GfhUVsTvNcDa9cW2cd-fuojCOj2Suum46PPqc0kjGi9tHX_NDpExq-wQhFyXcZE87ARbBuU1hb6GB-QHWZzcujJC6tRssj3Uatb474rPR0Lf8,
,I/PeopleContactsSync( 4261): CP2 sync disabled,
D/Vision  ( 4261): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package: flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) },
D/Vision  ( 4261): Failed to find package metadata for com.example.hello
D/Vision  ( 4261): No vision deps
,I/PackageManager(  955):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4261, uid=10024, userID:0
,I/GoogleURLConnFactory( 4261): Using platform SSLCertificateSocketFactory
I/ActivityManager(  955): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5147 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a
,I/Icing   ( 4261): Storage manager: low false usage 1.77MB avail 5.80GB capacity 7.95GB
,V/AlarmManager(  955): sending alarm PendingIntent{3643f375: PendingIntentRecord{109a7f0a android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=60641, Int=0
,D/libc    ( 4261): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
,D/libc    ( 4261): [NET] android_getaddrinfofornet-, err=8
,D/Process (  955): killProcessQuiet, pid=4690,
I/ActivityManager(  955): Killing 4690:com.htc.sense.news/u0a74 (adj 15): empty #17
,D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ClockController( 1222): schedule update now=1449414000029 next=59971
,D/libc    ( 4261): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024,
D/libc    ( 4261): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4261): [NET] android_getaddrinfo_proxy+
D/libc    ( 4261): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  400): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  400): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  400): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 4261): [NET] android_getaddrinfo_proxy-, NODATA
,I/Clock   ( 1222): updateClock:16:00 Europe/Warsaw
,I/Clock   ( 1222): updateClock:16:00 Europe/Warsaw
I/Clock   ( 1222): updateClock:16:00 Europe/Warsaw
,W/Icing   ( 4261): Received bad json for section weights override -- ignoring.
,W/ConfigFetchTask( 4261): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,I/ConfigFetchService( 4261): fetch service done; releasing wakelock
I/ConfigFetchService( 4261): stopping self
D/PMS     (  955): releaseWL(26c01680): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 WorkSource{10373 com.example.hello}
,W/Icing   ( 4261): Received bad json for corpus context scoring override -- ignoring.
,W/Icing   ( 4261): Received bad json for section weights override -- ignoring.
,W/Icing   ( 4261): Received bad json for corpus context scoring override -- ignoring.,
,I/ActivityManager(  955): Recipient 4690,
,V/AlarmManager(  955): sending alarm PendingIntent{97fac57: PendingIntentRecord{14291344 com.android.vending startService}}, i=null, t=0, cnt=1, w=1449414000198, Int=0,
,D/WeatherUtility( 1222): Weather sync is On
W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,D/Finsky  ( 5062): [1] DailyHygiene.onStartCommand: Beginning daily hygiene,
,W/BaseAppContext( 4261): Using Auth Proxy for data requests.,
,W/BaseAppContext( 4261): Using Auth Proxy for data requests.
,V/Finsky  ( 5062): [1] GearheadStateMonitor.onReady: sIsProjecting:false,
V/GLSActivity( 1867): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/BaseAppContext( 4261): Using Auth Proxy for data requests.,
,I/GLSUser ( 1867): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1867): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1867): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1867): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1867): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Icing   ( 4261): Loading extension by file descriptor -1 failed
,W/Finsky  ( 5062): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,V/GLSActivity( 1867): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1867): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1867): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1867): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1867): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1867): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 4261): Explicit concurrent mark sweep GC freed 28566(2MB) AllocSpace objects, 22(440KB) LOS objects, 42% free, 5MB/9MB, paused 1.691ms total 103.500ms
,W/BaseAppContext( 4261): Using Auth Proxy for data requests.,
,W/BaseAppContext( 4261): Using Auth Proxy for data requests.
,V/GLSActivity( 1867): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BaseAppContext( 4261): Using Auth Proxy for data requests.,
,I/GLSUser ( 1867): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1867): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1867): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1867): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1867): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5062): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Icing   ( 4261): updateResources: need to parse f{com.google.android.gms}
,E/AndroidHttpClient( 5062): Leak found
E/AndroidHttpClient( 5062): java.lang.IllegalStateException: AndroidHttpClient created and never closed
E/AndroidHttpClient( 5062): 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
E/AndroidHttpClient( 5062): 	,at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
E/AndroidHttpClient( 5062): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
E/AndroidHttpClient( 5062): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
E/AndroidHttpClient( 5062): 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
E/AndroidHttpClient( 5062): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/AndroidHttpClient( 5062): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/AndroidHttpClient( 5062): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidHttpClient( 5062): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidHttpClient( 5062): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidHttpClient( 5062): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidHttpClient( 5062): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidHttpClient( 5062): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidHttpClient( 5062): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidHttpClient( 5062): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidHttpClient( 5062): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/art     (  955): Explicit concurrent mark sweep GC freed 24918(1167KB) AllocSpace objects, 3(348KB) LOS objects, 33% free, 15MB/23MB, paused 1.371ms total 142.610ms,
,I/Icing   ( 4261): Internal init done: storage state 0
,I/PackageManager(  955):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService, state=2, flag=1, pid=4261, uid=10024, userID:0
I/PackageManager(  955):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateActivity, state=2, flag=1, pid=4261, uid=10024, userID:0
I/PackageManager(  955):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$SecretCodeReceiver, state=2, flag=1, pid=4261, uid=10024, userID:0
,I/PackageManager(  955):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$Receiver, state=2, flag=1, pid=4261, uid=10024, userID:0
,I/Icing   ( 4261): Post-init done
,D/PMS     (  955): releaseWL(2da4c4b9): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,I/SocialFeedProvider( 1515): +disConnect socialManager
,I/SocialFeedProvider( 1515): disconnect socialManager
I/SocialFeedProvider( 1515): -disConnect socialManager
,I/GAv4    ( 5147): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5147):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5147):   adb logcat -s GAv4
,W/GAv4    ( 5147): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,D/AccTypeManager( 1675): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,W/SystemReader(  955): Cannot find grip_rejection_width, use default value instead
,W/GAv4    ( 5147): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5147): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/ResourcesManager( 1457): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/GLSActivity( 1867): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
W/ResourcesManager(  955): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/AccTypeManager( 1675): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/Prism.ItemManager( 1515): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/Prism.AllAppsManager( 1515): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/Prism.ItemManager( 1515): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/AnalyticsTrackerProxyImpl( 5147): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.25.45
,I/Launcher( 1515): Deferring update until onResume
D/Launcher( 1515): waitUntilResume // bindAppsUpdated
D/PhoneApp( 1457): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
D/AccTypeManager( 1675): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/ExternalAccountType( 1675): Unsupported attribute readOnly
,W/PackageManager(  955): Unable to load service info ResolveInfo{3d1ca12b com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  955): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  955): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  955): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  955): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  955): ,	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  955): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  955): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  955): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  955): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  955): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  955): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  955): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  955): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  955): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  955): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  955): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/BackupManagerService(  955): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService},
,D/ChimeraCfgMgr( 4261): Loading module com.google.android.gms.games from APK com.google.android.play.games,
D/ChimeraModuleLdr( 4261): Module APK com.google.android.play.games already loaded
,I/ActivityManager(  955): Start proc com.htc.sense.news for service com.htc.launcher/com.htc.plugin.news.SocialBiLogHelper: pid=5194 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a
V/AlarmManager(  955): sending alarm PendingIntent{f37e978: PendingIntentRecord{ec12851 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1449414001083, Int=0
,D/VoldConnector(  955): SND -> {16 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/},
,W/ContextImpl( 5147): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.docs/cache,
,E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/
,I/ActivityManager(  955): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5217 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,V/GmsNetworkLocationProvi( 1783): DISABLE
,W/ResourcesManager( 5147): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5147): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/GCoreNlp( 1783): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/GLSUser ( 1867): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1867): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1867): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1867): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1867): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LocationProviderProxy(  955): applying state to connected service
,V/JNIHelp ( 5147): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/PMS     (  955): acquireWL(22dd3b9f): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1783 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  955): releaseWL(22dd3b9f): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,W/ResourcesManager( 5217): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/LocationProviderProxy(  955): applying state to connected service
W/Finsky  ( 5062): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
D/PMS     (  955): acquireWL(3c5704ec): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1783 10024 WorkSource{10024 com.google.android.gms}
D/Finsky  ( 5062): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
D/PMS     (  955): releaseWL(3c5704ec): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  955): acquireWL(2f1530b5): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1783 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  955): acquireWL(21db134a): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1783 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  955): releaseWL(2f1530b5): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  955): releaseWL(21db134a): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/Finsky  ( 5062): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5062): [1] DailyHygiene.reschedule: Scheduling new run in 275 minutes (failures=4)
,I/ImageRamCache( 5194): create image Cache, size: 31457280.
,I/ImageRamCache( 5194): [resize] ImageRamCache resized to: 30Mb.
I/ImageRamCache( 5194): create image Cache, size: 31457280.
I/FeedSettings( 5194): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 5194): GroupBudget 0.500000 0.380000
I/FeedSettings( 5194): GroupBudget 60 45 15
W/System  ( 5147): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5147): Installed default security provider GmsCore_OpenSSL
I/Prism.ExternalStringMa_( 5194): changeLocale(): en_GB
,I/ActivityManager(  955): Killing 3723:com.htc.sense.mms/u0a64 (adj 15): empty #17,
D/Process (  955): killProcessQuiet, pid=3723
D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/DeviceConnectionService( 1783): client connected with version: 7571000
,I/Prism.AllAppsOptionsMa_( 5194): loadSortType() with Custom
I/Prism.AllAppsOptionsMa_( 5194): loadGridSize() with Alternative
,I/ActivityManager(  955): Recipient 3723,
,D/Process (  955): killProcessQuiet, pid=4731
I/ActivityManager(  955): Killing 4731:com.htc.mobiledata:remote/u0a46 (adj 15): empty #18
D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  955): Recipient 4731
,V/GLSActivity( 1867): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SocialManager[SocialBiLogHelper]( 5194): action: com.htc.sense.hsp.HANDLE_ULOG
,I/SocialManager[SocialBiLogHelper]( 5194): last commit ulog time 1449381160756
,I/SocialManager[SocialBiLogHelper]( 5194): skip commit this time
,I/ActivityManager(  955): Killing 4798:com.htc.mobiledata/u0a46 (adj 15): empty #17
D/Process (  955): killProcessQuiet, pid=4798
D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  955): Recipient 4798,
,D/PMS     (  955): acquireWL(2a6d9308): PARTIAL_WAKE_LOCK  AsyncService 0x1 5217 10167 null,
,D/PMS     (  955): acquireWL(5034c6): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 5217 10167 null
,D/PMS     (  955): releaseWL(2a6d9308): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  955): releaseWL(5034c6): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null,
,I/ActivityManager(  955): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5258 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a,
,D/Process (  955): killProcessQuiet, pid=4363
I/ActivityManager(  955): Killing 4363:com.google.android.talk/u0a112 (adj 15): empty #17
D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  955): Recipient 4363
,D/PMS     (  955): acquireWL(b28dfdd): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 4939 10011 null,
,E/SQLiteLog( 4939): (284) automatic index on view_events(_id)
,I/ActivityManager(  955): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=5282 uid=10028 gids={50028, 9997, 1028, 1015, 1023, 3003, 2001, 3002} abi=armeabi-v7a,
,D/PMS     (  955): releaseWL(b28dfdd): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null,
W/ResourcesManager( 5282): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  955): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=5304 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a
,D/LocationManagerService(  955): getProviders()=[passive]
,I/Prism.ItemManager( 1515): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1515): loadItems() com.htc.launcher.pageview.WidgetManager@1e00a9a +
I/Prism.WidgetManager( 1515): onLoadItems() +
I/UpdateIcingCorporaServi( 5258): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,I/EASAppSvc( 5304): [ NA ]onCreate
,I/VersionUtil( 5304): [ NA ]setIsFOTAing: true,
,W/ResourcesManager( 1515): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/VersionUtil( 5304): [ NA ]onUpgrade: current version=100, latest version=100
I/VersionUtil( 5304): [ NA ]setIsFOTAing: false
,D/HtcAdjCursorFactory( 5304): Set CursorWindow size to: 4194304 KB, Tid: 5333
,D/ORMLib  ( 4776): put(),
,I/ActivityManager(  955): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=5339 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,D/Process (  955): killProcessQuiet, pid=4832
,I/ActivityManager(  955): Killing 4832:com.nero.android.htc.sync/u0a5 (adj 15): empty #17
D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/asset   ( 5258): Copying FileAsset 0x558212f2b0 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,I/UpdateIcingCorporaServi( 5258): UpdateCorporaTask done [took 185 ms] updated apps [took 185 ms] 
,I/ActivityManager(  955): Recipient 4832
D/WifiService(  955): Client connection lost with reason: 4
,W/ResourcesManager( 1515): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/Process (  955): killProcessQuiet, pid=4912
I/ActivityManager(  955): Killing 4912:com.htc.backupreset/1000 (adj 15): empty #17
D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiTrafficPoller(  955): ADD_CLIENT: 6
D/WifiService(  955): New client listening to asynchronous messages
,W/EAS_NetworkUtil( 5304): [ NA ]getNetworkInfo: NetworkInfo is null
,E/SQLiteLog( 5282): (283) recovered 15 frames from WAL file /data/data/com.htc.album/databases/MMexternal.db-wal
,W/asset   ( 1515): Copying FileAsset 0x5582712860 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.,
,I/ActivityManager(  955): Recipient 4912,
,E/Prism.WidgetManager( 1515): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1515): onLoadItems() -,
I/Prism.ItemManager( 1515): loadItems() com.htc.launcher.pageview.WidgetManager@1e00a9a -
,D/PhoneApp( 1457): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1457): -- N1 =0,
,D/PhoneApp( 1457): -- N2 =0
D/PhoneApp( 1457): -- N3 =0
,I/EASAppSvc( 5304): [ NA ]onDestroy
,I/EASAppSvc( 5304): [ NA ]> uninitEASService
,I/EASRequestController( 5304): [ NA ]release
I/EASAppSvc( 5304): [ NA ]onCreate
,I/VersionUtil( 5304): [ NA ]setIsFOTAing: true
,D/BluetoothManagerService(  955): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  955): disable(): mBluetooth = null mBinding = false
W/Settings:Agent(  955): MONITOR_LOG
W/Settings:Agent(  955): name: bluetooth_on
W/Settings:Agent(  955): value: 0
W/Settings:Agent(  955): >> traceCallingStack()
W/Settings:Agent(  955): Process.myPid(): 955
W/Settings:Agent(  955): Process.myTid(): 974
W/Settings:Agent(  955): Process.myUid(): 1000
W/Settings:Agent(  955): 
W/Settings:Agent(  955): 
W/System.err(  955): java.lang.Throwable: stack dump
,I/VersionUtil( 5304): [ NA ]onUpgrade: current version=100, latest version=100
I/VersionUtil( 5304): [ NA ]setIsFOTAing: false
D/EASPublicBinder( 5304): [ NA ]release
,D/TaskBinder( 5304): [ NA ]release
D/TaskBinder( 5304): [ NA ]release
I/EASAppSvc( 5304): [ NA ]< uninitEASService
W/EAS_NetworkUtil( 5304): [ NA ]getNetworkInfo: NetworkInfo is null
,W/System.err(  955): 	at java.lang.Thread.dumpStack(Thread.java:490),
W/System.err(  955): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  955): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  955): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  955): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  955): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  955): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:378)
W/System.err(  955): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:624)
W/System.err(  955): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  955): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  955): 
W/Settings:Agent(  955): << traceCallingStack(): 9(ms)
,D/BluetoothManagerService(  955): Message: MESSAGE_DISABLE
,D/WifiManager( 4756): setWifiEnabled: Base Package Name=com.example.hello, uid=10373
,I/MusicStore( 5339): Database version: 120
,D/WifiService(  955): setWifiEnabled: false pid=4756, uid=10373,
E/WifiService(  955): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  955): isSprintWifiRestricted(): false
I/WifiService(  955): isMdmWifiRestricted(): false
,W/Settings:Agent(  955): MONITOR_LOG,
W/Settings:Agent(  955): name: wifi_on
W/Settings:Agent(  955): value: 0
W/Settings:Agent(  955): >> traceCallingStack()
W/Settings:Agent(  955): Process.myPid(): 955
W/Settings:Agent(  955): Process.myTid(): 1714
W/Settings:Agent(  955): Process.myUid(): 1000
,W/Settings:Agent(  955): 
W/Settings:Agent(  955): 
W/System.err(  955): java.lang.Throwable: stack dump
,W/System.err(  955): ,	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  955): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  955): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  955): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  955): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  955): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  955): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  955): 	,at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:112)
W/System.err(  955): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  955): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  955): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  955): 
W/Settings:Agent(  955): << traceCallingStack(): 8(ms)
,D/WifiController(  955): handleMessage: E msg.what=155656,
D/WifiController(  955): processMsg: ApStaDisabledState
D/WifiController(  955): handleMessage: X
I/jxcore-log( 4756): ****TEST TOOK:  5089  ms ****
I/jxcore-log( 4756): 
I/jxcore-log( 4756): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4756): 
,I/art     (  955): Explicit concurrent mark sweep GC freed 22389(1209KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.380ms total 136.215ms
,D/WifiService(  955): New client listening to asynchronous messages
E/WifiTrafficPoller(  955): ADD_CLIENT: 7
,D/ORMLib  ( 4776): put()
,D/VoldConnector(  955): SND -> {17 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 5339): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,I/EASAppSvc( 5304): [ NA ]onDestroy,
I/EASAppSvc( 5304): [ NA ]> uninitEASService
,I/ActivityManager(  955): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=5383 uid=10066 gids={50066, 9997, 3003} abi=arm64-v8a
,I/EASRequestController( 5304): [ NA ]release
,D/EASPublicBinder( 5304): [ NA ]release
D/TaskBinder( 5304): [ NA ]release
D/TaskBinder( 5304): [ NA ]release
I/EASAppSvc( 5304): [ NA ]< uninitEASService
,W/ContextImpl( 5339): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files,
D/VoldConnector(  955): SND -> {18 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,D/VoldConnector(  955): SND -> {19 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 5339): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/ResourcesManager( 5339): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 5339): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Process (  955): killProcessQuiet, pid=4965,
I/ActivityManager(  955): Killing 4965:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,V/JNIHelp ( 5339): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/ORMLib  ( 4776): put()
I/HtcModeClient( 3151): handler message = 4011
,E/HtcModeClient( 3151): Check connection and retry 5 times.
,E/cutils-trace( 5380): Error opening trace file: Permission denied (13),
,W/ActivityThread( 5339): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5339): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3ab962e3: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
I/ProviderInstaller( 5339): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5339): GMSCore installation verified
,D/CustomizationManager( 5380): ====startRecUseTime====,
D/htc.customization.log.level( 5380):  is 
W/CustomizationLogLevel( 5380): Level value is invalid, use default level 2
,I/ActivityManager(  955): Recipient 4965,
,D/CustomizationManager( 5380):  Read ACC file spent 0.031 (s),
,D/CIDMapFileReader( 5380): Parsing tag item name = HTC__001,
D/CIDMapFileReader( 5380): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5380): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5380): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5380): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5380): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 5380): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 5380): full path : /system/customize/CID/HTC__102.xml
,I/CustomizationCIDLoader( 5380): Parsing tag category name = system
I/CustomizationCIDLoader( 5380): Parsing tag category name = application
,I/CustomizationCIDLoader( 5380): Parsing tag category name = SettingsProvider
,I/CustomizationCIDLoader( 5380): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5380): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5380): Parsing tag category name = Settings
I/CustomizationCIDLoader( 5380): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 5380): add string-array item, value = 42507,
I/CustomizationCIDLoader( 5380): add string-array item, value = 21902
I/CustomizationCIDLoader( 5380): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 5380): add string-array item, value = 23420
I/CustomizationCIDLoader( 5380): add string-array item, value = 22299
I/CustomizationCIDLoader( 5380): add string-array item, value = 24002,
I/CustomizationCIDLoader( 5380): add string-array item, value = 23210
I/CustomizationCIDLoader( 5380): add string-array item, value = 23205
I/CustomizationCIDLoader( 5380): add string-array item, value = 23806
I/CustomizationCIDLoader( 5380): add string-array item, value = 23430
I/CustomizationCIDLoader( 5380): add string-array item, value = 23408
I/CustomizationCIDLoader( 5380): add string-array item, value = 27205
I/CustomizationCIDLoader( 5380): add string-array item, value = 42507:C:1:0,
I/CustomizationCIDLoader( 5380): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 5380): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 5380): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 5380): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 5380): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 5380): add string-array item, value = 23210:D:2:0
,I/CustomizationCIDLoader( 5380): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 5380): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 5380): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 5380): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 5380): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 5380):  Read CID file spent 0.066 (s)
D/CustomizationManager( 5380):  All configurations done spent 0.066 (s)
,D/PackageManager(  955): deletePackageAsUser: pkg=com.example.hello, pid=5380, uid=2000 userid=0
,I/ConfigStore( 5339): Config Database version: 1
I/ActivityManager(  955): Force stopping com.example.hello appid=10373 user=-1: uninstall pkg
I/ActivityManager(  955): Killing 4756:com.example.hello/u0a373 (adj 0): stop com.example.hello
D/Process (  955): killProcessQuiet, pid=4756
D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
,W/PackageSettings(  955): Skipping PackageSetting{331b9ac6 com.test.thalitest/10366} due to missing metadata,
,I/ActivityManager(  955): Recipient 4756,
,I/WindowState(  955): WIN DEATH: Window{2dc02f0 u0 com.example.hello/com.example.hello.MainActivity}
D/WifiService(  955): Client connection lost with reason: 4
E/InputEventReceiver( 1347): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{15bdaaee uid 10373 pid 4756} (c)'
,D/PMS     (  955): acquireWL(2928527b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 955 1000 null
I/BatteryService(  955): n_update end
D/PMS     (  955): releaseWL(2928527b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/ActivityManager(  955): Force removing ActivityRecord{154193f4 u0 com.example.hello/.MainActivity t8}: app died, no saved state
,I/ActivityManager(  955): Force stopping com.example.hello appid=10373 user=0: pkg removed,
,W/ActivityManager(  955): Spurious death for ProcessRecord{156ec898 4756:com.example.hello/u0a373}, curProc for 4756: null
,D/DotMatrix( 1304): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1304): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1304): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
,D/HtcPowerSaver(  955): updateBatteryInfo,
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  955): acquireWL(1ed9e8f1): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1783 10024 WorkSource{10024 com.google.android.gms}
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  955): releaseWL(1ed9e8f1): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
W/GeofencerStateMachine( 1783): Ignoring removeGeofence because network location is disabled.
D/AccTypeManager( 1675): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
W/SystemReader(  955): Cannot find grip_rejection_width, use default value instead
,I/FeedHostManager( 1515): [onResume]
I/FeedProviderManager( 1515): onResume
I/SocialFeedProvider( 1515): +onResume
I/SocialFeedProvider( 1515): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1515): -onResume
,I/ConnectivityHelper( 1515): [getCurrentConnectionType] no network connection
,I/Prism.ItemManager( 5194): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 5194): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/ActivityManager(  955): Killing 4990:com.htc.widget.hmsproc2/u0a40 (adj 15): empty #17
,D/Process (  955): killProcessQuiet, pid=4990
D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/AccTypeManager( 1675): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/InputMethodManagerService(  955): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/AccTypeManager( 1675): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/PhoneApp( 1457): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,E/ExternalAccountType( 1675): Unsupported attribute readOnly
,I/ActivityManager(  955): Recipient 4990,
I/Prism.ItemManager( 1515): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1515): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/PackageManager(  955): Unable to load service info ResolveInfo{2dfc6a4 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  955): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  955): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  955): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  955): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  955): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  955): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  955): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  955): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  955): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  955): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  955): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  955): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  955): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  955): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  955): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  955): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
W/ResourcesManager(  955): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/StatusBarManagerService(  955): setSystemUiVisibility(0x700)
D/StatusBarManagerService(  955): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  955): hiding MENU key
D/FindExtension( 1515): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/ThreadedRenderer( 1515): Defer allocateBuffers to drawing time
,I/art     (  955): Explicit concurrent mark sweep GC freed 18804(1419KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 16MB/24MB, paused 1.686ms total 216.457ms
,W/asset   (  955): Copying FileAsset 0x5582370490 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
W/InputMethodManagerService(  955): Got RemoteException sending setActive(false) notification to pid 4756 uid 10373
D/StatusBarManagerService(  955): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  955): Enable input method client, pid=1515
,I/PackageManager(  955):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=5339, uid=10159, userID:0
,D/StatusBarManagerService(  955): setSystemUiVisibility(0xc0000700),
D/StatusBarManagerService(  955): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  955): hiding MENU key
,I/art     ( 1867): Explicit concurrent mark sweep GC freed 13332(740KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 494us total 36.099ms
,D/WifiDisplayAdapter(  955): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  955):     Client/Owner: Client
D/WifiDisplayAdapter(  955):     GroupId: 
D/WifiDisplayAdapter(  955):     Passphrase: 
D/WifiDisplayAdapter(  955):     SessionId: 0
D/WifiDisplayAdapter(  955):     IP Address: }
,D/MediaRouterService(  955): Client com.google.android.music (pid 5339): Registered
,D/WifiDisplayAdapter(  955): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  955):     Client/Owner: Client
D/WifiDisplayAdapter(  955):     GroupId: 
,D/WifiDisplayAdapter(  955):     Passphrase: 
D/WifiDisplayAdapter(  955):     SessionId: 0
D/WifiDisplayAdapter(  955):     IP Address: }
,I/MediaRouter( 5339): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,D/JobSchedulerService(  955): Receieved: android.intent.action.PACKAGE_REMOVED,
D/TelephonyReceiver( 1457): bind: true
,I/ActivityManager(  955): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=5436 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/UsbnetService(  955): BroadcastReceiver::onReceive+
D/NotificationService(  955): plugged=true pluggin=true
D/UsbnetService(  955): onReceive BATTERY_CHANGED
,D/PMS     (  955): runPSCheck
D/UsbnetService(  955):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  955): Checking...
D/UsbnetService(  955): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  955): >> updateStatus
D/WifiController(  955): handleMessage: E msg.what=155652
D/WifiController(  955): battery changed pluggedType: 2
D/WifiController(  955): processMsg: ApStaDisabledState
I/HtcPowerSaver(  955): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  955): processMsg: DefaultState
I/HtcPowerSaver(  955): << updateStatus
D/WifiController(  955): handleMessage: X
,I/PhoneStatusBar( 1222): setImeWindowStatus(false,false)
,I/ActivityManager(  955): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.GenericMessagesProvider: pid=5449 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,D/TaskPersister(  955): removeObsoleteFile: deleting file=8_task.xml
,I/PackageManager(  955):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=5339, uid=10159, userID:0
,I/GHttpClientFactory( 5339): Using our fixed implementation of GMSCore's GoogleHttpClient
,D/DFPI.PIReciver( 5436): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/GoogleURLConnFactory( 5339): Using platform SSLCertificateSocketFactory
,I/DFPI.ApkInstallService( 5436): onHandleIntent
,I/DFPI.ApkInstallService( 5436): Media Scan Finished Case 
W/HtcWrapAdjustableCursorFactory( 5449): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.
,D/DFPI.ApkInstallService( 5436): check CID = HTC__102
I/DFPI.ApkInstallService( 5436): There is no Demo.apk in sd card or phone storage
,D/MessageFrequencyProvider( 5449): onCreate
,I/ActivityManager(  955): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=5483 uid=10049 gids={50049, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,V/GetPrviateResource( 5449): GetPrviateResource
,V/GetPrviateResource( 5449): GetPrviateResource
D/GenericMessagesProvider( 5449): query uri: content://htc-messages/wappush/count
E/SQLiteLog( 5449): (14) cannot open file at line 30058 of [9491ba7d73]
E/SQLiteLog( 5449): (14) os_unix.c:30058: (2) open(/data/data/com.htc.sense.mms/databases/wappush.db) - 
E/SQLiteConnection( 5449): DB info: sqlite3_open_v2, path: /data/data/com.htc.sense.mms/databases/wappush.db, flag: 1, ret: 14
E/SQLiteConnection( 5449): DB info: errno = 2, errno message = No such file or directory
,E/SQLiteDatabase( 5449): Failed to open database '/data/data/com.htc.sense.mms/databases/wappush.db'.
E/SQLiteDatabase( 5449): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 5449): 	,at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5449): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 5449): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 5449): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5449): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5449): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5449): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5449): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5449): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5449): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:712)
E/SQLiteDatabase( 5449): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
E/SQLiteDatabase( 5449): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 5449): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 5449): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
E/SQLiteDatabase( 5449): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err( 5449): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
W/System.err( 5449): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 5449): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
D/MessageCustFlag( 5449): sense_version=6.0
W/System.err( 5449): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
W/System.err( 5449): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/System.err( 5449): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/System.err( 5449): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/System.err( 5449): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
W/System.err( 5449): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
W/System.err( 5449): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
W/System.err( 5449): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:712)
W/System.err( 5449): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
W/System.err( 5449): 	at android.content.ContentProvider.query(ContentProvider.java:960)
W/System.err( 5449): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
W/System.err( 5449): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
W/System.err( 5449): 	at android.os.Binder.execTransact(Binder.java:454)
D/BTAccessoryUtil( 5449): createReceiver
,D/Process (  955): killProcessQuiet, pid=4557
I/ActivityManager(  955): Killing 4557:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,I/ActivityManager(  955): Recipient 4557,
,D/TelephonyReceiver( 1457): switchBindHtcMsgCursor: null,
D/BTAccessoryUtil( 5449): registerReceiver return intent = null,
D/MessageCustFlag( 5449): sku_id=118
D/HtcBuildUtils( 5449): getRATByHtcTelephonyCapability:1
W/SystemReader( 5449): Cannot find qct_8960_interface, use default value instead
,D/Process (  955): killProcessQuiet, pid=5018
I/ActivityManager(  955): Killing 5018:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/OpenGLRenderer( 1515): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...,
,I/ActivityManager(  955): Recipient 5018
,I/ActivityManager(  955): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=5508 uid=10079 gids={50079, 9997, 5001, 1028, 1015} abi=arm64-v8a,
,D/VoldConnector(  955): SND -> {20 volume mkdirs /storage/ext_sd/Android/data/com.htc.musicenhancer/cache/}
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.htc.musicenhancer/cache/
,W/ContextImpl( 5483): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
,I/SoundPicker( 5508): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED,
,I/SoundPicker( 5508): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 5508): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5508): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5508): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
,D/RingtoneManager( 5508): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,I/ActivityManager(  955): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=5536 uid=10084 gids={50084, 9997, 3003, 1028, 1015, 1023, 2001, 5006, 5001} abi=arm64-v8a
,I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
,W/SoundPicker( 5508): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5508): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5508): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5508): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
,I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5508): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5508): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5508): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5508): getActualDefaultRingtoneUri(context, 4)
,I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5508): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
,I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5508): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
,I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
,W/SoundPicker( 5508): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5508): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5508): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5508): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5508): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
I/SoundPicker( 5508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5508): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5508): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac,
,I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5508): getActualDefaultRingtoneUri(context, 2)
,I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5508): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 5508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac,
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/SoundPicker( 5508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac,
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/SoundPicker( 5508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac,
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,D/DFPI.PIReciver( 5436): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/DFPI.ApkInstallService( 5436): onHandleIntent
,I/DFPI.ApkInstallService( 5436): Media Scan Finished Case 
I/SoundPicker( 5508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
D/DFPI.ApkInstallService( 5436): check CID = HTC__102
I/DFPI.ApkInstallService( 5436): There is no Demo.apk in sd card or phone storage
,I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,D/Process (  955): killProcessQuiet, pid=5040
,I/ActivityManager(  955): Killing 5040:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/SQLiteDatabase( 5536): Failed to open database '/data/data/com.htc.updater/databases/fota.db'.
E/SQLiteDatabase( 5536): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5536): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5536): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 5536): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 5536): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5536): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5536): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5536): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5536): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5536): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5536): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 5536): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 5536): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5536): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 5536): 	at com.htc.updater.db.UpdaterProvider.query(UpdaterProvider.java:473)
E/SQLiteDatabase( 5536): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 5536): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 5536): 	at android.content.ContentResolver.query(ContentResolver.java:491)
E/SQLiteDatabase( 5536): 	at android.content.ContentResolver.query(ContentResolver.java:435)
E/SQLiteDatabase( 5536): 	at com.htc.updater.db.FOTASettings$NameValueCache.getString(FOTASettings.java:310)
E/SQLiteDatabase( 5536): 	at com.htc.updater.db.FOTASettings.getString(FOTASettings.java:185)
E/SQLiteDatabase( 5536): 	at com.htc.updater.db.FOTASettings.getBoolean(FOTASettings.java:257)
E/SQLiteDatabase( 5536): 	at com.htc.updater.UpdaterReceiver$CheckActionThread.run(UpdaterReceiver.java:183)
E/SQLiteOpenHelper( 5536): Couldn't open fota.db for writing (will try read-only):
E/SQLiteOpenHelper( 5536): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5536): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5536): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteOpenHelper( 5536): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteOpenHelper( 5536): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5536): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5536): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5536): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteOpenHelper( 5536): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteOpenHelper( 5536): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteOpenHelper( 5536): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteOpenHelper( 5536): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 5536): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 5536): 	at and,roid.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 5536): 	at com.htc.updater.db.UpdaterProvider.query(UpdaterProvider.java:473)
E/SQLiteOpenHelper( 5536): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteOpenHelper( 5536): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteOpenHelper( 5536): 	at android.content.ContentResolver.query(ContentResolver.java:491)
E/SQLiteOpenHelper( 5536): 	at android.content.ContentResolver.query(ContentResolver.java:435)
E/SQLiteOpenHelper( 5536): 	at com.htc.updater.db.FOTASettings$NameValueCache.getString(FOTASettings.java:310)
E/SQLiteOpenHelper( 5536): 	at com.htc.updater.db.FOTASettings.getString(FOTASettings.java:185)
E/SQLiteOpenHelper( 5536): 	at com.htc.updater.db.FOTASettings.getBoolean(FOTASettings.java:257)
E/SQLiteOpenHelper( 5536): 	at com.htc.updater.UpdaterReceiver$CheckActionThread.run(UpdaterReceiver.java:183)
W/SQLiteOpenHelper( 5536): Opened fota.db in read-only mode
E/UpdaterAPK | COTASettings( 5536): Can't set key cota_notify_download
E/UpdaterAPK | COTASettings( 5536): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/UpdaterAPK | COTASettings( 5536): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/UpdaterAPK | COTASettings( 5536): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/UpdaterAPK | COTASettings( 5536): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/UpdaterAPK | COTASettings( 5536): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/UpdaterAPK | COTASettings( 5536): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/UpdaterAPK | COTASettings( 5536): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:823)
E/UpdaterAPK | COTASettings( 5536): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
E/UpdaterAPK | COTASettings( 5536): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/UpdaterAPK | COTASettings( 5536): 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:480)
E/UpdaterAPK | COTASettings( 5536): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
E/UpdaterAPK | COTASettings( 5536): 	at android.content.ContentResolver.update(ContentResolver.java:1354)
E/UpdaterAPK | COTASettings( 5536): 	at com.htc.updater.db.COTASettings$NameValueCache.putString(COTASettings.java:91)
E/UpdaterAPK | COTASettings( 5536): 	at com.htc.updater.db.COTASettings.putString(COTASettings.java:146)
E/UpdaterAPK | COTASettings( 5536): 	at com.htc.updater.db.COTASettings.putBoolean(COTASettings.java:160)
E/UpdaterAPK | COTASettings( 5536): 	at com.htc.updater.UpdaterReceiver.checkConfirmStatus(UpdaterReceiver.java:687)
E/UpdaterAPK | COTASettings( 5536): 	at com.htc.updater.UpdaterReceiver.access$200(UpdaterReceiver.java:53)
E/UpdaterAPK | COTASettings( 5536): 	at com.htc.updater.UpdaterReceiver$CheckActionThread.run(UpdaterReceiver.java:192)
,I/ActivityManager(  955): Recipient 5040
,V/AlarmManager(  955): sending alarm PendingIntent{19b59666: PendingIntentRecord{3f084da7 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1449414004856, Int=0,
I/SoundPicker( 5508): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5508): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 5508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,E/SharedPreferencesImpl( 5339): Couldn't rename file /data/data/com.google.android.music/shared_prefs/store.preferences.xml to backup file /data/data/com.google.android.music/shared_prefs/store.preferences.xml.bak
,I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,D/DFPI.PIReciver( 5436): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5508): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5508): TurnFileToMediaUriService fromMediaScanned = true,
I/SoundPicker( 5508): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5508): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5508): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122,
D/RingtoneManager( 5508): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5508): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5508): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5508): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5508): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5508): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5508): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
,W/SoundPicker( 5508): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5508): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5508): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5508): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5508): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5508): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5508): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
E/SQLiteDatabase(  955): Failed to open database '/data/data/com.htc.checkinprovider/databases/htcCheckin.db'.
E/SQLiteDatabase(  955): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(  955): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(  955): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase(  955): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase(  955): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase(  955): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase(  955): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase(  955): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase(  955): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase(  955): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase(  955): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase(  955): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(  955): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(  955): 	at com.htc.checkinprovider.htcCheckinProvider.query(htcCheckinProvider.java:335)
E/SQLiteDatabase(  955): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase(  955): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase(  955): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
E/SQLiteDatabase(  955): 	at android.os.Binder.execTransact(Binder.java:454)
E/SQLiteDatabase( 5339): Failed to open database '/data/data/com.google.android.music/databases/music.db'.
E/SQLiteDatabase( 5339): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5339): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5339): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 5339): 	at android.data,base.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 5339): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5339): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5339): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5339): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5339): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5339): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5339): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 5339): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 5339): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5339): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5339): 	at com.google.android.music.store.Store.getDatabase(Store.java:287)
E/SQLiteDatabase( 5339): 	at com.google.android.music.store.BaseStore.beginRead(BaseStore.java:28)
E/SQLiteDatabase( 5339): 	at com.google.android.music.store.Store.createDatabase(Store.java:262)
E/SQLiteDatabase( 5339): 	at com.google.android.music.store.MediaStoreImporter.doImport(MediaStoreImporter.java:220)
E/SQLiteDatabase( 5339): 	at com.google.android.music.store.Store.importMediaStore(Store.java:10438)
E/SQLiteDatabase( 5339): 	at com.google.android.music.store.MediaStoreImportService.importMediaStore(MediaStoreImportService.java:75)
E/SQLiteDatabase( 5339): 	at com.google.android.music.store.MediaStoreImportService.access$100(MediaStoreImportService.java:34)
E/SQLiteDatabase( 5339): 	at com.google.android.music.store.MediaStoreImportService$4.run(MediaStoreImportService.java:140)
E/SQLiteDatabase( 5339): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 5339): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 5339): 	at com.google.android.music.utils.LoggableHandler.dispatchMessage(LoggableHandler.java:82)
E/SQLiteDatabase( 5339): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 5339): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper(  955): Couldn't open htcCheckin.db for writing (will try read-only):
E/SQLiteOpenHelper(  955): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(  955): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(  955): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteOpenHelper(  955): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteOpenHelper(  955): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper(  955): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper(  955): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper(  955): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteOpenHelper(  955): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteOpenHelper(  955): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteOpenHelper(  955): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteOpenHelper(  955): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(  955): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(  955): 	at com.htc.checkinprovider.htcCheckinProvider.query(htcCheckinProvider.java:335)
E/SQLiteOpenHelper(  955): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteOpenHelper(  955): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteOpenHelper(  955): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
E/SQLiteOpenHelper(  955): 	at android.os.Binder.execTransact(Binder.java:454)
I/DFPI.ApkInstallService( 5436): onHandleIntent
I/DFPI.ApkInstallService( 5436): Media Scan Finished Case 
W/SQLiteOpenHelper(  955): Opened htcCheckin.db in read-only mode
D/DFPI.ApkInstallService( 5436): check CID = HTC__102
I/DFPI.ApkInstallService( 5436): There is no Demo.apk in sd card or phone storage
E/AndroidRuntime( 5339): FATAL EXCEPTION: MediaStoreImportService
E/AndroidRuntime( 5339): Process: com.google.android.music:main, PID: 5339
E/AndroidRuntime( 5339): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5339): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5339): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 5339): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 5339): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5339): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5339): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5339): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 5339): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 5339): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 5339): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 5339): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 5339): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 5339): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 5339): 	at com.google.android.music.store.Store.getDatabase(Store.java:287)
E/AndroidRuntime( 5339): 	at com.google.android.music.store.BaseStore.beginRead(BaseStore.java:28)
E/AndroidRuntime( 5339): 	at com.google.android.music.store.Store.createDatabase(Store.java:262)
E/AndroidRuntime( 5339): 	at com.google.android.music.store.MediaStoreImporter.doImport(MediaStoreImporter.java:220)
E/AndroidRuntime( 5339): 	at com.google.android.music.store.Store.importMediaStore(Store.java:10438)
E/AndroidRuntime( 5339): 	at com.google.android.music.store.MediaStoreImportService.importMediaStore(MediaStoreImportService.java:75)
E/AndroidRuntime( 5339): 	at com.google.android.music.store.MediaStoreImportService.access$100(MediaStoreImportService.java:34)
E/AndroidRuntime( 5339): 	at com.google.android.music.store.MediaStoreImportService$4.run(MediaStoreImportService.java:140)
E/AndroidRuntime( 5339): 	at android.os.Handler.handleCallback(Handler.java:739)
E/AndroidRuntime( 5339): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 5339): 	at com.google.android.music.utils.LoggableHandler.dispatchMessage(LoggableHandler.java:82)
E/AndroidRuntime( 5339): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 5339): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/SoundPicker( 5508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5508): getActualDefaultRingtoneUri(context, 1, mode_cdma)
E/ActivityManager(  955): App crashed! Process: com.google.android.music:main
I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
I/SoundPicker( 5508): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
I/SoundPicker( 5508): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 5508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
E/DropBoxManagerService(  955): Can't write: system_app_crash
E/DropBoxManagerService(  955): java.io.FileNotFoundException: /data/system/dropbox/drop115.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  955): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  955): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  955): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  955): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  955): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  955): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  955): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  955): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  955): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  955): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  955): 	... 5 more
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5508): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,D/StatusBarManagerService(  955): setSystemUiVisibility(0xc0000000),
D/StatusBarManagerService(  955): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  955): hiding MENU key
,E/UpdaterAPK | FOTASettings( 5536): Can't set key backup_uri_string,
E/UpdaterAPK | FOTASettings( 5536): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:823)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:480)
E/UpdaterAPK | FOTASettings( 5536): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
E/UpdaterAPK | FOTASettings( 5536): 	,at android.content.ContentResolver.update(ContentResolver.java:1354)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:296)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:199)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:180)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:70)
E/UpdaterAPK | FOTASettings( 5536): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/UpdaterAPK | FOTASettings( 5536): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/UpdaterAPK | FOTASettings( 5536): 	at android.os.Looper.loop(Looper.java:155)
E/UpdaterAPK | FOTASettings( 5536): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/UpdaterAPK | FOTASettings( 5536): Can't set key download_sdcard
E/UpdaterAPK | FOTASettings( 5536): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
,E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:823)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:480)
E/UpdaterAPK | FOTASettings( 5536): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
E/UpdaterAPK | FOTASettings( 5536): 	at android.content.ContentResolver.update(ContentResolver.java:1354)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:296)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:199)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.db.FOTASettings.putBoolean(FOTASettings.java:280)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:181)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:70)
E/UpdaterAPK | FOTASettings( 5536): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/UpdaterAPK | FOTASettings( 5536): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,E/UpdaterAPK | FOTASettings( 5536): 	at android.os.Looper.loop(Looper.java:155)
E/UpdaterAPK | FOTASettings( 5536): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/UpdaterAPK | FOTASettings( 5536): Can't set key fota_prompt_version
E/UpdaterAPK | FOTASettings( 5536): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:823)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
,E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:480)
E/UpdaterAPK | FOTASettings( 5536): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
E/UpdaterAPK | FOTASettings( 5536): 	at android.content.ContentResolver.update(ContentResolver.java:1354)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:296)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:199)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:182)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:70)
E/UpdaterAPK | FOTASettings( 5536): 	,at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/UpdaterAPK | FOTASettings( 5536): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/UpdaterAPK | FOTASettings( 5536): 	at android.os.Looper.loop(Looper.java:155)
E/UpdaterAPK | FOTASettings( 5536): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/UpdaterAPK | FOTASettings( 5536): Can't set key fota_prompt_feature
E/UpdaterAPK | FOTASettings( 5536): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:823)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:480)
E/UpdaterAPK | FOTASettings( 5536): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
E/UpdaterAPK | FOTASettings( 5536): 	at android.content.ContentResolver.update(ContentResolver.java:1354)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:296)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:199)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:183)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:70)
E/UpdaterAPK | FOTASettings( 5536): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/UpdaterAPK | FOTASettings( 5536): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/UpdaterAPK | FOTASettings( 5536): 	at android.os.Looper.loop(Looper.java:155)
E/UpdaterAPK | FOTASettings( 5536): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/UpdaterAPK | FOTASettings( 5536): Can't set key fota_prompt_size
E/UpdaterAPK | FOTASettings( 5536): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:823)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:480,)
E/UpdaterAPK | FOTASettings( 5536): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
E/UpdaterAPK | FOTASettings( 5536): 	at android.content.ContentResolver.update(ContentResolver.java:1354)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:296)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:199)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:184)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:70)
E/UpdaterAPK | FOTASettings( 5536): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/UpdaterAPK | FOTASettings( 5536): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/UpdaterAPK | FOTASettings( 5536): 	at android.os.Looper.loop(Looper.java:155)
E/UpdaterAPK | FOTASettings( 5536): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/UpdaterAPK | FOTASettings( 5536): Can't set key fota_force_update
E/UpdaterAPK | FOTASettings( 5536): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:823)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:480)
E/UpdaterAPK | FOTASettings( 5536): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
E/UpdaterAPK | FOTASettings( 5536): 	at android.content.ContentResolver.update(ContentResolver.java:1354)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:296)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:199)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:185)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:70)
E/UpdaterAPK | FOTASettings( 5536): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/UpdaterAPK | FOTASettings( 5536): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/UpdaterAPK | FOTASettings( 5536): 	at android.os.Looper.loop(Looper.java:155)
E/UpdaterAPK | FOTASettings( 5536): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/UpdaterAPK | FOTASettings( 5536): Can't set key fota_notify_download
E/UpdaterAPK | FOTASettings( 5536): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:823)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:480)
E/UpdaterAPK | FOTASettings( 5536): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
E/UpdaterAPK | FOTASettings( 5536): 	at android.content.ContentResolver.update(ContentResolver.java:1354)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:296)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:199)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.db.FOTASettings.putBoolean(FOTASettings.java:280)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:186)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:70)
E/UpdaterAPK | FOTASettings( 5536): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/UpdaterAPK | FOTASettings( 5536): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/UpdaterAPK | FOTASettings( 5536): 	at android.os.Looper.loop(Looper.java:155)
E/UpdaterAPK | FOTASettings( 5536): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/SoundPicker( 5508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
E/UpdaterAPK | FOTASettings( 5536): Can't set key fota_need_token
E/UpdaterAPK | FOTASettings( 5536): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:823)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:480)
E/UpdaterAPK | FOTASettings( 5536): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
E,/UpdaterAPK | FOTASettings( 5536): 	at android.content.ContentResolver.update(ContentResolver.java:1354)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:296)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:199)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.db.FOTASettings.putBoolean(FOTASettings.java:280)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:189)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:70)
E/UpdaterAPK | FOTASettings( 5536): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/UpdaterAPK | FOTASettings( 5536): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/UpdaterAPK | FOTASettings( 5536): 	at android.os.Looper.loop(Looper.java:155)
E/UpdaterAPK | FOTASettings( 5536): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5508): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
E/UpdaterAPK | FOTASettings( 5536): Can't set key fota_reserve_data_size
E/UpdaterAPK | FOTASettings( 5536): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:823)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:480)
E/UpdaterAPK | FOTASettings( 5536): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
E/UpdaterAPK | FOTASettings( 5536): 	at android.content.ContentResolver.update(ContentResolver.java:1354)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:296)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:199)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.db.FOTASettings.putInt(FOTASettings.java:239)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:194)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:70)
E/UpdaterAPK | FOTASettings( 5536): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/UpdaterAPK | FOTASettings( 5536): 	at android.os.Handler.dispatchMessage(Handler.java:,102)
E/UpdaterAPK | FOTASettings( 5536): 	at android.os.Looper.loop(Looper.java:155)
E/UpdaterAPK | FOTASettings( 5536): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/UpdaterAPK | FOTASettings( 5536): Can't set key fota_package_download_via_wifi
E/UpdaterAPK | FOTASettings( 5536): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:823)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:480)
E/UpdaterAPK | FOTASettings( 5536): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
E/UpdaterAPK | FOTASettings( 5536): 	at android.content.ContentResolver.update(ContentResolver.java:1354)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:296)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:199)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.db.FOTASettings.putBoolean(FOTASettings.java:280)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:200)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:70)
E/UpdaterAPK | FOTASettings( 5536): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/UpdaterAPK | FOTASettings( 5536): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/UpdaterAPK | FOTASettings( 5536): 	at android.os.Looper.loop(Looper.java:155)
E/UpdaterAPK | FOTASettings( 5536): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/UpdaterAPK | FOTASettings( 5536): Can't set key fota_prompt_message
E/UpdaterAPK | FOTASettings( 5536): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:823)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:480)
E/UpdaterAPK | FOTASettings( 5536): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
E/UpdaterAPK | FOTASettings( 5536): 	at android.content.ContentResolver.update(ContentResolver.java:1354)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:296)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:199)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:202)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:70)
E/UpdaterAPK | FOTASettings( 5536): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/UpdaterAPK | FOTASettings( 5536): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/UpdaterAPK | FOTASettings( 5536): 	at android.os.Looper.loop(Looper.java:155)
E/UpdaterAPK | FOTASettings( 5536): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/SoundPicker( 5508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5508): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
I/ActionCombine( 5536): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
I/SoundPicker( 5508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
I/SoundPicker( 5508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
I/SoundPicker( 5508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,E/UpdaterAPK | FOTASettings( 5536): Can't set key fota_optional
E/UpdaterAPK | FOTASettings( 5536): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:823)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
E/UpdaterAPK | FOTASettings( 5536): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:480)
E/UpdaterAPK | FOTASettings( 5536): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
E/UpdaterAPK | FOTASettings( 5536): 	at android.content.ContentResolver.update(ContentResolver.java:1354)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:296)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:199)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:282)
E/UpdaterAPK | FOTASettings( 5536): 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:70)
E/UpdaterAPK | FOTASettings( 5536): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/UpdaterAPK | FOTASettings( 5536): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/UpdaterAPK | FOTASettings( 5536): 	at android.os.Looper.loop(Looper.java:155)
E/UpdaterAPK | FOTASettings( 5536): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/SoundPicker( 5508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
I/SoundPicker( 5508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/RemoteViews( 1222): setHTCTheme(com.htc.updater,true,33751145)
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5508): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5508): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5508): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5508): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5508): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5508): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5508): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5508): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5508): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5508): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5508): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5508): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5508): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5508): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5508): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5508): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5508): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5508): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5508): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
I/SoundPicker( 5508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/RemoteViews( 1222): apply : com.htc.updater 1 10 2 36
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5508): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
I/SoundPicker( 5508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5508): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
I/SoundPicker( 5508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5508): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
I/SoundPicker( 5508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5508): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
I/SoundPicker( 5508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
I/SoundPicker( 5508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
D/FindExtension( 1222): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/SoundPicker( 5508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/ThreadedRenderer( 1222): Defer allocateBuffers to drawing time
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
I/SoundPicker( 5508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5508): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5508): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac,
I/SoundPicker( 5508): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/ConfigService( 1867): onDestroy,
,I/Prism.ItemManager( 5194): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
I/Prism.ItemManager( 5194): loadItems() com.htc.launcher.pageview.WidgetManager@21e3097 +
I/Prism.WidgetManager( 5194): onLoadItems() +
,W/ResourcesManager( 5194): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,I/Prism.ItemManager( 1515): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
I/Prism.ItemManager( 1515): loadItems() com.htc.launcher.pageview.WidgetManager@1e00a9a +
I/Prism.WidgetManager( 1515): onLoadItems() +

```
