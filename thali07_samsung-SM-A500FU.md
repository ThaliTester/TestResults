#### Test 506502784dae475_thali07_samsung-SM-A500FU Logs


```
--------- beginning of main
D/CscParser( 5020): getInstance fileName =/system/csc/customer.xml
D/Mms/MmsConfig( 5020):  enable multiwindow = true
D/TapandpayWidget:TapandpayAppWidgetProvider( 5155): Widget is not attached.
E/Mms/MessageUtils( 5020): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 5020): updateCountryIso : update country iso info 
D/Mms/MmsConfig( 5020): [end]    init() consume time = 131.422708
D/Mms/Contact( 5020): [start]    init() consume time = 0.745521
D/TP/MmsSmsProvider( 1440): query,matched:13, calling pid = 5020
D/TP/MmsSmsProvider( 1440): match 13:Elapsed time : 1.414 ms
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
--------- beginning of system
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
D/PackageBroadcastService( 1996): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
D/Mms/Contact( 5020): [end]    init consume time = 31.478541
D/ChimeraCfgMgr( 1996): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1996): Loading module APK com.google.android.play.games
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Mms/ArtClassLoader( 5020): init [DONE] art
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
D/Mms/DraftCache( 5020): [start]    rebuildCache consume time = 11.075938
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.config.ConfigFetchService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Mms/MethodReflector( 5020): getSubId is called
D/Mms/TelephonyUtils( 5020): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 5020): getTelephonyProperty is called
D/Mms/DownloadManager( 5020): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5020): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5020): auto download without roaming -> true
D/Mms/DownloadManager( 5020): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/MethodReflector( 5020): getSubId is called
D/Mms/MethodReflector( 5020): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 5020): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 5020): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 5020): getTelephonyProperty is called
D/Mms/DownloadManager( 5020): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 5020): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 5020): auto download without roaming -> true
D/Mms/DownloadManager( 5020): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 5020): auto download during roaming secondary -> false
D/Mms/DownloadManager( 5020): mAutoDownload ------> true
D/TP/MmsSmsProvider( 1440): query,matched:12, calling pid = 5020
D/TP/MmsSmsProvider( 1440): match 12:Elapsed time : 2.222 ms
,D/Mms/DraftCache( 5020): [end]    rebuildCache consume time = 25.47026
D/ComposerPerformance( 5020): 1449750986578 ms / [DONE] Composer constructor
E/CII     ( 5020): CommonIMSInterface: VoLTE CSC feature disabled.
I/Mms/ReservationManager( 5020): ReservationManager()
I/Mms/ReservationManager( 5020): resetAfterConnected()
D/TP/MmsSmsProvider( 1440): query,matched:7, calling pid = 5020
D/TP/MmsSmsProvider( 1440): match 7:Elapsed time : 2.026 ms
I/Mms/ReservationManager( 5020): getReservedSendMessageCount(): retMessageCount=0
D/Mms/Conversation( 5020): [start]    init() consume time = 16.561094
D/Mms/MmsApp( 5020): [end]    onCreate() consume time = 0.345261
D/TP/MmsSmsProvider( 1440): deleteConversation threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1440): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1440): updateThread(), thread_id = 9223372036854775807
V/TP/MmsSmsDatabaseHelper( 1440): sUpgradeVersion = 0, db.getVersion() = 81
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TP/MmsSmsProvider( 1440): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1440): need read changed broadcast:false
D/Mms/Conversation( 5020): [end]    init consume time = 12.236093
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
D/Mms/MessagingNotification( 5020): [start]    init() consume time = 1.110886
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Mms/DownloadManager( 5020): Service state changed: Bundle[mParcelledData.dataSize=744]
D/Mms/DownloadManager( 5020): roaming ------> false, mSimSlot = 0
D/Mms/MethodReflector( 5020): getSubId is called
D/Mms/TelephonyUtils( 5020): getLongSubId from simSlot 0, return Value = -1
D/Mms/MessagingNotification( 5020): [end]    init consume time = 8.620208
D/Mms/MethodReflector( 5020): getTelephonyProperty is called
D/Mms/DownloadManager( 5020): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5020): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5020): auto download without roaming -> true
D/Mms/DownloadManager( 5020): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 5020): mAutoDownload ------> true
D/Mms/Synchronizer( 5020): [start]    doSync consume time = 2.376146
D/TP/MmsSmsProvider( 1440): query,matched:0, calling pid = 5020
V/TP/MmsSmsProvider( 1440): getSimpleConversations entered.
D/Mms/SpamFilter( 5020): [start]    SpamFilter fill() begin consume time = 1.388437
D/Mms/FreeMessageStatusReceiver( 5020): onReceive, action : android.intent.action.PACKAGE_ADDED
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
D/TP/MmsSmsProvider( 1440): update, matched:300, calling pid = 5020
V/TP/MmsSmsProvider( 1440): syncDBData start
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
V/TP/MmsSmsProvider( 1440): syncDBData sms end
V/TP/MmsSmsProvider( 1440): syncDBData mms end
V/TP/MmsSmsProvider( 1440): syncDBData end
D/TP/MmsSmsProvider( 1440): match 0:Elapsed time : 6.561 ms
D/Mms/Synchronizer( 5020): [end]    doSync consume time = 7.176615
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/TP/MmsSmsProvider( 1440): query,matched:400, calling pid = 5020
E/Zygote  ( 5196): MountEmulatedStorage()
E/Zygote  ( 5196): v2
I/libpersona( 5196): KNOX_SDCARD checking this for 10047
I/SELinux ( 5196): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/libpersona( 5196): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5196 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
I/SELinux ( 5196): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5196): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
D/Mms/FreeMessageReceiverService( 5020): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 5020): onHandleIntent: ACTION_PACKAGE_ADDED
I/ActivityManager( 1016): Killing 4444:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
D/TimaKeyStoreProvider( 5196): TimaSignature is unavailable
D/ActivityThread( 5196): Added TimaKeyStore provider
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 5196): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5196): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
I/ActivityManager( 1016): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5212 uid=10072 gids={50072, 9997} abi=armeabi-v7a
W/ResourcesManager( 5196): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/Mms/SpamFilter( 5020): [end]    SpamFilter fill() finished consume time = 87.159635
E/Zygote  ( 5212): MountEmulatedStorage()
I/libpersona( 5212): KNOX_SDCARD checking this for 10072
E/Zygote  ( 5212): v2
I/libpersona( 5212): KNOX_SDCARD not a persona
I/SELinux ( 5212): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 5212): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5212): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5212): TimaSignature is unavailable
D/ActivityThread( 5212): Added TimaKeyStore provider
I/ActivityManager( 1016): Killing 4242:com.samsung.android.app.mirrorlink/1000 (adj 15): empty #31
I/art     (  305): Explicit concurrent mark sweep GC freed 8761(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 637us total 41.996ms
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 746us total 19.392ms
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 617us total 16.550ms
D/AndroidRuntime( 5193): 
D/AndroidRuntime( 5193): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5193): CheckJNI is OFF
D/AndroidRuntime( 5193): readGMSProperty: start
D/AndroidRuntime( 5193): readGMSProperty: already setted!!
D/AndroidRuntime( 5193): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5193): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5193): readGMSProperty: end
D/AndroidRuntime( 5193): addProductProperty: start
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_4444/cgroup.procs: No such file or directory
W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_4242/cgroup.procs: No such file or directory
D/BadgeProvider( 5212): onCreate
D/BadgeProvider( 5212): DatabaseHelper
D/MyFiles ( 5196): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
I/ActivityManager( 1016): Killing 3489:com.android.providers.calendar/u0a42 (adj 15): empty #31
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
D/Mms/MessagingNotification( 5020): checkBadgeCount unreadCount=0 badgeCount=0
E/installd(  284): system dir 0 : /system/app/
E/installd(  284): system dir 1 : /system/priv-app/
E/installd(  284): system dir 2 : /vendor/app/
E/installd(  284): system dir 3 : /oem/app/
I/TactileAssist( 1016): enable value -1
I/TactileAssist( 1016): internal enable value -1
I/TactileAssist( 1016): intensity value -1
I/TactileAssist( 1016): saveAppList value true
D/TP/SmsProvider( 1440): query,matched:26, calling pid = 5020
D/TP/SmsProvider( 1440): match 26:Elapsed time : 2.727 ms
I/TactileAssist( 1016): List of disabled apps :
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5238): MountEmulatedStorage()
E/Zygote  ( 5238): v2
I/libpersona( 5238): KNOX_SDCARD checking this for 10053
I/libpersona( 5238): KNOX_SDCARD not a persona
I/SELinux ( 5238): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1016): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=5238 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a
I/SELinux ( 5238): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5238): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/TP/MmsSmsProvider( 1440): query,matched:6, calling pid = 5020
D/TP/MmsSmsProvider( 1440): match 6:Elapsed time : 1.127 ms
W/libprocessgroup( 1016): failed to open /acct/uid_10042/pid_3489/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 5238): TimaSignature is unavailable
D/ActivityThread( 5238): Added TimaKeyStore provider
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/PackageManager( 1016): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
I/ActivityManager( 1016): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5257 uid=10025 gids={50025, 9997} abi=armeabi-v7a
E/Zygote  ( 5257): MountEmulatedStorage()
E/Zygote  ( 5257): v2
I/libpersona( 5257): KNOX_SDCARD checking this for 10025
I/libpersona( 5257): KNOX_SDCARD not a persona
I/SELinux ( 5257): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SL_DEBUG( 5139): isLoggable:: isProductShip = 1
I/SL_DEBUG( 5139): isLoggable:: SL_DEBUG_EXIST = false
I/SELinux ( 5257): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5257): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ResourcesManager( 5238): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider( 5257): TimaSignature is unavailable
D/ActivityThread( 5257): Added TimaKeyStore provider
W/ResourcesManager( 5257): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ConfigFetchService( 1996): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1996): launchTask
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ChimeraCfgMgr( 1996): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1996): Module APK com.google.android.play.games already loaded
D/Compatibility( 5238): onReceive() it will make start service
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5139): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/ChimeraCfgMgr( 1996): Loading module com.google.android.gms.vision from APK com.google.android.gms
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/Vision  ( 1996): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1996): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1996): No vision deps
V/ConfigFetchTask( 1996): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1XthS64CiQjYy6hQB7nj3mphv59HZNQhVEMJJjEXvjeEJ-0vghaIXNVJGGU917qOXpLXpJufG9HqqAUJDWfWySzOOeGnGFjWjmz9jAce_1L21WAgU9_sXUOx5nYGK8T_DKW5Pa4PMcJXECh-DLOcoGljfx5_2L_r80mbie96IuDgZxohgax2aqR8TxQUYrusDCxbOfmDt3xyCLWWiXDiwMZugNHEP-NBWT0xVlfo22zyngyZRI
E/Zygote  ( 5282): MountEmulatedStorage()
I/libpersona( 5282): KNOX_SDCARD checking this for 1000
E/Zygote  ( 5282): v2
I/libpersona( 5282): KNOX_SDCARD not a persona
D/Compatibility( 5238): onHandleIntent()
I/ActivityManager( 1016): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=5282 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/Compatibility( 5238): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10175, android.intent.extra.user_handle=0}]
D/Compatibility( 5238): found: 2
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/GoogleURLConnFactory( 1996): Using platform SSLCertificateSocketFactory
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
D/Compatibility( 5238): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5238): skipping ResolveInfo{2d69a98b com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5238): considering ResolveInfo{3427ba68 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5238): default: com.sec.android.app.soundalive.SAControlPanelActivity
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Compatibility( 5238): enabling receiver ResolveInfo{24263e81 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
I/PeopleContactsSync( 1996): CP2 sync disabled
D/Compatibility( 5238): enabling receiver ResolveInfo{241a1b26 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 5238): enabling receiver ResolveInfo{38c75367 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 5238): enabling receiver ResolveInfo{10f21514 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
I/GAv4    ( 5034): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5034):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5034):   adb logcat -s GAv4
D/Compatibility( 5238): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
I/ActivityManager( 1016): Killing 4708:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
W/GAv4    ( 5034): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 5034): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
I/SELinux ( 5282): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 5282): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
W/GAv4    ( 5034): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/SELinux ( 5282): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/AnalyticsTrackerProxyImpl( 5034): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
I/OMACP   ( 5257): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
D/TimaKeyStoreProvider( 5282): TimaSignature is unavailable
D/ActivityThread( 5282): Added TimaKeyStore provider
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
W/libprocessgroup( 1016): failed to open /acct/uid_10069/pid_4708/cgroup.procs: No such file or directory
D/Mms/Omacp( 5020): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
I/System.out( 1996): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1996): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1996): (HTTPLog)-Static: isShipBuild true
I/System.out( 1996): (HTTPLog)-Thread-249-458095978: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1996): (HTTPLog)-Static: isSBSettingEnabled false
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5139): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 10012
W/ConfigFetchTask( 1996): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/OMACP   ( 5257): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
I/ConfigFetchService( 1996): fetch service done; releasing wakelock
I/OMACP   ( 5257): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
I/ConfigFetchService( 1996): stopping self
I/OMACP   ( 5257): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
I/OMACP   ( 5257): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
I/OMACP   ( 5257): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
I/OMACP   ( 5257): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
I/OMACP   ( 5257): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
W/ContextImpl( 5282): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:3125 
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
I/OMACP   ( 5257): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
I/OMACP   ( 5257): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
I/OMACP   ( 5257): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
I/OMACP   ( 5257): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
I/OMACP   ( 5257): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
I/OMACP   ( 5257): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5305): MountEmulatedStorage()
I/libpersona( 5305): KNOX_SDCARD checking this for 1000
E/Zygote  ( 5305): v2
I/libpersona( 5305): KNOX_SDCARD not a persona
I/SELinux ( 5305): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 5305): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5305): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=5305 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 4723:com.sec.knox.bridge/1000 (adj 15): empty #31
D/TimaKeyStoreProvider( 5305): TimaSignature is unavailable
D/ActivityThread( 5305): Added TimaKeyStore provider
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
W/BaseAppContext( 1996): Using Auth Proxy for data requests.
W/BaseAppContext( 1996): Using Auth Proxy for data requests.
W/ResourcesManager( 5305): Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_4723/cgroup.procs: No such file or directory
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5326): MountEmulatedStorage()
I/ActivityManager( 1016): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=5326 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 5326): v2
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/libpersona( 5326): KNOX_SDCARD checking this for 10041
I/libpersona( 5326): KNOX_SDCARD not a persona
I/SELinux ( 5326): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 5326): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/AffinityControl( 5193): AffinityControl: registerfunction enter
E/SELinux ( 5326): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5326): TimaSignature is unavailable
D/ActivityThread( 5326): Added TimaKeyStore provider
E/Zygote  ( 5336): MountEmulatedStorage()
E/Zygote  ( 5336): v2
I/libpersona( 5336): KNOX_SDCARD checking this for 1000
I/libpersona( 5336): KNOX_SDCARD not a persona
I/SELinux ( 5336): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 5336): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1016): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=5336 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 4739:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
E/SELinux ( 5336): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/AndroidRuntime( 5193): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1016): inState():  stateMachine is null !!
I/PersonaManagerService( 1016): PersonaId don't exist
I/ActivityManager( 1016): do not start freezing screen for locked container getKeyguardshowstate = false
D/TimaKeyStoreProvider( 5336): TimaSignature is unavailable
D/ActivityThread( 5336): Added TimaKeyStore provider
I/art     ( 1016): Explicit concurrent mark sweep GC freed 218375(14MB) AllocSpace objects, 3(4MB) LOS objects, 33% free, 26MB/40MB, paused 3.007ms total 178.657ms
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ResourcesManager( 5336): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ContextImpl( 5034): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.docs/cache
I/SA      ( 5326): [SSP] onCreated
W/ActivityManager( 1016): mDVFSHelper.acquire()
D/FocusedStackFrame( 1016): Set to : 0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1016): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1016): *FMB* installDecor flags : 25362712
W/ResourcesManager( 5034): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5034): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/Zygote  ( 5366): MountEmulatedStorage()
E/Zygote  ( 5366): v2
I/libpersona( 5366): KNOX_SDCARD checking this for 10175
I/libpersona( 5366): KNOX_SDCARD not a persona
I/SELinux ( 5366): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
I/ActivityManager( 1016): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5366 uid=10175 gids={50175, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1016): Focused application set to: xxxx
D/InputDispatcher( 1016): Focus left window: 1472
D/AndroidRuntime( 5193): Shutting down VM
I/SELinux ( 5366): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1016): Killing 4173:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
E/SELinux ( 5366): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Killing 4460:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
D/PhoneWindow( 1016): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1016): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  257): id=11 createSurf (1x1),1 flag=404, uhalitest
D/AcmsKeyStoreHelper( 5099):  getKeyStoreForApplication Enter
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
D/TimaKeyStoreProvider( 5366): TimaSignature is unavailable
D/ActivityThread( 5366): Added TimaKeyStore provider
V/WindowManager( 1016): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/ActivityManager( 1016): Display changed displayId=0
I/AcmsKeyStoreHelper( 5099): Key Store exist
I/AcmsKeyStoreHelper( 5099): Hence loading the keystore file
E/JavaBinder( 1016): !!! FAILED BINDER TRANSACTION !!!
D/StatusBarManagerService( 1016): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SA      ( 5326): [TPM] There is no property file
I/SA      ( 5326): [SCU] isHaveSA() - false
I/SA      ( 5326): [TPM] getModelProperty : null
I/SA      ( 5326): [TPM] getCSCProperty : null
I/SA      ( 5326): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 5326): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 5326): [DM] TFT FEATURE: false
I/SA      ( 5326): [PMR] Received action : android.intent.action.PACKAGE_ADDED
W/DisplayManagerService( 1016): Failed to notify process 4739 that displays changed, assuming it died.
W/DisplayManagerService( 1016): android.os.TransactionTooLargeException
W/DisplayManagerService( 1016): 	at android.os.BinderProxy.transactNative(Native Method)
W/DisplayManagerService( 1016): 	at android.os.BinderProxy.transact(Binder.java:511)
W/DisplayManagerService( 1016): 	at android.hardware.display.IDisplayManagerCallback$Stub$Proxy.onDisplayEvent(IDisplayManagerCallback.java:81)
W/DisplayManagerService( 1016): 	at com.android.server.display.DisplayManagerService$CallbackRecord.notifyDisplayEventAsync(DisplayManagerService.java:1372)
W/DisplayManagerService( 1016): 	at com.android.server.display.DisplayManagerService.deliverDisplayEvent(DisplayManagerService.java:1170)
W/DisplayManagerService( 1016): 	at com.android.server.display.DisplayManagerService.access$500(DisplayManagerService.java:146)
W/DisplayManagerService( 1016): 	at com.android.server.display.DisplayManagerService$DisplayManagerHandler.handleMessage(DisplayManagerService.java:1305)
W/DisplayManagerService( 1016): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DisplayManagerService( 1016): 	at android.os.Looper.loop(Looper.java:145)
W/DisplayManagerService( 1016): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/DisplayManagerService( 1016): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
D/PersonaManager( 1016): isKioskContainerExistOnDevice
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
D/WindowOrientationListener( 1016):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
V/JNIHelp ( 5034): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/SA      ( 5326): [DM] init START
I/SurfaceFlinger(  257): id=8 Removed Mauncher (5/9)
I/SurfaceFlinger(  257): id=8 Removed Mauncher (-2/9)
V/ActivityThread( 1472): updateVisibility : ActivityRecord{d08a82f token=android.os.BinderProxy@a933216 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1472): onTrimMemory. Level: 20
I/SA      ( 5326): [DM] This device is not a Vodafone
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_4739/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10150/pid_4460/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10057/pid_4173/cgroup.procs: No such file or directory
W/ResourceType( 5326): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 5326): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 5326): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 5326): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 5326): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 5326): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 5326): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
W/BaseAppContext( 1996): Using Auth Proxy for data requests.
W/ResourceType( 5326): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 5326): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 5326): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 5326): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 5326): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 5326): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 5326): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 5326): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 5326): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 5326): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
W/ResourceType( 5326): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 5326): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourceType( 5326): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 5326): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 5326): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 5326): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 5326): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 5326): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
I/SA      ( 5326): [SCU] isHaveSA() - false
I/SA      ( 5326): support phone number id : false
I/SA      ( 5326): [DM] Supports Ref Jpn : true
I/SA      ( 5326): [DM] init END
I/SA      ( 5326): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
I/SA      ( 5326): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10175 extra.user_handle.:0 ]
I/ActivityManager( 1016): Killing 3649:com.google.android.talk/u0a104 (adj 15): empty #31
W/BaseAppContext( 1996): Using Auth Proxy for data requests.
W/BaseAppContext( 1996): Using Auth Proxy for data requests.
W/ActivityThread( 5034): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5034): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@98295f7: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5034): Installed default security provider GmsCore_OpenSSL
D/AcmsKeyStoreHelper( 5099):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr( 5099): getKeyStoreForApplication success 
D/AcmsCore( 5099): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 5099): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5099): Decrementing - Counter value: 1
D/AcmsCore( 5099): AcmsCore: ACMS_APP_INSTALLED
W/art     ( 5193): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
D/AcmsCore( 5099): This is NOT a valid MirrorLink app
D/AcmsCore( 5099): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 5099): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5099): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 5099): Counter value is 0: Stopping ACMS service
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5388): MountEmulatedStorage()
E/Zygote  ( 5388): v2
I/libpersona( 5388): KNOX_SDCARD checking this for 10057
I/libpersona( 5388): KNOX_SDCARD not a persona
I/SELinux ( 5388): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1016): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5388 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
D/AcmsServiceMonitor( 5099): getSvcCounter - Counter value: 0
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
I/SELinux ( 5388): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
D/AcmsService( 5099): Enter onDestroy
I/AcmsService( 5099): cleanUp(): inside service clean up
D/AcmsCore( 5099): AcmsCore: inside DeInit
D/AcmsCore( 5099): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 5099): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 5099): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 5099): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 5099): AppEntryInterface: Inside CleanUp
E/SELinux ( 5388): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Killing 4082:com.google.android.gm/u0a101 (adj 15): empty #31
V/GLSActivity( 1725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/BaseAppContext( 1996): Using Auth Proxy for data requests.
D/AcmsServiceMonitor( 5099): getSvcCounter - Counter value: 0
D/AcmsService( 5099): killing acms process
I/Process ( 5099): Sending signal. PID: 5099 SIG: 9
D/TimaKeyStoreProvider( 5388): TimaSignature is unavailable
D/ActivityThread( 5388): Added TimaKeyStore provider
I/WebViewFactory( 5366): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 5366): Time to load native libraries: 2 ms (timestamps 5212-5214)
I/LibraryLoader( 5366): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5366): Binding Chromium to main looper Looper (main, tid 1) {38c75367}
I/LibraryLoader( 5366): Expected native library version number "",actual native library version number ""
I/chromium( 5366): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5366): Initializing chromium process, singleProcess=true
W/art     ( 5366): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5366): ApplicationContext is null in ApplicationStatus
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/chromium( 5366): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
W/chromium( 5366): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/libEGL  ( 5366): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5366): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5366): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5366): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5366): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5366): Local Branch: 
I/Adreno-EGL( 5366): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5366): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5366):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
E/Zygote  ( 5411): MountEmulatedStorage()
I/ActivityManager( 1016): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=5411 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/Zygote  ( 5411): v2
I/libpersona( 5411): KNOX_SDCARD checking this for 10010
I/libpersona( 5411): KNOX_SDCARD not a persona
I/SELinux ( 5411): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1016): Process ACMS.Process (pid 5099)(adj 0) has died(68,1109)
I/SELinux ( 5411): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5411): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
W/libprocessgroup( 1016): failed to open /acct/uid_10104/pid_3649/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10101/pid_4082/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 5411): TimaSignature is unavailable
D/ActivityThread( 5411): Added TimaKeyStore provider
D/BluetoothAdapter( 5366): 879476483: getState() :  mService = null. Returning STATE_OFF
D/LocationManagerService( 1016): getProviders()=[passive]
W/ActivityManager( 1016): Activity pause timeout for ActivityRecord{3e87d5d7 u0 com.test.thalitest/.MainActivity t228}
I/UpdateIcingCorporaServi( 5388): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/art     ( 5366): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 5366): onDetachedFromWindow called when already detached. Ignoring
D/PhoneWindow( 5366): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 5366): *FMB* installDecor flags : 8456448
D/SystemWebViewEngine( 5366): CordovaWebView is running on device made by: samsung
W/art     ( 5366): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5366): Attempt to remove local handle scope entry from IRT, ignoring
I/splitIntent( 1016): Queue : backgroundsplit_2 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
I/ActivityManager( 1016): Killing 4792:com.google.android.gms:car/u0a12 (adj 15): empty #31
I/UpdateIcingCorporaServi( 5388): UpdateCorporaTask done [took 132 ms] updated apps [took 132 ms] 
I/ActivityManager( 1016): Killing 4340:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
D/ChimeraCfgMgr( 1996): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1996): Module APK com.google.android.play.games already loaded
D/OpenGLRenderer( 5366): Render dirty regions requested: true
D/ActivityManager( 1016): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1016): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1016): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1016): handleActiveUserChange for user 0
D/PersonaManagerService( 1016): getPersonasForUser(): returning null!
W/chromium( 5366): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
V/ActivityThread( 5366): updateVisibility : ActivityRecord{2667c629 token=android.os.BinderProxy@15ca6ef3 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
D/PhoneWindow( 5366): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 5366): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  257): id=12 createSurf (1x1),1 flag=404, NainActivit
W/libprocessgroup( 1016): failed to open /acct/uid_10012/pid_4792/cgroup.procs: No such file or directory
D/InputDispatcher( 1016): Focus entered window: 5366
D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 5366): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 5366): Initialized EGL, version 1.4
D/OpenGLRenderer( 5366): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 5366): Enabling debug mode 0
D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4140, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/Mms/MmsApp( 5020):  start initViewCache mms
D/Mms/ComposeMessageFragment( 5020): [start]    fillCache consume time = 1880.893489
D/Mms/ComposeMessageFragment( 5020): fillCache, easy = false
V/EmergencyMode( 1405): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1405): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/InputMethodManagerService( 1016): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/SamsungIME( 1767): getCurrentCandidateView
D/PanelView( 1177): There is/are notification(s) 
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
I/ActivityManager( 1016): Displayed Component not be shown by security: +873ms (total +974ms)
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
I/Timeline( 1016): Timeline: Activity_windows_visible id: ActivityRecord{3e87d5d7 u0 com.test.thalitest/.MainActivity t228} time:75865
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
W/IInputConnectionWrapper( 5366): showStatusIcon on inactive InputConnection
W/ActivityManager( 1016): mDVFSHelper.release()
I/Timeline( 5366): Timeline: Activity_idle id: android.os.BinderProxy@15ca6ef3 time:75866
I/SurfaceFlinger(  257): id=11 Removed uhalitest (7/9)
I/SurfaceFlinger(  257): id=11 Removed uhalitest (-2/9)
D/AbsListView( 5020): Get MotionRecognitionManager
D/MotionRecognitionService( 1016):  ssp status : false
D/Mms/ComposeMessageFragment( 5020): [end]    fillCache consume time = 81.091719
D/SamsungIME( 1767): Dismiss ExpandCandiate
I/SamsungIME( 1767): getDebugLevel  : 0x4f4c
D/Mms/BubbleViewCache( 5020): fillCache bubble = 1
W/BindingManager( 5366): Cannot call determinedVisibility() - never saw a connection for the pid: 5366
I/SamsungIME( 1767): getDebugLevel  : 0x4f4c
I/SamsungIME( 1767): KeybaordView init() : load resources
I/SamsungIME( 1767): getCurrentKeyboard
I/SamsungIME( 1767): getTextKeyboard
D/SamsungIME( 1767): [SwiftkeyWrapper] currentLangauge : 1701729619
D/JsMessageQueue( 5366): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 5366): JniHelper::setJavaVM(0xb871e450), pthread_self() = -1194879304
,D/JX-Cordova( 5366): jxcore cordova android initializing
,E/SMD     (  288): DCD OFF
,W/jxcore-log( 5366): Initializing JXcore engine
W/jxcore-log( 5366): JXcore engine is ready
,W/jxcore-log( 5366): Starting JXcore engine
,E/audit   ( 1834): type=1400 msg=audit(1449750990.119:203): avc:  denied  { ioctl } for  pid=5366 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,E/audit   ( 1834):  SEPF_SM-A500FU_5.0.2_0027
E/audit   ( 1834): type=1300 msg=audit(1449750990.119:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=bec48d58 items=0 ppid=305 ppcomm=main pid=5366 auid=4294967295 uid=10175 gid=10175 euid=10175 suid=10175 fsuid=10175 egid=10175 sgid=10175 fsgid=10175 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1834): type=1320 msg=audit(1449750990.119:203): 
,W/jxcore-log( 5366): Platform android
W/jxcore-log( 5366): 
W/jxcore-log( 5366): Process ARCH arm
W/jxcore-log( 5366): 
,V/AlarmManager( 1016): waitForAlarm result :8
,E/Watchdog( 1016): !@Sync 2
,I/jxcore-log( 5366): JXcore Cordova bridge is ready!
I/jxcore-log( 5366): 
,W/jxcore-log( 5366): JXcore engine is started
,I/chromium( 5366): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 5366): Toggling radios to true
I/jxcore-log( 5366): 
,D/BluetoothAdapter( 5366): enable()
,W/ActivityManager( 1016): Permission Denial: getCurrentUser() from pid=5366, uid=10175 requires android.permission.INTERACT_ACROSS_USERS
,W/BluetoothManagerService( 1016): Failed getting userId using ActivityManagerNative
W/BluetoothManagerService( 1016): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5366, uid=10175 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService( 1016): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24603)
W/BluetoothManagerService( 1016): 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
W/BluetoothManagerService( 1016): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
W/BluetoothManagerService( 1016): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/BluetoothManagerService( 1016): 	at android.os.Binder.execTransact(Binder.java:461)
,E/DevicePolicyManagerService( 1016): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService( 1016): getAllowBluetoothMode - value retunrs : 2
,D/SettingsProvider( 1016): name = bluetooth_on
,E/DevicePolicyManagerService( 1016): getAllowBluetoothMode - value retunrs : 2
,E/DevicePolicyManagerService( 1016): getAllowBluetoothMode - value retunrs : 2
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/SecContentProvider( 1016): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1016): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2( 1016): mCursor = null
,E/Zygote  ( 5468): MountEmulatedStorage(),
I/libpersona( 5468): KNOX_SDCARD checking this for 1002,
E/Zygote  ( 5468): v2,
I/libpersona( 5468): KNOX_SDCARD not a persona
,W/WifiService( 1016): Failed getting userId using ActivityManagerNative
W/WifiService( 1016): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5366, uid=10175 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1016): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24603)
W/WifiService( 1016): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1016): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201),
W/WifiService( 1016): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1016): 	at android.os.Binder.execTransact(Binder.java:461)
D/WifiService( 1016): setWifiEnabled: true pid=5366, uid=10175
I/SELinux ( 5468): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
W/ActivityManager( 1016): Permission Denial: getCurrentUser() from pid=5366, uid=10175 requires android.permission.INTERACT_ACROSS_USERS
D/SettingsProvider( 1016): name = wifi_on
I/SELinux ( 5468): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
E/SELinux ( 5468): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/WifiHW  ( 1016): ##################### set firmware type 0 #####################
,I/WifiService( 1016): disconnect: pid=5366, uid=10175
,I/jxcore-log( 5366): Radios toggled
I/jxcore-log( 5366): 
,I/ActivityManager( 1016): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=5468 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,V/AlarmManager( 1016): waitForAlarm result :8,
,D/NtpTrustedTime( 1016): forceRefresh() from cache miss
,D/EnterpriseController(  278): uids 1000
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 1000
D/EnterpriseController(  278): uids 1000
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 1000
D/NtpTrustedTime( 1016): forceRefresh Fail.
,D/TimaKeyStoreProvider( 5468): TimaSignature is unavailable
,D/ActivityThread( 5468): Added TimaKeyStore provider
,W/ResourcesManager( 5468): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,W/ResourcesManager( 5468): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/ActivityManager( 1016): Killing 4262:com.google.android.music:main/u0a111 (adj 15): empty #31
,W/ProcessCpuTracker( 1016): Skipping unknown process pid 5489
,I/BluetoothA2dpSinkServiceJni( 5468): register_com_android_bluetooth_a2dp_sink
,D/BtSettings.ProfileConfig( 5468): Adding GattService
,D/BtSettings.ProfileConfig( 5468): Adding HeadsetService
,D/BtSettings.ProfileConfig( 5468): Adding A2dpService
,D/BtSettings.ProfileConfig( 5468): Adding HidService
,D/BtSettings.ProfileConfig( 5468): Adding HealthService
,D/BtSettings.ProfileConfig( 5468): Adding PanService
,D/BtSettings.ProfileConfig( 5468): Adding BluetoothMapService
,D/BtSettings.ProfileConfig( 5468): Adding SapService
,D/BtSettings.ProfileConfig( 5468): Adding HeadsetClientService
,D/BtSettings.ProfileConfig( 5468): Adding A2dpSinkService
,D/BtSettings.ProfileConfig( 5468): Adding SapClientService
D/BtSettings.ProfileConfig( 5468): Adding HidDevService
,I/BtSettings.ProfileConfig( 5468): *********Initializing Bluetooth Profile Settings*******
,D/SettingsProvider( 1016): name = bt_svcst_com.android.bluetooth.gatt.GattService
,D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
,D/SettingsProvider( 1016): selectionArgs: 1002
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1016): ret = -1
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1016): name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
,D/SettingsProvider( 1016): selectionArgs: 1002
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1016): name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 1002
,D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,D/SettingsProvider( 1016): name = bt_svcst_com.android.bluetooth.hid.HidService
,D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 1002
,D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1016): ret = -1
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1016): name = bt_svcst_com.android.bluetooth.hdp.HealthService
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 1002
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,D/SettingsProvider( 1016): name = bt_svcst_com.android.bluetooth.pan.PanService
,D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 1002
,D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1016): ret = -1
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,W/libprocessgroup( 1016): failed to open /acct/uid_10111/pid_4262/cgroup.procs: No such file or directory
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1016): name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 1002
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1016): name = bt_svcst_com.broadcom.bt.service.sap.SapService
,D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 1002
,D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1016): name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 1002
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1016): name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 1002
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1016): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
,D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 1002
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1016): name = bt_svcst_com.android.bluetooth.hid.HidDevService
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 1002
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,D/BluetoothAdapterState( 5468): make
,I/bluedroid( 5468): init
,I/BluetoothAdapterState( 5468): Entering OffState
I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,I/bte_conf( 5468): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 5468): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,E/bt_osi_config( 5468): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 5468): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,E/bt-btif ( 5468): btif_fetch_local_ble_random_bdaddr
,I/bluedroid( 5468): get_profile_interface socket
I/bluedroid( 5468): get_profile_interface map_client
,D/BluetoothAdapterService( 5468): checkAddrForIOP: Loading from conf
,D/BluetoothA2dp( 5468): doBind(): CallingUid(myUserHandle) = 0,
I/GKI_LINUX( 5468): gki_task_entry task_id=1 [BTIF] starting
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/BluetoothAdapterProperties( 5468): Address is:7C:F9:0E:51:18:22
E/BluetoothServiceJni( 5468): populateRssiValuesNative
I/bluedroid( 5468): getModelRssiValues
E/BluetoothServiceJni( 5468): model_rssi_values_callback: low = -70, mid = -60, high = 127
D/BluetoothAdapterProperties( 5468): modelRssiValuesCallback, low, mid, high = -70,-60,127
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothAdapterProperties( 5468): Name is: Thali Test (Galaxy A5)
,D/SettingsProvider( 1016): name = bluetooth_name
,I/bluedroid( 5468): config_hci_snoop_log
,D/BluetoothManagerService( 1016): Broadcasting onBluetoothServiceUp() to 9 receivers.
,D/BluetoothManagerService( 1016): Ble is always on enable gatt
,I/BluetoothManagerService( 1016): enableGattForLeMode, doBind called
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,E/DevicePolicyManagerService( 1016): getAllowBluetoothMode - value retunrs : 2
,E/DevicePolicyManagerService( 1016): getAllowBluetoothMode - value retunrs : 2
,I/BtGatt.JNI( 5468): classInitNative(L900): classInitNative: Success!
,D/SecContentProvider( 1016): uri = 3 selection = isBluetoothEnabled
,D/BluetoothAdapterState( 5468): CURRENT_STATE=OFF, MSG = USER_TURN_ON
,D/BluetoothAdapterProperties( 5468): Setting state to 11
,I/BluetoothAdapterState( 5468): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 5468): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 5468): updateAdapterState state is 11
,D/BluetoothAdapterService( 5468): Autoconnection is available 
D/BluetoothAdapterService( 5468): updateAdapterState prevState = 10newState = 11
,D/BluetoothSecureManager( 5468): getInstant: null
,D/BluetoothSecureManager( 5468): calling getMethod for getService
,D/BluetoothSecureManager( 5468): calling getService
,D/BluetoothSecureManager( 5468): getService return binder: android.os.BinderProxy@1055170a
D/BluetoothManagerService( 1016): Broadcasting onBluetoothServiceUp() to 0 receivers.
,D/BluetoothSecureManagerService( 1016): isSecureModeEnabled
W/InputMethodManagerService( 1016): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 1016): [BT Setting State] State =11
,D/BluetoothSecureManagerService( 1016): getSecureModeSetting, name: secure_mode_enable
,D/BluetoothTile( 1177):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 1177): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1177):  getBluetoothState : 11
D/BtConfig.SecureMode( 5468): isSecureModeOn:false
D/BtSettings.ProfileConfig( 5468): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 5468): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 5468): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 5468): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 5468): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 5468): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 5468): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 5468): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5468): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 5468): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
,D/BluetoothTile( 1177):  handleUpdatestate:false name:null
D/STATUSBAR-QSTileView( 1177): onStateChanged: Bluetooth
D/BtSettings.ProfileConfig( 5468): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 5468): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 5468): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 5468): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
,D/BtSettings.ProfileConfig( 5468): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/StatusBarManagerService( 1016): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
I/SamsungIME( 1767): STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,W/BluetoothAdapterService( 5468): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 5468): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
D/StatusBarManagerService( 1016): setIconVisibility slot=bluetooth visible=false
,D/PhoneStatusBar( 1177): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,W/BluetoothAdapterService( 5468): processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 5468): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 5468): processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 5468): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,W/BluetoothAdapterService( 5468): processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 5468): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/BluetoothAdapterService( 5468): processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
D/BluetoothBondStateMachine( 5468): make
,W/BluetoothAdapterService( 5468): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 5468): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 5468): Not skipping com.android.bluetooth.gatt.GattService
,I/BluetoothBondStateMachine( 5468): StableState(): Entering Off State
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothNotiBroadcastReceiver( 1307): onReceive
,V/BluetoothStatusReceiver( 1177): Received android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothStatusReceiver( 1177): AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,W/BluetoothAdapterService( 5468): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 5468): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 5468): Not skipping com.android.bluetooth.hfp.HeadsetService
,D/BtGatt.DebugUtils( 5468): handleDebugAction() action=null
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/BtGatt.GattService( 5468): Received start request. Starting profile...
D/BtGatt.GattService( 5468): start()
D/BtGatt.GattService( 5468): start()
I/bluedroid( 5468): get_profile_interface gatt
D/BluetoothAdapterService( 5468): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1af741bd
D/BtGatt.AdvertiseManager( 5468): advertise manager created
,E/Zygote  ( 5510): MountEmulatedStorage(),
I/libpersona( 5510): KNOX_SDCARD checking this for 10003
E/Zygote  ( 5510): v2
I/libpersona( 5510): KNOX_SDCARD not a persona
I/SELinux ( 5510): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1016): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=5510 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,I/SELinux ( 5510): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
E/SELinux ( 5510): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/BluetoothAdapterService( 5468): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 5468): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 5468): Not skipping com.android.bluetooth.a2dp.A2dpService
,D/BtGatt.GattService( 5468): mStartError = false
D/BluetoothAdapterService( 5468): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1af741bd
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/art     (  305): Explicit concurrent mark sweep GC freed 8721(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 627us total 23.251ms,
D/Tethering( 1016): interfaceAdded wlan0
,W/BluetoothAdapterService( 5468): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5468): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 5468): Not skipping com.android.bluetooth.hid.HidService
,D/HeadsetService( 5468): Received start request. Starting profile...
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
D/HeadsetService( 5468): start()
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
I/BluetoothHeadsetServiceJni( 5468): classInitNative: succeeds
,D/HeadsetStateMachine( 5468): make
,W/BluetoothAdapterService( 5468): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 5468): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 5468): Not skipping com.android.bluetooth.hdp.HealthService
E/HeadsetStateMachine( 5468): # of Max HF connection is 2
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 628us total 19.489ms
,W/BluetoothAdapterService( 5468): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
D/BtSettings.ProfileConfig( 5468): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 5468): Not skipping com.android.bluetooth.pan.PanService
,D/TimaKeyStoreProvider( 5510): TimaSignature is unavailable
,D/ActivityThread( 5510): Added TimaKeyStore provider
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,D/Tethering( 1016): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1016): interfaceStatusChanged wlan0, false
,I/WifiHW  (  278): wifi_change_fw_path(): fwpath = sta
D/SoftapController(  278): Softap fwReload - Ok
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 646us total 18.248ms
,E/Tethering( 1016): No numeric data
,I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1016): interfaceAdded p2p0
,D/Tethering( 1016): p2p0 is not a tetherable iface, ignoring
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
W/BluetoothAdapterService( 5468): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 5468): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 5468): Not skipping com.android.bluetooth.map.BluetoothMapService
D/CommandListener(  278): Setting iface cfg
D/CommandListener(  278): Trying to bring down wlan0
,D/Tethering( 1016): interfaceLinkStateChanged p2p0, false
D/Tethering( 1016): interfaceStatusChanged p2p0, false
I/Nat464Xlat( 1016): interfaceLinkStateChanged p2p0, false
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
D/CommandListener(  278): Clearing all IP addresses on wlan0
,I/bluedroid( 5468): get_profile_interface handsfree
D/Tethering( 1016): sendTetherStateChangedBroadcast 1, 0, 0
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
D/Tethering( 1016): clearTetheredNotification()
D/Tethering( 1016): InitialState.processMessage what=4
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 5468): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 5468): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 5468): Not skipping com.broadcom.bt.service.sap.SapService
,D/NtpTrustedTime( 1016): forceRefresh() from cache miss
,E/WifiHW  ( 1016): supplicant_name : p2p_supplicant
E/Tethering( 1016): No numeric data
,D/HotspotTile( 1177): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1177): updateTetherState():false, false
D/NtpTrustedTime( 1016): forceRefresh Fail.
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
V/NetworkStats( 1016): performPollLocked(flags=0x1)
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/NetworkStatsFactory( 1016): UpdateStatsForKnox updated
,V/NetworkStats( 1016): performPollLocked() took 5ms
D/NetworkStatsFactory( 1016): UpdateStatsForKnox main else ---
,W/BluetoothAdapterService( 5468): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 5468): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 5468): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 5468): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 5468): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 5468): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 5468): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 5468): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
D/Tethering( 1016): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1016): clearTetheredNotification()
W/BluetoothAdapterService( 5468): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 5468): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 5468): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/BluetoothAdapterService( 5468): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
I/BluetoothAdapterState( 5468): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/NtpTrustedTime( 1016): forceRefresh() from cache miss
V/NetworkStats( 1016): performPollLocked(flags=0x1)
D/NtpTrustedTime( 1016): forceRefresh Fail.
D/NetworkStatsFactory( 1016): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1016): UpdateStatsForKnox main else ---
,D/HotspotTile( 1177): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1177): updateTetherState():false, false
,D/NtpTrustedTime( 1016): forceRefresh() from cache miss
V/NetworkStats( 1016): performPollLocked() took 6ms
D/NtpTrustedTime( 1016): forceRefresh Fail.
I/DualScoManager( 5468): Instantiating Dual Sco Manager
I/DualScoManager( 5468): Set HeadsetServiceHelper
D/BluetoothAtMessage( 5468): createCMTIContentObservers
D/SettingsProvider( 1016): name = bluetooth_hfp_allowed_bvra
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 1002
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,D/NtpTrustedTime( 1016): forceRefresh() from cache miss
D/NtpTrustedTime( 1016): forceRefresh Fail.
W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
D/HeadsetStateMachine( 5468): Enter Disconnected: -2
D/HeadsetService( 5468): mStartError = false
D/BluetoothAdapterService( 5468): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1af741bd
E/BluetoothAdapterService(452411837)( 5468): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
D/HeadsetStateMachine( 5468): Clear mHeadsetBrsf
D/BluetoothA2dp( 1016): Proxy object connected
D/UserAnalysis.PlaceProvider( 5510): PlaceProvider onCreate()
D/A2dpService( 5468): Received start request. Starting profile...
D/A2dpService( 5468): start()
I/BluetoothAvrcpServiceJni( 5468): classInitNative: succeeds
I/bluedroid( 5468): get_profile_interface avrcp
D/HeadsetStateMachine( 5468): map size, before remove : 0
D/HeadsetStateMachine( 5468): map size, after remove: 0
I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
D/BluetoothA2dp( 2674): Proxy object connected
,I/wpa_supplicant( 5528): [wpa_supplicant_init]: use SECRIL
I/wpa_supplicant( 5528): Successfully initialized wpa_supplicant
,I/SecureStorage( 5528): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,D/UserAnalysis.SecureDbManager( 5510): Key for secure DB is newly created,
E/RemoteController( 5468): Cannot set synchronization mode on an unregistered RemoteController
,D/UserAnalysis.SecurePlaceDbHelper( 5510): SecurePlaceDbHelper() 
D/UserAnalysis( 5510): Create SecureDbHelper
I/SecureStorage( 5528): [INFO]: SPID(0x00000000)This device supports Secure Storage
D/IntelligenceServiceApplication( 5510): onCreate()
,I/SecureStorage(  336): [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 5528
I/SecureStorage(  336): [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
I/SecureStorage( 5528): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 5528): ssSupport state is = 1
I/wpa_supplicant( 5528): >>>>> GET KEY, IV <<<<<
I/SecureStorage( 5528): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  336): [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 5528
I/SecureStorage(  336): [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,D/IntelligenceServiceApplication( 5510): no applications having user consent for prediction
I/ActivityManager( 1016): Killing 4899:com.sec.android.diagmonagent/1000 (adj 15): empty #31
I/Avrcp   ( 5468):  Updating now playing list upon AVRCP Start
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
D/WifiMonitor( 1016): startMonitoring(wlan0) with mConnected = false
D/BluetoothMediaBrowser( 5468):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,I/BluetoothA2dpServiceJni( 5468): classInitNative: succeeds
,D/A2dpStateMachine( 5468): make
,V/PlaceDetection v1.0.19 ( 5510): [PlaceDetection::stopService] Service stopped.
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/STATUSBAR-WifiQuickSettingButton( 1177): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1177): Wifi onReceive(2)
,D/HotspotTile( 1177): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/HotspotTile( 1177): onReceive : 2, 0
,I/bluedroid( 5468): get_profile_interface a2dp
,I/GKI_LINUX( 5468): gki_task_entry task_id=2 [A2DP-MEDIA] starting
E/bt-btif ( 5468): warning : media task started media_task_refcnt 1 
D/STATUSBAR-QSTileView( 1177): onStateChanged: Wi-Fi
,D/A2dpService( 5468): mStartError = false
D/BluetoothAdapterService( 5468): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1af741bd
,D/A2dpStateMachine( 5468): Enter Disconnected: -2
D/WifiCredService( 1307): Action received :android.net.wifi.WIFI_STATE_CHANGED
,V/PlaceDetection v1.0.19 ( 5510): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.,
,I/BluetoothHidServiceJni( 5468): classInitNative: succeeds
,D/HidService( 5468): Received start request. Starting profile...
,D/HidService( 5468): start()
I/bluedroid( 5468): get_profile_interface hidhost
D/HidService( 5468): setHidService(): set to: null
D/HidService( 5468): mStartError = false
D/BluetoothAdapterService( 5468): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1af741bd
,I/BluetoothHealthServiceJni( 5468): classInitNative: succeeds
D/HealthService( 5468): Received start request. Starting profile...
,D/HealthService( 5468): start()
D/BluetoothMediaBrowser( 5468): no now playing list
,D/BluetoothMediaBrowser( 5468):  getNowPlayingId now playing id : -1
,I/bluedroid( 5468): get_profile_interface health
,D/HealthService( 5468): mStartError = false
,D/BluetoothAdapterService( 5468): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1af741bd
,I/BluetoothPanServiceJni( 5468): classInitNative(L105): succeeds
,D/BluetoothPan( 1016): BluetoothPAN Proxy object connected
,D/PanService( 5468): Received start request. Starting profile...
,D/PanService( 5468): start()
D/BluetoothPanServiceJni( 5468): initializeNative(L110): pan
I/bluedroid( 5468): get_profile_interface pan
,D/PanService( 5468): mStartError = false
,D/BluetoothAdapterService( 5468): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1af741bd
,D/HeadsetStateMachine( 5468): Proxy object connected
,D/HeadsetStateMachine( 5468): Try to query the phonestate on bind
,I/Telecom ( 1417): BluetoothPhoneService: queryPhoneState
,I/Telecom ( 1417): BluetoothPhoneService: handleMessage(7) / param 0
,I/Telecom ( 1417): BluetoothPhoneService: updateHeadsetWithCallState
,I/Telecom ( 1417): BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,I/Telecom ( 1417): BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,I/Telecom ( 1417): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,W/BluetoothHeadset( 1417): Proxy not attached to service
,I/Telecom ( 1417): BluetoothPhoneService: Result of Message : true
,D/HeadsetPhoneState( 5468): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,D/HeadsetStateMachine( 5468): Disconnected process message: 11
,D/BluetoothMapService( 5468): Received start request. Starting profile...
,D/BluetoothMapService( 5468): start()
,D/BluetoothMapService( 5468): mStartError = false
,D/BluetoothAdapterService( 5468): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1af741bd
,I/BluetoothSAPServiceJni( 5468): classInitNative(L204): succeeds
,D/SapService( 5468): Received start request. Starting profile...
D/SapService( 5468): start()
D/BluetoothSAPServiceJni( 5468): initializeNative(L209): sap
I/bluedroid( 5468): get_profile_interface sap
D/SapService( 5468): mStartError = false
D/BluetoothAdapterService( 5468): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1af741bd
D/HeadsetPhoneState( 5468): sendDeviceDataStateChanged
,D/HeadsetPhoneState( 5468): Signal level : previous=0 curr=0
E/BluetoothAdapterService(452411837)( 5468): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
V/HeadsetService( 5468): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/BluetoothA2dp( 5468): Proxy object connected
D/BluetoothAdapterService( 5468): Bluetooth A2dp source service connected
,D/HeadsetStateMachine( 5468): Disconnected process message: 18
D/HeadsetStateMachine( 5468): Disconnected process message: 10
,E/BluetoothAdapterService(452411837)( 5468): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
E/BluetoothAdapterService(452411837)( 5468): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
D/HeadsetPhoneState( 5468): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 5468): Disconnected process message: 11
,E/BluetoothAdapterService(452411837)( 5468): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
E/BluetoothAdapterService(452411837)( 5468): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/AuthorizationBluetoothService( 1725): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=5537 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
E/Zygote  ( 5537): MountEmulatedStorage()
I/libpersona( 5537): KNOX_SDCARD checking this for 10145
E/Zygote  ( 5537): v2
I/libpersona( 5537): KNOX_SDCARD not a persona
,I/SELinux ( 5537): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 5537): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 5537): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_4899/cgroup.procs: No such file or directory
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3388): Starting #2,
I/Hs20UtilService( 3388): Message received 5011
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 5537): TimaSignature is unavailable
D/ActivityThread( 5537): Added TimaKeyStore provider
,E/Zygote  ( 5549): MountEmulatedStorage()
I/libpersona( 5549): KNOX_SDCARD checking this for 1000
E/Zygote  ( 5549): v2
I/libpersona( 5549): KNOX_SDCARD not a persona
,I/SELinux ( 5549): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 5549): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 5549): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=5549 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,W/ResourcesManager( 5537): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.,
W/ResourcesManager( 5537): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5537): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5537): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5537): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/SecureStorage(  336): [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,D/TimaKeyStoreProvider( 5549): TimaSignature is unavailable
,D/ActivityThread( 5549): Added TimaKeyStore provider
,I/SecureStorage( 5528): [INFO]: SPID(0x00000002)Processing data has been completed
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,I/wpa_supplicant( 5528): Ctrl_iface: loading cred from phone
,I/SecureStorage( 5528): [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,D/SecurityLogAgent( 5549): KnoxConfiguration : Current State = 1
,I/SecureStorage( 5528): [INFO]: SPID(0x00000002)This device supports Secure Storage,
,I/SecureStorage(  336): [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 5528
I/SecureStorage(  336): [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
I/SecureStorage( 5528): [INFO]: SPID(0x00000002)SS Daemon is running
I/wpa_supplicant( 5528): ssSupport state is = 1
D/SecurityLogAgent( 5549): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5549): StateMachine : Current State = 1
,I/wpa_supplicant( 5528): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,E/wpa_supplicant( 5528): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 5528): SIM READ ERROR
I/wpa_supplicant( 5528): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5528): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 5528): SIM READ ERROR
I/wpa_supplicant( 5528): Blacklist: Clear (all) 
,I/wpa_supplicant( 5528): wpa_default_ap_write_once
I/wpa_supplicant( 5528): There is no /data/misc/wifi/default_ap.check. Start copy default ap
I/wpa_supplicant( 5528): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5528): getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
I/wpa_supplicant( 5528): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5528): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
I/wpa_supplicant( 5528): rfkill: Cannot open RFKILL control device
,D/Tethering( 1016): interfaceLinkStateChanged wlan0, false
D/Tethering( 1016): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, false
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/SecurityLogAgent( 5549): StateMachine : Changed Current State = 1
,I/ActivityManager( 1016): Killing 4916:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,E/BluetoothAdapterService(452411837)( 5468): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,E/BluetoothAdapterService(452411837)( 5468): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,E/SMD     (  288): DCD OFF,
,D/BluetoothAdapterState( 5468): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 5468): enable
,I/GKI_LINUX( 5468): gki_task_entry task_id=0 [BTU] starting
I/bt_hci_bdroid( 5468): init
,I/bt_vendor( 5468): bt-vendor : init
,I/bt_vendor( 5468): bt-vendor : get_bt_soc_type
E/bt_vendor( 5468): get_bt_soc_type: Failed to get soc type
,I/bt_vendor( 5468): init: Local BD Address : 22:18:51:0e:f9:7c
D/bt_userial_mct( 5468): userial_init
I/bt_vendor( 5468): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 5468): Starting hciattach daemon
,I/bt_vendor( 5468): try to set false
,I/bt_vendor( 5468): bt-vendor : BT_VND_OP_POWER_CTRL: On,
,I/bt_vendor( 5468): Starting hciattach daemon
I/bt_vendor( 5468): try to set true,
I/ServiceManager(  315): Waiting for service AtCmdFwd...
I/wpa_supplicant( 5528): wlan0: Setting scan request: 0 sec 100000 usec
,I/ActivityManager( 1016): Killing 4374:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,I/qcom-bluetooth( 5581): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,I/qcom-bluetooth( 5587): /system/etc/init.qcom.bt.sh: Transport : smd ,
,I/qcom-bluetooth( 5588): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,I/qcom-bluetooth( 5590): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,I/qcom-bluetooth( 5591): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,W/libprocessgroup( 1016): failed to open /acct/uid_10142/pid_4916/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10044/pid_4374/cgroup.procs: No such file or directory
,I/qcom-bluetooth( 5592): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 5593): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,I/wpa_supplicant( 5528): wlan0: State: DISCONNECTED -> DISCONNECTED,
I/SecureStorage( 5528): [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,I/SecureStorage( 5528): [INFO]: SPID(0x00000002)This device supports Secure Storage
,I/SecureStorage(  336): [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 5528
I/SecureStorage(  336): [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
I/SecureStorage( 5528): [INFO]: SPID(0x00000002)SS Daemon is running
I/wpa_supplicant( 5528): ssSupport state is = 1
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 27078(1481KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 26MB/40MB, paused 2.617ms total 178.445ms,
I/wpa_supplicant( 5528): Ctrl_iface: loading cred from phone
I/SecureStorage( 5528): [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,D/BadgeProvider( 5212): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/SecureStorage( 5528): [INFO]: SPID(0x00000002)This device supports Secure Storage,
I/SecureStorage(  336): [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 5528
I/SecureStorage(  336): [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,I/SecureStorage( 5528): [INFO]: SPID(0x00000002)SS Daemon is running
,I/wpa_supplicant( 5528): ssSupport state is = 1
I/wpa_supplicant( 5528): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5528): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 5528): SIM READ ERROR
I/wpa_supplicant( 5528): wpa_default_ap_write_once
I/wpa_supplicant( 5528): There is no /data/misc/wifi/default_ap.check. Start copy default ap
I/wpa_supplicant( 5528): rfkill: Cannot open RFKILL control device
,D/Tethering( 1016): interfaceLinkStateChanged p2p0, false
D/Tethering( 1016): interfaceStatusChanged p2p0, false
I/Nat464Xlat( 1016): interfaceLinkStateChanged p2p0, false
D/Tethering( 1016): interfaceLinkStateChanged p2p0, false
D/Tethering( 1016): interfaceStatusChanged p2p0, false
I/ConfigService( 1725): onDestroy
I/Nat464Xlat( 1016): interfaceLinkStateChanged p2p0, false
D/BadgeProvider( 5212): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5212): sendNotify, [notify] : null
D/Launcher.Model( 1472): reloadBadges entered.
D/BadgeProvider( 5212): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5212): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5212): update, [UpdateCount] : 1
,I/wpa_supplicant( 5528): p2p0: State: DISCONNECTED -> INACTIVE
I/wpa_supplicant( 5528): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,I/wpa_supplicant( 5528): p2p0: State: INACTIVE -> DISCONNECTED
I/wpa_supplicant( 5528): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
I/wpa_supplicant( 5528): Skip scan - bUseNetwork false
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,E/WifiStateMachine( 1016): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,D/WifiNative-wlan0( 1016): callSECApiBoolean - ID [21]
,I/wpa_supplicant( 5528): HOTSPOT20_ENABLE called
I/wpa_supplicant( 5528): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,E/wpa_supplicant( 5528): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 5528): SIM READ ERROR
I/wpa_supplicant( 5528): Blacklist: Clear (all) 
,I/wpa_supplicant( 5528): wlan0: Setting scan request: 0 sec 0 usec,
,I/wpa_supplicant( 5528): Skip scan - bUseNetwork false,
,D/WifiNative-wlan0( 1016): callSECApiInt - ID [210]
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WifiConfigStore( 1016): Loading config and enabling all networks 
D/STATUSBAR-WifiQuickSettingButton( 1177): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1177): Wifi onReceive(3)
,D/STATUSBAR-QSTileView( 1177): onStateChanged: Wi-Fi
,D/HotspotTile( 1177): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/WifiCredService( 1307): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/HotspotTile( 1177): onReceive : 3, 0
,E/WifiConfigStore( 1016): Not a HS20
,E/WifiConfigStore( 1016): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3388): Starting #3
,D/SecurityLogAgent( 5549): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 5549): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5549): StateMachine : Current State = 1
D/SecurityLogAgent( 5549): StateMachine : Changed Current State = 1
I/Hs20UtilService( 3388): Message received 5011
,I/qcom-bluetooth( 5604): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:51:18:22 
,D/WifiNative-wlan0( 1016): callSECApiInt - ID [65],
,D/WifiNative-wlan0( 1016): callSECApiBoolean - ID [13],
I/wpa_supplicant( 5528): USE_NETWORK : USE_NETWORK ON
I/wpa_supplicant( 5528): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 5528): reset timer : RESET_TIMER 0
I/wpa_supplicant( 5528): P2P: Current p2p state = IDLE
I/wpa_supplicant( 5528): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 5528): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 5528): First Scan Start
I/wpa_supplicant( 5528): Scan requested (ret=0) - scan timeout 30 seconds
,I/qcom-bluetooth( 5606): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,D/WifiNative-wlan0( 1016): Setting external_sim to 1
,D/WifiStateMachine( 1016): Setting OUI to DA-A1-19
I/WifiNative-HAL( 1016): startHal
E/wifi    ( 1016): getStaticLongField sWifiHalHandle 0x9d35188c
I/WifiNative-HAL( 1016): Could not start hal
,E/WifiNative-wlan0( 1016): do suspend true
,E/WifiStateMachine( 1016): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3,
D/WifiScanningService( 1016): SCAN_AVAILABLE : 3
D/WifiP2pService( 1016): P2pDisabledState{ what=131203 }
D/WifiScanningService( 1016): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler },
I/WifiNative-HAL( 1016): startHal
E/wifi    ( 1016): getStaticLongField sWifiHalHandle 0x9e7919bc
I/WifiNative-HAL( 1016): Could not start hal
E/WifiScanningService( 1016): could not start HAL
,D/RttService( 1016): SCAN_AVAILABLE : 3
D/CommandListener(  278): Setting iface cfg
D/WifiP2pService( 1016): P2pEnablingState
D/CommandListener(  278): Trying to bring up p2p0
,D/WifiP2pService( 1016): P2pEnablingState{ what=147457 }
D/WifiMonitor( 1016): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService( 1016): P2p socket connection successful
D/RttService( 1016): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1016): P2pEnabledState
,D/WifiP2pService( 1016): sending p2p connection changed broadcast: IDLE
,E/WifiStateMachine( 1016): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,D/WifiDisplayController( 1016): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiDisplayController( 1016): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 1016): disconnect
D/WifiDisplayController( 1016): updateConnection
D/WifiDisplayController( 1016): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/WifiStateMachine( 1016): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiNative-wlan0( 1016): callSECStringApiVoid - ID [215]
E/WifiNative-wlan0( 1016): invaild command id : 215
,E/WifiStateMachine( 1016): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiNative-wlan0( 1016): callSECStringApiVoid - ID [215]
E/WifiNative-wlan0( 1016): invaild command id : 215
,I/wpa_supplicant( 5528): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,D/AllShareCastTile( 1177): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
I/wpa_supplicant( 5528): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
D/AllShareCastTile( 1177): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
D/WifiP2pService( 1016): create mNetworkAgent
,I/wpa_supplicant( 5528): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,D/SecContentProvider2( 1016): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1016): mCursor = null
I/bt_vendor( 5468): bluetooth satus is on
D/bt_userial_mct( 5468): userial_open(port:0)
I/bt_vendor( 5468): bt-vendor : BT_VND_OP_USERIAL_OPEN
,I/bt_vendor( 5468): Done intiailizing UART
,I/bt_vendor( 5468): Done intiailizing UART
I/bt_userial_mct( 5468): CMD=65, EVT=65, ACL_Out=66, ACL_In=66
I/bt_vendor( 5468): Bluetooth Firmware and transport layer are initialized
,D/bt_userial_mct( 5468): Entering userial_read_thread()
,D/Tethering( 1016): interfaceLinkStateChanged p2p0, false
,D/Tethering( 1016): interfaceStatusChanged p2p0, false
,I/Nat464Xlat( 1016): interfaceLinkStateChanged p2p0, false
,D/ConnectivityService( 1016): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/WifiDisplayController( 1016): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService( 1016): hsengiv:checkWhatTypeOfNetwork and the value is false
,E/ConnectivityService( 1016): updateNetworkInfo()
D/ConnectivityService( 1016): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from null to UNKNOWN, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,E/CSLegacyTypeTracker( 1016): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} } for legacy network type 13
,D/WifiNative-p2p0( 1016): p2pGetDeviceAddress
D/WifiNative-p2p0( 1016): p2pGetDeviceAddress returning 7e:f9:0e:51:18:23
,D/WifiP2pService( 1016): DeviceAddress: 7e:18:23
,D/WifiDisplayController( 1016): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A5)
D/WifiDisplayController( 1016):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiDisplayController( 1016):  primary type: 10-0050F204-5
D/WifiDisplayController( 1016):  secondary type: null
D/WifiDisplayController( 1016):  wps: 0
D/WifiDisplayController( 1016):  grpcapab: 0
D/WifiDisplayController( 1016):  devcapab: 0
D/WifiDisplayController( 1016):  status: 3
D/WifiDisplayController( 1016):  wfdInfo: null
D/WifiDisplayController( 1016):  groupownerAddress: null
D/WifiDisplayController( 1016):  GOdeviceName: null
D/WifiDisplayController( 1016):  interfaceAddress: 
D/WifiDisplayController( 1016):  SConnectInfo : null
,D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
V/NearbySettings( 1307): DMSUtil.isNetworkConnected - flag-null, state-null
,I/        ( 5468): BTE_InitTraceLevels -- TRC_HCI
I/        ( 5468): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 5468): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 5468): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 5468): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 5468): BTE_InitTraceLevels -- TRC_A2D
I/        ( 5468): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 5468): BTE_InitTraceLevels -- TRC_BTM
I/        ( 5468): BTE_InitTraceLevels -- TRC_GAP
I/        ( 5468): BTE_InitTraceLevels -- TRC_PAN
I/        ( 5468): BTE_InitTraceLevels -- TRC_SAP
I/        ( 5468): BTE_InitTraceLevels -- TRC_SDP
I/        ( 5468): BTE_InitTraceLevels -- TRC_GATT
I/        ( 5468): BTE_InitTraceLevels -- TRC_SMP
I/        ( 5468): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 5468): BTE_InitTraceLevels -- TRC_BTIF
I/        ( 5468): BTE_InitTraceLevels -- TRC_PROTOCOL
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1307): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1307): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1307): MountReceiver.mPrefHandler - 7002
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5610): MountEmulatedStorage()
,E/Zygote  ( 5610): v2
,I/libpersona( 5610): KNOX_SDCARD checking this for 10068
I/libpersona( 5610): KNOX_SDCARD not a persona,
I/ActivityManager( 1016): Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=5610 uid=10068 gids={50068, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5610): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,D/WifiP2pService( 1016): sending p2p persistent groups changed broadcast
,D/WifiP2pService( 1016): InactiveState
D/WifiP2pService( 1016): InactiveState{ what=143376 },
D/WifiP2pService( 1016): P2pEnabledState{ what=143376 }
I/wpa_supplicant( 5528): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
I/SELinux ( 5610): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/ConnectivityService( 1016): updateNetworkInfo()
D/WifiP2pService( 1016): InactiveState{ what=143376 }
,D/WifiP2pService( 1016): P2pEnabledState{ what=143376 }
,E/SELinux ( 5610): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5610): TimaSignature is unavailable
,D/ActivityThread( 5610): Added TimaKeyStore provider
,W/ResourcesManager( 5610): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/FileShare-Client( 5610): ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/FileShare-Client( 5610): ClientBroadcastReceiver.onReceive - disconnected
,W/bt-l2cap( 5468): l2c_link_processs_ble_num_bufs 16
,E/bt-btm  ( 5468): BTM_SecRegister:p_cb_info->p_le_callback == 0xa44c96e9 
,E/bt-btm  ( 5468): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa44c96e9 
,D/BluetoothAdapterProperties( 5468): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0,
,E/bt-btif ( 5468): Calling BTA_HhEnable
,E/bt-btif ( 5468): btif_storage_get_adapter_property service_mask:0x2120048
,D/BluetoothAdapterProperties( 5468): Address is:7C:F9:0E:51:18:22
,E/BluetoothServiceJni( 5468): populateRssiValuesNative
,I/bluedroid( 5468): getModelRssiValues
,E/BluetoothServiceJni( 5468): model_rssi_values_callback: low = -70, mid = -60, high = 127
D/BluetoothAdapterProperties( 5468): modelRssiValuesCallback, low, mid, high = -70,-60,127
,D/SettingsProvider( 1016): name = bluetooth_name
,D/BluetoothAdapterProperties( 5468): Name is: Thali Test (Galaxy A5)
,D/BluetoothUtils( 5468): getBtEnabledContainers(): btContainers = []
,D/BluetoothAdapterProperties( 5468): Scan Mode:20
D/BluetoothAdapterProperties( 5468): Discoverable Timeout:120
,D/BluetoothAdapterProperties( 5468): LE Address is:FC:F3:1C:A2:30:44
,E/bt-btif ( 5468): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
E/bt-btif ( 5468): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,E/bt-btif ( 5468): btif_sock_init: !radio_req && !rfc_init
E/bt_mct  ( 5468): hci lib postload completed
,E/bt-btif ( 5468): btif_sock_init: !vhci_init
D/IOP_DB_BT( 5468): db_open: file /etc/bluetooth/iop_bt.db
,D/IOP_DB_BT( 5468): db_open: db_open : handle 3027939344l, read 13894 bytes onto local cache
,D/IOP_DB_BT( 5468): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 5468): db_query: result 1
I/        ( 5468): iop_db_open: iop_db_open status 0
,D/bte_conf( 5468): Device ID record 1 : primary
D/bte_conf( 5468):   vendorId            = 0075
D/bte_conf( 5468):   vendorIdSource      = 0001
D/bte_conf( 5468):   product             = 0100
D/bte_conf( 5468):   version             = 0200
D/bte_conf( 5468):   clientExecutableURL = 
D/bte_conf( 5468):   serviceDescription  = 
D/bte_conf( 5468):   documentationURL    = 
D/bte_conf( 5468): bte_load_did_conf no section named DID2.
,D/BluetoothPanServiceJni( 5468): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState( 5468): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 5468): ScanMode =  20
D/BluetoothAdapterProperties( 5468): State =  11
D/SecContentProvider( 1016): uri = 3 selection = isDiscoverableEnabled
,D/FileShare-Client( 5610): Outbound.stopDelayTimer - 
,D/BluetoothAdapterProperties( 5468): Setting state to 12
I/BluetoothAdapterState( 5468): Bluetooth adapter state changed: 11-> 12
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5628): MountEmulatedStorage()
I/libpersona( 5628): KNOX_SDCARD checking this for 10069
E/Zygote  ( 5628): v2
I/libpersona( 5628): KNOX_SDCARD not a persona
I/SELinux ( 5628): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 5628): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
I/ActivityManager( 1016): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=5628 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 5628): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/BluetoothUtils( 5468): getBtEnabledContainers(): btContainers = [],
D/BluetoothAdapterProperties( 5468): Scan Mode:21
D/BluetoothAdapterProperties( 5468): Discoverable Timeout:120
D/SettingsProvider( 1016): name = bluetooth_a2dp_sink_mode
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed,
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 1002
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,I/ActivityManager( 1016): Killing 3958:com.sec.spp.push/u0a35 (adj 15): empty #31
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=1002,
,D/BluetoothAdapterService( 5468): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 5468): updateAdapterState state is 12
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
D/BluetoothA2dp( 1016): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 5366): onBluetoothStateChange: up=true
D/BluetoothAdapter( 5366): onBluetoothStateChange: Bluetooth is on
D/BluetoothAdapterService( 5468): Autoconnection is available 
D/BluetoothAdapterService( 5468): updateAdapterState prevState = 11newState = 12
D/BluetoothAdapterService( 5468): starting service from this receiver
,D/BluetoothAdapter( 1417): onBluetoothStateChange: up=true
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
D/BluetoothAdapter( 1417): onBluetoothStateChange: Bluetooth is on
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/BluetoothAdapterState( 5468): Entering On State from state = 11
D/BluetoothAdapter( 1427): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1427): onBluetoothStateChange: Bluetooth is on
,D/BluetoothAdapter( 1016): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 1016): onBluetoothStateChange: Bluetooth is on
D/BluetoothAdapter( 1683): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1683): onBluetoothStateChange: Bluetooth is on
,D/BluetoothAdapter( 2674): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 2674): onBluetoothStateChange: Bluetooth is on
,D/BluetoothAdapter( 5468): onBluetoothStateChange: up=true
D/BluetoothAdapter( 5468): onBluetoothStateChange: Bluetooth is on
,D/BluetoothAdapter( 1177): onBluetoothStateChange: up=true
I/BluetoothPbapService( 5468): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
D/BluetoothAdapter( 1177): onBluetoothStateChange: Bluetooth is on
,D/BluetoothAdapter( 1440): onBluetoothStateChange: up=true
,D/TimaKeyStoreProvider( 5628): TimaSignature is unavailable
,D/ActivityThread( 5628): Added TimaKeyStore provider
,D/BluetoothAdapter( 1440): onBluetoothStateChange: Bluetooth is on
,D/BluetoothA2dp( 2674): onBluetoothStateChange: up=true
D/BluetoothA2dp( 5468): onBluetoothStateChange: up=true
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,W/InputMethodManagerService( 1016): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService( 1016): [BT Setting State] State =12
I/InputMethodManagerService( 1016): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,D/BluetoothHeadset( 1417): registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@292ce35b, true
,D/BluetoothTile( 1177):  onBluetoothStateChange:
,D/BluetoothHeadset( 1417): registerMessageListener
,D/BluetoothTile( 1177): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1177):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 1177):  getBluetoothState : 12
,D/BluetoothTile( 1177):  handleUpdatestate:false name:null
,D/BluetoothTile( 1177):  handleUpdatestate:false name:null
,I/SamsungIME( 1767): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,I/BluetoothPbapService( 5468): Handler(): got msg=1
,D/HeadsetService( 5468): registerMessageListener
,D/HeadsetService( 5468): registerMessageListener
D/HeadsetStateMachine( 5468): Disconnected process message: 70
D/HeadsetStateMachine( 5468): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@14cdfb0e
,I/Telecom ( 1417): BluetoothPhoneService: handleMessage(7) / param null
I/Telecom ( 1417): BluetoothPhoneService: updateHeadsetWithCallState
D/SecContentProvider( 1016): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,D/BluetoothTile( 1177):  handleUpdatestate:false name:null
,W/libprocessgroup( 1016): failed to open /acct/uid_10035/pid_3958/cgroup.procs: No such file or directory
,D/StatusBarManagerService( 1016): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,I/Telecom ( 1417): BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
I/Telecom ( 1417): BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
I/Telecom ( 1417): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,D/StatusBarManagerService( 1016): setIconVisibility slot=bluetooth visible=true
,D/PhoneStatusBar( 1177): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/FileShare-Server( 5628): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,V/BluetoothPbapService( 5468): PBAP Service initSocket try: 0
,D/HeadsetStateMachine( 5468): Disconnected process message: 9
,D/HeadsetStateMachine( 5468): mNumActive: 0 mNumHeld: 0 mCallState: 6
,D/BluetoothMapMasInstance( 5468): set MAP SDP message type : 1
,I/ActivityManager( 1016): Killing 4622:com.sec.spp.push:RemoteNotiProcess/u0a35 (adj 15): empty #31
,D/audio_hw_primary(  283): adev_set_parameters: enter: A2dpSuspended=false
,V/voice   (  283): voice_set_parameters: enter: A2dpSuspended=false
,V/voice   (  283): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  283): platform_set_parameters: enter: A2dpSuspended=false
V/msm8974_platform(  283): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  283): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  283): adev_set_parameters: exit
E/HeadsetStateMachine( 5468): terminateScoUsingVirtualVoiceCall:No present call to terminate
,D/BluetoothSocket( 5468): bindListen(): myUserId = 0
D/BluetoothSocket( 5468): bindListen(): myUserId = 0
W/BluetoothAdapter( 5468): getBluetoothService() called with no BluetoothManagerCallback
W/BluetoothAdapter( 5468): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 5468): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
D/BluetoothSocket( 5468): bindListen(), new LocalSocket 
D/BluetoothSocket( 5468): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 5468): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1906592f
D/BluetoothSocket( 5468): channel: 19
D/BluetoothPbapService( 5468): PBAP Socket is BluetoothServerSocket
D/BluetoothSocket( 5468): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
D/BluetoothSocket( 5468): bindListen(), new LocalSocket 
D/BluetoothSocket( 5468): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 5468): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3a7b3c
D/BluetoothSocket( 5468): channel: 5
,W/ContextImpl( 1307): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,D/LocalBluetoothProfileManager( 1307): Adding local A2DP profile
,D/BluetoothA2dp( 1307): doBind(): CallingUid(myUserHandle) = 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/LocalBluetoothProfileManager( 1307): Adding local HEADSET profile
,E/BluetoothHeadset( 1307): BTStateChangeCB is registed
,D/BluetoothHeadset( 1307): doBind(): CallingUid(myUserHandle) = 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 1307): BluetoothHeadset service is binded
,D/BluetoothMap( 1307): Create BluetoothMap proxy object
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,W/ContextImpl( 1307): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
D/Bluetoothsap( 1307): bindService called to Bluetooth SAP Service
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/LocalBluetoothProfileManager( 1307): PANU : true
,W/LocalBluetoothProfileManager( 1307): Warning: SAP profile was previously added.
D/LocalBluetoothProfileManager( 1307): LocalBluetoothProfileManager construction complete,
,D/DockEventReceiver( 1307): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1307): onReceive
D/BluetoothA2dp( 1307): Proxy object connected
D/A2dpProfile( 1307): Bluetooth service connected
,V/BluetoothStatusReceiver( 1177): Received android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothStatusReceiver( 1177): AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,D/HeadsetProfile( 1307): Bluetooth service connected
,D/BluetoothMap( 1307): Proxy object connected
D/MapProfile( 1307): Bluetooth service connected
D/BluetoothMap( 1307): getConnectedDevices()
,D/BluetoothAdapterService( 5468): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1af741bd
D/BtConfig.SecureMode( 5468): isSecureModeOn:false
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/AuthorizationBluetoothService( 1725): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/libprocessgroup( 1016): failed to open /acct/uid_10035/pid_4622/cgroup.procs: No such file or directory
,D/BluetoothPbap( 1307): Proxy object connected
,D/PbapServerProfile( 1307): Bluetooth service connected
,D/Bluetoothsap( 1307): BluetoothSAP Proxy object connected
D/SapProfile( 1307): Bluetooth service connected
,D/Bluetoothsap( 1307): getConnectedDevices()
,D/BluetoothInputDevice( 1307): Proxy object connected
,D/HidProfile( 1307): Bluetooth service connected
,D/BluetoothPan( 1307): BluetoothPAN Proxy object connected
,D/PanProfile( 1307): Bluetooth service connected
,D/SecContentProvider( 1016): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,D/BluetoothSocket( 5468): bindListen(): myUserId = 0
,W/BluetoothAdapter( 5468): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 5468): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[81]}
D/BluetoothSocket( 5468): bindListen(), new LocalSocket 
D/BluetoothSocket( 5468): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 5468): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@36725de6
,D/BluetoothSocket( 5468): channel: 12
I/BtOppRfcommListener( 5468): Accept thread started.
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/wpa_supplicant( 5528): nl80211: Received scan results (8 BSSes),
I/wpa_supplicant( 5528): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 5528): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 5528): Trying to associate with  'G700'
I/wpa_supplicant( 5528): wlan0: State: SCANNING -> ASSOCIATING,
I/wpa_supplicant( 5528): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
D/WifiMonitor( 1016): didn't find BSSID Trying to associate with SSID 'NG700'
I/WifiNative-HAL( 1016): startHal
,E/wifi    ( 1016): getStaticLongField sWifiHalHandle 0x9d3518ac
I/WifiNative-HAL( 1016): Could not start hal
,D/SecContentProvider2( 1016): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1016): mCursor = null
,E/wpa_supplicant( 5528): Cmd 35605 not handled
,I/wpa_supplicant( 5528): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 5528): wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
I/wpa_supplicant( 5528): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 5528): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 5528): Associated with C0.AA.48
D/Tethering( 1016): interfaceLinkStateChanged wlan0, false
D/Tethering( 1016): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 5528): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 5528): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 5528): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1016): interfaceLinkStateChanged wlan0, false,
I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, false
D/Tethering( 1016): interfaceStatusChanged wlan0, false
,D/Tethering( 1016): interfaceLinkStateChanged wlan0, false
D/Tethering( 1016): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, false
,D/SecContentProvider2( 1016): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1016): mCursor = null
,D/Tethering( 1016): interfaceLinkStateChanged wlan0, true
,D/Tethering( 1016): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 5528): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/SecContentProvider2( 1016): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1016): mCursor = null
I/wpa_supplicant( 5528): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, true
I/wpa_supplicant( 5528): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 5528): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 5528): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 5528): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 5528): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,E/Tethering( 1016): No numeric data
I/wpa_supplicant( 5528): Blacklist: Clear (temp) 
I/wpa_supplicant( 5528): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 1016): interfaceLinkStateChanged wlan0, true
,D/Tethering( 1016): interfaceStatusChanged wlan0, true
,I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, true
,D/Tethering( 1016): sendTetherStateChangedBroadcast 1, 0, 0
,D/Tethering( 1016): clearTetheredNotification()
D/NtpTrustedTime( 1016): forceRefresh() from cache miss
D/WifiNative-wlan0( 1016): callSECApiVoid - ID [50]
,D/EnterpriseController(  278): uids 1000
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 1000
,D/HotspotTile( 1177): onReceive : android.net.conn.TETHER_STATE_CHANGED
,D/HotspotTile( 1177): updateTetherState():false, false
D/EnterpriseController(  278): uids 1000
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 1000
,D/NtpTrustedTime( 1016): forceRefresh Fail.
,E/WifiConfigStore( 1016): setLastSelectedConfiguration -1
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,V/NetworkStats( 1016): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1016): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1016): UpdateStatsForKnox main else ---
,D/ConnectivityService( 1016): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService( 1016): hsengiv:checkWhatTypeOfNetwork and the value is false
,E/ConnectivityService( 1016): updateNetworkInfo()
,V/NetworkStats( 1016): performPollLocked() took 4ms
,E/WifiConfigStore( 1016): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService( 1016): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/NtpTrustedTime( 1016): forceRefresh() from cache miss
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,E/WifiConfigStore( 1016): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/Hs20UtilService( 3388): Starting #4
,D/NtpTrustedTime( 1016): forceRefresh Fail.
,I/Hs20UtilService( 3388): Message received 5007
,D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
V/NearbySettings( 1307): DMSUtil.isNetworkConnected - flag-null, state-null
,D/CommandListener(  278): Setting iface cfg
,I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED,
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1307): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1307): MountReceiver.mPrefHandler - 7002
,E/WifiStateMachine( 1016): Start Dhcp Watchdog 1
,D/SecContentProvider2( 1016): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1016): mCursor = null
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiNative-wlan0( 1016): do suspend false
,D/WifiP2pService( 1016): InactiveState{ what=143375 }
,D/WifiP2pService( 1016): P2pEnabledState{ what=143375 }
,D/SecContentProvider2( 1016): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1016): mCursor = null
,E/dhcpcd  ( 5659): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,I/dhcpcd  ( 5659): version 5.5.6 starting,
,E/dhcpcd  ( 5659): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,I/dhcpcd  ( 5659): wlan0: sending IPv6 Router Solicitation,
E/dhcpcd  ( 5659): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 5659): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 5659): bssid match
,I/dhcpcd  ( 5659): wlan0: rebinding lease of 192.168.1.137
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,V/AlarmManager( 1016): waitForAlarm result :4,
,I/dhcpcd  ( 5659): wlan0: acknowledged 192.168.1.137 from 192.168.1.1
,D/SSRM:n  ( 1016): SIOP:: AP = 380
,I/dhcpcd  ( 5659): wlan0: leased 192.168.1.137 for 86400 seconds
,I/PowerManagerService( 1016): [PWL] Off : 30s ago,
I/PowerManagerService( 1016): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1016): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1016): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=1996, ws=null) (elapsedTime=48137)
,I/PowerManagerService( 1016): [PWL]       PARTIAL_WAKE_LOCK              'bluedroid_timer' (uid=1002, pid=5468, ws=null) (elapsedTime=2180)
I/PowerManagerService( 1016): [PWL]       PARTIAL_WAKE_LOCK              'AudioMix' (uid=1013, pid=0, ws=null) (elapsedTime=1910)
I/PowerManagerService( 1016): [PWL]       PARTIAL_WAKE_LOCK              'AudioMix' (uid=1013, pid=0, ws=null) (elapsedTime=1907)
,E/WifiNative-wlan0( 1016): do suspend true
,D/WifiP2pService( 1016): InactiveState{ what=143375 },
D/WifiP2pService( 1016): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiStateMachine( 1016): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
E/WifiStateMachine( 1016): VerifyingLinkState enter
,D/WifiNative-wlan0( 1016): callSECApiInt - ID [210]
,E/ConnectivityService( 1016): updateNetworkInfo()
,D/ConnectivityService( 1016): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,D/ConnectivityService( 1016): Adding iface wlan0 to network 502
,D/WifiWatchdogStateMachine( 1016): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 1016): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
D/WifiWatchdogStateMachine.DnsResolver( 1016): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/WifiWatchdogStateMachine.SingDnsChecker( 1016): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1016): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
D/ConnectivityService( 1016): Adding Route [fe80::/64 -> :: wlan0] to network 502
,D/ConnectivityService( 1016): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 502
,E/WifiStateMachine( 1016): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,I/Hs20UtilService( 3388): Starting #5,
,I/Hs20UtilService( 3388): Message received 5007
,D/ConnectivityService( 1016): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 502
,D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,E/ConnectivityService( 1016): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1016): Setting Dns servers for network 502 to [/192.168.1.1]
D/ConnectivityService( 1016): LTETest block dns file not exists
,I/NearbySettings( 1307): MountReceiver.onReceive - Keep current state
,D/ConnectivityService( 1016): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,E/ConnectivityService( 1016): updateNetworkInfo()
,E/ConnectivityService( 1016): updateNetworkInfo()
,I/WifiTrafficPoller( 1016): evaluateTrafficStatsPolling
,D/ConnectivityService( 1016): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1016): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 1016): rematching NetworkAgentInfo [WIFI () - 502]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1016):    accepting network in place of null
,D/WIFI_P2P( 1016): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/TelephonyNetworkFactory( 1440): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/TelephonyNetworkFactory( 1440): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1016): Setting tx/rx TCP buffers to 524288,1048576,4525824,524288,1048576,4525824
,E/WifiStateMachine( 1016): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/WifiTrafficPoller( 1016): evaluateTrafficStatsPolling
I/WifiTrafficPoller( 1016): mBoosterFLAG : 0
I/WifiTrafficPoller( 1016): current booster mode : FullMode
,E/WifiStateMachine( 1016): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/WifiNative-wlan0( 1016): callSECApiVoid - ID [212]
,D/WIFI    ( 1016): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/CSLegacyTypeTracker( 1016): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1016): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
,D/ConnectivityService( 1016): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/System.out( 1016): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
D/Tethering( 1016): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,D/Tethering( 1016): MasterInitialState.processMessage what=3
I/System.out( 1016): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1016): (HTTPLog)-Static: isShipBuild true
,I/System.out( 1016): (HTTPLog)-Thread-171-174336634: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
V/NetworkStats( 1016): updateIfacesLocked()
V/NetworkStats( 1016): performPollLocked(flags=0x1)
I/System.out( 1016): (HTTPLog)-Static: isSBSettingEnabled false
,D/NetworkStatsFactory( 1016): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1016): UpdateStatsForKnox main else ---
,D/NtpTrustedTime( 1016): forceRefresh() from cache miss
,D/ConnectivityService( 1016): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/EnterpriseController(  278): uids 1000
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 1000
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,D/EnterpriseController(  278): uids 1000
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 1000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/EnterpriseController(  278): uids 1000
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 1000
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/ConnectivityService( 1016): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
,D/NtpTrustedTime( 1016): forceRefresh Fail.
,D/EntConnectivity( 1016): Not allowed due to - mEnabled false - primarySimSlot false
,V/NetworkStats( 1016): performPollLocked() took 9ms
I/Hs20UtilService( 3388): Starting #6
,I/Hs20UtilService( 3388): Message received 5007
,D/StatusBar.NetworkController( 1177): EthernetConnected: false
,D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1177): updateDataNetType()
D/StatusBar.NetworkController( 1177): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1177): updateLTEICONDataNetType:0
,V/NetworkStats( 1016): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1177): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/NtpTrustedTime( 1016): forceRefresh() from cache miss
,D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/NtpTrustedTime( 1016): forceRefresh Fail.
,V/NearbySettings( 1307): DMSUtil.isNetworkConnected - flag-null, state-null
D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1307): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1307): MountReceiver.onReceive - Keep current state
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/Hs20UtilService( 3388): Starting #7
,I/NearbySettings( 1307): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 3388): Message received 5007
,D/WifiStateMachine( 1016): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravityEnabledState
,D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravity
,D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravityXOffset
,D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravityYOffset
,D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 15 selection = getToastShowPackageNameState
,D/SecContentProvider2( 1016): mCursor = null
,I/System.out( 1016): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/SurfaceFlinger(  257): id=13 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 1016): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1016
,D/SRIB_DCS( 1177): log_dcs ThreadedRenderer::initialize entered! 
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 10 Dec 2015 12:36:34 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449750995100], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449750995077]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): Validated
,D/ConnectivityService( 1016): Validated NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 1016): rematching NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 1016): Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
D/ConnectivityService( 1016): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService( 1016): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524290
,E/SMD     (  288): DCD OFF
,D/StatusBar.NetworkController( 1177): EthernetConnected: false
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): 0,
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1177): updateDataNetType()
,D/StatusBar.NetworkController( 1177): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1177): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1177): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/ConnectivityService( 1016): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/NtpTrustedTime( 1016): forceRefresh() from cache miss
,D/NtpTrustedTime( 1016): forceRefresh Fail.
,I/DBG_DM  ( 2799): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 2799): [com.wssyncmldm.llllIIIllIlIIIIllllI(230/onReceive)] ----------- XEVENT_DM_INIT WIFI ok
,I/DBG_DM  ( 2799): [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,I/PCWCLIENTTRACE_PushUtil( 5070): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5070): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5070): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5070): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1016): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=22
I/splitIntent( 1016): base  index=22, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1016): other index=24, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1016): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5701): MountEmulatedStorage()
E/Zygote  ( 5701): v2
I/libpersona( 5701): KNOX_SDCARD checking this for 10111
I/libpersona( 5701): KNOX_SDCARD not a persona
,I/ActivityManager( 1016): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=5701 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5701): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 5701): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 5701): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.apps.books/com.google.android.apps.books.service.SyncService; callingUser = 0; userId(target) = 0
,I/DBG_DM  ( 2799): [IlIlllIlllllIlIllllI(403/llIIllllIIlllIIIIlll)] Check completed.
,D/TimaKeyStoreProvider( 5701): TimaSignature is unavailable
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/ActivityThread( 5701): Added TimaKeyStore provider
,I/DBG_DM  ( 2799): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,E/Zygote  ( 5717): MountEmulatedStorage()
,E/Zygote  ( 5717): v2
I/libpersona( 5717): KNOX_SDCARD checking this for 10075
I/libpersona( 5717): KNOX_SDCARD not a persona
,I/SELinux ( 5717): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/ActivityManager( 1016): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=5717 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5717): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 5717): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,I/DBG_DM  ( 2799): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.metadata.sync.syncadapter.SyncAdapterService; callingUser = 0; userId(target) = 0
I/DBG_DM  ( 2799): [IIlIIIlllllIIlIIIlII(91/llllIIIllIlIIIIllllI)] 
,D/ConnectivityService( 1016): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,fe80::7ef9:eff:fe51:1823/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 1016): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 1016): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.gallery3d/com.sec.android.gallery3d.remote.picasa.PicasaService; callingUser = 0; userId(target) = 0
,D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524295
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 2799): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,D/TimaKeyStoreProvider( 5717): TimaSignature is unavailable,
,D/ActivityThread( 5717): Added TimaKeyStore provider
,I/ActivityManager( 1016): Start proc com.sec.android.gallery3d for service com.sec.android.gallery3d/.remote.picasa.PicasaService: pid=5732 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a,
,E/Zygote  ( 5732): MountEmulatedStorage()
E/Zygote  ( 5732): v2
I/libpersona( 5732): KNOX_SDCARD checking this for 10044
I/libpersona( 5732): KNOX_SDCARD not a persona
I/DBG_DM  ( 2799): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 8
,I/SELinux ( 5732): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 5732): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 5732): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 2799): [com.wssyncmldm.db.file.XDB(6236/IlIIlIIlIllllIlllIII)] Initiated Type: 2
,I/DBG_DM  ( 2799): [IlIlllIlllllIlIllllI(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
,I/DBG_DM  ( 2799): [IlIlllIlllllIlIllllI(177/lllIlIlIIIllIIlIllIl)] nDownloadPostpone is [8]
,D/GpsLocationProvider( 1016): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/art     ( 1996): Suspending all threads took: 10.341ms
,D/TimaKeyStoreProvider( 5732): TimaSignature is unavailable
,D/ActivityThread( 5732): Added TimaKeyStore provider
,W/ResourcesManager( 5732): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5732): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/DBG_DM  ( 2799): [com.wssyncmldm.db.file.XDB(5457/lllIIIIllIlIlllllllI)] Set Download Postpone status : 0,
W/ResourcesManager( 5732): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5732): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5732): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
I/DBG_DM  ( 2799): [llllIIIllIllIlllIIlI(772/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
W/ResourcesManager( 5732): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 5732): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5732): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/DBG_DM  ( 2799): [llllIlllIIIlIlIlIIII(49/llIIIIlllllIIllIIllI)] 
,I/DBG_DM  ( 2799): [IlIIlIIlIllllIlllIII(274/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,I/MusicStore( 5701): Database version: 120
I/DBG_DM  ( 2799): [IlIIlIIlIllllIlllIII(1901/llllIIIllIlIIIIllllI)] 
,I/DBG_DM  ( 2799): [com.wssyncmldm.DMSecBroadcastReceiver(572/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
,I/DBG_DM  ( 2799): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(503/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,E/GpsLocationProvider( 1016): No APN found to select.,
,I/DBG_DM  ( 2799): [IIllIIIIlIlIlIlIllII(49/IIIlIIllIlIIllIlllII)] FirmwareObjectSize:387678779
,I/DBG_DM  ( 2799): [IIllIIIIlIlIlIlIllII(1715/llllllIllIlIlllIIlIl)] 
,I/DBG_DM  ( 2799): [com.wssyncmldm.db.file.XDB(5178/IIIIlIllIlllIlIIIIlI)] Data Margin : 500
,I/DBG_DM  ( 2799): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Data App Weight : 0.0
,I/DBG_DM  ( 2799): [com.wssyncmldm.db.file.XDB(5258/llllIIlIlIIIIllIlIIl)] Delta Weight : 0.5
,I/DBG_DM  ( 2799): [com.wssyncmldm.db.file.llllIIIllIlIIIIllllI(194/llIIIIlllllIIllIIllI)] ### Data Margin only: 718127389
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,I/DBG_DM  ( 2799): [com.wssyncmldm.llIIllllIIlllIIIIlll(1125/handleMessage)] event ->220
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/NearbySource( 5732): Nearby Source Create!
,D/NearbyContext( 5732): Nearby Context Create!
,I/DBG_DM  ( 2799): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 2799): [com.wssyncmldm.XDMService(712/lllIIIIllIlIlllllllI)] 
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5732): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource( 5732): Samsung link source created
,I/DBG_DM  ( 2799): [com.wssyncmldm.db.file.XDB(5018/IIllIIllIIIlllIlIIll)] Get Autoinstall status : false
,I/DBG_DM  ( 2799): [llllIIIllIllIlllIIlI(726/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
,I/DBG_DM  ( 2799): [com.wssyncmldm.XDMService(468/lIllIllllIIIlllIlllI)] 
,I/DBG_DM  ( 2799): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : false
,E/DBG_DM  ( 2799): [com.wssyncmldm.XDMService(476/lIllIllllIIIlllIlllI)] didn't register,
,E/DBG_DM  ( 2799): [com.wssyncmldm.XDMService(477/lIllIllllIIIlllIlllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@18ed9b40
,E/Auth.Api.Credentials( 1996): [CredentialSyncAdapter] Unknown sync event.
,I/DBG_DM  ( 2799): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : false
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5701): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/DriveInitializer( 1996): Background init thread started
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/DBG_DM  ( 2799): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,D/ContactProvider( 5732): getAllContactInfoList Start
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ContactProvider( 5732): getAllContactInfoList End
,I/syncContacts( 5732): thread: 978, sync time = 53
,I/DBG_DM  ( 2799): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5701): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0,
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/,
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,I/DBG_DM  ( 2799): [com.wssyncmldm.ui.XUIFotaPostponeActivity(337/llIIIIlllllIIllIIllI)] 
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravityEnabledState
D/SecContentProvider2( 1016): mCursor = null
W/ContextImpl( 5701): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
D/WindowManager( 1016): showStatusBarByNotification() mOpenByNotification=false
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravity
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
D/SecContentProvider2( 1016): mCursor = null
,W/DriveInitializer( 1996): Awaiting to be initialized
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravityXOffset
,D/SecContentProvider2( 1016): mCursor = null
,W/ContextImpl( 1996): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,W/ResourcesManager( 1177): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravityYOffset
D/SecContentProvider2( 1016): mCursor = null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncService; callingUser = 0; userId(target) = 0
I/DBG_DM  ( 2799): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,D/SecContentProvider2( 1016): uri = 15 selection = getToastEnabledState
D/SecContentProvider2( 1016): mCursor = null
,I/DBG_DM  ( 2799): [com.wssyncmldm.db.file.XDB(5457/lllIIIIllIlIlllllllI)] Set Download Postpone status : 8
,I/DBG_DM  ( 2799): [com.wssyncmldm.ui.XUIFotaPostponeActivity(386/llIIIIlllllIIllIIllI)] No idle Postpone
,I/DBG_DM  ( 2799): [com.wssyncmldm.ui.XUIFotaPostponeActivity(474/llIIIIlllllIIllIIllI)] 
,D/KnoxNotification( 1177): ----- inflateViews : modified publicViewLocal -----
,W/ResourcesManager( 5701): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5701): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/KnoxNotification( 1177): ----- inflateViews : modified KnoxViewLocal -----
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PersonaManager( 1177): PersonaID is invalid or persona doesn't exists. : 0
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PanelView( 1177): There is/are notification(s) 
,D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,V/JNIHelp ( 5701): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,W/ActivityThread( 5701): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5701): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3cd6d215: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5701): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5701): GMSCore installation verified
,I/ConfigStore( 5701): Config Database version: 1
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 58531(3MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 27MB/40MB, paused 2.649ms total 172.110ms
,D/SecContentProvider2( 1016): uri = 15 selection = getToastShowPackageNameState
D/SecContentProvider2( 1016): mCursor = null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/GAV2    ( 5717): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/BooksApp( 5717): Created application version: 3.6.9 (30609)
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1016): getStreamVolume 3 index 0
,I/MediaRouter( 5701): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 5701): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,I/art     ( 1725): Explicit concurrent mark sweep GC freed 7750(396KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 10MB/17MB, paused 1.006ms total 44.671ms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/NetworkMonitor( 5701): type=WIFI subType= reason=null isConnected=true
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/DriveInitializer( 1996): Background init thread ended
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/NetworkMonitor( 5701): type=WIFI subType= reason=null isConnected=true
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5788): MountEmulatedStorage(),
I/ActivityManager( 1016): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=5788 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 5788): v2
I/libpersona( 5788): KNOX_SDCARD checking this for 10002
I/libpersona( 5788): KNOX_SDCARD not a persona
,I/SELinux ( 5788): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 5788): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 5788): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/GHttpClientFactory( 5701): Using our fixed implementation of GMSCore's GoogleHttpClient
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 5788): TimaSignature is unavailable
,D/ActivityThread( 5788): Added TimaKeyStore provider
,I/GoogleURLConnFactory( 5701): Using platform SSLCertificateSocketFactory
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/BooksSync( 5717): Starting books sync for 61035162, extras: ade
,I/ActivityManager( 1016): Killing 5004:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,W/libprocessgroup( 1016): failed to open /acct/uid_10100/pid_5004/cgroup.procs: No such file or directory
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1016): Killing 5034:com.google.android.apps.docs/u0a91 (adj 15): empty #31
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5810): MountEmulatedStorage(),
I/ActivityManager( 1016): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=5810 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/Zygote  ( 5810): v2
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
I/libpersona( 5810): KNOX_SDCARD checking this for 1000
I/libpersona( 5810): KNOX_SDCARD not a persona
,I/SELinux ( 5810): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/SELinux ( 5810): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 5810): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 5810): TimaSignature is unavailable
,D/ActivityThread( 5810): Added TimaKeyStore provider
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DIAGMON_AGENT( 5810): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.gallery3d/com.sec.android.gallery3d.remote.picasa.PicasaService; callingUser = 0; userId(target) = 0
,W/libprocessgroup( 1016): failed to open /acct/uid_10091/pid_5034/cgroup.procs: No such file or directory
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/PicasaService( 5732): start picasa sync
,D/PicasaService( 5732): end picasa sync
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.metadata.sync.syncadapter.SyncAdapterService; callingUser = 0; userId(target) = 0
,E/SQLiteLog( 5717): (284) automatic index on view_volumes(volume_id)
,I/DIAGMON_AGENT( 5810): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 5810): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/BooksConfig( 5717): GmsCore Version = 7.8.99 (2134222-436)
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.sync.FitnessSyncAdapterService; callingUser = 0; userId(target) = 0
,I/DIAGMON_AGENT( 5810): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 5810): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 5810): ./extraInfo: "NG700"
,I/DIAGMON_AGENT( 5810): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/PackageManager( 1016): [MSG] MCS_UNBIND
,I/ActivityManager( 1016): Killing 4990:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 5085): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5085): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5085): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/DBG_POLICYDM( 5085): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5085): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5085): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/GLSUser ( 1725): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1725): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1725): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1725): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0,
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5837): MountEmulatedStorage()
,E/Zygote  ( 5837): v2
I/libpersona( 5837): KNOX_SDCARD checking this for 10009
I/libpersona( 5837): KNOX_SDCARD not a persona
,I/SELinux ( 5837): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 5837): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
I/ActivityManager( 1016): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=5837 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 5837): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 5837): TimaSignature is unavailable
,D/ActivityThread( 5837): Added TimaKeyStore provider
,W/libprocessgroup( 1016): failed to open /acct/uid_10015/pid_4990/cgroup.procs: No such file or directory
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/WindowManager( 1016): showStatusBarByNotification() mOpenByNotification=false
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/ResourcesManager( 1177): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1177): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/KnoxNotification( 1177): ----- inflateViews : modified publicViewLocal -----
,D/KnoxNotification( 1177): ----- inflateViews : modified KnoxViewLocal -----
,I/GLSUser ( 1725): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1725): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1725): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1725): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/PersonaManager( 1177): PersonaID is invalid or persona doesn't exists. : 0
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
D/PersonaManager( 1177): isKioskContainerExistOnDevice
,V/GLSActivity( 1725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 5717): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,I/ActivityManager( 1016): Killing 5051:com.samsung.helphub/1000 (adj 15): empty #31
,I/FOTA_Client( 5837): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,E/BooksSync( 5717): Soft error
E/BooksSync( 5717): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5717): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 5717): Sync error
E/BooksSync( 5717): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5717): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 5717): Finished books sync
,W/FOTA_Client( 5837): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,I/ActivityManager( 1016): Killing 4686:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31
,I/KLMS-2.5.183: ( 3443): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Dec 10 13:36:37 GMT+01:00 2015
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.183: ( 3443): KLMSAbstractReciever(): onReceive().END.
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.183: ( 3443): KLMSIntentService(): onCreate()
,I/KLMS-2.5.183: ( 3443): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/Zygote  ( 5855): MountEmulatedStorage(),
E/Zygote  ( 5855): v2
I/libpersona( 5855): KNOX_SDCARD checking this for 10034,
I/SELinux ( 5855): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/libpersona( 5855): KNOX_SDCARD not a persona
,I/SELinux ( 5855): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/KLMS-2.5.183: ( 3443): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
E/SELinux ( 5855): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=5855 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a,
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,E/SQLiteLog( 1725): (10) POSIX Error : 11 SQLite Error : 3850
,I/KLMS-2.5.183: ( 3443): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.183: ( 3443): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.183: ( 3443): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.183: ( 3443): StateImplV2(): networkChangeListener().START
,I/art     (  305): Explicit concurrent mark sweep GC freed 8724(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 737us total 25.513ms
,I/KLMS-2.5.183: ( 3443): NetworkChangeOperations(): uploadRequestLog().START 
,D/TimaKeyStoreProvider( 5855): TimaSignature is unavailable
,D/ActivityThread( 5855): Added TimaKeyStore provider
,I/KLMS-2.5.183: ( 3443): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.5.183: ( 3443): StateImplV2(): networkChangeListener().END
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 635us total 16.986ms
,I/KLMS-2.5.183: ( 3443): KLMSIntentService(): onDestroy()
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 604us total 16.788ms
,I/DBG_POLICYDM( 5085): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE,
,I/DBG_POLICYDM( 5085): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5085): [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
,E/DBG_POLICYDM( 5085): [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,E/DBG_POLICYDM( 5085): [com.policydm.XDMBroadcastReceiver(240/xdmNotInitSetResume)] DM Not Init
,I/DBG_POLICYDM( 5085): [com.policydm.XDMApplication(246/xdmInitializing)] ----------- XEVENT_DM_INIT WIFI ok
,I/SA      ( 5326): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
,I/SA      ( 5326): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 5326): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/DBG_POLICYDM( 5085): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,I/SA      ( 5326): [SLFUCHKMGR] constructor called
,I/DBG_POLICYDM( 5085): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/SA      ( 5326): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5326): [OR] == isSIMCardReady false ==
,I/SA      ( 5326): [SCU] == networkStateCheck == true
,I/DBG_POLICYDM( 5085): [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
I/SA      ( 5326): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5326): isChinaCountryCode : false
I/SA      ( 5326): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 5326): [OR] == networkStateCheck true ==
,I/DBG_POLICYDM( 5085): [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
,I/SA      ( 5326): [OR] GetMyCountryZoneTask
,I/SA      ( 5326): [OR] onReceive END
,I/DBG_POLICYDM( 5085): [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
,I/ActivityManager( 1016): Killing 5122:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,V/DownloadManager( 1229): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/SA      ( 5326): [SRS] prepareGetMyCountryZone
,D/accuweather( 1554): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/SA      ( 5326): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5326): [SSP] query invoked
I/DBG_POLICYDM( 5085): [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
,D/daemonapp( 1285): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,D/accuweather( 1554): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1554): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1554): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1554): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/SecContentProvider2( 1016): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1016): mCursor = null
,D/accuweather( 1554): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5085): [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
D/accuweather( 1554): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/SA      ( 5326): [TPMU] GetMccFromDB : null
,I/SA      ( 5326): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5326): [TPM] isNoProxy(default) : true
,I/DBG_POLICYDM( 5085): [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
,I/DBG_POLICYDM( 5085): [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
I/DBG_POLICYDM( 5085): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,E/Zygote  ( 5882): MountEmulatedStorage()
,E/Zygote  ( 5882): v2
I/libpersona( 5882): KNOX_SDCARD checking this for 10125
I/libpersona( 5882): KNOX_SDCARD not a persona
,I/SELinux ( 5882): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/DBG_POLICYDM( 5085): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/DBG_POLICYDM( 5085): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,I/SELinux ( 5882): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
I/DBG_POLICYDM( 5085): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,E/SELinux ( 5882): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/DBG_POLICYDM( 5085): [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
I/ActivityManager( 1016): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=5882 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
I/DBG_POLICYDM( 5085): [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
,D/SyncManager( 1016): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 22638, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/DBG_POLICYDM( 5085): [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
,I/DBG_POLICYDM( 5085): [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,I/ActivityManager( 1016): Killing 4755:com.android.vending/u0a28 (adj 15): empty #31
,I/ActivityManager( 1016): Killing 5155:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #32
,E/File    ( 5326): fail readDirectory() errno=2
,D/TimaKeyStoreProvider( 5882): TimaSignature is unavailable
,D/ActivityThread( 5882): Added TimaKeyStore provider
,I/DBG_POLICYDM( 5085): [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
,I/DBG_POLICYDM( 5085): [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
,I/DBG_POLICYDM( 5085): [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,I/DBG_POLICYDM( 5085): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2015/12/15/15:15:43
,I/DBG_POLICYDM( 5085): [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2015/12/10/13:36:37
,I/DBG_POLICYDM( 5085): [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
,I/DBG_POLICYDM( 5085): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
,W/ResourcesManager( 5882): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5882): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 5882): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/DBG_POLICYDM( 5085): [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
,D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1016): mCursor = null
,I/DBG_POLICYDM( 5085): [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
,D/QuickConnect( 5882): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 5882): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 5882): PeriphStartReceiver.onReceive - no need to start
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_5051/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10032/pid_4686/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10152/pid_5122/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10028/pid_4755/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 5085): [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,W/libprocessgroup( 1016): failed to open /acct/uid_10156/pid_5155/cgroup.procs: No such file or directory
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/SecurityLogAgent( 5549): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 5549): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5549): StateMachine : Current State = 1
,D/SecurityLogAgent( 5549): StateMachine : Changed Current State = 1
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5897): MountEmulatedStorage()
,E/Zygote  ( 5897): v2
I/libpersona( 5897): KNOX_SDCARD checking this for 10159
I/libpersona( 5897): KNOX_SDCARD not a persona
,I/SELinux ( 5897): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1016): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=5897 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 4211:com.google.android.gms.wearable/u0a12 (adj 15): empty #31
,I/SELinux ( 5897): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 5897): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5897): TimaSignature is unavailable
,D/ActivityThread( 5897): Added TimaKeyStore provider
,I/DBG_POLICYDM( 5085): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
,I/DBG_POLICYDM( 5085): [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,I/DBG_POLICYDM( 5085): [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
,I/ActivityManager( 1016): Killing 5020:com.android.mms/u0a46 (adj 15): empty #31
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 5085): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10012
,I/DBG_POLICYDM( 5085): [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
,W/libprocessgroup( 1016): failed to open /acct/uid_10012/pid_4211/cgroup.procs: No such file or directory
,D/CountryDetector( 1016): No listener is left
,I/iu.SyncManager( 1996): SYNC; picasa accounts
,D/NetworkLogImpl( 1996): Loaded NetworkSpeedPredictor
,W/libprocessgroup( 1016): failed to open /acct/uid_10046/pid_5020/cgroup.procs: No such file or directory
,I/iu.Environment( 1996): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/iu.UploadsManager( 1996): num queued entries: 0
,I/iu.UploadsManager( 1996): num updated entries: 0
,I/iu.SyncManager( 1996): NEXT; no task
,D/ChimeraCfgMgr( 1996): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/ChimeraCfgMgr( 1996): Loading module com.google.android.gms.kids from APK com.google.android.gms
,E/Zygote  ( 5920): MountEmulatedStorage(),
E/Zygote  ( 5920): v2
I/libpersona( 5920): KNOX_SDCARD checking this for 10104
I/libpersona( 5920): KNOX_SDCARD not a persona
,I/SELinux ( 5920): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1016): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5920 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/SELinux ( 5920): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 5920): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5920): TimaSignature is unavailable
,D/ActivityThread( 5920): Added TimaKeyStore provider
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 27925(1333KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/40MB, paused 2.542ms total 150.611ms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1725): Connected
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 5920): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/GCM     ( 1725): Message class com.google.f.a.a.p
,E/SMD     (  288): DCD OFF
,I/GLSUser ( 1725): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1725): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1725): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1725): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/art     ( 5326): Suspending all threads took: 5.650ms
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PanelView( 1177): There is/are notification(s) 
,D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,W/Kids    ( 1996): [AccountUtils] Account not ready
W/Kids    ( 1996): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1996): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1996): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1996): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1996): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1996): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1996): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1996): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1996): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1996): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1996): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1996): 	at java.lang.Thread.run(Thread.java:818)
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/dhcpcd  ( 5659): wlan0: sending IPv6 Router Solicitation
,I/Babel_SMS( 5920): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 5920): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5920): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,I/Babel_SMS( 5920): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5920): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 5920): MmsConfig.loadFromResources
,E/Babel_SMS( 5920): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 5920): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,I/SA      ( 5326): [RC New] Execute method=[GET] start
,I/SA      ( 5326): [RC New] Security=[true]
,W/QCamera2Factory(  283): getCameraInfo: E, camera_id = 0
,W/QCamera2Factory(  283): getCameraInfo: X
,W/QCamera2Factory(  283): getCameraInfo: E, camera_id = 1
,W/QCamera2Factory(  283): getCameraInfo: X
I/System.out( 5326): Thread-915(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5326): Thread-915(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5326): Thread-915(ApacheHTTPLog):isShipBuild true
I/System.out( 5326): Thread-915(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5326): Thread-915(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/EnterpriseController(  278): uids 10041
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10041
,W/Settings( 5920): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5920): startup - clean
,I/Babel   ( 5920): deleted: false for 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5948): MountEmulatedStorage(),
E/Zygote  ( 5948): v2
I/libpersona( 5948): KNOX_SDCARD checking this for 10035
I/libpersona( 5948): KNOX_SDCARD not a persona
,I/SELinux ( 5948): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1016): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=5948 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5948): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 5948): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,W/VideoCapabilities( 5920): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 5920): Unsupported mime audio/evrc
,W/AudioCapabilities( 5920): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5920): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 5920): Unsupported mime audio/mpeg-L2
,D/TimaKeyStoreProvider( 5948): TimaSignature is unavailable
,D/ActivityThread( 5948): Added TimaKeyStore provider
,I/SurfaceFlinger(  257): id=13 Removed Uoast (8/9)
,W/AudioCapabilities( 5920): Unsupported mime audio/x-ms-wma
,D/PowerManagerService( 1016): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1016) eventTime = 85793
,D/PowerManagerService( 1016): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1016 (0x0)
D/PowerManagerService( 1016): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1016, ws=WorkSource{10054}) (elapsedTime=3488)
,W/AudioCapabilities( 5920): Unsupported mime audio/x-ima
,W/AudioCapabilities( 5920): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5920): Unsupported mime audio/evrc
,D/OpenGLRenderer( 2799): Render dirty regions requested: true
,I/SurfaceFlinger(  257): id=14 createSurf (1x1),1 flag=4, Uoast
,W/VideoCapabilities( 5920): Unsupported mime video/wvc1
,W/VideoCapabilities( 5920): Unsupported mime video/x-ms-wmv
,D/PowerManagerService( 1016): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1016
,W/VideoCapabilities( 5920): Unrecognized profile/level 32768/2 for video/mp4v-es
W/VideoCapabilities( 5920): Unsupported mime video/wvc1
W/VideoCapabilities( 5920): Unsupported mime video/x-ms-wmv
W/VideoCapabilities( 5920): Unsupported mime video/x-ms-wmv7
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4142, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,W/VideoCapabilities( 5920): Unsupported mime video/x-ms-wmv8
,D/SRIB_DCS( 2799): log_dcs ThreadedRenderer::initialize entered! 
,W/VideoCapabilities( 5920): Unsupported mime video/mp43
,I/Adreno-EGL( 2799): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 2799): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 2799): Build Date: 04/06/15 Mon
I/Adreno-EGL( 2799): Local Branch: 
I/Adreno-EGL( 2799): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 2799): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 2799):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,I/OpenGLRenderer( 2799): Initialized EGL, version 1.4
,W/VideoCapabilities( 5920): Unsupported mime video/sorenson
,E/SPPClientService( 5948): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
E/SPPClientService( 5948): [SystemStateMoniter] Current Time : 85896
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1405): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1405): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,E/SPPClientService( 5948): [SystemStateMoniter] No Connect : false
,E/SPPClientService( 5948): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 5948): [PushClientApplication] Push log off : This is Ship build version
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,V/HeadsetService( 5468): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/OpenGLRenderer( 2799): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 2799): Enabling debug mode 0
D/HeadsetStateMachine( 5468): Disconnected process message: 10
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/VideoCapabilities( 5920): Unsupported mime video/mp4v-esdp
,D/SPPClientService( 5948): PushLog.txt file is not deleted.
D/SPPClientService( 5948): PushLog.txt file is not deleted.
D/SPPClientService( 5948): ============PushLog. stop!
,I/ActivityManager( 1016): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5967 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 5967): MountEmulatedStorage()
E/Zygote  ( 5967): v2
I/libpersona( 5967): KNOX_SDCARD checking this for 10113
I/libpersona( 5967): KNOX_SDCARD not a persona
,I/ActivityManager( 1016): Killing 5196:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,I/SELinux ( 5967): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 5967): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 5967): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/VideoCapabilities( 5920): Unsupported profile 4 for video/mp4v-es
,D/TimaKeyStoreProvider( 5967): TimaSignature is unavailable
,D/ActivityThread( 5967): Added TimaKeyStore provider
,D/btif_config_util( 5468): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/VideoCapabilities( 5920): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5920): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5920): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5920): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 5920): onServiceConnected
,W/Babel   ( 5920): Attempted to change video mute state without an active call.
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 5920): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 5920): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 5920): (HTTPLog)-Static: isShipBuild true
I/System.out( 5920): (HTTPLog)-Thread-1021-64130576: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 5920): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): uids 10104
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10104
,I/System.out( 5920): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/Babel   ( 5920): connection state changed from UNKNOWN to CONNECTED
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,I/ActivityManager( 1016): Killing 5257:com.wsomacp/u0a25 (adj 15): empty #31
,W/ContextImpl( 5967): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 5967): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5967):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5967):   adb logcat -s GAv4
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5967): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5967): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5967): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 5967): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup( 1016): failed to open /acct/uid_10047/pid_5196/cgroup.procs: No such file or directory
,W/GAv4    ( 5967): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5967): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup( 1016): failed to open /acct/uid_10025/pid_5257/cgroup.procs: No such file or directory
,I/SA      ( 5326): [RC New] [v2liruge] api execute + 694
,I/SA      ( 5326): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5326): AsyncTask #1 calls detatch()
,I/SA      ( 5326): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 5326): [OCP] update openData : PL
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/SA      ( 5326): [TPMU] getNetworkMcc : 
I/SA      ( 5326): [SCU] saveMccToPreferece Start
I/SA      ( 5326): [SCU] RegionMCC : 260
I/SA      ( 5326): [SSP] query invoked
,I/SA      ( 5326): [TPMU] GetMccFromDB : null,
I/SA      ( 5326): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5326): [SCU] saveMccToPreferece End
I/SA      ( 5326): [RC New] executeRequest [v2liruge] end. 763
,I/SA      ( 5326): [RC New] Execute end
I/SA      ( 5326): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 5326): [OR] GetMyCountryZoneTask Success
,I/WebViewFactory( 5967): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,I/LibraryLoader( 5967): Time to load native libraries: 2 ms (timestamps 6364-6366)
I/LibraryLoader( 5967): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5967): Binding Chromium to main looper Looper (main, tid 1) {20f9a6c3}
,I/LibraryLoader( 5967): Expected native library version number "",actual native library version number ""
,I/chromium( 5967): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5967): Initializing chromium process, singleProcess=true
,W/art     ( 5967): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5967): ApplicationContext is null in ApplicationStatus
,W/chromium( 5967): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5967): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 5967): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5967): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5967): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5967): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5967): Local Branch: 
I/Adreno-EGL( 5967): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5967): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5967):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/NSApplication( 5967): Starting up...
,W/AudioManagerAndroid( 5967): Requires BLUETOOTH permission
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6027): MountEmulatedStorage(),
E/Zygote  ( 6027): v2
I/libpersona( 6027): KNOX_SDCARD checking this for 10081
I/libpersona( 6027): KNOX_SDCARD not a persona
,I/SELinux ( 6027): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1016): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6027 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 5238:com.sec.android.app.soundalive/u0a53 (adj 15): empty #31
I/SELinux ( 6027): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6027): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6027): TimaSignature is unavailable
,D/ActivityThread( 6027): Added TimaKeyStore provider
,E/SQLiteLog( 1725): (10) POSIX Error : 11 SQLite Error : 3850
,W/libprocessgroup( 1016): failed to open /acct/uid_10053/pid_5238/cgroup.procs: No such file or directory
,D/WaitQueueForNetworkActivate( 5411): notifyNetworkActivated
,W/ContextImpl( 5411): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/hcjo    ( 5411): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5411): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 5411): exit::IDLE
D/InitializeManagerStateMachine( 5411): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5411): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5411): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5411): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5411): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5411): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5411): entry::SUCCESS
D/hcjo    ( 5411): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5411): AutoUpdateTriggerManager:IDLE:setInterval:345600000
,D/hcjo    ( 5411): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 5411): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5411): exit::SUCCESS
,D/InitializeManagerStateMachine( 5411): entry::IDLE
,I/ActivityManager( 1016): Killing 5282:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_5282/cgroup.procs: No such file or directory
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5070): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5070): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5070): [GetString-S]
,I/ReactiveServiceManager( 5070): Supported : 1
,D/QSEECOMAPI: ( 1016): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 1016): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1016): Loaded image: APP id = 10
,D/QSEECOMAPI: ( 1016): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 1016): QSEECom_shutdown_app, app_id = 10
E/terrier ( 1016): handleString: Failed to handle string(-4)
,E/terrier ( 1016): Java_com_android_server_ReactiveService_GetString: error code = [-4]
D/PCWCLIENTTRACE_SecurePreferencesJNI( 5070): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5070): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5070): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5070): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5070): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 5070): [ensureRegistration] - No Samsung account
,I/DBG_POLICYDM( 5085): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5085): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5085): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5085): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5085): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5085): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5085): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5085): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/DBG_POLICYDM( 5085): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,I/DBG_POLICYDM( 5085): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,E/DBG_POLICYDM( 5085): [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
,I/DBG_POLICYDM( 5085): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5085): [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
,E/SMD     (  288): DCD OFF
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,I/GAV2    ( 5717): Thread[GAThread,5,main]: No campaign data found.
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/ActivityManager( 1016): Waited long enough for: ServiceRecord{24809388 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6057): MountEmulatedStorage()
E/Zygote  ( 6057): v2
I/libpersona( 6057): KNOX_SDCARD checking this for 10012
I/libpersona( 6057): KNOX_SDCARD not a persona
,I/SELinux ( 6057): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/ActivityManager( 1016): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=6057 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
I/SELinux ( 6057): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
E/SELinux ( 6057): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
I/MusicLeanback( 5701): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 5701): Stop autocaching.
,D/TimaKeyStoreProvider( 6057): TimaSignature is unavailable,
D/ActivityThread( 6057): Added TimaKeyStore provider
,W/ResourcesManager( 6057): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6057): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6057): VM with version 2.1.0 has multidex support
,I/MultiDex( 6057): install
I/MultiDex( 6057): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6057): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 6057): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6057): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@36725de6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6057): Installed default security provider GmsCore_OpenSSL
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1016): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,I/splitIntent( 1016): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
I/splitIntent( 1016): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
I/splitIntent( 1016): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,D/GCM     ( 1725): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1725): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GmsCoreStatsServiceLauncher( 1996): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 6057): callingUid 10012, callindPid: 6057
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1683): [180] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/GmsUtils( 5701): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 5701): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1996): Restart initialization of location
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/SurfaceFlinger(  257): id=14 Removed Uoast (8/9)
,I/SurfaceFlinger(  257): id=14 Removed Uoast (-2/9)
,D/PowerManagerService( 1016): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1016) eventTime = 89292
,D/PowerManagerService( 1016): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1016 (0x0)
D/PowerManagerService( 1016): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1016, ws=WorkSource{1000}) (elapsedTime=3438)
,I/dhcpcd  ( 5659): wlan0: sending IPv6 Router Solicitation
,I/jxcore-log( 5366): Test app app.js loaded
I/jxcore-log( 5366): 
,I/chromium( 5366): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 380
,I/dhcpcd  ( 5659): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 5659): wlan0: no IPv6 Routers available
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.android.vending
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6087): MountEmulatedStorage(),
E/Zygote  ( 6087): v2
,I/libpersona( 6087): KNOX_SDCARD checking this for 10028
I/libpersona( 6087): KNOX_SDCARD not a persona
,I/SELinux ( 6087): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1016): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentFiltersService: pid=6087 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6087): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 6087): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6087): TimaSignature is unavailable
,D/ActivityThread( 6087): Added TimaKeyStore provider
,V/AlarmManager( 1016): waitForAlarm result :4
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/Finsky  ( 6087): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/ActivityManager( 1016): Killing 5305:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,D/Finsky  ( 6087): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_5305/cgroup.procs: No such file or directory
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6121): MountEmulatedStorage(),
E/Zygote  ( 6121): v2,
I/libpersona( 6121): KNOX_SDCARD checking this for 10012,
I/ActivityManager( 1016): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6121 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
I/libpersona( 6121): KNOX_SDCARD not a persona
,I/SELinux ( 6121): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6121): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6121): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/Settings( 6087): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6087): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/TimaKeyStoreProvider( 6121): TimaSignature is unavailable
,D/ActivityThread( 6121): Added TimaKeyStore provider
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ResourcesManager( 6121): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6121): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6121): VM with version 2.1.0 has multidex support
I/MultiDex( 6121): install
I/MultiDex( 6121): VM has multidex support, MultiDex support library is disabled.
,D/Finsky  ( 6087): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6087): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 6087): [1035] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,D/Finsky  ( 6087): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,V/JNIHelp ( 6121): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6087): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityThread( 6121): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6121): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@36725de6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6121): Installed default security provider GmsCore_OpenSSL
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1016): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1016): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
D/GCM     ( 1725): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/splitIntent( 1016): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
I/splitIntent( 1016): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1725): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1725): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1725): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1725): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1725): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GmsCoreStatsServiceLauncher( 1996): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6087): [1035] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SMD     (  288): DCD OFF
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 6057): callingUid 10012, callindPid: 6057
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1683): [181] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1996): Restart initialization of location
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     ( 1725): Explicit concurrent mark sweep GC freed 16498(952KB) AllocSpace objects, 8(248KB) LOS objects, 40% free, 10MB/17MB, paused 1.087ms total 48.799ms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1725): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1725): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1725): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1725): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 27417(1429KB) AllocSpace objects, 5(100KB) LOS objects, 33% free, 27MB/40MB, paused 6.394ms total 152.344ms
,D/Finsky  ( 6087): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,V/Finsky  ( 6087): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,D/Finsky  ( 6087): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6087): [1] 5.onFinished: Scheduling replication attempt 2.
,I/ActivityManager( 1016): Killing 5139:com.samsung.android.sdk.samsunglink/u0a38 (adj 15): empty #31
,W/libprocessgroup( 1016): failed to open /acct/uid_10038/pid_5139/cgroup.procs: No such file or directory
,V/AlarmManager( 1016): waitForAlarm result :4
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.DailyHygiene; callingUser = 0; userId(target) = 0
,D/Finsky  ( 6087): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1725): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1725): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1725): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1725): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Finsky  ( 6087): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1725): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1725): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1725): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1725): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1725): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1725): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1725): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1725): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Finsky  ( 6087): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1725): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1725): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1725): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1725): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Finsky  ( 6087): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6087): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6087): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6087): [1] DailyHygiene.reschedule: Scheduling new run in 31 minutes (failures=2)
,D/DeviceConnectionService( 1683): client connected with version: 7571000
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4225, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 1016): stay LED for charging
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate,
V/EmergencyMode( 1405): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1405): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 5468): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5468): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.preloadupdate.PreloadUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 5411): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5411): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5411): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5411): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 5411): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5411): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5411): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 5411): entry::IDLE
,E/SMD     (  288): DCD OFF
,I/ActivityManager( 1016): Killing 5336:com.sec.knox.bridge/1000 (adj 15): empty #31
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_5336/cgroup.procs: No such file or directory
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 340
,I/PowerManagerService( 1016): [PWL] Off : 50s ago
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4236, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1405): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1405): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5468): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5468): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  288): DCD OFF
,D/FactoryTest( 4654): Not factory mode
,D/FactoryTest( 4654): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 4654): DRIVER_TIME_OUT 60s lapsed,
D/MTPRx   ( 4654): still no open session command from host, so toast
,W/ContextImpl( 4654): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 4654): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,I/Timeline( 4654): Timeline: Activity_launch_request id:com.android.settings time:106755
,E/PersonaManagerService( 1016): inState():  stateMachine is null !!
,I/PersonaManagerService( 1016): PersonaId don't exist
I/ActivityManager( 1016): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.android.settings
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings,
W/ActivityManager( 1016): mDVFSHelper.acquire(),
,D/PersonaManager( 1016): isKioskContainerExistOnDevice
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/InputDispatcher( 1016): Focused application set to: xxxx
,D/InputDispatcher( 1016): Focus left window: 5366
,E/MTPRx   ( 4654): started activity for popup
,D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
,W/ResourcesManager( 4654): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 4654): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 4654): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4654): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4654): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4654): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 4654): PREF_DONT_ASK_AGAIN : true
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.android.settings
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1016): Focused application set to: xxxx
,D/InputDispatcher( 1016): Focus entered window: 5366
,D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
,D/InputMethodManagerService( 1016): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/InputMethodManagerService( 1016): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@9ecd7c1 attribute=null, token = android.os.BinderProxy@2b92a99a
,D/SettingsReceiverActivity( 4654): dev.kiessupport is : TRUE
,D/PhoneWindow( 4654): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 4654): *FMB* installDecor flags : 8388610
,D/ActivityManager( 1016): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1016): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1016): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1016): handleActiveUserChange for user 0
D/PersonaManagerService( 1016): getPersonasForUser(): returning null!
,D/PersonaManager( 1016): isKioskContainerExistOnDevice
,V/ActivityThread( 5366): updateVisibility : ActivityRecord{2667c629 token=android.os.BinderProxy@15ca6ef3 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/Timeline( 5366): Timeline: Activity_idle id: android.os.BinderProxy@15ca6ef3 time:106936
,V/AlarmManager( 1016): waitForAlarm result :8
,E/Watchdog( 1016): !@Sync 3
,I/Atfwd_Sendcmd(  315): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  315): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  288): DCD OFF
,W/ActivityManager( 1016): mDVFSHelper.release()
,D/SSRM:n  ( 1016): SIOP:: AP = 330,
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :4
,V/AlarmManager( 1016): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManagerEXT( 1016): <AppSync3 Whitelist>
,V/AlarmManagerEXT( 1016): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,V/AlarmManager( 1016): waitForAlarm result :4
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1725): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1725): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1725): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1725): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms,
,D/Finsky  ( 6087): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6087): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6087): [1] 5.onFinished: Scheduling replication attempt 3.
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4238, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): stay LED for charging
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1405): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1405): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5468): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5468): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 320
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4242, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 1016): stay LED for charging
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1405): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1405): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5468): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5468): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1016): [PWL] Off : 75s ago,
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 310
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 1016): waitForAlarm result :4
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1725): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1725): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1725): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1725): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6087): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6087): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6087): [1] 5.onFinished: Scheduling replication attempt 4.
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4240, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged,
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1405): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1405): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5468): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5468): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1016): !@Sync 4,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1016): SIOP:: AP = 300
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,V/AlarmManager( 1016): waitForAlarm result :4,
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.apps.books/com.google.android.apps.books.service.SyncService; callingUser = 0; userId(target) = 0
,I/BooksSync( 5717): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 5717): GmsCore Version = 7.8.99 (2134222-436)
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1725): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1725): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1725): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1725): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 3
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
D/PanelView( 1177): There is/are notification(s) 
,D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1725): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1725): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1725): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1725): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 5717): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 5717): Soft error
E/BooksSync( 5717): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5717): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 5717): Sync error
E/BooksSync( 5717): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5717): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 5717): Finished books sync
,D/SyncManager( 1016): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 117723, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1016): mCursor = null
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4245, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService( 1016): Plugged
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate,
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
V/EmergencyMode( 1405): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1405): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5468): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 5468): Disconnected process message: 10,
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 300
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4243, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1405): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1405): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5468): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5468): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/PowerManagerService( 1016): [PWL] Off : 105s ago,
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1016): SIOP:: AP = 300
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :4
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/NtpTrustedTime( 1016): forceRefresh() from cache miss
,D/EnterpriseController(  278): uids 1000
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 1000
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.store.VacuumService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.uploader.UploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/VacuumService( 1725): Vacuum at: now=1449751077431 tag=VacuumService
,I/GoogleURLConnFactory( 1725): Using platform SSLCertificateSocketFactory
,W/Uploader( 1725): No account for auth token provided
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1725): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1725): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1725): (HTTPLog)-Static: isShipBuild true
I/System.out( 1725): (HTTPLog)-Thread-207-791623735: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1725): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10012
,I/System.out( 1725): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1725): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1725, getuid(): 10012
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
I/qtaguid ( 1725): Tagging socket 62 with tag 120100000000{4609,0} for uid -1, pid: 1725, getuid(): 10012
,V/GLSActivity( 1725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1725): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1725): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1725): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1725): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6087): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6087): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6087): [1] 5.onFinished: Scheduling replication attempt 5.
,W/Uploader( 1725): No account for auth token provided
,I/System.out( 1725): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1725): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1725, getuid(): 10012
,W/Uploader( 1725):  no longer exists, so no auth token.
,I/System.out( 1725): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1725): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1725, getuid(): 10012
,W/Uploader( 1725): No account for auth token provided
,I/System.out( 1725): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1725): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1725, getuid(): 10012
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 39776(2MB) AllocSpace objects, 31(516KB) LOS objects, 33% free, 27MB/41MB, paused 2.470ms total 176.671ms
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1725): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1725): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1725): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1725): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/Uploader( 1725): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1725): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1725): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1725): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1725): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1725): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1725): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1725): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1725): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1725): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1725): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1725): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1725): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,I/System.out( 1725): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1725): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1725, getuid(): 10012
,W/Uploader( 1725): No account for auth token provided
,I/System.out( 1725): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1725): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1725, getuid(): 10012
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SQLiteLog( 1725): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4245, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate,
,V/EmergencyMode( 1405): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1405): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5468): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5468): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,V/AlarmManager( 1016): waitForAlarm result :8,
,E/Watchdog( 1016): !@Sync 5
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 300
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4243, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1016): Plugged
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
V/EmergencyMode( 1405): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1405): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5468): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5468): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 300,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,D/EnterpriseController(  278): uids 1000
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 1000
,D/NtpTrustedTime( 1016): requestTime Success from server:north-america.pool.ntp.org mCachedNtpTime : 1449751097384 mCachedNtpElapsedRealtime : 184808 mCachedNtpCertainty : 94,
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/AlarmManagerService( 1016): Setting time of day to sec=1449751097
D/AlarmManagerService( 1016): Trying to open a file
,D/AlarmManagerService( 1016): File Open Success
,D/AlarmManagerService( 1016): File Close Success
I/AlarmManagerService( 1016): DRM_TIME_PATH CHMOD 666 for resetState done 
,V/AlarmManager( 1016): waitForAlarm result :65536
W/AlarmManagerService( 1016): Unable to set rtc to 1449751097: Invalid argument
,V/AlarmManager( 1016): No more alarm at this time.nowELAPSED=184832 batch.start=185083
,D/OTPFW   ( 1016): OTPTimeChangeLogger :: TimeChangeListener$onReceive | Device Time Changed. Current time = 1449751097401
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_SET
D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/WifiStateMachine( 1016): android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
,I/DowntimeConditions( 1016): android.intent.action.TIME_SET ignored because schedule turned off.
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_SET
,W/Settings( 1016): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SettingsProvider( 1016): name = lockscreen_zoom_panning_effect
,D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 10054
,D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,D/KeyguardEffectViewUtil( 1177): isStrongPowerSavingMode() :false
,D/KeyguardEffectViewController( 1177): isPreloadedWallpaper=true
,I/GeometricMosaic_Keyguard( 1177): update,
D/KeyguardEffectViewUtil( 1177): getCurrentWallpaper() mWallpaperPath :null
,W/SEC_DRM_PLUGIN_Playready(  282): PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK after: 1449751097 after conversion: 1449751097,
W/SEC_DRM_PLUGIN_Playready(  282): PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK before: 1449751097 after conversion: 1449751097
,I/splitIntent( 1016): Split this intent : android.intent.action.TIME_SET, mSplitNum[0]=7, mSplitNum[1]=12, mSplitNum[2]=17, mBgSplitQueueNum=3 divideNum= 5 r.nextReceiver= 1 receivers.size=23
I/splitIntent( 1016): finish to split intent : android.intent.action.TIME_SET !! Enqueue -> schedule it!!
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6214): MountEmulatedStorage(),
I/libpersona( 6214): KNOX_SDCARD checking this for 10062
E/Zygote  ( 6214): v2
I/libpersona( 6214): KNOX_SDCARD not a persona
,I/SELinux ( 6214): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6214): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 6214): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1016): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=6214 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6225): MountEmulatedStorage()
I/libpersona( 6225): KNOX_SDCARD checking this for 10135
E/Zygote  ( 6225): v2
I/libpersona( 6225): KNOX_SDCARD not a persona
,I/SELinux ( 6225): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1016): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6225 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a,
I/SELinux ( 6225): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6225): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6214): TimaSignature is unavailable
,D/ActivityThread( 6214): Added TimaKeyStore provider
,D/daemonapp( 1285): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1285): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,I/FOTA_Client( 5837): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,D/daemonapp( 1285): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/KeyguardEffectViewUtil( 1177): set current wallpaper info
,I/art     (  305): Explicit concurrent mark sweep GC freed 8691(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 648us total 24.802ms
,D/SettingsProvider( 1016): name = keyguard_current_wallpaper_type
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 10054
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,D/SettingsProvider( 1016): name = keyguard_current_wallpaper_file_path
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 10054
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
D/SettingsProvider( 1016): name = keyguard_current_wallpaper_res_id
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 10054
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,D/TimaKeyStoreProvider( 6225): TimaSignature is unavailable
D/ActivityThread( 6225): Added TimaKeyStore provider
,I/FOTA_Client( 5837): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 610us total 16.747ms
,D/daemonapp( 1285): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/KLMS-2.5.183: ( 3443): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Thu Dec 10 13:38:17 GMT+01:00 2015
,D/daemonapp( 1285): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
D/daemonapp( 1285): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,D/comsamsunglog( 1285): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1285): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1285): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1285): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1285): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
I/KLMS-2.5.183: ( 3443): KLMSAbstractReciever(): onReceive().END.
D/daemonapp( 1285): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 618us total 16.894ms
,D/daemonapp( 1285): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,I/SA      ( 5326): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,D/daemonapp( 1285): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1285): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1285): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1285): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,W/ResourcesManager( 6225): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6225): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6225): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KLMS-2.5.183: ( 3443): KLMSIntentService(): onCreate(),
I/KLMS-2.5.183: ( 3443): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.5.183: ( 3443): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/KLMS-2.5.183: ( 3443): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
I/KLMS-2.5.183: ( 3443): KLMSIntentService(): TIME_CHANGED
,I/KLMS-2.5.183: ( 3443): StateImplV2(): dateTimeChanged().START : Thu Dec 10 13:38:17 GMT+01:00 2015
,E/daemonapp( 1285): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!,
,D/TEST    ( 1177): run!!!
,I/KLMS-2.5.183: ( 3443): StateImplV2(): dateTimeChanged().END
,D/comdaemonstockapp( 1285): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
,D/comdaemonstockapp( 1285): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,I/KLMS-2.5.183: ( 3443): KLMSIntentService(): onDestroy()
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,V/AlarmManager( 1016): waitForAlarm result :4
,I/GeometricMosaic_Renderer( 1177): setBackgroundBitmap
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6250): MountEmulatedStorage()
E/Zygote  ( 6250): v2,
I/libpersona( 6250): KNOX_SDCARD checking this for 10046
I/libpersona( 6250): KNOX_SDCARD not a persona
,I/SELinux ( 6250): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1016): Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=6250 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,I/SELinux ( 6250): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
E/SELinux ( 6250): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/daemonapp( 1285): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/ExternalOEMControlProvider( 6214): onCreate
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/TimaKeyStoreProvider( 6250): TimaSignature is unavailable
,D/ActivityThread( 6250): Added TimaKeyStore provider
,D/accuweather( 1554): [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,D/accuweather( 1554): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/ Time Manager ( 6214): Time Difference not stored. TIME_DIFFERENCE
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6269): MountEmulatedStorage()
E/Zygote  ( 6269): v2
I/libpersona( 6269): KNOX_SDCARD checking this for 10085
I/libpersona( 6269): KNOX_SDCARD not a persona
,I/ActivityManager( 1016): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=6269 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6269): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6269): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
W/ResourcesManager( 6250): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
E/SELinux ( 6269): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ResourcesManager( 6250): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6250): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6250): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6250): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 6250): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 6269): TimaSignature is unavailable
,D/ActivityThread( 6269): Added TimaKeyStore provider
,E/Zygote  ( 6284): MountEmulatedStorage()
I/libpersona( 6284): KNOX_SDCARD checking this for 10042
E/Zygote  ( 6284): v2
I/libpersona( 6284): KNOX_SDCARD not a persona
,I/SELinux ( 6284): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1016): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6284 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6284): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6284): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,D/SecurityLogAgent( 5549): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 5549): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5549): StateMachine : Current State = 1
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 6269): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6269): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6269): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6269): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6269): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6269): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,D/TimaKeyStoreProvider( 6284): TimaSignature is unavailable,
D/ActivityThread( 6284): Added TimaKeyStore provider
,E/Zygote  ( 6300): MountEmulatedStorage(),
E/Zygote  ( 6300): v2
,I/libpersona( 6300): KNOX_SDCARD checking this for 10157
I/libpersona( 6300): KNOX_SDCARD not a persona
,I/SELinux ( 6300): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
I/ActivityManager( 1016): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=6300 uid=10157 gids={50157, 9997} abi=armeabi-v7a
,I/SELinux ( 6300): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6300): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
D/Mms/MmsApp( 6250): [start]    onCreate() consume time = 0.0
,W/ResourcesManager( 6284): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 6300): TimaSignature is unavailable
,D/ActivityThread( 6300): Added TimaKeyStore provider
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/CalendarProvider2( 6284): CalendarProvider2.onCreate() called
,W/ResourcesManager( 6300): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6317): MountEmulatedStorage()
E/Zygote  ( 6317): v2,
I/libpersona( 6317): KNOX_SDCARD checking this for 1000
I/libpersona( 6317): KNOX_SDCARD not a persona
,I/SELinux ( 6317): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1016): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6317 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 6317): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1016): Killing 5388:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,E/SELinux ( 6317): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SettingsProvider( 1016): name = next_alarm_formatted
,D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 10085
,D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,W/art     ( 6250): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 130.621ms
,D/TimaKeyStoreProvider( 6317): TimaSignature is unavailable
,D/ActivityThread( 6317): Added TimaKeyStore provider
,D/TimeService( 6317): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449751098044
D/        ( 6317): TimeServiceNative: User Time to be set is 1449751098044
D/QC-time-services( 6317): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 6317): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 6317): Lib:time_genoff_operation: pargs->ts_val = 1449751098044
,D/QC-time-services( 6317): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  317): Daemon: Connection accepted:time_genoff
,D/QC-time-services(  317): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449751098044
D/QC-time-services(  317): Daemon:genoff_opr: Base = 2, val = 1449751098044, operation = 0
D/QC-time-services(  317): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS5/2/70 3:52:44
,D/QC-time-services(  317): Daemon:Value read from RTC seconds = 13146764000
,D/QC-time-services(  317): Daemon:new time 1449751098044 
D/QC-time-services(  317): Daemon: delta 1436604334044 genoff 1436604334044 
D/QC-time-services(  317): Daemon:genoff_persistent_update: Writing genoff = 1436604334044 to memory
D/QC-time-services(  317): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  317): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  317): Updating the TOD offset
D/QC-time-services(  317): Daemon:genoff_persistent_update: Writing genoff = 1436604334044 to memory
D/QC-time-services(  317): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  317): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,E/QC-time-services(  317): Daemon:Update to modem bit set
D/QC-time-services(  317): Daemon:genoff_send_modem: Sending data to MODEM !
E/QC-time-services( 6317): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
D/QC-time-services(  317): Daemon: Base = 2, Value being sent to MODEM = 1120639534044
,E/QC-time-services(  317): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,E/QC-time-services(  317): Daemon: Time-services: Waiting to acceptconnection
,I/ActivityManager( 1016): Killing 5212:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,D/Mms/ArtClassLoader( 6250): init before art
D/Mms/TelephonyPermission( 6250): start operation mode monitor
,W/ResourcesManager( 6250): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/libprocessgroup( 1016): failed to open /acct/uid_10057/pid_5388/cgroup.procs: No such file or directory
,D/Mms/TelephonyPermission( 6250): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission( 6250): isDefault true
,D/Mms/MmsApp( 6250): onCreate() com.android.mms
,D/Mms/MmsApp( 6250): [start]    initCountryIso consume time = 265.663073
,D/CountryDetector( 1016): The first listener is added
,W/art     ( 6269): Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 123.970ms
,I/rmt_storage(  268): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb83277c8
I/rmt_storage(  268): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  268): wakelock acquired: 1, error no: 42
I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1204651896)
,D/Mms/MmsApp( 6250): [end]    initCountryIso consume time = 10.566354
D/Mms/MmsConfig( 6250): [start]    MmsConfig.init() consume time = 0.116146
,D/Mms/MmsConfig( 6250): before partial update
,D/Mms/MmsConfig( 6250): Load Resize quality : 80
,D/EasySignUpManager_1.0.1( 6250): serviceId : 1, features : -1
,D/EasySignUpManager_1.0.1( 6250): isAuth is false
D/Mms/MmsConfig( 6250): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,W/libprocessgroup( 1016): failed to open /acct/uid_10072/pid_5212/cgroup.procs: No such file or directory
,I/ActivityManager( 1016): Killing 5610:com.samsung.android.app.FileShareClient/u0a68 (adj 15): empty #31
,I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1204651896) wakelock released: 1, error no: 0
I/rmt_storage(  268): 
I/rmt_storage(  268): rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb83277c8
,D/TP/MmsSmsProvider( 1440): query,matched:2117, calling pid = 6250
D/TP/MmsSmsProvider( 1440): match 2117:Elapsed time : 1.025 ms
,D/EasySignUpManager_1.0.1( 6250): isAuth is false
,D/EasySignUpManager_1.0.1( 6250): getServiceStatus : serviceId (1) is OFF
E/CscParser( 6250): mps_code.dat does not exist
,E/CscParser( 6250): customer_path =/system/csc/customer.xml
E/CscParser( 6250): fileName + /system/csc/customer.xml
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/CscParser( 6250): mps_code.dat does not exist
E/CscParser( 6250): customer_path =/system/csc/customer.xml
E/CscParser( 6250): fileName + /system/csc/customer.xml
E/Zygote  ( 6341): MountEmulatedStorage()
E/Zygote  ( 6341): v2
I/libpersona( 6341): KNOX_SDCARD checking this for 10094
I/libpersona( 6341): KNOX_SDCARD not a persona
I/SELinux ( 6341): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6341): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1016): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6341 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
E/SELinux ( 6341): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Killing 5628:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
,D/CscParser( 6250): getInstance fileName =/system/csc/customer.xml
D/Mms/MmsConfig( 6250):  enable multiwindow = true
,E/Mms/MessageUtils( 6250): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 6250): updateCountryIso : update country iso info 
,D/Mms/MmsConfig( 6250): [end]    init() consume time = 120.978333
,D/Mms/Contact( 6250): [start]    init() consume time = 1.526094
,D/TimaKeyStoreProvider( 6341): TimaSignature is unavailable
,D/ActivityThread( 6341): Added TimaKeyStore provider
,D/TP/MmsSmsProvider( 1440): query,matched:13, calling pid = 6250
D/TP/MmsSmsProvider( 1440): match 13:Elapsed time : 1.119 ms
,D/Mms/Contact( 6250): [end]    init consume time = 15.870729
,W/libprocessgroup( 1016): failed to open /acct/uid_10068/pid_5610/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10069/pid_5628/cgroup.procs: No such file or directory
D/Mms/DraftCache( 6250): [start]    rebuildCache consume time = 3.084739
,D/TP/MmsSmsProvider( 1440): query,matched:12, calling pid = 6250
,D/Mms/MethodReflector( 6250): getSubId is called
D/Mms/TelephonyUtils( 6250): getLongSubId from simSlot 0, return Value = -1
D/TP/MmsSmsProvider( 1440): match 12:Elapsed time : 1.925 ms
,D/Mms/MethodReflector( 6250): getTelephonyProperty is called
D/Mms/DownloadManager( 6250): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 6250): [NotificationTransaction] getAutoDownloadState simSlot : 0
,D/Mms/DownloadManager( 6250): auto download without roaming -> true
D/Mms/DownloadManager( 6250): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/MethodReflector( 6250): getSubId is called
,D/Mms/MethodReflector( 6250): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 6250): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 6250): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 6250): getTelephonyProperty is called
D/Mms/DownloadManager( 6250): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 6250): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 6250): auto download without roaming -> true
D/Mms/DownloadManager( 6250): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 6250): auto download during roaming secondary -> false
D/Mms/DownloadManager( 6250): mAutoDownload ------> true
D/Mms/DraftCache( 6250): [end]    rebuildCache consume time = 15.902396
,D/elm:15183( 6341): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:15183( 6341): ELMEngine.ELMEngine( context ).
,D/elm:15183( 6341): MDMBridge.setEnterpriseBridge()
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15183( 6341): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/elm:15183( 6341): ElmAgentService : onCreate()
,D/elm:15183( 6341): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,E/Zygote  ( 6361): MountEmulatedStorage(),
E/Zygote  ( 6361): v2
I/libpersona( 6361): KNOX_SDCARD checking this for 10134
I/libpersona( 6361): KNOX_SDCARD not a persona
,I/SELinux ( 6361): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6361): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,D/elm:15183( 6341): ELMAgentService.listeningToTimeDateChanges( context, intent ).
E/SELinux ( 6361): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL,
D/elm:15183( 6341): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
I/ActivityManager( 1016): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=6361 uid=10134 gids={50134, 9997} abi=armeabi-v7a
D/elm:15183( 6341): ModuleBase.ModifySetAlarm()
D/elm:15183( 6341): MDMBridge.getInstance()
D/elm:15183( 6341): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:15183( 6341): ElmAgentService : onDestroy().
,I/ActivityManager( 1016): Killing 5510:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31,
,D/TimaKeyStoreProvider( 6361): TimaSignature is unavailable
D/ActivityThread( 6361): Added TimaKeyStore provider
,D/ComposerPerformance( 6250): 1449751098362 ms / [DONE] Composer constructor
,E/CII     ( 6250): CommonIMSInterface: VoLTE CSC feature disabled.
,I/Mms/ReservationManager( 6250): ReservationManager()
I/Mms/ReservationManager( 6250): resetAfterConnected()
,D/Mms/ArtClassLoader( 6250): init [DONE] art
,D/Mms/Conversation( 6250): [start]    init() consume time = 78.846302
,D/TP/MmsSmsProvider( 1440): query,matched:7, calling pid = 6250
,D/TP/MmsSmsProvider( 1440): deleteConversation threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1440): match 7:Elapsed time : 2.113 ms
,D/TP/MmsSmsProvider( 1440): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1440): updateThread(), thread_id = 9223372036854775807
,V/TP/MmsSmsDatabaseHelper( 1440): sUpgradeVersion = 0, db.getVersion() = 81
,W/ResourcesManager( 6361): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/Mms/ReservationManager( 6250): getReservedSendMessageCount(): retMessageCount=0
,W/ResourcesManager( 6361): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/TP/MmsSmsProvider( 1440): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1440): need read changed broadcast:false
,D/Mms/MmsApp( 6250): [end]    onCreate() consume time = 14.125834
,D/Mms/Conversation( 6250): [end]    init consume time = 0.61375
,D/Mms/MessagingNotification( 6250): [start]    init() consume time = 1.419166
,D/Mms/DownloadManager( 6250): Service state changed: Bundle[mParcelledData.dataSize=744]
,I/ActivityManager( 1016): Killing 5070:com.sec.pcw.device/1000 (adj 15): empty #31
,D/Mms/DownloadManager( 6250): roaming ------> false, mSimSlot = 0
,D/Mms/MethodReflector( 6250): getSubId is called
D/Mms/TelephonyUtils( 6250): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 6250): getTelephonyProperty is called
D/Mms/MessagingNotification( 6250): [end]    init consume time = 8.563386
D/Mms/DownloadManager( 6250): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 6250): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 6250): auto download without roaming -> true
D/Mms/DownloadManager( 6250): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 6250): mAutoDownload ------> true
,D/Mms/Synchronizer( 6250): [start]    doSync consume time = 1.653229
,D/Mms/SpamFilter( 6250): [start]    SpamFilter fill() begin consume time = 1.643541
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/TP/MmsSmsProvider( 1440): query,matched:0, calling pid = 6250
,V/TP/MmsSmsProvider( 1440): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1440): match 0:Elapsed time : 1.976 ms
,D/TP/MmsSmsProvider( 1440): update, matched:300, calling pid = 6250
V/TP/MmsSmsProvider( 1440): syncDBData start
,V/TP/MmsSmsProvider( 1440): syncDBData sms end
,V/TP/MmsSmsProvider( 1440): syncDBData mms end
I/splitIntent( 1016): Queue : backgroundsplit_0 intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1016): Killing 5788:com.sec.android.cloudagent/u0a2 (adj 15): empty #31
,V/GLSActivity( 1725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TP/MmsSmsProvider( 1440): query,matched:400, calling pid = 6250
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,V/TP/MmsSmsProvider( 1440): syncDBData end
,E/Zygote  ( 6380): MountEmulatedStorage()
I/libpersona( 6380): KNOX_SDCARD checking this for 10072
E/Zygote  ( 6380): v2
I/libpersona( 6380): KNOX_SDCARD not a persona
I/SELinux ( 6380): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6380): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6380): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1016): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6380 uid=10072 gids={50072, 9997} abi=armeabi-v7a
D/Mms/Synchronizer( 6250): [end]    doSync consume time = 36.631198
,D/Mms/SpamFilter( 6250): [end]    SpamFilter fill() finished consume time = 3.602865
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 6380): TimaSignature is unavailable
,D/ActivityThread( 6380): Added TimaKeyStore provider
,I/ActivityManager( 1016): Killing 5810:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1725): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1725): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
D/BadgeProvider( 6380): onCreate
D/BadgeProvider( 6380): DatabaseHelper
,I/GLSUser ( 1725): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1725): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/libprocessgroup( 1016): failed to open /acct/uid_10003/pid_5510/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_5070/cgroup.procs: No such file or directory
,V/GLSActivity( 1725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6087): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6087): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6087): [1] 5.onFinished: Giving up after 6 failures.
,D/Mms/MessagingNotification( 6250): checkBadgeCount unreadCount=0 badgeCount=0
,D/TP/SmsProvider( 1440): query,matched:26, calling pid = 6250
,D/TP/SmsProvider( 1440): match 26:Elapsed time : 1.518 ms
,W/libprocessgroup( 1016): failed to open /acct/uid_10002/pid_5788/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_5810/cgroup.procs: No such file or directory
,I/ActivityManager( 1016): Killing 5732:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,D/TP/MmsSmsProvider( 1440): query,matched:6, calling pid = 6250
,D/TP/MmsSmsProvider( 1440): match 6:Elapsed time : 2.199 ms
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=6395 uid=10025 gids={50025, 9997} abi=armeabi-v7a
,E/Zygote  ( 6395): MountEmulatedStorage()
,E/Zygote  ( 6395): v2
I/libpersona( 6395): KNOX_SDCARD checking this for 10025
I/libpersona( 6395): KNOX_SDCARD not a persona
,I/SELinux ( 6395): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6395): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6395): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6395): TimaSignature is unavailable
,D/ActivityThread( 6395): Added TimaKeyStore provider
,I/ActivityManager( 1016): Killing 4957:com.android.defcontainer/u0a4 (adj 15): empty #31
,W/ResourcesManager( 6395): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,I/OMACP   ( 6395): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,D/Mms/Omacp( 6250): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,I/OMACP   ( 6395): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,I/OMACP   ( 6395): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,I/OMACP   ( 6395): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,I/OMACP   ( 6395): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,I/OMACP   ( 6395): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,I/OMACP   ( 6395): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,I/OMACP   ( 6395): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,I/OMACP   ( 6395): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,I/OMACP   ( 6395): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,I/OMACP   ( 6395): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,I/OMACP   ( 6395): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,I/OMACP   ( 6395): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,I/OMACP   ( 6395): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,W/libprocessgroup( 1016): failed to open /acct/uid_10044/pid_5732/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10004/pid_4957/cgroup.procs: No such file or directory
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/CalendarProvider2( 6284): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4226, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1405): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1405): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5468): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5468): Disconnected process message: 10
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ActivityManager( 1016): Killing 5855:com.sec.android.soagent/u0a34 (adj 15): empty #31
,W/libprocessgroup( 1016): failed to open /acct/uid_10034/pid_5855/cgroup.procs: No such file or directory
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF
,I/Mms/MmsApp( 6250):  start initViewCache mms
D/Mms/ComposeMessageFragment( 6250): [start]    fillCache consume time = 1945.67802
D/Mms/ComposeMessageFragment( 6250): fillCache, easy = false
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 20469(1166KB) AllocSpace objects, 10(180KB) LOS objects, 33% free, 27MB/40MB, paused 2.376ms total 170.346ms
,D/AbsListView( 6250): Get MotionRecognitionManager
,D/MotionRecognitionService( 1016):  ssp status : false
,D/Mms/ComposeMessageFragment( 6250): [end]    fillCache consume time = 234.69974
,D/Mms/BubbleViewCache( 6250): fillCache bubble = 1
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 300,
,I/PowerManagerService( 1016): [PWL] Off : 140s ago,
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1016): waitForAlarm result :4
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4246, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): stay LED for charging,
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
V/EmergencyMode( 1405): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1405): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5468): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5468): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1016): !@Sync 6
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 300
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4247, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1405): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1405): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5468): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5468): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  288): DCD OFF,
,V/AlarmManager( 1016): waitForAlarm result :4
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.apps.books/com.google.android.apps.books.service.SyncService; callingUser = 0; userId(target) = 0
,I/BooksSync( 5717): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 5717): GmsCore Version = 7.8.99 (2134222-436)
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1725): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1725): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1725): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1725): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
D/PersonaManager( 1177): isKioskContainerExistOnDevice
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PanelView( 1177): There is/are notification(s) 
,D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/art     ( 1725): Explicit concurrent mark sweep GC freed 55497(2MB) AllocSpace objects, 47(2MB) LOS objects, 40% free, 10MB/17MB, paused 1.399ms total 63.284ms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1725): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1725): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1725): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1725): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 5717): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 5717): Soft error
E/BooksSync( 5717): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5717): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 5717): Sync error
E/BooksSync( 5717): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5717): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 5717): Finished books sync
,D/SyncManager( 1016): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 209405, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1016): mCursor = null
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 300
,I/Atfwd_Sendcmd(  315): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  315): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4246, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged,
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1405): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1405): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5468): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5468): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4247, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate,
V/EmergencyMode( 1405): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1405): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 5468): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5468): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,V/AlarmManager( 1016): waitForAlarm result :8
,E/Watchdog( 1016): !@Sync 7
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 180s ago
,D/SSRM:n  ( 1016): SIOP:: AP = 290,
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4246, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging,
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1016): Plugged
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
V/EmergencyMode( 1405): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1405): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5468): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5468): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  288): DCD OFF,
,V/AlarmManager( 1016): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  288): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4247, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1405): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1405): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5468): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5468): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1016): SIOP:: AP = 290,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1016): !@Sync 8,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290,
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 4,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 225s ago
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290,
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,V/AlarmManager( 1016): waitForAlarm result :8
,E/Watchdog( 1016): !@Sync 9,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService( 1016): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1016): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1016): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1016): initializing...
,I/TLC_TIMA_PKM_initialize( 1016): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1016): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1016): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1016): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1016): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication( 1016): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1016): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1016): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1016): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1016): Loaded image: APP id = 11
,I/TZ: qc_tlc_communication( 1016): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1016): Trustlet response is completed
,E/SMD     (  288): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4243, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1405): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1405): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5468): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5468): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1016): !@Sync 10,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  288): DCD OFF
,I/Atfwd_Sendcmd(  315): AtCmdFwd service not ready - Exhausted retry attempts - :6
,I/Atfwd_Daemon(  315): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 275s ago
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4242, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 1016): stay LED for charging
,I/MotionRecognitionService( 1016): Plugged
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1405): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1405): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5468): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5468): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  288): DCD OFF

```
