#### Test 503880196b4ec73_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/Process (  903): killProcessQuiet, pid=2935
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
--------- beginning of /dev/log/system
I/ActivityManager(  903): Killing 2935:com.zoodles.kidmode/u0a149 (adj 15): empty #17
D/SMSBackup( 3152): Got a database change event
I/ActivityManager(  903): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=3250 uid=10075 gids={50075, 3003, 5012, 1028, 1015, 5001, 1023}
D/Process (  903): killProcessQuiet, pid=2964
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Killing 2964:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
I/ActivityManager(  903): Recipient 2964
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=3264 uid=10091 gids={50091, 3003, 5012}
V/AlarmManager(  903): sending alarm PendingIntent{4230af68: PendingIntentRecord{4248f3a8 com.htc.mobiledata startService}}, i=com.htc.mobiledata.intent.REQUEST, t=2, cnt=1, w=53555, Int=0
I/ActivityManager(  903): Recipient 2935
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ImageRamCache( 3250): create image Cache, size: 31457280.
I/ImageRamCache( 3250): [resize] ImageRamCache resized to: 12Mb.
I/ImageRamCache( 3250): create image Cache, size: 12582912.
I/FeedSettings( 3250): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 3250): GroupBudget 0.500000 0.380000
I/FeedSettings( 3250): GroupBudget 60 45 15
I/Prism.ExternalStringMa_( 3250): changeLocale(): en_GB
D/MessagingNotification( 2552): New incoming message, can't cancel notification now
D/MessagingNotification( 2552): newMsgCnt: 0, false
I/Prism.AllAppsOptionsMa_( 3250): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 3250): loadGridSize() with Alternative
I/ActivityManager(  903): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3280 uid=10091 gids={50091, 3003, 5012}
D/CustomHighlightReceiver( 3250): [custom highlight] onReceive
D/CustomHighlightService( 3250): [custom highlight] onHandleIntent
I/ActivityManager(  903): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
D/NewsDB  ( 3250): set custom highlight []
D/CustomHighlightService( 3250): [custom highlight] set tags 
D/Process (  903): killProcessQuiet, pid=2992
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/GCM     ( 1337): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  903): Resuming delayed broadcast
I/ActivityManager(  903): Killing 2992:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
I/ActivityManager(  903): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  903): Recipient 2992
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Resuming delayed broadcast
D/MessagingShortcutReceiver( 2552): keep hiding shortcut bubble
D/MessagingShortcut( 2552): updateMsgShortcut, msg count> -1
D/MessagingShortcut( 2552): After query: 0
D/MessagingShortcut( 2552): mPresentUnreadCount: -1
D/MessagingShortcut( 2552): setMsgShortcutDrawable> 0
D/MessagingShortcut( 2552): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1528): [EventService] reorderNotification, total:1
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/ActivityManager(  903): Delay finish: com.htc.task/.TodoReceiver
D/TodoTaskshortcut( 3209): update TASK shortcut>
I/ActivityManager(  903): Resuming delayed broadcast
D/HtcBroadcastReceiver( 1216): onReceive: com.htc.launcher.action.ACTION_ITEM_ADDED
D/MdScBoot( 3264): [af8.1.] 30@-202028 -> 40@-202058
I/ActivityManager(  903): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver: pid=3297 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
D/MdScBoot( 3264): [af8.2.] 40@-202058
D/Process (  903): killProcessQuiet, pid=3006
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
D/Process (  903): killProcessQuiet, pid=3019
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3006:com.android.smith/u0a163 (adj 15): empty #17
I/ActivityManager(  903): Killing 3019:com.google.android.youtube/u0a168 (adj 15): empty #17
I/ActivityManager(  903): Recipient 3006
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Recipient 3019
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  903): Client com.google.android.youtube (pid 3019): Died!
I/Babel   ( 3297): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 3297): MmsConfig.loadMmsSettings
E/dalvikvm( 3297): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
E/ProviderInstaller( 3297): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
E/dalvikvm( 3297): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
E/ProviderInstaller( 3297): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
V/JNIHelp ( 3297): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
D/MmsCustomizationProvider( 2552): query uri: content://htc-mms-customization/mms-ua/ua_string
D/MmsCustomizationProvider( 2552): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 3297): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/Babel   ( 3297): MmsConfig.loadFromDatabase
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=3297, uid=10111, userID:0
W/Settings( 3297): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Babel   ( 3297): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 3297): MmsConfig.loadFromResources
E/Babel   ( 3297): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 3297): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=3297, uid=10111, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=3297, uid=10111, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=3297, uid=10111, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=3297, uid=10111, userID:0
D/Process (  903): killProcessQuiet, pid=2975
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=3297, uid=10111, userID:0
I/ActivityManager(  903): Killing 2975:com.android.settings/1000 (adj 15): empty #17
D/GCM     ( 1337): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Recipient 2975
D/MtpReceiver( 2226): [MTP][MtpReceiver][onReceive]+
D/MtpReceiver( 2226): [MTP][MtpReceiver][onReceive]1-
D/MtpReceiver( 2226): [MTP][handleMessage][startService]
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1746/10178)
D/MtpReceiver( 2226): [MTP][handleMessage][UsbManager.USB_CONNECTED][insert]+
D/MtpReceiver( 2226): [MTP][handleMessage]-
D/MtpService( 2226): [MTP] startForeground
D/DotMatrix( 1528): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
I/ProviderInstaller( 3297): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  903): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3330 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
I/RemoteViews( 1103): com.android.providers.media (false,0)
I/RemoteViews.Performance( 1103): com.android.providers.media 1 2 10
D/MtpService( 2226): updating state; isCurrentUser=true, mMtpLocked=false
I/RemoteViews( 1103): com.android.providers.media (false,0)
I/RemoteViews.Performance( 1103): com.android.providers.media 1 1 15
D/MtpDatabase( 2226): TotalSize=1918604,MediaCacheLimit=6000
D/MtpService( 2226): [isMtpConnected] connected: true
D/SyncApplication( 3330): Loading default preferences
W/Resources( 3330): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
D/Process (  903): killProcessQuiet, pid=3069
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3069:com.htc.sense.browser/u0a12 (adj 15): empty #17
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Recipient 3069
D/WifiService(  903): New client listening to asynchronous messages
D/SyncApplication( 3330): Overriding preferences with custom values
D/SyncApplication( 3330): Updating preferences succeeded
E/SyncApplication( 3330): Application created.
D/VolumeInfo( 3330): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
D/VolumeInfo( 3330): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 3330): Found 0 mount point(s)
V/VolumeInfo( 3330): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
D/VolumeInfo( 3330): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
D/CustomizationManager( 3294): ====startRecUseTime====
D/htc.customization.log.level( 3294):  is 
W/CustomizationLogLevel( 3294): Level value is invalid, use default level 2
D/VolumeInfo( 3330): Read the volume-id from the sd card: {61911E1D-261C-4FB6-8207-55BA8B8D5E9C}
W/VolumeInfo( 3330): Can not create volume ID for unmounted volume null
I/CalendarDefines( 3330): getNewCalendarAuthority()...
D/SyncApplication( 3330): enableAppOperation()+
D/SyncApplication( 3330): enableAppOperation()-
D/HTCUtilities( 3330): isNeorSinged() + 
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3330, uid=10008, userID:0
W/PackageManager(  903): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3330, uid=10008, userID:0
W/PackageManager(  903): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
D/HTCUtilities( 3330): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
D/HTCUtilities( 3330): isNeorSinged() return false
D/CDMountReceiver( 3330): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
D/CDMountReceiver( 3330): USB connected to PC
D/FOTAReceiver( 3330): onReceive() enter 
D/FOTAReceiver( 3330): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
D/Process (  903): killProcessQuiet, pid=3108
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Start proc com.android.settings for broadcast com.android.settings/.MLReceiver: pid=3349 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  903): Killing 3108:com.google.android.partnersetup/u0a31 (adj 15): empty #17
D/CustomizationManager( 3294):  Read ACC file spent 0.065 (s)
D/CIDMapFileReader( 3294): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3294): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3294): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3294): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3294): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3294): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3294): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3294): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3294): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3294): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3294): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3294): Parsing tag category name = system
I/CustomizationCIDLoader( 3294): Parsing tag category name = application
I/CustomizationCIDLoader( 3294): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3294): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3294): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3294): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3294): Parsing tag category name = Settings
D/CustomizationManager( 3294):  Read CID file spent 0.112 (s)
D/CustomizationManager( 3294):  All configurations done spent 0.112 (s)
W/HtcNativeFlag( 3294): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3294): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3294): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3294): Fail to get flag for type 'language', use default value: -1
I/ActivityManager(  903): Recipient 3108
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/CpuWake (  903): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  903): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  903): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  903): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  903): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  903): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  903): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3294
W/asset   (  903): Copying FileAsset 0x6952bb60 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/Intent  (  903): @test_code: getHtcIntentFlag: 0 obj: 1114503616
D/PMS     (  903): acquireHCC(427e4208): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 903 1000 null
D/PMS     (  903): acquireHCC(42317220): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 903 1000 null
I/FeedHostManager( 1244): [onPause]
I/FeedProviderManager( 1244): onPause
I/FeedHostManager( 1244): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41bf0a48
I/SocialFeedProvider( 1244): +onPause
I/SocialFeedProvider( 1244): -onPause
E/cutils-trace( 3294): Error opening trace file: No such file or directory (2)
D/HtcFingerPrintQuickLaunchProvider( 3349): -onCreate()
D/PMS     (  903): acquireWL(425db730): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 903 1000 null
I/ActivityManager(  903): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3363 uid=10355 gids={50355, 3003, 5012, 3001, 3002}
V/Settings:HtcSettingsApplication( 3349): [3349/3349] onCreate()
D/TetherSettings( 3349): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3349): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3349): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3349): Cust_ConnectToPC   : spcsc>false
D/        ( 3349): Cust_ConnectToPC   : IPT>true
D/        ( 3349): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3349): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/TetherSettings( 3349): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3349): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3349): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3349): Cust_ConnectToPC   : spcsc>false
D/        ( 3349): Cust_ConnectToPC   : IPT>true
D/        ( 3349): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3349): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3349): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3349): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3349): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
D/SmartNS_Utility( 3349): usb_cable_connect = 1
D/SmartNS_Utility( 3349): usb_denied = 0
W/asset   ( 3363): Copying FileAsset 0x5c701048 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/SmartNS_NSReceiver( 3349): locked:falsesecurity:falseisLocked:false
D/SmartNS_NSReceiver( 3349): USB = true hasTethered = false isNSOpening: false
I/PSReceiver( 3349): onReceive:com.htc.intent.action.USB_CONNECT2PC
I/SmartNS_PSService( 3349): onReceive:com.htc.intent.action.USB_CONNECT2PC
W/Settings( 3349): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3349):  defaultType:0
I/SmartNS_PSService( 3349): fail notificaiton:false
D/SmartNS_Utility( 3349): usb_cable_connect = 1
D/SmartNS_Utility( 3349): usb_denied = 0
I/SmartNS_PSService( 3349): usb notificaiton:true
W/ContextImpl( 3349): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
V/Tethering(  903): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Tethering(  903): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  903): bSetPropertyMultiRAB:false
D/ConnectivityService(  903): getActiveNetworkInfo called by com.android.settings (3349/1000)
I/TrimMemoryManager( 1244): [trimMemory] 20
D/SmartNS_Utility( 3349): usb_cable_connect = 1
D/SmartNS_Utility( 3349): usb_denied = 0
I/SmartNS_PSService( 3349): usb notificaiton:true
D/DotMatrix( 1528): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
V/Tethering(  903): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Tethering(  903): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  903): bSetPropertyMultiRAB:false
V/WebViewChromiumFactoryProvider( 3363): Binding Chromium to main looper Looper (main, tid 1) {41a7e128}
I/LibraryLoader( 3363): Expected native library version number "",actual native library version number ""
I/chromium( 3363): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3363): Initializing chromium process, renderers=0
D/ConnectivityService(  903): getActiveNetworkInfo called by com.android.settings (3349/1000)
D/SmartNS_Utility( 3349): usb_cable_connect = 1
D/SmartNS_Utility( 3349): usb_denied = 0
D/DotMatrix( 1528): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
I/RemoteViews( 1103): com.android.settings (true,33751552)
I/RemoteViews.Performance( 1103): com.android.settings 2 1 10
I/SmartNS_PSService( 3349): KeyGuard locked:falseKeyGuard is secured:false
D/SmartNS_PSService( 3349): USB Plugged, Set USBPlugged=  truePSenabled:false
I/RemoteViews( 1103): com.android.settings (true,33751552)
I/RemoteViews.Performance( 1103): com.android.settings 1 1 10
D/Process (  903): killProcessQuiet, pid=3120
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  903): acquireWL(427fba00): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  903): acquireWL(42598200): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
I/ActivityManager(  903): Killing 3120:com.htc.contacts/u0a41 (adj 15): empty #17
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  903): java.lang.Throwable: stack dump
W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  903): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  903): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  903): 	at android.os.Binder.execTransact(Binder.java:412)
D/BluetoothManagerService(  903): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42474088:true
W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 3363): 1101609760: getState() :  mService = null. Returning STATE_OFF
D/PMS     (  903): releaseWL(42598200): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
W/WeatherUtility( 3180): can't get weather sync account
I/Adreno-EGL( 3363): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3363): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3363): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3363): Local Branch: 
I/Adreno-EGL( 3363): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3363): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3363):                  aa63bbd948f41d15fc72f585e
W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
D/AppWidgetHostView( 1244): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider})
I/RemoteViews( 1244): com.google.android.googlequicksearchbox (false,0)
I/RemoteViews.Performance( 1244): com.google.android.googlequicksearchbox 1 1 5
I/ActivityManager(  903): Delay finish: pl.k2.droidoaudioteka/.ui.widgets.BigWidgetProvider
D/AppWidgetHostView( 1244): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{pl.k2.droidoaudioteka/pl.k2.droidoaudioteka.ui.widgets.BigWidgetProvider})
I/ActivityManager(  903): Resuming delayed broadcast
I/RemoteViews( 1244): pl.k2.droidoaudioteka (false,0)
I/RemoteViews.Performance( 1244): pl.k2.droidoaudioteka 1 0 8
W/chromium( 3363): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/ActivityManager(  903): Delay finish: com.google.android.gms/.playlog.service.MonitorAlarmReceiver
D/LocationManagerService(  903): getAllProviders()=[passive, gps, network]
W/dalvikvm( 3363): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3363): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3363): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3363): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3363): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/WeatherRequest( 3180): request cur loc, but there is no sys cur
W/Settings( 3180): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Recipient 3120
W/dalvikvm( 3363): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3363): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3363): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3363): CordovaWebView is running on device made by: HTC
,D/AppWidgetHostView( 1244): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
I/RemoteViews( 1244): com.htc.widget.weatherclock (true,33751552)
I/RemoteViews.Performance( 1244): com.htc.widget.weatherclock 0 8 17
I/ActivityManager(  903): Resuming delayed broadcast
W/AwContents( 3363): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  903): Displayed com.example.hello/.MainActivity: +310ms
W/ResourceType( 3363): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 3363): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41ac4e68, mServedView=org.apache.cordova.engine.SystemWebView{41a8ae40 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1180): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1180): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1180): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1180): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  903): Disable input method client, pid=1244
I/InputMethodManagerService(  903): Enable input method client, pid=3363
W/AwContents( 3363): nativeOnDraw failed; clearing to background color.
D/PMS     (  903): releaseWL(425db730): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  903): sending alarm PendingIntent{4205da38: PendingIntentRecord{42058960 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=54775, Int=0
I/ClockThread( 1103): now=1448306460027 next=59973
V/AlarmManager(  903): sending alarm PendingIntent{428415f0: PendingIntentRecord{425693c8 com.google.android.gms broadcastIntent}}, i=null, t=1, cnt=1, w=1448306459937, Int=0
I/ActivityManager(  903): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1194/10028)
E/AndroidProtocolHandler( 3363): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/chromium( 3363): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1194/10028)
I/ActivityManager(  903): Resuming delayed broadcast
I/ActivityManager(  903): Delay finish: com.google.android.gms/.security.snet.SnetBootCompletedReceiver
V/AlarmManager(  903): sending alarm PendingIntent{4259f3e0: PendingIntentRecord{42729628 com.google.android.gms startService}}, i=null, t=0, cnt=17055, w=84918423, Int=84918423
I/ActivityManager(  903): Resuming delayed broadcast
D/JsMessageQueue( 3363): Set native->JS mode to OnlineEventsBridgeMode
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1194/10028)
I/AdsMeasurementBroadcastReceiver( 1194): Reporting settings might have changed, alerting AdsMeasurementService
D/AdsMeasurementBroadcastReceiver( 1194): Unauthorized to start the main service
D/SnetService( 1194): snet destroyed
I/ActivityManager(  903): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
D/PackageBroadcastService( 1194): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
D/PMS     (  903): acquireWL(428237f8): PARTIAL_WAKE_LOCK  Icing 0x1 1194 10028 null
D/PMS     (  903): releaseWL(428237f8): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/PeopleContactsSync( 1194): CP2 sync disabled
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1194, uid=10028, userID:0
D/jxcore_app_log( 3363): JniHelper::setJavaVM(0x41551048), pthread_self() = 1658191096
D/JX-Cordova( 3363): jxcore cordova android initializing
W/jxcore-log( 3363): Initializing JXcore engine
W/jxcore-log( 3363): JXcore engine is ready
W/jxcore-log( 3363): Starting JXcore engine
I/ActivityManager(  903): Resuming delayed broadcast
W/jxcore-log( 3363): Platform android
W/jxcore-log( 3363): 
W/jxcore-log( 3363): Process ARCH arm
W/jxcore-log( 3363): 
I/ActivityManager(  903): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=3431 uid=10031 gids={50031, 3003, 5012}
I/ActivityManager(  903): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
I/ActivityManager(  903): Resuming delayed broadcast
I/jxcore-log( 3363): JXcore Cordova bridge is ready!
I/jxcore-log( 3363): 
W/jxcore-log( 3363): JXcore engine is started
I/ActivityManager(  903): Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
I/ActivityManager(  903): Resuming delayed broadcast
I/[PluginManager]RegisterService( 1371): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.example.hello
I/[PluginManager]RegisterService( 1371): handle notify Blinkfeed plugin client changed
I/ActivityManager(  903): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  903): Resuming delayed broadcast
I/ActivityManager(  903): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=3447 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
E/jxcore-log( 3363): >> HTC-HTC Desire 820
E/jxcore-log( 3363): 
I/jxcore-log( 3363): Total memory 1964650496
I/jxcore-log( 3363): 
I/jxcore-log( 3363): Free memory 715165696
I/jxcore-log( 3363): 
I/jxcore-log( 3363): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3363): 
I/jxcore-log( 3363): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3363): 
I/jxcore-log( 3363): userPath [ 'www' ]
I/jxcore-log( 3363): 
I/jxcore-log( 3363): Size 720 1184
I/jxcore-log( 3363): 
I/jxcore-log( 3363): Screen Brightness 10
I/jxcore-log( 3363): 
E/jxcore-log( 3363): Dummy Error Log.
E/jxcore-log( 3363): 
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=3447, uid=10073, userID:0
D/Finsky  ( 3447): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  903): getAllNetworkInfo called by com.android.vending (3447/10073)
D/ConnectivityService(  903): getAllNetworkInfo called by com.android.vending (3447/10073)
D/Finsky  ( 3447): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
W/Settings( 3447): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 3447): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=3447, uid=10073, userID:0
D/Process (  903): killProcessQuiet, pid=3164
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/Prism.PackageStateRece_( 1244): action: android.intent.action.PACKAGE_ADDED
D/Finsky  ( 3447): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 3447): [1] 2.run: Finished loading 1 libraries.
I/ActivityManager(  903): Killing 3164:com.htc.calendar/u0a13 (adj 15): empty #17
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Recipient 3164
I/IcingCorporaProvider( 2671): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
I/ActivityManager(  903): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
D/Finsky  ( 3447): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager(  903): Delaying start of: ServiceRecord{4252bcd8 u0 com.android.vending/com.google.android.finsky.services.RestoreService}
W/asset   ( 2671): Copying FileAsset 0x5c7064d8 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/IcingCorporaProvider( 2671): UpdateCorporaTask done [took 39 ms] updated apps [took 39 ms] 
D/Finsky  ( 3447): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  903): Resuming delayed broadcast
I/ActivityManager(  903): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=3482 uid=10098 gids={50098, 3003, 5012}
D/Process (  903): killProcessQuiet, pid=2949
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 2949:com.android.settings:remote/1000 (adj 15): empty #17
I/ActivityManager(  903): Recipient 2949
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DeviceManagement( 3482): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=3482 dbg=false s=true
I/DeviceManagement( 3482): PackageUpdateReceiver: vvv Package added: [com.example.hello]
I/ActivityManager(  903): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=3495 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
D/Process (  903): killProcessQuiet, pid=3195
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Killing 3195:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Recipient 3195
,I/jxcore-log( 3363): getBuffer is called!!!!
I/jxcore-log( 3363): 
,W/GAV2    ( 3495): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  903): Start proc com.htc.backup for broadcast com.htc.backup/.task.restore.PackageInstallReceiver: pid=3515 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/htcbackup-core( 3515): ModelRegistry: Loading model meta data from resources...
,W/ContextImpl( 3515): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
W/ContextImpl( 3515): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 com.htc.cs.dm.config.ConfigManager.getConfig:322 
,I/DeviceManagement( 3482): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=44]
,I/DeviceManagement( 3482): ConfigManagerBoundService: Caller: uid=android.uid.system:1000 (1000) packages=[com.android.keychain, com.htc.cirmodule, com.htc.android.htcsetupwizard, com.htc.android.htcloglevel, com.htc.smartdim, com.htc.htcpowermanager, com.htc.lockscreen, com.htc.autobot.cargps.provider, com.qualcomm.timeservice, com.android.location.fused, com.android.CSDFunctionG, com.htc.home.personalize, com.htc.feedback, com.htc.mirrorlinkserver, com.htc.guide, com.android.settings, com.htc.drive.activator, com.htc.backup, com.qualcomm.privinit, com.htc.usage, android, com.android.providers.settings, com.android.inputdevices, com.htc.checkinprovider, com.htc.backupreset]
,I/DeviceManagement( 3482): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=44], appID=com.htc.backup}]]
,I/ActivityManager(  903): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=3532 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
,D/Process (  903): killProcessQuiet, pid=3224
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Killing 3224:com.htc.stock/u0a81 (adj 15): empty #17
,I/DeviceManagement( 3482): WorkflowService: Starting workflow service
I/DeviceManagement( 3482): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41ab8428] args=[Bundle[mParcelledData.dataSize=144]]
,I/DeviceManagement( 3482): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=144]
I/ActivityManager(  903): Recipient 3224
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DeviceManagement( 3482): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 3482): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 3482): SessionStateController: Checking invariants...
,D/HtcCupdReceiver(Provider)( 3532):  @@@@@ receive action=android.intent.action.PACKAGE_ADDED
I/ActivityManager(  903): Delay finish: com.htc.providers.settings/.HtcCupdReceiver
,I/DeviceManagement( 3482): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
,W/CpuWake (  903): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  903): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  903): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  903): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  903): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  903): <<release mCpuPerf_Freq wakelock
D/PMS     (  903): releaseHCC(427e4208): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  903): releaseHCC(42317220): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/DeviceManagement( 3482): SessionStateController: Checking invariants...
,I/ActivityManager(  903): Resuming delayed broadcast
,W/GAV2    ( 3495): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
D/Process (  903): killProcessQuiet, pid=3236
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=3547 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
I/ActivityManager(  903): Killing 3236:com.htc.stock:remote/u0a81 (adj 15): empty #17
I/DeviceManagement( 3482): ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true
I/DeviceManagement( 3482): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41ab8428]
I/DeviceManagement( 3482): WorkflowService: Stopping workflow service
,D/Process (  903): killProcessQuiet, pid=3139
I/ActivityManager(  903): Recipient 3236
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Killing 3139:com.htc.widget.hmsproc1/u0a38 (adj 15): empty #17
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  903): Recipient 3139
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/AlarmManager(  903): sending alarm PendingIntent{42328ac0: PendingIntentRecord{425a4768 com.android.vending startService}}, i=null, t=0, cnt=1, w=1448306461744, Int=0
,D/PMS     (  903): acquireWL(42532978): PARTIAL_WAKE_LOCK  AsyncService 0x1 3547 10160 null
,D/PMS     (  903): releaseWL(42532978): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  903): acquireWL(4238e690): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 3547 10160 null
,W/GLSUser ( 1337): GoogleAccountDataService.getToken()
,I/GoogleHttpClient( 1337): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1337): Using GMS GoogleHttpClient
,W/GLSActivity( 1337): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1337): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1337): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/PMS     (  903): acquireWL(4273f138): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 3547 10160 null
D/PMS     (  903): releaseWL(4238e690): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
,I/ActivityManager(  903): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=3577 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (3547/10160)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (3547/10160)
,D/Settings:HtcWirelessFeatureFlags( 3349): id/is att sku: 99/false
,W/SystemReader( 3349): Cannot find devicepolicy_lower_fp_quality, use default value instead
,W/SystemReader( 3349): Cannot find support_harman, use default value instead
,W/SystemReader( 3349): Cannot find effect_manager_id, use default value instead
W/ContextImpl( 3577): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  903): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
,D/PowerUsageService( 3577): call getInstance()
,W/GLSUser ( 1337): GoogleAccountDataService.getToken()
,E/Settings:HtcWrapHeaderInfo( 3349): no such activity!
,D/PowerUsageList:PowerUsageHelper( 3577): MY_DEBUG = false
,W/GLSActivity( 1337): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1337): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1337): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/BatSI   (  903): Couldn't get kernel wake lock stats
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3349): The wrap header doesn't exist in header list.
,W/Finsky  ( 3447): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3447): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,E/Settings:HtcWrapHeaderInfo( 3349): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 3349): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3349): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3349): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3349): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3349): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3349): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3349): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3349): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3349): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3349): [supportHomeButton]support         :false
,D/PMS     (  903): releaseWL(4273f138): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
,W/FingerprintManager( 3349): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
I/ActivityManager(  903): Resuming delayed broadcast
,E/Settings:HtcVoWifiWidgetEnabler( 3349): isSupportVoWifi: null
I/ActivityManager(  903): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3349): Failed to find provider info for com.htc.vowifi
,D/PMS     (  903): acquireWL(427d5330): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3577 1000 null
W/WeatherUtility( 1103): can't get weather sync account
,D/WeatherUtility( 1371): Weather sync is On
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,D/WSP     ( 1371): [Receiver] auto sync agent, auto sync is enabled, reset schedule
,W/WeatherUtility( 3180): can't get weather sync account
I/ActivityManager(  903): Delay finish: com.htc.widget.weatherclock/.util.WidgetReceiver
,W/WeatherRequest( 3180): request cur loc, but there is no sys cur
,W/Settings( 3180): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3349): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3349): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 3349): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3349): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3349): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3349): [supportRecentAppsButton]support         :false
,D/AppWidgetHostView( 1244): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1244): com.htc.widget.weatherclock (true,33751552)
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3349): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3349): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3349): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3349): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3349): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3349): [supportHomeButton]support         :false
,W/FingerprintManager( 3349): hasFingerprint() - sSensorCode = 0
,I/RemoteViews.Performance( 1244): com.htc.widget.weatherclock 1 8 17
,E/Settings:HtcVoWifiWidgetEnabler( 3349): isSupportVoWifi: null
I/ActivityManager(  903): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3349): Failed to find provider info for com.htc.vowifi
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,I/SocialFeedProvider( 1244): +disConnect socialManager
,I/SocialFeedProvider( 1244): disconnect socialManager
,I/SocialFeedProvider( 1244): -disConnect socialManager
,I/SensorManager(  903): mEventCount = 300
,V/AlarmManager(  903): sending alarm PendingIntent{422fff90: PendingIntentRecord{4247df00 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1448306462419, Int=0
,I/SocialManager[SocialBiLogHelper]( 3250): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 3250): last commit ulog time 1448257748911
,I/SocialManager[SocialBiLogHelper]( 3250): skip commit this time
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=3600 uid=10032 gids={50032, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
,W/GLSUser ( 1337): GoogleAccountDataService.getToken()
,W/GLSActivity( 1337): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1337): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1337): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 3447): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3447): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3447): [1] DailyHygiene.reschedule: Giving up. (failures=6)
,D/Process (  903): killProcessQuiet, pid=3152
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3152:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3152
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,D/PMS     (  903): releaseWL(427fba00): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,V/AlarmManager(  903): sending alarm PendingIntent{42570158: PendingIntentRecord{426fc538 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1448306463187, Int=0
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=3618 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/Process (  903): killProcessQuiet, pid=3280
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  903): Killing 3280:com.htc.mobiledata/u0a91 (adj 15): empty #17
D/Process (  903): killProcessQuiet, pid=3209
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3209:com.htc.task/u0a70 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3280
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Recipient 3209
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/MusicStore( 3618): Database version: 95
,W/ContextImpl( 3618): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 3618): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3618): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3618): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3618): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=3618, uid=10154, userID:0
,D/WifiDisplayAdapter(  903): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  903):     Client/Owner: Client
D/WifiDisplayAdapter(  903):     GroupId: 
D/WifiDisplayAdapter(  903):     Passphrase: 
D/WifiDisplayAdapter(  903):     SessionId: 0
D/WifiDisplayAdapter(  903):     IP Address: }
,D/MediaRouterService(  903): Client com.google.android.music (pid 3618): Registered
,D/WifiDisplayAdapter(  903): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  903):     Client/Owner: Client
D/WifiDisplayAdapter(  903):     GroupId: 
D/WifiDisplayAdapter(  903):     Passphrase: 
D/WifiDisplayAdapter(  903):     SessionId: 0
D/WifiDisplayAdapter(  903):     IP Address: }
I/MediaRouter( 3618): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/ActivityManager(  903): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=3637 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.music (3618/10154)
,D/MediaRouter( 3618): getSelectedRoute
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=3618, uid=10154, userID:0
,D/Process (  903): killProcessQuiet, pid=3264
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3264:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
,D/DFPI.PIReciver( 3637): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/ActivityManager(  903): Recipient 3264
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DFPI.ApkInstallService( 3637): onHandleIntent
I/DFPI.ApkInstallService( 3637): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3637): check CID = HTC__032
I/DFPI.ApkInstallService( 3637): There is no Demo.apk in sd card or phone storage
,I/HtcModeClient( 1476): handler message = 4011
,E/HtcModeClient( 1476): Check connection and retry 6 times.
I/ActivityManager(  903): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=3653 uid=10051 gids={50051, 1028, 1015, 3003, 5012}
,I/ActivityManager(  903): Delay finish: com.htc.musicenhancer/.provider.MScannerReceiver
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.musicenhancer (3653/10051)
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3653): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,D/PMS     (  903): releaseWL(427d5330): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/ActivityManager(  903): Waited long enough for: ServiceRecord{427bdba0 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=3671 uid=10080 gids={50080, 5001, 1028, 1015}
,I/SoundPicker( 3671): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3671): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3671): SoundPickerReceiver [onReceive] startService
,I/ActivityManager(  903): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3671): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3671): TurnFileToMediaUriService fromMediaScanned = true
,I/SoundPicker( 3671): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
,D/RingtoneManager( 3671): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,D/RingtoneManager( 3671): MODE_GSM access default DB
,I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
,W/SoundPicker( 3671): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
,D/RingtoneManager( 3671): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
,W/SoundPicker( 3671): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
,D/RingtoneManager( 3671): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
,I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
,W/SoundPicker( 3671): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
,D/RingtoneManager( 3671): getActualDefaultRingtoneUri(context, 2)
,I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
,W/SoundPicker( 3671): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
,D/RingtoneManager( 3671): getActualDefaultRingtoneUri(context, 4)
,I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,W/SoundPicker( 3671): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
,I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,W/SoundPicker( 3671): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86,
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7,
W/SoundPicker( 3671): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 3671): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3671): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3671): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3671): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3671): MODE_GSM access default DB
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
,I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3671): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3671): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
,I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3671): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3671): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
,I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
,I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112,
,I/SoundPicker( 3671): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3671): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
,I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3671): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,D/RingtoneManager( 3671): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
,I/SoundPicker( 3671): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
,I/SoundPicker( 3671): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
,I/SoundPicker( 3671): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
,I/SoundPicker( 3671): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
,I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3671): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/ActivityManager(  903): Resuming delayed broadcast
,D/Process (  903): killProcessQuiet, pid=3297
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  903): Killing 3297:com.google.android.talk/u0a111 (adj 15): empty #17
,D/DFPI.PIReciver( 3637): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3637): onHandleIntent
,I/DFPI.ApkInstallService( 3637): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3637): check CID = HTC__032
,I/DFPI.ApkInstallService( 3637): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  903): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  903): Resuming delayed broadcast
,I/SoundPicker( 3671): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3671): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3671): SoundPickerReceiver [onReceive] startService
,I/ActivityManager(  903): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3671): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3671): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3671): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3671): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3671): MODE_GSM access default DB
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3671): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3671): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3671): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3671): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3671): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3671): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3671): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 3671): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 3671): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 3671): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 3671): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 3671): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3671): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3671): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3671): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3671): MODE_GSM access default DB
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3671): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3671): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/inte,rnal/audio/media/112 type=2
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3671): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3671): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3671): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3671): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/SoundPicker( 3671): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3671): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
I/SoundPicker( 3671): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
I/SoundPicker( 3671): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
I/SoundPicker( 3671): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
I/ActivityManager(  903): Recipient 3297
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/SoundPicker( 3671): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/SoundPicker( 3671): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  903): Resuming delayed broadcast
I/ActivityManager(  903): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
D/DFPI.PIReciver( 3637): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/ActivityManager(  903): Resuming delayed broadcast
I/ActivityManager(  903): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/DFPI.ApkInstallService( 3637): onHandleIntent
I/DFPI.ApkInstallService( 3637): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3637): check CID = HTC__032
I/DFPI.ApkInstallService( 3637): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  903): Resuming delayed broadcast
I/SoundPicker( 3671): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3671): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3671): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3671): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3671): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3671): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3671): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3671): MODE_GSM access default DB
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3671): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
,D/RingtoneManager( 3671): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3671): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3671): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3671): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3671): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3671): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 3671): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 3671): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 3671): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 3671): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 3671): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3671): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3671): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3671): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3671): MODE_GSM access default DB
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
,I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/ActivityManager(  903): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3671): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3671): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3671): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3671): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3671): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3671): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/SoundPicker( 3671): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3671): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
I/SoundPicker( 3671): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
I/SoundPicker( 3671): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.fla,c
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
I/SoundPicker( 3671): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
I/SoundPicker( 3671): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/SoundPicker( 3671): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac,
I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/MediaStoreImporter( 3618): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/ActivityManager(  903): Resuming delayed broadcast
D/TelephonyReceiver( 1216): bind: true
,D/GenericMessagesProvider( 2552): query uri: content://htc-messages/wappush/count
E/SQLiteLog( 2552): (14) cannot open file at line 30190 of [00bb9c9ce4]
E/SQLiteLog( 2552): (14) os_unix.c:30190: (2) open(/data/data/com.htc.sense.mms/databases/wappush.db) - 
E/SQLiteConnection( 2552): DB info: sqlite3_open_v2, path: /data/data/com.htc.sense.mms/databases/wappush.db, flag: 1, ret: 14
,E/SQLiteConnection( 2552): DB info: errno = 2, errno message = No such file or directory
,E/SQLiteDatabase( 2552): Failed to open database '/data/data/com.htc.sense.mms/databases/wappush.db'.
E/SQLiteDatabase( 2552): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 2552): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2552): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2552): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2552): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2552): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2552): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2552): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2552): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2552): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2552): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
E/SQLiteDatabase( 2552): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
E/SQLiteDatabase( 2552): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 2552): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 2552): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
E/SQLiteDatabase( 2552): 	at android.os.Binder.execTransact(Binder.java:412)
E/SQLiteDatabase( 2552): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 2552): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
W/System.err( 2552): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 2552): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/System.err( 2552): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
,W/System.err( 2552): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/System.err( 2552): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/System.err( 2552): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/System.err( 2552): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/System.err( 2552): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/System.err( 2552): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/System.err( 2552): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
W/System.err( 2552): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
W/System.err( 2552): 	at android.content.ContentProvider.query(ContentProvider.java:869)
W/System.err( 2552): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
W/System.err( 2552): ,	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
W/System.err( 2552): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err( 2552): 	at dalvik.system.NativeStart.run(Native Method)
,D/TelephonyReceiver( 1216): switchBindHtcMsgCursor: null
,I/ActivityManager(  903): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=3693 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
,I/ActivityManager(  903): Delay finish: com.htc.task/.TodoTaskReceiver
,I/ActivityManager(  903): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=3706 uid=10063 gids={50063, 3003, 5012, 1023, 1028, 1015}
,I/ActivityManager(  903): Resuming delayed broadcast
,D/DFPI.PIReciver( 3637): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3637): onHandleIntent
I/DFPI.ApkInstallService( 3637): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3637): check CID = HTC__032
,I/DFPI.ApkInstallService( 3637): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  903): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,D/Process (  903): killProcessQuiet, pid=3330
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Resuming delayed broadcast
I/ActivityManager(  903): Killing 3330:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3330
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/SoundPicker( 3671): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,D/WifiService(  903): Client connection lost with reason: 4
W/ContextImpl( 3671): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3671): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3671): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3671): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3671): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3671): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,D/RingtoneManager( 3671): MODE_GSM access default DB
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3671): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3671): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3671): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3671): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3671): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3671): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3671): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 3671): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 3671): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 3671): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 3671): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 3671): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3671): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3671): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3671): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3671): MODE_GSM access default DB
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
,I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/ActivityManager(  903): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3671): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3671): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3671): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3671): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
,I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3671): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3671): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/EASAppSvc( 3706): [ NA ]- onCreate()
,I/SoundPicker( 3671): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/EASAppSvc( 3706): [ NA ]> onUpgrade: version = 63
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3671): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
,I/SoundPicker( 3671): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
,I/SoundPicker( 3671): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
D/ORMLib  ( 3693): put()
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
,I/SoundPicker( 3671): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
,I/SoundPicker( 3671): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3671): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
,I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,D/WifiService(  903): New client listening to asynchronous messages
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.htc.android.mail (3706/10063)
,I/SoundPicker( 3671): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3671): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/ConnectivityService(  903): getNetworkInfo networkType=0 called by com.htc.android.mail (3706/10063)
D/ConnectivityService(  903): getNetworkInfo networkType=55 called by com.htc.android.mail (3706/10063)
I/ActivityManager(  903): Resuming delayed broadcast
,I/EASAppSvc( 3706): [ NA ]- onDestroy()
,I/EASAppSvc( 3706): [ NA ]> uninitEASService
,I/EASRequestController( 3706): [ NA ]release
,I/EASAppSvc( 3706): [ NA ]< uninitEASService
,I/EASAppSvc( 3706): [ NA ]- onCreate()
,I/EASAppSvc( 3706): [ NA ]> onUpgrade: version = 63
I/ActivityManager(  903): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.htc.android.mail (3706/10063)
D/ConnectivityService(  903): getNetworkInfo networkType=0 called by com.htc.android.mail (3706/10063)
D/ConnectivityService(  903): getNetworkInfo networkType=55 called by com.htc.android.mail (3706/10063)
,D/ORMLib  ( 3693): put()
,I/MediaStoreImporter( 3618): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  903): Resuming delayed broadcast
,D/Process (  903): killProcessQuiet, pid=3431
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/EASAppSvc( 3706): [ NA ]- onDestroy()
,I/EASAppSvc( 3706): [ NA ]> uninitEASService
D/PMS     (  903): acquireWL(424ee108): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 1476 10014 null
I/ActivityManager(  903): Killing 3431:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Recipient 3431
,I/ActivityManager(  903): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=3739 uid=10067 gids={50067, 3003, 5012}
,I/EASRequestController( 3706): [ NA ]release
,I/EASAppSvc( 3706): [ NA ]< uninitEASService
I/ActivityManager(  903): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,D/PMS     (  903): releaseWL(424ee108): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=3758 uid=10084 gids={50084, 3003, 5012, 1028, 1015, 1023, 2001, 5006, 5001}
,D/Process (  903): killProcessQuiet, pid=3495
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3495:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,D/Process (  903): killProcessQuiet, pid=3515
,I/ActivityManager(  903): Killing 3515:com.htc.backup/1000 (adj 15): empty #17
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/TelephonyReceiver( 1216): bind: false
D/TelephonyReceiver( 1216): switchBindHtcMsgCursor: null
,I/ActivityManager(  903): Recipient 3495,
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Recipient 3515
,D/ORMLib  ( 3693): put()
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Start proc com.google.android.gm for broadcast com.google.android.gm/.MailIntentReceiver: pid=3773 uid=10107 gids={50107, 3003, 5012, 1028, 1015}
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,W/GAV2    ( 3773): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  903): Delay finish: com.google.android.gm/.MailIntentReceiver
,D/PMS     (  903): acquireWL(422032f8): PARTIAL_WAKE_LOCK  Icing 0x1 1194 10028 null
,D/PMS     (  903): releaseWL(422032f8): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/BluetoothManagerService(  903): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  903): disable(): mBluetooth = null mBinding = false
W/HtcDLNAServiceManager(  903): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  903): Settings:Agentname: bluetooth_on
W/HtcDLNAServiceManager(  903): Settings:Agentvalue: 0
W/Settings:Agent(  903): >> traceCallingStack()
W/Settings:Agent(  903): Process.myPid(): 903
W/Settings:Agent(  903): Process.myTid(): 1450
W/Settings:Agent(  903): Process.myUid(): 1000
W/Settings:Agent(  903): 
W/Settings:Agent(  903): 
W/System.err(  903): java.lang.Throwable: stack dump
W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  903): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  903): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  903): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  903): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  903): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  903): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
W/System.err(  903): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:583)
W/System.err(  903): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  903): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  903): 
W/Settings:Agent(  903): << traceCallingStack(): 6(ms)
D/BluetoothManagerService(  903): Message: MESSAGE_DISABLE
,D/WifiManager( 3363): setWifiEnabled: Base Package Name=com.example.hello, uid=10355
W/HtcDLNAServiceManager(  903): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  903): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  903): Settings:Agentvalue: 0
W/Settings:Agent(  903): >> traceCallingStack()
W/Settings:Agent(  903): Process.myPid(): 903
W/Settings:Agent(  903): Process.myTid(): 1318
W/Settings:Agent(  903): Process.myUid(): 1000
W/Settings:Agent(  903): 
W/Settings:Agent(  903): 
W/System.err(  903): java.lang.Throwable: stack dump
W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  903): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  903): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  903): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  903): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  903): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
,W/System.err(  903): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  903): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:114)
,W/System.err(  903): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
D/PMS     (  903): acquireWL(42580348): PARTIAL_WAKE_LOCK  Icing 0x1 1194 10028 null
D/WifiService(  903): New client listening to asynchronous messages
D/WifiService(  903): setWifiEnabled: false pid=3363, uid=10355
E/WifiService(  903): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  903): isSprintWifiRestricted(): false
I/WifiService(  903): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  903): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/System.err(  903): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  903): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  903): 
W/Settings:Agent(  903): << traceCallingStack(): 3(ms)
I/jxcore-log( 3363): ****TEST TOOK:  5047  ms ****
I/jxcore-log( 3363): 
I/jxcore-log( 3363): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3363): 
,D/NotificationService(  903): notification sound not played, stream=5 volume=0 always=false
D/DotMatrix( 1528): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false
,I/RemoteViews( 1103): com.htc.updater (true,33751552)
D/PMS     (  903): releaseWL(42580348): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/OnDemandProgressBar( 1103): release indeterminate drawable android.widget.OnDemandProgressBar{41d5a810 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1103): com.htc.updater 1 8 0 10
,I/ActivityManager(  903): Resuming delayed broadcast
I/RemoteViews( 1103): com.htc.updater (true,33751552)
,D/OnDemandProgressBar( 1103): release indeterminate drawable android.widget.OnDemandProgressBar{41e1ca48 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1103): com.htc.updater 1 7 0 10
I/ActivityManager(  903): Delay finish: com.google.android.gm/.GmailReceiver
,I/Gmail   ( 3773): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 3773): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 3773): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 3773): calculateUnknownSyncRationalesAndPurgeInBackground: running
W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Delay finish: com.google.android.gm/.GmailReceiver
,I/NotifUtils( 3773): Validating Notification, mapSize: 0 getAttention: true ignoreUnobtrusive: false
,I/NotifUtils( 3773): validateNotifications - cancelling account 61035162 / folder -317575340
I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver: pid=3818 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,D/Process (  903): killProcessQuiet, pid=3482
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3482:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3482
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Babel   ( 3818): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 3818): MmsConfig.loadMmsSettings
,D/AutoSetting( 1371): service - mRequestRunnable: screen on delay 10s, request NLP now
D/AutoSetting( 1371): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1371): service - requestNLP() NetworkLocationProvider not enabled
,E/dalvikvm( 3818): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
,E/ProviderInstaller( 3818): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
E/dalvikvm( 3818): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
,E/ProviderInstaller( 3818): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
,V/JNIHelp ( 3818): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
,E/cutils-trace( 3804): Error opening trace file: No such file or directory (2)
,D/MmsCustomizationProvider( 2552): query uri: content://htc-mms-customization/mms-ua/ua_string
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=3818, uid=10111, userID:0
,W/Settings( 3818): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MmsCustomizationProvider( 2552): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/Babel   ( 3818): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 3818): MmsConfig.loadFromDatabase
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=3818, uid=10111, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=3818, uid=10111, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=3818, uid=10111, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=3818, uid=10111, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=3818, uid=10111, userID:0
,D/PMS     (  903): acquireWL(427ac140): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 3818 10111 null
E/Babel   ( 3818): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 3818): MmsConfig.loadFromResources
E/Babel   ( 3818): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 3818): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/ActivityManager(  903): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,I/ProviderInstaller( 3818): Installed default security provider GmsCore_OpenSSL
,D/PMS     (  903): releaseWL(427ac140): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  903): Resuming delayed broadcast
,D/PMS     (  903): acquireWL(4252c5b8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 3818 10111 null
,I/ActivityManager(  903): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,D/CustomizationManager( 3804): ====startRecUseTime====
D/htc.customization.log.level( 3804):  is 
,W/CustomizationLogLevel( 3804): Level value is invalid, use default level 2
,D/PMS     (  903): releaseWL(4252c5b8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  903): Resuming delayed broadcast
,D/PMS     (  903): acquireWL(42586b40): PARTIAL_WAKE_LOCK  NetworkStats 0x1 903 1000 null
,D/Process (  903): killProcessQuiet, pid=3532
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3532:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/PMS     (  903): releaseWL(42586b40): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
I/ActivityManager(  903): Recipient 3532
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  903): acquireWL(4284c910): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 3818 10111 null
I/ActivityManager(  903): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,D/CustomizationManager( 3804):  Read ACC file spent 0.059 (s)
,D/CIDMapFileReader( 3804): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3804): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3804): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3804): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3804): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3804): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3804): Parsing tag item name = HTC__016
,D/CIDMapFileReader( 3804): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3804): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 3804): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 3804): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 3804): Parsing tag category name = system
,I/CustomizationCIDLoader( 3804): Parsing tag category name = application
I/CustomizationCIDLoader( 3804): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3804): Parsing tag category name = AutomotiveHome,
I/CustomizationCIDLoader( 3804): Parsing tag category name = AudioService
,I/CustomizationCIDLoader( 3804): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3804): Parsing tag category name = Settings
D/CustomizationManager( 3804):  Read CID file spent 0.103 (s)
,D/CustomizationManager( 3804):  All configurations done spent 0.103 (s),
W/HtcNativeFlag( 3804): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3804): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3804): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 3804): Fail to get flag for type 'language', use default value: -1,
,D/PackageManager(  903): deletePackageAsUser: pkg=com.example.hello, pid=3804, uid=2000 user=0
,I/ActivityManager(  903): Force stopping com.example.hello appid=10355 user=-1: uninstall pkg
,D/Process (  903): killProcessQuiet, pid=3363
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  903): Killing 3363:com.example.hello/u0a355 (adj 0): stop com.example.hello
,W/asset   (  903): Copying FileAsset 0x6d837518 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
W/ActivityManager(  903): Force removing ActivityRecord{4274c260 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/ActivityManager(  903): handleTopAppChanged(): The previous AP is died unexpectedly.
,W/PackageSettings(  903): Skipping PackageSetting{42214a50 com.test.thalitest/10348} due to missing metadata
,I/ActivityManager(  903): Force stopping com.example.hello appid=10355 user=0: pkg removed
,D/PMS     (  903): releaseWL(4284c910): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,W/InputDispatcher(  903): channel '428362b0 com.example.hello.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  903): channel '428362b0 com.example.hello.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.talk (3818/10111)
,I/WindowState(  903): WIN DEATH: Window{428362b0 u0 com.example.hello/com.example.hello.MainActivity}
,W/InputDispatcher(  903): Attempted to unregister already unregistered input channel '428362b0 com.example.hello.MainActivity (s)'
D/WifiService(  903): Client connection lost with reason: 4
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/WindowManager(  903): WINDOW DIED Window{428362b0 u0 com.example.hello/com.example.hello.MainActivity}
I/HtcKeyguardAppUpdateMonitor( 1103): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1103): ApplicationsIntentReceiver packageName:com.example.hello
I/HtcKeyguardAppUpdateMonitor( 1103): ApplicationsIntentReceiver replacing:false
,D/DotMatrix( 1528): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
,W/GeofencerStateMachine( 1414): Ignoring removeGeofence because network location is disabled.
D/DotMatrix( 1528): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1528): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
I/acms    ( 1764): Unregistering com.example.hello
,E/acms    ( 1764): Could not unregister removed application com.example.hello
W/AccTypeManager( 1299): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1299): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  903): acquireWL(427d52e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1414 10028 null
,D/PMS     (  903): releaseWL(427d52e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/Prism.ItemManager( 3250): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 3250): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/FeedHostManager( 1244): [onResume]
I/FeedProviderManager( 1244): onResume
I/SocialFeedProvider( 1244): +onResume
I/SocialFeedProvider( 1244): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1244): -onResume
,I/ConnectivityHelper( 1244): [getCurrentConnectionType] no network connection
,D/AccTypeManager( 1299): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.launcher (1244/10075)
,W/SystemReader( 1227): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "sms"
I/Prism.ItemManager( 1244): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1244): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,E/ExternalAccountType( 1299): Unsupported attribute readOnly
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "smsto"
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.talk (3818/10111)
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "mms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "mmsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "sms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "smsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,I/InputMethodManagerService(  903): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "mms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "mmsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,W/InputMethodManagerService(  903): Got RemoteException sending setActive(false) notification to pid 3363 uid 10355
,W/Binder  ( 1180): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1180): java.lang.NullPointerException
W/Binder  ( 1180): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1180): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1180): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1180): 	at dalvik.system.NativeStart.run(Native Method)
,D/PhoneApp( 1216): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/InputMethodManagerService(  903): Enable input method client, pid=1244
,W/PackageManager(  903): Unable to load service info ResolveInfo{4257d910 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  903): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  903): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  903): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  903): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  903): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  903): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  903): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  903): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  903): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  903): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  903): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  903): 	at dalvik.system.NativeStart.main(Native Method)
,D/RemoteDisplayProvider(  903): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  903): start
,W/AtomicFile(  903): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  903): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,D/PMS     (  903): acquireWL(42728800): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42728800): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1103): closing low battery warning: level=98
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1103): status:2 level:98 unsupport:false plugged:true
,V/AlarmManager(  903): sending alarm PendingIntent{424fe218: PendingIntentRecord{42555808 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1448306467473, Int=0
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.talk (3818/10111)
,E/SQLiteLog( 3818): (3850) statement aborts at 32: [UPDATE messages SET server_target_retry=?,fail_count=?,server_fail_count=? WHERE _id=?] disk I/O error
,E/SQLiteDBG( 3818): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.talk/databases/message_store.db, handle = 0x644ee800
,W/dalvikvm( 3818): threadid=13: thread exiting with uncaught exception (group=0x41649e30)
,E/Babel   ( 3818): Uncaught exception in background thread Thread[default_queuethalitester@gmail.com,5,main]
,E/Babel   ( 3818): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/Babel   ( 3818): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/Babel   ( 3818): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/Babel   ( 3818): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/Babel   ( 3818): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/Babel   ( 3818): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1645)
E/Babel   ( 3818): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1591)
E/Babel   ( 3818): 	at com.google.android.apps.babel.realtimechat.dr.c(SourceFile:1898)
E/Babel   ( 3818): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:906)
E/Babel   ( 3818): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1094)
E/AndroidRuntime( 3818): FATAL EXCEPTION: default_queuethalitester@gmail.com
E/AndroidRuntime( 3818): Process: com.google.android.talk, PID: 3818
E/AndroidRuntime( 3818): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 3818): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 3818): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 3818): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 3818): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 3818): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1645)
E/AndroidRuntime( 3818): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1591)
E/AndroidRuntime( 3818): 	at com.google.android.apps.babel.realtimechat.dr.c(SourceFile:1898)
E/AndroidRuntime( 3818): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:906)
E/AndroidRuntime( 3818): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1094)
,E/ActivityManager(  903): App crashed! Process: com.google.android.talk
,E/DropBoxManagerService(  903): Can't write: system_app_crash
E/DropBoxManagerService(  903): java.io.FileNotFoundException: /data/system/dropbox/drop121.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  903): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  903): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  903): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  903): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  903): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  903): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  903): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  903): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  903): 	... 5 more
,D/HABCtrl (  903): ALG=2, lsvalue=10(0th)->40(1th), last_level=1, lValue=64->64

```
