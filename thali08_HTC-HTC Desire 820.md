#### Test 50242285feafdeb_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
I/ActivityManager(  902): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver: pid=3204 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
--------- beginning of /dev/log/main
W/WeatherUtility( 3188): can't get weather sync account
E/Prism.WidgetManager( 1246): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1246): onLoadItems() -
I/Prism.ItemManager( 1246): loadItems() com.htc.launcher.pageview.WidgetManager@41bccf68 -
W/WeatherRequest( 3188): request cur loc, but there is no sys cur
W/Settings( 3188): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/DemoRecovery.RestoreReceiver( 3204): onReceive: com.htc.launcher.intent.LOADING_COMPLETE
W/ContextImpl( 3204): Implicit intents with startService are not safe: Intent { act=com.htc.demorecovery.LOADING_COMPLETE } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.demoflopackageinstaller.demorecovery.RestoreReceiver.onReceive:26 
I/ActivityManager(  902): Delay finish: com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver
I/RestoreService( 3204): onHandleIntent: com.htc.demorecovery.LOADING_COMPLETE
I/ActivityManager(  902): Resuming delayed broadcast
D/AppWidgetHostView( 1246): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
I/RemoteViews( 1246): com.htc.widget.weatherclock (true,33751552)
D/Process (  902): killProcessQuiet, pid=2910
D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  902): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3221 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
I/ActivityManager(  902): Killing 2910:com.htc.backupreset/1000 (adj 15): empty #17
I/RemoteViews.Performance( 1246): com.htc.widget.weatherclock 1 16 17
I/ActivityManager(  902): Recipient 2910
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  902): acquireWL(425d4288): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3221 10070 null
D/PMS     (  902): acquireWL(425d38e8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3221 10070 null
I/ActivityManager(  902): Delay finish: com.htc.task/.TodoReceiver
D/TodoTaskshortcut( 3221): update TASK shortcut>
D/PMS     (  902): releaseWL(425d4288): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/ContactMessageStore( 1219): MSG_NOTIFY_CS_TO_SYNC >>
D/ContactMessageStore( 1219): MSG_NOTIFY_CS_TO_SYNC <<
I/TodoTaskNotifyService( 3221): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
D/DotMatrix( 1581): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  902): releaseWL(425d38e8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  902): Resuming delayed broadcast
W/NotifyReceiver( 3221): stopSelfResult true
D/Process (  902): killProcessQuiet, pid=2929
D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Start proc com.htc.stock for broadcast com.htc.stock/.receiver.StockReceiver: pid=3238 uid=10081 gids={50081, 3003, 5012}
I/ActivityManager(  902): Killing 2929:com.htc.htccupd/u0a17 (adj 15): empty #17
I/ActivityManager(  902): Recipient 2929
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PhoneApp( 1219): EVENT_QUERY_MO_PACKAGES
D/PhoneApp( 1219): -- N1 =0
D/PhoneApp( 1219): -- N2 =0
D/PhoneApp( 1219): -- N3 =0
I/ActivityManager(  902): Start proc com.htc.stock:remote for content provider com.htc.stock/.provider.StockProvider: pid=3250 uid=10081 gids={50081, 3003, 5012}
D/Process (  902): killProcessQuiet, pid=2945
D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/SMSBackup( 3159): Got a database change event
D/Process (  902): killProcessQuiet, pid=2972
D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  902): Killing 2945:com.zoodles.kidmode/u0a149 (adj 15): empty #17
I/ActivityManager(  902): Killing 2972:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
I/ActivityManager(  902): Recipient 2945
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/AdsMeasurementBroadcastReceiver( 1198): Reporting settings might have changed, alerting AdsMeasurementService
D/AdsMeasurementBroadcastReceiver( 1198): Unauthorized to start the main service
I/ActivityManager(  902): Recipient 2972
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  902): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=3262 uid=10075 gids={50075, 3003, 5012, 1028, 1015, 5001, 1023}
I/ImageRamCache( 3262): create image Cache, size: 31457280.
I/ImageRamCache( 3262): [resize] ImageRamCache resized to: 12Mb.
I/ImageRamCache( 3262): create image Cache, size: 12582912.
I/FeedSettings( 3262): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 3262): GroupBudget 0.500000 0.380000
I/FeedSettings( 3262): GroupBudget 60 45 15
I/Prism.ExternalStringMa_( 3262): changeLocale(): en_GB
I/Prism.AllAppsOptionsMa_( 3262): loadSortType() with Custom
I/Prism.AllAppsOptionsMa_( 3262): loadGridSize() with Alternative
D/CustomHighlightReceiver( 3262): [custom highlight] onReceive
D/CustomHighlightService( 3262): [custom highlight] onHandleIntent
D/NewsDB  ( 3262): set custom highlight []
I/ActivityManager(  902): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
E/cutils-trace( 3236): Error opening trace file: No such file or directory (2)
D/CustomHighlightService( 3262): [custom highlight] set tags 
D/Process (  902): killProcessQuiet, pid=2999
D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Resuming delayed broadcast
I/ActivityManager(  902): Killing 2999:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
D/GCM     ( 1344): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  902): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  902): Recipient 2999
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MessagingShortcutReceiver( 2566): keep hiding shortcut bubble
D/MessagingShortcut( 2566): updateMsgShortcut, msg count> -1
D/MessagingShortcut( 2566): After query: 0
D/MessagingShortcut( 2566): mPresentUnreadCount: -1
D/MessagingShortcut( 2566): setMsgShortcutDrawable> 0
D/MessagingShortcut( 2566): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
D/DotMatrix( 1581): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/ActivityManager(  902): Resuming delayed broadcast
D/DotMatrix( 1581): [EventService] reorderNotification, total:0
D/DotMatrix( 1581): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1581): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/TodoTaskshortcut( 3221): update TASK shortcut>
I/ActivityManager(  902): Delay finish: com.htc.task/.TodoReceiver
I/ActivityManager(  902): Resuming delayed broadcast
D/HtcBroadcastReceiver( 1219): onReceive: com.htc.launcher.action.ACTION_ITEM_ADDED
I/ActivityManager(  902): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3286 uid=10091 gids={50091, 3003, 5012}
D/MessagingNotification( 2566): New incoming message, can't cancel notification now
D/MessagingNotification( 2566): newMsgCnt: 0, false
I/ActivityManager(  902): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
D/HABCtrl (  902): TPE algorithm. schedule timeout.
D/HABCtrl (  902): ALG=2, lsvalue=40(1th)->10(0th), last_level=1, lValue=64->64
I/ActivityManager(  902): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3300 uid=10091 gids={50091, 3003, 5012}
D/CustomizationManager( 3236): ====startRecUseTime====
D/htc.customization.log.level( 3236):  is 
W/CustomizationLogLevel( 3236): Level value is invalid, use default level 2
D/MdScBoot( 3286): [7b8.1.] 30@-234746 -> 40@-234815
I/ActivityManager(  902): Resuming delayed broadcast
D/HABCtrl (  902): mTPEAlgorithmTimeoutTask: TPE algorithm. restore.
I/ActivityManager(  902): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver: pid=3312 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
D/Process (  902): killProcessQuiet, pid=3013
D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
D/Process (  902): killProcessQuiet, pid=3025
D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Killing 3013:com.android.smith/u0a163 (adj 15): empty #17
I/ActivityManager(  902): Killing 3025:com.google.android.youtube/u0a168 (adj 15): empty #17
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  902): Recipient 3013
D/CustomizationManager( 3236):  Read ACC file spent 0.063 (s)
D/CIDMapFileReader( 3236): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3236): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3236): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3236): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3236): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3236): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3236): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3236): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3236): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3236): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3236): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3236): Parsing tag category name = system
I/CustomizationCIDLoader( 3236): Parsing tag category name = application
I/CustomizationCIDLoader( 3236): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3236): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3236): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3236): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3236): Parsing tag category name = Settings
D/CustomizationManager( 3236):  Read CID file spent 0.108 (s)
D/CustomizationManager( 3236):  All configurations done spent 0.108 (s)
W/HtcNativeFlag( 3236): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3236): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3236): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3236): Fail to get flag for type 'language', use default value: -1
E/dalvikvm( 3312): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
E/ProviderInstaller( 3312): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
I/ActivityManager(  902): Recipient 3025
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  902): Client com.google.android.youtube (pid 3025): Died!
I/Babel   ( 3312): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 3312): MmsConfig.loadMmsSettings
W/CpuWake (  902): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  902): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  902): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  902): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  902): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  902): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  902): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3236
D/PMS     (  902): acquireHCC(422cd800): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 902 1000 null
W/asset   (  902): Copying FileAsset 0x62dc5d98 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
E/dalvikvm( 3312): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
E/ProviderInstaller( 3312): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
I/Intent  (  902): @test_code: getHtcIntentFlag: 0 obj: 1110923272
V/JNIHelp ( 3312): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
D/PMS     (  902): acquireHCC(42465f98): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 902 1000 null
I/FeedHostManager( 1246): [onPause]
I/FeedProviderManager( 1246): onPause
I/FeedHostManager( 1246): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@42318990
I/SocialFeedProvider( 1246): +onPause
I/SocialFeedProvider( 1246): -onPause
D/PMS     (  902): acquireWL(4209b168): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 902 1000 null
I/ActivityManager(  902): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3337 uid=10356 gids={50356, 3003, 5012, 3001, 3002}
D/MmsCustomizationProvider( 2566): query uri: content://htc-mms-customization/mms-ua/ua_string
D/MmsCustomizationProvider( 2566): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/TrimMemoryManager( 1246): [trimMemory] 20
W/asset   ( 3337): Copying FileAsset 0x5d82c428 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/Babel   ( 3312): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/Babel   ( 3312): MmsConfig.loadFromDatabase
I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=3312, uid=10111, userID:0
E/Babel   ( 3312): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 3312): MmsConfig.loadFromResources
E/Babel   ( 3312): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 3312): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
W/Settings( 3312): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=3312, uid=10111, userID:0
D/Process (  902): killProcessQuiet, pid=2982
D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=3312, uid=10111, userID:0
I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=3312, uid=10111, userID:0
I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=3312, uid=10111, userID:0
I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=3312, uid=10111, userID:0
I/ActivityManager(  902): Killing 2982:com.android.settings/1000 (adj 15): empty #17
D/GCM     ( 1344): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
V/WebViewChromiumFactoryProvider( 3337): Binding Chromium to main looper Looper (main, tid 1) {41b3d038}
I/LibraryLoader( 3337): Expected native library version number "",actual native library version number ""
I/chromium( 3337): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3337): Initializing chromium process, renderers=0
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  902): Recipient 2982
W/System.err(  902): java.lang.Throwable: stack dump
W/System.err(  902): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  902): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  902): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  902): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  902): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 3337): 1102391856: getState() :  mService = null. Returning STATE_OFF
D/BluetoothManagerService(  902): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  902): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42145700:true
D/PMS     (  902): acquireWL(4242b1f0): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  902): acquireWL(424f4630): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  902): releaseWL(424f4630): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/MtpReceiver( 2233): [MTP][MtpReceiver][onReceive]+
D/MtpReceiver( 2233): [MTP][handleMessage][startService]
D/MtpReceiver( 2233): [MTP][MtpReceiver][onReceive]1-
I/ProviderInstaller( 3312): Installed default security provider GmsCore_OpenSSL
D/MtpReceiver( 2233): [MTP][handleMessage][UsbManager.USB_CONNECTED][insert]+
D/MtpReceiver( 2233): [MTP][handleMessage]-
D/ConnectivityService(  902): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1743/10178)
I/Adreno-EGL( 3337): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3337): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3337): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3337): Local Branch: 
I/Adreno-EGL( 3337): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3337): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3337):                  aa63bbd948f41d15fc72f585e
D/MtpService( 2233): [MTP] startForeground
I/ActivityManager(  902): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3361 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
D/MtpService( 2233): updating state; isCurrentUser=true, mMtpLocked=false
D/MtpDatabase( 2233): TotalSize=1918604,MediaCacheLimit=6000
D/DotMatrix( 1581): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
D/MtpService( 2233): [isMtpConnected] connected: true
I/RemoteViews( 1107): com.android.providers.media (false,0)
I/RemoteViews.Performance( 1107): com.android.providers.media 1 0 10
I/RemoteViews( 1107): com.android.providers.media (false,0)
I/RemoteViews.Performance( 1107): com.android.providers.media 0 1 15
W/chromium( 3337): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 3337): VFY: unable to resolve virtual method 172: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3337): VFY: unable to resolve virtual method 167: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3337): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3337): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3337): VFY: unable to resolve virtual method 225: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/SyncApplication( 3361): Loading default preferences
W/dalvikvm( 3337): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3337): VFY: unable to resolve virtual method 183: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3337): VFY: unable to resolve virtual method 188: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3337): CordovaWebView is running on device made by: HTC
W/Resources( 3361): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
D/WifiService(  902): New client listening to asynchronous messages
,D/SyncApplication( 3361): Overriding preferences with custom values
D/SyncApplication( 3361): Updating preferences succeeded
E/SyncApplication( 3361): Application created.
D/VolumeInfo( 3361): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
D/VolumeInfo( 3361): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
D/Process (  902): killProcessQuiet, pid=3076
V/VolumeInfo( 3361): Found 0 mount point(s)
V/VolumeInfo( 3361): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/VolumeInfo( 3361): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
I/ActivityManager(  902): Killing 3076:com.htc.sense.browser/u0a12 (adj 15): empty #17
D/VolumeInfo( 3361): Read the volume-id from the sd card: {61911E1D-261C-4FB6-8207-55BA8B8D5E9C}
W/VolumeInfo( 3361): Can not create volume ID for unmounted volume null
W/AwContents( 3337): nativeOnDraw failed; clearing to background color.
I/CalendarDefines( 3361): getNewCalendarAuthority()...
I/HtcModeClient( 1483): handler message = 4011
E/HtcModeClient( 1483): Check connection and retry 5 times.
D/SyncApplication( 3361): enableAppOperation()+
D/SyncApplication( 3361): enableAppOperation()-
I/PackageManager(  902):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3361, uid=10008, userID:0
W/PackageManager(  902): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  902):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3361, uid=10008, userID:0
W/PackageManager(  902): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
D/HTCUtilities( 3361): isNeorSinged() + 
W/ResourceType( 3337): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 3337): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b83d78, mServedView=org.apache.cordova.engine.SystemWebView{41b49d50 VFEDH.C. .F....I. 0,0-720,1134 #64}
D/HTCUtilities( 3361): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
W/XT9_C   ( 1182): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1182): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1182): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1182): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/HTCUtilities( 3361): isNeorSinged() return false
D/CDMountReceiver( 3361): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
D/CDMountReceiver( 3361): USB connected to PC
I/ActivityManager(  902): Displayed com.example.hello/.MainActivity: +281ms
W/AwContents( 3337): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  902): Disable input method client, pid=1246
I/InputMethodManagerService(  902): Enable input method client, pid=3337
D/PMS     (  902): releaseWL(4209b168): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
I/ActivityManager(  902): Recipient 3076
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/FOTAReceiver( 3361): onReceive() enter 
D/FOTAReceiver( 3361): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
I/ActivityManager(  902): Start proc com.android.settings for broadcast com.android.settings/.MLReceiver: pid=3398 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process (  902): killProcessQuiet, pid=3115
D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  902): Killing 3115:com.google.android.partnersetup/u0a31 (adj 15): empty #17
I/ActivityManager(  902): Recipient 3115
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/chromium( 3337): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
E/AndroidProtocolHandler( 3337): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/JsMessageQueue( 3337): Set native->JS mode to OnlineEventsBridgeMode
D/HtcFingerPrintQuickLaunchProvider( 3398): -onCreate()
V/Settings:HtcSettingsApplication( 3398): [3398/3398] onCreate()
D/TetherSettings( 3398): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3398): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3398): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3398): Cust_ConnectToPC   : spcsc>false
D/        ( 3398): Cust_ConnectToPC   : IPT>true
D/        ( 3398): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3398): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/TetherSettings( 3398): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3398): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3398): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3398): Cust_ConnectToPC   : spcsc>false
D/        ( 3398): Cust_ConnectToPC   : IPT>true
D/        ( 3398): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3398): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3398): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3398): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3398): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
D/SmartNS_Utility( 3398): usb_cable_connect = 1
D/SmartNS_Utility( 3398): usb_denied = 0
I/SmartNS_NSReceiver( 3398): locked:falsesecurity:falseisLocked:false
D/SmartNS_NSReceiver( 3398): USB = true hasTethered = false isNSOpening: false
I/PSReceiver( 3398): onReceive:com.htc.intent.action.USB_CONNECT2PC
W/ContextImpl( 3398): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 3398): onReceive:com.htc.intent.action.USB_CONNECT2PC
W/Settings( 3398): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3398):  defaultType:0
I/SmartNS_PSService( 3398): fail notificaiton:false
D/SmartNS_Utility( 3398): usb_cable_connect = 1
D/SmartNS_Utility( 3398): usb_denied = 0
I/SmartNS_PSService( 3398): usb notificaiton:true
V/Tethering(  902): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Tethering(  902): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  902): bSetPropertyMultiRAB:false
D/ConnectivityService(  902): getActiveNetworkInfo called by com.android.settings (3398/1000)
I/RemoteViews( 1107): com.android.settings (true,33751552)
I/RemoteViews.Performance( 1107): com.android.settings 2 0 10
D/DotMatrix( 1581): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
D/SmartNS_Utility( 3398): usb_cable_connect = 1
D/SmartNS_Utility( 3398): usb_denied = 0
I/SmartNS_PSService( 3398): usb notificaiton:true
V/Tethering(  902): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Tethering(  902): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  902): bSetPropertyMultiRAB:false
I/ActivityManager(  902): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
D/ConnectivityService(  902): getActiveNetworkInfo called by com.android.settings (3398/1000)
W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
D/SmartNS_Utility( 3398): usb_cable_connect = 1
D/SmartNS_Utility( 3398): usb_denied = 0
I/RemoteViews( 1107): com.android.settings (true,33751552)
D/DotMatrix( 1581): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
I/RemoteViews.Performance( 1107): com.android.settings 1 0 10
I/SmartNS_PSService( 3398): KeyGuard locked:falseKeyGuard is secured:false
D/SmartNS_PSService( 3398): USB Plugged, Set USBPlugged=  truePSenabled:false
I/ActivityManager(  902): Resuming delayed broadcast
W/WeatherUtility( 3188): can't get weather sync account
D/AppWidgetHostView( 1246): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider})
D/jxcore_app_log( 3337): JniHelper::setJavaVM(0x41612048), pthread_self() = 1658618504
I/RemoteViews( 1246): com.google.android.googlequicksearchbox (false,0)
I/RemoteViews.Performance( 1246): com.google.android.googlequicksearchbox 3 0 5
I/ActivityManager(  902): Delay finish: pl.k2.droidoaudioteka/.ui.widgets.BigWidgetProvider
D/AppWidgetHostView( 1246): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{pl.k2.droidoaudioteka/pl.k2.droidoaudioteka.ui.widgets.BigWidgetProvider})
I/RemoteViews( 1246): pl.k2.droidoaudioteka (false,0)
I/RemoteViews.Performance( 1246): pl.k2.droidoaudioteka 1 1 8
I/ActivityManager(  902): Resuming delayed broadcast
I/ActivityManager(  902): Delay finish: com.google.android.gms/.playlog.service.MonitorAlarmReceiver
D/LocationManagerService(  902): getAllProviders()=[passive, gps, network]
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.gms (1198/10028)
W/WeatherRequest( 3188): request cur loc, but there is no sys cur
W/Settings( 3188): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/AppWidgetHostView( 1246): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
I/RemoteViews( 1246): com.htc.widget.weatherclock (true,33751552)
I/ActivityManager(  902): Resuming delayed broadcast
I/ActivityManager(  902): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
I/RemoteViews.Performance( 1246): com.htc.widget.weatherclock 2 7 17
W/jxcore-log( 3337): Initializing JXcore engine
W/jxcore-log( 3337): JXcore engine is ready
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.gms (1198/10028)
I/ActivityManager(  902): Resuming delayed broadcast
I/ActivityManager(  902): Delay finish: com.google.android.gms/.security.snet.SnetBootCompletedReceiver
V/AlarmManager(  902): sending alarm PendingIntent{424fda20: PendingIntentRecord{4286c688 com.google.android.gms startService}}, i=null, t=0, cnt=17105, w=84918423, Int=84918423
W/jxcore-log( 3337): Starting JXcore engine
I/ActivityManager(  902): Resuming delayed broadcast
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.gms (1198/10028)
I/AdsMeasurementBroadcastReceiver( 1198): Reporting settings might have changed, alerting AdsMeasurementService
D/AdsMeasurementBroadcastReceiver( 1198): Unauthorized to start the main service
D/SnetService( 1198): snet destroyed
I/ActivityManager(  902): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=3432 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
W/jxcore-log( 3337): Platform android
W/jxcore-log( 3337): 
W/jxcore-log( 3337): Process ARCH arm
W/jxcore-log( 3337): 
I/jxcore-log( 3337): JXcore Cordova bridge is ready!
I/jxcore-log( 3337): 
W/jxcore-log( 3337): JXcore engine is started
E/jxcore  ( 3337): Error!: No such native module /data/data/com.example.hello/files/www/jxcore/app.js
E/jxcore  ( 3337): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
W/ContextImpl( 3432): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
D/PowerUsageService( 3432): call getInstance()
I/ActivityManager(  902): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
D/PowerUsageList:PowerUsageHelper( 3432): MY_DEBUG = false
W/BatSI   (  902): Couldn't get kernel wake lock stats
W/BatSI   (  902): Couldn't get kernel wake lock stats
W/BatSI   (  902): Couldn't get kernel wake lock stats
I/ActivityManager(  902): Resuming delayed broadcast
D/PMS     (  902): acquireWL(42772098): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3432 1000 null
D/Process (  902): killProcessQuiet, pid=3128
D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  902): Killing 3128:com.htc.contacts/u0a41 (adj 15): empty #17
W/WeatherUtility( 1107): can't get weather sync account
D/WeatherUtility( 1388): Weather sync is On
D/WSP     ( 1388): [Receiver] auto sync agent, auto sync is enabled, reset schedule
W/WeatherUtility( 3188): can't get weather sync account
W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
D/PackageBroadcastService( 1198): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
W/WeatherRequest( 3188): request cur loc, but there is no sys cur
W/Settings( 3188): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  902): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
D/AppWidgetHostView( 1246): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
I/RemoteViews( 1246): com.htc.widget.weatherclock (true,33751552)
I/RemoteViews.Performance( 1246): com.htc.widget.weatherclock 0 5 17
D/PMS     (  902): acquireWL(4263b380): PARTIAL_WAKE_LOCK  Icing 0x1 1198 10028 null
D/PMS     (  902): releaseWL(4263b380): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ActivityManager(  902): Recipient 3128
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/PeopleContactsSync( 1198): CP2 sync disabled
I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1198, uid=10028, userID:0
,I/ActivityManager(  902): Resuming delayed broadcast
,I/ActivityManager(  902): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=3459 uid=10031 gids={50031, 3003, 5012}
,I/ActivityManager(  902): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/ActivityManager(  902): Resuming delayed broadcast
,I/ActivityManager(  902): Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
I/ActivityManager(  902): Resuming delayed broadcast
D/Process (  902): killProcessQuiet, pid=3172
D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Killing 3172:com.htc.calendar/u0a13 (adj 15): empty #17
I/[PluginManager]RegisterService( 1388): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.example.hello
,I/[PluginManager]RegisterService( 1388): handle notify Blinkfeed plugin client changed
I/ActivityManager(  902): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  902): Resuming delayed broadcast
I/ActivityManager(  902): Recipient 3172
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  902): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=3475 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
,I/PackageManager(  902):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=3475, uid=10073, userID:0
,D/Finsky  ( 3475): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  902): getAllNetworkInfo called by com.android.vending (3475/10073)
,D/ConnectivityService(  902): getAllNetworkInfo called by com.android.vending (3475/10073)
,D/Finsky  ( 3475): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 3475): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3475): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/PackageManager(  902):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=3475, uid=10073, userID:0
,D/Process (  902): killProcessQuiet, pid=2959
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/Prism.PackageStateRece_( 1246): action: android.intent.action.PACKAGE_ADDED
D/Finsky  ( 3475): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3475): [1] 2.run: Finished loading 1 libraries.
I/ActivityManager(  902): Killing 2959:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  902): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/ActivityManager(  902): Recipient 2959
,I/IcingCorporaProvider( 2681): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Finsky  ( 3475): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager(  902): Delaying start of: ServiceRecord{4240da68 u0 com.android.vending/com.google.android.finsky.services.RestoreService}
,D/PMS     (  902): acquireWL(426ad078): PARTIAL_WAKE_LOCK  Icing 0x1 1198 10028 null
,D/PMS     (  902): releaseWL(426ad078): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  902): acquireWL(42620cf8): PARTIAL_WAKE_LOCK  Icing 0x1 1198 10028 null
,D/PMS     (  902): releaseWL(42620cf8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  902): acquireWL(4259de80): PARTIAL_WAKE_LOCK  Icing 0x1 1198 10028 null
,D/PMS     (  902): releaseWL(4259de80): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  902): acquireWL(425e6d88): PARTIAL_WAKE_LOCK  Icing 0x1 1198 10028 null
,D/PMS     (  902): releaseWL(425e6d88): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  902): acquireWL(42365df0): PARTIAL_WAKE_LOCK  Icing 0x1 1198 10028 null
,D/PMS     (  902): releaseWL(42365df0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  902): acquireWL(426d5710): PARTIAL_WAKE_LOCK  Icing 0x1 1198 10028 null
W/CpuWake (  902): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  902): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  902): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  902): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  902): >>release mCpuPerf_Freq wakelock
W/CpuWake (  902): <<release mCpuPerf_Freq wakelock
,D/PMS     (  902): releaseHCC(422cd800): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  902): releaseHCC(42465f98): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,D/PMS     (  902): releaseWL(426d5710): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  902): acquireWL(426e51d8): PARTIAL_WAKE_LOCK  Icing 0x1 1198 10028 null
,D/PMS     (  902): releaseWL(426e51d8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  902): acquireWL(425e5e20): PARTIAL_WAKE_LOCK  Icing 0x1 1198 10028 null
,D/PMS     (  902): releaseWL(425e5e20): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  902): acquireWL(42619a80): PARTIAL_WAKE_LOCK  Icing 0x1 1198 10028 null
,D/PMS     (  902): releaseWL(42619a80): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  902): acquireWL(426e5e80): PARTIAL_WAKE_LOCK  Icing 0x1 1198 10028 null
,D/PMS     (  902): releaseWL(426e5e80): PARTIAL_WAKE_LOCK  Icing 0x1 null
,W/asset   ( 2681): Copying FileAsset 0x63f0a190 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,I/IcingCorporaProvider( 2681): UpdateCorporaTask done [took 254 ms] updated apps [took 254 ms] 
,D/Finsky  ( 3475): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  902): Resuming delayed broadcast
,I/ActivityManager(  902): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=3512 uid=10098 gids={50098, 3003, 5012}
,I/DeviceManagement( 3512): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=3512 dbg=false s=true
,I/DeviceManagement( 3512): PackageUpdateReceiver: vvv Package added: [com.example.hello]
,I/ActivityManager(  902): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=3525 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,D/Process (  902): killProcessQuiet, pid=3204
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  902): Killing 3204:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  902): Recipient 3204
,V/AlarmManager(  902): sending alarm PendingIntent{425271e0: PendingIntentRecord{425fa178 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1452552498161, Int=0
,D/Process (  902): killProcessQuiet, pid=3238
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Killing 3238:com.htc.stock/u0a81 (adj 15): empty #17
,I/ActivityManager(  902): Recipient 3238
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/GAV2    ( 3525): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  902): Start proc com.htc.backup for broadcast com.htc.backup/.task.restore.PackageInstallReceiver: pid=3545 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/PMS     (  902): releaseWL(42772098): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/htcbackup-core( 3545): ModelRegistry: Loading model meta data from resources...
,W/ContextImpl( 3545): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
W/ContextImpl( 3545): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 com.htc.cs.dm.config.ConfigManager.getConfig:322 
,I/DeviceManagement( 3512): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=44]
,I/DeviceManagement( 3512): ConfigManagerBoundService: Caller: uid=android.uid.system:1000 (1000) packages=[android, com.htc.android.htcsetupwizard, com.htc.backup, com.htc.drive.activator, com.android.settings, com.htc.htcpowermanager, com.htc.autobot.cargps.provider, com.android.keychain, com.htc.backupreset, com.android.providers.settings, com.htc.mirrorlinkserver, com.htc.smartdim, com.htc.home.personalize, com.android.inputdevices, com.qualcomm.privinit, com.htc.android.htcloglevel, com.android.location.fused, com.htc.lockscreen, com.htc.checkinprovider, com.htc.feedback, com.qualcomm.timeservice, com.htc.cirmodule, com.htc.guide, com.htc.usage, com.android.CSDFunctionG]
,I/DeviceManagement( 3512): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=44], appID=com.htc.backup}]]
,I/ActivityManager(  902): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=3562 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
,D/Process (  902): killProcessQuiet, pid=3250
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  902): Killing 3250:com.htc.stock:remote/u0a81 (adj 15): empty #17
,V/AlarmManager(  902): sending alarm PendingIntent{42737940: PendingIntentRecord{426b68f8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1452552498688, Int=0
I/DeviceManagement( 3512): WorkflowService: Starting workflow service
I/DeviceManagement( 3512): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41b6f770] args=[Bundle[mParcelledData.dataSize=144]]
I/DeviceManagement( 3512): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=144]
,I/DeviceManagement( 3512): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  902): Recipient 3250
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DeviceManagement( 3512): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 3512): SessionStateController: Checking invariants...
,D/HtcCupdReceiver(Provider)( 3562):  @@@@@ receive action=android.intent.action.PACKAGE_ADDED
I/ActivityManager(  902): Delay finish: com.htc.providers.settings/.HtcCupdReceiver
,W/GLSUser ( 1344): GoogleAccountDataService.getToken()
,I/GoogleHttpClient( 1344): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1344): Using GMS GoogleHttpClient
,W/GLSActivity( 1344): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1344): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1344): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSUser ( 1344): GoogleAccountDataService.getToken()
,I/DeviceManagement( 3512): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
,W/GLSActivity( 1344): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1344): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1344): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 3475): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
I/ActivityManager(  902): Resuming delayed broadcast
,W/GAV2    ( 3525): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  902): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=3579 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,D/Finsky  ( 3475): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,I/DeviceManagement( 3512): SessionStateController: Checking invariants...
D/PMS     (  902): releaseWL(4242b1f0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/DeviceManagement( 3512): ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 3512): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41b6f770]
,I/DeviceManagement( 3512): WorkflowService: Stopping workflow service
D/Process (  902): killProcessQuiet, pid=3146
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Killing 3146:com.htc.widget.hmsproc1/u0a38 (adj 15): empty #17
,I/ActivityManager(  902): Recipient 3146
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  902): acquireWL(427e8198): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 3579 10160 null
,W/GLSUser ( 1344): GoogleAccountDataService.getToken()
D/PMS     (  902): acquireWL(427d9b20): PARTIAL_WAKE_LOCK  AsyncService 0x1 3579 10160 null
,D/PMS     (  902): releaseWL(427d9b20): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,W/GLSActivity( 1344): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1344): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1344): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 3475): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3475): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3475): [1] DailyHygiene.reschedule: Scheduling new run in 9 minutes (failures=1)
,D/Process (  902): killProcessQuiet, pid=3159
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Killing 3159:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
D/PMS     (  902): acquireWL(427ca040): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 3579 10160 null
D/PMS     (  902): releaseWL(427e8198): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
,I/ActivityManager(  902): Recipient 3159
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  902): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=3608 uid=10032 gids={50032, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.apps.plus (3579/10160)
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.apps.plus (3579/10160)
,D/PMS     (  902): releaseWL(427ca040): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
,D/Process (  902): killProcessQuiet, pid=3262
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Killing 3262:com.htc.sense.news/u0a75 (adj 15): empty #17
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  902): Recipient 3262
,D/Settings:HtcWirelessFeatureFlags( 3398): id/is att sku: 99/false
,W/SystemReader( 3398): Cannot find devicepolicy_lower_fp_quality, use default value instead
,W/SystemReader( 3398): Cannot find support_harman, use default value instead
,W/SystemReader( 3398): Cannot find effect_manager_id, use default value instead
,E/Settings:HtcWrapHeaderInfo( 3398): no such activity!
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3398): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3398): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 3398): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3398): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3398): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3398): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3398): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3398): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3398): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3398): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3398): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3398): [supportHomeButton]support         :false
,I/ActivityManager(  902): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=3625 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,W/FingerprintManager( 3398): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
,I/ActivityManager(  902): Cannot resolve ContentProvider=com.htc.vowifi
,E/Settings:HtcVoWifiWidgetEnabler( 3398): isSupportVoWifi: null
E/ActivityThread( 3398): Failed to find provider info for com.htc.vowifi
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3398): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3398): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 3398): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3398): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3398): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3398): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3398): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3398): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3398): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3398): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3398): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3398): [supportHomeButton]support         :false
,I/MusicStore( 3625): Database version: 95
,W/FingerprintManager( 3398): hasFingerprint() - sSensorCode = 0
,E/Settings:HtcVoWifiWidgetEnabler( 3398): isSupportVoWifi: null
I/ActivityManager(  902): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3398): Failed to find provider info for com.htc.vowifi
,W/ContextImpl( 3625): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 3625): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  350): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3625): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  350): Returning OperationFailed - no handler for errno 30
,E/cutils  (  350): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3625): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  350): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  350): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 3625): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  350): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=3625, uid=10154, userID:0
,D/WifiDisplayAdapter(  902): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  902):     Client/Owner: Client
D/WifiDisplayAdapter(  902):     GroupId: 
D/WifiDisplayAdapter(  902):     Passphrase: 
D/WifiDisplayAdapter(  902):     SessionId: 0
D/WifiDisplayAdapter(  902):     IP Address: }
,D/MediaRouterService(  902): Client com.google.android.music (pid 3625): Registered
,I/MediaRouter( 3625): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  902): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  902):     Client/Owner: Client
D/WifiDisplayAdapter(  902):     GroupId: 
D/WifiDisplayAdapter(  902):     Passphrase: 
D/WifiDisplayAdapter(  902):     SessionId: 0
D/WifiDisplayAdapter(  902):     IP Address: }
,I/ActivityManager(  902): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.music (3625/10154)
,D/MediaRouter( 3625): getSelectedRoute
,I/ActivityManager(  902): Resuming delayed broadcast
,I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=3625, uid=10154, userID:0
,I/ActivityManager(  902): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=3647 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
,D/Process (  902): killProcessQuiet, pid=3221
,I/ActivityManager(  902): Killing 3221:com.htc.task/u0a70 (adj 15): empty #17
D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/DFPI.PIReciver( 3647): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3647): onHandleIntent
,I/DFPI.ApkInstallService( 3647): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3647): check CID = HTC__032
,I/DFPI.ApkInstallService( 3647): There is no Demo.apk in sd card or phone storage
,D/Process (  902): killProcessQuiet, pid=3286
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  902): Resuming delayed broadcast
I/ActivityManager(  902): Killing 3286:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
,I/ActivityManager(  902): Recipient 3286
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  902): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=3661 uid=10051 gids={50051, 1028, 1015, 3003, 5012}
,I/ActivityManager(  902): Recipient 3221
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  902): Delay finish: com.htc.musicenhancer/.provider.MScannerReceiver
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.htc.musicenhancer (3661/10051)
,E/cutils  (  350): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3661): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
W/Vold    (  350): Returning OperationFailed - no handler for errno 30
,I/SocialFeedProvider( 1246): +disConnect socialManager
,I/SocialFeedProvider( 1246): disconnect socialManager
,I/SocialFeedProvider( 1246): -disConnect socialManager
,I/ActivityManager(  902): Start proc com.htc.sense.news for service com.htc.launcher/com.htc.plugin.news.SocialBiLogHelper: pid=3679 uid=10075 gids={50075, 3003, 5012, 1028, 1015, 5001, 1023}
,V/AlarmManager(  902): sending alarm PendingIntent{42408428: PendingIntentRecord{4251b310 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1452552500067, Int=0
,I/ImageRamCache( 3679): create image Cache, size: 31457280.
I/ImageRamCache( 3679): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 3679): create image Cache, size: 12582912.
,I/FeedSettings( 3679): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 3679): GroupBudget 0.500000 0.380000
,I/FeedSettings( 3679): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 3679): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 3679): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 3679): loadGridSize() with Alternative
,I/SocialManager[SocialBiLogHelper]( 3679): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 3679): last commit ulog time 1452491635921
,I/SocialManager[SocialBiLogHelper]( 3679): skip commit this time
,D/Process (  902): killProcessQuiet, pid=3300
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Killing 3300:com.htc.mobiledata/u0a91 (adj 15): empty #17
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  902): Recipient 3300
,I/SensorManager(  902): mEventCount = 450
,I/ActivityManager(  902): Resuming delayed broadcast
,I/ActivityManager(  902): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=3695 uid=10080 gids={50080, 5001, 1028, 1015}
,D/Process (  902): killProcessQuiet, pid=3312
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Killing 3312:com.google.android.talk/u0a111 (adj 15): empty #17
,I/HtcModeClient( 1483): handler message = 4011
,E/HtcModeClient( 1483): Check connection and retry 6 times.
,I/SoundPicker( 3695): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3695): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3695): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3695): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3695): TurnFileToMediaUriService fromMediaScanned = true
,I/SoundPicker( 3695): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
I/ActivityManager(  902): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,D/RingtoneManager( 3695): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,D/RingtoneManager( 3695): MODE_GSM access default DB
,I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3695): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3695): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3695): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
,D/RingtoneManager( 3695): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3695): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
,D/RingtoneManager( 3695): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3695): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 3695): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,W/SoundPicker( 3695): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,W/SoundPicker( 3695): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,W/SoundPicker( 3695): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,W/SoundPicker( 3695): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3695): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3695): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3695): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3695): MODE_GSM access default DB
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
,I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3695): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3695): getActualDefaultRingtoneUri(context, 1, mode_cdma)
,I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
,I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3695): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3695): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
,I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3695): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3695): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
,I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3695): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3695): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
,I/SoundPicker( 3695): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
I/ActivityManager(  902): Recipient 3312
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/SoundPicker( 3695): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
I/SoundPicker( 3695): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
I/SoundPicker( 3695): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/SoundPicker( 3695): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/ActivityManager(  902): Resuming delayed broadcast
I/ActivityManager(  902): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  902): Waited long enough for: ServiceRecord{42635dc8 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,I/ActivityManager(  902): Resuming delayed broadcast
,D/DFPI.PIReciver( 3647): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3647): onHandleIntent
,I/DFPI.ApkInstallService( 3647): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3647): check CID = HTC__032
,I/DFPI.ApkInstallService( 3647): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  902): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  902): Resuming delayed broadcast
,I/SoundPicker( 3695): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3695): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3695): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3695): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3695): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3695): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3695): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3695): MODE_GSM access default DB
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3695): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3695): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3695): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3695): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3695): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3695): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3695): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 3695): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 3695): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 3695): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 3695): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 3695): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3695): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3695): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3695): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3695): MODE_GSM access default DB
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
,I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/ActivityManager(  902): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3695): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3695): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3695): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3695): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3695): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3695): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/SoundPicker( 3695): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3695): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
,I/SoundPicker( 3695): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
,I/SoundPicker( 3695): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
,I/SoundPicker( 3695): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
,I/SoundPicker( 3695): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
,I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3695): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  902): Resuming delayed broadcast
,I/ActivityManager(  902): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  902): Resuming delayed broadcast
,I/ActivityManager(  902): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=3714 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
,I/ActivityManager(  902): Delay finish: com.htc.task/.TodoTaskReceiver
,I/ActivityManager(  902): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=3727 uid=10063 gids={50063, 3003, 5012, 1023, 1028, 1015}
,I/ActivityManager(  902): Resuming delayed broadcast
D/DFPI.PIReciver( 3647): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/DFPI.ApkInstallService( 3647): onHandleIntent
,I/DFPI.ApkInstallService( 3647): Media Scan Finished Case 
,I/ActivityManager(  902): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
D/DFPI.ApkInstallService( 3647): check CID = HTC__032
,I/DFPI.ApkInstallService( 3647): There is no Demo.apk in sd card or phone storage
,D/Process (  902): killProcessQuiet, pid=2566
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Resuming delayed broadcast
I/ActivityManager(  902): Killing 2566:com.htc.sense.mms/u0a64 (adj 15): empty #17
,I/SoundPicker( 3695): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3695): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3695): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3695): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3695): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3695): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3695): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3695): MODE_GSM access default DB
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3695): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3695): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3695): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3695): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3695): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3695): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3695): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 3695): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 3695): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 3695): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 3695): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 3695): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3695): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3695): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3695): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3695): MODE_GSM access default DB
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
,I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/ActivityManager(  902): Recipient 2566
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  902): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3695): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3695): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3695): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3695): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3695): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3695): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/SoundPicker( 3695): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3695): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
,I/SoundPicker( 3695): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
,I/SoundPicker( 3695): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/EASAppSvc( 3727): [ NA ]- onCreate()
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
,I/EASAppSvc( 3727): [ NA ]> onUpgrade: version = 63
,I/SoundPicker( 3695): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
,D/ORMLib  ( 3714): put()
,I/SoundPicker( 3695): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
,I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3695): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,D/WifiService(  902): New client listening to asynchronous messages
,D/ConnectivityService(  902): getNetworkInfo networkType=1 called by com.htc.android.mail (3727/10063)
,D/ConnectivityService(  902): getNetworkInfo networkType=0 called by com.htc.android.mail (3727/10063)
,D/ConnectivityService(  902): getNetworkInfo networkType=55 called by com.htc.android.mail (3727/10063)
,I/ActivityManager(  902): Resuming delayed broadcast
I/EASAppSvc( 3727): [ NA ]- onDestroy()
I/EASAppSvc( 3727): [ NA ]> uninitEASService
,I/EASRequestController( 3727): [ NA ]release
,I/EASAppSvc( 3727): [ NA ]< uninitEASService
,I/ActivityManager(  902): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
I/EASAppSvc( 3727): [ NA ]- onCreate()
,I/EASAppSvc( 3727): [ NA ]> onUpgrade: version = 63
D/ConnectivityService(  902): getNetworkInfo networkType=1 called by com.htc.android.mail (3727/10063)
D/ConnectivityService(  902): getNetworkInfo networkType=0 called by com.htc.android.mail (3727/10063)
D/ConnectivityService(  902): getNetworkInfo networkType=55 called by com.htc.android.mail (3727/10063)
,D/ORMLib  ( 3714): put()
,I/EASAppSvc( 3727): [ NA ]- onDestroy()
,I/EASAppSvc( 3727): [ NA ]> uninitEASService
,I/EASRequestController( 3727): [ NA ]release
I/ActivityManager(  902): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=3760 uid=10067 gids={50067, 3003, 5012}
,I/EASAppSvc( 3727): [ NA ]< uninitEASService
,I/MediaStoreImporter( 3625): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/ActivityManager(  902): Killing 3361:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/Process (  902): killProcessQuiet, pid=3361
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/Process (  902): killProcessQuiet, pid=3432
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Resuming delayed broadcast
I/ActivityManager(  902): Killing 3432:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,D/ORMLib  ( 3714): put()
I/ActivityManager(  902): Recipient 3361
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  902): Client connection lost with reason: 4
,D/DFPI.PIReciver( 3647): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/ActivityManager(  902): Recipient 3432
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  902): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
I/ActivityManager(  902): Resuming delayed broadcast
I/DFPI.ApkInstallService( 3647): onHandleIntent
,I/DFPI.ApkInstallService( 3647): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3647): check CID = HTC__032
,I/DFPI.ApkInstallService( 3647): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  902): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  902): Resuming delayed broadcast
,I/SoundPicker( 3695): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3695): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3695): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3695): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3695): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3695): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3695): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3695): MODE_GSM access default DB
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3695): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3695): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3695): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
,D/RingtoneManager( 3695): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3695): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3695): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3695): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 3695): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 3695): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 3695): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 3695): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 3695): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3695): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3695): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3695): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3695): MODE_GSM access default DB
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
,I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/ActivityManager(  902): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3695): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3695): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3695): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3695): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3695): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3695): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/SoundPicker( 3695): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3695): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
I/SoundPicker( 3695): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
I/SoundPicker( 3695): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.fla,c
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
I/SoundPicker( 3695): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
I/SoundPicker( 3695): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3695): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/SoundPicker( 3695): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3695): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  902): Resuming delayed broadcast
I/ActivityManager(  902): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/MediaStoreImporter( 3625): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,D/TelephonyReceiver( 1219): bind: true
I/ActivityManager(  902): Resuming delayed broadcast
D/PMS     (  902): acquireWL(41fcc708): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 1483 10014 null
,I/ActivityManager(  902): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.GenericMessagesProvider: pid=3785 uid=10064 gids={50064, 3003, 5012, 1028, 1015, 1023}
,I/ActivityManager(  902): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,D/PMS     (  902): releaseWL(41fcc708): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,I/ActivityManager(  902): Resuming delayed broadcast
,D/MessageFrequencyProvider( 3785): onCreate
,I/ActivityManager(  902): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=3800 uid=10084 gids={50084, 3003, 5012, 1028, 1015, 1023, 2001, 5006, 5001}
V/GetPrviateResource( 3785): GetPrviateResource
D/GenericMessagesProvider( 3785): query uri: content://htc-messages/wappush/count
V/GetPrviateResource( 3785): GetPrviateResource
E/SQLiteLog( 3785): (14) cannot open file at line 30190 of [00bb9c9ce4]
E/SQLiteLog( 3785): (14) os_unix.c:30190: (2) open(/data/data/com.htc.sense.mms/databases/wappush.db) - 
E/SQLiteConnection( 3785): DB info: sqlite3_open_v2, path: /data/data/com.htc.sense.mms/databases/wappush.db, flag: 1, ret: 14
E/SQLiteConnection( 3785): DB info: errno = 2, errno message = No such file or directory
E/SQLiteDatabase( 3785): Failed to open database '/data/data/com.htc.sense.mms/databases/wappush.db'.
E/SQLiteDatabase( 3785): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 3785): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3785): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3785): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3785): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3785): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3785): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3785): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3785): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3785): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3785): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
E/SQLiteDatabase( 3785): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
E/SQLiteDatabase( 3785): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 3785): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 3785): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
E/SQLiteDatabase( 3785): 	at android.os.Binder.execTransact(Binder.java:412)
E/SQLiteDatabase( 3785): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 3785): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
W/System.err( 3785): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 3785): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/System.err( 3785): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/System.err( 3785): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/System.err( 3785): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/System.err( 3785): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/System.err( 3785): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/System.err( 3785): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/System.err( 3785): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/System.err( 3785): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
W/System.err( 3785): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
W/System.err( 3785): 	at android.content.ContentProvider.query(ContentProvider.java:869)
W/System.err( 3785): 	at android.content.ContentProvider$Transport.query(ContentProvider.java,:212)
W/System.err( 3785): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
W/System.err( 3785): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err( 3785): 	at dalvik.system.NativeStart.run(Native Method)
D/Process (  902): killProcessQuiet, pid=3188
D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
D/TelephonyReceiver( 1219): switchBindHtcMsgCursor: null
I/ActivityManager(  902): Killing 3188:com.htc.widget.hmsproc2/u0a42 (adj 15): empty #17
D/Process (  902): killProcessQuiet, pid=3459
D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/TelephonyReceiver( 1219): bind: false
I/ActivityManager(  902): Killing 3459:com.google.android.partnersetup/u0a31 (adj 15): empty #17
D/TelephonyReceiver( 1219): switchBindHtcMsgCursor: null
I/ActivityManager(  902): Recipient 3459
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  902): Start proc com.google.android.gm for broadcast com.google.android.gm/.MailIntentReceiver: pid=3813 uid=10107 gids={50107, 3003, 5012, 1028, 1015}
,I/ActivityManager(  902): Recipient 3188
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0,
,D/MessageCustFlag( 3785): sense_version=6.0,
,D/BTAccessoryUtil( 3785): createReceiver
,D/BTAccessoryUtil( 3785): registerReceiver return intent = null
D/MessageCustFlag( 3785): sku_id=99
,W/SystemReader( 3785): Cannot find message_ambs_application_id, use default value instead
,D/Messaging( 3785): supportCMAS(SIE)/init? false/true
D/MmsConfig( 3785): networkCode: 
,D/MessageCustFlag( 3785): sku_id=99
D/MmsConfig( 3785): SIE smsPri: null
,D/MmsConfig( 3785): networkCode: 
,D/HtcTelephonyCapability( 3785): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 3785): The project is not dual project , phone_feature_type_stand_by = 0
,D/HtcBuildUtils( 3785): getRATByHtcTelephonyCapability:1
,W/SystemReader( 3785): Cannot find qct_8960_interface, use default value instead
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,W/GAV2    ( 3813): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  902): Delay finish: com.google.android.gm/.MailIntentReceiver
,D/PMS     (  902): acquireWL(424bd9b0): PARTIAL_WAKE_LOCK  Icing 0x1 1198 10028 null
,D/PMS     (  902): releaseWL(424bd9b0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  902): acquireWL(42607d40): PARTIAL_WAKE_LOCK  Icing 0x1 1198 10028 null
,D/PMS     (  902): releaseWL(42607d40): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/DotMatrix( 1581): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false
,I/RemoteViews( 1107): com.htc.updater (true,33751552)
D/NotificationService(  902): notification sound not played, stream=5 volume=0 always=false
,D/OnDemandProgressBar( 1107): release indeterminate drawable android.widget.OnDemandProgressBar{41ed9158 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1107): com.htc.updater 2 8 0 10
,I/ActivityManager(  902): Resuming delayed broadcast
,I/RemoteViews( 1107): com.htc.updater (true,33751552)
,D/OnDemandProgressBar( 1107): release indeterminate drawable android.widget.OnDemandProgressBar{41b81060 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/ActivityManager(  902): Delay finish: com.google.android.gm/.GmailReceiver
I/RemoteViews.Performance( 1107): com.htc.updater 1 8 0 10
,I/Gmail   ( 3813): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 3813): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 3813): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3813): calculateUnknownSyncRationalesAndPurgeInBackground: running
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/ActivityManager(  902): Resuming delayed broadcast
,I/ActivityManager(  902): Delay finish: com.google.android.gm/.GmailReceiver,
,I/ActivityManager(  902): Resuming delayed broadcast
,I/ActivityManager(  902): Delay finish: com.google.android.gm/.GmailReceiver
,I/NotifUtils( 3813): Validating Notification, mapSize: 0 getAttention: true ignoreUnobtrusive: false
,I/NotifUtils( 3813): validateNotifications - cancelling account 61035162 / folder -317575340
I/ActivityManager(  902): Resuming delayed broadcast
,I/ActivityManager(  902): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver: pid=3856 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,D/Process (  902): killProcessQuiet, pid=3525
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Killing 3525:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,I/ActivityManager(  902): Recipient 3525
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Babel   ( 3856): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 3856): MmsConfig.loadMmsSettings
,E/dalvikvm( 3856): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
,E/ProviderInstaller( 3856): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
E/dalvikvm( 3856): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
,E/ProviderInstaller( 3856): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
,V/JNIHelp ( 3856): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
,D/MmsCustomizationProvider( 3785): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 3785): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 3856): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 3856): MmsConfig.loadFromDatabase
,E/Babel   ( 3856): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 3856): MmsConfig.loadFromResources
,E/Babel   ( 3856): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 3856): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=3856, uid=10111, userID:0
,W/Settings( 3856): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=3856, uid=10111, userID:0
I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=3856, uid=10111, userID:0
I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=3856, uid=10111, userID:0
I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=3856, uid=10111, userID:0
I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=3856, uid=10111, userID:0
D/PMS     (  902): acquireWL(427c6f78): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 3856 10111 null
I/ActivityManager(  902): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,I/ProviderInstaller( 3856): Installed default security provider GmsCore_OpenSSL
,D/PMS     (  902): releaseWL(427c6f78): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  902): Resuming delayed broadcast
,D/PMS     (  902): acquireWL(42714d08): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 3856 10111 null
,I/ActivityManager(  902): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,D/PMS     (  902): releaseWL(42714d08): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  902): Resuming delayed broadcast
,D/PMS     (  902): acquireWL(426b07c8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 902 1000 null
,D/Process (  902): killProcessQuiet, pid=3545
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Killing 3545:com.htc.backup/1000 (adj 15): empty #17
,D/PMS     (  902): releaseWL(426b07c8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  902): Recipient 3545
,D/PMS     (  902): acquireWL(4265e518): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 3856 10111 null
,I/ActivityManager(  902): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,D/PMS     (  902): releaseWL(4265e518): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.talk (3856/10111)
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.talk (3856/10111)
,D/AutoSetting( 1388): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 1388): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1388): service - requestNLP() NetworkLocationProvider not enabled
,V/AlarmManager(  902): sending alarm PendingIntent{4268cc88: PendingIntentRecord{4268cc50 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1452552504234, Int=0
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.talk (3856/10111)
,D/Messaging( 3785): mNeedToUpdateDate2 start
,D/MmsConfig( 3785): packageName: com.htc.vvm.att does not exist
,D/TelephUtils( 1219): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
,D/MmsSmsV2Provider( 1219):  phoneType = -1
,D/MmsSmsV2Provider( 1219): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/ReportIndicatorCache( 3785): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 3785): 
D/MmsAsyncWorkHandler( 3785): HM tk = 20001
D/ReportIndicatorCache( 3785): MSG_QUERY_REPORTS >>
,D/SettingsManager( 3785): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41b44240
D/TelephUtils( 1219): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
I/Messaging( 3785): mccmnc> 
D/MmsSmsV2Provider( 1219):  phoneType = -1
,D/MmsSmsV2Provider( 1219): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/DraftCache( 3785): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 3785): [DraftCache/1] refresh
,D/MmsConfig( 3785): networkCode: 
,D/Messaging( 3785): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1219): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
,D/MmsSmsV2Provider( 1219):  phoneType = -1
D/MmsSmsV2Provider( 1219): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/Messaging( 3785): mNeedToUpdateDate2: false
,D/PhoneStorageUtil( 3785): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 3785): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 3785): createReceiver
,D/MessageCustFlag( 3785): sense_version=6.0
,D/TelephUtils( 1219): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
,D/Jerry   ( 3785): start to preload cursor >>>>>>>
,D/AccFlag ( 1219): sku_id=99
D/TelephUtils( 1219): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
V/MmsProvider( 1219): Update uri=content://mms, match=0
,V/MmsProvider( 1219): selection=st=129 AND m_type!=134
,D/Messaging( 3785): Reset downloading state: 0
,V/MmsSystemEventReceiver( 3785): TransactionService is going to be woken up.
I/ActivityManager(  902): Delaying start of: ServiceRecord{4265d0c0 u0 com.htc.sense.mms/.transaction.TransactionService}
,D/DraftCache( 3785): [DraftCache/388] rebuildCache
D/TelephUtils( 1219): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
D/MmsSmsV2Provider( 1219):  phoneType = -1
,D/MmsSmsV2Provider( 1219): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 3785): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/TelephUtils( 1219): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
,D/MmsSmsV2Provider( 1219):  phoneType = -1
,D/TelephUtils( 1219): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
,D/Jerry   ( 1219): URI_DRAFT
D/DraftCache( 3785): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 3785): [DraftCache/388] rebuildCache time: 1
,D/MmsAsyncWorkHandler( 3785): 
D/MmsAsyncWorkHandler( 3785): HM tk = 20002
,D/TelephUtils( 1219): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
,D/AccFlag ( 1219): sku_id=99
,D/Messaging( 3785): ViewCache CreatePreload
,D/Messaging( 3785): ViewCache CreatePreloadOnlyMultipleOpsList
,D/TelephUtils( 1219): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
D/Cust_MMSMS( 3785): _has_set_default_values_2=true
,D/AccFlag ( 1219): sku_id=99
,D/MsgPreferenceUtils( 3785): def_index: 0
,D/MsgPreferenceUtils( 3785): globalIndex = 1
D/MsgPreferenceUtils( 3785): phone state: true
D/MsgPreferenceUtils( 3785): sd state: false
,D/MsgPreferenceUtils( 3785): vIndex = 0
,D/PMS     (  902): acquireWL(4259fb00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(4259fb00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
,I/HtcPowerSaver(  902): >> updateStatus
D/DotMatrix( 1581): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1581): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1581): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,V/TransactionService( 3785): 1-Creating TransactionService
V/TransactionService( 3785): onStartCommand: 1
D/MmsSystemEventReceiver( 3785): unRegisterForConnectionStateChanges
V/TransactionService( 3785): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 3785): Loading previous transactions.
,D/TelephUtils( 1219): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
,D/AccFlag ( 1219): device_type: 1
D/TransactionService( 3785): Force set service start id to 1
V/TransactionService( 3785): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 3785): unRegisterForConnectionStateChanges
,I/ActivityManager(  902): Resuming delayed broadcast
D/TransactionService( 3785): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 3785): Destroying TransactionService
,V/TransactionService( 3785): 4-Handling incoming message: { when=-4ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 4
D/ConnectivityService(  902): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  902): Done.
,D/ConnectivityService(  902): Setting timer for 720seconds
,I/ActivityManager(  902): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
D/PackageBroadcastService( 1198): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.aurora
,I/PeopleContactsSync( 1198): CP2 sync disabled
I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1198, uid=10028, userID:0
D/PMS     (  902): acquireWL(42297868): PARTIAL_WAKE_LOCK  Icing 0x1 1198 10028 null
D/PMS     (  902): releaseWL(42297868): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ActivityManager(  902): Resuming delayed broadcast
I/[PluginManager]RegisterService( 1388): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.aurora
,I/[PluginManager]RegisterService( 1388): handle notify Blinkfeed plugin client changed
I/ActivityManager(  902): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  902): Resuming delayed broadcast
,I/IcingCorporaProvider( 2681): Updating corpora: APPS=com.htc.aurora, CONTACTS=MAYBE
I/ActivityManager(  902): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/IcingCorporaProvider( 2681): UpdateCorporaTask done [took 45 ms] updated apps [took 45 ms] 
I/ActivityManager(  902): Resuming delayed broadcast
,I/ActivityManager(  902): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  902): acquireWL(423b3c10): PARTIAL_WAKE_LOCK  AsyncService 0x1 3579 10160 null
,D/PMS     (  902): releaseWL(423b3c10): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  902): Resuming delayed broadcast
,D/PMS     (  902): acquireWL(42514ec0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3714 10070 null
,D/PMS     (  902): acquireWL(423dc858): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3714 10070 null
,I/ActivityManager(  902): Delay finish: com.htc.launcher/.receiver.NotificationReceiver
,E/TodoTaskNotifyService( 3714): java.lang.NullPointerException
,W/System.err( 3714): java.lang.NullPointerException
W/System.err( 3714): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3714): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3714): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3714): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 3714): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  902): releaseWL(42514ec0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,W/NotifyReceiver( 3714): stopSelfResult true
D/PMS     (  902): releaseWL(423dc858): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  902): Resuming delayed broadcast
,I/WSP     ( 1388): [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
,D/WeatherUtility( 1388): Weather sync is On
,I/WSP     ( 1388): [Receiver] next auto-sync alarm event is 60 mins later, at time: Tue Jan 12 00:48:26 CET 2016
,W/WSP     ( 1388): [Receiver] can't get active network info
I/ActivityManager(  902): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
D/ConnectivityService(  902): getActiveNetworkInfo called by com.htc.sense.hsp (1388/10053)
,V/WSP     ( 1388): [SyncService] no data connection, stop sync service
D/ConnectivityService(  902): getActiveNetworkInfo called by com.htc.sense.hsp (1388/10053)
,I/HtcModeClient( 1483): handler message = 4011
,E/HtcModeClient( 1483): Check connection and retry 7 times.
,W/MediaManager( 3608): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  902): Resuming delayed broadcast
,I/ActivityManager(  902): Delay finish: com.htc.task/.TodoReceiver
,D/TodoTaskshortcut( 3714): update TASK shortcut>
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.talk (3856/10111)
,I/SensorManager(  902): mEventCount = 600
,I/GAV2    ( 3813): Thread[GAThread,5,main]: No campaign data found.
,I/GAV4    ( 3856): Thread[GAThread,5,main]: No campaign data found.
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.talk (3856/10111)
,I/HtcModeClient( 1483): handler message = 4011
,E/HtcModeClient( 1483): Check connection and retry 8 times.
,I/CalendarProvider2( 1483): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 1483): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  902): Resuming delayed broadcast
,I/ActivityManager(  902): Delay finish: com.google.android.gm/.MailIntentReceiver
,I/ActivityManager(  902): Resuming delayed broadcast
,I/ActivityManager(  902): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3941 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/SyncApplication( 3941): Loading default preferences
,W/Resources( 3941): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WifiService(  902): New client listening to asynchronous messages
,D/SyncApplication( 3941): Overriding preferences with custom values
,D/SyncApplication( 3941): Updating preferences succeeded
,E/SyncApplication( 3941): Application created.
D/VolumeInfo( 3941): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 3941): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 3941): Found 0 mount point(s)
,V/VolumeInfo( 3941): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 3941): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,I/CalendarDefines( 3941): getNewCalendarAuthority()...
,D/VolumeInfo( 3941): Read the volume-id from the sd card: {61911E1D-261C-4FB6-8207-55BA8B8D5E9C}
,W/VolumeInfo( 3941): Can not create volume ID for unmounted volume null
I/PackageManager(  902):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3941, uid=10008, userID:0
W/PackageManager(  902): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  902):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3941, uid=10008, userID:0
,D/SyncApplication( 3941): enableAppOperation()+
,D/SyncApplication( 3941): enableAppOperation()-
,D/HTCUtilities( 3941): isNeorSinged() + 
W/PackageManager(  902): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/HTCUtilities( 3941): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 3941): isNeorSinged() return false
,D/CDMountReceiver( 3941): whether to enable CD Auto-mount: true
,D/CDMountReceiver( 3941): showNotification() contentText=If HTC Sync Manager setup doesnt start automatically on your computer, download from www.htc.com/hsm
,D/CDMountReceiver( 3941): enable CD Auto-mount: true
,D/DotMatrix( 1581): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
,D/HTCUtilities( 3941): enable auto-mount
,I/RemoteViews( 1107): com.nero.android.htc.sync (false,0)
,D/HTCUtilities( 3941): enable auto-mount
I/ActivityManager(  902): Delay finish: com.nero.android.htc.sync/.CDMountReceiver
,D/OnDemandProgressBar( 1107): release indeterminate drawable android.widget.OnDemandProgressBar{41f10cb0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/MountService(  902): mountISO: /system/etc/PCTOOL.ISO
D/MountService(  902): mountISO: /system/etc/PCTOOL.ISO
I/ActivityManager(  902): Resuming delayed broadcast
D/PMS     (  902): releaseWL(426635d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10008}
,D/PMS     (  902): acquireWL(4268eae8): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 3625 10154 null
,I/RemoteViews.Performance( 1107): com.nero.android.htc.sync 1 12 7 11
,I/RemoteViews( 1107): com.nero.android.htc.sync (false,0)
I/ActivityManager(  902): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,D/OnDemandProgressBar( 1107): release indeterminate drawable android.widget.OnDemandProgressBar{41c80838 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1107): com.nero.android.htc.sync 0 10 3 16
,W/ContextImpl( 3625): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 3625): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=3625, uid=10154, userID:0
,D/PMS     (  902): releaseWL(4268eae8): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/MusicLeanback( 3625): Conditions not met for autocaching.
,I/MusicLeanback( 3625): Stop autocaching.
I/ActivityManager(  902): Resuming delayed broadcast
I/ActivityManager(  902): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,W/MediaManager( 3608): [DualLensScanUtil]	mmpCursor count is 0
,D/Process (  902): killProcessQuiet, pid=3512
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Resuming delayed broadcast
I/ActivityManager(  902): Killing 3512:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  902): Recipient 3512
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  902): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3970 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,D/CalendarApplication( 3970): onCreate
D/ProviderChangeReceiver( 3970): ---------------------------------------------------
,D/ProviderChangeReceiver( 3970): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3970): start to updateAlertNotification!
,I/ActivityManager(  902): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=3984 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  902): killProcessQuiet, pid=3562
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  902): Killing 3562:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,D/AlertService( 3970): No fired or scheduled alerts
,D/HtcAlertUtils( 3970): -- cancelReminderNotification --
,D/HtcAlertUtils( 3970): broadcastExistReminder!
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  902): Recipient 3562
,D/DotMatrix( 1581): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,V/Settings:HtcSettingsApplication( 3984): [3984/3984] onCreate()
W/ContextImpl( 3984): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  902): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
,I/ActivityManager(  902): Resuming delayed broadcast
,D/Process (  902): killProcessQuiet, pid=3679
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  902): Killing 3679:com.htc.sense.news/u0a75 (adj 15): empty #17
,I/ActivityManager(  902): Recipient 3679
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  902): acquireWL(42690e70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{10073}
,V/AlarmManager(  902): sending alarm PendingIntent{41e46360: PendingIntentRecord{425d7820 com.android.vending startService}}, i=null, t=0, cnt=1, w=1452552513895, Int=0
,D/PMS     (  902): releaseWL(42690e70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,D/Finsky  ( 3475): [1] 5.onFinished: Installation state replication succeeded.
,D/PMS     (  902): acquireWL(421cdcb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(421cdcb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1581): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1581): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1581): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,I/ActivityManager(  902): Waited long enough for: ServiceRecord{425deb28 u0 com.htc.musicenhancer/.EnhancerService}
,I/SensorManager(  902): mEventCount = 750
,D/Process (  902): killProcessQuiet, pid=3727
,I/ActivityManager(  902): Killing 3727:com.htc.android.mail:sync/u0a63 (adj 15): empty #17
D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  902): Recipient 3727
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  902): Client connection lost with reason: 4
,I/HtcModeClient( 1483): handler message = 4011
,E/HtcModeClient( 1483): Check connection and retry 9 times.
,I/HtcModeClient( 1483): handler message = 4011
,E/HtcModeClient( 1483): Check connection and retry 10 times.
,I/SensorManager(  902): mEventCount = 900
,D/AutoSetting( 1388): service - handleMessage() stop self
,D/AutoSetting( 1388): service - handleMessage() quit looper
,D/AutoSetting( 1388): service - onDestroy() END
,I/ActivityManager(  902): Killing 3760:com.htc.task.gtask/u0a67 (adj 15): empty #17
D/Process (  902): killProcessQuiet, pid=3760
D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  902): Recipient 3760
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/libc    (  902): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  902): [NET] getaddrinfo-,err=8
D/libc    (  902): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  902): [NET] getaddrinfo-, 1
,D/libc    (  902): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
,D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/PMS     (  902): acquireWL(426ea998): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    (  902): [NET] getaddrinfo_proxy-
V/AlarmManager(  902): sending alarm PendingIntent{4223b238: PendingIntentRecord{41c3bfe0 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=81047, Int=0
D/PMS     (  902): releaseWL(426ea998): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ContactMessageStore( 1219): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1219): MSG_NOTIFY_CS_TO_SYNC <<
,I/HtcModeClient( 1483): handler message = 4011
,E/HtcModeClient( 1483): Check connection and retry 11 times.
,I/SensorManager(  902): mEventCount = 1050
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 5
,I/HtcModeClient( 1483): handler message = 4011
,E/HtcModeClient( 1483): Check connection and retry 12 times.
,I/SensorManager(  902): mEventCount = 1200
,I/HtcModeClient( 1483): handler message = 4011
,E/HtcModeClient( 1483): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1483): Don't start project servcice
,D/HtcModeClient( 1483): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1483): connectState: CONNECTION_READY = false
,D/SilentMusic( 1483): call stop
,D/HtcModeClient( 1483): close connection
,W/HtcModeClient( 1483): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1483): read the terminate packet, so break
,D/Process (  902): killProcessQuiet, pid=3647
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Killing 3647:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  902): Recipient 3647
,D/HABCtrl (  902): ALG=2, lsvalue=10(0th)->40(1th), last_level=1, lValue=64->64
,D/PMS     (  902): acquireWL(4238eab0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{420ebac0: PendingIntentRecord{4239b268 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=97070, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(4238eab0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ClockThread( 1107): now=1452552540061 next=59939
,D/PMS     (  902): acquireWL(425ac418): PARTIAL_WAKE_LOCK  Icing 0x1 1198 10028 null
,D/PMS     (  902): releaseWL(425ac418): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  902): acquireWL(42616280): PARTIAL_WAKE_LOCK  Icing 0x1 1198 10028 null
,D/PMS     (  902): releaseWL(42616280): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  902): acquireWL(4286d008): PARTIAL_WAKE_LOCK  Icing 0x1 1198 10028 null
,D/PMS     (  902): releaseWL(4286d008): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  902): acquireWL(42629a48): PARTIAL_WAKE_LOCK  Icing 0x1 1198 10028 null
,D/PMS     (  902): releaseWL(42629a48): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/SensorManager(  902): mEventCount = 1350
,I/ActivityManager(  902): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4003 uid=10077 gids={50077}
,D/PMS     (  902): acquireWL(424e3280): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{10077}
,V/AlarmManager(  902): sending alarm PendingIntent{4242dba0: PendingIntentRecord{426a1470 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1452552546256, Int=60000
,D/PMS     (  902): releaseWL(424e3280): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4003): SMSBackupAgentService started
,D/SMSBackup( 4003): Checking restore status
,D/SMSBackup( 4003): Restore complete
,D/SMSBackup( 4003): cancelCheckAlarm
,D/SMSBackup( 4003): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  902): killProcessQuiet, pid=3695
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Killing 3695:com.htc.sdm/u0a80 (adj 15): empty #17
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  902): Recipient 3695
,I/SensorManager(  902): mEventCount = 1500
,I/PMS     (  902): Going to sleep due to screen timeout...
,I/SensorManager(  902): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@4217f090
,W/SensorService(  902): Following SensorService logs are not warning, just make sure they are printed
I/ActivityManager(  902): mThumbnailWidth=360, mThumbnailHeight=640
,W/BatSI   (  902): Couldn't get kernel wake lock stats
,W/SensorService(  902): disable: get sensor name = CM36282 Light sensor
W/SensorService(  902): pid=902, uid=1000
W/SensorService(  902): Active sensors: size = 2
W/SensorService(  902): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  902): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  902): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@4217f090, eanble = 0, strlen(mName) = 59
W/SensorService(  902): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  902): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42118898
W/SensorService(  902): Listener[1] = com.htc.smartdim.sensor_eye@42076870
,W/SensorService(  902): void android::SensorService::listenerSensor(const char*, int32_t)--:
V/LightsService(  902): setLight #2: color=#0
D/qdlights(  902): set_light_buttons_func: on=0 brightness=0
V/LightsService(  902): setLight #0: color=#0
,W/PMS     (  902): mWirelessDisplayManager is null
,D/WirelessDisplayService(  902): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  902): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,D/SurfaceControl(  902): Excessive delay in blankDisplay() while turning screen off: 378ms
D/PMS     (  902): nativeSetInteractive:false
D/PMS     (  902): nativeSetInteractive:false done
D/PMS     (  902): nativeSetAutoSuspend:true
D/PMS     (  902): nativeSetAutoSuspend:true done
D/NfcService( 1230): ScreenObserver: OFF
,D/NfcService( 1230): applyRouting - 0
D/HABCtrl (  902): TPE algorithm. remove timeout.
D/PMS     (  902): OOBE c monitor 11
I/InputManager(  902): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  902): screenObserver, isScreenOn=false
I/InputMethodManagerService(  902): Disable input method client, pid=3337
,D/PMS     (  902): acquireWL(42773fc8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1230 1027 null
D/NfcService( 1230): applyRouting -2
,V/KeyguardServiceDelegate(  902): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@42633ee0)
,I/IntentController( 1107): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/PMN     (  902): wakingUp
D/PMS     (  902): releaseWL(42773fc8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,V/KeyguardServiceDelegate(  902): **** SHOWN CALLED ****
,D/WirelessDisplayService(  902): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  902): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  902): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
I/WindowManager(  902): No lock screen! windowToken=null
D/PMS     (  902): acquireWL(426db130): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  902): n_update end
D/PMS     (  902): releaseWL(426db130): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMN     (  902): onScreenOn
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1581): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1581): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1581): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/MtpService( 2233): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/HtcPowerSaver(  902): updateBatteryInfo
D/PowerUI ( 1107): closing low battery warning: level=100
,D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/MtpService( 2233): [MTP][onReceive]-
,D/NfcService( 1230): applyRouting - 0
,D/NfcService( 1230): applyRouting -2
D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/AlarmManager(  902): ACTION_SCREEN_ON
I/AlarmManager(  902): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  902): [AlarmQueuing] done recovering
I/AlarmManager(  902): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  902): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  902): acquireWL(427e0c10): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1230 1027 null
D/PMS     (  902): releaseWL(427e0c10): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
,D/AutoSetting( 1388): receiver - intent: android.intent.action.USER_PRESENT
D/TetherSettings( 3398): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3398): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3398): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3398): Cust_ConnectToPC   : spcsc>false
D/        ( 3398): Cust_ConnectToPC   : IPT>true
D/        ( 3398): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3398): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3398): hasRemovableStorageSlot: true
I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
D/SmartNS_Utility( 3398): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3398): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/AutoSetting( 1388): service - onCreate()
,I/PSReceiver( 3398): onReceive:android.intent.action.USER_PRESENT
I/ClockThread( 1107): stop update clock
D/WirelessDisplayService(  902): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  902): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  902): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  902): onReceive: action=android.intent.action.SCREEN_ON
V/NotificationService(  902): batLight: Full, plugged
V/LightsService(  902): setLight #8: color=#c8c800
D/qdlights(  902): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  902): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  902): setLight #8: color=#c800
D/qdlights(  902): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  902): [LedInfo] has indicator attribute
D/qdlights(  902): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  902): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,W/ContextImpl( 3398): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/WifiNative-wlan0(  902): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  902):    returned false
I/SmartNS_PSService( 3398): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3398): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3398):  defaultType:0
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,V/SRS_Proc(  371): ParamSet string: screen_state=on
,D/AutoSetting( 1388): service - AddressCache: using context: com.htc.Weather
V/NotificationService(  902): batLight: Full, plugged
V/LightsService(  902): setLight #8: color=#c8c800
D/qdlights(  902): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  902): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  902): setLight #8: color=#c800
D/qdlights(  902): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  902): [LedInfo] has indicator attribute
D/qdlights(  902): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  902): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
D/WirelessDisplayService(  902): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,D/AutoSetting( 1388): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/LocationManagerService(  902): request 425aa1a0 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
,D/NetworkPolicy(  902): updateScreenOn: false
D/LocationManagerService(  902): provider request: passive ProviderRequest[ON interval=0]
,I/ActivityManager(  902): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4025 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1581): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  902): acquireWL(426e87f8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1409 10028 null
D/PMS     (  902): releaseWL(426e87f8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/SensorManager(  902): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42118898
,W/SensorService(  902): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  902): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  902): pid=902, uid=1000
W/SensorService(  902): Active sensors: size = 2
W/SensorService(  902): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  902): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  902): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42118898, eanble = 0, strlen(mName) = 91
W/SensorService(  902): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  902): Listener[0] = com.htc.smartdim.sensor_eye@42076870
,W/SensorService(  902): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  902): goingToSleep
D/PMS     (  902): acquireWL(426e9270): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 902 1000 null
,D/AlarmManager(  902): ACTION_SCREEN_OFF
I/AlarmManager(  902): [AlarmQueuing] screen off now: 
I/AlarmManager(  902): [AlarmQueuing] data connection: true
,I/AlarmManager(  902): [AlarmQueuing] wifi connection: false
,W/ContextImpl( 4025): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/WifiDataStallTracker(  902): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  902): stopDataStallAlarm: current tag=19650 mDataStallAlarmIntent=null
,D/WifiNative-wlan0(  902): doBoolean: SET_SCREEN_ON 0
,D/WifiNative-wlan0(  902):    returned false
,D/PMS     (  902): releaseWL(426e9270): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
D/PMS     (  902): acquireWL(4262a2f8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 902 1000 null
D/PMS     (  902): releaseWL(4262a2f8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,V/SRS_Proc(  371): ParamSet string: screen_state=off
,D/ContactMessageStore( 1219): start background delete task...
D/ContactMessageStore( 1219): size: 0 , 0
,D/ContactMessageStore( 1219): Background delete complete
D/NetworkPolicy(  902): updateScreenOn: false
,D/SmartSyncUtils( 4025): isEpsOn(), nState = 0
D/PMS     (  902): acquireWL(426a4d58): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4025 1000 null
,D/PMS     (  902): releaseWL(426a4d58): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4025): getMobilePolicyEnabled, result = true
,I/PhoneStatusBar( 1107): removeHeadsNotification.gc: 57
,W/ContextImpl( 4025): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4025): isEpsOn(), nState = 0
D/SmartSyncUtils( 4025): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4025): isEpsOn(), nState = 0
,D/DotMatrix( 1581): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1581): [EventService] getTotalRam: 1873 Mb
D/WifiService(  902): New client listening to asynchronous messages
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  902): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42076870
W/SensorService(  902): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  902): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  902): pid=902, uid=1000
W/SensorService(  902): Active sensors: size = 1
W/SensorService(  902): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  902): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42076870, eanble = 0, strlen(mName) = 36
W/SensorService(  902): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  902): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  902): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  902): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  902): pid=902, uid=1000
W/SensorService(  902): Active sensors: size = 0
W/SensorService(  902): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42076870, eanble = 0, strlen(mName) = 36
W/SensorService(  902): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  902): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  902): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42076870
D/PMS     (  902): acquireWL(4286c1c8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1409 10028 null
D/PMS     (  902): releaseWL(4286c1c8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,E/ActivityThread(  902): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42731430 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  902): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42731430 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  902): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  902): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  902): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  902): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  902): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  902): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  902): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  902): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  902): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  902): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  902): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  902): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  902): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  902): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  902): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  902): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  902): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  902): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  902): 	at dalvik.system.NativeStart.main(Native Method)
D/AutoSetting( 1388): service - mHandler: cancel location update
D/AutoSetting( 1388): service -           changes count: 0
,D/ContactMessageStore( 1219): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1219): MSG_NOTIFY_CS_TO_SYNC <<
,D/Process (  902): killProcessQuiet, pid=3661
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Killing 3661:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  902): Recipient 3661
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  902): Waited long enough for: ServiceRecord{42694e20 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  902): acquireWL(4261d618): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(4261d618): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  902): updateBatteryInfo
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1581): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1581): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1581): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PowerUI ( 1107): closing low battery warning: level=100
D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  902): acquireWL(427d5d18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{42332438: PendingIntentRecord{42509b98 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141042, Int=0
,V/AlarmManager(  902): sending alarm PendingIntent{4223b238: PendingIntentRecord{41c3bfe0 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=141050, Int=0
,V/AlarmManager(  902): sending alarm PendingIntent{4238dea0: PendingIntentRecord{4250fa20 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141787, Int=0
,D/GpsLocationProvider(  902): ALARM_XTRA_TIMEOUT
,D/GpsLocationProvider(  902): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  902): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/libc    (  902): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  902): [NET] getaddrinfo-,err=8
D/libc    (  902): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  902): [NET] getaddrinfo-, 1
,D/libc    (  902): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
,D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    (  902): [NET] getaddrinfo_proxy-
D/PMS     (  902): acquireWL(42845608): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 902 1000 null
D/PMS     (  902): releaseWL(42845608): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/PMS     (  902): releaseWL(427d5d18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/AutoSetting( 1388): service - handleMessage() stop self
,D/AutoSetting( 1388): service - handleMessage() quit looper
,D/AutoSetting( 1388): service - onDestroy() END
,D/Process (  902): killProcessQuiet, pid=3800
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Killing 3800:com.htc.updater/u0a84 (adj 15): empty #17
,I/ActivityManager(  902): Recipient 3800
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  902): acquireWL(426c03f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{420ebac0: PendingIntentRecord{4239b268 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=157071, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(426c03f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 4
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.gms (1198/10028)
,D/PMS     (  902): acquireWL(4274f3c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  902): updateBatteryInfo
D/DotMatrix( 1581): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1581): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1581): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
D/PMS     (  902): releaseWL(4274f3c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/HtcPowerSaver(  902): >> updateStatus
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1219): switchBindHtcMsgCursor: null
,D/PMS     (  902): acquireWL(427c2da8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(427c2da8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
,D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/DotMatrix( 1581): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1581): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1581): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  902): acquireWL(42856338): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,D/libc    (  902): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  902): [NET] getaddrinfo-,err=8
D/libc    (  902): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  902): [NET] getaddrinfo-, 1
,D/libc    (  902): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
,D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    (  902): [NET] getaddrinfo_proxy-
V/AlarmManager(  902): sending alarm PendingIntent{4223b238: PendingIntentRecord{41c3bfe0 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=201867, Int=0
D/PMS     (  902): releaseWL(42856338): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 150000ms),E/cutils-trace( 4053): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4053): ====startRecUseTime====
D/htc.customization.log.level( 4053):  is 
W/CustomizationLogLevel( 4053): Level value is invalid, use default level 2
D/CustomizationManager( 4053):  Read ACC file spent 0.120 (s)
D/CIDMapFileReader( 4053): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4053): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4053): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4053): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4053): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4053): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4053): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4053): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4053): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4053): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4053): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4053): Parsing tag category name = system
I/CustomizationCIDLoader( 4053): Parsing tag category name = application
I/CustomizationCIDLoader( 4053): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4053): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4053): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4053): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4053): Parsing tag category name = Settings
D/CustomizationManager( 4053):  Read CID file spent 0.176 (s)
D/CustomizationManager( 4053):  All configurations done spent 0.177 (s)
W/HtcNativeFlag( 4053): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4053): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4053): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4053): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  902): deletePackageAsUser: pkg=com.example.hello, pid=4053, uid=2000 user=0
I/ActivityManager(  902): Force stopping com.example.hello appid=10356 user=-1: uninstall pkg
D/Process (  902): killProcessQuiet, pid=3337
D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
W/asset   (  902): Copying FileAsset 0x6304bdb8 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/ActivityManager(  902): Killing 3337:com.example.hello/u0a356 (adj 0): stop com.example.hello
W/ActivityManager(  902): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  902):   Force finishing activity ActivityRecord{41e8a278 u0 com.example.hello/.MainActivity t2}
W/PackageSettings(  902): Skipping PackageSetting{422b3690 com.test.thalitest/10348} due to missing metadata
E/JavaBinder(  902): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  902): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  902): Got RemoteException sending setActive(false) notification to pid 3337 uid 10356
E/JavaBinder( 1182): !!! FAILED BINDER TRANSACTION !!!
I/ActivityManager(  902): Force stopping com.example.hello appid=10356 user=0: pkg removed
D/DotMatrix( 1581): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1581): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1581): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
I/acms    ( 1762): Unregistering com.example.hello
E/acms    ( 1762): Could not unregister removed application com.example.hello
I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
D/PMS     (  902): acquireWL(4271def0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1409 10028 null
I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver packageName:com.example.hello
I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver replacing:false
W/GeofencerStateMachine( 1409): Ignoring removeGeofence because network location is disabled.
W/AccTypeManager( 1305): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1305): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  902): releaseWL(4271def0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/VoicemailCleanupService( 1273): Cleaning up data for package: com.example.hello
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/InputDispatcher(  902): channel '424ee360 com.example.hello.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  902): channel '424ee360 com.example.hello.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
W/InputDispatcher(  902): channel '42347dc0 com.example.hello.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  902): channel '42347dc0 com.example.hello.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
W/SystemReader( 1230): Cannot find nfc_is_upgrade_to_ar890, use default value instead
W/InputDispatcher(  902): Attempted to unregister already unregistered input channel '424ee360 com.example.hello.MainActivity (s)'
I/Prism.ItemManager( 1246): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1246): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/WindowState(  902): WIN DEATH: Window{424ee360 u0 com.example.hello/com.example.hello.MainActivity}
I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  902):   Scheme: "sms"
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
W/InputDispatcher(  902): Attempted to unregister already unregistered input channel '42347dc0 com.example.hello.MainActivity (s)'
I/WindowState(  902): WIN DEATH: Window{42347dc0 u0 com.example.hello/com.example.hello.MainActivity}
I/WindowManager(  902): WINDOW DIED Window{424ee360 u0 com.example.hello/com.example.hello.MainActivity}
I/WindowManager(  902): WINDOW DIED Window{42347dc0 u0 com.example.hello/com.example.hello.MainActivity}
D/AccTypeManager( 1305): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  902):   Scheme: "smsto"
I/Launcher( 1246): Deferring update until onResume
D/Launcher( 1246): waitUntilResume // bindAppsRemoved
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  902):   Scheme: "mms"
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
D/PackageBroadcastService( 1198): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
I/InputMethodManagerService(  902): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
E/ExternalAccountType( 1305): Unsupported attribute readOnly
I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  902):   Scheme: "mmsto"
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
I/ActivityManager(  902): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4068 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  902):   Scheme: "sms"
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  902):   Scheme: "smsto"
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  902):   Scheme: "mms"
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
I/ActivityManager(  902): Delaying start of: ServiceRecord{42818bc0 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  902):   Scheme: "mmsto"
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
D/PhoneApp( 1219): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/MultiDex( 4068): install
I/MultiDex( 4068): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4068): loading existing secondary dex files
I/ActivityManager(  902): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4086 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/MultiDex( 4068): load found 1 secondary dex files
I/MultiDex( 4068): install done
I/PeopleContactsSync( 1198): CP2 sync disabled
I/Icing   ( 1198): doRemovePackageData com.example.hello
I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1198, uid=10028, userID:0
D/PMS     (  902): acquireWL(4241d090): PARTIAL_WAKE_LOCK  Icing 0x1 1198 10028 null
D/PMS     (  902): releaseWL(4241d090): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ProviderInstaller( 4068): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  902): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 4086): install
I/MultiDex( 4086): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4086): loading existing secondary dex files
I/MultiDex( 4086): load found 1 secondary dex files
I/MultiDex( 4086): install done
I/ProviderInstaller( 4086): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
E/SQLiteDatabase( 1198): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
E/SQLiteDatabase( 1198): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1198): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1198): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 1198): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 1198): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1198): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1198): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1198): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 1198): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 1198): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 1198): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 1198): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1198): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1198): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 1198): 	at bxi.delete(SourceFile:258)
E/SQLiteDatabase( 1198): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 1198): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/SQLiteDatabase( 1198): 	at aqn.a(SourceFile:27)
E/SQLiteDatabase( 1198): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/SQLiteDatabase( 1198): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1198): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1198): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 1198): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  902): Resuming delayed broadcast
E/ClearPendingStateOp( 1198): Runtime exception while performing operation
E/ClearPendingStateOp( 1198): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 1198): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 1198): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/ClearPendingStateOp( 1198): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/ClearPendingStateOp( 1198): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 1198): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 1198): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 1198): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/ClearPendingStateOp( 1198): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/ClearPendingStateOp( 1198): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/ClearPendingStateOp( 1198): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/ClearPendingStateOp( 1198): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/ClearPendingStateOp( 1198): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/ClearPendingStateOp( 1198): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/ClearPendingStateOp( 1198): 	at bxi.delete(SourceFile:258)
E/ClearPendingStateOp( 1198): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/ClearPendingStateOp( 1198): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/ClearPendingStateOp( 1198): 	at aqn.a(SourceFile:27)
E/ClearPendingStateOp( 1198): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/ClearPendingStateOp( 1198): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ClearPendingStateOp( 1198): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ClearPendingStateOp( 1198): 	at android.os.Looper.loop(Looper.java:157)
E/ClearPendingStateOp( 1198): 	at android.os.HandlerThread.run(HandlerThread.java:61)
F/ClearPendingStateOp( 1198): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 1198): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 1198): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 1198): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
F/ClearPendingStateOp( 1198): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
F/ClearPendingStateOp( 1198): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 1198): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 1198): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 1198): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
F/ClearPendingStateOp( 1198): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
F/ClearPendingStateOp( 1198): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
F/ClearPendingStateOp( 1198): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
F/ClearPendingStateOp( 1198): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
F/ClearPendingStateOp( 1198): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
F/ClearPendingStateOp( 1198): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
F/ClearPendingStateOp( 1198): 	at bxi.delete(SourceFile:258)
F/ClearPendingStateOp( 1198): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
F/ClearPendingStateOp( 1198): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
F/ClearPendingStateOp( 1198): 	at aqn.a(SourceFile:27)
F/ClearPendingStateOp( 1198): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
F/ClearPendingStateOp( 1198): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
F/ClearPendingStateOp( 1198): 	at android.os.Handler.dispatchMessage(Handler.java:102)
F/ClearPendingStateOp( 1198): 	at android.os.Looper.loop(Looper.java:157)
F/ClearPendingStateOp( 1198): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process (  902): killProcessQuiet, pid=3856
I/ActivityManager(  902): Killing 3856:com.google.android.talk/u0a111 (adj 15): empty #17
D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
W/SQLiteConnectionPool( 1198): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/help_responses.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
E/SharedPreferencesImpl( 1182): Couldn't rename file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml to backup file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml.bak
I/[PluginManager]RegisterService( 1388): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.example.hello
E/SQLiteLog( 1388): (3850) statement aborts at 44: [UPDATE plugin SET removed=? WHERE package_id IN ( SELECT _id FROM plugin_pkg WHERE package=? )] disk I/O error
E/SQLiteDBG( 1388): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/user/0/com.htc.sense.hsp/databases/registry.db, handle = 0x5ca46838
W/[PluginManager]RegisterService( 1388): provider may killed!
W/[PluginManager]RegisterService( 1388): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
W/[PluginManager]RegisterService( 1388): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
W/[PluginManager]RegisterService( 1388): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
W/[PluginManager]RegisterService( 1388): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
W/[PluginManager]RegisterService( 1388): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
W/[PluginManager]RegisterService( 1388): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1645)
W/[PluginManager]RegisterService( 1388): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1591)
W/[PluginManager]RegisterService( 1388): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.update(Unknown Source)
W/[PluginManager]RegisterService( 1388): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
W/[PluginManager]RegisterService( 1388): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
W/[PluginManager]RegisterService( 1388): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/[PluginManager]RegisterService( 1388): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/[PluginManager]RegisterService( 1388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/[PluginManager]RegisterService( 1388): 	at android.os.Looper.loop(Looper.java:157)
W/[PluginManager]RegisterService( 1388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  902): Can't write: system_app_wtf
E/DropBoxManagerService(  902): java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  902): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  902): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  902): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  902): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  902): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  902): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  902): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  902): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  902): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  902): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  902): 	... 5 more
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  902): Recipient 3856
I/[PluginManager]RegisterService( 1388): handle notify Blinkfeed plugin client changed
W/SQLiteConnectionPool( 1198): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/metrics.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
W/SQLiteConnectionPool( 1198): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/history_query.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/Prism.PackageStateRece_( 1246): action: android.intent.action.PACKAGE_REMOVED
I/IcingCorporaProvider( 2681): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
I/ActivityManager(  902): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4109 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4068): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4068): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4068): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4068): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4068): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4068): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4068): 	at ctn.run(SourceFile:985)
W/dalvikvm( 4068): threadid=12: thread exiting with uncaught exception (group=0x4170ae30)
E/AndroidRuntime( 4068): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4068): Process: com.google.android.gms.drive, PID: 4068
E/AndroidRuntime( 4068): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4068): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4068): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4068): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4068): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4068): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4068): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4068): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4068): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4068): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4068): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4068): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4068): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4068): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4068): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4068): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4068): 	at ctn.run(SourceFile:985)
E/ActivityManager(  902): App crashed! Process: com.google.android.gms.drive
E/DropBoxManagerService(  902): Can't write: system_app_crash
E/DropBoxManagerService(  902): java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  902): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  902): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  902): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  902): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  902): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  902): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  902): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  902): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  902): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  902): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  902): 	... 5 more
D/Process ( 4068): killProcess, pid=4068
D/Process ( 4068): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/SQLiteLog( 2681): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2681): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x63ed4e60
W/dalvikvm( 2681): threadid=16: thread exiting with uncaught exception (group=0x4170ae30)
E/AndroidRuntime( 2681): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2681): Process: com.google.android.googlequicksearchbox:search, PID: 2681
E/AndroidRuntime( 2681): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2681): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2681): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2681): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2681): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2681): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2681): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2681): 	at cid.d(PG:186)
E/AndroidRuntime( 2681): 	at clo.g(PG:594)
E/AndroidRuntime( 2681): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2681): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2681): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2681): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2681): 	at clr.tL(PG:827)
E/AndroidRuntime( 2681): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2681): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2681): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2681): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2681): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2681): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  902): App crashed! Process: com.google.android.googlequicksearchbox:search
D/Process ( 2681): killProcess, pid=2681
D/Process ( 2681): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  902): Can't write: system_app_crash
E/DropBoxManagerService(  902): java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  902): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  902): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  902): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  902): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  902): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  902): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  902): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  902): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  902): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  902): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  902): 	... 5 more
W/PackageManager(  902): Unable to load service info ResolveInfo{4250b120 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  902): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  902): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  902): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  902): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  902): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  902): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  902): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  902): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  902): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  902): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  902): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  902): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  902): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  902): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  902): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  902): 	at dalvik.system.NativeStart.main(Native Method)
I/ActivityManager(  902): Recipient 2681
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  902): Client com.google.android.googlequicksearchbox (pid 2681): Died!
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  902): Recipient 4068
D/WifiService(  902): Client connection lost with reason: 4
I/ActivityManager(  902): Process com.google.android.gms.drive (pid 4068) has died.
W/ActivityManager(  902): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
I/ActivityManager(  902): Process com.google.android.googlequicksearchbox:search (pid 2681) has died.
W/ActivityManager(  902): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 1000ms
W/ActivityManager(  902): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
D/RemoteDisplayProvider(  902): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  902): start
W/AtomicFile(  902): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  902): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
E/SQLiteDatabase( 4109): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4109): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4109): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4109): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4109): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4109): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4109): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4109): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4109): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4109): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4109): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4109): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4109): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4109): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4109): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4109): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4109): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4109): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4109): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4109): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4109): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4109): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4109): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4109): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4109): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4109): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4109): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4109): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4109): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4109): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4109): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4109): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4109): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4109): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4109): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4109): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4109): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4109): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4109): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4109): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4109): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4109): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4109): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4109): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4109): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4109): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4109): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4109): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4109): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4109): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4109): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4109): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4109): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4109): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4109): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4109): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4109): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4109): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4109): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4109): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4109): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4109): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4109): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4109): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4109): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4109): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4109): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4109): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4109): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4109): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4109): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4109): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4109): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4109): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4109): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4109): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4109): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4109): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4109): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4109): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4109): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4109): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4109): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4109): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4109): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4109): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4109): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4109): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4109): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4109): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4109): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4109): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4109): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4109): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4109): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4109): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4109): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4109): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4109): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4109): threadid=11: thread exiting with uncaught exception (group=0x4170ae30)
E/ActivityManager(  902): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4109): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4109): Process: com.google.android.apps.docs, PID: 4109
E/AndroidRuntime( 4109): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4109): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4109): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4109): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4109): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4109): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4109): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4109): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4109): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4109): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4109): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4109): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4109): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4109): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4109): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4109): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4109): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4109): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4109): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  902): Can't write: system_app_crash
E/DropBoxManagerService(  902): java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  902): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  902): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  902): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  902): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  902): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  902): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  902): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  902): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  902): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  902): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  902): 	... 5 more
D/Process ( 4109): killProcess, pid=4109
D/Process ( 4109): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  902): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4127 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  902): Recipient 4109
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Process (  902): killProcessQuiet, pid=3785
D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  902): Killing 3785:com.htc.sense.mms/u0a64 (adj 15): empty #17
I/ActivityManager(  902): Process com.google.android.apps.docs (pid 4109) has died.
I/ActivityManager(  902): Recipient 3785
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ContextImpl( 4127): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  902): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4140 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4127): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4127): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4127): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4127): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4127): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4127): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4127): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4127): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4127): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4127): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4127): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4127): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4127): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4127): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4127): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4127): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4127): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4127): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4127): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4127): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4127): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4127): threadid=10: thread exiting with uncaught exception (group=0x4170ae30)
E/ActivityManager(  902): App crashed! Process: com.android.keychain
E/AndroidRuntime( 4127): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4127): Process: com.android.keychain, PID: 4127
E/AndroidRuntime( 4127): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4127): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4127): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4127): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4127): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4127): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4127): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4127): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4127): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4127): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4127): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4127): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4127): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4127): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4127): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4127): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4127): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4127): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4127): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4127): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  902): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4127): killProcess, pid=4127
D/Process ( 4127): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  902): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  902): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452552659626.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  902): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  902): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  902): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  902): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  902): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  902): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  902): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  902): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  902): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  902): 	... 4 more
I/ActivityManager(  902): Recipient 4127
I/ActivityManager(  902): Process com.android.keychain (pid 4127) has died.
W/ActivityManager(  902): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10600ms
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/AppTag  ( 4140): getInstance(Context context)
D/AppTag  ( 4140): getInstance(Context context)
D/AppTag  ( 4140): onCreate()
D/PMS     (  902): acquireWL(42723c08): PARTIAL_WAKE_LOCK  AsyncService 0x1 3579 10160 null
D/PMS     (  902): releaseWL(42723c08): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  902): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4157 uid=10098 gids={50098, 3003, 5012}
I/DeviceManagement( 4157): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4157 dbg=false s=true
I/DeviceManagement( 4157): PackageUpdateReceiver: vvv Package removed: [com.example.hello]
I/DeviceManagement( 4157): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.example.hello, operation=3}]]
I/DeviceManagement( 4157): WorkflowService: Starting workflow service
I/DeviceManagement( 4157): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b6d300] args=[Bundle[mParcelledData.dataSize=116]]
I/DeviceManagement( 4157): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4157): PackageUpdateWorkflow: Package update: package=com.example.hello, operation=REMOVE
I/DeviceManagement( 4157): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4157): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  902): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4172 uid=10099 gids={50099, 3003, 5012}
I/DeviceManagement( 4157): BackgroundController: *** Processing package remove for appID=com.example.hello
I/DeviceManagement( 4157): SessionStateController: Checking invariants...
I/Prism.ItemManager( 1246): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1246): loadItems() com.htc.launcher.pageview.WidgetManager@41bccf68 +
I/Prism.WidgetManager( 1246): onLoadItems() +
D/Documents( 4172): Loading roots for com.android.providers.downloads.documents
,D/Documents( 4172): Loading roots for com.android.externalstorage.documents

```
